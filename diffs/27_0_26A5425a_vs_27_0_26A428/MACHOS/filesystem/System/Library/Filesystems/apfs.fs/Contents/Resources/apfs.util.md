## apfs.util

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs.util`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 3288.1.3.0.0
-  __TEXT.__text: 0x2f4c
+  __TEXT.__text: 0x2ef0
   __TEXT.__auth_stubs: 0x330
   __TEXT.__cstring: 0x1bd9
   __TEXT.__const: 0x40
-  __TEXT.__unwind_info: 0xc8
+  __TEXT.__unwind_info: 0x128
   __DATA_CONST.__const: 0x68
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__auth_got: 0x198
Functions:
~ sub_1000007e0 : 3532 -> 3460
~ sub_1000016e8 -> sub_1000016a0 : 56 -> 48
~ sub_100001ab8 -> sub_100001a68 : 124 -> 112
```
