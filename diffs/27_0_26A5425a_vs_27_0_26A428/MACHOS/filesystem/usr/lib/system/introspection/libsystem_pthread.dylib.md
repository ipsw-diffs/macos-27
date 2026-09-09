## libsystem_pthread.dylib

> `/usr/lib/system/introspection/libsystem_pthread.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__dof_plockstat`
- `__DATA_DIRTY.__data`

```diff

 553.0.1.0.0
-  __TEXT.__text: 0xb270
+  __TEXT.__text: 0xadfc
   __TEXT.__auth_stubs: 0x460
   __TEXT.__const: 0x150
   __TEXT.__cstring: 0xe11
   __TEXT.__dof_plockstat: 0x16af
-  __TEXT.__unwind_info: 0x340
+  __TEXT.__unwind_info: 0x438
   __DATA_CONST.__auth_got: 0x230
   __DATA_CONST.__got: 0x38
   __DATA_CONST.__auth_ptr: 0x8
Functions:
~ __pthread_start : 320 -> 300
~ _pthread_mach_thread_np : 256 -> 216
~ _pthread_get_stacksize_np : 388 -> 368
~ _pthread_get_stackaddr_np : 212 -> 192
~ _pthread_threadid_np : 256 -> 236
~ _pthread_getname_np : 240 -> 220
~ _pthread_setname_np : 204 -> 184
~ _pthread_jit_write_with_callback_np : 304 -> 292
~ _pthread_jit_write_freeze_callbacks_np : 156 -> 144
~ _pthread_create_with_workgroup_np : 48 -> 36
~ _pthread_detach : 284 -> 264
~ _pthread_kill : 504 -> 444
~ ___pthread_workqueue_setkill : 208 -> 176
~ _pthread_exit : 144 -> 124
~ _pthread_getschedparam : 212 -> 192
~ _pthread_setschedparam : 572 -> 512
~ __pthread_set_self : 100 -> 88
~ __pthread_bsdthread_init : 304 -> 292
~ ___pthread_late_init : 112 -> 100
~ __pthread_clear_qos_tsd : 152 -> 140
~ __pthread_wqthread_setup : 560 -> 548
~ __pthread_wqthread_legacy_worker_wrap : 184 -> 180
~ _OUTLINED_FUNCTION_0 : 36 -> 24
~ _pthread_cancel : 368 -> 328
~ _pthread_setcancelstate : 180 -> 160
~ _pthread_setcanceltype : 144 -> 124
~ __pthread_exit_if_canceled : 136 -> 116
~ __pthread_join : 1040 -> 1000
~ _pthread_cond_signal_thread_np : 912 -> 900
~ __pthread_psynch_cond_cleanup : 92 -> 80
~ __pthread_mutex_lock_init_slow : 188 -> 152
~ _pthread_mutex_unlock : 264 -> 228
~ __pthread_mutex_unlock_init_slow : 164 -> 140
~ __pthread_mutex_fairshare_unlock : 176 -> 164
~ _pthread_mutex_lock : 312 -> 264
~ _pthread_mutex_trylock : 308 -> 260
~ __pthread_mutex_fairshare_lock : 208 -> 196
~ _pthread_attr_get_qos_class_np : 164 -> 160
~ _pthread_set_qos_class_self_np : 112 -> 100
~ __pthread_set_properties_self : 244 -> 224
~ _pthread_set_qos_class_np : 116 -> 84
~ _pthread_get_qos_class_np : 108 -> 104
~ _qos_class_self : 68 -> 64
~ _qos_class_main : 68 -> 64
~ __pthread_qos_class_decode : 100 -> 96
~ __pthread_qos_class_and_override_decode : 176 -> 172
~ _pthread_qos_max_parallelism : 372 -> 368
~ _pthread_rwlock_rdlock : 216 -> 204
~ _pthread_rwlock_tryrdlock : 252 -> 240
~ _pthread_rwlock_wrlock : 208 -> 196
~ _pthread_rwlock_trywrlock : 220 -> 208
~ _pthread_self : 76 -> 56
~ _pthread_join : 68 -> 56
~ __pthread_atfork_prepare : 136 -> 124
~ __pthread_atfork_parent : 120 -> 108
~ __pthread_atfork_parent_handlers : 160 -> 148
~ __pthread_fork_prepare : 40 -> 28
~ __pthread_fork_parent : 40 -> 28
~ pthread_testcancel.cold.1 : 84 -> 64
~ __pthread_ulock_cond_cleanup : 76 -> 68
~ _pthread_qos_class_and_override_decode.cold.1 : 88 -> 84
~ _pthread_rwlock_unlock : 276 -> 264
```
