## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t6050.RELEASE.restore.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__DATA.__auth_ptr`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__DATA.__thread_vars`
- `__PDATA.__auth_ptr`
- `__PDATA.__mod_init_func`
- `__PDATA.__data`
- `__PDATA.__shared_cache`

```diff

-1777.40.24.501.1
-  __TEXT.__text: 0x5d7030
+1777.40.28.0.2
+  __TEXT.__text: 0x5d79d8
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0x4f3a1
-  __TEXT.__const: 0x120d14
+  __TEXT.__cstring: 0x4f781
+  __TEXT.__const: 0x120d24
   __TEXT.__swift5_typeref: 0x132aa
   __TEXT.__swift5_reflstr: 0x12308
   __TEXT.__swift5_assocty: 0x7ba8

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0xb0
-  __TEXT.__eh_frame: 0x3391c
+  __TEXT.__eh_frame: 0x3389c
   __DATA.__TIGHTBEAM_VT: 0x720
   __DATA.__TIGHTBEAM: 0x1d8
-  __DATA.__const: 0x3b818
+  __DATA.__const: 0x3b828
   __DATA.__data: 0x16d20
   __DATA.__mod_init_func: 0x40
   __DATA.__ENDPOINTS: 0x1a744

   __DATA.__bss: 0xe540
   __DATA.__common: 0x6ca
   __PDATA.__auth_ptr: 0x280
-  __PDATA.__const: 0x6800
+  __PDATA.__const: 0x6810
   __PDATA.__objc_imageinfo: 0x8
   __PDATA.__mod_init_func: 0x18
   __PDATA.__data: 0x2af0
   __PDATA.__ENDPOINTS: 0x838
   __PDATA.__shared_cache: 0x70
-  __PDATA.__bss: 0xba48
+  __PDATA.__bss: 0xbae8
   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 22622
+  Functions: 22627
   Symbols:   1
-  CStrings:  7226
+  CStrings:  7242
 
CStrings:
+ "%s(%zu): failed to delete delta scratch RO span slot"
+ "%s(%zu): failed to delete delta scratch RO temp cap"
+ "%s(%zu): failed to map frame into delta scratch RO span"
+ "B16@?0^{vas_core_span={?=CQQCCCCC^vQ}iC[3C]{?=^?^?^?}^vQQ^{vas_core_vas}^{vas_core_span}^{vas_core_span}Q^{vas_segment}{spanmap_struct=b2b4b22b36}{_liblibc_mtx=[16C]}B{?=^{vas_core_span}^^{vas_core_span}}{spanmap_struct=b2b4b22b36}}8"
+ "BUG IN LIBTRACE: log payload "
+ "Log payload exceeds "
+ "Unexpected L4_Error: %s(%zu) err='L4_Cap_Delete(scratch->ro_span_slot)'"
+ "Unexpected L4_Error: %s(%zu) err='L4_Cap_Delete(scratch->ro_temp_slot)'"
+ "Unexpected L4_Error: %s(%zu) err='_map_this_frame_readonly(scratch->ro_span, (uintptr_t)ro_words, scratch->ro_temp_slot)'"
+ "[LogServer] error: "
+ "[VAS abort in function %s at line %d] [%s] could not allocate fixup span for fault handler\n"
+ "[VAS abort in function %s at line %d] [true: (%s)] Could not depopulate temp span (drop): %s (0x%04hx)\n\n"
+ "[VAS abort in function %s at line %d] [true: (%s)] _delta_page_against_original returned unexpected result(%p)\n"
+ "])\n  deviceStateDisplayWake: allowance="
+ "_delta_page_against_original"
+ "_os_log_payload_size(olp), OS_LOG_EXCLAVES_PAYLOAD_MAX"
+ "applyFixups: rebase failed for %#lx (region %zd)"
+ "applyFixups: region %zd has NULL fixup_metadata_pointer"
+ "delta_output != fault->write_buffer"
+ "olp->olp_tpb.tp_size, OS_LOG_EXCLAVES_TRACEPOINT_HDR_SIZE"
+ "vas_return_code(drop_depop) != VAS_SUCCESS"
- "B16@?0^{vas_core_span={?=CQQCCCCC^vQ}iC[3C]{?=^?^?}^vQQ^{vas_core_vas}^{vas_core_span}^{vas_core_span}Q^{vas_segment}{spanmap_struct=b2b4b22b36}{_liblibc_mtx=[16C]}B{?=^{vas_core_span}^^{vas_core_span}}{spanmap_struct=b2b4b22b36}}8"
- "BUG IN LIBTRACE: Received a BATCH_ERROR while creating a LogBatch"
- "])\n  medinaStateDisplayWake: allowance="
- "_os_log_payload_size(olp), OS_LOG_PAYLOAD_HARD_MAX_SIZE"
- "olp->olp_tpb.tp_size, OS_LOG_PAYLOAD_HDR_SIZE"
```
