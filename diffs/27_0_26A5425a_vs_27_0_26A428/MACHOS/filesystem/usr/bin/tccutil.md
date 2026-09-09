## tccutil

> `/usr/bin/tccutil`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 913.3.3.0.0
-  __TEXT.__text: 0xe10
+  __TEXT.__text: 0xd74
   __TEXT.__auth_stubs: 0x320
   __TEXT.__objc_stubs: 0x180
   __TEXT.__cstring: 0x471
   __TEXT.__const: 0x10
   __TEXT.__gcc_except_tab: 0x20
   __TEXT.__objc_methname: 0xfc
-  __TEXT.__unwind_info: 0xc8
+  __TEXT.__unwind_info: 0xf0
   __DATA_CONST.__const: 0xd0
   __DATA_CONST.__cfstring: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000ae0 : 68 -> 56
~ sub_100000b24 -> sub_100000b18 : 124 -> 112
~ sub_100000ba0 -> sub_100000b88 : 320 -> 308
~ sub_1000010a4 -> sub_100001080 : 28 -> 16
~ sub_1000010c0 -> sub_100001090 : 28 -> 16
~ sub_100001424 -> sub_1000013e8 : 76 -> 64
~ sub_100001470 -> sub_100001428 : 132 -> 120
~ sub_1000014f4 -> sub_1000014a0 : 140 -> 128
~ sub_100001580 -> sub_100001520 : 96 -> 84
~ sub_1000015e0 -> sub_100001574 : 204 -> 192
~ sub_1000016ac -> sub_100001634 : 88 -> 76
~ sub_100001704 -> sub_100001680 : 76 -> 64
~ sub_100001750 -> sub_1000016c0 : 32 -> 20
```
