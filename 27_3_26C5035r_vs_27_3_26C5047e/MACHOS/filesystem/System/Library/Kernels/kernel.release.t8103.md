## kernel.release.t8103

> `/System/Library/Kernels/kernel.release.t8103`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__kern_brk_desc`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__KDP.__text`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__HIBDATA.__data`
- `__BOOTDATA.__static_if`
- `__BOOTDATA.__static_ifinit`

```diff

-13432.60.57.0.0
-  __TEXT.__const: 0x37be0
+13432.60.70.0.3
+  __TEXT.__const: 0x37d30
   __TEXT.__copyio_vectors: 0x150
-  __TEXT.__cstring: 0xa67a9
-  __TEXT.__os_log: 0x42efd
+  __TEXT.__cstring: 0xa6adf
+  __TEXT.__os_log: 0x42fb4
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310
   __DATA_CONST.__sdt_cstring: 0x741a
   __DATA_CONST.__sdt: 0xed48
   __DATA_CONST.__kalloc_type: 0x17dc0
-  __DATA_CONST.__const: 0x1307a0
-  __DATA_CONST.__assert: 0xfb4
+  __DATA_CONST.__const: 0x130710
+  __DATA_CONST.__assert: 0xfc8
   __DATA_CONST.__kalloc_var: 0x7ee0
   __DATA_CONST.__kern_brk_desc: 0x78
   __DATA_CONST.__mod_init_func: 0x2d8
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9c4d88
+  __TEXT_EXEC.__text: 0x9c8488
   __TEXT_EXEC.__hib_text: 0x19a0
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x6b74

   __LAST.__pinst: 0x8
   __LAST.__last: 0x0
   __KLDDATA.__cstring: 0x71f
-  __KLDDATA.__const: 0x9c58
+  __KLDDATA.__const: 0x9c88
   __KLDDATA.__mod_init_func: 0x8
   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__bss: 0x1
-  __DATA.__data: 0x20c09
+  __DATA.__data: 0x20c89
   __DATA.__lock_grp: 0x17390
   __DATA.__percpu: 0x7890
-  __DATA.__common: 0x8cc10
+  __DATA.__common: 0x8cbf0
   __DATA.__bss: 0x4b838
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x670
   __HIBDATA.__common: 0x108
   __BOOTDATA.__data: 0x18000
   __BOOTDATA.__static_if: 0xff0
-  __BOOTDATA.__init: 0x18248
-  __BOOTDATA.__init_entry_set: 0x14cd0
+  __BOOTDATA.__init: 0x18278
+  __BOOTDATA.__init_entry_set: 0x14df0
   __BOOTDATA.__static_ifinit: 0x28
   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x50a14
-  __CTF.__ctf: 0x10e4cb
-  Functions: 22992
+  __CTF.__ctf: 0x10e65b
+  Functions: 23007
   Symbols:   6956
-  CStrings:  26076
+  CStrings:  26095
 
