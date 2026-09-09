## sdiff

> `/usr/bin/sdiff`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 77.0.0.0.0
-  __TEXT.__text: 0x202c
+  __TEXT.__text: 0x2014
   __TEXT.__auth_stubs: 0x3b0
   __TEXT.__const: 0x38
   __TEXT.__cstring: 0xb76
-  __TEXT.__unwind_info: 0xa8
+  __TEXT.__unwind_info: 0x110
   __DATA_CONST.__const: 0xa8
   __DATA_CONST.__auth_got: 0x1d8
   __DATA_CONST.__got: 0x30
Functions:
~ sub_100000aa4 : 28 -> 16
~ sub_100001ca4 -> sub_100001c98 : 968 -> 956
```
