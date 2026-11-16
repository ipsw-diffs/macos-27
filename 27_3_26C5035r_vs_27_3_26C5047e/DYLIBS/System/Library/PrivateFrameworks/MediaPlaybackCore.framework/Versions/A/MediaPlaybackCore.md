## MediaPlaybackCore

> `/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/Versions/A/MediaPlaybackCore`

```diff

-26300.26.43.301.0
-  __TEXT.__text: 0x3c1138
-  __TEXT.__objc_methlist: 0x166a0
+26300.26.46.101.0
+  __TEXT.__text: 0x3c5510
+  __TEXT.__objc_methlist: 0x168a8
   __TEXT.__dlopen_cstrs: 0xbe
-  __TEXT.__const: 0xdaa0
-  __TEXT.__cstring: 0x23818
-  __TEXT.__constg_swiftt: 0x66a4
+  __TEXT.__const: 0xda90
+  __TEXT.__cstring: 0x237bc
+  __TEXT.__constg_swiftt: 0x66ec
   __TEXT.__swift5_typeref: 0x4684
   __TEXT.__swift5_builtin: 0x578
-  __TEXT.__swift5_reflstr: 0x4b32
-  __TEXT.__swift5_fieldmd: 0x48f4
+  __TEXT.__swift5_reflstr: 0x4b82
+  __TEXT.__swift5_fieldmd: 0x4918
   __TEXT.__swift5_assocty: 0xa20
-  __TEXT.__oslogstring: 0x42900
+  __TEXT.__oslogstring: 0x430da
   __TEXT.__swift5_proto: 0x7a8
   __TEXT.__swift5_types: 0x450
-  __TEXT.__swift5_capture: 0x6814
+  __TEXT.__swift5_capture: 0x68a8
   __TEXT.__swift_as_entry: 0x2c0
   __TEXT.__swift_as_ret: 0x324
   __TEXT.__swift_as_cont: 0x8b4
   __TEXT.__swift5_mpenum: 0xf8
   __TEXT.__swift5_protos: 0xc4
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x5734
+  __TEXT.__gcc_except_tab: 0x57a8
   __TEXT.__ustring: 0x4d4
-  __TEXT.__unwind_info: 0xd4c0
-  __TEXT.__eh_frame: 0x9d08
+  __TEXT.__unwind_info: 0xd5e8
+  __TEXT.__eh_frame: 0x9d38
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x2cd8
-  __DATA_CONST.__objc_classlist: 0xc28
+  __DATA_CONST.__objc_classlist: 0xc38
   __DATA_CONST.__objc_catlist: 0x280
-  __DATA_CONST.__objc_protolist: 0x6c8
+  __DATA_CONST.__objc_protolist: 0x6d0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc0b0
+  __DATA_CONST.__objc_selrefs: 0xc130
   __DATA_CONST.__objc_protorefs: 0x2c8
-  __DATA_CONST.__objc_superrefs: 0x6b8
+  __DATA_CONST.__objc_superrefs: 0x6c8
   __DATA_CONST.__objc_arraydata: 0x288
   __DATA_CONST.__got: 0x2ab0
-  __AUTH_CONST.__const: 0x1ee80
+  __AUTH_CONST.__const: 0x1eff0
   __AUTH_CONST.__cfstring: 0x1e4a0
-  __AUTH_CONST.__objc_const: 0x310f0
-  __AUTH_CONST.__objc_intobj: 0x8b8
+  __AUTH_CONST.__objc_const: 0x315c8
+  __AUTH_CONST.__objc_intobj: 0x8a0
   __AUTH_CONST.__objc_arrayobj: 0x258
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x50
   __AUTH_CONST.__auth_got: 0x2718
-  __AUTH.__objc_data: 0x4808
+  __AUTH.__objc_data: 0x48a8
   __AUTH.__data: 0x1ff0
-  __DATA.__objc_ivar: 0x1a6c
-  __DATA.__data: 0x56d0
+  __DATA.__objc_ivar: 0x1aac
+  __DATA.__data: 0x5740
   __DATA.__bss: 0xc028
   __DATA.__common: 0xe8
-  __DATA_DIRTY.__objc_data: 0x3100
-  __DATA_DIRTY.__data: 0x5c18
+  __DATA_DIRTY.__objc_data: 0x3118
+  __DATA_DIRTY.__data: 0x5c48
   __DATA_DIRTY.__bss: 0x1b30
   __DATA_DIRTY.__common: 0xb0
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 19328
-  Symbols:   22677
-  CStrings:  7642
+  Functions: 19418
+  Symbols:   22770
+  CStrings:  7662
 
Symbols:
+ -[MPCAssistantPlaybackQueue privateListeningOverride]
+ -[MPCAssistantPlaybackQueue setPrivateListeningOverride:]
+ -[MPCModelGenericAVItem _applyTimedMetadataResponse:metadataChangeTime:]
+ -[MPCModelGenericAVItem _prepareLeaseWithShouldRequireLeaseAcquisition:completesWhenRequestSent:completionHandler:]
+ -[MPCModelGenericAVItemTimedMetadataRequest lastFinalResponse]
+ -[MPCModelGenericAVItemTimedMetadataRequest setLastFinalResponse:]
+ -[MPCPlaybackAccount _isUnknownAccount]
+ -[MPCPlaybackEngine isSelfieSingSessionActive]
+ -[MPCPlaybackEngine selfieSingSessionController]
+ -[MPCPlaybackEngine takeSelfieSingSessionAssertion]
+ -[MPCSelfieSingSessionController .cxx_destruct]
+ -[MPCSelfieSingSessionController _assertionDidInvalidateWithIdentifier:released:]
+ -[MPCSelfieSingSessionController _scheduleActiveStateUpdate]
+ -[MPCSelfieSingSessionController _updateActiveState]
+ -[MPCSelfieSingSessionController initWithEngineID:activeStateHandler:]
+ -[MPCSelfieSingSessionController isActive]
+ -[MPCSelfieSingSessionController takeAssertion]
+ -[MPCWhiskyController engineDidBeginSelfieSingSession:]
+ -[MPCWhiskyController engineDidEndSelfieSingSession:]
+ -[_MPCPlaybackEnginePlayer engineDidBeginSelfieSingSession:]
+ -[_MPCPlaybackEnginePlayer engineDidEndSelfieSingSession:]
+ -[_MPCSelfieSingSessionAssertion .cxx_destruct]
+ -[_MPCSelfieSingSessionAssertion _invalidateReleased:]
+ -[_MPCSelfieSingSessionAssertion _invalidateReplaced]
+ -[_MPCSelfieSingSessionAssertion dealloc]
+ -[_MPCSelfieSingSessionAssertion description]
+ -[_MPCSelfieSingSessionAssertion identifier]
+ -[_MPCSelfieSingSessionAssertion initWithController:]
+ -[_MPCSelfieSingSessionAssertion invalidate]
+ -[_MPCSelfieSingSessionAssertion isInvalidated]
+ GCC_except_table1019
+ GCC_except_table1021
+ GCC_except_table1028
+ GCC_except_table1030
+ GCC_except_table1043
+ GCC_except_table1047
+ GCC_except_table1053
+ GCC_except_table1065
+ GCC_except_table1262
+ GCC_except_table1264
+ GCC_except_table1434
+ GCC_except_table1438
+ GCC_except_table1482
+ GCC_except_table1493
+ GCC_except_table1500
+ GCC_except_table1507
+ GCC_except_table1544
+ GCC_except_table1556
+ GCC_except_table1565
+ GCC_except_table1608
+ GCC_except_table1781
+ GCC_except_table1783
+ GCC_except_table1801
+ GCC_except_table1871
+ GCC_except_table1956
+ GCC_except_table1957
+ GCC_except_table2071
+ GCC_except_table2091
+ GCC_except_table2093
+ GCC_except_table2122
+ GCC_except_table2139
+ GCC_except_table2141
+ GCC_except_table2144
+ GCC_except_table2155
+ GCC_except_table2165
+ GCC_except_table2281
+ GCC_except_table229
+ GCC_except_table2332
+ GCC_except_table2336
+ GCC_except_table2339
+ GCC_except_table2367
+ GCC_except_table2391
+ GCC_except_table2424
+ GCC_except_table2665
+ GCC_except_table2693
+ GCC_except_table2722
+ GCC_except_table2867
+ GCC_except_table2895
+ GCC_except_table2896
+ GCC_except_table2921
+ GCC_except_table2923
+ GCC_except_table2932
+ GCC_except_table2934
+ GCC_except_table2936
+ GCC_except_table2938
+ GCC_except_table2941
+ GCC_except_table2969
+ GCC_except_table2978
+ GCC_except_table2983
+ GCC_except_table2985
+ GCC_except_table2989
+ GCC_except_table2994
+ GCC_except_table3000
+ GCC_except_table3003
+ GCC_except_table3006
+ GCC_except_table3026
+ GCC_except_table3076
+ GCC_except_table3166
+ GCC_except_table3170
+ GCC_except_table3181
+ GCC_except_table3182
+ GCC_except_table3206
+ GCC_except_table3218
+ GCC_except_table3268
+ GCC_except_table3277
+ GCC_except_table3334
+ GCC_except_table3354
+ GCC_except_table3355
+ GCC_except_table3365
+ GCC_except_table3406
+ GCC_except_table3410
+ GCC_except_table3420
+ GCC_except_table3431
+ GCC_except_table3435
+ GCC_except_table3483
+ GCC_except_table3528
+ GCC_except_table3533
+ GCC_except_table3653
+ GCC_except_table3674
+ GCC_except_table3681
+ GCC_except_table3708
+ GCC_except_table3712
+ GCC_except_table3722
+ GCC_except_table3786
+ GCC_except_table3790
+ GCC_except_table3858
+ GCC_except_table395
+ GCC_except_table3963
+ GCC_except_table3967
+ GCC_except_table3979
+ GCC_except_table3995
+ GCC_except_table4002
+ GCC_except_table4012
+ GCC_except_table4140
+ GCC_except_table4186
+ GCC_except_table4187
+ GCC_except_table4188
+ GCC_except_table4218
+ GCC_except_table4236
+ GCC_except_table4241
+ GCC_except_table4243
+ GCC_except_table4279
+ GCC_except_table4291
+ GCC_except_table4380
+ GCC_except_table4399
+ GCC_except_table4414
+ GCC_except_table4423
+ GCC_except_table4454
+ GCC_except_table448
+ GCC_except_table456
+ GCC_except_table4625
+ GCC_except_table4626
+ GCC_except_table466
+ GCC_except_table477
+ GCC_except_table4805
+ GCC_except_table4840
+ GCC_except_table4842
+ GCC_except_table4850
+ GCC_except_table4858
+ GCC_except_table4874
+ GCC_except_table4886
+ GCC_except_table4907
+ GCC_except_table4920
+ GCC_except_table4967
+ GCC_except_table4981
+ GCC_except_table5003
+ GCC_except_table5009
+ GCC_except_table5054
+ GCC_except_table5089
+ GCC_except_table5173
+ GCC_except_table5535
+ GCC_except_table561
+ GCC_except_table5641
+ GCC_except_table5664
+ GCC_except_table5666
+ GCC_except_table578
+ GCC_except_table5815
+ GCC_except_table5840
+ GCC_except_table595
+ GCC_except_table6012
+ GCC_except_table6078
+ GCC_except_table6103
+ GCC_except_table6138
+ GCC_except_table6141
+ GCC_except_table6144
+ GCC_except_table6230
+ GCC_except_table6447
+ GCC_except_table6464
+ GCC_except_table6915
+ GCC_except_table7259
+ GCC_except_table7274
+ GCC_except_table7365
+ GCC_except_table7374
+ GCC_except_table7463
+ GCC_except_table7470
+ GCC_except_table7488
+ GCC_except_table7539
+ GCC_except_table7540
+ GCC_except_table7543
+ GCC_except_table7548
+ GCC_except_table7564
+ GCC_except_table846
+ GCC_except_table904
+ GCC_except_table984
+ _MPCPlaybackEngineEventTypeSelfieSingSessionBegin
+ _MPCPlaybackEngineEventTypeSelfieSingSessionEnd
+ _OBJC_CLASS_$_MPCSelfieSingSessionController
+ _OBJC_CLASS_$__MPCSelfieSingSessionAssertion
+ _OBJC_IVAR_$_MPCAssistantPlaybackQueue._privateListeningOverride
+ _OBJC_IVAR_$_MPCModelGenericAVItem._lastFinalTimedMetadataResponse
+ _OBJC_IVAR_$_MPCModelGenericAVItem._timedMetadataStationFallbackGeneration
+ _OBJC_IVAR_$_MPCModelGenericAVItemTimedMetadataRequest._lastFinalResponse
+ _OBJC_IVAR_$_MPCModelRadioQueueFeeder._stationArtworkCacheRequestInFlight
+ _OBJC_IVAR_$_MPCPlaybackEngine._selfieSingSessionController
+ _OBJC_IVAR_$_MPCQueueController._liveItemBeginQueueItemID
+ _OBJC_IVAR_$_MPCQueueController._liveItemBeginQueueSectionID
+ _OBJC_IVAR_$_MPCSelfieSingSessionController._active
+ _OBJC_IVAR_$_MPCSelfieSingSessionController._activeStateHandler
+ _OBJC_IVAR_$_MPCSelfieSingSessionController._engineID
+ _OBJC_IVAR_$_MPCSelfieSingSessionController._holder
+ _OBJC_IVAR_$_MPCSelfieSingSessionController._holderIdentifier
+ _OBJC_IVAR_$_MPCSelfieSingSessionController._lock
+ _OBJC_IVAR_$__MPCSelfieSingSessionAssertion._controller
+ _OBJC_IVAR_$__MPCSelfieSingSessionAssertion._identifier
+ _OBJC_IVAR_$__MPCSelfieSingSessionAssertion._invalidated
+ _OBJC_IVAR_$__MPCSelfieSingSessionAssertion._lock
+ _OBJC_METACLASS_$_MPCSelfieSingSessionController
+ _OBJC_METACLASS_$__MPCSelfieSingSessionAssertion
+ __OBJC_$_INSTANCE_METHODS_MPCSelfieSingSessionController
+ __OBJC_$_INSTANCE_METHODS__MPCSelfieSingSessionAssertion
+ __OBJC_$_INSTANCE_VARIABLES_MPCSelfieSingSessionController
+ __OBJC_$_INSTANCE_VARIABLES__MPCSelfieSingSessionAssertion
+ __OBJC_$_PROP_LIST_MPCSelfieSingSessionAssertion
+ __OBJC_$_PROP_LIST_MPCSelfieSingSessionController
+ __OBJC_$_PROP_LIST__MPCSelfieSingSessionAssertion
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MPCSelfieSingSessionAssertion
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MPCSelfieSingSessionAssertion
+ __OBJC_$_PROTOCOL_REFS_MPCSelfieSingSessionAssertion
+ __OBJC_CLASS_PROTOCOLS_$__MPCSelfieSingSessionAssertion
+ __OBJC_CLASS_RO_$_MPCSelfieSingSessionController
+ __OBJC_CLASS_RO_$__MPCSelfieSingSessionAssertion
+ __OBJC_LABEL_PROTOCOL_$_MPCSelfieSingSessionAssertion
+ __OBJC_METACLASS_RO_$_MPCSelfieSingSessionController
+ __OBJC_METACLASS_RO_$__MPCSelfieSingSessionAssertion
+ __OBJC_PROTOCOL_$_MPCSelfieSingSessionAssertion
+ ___115-[MPCModelGenericAVItem _prepareLeaseWithShouldRequireLeaseAcquisition:completesWhenRequestSent:completionHandler:]_block_invoke
+ ___115-[MPCModelGenericAVItem _prepareLeaseWithShouldRequireLeaseAcquisition:completesWhenRequestSent:completionHandler:]_block_invoke_2
+ ___40-[MPCPlaybackEngine initWithParameters:]_block_invoke
+ ___42-[MPCSelfieSingSessionController isActive]_block_invoke
+ ___47-[MPCSelfieSingSessionController takeAssertion]_block_invoke
+ ___47-[_MPCSelfieSingSessionAssertion isInvalidated]_block_invoke
+ ___52-[MPCModelGenericAVItem _reloadTimedMetadataRequest]_block_invoke_3
+ ___52-[MPCSelfieSingSessionController _updateActiveState]_block_invoke
+ ___53-[_MPCSelfieSingSessionAssertion _invalidateReplaced]_block_invoke
+ ___54-[_MPCSelfieSingSessionAssertion _invalidateReleased:]_block_invoke
+ ___60-[MPCSelfieSingSessionController _scheduleActiveStateUpdate]_block_invoke
+ ___78-[MPCModelGenericAVItem _finishDeferredLeaseAcquisitionWithCompletionHandler:]_block_invoke_3
+ ___78-[MPCModelGenericAVItem _finishDeferredLeaseAcquisitionWithCompletionHandler:]_block_invoke_4
+ ___81-[MPCSelfieSingSessionController _assertionDidInvalidateWithIdentifier:released:]_block_invoke
+ ____MPCQCBMSessionTypeAccounts_block_invoke
+ ___block_descriptor_49_e8_32s40bs_e64_v24?0"MPCModelGenericAVItemTimedMetadataResponse"8"NSError"16l
+ ___block_descriptor_50_e8_32s40bs_e97_v32?0"ICMusicSubscriptionLeaseSession"8"MPSubscriptionStatusPlaybackInformation"16"NSError"24l
+ ___block_descriptor_58_e8_32s40s48bs_e5_v8?0l
+ ___block_descriptor_73_e8_32s40s48bs_e5_v8?0l
+ ___swift_closure_destructor.150Tm
+ ___swift_closure_destructor.372Tm
+ ___swift_closure_destructor.480Tm
+ _objc_msgSend$_applyTimedMetadataResponse:metadataChangeTime:
+ _objc_msgSend$_assertionDidInvalidateWithIdentifier:released:
+ _objc_msgSend$_invalidateReleased:
+ _objc_msgSend$_invalidateReplaced
+ _objc_msgSend$_isUnknownAccount
+ _objc_msgSend$_prepareLeaseWithShouldRequireLeaseAcquisition:completesWhenRequestSent:completionHandler:
+ _objc_msgSend$_scheduleActiveStateUpdate
+ _objc_msgSend$_updateActiveState
+ _objc_msgSend$engineDidBeginSelfieSingSession:
+ _objc_msgSend$engineDidEndSelfieSingSession:
+ _objc_msgSend$initWithEngineID:activeStateHandler:
+ _objc_msgSend$isSelfieSingSessionActive
+ _objc_msgSend$lastFinalResponse
+ _objc_msgSend$pausesAtItemEnd
+ _objc_msgSend$setLastFinalResponse:
+ _objc_msgSend$setPausesAtItemEnd:
+ _objc_msgSend$takeAssertion
- -[MPCPlaybackAccountManager guestAccount]
- -[MPCPlaybackAccountManager unknownAccount]
- GCC_except_table1013
- GCC_except_table1018
- GCC_except_table1025
- GCC_except_table1027
- GCC_except_table1040
- GCC_except_table1044
- GCC_except_table1050
- GCC_except_table1056
- GCC_except_table1252
- GCC_except_table1259
- GCC_except_table1429
- GCC_except_table1433
- GCC_except_table1477
- GCC_except_table1488
- GCC_except_table1495
- GCC_except_table1502
- GCC_except_table1539
- GCC_except_table1551
- GCC_except_table1560
- GCC_except_table1603
- GCC_except_table1776
- GCC_except_table1778
- GCC_except_table1791
- GCC_except_table1866
- GCC_except_table1951
- GCC_except_table1952
- GCC_except_table2066
- GCC_except_table2086
- GCC_except_table2088
- GCC_except_table2116
- GCC_except_table2127
- GCC_except_table2135
- GCC_except_table2138
- GCC_except_table2149
- GCC_except_table2159
- GCC_except_table227
- GCC_except_table2275
- GCC_except_table2326
- GCC_except_table2330
- GCC_except_table2333
- GCC_except_table2361
- GCC_except_table2385
- GCC_except_table2418
- GCC_except_table2659
- GCC_except_table2687
- GCC_except_table2714
- GCC_except_table2859
- GCC_except_table2880
- GCC_except_table2887
- GCC_except_table2913
- GCC_except_table2915
- GCC_except_table2920
- GCC_except_table2924
- GCC_except_table2926
- GCC_except_table2930
- GCC_except_table2933
- GCC_except_table2961
- GCC_except_table2970
- GCC_except_table2975
- GCC_except_table2977
- GCC_except_table2981
- GCC_except_table2986
- GCC_except_table2987
- GCC_except_table2992
- GCC_except_table2998
- GCC_except_table3018
- GCC_except_table3068
- GCC_except_table3158
- GCC_except_table3162
- GCC_except_table3173
- GCC_except_table3174
- GCC_except_table3198
- GCC_except_table3210
- GCC_except_table3257
- GCC_except_table3258
- GCC_except_table3324
- GCC_except_table3341
- GCC_except_table3342
- GCC_except_table3352
- GCC_except_table3393
- GCC_except_table3397
- GCC_except_table3407
- GCC_except_table3418
- GCC_except_table3422
- GCC_except_table3472
- GCC_except_table3517
- GCC_except_table3522
- GCC_except_table3642
- GCC_except_table3663
- GCC_except_table3670
- GCC_except_table3697
- GCC_except_table3701
- GCC_except_table3711
- GCC_except_table3768
- GCC_except_table3775
- GCC_except_table3849
- GCC_except_table391
- GCC_except_table3952
- GCC_except_table3956
- GCC_except_table3968
- GCC_except_table3984
- GCC_except_table3991
- GCC_except_table4001
- GCC_except_table4129
- GCC_except_table4175
- GCC_except_table4176
- GCC_except_table4177
- GCC_except_table4196
- GCC_except_table4225
- GCC_except_table4230
- GCC_except_table4232
- GCC_except_table4268
- GCC_except_table4280
- GCC_except_table4369
- GCC_except_table4388
- GCC_except_table4403
- GCC_except_table4412
- GCC_except_table4443
- GCC_except_table446
- GCC_except_table454
- GCC_except_table4614
- GCC_except_table4615
- GCC_except_table464
- GCC_except_table475
- GCC_except_table4794
- GCC_except_table4829
- GCC_except_table4831
- GCC_except_table4839
- GCC_except_table4847
- GCC_except_table4863
- GCC_except_table4875
- GCC_except_table4885
- GCC_except_table4909
- GCC_except_table4956
- GCC_except_table4970
- GCC_except_table4987
- GCC_except_table4992
- GCC_except_table5043
- GCC_except_table5078
- GCC_except_table5162
- GCC_except_table5523
- GCC_except_table560
- GCC_except_table576
- GCC_except_table5776
- GCC_except_table5801
- GCC_except_table593
- GCC_except_table5973
- GCC_except_table6039
- GCC_except_table6064
- GCC_except_table6099
- GCC_except_table6102
- GCC_except_table6105
- GCC_except_table6191
- GCC_except_table6408
- GCC_except_table6425
- GCC_except_table6876
- GCC_except_table7220
- GCC_except_table7235
- GCC_except_table7326
- GCC_except_table7335
- GCC_except_table7424
- GCC_except_table7431
- GCC_except_table7449
- GCC_except_table7500
- GCC_except_table7501
- GCC_except_table7504
- GCC_except_table7509
- GCC_except_table7525
- GCC_except_table845
- GCC_except_table901
- GCC_except_table981
- _OBJC_IVAR_$_MPCPlaybackAccountManager._guestAccount
- _OBJC_IVAR_$_MPCPlaybackAccountManager._unknownAccount
- ___65-[MPCPlaybackPerformanceController prewarmFrequentHLSConnections]_block_invoke
- ___65-[MPCPlaybackPerformanceController prewarmFrequentHLSConnections]_block_invoke_2
- ___90-[MPCModelGenericAVItem _prepareLeaseWithShouldRequireLeaseAcquisition:completionHandler:]_block_invoke
- ___90-[MPCModelGenericAVItem _prepareLeaseWithShouldRequireLeaseAcquisition:completionHandler:]_block_invoke_2
- ___block_descriptor_32_e31_q24?0"NSNumber"8"NSNumber"16l
- ___block_descriptor_48_e8_32s40bs_e64_v24?0"MPCModelGenericAVItemTimedMetadataResponse"8"NSError"16l
- ___block_descriptor_48_e8_32s_e18_B16?0"NSString"8l
- ___block_descriptor_49_e8_32s40bs_e97_v32?0"ICMusicSubscriptionLeaseSession"8"MPSubscriptionStatusPlaybackInformation"16"NSError"24l
- ___block_descriptor_57_e8_32s40s48bs_e5_v8?0l
- ___block_descriptor_89_e8_32s40s48s56s64bs_e5_v8?0l
- ___swift_closure_destructor.149Tm
- ___swift_closure_destructor.371Tm
- ___swift_closure_destructor.479Tm
- _objc_msgSend$guestAccount
- _objc_msgSend$keysSortedByValueUsingComparator:
- _objc_msgSend$unknownAccount
CStrings:
+ "<%@: %p id=%@ invalidated=%d>"
+ "Atmos: %@"
+ "Object is a video"
+ "Q\xf0\x91"
+ "Surround: %@"
+ "[%{public}@]-[LeaseRatePreparation] - %{public}@: Completing without waiting for lease acquisition response [online keys already available]"
+ "[AC] Failed to download %{public}s to asset cache: %{public}s"
+ "[AC] Not downloading %{public}s to asset cache [asset cache unavailable]"
+ "[AC] Not downloading %{public}s to asset cache [cache item is not downloadable]"
+ "[AC] Not downloading %{public}s to asset cache [item already has a download task]"
+ "[AC] Not downloading %{public}s to asset cache [item was released]"
+ "[AC] Not downloading %{public}s to asset cache [no cache item]"
+ "[AP] - %{public}@ - Applying restriction deferred during the Selfie Sing session"
+ "[AP] - %{public}@ - Deferring restriction until the Selfie Sing session ends [%{public}@]"
+ "[AP] - %{public}@ - Not arming the pause timeout [Selfie Sing session active]"
+ "[ENG:%{public}@] SelfieSingSession | invalidating assertion [] id=%{public}@"
+ "[ENG:%{public}@] SelfieSingSession | invalidating assertion [released without invalidate] id=%{public}@"
+ "[ENG:%{public}@] SelfieSingSession | session began []"
+ "[ENG:%{public}@] SelfieSingSession | session ended []"
+ "[ENG:%{public}@] SelfieSingSession | taking assertion [] id=%{public}@"
+ "[ENG:%{public}@] SelfieSingSession | taking assertion [already held] heldID=%{public}@"
+ "[PL:%{public}s] PLAYER CONTROLLER: Dropping the held itemDidBecomeCurrent of the incoming item the queue already considers current - item:%{public}s"
+ "[PL:%{public}s] PLAYER PROCESSING: InternalPlayerController - pausesAtItemEnd:%{bool,public}d - current item: %{public}s"
+ "[PL:%{public}s] STATE MACHINE: Applying target start time %{public}fs parked while changing queue - identifier:%{public}s in state: %{public}s"
+ "[PL:%{public}s] STATE MACHINE: Discarding target start time %{public}fs superseded by jump to %{public}fs - identifier:%{public}s"
+ "paused at item end"
+ "selfie-sing-session-begin"
+ "selfie-sing-session-end"
+ "\xf0\xf0\xf0\xe1"
- "DownloadToAssetCache"
- "MPCPlaybackPerformanceHLSHostCounts"
- "MPCPlaybackPerformanceHLSPrewarmOptions"
- "MPCPlaybackPerformanceHLSTotalPlays"
- "Object is a video without traits"
- "Q\xf0\x81"
- "Unexpected item type for loaded enhanced audio"
- "q24@?0@\"NSNumber\"8@\"NSNumber\"16"
- "\xf0\xf0\xf0\xc1"
```
