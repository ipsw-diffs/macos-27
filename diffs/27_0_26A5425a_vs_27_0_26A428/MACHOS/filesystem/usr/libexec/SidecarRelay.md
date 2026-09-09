## SidecarRelay

> `/usr/libexec/SidecarRelay`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 400.42.0.0.0
-  __TEXT.__text: 0x8cccc
+  __TEXT.__text: 0x88c50
   __TEXT.__auth_stubs: 0x1a80
   __TEXT.__objc_stubs: 0x19c0
   __TEXT.__objc_methlist: 0xab0

   __TEXT.__swift5_capture: 0x3e60
   __TEXT.__oslogstring: 0x2c31
   __TEXT.__cstring: 0x1669
-  __TEXT.__unwind_info: 0x1d60
+  __TEXT.__unwind_info: 0x2698
   __TEXT.__eh_frame: 0x1058
   __DATA_CONST.__const: 0xc1e8
   __DATA_CONST.__cfstring: 0x80

   - /usr/lib/swift/libswift_DarwinFoundation3.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4622
+  Functions: 4627
   Symbols:   736
   CStrings:  874
 
```
