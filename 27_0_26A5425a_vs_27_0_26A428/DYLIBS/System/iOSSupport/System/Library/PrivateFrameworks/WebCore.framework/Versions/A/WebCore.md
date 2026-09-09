## WebCore

> `/System/iOSSupport/System/Library/PrivateFrameworks/WebCore.framework/Versions/A/WebCore`

```diff

-625.1.29.11.26
-  __TEXT.__text: 0x32e7694
+625.1.29.11.27
+  __TEXT.__text: 0x32f9c54
   __TEXT.__objc_methlist: 0x4ed4
   __TEXT.__getClass_cstr: 0xc57
   __TEXT.__dlsym_cstr: 0x734b
-  __TEXT.__const: 0x1975f0
+  __TEXT.__const: 0x1975b0
   __TEXT.__swift5_typeref: 0x2bb
-  __TEXT.__cstring: 0x30f336
+  __TEXT.__cstring: 0x30efc2
   __TEXT.__constg_swiftt: 0x2e8
   __TEXT.__swift5_fieldmd: 0x17c
   __TEXT.__swift5_reflstr: 0x7f
   __TEXT.__swift5_proto: 0x3c
   __TEXT.__swift5_types: 0x44
-  __TEXT.__gcc_except_tab: 0x25ff0
+  __TEXT.__gcc_except_tab: 0x2601c
   __TEXT.__swift5_assocty: 0x1a0
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__oslogstring: 0xf14e
   __TEXT.__ustring: 0x1ce
-  __TEXT.__unwind_info: 0x64860
+  __TEXT.__unwind_info: 0x648c0
   __TEXT.__eh_frame: 0x1374
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x8
   __DATA.__objc_ivar: 0x43c
-  __DATA.__data: 0x180c8
-  __DATA.__common: 0x5668
+  __DATA.__data: 0x180c0
+  __DATA.__common: 0x5670
   __DATA.__bss: 0x4748
   __DATA_DIRTY.__objc_ivar: 0x50
   __DATA_DIRTY.__objc_data: 0xa78

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 107386
-  Symbols:   137191
-  CStrings:  29843
+  Functions: 107407
+  Symbols:   137212
+  CStrings:  29842
 
Symbols:
+ __ZN3WTF3RefIN7WebCore8SQLErrorENS_12RawPtrTraitsIS2_EENS_21DefaultRefDerefTraitsIS2_EEED1Ev
+ __ZN3WTF3URLC2EOS0_
+ __ZN3WTF6RefPtrIN7WebCore8SQLErrorENS_12RawPtrTraitsIS2_EENS_21DefaultRefDerefTraitsIS2_EEEaSIS2_EERS7_ONS_3RefIT_NS3_ISB_EENS5_ISB_EEEE
+ __ZN3WTF9HashTableINS_3RefIN7WebCore8DatabaseENS_12RawPtrTraitsIS3_EENS_21DefaultRefDerefTraitsIS3_EEEES8_NS_17IdentityExtractorENS_11DefaultHashIS8_EENS_10HashTraitsIS8_EESD_NS_10FastMallocEE3addILNS_17ShouldValidateKeyE1EEENS_18HashTableAddResultINS_17HashTableIteratorISF_S8_S8_S9_SB_SD_SD_EEEEOS8_
+ __ZN3WTF9HashTableINS_3RefIN7WebCore8DatabaseENS_12RawPtrTraitsIS3_EENS_21DefaultRefDerefTraitsIS3_EEEES8_NS_17IdentityExtractorENS_11DefaultHashIS8_EENS_10HashTraitsIS8_EESD_NS_10FastMallocEE6removeEPS8_
+ __ZN5mpark6detail4baseIJN3WTF3RefIN7WebCore8DatabaseENS2_12RawPtrTraitsIS5_EENS2_21DefaultRefDerefTraitsIS5_EEEENS4_9ExceptionEEE14generic_assignINS0_8impl_smfILb0EJSA_SB_EEEEEvOT_
+ __ZN7WebCore12DatabaseTask11performTaskEv
+ __ZN7WebCore12wellKnownURLEN3WTF10StringViewES1_
+ __ZN7WebCore14DatabaseThread18recordDatabaseOpenERNS_8DatabaseE
+ __ZN7WebCore14DatabaseThread23unscheduleDatabaseTasksERNS_8DatabaseE
+ __ZN7WebCore14DatabaseThread5startEv
+ __ZN7WebCore14DatabaseThreadC2Ev
+ __ZN7WebCore14SQLTransaction16getNextStatementEv
+ __ZN7WebCore14SQLTransaction19postflightAndCommitEv
+ __ZN7WebCore14SQLTransaction19runCurrentStatementEv
+ __ZN7WebCore15DatabaseContextD2Ev
+ __ZN7WebCore18DatagramByteSource6createEv
+ __ZN7WebCore21SQLTransactionBackendC1ERNS_14SQLTransactionE
+ __ZN7WebCore24DatabaseTaskSynchronizer13taskCompletedEv
+ __ZN7WebCore25findOriginInWellKnownListERKNS_18SecurityOriginDataENSt3__14spanIKhLm18446744073709551615EEEN3WTF12ASCIILiteralEONS_25WellKnownOriginListPolicyE
+ __ZN7WebCore26isWellKnownRedirectAllowedERKN3WTF3URLE
+ __ZN7WebCore29isWellKnownResponseAcceptableEiN3WTF10StringViewE
+ __ZN7WebCore29parseOriginsFromWellKnownListENSt3__14spanIKhLm18446744073709551615EEEN3WTF12ASCIILiteralEONS_25WellKnownOriginListPolicyE
+ __ZN7WebCore33prefetchedHostnameCountForTestingEv
+ __ZN7WebCoreL20parseCandidatesArrayENSt3__14spanIKhLm18446744073709551615EEEN3WTF12ASCIILiteralEm
+ __ZNK3WTF29ThreadSafeWeakPtrControlBlock11strongDerefIN7WebCore14DatabaseThreadELNS_17DestructionThreadE0EEEvv
- __ZN3WTF23ObjectIdentifierGenericIN7WebCore16WebSocketChannelENS_38ObjectIdentifierThreadSafeAccessTraitsIyEEyE21m_generationProtectedE
- __ZN7WebCore15DatabaseContext13stopDatabasesEPNS_24DatabaseTaskSynchronizerE
- __ZN7WebCore18DatagramByteSource4pullERNS_17JSDOMGlobalObjectERNS_28ReadableByteStreamControllerEON3WTF3RefINS_15DeferredPromiseENS5_12RawPtrTraitsIS7_EENS5_21DefaultRefDerefTraitsIS7_EEEE
- __ZN7WebCore18DatagramByteSource6cancelEON3WTF3RefINS_15DeferredPromiseENS1_12RawPtrTraitsIS3_EENS1_21DefaultRefDerefTraitsIS3_EEEE
- __ZNK3WTF47ThreadSafeRefCountedAndCanMakeThreadSafeWeakPtrIN7WebCore8DatabaseELNS_17DestructionThreadE0EE5derefEv
CStrings:
- "static ObjectIdentifierGeneric<type-parameter-0-0, type-parameter-0-1, type-parameter-0-2> WTF::ObjectIdentifierGeneric<WebCore::WebSocketChannel, WTF::ObjectIdentifierThreadSafeAccessTraits<uint64_t>, unsigned long long>::generate() [T = WebCore::WebSocketChannel, ThreadSafety = WTF::ObjectIdentifierThreadSafeAccessTraits<uint64_t>, RawValue = unsigned long long]"
```
