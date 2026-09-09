## gzip

> `/usr/bin/gzip`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 487.0.1.0.0
-  __TEXT.__text: 0x588c
+  __TEXT.__text: 0x5850
   __TEXT.__auth_stubs: 0x5e0
   __TEXT.__const: 0x67d
   __TEXT.__cstring: 0x1058
-  __TEXT.__unwind_info: 0xf8
+  __TEXT.__unwind_info: 0x180
   __DATA_CONST.__const: 0x2a0
   __DATA_CONST.__auth_got: 0x2f0
   __DATA_CONST.__got: 0x30
Functions:
~ sub_10000152c : 348 -> 336
~ sub_100001848 -> sub_10000183c : 80 -> 68
~ sub_1000024f8 -> sub_1000024e0 : 232 -> 220
~ sub_100002dd4 -> sub_100002db0 : 3072 -> 3084
~ sub_1000039d4 -> sub_1000039bc : 204 -> 192
~ sub_100003aa0 -> sub_100003a7c : 188 -> 176
~ sub_100003b5c -> sub_100003b2c : 124 -> 120
~ sub_100003c90 -> sub_100003c5c : 1344 -> 1336
```
