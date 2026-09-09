## diff

> `/usr/bin/diff`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 77.0.0.0.0
-  __TEXT.__text: 0xb1bc
+  __TEXT.__text: 0xb0a4
   __TEXT.__auth_stubs: 0x630
   __TEXT.__const: 0x73
   __TEXT.__cstring: 0xf6a
-  __TEXT.__unwind_info: 0x190
+  __TEXT.__unwind_info: 0x210
   __DATA_CONST.__const: 0x100
   __DATA_CONST.__auth_got: 0x318
   __DATA_CONST.__got: 0x40
Functions:
~ sub_1000006c8 : 88 -> 76
~ sub_100000cc0 -> sub_100000cb4 : 212 -> 204
~ sub_100000e08 -> sub_100000df4 : 88 -> 64
~ sub_100001760 -> sub_100001734 : 1120 -> 1096
~ sub_100001bc0 -> sub_100001b7c : 220 -> 196
~ sub_100001c9c -> sub_100001c40 : 5824 -> 5812
~ sub_1000034a4 -> sub_10000343c : 544 -> 532
~ sub_100003748 -> sub_1000036d4 : 180 -> 184
~ sub_1000038a0 -> sub_100003830 : 1204 -> 1192
~ sub_100003dec -> sub_100003d70 : 2888 -> 2880
~ sub_100004934 -> sub_1000048b0 : 860 -> 852
~ sub_100004c90 -> sub_100004c04 : 704 -> 696
~ sub_10000502c -> sub_100004f98 : 104 -> 100
~ sub_1000053e8 -> sub_100005350 : 28 -> 16
~ sub_100005404 -> sub_100005360 : 36 -> 24
~ sub_100005428 -> sub_100005378 : 348 -> 336
~ sub_100005824 -> sub_100005768 : 508 -> 496
~ sub_100006080 -> sub_100005fb8 : 532 -> 524
~ sub_100006494 -> sub_1000063c4 : 684 -> 672
~ sub_100006740 -> sub_100006664 : 80 -> 68
~ sub_1000070a4 -> sub_100006fbc : 1392 -> 1368
~ sub_100007614 -> sub_100007514 : 32 -> 20
~ sub_1000091b0 -> sub_1000090a4 : 1036 -> 1052
~ sub_1000095bc -> sub_1000094c0 : 968 -> 952
~ sub_10000a8b4 -> sub_10000a7a8 : 100 -> 88
```
