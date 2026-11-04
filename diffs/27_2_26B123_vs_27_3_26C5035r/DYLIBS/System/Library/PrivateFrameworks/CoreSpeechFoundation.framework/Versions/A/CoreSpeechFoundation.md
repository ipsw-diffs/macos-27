## CoreSpeechFoundation

> `/System/Library/PrivateFrameworks/CoreSpeechFoundation.framework/Versions/A/CoreSpeechFoundation`

```diff

-3605.32.1.14.1
-  __TEXT.__text: 0xc9490
-  __TEXT.__objc_methlist: 0xdad8
+3610.11.1.0.0
+  __TEXT.__text: 0xcd130
+  __TEXT.__objc_methlist: 0xdeb0
   __TEXT.__const: 0xb98
   __TEXT.__dlopen_cstrs: 0x18c
   __TEXT.__constg_swiftt: 0x25c
   __TEXT.__swift5_typeref: 0x19d
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_types: 0x20
-  __TEXT.__cstring: 0x15e27
+  __TEXT.__cstring: 0x165b1
   __TEXT.__swift5_reflstr: 0x174
   __TEXT.__swift5_assocty: 0x18
   __TEXT.__swift5_fieldmd: 0x180
   __TEXT.__swift5_proto: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__gcc_except_tab: 0x3d48
-  __TEXT.__oslogstring: 0x10958
-  __TEXT.__unwind_info: 0x4828
+  __TEXT.__gcc_except_tab: 0x3db8
+  __TEXT.__oslogstring: 0x1158d
+  __TEXT.__unwind_info: 0x4930
   __TEXT.__eh_frame: 0xe0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1030
-  __DATA_CONST.__objc_classlist: 0x770
+  __DATA_CONST.__const: 0x10a0
+  __DATA_CONST.__objc_classlist: 0x790
   __DATA_CONST.__objc_catlist: 0x58
-  __DATA_CONST.__objc_protolist: 0x210
+  __DATA_CONST.__objc_protolist: 0x218
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x18
-  __DATA_CONST.__objc_selrefs: 0x7420
+  __DATA_CONST.__objc_selrefs: 0x75f8
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0x568
+  __DATA_CONST.__objc_superrefs: 0x580
   __DATA_CONST.__objc_arraydata: 0x1e0
-  __DATA_CONST.__got: 0xc68
-  __AUTH_CONST.__const: 0x3b60
-  __AUTH_CONST.__cfstring: 0x9a00
-  __AUTH_CONST.__objc_const: 0x151b0
+  __DATA_CONST.__got: 0xc88
+  __AUTH_CONST.__const: 0x3bf0
+  __AUTH_CONST.__cfstring: 0x9c40
+  __AUTH_CONST.__objc_const: 0x157e0
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_dictobj: 0x1e0
-  __AUTH_CONST.__objc_intobj: 0x4c8
+  __AUTH_CONST.__objc_intobj: 0x4e0
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_floatobj: 0x1a0
-  __AUTH_CONST.__auth_got: 0xed0
-  __AUTH.__objc_data: 0x2b8
+  __AUTH_CONST.__auth_got: 0xef0
+  __AUTH.__objc_data: 0x3f8
   __AUTH.__data: 0x18
-  __DATA.__objc_ivar: 0xdd4
-  __DATA.__data: 0x1908
-  __DATA.__bss: 0x9c0
+  __DATA.__objc_ivar: 0xe34
+  __DATA.__data: 0x1968
+  __DATA.__bss: 0x9f0
   __DATA_DIRTY.__objc_data: 0x4860
   __DATA_DIRTY.__data: 0x310
   __DATA_DIRTY.__bss: 0x658

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5313
-  Symbols:   12179
-  CStrings:  3661
+  Functions: 5394
+  Symbols:   12371
+  CStrings:  3746
 
Symbols:
+ +[CSCompanionRuntimeThresholdKeys _originatingPlatformForSelfPlatform:servingPlatform:]
+ +[CSCompanionRuntimeThresholdKeys devicePrefixForPlatform:]
+ +[CSCompanionRuntimeThresholdKeys micSourceForRecordRoute:]
+ +[CSCompanionRuntimeThresholdKeys overrideKeyForSelfPlatform:servingPlatform:recordRoute:]
+ +[CSCompanionRuntimeThresholdKeys sectionKeysForSelfPlatform:servingPlatform:recordRoute:]
+ +[CSLinwoodEnabledAndAvailableMonitor sharedInstance]
+ +[CSRequestMutex CSRequestMutexOwnerDescription:]
+ +[CSRequestMutex CSRequestMutexOwnerShortName:]
+ +[CSRequestMutexController CSRequestMutexControllerResourceTypeDescription:]
+ +[CSRequestMutexController DefaultHoldTimeInMillisForResourceTypeDescription:]
+ +[CSRequestMutexController MaxHoldTimeInMillisForResourceTypeDescription:]
+ +[CSRequestMutexController sharedInstance]
+ +[CSUtils isDeviceSelectionParticipating]
+ +[CSUtils isDeviceSelectionShadowModeEnabled]
+ +[CSUtils isRequestLockEnforcingSingleTenancyEnabled]
+ +[CSUtils shouldExcludeBSSChannelsFromVoiceTrigger]
+ +[CSUtils supportMindPalaceAmbient]
+ +[CSUtils supportsVoiceTriggerAssetChannelSelection]
+ +[CSVoiceTriggerFirstPassConfigDecoder _processingChannelsBitSetWithoutBSS:]
+ +[CSVoiceTriggerFirstPassConfigDecoder decodeConfigFrom:shouldExcludeBSSChannels:]
+ +[CSVoiceTriggerFirstPassConfigDecoder decodeConfigFrom:shouldExcludeBSSChannels:isLinwoodEnabledAndAvailable:]
+ -[CSAudioPowerProvider _deactivateLocked]
+ -[CSAudioStartStreamOption serverAudioSentByClient]
+ -[CSAudioStartStreamOption setServerAudioSentByClient:]
+ -[CSFPreferences deviceSelectionTriggerAudioSliceMs]
+ -[CSFPreferences selfTapGainOverride]
+ -[CSFPreferences spectralMeterNormalizationEnabledOverride]
+ -[CSLinwoodEnabledAndAvailableMonitor _checkLinwoodEnabledAndAvailable]
+ -[CSLinwoodEnabledAndAvailableMonitor _didReceiveSiriCapabilitiesChanged]
+ -[CSLinwoodEnabledAndAvailableMonitor _notifyObserver:withEnabledAndAvailable:]
+ -[CSLinwoodEnabledAndAvailableMonitor _startMonitoringWithQueue:]
+ -[CSLinwoodEnabledAndAvailableMonitor _stopMonitoring]
+ -[CSLinwoodEnabledAndAvailableMonitor init]
+ -[CSLinwoodEnabledAndAvailableMonitor isEnabledAndAvailable]
+ -[CSRequestMutex .cxx_destruct]
+ -[CSRequestMutex _armAutoReleaseForOwner:generation:holdTimeInMillis:]
+ -[CSRequestMutex _clearOwnerLocked]
+ -[CSRequestMutex _notifyOwnerDidChangeFrom:to:]
+ -[CSRequestMutex _tryAcquireForOwner:client:requestId:holdTimeInMillis:]
+ -[CSRequestMutex initWithSingleTenancyEnforced:]
+ -[CSRequestMutex init]
+ -[CSRequestMutex ownerRequestId]
+ -[CSRequestMutex registerObserver:]
+ -[CSRequestMutex releaseAllForRemoteClient:]
+ -[CSRequestMutex releaseForOwner:requestId:]
+ -[CSRequestMutex releaseForRemoteClient:requestId:isCompanionRequest:]
+ -[CSRequestMutex releaseForRequestId:]
+ -[CSRequestMutex requestMutexOwner]
+ -[CSRequestMutex tryAcquireForCompanionWithRequestId:holdTimeInMillis:]
+ -[CSRequestMutex tryAcquireForLocalWithRequestId:holdTimeInMillis:]
+ -[CSRequestMutex tryAcquireForOwner:requestId:holdTimeInMillis:]
+ -[CSRequestMutex tryAcquireForRemoteClient:requestId:isCompanionRequest:holdTimeInMillis:]
+ -[CSRequestMutex unregisterObserver:]
+ -[CSRequestMutexController .cxx_destruct]
+ -[CSRequestMutexController _aggregateOwnersRuntimeType]
+ -[CSRequestMutexController _areAllResourcesAvailableToAcquireByOwner:resourceType:]
+ -[CSRequestMutexController _publishAggregateOwnerIfChanged]
+ -[CSRequestMutexController _resourceOwnerDescription]
+ -[CSRequestMutexController areAllResourcesAvailableToAcquireByOwner:resourceType:]
+ -[CSRequestMutexController dealloc]
+ -[CSRequestMutexController initWithSingleTenancyEnforced:]
+ -[CSRequestMutexController init]
+ -[CSRequestMutexController registerObserver:]
+ -[CSRequestMutexController releaseAllForRemoteClient:]
+ -[CSRequestMutexController releaseForOwner:requestId:resourceType:]
+ -[CSRequestMutexController releaseForRemoteClient:requestId:isCompanionRequest:resourceType:]
+ -[CSRequestMutexController releaseForRequestId:resourceType:]
+ -[CSRequestMutexController releaseIfHeldForRequestId:resourceType:]
+ -[CSRequestMutexController requestMutexOwnerDidChange:]
+ -[CSRequestMutexController tryAcquireForCompanionWithRequestId:resourceType:]
+ -[CSRequestMutexController tryAcquireForLocalWithRequestId:resourceType:]
+ -[CSRequestMutexController tryAcquireForOwner:requestId:resourceType:]
+ -[CSRequestMutexController tryAcquireForRemoteClient:requestId:isCompanionRequest:resourceType:holdTimeInMillis:]
+ -[CSRequestMutexController unregisterObserver:]
+ -[CSVoiceTriggerSecondPassConfig allowedChannelsBitsetLinwood]
+ -[CSVoiceTriggerSecondPassConfig allowedChannelsBitset]
+ -[CSVoiceTriggerSecondPassConfig initWithPreTriggerAudioTime:prependingAudioTime:trailingAudioTime:resourcePath:configPathNDAPI:useRecognizerCombination:configPathRecognizer:useKeywordSpotting:phraseConfigs:wearerDetectionConfig:quasarCheckerResultCutOffCount:useTimeBasedTriggerLength:allowedChannelsBitset:allowedChannelsBitsetLinwood:]
+ GCC_except_table1012
+ GCC_except_table1013
+ GCC_except_table1020
+ GCC_except_table1024
+ GCC_except_table1025
+ GCC_except_table1029
+ GCC_except_table1033
+ GCC_except_table1034
+ GCC_except_table1048
+ GCC_except_table1120
+ GCC_except_table1121
+ GCC_except_table1131
+ GCC_except_table1465
+ GCC_except_table1496
+ GCC_except_table1579
+ GCC_except_table1583
+ GCC_except_table1584
+ GCC_except_table1585
+ GCC_except_table1587
+ GCC_except_table1588
+ GCC_except_table1591
+ GCC_except_table1599
+ GCC_except_table1608
+ GCC_except_table1610
+ GCC_except_table1611
+ GCC_except_table1614
+ GCC_except_table1615
+ GCC_except_table1616
+ GCC_except_table1618
+ GCC_except_table1622
+ GCC_except_table1800
+ GCC_except_table2014
+ GCC_except_table2015
+ GCC_except_table2016
+ GCC_except_table2020
+ GCC_except_table2023
+ GCC_except_table2024
+ GCC_except_table2026
+ GCC_except_table2032
+ GCC_except_table2038
+ GCC_except_table2040
+ GCC_except_table2041
+ GCC_except_table2107
+ GCC_except_table2112
+ GCC_except_table2177
+ GCC_except_table2230
+ GCC_except_table2231
+ GCC_except_table2233
+ GCC_except_table2234
+ GCC_except_table2240
+ GCC_except_table2251
+ GCC_except_table2264
+ GCC_except_table2307
+ GCC_except_table2325
+ GCC_except_table2406
+ GCC_except_table2506
+ GCC_except_table2543
+ GCC_except_table2714
+ GCC_except_table2718
+ GCC_except_table2794
+ GCC_except_table2805
+ GCC_except_table2807
+ GCC_except_table2812
+ GCC_except_table2829
+ GCC_except_table2836
+ GCC_except_table2838
+ GCC_except_table2856
+ GCC_except_table2877
+ GCC_except_table2927
+ GCC_except_table2931
+ GCC_except_table2990
+ GCC_except_table2992
+ GCC_except_table2993
+ GCC_except_table3162
+ GCC_except_table3302
+ GCC_except_table3310
+ GCC_except_table3320
+ GCC_except_table3329
+ GCC_except_table3332
+ GCC_except_table3334
+ GCC_except_table3335
+ GCC_except_table3374
+ GCC_except_table3380
+ GCC_except_table3430
+ GCC_except_table3523
+ GCC_except_table3535
+ GCC_except_table3541
+ GCC_except_table3548
+ GCC_except_table3560
+ GCC_except_table3585
+ GCC_except_table3586
+ GCC_except_table3587
+ GCC_except_table3588
+ GCC_except_table3613
+ GCC_except_table3626
+ GCC_except_table3819
+ GCC_except_table3879
+ GCC_except_table3936
+ GCC_except_table3969
+ GCC_except_table3970
+ GCC_except_table3975
+ GCC_except_table3976
+ GCC_except_table3977
+ GCC_except_table3997
+ GCC_except_table3999
+ GCC_except_table4004
+ GCC_except_table4005
+ GCC_except_table4006
+ GCC_except_table4014
+ GCC_except_table4038
+ GCC_except_table4085
+ GCC_except_table4106
+ GCC_except_table4107
+ GCC_except_table4108
+ GCC_except_table4109
+ GCC_except_table4196
+ GCC_except_table4197
+ GCC_except_table4208
+ GCC_except_table4210
+ GCC_except_table4213
+ GCC_except_table4216
+ GCC_except_table4220
+ GCC_except_table4222
+ GCC_except_table4226
+ GCC_except_table4230
+ GCC_except_table4233
+ GCC_except_table4242
+ GCC_except_table4243
+ GCC_except_table4245
+ GCC_except_table4247
+ GCC_except_table4248
+ GCC_except_table4253
+ GCC_except_table4254
+ GCC_except_table4259
+ GCC_except_table4260
+ GCC_except_table4263
+ GCC_except_table4266
+ GCC_except_table4269
+ GCC_except_table4270
+ GCC_except_table4271
+ GCC_except_table4273
+ GCC_except_table4274
+ GCC_except_table4276
+ GCC_except_table4277
+ GCC_except_table4278
+ GCC_except_table4279
+ GCC_except_table4307
+ GCC_except_table4357
+ GCC_except_table4363
+ GCC_except_table4427
+ GCC_except_table4428
+ GCC_except_table4429
+ GCC_except_table4430
+ GCC_except_table4432
+ GCC_except_table4433
+ GCC_except_table4458
+ GCC_except_table4465
+ GCC_except_table4467
+ GCC_except_table4480
+ GCC_except_table4489
+ GCC_except_table4491
+ GCC_except_table4492
+ GCC_except_table4493
+ GCC_except_table4494
+ GCC_except_table4495
+ GCC_except_table4496
+ GCC_except_table4499
+ GCC_except_table4502
+ GCC_except_table4504
+ GCC_except_table4508
+ GCC_except_table4510
+ GCC_except_table4511
+ GCC_except_table4513
+ GCC_except_table4515
+ GCC_except_table4517
+ GCC_except_table4519
+ GCC_except_table4526
+ GCC_except_table4539
+ GCC_except_table4540
+ GCC_except_table4542
+ GCC_except_table4543
+ GCC_except_table4545
+ GCC_except_table4547
+ GCC_except_table4548
+ GCC_except_table4549
+ GCC_except_table4556
+ GCC_except_table4558
+ GCC_except_table4562
+ GCC_except_table4563
+ GCC_except_table4593
+ GCC_except_table4731
+ GCC_except_table4738
+ GCC_except_table4821
+ GCC_except_table4893
+ GCC_except_table4903
+ GCC_except_table4951
+ GCC_except_table4952
+ GCC_except_table4953
+ GCC_except_table4955
+ GCC_except_table4956
+ GCC_except_table4959
+ GCC_except_table4961
+ GCC_except_table4963
+ GCC_except_table4964
+ GCC_except_table4966
+ GCC_except_table4968
+ GCC_except_table4969
+ GCC_except_table4971
+ GCC_except_table5007
+ GCC_except_table5073
+ GCC_except_table5078
+ GCC_except_table5119
+ GCC_except_table5185
+ GCC_except_table624
+ GCC_except_table746
+ GCC_except_table752
+ GCC_except_table755
+ GCC_except_table761
+ GCC_except_table917
+ GCC_except_table926
+ GCC_except_table988
+ GCC_except_table989
+ GCC_except_table996
+ _AFDeviceSelectionParticipating
+ _AFIsLinwoodEnabledAndAvailable
+ _OBJC_CLASS_$_CSCompanionRuntimeThresholdKeys
+ _OBJC_CLASS_$_CSLinwoodEnabledAndAvailableMonitor
+ _OBJC_CLASS_$_CSRequestMutex
+ _OBJC_CLASS_$_CSRequestMutexController
+ _OBJC_IVAR_$_CSAudioPowerProvider._cachedSpectralNormalizationEnabledOverride
+ _OBJC_IVAR_$_CSAudioPowerProvider._deactivateLock
+ _OBJC_IVAR_$_CSAudioPowerProvider._selfTapGain
+ _OBJC_IVAR_$_CSAudioPowerProvider._selfTapScratchBuffer
+ _OBJC_IVAR_$_CSAudioPowerProvider._selfTapScratchCapacity
+ _OBJC_IVAR_$_CSAudioPowerProvider._unconfiguredPowerMeterDropHeartbeat
+ _OBJC_IVAR_$_CSAudioStartStreamOption._serverAudioSentByClient
+ _OBJC_IVAR_$_CSLinwoodEnabledAndAvailableMonitor._isLinwoodEnabledAndAvailable
+ _OBJC_IVAR_$_CSRequestMutex._autoReleaseQueue
+ _OBJC_IVAR_$_CSRequestMutex._generation
+ _OBJC_IVAR_$_CSRequestMutex._lock
+ _OBJC_IVAR_$_CSRequestMutex._observers
+ _OBJC_IVAR_$_CSRequestMutex._ownersRequestId
+ _OBJC_IVAR_$_CSRequestMutex._ownersRuntimeType
+ _OBJC_IVAR_$_CSRequestMutex._ownersXPCConnectionId
+ _OBJC_IVAR_$_CSRequestMutex._singleTenancyEnforced
+ _OBJC_IVAR_$_CSRequestMutexController._lock
+ _OBJC_IVAR_$_CSRequestMutexController._observerNotificationQueue
+ _OBJC_IVAR_$_CSRequestMutexController._observers
+ _OBJC_IVAR_$_CSRequestMutexController._publishedOwnersRuntimeType
+ _OBJC_IVAR_$_CSRequestMutexController._requestMutexes
+ _OBJC_IVAR_$_CSRequestMutexController._singleTenancyEnforced
+ _OBJC_IVAR_$_CSVoiceTriggerSecondPassConfig._allowedChannelsBitset
+ _OBJC_IVAR_$_CSVoiceTriggerSecondPassConfig._allowedChannelsBitsetLinwood
+ _OBJC_METACLASS_$_CSCompanionRuntimeThresholdKeys
+ _OBJC_METACLASS_$_CSLinwoodEnabledAndAvailableMonitor
+ _OBJC_METACLASS_$_CSRequestMutex
+ _OBJC_METACLASS_$_CSRequestMutexController
+ __OBJC_$_CLASS_METHODS_CSCompanionRuntimeThresholdKeys
+ __OBJC_$_CLASS_METHODS_CSLinwoodEnabledAndAvailableMonitor
+ __OBJC_$_CLASS_METHODS_CSRequestMutex
+ __OBJC_$_CLASS_METHODS_CSRequestMutexController
+ __OBJC_$_INSTANCE_METHODS_CSLinwoodEnabledAndAvailableMonitor
+ __OBJC_$_INSTANCE_METHODS_CSRequestMutex
+ __OBJC_$_INSTANCE_METHODS_CSRequestMutexController
+ __OBJC_$_INSTANCE_VARIABLES_CSLinwoodEnabledAndAvailableMonitor
+ __OBJC_$_INSTANCE_VARIABLES_CSRequestMutex
+ __OBJC_$_INSTANCE_VARIABLES_CSRequestMutexController
+ __OBJC_$_PROP_LIST_CSRequestMutex
+ __OBJC_$_PROP_LIST_CSRequestMutexController
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSRequestMutexObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSRequestMutexObserver
+ __OBJC_$_PROTOCOL_REFS_CSRequestMutexObserver
+ __OBJC_CLASS_PROTOCOLS_$_CSRequestMutexController
+ __OBJC_CLASS_RO_$_CSCompanionRuntimeThresholdKeys
+ __OBJC_CLASS_RO_$_CSLinwoodEnabledAndAvailableMonitor
+ __OBJC_CLASS_RO_$_CSRequestMutex
+ __OBJC_CLASS_RO_$_CSRequestMutexController
+ __OBJC_LABEL_PROTOCOL_$_CSRequestMutexObserver
+ __OBJC_METACLASS_RO_$_CSCompanionRuntimeThresholdKeys
+ __OBJC_METACLASS_RO_$_CSLinwoodEnabledAndAvailableMonitor
+ __OBJC_METACLASS_RO_$_CSRequestMutex
+ __OBJC_METACLASS_RO_$_CSRequestMutexController
+ __OBJC_PROTOCOL_$_CSRequestMutexObserver
+ ___42+[CSRequestMutexController sharedInstance]_block_invoke
+ ___52-[CSFPreferences deviceSelectionTriggerAudioSliceMs]_block_invoke
+ ___53+[CSLinwoodEnabledAndAvailableMonitor sharedInstance]_block_invoke
+ ___53+[CSUtils isRequestLockEnforcingSingleTenancyEnabled]_block_invoke
+ ___55-[CSAudioProvider _handleDidStopAudioStreamWithReason:]_block_invoke_3
+ ___55-[CSRequestMutexController requestMutexOwnerDidChange:]_block_invoke
+ ___70-[CSRequestMutex _armAutoReleaseForOwner:generation:holdTimeInMillis:]_block_invoke
+ ___73-[CSLinwoodEnabledAndAvailableMonitor _didReceiveSiriCapabilitiesChanged]_block_invoke
+ ___block_descriptor_100_e100_i28?0r^{AudioTimeStamp=dQdQ{SMPTETime=ssIIIssss}II}8I16r^{AudioBufferList=I[1{AudioBuffer=II^v}]}20l
+ ___block_descriptor_57_e8_32s_e5_v8?0l
+ __siriCapabilitiesDidChange
+ _deviceSelectionTriggerAudioSliceMs.durationMs
+ _deviceSelectionTriggerAudioSliceMs.onceToken
+ _isRequestLockEnforcingSingleTenancyEnabled.onceToken
+ _isRequestLockEnforcingSingleTenancyEnabled.result
+ _kAFSiriCapabilitiesDidChangeNotification
+ _objc_msgSend$CSRequestMutexControllerResourceTypeDescription:
+ _objc_msgSend$CSRequestMutexOwnerDescription:
+ _objc_msgSend$CSRequestMutexOwnerShortName:
+ _objc_msgSend$DefaultHoldTimeInMillisForResourceTypeDescription:
+ _objc_msgSend$MaxHoldTimeInMillisForResourceTypeDescription:
+ _objc_msgSend$_aggregateOwnersRuntimeType
+ _objc_msgSend$_areAllResourcesAvailableToAcquireByOwner:resourceType:
+ _objc_msgSend$_armAutoReleaseForOwner:generation:holdTimeInMillis:
+ _objc_msgSend$_checkLinwoodEnabledAndAvailable
+ _objc_msgSend$_clearOwnerLocked
+ _objc_msgSend$_deactivateLocked
+ _objc_msgSend$_didReceiveSiriCapabilitiesChanged
+ _objc_msgSend$_notifyObserver:withEnabledAndAvailable:
+ _objc_msgSend$_notifyOwnerDidChangeFrom:to:
+ _objc_msgSend$_originatingPlatformForSelfPlatform:servingPlatform:
+ _objc_msgSend$_processingChannelsBitSetWithoutBSS:
+ _objc_msgSend$_publishAggregateOwnerIfChanged
+ _objc_msgSend$_resourceOwnerDescription
+ _objc_msgSend$_tryAcquireForOwner:client:requestId:holdTimeInMillis:
+ _objc_msgSend$decodeConfigFrom:shouldExcludeBSSChannels:
+ _objc_msgSend$decodeConfigFrom:shouldExcludeBSSChannels:isLinwoodEnabledAndAvailable:
+ _objc_msgSend$devicePrefixForPlatform:
+ _objc_msgSend$initWithPreTriggerAudioTime:prependingAudioTime:trailingAudioTime:resourcePath:configPathNDAPI:useRecognizerCombination:configPathRecognizer:useKeywordSpotting:phraseConfigs:wearerDetectionConfig:quasarCheckerResultCutOffCount:useTimeBasedTriggerLength:allowedChannelsBitset:allowedChannelsBitsetLinwood:
+ _objc_msgSend$initWithSingleTenancyEnforced:
+ _objc_msgSend$isAudioStreamConsumingEnabled
+ _objc_msgSend$isDeviceSelectionShadowModeEnabled
+ _objc_msgSend$isMedocFeatureEnabled
+ _objc_msgSend$isRequestLockEnforcingSingleTenancyEnabled
+ _objc_msgSend$linwoodEnabledAndAvailableMonitor:didReceiveEnabledAndAvailable:
+ _objc_msgSend$micSourceForRecordRoute:
+ _objc_msgSend$ownerRequestId
+ _objc_msgSend$releaseAllForRemoteClient:
+ _objc_msgSend$releaseForOwner:requestId:
+ _objc_msgSend$releaseForRemoteClient:requestId:isCompanionRequest:
+ _objc_msgSend$releaseForRequestId:
+ _objc_msgSend$releaseForRequestId:resourceType:
+ _objc_msgSend$requestMutexOwner
+ _objc_msgSend$requestMutexOwnerDidChange:
+ _objc_msgSend$selfTapGainOverride
+ _objc_msgSend$setServerAudioSentByClient:
+ _objc_msgSend$spectralMeterNormalizationEnabledOverride
+ _objc_msgSend$supportMindPalaceAmbient
+ _objc_msgSend$supportsVoiceTriggerAssetChannelSelection
+ _objc_msgSend$tryAcquireForOwner:requestId:holdTimeInMillis:
+ _objc_msgSend$tryAcquireForOwner:requestId:resourceType:
+ _objc_msgSend$tryAcquireForRemoteClient:requestId:isCompanionRequest:holdTimeInMillis:
+ _os_unfair_recursive_lock_lock_with_options
+ _os_unfair_recursive_lock_unlock
- +[CSUtils isDeviceSelectionEnabled]
- -[CSFPreferences deviceSelectionShazamDuration]
- -[CSVoiceTriggerSecondPassConfig initWithPreTriggerAudioTime:prependingAudioTime:trailingAudioTime:resourcePath:configPathNDAPI:useRecognizerCombination:configPathRecognizer:useKeywordSpotting:phraseConfigs:wearerDetectionConfig:quasarCheckerResultCutOffCount:useTimeBasedTriggerLength:]
- GCC_except_table1009
- GCC_except_table1010
- GCC_except_table1015
- GCC_except_table1016
- GCC_except_table1022
- GCC_except_table1026
- GCC_except_table1027
- GCC_except_table1031
- GCC_except_table1046
- GCC_except_table1116
- GCC_except_table1119
- GCC_except_table1129
- GCC_except_table1452
- GCC_except_table1483
- GCC_except_table1566
- GCC_except_table1570
- GCC_except_table1571
- GCC_except_table1572
- GCC_except_table1573
- GCC_except_table1574
- GCC_except_table1575
- GCC_except_table1576
- GCC_except_table1577
- GCC_except_table1578
- GCC_except_table1595
- GCC_except_table1597
- GCC_except_table1598
- GCC_except_table1601
- GCC_except_table1605
- GCC_except_table1609
- GCC_except_table1787
- GCC_except_table2000
- GCC_except_table2001
- GCC_except_table2002
- GCC_except_table2003
- GCC_except_table2007
- GCC_except_table2010
- GCC_except_table2011
- GCC_except_table2019
- GCC_except_table2025
- GCC_except_table2027
- GCC_except_table2028
- GCC_except_table2094
- GCC_except_table2099
- GCC_except_table2162
- GCC_except_table2215
- GCC_except_table2216
- GCC_except_table2218
- GCC_except_table2219
- GCC_except_table2225
- GCC_except_table2236
- GCC_except_table2249
- GCC_except_table2292
- GCC_except_table2310
- GCC_except_table2391
- GCC_except_table2491
- GCC_except_table2528
- GCC_except_table2699
- GCC_except_table2703
- GCC_except_table2779
- GCC_except_table2790
- GCC_except_table2792
- GCC_except_table2797
- GCC_except_table2799
- GCC_except_table2821
- GCC_except_table2823
- GCC_except_table2841
- GCC_except_table2862
- GCC_except_table2912
- GCC_except_table2916
- GCC_except_table2975
- GCC_except_table2977
- GCC_except_table2978
- GCC_except_table3145
- GCC_except_table3285
- GCC_except_table3293
- GCC_except_table3303
- GCC_except_table3312
- GCC_except_table3315
- GCC_except_table3317
- GCC_except_table3318
- GCC_except_table3357
- GCC_except_table3363
- GCC_except_table3410
- GCC_except_table3503
- GCC_except_table3515
- GCC_except_table3521
- GCC_except_table3528
- GCC_except_table3540
- GCC_except_table3565
- GCC_except_table3566
- GCC_except_table3567
- GCC_except_table3568
- GCC_except_table3593
- GCC_except_table3606
- GCC_except_table3777
- GCC_except_table3837
- GCC_except_table3851
- GCC_except_table3894
- GCC_except_table3927
- GCC_except_table3928
- GCC_except_table3930
- GCC_except_table3933
- GCC_except_table3934
- GCC_except_table3955
- GCC_except_table3957
- GCC_except_table3962
- GCC_except_table3963
- GCC_except_table3964
- GCC_except_table3996
- GCC_except_table4022
- GCC_except_table4043
- GCC_except_table4065
- GCC_except_table4066
- GCC_except_table4067
- GCC_except_table4154
- GCC_except_table4155
- GCC_except_table4166
- GCC_except_table4168
- GCC_except_table4169
- GCC_except_table4170
- GCC_except_table4171
- GCC_except_table4174
- GCC_except_table4175
- GCC_except_table4178
- GCC_except_table4179
- GCC_except_table4180
- GCC_except_table4181
- GCC_except_table4184
- GCC_except_table4185
- GCC_except_table4186
- GCC_except_table4187
- GCC_except_table4188
- GCC_except_table4191
- GCC_except_table4194
- GCC_except_table4200
- GCC_except_table4201
- GCC_except_table4203
- GCC_except_table4205
- GCC_except_table4206
- GCC_except_table4218
- GCC_except_table4224
- GCC_except_table4231
- GCC_except_table4232
- GCC_except_table4234
- GCC_except_table4235
- GCC_except_table4237
- GCC_except_table4315
- GCC_except_table4321
- GCC_except_table4377
- GCC_except_table4378
- GCC_except_table4385
- GCC_except_table4386
- GCC_except_table4387
- GCC_except_table4388
- GCC_except_table4390
- GCC_except_table4391
- GCC_except_table4413
- GCC_except_table4415
- GCC_except_table4416
- GCC_except_table4417
- GCC_except_table4421
- GCC_except_table4422
- GCC_except_table4423
- GCC_except_table4424
- GCC_except_table4425
- GCC_except_table4426
- GCC_except_table4438
- GCC_except_table4447
- GCC_except_table4449
- GCC_except_table4450
- GCC_except_table4451
- GCC_except_table4452
- GCC_except_table4453
- GCC_except_table4454
- GCC_except_table4460
- GCC_except_table4469
- GCC_except_table4471
- GCC_except_table4473
- GCC_except_table4475
- GCC_except_table4477
- GCC_except_table4484
- GCC_except_table4498
- GCC_except_table4500
- GCC_except_table4507
- GCC_except_table4514
- GCC_except_table4516
- GCC_except_table4520
- GCC_except_table4521
- GCC_except_table4551
- GCC_except_table4662
- GCC_except_table4669
- GCC_except_table4752
- GCC_except_table4813
- GCC_except_table4823
- GCC_except_table4871
- GCC_except_table4872
- GCC_except_table4873
- GCC_except_table4875
- GCC_except_table4876
- GCC_except_table4879
- GCC_except_table4880
- GCC_except_table4882
- GCC_except_table4883
- GCC_except_table4885
- GCC_except_table4887
- GCC_except_table4888
- GCC_except_table4890
- GCC_except_table4926
- GCC_except_table4992
- GCC_except_table4997
- GCC_except_table5038
- GCC_except_table5104
- GCC_except_table622
- GCC_except_table744
- GCC_except_table748
- GCC_except_table753
- GCC_except_table759
- GCC_except_table915
- GCC_except_table924
- GCC_except_table986
- GCC_except_table987
- GCC_except_table994
- ___47-[CSFPreferences deviceSelectionShazamDuration]_block_invoke
- ___block_descriptor_80_e100_i28?0r^{AudioTimeStamp=dQdQ{SMPTETime=ssIIIssss}II}8I16r^{AudioBufferList=I[1{AudioBuffer=II^v}]}20l
- _deviceSelectionShazamDuration.atoaDuration
- _deviceSelectionShazamDuration.onceToken
- _objc_msgSend$initWithPreTriggerAudioTime:prependingAudioTime:trailingAudioTime:resourcePath:configPathNDAPI:useRecognizerCombination:configPathRecognizer:useKeywordSpotting:phraseConfigs:wearerDetectionConfig:quasarCheckerResultCutOffCount:useTimeBasedTriggerLength:
- _objc_msgSend$isDeviceSelectionEnabled
CStrings:
+ "\"5\xb1B"
+ "%s #requestLock aggregate owner changed from %s to %s, notifying %lu observer(s)"
+ "%s #requestLock hold of %ld ms for %s expiry superseded, no-op"
+ "%s #requestLock hold of %ld ms for %s request %@ expired: the request that took the hold over never released it, owner now is none"
+ "%s #requestLock hold of %ld ms for %s request %@ expired: the reserving client never started a request, owner now is none"
+ "%s #requestLock lock owner changed but aggregate owner unchanged: %s, %@"
+ "%s #requestLock owner changed from %s to %s, notifying %lu observer(s)"
+ "%s #requestLock releaseAllForRemoteClient: remote client went away holding %s ownership, owner now is none"
+ "%s #requestLock releaseForOwner: %s, requestId: %@, resource: %s, %@"
+ "%s #requestLock releaseForOwner: no-op for %@, nobody holds the mutex"
+ "%s #requestLock releaseForOwner: no-op for %s request %@, %s holds the mutex for %@"
+ "%s #requestLock releaseForOwner: released %s ownership held by %@, released by %@, owner now is none"
+ "%s #requestLock releaseForRemoteClient: %s, requestId: %@, resource: %s, %@"
+ "%s #requestLock releaseForRemoteClient: no-op, remote client does not hold %s ownership for %@ (held for %@)"
+ "%s #requestLock releaseForRemoteClient: released %s ownership held for %@, owner now is none"
+ "%s #requestLock releaseForRequestId: no-op for %@, nobody holds the mutex"
+ "%s #requestLock releaseForRequestId: released %s ownership held by %@, released by %@, owner now is none"
+ "%s #requestLock releaseForRequestId: requestId: %@, resource: %s, %@"
+ "%s #requestLock releaseIfHeldForRequestId: requestId: %@, resource: %s, held for it: %d, %@"
+ "%s #requestLock resource %s is unavailable to owner %s b/c resource %s is already held by %s."
+ "%s #requestLock resources disagree on owner: %s and %s both hold one, reporting %s"
+ "%s #requestLock tryAcquire called when feature, RequestLockEnforcingSingleTenancyEnabled, not enabled"
+ "%s #requestLock tryAcquire for %s request %@: acquired (previous owner: %s for %@, holdTimeInMillis: %ld, remote client: %d)"
+ "%s #requestLock tryAcquire for %s request %@: blocked, %s currently owns the mutex for %@"
+ "%s #requestLock tryAcquireForOwner: %s, requestId: %@, resource: %s, succeeded: %i, %@"
+ "%s #requestLock tryAcquireForRemoteClient: %s, requestId: %@, resource: %s, succeeded: %i, %@"
+ "%s #requestLock tryAcquireForRemoteClient: rejected, no xpcConnectionId supplied"
+ "%s Failed to allocate SelfTap gain scratch buffer; falling back to unity gain"
+ "%s Ignoring asset processingChannelsBitset=0x%{public}llx, using 0x%{public}llx"
+ "%s Ignoring invalid selfTapGainOverride %.3f; using unity gain"
+ "%s Linwood enabled and available changed to %{public}@"
+ "%s Linwood is enabled and available, processingChannelsBitset=0x%{public}llx"
+ "%s Moving-window normalization %{public}s by override for route '%{public}@'"
+ "%s Power meter is not configured yet, dropping audio chunk, heartbeat = %llu"
+ "%s Second pass allowedChannelsBitset=0x%{public}llx, allowedChannelsBitset_linwood=0x%{public}llx"
+ "%s SelfTap gain override applied: %.3fx (%.2f dB)"
+ "%s Start monitoring: Linwood enabled and available, Linwood is %{public}@"
+ "%s Stop monitoring: Linwood enabled and available"
+ "+[CSVoiceTriggerFirstPassConfigDecoder decodeConfigFrom:shouldExcludeBSSChannels:isLinwoodEnabledAndAvailable:]"
+ "-[CSAudioPowerProvider _deactivateLocked]"
+ "-[CSLinwoodEnabledAndAvailableMonitor _didReceiveSiriCapabilitiesChanged]"
+ "-[CSLinwoodEnabledAndAvailableMonitor _startMonitoringWithQueue:]"
+ "-[CSLinwoodEnabledAndAvailableMonitor _stopMonitoring]"
+ "-[CSRequestMutex _armAutoReleaseForOwner:generation:holdTimeInMillis:]_block_invoke"
+ "-[CSRequestMutex _notifyOwnerDidChangeFrom:to:]"
+ "-[CSRequestMutex _tryAcquireForOwner:client:requestId:holdTimeInMillis:]"
+ "-[CSRequestMutex releaseAllForRemoteClient:]"
+ "-[CSRequestMutex releaseForOwner:requestId:]"
+ "-[CSRequestMutex releaseForRemoteClient:requestId:isCompanionRequest:]"
+ "-[CSRequestMutex releaseForRequestId:]"
+ "-[CSRequestMutex tryAcquireForRemoteClient:requestId:isCompanionRequest:holdTimeInMillis:]"
+ "-[CSRequestMutexController _aggregateOwnersRuntimeType]"
+ "-[CSRequestMutexController _areAllResourcesAvailableToAcquireByOwner:resourceType:]"
+ "-[CSRequestMutexController _publishAggregateOwnerIfChanged]"
+ "-[CSRequestMutexController releaseForOwner:requestId:resourceType:]"
+ "-[CSRequestMutexController releaseForRemoteClient:requestId:isCompanionRequest:resourceType:]"
+ "-[CSRequestMutexController releaseForRequestId:resourceType:]"
+ "-[CSRequestMutexController releaseIfHeldForRequestId:resourceType:]"
+ "-[CSRequestMutexController tryAcquireForOwner:requestId:resourceType:]"
+ "-[CSRequestMutexController tryAcquireForRemoteClient:requestId:isCompanionRequest:resourceType:holdTimeInMillis:]"
+ "BluetoothDoAP"
+ "BuiltIn"
+ "CSRequestMutex.autoRelease"
+ "CSRequestMutexController.observerNotification"
+ "Device Selection Trigger Audio Slice Ms"
+ "[serverAudioSentByClient = %@]"
+ "allowedChannelsBitset"
+ "allowedChannelsBitset_linwood"
+ "appletv"
+ "audio"
+ "audioaccessory"
+ "companion"
+ "enabled and available"
+ "homeaccessory"
+ "ipad"
+ "iphone"
+ "local"
+ "none"
+ "not enabled or not available"
+ "override_selftap_gain"
+ "processingChannelsBitset_linwood"
+ "request_lock"
+ "resourceOwners: (%c, %c, %c)"
+ "serverAudioSentByClient"
+ "spectral_meter_normalization_enabled"
+ "unspecified"
+ "vision"
+ "watch"
- "+[CSVoiceTriggerFirstPassConfigDecoder decodeConfigFrom:]"
- "-[CSAudioPowerProvider deactivate]"
- "Device Selection Shazam Duration"
```
