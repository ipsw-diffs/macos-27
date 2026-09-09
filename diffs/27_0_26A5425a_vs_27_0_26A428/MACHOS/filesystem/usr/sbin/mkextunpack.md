## mkextunpack

> `/usr/sbin/mkextunpack`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 784.0.0.0.0
-  __TEXT.__text: 0x2054
+  __TEXT.__text: 0x2048
   __TEXT.__auth_stubs: 0x490
   __TEXT.__cstring: 0x838
-  __TEXT.__unwind_info: 0xb0
+  __TEXT.__unwind_info: 0xb8
   __DATA_CONST.__cfstring: 0x140
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x248
Functions:
~ sub_100000878 : 156 -> 144
```
