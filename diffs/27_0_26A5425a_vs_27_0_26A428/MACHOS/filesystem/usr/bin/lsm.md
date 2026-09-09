## lsm

> `/usr/bin/lsm`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 10.0.0.0.0
-  __TEXT.__text: 0x2d90
+  __TEXT.__text: 0x2ca0
   __TEXT.__auth_stubs: 0x410
   __TEXT.__objc_stubs: 0xb60
   __TEXT.__objc_methlist: 0x298

   __TEXT.__objc_methname: 0x862
   __TEXT.__objc_methtype: 0x185
   __TEXT.__const: 0x10
-  __TEXT.__unwind_info: 0x120
+  __TEXT.__unwind_info: 0x140
   __DATA_CONST.__const: 0x130
   __DATA_CONST.__cfstring: 0x3c0
   __DATA_CONST.__objc_classlist: 0x48
Functions:
~ sub_100000db0 : 136 -> 124
~ sub_100001504 -> sub_1000014f8 : 536 -> 512
~ sub_10000195c -> sub_100001938 : 216 -> 192
~ sub_100001ab0 -> sub_100001a74 : 320 -> 308
~ sub_100001cbc -> sub_100001c74 : 200 -> 188
~ sub_100002104 -> sub_1000020b0 : 160 -> 148
~ sub_1000023f0 -> sub_100002390 : 220 -> 196
~ sub_1000024cc -> sub_100002454 : 440 -> 380
~ sub_100002724 -> sub_100002670 : 540 -> 528
~ sub_100002a6c -> sub_1000029ac : 272 -> 260
~ sub_100002b7c -> sub_100002ab0 : 552 -> 540
~ sub_10000308c -> sub_100002fb4 : 316 -> 304
~ sub_1000038c0 -> sub_1000037dc : 76 -> 64
```
