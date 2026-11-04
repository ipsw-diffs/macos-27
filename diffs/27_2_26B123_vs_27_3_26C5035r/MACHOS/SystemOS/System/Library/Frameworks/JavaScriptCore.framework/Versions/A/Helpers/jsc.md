## jsc

> `/System/Library/Frameworks/JavaScriptCore.framework/Versions/A/Helpers/jsc`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

-625.2.8.11.9
-  __TEXT.__text: 0x36228
-  __TEXT.__auth_stubs: 0x1840
-  __TEXT.__const: 0x260
-  __TEXT.__cstring: 0x6e20
-  __DATA_CONST.__const: 0x1748
+626.1.12.11.4
+  __TEXT.__text: 0x4ed38
+  __TEXT.__auth_stubs: 0x1b40
+  __TEXT.__const: 0x278
+  __TEXT.__cstring: 0x7675
+  __DATA_CONST.__const: 0x1750
   __DATA_CONST.__jsc_ops: 0x0
-  __DATA_CONST.__auth_got: 0xc20
-  __DATA_CONST.__got: 0x98
+  __DATA_CONST.__auth_got: 0xda0
+  __DATA_CONST.__got: 0xe8
   __DATA.__data: 0x10
   __DATA.__bss: 0xb8
   - /System/Library/Frameworks/JavaScriptCore.framework/Versions/A/JavaScriptCore
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libedit.3.dylib
-  Functions: 320
-  Symbols:   442
-  CStrings:  925
+  Functions: 432
+  Symbols:   499
+  CStrings:  944
 
