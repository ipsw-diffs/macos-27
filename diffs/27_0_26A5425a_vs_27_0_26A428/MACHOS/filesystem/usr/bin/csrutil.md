## csrutil

> `/usr/bin/csrutil`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 87.0.3.0.0
-  __TEXT.__text: 0x169bc
+  __TEXT.__text: 0x166d0
   __TEXT.__auth_stubs: 0x840
   __TEXT.__objc_stubs: 0xe60
   __TEXT.__objc_methlist: 0x304

   __TEXT.__const: 0x131
   __TEXT.__gcc_except_tab: 0x1e0
   __TEXT.__oslogstring: 0x1af
-  __TEXT.__unwind_info: 0x548
+  __TEXT.__unwind_info: 0x710
   __DATA_CONST.__const: 0x340
   __DATA_CONST.__cfstring: 0x600
   __DATA_CONST.__objc_classlist: 0x18
Functions:
~ sub_100001038 : 220 -> 184
~ sub_100001134 -> sub_100001110 : 220 -> 184
~ sub_100001210 -> sub_1000011c8 : 200 -> 188
~ sub_1000012d8 -> sub_100001284 : 676 -> 664
~ sub_1000015a0 -> sub_100001540 : 80 -> 68
~ sub_1000019f0 -> sub_100001984 : 120 -> 108
~ sub_100001a68 -> sub_1000019f0 : 68 -> 56
~ sub_100001c40 -> sub_100001bbc : 68 -> 56
~ sub_100001ee8 -> sub_100001e58 : 592 -> 580
~ sub_1000025e8 -> sub_10000254c : 308 -> 296
~ sub_10000271c -> sub_100002674 : 72 -> 60
~ sub_100002764 -> sub_1000026b0 : 64 -> 52
~ sub_1000027a4 -> sub_1000026e4 : 220 -> 208
~ sub_100002ba4 -> sub_100002ad8 : 96 -> 84
~ sub_100002c04 -> sub_100002b2c : 84 -> 72
~ sub_100003234 -> sub_100003150 : 104 -> 92
~ sub_100003348 -> sub_100003258 : 152 -> 140
~ sub_1000033e0 -> sub_1000032e4 : 512 -> 500
~ sub_100003680 -> sub_100003578 : 92 -> 80
~ sub_1000038f4 -> sub_1000037e0 : 72 -> 60
~ sub_100003988 -> sub_100003868 : 88 -> 76
~ sub_100003a00 -> sub_1000038d4 : 88 -> 76
~ sub_100003a78 -> sub_100003940 : 88 -> 76
~ sub_100003cd4 -> sub_100003b90 : 624 -> 612
~ sub_1000046e0 -> sub_100004590 : 280 -> 268
~ sub_1000048a8 -> sub_10000474c : 300 -> 288
~ sub_1000049d4 -> sub_10000486c : 248 -> 236
~ sub_100004acc -> sub_100004958 : 300 -> 288
~ sub_100004f4c -> sub_100004dcc : 860 -> 848
~ sub_100006764 -> sub_1000065d8 : 548 -> 536
~ sub_100006988 -> sub_1000067f0 : 32 -> 20
~ sub_1000069a8 -> sub_100006804 : 32 -> 20
~ sub_100006af8 -> sub_100006948 : 484 -> 472
~ sub_100006e58 -> sub_100006c9c : 32 -> 20
~ sub_1000076d8 -> sub_100007510 : 36 -> 24
~ sub_1000076fc -> sub_100007528 : 28 -> 16
~ sub_100007718 -> sub_100007538 : 32 -> 20
~ sub_100007738 -> sub_10000754c : 44 -> 32
~ sub_100007788 -> sub_100007590 : 36 -> 24
~ sub_1000077dc -> sub_1000075d8 : 28 -> 16
~ sub_100007840 -> sub_100007630 : 40 -> 28
~ sub_1000078b0 -> sub_100007694 : 28 -> 16
~ sub_1000078cc -> sub_1000076a4 : 12 -> 20
~ sub_1000078d8 -> sub_1000076b8 : 20 -> 12
~ sub_100007a60 -> sub_100007838 : 40 -> 28
~ sub_100007a88 -> sub_100007854 : 24 -> 16
~ sub_100007aa0 -> sub_100007864 : 16 -> 24
~ sub_100007ab0 -> sub_10000787c : 40 -> 28
~ sub_100007aec -> sub_1000078ac : 28 -> 16
~ sub_100007b14 -> sub_1000078c8 : 32 -> 20
~ sub_100007b74 -> sub_10000791c : 36 -> 24
~ sub_100007bf4 -> sub_100007990 : 24 -> 12
~ sub_100007c0c -> sub_10000799c : 24 -> 12
~ sub_100007c24 -> sub_1000079a8 : 24 -> 12
~ sub_100008474 -> sub_1000081ec : 24 -> 12
~ sub_100008550 -> sub_1000082bc : 124 -> 120
~ sub_1000085f4 -> sub_10000835c : 256 -> 244
~ sub_100008964 -> sub_1000086c0 : 28 -> 16
~ sub_10000b984 -> sub_10000b6d4 : 28 -> 16
~ sub_10000ba3c -> sub_10000b780 : 32 -> 20
~ sub_10000bf8c -> sub_10000bcc4 : 40 -> 28
~ sub_10000c324 -> sub_10000c050 : 32 -> 20
~ sub_10000e588 -> sub_10000e2a8 : 156 -> 144
```
