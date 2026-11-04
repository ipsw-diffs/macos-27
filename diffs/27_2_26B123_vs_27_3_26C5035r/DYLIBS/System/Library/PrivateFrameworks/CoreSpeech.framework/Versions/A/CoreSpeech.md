## CoreSpeech

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/Versions/A/CoreSpeech`

```diff

-3605.32.1.14.1
-  __TEXT.__text: 0x13b120
-  __TEXT.__lazy_helpers: 0x54
-  __TEXT.__objc_methlist: 0x140ac
+3610.11.1.0.0
+  __TEXT.__text: 0x13cc9c
+  __TEXT.__lazy_helpers: 0xa8
+  __TEXT.__objc_methlist: 0x141bc
   __TEXT.__const: 0x42c
   __TEXT.__dlopen_cstrs: 0x4e
-  __TEXT.__gcc_except_tab: 0x321c
-  __TEXT.__cstring: 0x256a7
-  __TEXT.__oslogstring: 0x1e4e7
-  __TEXT.__unwind_info: 0x5d20
+  __TEXT.__gcc_except_tab: 0x323c
+  __TEXT.__cstring: 0x258cc
+  __TEXT.__oslogstring: 0x1eb6c
+  __TEXT.__unwind_info: 0x5d70
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xd78
+  __DATA_CONST.__const: 0xd80
   __DATA_CONST.__objc_classlist: 0x838
   __DATA_CONST.__objc_catlist: 0x48
-  __DATA_CONST.__objc_protolist: 0x4a8
+  __DATA_CONST.__objc_protolist: 0x4b0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0xa5c8
+  __DATA_CONST.__objc_selrefs: 0xa6c0
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0x658
   __DATA_CONST.__objc_arraydata: 0x3f8
-  __DATA_CONST.__got: 0x18a0
-  __AUTH_CONST.__const: 0x59f0
-  __AUTH_CONST.__cfstring: 0x9120
-  __AUTH_CONST.__objc_const: 0x1fce8
+  __DATA_CONST.__got: 0x18b8
+  __AUTH_CONST.__const: 0x5a30
+  __AUTH_CONST.__cfstring: 0x91c0
+  __AUTH_CONST.__objc_const: 0x1fd90
   __AUTH_CONST.__weak_auth_got: 0x28
-  __AUTH_CONST.__lazy_load_got: 0x8
+  __AUTH_CONST.__lazy_load_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x918
   __AUTH_CONST.__objc_doubleobj: 0x90
   __AUTH_CONST.__objc_dictobj: 0x3e8
   __AUTH_CONST.__objc_floatobj: 0x4d0
   __AUTH_CONST.__objc_arrayobj: 0x108
-  __AUTH_CONST.__auth_got: 0xc18
+  __AUTH_CONST.__auth_got: 0xc20
   __AUTH.__objc_data: 0x3b60
-  __DATA.__objc_ivar: 0x184c
-  __DATA.__data: 0x3774
-  __DATA.__bss: 0x5c8
+  __DATA.__objc_ivar: 0x1858
+  __DATA.__data: 0x37d4
+  __DATA.__bss: 0x5d0
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x16d0
   __DATA_DIRTY.__data: 0xc0
-  __DATA_DIRTY.__bss: 0x100
+  __DATA_DIRTY.__bss: 0xf8
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 7810
-  Symbols:   16953
-  CStrings:  5181
+  Functions: 7832
+  Symbols:   17022
+  CStrings:  5212
 
