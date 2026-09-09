## avbanalyse

> `/usr/bin/avbanalyse`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 1500.16.0.0.0
-  __TEXT.__text: 0x186f0
+  __TEXT.__text: 0x18460
   __TEXT.__auth_stubs: 0x210
   __TEXT.__objc_stubs: 0x2760
   __TEXT.__objc_methlist: 0x23f4

   __TEXT.__objc_classname: 0x6e4
   __TEXT.__objc_methtype: 0x320
   __TEXT.__const: 0x108
-  __TEXT.__unwind_info: 0x7e0
+  __TEXT.__unwind_info: 0x818
   __DATA_CONST.__const: 0x2d0
   __DATA_CONST.__cfstring: 0x1e20
   __DATA_CONST.__objc_classlist: 0x238
Functions:
~ sub_100000c60 : 296 -> 284
~ sub_100000d88 -> sub_100000d7c : 272 -> 260
~ sub_100000e98 -> sub_100000e80 : 272 -> 260
~ sub_100000fa8 -> sub_100000f84 : 276 -> 264
~ sub_10000177c -> sub_10000174c : 168 -> 156
~ sub_100001824 -> sub_1000017e8 : 1192 -> 1180
~ sub_100001ccc -> sub_100001c84 : 204 -> 192
~ sub_100002a38 -> sub_1000029e4 : 388 -> 376
~ sub_100002ef4 -> sub_100002e94 : 332 -> 320
~ sub_10000338c -> sub_100003320 : 388 -> 376
~ sub_1000038ec -> sub_100003874 : 468 -> 456
~ sub_100003d84 -> sub_100003d00 : 268 -> 256
~ sub_100009330 -> sub_1000092a0 : 308 -> 296
~ sub_100009464 -> sub_1000093c8 : 308 -> 296
~ sub_100009608 -> sub_100009560 : 236 -> 224
~ sub_100009850 -> sub_10000979c : 240 -> 228
~ sub_10000a8f8 -> sub_10000a838 : 356 -> 344
~ sub_10000aa5c -> sub_10000a990 : 68 -> 56
~ sub_10000ba5c -> sub_10000b984 : 232 -> 220
~ sub_10000bbf4 -> sub_10000bb10 : 240 -> 228
~ sub_10000c1bc -> sub_10000c0cc : 356 -> 344
~ sub_10000c320 -> sub_10000c224 : 68 -> 56
~ sub_10000c394 -> sub_10000c28c : 460 -> 448
~ sub_10000c790 -> sub_10000c67c : 308 -> 296
~ sub_10000c8c4 -> sub_10000c7a4 : 40 -> 28
~ sub_10000d4d8 -> sub_10000d3ac : 84 -> 72
~ sub_10000def8 -> sub_10000ddc0 : 84 -> 72
~ sub_10000dfe8 -> sub_10000dea4 : 240 -> 228
~ sub_10000e5d4 -> sub_10000e484 : 440 -> 428
~ sub_10000e78c -> sub_10000e630 : 68 -> 56
~ sub_10000e8b4 -> sub_10000e74c : 912 -> 904
~ sub_10000ec44 -> sub_10000ead4 : 640 -> 628
~ sub_10000ef24 -> sub_10000eda8 : 68 -> 56
~ sub_100012a98 -> sub_100012910 : 240 -> 228
~ sub_100013b14 -> sub_100013980 : 356 -> 344
~ sub_100013c78 -> sub_100013ad8 : 68 -> 56
~ sub_100015054 -> sub_100014ea8 : 100 -> 88
~ sub_1000150c8 -> sub_100014f10 : 68 -> 56
~ sub_1000152b0 -> sub_1000150ec : 200 -> 188
~ sub_100015378 -> sub_1000151a8 : 288 -> 276
~ sub_100015498 -> sub_1000152bc : 40 -> 28
~ sub_1000154c0 -> sub_1000152d8 : 192 -> 180
~ sub_100015660 -> sub_10001546c : 240 -> 228
~ sub_100015c28 -> sub_100015a28 : 356 -> 344
~ sub_100015d8c -> sub_100015b80 : 68 -> 56
~ sub_100015f20 -> sub_100015d08 : 324 -> 312
~ sub_1000162dc -> sub_1000160b8 : 500 -> 488
~ sub_1000167d8 -> sub_1000165a8 : 404 -> 392
~ sub_100016b44 -> sub_100016908 : 528 -> 516
~ sub_100016fd0 -> sub_100016d88 : 696 -> 684
~ sub_1000177e0 -> sub_10001758c : 156 -> 144
~ sub_100017a1c -> sub_1000177bc : 376 -> 364
~ sub_100017dd0 -> sub_100017b64 : 156 -> 144
~ sub_100017fe8 -> sub_100017d70 : 68 -> 56
~ sub_1000190e8 -> sub_100018e64 : 128 -> 116
```
