## security

> `/usr/bin/security`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__dof_security_`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-62460.1.2.0.0
-  __TEXT.__text: 0x23228
+62460.1.3.0.0
+  __TEXT.__text: 0x22f14
   __TEXT.__auth_stubs: 0x1f80
   __TEXT.__objc_stubs: 0x9a0
   __TEXT.__objc_methlist: 0x128

   __TEXT.__objc_classname: 0xe
   __TEXT.__objc_methtype: 0xed
   __TEXT.__dof_security_: 0x2a0
-  __TEXT.__unwind_info: 0x830
+  __TEXT.__unwind_info: 0x950
   __DATA_CONST.__const: 0x1c90
   __DATA_CONST.__cfstring: 0xbe0
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ sub_100005618 : 92 -> 72
~ sub_10000570c -> sub_1000056f8 : 92 -> 72
~ sub_1000087f4 -> sub_1000087cc : 2296 -> 2332
~ sub_1000096dc -> sub_1000096d8 : 1876 -> 1932
~ sub_10000b618 -> sub_10000b64c : 144 -> 132
~ sub_10000c7dc -> sub_10000c804 : 80 -> 68
~ sub_10000c82c -> sub_10000c848 : 72 -> 60
~ sub_10000cff0 -> sub_10000d000 : 688 -> 716
~ sub_10000d2a0 -> sub_10000d2cc : 924 -> 968
~ sub_10000e9c8 -> sub_10000ea20 : 400 -> 388
~ sub_100011318 -> sub_100011364 : 104 -> 92
~ sub_1000116d0 -> sub_100011710 : 200 -> 164
~ sub_100011a14 -> sub_100011a30 : 280 -> 268
~ sub_1000128d4 -> sub_1000128e4 : 500 -> 488
~ sub_100012c68 -> sub_100012c6c : 204 -> 192
~ sub_100012e18 -> sub_100012e10 : 424 -> 412
~ sub_100012fc0 -> sub_100012fac : 484 -> 460
~ sub_1000144dc -> sub_1000144b0 : 232 -> 220
~ sub_100014bc4 -> sub_100014b8c : 100 -> 88
~ sub_100014ca8 -> sub_100014c64 : 1224 -> 1212
~ sub_100015170 -> sub_100015120 : 88 -> 76
~ sub_100016508 -> sub_1000164ac : 216 -> 192
~ sub_1000165e0 -> sub_10001656c : 208 -> 196
~ sub_100016704 -> sub_100016684 : 1240 -> 1244
~ sub_100016d7c -> sub_100016d00 : 76 -> 64
~ sub_10001870c -> sub_100018684 : 116 -> 104
~ sub_1000188d4 -> sub_100018840 : 1428 -> 1412
~ sub_10001a128 -> sub_10001a084 : 452 -> 440
~ sub_10001a508 -> sub_10001a458 : 468 -> 456
~ sub_10001a8c8 -> sub_10001a80c : 92 -> 80
~ sub_10001a924 -> sub_10001a85c : 1252 -> 1240
~ sub_10001ae08 -> sub_10001ad34 : 396 -> 384
~ sub_10001bd24 -> sub_10001bc44 : 72 -> 60
~ sub_10001bd6c -> sub_10001bc80 : 64 -> 52
~ sub_10001c55c -> sub_10001c464 : 252 -> 240
~ sub_10001c784 -> sub_10001c680 : 392 -> 368
~ sub_10001cc20 -> sub_10001cb04 : 56 -> 44
~ sub_10001ccf8 -> sub_10001cbd0 : 56 -> 44
~ sub_10001d170 -> sub_10001d03c : 408 -> 396
~ sub_10001d770 -> sub_10001d630 : 56 -> 44
~ sub_10001d7a8 -> sub_10001d65c : 56 -> 44
~ sub_10001da14 -> sub_10001d8bc : 84 -> 72
~ sub_10001da68 -> sub_10001d904 : 92 -> 80
~ sub_10001dac4 -> sub_10001d954 : 108 -> 96
~ sub_10001dc5c -> sub_10001dae0 : 76 -> 64
~ sub_10001dcb4 -> sub_10001db2c : 56 -> 44
~ sub_10001dcec -> sub_10001db58 : 60 -> 48
~ sub_10001df50 -> sub_10001ddb0 : 308 -> 296
~ sub_10001e0a0 -> sub_10001def4 : 56 -> 44
~ sub_10001e0d8 -> sub_10001df20 : 60 -> 48
~ sub_10001e114 -> sub_10001df50 : 60 -> 48
~ sub_10001e150 -> sub_10001df80 : 60 -> 48
~ sub_10001e8a4 -> sub_10001e6c8 : 204 -> 184
~ sub_10001ec04 -> sub_10001ea14 : 144 -> 132
~ sub_10001f8e8 -> sub_10001f6ec : 572 -> 560
~ sub_100020a90 -> sub_100020888 : 136 -> 124
~ sub_100020b1c -> sub_100020908 : 56 -> 44
~ sub_100021058 -> sub_100020e38 : 260 -> 248
~ sub_100021160 -> sub_100020f34 : 56 -> 44
~ sub_1000217a4 -> sub_10002156c : 76 -> 64
~ sub_1000218d8 -> sub_100021694 : 92 -> 72
~ sub_100021934 -> sub_1000216dc : 92 -> 72
~ sub_100021b2c -> sub_1000218c0 : 56 -> 44
~ sub_100021e1c -> sub_100021ba4 : 256 -> 236
~ sub_100021f1c -> sub_100021c90 : 296 -> 276
~ sub_1000221f8 -> sub_100021f58 : 252 -> 240
~ sub_1000222f8 -> sub_10002204c : 56 -> 44
~ sub_1000228c8 -> sub_100022610 : 156 -> 144
~ sub_100022968 -> sub_1000226a4 : 56 -> 44
~ sub_100022e08 -> sub_100022b38 : 56 -> 44
~ sub_1000230c8 -> sub_100022dec : 92 -> 72
~ sub_10002383c -> sub_10002354c : 72 -> 60
~ sub_100023bc4 -> sub_1000238c8 : 56 -> 44
~ sub_100023c5c -> sub_100023954 : 132 -> 120
```
