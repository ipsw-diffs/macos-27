## SiriVOX

> `/System/Library/PrivateFrameworks/SiriVOX.framework/Versions/A/SiriVOX`

```diff

-3605.19.1.0.0
-  __TEXT.__text: 0x8abf4
-  __TEXT.__objc_methlist: 0x8bf8
-  __TEXT.__const: 0x12c
+3610.11.1.0.0
+  __TEXT.__text: 0x8d390
+  __TEXT.__objc_methlist: 0x8dd8
+  __TEXT.__const: 0x138
   __TEXT.__constg_swiftt: 0x8c
   __TEXT.__swift5_typeref: 0x97
   __TEXT.__swift5_fieldmd: 0x38
   __TEXT.__swift5_types: 0x8
-  __TEXT.__cstring: 0x1175f
+  __TEXT.__cstring: 0x11ace
   __TEXT.__swift5_capture: 0x78
   __TEXT.__swift5_reflstr: 0x16
-  __TEXT.__gcc_except_tab: 0x5e8
-  __TEXT.__oslogstring: 0x8be9
+  __TEXT.__gcc_except_tab: 0x680
+  __TEXT.__oslogstring: 0x91cd
   __TEXT.__dlopen_cstrs: 0xda
-  __TEXT.__unwind_info: 0x2cc0
+  __TEXT.__unwind_info: 0x2dd0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xff8
-  __DATA_CONST.__objc_classlist: 0x678
+  __DATA_CONST.__const: 0x1078
+  __DATA_CONST.__objc_classlist: 0x680
   __DATA_CONST.__objc_catlist: 0x48
-  __DATA_CONST.__objc_protolist: 0x2d8
+  __DATA_CONST.__objc_protolist: 0x2e0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3db8
+  __DATA_CONST.__objc_selrefs: 0x3eb8
   __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0x4a8
-  __DATA_CONST.__objc_arraydata: 0x980
-  __DATA_CONST.__got: 0x778
-  __AUTH_CONST.__const: 0x2cc8
-  __AUTH_CONST.__cfstring: 0x5f60
-  __AUTH_CONST.__objc_const: 0x13900
+  __DATA_CONST.__objc_superrefs: 0x4b0
+  __DATA_CONST.__objc_arraydata: 0x990
+  __DATA_CONST.__got: 0x798
+  __AUTH_CONST.__const: 0x2df8
+  __AUTH_CONST.__cfstring: 0x6000
+  __AUTH_CONST.__objc_const: 0x13c38
   __AUTH_CONST.__objc_arrayobj: 0x78
-  __AUTH_CONST.__objc_intobj: 0xe58
+  __AUTH_CONST.__objc_intobj: 0xe70
   __AUTH_CONST.__objc_dictobj: 0x348
-  __AUTH_CONST.__auth_got: 0x570
-  __AUTH.__objc_data: 0x4150
+  __AUTH_CONST.__auth_got: 0x590
+  __AUTH.__objc_data: 0x41a0
   __AUTH.__data: 0x30
-  __DATA.__objc_ivar: 0xccc
-  __DATA.__data: 0x2260
+  __DATA.__objc_ivar: 0xd18
+  __DATA.__data: 0x22c0
   __DATA.__bss: 0x248
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3215
-  Symbols:   8322
-  CStrings:  2259
+  Functions: 3280
+  Symbols:   8478
+  CStrings:  2305
 
Symbols:
+ -[SVXHomePodUIBridgeClientDelegate _handleDirectedSpeechDetected]
+ -[SVXHomePodUIBridgeClientDelegate _handleDirectedSpeechSelected]
+ -[SVXHomePodUIBridgeClientDelegate _handleSpeechMitigated]
+ -[SVXHomePodUIBridgeClientDelegate _openFollowUpWindow]
+ -[SVXHomePodUIBridgeClientDelegate _resetLASWindowState]
+ -[SVXHomePodUIBridgeClientDelegate _sendPrompt]
+ -[SVXHomePodUIBridgeClientDelegate _tearDownLASWindow]
+ -[SVXHomePodUIBridgeClientDelegate _unduckTTSIfNeeded]
+ -[SVXHomePodUIBridgeClientDelegate attendingStatusChanged:]
+ -[SVXHomePodUIBridgeClientDelegate didDetectSameUserSpeech]
+ -[SVXHomePodUIBridgeClientDelegate didDetectUserSpeech]
+ -[SVXHomePodUIBridgeClientDelegate didDuckTTS]
+ -[SVXHomePodUIBridgeClientDelegate duckTTSToVolume:rampTime:completion:]
+ -[SVXHomePodUIBridgeClientDelegate orchestrationDidPresentResponseFullyInApp]
+ -[SVXHomePodUIBridgeClientDelegate pauseTTS]
+ -[SVXHomePodUIBridgeClientDelegate playbackFinished]
+ -[SVXHomePodUIBridgeClientDelegate promptPending]
+ -[SVXHomePodUIBridgeClientDelegate resumeTTS]
+ -[SVXHomePodUIBridgeClientDelegate sessionDismissed]
+ -[SVXHomePodUIBridgeClientDelegate sessionStateHandler:didTransitionFromState:toState:forEvent:machAbsoluteTime:]
+ -[SVXHomePodUIBridgeClientDelegate sessionStateHandler]
+ -[SVXHomePodUIBridgeClientDelegate setDidDuckTTS:]
+ -[SVXHomePodUIBridgeClientDelegate setPlaybackFinished:]
+ -[SVXHomePodUIBridgeClientDelegate setPromptPending:]
+ -[SVXHomePodUIBridgeClientDelegate setSessionDismissed:]
+ -[SVXHomePodUIBridgeClientDelegate setSessionStateHandler:]
+ -[SVXHomePodUIBridgeClientDelegate setSpeculativeLASActivationContext:]
+ -[SVXHomePodUIBridgeClientDelegate setSruifClient:]
+ -[SVXHomePodUIBridgeClientDelegate showAssetsDownloadNotificationPrompt]
+ -[SVXHomePodUIBridgeClientDelegate siriDismissed]
+ -[SVXHomePodUIBridgeClientDelegate speculativeLASActivationContext]
+ -[SVXHomePodUIBridgeClientDelegate sruifClient]
+ -[SVXHomePodUIBridgeClientDelegate willStartPlayback]
+ -[SVXMissingAssetActivationDecision declineError]
+ -[SVXMissingAssetActivationDecision initWithDeclineError:promptLocalizationKey:]
+ -[SVXMissingAssetActivationGuard setSiriAvailability:]
+ -[SVXMissingAssetActivationGuard siriAvailability]
+ -[SVXSession _isContinuousConversationActive]
+ -[SVXSession _showListeningIfFollowUpWindowOpen]
+ -[SVXSession endContinuousConversation]
+ -[SVXSession speechSynthesizerDidFinishPlaybackWithTaskTracker:queueIsEmpty:]
+ -[SVXSession uiBridgeClientDidOpenFollowUpWindow]
+ -[SVXSession uiBridgeClientDidRestoreFollowUpWindow]
+ -[SVXSessionManager _currentOrchestrationMode]
+ -[SVXSessionManager _handleSiriCapabilitiesChanged]
+ -[SVXSessionManager _invalidateStaleSessionForOrchestrationModeChange]
+ -[SVXSessionManager _isDeviceSelectionShadowMode]
+ -[SVXSessionManager _refreshOrchestrationMode]
+ -[SVXSessionManager _siriCapabilitiesDidChange]
+ -[SVXSessionManager dealloc]
+ -[SVXShadowRecencyDonor .cxx_destruct]
+ -[SVXShadowRecencyDonor activationBegan]
+ -[SVXShadowRecencyDonor initWithNow:continuousUptime:donate:]
+ -[SVXShadowRecencyDonor init]
+ -[SVXShadowRecencyDonor myriadWon]
+ -[SVXSpeechSynthesisUtils isPhaticPrompt:]
+ -[SVXSpeechSynthesizer _handleContextFailedBeforeStreamStart:error:]
+ -[SVXSpeechSynthesizer _handleSpeakingContextFinishedWithoutAudio:]
+ -[SVXSpeechSynthesizer _holdAudioSessionAssertion:forStreamId:]
+ -[SVXSpeechSynthesizer _releaseAllStreamAudioSessionAssertions]
+ -[SVXSpeechSynthesizer _releaseAudioSessionAssertionForStreamId:]
+ GCC_except_table1178
+ GCC_except_table1193
+ GCC_except_table1249
+ GCC_except_table1520
+ GCC_except_table1662
+ GCC_except_table1663
+ GCC_except_table1700
+ GCC_except_table1708
+ GCC_except_table1709
+ GCC_except_table1741
+ GCC_except_table1849
+ GCC_except_table1851
+ GCC_except_table1852
+ GCC_except_table1959
+ GCC_except_table2130
+ GCC_except_table2141
+ GCC_except_table2143
+ GCC_except_table2148
+ GCC_except_table2161
+ GCC_except_table2163
+ GCC_except_table2322
+ GCC_except_table2446
+ GCC_except_table2448
+ GCC_except_table2451
+ GCC_except_table2453
+ GCC_except_table2455
+ GCC_except_table2457
+ GCC_except_table2475
+ GCC_except_table2476
+ GCC_except_table2606
+ GCC_except_table2610
+ GCC_except_table2612
+ GCC_except_table2615
+ GCC_except_table2922
+ GCC_except_table3077
+ GCC_except_table3152
+ GCC_except_table541
+ GCC_except_table559
+ GCC_except_table571
+ GCC_except_table804
+ _AFDeviceSelectionParticipating
+ _NSDebugDescriptionErrorKey
+ _NSStringFromAFSiriOrchestrationMode
+ _NSStringFromAFSiriUnavailabilityReasons
+ _OBJC_CLASS_$_AFDialogPhase
+ _OBJC_CLASS_$_DeviceSelectionSignalDonation
+ _OBJC_CLASS_$_SRUIFSiriSessionStateHandler
+ _OBJC_CLASS_$_SRUIFUIBridgeClient
+ _OBJC_CLASS_$_SVXShadowRecencyDonor
+ _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._didDuckTTS
+ _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._playbackFinished
+ _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._promptPending
+ _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._sessionDismissed
+ _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._sessionStateHandler
+ _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._speculativeLASActivationContext
+ _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._sruifClient
+ _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._sruifDelegateQueue
+ _OBJC_IVAR_$_SVXMissingAssetActivationDecision._declineError
+ _OBJC_IVAR_$_SVXSession._hasEndedContinuousConversation
+ _OBJC_IVAR_$_SVXSession._isAwaitingFollowUpActivation
+ _OBJC_IVAR_$_SVXSession._isLASFollowUpWindowOpen
+ _OBJC_IVAR_$_SVXSessionManager._contextOrchestrationMode
+ _OBJC_IVAR_$_SVXSessionManager._currentSessionNeedsRebuild
+ _OBJC_IVAR_$_SVXSessionManager._currentSessionOrchestrationMode
+ _OBJC_IVAR_$_SVXSessionManager._hasLoggedDeferredTeardown
+ _OBJC_IVAR_$_SVXSessionManager._orchestrationMode
+ _OBJC_IVAR_$_SVXSessionManager._shadowRecencyDonor
+ _OBJC_IVAR_$_SVXShadowRecencyDonor._continuousUptime
+ _OBJC_IVAR_$_SVXShadowRecencyDonor._donate
+ _OBJC_IVAR_$_SVXShadowRecencyDonor._now
+ _OBJC_IVAR_$_SVXShadowRecencyDonor._pendingActivationDate
+ _OBJC_IVAR_$_SVXShadowRecencyDonor._pendingActivationUptime
+ _OBJC_IVAR_$_SVXSpeechSynthesizer._streamAudioSessionAssertions
+ _OBJC_METACLASS_$_SVXShadowRecencyDonor
+ _SVXDeclineErrorForSiriStatus
+ __OBJC_$_INSTANCE_METHODS_SVXShadowRecencyDonor
+ __OBJC_$_INSTANCE_VARIABLES_SVXShadowRecencyDonor
+ __OBJC_$_PROP_LIST_SVXMissingAssetActivationGuard
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SRUIFUIBridgeClientDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SRUIFSiriSessionStateHandlerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SRUIFUIBridgeClientDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SRUIFSiriSessionStateHandlerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SRUIFUIBridgeClientDelegate
+ __OBJC_$_PROTOCOL_REFS_SRUIFSiriSessionStateHandlerDelegate
+ __OBJC_$_PROTOCOL_REFS_SRUIFUIBridgeClientDelegate
+ __OBJC_CLASS_RO_$_SVXShadowRecencyDonor
+ __OBJC_LABEL_PROTOCOL_$_SRUIFSiriSessionStateHandlerDelegate
+ __OBJC_LABEL_PROTOCOL_$_SRUIFUIBridgeClientDelegate
+ __OBJC_METACLASS_RO_$_SVXShadowRecencyDonor
+ __OBJC_PROTOCOL_$_SRUIFSiriSessionStateHandlerDelegate
+ __OBJC_PROTOCOL_$_SRUIFUIBridgeClientDelegate
+ ___29-[SVXShadowRecencyDonor init]_block_invoke
+ ___29-[SVXShadowRecencyDonor init]_block_invoke_2
+ ___29-[SVXShadowRecencyDonor init]_block_invoke_3
+ ___29-[SVXShadowRecencyDonor init]_block_invoke_4
+ ___39-[SVXSession endContinuousConversation]_block_invoke
+ ___39-[SVXSessionManager initiateEmergency:]_block_invoke
+ ___47-[SVXSessionManager _siriCapabilitiesDidChange]_block_invoke
+ ___49-[SVXHomePodUIBridgeClientDelegate siriDismissed]_block_invoke
+ ___49-[SVXSession uiBridgeClientDidOpenFollowUpWindow]_block_invoke
+ ___52-[SVXSession uiBridgeClientDidRestoreFollowUpWindow]_block_invoke
+ ___53-[SVXHomePodUIBridgeClientDelegate willStartPlayback]_block_invoke
+ ___54-[SVXHomePodUIBridgeClientDelegate _unduckTTSIfNeeded]_block_invoke
+ ___58-[SVXHomePodUIBridgeClientDelegate _handleSpeechMitigated]_block_invoke
+ ___59-[SVXHomePodUIBridgeClientDelegate attendingStatusChanged:]_block_invoke
+ ___65-[SVXHomePodUIBridgeClientDelegate _handleDirectedSpeechDetected]_block_invoke
+ ___65-[SVXHomePodUIBridgeClientDelegate _handleDirectedSpeechSelected]_block_invoke
+ ___67-[SVXHomePodUIBridgeClientDelegate didPromptListeningAfterSpeaking]_block_invoke
+ ___70-[SVXSessionManager _invalidateStaleSessionForOrchestrationModeChange]_block_invoke
+ ___77-[SVXSession speechSynthesizerDidFinishPlaybackWithTaskTracker:queueIsEmpty:]_block_invoke
+ ___88-[SVXSessionManager _handleSession:didResignActiveWithDeactivationContext:activityUUID:]_block_invoke_2
+ ___block_descriptor_32_e13_"NSDate"8?0l
+ ___block_descriptor_32_e16_v16?0"NSDate"8l
+ ___block_descriptor_32_e5_d8?0l
+ ___block_descriptor_41_e8_32s_e43_v24?0"DeviceSelectionDevice"8"NSError"16l
+ ___block_descriptor_48_e8_32s40s_e8_v16?0q8l
+ ___block_descriptor_56_e8_32s40r48r_e5_v8?0l
+ ___block_descriptor_64_e8_32s40s48bs56r_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48bs_e17_v16?0"NSError"8l
+ ___copy_helper_block_e8_32s40s48b56r
+ ___destroy_helper_block_e8_32s40s48s56r
+ __siriCapabilitiesDidChange
+ _objc_msgSend$_currentOrchestrationMode
+ _objc_msgSend$_handleContextFailedBeforeStreamStart:error:
+ _objc_msgSend$_handleDirectedSpeechDetected
+ _objc_msgSend$_handleDirectedSpeechSelected
+ _objc_msgSend$_handleSiriCapabilitiesChanged
+ _objc_msgSend$_handleSpeakingContextFinishedWithoutAudio:
+ _objc_msgSend$_handleSpeechMitigated
+ _objc_msgSend$_holdAudioSessionAssertion:forStreamId:
+ _objc_msgSend$_invalidateStaleSessionForOrchestrationModeChange
+ _objc_msgSend$_isContinuousConversationActive
+ _objc_msgSend$_isDeviceSelectionShadowMode
+ _objc_msgSend$_openFollowUpWindow
+ _objc_msgSend$_refreshOrchestrationMode
+ _objc_msgSend$_releaseAllStreamAudioSessionAssertions
+ _objc_msgSend$_releaseAudioSessionAssertionForStreamId:
+ _objc_msgSend$_resetLASWindowState
+ _objc_msgSend$_sendPrompt
+ _objc_msgSend$_showListeningIfFollowUpWindowOpen
+ _objc_msgSend$_siriCapabilitiesDidChange
+ _objc_msgSend$_tearDownLASWindow
+ _objc_msgSend$_unduckTTSIfNeeded
+ _objc_msgSend$activationBegan
+ _objc_msgSend$audioSessionAssertion
+ _objc_msgSend$declineError
+ _objc_msgSend$desiredOrchestrationMode
+ _objc_msgSend$dialogPhaseForAceDialogPhase:
+ _objc_msgSend$didDuckTTS
+ _objc_msgSend$donateRecencySignalForActivationDate:isCloseWin:closeWinMargin:withCompletion:
+ _objc_msgSend$endContinuousConversation
+ _objc_msgSend$endForReason:
+ _objc_msgSend$initWithDeclineError:promptLocalizationKey:
+ _objc_msgSend$initWithNow:continuousUptime:donate:
+ _objc_msgSend$initWithStateHandler:delegateQueue:
+ _objc_msgSend$isErrorDialogPhase
+ _objc_msgSend$isPhaticPrompt:
+ _objc_msgSend$myriadWon
+ _objc_msgSend$playbackFinished
+ _objc_msgSend$promptPending
+ _objc_msgSend$promptedUserForInput
+ _objc_msgSend$sessionDismissed
+ _objc_msgSend$sessionShouldSkipLocalAudioDucking:
+ _objc_msgSend$setDidDuckTTS:
+ _objc_msgSend$setPlaybackFinished:
+ _objc_msgSend$setPromptPending:
+ _objc_msgSend$setSessionDismissed:
+ _objc_msgSend$setSessionStateHandler:
+ _objc_msgSend$setSiriAvailability:
+ _objc_msgSend$setSpeculativeLASActivationContext:
+ _objc_msgSend$setSruifClient:
+ _objc_msgSend$siriAvailability
+ _objc_msgSend$siriDismissed
+ _objc_msgSend$speculativeLASActivationContext
+ _objc_msgSend$speechSynthesizerDidFinishPlaybackWithTaskTracker:queueIsEmpty:
+ _objc_msgSend$sruifClient
+ _objc_msgSend$status
+ _objc_msgSend$stopAttending
+ _objc_msgSend$uiBridgeClientDidOpenFollowUpWindow
+ _objc_msgSend$uiBridgeClientDidRestoreFollowUpWindow
+ _objc_msgSend$willStartPlayback
+ _objc_setProperty_atomic
- -[SVXHomePodUIBridgeClientDelegate currentUserTurnID]
- -[SVXHomePodUIBridgeClientDelegate didPauseTTSForCurrentUserTurn]
- -[SVXHomePodUIBridgeClientDelegate isAttending]
- -[SVXHomePodUIBridgeClientDelegate setCurrentUserTurnID:]
- -[SVXHomePodUIBridgeClientDelegate setDidPauseTTSForCurrentUserTurn:]
- -[SVXHomePodUIBridgeClientDelegate setIsAttending:]
- -[SVXHomePodUIBridgeClientDelegate setUiBridgeClient:]
- -[SVXHomePodUIBridgeClientDelegate uiBridgeClient]
- -[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDetectedSpeechStart:]
- -[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDidDetectUserSpeechWithContext:]
- -[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDidFinalizeUserTurnWithContext:]
- -[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDidStartAttending]
- -[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDidStopAttendingUnexpectedlyWithReason:]
- -[SVXHomePodUIBridgeClientDelegate uiBridgeServiceReceivedSpeechMitigationResult:]
- -[SVXHomePodUIBridgeClientDelegate uiBridgeServiceWillStartAttending]
- -[SVXMissingAssetActivationDecision initWithShouldDeclineActivation:promptLocalizationKey:]
- -[SVXMissingAssetActivationDecision shouldDeclineActivation]
- -[SVXSession speechSynthesizerDidFinishPlayback]
- GCC_except_table1172
- GCC_except_table1187
- GCC_except_table1243
- GCC_except_table1514
- GCC_except_table1656
- GCC_except_table1657
- GCC_except_table1687
- GCC_except_table1695
- GCC_except_table1696
- GCC_except_table1727
- GCC_except_table1831
- GCC_except_table1833
- GCC_except_table1834
- GCC_except_table1937
- GCC_except_table2102
- GCC_except_table2127
- GCC_except_table2264
- GCC_except_table2387
- GCC_except_table2389
- GCC_except_table2391
- GCC_except_table2409
- GCC_except_table2410
- GCC_except_table2540
- GCC_except_table2544
- GCC_except_table2546
- GCC_except_table2549
- GCC_except_table2856
- GCC_except_table3012
- GCC_except_table3087
- GCC_except_table540
- GCC_except_table558
- GCC_except_table570
- GCC_except_table798
- _OBJC_CLASS_$_SUIBUIBridgeClient
- _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._currentUserTurnID
- _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._didPauseTTSForCurrentUserTurn
- _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._isAttending
- _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._uiBridgeClient
- _OBJC_IVAR_$_SVXMissingAssetActivationDecision._shouldDeclineActivation
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SUIBUIBridgeServiceDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_SUIBUIBridgeServiceDelegate
- __OBJC_$_PROTOCOL_REFS_SUIBUIBridgeServiceDelegate
- __OBJC_LABEL_PROTOCOL_$_SUIBUIBridgeServiceDelegate
- __OBJC_PROTOCOL_$_SUIBUIBridgeServiceDelegate
- ___48-[SVXSession speechSynthesizerDidFinishPlayback]_block_invoke
- ___69-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceWillStartAttending]_block_invoke
- ___71-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDetectedSpeechStart:]_block_invoke
- ___82-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDidDetectUserSpeechWithContext:]_block_invoke
- ___82-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDidFinalizeUserTurnWithContext:]_block_invoke
- ___82-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceReceivedSpeechMitigationResult:]_block_invoke
- ___90-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDidStopAttendingUnexpectedlyWithReason:]_block_invoke
- ___block_descriptor_40_e8_32s_e43_v24?0"DeviceSelectionDevice"8"NSError"16l
- ___block_descriptor_48_e8_32w_e5_v8?0l
- _objc_msgSend$currentUserTurnID
- _objc_msgSend$decision
- _objc_msgSend$didPauseTTSForCurrentUserTurn
- _objc_msgSend$initWithShouldDeclineActivation:promptLocalizationKey:
- _objc_msgSend$isInvocationUser
- _objc_msgSend$preheat
- _objc_msgSend$setCurrentUserTurnID:
- _objc_msgSend$setDidPauseTTSForCurrentUserTurn:
- _objc_msgSend$setIsAttending:
- _objc_msgSend$setUiBridgeClient:
- _objc_msgSend$shouldDeclineActivation
- _objc_msgSend$siriPrompted
- _objc_msgSend$speechSynthesizerDidFinishPlayback
- _objc_msgSend$stopAttendingForReason:
- _objc_msgSend$uiBridgeClient
- _objc_msgSend$userTurnID
CStrings:
+ "#Choreography Attending stopped, discarding pending LAS activation"
+ "#Choreography Created SRUIFUIBridgeClient"
+ "#Choreography Directed speech detected during LAS attending, activating follow-up"
+ "#Choreography Ignoring follow-up barrier after dismissal"
+ "#Choreography More audio starting — pausing follow-up window"
+ "#Choreography Playback already finished — starting follow-up window"
+ "#Choreography Sending SiriPrompted: rootRequestId=%{public}@"
+ "#Choreography Speech mitigated, restoring follow-up window"
+ "#Choreography attendingStatusChanged: %d"
+ "#Choreography didDetectUserSpeech (not the invoking user), ignoring for LAS"
+ "#Choreography duckTTSToVolume: %f"
+ "#Choreography failed to unduck TTS: %{public}@"
+ "#Choreography orchestrationDidPresentResponseFullyInApp: no HomePod UI, ignoring"
+ "#Choreography showAssetsDownloadNotificationPrompt: no HomePod UI, ignoring"
+ "#Choreography siriDismissed: rootRequestId=%{public}@"
+ "#Choreography unducking TTS"
+ "#Choreography verdict: directed speech selected"
+ "#Choreography verdict: speech mitigated"
+ "%@ (reasons: %@)"
+ "%s #deviceSelection #shadow Myriad won; donating recency."
+ "%s #deviceSelection #shadow Recency donation failed: %{public}@"
+ "%s #deviceSelection #shadow recorded %{public}s; Myriad decides."
+ "%s #missingAssets - Declining activation for source %@ (promptKey = %@, error = %{public}@)"
+ "%s #tts Empty first piece for streamId %@; starting the stream without text."
+ "%s Blocking listeningAfterSpeaking activation because the last Siri request resulted in an error dialog (isErrorDialogPhase = %d)"
+ "%s Ending continuous conversation after the current request"
+ "%s Ending continuous conversation — deactivating session"
+ "%s Ignoring playback end from an earlier request. (_currentRequestUUID = %@, playbackRequestUUID = %@)"
+ "%s LAS follow-up window open and request ended, showing listening"
+ "%s LAS follow-up window open, waiting for the request to end before showing listening"
+ "%s LAS follow-up window restored after mitigation"
+ "%s Not acquiring audio ducking coordination assertion: another device ducks this speaker."
+ "%s Not arming listen-after-speaking for the two-shot phatic prompt"
+ "%s Orchestration mode changed %@ -> %@ (rebuild = %d), invalidating session"
+ "%s Orchestration mode changed %@ -> %@ since the last context clear, clearing context"
+ "%s Orchestration mode changed mid-request, deferring session invalidation"
+ "%s Playback ended but more synthesis is queued; the response is not over."
+ "%s Releasing the audio session held for a stream. (streamId = %@, assertion = %@)"
+ "%s Speaking context finished without audio; reporting the audio end. (context = %@)"
+ "%s Stream never started; reporting its end here. (streamId = %@, error = %@)"
+ "%s taskTracker = %@, queueIsEmpty = %d"
+ "-[SVXSession _showListeningIfFollowUpWindowOpen]"
+ "-[SVXSession endContinuousConversation]_block_invoke"
+ "-[SVXSession speechSynthesizerDidFinishPlaybackWithTaskTracker:queueIsEmpty:]"
+ "-[SVXSession speechSynthesizerDidFinishPlaybackWithTaskTracker:queueIsEmpty:]_block_invoke"
+ "-[SVXSession uiBridgeClientDidRestoreFollowUpWindow]_block_invoke"
+ "-[SVXSessionManager _invalidateStaleSessionForOrchestrationModeChange]_block_invoke"
+ "-[SVXShadowRecencyDonor init]_block_invoke_4"
+ "-[SVXShadowRecencyDonor myriadWon]"
+ "-[SVXSpeechSynthesizer _handleContextFailedBeforeStreamStart:error:]"
+ "-[SVXSpeechSynthesizer _handleSpeakingContextFinishedWithoutAudio:]"
+ "-[SVXSpeechSynthesizer _releaseAudioSessionAssertionForStreamId:]"
+ "2"
+ "@\"NSDate\"8@?0"
+ "Siri is on but unavailable"
+ "Siri is restricted by a policy"
+ "Siri is turned off in Settings"
+ "assistantDisabled"
+ "com.apple.siri.SVXHomePodUIBridgeClientDelegate.sruif"
+ "d8@?0"
+ "lost"
+ "v16@?0@\"NSDate\"8"
+ "won"
- "\""
- "#Choreography - TTS was never paused for this turn, skipping resume"
- "#Choreography - TTS was never paused, skipping legacy resume"
- "#Choreography - UUID mismatch, skipping resume"
- "#Choreography Attending stopped unexpectedly — discarding pending LAS activation and deactivating session"
- "#Choreography Created SUIBUIBridgeClient"
- "#Choreography Directed speech detected during LAS attending — activating follow-up"
- "#Choreography SUIBUIBridgeServiceDelegate: uiBridgeServiceDidStartAttending"
- "#Choreography SUIBUIBridgeServiceDelegate: uiBridgeServiceDidStopAttendingUnexpectedly reason=%ld, hasPendingLAS=%d"
- "#Choreography SUIBUIBridgeServiceDelegate: uiBridgeServiceWillStartAttending"
- "#Choreography uiBridgeServiceDetectedSpeechStart: shouldDuckTTS=%d"
- "#Choreography uiBridgeServiceDidDetectUserSpeechWithContext: isInvocationUser=%d, hasPendingLAS=%d"
- "#Choreography uiBridgeServiceDidFinalizeUserTurnWithContext: decision=%ld"
- "#Choreography uiBridgeServiceReceivedSpeechMitigationResult: mitigationResult=%ld"
- "%s #missingAssets - Declining activation for source %@ (promptKey = %@)"
- "%s Blocking listeningAfterSpeaking activation because the last Siri request resulted in an error dialog"
- "-[SVXSession speechSynthesizerDidFinishPlayback]"
```
