## AOSUI

> `/System/Library/PrivateFrameworks/AOSUI.framework/Versions/A/AOSUI`

```diff

-921.250.1.0.0
-  __TEXT.__text: 0x10e210
-  __TEXT.__objc_methlist: 0x10c4c
+921.250.3.0.0
+  __TEXT.__text: 0x10ec50
+  __TEXT.__objc_methlist: 0x10c9c
   __TEXT.__const: 0x2d8
-  __TEXT.__cstring: 0x12a65
-  __TEXT.__oslogstring: 0xcdcc
-  __TEXT.__gcc_except_tab: 0x1774
+  __TEXT.__cstring: 0x12b92
+  __TEXT.__oslogstring: 0xce90
+  __TEXT.__gcc_except_tab: 0x17b4
   __TEXT.__ustring: 0x132
   __TEXT.__dlopen_cstrs: 0x1f4
-  __TEXT.__unwind_info: 0x6158
+  __TEXT.__unwind_info: 0x6178
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x60
   __DATA_CONST.__objc_protolist: 0x260
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9760
+  __DATA_CONST.__objc_selrefs: 0x97c0
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__objc_superrefs: 0x478
   __DATA_CONST.__objc_arraydata: 0x108
-  __DATA_CONST.__got: 0x1898
-  __AUTH_CONST.__const: 0x4320
-  __AUTH_CONST.__cfstring: 0xc8e0
-  __AUTH_CONST.__objc_const: 0x2f390
+  __DATA_CONST.__got: 0x18a8
+  __AUTH_CONST.__const: 0x4350
+  __AUTH_CONST.__cfstring: 0xc920
+  __AUTH_CONST.__objc_const: 0x2f410
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x180

   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x35c0
   __AUTH.__data: 0x9e8
-  __DATA.__objc_ivar: 0x14a4
+  __DATA.__objc_ivar: 0x14b0
   __DATA.__data: 0x22a0
   __DATA.__bss: 0x2b0
   __DATA.__common: 0x28

   - /usr/lib/libDiagnosticMessagesClient.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 7270
-  Symbols:   14491
-  CStrings:  3311
+  Functions: 7282
+  Symbols:   14516
+  CStrings:  3322
 
Symbols:
+ -[AOSUIAccountContactsController removeCustodianForContact:telemetryFlowID:completion:]
+ -[AOSUIMyCustodianActionHandler _presentRemoveFailedAlertForViewController:]
+ -[MMTermsOfServiceController _saveTermsAcceptance:]
+ -[MMTermsOfServiceController _showWebViewTermsForWindow:]
+ -[MMTermsOfServiceController acceptedTermsController]
+ -[MMTermsOfServiceController setAcceptedTermsController:]
+ -[MMTermsOfServiceController setWebViewTermsWindow:]
+ -[MMTermsOfServiceController webViewTermsWindow]
+ _OBJC_CLASS_$_AACustodianUpdateRequestContext
+ _OBJC_CLASS_$_AAUrlBagHelper
+ _OBJC_IVAR_$_AOSUIMyCustodianActionHandler._telemetryFlowID
+ _OBJC_IVAR_$_MMTermsOfServiceController._acceptedTermsController
+ _OBJC_IVAR_$_MMTermsOfServiceController._webViewTermsWindow
+ ___51-[MMTermsOfServiceController _saveTermsAcceptance:]_block_invoke
+ ___57-[MMTermsOfServiceController _showWebViewTermsForWindow:]_block_invoke
+ ___75-[MMTermsOfServiceController showTermsOfServiceDialogForWindow:completion:]_block_invoke_2
+ ___76-[AOSUIMyCustodianActionHandler _presentRemoveFailedAlertForViewController:]_block_invoke
+ ___87-[AOSUIAccountContactsController removeCustodianForContact:telemetryFlowID:completion:]_block_invoke
+ ___block_descriptor_40_e8_32s_e25_v20?0B8"NSDictionary"12l
+ _objc_msgSend$_presentRemoveFailedAlertForViewController:
+ _objc_msgSend$_saveTermsAcceptance:
+ _objc_msgSend$_showWebViewTermsForWindow:
+ _objc_msgSend$acceptedTermsController
+ _objc_msgSend$initWithCustodianID:
+ _objc_msgSend$isRemoteUITermsEnabledWithCompletion:
+ _objc_msgSend$presentTermsForAccount:termsEntries:deviceOSVersion:inWindow:completion:
+ _objc_msgSend$primaryAuthKitAccount
+ _objc_msgSend$removeCustodianForContact:telemetryFlowID:completion:
+ _objc_msgSend$removeCustodianWithContext:completion:
+ _objc_msgSend$setIsSyncAction:
- -[AOSUIAccountContactsController removeCustodianForContact:completion:]
- ___71-[AOSUIAccountContactsController removeCustodianForContact:completion:]_block_invoke
- ___76-[MMTermsOfServiceController mmWebKitViewControllerAgreedToTerms:termsInfo:]_block_invoke
- _objc_msgSend$removeCustodian:completion:
- _objc_msgSend$removeCustodianForContact:completion:
CStrings:
+ "%s RemoteUI ToS finished, agreed: %@, accepted terms entries: %lu"
+ "%s Showing ToS in RemoteUI"
+ "%s Showing ToS in the webview"
+ "%s remoteUITermsEnabled: %@"
+ "-[MMTermsOfServiceController _showWebViewTermsForWindow:]"
+ "-[MMTermsOfServiceController _showWebViewTermsForWindow:]_block_invoke"
+ "-[MMTermsOfServiceController showTermsOfServiceDialogForWindow:completion:]_block_invoke_2"
+ "Prompt %@ is not presented, ignoring dismiss"
+ "REMOVE_RECOVERY_CONTACT_FAILED_ALERT_MESSAGE"
+ "TRY_AGAIN"
+ "v20@?0B8@\"NSDictionary\"12"
```
