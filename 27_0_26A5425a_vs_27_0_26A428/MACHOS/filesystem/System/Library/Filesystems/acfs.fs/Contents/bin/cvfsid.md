## cvfsid

> `/System/Library/Filesystems/acfs.fs/Contents/bin/cvfsid`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0x11f58
+  __TEXT.__text: 0x11e4c
   __TEXT.__auth_stubs: 0x800
   __TEXT.__cstring: 0x35ff
   __TEXT.__const: 0xac2
-  __TEXT.__unwind_info: 0x3c0
+  __TEXT.__unwind_info: 0x4f8
   __DATA_CONST.__const: 0x40
   __DATA_CONST.__auth_got: 0x400
   __DATA_CONST.__got: 0x30
Functions:
~ _auth_sign_data : 212 -> 204
~ _SnLicMtime : 140 -> 128
~ __SnLicValidate : 2188 -> 2180
~ _SnLicStrToLicEnt : 144 -> 132
~ _SnLicCheckDiskCapMsg : 84 -> 72
~ _SnBadDiskCatalogMsg : 84 -> 72
~ _InitializeValidator : 108 -> 96
~ _PanicCheckedWriteLog : 328 -> 304
~ _initialize_roots : 292 -> 280
~ _get_masklen : 140 -> 128
~ _ResetAddrLists : 96 -> 84
~ _save_metadata_filter : 200 -> 188
~ _BuildAddrLists : 3032 -> 3040
~ __enumerate_mac_addrs : 152 -> 140
~ __enumerate_ip_addrs : 164 -> 152
~ _enumerate_auth_ids : 112 -> 100
~ __SnfsCfgEntFree : 104 -> 92
~ _SnfsDirEnumEnd : 96 -> 84
~ _unregister_spurious_wakeup : 160 -> 148
~ ___starter : 104 -> 92
~ _ThreadPriority : 208 -> 200
~ _RecvFromTo : 516 -> 504
~ _CloseLog : 220 -> 208
~ _GetLogFileInfo : 184 -> 172
```
