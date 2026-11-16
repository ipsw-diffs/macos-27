## corespeechd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_ptr`

```diff

-3610.11.1.0.0
-  __TEXT.__text: 0x180f88
-  __TEXT.__auth_stubs: 0x1430
+3610.19.5.0.0
+  __TEXT.__text: 0x184078
+  __TEXT.__auth_stubs: 0x1440
   __TEXT.__lazy_helpers: 0xa8
-  __TEXT.__objc_stubs: 0x219c0
-  __TEXT.__objc_methlist: 0x1b9a0
+  __TEXT.__objc_stubs: 0x21d40
+  __TEXT.__objc_methlist: 0x1bd80
   __TEXT.__const: 0x398
   __TEXT.__dlopen_cstrs: 0x126
-  __TEXT.__gcc_except_tab: 0x2dc8
-  __TEXT.__cstring: 0x2f341
-  __TEXT.__objc_methname: 0x4754a
-  __TEXT.__oslogstring: 0x283aa
-  __TEXT.__objc_classname: 0x3970
-  __TEXT.__objc_methtype: 0x90a3
-  __TEXT.__unwind_info: 0x7200
-  __DATA_CONST.__const: 0x65f0
-  __DATA_CONST.__cfstring: 0x8a20
-  __DATA_CONST.__objc_classlist: 0x9c8
+  __TEXT.__gcc_except_tab: 0x2de4
+  __TEXT.__cstring: 0x2f757
+  __TEXT.__objc_methname: 0x47fed
+  __TEXT.__oslogstring: 0x28bdb
+  __TEXT.__objc_classname: 0x39e8
+  __TEXT.__objc_methtype: 0x9195
+  __TEXT.__unwind_info: 0x72c8
+  __DATA_CONST.__const: 0x65e0
+  __DATA_CONST.__cfstring: 0x8a60
+  __DATA_CONST.__objc_classlist: 0x9d0
   __DATA_CONST.__objc_catlist: 0x30
-  __DATA_CONST.__objc_protolist: 0x5c0
+  __DATA_CONST.__objc_protolist: 0x5d8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0xc8
-  __DATA_CONST.__objc_superrefs: 0x800
+  __DATA_CONST.__objc_superrefs: 0x808
   __DATA_CONST.__objc_arraydata: 0x248
   __DATA_CONST.__objc_dictobj: 0x2a8
   __DATA_CONST.__objc_floatobj: 0x590
   __DATA_CONST.__objc_intobj: 0xd20
   __DATA_CONST.__objc_arrayobj: 0x168
   __DATA_CONST.__objc_doubleobj: 0x60
-  __DATA_CONST.__auth_got: 0xa30
-  __DATA_CONST.__got: 0x13d8
+  __DATA_CONST.__auth_got: 0xa38
+  __DATA_CONST.__got: 0x13e0
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA.__objc_const: 0x2b528
-  __DATA.__objc_selrefs: 0xccd0
-  __DATA.__objc_ivar: 0x21cc
-  __DATA.__objc_data: 0x61d0
+  __DATA.__objc_const: 0x2bb08
+  __DATA.__objc_selrefs: 0xceb0
+  __DATA.__objc_ivar: 0x2228
+  __DATA.__objc_data: 0x6220
   __DATA.__lazy_load_got: 0x10
-  __DATA.__data: 0x4504
+  __DATA.__data: 0x4624
   __DATA.__bss: 0x638
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 10441
-  Symbols:   967
-  CStrings:  16943
+  Functions: 10529
+  Symbols:   969
+  CStrings:  17097
 
Symbols:
+ _CSIsJ265
+ _kCSAttSiriHSCategoryKey
CStrings:
+ "!F"
+ "#Bqb"
+ "$\""
+ "%s Attending OSD SPG quiet mode requested rows: %lu (threshold %.0f ms), applied rows: %lu (0 = asset unsupported)"
+ "%s Audio injection enabled, skip creating CSAggressiveECModeHandler"
+ "%s CSVoiceTriggerSecondPass[%{public}@]:Siri activation suppressed, skip prewarm"
+ "%s Cannot wait for enrollment voice trigger : %{public}@"
+ "%s Captured turn audio start: startSampleCount=%llu hostTime=%llu route=%@"
+ "%s Deferring two shot at %{public}fms of processed audio, audio is %{public}.0fms behind real time"
+ "%s Detected speech start at %{public}fms of processed audio, after the two shot"
+ "%s Detected speech start at %{public}fms of processed audio, no two shot"
+ "%s Disable PHS since the enrollment gate only needs a Hey Siri detection"
+ "%s Enrollment ended, restoring the exclave asset"
+ "%s Enrollment for locale %{public}@"
+ "%s Enrollment gate finished with error code %lu"
+ "%s Enrollment gate got second pass result %d"
+ "%s Fingerprint frame skip rate : %lu"
+ "%s Ignoring rising edge at %ldms, not after TRP silStart %.1fms"
+ "%s Mitigation asset updated, dropping resident mitigator"
+ "%s Mitigation not supported for ctx: %{public}@, skipping neural combiner for requestId: %@"
+ "%s Mitigator config changed from %{public}@ to %{public}@, rebuilding"
+ "%s No mitigation config to preload"
+ "%s Preloaded URES Mitigator for %{public}@"
+ "%s Sending Siri UI dismissal updates to listeners for rootRequestId: %@"
+ "%s Setting the exclave asset for enrollment locale %{public}@ failed, restoring the regular asset"
+ "%s Silence to speech transition detected at %ldms with currentSignalDuration: %f"
+ "%s Skip AFTM - shadow mode on HomePod Classic"
+ "%s Stopping CSAttSiriTwoShotDetector"
+ "%s Triggering asset refresh at Siri UI dismissal, for rootRequestId:%@, requestIdOriginatedFromClient: %i"
+ "%s Two shot feedback eligible: %d, silence threshold: %.0f ms, requestMHUUID: %@"
+ "%s Two shot heartbeat = %{public}llu, processedAudioMs: %{public}.0f, silenceDurationMs: %{public}.0f, armed: %d, didDetectSpeech: %d, didNotifyTwoShot: %d"
+ "%s UI dismissal for stale session %@ does not match current session %@. Skipping."
+ "%s Unable to preload Ures mitigator with err: %{public}@"
+ "%s VoiceTrigger is already listening, reuse it for the enrollment gate"
+ "%s VoiceTrigger is disabled, clean up second pass checker cached irs"
+ "%s VoiceTrigger is disabled, keep cached irs on HomePod"
+ "%s Waiting for enrollment voice trigger"
+ "%s endpointerTurnXPCService two shot detector at %f"
+ "%s skip purging cached irs for endpoint asset"
+ "-[CSAggressiveECModeHandler init]"
+ "-[CSAttSiriEndpointerTurnXPCService twoShotDetector:didDetectTwoShotAtTime:]_block_invoke"
+ "-[CSAttSiriOSDProvider start:useOwnVoiceVAD:startOfSpeechThresholdInMs:completion:]_block_invoke"
+ "-[CSAttSiriTwoShotDetector _evaluateOSDFeatures:]"
+ "-[CSAttSiriTwoShotDetector startWithRecordContext:voiceTriggerEventInfo:requestMHUUID:]_block_invoke"
+ "-[CSAttSiriTwoShotDetector stop]_block_invoke"
+ "-[CSAttSiriUresNode _preloadMitigatorForAsset:]_block_invoke"
+ "-[CSAttSiriUresNode invalidateMitigator]_block_invoke"
+ "-[CSAttendingStatesProvidingProxy dismissAttendingForRootRequestId:]_block_invoke"
+ "-[CSBuiltInVoiceTrigger _finishEnrollmentGateWithTriggerInfo:errorCode:]"
+ "-[CSBuiltInVoiceTrigger _handleEnrollmentGateSecondPassResult:]"
+ "-[CSBuiltInVoiceTrigger _setExclaveAsset:fallbackLocale:completion:]_block_invoke"
+ "-[CSBuiltInVoiceTrigger awaitEnrollmentVoiceTriggerWithCompletion:]_block_invoke"
+ "-[CSBuiltInVoiceTrigger beginEnrollmentForLocale:]_block_invoke"
+ "-[CSBuiltInVoiceTrigger endEnrollment]_block_invoke"
+ "-[CSIntuitiveConvRequestHandler dismissAttendingRequestedForRootRequest:requestIdOriginatedFromClient:]"
+ "-[CSIntuitiveConvRequestHandler dismissAttendingRequestedForRootRequest:requestIdOriginatedFromClient:]_block_invoke_2"
+ "@\"<CSAttSiriTwoShotDetectorOutputDelegate>\""
+ "@\"<CSBuiltInVoiceTriggering>\"16@0:8"
+ "@\"BMSource\""
+ "@\"CSAttSiriTwoShotDetector\""
+ "CSAttSiriTwoShotDetector"
+ "CSAttSiriTwoShotDetector queue"
+ "CSAttSiriTwoShotDetectorOutputDelegate"
+ "CSBuiltInVoiceTriggering"
+ "CSVoiceTriggerManagerProviding"
+ "T@\"<CSAttSiriTwoShotDetectorOutputDelegate>\",W,N,V_outputDelegate"
+ "T@\"CSAttSiriTwoShotDetector\",&,N,V_twoShotDetector"
+ "T@\"NSString\",C,N,V_enrollmentLocale"
+ "T@\"NSString\",C,N,V_mitigatorConfigFile"
+ "T@\"NSString\",C,N,V_requestMHUUID"
+ "T@?,C,N,V_enrollmentGateCompletion"
+ "TB,N,V_didDeferTwoShot"
+ "TB,N,V_enrollmentGateStartedAPVoiceTrigger"
+ "TB,N,V_isArmed"
+ "TB,N,V_keepMitigatorLoaded"
+ "TB,N,V_precomputedEmbeddingEnabled"
+ "TB,N,V_suppressSiriActivation"
+ "TB,V_discardingPendingAudio"
+ "TB,V_isEnrollmentGateActive"
+ "TQ,N,V_heartbeat"
+ "Td,N,V_audioDeliveryLagMs"
+ "Td,N,V_silenceThresholdMs"
+ "Td,N,V_vtExtraAudioAtStartMs"
+ "Tq,N,V_risingEdgeTimestampMs"
+ "_armWithRecordContext:voiceTriggerEventInfo:"
+ "_audioDeliveryLagMs"
+ "_cleanUpSecondPassCheckerCachedIrs"
+ "_didDeferTwoShot"
+ "_disarm"
+ "_discardingPendingAudio"
+ "_enrollmentGateCompletion"
+ "_enrollmentGateStartedAPVoiceTrigger"
+ "_enrollmentLocale"
+ "_evaluateOSDFeatures:"
+ "_finishEnrollmentGateWithTriggerInfo:errorCode:"
+ "_handleEnrollmentGateSecondPassResult:"
+ "_heartbeat"
+ "_isArmed"
+ "_isEnrollmentGateActive"
+ "_keepMitigatorLoaded"
+ "_mitigatorConfigFile"
+ "_precomputedEmbeddingEnabled"
+ "_preloadMitigatorForAsset:"
+ "_risingEdgeTimestampMs"
+ "_setExclaveAsset:fallbackLocale:completion:"
+ "_shouldRunVoiceTrigger"
+ "_silenceThresholdMs"
+ "_startPreloadingMitigator"
+ "_suppressSiriActivation"
+ "_twoShotDetector"
+ "_vtExtraAudioAtStartMs"
+ "_vtStatsBiomeSource"
+ "audioDeliveryLagMs"
+ "awaitEnrollmentVoiceTriggerWithCompletion:"
+ "beginEnrollmentForLocale:"
+ "builtInVoiceTrigger"
+ "cancelEnrollmentVoiceTriggerWait"
+ "didDeferTwoShot"
+ "discardingPendingAudio"
+ "dismissAttendingForRootRequestId:"
+ "dismissAttendingRequestedForRootRequest:requestIdOriginatedFromClient:"
+ "endEnrollment"
+ "enrollmentGateCompletion"
+ "enrollmentGateStartedAPVoiceTrigger"
+ "enrollmentLocale"
+ "extractEmbeddingFromSession:toProfile:withContext:withCompletion:"
+ "fetchFinalEmbeddingWithCompletion:"
+ "heartbeat"
+ "initWithConfigFile:sampleRate:context:queue:delegate:osdAnalyzerAssetLocker:quietRowsPerCompute:quietResumeAfterSilenceMs:"
+ "initWithPrecomputedEmbedding:"
+ "invalidateMitigator"
+ "isArmed"
+ "isAttendingOSDQuietModeEnabled"
+ "isEnrollmentGateActive"
+ "keepMitigatorLoaded"
+ "mitigatorConfigFile"
+ "onDeviceCompilationQueue"
+ "osdConfigPath"
+ "precomputedEmbeddingEnabled"
+ "purgeCachedIrForAssetExcludingCurrentAsset:baseCachedIrDir:"
+ "quietModeRows"
+ "removeCachedIrsForModelType:"
+ "risingEdgeTimestampMs"
+ "setAudioDeliveryLagMs:"
+ "setDidDeferTwoShot:"
+ "setDiscardingPendingAudio:"
+ "setEnrollmentGateCompletion:"
+ "setEnrollmentGateStartedAPVoiceTrigger:"
+ "setEnrollmentLocale:"
+ "setHeartbeat:"
+ "setIsArmed:"
+ "setIsEnrollmentGateActive:"
+ "setKeepMitigatorLoaded:"
+ "setMitigatorConfigFile:"
+ "setPrecomputedEmbeddingEnabled:"
+ "setRisingEdgeTimestampMs:"
+ "setSilenceThresholdMs:"
+ "setSuppressSiriActivation:"
+ "setTwoShotDetector:"
+ "setVtExtraAudioAtStartMs:"
+ "shouldReuseLiveEmbeddingForCCProfile"
+ "silenceThresholdMs"
+ "start:useOwnVoiceVAD:startOfSpeechThresholdInMs:completion:"
+ "startWithRecordContext:voiceTriggerEventInfo:requestMHUUID:"
+ "suppressSiriActivation"
+ "tryAcquireForLocalWithRequestId:mhId:resourceType:"
+ "twoShotDetector"
+ "twoShotDetector:didDetectTwoShotAtTime:"
+ "v24@0:8@?<v@?@\"NSData\">16"
+ "v24@0:8@?<v@?BQ@\"NSError\">16"
+ "v28@0:8@\"NSString\"16B24"
+ "v32@0:8@\"CSAttSiriTwoShotDetector\"16d24"
+ "v40@0:8B16B20d24@?32"
+ "vtExtraAudioAtStartMs"
- "#Bab"
- "%s Captured turn audio start: startSampleCount=%llu hostTime=%llu fromExclave=%d route=%@"
- "%s Created OSDAnalyzer: %{public}@"
- "%s Silence to speech transition detected at %ldms"
- "%s Triggering asset refresh at Siri UI dismissal, for rootRequestId:%@"
- "%s VoiceTrigger is disabled, clean up cached ir path"
- "%s purging for specific device is not handled here"
- "-[CSAttSiriOSDProvider start:useOwnVoiceVAD:completion:]_block_invoke"
- "-[CSIntuitiveConvRequestHandler dismissAttendingRequestedForRootRequest:]"
- "-[CSOnDeviceCachedIrPurgingHandler _purgeCachedIrFilesWithAsset:]"
- "TB,N,V_turnAudioFromExclave"
- "_cleanUpOnDeviceCompilationPath"
- "_turnAudioFromExclave"
- "dismissAttendingRequestedForRootRequest:"
- "purgeCachedIrForTrialAssetExcludingCurrentAsset:baseCachedIrDir:"
- "removeOnDeviceCachedPath"
- "setTurnAudioFromExclave:"
- "start:useOwnVoiceVAD:completion:"
- "turnAudioFromExclave"
- "v32@0:8B16B20@?24"
```
