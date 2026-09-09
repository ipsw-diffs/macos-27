## scp

> `/usr/bin/scp`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 369.0.4.0.0
-  __TEXT.__text: 0x12354
+  __TEXT.__text: 0x12204
   __TEXT.__auth_stubs: 0x6c0
   __TEXT.__const: 0xf0
   __TEXT.__cstring: 0x31d8
-  __TEXT.__unwind_info: 0x258
+  __TEXT.__unwind_info: 0x380
   __DATA_CONST.__const: 0x68
   __DATA_CONST.__auth_got: 0x360
   __DATA_CONST.__got: 0x68
Functions:
~ sub_1000046a0 : 240 -> 228
~ sub_1000054b0 -> sub_1000054a4 : 252 -> 228
~ sub_100005748 -> sub_100005724 : 676 -> 664
~ sub_100005d08 -> sub_100005cd8 : 1604 -> 1596
~ sub_10000746c -> sub_100007434 : 112 -> 100
~ sub_1000074dc -> sub_100007498 : 312 -> 300
~ sub_100007714 -> sub_1000076c4 : 352 -> 340
~ sub_100007874 -> sub_100007818 : 208 -> 196
~ sub_100007c04 -> sub_100007b9c : 252 -> 228
~ sub_100008350 -> sub_1000082d0 : 124 -> 112
~ sub_100008830 -> sub_1000087a4 : 3348 -> 3344
~ sub_100009744 -> sub_1000096b4 : 292 -> 280
~ sub_100009f60 -> sub_100009ec4 : 2572 -> 2568
~ sub_10000af78 -> sub_10000aed8 : 2716 -> 2712
~ sub_10000ca04 -> sub_10000c960 : 60 -> 48
~ sub_10000ced8 -> sub_10000ce28 : 172 -> 160
~ sub_10000e4b0 -> sub_10000e3f4 : 184 -> 172
~ sub_10000f0d4 -> sub_10000f00c : 104 -> 92
~ sub_10000f32c -> sub_10000f258 : 84 -> 72
~ sub_10000f53c -> sub_10000f45c : 228 -> 216
~ sub_10000f620 -> sub_10000f534 : 236 -> 224
~ sub_10000f848 -> sub_10000f750 : 196 -> 184
~ sub_10000fa60 -> sub_10000f95c : 24 -> 12
~ sub_10000fa78 -> sub_10000f968 : 832 -> 820
~ sub_100010044 -> sub_10000ff28 : 916 -> 908
~ sub_100010600 -> sub_1000104dc : 264 -> 252
~ sub_100010924 -> sub_1000107f4 : 72 -> 60
~ sub_100010a28 -> sub_1000108ec : 760 -> 756
~ sub_1000111fc -> sub_1000110bc : 652 -> 640
~ sub_1000127a0 -> sub_100012654 : 644 -> 652
~ sub_100012cf8 -> sub_100012bb4 : 44 -> 32
```
