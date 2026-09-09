## sort

> `/usr/bin/sort`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 199.0.0.0.0
-  __TEXT.__text: 0x8788
+  __TEXT.__text: 0x866c
   __TEXT.__auth_stubs: 0x730
   __TEXT.__const: 0xa6
   __TEXT.__cstring: 0x90e
-  __TEXT.__unwind_info: 0x1c8
+  __TEXT.__unwind_info: 0x298
   __DATA_CONST.__const: 0xb0
   __DATA_CONST.__auth_got: 0x398
   __DATA_CONST.__got: 0x68
Functions:
~ sub_100000ab4 : 348 -> 344
~ sub_100000c1c -> sub_100000c18 : 164 -> 156
~ sub_100000e28 -> sub_100000e1c : 632 -> 608
~ sub_1000010a0 -> sub_10000107c : 120 -> 112
~ sub_100001118 -> sub_1000010ec : 76 -> 72
~ sub_1000011c8 -> sub_100001198 : 636 -> 628
~ sub_100001b9c -> sub_100001b64 : 24 -> 12
~ sub_100001c10 -> sub_100001bcc : 196 -> 184
~ sub_100001eb4 -> sub_100001e64 : 112 -> 100
~ sub_100002a00 -> sub_1000029a4 : 180 -> 168
~ sub_100002ab4 -> sub_100002a4c : 244 -> 232
~ sub_100003b2c -> sub_100003ab8 : 144 -> 132
~ sub_100003bbc -> sub_100003b3c : 92 -> 80
~ sub_100004a2c -> sub_1000049a0 : 164 -> 152
~ sub_100004bfc -> sub_100004b64 : 476 -> 452
~ sub_100004f28 -> sub_100004e78 : 872 -> 860
~ sub_1000057ec -> sub_100005730 : 32 -> 20
~ sub_100005dbc -> sub_100005cf4 : 152 -> 140
~ sub_10000607c -> sub_100005fa8 : 1420 -> 1408
~ sub_100008104 -> sub_100008024 : 68 -> 56
~ sub_100008448 -> sub_10000835c : 28 -> 16
~ sub_100008464 -> sub_10000836c : 40 -> 28
~ sub_10000848c -> sub_100008388 : 40 -> 28
~ sub_1000084b4 -> sub_1000083a4 : 32 -> 20
```
