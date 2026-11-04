## AppPredictionClient

> `/System/Library/PrivateFrameworks/AppPredictionClient.framework/Versions/A/AppPredictionClient`

```diff

-678.0.1.0.0
-  __TEXT.__text: 0x19c530
-  __TEXT.__objc_methlist: 0x18b9c
-  __TEXT.__const: 0x708
-  __TEXT.__cstring: 0x1c2a2
-  __TEXT.__oslogstring: 0x178ab
-  __TEXT.__gcc_except_tab: 0x1cac
+678.2.1.0.3
+  __TEXT.__text: 0x1a0424
+  __TEXT.__objc_methlist: 0x18dec
+  __TEXT.__const: 0x718
+  __TEXT.__cstring: 0x1c88f
+  __TEXT.__oslogstring: 0x17ee6
+  __TEXT.__gcc_except_tab: 0x1d14
   __TEXT.__dlopen_cstrs: 0x2cc
   __TEXT.__ustring: 0x18a
-  __TEXT.__unwind_info: 0x8490
+  __TEXT.__unwind_info: 0x8580
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x31c0
-  __DATA_CONST.__objc_classlist: 0xdc8
+  __DATA_CONST.__const: 0x3238
+  __DATA_CONST.__objc_classlist: 0xdd0
   __DATA_CONST.__objc_catlist: 0x90
-  __DATA_CONST.__objc_protolist: 0x238
+  __DATA_CONST.__objc_protolist: 0x240
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa060
+  __DATA_CONST.__objc_selrefs: 0xa1a0
   __DATA_CONST.__objc_protorefs: 0x98
-  __DATA_CONST.__objc_superrefs: 0xbf0
+  __DATA_CONST.__objc_superrefs: 0xbf8
   __DATA_CONST.__objc_arraydata: 0xb30
-  __DATA_CONST.__got: 0x16d8
-  __AUTH_CONST.__const: 0x6550
-  __AUTH_CONST.__cfstring: 0x15560
-  __AUTH_CONST.__objc_const: 0x448a8
+  __DATA_CONST.__got: 0x16e8
+  __AUTH_CONST.__const: 0x6650
+  __AUTH_CONST.__cfstring: 0x156c0
+  __AUTH_CONST.__objc_const: 0x45140
   __AUTH_CONST.__objc_intobj: 0xa98
   __AUTH_CONST.__objc_arrayobj: 0x6d8
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH_CONST.__auth_got: 0x690
-  __AUTH.__objc_data: 0x33e0
-  __DATA.__objc_ivar: 0x1c50
-  __DATA.__data: 0x1aa0
+  __AUTH.__objc_data: 0x3430
+  __DATA.__objc_ivar: 0x1cd0
+  __DATA.__data: 0x1b00
   __DATA.__bss: 0x320
   __DATA_DIRTY.__objc_data: 0x55f0
   __DATA_DIRTY.__data: 0x88

   - /usr/lib/libarchive.2.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 10927
-  Symbols:   20260
-  CStrings:  4825
+  Functions: 10999
+  Symbols:   20409
+  CStrings:  4882
 
Symbols:
+ +[ATXDefaultHomeScreenItemManager _pendingWidgetIdentifiersForPersonalities:clientIdentity:]
+ +[ATXDefaultHomeScreenItemManager _personalitiesOfPairedDeviceWidgets:replacedByLocalCopiesAmongDescriptors:]
+ +[ATXDefaultHomeScreenItemManager _snapshotOfSmartStackRequest:]
+ +[ATXDefaultHomeScreenItemManager _widgetPersonalitiesFilteredOutOfDescriptors:keptDescriptors:personaIdentifier:]
+ +[ATXDefaultHomeScreenItemProducerUtilities _widgetKeyResolvingGatedWidgetPlaceholder:]
+ -[ATXDefaultHomeScreenItemManager _fetchWidgetSmartStackWithRequest:findingPendingWidgets:completionHandler:]
+ -[ATXDefaultHomeScreenItemManager _generateSmartStackResponseWithRequest:findingPendingWidgets:error:]
+ -[ATXDefaultHomeScreenItemManager _generateSmartStackWithDescriptorCacheFromRequest:findingPendingWidgets:error:]
+ -[ATXDefaultHomeScreenItemManager observeWidgetSmartStackWithRequest:timeout:updateHandler:]
+ -[ATXDefaultHomeScreenItemOnboardingStacks initWithOnboardingStacks:sortedThirdPartyWidgets:pendingWidgetPersonalities:]
+ -[ATXDefaultHomeScreenItemOnboardingStacks pendingWidgetPersonalities]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _isWaitingForDescriptorOfPersonality:size:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _pendingWidgetPersonalitiesForTvOSOnboardingStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _standInForWidgetWithPersonality:appBundleId:supportedFamilies:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _tvOSOnboardingStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer setShouldFindPendingWidgets:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer setWidgetIdentifiersDeniedForClient:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer setWidgetPersonalitiesFilteredOutForClient:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer shouldFindPendingWidgets]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer widgetIdentifiersDeniedForClient]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer widgetPersonalitiesFilteredOutForClient]
+ -[ATXDefaultHomeScreenItemProducer setShouldFindPendingWidgets:]
+ -[ATXDefaultHomeScreenItemProducer setWidgetIdentifiersDeniedForClient:]
+ -[ATXDefaultHomeScreenItemProducer setWidgetPersonalitiesFilteredOutForClient:]
+ -[ATXDefaultHomeScreenItemProducer shouldFindPendingWidgets]
+ -[ATXDefaultHomeScreenItemProducer widgetIdentifiersDeniedForClient]
+ -[ATXDefaultHomeScreenItemProducer widgetPersonalitiesFilteredOutForClient]
+ -[ATXWidgetSmartStackObservation .cxx_destruct]
+ -[ATXWidgetSmartStackObservation _queue_deadlineDidPass]
+ -[ATXWidgetSmartStackObservation _queue_finishWithOutcome:]
+ -[ATXWidgetSmartStackObservation _queue_firstBuildDeadlineDidPass]
+ -[ATXWidgetSmartStackObservation _queue_generate]
+ -[ATXWidgetSmartStackObservation _queue_handleResponse:error:]
+ -[ATXWidgetSmartStackObservation _queue_scheduleRebuild]
+ -[ATXWidgetSmartStackObservation _queue_sendFinalResult]
+ -[ATXWidgetSmartStackObservation _queue_sendResponse:error:isFinal:]
+ -[ATXWidgetSmartStackObservation _queue_startDeadlineTimer]
+ -[ATXWidgetSmartStackObservation cancelWithReason:]
+ -[ATXWidgetSmartStackObservation cancel]
+ -[ATXWidgetSmartStackObservation cancellationReason]
+ -[ATXWidgetSmartStackObservation descriptorsDidChange]
+ -[ATXWidgetSmartStackObservation initWithTimeout:generator:updateHandler:]
+ -[ATXWidgetSmartStackObservation startObservingDescriptorCacheFromProvider:]
+ -[ATXWidgetSmartStackObservation startObservingDescriptorCacheFromProvider:rebuildNotificationName:]
+ -[ATXWidgetSmartStackObservation widgetDescriptorCacheDidUpdateHomeScreenDescriptors:]
+ -[ATXWidgetSmartStackResponse initWithStacks:pendingWidgetIdentifiers:isFinal:]
+ -[ATXWidgetSmartStackResponse isFinal]
+ -[ATXWidgetSmartStackResponse pendingWidgetIdentifiers]
+ GCC_except_table40
+ GCC_except_table49
+ GCC_except_table50
+ _ATXPairedDeviceWidgetRankingImportedDarwinNotificationName
+ _OBJC_CLASS_$_ATXWidgetSmartStackObservation
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemOnboardingStacks._pendingWidgetPersonalities
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemOnboardingStacksProducer._shouldFindPendingWidgets
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemOnboardingStacksProducer._widgetIdentifiersDeniedForClient
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemOnboardingStacksProducer._widgetPersonalitiesFilteredOutForClient
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemProducer._shouldFindPendingWidgets
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemProducer._widgetIdentifiersDeniedForClient
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemProducer._widgetPersonalitiesFilteredOutForClient
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._buildQueue
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._cancellationReason
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._deadlinePassed
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._deadlineTimer
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._descriptorCache
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._generator
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._hasBuildResult
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._hasStarted
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._isFinished
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._isGenerating
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._isRebuildScheduled
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._lastSentResponse
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._latestError
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._latestResponse
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._needsGeneration
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._queue
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._rebuildNotificationToken
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._retainedSelf
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._signpostID
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._startUptime
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._timeout
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._updateCount
+ _OBJC_IVAR_$_ATXWidgetSmartStackObservation._updateHandler
+ _OBJC_IVAR_$_ATXWidgetSmartStackResponse._isFinal
+ _OBJC_IVAR_$_ATXWidgetSmartStackResponse._pendingWidgetIdentifiers
+ _OBJC_METACLASS_$_ATXWidgetSmartStackObservation
+ __OBJC_$_INSTANCE_METHODS_ATXWidgetSmartStackObservation
+ __OBJC_$_INSTANCE_VARIABLES_ATXWidgetSmartStackObservation
+ __OBJC_$_PROP_LIST_ATXWidgetSmartStackObservation
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_ATXWidgetDescriptorCacheObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ATXWidgetDescriptorCacheObserver
+ __OBJC_$_PROTOCOL_REFS_ATXWidgetDescriptorCacheObserver
+ __OBJC_CLASS_PROTOCOLS_$_ATXWidgetSmartStackObservation
+ __OBJC_CLASS_RO_$_ATXWidgetSmartStackObservation
+ __OBJC_LABEL_PROTOCOL_$_ATXWidgetDescriptorCacheObserver
+ __OBJC_METACLASS_RO_$_ATXWidgetSmartStackObservation
+ __OBJC_PROTOCOL_$_ATXWidgetDescriptorCacheObserver
+ ___100-[ATXWidgetSmartStackObservation startObservingDescriptorCacheFromProvider:rebuildNotificationName:]_block_invoke
+ ___109-[ATXDefaultHomeScreenItemManager _fetchWidgetSmartStackWithRequest:findingPendingWidgets:completionHandler:]_block_invoke
+ ___189-[ATXDefaultHomeScreenItemOnboardingStacksProducer _pendingWidgetPersonalitiesForTvOSOnboardingStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke
+ ___49-[ATXWidgetSmartStackObservation _queue_generate]_block_invoke
+ ___49-[ATXWidgetSmartStackObservation _queue_generate]_block_invoke_2
+ ___49-[ATXWidgetSmartStackObservation _queue_generate]_block_invoke_3
+ ___51-[ATXWidgetSmartStackObservation cancelWithReason:]_block_invoke
+ ___54-[ATXWidgetSmartStackObservation descriptorsDidChange]_block_invoke
+ ___56-[ATXWidgetSmartStackObservation _queue_scheduleRebuild]_block_invoke
+ ___59-[ATXWidgetSmartStackObservation _queue_startDeadlineTimer]_block_invoke
+ ___92+[ATXDefaultHomeScreenItemManager _pendingWidgetIdentifiersForPersonalities:clientIdentity:]_block_invoke
+ ___92-[ATXDefaultHomeScreenItemManager observeWidgetSmartStackWithRequest:timeout:updateHandler:]_block_invoke
+ ___block_descriptor_40_e8_32w_e49_v24?0"ATXWidgetSmartStackResponse"8"NSError"16l
+ ___block_descriptor_40_e8_32w_e8_v12?0i8l
+ ___block_descriptor_48_e8_32bs40w_e5_v8?0l
+ ___block_descriptor_58_e8_32s40s48r_e54_v16?0?<v?"ATXWidgetSmartStackResponse""NSError">8l
+ ___copy_helper_block_e8_32b40w
+ _objc_msgSend$_fetchWidgetSmartStackWithRequest:findingPendingWidgets:completionHandler:
+ _objc_msgSend$_generateSmartStackResponseWithRequest:findingPendingWidgets:error:
+ _objc_msgSend$_generateSmartStackWithDescriptorCacheFromRequest:findingPendingWidgets:error:
+ _objc_msgSend$_isWaitingForDescriptorOfPersonality:size:
+ _objc_msgSend$_pendingWidgetIdentifiersForPersonalities:clientIdentity:
+ _objc_msgSend$_pendingWidgetPersonalitiesForTvOSOnboardingStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:
+ _objc_msgSend$_personalitiesOfPairedDeviceWidgets:replacedByLocalCopiesAmongDescriptors:
+ _objc_msgSend$_queue_deadlineDidPass
+ _objc_msgSend$_queue_finishWithOutcome:
+ _objc_msgSend$_queue_firstBuildDeadlineDidPass
+ _objc_msgSend$_queue_generate
+ _objc_msgSend$_queue_handleResponse:error:
+ _objc_msgSend$_queue_scheduleRebuild
+ _objc_msgSend$_queue_sendFinalResult
+ _objc_msgSend$_queue_sendResponse:error:isFinal:
+ _objc_msgSend$_queue_startDeadlineTimer
+ _objc_msgSend$_snapshotOfSmartStackRequest:
+ _objc_msgSend$_standInForWidgetWithPersonality:appBundleId:supportedFamilies:
+ _objc_msgSend$_tvOSOnboardingStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:
+ _objc_msgSend$_widgetKeyResolvingGatedWidgetPlaceholder:
+ _objc_msgSend$_widgetPersonalitiesFilteredOutOfDescriptors:keptDescriptors:personaIdentifier:
+ _objc_msgSend$cancelWithReason:
+ _objc_msgSend$descriptorsDidChange
+ _objc_msgSend$initWithOnboardingStacks:sortedThirdPartyWidgets:pendingWidgetPersonalities:
+ _objc_msgSend$initWithStacks:pendingWidgetIdentifiers:isFinal:
+ _objc_msgSend$initWithTimeout:generator:updateHandler:
+ _objc_msgSend$isFinal
+ _objc_msgSend$pendingWidgetIdentifiers
+ _objc_msgSend$pendingWidgetPersonalities
+ _objc_msgSend$setShouldFindPendingWidgets:
+ _objc_msgSend$setSourceDeviceIdentifier:
+ _objc_msgSend$setWidgetIdentifiersDeniedForClient:
+ _objc_msgSend$setWidgetPersonalitiesFilteredOutForClient:
+ _objc_msgSend$setWithCapacity:
+ _objc_msgSend$shouldFindPendingWidgets
+ _objc_msgSend$startObservingDescriptorCacheFromProvider:rebuildNotificationName:
+ _objc_msgSend$systemUptime
+ _objc_msgSend$widgetDescriptorCacheDidUpdateHomeScreenDescriptors:
+ _objc_msgSend$widgetIdentifiersDeniedForClient
+ _objc_msgSend$widgetPersonalitiesFilteredOutForClient
- -[ATXDefaultHomeScreenItemManager _generateSmartStackWithDescriptorCacheFromRequest:error:]
- -[ATXDefaultHomeScreenItemManager _generateSmartStacksWithRequest:error:]
- ___86-[ATXDefaultHomeScreenItemManager fetchWidgetSmartStackWithRequest:completionHandler:]_block_invoke
- _objc_msgSend$_generateSmartStackWithDescriptorCacheFromRequest:error:
- _objc_msgSend$_generateSmartStacksWithRequest:error:
CStrings:
+ "%s: %lu of the client's widgets were filtered out: %{public}@"
+ "%s: %p already building, so building again after"
+ "%s: %p couldn't build the first stacks, and nothing will build them again: %{public}@"
+ "%s: %p couldn't build the first stacks, so waiting for descriptors to change: %{public}@"
+ "%s: %p couldn't register for %{public}@ (status %u), so it won't build again when it's posted"
+ "%s: %p finished (%{public}s, cancellation reason: %{public}s) after %.1fs and %lu updates, still waiting on %{public}@"
+ "%s: %p keeping the last stacks after a rebuild failed: %{public}@"
+ "%s: %p observing for Client: %@, variant: %lu, timeout: %.1fs"
+ "%s: %p rebuilt stacks are unchanged, still waiting on %lu widgets"
+ "%s: %p sending update %lu with %lu stacks, final: %{BOOL}d, still waiting on %lu widgets, error: %{public}@"
+ "%s: %p started, waiting up to %.1fs after the first stacks for missing widgets"
+ "%s: %p stopped waiting for missing widgets after %.1fs"
+ "%s: %p the first build didn't finish within %.1fs, so giving up"
+ "%s: Client has no persona, so it isn't waiting on %{public}@"
+ "%s: Couldn't copy the smart stack request, so the observation uses the caller's: %{public}@"
+ "%s: building the tvOS onboarding stacks again with stand-ins for %lu missing widgets"
+ "%s: local copies take the place of %lu of the paired device's widgets: %{public}@"
+ "%s: tvOS onboarding stacks are waiting on descriptors for %{public}@"
+ "+[ATXDefaultHomeScreenItemManager _pendingWidgetIdentifiersForPersonalities:clientIdentity:]"
+ "+[ATXDefaultHomeScreenItemManager _snapshotOfSmartStackRequest:]"
+ "-[ATXDefaultHomeScreenItemManager _generateSmartStackResponseWithRequest:findingPendingWidgets:error:]"
+ "-[ATXDefaultHomeScreenItemManager _generateSmartStackWithDescriptorCacheFromRequest:findingPendingWidgets:error:]"
+ "-[ATXDefaultHomeScreenItemManager observeWidgetSmartStackWithRequest:timeout:updateHandler:]"
+ "-[ATXDefaultHomeScreenItemOnboardingStacksProducer _pendingWidgetPersonalitiesForTvOSOnboardingStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]"
+ "-[ATXWidgetSmartStackObservation _queue_deadlineDidPass]"
+ "-[ATXWidgetSmartStackObservation _queue_finishWithOutcome:]"
+ "-[ATXWidgetSmartStackObservation _queue_firstBuildDeadlineDidPass]"
+ "-[ATXWidgetSmartStackObservation _queue_generate]"
+ "-[ATXWidgetSmartStackObservation _queue_handleResponse:error:]"
+ "-[ATXWidgetSmartStackObservation _queue_sendResponse:error:isFinal:]"
+ "-[ATXWidgetSmartStackObservation startObservingDescriptorCacheFromProvider:rebuildNotificationName:]_block_invoke"
+ "ATXStandInWidgetDevice"
+ "ATXWidgetSmartStackObservation"
+ "ATXWidgetSmartStackObservation.build"
+ "Failed to rebuild smart stacks"
+ "PriorityFeedbackNegative"
+ "PriorityFeedbackPositive"
+ "PriorityFeedbackReportConcern"
+ "Timed out building the first smart stacks"
+ "cancelled"
+ "com.apple.duetexpertd.pairedDeviceWidgetRankingImported"
+ "failed"
+ "final:%{BOOL}d stacks:%lu pending:%lu"
+ "isFinal"
+ "no_longer_needed"
+ "none"
+ "nothing"
+ "outcome:%{public}s cancellation:%{public}s updates:%lu pending:%lu"
+ "pendingWidgetIdentifiers"
+ "smartStackObservation"
+ "smartStackObservationRebuild"
+ "smartStackObservationUpdate"
+ "stack_removed"
+ "stacks:%lu pending:%lu"
+ "timedOut"
+ "unspecified"
+ "user_edited_stack"
+ "v16@?0@?<v@?@\"ATXWidgetSmartStackResponse\"@\"NSError\">8"
+ "v24@?0@\"ATXWidgetSmartStackResponse\"8@\"NSError\"16"
- "-[ATXDefaultHomeScreenItemManager _generateSmartStackWithDescriptorCacheFromRequest:error:]"
- "-[ATXDefaultHomeScreenItemManager _generateSmartStacksWithRequest:error:]"
```
