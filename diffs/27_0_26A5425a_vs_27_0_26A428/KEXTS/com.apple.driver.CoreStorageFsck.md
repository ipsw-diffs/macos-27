## com.apple.driver.CoreStorageFsck

> `com.apple.driver.CoreStorageFsck`

```diff

 572.0.0.0.0
   __TEXT.__const: 0x70
   __TEXT.__cstring: 0x1250
-  __TEXT_EXEC.__text: 0x129a8
+  __TEXT_EXEC.__text: 0x12bbc
   __TEXT_EXEC.__auth_stubs: 0x380
   __DATA.__data: 0xd8
   __DATA.__bss: 0x3e5
Functions:
~ __Z11buffer_initP5cs_csj : 120 -> 124
~ __Z14buffer_destroyP5cs_cs : 88 -> 92
~ __Z14buffer_releaseP5cs_csP6cs_buf : 456 -> 460
~ __Z12buffer_allocP5cs_csy : 632 -> 636
~ __Z12buffer_validP5cs_csP6cs_bufjyj : 124 -> 128
~ __Z14cs_crypto_initP5cs_pvP13dk_vol_header : 204 -> 208
~ __Z17cs_crypto_decryptP5cs_pvPKvmyPv : 200 -> 204
~ __Z17cs_crypto_encryptP5cs_pvPKvmyPv : 200 -> 204
~ __Z14errors_destroyP5cs_cs : 84 -> 88
~ __Z11scope_enterP5cs_csPKcz : 180 -> 184
~ __Z11scope_leaveP5cs_cs : 68 -> 72
~ __Z11scope_errorP5cs_csjPKcz : 84 -> 88
~ __ZL15error_constructP11fsck_errorsPKcPcj : 488 -> 492
~ __Z15scope_downgradeP5cs_csjPKcz : 128 -> 132
~ __Z10scope_exitP5cs_csjPKcz : 132 -> 136
~ __Z15scope_err_stateP5cs_csP13fsck_err_item : 240 -> 244
~ __Z16older_cs_versionP5cs_pvP13dk_vol_headerj : 336 -> 340
~ __Z9verify_vhP5cs_csP13dk_vol_headerj : 484 -> 488
~ __Z13verify_volhdrP5cs_csi : 1748 -> 1756
~ __ZL16prompt_repair_vhP5cs_csjP5cs_pvyb : 280 -> 284
~ __Z9verify_dlP5cs_csP13dk_disk_labeljb : 804 -> 808
~ __Z17verify_disklabelsP5cs_csi : 1708 -> 1712
~ __ZL15read_full_labelP5cs_pvymPP13dk_disk_label : 104 -> 108
~ __Z8mark_mlvP5cs_cs : 572 -> 576
~ __Z9lvg_setupP5cs_cs : 2044 -> 2048
~ __Z9parse_mlvP5cs_cs : 956 -> 960
~ __Z12fsck_cleanupP5cs_cs : 148 -> 152
~ __Z7fsck_csP5cs_csPPKc : 2136 -> 2140
~ __ZN6vectorI11cs_fix_itemE9push_backERKS0_ : 164 -> 168
~ __Z11device_openP5cs_pvbPb : 192 -> 196
~ __Z13device_attachP5cs_csi : 1044 -> 1048
~ __Z13device_detachP5cs_csi : 2144 -> 2148
~ __Z14device_read_pvP5cs_pvymPv : 500 -> 504
~ __Z15device_write_pvP5cs_pvymPKv : 592 -> 596
~ __Z8read_mlvP5cs_pvymPvy : 424 -> 428
~ __Z9write_mlvP5cs_pvymPKvy : 448 -> 452
~ __ZN15CoreStorageFsck9MetaClassC1Ev : 72 -> 76
~ __ZN15CoreStorageFsckC2EPK11OSMetaClass : 72 -> 76
~ __ZN5cs_csC1Ev : 252 -> 256
~ __ZN15CoreStorageFsckC1EPK11OSMetaClass : 72 -> 76
~ __ZN15CoreStorageFsckD2Ev : 84 -> 88
~ __ZN5cs_csD1Ev : 556 -> 560
~ __ZN15CoreStorageFsckD1Ev : 84 -> 88
~ __ZN15CoreStorageFsckD0Ev : 104 -> 108
~ __ZN15CoreStorageFsck9MetaClassC2Ev : 72 -> 76
~ __ZNK15CoreStorageFsck9MetaClass5allocEv : 52 -> 56
~ __ZN15CoreStorageFsckC2Ev : 92 -> 96
~ _fsck_module_start : 28 -> 32
~ _fsck_module_stop : 28 -> 32
~ __ZN15CoreStorageFsck4initEP12OSDictionary : 104 -> 108
~ __ZN15CoreStorageFsck5probeEP9IOServicePi : 992 -> 996
~ __ZL12set_pv_stateP16CoreStorageAdminP5cs_pvi : 228 -> 232
~ __ZL15dump_errors_logP5cs_cs : 176 -> 180
~ _GLOBAL__sub_I_kextmode.cpp : 80 -> 84
~ __Z14cs_memory_initv : 44 -> 48
~ __Z11cs_memallocPPvm : 76 -> 80
~ __Z10cs_memfreePPvm : 56 -> 60
~ __Z10cs_reffreePPv : 72 -> 76
~ __Z11repair_initP5cs_cs : 100 -> 104
~ __Z13mlv_scrubbingP5cs_csb : 852 -> 856
~ __Z12repair_applyP5cs_cs : 800 -> 804
~ __Z14mlv_used_stateP6cs_gpsm : 152 -> 156
~ __Z19try_mlv_mirror_copyP5cs_csyjPvPK14mlv_blk_verify : 160 -> 164
~ __ZL22verify_mlv_mirror_copyP5cs_csPvPK14mlv_blk_verify : 204 -> 208
~ __Z21read_verify_mlv_blockP5cs_csybPK14mlv_blk_verifyPP6cs_buf : 432 -> 436
~ __ZL14mlv_used_laddrP6cs_gpsyPh : 212 -> 216
~ __Z14new_usage_nodeyyjP10usage_desc : 168 -> 172
~ __Z14mark_blk_usageP5cs_csP5cs_pvP14blk_usage_treeyyjP10usage_desc : 752 -> 756
~ __ZL14usage_conflictP5cs_csP5cs_pvP14blk_usage_treeyyjP10usage_descP9blk_usage : 276 -> 280
~ __Z15reset_blk_usageP5cs_csj : 2372 -> 2376
~ __Z7lvg2strP5cs_csbb : 424 -> 428
~ __Z8uuid2strPh : 164 -> 168
~ __Z10status2strjb : 1332 -> 1336
~ __Z10extent2strPKcRK12phy_ext_addry : 88 -> 92
~ __Z12uuid_extractP12OSDictionaryPKcPh : 168 -> 172
~ __Z11xml_to_dictPKcmmiPP12OSDictionary : 432 -> 436
~ __Z15assemble_pv_setP5cs_cs : 1108 -> 1112
~ __Z11kill_tx_hdrP5cs_csyjb : 684 -> 688
~ __ZN6vectorI11cs_fix_itemE9push_backERKS0_ : 284 -> 288
~ __Z12verify_cksum9cksum_algPKvmPh : 212 -> 216
~ __Z13verify_blkhdrPK15metadata_headerthhyyyjj : 332 -> 336
~ __Z13verify_cryptoiiPh : 140 -> 144
~ __Z16load_verify_flogP5cs_cs : 2284 -> 2288
~ __Z16load_partial_gpsP5cs_csP6cs_lvgPK13recovery_infoPyPS3_ : 1248 -> 1252
~ __ZL8load_gpsP5cs_csP6cs_lvgPK13recovery_infoPyPS3_b : 1316 -> 1320
~ __ZL10unload_gpsP5cs_csP6cs_lvgjm : 364 -> 368
~ __ZL10verify_gpsP5cs_csP6cs_lvgb : 1908 -> 1912
~ __Z17load_chkpoint_gpsP5cs_csP6cs_lvgPK13recovery_infoPyPS3_ : 2084 -> 2088
~ __Z11discard_gpsP5cs_csP6cs_lvgj : 756 -> 760
~ __Z21verify_gps_collectionP5cs_cs : 2392 -> 2396
~ __ZL19verify_sblk_pendingP5cs_csP6cs_lvg : 508 -> 512
~ __ZL16verify_lv_btreesP5cs_csP6cs_lvg : 2992 -> 2996
~ __ZL16verify_blk_usageP5cs_cs : 1204 -> 1208
~ __ZL17verify_dummy_treeP5cs_csP6cs_lvg : 228 -> 232
~ __ZL18verify_live_vaddrsP5cs_csP6cs_lvg : 512 -> 516
~ __Z20verify_live_segmentsP5cs_cs : 616 -> 620
~ __ZL21blk_usage_tree_removeP14blk_usage_treeP9blk_usage : 1768 -> 1772
~ __ZL22blk_usage_tree_psearchP14blk_usage_treeP9blk_usage : 132 -> 136
~ __ZL21blk_usage_tree_insertP14blk_usage_treeP9blk_usage : 528 -> 532
~ __ZL22blk_usage_tree_nsearchP14blk_usage_treeP9blk_usage : 132 -> 136
~ __ZL13verify_seghdrP5cs_csP15metadata_headerPv : 660 -> 664
~ __ZN6vectorI10cs_seginfoE6resizeEmRKS0_ : 480 -> 484
~ __ZN6vectorIP6cs_bufE6resizeEmRKS1_ : 224 -> 228
~ __ZN6vectorIPvE9push_backERKS0_ : 140 -> 144
~ __ZL14vat_allocationP6cs_lvgyb : 588 -> 592
~ __ZN6vectorI7vat_entE6resizeEmRKS0_ : 248 -> 252
~ __ZN6vectorI7sut_entE6resizeEmRKS0_ : 240 -> 244
~ __ZN6vectorIjE6resizeEmRKj : 224 -> 228
~ __Z10bt_iterateIyEjP5btreeIT_ES1_PFjS1_PvmP5cs_csS4_ES4_mS4_ : 132 -> 136
~ __ZL11cb_lvf_walkyPvmP5cs_csS_ : 784 -> 788
~ __Z8get_nodeIyEjP5btreeIT_EyPP7bt_node : 332 -> 336
~ __ZL19bt_iterate_internalIyEjP5btreeIT_EP7bt_nodeS1_PFjS1_PvmP5cs_csS6_EPcmS6_P12btree_sortedIS1_E : 696 -> 700
~ __ZL18load_sblk_overflowP5cs_csPPvS1_mmmyh : 464 -> 468
~ __ZN6vectorI6cs_lvfE9push_backERKS0_ : 176 -> 180
~ __ZL16lvf_keys_presentP5cs_csP6cs_lvf : 428 -> 432
~ __ZL10cb_lv_walkyPvmP5cs_csS_ : 864 -> 868
~ __Z10bt_iterateI6lv_keyEjP5btreeIT_ES2_PFjS2_PvmP5cs_csS5_ES5_mS5_ : 140 -> 144
~ __ZL12cb_layout_lv6lv_keyPvmP5cs_csS0_ : 616 -> 620
~ __ZL12layout_paramP15layout_cb_paramP6cs_lvfP5cs_lv : 236 -> 240
~ __ZL19bt_iterate_internalI6lv_keyEjP5btreeIT_EP7bt_nodeS2_PFjS2_PvmP5cs_csS7_EPcmS7_P12btree_sortedIS2_E : 812 -> 816
~ __ZL19expected_propertiesP5cs_csP12OSDictionaryb : 140 -> 144
~ __Z10bt_iterateI12phy_ext_addrEjP5btreeIT_ES2_PFjS2_PvmP5cs_csS5_ES5_mS5_ : 132 -> 136
~ __ZL12cb_layout_uu12phy_ext_addrPvmP5cs_csS0_ : 680 -> 684
~ __ZL16extract_dsditemsR6vectorI8dsd_infoEPS0_iPy : 264 -> 268
~ __ZL19bt_iterate_internalI12phy_ext_addrEjP5btreeIT_EP7bt_nodeS2_PFjS2_PvmP5cs_csS7_EPcmS7_P12btree_sortedIS2_E : 732 -> 736
~ __ZL15cb_backref_walk12phy_ext_addrPvmP5cs_csS0_ : 876 -> 880
~ __ZL13cb_dummy_treeyPvmP5cs_csS_ : 52 -> 56
~ _Z17cs_crypto_decryptP5cs_pvPKvmyPv.cold.1 : 24 -> 28
~ _Z17cs_crypto_encryptP5cs_pvPKvmyPv.cold.1 : 24 -> 28
~ _Z11cs_memallocPPvm.cold.1 : 44 -> 48
~ _ZL19bt_iterate_internalIyEjP5btreeIT_EP7bt_nodeS1_PFjS1_PvmP5cs_csS6_EPcmS6_P12btree_sortedIS1_E.cold.1 : 24 -> 28
~ _ZL19bt_iterate_internalIyEjP5btreeIT_EP7bt_nodeS1_PFjS1_PvmP5cs_csS6_EPcmS6_P12btree_sortedIS1_E.cold.2 : 24 -> 28
```
