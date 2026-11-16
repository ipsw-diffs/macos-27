## AudioSession

> `/System/Library/PrivateFrameworks/AudioSession.framework/Versions/A/AudioSession`

```diff

-449.302.0.0.0
-  __TEXT.__text: 0x4d888
+449.305.0.0.0
+  __TEXT.__text: 0x4d770
   __TEXT.__realtime: 0x1718
   __TEXT.__objc_methlist: 0x2024
-  __TEXT.__cstring: 0x4e90
+  __TEXT.__cstring: 0x4ec4
   __TEXT.__const: 0x271a
   __TEXT.__gcc_except_tab: 0x77f8
   __TEXT.__oslogstring: 0x5db5

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x738
+  __DATA_CONST.__const: 0x740
   __DATA_CONST.__objc_classlist: 0x118
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_selrefs: 0x1570
   __DATA_CONST.__objc_superrefs: 0xe0
   __DATA_CONST.__objc_arraydata: 0x10
-  __DATA_CONST.__got: 0x738
+  __DATA_CONST.__got: 0x740
   __AUTH_CONST.__const: 0x2798
-  __AUTH_CONST.__cfstring: 0x2d20
+  __AUTH_CONST.__cfstring: 0x2d40
   __AUTH_CONST.__objc_const: 0x3280
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x90

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 1985
-  Symbols:   3961
-  CStrings:  1001
+  Symbols:   3963
+  CStrings:  1002
 
Symbols:
+ _AVAudioSessionInterruptionEndLikelyToBeResumableKey
+ _kAudioSessionNotification_InterruptionInfoKey_EndInterruptionLikelyToBeResumable
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[AVAudioSession dealloc] : 1292 -> 1288
~ -[AVAudioSession(CatalystPrivate) handleAppStatePauseFinal:] : 560 -> 556
~ -[AVAudioSession(CatalystPrivate) getATDefaultDeviceAggregate] : 136 -> 132
~ -[AVAudioSession(CatalystPrivate) handleDefaultInputChange:] : 428 -> 424
~ -[AVAudioSession(AVAudioSessionPrivate) setRecordingFromRemoteInput:error:] : 236 -> 232
~ -[AVAudioSession(AVAudioSessionPrivate) reporterID] : 256 -> 252
~ -[AVAudioSession(AVAudioSessionDeprecated) delegate] : 100 -> 96
~ -[AVAudioSession(AVAudioSessionDeprecated) setDelegate:] : 144 -> 140
~ __ZN4avas6client17SessionCore_macOS21sendPlayStateToServerEv : 80 -> 76
~ __ZN4avas6client17SessionCore_macOS11isRunningIOEv : 88 -> 84
~ __ZN4avas6client23SessionCoreLegacy_macOSC2EP27AVAudioSessionSpecificationP14AVAudioSession : 448 -> 444
~ __ZN4avas6client23SessionCoreLegacy_macOSD2Ev : 104 -> 100
~ __ZN4avas6client23SessionCoreLegacy_macOS23currentRouteDescriptionEv : 188 -> 176
~ __ZN4avas6client23SessionCoreLegacy_macOS26addAggregateDeviceObserverEv : 404 -> 392
~ __ZN4avas6client23SessionCoreLegacy_macOS18preferredInputPortEv : 72 -> 68
~ __ZN4avas6client23SessionCoreLegacy_macOS21setPreferredInputPortEP29AVAudioSessionPortDescription : 80 -> 76
~ __ZNK4avas6client23SessionCoreLegacy_macOS8categoryEv : 80 -> 76
~ __ZNK4avas6client23SessionCoreLegacy_macOS4modeEv : 80 -> 76
~ __ZN4avas6client23SessionCoreLegacy_macOS7setModeEP8NSStringPU15__autoreleasingP7NSError : 1020 -> 1016
~ __ZN4avas6client23SessionCoreLegacy_macOS11setCategoryEP8NSStringPU15__autoreleasingP7NSError : 924 -> 916
~ __ZN4avas6client23SessionCoreLegacy_macOS9setActiveEbmPU15__autoreleasingP7NSError : 472 -> 468
~ __ZN4avas6client23SessionCoreLegacy_macOS11setCategoryEP8NSStringmPU15__autoreleasingP7NSError : 88 -> 84
~ __ZN4avas6client23SessionCoreLegacy_macOS11setCategoryEP8NSStringS3_mPU15__autoreleasingP7NSError : 208 -> 204
~ __ZN4avas6client23SessionCoreLegacy_macOS11setCategoryEP8NSStringS3_32AVAudioSessionRouteSharingPolicymPU15__autoreleasingP7NSError : 260 -> 256
~ __ZNK4avas6client23SessionCoreLegacy_macOS15categoryOptionsEv : 60 -> 56
~ __ZNK4avas6client23SessionCoreLegacy_macOS18routeSharingPolicyEv : 60 -> 56
~ __ZNK4avas6client23SessionCoreLegacy_macOS42allowHapticsAndSystemSoundsDuringRecordingEv : 60 -> 56
~ __ZN4avas6client23SessionCoreLegacy_macOS45setAllowHapticsAndSystemSoundsDuringRecordingEb : 64 -> 60
~ __ZNK4avas6client23SessionCoreLegacy_macOS38prefersNoInterruptionsFromSystemAlertsEv : 60 -> 56
~ __ZN4avas6client23SessionCoreLegacy_macOS41setPrefersNoInterruptionsFromSystemAlertsEb : 64 -> 60
~ __ZNK4avas6client23SessionCoreLegacy_macOS27supportsMultichannelContentEv : 60 -> 56
~ __ZN4avas6client23SessionCoreLegacy_macOS30setSupportsMultichannelContentEb : 64 -> 60
~ __ZNK4avas6client23SessionCoreLegacy_macOS36prefersInterruptionOnRouteDisconnectEv : 60 -> 56
~ __ZN4avas6client23SessionCoreLegacy_macOS39setPrefersInterruptionOnRouteDisconnectEb : 64 -> 60
~ __ZNK4avas6client23SessionCoreLegacy_macOS25preferredInputOrientationEv : 60 -> 56
~ __ZN4avas6client23SessionCoreLegacy_macOS28setPreferredInputOrientationE24AVAudioStereoOrientation : 64 -> 60
~ __ZNK4avas6client23SessionCoreLegacy_macOS30preferredInputNumberOfChannelsEv : 60 -> 56
~ __ZN4avas6client23SessionCoreLegacy_macOS33setPreferredInputNumberOfChannelsEl : 64 -> 60
~ __ZNK4avas6client23SessionCoreLegacy_macOS31preferredOutputNumberOfChannelsEv : 60 -> 56
~ __ZN4avas6client23SessionCoreLegacy_macOS34setPreferredOutputNumberOfChannelsEl : 64 -> 60
~ __ZNK4avas6client23SessionCoreLegacy_macOS21isExpanseMediaSessionEv : 60 -> 56
~ __ZN4avas6client23SessionCoreLegacy_macOS24setIsExpanseMediaSessionEb : 64 -> 60
~ __ZNK4avas6client23SessionCoreLegacy_macOS24recordingFromRemoteInputEv : 60 -> 56
~ __ZNK4avas6client23SessionCoreLegacy_macOS19preferredSampleRateEv : 68 -> 64
~ __ZN4avas6client23SessionCoreLegacy_macOS22setPreferredSampleRateEd : 72 -> 68
~ __ZNK4avas6client23SessionCoreLegacy_macOS25preferredIOBufferDurationEv : 68 -> 64
~ __ZN4avas6client23SessionCoreLegacy_macOS28setPreferredIOBufferDurationEd : 72 -> 68
~ __ZNK4avas6client23SessionCoreLegacy_macOS10sampleRateEv : 96 -> 92
~ __ZNK4avas6client23SessionCoreLegacy_macOS21inputNumberOfChannelsEv : 88 -> 84
~ __ZNK4avas6client23SessionCoreLegacy_macOS22outputNumberOfChannelsEv : 88 -> 84
~ __ZN4avas6client23SessionCoreLegacy_macOS29getATDefaultDeviceAggregateIDEv : 136 -> 132
~ __ZNK4avas6client23SessionCoreLegacy_macOS16isInputAvailableEv : 112 -> 108
~ __ZNK4avas6client23SessionCoreLegacy_macOS17isOutputAvailableEv : 96 -> 92
~ __ZN4avas6client23SessionCoreLegacy_macOS29setPreferredIOBufferFrameSizeEm : 232 -> 228
~ __ZNK4avas6client23SessionCoreLegacy_macOS26preferredIOBufferFrameSizeEv : 60 -> 56
~ __ZN4avas6client23SessionCoreLegacy_macOS21setRouteSharingPolicyE32AVAudioSessionRouteSharingPolicy : 64 -> 60
~ __ZN4avas6client23SessionCoreLegacy_macOS18setActivationStateEb : 440 -> 436
~ __ZN4avas6client23SessionCoreLegacy_macOS20determineServiceTypeEv : 760 -> 756
~ __ZN4avas6client23SessionCoreLegacy_macOS23sendActiveDeviceMessageEb : 448 -> 444
~ __ZN4avas6client23SessionCoreLegacy_macOS24addReporterIDToAggregateEv : 204 -> 200
~ __ZN4avas6client23SessionCoreLegacy_macOS29removeReporterIDFromAggregateEv : 204 -> 200
~ __ZN4avas6client23SessionCoreLegacy_macOS22prepareAggregateDeviceEb : 476 -> 464
~ __ZN4avas6client23SessionCoreLegacy_macOS12setPlayStateEP27AVAudioSessionPlayStateInfo : 124 -> 120
~ __ZN4avas6client23SessionCoreLegacy_macOS37checkPrimarySessionImplicitActivationEb : 672 -> 668
~ __ZN4avas6client23SessionCoreLegacy_macOS21hasPhoneCallBehaviourEv : 676 -> 668
~ __ZN4avas6client23SessionCoreLegacy_macOS17handleRouteChangeEv : 1056 -> 1048
~ ____ZN4avas6client23SessionCoreLegacy_macOS25handleSystemDevicesChangeEv_block_invoke : 192 -> 188
~ __ZN4avas6client23SessionCoreLegacy_macOS30updateDeviceStreamDescriptionsEb : 472 -> 464
~ __ZN4avas6client23SessionCoreLegacy_macOS11getChannelsEjjP8NSStringS3_ : 1096 -> 1088
~ __ZNK4avas6client11SessionCore18HandleInterruptionEP12NSDictionary : 2012 -> 2100
~ __ZN4avas6client10KVOManager22markPropertiesDirtyAllEv : 128 -> 124
~ __ZN4avas6client11SessionCore29resetCachedPreferredInputPortEv : 64 -> 60
~ __ZN4avas6client10KVOManager19markPropertiesDirtyEm : 104 -> 100
~ __ZN4avas6client11KVOPropertyIfE15UpdateAndNotifyERKfb : 176 -> 172
~ __ZNSt3__111unique_lockIN5caulk4mach21unfair_recursive_lockEE4lockB9nqe220106Ev : 100 -> 96
~ __ZN4avas6client11KVOPropertyIU8__strongP7NSArrayE15UpdateAndNotifyERU8__strongKS3_b : 176 -> 172
~ __ZN4avas6client11KVOPropertyIU8__strongP35AVAudioSessionDataSourceDescriptionE15UpdateAndNotifyERU8__strongKS3_b : 176 -> 172
~ __ZN4avas6client11KVOPropertyIjE15UpdateAndNotifyERKjb : 176 -> 172
~ __ZN4avas6client11KVOPropertyIdE15UpdateAndNotifyERKdb : 176 -> 172
~ __ZN4avas6client11SessionCore25setSessionCreationHandlerENSt3__110shared_ptrINS2_8functionIFvvEEEEE : 96 -> 92
~ __ZNSt3__110__function6__funcIZN4avas6client11SessionCore21createSessionInServerEvE3$_1FvvEEclEv : 452 -> 444
CStrings:
+ "AVAudioSessionInterruptionEndLikelyToBeResumableKey"
```
