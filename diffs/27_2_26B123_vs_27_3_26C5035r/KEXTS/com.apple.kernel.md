## com.apple.kernel

> `com.apple.kernel`

```diff

-13432.41.4.0.0
-  __TEXT.__const: 0x38b20
+13432.60.57.0.0
+  __TEXT.__const: 0x391e0
   __TEXT.__copyio_vectors: 0x340
-  __TEXT.__cstring: 0xb6fa1
-  __TEXT.__os_log: 0x42c0b
+  __TEXT.__cstring: 0xb8bc2
+  __TEXT.__os_log: 0x435db
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310
-  __DATA_CONST.__sdt_cstring: 0x73e4
-  __DATA_CONST.__sdt: 0xee38
-  __DATA_CONST.__kalloc_type: 0x183c0
-  __DATA_CONST.__const: 0x139b90
-  __DATA_CONST.__assert: 0x15cc
+  __DATA_CONST.__sdt_cstring: 0x7446
+  __DATA_CONST.__sdt: 0xee80
+  __DATA_CONST.__kalloc_type: 0x18640
+  __DATA_CONST.__const: 0x13ac50
+  __DATA_CONST.__assert: 0x15e0
   __DATA_CONST.__kalloc_var: 0x87f0
   __DATA_CONST.__exclaves_bt: 0xc0
-  __DATA_CONST.__kern_brk_desc: 0x60
+  __DATA_CONST.__kern_brk_desc: 0x78
   __DATA_CONST.__mod_init_func: 0x2e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9f7650
+  __TEXT_EXEC.__text: 0x9ffbc0
   __TEXT_EXEC.__hib_text: 0x19c8
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x6a2c
   __KLD.__text: 0xab7c
+  __KDP.__text: 0x49c
   __LASTDATA_CONST.__mod_init_func: 0x8
   __LAST.__pinst: 0x8
   __LAST.__last: 0x0
   __KLDDATA.__cstring: 0x71f
-  __KLDDATA.__const: 0xa0c0
+  __KLDDATA.__const: 0xa0f8
   __KLDDATA.__mod_init_func: 0x8
   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__bss: 0x1
-  __DATA.__data: 0x20c11
-  __DATA.__lock_grp: 0x17b40
+  __DATA.__data: 0x20c51
+  __DATA.__lock_grp: 0x17f18
   __DATA.__percpu: 0x8730
-  __DATA.__common: 0xa3c60
-  __DATA.__bss: 0xabf10
+  __DATA.__common: 0xa3fc0
+  __DATA.__bss: 0xae5b8
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x670
   __HIBDATA.__common: 0x108
   __BOOTDATA.__data: 0x18000
   __BOOTDATA.__static_if: 0xed0
-  __BOOTDATA.__init: 0x22378
-  __BOOTDATA.__init_entry_set: 0x157b0
+  __BOOTDATA.__init: 0x224d0
+  __BOOTDATA.__init_entry_set: 0x15ca8
   __BOOTDATA.__static_ifinit: 0x18
   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x5089d
+  __LINKINFO.__symbolsets: 0x50a14
   __CTF.__ctf: 0x0
-  Functions: 23922
-  Symbols:   6951
-  CStrings:  26968
+  Functions: 23974
+  Symbols:   6956
+  CStrings:  27235
 
Symbols:
+ __ZN9IOService49exclaveRegisterANEUpcallUpdateXnuContentWithFlagsEPNS_19IOExclaveProxyStateEU13block_pointerFyyyyyE
+ _gIOPlatformRootUnmountActionKey
+ _launch_constraint_data_get_caller_is_platform_binary
+ _launch_constraint_data_get_caller_is_xpc_launcher
+ _launch_constraint_data_get_is_exec
CStrings:
+ "!upl->is_copyout_from"
+ "%s n %p bad copy len %d @%s:%d"
+ "%s: %s: %d ipsec offload object(s) still installed at cleanup; deinstalling\n"
+ "%s: %s: %s not forwarding looped back packet"
+ "%s: %s: SA delete: unknown handle 0x%llx\n"
+ "%s: %s: SA selector transport %u is not an IPSEC_OFFLOAD_L4_* value\n"
+ "%s: %s: header too large for tso, mss %d"
+ "%s: %s: header too large to segment, mss %d"
+ "%s: %s: ipsec offload object table full\n"
+ "%s: %s: policy delete: unknown handle 0x%llx\n"
+ "%s: %s: policy selector transport %u is not an IPSEC_OFFLOAD_L4_* value\n"
+ "%s: %s: reclaimed %d ipsec offload object(s) after flush\n"
+ "%s: <pid %d> Disallow flow add, requested nexus mismatched with NECP result - requested ifindex %d policy <result %d ifindex %d>\n"
+ "%s: IPv6 payload length %u < extension headers %d"
+ "%s: NECP CLIENT FLOW TRACE <pid %d %s> <flow %s> <filter - flow %X client %X>: defuncting flow registration flags=0x%x\n\n"
+ "%s: NECP CLIENT FLOW TRACE <pid %d %s> <flow %s> <filter - flow %X client %X>: preserving resolve registration across interface-property drop flags=0x%x\n\n"
+ "%s: NECP_CLIENT_RESULT_LOG <pid %d %s> <result %d> <tunnel %d> <scope %d> <flowdivert %d> <filter %d> <result flags %X>: Updated client result\n\n"
+ "%s: TLS PSK derivation context add: duplicate inbound key ID %llu\n"
+ "%s: TLS PSK derivation context flush payload length is invalid (%lu)\n"
+ "%s: TLS PSK derivation context payload length is invalid (%lu)\n"
+ "%s: TLS PSK derivation context remove payload length is invalid (%lu)\n"
+ "%s: TLS derived PSK inbound copyin agent_uuid error (%d)\n"
+ "%s: TLS derived PSK inbound copyin params error (%d)\n"
+ "%s: TLS derived PSK inbound: no derivation context for key ID 0x%llx\n"
+ "%s: TLS derived PSK inbound: service ID too long (%zu > %d)\n"
+ "%s: TLS derived PSK inbound: user buffer too small (%zu < %zu)\n"
+ "%s: TLS derived PSK outbound copyin agent_uuid error (%d)\n"
+ "%s: TLS derived PSK outbound copyin params error (%d)\n"
+ "%s: TLS derived PSK outbound: service ID too long (%zu > %d)\n"
+ "%s: TLS derived PSK outbound: user buffer too small (%zu < %zu)\n"
+ "%s: bad TCP data offset"
+ "%s: changing cache attributes of page that may be UAT-mapped, pn=%#x, wimg_bits_prev=%#x, wimg_bits_new=%#x, update_pp_attr=%d @%s:%d"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/xnu/bsd/net/if_fake_ipsec.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/xnu/bsd/netkey/key_offload.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/xnu/bsd/skywalk/nexus/netif/nx_netif_ipsec.c"
+ "11111122"
+ "111111222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222221121122222222222211222122112222121"
+ "111121222222222222221222222122"
+ "11112221122222211111121"
+ "111221"
+ "112222221212221222222222222222222222222221122222"
+ "2111111222222222222122222112111111221"
+ "2211122022222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222022212122222111111122221111111222221111112222211111122222111111222221122221112221111211111110"
+ "2212122222222222222222112222212111111112211222112"
+ "32-bit 4k commpage not supported for SPTM configurations @%s:%d"
+ "ARM_BR_MIS_PRED"
+ "ARM_BR_PRED"
+ "ARM_L1D_CACHE"
+ "ARM_L1D_CACHE_LMISS_RD"
+ "ARM_L1D_CACHE_RD"
+ "ARM_L1D_CACHE_REFILL"
+ "ARM_L1I_CACHE"
+ "ARM_MEM_ACCESS"
+ "ARM_MEM_ACCESS_CHECKED"
+ "ARM_MEM_ACCESS_CHECKED_RD"
+ "ARM_MEM_ACCESS_CHECKED_WR"
+ "ARM_MEM_ACCESS_RD"
+ "ARM_MEM_ACCESS_WR"
+ "ARM_STALL"
+ "ARM_STALL_BACKEND"
+ "ARM_STALL_FRONTEND"
+ "ARM_STALL_SLOT"
+ "ARM_STALL_SLOT_BACKEND"
+ "ARM_STALL_SLOT_FRONTEND"
+ "ATOMIC_OR_EXCLUSIVE_FAIL"
+ "ATOMIC_OR_EXCLUSIVE_SUCC"
+ "BRANCH_BR_INDIR_MISPRED_NONSPEC"
+ "BRANCH_CALL_INDIR_MISPRED_NONSPEC"
+ "BRANCH_COND_MISPRED_NONSPEC"
+ "BRANCH_INDIR_MISPRED_NONSPEC"
+ "BRANCH_MISPRED_NONSPEC"
+ "BRANCH_RET_INDIR_MISPRED_NONSPEC"
+ "CORE_ACTIVE_CYCLE"
+ "CORE_WAITING_SME_ENGINE_CYCLE"
+ "DECODE_UOP"
+ "FETCH_RESTART"
+ "FLUSH_RESTART_OTHER_NONSPEC"
+ "Flush ipsec offload state when a feth is destroyed, like IOSkywalkFamily"
+ "Hold the ipsec gate this many ms after a simulated disable (test only)"
+ "INST_ALL"
+ "INST_BARRIER"
+ "INST_BRANCH"
+ "INST_BRANCH_CALL"
+ "INST_BRANCH_CALL_INDIR"
+ "INST_BRANCH_COND"
+ "INST_BRANCH_INDIR"
+ "INST_BRANCH_RET"
+ "INST_BRANCH_TAKEN"
+ "INST_INT_ALU"
+ "INST_INT_LD"
+ "INST_INT_ST"
+ "INST_LDST"
+ "INST_MICROCODED"
+ "INST_SIMD_ALU"
+ "INST_SIMD_ALU_VEC"
+ "INST_SIMD_LD"
+ "INST_SIMD_ST"
+ "INST_SME_ENGINE_ALU"
+ "INST_SME_ENGINE_LD"
+ "INST_SME_ENGINE_PACKING_FUSED"
+ "INST_SME_ENGINE_SCALARFP"
+ "INST_SME_ENGINE_ST"
+ "INTERRUPT_PENDING"
+ "IOExclaveLPW: operation start: LPW(%llx, %llx) types %llx id %llx\n"
+ "IOExclaveLPW: operation stop: id %llx\n"
+ "IOPlatformRootUnmountAction"
+ "IPTunnel (%s%d, %X)"
+ "IPsec offload SA adds that found the same SPI still installed"
+ "IPsec offload SAs currently installed in the fake driver"
+ "IPsec offload adds refused for a selector transport outside the KPI enum"
+ "IPsec offload objects reclaimed at interface teardown (should be 0)"
+ "IPsec offload objects the driver reclaimed after a flush (raced adds only)"
+ "IPsec offload policies currently installed in the fake driver"
+ "L1D_CACHE_MISS_LD"
+ "L1D_CACHE_MISS_LD_NONSPEC"
+ "L1D_CACHE_MISS_ST"
+ "L1D_CACHE_MISS_ST_NONSPEC"
+ "L1D_CACHE_WRITEBACK"
+ "L1D_TLB_ACCESS"
+ "L1D_TLB_FILL"
+ "L1D_TLB_MISS"
+ "L1D_TLB_MISS_NONSPEC"
+ "L1I_CACHE_MISS_DEMAND"
+ "L1I_TLB_FILL"
+ "L1I_TLB_MISS_DEMAND"
+ "L2_TLB_MISS_DATA"
+ "L2_TLB_MISS_INSTRUCTION"
+ "LDST_MEM_ACCESS_CHECKED_X2K"
+ "LDST_OLDEST_MTE_TAG_CHECK_CYCLE"
+ "LDST_SME_PRED_INACTIVE"
+ "LDST_SME_XPG_UOP"
+ "LDST_UNIT_OLD_L1D_CACHE_MISS"
+ "LDST_UNIT_WAITING_OLD_L1D_CACHE_MISS"
+ "LDST_UNIT_WAITING_SME_ENGINE_INST_QUEUE_FULL"
+ "LDST_UNIT_WAITING_SME_ENGINE_MEM_DATA"
+ "LDST_X64_UOP"
+ "LDST_XPG_UOP"
+ "LD_NT_UOP"
+ "LD_SME_MEM_ORDER_VIOL_LD_NONSPEC"
+ "LD_SME_NORMAL_UOP"
+ "LD_SME_NT_UOP"
+ "LD_SRC_CORE_SAMECLUSTER_NONSPEC"
+ "LD_SRC_LL_CACHE_NONSPEC"
+ "LD_SRC_MEMSYS_NONSPEC"
+ "LD_SRC_MEMSYS_OTHERDIE_NONSPEC"
+ "LD_SRC_OTHERCLUSTER_NONSPEC"
+ "LD_SRC_OTHERCLUSTER_OTHERDIE_NONSPEC"
+ "LD_SRC_PL2_CACHE_NONSPEC"
+ "LD_SRC_STORE_NONSPEC"
+ "LD_UNIT_UOP"
+ "LD_UNIT_WAITING_YOUNG_L1D_CACHE_MISS"
+ "MAP_DISPATCH_BUBBLE"
+ "MAP_DISPATCH_BUBBLE_IC"
+ "MAP_DISPATCH_BUBBLE_ITLB"
+ "MAP_DISPATCH_BUBBLE_SLOT"
+ "MAP_DISPATCH_BUBBLE_TAKENBR_SLOT"
+ "MAP_INT_SME_UOP"
+ "MAP_INT_UOP"
+ "MAP_LDST_UOP"
+ "MAP_RECOVERY"
+ "MAP_REWIND"
+ "MAP_SIMD_UOP"
+ "MAP_STALL"
+ "MAP_STALL_DISPATCH"
+ "MAP_STALL_NONRECOVERY"
+ "MAP_UOP"
+ "MMU_TABLE_WALK_DATA"
+ "MMU_TABLE_WALK_INSTRUCTION"
+ "No TLS PSK derivation context received"
+ "No TLS PSK derivation context remove request received"
+ "Number of CEs detected this boot"
+ "Number of pages currently deferred for SK Framebank withdrawal"
+ "PL2_CACHE_ACCESS"
+ "PL2_CACHE_ACCESS_INSTRUCTION"
+ "PL2_CACHE_ACCESS_LD"
+ "PL2_CACHE_ACCESS_MMU"
+ "PL2_CACHE_ACCESS_ST"
+ "PL2_CACHE_MISS"
+ "PL2_CACHE_MISS_INSTRUCTION"
+ "PL2_CACHE_MISS_LD"
+ "PL2_CACHE_MISS_MMU"
+ "PL2_CACHE_MISS_ST"
+ "RETIRE_UOP"
+ "Re-enable ipsec offload on the named feth after a simulated disable (test only)"
+ "Request to add TLS PSK derivation context"
+ "Request to flush TLS PSK derivation contexts"
+ "Request to remove TLS PSK derivation context"
+ "SA"
+ "SCHEDULE_EMPTY"
+ "SCHEDULE_UOP_ANY"
+ "SCHEDULE_WAITING_SME_ENGINE_REG_DATA"
+ "SK[%u]: %-30s %s: ipsec offload capability has no io_release; offload disabled\n"
+ "SK[%u]: %-30s %s: ipsec offload capability rejected (%d); sent io_version %u, io_ops_version %u\n"
+ "SK[%u]: %-30s %s: no ipsec offload capability (%d)\n"
+ "SME_ENGINE_SM_ENABLE"
+ "SME_ENGINE_SM_ZA_ENABLE"
+ "SME_ENGINE_ZA_ENABLED_SM_DISABLED"
+ "ST_MEM_ORDER_VIOL_LD_NONSPEC"
+ "ST_NT_UOP"
+ "ST_SME_MEM_ORDER_VIOL_LD_NONSPEC"
+ "ST_SME_NORMAL_UOP"
+ "ST_SME_NT_UOP"
+ "ST_UNIT_UOP"
+ "Simulate an interface disable's ipsec teardown on the named feth (test only)"
+ "SocketScoped (%s%d, %X)"
+ "Stall an IPsec offload SA add this many ms before it returns (test only)"
+ "Stall an IPsec offload SA delete this many ms before it runs (test only)"
+ "Stall an IPsec offload policy add this many ms before it returns (test only)"
+ "TLS derived PSK inbound: agent not found"
+ "TLS derived PSK inbound: caller is not a platform binary"
+ "TLS derived PSK inbound: failed to write response TLV"
+ "TLS derived PSK inbound: missing instance ID or nonce"
+ "TLS derived PSK inbound: missing required TLVs"
+ "TLS derived PSK inbound: missing service ID"
+ "TLS derived PSK outbound: agent not found"
+ "TLS derived PSK outbound: failed to write response TLVs"
+ "TLS derived PSK outbound: missing instance ID"
+ "TLS derived PSK outbound: missing required TLVs"
+ "TLS derived PSK outbound: missing service ID"
+ "TLS derived PSK outbound: no outbound derivation context"
+ "__KDP"
+ "bytes_lost (%u) smaller than clamped length (%u)"
+ "capab.io_ops->ops_policy_add != NULL"
+ "capab.io_ops->ops_policy_delete != NULL"
+ "capab.io_ops->ops_sa_add != NULL"
+ "capab.io_ops->ops_sa_delete != NULL"
+ "clamp partial-below RACK segment [%u, %u) flags 0x%x to snd_una %u"
+ "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
+ "com.apple.xpc.launchd"
+ "com.apple.xpc.proxy"
+ "feth_ipsec_cleanup"
+ "feth_ipsec_gate_owner == current_thread()"
+ "feth_ipsec_obj_purge"
+ "feth_ipsec_policy_count > 0"
+ "feth_ipsec_sa_count > 0"
+ "io->io_refcnt > 0"
+ "ipsec__offload__flush"
+ "ipsec__offload__flush__late"
+ "ipsec__offload__flush__nohandler"
+ "ipsec__offload__no__release"
+ "ipsec__offload__unavailable"
+ "ipsec_offload_add_return_delay_ms"
+ "ipsec_offload_bad_transport"
+ "ipsec_offload_delete_delay_ms"
+ "ipsec_offload_disable"
+ "ipsec_offload_disable_hold_ms"
+ "ipsec_offload_dup_spi"
+ "ipsec_offload_enable"
+ "ipsec_offload_flush_on_destroy"
+ "ipsec_offload_leaked"
+ "ipsec_offload_policy_add_return_delay_ms"
+ "ipsec_offload_policy_count"
+ "ipsec_offload_policy_count > 0"
+ "ipsec_offload_reclaimed"
+ "ipsec_offload_sa_count"
+ "ipsec_offload_sav_count > 0"
+ "key_flush_offload_for_ifnet: %s: removed %u offloaded SA(s), %u policy(ies)\n"
+ "key_install_offload_policy: handle 0x%llx abandoned to an in-progress teardown\n"
+ "key_install_offload_sa: handle 0x%llx abandoned to an in-progress teardown\n"
+ "key_offload_delete"
+ "key_offload_issue_deletes: %s delete failed %d\n"
+ "kill_footprint_pages"
+ "kill_pages_freed"
+ "mptcp_usr_sosend"
+ "necp_client_acquire_tls_derived_psk_inbound"
+ "necp_client_acquire_tls_derived_psk_inbound bad input"
+ "necp_client_acquire_tls_derived_psk_outbound"
+ "necp_client_acquire_tls_derived_psk_outbound bad input"
+ "necp_defunct_flow_registration"
+ "netagent_acquire_tls_derived_psk_inbound"
+ "netagent_acquire_tls_derived_psk_outbound"
+ "netagent_handle_tls_psk_derivation_context_add_setopt"
+ "netagent_handle_tls_psk_derivation_context_flush_setopt"
+ "netagent_handle_tls_psk_derivation_context_remove_setopt"
+ "nx_netif_ipsec_offload_configure"
+ "nx_netif_ipsec_offload_retain"
+ "offload interface teardowns"
+ "offload_flush_generation"
+ "oslog_metadata_version"
+ "pageout_freed_external_executable"
+ "pageout_freed_external_sharedcache"
+ "pageout_freed_external_sharedcache_executable"
+ "pageout_freed_internal"
+ "pageout_freed_speculative_sharedcache"
+ "pmap_fast_faults"
+ "pmap_force_fast_faults"
+ "pmap_spurious_fast_faults"
+ "site.struct key_offload_delete"
+ "site.struct netagent_tls_psk_derivation_context"
+ "site.struct netif_ipsec_offload"
+ "site.struct os_log_metadata_entry"
+ "sk_deferred_page_count"
+ "sosend"
+ "stale RACK segment [%u, %u) flags 0x%x at or below snd_una %u"
+ "v24@?0^{thread=(?={queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}{mpsc_queue_chain=A^{mpsc_queue_chain}}{priority_queue_entry_sched=^{priority_queue_entry_sched}^{priority_queue_entry_sched}b16b4b44})Q{?=^{processor}}(?=^{waitq}^{waitq_set}^{select_set})^{turnstile}^v{priority_queue_sched_max=^{priority_queue_entry_sched}}{priority_queue_sched_max=^{priority_queue_entry_sched}}B[2B][2B][2B]b1b1b0c{priority_queue_entry_stable=^{priority_queue_entry_stable}^{priority_queue_entry_stable}b16b4b44Q}{priority_queue_entry_sched=^{priority_queue_entry_sched}^{priority_queue_entry_sched}b16b4b44}{queue_entry=^{queue_entry}^{queue_entry}}{lck_spin_s={hslock=Q}Q}{lck_spin_s={hslock=Q}Q}SBBCBBBIIi(thread_rr_state=I{?=CCS})^?^vQQ{machine_thread=I^{arm_context}^{arm_saved_state}^{arm_neon_saved_state}^{arm_saved_state}(?=^{arm_state_hdr}^{?})QQ^{arm_debug_aggregate_state}QQ^vQ{perfcontrol_state=[8Q]}QQ(?=qS)^{cpu_data}ISBBBQQQQQB}iiiCIIIsssssSsCiAII{smrq_slist_head={?=^{smrq_slink}}}^{vm_map_lock_ctx}ii^{timer_call}{?=IIIBCQ}QQQQQQ^{thread_group}^{processor}^{processor}^{processor}QQQQ^?IIIIIIIIQQQQQ{timer=QQ}{recount_thread=^{recount_track}QI}Q{queue_entry=^{queue_entry}^{queue_entry}}^{affinity_set}^{task_watcher}(?={?={?=QQII}Q^{ipc_object}iIIII^{ipc_kmsg}}{?=^{semaphore}^{semaphore}ii^?}{?=[8^v]})(?=^{thread_call_thread_state}{?=iiqq})iiBBI{circle_queue_head=^{queue_entry}}^{ipc_port}Q{queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}^{thread_ro}^{_vm_map}^{timer_call}SBb1b1b1b1b1b1b1b1b0AI{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}^{ipc_port}[3^{ipc_port}]^{ipc_port}^{ipc_port}SSIqqQIIiI^{ipc_voucher}IIIIIAS^Q^vII^{ledger}^{ledger}^{ledger}QQQII{thread_requested_policy=b1b1b2b2b1b1b3b3b1b3b4b3b3b3b1b3b3b2b1b23}{thread_effective_policy=b1b2b1b1b1b1b1b3b3b3b4b3b1b1b38}^{thread_qos_override}ICCAS^{io_stat_info}IIIISb1b1b1b1b1b11C^{thread_group}^{thread_group}^{thread_group}(?=^{thread_group}^{thread_group})^{work_interval}IiiiIi^v^{knote}Q^{exclaves_ctx}ISAS^{task}{queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}^{task}{ipc_sec_policy_in_flight_violation_info=*Ii}}8^{thread=(?={queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}{mpsc_queue_chain=A^{mpsc_queue_chain}}{priority_queue_entry_sched=^{priority_queue_entry_sched}^{priority_queue_entry_sched}b16b4b44})Q{?=^{processor}}(?=^{waitq}^{waitq_set}^{select_set})^{turnstile}^v{priority_queue_sched_max=^{priority_queue_entry_sched}}{priority_queue_sched_max=^{priority_queue_entry_sched}}B[2B][2B][2B]b1b1b0c{priority_queue_entry_stable=^{priority_queue_entry_stable}^{priority_queue_entry_stable}b16b4b44Q}{priority_queue_entry_sched=^{priority_queue_entry_sched}^{priority_queue_entry_sched}b16b4b44}{queue_entry=^{queue_entry}^{queue_entry}}{lck_spin_s={hslock=Q}Q}{lck_spin_s={hslock=Q}Q}SBBCBBBIIi(thread_rr_state=I{?=CCS})^?^vQQ{machine_thread=I^{arm_context}^{arm_saved_state}^{arm_neon_saved_state}^{arm_saved_state}(?=^{arm_state_hdr}^{?})QQ^{arm_debug_aggregate_state}QQ^vQ{perfcontrol_state=[8Q]}QQ(?=qS)^{cpu_data}ISBBBQQQQQB}iiiCIIIsssssSsCiAII{smrq_slist_head={?=^{smrq_slink}}}^{vm_map_lock_ctx}ii^{timer_call}{?=IIIBCQ}QQQQQQ^{thread_group}^{processor}^{processor}^{processor}QQQQ^?IIIIIIIIQQQQQ{timer=QQ}{recount_thread=^{recount_track}QI}Q{queue_entry=^{queue_entry}^{queue_entry}}^{affinity_set}^{task_watcher}(?={?={?=QQII}Q^{ipc_object}iIIII^{ipc_kmsg}}{?=^{semaphore}^{semaphore}ii^?}{?=[8^v]})(?=^{thread_call_thread_state}{?=iiqq})iiBBI{circle_queue_head=^{queue_entry}}^{ipc_port}Q{queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}^{thread_ro}^{_vm_map}^{timer_call}SBb1b1b1b1b1b1b1b1b0AI{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}^{ipc_port}[3^{ipc_port}]^{ipc_port}^{ipc_port}SSIqqQIIiI^{ipc_voucher}IIIIIAS^Q^vII^{ledger}^{ledger}^{ledger}QQQII{thread_requested_policy=b1b1b2b2b1b1b3b3b1b3b4b3b3b3b1b3b3b2b1b23}{thread_effective_policy=b1b2b1b1b1b1b1b3b3b3b4b3b1b1b38}^{thread_qos_override}ICCAS^{io_stat_info}IIIISb1b1b1b1b1b11C^{thread_group}^{thread_group}^{thread_group}(?=^{thread_group}^{thread_group})^{work_interval}IiiiIi^v^{knote}Q^{exclaves_ctx}ISAS^{task}{queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}^{task}{ipc_sec_policy_in_flight_violation_info=*Ii}}16"
+ "v24@?0{exclaveindicatorcontroller_cpstate_s=QQ}8"
+ "vm_upl_sk_retype_back: kalloc_type failed for %llu pages @%s:%d"
- "%s: NECP_CLIENT_RESULT_LOG <pid %d %s> <result %d> <tunnel %d> <scope %d> <flowdivert %d> <filter %d>: Updated client result\n\n"
- "11111122222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222221121122222222222211222122112222121"
- "11112122222222222222122222122"
- "11112221122222211121"
- "11222222121222122222222222222222222222222112222"
- "21111112222222222122222112111111221"
- "22111220222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222220222121222221111111222211111112222211111122222111111222221111112222211222211122211112111111111111"
- "2212122222222222222222222212111111112211222112"
- "32-bit 4k commpage not currently supported for SPTM configurations @%s:%d"
- "LPW(%llx, %llx)"
- "Number of CEs logged this boot"
- "SK[%u]: %-30s %s does not support ipsec offload\n"
- "SK[%u]: %-30s ifp %p || ifp->if_na %p\n"
- "SK[%u]: %-30s ipsec offload capab error: %d\n"
- "SK[%u]: %-30s nif == NULL\n"
- "check_ipsec_offload"
- "configure_capab_ipsec_offload"
- "invalid__ifp"
- "invalid__nif"
- "ipsec_offload->io_ops.ops_policy_add != NULL"
- "ipsec_offload->io_ops.ops_policy_delete != NULL"
- "ipsec_offload->io_ops.ops_sa_add != NULL"
- "ipsec_offload->io_ops.ops_sa_delete != NULL"
- "ipsec_offload->io_prov_ctx != NULL"
- "key_delsp: offload policy delete failed %d\n"
- "key_reset_sav: offload delete failed %d\n"
- "ln->ln_state > ND6_LLINFO_INCOMPLETE"
- "not__supported"
- "stale RACK segment [%u, %u) flags 0x%x below snd_una %u"
- "v24@?0^{thread=(?={queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}{mpsc_queue_chain=A^{mpsc_queue_chain}}{priority_queue_entry_sched=^{priority_queue_entry_sched}^{priority_queue_entry_sched}b16b4b44})Q{?=^{processor}}(?=^{waitq}^{waitq_set}^{select_set})^{turnstile}^v{priority_queue_sched_max=^{priority_queue_entry_sched}}{priority_queue_sched_max=^{priority_queue_entry_sched}}B[2B][2B][2B]b1b1b0c{priority_queue_entry_stable=^{priority_queue_entry_stable}^{priority_queue_entry_stable}b16b4b44Q}{priority_queue_entry_sched=^{priority_queue_entry_sched}^{priority_queue_entry_sched}b16b4b44}{queue_entry=^{queue_entry}^{queue_entry}}{lck_spin_s={hslock=Q}Q}{lck_spin_s={hslock=Q}Q}SBBCBBBIIi(thread_rr_state=I{?=CCS})^?^vQQ{machine_thread=I^{arm_context}^{arm_saved_state}^{arm_neon_saved_state}^{arm_saved_state}(?=^{arm_state_hdr}^{?})QQ^{arm_debug_aggregate_state}QQ^vQ{perfcontrol_state=[8Q]}QQ(?=qS)^{cpu_data}ISBBBQQQQQB}iiiCIIIsssssSsCiAII{smrq_slist_head={?=^{smrq_slink}}}^{vm_map_lock_ctx}ii^{timer_call}{?=IIIBCQ}QQQQQQ^{thread_group}^{processor}^{processor}^{processor}QQQQ^?IIIIIIIIQQQQQ{timer=QQ}{recount_thread=^{recount_track}QI}Q{queue_entry=^{queue_entry}^{queue_entry}}^{affinity_set}^{task_watcher}(?={?={?=QQII}Q^{ipc_object}iIIII^{ipc_kmsg}}{?=^{semaphore}^{semaphore}ii^?}{?=[8^v]})(?=^{thread_call_thread_state}{?=iiqq})iiI{circle_queue_head=^{queue_entry}}^{ipc_port}BB{queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}^{thread_ro}^{_vm_map}^{timer_call}SBb1b1b1b1b1b1b1b1b0AI{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}^{ipc_port}[3^{ipc_port}]^{ipc_port}^{ipc_port}SSIqqQIIiI^{ipc_voucher}IIIIIAS^Q^vII^{ledger}^{ledger}^{ledger}QQQII{thread_requested_policy=b1b1b2b2b1b1b3b3b1b3b4b3b3b3b1b3b3b2b1b23}{thread_effective_policy=b1b2b1b1b1b1b1b3b3b3b4b3b1b1b38}^{thread_qos_override}ICCAS^{io_stat_info}IIIISb1b1b1b1b1b11C^{thread_group}^{thread_group}^{thread_group}(?=^{thread_group}^{thread_group})^{work_interval}IiiiIi^v^{knote}Q^{exclaves_ctx}ISAS^{task}{queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}^{task}{ipc_sec_policy_in_flight_violation_info=*Ii}}8^{thread=(?={queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}{mpsc_queue_chain=A^{mpsc_queue_chain}}{priority_queue_entry_sched=^{priority_queue_entry_sched}^{priority_queue_entry_sched}b16b4b44})Q{?=^{processor}}(?=^{waitq}^{waitq_set}^{select_set})^{turnstile}^v{priority_queue_sched_max=^{priority_queue_entry_sched}}{priority_queue_sched_max=^{priority_queue_entry_sched}}B[2B][2B][2B]b1b1b0c{priority_queue_entry_stable=^{priority_queue_entry_stable}^{priority_queue_entry_stable}b16b4b44Q}{priority_queue_entry_sched=^{priority_queue_entry_sched}^{priority_queue_entry_sched}b16b4b44}{queue_entry=^{queue_entry}^{queue_entry}}{lck_spin_s={hslock=Q}Q}{lck_spin_s={hslock=Q}Q}SBBCBBBIIi(thread_rr_state=I{?=CCS})^?^vQQ{machine_thread=I^{arm_context}^{arm_saved_state}^{arm_neon_saved_state}^{arm_saved_state}(?=^{arm_state_hdr}^{?})QQ^{arm_debug_aggregate_state}QQ^vQ{perfcontrol_state=[8Q]}QQ(?=qS)^{cpu_data}ISBBBQQQQQB}iiiCIIIsssssSsCiAII{smrq_slist_head={?=^{smrq_slink}}}^{vm_map_lock_ctx}ii^{timer_call}{?=IIIBCQ}QQQQQQ^{thread_group}^{processor}^{processor}^{processor}QQQQ^?IIIIIIIIQQQQQ{timer=QQ}{recount_thread=^{recount_track}QI}Q{queue_entry=^{queue_entry}^{queue_entry}}^{affinity_set}^{task_watcher}(?={?={?=QQII}Q^{ipc_object}iIIII^{ipc_kmsg}}{?=^{semaphore}^{semaphore}ii^?}{?=[8^v]})(?=^{thread_call_thread_state}{?=iiqq})iiI{circle_queue_head=^{queue_entry}}^{ipc_port}BB{queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}^{thread_ro}^{_vm_map}^{timer_call}SBb1b1b1b1b1b1b1b1b0AI{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}^{ipc_port}[3^{ipc_port}]^{ipc_port}^{ipc_port}SSIqqQIIiI^{ipc_voucher}IIIIIAS^Q^vII^{ledger}^{ledger}^{ledger}QQQII{thread_requested_policy=b1b1b2b2b1b1b3b3b1b3b4b3b3b3b1b3b3b2b1b23}{thread_effective_policy=b1b2b1b1b1b1b1b3b3b3b4b3b1b1b38}^{thread_qos_override}ICCAS^{io_stat_info}IIIISb1b1b1b1b1b11C^{thread_group}^{thread_group}^{thread_group}(?=^{thread_group}^{thread_group})^{work_interval}IiiiIi^v^{knote}Q^{exclaves_ctx}ISAS^{task}{queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}^{task}{ipc_sec_policy_in_flight_violation_info=*Ii}}16"
```
