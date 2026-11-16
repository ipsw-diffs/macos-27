## CoreSpeech

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/Versions/A/CoreSpeech`

```diff

-3610.11.1.0.0
-  __TEXT.__text: 0x13cc9c
+3610.19.5.0.0
+  __TEXT.__text: 0x13e2c8
   __TEXT.__lazy_helpers: 0xa8
-  __TEXT.__objc_methlist: 0x141bc
+  __TEXT.__objc_methlist: 0x142f4
   __TEXT.__const: 0x42c
   __TEXT.__dlopen_cstrs: 0x4e
-  __TEXT.__gcc_except_tab: 0x323c
-  __TEXT.__cstring: 0x258cc
-  __TEXT.__oslogstring: 0x1eb6c
-  __TEXT.__unwind_info: 0x5d70
+  __TEXT.__gcc_except_tab: 0x3248
+  __TEXT.__cstring: 0x25a29
+  __TEXT.__oslogstring: 0x1ee85
+  __TEXT.__unwind_info: 0x5dc8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xd80
+  __DATA_CONST.__const: 0xd60
   __DATA_CONST.__objc_classlist: 0x838
   __DATA_CONST.__objc_catlist: 0x48
-  __DATA_CONST.__objc_protolist: 0x4b0
+  __DATA_CONST.__objc_protolist: 0x4c0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0xa6c0
+  __DATA_CONST.__objc_selrefs: 0xa770
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0x658
   __DATA_CONST.__objc_arraydata: 0x3f8
   __DATA_CONST.__got: 0x18b8
-  __AUTH_CONST.__const: 0x5a30
-  __AUTH_CONST.__cfstring: 0x91c0
-  __AUTH_CONST.__objc_const: 0x1fd90
+  __AUTH_CONST.__const: 0x5b60
+  __AUTH_CONST.__cfstring: 0x91e0
+  __AUTH_CONST.__objc_const: 0x1ff08
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__lazy_load_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x918

   __AUTH_CONST.__objc_dictobj: 0x3e8
   __AUTH_CONST.__objc_floatobj: 0x4d0
   __AUTH_CONST.__objc_arrayobj: 0x108
-  __AUTH_CONST.__auth_got: 0xc20
+  __AUTH_CONST.__auth_got: 0xc28
   __AUTH.__objc_data: 0x3b60
-  __DATA.__objc_ivar: 0x1858
-  __DATA.__data: 0x37d4
+  __DATA.__objc_ivar: 0x1870
+  __DATA.__data: 0x3894
   __DATA.__bss: 0x5d0
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x16d0

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 7832
-  Symbols:   17022
-  CStrings:  5212
+  Functions: 7862
+  Symbols:   17082
+  CStrings:  5230
 
