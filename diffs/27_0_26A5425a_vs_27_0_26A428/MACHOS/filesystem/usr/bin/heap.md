## heap

> `/usr/bin/heap`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 64578.57.1.0.0
-  __TEXT.__text: 0xaef4
+  __TEXT.__text: 0xaca0
   __TEXT.__auth_stubs: 0x840
   __TEXT.__objc_stubs: 0x1940
   __TEXT.__objc_methlist: 0x230

   __TEXT.__objc_methtype: 0x155
   __TEXT.__gcc_except_tab: 0x430
   __TEXT.__oslogstring: 0x749
-  __TEXT.__unwind_info: 0x220
+  __TEXT.__unwind_info: 0x2c8
   __DATA_CONST.__const: 0x790
   __DATA_CONST.__cfstring: 0x9a0
   __DATA_CONST.__objc_classlist: 0x18
```
