## kuncd

> `/usr/libexec/kuncd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 22.0.0.0.0
-  __TEXT.__text: 0x3084
+  __TEXT.__text: 0x305c
   __TEXT.__auth_stubs: 0x580
   __TEXT.__const: 0x70
   __TEXT.__cstring: 0x6ce
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0xf0
   __DATA_CONST.__const: 0x160
   __DATA_CONST.__cfstring: 0x7c0
   __DATA_CONST.__auth_got: 0x2c0
Functions:
~ sub_1000020f4 : 168 -> 156
~ sub_1000026e8 -> sub_1000026dc : 304 -> 292
~ sub_100003134 -> sub_10000311c : 672 -> 664
~ sub_1000033d4 -> sub_1000033b4 : 932 -> 924
```
