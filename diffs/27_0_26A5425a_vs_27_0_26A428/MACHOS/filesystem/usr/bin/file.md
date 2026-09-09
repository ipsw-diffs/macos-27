## file

> `/usr/bin/file`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 110.0.0.0.0
-  __TEXT.__text: 0x15af0
+  __TEXT.__text: 0x15a10
   __TEXT.__auth_stubs: 0x7d0
   __TEXT.__const: 0x1401
   __TEXT.__cstring: 0x3e04
-  __TEXT.__unwind_info: 0x2d0
+  __TEXT.__unwind_info: 0x3c8
   __DATA_CONST.__const: 0x12e0
   __DATA_CONST.__auth_got: 0x3e8
   __DATA_CONST.__got: 0x38
Functions:
~ sub_100000770 : 100 -> 88
~ sub_1000007d4 -> sub_1000007c8 : 92 -> 80
~ sub_1000009f4 -> sub_1000009dc : 1552 -> 1548
~ sub_1000014a0 -> sub_100001484 : 244 -> 240
~ sub_100001594 -> sub_100001574 : 64 -> 52
~ sub_1000015d4 -> sub_1000015a8 : 212 -> 200
~ sub_1000016a8 -> sub_100001670 : 2176 -> 2172
~ sub_100002084 -> sub_100002048 : 7576 -> 7592
~ sub_100003e5c -> sub_100003e30 : 204 -> 192
~ sub_100003fe0 -> sub_100003fa8 : 440 -> 448
~ sub_100004ee0 -> sub_100004eb0 : 1648 -> 1644
~ sub_100005644 -> sub_100005610 : 176 -> 172
~ sub_100005c54 -> sub_100005c1c : 96 -> 84
~ sub_100006004 -> sub_100005fc0 : 376 -> 372
~ sub_1000066b8 -> sub_100006670 : 204 -> 192
~ sub_100007240 -> sub_1000071ec : 1004 -> 1012
~ sub_100008b50 -> sub_100008b04 : 1432 -> 1428
~ sub_10000a0bc -> sub_10000a06c : 68 -> 56
~ sub_10000a100 -> sub_10000a0a4 : 68 -> 56
~ sub_10000ac58 -> sub_10000abf0 : 128 -> 116
~ sub_10000acd8 -> sub_10000ac64 : 76 -> 64
~ sub_10000ee18 -> sub_10000ed98 : 1156 -> 1144
~ sub_10000fd4c -> sub_10000fcc0 : 1484 -> 1488
~ sub_100010b98 -> sub_100010b10 : 1924 -> 1920
~ sub_100011474 -> sub_1000113e8 : 3828 -> 3824
~ sub_1000124f4 -> sub_100012464 : 1796 -> 1784
~ sub_100013a3c -> sub_1000139a0 : 696 -> 672
~ sub_100013cf4 -> sub_100013c40 : 128 -> 116
~ sub_100014760 -> sub_1000146a0 : 3600 -> 3592
~ sub_100015c4c -> sub_100015b84 : 704 -> 680
```
