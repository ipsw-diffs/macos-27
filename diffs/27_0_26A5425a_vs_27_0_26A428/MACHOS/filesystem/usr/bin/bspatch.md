## bspatch

> `/usr/bin/bspatch`

```diff

 12.0.0.0.0
-  __TEXT.__text: 0xa78
+  __TEXT.__text: 0xa30
   __TEXT.__auth_stubs: 0x1b0
   __TEXT.__cstring: 0xbe
-  __TEXT.__unwind_info: 0x68
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__auth_got: 0xd8
   __DATA_CONST.__got: 0x10
   __DATA.__data: 0x4
Functions:
~ sub_100000dd8 : 88 -> 76
~ sub_100000e30 -> sub_100000e24 : 28 -> 16
~ sub_100000e4c -> sub_100000e34 : 36 -> 24
~ sub_100000e70 -> sub_100000e4c : 36 -> 24
~ sub_100000e94 -> sub_100000e64 : 36 -> 24
~ sub_100000eb8 -> sub_100000e7c : 36 -> 24
```
