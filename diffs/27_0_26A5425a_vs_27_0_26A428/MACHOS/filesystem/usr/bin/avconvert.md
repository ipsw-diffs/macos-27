## avconvert

> `/usr/bin/avconvert`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 2450.77.5.1.0
-  __TEXT.__text: 0x488c
+  __TEXT.__text: 0x479c
   __TEXT.__auth_stubs: 0x440
   __TEXT.__objc_stubs: 0x13a0
   __TEXT.__objc_methlist: 0x59c

   __TEXT.__objc_methname: 0x1698
   __TEXT.__objc_classname: 0x54
   __TEXT.__objc_methtype: 0x450
-  __TEXT.__unwind_info: 0x130
+  __TEXT.__unwind_info: 0x170
   __DATA_CONST.__const: 0x120
   __DATA_CONST.__cfstring: 0x14a0
   __DATA_CONST.__objc_classlist: 0x10
Functions:
~ sub_1000015ec : 72 -> 60
~ sub_100002780 -> sub_100002774 : 216 -> 204
~ sub_100002858 -> sub_100002840 : 120 -> 108
~ sub_10000435c -> sub_100004338 : 160 -> 148
~ sub_1000043fc -> sub_1000043cc : 128 -> 116
~ sub_100004490 -> sub_100004454 : 80 -> 68
~ sub_1000044e0 -> sub_100004498 : 68 -> 56
~ sub_1000046b4 -> sub_100004660 : 308 -> 296
~ sub_1000048a4 -> sub_100004844 : 112 -> 100
~ sub_100004914 -> sub_1000048a8 : 92 -> 80
~ sub_100004a8c -> sub_100004a14 : 96 -> 84
~ sub_100004aec -> sub_100004a68 : 112 -> 100
~ sub_100004b5c -> sub_100004acc : 92 -> 80
~ sub_100004dd4 -> sub_100004d38 : 140 -> 128
~ sub_100005200 -> sub_100005158 : 32 -> 20
~ sub_100005220 -> sub_10000516c : 32 -> 20
~ sub_10000524c -> sub_10000518c : 32 -> 20
~ sub_100005530 -> sub_100005464 : 88 -> 76
~ sub_100005588 -> sub_1000054b0 : 96 -> 84
~ sub_1000055e8 -> sub_100005504 : 92 -> 80
```
