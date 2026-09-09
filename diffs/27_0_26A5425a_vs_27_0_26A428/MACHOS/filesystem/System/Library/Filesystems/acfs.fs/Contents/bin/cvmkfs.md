## cvmkfs

> `/System/Library/Filesystems/acfs.fs/Contents/bin/cvmkfs`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0x92b60
+  __TEXT.__text: 0x92340
   __TEXT.__auth_stubs: 0x1420
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0xc910
   __TEXT.__cstring: 0x20e8c
   __TEXT.__gcc_except_tab: 0x5c8
-  __TEXT.__unwind_info: 0x1a70
+  __TEXT.__unwind_info: 0x22c0
   __DATA_CONST.__const: 0x708
   __DATA_CONST.__cfstring: 0x460
   __DATA_CONST.__auth_got: 0xa18

   - /usr/lib/libcompression.dylib
   - /usr/lib/libxml2.2.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 2287
+  Functions: 2288
   Symbols:   3471
   CStrings:  3709
 
Functions:
~ _d_finish : 148 -> 136
~ _user_response : 100 -> 88
~ _buf_read_data : 412 -> 416
~ _buf_write_data : 432 -> 436
~ _temp_file_close : 528 -> 516
~ _inplace_bt_finish_cb : 76 -> 64
~ _inplace_bt_finish_iget : 84 -> 72
~ _slice_bt_finish : 164 -> 152
~ _bt_space_find_freespace : 284 -> 280
~ _space_mark : 616 -> 612
~ _tmpext_mark_all : 1924 -> 1920
~ _CowIO_internal : 1232 -> 1236
~ _activate_pio : 140 -> 128
~ _deactivate_pio : 100 -> 88
~ _suspend_pio_activity : 152 -> 140
~ _resume_pio_activity : 84 -> 72
~ _setupio_rw : 552 -> 548
~ _pio_pdev_free : 156 -> 144
~ _pio_stats : 240 -> 228
~ ___starter : 104 -> 92
~ __HexDump : 468 -> 456
~ _scan_progress : 716 -> 704
~ _CvDumpLabel : 2596 -> 2584
~ _CvFreeLabelBuffer : 68 -> 56
~ _CvCopyLabel : 80 -> 68
~ _verify_lun_readable : 736 -> 732
~ _label_config_failed : 204 -> 192
~ _CvBuildLabelEFI : 344 -> 332
~ _CvBuildLabel : 428 -> 404
~ _CvLabelWarnings : 712 -> 700
~ _CvLabelChangeEssay : 436 -> 424
~ _PlistString : 224 -> 212
~ _CvDisplayLabel : 1816 -> 1804
~ _disk_scan_finalize : 1748 -> 1744
~ _CvPrintInfo : 664 -> 652
~ _human_capacity : 200 -> 188
~ _initLibMPIOFramework : 40 -> 28
~ _find_IORegistryBSDName : 832 -> 836
~ _find_IORegistryContent : 728 -> 704
~ _find_IORegistrySerialNumber : 2248 -> 2260
~ _print_ucs2 : 108 -> 96
~ _Buf_init : 1412 -> 1404
~ _cvfs_buf_readahead : 344 -> 332
~ _cvfs_brelse : 328 -> 304
~ _cvfs_buf_claim : 168 -> 156
~ _cvfs_gang_getblk : 1172 -> 1164
~ _cvfs_bpin : 84 -> 72
~ _cvfs_bunpin : 84 -> 72
~ _cvfs_buf_adjust_refcount : 128 -> 116
~ ___starter : 104 -> 92
~ _In_hold_locked : 384 -> 372
~ _In_hold : 68 -> 56
~ _In_rele : 360 -> 348
~ _create_iel_hash_entry : 188 -> 176
~ _inodelock : 184 -> 160
~ _Inoderelease : 232 -> 208
~ _ic_inode_block_allocate : 416 -> 404
~ _inode_add_freelist_locked : 504 -> 492
~ _sb_rwlock : 476 -> 452
~ _sb_rwunlock : 188 -> 164
~ _journal_init : 312 -> 300
~ _Journal_zero : 436 -> 432
~ _Journal_clear : 60 -> 48
~ _Journal_recover : 6600 -> 6472
~ _jrnrec_trans_free : 232 -> 220
~ _l2bc_unhash_buf : 144 -> 132
~ _l2bc_free_buf : 168 -> 156
~ _l2bc_buf_inval_by_blkno : 328 -> 316
~ _l2bc_buf_process : 104 -> 92
~ _l2bc_buf_enqueue : 204 -> 192
~ _l2bc_reclaim_chunk : 136 -> 124
~ _l2bc_init_chunk : 272 -> 260
~ _l2bc_init : 1412 -> 1404
~ ___starter : 104 -> 92
~ _snbt_find_relative_block : 660 -> 664
~ _snbtree_lookup : 1036 -> 1032
~ _snbt_find_max_key : 400 -> 404
~ _snbtree_get_leaf_block : 1128 -> 1124
~ _snbt_rel_level : 96 -> 84
~ _snbt_check_block : 84 -> 72
~ _snbt_node_bsearch_block : 596 -> 600
~ _snbt_move_entries_node : 524 -> 544
~ _snbt_node_split : 548 -> 556
~ _snbt_node_remove_key : 496 -> 500
~ _snbt_node_fix_parent : 656 -> 652
~ _snbtree_payload_compare : 612 -> 600
~ _snbt_payload_copy : 580 -> 568
~ _snbt_payload_out : 848 -> 836
~ _snbt_shuffle_keys : 508 -> 512
~ _snbt_move_entries_leaf : 1096 -> 1100
~ _snbt_reorg_block : 360 -> 348
~ _snbtree_data_scan : 284 -> 288
~ _snbt_get_segp : 100 -> 104
~ _snbt_get_largest_block : 304 -> 300
~ _case_convert : 168 -> 156
~ _binode_get_segp : 100 -> 104
~ _binode_get_bia : 496 -> 500
~ _binode_set_bia : 340 -> 344
~ __binode_check : 260 -> 236
~ _extract_binode_flbt_attr : 168 -> 172
~ _binode_copy_core : 604 -> 608
~ _binode_incore_to_ondisk : 592 -> 596
~ _FsmPMGetDisks : 1388 -> 1384
~ _FsmGetPartitionNativeKeys : 416 -> 412
~ _FsmStartIoTest : 352 -> 344
~ ___starter : 104 -> 92
~ __Z31protobuf_AddDesc_qustat_2eprotov : 468 -> 456
~ __Z36protobuf_ShutdownFile_qustat_2eprotov : 440 -> 428
~ __ZN6QustatD2Ev : 84 -> 72
~ __ZN6QustatD1Ev : 84 -> 72
~ __ZN6QustatD0Ev : 104 -> 92
~ __ZNK6Qustat24SerializeWithCachedSizesEPN6google8protobuf2io17CodedOutputStreamE : 232 -> 220
~ __ZNK6Qustat31SerializeWithCachedSizesToArrayEPh : 288 -> 276
~ __ZN6Qustat9MergeFromERKN6google8protobuf7MessageE : 236 -> 216
~ __ZN6Qustat8CopyFromERKN6google8protobuf7MessageE : 124 -> 112
~ __ZN6Qustat8CopyFromERKS_ : 100 -> 88
~ __ZN11Qustat_helpD2Ev : 96 -> 84
~ __ZN11Qustat_help10SharedDtorEv : 284 -> 272
~ __ZN11Qustat_helpD0Ev : 56 -> 44
~ __ZNK11Qustat_help24SerializeWithCachedSizesEPN6google8protobuf2io17CodedOutputStreamE : 316 -> 304
~ __ZNK11Qustat_help31SerializeWithCachedSizesToArrayEPh : 440 -> 428
~ __ZN11Qustat_help9MergeFromERKN6google8protobuf7MessageE : 236 -> 216
~ __ZN11Qustat_help8CopyFromERKN6google8protobuf7MessageE : 124 -> 112
~ __ZN11Qustat_help8CopyFromERKS_ : 100 -> 88
~ __ZN12Qustat_tableD2Ev : 164 -> 152
~ __ZN12Qustat_tableD0Ev : 56 -> 44
~ __ZN12Qustat_table5ClearEv : 132 -> 120
~ __ZNK12Qustat_table24SerializeWithCachedSizesEPN6google8protobuf2io17CodedOutputStreamE : 332 -> 320
~ __ZNK12Qustat_table31SerializeWithCachedSizesToArrayEPh : 520 -> 508
~ __ZN12Qustat_table9MergeFromERKN6google8protobuf7MessageE : 236 -> 216
~ __ZN12Qustat_table8CopyFromERKN6google8protobuf7MessageE : 124 -> 112
~ __ZN12Qustat_table8CopyFromERKS_ : 100 -> 88
~ __ZN10Qustat_grpD2Ev : 108 -> 96
~ __ZN10Qustat_grp10SharedDtorEv : 236 -> 224
~ __ZN10Qustat_grpD0Ev : 56 -> 44
~ __ZN10Qustat_grp5ClearEv : 284 -> 272
~ __ZNK10Qustat_grp24SerializeWithCachedSizesEPN6google8protobuf2io17CodedOutputStreamE : 316 -> 304
~ __ZNK10Qustat_grp31SerializeWithCachedSizesToArrayEPh : 432 -> 420
~ __ZN10Qustat_grp9MergeFromERKN6google8protobuf7MessageE : 236 -> 216
~ __ZN10Qustat_grp8CopyFromERKN6google8protobuf7MessageE : 124 -> 112
~ __ZN10Qustat_grp8CopyFromERKS_ : 100 -> 88
~ __ZN11Qustat_listD2Ev : 96 -> 84
~ __ZN11Qustat_listD0Ev : 56 -> 44
~ __ZN11Qustat_list5ClearEv : 84 -> 72
~ __ZNK11Qustat_list24SerializeWithCachedSizesEPN6google8protobuf2io17CodedOutputStreamE : 156 -> 144
~ __ZNK11Qustat_list31SerializeWithCachedSizesToArrayEPh : 204 -> 192
~ __ZN11Qustat_list9MergeFromERKN6google8protobuf7MessageE : 236 -> 216
~ __ZN11Qustat_list8CopyFromERKN6google8protobuf7MessageE : 124 -> 112
~ __ZN11Qustat_list8CopyFromERKS_ : 100 -> 88
~ __ZN6google8protobuf8internal20RepeatedPtrFieldBase7DestroyINS0_16RepeatedPtrFieldI11Qustat_helpE11TypeHandlerEEEvv : 156 -> 144
~ __ZL19qustat_help_marshalP13qustat_help_tP11Qustat_help : 448 -> 436
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ __qustat_pub_reset_callback : 172 -> 160
~ __qustat_pub_minmax_reset_callback : 172 -> 160
~ _OUTLINED_FUNCTION_4 : 24 -> 12
~ _OUTLINED_FUNCTION_5 : 24 -> 12
~ _OUTLINED_FUNCTION_8 : 24 -> 12
~ ___starter : 104 -> 92
~ _OUTLINED_FUNCTION_3 : 24 -> 12
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _qustat_msg_close : 84 -> 72
~ _OUTLINED_FUNCTION_5 : 24 -> 12
~ _auth_sign_data : 212 -> 204
~ _round_to_nearest_Xbyte : 308 -> 304
~ _set_required_action : 408 -> 396
~ _set_update_in_progress : 96 -> 84
~ _add_extension_to_affinity : 340 -> 328
~ _cfg_invalid_ASR_alloc_strat_combo_transform : 76 -> 64
~ _free_disk : 428 -> 416
~ __set_sg_vacant : 160 -> 148
~ _set_sg_vacant : 72 -> 60
~ _add_vacant_disks : 424 -> 420
~ _sort_disks : 280 -> 268
~ _validate_cfg_sg_disks : 716 -> 712
~ _validate_cfg_rtios : 724 -> 720
~ _setup_directory_component : 80 -> 68
~ _config_directory_setup : 160 -> 148
~ _validate_stripegroups_transform : 704 -> 696
~ _free_config : 292 -> 280
~ _get_config_template_buffer : 280 -> 268
~ _write_config_file_to_fd : 156 -> 144
~ _autoconvert_config : 260 -> 248
~ _delete_inode_expand_values : 108 -> 96
~ _add_cfg_msg_str : 312 -> 300
~ _destroy_expandable_buffer : 72 -> 60
~ _process_global : 4132 -> 4096
~ _dump_globals : 9488 -> 9476
~ _xml_id : 180 -> 168
~ _handleFirstPass : 216 -> 204
~ _handleSecondPass : 304 -> 292
~ _free_slice_arr : 128 -> 116
~ _call_parser : 208 -> 196
~ _diskDel : 152 -> 140
~ _stripeDel : 264 -> 252
~ _disktypeDel : 152 -> 140
~ _nameAdd : 252 -> 240
~ _nameDel : 152 -> 140
~ _cfg_yyparse : 12092 -> 12936
~ _cfg_yy_delete_buffer : 112 -> 100
~ _cfg_yy_scan_string : 60 -> 48
~ _PanicCheckedWriteLog : 328 -> 304
~ _initialize_roots : 292 -> 280
~ _get_masklen : 140 -> 128
~ _ResetAddrLists : 96 -> 84
~ _save_metadata_filter : 200 -> 188
~ _BuildAddrLists : 3032 -> 3040
~ __enumerate_mac_addrs : 152 -> 140
~ __enumerate_ip_addrs : 164 -> 152
~ _enumerate_auth_ids : 112 -> 100
~ __SnfsCfgEntFree : 104 -> 92
~ _SnfsDirEnumEnd : 96 -> 84
~ _unregister_spurious_wakeup : 160 -> 148
~ ___starter : 104 -> 92
~ _ThreadPriority : 208 -> 200
~ _RecvFromTo : 516 -> 504
~ _FormatSysError : 68 -> 56
~ _CloseLog : 220 -> 208
~ _GetLogFileInfo : 184 -> 172
~ _sn_hash_destroy : 128 -> 116
~ _sn_hash_info : 156 -> 148
~ _name_destroy_key : 60 -> 48
~ _uint64_destroy_key : 60 -> 48
~ _print_hist_file_size : 116 -> 104
~ _print_hist_file_size_icb : 116 -> 104
~ _print_hist_file_blocks : 84 -> 72
~ _print_hist_frag_size : 84 -> 72
~ _print_hist_extent_size : 84 -> 72
~ _print_hist_extents_per_file : 84 -> 72
~ _print_hist_entries_per_dir : 84 -> 72
~ _print_hist_atime : 84 -> 72
~ _print_hist_mtime : 84 -> 72
~ _print_hist_secondary_mtime : 84 -> 72
~ _print_hist_snbtree_height : 84 -> 72
~ _print_hist_snbtree_blocks : 84 -> 72
~ _FsmSetEmbeddedCluster : 176 -> 172
~ _FsmCopyEmbedded : 148 -> 136
~ _cvlog_response : 108 -> 96
~ _cpu_usage : 52 -> 44
~ _percent_cpu_usage : 120 -> 112
~ _percent_cpu_usage2 : 152 -> 144
~ _cvlog_timer : 640 -> 624
~ _qustat_reset : 312 -> 300
~ _qustat_minmax_reset : 232 -> 220
~ _qustat_grp_free : 216 -> 204
~ _qustat_grp_insert : 224 -> 212
~ _qustat_grp_remove : 224 -> 212
~ _qustat_grp_reset : 240 -> 228
~ __qustat_tbl_reset : 712 -> 700
~ _qustat_grp_minmax_reset : 240 -> 228
~ __qustat_tbl_minmax_reset : 164 -> 152
~ _qustat_minmax_tbl_reset : 224 -> 212
~ _qustat_tbl_reset : 224 -> 212
~ _qustat_tbl_free : 216 -> 204
~ __qustat_mod_free : 96 -> 84
~ _qustat_tbl_to_stat : 276 -> 272
~ __qustat_help_hash_free : 192 -> 180
~ _qustat_help_hash_destroy : 240 -> 228
~ _qustat_help_array_free : 240 -> 228
~ _qustat_help_free : 216 -> 204
~ __qustat_archive_free : 84 -> 72
~ __qustat_csv_free : 120 -> 108
~ __qustat_file_close : 88 -> 76
~ _qustat_snprintf_end : 184 -> 172
~ __qustat_snprintf_end : 96 -> 84
+ _OUTLINED_FUNCTION_0
~ _zmq_strerror : 72 -> 60
~ _drb_rele : 92 -> 80
~ _drb_write : 288 -> 284
~ _drb_read : 280 -> 276
~ _ds_add_fd : 240 -> 216
~ _ds_close_fd : 128 -> 116
~ _snbt_remove_record : 1256 -> 1260
~ _qustat_grp_time_snap_set : 232 -> 220
~ _qustat_rec_lvl : 92 -> 100
~ _qustat_rec_sum : 128 -> 136
~ _qustat_rec_time_end : 84 -> 72
```
