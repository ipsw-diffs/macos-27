## ncal

> `/usr/bin/ncal`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 45.0.0.0.0
-  __TEXT.__text: 0x2474
+  __TEXT.__text: 0x245c
   __TEXT.__auth_stubs: 0x270
   __TEXT.__const: 0x2c8
   __TEXT.__cstring: 0x59e
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xe8
   __DATA_CONST.__auth_got: 0x138
   __DATA_CONST.__got: 0x28
   __DATA_CONST.__auth_ptr: 0x8
Functions:
~ sub_100000cb0 : 56 -> 44
~ sub_100000d78 -> sub_100000d6c : 56 -> 44
~ sub_100000db0 -> sub_100000d98 : 5760 -> 5776
~ sub_100002488 -> sub_100002480 : 104 -> 80
~ sub_1000024f0 -> sub_1000024d0 : 324 -> 332
```
