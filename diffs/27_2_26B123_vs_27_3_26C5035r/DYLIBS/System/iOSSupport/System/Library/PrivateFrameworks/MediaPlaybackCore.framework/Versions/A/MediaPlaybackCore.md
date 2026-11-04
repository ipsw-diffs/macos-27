## MediaPlaybackCore

> `/System/iOSSupport/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/Versions/A/MediaPlaybackCore`

```diff

-26240.26.40.301.0
-  __TEXT.__text: 0x446438
-  __TEXT.__objc_methlist: 0x17660
+26300.26.43.301.0
+  __TEXT.__text: 0x45dd40
+  __TEXT.__objc_methlist: 0x177b8
   __TEXT.__dlopen_cstrs: 0xbe
-  __TEXT.__const: 0xfb60
-  __TEXT.__cstring: 0x24b22
-  __TEXT.__constg_swiftt: 0x78bc
-  __TEXT.__swift5_typeref: 0x5162
+  __TEXT.__const: 0x10020
+  __TEXT.__cstring: 0x24e25
+  __TEXT.__constg_swiftt: 0x7b44
+  __TEXT.__swift5_typeref: 0x534a
   __TEXT.__swift5_builtin: 0x67c
-  __TEXT.__swift5_reflstr: 0x57e2
-  __TEXT.__swift5_fieldmd: 0x5310
+  __TEXT.__swift5_reflstr: 0x59f2
+  __TEXT.__swift5_fieldmd: 0x55a0
   __TEXT.__swift5_assocty: 0xb58
-  __TEXT.__oslogstring: 0x490ba
-  __TEXT.__swift5_proto: 0x8c0
-  __TEXT.__swift5_types: 0x518
-  __TEXT.__swift5_capture: 0x86fc
-  __TEXT.__swift_as_entry: 0x4a0
-  __TEXT.__swift_as_ret: 0x5b4
-  __TEXT.__swift_as_cont: 0xddc
+  __TEXT.__oslogstring: 0x4a193
+  __TEXT.__swift5_proto: 0x8d8
+  __TEXT.__swift5_types: 0x534
+  __TEXT.__swift5_capture: 0x8aec
+  __TEXT.__swift_as_entry: 0x4e0
+  __TEXT.__swift_as_ret: 0x5f4
+  __TEXT.__swift_as_cont: 0xe98
   __TEXT.__swift5_mpenum: 0xf8
-  __TEXT.__swift5_protos: 0xd8
+  __TEXT.__swift5_protos: 0xe8
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x5738
+  __TEXT.__gcc_except_tab: 0x577c
   __TEXT.__ustring: 0x4dc
-  __TEXT.__unwind_info: 0xfc40
-  __TEXT.__eh_frame: 0xfbac
+  __TEXT.__unwind_info: 0x10650
+  __TEXT.__eh_frame: 0x1095c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x8fc8
-  __DATA_CONST.__objc_classlist: 0xce8
+  __DATA_CONST.__const: 0x9110
+  __DATA_CONST.__objc_classlist: 0xd00
   __DATA_CONST.__objc_catlist: 0x280
   __DATA_CONST.__objc_protolist: 0x7a0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc680
+  __DATA_CONST.__objc_selrefs: 0xc750
   __DATA_CONST.__objc_protorefs: 0x380
   __DATA_CONST.__objc_superrefs: 0x6c0
   __DATA_CONST.__objc_arraydata: 0x288
-  __DATA_CONST.__got: 0x3130
-  __AUTH_CONST.__const: 0x1ca50
-  __AUTH_CONST.__cfstring: 0x1e600
-  __AUTH_CONST.__objc_const: 0x33580
-  __AUTH_CONST.__objc_intobj: 0x8a0
-  __AUTH_CONST.__objc_arrayobj: 0x270
+  __DATA_CONST.__got: 0x31b8
+  __AUTH_CONST.__const: 0x1d5c8
+  __AUTH_CONST.__cfstring: 0x1e860
+  __AUTH_CONST.__objc_const: 0x33d18
+  __AUTH_CONST.__objc_intobj: 0x8b8
+  __AUTH_CONST.__objc_arrayobj: 0x258
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x50
-  __AUTH_CONST.__auth_got: 0x3338
-  __AUTH.__objc_data: 0x53c8
-  __AUTH.__data: 0x2a90
-  __DATA.__objc_ivar: 0x1a74
-  __DATA.__data: 0x66e8
-  __DATA.__bss: 0xde38
-  __DATA.__common: 0x1f8
-  __DATA_DIRTY.__objc_data: 0x3908
+  __AUTH_CONST.__auth_got: 0x3408
+  __AUTH.__objc_data: 0x5520
+  __AUTH.__data: 0x2d20
+  __DATA.__objc_ivar: 0x1a98
+  __DATA.__data: 0x6888
+  __DATA.__bss: 0xdf48
+  __DATA.__common: 0x240
+  __DATA_DIRTY.__objc_data: 0x3948
   __DATA_DIRTY.__data: 0x5d90
   __DATA_DIRTY.__bss: 0x1b28
   __DATA_DIRTY.__common: 0xf0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 22786
-  Symbols:   23437
-  CStrings:  7985
+  Functions: 23271
+  Symbols:   23564
+  CStrings:  8065
 
Symbols:
+ +[MPCPlaybackPerformanceController supportsAssetConnectionPrewarming]
+ -[MPCModelGenericAVItem _computeNormalizedGainFromPlayerItem:reason:]
+ -[MPCModelGenericAVItem cachedTimebase]
+ -[MPCModelGenericAVItem normalizedGain]
+ -[MPCModelGenericAVItem setCachedTimebase:]
+ -[MPCModelGenericAVItem setNormalizedGain:]
+ -[MPCPlayPerfMetrics set_tokenMintWaitTime:]
+ -[MPCPlayPerfMetrics tokenMintWaitTime]
+ -[MPCPlaybackAccountManager _defaultMediaUserChangedNotification:]
+ -[MPCPlaybackEngine assetTokenManager]
+ -[MPCPlaybackEngine audioTapDelegate]
+ -[MPCPlaybackEngine setAudioTapDelegate:]
+ -[MPCPlaybackPerformanceController prewarmFrequentHLSConnections]
+ -[MPCPlaybackPerformanceController recordHLSAssetURL:options:]
+ -[MPCPlayerItemConfigurator assetTokenManager]
+ -[MPCReportingLyricsViewEvent isSelfieSingShare]
+ -[MPCReportingLyricsViewEvent setSelfieSingShare:]
+ -[MPCSingleTrackAudioProcessor currentContentItemID]
+ -[MPCSingleTrackAudioProcessor setCurrentContentItemID:]
+ GCC_except_table1000
+ GCC_except_table1003
+ GCC_except_table1196
+ GCC_except_table1198
+ GCC_except_table1368
+ GCC_except_table1370
+ GCC_except_table1411
+ GCC_except_table1422
+ GCC_except_table1429
+ GCC_except_table1436
+ GCC_except_table1473
+ GCC_except_table1494
+ GCC_except_table1537
+ GCC_except_table1710
+ GCC_except_table1712
+ GCC_except_table1725
+ GCC_except_table1730
+ GCC_except_table1800
+ GCC_except_table1884
+ GCC_except_table1885
+ GCC_except_table1993
+ GCC_except_table2013
+ GCC_except_table2015
+ GCC_except_table2052
+ GCC_except_table2057
+ GCC_except_table2059
+ GCC_except_table2062
+ GCC_except_table2073
+ GCC_except_table2083
+ GCC_except_table2198
+ GCC_except_table2249
+ GCC_except_table2253
+ GCC_except_table2256
+ GCC_except_table2282
+ GCC_except_table2306
+ GCC_except_table2338
+ GCC_except_table2579
+ GCC_except_table2607
+ GCC_except_table2634
+ GCC_except_table2779
+ GCC_except_table2800
+ GCC_except_table2807
+ GCC_except_table2808
+ GCC_except_table2833
+ GCC_except_table2840
+ GCC_except_table2846
+ GCC_except_table2848
+ GCC_except_table2850
+ GCC_except_table2853
+ GCC_except_table2888
+ GCC_except_table2893
+ GCC_except_table2899
+ GCC_except_table2905
+ GCC_except_table2910
+ GCC_except_table2913
+ GCC_except_table2916
+ GCC_except_table2936
+ GCC_except_table2986
+ GCC_except_table3076
+ GCC_except_table3080
+ GCC_except_table3091
+ GCC_except_table3092
+ GCC_except_table3116
+ GCC_except_table3124
+ GCC_except_table3166
+ GCC_except_table3167
+ GCC_except_table3174
+ GCC_except_table3231
+ GCC_except_table3248
+ GCC_except_table3249
+ GCC_except_table3259
+ GCC_except_table3301
+ GCC_except_table3303
+ GCC_except_table3321
+ GCC_except_table3325
+ GCC_except_table3369
+ GCC_except_table3414
+ GCC_except_table3419
+ GCC_except_table3540
+ GCC_except_table3561
+ GCC_except_table3568
+ GCC_except_table3593
+ GCC_except_table3597
+ GCC_except_table3607
+ GCC_except_table3664
+ GCC_except_table3669
+ GCC_except_table3673
+ GCC_except_table3741
+ GCC_except_table3838
+ GCC_except_table3842
+ GCC_except_table3853
+ GCC_except_table3869
+ GCC_except_table3875
+ GCC_except_table3885
+ GCC_except_table4013
+ GCC_except_table4059
+ GCC_except_table4060
+ GCC_except_table4061
+ GCC_except_table4080
+ GCC_except_table4091
+ GCC_except_table4110
+ GCC_except_table4115
+ GCC_except_table4117
+ GCC_except_table4131
+ GCC_except_table4154
+ GCC_except_table4165
+ GCC_except_table4254
+ GCC_except_table4273
+ GCC_except_table4286
+ GCC_except_table4297
+ GCC_except_table4328
+ GCC_except_table4499
+ GCC_except_table4500
+ GCC_except_table4677
+ GCC_except_table4712
+ GCC_except_table4714
+ GCC_except_table4722
+ GCC_except_table4745
+ GCC_except_table4753
+ GCC_except_table4761
+ GCC_except_table4771
+ GCC_except_table4784
+ GCC_except_table4828
+ GCC_except_table4842
+ GCC_except_table4858
+ GCC_except_table4861
+ GCC_except_table4867
+ GCC_except_table4914
+ GCC_except_table4951
+ GCC_except_table5037
+ GCC_except_table506
+ GCC_except_table523
+ GCC_except_table5365
+ GCC_except_table5366
+ GCC_except_table540
+ GCC_except_table5441
+ GCC_except_table5538
+ GCC_except_table5688
+ GCC_except_table5713
+ GCC_except_table5882
+ GCC_except_table5947
+ GCC_except_table5972
+ GCC_except_table6007
+ GCC_except_table6010
+ GCC_except_table6013
+ GCC_except_table6099
+ GCC_except_table6316
+ GCC_except_table6333
+ GCC_except_table6804
+ GCC_except_table7144
+ GCC_except_table7159
+ GCC_except_table7250
+ GCC_except_table7259
+ GCC_except_table7348
+ GCC_except_table7355
+ GCC_except_table7373
+ GCC_except_table7424
+ GCC_except_table7425
+ GCC_except_table7433
+ GCC_except_table7449
+ GCC_except_table791
+ GCC_except_table847
+ GCC_except_table927
+ GCC_except_table961
+ GCC_except_table968
+ GCC_except_table970
+ GCC_except_table983
+ GCC_except_table987
+ GCC_except_table993
+ GCC_except_table997
+ _AVPlayerInterstitialEventMonitorCurrentEventDidChangeNotification
+ _AVPlayerInterstitialEventMonitorEventsDidChangeNotification
+ _AudioFormatGetProperty
+ _ICUserProfileStoreDefaultMediaUserDidChangeNotification
+ _MPCPlaybackEngineEventAssetTokenSourceCached
+ _MPCPlaybackEngineEventAssetTokenSourceMinted
+ _MPCPlaybackEngineEventAssetTokenSourceResumeRefresh
+ _MPCPlaybackEngineEventAssetTokenSourceScheduledRefresh
+ _MPCPlaybackEngineEventAssetTokenSourceSeekRefresh
+ _MPCPlaybackEngineEventItemMetadataKeyRequiresAssetToken
+ _MPCPlaybackEngineEventPayloadKeyAssetTokenDurationSeconds
+ _MPCPlaybackEngineEventPayloadKeyAssetTokenError
+ _MPCPlaybackEngineEventPayloadKeyAssetTokenExpiration
+ _MPCPlaybackEngineEventPayloadKeyAssetTokenRefreshAttempt
+ _MPCPlaybackEngineEventPayloadKeyAssetTokenSource
+ _MPCPlaybackEngineEventPayloadKeyAssetTokenTTLSeconds
+ _MPCPlaybackEngineEventPayloadKeyInterstitialDuration
+ _MPCPlaybackEngineEventTypeAssetTokenAcquired
+ _MPModelPropertySongVisualTraits
+ _MPNowPlayingContentItemUserInfoKeyPodcastEpisodeRequiresAssetToken
+ _OBJC_CLASS_$_AVPlayerInterstitialEventController
+ _OBJC_CLASS_$_MPCAssetTokenManager
+ _OBJC_IVAR_$_MPCModelGenericAVItem._cachedTimebase
+ _OBJC_IVAR_$_MPCModelGenericAVItem._normalizedGain
+ _OBJC_IVAR_$_MPCPlaybackEngine._assetTokenManager
+ _OBJC_IVAR_$_MPCPlaybackEngine._audioTapDelegate
+ _OBJC_IVAR_$_MPCPlaybackPerformanceController._hlsHostCounts
+ _OBJC_IVAR_$_MPCPlaybackPerformanceController._hlsPrewarmOptions
+ _OBJC_IVAR_$_MPCPlaybackPerformanceController._hlsTotalPlays
+ _OBJC_IVAR_$_MPCPlaybackPerformanceController._lastHLSConnectionActivity
+ _OBJC_IVAR_$_MPCReportingLyricsViewEvent._selfieSingShare
+ _OBJC_IVAR_$_MPCSingleTrackAudioProcessor._currentContentItemID
+ _OBJC_METACLASS_$_MPCAssetTokenManager
+ _OUTLINED_FUNCTION_473
+ __DATA_MPCAssetTokenManager
+ __DATA__TtC17MediaPlaybackCore17AssetTokenSession
+ __DATA__TtC17MediaPlaybackCore32InterstitialRestrictionOverrider
+ __IVARS_MPCAssetTokenManager
+ __IVARS__TtC17MediaPlaybackCore17AssetTokenSession
+ __IVARS__TtC17MediaPlaybackCore32InterstitialRestrictionOverrider
+ __METACLASS_DATA_MPCAssetTokenManager
+ __METACLASS_DATA__TtC17MediaPlaybackCore17AssetTokenSession
+ __METACLASS_DATA__TtC17MediaPlaybackCore32InterstitialRestrictionOverrider
+ __MPCFreeAudioBufferList
+ __OBJC_$_CLASS_METHODS_MPCAssetTokenManager(MediaPlaybackCore|MediaPlaybackCore1)
+ __OBJC_$_INSTANCE_METHODS_MPCAssetTokenManager(MediaPlaybackCore|MediaPlaybackCore1)
+ __OBJC_CLASS_PROTOCOLS_$_MPCAssetTokenManager(MediaPlaybackCore|MediaPlaybackCore1)
+ ___64-[MPCPlayPerfMetrics addAssetSelectionWithCursor:itemIDPayload:]_block_invoke_2
+ ___65-[MPCPlaybackPerformanceController prewarmFrequentHLSConnections]_block_invoke
+ ___65-[MPCPlaybackPerformanceController prewarmFrequentHLSConnections]_block_invoke_2
+ ____MPCAudioTapProcess_block_invoke
+ ___block_descriptor_32_e31_q24?0"NSNumber"8"NSNumber"16l
+ ___block_descriptor_48_e8_32bs40w_e8_v16?0q8lw40l8s32l8
+ ___block_descriptor_48_e8_32s_e18_B16?0"NSString"8ls32l8
+ ___block_descriptor_88_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___swift_closure_destructor.107Tm
+ ___swift_closure_destructor.113Tm
+ ___swift_closure_destructor.226Tm
+ ___swift_closure_destructor.28Tm
+ ___swift_closure_destructor.499Tm
+ ___swift_closure_destructor.608Tm
+ ___swift_closure_destructor.97Tm
+ ___swift_memcpy41_8
+ ___unnamed_11
+ _associated conformance 17MediaPlaybackCore17AssetTokenManagerC18InvalidationReasonOSHAASQ
+ _bzero
+ _get_enum_tag_for_layout_string 17MediaPlaybackCore17PodcastsPlayEvent33_9E2A88F7161E17A7C0D0C9ACE6FC197BLLV14AssetPlacementO
+ _objc_getProperty
+ _objc_msgSend$_computeNormalizedGainFromPlayerItem:reason:
+ _objc_msgSend$assetTokenManager
+ _objc_msgSend$audioTapDelegate
+ _objc_msgSend$cachedTimebase
+ _objc_msgSend$currentContentItemID
+ _objc_msgSend$currentEvent
+ _objc_msgSend$effectiveLoudnessInfo
+ _objc_msgSend$engine:didRenderAudioBuffer:itemTime:itemTimebase:numberOfFrames:sampleRate:normalizedGain:
+ _objc_msgSend$errorStatusCode
+ _objc_msgSend$initWithEngine:
+ _objc_msgSend$invalidateAll
+ _objc_msgSend$isSelfieSingShare
+ _objc_msgSend$keysSortedByValueUsingComparator:
+ _objc_msgSend$normalizedGain
+ _objc_msgSend$podcastRequiresAssetToken
+ _objc_msgSend$prewarmFrequentHLSConnections
+ _objc_msgSend$primaryItem
+ _objc_msgSend$recordHLSAssetURL:options:
+ _objc_msgSend$requiresAssetToken
+ _objc_msgSend$restrictions
+ _objc_msgSend$setAssetTokenManager:
+ _objc_msgSend$setCachedTimebase:
+ _objc_msgSend$setCurrentContentItemID:
+ _objc_msgSend$setEvents:
+ _objc_msgSend$setNormalizedGain:
+ _objc_msgSend$setRestrictions:
+ _objc_msgSend$set_tokenMintWaitTime:
+ _objc_msgSend$supportsAssetConnectionPrewarming
+ _objc_msgSend$tokenMintWaitTime
+ _objc_setProperty_atomic_copy
+ _symbolic $s17MediaPlaybackCore15AssetTokenClockP
+ _symbolic $s17MediaPlaybackCore20AssetTokenRequestingP
+ _symbolic $s17MediaPlaybackCore21AssetTokenManagerHostP
+ _symbolic $s17MediaPlaybackCore25AssetTokenSessionReporterP
+ _symbolic SDySS_____G 17MediaPlaybackCore17AssetTokenSessionC
+ _symbolic SDy__________G 18PodcastsFoundation17AssetTokenRequestV 17MediaPlaybackCore06CachedD0V
+ _symbolic SSSg2id_SdSg13startPositionAC8durationt
+ _symbolic ScTy___________pGSg 18PodcastsFoundation10AssetTokenV s5ErrorP
+ _symbolic So35AVPlayerInterstitialEventControllerC
+ _symbolic _____ 17MediaPlaybackCore11CachedTokenV
+ _symbolic _____ 17MediaPlaybackCore11SystemClockV
+ _symbolic _____ 17MediaPlaybackCore17AssetTokenManagerC
+ _symbolic _____ 17MediaPlaybackCore17AssetTokenManagerC18InvalidationReasonO
+ _symbolic _____ 17MediaPlaybackCore17AssetTokenSessionC
+ _symbolic _____ 17MediaPlaybackCore17PodcastsPlayEvent33_9E2A88F7161E17A7C0D0C9ACE6FC197BLLV14AssetPlacementO
+ _symbolic _____ 17MediaPlaybackCore32InterstitialRestrictionOverriderC
+ _symbolic _____ 18PodcastsFoundation10AssetTokenV
+ _symbolic _____ 18PodcastsFoundation17AssetTokenRequestV
+ _symbolic _____ 18PodcastsFoundation23AssetTokenRefreshPolicyV
+ _symbolic _____Sg 17MediaPlaybackCore32InterstitialRestrictionOverriderC
+ _symbolic _____Sg 18PodcastsFoundation10AssetTokenV
+ _symbolic _____SgXw 17MediaPlaybackCore17AssetTokenManagerC
+ _symbolic _____SgXw 17MediaPlaybackCore17AssetTokenSessionC
+ _symbolic _____SgXw 17MediaPlaybackCore32InterstitialRestrictionOverriderC
+ _symbolic _____SgXwz_Xx 17MediaPlaybackCore17AssetTokenManagerC
+ _symbolic _____SgXwz_Xx 17MediaPlaybackCore17AssetTokenSessionC
+ _symbolic ______p 17MediaPlaybackCore15AssetTokenClockP
+ _symbolic ______p 18PodcastsFoundation18AssetTokenProviderP
+ _symbolic ______pSgXw 17MediaPlaybackCore21AssetTokenManagerHostP
+ _symbolic ______pSgXw 17MediaPlaybackCore25AssetTokenSessionReporterP
+ _type_layout_string 17MediaPlaybackCore17PodcastsPlayEvent33_9E2A88F7161E17A7C0D0C9ACE6FC197BLLV14AssetPlacementO
- -[MPCPlaybackPerformanceController lastCDNWarming]
- -[MPCPlaybackPerformanceController loadAVAssetWithURL:]
- -[MPCPlaybackPerformanceController markCDNConnectionWarmed]
- -[MPCPlaybackPerformanceController setLastCDNWarming:]
- -[MPCPlaybackPerformanceController warmCDNConnection]
- GCC_except_table1185
- GCC_except_table1189
- GCC_except_table1359
- GCC_except_table1361
- GCC_except_table1402
- GCC_except_table1413
- GCC_except_table1420
- GCC_except_table1427
- GCC_except_table1464
- GCC_except_table1476
- GCC_except_table1528
- GCC_except_table1701
- GCC_except_table1703
- GCC_except_table1716
- GCC_except_table1721
- GCC_except_table1791
- GCC_except_table1875
- GCC_except_table1876
- GCC_except_table1984
- GCC_except_table2004
- GCC_except_table2006
- GCC_except_table2034
- GCC_except_table2048
- GCC_except_table2050
- GCC_except_table2053
- GCC_except_table2064
- GCC_except_table2074
- GCC_except_table2189
- GCC_except_table2240
- GCC_except_table2244
- GCC_except_table2247
- GCC_except_table2273
- GCC_except_table2297
- GCC_except_table2329
- GCC_except_table2570
- GCC_except_table2598
- GCC_except_table2625
- GCC_except_table2770
- GCC_except_table2791
- GCC_except_table2798
- GCC_except_table2799
- GCC_except_table2824
- GCC_except_table2826
- GCC_except_table2831
- GCC_except_table2837
- GCC_except_table2839
- GCC_except_table2841
- GCC_except_table2870
- GCC_except_table2884
- GCC_except_table2886
- GCC_except_table2890
- GCC_except_table2896
- GCC_except_table2901
- GCC_except_table2907
- GCC_except_table2927
- GCC_except_table2977
- GCC_except_table3063
- GCC_except_table3067
- GCC_except_table3078
- GCC_except_table3079
- GCC_except_table3103
- GCC_except_table3111
- GCC_except_table3152
- GCC_except_table3153
- GCC_except_table3160
- GCC_except_table3217
- GCC_except_table3235
- GCC_except_table3244
- GCC_except_table3286
- GCC_except_table3288
- GCC_except_table3295
- GCC_except_table3306
- GCC_except_table3354
- GCC_except_table3399
- GCC_except_table3404
- GCC_except_table3525
- GCC_except_table3546
- GCC_except_table3553
- GCC_except_table3578
- GCC_except_table3582
- GCC_except_table3592
- GCC_except_table3649
- GCC_except_table3654
- GCC_except_table3658
- GCC_except_table3727
- GCC_except_table3824
- GCC_except_table3828
- GCC_except_table3839
- GCC_except_table3855
- GCC_except_table3861
- GCC_except_table3871
- GCC_except_table3999
- GCC_except_table4045
- GCC_except_table4046
- GCC_except_table4047
- GCC_except_table4066
- GCC_except_table4077
- GCC_except_table4095
- GCC_except_table4100
- GCC_except_table4102
- GCC_except_table4116
- GCC_except_table4139
- GCC_except_table4150
- GCC_except_table4239
- GCC_except_table4258
- GCC_except_table4271
- GCC_except_table4282
- GCC_except_table4313
- GCC_except_table4484
- GCC_except_table4485
- GCC_except_table4662
- GCC_except_table4697
- GCC_except_table4699
- GCC_except_table4707
- GCC_except_table4715
- GCC_except_table4738
- GCC_except_table4746
- GCC_except_table4756
- GCC_except_table4769
- GCC_except_table4813
- GCC_except_table4827
- GCC_except_table4843
- GCC_except_table4846
- GCC_except_table4852
- GCC_except_table4899
- GCC_except_table4936
- GCC_except_table5022
- GCC_except_table505
- GCC_except_table521
- GCC_except_table5348
- GCC_except_table5349
- GCC_except_table538
- GCC_except_table5421
- GCC_except_table5517
- GCC_except_table5667
- GCC_except_table5692
- GCC_except_table5861
- GCC_except_table5926
- GCC_except_table5951
- GCC_except_table5986
- GCC_except_table5989
- GCC_except_table5992
- GCC_except_table6078
- GCC_except_table6295
- GCC_except_table6312
- GCC_except_table6783
- GCC_except_table7123
- GCC_except_table7138
- GCC_except_table7229
- GCC_except_table7238
- GCC_except_table7327
- GCC_except_table7334
- GCC_except_table7352
- GCC_except_table7403
- GCC_except_table7404
- GCC_except_table7407
- GCC_except_table7412
- GCC_except_table790
- GCC_except_table846
- GCC_except_table922
- GCC_except_table953
- GCC_except_table956
- GCC_except_table965
- GCC_except_table978
- GCC_except_table982
- GCC_except_table988
- GCC_except_table992
- GCC_except_table995
- GCC_except_table998
- _OBJC_IVAR_$_MPCPlaybackPerformanceController._lastCDNWarming
- ___55-[MPCPlaybackPerformanceController loadAVAssetWithURL:]_block_invoke
- ___swift_closure_destructor.106Tm
- ___swift_closure_destructor.112Tm
- ___swift_closure_destructor.225Tm
- ___swift_closure_destructor.22Tm
- ___swift_closure_destructor.498Tm
- ___swift_closure_destructor.607Tm
- ___swift_closure_destructor.96Tm
- ___unnamed_10
- _objc_msgSend$lastCDNWarming
- _objc_msgSend$loadAVAssetWithURL:
- _objc_msgSend$markCDNConnectionWarmed
- _objc_msgSend$setLastCDNWarming:
- _objc_msgSend$stringForFactor:
- _objc_msgSend$warmCDNConnection
- _symbolic ySSc
CStrings:
+ "Acquiring token, contentItemID=%{public}s"
+ "Active account changed, dropping %ld cached token(s)"
+ "Already paused, ignoring"
+ "Asset Token Refresh"
+ "Asset needs no FairPlay key session, using url: %{private}s"
+ "Asset token refresh"
+ "AssetTokenRefresh"
+ "HTTP %ld on CAT-protected stream for episode=%{private,mask.hash}s. Clearing CAT state to retry with a fresh token."
+ "Invalidating manager, %ld session(s)"
+ "Invalidating session, hadTimer=%{bool,public}d hadToken=%{bool,public}d contentItemID=%{public}s"
+ "Invalidating session, reason=%{public}s contentItemID=%{public}s"
+ "Joining pending fetch, contentItemID=%{public}s"
+ "MPCAssetTokenManager"
+ "MPCPlaybackPerformanceHLSHostCounts"
+ "MPCPlaybackPerformanceHLSPrewarmOptions"
+ "MPCPlaybackPerformanceHLSTotalPlays"
+ "MediaPlaybackCore.AssetTokenManager"
+ "Mint failed offline for downloaded item=%{private,mask.hash}s error=%{public}s; falling back to the download."
+ "No AssetTokenManager set on item=%{private,mask.hash}s; cannot acquire token"
+ "Offline; playing the download for item=%{private,mask.hash}s"
+ "Pausing"
+ "Pausing session, cancelling timer, contentItemID=%{public}s"
+ "PodcastsAssetToken"
+ "Position jumped, contentItemID=%{public}s"
+ "Pre-fetch cancelled, contentItemID=%{public}s"
+ "Pre-fetch failed, contentItemID=%{public}s error=%{public}s"
+ "Pre-fetching token, contentItemID=%{public}s"
+ "Prefetch failed, contentItemID=%{public}s error=%{public}s"
+ "Prefetching token for next item, contentItemID=%{public}s"
+ "Q\xf0\x91"
+ "Rate changed, rate=%{public}f contentItemID=%{public}s"
+ "Refresh already in flight, coalescing, contentItemID=%{public}s"
+ "Refresh skipped, host gone, contentItemID=%{public}s"
+ "Refresh skipped, item mismatch: current=%{public}s session=%{public}s"
+ "Refresh skipped, no cached token, contentItemID=%{public}s"
+ "Refreshing on resume, contentItemID=%{public}s"
+ "Refreshing on seek, contentItemID=%{public}s"
+ "Resume ignored, no cached token, contentItemID=%{public}s"
+ "Resume ignored, no session, contentItemID=%{public}s"
+ "Resume ignored, not paused, contentItemID=%{public}s"
+ "Returning cached token, contentItemID=%{public}s"
+ "SEED"
+ "Scheduling refresh in %lds, contentItemID=%{public}s"
+ "Scheduling refresh timer on resume, contentItemID=%{public}s"
+ "Skipping prewarm; deferring asset load until activation."
+ "Skipping refresh, token outlives playback, contentItemID=%{public}s"
+ "Skipping teardown invalidate, item still current, contentItemID=%{public}s"
+ "TokenMint"
+ "[%{public}@]-[LeaseRatePreparation] - %{public}@: Not waiting for key renewals [downloaded asset]"
+ "[%{public}@]-[SelfieSing] - %{public}@ - normalizedGain changed from %f to %f. Update reason=%{public}@, track=%{public}@"
+ "[LeaseRatePreparation] - %{public}@: Stopped waiting for key renewals [timeout] reason=%ld"
+ "[PL:%{public}s] PLAYER CONTROLLER: An interstitial event could not be carried over, so the provider's schedule is left in place rather than unscheduling an ad break"
+ "[PL:%{public}s] PLAYER CONTROLLER: Dropped navigation restrictions from %{public}ld of %{public}ld interstitial events"
+ "[PL:%{public}s] PLAYER PROCESSING: InternalPlayerController - Lifted forwardBufferDuration cap on current item: %{public}@ [item became current while capped]"
+ "[PL:%{public}s] PLAYER PROCESSING: InternalPlayerController - Saving playback resume time: %{public}f [%{public}s]"
+ "[PL:%{public}s] PLAYER PROCESSING: InternalPlayerController - Seek to time completed [%{public}s] - target time:%{public}f - identifier: %{public}s"
+ "[PL:%{public}s] STACK PROCESSING: Reloading current item [%{public}s] - Asset loading is suspended %{public}s, nothing to reload"
+ "[PL:%{public}s] STACK PROCESSING: Reloading current item [%{public}s] - Lifting asset load prevention %{public}s"
+ "[SelfieSing] - %{public}@ - normalizedGain set to %.1f: AudioFormatGetProperty(ComputeLoudnessScalar) failed: %d. Update reason=%{public}@, track=%{public}@"
+ "[SelfieSing] - %{public}@ - normalizedGain set to %.1f: effectiveLoudnessInfo is nil. Update reason=%{public}@"
+ "[SelfieSing] - %{public}@ - queueItem.timebase is nil at configuration time for item: %{public}@"
+ "[SelfieSing] - audio tap callback skipped: contentItemID changed from %{public}@ to %{public}@"
+ "[SelfieSing] - audio tap callback skipped: currentItem is nil"
+ "[SelfieSing] - audio tap callback skipped: failed to copy audio buffer list"
+ "asset-token-acquired"
+ "asset-token-duration-seconds"
+ "asset-token-error"
+ "asset-token-expiration"
+ "asset-token-refresh-attempt"
+ "asset-token-source"
+ "asset-token-ttl-seconds"
+ "forwarded to incoming item "
+ "interstitial-duration"
+ "itemIsReadyToPlay"
+ "minted"
+ "playbackDidStart"
+ "playbackStartTimeOverride set on queue item "
+ "q24@?0@\"NSNumber\"8@\"NSNumber\"16"
+ "requires-asset-token"
+ "resume-refresh"
+ "scheduled-refresh"
+ "seek-refresh"
+ "selfie_sing"
+ "tokenMintWaitTime"
+ "tracksDidChange"
+ "|%{public}@ %{public}@ %2i %{public}@  │ requiresAssetToken: %{BOOL}u"
+ "|%{public}@ %{public}@ %2i %{public}@  ╰ duration: %0.2f"
+ "|%{public}@ %{public}@ %2i %{public}@  ╰ ttl: %.0fs; expires: %{public}@"
+ "|%{public}@ %{public}@ %2i %{public}@ ╲╭ source: %{public}@; attempt: %ld"
+ "\xf0\xf0\xf0\xc1"
- "Asset is STDQ, no fairplay needed, using url: %{private}s"
- "Completed warming asset CDN connection with asset: %{public}@"
- "MUSIC_PLAYBACK_PERFORMANCE_WARMING_CDN"
- "Warming asset CDN connection with URL: %@"
- "[PL:%{public}s] PLAYER PROCESSING: InternalPlayerController - Saving playback resume time: %{public}f [playbackStartTimeOverride set on queue item]"
- "[PL:%{public}s] PLAYER PROCESSING: InternalPlayerController - Seek to time completed [playbackStartTimeOverride set on queue item] - target time:%{public}f - queue item:%{public}s - identifier: %{public}s"
- "assetURL1"
- "assetURL2"
- "warmingInterval"
- "\xf0\xf0\xf0\xa1"
```
