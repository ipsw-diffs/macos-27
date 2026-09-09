## umtool

> `/usr/bin/umtool`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 490.0.3.0.0
-  __TEXT.__text: 0x15710
+  __TEXT.__text: 0x15468
   __TEXT.__auth_stubs: 0x3c0
   __TEXT.__objc_stubs: 0x1180
   __TEXT.__objc_methlist: 0x368

   __TEXT.__objc_methtype: 0xb3
   __TEXT.__gcc_except_tab: 0x1ac
   __TEXT.__oslogstring: 0x1af
-  __TEXT.__unwind_info: 0x3f8
+  __TEXT.__unwind_info: 0x598
   __DATA_CONST.__const: 0x140
   __DATA_CONST.__cfstring: 0x13e0
   __DATA_CONST.__objc_classlist: 0x30
Functions:
~ sub_100000d70 : 108 -> 96
~ sub_100000ddc -> sub_100000dd0 : 924 -> 912
~ sub_100001304 -> sub_1000012ec : 96 -> 84
~ sub_100001364 -> sub_100001340 : 116 -> 104
~ sub_1000013ec -> sub_1000013bc : 92 -> 80
~ sub_100001448 -> sub_10000140c : 268 -> 256
~ sub_1000018e8 -> sub_1000018a0 : 116 -> 104
~ sub_10000195c -> sub_100001908 : 348 -> 336
~ sub_100001ab8 -> sub_100001a58 : 68 -> 56
~ sub_100001bc0 -> sub_100001b54 : 140 -> 128
~ sub_100001c4c -> sub_100001bd4 : 432 -> 420
~ sub_100001e14 -> sub_100001d90 : 132 -> 120
~ sub_100001eb4 -> sub_100001e24 : 328 -> 316
~ sub_100001ffc -> sub_100001f60 : 132 -> 120
~ sub_100002094 -> sub_100001fec : 68 -> 56
~ sub_100002194 -> sub_1000020e0 : 268 -> 256
~ sub_1000022a0 -> sub_1000021e0 : 348 -> 336
~ sub_1000023fc -> sub_100002330 : 388 -> 376
~ sub_100002580 -> sub_1000024a8 : 132 -> 120
~ sub_100002604 -> sub_100002520 : 132 -> 120
~ sub_100002688 -> sub_100002598 : 284 -> 272
~ sub_1000027a4 -> sub_1000026a8 : 132 -> 120
~ sub_100002984 -> sub_10000287c : 132 -> 120
~ sub_100002a08 -> sub_1000028f4 : 132 -> 120
~ sub_100002a8c -> sub_10000296c : 132 -> 120
~ sub_100003990 -> sub_100003864 : 92 -> 80
~ sub_1000039ec -> sub_1000038b4 : 72 -> 60
~ sub_100003a34 -> sub_1000038f0 : 64 -> 52
~ sub_100003a74 -> sub_100003924 : 92 -> 80
~ sub_100003aec -> sub_100003990 : 276 -> 264
~ sub_100003c80 -> sub_100003b18 : 1516 -> 1512
~ sub_100005e48 -> sub_100005cdc : 132 -> 120
~ sub_100006048 -> sub_100005ed0 : 32 -> 20
~ sub_1000068c8 -> sub_100006744 : 36 -> 24
~ sub_1000068ec -> sub_10000675c : 28 -> 16
~ sub_100006908 -> sub_10000676c : 32 -> 20
~ sub_100006928 -> sub_100006780 : 44 -> 32
~ sub_100006978 -> sub_1000067c4 : 36 -> 24
~ sub_1000069cc -> sub_10000680c : 28 -> 16
~ sub_100006a30 -> sub_100006864 : 40 -> 28
~ sub_100006aa0 -> sub_1000068c8 : 28 -> 16
~ sub_100006abc -> sub_1000068d8 : 12 -> 20
~ sub_100006ac8 -> sub_1000068ec : 20 -> 12
~ sub_100006c50 -> sub_100006a6c : 40 -> 28
~ sub_100006c78 -> sub_100006a88 : 24 -> 16
~ sub_100006c90 -> sub_100006a98 : 16 -> 24
~ sub_100006ca0 -> sub_100006ab0 : 40 -> 28
~ sub_100006cdc -> sub_100006ae0 : 28 -> 16
~ sub_100006d04 -> sub_100006afc : 32 -> 20
~ sub_100006d64 -> sub_100006b50 : 36 -> 24
~ sub_100006de4 -> sub_100006bc4 : 24 -> 12
~ sub_100006dfc -> sub_100006bd0 : 24 -> 12
~ sub_100006e14 -> sub_100006bdc : 24 -> 12
~ sub_100007664 -> sub_100007420 : 24 -> 12
~ sub_100007740 -> sub_1000074f0 : 124 -> 120
~ sub_1000077e4 -> sub_100007590 : 256 -> 244
~ sub_100007b54 -> sub_1000078f4 : 28 -> 16
~ sub_10000ab74 -> sub_10000a908 : 28 -> 16
~ sub_10000ac2c -> sub_10000a9b4 : 32 -> 20
~ sub_10000b17c -> sub_10000aef8 : 40 -> 28
~ sub_10000b514 -> sub_10000b284 : 32 -> 20
~ sub_10000d01c -> sub_10000cd80 : 156 -> 144
```
