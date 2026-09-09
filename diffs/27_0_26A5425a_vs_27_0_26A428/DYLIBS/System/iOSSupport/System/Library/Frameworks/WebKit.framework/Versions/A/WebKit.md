## WebKit

> `/System/iOSSupport/System/Library/Frameworks/WebKit.framework/Versions/A/WebKit`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`

```diff

-625.1.29.11.26
-  __TEXT.__text: 0xfd14a0
-  __TEXT.__objc_methlist: 0x18c18
-  __TEXT.__dlsym_cstr: 0xa8e
+625.1.29.11.27
+  __TEXT.__text: 0xfd32e8
+  __TEXT.__objc_methlist: 0x18c38
+  __TEXT.__dlsym_cstr: 0xaa7
   __TEXT.__getClass_cstr: 0x193
-  __TEXT.__const: 0x8574
-  __TEXT.__gcc_except_tab: 0x71e58
-  __TEXT.__cstring: 0x1ee5dc
+  __TEXT.__const: 0x8564
+  __TEXT.__gcc_except_tab: 0x71ebc
+  __TEXT.__cstring: 0x1ee3cc
   __TEXT.__swift5_typeref: 0x1956
   __TEXT.__constg_swiftt: 0x1b1c
   __TEXT.__swift5_reflstr: 0xb58

   __TEXT.__swift5_types2: 0x8
   __TEXT.__oslogstring: 0x5d522
   __TEXT.__ustring: 0xc44
-  __TEXT.__unwind_info: 0x4a540
+  __TEXT.__unwind_info: 0x4a5b0
   __TEXT.__eh_frame: 0x9334
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x20c10
+  __DATA_CONST.__const: 0x20c70
   __DATA_CONST.__objc_classlist: 0xb90
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x368
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf560
+  __DATA_CONST.__objc_selrefs: 0xf578
   __DATA_CONST.__objc_protorefs: 0xa0
   __DATA_CONST.__objc_superrefs: 0x8e0
   __DATA_CONST.__objc_arraydata: 0x620
   __DATA_CONST.__got: 0x1db8
-  __AUTH_CONST.__const: 0x5ec10
+  __AUTH_CONST.__const: 0x5ed10
   __AUTH_CONST.__cfstring: 0x11ba0
-  __AUTH_CONST.__objc_const: 0x25d48
+  __AUTH_CONST.__objc_const: 0x25d50
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x4e0
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__objc_doubleobj: 0x20
-  __AUTH_CONST.__auth_got: 0xc378
+  __AUTH_CONST.__auth_got: 0xc390
   __AUTH.__objc_data: 0x5510
   __AUTH.__data: 0x960
   __AUTH.__thread_vars: 0x60
   __AUTH.__thread_bss: 0x20
   __DATA.__objc_ivar: 0xf04
-  __DATA.__data: 0x3298
-  __DATA.__common: 0xe60
-  __DATA.__bss: 0x3990
+  __DATA.__data: 0x32a8
+  __DATA.__common: 0xe48
+  __DATA.__bss: 0x39a0
   __DATA_DIRTY.__objc_ivar: 0x43c
   __DATA_DIRTY.__objc_data: 0x21c0
   __DATA_DIRTY.__data: 0x5210
   __DATA_DIRTY.__common: 0x3478
-  __DATA_DIRTY.__bss: 0x1550
+  __DATA_DIRTY.__bss: 0x1560
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 66013
-  Symbols:   97001
-  CStrings:  17342
+  Functions: 66031
+  Symbols:   97022
+  CStrings:  17346
 
