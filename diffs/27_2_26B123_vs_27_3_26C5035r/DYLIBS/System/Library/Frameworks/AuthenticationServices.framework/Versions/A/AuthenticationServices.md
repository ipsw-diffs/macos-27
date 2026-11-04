## AuthenticationServices

> `/System/Library/Frameworks/AuthenticationServices.framework/Versions/A/AuthenticationServices`

### Sections with Same Size but Changed Content

- `__TEXT.__ustring`

```diff

-625.2.8.11.9
-  __TEXT.__text: 0x10f484
-  __TEXT.__objc_methlist: 0x7f7c
-  __TEXT.__const: 0x12784
-  __TEXT.__cstring: 0xb168
+626.1.12.11.4
+  __TEXT.__text: 0x118344
+  __TEXT.__objc_methlist: 0x80e8
+  __TEXT.__const: 0x12c84
+  __TEXT.__cstring: 0xb218
   __TEXT.__ustring: 0x65ac
-  __TEXT.__oslogstring: 0x33e8
-  __TEXT.__gcc_except_tab: 0x11a4
+  __TEXT.__oslogstring: 0x3858
+  __TEXT.__gcc_except_tab: 0x11f0
   __TEXT.__dlopen_cstrs: 0x25e
-  __TEXT.__swift5_typeref: 0x2ab0
-  __TEXT.__constg_swiftt: 0x1eb4
-  __TEXT.__swift5_reflstr: 0x199a
-  __TEXT.__swift5_fieldmd: 0x2b18
-  __TEXT.__swift5_builtin: 0x1e0
-  __TEXT.__swift5_assocty: 0x730
-  __TEXT.__swift5_proto: 0x8ec
-  __TEXT.__swift5_types: 0x2f4
-  __TEXT.__swift_as_entry: 0x1d4
-  __TEXT.__swift_as_ret: 0x1f4
-  __TEXT.__swift_as_cont: 0x3d0
+  __TEXT.__swift5_typeref: 0x2e4a
+  __TEXT.__swift5_fieldmd: 0x2c60
+  __TEXT.__constg_swiftt: 0x2000
+  __TEXT.__swift5_reflstr: 0x1af1
+  __TEXT.__swift5_builtin: 0x208
+  __TEXT.__swift5_assocty: 0x7a8
+  __TEXT.__swift5_proto: 0x91c
+  __TEXT.__swift5_types: 0x314
+  __TEXT.__swift_as_entry: 0x1ec
+  __TEXT.__swift_as_ret: 0x218
+  __TEXT.__swift_as_cont: 0x41c
   __TEXT.__swift5_protos: 0x24
-  __TEXT.__swift5_capture: 0xb54
+  __TEXT.__swift5_capture: 0xc4c
   __TEXT.__swift5_mpenum: 0x90
-  __TEXT.__unwind_info: 0x6398
-  __TEXT.__eh_frame: 0x5598
+  __TEXT.__unwind_info: 0x66e0
+  __TEXT.__eh_frame: 0x5cb0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x850
-  __DATA_CONST.__objc_classlist: 0x528
+  __DATA_CONST.__objc_classlist: 0x538
   __DATA_CONST.__objc_catlist: 0x60
-  __DATA_CONST.__objc_protolist: 0x2a8
+  __DATA_CONST.__objc_protolist: 0x2b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4bd8
-  __DATA_CONST.__objc_protorefs: 0xf8
-  __DATA_CONST.__objc_superrefs: 0x340
+  __DATA_CONST.__objc_selrefs: 0x4d18
+  __DATA_CONST.__objc_protorefs: 0x108
+  __DATA_CONST.__objc_superrefs: 0x348
   __DATA_CONST.__objc_arraydata: 0x1a0
-  __DATA_CONST.__got: 0xea8
-  __AUTH_CONST.__const: 0x9d20
-  __AUTH_CONST.__cfstring: 0x48a0
-  __AUTH_CONST.__objc_const: 0xf928
+  __DATA_CONST.__got: 0xf10
+  __AUTH_CONST.__const: 0xa2f0
+  __AUTH_CONST.__cfstring: 0x4980
+  __AUTH_CONST.__objc_const: 0xfd88
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_intobj: 0xa8
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x1358
-  __AUTH.__objc_data: 0x3060
-  __AUTH.__data: 0x13c0
-  __DATA.__objc_ivar: 0x79c
-  __DATA.__data: 0x3330
-  __DATA.__bss: 0x10c20
+  __AUTH_CONST.__auth_got: 0x13b0
+  __AUTH.__objc_data: 0x3068
+  __AUTH.__data: 0x1588
+  __DATA.__objc_ivar: 0x7bc
+  __DATA.__data: 0x3460
+  __DATA.__bss: 0x11020
   __DATA.__common: 0x20
   __DATA_DIRTY.__objc_data: 0xa10
   __DATA_DIRTY.__data: 0xc8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7472
-  Symbols:   8237
-  CStrings:  1351
+  Functions: 7667
+  Symbols:   8387
+  CStrings:  1375
 
Symbols:
+ +[_ASPasswordManagerDeleteAlertConfiguration _canUseSingleItemConfigurationWithAccountsSelectionInfo:]
+ +[_ASPasswordManagerDeleteAlertConfiguration _namesOfWiFiNetworks:]
+ +[_ASPasswordManagerDeleteAlertConfiguration _shouldUseWLANTerminologyInsteadOfWiFi]
+ +[_ASPasswordManagerDeleteAlertConfiguration _titleStringForAlertToDeleteMixedItemsIsPermanentlyDeleting:]
+ +[_ASPasswordManagerDeleteAlertConfiguration _wiFiOnlySubtitleStringWithAccountsSelectionInfo:]
+ +[_ASPasswordManagerDeleteAlertConfiguration _wiFiSubtitleStringWithAccountsSelectionInfo:]
+ +[_ASPasswordManagerDeleteAlertConfiguration configurationForDeletingSavedAccounts:wiFiNetworks:]
+ -[ASAuthorizationServiceViewController _finishVerificationCodesDeliverySetupWithShouldProceed:error:]
+ -[ASAuthorizationServiceViewController _presentVerificationCodesDeliverySetupViewControllerWithAccounts:reason:requestingAppName:completionHandler:]
+ -[ASAuthorizationServiceViewController beginVerificationCodesDeliverySetupOnEndpoint:withCompletionHandler:]
+ -[ASCredentialRequestConfirmButtonSubPane setUpButtonWithTitle:]
+ -[ASNavigationControllerBarView _initWithFrame:topPadding:pinsItemsToBottomEdge:]
+ -[ASPasskeyCredentialRequest initWithCredentialIdentity:requestType:clientDataHash:userVerificationPreference:supportedAlgorithms:]
+ -[_ASAgentCredentialExchangeListener _connection:ownsOperation:]
+ -[_ASAgentCredentialExchangeListener _performWithLockIfOperationIsCurrent:block:]
+ -[_ASAgentCredentialExchangeListener _terminateOperationIfCurrent:]
+ -[_ASConditionalRegistrationRequester init]
+ -[_ASPasswordManagerAccountsSelectionInfo .cxx_destruct]
+ -[_ASPasswordManagerAccountsSelectionInfo accounts]
+ -[_ASPasswordManagerAccountsSelectionInfo hasWiFiNetworks]
+ -[_ASPasswordManagerAccountsSelectionInfo initWithSavedAccounts:wiFiNetworks:]
+ -[_ASPasswordManagerAccountsSelectionInfo managedWiFiNetworks]
+ -[_ASPasswordManagerAccountsSelectionInfo wiFiNetworksToForget]
+ -[_ASPasswordManagerDeleteAlertConfiguration hasIrreversibleConsequences]
+ GCC_except_table36
+ GCC_except_table44
+ GCC_except_table52
+ GCC_except_table58
+ GCC_except_table59
+ GCC_except_table60
+ GCC_except_table70
+ GCC_except_table72
+ GCC_except_table74
+ GCC_except_table80
+ GCC_except_table82
+ GCC_except_table85
+ GCC_except_table95
+ _ASInterfaceForVerificationCodesDeliverySetupDaemonProtocol
+ _MGGetBoolAnswer
+ _OBJC_CLASS_$_ASCCredentialServiceIdentifier
+ _OBJC_CLASS_$_ASCVerificationCodesDeliverySetupAccount
+ _OBJC_CLASS_$_NSURLProtectionSpace
+ _OBJC_CLASS_$_WBSWiFiNetworkLocalizedStrings
+ _OBJC_IVAR_$_ASAuthorizationServiceViewController._verificationCodesDeliverySetupCompletionHandler
+ _OBJC_IVAR_$_ASAuthorizationServiceViewController._verificationCodesDeliverySetupDaemonConnection
+ _OBJC_IVAR_$_ASAuthorizationServiceViewController._verificationCodesDeliverySetupViewController
+ _OBJC_IVAR_$__ASConditionalRegistrationRequester._queue
+ _OBJC_IVAR_$__ASPasswordManagerAccountsSelectionInfo._accounts
+ _OBJC_IVAR_$__ASPasswordManagerAccountsSelectionInfo._managedWiFiNetworks
+ _OBJC_IVAR_$__ASPasswordManagerAccountsSelectionInfo._wiFiNetworksToForget
+ _OBJC_IVAR_$__ASPasswordManagerDeleteAlertConfiguration._isForgettingWiFiNetworks
+ __DATA__TtC22AuthenticationServicesP33_5715F930C8FEF8ACFAE0CBB4BA5B403E37VerificationCodesDeliverySetupSession
+ __DATA__TtC22AuthenticationServicesP33_5715F930C8FEF8ACFAE0CBB4BA5B403E45VerificationCodesDeliverySetupSessionsManager
+ __IVARS__TtC22AuthenticationServicesP33_5715F930C8FEF8ACFAE0CBB4BA5B403E37VerificationCodesDeliverySetupSession
+ __IVARS__TtC22AuthenticationServicesP33_5715F930C8FEF8ACFAE0CBB4BA5B403E45VerificationCodesDeliverySetupSessionsManager
+ __METACLASS_DATA__TtC22AuthenticationServicesP33_5715F930C8FEF8ACFAE0CBB4BA5B403E37VerificationCodesDeliverySetupSession
+ __METACLASS_DATA__TtC22AuthenticationServicesP33_5715F930C8FEF8ACFAE0CBB4BA5B403E45VerificationCodesDeliverySetupSessionsManager
+ __OBJC_$_INSTANCE_METHODS_ASAgentVerificationCodesService(AuthenticationServices|AuthenticationServices1)
+ __OBJC_$_INSTANCE_METHODS_ASAuthorizationController(SwiftImplementation|AuthenticationServices)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS__TtP22AuthenticationServices46ASVerificationCodesDeliverySetupDaemonProtocol_
+ __OBJC_$_PROTOCOL_METHOD_TYPES__TtP22AuthenticationServices46ASVerificationCodesDeliverySetupDaemonProtocol_
+ __OBJC_$_PROTOCOL_REFS__TtP22AuthenticationServices46ASVerificationCodesDeliverySetupDaemonProtocol_
+ __OBJC_CLASS_PROTOCOLS_$_ASAgentVerificationCodesService(AuthenticationServices|AuthenticationServices1)
+ __OBJC_LABEL_PROTOCOL_$__TtP22AuthenticationServices46ASVerificationCodesDeliverySetupDaemonProtocol_
+ __OBJC_PROTOCOL_$__TtP22AuthenticationServices46ASVerificationCodesDeliverySetupDaemonProtocol_
+ __OBJC_PROTOCOL_REFERENCE_$__TtP22AuthenticationServices46ASVerificationCodesDeliverySetupDaemonProtocol_
+ __PROTOCOL_INSTANCE_METHODS__TtP22AuthenticationServices46ASVerificationCodesDeliverySetupDaemonProtocol_
+ __PROTOCOL_METHOD_TYPES__TtP22AuthenticationServices46ASVerificationCodesDeliverySetupDaemonProtocol_
+ __PROTOCOL_PROTOCOLS__TtP22AuthenticationServices46ASVerificationCodesDeliverySetupDaemonProtocol_
+ __PROTOCOL__TtP22AuthenticationServices46ASVerificationCodesDeliverySetupDaemonProtocol_
+ ___101-[ASAuthorizationServiceViewController _finishVerificationCodesDeliverySetupWithShouldProceed:error:]_block_invoke
+ ___101-[ASAuthorizationServiceViewController _finishVerificationCodesDeliverySetupWithShouldProceed:error:]_block_invoke_2
+ ___103-[_ASConditionalRegistrationRequester requestAutomaticPasskeyUpgradeWithLoginChoice:completionHandler:]_block_invoke
+ ___108-[ASAuthorizationServiceViewController beginVerificationCodesDeliverySetupOnEndpoint:withCompletionHandler:]_block_invoke
+ ___108-[ASAuthorizationServiceViewController beginVerificationCodesDeliverySetupOnEndpoint:withCompletionHandler:]_block_invoke_2
+ ___119-[_ASConditionalRegistrationRequester credentialAuthenticationViewController:didFinishWithCredential:error:completion:]_block_invoke
+ ___138-[_ASConditionalRegistrationRequester credentialAuthenticationViewController:didFinishWithPasskeyRegistrationCredential:error:completion:]_block_invoke
+ ___148-[ASAuthorizationServiceViewController _presentVerificationCodesDeliverySetupViewControllerWithAccounts:reason:requestingAppName:completionHandler:]_block_invoke
+ ___64-[ASCredentialRequestConfirmButtonSubPane setUpButtonWithTitle:]_block_invoke
+ ___67-[_ASAgentCredentialExchangeListener _terminateOperationIfCurrent:]_block_invoke
+ ___70+[_ASWebsiteNameProvider fetchWebsiteNameForDomain:completionHandler:]_block_invoke_2
+ ___76-[_ASAgentCredentialExchangeListener _setUpImporterConnection:forOperation:]_block_invoke_2
+ ___79-[_ASAgentCredentialExchangeListener _setUpViewServiceConnection:forOperation:]_block_invoke_2
+ ___83-[_ASAgentCredentialExchangeListener importCredentialsWithToken:completionHandler:]_block_invoke
+ ___86-[_ASAgentCredentialExchangeListener continueExportWithCredentials:completionHandler:]_block_invoke_3
+ ___97+[_ASPasswordManagerDeleteAlertConfiguration configurationForDeletingSavedAccounts:wiFiNetworks:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e45_v40?0"NSArray"8Q16"NSString"24"NSError"32l
+ ___block_descriptor_48_e8_32s40w_e17_v16?0"NSTimer"8l
+ ___block_descriptor_49_e8_32s40s_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48bs56r64r_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0l
+ ___block_descriptor_72_ea8_32s40s48s56bs_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48b56r64r
+ ___destroy_helper_block_e8_32s40s48s56r64r
+ ___swift_closure_destructor.107Tm
+ ___swift_closure_destructor.16Tm
+ ___swift_closure_destructor.202Tm
+ ___swift_closure_destructor.96Tm
+ _associated conformance 22AuthenticationServices35ASDeliveredVerificationCodesManagerC11SetUpReasonOSHAASQ
+ _associated conformance 22AuthenticationServices35ASDeliveredVerificationCodesManagerC21AccountRecordForSetUpV13ContactMethodOSHAASQ
+ _objc_msgSend$_canUseSingleItemConfigurationWithAccountsSelectionInfo:
+ _objc_msgSend$_connection:ownsOperation:
+ _objc_msgSend$_finishVerificationCodesDeliverySetupWithShouldProceed:error:
+ _objc_msgSend$_initWithFrame:topPadding:pinsItemsToBottomEdge:
+ _objc_msgSend$_namesOfWiFiNetworks:
+ _objc_msgSend$_performWithLockIfOperationIsCurrent:block:
+ _objc_msgSend$_presentVerificationCodesDeliverySetupViewControllerWithAccounts:reason:requestingAppName:completionHandler:
+ _objc_msgSend$_shouldUseWLANTerminologyInsteadOfWiFi
+ _objc_msgSend$_terminateOperationIfCurrent:
+ _objc_msgSend$_titleStringForAlertToDeleteMixedItemsIsPermanentlyDeleting:
+ _objc_msgSend$_wiFiOnlySubtitleStringWithAccountsSelectionInfo:
+ _objc_msgSend$_wiFiSubtitleStringWithAccountsSelectionInfo:
+ _objc_msgSend$accounts
+ _objc_msgSend$arrayWithCapacity:
+ _objc_msgSend$checkForSupport
+ _objc_msgSend$configurationForDeletingSavedAccounts:wiFiNetworks:
+ _objc_msgSend$constraintGreaterThanOrEqualToAnchor:constant:
+ _objc_msgSend$forgetAllManagedNetworksSubtitleStringForNumberOfNetworks:preferWLANTerminology:
+ _objc_msgSend$forgetManagedNetworksTitleStringPreferringWLANTerminology:
+ _objc_msgSend$forgetNetworksSubtitleStringForNumberOfNetworks:preferWLANTerminology:
+ _objc_msgSend$forgetNetworksTitleStringForNumberOfNetworks:preferWLANTerminology:
+ _objc_msgSend$forgetSomeManagedNetworksSubtitleSuffixStringForNames:preferWLANTerminology:
+ _objc_msgSend$getVerificationCodesDeliverySetupInfoWithCompletionHandler:
+ _objc_msgSend$hasWiFiNetworks
+ _objc_msgSend$initWithAccounts:reason:requestingAppName:completionHandler:
+ _objc_msgSend$initWithCredentialIdentity:requestType:clientDataHash:userVerificationPreference:supportedAlgorithms:
+ _objc_msgSend$initWithEmailAddress:user:serviceIdentifier:
+ _objc_msgSend$initWithSavedAccounts:wiFiNetworks:
+ _objc_msgSend$isInternalInstall
+ _objc_msgSend$isManagedByProfile
+ _objc_msgSend$localizedShortName
+ _objc_msgSend$managedWiFiNetworks
+ _objc_msgSend$object
+ _objc_msgSend$presentAccountsToSetUp:reason:windowSceneIdentifier:completionHandler:
+ _objc_msgSend$presentVerificationCodesDeliverySetupWithWindow:daemonEndpoint:completionHandler:
+ _objc_msgSend$providerApplicationBundleIdentifier
+ _objc_msgSend$providerExtensionBundleIdentifier
+ _objc_msgSend$setUpButtonWithTitle:
+ _objc_msgSend$signInEventForAutoFillOfUsername:password:serviceIdentifierType:serviceIdentifier:hostApplicationBundleIdentifier:completionHandler:
+ _objc_msgSend$ssid
+ _objc_msgSend$userFinishedVerificationCodesDeliverySetupWithShouldProceed:completionHandler:
+ _objc_msgSend$wiFiNetworksToForget
+ _symbolic $s22AuthenticationServices46ASVerificationCodesDeliverySetupDaemonProtocolP
+ _symbolic SaySo20NSURLProtectionSpaceCGSg
+ _symbolic SaySo40ASCVerificationCodesDeliverySetupAccountCG
+ _symbolic ScCySo21NSXPCListenerEndpointCSg_Sbt______pG s5ErrorP
+ _symbolic SccySb______pG s5ErrorP
+ _symbolic SccySo22WBSPasswordSignInEventCSg_____G s5NeverO
+ _symbolic So13NSXPCListenerC
+ _symbolic So15NSXPCConnectionCSgXw
+ _symbolic So15WBSSavedAccountCSg
+ _symbolic So20ASPasswordCredentialC
+ _symbolic So21NSXPCListenerEndpointCSgSb______pSgIeghgyg_ s5ErrorP
+ _symbolic So21NSXPCListenerEndpointCSg_Sbt
+ _symbolic So21NSXPCListenerEndpointCSg_____So7NSErrorCSgIeyBhyyy_ 10ObjectiveC8ObjCBoolV
+ _symbolic So29ASCredentialServiceIdentifierC
+ _symbolic So30ASCCredentialServiceIdentifierC
+ _symbolic So31ASAgentVerificationCodesServiceCSgXw
+ _symbolic So31ASAgentVerificationCodesServiceCSgXwz_Xx
+ _symbolic So40ASCVerificationCodesDeliverySetupAccountC
+ _symbolic So40ASCVerificationCodesDeliverySetupAccountCm
+ _symbolic So7NSArrayCm
+ _symbolic _____ 22AuthenticationServices35ASDeliveredVerificationCodesManagerC11SetUpReasonO
+ _symbolic _____ 22AuthenticationServices35ASDeliveredVerificationCodesManagerC21AccountRecordForSetUpV
+ _symbolic _____ 22AuthenticationServices35ASDeliveredVerificationCodesManagerC21AccountRecordForSetUpV13ContactMethodO
+ _symbolic _____ 22AuthenticationServices37VerificationCodesDeliverySetupSession33_5715F930C8FEF8ACFAE0CBB4BA5B403ELLC
+ _symbolic _____ 22AuthenticationServices45VerificationCodesDeliverySetupSessionsManager33_5715F930C8FEF8ACFAE0CBB4BA5B403ELLC
+ _symbolic _____ So20ASPasswordCredentialC22AuthenticationServicesE10SaveActionV
+ _symbolic _____ So29SFSafariCredentialStoreActionV
+ _symbolic _____ So39ASCVerificationCodesDeliverySetupReasonV
+ _symbolic _____ySay_____GG 2os21OSAllocatedUnfairLockV 22AuthenticationServices37VerificationCodesDeliverySetupSession33_5715F930C8FEF8ACFAE0CBB4BA5B403ELLC
+ _symbolic _____ySay_____G_____G s13ManagedBufferCsRi__rlE 22AuthenticationServices37VerificationCodesDeliverySetupSession33_5715F930C8FEF8ACFAE0CBB4BA5B403ELLC So16os_unfair_lock_sV
+ _symbolic _____ySo13NSXPCListenerCG 10SafariCore7WBSLazyC
+ _symbolic _____y_____G 10SafariCore7WBSLazyC 022AuthenticationServicesB021ASCHideMyEmailManagerC
+ _symbolic _____y_____G s11_SetStorageC s11AnyHashableV
+ _symbolic _____y______pG 10SafariCore7WBSLazyC 022AuthenticationServicesB029ASCredentialProvidersProviderP
+ _symbolic _____y______pG 10SafariCore7WBSLazyC 22AuthenticationServices27ASApplicationRecordResolverP
+ _symbolic _____yypG s23_ContiguousArrayStorageC
+ _type_layout_string 22AuthenticationServices35ASDeliveredVerificationCodesManagerC21AccountRecordForSetUpV
+ _type_layout_string 22AuthenticationServices35ASDeliveredVerificationCodesManagerC21AccountRecordForSetUpV13ContactMethodO
+ _type_layout_string So20ASPasswordCredentialC22AuthenticationServicesE10SaveActionV
- -[ASAuthorizationServiceViewController presentError:forService:completionHandler:]
- -[ASNavigationControllerBarView _initWithFrame:topPadding:]
- GCC_except_table37
- GCC_except_table39
- GCC_except_table40
- GCC_except_table47
- GCC_except_table56
- GCC_except_table57
- GCC_except_table65
- GCC_except_table67
- GCC_except_table69
- GCC_except_table75
- GCC_except_table81
- GCC_except_table84
- GCC_except_table92
- __CLASS_PROPERTIES_ASAuthorizationPublicKeyCredentialPRFRegistrationInput
- __OBJC_$_INSTANCE_METHODS_ASAgentVerificationCodesService(AuthenticationServices)
- __OBJC_$_INSTANCE_METHODS_ASAuthorizationController(SwiftImplementation)
- __OBJC_CLASS_PROTOCOLS_$_ASAgentVerificationCodesService(AuthenticationServices)
- ___80-[ASCredentialRequestConfirmButtonSubPane setUpButtonInPaneContext:buttonTitle:]_block_invoke
- ___84+[_ASPasswordManagerDeleteAlertConfiguration configurationForDeletingSavedAccounts:]_block_invoke
- ___block_descriptor_48_e8_32s40s_e17_v16?0"NSTimer"8l
- ___swift_closure_destructor.87Tm
- ___swift_closure_destructor.91Tm
- _objc_msgSend$_initWithFrame:topPadding:
- _objc_msgSend$credentialProviderInformationForAutoFillOfUsername:password:serviceIdentifierType:serviceIdentifier:hostApplicationBundleIdentifier:completionHandler:
- _objc_msgSend$initWithSavedAccounts:
- _objc_msgSend$requestWithCredentialIdentity:clientDataHash:userVerificationPreference:supportedAlgorithms:
- _symbolic SccySSSg_AAt_____G s5NeverO
- _symbolic ______pSg 22AuthenticationServices27ASApplicationRecordResolverP
- _symbolic ______pSg 26AuthenticationServicesCore29ASCredentialProvidersProviderP
CStrings:
+ "\n\n"
+ "%{public}s: Unexpectedly found no registration handler"
+ "-[_ASAgentCredentialExchangeListener importCredentialsWithToken:completionHandler:]_block_invoke"
+ "-[_ASConditionalRegistrationRequester credentialAuthenticationViewController:didFinishWithCredential:error:completion:]"
+ "-[_ASConditionalRegistrationRequester credentialAuthenticationViewController:didFinishWithPasskeyRegistrationCredential:error:completion:]"
+ "Are you sure you want to delete these items?"
+ "Are you sure you want to permanently delete these items?"
+ "AuthenticationServices/ASAuthorizationPublicKeyCredentialPRFExtension.swift"
+ "AuthenticationServices/ASPasswordAuthenticationPaneViewControllerConfiguration.swift"
+ "AuthenticationServices/_ASAgentAutomaticSecurityUpgradeListener.swift"
+ "Calling verification codes delivery setup completion handler."
+ "Cannot load view controller"
+ "Cannot present verification codes delivery setup: %{public}@"
+ "Connection arrived on a verification codes delivery setup endpoint with no presentation behind it"
+ "Could not look up the requesting app."
+ "Did present verification codes delivery setup UI. shouldProceed=%{bool}d"
+ "Discarding a verification codes delivery setup presentation whose client went away"
+ "Forget"
+ "Lost connection to verification codes delivery setup daemon: %{public}@"
+ "No accounts need verification codes delivery setup"
+ "No accounts need verification codes delivery setup. Proceeding without presenting UI."
+ "PMEmailSetupViewController"
+ "Passkeys are digital keys saved to your iCloud Keychain. They are backed up and sync across all of your Apple devices. You can use a passkey to sign in to apps and websites on iPhone, iPad, Mac, Apple TV, Vision\u00a0Pro, and web browsers on other platforms.\n\nPasskeys keep your accounts more secure than passwords do. They use powerful cryptography, which makes every passkey strong. Unlike passwords, malicious websites cannot trick you into giving away your passkeys.\n\nYou sign in to apps and websites with passkeys differently than you do with passwords. When prompted to sign in with a passkey, you use Face\u00a0ID, Touch\u00a0ID, Optic\u00a0ID, or your device passcode. Your biometric information and device passcode are never sent to the service you’re signing in to."
+ "Rejected an unentitled connection to the verification codes delivery setup endpoint"
+ "Rejecting %{public}s from a connection that does not own the current operation."
+ "S"
+ "There is no verification codes delivery setup in progress."
+ "Verification codes delivery setup completion handler already invoked."
+ "Verification codes delivery setup view service"
+ "View service disconnected from a verification codes delivery setup presentation"
+ "View service reported the answer. shouldProceed=%{bool,public}d"
+ "com.apple.AuthenticationServices._ASConditionalRegistrationRequester"
+ "com.apple.private.AuthenticationServicesAgent"
+ "presentAccountsToSetUp(_:reason:anchor:)"
+ "v40@?0@\"NSArray\"8Q16@\"NSString\"24@\"NSError\"32"
+ "wapi"
- "-[_ASAgentCredentialExchangeListener _setUpExporterConnection:forOperation:]_block_invoke"
- "-[_ASAgentCredentialExchangeListener continueExportWithCredentials:completionHandler:]_block_invoke_2"
- "-[_ASAgentCredentialExchangeListener importCredentialsWithToken:completionHandler:]"
- "AuthenticationServices.__ASAuthorizationPublicKeyCredentialPRFAssertionInput"
- "AuthenticationServices.__ASAuthorizationPublicKeyCredentialPRFAssertionInputValues"
- "AuthenticationServices.__ASAuthorizationPublicKeyCredentialPRFAssertionOutput"
- "AuthenticationServices.__ASAuthorizationPublicKeyCredentialPRFRegistrationInput"
- "AuthenticationServices.__ASAuthorizationPublicKeyCredentialPRFRegistrationOutput"
- "AuthenticationServices_Private.ASPasswordAuthenticationPaneViewControllerConfiguration"
- "AuthenticationServices_Private._ASAgentAutomaticSecurityUpgradeListener"
- "Passkeys are digital keys saved to your iCloud Keychain. They are backed up and sync across all of your Apple devices. You can use a passkey to sign in to apps and websites on iPhone, iPad, Mac, Apple TV, Vision\u00a0Pro, and web browsers on other platforms.\n\nPasskeys keep your accounts more secure than passwords do. They use powerful cryptography, which makes every passkey strong. Unlike passwords, malicious websites cannot trick you into giving away your passkeys.\n\nYou sign in to apps and websites with passkeys differently than you do with passwords. When prompted to sign in with a passkey, you use Face ID, Touch ID, Optic\u00a0ID, or your device passcode. Your biometric information and device passcode are never sent to the service you’re signing in to."
- "\xd1"
```
