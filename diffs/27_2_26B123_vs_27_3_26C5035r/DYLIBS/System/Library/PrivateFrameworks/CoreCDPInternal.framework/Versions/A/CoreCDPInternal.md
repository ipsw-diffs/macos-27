## CoreCDPInternal

> `/System/Library/PrivateFrameworks/CoreCDPInternal.framework/Versions/A/CoreCDPInternal`

```diff

-448.125.10.0.0
-  __TEXT.__text: 0x94488
-  __TEXT.__objc_methlist: 0x56d4
+448.250.2.0.0
+  __TEXT.__text: 0x957f0
+  __TEXT.__objc_methlist: 0x5744
   __TEXT.__const: 0x890
-  __TEXT.__oslogstring: 0x14caa
-  __TEXT.__cstring: 0xe156
+  __TEXT.__oslogstring: 0x1502a
+  __TEXT.__cstring: 0xe9e6
   __TEXT.__gcc_except_tab: 0xb4c
   __TEXT.__dlopen_cstrs: 0xbc
   __TEXT.__constg_swiftt: 0x1e4

   __TEXT.__swift_as_ret: 0x58
   __TEXT.__swift_as_cont: 0x68
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x2f38
+  __TEXT.__unwind_info: 0x2f80
   __TEXT.__eh_frame: 0x930
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x180
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3988
+  __DATA_CONST.__objc_selrefs: 0x39f0
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x150
-  __DATA_CONST.__objc_arraydata: 0x220
-  __DATA_CONST.__got: 0x1118
-  __AUTH_CONST.__const: 0x2ec0
-  __AUTH_CONST.__cfstring: 0x9580
-  __AUTH_CONST.__objc_const: 0xfcb8
+  __DATA_CONST.__objc_arraydata: 0x230
+  __DATA_CONST.__got: 0x1158
+  __AUTH_CONST.__const: 0x2f40
+  __AUTH_CONST.__cfstring: 0x9a40
+  __AUTH_CONST.__objc_const: 0xfce8
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__objc_arrayobj: 0xc0
+  __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x800
   __AUTH.__objc_data: 0x170
-  __DATA.__objc_ivar: 0x3c4
+  __DATA.__objc_ivar: 0x3c8
   __DATA.__data: 0x1190
   __DATA.__bss: 0x498
   __DATA_DIRTY.__objc_data: 0x1910

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3235
-  Symbols:   5790
-  CStrings:  2811
+  Functions: 3253
+  Symbols:   5826
+  CStrings:  2863
 
Symbols:
+ +[CDPDPCSController isRecordPasswordGenerationMismatchError:]
+ +[CDPDPCSController passwordVersionMismatchForValidateTelemetry:]
+ -[CDPDAuthProxyImpl recreatePDPRecordWithFallbackForAltDSID:telemetryFlowID:completion:]
+ -[CDPDPDPRecoveryController recreatePDPRecordWithFallbackWithCompletion:]
+ -[CDPDStateMachine _routePostOctagonPDPSetupFailure:completion:]
+ -[CDPDStateMachine _sendPDPServerRecreationEvent:didSucceed:error:]
+ -[CDPDStateMachine _shouldAttemptPDPServerRecreationAfterSetupError:]
+ GCC_except_table62
+ _AKAppleIDAuthenticationServerErrorDomain
+ _OBJC_CLASS_$_AKBasicServerRequest
+ _OBJC_CLASS_$_NSConstantDictionary
+ _OBJC_IVAR_$_CDPDStateMachine._pdpServerRecreationAlreadyAttempted
+ ___61+[CDPDPCSController isRecordPasswordGenerationMismatchError:]_block_invoke
+ ___64-[CDPDStateMachine _routePostOctagonPDPSetupFailure:completion:]_block_invoke
+ ___73-[CDPDPDPRecoveryController recreatePDPRecordWithFallbackWithCompletion:]_block_invoke
+ ___88-[CDPDAuthProxyImpl recreatePDPRecordWithFallbackForAltDSID:telemetryFlowID:completion:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e43_v24?0"AKBasicServerResponse"8"NSError"16l
+ ___block_descriptor_56_e8_32s40s48bs_e37_v32?0Q8"NSDictionary"16"NSError"24l
+ _kCDPAnalyticsPDPServerRecreationFinishEvent
+ _kCDPAnalyticsPDPServerRecreationSetupAfterRecreateEvent
+ _kCDPAnalyticsPDPServerRecreationSkippedEvent
+ _kCDPAnalyticsPDPServerRecreationStartEvent
+ _kCDPAnalyticsPDPSetupHealedOnRevalidateEvent
+ _kPCSErrorDomain
+ _objc_msgSend$_routePostOctagonPDPSetupFailure:completion:
+ _objc_msgSend$_sendPDPServerRecreationEvent:didSucceed:error:
+ _objc_msgSend$_shouldAttemptPDPServerRecreationAfterSetupError:
+ _objc_msgSend$executeIDMSRequestWithContext:completion:
+ _objc_msgSend$httpResponse
+ _objc_msgSend$initWithAltDSID:urlBagKey:
+ _objc_msgSend$isDBRServerRecreationEnabled
+ _objc_msgSend$isRecordPasswordGenerationMismatchError:
+ _objc_msgSend$passwordVersionMismatchForValidateTelemetry:
+ _objc_msgSend$recreatePDPRecordWithFallbackForAltDSID:telemetryFlowID:completion:
+ _objc_msgSend$recreatePDPRecordWithFallbackWithCompletion:
+ _objc_msgSend$setAdditionalHeaders:
+ _objc_msgSend$setRequestBody:
- GCC_except_table60
CStrings:
+ "CDPDStateMachine: DBR password-version mismatch, attempting server-side recreation"
+ "CDPDStateMachine: DBR record healthy after the failed setup, skipping escalation"
+ "CDPDStateMachine: DBR record not healthy after server-side recreation (state: %lu), running setup"
+ "CDPDStateMachine: DBR setup failed on auth, skipping server-side recreation"
+ "CDPDStateMachine: DBR setup still failed after server-side recreation: %@"
+ "CDPDStateMachine: Server-side recreation failed: %@"
+ "CDPDStateMachine: Server-side recreation healed the DBR record"
+ "CDPDStateMachine: Server-side recreation healed the DBR record after setup"
+ "CDPDStateMachine: server-side recreation already attempted in this sign-in, skipping"
+ "PDP: server-side recreation did %@ succeed, error=%{public}@"
+ "PDP: server-side recreation needs an altDSID"
+ "Requesting server-side DBR recreation for %{mask.hash}@"
+ "Server-side DBR recreation returned HTTP status %ld"
+ "altDsId"
+ "application/json"
+ "com.apple.authkit.appleSMSSenderCacheRefreshed"
+ "com.apple.authkit.callsignalsRequested"
+ "com.apple.authkit.codeDisplayedWithinvisibleInk"
+ "com.apple.authkit.grayTextDisclosures"
+ "com.apple.authkit.invisibleInkRemovedFromCode"
+ "com.apple.authkit.localAuthentication"
+ "com.apple.authkit.pushReceived"
+ "com.apple.authkit.signIn.2FAApprovalFlowEnd"
+ "com.apple.authkit.signIn.2FAApprovalFlowStart"
+ "com.apple.authkit.signIn.appleSMSSenderDetected"
+ "com.apple.authkit.signIn.check2FACodeLegitimacy"
+ "com.apple.remoteui.appleid_account_manage_approval_signin"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_closeButtonBarItem_1"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_confirm"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_confirm_post_HSA2Code_1"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_confirm_post_PiggybackingCode_1"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_confirm_post_SMSCode_1"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_confirm_post_SkybridgeCode_1"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_confirm_post_closeButtonBarItem_1"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_confirm_post_multiChoice_1"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_confirm_post_page"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_deny"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_deny_multiChoice_1"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_deny_multiChoice_2"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_deny_page"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_labelRow_1"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_labelRow_2"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_multiChoice_1"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_multiChoice_2"
+ "com.apple.remoteui.appleid_account_manage_approval_signin_page"
+ "com.apple.remoteui.appleid_account_manage_security_password"
+ "com.apple.remoteui.auth_header_1"
+ "com.apple.remoteui.auth_navigationBar_1"
+ "com.apple.remoteui.auth_page"
+ "com.apple.remoteui.auth_verify_biometrics"
+ "pdpRecreateWithFallback"
+ "v24@?0@\"AKBasicServerResponse\"8@\"NSError\"16"
```
