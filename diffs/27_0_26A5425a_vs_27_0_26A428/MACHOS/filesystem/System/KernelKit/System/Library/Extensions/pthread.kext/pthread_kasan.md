## pthread_kasan

> `/System/KernelKit/System/Library/Extensions/pthread.kext/pthread_kasan`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA_CONST.__const`

```diff

 553.0.1.0.0
   __TEXT.__cstring: 0x72d
-  __TEXT_EXEC.__text: 0x8d4c
+  __TEXT_EXEC.__text: 0x8dd4
   __TEXT_EXEC.__auth_stubs: 0x440
   __DATA.__data: 0x148
   __DATA.__bss: 0x21
Symbols:
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-kasan/arm64e.x1/kern_init.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-kasan/arm64e.x1/kern_support-831a2fddce75636b2a90ea24768301f1.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-kasan/arm64e.x1/kern_support-c6b2061c1651b7643c7ea2fc4132b794.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-kasan/arm64e.x1/kern_synch.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-kasan/arm64e.x1/pthread.swiftmodule
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-kasan/arm64e.x1/pthread_info.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-kasan/arm64e/kern_init.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-kasan/arm64e/kern_support-3e2e773c0623037ee1adfd5edecc6a8f.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-kasan/arm64e/kern_support-7aaf8b5f66b24f01927e37aebf82536a.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-kasan/arm64e/kern_synch.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-kasan/arm64e/pthread.swiftmodule
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-kasan/arm64e/pthread_info.o
Functions:
~ __bsdthread_create : 2088 -> 2092
~ __bsdthread_terminate : 636 -> 640
~ __bsdthread_register : 1640 -> 1636
~ _stack_addr_hint : 264 -> 256
~ _workq_create_threadstack : 436 -> 440
~ _workq_thread_allocsize : 160 -> 164
~ _workq_destroy_threadstack : 72 -> 64
~ _workq_markfree_threadstack : 112 -> 104
~ _workq_setup_thread : 492 -> 496
~ _workq_thread_get_addrs : 92 -> 96
~ _workq_kevent : 388 -> 392
~ _workq_set_register_state : 664 -> 668
~ _workq_handle_stack_events : 384 -> 388
~ __pthread_init : 320 -> 324
~ _workq_thread_set_top_addr : 48 -> 52
~ _pthread_start : 44 -> 48
~ _current_uthread : 80 -> 72
~ __psynch_mutexwait : 1052 -> 1056
~ _ksyn_wqfind : 1584 -> 1588
~ __kwq_handle_interrupted_wakeup : 200 -> 204
~ __kwq_set_owner : 108 -> 112
~ _ksyn_wqunlock : 84 -> 76
~ __kwq_clear_preposted_wakeup : 72 -> 76
~ _ksyn_wait : 588 -> 592
~ _psynch_mtxcontinue : 340 -> 344
~ _ksyn_wqrelease : 880 -> 884
~ __psynch_mutexdrop : 160 -> 164
~ __psynch_mutexdrop_internal : 812 -> 804
~ __psynch_cvbroad : 220 -> 212
~ ___psynch_cvsignal : 780 -> 784
~ __psynch_cvwait : 1236 -> 1240
~ _UPDATE_CVKWQ : 292 -> 296
~ _ksyn_queue_find_cvpreposeq : 128 -> 132
~ _ksyn_queue_remove_item : 632 -> 636
~ _ksyn_handle_cvbroad : 1320 -> 1324
~ _ksyn_cvupdate_fixup : 248 -> 252
~ _psynch_cvcontinue : 764 -> 768
~ __psynch_cvclrprepost : 436 -> 440
~ _ksyn_queue_free_items : 628 -> 620
~ ___psynch_rw_lock : 356 -> 360
~ __psynch_rw_unlock : 536 -> 540
~ __ksyn_check_init : 104 -> 108
~ _find_diff : 88 -> 92
~ _find_seq_till : 140 -> 144
~ _kwq_handle_unlock : 884 -> 888
~ __kwq_mark_preposted_wakeup : 88 -> 92
~ _pth_global_hashinit : 48 -> 52
~ __pth_proc_hashinit : 156 -> 148
~ __pth_proc_hashdelete : 648 -> 624
~ _ksyn_freeallkwe : 264 -> 268
~ __kwq_destroy : 100 -> 92
~ _psynch_wq_cleanup : 844 -> 848
~ __kwq_is_used : 92 -> 96
~ __pthread_get_thread_kwq : 124 -> 128
~ __pthread_find_owner : 196 -> 200
~ __kwq_clear_interrupted_wakeup : 80 -> 84
~ _ksyn_mtxsignal : 380 -> 384
~ __kwq_cleanup_old_owner : 60 -> 64
~ __kwq_mark_interruped_wakeup : 112 -> 116
~ _ksyn_queue_find_seq : 80 -> 84
~ _ksyn_signal : 304 -> 308
~ __kwq_use_turnstile : 32 -> 36
~ __kwq_type : 44 -> 48
~ __ksyn_cvsignal_thread : 328 -> 332
~ __ksyn_cvsignal_any : 512 -> 516
~ _ksyn_signal_thread : 244 -> 248
~ _ksyn_queue_find_signalseq : 400 -> 404
~ _ksyn_prepost : 156 -> 160
~ _ksyn_queue_insert : 1172 -> 1176
~ _update_low_high : 152 -> 156
~ _psynch_rw_rdcontinue : 24 -> 28
~ _psynch_rw_wrcontinue : 24 -> 28
~ __kwq_handle_overlap : 192 -> 196
~ __kwq_handle_preposted_wakeup : 256 -> 260
~ __psynch_rw_continue : 248 -> 252
~ _CLEAR_REINIT_BITS : 304 -> 308
~ _ksyn_findobj : 372 -> 376
~ _ksyn_wq_hash_lookup : 328 -> 332
~ _ksyn_queue_init : 88 -> 92
~ __kwq_report_inuse : 872 -> 864
~ _kwq_find_rw_lowest : 756 -> 760
~ _ksyn_queue_count_tolowest : 184 -> 188
~ _ksyn_wakeupreaders : 204 -> 208
~ _find_nextlowseq : 152 -> 156
~ _find_nexthighseq : 152 -> 156
~ __thread_selfid : 68 -> 72
~ _swift_initStackObject : 56 -> 60
~ _swift_initStaticObject : 56 -> 60
~ _swift_isUniquelyReferenced_native : 40 -> 36
~ _swift_isUniquelyReferenced_nonNull_native : 24 -> 20
~ _swift_isEscapingClosureAtFileLocation : 44 -> 40
~ _swift_dynamicCastClass : 76 -> 80
~ __swift_embedded_get_heap_object_metadata_pointer : 60 -> 40
~ _swift_dynamicCastClassUnconditional : 72 -> 76
~ _swift_dynamicCast : 132 -> 136
~ _$es7tryCast33_8BFEAB69C69C8B87ED137407D82370D4LL3dst0J8Metadata3src0lK013takeOnSuccesss07DynamicB6ResultABLLOSv_S3VSbtF : 304 -> 308
~ _$es29ExistentialTypeRepresentationO7projectySV8metadata_SV5valuetSVF : 156 -> 164
~ _swift_getErrorValue : 108 -> 112
~ __swift_embedded_metadata_get_align_mask : 48 -> 28
~ _swift_retainCount : 36 -> 32
~ __swift_embedded_metadata_get_vwt_flags : 48 -> 28
```