Symbols:
+ __ZN3JSC10CachedCallC1EPNS_14JSGlobalObjectEPNS_10JSFunctionEi
+ __ZN3JSC10Identifier4fromERNS_2VMEj
+ __ZN3JSC11ArrayBuffer9shareWithERNS_19ArrayBufferContentsE
+ __ZN3JSC11ArrayBuffer9tryCreateENSt3__14spanIKhLm18446744073709551615EEE
+ __ZN3JSC12BigIntObject6createERNS_2VMEPNS_14JSGlobalObjectENS_7JSValueE
+ __ZN3JSC12BigIntObject6s_infoE
+ __ZN3JSC12DateInstance14finishCreationERNS_2VMEd
+ __ZN3JSC12DateInstance6s_infoE
+ __ZN3JSC12DateInstanceC1ERNS_2VMEPNS_9StructureE
+ __ZN3JSC12RegExpObjectC1ERNS_2VMEPNS_9StructureEPNS_6RegExpEb
+ __ZN3JSC12VMEntryScope12tearDownSlowEv
+ __ZN3JSC12iteratorStepEPNS_14JSGlobalObjectENS_15IterationRecordE
+ __ZN3JSC13BooleanObject6s_infoE
+ __ZN3JSC13BooleanObjectC1ERNS_2VMEPNS_9StructureE
+ __ZN3JSC13ErrorInstance6createEPNS_14JSGlobalObjectEON3WTF6StringENS_9ErrorTypeENS_10LineColumnES5_S5_S5_
+ __ZN3JSC13ErrorInstance6s_infoE
+ __ZN3JSC13JSMapIterator14finishCreationERNS_2VMEPNS_5JSMapENS_13IterationKindE
+ __ZN3JSC13JSSetIterator14finishCreationERNS_2VMEPNS_5JSSetENS_13IterationKindE
+ __ZN3JSC13iteratorCloseEPNS_14JSGlobalObjectENS_7JSValueE
+ __ZN3JSC13iteratorValueEPNS_14JSGlobalObjectENS_7JSValueE
+ __ZN3JSC14StructureCache32emptyObjectStructureForPrototypeEPNS_14JSGlobalObjectEPNS_8JSObjectEjbPNS_18FunctionExecutableE
+ __ZN3JSC15ArrayBufferView4wrapEPNS_14JSGlobalObjectES2_
+ __ZN3JSC15JSArrayIterator6createERNS_2VMEPNS_9StructureEPNS_8JSObjectENS_7JSValueE
+ __ZN3JSC15JSBoundFunction6s_infoE
+ __ZN3JSC15ObjectPrototype6s_infoE
+ __ZN3JSC15constructNumberEPNS_14JSGlobalObjectENS_7JSValueE
+ __ZN3JSC15constructStringERNS_2VMEPNS_14JSGlobalObjectENS_7JSValueE
+ __ZN3JSC16MarkedVectorBase10slowAppendENS_7JSValueE
+ __ZN3JSC16MarkedVectorBase29m_storageForOutOfBoundsAccessE
+ __ZN3JSC16getIterationModeENS_7JSValueE
+ __ZN3JSC17DeferredWorkTimer24scheduleWorkSoonIfActiveERKN3WTF17ThreadSafeWeakPtrINS0_6TicketEEEONS1_8FunctionIFvRS3_EEE
+ __ZN3JSC17JSArrayBufferView18possiblySharedImplEv
+ __ZN3JSC18constructArrayPairEPNS_14JSGlobalObjectENS_7JSValueES2_
+ __ZN3JSC19WebAssemblyFunction6s_infoE
+ __ZN3JSC19iteratorForIterableEPNS_14JSGlobalObjectENS_7JSValueE
+ __ZN3JSC24createStackOverflowErrorEPNS_14JSGlobalObjectE
+ __ZN3JSC26iteratorStepWithCachedCallEPNS_14JSGlobalObjectENS_15IterationRecordEPNS_10CachedCallE
+ __ZN3JSC29createNotEnoughArgumentsErrorEPNS_14JSGlobalObjectE
+ __ZN3JSC40extractErrorInformationFromErrorInstanceEPNS_14JSGlobalObjectERNS_13ErrorInstanceE
+ __ZN3JSC4Yarr10parseFlagsEN3WTF10StringViewE
+ __ZN3JSC4Yarr11flagsStringEN3WTF9OptionSetINS0_5FlagsELNS1_14ConcurrencyTagE0EEE
+ __ZN3JSC6RegExp6createERNS_2VMERKN3WTF6StringENS3_9OptionSetINS_4Yarr5FlagsELNS3_14ConcurrencyTagE0EEE
+ __ZN3JSC8DataView9wrappedAsEON3WTF3RefINS_11ArrayBufferENS1_12RawPtrTraitsIS3_EENS1_21DefaultRefDerefTraitsIS3_EEEEmNSt3__18optionalImEE
+ __ZN3JSC8GCClient4Heap12mapSpaceSlowEv
+ __ZN3JSC8GCClient4Heap12setSpaceSlowEv
+ __ZN3JSC8GCClient4Heap20mapIteratorSpaceSlowEv
+ __ZN3JSC8GCClient4Heap20setIteratorSpaceSlowEv
+ __ZN3JSC8GCClient4Heap22booleanObjectSpaceSlowEv
+ __ZN3JSC8JSBigInt13tryCreateFromEPNS_14JSGlobalObjectERNS_2VMEbNSt3__14spanIKyLm18446744073709551615EEE
+ __ZN3JSC8JSBigInt13tryCreateZeroERNS_2VME
+ __ZN3JSC8JSBigInt6equalsEPS0_S1_
+ __ZN3JSC8JSBigInt8hashSlowEv
+ __ZN3JSC8JSObject19putDirectMayBeIndexEPNS_14JSGlobalObjectENS_12PropertyNameENS_7JSValueE
+ __ZN3JSC8JSObject27getOwnNonIndexPropertyNamesEPNS_14JSGlobalObjectERNS_24PropertyNameArrayBuilderENS_22DontEnumPropertiesModeE
+ __ZN3WTF13emptyAtomDataE
+ __ZN3WTF14AtomStringImpl3addENSt3__14spanIKDsLm18446744073709551615EEE
+ __ZN3WTF14AtomStringImpl3addENSt3__14spanIKhLm18446744073709551615EEE
+ __ZN3WTF14FileSystemImpl8statFileENSt3__14spanIKcLm18446744073709551615EEER4stat
+ __ZN3WTF21MemoryPressureHandler25setDispatchQueueWithLabelENS_12ASCIILiteralE
+ __ZN3WTF5equalEPKNS_10StringImplES2_
+ __ZN3WTF5equalERKNS_10StringImplES2_
+ __ZN3WTF6StringC1ENSt3__14spanIKDsLm18446744073709551615EEE
+ __ZN3WTF6StringC1ENSt3__14spanIKhLm18446744073709551615EEE
+ __ZN3WTF6Thread33setCurrentThreadIsUserInteractiveEi
+ __ZN3WTF7RunLoop13dispatchAfterENS_7SecondsEONS_8FunctionIFvvEEE
+ __ZNK3JSC19ArrayBufferContents9shareWithERS0_
+ __ZNK3JSC8JSString13equalSlowCaseEPNS_14JSGlobalObjectEPS0_
+ __ZNK3WTF17StringPrintStream13toUTF8CStringEv
- __ZN3JSC13JSArrayBuffer6createERNS_2VMEPNS_9StructureEON3WTF6RefPtrINS_11ArrayBufferENS5_12RawPtrTraitsIS7_EENS5_21DefaultRefDerefTraitsIS7_EEEE
- __ZN3JSC17DeferredWorkTimer24scheduleWorkSoonIfActiveERKN3WTF17ThreadSafeWeakPtrINS0_6TicketENS1_15NoTaggingTraitsIS3_EEEEONS1_8FunctionIFvRS3_EEE
- __ZN3WTF11PrintStream6printfEPKcz
- __ZN3WTF6StringC1ENSt3__14spanIKcLm18446744073709551615EEE
- __ZN3WTF7RunLoop13scheduleTimerENS_7SecondsEONS_8FunctionIFvvEEE
- __ZNK3JSC13JSArrayBuffer8isSharedEv
- __ZNK3WTF17StringPrintStream9toCStringEv
- __ZSt9terminatev
- _dispatch_queue_create
- _os_release
- _stat
CStrings:
+ "  --enable-all-experimental-features  Enables all JSC feature-flag options (off-by-default in-development features)\n"
+ "--enable-all-experimental-features"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/wtf/Box.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/wtf/HashTable.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/wtf/RefCounted.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/wtf/StdLibExtras.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/wtf/ThreadSpecific.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/wtf/Vector.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/wtf/text/StringCommon.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/wtf/text/StringConcatenate.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_executables/Source/JavaScriptCore/runtime/CloneDeserializerBase.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_executables/Source/JavaScriptCore/runtime/CloneSerializerBase.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_executables/Source/JavaScriptCore/runtime/JSCast.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore_executables/Source/JavaScriptCore/runtime/MarkedVector.h"
+ "Duplicate transferable for structured clone"
+ "JSValue JSC::CloneDeserializerBase<JSCCloneDeserializer>::readTerminalImpl(SerializationTag) [Derived = JSCCloneDeserializer]"
+ "JSValue JSC::JSObject::getIndexQuicklyForTypedArray(unsigned int, ArrayProfile *) const"
+ "JSValue JSC::JSObject::tryGetIndexQuickly(unsigned int, ArrayProfile *) const"
+ "SerializationReturnCode JSC::CloneSerializerBase<JSCCloneSerializer>::serialize(JSValue) [Derived = JSCCloneSerializer, SideChannelsType = JSC::CloneSerializationSideChannels]"
+ "To *WTF::downcast(JSC::JSValue &) [To = JSC::JSBigInt]"
+ "UTF8CString toUTF8CString(JSGlobalObject *, ThrowScope &, std::expected<UTF8CString, UTF8ConversionError>)"
+ "Value could not be cloned."
+ "VisitNamedMemberResult JSC::CloneDeserializerBase<JSCCloneDeserializer>::startVisitNamedMember(MarkedVector<JSObject *, 32> &, Vector<Identifier, 16> &, Vector<WalkerState, 16> &, JSValue &) [Derived = JSCCloneDeserializer, endState = JSC::WalkerState::ArrayEndVisitNamedMember]"
+ "dfgThresholdScaleForFewPerformanceCores"
+ "ftlThresholdScaleForFewPerformanceCores"
+ "globalInliningPlanBudgetForDFG"
+ "globalInliningPlanBudgetForFTL"
+ "inliningPlanDepthPenalty"
+ "inliningPlanTierBonusBase"
+ "inliningPlanTierBonusPowerForBaseline"
+ "inliningPlanTierBonusPowerForDFG"
+ "inliningPlanTierBonusPowerForFTL"
+ "maximumGlobalInliningPlanSites"
+ "numberOfSuperAndPerformanceCoresOverride"
+ "structuredClone"
+ "structuredClone options must be an object."
+ "structuredClone transfer list can only contain ArrayBuffers"
+ "transfer"
+ "useGlobalInliningPlanner"
+ "useImportText"
+ "useJointIteration"
+ "useRegExpBufferBoundaries"
+ "useWarmUpMarkedBlocks"
+ "useWasmByteLoopReplacement"
+ "useWasmJSTypes"
+ "validateKey"
+ "void JSC::MarkedVector<JSC::JSValue, 8, WTF::RecordOverflow>::appendWithCrashOnOverflow(T) [T = JSC::JSValue, passedInlineCapacity = 8, OverflowHandler = WTF::RecordOverflow]"
+ "void WTF::memcpySpan(std::span<T, TExtent>, std::span<U, UExtent>) [T = char, TExtent = 18446744073709551615UL, U = const char, UExtent = 18446744073709551615UL] [[clang::annotate_type(...)]]"
+ "void WTF::memcpySpan(std::span<T, TExtent>, std::span<U, UExtent>) [T = unsigned char, TExtent = 18446744073709551615UL, U = const char8_t, UExtent = 18446744073709551615UL] [[clang::annotate_type(...)]]"
+ "void WTF::memcpySpan(std::span<T, TExtent>, std::span<U, UExtent>) [T = unsigned char, TExtent = 18446744073709551615UL, U = const unsigned char, UExtent = 18446744073709551615UL] [[clang::annotate_type(...)]]"
+ "warmUpMarkedBlockCount"
+ "warmUpMarkedBlockIdleTimeout"
- " fopen had error: "
- "%.*s"
- ".bytecode-cache"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/wtf/Box.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/wtf/MemoryPressureHandler.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/wtf/RefCounted.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/wtf/StdLibExtras.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/wtf/ThreadSpecific.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/wtf/Vector.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/wtf/text/StringCommon.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/wtf/text/StringConcatenate.h"
- "CString toCString(JSGlobalObject *, ThrowScope &, Expected<CString, UTF8ConversionError>)"
- "Could not open file '"
- "Could not open file at "
- "Module specifier, '"
- "Not supported object"
- "airForceBriggsAllocator"
- "airForceIRCAllocator"
- "airUseGreedyRegAlloc"
- "customFullGCCallbackBailThreshold"
- "dfgThresholdScaleForLowP0Cores"
- "ftlThresholdScaleForLowP0Cores"
- "numberOfP0CoresOverrides"
- "std::span<const char> WTF::enumNameImpl() [V = WTF::Signal::AccessFault]"
- "std::span<const char> WTF::enumNameImpl() [V = WTF::Signal::Breakpoint]"
- "std::span<const char> WTF::enumNameImpl() [V = WTF::Signal::FloatingPoint]"
- "std::span<const char> WTF::enumNameImpl() [V = WTF::Signal::IllegalInstruction]"
- "std::span<const char> WTF::enumNameImpl() [V = WTF::Signal::NumberOfSignals]"
- "std::span<const char> WTF::enumNameImpl() [V = WTF::Signal::Usr]"
- "std::span<const char> WTF::enumTypeNameImpl() [E = WTF::Signal]"
- "void WTF::MemoryPressureHandler::setDispatchQueue(OSObjectPtr<dispatch_queue_t> &&)"
- "void WTF::memcpySpan(std::span<T, TExtent>, std::span<U, UExtent>) [T = char, TExtent = 18446744073709551615UL, U = const char, UExtent = 18446744073709551615UL]"
- "void WTF::memcpySpan(std::span<T, TExtent>, std::span<U, UExtent>) [T = unsigned char, TExtent = 18446744073709551615UL, U = const char8_t, UExtent = 18446744073709551615UL]"
```
