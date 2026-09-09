## pthread_development

> `/System/KernelKit/System/Library/Extensions/pthread.kext/pthread_development`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA_CONST.__const`

```diff

   __TEXT.__const: 0x40
   __TEXT.__cstring: 0x834
   __TEXT.__os_log: 0x95
-  __TEXT_EXEC.__text: 0x6838
+  __TEXT_EXEC.__text: 0x6884
   __TEXT_EXEC.__auth_stubs: 0x380
   __DATA.__data: 0x148
   __DATA.__bss: 0x21
Symbols:
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-development/arm64e.x1/kern_init.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-development/arm64e.x1/kern_support-831a2fddce75636b2a90ea24768301f1.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-development/arm64e.x1/kern_support-c6b2061c1651b7643c7ea2fc4132b794.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-development/arm64e.x1/kern_synch.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-development/arm64e.x1/pthread.swiftmodule
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-development/arm64e.x1/pthread_info.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-development/arm64e/kern_init.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-development/arm64e/kern_support-3e2e773c0623037ee1adfd5edecc6a8f.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-development/arm64e/kern_support-7aaf8b5f66b24f01927e37aebf82536a.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-development/arm64e/kern_synch.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-development/arm64e/pthread.swiftmodule
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-development/arm64e/pthread_info.o
Functions:
~ __bsdthread_create : 1220 -> 1224
~ __pthread_priority_to_policy : 76 -> 72
~ __bsdthread_terminate : 680 -> 684
~ __bsdthread_register : 1228 -> 1224
~ _workq_create_threadstack : 280 -> 284
~ _workq_thread_allocsize : 132 -> 136
~ _workq_destroy_threadstack : 72 -> 64
~ _workq_markfree_threadstack : 164 -> 168
~ _workq_setup_thread : 536 -> 540
~ _workq_set_register_state : 376 -> 380
~ _workq_handle_stack_events : 312 -> 316
~ __pthread_init : 204 -> 208
~ _pthread_start : 44 -> 48
~ _current_uthread : 56 -> 48
~ __psynch_mutexwait : 1068 -> 1072
~ _ksyn_wqfind : 1288 -> 1292
~ _ksyn_wqunlock : 76 -> 68
~ _ksyn_wait : 264 -> 268
~ _psynch_mtxcontinue : 292 -> 296
~ _ksyn_wqrelease : 608 -> 600
~ __psynch_mutexdrop : 808 -> 812
~ __psynch_cvbroad : 212 -> 204
~ ___psynch_cvsignal : 776 -> 780
~ __psynch_cvwait : 1080 -> 1084
~ _ksyn_queue_remove_item : 508 -> 512
~ _ksyn_handle_cvbroad : 1004 -> 1008
~ _ksyn_cvupdate_fixup : 136 -> 140
~ _psynch_cvcontinue : 596 -> 600
~ __psynch_cvclrprepost : 456 -> 460
~ _ksyn_queue_free_items : 536 -> 528
~ ___psynch_rw_lock : 776 -> 780
~ __psynch_rw_unlock : 676 -> 680
~ __ksyn_check_init : 72 -> 76
~ _kwq_handle_unlock : 1032 -> 1036
~ _pth_global_hashinit : 48 -> 52
~ __pth_proc_hashinit : 104 -> 96
~ __pth_proc_hashdelete : 600 -> 592
~ __kwq_destroy : 92 -> 84
~ _psynch_wq_cleanup : 492 -> 496
~ __pthread_get_thread_kwq : 96 -> 100
~ __pthread_find_owner : 160 -> 164
~ _ksyn_mtxsignal : 308 -> 312
~ _ksyn_signal : 216 -> 220
~ _ksyn_cvsignal : 1068 -> 1072
~ _ksyn_prepost : 92 -> 96
~ _ksyn_queue_insert : 848 -> 852
~ _psynch_rw_rdcontinue : 24 -> 28
~ _psynch_rw_wrcontinue : 24 -> 28
~ __psynch_rw_continue : 216 -> 220
~ __kwq_report_inuse : 540 -> 532
~ _OUTLINED_FUNCTION_0 : 36 -> 24
~ _OUTLINED_FUNCTION_1 : 36 -> 24
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
~ workq_set_register_state.cold.1 : 44 -> 48
~ ksyn_wait.cold.1 : 264 -> 268
~ ksyn_wqrelease.cold.1 : 44 -> 48
~ _psynch_cvwait.cold.1 : 44 -> 48
~ ksyn_queue_remove_item.cold.1 : 44 -> 48
~ ksyn_queue_remove_item.cold.2 : 44 -> 48
~ ksyn_handle_cvbroad.cold.1 : 24 -> 28
~ kwq_handle_unlock.cold.1 : 44 -> 48
~ _pth_proc_hashinit.cold.1 : 44 -> 48
~ ksyn_mtxsignal.cold.1 : 44 -> 48
~ ksyn_signal.cold.1 : 24 -> 28
~ ksyn_signal.cold.2 : 44 -> 48
~ ksyn_cvsignal.cold.1 : 24 -> 28
~ ksyn_cvsignal.cold.2 : 52 -> 56
~ ksyn_cvsignal.cold.3 : 52 -> 56
~ ksyn_cvsignal.cold.4 : 24 -> 28
~ ksyn_cvsignal.cold.5 : 44 -> 48
~ ksyn_queue_insert.cold.1 : 44 -> 48
```
