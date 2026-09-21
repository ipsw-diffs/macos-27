## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8142.RELEASE.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
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
-  __TEXT.__text: 0xd5b8a8
+1777.40.28.0.2
+  __TEXT.__text: 0xd5f904
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0xa4581
-  __TEXT.__const: 0x19c9a4
-  __TEXT.__swift5_typeref: 0x2a346
-  __TEXT.__swift5_reflstr: 0x3d138
+  __TEXT.__cstring: 0xa4a61
+  __TEXT.__const: 0x19cc54
+  __TEXT.__swift5_typeref: 0x2a366
+  __TEXT.__swift5_reflstr: 0x3d268
   __TEXT.__swift5_assocty: 0xea50
-  __TEXT.__swift5_fieldmd: 0x5d558
-  __TEXT.__constg_swiftt: 0x62624
+  __TEXT.__swift5_fieldmd: 0x5d674
+  __TEXT.__constg_swiftt: 0x626f0
   __TEXT.__swift5_protos: 0x121c
-  __TEXT.__swift5_proto: 0x9be8
-  __TEXT.__swift5_types: 0x5f98
+  __TEXT.__swift5_proto: 0x9c10
+  __TEXT.__swift5_types: 0x5fac
   __TEXT.__swift5_types2: 0xc0
   __TEXT.__swift5_builtin: 0x2760
   __TEXT.__swift5_capture: 0x3538
   __TEXT.__objc_methtype: 0x2d6
   __TEXT.__swift5_mpenum: 0xc34
-  __TEXT.__swift_as_entry: 0x1640
-  __TEXT.__swift_as_ret: 0x1850
-  __TEXT.__swift_as_cont: 0x2ee4
+  __TEXT.__swift_as_entry: 0x1658
+  __TEXT.__swift_as_ret: 0x1870
+  __TEXT.__swift_as_cont: 0x2f3c
   __TEXT.__oslogstring: 0x6cc7
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constructor: 0x0

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x128
-  __TEXT.__eh_frame: 0x76804
+  __TEXT.__eh_frame: 0x76cf4
   __DATA.__TIGHTBEAM_VT: 0x1200
   __DATA.__TIGHTBEAM: 0x4a8
-  __DATA.__const: 0xe3358
-  __DATA.__data: 0x4f6b8
+  __DATA.__const: 0xe3630
+  __DATA.__data: 0x4f6e0
   __DATA.__mod_init_func: 0x40
   __DATA.__ENDPOINTS: 0x1bbd0
   __DATA.__auth_ptr: 0x7570

   __DATA.__bss: 0x24aa0
   __DATA.__common: 0x2961
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
-  Functions: 47603
+  Functions: 47652
   Symbols:   1
-  CStrings:  15118
+  CStrings:  15137
 
CStrings:
+ " opted into prefers-waiting-through-sleep; option accepted but not yet implemented"
+ "%s(%zu): failed to delete delta scratch RO span slot"
+ "%s(%zu): failed to delete delta scratch RO temp cap"
+ "%s(%zu): failed to map frame into delta scratch RO span"
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Fri Sep 11 23:21:59 PDT 2026; root:AppleImage4_exclavecore-374~18483/ExclaveImage4/RELEASE_ARM64E"
+ "ANEExclave version: ANEExclave_exclavecore-13.101.1"
+ "B16@?0^{vas_core_span={?=CQQCCCCC^vQ}iC[3C]{?=^?^?^?}^vQQ^{vas_core_vas}^{vas_core_span}^{vas_core_span}Q^{vas_segment}{spanmap_struct=b2b4b22b36}{_liblibc_mtx=[16C]}B{?=^{vas_core_span}^^{vas_core_span}}{spanmap_struct=b2b4b22b36}}8"
+ "BUG IN LIBTRACE: log payload "
+ "Build Date: Fri Sep 11 22:16:20 PDT 2026"
+ "Deferred power on for ANEEngine from "
+ "ExclaveOS Image4 Framework Version 7.0.0: Fri Sep 11 23:21:59 PDT 2026; root:AppleImage4_exclavecore-374~18483/ExclaveImage4/RELEASE_ARM64E"
+ "Log payload exceeds "
+ "Resuming ANEEngine to service existing clients from "
+ "Tue Sep 15 13:13:25 PDT 2026"
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
+ "clientSessionHint(client:model:args:) Cycles: "
+ "clientSetPowerHint(client:model:keepPowered:) Cycles: "
+ "delta_output != fault->write_buffer"
+ "olp->olp_tpb.tp_size, OS_LOG_EXCLAVES_TRACEPOINT_HDR_SIZE"
+ "vas_return_code(drop_depop) != VAS_SUCCESS"
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Thu Sep  3 23:08:07 PDT 2026; root:AppleImage4_exclavecore-374~18265/ExclaveImage4/RELEASE_ARM64E"
- "ANEExclave version: ANEExclave_exclavecore-13.100.8"
- "B16@?0^{vas_core_span={?=CQQCCCCC^vQ}iC[3C]{?=^?^?}^vQQ^{vas_core_vas}^{vas_core_span}^{vas_core_span}Q^{vas_segment}{spanmap_struct=b2b4b22b36}{_liblibc_mtx=[16C]}B{?=^{vas_core_span}^^{vas_core_span}}{spanmap_struct=b2b4b22b36}}8"
- "BUG IN LIBTRACE: Received a BATCH_ERROR while creating a LogBatch"
- "Build Date: Thu Sep  3 22:41:50 PDT 2026"
- "Deferred power on for ANEEngine"
- "ExclaveOS Image4 Framework Version 7.0.0: Thu Sep  3 23:08:07 PDT 2026; root:AppleImage4_exclavecore-374~18265/ExclaveImage4/RELEASE_ARM64E"
- "Fri Sep 11 21:40:44 PDT 2026"
- "Resuming ANEEngine to service existing clients"
- "])\n  medinaStateDisplayWake: allowance="
- "_os_log_payload_size(olp), OS_LOG_PAYLOAD_HARD_MAX_SIZE"
- "olp->olp_tpb.tp_size, OS_LOG_PAYLOAD_HDR_SIZE"
```
