## bioutil

> `/usr/bin/bioutil`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 577.0.0.0.0
-  __TEXT.__text: 0x13018
+  __TEXT.__text: 0x12e94
   __TEXT.__auth_stubs: 0x370
   __TEXT.__objc_stubs: 0x6a0
   __TEXT.__const: 0x131

   __TEXT.__cstring: 0x3269
   __TEXT.__oslogstring: 0x209
   __TEXT.__objc_methname: 0x470
-  __TEXT.__unwind_info: 0x360
+  __TEXT.__unwind_info: 0x4c8
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__cfstring: 0x300
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000c30 : 248 -> 236
~ sub_100000e60 -> sub_100000e54 : 488 -> 476
~ sub_10000147c -> sub_100001464 : 80 -> 68
~ sub_1000014cc -> sub_1000014a8 : 68 -> 56
~ sub_100003274 -> sub_100003244 : 84 -> 72
~ sub_100003330 -> sub_1000032f4 : 32 -> 20
~ sub_100003350 -> sub_100003308 : 28 -> 16
~ sub_1000034e8 -> sub_100003494 : 32 -> 20
~ sub_100003d68 -> sub_100003d08 : 36 -> 24
~ sub_100003d8c -> sub_100003d20 : 28 -> 16
~ sub_100003da8 -> sub_100003d30 : 32 -> 20
~ sub_100003dc8 -> sub_100003d44 : 44 -> 32
~ sub_100003e18 -> sub_100003d88 : 36 -> 24
~ sub_100003e6c -> sub_100003dd0 : 28 -> 16
~ sub_100003ed0 -> sub_100003e28 : 40 -> 28
~ sub_100003f40 -> sub_100003e8c : 28 -> 16
~ sub_100003f5c -> sub_100003e9c : 12 -> 20
~ sub_100003f68 -> sub_100003eb0 : 20 -> 12
~ sub_1000040f0 -> sub_100004030 : 40 -> 28
~ sub_100004118 -> sub_10000404c : 24 -> 16
~ sub_100004130 -> sub_10000405c : 16 -> 24
~ sub_100004140 -> sub_100004074 : 40 -> 28
~ sub_10000417c -> sub_1000040a4 : 28 -> 16
~ sub_1000041a4 -> sub_1000040c0 : 32 -> 20
~ sub_100004204 -> sub_100004114 : 36 -> 24
~ sub_100004284 -> sub_100004188 : 24 -> 12
~ sub_10000429c -> sub_100004194 : 24 -> 12
~ sub_1000042b4 -> sub_1000041a0 : 24 -> 12
~ sub_100004b04 -> sub_1000049e4 : 24 -> 12
~ sub_100004be0 -> sub_100004ab4 : 124 -> 120
~ sub_100004c84 -> sub_100004b54 : 256 -> 244
~ sub_100004ff4 -> sub_100004eb8 : 28 -> 16
~ sub_100008014 -> sub_100007ecc : 28 -> 16
~ sub_1000080cc -> sub_100007f78 : 32 -> 20
~ sub_10000861c -> sub_1000084bc : 40 -> 28
~ sub_1000089b4 -> sub_100008848 : 32 -> 20
~ sub_10000a7fc -> sub_10000a684 : 156 -> 144
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-577~3086, %s file: %s, line: %d\n\n"
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-577~3105, %s file: %s, line: %d\n\n"
```
