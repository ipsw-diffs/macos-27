## com.apple.filesystems.apfs

> `com.apple.filesystems.apfs`

```diff

-3288.40.17.0.0
+3288.41.1.0.0
   __TEXT.__const: 0xa00
-  __TEXT.__cstring: 0x5522b
-  __TEXT_EXEC.__text: 0x164240
+  __TEXT.__cstring: 0x55386
+  __TEXT_EXEC.__text: 0x1645c4
   __TEXT_EXEC.__auth_stubs: 0x2630
   __DATA.__data: 0x7c4
   __DATA.__bss: 0xb10

   __DATA_CONST.__auth_got: 0x1318
   __DATA_CONST.__got: 0x160
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 2504
-  Symbols:   4574
-  CStrings:  7328
+  Functions: 2506
+  Symbols:   4576
+  CStrings:  7333
 
Symbols:
+ _cp_open_needs_crypto
+ _fs_add_xattr.kalloc_type_view_23507
+ _fs_add_xattr.kalloc_type_view_23513
+ _fs_add_xattr.kalloc_type_view_23516
+ _fs_add_xattr.kalloc_type_view_23570
+ _fs_add_xattr.kalloc_type_view_23571
+ _jcrypto_state_is_missing
+ apfs_drop_allocated_unwritten_ranges.kalloc_type_view_16907
+ apfs_find_gaps_in_rangelist.kalloc_type_view_12205
+ apfs_flush_allocated_unwritten_ranges.kalloc_type_view_14216
+ apfs_flush_allocated_unwritten_ranges.kalloc_type_view_14308
+ apfs_io_common.kalloc_type_view_18838
+ apfs_io_common.kalloc_type_view_18876
+ apfs_io_common.kalloc_type_view_18887
+ apfs_io_common.kalloc_type_view_18905
+ apfs_io_common.kalloc_type_view_18923
+ apfs_io_common.kalloc_type_view_18943
+ apfs_io_common.kalloc_type_view_18970
+ apfs_io_common.kalloc_type_view_19053
+ apfs_io_common.kalloc_type_view_19074
+ apfs_io_common.kalloc_type_view_19085
+ apfs_io_common.kalloc_type_view_19103
+ apfs_io_common.kalloc_type_view_19122
+ apfs_io_common.kalloc_type_view_19135
+ apfs_io_common.kalloc_type_view_19156
+ apfs_io_common.kalloc_type_view_19168
+ apfs_io_common.kalloc_type_view_19175
+ apfs_iodone.kalloc_type_view_18316
+ apfs_iodone.kalloc_type_view_18355
+ apfs_punch_out_ranges_in_fext.kalloc_type_view_21802
+ apfs_punch_out_ranges_in_fext.kalloc_type_view_21809
+ apfs_reallocate_range.kalloc_type_view_2348
+ apfs_reallocate_range.kalloc_type_view_2350
+ apfs_release_io_context.kalloc_type_view_18553
+ apfs_release_io_context.kalloc_type_view_18563
+ apfs_rr_async_read_callback.kalloc_type_view_1350
+ apfs_rr_move_data.kalloc_type_view_1455
+ apfs_rr_move_data.kalloc_type_view_1545
+ apfs_trim_ranges_in_region.kalloc_type_view_17520
+ apfs_update_ranges_on_allocation.kalloc_type_view_17611
+ apfs_update_reserved_ranges.kalloc_type_view_21945
+ apfs_update_reserved_ranges.kalloc_type_view_21950
+ apfs_vnop_blockmap.kalloc_type_view_17961
+ apfs_vnop_blockmap.kalloc_type_view_18249
+ apfs_vnop_getattrlistbulk.kalloc_type_view_19824
+ apfs_vnop_getattrlistbulk.kalloc_type_view_19837
+ apfs_vnop_getattrlistbulk.kalloc_type_view_19894
+ apfs_vnop_getattrlistbulk.kalloc_type_view_19918
+ apfs_vnop_readdir.kalloc_type_view_16533
+ apfs_vnop_readdir.kalloc_type_view_16555
+ apfs_vnop_readdir.kalloc_type_view_16647
+ apfs_vnop_readdir.kalloc_type_view_16657
+ apfs_vnop_readdir.kalloc_type_view_16678
+ arle_alloc_pending_entry.kalloc_type_view_21388
+ dft_alloc.kalloc_type_view_51
+ dft_alloc.kalloc_type_view_56
+ dft_alloc.kalloc_type_view_63
+ dft_alloc.kalloc_type_view_71
+ dft_free.kalloc_type_view_107
+ dump_extents_of_stream.kalloc_type_view_18890
+ ek_to_crypto_state.kalloc_type_view_33003
+ extent_evict_range.kalloc_type_view_26286
+ extent_evict_range.kalloc_type_view_26386
+ fs_get_xattr_ext.kalloc_type_view_23611
+ fs_get_xattr_ext.kalloc_type_view_23631
+ fs_iterate_snapshots.kalloc_type_view_27197
+ fs_iterate_snapshots.kalloc_type_view_27244
+ fs_map_file_offset_ext.kalloc_type_view_22357
+ fs_map_file_offset_ext.kalloc_type_view_22389
+ fs_map_file_offset_ext.kalloc_type_view_22427
+ fs_map_file_offset_ext.kalloc_type_view_22450
+ fs_remove_xattr_with_nstream_inode.kalloc_type_view_23714
+ fs_remove_xattr_with_nstream_inode.kalloc_type_view_23736
+ fs_remove_xattr_with_nstream_inode.kalloc_type_view_23757
+ fs_remove_xattr_with_nstream_inode.kalloc_type_view_23921
+ legacy_get_ek.kalloc_type_view_34438
+ lookup_unfoldable_name_iterator.kalloc_type_view_18488
+ lookup_unfoldable_name_iterator.kalloc_type_view_18494
+ lookup_unfoldable_name_iterator.kalloc_type_view_18506
+ simple_remove_xattr.kalloc_type_view_23650
+ simple_remove_xattr.kalloc_type_view_23663
+ update_parent_xattr.kalloc_type_view_20867
+ update_parent_xattr.kalloc_type_view_20997
+ xattr_cloner.kalloc_type_view_17115
+ xattr_cloner.kalloc_type_view_17164
+ xattr_ek_to_crypto_state.kalloc_type_view_33651
- _fs_add_xattr.kalloc_type_view_23505
- _fs_add_xattr.kalloc_type_view_23511
- _fs_add_xattr.kalloc_type_view_23514
- _fs_add_xattr.kalloc_type_view_23568
- _fs_add_xattr.kalloc_type_view_23569
- apfs_drop_allocated_unwritten_ranges.kalloc_type_view_16827
- apfs_find_gaps_in_rangelist.kalloc_type_view_12125
- apfs_flush_allocated_unwritten_ranges.kalloc_type_view_14136
- apfs_flush_allocated_unwritten_ranges.kalloc_type_view_14228
- apfs_io_common.kalloc_type_view_18758
- apfs_io_common.kalloc_type_view_18796
- apfs_io_common.kalloc_type_view_18807
- apfs_io_common.kalloc_type_view_18825
- apfs_io_common.kalloc_type_view_18843
- apfs_io_common.kalloc_type_view_18863
- apfs_io_common.kalloc_type_view_18890
- apfs_io_common.kalloc_type_view_18973
- apfs_io_common.kalloc_type_view_18994
- apfs_io_common.kalloc_type_view_19005
- apfs_io_common.kalloc_type_view_19023
- apfs_io_common.kalloc_type_view_19042
- apfs_io_common.kalloc_type_view_19055
- apfs_io_common.kalloc_type_view_19076
- apfs_io_common.kalloc_type_view_19088
- apfs_io_common.kalloc_type_view_19095
- apfs_iodone.kalloc_type_view_18236
- apfs_iodone.kalloc_type_view_18275
- apfs_punch_out_ranges_in_fext.kalloc_type_view_21800
- apfs_punch_out_ranges_in_fext.kalloc_type_view_21807
- apfs_reallocate_range.kalloc_type_view_2328
- apfs_reallocate_range.kalloc_type_view_2330
- apfs_release_io_context.kalloc_type_view_18473
- apfs_release_io_context.kalloc_type_view_18483
- apfs_rr_async_read_callback.kalloc_type_view_1349
- apfs_rr_move_data.kalloc_type_view_1454
- apfs_rr_move_data.kalloc_type_view_1544
- apfs_trim_ranges_in_region.kalloc_type_view_17440
- apfs_update_ranges_on_allocation.kalloc_type_view_17531
- apfs_update_reserved_ranges.kalloc_type_view_21943
- apfs_update_reserved_ranges.kalloc_type_view_21948
- apfs_vnop_blockmap.kalloc_type_view_17881
- apfs_vnop_blockmap.kalloc_type_view_18169
- apfs_vnop_getattrlistbulk.kalloc_type_view_19744
- apfs_vnop_getattrlistbulk.kalloc_type_view_19757
- apfs_vnop_getattrlistbulk.kalloc_type_view_19814
- apfs_vnop_getattrlistbulk.kalloc_type_view_19838
- apfs_vnop_readdir.kalloc_type_view_16453
- apfs_vnop_readdir.kalloc_type_view_16475
- apfs_vnop_readdir.kalloc_type_view_16567
- apfs_vnop_readdir.kalloc_type_view_16577
- apfs_vnop_readdir.kalloc_type_view_16598
- arle_alloc_pending_entry.kalloc_type_view_21386
- dft_alloc.kalloc_type_view_50
- dft_alloc.kalloc_type_view_55
- dft_alloc.kalloc_type_view_62
- dft_alloc.kalloc_type_view_70
- dft_free.kalloc_type_view_106
- dump_extents_of_stream.kalloc_type_view_18888
- ek_to_crypto_state.kalloc_type_view_33001
- extent_evict_range.kalloc_type_view_26284
- extent_evict_range.kalloc_type_view_26384
- fs_get_xattr_ext.kalloc_type_view_23609
- fs_get_xattr_ext.kalloc_type_view_23629
- fs_iterate_snapshots.kalloc_type_view_27195
- fs_iterate_snapshots.kalloc_type_view_27242
- fs_map_file_offset_ext.kalloc_type_view_22355
- fs_map_file_offset_ext.kalloc_type_view_22387
- fs_map_file_offset_ext.kalloc_type_view_22425
- fs_map_file_offset_ext.kalloc_type_view_22448
- fs_remove_xattr_with_nstream_inode.kalloc_type_view_23712
- fs_remove_xattr_with_nstream_inode.kalloc_type_view_23734
- fs_remove_xattr_with_nstream_inode.kalloc_type_view_23755
- fs_remove_xattr_with_nstream_inode.kalloc_type_view_23919
- legacy_get_ek.kalloc_type_view_34436
- lookup_unfoldable_name_iterator.kalloc_type_view_18486
- lookup_unfoldable_name_iterator.kalloc_type_view_18492
- lookup_unfoldable_name_iterator.kalloc_type_view_18504
- simple_remove_xattr.kalloc_type_view_23648
- simple_remove_xattr.kalloc_type_view_23661
- update_parent_xattr.kalloc_type_view_20787
- update_parent_xattr.kalloc_type_view_20917
- xattr_cloner.kalloc_type_view_17113
- xattr_cloner.kalloc_type_view_17162
- xattr_ek_to_crypto_state.kalloc_type_view_33649
CStrings:
+ "%s:%d: %s apfs_rr: cleanup 0 failed to decrement head split crypto refcount (ret %d) \n"
+ "%s:%d: %s apfs_rr: cleanup first failed to decrement crypto refcount (ret %d) \n"
+ "%s:%d: %s apfs_rr: cleanup last failed to decrement crypto refcount (ret %d) \n"
+ "%s:%d: %s applied dstream workaround inode %llu\n"
+ "%s:%d: %s ino %llu '%s' cp_open() failed with EILSEQ\n"
+ "2026/10/07"
+ "22:31:51"
+ "22:31:52"
+ "3288.41.1"
+ "Oct  7 2026"
+ "apfs-3288.41.1"
- "2026/09/29"
- "21:14:26"
- "21:14:27"
- "3288.40.17"
- "Sep 29 2026"
- "apfs-3288.40.17"
```
