## AssistantServices

> `/System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/AssistantServices`

```diff

-3605.31.1.14.2
-  __TEXT.__text: 0x19f550
-  __TEXT.__objc_methlist: 0x1f104
-  __TEXT.__const: 0x3f0
+3610.11.2.4.1
+  __TEXT.__text: 0x1a4d24
+  __TEXT.__objc_methlist: 0x1f29c
+  __TEXT.__const: 0x400
   __TEXT.__dlopen_cstrs: 0x421
-  __TEXT.__gcc_except_tab: 0x1fc0
-  __TEXT.__cstring: 0x3ba11
-  __TEXT.__oslogstring: 0xef74
+  __TEXT.__gcc_except_tab: 0x20c8
+  __TEXT.__cstring: 0x3c112
+  __TEXT.__oslogstring: 0xf97e
   __TEXT.__ustring: 0x2ac
-  __TEXT.__unwind_info: 0x9910
+  __TEXT.__unwind_info: 0x9a58
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x42e0
+  __DATA_CONST.__const: 0x4388
   __DATA_CONST.__objc_classlist: 0xef8
   __DATA_CONST.__objc_catlist: 0x2a0
   __DATA_CONST.__objc_protolist: 0x5f8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xbe20
+  __DATA_CONST.__objc_selrefs: 0xbf10
   __DATA_CONST.__objc_protorefs: 0x180
   __DATA_CONST.__objc_superrefs: 0xf10
   __DATA_CONST.__objc_arraydata: 0x2450
-  __DATA_CONST.__got: 0x1660
-  __AUTH_CONST.__const: 0x8370
-  __AUTH_CONST.__cfstring: 0x27fe0
-  __AUTH_CONST.__objc_const: 0x36530
+  __DATA_CONST.__got: 0x1780
+  __AUTH_CONST.__const: 0x84a0
+  __AUTH_CONST.__cfstring: 0x28240
+  __AUTH_CONST.__objc_const: 0x36740
   __AUTH_CONST.__objc_intobj: 0x2730
   __AUTH_CONST.__objc_dictobj: 0xd20
   __AUTH_CONST.__objc_arrayobj: 0x5d0
   __AUTH_CONST.__objc_doubleobj: 0x40
-  __AUTH_CONST.__auth_got: 0x990
+  __AUTH_CONST.__auth_got: 0x9b0
   __AUTH.__objc_data: 0x84a8
   __AUTH.__data: 0xd0
-  __DATA.__objc_ivar: 0x259c
+  __AUTH.__thread_vars: 0x30
+  __AUTH.__thread_bss: 0x10
+  __DATA.__objc_ivar: 0x25d0
   __DATA.__data: 0x48c0
-  __DATA.__bss: 0xf30
+  __DATA.__bss: 0xf98
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x1108
   __DATA_DIRTY.__data: 0x20

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12026
-  Symbols:   26261
-  CStrings:  8386
+  Functions: 12116
+  Symbols:   26450
+  CStrings:  8467
 
Symbols:
+ +[AFFeatureFlags(SWEFeatureFlags) emergencyOrchestrationModeEnabled]
+ +[AFFeatureFlags(SWEFeatureFlags) isDeviceSelectionShadowModeEnabled]
+ +[AFFeatureFlags(SWEFeatureFlags) isHomePodASRStartOnActivationEnabled]
+ +[AFFeatureFlags(SWEFeatureFlags) linwoodEnabledForCandidateHomePods]
+ +[AFFeatureFlags(SWEFeatureFlags) linwoodEnabledForHomePod2ndGen]
+ +[AFFeatureFlags(SWEFeatureFlags) visualStandbyEnabled]
+ -[AFClientConfiguration carOwnsCommunication]
+ -[AFClientConfiguration initWithAccessibilityState:deviceRingerSwitchState:isDeviceInCarDNDMode:isDeviceInStarkMode:supportsCarPlayVehicleData:isDeviceWatchAuthenticated:areAnnouncementRequestsPermittedByPresentationWhileActive:outputVolume:tapToSiriAudioPlaybackRequest:twoShotAudioPlaybackRequest:deviceSetupFlowBeginDate:deviceSetupFlowEndDate:carOwnsMainAudio:isEyesFreeDevice:carOwnsCommunication:]
+ -[AFConnection _exchangeInputAudioPowerUpdater:]
+ -[AFConnection _inputAudioPowerUpdaterForPolling]
+ -[AFConnection _rejectsCallDuringDealloc:]
+ -[AFConnection _removeSharedObserverListeners]
+ -[AFConnection setCarOwnsCommunication:]
+ -[AFDeviceContextConnection _endUpdateLocalDeviceContextForGeneration:]
+ -[AFDictationConnection _exchangeInputAudioPowerUpdater:]
+ -[AFDictationConnection _inputAudioPowerUpdaterForPolling]
+ -[AFPluginManager _factoryInstanceForPlugin:]
+ -[AFPluginManager _loadBundlesIntoDomainKeyDictionary:]
+ -[AFPluginManager _publishDomainKeyDictionary:]
+ -[AFPluginManager _registerBundle:inDomainKeyDictionary:]
+ -[AFPreferences _AFPublicPreferencesSetValue:forKey:]
+ -[AFPreferences _AFPublicPreferencesValueForKey:]
+ -[AFPreferences getMessageWithoutConfirmationHomeEnabled]
+ -[AFPreferences setMessageWithoutConfirmationHomeEnabled:]
+ -[AFSpeakableUtteranceParser _currentDateForFunctions]
+ -[AFSpeakableUtteranceParser _setCurrentDateForTesting:]
+ -[AFSystemAssistantExperienceStatusManager availabilityProviderForTesting]
+ -[AFSystemAssistantExperienceStatusManager setAvailabilityProviderForTesting:]
+ -[AFWatchdogTimer _cancelLocked]
+ -[AFWatchdogTimer _startLocked]
+ -[AFWatchdogTimer _stopLocked]
+ -[AFWatchdogTimer _timeRemainingLocked]
+ -[_AFClientConfigurationMutation getCarOwnsCommunication]
+ -[_AFClientConfigurationMutation setCarOwnsCommunication:]
+ GCC_except_table1016
+ GCC_except_table10192
+ GCC_except_table10197
+ GCC_except_table10198
+ GCC_except_table10202
+ GCC_except_table10392
+ GCC_except_table10565
+ GCC_except_table10593
+ GCC_except_table10690
+ GCC_except_table10694
+ GCC_except_table10698
+ GCC_except_table10727
+ GCC_except_table11078
+ GCC_except_table11080
+ GCC_except_table11083
+ GCC_except_table11096
+ GCC_except_table11166
+ GCC_except_table11181
+ GCC_except_table11206
+ GCC_except_table11212
+ GCC_except_table11371
+ GCC_except_table11375
+ GCC_except_table11377
+ GCC_except_table11380
+ GCC_except_table11386
+ GCC_except_table11393
+ GCC_except_table1152
+ GCC_except_table11600
+ GCC_except_table11924
+ GCC_except_table12065
+ GCC_except_table12068
+ GCC_except_table12070
+ GCC_except_table1229
+ GCC_except_table1350
+ GCC_except_table1353
+ GCC_except_table1537
+ GCC_except_table1574
+ GCC_except_table1582
+ GCC_except_table1588
+ GCC_except_table1608
+ GCC_except_table1614
+ GCC_except_table1617
+ GCC_except_table1984
+ GCC_except_table2098
+ GCC_except_table2232
+ GCC_except_table2367
+ GCC_except_table2368
+ GCC_except_table2382
+ GCC_except_table2390
+ GCC_except_table2391
+ GCC_except_table2394
+ GCC_except_table2400
+ GCC_except_table2447
+ GCC_except_table2449
+ GCC_except_table2451
+ GCC_except_table2469
+ GCC_except_table2475
+ GCC_except_table2518
+ GCC_except_table2530
+ GCC_except_table2675
+ GCC_except_table274
+ GCC_except_table2767
+ GCC_except_table2821
+ GCC_except_table3048
+ GCC_except_table3049
+ GCC_except_table3246
+ GCC_except_table3307
+ GCC_except_table3524
+ GCC_except_table3527
+ GCC_except_table3532
+ GCC_except_table3550
+ GCC_except_table3597
+ GCC_except_table3603
+ GCC_except_table3609
+ GCC_except_table3702
+ GCC_except_table3706
+ GCC_except_table3816
+ GCC_except_table384
+ GCC_except_table3879
+ GCC_except_table3881
+ GCC_except_table3883
+ GCC_except_table3885
+ GCC_except_table3899
+ GCC_except_table3905
+ GCC_except_table403
+ GCC_except_table4030
+ GCC_except_table4034
+ GCC_except_table4039
+ GCC_except_table410
+ GCC_except_table4411
+ GCC_except_table4426
+ GCC_except_table4433
+ GCC_except_table4449
+ GCC_except_table4521
+ GCC_except_table4550
+ GCC_except_table4588
+ GCC_except_table4589
+ GCC_except_table4590
+ GCC_except_table4615
+ GCC_except_table4639
+ GCC_except_table4999
+ GCC_except_table5004
+ GCC_except_table5007
+ GCC_except_table5010
+ GCC_except_table5013
+ GCC_except_table5016
+ GCC_except_table5019
+ GCC_except_table5022
+ GCC_except_table5025
+ GCC_except_table5028
+ GCC_except_table5058
+ GCC_except_table5204
+ GCC_except_table5207
+ GCC_except_table5280
+ GCC_except_table5624
+ GCC_except_table5637
+ GCC_except_table5641
+ GCC_except_table5653
+ GCC_except_table5657
+ GCC_except_table5770
+ GCC_except_table5772
+ GCC_except_table5828
+ GCC_except_table5872
+ GCC_except_table618
+ GCC_except_table6220
+ GCC_except_table6227
+ GCC_except_table6233
+ GCC_except_table6235
+ GCC_except_table6237
+ GCC_except_table6279
+ GCC_except_table6281
+ GCC_except_table6287
+ GCC_except_table6292
+ GCC_except_table6296
+ GCC_except_table6302
+ GCC_except_table6309
+ GCC_except_table6311
+ GCC_except_table6316
+ GCC_except_table6318
+ GCC_except_table6323
+ GCC_except_table6335
+ GCC_except_table6338
+ GCC_except_table6352
+ GCC_except_table6354
+ GCC_except_table6356
+ GCC_except_table6358
+ GCC_except_table6360
+ GCC_except_table6362
+ GCC_except_table6409
+ GCC_except_table6435
+ GCC_except_table6492
+ GCC_except_table6548
+ GCC_except_table672
+ GCC_except_table6931
+ GCC_except_table7079
+ GCC_except_table7223
+ GCC_except_table7461
+ GCC_except_table7470
+ GCC_except_table7488
+ GCC_except_table7855
+ GCC_except_table7859
+ GCC_except_table7904
+ GCC_except_table7910
+ GCC_except_table7937
+ GCC_except_table7944
+ GCC_except_table8163
+ GCC_except_table8237
+ GCC_except_table8248
+ GCC_except_table8281
+ GCC_except_table8284
+ GCC_except_table8361
+ GCC_except_table8365
+ GCC_except_table8375
+ GCC_except_table8386
+ GCC_except_table8401
+ GCC_except_table8486
+ GCC_except_table8488
+ GCC_except_table8512
+ GCC_except_table8635
+ GCC_except_table8698
+ GCC_except_table8701
+ GCC_except_table8705
+ GCC_except_table8724
+ GCC_except_table8738
+ GCC_except_table878
+ GCC_except_table8814
+ GCC_except_table885
+ GCC_except_table8872
+ GCC_except_table8898
+ GCC_except_table8925
+ GCC_except_table9169
+ GCC_except_table9298
+ GCC_except_table9349
+ GCC_except_table9445
+ GCC_except_table9549
+ GCC_except_table9651
+ GCC_except_table9842
+ GCC_except_table9847
+ GCC_except_table9975
+ _AFDeviceSelectionExcludedHomePod
+ _AFDeviceSelectionParticipating
+ _AFDictionarySchemaFailingKeyPath
+ _AFIsAppleDictationClientSigningIdentity
+ _AFIsHomeAccessory
+ _AFIsSupportedHomePodForLinwood
+ _AFMyriadElectionActivationKindForSpeechEvent
+ _AFObjectsAreEqual
+ _AFPluginManagerLoadsOnCurrentThread
+ _AFPluginManagerLoadsOnCurrentThread$tlv$init
+ _AFPreferencesDeviceOwnerTwentyFourHourTimeDisplay
+ _AFPreferencesSetDeviceOwnerTwentyFourHourTimeDisplay
+ _AFPublicPreferencesSynchronize
+ _AFRemotePeerCommandDispositionForAceCommand
+ _AFRemotePeerCommandDispositionForResolvedAceCommand
+ _AFRemotePeerCommandDispositionGetName
+ _AFSetPendingDictationContinuationDrainedHandlerForTesting
+ _AFSetSiriTaskDeliveryTimeoutForTesting
+ _AFSiriTaskmasterQueueKey
+ _AFSpeakableUtteranceParserNestingDepth
+ _AFSpeakableUtteranceParserNestingDepth$tlv$init
+ _AFSpeechRecognitionArrayHash
+ _AFSpeechRecognitionArrayOfClass
+ _AFSpeechTokenArrayOfClass
+ _AFUserUtteranceInterpretationIndices
+ _AFVisualIntelligenceCameraRestricted.once
+ _OBJC_IVAR_$_AFAudioPowerUpdater._providerLock
+ _OBJC_IVAR_$_AFClientConfiguration._carOwnsCommunication
+ _OBJC_IVAR_$_AFConnection._deallocInProgress
+ _OBJC_IVAR_$_AFConnection._inputAudioPowerUpdaterLock
+ _OBJC_IVAR_$_AFDeviceContextConnection._localDeviceContextUpdateGeneration
+ _OBJC_IVAR_$_AFDictationConnection._didLogUnreadableOfflineDictationStatus
+ _OBJC_IVAR_$_AFDictationConnection._inputAudioPowerUpdaterLock
+ _OBJC_IVAR_$_AFPluginManager._bundlesLock
+ _OBJC_IVAR_$_AFPluginManager._factoryInstanceLock
+ _OBJC_IVAR_$_AFSiriTaskExecution._taskDeliveryWatchdogTimer
+ _OBJC_IVAR_$_AFSpeakableUtteranceParser._currentDateForTesting
+ _OBJC_IVAR_$_AFSystemAssistantExperienceStatusManager._availabilityProviderForTesting
+ _OBJC_IVAR_$__AFClientConfigurationMutation._carOwnsCommunication
+ _SAABMultiPersonSearchClassIdentifier
+ _SAABPersonSearchClassIdentifier
+ _SAAcknowledgeAlertClassIdentifier
+ _SACalendarDefaultSourceGetClassIdentifier
+ _SACalendarEventSearchClassIdentifier
+ _SACalendarGroupIdentifier
+ _SADeviceControlGroupIdentifier
+ _SADomainObjectCancelClassIdentifier
+ _SADomainObjectCommitClassIdentifier
+ _SADomainObjectCreateClassIdentifier
+ _SADomainObjectDeleteClassIdentifier
+ _SADomainObjectPunchOutClassIdentifier
+ _SADomainObjectRetrieveClassIdentifier
+ _SADomainObjectUpdateClassIdentifier
+ _SAEmailGroupIdentifier
+ _SAEmailSearchClassIdentifier
+ _SAGroupIdentifier
+ _SAHAGroupIdentifier
+ _SAPhoneCallClassIdentifier
+ _SAPhoneGroupIdentifier
+ _SAPhoneSearchClassIdentifier
+ _SAReminderGroupIdentifier
+ _SAReminderListSearchClassIdentifier
+ _SAReminderSearchClassIdentifier
+ _SAReminderSnoozeClassIdentifier
+ _SASettingGroupIdentifier
+ _SASmsGroupIdentifier
+ _SASmsGroupSearchClassIdentifier
+ _SASmsRecipientSearchClassIdentifier
+ _SASmsSearchClassIdentifier
+ _SAStockAddClassIdentifier
+ _SAStockGroupIdentifier
+ _SAStockSearchClassIdentifier
+ _SAUILGroupIdentifier
+ _SAUILParseExpressionsClassIdentifier
+ _SecTaskGetCodeSignStatus
+ __AFAVFAudioFrameworkPath
+ __AFAceDictionaryHasGroupAndClass
+ __AFGetAVAudioSessionClass
+ __AFMigratedPreferencesQueue
+ __AFMigratedPreferencesQueue.onceToken
+ __AFMigratedPreferencesQueue.queue
+ __AFPreferencesGetMessageWithoutConfirmationHomeEnabled
+ __AFPreferencesInvalidateLanguageCaches
+ __AFPreferencesLanguageObserverRegistrationAttemptsForTesting
+ __AFPreferencesLongLivedIdentifierUploadingEnabledWithPreferences
+ __AFPreferencesMigrateToPublicDomainIfNeeded
+ __AFPreferencesSetLanguageBackedUpReaderForTesting
+ __AFPreferencesSetLanguageBackedUpSynchronizerForTesting
+ __AFPreferencesSetLanguageIsInternalInstallOverrideForTesting
+ __AFPreferencesSetMessageWithoutConfirmationHomeEnabled
+ __AFPreferencesSyncMigratedDefaultsToPublicDomain
+ __AFPreferencesSyncMigratedDefaultsToPublicDomainOnQueue
+ __AFPublicPreferencesBoolForKeyWithDefault
+ __AFPublicPreferencesBoolValueForKey
+ __AFPublicPreferencesSetValueForKey
+ __AFPublicPreferencesSetValueForKeyWithContext
+ __AFPublicPreferencesValueForKey
+ __AFPublicPreferencesValueForKeyWithContext
+ __AFRemotePeerAllowedCommands.onceToken
+ __AFRemotePeerAllowedCommands.sAllowedCommands
+ __AFRemotePeerCommandDispositionForResolvedGroupAndClass
+ __AFRemotePeerRefusedGroups.onceToken
+ __AFRemotePeerRefusedGroups.sRefusedGroups
+ __AFSiriAvailabilityValue
+ __AFSoftLinkOptionalClass
+ __OBJC_$_CLASS_METHODS_NSString(AFSecurityDigestibleChunksProvider|AFSiriRequest|AFPreferences|AssistantServices|ShortDescription)
+ __OBJC_$_CLASS_METHODS_NSURL(AFSecurityDigestibleChunksProvider|STSiriMessage|AFBundleResourceSupport|AMOSExtensions)
+ __OBJC_$_INSTANCE_METHODS_AFClockAlarmSnapshot(AFClockAlarmSnapshotMutability|Utility|ShortDescription|ContextSnapshot)
+ __OBJC_$_INSTANCE_METHODS_AFClockTimerSnapshot(AFClockTimerSnapshotMutability|Utility|ShortDescription|ContextSnapshot)
+ __OBJC_$_INSTANCE_METHODS_AFLocationSnapshot(AFLocationSnapshotMutability|Ace|ShortDescription|ContextSnapshot)
+ __OBJC_$_INSTANCE_METHODS_NSString(AFSecurityDigestibleChunksProvider|AFSiriRequest|AFPreferences|AssistantServices|ShortDescription)
+ __OBJC_$_INSTANCE_METHODS_NSURL(AFSecurityDigestibleChunksProvider|STSiriMessage|AFBundleResourceSupport|AMOSExtensions)
+ __OBJC_CLASS_PROTOCOLS_$_AFClockAlarmSnapshot(AFClockAlarmSnapshotMutability|Utility|ShortDescription|ContextSnapshot)
+ __OBJC_CLASS_PROTOCOLS_$_AFClockTimerSnapshot(AFClockTimerSnapshotMutability|Utility|ShortDescription|ContextSnapshot)
+ __OBJC_CLASS_PROTOCOLS_$_AFLocationSnapshot(AFLocationSnapshotMutability|Ace|ShortDescription|ContextSnapshot)
+ __OBJC_CLASS_PROTOCOLS_$_NSURL(AFSecurityDigestibleChunksProvider|STSiriMessage|AFBundleResourceSupport|AMOSExtensions)
+ ___118-[AFDeviceContextConnection donateSerializedContextMapByPrivacyClass:withMetadataMap:forType:pushToRemote:completion:]_block_invoke_2
+ ___40-[AFConnection setCarOwnsCommunication:]_block_invoke
+ ___403-[AFClientConfiguration initWithAccessibilityState:deviceRingerSwitchState:isDeviceInCarDNDMode:isDeviceInStarkMode:supportsCarPlayVehicleData:isDeviceWatchAuthenticated:areAnnouncementRequestsPermittedByPresentationWhileActive:outputVolume:tapToSiriAudioPlaybackRequest:twoShotAudioPlaybackRequest:deviceSetupFlowBeginDate:deviceSetupFlowEndDate:carOwnsMainAudio:isEyesFreeDevice:carOwnsCommunication:]_block_invoke
+ ___41-[AFSiriAvailability initWithDictionary:]_block_invoke
+ ___48-[AFDeviceContextMetadata initWithBackingStore:]_block_invoke
+ ___58-[AFConnection acquireAudioSessionWithContext:completion:]_block_invoke_2
+ ___58-[AFSiriTaskmaster handleSiriTaskUsageResult:fromRequest:]_block_invoke
+ ___AFVisualIntelligenceCameraRestricted_block_invoke
+ ____AFMigratedPreferencesQueue_block_invoke
+ ____AFPreferencesMigrateToPublicDomainIfNeeded_block_invoke
+ ____AFPreferencesSyncMigratedDefaultsToPublicDomain_block_invoke
+ ____AFRemotePeerAllowedCommands_block_invoke
+ ____AFRemotePeerRefusedGroups_block_invoke
+ ____AFSetAudioSessionActiveResultCreateDeallocated_block_invoke
+ ___block_descriptor_32_e18_"NSString"16?08l
+ ___block_descriptor_40_e8_32s_e45_"NSNumber"24?0"NSDictionary"8"NSString"16l
+ ___block_descriptor_48_e8_32w_e17_v16?0"NSError"8l
+ ___block_descriptor_56_e8_32s40r48w_e25_v16?0"AFDeviceContext"8l
+ ___block_descriptor_56_e8_32s40s48r_e25_v32?0"NSNumber"8Q16^B24l
+ ___block_descriptor_92_e8_32s40s48s56s64s_e41_v16?0"<AFClientConfigurationMutating>"8l
+ ___copy_helper_block_e8_32s40r48w
+ __tlv_bootstrap
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
+ _kAFAppleIntelligenceFallbackEnabledKey
+ _kAFDictationSLSEnabledKey
+ _kAFDictationSLSLanguagesEnabledKey
+ _kAFDisplayedLowStorageNotificationStatus
+ _kAFMessageWithoutConfirmationHomeKey
+ _kAFOfflineDictationStatusKey
+ _kAFPublicPreferencesMigratedKey
+ _kAFRemotePeerDeliveredCommandKey
+ _kAFRemotePeerDeliveredCommandValue
+ _kAssistantPublicPreferenceDomain
+ _objc_msgSend$_AFPublicPreferencesSetValue:forKey:
+ _objc_msgSend$_AFPublicPreferencesValueForKey:
+ _objc_msgSend$_cancelLocked
+ _objc_msgSend$_currentDateForFunctions
+ _objc_msgSend$_endUpdateLocalDeviceContextForGeneration:
+ _objc_msgSend$_exchangeInputAudioPowerUpdater:
+ _objc_msgSend$_factoryInstanceForPlugin:
+ _objc_msgSend$_inputAudioPowerUpdaterForPolling
+ _objc_msgSend$_loadBundlesIntoDomainKeyDictionary:
+ _objc_msgSend$_publishDomainKeyDictionary:
+ _objc_msgSend$_registerBundle:inDomainKeyDictionary:
+ _objc_msgSend$_rejectsCallDuringDealloc:
+ _objc_msgSend$_removeSharedObserverListeners
+ _objc_msgSend$_setCurrentDateForTesting:
+ _objc_msgSend$_startLocked
+ _objc_msgSend$_stopLocked
+ _objc_msgSend$_timeRemainingLocked
+ _objc_msgSend$availabilityProviderForTesting
+ _objc_msgSend$carOwnsCommunication
+ _objc_msgSend$getCarOwnsCommunication
+ _objc_msgSend$initWithAccessibilityState:deviceRingerSwitchState:isDeviceInCarDNDMode:isDeviceInStarkMode:supportsCarPlayVehicleData:isDeviceWatchAuthenticated:areAnnouncementRequestsPermittedByPresentationWhileActive:outputVolume:tapToSiriAudioPlaybackRequest:twoShotAudioPlaybackRequest:deviceSetupFlowBeginDate:deviceSetupFlowEndDate:carOwnsMainAudio:isEyesFreeDevice:carOwnsCommunication:
+ _objc_msgSend$isDeviceSelectionShadowModeEnabled
+ _objc_msgSend$linwoodEnabledForCandidateHomePods
+ _objc_msgSend$linwoodEnabledForHomePod2ndGen
+ _objc_msgSend$readSharedUserIdentifier:
+ _objc_msgSend$setCarOwnsCommunication:
+ _objc_setProperty_atomic_copy
+ _sAFPendingDictationContinuationDrainedHandler
+ _sLanguageBackedUpReaderForTesting
+ _sLanguageBackedUpSynchronizerForTesting
+ _sLanguageIsInternalInstallOverrideForTesting
+ _sLanguageObserverRegistrationAttemptsForTesting
+ _s_deliveryTimeoutOverride
- -[AFClientConfiguration initWithAccessibilityState:deviceRingerSwitchState:isDeviceInCarDNDMode:isDeviceInStarkMode:supportsCarPlayVehicleData:isDeviceWatchAuthenticated:areAnnouncementRequestsPermittedByPresentationWhileActive:outputVolume:tapToSiriAudioPlaybackRequest:twoShotAudioPlaybackRequest:deviceSetupFlowBeginDate:deviceSetupFlowEndDate:carOwnsMainAudio:isEyesFreeDevice:]
- -[AFPluginManager _registerBundle:]
- GCC_except_table1006
- GCC_except_table10112
- GCC_except_table10117
- GCC_except_table10118
- GCC_except_table10122
- GCC_except_table10312
- GCC_except_table10485
- GCC_except_table10513
- GCC_except_table10610
- GCC_except_table10614
- GCC_except_table10618
- GCC_except_table10647
- GCC_except_table10995
- GCC_except_table10997
- GCC_except_table11000
- GCC_except_table11009
- GCC_except_table11075
- GCC_except_table11090
- GCC_except_table11115
- GCC_except_table11121
- GCC_except_table11280
- GCC_except_table11284
- GCC_except_table11286
- GCC_except_table11289
- GCC_except_table11295
- GCC_except_table11302
- GCC_except_table1142
- GCC_except_table11509
- GCC_except_table11833
- GCC_except_table11974
- GCC_except_table11977
- GCC_except_table11979
- GCC_except_table1209
- GCC_except_table1340
- GCC_except_table1342
- GCC_except_table1525
- GCC_except_table1562
- GCC_except_table1570
- GCC_except_table1576
- GCC_except_table1596
- GCC_except_table1602
- GCC_except_table1605
- GCC_except_table1972
- GCC_except_table2086
- GCC_except_table2219
- GCC_except_table2341
- GCC_except_table2355
- GCC_except_table2369
- GCC_except_table2377
- GCC_except_table2378
- GCC_except_table2381
- GCC_except_table2387
- GCC_except_table2434
- GCC_except_table2436
- GCC_except_table2438
- GCC_except_table2456
- GCC_except_table2462
- GCC_except_table2505
- GCC_except_table2517
- GCC_except_table273
- GCC_except_table2756
- GCC_except_table2769
- GCC_except_table2773
- GCC_except_table2785
- GCC_except_table2789
- GCC_except_table2902
- GCC_except_table2904
- GCC_except_table2961
- GCC_except_table3005
- GCC_except_table3352
- GCC_except_table3359
- GCC_except_table3365
- GCC_except_table3367
- GCC_except_table3369
- GCC_except_table3404
- GCC_except_table3406
- GCC_except_table3412
- GCC_except_table3418
- GCC_except_table3422
- GCC_except_table3428
- GCC_except_table3435
- GCC_except_table3437
- GCC_except_table3444
- GCC_except_table3446
- GCC_except_table3451
- GCC_except_table3463
- GCC_except_table3466
- GCC_except_table3480
- GCC_except_table3482
- GCC_except_table3484
- GCC_except_table3486
- GCC_except_table3488
- GCC_except_table3490
- GCC_except_table3562
- GCC_except_table3619
- GCC_except_table3655
- GCC_except_table377
- GCC_except_table396
- GCC_except_table402
- GCC_except_table4038
- GCC_except_table4326
- GCC_except_table4529
- GCC_except_table4537
- GCC_except_table4595
- GCC_except_table4963
- GCC_except_table4967
- GCC_except_table5012
- GCC_except_table5018
- GCC_except_table5045
- GCC_except_table5052
- GCC_except_table5264
- GCC_except_table5338
- GCC_except_table5349
- GCC_except_table5382
- GCC_except_table5385
- GCC_except_table5462
- GCC_except_table5466
- GCC_except_table5476
- GCC_except_table5487
- GCC_except_table5502
- GCC_except_table5587
- GCC_except_table5589
- GCC_except_table5613
- GCC_except_table5729
- GCC_except_table5792
- GCC_except_table5795
- GCC_except_table5799
- GCC_except_table5818
- GCC_except_table5833
- GCC_except_table5907
- GCC_except_table5965
- GCC_except_table5991
- GCC_except_table608
- GCC_except_table6259
- GCC_except_table6388
- GCC_except_table6438
- GCC_except_table6532
- GCC_except_table662
- GCC_except_table6717
- GCC_except_table6805
- GCC_except_table6859
- GCC_except_table7085
- GCC_except_table7086
- GCC_except_table7283
- GCC_except_table7343
- GCC_except_table7557
- GCC_except_table7560
- GCC_except_table7565
- GCC_except_table7569
- GCC_except_table7583
- GCC_except_table7630
- GCC_except_table7636
- GCC_except_table7642
- GCC_except_table7735
- GCC_except_table7739
- GCC_except_table7849
- GCC_except_table7912
- GCC_except_table7914
- GCC_except_table7916
- GCC_except_table7918
- GCC_except_table7932
- GCC_except_table7938
- GCC_except_table8063
- GCC_except_table8067
- GCC_except_table8072
- GCC_except_table8444
- GCC_except_table8459
- GCC_except_table8466
- GCC_except_table8482
- GCC_except_table8553
- GCC_except_table8582
- GCC_except_table8620
- GCC_except_table8621
- GCC_except_table8622
- GCC_except_table8647
- GCC_except_table865
- GCC_except_table8671
- GCC_except_table868
- GCC_except_table9031
- GCC_except_table9036
- GCC_except_table9039
- GCC_except_table9042
- GCC_except_table9045
- GCC_except_table9048
- GCC_except_table9051
- GCC_except_table9054
- GCC_except_table9057
- GCC_except_table9060
- GCC_except_table9233
- GCC_except_table9236
- GCC_except_table9309
- GCC_except_table9469
- GCC_except_table9571
- GCC_except_table9762
- GCC_except_table9767
- GCC_except_table9895
- __OBJC_$_CLASS_METHODS_NSString(AFSecurityDigestibleChunksProvider|AFPreferences|AssistantServices|AFSiriRequest|ShortDescription)
- __OBJC_$_CLASS_METHODS_NSURL(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport|AMOSExtensions|STSiriMessage)
- __OBJC_$_INSTANCE_METHODS_AFClockAlarmSnapshot(Utility|AFClockAlarmSnapshotMutability|ShortDescription|ContextSnapshot)
- __OBJC_$_INSTANCE_METHODS_AFClockTimerSnapshot(Utility|AFClockTimerSnapshotMutability|ShortDescription|ContextSnapshot)
- __OBJC_$_INSTANCE_METHODS_AFLocationSnapshot(Ace|AFLocationSnapshotMutability|ShortDescription|ContextSnapshot)
- __OBJC_$_INSTANCE_METHODS_NSString(AFSecurityDigestibleChunksProvider|AFPreferences|AssistantServices|AFSiriRequest|ShortDescription)
- __OBJC_$_INSTANCE_METHODS_NSURL(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport|AMOSExtensions|STSiriMessage)
- __OBJC_CLASS_PROTOCOLS_$_AFClockAlarmSnapshot(Utility|AFClockAlarmSnapshotMutability|ShortDescription|ContextSnapshot)
- __OBJC_CLASS_PROTOCOLS_$_AFClockTimerSnapshot(Utility|AFClockTimerSnapshotMutability|ShortDescription|ContextSnapshot)
- __OBJC_CLASS_PROTOCOLS_$_AFLocationSnapshot(Ace|AFLocationSnapshotMutability|ShortDescription|ContextSnapshot)
- __OBJC_CLASS_PROTOCOLS_$_NSURL(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport|AMOSExtensions|STSiriMessage)
- ___28-[AFSiriTaskExecution start]_block_invoke_3
- ___382-[AFClientConfiguration initWithAccessibilityState:deviceRingerSwitchState:isDeviceInCarDNDMode:isDeviceInStarkMode:supportsCarPlayVehicleData:isDeviceWatchAuthenticated:areAnnouncementRequestsPermittedByPresentationWhileActive:outputVolume:tapToSiriAudioPlaybackRequest:twoShotAudioPlaybackRequest:deviceSetupFlowBeginDate:deviceSetupFlowEndDate:carOwnsMainAudio:isEyesFreeDevice:]_block_invoke
- ___82-[AFDictationConnection forcedOfflineDictationIsAvailableForLanguage:synchronous:]_block_invoke_2
- ___83+[SASSpeechPartialResult(AFSpeechTokenAdditions) createUsingPhrases:andUtterances:]_block_invoke
- ___block_descriptor_48_e8_32bs40w_e25_v16?0"AFDeviceContext"8l
- ___block_descriptor_48_e8_32r40r_e15_v32?08Q16^B24l
- ___block_descriptor_48_e8_32s40s_e25_v32?0"NSNumber"8Q16^B24l
- ___block_descriptor_91_e8_32s40s48s56s64s_e41_v16?0"<AFClientConfigurationMutating>"8l
- _objc_msgSend$_AFSupportPreferencesValueForKey:
- _objc_msgSend$_registerBundle:
- _objc_msgSend$fetchSharedUserIdentifier:
- _objc_msgSend$forceAsrOnServerForUOD
- _objc_msgSend$initWithAccessibilityState:deviceRingerSwitchState:isDeviceInCarDNDMode:isDeviceInStarkMode:supportsCarPlayVehicleData:isDeviceWatchAuthenticated:areAnnouncementRequestsPermittedByPresentationWhileActive:outputVolume:tapToSiriAudioPlaybackRequest:twoShotAudioPlaybackRequest:deviceSetupFlowBeginDate:deviceSetupFlowEndDate:carOwnsMainAudio:isEyesFreeDevice:
- _objc_msgSend$isAsrOnServerForUODEnabled
- _objc_msgSend$isNLRouterEnabled
- _objc_msgSend$isSiriHybridUODEnabledForMacOS
- _objc_msgSend$isSiriUODEnabledForMacOS
- _objc_msgSend$isSiriUODForceEnabledForDevice
CStrings:
+ "$class"
+ "$group"
+ "%@ (%@)"
+ "%@ {accessibilityState = %@, deviceRingerSwitchState = %@, isDeviceInCarDNDMode = %@, isDeviceInStarkMode = %@, supportsCarPlayVehicleData = %@, isDeviceWatchAuthenticated = %@, areAnnouncementRequestsPermittedByPresentationWhileActive = %@, outputVolume = %f, tapToSiriAudioPlaybackRequest = %@, twoShotAudioPlaybackRequest = %@, deviceSetupFlowBeginDate = %@, deviceSetupFlowEndDate = %@, carOwnsMainAudio = %@, isEyesFreeDevice = %@, carOwnsCommunication = %@}"
+ "%s #SiriAvailability ignored %lu wrong-typed value(s): %{public}@"
+ "%s %p Ignored because generation %lu is not the current one (%lu)."
+ "%s %p No offline dictation status; reporting unavailable, will retry"
+ "%s %p generation = %lu"
+ "%s %p ignoring %{public}@ during dealloc"
+ "%s %p not creating a connection during dealloc"
+ "%s %{public}lu of %{public}lu server utterances have interpretation indices that do not fit the %{public}lu phrases; they are left out"
+ "%s %{public}s has no class %{public}s"
+ "%s +provider called on %@ but the shared instance is a %@"
+ "%s Called back while loading bundles from \"%@\"; no bundles are available yet"
+ "%s Could not load %{public}s for %{public}s: %{public}s"
+ "%s Delivery of %@ timed out after %{public}.2f seconds"
+ "%s Dropping punchout outcome: result=%@ has description %@, request=%@ has name %@"
+ "%s Ignoring an utterance that is not an AFSpeechUtterance"
+ "%s Ignoring phrases that are not an array of AFSpeechPhrase"
+ "%s Ignoring utterance interpretationIndices that are not an array"
+ "%s Ignoring utterance interpretationIndices with a non-number index"
+ "%s Ignoring utterance whose interpretation index %{public}lu at phrase %{public}lu is past its %{public}lu interpretations"
+ "%s Ignoring utterance whose interpretation indices are not an array"
+ "%s Ignoring utterance whose phrase %{public}lu has interpretations that are not an array of AFSpeechInterpretation"
+ "%s Ignoring utterance whose selected interpretation at phrase %{public}lu has tokens that are not an array of AFSpeechToken"
+ "%s Ignoring utterance with %{public}lu interpretation indices for %{public}lu phrases"
+ "%s Ignoring utterance with a non-number interpretation index"
+ "%s Ignoring utterances that are not an array of AFSpeechUtterance"
+ "%s No delegate on %@; punchout outcome %@ is being discarded"
+ "%s No plugin bundles at path \"%@\":%@"
+ "%s No readable AFSiriAvailability in this process; the Device Configuration Visual Intelligence restriction is not applied here. Enforcing it requires read access to com.apple.assistant.backedup."
+ "%s Not treating %{public}@ as an Apple client: code sign status 0x%x is not a valid platform binary, or the identifier does not start with com.apple."
+ "%s Pending dictation request was refused; there is nothing to continue"
+ "%s Siri plugin %@ has a non-array %@ entry, ignoring it"
+ "%s Siri plugin %@ has a non-string %@ identifier, ignoring it"
+ "%s passed invalid property list (%{public}@ %ld at %{public}@, %{public}@ with %lu keys): %{private}@"
+ "%s returning nil; passed invalid property list (%{public}@ %ld at %{public}@, %{public}@ with %lu keys): %{private}@"
+ "%s returning nil; unable to create associated data store from property list"
+ "%s utterance has %{public}lu interpretationIndices for %{public}lu phrases"
+ "%s utterance interpretationIndex (%{public}lu) is out of range of %{public}lu interpretations"
+ "%s visualIntelligenceRestricted = %d (no readable AFSiriAvailability, local policy only)"
+ "(dictionary) (%@)"
+ "(elided: not on the taskmaster queue)"
+ "(none)"
+ "+[AFCarPlayAnnouncementRequestCapabilityProvider provider]"
+ "+[AFHeadphonesAnnouncementRequestCapabilityProvider provider]"
+ "+[AFSpeechRecognition tokenListFromUtterance:phrases:]"
+ "-[AFConnection _connection]"
+ "-[AFConnection _rejectsCallDuringDealloc:]"
+ "-[AFConnection acquireAudioSessionWithContext:completion:]_block_invoke_2"
+ "-[AFConnection startRecordingAndGetContinueBlockForPendingSpeechRequestWithOptions:]_block_invoke_3"
+ "-[AFDeviceContextConnection _endUpdateLocalDeviceContextForGeneration:]"
+ "-[AFDictationConnection forcedOfflineDictationIsAvailableForLanguage:synchronous:]"
+ "-[AFPluginManager _loadBundlesIntoDomainKeyDictionary:]"
+ "-[AFPluginManager _registerBundle:inDomainKeyDictionary:]"
+ "-[AFSiriAvailability initWithDictionary:]"
+ "-[AFSiriTaskExecution start]_block_invoke_2"
+ "-[AFSiriTaskmaster handleSiriTaskUsageResult:fromRequest:]_block_invoke"
+ "-[AFSpeechRecognition nBestTokenListsFromSausage]"
+ "-[AFSpeechRecognition oneBestTokenList]"
+ "-[AFUserUtterance interpretationOfUtteranceAtIndex:]_block_invoke"
+ "-[SASRecognition(AFSpeechTokenAdditions) af_speechUtterances]"
+ "/System/Library/Frameworks/AVFAudio.framework/AVFAudio"
+ "@\"NSNumber\"24@?0@\"NSDictionary\"8@\"NSString\"16"
+ "@\"NSString\"16@?0@8"
+ "AFClientConfiguration::carOwnsCommunication"
+ "AFDictionarySchemaFailingKeyPath"
+ "AFRemotePeerDeliveredCommand"
+ "AFUserUtteranceInterpretationIndices"
+ "AFVisualIntelligenceCameraRestricted_block_invoke"
+ "AVAudioSession"
+ "Device Owner Twenty Four Hour Time Display"
+ "Emergency"
+ "Message Without Confirmation Home"
+ "Public Preferences Migrated"
+ "Standby"
+ "_AFPreferencesSetMessageWithoutConfirmationHomeEnabled"
+ "_AFPublicPreferencesBoolValueForKey"
+ "_AFSoftLinkOptionalClass"
+ "allow"
+ "allow (logged)"
+ "carOwnsCommunication"
+ "com.apple."
+ "com.apple.assistant.preferences.public-domain-migration"
+ "com.apple.assistant.public"
+ "device_selection_shadow"
+ "emergency_orchestration_mode"
+ "homepod_asr_start_on_activation"
+ "linwood_enabled_for_candidate_homepods"
+ "linwood_enabled_for_homepod_2ndgen"
+ "refuse"
+ "\xf0\xf0\xf02"
- "%@ {accessibilityState = %@, deviceRingerSwitchState = %@, isDeviceInCarDNDMode = %@, isDeviceInStarkMode = %@, supportsCarPlayVehicleData = %@, isDeviceWatchAuthenticated = %@, areAnnouncementRequestsPermittedByPresentationWhileActive = %@, outputVolume = %f, tapToSiriAudioPlaybackRequest = %@, twoShotAudioPlaybackRequest = %@, deviceSetupFlowBeginDate = %@, deviceSetupFlowEndDate = %@, carOwnsMainAudio = %@, isEyesFreeDevice = %@}"
- "%s passed invalid property list (%@): %{public}@"
- "%s returning nil; passed invalid property list (%@): %{public}@"
- "%s returning nil; passed invalid property list (%{public}@): %@"
- "%s returning nil; unable co create associated data store from property list %@"
- "%s visualIntelligenceRestricted = 1 (no persisted AFSiriAvailability)"
- "-[AFConnection acquireAudioSessionWithContext:completion:]_block_invoke"
- "-[AFConnection startRecordingAndGetContinueBlockForPendingSpeechRequestWithOptions:]_block_invoke_2"
- "-[AFPluginManager _registerBundle:]"
- "-[AFSiriTaskExecution start]_block_invoke_3"
- "\xf0\xf0\xf0\""
```
