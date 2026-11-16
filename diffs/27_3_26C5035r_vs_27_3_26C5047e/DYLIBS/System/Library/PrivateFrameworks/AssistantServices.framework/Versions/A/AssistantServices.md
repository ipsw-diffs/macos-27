## AssistantServices

> `/System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/AssistantServices`

```diff

-3610.11.2.4.1
-  __TEXT.__text: 0x1a4d24
-  __TEXT.__objc_methlist: 0x1f29c
+3610.19.2.4.1
+  __TEXT.__text: 0x1a5cac
+  __TEXT.__objc_methlist: 0x1f33c
   __TEXT.__const: 0x400
   __TEXT.__dlopen_cstrs: 0x421
-  __TEXT.__gcc_except_tab: 0x20c8
-  __TEXT.__cstring: 0x3c112
-  __TEXT.__oslogstring: 0xf97e
+  __TEXT.__gcc_except_tab: 0x2118
+  __TEXT.__cstring: 0x3c3a9
+  __TEXT.__oslogstring: 0xfab6
   __TEXT.__ustring: 0x2ac
-  __TEXT.__unwind_info: 0x9a58
+  __TEXT.__unwind_info: 0x9ac0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4388
+  __DATA_CONST.__const: 0x4390
   __DATA_CONST.__objc_classlist: 0xef8
   __DATA_CONST.__objc_catlist: 0x2a0
   __DATA_CONST.__objc_protolist: 0x5f8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xbf10
+  __DATA_CONST.__objc_selrefs: 0xbf88
   __DATA_CONST.__objc_protorefs: 0x180
   __DATA_CONST.__objc_superrefs: 0xf10
-  __DATA_CONST.__objc_arraydata: 0x2450
-  __DATA_CONST.__got: 0x1780
-  __AUTH_CONST.__const: 0x84a0
-  __AUTH_CONST.__cfstring: 0x28240
-  __AUTH_CONST.__objc_const: 0x36740
+  __DATA_CONST.__objc_arraydata: 0x2300
+  __DATA_CONST.__got: 0x1798
+  __AUTH_CONST.__const: 0x8500
+  __AUTH_CONST.__cfstring: 0x28340
+  __AUTH_CONST.__objc_const: 0x367a0
   __AUTH_CONST.__objc_intobj: 0x2730
   __AUTH_CONST.__objc_dictobj: 0xd20
-  __AUTH_CONST.__objc_arrayobj: 0x5d0
+  __AUTH_CONST.__objc_arrayobj: 0x5a0
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__auth_got: 0x9b0
   __AUTH.__objc_data: 0x84a8
   __AUTH.__data: 0xd0
   __AUTH.__thread_vars: 0x30
   __AUTH.__thread_bss: 0x10
-  __DATA.__objc_ivar: 0x25d0
+  __DATA.__objc_ivar: 0x25d8
   __DATA.__data: 0x48c0
-  __DATA.__bss: 0xf98
+  __DATA.__bss: 0xfa8
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x1108
   __DATA_DIRTY.__data: 0x20
-  __DATA_DIRTY.__bss: 0x1b8
+  __DATA_DIRTY.__bss: 0x198
   __DATA_DIRTY.__common: 0xf8
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics
   - /System/Library/PrivateFrameworks/FaceTimeNameUtility.framework/Versions/A/FaceTimeNameUtility
   - /System/Library/PrivateFrameworks/FeedbackLogger.framework/Versions/A/FeedbackLogger
+  - /System/Library/PrivateFrameworks/GenerativeModels.framework/Versions/A/GenerativeModels
   - /System/Library/PrivateFrameworks/MediaRemote.framework/Versions/A/MediaRemote
   - /System/Library/PrivateFrameworks/ProactiveSupport.framework/Versions/A/ProactiveSupport
   - /System/Library/PrivateFrameworks/ProtocolBuffer.framework/Versions/A/ProtocolBuffer
   - /System/Library/PrivateFrameworks/SAObjects.framework/Versions/A/SAObjects
   - /System/Library/PrivateFrameworks/SiriAnalytics.framework/Versions/A/SiriAnalytics
+  - /System/Library/PrivateFrameworks/SiriAvailability.framework/Versions/A/SiriAvailability
   - /System/Library/PrivateFrameworks/SiriCrossDeviceArbitration.framework/Versions/A/SiriCrossDeviceArbitration
   - /System/Library/PrivateFrameworks/SiriCrossDeviceArbitrationFeedback.framework/Versions/A/SiriCrossDeviceArbitrationFeedback
   - /System/Library/PrivateFrameworks/SiriInstrumentation.framework/Versions/A/SiriInstrumentation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12116
-  Symbols:   26450
-  CStrings:  8467
+  Functions: 12142
+  Symbols:   26489
+  CStrings:  8488
 
Symbols:
+ +[AFFeatureFlags(SWEFeatureFlags) isHomePodPauseMusicOnRequestEnabled]
+ +[AFFeatureFlags(SWEFeatureFlags) isPebbleFutureLocaleWavesEnabled]
+ +[AFFeatureFlags(SWEFeatureFlags) isPebbleRecognitionWithVoiceProfileEnabled]
+ +[AFFeatureFlags(SWEFeatureFlags) isPebbleVoiceIdMUDownloadEnabled]
+ -[AFDictationConnection _homeAccessoryDictationIsAvailableForLanguage:offlineDictationStatus:]
+ -[AFPreferences(Accessibility) removeAppleIntelligenceFallback]
+ -[AFSettingsConnection fetchCompanionSiriAvailabilityForSetup:completion:]
+ -[AFSiriAvailability isLinwoodCapableIgnoringUserSettingWithCompanionSiriAvailability:]
+ -[AFSpeechConnectionRequestContext initWithRequestId:inputOrigin:]
+ -[AFSpeechConnectionRequestContext inputOrigin]
+ -[_AFSpeechConnectionRequestContextMutation getInputOrigin]
+ -[_AFSpeechConnectionRequestContextMutation setInputOrigin:]
+ GCC_except_table10002
+ GCC_except_table10219
+ GCC_except_table10224
+ GCC_except_table10225
+ GCC_except_table10229
+ GCC_except_table10419
+ GCC_except_table10590
+ GCC_except_table10618
+ GCC_except_table10715
+ GCC_except_table10719
+ GCC_except_table10723
+ GCC_except_table10752
+ GCC_except_table11103
+ GCC_except_table11105
+ GCC_except_table11108
+ GCC_except_table11121
+ GCC_except_table11192
+ GCC_except_table11207
+ GCC_except_table11232
+ GCC_except_table11238
+ GCC_except_table11397
+ GCC_except_table11401
+ GCC_except_table11403
+ GCC_except_table11406
+ GCC_except_table11412
+ GCC_except_table11419
+ GCC_except_table11626
+ GCC_except_table11950
+ GCC_except_table12091
+ GCC_except_table12094
+ GCC_except_table12096
+ GCC_except_table2233
+ GCC_except_table2355
+ GCC_except_table2369
+ GCC_except_table2383
+ GCC_except_table2392
+ GCC_except_table2395
+ GCC_except_table2401
+ GCC_except_table2448
+ GCC_except_table2450
+ GCC_except_table2452
+ GCC_except_table2470
+ GCC_except_table2476
+ GCC_except_table2519
+ GCC_except_table2531
+ GCC_except_table2676
+ GCC_except_table2769
+ GCC_except_table2823
+ GCC_except_table3050
+ GCC_except_table3051
+ GCC_except_table3251
+ GCC_except_table3312
+ GCC_except_table3529
+ GCC_except_table3537
+ GCC_except_table3541
+ GCC_except_table3555
+ GCC_except_table3602
+ GCC_except_table3608
+ GCC_except_table3614
+ GCC_except_table3707
+ GCC_except_table3711
+ GCC_except_table3821
+ GCC_except_table3884
+ GCC_except_table3886
+ GCC_except_table3888
+ GCC_except_table3890
+ GCC_except_table3904
+ GCC_except_table3910
+ GCC_except_table4035
+ GCC_except_table4044
+ GCC_except_table4062
+ GCC_except_table4422
+ GCC_except_table4437
+ GCC_except_table4444
+ GCC_except_table4460
+ GCC_except_table4532
+ GCC_except_table4561
+ GCC_except_table4599
+ GCC_except_table4600
+ GCC_except_table4601
+ GCC_except_table4626
+ GCC_except_table4650
+ GCC_except_table5015
+ GCC_except_table5018
+ GCC_except_table5021
+ GCC_except_table5024
+ GCC_except_table5027
+ GCC_except_table5030
+ GCC_except_table5033
+ GCC_except_table5036
+ GCC_except_table5039
+ GCC_except_table5069
+ GCC_except_table5215
+ GCC_except_table5218
+ GCC_except_table5291
+ GCC_except_table5635
+ GCC_except_table5648
+ GCC_except_table5652
+ GCC_except_table5664
+ GCC_except_table5668
+ GCC_except_table5781
+ GCC_except_table5783
+ GCC_except_table5839
+ GCC_except_table5883
+ GCC_except_table6229
+ GCC_except_table6236
+ GCC_except_table6242
+ GCC_except_table6244
+ GCC_except_table6246
+ GCC_except_table6288
+ GCC_except_table6290
+ GCC_except_table6301
+ GCC_except_table6305
+ GCC_except_table6320
+ GCC_except_table6325
+ GCC_except_table6327
+ GCC_except_table6332
+ GCC_except_table6344
+ GCC_except_table6347
+ GCC_except_table6361
+ GCC_except_table6363
+ GCC_except_table6365
+ GCC_except_table6367
+ GCC_except_table6369
+ GCC_except_table6371
+ GCC_except_table6418
+ GCC_except_table6444
+ GCC_except_table6501
+ GCC_except_table6561
+ GCC_except_table6946
+ GCC_except_table7094
+ GCC_except_table7238
+ GCC_except_table7476
+ GCC_except_table7485
+ GCC_except_table7503
+ GCC_except_table7870
+ GCC_except_table7874
+ GCC_except_table7919
+ GCC_except_table7925
+ GCC_except_table7952
+ GCC_except_table7959
+ GCC_except_table8181
+ GCC_except_table8255
+ GCC_except_table8266
+ GCC_except_table8299
+ GCC_except_table8302
+ GCC_except_table8379
+ GCC_except_table8383
+ GCC_except_table8393
+ GCC_except_table8404
+ GCC_except_table8419
+ GCC_except_table8504
+ GCC_except_table8506
+ GCC_except_table8530
+ GCC_except_table8653
+ GCC_except_table8716
+ GCC_except_table8719
+ GCC_except_table8723
+ GCC_except_table8742
+ GCC_except_table8756
+ GCC_except_table8833
+ GCC_except_table8891
+ GCC_except_table8917
+ GCC_except_table8944
+ GCC_except_table9193
+ GCC_except_table9322
+ GCC_except_table9373
+ GCC_except_table9472
+ GCC_except_table9576
+ GCC_except_table9678
+ GCC_except_table9869
+ GCC_except_table9874
+ _AFAttentionAwarenessSupportsFaceDetect
+ _AFCDAFaceDetectionHelper
+ _AFCleanup2026IncidentMetadata
+ _AFIsAffectedBy2026Incident
+ _AFIsIPad.isiPad
+ _AFIsLinwoodCandidateHomePodWithoutLinwood
+ _AFIsMitigated2026IncidentByThisBuildUpdate
+ _AFIsSiriAvailabilityFrameworkLoaded
+ _AFIsSiriAvailabilityFrameworkLoaded.isLoaded
+ _AFIsSiriAvailabilityFrameworkLoaded.onceToken
+ _AFPreferencesRecognizedSpeakerTwentyFourHourTimeDisplay
+ _AFPreferencesSetRecognizedSpeakerTwentyFourHourTimeDisplay
+ _AFRecognizedSpeakerHasNoTwentyFourHourTimeChoice
+ _AFSUPPrefersTwentyFourHourTime
+ _AFSettingsServiceXPCInterface.__onceToken
+ _AFSettingsServiceXPCInterface.interface
+ _AFUsesRecognizedSpeakerTwentyFourHourTime
+ _OBJC_CLASS_$_GMAvailabilityWrapper
+ _OBJC_CLASS_$_SODeviceDescriptor
+ _OBJC_CLASS_$_SOHomePodDescriptor
+ _OBJC_IVAR_$_AFSpeechConnectionRequestContext._inputOrigin
+ _OBJC_IVAR_$__AFSpeechConnectionRequestContextMutation._inputOrigin
+ __AFPreferencesResolveUseDeviceSpeakerForTTS
+ ___66-[AFSpeechConnectionRequestContext initWithRequestId:inputOrigin:]_block_invoke
+ ___74-[AFSettingsConnection fetchCompanionSiriAvailabilityForSetup:completion:]_block_invoke
+ ___99-[AFSettingsConnection(Internal) _updateMultiUserInfoForUser:score:companionInfo:reset:completion:]_block_invoke_5
+ ___AFIsSiriAvailabilityFrameworkLoaded_block_invoke
+ ___AFSettingsServiceXPCInterface_block_invoke
+ ___block_descriptor_48_e8_32s40s_e52_v16?0"<AFSpeechConnectionRequestContextMutating>"8l
+ ___block_descriptor_56_e8_32s40r48r_e40_v24?0"AFSiriAvailability"8"NSError"16l
+ ___block_descriptor_64_e8_32bs40r48r56r_e8_v16?0q8l
+ _objc_msgSend$allSupportedLocalesDisplayedInLocale:
+ _objc_msgSend$current
+ _objc_msgSend$currentWithUseCaseIdentifiers:language:isChinaPartOfAdditonalPolicyOptions:
+ _objc_msgSend$fetchCompanionSiriAvailabilityForSetup:completion:
+ _objc_msgSend$initWithRequestId:inputOrigin:
+ _objc_msgSend$isLinwoodAccessRestricted
+ _objc_msgSend$multiUserLocalesForSiriKind:displayedInLocale:
+ _objc_msgSend$setCapabilities:
+ _objc_msgSend$supportsLocale:inOrchestrationMode:
- -[AFSpeechConnectionRequestContext initWithRequestId:]
- GCC_except_table10192
- GCC_except_table10197
- GCC_except_table10198
- GCC_except_table10202
- GCC_except_table10392
- GCC_except_table10565
- GCC_except_table10593
- GCC_except_table10690
- GCC_except_table10694
- GCC_except_table10698
- GCC_except_table10727
- GCC_except_table11078
- GCC_except_table11080
- GCC_except_table11083
- GCC_except_table11096
- GCC_except_table11166
- GCC_except_table11181
- GCC_except_table11206
- GCC_except_table11212
- GCC_except_table11371
- GCC_except_table11375
- GCC_except_table11377
- GCC_except_table11380
- GCC_except_table11386
- GCC_except_table11393
- GCC_except_table11600
- GCC_except_table11924
- GCC_except_table12065
- GCC_except_table12068
- GCC_except_table12070
- GCC_except_table2232
- GCC_except_table2354
- GCC_except_table2367
- GCC_except_table2382
- GCC_except_table2390
- GCC_except_table2394
- GCC_except_table2400
- GCC_except_table2447
- GCC_except_table2449
- GCC_except_table2451
- GCC_except_table2469
- GCC_except_table2475
- GCC_except_table2518
- GCC_except_table2530
- GCC_except_table2675
- GCC_except_table2767
- GCC_except_table2821
- GCC_except_table3048
- GCC_except_table3049
- GCC_except_table3246
- GCC_except_table3307
- GCC_except_table3524
- GCC_except_table3527
- GCC_except_table3536
- GCC_except_table3550
- GCC_except_table3597
- GCC_except_table3603
- GCC_except_table3609
- GCC_except_table3702
- GCC_except_table3706
- GCC_except_table3816
- GCC_except_table3879
- GCC_except_table3881
- GCC_except_table3883
- GCC_except_table3885
- GCC_except_table3899
- GCC_except_table3905
- GCC_except_table4030
- GCC_except_table4034
- GCC_except_table4411
- GCC_except_table4426
- GCC_except_table4433
- GCC_except_table4449
- GCC_except_table4521
- GCC_except_table4550
- GCC_except_table4588
- GCC_except_table4589
- GCC_except_table4590
- GCC_except_table4615
- GCC_except_table4639
- GCC_except_table4999
- GCC_except_table5004
- GCC_except_table5007
- GCC_except_table5013
- GCC_except_table5016
- GCC_except_table5019
- GCC_except_table5022
- GCC_except_table5025
- GCC_except_table5028
- GCC_except_table5058
- GCC_except_table5204
- GCC_except_table5207
- GCC_except_table5280
- GCC_except_table5624
- GCC_except_table5637
- GCC_except_table5641
- GCC_except_table5653
- GCC_except_table5657
- GCC_except_table5770
- GCC_except_table5772
- GCC_except_table5828
- GCC_except_table5872
- GCC_except_table6220
- GCC_except_table6227
- GCC_except_table6233
- GCC_except_table6235
- GCC_except_table6237
- GCC_except_table6279
- GCC_except_table6281
- GCC_except_table6287
- GCC_except_table6292
- GCC_except_table6302
- GCC_except_table6309
- GCC_except_table6316
- GCC_except_table6323
- GCC_except_table6335
- GCC_except_table6338
- GCC_except_table6352
- GCC_except_table6354
- GCC_except_table6356
- GCC_except_table6358
- GCC_except_table6360
- GCC_except_table6362
- GCC_except_table6409
- GCC_except_table6435
- GCC_except_table6492
- GCC_except_table6548
- GCC_except_table6931
- GCC_except_table7079
- GCC_except_table7223
- GCC_except_table7461
- GCC_except_table7470
- GCC_except_table7488
- GCC_except_table7855
- GCC_except_table7859
- GCC_except_table7904
- GCC_except_table7910
- GCC_except_table7937
- GCC_except_table7944
- GCC_except_table8163
- GCC_except_table8237
- GCC_except_table8248
- GCC_except_table8281
- GCC_except_table8284
- GCC_except_table8361
- GCC_except_table8365
- GCC_except_table8375
- GCC_except_table8386
- GCC_except_table8401
- GCC_except_table8486
- GCC_except_table8488
- GCC_except_table8512
- GCC_except_table8635
- GCC_except_table8698
- GCC_except_table8701
- GCC_except_table8705
- GCC_except_table8724
- GCC_except_table8738
- GCC_except_table8814
- GCC_except_table8872
- GCC_except_table8898
- GCC_except_table8925
- GCC_except_table9169
- GCC_except_table9298
- GCC_except_table9349
- GCC_except_table9445
- GCC_except_table9549
- GCC_except_table9651
- GCC_except_table9842
- GCC_except_table9847
- GCC_except_table9975
- _AFIsIPad.isIPad
- _AFLocaleIdentifierSupportsSAE.once
- _AFLocaleIdentifierSupportsSAE.supportedGlobalLocalesWave2
- _AFLocaleIdentifierSupportsSAE.supportedLocales
- ___54-[AFSpeechConnectionRequestContext initWithRequestId:]_block_invoke
- ___65+[AFFeatureFlags(SWEFeatureFlags) isSiriUODAvailableForLanguage:]_block_invoke
- ___AFLocaleIdentifierSupportsSAE_block_invoke
- ___block_descriptor_40_e8_32s_e52_v16?0"<AFSpeechConnectionRequestContextMutating>"8l
- _isSiriUODAvailableForLanguage:.bottomLocales
- _isSiriUODAvailableForLanguage:.once
- _isSiriUODAvailableForLanguage:.top13Locales
- _objc_msgSend$initWithRequestId:
- _objc_msgSend$siriDataSharingOptInStatusHistory
CStrings:
+ "%@ {requestId = %@, inputOrigin = %@}"
+ "%s #Montara restrictions in China, mdm: false, AFMontaraRestricted: false."
+ "%s #SiriAvailability fetching Siri availability for setup with the companion's: %{public}@"
+ "%s 24-hour time: %d (speaker %@, owner %@)"
+ "%s siriAIEnabled=%{BOOL}d siriAIEverAvailable=%{BOOL}d optInStatusVersionMissing=%{BOOL}d → %{BOOL}d"
+ "-[AFSUPFunctionProvider _currentTime:]"
+ "-[AFSettingsConnection fetchCompanionSiriAvailabilityForSetup:completion:]"
+ "-[AFSettingsConnection fetchCompanionSiriAvailabilityForSetup:completion:]_block_invoke"
+ "AFIsAffectedBy2026Incident"
+ "AFSpeechConnectionRequestContext::inputOrigin"
+ "Foundation"
+ "LinwoodChinaMainland"
+ "NSLocaleLanguageSupport2"
+ "No connection to assistantd"
+ "Recognized Speaker Twenty Four Hour Time Display"
+ "SiriAIDowngradeWithoutDataSharingV3Completed"
+ "com.apple.gms.availability"
+ "com.apple.gms.enhancedSiri.wasEverAvailable"
+ "enablePebbleRecognitionWithVoiceProfile"
+ "hi-Latn"
+ "homepod_pause_music_on_request"
+ "v24@?0@\"AFSiriAvailability\"8@\"NSError\"16"
- "%@ {requestId = %@}"
```
