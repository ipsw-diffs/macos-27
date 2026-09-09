## installer

> `/usr/sbin/installer`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 604.0.1.0.0
-  __TEXT.__text: 0x608c
+  __TEXT.__text: 0x5fa8
   __TEXT.__auth_stubs: 0x2a0
   __TEXT.__objc_stubs: 0x1ba0
   __TEXT.__objc_methlist: 0x5bc

   __TEXT.__objc_methname: 0x1569
   __TEXT.__objc_classname: 0x9e
   __TEXT.__objc_methtype: 0x31d
-  __TEXT.__unwind_info: 0x190
+  __TEXT.__unwind_info: 0x1d8
   __DATA_CONST.__const: 0xc8
   __DATA_CONST.__cfstring: 0xfc0
   __DATA_CONST.__objc_classlist: 0x18
Functions:
~ sub_100001098 : 1576 -> 1564
~ sub_100001c3c -> sub_100001c30 : 216 -> 192
~ sub_100002750 -> sub_10000272c : 72 -> 60
~ sub_100002908 -> sub_1000028d8 : 52 -> 40
~ sub_10000310c -> sub_1000030d0 : 28 -> 16
~ sub_100003128 -> sub_1000030e0 : 24 -> 12
~ sub_100003140 -> sub_1000030ec : 24 -> 12
~ sub_100003778 -> sub_100003718 : 252 -> 216
~ sub_100004df4 -> sub_100004d70 : 380 -> 368
~ sub_100004f70 -> sub_100004ee0 : 380 -> 368
~ sub_1000050ec -> sub_100005050 : 320 -> 308
~ sub_1000053ac -> sub_100005304 : 128 -> 116
~ sub_1000054a4 -> sub_1000053f0 : 320 -> 308
~ sub_100005644 -> sub_100005584 : 96 -> 84
~ sub_100005b18 -> sub_100005a4c : 288 -> 276
~ sub_1000066b0 -> sub_1000065d8 : 560 -> 548
```
