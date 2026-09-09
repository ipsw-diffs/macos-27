## retimerd

> `/usr/libexec/retimerd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 33.0.0.0.0
-  __TEXT.__text: 0x6218
+  __TEXT.__text: 0x6054
   __TEXT.__auth_stubs: 0x6d0
   __TEXT.__objc_stubs: 0x80
   __TEXT.__gcc_except_tab: 0x6c0

   __TEXT.__const: 0x30
   __TEXT.__oslogstring: 0x3f
   __TEXT.__objc_methname: 0x8c
-  __TEXT.__unwind_info: 0x368
+  __TEXT.__unwind_info: 0x380
   __DATA_CONST.__const: 0x98
   __DATA_CONST.__cfstring: 0x780
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000c4c : 224 -> 212
~ sub_10000146c -> sub_100001460 : 680 -> 668
~ sub_100001714 -> sub_1000016fc : 104 -> 92
~ sub_10000177c -> sub_100001758 : 104 -> 92
~ sub_1000017e4 -> sub_1000017b4 : 280 -> 268
~ sub_100002130 -> sub_1000020f4 : 220 -> 208
~ sub_100002440 -> sub_1000023f8 : 432 -> 428
~ sub_1000025f0 -> sub_1000025a4 : 164 -> 152
~ sub_1000027b8 -> sub_100002760 : 196 -> 192
~ sub_1000033b8 -> sub_10000335c : 1008 -> 928
~ sub_1000037a8 -> sub_1000036fc : 2192 -> 2168
~ sub_100004038 -> sub_100003f74 : 64 -> 52
~ sub_10000422c -> sub_10000415c : 284 -> 268
~ sub_100004428 -> sub_100004348 : 656 -> 536
~ sub_100004ba0 -> sub_100004a48 : 336 -> 264
~ sub_100004cf0 -> sub_100004b50 : 144 -> 132
~ sub_1000060dc -> sub_100005f30 : 48 -> 36
~ sub_100006a04 -> sub_10000684c : 152 -> 140
```
