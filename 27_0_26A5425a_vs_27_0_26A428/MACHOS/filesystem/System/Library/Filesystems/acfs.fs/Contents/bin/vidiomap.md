## vidiomap

> `/System/Library/Filesystems/acfs.fs/Contents/bin/vidiomap`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0x4068
+  __TEXT.__text: 0x4030
   __TEXT.__auth_stubs: 0x380
   __TEXT.__cstring: 0xa86
   __TEXT.__const: 0x28
-  __TEXT.__unwind_info: 0x1b0
+  __TEXT.__unwind_info: 0x270
   __DATA_CONST.__auth_got: 0x1c0
   __DATA_CONST.__got: 0x28
   __DATA.__data: 0xa4
Functions:
~ _vma_fl_from_dir : 196 -> 184
~ _vma_print_exts : 932 -> 920
~ _vma_create_file_entry : 256 -> 252
~ _vma_insert_exts : 120 -> 124
~ _vma_clone : 612 -> 604
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ vma_resequence.cold.1 : 84 -> 72
```
