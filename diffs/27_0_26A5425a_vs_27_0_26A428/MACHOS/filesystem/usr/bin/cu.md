## cu

> `/usr/bin/cu`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 22.0.0.0.0
-  __TEXT.__text: 0x13634
+  __TEXT.__text: 0x13494
   __TEXT.__auth_stubs: 0x820
   __TEXT.__const: 0xd85
   __TEXT.__cstring: 0x2457
-  __TEXT.__unwind_info: 0x3d0
+  __TEXT.__unwind_info: 0x4b8
   __DATA_CONST.__const: 0x1b30
   __DATA_CONST.__auth_got: 0x410
   __DATA_CONST.__got: 0x40
Functions:
~ sub_100001b34 : 320 -> 308
~ sub_100001c74 -> sub_100001c68 : 232 -> 220
~ sub_100001d5c -> sub_100001d44 : 88 -> 76
~ sub_100001e9c -> sub_100001e78 : 328 -> 316
~ sub_1000030c8 -> sub_100003098 : 324 -> 312
~ sub_10000320c -> sub_1000031d0 : 236 -> 232
~ sub_100003e48 -> sub_100003e08 : 592 -> 580
~ sub_1000040fc -> sub_1000040b0 : 2964 -> 2960
~ sub_100005b40 -> sub_100005af0 : 200 -> 140
~ sub_100005c44 -> sub_100005bb8 : 432 -> 428
~ sub_100005fac -> sub_100005f1c : 156 -> 144
~ sub_100006154 -> sub_1000060b8 : 120 -> 108
~ sub_1000061cc -> sub_100006124 : 160 -> 148
~ sub_100006974 -> sub_1000068c0 : 64 -> 52
~ sub_1000073d0 -> sub_100007310 : 60 -> 48
~ sub_10000a110 -> sub_10000a044 : 128 -> 116
~ sub_10000adec -> sub_10000ad14 : 248 -> 236
~ sub_10000b750 -> sub_10000b66c : 104 -> 92
~ sub_10000d0d8 -> sub_10000cfe8 : 196 -> 184
~ sub_10000d4f8 -> sub_10000d3fc : 936 -> 900
~ sub_10000df0c -> sub_10000ddec : 844 -> 828
~ sub_10000ee84 -> sub_10000ed54 : 80 -> 68
~ sub_100010b14 -> sub_1000109d8 : 616 -> 604
~ sub_100011080 -> sub_100010f38 : 144 -> 132
~ sub_100011110 -> sub_100010fbc : 220 -> 208
~ sub_100012704 -> sub_1000125a4 : 116 -> 104
~ sub_100012c80 -> sub_100012b14 : 80 -> 68
~ sub_100012cd0 -> sub_100012b58 : 376 -> 368
~ sub_100012f4c -> sub_100012dcc : 232 -> 212
~ sub_100013afc -> sub_100013968 : 112 -> 100
```
