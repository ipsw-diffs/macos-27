## snfsdefrag

> `/System/Library/Filesystems/acfs.fs/Contents/bin/snfsdefrag`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0x924c
+  __TEXT.__text: 0x91b4
   __TEXT.__auth_stubs: 0x5d0
   __TEXT.__const: 0x50
   __TEXT.__cstring: 0x23a0
-  __TEXT.__unwind_info: 0x268
+  __TEXT.__unwind_info: 0x388
   __DATA_CONST.__auth_got: 0x2e8
   __DATA_CONST.__got: 0x30
   __DATA.__data: 0x1f30
Functions:
~ _check4ExtentOverlap : 568 -> 556
~ _doFileInt : 4212 -> 4208
~ _PanicCheckedWriteLog : 328 -> 304
~ _initialize_roots : 292 -> 280
~ _unregister_spurious_wakeup : 160 -> 148
~ ___starter : 104 -> 92
~ _UtilTrackSuccess : 76 -> 64
~ _UtilTrackReport : 368 -> 356
~ _UtilTrackClose : 64 -> 52
~ _UtilTrackFailure : 64 -> 52
~ _UtilTrackHeartBeatPulse : 112 -> 100
~ _ThreadPriority : 208 -> 200
~ _auth_sign_data : 212 -> 204
```
