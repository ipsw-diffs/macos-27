## kernel.release.t8152

> `/System/Library/Kernels/kernel.release.t8152`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__const`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__exclaves_bt`
- `__DATA_CONST.__kern_brk_desc`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`
- `__BOOTDATA.__static_if`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`

```diff

-13432.40.144.0.1
+13432.40.162.0.0
   __TEXT.__const: 0x38b20
   __TEXT.__copyio_vectors: 0x340
-  __TEXT.__cstring: 0xb6f47
-  __TEXT.__os_log: 0x42a7a
+  __TEXT.__cstring: 0xb6fa2
+  __TEXT.__os_log: 0x42b0a
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310
   __DATA_CONST.__sdt_cstring: 0x73b0

   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9f60b8
+  __TEXT_EXEC.__text: 0x9f6850
   __TEXT_EXEC.__hib_text: 0x19c8
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x6a2c

   __DATA.__lock_grp: 0x17b40
   __DATA.__percpu: 0x8730
   __DATA.__common: 0xa3c60
-  __DATA.__bss: 0xabee0
+  __DATA.__bss: 0xabf10
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x670
   __HIBDATA.__common: 0x108

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x50830
-  __CTF.__ctf: 0x10d19a
-  Functions: 23914
+  __CTF.__ctf: 0x10d104
+  Functions: 23915
   Symbols:   6949
-  CStrings:  26956
+  CStrings:  26960
 
CStrings:
+ "%s: <pid %d> Disallow request nexus with flow divert result\n"
+ "22212111221122112211102222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222220222221111112121111222221112221222222222222221122222112"
+ "22222211111311111221"
+ "B16@?0^{task={lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}{os_refcnt=AI}BBBBIIQ^{_vm_map}{queue_entry=^{queue_entry}^{queue_entry}}^{task_watchports}^v{queue_entry=^{queue_entry}^{queue_entry}}^{restartable_ranges}^{processor_set}^{affinity_space}iIiiissiQ{recount_task=^{recount_track}^{recount_usage}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}[4^{ipc_port}]^{ipc_port}[14{exception_action=^{ipc_port}iiii^{label}}]{hardened_exception_action={exception_action=^{ipc_port}iiii^{label}}II}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}[3^{ipc_port}]^^{ipc_port}^{ipc_space}^{task_token_data}^{ledger}{queue_entry=^{queue_entry}^{queue_entry}}iI^vQQCCACQQQi{?=QQAQQ}BBBBB^Q^Q^Q^Q^Q^QIIIIII^{proc_ro}^{kcdata_descriptor}Q{queue_entry=^{queue_entry}^{queue_entry}}^{label}IIQQ{cpc_task=B}ACBBBBb4b4b4b4CCCCCB*^{vm_shared_region}QQQ^{thread_call}{queue_entry=^{queue_entry}^{queue_entry}}ii^{bank_task}^{ipc_importance_task}{vm_extmod_statistics=qqqqqq}{task_requested_policy=b1b1b2b2b1b1b2b1b3b3b3b1b5b3b3b1b3b1b1b3b1b3b1b1b1b4b12}{task_effective_policy=b1b1b2b1b1b1b2b1b1b3b3b1b1b1b4b1b1b1b3b3b1b1b1b1b1b26}{task_pend_token=(?={?=b1b1b1b1b1b1b1b1b1b1b1b1b1b1}I)}b1b1b1b1b1b27AI^{io_stat_info}{task_writes_counters=QQQQ}{task_writes_counters=QQQQ}{_cpu_time_qos_stats=QQQQQQQ}{_cpu_time_qos_stats=QQQQQQQ}IIQQCCCiii{queue_entry=^{queue_entry}^{queue_entry}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}b16b1b1b1b1b1b1b1b2b1b6c[2^{coalition}][2{queue_entry=^{queue_entry}^{queue_entry}}]Q^vIQ{queue_entry=^{queue_entry}^{queue_entry}}IQQ[16C]Q^{_vmobject_list_output_}II^{vm_deferred_reclamation_metadata_s}^v^vIQC{task_security_config=(?={?=b1b1b1b3b1b1b1b1b1b1C}I)}}8"
+ "SK[%u]: %-30s Tx flow port %d != channel port %d, %s\n"
+ "com.apple.private.verified-jit-mode"
+ "necp_set_socket_resolver_signature_from_parameters"
- "222121112211221122111022222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222221111112121111222221112221222222222222221122222112"
- "2222221111131111121"
- "B16@?0^{task={lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}{os_refcnt=AI}BBBBIIQ^{_vm_map}{queue_entry=^{queue_entry}^{queue_entry}}^{task_watchports}^v{queue_entry=^{queue_entry}^{queue_entry}}^{restartable_ranges}^{processor_set}^{affinity_space}iIiiissiQ{recount_task=^{recount_track}^{recount_usage}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}[4^{ipc_port}]^{ipc_port}[14{exception_action=^{ipc_port}iiii^{label}}]{hardened_exception_action={exception_action=^{ipc_port}iiii^{label}}II}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}[3^{ipc_port}]^^{ipc_port}^{ipc_space}^{task_token_data}^{ledger}{queue_entry=^{queue_entry}^{queue_entry}}iI^vQQCCACQQQi{?=QQAQQ}BBBBB^Q^Q^Q^Q^Q^QIIIIII^{proc_ro}^{kcdata_descriptor}Q{queue_entry=^{queue_entry}^{queue_entry}}^{label}IIQQ{cpc_task=B}ACBBBBb4b4b4b4CCCCCB*^{vm_shared_region}QQQ^{thread_call}{queue_entry=^{queue_entry}^{queue_entry}}ii^{bank_task}^{ipc_importance_task}{vm_extmod_statistics=qqqqqq}{task_requested_policy=b1b1b2b2b1b1b2b1b3b3b3b1b5b3b3b1b3b1b1b3b1b3b1b1b1b4b12}{task_effective_policy=b1b1b2b1b1b1b2b1b1b3b3b1b1b1b4b1b1b1b3b3b1b1b1b1b1b26}{task_pend_token=(?={?=b1b1b1b1b1b1b1b1b1b1b1b1b1b1}I)}b1b1b1b1b1b27AI^{io_stat_info}{task_writes_counters=QQQQ}{task_writes_counters=QQQQ}{_cpu_time_qos_stats=QQQQQQQ}{_cpu_time_qos_stats=QQQQQQQ}IIQQCCCiii{queue_entry=^{queue_entry}^{queue_entry}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}b16b1b1b1b1b1b1b1b2b1b6[2^{coalition}][2{queue_entry=^{queue_entry}^{queue_entry}}]Q^vIQ{queue_entry=^{queue_entry}^{queue_entry}}IQQ[16C]Q^{_vmobject_list_output_}II^{vm_deferred_reclamation_metadata_s}^v^vIQC{task_security_config=(?={?=b1b1b1b3b1b1b1b1b1b1C}I)}}8"
```
