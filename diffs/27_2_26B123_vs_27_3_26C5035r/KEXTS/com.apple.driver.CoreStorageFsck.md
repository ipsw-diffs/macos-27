## com.apple.driver.CoreStorageFsck

> `com.apple.driver.CoreStorageFsck`

```diff

-572.40.2.0.1
-  __TEXT.__const: 0x70
-  __TEXT.__cstring: 0x1250
-  __TEXT_EXEC.__text: 0x12480
+572.60.3.0.0
+  __TEXT.__const: 0x80
+  __TEXT.__cstring: 0x13c2
+  __TEXT_EXEC.__text: 0x12eec
   __TEXT_EXEC.__auth_stubs: 0x380
   __DATA.__data: 0xd8
   __DATA.__bss: 0x3e5
-  __DATA.__common: 0x30
+  __DATA.__common: 0x28
   __DATA_CONST.__mod_init_func: 0x8
   __DATA_CONST.__mod_term_func: 0x8
   __DATA_CONST.__const: 0xa48
-  __DATA_CONST.__kalloc_type: 0x40
+  __DATA_CONST.__kalloc_var: 0x10e0
+  __DATA_CONST.__kalloc_type: 0x6c0
   __DATA_CONST.__auth_got: 0x1c0
-  __DATA_CONST.__got: 0x50
+  __DATA_CONST.__got: 0x48
   __DATA_CONST.__auth_ptr: 0x10
-  Functions: 201
-  Symbols:   562
-  CStrings:  247
+  Functions: 227
+  Symbols:   623
+  CStrings:  274
 
Symbols:
+ _IOFreeTypeImpl
+ _IOFreeTypeVarImpl
+ _IOMallocTypeImpl
+ _IOMallocTypeVarImpl
+ _OUTLINED_FUNCTION_1
+ _OUTLINED_FUNCTION_2
+ __Z10btree_openI12phy_ext_addrEjPP5btreeIT_EP5cs_csyhi
+ __Z10btree_openI6lv_keyEjPP5btreeIT_EP5cs_csyhi
+ __Z10btree_openIyEjPP5btreeIT_EP5cs_csyhi
+ __ZN6vectorI11cs_fix_itemED1Ev
+ __ZN6vectorIP6cs_bufED1Ev
+ __ZZ10btree_openI12phy_ext_addrEjPP5btreeIT_EP5cs_csyhiE19kalloc_type_view_80
+ __ZZ10btree_openI6lv_keyEjPP5btreeIT_EP5cs_csyhiE19kalloc_type_view_80
+ __ZZ10btree_openIyEjPP5btreeIT_EP5cs_csyhiE19kalloc_type_view_80
+ __ZZ11btree_closeI12phy_ext_addrEjP5btreeIT_EE19kalloc_type_view_92
+ __ZZ11btree_closeI6lv_keyEjP5btreeIT_EE19kalloc_type_view_92
+ __ZZ11btree_closeIyEjP5btreeIT_EE19kalloc_type_view_92
+ __ZZ11buffer_initP5cs_csjE19kalloc_type_view_27
+ __ZZ11discard_gpsP5cs_csP6cs_lvgjE21kalloc_type_view_2563
+ __ZZ12buffer_allocP5cs_csyE19kalloc_type_view_70
+ __ZZ12buffer_allocP5cs_csyE19kalloc_type_view_73
+ __ZZ12fsck_cleanupP5cs_csE20kalloc_type_view_823
+ __ZZ12release_nodeI12phy_ext_addrEvP5btreeIT_EP7bt_nodeE19kalloc_type_view_81
+ __ZZ12release_nodeI6lv_keyEvP5btreeIT_EP7bt_nodeE19kalloc_type_view_81
+ __ZZ12release_nodeIyEvP5btreeIT_EP7bt_nodeE19kalloc_type_view_81
+ __ZZ13device_attachP5cs_csiE20kalloc_type_view_148
+ __ZZ13device_detachP5cs_csiE20kalloc_type_view_164
+ __ZZ13device_detachP5cs_csiE20kalloc_type_view_172
+ __ZZ13verify_volhdrP5cs_csiE20kalloc_type_view_281
+ __ZZ14buffer_destroyP5cs_csE19kalloc_type_view_44
+ __ZZ14buffer_releaseP5cs_csP6cs_bufE20kalloc_type_view_100
+ __ZZ14cs_crypto_initP5cs_pvP13dk_vol_headerE19kalloc_type_view_24
+ __ZZ17cs_crypto_destroyP5cs_pvP13dk_vol_headerE19kalloc_type_view_45
+ __ZZ8get_nodeI12phy_ext_addrEjP5btreeIT_EyPP7bt_nodeE19kalloc_type_view_45
+ __ZZ8get_nodeI12phy_ext_addrEjP5btreeIT_EyPP7bt_nodeE19kalloc_type_view_66
+ __ZZ8get_nodeI6lv_keyEjP5btreeIT_EyPP7bt_nodeE19kalloc_type_view_45
+ __ZZ8get_nodeI6lv_keyEjP5btreeIT_EyPP7bt_nodeE19kalloc_type_view_66
+ __ZZ8get_nodeIyEjP5btreeIT_EyPP7bt_nodeE19kalloc_type_view_45
+ __ZZ8get_nodeIyEjP5btreeIT_EyPP7bt_nodeE19kalloc_type_view_66
+ __ZZ9lvg_setupP5cs_csE20kalloc_type_view_698
+ __ZZL16load_verify_sblkP5cs_csP6cs_lvgE20kalloc_type_view_599
+ __ZZN6vectorI10cs_seginfoE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorI10cs_seginfoE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorI10cs_seginfoED1EvE20kalloc_type_view_203
+ __ZZN6vectorI11cs_fix_itemE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorI11cs_fix_itemE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorI11cs_fix_itemED1EvE20kalloc_type_view_203
+ __ZZN6vectorI11cs_mlv_blksE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorI11cs_mlv_blksE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorI11cs_mlv_blksED1EvE20kalloc_type_view_203
+ __ZZN6vectorI5cs_lvE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorI5cs_lvE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorI5cs_lvED1EvE20kalloc_type_view_203
+ __ZZN6vectorI5cs_pvE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorI5cs_pvE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorI5cs_pvED1EvE20kalloc_type_view_203
+ __ZZN6vectorI6cs_lvfE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorI6cs_lvfE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorI6cs_lvfED1EvE20kalloc_type_view_203
+ __ZZN6vectorI7sut_entE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorI7sut_entE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorI7sut_entED1EvE20kalloc_type_view_203
+ __ZZN6vectorI7vat_entE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorI7vat_entE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorI7vat_entED1EvE20kalloc_type_view_203
+ __ZZN6vectorI8dsd_infoE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorI8dsd_infoE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorI8dsd_infoED1EvE20kalloc_type_view_203
+ __ZZN6vectorIP5cs_pvE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorIP5cs_pvE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorIP5cs_pvED1EvE20kalloc_type_view_203
+ __ZZN6vectorIP6cs_bufE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorIP6cs_bufE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorIP6cs_bufED1EvE20kalloc_type_view_203
+ __ZZN6vectorIPvE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorIPvE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorIPvED1EvE20kalloc_type_view_203
+ __ZZN6vectorIjE7reserveEmE20kalloc_type_view_329
+ __ZZN6vectorIjE7reserveEmE20kalloc_type_view_332
+ __ZZN6vectorIjED1EvE20kalloc_type_view_203
- _OSFree
- _OSMalloc
- _OSMalloc_Tagalloc
- _OSMalloc_Tagfree
- __Z10cs_memfreePPvm
- __Z11cs_memallocPPvm
- __Z14cs_memory_initv
- __Z17cs_memory_destroyv
- __ZN6vectorI10cs_seginfoE6resizeEmRKS0_
- __ZN6vectorI11cs_fix_itemE7reserveEm
- __ZN6vectorI5cs_lvE7reserveEm
- __ZN6vectorI5cs_pvE7reserveEm
- __ZN6vectorI6cs_lvfE7reserveEm
- __ZN6vectorI7sut_entE6resizeEmRKS0_
- __ZN6vectorI8dsd_infoE7reserveEm
- __ZN6vectorIPvE7reserveEm
- __ZN6vectorIjE6resizeEmRKj
- _fsck_mem_tag
- _mem_alloc_tag
CStrings:
+ "1"
+ "11112221"
+ "111222112"
+ "112222222222211122212121212"
+ "12122"
+ "122"
+ "2211"
+ "2221122221"
+ "22222212221"
+ "2222222112221"
+ "bt_buf_impl.h"
+ "buffer.cpp"
+ "errors.cpp"
+ "fsck_cs.cpp"
+ "io.cpp"
+ "repair.cpp"
+ "site.blk_usage_tree"
+ "site.bt_node_t"
+ "site.cs_buf_t"
+ "site.cscrypto"
+ "site.dk_mlv_superblock_t"
+ "site.dk_vol_header_t"
+ "site.struct btree<bt_key_t>"
+ "site.typeof(*cs->cs_bufcache.buf_hash)"
+ "site.uint8_t"
+ "site.value_type"
+ "util.cpp"
+ "verify.cpp"
- "corestorage-fsck-kext"
```
