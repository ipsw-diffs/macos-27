## AppleAccount

> `/System/Library/PrivateFrameworks/AppleAccount.framework/Versions/A/AppleAccount`

```diff

-1069.125.7.0.0
-  __TEXT.__text: 0x278384
-  __TEXT.__objc_methlist: 0xb304
-  __TEXT.__cstring: 0x105a1
-  __TEXT.__const: 0x484a0
-  __TEXT.__oslogstring: 0x128fd
-  __TEXT.__gcc_except_tab: 0x1aa8
+1069.250.3.0.0
+  __TEXT.__text: 0x279a34
+  __TEXT.__objc_methlist: 0xb3ec
+  __TEXT.__cstring: 0x10771
+  __TEXT.__const: 0x484b0
+  __TEXT.__oslogstring: 0x12c0d
+  __TEXT.__gcc_except_tab: 0x1ad8
   __TEXT.__dlopen_cstrs: 0x2d3
   __TEXT.__swift5_typeref: 0x334a
   __TEXT.__constg_swiftt: 0x26a0

   __TEXT.__swift_as_ret: 0x244
   __TEXT.__swift_as_cont: 0x450
   __TEXT.__swift5_capture: 0x7b8
-  __TEXT.__unwind_info: 0x7b28
+  __TEXT.__unwind_info: 0x7bc0
   __TEXT.__eh_frame: 0x6970
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2690
+  __DATA_CONST.__const: 0x26b0
   __DATA_CONST.__objc_classlist: 0x898
   __DATA_CONST.__objc_catlist: 0xa0
   __DATA_CONST.__objc_protolist: 0x248
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x50d0
+  __DATA_CONST.__objc_selrefs: 0x5170
   __DATA_CONST.__objc_protorefs: 0xe0
   __DATA_CONST.__objc_superrefs: 0x588
   __DATA_CONST.__objc_arraydata: 0xe0
   __DATA_CONST.__got: 0x1030
-  __AUTH_CONST.__const: 0x10a50
-  __AUTH_CONST.__cfstring: 0xcfe0
-  __AUTH_CONST.__objc_const: 0x26320
-  __AUTH_CONST.__objc_intobj: 0x120
+  __AUTH_CONST.__const: 0x10b00
+  __AUTH_CONST.__cfstring: 0xd060
+  __AUTH_CONST.__objc_const: 0x26410
+  __AUTH_CONST.__objc_intobj: 0x138
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x12c0
   __AUTH.__objc_data: 0xa0
-  __DATA.__objc_ivar: 0xbc0
+  __DATA.__objc_ivar: 0xbd4
   __DATA.__data: 0x2858
-  __DATA.__bss: 0x14c80
+  __DATA.__bss: 0x14c90
   __DATA.__common: 0xa48
   __DATA_DIRTY.__objc_data: 0x5ba0
   __DATA_DIRTY.__data: 0x2d30

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 8777
-  Symbols:   11226
-  CStrings:  3529
+  Functions: 8816
+  Symbols:   11290
+  CStrings:  3550
 
Symbols:
+ +[AAFeatureFlags isRemoteUITermsMigrationEnabled]
+ +[AAUrlBagHelper _completeWithRemoteUITermsFeatureFlagFallback:]
+ +[AAUrlBagHelper isRemoteUITermsEnabledWithCompletion:]
+ -[AAMessagingService _attachAckCompletionToCustodianMessage:context:]
+ -[AAMessagingService _beginInFlightMessageWithGUID:]
+ -[AAMessagingService _deliverInheritanceMessage:custodianMessage:]
+ -[AAMessagingService _endInFlightMessageWithGUID:]
+ -[AAMessagingService _faultIfStillPendingAfterDelay:]
+ -[AAMessagingService _optionsDictionaryWithResponseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:sendFromHandleUri:wantsDeliveryAcknowledgement:]
+ -[AAMessagingService _processDeliveredMessageIdentifier:transaction:]
+ -[AAMessagingService _processPendingDeliveredMessageIdentifiers]
+ -[AAMessagingService pendingDeliveredMessageIdentifiers]
+ -[AAMessagingService sendMessage:destinations:sendFromHandleUri:responseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:wantsDeliveryAcknowledgement:error:]
+ -[AAMessagingService service:account:identifier:hasBeenDeliveredWithContext:]
+ -[AAPendingIDSMessage ackCompletion]
+ -[AAPendingIDSMessage setAckCompletion:]
+ -[AAPendingIDSMessage setTransaction:]
+ -[AAPendingIDSMessage transaction]
+ -[AAURLSession _sessionQueue_dequeueTask:withResponse:headerFields:error:]
+ -[NSError(AppleAccount) aa_isAccountsDaemonConnectionError]
+ GCC_except_table72
+ GCC_except_table75
+ _OBJC_IVAR_$_AAMessagingService._inFlightMessageGUIDs
+ _OBJC_IVAR_$_AAMessagingService._pendingDeliveredMessageIdentifiers
+ _OBJC_IVAR_$_AAMessagingService._pendingDeliveredTransaction
+ _OBJC_IVAR_$_AAPendingIDSMessage._ackCompletion
+ _OBJC_IVAR_$_AAPendingIDSMessage._transaction
+ __AAUrlBagRemoteUITermsConfigKey
+ __AAUrlBagRemoteUITermsEnabledKey
+ ___174-[AAMessagingService sendMessage:destinations:sendFromHandleUri:responseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:wantsDeliveryAcknowledgement:error:]_block_invoke
+ ___53-[AAMessagingService _faultIfStillPendingAfterDelay:]_block_invoke
+ ___55+[AAUrlBagHelper isRemoteUITermsEnabledWithCompletion:]_block_invoke
+ ___69-[AAMessagingService _attachAckCompletionToCustodianMessage:context:]_block_invoke
+ ___69-[AAMessagingService _attachAckCompletionToCustodianMessage:context:]_block_invoke_2
+ ___69-[AAMessagingService _processDeliveredMessageIdentifier:transaction:]_block_invoke
+ ___98-[AASignInFlowController _onqueue_validateAndEnrollCDPStateForAccount:withAuthResults:completion:]_block_invoke_2
+ ___98-[AASignInFlowController _onqueue_validateAndEnrollCDPStateForAccount:withAuthResults:completion:]_block_invoke_3
+ ___AARunOnce_block_invoke
+ ___block_descriptor_48_e8_32w40w_e5_v8?0l
+ ___block_descriptor_56_e8_32bs40r48r_e5_v8?0l
+ ___block_descriptor_64_e8_32s40s48s56w_e5_v8?0l
+ ___copy_helper_block_e8_32b40r48r
+ ___copy_helper_block_e8_32s40s48s56w
+ ___copy_helper_block_e8_32w40w
+ ___destroy_helper_block_e8_32w40w
+ ___getIDSSendMessageOptionWantsClientAcknowledgementKeySymbolLoc_block_invoke
+ _getIDSSendMessageOptionWantsClientAcknowledgementKey
+ _getIDSSendMessageOptionWantsClientAcknowledgementKeySymbolLoc
+ _getIDSSendMessageOptionWantsClientAcknowledgementKeySymbolLoc.ptr
+ _kAAAnalyticsEventDeviceListCacheHit
+ _kAAAnalyticsEventDeviceListCacheMiss
+ _kAAAnalyticsEventDeviceListCacheValidation
+ _kAAPreflightSaveDaemonRetryDelay
+ _objc_msgSend$_attachAckCompletionToCustodianMessage:context:
+ _objc_msgSend$_beginInFlightMessageWithGUID:
+ _objc_msgSend$_completeWithRemoteUITermsFeatureFlagFallback:
+ _objc_msgSend$_deliverInheritanceMessage:custodianMessage:
+ _objc_msgSend$_endInFlightMessageWithGUID:
+ _objc_msgSend$_faultIfStillPendingAfterDelay:
+ _objc_msgSend$_optionsDictionaryWithResponseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:sendFromHandleUri:wantsDeliveryAcknowledgement:
+ _objc_msgSend$_processDeliveredMessageIdentifier:transaction:
+ _objc_msgSend$_processPendingDeliveredMessageIdentifiers
+ _objc_msgSend$_sessionQueue_dequeueTask:withResponse:headerFields:error:
+ _objc_msgSend$aa_isAccountsDaemonConnectionError
+ _objc_msgSend$ackCompletion
+ _objc_msgSend$initWithService:manuallyAckMessages:
+ _objc_msgSend$isRemoteUITermsMigrationEnabled
+ _objc_msgSend$isSyncAction
+ _objc_msgSend$messageService:didDeliverMessageWithIdentifier:
+ _objc_msgSend$messageService:didReceiveMessage:fromID:sentToHandleUri:completion:
+ _objc_msgSend$originalGUID
+ _objc_msgSend$sendAckForMessageWithContext:
+ _objc_msgSend$sendMessage:destinations:sendFromHandleUri:responseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:wantsDeliveryAcknowledgement:error:
+ _objc_msgSend$setAckCompletion:
+ _objc_msgSend$setTransaction:
- +[AAUrlBagHelper canRepairCustodian]
- -[AAMessagingService _optionsDictionaryWithResponseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:sendFromHandleUri:]
- -[AAURLSession _sessionQueue_dequeueTask:withResponse:error:]
- GCC_except_table71
- GCC_except_table74
- GCC_except_table77
- __AAUrlBagCanRepairCustodianKey
- ___145-[AAMessagingService sendMessage:destinations:sendFromHandleUri:responseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:error:]_block_invoke
- _objc_msgSend$_optionsDictionaryWithResponseIdentifier:fireAndForget:requiredCapabilities:lackingCapabilities:sendFromHandleUri:
- _objc_msgSend$_sessionQueue_dequeueTask:withResponse:error:
- _objc_msgSend$initWithService:
CStrings:
+ "AAMessagingService: message %@ is already in flight. Ignoring the duplicate."
+ "AAMessagingService: message of type %ld still waits for its delegate after %lld s"
+ "Custodian delegate %@ does not handle delivery acknowledgements, dropping %@"
+ "Delivered message has an identifier that is not a UUID: %@"
+ "IDSSendMessageOptionWantsClientAcknowledgementKey"
+ "Message %@ has been delivered"
+ "MessagingService lost strong ref processing delivery acknowledgement"
+ "PreflightSave failed because accountsd went away, retrying once after a short delay..."
+ "RUI Terms: Failed to fetch RUI terms config from URL bag: %@"
+ "RUI Terms: Falling back to OS FeatureFlag: %d"
+ "RUI Terms: Returning remoteUITermsEnabled from urlbag: %@"
+ "RUI Terms: Unexpected config value type: %@"
+ "RUI Terms: remoteUITermsMigrationCfgs from urlbag: %@"
+ "RemoteUITermsMigration"
+ "Sending %@: %@ in response to %@, wants delivery acknowledgement: %@"
+ "Sending %@: %@, wants delivery acknowledgement: %@"
+ "Sending to %@"
+ "com.apple.aa.messaging.ack"
+ "com.apple.aa.messaging.delivered"
+ "com.apple.aa.messaging.incomingData"
+ "com.apple.appleaccount.deviceListCache.hit"
+ "com.apple.appleaccount.deviceListCache.miss"
+ "com.apple.appleaccount.deviceListCache.validation"
+ "remoteUITermsEnabled"
+ "remoteUITermsMigrationCfgs"
+ "typeof (((typeof (IDSSendMessageOptionWantsClientAcknowledgementKey) (*)(void))0)()) getIDSSendMessageOptionWantsClientAcknowledgementKey(void)"
+ "\x92"
- "DecoupleOTPeerID"
- "Returning canRepairCustodianV2 from urlbag: %@"
- "Sending %@: %@ to %@"
- "Sending %@: %@ to %@ in response to %@"
- "b"
- "canRepairCustodianV2"
```
