## newfs_msdos

> `/System/Library/Filesystems/msdos.fs/Contents/Resources/newfs_msdos`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 845.0.3.0.1
-  __TEXT.__text: 0x3038
+  __TEXT.__text: 0x3018
   __TEXT.__auth_stubs: 0x330
   __TEXT.__const: 0x10
   __TEXT.__cstring: 0x10ce
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xc0
   __DATA_CONST.__cfstring: 0xa0
   __DATA_CONST.__auth_got: 0x198
   __DATA_CONST.__got: 0x30
Functions:
~ sub_100000728 : 5668 -> 5648
~ sub_1000032f8 -> sub_1000032e4 : 268 -> 256
```
