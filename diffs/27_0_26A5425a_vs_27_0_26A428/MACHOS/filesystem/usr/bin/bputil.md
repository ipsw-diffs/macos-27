## bputil

> `/usr/bin/bputil`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_selrefs`

```diff

 304.0.0.0.0
-  __TEXT.__text: 0xb0ac
+  __TEXT.__text: 0xaf8c
   __TEXT.__auth_stubs: 0x650
   __TEXT.__objc_stubs: 0x680
   __TEXT.__const: 0xcf0

   __TEXT.__oslogstring: 0x160
   __TEXT.__gcc_except_tab: 0xe4
   __TEXT.__objc_methname: 0x414
-  __TEXT.__unwind_info: 0x1f8
+  __TEXT.__unwind_info: 0x338
   __DATA_CONST.__const: 0x470
   __DATA_CONST.__cfstring: 0x260
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000cb0 : 220 -> 208
~ sub_100000ff4 -> sub_100000fe8 : 32 -> 20
~ sub_100001030 -> sub_100001018 : 32 -> 20
~ sub_10000107c -> sub_100001058 : 48 -> 36
~ sub_1000010ec -> sub_1000010bc : 24 -> 12
~ sub_100001104 -> sub_1000010c8 : 32 -> 20
~ sub_100001540 -> sub_1000014f8 : 656 -> 632
~ sub_100002404 -> sub_1000023a4 : 80 -> 68
~ sub_100002454 -> sub_1000023e8 : 68 -> 56
~ sub_100002610 -> sub_100002598 : 268 -> 256
~ sub_1000028d8 -> sub_100002854 : 648 -> 636
~ sub_100002b60 -> sub_100002ad0 : 220 -> 208
~ sub_100002c3c -> sub_100002ba0 : 148 -> 136
~ sub_100002d68 -> sub_100002cc0 : 9692 -> 9680
~ sub_100006a04 -> sub_100006950 : 32 -> 20
~ sub_100006a34 -> sub_100006974 : 32 -> 20
~ sub_100006a6c -> sub_1000069a0 : 24 -> 12
~ sub_100006be8 -> sub_100006b10 : 32 -> 20
~ sub_100006fe0 -> sub_100006efc : 28 -> 16
~ sub_1000070f4 -> sub_100007004 : 28 -> 16
~ sub_1000071a8 -> sub_1000070ac : 488 -> 480
~ sub_100008004 -> sub_100007f00 : 56 -> 44
~ sub_10000804c -> sub_100007f3c : 24 -> 12
~ sub_1000085bc -> sub_1000084a0 : 580 -> 576
```
