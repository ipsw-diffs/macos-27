## codesign

> `/usr/bin/codesign`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__dof_security_`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_dupclass`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

 135.0.6.0.0
-  __TEXT.__text: 0x23c00
+  __TEXT.__text: 0x23718
   __TEXT.__auth_stubs: 0x1680
   __TEXT.__objc_stubs: 0xcc0
   __TEXT.__init_offsets: 0xc
   __TEXT.__objc_methlist: 0x35c
-  __TEXT.__const: 0xfa8
+  __TEXT.__const: 0xfb8
   __TEXT.__gcc_except_tab: 0x1a1c
-  __TEXT.__cstring: 0x4178
+  __TEXT.__cstring: 0x4187
   __TEXT.__objc_methname: 0xcc7
   __TEXT.__objc_classname: 0xa0
   __TEXT.__objc_methtype: 0x1fb

   __TEXT.__swift5_proto: 0x14
   __TEXT.__oslogstring: 0xa1
   __TEXT.__dof_security_: 0x325
-  __TEXT.__unwind_info: 0x968
+  __TEXT.__unwind_info: 0xb28
   __TEXT.__eh_frame: 0x90
   __DATA_CONST.__const: 0x1698
-  __DATA_CONST.__cfstring: 0x1140
+  __DATA_CONST.__cfstring: 0x1160
   __DATA_CONST.__objc_classlist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x10

   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 522
   Symbols:   584
-  CStrings:  813
+  CStrings:  814
 
