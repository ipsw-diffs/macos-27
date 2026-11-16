## btmdiagnose

> `/usr/bin/btmdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-371.2.2.0.0
-  __TEXT.__text: 0x25404
+371.2.4.0.0
+  __TEXT.__text: 0x25de4
   __TEXT.__auth_stubs: 0xa30
-  __TEXT.__objc_stubs: 0x3680
+  __TEXT.__objc_stubs: 0x36a0
   __TEXT.__objc_methlist: 0x1724
   __TEXT.__const: 0x122
   __TEXT.__gcc_except_tab: 0x418
-  __TEXT.__objc_methname: 0x4272
+  __TEXT.__objc_methname: 0x428f
   __TEXT.__cstring: 0x1813
-  __TEXT.__oslogstring: 0x1e18
+  __TEXT.__oslogstring: 0x1e6b
   __TEXT.__objc_classname: 0x176
   __TEXT.__objc_methtype: 0xfb1
   __TEXT.__swift5_entry: 0x8

   __DATA_CONST.__got: 0x2a0
   __DATA_CONST.__auth_ptr: 0x48
   __DATA.__objc_const: 0x2370
-  __DATA.__objc_selrefs: 0x11f0
+  __DATA.__objc_selrefs: 0x11f8
   __DATA.__objc_ivar: 0x170
   __DATA.__objc_data: 0x3c0
   __DATA.__data: 0x430

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_DarwinFoundation2.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 681
+  Functions: 682
   Symbols:   270
-  CStrings:  1318
+  CStrings:  1320
 
CStrings:
+ "updateGlobalDataContainer: container '%{public}@' doesn't match record '%{public}@"
+ "validateWithRequirement:url:"
```
