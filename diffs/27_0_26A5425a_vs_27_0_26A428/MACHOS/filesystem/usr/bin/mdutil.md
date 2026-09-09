## mdutil

> `/usr/bin/mdutil`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 2459.405.0.0.0
-  __TEXT.__text: 0xd6ec
+  __TEXT.__text: 0xd4d4
   __TEXT.__auth_stubs: 0xe50
   __TEXT.__objc_stubs: 0x540
   __TEXT.__const: 0x2f8

   __TEXT.__oslogstring: 0x81
   __TEXT.__gcc_except_tab: 0x24
   __TEXT.__objc_methname: 0x3a2
-  __TEXT.__unwind_info: 0x380
+  __TEXT.__unwind_info: 0x530
   __DATA_CONST.__const: 0x3c0
   __DATA_CONST.__cfstring: 0x9e0
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100001170 : 96 -> 84
~ sub_100003848 -> sub_10000383c : 532 -> 528
~ sub_100003b44 -> sub_100003b34 : 152 -> 148
~ sub_100003c74 -> sub_100003c60 : 96 -> 84
~ sub_100003d7c -> sub_100003d5c : 112 -> 100
~ sub_100004590 -> sub_100004564 : 204 -> 192
~ sub_100004b40 -> sub_100004b08 : 140 -> 128
~ sub_100005064 -> sub_100005020 : 88 -> 76
~ sub_100005424 -> sub_1000053d4 : 128 -> 116
~ sub_1000054b4 -> sub_100005458 : 128 -> 116
~ sub_10000554c -> sub_1000054e4 : 128 -> 116
~ sub_10000566c -> sub_1000055f8 : 72 -> 60
~ sub_1000056b4 -> sub_100005634 : 192 -> 168
~ sub_100005810 -> sub_100005778 : 148 -> 136
~ sub_1000058a4 -> sub_100005800 : 140 -> 128
~ sub_100005950 -> sub_1000058a0 : 148 -> 136
~ sub_1000059e4 -> sub_100005928 : 148 -> 136
~ sub_100005a78 -> sub_1000059b0 : 156 -> 144
~ sub_100005b14 -> sub_100005a40 : 156 -> 144
~ sub_100005bb0 -> sub_100005ad0 : 156 -> 144
~ sub_100005c4c -> sub_100005b60 : 156 -> 144
~ sub_100005ce8 -> sub_100005bf0 : 176 -> 164
~ sub_100006118 -> sub_100006014 : 28 -> 16
~ sub_1000062e8 -> sub_1000061d8 : 148 -> 136
~ sub_1000064c8 -> sub_1000063ac : 92 -> 80
~ sub_100006548 -> sub_100006420 : 148 -> 136
~ sub_1000065e8 -> sub_1000064b4 : 96 -> 84
~ sub_100006a9c -> sub_10000695c : 372 -> 348
~ sub_100006c24 -> sub_100006acc : 52 -> 40
~ sub_100008800 -> sub_10000869c : 272 -> 260
~ sub_1000094d0 -> sub_100009360 : 76 -> 64
~ sub_10000962c -> sub_1000094b0 : 116 -> 104
~ sub_1000096a0 -> sub_100009518 : 80 -> 68
~ sub_1000096f0 -> sub_10000955c : 68 -> 56
~ sub_100009734 -> sub_100009594 : 92 -> 80
~ sub_1000097ac -> sub_100009600 : 92 -> 80
~ sub_1000099fc -> sub_100009844 : 160 -> 148
~ sub_100009a9c -> sub_1000098d8 : 160 -> 148
~ sub_100009d30 -> sub_100009b60 : 104 -> 92
~ sub_100009ed0 -> sub_100009cf4 : 32 -> 24
~ sub_100009ef0 -> sub_100009d0c : 36 -> 28
~ sub_10000b1b0 -> sub_10000afc4 : 88 -> 76
~ sub_10000b340 -> sub_10000b148 : 92 -> 80
~ sub_10000b3e4 -> sub_10000b1e0 : 304 -> 300
~ sub_10000b70c -> sub_10000b504 : 120 -> 116
~ sub_10000bab4 -> sub_10000b8a8 : 60 -> 48
```
