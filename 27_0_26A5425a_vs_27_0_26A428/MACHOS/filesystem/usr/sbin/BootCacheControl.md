## BootCacheControl

> `/usr/sbin/BootCacheControl`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 162.0.0.0.0
-  __TEXT.__text: 0x13234
+  __TEXT.__text: 0x13148
   __TEXT.__auth_stubs: 0x6a0
   __TEXT.__const: 0x260
   __TEXT.__cstring: 0x4409
   __TEXT.__oslogstring: 0x1e6e
-  __TEXT.__unwind_info: 0x1a8
+  __TEXT.__unwind_info: 0x210
   __DATA_CONST.__const: 0x1e0
   __DATA_CONST.__cfstring: 0xe0
   __DATA_CONST.__auth_got: 0x350
Functions:
~ sub_100001e80 : 684 -> 672
~ sub_100002d30 -> sub_100002d24 : 520 -> 516
~ sub_100002f38 -> sub_100002f28 : 352 -> 340
~ sub_1000031c8 -> sub_1000031ac : 492 -> 488
~ sub_1000033b4 -> sub_100003394 : 32 -> 20
~ sub_1000033d4 -> sub_1000033a8 : 96 -> 84
~ sub_100003434 -> sub_1000033fc : 84 -> 72
~ sub_100003488 -> sub_100003444 : 124 -> 112
~ sub_100004e3c -> sub_100004dec : 1060 -> 1056
~ sub_100005260 -> sub_10000520c : 3296 -> 3260
~ sub_100005f40 -> sub_100005ec8 : 80 -> 68
~ sub_100006ba0 -> sub_100006b1c : 4708 -> 4696
~ sub_100008644 -> sub_1000085b4 : 1576 -> 1580
~ sub_100009a50 -> sub_1000099c4 : 1160 -> 1156
~ sub_10000a6c0 -> sub_10000a630 : 80 -> 68
~ sub_10000a710 -> sub_10000a674 : 68 -> 56
~ sub_10000ac64 -> sub_10000abbc : 27096 -> 27112
~ sub_100012a04 -> sub_10001296c : 160 -> 148
~ sub_100012f94 -> sub_100012ef0 : 1020 -> 1008
~ sub_100013514 -> sub_100013464 : 32 -> 20
~ sub_100013534 -> sub_100013478 : 28 -> 16
~ sub_100013550 -> sub_100013488 : 28 -> 16
~ sub_10001356c -> sub_100013498 : 28 -> 16
~ sub_100013588 -> sub_1000134a8 : 28 -> 16
```
