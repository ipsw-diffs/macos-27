## managedappdistributiond

> `/System/Library/Frameworks/ManagedAppDistribution.framework/Support/managedappdistributiond`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_protos`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-4.1.15.0.0
-  __TEXT.__text: 0x4460b4
-  __TEXT.__auth_stubs: 0x57b0
-  __TEXT.__objc_stubs: 0x4140
+4.1.15.1.0
+  __TEXT.__text: 0x443bb8
+  __TEXT.__auth_stubs: 0x5710
+  __TEXT.__objc_stubs: 0x40c0
   __TEXT.__objc_methlist: 0xf28
-  __TEXT.__const: 0x25b10
+  __TEXT.__const: 0x25b20
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__cstring: 0x5e9d
-  __TEXT.__oslogstring: 0xe0b2
+  __TEXT.__cstring: 0x5e8d
+  __TEXT.__oslogstring: 0xde62
   __TEXT.__swift5_typeref: 0x5dc4
   __TEXT.__objc_classname: 0x1cd6
   __TEXT.__objc_methtype: 0x17bc

   __TEXT.__constg_swiftt: 0x73f4
   __TEXT.__swift5_proto: 0x1850
   __TEXT.__swift5_types: 0x964
-  __TEXT.__objc_methname: 0x5f45
+  __TEXT.__objc_methname: 0x5ef5
   __TEXT.__swift_as_entry: 0xab8
   __TEXT.__swift_as_ret: 0x11b4
   __TEXT.__swift_as_cont: 0x2d00
   __TEXT.__swift5_protos: 0x88
-  __TEXT.__unwind_info: 0x111c8
-  __TEXT.__eh_frame: 0x2f69c
-  __DATA_CONST.__const: 0x1fab8
+  __TEXT.__unwind_info: 0x111b0
+  __TEXT.__eh_frame: 0x2f6b4
+  __DATA_CONST.__const: 0x1fa38
   __DATA_CONST.__cfstring: 0x60
   __DATA_CONST.__objc_classlist: 0x2f0
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x138
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0xa8
-  __DATA_CONST.__auth_got: 0x2be8
-  __DATA_CONST.__got: 0x1848
-  __DATA_CONST.__auth_ptr: 0x1828
+  __DATA_CONST.__auth_got: 0x2b98
+  __DATA_CONST.__got: 0x1838
+  __DATA_CONST.__auth_ptr: 0x1830
   __DATA.__objc_const: 0x7238
-  __DATA.__objc_selrefs: 0x1460
+  __DATA.__objc_selrefs: 0x1440
   __DATA.__objc_data: 0x1cd0
   __DATA.__data: 0x10408
   __DATA.__bss: 0x2c2b8

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13994
-  Symbols:   2613
-  CStrings:  2799
+  Functions: 13989
+  Symbols:   2601
+  CStrings:  2786
 
Symbols:
- _$s24StorageContainersPrivate9ContainerC10AttributesV15protectedSystem9ownershipA2E9OwnershipO_tFZ
- _$s24StorageContainersPrivate9ContainerC10AttributesV9OwnershipO8explicityAGs6UInt32V_AJ6System15FilePermissionsVtcAGmFWC
- _$s24StorageContainersPrivate9ContainerC10AttributesV9OwnershipOMa
- _$s24StorageContainersPrivate9ContainerC2of10identifier7persona7options4partA2C10AttributesV_SSSgAC7PersonaOSayAA5QueryC7OptionsOGAC4PartOtKcfC
- _$s24StorageContainersPrivate9ContainerC5OwnedC11grantAccess8requiredySb_tKF
- _$s24StorageContainersPrivate9ContainerC5OwnedC2of7personaAeC10AttributesV_AC7PersonaOtKcfc
- _$s24StorageContainersPrivate9ContainerC5OwnedC4path6System8FilePathVSgvg
- _$s24StorageContainersPrivate9ContainerC5OwnedCMa
- _$s24StorageContainersPrivate9ContainerC7PersonaO14currentVoucheryA2EmFWC
- _$s24StorageContainersPrivate9ContainerCMa
- _getegid
- _geteuid
CStrings:
+ "ManagedAppDistributionDaemon/Dependencies.swift"
- "Deleted legacy container for group.%{public}s"
- "Failed to delete legacy container for group.%{public}s: %{public}@"
- "Failed to migrate legacy file %{public}s: %{public}@"
- "Legacy container for group.%{public}s has management state, migrating database files"
- "Legacy container for group.%{public}s has no management state, deleting without migrating"
- "Migrated legacy container files: %{public}s"
- "No legacy container found for group.%{public}s, not migrating"
- "Protected system container exists, no legacy container migration will take place"
- "close"
- "copyItemAtURL:toURL:error:"
- "countForProperty:predicate:onConnection:"
- "database.sqlite-shm"
- "database.sqlite-wal"
- "setReadOnly:"
```
