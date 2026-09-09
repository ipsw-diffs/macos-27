## zip

> `/usr/bin/zip`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 33.0.0.0.0
-  __TEXT.__text: 0x16600
+  __TEXT.__text: 0x16500
   __TEXT.__auth_stubs: 0x580
   __TEXT.__const: 0x9bb
   __TEXT.__cstring: 0x9491
-  __TEXT.__unwind_info: 0x250
+  __TEXT.__unwind_info: 0x2c0
   __DATA_CONST.__const: 0xb40
   __DATA_CONST.__auth_got: 0x2c0
   __DATA_CONST.__got: 0x28
Functions:
~ sub_100000a00 : 440 -> 428
~ sub_100000bd0 -> sub_100000bc4 : 320 -> 308
~ sub_100000d10 -> sub_100000cf8 : 248 -> 236
~ sub_100000e08 -> sub_100000de4 : 248 -> 236
~ sub_100006840 -> sub_100006810 : 428 -> 424
~ sub_1000069ec -> sub_1000069b8 : 660 -> 648
~ sub_100007580 -> sub_100007540 : 48 -> 36
~ sub_10000a8b4 -> sub_10000a868 : 1448 -> 1452
~ sub_10000b254 -> sub_10000b20c : 1312 -> 1300
~ sub_10000b774 -> sub_10000b720 : 852 -> 832
~ sub_10000c658 -> sub_10000c5f0 : 120 -> 108
~ sub_10000ccc4 -> sub_10000cc50 : 588 -> 576
~ sub_10000e700 -> sub_10000e680 : 728 -> 732
~ sub_1000103e0 -> sub_100010364 : 312 -> 300
~ sub_1000116c4 -> sub_10001163c : 2804 -> 2800
~ sub_1000121b8 -> sub_10001212c : 1088 -> 1064
~ sub_100013b64 -> sub_100013ac0 : 984 -> 972
~ sub_100014074 -> sub_100013fc4 : 88 -> 76
~ sub_100014e94 -> sub_100014dd8 : 1408 -> 1404
~ sub_100015414 -> sub_100015354 : 944 -> 932
~ sub_100015d24 -> sub_100015c58 : 992 -> 972
~ sub_100016104 -> sub_100016024 : 492 -> 464
~ sub_1000163d4 -> sub_1000162d8 : 372 -> 360
~ sub_100016a58 -> sub_100016950 : 384 -> 392
```
