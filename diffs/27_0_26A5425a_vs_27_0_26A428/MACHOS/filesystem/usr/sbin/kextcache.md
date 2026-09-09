## kextcache

> `/usr/sbin/kextcache`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 784.0.0.0.0
-  __TEXT.__text: 0x4a050
+  __TEXT.__text: 0x49af0
   __TEXT.__auth_stubs: 0x1be0
   __TEXT.__objc_stubs: 0x6a0
   __TEXT.__const: 0xe40

   __TEXT.__oslogstring: 0x152
   __TEXT.__gcc_except_tab: 0x628
   __TEXT.__objc_methname: 0x482
-  __TEXT.__unwind_info: 0x9f0
+  __TEXT.__unwind_info: 0xc00
   __TEXT.__eh_frame: 0x7c
   __DATA_CONST.__const: 0x2f0
   __DATA_CONST.__cfstring: 0x3d00

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
   - /usr/lib/system/libkxld.dylib
-  Functions: 662
+  Functions: 661
   Symbols:   528
   CStrings:  1802
 
```
