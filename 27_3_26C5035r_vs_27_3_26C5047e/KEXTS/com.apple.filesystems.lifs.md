## com.apple.filesystems.lifs

> `com.apple.filesystems.lifs`

```diff

-974.60.5.0.0
-  __TEXT.__os_log: 0x1fde
+974.60.6.0.0
+  __TEXT.__os_log: 0x202b
   __TEXT.__cstring: 0x29f1
   __TEXT.__const: 0x338
-  __TEXT_EXEC.__text: 0x20870
+  __TEXT_EXEC.__text: 0x20960
   __TEXT_EXEC.__auth_stubs: 0xfa0
   __DATA.__data: 0x528
   __DATA.__common: 0x130

   __DATA_CONST.__auth_got: 0x7d0
   __DATA_CONST.__got: 0x88
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 463
-  Symbols:   1331
-  CStrings:  519
+  Functions: 464
+  Symbols:   1333
+  CStrings:  521
 
Symbols:
+ _add_sillyrename_entry.kalloc_type_view_2142
+ _add_sillyrename_entry.kalloc_type_view_2165
+ _cleanup_sillyrename_entries.kalloc_type_view_2263
+ _lifs_apply_cache_action._os_log_fmt
+ _lifs_create_node_ext.kalloc_type_view_448
+ _lifs_create_node_ext.kalloc_type_view_609
+ _lifs_hash
+ _lifs_mirror_mount_domount.kalloc_type_view_1278
+ _lifs_mirror_mount_domount.kalloc_type_view_1329
+ _lifs_mount.kalloc_type_view_888
+ _lifs_mount.kalloc_type_view_938
+ _lifs_mount.kalloc_type_view_942
+ _lifs_mount.kalloc_type_view_946
+ _lifs_unmount.kalloc_type_view_1097
+ _lifs_unmount_dangling_all.kalloc_type_view_1593
+ _lifs_unmount_dangling_all.kalloc_type_view_1614
+ _lifs_unmount_dangling_thread.kalloc_type_view_1566
+ _lifs_vnop_reclaim.kalloc_type_view_5167
+ _move_sillyrename_entries.kalloc_type_view_2237
- _add_sillyrename_entry.kalloc_type_view_2144
- _add_sillyrename_entry.kalloc_type_view_2167
- _cleanup_sillyrename_entries.kalloc_type_view_2265
- _lifs_create_node_ext.kalloc_type_view_450
- _lifs_create_node_ext.kalloc_type_view_611
- _lifs_mirror_mount_domount.kalloc_type_view_1280
- _lifs_mirror_mount_domount.kalloc_type_view_1331
- _lifs_mount.kalloc_type_view_873
- _lifs_mount.kalloc_type_view_923
- _lifs_mount.kalloc_type_view_927
- _lifs_mount.kalloc_type_view_931
- _lifs_unmount.kalloc_type_view_1082
- _lifs_unmount_dangling_all.kalloc_type_view_1578
- _lifs_unmount_dangling_all.kalloc_type_view_1599
- _lifs_unmount_dangling_thread.kalloc_type_view_1551
- _lifs_vnop_reclaim.kalloc_type_view_5169
- _move_sillyrename_entries.kalloc_type_view_2239
Functions:
~ _lifs_vnop_reclaim : 660 -> 656
~ __ZN19AppleLIFSUserClient18methodOpenKernelFDEPS_PvP25IOExternalMethodArguments : 880 -> 876
~ _lifs_mount : 2164 -> 2340
+ _lifs_hash
~ _lifs_apply_cache_action : 404 -> 456
CStrings:
+ "Failed to allocate lifs node table"
+ "REVOKE is not supported on the mount root"
```
