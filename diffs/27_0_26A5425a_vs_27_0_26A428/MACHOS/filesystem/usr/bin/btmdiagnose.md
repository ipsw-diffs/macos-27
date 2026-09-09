## btmdiagnose

> `/usr/bin/btmdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 371.0.0.0.0
-  __TEXT.__text: 0x25a20
+  __TEXT.__text: 0x25104
   __TEXT.__auth_stubs: 0xa20
   __TEXT.__objc_stubs: 0x3620
   __TEXT.__objc_methlist: 0x171c

   __TEXT.__objc_methtype: 0xfb1
   __TEXT.__swift5_entry: 0x8
   __TEXT.__swift5_typeref: 0x5a
-  __TEXT.__unwind_info: 0x768
+  __TEXT.__unwind_info: 0x980
   __TEXT.__eh_frame: 0x260
   __DATA_CONST.__const: 0x800
   __DATA_CONST.__cfstring: 0x1b40

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_DarwinFoundation2.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 681
+  Functions: 679
   Symbols:   269
   CStrings:  1309
 
```
