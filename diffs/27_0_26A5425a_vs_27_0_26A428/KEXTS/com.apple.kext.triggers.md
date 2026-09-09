## com.apple.kext.triggers

> `com.apple.kext.triggers`

```diff

 328.0.0.0.0
   __TEXT.__cstring: 0x3ab
   __TEXT.__const: 0x48
-  __TEXT_EXEC.__text: 0x284c
+  __TEXT_EXEC.__text: 0x28b4
   __TEXT_EXEC.__auth_stubs: 0x420
   __DATA.__data: 0xf0
   __DATA.__bss: 0x3c
Functions:
~ _trigger_new_autofs : 296 -> 300
~ _trigger_resolve : 944 -> 948
~ _trigger_unresolve : 132 -> 136
~ _trigger_rearm : 152 -> 156
~ _trigger_reclaim : 72 -> 76
~ _trigger_new : 84 -> 88
~ _trigger_do_mount_url : 144 -> 148
~ _trigger_free : 196 -> 200
~ _SMBRemountServer : 468 -> 472
~ _auto_get_automountd_port : 132 -> 136
~ _unmount_triggered_mounts : 692 -> 696
~ _triggers_start : 336 -> 340
~ _triggers_do_unmount : 196 -> 200
~ _triggers_stop : 240 -> 244
~ _trigger_mount_thread : 304 -> 308
~ _trigger_make_unresolved : 200 -> 204
~ _triggers_unmount_thread : 52 -> 56
~ _decrement_unmount_thread_count : 108 -> 112
~ _autofs_mount : 916 -> 920
~ _autofs_unmount : 608 -> 612
~ _autofs_readdir : 528 -> 532
~ _autofs_readsubdir : 780 -> 784
~ _autofs_lookup : 776 -> 780
~ _autofs_mount_subtrigger : 864 -> 868
~ _autofs_mount_url : 588 -> 592
~ _autofs_smb_remount_server : 112 -> 116
```
