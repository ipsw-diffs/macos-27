## com.apple.filesystems.webdav

> `com.apple.filesystems.webdav`

```diff

 413.0.0.0.0
   __TEXT.__cstring: 0x904
   __TEXT.__const: 0xd0
-  __TEXT_EXEC.__text: 0x5c90
+  __TEXT_EXEC.__text: 0x5d70
   __TEXT_EXEC.__auth_stubs: 0x770
   __DATA.__data: 0x340
   __DATA.__common: 0x38
Functions:
~ _webdav_hashinit : 96 -> 100
~ _webdav_hashdestroy : 96 -> 100
~ _webdav_hashget : 440 -> 444
~ _webdav_hashins : 184 -> 188
~ _webdav_hashrem : 168 -> 172
~ _webdav_assign_ref : 368 -> 372
~ _webdav_check_agent_entitlement : 40 -> 44
~ _webdav_mount : 1148 -> 1152
~ _webdav_unmount : 324 -> 328
~ _webdav_root : 60 -> 64
~ _webdav_vfs_getattr : 772 -> 776
~ _webdav_init : 140 -> 144
~ _webdav_sysctl : 608 -> 612
~ _webdav_fs_module_start : 204 -> 208
~ _webdav_vfs_statfs : 196 -> 200
~ _webdav_translate_ref : 132 -> 136
~ _webdav_copy_creds : 44 -> 48
~ _webdav_up : 192 -> 196
~ _webdav_sendmsg : 1600 -> 1604
~ _webdav_dead : 172 -> 176
~ _webdav_get : 648 -> 652
~ _webdav_vnop_lookup : 1300 -> 1304
~ _webdav_vnop_create : 504 -> 508
~ _webdav_vnop_open : 92 -> 96
~ _webdav_vnop_close : 88 -> 92
~ _webdav_vnop_getattr : 108 -> 112
~ _webdav_vnop_setattr : 748 -> 752
~ _webdav_vnop_read : 92 -> 96
~ _webdav_vnop_write : 852 -> 856
~ _webdav_vnop_ioctl : 440 -> 444
~ _webdav_vnop_mmap : 88 -> 92
~ _webdav_vnop_mnomap : 108 -> 112
~ _webdav_vnop_fsync : 120 -> 124
~ _webdav_vnop_remove : 456 -> 460
~ _webdav_vnop_rename : 1016 -> 1020
~ _webdav_vnop_mkdir : 500 -> 504
~ _webdav_vnop_rmdir : 420 -> 424
~ _webdav_vnop_readdir : 740 -> 744
~ _webdav_vnop_reclaim : 120 -> 124
~ _webdav_vnop_pathconf : 200 -> 204
~ _webdav_vnop_pagein : 944 -> 948
~ _webdav_vnop_pageout : 1004 -> 1008
~ _webdav_getattr_common : 1388 -> 1392
~ _webdav_purge_stale_vnode : 68 -> 72
~ _webdav_vnop_open_locked : 580 -> 584
~ _webdav_vnop_close_locked : 128 -> 132
~ _webdav_close_mnomap : 344 -> 348
~ _webdav_fsync : 644 -> 648
~ _webdav_rdwr : 1904 -> 1916
~ _webdav_read_bytes : 360 -> 364
~ _webdav_task_has_entitlement : 112 -> 116
~ _webdav_lock : 64 -> 68
~ _webdav_unlock : 40 -> 44
~ webdav_sendmsg.cold.1 : 44 -> 48
```
