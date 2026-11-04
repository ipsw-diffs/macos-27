## MediaToolbox

> `/System/Library/Frameworks/MediaToolbox.framework/Versions/A/MediaToolbox`

```diff

-3385.14.5.2.0
-  __TEXT.__text: 0x9e0ca8
+3395.5.1.0.0
+  __TEXT.__text: 0x9e4638
   __TEXT.__lazy_helpers: 0x2a0
   __TEXT.__objc_methlist: 0x22d4
-  __TEXT.__cstring: 0x649c4
+  __TEXT.__cstring: 0x64d74
   __TEXT.__const: 0x1d830
-  __TEXT.__gcc_except_tab: 0x1460
-  __TEXT.__oslogstring: 0x60a8a
+  __TEXT.__gcc_except_tab: 0x1484
+  __TEXT.__oslogstring: 0x61054
   __TEXT.__ustring: 0x24e
   __TEXT.__dlopen_cstrs: 0x21c
   __TEXT.__constg_swiftt: 0x234

   __TEXT.__swift_as_ret: 0x10
   __TEXT.__swift_as_cont: 0x30
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x1eff8
+  __TEXT.__unwind_info: 0x1f080
   __TEXT.__eh_frame: 0x408
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1ebe8
+  __DATA_CONST.__const: 0x1ed68
   __DATA_CONST.__objc_classlist: 0x1e0
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1cc0
+  __DATA_CONST.__objc_selrefs: 0x1cc8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x1a8
   __DATA_CONST.__objc_arraydata: 0x30
-  __DATA_CONST.__got: 0x42c8
-  __AUTH_CONST.__const: 0x3cb80
-  __AUTH_CONST.__cfstring: 0x4dde0
+  __DATA_CONST.__got: 0x4300
+  __AUTH_CONST.__const: 0x3cc30
+  __AUTH_CONST.__cfstring: 0x4e200
   __AUTH_CONST.__objc_const: 0x47a8
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__lazy_load_got: 0x38

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 39798
-  Symbols:   11915
-  CStrings:  18964
+  Functions: 39848
+  Symbols:   11947
+  CStrings:  19015
 
Symbols:
+ _FigAssetSetUpConnectionForURLAsync
+ _FigBufferedAirPlayOutputTimeCalculatorAdvanceRPEnd
+ _FigBufferedAirPlayOutputTimeCalculatorReAnchorRPIfBehind
+ _FigBufferedAirPlayOutputTimeCalculatorSetRPEnd
+ _FigBufferedAirPlayOutputTimeCalculatorSnapshotRPEndAsAnchorPoint
+ _FigSessionDataCreateLoudnessTypeDictionary
+ _FigSessionDataSpecifierIsAppleAudioLoudnessMetadata
+ _kCMSampleAttachmentKey_SMPTE_ST_2094_50Data
+ _kFigAudioQueueProperty_EnableOfflineLoudnessNormalization
+ _kFigAudioRenderPipelineProperty_EnableOfflineLoudnessNormalization
+ _kFigBufferedAirPlayAudioChainSubPipeNotification_EnableOfflineLoudnessNormalizationApplied
+ _kFigBufferedAirPlayOutputProperty_SupportsReceiverSideCALMLoudness
+ _kFigBufferedAirPlaySubPipeManagerCreateOption_SupportsReceiverSideCALMLoudness
+ _kFigEndPointPlaybackSessionKey_LoudnessInfo
+ _kFigEndpointPlaybackSessionProxiedProperty_LoudnessInfo
+ _kFigEndpointPlaybackSessionProxiedProperty_PrefersAudioVideoVariants
+ _kFigEndpointStreamProperty_SupportsReceiverSideCALMLoudness
+ _kFigHTTPRequestCreateOption_PreconnectOnly
+ _kFigISOUserDataKey_ContentTypeForLoudnessControl
+ _kFigLoudnessControlMode_Advertisement
+ _kFigLoudnessControlMode_UseItemMeasurement
+ _kFigLoudnessControlMode_UseSequenceMeasurement
+ _kFigPlaybackItemProperty_ContentLibraryLoudnessTarget
+ _kFigPlaybackItemProperty_ContentTypeForLoudnessControl
+ _kFigPlaybackItemProperty_LoudnessControlMode
+ _kFigPlaybackItemProperty_PrefersAudioVideoVariants
+ _kFigPlayerProperty_AppliesLoudnessAdjustmentsAutomatically
+ _kFigPlayerSetRateOption_ClientSetRateUpTime
+ _kFigReportingEventKey_AssetToClientSetRateMilliseconds
+ _kFigSampleBufferAttachmentKey_ContentTypeForLoudnessControl
+ _kFigStdAssetProperty_ContentTypeForLoudnessControl
+ _kFigStdTrackProperty_ContentTypeForLoudnessControl
+ _kFigTrackProperty_ContentTypeForLoudnessControl
+ _kFigUserDataKey_ContentTypeForLoudnessControl
+ _kLoudnessInfoDictionary_ContentTypeKey
- _FigBufferedAirPlayOutputTimeCalculatorSetLastKnownOPTS
- _kCMSampleAttachmentKey_SMPTE2094_50Data
- _kFigPlaybackItemProperty_SuppressesAudioOnlyVariants
CStrings:
+ "%@-%@"
+ "<<<< Boss >>>> %s: <%p|%{public}s> Reusing render pipeline %p (it's in both the add and remove lists) => will tell mentors to cancel previous output"
+ "<<<< FAQRP >>>> %s: (%p %{public}s) timebase anchor is %.3f in the past (sourceTime %.3f, sourceTimeNow %.3f); re-anchoring start from mediaTime %.3f, hostTime %.3f to mediaTime %.3f, hostTime %.3f (deltas: media %+.3f, host %+.3f)"
+ "<<<< FigBufferedAirPlayAudioChainSubPipeTranscode >>>> %s: [%p] %{public}s setLoudnessInfo hasCALMInfo=%c receiverWillApply=%c LoudnessInfo=%@"
+ "<<<< FigBufferedAirPlayDomainTransitionSubPipeManager >>>> %s: [%p] %@ anchored transition false->true (RP end tracking now active)"
+ "<<<< FigBufferedAirPlayDomainTransitionSubPipeManager >>>> %s: [%p] %@ reset: anchored transition true->false (RP end tracking now inactive)"
+ "<<<< FigBufferedAirPlayOutput >>>> %s: [%p] %{public}s SetRate callback err %d outputErr %d rate %1.2f @ context->mediaTime %1.3f mediaTime %1.3f rateScaledMediaTime %1.3f, hosttime: %1.3f"
+ "<<<< FigBufferedAirPlayOutputProxy >>>> %s: [%p] %{public}s flush: resetting TimeCalculator (BAO timeline restarts at zero) and re-preparing registered RPs"
+ "<<<< FigBufferedAirPlayOutputProxy >>>> %s: [%p] %{public}s rpID[%@]%s connectRenderPipelineToBAO: %s (outgoingRP=%@)"
+ "<<<< FigBufferedAirPlayOutputTimeCalculator >>>> %s: [BAOLinearStartTimeCalc:%p] Committed anchorPoint=%1.3f from outgoing RP=%@"
+ "<<<< FigBufferedAirPlayOutputTimeCalculator >>>> %s: [BAOLinearStartTimeCalc:%p] No recorded end for outgoing RP=%@; anchorPoint unchanged"
+ "<<<< FigBufferedAirPlayOutputTimeCalculator >>>> %s: [BAOLinearStartTimeCalc:%p] No timebase for RP=%@. Creating identity timebase."
+ "<<<< FigBufferedAirPlayOutputTimeCalculator >>>> %s: [BAOLinearStartTimeCalc:%p] No timebase for inRpID=%@. Created derivedTimebase %p"
+ "<<<< FigBufferedAirPlayOutputTimeCalculator >>>> %s: [BAOLinearStartTimeCalc:%p] Re-anchored RP=%@: sbuf RP-time %1.3f was behind anchorPoint -> BAO %1.3f"
+ "<<<< FigBufferedAirPlayOutputTimeCalculator >>>> %s: [BAOLinearStartTimeCalc:%p] Set RP=%@ end to BAO %1.3f (explicit, may move backward)"
+ "<<<< FigPlayer_AP >>>> %s: [%p] %{public}s Interstitial Player waiting for the primary Player to create bufferedAirPlayOutput"
+ "AVTCancelTime"
+ "AVTToggleTime"
+ "AVTVidIntentTimeWC"
+ "Advertisement"
+ "AppliesLoudnessAdjustmentsAutomatically"
+ "ClientSetRateUpTime"
+ "ClipFeedIndex"
+ "ClipPriorityList"
+ "ContentLibraryLoudnessTarget"
+ "ContentTypeForLoudnessControl"
+ "CoreMedia/PlaybackWithAutoCaptionGenerationForAllEN"
+ "EnableOfflineLoudnessNormalization"
+ "EnableOfflineLoudnessNormalizationApplied"
+ "FBSP_ContentTypeForLoudnessControl"
+ "FHRP_PreconnectOnly"
+ "FigBufferedAirPlayOutputTimeCalculatorSetRPEnd"
+ "FigBufferedAirPlayOutputTimeCalculatorSnapshotRPEndAsAnchorPoint"
+ "LoudnessControlMode"
+ "PlaybackWithAutoCaptionGenerationForAllEN"
+ "SupportsReceiverSideCALMLoudness"
+ "UseItemMeasurement"
+ "UseSequenceMeasurement"
+ "VidMediaTimeRndrDelay"
+ "ad"
+ "adjust to album loudness"
+ "advertisement"
+ "bapspTranscode_setLoudnessInfo"
+ "com.apple.audio-loudness-type"
+ "completion"
+ "content type"
+ "content type flags"
+ "content type version"
+ "continuous handoff, anchoring to outgoing RP end"
+ "ctlc"
+ "doNotReadaheadCryptKeys"
+ "en-AU"
+ "en-GB"
+ "en-IE"
+ "en-IN"
+ "en-NZ"
+ "en-SG"
+ "en-ZA"
+ "fbap_mixcalc_convertRPTimeToBAOTimeLocked"
+ "fbapdtsp_reset"
+ "fresh start, resetting calculator"
+ "httpSession"
+ "library loudness"
+ "prefersAudioVideoVariants"
- "<<<< FigBufferedAirPlayOutput >>>> %s: [%p] %{public}s SetRate callback err %d outputErr %d rate %1.2f @ context->mediaTime %1.3f mediaTime %1.3f, hosttime: %1.3f"
- "<<<< FigBufferedAirPlayOutputTimeCalculator >>>> %s: [BAOLinearStartTimeCalc:%p] No timebase for RP=%@. Creating with lastKnownOPTS=%1.3f"
- "<<<< FigBufferedAirPlayOutputTimeCalculator >>>> %s: [BAOLinearStartTimeCalc:%p] No timebase for inRpID=%@. Created one %p, lastKnownOPTS=%1.3f"
- "<<<< FigBufferedAirPlayOutputTimeCalculator >>>> %s: [BAOLinearStartTimeCalc:%p] RP=%@ has no overlap info. Realigning timebase with lastKnownOPTS=%1.3f"
- "<<<< FigBufferedAirPlayOutputTimeCalculator >>>> %s: [BAOLinearStartTimeCalc:%p] RP=%@ has overlap info. Timebase alignment verified."
- "AVTMediaRndrTimeDelay"
- "AVTUptimeDur"
- "AVTVariantType"
- "CA"
- "FigBufferedAirPlayOutputTimeCalculatorConvertRPTimeToBAOTime"
- "SuppressesAudioOnlyVariants"
- "US"
- "VidRendMediaRndrDelay"
```
