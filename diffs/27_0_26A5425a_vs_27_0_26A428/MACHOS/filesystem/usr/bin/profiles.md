## profiles

> `/usr/bin/profiles`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1842.1.1.0.0
-  __TEXT.__text: 0x111c4
+  __TEXT.__text: 0x110e4
   __TEXT.__auth_stubs: 0xac0
   __TEXT.__objc_stubs: 0x1240
   __TEXT.__objc_methlist: 0x68

   __TEXT.__objc_classname: 0x12
   __TEXT.__objc_methtype: 0x4b
   __TEXT.__objc_methname: 0xd91
-  __TEXT.__unwind_info: 0x260
+  __TEXT.__unwind_info: 0x408
   __DATA_CONST.__const: 0x228
   __DATA_CONST.__cfstring: 0x1220
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ sub_100001108 : 220 -> 208
~ sub_1000037c8 -> sub_1000037bc : 28 -> 16
~ sub_100004cec -> sub_100004cd4 : 96 -> 84
~ sub_100004d4c -> sub_100004d28 : 80 -> 68
~ sub_100006dd8 -> sub_100006da8 : 160 -> 148
~ sub_100008234 -> sub_1000081f8 : 748 -> 736
~ sub_10000a4c8 -> sub_10000a480 : 32 -> 20
~ sub_10000a500 -> sub_10000a4ac : 24 -> 12
~ sub_10000a518 -> sub_10000a4b8 : 24 -> 12
~ sub_10000a5a0 -> sub_10000a534 : 140 -> 128
~ sub_10000a62c -> sub_10000a5b4 : 100 -> 88
~ sub_10000bf50 -> sub_10000becc : 24 -> 12
~ sub_10000cc70 -> sub_10000cbe0 : 160 -> 148
~ sub_10000d484 -> sub_10000d3e8 : 28 -> 16
~ sub_10000dc78 -> sub_10000dbd0 : 356 -> 344
~ sub_10000dddc -> sub_10000dd28 : 688 -> 692
~ sub_10000f4f8 -> sub_10000f448 : 112 -> 100
~ sub_10000f568 -> sub_10000f4ac : 80 -> 68
~ sub_10000f5b8 -> sub_10000f4f0 : 68 -> 56
~ sub_10000fa64 -> sub_10000f990 : 620 -> 608
CStrings:
+ "20:32:34"
+ "Aug  8 2026"
- "03:05:49"
- "Aug 10 2026"
```
