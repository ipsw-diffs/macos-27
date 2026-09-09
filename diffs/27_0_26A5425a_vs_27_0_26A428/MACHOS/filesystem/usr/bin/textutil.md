## textutil

> `/usr/bin/textutil`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 365.0.0.0.0
-  __TEXT.__text: 0x2d48
+  __TEXT.__text: 0x2d00
   __TEXT.__auth_stubs: 0x1d0
   __TEXT.__objc_stubs: 0x980
   __TEXT.__objc_methlist: 0x2c

   __TEXT.__objc_methname: 0x6ea
   __TEXT.__objc_methtype: 0x3c
   __TEXT.__cstring: 0x14ad
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xb8
   __DATA_CONST.__cfstring: 0x700
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000b98 : 60 -> 48
~ sub_100000c40 -> sub_100000c34 : 200 -> 188
~ sub_100000d08 -> sub_100000cf0 : 200 -> 188
~ sub_100000e2c -> sub_100000e08 : 508 -> 496
~ sub_100001028 -> sub_100000ff8 : 684 -> 672
~ sub_10000379c -> sub_100003760 : 28 -> 16
```
