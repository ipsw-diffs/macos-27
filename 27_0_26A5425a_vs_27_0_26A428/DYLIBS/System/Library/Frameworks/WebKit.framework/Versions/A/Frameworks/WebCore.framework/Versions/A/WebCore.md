## WebCore

> `/System/Library/Frameworks/WebKit.framework/Versions/A/Frameworks/WebCore.framework/Versions/A/WebCore`

```diff

-625.1.29.11.26
-  __TEXT.__text: 0x37e1f4c
+625.1.29.11.27
+  __TEXT.__text: 0x37efa48
   __TEXT.__objc_methlist: 0x4200
   __TEXT.__getClass_cstr: 0x1063
   __TEXT.__dlsym_cstr: 0x6b58
-  __TEXT.__const: 0x1b4658
+  __TEXT.__const: 0x1b4618
   __TEXT.__swift5_typeref: 0x2bb
-  __TEXT.__cstring: 0x34e036
+  __TEXT.__cstring: 0x34ddfe
   __TEXT.__constg_swiftt: 0x2e8
   __TEXT.__swift5_fieldmd: 0x17c
   __TEXT.__swift5_reflstr: 0x7f
   __TEXT.__swift5_proto: 0x3c
   __TEXT.__swift5_types: 0x44
-  __TEXT.__gcc_except_tab: 0x39110
+  __TEXT.__gcc_except_tab: 0x39118
   __TEXT.__swift5_assocty: 0x1a0
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__oslogstring: 0x147b1
   __TEXT.__ustring: 0x2b2
-  __TEXT.__unwind_info: 0x77ea8
+  __TEXT.__unwind_info: 0x77ee8
   __TEXT.__eh_frame: 0x1724
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x8
   __DATA.__objc_ivar: 0x3d8
-  __DATA.__data: 0x1c180
-  __DATA.__common: 0xd198
+  __DATA.__data: 0x1c178
+  __DATA.__common: 0xd1a0
   __DATA.__bss: 0x405d0
   __DATA_DIRTY.__objc_ivar: 0x54
   __DATA_DIRTY.__objc_data: 0xb68

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 125603
-  Symbols:   159235
-  CStrings:  33702
+  Functions: 125616
+  Symbols:   159250
+  CStrings:  33701
 
Symbols:
+ __ZN3WTF9HashTableINS_3RefIN7WebCore8DatabaseENS_12RawPtrTraitsIS3_EENS_21DefaultRefDerefTraitsIS3_EEEES8_NS_17IdentityExtractorENS_11DefaultHashIS8_EENS_10HashTraitsIS8_EESD_NS_10FastMallocEE3addILNS_17ShouldValidateKeyE1EEENS_18HashTableAddResultINS_17HashTableIteratorISF_S8_S8_S9_SB_SD_SD_EEEEOS8_
+ __ZN3WTF9HashTableINS_3RefIN7WebCore8DatabaseENS_12RawPtrTraitsIS3_EENS_21DefaultRefDerefTraitsIS3_EEEES8_NS_17IdentityExtractorENS_11DefaultHashIS8_EENS_10HashTraitsIS8_EESD_NS_10FastMallocEE6removeEPS8_
+ __ZN7WebCore12DatabaseTask11performTaskEv
+ __ZN7WebCore12wellKnownURLEN3WTF10StringViewES1_
+ __ZN7WebCore14DatabaseThread18recordDatabaseOpenERNS_8DatabaseE
+ __ZN7WebCore14DatabaseThread23unscheduleDatabaseTasksERNS_8DatabaseE
+ __ZN7WebCore14DatabaseThread5startEv
+ __ZN7WebCore14DatabaseThreadC2Ev
+ __ZN7WebCore14SQLTransaction16getNextStatementEv
+ __ZN7WebCore14SQLTransaction19postflightAndCommitEv
+ __ZN7WebCore14SQLTransaction19runCurrentStatementEv
+ __ZN7WebCore21SQLTransactionBackendC1ERNS_14SQLTransactionE
+ __ZN7WebCore24DatabaseTaskSynchronizer13taskCompletedEv
+ __ZN7WebCore25findOriginInWellKnownListERKNS_18SecurityOriginDataENSt3__14spanIKhLm18446744073709551615EEEN3WTF12ASCIILiteralEONS_25WellKnownOriginListPolicyE
+ __ZN7WebCore26isWellKnownRedirectAllowedERKN3WTF3URLE
+ __ZN7WebCore29isWellKnownResponseAcceptableEiN3WTF10StringViewE
+ __ZN7WebCore29parseOriginsFromWellKnownListENSt3__14spanIKhLm18446744073709551615EEEN3WTF12ASCIILiteralEONS_25WellKnownOriginListPolicyE
+ __ZN7WebCore33prefetchedHostnameCountForTestingEv
+ __ZN7WebCoreL20parseCandidatesArrayENSt3__14spanIKhLm18446744073709551615EEEN3WTF12ASCIILiteralEm
- __ZN3WTF23ObjectIdentifierGenericIN7WebCore16WebSocketChannelENS_38ObjectIdentifierThreadSafeAccessTraitsIyEEyE21m_generationProtectedE
- __ZN7WebCore18DatagramByteSource4pullERNS_17JSDOMGlobalObjectERNS_28ReadableByteStreamControllerEON3WTF3RefINS_15DeferredPromiseENS5_12RawPtrTraitsIS7_EENS5_21DefaultRefDerefTraitsIS7_EEEE
- __ZN7WebCore18DatagramByteSource6cancelEON3WTF3RefINS_15DeferredPromiseENS1_12RawPtrTraitsIS3_EENS1_21DefaultRefDerefTraitsIS3_EEEE
- __ZN7WebCore22ScriptExecutionContext18setDatabaseContextEPNS_15DatabaseContextE
CStrings:
- "static ObjectIdentifierGeneric<type-parameter-0-0, type-parameter-0-1, type-parameter-0-2> WTF::ObjectIdentifierGeneric<WebCore::WebSocketChannel, WTF::ObjectIdentifierThreadSafeAccessTraits<uint64_t>, unsigned long long>::generate() [T = WebCore::WebSocketChannel, ThreadSafety = WTF::ObjectIdentifierThreadSafeAccessTraits<uint64_t>, RawValue = unsigned long long]"
```
