## AVFCore

> `/System/Library/PrivateFrameworks/AVFCore.framework/Versions/A/AVFCore`

```diff

-2475.13.5.1.0
-  __TEXT.__text: 0x1b5400
-  __TEXT.__objc_methlist: 0x1bf94
-  __TEXT.__gcc_except_tab: 0x98d8
+2485.5.1.0.0
+  __TEXT.__text: 0x1b6704
+  __TEXT.__objc_methlist: 0x1c054
+  __TEXT.__gcc_except_tab: 0x9a14
   __TEXT.__const: 0x1f2c
-  __TEXT.__cstring: 0x2713b
-  __TEXT.__oslogstring: 0x4ab6
+  __TEXT.__cstring: 0x273fb
+  __TEXT.__oslogstring: 0x4a3b
   __TEXT.__ustring: 0x18
   __TEXT.__swift5_typeref: 0x41a
   __TEXT.__constg_swiftt: 0x290

   __TEXT.__swift5_proto: 0x6c
   __TEXT.__swift5_types: 0x48
   __TEXT.__swift5_capture: 0x60
-  __TEXT.__unwind_info: 0xc3a8
+  __TEXT.__unwind_info: 0xc478
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3528
+  __DATA_CONST.__const: 0x35b0
   __DATA_CONST.__objc_classlist: 0x1258
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x1c0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb1f8
+  __DATA_CONST.__objc_selrefs: 0xb270
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0xd88
-  __DATA_CONST.__objc_arraydata: 0x308
-  __DATA_CONST.__got: 0x46b8
-  __AUTH_CONST.__const: 0x3c70
-  __AUTH_CONST.__cfstring: 0x1abe0
-  __AUTH_CONST.__objc_const: 0x328e0
+  __DATA_CONST.__objc_arraydata: 0x360
+  __DATA_CONST.__got: 0x46d8
+  __AUTH_CONST.__const: 0x3cc0
+  __AUTH_CONST.__cfstring: 0x1ae20
+  __AUTH_CONST.__objc_const: 0x32a10
   __AUTH_CONST.__objc_intobj: 0x240
   __AUTH_CONST.__objc_doubleobj: 0x30
-  __AUTH_CONST.__objc_arrayobj: 0x360
+  __AUTH_CONST.__objc_arrayobj: 0x378
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x1e20
+  __AUTH_CONST.__auth_got: 0x1e30
   __AUTH.__objc_data: 0x82d0
   __AUTH.__data: 0x1d8
-  __DATA.__objc_ivar: 0x27bc
+  __DATA.__objc_ivar: 0x27d0
   __DATA.__data: 0x16b0
   __DATA.__crash_info: 0x148
   __DATA.__common: 0x1c0

   __DATA_DIRTY.__objc_data: 0x3520
   __DATA_DIRTY.__data: 0x8
   __DATA_DIRTY.__common: 0x1c0
-  __DATA_DIRTY.__bss: 0x1a0
+  __DATA_DIRTY.__bss: 0x1b0
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVRouting.framework/Versions/A/AVRouting
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12003
-  Symbols:   27956
-  CStrings:  4285
+  Functions: 12040
+  Symbols:   28038
+  CStrings:  4303
 
Symbols:
+ +[AVPlayerItemVideoOutput(AVPlayerItemVideoOutput_UnitTestOnly) _setImageAvailableCallbackAfterPromotionTestHook:]
+ +[AVURLAsset(AVURLAssetConnectionPrewarming) setUpConnectionForURL:options:completionHandler:]
+ -[AVPlayer appliesLoudnessAdjustmentsAutomatically]
+ -[AVPlayer setAppliesLoudnessAdjustmentsAutomatically:]
+ -[AVPlayerItem _updateContentLibraryLoudnessTargetOnFigPlaybackItem]
+ -[AVPlayerItem _updateContentTypeForLoudnessControlOnFigPlaybackItem]
+ -[AVPlayerItem _updateLoudnessControlModeOnFigPlaybackItem]
+ -[AVPlayerItem prefersAudioVideoVariants]
+ -[AVPlayerItem setPrefersAudioVideoVariants:]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing) allowedAudioSpatializationFormats]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing) audioMix]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing) audioTimePitchAlgorithm]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing) isAudioSpatializationAllowed]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing) setAllowedAudioSpatializationFormats:]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing) setAudioMix:]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing) setAudioSpatializationAllowed:]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing) setAudioTimePitchAlgorithm:]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing_Private) audioTapProcessor]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing_Private) loudnessInfo]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing_Private) resetAudioBufferedAhead]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing_Private) setAudioTapProcessor:]
+ -[AVPlayerItem(AVPlayerItemAudioProcessing_Private) setLoudnessInfo:]
+ -[AVPlayerItem(AVPlayerItemLoudnessControl) contentLibraryLoudnessTarget]
+ -[AVPlayerItem(AVPlayerItemLoudnessControl) contentTypeForLoudnessControl]
+ -[AVPlayerItem(AVPlayerItemLoudnessControl) loudnessControlMode]
+ -[AVPlayerItem(AVPlayerItemLoudnessControl) setContentLibraryLoudnessTarget:]
+ -[AVPlayerItem(AVPlayerItemLoudnessControl) setContentTypeForLoudnessControl:]
+ -[AVPlayerItem(AVPlayerItemLoudnessControl) setLoudnessControlMode:]
+ GCC_except_table1006
+ GCC_except_table1025
+ GCC_except_table1027
+ GCC_except_table1029
+ GCC_except_table1031
+ GCC_except_table1036
+ GCC_except_table1038
+ GCC_except_table1040
+ GCC_except_table1042
+ GCC_except_table1053
+ GCC_except_table1071
+ GCC_except_table1076
+ GCC_except_table1078
+ GCC_except_table1080
+ GCC_except_table1081
+ GCC_except_table1085
+ GCC_except_table1088
+ GCC_except_table1102
+ GCC_except_table1106
+ GCC_except_table1110
+ GCC_except_table1118
+ GCC_except_table1121
+ GCC_except_table1124
+ GCC_except_table1131
+ GCC_except_table1135
+ GCC_except_table1143
+ GCC_except_table1147
+ GCC_except_table1148
+ GCC_except_table1153
+ GCC_except_table1157
+ GCC_except_table1164
+ GCC_except_table1166
+ GCC_except_table1169
+ GCC_except_table1170
+ GCC_except_table1179
+ GCC_except_table287
+ GCC_except_table294
+ GCC_except_table296
+ GCC_except_table297
+ GCC_except_table324
+ GCC_except_table343
+ GCC_except_table345
+ GCC_except_table353
+ GCC_except_table354
+ GCC_except_table364
+ GCC_except_table366
+ GCC_except_table373
+ GCC_except_table374
+ GCC_except_table375
+ GCC_except_table381
+ GCC_except_table392
+ GCC_except_table404
+ GCC_except_table406
+ GCC_except_table418
+ GCC_except_table426
+ GCC_except_table428
+ GCC_except_table446
+ GCC_except_table448
+ GCC_except_table458
+ GCC_except_table462
+ GCC_except_table464
+ GCC_except_table470
+ GCC_except_table478
+ GCC_except_table485
+ GCC_except_table489
+ GCC_except_table491
+ GCC_except_table497
+ GCC_except_table507
+ GCC_except_table508
+ GCC_except_table509
+ GCC_except_table529
+ GCC_except_table532
+ GCC_except_table541
+ GCC_except_table543
+ GCC_except_table546
+ GCC_except_table548
+ GCC_except_table550
+ GCC_except_table554
+ GCC_except_table556
+ GCC_except_table560
+ GCC_except_table563
+ GCC_except_table564
+ GCC_except_table567
+ GCC_except_table573
+ GCC_except_table575
+ GCC_except_table578
+ GCC_except_table589
+ GCC_except_table591
+ GCC_except_table593
+ GCC_except_table594
+ GCC_except_table597
+ GCC_except_table601
+ GCC_except_table607
+ GCC_except_table611
+ GCC_except_table613
+ GCC_except_table614
+ GCC_except_table621
+ GCC_except_table622
+ GCC_except_table624
+ GCC_except_table625
+ GCC_except_table636
+ GCC_except_table638
+ GCC_except_table643
+ GCC_except_table646
+ GCC_except_table647
+ GCC_except_table649
+ GCC_except_table658
+ GCC_except_table662
+ GCC_except_table663
+ GCC_except_table667
+ GCC_except_table673
+ GCC_except_table675
+ GCC_except_table681
+ GCC_except_table683
+ GCC_except_table684
+ GCC_except_table686
+ GCC_except_table689
+ GCC_except_table694
+ GCC_except_table696
+ GCC_except_table706
+ GCC_except_table710
+ GCC_except_table722
+ GCC_except_table724
+ GCC_except_table730
+ GCC_except_table732
+ GCC_except_table734
+ GCC_except_table742
+ GCC_except_table746
+ GCC_except_table748
+ GCC_except_table758
+ GCC_except_table762
+ GCC_except_table770
+ GCC_except_table772
+ GCC_except_table773
+ GCC_except_table777
+ GCC_except_table782
+ GCC_except_table787
+ GCC_except_table792
+ GCC_except_table798
+ GCC_except_table804
+ GCC_except_table814
+ GCC_except_table817
+ GCC_except_table819
+ GCC_except_table823
+ GCC_except_table828
+ GCC_except_table830
+ GCC_except_table833
+ GCC_except_table839
+ GCC_except_table845
+ GCC_except_table859
+ GCC_except_table861
+ GCC_except_table864
+ GCC_except_table867
+ GCC_except_table872
+ GCC_except_table878
+ GCC_except_table883
+ GCC_except_table886
+ GCC_except_table892
+ GCC_except_table896
+ GCC_except_table899
+ GCC_except_table903
+ GCC_except_table907
+ GCC_except_table909
+ GCC_except_table913
+ GCC_except_table923
+ GCC_except_table930
+ GCC_except_table939
+ GCC_except_table943
+ GCC_except_table947
+ GCC_except_table954
+ GCC_except_table956
+ GCC_except_table958
+ GCC_except_table960
+ GCC_except_table964
+ GCC_except_table968
+ GCC_except_table983
+ GCC_except_table985
+ GCC_except_table990
+ GCC_except_table991
+ GCC_except_table995
+ GCC_except_table998
+ _AVLoudnessControlModeAdvertisement
+ _AVLoudnessControlModeUseItemMeasurement
+ _AVLoudnessControlModeUseSequenceMeasurement
+ _AVMetadataIdentifierISOUserDataAudioStreamLoudness
+ _AVMetadataIdentifierISOUserDataContentTypeForLoudnessControl
+ _AVMetadataIdentifierQuickTimeUserDataAudioStreamLoudness
+ _AVMetadataIdentifierQuickTimeUserDataContentTypeForLoudnessControl
+ _AVPlayerItemVideoOutputReleaseContext
+ _AVQuickTimeContentTypeForLoudnessControlAlarm
+ _AVQuickTimeContentTypeForLoudnessControlAudiobookPodcastOrRadioProgram
+ _AVQuickTimeContentTypeForLoudnessControlDeviceCaptureOrUserGenerated
+ _AVQuickTimeContentTypeForLoudnessControlLiveAudiovisualProduction
+ _AVQuickTimeContentTypeForLoudnessControlMusic
+ _AVQuickTimeContentTypeForLoudnessControlOnDemandAudiovisualProduction
+ _AVQuickTimeContentTypeForLoudnessControlOtherSystemSound
+ _AVQuickTimeContentTypeForLoudnessControlRingtone
+ _AVQuickTimeContentTypeForLoudnessControlSynthesizedSpeech
+ _AVQuickTimeContentTypeForLoudnessControlToCTLCContentType
+ _AVQuickTimeContentTypeForLoudnessControlUserInterfaceFeedback
+ _FigAssetSetUpConnectionForURLAsync
+ _OBJC_IVAR_$_AVPlayerInternal.appliesLoudnessAdjustmentsAutomatically
+ _OBJC_IVAR_$_AVPlayerItemInternal.contentLibraryLoudnessTarget
+ _OBJC_IVAR_$_AVPlayerItemInternal.contentTypeForLoudnessControl
+ _OBJC_IVAR_$_AVPlayerItemInternal.loudnessControlMode
+ _OBJC_IVAR_$_AVPlayerItemInternal.prefersAudioVideoVariants
+ __OBJC_$_CLASS_METHODS_AVPlayerItem(AVPlayerItemAudioProcessing|AVPlayerItemAudioProcessing_Private|AVPlayerItemLoudnessControl|AVPlayerItemCustomMediaSelectionScheme|AVPlayerItemCustomMediaSelectionScheme_Private|AVPlayerItemProtectedContent|AVPlayerItemProtectedContentPrivate|AVPlayerItemLogging|AVPlayerItemOutputs|AVPlayerItemMediaDataCollectors|LegibleOutputSupport|MetadataOutputSupport|RenderedLegibleOutputSupport|SwiftMedia|AVPlayerItemAVKit|AVPlayerItemVideoEnhancement|AVPlayerInterstitialSupport|AVPlayerItemIntegratedTimelineSupport|AVPlayerItemSpeedRamp|AVPlayerItemSpeedRampInternal|AVMetricEventStreamPublisherInternal|AVPlayerItemTrackInfoCaching|fixFaultyTFDT165791136)
+ __OBJC_$_CLASS_METHODS_AVPlayerItemVideoOutput(AVPlayerItemVideoOutput_UnitTestOnly)
+ __OBJC_$_CLASS_METHODS_AVURLAsset(AVAssetCache|AVURLAssetCache_Private|AVAssetVariantInspection|AVURLAssetURLHandlingInternal|AVURLAssetURLHandling|AVMediaExtension|AVURLAssetInstanceIdentiferMapping|AVURLAssetContentKeyEligibility|AVURLAssetContentKeyEligibilityInternal|AVURLAssetCustomURLHandling|NSItemProvider|AVAssetSerializableCreationOptionsSupport|AVNSURLSessionAsset|AVURLAssetConnectionPrewarming)
+ __OBJC_$_INSTANCE_METHODS_AVPlayerItem(AVPlayerItemAudioProcessing|AVPlayerItemAudioProcessing_Private|AVPlayerItemLoudnessControl|AVPlayerItemCustomMediaSelectionScheme|AVPlayerItemCustomMediaSelectionScheme_Private|AVPlayerItemProtectedContent|AVPlayerItemProtectedContentPrivate|AVPlayerItemLogging|AVPlayerItemOutputs|AVPlayerItemMediaDataCollectors|LegibleOutputSupport|MetadataOutputSupport|RenderedLegibleOutputSupport|SwiftMedia|AVPlayerItemAVKit|AVPlayerItemVideoEnhancement|AVPlayerInterstitialSupport|AVPlayerItemIntegratedTimelineSupport|AVPlayerItemSpeedRamp|AVPlayerItemSpeedRampInternal|AVMetricEventStreamPublisherInternal|AVPlayerItemTrackInfoCaching|fixFaultyTFDT165791136)
+ __OBJC_$_INSTANCE_METHODS_AVURLAsset(AVAssetCache|AVURLAssetCache_Private|AVAssetVariantInspection|AVURLAssetURLHandlingInternal|AVURLAssetURLHandling|AVMediaExtension|AVURLAssetInstanceIdentiferMapping|AVURLAssetContentKeyEligibility|AVURLAssetContentKeyEligibilityInternal|AVURLAssetCustomURLHandling|NSItemProvider|AVAssetSerializableCreationOptionsSupport|AVNSURLSessionAsset|AVURLAssetConnectionPrewarming)
+ __OBJC_CLASS_PROTOCOLS_$_AVPlayerItem(AVPlayerItemAudioProcessing|AVPlayerItemAudioProcessing_Private|AVPlayerItemLoudnessControl|AVPlayerItemCustomMediaSelectionScheme|AVPlayerItemCustomMediaSelectionScheme_Private|AVPlayerItemProtectedContent|AVPlayerItemProtectedContentPrivate|AVPlayerItemLogging|AVPlayerItemOutputs|AVPlayerItemMediaDataCollectors|LegibleOutputSupport|MetadataOutputSupport|RenderedLegibleOutputSupport|SwiftMedia|AVPlayerItemAVKit|AVPlayerItemVideoEnhancement|AVPlayerInterstitialSupport|AVPlayerItemIntegratedTimelineSupport|AVPlayerItemSpeedRamp|AVPlayerItemSpeedRampInternal|AVMetricEventStreamPublisherInternal|AVPlayerItemTrackInfoCaching|fixFaultyTFDT165791136)
+ __OBJC_CLASS_PROTOCOLS_$_AVURLAsset(AVAssetCache|AVURLAssetCache_Private|AVAssetVariantInspection|AVURLAssetURLHandlingInternal|AVURLAssetURLHandling|AVMediaExtension|AVURLAssetInstanceIdentiferMapping|AVURLAssetContentKeyEligibility|AVURLAssetContentKeyEligibilityInternal|AVURLAssetCustomURLHandling|NSItemProvider|AVAssetSerializableCreationOptionsSupport|AVNSURLSessionAsset|AVURLAssetConnectionPrewarming)
+ ___41-[AVPlayerItem prefersAudioVideoVariants]_block_invoke
+ ___45-[AVPlayerItem setPrefersAudioVideoVariants:]_block_invoke
+ ___45-[AVPlayerItem setPrefersAudioVideoVariants:]_block_invoke_2
+ ___51-[AVPlayer appliesLoudnessAdjustmentsAutomatically]_block_invoke
+ ___53-[AVPlayerItem(AVPlayerItemAudioProcessing) audioMix]_block_invoke
+ ___55-[AVPlayer setAppliesLoudnessAdjustmentsAutomatically:]_block_invoke
+ ___55-[AVPlayer setAppliesLoudnessAdjustmentsAutomatically:]_block_invoke_2
+ ___57-[AVPlayerItem(AVPlayerItemAudioProcessing) setAudioMix:]_block_invoke
+ ___57-[AVPlayerItem(AVPlayerItemAudioProcessing) setAudioMix:]_block_invoke_2
+ ___59-[AVPlayerItem _updateLoudnessControlModeOnFigPlaybackItem]_block_invoke
+ ___64-[AVPlayerItem(AVPlayerItemLoudnessControl) loudnessControlMode]_block_invoke
+ ___65-[AVPlayerItem(AVPlayerItemAudioProcessing_Private) loudnessInfo]_block_invoke
+ ___68-[AVPlayerItem _updateContentLibraryLoudnessTargetOnFigPlaybackItem]_block_invoke
+ ___68-[AVPlayerItem(AVPlayerItemAudioProcessing) audioTimePitchAlgorithm]_block_invoke
+ ___68-[AVPlayerItem(AVPlayerItemLoudnessControl) setLoudnessControlMode:]_block_invoke
+ ___69-[AVPlayerItem _updateContentTypeForLoudnessControlOnFigPlaybackItem]_block_invoke
+ ___69-[AVPlayerItem(AVPlayerItemAudioProcessing_Private) setLoudnessInfo:]_block_invoke
+ ___70-[AVPlayerItem(AVPlayerItemAudioProcessing_Private) audioTapProcessor]_block_invoke
+ ___72-[AVPlayerItem(AVPlayerItemAudioProcessing) setAudioTimePitchAlgorithm:]_block_invoke
+ ___73-[AVPlayerItem(AVPlayerItemAudioProcessing) isAudioSpatializationAllowed]_block_invoke
+ ___73-[AVPlayerItem(AVPlayerItemLoudnessControl) contentLibraryLoudnessTarget]_block_invoke
+ ___74-[AVPlayerItem(AVPlayerItemLoudnessControl) contentTypeForLoudnessControl]_block_invoke
+ ___75-[AVPlayerItem(AVPlayerItemAudioProcessing) setAudioSpatializationAllowed:]_block_invoke
+ ___76-[AVPlayerItem(AVPlayerItemAudioProcessing_Private) resetAudioBufferedAhead]_block_invoke
+ ___77-[AVPlayerItem(AVPlayerItemLoudnessControl) setContentLibraryLoudnessTarget:]_block_invoke
+ ___78-[AVPlayerItem(AVPlayerItemAudioProcessing) allowedAudioSpatializationFormats]_block_invoke
+ ___78-[AVPlayerItem(AVPlayerItemLoudnessControl) setContentTypeForLoudnessControl:]_block_invoke
+ ___82-[AVPlayerItem(AVPlayerItemAudioProcessing) setAllowedAudioSpatializationFormats:]_block_invoke
+ ___94+[AVURLAsset(AVURLAssetConnectionPrewarming) setUpConnectionForURL:options:completionHandler:]_block_invoke
+ ___94+[AVURLAsset(AVURLAssetConnectionPrewarming) setUpConnectionForURL:options:completionHandler:]_block_invoke_2
+ ___block_descriptor_40_e8_32b_e8_v12?0i8l
+ ___getSetUpConnectionCompletionQueue_block_invoke
+ _dispatch_async_f
+ _kFigPlaybackItemProperty_ContentLibraryLoudnessTarget
+ _kFigPlaybackItemProperty_ContentTypeForLoudnessControl
+ _kFigPlaybackItemProperty_LoudnessControlMode
+ _kFigPlaybackItemProperty_PrefersAudioVideoVariants
+ _kFigPlayerProperty_AppliesLoudnessAdjustmentsAutomatically
+ _objc_msgSend$_updateContentLibraryLoudnessTargetOnFigPlaybackItem
+ _objc_msgSend$_updateContentTypeForLoudnessControlOnFigPlaybackItem
+ _objc_msgSend$_updateLoudnessControlModeOnFigPlaybackItem
+ _objc_msgSend$appliesLoudnessAdjustmentsAutomatically
+ _objc_msgSend$contentLibraryLoudnessTarget
+ _objc_msgSend$contentTypeForLoudnessControl
+ _objc_msgSend$loudnessControlMode
+ _objc_msgSend$prefersAudioVideoVariants
+ _objc_msgSend$setAppliesLoudnessAdjustmentsAutomatically:
+ _objc_msgSend$setContentLibraryLoudnessTarget:
+ _objc_msgSend$setContentTypeForLoudnessControl:
+ _objc_msgSend$setLoudnessControlMode:
+ _objc_msgSend$setPrefersAudioVideoVariants:
+ _objc_msgSend$setSuppressesAudioOnlyVariants:
+ _objc_msgSend$suppressesAudioOnlyVariants
+ _sImageAvailableCallbackAfterPromotionTestHook
- -[AVPlayerItem allowedAudioSpatializationFormats]
- -[AVPlayerItem audioMix]
- -[AVPlayerItem audioTapProcessor]
- -[AVPlayerItem audioTimePitchAlgorithm]
- -[AVPlayerItem isAudioSpatializationAllowed]
- -[AVPlayerItem loudnessInfo]
- -[AVPlayerItem resetAudioBufferedAhead]
- -[AVPlayerItem setAllowedAudioSpatializationFormats:]
- -[AVPlayerItem setAudioMix:]
- -[AVPlayerItem setAudioSpatializationAllowed:]
- -[AVPlayerItem setAudioTapProcessor:]
- -[AVPlayerItem setAudioTimePitchAlgorithm:]
- -[AVPlayerItem setLoudnessInfo:]
- GCC_except_table1005
- GCC_except_table1009
- GCC_except_table1011
- GCC_except_table1013
- GCC_except_table1016
- GCC_except_table1018
- GCC_except_table1020
- GCC_except_table1022
- GCC_except_table1045
- GCC_except_table1051
- GCC_except_table1056
- GCC_except_table1058
- GCC_except_table1060
- GCC_except_table1061
- GCC_except_table1062
- GCC_except_table1068
- GCC_except_table1070
- GCC_except_table1086
- GCC_except_table1095
- GCC_except_table1098
- GCC_except_table1099
- GCC_except_table1101
- GCC_except_table1104
- GCC_except_table1107
- GCC_except_table1111
- GCC_except_table1123
- GCC_except_table1128
- GCC_except_table1130
- GCC_except_table1133
- GCC_except_table1137
- GCC_except_table1144
- GCC_except_table1146
- GCC_except_table1149
- GCC_except_table285
- GCC_except_table289
- GCC_except_table291
- GCC_except_table292
- GCC_except_table299
- GCC_except_table307
- GCC_except_table337
- GCC_except_table340
- GCC_except_table348
- GCC_except_table349
- GCC_except_table357
- GCC_except_table361
- GCC_except_table363
- GCC_except_table367
- GCC_except_table369
- GCC_except_table376
- GCC_except_table400
- GCC_except_table401
- GCC_except_table403
- GCC_except_table413
- GCC_except_table421
- GCC_except_table427
- GCC_except_table436
- GCC_except_table439
- GCC_except_table450
- GCC_except_table453
- GCC_except_table459
- GCC_except_table461
- GCC_except_table473
- GCC_except_table475
- GCC_except_table483
- GCC_except_table487
- GCC_except_table493
- GCC_except_table496
- GCC_except_table504
- GCC_except_table519
- GCC_except_table525
- GCC_except_table530
- GCC_except_table531
- GCC_except_table551
- GCC_except_table555
- GCC_except_table561
- GCC_except_table566
- GCC_except_table569
- GCC_except_table576
- GCC_except_table582
- GCC_except_table588
- GCC_except_table595
- GCC_except_table596
- GCC_except_table598
- GCC_except_table599
- GCC_except_table602
- GCC_except_table604
- GCC_except_table608
- GCC_except_table610
- GCC_except_table612
- GCC_except_table615
- GCC_except_table616
- GCC_except_table618
- GCC_except_table620
- GCC_except_table623
- GCC_except_table626
- GCC_except_table632
- GCC_except_table634
- GCC_except_table635
- GCC_except_table641
- GCC_except_table651
- GCC_except_table653
- GCC_except_table664
- GCC_except_table668
- GCC_except_table670
- GCC_except_table671
- GCC_except_table672
- GCC_except_table676
- GCC_except_table685
- GCC_except_table687
- GCC_except_table688
- GCC_except_table691
- GCC_except_table692
- GCC_except_table695
- GCC_except_table708
- GCC_except_table709
- GCC_except_table714
- GCC_except_table715
- GCC_except_table725
- GCC_except_table731
- GCC_except_table733
- GCC_except_table739
- GCC_except_table740
- GCC_except_table743
- GCC_except_table744
- GCC_except_table749
- GCC_except_table753
- GCC_except_table755
- GCC_except_table760
- GCC_except_table761
- GCC_except_table763
- GCC_except_table768
- GCC_except_table771
- GCC_except_table775
- GCC_except_table778
- GCC_except_table779
- GCC_except_table783
- GCC_except_table784
- GCC_except_table788
- GCC_except_table790
- GCC_except_table794
- GCC_except_table799
- GCC_except_table802
- GCC_except_table805
- GCC_except_table818
- GCC_except_table821
- GCC_except_table824
- GCC_except_table829
- GCC_except_table838
- GCC_except_table840
- GCC_except_table842
- GCC_except_table847
- GCC_except_table849
- GCC_except_table855
- GCC_except_table871
- GCC_except_table874
- GCC_except_table877
- GCC_except_table889
- GCC_except_table891
- GCC_except_table894
- GCC_except_table914
- GCC_except_table918
- GCC_except_table920
- GCC_except_table922
- GCC_except_table924
- GCC_except_table928
- GCC_except_table936
- GCC_except_table940
- GCC_except_table944
- GCC_except_table948
- GCC_except_table951
- GCC_except_table963
- GCC_except_table965
- GCC_except_table970
- GCC_except_table975
- GCC_except_table978
- GCC_except_table986
- GCC_except_table987
- __OBJC_$_CLASS_METHODS_AVPlayerItem(AVPlayerItemCustomMediaSelectionScheme|AVPlayerItemCustomMediaSelectionScheme_Private|AVPlayerItemProtectedContent|AVPlayerItemProtectedContentPrivate|AVPlayerItemLogging|AVPlayerItemOutputs|AVPlayerItemMediaDataCollectors|LegibleOutputSupport|MetadataOutputSupport|RenderedLegibleOutputSupport|SwiftMedia|AVPlayerItemAVKit|AVPlayerItemVideoEnhancement|AVPlayerInterstitialSupport|AVPlayerItemIntegratedTimelineSupport|AVPlayerItemSpeedRamp|AVPlayerItemSpeedRampInternal|AVMetricEventStreamPublisherInternal|AVPlayerItemTrackInfoCaching|fixFaultyTFDT165791136)
- __OBJC_$_CLASS_METHODS_AVURLAsset(AVAssetCache|AVURLAssetCache_Private|AVAssetVariantInspection|AVURLAssetURLHandlingInternal|AVURLAssetURLHandling|AVMediaExtension|AVURLAssetInstanceIdentiferMapping|AVURLAssetContentKeyEligibility|AVURLAssetContentKeyEligibilityInternal|AVURLAssetCustomURLHandling|NSItemProvider|AVAssetSerializableCreationOptionsSupport|AVNSURLSessionAsset)
- __OBJC_$_INSTANCE_METHODS_AVPlayerItem(AVPlayerItemCustomMediaSelectionScheme|AVPlayerItemCustomMediaSelectionScheme_Private|AVPlayerItemProtectedContent|AVPlayerItemProtectedContentPrivate|AVPlayerItemLogging|AVPlayerItemOutputs|AVPlayerItemMediaDataCollectors|LegibleOutputSupport|MetadataOutputSupport|RenderedLegibleOutputSupport|SwiftMedia|AVPlayerItemAVKit|AVPlayerItemVideoEnhancement|AVPlayerInterstitialSupport|AVPlayerItemIntegratedTimelineSupport|AVPlayerItemSpeedRamp|AVPlayerItemSpeedRampInternal|AVMetricEventStreamPublisherInternal|AVPlayerItemTrackInfoCaching|fixFaultyTFDT165791136)
- __OBJC_$_INSTANCE_METHODS_AVURLAsset(AVAssetCache|AVURLAssetCache_Private|AVAssetVariantInspection|AVURLAssetURLHandlingInternal|AVURLAssetURLHandling|AVMediaExtension|AVURLAssetInstanceIdentiferMapping|AVURLAssetContentKeyEligibility|AVURLAssetContentKeyEligibilityInternal|AVURLAssetCustomURLHandling|NSItemProvider|AVAssetSerializableCreationOptionsSupport|AVNSURLSessionAsset)
- __OBJC_CLASS_PROTOCOLS_$_AVPlayerItem(AVPlayerItemCustomMediaSelectionScheme|AVPlayerItemCustomMediaSelectionScheme_Private|AVPlayerItemProtectedContent|AVPlayerItemProtectedContentPrivate|AVPlayerItemLogging|AVPlayerItemOutputs|AVPlayerItemMediaDataCollectors|LegibleOutputSupport|MetadataOutputSupport|RenderedLegibleOutputSupport|SwiftMedia|AVPlayerItemAVKit|AVPlayerItemVideoEnhancement|AVPlayerInterstitialSupport|AVPlayerItemIntegratedTimelineSupport|AVPlayerItemSpeedRamp|AVPlayerItemSpeedRampInternal|AVMetricEventStreamPublisherInternal|AVPlayerItemTrackInfoCaching|fixFaultyTFDT165791136)
- __OBJC_CLASS_PROTOCOLS_$_AVURLAsset(AVAssetCache|AVURLAssetCache_Private|AVAssetVariantInspection|AVURLAssetURLHandlingInternal|AVURLAssetURLHandling|AVMediaExtension|AVURLAssetInstanceIdentiferMapping|AVURLAssetContentKeyEligibility|AVURLAssetContentKeyEligibilityInternal|AVURLAssetCustomURLHandling|NSItemProvider|AVAssetSerializableCreationOptionsSupport|AVNSURLSessionAsset)
- ___24-[AVPlayerItem audioMix]_block_invoke
- ___28-[AVPlayerItem loudnessInfo]_block_invoke
- ___28-[AVPlayerItem setAudioMix:]_block_invoke
- ___28-[AVPlayerItem setAudioMix:]_block_invoke_2
- ___32-[AVPlayerItem setLoudnessInfo:]_block_invoke
- ___33-[AVPlayerItem audioTapProcessor]_block_invoke
- ___39-[AVPlayerItem audioTimePitchAlgorithm]_block_invoke
- ___39-[AVPlayerItem resetAudioBufferedAhead]_block_invoke
- ___43-[AVPlayerItem setAudioTimePitchAlgorithm:]_block_invoke
- ___43-[AVPlayerItem suppressesAudioOnlyVariants]_block_invoke
- ___44-[AVPlayerItem isAudioSpatializationAllowed]_block_invoke
- ___46-[AVPlayerItem setAudioSpatializationAllowed:]_block_invoke
- ___47-[AVPlayerItem setSuppressesAudioOnlyVariants:]_block_invoke
- ___47-[AVPlayerItem setSuppressesAudioOnlyVariants:]_block_invoke_2
- ___49-[AVPlayerItem allowedAudioSpatializationFormats]_block_invoke
- ___53-[AVPlayerItem setAllowedAudioSpatializationFormats:]_block_invoke
- _kFigPlaybackItemProperty_SuppressesAudioOnlyVariants
CStrings:
+ "Advertisement"
+ "QTContentTypeForLoudnessControlAlarm"
+ "QTContentTypeForLoudnessControlAudiobookPodcastOrRadioProgram"
+ "QTContentTypeForLoudnessControlDeviceCaptureOrUserGenerated"
+ "QTContentTypeForLoudnessControlLiveAudiovisualProduction"
+ "QTContentTypeForLoudnessControlMusic"
+ "QTContentTypeForLoudnessControlOnDemandAudiovisualProduction"
+ "QTContentTypeForLoudnessControlOtherSystemSound"
+ "QTContentTypeForLoudnessControlRingtone"
+ "QTContentTypeForLoudnessControlSynthesizedSpeech"
+ "QTContentTypeForLoudnessControlUserInterfaceFeedback"
+ "UseItemMeasurement"
+ "UseSequenceMeasurement"
+ "appliesLoudnessAdjustmentsAutomatically"
+ "com.apple.avfoundation.avurlasset.setupconnectioncompletion"
+ "udta/ctlc"
+ "udta/ludt"
+ "uiso/ctlc"
+ "uiso/ludt"
- "<<<< AVSampleBufferVideoRenderer >>>> %s: <%{public}@|%p> Waking a suspended Swift enqueue because a flush is now required"
```
