## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/Versions/A/APFS`

```diff

 3288.1.3.0.0
-  __TEXT.__text: 0x57140
+  __TEXT.__text: 0x5722c
   __TEXT.__const: 0x8540
   __TEXT.__cstring: 0xeada
   __TEXT.__oslogstring: 0x1467
Functions:
~ _btree_node_init_phys : 236 -> 240
~ _btree_node_key_off : 36 -> 40
~ _btree_node_key_len : 40 -> 44
~ _btree_node_val_off : 44 -> 48
~ _btree_node_val_ptr : 220 -> 224
~ _btree_node_entry_update : 2500 -> 2632
~ _btree_node_child_id_update : 236 -> 240
~ _bt_shift_or_split : 8716 -> 8568
~ _btree_iterate_nodes : 2688 -> 2696
~ _btree_node_compact : 1364 -> 1368
~ _bt_merge_nodes : 2128 -> 2148
~ _spaceman_allocation_init : 1064 -> 1068
~ _spaceman_datazone_load_from_disk : 268 -> 272
~ _spaceman_get_new_chunk_for_allocation_zone : 2264 -> 2272
~ _nextBaseAndAnyMarks : 1980 -> 2108
~ _spaceman_iterate_free_extents_internal : 3752 -> 3788
~ _spaceman_alloc_iterate_chunks : 3500 -> 3496
~ _spaceman_modify_bits : 3592 -> 3604
~ _nx_checkpoint_load_data : 1096 -> 1092
~ _OUTLINED_FUNCTION_1 : 44 -> 36
~ _OUTLINED_FUNCTION_2 : 36 -> 44
~ _btree_check_recent_sanity : 1260 -> 1264
~ _nx_check : 10480 -> 10416
~ _spaceman_fxc_tree_insert_at_path : 636 -> 664
~ _spaceman_fxc_tree_delete_at_path : 844 -> 868
~ _spaceman_fxtp_add_child : 244 -> 252
~ _spaceman_fxc_tree_adjacent : 244 -> 248
~ _spaceman_fxc_tree_single_rotate : 304 -> 308
~ _spaceman_fxc_tree_double_rotate : 364 -> 368
```
