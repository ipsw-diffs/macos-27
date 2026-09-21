## findmylocateagent

> `/usr/libexec/findmylocateagent`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_entry`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__got`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-141.21.6.16.15
-  __TEXT.__text: 0x44e0a0
-  __TEXT.__auth_stubs: 0x4f60
+141.21.6.16.16
+  __TEXT.__text: 0x458d48
+  __TEXT.__auth_stubs: 0x4f80
   __TEXT.__objc_stubs: 0x1840
   __TEXT.__objc_methlist: 0xba4
-  __TEXT.__const: 0x1be98
-  __TEXT.__cstring: 0x9bb2
-  __TEXT.__swift5_typeref: 0x6024
-  __TEXT.__constg_swiftt: 0x5c2c
-  __TEXT.__swift5_builtin: 0x118
-  __TEXT.__swift5_reflstr: 0x6f1d
-  __TEXT.__swift5_fieldmd: 0x7ea0
+  __TEXT.__const: 0x1c178
+  __TEXT.__cstring: 0x9cd2
+  __TEXT.__swift5_typeref: 0x6108
+  __TEXT.__constg_swiftt: 0x5d08
+  __TEXT.__swift5_builtin: 0x12c
+  __TEXT.__swift5_reflstr: 0x6ffd
+  __TEXT.__swift5_fieldmd: 0x7fa4
   __TEXT.__swift5_assocty: 0x880
-  __TEXT.__swift5_proto: 0x14b8
-  __TEXT.__swift5_types: 0x6b4
+  __TEXT.__swift5_proto: 0x14bc
+  __TEXT.__swift5_types: 0x6c8
   __TEXT.__objc_classname: 0xeda
-  __TEXT.__objc_methname: 0x3ce5
+  __TEXT.__objc_methname: 0x3db5
   __TEXT.__objc_methtype: 0xd30
   __TEXT.__swift5_protos: 0x48
-  __TEXT.__swift5_mpenum: 0x40
-  __TEXT.__oslogstring: 0x12ce6
-  __TEXT.__swift_as_entry: 0x1328
-  __TEXT.__swift_as_ret: 0x20ac
-  __TEXT.__swift_as_cont: 0x3740
-  __TEXT.__swift5_capture: 0x3d54
+  __TEXT.__swift5_mpenum: 0x48
+  __TEXT.__oslogstring: 0x12ea6
+  __TEXT.__swift_as_entry: 0x1360
+  __TEXT.__swift_as_ret: 0x2120
+  __TEXT.__swift_as_cont: 0x37c8
+  __TEXT.__swift5_capture: 0x3df8
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__unwind_info: 0x14230
-  __TEXT.__eh_frame: 0x3bb20
-  __DATA_CONST.__const: 0x13c90
+  __TEXT.__unwind_info: 0x13d98
+  __TEXT.__eh_frame: 0x3c4f8
+  __DATA_CONST.__const: 0x13fb0
   __DATA_CONST.__objc_classlist: 0x1d0
   __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0xa0
   __DATA_CONST.__linkguard: 0x33
-  __DATA_CONST.__auth_got: 0x27b8
+  __DATA_CONST.__auth_got: 0x27c8
   __DATA_CONST.__got: 0x1a10
-  __DATA_CONST.__auth_ptr: 0x1600
-  __DATA.__objc_const: 0x4f90
+  __DATA_CONST.__auth_ptr: 0x1630
+  __DATA.__objc_const: 0x4fd0
   __DATA.__objc_selrefs: 0xa08
   __DATA.__objc_data: 0xbf0
-  __DATA.__data: 0xc800
-  __DATA.__bss: 0x28300
-  __DATA.__common: 0x1300
+  __DATA.__data: 0xc9c0
+  __DATA.__bss: 0x28380
+  __DATA.__common: 0x1318
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppIntents.framework/Versions/A/AppIntents
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 14406
-  Symbols:   2474
-  CStrings:  3039
+  Functions: 14581
+  Symbols:   2477
+  CStrings:  3054
 
Symbols:
+ _$sSL2leoiySbx_xtFZTj
+ _$ss12StaticStringV11descriptionSSvg
+ _$ss12StaticStringVMn
CStrings:
+ "$__lazy_storage_$_cacheExpiryScheduler"
+ "%{public}s expired Friend:%{private,mask.hash}s\nexpiresByGroupId:%{private,mask.hash}s\nlocationSharingState:%{private,mask.hash}s"
+ "%{public}s missing XPC alarm event handler"
+ "%{public}s not eligible, since we have non-nil, non-stale serverSettings already."
+ "%{public}s: No LocalStorageService; skipping donation"
+ "Elapsed: %{public}s"
+ "Expiry alarm fired: %{public}s"
+ "Force refreshClient, since server settings are nil or stale in local DB."
+ "LabelStore: labels changed for %{public}ld users, re-donating Person Entities"
+ "No upcoming expiry; alarm cleared"
+ "Re-arming after %{public}s"
+ "Waking at %{public}s for %{public}s"
+ "_retrieveAndDonatePersonEntities(impactedUsers:)"
+ "com.apple.findmy.findmylocate.ExpiryAlarm"
+ "determineIfAnyUpdatesNeeded(previousMeDevice:previousShareMyLocationState:previousFriendshipRequestsAllowed:)"
+ "expiryAlarmDebounceTask"
+ "registerExpiryAlarmHandler()"
+ "updateLocalStorage(with:)"
- "%{public}s expired Friend:%{private,mask.hash}s\nexpiresByGroupId:%{private,mask.hash}s"
- "%{public}s not eligible, since we have non-nil serverSettings already."
- "Force refreshClient, since we have nil server settings in local DB."
```
