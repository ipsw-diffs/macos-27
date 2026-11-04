## com.apple.filesystems.smbfs

> `com.apple.filesystems.smbfs`

```diff

-579.40.9.0.0
+579.60.5.0.0
   __TEXT.__const: 0xc35
-  __TEXT.__cstring: 0x5196
+  __TEXT.__cstring: 0x51ac
   __TEXT.__os_log: 0x1807a
-  __TEXT_EXEC.__text: 0x8466c
-  __TEXT_EXEC.__auth_stubs: 0x1580
+  __TEXT_EXEC.__text: 0x84838
+  __TEXT_EXEC.__auth_stubs: 0x1590
   __DATA.__data: 0x12d8
   __DATA.__bss: 0x107c
   __DATA.__common: 0x2278
   __DATA_CONST.__const: 0x78
   __DATA_CONST.__kalloc_type: 0x4ec0
   __DATA_CONST.__kalloc_var: 0x640
-  __DATA_CONST.__auth_got: 0xac0
+  __DATA_CONST.__auth_got: 0xac8
   __DATA_CONST.__got: 0x50
   __DATA_CONST.__auth_ptr: 0x8
   Functions: 799
-  Symbols:   2327
-  CStrings:  2658
+  Symbols:   2328
+  CStrings:  2659
 
Symbols:
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6328
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6366
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6377
+ _smb1fs_smb_findclose.kalloc_type_view_5715
+ _smb2fs_reconnect.kalloc_type_view_3846
+ _smb2fs_reconnect.kalloc_type_view_4422
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3605
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3761
+ _smb_session_lease_thread.kalloc_type_view_2276
+ _smb_share_create.kalloc_type_view_1527
+ _smb_share_create.kalloc_type_view_1533
+ _smb_share_free.kalloc_type_view_1484
+ _smbfs_CloseChildren.kalloc_type_view_3390
+ _smbfs_clear_lockEntries.kalloc_type_view_6739
+ _smbfs_clear_lockEntries.kalloc_type_view_6769
+ _smbfs_free_locks_on_close.kalloc_type_view_6927
+ _smbfs_get_lockEntry.kalloc_type_view_7134
+ _smbfs_get_lockEntry.kalloc_type_view_7223
+ _smbfs_lease_hash_add.kalloc_type_view_6180
+ _smbfs_lease_hash_remove.kalloc_type_view_6280
+ _smbfs_smb_findopen.kalloc_type_view_5978
+ _smbfs_smb_reopen_file.kalloc_type_view_5065
+ _smbfs_smb_reopen_file.kalloc_type_view_5141
+ _smbfs_vnop_advlock.kalloc_type_view_11069
+ _smbfs_vnop_advlock.kalloc_type_view_11158
+ _smbfs_vnop_getxattr.kalloc_type_view_12851
+ _smbfs_vnop_getxattr.kalloc_type_view_12868
+ _smbfs_vnop_rename.kalloc_type_view_9227
+ _vnode_isrecycled
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6285
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6323
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6334
- _smb1fs_smb_findclose.kalloc_type_view_5709
- _smb2fs_reconnect.kalloc_type_view_3835
- _smb2fs_reconnect.kalloc_type_view_4379
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3597
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3753
- _smb_session_lease_thread.kalloc_type_view_2260
- _smb_share_create.kalloc_type_view_1513
- _smb_share_create.kalloc_type_view_1519
- _smb_share_free.kalloc_type_view_1470
- _smbfs_CloseChildren.kalloc_type_view_3387
- _smbfs_clear_lockEntries.kalloc_type_view_6696
- _smbfs_clear_lockEntries.kalloc_type_view_6726
- _smbfs_free_locks_on_close.kalloc_type_view_6884
- _smbfs_get_lockEntry.kalloc_type_view_7091
- _smbfs_get_lockEntry.kalloc_type_view_7180
- _smbfs_lease_hash_add.kalloc_type_view_6137
- _smbfs_lease_hash_remove.kalloc_type_view_6237
- _smbfs_smb_findopen.kalloc_type_view_5972
- _smbfs_smb_reopen_file.kalloc_type_view_5059
- _smbfs_smb_reopen_file.kalloc_type_view_5135
- _smbfs_vnop_advlock.kalloc_type_view_11050
- _smbfs_vnop_advlock.kalloc_type_view_11139
- _smbfs_vnop_getxattr.kalloc_type_view_12832
- _smbfs_vnop_getxattr.kalloc_type_view_12849
- _smbfs_vnop_rename.kalloc_type_view_9208
Functions:
~ _smbfs_CloseChildren : 768 -> 848
~ _smb2fs_reconnect : 3244 -> 3472
~ _smbfs_update_symlink_cache : 252 -> 280
~ _smbfs_vnop_rename : 5224 -> 5268
~ _smb_sm_negotiate : 2188 -> 2260
~ _smb_session_lease_thread : 444 -> 452
CStrings:
+ "11221"
+ "session-lease-start"
- "121"
```
