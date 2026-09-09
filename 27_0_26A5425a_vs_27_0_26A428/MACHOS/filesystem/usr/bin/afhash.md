## afhash

> `/usr/bin/afhash`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 830.0.0.0.0
-  __TEXT.__text: 0x12c0
+  __TEXT.__text: 0x129c
   __TEXT.__auth_stubs: 0x220
   __TEXT.__const: 0x10
   __TEXT.__gcc_except_tab: 0xa0
   __TEXT.__cstring: 0x886
-  __TEXT.__unwind_info: 0xb0
+  __TEXT.__unwind_info: 0xb8
   __DATA_CONST.__const: 0x80
   __DATA_CONST.__auth_got: 0x118
   __DATA_CONST.__got: 0x10
Functions:
~ sub_10000115c : 544 -> 532
~ sub_10000137c -> sub_100001370 : 144 -> 132
~ sub_1000018f0 -> sub_1000018d8 : 152 -> 140
```
