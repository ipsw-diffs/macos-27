## AppleMediaServicesUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/Versions/A/AppleMediaServicesUI`

```diff

-8.2.9.1.1
-  __TEXT.__text: 0x1dcc50
-  __TEXT.__objc_methlist: 0x10e8c
-  __TEXT.__const: 0xe7e4
-  __TEXT.__cstring: 0xe37b
-  __TEXT.__oslogstring: 0x96ab
+8.2.15.0.0
+  __TEXT.__text: 0x1e3720
+  __TEXT.__objc_methlist: 0x10f9c
+  __TEXT.__const: 0xe814
+  __TEXT.__cstring: 0xe64b
+  __TEXT.__oslogstring: 0x98fb
   __TEXT.__ustring: 0x13a
-  __TEXT.__gcc_except_tab: 0x11bc
+  __TEXT.__gcc_except_tab: 0x11dc
   __TEXT.__dlopen_cstrs: 0x9b8
-  __TEXT.__constg_swiftt: 0x5d18
-  __TEXT.__swift5_typeref: 0xf708
+  __TEXT.__constg_swiftt: 0x5dd8
+  __TEXT.__swift5_typeref: 0xf750
   __TEXT.__swift5_builtin: 0x1f4
-  __TEXT.__swift5_reflstr: 0x2f25
-  __TEXT.__swift5_fieldmd: 0x362c
+  __TEXT.__swift5_reflstr: 0x2f65
+  __TEXT.__swift5_fieldmd: 0x3664
   __TEXT.__swift5_assocty: 0x11c8
   __TEXT.__swift5_proto: 0x55c
-  __TEXT.__swift5_types: 0x490
-  __TEXT.__swift5_capture: 0x19b0
+  __TEXT.__swift5_types: 0x498
+  __TEXT.__swift5_capture: 0x19fc
   __TEXT.__swift5_protos: 0x30
   __TEXT.__swift_as_entry: 0x1d8
   __TEXT.__swift_as_ret: 0x230
   __TEXT.__swift_as_cont: 0x588
   __TEXT.__swift5_mpenum: 0x50
-  __TEXT.__unwind_info: 0xa550
-  __TEXT.__eh_frame: 0x6ec0
+  __TEXT.__unwind_info: 0xa6b0
+  __TEXT.__eh_frame: 0x7188
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3be0
-  __DATA_CONST.__objc_classlist: 0xb08
+  __DATA_CONST.__const: 0x3c80
+  __DATA_CONST.__objc_classlist: 0xb18
   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x3b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8bb0
+  __DATA_CONST.__objc_selrefs: 0x8c70
   __DATA_CONST.__objc_protorefs: 0x148
   __DATA_CONST.__objc_superrefs: 0x658
-  __DATA_CONST.__objc_arraydata: 0x340
-  __DATA_CONST.__got: 0x1b60
-  __AUTH_CONST.__const: 0x9bc0
-  __AUTH_CONST.__cfstring: 0xab00
-  __AUTH_CONST.__objc_const: 0x212e0
+  __DATA_CONST.__objc_arraydata: 0x3d0
+  __DATA_CONST.__got: 0x1b90
+  __AUTH_CONST.__const: 0x9cc0
+  __AUTH_CONST.__cfstring: 0xac40
+  __AUTH_CONST.__objc_const: 0x21448
   __AUTH_CONST.__objc_intobj: 0x318
-  __AUTH_CONST.__objc_dictobj: 0x258
+  __AUTH_CONST.__objc_dictobj: 0x370
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x108
-  __AUTH_CONST.__auth_got: 0x2778
-  __AUTH.__objc_data: 0x8c60
-  __AUTH.__data: 0x5750
-  __DATA.__objc_ivar: 0x1114
-  __DATA.__data: 0x6950
+  __AUTH_CONST.__auth_got: 0x2798
+  __AUTH.__objc_data: 0x8e28
+  __AUTH.__data: 0x5790
+  __DATA.__objc_ivar: 0x111c
+  __DATA.__data: 0x69d0
   __DATA.__objc_stublist: 0x10
   __DATA.__bss: 0xb200
-  __DATA.__common: 0x308
+  __DATA.__common: 0x320
   __DATA_DIRTY.__objc_data: 0x1088
   __DATA_DIRTY.__data: 0x148
   __DATA_DIRTY.__bss: 0x58

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 14823
-  Symbols:   16032
-  CStrings:  2789
+  Functions: 14903
+  Symbols:   16102
+  CStrings:  2816
 
Symbols:
+ +[AMSUIAlertDialogTask(MetricsTiming) _beginMetricsTimingNowOnRequest:]
+ +[AMSUIAlertDialogTask(MetricsTiming) _beginMetricsTimingOnRequest:initiationTime:]
+ +[AMSUIAlertDialogTask(MetricsTiming) _recordMetricsTimingNowForKey:onRequest:]
+ +[AMSUIAlertDialogTask(MetricsTiming) _setMetricsTimingValue:forKey:onRequest:]
+ +[AMSUIAlertDialogTask(MetricsTiming) _updateMetricsTimingOnRequest:resetting:usingBlock:]
+ +[AMSUIWebView _resourceTrustRulesForDomains:]
+ +[AMSUIWebView _topDocumentTrustRulesForDomains:]
+ -[AMSUIMessageView customBackgroundColor]
+ -[AMSUIMessageView setCustomBackgroundColor:]
+ -[AMSUIWebCameraReaderPageModel _shouldUseIDCaptureTestImages]
+ -[AMSUIWebClientContext disableResourceTrustRules]
+ -[AMSUIWebClientContext disableScriptMessageFrameCheck]
+ -[AMSUIWebClientContext purchaseIdentifier]
+ -[AMSUIWebView _handleScriptMessage:logKey:replyHandler:]
+ GCC_except_table24
+ GCC_except_table54
+ _AMSDialogMetricsTimingKeyInitiationTime
+ _AMSDialogMetricsTimingKeyOnScreenResourcesAppearEndTime
+ _AMSDialogMetricsTimingKeyUserResponseTime
+ _AMSDialogRequestUserInfoKeyMetricsTiming
+ _AMSMetricsEventTypeDialog
+ _OBJC_CLASS_$_AMSUIWebTestImageCaptureViewControllerProvider
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_CLASS_$__TtC20AppleMediaServicesUI30TestImageCaptureViewController
+ _OBJC_IVAR_$_AMSUIMessageView._customBackgroundColor
+ _OBJC_IVAR_$_AMSUIWebClientContext._disableResourceTrustRules
+ _OBJC_IVAR_$_AMSUIWebClientContext._disableScriptMessageFrameCheck
+ _OBJC_METACLASS_$_AMSUIWebTestImageCaptureViewControllerProvider
+ _OBJC_METACLASS_$__TtC20AppleMediaServicesUI30TestImageCaptureViewController
+ __CLASS_METHODS_AMSUIWebTestImageCaptureViewControllerProvider
+ __DATA_AMSUIWebTestImageCaptureViewControllerProvider
+ __DATA__TtC20AppleMediaServicesUI30TestImageCaptureViewController
+ __INSTANCE_METHODS_AMSUIWebTestImageCaptureViewControllerProvider
+ __INSTANCE_METHODS__TtC20AppleMediaServicesUI30TestImageCaptureViewController
+ __IVARS__TtC20AppleMediaServicesUI30TestImageCaptureViewController
+ __METACLASS_DATA_AMSUIWebTestImageCaptureViewControllerProvider
+ __METACLASS_DATA__TtC20AppleMediaServicesUI30TestImageCaptureViewController
+ __OBJC_$_CLASS_METHODS_AMSUIAlertDialogTask(MetricsTiming)
+ __PROTOCOLS__TtC20AppleMediaServicesUI30TestImageCaptureViewController
+ ___57-[AMSUIWebView _handleScriptMessage:logKey:replyHandler:]_block_invoke
+ ___75-[AMSUIWebView userContentController:didReceiveScriptMessage:replyHandler:]_block_invoke_2
+ ___79+[AMSUIAlertDialogTask(MetricsTiming) _setMetricsTimingValue:forKey:onRequest:]_block_invoke
+ ___83+[AMSUIAlertDialogTask(MetricsTiming) _beginMetricsTimingOnRequest:initiationTime:]_block_invoke
+ ___block_descriptor_40_e8_32s_e29_v16?0"NSMutableDictionary"8ls32l8
+ ___block_descriptor_48_e8_32s40s_e29_v16?0"NSMutableDictionary"8ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56s_e32_v28?0"NSArray"8B16"NSError"20ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e20_v20?0B8"NSError"12lw64l8s56l8s32l8s40l8s48l8
+ ___block_descriptor_81_e8_32s40s48s56s64bs72w_e5_v8?0lw72l8s64l8s32l8s40l8s48l8s56l8
+ _objc_msgSend$_beginMetricsTimingNowOnRequest:
+ _objc_msgSend$_beginMetricsTimingOnRequest:initiationTime:
+ _objc_msgSend$_handleScriptMessage:logKey:replyHandler:
+ _objc_msgSend$_recordMetricsTimingNowForKey:onRequest:
+ _objc_msgSend$_resourceTrustRulesForDomains:
+ _objc_msgSend$_setMetricsTimingValue:forKey:onRequest:
+ _objc_msgSend$_shouldUseIDCaptureTestImages
+ _objc_msgSend$_topDocumentTrustRulesForDomains:
+ _objc_msgSend$_updateMetricsTimingOnRequest:resetting:usingBlock:
+ _objc_msgSend$characterSetWithCharactersInString:
+ _objc_msgSend$contentsOfDirectoryAtURL:includingPropertiesForKeys:options:error:
+ _objc_msgSend$createControllerWithModel:
+ _objc_msgSend$customBackgroundColor
+ _objc_msgSend$disableResourceTrustRules
+ _objc_msgSend$disableScriptMessageFrameCheck
+ _objc_msgSend$escapedPatternForString:
+ _objc_msgSend$frameInfo
+ _objc_msgSend$isMainFrame
+ _objc_msgSend$protocol
+ _objc_msgSend$purchaseIdentifier
+ _objc_msgSend$securityOrigin
+ _objc_msgSend$setCustomBackgroundColor:
+ _objc_msgSend$setHost:
+ _objc_msgSend$setPurchaseIdentifier:
+ _objc_msgSend$setScheme:
+ _objc_msgSend$stringByTrimmingCharactersInSet:
+ _objc_msgSend$useIDCaptureTestImages
+ _symbolic SDySSypGIegg_
+ _symbolic SDySSypGz_Xx
+ _symbolic SS3key_yp5valuet
+ _symbolic _____ 20AppleMediaServicesUI30TestImageCaptureViewControllerC
+ _symbolic _____ 20AppleMediaServicesUI38TestImageCaptureViewControllerProviderC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation3URLV
- -[AMSUIMessageView isUsingCustomBackground]
- -[AMSUIMessageView setIsUsingCustomBackground:]
- GCC_except_table48
- _OBJC_IVAR_$_AMSUIMessageView._isUsingCustomBackground
- _OUTLINED_FUNCTION_132
- _OUTLINED_FUNCTION_133
- _OUTLINED_FUNCTION_134
- __OBJC_$_CLASS_METHODS_AMSUIAlertDialogTask
- ___block_descriptor_56_e8_32s40s48s_e32_v28?0"NSArray"8B16"NSError"20ls32l8s40l8s48l8
- _objc_msgSend$isUsingCustomBackground
- _objc_msgSend$setIsUsingCustomBackground:
CStrings:
+ "%{public}@: [%{public}@] Rejecting script message from opaque origin"
+ "%{public}@: [%{public}@] Rejecting script message from subframe: %{public}@"
+ "%{public}@: [%{public}@] Rejecting script message from untrusted origin: %{public}@ %{public}@"
+ "%{public}@: [%{public}@] Rejecting script message, context is unavailable"
+ "%{public}@: [%{public}@] Resource trust rules disabled by bag."
+ "%{public}@Using ID capture test images instead of the camera"
+ "([^/@]+\\.)?"
+ "AMS INTERNAL ERROR: Context Unavailable"
+ "AMS INTERNAL ERROR: Untrusted Frame"
+ "AMS INTERNAL ERROR: Web View Deallocated"
+ "Add images in internal settings under Age Verification > ID Capture Images."
+ "AppleMediaServicesUI.TestImageCaptureViewController"
+ "AppleMediaServicesUI/AMSUIWebTestImageCaptureViewController.swift"
+ "Could not load ID capture test image"
+ "ERROR_NO_INTERNET_MESSAGE_WIFI"
+ "ERROR_NO_INTERNET_MESSAGE_WLAN"
+ "Failed to create metrics identifier store: "
+ "Finishing with test image data"
+ "No ID capture test images"
+ "Using test image: "
+ "[%{public}@] %{public}@ present, resource trust rules will be disabled."
+ "[%{public}@] %{public}@ present, script message frame check will be disabled."
+ "^blob:"
+ "^https://%@%@(:[0-9]+)?/"
+ "disableWebResourceTrustRules"
+ "disableWebScriptMessageFrameCheck"
+ "ignore-previous-rules"
+ "purchaseId"
+ "v16@?0@\"NSMutableDictionary\"8"
- "WIFI_NETWORK_ERROR_MESSAGE"
- "WLAN_NETWORK_ERROR_MESSAGE"
```
