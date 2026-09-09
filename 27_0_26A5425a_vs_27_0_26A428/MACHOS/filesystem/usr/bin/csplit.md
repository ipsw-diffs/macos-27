## csplit

> `/usr/bin/csplit`

```diff

 199.0.0.0.0
-  __TEXT.__text: 0xe0c
+  __TEXT.__text: 0xdd4
   __TEXT.__auth_stubs: 0x260
   __TEXT.__const: 0x4a
   __TEXT.__cstring: 0x1a8
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0xc0
   __DATA_CONST.__auth_got: 0x130
   __DATA_CONST.__got: 0x28
   __DATA.__bss: 0xc60
Functions:
~ sub_100000da0 : 68 -> 56
~ sub_100001134 -> sub_100001128 : 40 -> 28
~ sub_10000115c -> sub_100001144 : 32 -> 20
~ sub_10000117c -> sub_100001158 : 28 -> 16
~ sub_100001218 -> sub_1000011e8 : 60 -> 52
```
