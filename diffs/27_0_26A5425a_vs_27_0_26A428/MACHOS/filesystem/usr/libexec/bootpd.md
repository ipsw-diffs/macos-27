## bootpd

> `/usr/libexec/bootpd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 557.0.0.0.0
-  __TEXT.__text: 0x1de1c
+  __TEXT.__text: 0x1dce8
   __TEXT.__auth_stubs: 0xdd0
   __TEXT.__const: 0x158
   __TEXT.__cstring: 0x2d38
   __TEXT.__oslogstring: 0x2119
-  __TEXT.__unwind_info: 0x450
+  __TEXT.__unwind_info: 0x508
   __DATA_CONST.__const: 0x14d8
   __DATA_CONST.__cfstring: 0x12e0
   __DATA_CONST.__auth_got: 0x6e8
Functions:
~ sub_100004ed8 : 292 -> 280
~ sub_1000058e8 -> sub_1000058dc : 3772 -> 3768
~ sub_100006e14 -> sub_100006e04 : 5456 -> 5444
~ sub_10000ab04 -> sub_10000aae8 : 116 -> 104
~ sub_10000b20c -> sub_10000b1e4 : 244 -> 232
~ sub_10000d760 -> sub_10000d72c : 140 -> 128
~ sub_10001078c -> sub_10001074c : 108 -> 96
~ sub_100010abc -> sub_100010a70 : 1220 -> 1224
~ sub_1000122d8 -> sub_100012290 : 384 -> 360
~ sub_100012510 -> sub_1000124b0 : 72 -> 60
~ sub_100012570 -> sub_100012504 : 100 -> 88
~ sub_1000128b8 -> sub_100012840 : 972 -> 948
~ sub_100012cc0 -> sub_100012c30 : 324 -> 300
~ sub_100012e04 -> sub_100012d5c : 124 -> 112
~ sub_100013698 -> sub_1000135e4 : 484 -> 468
~ sub_100013f44 -> sub_100013e80 : 116 -> 104
~ _hostfree : 108 -> 96
~ _macNCopt_str_to_type : 472 -> 460
~ sub_100018cc8 -> sub_100018be0 : 632 -> 620
~ sub_100019b54 -> sub_100019a60 : 68 -> 56
~ sub_10001a0e8 -> sub_100019fe8 : 68 -> 56
~ sub_10001a148 -> sub_10001a03c : 144 -> 136
~ sub_10001ade4 -> sub_10001acd0 : 188 -> 192
~ sub_10001dc70 -> sub_10001db60 : 256 -> 244
~ sub_10001dd70 -> sub_10001dc54 : 124 -> 112
~ sub_10001e528 -> sub_10001e400 : 96 -> 84
```