Symbols:
+ -[WKWebsiteDataStore(WKPrivate) _canPrefetchDNSForTesting:]
+ -[WKWebsiteDataStore(WKPrivate) _prefetchedDNSHostnameCountForTesting:]
+ __ZL18isProxyTypeTCPOnlyPU29objcproto18OS_nw_proxy_config8NSObject
+ __ZN3IPC18handleMessageAsyncIN8Messages14NetworkProcess24CanPrefetchDNSForTestingENS_10ConnectionEN6WebKit14NetworkProcessES6_FvN3PAL9SessionIDEON3WTF17CompletionHandlerIFvbEEEEEEvRT0_RNS_7DecoderEPT1_MT2_T3_
+ __ZN3IPC18handleMessageAsyncIN8Messages14NetworkProcess36PrefetchedDNSHostnameCountForTestingENS_10ConnectionEN6WebKit14NetworkProcessES6_KFvON3WTF17CompletionHandlerIFvyEEEEEEvRT0_RNS_7DecoderEPT1_MT2_T3_
+ __ZN3WTF6Detail15CallableWrapperIZ114-[WKWebsiteDataStore(WKPrivate) _installMockParentalControlsURLFilterForTestingWithBlockedURLs:completionHandler:]E4$_53vJEE4callEv
+ __ZN3WTF6Detail15CallableWrapperIZ114-[WKWebsiteDataStore(WKPrivate) _installMockParentalControlsURLFilterForTestingWithBlockedURLs:completionHandler:]E4$_53vJEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZ114-[WKWebsiteDataStore(WKPrivate) _installMockParentalControlsURLFilterForTestingWithBlockedURLs:completionHandler:]E4$_53vJEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo data]E4$_69vJP13NSFileWrapperEE4callES4_
+ __ZN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo data]E4$_69vJP13NSFileWrapperEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo data]E4$_69vJP13NSFileWrapperEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo name]E4$_70vJP13NSFileWrapperEE4callES4_
+ __ZN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo name]E4$_70vJP13NSFileWrapperEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo name]E4$_70vJP13NSFileWrapperEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZ32-[_WKAttachmentInfo fileWrapper]E4$_71vJP13NSFileWrapperEE4callES4_
+ __ZN3WTF6Detail15CallableWrapperIZ32-[_WKAttachmentInfo fileWrapper]E4$_71vJP13NSFileWrapperEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZ32-[_WKAttachmentInfo fileWrapper]E4$_71vJP13NSFileWrapperEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZ55-[_WKAttachment setFileWrapper:contentType:completion:]E4$_72vJEE4callEv
+ __ZN3WTF6Detail15CallableWrapperIZ55-[_WKAttachment setFileWrapper:contentType:completion:]E4$_72vJEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZ55-[_WKAttachment setFileWrapper:contentType:completion:]E4$_72vJEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZ59-[WKWebsiteDataStore(WKPrivate) _canPrefetchDNSForTesting:]E4$_51vJbEE4callEb
+ __ZN3WTF6Detail15CallableWrapperIZ59-[WKWebsiteDataStore(WKPrivate) _canPrefetchDNSForTesting:]E4$_51vJbEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZ59-[WKWebsiteDataStore(WKPrivate) _canPrefetchDNSForTesting:]E4$_51vJbEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZ71-[WKWebsiteDataStore(WKPrivate) _prefetchedDNSHostnameCountForTesting:]E4$_52vJyEE4callEy
+ __ZN3WTF6Detail15CallableWrapperIZ71-[WKWebsiteDataStore(WKPrivate) _prefetchedDNSHostnameCountForTesting:]E4$_52vJyEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZ71-[WKWebsiteDataStore(WKPrivate) _prefetchedDNSHostnameCountForTesting:]E4$_52vJyEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZN3IPC10Connection31makeAsyncReplyCompletionHandlerIN8Messages14NetworkProcess24CanPrefetchDNSForTestingENS_17CompletionHandlerIFvbEEEEENS8_IFvPS3_PNS2_7DecoderEEEEOT0_NS_19ThreadLikeAssertionEEUlSB_SD_E_vJSB_SD_EE4callESB_SD_
+ __ZN3WTF6Detail15CallableWrapperIZN3IPC10Connection31makeAsyncReplyCompletionHandlerIN8Messages14NetworkProcess24CanPrefetchDNSForTestingENS_17CompletionHandlerIFvbEEEEENS8_IFvPS3_PNS2_7DecoderEEEEOT0_NS_19ThreadLikeAssertionEEUlSB_SD_E_vJSB_SD_EED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZN3IPC10Connection31makeAsyncReplyCompletionHandlerIN8Messages14NetworkProcess24CanPrefetchDNSForTestingENS_17CompletionHandlerIFvbEEEEENS8_IFvPS3_PNS2_7DecoderEEEEOT0_NS_19ThreadLikeAssertionEEUlSB_SD_E_vJSB_SD_EED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZN3IPC10Connection31makeAsyncReplyCompletionHandlerIN8Messages14NetworkProcess36PrefetchedDNSHostnameCountForTestingENS_17CompletionHandlerIFvyEEEEENS8_IFvPS3_PNS2_7DecoderEEEEOT0_NS_19ThreadLikeAssertionEEUlSB_SD_E_vJSB_SD_EE4callESB_SD_
+ __ZN3WTF6Detail15CallableWrapperIZN3IPC10Connection31makeAsyncReplyCompletionHandlerIN8Messages14NetworkProcess36PrefetchedDNSHostnameCountForTestingENS_17CompletionHandlerIFvyEEEEENS8_IFvPS3_PNS2_7DecoderEEEEOT0_NS_19ThreadLikeAssertionEEUlSB_SD_E_vJSB_SD_EED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZN3IPC10Connection31makeAsyncReplyCompletionHandlerIN8Messages14NetworkProcess36PrefetchedDNSHostnameCountForTestingENS_17CompletionHandlerIFvyEEEEENS8_IFvPS3_PNS2_7DecoderEEEEOT0_NS_19ThreadLikeAssertionEEUlSB_SD_E_vJSB_SD_EED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZN3IPC18handleMessageAsyncIN8Messages14NetworkProcess24CanPrefetchDNSForTestingENS2_10ConnectionEN6WebKit14NetworkProcessES9_FvN3PAL9SessionIDEONS_17CompletionHandlerIFvbEEEEEEvRT0_RNS2_7DecoderEPT1_MT2_T3_EUlDpOT_E_vJbEE4callEb
+ __ZN3WTF6Detail15CallableWrapperIZN3IPC18handleMessageAsyncIN8Messages14NetworkProcess24CanPrefetchDNSForTestingENS2_10ConnectionEN6WebKit14NetworkProcessES9_FvN3PAL9SessionIDEONS_17CompletionHandlerIFvbEEEEEEvRT0_RNS2_7DecoderEPT1_MT2_T3_EUlDpOT_E_vJbEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZN3IPC18handleMessageAsyncIN8Messages14NetworkProcess24CanPrefetchDNSForTestingENS2_10ConnectionEN6WebKit14NetworkProcessES9_FvN3PAL9SessionIDEONS_17CompletionHandlerIFvbEEEEEEvRT0_RNS2_7DecoderEPT1_MT2_T3_EUlDpOT_E_vJbEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZN3IPC18handleMessageAsyncIN8Messages14NetworkProcess36PrefetchedDNSHostnameCountForTestingENS2_10ConnectionEN6WebKit14NetworkProcessES9_KFvONS_17CompletionHandlerIFvyEEEEEEvRT0_RNS2_7DecoderEPT1_MT2_T3_EUlDpOT_E_vJyEE4callEy
+ __ZN3WTF6Detail15CallableWrapperIZN3IPC18handleMessageAsyncIN8Messages14NetworkProcess36PrefetchedDNSHostnameCountForTestingENS2_10ConnectionEN6WebKit14NetworkProcessES9_KFvONS_17CompletionHandlerIFvyEEEEEEvRT0_RNS2_7DecoderEPT1_MT2_T3_EUlDpOT_E_vJyEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZN3IPC18handleMessageAsyncIN8Messages14NetworkProcess36PrefetchedDNSHostnameCountForTestingENS2_10ConnectionEN6WebKit14NetworkProcessES9_KFvONS_17CompletionHandlerIFvyEEEEEEvRT0_RNS2_7DecoderEPT1_MT2_T3_EUlDpOT_E_vJyEED1Ev
+ __ZN6WebKit14NetworkProcess24canPrefetchDNSForTestingEN3PAL9SessionIDEON3WTF17CompletionHandlerIFvbEEE
+ __ZN6WebKit19NetworkSessionCocoa52applyProxyConfigurationToNWParametersForWebTransportEPU27objcproto16OS_nw_parameters8NSObject
+ __ZN6WebKit21AuxiliaryProcessProxy18sendWithAsyncReplyIN8Messages14NetworkProcess24CanPrefetchDNSForTestingEN3WTF17CompletionHandlerIFvbEEEEENSt3__18optionalINS5_23ObjectIdentifierGenericIN3IPC16AsyncReplyIDTypeENS5_38ObjectIdentifierThreadSafeAccessTraitsIyEEyEEEEOT_OT0_yNS5_9OptionSetINSC_10SendOptionELNS5_14ConcurrencyTagE0EEENS0_35ShouldStartProcessThrottlerActivityE
+ __ZN6WebKit21AuxiliaryProcessProxy18sendWithAsyncReplyIN8Messages14NetworkProcess32RemovePushSubscriptionsForOriginEN3WTF17CompletionHandlerIFvjEEEEENSt3__18optionalINS5_23ObjectIdentifierGenericIN3IPC16AsyncReplyIDTypeENS5_38ObjectIdentifierThreadSafeAccessTraitsIyEEyEEEEOT_OT0_yNS5_9OptionSetINSC_10SendOptionELNS5_14ConcurrencyTagE0EEENS0_35ShouldStartProcessThrottlerActivityE
+ __ZN6WebKit21AuxiliaryProcessProxy18sendWithAsyncReplyIN8Messages14NetworkProcess36PrefetchedDNSHostnameCountForTestingEN3WTF17CompletionHandlerIFvyEEEEENSt3__18optionalINS5_23ObjectIdentifierGenericIN3IPC16AsyncReplyIDTypeENS5_38ObjectIdentifierThreadSafeAccessTraitsIyEEyEEEEOT_OT0_yNS5_9OptionSetINSC_10SendOptionELNS5_14ConcurrencyTagE0EEENS0_35ShouldStartProcessThrottlerActivityE
+ __ZN6WebKit21AuxiliaryProcessProxy18sendWithAsyncReplyIN8Messages14NetworkProcess39SetPushAndNotificationsEnabledForOriginEN3WTF17CompletionHandlerIFvvEEEEENSt3__18optionalINS5_23ObjectIdentifierGenericIN3IPC16AsyncReplyIDTypeENS5_38ObjectIdentifierThreadSafeAccessTraitsIyEEyEEEEOT_OT0_yNS5_9OptionSetINSC_10SendOptionELNS5_14ConcurrencyTagE0EEENS0_35ShouldStartProcessThrottlerActivityE
+ __ZN6WebKit26WebPageInspectorController13setIndicatingEb
+ __ZN6WebKit27RemoteProgressBasedTimeline6createEN7WebCore16ProcessQualifiedIN3WTF23ObjectIdentifierGenericINS1_22TimelineIdentifierTypeENS3_38ObjectIdentifierMainThreadAccessTraitsIyEEyEEEERKNS1_22ProgressResolutionDataE
+ __ZN6WebKit27RemoteProgressBasedTimelineC2EN7WebCore16ProcessQualifiedIN3WTF23ObjectIdentifierGenericINS1_22TimelineIdentifierTypeENS3_38ObjectIdentifierMainThreadAccessTraitsIyEEyEEEERKNS1_22ProgressResolutionDataE
+ __ZN6WebKit32EnhancedSecuritySitesPersistenceD2Ev
+ __ZN7WebCore33prefetchedHostnameCountForTestingEv
+ __ZNK3WTF29ThreadSafeWeakPtrControlBlock11strongDerefIN6WebKit27EnhancedSecuritySitesHolderELNS_17DestructionThreadE2EEEvv
+ __ZNK6WebKit14NetworkProcess36prefetchedDNSHostnameCountForTestingEON3WTF17CompletionHandlerIFvyEEE
+ __ZNK6WebKit14NetworkSession14canPrefetchDNSEv
+ __ZNK6WebKit16WebsiteDataStore24canPrefetchDNSForTestingEON3WTF17CompletionHandlerIFvbEEE
+ __ZNK6WebKit16WebsiteDataStore36prefetchedDNSHostnameCountForTestingEON3WTF17CompletionHandlerIFvyEEE
+ __ZNK6WebKit19NetworkSessionCocoa14canPrefetchDNSEv
+ __ZTVN3WTF6Detail15CallableWrapperIZ114-[WKWebsiteDataStore(WKPrivate) _installMockParentalControlsURLFilterForTestingWithBlockedURLs:completionHandler:]E4$_53vJEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo data]E4$_69vJP13NSFileWrapperEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo name]E4$_70vJP13NSFileWrapperEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZ32-[_WKAttachmentInfo fileWrapper]E4$_71vJP13NSFileWrapperEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZ55-[_WKAttachment setFileWrapper:contentType:completion:]E4$_72vJEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZ59-[WKWebsiteDataStore(WKPrivate) _canPrefetchDNSForTesting:]E4$_51vJbEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZ71-[WKWebsiteDataStore(WKPrivate) _prefetchedDNSHostnameCountForTesting:]E4$_52vJyEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZN3IPC10Connection31makeAsyncReplyCompletionHandlerIN8Messages14NetworkProcess24CanPrefetchDNSForTestingENS_17CompletionHandlerIFvbEEEEENS8_IFvPS3_PNS2_7DecoderEEEEOT0_NS_19ThreadLikeAssertionEEUlSB_SD_E_vJSB_SD_EEE
+ __ZTVN3WTF6Detail15CallableWrapperIZN3IPC10Connection31makeAsyncReplyCompletionHandlerIN8Messages14NetworkProcess36PrefetchedDNSHostnameCountForTestingENS_17CompletionHandlerIFvyEEEEENS8_IFvPS3_PNS2_7DecoderEEEEOT0_NS_19ThreadLikeAssertionEEUlSB_SD_E_vJSB_SD_EEE
+ __ZTVN3WTF6Detail15CallableWrapperIZN3IPC18handleMessageAsyncIN8Messages14NetworkProcess24CanPrefetchDNSForTestingENS2_10ConnectionEN6WebKit14NetworkProcessES9_FvN3PAL9SessionIDEONS_17CompletionHandlerIFvbEEEEEEvRT0_RNS2_7DecoderEPT1_MT2_T3_EUlDpOT_E_vJbEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZN3IPC18handleMessageAsyncIN8Messages14NetworkProcess36PrefetchedDNSHostnameCountForTestingENS2_10ConnectionEN6WebKit14NetworkProcessES9_KFvONS_17CompletionHandlerIFvyEEEEEEvRT0_RNS2_7DecoderEPT1_MT2_T3_EUlDpOT_E_vJyEEE
+ __ZZ36-[_WKApplicationManifest themeColor]EN4$_65D1Ev
+ __ZZ41-[_WKApplicationManifest backgroundColor]EN4$_64D1Ev
+ __ZZ69+[WKWebsiteDataStore(WKPrivate) _allWebsiteDataTypesIncludingPrivate]ENK4$_54clEv
+ __ZZL27nw_proxy_config_get_typePtrvE11auditedName
+ ___block_descriptor_33_e8_32c87_ZTSKZ73-[WKWebsiteDataStore(WKPrivate) _abortBackgroundFetch:completionHandler:]E4$_55_e5_v8?0l
+ ___block_descriptor_33_e8_32c87_ZTSKZ73-[WKWebsiteDataStore(WKPrivate) _clickBackgroundFetch:completionHandler:]E4$_58_e5_v8?0l
+ ___block_descriptor_33_e8_32c87_ZTSKZ73-[WKWebsiteDataStore(WKPrivate) _pauseBackgroundFetch:completionHandler:]E4$_56_e5_v8?0l
+ ___block_descriptor_33_e8_32c88_ZTSKZ74-[WKWebsiteDataStore(WKPrivate) _resumeBackgroundFetch:completionHandler:]E4$_57_e5_v8?0l
+ ___block_descriptor_48_e8_32c50_ZTSKZ36-[_WKApplicationManifest themeColor]E4$_65_e36_"UIColor"16?0"UITraitCollection"8l
+ ___block_descriptor_48_e8_32c55_ZTSKZ41-[_WKApplicationManifest backgroundColor]E4$_64_e36_"UIColor"16?0"UITraitCollection"8l
+ ___copy_helper_block_e8_32c50_ZTSKZ36-[_WKApplicationManifest themeColor]E4$_65
+ ___copy_helper_block_e8_32c55_ZTSKZ41-[_WKApplicationManifest backgroundColor]E4$_64
+ ___copy_helper_block_e8_32c87_ZTSKZ73-[WKWebsiteDataStore(WKPrivate) _abortBackgroundFetch:completionHandler:]E4$_55
+ ___copy_helper_block_e8_32c87_ZTSKZ73-[WKWebsiteDataStore(WKPrivate) _clickBackgroundFetch:completionHandler:]E4$_58
+ ___copy_helper_block_e8_32c87_ZTSKZ73-[WKWebsiteDataStore(WKPrivate) _pauseBackgroundFetch:completionHandler:]E4$_56
+ ___copy_helper_block_e8_32c88_ZTSKZ74-[WKWebsiteDataStore(WKPrivate) _resumeBackgroundFetch:completionHandler:]E4$_57
+ ___destroy_helper_block_e8_32c50_ZTSKZ36-[_WKApplicationManifest themeColor]E4$_65
+ ___destroy_helper_block_e8_32c55_ZTSKZ41-[_WKApplicationManifest backgroundColor]E4$_64
+ _nw_parameters_add_custom_proxy_config
+ _nw_parameters_clear_custom_proxy_configs
- __PRETTY_FUNCTION__._ZN3WTF23ObjectIdentifierGenericIN7WebCore21ProcessIdentifierTypeENS_38ObjectIdentifierMainThreadAccessTraitsIyEEyEC2Ey
- __PRETTY_FUNCTION__._ZN3WTF8downcastIN6WebKit29RemoteMediaSessionClientProxyEN7WebCore26PlatformMediaSessionClientEEERNSt3__111conditionalIXsr3stdE10is_const_vIT0_EENS5_9add_constIT_E4typeEu14__remove_constIS9_EE4typeERS7_
- __ZN3WTF10CheckedPtrIN6WebKit21InspectorBrowserAgentENS_12RawPtrTraitsIS2_EEEaSEPS2_
- __ZN3WTF6Detail15CallableWrapperIZ114-[WKWebsiteDataStore(WKPrivate) _installMockParentalControlsURLFilterForTestingWithBlockedURLs:completionHandler:]E4$_51vJEE4callEv
- __ZN3WTF6Detail15CallableWrapperIZ114-[WKWebsiteDataStore(WKPrivate) _installMockParentalControlsURLFilterForTestingWithBlockedURLs:completionHandler:]E4$_51vJEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZ114-[WKWebsiteDataStore(WKPrivate) _installMockParentalControlsURLFilterForTestingWithBlockedURLs:completionHandler:]E4$_51vJEED1Ev
- __ZN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo data]E4$_67vJP13NSFileWrapperEE4callES4_
- __ZN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo data]E4$_67vJP13NSFileWrapperEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo data]E4$_67vJP13NSFileWrapperEED1Ev
- __ZN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo name]E4$_68vJP13NSFileWrapperEE4callES4_
- __ZN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo name]E4$_68vJP13NSFileWrapperEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo name]E4$_68vJP13NSFileWrapperEED1Ev
- __ZN3WTF6Detail15CallableWrapperIZ32-[_WKAttachmentInfo fileWrapper]E4$_69vJP13NSFileWrapperEE4callES4_
- __ZN3WTF6Detail15CallableWrapperIZ32-[_WKAttachmentInfo fileWrapper]E4$_69vJP13NSFileWrapperEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZ32-[_WKAttachmentInfo fileWrapper]E4$_69vJP13NSFileWrapperEED1Ev
- __ZN3WTF6Detail15CallableWrapperIZ55-[_WKAttachment setFileWrapper:contentType:completion:]E4$_70vJEE4callEv
- __ZN3WTF6Detail15CallableWrapperIZ55-[_WKAttachment setFileWrapper:contentType:completion:]E4$_70vJEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZ55-[_WKAttachment setFileWrapper:contentType:completion:]E4$_70vJEED1Ev
- __ZN3WTF6VectorINS_3RefINS_8JSONImpl5ValueENS_12RawPtrTraitsIS3_EENS_21DefaultRefDerefTraitsIS3_EEEELm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEE14appendSlowCaseILNS_13FailureActionE0ENS1_INS2_10ObjectBaseENS4_ISE_EENS6_ISE_EEEEEEbOT0_
- __ZN3WTF8JSONImpl7ArrayOfIN9Inspector8Protocol7Browser9ExtensionEE7addItemIS5_EEvONS_3RefINS0_10ObjectBaseENS_12RawPtrTraitsIS9_EENS_21DefaultRefDerefTraitsIS9_EEEE
- __ZN3WTF9HashTableINS_23ObjectIdentifierGenericIN7WebCore19FrameIdentifierTypeENS_38ObjectIdentifierMainThreadAccessTraitsIyEEyEENS_12KeyValuePairIS6_N9Inspector17ProxyingPageAgent23CachedFrameDocumentInfoEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS6_EENS_7HashMapIS6_SA_SF_NS_10HashTraitsIS6_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESI_SM_E4findINS_22IdentityHashTranslatorISO_SF_EELSL_1ES6_EENS_17HashTableIteratorISP_S6_SB_SD_SF_SO_SI_EERKT1_
- __ZN3WTF9HashTableINS_23ObjectIdentifierGenericIN7WebCore19FrameIdentifierTypeENS_38ObjectIdentifierMainThreadAccessTraitsIyEEyEENS_12KeyValuePairIS6_N9Inspector17ProxyingPageAgent23CachedFrameDocumentInfoEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS6_EENS_7HashMapIS6_SA_SF_NS_10HashTraitsIS6_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESI_SM_E6removeEPSB_
- __ZN6WebKit21InspectorBrowserAgent9s_heapRefE
- __ZN6WebKit21InspectorBrowserAgentC2ERNS_19WebPageAgentContextE
- __ZN6WebKit23RemoteMediaSessionProxyC2ERKNS_23RemoteMediaSessionStateERNS_30RemoteMediaSessionManagerProxyE
- __ZN6WebKit30WebExtensionStorageSQLiteStore10getAllKeysEON3WTF17CompletionHandlerIFvNS1_6VectorINS1_6StringELm0ENS1_15CrashOnOverflowELm16ENS1_10FastMallocEEERKS4_EEE
- __ZN6WebKit30WebExtensionStorageSQLiteStore12setKeyedDataEN3WTF7HashMapINS1_6StringES3_NS1_11DefaultHashIS3_EENS1_10HashTraitsIS3_EES7_NS1_15HashTableTraitsELNS1_17ShouldValidateKeyE1ENS1_10FastMallocEEEONS1_17CompletionHandlerIFvNS1_6VectorIS3_Lm0ENS1_15CrashOnOverflowELm16ESA_EERKS3_EEE
- __ZN6WebKit30WebExtensionStorageSQLiteStore19deleteValuesForKeysEN3WTF6VectorINS1_6StringELm0ENS1_15CrashOnOverflowELm16ENS1_10FastMallocEEEONS1_17CompletionHandlerIFvRKS3_EEE
- __ZN6WebKit30WebExtensionStorageSQLiteStore24getStorageSizeForAllKeysEN3WTF7HashMapINS1_6StringES3_NS1_11DefaultHashIS3_EENS1_10HashTraitsIS3_EES7_NS1_15HashTableTraitsELNS1_17ShouldValidateKeyE1ENS1_10FastMallocEEEONS1_17CompletionHandlerIFvmiSB_RKS3_EEE
- __ZN6WebKit35RemoteProgressBasedTimelineRegistry22updateTimelinesForNodeERKN7WebCore26ScrollingTreeScrollingNodeE
- __ZN9Inspector17ProxyingPageAgent14frameDestroyedEN3WTF23ObjectIdentifierGenericIN7WebCore19FrameIdentifierTypeENS1_38ObjectIdentifierMainThreadAccessTraitsIyEEyEE
- __ZN9Inspector17ProxyingPageAgent9s_heapRefE
- __ZN9Inspector17ProxyingPageAgentC2ERN6WebKit19WebPageAgentContextE
- __ZN9Inspector20ProxyingNetworkAgent9s_heapRefE
- __ZN9Inspector20ProxyingNetworkAgentC2ERN6WebKit19WebPageAgentContextE
- __ZN9Inspector8Protocol7Browser9Extension7BuilderILi0EE14setExtensionIdERKN3WTF6StringE
- __ZN9Inspector8Protocol7Browser9Extension7BuilderILi1EE7setNameERKN3WTF6StringE
- __ZNK6WebKit12WebExtension19InjectedContentData34expandedExcludeMatchPatternStringsEv
- __ZNK6WebKit24WebExtensionMatchPattern18hostIsPublicSuffixEv
- __ZNKR6WebKit29WebsiteDataStoreConfiguration11Directories12isolatedCopyEv
- __ZNKSt3__111__copy_implclB9sqn220106IPKN7WebCore18SecurityOriginDataES5_PS3_Li0EEENS_4pairIT_T1_EES8_T0_S9_
- __ZNO6WebKit29WebsiteDataStoreConfiguration11Directories12isolatedCopyEv
- __ZNSt3__123__optional_storage_baseIN7WebCore21NowPlayingInfoArtworkELb0EE13__assign_fromB9sqn220106IRKNS_27__optional_copy_assign_baseIS2_Lb0EEEEEvOT_
- __ZTVN3WTF6Detail15CallableWrapperIZ114-[WKWebsiteDataStore(WKPrivate) _installMockParentalControlsURLFilterForTestingWithBlockedURLs:completionHandler:]E4$_51vJEEE
- __ZTVN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo data]E4$_67vJP13NSFileWrapperEEE
- __ZTVN3WTF6Detail15CallableWrapperIZ25-[_WKAttachmentInfo name]E4$_68vJP13NSFileWrapperEEE
- __ZTVN3WTF6Detail15CallableWrapperIZ32-[_WKAttachmentInfo fileWrapper]E4$_69vJP13NSFileWrapperEEE
- __ZTVN3WTF6Detail15CallableWrapperIZ55-[_WKAttachment setFileWrapper:contentType:completion:]E4$_70vJEEE
- __ZZ36-[_WKApplicationManifest themeColor]EN4$_61D1Ev
- __ZZ41-[_WKApplicationManifest backgroundColor]EN4$_60D1Ev
- __ZZ69+[WKWebsiteDataStore(WKPrivate) _allWebsiteDataTypesIncludingPrivate]ENK4$_52clEv
- ___block_descriptor_33_e8_32c87_ZTSKZ73-[WKWebsiteDataStore(WKPrivate) _abortBackgroundFetch:completionHandler:]E4$_53_e5_v8?0l
- ___block_descriptor_33_e8_32c87_ZTSKZ73-[WKWebsiteDataStore(WKPrivate) _clickBackgroundFetch:completionHandler:]E4$_56_e5_v8?0l
- ___block_descriptor_33_e8_32c87_ZTSKZ73-[WKWebsiteDataStore(WKPrivate) _pauseBackgroundFetch:completionHandler:]E4$_54_e5_v8?0l
- ___block_descriptor_33_e8_32c88_ZTSKZ74-[WKWebsiteDataStore(WKPrivate) _resumeBackgroundFetch:completionHandler:]E4$_55_e5_v8?0l
- ___block_descriptor_48_e8_32c50_ZTSKZ36-[_WKApplicationManifest themeColor]E4$_63_e36_"UIColor"16?0"UITraitCollection"8l
- ___block_descriptor_48_e8_32c55_ZTSKZ41-[_WKApplicationManifest backgroundColor]E4$_62_e36_"UIColor"16?0"UITraitCollection"8l
- ___copy_helper_block_e8_32c50_ZTSKZ36-[_WKApplicationManifest themeColor]E4$_63
- ___copy_helper_block_e8_32c55_ZTSKZ41-[_WKApplicationManifest backgroundColor]E4$_62
- ___copy_helper_block_e8_32c87_ZTSKZ73-[WKWebsiteDataStore(WKPrivate) _abortBackgroundFetch:completionHandler:]E4$_53
- ___copy_helper_block_e8_32c87_ZTSKZ73-[WKWebsiteDataStore(WKPrivate) _clickBackgroundFetch:completionHandler:]E4$_56
- ___copy_helper_block_e8_32c87_ZTSKZ73-[WKWebsiteDataStore(WKPrivate) _pauseBackgroundFetch:completionHandler:]E4$_54
- ___copy_helper_block_e8_32c88_ZTSKZ74-[WKWebsiteDataStore(WKPrivate) _resumeBackgroundFetch:completionHandler:]E4$_55
- ___destroy_helper_block_e8_32c50_ZTSKZ36-[_WKApplicationManifest themeColor]E4$_63
- ___destroy_helper_block_e8_32c55_ZTSKZ41-[_WKApplicationManifest backgroundColor]E4$_62
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1002: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1024: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1049: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1070: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1072: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1085: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1113: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1142: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1144: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1160: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1169: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1182: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1259: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1265: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1303: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1308: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1372: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1472: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1561: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1707: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1791: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1793: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1843: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1865: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1867: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1870: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1884: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1898: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1929: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1960: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1965: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 2035: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 2039: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 806: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 867: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 882: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 920: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 948: Invalid message dispatched %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 981: Invalid message dispatched %s"
+ "22625.1.29.11.27"
+ "NetworkProcess_CanPrefetchDNSForTesting"
+ "NetworkProcess_CanPrefetchDNSForTestingReply"
+ "NetworkProcess_PrefetchedDNSHostnameCountForTesting"
+ "NetworkProcess_PrefetchedDNSHostnameCountForTestingReply"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1001: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1023: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1046: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1067: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1071: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1084: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1112: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1141: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1143: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1159: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1168: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1181: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1258: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1264: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1302: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1307: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1371: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1471: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1560: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1706: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1790: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1792: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1841: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1864: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1866: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1869: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1883: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1897: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1928: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1959: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 1964: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 2034: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 2038: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 805: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 866: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 881: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 919: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 947: Invalid message dispatched %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/WebKit_iosmac/Source/WebKit/NetworkProcess/NetworkConnectionToWebProcess.cpp 980: Invalid message dispatched %s"
- "22625.1.29.11.26"
```
