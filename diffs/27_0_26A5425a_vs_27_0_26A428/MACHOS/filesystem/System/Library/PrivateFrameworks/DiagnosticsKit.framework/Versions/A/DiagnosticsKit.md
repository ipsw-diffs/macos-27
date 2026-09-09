## DiagnosticsKit

> `/System/Library/PrivateFrameworks/DiagnosticsKit.framework/Versions/A/DiagnosticsKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`

```diff

 104.0.0.0.0
-  __TEXT.__text: 0x2038c
+  __TEXT.__text: 0x1f5d8
   __TEXT.__objc_methlist: 0x2b0c
   __TEXT.__const: 0xd0
   __TEXT.__cstring: 0x1ba4
   __TEXT.__gcc_except_tab: 0x970
   __TEXT.__oslogstring: 0x1b2b
-  __TEXT.__unwind_info: 0x990
+  __TEXT.__unwind_info: 0xc68
   __TEXT.__objc_stubs: 0x3c40
   __TEXT.__auth_stubs: 0x520
   __TEXT.__objc_classname: 0x605
Functions:
~ +[DKComponentPredicate componentPredicateWithDomain:exactMatch:] : 108 -> 96
~ +[DKComponentPredicate componentPredicateWithType:identifier:] : 128 -> 116
~ +[DKComponentPredicate componentPredicateMatchingComponentIdentity:] : 136 -> 124
~ -[DKComponentPredicate .cxx_destruct] : 80 -> 68
~ ___copy_helper_block_e8_32w40w : 72 -> 60
~ ___destroy_helper_block_e8_32w40w : 60 -> 48
~ ___copy_helper_block_e8_32s40s48s56b : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56s : 76 -> 64
~ ___52-[DKDiagnosticXPCManager diagnosticsWithCompletion:]_block_invoke : 112 -> 100
~ ___copy_helper_block_e8_32s40b : 72 -> 60
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ -[DKDiagnosticXPCManager attributesForIdentifier:] : 436 -> 424
~ ___50-[DKDiagnosticXPCManager attributesForIdentifier:]_block_invoke : 104 -> 92
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ ___59-[DKDiagnosticXPCManager registerDiagnosticWithAttributes:]_block_invoke : 116 -> 104
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ -[DKDiagnosticXPCManager uiResponder] : 52 -> 40
~ -[DKDiagnosticXPCManager .cxx_destruct] : 100 -> 88
~ -[DKDiagnosticServiceRequest _completeWithDiagnosticResult:error:] : 216 -> 204
~ -[DKDiagnosticServiceRequest hostServicesDelegate] : 44 -> 32
~ -[DKDiagnosticServiceRequest .cxx_destruct] : 88 -> 76
~ +[DKComponentIdentity componentIdentityWithDomain:version:resources:] : 156 -> 144
~ +[DKComponentIdentity componentIdentityWithType:identifier:version:resources:] : 192 -> 180
~ -[DKComponentIdentity description] : 136 -> 124
~ -[DKComponentIdentity dictionaryRepresentation] : 308 -> 296
~ -[DKComponentIdentity encodeWithCoder:] : 292 -> 280
~ -[DKComponentIdentity .cxx_destruct] : 104 -> 92
~ +[DKAnalytics sendAnalyticsWithEvent:payloadDict:] : 152 -> 140
~ -[NSString(Localization) localizedString] : 116 -> 104
~ _DiagnosticsKitLogHandleForCategory : 100 -> 88
~ ___DiagnosticsKitLogHandleForCategory_block_invoke : 248 -> 236
~ _DKTemporaryDirectoryURL : 532 -> 520
~ -[DKDiagnosticResult description] : 236 -> 224
~ -[DKDiagnosticResult .cxx_destruct] : 104 -> 92
~ +[DKReport reportWithComponents:] : 92 -> 80
~ -[DKReport reportByMergingReport:] : 124 -> 112
~ -[DKReport arrayForJSON] : 356 -> 344
~ -[DKReport encodeWithCoder:] : 108 -> 96
~ -[DKReport description] : 136 -> 124
~ -[DKReporterRegistry generatorForComponentIdentity:] : 172 -> 160
~ -[DKReporterRegistry components] : 176 -> 164
~ -[DKReporterRegistry generators] : 176 -> 164
~ -[DKReporterRegistry .cxx_destruct] : 68 -> 56
~ +[DKReportHostContext _extensionAuxiliaryVendorProtocol] : 68 -> 56
~ ___56+[DKReportHostContext _extensionAuxiliaryVendorProtocol]_block_invoke : 164 -> 152
~ +[DKReportHostContext _extensionAuxiliaryHostProtocol] : 68 -> 56
~ ___54+[DKReportHostContext _extensionAuxiliaryHostProtocol]_block_invoke : 164 -> 152
~ __51-[DKReportHostContext startWithPayload:completion:]_block_invoke.59 : 108 -> 96
~ ___51-[DKReportHostContext startWithPayload:completion:]_block_invoke_2 : 108 -> 96
~ -[DKReportHostContext cancelWithCompletion:] : 112 -> 100
~ -[DKReportHostContext completeRemoteWithReport:completion:] : 140 -> 128
~ -[DKReportHostContext delegate] : 52 -> 40
~ +[DKDiagnosticParameters diagnosticParametersWithDictionary:] : 92 -> 80
~ -[DKDiagnosticParameters encodeWithCoder:] : 132 -> 120
~ -[DKDiagnosticParameters _decoderClasses] : 68 -> 56
~ ___41-[DKDiagnosticParameters _decoderClasses]_block_invoke : 240 -> 228
~ -[DKDiagnosticParameters .cxx_destruct] : 80 -> 68
~ -[DKDiagnosticControllerMock beginRequestWithInputsClass:predicates:specifications:parameters:completion:] : 436 -> 424
~ -[DKDiagnosticControllerMock setFinished:] : 228 -> 216
~ -[DKDiagnosticControllerMock setCancelled:] : 76 -> 64
~ -[DKDiagnosticControllerMock setProgress:] : 200 -> 188
~ -[DKDiagnosticControllerMock observeValueForKeyPath:ofObject:change:context:] : 228 -> 216
~ -[DKDiagnosticControllerMock .cxx_destruct] : 116 -> 104
~ -[DKDiagnosticController setFinished:] : 420 -> 408
~ ___38-[DKDiagnosticController setFinished:]_block_invoke : 108 -> 96
~ -[DKDiagnosticController teardownForHostInvalidationIfNeeded] : 252 -> 240
~ -[DKDiagnosticController setCancelled:] : 76 -> 64
~ -[DKDiagnosticController setProgress:] : 200 -> 188
~ -[DKDiagnosticController observeValueForKeyPath:ofObject:change:context:] : 272 -> 260
~ -[DKDiagnosticController .cxx_destruct] : 92 -> 80
~ +[DKReporterContext _extensionAuxiliaryVendorProtocol] : 68 -> 56
~ ___54+[DKReporterContext _extensionAuxiliaryVendorProtocol]_block_invoke : 164 -> 152
~ +[DKReporterContext _extensionAuxiliaryHostProtocol] : 68 -> 56
~ ___52+[DKReporterContext _extensionAuxiliaryHostProtocol]_block_invoke : 164 -> 152
~ __51-[DKReporterContext completeWithReport:completion:]_block_invoke.59 : 108 -> 96
~ ___51-[DKReporterContext completeWithReport:completion:]_block_invoke_2 : 108 -> 96
~ ___71-[DKReporterContext startRemoteReportWithComponentIdentity:completion:]_block_invoke : 64 -> 52
~ -[NSDictionary(Validations) dk_stringFromKey:maxLength:defaultValue:failed:] : 356 -> 344
~ -[NSDictionary(Validations) dk_stringFromKey:inSet:defaultValue:failed:] : 284 -> 272
~ -[NSDictionary(Validations) dk_numberFromKey:lowerBound:upperBound:defaultValue:failed:] : 620 -> 608
~ -[NSDictionary(Validations) dk_dictionaryFromKey:defaultValue:failed:] : 280 -> 268
~ -[NSDictionary(Validations) dk_dictionaryFromKey:limitedToKeys:defaultValue:failed:] : 264 -> 252
~ -[NSDictionary(Validations) dk_arrayFromKey:types:maxLength:defaultValue:failed:validator:] : 856 -> 844
~ -[NSDictionary(Validations) dk_arrayFromKey:inSet:maxLength:defaultValue:failed:] : 712 -> 700
~ -[NSDictionary(Validations) dk_dataFromKey:minLength:maxLength:defaultValue:failed:] : 540 -> 528
~ -[NSDictionary(Validations) dk_stringFromRequiredKey:maxLength:failed:] : 88 -> 76
~ -[NSDictionary(Validations) dk_stringFromRequiredKey:inSet:failed:] : 152 -> 140
~ -[NSDictionary(Validations) dk_numberFromRequiredKey:lowerBound:upperBound:failed:] : 164 -> 152
~ -[NSDictionary(Validations) dk_dictionaryFromRequiredKey:failed:] : 88 -> 76
~ -[NSDictionary(Validations) dk_dictionaryFromRequiredKey:limitedToKeys:failed:] : 260 -> 248
~ -[NSDictionary(Validations) dk_arrayFromRequiredKey:types:maxLength:failed:] : 88 -> 76
~ -[NSDictionary(Validations) dk_arrayFromRequiredKey:types:maxLength:failed:validator:] : 92 -> 80
~ -[NSDictionary(Validations) dk_arrayFromRequiredKey:inSet:maxLength:failed:] : 88 -> 76
~ -[NSDictionary(Validations) dk_dataFromRequiredKey:maxLength:failed:] : 104 -> 92
~ _OUTLINED_FUNCTION_2 : 32 -> 20
~ _OUTLINED_FUNCTION_4 : 32 -> 20
~ +[DKExtensionDiscovery discoveryUsingExtensionRegistry:services:bundleIdentifier:] : 160 -> 148
~ ___copy_helper_block_e8_32s40s48w : 76 -> 64
~ ___destroy_helper_block_e8_32s40s48w : 68 -> 56
~ __48-[DKExtensionDiscovery _beginExtensionDiscovery]_block_invoke.11 : 136 -> 124
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ ___44-[DKExtensionDiscovery performWhenComplete:]_block_invoke : 288 -> 276
~ -[DKExtensionDiscovery .cxx_destruct] : 140 -> 128
~ -[DKDiagnosticContext auditToken] : 92 -> 80
~ -[DKDiagnosticContext _helperConnnection] : 108 -> 96
~ -[DKDiagnosticContext _helperPrincipalObject] : 108 -> 96
~ -[DKDiagnosticContext testID] : 88 -> 76
~ -[DKDiagnosticContext _testName] : 88 -> 76
~ -[DKDiagnosticContext _extensionAttributes] : 128 -> 116
~ +[DKDiagnosticContext _extensionAuxiliaryVendorProtocol] : 68 -> 56
~ ___56+[DKDiagnosticContext _extensionAuxiliaryVendorProtocol]_block_invoke : 164 -> 152
~ +[DKDiagnosticContext _extensionAuxiliaryHostProtocol] : 68 -> 56
~ ___54+[DKDiagnosticContext _extensionAuxiliaryHostProtocol]_block_invoke : 164 -> 152
~ -[DKDiagnosticContext updateProgress:forTest:] : 132 -> 120
~ -[DKDiagnosticContext enableVolumeHUD:] : 72 -> 60
~ -[DKDiagnosticContext setScreenToBrightness:animate:] : 88 -> 76
~ ___60-[DKDiagnosticContext cancelRemoteDiagnosticWithCompletion:]_block_invoke : 192 -> 180
~ ___63-[DKDiagnosticContext completeWithDiagnosticResult:completion:]_block_invoke : 140 -> 128
~ ___69-[DKDiagnosticContext checkShouldShowRemoteDiagnosticViewController:]_block_invoke : 132 -> 108
~ -[DKDiagnosticContext setNeedsUpdateResponder] : 84 -> 72
~ -[DKDiagnosticContext dismissRemoteDiagnosticViewControllerWithCompletion:] : 96 -> 84
~ -[DKDiagnosticContext _getRemoteProxyAndSetUpHandlers] : 172 -> 160
~ __54-[DKDiagnosticContext _getRemoteProxyAndSetUpHandlers]_block_invoke.147 : 108 -> 96
~ ___54-[DKDiagnosticContext _getRemoteProxyAndSetUpHandlers]_block_invoke_2 : 108 -> 96
~ -[DKDiagnosticContext remoteHostCompleteWithResult:completion:] : 132 -> 120
~ -[DKDiagnosticContext remoteHostDismissViewControllerWithCompletion:] : 96 -> 84
~ -[DKDiagnosticContext remoteHostDisplayAlertWithHeader:message:buttonStrings:completion:] : 196 -> 184
~ -[DKDiagnosticContext remoteHostDisplayInstructions:style:imageLocators:title:subtitle:iconLocator:options:navigationBarActions:completion:] : 332 -> 320
~ -[DKDiagnosticContext remoteHostEnableVolumeHUD:] : 72 -> 60
~ -[DKDiagnosticContext remoteHostGetAsset:completion:] : 132 -> 120
~ -[DKDiagnosticContext remoteHostRequestPluginReloadOnFinishWithCompletion:] : 96 -> 84
~ -[DKDiagnosticContext remoteHostSetScreenToBrightness:animate:] : 88 -> 76
~ -[DKDiagnosticContext remoteHostShowUI:completion:] : 132 -> 120
~ -[DKDiagnosticContext remoteHostRequestSessionAccessoryIdentifierWithCompletion:] : 96 -> 84
~ -[DKDiagnosticContext remoteHostRequestSessionAccessoryBluetoothAddressWithCompletion:] : 96 -> 84
~ -[DKDiagnosticContext remoteHostUnpairSessionAccessoryOnTestCompletion] : 64 -> 52
~ -[DKDiagnosticContext remoteHostAllowSessionAccessoryDisconnectForDuration:] : 96 -> 84
~ -[DKDiagnosticContext remoteHostClearAllowSessionAccessoryDisconnect] : 64 -> 52
~ -[DKDiagnosticContext remoteHostUpdateProgress:forTest:] : 132 -> 120
~ -[DKDiagnosticContext remoteHostUploadAssets:completion:] : 132 -> 120
~ -[DKDiagnosticContext .cxx_destruct] : 84 -> 72
~ +[DKCanonicalVersion canonicalVersionWithString:] : 92 -> 80
~ -[DKCanonicalVersion isNewerThan:] : 508 -> 504
~ -[DKCanonicalVersion encodeWithCoder:] : 160 -> 148
~ -[DKCanonicalVersion _parseParts:] : 396 -> 384
~ -[DKCanonicalVersion .cxx_destruct] : 68 -> 56
~ -[DKResourceMonitorQueueItem .cxx_destruct] : 68 -> 56
~ -[DKResourceMonitor .cxx_destruct] : 68 -> 56
~ ___copy_helper_block_e8_32s40b48r56r : 104 -> 92
~ ___destroy_helper_block_e8_32s40s48r56r : 84 -> 72
~ ___copy_helper_block_e8_32b40r48r : 96 -> 84
~ ___destroy_helper_block_e8_32s40r48r : 76 -> 64
~ ___copy_helper_block_e8_32s40s48s56s64b : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___copy_helper_block_e8_32s40b48r : 88 -> 76
~ ___copy_helper_block_e8_32s40s48b56r : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ ___copy_helper_block_e8_32s40s48b : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ -[DKReportManager retryInterruptedRequests:andWithError:] : 1228 -> 1216
~ ___copy_helper_block_e8_32s40s48r56r64r : 112 -> 100
~ ___destroy_helper_block_e8_32s40s48r56r64r : 96 -> 84
~ -[DKReportManager getRequests:] : 512 -> 500
~ ___copy_helper_block_e8_32s40b48r56r64r72r80r : 152 -> 140
~ ___destroy_helper_block_e8_32s40s48r56r64r72r80r : 120 -> 108
~ ___copy_helper_block_e8_32s40s48s56s64b72r80r88r96r104r112r120r : 208 -> 196
~ ___destroy_helper_block_e8_32s40s48s56s64s72r80r88r96r104r112r120r : 168 -> 156
~ ___70-[DKReportManager sendRequests:serialRequests:failOnError:completion:]_block_invoke_2 : 84 -> 72
~ ___43-[DKReportManager reportersWithCompletion:]_block_invoke : 84 -> 72
~ -[DKReportManager cancelAllReports] : 88 -> 76
~ -[DKReportManager .cxx_destruct] : 140 -> 128
~ -[NSDictionary(Safe) getStringForKey:] : 120 -> 108
~ -[NSDictionary(Safe) getNumberForKey:] : 120 -> 108
~ -[NSDictionary(Safe) getDictionaryForKey:] : 120 -> 108
~ -[NSDictionary(Safe) getArrayForKey:] : 120 -> 108
~ -[NSDictionary(Safe) getKey:ofType:] : 88 -> 76
~ -[NSDictionary(Safe) alwaysGetStringForKey:default:] : 148 -> 136
~ -[NSDictionary(Safe) alwaysGetNumberForKey:default:] : 148 -> 136
~ -[NSDictionary(Safe) alwaysGetDictionaryForKey:default:] : 148 -> 136
~ -[NSDictionary(Safe) alwaysGetArrayForKey:default:] : 148 -> 136
~ -[NSDictionary(Safe) alwaysGetKey:ofType:default:] : 128 -> 116
~ -[NSDictionary(Safe) alwaysGetKey:ofType:] : 68 -> 56
~ +[DKUtilities acceptableDecoderClasses] : 68 -> 56
~ ___39+[DKUtilities acceptableDecoderClasses]_block_invoke : 284 -> 272
~ +[DKUtilities extensionAttributes] : 384 -> 372
~ +[DKUtilities inputsForDiagnostic:predicates:specifications:parameters:] : 204 -> 192
~ +[DKUtilities inputsUsingClass:diagnostic:predicates:specifications:parameters:] : 372 -> 360
~ +[DKUtilities _fetchItemProviderFromItems:withError:] : 324 -> 312
~ +[DKUtilities _sharedParsingFailedError] : 68 -> 56
~ -[DKReporterAttributes description] : 216 -> 204
~ -[DKReporterAttributes .cxx_destruct] : 116 -> 104
~ -[DKDiagnosticAttributes .cxx_destruct] : 140 -> 128
~ -[DKDiagnosticProgress description] : 160 -> 148
~ -[DKDiagnosticProgress .cxx_destruct] : 68 -> 56
~ -[DKDiagnosticRegistry adapterForIdentifier:] : 172 -> 160
~ -[DKDiagnosticRegistry diagnosticForIdentifier:] : 80 -> 68
~ -[DKDiagnosticRegistry diagnostics] : 432 -> 420
~ ___29-[DKReporterController start]_block_invoke : 80 -> 68
~ -[DKReporterController .cxx_destruct] : 68 -> 56
~ -[DKRequestContext .cxx_destruct] : 68 -> 56
~ +[DKExtensionAdapter extensionAdapterWithExtensionAttributes:] : 92 -> 80
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ -[DKExtensionAdapter description] : 156 -> 144
~ -[DKExtensionAdapter _requestForExtensionRequestIdentifier:] : 392 -> 380
~ -[DKExtensionAdapter .cxx_destruct] : 92 -> 80
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ -[DKMutableDiagnosticResult copyWithZone:] : 64 -> 52
~ -[DKMutableDiagnosticResult .cxx_destruct] : 144 -> 132
~ +[DiagnosticsKit_Subsystem initForPlugInKit] : 68 -> 56
~ +[DKAssetUploadItem assetWithData:andExtra:] : 128 -> 116
~ -[DKAssetUploadItem _decoderClasses] : 68 -> 56
~ ___36-[DKAssetUploadItem _decoderClasses]_block_invoke : 212 -> 200
~ -[DKAssetUploadItem encodeWithCoder:] : 160 -> 148
~ -[DKAssetUploadItem .cxx_destruct] : 68 -> 56
~ +[DKAssetUploadItems assetWithItems:] : 92 -> 80
~ -[DKAssetUploadItems _decoderClasses] : 68 -> 56
~ ___37-[DKAssetUploadItems _decoderClasses]_block_invoke : 240 -> 228
~ -[DKAssetUploadItems encodeWithCoder:] : 108 -> 96
~ -[DKDiagnosticHostContext _helperConnnection] : 108 -> 96
~ +[DKDiagnosticHostContext _extensionAuxiliaryVendorProtocol] : 68 -> 56
~ ___60+[DKDiagnosticHostContext _extensionAuxiliaryVendorProtocol]_block_invoke : 164 -> 152
~ +[DKDiagnosticHostContext _extensionAuxiliaryHostProtocol] : 68 -> 56
~ ___58+[DKDiagnosticHostContext _extensionAuxiliaryHostProtocol]_block_invoke : 164 -> 152
~ -[DKDiagnosticHostContext remoteHostUpdateProgress:forTest:] : 228 -> 216
~ -[DKDiagnosticHostContext remoteHostEnableVolumeHUD:] : 200 -> 188
~ -[DKDiagnosticHostContext remoteHostSetScreenToBrightness:animate:] : 220 -> 208
~ -[DKDiagnosticHostContext remoteHostCompleteWithResult:completion:] : 132 -> 120
~ -[DKDiagnosticHostContext remoteHostDismissViewControllerWithCompletion:] : 148 -> 136
~ -[DKDiagnosticHostContext remoteHostShowUI:completion:] : 228 -> 216
~ -[DKDiagnosticHostContext remoteHostRequestPluginReloadOnFinishWithCompletion:] : 200 -> 188
~ -[DKDiagnosticHostContext remoteHostRequestSessionAccessoryIdentifierWithCompletion:] : 200 -> 188
~ -[DKDiagnosticHostContext remoteHostRequestSessionAccessoryBluetoothAddressWithCompletion:] : 200 -> 188
~ -[DKDiagnosticHostContext remoteHostUnpairSessionAccessoryOnTestCompletion] : 180 -> 168
~ -[DKDiagnosticHostContext remoteHostAllowSessionAccessoryDisconnectForDuration:] : 200 -> 188
~ -[DKDiagnosticHostContext remoteHostClearAllowSessionAccessoryDisconnect] : 180 -> 168
~ -[DKDiagnosticHostContext remoteHostDisplayAlertWithHeader:message:buttonStrings:completion:] : 292 -> 280
~ -[DKDiagnosticHostContext remoteHostDisplayInstructions:style:imageLocators:title:subtitle:iconLocator:options:navigationBarActions:completion:] : 424 -> 412
~ -[DKDiagnosticHostContext delegate] : 52 -> 40
~ -[DKDiagnosticHostContext .cxx_destruct] : 80 -> 68
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ ___49-[DKDiagnosticManager diagnosticsWithCompletion:]_block_invoke_2 : 112 -> 100
~ -[DKDiagnosticManager attributesForIdentifier:] : 148 -> 136
~ -[DKDiagnosticManager adapterForIdentifier:] : 148 -> 136
~ -[DKDiagnosticManager cancelAllDiagnostics] : 72 -> 60
~ -[DKDiagnosticManager updateProgress:forTest:] : 212 -> 200
~ -[DKDiagnosticManager getAsset:completion:] : 184 -> 172
~ -[DKDiagnosticManager uploadAssets:completion:] : 184 -> 172
~ -[DKDiagnosticManager requestSessionAccessoryIdentifierWithCompletion:] : 184 -> 172
~ -[DKDiagnosticManager requestSessionAccessoryBluetoothAddressWithCompletion:] : 184 -> 172
~ -[DKDiagnosticManager unpairSessionAccessoryOnTestCompletion] : 164 -> 152
~ -[DKDiagnosticManager allowSessionAccessoryDisconnectForDuration:] : 184 -> 172
~ -[DKDiagnosticManager clearAllowSessionAccessoryDisconnect] : 164 -> 152
~ -[DKDiagnosticManager displayAlertWithHeader:message:buttonStrings:completion:] : 276 -> 264
~ -[DKDiagnosticManager displayInstructions:style:imageLocators:title:subtitle:iconLocator:options:navigationBarActions:completion:] : 412 -> 400
~ -[DKDiagnosticManager progressResponder] : 44 -> 32
~ -[DKDiagnosticManager assetResponder] : 44 -> 32
~ -[DKDiagnosticManager accessoryResponder] : 44 -> 32
~ -[DKDiagnosticManager userAlertResponder] : 44 -> 32
~ -[DKDiagnosticManager .cxx_destruct] : 136 -> 124
~ +[DKReportingConcurrentRequest concurrentRequestWithGenerator:] : 92 -> 80
~ -[DKReportingConcurrentRequest .cxx_destruct] : 68 -> 56
~ +[DKReportingConcurrentRequestGroup initWithResources:] : 124 -> 112
~ -[DKReportingConcurrentRequestGroup .cxx_destruct] : 80 -> 68
~ +[DKReportPlanner plannerWithReportGeneratorRegistry:] : 96 -> 84
~ -[DKReportPlanner requestGroupsForPredicateManifest:] : 716 -> 704
~ -[DKReportPlanner _resolveComponentIdentityManifest:] : 660 -> 648
~ +[DKExtensionRequest requestWithExtensionAttributes:] : 96 -> 84
~ -[DKExtensionRequest cancelExtensionRequest] : 168 -> 156
~ -[DKExtensionRequest description] : 236 -> 224
~ -[DKExtensionRequest _cancelTimedOutWithInfo:] : 124 -> 112
~ ___46-[DKExtensionRequest _finishWithResult:error:]_block_invoke : 120 -> 108
~ -[DKExtensionRequest delegate] : 44 -> 32
~ -[DKExtensionRequest hostServicesDelegate] : 44 -> 32
~ -[DKExtensionRequest .cxx_destruct] : 168 -> 156
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ -[DKDiagnosticAllowList .cxx_destruct] : 68 -> 56
~ -[NSObject(Serialization) dropNonSerializableDataWithError:] : 1148 -> 1136
~ +[DKEnterSandbox _bundleId] : 88 -> 76
~ +[DKEnterSandbox _processName] : 88 -> 76
~ +[DKEnterSandbox _getHomeDirectory] : 96 -> 84
~ _OUTLINED_FUNCTION_2 : 28 -> 16
~ -[DKDiagnosticService resume] : 64 -> 52
~ ___copy_helper_block_e8_32w40w48w : 84 -> 72
~ ___destroy_helper_block_e8_32w40w48w : 68 -> 56
~ -[DKDiagnosticService .cxx_destruct] : 80 -> 68
~ +[DKComponent componentWithIdentity:attributes:] : 128 -> 116
~ -[DKComponent dictionaryForJSON] : 352 -> 340
~ -[DKComponent encodeWithCoder:] : 160 -> 148
~ -[DKComponent description] : 136 -> 124
~ -[DKComponent .cxx_destruct] : 68 -> 56
```
