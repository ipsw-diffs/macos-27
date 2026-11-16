## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__kern_brk_desc`
- `__DATA_CONST.__sdt_cstring`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__got`
- `__KLDDATA.__static_ifinit`
- `__LASTDATA_CONST.__mod_init_func`

```diff

-13432.60.57.0.0
-  __TEXT.__text: 0x910d10
-  __TEXT.__const: 0x45850
-  __TEXT.__os_log: 0x4d22b
-  __TEXT.__cstring: 0xa4a01
+13432.60.70.0.3
+  __TEXT.__text: 0x913880
+  __TEXT.__const: 0x459a0
+  __TEXT.__os_log: 0x4d2fb
+  __TEXT.__cstring: 0xa4be1
   __TEXT.__eh_frame: 0x118
   __DATA.__lock_grp: 0x16950
   __DATA.__data: 0x83c40
   __DATA.__percpu: 0x3e28
-  __DATA.__common: 0x1bde50
+  __DATA.__common: 0x1bde30
   __DATA.__bss: 0x88990
-  __DATA_CONST.__const: 0xa4248
+  __DATA_CONST.__const: 0xa41b8
   __DATA_CONST.__kalloc_type: 0x17d80
   __DATA_CONST.__kalloc_var: 0x7ee0
-  __DATA_CONST.__assert: 0xf78
+  __DATA_CONST.__assert: 0xf8c
   __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_CONST.__sdt_cstring: 0x73f8
-  __DATA_CONST.__sdt: 0xf540
+  __DATA_CONST.__sdt: 0xf558
   __DATA_CONST.__mod_init_func: 0x2c8
   __DATA_CONST.__got: 0x58
-  __KLDDATA.__init: 0x11e98
-  __KLDDATA.__init_entry_set: 0x148f8
-  __KLDDATA.__const: 0x9470
+  __KLDDATA.__init: 0x11ec8
+  __KLDDATA.__init_entry_set: 0x14a18
+  __KLDDATA.__const: 0x94a0
   __KLDDATA.__static_ifinit: 0x8
   __KLDDATA.__cstring: 0x79c
   __KLDDATA.__mod_init_func: 0x8

   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
   __LINKINFO.__symbolsets: 0x4e531
-  __CTF.__ctf: 0xd2308
-  Functions: 27214
-  Symbols:   24465
-  CStrings:  26234
+  __CTF.__ctf: 0xd246a
+  Functions: 27225
+  Symbols:   24480
+  CStrings:  26250
 