Symbols:
+ +[CSAudioInjectionServices invalidateConnection:]
+ -[CSBuiltInVoiceTrigger _finishEnrollmentGateWithTriggerInfo:errorCode:]
+ -[CSBuiltInVoiceTrigger _handleEnrollmentGateSecondPassResult:]
+ -[CSBuiltInVoiceTrigger _setExclaveAsset:fallbackLocale:completion:]
+ -[CSBuiltInVoiceTrigger _shouldRunVoiceTrigger]
+ -[CSBuiltInVoiceTrigger awaitEnrollmentVoiceTriggerWithCompletion:]
+ -[CSBuiltInVoiceTrigger beginEnrollmentForLocale:]
+ -[CSBuiltInVoiceTrigger cancelEnrollmentVoiceTriggerWait]
+ -[CSBuiltInVoiceTrigger endEnrollment]
+ -[CSBuiltInVoiceTrigger enrollmentGateCompletion]
+ -[CSBuiltInVoiceTrigger enrollmentGateStartedAPVoiceTrigger]
+ -[CSBuiltInVoiceTrigger enrollmentLocale]
+ -[CSBuiltInVoiceTrigger isEnrollmentGateActive]
+ -[CSBuiltInVoiceTrigger setEnrollmentGateCompletion:]
+ -[CSBuiltInVoiceTrigger setEnrollmentGateStartedAPVoiceTrigger:]
+ -[CSBuiltInVoiceTrigger setEnrollmentLocale:]
+ -[CSBuiltInVoiceTrigger setIsEnrollmentGateActive:]
+ -[CSEndpointerXPCClient cachedEventTypeByRequestId]
+ -[CSEndpointerXPCClient cachedMetricsByRequestId]
+ -[CSEndpointerXPCClient setCachedEventTypeByRequestId:]
+ -[CSEndpointerXPCClient setCachedMetricsByRequestId:]
+ -[CSOnDeviceCachedIrPurgingHandler _cleanUpSecondPassCheckerCachedIrs]
+ -[CSSpeechManager builtInVoiceTrigger]
+ -[CSVoiceTriggerSecondPassRequestOption setSuppressSiriActivation:]
+ -[CSVoiceTriggerSecondPassRequestOption suppressSiriActivation]
+ GCC_except_table2435
+ GCC_except_table2465
+ GCC_except_table2578
+ GCC_except_table2637
+ GCC_except_table2649
+ GCC_except_table2680
+ GCC_except_table2705
+ GCC_except_table2716
+ GCC_except_table2754
+ GCC_except_table2758
+ GCC_except_table2761
+ GCC_except_table2765
+ GCC_except_table2769
+ GCC_except_table2778
+ GCC_except_table2784
+ GCC_except_table2787
+ GCC_except_table2815
+ GCC_except_table3087
+ GCC_except_table3162
+ GCC_except_table3199
+ GCC_except_table3229
+ GCC_except_table3232
+ GCC_except_table3235
+ GCC_except_table3268
+ GCC_except_table3328
+ GCC_except_table3489
+ GCC_except_table3515
+ GCC_except_table3543
+ GCC_except_table3582
+ GCC_except_table3584
+ GCC_except_table3586
+ GCC_except_table3602
+ GCC_except_table3604
+ GCC_except_table3606
+ GCC_except_table3608
+ GCC_except_table3610
+ GCC_except_table3612
+ GCC_except_table3614
+ GCC_except_table3617
+ GCC_except_table3625
+ GCC_except_table3628
+ GCC_except_table3635
+ GCC_except_table3637
+ GCC_except_table3639
+ GCC_except_table3641
+ GCC_except_table3643
+ GCC_except_table3648
+ GCC_except_table3652
+ GCC_except_table3655
+ GCC_except_table3661
+ GCC_except_table3664
+ GCC_except_table3667
+ GCC_except_table3675
+ GCC_except_table3683
+ GCC_except_table3795
+ GCC_except_table3819
+ GCC_except_table3885
+ GCC_except_table3901
+ GCC_except_table3922
+ GCC_except_table4014
+ GCC_except_table4267
+ GCC_except_table4325
+ GCC_except_table4329
+ GCC_except_table4332
+ GCC_except_table4336
+ GCC_except_table4361
+ GCC_except_table4364
+ GCC_except_table4419
+ GCC_except_table4425
+ GCC_except_table4784
+ GCC_except_table4947
+ GCC_except_table4957
+ GCC_except_table4981
+ GCC_except_table5001
+ GCC_except_table5085
+ GCC_except_table5099
+ GCC_except_table5108
+ GCC_except_table5117
+ GCC_except_table5123
+ GCC_except_table5125
+ GCC_except_table5128
+ GCC_except_table5136
+ GCC_except_table5140
+ GCC_except_table5146
+ GCC_except_table5148
+ GCC_except_table5166
+ GCC_except_table5173
+ GCC_except_table5178
+ GCC_except_table5180
+ GCC_except_table5182
+ GCC_except_table5187
+ GCC_except_table5190
+ GCC_except_table5196
+ GCC_except_table5199
+ GCC_except_table5203
+ GCC_except_table5207
+ GCC_except_table5222
+ GCC_except_table5253
+ GCC_except_table5362
+ GCC_except_table5392
+ GCC_except_table5395
+ GCC_except_table5487
+ GCC_except_table5501
+ GCC_except_table5508
+ GCC_except_table5528
+ GCC_except_table5532
+ GCC_except_table5542
+ GCC_except_table5796
+ GCC_except_table5802
+ GCC_except_table5848
+ GCC_except_table5853
+ GCC_except_table5893
+ GCC_except_table5902
+ GCC_except_table5932
+ GCC_except_table6018
+ GCC_except_table6242
+ GCC_except_table6250
+ GCC_except_table6270
+ GCC_except_table6275
+ GCC_except_table6384
+ GCC_except_table6454
+ GCC_except_table6476
+ GCC_except_table6477
+ GCC_except_table6487
+ GCC_except_table6488
+ GCC_except_table6500
+ GCC_except_table6531
+ GCC_except_table6542
+ GCC_except_table6547
+ GCC_except_table6552
+ GCC_except_table6584
+ GCC_except_table6692
+ GCC_except_table6706
+ GCC_except_table6729
+ GCC_except_table6741
+ GCC_except_table6784
+ GCC_except_table6930
+ GCC_except_table6966
+ GCC_except_table7017
+ GCC_except_table7072
+ GCC_except_table7095
+ GCC_except_table7131
+ GCC_except_table7150
+ GCC_except_table7160
+ GCC_except_table7170
+ GCC_except_table7212
+ GCC_except_table7219
+ GCC_except_table7241
+ GCC_except_table7290
+ GCC_except_table7381
+ GCC_except_table7382
+ GCC_except_table7383
+ GCC_except_table7384
+ GCC_except_table7385
+ GCC_except_table7390
+ GCC_except_table7454
+ GCC_except_table7502
+ GCC_except_table7508
+ GCC_except_table7511
+ GCC_except_table7519
+ GCC_except_table7525
+ GCC_except_table7553
+ GCC_except_table7559
+ GCC_except_table7565
+ GCC_except_table7698
+ _CSIsJ265
+ _OBJC_IVAR_$_CSBuiltInVoiceTrigger._enrollmentGateCompletion
+ _OBJC_IVAR_$_CSBuiltInVoiceTrigger._enrollmentGateStartedAPVoiceTrigger
+ _OBJC_IVAR_$_CSBuiltInVoiceTrigger._enrollmentLocale
+ _OBJC_IVAR_$_CSBuiltInVoiceTrigger._isEnrollmentGateActive
+ _OBJC_IVAR_$_CSEndpointerXPCClient._cachedEventTypeByRequestId
+ _OBJC_IVAR_$_CSEndpointerXPCClient._cachedMetricsByRequestId
+ _OBJC_IVAR_$_CSVoiceTriggerSecondPassRequestOption._suppressSiriActivation
+ _OBJC_IVAR_$_CSVoiceTriggerStatistics._vtStatsBiomeSource
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSBuiltInVoiceTriggering
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSVoiceTriggerManagerProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSBuiltInVoiceTriggering
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSVoiceTriggerManagerProviding
+ __OBJC_$_PROTOCOL_REFS_CSBuiltInVoiceTriggering
+ __OBJC_$_PROTOCOL_REFS_CSVoiceTriggerManagerProviding
+ __OBJC_LABEL_PROTOCOL_$_CSBuiltInVoiceTriggering
+ __OBJC_LABEL_PROTOCOL_$_CSVoiceTriggerManagerProviding
+ __OBJC_PROTOCOL_$_CSBuiltInVoiceTriggering
+ __OBJC_PROTOCOL_$_CSVoiceTriggerManagerProviding
+ ___38-[CSBuiltInVoiceTrigger endEnrollment]_block_invoke
+ ___50-[CSBuiltInVoiceTrigger beginEnrollmentForLocale:]_block_invoke
+ ___57-[CSBuiltInVoiceTrigger cancelEnrollmentVoiceTriggerWait]_block_invoke
+ ___63-[CSBuiltInVoiceTrigger _handleEnrollmentGateSecondPassResult:]_block_invoke
+ ___67-[CSBuiltInVoiceTrigger awaitEnrollmentVoiceTriggerWithCompletion:]_block_invoke
+ ___68-[CSBuiltInVoiceTrigger _setExclaveAsset:fallbackLocale:completion:]_block_invoke
+ ___70-[CSOnDeviceCachedIrPurgingHandler _cleanUpSecondPassCheckerCachedIrs]_block_invoke
+ ___block_descriptor_41_e8_32s_e8_v16?0Q8l
+ ___block_descriptor_48_e8_32bs_e5_v8?0l
+ ___block_descriptor_48_e8_32s40bs_e8_v16?0Q8l
+ ___block_descriptor_48_e8_32s40s_e8_v12?0B8l
+ ___block_descriptor_56_e8_32s40bs_e18_v16?0"NSString"8l
+ ___block_descriptor_56_e8_32s40bs_e23_v28?0B8"NSError"12Q20l
+ ___block_descriptor_56_e8_32s40bs_e26_v36?0B8"NSError"12Q20Q28l
+ ___block_descriptor_73_e8_32s40s48s56w_e58_v24?0"CSVoiceTriggerSecondPassResultHolder"8"NSError"16l
+ _objc_msgSend$_cleanUpSecondPassCheckerCachedIrs
+ _objc_msgSend$_finishEnrollmentGateWithTriggerInfo:errorCode:
+ _objc_msgSend$_handleEnrollmentGateSecondPassResult:
+ _objc_msgSend$_setExclaveAsset:fallbackLocale:completion:
+ _objc_msgSend$_shouldRunVoiceTrigger
+ _objc_msgSend$invalidateConnection:
+ _objc_msgSend$isEnrollmentGateActive
+ _objc_msgSend$onDeviceCompilationQueue
+ _objc_msgSend$osdConfigPath
+ _objc_msgSend$purgeCachedIrForAssetExcludingCurrentAsset:baseCachedIrDir:
+ _objc_msgSend$removeCachedIrsForModelType:
+ _objc_msgSend$setIsEnrollmentGateActive:
+ _objc_msgSend$setSuppressSiriActivation:
+ _objc_msgSend$suppressSiriActivation
- -[CSEndpointerXPCClient cachedEventType]
- -[CSEndpointerXPCClient cachedMetrics]
- -[CSEndpointerXPCClient setCachedEventType:]
- -[CSEndpointerXPCClient setCachedMetrics:]
- -[CSOnDeviceCachedIrPurgingHandler _cleanUpOnDeviceCompilationPath]
- GCC_except_table2434
- GCC_except_table2464
- GCC_except_table2577
- GCC_except_table2636
- GCC_except_table2648
- GCC_except_table2679
- GCC_except_table2704
- GCC_except_table2715
- GCC_except_table2749
- GCC_except_table2757
- GCC_except_table2760
- GCC_except_table2763
- GCC_except_table2767
- GCC_except_table2777
- GCC_except_table2783
- GCC_except_table2785
- GCC_except_table2814
- GCC_except_table3086
- GCC_except_table3161
- GCC_except_table3198
- GCC_except_table3228
- GCC_except_table3231
- GCC_except_table3234
- GCC_except_table3267
- GCC_except_table3327
- GCC_except_table3488
- GCC_except_table3514
- GCC_except_table3542
- GCC_except_table3580
- GCC_except_table3583
- GCC_except_table3585
- GCC_except_table3601
- GCC_except_table3603
- GCC_except_table3605
- GCC_except_table3607
- GCC_except_table3609
- GCC_except_table3611
- GCC_except_table3613
- GCC_except_table3616
- GCC_except_table3624
- GCC_except_table3627
- GCC_except_table3634
- GCC_except_table3636
- GCC_except_table3638
- GCC_except_table3640
- GCC_except_table3642
- GCC_except_table3644
- GCC_except_table3649
- GCC_except_table3654
- GCC_except_table3656
- GCC_except_table3662
- GCC_except_table3665
- GCC_except_table3674
- GCC_except_table3679
- GCC_except_table3794
- GCC_except_table3818
- GCC_except_table3884
- GCC_except_table3900
- GCC_except_table3921
- GCC_except_table4013
- GCC_except_table4266
- GCC_except_table4323
- GCC_except_table4328
- GCC_except_table4331
- GCC_except_table4335
- GCC_except_table4360
- GCC_except_table4363
- GCC_except_table4418
- GCC_except_table4424
- GCC_except_table4783
- GCC_except_table4946
- GCC_except_table4956
- GCC_except_table4980
- GCC_except_table5000
- GCC_except_table5084
- GCC_except_table5098
- GCC_except_table5107
- GCC_except_table5116
- GCC_except_table5122
- GCC_except_table5124
- GCC_except_table5127
- GCC_except_table5135
- GCC_except_table5139
- GCC_except_table5145
- GCC_except_table5147
- GCC_except_table5165
- GCC_except_table5172
- GCC_except_table5177
- GCC_except_table5179
- GCC_except_table5181
- GCC_except_table5183
- GCC_except_table5189
- GCC_except_table5193
- GCC_except_table5198
- GCC_except_table5200
- GCC_except_table5206
- GCC_except_table5221
- GCC_except_table5252
- GCC_except_table5361
- GCC_except_table5391
- GCC_except_table5394
- GCC_except_table5484
- GCC_except_table5498
- GCC_except_table5505
- GCC_except_table5525
- GCC_except_table5529
- GCC_except_table5539
- GCC_except_table5785
- GCC_except_table5791
- GCC_except_table5824
- GCC_except_table5829
- GCC_except_table5867
- GCC_except_table5876
- GCC_except_table5906
- GCC_except_table5992
- GCC_except_table6216
- GCC_except_table6224
- GCC_except_table6244
- GCC_except_table6249
- GCC_except_table6358
- GCC_except_table6428
- GCC_except_table6450
- GCC_except_table6451
- GCC_except_table6461
- GCC_except_table6462
- GCC_except_table6474
- GCC_except_table6505
- GCC_except_table6516
- GCC_except_table6521
- GCC_except_table6526
- GCC_except_table6558
- GCC_except_table6640
- GCC_except_table6677
- GCC_except_table6680
- GCC_except_table6715
- GCC_except_table6758
- GCC_except_table6904
- GCC_except_table6940
- GCC_except_table6991
- GCC_except_table7046
- GCC_except_table7069
- GCC_except_table7105
- GCC_except_table7124
- GCC_except_table7134
- GCC_except_table7144
- GCC_except_table7186
- GCC_except_table7193
- GCC_except_table7215
- GCC_except_table7264
- GCC_except_table7355
- GCC_except_table7356
- GCC_except_table7357
- GCC_except_table7358
- GCC_except_table7359
- GCC_except_table7364
- GCC_except_table7428
- GCC_except_table7476
- GCC_except_table7482
- GCC_except_table7485
- GCC_except_table7493
- GCC_except_table7499
- GCC_except_table7524
- GCC_except_table7530
- GCC_except_table7536
- GCC_except_table7668
- _OBJC_IVAR_$_CSEndpointerXPCClient._cachedEventType
- _OBJC_IVAR_$_CSEndpointerXPCClient._cachedMetrics
- ___67-[CSOnDeviceCachedIrPurgingHandler _cleanUpOnDeviceCompilationPath]_block_invoke
- ___block_descriptor_32_e8_v16?0Q8l
- ___block_descriptor_72_e8_32s40s48s56w_e58_v24?0"CSVoiceTriggerSecondPassResultHolder"8"NSError"16l
- _objc_msgSend$_cleanUpOnDeviceCompilationPath
- _objc_msgSend$purgeCachedIrForTrialAssetExcludingCurrentAsset:baseCachedIrDir:
- _objc_msgSend$removeOnDeviceCachedPath
CStrings:
+ "%s Audio injection enabled, skip creating CSAggressiveECModeHandler"
+ "%s CSVoiceTriggerSecondPass[%{public}@]:Siri activation suppressed, skip prewarm"
+ "%s Cannot wait for enrollment voice trigger : %{public}@"
+ "%s Created OSDAnalyzer: %{public}@ model path: %{public}@"
+ "%s Disable PHS since the enrollment gate only needs a Hey Siri detection"
+ "%s Enrollment ended, restoring the exclave asset"
+ "%s Enrollment for locale %{public}@"
+ "%s Enrollment gate finished with error code %lu"
+ "%s Enrollment gate got second pass result %d"
+ "%s Fingerprint frame skip rate : %lu"
+ "%s Setting the exclave asset for enrollment locale %{public}@ failed, restoring the regular asset"
+ "%s VoiceTrigger is already listening, reuse it for the enrollment gate"
+ "%s VoiceTrigger is disabled, clean up second pass checker cached irs"
+ "%s VoiceTrigger is disabled, keep cached irs on HomePod"
+ "%s Waiting for enrollment voice trigger"
+ "%s skip purging cached irs for endpoint asset"
+ "-[CSAggressiveECModeHandler init]"
+ "-[CSBuiltInVoiceTrigger _finishEnrollmentGateWithTriggerInfo:errorCode:]"
+ "-[CSBuiltInVoiceTrigger _handleEnrollmentGateSecondPassResult:]"
+ "-[CSBuiltInVoiceTrigger _setExclaveAsset:fallbackLocale:completion:]_block_invoke"
+ "-[CSBuiltInVoiceTrigger awaitEnrollmentVoiceTriggerWithCompletion:]_block_invoke"
+ "-[CSBuiltInVoiceTrigger beginEnrollmentForLocale:]_block_invoke"
+ "-[CSBuiltInVoiceTrigger endEnrollment]_block_invoke"
- "%s Created OSDAnalyzer: %{public}@"
- "%s VoiceTrigger is disabled, clean up cached ir path"
- "%s purging for specific device is not handled here"
- "-[CSOnDeviceCachedIrPurgingHandler _purgeCachedIrFilesWithAsset:]"
- "CSOnDeviceCachedIrPurgingHandler"
```
