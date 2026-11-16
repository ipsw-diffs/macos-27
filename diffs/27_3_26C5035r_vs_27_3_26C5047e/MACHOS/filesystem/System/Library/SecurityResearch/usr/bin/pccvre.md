## pccvre

> `/System/Library/SecurityResearch/usr/bin/pccvre`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-274.60.2.0.0
-  __TEXT.__text: 0x1a8ab0
+274.60.3.0.0
+  __TEXT.__text: 0x1a9c50
   __TEXT.__auth_stubs: 0x33c0
   __TEXT.__objc_stubs: 0xa40
   __TEXT.__objc_methlist: 0x184

   __TEXT.__swift5_mpenum: 0xf8
   __TEXT.__swift5_reflstr: 0x355d
   __TEXT.__swift5_fieldmd: 0x5990
-  __TEXT.__cstring: 0xa786
+  __TEXT.__cstring: 0xa7e6
   __TEXT.__swift5_assocty: 0x688
   __TEXT.__swift5_proto: 0x1390
   __TEXT.__swift5_types: 0x5ec

   __TEXT.__swift5_capture: 0x344
   __TEXT.__objc_methtype: 0x2c4
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__unwind_info: 0x6fa8
-  __TEXT.__eh_frame: 0xcd24
+  __TEXT.__unwind_info: 0x6f98
+  __TEXT.__eh_frame: 0xccb4
   __DATA_CONST.__const: 0x9840
   __DATA_CONST.__cfstring: 0x34c0
   __DATA_CONST.__objc_classlist: 0xd8

   - /usr/lib/swift/libswift_DarwinFoundation3.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 7100
+  Functions: 7097
   Symbols:   1376
   CStrings:  1608
 
CStrings:
+ "Path to a specific image to verify instead of the OS asset fetched by `release download` (for example, a host image you downloaded yourself)."
- "Path to a specific image to verify."
```
