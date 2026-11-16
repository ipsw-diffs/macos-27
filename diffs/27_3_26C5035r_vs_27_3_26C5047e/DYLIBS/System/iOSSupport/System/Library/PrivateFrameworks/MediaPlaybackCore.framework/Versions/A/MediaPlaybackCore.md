## MediaPlaybackCore

> `/System/iOSSupport/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/Versions/A/MediaPlaybackCore`

```diff

-26300.26.43.301.0
-  __TEXT.__text: 0x45dd40
-  __TEXT.__objc_methlist: 0x177b8
+26300.26.46.101.0
+  __TEXT.__text: 0x4622f8
+  __TEXT.__objc_methlist: 0x179b8
   __TEXT.__dlopen_cstrs: 0xbe
-  __TEXT.__const: 0x10020
-  __TEXT.__cstring: 0x24e25
-  __TEXT.__constg_swiftt: 0x7b44
+  __TEXT.__const: 0x10010
+  __TEXT.__cstring: 0x24dc9
+  __TEXT.__constg_swiftt: 0x7b8c
   __TEXT.__swift5_typeref: 0x534a
   __TEXT.__swift5_builtin: 0x67c
-  __TEXT.__swift5_reflstr: 0x59f2
-  __TEXT.__swift5_fieldmd: 0x55a0
+  __TEXT.__swift5_reflstr: 0x5a42
+  __TEXT.__swift5_fieldmd: 0x55c4
   __TEXT.__swift5_assocty: 0xb58
-  __TEXT.__oslogstring: 0x4a193
+  __TEXT.__oslogstring: 0x4a96d
   __TEXT.__swift5_proto: 0x8d8
   __TEXT.__swift5_types: 0x534
-  __TEXT.__swift5_capture: 0x8aec
+  __TEXT.__swift5_capture: 0x8b80
   __TEXT.__swift_as_entry: 0x4e0
   __TEXT.__swift_as_ret: 0x5f4
   __TEXT.__swift_as_cont: 0xe98
   __TEXT.__swift5_mpenum: 0xf8
   __TEXT.__swift5_protos: 0xe8
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x577c
+  __TEXT.__gcc_except_tab: 0x57f0
   __TEXT.__ustring: 0x4dc
-  __TEXT.__unwind_info: 0x10650
-  __TEXT.__eh_frame: 0x1095c
+  __TEXT.__unwind_info: 0x10770
+  __TEXT.__eh_frame: 0x1098c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9110
-  __DATA_CONST.__objc_classlist: 0xd00
+  __DATA_CONST.__const: 0x90e8
+  __DATA_CONST.__objc_classlist: 0xd10
   __DATA_CONST.__objc_catlist: 0x280
-  __DATA_CONST.__objc_protolist: 0x7a0
+  __DATA_CONST.__objc_protolist: 0x7a8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc750
+  __DATA_CONST.__objc_selrefs: 0xc7e0
   __DATA_CONST.__objc_protorefs: 0x380
-  __DATA_CONST.__objc_superrefs: 0x6c0
+  __DATA_CONST.__objc_superrefs: 0x6d0
   __DATA_CONST.__objc_arraydata: 0x288
-  __DATA_CONST.__got: 0x31b8
-  __AUTH_CONST.__const: 0x1d5c8
+  __DATA_CONST.__got: 0x31c0
+  __AUTH_CONST.__const: 0x1d768
   __AUTH_CONST.__cfstring: 0x1e860
-  __AUTH_CONST.__objc_const: 0x33d18
-  __AUTH_CONST.__objc_intobj: 0x8b8
+  __AUTH_CONST.__objc_const: 0x341f0
+  __AUTH_CONST.__objc_intobj: 0x8a0
   __AUTH_CONST.__objc_arrayobj: 0x258
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x50
-  __AUTH_CONST.__auth_got: 0x3408
-  __AUTH.__objc_data: 0x5520
+  __AUTH_CONST.__auth_got: 0x3418
+  __AUTH.__objc_data: 0x55c0
   __AUTH.__data: 0x2d20
-  __DATA.__objc_ivar: 0x1a98
-  __DATA.__data: 0x6888
+  __DATA.__objc_ivar: 0x1ad8
+  __DATA.__data: 0x68e8
   __DATA.__bss: 0xdf48
   __DATA.__common: 0x240
-  __DATA_DIRTY.__objc_data: 0x3948
-  __DATA_DIRTY.__data: 0x5d90
+  __DATA_DIRTY.__objc_data: 0x3960
+  __DATA_DIRTY.__data: 0x5db0
   __DATA_DIRTY.__bss: 0x1b28
   __DATA_DIRTY.__common: 0xf0
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 23271
-  Symbols:   23564
-  CStrings:  8065
+  Functions: 23369
+  Symbols:   23662
+  CStrings:  8085
 
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
+ GCC_except_table1006
+ GCC_except_table1201
+ GCC_except_table1203
+ GCC_except_table1373
+ GCC_except_table1375
+ GCC_except_table1416
+ GCC_except_table1427
+ GCC_except_table1434
+ GCC_except_table1441
+ GCC_except_table1478
+ GCC_except_table1490
+ GCC_except_table1499
+ GCC_except_table1542
+ GCC_except_table1715
+ GCC_except_table1717
+ GCC_except_table1735
+ GCC_except_table1805
+ GCC_except_table1889
+ GCC_except_table1890
+ GCC_except_table193
+ GCC_except_table1998
+ GCC_except_table2018
+ GCC_except_table2020
+ GCC_except_table2049
+ GCC_except_table2058
+ GCC_except_table2063
+ GCC_except_table2065
+ GCC_except_table2068
+ GCC_except_table2079
+ GCC_except_table2089
+ GCC_except_table2204
+ GCC_except_table2255
+ GCC_except_table2259
+ GCC_except_table2262
+ GCC_except_table2288
+ GCC_except_table2312
+ GCC_except_table2344
+ GCC_except_table2585
+ GCC_except_table2613
+ GCC_except_table2642
+ GCC_except_table2787
+ GCC_except_table2815
+ GCC_except_table2816
+ GCC_except_table2841
+ GCC_except_table2843
+ GCC_except_table2852
+ GCC_except_table2854
+ GCC_except_table2856
+ GCC_except_table2858
+ GCC_except_table2861
+ GCC_except_table2887
+ GCC_except_table2896
+ GCC_except_table2901
+ GCC_except_table2903
+ GCC_except_table2907
+ GCC_except_table2912
+ GCC_except_table2918
+ GCC_except_table2921
+ GCC_except_table2924
+ GCC_except_table2944
+ GCC_except_table2994
+ GCC_except_table3084
+ GCC_except_table3088
+ GCC_except_table3099
+ GCC_except_table3100
+ GCC_except_table3132
+ GCC_except_table3176
+ GCC_except_table3177
+ GCC_except_table3184
+ GCC_except_table3241
+ GCC_except_table3261
+ GCC_except_table3262
+ GCC_except_table3272
+ GCC_except_table3314
+ GCC_except_table3316
+ GCC_except_table3323
+ GCC_except_table3334
+ GCC_except_table3338
+ GCC_except_table3380
+ GCC_except_table3425
+ GCC_except_table3430
+ GCC_except_table352
+ GCC_except_table3551
+ GCC_except_table3572
+ GCC_except_table3579
+ GCC_except_table3604
+ GCC_except_table3608
+ GCC_except_table3618
+ GCC_except_table3675
+ GCC_except_table3680
+ GCC_except_table3684
+ GCC_except_table3750
+ GCC_except_table3849
+ GCC_except_table3864
+ GCC_except_table3880
+ GCC_except_table3886
+ GCC_except_table3896
+ GCC_except_table398
+ GCC_except_table4024
+ GCC_except_table406
+ GCC_except_table4070
+ GCC_except_table4071
+ GCC_except_table4072
+ GCC_except_table4102
+ GCC_except_table4121
+ GCC_except_table4126
+ GCC_except_table4128
+ GCC_except_table414
+ GCC_except_table4142
+ GCC_except_table4176
+ GCC_except_table423
+ GCC_except_table4265
+ GCC_except_table4284
+ GCC_except_table4308
+ GCC_except_table4339
+ GCC_except_table4510
+ GCC_except_table4511
+ GCC_except_table4688
+ GCC_except_table4723
+ GCC_except_table4725
+ GCC_except_table4733
+ GCC_except_table4741
+ GCC_except_table4756
+ GCC_except_table4764
+ GCC_except_table4772
+ GCC_except_table4782
+ GCC_except_table4795
+ GCC_except_table4839
+ GCC_except_table4853
+ GCC_except_table4869
+ GCC_except_table4872
+ GCC_except_table4878
+ GCC_except_table4925
+ GCC_except_table4962
+ GCC_except_table5048
+ GCC_except_table507
+ GCC_except_table524
+ GCC_except_table5376
+ GCC_except_table5377
+ GCC_except_table541
+ GCC_except_table5453
+ GCC_except_table5553
+ GCC_except_table5576
+ GCC_except_table5578
+ GCC_except_table5727
+ GCC_except_table5752
+ GCC_except_table5921
+ GCC_except_table5986
+ GCC_except_table6011
+ GCC_except_table6046
+ GCC_except_table6049
+ GCC_except_table6052
+ GCC_except_table6138
+ GCC_except_table6355
+ GCC_except_table6372
+ GCC_except_table6843
+ GCC_except_table7183
+ GCC_except_table7198
+ GCC_except_table7289
+ GCC_except_table7298
+ GCC_except_table7387
+ GCC_except_table7394
+ GCC_except_table7412
+ GCC_except_table7463
+ GCC_except_table7464
+ GCC_except_table7467
+ GCC_except_table7472
+ GCC_except_table7488
+ GCC_except_table792
+ GCC_except_table850
+ GCC_except_table930
+ GCC_except_table964
+ GCC_except_table966
+ GCC_except_table971
+ GCC_except_table973
+ GCC_except_table986
+ GCC_except_table990
+ GCC_except_table996
+ _CGRectGetHeight
+ _CGRectGetWidth
+ _MPCPlaybackEngineEventTypeSelfieSingSessionBegin
+ _MPCPlaybackEngineEventTypeSelfieSingSessionEnd
+ _OBJC_CLASS_$_MPCSelfieSingSessionController
+ _OBJC_CLASS_$_UIScreen
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
+ ___block_descriptor_49_e8_32s40bs_e64_v24?0"MPCModelGenericAVItemTimedMetadataResponse"8"NSError"16ls40l8s32l8
+ ___block_descriptor_50_e8_32s40bs_e97_v32?0"ICMusicSubscriptionLeaseSession"8"MPSubscriptionStatusPlaybackInformation"16"NSError"24ls32l8s40l8
+ ___block_descriptor_58_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
+ ___block_descriptor_73_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
+ ___swift_closure_destructor.227Tm
+ ___swift_closure_destructor.500Tm
+ ___swift_closure_destructor.609Tm
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
+ _objc_msgSend$mainScreen
+ _objc_msgSend$nativeBounds
+ _objc_msgSend$pausesAtItemEnd
+ _objc_msgSend$setLastFinalResponse:
+ _objc_msgSend$setPausesAtItemEnd:
+ _objc_msgSend$takeAssertion
- -[MPCPlaybackAccountManager guestAccount]
- -[MPCPlaybackAccountManager unknownAccount]
- GCC_except_table1191
- GCC_except_table1198
- GCC_except_table1368
- GCC_except_table1370
- GCC_except_table1411
- GCC_except_table1422
- GCC_except_table1429
- GCC_except_table1436
- GCC_except_table1473
- GCC_except_table1485
- GCC_except_table1494
- GCC_except_table1537
- GCC_except_table1710
- GCC_except_table1712
- GCC_except_table1725
- GCC_except_table1800
- GCC_except_table1884
- GCC_except_table1885
- GCC_except_table191
- GCC_except_table1993
- GCC_except_table2013
- GCC_except_table2015
- GCC_except_table2043
- GCC_except_table2052
- GCC_except_table2057
- GCC_except_table2059
- GCC_except_table2062
- GCC_except_table2073
- GCC_except_table2083
- GCC_except_table2198
- GCC_except_table2249
- GCC_except_table2253
- GCC_except_table2256
- GCC_except_table2282
- GCC_except_table2306
- GCC_except_table2338
- GCC_except_table2579
- GCC_except_table2607
- GCC_except_table2634
- GCC_except_table2779
- GCC_except_table2800
- GCC_except_table2807
- GCC_except_table2833
- GCC_except_table2835
- GCC_except_table2840
- GCC_except_table2844
- GCC_except_table2846
- GCC_except_table2850
- GCC_except_table2853
- GCC_except_table2879
- GCC_except_table2888
- GCC_except_table2893
- GCC_except_table2895
- GCC_except_table2899
- GCC_except_table2904
- GCC_except_table2905
- GCC_except_table2910
- GCC_except_table2916
- GCC_except_table2936
- GCC_except_table2986
- GCC_except_table3076
- GCC_except_table3080
- GCC_except_table3091
- GCC_except_table3092
- GCC_except_table3116
- GCC_except_table3166
- GCC_except_table3167
- GCC_except_table3174
- GCC_except_table3231
- GCC_except_table3248
- GCC_except_table3249
- GCC_except_table3259
- GCC_except_table3301
- GCC_except_table3303
- GCC_except_table3310
- GCC_except_table3321
- GCC_except_table3325
- GCC_except_table3369
- GCC_except_table3414
- GCC_except_table3419
- GCC_except_table348
- GCC_except_table3540
- GCC_except_table3561
- GCC_except_table3568
- GCC_except_table3593
- GCC_except_table3597
- GCC_except_table3607
- GCC_except_table3664
- GCC_except_table3669
- GCC_except_table3673
- GCC_except_table3741
- GCC_except_table3838
- GCC_except_table3842
- GCC_except_table3869
- GCC_except_table3875
- GCC_except_table3885
- GCC_except_table396
- GCC_except_table4013
- GCC_except_table404
- GCC_except_table4059
- GCC_except_table4060
- GCC_except_table4061
- GCC_except_table4080
- GCC_except_table4110
- GCC_except_table4115
- GCC_except_table4117
- GCC_except_table412
- GCC_except_table4131
- GCC_except_table4154
- GCC_except_table421
- GCC_except_table4254
- GCC_except_table4273
- GCC_except_table4286
- GCC_except_table4328
- GCC_except_table4499
- GCC_except_table4500
- GCC_except_table4677
- GCC_except_table4712
- GCC_except_table4714
- GCC_except_table4722
- GCC_except_table4730
- GCC_except_table4745
- GCC_except_table4753
- GCC_except_table4761
- GCC_except_table4771
- GCC_except_table4784
- GCC_except_table4828
- GCC_except_table4842
- GCC_except_table4858
- GCC_except_table4861
- GCC_except_table4867
- GCC_except_table4914
- GCC_except_table4951
- GCC_except_table5037
- GCC_except_table506
- GCC_except_table522
- GCC_except_table5365
- GCC_except_table5366
- GCC_except_table539
- GCC_except_table5441
- GCC_except_table5688
- GCC_except_table5713
- GCC_except_table5882
- GCC_except_table5947
- GCC_except_table5972
- GCC_except_table6007
- GCC_except_table6010
- GCC_except_table6013
- GCC_except_table6099
- GCC_except_table6316
- GCC_except_table6333
- GCC_except_table6804
- GCC_except_table7144
- GCC_except_table7159
- GCC_except_table7250
- GCC_except_table7259
- GCC_except_table7348
- GCC_except_table7355
- GCC_except_table7373
- GCC_except_table7424
- GCC_except_table7425
- GCC_except_table7428
- GCC_except_table7433
- GCC_except_table7449
- GCC_except_table791
- GCC_except_table847
- GCC_except_table927
- GCC_except_table958
- GCC_except_table963
- GCC_except_table968
- GCC_except_table970
- GCC_except_table983
- GCC_except_table987
- GCC_except_table993
- GCC_except_table997
- _OBJC_IVAR_$_MPCPlaybackAccountManager._guestAccount
- _OBJC_IVAR_$_MPCPlaybackAccountManager._unknownAccount
- ___65-[MPCPlaybackPerformanceController prewarmFrequentHLSConnections]_block_invoke
- ___65-[MPCPlaybackPerformanceController prewarmFrequentHLSConnections]_block_invoke_2
- ___90-[MPCModelGenericAVItem _prepareLeaseWithShouldRequireLeaseAcquisition:completionHandler:]_block_invoke
- ___90-[MPCModelGenericAVItem _prepareLeaseWithShouldRequireLeaseAcquisition:completionHandler:]_block_invoke_2
- ___block_descriptor_32_e31_q24?0"NSNumber"8"NSNumber"16l
- ___block_descriptor_48_e8_32s40bs_e64_v24?0"MPCModelGenericAVItemTimedMetadataResponse"8"NSError"16ls40l8s32l8
- ___block_descriptor_48_e8_32s_e18_B16?0"NSString"8ls32l8
- ___block_descriptor_49_e8_32s40bs_e97_v32?0"ICMusicSubscriptionLeaseSession"8"MPSubscriptionStatusPlaybackInformation"16"NSError"24ls32l8s40l8
- ___block_descriptor_57_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
- ___block_descriptor_89_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- ___swift_closure_destructor.226Tm
- ___swift_closure_destructor.499Tm
- ___swift_closure_destructor.608Tm
- _objc_msgSend$guestAccount
- _objc_msgSend$keysSortedByValueUsingComparator:
- _objc_msgSend$unknownAccount
CStrings:
+ "<%@: %p id=%@ invalidated=%d>"
+ "Atmos: %@"
+ "Object is a video"
+ "Q\xf0\xa1"
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
- "Q\xf0\x91"
- "Unexpected item type for loaded enhanced audio"
- "q24@?0@\"NSNumber\"8@\"NSNumber\"16"
- "\xf0\xf0\xf0\xc1"
```
