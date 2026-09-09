## com.apple.BootCache

> `com.apple.BootCache`

```diff

 162.0.0.0.0
   __TEXT.__const: 0x68
   __TEXT.__cstring: 0x17a6
-  __TEXT_EXEC.__text: 0xb490
+  __TEXT_EXEC.__text: 0xb554
   __TEXT_EXEC.__auth_stubs: 0x880
   __DATA.__data: 0x118
   __DATA.__common: 0x38
Functions:
~ _BC_sysctl : 7436 -> 7440
~ _BC_get_dev : 148 -> 152
~ _BC_load : 252 -> 256
~ _BC_root_unmount_hook : 64 -> 68
~ _BC_unload : 200 -> 204
~ _BC_terminate_history : 480 -> 484
~ _BC_terminate_cache : 2088 -> 2092
~ _BC_discard_history : 144 -> 148
~ _BC_copyout_history_mounts : 80 -> 84
~ _BC_copyout_history_entries : 148 -> 152
~ _BC_reset_cache : 244 -> 248
~ _BC_add_history : 1776 -> 1780
~ _BC_cache_contains_block : 260 -> 264
~ _BC_mount_available : 572 -> 576
~ _BC_strategy : 8920 -> 8924
~ _BC_close : 1148 -> 1152
~ _BC_find_cache_mount : 168 -> 172
~ _wait_for_extent : 212 -> 216
~ _BC_handle_discards : 924 -> 928
~ _uuid_string : 112 -> 116
~ _BC_terminate_cache_thread : 68 -> 72
~ _BC_teardown_extent : 84 -> 88
~ _BC_teardown_mount : 132 -> 136
~ _BC_setup_mount : 336 -> 340
~ _BC_setup_extent : 172 -> 176
~ _BC_alloc_pagebuffer : 168 -> 172
~ _fill_in_bc_cache_mounts : 2388 -> 2392
~ _BC_teardown_mount_and_extents : 232 -> 236
~ _BC_fill_in_cache_mount : 704 -> 708
~ _BC_fill_in_cache_mount_ex : 1664 -> 1668
~ _BC_reader_thread : 3720 -> 3724
~ _check_for_new_mount_itr : 1756 -> 1760
~ _BC_get_history_mount_device : 304 -> 308
~ __ZN19com_apple_BootCache9MetaClassC1Ev : 72 -> 76
~ __ZN19com_apple_BootCacheC2EPK11OSMetaClass : 52 -> 56
~ __ZN19com_apple_BootCacheC1EPK11OSMetaClass : 52 -> 56
~ __ZN19com_apple_BootCacheD0Ev : 68 -> 72
~ __ZN19com_apple_BootCache9MetaClassC2Ev : 72 -> 76
~ __ZNK19com_apple_BootCache9MetaClass5allocEv : 104 -> 108
~ __ZN19com_apple_BootCacheC1Ev : 88 -> 92
~ __ZN19com_apple_BootCacheC2Ev : 88 -> 92
~ __ZN19com_apple_BootCache5startEP9IOService : 108 -> 112
~ __ZN19com_apple_BootCache4stopEP9IOService : 148 -> 152
~ _GLOBAL__sub_I_kext_glue.cpp : 80 -> 84
~ _bc_get_volume_info : 2028 -> 2032
~ __ZL47apfs_container_has_encrypted_or_rolling_volumesP15IORegistryEntryPbS1_ : 596 -> 600
~ _bc_get_group_uuid_for_dev : 1428 -> 1432
~ _lookup_dev_name : 780 -> 784
~ _apfs_get_inode : 76 -> 80
```
