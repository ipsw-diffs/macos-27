## dmd

> `/usr/libexec/dmd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 261.1.5.0.0
-  __TEXT.__text: 0x615d0
+  __TEXT.__text: 0x5f690
   __TEXT.__auth_stubs: 0xa00
   __TEXT.__objc_stubs: 0x9a00
   __TEXT.__objc_methlist: 0x6724

   __TEXT.__oslogstring: 0x7049
   __TEXT.__gcc_except_tab: 0xc04
   __TEXT.__ustring: 0x498
-  __TEXT.__unwind_info: 0x1a30
+  __TEXT.__unwind_info: 0x2068
   __DATA_CONST.__const: 0x1880
   __DATA_CONST.__cfstring: 0x4940
   __DATA_CONST.__objc_classlist: 0x638
```
