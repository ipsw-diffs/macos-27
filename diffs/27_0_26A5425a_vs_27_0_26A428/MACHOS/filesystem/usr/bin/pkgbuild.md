## pkgbuild

> `/usr/bin/pkgbuild`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 883.0.0.0.0
-  __TEXT.__text: 0x6dcc
+  __TEXT.__text: 0x6cf0
   __TEXT.__auth_stubs: 0x210
   __TEXT.__objc_stubs: 0x2020
   __TEXT.__objc_methlist: 0x668

   __TEXT.__objc_classname: 0x5c
   __TEXT.__objc_methtype: 0x1d3
   __TEXT.__gcc_except_tab: 0x90
-  __TEXT.__unwind_info: 0x178
+  __TEXT.__unwind_info: 0x208
   __DATA_CONST.__const: 0x210
   __DATA_CONST.__cfstring: 0x13c0
   __DATA_CONST.__objc_classlist: 0x18
Functions:
~ sub_100000d08 : 216 -> 204
~ sub_100001b28 -> sub_100001b1c : 28 -> 16
~ sub_100001ef8 -> sub_100001ee0 : 228 -> 216
~ sub_1000029b8 -> sub_100002994 : 252 -> 240
~ sub_100002c9c -> sub_100002c6c : 728 -> 724
~ sub_1000038e4 -> sub_1000038b0 : 76 -> 64
~ sub_10000440c -> sub_1000043cc : 268 -> 256
~ sub_100004518 -> sub_1000044cc : 112 -> 100
~ sub_100004588 -> sub_100004530 : 92 -> 80
~ sub_100005558 -> sub_1000054f4 : 96 -> 84
~ sub_1000055b8 -> sub_100005548 : 80 -> 68
~ sub_100005608 -> sub_10000558c : 264 -> 240
~ sub_100006b28 -> sub_100006a94 : 52 -> 40
~ sub_100006b5c -> sub_100006abc : 56 -> 44
~ sub_100006b94 -> sub_100006ae8 : 56 -> 44
~ sub_100006bcc -> sub_100006b14 : 56 -> 44
~ sub_100006e4c -> sub_100006d88 : 72 -> 60
~ sub_1000073b4 -> sub_1000072e4 : 108 -> 96
```
