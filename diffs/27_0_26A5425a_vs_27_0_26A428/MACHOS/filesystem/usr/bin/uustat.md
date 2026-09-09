## uustat

> `/usr/bin/uustat`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 22.0.0.0.0
-  __TEXT.__text: 0xea30
+  __TEXT.__text: 0xe904
   __TEXT.__auth_stubs: 0x650
   __TEXT.__const: 0xaf0
   __TEXT.__cstring: 0x1ae8
-  __TEXT.__unwind_info: 0x2f8
+  __TEXT.__unwind_info: 0x3a0
   __DATA_CONST.__const: 0x17c0
   __DATA_CONST.__auth_got: 0x328
   __DATA_CONST.__got: 0x30
Functions:
~ sub_1000006d8 : 5932 -> 5928
~ sub_100001ee4 -> sub_100001ee0 : 428 -> 416
~ sub_1000044d8 -> sub_1000044c8 : 592 -> 580
~ sub_100004b04 -> sub_100004ae8 : 64 -> 52
~ sub_100005a80 -> sub_100005a58 : 264 -> 240
~ sub_100006a28 -> sub_1000069e8 : 72 -> 60
~ sub_100006a70 -> sub_100006a24 : 256 -> 244
~ sub_100008588 -> sub_100008530 : 84 -> 72
~ sub_100008b5c -> sub_100008af8 : 196 -> 184
~ sub_100008f78 -> sub_100008f08 : 936 -> 900
~ sub_1000097b0 -> sub_10000971c : 844 -> 828
~ sub_100009f60 -> sub_100009ebc : 224 -> 212
~ sub_10000a804 -> sub_10000a754 : 80 -> 68
~ sub_10000be48 -> sub_10000bd8c : 616 -> 604
~ sub_10000c3b4 -> sub_10000c2ec : 144 -> 132
~ sub_10000c444 -> sub_10000c370 : 220 -> 208
~ sub_10000d5a4 -> sub_10000d4c4 : 116 -> 104
~ sub_10000dc0c -> sub_10000db20 : 80 -> 68
~ sub_10000dc5c -> sub_10000db64 : 376 -> 368
~ sub_10000ded8 -> sub_10000ddd8 : 232 -> 212
~ sub_10000eda8 -> sub_10000ec94 : 136 -> 124
~ sub_10000ef4c -> sub_10000ee2c : 112 -> 100
```
