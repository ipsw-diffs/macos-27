## mdt

> `/System/Library/Filesystems/acfs.fs/Contents/bin/mdt`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0x4bb0
+  __TEXT.__text: 0x4b80
   __TEXT.__auth_stubs: 0x400
   __TEXT.__const: 0x28
   __TEXT.__cstring: 0xd64
-  __TEXT.__unwind_info: 0x1b8
+  __TEXT.__unwind_info: 0x298
   __DATA_CONST.__auth_got: 0x200
   __DATA_CONST.__got: 0x28
   __DATA.__data: 0xbc
Functions:
~ _mdt_remount : 140 -> 128
~ _mdt_einit : 368 -> 356
~ _mdt_print : 332 -> 320
~ _OUTLINED_FUNCTION_0 : 28 -> 16
```
