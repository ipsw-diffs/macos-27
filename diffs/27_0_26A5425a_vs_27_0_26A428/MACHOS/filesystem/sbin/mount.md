## mount

> `/sbin/mount`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 766.0.1.0.0
-  __TEXT.__text: 0x3e00
+  __TEXT.__text: 0x3cf4
   __TEXT.__auth_stubs: 0x4c0
   __TEXT.__objc_stubs: 0x6a0
   __TEXT.__const: 0x38

   __TEXT.__cstring: 0xb02
   __TEXT.__oslogstring: 0xc
   __TEXT.__objc_methname: 0x515
-  __TEXT.__unwind_info: 0xf8
+  __TEXT.__unwind_info: 0x158
   __DATA_CONST.__const: 0x4a8
   __DATA_CONST.__cfstring: 0x220
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000b30 : 5588 -> 5592
~ sub_10000211c -> sub_100002120 : 144 -> 132
~ sub_1000021ac -> sub_1000021a4 : 80 -> 68
~ sub_1000021fc -> sub_1000021e8 : 68 -> 56
~ sub_10000225c -> sub_10000223c : 132 -> 120
~ sub_1000022e0 -> sub_1000022b4 : 264 -> 252
~ sub_1000023e8 -> sub_1000023b0 : 128 -> 116
~ sub_100002468 -> sub_100002424 : 128 -> 116
~ sub_1000024e8 -> sub_100002498 : 124 -> 112
~ sub_100002564 -> sub_100002508 : 88 -> 76
~ sub_1000025bc -> sub_100002554 : 76 -> 64
~ sub_100002658 -> sub_1000025e4 : 192 -> 180
~ sub_100002718 -> sub_100002698 : 112 -> 100
~ sub_100002788 -> sub_1000026fc : 92 -> 80
~ sub_100002864 -> sub_1000027cc : 80 -> 68
~ sub_1000028b4 -> sub_100002810 : 72 -> 60
~ sub_1000028fc -> sub_10000284c : 108 -> 96
~ sub_100002968 -> sub_1000028ac : 108 -> 96
~ sub_1000033f4 -> sub_10000332c : 204 -> 192
~ sub_1000036f4 -> sub_100003620 : 2252 -> 2244
~ sub_100003fc0 -> sub_100003ee4 : 156 -> 144
~ sub_100004418 -> sub_100004330 : 24 -> 12
~ sub_100004598 -> sub_1000044a4 : 164 -> 152
~ sub_10000463c -> sub_10000453c : 120 -> 108
```
