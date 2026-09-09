## visudo

> `/usr/sbin/visudo`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 131.0.1.0.0
-  __TEXT.__text: 0x2a080
+  __TEXT.__text: 0x29fd4
   __TEXT.__auth_stubs: 0x8d0
   __TEXT.__cstring: 0x81a8
   __TEXT.__const: 0xc7e0
   __TEXT.__oslogstring: 0x5c
-  __TEXT.__unwind_info: 0x4b8
+  __TEXT.__unwind_info: 0x6b0
   __DATA_CONST.__const: 0x758
   __DATA_CONST.__auth_got: 0x468
   __DATA_CONST.__got: 0x50
Functions:
~ sub_1000068e4 : 164 -> 152
~ sub_10000b43c -> sub_10000b430 : 5928 -> 5944
~ sub_10000cf4c -> sub_10000cf50 : 96 -> 84
~ sub_10000d6ac -> sub_10000d6a4 : 808 -> 800
~ sub_10000dae4 -> sub_10000dad4 : 268 -> 244
~ sub_1000141ac -> sub_100014184 : 88 -> 76
~ sub_100016778 -> sub_100016744 : 120 -> 108
~ sub_10001914c -> sub_10001910c : 15256 -> 15268
~ sub_10001d2bc -> sub_10001d288 : 112 -> 100
~ sub_10001d588 -> sub_10001d548 : 60 -> 48
~ sub_10001f03c -> sub_10001eff0 : 28 -> 16
~ sub_10001ffc4 -> sub_10001ff6c : 496 -> 476
~ sub_1000201c0 -> sub_100020154 : 600 -> 608
~ sub_1000204d4 -> sub_100020470 : 72 -> 60
~ sub_10002056c -> sub_1000204fc : 64 -> 52
~ sub_1000231d0 -> sub_100023154 : 224 -> 212
~ sub_10002401c -> sub_100023f94 : 240 -> 228
~ sub_10002472c -> sub_100024698 : 244 -> 232
~ sub_100024b14 -> sub_100024a74 : 88 -> 76
~ sub_100025050 -> sub_100024fa4 : 64 -> 52
~ sub_100028808 -> sub_100028750 : 692 -> 704
```
