## ioupsd

> `/usr/libexec/ioupsd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

-2043.0.47.0.3
-  __TEXT.__text: 0x38e8
+2043.1.1.0.0
+  __TEXT.__text: 0x38b8
   __TEXT.__auth_stubs: 0x600
   __TEXT.__objc_stubs: 0x100
   __TEXT.__cstring: 0x403

   __TEXT.__oslogstring: 0x21c
   __TEXT.__dlopen_cstrs: 0x5c
   __TEXT.__objc_methname: 0x98
-  __TEXT.__unwind_info: 0x110
+  __TEXT.__unwind_info: 0x150
   __DATA_CONST.__const: 0x140
   __DATA_CONST.__cfstring: 0x560
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_10000131c : 156 -> 144
~ sub_10000325c -> sub_100003250 : 240 -> 216
~ sub_1000037f8 -> sub_1000037d4 : 256 -> 244
```
