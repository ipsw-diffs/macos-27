## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8152.RELEASE.im4p/exclave_sharedcache`

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
-  __TEXT.__text: 0xd00bc0
+1777.40.28.0.2
+  __TEXT.__text: 0xd04bec
   __TEXT.__lcxx_override: 0xd0
-  __TEXT.__cstring: 0xa1961
-  __TEXT.__const: 0x19a5e4
-  __TEXT.__swift5_typeref: 0x28ac0
-  __TEXT.__swift5_reflstr: 0x3aaf8
+  __TEXT.__cstring: 0xa1e41
+  __TEXT.__const: 0x19a894
+  __TEXT.__swift5_typeref: 0x28ae0
+  __TEXT.__swift5_reflstr: 0x3ac28
   __TEXT.__swift5_assocty: 0xe5a8
-  __TEXT.__swift5_fieldmd: 0x5b980
-  __TEXT.__constg_swiftt: 0x5f6c8
+  __TEXT.__swift5_fieldmd: 0x5ba9c
+  __TEXT.__constg_swiftt: 0x5f794
   __TEXT.__swift5_protos: 0x1150
-  __TEXT.__swift5_proto: 0x9770
-  __TEXT.__swift5_types: 0x5d68
+  __TEXT.__swift5_proto: 0x9798
+  __TEXT.__swift5_types: 0x5d7c
   __TEXT.__swift5_types2: 0xbc
   __TEXT.__swift5_builtin: 0x2698
   __TEXT.__swift5_capture: 0x34d8
   __TEXT.__objc_methtype: 0x2d6
   __TEXT.__swift5_mpenum: 0xb6c
-  __TEXT.__swift_as_entry: 0x1634
-  __TEXT.__swift_as_ret: 0x184c
-  __TEXT.__swift_as_cont: 0x2ed0
+  __TEXT.__swift_as_entry: 0x164c
+  __TEXT.__swift_as_ret: 0x186c
+  __TEXT.__swift_as_cont: 0x2f28
   __TEXT.__oslogstring: 0x6cb7
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constructor: 0x0

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x128
-  __TEXT.__eh_frame: 0x743ec
+  __TEXT.__eh_frame: 0x748dc
   __DATA.__TIGHTBEAM_VT: 0x11a0
   __DATA.__TIGHTBEAM: 0x490
-  __DATA.__const: 0xe4ff0
-  __DATA.__data: 0x4c840
+  __DATA.__const: 0xe52c8
+  __DATA.__data: 0x4c868
   __DATA.__mod_init_func: 0x40
   __DATA.__ENDPOINTS: 0x1bbd0
   __DATA.__auth_ptr: 0x5fa8

   __DATA.__bss: 0x240a0
   __DATA.__common: 0x25a1
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
   Functions: 1361
   Symbols:   1
-  CStrings:  14885
+  CStrings:  14904
 
Functions:
~ sub_7ffe4e8 : 141072 -> 141224
~ sub_80244e4 -> sub_802457c : 426140 -> 427932
~ sub_808c580 -> sub_808cd18 : 170976 -> 171232
~ sub_80b62d8 -> sub_80b6b70 : 232 -> 208
~ sub_828d44c -> sub_828dccc : 797256 -> 811244
~ sub_834ffac -> sub_8353ed0 : 679096 -> 679752
~ sub_842f09c -> sub_8433250 : 261736 -> 261584
~ sub_8471660 -> sub_847577c : 1288208 -> 1287740
~ sub_893b418 -> sub_893f360 : 913044 -> 913092
~ sub_8a9d18c -> sub_8aa1104 : 1436 -> 1428
~ sub_8ae9680 -> sub_8aed5f0 : 6048 -> 6096
~ sub_8aeba40 -> sub_8aef9e0 : 307600 -> 307716
~ sub_8c60a54 -> sub_8c64a68 : 42072 -> 42080
~ sub_8c72238 -> sub_8c76254 : 210472 -> 210484
~ sub_8cbaca8 -> sub_8cbecd0 : 264192 -> 264196
~ sub_8cfb4a8 -> sub_8cff4d4 : 11608 -> 11612
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
- "Fri Sep 11 21:40:51 PDT 2026"
- "Resuming ANEEngine to service existing clients"
- "])\n  medinaStateDisplayWake: allowance="
- "_os_log_payload_size(olp), OS_LOG_PAYLOAD_HARD_MAX_SIZE"
- "olp->olp_tpb.tp_size, OS_LOG_PAYLOAD_HDR_SIZE"
```
