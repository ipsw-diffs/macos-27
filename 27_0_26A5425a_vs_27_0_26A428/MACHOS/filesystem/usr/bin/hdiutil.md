## hdiutil

> `/usr/bin/hdiutil`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 704.0.0.0.0
-  __TEXT.__text: 0x2abe4
+  __TEXT.__text: 0x2a458
   __TEXT.__auth_stubs: 0x1d10
   __TEXT.__cstring: 0xfe16
   __TEXT.__const: 0x160
-  __TEXT.__unwind_info: 0x560
+  __TEXT.__unwind_info: 0x6f8
   __DATA_CONST.__const: 0x208
   __DATA_CONST.__cfstring: 0x39a0
   __DATA_CONST.__objc_imageinfo: 0x8
```
