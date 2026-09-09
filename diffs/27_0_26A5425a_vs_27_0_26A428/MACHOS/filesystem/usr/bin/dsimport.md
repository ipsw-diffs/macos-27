## dsimport

> `/usr/bin/dsimport`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 106.0.0.0.0
-  __TEXT.__text: 0x633c
+  __TEXT.__text: 0x62f4
   __TEXT.__auth_stubs: 0x360
   __TEXT.__objc_stubs: 0x11e0
   __TEXT.__objc_methlist: 0x384

   __TEXT.__objc_classname: 0x49
   __TEXT.__objc_methtype: 0x1af
   __TEXT.__const: 0xa0
-  __TEXT.__unwind_info: 0x118
+  __TEXT.__unwind_info: 0x158
   __DATA_CONST.__cfstring: 0xcc0
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_catlist: 0x8
Functions:
~ sub_100003350 : 256 -> 232
~ sub_100003d90 -> sub_100003d78 : 336 -> 324
~ sub_10000573c -> sub_100005718 : 192 -> 180
~ sub_1000065a4 -> sub_100006574 : 284 -> 272
~ sub_100006d40 -> sub_100006d04 : 228 -> 216
```
