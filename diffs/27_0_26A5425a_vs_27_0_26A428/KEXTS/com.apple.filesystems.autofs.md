## com.apple.filesystems.autofs

> `com.apple.filesystems.autofs`

```diff

 328.0.0.0.0
   __TEXT.__const: 0xf8
   __TEXT.__cstring: 0xfff
-  __TEXT_EXEC.__text: 0x6d44
+  __TEXT_EXEC.__text: 0x6e98
   __TEXT_EXEC.__auth_stubs: 0x6d0
   __DATA.__data: 0x5d0
   __DATA.__common: 0x78
Functions:
~ _autofs_mount_set_busy : 248 -> 252
~ _autofs_mount_clear_busy : 156 -> 160
~ _auto_fninfo_unlock_shared : 88 -> 92
~ _auto_is_autofs : 88 -> 92
~ _auto_lookup_request : 280 -> 284
~ _auto_lookup_aux : 284 -> 288
~ _get_key_and_subdirectory : 304 -> 308
~ _auto_readdir_aux : 456 -> 460
~ _auto_makefnnode : 864 -> 868
~ _auto_check_homedirmount : 32 -> 36
~ _autofs_trigger_get_mount_args : 92 -> 96
~ _auto_do_mount : 408 -> 412
~ _auto_rearm : 168 -> 172
~ _auto_freefnnode : 196 -> 200
~ _auto_disconnect : 380 -> 384
~ _auto_enter : 456 -> 460
~ _auto_search : 160 -> 164
~ _auto_mount_request : 1032 -> 1036
~ _getstring : 236 -> 240
~ _auto_make_subtriggers : 188 -> 192
~ _auto_trigger_callback : 652 -> 656
~ _free_mounta_strings : 280 -> 284
~ _autofs_subtrigger_get_mount_args : 52 -> 56
~ _auto_do_subtrigger_mount : 312 -> 316
~ _auto_do_submount : 136 -> 140
~ _auto_root : 60 -> 64
~ _autofs_dev_open : 100 -> 104
~ _autofs_dev_close : 60 -> 64
~ _autofs_ioctl : 540 -> 544
~ _auto_is_automounter : 108 -> 112
~ _autofs_nowait_dev_open : 196 -> 200
~ _autofs_nowait_dev_close : 124 -> 128
~ _autofs_nowait_dev_clone : 96 -> 100
~ _auto_is_nowait_process : 92 -> 96
~ _autofs_notrigger_dev_open : 196 -> 200
~ _autofs_notrigger_dev_close : 124 -> 128
~ _autofs_notrigger_dev_clone : 96 -> 100
~ _auto_is_notrigger_process : 108 -> 112
~ _autofs_homedirmounter_dev_open : 192 -> 196
~ _autofs_homedirmounter_dev_close : 116 -> 120
~ _autofs_homedirmounter_dev_clone : 96 -> 100
~ _auto_is_homedirmounter_process : 128 -> 132
~ _auto_mark_vnode_homedirmount : 192 -> 196
~ _auto_control_dev_open : 84 -> 88
~ _auto_control_dev_close : 60 -> 64
~ _auto_control_ioctl : 544 -> 548
~ _auto_mount : 1476 -> 1480
~ _auto_unmount : 596 -> 600
~ _autofs_zone_init : 524 -> 528
~ _autofs_restrict_opts : 488 -> 492
~ _homedirmounter_process_free : 144 -> 148
~ _auto_update_options : 696 -> 700
~ _autofs_start : 1440 -> 1444
~ _unlock_autofs_locks : 144 -> 148
~ _autofs_stop : 876 -> 880
~ _auto_lookup : 1068 -> 1072
~ _auto_getattr : 36 -> 40
~ _auto_setattr : 124 -> 128
~ _auto_readdir : 1556 -> 1560
~ _auto_readlink : 156 -> 160
~ _auto_getxattr : 44 -> 48
~ _auto_reclaim : 228 -> 232
~ _auto_nobrowse : 88 -> 92
~ _auto_get_attributes : 416 -> 420
~ _autofs_mount : 916 -> 920
~ _autofs_unmount : 608 -> 612
~ _autofs_readdir : 528 -> 532
~ _autofs_readsubdir : 780 -> 784
~ _autofs_lookup : 776 -> 780
~ _autofs_mount_subtrigger : 864 -> 868
~ _autofs_mount_url : 588 -> 592
~ _autofs_smb_remount_server : 112 -> 116
~ autofs_mount_clear_busy.cold.1 : 52 -> 56
~ autofs_mount_clear_busy.cold.2 : 52 -> 56
~ autofs_start.cold.1 : 24 -> 28
~ autofs_start.cold.2 : 44 -> 48
~ autofs_start.cold.3 : 44 -> 48
~ autofs_start.cold.4 : 44 -> 48
~ autofs_start.cold.5 : 44 -> 48
~ autofs_stop.cold.1 : 44 -> 48
~ autofs_stop.cold.2 : 24 -> 28
~ autofs_stop.cold.3 : 44 -> 48
~ autofs_stop.cold.4 : 44 -> 48
~ autofs_stop.cold.5 : 44 -> 48
~ autofs_stop.cold.6 : 44 -> 48
```
