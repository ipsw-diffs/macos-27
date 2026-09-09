## afinfo

> `/usr/bin/afinfo`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 830.0.0.0.0
-  __TEXT.__text: 0x76d0
+  __TEXT.__text: 0x762c
   __TEXT.__auth_stubs: 0x610
   __TEXT.__objc_stubs: 0x80
   __TEXT.__gcc_except_tab: 0x63c
   __TEXT.__cstring: 0x1dae
   __TEXT.__const: 0xa8
   __TEXT.__objc_methname: 0x32
-  __TEXT.__unwind_info: 0x2a0
+  __TEXT.__unwind_info: 0x2c8
   __DATA_CONST.__const: 0xe8
   __DATA_CONST.__cfstring: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100001938 : 10464 -> 10372
~ sub_100005024 -> sub_100004fc8 : 448 -> 436
~ sub_1000071a8 -> sub_100007140 : 120 -> 108
~ sub_100007478 -> sub_100007404 : 124 -> 112
~ sub_100007568 -> sub_1000074e8 : 352 -> 340
~ sub_100007a80 -> sub_1000079f4 : 68 -> 56
~ sub_100008078 -> sub_100007fe0 : 120 -> 108
```
