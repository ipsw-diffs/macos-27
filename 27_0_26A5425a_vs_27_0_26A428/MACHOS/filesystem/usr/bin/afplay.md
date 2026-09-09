## afplay

> `/usr/bin/afplay`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA.__objc_selrefs`

```diff

 830.0.0.0.0
-  __TEXT.__text: 0x3824
+  __TEXT.__text: 0x3800
   __TEXT.__auth_stubs: 0x460
   __TEXT.__objc_stubs: 0x80
   __TEXT.__const: 0x7e

   __TEXT.__cstring: 0x92f
   __TEXT.__oslogstring: 0x74
   __TEXT.__objc_methname: 0x32
-  __TEXT.__unwind_info: 0x138
+  __TEXT.__unwind_info: 0x140
   __DATA_CONST.__const: 0xe8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x240
Functions:
~ sub_1000037f4 : 32 -> 20
~ sub_100003b04 -> sub_100003af8 : 56 -> 44
~ sub_100003ea8 -> sub_100003e90 : 68 -> 56
```
