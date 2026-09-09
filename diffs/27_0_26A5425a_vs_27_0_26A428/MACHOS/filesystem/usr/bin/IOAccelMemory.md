## IOAccelMemory

> `/usr/bin/IOAccelMemory`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 491.0.0.0.0
-  __TEXT.__text: 0x9414
+  __TEXT.__text: 0x8fac
   __TEXT.__auth_stubs: 0x400
   __TEXT.__objc_stubs: 0x520
   __TEXT.__const: 0x28
   __TEXT.__gcc_except_tab: 0xbc0
   __TEXT.__cstring: 0xf5c
   __TEXT.__objc_methname: 0x282
-  __TEXT.__unwind_info: 0x2a8
+  __TEXT.__unwind_info: 0x300
   __DATA_CONST.__const: 0x170
   __DATA_CONST.__cfstring: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_1000024e8 : 3228 -> 3108
~ sub_100003184 -> sub_10000310c : 200 -> 188
~ sub_10000324c -> sub_1000031c8 : 72 -> 60
~ sub_100003294 -> sub_100003204 : 64 -> 52
~ sub_1000032d4 -> sub_100003238 : 7500 -> 7280
~ sub_100005020 -> sub_100004ea8 : 80 -> 68
~ sub_100005070 -> sub_100004eec : 72 -> 60
~ sub_100005238 -> sub_1000050a8 : 600 -> 588
~ sub_100005940 -> sub_1000057a4 : 72 -> 60
~ sub_100005988 -> sub_1000057e0 : 60 -> 48
~ sub_100005e2c -> sub_100005c78 : 1956 -> 1736
~ sub_1000065d0 -> sub_100006340 : 564 -> 524
~ sub_100006980 -> sub_1000066c8 : 112 -> 108
~ sub_100006bb8 -> sub_1000068fc : 100 -> 88
~ sub_100006c70 -> sub_1000069a8 : 84 -> 80
~ sub_100006d80 -> sub_100006ab4 : 80 -> 68
~ sub_100006e60 -> sub_100006b88 : 68 -> 56
~ sub_100006ea4 -> sub_100006bc0 : 360 -> 320
~ sub_1000071d0 -> sub_100006ec4 : 284 -> 232
~ sub_1000077fc -> sub_1000074bc : 152 -> 140
~ sub_100007894 -> sub_100007548 : 236 -> 224
~ sub_100007980 -> sub_100007628 : 128 -> 116
~ sub_100007a00 -> sub_10000769c : 104 -> 92
~ sub_100007a68 -> sub_1000076f8 : 1984 -> 1884
~ sub_1000082fc -> sub_100007f28 : 128 -> 116
~ sub_100008494 -> sub_1000080b4 : 216 -> 212
~ sub_1000086d4 -> sub_1000082f0 : 1060 -> 976
~ sub_100008c70 -> sub_100008838 : 308 -> 296
~ sub_100008da4 -> sub_100008960 : 392 -> 380
~ sub_1000097bc -> sub_10000936c : 368 -> 356
~ sub_1000099f0 -> sub_100009594 : 256 -> 244
```
