## dig

> `/usr/bin/dig`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 65.0.0.0.0
-  __TEXT.__text: 0x191b8c
+  __TEXT.__text: 0x18ccf0
   __TEXT.__auth_stubs: 0xc50
   __TEXT.__const: 0x1a88
   __TEXT.__cstring: 0x4800a
-  __TEXT.__unwind_info: 0x4838
+  __TEXT.__unwind_info: 0xd7a0
   __TEXT.__eh_frame: 0x50
   __DATA_CONST.__const: 0x15a8
   __DATA_CONST.__auth_got: 0x628
```
