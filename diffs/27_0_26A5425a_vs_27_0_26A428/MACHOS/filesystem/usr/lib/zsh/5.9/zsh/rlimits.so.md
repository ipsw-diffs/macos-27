## rlimits.so

> `/usr/lib/zsh/5.9/zsh/rlimits.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 118.0.0.0.0
-  __TEXT.__text: 0x1204
+  __TEXT.__text: 0x11d4
   __TEXT.__auth_stubs: 0x140
   __TEXT.__const: 0x8
   __TEXT.__cstring: 0x347
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__const: 0x168
   __DATA_CONST.__auth_got: 0xa0
   __DATA_CONST.__got: 0x18
Functions:
~ _cleanup_ : 148 -> 136
~ sub_84c -> sub_840 : 1036 -> 1024
~ sub_130c -> sub_12f4 : 104 -> 92
~ sub_1560 -> sub_153c : 400 -> 388
```
