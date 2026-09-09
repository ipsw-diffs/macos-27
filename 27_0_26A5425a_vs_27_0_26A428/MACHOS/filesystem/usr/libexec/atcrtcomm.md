## atcrtcomm

> `/usr/libexec/atcrtcomm`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 33.0.0.0.0
-  __TEXT.__text: 0x1540
+  __TEXT.__text: 0x151c
   __TEXT.__auth_stubs: 0x2d0
   __TEXT.__gcc_except_tab: 0x3c
   __TEXT.__const: 0x48
   __TEXT.__cstring: 0x335
-  __TEXT.__unwind_info: 0x110
+  __TEXT.__unwind_info: 0x128
   __DATA_CONST.__const: 0xd0
   __DATA_CONST.__cfstring: 0x180
   __DATA_CONST.__auth_got: 0x170
Functions:
~ sub_1000007ac : 248 -> 236
~ sub_100000e58 -> sub_100000e4c : 68 -> 56
~ sub_100001098 -> sub_100001080 : 224 -> 212
```
