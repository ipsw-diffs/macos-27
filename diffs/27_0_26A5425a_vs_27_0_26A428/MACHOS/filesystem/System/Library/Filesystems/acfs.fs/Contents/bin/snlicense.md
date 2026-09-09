## snlicense

> `/System/Library/Filesystems/acfs.fs/Contents/bin/snlicense`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0x27afc
+  __TEXT.__text: 0x2788c
   __TEXT.__auth_stubs: 0x970
   __TEXT.__cstring: 0x6c95
   __TEXT.__const: 0xc90
-  __TEXT.__unwind_info: 0x820
+  __TEXT.__unwind_info: 0xa80
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__auth_got: 0x4b8
   __DATA_CONST.__got: 0x40
Functions:
~ _usage : 468 -> 456
~ _SnLicCapStoreFree : 92 -> 80
~ __SnLicCapStoreNext : 108 -> 100
~ __SnLicCapStoreFind : 356 -> 348
~ _SnLicCapStoreToNet : 540 -> 532
~ _SnLicCapInsert : 92 -> 80
~ _SnLicCapChgrp : 116 -> 104
~ _SnLicCapRemove : 92 -> 80
~ _SnLicOwnerFree : 108 -> 96
~ _SnLicReserveFree : 88 -> 76
~ _SnLicSrvConnClose : 100 -> 88
~ _SnLicSrvStdRespFree : 84 -> 72
~ _FsmPMGetDisks : 1388 -> 1384
~ _FsmGetPartitionNativeKeys : 416 -> 412
~ _FsmStartIoTest : 352 -> 344
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
~ _FormatSysError : 68 -> 56
~ _CloseLog : 220 -> 208
~ _GetLogFileInfo : 184 -> 172
~ _FsmSetEmbeddedCluster : 176 -> 172
~ _FsmCopyEmbedded : 148 -> 136
~ _do_dump : 1640 -> 1616
~ _dump_indent : 236 -> 224
~ _hashtable_close : 56 -> 44
~ _jsonp_strdup : 60 -> 48
~ _json_object_set_new : 160 -> 148
~ _json_string_nocheck : 72 -> 60
~ _json_string : 68 -> 56
~ _json_stringn : 92 -> 80
~ _json_string_set_nocheck : 84 -> 72
~ _json_string_set : 84 -> 72
~ _json_string_setn : 116 -> 104
~ _json_delete : 208 -> 196
~ _json_copy : 508 -> 496
~ _json_deep_copy : 464 -> 452
```
