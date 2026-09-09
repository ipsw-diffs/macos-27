## ls

> `/bin/ls`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 487.0.1.0.0
-  __TEXT.__text: 0x3c1c
+  __TEXT.__text: 0x3b8c
   __TEXT.__auth_stubs: 0x540
   __TEXT.__const: 0x10d
   __TEXT.__cstring: 0x503
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0x110
   __DATA_CONST.__const: 0x268
   __DATA_CONST.__auth_got: 0x2a0
   __DATA_CONST.__got: 0x30
Functions:
~ sub_100000960 : 3076 -> 3088
~ sub_1000016d4 -> sub_1000016e0 : 804 -> 792
~ sub_100001a78 : 2232 -> 2184
~ sub_100003180 -> sub_100003150 : 172 -> 148
~ sub_1000032b4 -> sub_10000326c : 236 -> 224
~ sub_1000033a0 -> sub_10000334c : 820 -> 808
~ sub_100003840 -> sub_1000037e0 : 72 -> 60
~ sub_100003888 -> sub_10000381c : 44 -> 32
~ sub_100003904 -> sub_10000388c : 412 -> 388
```
