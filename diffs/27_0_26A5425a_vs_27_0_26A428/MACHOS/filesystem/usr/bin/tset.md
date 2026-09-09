## tset

> `/usr/bin/tset`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 81.0.0.0.0
-  __TEXT.__text: 0x14f0
+  __TEXT.__text: 0x14e0
   __TEXT.__auth_stubs: 0x300
   __TEXT.__const: 0x337
   __TEXT.__cstring: 0x253
-  __TEXT.__unwind_info: 0x98
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__auth_got: 0x180
   __DATA_CONST.__got: 0x40
   __DATA.__data: 0x14
Functions:
~ sub_100001304 : 948 -> 944
~ sub_1000016b8 -> sub_1000016b4 : 344 -> 332
```
