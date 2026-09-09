## xargs

> `/usr/bin/xargs`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 334.0.0.0.0
-  __TEXT.__text: 0x163c
+  __TEXT.__text: 0x162c
   __TEXT.__auth_stubs: 0x2d0
   __TEXT.__const: 0x4c
   __TEXT.__cstring: 0x364
-  __TEXT.__unwind_info: 0x80
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__const: 0x120
   __DATA_CONST.__auth_got: 0x168
   __DATA_CONST.__got: 0x20
Functions:
~ sub_1000007ac : 3360 -> 3368
~ sub_1000016b8 -> sub_1000016c0 : 424 -> 412
~ sub_100001ab4 -> sub_100001ab0 : 24 -> 12
```
