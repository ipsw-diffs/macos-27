## afscexpand

> `/usr/bin/afscexpand`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 182.40.4.0.0
-  __TEXT.__text: 0x15b3c
+  __TEXT.__text: 0x15bbc
   __TEXT.__auth_stubs: 0x320
   __TEXT.__const: 0x238a8
   __TEXT.__cstring: 0xc29
Functions:
~ sub_10000e700 : 2536 -> 2612
~ sub_10000f0e8 -> sub_10000f134 : 2824 -> 2804
~ sub_10000fdbc -> sub_10000fdf4 : 800 -> 812
~ sub_1000100dc -> sub_100010120 : 444 -> 456
~ sub_100010298 -> sub_1000102e8 : 880 -> 892
~ sub_100010608 -> sub_100010664 : 520 -> 532
~ sub_100010810 -> sub_100010878 : 824 -> 836
~ sub_100010b48 -> sub_100010bbc : 468 -> 480
```
