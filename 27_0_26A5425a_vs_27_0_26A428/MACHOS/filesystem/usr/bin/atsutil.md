## atsutil

> `/usr/bin/atsutil`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 601.0.0.0.0
-  __TEXT.__text: 0x1644
+  __TEXT.__text: 0x1620
   __TEXT.__auth_stubs: 0x340
   __TEXT.__objc_stubs: 0x220
   __TEXT.__const: 0x30
   __TEXT.__gcc_except_tab: 0xc8
   __TEXT.__cstring: 0x80d
   __TEXT.__objc_methname: 0x177
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xd0
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__cfstring: 0x1c0
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100001d08 : 204 -> 192
~ sub_100001dd4 -> sub_100001dc8 : 72 -> 60
~ sub_100001e1c -> sub_100001e04 : 64 -> 52
```
