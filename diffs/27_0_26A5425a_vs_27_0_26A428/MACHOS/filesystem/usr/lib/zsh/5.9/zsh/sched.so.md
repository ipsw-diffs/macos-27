## sched.so

> `/usr/lib/zsh/5.9/zsh/sched.so`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 118.0.0.0.0
-  __TEXT.__text: 0x90c
+  __TEXT.__text: 0x8f4
   __TEXT.__auth_stubs: 0x1a0
   __TEXT.__cstring: 0xd6
   __TEXT.__unwind_info: 0x90
Functions:
~ _cleanup_ : 180 -> 168
~ sub_d78 -> sub_d6c : 116 -> 104
```
