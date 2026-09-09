## awk

> `/usr/bin/awk`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 40.0.0.0.0
-  __TEXT.__text: 0xf740
+  __TEXT.__text: 0xf618
   __TEXT.__auth_stubs: 0x4a0
   __TEXT.__const: 0x56f0
   __TEXT.__cstring: 0x2275
-  __TEXT.__unwind_info: 0x308
+  __TEXT.__unwind_info: 0x3b0
   __DATA_CONST.__const: 0x798
   __DATA_CONST.__auth_got: 0x250
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100000678 : 372 -> 360
~ sub_100000a2c -> sub_100000a20 : 348 -> 336
~ sub_100000b88 -> sub_100000b70 : 204 -> 192
~ sub_100000ed0 -> sub_100000eac : 160 -> 148
~ sub_100001210 -> sub_1000011e0 : 1324 -> 1320
~ sub_100002e9c -> sub_100002e68 : 44 -> 32
~ sub_100002fd4 -> sub_100002f94 : 608 -> 596
~ sub_10000357c -> sub_100003530 : 2716 -> 2704
~ sub_100004db0 -> sub_100004d58 : 296 -> 284
~ sub_100004fe4 -> sub_100004f80 : 244 -> 232
~ sub_100005350 -> sub_1000052e0 : 216 -> 192
~ sub_100006338 -> sub_1000062b0 : 112 -> 100
~ sub_100006a54 -> sub_1000069c0 : 152 -> 140
~ sub_100006c2c -> sub_100006b8c : 352 -> 340
~ sub_100006e90 -> sub_100006de4 : 36 -> 24
~ sub_100006ebc -> sub_100006e04 : 3936 -> 3944
~ sub_100008754 -> sub_1000086a4 : 132 -> 120
~ sub_1000092ac -> sub_1000091f0 : 228 -> 216
~ sub_10000b02c -> sub_10000af64 : 444 -> 436
~ sub_10000b2e0 -> sub_10000b210 : 2216 -> 2200
~ sub_10000c4ec -> sub_10000c40c : 88 -> 76
~ sub_10000c544 -> sub_10000c458 : 208 -> 196
~ sub_10000cc08 -> sub_10000cb10 : 96 -> 84
~ sub_10000cc68 -> sub_10000cb64 : 116 -> 104
~ sub_10000ea00 -> sub_10000e8f0 : 280 -> 268
~ sub_10000f780 -> sub_10000f664 : 96 -> 84
```
