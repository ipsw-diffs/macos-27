## bootinstalld

> `/usr/libexec/bootinstalld`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 669.0.2.0.0
-  __TEXT.__text: 0x4db0
+  __TEXT.__text: 0x4c60
   __TEXT.__auth_stubs: 0x2f0
   __TEXT.__objc_stubs: 0xf60
   __TEXT.__objc_methlist: 0x33c

   __TEXT.__objc_methtype: 0x310
   __TEXT.__const: 0x18
   __TEXT.__gcc_except_tab: 0x268
-  __TEXT.__unwind_info: 0x180
+  __TEXT.__unwind_info: 0x1c0
   __DATA_CONST.__const: 0x2f0
   __DATA_CONST.__cfstring: 0x240
   __DATA_CONST.__objc_classlist: 0x18
Functions:
~ sub_100000edc : 84 -> 72
~ sub_1000010e4 -> sub_1000010d8 : 108 -> 96
~ sub_100001150 -> sub_100001138 : 136 -> 124
~ sub_100001200 -> sub_1000011dc : 68 -> 56
~ sub_100001244 -> sub_100001214 : 68 -> 56
~ sub_100001408 -> sub_1000013cc : 176 -> 164
~ sub_1000014b8 -> sub_100001470 : 60 -> 48
~ sub_1000014f4 -> sub_1000014a0 : 60 -> 48
~ sub_1000015f4 -> sub_100001594 : 132 -> 120
~ sub_100001678 -> sub_10000160c : 840 -> 828
~ sub_100001c44 -> sub_100001bcc : 348 -> 336
~ sub_100002068 -> sub_100001fe4 : 80 -> 68
~ sub_1000020b8 -> sub_100002028 : 72 -> 60
~ sub_100002510 -> sub_100002474 : 180 -> 168
~ sub_100002810 -> sub_100002768 : 96 -> 84
~ sub_100002870 -> sub_1000027bc : 84 -> 72
~ sub_1000028c4 -> sub_100002804 : 2184 -> 2172
~ sub_100003688 -> sub_1000035bc : 104 -> 92
~ sub_1000036f0 -> sub_100003618 : 92 -> 80
~ sub_100004474 -> sub_100004390 : 88 -> 76
~ sub_1000044cc -> sub_1000043dc : 80 -> 68
~ sub_100004694 -> sub_100004598 : 104 -> 92
~ sub_1000046fc -> sub_1000045f4 : 88 -> 76
~ sub_100004d48 -> sub_100004c34 : 272 -> 260
~ sub_100004e80 -> sub_100004d60 : 68 -> 56
~ sub_100005350 -> sub_100005224 : 64 -> 52
~ sub_1000053dc -> sub_1000052a4 : 104 -> 92
~ sub_100005a34 -> sub_1000058f0 : 32 -> 20
```
