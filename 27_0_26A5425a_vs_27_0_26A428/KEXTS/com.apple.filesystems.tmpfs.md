## com.apple.filesystems.tmpfs

> `com.apple.filesystems.tmpfs`

```diff

   __TEXT.__cstring: 0x4b7
   __TEXT.__const: 0x40
   __TEXT.__os_log: 0x20a
-  __TEXT_EXEC.__text: 0x9674
+  __TEXT_EXEC.__text: 0x9808
   __TEXT_EXEC.__auth_stubs: 0x640
   __DATA.__data: 0x180
   __DATA.__bss: 0x8
Functions:
~ _tmpfs_start : 216 -> 220
~ _tmpfs_stop : 60 -> 64
~ _tmpfs_getattr : 1100 -> 1104
~ _tmpfs_setattr : 640 -> 644
~ _tmpfs_reclaim : 204 -> 208
~ _tmpfs_fifo_read : 120 -> 124
~ _tmpfs_fifo_write : 120 -> 124
~ _tmpfs_lookup : 1180 -> 1184
~ _tmpfs_create : 152 -> 156
~ _tmpfs_mknod : 176 -> 180
~ _tmpfs_open : 96 -> 100
~ _tmpfs_close : 76 -> 80
~ _tmpfs_read : 916 -> 920
~ _tmpfs_write : 1412 -> 1416
~ _tmpfs_fsync : 96 -> 100
~ _tmpfs_remove : 392 -> 396
~ _tmpfs_link : 436 -> 440
~ _tmpfs_rename : 84 -> 88
~ _tmpfs_renamex : 1808 -> 1812
~ _tmpfs_mkdir : 152 -> 156
~ _tmpfs_rmdir : 456 -> 460
~ _tmpfs_symlink : 164 -> 168
~ _tmpfs_readdir : 212 -> 216
~ _tmpfs_readlink : 148 -> 152
~ _tmpfs_inactive : 84 -> 88
~ _tmpfs_pathconf : 224 -> 228
~ _tmpfs_mmap : 144 -> 148
~ _tmpfs_pagein : 280 -> 284
~ _tmpfs_pageout : 836 -> 844
~ _tmpfs_getxattr : 420 -> 424
~ _tmpfs_listxattr : 92 -> 96
~ _tmpfs_setxattr : 776 -> 780
~ _tmpfs_removexattr : 148 -> 152
~ _tmpfs_dir_RB_REMOVE : 376 -> 380
~ _tmpfs_dir_RB_INSERT : 132 -> 136
~ _tmpfs_xattrs_RB_REMOVE : 372 -> 376
~ _tmpfs_xattrs_RB_INSERT : 220 -> 224
~ _tmpfs_xattrs_RB_FIND : 124 -> 128
~ _tmpfs_xattrs_RB_NFIND : 156 -> 160
~ _tmpfs_extents_head_RB_REMOVE : 376 -> 380
~ _tmpfs_extents_head_RB_INSERT : 144 -> 148
~ _tmpfs_io_lock_shared : 80 -> 84
~ _tmpfs_io_unlock_shared : 80 -> 84
~ _tmpfs_io_lock_exclusive : 68 -> 72
~ _tmpfs_io_lock_shared_to_exclusive : 80 -> 84
~ _tmpfs_initialize_region : 552 -> 556
~ _tmpfs_pagein_range : 968 -> 976
~ _tmpfs_alloc_node : 632 -> 636
~ _tmpfs_free_node : 424 -> 428
~ _tmpfs_free_links : 224 -> 228
~ _tmpfs_dirent_init : 212 -> 216
~ _tmpfs_alloc_dirent : 260 -> 264
~ _tmpfs_free_dirent : 128 -> 132
~ _tmpfs_alloc_vp : 704 -> 708
~ _tmpfs_get_parent : 104 -> 108
~ _tmpfs_free_vp : 28 -> 32
~ _tmpfs_alloc_file : 560 -> 564
~ _tmpfs_dir_lookup : 476 -> 480
~ _tmpfs_dir_attach : 384 -> 388
~ _tmpfs_dir_next : 88 -> 92
~ _tmpfs_dirent_matches : 128 -> 132
~ _tmpfs_dir_detach : 532 -> 536
~ _tmpfs_remove_link_origin : 176 -> 180
~ _tmpfs_dir_destroy : 220 -> 224
~ _tmpfs_dir_getdents : 1072 -> 1076
~ _insert_direntry : 416 -> 420
~ _tmpfs_chflags : 84 -> 88
~ _tmpfs_chmod : 88 -> 92
~ _tmpfs_chown : 108 -> 112
~ _tmpfs_chsize : 500 -> 504
~ _tmpfs_trim_paged_out : 336 -> 340
~ _tmpfs_chtimes : 260 -> 264
~ _tmpfs_itimes : 168 -> 172
~ _tmpfs_check_name : 128 -> 132
~ _tmpfs_node_lookup_xattr : 88 -> 92
~ _tmpfs_node_add_xattr : 184 -> 188
~ _tmpfs_node_remove_xattr : 100 -> 104
~ _tmpfs_node_list_xattr : 200 -> 204
~ _tmpfs_xattr_name_to_kind : 124 -> 128
~ _tmpfs_get_extent_overlapping_range : 188 -> 192
~ _tmpfs_extents_overlap_exists : 36 -> 40
~ _tmpfs_extent_free : 152 -> 156
~ _tmpfs_extents_insert : 204 -> 208
~ _tmpfs_extent_remove_and_free : 152 -> 156
~ _tmpfs_current_link_origin : 72 -> 76
~ _tmpfs_update_link_origin : 404 -> 408
~ _tmpfs_dirent_hash_func : 68 -> 72
~ _tmpfs_mount : 1096 -> 1100
~ _tmpfs_unmount : 216 -> 220
~ _tmpfs_root : 88 -> 92
~ _tmpfs_vfs_getattr : 368 -> 372
~ _tmpfs_vget : 60 -> 64
~ _tmpfs_fhtovp : 288 -> 292
~ _tmpfs_vptofh : 100 -> 104
~ tmpfs_renamex.cold.1 : 44 -> 48
~ tmpfs_renamex.cold.2 : 44 -> 48
~ tmpfs_io_lock_exclusive.cold.1 : 56 -> 60
~ tmpfs_io_lock_shared_to_exclusive.cold.1 : 56 -> 60
~ tmpfs_dir_getdents.cold.1 : 56 -> 60
```
