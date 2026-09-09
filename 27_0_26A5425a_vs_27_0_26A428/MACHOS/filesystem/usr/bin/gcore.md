## gcore

> `/usr/bin/gcore`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 1071.0.1.0.0
-  __TEXT.__text: 0xd580
+  __TEXT.__text: 0xd40c
   __TEXT.__auth_stubs: 0x840
   __TEXT.__const: 0xd9
   __TEXT.__cstring: 0x2b7e
   __TEXT.__oslogstring: 0xaa4
-  __TEXT.__unwind_info: 0x258
+  __TEXT.__unwind_info: 0x5d0
   __DATA_CONST.__const: 0x428
   __DATA_CONST.__auth_got: 0x420
   __DATA_CONST.__got: 0x60
Functions:
~ sub_10000212c : 504 -> 496
~ sub_1000025e4 -> sub_1000025dc : 112 -> 100
~ sub_100002840 -> sub_10000282c : 728 -> 716
~ sub_100002b18 -> sub_100002af8 : 100 -> 88
~ sub_100002b7c -> sub_100002b50 : 124 -> 112
~ sub_100002bfc -> sub_100002bc4 : 208 -> 196
~ sub_100002ccc -> sub_100002c88 : 60 -> 48
~ sub_100002dc4 -> sub_100002d74 : 28 -> 16
~ sub_1000038e0 -> sub_100003884 : 1408 -> 1404
~ sub_100004150 -> sub_1000040f0 : 96 -> 84
~ sub_1000052a4 -> sub_100005238 : 84 -> 72
~ sub_100005808 -> sub_100005790 : 984 -> 980
~ sub_100006470 -> sub_1000063f4 : 72 -> 60
~ sub_1000064b8 -> sub_100006430 : 72 -> 60
~ sub_100006500 -> sub_10000646c : 72 -> 60
~ sub_1000067f4 -> sub_100006754 : 92 -> 80
~ sub_100006850 -> sub_1000067a4 : 92 -> 80
~ sub_1000068ac -> sub_1000067f4 : 92 -> 80
~ sub_100006d80 -> sub_100006cbc : 288 -> 284
~ sub_100007530 -> sub_100007468 : 432 -> 428
~ sub_1000076e0 -> sub_100007614 : 388 -> 384
~ sub_10000787c -> sub_1000077ac : 28 -> 16
~ sub_100007898 -> sub_1000077bc : 32 -> 20
~ sub_1000078dc -> sub_1000077f4 : 104 -> 92
~ sub_100007944 -> sub_100007850 : 152 -> 140
~ sub_100007d50 -> sub_100007c50 : 248 -> 236
~ sub_1000080bc -> sub_100007fb0 : 56 -> 44
~ sub_100009980 -> sub_100009868 : 176 -> 164
~ sub_10000a1fc -> sub_10000a0d8 : 80 -> 68
~ sub_10000a24c -> sub_10000a11c : 68 -> 56
~ sub_10000a4c8 -> sub_10000a38c : 88 -> 76
~ sub_10000a520 -> sub_10000a3d8 : 108 -> 96
~ sub_10000a5cc -> sub_10000a478 : 20 -> 32
~ sub_10000a5e0 -> sub_10000a498 : 32 -> 20
~ sub_10000a630 -> sub_10000a4dc : 24 -> 12
~ sub_10000a978 -> sub_10000a818 : 172 -> 160
~ sub_10000af34 -> sub_10000adc8 : 92 -> 80
~ sub_10000b0e0 -> sub_10000af68 : 304 -> 308
```