CStrings:
+ "<unavailable>"
+ "Attempted fault on a copy of a file beyond snapshotted file size\n"
+ "Attempted fault on a copy of a file beyond snapshotted file size via vm_fault_page\n"
+ "B16@?0^{task={lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}{os_refcnt=AI}BBBBIIQ^{_vm_map}{queue_entry=^{queue_entry}^{queue_entry}}^{task_watchports}^v{queue_entry=^{queue_entry}^{queue_entry}}^{restartable_ranges}^{processor_set}^{affinity_space}iIiiissiQ{recount_task=^{recount_track}^{recount_usage}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}[4^{ipc_port}]^{ipc_port}[14{exception_action=^{ipc_port}iiii^{label}}]{hardened_exception_action={exception_action=^{ipc_port}iiii^{label}}II}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}[3^{ipc_port}]^^{ipc_port}^{ipc_space}^{task_token_data}^{ledger}{queue_entry=^{queue_entry}^{queue_entry}}iI^vQQC{?=QQAQQ}BBBB^Q^Q^Q^Q^Q^QIIIIII^{proc_ro}^{kcdata_descriptor}Q{queue_entry=^{queue_entry}^{queue_entry}}^{label}IIQQ{cpc_task=B}ACBBBBb4b4b4b4CCCCB*^{vm_shared_region}QQQ^{thread_call}{queue_entry=^{queue_entry}^{queue_entry}}ii^{bank_task}^{ipc_importance_task}{vm_extmod_statistics=qqqqqq}{task_requested_policy=b1b1b2b2b1b1b2b1b3b3b3b1b5b3b3b1b3b1b1b3b1b3b1b1b1b4b12}{task_effective_policy=b1b1b2b1b1b1b2b1b1b3b3b1b1b1b4b1b1b1b3b3b1b1b1b1b1b26}{task_pend_token=(?={?=b1b1b1b1b1b1b1b1b1b1b1b1b1b1}I)}b1b1b1b1b1b27AI^{io_stat_info}{task_writes_counters=QQQQ}{task_writes_counters=QQQQ}{_cpu_time_qos_stats=QQQQQQQ}{_cpu_time_qos_stats=QQQQQQQ}IIQQCCCiii{queue_entry=^{queue_entry}^{queue_entry}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}b16b1b1b1b1b1b1b1b2b1b6c[2^{coalition}][2{queue_entry=^{queue_entry}^{queue_entry}}]Q^vIQ{queue_entry=^{queue_entry}^{queue_entry}}IQQ[16C]Q^{_vmobject_list_output_}II^{vm_deferred_reclamation_metadata_s}QCAB{task_security_config=(?={?=b1b1b1b3b1b1b1b1b1b1C}I)}}8"
+ "Invalid vmo_snapshot_policy value: %u @%s:%d"
+ "SK[%u]: %-30s fsw %p FREE (unconstructed)\n"
+ "SK[%u]: %-30s nexus %p advisory region \"%s\" alloc failed\n"
+ "com.apple.developer.networking.ipoptions.restricted-access"
+ "file copy snapshot statistics"
+ "file copy snapshot violations"
+ "file copy snapshot violations from kernel"
+ "fsw_free_unconstructed"
+ "kernel_violations"
+ "nx_advisory_alloc"
+ "phystokv_reason"
+ "phystokv_reason: illegal phys->kv translation of pa=0x%llx (reasons=0x%b) @%s:%d"
+ "phystokv_reason: invalid reasons 0x%x (pa=0x%llx) @%s:%d"
+ "phystokv_reason_enforce"
+ "pti != NULL && pti->pt_tty == tp"
+ "section data overlaps DOF header"
+ "section data overlaps section headers"
+ "section headers overlap DOF header"
+ "snapshot"
+ "violations"
+ "vnode_link_lock_suspended"
- "B16@?0^{task={lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}{os_refcnt=AI}BBBBIIQ^{_vm_map}{queue_entry=^{queue_entry}^{queue_entry}}^{task_watchports}^v{queue_entry=^{queue_entry}^{queue_entry}}^{restartable_ranges}^{processor_set}^{affinity_space}iIiiissiQ{recount_task=^{recount_track}^{recount_usage}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}[4^{ipc_port}]^{ipc_port}[14{exception_action=^{ipc_port}iiii^{label}}]{hardened_exception_action={exception_action=^{ipc_port}iiii^{label}}II}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}[3^{ipc_port}]^^{ipc_port}^{ipc_space}^{task_token_data}^{ledger}{queue_entry=^{queue_entry}^{queue_entry}}iI^vQQC{?=QQAQQ}BBBB^Q^Q^Q^Q^Q^QIIIIII^{proc_ro}^{kcdata_descriptor}Q{queue_entry=^{queue_entry}^{queue_entry}}^{label}IIQQ{cpc_task=B}ACBBBBb4b4b4b4CCCCB*^{vm_shared_region}QQQ^{thread_call}{queue_entry=^{queue_entry}^{queue_entry}}ii^{bank_task}^{ipc_importance_task}{vm_extmod_statistics=qqqqqq}{task_requested_policy=b1b1b2b2b1b1b2b1b3b3b3b1b5b3b3b1b3b1b1b3b1b3b1b1b1b4b12}{task_effective_policy=b1b1b2b1b1b1b2b1b1b3b3b1b1b1b4b1b1b1b3b3b1b1b1b1b1b26}{task_pend_token=(?={?=b1b1b1b1b1b1b1b1b1b1b1b1b1b1}I)}b1b1b1b1b1b27AI^{io_stat_info}{task_writes_counters=QQQQ}{task_writes_counters=QQQQ}{_cpu_time_qos_stats=QQQQQQQ}{_cpu_time_qos_stats=QQQQQQQ}IIQQCCCiii{queue_entry=^{queue_entry}^{queue_entry}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}b16b1b1b1b1b1b1b1b2b1b6c[2^{coalition}][2{queue_entry=^{queue_entry}^{queue_entry}}]Q^vIQ{queue_entry=^{queue_entry}^{queue_entry}}IQQ[16C]Q^{_vmobject_list_output_}II^{vm_deferred_reclamation_metadata_s}QC{task_security_config=(?={?=b1b1b1b3b1b1b1b1b1b1C}I)}}8"
- "object_no_shadowing_extra_refs"
- "object_pageout_clean_but_shadowing"
- "object_pageout_clean_no_shadowing"
- "pageout_clean_but_shadowing"
- "pageout_clean_no_shadowing"
```
