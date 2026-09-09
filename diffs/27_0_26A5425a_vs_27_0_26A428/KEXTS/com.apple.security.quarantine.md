## com.apple.security.quarantine

> `com.apple.security.quarantine`

```diff

   __TEXT.__const: 0x71
   __TEXT.__cstring: 0x715
   __TEXT.__os_log: 0x3ba
-  __TEXT_EXEC.__text: 0x981c
+  __TEXT_EXEC.__text: 0x99c4
   __TEXT_EXEC.__auth_stubs: 0x900
   __DATA.__data: 0xcc3
   __DATA.__common: 0x24
Functions:
~ _qtn_datadup : 88 -> 92
~ _qtn_strdup : 92 -> 96
~ _responsibility_get_responsible_proc : 200 -> 204
~ _proc_get_ultimate_responsibility : 776 -> 780
~ _proc_get_responsible_identity : 380 -> 384
~ _responsibility_identity_retain : 76 -> 80
~ _responsibility_identity_release : 84 -> 88
~ _responsibility_identity_get_user_uuid : 40 -> 44
~ _responsibility_identity_get_persistent_identifier : 52 -> 56
~ _identity_derive_persistent_id_v0 : 396 -> 400
~ _quarantine_proc_get_tracking_data : 372 -> 376
~ _proc_get_cred_label : 144 -> 148
~ _qtnstate_rele : 136 -> 140
~ _cred_label_rele : 328 -> 332
~ _kmod_start : 96 -> 100
~ _identity_create_from_process : 144 -> 148
~ _identity_create_from_executable_vnode : 652 -> 656
~ _identity_derive_platform_data : 80 -> 84
~ _getpath : 136 -> 140
~ _identity_destroy : 168 -> 172
~ ___identity_derive_persistent_id_v0_block_invoke : 124 -> 128
~ ___identity_derive_persistent_id_v0_block_invoke_2 : 124 -> 128
~ _hook_cred_check_label_update : 148 -> 152
~ _hook_cred_label_associate : 356 -> 360
~ _hook_cred_label_destroy : 60 -> 64
~ _hook_cred_label_update_execve : 1400 -> 1404
~ _hook_cred_label_update : 292 -> 296
~ _hook_vnode_notify_setacl : 64 -> 68
~ _hook_vnode_notify_setattrlist : 64 -> 68
~ _hook_vnode_notify_setextattr : 64 -> 68
~ _hook_vnode_notify_setflags : 64 -> 68
~ _hook_vnode_notify_setmode : 64 -> 68
~ _hook_vnode_notify_setowner : 64 -> 68
~ _hook_vnode_notify_setutimes : 64 -> 68
~ _hook_vnode_notify_truncate : 68 -> 72
~ _hook_vnode_notify_swap : 616 -> 620
~ _hook_mount_notify_mount : 580 -> 584
~ _hook_mount_check_remount : 108 -> 112
~ _hook_mount_label_internalize : 212 -> 216
~ _hook_policy_init : 172 -> 176
~ _hook_policy_initbsd : 68 -> 72
~ _hook_policy_syscall : 8468 -> 8472
~ _hook_proc_notify_exec_complete : 540 -> 544
~ _hook_proc_notify_exit : 500 -> 504
~ _hook_vnode_check_exec : 100 -> 104
~ _hook_vnode_check_setextattr : 312 -> 316
~ _hook_vnode_notify_create : 980 -> 984
~ _hook_vnode_notify_rename : 728 -> 732
~ _hook_vnode_notify_deleteextattr : 64 -> 68
~ _hook_vnode_notify_open : 628 -> 632
~ _hook_vnode_notify_link : 724 -> 728
~ _responsibility_alloc : 116 -> 120
~ _responsibility_set_responsible_identity : 152 -> 156
~ _cred_label_establish_independence : 564 -> 568
~ _cred_label_set_responsibility : 204 -> 208
~ _cred_label_set_qtnstate : 76 -> 80
~ _qtnstate_establish_independence : 508 -> 512
~ _qtnstate_set_identifier : 72 -> 76
~ _qtn_taint_vnode_if_needed : 572 -> 576
~ _qtn_track_vnode_if_needed_cred : 316 -> 320
~ _quarantine_vnode_copy_info : 292 -> 296
~ _vnode_recalculate_flags : 140 -> 144
~ _quarantine_set_ea : 232 -> 236
~ _quarantine_update_flags : 212 -> 216
~ _quarantine_getinfo : 464 -> 468
~ _qtn_get_timestamp : 72 -> 76
~ _quarantine_info_parse : 180 -> 184
~ _qtn_track_vnode_if_needed : 212 -> 216
~ _vnode_update_flags : 588 -> 592
~ _getrdev : 260 -> 264
~ _syscall_quarantine_getinfo_path : 232 -> 236
~ _syscall_quarantine_setinfo_path : 276 -> 280
~ _syscall_quarantine_getprocinfo : 576 -> 580
~ _syscall_quarantine_getinfo_common : 356 -> 360
~ _syscall_quarantine_setinfo_common : 1528 -> 1532
~ _vnode_is_hardlink : 176 -> 180
~ _quarantine_get_flags : 196 -> 200
~ _proc_set_cred_label : 104 -> 108
~ _is_xpcproxy : 72 -> 76
~ _responsibility_set : 184 -> 188
~ __responsibility_set : 620 -> 624
~ ___syscall_responsibility_get_audittoken_block_invoke : 92 -> 96
~ ___copy_helper_block_8_32r40r : 80 -> 84
~ ___destroy_helper_block_8_32r40r : 68 -> 72
~ _identity_copy : 372 -> 376
~ _responsibility_copy : 128 -> 132
~ _apply_exec_quarantine : 480 -> 484
~ _mount_label_copy_quarantine_info : 104 -> 108
~ _mount_label_set_quarantine_info : 152 -> 156
~ _get_device_quarantine_info : 380 -> 384
~ __ZL27iokit_entry_for_bsddev_slowiPKc : 520 -> 524
~ _ProcessHasEntitlement : 52 -> 56
~ _entitlements_serialize : 364 -> 368
~ _is_entitled_to_retain_responsibility : 204 -> 208
~ _entitlements_remove_fda : 580 -> 584
~ _send_security_policy_mismatch_analytics : 1408 -> 1412
~ _analytics_init : 224 -> 228
~ __ZL29attach_core_analytics_servicePvS_P9IOServiceP10IONotifier : 140 -> 144
~ responsibility_get_responsible_proc.cold.1 : 20 -> 24
~ responsibility_get_responsible_proc.cold.2 : 20 -> 24
~ proc_get_responsible_identity.cold.3 : 20 -> 24
~ identity_create_from_executable_vnode.cold.1 : 80 -> 84
~ identity_create_from_executable_vnode.cold.2 : 20 -> 24
~ identity_create_from_executable_vnode.cold.3 : 24 -> 28
~ identity_destroy.cold.1 : 44 -> 48
~ responsibility_alloc.cold.1 : 44 -> 48
```
