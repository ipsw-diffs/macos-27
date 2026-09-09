## mobilerepaird

> `/usr/libexec/mobilerepaird`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 1307.1.2.0.0
-  __TEXT.__text: 0xafa0
+  __TEXT.__text: 0xaf24
   __TEXT.__auth_stubs: 0x480
-  __TEXT.__objc_stubs: 0x1960
+  __TEXT.__objc_stubs: 0x1980
   __TEXT.__objc_methlist: 0x904
   __TEXT.__const: 0xa8
   __TEXT.__gcc_except_tab: 0x3b0
-  __TEXT.__objc_methname: 0x1dcd
-  __TEXT.__cstring: 0x199a
+  __TEXT.__objc_methname: 0x1de6
+  __TEXT.__cstring: 0x1b02
   __TEXT.__oslogstring: 0x76c
   __TEXT.__objc_classname: 0x162
   __TEXT.__objc_methtype: 0x364
-  __TEXT.__unwind_info: 0x248
+  __TEXT.__unwind_info: 0x2b8
   __DATA_CONST.__const: 0x3e0
-  __DATA_CONST.__cfstring: 0x15c0
+  __DATA_CONST.__cfstring: 0x1740
   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__auth_got: 0x250
   __DATA_CONST.__got: 0x280
   __DATA.__objc_const: 0x10d8
-  __DATA.__objc_selrefs: 0x810
+  __DATA.__objc_selrefs: 0x818
   __DATA.__objc_ivar: 0xb0
   __DATA.__objc_data: 0x370
   __DATA.__data: 0x190

   - /usr/lib/libobjc.A.dylib
   Functions: 218
   Symbols:   155
-  CStrings:  641
+  CStrings:  654
 
Functions:
~ sub_1000031cc : 228 -> 216
~ sub_100003440 -> sub_100003434 : 124 -> 112
~ sub_1000034bc -> sub_1000034a4 : 124 -> 112
~ sub_100004a28 -> sub_100004a04 : 72 -> 60
~ sub_100004a70 -> sub_100004a40 : 64 -> 52
~ sub_100004d08 -> sub_100004ccc : 884 -> 872
~ sub_10000507c -> sub_100005034 : 60 -> 48
~ sub_1000050b8 -> sub_100005064 : 60 -> 48
~ sub_1000050f8 -> sub_100005098 : 396 -> 384
~ sub_10000556c -> sub_100005500 : 344 -> 332
~ sub_1000056dc -> sub_100005664 : 32 -> 20
~ sub_100005718 -> sub_100005694 : 32 -> 20
~ sub_1000057fc -> sub_10000576c : 1168 -> 1320
~ sub_100005c8c -> sub_100005c94 : 208 -> 196
~ sub_100005d5c -> sub_100005d58 : 160 -> 148
~ sub_100005dfc -> sub_100005dec : 116 -> 104
~ sub_100005f34 -> sub_100005f18 : 1028 -> 1172
~ sub_10000633c -> sub_1000063b0 : 160 -> 148
~ sub_1000063dc -> sub_100006444 : 116 -> 104
~ sub_1000065b4 -> sub_100006610 : 160 -> 148
~ sub_100006654 -> sub_1000066a4 : 108 -> 96
~ sub_100007078 -> sub_1000070bc : 160 -> 148
~ sub_100007118 -> sub_100007150 : 108 -> 96
~ sub_100007414 -> sub_100007440 : 160 -> 148
~ sub_1000074b4 -> sub_1000074d4 : 116 -> 104
~ sub_100007674 -> sub_100007688 : 160 -> 148
~ sub_100007714 -> sub_10000771c : 108 -> 96
~ sub_100007e8c -> sub_100007e88 : 468 -> 456
~ sub_100008bcc -> sub_100008bbc : 68 -> 56
~ sub_100008c10 -> sub_100008bf4 : 68 -> 56
~ sub_1000097c4 -> sub_10000979c : 160 -> 148
~ sub_100009864 -> sub_100009830 : 64 -> 52
~ sub_100009ec8 -> sub_100009e88 : 92 -> 80
~ sub_100009f24 -> sub_100009ed8 : 92 -> 80
~ sub_10000a868 -> sub_10000a810 : 76 -> 64
~ sub_10000a8b4 -> sub_10000a850 : 76 -> 64
~ sub_10000b87c -> sub_10000b80c : 32 -> 20
CStrings:
+ "FINISH_BATTERYMAIN_REPAIR_DESC"
+ "FINISH_BATTERYMAIN_REPAIR_TITLE"
+ "FINISH_DISPLAYOUTR_REPAIR_DESC"
+ "FINISH_DISPLAYOUTR_REPAIR_TITLE"
+ "IMPORTANT_BATTERYMAIN_MESSAGE"
+ "IMPORTANT_DISPLAYOUTR_MESSAGE"
+ "UNABLE_TO_VERIFY_BATTERYMAIN_MESSAGE"
+ "UNABLE_TO_VERIFY_BATTERYMAIN_NOTIF_TEXT"
+ "UNABLE_TO_VERIFY_DISPLAYOUTR_MESSAGE"
+ "UNABLE_TO_VERIFY_DISPLAYOUTR_NOTIF_TEXT"
+ "isFDRDataClassSupported:"
+ "tcrt-outr"
+ "vcrt-4081"
```
