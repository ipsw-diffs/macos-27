## cvmkfile

> `/System/Library/Filesystems/acfs.fs/Contents/bin/cvmkfile`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0xa4d0
+  __TEXT.__text: 0xa438
   __TEXT.__auth_stubs: 0x620
   __TEXT.__cstring: 0x16c7
   __TEXT.__const: 0x4e0
-  __TEXT.__unwind_info: 0x2c0
+  __TEXT.__unwind_info: 0x3e0
   __DATA_CONST.__auth_got: 0x310
   __DATA_CONST.__got: 0x40
   __DATA_CONST.__auth_ptr: 0x8
Functions:
~ _auth_sign_data : 212 -> 204
~ _PanicCheckedWriteLog : 328 -> 304
~ _initialize_roots : 292 -> 280
~ _get_masklen : 140 -> 128
~ _ResetAddrLists : 96 -> 84
~ _save_metadata_filter : 200 -> 188
~ _BuildAddrLists : 3032 -> 3040
~ __enumerate_mac_addrs : 152 -> 140
~ __enumerate_ip_addrs : 164 -> 152
~ _enumerate_auth_ids : 112 -> 100
~ _unregister_spurious_wakeup : 160 -> 148
~ ___starter : 104 -> 92
~ _ThreadPriority : 208 -> 200
~ _RecvFromTo : 516 -> 504
```
