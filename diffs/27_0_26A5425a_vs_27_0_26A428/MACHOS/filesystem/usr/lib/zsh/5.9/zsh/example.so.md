## example.so

> `/usr/lib/zsh/5.9/zsh/example.so`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 118.0.0.0.0
-  __TEXT.__text: 0x530
+  __TEXT.__text: 0x518
   __TEXT.__auth_stubs: 0x160
   __TEXT.__cstring: 0x100
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__auth_got: 0xb0
   __DATA_CONST.__got: 0x10
   __DATA.__data: 0x238
Functions:
~ _boot_ : 156 -> 144
~ _cleanup_ : 76 -> 64
```
