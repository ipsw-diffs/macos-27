## vim

> `/usr/bin/vim`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 167.0.0.0.0
-  __TEXT.__text: 0x23fd78
+  __TEXT.__text: 0x23adf8
   __TEXT.__auth_stubs: 0xea0
   __TEXT.__objc_stubs: 0x260
   __TEXT.__const: 0xb290
   __TEXT.__cstring: 0x1815b
   __TEXT.__objc_methname: 0x164
-  __TEXT.__unwind_info: 0x4d40
+  __TEXT.__unwind_info: 0x6100
   __TEXT.__eh_frame: 0x50
   __DATA_CONST.__const: 0x113b0
   __DATA_CONST.__cfstring: 0x80

   - /usr/lib/libiconv.2.dylib
   - /usr/lib/libncurses.5.4.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 6621
+  Functions: 6623
   Symbols:   257
   CStrings:  7406
 
CStrings:
+ "Aug  8 2026 16:52:02"
- "Aug 10 2026 01:21:01"
```
