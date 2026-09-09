## talk

> `/usr/bin/talk`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 308.0.0.0.0
-  __TEXT.__text: 0x1df8
+  __TEXT.__text: 0x1db0
   __TEXT.__auth_stubs: 0x500
   __TEXT.__const: 0x9b
   __TEXT.__cstring: 0x5cf
-  __TEXT.__unwind_info: 0xd8
+  __TEXT.__unwind_info: 0x100
   __DATA_CONST.__const: 0x48
   __DATA_CONST.__auth_got: 0x280
   __DATA_CONST.__got: 0x48
Functions:
~ sub_100000780 : 76 -> 64
~ sub_1000007cc -> sub_1000007c0 : 784 -> 760
~ sub_100000efc -> sub_100000ed8 : 148 -> 136
~ sub_100000f90 -> sub_100000f60 : 200 -> 188
~ sub_100002148 -> sub_10000210c : 260 -> 248
```
