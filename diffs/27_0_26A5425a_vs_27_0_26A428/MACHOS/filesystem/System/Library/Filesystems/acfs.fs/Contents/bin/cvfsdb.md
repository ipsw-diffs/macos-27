## cvfsdb

> `/System/Library/Filesystems/acfs.fs/Contents/bin/cvfsdb`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0x77bd4
+  __TEXT.__text: 0x77770
   __TEXT.__auth_stubs: 0xff0
   __TEXT.__cstring: 0x1f4f9
   __TEXT.__const: 0xd618
-  __TEXT.__unwind_info: 0x1250
+  __TEXT.__unwind_info: 0x17f8
   __DATA_CONST.__const: 0x660
   __DATA_CONST.__cfstring: 0x460
   __DATA_CONST.__auth_got: 0x7f8

   - /usr/lib/libedit.3.dylib
   - /usr/lib/libncurses.5.4.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 1673
+  Functions: 1674
   Symbols:   2572
   CStrings:  3872
 
Functions:
~ _cvfsdb_WriteLog : 252 -> 240
~ _usage : 120 -> 108
~ _yyparse : 4812 -> 4820
~ _yy_delete_buffer : 112 -> 100
~ _yy_scan_string : 60 -> 48
~ _cvfsdb_stripegroup : 192 -> 180
~ _SaveConfig : 192 -> 180
~ _cvfsdb_print_max_inodes : 324 -> 312
~ _cvfsdb_dumpbtree : 156 -> 144
~ _ShowIel : 316 -> 304
~ _ShowRawBlock : 1180 -> 1168
~ _ShowInode : 604 -> 580
~ _ShowOnDisk : 672 -> 660
~ _ShowFreei : 136 -> 124
~ _ShowAlloc : 1348 -> 1320
~ _ShowSg : 1236 -> 1224
~ _ShowNtsdFull : 488 -> 476
~ _Help : 1204 -> 1192
~ _Sb_PeekPoke_Help : 708 -> 696
~ _Ondisk_PeekPoke_Help : 1028 -> 1016
~ _CvfsDbDefaultInput : 204 -> 192
~ _PeekPoke : 768 -> 744
~ _Poke : 176 -> 164
~ _PokeSb : 168 -> 156
~ _PokeInode : 168 -> 156
~ _cvfsdb_ls : 180 -> 168
~ _db_finish : 132 -> 120
~ _print_mcan_bottom : 184 -> 172
~ _binode_print : 228 -> 204
~ _Journal_dump : 540 -> 528
~ _icbPrint : 1296 -> 1284
~ _print_ntsec : 812 -> 800
~ _print_fsid_flag_names : 216 -> 204
~ _snbtree_payload_print : 1712 -> 1640
~ ___starter : 104 -> 92
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
~ _FsmPMGetDisks : 1388 -> 1384
~ _FsmGetPartitionNativeKeys : 416 -> 412
~ _FsmStartIoTest : 352 -> 344
~ ___starter : 104 -> 92
~ _sb_rwlock : 476 -> 452
~ _sb_rwunlock : 188 -> 164
~ _journal_init : 312 -> 300
~ _Journal_zero : 436 -> 432
~ _Journal_clear : 60 -> 48
~ _Journal_recover : 6600 -> 6472
~ _jrnrec_trans_free : 232 -> 220
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
~ _binode_get_segp : 100 -> 104
~ _binode_get_bia : 496 -> 500
~ _binode_set_bia : 340 -> 344
~ __binode_check : 260 -> 236
~ _extract_binode_flbt_attr : 168 -> 172
~ _binode_copy_core : 604 -> 608
~ _binode_incore_to_ondisk : 592 -> 596
~ _auth_sign_data : 212 -> 204
~ _PanicCheckedWriteLog : 328 -> 304
~ _initialize_roots : 292 -> 280
~ _get_masklen : 140 -> 128
~ _ResetAddrLists : 96 -> 84
~ _save_metadata_filter : 200 -> 188
~ _BuildAddrLists : 3032 -> 3040
~ __enumerate_mac_addrs : 152 -> 140
~ __enumerate_ip_addrs : 164 -> 152
~ _enumerate_auth_ids : 112 -> 100
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
~ _FsmSetEmbeddedCluster : 176 -> 172
~ _FsmCopyEmbedded : 148 -> 136
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
+ _OUTLINED_FUNCTION_0
~ _snbt_remove_record : 1256 -> 1260
~ _qustat_rec_lvl : 92 -> 100
~ _qustat_rec_sum : 128 -> 136
~ _qustat_rec_time_end : 84 -> 72
```
