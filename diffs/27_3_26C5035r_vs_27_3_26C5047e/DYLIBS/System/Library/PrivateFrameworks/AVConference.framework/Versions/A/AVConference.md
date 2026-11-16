## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/Versions/A/AVConference`

```diff

-2265.2.1.0.0
-  __TEXT.__text: 0x7c4114
+2265.4.1.0.0
+  __TEXT.__text: 0x7c5e70
   __TEXT.__realtime: 0xea4
-  __TEXT.__objc_methlist: 0x3a098
-  __TEXT.__const: 0x184a8
-  __TEXT.__cstring: 0x9bd3b
-  __TEXT.__oslogstring: 0x143e5f
+  __TEXT.__objc_methlist: 0x3a120
+  __TEXT.__const: 0x18588
+  __TEXT.__cstring: 0x9c004
+  __TEXT.__oslogstring: 0x144324
   __TEXT.__gcc_except_tab: 0x326c
   __TEXT.__ustring: 0x2d4
   __TEXT.__dlopen_cstrs: 0x56
-  __TEXT.__unwind_info: 0x1b598
+  __TEXT.__unwind_info: 0x1b600
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3ec0
+  __DATA_CONST.__const: 0x3f10
   __DATA_CONST.__objc_classlist: 0x14a0
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x508
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x18638
+  __DATA_CONST.__objc_selrefs: 0x18698
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x1240
   __DATA_CONST.__objc_arraydata: 0x2790
   __DATA_CONST.__got: 0x1b08
-  __AUTH_CONST.__const: 0x8a08
-  __AUTH_CONST.__cfstring: 0x292a0
+  __AUTH_CONST.__const: 0x8a38
+  __AUTH_CONST.__cfstring: 0x29400
   __AUTH_CONST.__objc_const: 0x6c908
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x4e00

   - /usr/lib/libspindump.dylib
   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 35385
-  Symbols:   52630
-  CStrings:  33448
+  Functions: 35408
+  Symbols:   52671
+  CStrings:  33478
 
Symbols:
+ +[VCSession forceFIRThrottleExperimentsToControl:ifUnsupportedByRemoteFrameworkVersion:]
+ +[VCSession isFIRThrottleExperimentSupportedByRemoteFrameworkVersion:]
+ +[VCSessionParticipant isValidAudioPosition:]
+ +[VCSessionParticipant isValidVolume:]
+ -[VCRedundancyControlAlgorithmVideoMultiway envelopeTimeWithStorebagKey:userDefaultKey:improvedStorebagKey:improvedUserDefaultKey:defaultTime:]
+ -[VCSession dispatchToParticipantWithID:block:]
+ -[VCSession resetFIRThrottleExperimentsIfUnsupportedByRemoteParticipant:]
+ -[VCSession setMediaState:forMediaType:participantID:]
+ -[VCSession setScreenEnabled:forParticipantID:]
+ -[VCSession setVideoEnabled:forParticipantID:]
+ -[VCSession(OneToOne) dispatchedUpdateOneToOneRateControllerForVideoEnabled:screenEnabled:]
+ -[VCSessionParticipantLocal dispatchedSetMuted:]
+ GCC_except_table229
+ _VCFIRThrottleTierAThreshold
+ _VCFIRThrottleTierBThreshold
+ _VCRedundancyMultiwayImprovedAttackTime
+ _VCRedundancyMultiwayImprovedDecayTime
+ _VideoReceiver_ResolveFIRThrottleIntervalForExperiments
+ ___44-[VCSessionManager registerBlocksForService]_block_invoke_6
+ ___44-[VCSessionManager registerBlocksForService]_block_invoke_7
+ ___44-[VCSessionManager registerBlocksForService]_block_invoke_8
+ ___44-[VCSessionManager registerBlocksForService]_block_invoke_9
+ ___46-[VCSession setVideoEnabled:forParticipantID:]_block_invoke
+ ___47-[VCSession dispatchToParticipantWithID:block:]_block_invoke
+ ___47-[VCSession setScreenEnabled:forParticipantID:]_block_invoke
+ ___54-[VCSession setMediaState:forMediaType:participantID:]_block_invoke
+ ___block_descriptor_36_e30_v16?0"VCSessionParticipant"8l
+ ___block_descriptor_40_e8_32o_e30_v16?0"VCSessionParticipant"8l
+ _kVCExperimentFIRThrottleTierA
+ _kVCExperimentFIRThrottleTierB
+ _objc_msgSend$dispatchToParticipantWithID:block:
+ _objc_msgSend$dispatchedSetMuted:
+ _objc_msgSend$dispatchedUpdateOneToOneRateControllerForVideoEnabled:screenEnabled:
+ _objc_msgSend$envelopeTimeWithStorebagKey:userDefaultKey:improvedStorebagKey:improvedUserDefaultKey:defaultTime:
+ _objc_msgSend$forceFIRThrottleExperimentsToControl:ifUnsupportedByRemoteFrameworkVersion:
+ _objc_msgSend$isFIRThrottleExperimentSupportedByRemoteFrameworkVersion:
+ _objc_msgSend$isValidAudioPosition:
+ _objc_msgSend$isValidVolume:
+ _objc_msgSend$resetFIRThrottleExperimentsIfUnsupportedByRemoteParticipant:
+ _objc_msgSend$setMediaState:forMediaType:participantID:
+ _objc_msgSend$setScreenEnabled:forParticipantID:
+ _objc_msgSend$setVideoEnabled:forParticipantID:
- GCC_except_table219
CStrings:
+ " [%s] %s:%d %@(%p) KPI-VAR-STATE: multiwayImprovedFactor=%d decayTime=%.3f attackTime=%.3f"
+ " [%s] %s:%d KPI-VAR-STATE: multiwayImprovedFactor=%d decayTime=%.3f attackTime=%.3f"
+ " [%s] %s:%d [AR_TX][FTDC][%p] Dual capture disabled: restoring cached AR portraitAR=%.3f, landscapeAR=%.3f"
+ "+[VCSession forceFIRThrottleExperimentsToControl:ifUnsupportedByRemoteFrameworkVersion:]"
+ "-[VCSession dispatchToParticipantWithID:block:]"
+ "-[VCSession setMediaState:forMediaType:participantID:]_block_invoke"
+ "-[VCSession setScreenEnabled:forParticipantID:]_block_invoke"
+ "-[VCSession setVideoEnabled:forParticipantID:]_block_invoke"
+ "-[VCSessionManager registerBlocksForService]_block_invoke_6"
+ "2265"
+ "2265.4.1"
+ "VCSession [%s] %s:%d %@(%p) changing VCSessionParticipant=%p mediaType=%d to state=%d"
+ "VCSession [%s] %s:%d %@(%p) changing VCSessionParticipant[%p] screenEnabled to %d"
+ "VCSession [%s] %s:%d %@(%p) changing VCSessionParticipant[%p] videoEnabled to %d"
+ "VCSession [%s] %s:%d %@(%p) nil block for participantID=%@"
+ "VCSession [%s] %s:%d FIRTHROTTLE-AB: failed to force control for remoteFrameworkVersion=%s tierA=%d tierB=%d"
+ "VCSession [%s] %s:%d FIRTHROTTLE-AB: remoteFrameworkVersion=%s predates the experiment, running control"
+ "VCSession [%s] %s:%d changing VCSessionParticipant=%p mediaType=%d to state=%d"
+ "VCSession [%s] %s:%d changing VCSessionParticipant[%p] screenEnabled to %d"
+ "VCSession [%s] %s:%d changing VCSessionParticipant[%p] videoEnabled to %d"
+ "VCSession [%s] %s:%d nil block for participantID=%@"
+ "VCVideoStream [%s] %s:%d %@(%p) FIRTHROTTLE-AB: senderMinKeyFrameIntervalMs=%.1f firThrottleIntervalMs=%.1f"
+ "VCVideoStream [%s] %s:%d FIRTHROTTLE-AB: senderMinKeyFrameIntervalMs=%.1f firThrottleIntervalMs=%.1f"
+ "VSTDurHist"
+ "VSTDurHistA"
+ "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] rejected out-of-range firThrottleIntervalMs=%.1f, falling back to defaultMs=%.1f"
+ "VideoReceiver [%s] %s:%d FIRTHROTTLE-AB: firThrottleIntervalMs=%.1f armTierA=%d armTierB=%d (videoReceiver=%p)"
+ "_VideoPacketBuffer_NormalizeFIRThrottleInterval"
+ "enableFIRThrottleTierA"
+ "enableFIRThrottleTierB"
+ "redundancyMultiwayImprovedAttackTime"
+ "redundancyMultiwayImprovedDecayTime"
+ "v16@?0@\"VCSessionParticipant\"8"
+ "vc-experiment-fir-throttle-tier-a-threshold"
+ "vc-experiment-fir-throttle-tier-b-threshold"
+ "vc-red-multiway-improved-attack-time"
+ "vc-red-multiway-improved-decay-time"
- " [%s] %s:%d %@(%p) KPI-VAR-STATE: multiwayImprovedFactor=%d"
- " [%s] %s:%d KPI-VAR-STATE: multiwayImprovedFactor=%d"
- " [%s] %s:%d changing VCSessionParticipant=%p mediaType=%d to state=%d"
- " [%s] %s:%d changing VCSessionParticipant[%p] screenEnabled to %d"
- " [%s] %s:%d changing VCSessionParticipant[%p] videoEnabled to %d"
- "-[VCSessionManager registerBlocksForService]_block_invoke_3"
- "2265.2.1"
```
