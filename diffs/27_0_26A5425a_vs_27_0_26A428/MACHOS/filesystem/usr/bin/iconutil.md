## iconutil

> `/usr/bin/iconutil`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 792.100.0.0.0
-  __TEXT.__text: 0x18e8
+  __TEXT.__text: 0x18b8
   __TEXT.__auth_stubs: 0x130
   __TEXT.__objc_stubs: 0x5a0
   __TEXT.__const: 0x38
   __TEXT.__cstring: 0x314
   __TEXT.__objc_methname: 0x3a8
-  __TEXT.__unwind_info: 0x88
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__cfstring: 0x120
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000b48 : 468 -> 456
~ sub_100000d1c -> sub_100000d10 : 136 -> 124
~ sub_1000023c0 -> sub_1000023a8 : 32 -> 20
~ sub_1000023e0 -> sub_1000023bc : 32 -> 20
```
