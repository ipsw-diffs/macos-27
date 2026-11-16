## toolkitd

> `/usr/libexec/toolkitd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-5203.0.1.0.0
-  __TEXT.__text: 0x9d6a8
-  __TEXT.__auth_stubs: 0x2ae0
-  __TEXT.__objc_stubs: 0x1a40
+5206.0.5.0.0
+  __TEXT.__text: 0x9dc80
+  __TEXT.__auth_stubs: 0x2b10
+  __TEXT.__objc_stubs: 0x1a20
   __TEXT.__objc_methlist: 0x13c
-  __TEXT.__const: 0x479c
+  __TEXT.__const: 0x477c
   __TEXT.__objc_classname: 0x17d
-  __TEXT.__objc_methname: 0x1328
+  __TEXT.__objc_methname: 0x1318
   __TEXT.__objc_methtype: 0x1fe
-  __TEXT.__constg_swiftt: 0xd38
+  __TEXT.__constg_swiftt: 0xd44
   __TEXT.__swift5_typeref: 0x17f1
-  __TEXT.__swift5_reflstr: 0x10a4
-  __TEXT.__swift5_fieldmd: 0x10d8
+  __TEXT.__swift5_reflstr: 0x10b4
+  __TEXT.__swift5_fieldmd: 0x10e4
   __TEXT.__cstring: 0x223d
-  __TEXT.__oslogstring: 0x18ec
+  __TEXT.__oslogstring: 0x199c
   __TEXT.__swift5_capture: 0xce0
   __TEXT.__swift5_builtin: 0xdc
   __TEXT.__swift5_assocty: 0x330
   __TEXT.__swift5_proto: 0x1c4
   __TEXT.__swift5_types: 0x148
-  __TEXT.__swift_as_entry: 0x1dc
+  __TEXT.__swift_as_entry: 0x1d8
   __TEXT.__swift_as_cont: 0x414
-  __TEXT.__swift_as_ret: 0x228
+  __TEXT.__swift_as_ret: 0x224
   __TEXT.__swift5_entry: 0x8
   __TEXT.__swift5_mpenum: 0xc8
   __TEXT.__swift5_protos: 0x28
-  __TEXT.__unwind_info: 0x2428
-  __TEXT.__eh_frame: 0x5fd8
-  __DATA_CONST.__const: 0x42a0
+  __TEXT.__unwind_info: 0x2440
+  __TEXT.__eh_frame: 0x5f90
+  __DATA_CONST.__const: 0x4220
   __DATA_CONST.__objc_classlist: 0x38
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__auth_got: 0x1578
+  __DATA_CONST.__auth_got: 0x1590
   __DATA_CONST.__got: 0xbe0
   __DATA_CONST.__auth_ptr: 0x760
   __DATA.__objc_const: 0x780
-  __DATA.__objc_selrefs: 0x720
+  __DATA.__objc_selrefs: 0x718
   __DATA.__objc_data: 0x50
-  __DATA.__data: 0x1cb8
+  __DATA.__data: 0x1d50
   __DATA.__bss: 0x24a0
   __DATA.__common: 0x2b0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3007
-  Symbols:   1217
+  Functions: 2991
+  Symbols:   1220
   CStrings:  596
 
Symbols:
+ _$s11WorkflowKit04ToolB14IndexingPolicyC31shouldPreserveExistingFlowTools08existingiC5Count09generatedicL024removedContainersIsEmpty21hasIncompleteMetadataSbSi_SiS2btFZ
+ _$s7ToolKit0A8DatabaseC8AccessorC09localFlowA5CountSiyKF
+ _$sSo25LNActionParameterMetadataC11WorkflowKitE40dynamicOptionsProviderRestrictionContext14toolIdentifier12parameterKey5query06bundleL004ToolE00iJ0OSgSS_SSSo07LNQueryC0CSgSStF
CStrings:
+ "Preserving %ld existing FlowTool(s): this pass regenerated only %ld. Skipping destructive FlowTool replacement so a later reindex can regenerate once indexing is complete."
- "dynamicOptionsSupport"
```
