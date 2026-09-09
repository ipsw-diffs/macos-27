## MTLAssetUpgraderD

> `/usr/libexec/MTLAssetUpgraderD`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 382.5.3.0.0
-  __TEXT.__text: 0x1867c
+  __TEXT.__text: 0x18514
   __TEXT.__auth_stubs: 0x750
   __TEXT.__objc_stubs: 0x7c0
   __TEXT.__gcc_except_tab: 0xf84

   __TEXT.__oslogstring: 0xadc
   __TEXT.__cstring: 0x8ea
   __TEXT.__objc_methname: 0x4e3
-  __TEXT.__unwind_info: 0x5b8
+  __TEXT.__unwind_info: 0x708
   __DATA_CONST.__const: 0x238
   __DATA_CONST.__cfstring: 0x1c0
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ __ZNSt3__112__hash_tableINS_17__hash_value_typeINS_5tupleIJNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjjEEEjEENS_22__unordered_map_hasherIS9_NS_4pairIKS9_jEE8key_hashNS_8equal_toIS9_EEEENS_21__unordered_map_equalIS9_SE_SH_SF_EENS6_ISE_EEE17__deallocate_nodeB9nqe220106EPNS_11__hash_nodeISA_PvEE : 68 -> 56
~ __ZNSt3__16vectorINS_5tupleIJNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjjEEENS5_IS8_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeINS_5tupleIJNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjjEEEjEENS_22__unordered_map_hasherIS9_NS_4pairIKS9_jEE8key_hashNS_8equal_toIS9_EEEENS_21__unordered_map_equalIS9_SE_SH_SF_EENS6_ISE_EEE16__emplace_uniqueB9nqe220106IJRKNS_21piecewise_construct_tENS2_IJOS9_EEENS2_IJEEEEEENSC_INS_15__hash_iteratorIPNS_11__hash_nodeISA_PvEEEEbEEDpOT_ENKUlRSD_SQ_OSS_OST_E_clES14_SQ_S15_S16_ : 724 -> 720
~ __ZNSt3__112__hash_tableINS_17__hash_value_typeINS_5tupleIJNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjjEEEjEENS_22__unordered_map_hasherIS9_NS_4pairIKS9_jEE8key_hashNS_8equal_toIS9_EEEENS_21__unordered_map_equalIS9_SE_SH_SF_EENS6_ISE_EEE8__rehashILb1EEEvm : 228 -> 212
~ __ZNSt3__122__hash_node_destructorINS_9allocatorINS_11__hash_nodeINS_17__hash_value_typeINS_5tupleIJNS_12basic_stringIcNS_11char_traitsIcEENS1_IcEEEEjjEEEjEEPvEEEEEclB9nqe220106EPSD_ : 100 -> 88
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 68 -> 56
~ __ZNSt3__16vectorINS_4pairINS_5tupleIJNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjjEEEjEENS6_ISA_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERZN17MTLArchiveUsageDB18getPrioritizedListEvE3$_0PNS_4pairINS_5tupleIJNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjjEEEjEELb0EEEvT1_SG_T0_NS_15iterator_traitsISG_E15difference_typeEb : 3268 -> 3244
~ __ZNSt3__16vectorINS_5tupleIJNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjjEEENS5_IS8_EEE24__emplace_back_slow_pathIJS8_EEEPS8_DpOT_ : 248 -> 244
~ ____ZN17MTLAssetUpgraderD26listPrioritizedAppLaunchesEv_block_invoke_2 : 316 -> 304
~ __ZN17MTLAssetUpgraderD10findDeviceEjj : 432 -> 420
~ __ZN17MTLAssetUpgraderD17getCacheDirectoryENS_9CacheTypeERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE : 1184 -> 1172
~ __ZN17RecompilationWork9serializeEv : 176 -> 164
~ __ZN17MTLAssetUpgraderD21getAppBundleDirectoryERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE : 244 -> 232
~ __ZN17MTLAssetUpgraderD14resolveFileURLEP5NSURL : 236 -> 224
~ __ZN17MTLAssetUpgraderD19generateArchiveNameERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE : 420 -> 408
~ __ZN17RecompilationWorkD0Ev : 56 -> 44
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE24__emplace_back_slow_pathIJS6_EEEPS6_DpOT_ : 264 -> 260
~ _OUTLINED_FUNCTION_4 : 24 -> 12
~ _mdb_txn_renew0 : 1012 -> 1016
~ _mdb_txn_end : 584 -> 576
~ __mdb_txn_abort : 80 -> 68
~ _mdb_cursor_init : 176 -> 180
~ _mdb_cursor_next : 612 -> 600
~ __mdb_cursor_del : 804 -> 792
~ _mdb_freelist_save : 1416 -> 1420
~ _mdb_page_flush : 940 -> 944
~ _mdb_env_write_meta : 516 -> 512
~ _mdb_page_copy : 144 -> 132
~ _mdb_find_oldest : 80 -> 76
~ _mdb_update_key : 368 -> 356
~ _mdb_page_search_lowest : 204 -> 192
~ _OUTLINED_FUNCTION_5 : 36 -> 24
~ _OUTLINED_FUNCTION_7 : 32 -> 20
~ _mdb_env_set_mapsize : 176 -> 172
~ _mdb_env_open : 760 -> 764
~ _mdb_env_close : 92 -> 80
~ _mdb_env_copyfd0 : 416 -> 408
~ _mdb_reader_list : 424 -> 412
```