Functions:
~ sub_1000018d8 : 6496 -> 6488
~ sub_1000034bc -> sub_1000034b4 : 236 -> 224
~ sub_10000372c -> sub_100003718 : 164 -> 152
~ sub_10000615c -> sub_10000613c : 236 -> 224
~ sub_1000069c8 -> sub_10000699c : 144 -> 132
~ sub_1000089e8 -> sub_1000089b0 : 180 -> 156
~ sub_100008a9c -> sub_100008a4c : 92 -> 80
~ sub_100008ed8 -> sub_100008e7c : 280 -> 268
~ sub_100009a68 -> sub_100009a00 : 56 -> 44
~ sub_10000a060 -> sub_100009fec : 68 -> 56
~ sub_10000e338 -> sub_10000e2b8 : 344 -> 320
~ sub_10000e4dc -> sub_10000e444 : 148 -> 136
~ sub_10000e7a0 -> sub_10000e6fc : 132 -> 120
~ sub_10000ea68 -> sub_10000e9b8 : 268 -> 256
~ sub_10000ebc0 -> sub_10000eb04 : 44 -> 32
~ sub_10000f188 -> sub_10000f0c0 : 268 -> 260
~ sub_10000f3c0 -> sub_10000f2f0 : 88 -> 76
~ sub_10000f5e0 -> sub_10000f504 : 120 -> 108
~ sub_10000f8b8 -> sub_10000f7d0 : 120 -> 108
~ sub_10000facc -> sub_10000f9d8 : 1660 -> 1620
~ sub_100010148 -> sub_10001002c : 400 -> 380
~ sub_1000102d8 -> sub_1000101a8 : 324 -> 280
~ sub_1000104a0 -> sub_100010344 : 240 -> 228
~ sub_100010590 -> sub_100010428 : 524 -> 504
~ sub_100010814 -> sub_100010698 : 132 -> 120
~ sub_10001090c -> sub_100010784 : 1732 -> 1640
~ sub_100010fd0 -> sub_100010dec : 100 -> 88
~ sub_100011034 -> sub_100010e44 : 476 -> 456
~ sub_100011210 -> sub_10001100c : 452 -> 432
~ sub_100011538 -> sub_100011320 : 108 -> 96
~ sub_1000115a4 -> sub_100011380 : 84 -> 72
~ sub_100011748 -> sub_100011518 : 776 -> 756
~ sub_100011a70 -> sub_10001182c : 260 -> 252
~ sub_100011b74 -> sub_100011928 : 1404 -> 1384
~ sub_1000121e0 -> sub_100011f80 : 56 -> 44
~ sub_100012228 -> sub_100011fbc : 56 -> 44
~ sub_100012260 -> sub_100011fe8 : 80 -> 68
~ sub_10001242c -> sub_1000121a8 : 80 -> 68
~ sub_1000125e0 -> sub_100012350 : 788 -> 776
~ sub_100012984 -> sub_1000126e8 : 84 -> 72
~ sub_100012f04 -> sub_100012c5c : 80 -> 68
~ sub_100013418 -> sub_100013164 : 152 -> 140
~ sub_100013580 -> sub_1000132c0 : 2240 -> 2228
~ sub_1000145e4 -> sub_100014318 : 416 -> 404
~ sub_100014784 -> sub_1000144ac : 400 -> 388
~ sub_100014914 -> sub_100014630 : 400 -> 388
~ sub_100015c4c -> sub_10001595c : 96 -> 84
~ sub_100015cac -> sub_1000159b0 : 1944 -> 1932
~ sub_100016b38 -> sub_100016830 : 972 -> 960
~ sub_1000171e4 -> sub_100016ed0 : 116 -> 104
~ sub_10001a2e8 -> sub_100019fc8 : 3172 -> 3076
~ sub_10001ba68 -> sub_10001b6e8 : 1436 -> 1388
~ sub_10001c004 -> sub_10001bc54 : 224 -> 212
~ sub_10001c44c -> sub_10001c090 : 340 -> 328
~ sub_10001c668 -> sub_10001c2a0 : 292 -> 268
~ sub_10001c900 -> sub_10001c520 : 72 -> 60
~ sub_10001d2f8 -> sub_10001cf0c : 56 -> 44
~ sub_10001d330 -> sub_10001cf38 : 56 -> 44
~ sub_10001d368 -> sub_10001cf64 : 56 -> 44
~ sub_10001d884 -> sub_10001d474 : 100 -> 88
~ sub_10001d908 -> sub_10001d4ec : 152 -> 140
~ sub_10001dd4c -> sub_10001d924 : 68 -> 56
~ sub_10001dd90 -> sub_10001d95c : 236 -> 224
~ sub_10001de7c -> sub_10001da3c : 3332 -> 3340
~ sub_10001ef14 -> sub_10001eadc : 112 -> 100
~ sub_10001ef84 -> sub_10001eb40 : 176 -> 164
~ sub_10001f034 -> sub_10001ebe4 : 204 -> 192
~ sub_10001ffb4 -> sub_10001fb58 : 100 -> 88
~ sub_1000200f0 -> sub_10001fc88 : 132 -> 120
~ sub_100020220 -> sub_10001fdac : 228 -> 212
~ sub_100020444 -> sub_10001ffc0 : 564 -> 560
~ sub_100020c70 -> sub_1000207e8 : 164 -> 152
~ sub_100020d64 -> sub_1000208d0 : 112 -> 100
~ sub_100020e88 -> sub_1000209e8 : 128 -> 116
~ sub_100020f50 -> sub_100020aa4 : 196 -> 192
~ sub_100021450 -> sub_100020fa0 : 600 -> 596
~ sub_1000216a8 -> sub_1000211f4 : 100 -> 88
~ sub_100021734 -> sub_100021274 : 152 -> 140
~ sub_100021f10 -> sub_100021a44 : 300 -> 284
~ sub_10002238c -> sub_100021eb0 : 28 -> 16
~ sub_1000224f8 -> sub_100022010 : 212 -> 200
~ sub_100022650 -> sub_10002215c : 572 -> 568
~ sub_100022e6c -> sub_100022974 : 148 -> 160
~ sub_1000234a0 -> sub_100022fb4 : 1200 -> 1192
~ sub_100023c38 -> sub_100023744 : 2628 -> 2660
~ sub_1000246a0 -> sub_1000241cc : 40 -> 28
~ sub_100024928 -> sub_100024448 : 488 -> 480
CStrings:
+ "arch_arm64e_v1"
```
