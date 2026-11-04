## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/A/AppleMediaServices`

```diff

-10.1.18.0.0
-  __TEXT.__text: 0x8e7ab4
+10.2.12.1.1
+  __TEXT.__text: 0x8f8978
   __TEXT.__lazy_helpers: 0x2e98
-  __TEXT.__objc_methlist: 0x247fc
-  __TEXT.__const: 0xbb0b0
-  __TEXT.__dlopen_cstrs: 0x834
-  __TEXT.__cstring: 0x2cd80
-  __TEXT.__swift5_typeref: 0x7ab9
-  __TEXT.__swift5_reflstr: 0x430e
-  __TEXT.__swift5_assocty: 0xfc0
-  __TEXT.__constg_swiftt: 0x5dcc
-  __TEXT.__swift5_builtin: 0x3e8
-  __TEXT.__swift5_fieldmd: 0x5aa4
-  __TEXT.__swift5_proto: 0x126c
-  __TEXT.__swift5_types: 0x724
-  __TEXT.__swift_as_entry: 0x8d8
-  __TEXT.__swift_as_ret: 0xa64
-  __TEXT.__swift_as_cont: 0x1400
-  __TEXT.__swift5_capture: 0x41ec
+  __TEXT.__objc_methlist: 0x2526c
+  __TEXT.__const: 0xbb570
+  __TEXT.__dlopen_cstrs: 0x8f8
+  __TEXT.__cstring: 0x2d7da
+  __TEXT.__swift5_typeref: 0x7ccb
+  __TEXT.__swift5_reflstr: 0x452e
+  __TEXT.__swift5_assocty: 0xfd8
+  __TEXT.__constg_swiftt: 0x5f04
+  __TEXT.__swift5_builtin: 0x3fc
+  __TEXT.__swift5_fieldmd: 0x5ce0
+  __TEXT.__swift5_proto: 0x12a4
+  __TEXT.__swift5_types: 0x750
+  __TEXT.__swift_as_entry: 0x8dc
+  __TEXT.__swift_as_ret: 0xa6c
+  __TEXT.__swift_as_cont: 0x1410
+  __TEXT.__swift5_capture: 0x42c0
   __TEXT.__swift5_mpenum: 0x9c
   __TEXT.__swift5_protos: 0x120
-  __TEXT.__oslogstring: 0x317bf
-  __TEXT.__gcc_except_tab: 0x53a0
+  __TEXT.__oslogstring: 0x31dd3
+  __TEXT.__gcc_except_tab: 0x54d4
   __TEXT.__ustring: 0x262
-  __TEXT.__unwind_info: 0x174a8
-  __TEXT.__eh_frame: 0x18634
+  __TEXT.__unwind_info: 0x16f08
+  __TEXT.__eh_frame: 0x1887c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x5da8
-  __DATA_CONST.__objc_classlist: 0x1600
+  __DATA_CONST.__const: 0x5e38
+  __DATA_CONST.__objc_classlist: 0x1640
   __DATA_CONST.__objc_catlist: 0xe8
-  __DATA_CONST.__objc_protolist: 0x4b0
+  __DATA_CONST.__objc_protolist: 0x4d0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xff70
-  __DATA_CONST.__objc_protorefs: 0x278
-  __DATA_CONST.__objc_superrefs: 0xcf8
+  __DATA_CONST.__objc_selrefs: 0x10398
+  __DATA_CONST.__objc_protorefs: 0x280
+  __DATA_CONST.__objc_superrefs: 0xd10
   __DATA_CONST.__objc_arraydata: 0x498
-  __DATA_CONST.__got: 0x1a48
-  __AUTH_CONST.__const: 0x45830
-  __AUTH_CONST.__cfstring: 0x237a0
-  __AUTH_CONST.__objc_const: 0x400f0
+  __DATA_CONST.__got: 0x1a88
+  __AUTH_CONST.__const: 0x46580
+  __AUTH_CONST.__cfstring: 0x23c60
+  __AUTH_CONST.__objc_const: 0x40ec8
   __AUTH_CONST.__lazy_load_got: 0x460
   __AUTH_CONST.__objc_intobj: 0xc60
   __AUTH_CONST.__objc_arrayobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0x2460
-  __AUTH.__objc_data: 0x9ae8
-  __AUTH.__data: 0x2cb0
-  __DATA.__objc_ivar: 0x1a64
-  __DATA.__data: 0x7e70
-  __DATA.__bss: 0x1c958
+  __AUTH_CONST.__auth_got: 0x2480
+  __AUTH.__objc_data: 0x9da8
+  __AUTH.__data: 0x2d20
+  __DATA.__objc_ivar: 0x1ab8
+  __DATA.__data: 0x8070
+  __DATA.__bss: 0x1d088
   __DATA.__common: 0x1520
-  __DATA_DIRTY.__objc_ivar: 0x6e4
+  __DATA_DIRTY.__objc_ivar: 0x714
   __DATA_DIRTY.__objc_data: 0x6048
-  __DATA_DIRTY.__data: 0x31fc
-  __DATA_DIRTY.__bss: 0x63b0
+  __DATA_DIRTY.__data: 0x320c
+  __DATA_DIRTY.__bss: 0x63f0
   __DATA_DIRTY.__common: 0x90
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 30067
-  Symbols:   32225
-  CStrings:  8978
+  Functions: 30485
+  Symbols:   32693
+  CStrings:  9077
 
Symbols:
+ +[AMSHTTPArchive _flushPendingEntriesWithTracker:archiveService:timeout:]
+ +[AMSHTTPArchive _recordTaskInfo:responseData:route:tracker:]
+ +[AMSHTTPArchive _sharedRecordingTracker]
+ +[AMSHTTPArchive flushPendingEntriesPromiseWithTimeout:]
+ +[AMSHTTPArchiveService _sharedConnectionQueue]
+ +[AMSHTTPArchiveService _sharedService]
+ +[AMSPaymentSheetTask _spkPaymentSheetDisabledBagKey]
+ +[AMSPurchase _identifierFromUUID:]
+ +[AMSRequestDecorator sharedDecorator]
+ +[AMSSecureThreeDomainInterruptionRequestHandler bodyByInjectingSessionId:intoRequest:]
+ +[AMSSecureThreeDomainInterruptionRequestHandler formURLEncodedQueryFromItems:]
+ +[AMSSecureThreeDomainInterruptionRequestHandler percentEncodedFormComponent:]
+ +[AMSSecureThreeDomainInterruptionRequestHandler updateBodyOnAction:withSessionId:originatingTaskInfo:]
+ +[AMSStreamHTTPArchiveEntryController _maxBufferSizeForMemoryPressureStatus:]
+ +[AMSStreamHTTPArchiveEntryController ams_flushAllEntriesToDisk]
+ -[AMSAccountCachedServerDataFields ageSignalConflict]
+ -[AMSAccountCachedServerDataFields setAgeSignalConflict:]
+ -[AMSAuthenticateOptions purchaseIdentifier]
+ -[AMSAuthenticateOptions setPurchaseIdentifier:]
+ -[AMSHARRecordingTracker .cxx_destruct]
+ -[AMSHARRecordingTracker hasRecorded]
+ -[AMSHARRecordingTracker init]
+ -[AMSHARRecordingTracker notifyWhenIdleOnQueue:block:]
+ -[AMSHARRecordingTracker trackedRecordingBlock:]
+ -[AMSHTTPArchiveService flushPromise]
+ -[AMSHTTPArchiveService initWithRecordingConnection:]
+ -[AMSHTTPArchiveService lostConnection]
+ -[AMSHTTPArchiveService setLostConnection:]
+ -[AMSPaymentRequest ams_tagRequestWithPurchaseIdentifier:]
+ -[AMSPaymentRequest purchaseIdentifier]
+ -[AMSPaymentRequest setPurchaseIdentifier:]
+ -[AMSPaymentSheetPerformanceMetrics purchaseUUID]
+ -[AMSPaymentSheetPerformanceMetrics setPurchaseUUID:]
+ -[AMSPaymentSheetRequest purchaseIdentifier]
+ -[AMSPaymentSheetRequest setPurchaseIdentifier:]
+ -[AMSPaymentSheetRequest(PassKit) _requestForExpandableInfoURL:requestType:bag:session:error:]
+ -[AMSPaymentSheetTask _adoptRendererEndpoint:error:source:logKey:]
+ -[AMSPaymentSheetTask _computeShouldUseSPKPaymentSheet]
+ -[AMSPaymentSheetTask _dismissPaymentSheet:]
+ -[AMSPaymentSheetTask _isSPKPaymentSheetFeatureFlagEnabled]
+ -[AMSPaymentSheetTask _performViewServiceOrInProcessTask]
+ -[AMSPaymentSheetTask _performWithRendererEndpoint]
+ -[AMSPaymentSheetTask _promiseIfCancelledBeforeStart]
+ -[AMSPaymentSheetTask _resolveRendererEndpointFromPresentingProcess]
+ -[AMSPaymentSheetTask _resolveRendererEndpoint]
+ -[AMSPaymentSheetTask _shouldUseSPKPaymentSheet]
+ -[AMSPaymentSheetTask cancelRequested]
+ -[AMSPaymentSheetTask paymentSheet:didEncounterAuthorizationEvent:]
+ -[AMSPaymentSheetTask paymentSheetDidActivate:]
+ -[AMSPaymentSheetTask paymentSheet]
+ -[AMSPaymentSheetTask presentationSceneBundleIdentifierForPaymentSheet:]
+ -[AMSPaymentSheetTask presentationSceneIdentifierForPaymentSheet:]
+ -[AMSPaymentSheetTask rendererEndpoint]
+ -[AMSPaymentSheetTask servicesPaymentRendererEndpoint]
+ -[AMSPaymentSheetTask setCancelRequested:]
+ -[AMSPaymentSheetTask setPaymentSheet:]
+ -[AMSPaymentSheetTask setRendererEndpoint:]
+ -[AMSPaymentSheetTask setUsingSPKPaymentSheet:]
+ -[AMSPaymentSheetTask usingSPKPaymentSheet]
+ -[AMSPurchase purchaseUUID]
+ -[AMSPurchase servicesPaymentViewServiceListener]
+ -[AMSPurchase setServicesPaymentViewServiceListener:]
+ -[AMSPurchaseQueueConfiguration excludesServerPayloadFromErrors]
+ -[AMSPurchaseQueueConfiguration setExcludesServerPayloadFromErrors:]
+ -[AMSPurchaseTask _promiseExcludingServerPayload:]
+ -[AMSPurchaseTask endTime]
+ -[AMSPurchaseTask excludesServerPayloadFromErrors]
+ -[AMSPurchaseTask setEndTime:]
+ -[AMSPurchaseTask setExcludesServerPayloadFromErrors:]
+ -[AMSPurchaseTask setStartTime:]
+ -[AMSPurchaseTask startTime]
+ -[AMSRequestDecorator addAbsintheHeadersToRequest:buyParams:bag:shouldUseRemoteSigningIfAvailable:]
+ -[AMSRequestDecorator addAcceptEncodingHeaderToRequest:]
+ -[AMSRequestDecorator addAcceptLanguageHeaderToRequest:]
+ -[AMSRequestDecorator addAnisetteHeadersToRequest:account:type:bag:]
+ -[AMSRequestDecorator addAuthKitHeadersToRequest:]
+ -[AMSRequestDecorator addBiometricsHeadersToRequest:forAccount:options:]
+ -[AMSRequestDecorator addCacheBusterParameterToRequest:preservingQueryEncoding:]
+ -[AMSRequestDecorator addCachePolicyHeaderToRequest:]
+ -[AMSRequestDecorator addClientIdentifierHeaderToRequest:forClient:]
+ -[AMSRequestDecorator addClientVersionsToRequest:forClient:]
+ -[AMSRequestDecorator addConnectionTypeHeaderToRequest:]
+ -[AMSRequestDecorator addCookiesToRequest:forAccount:clientInfo:bag:cleanupGlobalCookies:excludeAccountIdentifierCookies:]
+ -[AMSRequestDecorator addFPDIHeadersToRequest:buyParams:bag:retryCount:fairPlayDeviceIdentity:fpdiNetworkProvider:]
+ -[AMSRequestDecorator addForwardedForHeaderToRequest:]
+ -[AMSRequestDecorator addGSTokenToRequest:forAccount:identifier:]
+ -[AMSRequestDecorator addGUIDHeaderToRequest:matchingURL:bag:]
+ -[AMSRequestDecorator addGUIDParameterToRequest:matchingURL:bag:preservingQueryEncoding:]
+ -[AMSRequestDecorator addGroupDSIDsToRequest:primaryAccount:groupAccounts:]
+ -[AMSRequestDecorator addIdentifierHeadersToRequest:forAccount:]
+ -[AMSRequestDecorator addIssuingProcessHeaderToRequest:]
+ -[AMSRequestDecorator addMMeClientInfoAndDeviceHeadersToRequest:]
+ -[AMSRequestDecorator addMescalHeaderToRequest:type:bag:logKey:]
+ -[AMSRequestDecorator addPaymentHardwareStatusToRequest:bag:]
+ -[AMSRequestDecorator addPrimaryiCloudIdentifierHeaderToRequest:]
+ -[AMSRequestDecorator addProductTypeHeaderToRequest:]
+ -[AMSRequestDecorator addRequestingProcessHeaderToRequest:forClient:]
+ -[AMSRequestDecorator addStorefrontHeaderToRequest:forAccount:mediaType:bag:]
+ -[AMSRequestDecorator addTimezoneOffsetHeaderToRequest:]
+ -[AMSRequestDecorator addTreatmentHeadersToRequest:forTreatmentNamespace:bag:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:]
+ -[AMSRequestDecorator addUserAgentHeaderToRequest:forClient:]
+ -[AMSRequestDecorator compressBodyInRequest:logUUID:loggingFor:]
+ -[AMSRequestDecorator disableCookieHandlingInRequest:]
+ -[AMSRequestDecorator encodeBodyParametersInRequest:parameters:encoding:error:]
+ -[AMSRequestDecorator shouldAddPaymentHardwareStatusForRequest:bag:]
+ -[AMSRequestDecorator sortQueryParametersInRequest:]
+ -[AMSSecureThreeDomainInterruptionTask .cxx_destruct]
+ -[AMSSecureThreeDomainInterruptionTask _makeInterruptionWithSceneIdentifier:]
+ -[AMSSecureThreeDomainInterruptionTask _presentInterruption:]
+ -[AMSSecureThreeDomainInterruptionTask _presentInterruptionWithViewServiceEndpoint:]
+ -[AMSSecureThreeDomainInterruptionTask _resolvePresentationTargetAndPresent]
+ -[AMSSecureThreeDomainInterruptionTask activeInterruption]
+ -[AMSSecureThreeDomainInterruptionTask challengeResponse]
+ -[AMSSecureThreeDomainInterruptionTask customData]
+ -[AMSSecureThreeDomainInterruptionTask hostAppAuditTokenData]
+ -[AMSSecureThreeDomainInterruptionTask initWithSceneIdentifier:]
+ -[AMSSecureThreeDomainInterruptionTask initWithURLTaskInfo:]
+ -[AMSSecureThreeDomainInterruptionTask perform]
+ -[AMSSecureThreeDomainInterruptionTask sceneIdentifier]
+ -[AMSSecureThreeDomainInterruptionTask setActiveInterruption:]
+ -[AMSSecureThreeDomainInterruptionTask setChallengeResponse:]
+ -[AMSSecureThreeDomainInterruptionTask setCustomData:]
+ -[AMSSecureThreeDomainInterruptionTask setHostAppAuditTokenData:]
+ -[AMSSecureThreeDomainInterruptionTask setSceneIdentifier:]
+ -[AMSSecureThreeDomainInterruptionTask setUrlTaskInfo:]
+ -[AMSSecureThreeDomainInterruptionTask setViewServiceEndpoint:]
+ -[AMSSecureThreeDomainInterruptionTask urlTaskInfo]
+ -[AMSSecureThreeDomainInterruptionTask viewServiceEndpoint]
+ -[AMSSubscriptionInviteTask .cxx_destruct]
+ -[AMSSubscriptionInviteTask _present]
+ -[AMSSubscriptionInviteTask bag]
+ -[AMSSubscriptionInviteTask cancel]
+ -[AMSSubscriptionInviteTask initWithRequest:sceneIdentifier:]
+ -[AMSSubscriptionInviteTask initWithSubscriptionInfo:sceneIdentifier:]
+ -[AMSSubscriptionInviteTask perform]
+ -[AMSSubscriptionInviteTask request]
+ -[AMSSubscriptionInviteTask sceneIdentifier]
+ -[AMSSubscriptionInviteTask setBag:]
+ -[AMSTreatmentStore metricsReporter]
+ -[AMSTreatmentStore setMetricsReporter:]
+ -[AMSTreatmentStoreMetricsReporter reportTreatmentStoreFailureEvent:]
+ -[AMSURLRequestEncoder _addCookiesToRequest:account:decorator:]
+ -[AMSURLRequestEncoder currentProcess]
+ -[AMSURLRequestEncoder decorator]
+ -[AMSURLRequestEncoder purchaseIdentifier]
+ -[AMSURLRequestEncoder setCurrentProcess:]
+ -[AMSURLRequestEncoder setDecorator:]
+ -[AMSURLRequestEncoder setPurchaseIdentifier:]
+ -[AMSURLRequestProperties purchaseIdentifier]
+ -[AMSURLRequestProperties setPurchaseIdentifier:]
+ -[NSError(AppleMediaServices_Project) ams_errorByRemovingUserInfoKeys:]
+ GCC_except_table117
+ GCC_except_table120
+ GCC_except_table51
+ GCC_except_table58
+ GCC_except_table66
+ GCC_except_table70
+ GCC_except_table88
+ _AMSBagKeySPKPaymentSheetMacOSDisabled
+ _AMSBagKeySystemEngagementSceneRemoteAlertEnabled
+ _AMSDefaultsSamplingIdentifierMetricsLogging
+ _AMSErrorByRemovingUserInfoKeys
+ _AMSFinanceDialogMetricsKeyPurchaseId
+ _AMSHumanReadableDescriptionForPaymentSheetCancellationType
+ _AMSServicesPaymentViewServiceViewController
+ _OBJC_CLASS_$_AMSFinanceSubscriptionInviteResponse
+ _OBJC_CLASS_$_AMSHARRecordingTracker
+ _OBJC_CLASS_$_AMSRequestDecorator
+ _OBJC_CLASS_$_AMSSecureThreeDomainInterruptionRequestHandler
+ _OBJC_CLASS_$_AMSSecureThreeDomainInterruptionTask
+ _OBJC_CLASS_$_AMSSubscriptionInviteTask
+ _OBJC_CLASS_$_AMSTreatmentStoreMetricsReporter
+ _OBJC_CLASS_$_AMSUnderlyingErrorTreeBridge
+ _OBJC_CLASS_$_NSMutableCharacterSet
+ _OBJC_CLASS_$_NSPredicate
+ _OBJC_IVAR_$_AMSAccountCachedServerDataFields._ageSignalConflict
+ _OBJC_IVAR_$_AMSAuthenticateOptions._purchaseIdentifier
+ _OBJC_IVAR_$_AMSHARRecordingTracker._group
+ _OBJC_IVAR_$_AMSHARRecordingTracker._hasRecorded
+ _OBJC_IVAR_$_AMSHTTPArchiveService._lostConnection
+ _OBJC_IVAR_$_AMSPaymentRequest._purchaseIdentifier
+ _OBJC_IVAR_$_AMSPaymentSheetPerformanceMetrics._purchaseUUID
+ _OBJC_IVAR_$_AMSPaymentSheetRequest._purchaseIdentifier
+ _OBJC_IVAR_$_AMSPaymentSheetTask._cancelRequested
+ _OBJC_IVAR_$_AMSPaymentSheetTask._usingSPKPaymentSheet
+ _OBJC_IVAR_$_AMSPurchase._purchaseUUID
+ _OBJC_IVAR_$_AMSPurchase._servicesPaymentViewServiceListener
+ _OBJC_IVAR_$_AMSPurchaseQueueConfiguration._excludesServerPayloadFromErrors
+ _OBJC_IVAR_$_AMSPurchaseTask._endTime
+ _OBJC_IVAR_$_AMSPurchaseTask._excludesServerPayloadFromErrors
+ _OBJC_IVAR_$_AMSPurchaseTask._startTime
+ _OBJC_IVAR_$_AMSTreatmentStore._metricsReporter
+ _OBJC_IVAR_$_AMSURLRequestEncoder._currentProcess
+ _OBJC_IVAR_$_AMSURLRequestEncoder._decorator
+ _OBJC_IVAR_$_AMSURLRequestEncoder._purchaseIdentifier
+ _OBJC_IVAR_$_AMSURLRequestProperties._purchaseIdentifier
+ _OBJC_METACLASS_$_AMSFinanceSubscriptionInviteResponse
+ _OBJC_METACLASS_$_AMSHARRecordingTracker
+ _OBJC_METACLASS_$_AMSRequestDecorator
+ _OBJC_METACLASS_$_AMSSecureThreeDomainInterruptionRequestHandler
+ _OBJC_METACLASS_$_AMSSecureThreeDomainInterruptionTask
+ _OBJC_METACLASS_$_AMSSubscriptionInviteTask
+ _OBJC_METACLASS_$_AMSTreatmentStoreMetricsReporter
+ _OBJC_METACLASS_$_AMSUnderlyingErrorTreeBridge
+ __CLASS_METHODS_AMSFinanceSubscriptionInviteResponse
+ __CLASS_METHODS_AMSUnderlyingErrorTreeBridge
+ __DATA_AMSFinanceSubscriptionInviteResponse
+ __DATA_AMSUnderlyingErrorTreeBridge
+ __INSTANCE_METHODS_AMSFinanceSubscriptionInviteResponse
+ __INSTANCE_METHODS_AMSUnderlyingErrorTreeBridge
+ __IVARS_AMSFinanceSubscriptionInviteResponse
+ __METACLASS_DATA_AMSFinanceSubscriptionInviteResponse
+ __METACLASS_DATA_AMSUnderlyingErrorTreeBridge
+ __OBJC_$_CATEGORY_NSDate_$_AppleMediaServices
+ __OBJC_$_CLASS_METHODS_AMSRequestDecorator
+ __OBJC_$_CLASS_METHODS_AMSSecureThreeDomainInterruptionRequestHandler
+ __OBJC_$_CLASS_METHODS_NSDate(AppleMediaServices|AMSFormattingUtilities)
+ __OBJC_$_CLASS_PROP_LIST_AMSRequestDecorator
+ __OBJC_$_INSTANCE_METHODS_AMSHARRecordingTracker
+ __OBJC_$_INSTANCE_METHODS_AMSRequestDecorator
+ __OBJC_$_INSTANCE_METHODS_AMSSecureThreeDomainInterruptionTask
+ __OBJC_$_INSTANCE_METHODS_AMSSubscriptionInviteTask(AppleMediaServices)
+ __OBJC_$_INSTANCE_METHODS_AMSTreatmentStoreMetricsReporter
+ __OBJC_$_INSTANCE_METHODS_NSDate(AppleMediaServices|AMSFormattingUtilities)
+ __OBJC_$_INSTANCE_VARIABLES_AMSHARRecordingTracker
+ __OBJC_$_INSTANCE_VARIABLES_AMSSecureThreeDomainInterruptionTask
+ __OBJC_$_INSTANCE_VARIABLES_AMSSubscriptionInviteTask
+ __OBJC_$_PROP_LIST_AMSHARRecordingTracker
+ __OBJC_$_PROP_LIST_AMSRequestDecorator
+ __OBJC_$_PROP_LIST_AMSSecureThreeDomainInterruptionTask
+ __OBJC_$_PROP_LIST_AMSTreatmentStoreMetricsReporter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AMSRequestDecorating
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AMSTreatmentStoreMetricsReporting
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_AMSPaymentViewTaskProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SPKPaymentSheetDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AMSRequestDecorating
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AMSTreatmentStoreMetricsReporting
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SPKPaymentSheetDelegate
+ __OBJC_$_PROTOCOL_REFS_AMSRequestDecorating
+ __OBJC_$_PROTOCOL_REFS_AMSTreatmentStoreMetricsReporting
+ __OBJC_$_PROTOCOL_REFS_SPKPaymentSheetDelegate
+ __OBJC_CLASS_PROTOCOLS_$_AMSRequestDecorator
+ __OBJC_CLASS_PROTOCOLS_$_AMSTreatmentStoreMetricsReporter
+ __OBJC_CLASS_RO_$_AMSHARRecordingTracker
+ __OBJC_CLASS_RO_$_AMSRequestDecorator
+ __OBJC_CLASS_RO_$_AMSSecureThreeDomainInterruptionRequestHandler
+ __OBJC_CLASS_RO_$_AMSSecureThreeDomainInterruptionTask
+ __OBJC_CLASS_RO_$_AMSSubscriptionInviteTask
+ __OBJC_CLASS_RO_$_AMSTreatmentStoreMetricsReporter
+ __OBJC_LABEL_PROTOCOL_$_AMSRequestDecorating
+ __OBJC_LABEL_PROTOCOL_$_AMSTreatmentStoreMetricsReporting
+ __OBJC_LABEL_PROTOCOL_$_SPKPaymentSheetDelegate
+ __OBJC_METACLASS_RO_$_AMSHARRecordingTracker
+ __OBJC_METACLASS_RO_$_AMSRequestDecorator
+ __OBJC_METACLASS_RO_$_AMSSecureThreeDomainInterruptionRequestHandler
+ __OBJC_METACLASS_RO_$_AMSSecureThreeDomainInterruptionTask
+ __OBJC_METACLASS_RO_$_AMSSubscriptionInviteTask
+ __OBJC_METACLASS_RO_$_AMSTreatmentStoreMetricsReporter
+ __OBJC_PROTOCOL_$_AMSRequestDecorating
+ __OBJC_PROTOCOL_$_AMSTreatmentStoreMetricsReporting
+ __OBJC_PROTOCOL_$_SPKPaymentSheetDelegate
+ __PROTOCOLS_AMSFinanceSubscriptionInviteResponse
+ __PROTOCOL_AMSSubscriptionInvitePresenting
+ __PROTOCOL_INSTANCE_METHODS_AMSSubscriptionInvitePresenting
+ __PROTOCOL_METHOD_TYPES_AMSSubscriptionInvitePresenting
+ __PROTOCOL_PROTOCOLS_AMSSubscriptionInvitePresenting
+ ___30-[AMSPaymentSheetTask perform]_block_invoke
+ ___36-[AMSSubscriptionInviteTask perform]_block_invoke
+ ___37-[AMSHTTPArchiveService flushPromise]_block_invoke
+ ___37-[AMSHTTPArchiveService flushPromise]_block_invoke_2
+ ___37-[AMSHTTPArchiveService flushPromise]_block_invoke_3
+ ___38+[AMSRequestDecorator sharedDecorator]_block_invoke
+ ___39+[AMSHTTPArchiveService _sharedService]_block_invoke
+ ___41+[AMSHTTPArchive _sharedRecordingTracker]_block_invoke
+ ___44-[AMSPaymentSheetTask _dismissPaymentSheet:]_block_invoke
+ ___44-[AMSPaymentSheetTask _dismissPaymentSheet:]_block_invoke_2
+ ___47+[AMSHTTPArchiveService _sharedConnectionQueue]_block_invoke
+ ___47-[AMSPaymentSheetTask _resolveRendererEndpoint]_block_invoke
+ ___47-[AMSSecureThreeDomainInterruptionTask perform]_block_invoke
+ ___48-[AMSHARRecordingTracker trackedRecordingBlock:]_block_invoke
+ ___48-[AMSPaymentSheetTask _shouldUseSPKPaymentSheet]_block_invoke
+ ___49-[AMSPaymentSheetTask _prewarmPaymentUIFramework]_block_invoke_3
+ ___49-[AMSPaymentSheetTask _prewarmPaymentUIFramework]_block_invoke_4
+ ___50-[AMSPurchaseTask _promiseExcludingServerPayload:]_block_invoke
+ ___51-[AMSPaymentSheetTask _performWithRendererEndpoint]_block_invoke
+ ___54-[AMSHARRecordingTracker notifyWhenIdleOnQueue:block:]_block_invoke
+ ___55-[AMSPaymentSheetTask _computeShouldUseSPKPaymentSheet]_block_invoke
+ ___56+[AMSHTTPArchive flushPendingEntriesPromiseWithTimeout:]_block_invoke
+ ___61+[AMSHTTPArchive _recordTaskInfo:responseData:route:tracker:]_block_invoke
+ ___61-[AMSSecureThreeDomainInterruptionTask _presentInterruption:]_block_invoke
+ ___62-[AMSPaymentSheetTask _presentPaymentSheetWithPaymentRequest:]_block_invoke_4
+ ___63-[AMSURLRequestEncoder _addCookiesToRequest:account:decorator:]_block_invoke
+ ___68-[AMSPaymentSheetTask _resolveRendererEndpointFromPresentingProcess]_block_invoke
+ ___68-[AMSPaymentSheetTask _resolveRendererEndpointFromPresentingProcess]_block_invoke_2
+ ___73+[AMSHTTPArchive _flushPendingEntriesWithTracker:archiveService:timeout:]_block_invoke
+ ___73+[AMSHTTPArchive _flushPendingEntriesWithTracker:archiveService:timeout:]_block_invoke_2
+ ___78+[AMSSecureThreeDomainInterruptionRequestHandler percentEncodedFormComponent:]_block_invoke
+ ___87+[AMSSecureThreeDomainInterruptionRequestHandler bodyByInjectingSessionId:intoRequest:]_block_invoke
+ ___AMSExcludedPurchaseErrorKeys_block_invoke
+ ___AMSURLRequestEncoderIsAppStoreProcess_block_invoke
+ ___ServicesPaymentKitLibraryCore_block_invoke
+ ___block_descriptor_32_e28_"AMSHTTPArchiveService"8?0l
+ ___block_descriptor_40_e8_32s_e16_v16?0"NSData"8l
+ ___block_descriptor_40_e8_32s_e41_B24?0"NSURLQueryItem"8"NSDictionary"16l
+ ___block_descriptor_40_e8_32s_e44_"AMSPromise"24?0"AMSBoolean"8"NSError"16l
+ ___block_descriptor_40_e8_32w_e59_v24?0"PKPayment"8?<v?"PKPaymentAuthorizationResult">16l
+ ___block_descriptor_41_e8_32s_e5_v8?0l
+ ___block_descriptor_48_e8_32w40w_e5_v8?0l
+ ___block_descriptor_49_e8_32s40s_e20_v20?0B8"NSError"12l
+ ___block_descriptor_56_e8_32s40bs_e20_v20?0B8"NSError"12l
+ ___block_descriptor_56_e8_32s40s48s_e32_v24?0"AMSBoolean"8"NSError"16l
+ ___block_descriptor_56_e8_32s40s48w_e30_v24?0"NSNumber"8"NSError"16l
+ ___block_descriptor_56_e8_32s40s48w_e43_v24?0"NSXPCListenerEndpoint"8"NSError"16l
+ ___block_descriptor_64_e8_32s40s48s56r_e30_"AMSPromise"16?0"NSNumber"8l
+ ___block_descriptor_64_e8_32s40s48s56r_e34_"AMSPromise"16?0"NSDictionary"8l
+ ___block_descriptor_64_e8_32s40s48s56s_e38_"AMSBinaryPromise"20?0B8"NSError"12l
+ ___block_descriptor_64_e8_32s40s48s56s_e44_"AMSPromise"24?0"AMSBoolean"8"NSError"16l
+ ___block_descriptor_72_e8_32s40s48s56r64r_e30_"AMSPromise"16?0"NSNumber"8l
+ ___block_descriptor_80_e8_32s40s48s56s64s72r_e45_"AMSPromise"24?0"AMSOptional"8"NSError"16l
+ ___block_descriptor_88_e8_32s40s48s56s64s_e17_v16?0"NSError"8l
+ ___getSPKPaymentSheetClass_block_invoke
+ ___getSPKSecureThreeDomainInterruptionClass_block_invoke
+ ___swift_closure_destructor.172Tm
+ ___swift_closure_destructor.176Tm
+ ___swift_closure_destructor.180Tm
+ ___swift_closure_destructor.279Tm
+ _associated conformance 18AppleMediaServices13HARBufferCoreO6EffectOSHAASQ
+ _associated conformance 18AppleMediaServices16MusicRestrictionOSHAASQ
+ _associated conformance 18AppleMediaServices26NearFieldRedeemReadingModeO5EventOSHAASQ
+ _associated conformance 18AppleMediaServices26NearFieldRedeemReadingModeO5PhaseOSHAASQ
+ _audit_stringServicesPaymentKit
+ _dispatch_group_notify
+ _flat unique So31AMSSubscriptionInvitePresenting_p
+ _getSPKPaymentSheetClass
+ _keypath_get_selector_presenter
+ _objc_msgSend$_addCookiesToRequest:account:decorator:
+ _objc_msgSend$_adoptRendererEndpoint:error:source:logKey:
+ _objc_msgSend$_computeShouldUseSPKPaymentSheet
+ _objc_msgSend$_dismissPaymentSheet:
+ _objc_msgSend$_flushPendingEntriesWithTracker:archiveService:timeout:
+ _objc_msgSend$_handlePaymentAuthorization:completion:
+ _objc_msgSend$_identifierFromUUID:
+ _objc_msgSend$_isSPKPaymentSheetFeatureFlagEnabled
+ _objc_msgSend$_makeInterruptionWithSceneIdentifier:
+ _objc_msgSend$_maxBufferSizeForMemoryPressureStatus:
+ _objc_msgSend$_performViewServiceOrInProcessTask
+ _objc_msgSend$_performWithRendererEndpoint
+ _objc_msgSend$_present
+ _objc_msgSend$_presentInterruption:
+ _objc_msgSend$_presentInterruptionWithViewServiceEndpoint:
+ _objc_msgSend$_promiseExcludingServerPayload:
+ _objc_msgSend$_promiseIfCancelledBeforeStart
+ _objc_msgSend$_recordTaskInfo:responseData:route:tracker:
+ _objc_msgSend$_requestForExpandableInfoURL:requestType:bag:session:error:
+ _objc_msgSend$_resolvePresentationTargetAndPresent
+ _objc_msgSend$_resolveRendererEndpoint
+ _objc_msgSend$_resolveRendererEndpointFromPresentingProcess
+ _objc_msgSend$_sharedConnectionQueue
+ _objc_msgSend$_sharedRecordingTracker
+ _objc_msgSend$_sharedService
+ _objc_msgSend$_shouldUseSPKPaymentSheet
+ _objc_msgSend$_spkPaymentSheetDisabledBagKey
+ _objc_msgSend$addAcceptEncodingHeaderToRequest:
+ _objc_msgSend$addAcceptLanguageHeaderToRequest:
+ _objc_msgSend$addAuthKitHeadersToRequest:
+ _objc_msgSend$addBiometricsHeadersToRequest:forAccount:options:
+ _objc_msgSend$addCacheBusterParameterToRequest:preservingQueryEncoding:
+ _objc_msgSend$addCachePolicyHeaderToRequest:
+ _objc_msgSend$addCharactersInRange:
+ _objc_msgSend$addCharactersInString:
+ _objc_msgSend$addClientIdentifierHeaderToRequest:forClient:
+ _objc_msgSend$addConnectionTypeHeaderToRequest:
+ _objc_msgSend$addCookiesToRequest:forAccount:clientInfo:bag:cleanupGlobalCookies:excludeAccountIdentifierCookies:
+ _objc_msgSend$addForwardedForHeaderToRequest:
+ _objc_msgSend$addGSTokenToRequest:forAccount:identifier:
+ _objc_msgSend$addGroupDSIDsToRequest:primaryAccount:groupAccounts:
+ _objc_msgSend$addIdentifierHeadersToRequest:forAccount:
+ _objc_msgSend$addIssuingProcessHeaderToRequest:
+ _objc_msgSend$addMMeClientInfoAndDeviceHeadersToRequest:
+ _objc_msgSend$addPrimaryiCloudIdentifierHeaderToRequest:
+ _objc_msgSend$addProductTypeHeaderToRequest:
+ _objc_msgSend$addRequestingProcessHeaderToRequest:forClient:
+ _objc_msgSend$addStorefrontHeaderToRequest:forAccount:mediaType:bag:
+ _objc_msgSend$addTimezoneOffsetHeaderToRequest:
+ _objc_msgSend$addUserAgentHeaderToRequest:forClient:
+ _objc_msgSend$ageSignalConflict
+ _objc_msgSend$ams_addClientVersionsForClient:
+ _objc_msgSend$ams_errorByRemovingUserInfoKeys:
+ _objc_msgSend$ams_flushAllEntriesToDisk
+ _objc_msgSend$ams_underlyingErrorTreeForError:
+ _objc_msgSend$bodyByInjectingSessionId:intoRequest:
+ _objc_msgSend$cachedShouldUseSPKPaymentSheetPromise
+ _objc_msgSend$cancelRequested
+ _objc_msgSend$challengeResponse
+ _objc_msgSend$compressBodyInRequest:logUUID:loggingFor:
+ _objc_msgSend$customData
+ _objc_msgSend$decorator
+ _objc_msgSend$disableCookieHandlingInRequest:
+ _objc_msgSend$encodeBodyParametersInRequest:parameters:encoding:error:
+ _objc_msgSend$endTime
+ _objc_msgSend$excludesServerPayloadFromErrors
+ _objc_msgSend$fetchServicesPaymentListenerEndpointWithReply:
+ _objc_msgSend$filterUsingPredicate:
+ _objc_msgSend$flushPromise
+ _objc_msgSend$formURLEncodedQueryFromItems:
+ _objc_msgSend$groupSubscriptionInfoIn:
+ _objc_msgSend$hasRecorded
+ _objc_msgSend$hostAppAuditTokenData
+ _objc_msgSend$initWithRequest:sceneIdentifier:
+ _objc_msgSend$initWithResponseDictionary:
+ _objc_msgSend$initWithResultData:
+ _objc_msgSend$initWithSceneIdentifier:
+ _objc_msgSend$initWithSubscriptionInfo:
+ _objc_msgSend$isPaymentInterruptionAction:
+ _objc_msgSend$isSecureThreeDomainAction:
+ _objc_msgSend$lostConnection
+ _objc_msgSend$metricsReporter
+ _objc_msgSend$musicRestrictionValue
+ _objc_msgSend$notifyWhenIdleOnQueue:block:
+ _objc_msgSend$paymentSheet
+ _objc_msgSend$paymentSheetRenderingMethod
+ _objc_msgSend$percentEncodedFormComponent:
+ _objc_msgSend$performSecureThreeDomainInterruptionWithTaskInfo:completionHandler:
+ _objc_msgSend$predicateWithBlock:
+ _objc_msgSend$presentSubscriptionInviteForTask:subscriptionFamilyId:
+ _objc_msgSend$presenter
+ _objc_msgSend$purchaseUUID
+ _objc_msgSend$reasonMessage
+ _objc_msgSend$rendererEndpoint
+ _objc_msgSend$reportTreatmentStoreFailureEvent:
+ _objc_msgSend$sceneIdentifier
+ _objc_msgSend$scheduleSendBarrierBlock:
+ _objc_msgSend$secure3dSessionId
+ _objc_msgSend$servicesPaymentRendererEndpoint
+ _objc_msgSend$servicesPaymentViewServiceListener
+ _objc_msgSend$setActiveInterruption:
+ _objc_msgSend$setCachedShouldUseSPKPaymentSheetPromise:
+ _objc_msgSend$setCancelRequested:
+ _objc_msgSend$setChallengeResponse:
+ _objc_msgSend$setCustomData:
+ _objc_msgSend$setEndTime:
+ _objc_msgSend$setExcludesServerPayloadFromErrors:
+ _objc_msgSend$setHostAppAuditTokenData:
+ _objc_msgSend$setLostConnection:
+ _objc_msgSend$setPageUserInteractiveTime:
+ _objc_msgSend$setPaymentAuthorizationHandler:
+ _objc_msgSend$setPaymentSheet:
+ _objc_msgSend$setPresenter:
+ _objc_msgSend$setPurchaseIdentifier:
+ _objc_msgSend$setPurchaseUUID:
+ _objc_msgSend$setRendererEndpoint:
+ _objc_msgSend$setServicesPaymentViewServiceListener:
+ _objc_msgSend$setStartTime:
+ _objc_msgSend$setUsingSPKPaymentSheet:
+ _objc_msgSend$setViewServiceEndpoint:
+ _objc_msgSend$sharedDecorator
+ _objc_msgSend$sortQueryParametersInRequest:
+ _objc_msgSend$startTime
+ _objc_msgSend$subscriptionFamilyId
+ _objc_msgSend$trackedRecordingBlock:
+ _objc_msgSend$updateBodyOnAction:withSessionId:originatingTaskInfo:
+ _objc_msgSend$urlTaskInfo
+ _objc_msgSend$usingSPKPaymentSheet
+ _objc_msgSend$viewServiceEndpoint
+ _sharedService
+ _symbolic $s18AppleMediaServices28SubscriptionInvitePresentingP
+ _symbolic Sb21recordedSinceLastTick_t
+ _symbolic Sb8buffered_t
+ _symbolic Sd26cardSessionKeyValidityTime_t
+ _symbolic So12AMSURLActionCSgIegg_
+ _symbolic So12AMSURLActionCSgIeyBy_
+ _symbolic So25AMSSubscriptionInviteTaskC
+ _symbolic So36AMSSecureThreeDomainInterruptionTaskC
+ _symbolic So37AMSFinancePaymentInterruptionResponseCXDXMT
+ _symbolic _____ 18AppleMediaServices13HARBufferCoreO
+ _symbolic _____ 18AppleMediaServices13HARBufferCoreO5EventO
+ _symbolic _____ 18AppleMediaServices13HARBufferCoreO5PhaseO
+ _symbolic _____ 18AppleMediaServices13HARBufferCoreO6EffectO
+ _symbolic _____ 18AppleMediaServices16MusicRestrictionO
+ _symbolic _____ 18AppleMediaServices25NearFieldMetricsEventCoreO
+ _symbolic _____ 18AppleMediaServices26NearFieldRedeemReadingModeO
+ _symbolic _____ 18AppleMediaServices26NearFieldRedeemReadingModeO5EventO
+ _symbolic _____ 18AppleMediaServices26NearFieldRedeemReadingModeO5PhaseO
+ _symbolic _____ 18AppleMediaServices26NearFieldRedeemReadingModeO6ActionO
+ _symbolic _____ So38AMSSecureThreeDomainInterruptionStatusV
+ _symbolic _____Sg So38AMSSecureThreeDomainInterruptionStatusV
+ _symbolic ______Sd26cardSessionKeyValidityTimet 18AppleMediaServices26NearFieldRedeemReadingModeO5PhaseO
+ _symbolic ___________t 18AppleMediaServices26NearFieldRedeemReadingModeO AC5EventO
+ _symbolic ______p 18AppleMediaServices28SubscriptionInvitePresentingP
+ _symbolic ______ypt s11AnyHashableV
+ _symbolic ______yptSg s11AnyHashableV
+ _task_info
- -[AMSPurchase _generateIdentifier]
- -[AMSURLRequestEncoder _addCookiesToRequest:account:]
- GCC_except_table100
- GCC_except_table68
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSDate_$_AMSFormattingUtilities
- __OBJC_$_CATEGORY_NSDate_$_AMSFormattingUtilities
- __OBJC_$_CLASS_METHODS_NSDate(AMSFormattingUtilities|AppleMediaServices)
- __OBJC_$_PROP_LIST_NSDate_$_AMSFormattingUtilities
- ___37+[AMSHTTPArchiveService _sharedProxy]_block_invoke_3
- ___45+[AMSStreamHTTPArchiveEntryController buffer]_block_invoke_2
- ___53-[AMSURLRequestEncoder _addCookiesToRequest:account:]_block_invoke
- ___56+[AMSHTTPArchive ams_recordTaskInfo:responseData:route:]_block_invoke
- ___block_descriptor_48_e8_32s40s_e44_"AMSPromise"24?0"AMSBoolean"8"NSError"16l
- ___block_descriptor_56_e8_32s40s48r_e30_"AMSPromise"16?0"NSNumber"8l
- ___block_descriptor_56_e8_32s40s48r_e34_"AMSPromise"16?0"NSDictionary"8l
- ___block_descriptor_64_e8_32s40s48r56r_e30_"AMSPromise"16?0"NSNumber"8l
- ___block_descriptor_72_e8_32s40s48s56s64r_e45_"AMSPromise"24?0"AMSOptional"8"NSError"16l
- ___swift_closure_destructor.170Tm
- ___swift_closure_destructor.174Tm
- ___swift_closure_destructor.178Tm
- ___swift_closure_destructor.277Tm
- __sharedProxy.sharedService
- _objc_msgSend$_addCookiesToRequest:account:
- _objc_msgSend$_generateIdentifier
CStrings:
+ "  musicRestriction: "
+ "!\xa2"
+ "%20"
+ "%{public}@: [%{public}@] Gave up flushing pending HAR records; the archive may be truncated. %{public}@"
+ "%{public}@Attempting to dismiss nil payment sheet"
+ "%{public}@Cancelled before the payment sheet task started"
+ "%{public}@Cancelling payment sheet: %{public}@"
+ "%{public}@Dismissing payment sheet: %{public}@"
+ "%{public}@Excluded the server response body from the purchase error"
+ "%{public}@Failed to ask the view service for a ServicesPaymentKit endpoint: %{public}@"
+ "%{public}@Failed to decode 3DS body as UTF-8"
+ "%{public}@Failed to determine SPK payment sheet eligibility: %{public}@"
+ "%{public}@Failed to determine SPK payment sheet eligibility; using the view service: %{public}@"
+ "%{public}@Failed to parse 3DS form body"
+ "%{public}@No ServicesPaymentKit renderer endpoint from %{public}@: %{public}@"
+ "%{public}@No ServicesPaymentKit renderer for the payment sheet (endpoint: %{public}@)"
+ "%{public}@Not updating body for content type: %{public}@"
+ "%{public}@Obtained a ServicesPaymentKit renderer endpoint from %{public}@"
+ "%{public}@Payment sheet dismissed"
+ "%{public}@Presenting 3D Secure interruption through view service endpoint from %{public}@"
+ "%{public}@Presenting payment sheet: %{public}@"
+ "%{public}@SubsForGroups feature disabled (subscriptionFamilyId=%{public}@, sceneIdentifier=%{public}@)"
+ "%{public}@Timed out asking the view service for a ServicesPaymentKit endpoint"
+ "%{public}@Timed out waiting for the presenting process's ServicesPaymentKit endpoint"
+ "%{public}@paymentSheet: %{public}@"
+ "%{public}@paymentSheet: %{public}@ | event: %lu"
+ "-._~"
+ "-paymentInterruption"
+ "/System/Library/PrivateFrameworks/ServicesPaymentKit.framework/Contents/MacOS/ServicesPaymentKit"
+ "38BC2C08-01A6-451D-9ABE-791707FBD11C"
+ "3D Secure Interruption Failed"
+ "3DS UI process reported an internal error"
+ "3DS authentication was cancelled by the user"
+ "3DS authentication was rejected by the issuer"
+ "3DS interruption cancelled by user; failing purchase"
+ "3DS interruption failed with internal error; failing purchase. reason="
+ "3DS interruption failed: "
+ "3DS interruption rejected by issuer; failing purchase"
+ "3DS interruption resolved, replaying purchase"
+ "<%@ dialog event>"
+ "<%@ loadUrl event>"
+ "<%@ pageRender event>"
+ "@\"AMSHTTPArchiveService\"8@?0"
+ "AMSAuthenticateOptionsPurchaseIdentifierKey"
+ "AppleMediaServices_BridgedInterface.AMSFinanceSubscriptionInviteResponse"
+ "B24@?0@\"NSURLQueryItem\"8@\"NSDictionary\"16"
+ "DetermineSPKVsPassKitSheet"
+ "Failed to construct retry action"
+ "Failed to construct retry action after 3DS resolution"
+ "Failed to instantiate SPKSecureThreeDomainInterruption"
+ "HAR Recording Connection Invalidated"
+ "MetricsLogging"
+ "No presenter; use AppleMediaServicesUI's init(request:presenting:)"
+ "No renderer for the payment sheet"
+ "No view service endpoint available for presentation"
+ "Payment Sheet Missing"
+ "Request has no subscriptionFamilyId"
+ "SPKPaymentSheet_macOS"
+ "SPKSecureThreeDomainInterruption"
+ "ServicesPaymentKit"
+ "ServicesPaymentKit is disabled by feature flag"
+ "ServicesPaymentViewController"
+ "Starting 3DS interruption with response"
+ "SubsForGroups"
+ "SubsForGroups feature disabled"
+ "Subscription Invite Failed"
+ "Subscription invite failed: "
+ "The payment sheet task was cancelled before it started."
+ "Unable to create payment sheet"
+ "Unknown paymentInterruption sub-type"
+ "We attempted to dismiss a nil payment sheet."
+ "amsPurchaseTaskEndTime"
+ "amsPurchaseTaskStartTime"
+ "application/x-www-form-urlencoded"
+ "connectionInterrupted"
+ "connectionInvalidated"
+ "dailyLimitExceeded"
+ "groupSubscriptionInfo"
+ "invalidArguments"
+ "kAgeSignalConflict"
+ "kPurchaseIdentifier"
+ "missing"
+ "platformNotSupported"
+ "purchaseIdentifier"
+ "purchaseUUID"
+ "randomizedSuppression"
+ "requestThrottled"
+ "seed"
+ "selfie_sing"
+ "serviceInterrupted"
+ "serviceUnavailable"
+ "servicesPaymentViewServiceListener"
+ "snapshotTypeDoesNotConformToNSSecureCoding"
+ "softlink:r:path:/System/Library/PrivateFrameworks/ServicesPaymentKit.framework/ServicesPaymentKit"
+ "spk-payment-sheet-macos-disabled"
+ "systemEngagementSceneRemoteAlertEnabled"
+ "task"
+ "the presenting process"
+ "the view service"
+ "v16@?0@\"NSData\"8"
+ "v24@?0@\"NSXPCListenerEndpoint\"8@\"NSError\"16"
+ "v24@?0@\"PKPayment\"8@?<v@?@\"PKPaymentAuthorizationResult\">16"
- "!\xa1"
- "<private>"
- "TreatmentStoreErrorMetrics"
```
