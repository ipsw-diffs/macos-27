## bless

> `/usr/sbin/bless`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 335.0.2.0.0
-  __TEXT.__text: 0x1fee0
+  __TEXT.__text: 0x1fe20
   __TEXT.__auth_stubs: 0x10f0
   __TEXT.__objc_stubs: 0x3c0
   __TEXT.__const: 0x3b0
   __TEXT.__cstring: 0x9aec
   __TEXT.__oslogstring: 0x43c
   __TEXT.__objc_methname: 0x257
-  __TEXT.__unwind_info: 0x348
+  __TEXT.__unwind_info: 0x4c8
   __TEXT.__eh_frame: 0x7c
   __DATA_CONST.__const: 0xf8
   __DATA_CONST.__cfstring: 0x1280
Functions:
~ sub_1000016ec : 204 -> 180
~ sub_100001844 -> sub_10000182c : 32 -> 20
~ sub_100001864 -> sub_100001840 : 32 -> 20
~ sub_100001884 -> sub_100001854 : 104 -> 92
~ sub_1000084e4 -> sub_1000084a8 : 628 -> 632
~ sub_100008758 -> sub_100008720 : 96 -> 84
~ sub_10000acf0 -> sub_10000acac : 92 -> 80
~ sub_10000d12c -> sub_10000d0dc : 488 -> 480
~ sub_10000fed4 -> sub_10000fe7c : 144 -> 132
~ sub_100011874 -> sub_100011810 : 712 -> 708
~ sub_100012394 -> sub_10001232c : 1104 -> 1100
~ sub_100018f04 -> sub_100018e98 : 104 -> 92
~ sub_100018f6c -> sub_100018ef4 : 60 -> 48
~ sub_10001c1b0 -> sub_10001c12c : 172 -> 160
~ sub_10001c25c -> sub_10001c1cc : 336 -> 324
~ sub_10001d328 -> sub_10001d28c : 236 -> 224
~ sub_10001e4f0 -> sub_10001e448 : 68 -> 56
~ sub_10001f204 -> sub_10001f150 : 88 -> 76
```
