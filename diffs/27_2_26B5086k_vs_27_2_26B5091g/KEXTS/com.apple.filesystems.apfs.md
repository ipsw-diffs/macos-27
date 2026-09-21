## com.apple.filesystems.apfs

> `com.apple.filesystems.apfs`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-3288.40.13.0.0
+3288.40.14.0.0
   __TEXT.__const: 0xa00
   __TEXT.__cstring: 0x5505c
-  __TEXT_EXEC.__text: 0x163e58
+  __TEXT_EXEC.__text: 0x163ef0
   __TEXT_EXEC.__auth_stubs: 0x2630
   __DATA.__data: 0x7c4
   __DATA.__bss: 0xb10
Symbols:
+ _fs_add_xattr.kalloc_type_view_23489
+ _fs_add_xattr.kalloc_type_view_23495
+ _fs_add_xattr.kalloc_type_view_23498
+ _fs_add_xattr.kalloc_type_view_23552
+ _fs_add_xattr.kalloc_type_view_23553
+ apfs_punch_out_ranges_in_fext.kalloc_type_view_21791
+ apfs_update_reserved_ranges.kalloc_type_view_21927
+ apfs_update_reserved_ranges.kalloc_type_view_21932
+ arle_alloc_pending_entry.kalloc_type_view_21370
+ change_crypto_id_prot_class.kalloc_type_view_9820
+ change_crypto_id_prot_class.kalloc_type_view_9886
+ create_new_crypto_state_for_id.kalloc_type_view_7577
+ create_new_crypto_state_for_id.kalloc_type_view_7582
+ create_new_crypto_state_for_id.kalloc_type_view_7602
+ create_sibling_link.kalloc_type_view_11683
+ create_sibling_link.kalloc_type_view_11699
+ dir_rec_alloc_with_hash.kalloc_type_view_11318
+ dir_rec_alloc_with_hash.kalloc_type_view_11324
+ dir_rec_alloc_with_hash.kalloc_type_view_11348
+ dump_extents_of_stream.kalloc_type_view_18872
+ ek_to_crypto_state.kalloc_type_view_32985
+ er_state_allocate_roll_buffers.kalloc_type_view_8198
+ er_state_destroy_obj.kalloc_type_view_8837
+ er_state_free_roll_buffers.kalloc_type_view_8160
+ er_state_obj_create_phys_from_previous_version.kalloc_type_view_8240
+ er_state_upgrade_version.kalloc_type_view_8393
+ extent_evict_range.kalloc_type_view_26268
+ extent_evict_range.kalloc_type_view_26368
+ fext_collector.kalloc_type_view_14449
+ fext_collector_cleanup.kalloc_type_view_14412
+ fext_collector_reset.kalloc_type_view_14401
+ free_linkids.kalloc_type_view_11875
+ fs_get_xattr_ext.kalloc_type_view_23593
+ fs_get_xattr_ext.kalloc_type_view_23613
+ fs_iterate_snapshots.kalloc_type_view_27179
+ fs_iterate_snapshots.kalloc_type_view_27226
+ fs_map_file_offset_ext.kalloc_type_view_22339
+ fs_map_file_offset_ext.kalloc_type_view_22371
+ fs_map_file_offset_ext.kalloc_type_view_22409
+ fs_map_file_offset_ext.kalloc_type_view_22432
+ fs_remove_xattr_with_nstream_inode.kalloc_type_view_23696
+ fs_remove_xattr_with_nstream_inode.kalloc_type_view_23718
+ fs_remove_xattr_with_nstream_inode.kalloc_type_view_23739
+ fs_remove_xattr_with_nstream_inode.kalloc_type_view_23903
+ icp_new_crypto.kalloc_type_view_7978
+ icp_new_crypto.kalloc_type_view_7990
+ icp_new_crypto.kalloc_type_view_7992
+ icp_new_crypto.kalloc_type_view_8026
+ icp_new_crypto.kalloc_type_view_8051
+ icp_new_crypto.kalloc_type_view_8066
+ insert_linkid.kalloc_type_view_11823
+ jobj_allocate.kalloc_type_view_2683
+ jobj_allocate.kalloc_type_view_2687
+ jobj_allocate.kalloc_type_view_2693
+ jobj_allocate.kalloc_type_view_2697
+ jobj_allocate.kalloc_type_view_2703
+ jobj_allocate.kalloc_type_view_2706
+ jobj_allocate.kalloc_type_view_2709
+ jobj_allocate.kalloc_type_view_2719
+ jobj_allocate.kalloc_type_view_2722
+ jobj_allocate.kalloc_type_view_2732
+ jobj_allocate.kalloc_type_view_2735
+ jobj_allocate.kalloc_type_view_2744
+ jobj_allocate.kalloc_type_view_2747
+ jobj_allocate.kalloc_type_view_2750
+ jobj_release.kalloc_type_view_2772
+ jobj_release.kalloc_type_view_2775
+ jobj_release.kalloc_type_view_2778
+ jobj_release.kalloc_type_view_2787
+ jobj_release.kalloc_type_view_2790
+ jobj_release.kalloc_type_view_2807
+ jobj_release.kalloc_type_view_2810
+ jobj_release.kalloc_type_view_2827
+ jobj_release.kalloc_type_view_2837
+ jobj_release.kalloc_type_view_2841
+ jobj_release.kalloc_type_view_2847
+ legacy_get_ek.kalloc_type_view_34420
+ lookup_unfoldable_name_iterator.kalloc_type_view_18478
+ lookup_unfoldable_name_iterator.kalloc_type_view_18484
+ lookup_unfoldable_name_iterator.kalloc_type_view_18492
+ simple_remove_xattr.kalloc_type_view_23632
+ simple_remove_xattr.kalloc_type_view_23645
+ xattr_cloner.kalloc_type_view_17113
+ xattr_cloner.kalloc_type_view_17162
+ xattr_ek_to_crypto_state.kalloc_type_view_33633
- _fs_add_xattr.kalloc_type_view_23482
- _fs_add_xattr.kalloc_type_view_23488
- _fs_add_xattr.kalloc_type_view_23491
- _fs_add_xattr.kalloc_type_view_23545
- _fs_add_xattr.kalloc_type_view_23546
- apfs_punch_out_ranges_in_fext.kalloc_type_view_21777
- apfs_update_reserved_ranges.kalloc_type_view_21920
- apfs_update_reserved_ranges.kalloc_type_view_21925
- arle_alloc_pending_entry.kalloc_type_view_21363
- change_crypto_id_prot_class.kalloc_type_view_9813
- change_crypto_id_prot_class.kalloc_type_view_9879
- create_new_crypto_state_for_id.kalloc_type_view_7570
- create_new_crypto_state_for_id.kalloc_type_view_7575
- create_new_crypto_state_for_id.kalloc_type_view_7595
- create_sibling_link.kalloc_type_view_11676
- create_sibling_link.kalloc_type_view_11692
- dir_rec_alloc_with_hash.kalloc_type_view_11311
- dir_rec_alloc_with_hash.kalloc_type_view_11317
- dir_rec_alloc_with_hash.kalloc_type_view_11341
- dump_extents_of_stream.kalloc_type_view_18865
- ek_to_crypto_state.kalloc_type_view_32977
- er_state_allocate_roll_buffers.kalloc_type_view_8191
- er_state_destroy_obj.kalloc_type_view_8830
- er_state_free_roll_buffers.kalloc_type_view_8153
- er_state_obj_create_phys_from_previous_version.kalloc_type_view_8233
- er_state_upgrade_version.kalloc_type_view_8386
- extent_evict_range.kalloc_type_view_26260
- extent_evict_range.kalloc_type_view_26360
- fext_collector.kalloc_type_view_14435
- fext_collector_cleanup.kalloc_type_view_14405
- fext_collector_reset.kalloc_type_view_14394
- free_linkids.kalloc_type_view_11868
- fs_get_xattr_ext.kalloc_type_view_23586
- fs_get_xattr_ext.kalloc_type_view_23606
- fs_iterate_snapshots.kalloc_type_view_27171
- fs_iterate_snapshots.kalloc_type_view_27218
- fs_map_file_offset_ext.kalloc_type_view_22332
- fs_map_file_offset_ext.kalloc_type_view_22364
- fs_map_file_offset_ext.kalloc_type_view_22402
- fs_map_file_offset_ext.kalloc_type_view_22425
- fs_remove_xattr_with_nstream_inode.kalloc_type_view_23689
- fs_remove_xattr_with_nstream_inode.kalloc_type_view_23711
- fs_remove_xattr_with_nstream_inode.kalloc_type_view_23732
- fs_remove_xattr_with_nstream_inode.kalloc_type_view_23896
- icp_new_crypto.kalloc_type_view_7971
- icp_new_crypto.kalloc_type_view_7983
- icp_new_crypto.kalloc_type_view_7985
- icp_new_crypto.kalloc_type_view_8019
- icp_new_crypto.kalloc_type_view_8044
- icp_new_crypto.kalloc_type_view_8059
- insert_linkid.kalloc_type_view_11816
- jobj_allocate.kalloc_type_view_2673
- jobj_allocate.kalloc_type_view_2676
- jobj_allocate.kalloc_type_view_2686
- jobj_allocate.kalloc_type_view_2690
- jobj_allocate.kalloc_type_view_2696
- jobj_allocate.kalloc_type_view_2699
- jobj_allocate.kalloc_type_view_2702
- jobj_allocate.kalloc_type_view_2705
- jobj_allocate.kalloc_type_view_2708
- jobj_allocate.kalloc_type_view_2718
- jobj_allocate.kalloc_type_view_2728
- jobj_allocate.kalloc_type_view_2737
- jobj_allocate.kalloc_type_view_2740
- jobj_allocate.kalloc_type_view_2743
- jobj_release.kalloc_type_view_2765
- jobj_release.kalloc_type_view_2768
- jobj_release.kalloc_type_view_2771
- jobj_release.kalloc_type_view_2776
- jobj_release.kalloc_type_view_2780
- jobj_release.kalloc_type_view_2789
- jobj_release.kalloc_type_view_2800
- jobj_release.kalloc_type_view_2806
- jobj_release.kalloc_type_view_2830
- jobj_release.kalloc_type_view_2834
- jobj_release.kalloc_type_view_2840
- legacy_get_ek.kalloc_type_view_34412
- lookup_unfoldable_name_iterator.kalloc_type_view_18471
- lookup_unfoldable_name_iterator.kalloc_type_view_18477
- lookup_unfoldable_name_iterator.kalloc_type_view_18485
- simple_remove_xattr.kalloc_type_view_23625
- simple_remove_xattr.kalloc_type_view_23638
- xattr_cloner.kalloc_type_view_17106
- xattr_cloner.kalloc_type_view_17155
- xattr_ek_to_crypto_state.kalloc_type_view_33625
Functions:
~ _handle_clonegroup_iterate : 2260 -> 2264
~ _jobj_validate_key_val : 644 -> 668
~ _spaceman_modify_bits : 3800 -> 3848
~ _spaceman_resize : 6388 -> 6396
~ _spaceman_iterate_process_bitmap_block : 2500 -> 2504
~ _spaceman_iterate_free_extents_internal : 4336 -> 4356
~ _spaceman_alloc_iterate_chunks : 3660 -> 3704
CStrings:
+ "18:58:25"
+ "18:58:26"
+ "2026/09/13"
+ "3288.40.14"
+ "Sep 13 2026"
+ "apfs-3288.40.14"
- "2026/09/04"
- "22:55:09"
- "22:55:10"
- "3288.40.13"
- "Sep  4 2026"
- "apfs-3288.40.13"
```
