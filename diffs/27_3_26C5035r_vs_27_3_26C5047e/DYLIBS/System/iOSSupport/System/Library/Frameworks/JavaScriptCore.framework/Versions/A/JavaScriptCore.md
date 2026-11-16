## JavaScriptCore

> `/System/iOSSupport/System/Library/Frameworks/JavaScriptCore.framework/Versions/A/JavaScriptCore`

```diff

-626.1.12.11.4
-  __TEXT.__text: 0x1e1de70
+626.1.17.0.0
+  __TEXT.__text: 0x1e1f540
   __TEXT.__jsc_int: 0x68cf8
   __TEXT.__objc_methlist: 0xb9c
   __TEXT.__const: 0xa5664
   __TEXT.__dlsym_cstr: 0x34
-  __TEXT.__cstring: 0x10eba1
+  __TEXT.__cstring: 0x10e959
   __TEXT.__oslogstring: 0xafc
   __TEXT.__gcc_except_tab: 0x2aa8
   __TEXT.__ustring: 0x10
-  __TEXT.__unwind_info: 0x1ec28
+  __TEXT.__unwind_info: 0x1ec48
   __TEXT.__eh_frame: 0x280
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_superrefs: 0x40
   __DATA_CONST.__jsc_ops: 0x1c58
   __DATA_CONST.__got: 0x278
-  __AUTH_CONST.__const: 0x3df78
+  __AUTH_CONST.__const: 0x3dfc0
   __AUTH_CONST.__cfstring: 0x1060
   __AUTH_CONST.__objc_const: 0xdf8
   __AUTH_CONST.__weak_auth_got: 0x18
-  __AUTH_CONST.__auth_got: 0x17e8
+  __AUTH_CONST.__auth_got: 0x17f0
   __AUTH.__objc_data: 0xa0
   __AUTH.__data: 0x200
   __DATA.__objc_ivar: 0x80
   __DATA.__crash_info: 0x148
-  __DATA.__data: 0x10824
+  __DATA.__data: 0x10834
   __DATA.__common: 0x1930
   __DATA.__bss: 0x16a8
   __DATA_DIRTY.__objc_ivar: 0x8

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 39330
-  Symbols:   49392
-  CStrings:  24938
+  Functions: 39341
+  Symbols:   49407
+  CStrings:  24965
 
Symbols:
+ __ZN3JSC3FTL12_GLOBAL__N_112LowerDFGToB330substringRopeBaseImplAndOffsetEPNS_2B35ValueE
+ __ZN3WTF20MainThreadDispatcher13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEE
+ __ZN3WTF6Detail15CallableWrapperIZNS_20MainThreadDispatcher13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEEE3$_0vJEE4callEv
+ __ZN3WTF6Detail15CallableWrapperIZNS_20MainThreadDispatcher13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEEE3$_0vJEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZNS_20MainThreadDispatcher13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEEE3$_0vJEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZNS_7RunLoop13scheduleTimerENS_7SecondsEONS_8FunctionIFvvEEEE3$_0vJEE4callEv
+ __ZN3WTF6Detail15CallableWrapperIZNS_7RunLoop13scheduleTimerENS_7SecondsEONS_8FunctionIFvvEEEE3$_0vJEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZNS_7RunLoop13scheduleTimerENS_7SecondsEONS_8FunctionIFvvEEEE3$_0vJEED1Ev
+ __ZN3WTF7RunLoop13scheduleTimerENS_7SecondsEONS_8FunctionIFvvEEE
+ __ZN3WTF9WorkQueue13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZNS_20MainThreadDispatcher13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEEE3$_0vJEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZNS_7RunLoop13scheduleTimerENS_7SecondsEONS_8FunctionIFvvEEEE3$_0vJEEE
+ __ZThn24_N3WTF20SuspendableWorkQueue13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEE
+ __ZThn24_N3WTF9WorkQueue13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEE
+ ___PRETTY_FUNCTION__._ZN3WTF7RunLoop13scheduleTimerENS_7SecondsEONS_8FunctionIFvvEEE
+ _fputc
+ _pas_bitfit_participant_epoch_offsets
+ _pas_page_sharing_participant_get_use_epoch
+ _pas_report_page_config
+ _pas_segregated_participant_epoch_offsets
- __ZN3WTF6Detail15CallableWrapperIZNS_7RunLoop13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEEE3$_0vJEE4callEv
- __ZN3WTF6Detail15CallableWrapperIZNS_7RunLoop13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEEE3$_0vJEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZNS_7RunLoop13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEEE3$_0vJEED1Ev
- __ZTVN3WTF6Detail15CallableWrapperIZNS_7RunLoop13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEEE3$_0vJEEE
- ___PRETTY_FUNCTION__._ZN3WTF7RunLoop13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEE
CStrings:
+ "\n\t\t\t%s: %uB, %uB, %uB, %uB"
+ "\n\t\t%-18s %7zuB %7zuB %4zuB %8s %7zuB %8s %7zuB  %-10s %4u"
+ "\n\t\t%-18s %8s %8s %5s %8s %8s %8s %8s  %-10s %4s"
+ "\n\t\t%-18s disabled"
+ "\n\t\tRuntime Heap Config Size-Maximums (Segregated, Bitfit, Baseline Dir, No-View-Cache Dir):"
+ "\n\tForwarding to System Heap: %u"
+ "\n\tHeap-Config %s:"
+ "%.2f"
+ "%s(%d,0x%x) malloc: libpas config:\n\tDeallocation Log (Max Entries, Max Bytes): %zu, %zuB\n\tScavenger (Period, Deep-Sleep Timeout, Epoch-Delta): %.2fms, %.2fms, %llu\n\tMTE (Enabled/Lockdown/Hardened/ATE/RoS/ZTA): (%u, %u, %u, %u, %u, %u)"
+ "+MTE"
+ "Flex"
+ "Intrinsic"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22086:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22092:42)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22123:49), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22126:46)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22146:49), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22149:46)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22165:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22169:42)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22194:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22198:42)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22223:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22227:42)]"
+ "Marge Bitfit"
+ "Medium Bitfit"
+ "Medium Segregated"
+ "Page Configs:"
+ "Primitive"
+ "Ref<RunLoop::DispatchTimer> WTF::RunLoop::scheduleTimer(Seconds, Function<void ()> &&)"
+ "Small Bitfit"
+ "Small Segregated"
+ "Typed"
+ "align"
+ "cap %zu"
+ "granule"
+ "handicap"
+ "max obj"
+ "min-objs"
+ "utility"
+ "view-cache"
- "%s(%d,0x%x) malloc: libpas config:\n\tDeallocation Log (Max Entries, Max Bytes): %zu, %zuB\n\tScavenger (Period, Deep-Sleep Timeout, Epoch-Delta): %.2fms, %.2fms, %llu\n\tMTE (Enabled/Lockdown/Hardened/ATE/RoS/ZTA): (%u, %u, %u, %u, %u, %u)\n\tForwarding to System Heap: %u\n\tHeap-Config bmalloc:\n\t\tPage Configs (Enabled/MTE Taggable, Static Max Obj Size):\n\t\t\tSmall Segregated: %u/%u, %zuB\n\t\t\tMedium Segregated: %u/%u, %zuB\n\t\t\tSmall Bitfit: %u/%u, %zuB\n\t\t\tMedium Bitfit : %u/%u, %zuB\n\t\t\tMarge Bitfit : %u/%u, %zuB\n\t\tRuntime Heap Config Size-Maximums (Segregated, Bitfit, Baseline Dir, No-View-Cache Dir):\n\t\t\tFlex: %uB, %uB, %uB, %uB\n\t\t\tIntrinsic: %uB, %uB, %uB, %uB\n\t\t\tTyped: %uB, %uB, %uB, %uB\n\t\t\tPrimitive: %uB, %uB, %uB, %uB\n\tHeap-Config jit:\n\t\tPage Configs (Enabled/MTE Taggable, Static Max Obj Size):\n\t\t\tSmall Segregated: %u/%u, %zuB\n\t\t\tMedium Segregated: %u/%u, %zuB\n\t\t\tSmall Bitfit: %u/%u, %zuB\n\t\t\tMedium Bitfit : %u/%u, %zuB\n\t\t\tMarge Bitfit : %u/%u, %zuB\n\t\tRuntime Heap Config Size-Maximums (Segregated, Bitfit, Baseline Dir, No-View-Cache Dir):\n\t\t\tFlex: %uB, %uB, %uB, %uB\n\tHeap-Config utility:\n\t\tPage Configs (Enabled/MTE Taggable, Static Max Obj Size):\n\t\t\tSmall Segregated: %u/%u, %zuB\n\t\t\tMedium Segregated: %u/%u, %zuB\n\t\t\tSmall Bitfit: %u/%u, %zuB\n\t\t\tMedium Bitfit : %u/%u, %zuB\n\t\t\tMarge Bitfit : %u/%u, %zuB\n"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22037:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22043:42)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22074:49), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22077:46)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22097:49), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22100:46)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22116:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22120:42)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22145:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22149:42)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22174:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:22178:42)]"
- "Ref<RunLoop::DispatchTimer> WTF::RunLoop::dispatchAfter(Seconds, Function<void ()> &&)"
```
