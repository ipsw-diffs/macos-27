## libCoreStorage.dylib

> `/usr/lib/libCoreStorage.dylib`

```diff

-572.40.2.0.1
-  __TEXT.__text: 0x61108
-  __TEXT.__gcc_except_tab: 0x1f74
+572.60.3.0.0
+  __TEXT.__text: 0x60e40
+  __TEXT.__gcc_except_tab: 0x1f4c
   __TEXT.__cstring: 0x752f
   __TEXT.__const: 0x7e0
-  __TEXT.__unwind_info: 0x1a40
+  __TEXT.__unwind_info: 0x1a28
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0x78
   __DATA_CONST.__got: 0x0

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libutil.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1434
-  Symbols:   1914
+  Functions: 1432
+  Symbols:   1907
   CStrings:  848
 
Symbols:
+ GCC_except_table121
+ GCC_except_table133
+ GCC_except_table134
+ GCC_except_table260
+ GCC_except_table261
+ GCC_except_table264
+ GCC_except_table277
+ GCC_except_table280
+ GCC_except_table30
+ GCC_except_table87
+ GCC_except_table91
- GCC_except_table123
- GCC_except_table127
- GCC_except_table136
- GCC_except_table137
- GCC_except_table262
- GCC_except_table265
- GCC_except_table272
- GCC_except_table281
- GCC_except_table283
- GCC_except_table80
- GCC_except_table82
- GCC_except_table92
- GCC_except_table95
- __ZN6vectorI13part_seg_infoE5clearEv
- __ZN6vectorI14phy_ext_simpleE6resizeEmRKS0_
- __ZN6vectorI18cpdk_data_move_reqE6resizeEmRKS0_
- _destroy_memalloc_context
- _init_memalloc_context
Functions:
~ __ZN11cache_extra12destroy_poolEv : 200 -> 188
~ __Z26init_enhanced_cache_systemv : 132 -> 116
~ __Z29destroy_enhanced_cache_systemv : 124 -> 116
~ __Z12iterate_flogP3lvgP2txjjR6vectorIyEPFiS0_jjP11pv_flog_entPvES8_ : 448 -> 436
~ __Z8lfs_syncP3txg : 8156 -> 8144
~ __Z15release_all_bufP6vectorI13part_seg_infoE : 212 -> 220
- __ZN6vectorI13part_seg_infoE5clearEv
~ __Z17load_lfs_from_segP3lvgRK13recovery_info : 3844 -> 3796
~ __Z29lv_commit_properties_internalP9cache_entP3lvgP14__CFDictionarybbbbbP2txPK8__CFData : 1676 -> 1636
~ __Z9lv_createP14__CFDictionaryS0_jP3lvgPP9lv_handlePP10lvf_handle : 2644 -> 2656
~ __ZL15pv_reservationsP3lvgPyR6vectorI14pv_reservationE : 556 -> 544
~ __Z13bootstrap_mlvP3lvgP16CoreStorageGroup : 2656 -> 2648
~ __Z11lvg_add_pvsP3lvgP14__CFDictionaryP9__CFArray : 1376 -> 1348
~ __ZN3lvg19lvg_clear_deny_listEv : 60 -> 48
~ __Z12init_contextv : 44 -> 40
~ __Z15destroy_contextv : 32 -> 28
~ __Z12derive_paramP18create_lvg_context : 2996 -> 2968
~ __Z13cs_rsrv_mergeR6vectorI14pv_reservationES2_ : 104 -> 92
~ __ZN15space_allocatornwEm : 4 -> 48
~ __ZN15space_allocatordlEPvm : 28 -> 72
~ __ZN15space_allocator15reserve_blks_pvEjyR6vectorI14pv_reservationE : 256 -> 244
~ __ZN15space_allocator13rollback_blksER6vectorI14pv_reservationE : 176 -> 164
~ __ZN15space_allocator12reserve_blksEjyR6vectorI14pv_reservationE : 1456 -> 1444
~ __Z18decide_new_mlv_extP3lvgyyR6vectorI7mlv_extE : 2308 -> 2292
~ __Z25find_candidate_pv_for_mlvPFvPvjPbS0_ES_jyjPFbS_myES_P6vectorImEPj : 688 -> 656
~ __Z19relocate_phy_extentP3lvgRK12phy_ext_addryP6vectorIP18CoreStorageLogicalEi : 732 -> 720
~ __Z24unpause_all_bg_transformP6vectorIP18CoreStorageLogicalE : 44 -> 8
~ __Z23make_space_for_mlv_growP3lvgR6vectorI7mlv_extE : 588 -> 576
~ __Z13dsd_list_loadP3lvgyP6vectorI8dsd_infoEPS1_IyEPm : 296 -> 260
- _caller_info_init
~ __ZN15move_work_queue5enqueEP9ioreq_entb : 1492 -> 1468
~ __ZN15move_work_queue17dequeue_move_workER19cpdk_data_move_infoPPiPbR6vectorIP9ioreq_entE : 1448 -> 1436
~ __ZN15move_work_queue19cancel_all_requestsEv : 288 -> 232
~ __ZN21compositedisk_manager14sync_move_workEPP2tx : 520 -> 508
~ __ZN21compositedisk_manager17process_move_workEP19cpdk_data_move_infoRPiPc : 4876 -> 4856
~ __ZN21compositedisk_manager15get_ext_lv_infoEP9ioreq_entR6vectorIP12ioreq_ent_exEPb : 376 -> 364
~ __ZN21compositedisk_manager16handle_move_workEPb : 2692 -> 2624
~ __ZN15replacement_alg14redirect_writeERK9ioreq_entR6vectorI14phy_ext_simpleE : 52 -> 8
```
