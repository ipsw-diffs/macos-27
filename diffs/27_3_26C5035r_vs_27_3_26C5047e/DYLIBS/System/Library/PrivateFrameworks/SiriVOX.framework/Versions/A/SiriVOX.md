## SiriVOX

> `/System/Library/PrivateFrameworks/SiriVOX.framework/Versions/A/SiriVOX`

```diff

-3610.11.1.0.0
-  __TEXT.__text: 0x8d390
-  __TEXT.__objc_methlist: 0x8dd8
-  __TEXT.__const: 0x138
-  __TEXT.__constg_swiftt: 0x8c
-  __TEXT.__swift5_typeref: 0x97
-  __TEXT.__swift5_fieldmd: 0x38
-  __TEXT.__swift5_types: 0x8
-  __TEXT.__cstring: 0x11ace
+3610.18.1.0.0
+  __TEXT.__text: 0x91af0
+  __TEXT.__objc_methlist: 0x920c
+  __TEXT.__const: 0x188
+  __TEXT.__constg_swiftt: 0xc8
+  __TEXT.__swift5_typeref: 0x10b
+  __TEXT.__swift5_fieldmd: 0x70
+  __TEXT.__swift5_types: 0xc
+  __TEXT.__cstring: 0x11fe5
   __TEXT.__swift5_capture: 0x78
-  __TEXT.__swift5_reflstr: 0x16
-  __TEXT.__gcc_except_tab: 0x680
-  __TEXT.__oslogstring: 0x91cd
+  __TEXT.__swift5_reflstr: 0x28
+  __TEXT.__oslogstring: 0x9741
+  __TEXT.__gcc_except_tab: 0x710
   __TEXT.__dlopen_cstrs: 0xda
-  __TEXT.__unwind_info: 0x2dd0
+  __TEXT.__unwind_info: 0x2f78
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1078
-  __DATA_CONST.__objc_classlist: 0x680
+  __DATA_CONST.__const: 0x10e8
+  __DATA_CONST.__objc_classlist: 0x6a0
   __DATA_CONST.__objc_catlist: 0x48
-  __DATA_CONST.__objc_protolist: 0x2e0
+  __DATA_CONST.__objc_protolist: 0x2f0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3eb8
-  __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0x4b0
+  __DATA_CONST.__objc_selrefs: 0x4190
+  __DATA_CONST.__objc_protorefs: 0x50
+  __DATA_CONST.__objc_superrefs: 0x4c8
   __DATA_CONST.__objc_arraydata: 0x990
-  __DATA_CONST.__got: 0x798
-  __AUTH_CONST.__const: 0x2df8
-  __AUTH_CONST.__cfstring: 0x6000
-  __AUTH_CONST.__objc_const: 0x13c38
+  __DATA_CONST.__got: 0x7e0
+  __AUTH_CONST.__const: 0x2f20
+  __AUTH_CONST.__cfstring: 0x6320
+  __AUTH_CONST.__objc_const: 0x144a8
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_intobj: 0xe70
   __AUTH_CONST.__objc_dictobj: 0x348
-  __AUTH_CONST.__auth_got: 0x590
-  __AUTH.__objc_data: 0x41a0
-  __AUTH.__data: 0x30
-  __DATA.__objc_ivar: 0xd18
-  __DATA.__data: 0x22c0
-  __DATA.__bss: 0x248
+  __AUTH_CONST.__auth_got: 0x678
+  __AUTH.__objc_data: 0x4358
+  __AUTH.__data: 0x58
+  __DATA.__objc_ivar: 0xd98
+  __DATA.__data: 0x2340
+  __DATA.__bss: 0x260
+  __DATA.__common: 0x18
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3280
-  Symbols:   8478
-  CStrings:  2305
+  Functions: 3413
+  Symbols:   8747
+  CStrings:  2365
 
Symbols:
+ -[SVXAFUtilitiesWrapper af_IsLinwoodEnabled]
+ -[SVXAceViewHandler _chunkHasSpeakableText:]
+ -[SVXAceViewHandler _endStreamWithIdentifier:error:]
+ -[SVXAceViewHandler _firstProducedSpeechDidStartForStreamIdentifier:]
+ -[SVXAceViewHandler _speakAceView:speakableText:speakableStreamId:isFollowUpQuestion:isExpository:taskTracker:completion:]
+ -[SVXAceViewHandler _speakableStreamerForStreamIdentifier:]
+ -[SVXAceViewHandler _usesSpeakableStreamer]
+ -[SVXAceViewHandler setSpeakableFragmentContexts:]
+ -[SVXAceViewHandler setSpeakableStreamers:]
+ -[SVXAceViewHandler setStreamsAwaitingFirstSpeech:]
+ -[SVXAceViewHandler setStreamsAwaitingFollowUpSpeech:]
+ -[SVXAceViewHandler setStreamsWithDeferredStop:]
+ -[SVXAceViewHandler setStreamsWithProducedSpeech:]
+ -[SVXAceViewHandler speakableFragmentContexts]
+ -[SVXAceViewHandler speakableStreamer:didProduceSpeakableText:]
+ -[SVXAceViewHandler speakableStreamerDidDetectFollowUp:]
+ -[SVXAceViewHandler speakableStreamers]
+ -[SVXAceViewHandler streamsAwaitingFirstSpeech]
+ -[SVXAceViewHandler streamsAwaitingFollowUpSpeech]
+ -[SVXAceViewHandler streamsWithDeferredStop]
+ -[SVXAceViewHandler streamsWithProducedSpeech]
+ -[SVXHomePodUIBridgeClientDelegate _tearDownForDismissal]
+ -[SVXHomePodUIBridgeClientDelegate discardPendingTTSPrewarm]
+ -[SVXHomePodUIBridgeClientDelegate scheduleTTSPrewarm:]
+ -[SVXHomePodUIBridgeClientDelegate siriDismissedForRelaunch]
+ -[SVXMissingAssetActivationGuard _refreshSiriAvailability]
+ -[SVXSession _deactivateAfterLASAttendingStopped]
+ -[SVXSession _handleStartListenAfterSpeaking:record:taskTracker:atEndOfSpeech:]
+ -[SVXSession _releaseAudioSessionForFollowUpWindowIfRequestEnded]
+ -[SVXSession _shouldIgnoreUnscopedCloseAssistant:]
+ -[SVXSession fireIdleTimerForTesting]
+ -[SVXSessionIdleTimer fireSessionIdleTimersNow]
+ -[SVXSessionManager _handleEndSessionTestHook]
+ -[SVXSessionManager _registerEndSessionTestHook]
+ -[SVXSessionManager myriadSessionDidStartWithCdaId:]
+ -[SVXShadowComparisonLogger .cxx_destruct]
+ -[SVXShadowComparisonLogger _scoreBoostsFrom:]
+ -[SVXShadowComparisonLogger electionBegan]
+ -[SVXShadowComparisonLogger initWithEmit:]
+ -[SVXShadowComparisonLogger init]
+ -[SVXShadowComparisonLogger myriadReported]
+ -[SVXShadowComparisonLogger myriadSessionDidStartWithCdaId:]
+ -[SVXShadowComparisonLogger recordAnswerForElection:won:localScore:error:machDuration:]
+ -[SVXShadowLocalScore .cxx_destruct]
+ -[SVXShadowLocalScore audioOrderDeviceCount]
+ -[SVXShadowLocalScore audioOrderPosition]
+ -[SVXShadowLocalScore boostsApplied]
+ -[SVXShadowLocalScore confidence]
+ -[SVXShadowLocalScore deviceClass]
+ -[SVXShadowLocalScore deviceGroup]
+ -[SVXShadowLocalScore goodness]
+ -[SVXShadowLocalScore initWithGoodness:confidence:deviceGroup:deviceClass:productType:boostsApplied:audioOrderPosition:audioOrderDeviceCount:]
+ -[SVXShadowLocalScore productType]
+ -[SVXSpeakableFragmentContext .cxx_destruct]
+ -[SVXSpeakableFragmentContext aceView]
+ -[SVXSpeakableFragmentContext initWithAceView:isExpository:taskTracker:]
+ -[SVXSpeakableFragmentContext isExpository]
+ -[SVXSpeakableFragmentContext taskTracker]
+ -[SVXSpeechSynthesizer hasStreamWithStreamId:]
+ GCC_except_table1199
+ GCC_except_table1216
+ GCC_except_table1217
+ GCC_except_table1274
+ GCC_except_table1546
+ GCC_except_table1688
+ GCC_except_table1689
+ GCC_except_table1728
+ GCC_except_table1736
+ GCC_except_table1737
+ GCC_except_table1769
+ GCC_except_table1793
+ GCC_except_table1794
+ GCC_except_table1881
+ GCC_except_table1883
+ GCC_except_table1884
+ GCC_except_table1993
+ GCC_except_table2060
+ GCC_except_table2061
+ GCC_except_table2194
+ GCC_except_table2205
+ GCC_except_table2207
+ GCC_except_table2212
+ GCC_except_table2225
+ GCC_except_table2227
+ GCC_except_table2392
+ GCC_except_table2517
+ GCC_except_table2520
+ GCC_except_table2524
+ GCC_except_table2526
+ GCC_except_table2528
+ GCC_except_table2530
+ GCC_except_table2549
+ GCC_except_table2550
+ GCC_except_table2585
+ GCC_except_table2681
+ GCC_except_table2685
+ GCC_except_table2687
+ GCC_except_table2690
+ GCC_except_table3001
+ GCC_except_table3156
+ GCC_except_table3231
+ GCC_except_table805
+ _NSSelectorFromString
+ _OBJC_CLASS_$_CDASchemaCDAClientEvent
+ _OBJC_CLASS_$_CDASchemaCDAClientEventMetadata
+ _OBJC_CLASS_$_CDASchemaCDADeviceSelectionDecisionMade
+ _OBJC_CLASS_$_CDASchemaCDADeviceSelectionScoreBoosts
+ _OBJC_CLASS_$_SCDADevice
+ _OBJC_CLASS_$_SISchemaErrorInfo
+ _OBJC_CLASS_$_SVXShadowComparisonLogger
+ _OBJC_CLASS_$_SVXShadowLocalScore
+ _OBJC_CLASS_$_SVXSpeakableFragmentContext
+ _OBJC_CLASS_$__TtC7SiriVOX20SVXSpeakableStreamer
+ _OBJC_IVAR_$_SVXAceViewHandler._speakableFragmentContexts
+ _OBJC_IVAR_$_SVXAceViewHandler._speakableStreamers
+ _OBJC_IVAR_$_SVXAceViewHandler._streamsAwaitingFirstSpeech
+ _OBJC_IVAR_$_SVXAceViewHandler._streamsAwaitingFollowUpSpeech
+ _OBJC_IVAR_$_SVXAceViewHandler._streamsWithDeferredStop
+ _OBJC_IVAR_$_SVXAceViewHandler._streamsWithProducedSpeech
+ _OBJC_IVAR_$_SVXMissingAssetActivationGuard._refreshLock
+ _OBJC_IVAR_$_SVXSession._isFollowUpQuestionPending
+ _OBJC_IVAR_$_SVXSession._isLASFollowUpWindowReleasePending
+ _OBJC_IVAR_$_SVXSessionManager._endSessionNotifyToken
+ _OBJC_IVAR_$_SVXSessionManager._shadowComparisonLogger
+ _OBJC_IVAR_$_SVXShadowComparisonLogger._answeredElectionToken
+ _OBJC_IVAR_$_SVXShadowComparisonLogger._decisionLatencyMs
+ _OBJC_IVAR_$_SVXShadowComparisonLogger._deviceSelectionWon
+ _OBJC_IVAR_$_SVXShadowComparisonLogger._electionCdaId
+ _OBJC_IVAR_$_SVXShadowComparisonLogger._emit
+ _OBJC_IVAR_$_SVXShadowComparisonLogger._latestElectionToken
+ _OBJC_IVAR_$_SVXShadowComparisonLogger._localScore
+ _OBJC_IVAR_$_SVXShadowComparisonLogger._loggedCdaId
+ _OBJC_IVAR_$_SVXShadowComparisonLogger._myriadCdaId
+ _OBJC_IVAR_$_SVXShadowComparisonLogger._selectionError
+ _OBJC_IVAR_$_SVXShadowLocalScore._audioOrderDeviceCount
+ _OBJC_IVAR_$_SVXShadowLocalScore._audioOrderPosition
+ _OBJC_IVAR_$_SVXShadowLocalScore._boostsApplied
+ _OBJC_IVAR_$_SVXShadowLocalScore._confidence
+ _OBJC_IVAR_$_SVXShadowLocalScore._deviceClass
+ _OBJC_IVAR_$_SVXShadowLocalScore._deviceGroup
+ _OBJC_IVAR_$_SVXShadowLocalScore._goodness
+ _OBJC_IVAR_$_SVXShadowLocalScore._productType
+ _OBJC_IVAR_$_SVXSpeakableFragmentContext._aceView
+ _OBJC_IVAR_$_SVXSpeakableFragmentContext._isExpository
+ _OBJC_IVAR_$_SVXSpeakableFragmentContext._taskTracker
+ _OBJC_METACLASS_$_SVXShadowComparisonLogger
+ _OBJC_METACLASS_$_SVXShadowLocalScore
+ _OBJC_METACLASS_$_SVXSpeakableFragmentContext
+ _OBJC_METACLASS_$__TtC7SiriVOX20SVXSpeakableStreamer
+ _SCDAToSISchemaUUID
+ _SVXMillisecondsFromMachDuration.once
+ _SVXMillisecondsFromMachDuration.timebase
+ __CLASS_METHODS__TtC7SiriVOX20SVXSpeakableStreamer
+ __CLASS_PROPERTIES__TtC7SiriVOX20SVXSpeakableStreamer
+ __DATA__TtC7SiriVOX20SVXSpeakableStreamer
+ __INSTANCE_METHODS__TtC7SiriVOX20SVXSpeakableStreamer
+ __IVARS__TtC7SiriVOX20SVXSpeakableStreamer
+ __METACLASS_DATA__TtC7SiriVOX20SVXSpeakableStreamer
+ __OBJC_$_INSTANCE_METHODS_SVXShadowComparisonLogger
+ __OBJC_$_INSTANCE_METHODS_SVXShadowLocalScore
+ __OBJC_$_INSTANCE_METHODS_SVXSpeakableFragmentContext
+ __OBJC_$_INSTANCE_VARIABLES_SVXShadowComparisonLogger
+ __OBJC_$_INSTANCE_VARIABLES_SVXShadowLocalScore
+ __OBJC_$_INSTANCE_VARIABLES_SVXSpeakableFragmentContext
+ __OBJC_$_PROP_LIST_SVXShadowLocalScore
+ __OBJC_$_PROP_LIST_SVXSpeakableFragmentContext
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SVXMyriadResponseDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT__TtP7SiriVOX28SVXSpeakableStreamerDelegate_
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS__TtP7SiriVOX28SVXSpeakableStreamerDelegate_
+ __OBJC_$_PROTOCOL_METHOD_TYPES__TtP7SiriVOX28SVXSpeakableStreamerDelegate_
+ __OBJC_CLASS_RO_$_SVXShadowComparisonLogger
+ __OBJC_CLASS_RO_$_SVXShadowLocalScore
+ __OBJC_CLASS_RO_$_SVXSpeakableFragmentContext
+ __OBJC_LABEL_PROTOCOL_$__TtP7SiriVOX28SVXSpeakableStreamerDelegate_
+ __OBJC_METACLASS_RO_$_SVXShadowComparisonLogger
+ __OBJC_METACLASS_RO_$_SVXShadowLocalScore
+ __OBJC_METACLASS_RO_$_SVXSpeakableFragmentContext
+ __OBJC_PROTOCOL_$__TtP7SiriVOX28SVXSpeakableStreamerDelegate_
+ __PROPERTIES__TtC7SiriVOX20SVXSpeakableStreamer
+ __PROTOCOL_INSTANCE_METHODS_OPT__TtP7SiriVOX28SVXSpeakableStreamerDelegate_
+ __PROTOCOL_INSTANCE_METHODS__TtP7SiriVOX28SVXSpeakableStreamerDelegate_
+ __PROTOCOL_METHOD_TYPES__TtP7SiriVOX28SVXSpeakableStreamerDelegate_
+ __PROTOCOL__TtP7SiriVOX28SVXSpeakableStreamerDelegate_
+ __SVXSessionGetRecentSpeechSynthesisEndTimestamp
+ ___122-[SVXAceViewHandler _speakAceView:speakableText:speakableStreamId:isFollowUpQuestion:isExpository:taskTracker:completion:]_block_invoke
+ ___33-[SVXShadowComparisonLogger init]_block_invoke
+ ___37-[SVXSession fireIdleTimerForTesting]_block_invoke
+ ___47-[SVXSessionIdleTimer fireSessionIdleTimersNow]_block_invoke
+ ___48-[SVXMyriadHostDevice scdaWillStartWithSession:]_block_invoke
+ ___48-[SVXSessionManager _registerEndSessionTestHook]_block_invoke
+ ___48-[SVXSessionManager _registerEndSessionTestHook]_block_invoke_2
+ ___52-[SVXAceViewHandler _endStreamWithIdentifier:error:]_block_invoke
+ ___52-[SVXSessionManager myriadSessionDidStartWithCdaId:]_block_invoke
+ ___57-[SVXHomePodUIBridgeClientDelegate _tearDownForDismissal]_block_invoke
+ ___60-[SVXSession _handleSpeechRecordingDidBeginOnAVRecordRoute:]_block_invoke
+ ___61-[SVXSessionIdleTimer startSessionIdleTimerWithTimeInterval:]_block_invoke_2
+ ___63-[SVXAceViewHandler speakableStreamer:didProduceSpeakableText:]_block_invoke
+ ___63-[SVXAceViewHandler speakableStreamer:didProduceSpeakableText:]_block_invoke_2
+ ___65-[SVXSession taskTrackingCenter:didBeginTrackingTaskWithContext:]_block_invoke
+ ___79-[SVXSession _handleStartListenAfterSpeaking:record:taskTracker:atEndOfSpeech:]_block_invoke
+ ___93-[SVXAceViewHandler streamingConsumerDidFinishStreamingWithIdentifier:error:attributionData:]_block_invoke
+ ___SVXMillisecondsFromMachDuration_block_invoke
+ ___block_descriptor_32_e33_v16?0"CDASchemaCDAClientEvent"8l
+ ___block_descriptor_40_e8_32bs_e73_v32?0"DeviceSelectionDevice"8"DeviceSelectionLocalScore"16"NSError"24l
+ ___block_descriptor_48_e8_32s40w_e8_v12?0i8l
+ ___block_descriptor_57_e8_32s40s48w_e33_v16?0"SVXServiceCommandResult"8l
+ ___block_descriptor_57_e8_32s40s_e67_v32?0"DeviceSelectionDevice"8"SVXShadowLocalScore"16"NSError"24l
+ ___block_descriptor_64_e8_32s40s48w_e5_v8?0l
+ ___block_descriptor_65_e8_32s40s48s_e34_v16?0"<SVXTaskContextMutating>"8l
+ ___block_descriptor_82_e8_32s40s48s56s64s72s_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s64s72s
+ ___copy_helper_block_e8_32s40s48w
+ ___swift_allocate_value_buffer
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_project_value_buffer
+ __swiftImmortalRefCount
+ __swift_stdlib_malloc_size
+ __swift_stdlib_reportUnimplementedInitializer
+ _flat unique 7SiriVOX28SVXSpeakableStreamerDelegate_p
+ _malloc_size
+ _memcpy
+ _notify_cancel
+ _notify_register_dispatch
+ _objc_msgSend$_chunkHasSpeakableText:
+ _objc_msgSend$_deactivateAfterLASAttendingStopped
+ _objc_msgSend$_endStreamWithIdentifier:error:
+ _objc_msgSend$_firstProducedSpeechDidStartForStreamIdentifier:
+ _objc_msgSend$_handleEndSessionTestHook
+ _objc_msgSend$_handleStartListenAfterSpeaking:record:taskTracker:atEndOfSpeech:
+ _objc_msgSend$_refreshSiriAvailability
+ _objc_msgSend$_registerEndSessionTestHook
+ _objc_msgSend$_releaseAudioSessionForFollowUpWindowIfRequestEnded
+ _objc_msgSend$_scoreBoostsFrom:
+ _objc_msgSend$_shouldIgnoreUnscopedCloseAssistant:
+ _objc_msgSend$_speakAceView:speakableText:speakableStreamId:isFollowUpQuestion:isExpository:taskTracker:completion:
+ _objc_msgSend$_speakableStreamerForStreamIdentifier:
+ _objc_msgSend$_tearDownForDismissal
+ _objc_msgSend$_usesSpeakableStreamer
+ _objc_msgSend$aceView
+ _objc_msgSend$af_IsLinwoodEnabled
+ _objc_msgSend$audioOrderDeviceCount
+ _objc_msgSend$audioOrderPosition
+ _objc_msgSend$boostsApplied
+ _objc_msgSend$cdaDeviceClassForSCDADeviceClass:andProducType:
+ _objc_msgSend$confidence
+ _objc_msgSend$consumeWithFragment:fragmentId:
+ _objc_msgSend$deviceClass
+ _objc_msgSend$deviceGroup
+ _objc_msgSend$discardBuffered
+ _objc_msgSend$discardPendingTTSPrewarm
+ _objc_msgSend$drain
+ _objc_msgSend$electionBegan
+ _objc_msgSend$fireIdleTimerForTesting
+ _objc_msgSend$fireSessionIdleTimersNow
+ _objc_msgSend$goodness
+ _objc_msgSend$hasStreamWithStreamId:
+ _objc_msgSend$initWithAceView:isExpository:taskTracker:
+ _objc_msgSend$initWithEmit:
+ _objc_msgSend$initWithGoodness:confidence:deviceGroup:deviceClass:productType:boostsApplied:audioOrderPosition:audioOrderDeviceCount:
+ _objc_msgSend$languageString
+ _objc_msgSend$myriadReported
+ _objc_msgSend$myriadSessionDidStartWithCdaId:
+ _objc_msgSend$outcome
+ _objc_msgSend$preferredSpeakableTextVoice
+ _objc_msgSend$productType
+ _objc_msgSend$recordAnswerForElection:won:localScore:error:machDuration:
+ _objc_msgSend$scheduleTTSPrewarm:
+ _objc_msgSend$selectDeviceReportingLocalScoreForRole:withSignals:completion:
+ _objc_msgSend$sessionId
+ _objc_msgSend$setAlarmOrTimerFiringBoost:
+ _objc_msgSend$setAttentionOverride:
+ _objc_msgSend$setAudioOrderDeviceCount:
+ _objc_msgSend$setAudioOrderPosition:
+ _objc_msgSend$setCdaId:
+ _objc_msgSend$setCode:
+ _objc_msgSend$setConfidence:
+ _objc_msgSend$setDecision:
+ _objc_msgSend$setDecisionLatencyInMs:
+ _objc_msgSend$setDeviceAdjustmentBoost:
+ _objc_msgSend$setDeviceClass:
+ _objc_msgSend$setDeviceGroup:
+ _objc_msgSend$setDeviceSelectionDecisionMade:
+ _objc_msgSend$setExpectsCoreResponse:
+ _objc_msgSend$setGoodness:
+ _objc_msgSend$setGoodnessScoreBoosts:
+ _objc_msgSend$setInEarOverride:
+ _objc_msgSend$setLiftTimeBoost:
+ _objc_msgSend$setMediaPlaybackActiveBoost:
+ _objc_msgSend$setMediaPlaybackRecentPlaybackBoost:
+ _objc_msgSend$setOutcome:
+ _objc_msgSend$setPerceptionBoost:
+ _objc_msgSend$setPlatformBoost:
+ _objc_msgSend$setProductType:
+ _objc_msgSend$setRaiseToWakeBoost:
+ _objc_msgSend$setRecencyBoost:
+ _objc_msgSend$setUnlockTimeBoost:
+ _objc_msgSend$setWatchGestureBoost:
+ _objc_msgSend$setWatchLoudnessThresholdOverride:
+ _objc_msgSend$siriDismissedForRelaunch
+ _os_variant_has_internal_content
+ _swift_bridgeObjectRelease_n
+ _swift_coroFrameAlloc
+ _swift_getObjectType
+ _swift_slowDealloc
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_unknownObjectWeakAssign
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic $s7SiriVOX28SVXSpeakableStreamerDelegateP
+ _symbolic _____ 7SiriVOX20SVXSpeakableStreamerC
+ _symbolic ______pSgXw 7SiriVOX28SVXSpeakableStreamerDelegateP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
- GCC_except_table1178
- GCC_except_table1193
- GCC_except_table1249
- GCC_except_table1520
- GCC_except_table1662
- GCC_except_table1663
- GCC_except_table1700
- GCC_except_table1708
- GCC_except_table1709
- GCC_except_table1741
- GCC_except_table1849
- GCC_except_table1851
- GCC_except_table1852
- GCC_except_table1959
- GCC_except_table2130
- GCC_except_table2141
- GCC_except_table2143
- GCC_except_table2148
- GCC_except_table2161
- GCC_except_table2163
- GCC_except_table2322
- GCC_except_table2446
- GCC_except_table2448
- GCC_except_table2451
- GCC_except_table2453
- GCC_except_table2455
- GCC_except_table2457
- GCC_except_table2475
- GCC_except_table2476
- GCC_except_table2606
- GCC_except_table2610
- GCC_except_table2612
- GCC_except_table2615
- GCC_except_table2922
- GCC_except_table3077
- GCC_except_table3152
- GCC_except_table804
- ___38-[SVXAceViewHandler invalidateStreams]_block_invoke
- ___49-[SVXHomePodUIBridgeClientDelegate siriDismissed]_block_invoke
- ___65-[SVXSession _handleStartListenAfterSpeaking:record:taskTracker:]_block_invoke
- ___71-[SVXAceViewHandler handleAceView:isExpository:taskTracker:completion:]_block_invoke
- ___block_descriptor_40_e8_32s_e47_v32?0?<v?"SVXServiceCommandResult">8Q16^B24l
- ___block_descriptor_41_e8_32s_e43_v24?0"DeviceSelectionDevice"8"NSError"16l
- ___block_descriptor_64_e8_32s40s48s_e34_v16?0"<SVXTaskContextMutating>"8l
- _objc_msgSend$selectDeviceForRole:withSignals:completion:
CStrings:
+ "#SpeakableStreamer created for stream %{public}s"
+ "%s #activation Anchoring recording to speech synthesis end %lf s ago"
+ "%s #activation No usable speech synthesis end time (begin %llu, end %llu, now %llu)"
+ "%s #activation Speech synthesis ended %lf s ago, too old to anchor recording"
+ "%s #deviceSelection #shadow Logged %{public}@ under cdaId %@."
+ "%s #deviceSelection #shadow No cdaId for this election; not logging the comparison."
+ "%s #deviceSelection #shadow No column for boost %{public}@; omitted."
+ "%s #missingAssets - Re-read Siri Availability before declining: %@"
+ "%s #tts Speakable streamer produced text with no fragment to speak it for stream %@"
+ "%s %@ preferred voice %@ (%@) for %@, isLinwoodEnabled = %d"
+ "%s A question that nothing listens after was queued; the mic opens when the speech ends."
+ "%s Ignored %@ because it has no refId and the current request's answer is still being presented."
+ "%s LAS attending stopped without activation while request %@ is active — waiting for it to end"
+ "%s LAS follow-up window open, waiting for the request to end before releasing the audio session"
+ "%s Not arming listen-after-speaking for a device setup scene"
+ "%s Relaunch deactivation: not telling UIBridge the session ended"
+ "%s Skipping Myriad for a server command re-arm."
+ "%s Test hook: firing the session idle timer now"
+ "%s Test hook: ignored, no current session"
+ "%s Test hook: no session idle timer is pending."
+ "-[SVXAceViewHandler _speakAceView:speakableText:speakableStreamId:isFollowUpQuestion:isExpository:taskTracker:completion:]"
+ "-[SVXAceViewHandler _speakAceView:speakableText:speakableStreamId:isFollowUpQuestion:isExpository:taskTracker:completion:]_block_invoke"
+ "-[SVXAceViewHandler speakableStreamer:didProduceSpeakableText:]"
+ "-[SVXSession _handleStartListenAfterSpeaking:record:taskTracker:atEndOfSpeech:]"
+ "-[SVXSession _releaseAudioSessionForFollowUpWindowIfRequestEnded]"
+ "-[SVXSession fireIdleTimerForTesting]_block_invoke"
+ "-[SVXSession taskTrackingCenter:didBeginTrackingTaskWithContext:]_block_invoke"
+ "-[SVXSessionIdleTimer fireSessionIdleTimersNow]_block_invoke"
+ "-[SVXSessionManager _handleEndSessionTestHook]"
+ "-[SVXShadowComparisonLogger _scoreBoostsFrom:]"
+ "-[SVXShadowComparisonLogger myriadReported]"
+ "CDADEVICESELECTIONOUTCOME_CANCELED"
+ "CDADEVICESELECTIONOUTCOME_DECIDED"
+ "CDADEVICESELECTIONOUTCOME_ERRORED"
+ "CDADEVICESELECTIONOUTCOME_NOT_RUN"
+ "CDADEVICESELECTIONOUTCOME_TIMED_OUT"
+ "CDADEVICESELECTIONOUTCOME_UNKNOWN"
+ "Follow-up Window Opened"
+ "Ignoring"
+ "SiriVOX.SVXSpeakableStreamer"
+ "Using"
+ "_SVXSessionGetRecentSpeechSynthesisEndTimestamp"
+ "alarmOrTimerFiring"
+ "attention"
+ "audioOrderPosition"
+ "com.apple.siridebug.endsession"
+ "deviceAdjustment"
+ "errored"
+ "inEar"
+ "init()"
+ "liftTimeBoost"
+ "mediaPlaybackActive"
+ "mediaPlaybackRecentPlayback"
+ "perception"
+ "platformBoost"
+ "raiseToWake"
+ "recencyBoost"
+ "relaunch"
+ "unlockTimeBoost"
+ "v12@?0i8"
+ "v16@?0@\"CDASchemaCDAClientEvent\"8"
+ "v32@?0@\"DeviceSelectionDevice\"8@\"DeviceSelectionLocalScore\"16@\"NSError\"24"
+ "v32@?0@\"DeviceSelectionDevice\"8@\"SVXShadowLocalScore\"16@\"NSError\"24"
+ "watchGesture"
+ "watchLoudnessThreshold"
- "-[SVXAceViewHandler handleAceView:isExpository:taskTracker:completion:]"
- "-[SVXAceViewHandler handleAceView:isExpository:taskTracker:completion:]_block_invoke"
- "-[SVXSession _handleStartListenAfterSpeaking:record:taskTracker:]"
- "v24@?0@\"DeviceSelectionDevice\"8@\"NSError\"16"
- "v32@?0@?<v@?@\"SVXServiceCommandResult\">8Q16^B24"
```
