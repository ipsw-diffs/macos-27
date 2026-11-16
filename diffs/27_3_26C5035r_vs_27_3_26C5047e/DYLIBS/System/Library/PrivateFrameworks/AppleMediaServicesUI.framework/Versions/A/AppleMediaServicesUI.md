## AppleMediaServicesUI

> `/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/Versions/A/AppleMediaServicesUI`

```diff

-8.2.9.1.1
-  __TEXT.__text: 0x1d92c8
-  __TEXT.__objc_methlist: 0xede4
+8.2.15.0.0
+  __TEXT.__text: 0x1dd9d0
+  __TEXT.__objc_methlist: 0xee94
   __TEXT.__const: 0xf1f4
-  __TEXT.__gcc_except_tab: 0xe04
-  __TEXT.__oslogstring: 0x89cb
-  __TEXT.__cstring: 0xe0cb
+  __TEXT.__gcc_except_tab: 0xe28
+  __TEXT.__oslogstring: 0x8bdb
+  __TEXT.__cstring: 0xe2bb
   __TEXT.__dlopen_cstrs: 0x9ab
-  __TEXT.__constg_swiftt: 0x5e00
-  __TEXT.__swift5_typeref: 0x110be
+  __TEXT.__constg_swiftt: 0x5e08
+  __TEXT.__swift5_typeref: 0x110ec
   __TEXT.__swift5_builtin: 0x21c
-  __TEXT.__swift5_reflstr: 0x3195
+  __TEXT.__swift5_reflstr: 0x3185
   __TEXT.__swift5_fieldmd: 0x3704
   __TEXT.__swift5_assocty: 0x1220
   __TEXT.__swift5_proto: 0x5c4
   __TEXT.__swift5_types: 0x490
-  __TEXT.__swift5_capture: 0x1a30
+  __TEXT.__swift5_capture: 0x1a7c
   __TEXT.__swift_as_entry: 0x1dc
   __TEXT.__swift_as_ret: 0x248
   __TEXT.__swift_as_cont: 0x5dc
   __TEXT.__swift5_protos: 0x30
   __TEXT.__swift5_mpenum: 0x50
-  __TEXT.__unwind_info: 0xa330
-  __TEXT.__eh_frame: 0x74b4
+  __TEXT.__unwind_info: 0xa3c0
+  __TEXT.__eh_frame: 0x7544
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x310
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7680
+  __DATA_CONST.__objc_selrefs: 0x7748
   __DATA_CONST.__objc_protorefs: 0x128
   __DATA_CONST.__objc_superrefs: 0x5d8
-  __DATA_CONST.__objc_arraydata: 0x348
-  __DATA_CONST.__got: 0x1960
-  __AUTH_CONST.__const: 0xc620
-  __AUTH_CONST.__cfstring: 0xa180
-  __AUTH_CONST.__objc_const: 0x1e890
+  __DATA_CONST.__objc_arraydata: 0x3d8
+  __DATA_CONST.__got: 0x1998
+  __AUTH_CONST.__const: 0xc7b0
+  __AUTH_CONST.__cfstring: 0xa2c0
+  __AUTH_CONST.__objc_const: 0x1e930
   __AUTH_CONST.__objc_intobj: 0x270
-  __AUTH_CONST.__objc_dictobj: 0x2d0
+  __AUTH_CONST.__objc_dictobj: 0x3e8
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x120
-  __AUTH_CONST.__auth_got: 0x24a8
-  __AUTH.__objc_data: 0x7e90
-  __AUTH.__data: 0x5f88
-  __DATA.__objc_ivar: 0xfe8
-  __DATA.__data: 0x6860
+  __AUTH_CONST.__auth_got: 0x24b8
+  __AUTH.__objc_data: 0x7e98
+  __AUTH.__data: 0x5f98
+  __DATA.__objc_ivar: 0xff4
+  __DATA.__data: 0x68a0
   __DATA.__bss: 0xbe78
   __DATA.__common: 0x308
   __DATA_DIRTY.__objc_data: 0xfe8

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 14526
-  Symbols:   14396
-  CStrings:  2690
+  Functions: 14569
+  Symbols:   14459
+  CStrings:  2713
 
Symbols:
+ +[AMSUIAlertDialogTask(MetricsTiming) _beginMetricsTimingNowOnRequest:]
+ +[AMSUIAlertDialogTask(MetricsTiming) _beginMetricsTimingOnRequest:initiationTime:]
+ +[AMSUIAlertDialogTask(MetricsTiming) _recordMetricsTimingNowForKey:onRequest:]
+ +[AMSUIAlertDialogTask(MetricsTiming) _setMetricsTimingValue:forKey:onRequest:]
+ +[AMSUIAlertDialogTask(MetricsTiming) _updateMetricsTimingOnRequest:resetting:usingBlock:]
+ +[AMSUIWebView _resourceTrustRulesForDomains:]
+ +[AMSUIWebView _topDocumentTrustRulesForDomains:]
+ -[AMSUIAlertDialogTask didProgrammaticallyDismiss]
+ -[AMSUIAlertDialogTask setDidProgrammaticallyDismiss:]
+ -[AMSUIMessageView customBackgroundColor]
+ -[AMSUIMessageView setCustomBackgroundColor:]
+ -[AMSUIWebCameraReaderPageModel _shouldUseIDCaptureTestImages]
+ -[AMSUIWebClientContext disableResourceTrustRules]
+ -[AMSUIWebClientContext disableScriptMessageFrameCheck]
+ -[AMSUIWebClientContext purchaseIdentifier]
+ -[AMSUIWebView _handleScriptMessage:logKey:replyHandler:]
+ GCC_except_table35
+ GCC_except_table64
+ GCC_except_table70
+ GCC_except_table9
+ _AMSDialogMetricsTimingKeyInitiationTime
+ _AMSDialogMetricsTimingKeyUserResponseTime
+ _AMSDialogRequestUserInfoKeyMetricsTiming
+ _AMSMetricsEventTypeDialog
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_IVAR_$_AMSUIAlertDialogTask._didProgrammaticallyDismiss
+ _OBJC_IVAR_$_AMSUIMessageView._customBackgroundColor
+ _OBJC_IVAR_$_AMSUIWebClientContext._disableResourceTrustRules
+ _OBJC_IVAR_$_AMSUIWebClientContext._disableScriptMessageFrameCheck
+ _OUTLINED_FUNCTION_148
+ _OUTLINED_FUNCTION_149
+ __OBJC_$_CLASS_METHODS_AMSUIAlertDialogTask(MetricsTiming)
+ ___57-[AMSUIWebView _handleScriptMessage:logKey:replyHandler:]_block_invoke
+ ___75-[AMSUIWebView userContentController:didReceiveScriptMessage:replyHandler:]_block_invoke_2
+ ___79+[AMSUIAlertDialogTask(MetricsTiming) _setMetricsTimingValue:forKey:onRequest:]_block_invoke
+ ___83+[AMSUIAlertDialogTask(MetricsTiming) _beginMetricsTimingOnRequest:initiationTime:]_block_invoke
+ ___block_descriptor_40_e8_32s_e29_v16?0"NSMutableDictionary"8l
+ ___block_descriptor_48_e8_32s40s_e29_v16?0"NSMutableDictionary"8l
+ ___block_descriptor_64_e8_32s40s48s56s_e32_v28?0"NSArray"8B16"NSError"20l
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e20_v20?0B8"NSError"12l
+ ___copy_helper_block_e8_32s40s48s56b64w
+ _objc_msgSend$_beginMetricsTimingNowOnRequest:
+ _objc_msgSend$_beginMetricsTimingOnRequest:initiationTime:
+ _objc_msgSend$_handleScriptMessage:logKey:replyHandler:
+ _objc_msgSend$_recordMetricsTimingNowForKey:onRequest:
+ _objc_msgSend$_resourceTrustRulesForDomains:
+ _objc_msgSend$_setMetricsTimingValue:forKey:onRequest:
+ _objc_msgSend$_topDocumentTrustRulesForDomains:
+ _objc_msgSend$_updateMetricsTimingOnRequest:resetting:usingBlock:
+ _objc_msgSend$characterSetWithCharactersInString:
+ _objc_msgSend$didProgrammaticallyDismiss
+ _objc_msgSend$disableResourceTrustRules
+ _objc_msgSend$disableScriptMessageFrameCheck
+ _objc_msgSend$escapedPatternForString:
+ _objc_msgSend$frameInfo
+ _objc_msgSend$isMainFrame
+ _objc_msgSend$modalWindow
+ _objc_msgSend$protocol
+ _objc_msgSend$purchaseIdentifier
+ _objc_msgSend$securityOrigin
+ _objc_msgSend$setCustomBackgroundColor:
+ _objc_msgSend$setDidProgrammaticallyDismiss:
+ _objc_msgSend$setHost:
+ _objc_msgSend$setPurchaseIdentifier:
+ _objc_msgSend$setScheme:
+ _objc_msgSend$stringByTrimmingCharactersInSet:
+ _objc_msgSend$useIDCaptureTestImages
+ _symbolic SDySSypGIegg_
+ _symbolic SDySSypGz_Xx
+ _symbolic SS3key_yp5valuet
- -[AMSUIMessageView isUsingCustomBackground]
- -[AMSUIMessageView setIsUsingCustomBackground:]
- GCC_except_table63
- _OBJC_IVAR_$_AMSUIMessageView._isUsingCustomBackground
- __OBJC_$_CLASS_METHODS_AMSUIAlertDialogTask
- ___block_descriptor_56_e8_32s40s48s_e32_v28?0"NSArray"8B16"NSError"20l
- _objc_msgSend$setIsUsingCustomBackground:
CStrings:
+ "%{public}@: [%{public}@] Rejecting script message from opaque origin"
+ "%{public}@: [%{public}@] Rejecting script message from subframe: %{public}@"
+ "%{public}@: [%{public}@] Rejecting script message from untrusted origin: %{public}@ %{public}@"
+ "%{public}@: [%{public}@] Rejecting script message, context is unavailable"
+ "%{public}@: [%{public}@] Resource trust rules disabled by bag."
+ "([^/@]+\\.)?"
+ "A"
+ "AMS INTERNAL ERROR: Context Unavailable"
+ "AMS INTERNAL ERROR: Untrusted Frame"
+ "AMS INTERNAL ERROR: Web View Deallocated"
+ "Could not build the share URL from the manageGroupSubscription URL"
+ "ERROR_NO_INTERNET_MESSAGE_WIFI"
+ "ERROR_NO_INTERNET_MESSAGE_WLAN"
+ "Failed to create metrics identifier store: "
+ "Request has no originalTransactionId"
+ "[%{public}@] %{public}@ present, resource trust rules will be disabled."
+ "[%{public}@] %{public}@ present, script message frame check will be disabled."
+ "^blob:"
+ "^https://%@%@(:[0-9]+)?/"
+ "disableWebResourceTrustRules"
+ "disableWebScriptMessageFrameCheck"
+ "ignore-previous-rules"
+ "originalTransactionId"
+ "purchaseId"
+ "v16@?0@\"NSMutableDictionary\"8"
- "WIFI_NETWORK_ERROR_MESSAGE"
- "WLAN_NETWORK_ERROR_MESSAGE"
```
