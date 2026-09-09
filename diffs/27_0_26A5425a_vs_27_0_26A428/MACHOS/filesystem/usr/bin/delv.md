## delv

> `/usr/bin/delv`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 65.0.0.0.0
-  __TEXT.__text: 0x1927c8
+  __TEXT.__text: 0x18d9a8
   __TEXT.__auth_stubs: 0xbf0
   __TEXT.__const: 0x1ac8
   __TEXT.__cstring: 0x47407
-  __TEXT.__unwind_info: 0x4918
+  __TEXT.__unwind_info: 0xdaf0
   __TEXT.__eh_frame: 0x50
   __DATA_CONST.__const: 0x1520
   __DATA_CONST.__auth_got: 0x5f8
```
