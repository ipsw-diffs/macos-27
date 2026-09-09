## ktrace

> `/usr/bin/ktrace`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 706.0.2.0.0
-  __TEXT.__text: 0x82dc
+  __TEXT.__text: 0x80a0
   __TEXT.__auth_stubs: 0x1010
   __TEXT.__objc_stubs: 0x20
   __TEXT.__const: 0xd0
   __TEXT.__cstring: 0x2e21
   __TEXT.__gcc_except_tab: 0x9c
   __TEXT.__objc_methname: 0x1e
-  __TEXT.__unwind_info: 0x220
+  __TEXT.__unwind_info: 0x318
   __DATA_CONST.__const: 0xb40
   __DATA_CONST.__cfstring: 0x140
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000c28 : 1372 -> 1168
~ sub_1000011d4 -> sub_100001108 : 32 -> 20
~ sub_1000011f8 -> sub_100001120 : 3736 -> 3720
~ sub_100002324 -> sub_10000223c : 600 -> 588
~ sub_10000257c -> sub_100002488 : 80 -> 68
~ sub_1000025d8 -> sub_1000024d8 : 160 -> 148
~ sub_100002704 -> sub_1000025f8 : 68 -> 56
~ sub_100002934 -> sub_10000281c : 300 -> 288
~ sub_1000036cc -> sub_1000035a8 : 112 -> 100
~ sub_10000373c -> sub_10000360c : 92 -> 80
~ sub_10000384c -> sub_100003710 : 128 -> 116
~ sub_1000038cc -> sub_100003784 : 104 -> 92
~ sub_100003b70 -> sub_100003a1c : 144 -> 132
~ sub_100003cb8 -> sub_100003b58 : 664 -> 652
~ sub_100003ff0 -> sub_100003e84 : 76 -> 64
~ sub_10000440c -> sub_100004294 : 32 -> 20
~ sub_100004618 -> sub_100004494 : 272 -> 248
~ sub_100004ed8 -> sub_100004d3c : 2956 -> 2964
~ sub_1000063b8 -> sub_100006224 : 140 -> 128
~ sub_100007194 -> sub_100006ff4 : 124 -> 112
~ sub_100007214 -> sub_100007068 : 112 -> 100
~ sub_1000075b8 -> sub_100007400 : 252 -> 240
~ sub_1000082cc -> sub_100008108 : 80 -> 68
~ sub_10000831c -> sub_10000814c : 68 -> 56
~ sub_1000083fc -> sub_100008220 : 96 -> 84
~ sub_10000845c -> sub_100008274 : 80 -> 68
~ sub_1000084ac -> sub_1000082b8 : 120 -> 108
~ sub_100008524 -> sub_100008324 : 412 -> 400
~ sub_1000086c0 -> sub_1000084b4 : 316 -> 304
~ sub_10000880c -> sub_1000085f4 : 72 -> 60
~ sub_100008854 -> sub_100008630 : 76 -> 64
~ sub_100008c94 -> sub_100008a64 : 76 -> 64
```
