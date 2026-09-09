## vidio

> `/System/Library/Filesystems/acfs.fs/Contents/bin/vidio`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0x3f7c
+  __TEXT.__text: 0x3f50
   __TEXT.__auth_stubs: 0x3a0
   __TEXT.__const: 0x30
   __TEXT.__cstring: 0x150a
-  __TEXT.__unwind_info: 0x118
+  __TEXT.__unwind_info: 0x160
   __DATA_CONST.__auth_got: 0x1d0
   __DATA_CONST.__got: 0x28
   __DATA.__data: 0x288
Functions:
~ _vio_filelist_init : 432 -> 428
~ _vio_pstats : 1592 -> 1564
~ _vio_async_req : 56 -> 44
```
