## localedef

> `/usr/bin/localedef`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 240.0.0.0.0
-  __TEXT.__text: 0x863c
+  __TEXT.__text: 0x851c
   __TEXT.__auth_stubs: 0x440
   __TEXT.__const: 0x12b0
   __TEXT.__cstring: 0x15cf
-  __TEXT.__unwind_info: 0x1f0
+  __TEXT.__unwind_info: 0x2b8
   __DATA_CONST.__const: 0x13e0
   __DATA_CONST.__auth_got: 0x220
   __DATA_CONST.__got: 0x38
Functions:
~ sub_100000f38 : 1356 -> 1332
~ sub_10000195c -> sub_100001944 : 184 -> 160
~ sub_100001cd4 -> sub_100001ca4 : 1644 -> 1652
~ sub_10000289c -> sub_100002874 : 588 -> 576
~ sub_100003038 -> sub_100003004 : 52 -> 40
~ sub_1000032e8 -> sub_1000032a8 : 476 -> 464
~ sub_100003750 -> sub_100003704 : 152 -> 128
~ sub_1000037e8 -> sub_100003784 : 1148 -> 1124
~ sub_100003d94 -> sub_100003d18 : 100 -> 88
~ sub_100003e18 -> sub_100003d90 : 96 -> 84
~ sub_100004358 -> sub_1000042c4 : 124 -> 112
~ sub_100004438 -> sub_100004398 : 68 -> 56
~ sub_10000447c -> sub_1000043d0 : 572 -> 560
~ sub_100006284 -> sub_1000061cc : 236 -> 224
~ sub_100006370 -> sub_1000062ac : 1416 -> 1420
~ sub_100006ee8 -> sub_100006e28 : 256 -> 244
~ sub_10000735c -> sub_100007290 : 640 -> 628
~ sub_100007744 -> sub_10000766c : 144 -> 132
~ sub_100007820 -> sub_10000773c : 276 -> 264
~ sub_100007934 -> sub_100007844 : 520 -> 496
~ sub_100007d8c -> sub_100007c84 : 532 -> 520
~ sub_100007ff0 -> sub_100007edc : 96 -> 84
```
