## mount_apfs

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/mount_apfs`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 3288.1.3.0.0
-  __TEXT.__text: 0x21b8
+  __TEXT.__text: 0x21a0
   __TEXT.__auth_stubs: 0x520
   __TEXT.__cstring: 0x86d
   __TEXT.__const: 0x197
-  __TEXT.__unwind_info: 0xa8
+  __TEXT.__unwind_info: 0xf8
   __DATA_CONST.__const: 0x288
   __DATA_CONST.__cfstring: 0x100
   __DATA_CONST.__auth_got: 0x290
Functions:
~ sub_100001ae8 : 924 -> 912
~ sub_100002204 -> sub_1000021f8 : 36 -> 24
```
