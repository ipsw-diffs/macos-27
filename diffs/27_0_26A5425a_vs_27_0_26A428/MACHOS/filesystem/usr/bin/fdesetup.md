## fdesetup

> `/usr/bin/fdesetup`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1842.1.1.0.0
-  __TEXT.__text: 0x2c2d4
+  __TEXT.__text: 0x2c08c
   __TEXT.__auth_stubs: 0xfb0
   __TEXT.__objc_stubs: 0x27a0
   __TEXT.__objc_methlist: 0x61c

   __TEXT.__objc_classname: 0x6d
   __TEXT.__objc_methname: 0x23d9
   __TEXT.__objc_methtype: 0x377
-  __TEXT.__unwind_info: 0x728
+  __TEXT.__unwind_info: 0xb70
   __DATA_CONST.__const: 0x590
   __DATA_CONST.__cfstring: 0x22e0
   __DATA_CONST.__objc_classlist: 0x28
Functions:
~ sub_100001a20 : 80 -> 68
~ sub_100001a70 -> sub_100001a64 : 84 -> 72
~ sub_100001ac4 -> sub_100001aac : 96 -> 84
~ sub_100002944 -> sub_100002920 : 128 -> 116
~ sub_1000029c4 -> sub_100002994 : 104 -> 92
~ sub_100002c14 -> sub_100002bd8 : 28 -> 16
~ sub_100003a94 -> sub_100003a4c : 80 -> 68
~ sub_100003ae4 -> sub_100003a90 : 68 -> 56
~ sub_10000440c -> sub_1000043ac : 144 -> 132
~ sub_10000449c -> sub_100004430 : 116 -> 104
~ sub_1000053d8 -> sub_100005360 : 96 -> 84
~ sub_100005438 -> sub_1000053b4 : 80 -> 68
~ sub_10000556c -> sub_1000054dc : 76 -> 64
~ sub_100006988 -> sub_1000068ec : 128 -> 116
~ sub_100006a08 -> sub_100006960 : 104 -> 92
~ sub_1000074b0 -> sub_1000073fc : 32 -> 20
~ sub_1000074d0 -> sub_100007410 : 28 -> 16
~ sub_1000074ec -> sub_100007420 : 28 -> 16
~ sub_100007508 -> sub_100007430 : 32 -> 20
~ sub_100007528 -> sub_100007444 : 32 -> 20
~ sub_10000bbc8 -> sub_10000bad8 : 80 -> 68
~ sub_10000bc18 -> sub_10000bb1c : 68 -> 56
~ sub_10000c164 -> sub_10000c05c : 24 -> 12
~ sub_10000c17c -> sub_10000c068 : 688 -> 692
~ sub_10000d1cc -> sub_10000d0bc : 428 -> 416
~ sub_10000d378 -> sub_10000d25c : 104 -> 80
~ sub_10000d4bc -> sub_10000d388 : 552 -> 540
~ sub_10000d6e4 -> sub_10000d5a4 : 380 -> 368
~ sub_10000d860 -> sub_10000d714 : 112 -> 100
~ sub_10000d8d0 -> sub_10000d778 : 112 -> 100
~ sub_10000dd74 -> sub_10000dc10 : 104 -> 80
~ sub_1000178b8 -> sub_10001773c : 140 -> 128
~ sub_100018f1c -> sub_100018d94 : 344 -> 332
~ sub_100019074 -> sub_100018ee0 : 80 -> 68
~ sub_1000190c4 -> sub_100018f24 : 68 -> 56
~ sub_1000244ac -> sub_100024300 : 220 -> 208
~ sub_100024588 -> sub_1000243d0 : 76 -> 64
~ sub_10002514c -> sub_100024f88 : 160 -> 148
~ sub_1000257a8 -> sub_1000255d8 : 32 -> 20
~ sub_10002580c -> sub_100025630 : 36 -> 24
~ sub_100025830 -> sub_100025648 : 32 -> 20
~ sub_100025860 -> sub_10002566c : 28 -> 16
~ sub_1000258ac -> sub_1000256ac : 40 -> 28
~ sub_100025a3c -> sub_100025830 : 28 -> 16
~ sub_100025a68 -> sub_100025850 : 28 -> 16
~ sub_100026544 -> sub_100026320 : 28 -> 16
~ sub_1000265c0 -> sub_100026390 : 32 -> 20
~ sub_10002681c -> sub_1000265e0 : 40 -> 28
CStrings:
+ "20:26:59"
+ "Aug  8 2026"
- "03:01:59"
- "Aug 10 2026"
```
