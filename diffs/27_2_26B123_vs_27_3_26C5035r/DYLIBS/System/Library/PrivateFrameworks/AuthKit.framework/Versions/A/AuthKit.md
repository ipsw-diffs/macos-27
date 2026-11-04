## AuthKit

> `/System/Library/PrivateFrameworks/AuthKit.framework/Versions/A/AuthKit`

### Sections with Same Size but Changed Content

- `__TEXT.__ustring`

```diff

-560.125.6.0.0
-  __TEXT.__text: 0x2c5b70
-  __TEXT.__objc_methlist: 0x106c4
+560.250.3.0.0
+  __TEXT.__text: 0x2cb5d8
+  __TEXT.__objc_methlist: 0x10a54
   __TEXT.__const: 0x3ac40
-  __TEXT.__cstring: 0x12cb4
-  __TEXT.__oslogstring: 0x15c1a
-  __TEXT.__gcc_except_tab: 0x6698
+  __TEXT.__cstring: 0x131b7
+  __TEXT.__oslogstring: 0x16215
+  __TEXT.__gcc_except_tab: 0x6760
   __TEXT.__dlopen_cstrs: 0x250
   __TEXT.__ustring: 0x3be
-  __TEXT.__unwind_info: 0x71a8
+  __TEXT.__unwind_info: 0x72e8
   __TEXT.__eh_frame: 0xc0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x5df0
-  __DATA_CONST.__objc_classlist: 0x7d8
+  __DATA_CONST.__const: 0x5f60
+  __DATA_CONST.__objc_classlist: 0x7f0
   __DATA_CONST.__objc_catlist: 0x88
-  __DATA_CONST.__objc_protolist: 0x248
+  __DATA_CONST.__objc_protolist: 0x268
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8090
-  __DATA_CONST.__objc_protorefs: 0xf0
-  __DATA_CONST.__objc_superrefs: 0x4f0
+  __DATA_CONST.__objc_selrefs: 0x81f0
+  __DATA_CONST.__objc_protorefs: 0xf8
+  __DATA_CONST.__objc_superrefs: 0x508
   __DATA_CONST.__objc_arraydata: 0x368
-  __DATA_CONST.__got: 0xa70
-  __AUTH_CONST.__const: 0xb720
-  __AUTH_CONST.__cfstring: 0x13f40
-  __AUTH_CONST.__objc_const: 0x2ed40
+  __DATA_CONST.__got: 0xa78
+  __AUTH_CONST.__const: 0xb740
+  __AUTH_CONST.__cfstring: 0x14580
+  __AUTH_CONST.__objc_const: 0x2faa8
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_dictobj: 0x438
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__auth_got: 0x568
-  __AUTH.__objc_data: 0x34d0
-  __DATA.__objc_ivar: 0x1264
-  __DATA.__data: 0x20f8
-  __DATA.__bss: 0x658
+  __AUTH.__objc_data: 0x35c0
+  __DATA.__objc_ivar: 0x12a4
+  __DATA.__data: 0x2278
+  __DATA.__bss: 0x668
   __DATA.__common: 0xa20
   __DATA_DIRTY.__objc_data: 0x19a0
-  __DATA_DIRTY.__bss: 0x320
+  __DATA_DIRTY.__bss: 0x330
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 6277
-  Symbols:   14569
-  CStrings:  4610
+  Functions: 6343
+  Symbols:   14764
+  CStrings:  4690
 
Symbols:
+ +[AKApprovalFlowIdentifiers supportsSecureCoding]
+ +[AKApprovalFlowViewServiceInterface XPCInterface]
+ -[AKAccountManager setStringArray:forAccount:withKey:]
+ -[AKAccountManager stringArrayFromAccount:withKey:]
+ -[AKAnalyticsSender .cxx_destruct]
+ -[AKAnalyticsSender initWithAnalyticsReporter:]
+ -[AKAnalyticsSender init]
+ -[AKAnalyticsSender sendAnalyticsEventNamed:context:account:error:]
+ -[AKAppleIDPasskeyCredential prfOutput]
+ -[AKAppleIDPasskeyCredential setPrfOutput:]
+ -[AKAppleIDPasskeyCredentialRequestContext prfSeed]
+ -[AKAppleIDPasskeyCredentialRequestContext setPrfSeed:]
+ -[AKAppleIDServerResourceLoadDelegate gsTokenIdentifier]
+ -[AKAppleIDServerResourceLoadDelegate pushTransactionID]
+ -[AKAppleIDServerResourceLoadDelegate setGsTokenIdentifier:]
+ -[AKAppleIDServerResourceLoadDelegate setPushTransactionID:]
+ -[AKAppleIDServerResourceLoadDelegate setSkipProcessBAAExclusionCheck:]
+ -[AKAppleIDServerResourceLoadDelegate skipProcessBAAExclusionCheck]
+ -[AKAppleIDSession setSkipProcessBAAExclusionCheck:]
+ -[AKAppleIDSession skipProcessBAAExclusionCheck]
+ -[AKAppleIDSessionContext setSkipProcessExclusionCheck:]
+ -[AKAppleIDSessionContext skipProcessExclusionCheck]
+ -[AKApprovalFlowContext approvalCode]
+ -[AKApprovalFlowContext flowIdentifiers]
+ -[AKApprovalFlowContext initWithCodeType:flowIdentifiers:ruiURLString:pushInfo:approvalCode:cardCopy:serverRequestConfiguration:]
+ -[AKApprovalFlowIdentifiers .cxx_destruct]
+ -[AKApprovalFlowIdentifiers copyWithZone:]
+ -[AKApprovalFlowIdentifiers description]
+ -[AKApprovalFlowIdentifiers encodeWithCoder:]
+ -[AKApprovalFlowIdentifiers flowKey]
+ -[AKApprovalFlowIdentifiers initWithCoder:]
+ -[AKApprovalFlowIdentifiers initWithFlowKey:telemetryFlowID:]
+ -[AKApprovalFlowIdentifiers telemetryFlowID]
+ -[AKAttestationRequestData setSkipProcessExclusionCheck:]
+ -[AKAttestationRequestData skipProcessExclusionCheck]
+ -[AKAuthorizationContext setTelemetryFlowID:]
+ -[AKAuthorizationContext telemetryFlowID]
+ -[AKBasicServerRequest gsTokenID]
+ -[AKBasicServerRequest setGsTokenID:]
+ -[AKCDPFactory beginCreateDBRRecordForPasskeyWithAltDSID:credentialID:prfOutput:force:completion:]
+ -[AKConfiguration approvalFlowTimeoutSecondsOverride]
+ -[AKOSEligibilityManager regulatoryCountryRegionsForDomain:]
+ -[AKSMSCodeApprovalController init]
+ -[AKSMSCodeApprovalController presentSMSApprovalForCode:completion:]
+ -[AKSMSCodeApprovalController validatePrimaryUserIsExpectingSMSCode:completion:]
+ -[AKSMSCodeApprovalController validateSMSSender:completion:]
+ -[AKUserInformation _parsePasskeyDBRInfo:]
+ -[AKUserInformation passkeyDBRCredentialIDsNeedingRecord]
+ -[AKUserInformation passkeyPRFSeed]
+ -[AKUserInformation setPasskeyDBRCredentialIDsNeedingRecord:]
+ -[AKUserInformation setPasskeyPRFSeed:]
+ -[NSData(AuthKit) ak_base64UrlEncodedString]
+ -[NSMutableURLRequest(AuthKit) ak_addAttestationDataHeadersSkippingProcessExclusionCheck:]
+ -[NSMutableURLRequest(AuthKit) ak_addPushTransactionIdHeader:]
+ GCC_except_table111
+ GCC_except_table114
+ GCC_except_table125
+ GCC_except_table128
+ GCC_except_table153
+ GCC_except_table160
+ GCC_except_table161
+ GCC_except_table175
+ GCC_except_table176
+ GCC_except_table201
+ GCC_except_table209
+ GCC_except_table217
+ GCC_except_table226
+ GCC_except_table230
+ GCC_except_table238
+ GCC_except_table24
+ GCC_except_table249
+ GCC_except_table250
+ GCC_except_table255
+ GCC_except_table282
+ GCC_except_table304
+ GCC_except_table305
+ GCC_except_table323
+ GCC_except_table326
+ GCC_except_table329
+ GCC_except_table337
+ GCC_except_table338
+ GCC_except_table378
+ GCC_except_table387
+ GCC_except_table388
+ GCC_except_table399
+ GCC_except_table400
+ GCC_except_table42
+ GCC_except_table61
+ GCC_except_table78
+ _AKAppleIDAuthenticationAppProvidedContextApproval
+ _AKAppleSMSSenderListKey
+ _AKAuthenticationSMSCodeHeaderField
+ _AKOSEDomainTeenAttachedToFamilyOfferToJoin
+ _AKPasskeyDBRCredentialIDResponseKey
+ _AKPasskeyDBRInfoResponseKey
+ _AKPasskeyDBRNeedsRecordResponseKey
+ _AKPasskeyDBRPRFSeedResponseKey
+ _AKPasskeyDBRPasskeysResponseKey
+ _AKSecrecyFeatureServerDrivenApprovalFlowSMS
+ _AKTTRComponentID
+ _AKTTRComponentName
+ _AKTTRComponentVersion
+ _AKTemporaryCollectRiskingSignalsHeaderKey
+ _AKTemporaryRiskingSignalsHeaderKey
+ _AKURLBagKeyFetchPasskeyPrfSalt
+ _AKURLBagKeyHasActiveSMSCode
+ _AKURLBagKeyPDPRecreateWithFallback
+ _AKURLBagKeyPresentSMSProtectionFlow
+ _AKURLBagKeySMSApprovalFlowEnabled
+ _AKURLBagKeySavePasskeyPrfSalt
+ _OBJC_CLASS_$_AKApprovalFlowIdentifiers
+ _OBJC_CLASS_$_AKApprovalFlowViewServiceInterface
+ _OBJC_CLASS_$_AKSMSCodeApprovalController
+ _OBJC_IVAR_$_AKAnalyticsSender._analyticsReporter
+ _OBJC_IVAR_$_AKAppleIDPasskeyCredential._prfOutput
+ _OBJC_IVAR_$_AKAppleIDPasskeyCredentialRequestContext._prfSeed
+ _OBJC_IVAR_$_AKAppleIDServerResourceLoadDelegate._gsTokenIdentifier
+ _OBJC_IVAR_$_AKAppleIDServerResourceLoadDelegate._pushTransactionID
+ _OBJC_IVAR_$_AKAppleIDServerResourceLoadDelegate._skipProcessBAAExclusionCheck
+ _OBJC_IVAR_$_AKAppleIDSession._skipProcessBAAExclusionCheck
+ _OBJC_IVAR_$_AKAppleIDSessionContext._skipProcessExclusionCheck
+ _OBJC_IVAR_$_AKApprovalFlowContext._approvalCode
+ _OBJC_IVAR_$_AKApprovalFlowContext._flowIdentifiers
+ _OBJC_IVAR_$_AKApprovalFlowIdentifiers._flowKey
+ _OBJC_IVAR_$_AKApprovalFlowIdentifiers._telemetryFlowID
+ _OBJC_IVAR_$_AKAttestationRequestData._skipProcessExclusionCheck
+ _OBJC_IVAR_$_AKAuthorizationContext._telemetryFlowID
+ _OBJC_IVAR_$_AKBasicServerRequest._gsTokenID
+ _OBJC_IVAR_$_AKUserInformation._passkeyDBRCredentialIDsNeedingRecord
+ _OBJC_IVAR_$_AKUserInformation._passkeyPRFSeed
+ _OBJC_METACLASS_$_AKApprovalFlowIdentifiers
+ _OBJC_METACLASS_$_AKApprovalFlowViewServiceInterface
+ _OBJC_METACLASS_$_AKSMSCodeApprovalController
+ __AKAppleIDSessionContextSkipProcessExclusionCheckKey
+ __AKApprovalFlowTimeoutSecondsOverrideKey
+ __AKPushTransactionID
+ __OBJC_$_CLASS_METHODS_AKApprovalFlowIdentifiers
+ __OBJC_$_CLASS_METHODS_AKApprovalFlowViewServiceInterface
+ __OBJC_$_CLASS_PROP_LIST_AKApprovalFlowIdentifiers
+ __OBJC_$_INSTANCE_METHODS_AKAnalyticsSender
+ __OBJC_$_INSTANCE_METHODS_AKApprovalFlowIdentifiers
+ __OBJC_$_INSTANCE_METHODS_AKSMSCodeApprovalController
+ __OBJC_$_INSTANCE_VARIABLES_AKAnalyticsSender
+ __OBJC_$_INSTANCE_VARIABLES_AKApprovalFlowIdentifiers
+ __OBJC_$_PROP_LIST_AKApprovalFlowIdentifiers
+ __OBJC_$_PROP_LIST_AKCDPFactory
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AKAnisetteDataProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AKApprovalFlowViewServiceProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AKCDPFactoryProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AKODIAssessmentSending
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AKAnisetteDataProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AKApprovalFlowViewServiceProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AKCDPFactoryProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AKODIAssessmentSending
+ __OBJC_$_PROTOCOL_REFS_AKAnisetteDataProviding
+ __OBJC_$_PROTOCOL_REFS_AKApprovalFlowViewServiceProtocol
+ __OBJC_$_PROTOCOL_REFS_AKCDPFactoryProtocol
+ __OBJC_$_PROTOCOL_REFS_AKODIAssessmentSending
+ __OBJC_CLASS_PROTOCOLS_$_AKAnisetteProvisioningController
+ __OBJC_CLASS_PROTOCOLS_$_AKApprovalFlowIdentifiers
+ __OBJC_CLASS_PROTOCOLS_$_AKCDPFactory
+ __OBJC_CLASS_RO_$_AKApprovalFlowIdentifiers
+ __OBJC_CLASS_RO_$_AKApprovalFlowViewServiceInterface
+ __OBJC_CLASS_RO_$_AKSMSCodeApprovalController
+ __OBJC_LABEL_PROTOCOL_$_AKAnisetteDataProviding
+ __OBJC_LABEL_PROTOCOL_$_AKApprovalFlowViewServiceProtocol
+ __OBJC_LABEL_PROTOCOL_$_AKCDPFactoryProtocol
+ __OBJC_LABEL_PROTOCOL_$_AKODIAssessmentSending
+ __OBJC_METACLASS_RO_$_AKApprovalFlowIdentifiers
+ __OBJC_METACLASS_RO_$_AKApprovalFlowViewServiceInterface
+ __OBJC_METACLASS_RO_$_AKSMSCodeApprovalController
+ __OBJC_PROTOCOL_$_AKAnisetteDataProviding
+ __OBJC_PROTOCOL_$_AKApprovalFlowViewServiceProtocol
+ __OBJC_PROTOCOL_$_AKCDPFactoryProtocol
+ __OBJC_PROTOCOL_$_AKODIAssessmentSending
+ __OBJC_PROTOCOL_REFERENCE_$_AKApprovalFlowViewServiceProtocol
+ ___50+[AKApprovalFlowViewServiceInterface XPCInterface]_block_invoke
+ ___60-[AKSMSCodeApprovalController validateSMSSender:completion:]_block_invoke
+ ___68-[AKSMSCodeApprovalController presentSMSApprovalForCode:completion:]_block_invoke
+ ___80-[AKSMSCodeApprovalController validatePrimaryUserIsExpectingSMSCode:completion:]_block_invoke
+ ___98-[AKCDPFactory beginCreateDBRRecordForPasskeyWithAltDSID:credentialID:prfOutput:force:completion:]_block_invoke
+ ___getASAuthorizationPublicKeyCredentialPRFAssertionInputValuesClass_block_invoke
+ ___getASAuthorizationPublicKeyCredentialPRFRegistrationInputClass_block_invoke
+ _getASAuthorizationPublicKeyCredentialPRFAssertionInputValuesClass
+ _getASAuthorizationPublicKeyCredentialPRFAssertionInputValuesClass.softClass
+ _getASAuthorizationPublicKeyCredentialPRFRegistrationInputClass
+ _getASAuthorizationPublicKeyCredentialPRFRegistrationInputClass.softClass
+ _kAKAnalyticsApprovalCodeType
+ _kAKAnalyticsEvent2FAApprovalFlowEnd
+ _kAKAnalyticsEvent2FAApprovalFlowStart
+ _kAKAnalyticsEventAppleSMSSenderDetected
+ _kAKAnalyticsEventCallSignalsRequested
+ _kAKAnalyticsEventCheck2FACodeLegitimacy
+ _kAKAnalyticsEventCodeDisplayedWithInvisibleInk
+ _kAKAnalyticsEventInvisibleInkRemovedFromCode
+ _kAKAnalyticsEventLocalAuthentication
+ _kAKAnalyticsEventPushReceived
+ _kAKAnalyticsEventSignInDisclosure
+ _kAKApprovalFlowApprovalCodeKey
+ _kAKApprovalFlowFlowIdentifiersKey
+ _kAKApprovalFlowIdentifiersFlowKeyKey
+ _kAKApprovalFlowIdentifiersTelemetryFlowIDKey
+ _kAKBasicServerRequestGSTokenID
+ _kAKTeenAttachedToFamilyOfferToJoinDomain
+ _kApprovalFlowSMSRemoteUITag
+ _kApprovalFlowSignInDisclosureViewRemoteUITag
+ _objc_msgSend$_parsePasskeyDBRInfo:
+ _objc_msgSend$ak_addAttestationDataHeadersSkippingProcessExclusionCheck:
+ _objc_msgSend$ak_addPushTransactionIdHeader:
+ _objc_msgSend$approvalCode
+ _objc_msgSend$authenticationMode
+ _objc_msgSend$beginCreateDBRRecordForPasskeyWithCredentialID:prfOutput:force:completion:
+ _objc_msgSend$first
+ _objc_msgSend$flowIdentifiers
+ _objc_msgSend$flowKey
+ _objc_msgSend$initWithAnalyticsReporter:
+ _objc_msgSend$initWithCodeType:flowIdentifiers:ruiURLString:pushInfo:approvalCode:cardCopy:serverRequestConfiguration:
+ _objc_msgSend$initWithFlowKey:telemetryFlowID:
+ _objc_msgSend$initWithInputValues:
+ _objc_msgSend$initWithSaltInput1:saltInput2:
+ _objc_msgSend$isMDMInformationRequired
+ _objc_msgSend$presentSMSApprovalForCode:completion:
+ _objc_msgSend$prf
+ _objc_msgSend$prfSeed
+ _objc_msgSend$setPasskeyDBRCredentialIDsNeedingRecord:
+ _objc_msgSend$setPasskeyPRFSeed:
+ _objc_msgSend$setPrf:
+ _objc_msgSend$setPrfOutput:
+ _objc_msgSend$setPrfSeed:
+ _objc_msgSend$setSkipProcessBAAExclusionCheck:
+ _objc_msgSend$setSkipProcessExclusionCheck:
+ _objc_msgSend$skipProcessBAAExclusionCheck
+ _objc_msgSend$validatePrimaryUserIsExpectingSMSCode:completion:
+ _objc_msgSend$validateSMSSender:completion:
- -[AKApprovalFlowContext initWithCodeType:messageId:ruiURLString:pushInfo:cardCopy:serverRequestConfiguration:]
- -[AKApprovalFlowContext messageId]
- GCC_except_table118
- GCC_except_table119
- GCC_except_table126
- GCC_except_table127
- GCC_except_table130
- GCC_except_table158
- GCC_except_table168
- GCC_except_table173
- GCC_except_table181
- GCC_except_table199
- GCC_except_table204
- GCC_except_table207
- GCC_except_table213
- GCC_except_table224
- GCC_except_table225
- GCC_except_table228
- GCC_except_table231
- GCC_except_table239
- GCC_except_table251
- GCC_except_table279
- GCC_except_table280
- GCC_except_table306
- GCC_except_table325
- GCC_except_table328
- GCC_except_table331
- GCC_except_table349
- GCC_except_table350
- GCC_except_table380
- GCC_except_table389
- GCC_except_table390
- GCC_except_table59
- GCC_except_table65
- GCC_except_table80
- _OBJC_IVAR_$_AKApprovalFlowContext._messageId
- _kAKApprovalFlowMessageIdKey
- _objc_msgSend$initWithCodeType:messageId:ruiURLString:pushInfo:cardCopy:serverRequestConfiguration:
- _objc_msgSend$messageId
CStrings:
+ "621449"
+ "<%@: %p codeType=%@ flowIdentifiers=%@ ruiURLString=%@ hasPushInfo=%@ cardCopy=%@>"
+ "<%@: %p flowKey=%@ telemetryFlowID=%@>"
+ "<%@: %p; altDSID=%@, urlBagKey=%@, requestBody=%@, additionalHeaders=%@, expectedResponseFormat=%lu, requestBodyFormat=%lu, telemetryFlowID=%@, gsTokenID=%@>"
+ "A sender number was not provided."
+ "AKApprovalFlowContext initialization failed, nil flowIdentifiers"
+ "AKApprovalFlowIdentifiers initialization failed, nil flowKey"
+ "ASAuthorizationPublicKeyCredentialPRFAssertionInputValues"
+ "ASAuthorizationPublicKeyCredentialPRFRegistrationInput"
+ "All"
+ "An SMS code was not provided."
+ "Authentication service returned an XPC error presenting SMS approval: %@"
+ "Authentication service returned an XPC error validating SMS sender: %@"
+ "Authentication service returned an XPC error validating expected SMS code: %@"
+ "BEGIN [%lld]: PresentSMSApproval  enableTelemetry=YES "
+ "BEGIN [%lld]: ValidatePrimaryUserIsExpectingCode  enableTelemetry=YES "
+ "BEGIN [%lld]: ValidateSMSSender  enableTelemetry=YES "
+ "CoreCDP stateController does not support beginCreateDBRRecordForPasskeyWithCredentialID:prfOutput:force:completion:"
+ "Creating passkey recovery record, force=%d"
+ "Dispatching SMS approval presentation to daemon"
+ "Dispatching SMS code validation to daemon"
+ "Dispatching SMS sender validation to daemon"
+ "END [%lld] %fs:PresentSMSApproval "
+ "END [%lld] %fs:ValidatePrimaryUserIsExpectingCode "
+ "END [%lld] %fs:ValidateSMSSender "
+ "Invalid domain string for regulatory regions: %@"
+ "No CDP context for the requested altDSID - refusing to create a passkey recovery record"
+ "No stored GS token for identifier %@"
+ "Passkey recovery record created."
+ "Passkey recovery record creation failed with error %{private}@"
+ "PasskeyDBR"
+ "PresentSMSApproval"
+ "Received server time [%@], from - %@"
+ "SMS"
+ "SMSCode"
+ "ServerDrivenApprovalFlowSMS"
+ "SignInDisclosureView"
+ "Signing request with GS token for identifier %@"
+ "Successfully obtained passkey credential."
+ "TEEN_ATTACHED_TO_FAMILY_OFFER_TO_JOIN"
+ "Teen attached to family offer to join - setting AKOSEOptionTeenAttachedToFamilyOfferToJoin flag"
+ "User is teen, using teen attached to family offer to join domain"
+ "ValidatePrimaryUserIsExpectingCode"
+ "ValidateSMSSender"
+ "X-Apple-Collect-Risking-Signals"
+ "X-Apple-I-Push-Txn-Id"
+ "X-Apple-I-SMS-Code"
+ "X-Apple-Risking-Signals"
+ "_AKApprovalFlowTimeoutSecondsOverride"
+ "_approvalCode"
+ "_flowIdentifiers"
+ "_flowKey"
+ "_gsTokenIdentifier"
+ "_passkeyDBRCredentialIDsNeedingRecord"
+ "_passkeyPRFSeed"
+ "_prfOutput"
+ "_prfSeed"
+ "_pushTransactionID"
+ "_skipProcessBAAExclusionCheck"
+ "_skipProcessExclusionCheck"
+ "abpSmsEnabled"
+ "appleSmsSenderList"
+ "approval"
+ "approvalCodeType"
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
+ "credentialId"
+ "fetchPrfSalt"
+ "gsTokenID"
+ "hsa2SmsAuthApprovalFlowUrl"
+ "needsDBRRecord"
+ "passkeyDBRInfo"
+ "passkeys"
+ "pdpRecreateWithFallback"
+ "prfSeed"
+ "savePrfSalt"
+ "validActiveSmsCodeUrl"
- "<%@: %p codeType=%@ messageId=%@ ruiURLString=%@ hasPushInfo=%@ cardCopy=%@>"
- "<%@: %p; altDSID=%@, urlBagKey=%@, requestBody=%@, additionalHeaders=%@, expectedResponseFormat=%lu, requestBodyFormat=%lu, telemetryFlowID=%@>"
- "AKApprovalFlowContext initialization failed, nil messageId"
- "Successfully obtained passkey credential: %@"
- "_messageId"
```
