## tiffutil

> `/usr/bin/tiffutil`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 365.0.0.0.0
-  __TEXT.__text: 0x3c68
+  __TEXT.__text: 0x3c08
   __TEXT.__auth_stubs: 0x380
   __TEXT.__objc_stubs: 0x200
   __TEXT.__const: 0x119
   __TEXT.__cstring: 0x1bd6
   __TEXT.__gcc_except_tab: 0x78
   __TEXT.__objc_methname: 0x122
-  __TEXT.__unwind_info: 0x108
+  __TEXT.__unwind_info: 0x138
   __DATA_CONST.__const: 0x6a8
   __DATA_CONST.__cfstring: 0xc0
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_10000202c : 88 -> 76
~ sub_100002084 -> sub_100002078 : 348 -> 336
~ sub_1000025f0 -> sub_1000025d8 : 156 -> 144
~ sub_10000439c -> sub_100004378 : 124 -> 112
~ sub_100004418 -> sub_1000043e8 : 36 -> 24
~ sub_10000443c -> sub_100004400 : 36 -> 24
~ sub_100004474 -> sub_10000442c : 76 -> 64
~ sub_1000044c0 -> sub_10000446c : 76 -> 64
```