Symbols:
+ ___vmo_snapshot_kernel_violations_early_storage
+ ___vmo_snapshot_violation_events_dropped_early_storage
+ ___vmo_snapshot_violations_early_storage
+ ___vmo_snapshot_violations_resilient_media_early_storage
+ ___vmo_snapshot_violations_untrusted_early_storage
+ ___vmo_snapshot_violations_write_early_storage
+ __ca_event_format_vmo_file_snapshot_violation
+ __ca_event_format_vmo_file_snapshot_violation_stats
+ _fsw_free_unconstructed
+ _in_pcb_restricted_ipopts_allowed
+ _inp_wait_sndinprog
+ _telemetry_kernel_backtrace_to_string
+ _vmo_snapshot_kernel_violations
+ _vmo_snapshot_policy
+ _vmo_snapshot_report_violation
+ _vmo_snapshot_violation_events_dropped
+ _vmo_snapshot_violations
+ _vmo_snapshot_violations_resilient_media
+ _vmo_snapshot_violations_untrusted
+ _vmo_snapshot_violations_write
- _dtrace_physmem_read
- _dtrace_physmem_write
- _vm_object_no_shadowing_extra_refs
- _vm_object_pageout_clean_but_shadowing
- _vm_object_pageout_clean_no_shadowing
CStrings:
+ "<unavailable>"
+ "Attempted fault on a copy of a file beyond snapshotted file size\n"
+ "Attempted fault on a copy of a file beyond snapshotted file size via vm_fault_page\n"
+ "B16@?0^{task={lck_mtx_s=(?={?=b16b8b1b1b1b1b4}I)III}{os_refcnt=AI}BBBBIIQ^{_vm_map}{queue_entry=^{queue_entry}^{queue_entry}}^{task_watchports}^v{queue_entry=^{queue_entry}^{queue_entry}}^{restartable_ranges}^{processor_set}^{affinity_space}iIiiissiQ{recount_task=^{recount_track}^{recount_usage}}{lck_mtx_s=(?={?=b16b8b1b1b1b1b4}I)III}[4^{ipc_port}]^{ipc_port}[14{exception_action=^{ipc_port}iiii^{label}}]{hardened_exception_action={exception_action=^{ipc_port}iiii^{label}}II}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}[3^{ipc_port}]^^{ipc_port}^{ipc_space}^{task_token_data}^{ledger}{queue_entry=^{queue_entry}^{queue_entry}}iI^{user_ldt}^vQQQi^Q^Q^Q^Q^Q^QIIIIII^{proc_ro}^{kcdata_descriptor}Q{queue_entry=^{queue_entry}^{queue_entry}}^{label}IIQQ{cpc_task=B}ACBBBBb4b4b4b4CCCC^{vm_shared_region}QQQ^{thread_call}{queue_entry=^{queue_entry}^{queue_entry}}ii^{bank_task}^{ipc_importance_task}{vm_extmod_statistics=qqqqqq}{task_requested_policy=b1b1b2b2b1b1b2b1b3b3b3b1b5b3b3b1b3b1b1b3b1b3b1b1b1b4b12}{task_effective_policy=b1b1b2b1b1b1b2b1b1b3b3b1b1b1b4b1b1b1b3b3b1b1b1b1b1b26}{task_pend_token=(?={?=b1b1b1b1b1b1b1b1b1b1b1b1b1b1}I)}b1b1b1b1b1b27AI^{io_stat_info}{task_writes_counters=QQQQ}{task_writes_counters=QQQQ}{_cpu_time_qos_stats=QQQQQQQ}{_cpu_time_qos_stats=QQQQQQQ}IIQQCCCiii{queue_entry=^{queue_entry}^{queue_entry}}{lck_mtx_s=(?={?=b16b8b1b1b1b1b4}I)III}b16b1b1b1b1b1b1b1b2b1b6c[2^{coalition}][2{queue_entry=^{queue_entry}^{queue_entry}}]Q^vIQ{queue_entry=^{queue_entry}^{queue_entry}}IQQ[16C]Q^{_vmobject_list_output_}II^{vm_deferred_reclamation_metadata_s}QCAB{task_security_config=(?={?=b1b1b1b3b1b1b1b1b1b1C}I)}}8"
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
+ "pti != NULL && pti->pt_tty == tp"
+ "section data overlaps DOF header"
+ "section data overlaps section headers"
+ "section headers overlap DOF header"
+ "snapshot"
+ "violations"
+ "vnode_link_lock_suspended"
- "B16@?0^{task={lck_mtx_s=(?={?=b16b8b1b1b1b1b4}I)III}{os_refcnt=AI}BBBBIIQ^{_vm_map}{queue_entry=^{queue_entry}^{queue_entry}}^{task_watchports}^v{queue_entry=^{queue_entry}^{queue_entry}}^{restartable_ranges}^{processor_set}^{affinity_space}iIiiissiQ{recount_task=^{recount_track}^{recount_usage}}{lck_mtx_s=(?={?=b16b8b1b1b1b1b4}I)III}[4^{ipc_port}]^{ipc_port}[14{exception_action=^{ipc_port}iiii^{label}}]{hardened_exception_action={exception_action=^{ipc_port}iiii^{label}}II}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}[3^{ipc_port}]^^{ipc_port}^{ipc_space}^{task_token_data}^{ledger}{queue_entry=^{queue_entry}^{queue_entry}}iI^{user_ldt}^vQQQi^Q^Q^Q^Q^Q^QIIIIII^{proc_ro}^{kcdata_descriptor}Q{queue_entry=^{queue_entry}^{queue_entry}}^{label}IIQQ{cpc_task=B}ACBBBBb4b4b4b4CCCC^{vm_shared_region}QQQ^{thread_call}{queue_entry=^{queue_entry}^{queue_entry}}ii^{bank_task}^{ipc_importance_task}{vm_extmod_statistics=qqqqqq}{task_requested_policy=b1b1b2b2b1b1b2b1b3b3b3b1b5b3b3b1b3b1b1b3b1b3b1b1b1b4b12}{task_effective_policy=b1b1b2b1b1b1b2b1b1b3b3b1b1b1b4b1b1b1b3b3b1b1b1b1b1b26}{task_pend_token=(?={?=b1b1b1b1b1b1b1b1b1b1b1b1b1b1}I)}b1b1b1b1b1b27AI^{io_stat_info}{task_writes_counters=QQQQ}{task_writes_counters=QQQQ}{_cpu_time_qos_stats=QQQQQQQ}{_cpu_time_qos_stats=QQQQQQQ}IIQQCCCiii{queue_entry=^{queue_entry}^{queue_entry}}{lck_mtx_s=(?={?=b16b8b1b1b1b1b4}I)III}b16b1b1b1b1b1b1b1b2b1b6c[2^{coalition}][2{queue_entry=^{queue_entry}^{queue_entry}}]Q^vIQ{queue_entry=^{queue_entry}^{queue_entry}}IQQ[16C]Q^{_vmobject_list_output_}II^{vm_deferred_reclamation_metadata_s}QC{task_security_config=(?={?=b1b1b1b3b1b1b1b1b1b1C}I)}}8"
- "object_no_shadowing_extra_refs"
- "object_pageout_clean_but_shadowing"
- "object_pageout_clean_no_shadowing"
- "pageout_clean_but_shadowing"
- "pageout_clean_no_shadowing"
```
