## CoreSpeech

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/Versions/A/CoreSpeech`

```diff

 3600.70.47.0.0
-  __TEXT.__text: 0x13c0f4
+  __TEXT.__text: 0x13f47c
   __TEXT.__lazy_helpers: 0x54
-  __TEXT.__objc_methlist: 0x13c58
+  __TEXT.__objc_methlist: 0x14038
   __TEXT.__const: 0x40c
   __TEXT.__dlopen_cstrs: 0x4e
-  __TEXT.__gcc_except_tab: 0x30d4
-  __TEXT.__cstring: 0x250d1
-  __TEXT.__oslogstring: 0x1dc65
-  __TEXT.__unwind_info: 0x4a30
+  __TEXT.__gcc_except_tab: 0x3194
+  __TEXT.__cstring: 0x2559f
+  __TEXT.__oslogstring: 0x1e169
+  __TEXT.__unwind_info: 0x4ad0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0xd40
-  __DATA_CONST.__objc_classlist: 0x810
+  __DATA_CONST.__objc_classlist: 0x838
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x4b0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0xa418
+  __DATA_CONST.__objc_selrefs: 0xa518
   __DATA_CONST.__objc_protorefs: 0xa0
-  __DATA_CONST.__objc_superrefs: 0x630
+  __DATA_CONST.__objc_superrefs: 0x658
   __DATA_CONST.__objc_arraydata: 0x3f0
-  __DATA_CONST.__got: 0x1878
-  __AUTH_CONST.__const: 0x5800
-  __AUTH_CONST.__cfstring: 0x9140
-  __AUTH_CONST.__objc_const: 0x1f3c0
+  __DATA_CONST.__got: 0x1890
+  __AUTH_CONST.__const: 0x5920
+  __AUTH_CONST.__cfstring: 0x9180
+  __AUTH_CONST.__objc_const: 0x1fb60
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__lazy_load_got: 0x8
   __AUTH_CONST.__objc_intobj: 0x900

   __AUTH_CONST.__objc_floatobj: 0x4d0
   __AUTH_CONST.__objc_arrayobj: 0xf0
   __AUTH_CONST.__auth_got: 0xc18
-  __AUTH.__objc_data: 0x39d0
-  __DATA.__objc_ivar: 0x17d4
+  __AUTH.__objc_data: 0x3b60
+  __DATA.__objc_ivar: 0x1828
   __DATA.__data: 0x37d4
   __DATA.__bss: 0x5c8
   __DATA.__common: 0x10

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 7691
-  Symbols:   16967
-  CStrings:  5140
+  Functions: 7797
+  Symbols:   17140
+  CStrings:  5173
 
