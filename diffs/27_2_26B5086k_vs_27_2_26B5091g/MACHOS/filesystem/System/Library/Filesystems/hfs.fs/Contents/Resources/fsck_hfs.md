## fsck_hfs

> `/System/Library/Filesystems/hfs.fs/Contents/Resources/fsck_hfs`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-753.40.2.0.0
-  __TEXT.__text: 0x34640
+753.40.3.0.0
+  __TEXT.__text: 0x346dc
   __TEXT.__auth_stubs: 0x7c0
   __TEXT.__const: 0x10b4
   __TEXT.__cstring: 0x6e74
Functions:
~ sub_1000193d4 : 1136 -> 1292
```
