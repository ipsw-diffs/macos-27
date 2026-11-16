## AppleAccount

> `/System/Library/PrivateFrameworks/AppleAccount.framework/Versions/A/AppleAccount`

```diff

-1069.250.3.0.0
-  __TEXT.__text: 0x279a34
-  __TEXT.__objc_methlist: 0xb3ec
-  __TEXT.__cstring: 0x10771
+1069.250.6.0.0
+  __TEXT.__text: 0x27aeb4
+  __TEXT.__objc_methlist: 0xb504
+  __TEXT.__cstring: 0x10ac1
   __TEXT.__const: 0x484b0
-  __TEXT.__oslogstring: 0x12c0d
-  __TEXT.__gcc_except_tab: 0x1ad8
+  __TEXT.__oslogstring: 0x12d0d
+  __TEXT.__gcc_except_tab: 0x1b14
   __TEXT.__dlopen_cstrs: 0x2d3
   __TEXT.__swift5_typeref: 0x334a
   __TEXT.__constg_swiftt: 0x26a0

   __TEXT.__swift_as_ret: 0x244
   __TEXT.__swift_as_cont: 0x450
   __TEXT.__swift5_capture: 0x7b8
-  __TEXT.__unwind_info: 0x7bc0
+  __TEXT.__unwind_info: 0x7c28
   __TEXT.__eh_frame: 0x6970
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x26b0
-  __DATA_CONST.__objc_classlist: 0x898
+  __DATA_CONST.__const: 0x2700
+  __DATA_CONST.__objc_classlist: 0x8a0
   __DATA_CONST.__objc_catlist: 0xa0
   __DATA_CONST.__objc_protolist: 0x248
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5170
+  __DATA_CONST.__objc_selrefs: 0x51e8
   __DATA_CONST.__objc_protorefs: 0xe0
-  __DATA_CONST.__objc_superrefs: 0x588
+  __DATA_CONST.__objc_superrefs: 0x590
   __DATA_CONST.__objc_arraydata: 0xe0
-  __DATA_CONST.__got: 0x1030
-  __AUTH_CONST.__const: 0x10b00
-  __AUTH_CONST.__cfstring: 0xd060
-  __AUTH_CONST.__objc_const: 0x26410
+  __DATA_CONST.__got: 0x1038
+  __AUTH_CONST.__const: 0x10b90
+  __AUTH_CONST.__cfstring: 0xd220
+  __AUTH_CONST.__objc_const: 0x26648
   __AUTH_CONST.__objc_intobj: 0x138
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x12c0
-  __AUTH.__objc_data: 0xa0
-  __DATA.__objc_ivar: 0xbd4
-  __DATA.__data: 0x2858
+  __AUTH.__objc_data: 0xf0
+  __DATA.__objc_ivar: 0xbf8
+  __DATA.__data: 0x2868
   __DATA.__bss: 0x14c90
   __DATA.__common: 0xa48
   __DATA_DIRTY.__objc_data: 0x5ba0

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 8816
-  Symbols:   11290
-  CStrings:  3550
+  Functions: 8842
+  Symbols:   11359
+  CStrings:  3569
 
Symbols:
+ +[NSError(AppleAccount) aa_cloudKitErrorForXPCReply:]
+ -[AACustodianController repairCustodians:telemetryFlowID:completion:]
+ -[AAFollowUpController _verifyTermsCFUMessageWithUserInfo:]
+ -[AAMessagingService _invokeSendResultHandler:withOutcome:]
+ -[AAMessagingService _reportedErrorForIDSSendError:]
+ -[AAMessagingService _sendMessage:destinations:sendFromHandleUri:responseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:wantsDeliveryAcknowledgement:sendResultHandler:error:]
+ -[AAMessagingService aliasUris:containSenderAliasUri:]
+ -[AAMessagingService canSend]
+ -[AAMessagingService isRegisteredSenderAliasUri:]
+ -[AAMessagingService registerSendResultHandler:forIdentifier:]
+ -[AAMessagingService requiredReachabilityForDestination:completion:]
+ -[AAMessagingService sendMessage:destinations:sendFromHandleUri:responseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:sendResultHandler:error:]
+ -[AASendResultOutcome .cxx_destruct]
+ -[AASendResultOutcome error]
+ -[AASendResultOutcome initWithSuccess:error:]
+ -[AASendResultOutcome success]
+ GCC_except_table103
+ GCC_except_table135
+ GCC_except_table139
+ GCC_except_table27
+ GCC_except_table34
+ GCC_except_table46
+ GCC_except_table66
+ GCC_except_table77
+ GCC_except_table80
+ GCC_except_table96
+ _AAFollowUpUserInfoAccountUsername
+ _AAFollowUpUserInfoTelemetryFlowID
+ _AAStoreBoundedLocked
+ _OBJC_CLASS_$_AASendResultOutcome
+ _OBJC_IVAR_$_AAMessagingService._earlySendResultOrder
+ _OBJC_IVAR_$_AAMessagingService._earlySendResults
+ _OBJC_IVAR_$_AAMessagingService._reachabilityQueryTimeout
+ _OBJC_IVAR_$_AAMessagingService._sendResultHandlerLock
+ _OBJC_IVAR_$_AAMessagingService._sendResultHandlerOrder
+ _OBJC_IVAR_$_AAMessagingService._sendResultHandlers
+ _OBJC_IVAR_$_AAMessagingService._sendResultQueue
+ _OBJC_IVAR_$_AASendResultOutcome._error
+ _OBJC_IVAR_$_AASendResultOutcome._success
+ _OBJC_METACLASS_$_AASendResultOutcome
+ __OBJC_$_INSTANCE_METHODS_AASendResultOutcome
+ __OBJC_$_INSTANCE_VARIABLES_AASendResultOutcome
+ __OBJC_$_PROP_LIST_AASendResultOutcome
+ __OBJC_CLASS_RO_$_AASendResultOutcome
+ __OBJC_METACLASS_RO_$_AASendResultOutcome
+ ___193-[AAMessagingService _sendMessage:destinations:sendFromHandleUri:responseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:wantsDeliveryAcknowledgement:sendResultHandler:error:]_block_invoke
+ ___59-[AAMessagingService _invokeSendResultHandler:withOutcome:]_block_invoke
+ ___68-[AAMessagingService requiredReachabilityForDestination:completion:]_block_invoke
+ ___69-[AACustodianController repairCustodians:telemetryFlowID:completion:]_block_invoke
+ ___block_descriptor_48_e8_32bs40r_e8_v16?0q8l
+ ___block_descriptor_56_e8_32bs40r48r_e8_v12?0B8l
+ ___block_descriptor_56_e8_32bs40r_e5_v8?0l
+ ___block_descriptor_57_e8_32s40s48s_e5_v8?0l
+ ___getIDSErrorDomainSymbolLoc_block_invoke
+ _getIDSErrorDomain
+ _getIDSErrorDomainSymbolLoc
+ _getIDSErrorDomainSymbolLoc.ptr
+ _kAAAnalyticsEventCustodianHealthCheckOwnerCleanupPhantomCustodian
+ _kAAAnalyticsEventCustodianSetupSuccessFamily
+ _kAAAnalyticsEventCustodianSetupSuccessFamilyUnknown
+ _kAAAnalyticsEventCustodianSetupSuccessNonFamily
+ _kAAAnalyticsEventSetupFailSafePendingFamily
+ _kAAAnalyticsEventSetupFailSafePendingFamilyUnknown
+ _kAAAnalyticsEventSetupFailSafePendingNonFamily
+ _kAAAnalyticsEventSetupFailSafeReadyFamily
+ _kAAAnalyticsEventSetupFailSafeReadyFamilyUnknown
+ _kAAAnalyticsEventSetupFailSafeReadyNonFamily
+ _objc_msgSend$_invokeSendResultHandler:withOutcome:
+ _objc_msgSend$_reportedErrorForIDSSendError:
+ _objc_msgSend$_sendMessage:destinations:sendFromHandleUri:responseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:wantsDeliveryAcknowledgement:sendResultHandler:error:
+ _objc_msgSend$_verifyTermsCFUMessageWithUserInfo:
+ _objc_msgSend$aa_formattedUsername
+ _objc_msgSend$aliasUris:containSenderAliasUri:
+ _objc_msgSend$aliases
+ _objc_msgSend$canSend
+ _objc_msgSend$initWithSuccess:error:
+ _objc_msgSend$registerSendResultHandler:forIdentifier:
+ _objc_msgSend$repairCustodians:telemetryFlowID:completion:
+ _objc_msgSend$requiredIDStatusForDestination:service:listenerID:queue:completionBlock:
+ _objc_msgSend$success
- GCC_except_table102
- GCC_except_table134
- GCC_except_table138
- GCC_except_table51
- GCC_except_table76
- GCC_except_table79
- GCC_except_table95
- ___174-[AAMessagingService sendMessage:destinations:sendFromHandleUri:responseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:wantsDeliveryAcknowledgement:error:]_block_invoke
- ___53-[AACustodianController repairCustodians:completion:]_block_invoke
- ___block_descriptor_56_e8_32bs40r48r_e5_v8?0l
- _objc_msgSend$sendMessage:destinations:sendFromHandleUri:responseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:wantsDeliveryAcknowledgement:error:
CStrings:
+ "AAMessagingService: the custodian delegate declined the IDS ack. The sender gets no delivery acknowledgment."
+ "CKErrorDomain"
+ "FOLLOWUP_VERIFY_TERMS_ACCOUNT_MESSAGE"
+ "IDSErrorDomain"
+ "No messaging destination for the handle. Reporting not registered."
+ "The IDS reachability query did not complete in %.1f seconds. Reporting Unknown."
+ "accountUsername"
+ "com.apple.AAMessaging.sendResult"
+ "com.apple.appleaccount.custodian.healthcheck.owner.cleanupPhantomCustodian"
+ "com.apple.appleaccount.custodian.setup.success.family"
+ "com.apple.appleaccount.custodian.setup.success.familyUnknown"
+ "com.apple.appleaccount.custodian.setup.success.nonFamily"
+ "com.apple.appleaccount.custodian.setupFailSafe.pending.family"
+ "com.apple.appleaccount.custodian.setupFailSafe.pending.familyUnknown"
+ "com.apple.appleaccount.custodian.setupFailSafe.pending.nonFamily"
+ "com.apple.appleaccount.custodian.setupFailSafe.ready.family"
+ "com.apple.appleaccount.custodian.setupFailSafe.ready.familyUnknown"
+ "com.apple.appleaccount.custodian.setupFailSafe.ready.nonFamily"
+ "telemetryFlowID"
+ "typeof (((typeof (IDSErrorDomain) (*)(void))0)()) getIDSErrorDomain(void)"
- "\x92"
```