Symbols:
+ -[CSAlwaysOnProcessorEnabledWatchExclave .cxx_destruct]
+ -[CSAlwaysOnProcessorEnabledWatchExclave _addConditons]
+ -[CSAlwaysOnProcessorEnabledWatchExclave _handlePowerStateChange:]
+ -[CSAlwaysOnProcessorEnabledWatchExclave _subscribeToMonitors]
+ -[CSAlwaysOnProcessorEnabledWatchExclave init]
+ -[CSAlwaysOnProcessorEnabledWatchExclave queue]
+ -[CSAlwaysOnProcessorEnabledWatchExclave setQueue:]
+ -[CSAlwaysOnProcessorEnabledWatchExclave setSleepModeMonitor:]
+ -[CSAlwaysOnProcessorEnabledWatchExclave setWristStateMonitor:]
+ -[CSAlwaysOnProcessorEnabledWatchExclave sleepModeMonitor]
+ -[CSAlwaysOnProcessorEnabledWatchExclave wristStateMonitor]
+ -[CSRaiseToSpeakEnabledPolicyWatchExclave _addListeningEnabledConditions]
+ -[CSRaiseToSpeakEnabledPolicyWatchExclave _subscribeEventMonitors]
+ -[CSRaiseToSpeakEnabledPolicyWatchExclave init]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch .cxx_destruct]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch _addVoiceTriggerAPModeSuspendConditions]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch _handleClientRecordStateDidChange:eventUUID:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch _handlePowerStateChange:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch _isAudioRouteIneligibleForAP]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch _isHearstRoutedWithNoPhoneCall]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch _isInPhoneCallStateWithHeadset]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch _isSpeechDetectionDevicePresent]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch _subscribeEventMonitors]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch attSiriStateMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch audioRouteChangeMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch audiostreamActivityMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch batteryMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch builtinSpeakerStateMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch commandControlStreamEventMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch init]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch isSiriClientConsideredAsRecord]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch pendingRecordingStopUUID]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch phoneCallStateMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch phraseSpotterEnabledMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch playbackVolumeStatusMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setAttSiriStateMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setAudioRouteChangeMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setAudiostreamActivityMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setBatteryMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setBuiltinSpeakerStateMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setCommandControlStreamEventMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setIsSiriClientConsideredAsRecord:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setPendingRecordingStopUUID:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setPhoneCallStateMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setPhraseSpotterEnabledMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setPlaybackVolumeStatusMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setSiriAssertionMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setSiriClientBehaviorMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setSleepModeMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setSpeechDetectionDevicePresentMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch setWristStateMonitor:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch siriAssertionMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch siriClientBehaviorMonitor:didChangedRecordState:withEventUUID:withContext:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch siriClientBehaviorMonitor:didStartStreamWithContext:successfully:option:withEventUUID:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch siriClientBehaviorMonitor:didStopStream:withEventUUID:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch siriClientBehaviorMonitor:willStartStreamWithContext:option:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch siriClientBehaviorMonitor:willStopStream:reason:]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch siriClientBehaviorMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch sleepModeMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch speechDetectionDevicePresentMonitor]
+ -[CSVoiceTriggerAPModeSuspendPolicyWatch wristStateMonitor]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch .cxx_destruct]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch CSAudioRouteChangeMonitor:didReceiveAudioRouteChangeEvent:]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch CSVoiceTriggerXPCServiceProxy:bypassPhraseSpotter:]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch CSVoiceTriggerXPCServiceProxy:bypassRaiseToSpeak:]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch _addConditons]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch _isExternalPhraseSpotterRunning:]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch _subscribeToMonitors]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch init]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch queue]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch setQueue:]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch siriClientBehaviorMonitor:didStartStreamWithContext:successfully:option:withEventUUID:]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch siriClientBehaviorMonitor:didStopStream:withEventUUID:]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch siriClientBehaviorMonitor:willStartStreamWithContext:option:]
+ -[CSVoiceTriggerActivationPolicyExclaveWatch siriClientBehaviorMonitor:willStopStream:reason:]
+ -[CSVoiceTriggerEnabledPolicyWatchExclave _addListeningEnabledConditions]
+ -[CSVoiceTriggerEnabledPolicyWatchExclave _subscribeEventMonitors]
+ -[CSVoiceTriggerEnabledPolicyWatchExclave init]
+ GCC_except_table1534
+ GCC_except_table1586
+ GCC_except_table1610
+ GCC_except_table1614
+ GCC_except_table1630
+ GCC_except_table1633
+ GCC_except_table1659
+ GCC_except_table1666
+ GCC_except_table1675
+ GCC_except_table1774
+ GCC_except_table1776
+ GCC_except_table1778
+ GCC_except_table1784
+ GCC_except_table1844
+ GCC_except_table1870
+ GCC_except_table1876
+ GCC_except_table1957
+ GCC_except_table1979
+ GCC_except_table2083
+ GCC_except_table2220
+ GCC_except_table2223
+ GCC_except_table2226
+ GCC_except_table2231
+ GCC_except_table2243
+ GCC_except_table2248
+ GCC_except_table2251
+ GCC_except_table2254
+ GCC_except_table2257
+ GCC_except_table2350
+ GCC_except_table2395
+ GCC_except_table2400
+ GCC_except_table2407
+ GCC_except_table2425
+ GCC_except_table2455
+ GCC_except_table2619
+ GCC_except_table2631
+ GCC_except_table2662
+ GCC_except_table2698
+ GCC_except_table2732
+ GCC_except_table2733
+ GCC_except_table2734
+ GCC_except_table2735
+ GCC_except_table2736
+ GCC_except_table2740
+ GCC_except_table2743
+ GCC_except_table2746
+ GCC_except_table2747
+ GCC_except_table2750
+ GCC_except_table2751
+ GCC_except_table2760
+ GCC_except_table2766
+ GCC_except_table2768
+ GCC_except_table2769
+ GCC_except_table2797
+ GCC_except_table3065
+ GCC_except_table3139
+ GCC_except_table3176
+ GCC_except_table3203
+ GCC_except_table3206
+ GCC_except_table3209
+ GCC_except_table3240
+ GCC_except_table3300
+ GCC_except_table3494
+ GCC_except_table3520
+ GCC_except_table3548
+ GCC_except_table3583
+ GCC_except_table3610
+ GCC_except_table3612
+ GCC_except_table3614
+ GCC_except_table3616
+ GCC_except_table3619
+ GCC_except_table3627
+ GCC_except_table3630
+ GCC_except_table3637
+ GCC_except_table3639
+ GCC_except_table3641
+ GCC_except_table3643
+ GCC_except_table3645
+ GCC_except_table3647
+ GCC_except_table3648
+ GCC_except_table3649
+ GCC_except_table3650
+ GCC_except_table3652
+ GCC_except_table3653
+ GCC_except_table3654
+ GCC_except_table3657
+ GCC_except_table3659
+ GCC_except_table3660
+ GCC_except_table3661
+ GCC_except_table3662
+ GCC_except_table3663
+ GCC_except_table3664
+ GCC_except_table3665
+ GCC_except_table3667
+ GCC_except_table3668
+ GCC_except_table3676
+ GCC_except_table3681
+ GCC_except_table3682
+ GCC_except_table3683
+ GCC_except_table3684
+ GCC_except_table3796
+ GCC_except_table3820
+ GCC_except_table3886
+ GCC_except_table3902
+ GCC_except_table3923
+ GCC_except_table4015
+ GCC_except_table4325
+ GCC_except_table4326
+ GCC_except_table4330
+ GCC_except_table4333
+ GCC_except_table4337
+ GCC_except_table4362
+ GCC_except_table4415
+ GCC_except_table4421
+ GCC_except_table4777
+ GCC_except_table4937
+ GCC_except_table4947
+ GCC_except_table4971
+ GCC_except_table4991
+ GCC_except_table5075
+ GCC_except_table5089
+ GCC_except_table5098
+ GCC_except_table5113
+ GCC_except_table5118
+ GCC_except_table5126
+ GCC_except_table5130
+ GCC_except_table5136
+ GCC_except_table5138
+ GCC_except_table5156
+ GCC_except_table5163
+ GCC_except_table5168
+ GCC_except_table5170
+ GCC_except_table5172
+ GCC_except_table5174
+ GCC_except_table5175
+ GCC_except_table5176
+ GCC_except_table5177
+ GCC_except_table5180
+ GCC_except_table5184
+ GCC_except_table5185
+ GCC_except_table5186
+ GCC_except_table5189
+ GCC_except_table5191
+ GCC_except_table5192
+ GCC_except_table5193
+ GCC_except_table5197
+ GCC_except_table5212
+ GCC_except_table5243
+ GCC_except_table5352
+ GCC_except_table5382
+ GCC_except_table5385
+ GCC_except_table5475
+ GCC_except_table5489
+ GCC_except_table5496
+ GCC_except_table5518
+ GCC_except_table5522
+ GCC_except_table5532
+ GCC_except_table5776
+ GCC_except_table5782
+ GCC_except_table5815
+ GCC_except_table5820
+ GCC_except_table5857
+ GCC_except_table5866
+ GCC_except_table5896
+ GCC_except_table5976
+ GCC_except_table6198
+ GCC_except_table6206
+ GCC_except_table6226
+ GCC_except_table6231
+ GCC_except_table6340
+ GCC_except_table6410
+ GCC_except_table6432
+ GCC_except_table6433
+ GCC_except_table6443
+ GCC_except_table6444
+ GCC_except_table6456
+ GCC_except_table6487
+ GCC_except_table6498
+ GCC_except_table6503
+ GCC_except_table6508
+ GCC_except_table6540
+ GCC_except_table6622
+ GCC_except_table6648
+ GCC_except_table6659
+ GCC_except_table6662
+ GCC_except_table6685
+ GCC_except_table6697
+ GCC_except_table6740
+ GCC_except_table6884
+ GCC_except_table6971
+ GCC_except_table7026
+ GCC_except_table7049
+ GCC_except_table7090
+ GCC_except_table7100
+ GCC_except_table7110
+ GCC_except_table7151
+ GCC_except_table7158
+ GCC_except_table7180
+ GCC_except_table7229
+ GCC_except_table7320
+ GCC_except_table7321
+ GCC_except_table7322
+ GCC_except_table7323
+ GCC_except_table7324
+ GCC_except_table7329
+ GCC_except_table7393
+ GCC_except_table7441
+ GCC_except_table7447
+ GCC_except_table7450
+ GCC_except_table7458
+ GCC_except_table7464
+ GCC_except_table7489
+ GCC_except_table7495
+ GCC_except_table7501
+ GCC_except_table7633
+ OBJC_IVAR_$_CSAlwaysOnProcessorEnabledWatchExclave._queue
+ OBJC_IVAR_$_CSAlwaysOnProcessorEnabledWatchExclave._sleepModeMonitor
+ OBJC_IVAR_$_CSAlwaysOnProcessorEnabledWatchExclave._wristStateMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._attSiriStateMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._audioRouteChangeMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._audiostreamActivityMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._batteryMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._builtinSpeakerStateMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._commandControlStreamEventMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._isSiriClientConsideredAsRecord
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._pendingRecordingStopUUID
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._phoneCallStateMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._phraseSpotterEnabledMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._playbackVolumeStatusMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._recordStateQueue
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._siriAssertionMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._siriClientBehaviorMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._sleepModeMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._speechDetectionDevicePresentMonitor
+ OBJC_IVAR_$_CSVoiceTriggerAPModeSuspendPolicyWatch._wristStateMonitor
+ OBJC_IVAR_$_CSVoiceTriggerActivationPolicyExclaveWatch._queue
+ _NSProcessInfoPowerStateDidChangeNotification
+ _OBJC_CLASS_$_CSAlwaysOnProcessorEnabledWatchExclave
+ _OBJC_CLASS_$_CSRaiseToSpeakEnabledPolicyWatchExclave
+ _OBJC_CLASS_$_CSVoiceTriggerAPModeSuspendPolicyWatch
+ _OBJC_CLASS_$_CSVoiceTriggerActivationPolicyExclaveWatch
+ _OBJC_CLASS_$_CSVoiceTriggerEnabledPolicyWatchExclave
+ _OBJC_METACLASS_$_CSAlwaysOnProcessorEnabledWatchExclave
+ _OBJC_METACLASS_$_CSRaiseToSpeakEnabledPolicyWatchExclave
+ _OBJC_METACLASS_$_CSVoiceTriggerAPModeSuspendPolicyWatch
+ _OBJC_METACLASS_$_CSVoiceTriggerActivationPolicyExclaveWatch
+ _OBJC_METACLASS_$_CSVoiceTriggerEnabledPolicyWatchExclave
+ __55-[CSAlwaysOnProcessorEnabledWatchExclave _addConditons]_block_invoke
+ __59-[CSVoiceTriggerActivationPolicyExclaveWatch _addConditons]_block_invoke
+ __73-[CSVoiceTriggerEnabledPolicyWatchExclave _addListeningEnabledConditions]_block_invoke
+ __81-[CSVoiceTriggerAPModeSuspendPolicyWatch _addVoiceTriggerAPModeSuspendConditions]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_CSAlwaysOnProcessorEnabledWatchExclave
+ __OBJC_$_INSTANCE_METHODS_CSRaiseToSpeakEnabledPolicyWatchExclave
+ __OBJC_$_INSTANCE_METHODS_CSVoiceTriggerAPModeSuspendPolicyWatch
+ __OBJC_$_INSTANCE_METHODS_CSVoiceTriggerActivationPolicyExclaveWatch
+ __OBJC_$_INSTANCE_METHODS_CSVoiceTriggerEnabledPolicyWatchExclave
+ __OBJC_$_INSTANCE_VARIABLES_CSAlwaysOnProcessorEnabledWatchExclave
+ __OBJC_$_INSTANCE_VARIABLES_CSVoiceTriggerAPModeSuspendPolicyWatch
+ __OBJC_$_INSTANCE_VARIABLES_CSVoiceTriggerActivationPolicyExclaveWatch
+ __OBJC_$_PROP_LIST_CSAlwaysOnProcessorEnabledWatchExclave
+ __OBJC_$_PROP_LIST_CSVoiceTriggerAPModeSuspendPolicyWatch
+ __OBJC_$_PROP_LIST_CSVoiceTriggerActivationPolicyExclaveWatch
+ __OBJC_CLASS_PROTOCOLS_$_CSVoiceTriggerAPModeSuspendPolicyWatch
+ __OBJC_CLASS_PROTOCOLS_$_CSVoiceTriggerActivationPolicyExclaveWatch
+ __OBJC_CLASS_RO_$_CSAlwaysOnProcessorEnabledWatchExclave
+ __OBJC_CLASS_RO_$_CSRaiseToSpeakEnabledPolicyWatchExclave
+ __OBJC_CLASS_RO_$_CSVoiceTriggerAPModeSuspendPolicyWatch
+ __OBJC_CLASS_RO_$_CSVoiceTriggerActivationPolicyExclaveWatch
+ __OBJC_CLASS_RO_$_CSVoiceTriggerEnabledPolicyWatchExclave
+ __OBJC_METACLASS_RO_$_CSAlwaysOnProcessorEnabledWatchExclave
+ __OBJC_METACLASS_RO_$_CSRaiseToSpeakEnabledPolicyWatchExclave
+ __OBJC_METACLASS_RO_$_CSVoiceTriggerAPModeSuspendPolicyWatch
+ __OBJC_METACLASS_RO_$_CSVoiceTriggerActivationPolicyExclaveWatch
+ __OBJC_METACLASS_RO_$_CSVoiceTriggerEnabledPolicyWatchExclave
+ ___100-[CSVoiceTriggerActivationPolicyExclaveWatch siriClientBehaviorMonitor:didStopStream:withEventUUID:]_block_invoke
+ ___104-[CSVoiceTriggerActivationPolicyExclaveWatch CSAudioRouteChangeMonitor:didReceiveAudioRouteChangeEvent:]_block_invoke
+ ___116-[CSVoiceTriggerAPModeSuspendPolicyWatch siriClientBehaviorMonitor:didChangedRecordState:withEventUUID:withContext:]_block_invoke
+ ___132-[CSVoiceTriggerActivationPolicyExclaveWatch siriClientBehaviorMonitor:didStartStreamWithContext:successfully:option:withEventUUID:]_block_invoke
+ ___55-[CSAlwaysOnProcessorEnabledWatchExclave _addConditons]_block_invoke
+ ___59-[CSVoiceTriggerActivationPolicyExclaveWatch _addConditons]_block_invoke
+ ___73-[CSRaiseToSpeakEnabledPolicyWatchExclave _addListeningEnabledConditions]_block_invoke
+ ___73-[CSVoiceTriggerEnabledPolicyWatchExclave _addListeningEnabledConditions]_block_invoke
+ ___81-[CSVoiceTriggerAPModeSuspendPolicyWatch _addVoiceTriggerAPModeSuspendConditions]_block_invoke
+ ___81-[CSVoiceTriggerAPModeSuspendPolicyWatch _addVoiceTriggerAPModeSuspendConditions]_block_invoke_2
+ ___86-[CSVoiceTriggerAPModeSuspendPolicyWatch _handleClientRecordStateDidChange:eventUUID:]_block_invoke
+ ___96-[CSVoiceTriggerActivationPolicyExclaveWatch CSVoiceTriggerXPCServiceProxy:bypassPhraseSpotter:]_block_invoke
+ _objc_msgSend$_addConditons
+ _objc_msgSend$_isExternalPhraseSpotterRunning:
+ _objc_msgSend$_isHearstRoutedWithNoPhoneCall
+ _objc_msgSend$_isInPhoneCallStateWithHeadset
+ _objc_msgSend$_subscribeToMonitors
+ _objc_msgSend$attSiriStateMonitor
+ _objc_msgSend$audiostreamActivityMonitor
+ _objc_msgSend$builtinSpeakerStateMonitor
+ _objc_msgSend$bypassPhraseSpotter
+ _objc_msgSend$commandControlStreamEventMonitor
+ _objc_msgSend$forceAPModeNonExclaveWatch
+ _objc_msgSend$isLowPowerModeEnabled
+ _objc_msgSend$isSiriClientConsideredAsRecord
+ _objc_msgSend$phraseSpotterEnabledMonitor
+ _objc_msgSend$playbackVolumeStatusMonitor
+ _objc_msgSend$setIsSiriClientConsideredAsRecord:
+ _objc_msgSend$siriAssertionMonitor
+ _objc_msgSend$siriClientBehaviorMonitor
+ _objc_msgSend$sleepModeMonitor
+ _objc_msgSend$wristState
+ _objc_msgSend$wristStateMonitor
- GCC_except_table1527
- GCC_except_table1551
- GCC_except_table1555
- GCC_except_table1571
- GCC_except_table1574
- GCC_except_table1600
- GCC_except_table1607
- GCC_except_table1616
- GCC_except_table1715
- GCC_except_table1717
- GCC_except_table1719
- GCC_except_table1725
- GCC_except_table1785
- GCC_except_table1811
- GCC_except_table1817
- GCC_except_table1898
- GCC_except_table1920
- GCC_except_table2024
- GCC_except_table2161
- GCC_except_table2164
- GCC_except_table2167
- GCC_except_table2172
- GCC_except_table2184
- GCC_except_table2189
- GCC_except_table2192
- GCC_except_table2195
- GCC_except_table2198
- GCC_except_table2291
- GCC_except_table2336
- GCC_except_table2341
- GCC_except_table2348
- GCC_except_table2366
- GCC_except_table2396
- GCC_except_table2501
- GCC_except_table2572
- GCC_except_table2603
- GCC_except_table2628
- GCC_except_table2639
- GCC_except_table2673
- GCC_except_table2674
- GCC_except_table2675
- GCC_except_table2676
- GCC_except_table2677
- GCC_except_table2681
- GCC_except_table2684
- GCC_except_table2688
- GCC_except_table2691
- GCC_except_table2692
- GCC_except_table2701
- GCC_except_table2707
- GCC_except_table2709
- GCC_except_table2710
- GCC_except_table2738
- GCC_except_table3006
- GCC_except_table3080
- GCC_except_table3117
- GCC_except_table3144
- GCC_except_table3147
- GCC_except_table3150
- GCC_except_table3181
- GCC_except_table3241
- GCC_except_table3435
- GCC_except_table3461
- GCC_except_table3489
- GCC_except_table3524
- GCC_except_table3525
- GCC_except_table3527
- GCC_except_table3529
- GCC_except_table3545
- GCC_except_table3547
- GCC_except_table3549
- GCC_except_table3551
- GCC_except_table3553
- GCC_except_table3555
- GCC_except_table3557
- GCC_except_table3560
- GCC_except_table3568
- GCC_except_table3571
- GCC_except_table3578
- GCC_except_table3580
- GCC_except_table3582
- GCC_except_table3589
- GCC_except_table3590
- GCC_except_table3591
- GCC_except_table3593
- GCC_except_table3594
- GCC_except_table3595
- GCC_except_table3598
- GCC_except_table3600
- GCC_except_table3601
- GCC_except_table3602
- GCC_except_table3603
- GCC_except_table3605
- GCC_except_table3609
- GCC_except_table3617
- GCC_except_table3622
- GCC_except_table3623
- GCC_except_table3624
- GCC_except_table3625
- GCC_except_table3731
- GCC_except_table3755
- GCC_except_table3821
- GCC_except_table3837
- GCC_except_table3858
- GCC_except_table3950
- GCC_except_table4203
- GCC_except_table4256
- GCC_except_table4257
- GCC_except_table4261
- GCC_except_table4264
- GCC_except_table4293
- GCC_except_table4346
- GCC_except_table4352
- GCC_except_table4708
- GCC_except_table4868
- GCC_except_table4878
- GCC_except_table4902
- GCC_except_table4922
- GCC_except_table5006
- GCC_except_table5020
- GCC_except_table5029
- GCC_except_table5038
- GCC_except_table5044
- GCC_except_table5046
- GCC_except_table5049
- GCC_except_table5057
- GCC_except_table5061
- GCC_except_table5067
- GCC_except_table5069
- GCC_except_table5087
- GCC_except_table5094
- GCC_except_table5099
- GCC_except_table5101
- GCC_except_table5103
- GCC_except_table5105
- GCC_except_table5106
- GCC_except_table5108
- GCC_except_table5111
- GCC_except_table5116
- GCC_except_table5117
- GCC_except_table5120
- GCC_except_table5122
- GCC_except_table5123
- GCC_except_table5124
- GCC_except_table5128
- GCC_except_table5143
- GCC_except_table5269
- GCC_except_table5299
- GCC_except_table5302
- GCC_except_table5392
- GCC_except_table5406
- GCC_except_table5413
- GCC_except_table5435
- GCC_except_table5439
- GCC_except_table5449
- GCC_except_table5693
- GCC_except_table5699
- GCC_except_table5732
- GCC_except_table5737
- GCC_except_table5774
- GCC_except_table5783
- GCC_except_table5813
- GCC_except_table5893
- GCC_except_table6115
- GCC_except_table6123
- GCC_except_table6143
- GCC_except_table6148
- GCC_except_table6257
- GCC_except_table6327
- GCC_except_table6349
- GCC_except_table6350
- GCC_except_table6360
- GCC_except_table6361
- GCC_except_table6373
- GCC_except_table6404
- GCC_except_table6415
- GCC_except_table6420
- GCC_except_table6425
- GCC_except_table6457
- GCC_except_table6539
- GCC_except_table6565
- GCC_except_table6576
- GCC_except_table6579
- GCC_except_table6602
- GCC_except_table6614
- GCC_except_table6778
- GCC_except_table6814
- GCC_except_table6865
- GCC_except_table6943
- GCC_except_table6984
- GCC_except_table6994
- GCC_except_table7004
- GCC_except_table7045
- GCC_except_table7052
- GCC_except_table7074
- GCC_except_table7123
- GCC_except_table7214
- GCC_except_table7215
- GCC_except_table7216
- GCC_except_table7217
- GCC_except_table7218
- GCC_except_table7223
- GCC_except_table7287
- GCC_except_table7335
- GCC_except_table7341
- GCC_except_table7344
- GCC_except_table7352
- GCC_except_table7358
- GCC_except_table7383
- GCC_except_table7389
- GCC_except_table7395
- GCC_except_table7527
CStrings:
+ "%s Built-in voice triggered, can stay in AOP mode"
+ "%s Disabling VoiceTrigger on AOP as since LowPowerMode is enabled"
+ "%s Disabling VoiceTrigger on AOP as since SleepMode is enabled"
+ "%s Disabling VoiceTrigger on AOP as the watch is off wrist"
+ "%s Display is off, remain in AOP mode so all triggers are gated"
+ "%s External phrase spotter running, ignore AOP trigger notification"
+ "%s ForceAPModeNonExclaveWatch=YES, forcing listening enabled (AP mode always on)"
+ "%s Phrase spotter is disabled, ignore Siri AP/AOP activation"
+ "%s RTS on watch cannot be turned on since there is another non eligible app recording and we are not in a connected or outgoing call"
+ "%s Received Hearst event %{public}ld"
+ "%s Turn on AP mode since LPM enabled with backlight ON"
+ "%s Turn on AP mode since Sleep Mode is enabled with backLight ON"
+ "%s Turn on AP mode since watch is off wrist and back light is on"
+ "%s VAD is not present (%d) or Hearst routed without phone call (%d)"
+ "%s VoiceTrigger on watch cannot be turned on since HS is disabled"
+ "%s VoiceTrigger on watch cannot be turned on since system shell is not started"
+ "%s VoiceTrigger on watch cannot be turned on since there is another non eligible app recording and we are not in a connected or outgoing call"
+ "%s phraseSpotter bypassed, ignore AOP/AP trigger notification"
+ "-[CSAlwaysOnProcessorEnabledWatchExclave _addConditons]_block_invoke"
+ "-[CSRaiseToSpeakEnabledPolicyWatchExclave _addListeningEnabledConditions]_block_invoke"
+ "-[CSVoiceTriggerAPModeSuspendPolicyWatch _addVoiceTriggerAPModeSuspendConditions]_block_invoke"
+ "-[CSVoiceTriggerAPModeSuspendPolicyWatch _addVoiceTriggerAPModeSuspendConditions]_block_invoke_2"
+ "-[CSVoiceTriggerAPModeSuspendPolicyWatch _handleClientRecordStateDidChange:eventUUID:]"
+ "-[CSVoiceTriggerAPModeSuspendPolicyWatch _handleClientRecordStateDidChange:eventUUID:]_block_invoke"
+ "-[CSVoiceTriggerAPModeSuspendPolicyWatch _isAudioRouteIneligibleForAP]"
+ "-[CSVoiceTriggerAPModeSuspendPolicyWatch _isSpeechDetectionDevicePresent]"
+ "-[CSVoiceTriggerActivationPolicyExclaveWatch CSAudioRouteChangeMonitor:didReceiveAudioRouteChangeEvent:]_block_invoke"
+ "-[CSVoiceTriggerActivationPolicyExclaveWatch _addConditons]_block_invoke"
+ "-[CSVoiceTriggerActivationPolicyExclaveWatch _isExternalPhraseSpotterRunning:]"
+ "-[CSVoiceTriggerEnabledPolicyWatchExclave _addListeningEnabledConditions]_block_invoke"
+ "CSVoiceTriggerAPModeSuspendPolicyWatch RecordState queue"
+ "com.apple.corespeech.CSAOPActivationEventHandlingPolicyWatch.queue"
+ "com.apple.corespeech.CSAlwaysOnProcessorEnabledExcalveWatch.queue"
```
