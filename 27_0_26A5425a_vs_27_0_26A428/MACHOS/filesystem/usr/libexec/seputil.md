## seputil

> `/usr/libexec/seputil`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 928.0.2.0.0
-  __TEXT.__text: 0x13d88
+  __TEXT.__text: 0x13890
   __TEXT.__auth_stubs: 0xa30
   __TEXT.__cstring: 0x5f15
   __TEXT.__const: 0x560
   __TEXT.__oslogstring: 0x6f
   __TEXT.__gcc_except_tab: 0x2a8
-  __TEXT.__unwind_info: 0x490
+  __TEXT.__unwind_info: 0x7a0
   __DATA_CONST.__const: 0x120
   __DATA_CONST.__cfstring: 0x100
   __DATA_CONST.__auth_got: 0x520
Functions:
~ sub_100000c38 : 204 -> 192
~ sub_100006e7c -> sub_100006e70 : 340 -> 344
~ sub_1000070a0 -> sub_100007098 : 664 -> 668
~ sub_100007790 -> sub_10000778c : 132 -> 120
~ sub_100008430 -> sub_100008420 : 196 -> 184
~ sub_1000087c4 -> sub_1000087a8 : 52 -> 40
~ sub_1000087f8 -> sub_1000087d0 : 28 -> 16
~ sub_100008814 -> sub_1000087e0 : 24 -> 12
~ sub_10000882c -> sub_1000087ec : 24 -> 12
~ sub_100008c58 -> sub_100008c0c : 1664 -> 1544
~ sub_1000092d8 -> sub_100009214 : 656 -> 536
~ sub_100009568 -> sub_10000942c : 340 -> 280
~ sub_100009750 -> sub_1000095d8 : 2448 -> 2348
~ sub_10000a0e0 -> sub_100009f04 : 452 -> 412
~ sub_10000a368 -> sub_10000a164 : 676 -> 556
~ sub_10000a60c -> sub_10000a390 : 716 -> 692
~ sub_10000a8d8 -> sub_10000a644 : 1008 -> 948
~ sub_10000acc8 -> sub_10000a9f8 : 196 -> 144
~ sub_10000ada0 -> sub_10000aa9c : 68 -> 56
~ sub_10000b418 -> sub_10000b108 : 964 -> 944
~ sub_10000bb60 -> sub_10000b83c : 1760 -> 1748
~ sub_10000c580 -> sub_10000c250 : 696 -> 684
~ sub_10000cc38 -> sub_10000c8fc : 488 -> 480
~ sub_10000dcb0 -> sub_10000d96c : 56 -> 44
~ sub_10000dd04 -> sub_10000d9b4 : 32 -> 20
~ sub_10000e050 -> sub_10000dcf4 : 72 -> 60
~ sub_10000e2c4 -> sub_10000df5c : 48 -> 36
~ sub_10000e45c -> sub_10000e0e8 : 260 -> 248
~ sub_10000e560 -> sub_10000e1e0 : 28 -> 16
~ sub_10000e57c -> sub_10000e1f0 : 216 -> 204
~ sub_10000e6ec -> sub_10000e354 : 136 -> 124
~ sub_10000e7c4 -> sub_10000e420 : 212 -> 200
~ sub_10000e898 -> sub_10000e4e8 : 336 -> 324
~ sub_10000ecd8 -> sub_10000e91c : 88 -> 76
~ sub_10000ed30 -> sub_10000e968 : 108 -> 96
~ sub_10000ed9c -> sub_10000e9c8 : 108 -> 96
~ sub_10000efd4 -> sub_10000ebf4 : 124 -> 112
~ sub_10000f73c -> sub_10000f350 : 216 -> 204
~ sub_10000fb5c -> sub_10000f764 : 212 -> 200
~ sub_10000fc30 -> sub_10000f82c : 152 -> 140
~ sub_10000fcc8 -> sub_10000f8b8 : 448 -> 424
~ sub_10000fe88 -> sub_10000fa60 : 324 -> 312
~ sub_1000101a4 -> sub_10000fd70 : 48 -> 36
~ sub_1000101d4 -> sub_10000fd94 : 48 -> 36
~ sub_100010204 -> sub_10000fdb8 : 48 -> 36
~ sub_1000102b8 -> sub_10000fe60 : 72 -> 60
~ sub_100010364 -> sub_10000ff00 : 84 -> 72
~ sub_1000103e4 -> sub_10000ff74 : 132 -> 120
~ sub_100010468 -> sub_10000ffec : 132 -> 120
~ sub_100010668 -> sub_1000101e0 : 84 -> 72
~ sub_100010778 -> sub_1000102e4 : 168 -> 156
~ sub_1000108f0 -> sub_100010450 : 48 -> 36
~ sub_100010be8 -> sub_10001073c : 48 -> 36
~ sub_100010c90 -> sub_1000107d8 : 72 -> 60
~ sub_100010de4 -> sub_100010920 : 48 -> 36
~ sub_100010f8c -> sub_100010abc : 116 -> 104
~ sub_1000110d0 -> sub_100010bf4 : 84 -> 72
~ sub_100011604 -> sub_10001111c : 76 -> 64
~ sub_10001266c -> sub_100012178 : 272 -> 268
```
