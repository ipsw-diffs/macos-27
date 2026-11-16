## com.apple.filesystems.smbfs

> `com.apple.filesystems.smbfs`

```diff

-579.60.5.0.0
+579.60.8.0.0
   __TEXT.__const: 0xc35
-  __TEXT.__cstring: 0x51ac
-  __TEXT.__os_log: 0x1807a
-  __TEXT_EXEC.__text: 0x84838
+  __TEXT.__cstring: 0x51c7
+  __TEXT.__os_log: 0x1801a
+  __TEXT_EXEC.__text: 0x846d4
   __TEXT_EXEC.__auth_stubs: 0x1590
   __DATA.__data: 0x12d8
   __DATA.__bss: 0x107c

   __DATA_CONST.__auth_got: 0xac8
   __DATA_CONST.__got: 0x50
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 799
-  Symbols:   2328
-  CStrings:  2659
+  Functions: 798
+  Symbols:   2327
+  CStrings:  2662
 
Symbols:
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6344
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6382
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6393
+ _smb1fs_smb_findclose.kalloc_type_view_5689
+ _smb2_smb_read_uio.kalloc_type_view_9184
+ _smb2_smb_read_uio.kalloc_type_view_9201
+ _smb2_smb_read_write_async.kalloc_type_view_9353
+ _smb2_smb_read_write_async.kalloc_type_view_9419
+ _smb2_smb_read_write_async.kalloc_type_view_9747
+ _smb2_smb_read_write_async.kalloc_type_view_9816
+ _smb2_smb_write_uio.kalloc_type_view_10976
+ _smb2_smb_write_uio.kalloc_type_view_11029
+ _smb2fs_reconnect.kalloc_type_view_3862
+ _smb2fs_reconnect.kalloc_type_view_4438
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3621
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3777
+ _smbfs_CloseChildren.kalloc_type_view_3406
+ _smbfs_build_path.kalloc_type_view_113
+ _smbfs_build_path.kalloc_type_view_115
+ _smbfs_build_path.kalloc_type_view_183
+ _smbfs_build_path.kalloc_type_view_186
+ _smbfs_clear_lockEntries.kalloc_type_view_6755
+ _smbfs_clear_lockEntries.kalloc_type_view_6785
+ _smbfs_free_locks_on_close.kalloc_type_view_6943
+ _smbfs_get_lockEntry.kalloc_type_view_7150
+ _smbfs_get_lockEntry.kalloc_type_view_7239
+ _smbfs_lease_hash_add.kalloc_type_view_6196
+ _smbfs_lease_hash_remove.kalloc_type_view_6296
+ _smbfs_nget.kalloc_type_view_1046
+ _smbfs_nget.kalloc_type_view_1066
+ _smbfs_nget.kalloc_type_view_1073
+ _smbfs_nget.kalloc_type_view_1379
+ _smbfs_nget.kalloc_type_view_962
+ _smbfs_nget.kalloc_type_view_991
+ _smbfs_smb_findopen.kalloc_type_view_5952
+ _smbfs_smb_reopen_file.kalloc_type_view_5039
+ _smbfs_smb_reopen_file.kalloc_type_view_5115
+ _smbfs_trigger_rel_mount_args.kalloc_type_view_307
+ _smbfs_vgetstrm.kalloc_type_view_1466
+ _smbfs_vgetstrm.kalloc_type_view_1473
+ _smbfs_vgetstrm.kalloc_type_view_1684
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6328
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6366
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6377
- _smb1fs_smb_findclose.kalloc_type_view_5715
- _smb2_smb_read_uio.kalloc_type_view_9179
- _smb2_smb_read_uio.kalloc_type_view_9196
- _smb2_smb_read_write_async.kalloc_type_view_9348
- _smb2_smb_read_write_async.kalloc_type_view_9414
- _smb2_smb_read_write_async.kalloc_type_view_9742
- _smb2_smb_read_write_async.kalloc_type_view_9811
- _smb2_smb_write_uio.kalloc_type_view_10971
- _smb2_smb_write_uio.kalloc_type_view_11024
- _smb2fs_reconnect.kalloc_type_view_3846
- _smb2fs_reconnect.kalloc_type_view_4422
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3605
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3761
- _smb_symlink_target_is_unsafe
- _smbfs_CloseChildren.kalloc_type_view_3390
- _smbfs_build_path.kalloc_type_view_114
- _smbfs_build_path.kalloc_type_view_116
- _smbfs_build_path.kalloc_type_view_184
- _smbfs_build_path.kalloc_type_view_187
- _smbfs_clear_lockEntries.kalloc_type_view_6739
- _smbfs_clear_lockEntries.kalloc_type_view_6769
- _smbfs_free_locks_on_close.kalloc_type_view_6927
- _smbfs_get_lockEntry.kalloc_type_view_7134
- _smbfs_get_lockEntry.kalloc_type_view_7223
- _smbfs_lease_hash_add.kalloc_type_view_6180
- _smbfs_lease_hash_remove.kalloc_type_view_6280
- _smbfs_nget.kalloc_type_view_1030
- _smbfs_nget.kalloc_type_view_1050
- _smbfs_nget.kalloc_type_view_1057
- _smbfs_nget.kalloc_type_view_1363
- _smbfs_nget.kalloc_type_view_946
- _smbfs_nget.kalloc_type_view_975
- _smbfs_smb_findopen.kalloc_type_view_5978
- _smbfs_smb_reopen_file.kalloc_type_view_5065
- _smbfs_smb_reopen_file.kalloc_type_view_5141
- _smbfs_trigger_rel_mount_args.kalloc_type_view_283
- _smbfs_vgetstrm.kalloc_type_view_1450
- _smbfs_vgetstrm.kalloc_type_view_1457
- _smbfs_vgetstrm.kalloc_type_view_1668
Functions:
~ _smb_check_for_windows_symlink : 888 -> 868
~ _smbfs_trigger_get_mount_args : 820 -> 1028
~ _smbfs_trigger_rel_mount_args : 84 -> 100
~ _smbfs_smb_get_reparse_tag : 600 -> 576
~ _smbfs_smb_windows_read_symlink : 792 -> 712
~ _smbfs_smb_unix_read_symlink : 888 -> 784
- _smb_symlink_target_is_unsafe
~ _smb2_smb_parse_get_reparse_point : 576 -> 552
CStrings:
+ ","
+ "noexec"
+ "quarantine"
+ "rdonly"
- "%s: %s has an unsafe symlink target, rejecting\n"
```
