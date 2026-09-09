## libsystem_kernel.dylib

> `/usr/lib/system/libsystem_kernel.dylib`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__DATA.__data`
- `__DATA_DIRTY.__data`

```diff

 13432.1.9.0.0
-  __TEXT.__text: 0x358e4
+  __TEXT.__text: 0x3502c
   __TEXT.__const: 0xcc0
   __TEXT.__cstring: 0x6a03
-  __TEXT.__unwind_info: 0x1238
+  __TEXT.__unwind_info: 0x15b8
   __DATA_CONST.__const: 0x2b90
   __AUTH_CONST.__const: 0x150
   __DATA.__crash_info: 0x148
Functions:
~ _kdebug_trace : 128 -> 116
~ _mach_port_mod_refs : 120 -> 108
~ _task_info : 540 -> 532
~ _mach_msg_destroy_port : 268 -> 244
~ _host_create_mach_voucher : 120 -> 108
~ _mach_port_construct : 120 -> 108
~ _mach_port_deallocate : 92 -> 80
~ _mach_port_destruct : 120 -> 108
~ _mach_vm_deallocate : 168 -> 156
~ _mach_port_request_notification : 168 -> 156
~ _mach_port_allocate : 112 -> 100
~ _mach_port_insert_member : 112 -> 100
~ _mach_port_insert_right : 120 -> 108
~ _mach_voucher_extract_attr_recipe : 120 -> 108
~ _mach_port_get_attributes : 140 -> 128
~ _kdebug_trace_string : 168 -> 156
~ _mach_port_type : 112 -> 100
~ _mach_port_guard : 120 -> 108
~ _mach_port_extract_member : 112 -> 100
~ _mach_vm_purgable_control : 120 -> 108
~ _munmap : 108 -> 96
~ _chmod : 252 -> 240
~ _mach_vm_protect : 140 -> 128
~ _fchmod : 252 -> 240
~ _mach_vm_region : 560 -> 552
~ _host_info : 544 -> 536
~ _mach_port_move_member : 112 -> 100
~ _thread_policy : 140 -> 120
~ _gethostuuid : 132 -> 120
~ ___libkernel_init : 532 -> 472
~ _thread_policy_set : 140 -> 120
~ _posix_spawn_file_actions_init : 144 -> 124
~ _malloc : 76 -> 56
~ __posix_spawn_file_actions_grow : 188 -> 168
~ _posix_spawnattr_init : 264 -> 244
~ _posix_spawnattr_setmacpolicyinfo_np : 468 -> 448
~ _posix_spawnattr_destroy : 740 -> 580
~ _posix_spawn_file_actions_destroy : 140 -> 120
~ _thread_info : 508 -> 500
~ _mach_ports_register : 196 -> 184
~ _setiopolicy_np : 144 -> 124
~ _setpriority : 140 -> 120
~ _vm_region_64 : 560 -> 552
~ _vm_region_recurse_64 : 556 -> 548
~ _mach_msg_overwrite : 628 -> 608
~ _mach_msg_server_consume_unsent_message : 104 -> 92
~ _work_interval_create : 280 -> 260
~ _thread_policy_get : 532 -> 524
~ _kdebug_signpost_internal : 180 -> 168
~ _host_statistics : 544 -> 536
~ __kernelrpc_mach_port_get_attributes : 496 -> 488
~ _mach_vm_region_recurse : 556 -> 548
~ _posix_spawn_appendportaction_np : 388 -> 348
~ _posix_spawnattr_setbinpref_np : 184 -> 176
~ _posix_spawnattr_setexceptionports_np : 72 -> 80
~ _reallocf : 208 -> 168
~ __libkernel_strcpy : 72 -> 60
~ _os_packet_trace_event : 100 -> 88
~ _fchmodat : 296 -> 284
~ _internal_catch_exception_raise_state_identity : 228 -> 216
~ _internal_catch_exception_raise_state : 208 -> 196
~ _internal_catch_exception_raise : 176 -> 164
~ _quota : 48 -> 36
~ _setquota : 48 -> 36
~ _mach_vm_reclaim_copied_ring_query : 176 -> 172
~ _thread_set_policy : 140 -> 120
~ _thread_get_register_pointer_values : 520 -> 460
~ ___statfs_ext_impl : 796 -> 736
~ _posix_spawnattr_getbinpref_np : 104 -> 96
~ _posix_spawnattr_getarchpref_np : 120 -> 112
~ _posix_spawnattr_setarchpref_np : 188 -> 180
~ _posix_spawnattr_set_subsystem_root_path_np : 284 -> 244
~ _posix_spawnattr_setcoalition_np : 228 -> 208
~ _posix_spawnattr_set_persona_np : 204 -> 184
~ _posix_spawnattr_set_uid_np : 204 -> 184
~ _posix_spawnattr_set_gid_np : 208 -> 188
~ _posix_spawnattr_set_groups_np : 268 -> 248
~ _posix_spawnattr_set_login_np : 268 -> 248
~ _posix_spawnattr_set_conclave_id_np : 232 -> 212
~ _stackshot_config_create : 128 -> 108
~ _stackshot_config_dealloc : 152 -> 132
~ ___darwin_check_fd_set_overflow : 216 -> 196
~ _os_channel_create_extended : 1960 -> 1900
~ _os_channel_destroy : 228 -> 176
~ _os_channel_attr_create : 144 -> 124
~ _os_channel_attr_set_key : 384 -> 324
~ _os_channel_attr_destroy : 208 -> 156
~ _os_nexus_attr_create : 144 -> 124
~ _os_nexus_attr_destroy : 72 -> 52
~ _os_nexus_controller_create : 240 -> 220
~ _os_nexus_controller_iterate_traffic_rules : 492 -> 432
~ _os_nexus_controller_destroy : 148 -> 116
~ _work_interval_notify_simple : 96 -> 84
~ _work_interval_instance_free : 72 -> 52
~ _work_interval_instance_get_telemetry_data : 28 -> 20
~ _work_interval_destroy : 356 -> 316
~ _proc_listpidspath : 2864 -> 2672
~ _mach_port_unguard : 112 -> 100
~ _host_priv_statistics : 544 -> 536
~ __kernelrpc_mach_port_peek : 532 -> 524
~ _mach_vm_page_info : 492 -> 484
~ _processor_set_statistics : 484 -> 476
~ _processor_set_info : 520 -> 512
~ _processor_info : 532 -> 524
~ _task_policy_get : 532 -> 524
~ _task_inspect : 476 -> 468
~ _mach_memory_entry_region_info : 532 -> 524
~ _mach_voucher_extract_all_attr_recipes : 596 -> 592
~ _mach_voucher_debug_info : 592 -> 588
```
