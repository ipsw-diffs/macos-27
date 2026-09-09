## pthread

> `/System/KernelKit/System/Library/Extensions/pthread.kext/pthread`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA_CONST.__const`

```diff

 553.0.1.0.0
   __TEXT.__const: 0x40
   __TEXT.__cstring: 0x72d
-  __TEXT_EXEC.__text: 0x6438
+  __TEXT_EXEC.__text: 0x6440
   __TEXT_EXEC.__auth_stubs: 0x370
   __DATA.__data: 0x13c
   __DATA.__bss: 0x21
Symbols:
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-normal/arm64e.x1/kern_support-c6b2061c1651b7643c7ea2fc4132b794.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-normal/arm64e.x1/pthread.swiftmodule
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-normal/arm64e.x1/pthread_lto.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-normal/arm64e/kern_support-7aaf8b5f66b24f01927e37aebf82536a.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-normal/arm64e/pthread.swiftmodule
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libpthread_kernelkit/install/TempContent/Objects/libpthread.build/pthread kext.build/Objects-normal/arm64e/pthread_lto.o
Functions:
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
~ __bsdthread_create : 1216 -> 1220
~ __pthread_priority_to_policy : 76 -> 72
~ __bsdthread_terminate : 580 -> 584
~ __bsdthread_register : 1224 -> 1220
~ _workq_create_threadstack : 276 -> 280
~ _workq_thread_allocsize : 128 -> 132
~ _workq_destroy_threadstack : 72 -> 64
~ _workq_markfree_threadstack : 124 -> 116
~ _workq_setup_thread : 532 -> 536
~ _workq_set_register_state : 396 -> 400
~ _workq_handle_stack_events : 300 -> 304
~ __pthread_init : 220 -> 224
~ _pthread_start : 44 -> 48
~ _current_uthread : 56 -> 48
~ __psynch_mutexwait : 1060 -> 1064
~ _ksyn_wqfind : 1264 -> 1268
~ _ksyn_wait : 444 -> 448
~ _ksyn_wqrelease : 636 -> 628
~ __kwq_destroy : 88 -> 80
~ _ksyn_queue_insert : 876 -> 880
~ _psynch_mtxcontinue : 304 -> 308
~ _ksyn_queue_remove_item : 564 -> 568
~ _ksyn_wqunlock : 72 -> 64
~ __kwq_report_inuse : 536 -> 528
~ __psynch_mutexdrop : 800 -> 804
~ _ksyn_mtxsignal : 336 -> 340
~ _ksyn_signal : 260 -> 264
~ __psynch_cvbroad : 208 -> 200
~ ___psynch_cvsignal : 1892 -> 1896
~ _ksyn_handle_cvbroad : 1064 -> 1068
~ _ksyn_cvupdate_fixup : 136 -> 140
~ _ksyn_queue_free_items : 532 -> 524
~ __psynch_cvwait : 1076 -> 1080
~ _psynch_cvcontinue : 600 -> 604
~ __psynch_cvclrprepost : 444 -> 448
~ ___psynch_rw_lock : 772 -> 776
~ __ksyn_check_init : 72 -> 76
~ _kwq_handle_unlock : 1064 -> 1068
~ _psynch_rw_rdcontinue : 24 -> 28
~ __psynch_rw_continue : 228 -> 232
~ _psynch_rw_wrcontinue : 24 -> 28
~ __psynch_rw_unlock : 672 -> 676
~ _pth_global_hashinit : 48 -> 52
~ __pth_proc_hashinit : 132 -> 124
~ __pth_proc_hashdelete : 596 -> 588
~ _psynch_wq_cleanup : 492 -> 496
~ __pthread_get_thread_kwq : 68 -> 72
~ __pthread_find_owner : 144 -> 148
```
