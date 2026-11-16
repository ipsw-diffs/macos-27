## SonicAudioUnits

> `/System/Library/PrivateFrameworks/SonicAudioUnits.framework/Versions/A/SonicAudioUnits`

```diff

-26200.26.36.401.0
-  __TEXT.__text: 0x4597c
+26300.26.44.101.0
+  __TEXT.__text: 0x45bfc
   __TEXT.__objc_methlist: 0x2c
-  __TEXT.__const: 0x3d20
-  __TEXT.__gcc_except_tab: 0x1e18
-  __TEXT.__oslogstring: 0x5d4
-  __TEXT.__cstring: 0xc613
-  __TEXT.__unwind_info: 0x1a98
+  __TEXT.__const: 0x3c80
+  __TEXT.__gcc_except_tab: 0x1e80
+  __TEXT.__oslogstring: 0x616
+  __TEXT.__cstring: 0xc66c
+  __TEXT.__unwind_info: 0x1ac8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_selrefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__got: 0x110
-  __AUTH_CONST.__const: 0x34e8
+  __AUTH_CONST.__const: 0x3468
   __AUTH_CONST.__cfstring: 0x820
   __AUTH_CONST.__objc_const: 0xb8
   __AUTH_CONST.__weak_auth_got: 0x28
-  __AUTH_CONST.__auth_got: 0x4d8
+  __AUTH_CONST.__auth_got: 0x560
   __AUTH.__objc_data: 0x50
   __AUTH.__data: 0x8
   __DATA.__objc_ivar: 0x4
   __DATA.__data: 0x4d0
-  __DATA.__bss: 0x970
+  __DATA.__bss: 0x980
   __DATA.__common: 0x6a258
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1548
-  Symbols:   2139
-  CStrings:  520
+  Functions: 1551
+  Symbols:   2150
+  CStrings:  525
 
Symbols:
+ GCC_except_table48
+ __ZN12CLiveRemixer22PrepareDeferredStorageEv
+ __ZN12CLiveRemixer23ActivateDeferredStorageEv
+ __ZN23CLiveRemixerFX_Repeater14PrepareStorageEv
+ __ZN23CLiveRemixerFX_TapeStop14PrepareStorageEv
+ __ZN25AURemixExtensionDSPKernel16stopPageInWorkerEv
+ __ZN25AURemixExtensionDSPKernel17startPageInWorkerEv
+ __ZN25AURemixExtensionDSPKernel28activateDeferredFXIfPreparedEv
+ __ZN25AURemixExtensionDSPKernelD1Ev
+ __ZN25AURemixExtensionDSPKernelD2Ev
+ __ZNKSt3__126__atomic_wait_backoff_implINS_13__atomic_baseIiLb0EEEZNS_13__atomic_waitB9nqe220106IKS2_iEEvRT_T0_NS_12memory_orderEEUlRKiE_E29__update_monitor_val_and_pollB9nqe220106EPVKvRx
+ __ZNKSt3__126__atomic_wait_backoff_implINS_13__atomic_baseIiLb0EEEZNS_13__atomic_waitB9nqe220106IKS2_iEEvRT_T0_NS_12memory_orderEEUlRKiE_EclB9nqe220106ENS_6chrono8durationIxNS_5ratioILl1ELl1000000000EEEEE
+ __ZNSt3__110unique_ptrINS_15__thread_structENS_14default_deleteIS1_EEED1B9nqe220106Ev
+ __ZNSt3__110unique_ptrINS_5tupleIJNS0_INS_15__thread_structENS_14default_deleteIS2_EEEEZN25AURemixExtensionDSPKernel17startPageInWorkerEvE3$_0EEENS3_IS8_EEED1B9nqe220106Ev
+ __ZNSt3__114__thread_proxyB9nqe220106INS_5tupleIJNS_10unique_ptrINS_15__thread_structENS_14default_deleteIS3_EEEEZN25AURemixExtensionDSPKernel17startPageInWorkerEvE3$_0EEEEEPvSA_
+ __ZNSt3__115__thread_structC1Ev
+ __ZNSt3__115__thread_structD1Ev
+ __ZNSt3__119__thread_local_dataEv
+ __ZNSt3__120__libcpp_atomic_waitEPVKvx
+ __ZNSt3__120__throw_system_errorEiPKc
+ __ZNSt3__123__cxx_atomic_notify_oneEPVKv
+ __ZNSt3__123__libcpp_atomic_monitorEPVKv
+ __ZNSt3__133__libcpp_thread_poll_with_backoffB9nqe220106IZNS_20__atomic_wait_unlessB9nqe220106INS_13__atomic_baseIiLb0EEEZNS_13__atomic_waitB9nqe220106IKS3_iEEvRT_T0_NS_12memory_orderEEUlRKiE_EEvRKS6_S9_OS8_EUlvE_RNS_26__atomic_wait_backoff_implIS3_SC_EEEENS_27__poll_with_backoff_resultsEOS6_SF_NS_6chrono8durationIxNS_5ratioILl1ELl1000000000EEEEE
+ __ZNSt3__16chrono12steady_clock3nowEv
+ __ZNSt3__16thread4joinEv
+ __ZNSt3__16threadD1Ev
+ _clock_gettime_nsec_np
+ _objc_release
+ _objc_retain
+ _pthread_create
+ _pthread_set_qos_class_self_np
+ _pthread_setname_np
+ _pthread_setspecific
- GCC_except_table42
- GCC_except_table58
- GCC_except_table62
- GCC_except_table67
- __ZN12CLiveRemixer14PageInAndResetEv
- __ZN23CLiveRemixerFX_Repeater13PageInBuffersEv
- __ZN23CLiveRemixerFX_TapeStop13PageInBuffersEv
- __ZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEv
- __ZNKSt3__110__function6__funcIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0FvRNS_10unique_ptrI13CPlatinumVerbNS_14default_deleteIS5_EEEEEE11target_typeEv
- __ZNKSt3__110__function6__funcIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0FvRNS_10unique_ptrI13CPlatinumVerbNS_14default_deleteIS5_EEEEEE6targetERKSt9type_info
- __ZNKSt3__110__function6__funcIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0FvRNS_10unique_ptrI13CPlatinumVerbNS_14default_deleteIS5_EEEEEE7__cloneEPNS0_6__baseISA_EE
- __ZNKSt3__110__function6__funcIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0FvRNS_10unique_ptrI13CPlatinumVerbNS_14default_deleteIS5_EEEEEE7__cloneEv
- __ZNSt3__110__function6__funcIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0FvRNS_10unique_ptrI13CPlatinumVerbNS_14default_deleteIS5_EEEEEE18destroy_deallocateEv
- __ZNSt3__110__function6__funcIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0FvRNS_10unique_ptrI13CPlatinumVerbNS_14default_deleteIS5_EEEEEE7destroyEv
- __ZNSt3__110__function6__funcIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0FvRNS_10unique_ptrI13CPlatinumVerbNS_14default_deleteIS5_EEEEEED0Ev
- __ZNSt3__110__function6__funcIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0FvRNS_10unique_ptrI13CPlatinumVerbNS_14default_deleteIS5_EEEEEED1Ev
- __ZNSt3__110__function6__funcIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0FvRNS_10unique_ptrI13CPlatinumVerbNS_14default_deleteIS5_EEEEEEclES9_
- __ZTINSt3__110__function6__funcIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0FvRNS_10unique_ptrI13CPlatinumVerbNS_14default_deleteIS5_EEEEEEE
- __ZTIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0
- __ZTSNSt3__110__function6__funcIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0FvRNS_10unique_ptrI13CPlatinumVerbNS_14default_deleteIS5_EEEEEEE
- __ZTSZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0
- __ZTVNSt3__110__function6__funcIZN27CLiveRemixerFX_FreezeReverb13PageInBuffersEvE3$_0FvRNS_10unique_ptrI13CPlatinumVerbNS_14default_deleteIS5_EEEEEEE
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:171"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:597"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:607"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:608"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:672"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:707"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:708"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:760"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixerFX_FreezeReverb.cpp:191"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixerFX_Repeater.cpp:336"
+ "AURemixFX"
+ "AURemixFX deferred page-in"
+ "Deferred effect storage prepared off the render thread in %.2f ms"
+ "com.apple.SonicAudioUnits"
+ "thread constructor failed"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:170"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:613"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:623"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:624"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:688"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:723"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:724"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixer.cpp:776"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixerFX_FreezeReverb.cpp:200"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/SonicAudioUnits/Partner/RemixFXAudioUnit/Source/AURemixExtension/DSP/LiveRemixer/CLiveRemixerFX_Repeater.cpp:342"
```
