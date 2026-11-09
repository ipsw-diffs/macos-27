## com.apple.filesystems.smbfs

> `com.apple.filesystems.smbfs`

```diff

-579.40.9.0.0
+579.41.1.0.0
   __TEXT.__const: 0xc35
   __TEXT.__cstring: 0x5196
-  __TEXT.__os_log: 0x1807a
-  __TEXT_EXEC.__text: 0x8466c
+  __TEXT.__os_log: 0x1801a
+  __TEXT_EXEC.__text: 0x84428
   __TEXT_EXEC.__auth_stubs: 0x1580
   __DATA.__data: 0x12d8
   __DATA.__bss: 0x107c

   __DATA_CONST.__auth_got: 0xac0
   __DATA_CONST.__got: 0x50
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 799
-  Symbols:   2327
-  CStrings:  2658
+  Functions: 798
+  Symbols:   2326
+  CStrings:  2657
 
Symbols:
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6276
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6314
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6325
+ _smb1fs_smb_findclose.kalloc_type_view_5683
+ _smb2_smb_read_uio.kalloc_type_view_9173
+ _smb2_smb_read_uio.kalloc_type_view_9190
+ _smb2_smb_read_write_async.kalloc_type_view_9342
+ _smb2_smb_read_write_async.kalloc_type_view_9408
+ _smb2_smb_read_write_async.kalloc_type_view_9736
+ _smb2_smb_read_write_async.kalloc_type_view_9805
+ _smb2_smb_write_uio.kalloc_type_view_10965
+ _smb2_smb_write_uio.kalloc_type_view_11018
+ _smb2fs_reconnect.kalloc_type_view_3826
+ _smb2fs_reconnect.kalloc_type_view_4370
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3588
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3744
+ _smbfs_CloseChildren.kalloc_type_view_3378
+ _smbfs_build_path.kalloc_type_view_113
+ _smbfs_build_path.kalloc_type_view_115
+ _smbfs_build_path.kalloc_type_view_183
+ _smbfs_build_path.kalloc_type_view_186
+ _smbfs_clear_lockEntries.kalloc_type_view_6687
+ _smbfs_clear_lockEntries.kalloc_type_view_6717
+ _smbfs_free_locks_on_close.kalloc_type_view_6875
+ _smbfs_get_lockEntry.kalloc_type_view_7082
+ _smbfs_get_lockEntry.kalloc_type_view_7171
+ _smbfs_lease_hash_add.kalloc_type_view_6128
+ _smbfs_lease_hash_remove.kalloc_type_view_6228
+ _smbfs_nget.kalloc_type_view_1021
+ _smbfs_nget.kalloc_type_view_1041
+ _smbfs_nget.kalloc_type_view_1048
+ _smbfs_nget.kalloc_type_view_1354
+ _smbfs_nget.kalloc_type_view_937
+ _smbfs_nget.kalloc_type_view_966
+ _smbfs_smb_findopen.kalloc_type_view_5946
+ _smbfs_smb_reopen_file.kalloc_type_view_5033
+ _smbfs_smb_reopen_file.kalloc_type_view_5109
+ _smbfs_trigger_get_mount_args.kalloc_type_view_205
+ _smbfs_trigger_get_mount_args.kalloc_type_view_236
+ _smbfs_trigger_get_mount_args.kalloc_type_view_260
+ _smbfs_trigger_rel_mount_args.kalloc_type_view_282
+ _smbfs_vgetstrm.kalloc_type_view_1441
+ _smbfs_vgetstrm.kalloc_type_view_1448
+ _smbfs_vgetstrm.kalloc_type_view_1659
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6285
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6323
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6334
- _smb1fs_smb_findclose.kalloc_type_view_5709
- _smb2_smb_read_uio.kalloc_type_view_9179
- _smb2_smb_read_uio.kalloc_type_view_9196
- _smb2_smb_read_write_async.kalloc_type_view_9348
- _smb2_smb_read_write_async.kalloc_type_view_9414
- _smb2_smb_read_write_async.kalloc_type_view_9742
- _smb2_smb_read_write_async.kalloc_type_view_9811
- _smb2_smb_write_uio.kalloc_type_view_10971
- _smb2_smb_write_uio.kalloc_type_view_11024
- _smb2fs_reconnect.kalloc_type_view_3835
- _smb2fs_reconnect.kalloc_type_view_4379
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3597
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3753
- _smb_symlink_target_is_unsafe
- _smbfs_CloseChildren.kalloc_type_view_3387
- _smbfs_build_path.kalloc_type_view_114
- _smbfs_build_path.kalloc_type_view_116
- _smbfs_build_path.kalloc_type_view_184
- _smbfs_build_path.kalloc_type_view_187
- _smbfs_clear_lockEntries.kalloc_type_view_6696
- _smbfs_clear_lockEntries.kalloc_type_view_6726
- _smbfs_free_locks_on_close.kalloc_type_view_6884
- _smbfs_get_lockEntry.kalloc_type_view_7091
- _smbfs_get_lockEntry.kalloc_type_view_7180
- _smbfs_lease_hash_add.kalloc_type_view_6137
- _smbfs_lease_hash_remove.kalloc_type_view_6237
- _smbfs_nget.kalloc_type_view_1030
- _smbfs_nget.kalloc_type_view_1050
- _smbfs_nget.kalloc_type_view_1057
- _smbfs_nget.kalloc_type_view_1363
- _smbfs_nget.kalloc_type_view_946
- _smbfs_nget.kalloc_type_view_975
- _smbfs_smb_findopen.kalloc_type_view_5972
- _smbfs_smb_reopen_file.kalloc_type_view_5059
- _smbfs_smb_reopen_file.kalloc_type_view_5135
- _smbfs_trigger_get_mount_args.kalloc_type_view_206
- _smbfs_trigger_get_mount_args.kalloc_type_view_237
- _smbfs_trigger_get_mount_args.kalloc_type_view_261
- _smbfs_trigger_rel_mount_args.kalloc_type_view_283
- _smbfs_vgetstrm.kalloc_type_view_1450
- _smbfs_vgetstrm.kalloc_type_view_1457
- _smbfs_vgetstrm.kalloc_type_view_1668
Functions:
~ _smb_check_for_windows_symlink : 888 -> 868
~ _smbfs_smb_get_reparse_tag : 600 -> 576
~ _smbfs_smb_windows_read_symlink : 792 -> 712
~ _smbfs_smb_unix_read_symlink : 888 -> 784
- _smb_symlink_target_is_unsafe
~ _smb2_smb_parse_get_reparse_point : 576 -> 552
CStrings:
- "%s: %s has an unsafe symlink target, rejecting\n"
```
