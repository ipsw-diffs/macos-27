## modelmanagerd

> `/usr/libexec/modelmanagerd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_assocty`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-714.60.14.0.0
-  __TEXT.__text: 0x1b4974
+714.60.17.0.0
+  __TEXT.__text: 0x1b4554
   __TEXT.__auth_stubs: 0x3df0
   __TEXT.__objc_stubs: 0x700
   __TEXT.__objc_methlist: 0x1c0
-  __TEXT.__const: 0x6956
-  __TEXT.__swift5_typeref: 0x2995
-  __TEXT.__cstring: 0x2020
-  __TEXT.__oslogstring: 0xa599
-  __TEXT.__swift5_capture: 0x270c
+  __TEXT.__const: 0x6926
+  __TEXT.__swift5_typeref: 0x2975
+  __TEXT.__cstring: 0x2000
+  __TEXT.__oslogstring: 0xa4f9
+  __TEXT.__swift5_capture: 0x26d0
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__constg_swiftt: 0x2f14
+  __TEXT.__constg_swiftt: 0x2ec4
   __TEXT.__swift5_builtin: 0x3c
-  __TEXT.__swift5_reflstr: 0x28a3
-  __TEXT.__swift5_fieldmd: 0x22e0
+  __TEXT.__swift5_reflstr: 0x2863
+  __TEXT.__swift5_fieldmd: 0x22bc
   __TEXT.__swift5_types: 0x1d0
   __TEXT.__objc_classname: 0xb90
-  __TEXT.__objc_methname: 0x1b03
+  __TEXT.__objc_methname: 0x1ad3
   __TEXT.__objc_methtype: 0x395
-  __TEXT.__swift_as_entry: 0x97c
-  __TEXT.__swift_as_ret: 0xb3c
-  __TEXT.__swift_as_cont: 0x12f4
+  __TEXT.__swift_as_entry: 0x974
+  __TEXT.__swift_as_ret: 0xb38
+  __TEXT.__swift_as_cont: 0x12d0
   __TEXT.__swift5_proto: 0x314
   __TEXT.__swift5_protos: 0x94
   __TEXT.__swift5_assocty: 0x1b8
-  __TEXT.__unwind_info: 0x7c50
-  __TEXT.__eh_frame: 0x1729c
-  __DATA_CONST.__const: 0x8800
+  __TEXT.__unwind_info: 0x7bf8
+  __TEXT.__eh_frame: 0x17154
+  __DATA_CONST.__const: 0x87b8
   __DATA_CONST.__objc_classlist: 0x1c0
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__auth_got: 0x1f00
   __DATA_CONST.__got: 0xf90
   __DATA_CONST.__auth_ptr: 0xda0
-  __DATA.__objc_const: 0x4580
+  __DATA.__objc_const: 0x4520
   __DATA.__objc_selrefs: 0x2a0
   __DATA.__objc_data: 0x7a0
-  __DATA.__data: 0x6690
-  __DATA.__common: 0x6b0
+  __DATA.__data: 0x6620
+  __DATA.__common: 0x6a8
   __DATA.__bss: 0x52c0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices

   - /usr/lib/swift/libswift_DarwinFoundation3.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 9458
+  Functions: 9426
   Symbols:   1706
-  CStrings:  1251
+  CStrings:  1244
 
CStrings:
+ "Conclave bootstrap hit a terminated provider, retrying after its cleanup"
+ "Discovered %ld new extensions and removed %ld (%ld total)"
+ "onChange"
- "Discovered %ld new extensions and removed %ld"
- "Handling exclave unload for asset %s"
- "assertionRequestID"
- "bootstrapsInFlight"
- "markAsInactive removed jetsam floor (synthetic request %s)"
- "markAsInactive skipped — connection still in use (bootstrap in flight or sibling loaded)"
- "markAsInactive skipped — not currently active"
- "markAsInactive(connection:)"
- "onAssetDidUnload"
- "onUpdate"
```
