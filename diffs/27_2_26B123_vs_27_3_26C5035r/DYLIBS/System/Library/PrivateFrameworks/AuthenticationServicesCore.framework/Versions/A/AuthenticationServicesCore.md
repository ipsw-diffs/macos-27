## AuthenticationServicesCore

> `/System/Library/PrivateFrameworks/AuthenticationServicesCore.framework/Versions/A/AuthenticationServicesCore`

```diff

-625.2.8.11.9
-  __TEXT.__text: 0xb2854
-  __TEXT.__objc_methlist: 0x3a80
-  __TEXT.__const: 0xbdd8
-  __TEXT.__cstring: 0x3be1
-  __TEXT.__oslogstring: 0x32dd
-  __TEXT.__gcc_except_tab: 0x2b0
+626.1.12.11.4
+  __TEXT.__text: 0xca804
+  __TEXT.__objc_methlist: 0x3de8
+  __TEXT.__const: 0xc9a8
+  __TEXT.__cstring: 0x3f11
+  __TEXT.__oslogstring: 0x38a0
+  __TEXT.__gcc_except_tab: 0x2d8
   __TEXT.__ustring: 0x48e
   __TEXT.__dlopen_cstrs: 0x5a
-  __TEXT.__swift5_typeref: 0x2283
-  __TEXT.__constg_swiftt: 0x22d8
-  __TEXT.__swift5_reflstr: 0x1501
-  __TEXT.__swift5_fieldmd: 0x20d0
-  __TEXT.__swift5_builtin: 0xa0
-  __TEXT.__swift5_assocty: 0x3f0
-  __TEXT.__swift5_proto: 0x8f8
-  __TEXT.__swift5_types: 0x280
-  __TEXT.__swift5_capture: 0x570
-  __TEXT.__swift_as_entry: 0xbc
-  __TEXT.__swift_as_ret: 0xa0
-  __TEXT.__swift_as_cont: 0xd0
-  __TEXT.__swift5_protos: 0x28
+  __TEXT.__constg_swiftt: 0x2644
+  __TEXT.__swift5_typeref: 0x283d
+  __TEXT.__swift5_builtin: 0xb4
+  __TEXT.__swift5_reflstr: 0x17c1
+  __TEXT.__swift5_assocty: 0x438
+  __TEXT.__swift5_fieldmd: 0x22b0
+  __TEXT.__swift5_proto: 0x964
+  __TEXT.__swift5_types: 0x298
+  __TEXT.__swift5_capture: 0x93c
+  __TEXT.__swift_as_entry: 0x160
+  __TEXT.__swift_as_ret: 0x16c
+  __TEXT.__swift_as_cont: 0x1fc
+  __TEXT.__swift5_protos: 0x38
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x4058
-  __TEXT.__eh_frame: 0x4130
+  __TEXT.__unwind_info: 0x4940
+  __TEXT.__eh_frame: 0x57f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4f0
-  __DATA_CONST.__objc_classlist: 0x200
-  __DATA_CONST.__objc_catlist: 0x20
-  __DATA_CONST.__objc_protolist: 0x170
+  __DATA_CONST.__const: 0x510
+  __DATA_CONST.__objc_classlist: 0x218
+  __DATA_CONST.__objc_catlist: 0x28
+  __DATA_CONST.__objc_protolist: 0x190
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1de0
-  __DATA_CONST.__objc_protorefs: 0xb8
-  __DATA_CONST.__objc_superrefs: 0xf8
-  __DATA_CONST.__got: 0x840
-  __AUTH_CONST.__const: 0x6728
-  __AUTH_CONST.__cfstring: 0x1ec0
-  __AUTH_CONST.__objc_const: 0x7a08
+  __DATA_CONST.__objc_selrefs: 0x2048
+  __DATA_CONST.__objc_protorefs: 0xc8
+  __DATA_CONST.__objc_superrefs: 0x100
+  __DATA_CONST.__got: 0x8e8
+  __AUTH_CONST.__const: 0x73b8
+  __AUTH_CONST.__cfstring: 0x2020
+  __AUTH_CONST.__objc_const: 0x8190
   __AUTH_CONST.__objc_intobj: 0x30
-  __AUTH_CONST.__auth_got: 0x1110
-  __AUTH.__objc_data: 0x490
-  __AUTH.__data: 0x790
-  __DATA.__objc_ivar: 0x3fc
-  __DATA.__data: 0x22e0
-  __DATA.__bss: 0xf930
-  __DATA.__common: 0x148
-  __DATA_DIRTY.__objc_data: 0x2210
-  __DATA_DIRTY.__data: 0x11f0
-  __DATA_DIRTY.__bss: 0x2180
+  __AUTH_CONST.__auth_got: 0x1260
+  __AUTH.__objc_data: 0x610
+  __AUTH.__data: 0xa20
+  __DATA.__objc_ivar: 0x424
+  __DATA.__data: 0x25c0
+  __DATA.__bss: 0x104c0
+  __DATA.__common: 0x158
+  __DATA_DIRTY.__objc_data: 0x21d0
+  __DATA_DIRTY.__data: 0x11a0
+  __DATA_DIRTY.__bss: 0x2170
   __DATA_DIRTY.__common: 0xb0
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4790
-  Symbols:   3975
-  CStrings:  696
+  Functions: 5312
+  Symbols:   4212
+  CStrings:  742
 
Symbols:
+ +[ASCCredentialServiceIdentifier supportsSecureCoding]
+ +[ASCWebKitSPISupport getCanRelyingPartyPerformPasskeyRequestsDuringHeadlessBrowsing:context:completionHandler:]
+ -[ASAgentAutoFillListener didGenerateStrongPasswordWithProperties:]
+ -[ASAgentAutoFillListener generationEventForAnyRecentGenerationForServiceIdentifierType:serviceIdentifier:hostApplicationBundleIdentifier:completionHandler:]
+ -[ASAgentAutoFillListener generationEventForStrongPassword:serviceIdentifierType:serviceIdentifier:hostApplicationBundleIdentifier:completionHandler:]
+ -[ASAgentAutoFillListener initWithPublicKeyCredentialManager:signInEventCollector:webAuthenticationManager:testWebAuthenticationManager:]
+ -[ASAgentAutoFillListener signInEventForAnyRecentAutoFillOfUsername:password:hostApplicationBundleIdentifier:completionHandler:]
+ -[ASAgentAutoFillListener signInEventForAutoFillOfUsername:password:serviceIdentifierType:serviceIdentifier:hostApplicationBundleIdentifier:completionHandler:]
+ -[ASAgentAutoFillListener testWebAuthenticationManager]
+ -[ASAgentAutoFillListener webAuthenticationManager]
+ -[ASAuthorizationRemoteViewController beginVerificationCodesDeliverySetupOnEndpoint:withCompletionHandler:]
+ -[ASCAgent _beginAuthorizationForApplicationIdentifier:withPresenter:]
+ -[ASCAgent _beginAuthorizationRequestsForContext:completionHandler:]
+ -[ASCAgent _cancelSecurityKeyOperationIfNecessary]
+ -[ASCAgent getCanRelyingPartyPerformPasskeyRequestsDuringHeadlessBrowsing:context:completionHandler:]
+ -[ASCAgent initWithTrafficController:connection:publicKeyCredentialManager:signInEventCollector:webAuthenticationManager:testWebAuthenticationManager:]
+ -[ASCAgent isClientEntitledWebBrowser]
+ -[ASCAgent publicKeyCredentialManager]
+ -[ASCAgent securityKeyPublicKeyCredentialOperationUUID]
+ -[ASCAgent setSecurityKeyPublicKeyCredentialOperationUUID:]
+ -[ASCAgent testWebAuthenticationManager]
+ -[ASCAgent test_setPlatformLoginChoices:]
+ -[ASCAgent webAuthenticationManager]
+ -[ASCAgentListener initWithPublicKeyCredentialManager:webAuthenticationManager:testWebAuthenticationManager:]
+ -[ASCAgentProxy getCanRelyingPartyPerformPasskeyRequestsDuringHeadlessBrowsing:context:completionHandler:]
+ -[ASCAuthorizationRemotePresenter presentVerificationCodesDeliverySetupWithUIWindow:daemonEndpoint:completionHandler:]
+ -[ASCAuthorizationRemotePresenter presentVerificationCodesDeliverySetupWithWindow:daemonEndpoint:completionHandler:]
+ -[ASCCredentialServiceIdentifier .cxx_destruct]
+ -[ASCCredentialServiceIdentifier copyWithZone:]
+ -[ASCCredentialServiceIdentifier description]
+ -[ASCCredentialServiceIdentifier displayName]
+ -[ASCCredentialServiceIdentifier encodeWithCoder:]
+ -[ASCCredentialServiceIdentifier hash]
+ -[ASCCredentialServiceIdentifier identifier]
+ -[ASCCredentialServiceIdentifier initWithCoder:]
+ -[ASCCredentialServiceIdentifier initWithIdentifier:type:]
+ -[ASCCredentialServiceIdentifier initWithIdentifier:type:displayName:]
+ -[ASCCredentialServiceIdentifier isEqual:]
+ -[ASCCredentialServiceIdentifier type]
+ -[ASFeatureManager shouldAllowPasskeysDuringHeadlessBrowsingForRelyingParty:context:]
+ -[ASFeatureManagerCachedQuirksData domainsEligibleForPasskeysDuringAutomaticPasswordChange]
+ -[ASFeatureManagerCachedQuirksData setDomainsEligibleForPasskeysDuringAutomaticPasswordChange:]
+ GCC_except_table117
+ GCC_except_table166
+ GCC_except_table21
+ GCC_except_table24
+ GCC_except_table41
+ GCC_except_table46
+ GCC_except_table55
+ GCC_except_table99
+ _AKPrivateEmailControllerDidRegisterNewEmail
+ _AKPrivateEmailControllerDidUnregistredEmail
+ _AKPrivateEmailOriginTypeSafari
+ _ASCAuthorizationVerificationCodesDeliverySetupAccountsKey
+ _ASCAuthorizationVerificationCodesDeliverySetupReasonKey
+ _ASCAuthorizationVerificationCodesDeliverySetupRequestingAppNameKey
+ _CFPreferencesAppSynchronize
+ _CFPreferencesCopyAppValue
+ _CFPreferencesSetAppValue
+ _NSDefaultRunLoopMode
+ _OBJC_CLASS_$_AKPrivateEmail
+ _OBJC_CLASS_$_ASCCredentialServiceIdentifier
+ _OBJC_CLASS_$_ASCVerificationCodesDeliverySetupAccount
+ _OBJC_CLASS_$_NSDistributedNotificationCenter
+ _OBJC_CLASS_$_NSRunLoop
+ _OBJC_CLASS_$_WBSAutoFillPasskey
+ _OBJC_CLASS_$_WBSHeadlessBrowsingContext
+ _OBJC_CLASS_$_WBSPasswordGenerationEvent
+ _OBJC_CLASS_$_WBSPasswordGenerationProperties
+ _OBJC_CLASS_$_WBSPasswordSignInEvent
+ _OBJC_CLASS_$__TtC26AuthenticationServicesCore19ASCABLEL2CAPChannel
+ _OBJC_IVAR_$_ASAgentAutoFillListener._testWebAuthenticationManager
+ _OBJC_IVAR_$_ASAgentAutoFillListener._webAuthenticationManager
+ _OBJC_IVAR_$_ASCAgent._securityKeyPublicKeyCredentialOperationUUID
+ _OBJC_IVAR_$_ASCAgent._testWebAuthenticationManager
+ _OBJC_IVAR_$_ASCAgent._webAuthenticationManager
+ _OBJC_IVAR_$_ASCAgentListener._testWebAuthenticationManager
+ _OBJC_IVAR_$_ASCAgentListener._webAuthenticationManager
+ _OBJC_IVAR_$_ASCCredentialServiceIdentifier._displayName
+ _OBJC_IVAR_$_ASCCredentialServiceIdentifier._identifier
+ _OBJC_IVAR_$_ASCCredentialServiceIdentifier._type
+ _OBJC_IVAR_$_ASFeatureManagerCachedQuirksData._domainsEligibleForPasskeysDuringAutomaticPasswordChange
+ _OBJC_METACLASS_$_ASCCredentialServiceIdentifier
+ _OBJC_METACLASS_$_ASCVerificationCodesDeliverySetupAccount
+ _OBJC_METACLASS_$__TtC26AuthenticationServicesCore19ASCABLEL2CAPChannel
+ _OUTLINED_FUNCTION_11
+ __CATEGORY_INSTANCE_METHODS_SFCredentialProviderExtensionManager_$_ASCredentialProvider
+ __CATEGORY_SFCredentialProviderExtensionManager_$_ASCredentialProvider
+ __CLASS_METHODS_ASCVerificationCodesDeliverySetupAccount
+ __CLASS_PROPERTIES_ASCVerificationCodesDeliverySetupAccount
+ __DATA_ASCVerificationCodesDeliverySetupAccount
+ __DATA__TtC26AuthenticationServicesCore14ASCABLETimeout
+ __DATA__TtC26AuthenticationServicesCore19ASCABLEL2CAPChannel
+ __DATA__TtC26AuthenticationServicesCore21ASCHideMyEmailManager
+ __INSTANCE_METHODS_ASCVerificationCodesDeliverySetupAccount
+ __INSTANCE_METHODS__TtC26AuthenticationServicesCore19ASCABLEL2CAPChannel
+ __IVARS_ASCVerificationCodesDeliverySetupAccount
+ __IVARS__TtC26AuthenticationServicesCore14ASCABLETimeout
+ __IVARS__TtC26AuthenticationServicesCore19ASCABLEL2CAPChannel
+ __IVARS__TtC26AuthenticationServicesCore21ASCHideMyEmailManager
+ __METACLASS_DATA_ASCVerificationCodesDeliverySetupAccount
+ __METACLASS_DATA__TtC26AuthenticationServicesCore14ASCABLETimeout
+ __METACLASS_DATA__TtC26AuthenticationServicesCore19ASCABLEL2CAPChannel
+ __METACLASS_DATA__TtC26AuthenticationServicesCore21ASCHideMyEmailManager
+ __OBJC_$_CLASS_METHODS_ASCCredentialServiceIdentifier
+ __OBJC_$_CLASS_PROP_LIST_ASCCredentialServiceIdentifier
+ __OBJC_$_INSTANCE_METHODS_ASAgentAutoFillListener(SwiftAdditions)
+ __OBJC_$_INSTANCE_METHODS_ASCAgent(AuthenticationServicesCore)
+ __OBJC_$_INSTANCE_METHODS_ASCCredentialServiceIdentifier
+ __OBJC_$_INSTANCE_VARIABLES_ASCCredentialServiceIdentifier
+ __OBJC_$_PROP_LIST_ASCCredentialServiceIdentifier
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CBPeripheralDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSStreamDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBPeripheralDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSStreamDelegate
+ __OBJC_$_PROTOCOL_REFS_CBPeripheralDelegate
+ __OBJC_$_PROTOCOL_REFS_NSStreamDelegate
+ __OBJC_CLASS_PROTOCOLS_$_ASCCredentialServiceIdentifier
+ __OBJC_CLASS_RO_$_ASCCredentialServiceIdentifier
+ __OBJC_LABEL_PROTOCOL_$_CBPeripheralDelegate
+ __OBJC_LABEL_PROTOCOL_$_NSStreamDelegate
+ __OBJC_METACLASS_RO_$_ASCCredentialServiceIdentifier
+ __OBJC_PROTOCOL_$_CBPeripheralDelegate
+ __OBJC_PROTOCOL_$_NSStreamDelegate
+ __PROPERTIES_ASCVerificationCodesDeliverySetupAccount
+ __PROTOCOLS_ASCVerificationCodesDeliverySetupAccount
+ __PROTOCOLS__TtC26AuthenticationServicesCore19ASCABLEL2CAPChannel
+ ___106-[ASCAgentProxy getCanRelyingPartyPerformPasskeyRequestsDuringHeadlessBrowsing:context:completionHandler:]_block_invoke
+ ___106-[ASCAgentProxy getCanRelyingPartyPerformPasskeyRequestsDuringHeadlessBrowsing:context:completionHandler:]_block_invoke_2
+ ___107-[ASAuthorizationRemoteViewController beginVerificationCodesDeliverySetupOnEndpoint:withCompletionHandler:]_block_invoke
+ ___107-[ASAuthorizationRemoteViewController beginVerificationCodesDeliverySetupOnEndpoint:withCompletionHandler:]_block_invoke_2
+ ___112+[ASCWebKitSPISupport getCanRelyingPartyPerformPasskeyRequestsDuringHeadlessBrowsing:context:completionHandler:]_block_invoke
+ ___112+[ASCWebKitSPISupport getCanRelyingPartyPerformPasskeyRequestsDuringHeadlessBrowsing:context:completionHandler:]_block_invoke_2
+ ___116-[ASCAuthorizationRemotePresenter presentVerificationCodesDeliverySetupWithWindow:daemonEndpoint:completionHandler:]_block_invoke
+ ___116-[ASCAuthorizationRemotePresenter presentVerificationCodesDeliverySetupWithWindow:daemonEndpoint:completionHandler:]_block_invoke_2
+ ___151-[ASCAgent initWithTrafficController:connection:publicKeyCredentialManager:signInEventCollector:webAuthenticationManager:testWebAuthenticationManager:]_block_invoke
+ ___49-[ASCAgent requestCompletedWithCredential:error:]_block_invoke
+ ___68-[ASCAgent _beginAuthorizationRequestsForContext:completionHandler:]_block_invoke
+ ___68-[ASCAgent _beginAuthorizationRequestsForContext:completionHandler:]_block_invoke_2
+ ___70-[ASCAgent _beginAuthorizationForApplicationIdentifier:withPresenter:]_block_invoke
+ ___70-[ASCAgent _beginAuthorizationForApplicationIdentifier:withPresenter:]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e32_v16?0"WBSPasswordSignInEvent"8l
+ ___block_descriptor_40_e8_32bs_e36_v16?0"WBSPasswordGenerationEvent"8l
+ ___block_descriptor_41_e8_32s_e5_v8?0l
+ ___block_descriptor_48_e8_32bs40w_e20_v20?0B8"NSError"12l
+ ___block_descriptor_48_e8_32s40bs_e69_v32?0"ASCCredentialRequestContext"8"NSXPCConnection"16"NSError"24l
+ ___block_descriptor_48_e8_32s40s_e40_v32?0"NSUUID"8"NSArray"16"NSError"24l
+ ___block_descriptor_56_e8_32s40s48bs_e20_v20?0B8"NSError"12l
+ ___block_descriptor_64_e8_32s40s48s56bs_e58_v24?0"WBSPasswordSignInEvent"8"NSXPCListenerEndpoint"16l
+ ___swift_closure_destructor.25Tm
+ ___swift_closure_destructor.44Tm
+ ___swift_closure_destructor.70Tm
+ ___swift_closure_destructor.9Tm
+ ___swift_memcpy3_2
+ _associated conformance 26AuthenticationServicesCore19ASCABLEL2CAPChannelC12ChannelErrorOSHAASQ
+ _associated conformance 26AuthenticationServicesCore20ASCredentialProviderO12DisplayOrderV10Foundation14SortComparatorAASH
+ _associated conformance 26AuthenticationServicesCore20ASCredentialProviderO12DisplayOrderVSHAASQ
+ _associated conformance 26AuthenticationServicesCore26ASCABLEAdvertisementSuffixV10CodingKeysOSHAASQ
+ _associated conformance 26AuthenticationServicesCore26ASCABLEAdvertisementSuffixV10CodingKeysOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 26AuthenticationServicesCore26ASCABLEAdvertisementSuffixV10CodingKeysOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance So8ASCAgentC26AuthenticationServicesCoreE5ErrorO10Foundation021_ObjectiveCBridgeableE0ACsAD
+ _associated conformance So8ASCAgentC26AuthenticationServicesCoreE5ErrorO10Foundation13CustomNSErrorACsAD
+ _associated conformance So8ASCAgentC26AuthenticationServicesCoreE5ErrorO10Foundation15_BridgedNSErrorAC8RawValueSY_s17FixedWidthInteger
+ _associated conformance So8ASCAgentC26AuthenticationServicesCoreE5ErrorO10Foundation15_BridgedNSErrorACSH
+ _associated conformance So8ASCAgentC26AuthenticationServicesCoreE5ErrorO10Foundation15_BridgedNSErrorACSY
+ _associated conformance So8ASCAgentC26AuthenticationServicesCoreE5ErrorO10Foundation15_BridgedNSErrorAcF021_ObjectiveCBridgeableE0
+ _associated conformance So8ASCAgentC26AuthenticationServicesCoreE5ErrorOSHACSQ
+ _flat unique So8NSObject_p
+ _getCanRelyingPartyPerformPasskeyRequestsDuringHeadlessBrowsing:context:completionHandler:.agentProxy
+ _getCanRelyingPartyPerformPasskeyRequestsDuringHeadlessBrowsing:context:completionHandler:.onceToken
+ _objc_msgSend$_beginAuthorizationForApplicationIdentifier:withPresenter:
+ _objc_msgSend$_beginAuthorizationRequestsForContext:completionHandler:
+ _objc_msgSend$_cancelSecurityKeyOperationIfNecessary
+ _objc_msgSend$addFeatureChangeObserverWithChange:
+ _objc_msgSend$addObserverForName:object:queue:usingBlock:
+ _objc_msgSend$assertUsingAutoFillPasskey:authenticatedLAContext:savedAccountContext:completionHandler:
+ _objc_msgSend$autoFillPreferencesDomain
+ _objc_msgSend$beginVerificationCodesDeliverySetupOnEndpoint:withCompletionHandler:
+ _objc_msgSend$cancelPeripheralConnection:
+ _objc_msgSend$clearPublicKeyCredentialOperationForUUID:
+ _objc_msgSend$close
+ _objc_msgSend$configureForPublicKeyAssertionIfNeededWithRequestContext:clientApplicationIdentifier:completionHandler:
+ _objc_msgSend$connectPeripheral:options:
+ _objc_msgSend$createPasskeyWithOptions:authenticatedContext:isConditionalRegistration:testOptions:completionHandler:
+ _objc_msgSend$decodeInt64ForKey:
+ _objc_msgSend$defaultCenter
+ _objc_msgSend$didGenerateStrongPasswordWithProperties:
+ _objc_msgSend$domainsEligibleForPasskeysDuringAutomaticPasswordChange
+ _objc_msgSend$encodeInt64:forKey:
+ _objc_msgSend$extensionSupportsSavingPasswordCredentials:
+ _objc_msgSend$externalProviderExtensionBundleID
+ _objc_msgSend$finishTasksAndInvalidate
+ _objc_msgSend$generationEventForAnyRecentGenerationForServiceIdentifierType:serviceIdentifier:hostApplicationBundleIdentifier:completionHandler:
+ _objc_msgSend$getAutoFillAssertionResultForOperationUUID:completionHandler:
+ _objc_msgSend$getCanRelyingPartyPerformPasskeyRequestsDuringHeadlessBrowsing:context:completionHandler:
+ _objc_msgSend$hasBytesAvailable
+ _objc_msgSend$hasSpaceAvailable
+ _objc_msgSend$hostApplicationBundleIdentifier
+ _objc_msgSend$initWithCoder:
+ _objc_msgSend$initWithDelegate:isRegistrationRequest:sourceApplicationIdentifier:
+ _objc_msgSend$initWithEmailAddress:user:serviceIdentifier:
+ _objc_msgSend$initWithIdentifier:type:
+ _objc_msgSend$initWithIdentifier:type:displayName:
+ _objc_msgSend$initWithProviderApplicationBundleIdentifier:providerExtensionBundleIdentifier:
+ _objc_msgSend$initWithProviderApplicationBundleIdentifier:providerExtensionBundleIdentifier:passwordKind:sessionID:
+ _objc_msgSend$initWithStrongPassword:passwordKind:serviceIdentifierType:serviceIdentifier:providerApplicationBundleIdentifier:providerExtensionBundleIdentifier:hostApplicationBundleIdentifier:sessionID:
+ _objc_msgSend$initWithTrafficController:connection:publicKeyCredentialManager:signInEventCollector:webAuthenticationManager:testWebAuthenticationManager:
+ _objc_msgSend$inputStream
+ _objc_msgSend$isContextDictionaryForAutomaticPasswordChange:
+ _objc_msgSend$listAllPrivateEmailsForAltDSID:completion:
+ _objc_msgSend$lookupPrivateEmailWithContext:completion:
+ _objc_msgSend$mainRunLoop
+ _objc_msgSend$open
+ _objc_msgSend$openL2CAPChannel:
+ _objc_msgSend$outputStream
+ _objc_msgSend$passkeysForRunningAssertionWithApplicationIdentifier:webPageURL:withCompletionHandler:
+ _objc_msgSend$performAssertionWithLoginChoice:authenticatedContext:completionHandler:
+ _objc_msgSend$presentVerificationCodesDeliverySetupWithWindow:daemonEndpoint:completionHandler:
+ _objc_msgSend$publicKeyCredentialManager
+ _objc_msgSend$read:maxLength:
+ _objc_msgSend$removeFeatureChangeObserverWithToken:
+ _objc_msgSend$removeFromRunLoop:forMode:
+ _objc_msgSend$safari_ephemeralSessionConfiguration
+ _objc_msgSend$safari_highLevelDomainFromHost
+ _objc_msgSend$scheduleInRunLoop:forMode:
+ _objc_msgSend$sessionID
+ _objc_msgSend$setDomainsEligibleForPasskeysDuringAutomaticPasswordChange:
+ _objc_msgSend$setSecurityKeyPublicKeyCredentialOperationUUID:
+ _objc_msgSend$set_sourceApplicationBundleIdentifier:
+ _objc_msgSend$shouldAllowPasskeysDuringHeadlessBrowsingForRelyingParty:context:
+ _objc_msgSend$shouldUsePasskeysInAuthenticationServices
+ _objc_msgSend$streamError
+ _objc_msgSend$strongPassword
+ _objc_msgSend$testWebAuthenticationManager
+ _objc_msgSend$type
+ _objc_msgSend$webAuthenticationManager
+ _objc_msgSend$write:maxLength:
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get
+ _swift_bridgeObjectRelease_n
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic $s10Foundation14SortComparatorP
+ _symbolic $s26AuthenticationServicesCore05ASWebA16ManagerInterfaceP
+ _symbolic $s26AuthenticationServicesCore18ASCABLEDataChannelP
+ _symbolic $s26AuthenticationServicesCore21ASCHideMyEmailLookupsP
+ _symbolic $s26AuthenticationServicesCore26ASCABLEDataChannelDelegateP
+ _symbolic $s26AuthenticationServicesCore31ASCredentialProviderPreferencesP
+ _symbolic Ieg_
+ _symbolic IeyB_Sg
+ _symbolic SaySiG
+ _symbolic SaySiGSg
+ _symbolic SaySo14AKPrivateEmailCG
+ _symbolic Say_____G 10Foundation4DataV
+ _symbolic Say_____G 26AuthenticationServicesCore20ASCredentialProviderO
+ _symbolic Say______pG So8NSObjectP
+ _symbolic SccySaySo14AKPrivateEmailCGSg______pG s5ErrorP
+ _symbolic Sd
+ _symbolic ShySSG
+ _symbolic Shy_____G 26AuthenticationServicesCore20ASCredentialProviderO
+ _symbolic So12CBPeripheralCSg
+ _symbolic So13NSInputStreamC
+ _symbolic So14NSOutputStreamC
+ _symbolic So18WBSAutoFillPasskeyC
+ _symbolic So22WBSPasswordSignInEventCSgIeyBy_
+ _symbolic So22WBSPasswordSignInEventCSgSo21NSXPCListenerEndpointCSgIeyByy_
+ _symbolic So22WBSSavedAccountContextCSg
+ _symbolic So23ASAgentAutoFillListenerC
+ _symbolic So26WBSPasswordGenerationEventCSgIeyBy_
+ _symbolic So27ASCCredentialRequestContextC
+ _symbolic So31WBSPasswordGenerationPropertiesC
+ _symbolic So39ASCPlatformPublicKeyCredentialAssertionCSgSo7NSErrorCSgIeyByy_
+ _symbolic So41ASCPlatformPublicKeyCredentialLoginChoiceC
+ _symbolic So42ASCPlatformPublicKeyCredentialRegistrationCSgSo7NSErrorCSgIeyByy_
+ _symbolic So5NSURLCSg
+ _symbolic So6NSUUIDC
+ _symbolic So6NSUUIDCSgSo7NSArrayCSgSo7NSErrorCSgIeyByyy_
+ _symbolic So7NSArrayCIeyBy_Sg
+ _symbolic So7NSArrayCSo41WBSPasskeyAutoFillFromNearbyDeviceOptionsCSgIeyByy_Sg
+ _symbolic So8ASCAgentC
+ _symbolic So9LAContextCSg
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 10Foundation9SortOrderO
+ _symbolic _____ 26AuthenticationServicesCore14ASCABLETimeoutC
+ _symbolic _____ 26AuthenticationServicesCore19ASCABLEL2CAPChannelC
+ _symbolic _____ 26AuthenticationServicesCore19ASCABLEL2CAPChannelC12ChannelErrorO
+ _symbolic _____ 26AuthenticationServicesCore20ASCredentialProviderO12DisplayOrderV
+ _symbolic _____ 26AuthenticationServicesCore21ASCHideMyEmailManagerC
+ _symbolic _____ 26AuthenticationServicesCore26ASCABLEAdvertisementSuffixV
+ _symbolic _____ 26AuthenticationServicesCore26ASCABLEAdvertisementSuffixV10CodingKeysO
+ _symbolic _____ So8ASCAgentC26AuthenticationServicesCoreE5ErrorO
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic _____Sg 11CBORLibrary7COSEKeyV
+ _symbolic _____Sg 26AuthenticationServicesCore31ASCCredentialRequestTestOptionsC
+ _symbolic _____Sg s6UInt16V
+ _symbolic _____SgXw 26AuthenticationServicesCore14ASCABLETimeoutC
+ _symbolic _____SgXw 26AuthenticationServicesCore21ASCHideMyEmailManagerC
+ _symbolic _____SgXwz_Xx 26AuthenticationServicesCore13ASCABLEClientC
+ _symbolic _____SgXwz_Xx 26AuthenticationServicesCore14ASCABLETimeoutC
+ _symbolic _____SgXwz_Xx 26AuthenticationServicesCore21ASCHideMyEmailManagerC
+ _symbolic _____XDXMT 26AuthenticationServicesCore13ASCABLEClientC
+ _symbolic ______p 26AuthenticationServicesCore05ASWebA16ManagerInterfaceP
+ _symbolic ______pSg 26AuthenticationServicesCore18ASCABLEDataChannelP
+ _symbolic ______pSg So8NSObjectP
+ _symbolic ______pSgXw 26AuthenticationServicesCore26ASCABLEDataChannelDelegateP
+ _symbolic _____ySSG 10SafariCore13WBSOrderedSetV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 26AuthenticationServicesCore26ASCABLEAdvertisementSuffixV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 26AuthenticationServicesCore26ASCABLEAdvertisementSuffixV10CodingKeysO
+ _symbolic yXlSg
+ _symbolic ytSg
+ _symbolic ytSgIeAgHr_
+ _type_layout_string 26AuthenticationServicesCore20ASCredentialProviderO12DisplayOrderV
+ _type_layout_string 26AuthenticationServicesCore26ASCABLEAdvertisementSuffixV
- +[ASCWebKitSPISupport arePasskeysDisallowedForRelyingParty:]
- +[ASCWebKitSPISupport getArePasskeysDisallowedForRelyingParty:withCompletionHandler:]
- -[ASAgentAutoFillListener initWithPublicKeyCredentialManager:signInEventCollector:]
- -[ASCAgent _shouldApplyQuirksToClientWithApplicationIdentifier:]
- -[ASCAgent getArePasskeysDisallowedForRelyingParty:withCompletionHandler:]
- -[ASCAgent initWithTrafficController:connection:publicKeyCredentialManager:signInEventCollector:]
- -[ASCAgentListener initWithPublicKeyCredentialManager:]
- -[ASCAgentProxy getArePasskeysDisallowedForRelyingParty:withCompletionHandler:]
- -[ASCAuthorizationPresenter presentError:forService:completionHandler:]
- -[ASCSecurityKeyPublicKeyCredentialLoginChoice setPublicKeyCredentialOperationUUID:]
- -[ASFeatureManager arePasskeysDisallowedForRelyingParty:]
- -[ASFeatureManagerCachedQuirksData domainsIneligibleForPasskeys]
- -[ASFeatureManagerCachedQuirksData setDomainsIneligibleForPasskeys:]
- GCC_except_table107
- GCC_except_table157
- GCC_except_table16
- GCC_except_table38
- GCC_except_table43
- GCC_except_table58
- GCC_except_table94
- _OBJC_CLASS_$__TtC26AuthenticationServicesCore22ASCPasswordSignInEvent
- _OBJC_CLASS_$__TtC26AuthenticationServicesCore26ASCPasswordGenerationEvent
- _OBJC_IVAR_$_ASFeatureManagerCachedQuirksData._domainsIneligibleForPasskeys
- _OBJC_METACLASS_$__TtC26AuthenticationServicesCore22ASCPasswordSignInEvent
- _OBJC_METACLASS_$__TtC26AuthenticationServicesCore26ASCPasswordGenerationEvent
- _WBSSafariViewServiceBundleIdentifier
- __DATA__TtC26AuthenticationServicesCore22ASCPasswordSignInEvent
- __DATA__TtC26AuthenticationServicesCore26ASCPasswordGenerationEvent
- __INSTANCE_METHODS__TtC26AuthenticationServicesCore22ASCPasswordSignInEvent
- __INSTANCE_METHODS__TtC26AuthenticationServicesCore26ASCPasswordGenerationEvent
- __IVARS__TtC26AuthenticationServicesCore22ASCPasswordSignInEvent
- __IVARS__TtC26AuthenticationServicesCore26ASCPasswordGenerationEvent
- __METACLASS_DATA__TtC26AuthenticationServicesCore22ASCPasswordSignInEvent
- __METACLASS_DATA__TtC26AuthenticationServicesCore26ASCPasswordGenerationEvent
- __OBJC_$_INSTANCE_METHODS_ASAgentAutoFillListener
- __OBJC_$_INSTANCE_METHODS_ASCAgent
- __PROPERTIES__TtC26AuthenticationServicesCore22ASCPasswordSignInEvent
- __PROPERTIES__TtC26AuthenticationServicesCore26ASCPasswordGenerationEvent
- ___60+[ASCWebKitSPISupport arePasskeysDisallowedForRelyingParty:]_block_invoke
- ___69-[ASCAgent beginAuthorizationForApplicationIdentifier:withPresenter:]_block_invoke
- ___69-[ASCAgent beginAuthorizationForApplicationIdentifier:withPresenter:]_block_invoke_2
- ___72-[ASCAgent performAuthorizationRequestsForContext:withClearanceHandler:]_block_invoke_2
- ___79-[ASCAgentProxy getArePasskeysDisallowedForRelyingParty:withCompletionHandler:]_block_invoke
- ___79-[ASCAgentProxy getArePasskeysDisallowedForRelyingParty:withCompletionHandler:]_block_invoke_2
- ___85+[ASCWebKitSPISupport getArePasskeysDisallowedForRelyingParty:withCompletionHandler:]_block_invoke
- ___85+[ASCWebKitSPISupport getArePasskeysDisallowedForRelyingParty:withCompletionHandler:]_block_invoke_2
- ___96-[ASCAgent _prepareForAuthorizationRequestsForContext:clientConnection:withPresentationHandler:]_block_invoke_6
- ___97-[ASCAgent initWithTrafficController:connection:publicKeyCredentialManager:signInEventCollector:]_block_invoke
- ___block_descriptor_40_e8_32bs_e66_v16?0"_TtC26AuthenticationServicesCore22ASCPasswordSignInEvent"8l
- ___block_descriptor_40_e8_32bs_e70_v16?0"_TtC26AuthenticationServicesCore26ASCPasswordGenerationEvent"8l
- ___block_descriptor_64_e8_32s40s48s56bs_e66_v16?0"_TtC26AuthenticationServicesCore22ASCPasswordSignInEvent"8l
- ___swift_closure_destructor.22Tm
- ___swift_closure_destructor.5Tm
- ___swift_memcpy51_8
- _getArePasskeysDisallowedForRelyingParty:withCompletionHandler:.agentProxy
- _getArePasskeysDisallowedForRelyingParty:withCompletionHandler:.onceToken
- _objc_msgSend$_shouldApplyQuirksToClientWithApplicationIdentifier:
- _objc_msgSend$arePasskeysDisallowedForRelyingParty:
- _objc_msgSend$beginAuthorizationForApplicationIdentifier:withPresenter:
- _objc_msgSend$domainsIneligibleForPasskeys
- _objc_msgSend$ephemeralSessionConfiguration
- _objc_msgSend$externalProviderListenerEndpoint
- _objc_msgSend$getArePasskeysDisallowedForRelyingParty:withCompletionHandler:
- _objc_msgSend$initWithDelegate:isRegistrationRequest:
- _objc_msgSend$initWithTrafficController:connection:publicKeyCredentialManager:signInEventCollector:
- _objc_msgSend$presentError:forService:completionHandler:
- _objc_msgSend$removePasskeyRequests
- _objc_msgSend$safari_isPasswordManagerFamily
- _objc_msgSend$setDomainsIneligibleForPasskeys:
- _objc_msgSend$sharedSession
- _symbolic $s26AuthenticationServicesCore19ASWebSocketDelegateP
- _symbolic _____ 26AuthenticationServicesCore22ASCPasswordSignInEventC
- _symbolic _____ 26AuthenticationServicesCore26ASCPasswordGenerationEventC
- _symbolic _____Sg 26AuthenticationServicesCore11ASWebSocketC
- _symbolic _____SgIeyBy_ 26AuthenticationServicesCore22ASCPasswordSignInEventC
- _symbolic _____SgIeyBy_ 26AuthenticationServicesCore26ASCPasswordGenerationEventC
- _symbolic ______pSgXw 26AuthenticationServicesCore19ASWebSocketDelegateP
- _symbolic _____ySnySiGG s23_ContiguousArrayStorageC
CStrings:
+ "-[ASCAgent _beginAuthorizationRequestsForContext:completionHandler:]_block_invoke"
+ "-[ASCAgent _beginAuthorizationRequestsForContext:completionHandler:]_block_invoke_2"
+ "-[ASCAgent requestCompletedWithCredential:error:]_block_invoke"
+ "<%@: %p; type=%@; identifier=%@; displayName=%@>"
+ "ASCAuthorizationVerificationCodesDeliverySetupAccounts"
+ "ASCAuthorizationVerificationCodesDeliverySetupReason"
+ "ASCAuthorizationVerificationCodesDeliverySetupRequestingAppName"
+ "ASCredentialServiceIdentifierDisplayName"
+ "ASCredentialServiceIdentifierType"
+ "ASCredentialServiceIdentifierValue"
+ "Acquired lock for %{public}s"
+ "Advertisement offers a BLE L2CAP channel (PSM %hu); connecting to the beacon peripheral."
+ "AuthenticationServicesCore.ASCABLEL2CAPChannel"
+ "AuthenticationServicesCore.ASCAgent.Error"
+ "AuthenticationServicesCore/ASCVerificationCodesDeliverySetupAccount.swift"
+ "AuthenticationServicesCore/ASCredentialProvider.swift"
+ "Biometrics enabled but in lockout"
+ "Cannot create an app service identifier without a displayName"
+ "Connected to peripheral; opening L2CAP channel with PSM %hu."
+ "Connecting to relay at %{sensitive}s"
+ "Could not construct COSEKey"
+ "Could not find operation UUID."
+ "Could not open L2CAP channel: %{public}s. Falling back to the tunnel server."
+ "Error configuring for passkey assertion: %{public}@"
+ "Failed to acquire lock for %{public}s"
+ "Failed to connect to peripheral for L2CAP: %{public}s. Falling back to the tunnel server."
+ "Failed to fetch Hide My Email addresses. %{public}s"
+ "Found unexpected value for credential service identifier type: %ld"
+ "L2CAP %s stream event: %lu"
+ "L2CAP %{public}s stream error: %{public}s"
+ "L2CAP %{public}s stream reached end."
+ "L2CAP inbound framing failed: %{public}s"
+ "L2CAP output stream opened; channel is ready."
+ "L2CAP write returned %ld; waiting for more space."
+ "L2CAP wrote %ld bytes; %ld chunks still queued."
+ "Opened L2CAP channel; beginning handshake."
+ "PreferredCredentialProviderForSaving"
+ "PreferredCredentialProviderForSavingPasswords"
+ "Received P256 key with unexpected format"
+ "Received largeBlob assertion with no data. This likely means there was no blob."
+ "Received prf assertion response with no results."
+ "Received unexpected string frame: %s"
+ "Released lock for %{public}s"
+ "Timed out establishing the BLE L2CAP channel. Falling back to the tunnel server."
+ "Timed out waiting for the authenticator to complete the handshake."
+ "Tried to connect to tunnel server without an advertisement."
+ "app"
+ "connectingPeripheral"
+ "domain"
+ "openingL2CAPChannel"
+ "supportedTransports"
+ "url"
+ "v16@?0@\"WBSPasswordGenerationEvent\"8"
+ "v16@?0@\"WBSPasswordSignInEvent\"8"
+ "v24@?0@\"WBSPasswordSignInEvent\"8@\"NSXPCListenerEndpoint\"16"
+ "v32@?0@\"ASCCredentialRequestContext\"8@\"NSXPCConnection\"16@\"NSError\"24"
+ "v32@?0@\"NSUUID\"8@\"NSArray\"16@\"NSError\"24"
- "-[ASCAgent performAuthorizationRequestsForContext:withClearanceHandler:]_block_invoke"
- "-[ASCAgent performAuthorizationRequestsForContext:withClearanceHandler:]_block_invoke_2"
- "AuthenticationServicesCore.ASCPasswordGenerationEvent"
- "AuthenticationServicesCore.ASCPasswordSignInEvent"
- "AuthenticationServicesCore.ASCredentialProviderObject"
- "Connecting to relay at %s"
- "Dropping passkey requests from quirked relying party."
- "Synchronously looking up passkey quirks."
- "Unexpectedly received string frame: %s"
- "v16@?0@\"_TtC26AuthenticationServicesCore22ASCPasswordSignInEvent\"8"
- "v16@?0@\"_TtC26AuthenticationServicesCore26ASCPasswordGenerationEvent\"8"
```
