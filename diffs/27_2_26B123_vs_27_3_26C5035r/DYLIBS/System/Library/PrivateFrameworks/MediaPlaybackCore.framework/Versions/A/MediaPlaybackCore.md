## MediaPlaybackCore

> `/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/Versions/A/MediaPlaybackCore`

```diff

-26240.26.40.301.0
-  __TEXT.__text: 0x3bca60
-  __TEXT.__objc_methlist: 0x165f8
+26300.26.43.301.0
+  __TEXT.__text: 0x3c1138
+  __TEXT.__objc_methlist: 0x166a0
   __TEXT.__dlopen_cstrs: 0xbe
-  __TEXT.__const: 0xd9b0
-  __TEXT.__cstring: 0x235c5
-  __TEXT.__constg_swiftt: 0x6668
-  __TEXT.__swift5_typeref: 0x4642
+  __TEXT.__const: 0xdaa0
+  __TEXT.__cstring: 0x23818
+  __TEXT.__constg_swiftt: 0x66a4
+  __TEXT.__swift5_typeref: 0x4684
   __TEXT.__swift5_builtin: 0x578
-  __TEXT.__swift5_reflstr: 0x4a52
-  __TEXT.__swift5_fieldmd: 0x486c
+  __TEXT.__swift5_reflstr: 0x4b32
+  __TEXT.__swift5_fieldmd: 0x48f4
   __TEXT.__swift5_assocty: 0xa20
-  __TEXT.__oslogstring: 0x421d7
+  __TEXT.__oslogstring: 0x42900
   __TEXT.__swift5_proto: 0x7a8
-  __TEXT.__swift5_types: 0x44c
-  __TEXT.__swift5_capture: 0x67e4
+  __TEXT.__swift5_types: 0x450
+  __TEXT.__swift5_capture: 0x6814
   __TEXT.__swift_as_entry: 0x2c0
   __TEXT.__swift_as_ret: 0x324
   __TEXT.__swift_as_cont: 0x8b4
   __TEXT.__swift5_mpenum: 0xf8
   __TEXT.__swift5_protos: 0xc4
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x56f0
+  __TEXT.__gcc_except_tab: 0x5734
   __TEXT.__ustring: 0x4d4
-  __TEXT.__unwind_info: 0xd410
-  __TEXT.__eh_frame: 0x9ce8
+  __TEXT.__unwind_info: 0xd4c0
+  __TEXT.__eh_frame: 0x9d08
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2c30
-  __DATA_CONST.__objc_classlist: 0xc20
+  __DATA_CONST.__const: 0x2cd8
+  __DATA_CONST.__objc_classlist: 0xc28
   __DATA_CONST.__objc_catlist: 0x280
   __DATA_CONST.__objc_protolist: 0x6c8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc000
+  __DATA_CONST.__objc_selrefs: 0xc0b0
   __DATA_CONST.__objc_protorefs: 0x2c8
   __DATA_CONST.__objc_superrefs: 0x6b8
   __DATA_CONST.__objc_arraydata: 0x288
-  __DATA_CONST.__got: 0x2a80
-  __AUTH_CONST.__const: 0x1ed00
-  __AUTH_CONST.__cfstring: 0x1e240
-  __AUTH_CONST.__objc_const: 0x30d88
-  __AUTH_CONST.__objc_intobj: 0x8a0
-  __AUTH_CONST.__objc_arrayobj: 0x270
+  __DATA_CONST.__got: 0x2ab0
+  __AUTH_CONST.__const: 0x1ee80
+  __AUTH_CONST.__cfstring: 0x1e4a0
+  __AUTH_CONST.__objc_const: 0x310f0
+  __AUTH_CONST.__objc_intobj: 0x8b8
+  __AUTH_CONST.__objc_arrayobj: 0x258
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x50
-  __AUTH_CONST.__auth_got: 0x26f8
+  __AUTH_CONST.__auth_got: 0x2718
   __AUTH.__objc_data: 0x4808
-  __AUTH.__data: 0x1f10
-  __DATA.__objc_ivar: 0x1a4c
+  __AUTH.__data: 0x1ff0
+  __DATA.__objc_ivar: 0x1a6c
   __DATA.__data: 0x56d0
-  __DATA.__bss: 0xc018
+  __DATA.__bss: 0xc028
   __DATA.__common: 0xe8
   __DATA_DIRTY.__objc_data: 0x3100
   __DATA_DIRTY.__data: 0x5c18

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 19265
-  Symbols:   22601
-  CStrings:  7600
+  Functions: 19328
+  Symbols:   22677
+  CStrings:  7642
 
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
+ -[MPCPlaybackEngine audioTapDelegate]
+ -[MPCPlaybackEngine setAudioTapDelegate:]
+ -[MPCPlaybackPerformanceController prewarmFrequentHLSConnections]
+ -[MPCPlaybackPerformanceController recordHLSAssetURL:options:]
+ -[MPCReportingLyricsViewEvent isSelfieSingShare]
+ -[MPCReportingLyricsViewEvent setSelfieSingShare:]
+ -[MPCSingleTrackAudioProcessor currentContentItemID]
+ -[MPCSingleTrackAudioProcessor setCurrentContentItemID:]
+ GCC_except_table1016
+ GCC_except_table1018
+ GCC_except_table1025
+ GCC_except_table1027
+ GCC_except_table1040
+ GCC_except_table1044
+ GCC_except_table1050
+ GCC_except_table1056
+ GCC_except_table1059
+ GCC_except_table1062
+ GCC_except_table1257
+ GCC_except_table1259
+ GCC_except_table1429
+ GCC_except_table1433
+ GCC_except_table1477
+ GCC_except_table1488
+ GCC_except_table1495
+ GCC_except_table1502
+ GCC_except_table1539
+ GCC_except_table1560
+ GCC_except_table1603
+ GCC_except_table1776
+ GCC_except_table1778
+ GCC_except_table1791
+ GCC_except_table1796
+ GCC_except_table1866
+ GCC_except_table1951
+ GCC_except_table1952
+ GCC_except_table2066
+ GCC_except_table2086
+ GCC_except_table2088
+ GCC_except_table2116
+ GCC_except_table2127
+ GCC_except_table2133
+ GCC_except_table2135
+ GCC_except_table2138
+ GCC_except_table2149
+ GCC_except_table2159
+ GCC_except_table2275
+ GCC_except_table2326
+ GCC_except_table2330
+ GCC_except_table2333
+ GCC_except_table2361
+ GCC_except_table2385
+ GCC_except_table2418
+ GCC_except_table2659
+ GCC_except_table2687
+ GCC_except_table2714
+ GCC_except_table2859
+ GCC_except_table2880
+ GCC_except_table2887
+ GCC_except_table2888
+ GCC_except_table2913
+ GCC_except_table2920
+ GCC_except_table2926
+ GCC_except_table2928
+ GCC_except_table2930
+ GCC_except_table2933
+ GCC_except_table2970
+ GCC_except_table2975
+ GCC_except_table2981
+ GCC_except_table2987
+ GCC_except_table2992
+ GCC_except_table2995
+ GCC_except_table2998
+ GCC_except_table3018
+ GCC_except_table3068
+ GCC_except_table3158
+ GCC_except_table3162
+ GCC_except_table3173
+ GCC_except_table3174
+ GCC_except_table3198
+ GCC_except_table3210
+ GCC_except_table3257
+ GCC_except_table3258
+ GCC_except_table3267
+ GCC_except_table3324
+ GCC_except_table3341
+ GCC_except_table3342
+ GCC_except_table3352
+ GCC_except_table3393
+ GCC_except_table3397
+ GCC_except_table3418
+ GCC_except_table3422
+ GCC_except_table3472
+ GCC_except_table3517
+ GCC_except_table3522
+ GCC_except_table3642
+ GCC_except_table3663
+ GCC_except_table3670
+ GCC_except_table3697
+ GCC_except_table3701
+ GCC_except_table3711
+ GCC_except_table3768
+ GCC_except_table3775
+ GCC_except_table3779
+ GCC_except_table3849
+ GCC_except_table3952
+ GCC_except_table3956
+ GCC_except_table3968
+ GCC_except_table3984
+ GCC_except_table3991
+ GCC_except_table4001
+ GCC_except_table4129
+ GCC_except_table4175
+ GCC_except_table4176
+ GCC_except_table4177
+ GCC_except_table4196
+ GCC_except_table4207
+ GCC_except_table4225
+ GCC_except_table4230
+ GCC_except_table4232
+ GCC_except_table4268
+ GCC_except_table4280
+ GCC_except_table4369
+ GCC_except_table4388
+ GCC_except_table4403
+ GCC_except_table4412
+ GCC_except_table4443
+ GCC_except_table4614
+ GCC_except_table4615
+ GCC_except_table4794
+ GCC_except_table4829
+ GCC_except_table4831
+ GCC_except_table4839
+ GCC_except_table4847
+ GCC_except_table4863
+ GCC_except_table4875
+ GCC_except_table4885
+ GCC_except_table4896
+ GCC_except_table4909
+ GCC_except_table4970
+ GCC_except_table4987
+ GCC_except_table4992
+ GCC_except_table4998
+ GCC_except_table5043
+ GCC_except_table5078
+ GCC_except_table5162
+ GCC_except_table5523
+ GCC_except_table560
+ GCC_except_table5626
+ GCC_except_table577
+ GCC_except_table5776
+ GCC_except_table5801
+ GCC_except_table594
+ GCC_except_table5973
+ GCC_except_table6039
+ GCC_except_table6064
+ GCC_except_table6099
+ GCC_except_table6102
+ GCC_except_table6105
+ GCC_except_table6191
+ GCC_except_table6408
+ GCC_except_table6425
+ GCC_except_table6876
+ GCC_except_table7220
+ GCC_except_table7235
+ GCC_except_table7326
+ GCC_except_table7335
+ GCC_except_table7424
+ GCC_except_table7431
+ GCC_except_table7449
+ GCC_except_table7500
+ GCC_except_table7501
+ GCC_except_table7504
+ GCC_except_table7509
+ GCC_except_table7525
+ GCC_except_table845
+ GCC_except_table901
+ GCC_except_table981
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
+ _OBJC_CLASS_$_AVPlayerInterstitialEventController
+ _OBJC_IVAR_$_MPCModelGenericAVItem._cachedTimebase
+ _OBJC_IVAR_$_MPCModelGenericAVItem._normalizedGain
+ _OBJC_IVAR_$_MPCPlaybackEngine._audioTapDelegate
+ _OBJC_IVAR_$_MPCPlaybackPerformanceController._hlsHostCounts
+ _OBJC_IVAR_$_MPCPlaybackPerformanceController._hlsPrewarmOptions
+ _OBJC_IVAR_$_MPCPlaybackPerformanceController._hlsTotalPlays
+ _OBJC_IVAR_$_MPCPlaybackPerformanceController._lastHLSConnectionActivity
+ _OBJC_IVAR_$_MPCReportingLyricsViewEvent._selfieSingShare
+ _OBJC_IVAR_$_MPCSingleTrackAudioProcessor._currentContentItemID
+ __DATA__TtC17MediaPlaybackCore32InterstitialRestrictionOverrider
+ __IVARS__TtC17MediaPlaybackCore32InterstitialRestrictionOverrider
+ __METACLASS_DATA__TtC17MediaPlaybackCore32InterstitialRestrictionOverrider
+ __MPCFreeAudioBufferList
+ ___64-[MPCPlayPerfMetrics addAssetSelectionWithCursor:itemIDPayload:]_block_invoke_2
+ ___65-[MPCPlaybackPerformanceController prewarmFrequentHLSConnections]_block_invoke
+ ___65-[MPCPlaybackPerformanceController prewarmFrequentHLSConnections]_block_invoke_2
+ ____MPCAudioTapProcess_block_invoke
+ ___block_descriptor_32_e31_q24?0"NSNumber"8"NSNumber"16l
+ ___block_descriptor_48_e8_32bs40w_e8_v16?0q8l
+ ___block_descriptor_48_e8_32s_e18_B16?0"NSString"8l
+ ___block_descriptor_88_e8_32s40s48s_e5_v8?0l
+ ___swift_closure_destructor.149Tm
+ ___swift_closure_destructor.28Tm
+ ___swift_closure_destructor.371Tm
+ ___swift_closure_destructor.479Tm
+ ___swift_closure_destructor.65Tm
+ ___unnamed_11
+ _objc_getProperty
+ _objc_msgSend$_computeNormalizedGainFromPlayerItem:reason:
+ _objc_msgSend$audioTapDelegate
+ _objc_msgSend$cachedTimebase
+ _objc_msgSend$currentContentItemID
+ _objc_msgSend$currentEvent
+ _objc_msgSend$effectiveLoudnessInfo
+ _objc_msgSend$engine:didRenderAudioBuffer:itemTime:itemTimebase:numberOfFrames:sampleRate:normalizedGain:
+ _objc_msgSend$isSelfieSingShare
+ _objc_msgSend$keysSortedByValueUsingComparator:
+ _objc_msgSend$normalizedGain
+ _objc_msgSend$podcastRequiresAssetToken
+ _objc_msgSend$prewarmFrequentHLSConnections
+ _objc_msgSend$primaryItem
+ _objc_msgSend$recordHLSAssetURL:options:
+ _objc_msgSend$requiresAssetToken
+ _objc_msgSend$restrictions
+ _objc_msgSend$setCachedTimebase:
+ _objc_msgSend$setCurrentContentItemID:
+ _objc_msgSend$setEvents:
+ _objc_msgSend$setNormalizedGain:
+ _objc_msgSend$setRestrictions:
+ _objc_msgSend$set_tokenMintWaitTime:
+ _objc_msgSend$supportsAssetConnectionPrewarming
+ _objc_msgSend$tokenMintWaitTime
+ _objc_setProperty_atomic_copy
+ _symbolic So35AVPlayerInterstitialEventControllerC
+ _symbolic _____ 17MediaPlaybackCore32InterstitialRestrictionOverriderC
+ _symbolic _____Sg 17MediaPlaybackCore32InterstitialRestrictionOverriderC
+ _symbolic _____SgXw 17MediaPlaybackCore32InterstitialRestrictionOverriderC
- -[MPCPlaybackPerformanceController lastCDNWarming]
- -[MPCPlaybackPerformanceController loadAVAssetWithURL:]
- -[MPCPlaybackPerformanceController markCDNConnectionWarmed]
- -[MPCPlaybackPerformanceController setLastCDNWarming:]
- -[MPCPlaybackPerformanceController warmCDNConnection]
- GCC_except_table1008
- GCC_except_table1011
- GCC_except_table1020
- GCC_except_table1022
- GCC_except_table1035
- GCC_except_table1039
- GCC_except_table1045
- GCC_except_table1051
- GCC_except_table1054
- GCC_except_table1057
- GCC_except_table1246
- GCC_except_table1250
- GCC_except_table1420
- GCC_except_table1424
- GCC_except_table1468
- GCC_except_table1479
- GCC_except_table1486
- GCC_except_table1493
- GCC_except_table1530
- GCC_except_table1542
- GCC_except_table1594
- GCC_except_table1767
- GCC_except_table1769
- GCC_except_table1782
- GCC_except_table1787
- GCC_except_table1857
- GCC_except_table1942
- GCC_except_table1943
- GCC_except_table2057
- GCC_except_table2077
- GCC_except_table2079
- GCC_except_table2107
- GCC_except_table2118
- GCC_except_table2124
- GCC_except_table2126
- GCC_except_table2129
- GCC_except_table2140
- GCC_except_table2150
- GCC_except_table2266
- GCC_except_table2317
- GCC_except_table2321
- GCC_except_table2324
- GCC_except_table2352
- GCC_except_table2376
- GCC_except_table2409
- GCC_except_table2650
- GCC_except_table2678
- GCC_except_table2705
- GCC_except_table2850
- GCC_except_table2871
- GCC_except_table2878
- GCC_except_table2879
- GCC_except_table2904
- GCC_except_table2906
- GCC_except_table2911
- GCC_except_table2917
- GCC_except_table2919
- GCC_except_table2921
- GCC_except_table2952
- GCC_except_table2966
- GCC_except_table2968
- GCC_except_table2972
- GCC_except_table2978
- GCC_except_table2983
- GCC_except_table2989
- GCC_except_table3009
- GCC_except_table3059
- GCC_except_table3145
- GCC_except_table3149
- GCC_except_table3160
- GCC_except_table3161
- GCC_except_table3185
- GCC_except_table3197
- GCC_except_table3243
- GCC_except_table3244
- GCC_except_table3253
- GCC_except_table3310
- GCC_except_table3328
- GCC_except_table3337
- GCC_except_table3378
- GCC_except_table3382
- GCC_except_table3392
- GCC_except_table3403
- GCC_except_table3457
- GCC_except_table3502
- GCC_except_table3507
- GCC_except_table3627
- GCC_except_table3648
- GCC_except_table3655
- GCC_except_table3682
- GCC_except_table3686
- GCC_except_table3696
- GCC_except_table3753
- GCC_except_table3760
- GCC_except_table3764
- GCC_except_table3835
- GCC_except_table3938
- GCC_except_table3942
- GCC_except_table3954
- GCC_except_table3970
- GCC_except_table3977
- GCC_except_table3987
- GCC_except_table4115
- GCC_except_table4161
- GCC_except_table4162
- GCC_except_table4163
- GCC_except_table4182
- GCC_except_table4193
- GCC_except_table4211
- GCC_except_table4216
- GCC_except_table4218
- GCC_except_table4254
- GCC_except_table4266
- GCC_except_table4355
- GCC_except_table4374
- GCC_except_table4389
- GCC_except_table4398
- GCC_except_table4429
- GCC_except_table4600
- GCC_except_table4601
- GCC_except_table4780
- GCC_except_table4815
- GCC_except_table4817
- GCC_except_table4825
- GCC_except_table4833
- GCC_except_table4849
- GCC_except_table4861
- GCC_except_table4871
- GCC_except_table4882
- GCC_except_table4895
- GCC_except_table4942
- GCC_except_table4973
- GCC_except_table4978
- GCC_except_table4984
- GCC_except_table5029
- GCC_except_table5064
- GCC_except_table5148
- GCC_except_table5505
- GCC_except_table559
- GCC_except_table5607
- GCC_except_table575
- GCC_except_table5757
- GCC_except_table5782
- GCC_except_table592
- GCC_except_table5954
- GCC_except_table6020
- GCC_except_table6045
- GCC_except_table6080
- GCC_except_table6083
- GCC_except_table6086
- GCC_except_table6172
- GCC_except_table6389
- GCC_except_table6406
- GCC_except_table6857
- GCC_except_table7201
- GCC_except_table7216
- GCC_except_table7307
- GCC_except_table7316
- GCC_except_table7405
- GCC_except_table7412
- GCC_except_table7430
- GCC_except_table7481
- GCC_except_table7482
- GCC_except_table7485
- GCC_except_table7490
- GCC_except_table7506
- GCC_except_table844
- GCC_except_table900
- GCC_except_table976
- _OBJC_IVAR_$_MPCPlaybackPerformanceController._lastCDNWarming
- ___55-[MPCPlaybackPerformanceController loadAVAssetWithURL:]_block_invoke
- ___swift_closure_destructor.148Tm
- ___swift_closure_destructor.22Tm
- ___swift_closure_destructor.370Tm
- ___swift_closure_destructor.478Tm
- ___swift_closure_destructor.64Tm
- ___unnamed_10
- _objc_msgSend$lastCDNWarming
- _objc_msgSend$loadAVAssetWithURL:
- _objc_msgSend$markCDNConnectionWarmed
- _objc_msgSend$setLastCDNWarming:
- _objc_msgSend$stringForFactor:
- _objc_msgSend$warmCDNConnection
CStrings:
+ "Asset Token Refresh"
+ "Asset token refresh"
+ "AssetTokenRefresh"
+ "MPCPlaybackPerformanceHLSHostCounts"
+ "MPCPlaybackPerformanceHLSPrewarmOptions"
+ "MPCPlaybackPerformanceHLSTotalPlays"
+ "Q\xf0\x81"
+ "SEED"
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
