## curses.so

> `/usr/lib/zsh/5.9/zsh/curses.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 118.0.0.0.0
-  __TEXT.__text: 0x23d0
+  __TEXT.__text: 0x23ac
   __TEXT.__auth_stubs: 0x5a0
   __TEXT.__cstring: 0x74d
   __TEXT.__const: 0x150
-  __TEXT.__unwind_info: 0xe8
+  __TEXT.__unwind_info: 0xf8
   __DATA_CONST.__const: 0x9f0
   __DATA_CONST.__auth_got: 0x2d0
   __DATA_CONST.__got: 0x80
Functions:
~ _cleanup_ : 108 -> 96
~ sub_7b8 -> sub_7ac : 384 -> 372
~ sub_25cc -> sub_25b4 : 64 -> 52
```
