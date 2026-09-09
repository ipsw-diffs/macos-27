## cvcp

> `/System/Library/Filesystems/acfs.fs/Contents/bin/cvcp`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0xd714
+  __TEXT.__text: 0xd634
   __TEXT.__auth_stubs: 0x6d0
   __TEXT.__const: 0x48
   __TEXT.__cstring: 0x32e6
-  __TEXT.__unwind_info: 0x2a8
+  __TEXT.__unwind_info: 0x430
   __DATA_CONST.__auth_got: 0x368
   __DATA_CONST.__got: 0x30
   __DATA_CONST.__auth_ptr: 0x8
Functions:
~ _usage : 632 -> 620
~ _main : 4400 -> 4392
~ _MsgQ_Put : 200 -> 188
~ _IOLoop : 1560 -> 1556
~ _TarQ_Read : 240 -> 236
~ _CopyRegularFiles : 364 -> 352
~ _BulkCreate : 796 -> 784
~ _TarQ_Write : 220 -> 212
~ _TarQ_Put : 184 -> 172
~ _TarOctal : 188 -> 184
~ ___starter : 104 -> 92
~ _OUTLINED_FUNCTION_0 : 48 -> 36
~ _OUTLINED_FUNCTION_3 : 48 -> 36
~ _OUTLINED_FUNCTION_5 : 24 -> 12
~ ___starter : 104 -> 92
~ _auth_sign_data : 212 -> 204
~ _PanicCheckedWriteLog : 328 -> 304
~ _initialize_roots : 292 -> 280
~ _unregister_spurious_wakeup : 160 -> 148
~ ___starter : 104 -> 92
~ _ThreadPriority : 208 -> 200
```
