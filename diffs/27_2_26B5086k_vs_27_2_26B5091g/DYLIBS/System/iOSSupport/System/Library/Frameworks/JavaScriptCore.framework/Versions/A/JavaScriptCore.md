## JavaScriptCore

> `/System/iOSSupport/System/Library/Frameworks/JavaScriptCore.framework/Versions/A/JavaScriptCore`

```diff

-625.2.4.1.0
-  __TEXT.__text: 0x1dca318
+625.2.5.11.1
+  __TEXT.__text: 0x1dcc038
   __TEXT.__jsc_int: 0x6a3b8
   __TEXT.__objc_methlist: 0xb9c
   __TEXT.__const: 0x9f554
   __TEXT.__dlsym_cstr: 0x34
-  __TEXT.__cstring: 0x12bfa8
+  __TEXT.__cstring: 0x12c047
   __TEXT.__oslogstring: 0xa0f
   __TEXT.__gcc_except_tab: 0x2968
   __TEXT.__ustring: 0x10
-  __TEXT.__unwind_info: 0x1e890
+  __TEXT.__unwind_info: 0x1e8a0
   __TEXT.__eh_frame: 0xc0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH_CONST.__objc_const: 0xdf8
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__auth_got: 0x17f0
-  __AUTH.__objc_data: 0xf0
-  __AUTH.__data: 0x250
+  __AUTH.__objc_data: 0xa0
+  __AUTH.__data: 0x200
   __DATA.__objc_ivar: 0x80
   __DATA.__crash_info: 0x148
-  __DATA.__data: 0x104b4
-  __DATA.__common: 0x1830
+  __DATA.__data: 0x103fc
+  __DATA.__common: 0x1828
   __DATA.__bss: 0x14e8
   __DATA_DIRTY.__objc_ivar: 0x8
-  __DATA_DIRTY.__objc_data: 0x280
-  __DATA_DIRTY.__data: 0x13fa9
+  __DATA_DIRTY.__objc_data: 0x2d0
+  __DATA_DIRTY.__data: 0x140b1
   __DATA_DIRTY.__wtf_config: 0x4000
   __DATA_DIRTY.__jsc_opcodes: 0x4000
-  __DATA_DIRTY.__common: 0x4852b8
+  __DATA_DIRTY.__common: 0x4852c0
   __DATA_DIRTY.__bss: 0xc0b0
   - /System/Library/Frameworks/BrowserEngineCore.framework/Versions/A/BrowserEngineCore
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 38974
-  Symbols:   48138
-  CStrings:  25785
+  Functions: 38978
+  Symbols:   48142
+  CStrings:  25790
 
Symbols:
+ __ZN3JSC4Wasm14IPIntGenerator23branchTargetMetadataForERKNS0_16IPIntControlTypeEj
+ __ZN3JSCL21functionWasmCalleeIDsEPNS_14JSGlobalObjectEPNS_9CallFrameE
+ __ZN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_3vJRNS2_17DeferredWorkTimer6TicketEEE4callESA_
+ __ZN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_3vJRNS2_17DeferredWorkTimer6TicketEEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_3vJRNS2_17DeferredWorkTimer6TicketEEED1Ev
+ __ZNK3JSC4Wasm11CalleeGroup18calleeIsReferencedERKN3WTF14AbstractLockerEPNS0_6CalleeE
+ __ZNK3JSC4Wasm14IPIntGenerator4failIJPKcjS4_tEEENSt3__110unexpectedIN3WTF6StringEEEDpT_
+ __ZTVN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_3vJRNS2_17DeferredWorkTimer6TicketEEEE
- __ZN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_2vJRNS2_17DeferredWorkTimer6TicketEEE4callESA_
- __ZN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_2vJRNS2_17DeferredWorkTimer6TicketEEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_2vJRNS2_17DeferredWorkTimer6TicketEEED1Ev
- __ZTVN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_2vJRNS2_17DeferredWorkTimer6TicketEEEE
CStrings:
+ " max: "
+ "Branch target would discard too many stack values: "
+ "Expected an exported WebAssembly function"
+ "Exported function has no callee group yet"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21665:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21671:42)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21702:49), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21705:46)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21725:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21729:42)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21754:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21758:42)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21783:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21787:42)]"
+ "TriState JSC::Wasm::CalleeGroup::calleeIsReferenced(const AbstractLocker &, Wasm::Callee *) const"
+ "auto JSC::FTL::(anonymous namespace)::LowerDFGToB3::compileCallOrConstructVarargsSpread()::(anonymous class)::operator()(auto, Node *) const [self:auto = std::reference_wrapper<const WTF::RecursableLambda<(lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:14335:70)>>]"
+ "auto JSC::FTL::(anonymous namespace)::LowerDFGToB3::compileForwardVarargsWithSpread()::(anonymous class)::operator()(auto, Node *, LValue) const [self:auto = std::reference_wrapper<const WTF::RecursableLambda<(lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:15377:47)>>]"
+ "void JSC::DFG::clobberize(Graph &, Node *, const ReadFunctor &, const WriteFunctor &, const DefFunctor &, const ClobberTopFunctor &) [ReadFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/dfg/DFGStoreBarrierInsertionPhase.cpp:522:33), WriteFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/dfg/DFGStoreBarrierInsertionPhase.cpp:537:34), DefFunctor = JSC::DFG::NoOpClobberize, ClobberTopFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/dfg/DFGClobberize.h:45:47)]"
+ "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13753:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13756:13)]"
+ "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13767:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13770:13)]"
+ "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13781:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13784:13)]"
+ "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13795:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13798:13)]"
+ "wasmCalleeIDs"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21659:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21665:42)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21696:49), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21699:46)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21719:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21723:42)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21748:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21752:42)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21777:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21781:42)]"
- "ToType WTF::safeCast(FromType) [ToType = unsigned short, FromType = WTF::Checked<unsigned int>]"
- "auto JSC::FTL::(anonymous namespace)::LowerDFGToB3::compileCallOrConstructVarargsSpread()::(anonymous class)::operator()(auto, Node *) const [self:auto = std::reference_wrapper<const WTF::RecursableLambda<(lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:14329:70)>>]"
- "auto JSC::FTL::(anonymous namespace)::LowerDFGToB3::compileForwardVarargsWithSpread()::(anonymous class)::operator()(auto, Node *, LValue) const [self:auto = std::reference_wrapper<const WTF::RecursableLambda<(lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:15371:47)>>]"
- "void JSC::DFG::clobberize(Graph &, Node *, const ReadFunctor &, const WriteFunctor &, const DefFunctor &, const ClobberTopFunctor &) [ReadFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/dfg/DFGStoreBarrierInsertionPhase.cpp:514:33), WriteFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/dfg/DFGStoreBarrierInsertionPhase.cpp:529:34), DefFunctor = JSC::DFG::NoOpClobberize, ClobberTopFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/dfg/DFGClobberize.h:45:47)]"
- "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13747:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13750:13)]"
- "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13761:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13764:13)]"
- "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13775:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13778:13)]"
- "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13789:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_iosmac/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13792:13)]"
```
