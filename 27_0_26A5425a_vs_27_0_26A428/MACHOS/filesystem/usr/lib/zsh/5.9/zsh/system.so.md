## system.so

> `/usr/lib/zsh/5.9/zsh/system.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 118.0.0.0.0
-  __TEXT.__text: 0x1524
+  __TEXT.__text: 0x1520
   __TEXT.__auth_stubs: 0x310
   __TEXT.__const: 0x20
   __TEXT.__cstring: 0x762
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xa8
   __DATA_CONST.__const: 0xa8
   __DATA_CONST.__auth_got: 0x188
   __DATA_CONST.__got: 0x58
Functions:
~ sub_1284 : 1552 -> 1548
```
