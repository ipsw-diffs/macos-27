## afconvert

> `/usr/bin/afconvert`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 830.0.0.0.0
-  __TEXT.__text: 0x12408
+  __TEXT.__text: 0x1228c
   __TEXT.__auth_stubs: 0x960
   __TEXT.__objc_stubs: 0x80
   __TEXT.__gcc_except_tab: 0x1158

   __TEXT.__const: 0x126
   __TEXT.__oslogstring: 0x20
   __TEXT.__objc_methname: 0x32
-  __TEXT.__unwind_info: 0x710
+  __TEXT.__unwind_info: 0x7b8
   __DATA_CONST.__const: 0xfd8
   __DATA_CONST.__cfstring: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_10000257c : 104 -> 108
~ sub_100002a24 -> sub_100002a28 : 56 -> 44
~ sub_100002cdc -> sub_100002cd4 : 344 -> 340
~ sub_100003158 -> sub_10000314c : 132 -> 120
~ sub_100003200 -> sub_1000031e8 : 196 -> 192
~ sub_100003358 -> sub_10000333c : 252 -> 248
~ sub_1000045e8 -> sub_1000045c8 : 84 -> 72
~ sub_100004690 -> sub_100004664 : 48 -> 36
~ sub_1000046c0 -> sub_100004688 : 24 -> 12
~ sub_1000046d8 -> sub_100004694 : 44 -> 32
~ sub_100004b4c -> sub_100004afc : 56 -> 44
~ sub_10000585c -> sub_100005800 : 132 -> 120
~ sub_1000058e0 -> sub_100005878 : 424 -> 412
~ sub_10000624c -> sub_1000061d8 : 156 -> 144
~ sub_1000072d0 -> sub_100007250 : 1184 -> 1172
~ sub_100007770 -> sub_1000076e4 : 76 -> 64
~ sub_1000077bc -> sub_100007724 : 1552 -> 1548
~ sub_1000087d8 -> sub_10000873c : 124 -> 112
~ sub_10000893c -> sub_100008894 : 556 -> 544
~ sub_100008cfc -> sub_100008c48 : 152 -> 140
~ sub_100009738 -> sub_100009678 : 344 -> 332
~ sub_100009c1c -> sub_100009b50 : 740 -> 736
~ sub_100009f00 -> sub_100009e30 : 136 -> 124
~ sub_100009f88 -> sub_100009eac : 128 -> 116
~ sub_10000a6a8 -> sub_10000a5c0 : 552 -> 540
~ sub_10000a8d0 -> sub_10000a7dc : 380 -> 368
~ sub_10000b910 -> sub_10000b810 : 116 -> 104
~ sub_10000b984 -> sub_10000b878 : 1876 -> 1868
~ sub_10000e2c4 -> sub_10000e1b0 : 56 -> 44
~ sub_10000e484 -> sub_10000e364 : 56 -> 44
~ sub_10000e680 -> sub_10000e554 : 196 -> 192
~ sub_10000e880 -> sub_10000e750 : 428 -> 424
~ sub_10000ebbc -> sub_10000ea88 : 452 -> 436
~ sub_10000f22c -> sub_10000f0e8 : 280 -> 276
~ sub_10000f528 -> sub_10000f3e0 : 1360 -> 1368
~ sub_100010690 -> sub_100010550 : 152 -> 140
~ sub_1000107fc -> sub_1000106b0 : 56 -> 44
~ sub_100011934 -> sub_1000117dc : 68 -> 56
~ sub_100012158 -> sub_100011ff4 : 56 -> 44
~ sub_100012488 -> sub_100012318 : 264 -> 252
```
