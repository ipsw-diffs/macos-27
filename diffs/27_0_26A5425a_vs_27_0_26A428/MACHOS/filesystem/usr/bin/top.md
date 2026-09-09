## top

> `/usr/bin/top`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 144.0.0.0.0
-  __TEXT.__text: 0xb740
+  __TEXT.__text: 0xb5e0
   __TEXT.__auth_stubs: 0x7f0
   __TEXT.__const: 0x250
   __TEXT.__cstring: 0x1957
-  __TEXT.__unwind_info: 0x2f0
+  __TEXT.__unwind_info: 0x3f8
   __DATA_CONST.__const: 0x640
   __DATA_CONST.__cfstring: 0xa0
   __DATA_CONST.__auth_got: 0x3f8
Functions:
~ sub_10000086c : 40 -> 28
~ sub_100000fa0 -> sub_100000f94 : 28 -> 16
~ sub_100001250 -> sub_100001238 : 288 -> 268
~ sub_100001740 -> sub_100001714 : 568 -> 576
~ sub_100001978 -> sub_100001954 : 108 -> 96
~ sub_100003060 -> sub_100003030 : 56 -> 52
~ sub_100003e10 -> sub_100003ddc : 80 -> 68
~ sub_1000044c0 -> sub_100004480 : 44 -> 32
~ sub_100004c48 -> sub_100004bfc : 684 -> 692
~ sub_100005118 -> sub_1000050d4 : 64 -> 52
~ sub_10000577c -> sub_10000572c : 136 -> 124
~ sub_10000690c -> sub_1000068b0 : 76 -> 64
~ sub_100006d18 -> sub_100006cb0 : 268 -> 256
~ sub_100006e24 -> sub_100006db0 : 136 -> 124
~ sub_100006eac -> sub_100006e2c : 284 -> 260
~ sub_10000707c -> sub_100006fe4 : 268 -> 244
~ sub_100007260 -> sub_1000071b0 : 136 -> 112
~ sub_10000739c -> sub_1000072d4 : 148 -> 124
~ sub_10000762c -> sub_10000754c : 500 -> 476
~ sub_100007820 -> sub_100007728 : 240 -> 228
~ sub_100007910 -> sub_10000780c : 88 -> 64
~ sub_100007c18 -> sub_100007afc : 284 -> 280
~ sub_100007d34 -> sub_100007c14 : 264 -> 260
~ sub_100007e54 -> sub_100007d30 : 268 -> 244
~ sub_100008d50 -> sub_100008c14 : 196 -> 184
~ sub_100008e14 -> sub_100008ccc : 1032 -> 1020
~ sub_10000a27c -> sub_10000a128 : 136 -> 124
```