Symbols:
+ +[CSMyriadPHash getTriggerAudioForVoiceTriggerInfo:withHostTime:writeFile:]
+ +[CSSiriAudioActivationInfo _isLinwoodEnabledAndAvailable]
+ +[CSSpeechController continuousVoiceTriggerActivationUserInfo:]
+ -[CSAsset(SpeakerRecognition) _firstNumberForKey:inSectionKeys:]
+ -[CSAsset(SpeakerRecognition) _numberForKey:inSection:]
+ -[CSAsset(SpeakerRecognition) inRequestSegmentSpkrIdScoreThresholdForSelfPlatform:servingPlatform:recordRoute:]
+ -[CSAttSiriAttentionAssetsStatusProvider _fetchCurrentAssetStatus]
+ -[CSAttSiriAttentionAssetsStatusProvider assetHandler]
+ -[CSAttSiriAttentionAssetsStatusProvider initWithDelegate:]
+ -[CSAttSiriAttentionAssetsStatusProvider initWithMitigationAssetHandler:delegate:]
+ -[CSAttSiriAttentionAssetsStatusProvider setAssetHandler:]
+ -[CSBuiltInVoiceTrigger _isLinwoodEnabledAndAvailable]
+ -[CSBuiltInVoiceTrigger _shouldRequestExclaveAudioWithProvider:]
+ -[CSBuiltInVoiceTrigger isListeningWithActiveCallContext]
+ -[CSBuiltInVoiceTrigger linwoodEnabledAndAvailableMonitor:didReceiveEnabledAndAvailable:]
+ -[CSBuiltInVoiceTrigger setIsListeningWithActiveCallContext:]
+ -[CSDeviceSelectionNotifier _notifyTriggerAudioSliceVoiceTriggerInfo:]
+ -[CSDeviceSelectionNotifier _shouldDonateTriggerAudioSlice]
+ -[CSDeviceSelectionNotifier voiceTriggerDidProduceFingerprintInfo:]
+ -[CSSiriAudioActivationInfo _canPrewarmForCrownHold]
+ -[CSSiriSpeechRecorder setServerAudioSentByClient:]
+ -[CSVoiceTriggerSecondPass _isLinwoodEnabledAndAvailable]
+ -[CSVoiceTriggerSecondPass _secondPassChannelForFirstPassChannel:channelSelectionScores:isLinwoodEnabledAndAvailable:]
+ GCC_except_table1248
+ GCC_except_table1262
+ GCC_except_table1469
+ GCC_except_table1543
+ GCC_except_table1595
+ GCC_except_table1619
+ GCC_except_table1623
+ GCC_except_table1639
+ GCC_except_table1642
+ GCC_except_table1675
+ GCC_except_table1684
+ GCC_except_table1783
+ GCC_except_table1785
+ GCC_except_table1787
+ GCC_except_table1793
+ GCC_except_table1853
+ GCC_except_table1879
+ GCC_except_table1885
+ GCC_except_table1966
+ GCC_except_table1988
+ GCC_except_table2092
+ GCC_except_table2229
+ GCC_except_table2232
+ GCC_except_table2235
+ GCC_except_table2240
+ GCC_except_table2252
+ GCC_except_table2257
+ GCC_except_table2260
+ GCC_except_table2263
+ GCC_except_table2266
+ GCC_except_table2359
+ GCC_except_table2404
+ GCC_except_table2416
+ GCC_except_table2434
+ GCC_except_table2464
+ GCC_except_table2577
+ GCC_except_table2636
+ GCC_except_table2648
+ GCC_except_table2679
+ GCC_except_table2704
+ GCC_except_table2715
+ GCC_except_table2749
+ GCC_except_table2751
+ GCC_except_table2752
+ GCC_except_table2763
+ GCC_except_table2764
+ GCC_except_table2767
+ GCC_except_table2768
+ GCC_except_table2777
+ GCC_except_table2783
+ GCC_except_table2785
+ GCC_except_table2786
+ GCC_except_table2814
+ GCC_except_table288
+ GCC_except_table291
+ GCC_except_table3086
+ GCC_except_table3161
+ GCC_except_table3198
+ GCC_except_table3228
+ GCC_except_table3231
+ GCC_except_table3234
+ GCC_except_table3267
+ GCC_except_table3327
+ GCC_except_table3488
+ GCC_except_table3514
+ GCC_except_table352
+ GCC_except_table3542
+ GCC_except_table3580
+ GCC_except_table3581
+ GCC_except_table3583
+ GCC_except_table3585
+ GCC_except_table3601
+ GCC_except_table3605
+ GCC_except_table3607
+ GCC_except_table3609
+ GCC_except_table3613
+ GCC_except_table3616
+ GCC_except_table3624
+ GCC_except_table3640
+ GCC_except_table3642
+ GCC_except_table3651
+ GCC_except_table3654
+ GCC_except_table3656
+ GCC_except_table3657
+ GCC_except_table3658
+ GCC_except_table3659
+ GCC_except_table3660
+ GCC_except_table3662
+ GCC_except_table3663
+ GCC_except_table3665
+ GCC_except_table3674
+ GCC_except_table3679
+ GCC_except_table3680
+ GCC_except_table3681
+ GCC_except_table3682
+ GCC_except_table3794
+ GCC_except_table3818
+ GCC_except_table3884
+ GCC_except_table3900
+ GCC_except_table3921
+ GCC_except_table4013
+ GCC_except_table402
+ GCC_except_table4266
+ GCC_except_table4323
+ GCC_except_table4324
+ GCC_except_table4328
+ GCC_except_table4331
+ GCC_except_table4335
+ GCC_except_table4360
+ GCC_except_table4363
+ GCC_except_table4418
+ GCC_except_table4424
+ GCC_except_table4783
+ GCC_except_table4946
+ GCC_except_table4956
+ GCC_except_table4980
+ GCC_except_table5000
+ GCC_except_table5084
+ GCC_except_table5107
+ GCC_except_table5116
+ GCC_except_table5122
+ GCC_except_table5124
+ GCC_except_table5135
+ GCC_except_table5139
+ GCC_except_table5145
+ GCC_except_table5172
+ GCC_except_table5179
+ GCC_except_table5181
+ GCC_except_table5185
+ GCC_except_table5186
+ GCC_except_table5189
+ GCC_except_table5193
+ GCC_except_table5194
+ GCC_except_table5195
+ GCC_except_table5198
+ GCC_except_table5200
+ GCC_except_table5201
+ GCC_except_table5202
+ GCC_except_table5206
+ GCC_except_table5221
+ GCC_except_table5252
+ GCC_except_table5361
+ GCC_except_table5391
+ GCC_except_table5394
+ GCC_except_table5484
+ GCC_except_table5498
+ GCC_except_table5505
+ GCC_except_table5525
+ GCC_except_table5529
+ GCC_except_table5539
+ GCC_except_table5785
+ GCC_except_table5791
+ GCC_except_table5824
+ GCC_except_table5829
+ GCC_except_table5867
+ GCC_except_table5876
+ GCC_except_table5906
+ GCC_except_table5992
+ GCC_except_table604
+ GCC_except_table6216
+ GCC_except_table6224
+ GCC_except_table6244
+ GCC_except_table6249
+ GCC_except_table6358
+ GCC_except_table6428
+ GCC_except_table6450
+ GCC_except_table6451
+ GCC_except_table6461
+ GCC_except_table6462
+ GCC_except_table6474
+ GCC_except_table6516
+ GCC_except_table6521
+ GCC_except_table6526
+ GCC_except_table6558
+ GCC_except_table662
+ GCC_except_table6640
+ GCC_except_table6666
+ GCC_except_table6677
+ GCC_except_table6680
+ GCC_except_table6703
+ GCC_except_table6715
+ GCC_except_table6758
+ GCC_except_table6904
+ GCC_except_table6940
+ GCC_except_table6991
+ GCC_except_table7046
+ GCC_except_table7069
+ GCC_except_table7105
+ GCC_except_table7124
+ GCC_except_table7134
+ GCC_except_table7144
+ GCC_except_table7186
+ GCC_except_table7215
+ GCC_except_table7264
+ GCC_except_table727
+ GCC_except_table731
+ GCC_except_table7355
+ GCC_except_table7356
+ GCC_except_table7357
+ GCC_except_table7358
+ GCC_except_table7359
+ GCC_except_table7364
+ GCC_except_table742
+ GCC_except_table7428
+ GCC_except_table7476
+ GCC_except_table7482
+ GCC_except_table7485
+ GCC_except_table7493
+ GCC_except_table7499
+ GCC_except_table7524
+ GCC_except_table7530
+ GCC_except_table7536
+ GCC_except_table7668
+ GCC_except_table910
+ GCC_except_table928
+ GCC_except_table933
+ _AFIsLinwoodEnabledAndAvailable
+ _OBJC_CLASS_$_CSCompanionRuntimeThresholdKeys
+ _OBJC_CLASS_$_CSHardwareLatencyHelper
+ _OBJC_CLASS_$_CSLinwoodEnabledAndAvailableMonitor
+ _OBJC_CLASS_$_DeviceSelectionTriggerAudio
+ _OBJC_CLASS_$_DeviceSelectionTriggerAudio$lazyGOT
+ _OBJC_CLASS_$_DeviceSelectionTriggerAudio$lazyGOT$loadHelper_x8
+ _OBJC_IVAR_$_CSAttSiriAttentionAssetsStatusProvider._assetHandler
+ _OBJC_IVAR_$_CSBuiltInVoiceTrigger._isListeningWithActiveCallContext
+ _OBJC_IVAR_$_CSSiriSpeechRecorder._serverAudioSentByClient
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSLinwoodEnabledAndAvailableMonitorDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSLinwoodEnabledAndAvailableMonitorDelegate
+ __OBJC_$_PROTOCOL_REFS_CSLinwoodEnabledAndAvailableMonitorDelegate
+ __OBJC_LABEL_PROTOCOL_$_CSLinwoodEnabledAndAvailableMonitorDelegate
+ __OBJC_PROTOCOL_$_CSLinwoodEnabledAndAvailableMonitorDelegate
+ ___63+[CSSpeechController continuousVoiceTriggerActivationUserInfo:]_block_invoke
+ ___66-[CSAttSiriAttentionAssetsStatusProvider _fetchCurrentAssetStatus]_block_invoke
+ ___70-[CSDeviceSelectionNotifier _notifyTriggerAudioSliceVoiceTriggerInfo:]_block_invoke
+ ___89-[CSBuiltInVoiceTrigger linwoodEnabledAndAvailableMonitor:didReceiveEnabledAndAvailable:]_block_invoke
+ ___block_descriptor_48_e8_32s_e20_v20?0B8"NSError"12l
+ ___block_descriptor_48_e8_32s_e31_v16?0"<SCDAContextMutating>"8l
+ _objc_msgSend$_fetchCurrentAssetStatus
+ _objc_msgSend$_firstNumberForKey:inSectionKeys:
+ _objc_msgSend$_isLinwoodEnabledAndAvailable
+ _objc_msgSend$_notifyTriggerAudioSliceVoiceTriggerInfo:
+ _objc_msgSend$_numberForKey:inSection:
+ _objc_msgSend$_secondPassChannelForFirstPassChannel:channelSelectionScores:isLinwoodEnabledAndAvailable:
+ _objc_msgSend$_shouldDonateTriggerAudioSlice
+ _objc_msgSend$_shouldRequestExclaveAudioWithProvider:
+ _objc_msgSend$allowedChannelsBitset
+ _objc_msgSend$allowedChannelsBitsetLinwood
+ _objc_msgSend$cachedInputLatencySeconds
+ _objc_msgSend$continuousVoiceTriggerActivationUserInfo:
+ _objc_msgSend$decodeConfigFrom:shouldExcludeBSSChannels:isLinwoodEnabledAndAvailable:
+ _objc_msgSend$deviceSelectionTriggerAudioSliceMs
+ _objc_msgSend$donateTriggerAudioSlice:withCompletion:
+ _objc_msgSend$getTriggerAudioForVoiceTriggerInfo:withHostTime:writeFile:
+ _objc_msgSend$inRequestSegmentSpkrIdScoreThreshold
+ _objc_msgSend$initWithBuffer:sampleRate:isFloat32:timestamp:triggerStartMachTime:triggerEndMachTime:dspLatency:
+ _objc_msgSend$initWithFilepath:
+ _objc_msgSend$initWithMitigationAssetHandler:delegate:
+ _objc_msgSend$isAudioOrderingEnabled
+ _objc_msgSend$isDeviceSelectionParticipating
+ _objc_msgSend$isDeviceSelectionShadowModeEnabled
+ _objc_msgSend$isEnabledAndAvailable
+ _objc_msgSend$sectionKeysForSelfPlatform:servingPlatform:recordRoute:
+ _objc_msgSend$setServerAudioSentByClient:
+ _objc_msgSend$sha256HashStringFromInputString:
+ _objc_msgSend$shouldExcludeBSSChannelsFromVoiceTrigger
+ _objc_msgSend$supportsVoiceTriggerAssetChannelSelection
- +[CSMyriadPHash generateFingerprintForVoiceTriggerInfo:forTime:]
- -[CSBuiltInVoiceTrigger _stopListening]
- GCC_except_table1241
- GCC_except_table1255
- GCC_except_table1462
- GCC_except_table1536
- GCC_except_table1588
- GCC_except_table1612
- GCC_except_table1616
- GCC_except_table1632
- GCC_except_table1635
- GCC_except_table1661
- GCC_except_table1677
- GCC_except_table1776
- GCC_except_table1778
- GCC_except_table1780
- GCC_except_table1786
- GCC_except_table1846
- GCC_except_table1872
- GCC_except_table1878
- GCC_except_table1959
- GCC_except_table1981
- GCC_except_table2085
- GCC_except_table2222
- GCC_except_table2225
- GCC_except_table2228
- GCC_except_table2233
- GCC_except_table2245
- GCC_except_table2250
- GCC_except_table2253
- GCC_except_table2256
- GCC_except_table2259
- GCC_except_table2352
- GCC_except_table2397
- GCC_except_table2402
- GCC_except_table2427
- GCC_except_table2457
- GCC_except_table2570
- GCC_except_table2629
- GCC_except_table2641
- GCC_except_table2672
- GCC_except_table2697
- GCC_except_table2708
- GCC_except_table2742
- GCC_except_table2743
- GCC_except_table2744
- GCC_except_table2745
- GCC_except_table2746
- GCC_except_table2756
- GCC_except_table2761
- GCC_except_table2770
- GCC_except_table2776
- GCC_except_table2778
- GCC_except_table2779
- GCC_except_table2807
- GCC_except_table286
- GCC_except_table289
- GCC_except_table3079
- GCC_except_table3154
- GCC_except_table3191
- GCC_except_table3221
- GCC_except_table3224
- GCC_except_table3227
- GCC_except_table3258
- GCC_except_table3318
- GCC_except_table3475
- GCC_except_table3501
- GCC_except_table3529
- GCC_except_table3567
- GCC_except_table3568
- GCC_except_table3570
- GCC_except_table3572
- GCC_except_table3588
- GCC_except_table3590
- GCC_except_table3592
- GCC_except_table3594
- GCC_except_table3596
- GCC_except_table3598
- GCC_except_table3600
- GCC_except_table3614
- GCC_except_table3621
- GCC_except_table3623
- GCC_except_table3625
- GCC_except_table3629
- GCC_except_table3631
- GCC_except_table3632
- GCC_except_table3633
- GCC_except_table3637
- GCC_except_table3641
- GCC_except_table3643
- GCC_except_table3652
- GCC_except_table3653
- GCC_except_table3661
- GCC_except_table3667
- GCC_except_table3668
- GCC_except_table3669
- GCC_except_table3781
- GCC_except_table3805
- GCC_except_table3871
- GCC_except_table3887
- GCC_except_table3908
- GCC_except_table395
- GCC_except_table4000
- GCC_except_table4253
- GCC_except_table4310
- GCC_except_table4311
- GCC_except_table4315
- GCC_except_table4318
- GCC_except_table4322
- GCC_except_table4347
- GCC_except_table4350
- GCC_except_table4405
- GCC_except_table4411
- GCC_except_table4768
- GCC_except_table4928
- GCC_except_table4938
- GCC_except_table4962
- GCC_except_table4982
- GCC_except_table5066
- GCC_except_table5080
- GCC_except_table5089
- GCC_except_table5104
- GCC_except_table5106
- GCC_except_table5109
- GCC_except_table5117
- GCC_except_table5121
- GCC_except_table5129
- GCC_except_table5154
- GCC_except_table5159
- GCC_except_table5161
- GCC_except_table5163
- GCC_except_table5166
- GCC_except_table5167
- GCC_except_table5168
- GCC_except_table5171
- GCC_except_table5175
- GCC_except_table5176
- GCC_except_table5180
- GCC_except_table5182
- GCC_except_table5188
- GCC_except_table5203
- GCC_except_table5234
- GCC_except_table5343
- GCC_except_table5373
- GCC_except_table5376
- GCC_except_table5466
- GCC_except_table5480
- GCC_except_table5487
- GCC_except_table5507
- GCC_except_table5511
- GCC_except_table5521
- GCC_except_table5765
- GCC_except_table5771
- GCC_except_table5804
- GCC_except_table5809
- GCC_except_table5846
- GCC_except_table5855
- GCC_except_table5885
- GCC_except_table597
- GCC_except_table5971
- GCC_except_table6195
- GCC_except_table6203
- GCC_except_table6223
- GCC_except_table6228
- GCC_except_table6337
- GCC_except_table6407
- GCC_except_table6429
- GCC_except_table6430
- GCC_except_table6440
- GCC_except_table6441
- GCC_except_table6453
- GCC_except_table6484
- GCC_except_table6495
- GCC_except_table6500
- GCC_except_table6537
- GCC_except_table655
- GCC_except_table6619
- GCC_except_table6645
- GCC_except_table6656
- GCC_except_table6659
- GCC_except_table6682
- GCC_except_table6694
- GCC_except_table6737
- GCC_except_table6883
- GCC_except_table6919
- GCC_except_table6970
- GCC_except_table7025
- GCC_except_table7048
- GCC_except_table7084
- GCC_except_table7103
- GCC_except_table7113
- GCC_except_table7123
- GCC_except_table7164
- GCC_except_table7171
- GCC_except_table720
- GCC_except_table724
- GCC_except_table7242
- GCC_except_table728
- GCC_except_table7333
- GCC_except_table7334
- GCC_except_table7335
- GCC_except_table7336
- GCC_except_table7337
- GCC_except_table7342
- GCC_except_table7406
- GCC_except_table7454
- GCC_except_table7460
- GCC_except_table7463
- GCC_except_table7471
- GCC_except_table7477
- GCC_except_table7502
- GCC_except_table7508
- GCC_except_table7514
- GCC_except_table7646
- GCC_except_table903
- GCC_except_table921
- GCC_except_table926
- ___39-[CSBuiltInVoiceTrigger _stopListening]_block_invoke
- ___73-[CSAttSiriAttentionAssetsStatusProvider initWithMitigationAssetHandler:]_block_invoke
- _objc_msgSend$isDeviceSelectionEnabled
CStrings:
+ "%@/%@%-@ch%d-mct%llu.pcm.wav"
+ "%s #deviceSelection AToA Failed to get trigger audio buffer"
+ "%s #deviceSelection AToA exclave trigger; no slice is donated on this build"
+ "%s #deviceSelection AToA trigger audio chunk is empty; no slice to donate"
+ "%s #deviceSelection AToA trigger audio has no buffer timestamp; it cannot be ordered"
+ "%s #deviceSelection AToA trigger audio slice has no samples; nothing donated"
+ "%s #deviceSelection Error - no audio chunk for trigger audio slice, channel: %@"
+ "%s #deviceSelection Error - no audioStreamProvider for UUID: %@"
+ "%s #deviceSelection Trigger audio buffer too short for %lu samples; slice will start at 0"
+ "%s #deviceSelection Trigger audio slice: %lu samples, format: %@, channel: %@"
+ "%s Audio Ordering not supported"
+ "%s CSVoiceTriggerSecondPass[%{public}@]:First pass selected channel %{public}tu, using channel %{public}tu for second pass"
+ "%s CSVoiceTriggerSecondPass[%{public}@]:No first pass score for allowed channels 0x%{public}llx, using first pass channel %{public}tu"
+ "%s Device Selection Feature or AToA (Audio Time of Arrival) disabled, returning"
+ "%s Donated trigger audio slice (%@, at: %llu) successfully"
+ "%s Failed to donate trigger audio slice: %@"
+ "%s Failed to save trigger audio slice to file %{public}@"
+ "%s Linwood enabled and available changed to %{public}@, first pass channels 0x%{public}llx -> 0x%{public}llx. Apply the current voice trigger asset again."
+ "%s Linwood enabled and available changed to %{public}@, first pass channels 0x%{public}llx do not change"
+ "%s Trigger Audio length %lu, format: %@"
+ "%s Using %{public}@=%{public}@ from section %{public}@"
+ "%s Wrote trigger audio slice as a PCM WAV file: %@"
+ "%s kVTEItriggerEndMachTime is nil, passing 0"
+ "%s kVTEItriggerStartMachTime is nil, passing 0"
+ "+[CSMyriadPHash getTriggerAudioForVoiceTriggerInfo:withHostTime:writeFile:]"
+ "-[CSAsset(SpeakerRecognition) _firstNumberForKey:inSectionKeys:]"
+ "-[CSAttSiriAttentionAssetsStatusProvider initWithMitigationAssetHandler:delegate:]"
+ "-[CSBuiltInVoiceTrigger linwoodEnabledAndAvailableMonitor:didReceiveEnabledAndAvailable:]_block_invoke"
+ "-[CSDeviceSelectionNotifier _notifyTriggerAudioSliceVoiceTriggerInfo:]"
+ "-[CSDeviceSelectionNotifier _notifyTriggerAudioSliceVoiceTriggerInfo:]_block_invoke"
+ "-[CSDeviceSelectionNotifier voiceTriggerDidProduceFingerprintInfo:]"
+ "-[CSVoiceTriggerSecondPass _secondPassChannelForFirstPassChannel:channelSelectionScores:isLinwoodEnabledAndAvailable:]"
+ "CSSpeechRecordSettingsKey_serverAudioSentByClient"
+ "TriggerAudioSlice-"
+ "float32"
+ "int16"
- "%s Returning nil - CS_USE_SHAZAM not set."
- "+[CSMyriadPHash generateFingerprintForVoiceTriggerInfo:forTime:]"
- "-[CSAttSiriAttentionAssetsStatusProvider initWithMitigationAssetHandler:]"
- "-[CSBuiltInVoiceTrigger _stopListening]"
- "-[CSBuiltInVoiceTrigger _stopListening]_block_invoke"
```
