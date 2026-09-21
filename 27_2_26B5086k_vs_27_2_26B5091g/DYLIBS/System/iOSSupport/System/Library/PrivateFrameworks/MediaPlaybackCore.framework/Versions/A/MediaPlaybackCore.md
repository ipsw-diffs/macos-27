## MediaPlaybackCore

> `/System/iOSSupport/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/Versions/A/MediaPlaybackCore`

```diff

-26200.26.36.301.0
-  __TEXT.__text: 0x43b54c
-  __TEXT.__objc_methlist: 0x175c8
+26200.26.37.501.0
+  __TEXT.__text: 0x43ee0c
+  __TEXT.__objc_methlist: 0x17638
   __TEXT.__dlopen_cstrs: 0xbe
-  __TEXT.__const: 0xf960
-  __TEXT.__cstring: 0x2484c
+  __TEXT.__const: 0xfa90
+  __TEXT.__cstring: 0x2492b
   __TEXT.__constg_swiftt: 0x7820
-  __TEXT.__swift5_typeref: 0x50fc
+  __TEXT.__swift5_typeref: 0x5118
   __TEXT.__swift5_builtin: 0x67c
-  __TEXT.__swift5_reflstr: 0x5712
-  __TEXT.__swift5_fieldmd: 0x52a0
+  __TEXT.__swift5_reflstr: 0x5722
+  __TEXT.__swift5_fieldmd: 0x52ac
   __TEXT.__swift5_assocty: 0xb58
-  __TEXT.__oslogstring: 0x489c4
+  __TEXT.__oslogstring: 0x48dc2
   __TEXT.__swift5_proto: 0x8b8
   __TEXT.__swift5_types: 0x514
-  __TEXT.__swift5_capture: 0x8438
+  __TEXT.__swift5_capture: 0x8444
   __TEXT.__swift_as_entry: 0x48c
   __TEXT.__swift_as_ret: 0x590
   __TEXT.__swift_as_cont: 0xd9c
-  __TEXT.__swift5_mpenum: 0xb8
+  __TEXT.__swift5_mpenum: 0xf8
   __TEXT.__swift5_protos: 0xd8
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x5708
+  __TEXT.__gcc_except_tab: 0x5748
   __TEXT.__ustring: 0x4dc
-  __TEXT.__unwind_info: 0xff08
-  __TEXT.__eh_frame: 0xf794
+  __TEXT.__unwind_info: 0xff18
+  __TEXT.__eh_frame: 0xf7ec
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x280
   __DATA_CONST.__objc_protolist: 0x7a0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc610
+  __DATA_CONST.__objc_selrefs: 0xc658
   __DATA_CONST.__objc_protorefs: 0x380
   __DATA_CONST.__objc_superrefs: 0x6c0
   __DATA_CONST.__objc_arraydata: 0x298
-  __DATA_CONST.__got: 0x30f0
+  __DATA_CONST.__got: 0x30f8
   __AUTH_CONST.__const: 0x1c318
-  __AUTH_CONST.__cfstring: 0x1e3c0
-  __AUTH_CONST.__objc_const: 0x33448
-  __AUTH_CONST.__objc_intobj: 0x888
+  __AUTH_CONST.__cfstring: 0x1e480
+  __AUTH_CONST.__objc_const: 0x334d0
+  __AUTH_CONST.__objc_intobj: 0x8a0
   __AUTH_CONST.__objc_arrayobj: 0x288
   __AUTH_CONST.__objc_dictobj: 0xc8
-  __AUTH_CONST.__objc_doubleobj: 0x60
-  __AUTH_CONST.__auth_got: 0x32e8
+  __AUTH_CONST.__objc_doubleobj: 0x50
+  __AUTH_CONST.__auth_got: 0x32e0
   __AUTH.__objc_data: 0x53c8
   __AUTH.__data: 0x2a70
   __DATA.__objc_ivar: 0x1a70

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 22544
-  Symbols:   23585
-  CStrings:  7957
+  Functions: 22598
+  Symbols:   23604
+  CStrings:  7966
 
Symbols:
+ -[MPCAudioAssetTypeSelector descriptionForExpectedAlbumAvailableDateTime:]
+ -[MPCAudioAssetTypeSelector preferredAudioAssetTypeForSongWithTrait:isStartItem:applyJitterTreatment:expectedAlbumAvailableDateTime:]
+ -[MPCAudioAssetTypeSelector stereoAssetTypeWithIsStartItem:applyJitterTreatment:explanation:]
+ -[MPCModelGenericAVItem _albumForPreReleaseTreatment]
+ -[MPCModelGenericAVItem _hasPendingDeferredLeaseAcquisition]
+ -[MPCModelGenericAVItem _setHasPendingDeferredLeaseAcquisition:]
+ -[MPCModelGenericAVItem expectedAlbumAvailableDateTime]
+ -[MPCModelGenericAVItem leaseAcquisitionJitterTime]
+ -[MPCModelGenericAVItem shouldApplyJitterTreatment]
+ -[_MPCPlaybackEnginePlayer _logTimeJumpForItem:fromTime:fromPrimaryTime:toTime:toPrimaryTime:userInitiated:timeStamp:]
+ -[_MPCPlaybackEnginePlayer _playbackDidStopForItem:source:reason:time:primaryTime:timeStamp:]
+ -[_MPCPlaybackEnginePlayer userSeekCompletedForItem:fromTime:fromPrimaryTime:toTime:toPrimaryTime:timeStamp:]
+ GCC_except_table3243
+ GCC_except_table3287
+ GCC_except_table3294
+ GCC_except_table3305
+ GCC_except_table3309
+ GCC_except_table3353
+ GCC_except_table3398
+ GCC_except_table3403
+ GCC_except_table3520
+ GCC_except_table3541
+ GCC_except_table3548
+ GCC_except_table3573
+ GCC_except_table3577
+ GCC_except_table3587
+ GCC_except_table3644
+ GCC_except_table3649
+ GCC_except_table3653
+ GCC_except_table3722
+ GCC_except_table3819
+ GCC_except_table3823
+ GCC_except_table3834
+ GCC_except_table3850
+ GCC_except_table3856
+ GCC_except_table3866
+ GCC_except_table3994
+ GCC_except_table4039
+ GCC_except_table4040
+ GCC_except_table4041
+ GCC_except_table4061
+ GCC_except_table4072
+ GCC_except_table4090
+ GCC_except_table4095
+ GCC_except_table4097
+ GCC_except_table4111
+ GCC_except_table4134
+ GCC_except_table4145
+ GCC_except_table4234
+ GCC_except_table4253
+ GCC_except_table4266
+ GCC_except_table4277
+ GCC_except_table4308
+ GCC_except_table4479
+ GCC_except_table4480
+ GCC_except_table4657
+ GCC_except_table4692
+ GCC_except_table4710
+ GCC_except_table4741
+ GCC_except_table4751
+ GCC_except_table4764
+ GCC_except_table4808
+ GCC_except_table4823
+ GCC_except_table4839
+ GCC_except_table4842
+ GCC_except_table4848
+ GCC_except_table4895
+ GCC_except_table4932
+ GCC_except_table5017
+ GCC_except_table5343
+ GCC_except_table5344
+ GCC_except_table5416
+ GCC_except_table5512
+ GCC_except_table5662
+ GCC_except_table5687
+ GCC_except_table5856
+ GCC_except_table5921
+ GCC_except_table5946
+ GCC_except_table5981
+ GCC_except_table5984
+ GCC_except_table5987
+ GCC_except_table6073
+ GCC_except_table6290
+ GCC_except_table6307
+ GCC_except_table6778
+ GCC_except_table7118
+ GCC_except_table7128
+ GCC_except_table7228
+ GCC_except_table7317
+ GCC_except_table7324
+ GCC_except_table7342
+ GCC_except_table7394
+ GCC_except_table7397
+ GCC_except_table7402
+ GCC_except_table7418
+ _MPCPlaybackEngineEventPayloadKeyInterstitialPrimaryPosition
+ _MPCPlaybackEngineEventPayloadKeyItemPrimaryEndPosition
+ _MPCPlaybackEngineEventPayloadKeyItemPrimaryStartPosition
+ _MPCPlaybackEngineEventPayloadKeyVideoRenderingModeDidChangePosition
+ _MPCPlaybackEngineEventPayloadKeyVideoRenderingModeDidChangePrimaryPosition
+ _MPModelPropertyAlbumExpectedReleaseDateComponents
+ ___58-[MPCModelGenericAVItem prepareForRate:completionHandler:]_block_invoke_4
+ ___58-[MPCModelGenericAVItem prepareForRate:completionHandler:]_block_invoke_5
+ _arc4random
+ _objc_msgSend$_albumForPreReleaseTreatment
+ _objc_msgSend$_hasPendingDeferredLeaseAcquisition
+ _objc_msgSend$_logTimeJumpForItem:fromTime:fromPrimaryTime:toTime:toPrimaryTime:userInitiated:timeStamp:
+ _objc_msgSend$_playbackDidStopForItem:source:reason:time:primaryTime:timeStamp:
+ _objc_msgSend$_setHasPendingDeferredLeaseAcquisition:
+ _objc_msgSend$descriptionForExpectedAlbumAvailableDateTime:
+ _objc_msgSend$expectedAlbumAvailableDateTime
+ _objc_msgSend$expectedReleaseDateComponents
+ _objc_msgSend$isHomePodRoute
+ _objc_msgSend$leaseAcquisitionJitterTime
+ _objc_msgSend$preferredAudioAssetTypeForSongWithTrait:isStartItem:applyJitterTreatment:expectedAlbumAvailableDateTime:
+ _objc_msgSend$primaryTime
+ _objc_msgSend$shouldApplyJitterTreatment
+ _objc_msgSend$stereoAssetTypeWithIsStartItem:applyJitterTreatment:explanation:
+ _objc_msgSend$userSeekCompletedForItem:fromTime:fromPrimaryTime:toTime:toPrimaryTime:timeStamp:
+ _symbolic Sb7success_______pSg4itemSdSg9startTimeAE012primaryStartD0Sd03endD0AE0e3EndD0SS10identifierSb7passive_____9timeStampt 17MediaPlaybackCore10PlayerItemP AA9EventTimeC
- -[MPCAudioAssetTypeSelector preferredAudioAssetTypeForSongWithTrait:isStartItem:]
- -[MPCAudioAssetTypeSelector stereoAssetTypeWithIsStartItem:explanation:]
- -[_MPCPlaybackEnginePlayer _logTimeJumpForItem:fromTime:toTime:userInitiated:timeStamp:]
- -[_MPCPlaybackEnginePlayer _playbackDidStopForItem:source:reason:time:timeStamp:]
- -[_MPCPlaybackEnginePlayer userSeekCompletedForItem:fromTime:toTime:timeStamp:]
- GCC_except_table3241
- GCC_except_table3283
- GCC_except_table3292
- GCC_except_table3303
- GCC_except_table3307
- GCC_except_table3345
- GCC_except_table3390
- GCC_except_table3395
- GCC_except_table3512
- GCC_except_table3533
- GCC_except_table3540
- GCC_except_table3565
- GCC_except_table3569
- GCC_except_table3579
- GCC_except_table3636
- GCC_except_table3641
- GCC_except_table3645
- GCC_except_table3714
- GCC_except_table3811
- GCC_except_table3815
- GCC_except_table3826
- GCC_except_table3842
- GCC_except_table3848
- GCC_except_table3858
- GCC_except_table3986
- GCC_except_table4031
- GCC_except_table4032
- GCC_except_table4033
- GCC_except_table4053
- GCC_except_table4064
- GCC_except_table4082
- GCC_except_table4087
- GCC_except_table4089
- GCC_except_table4103
- GCC_except_table4126
- GCC_except_table4137
- GCC_except_table4226
- GCC_except_table4245
- GCC_except_table4258
- GCC_except_table4269
- GCC_except_table4300
- GCC_except_table4471
- GCC_except_table4472
- GCC_except_table4649
- GCC_except_table4684
- GCC_except_table4686
- GCC_except_table4717
- GCC_except_table4743
- GCC_except_table4756
- GCC_except_table4800
- GCC_except_table4815
- GCC_except_table4831
- GCC_except_table4834
- GCC_except_table4840
- GCC_except_table4887
- GCC_except_table4924
- GCC_except_table5009
- GCC_except_table5335
- GCC_except_table5336
- GCC_except_table5408
- GCC_except_table5504
- GCC_except_table5654
- GCC_except_table5679
- GCC_except_table5848
- GCC_except_table5913
- GCC_except_table5938
- GCC_except_table5973
- GCC_except_table5976
- GCC_except_table5979
- GCC_except_table6065
- GCC_except_table6282
- GCC_except_table6299
- GCC_except_table6770
- GCC_except_table7110
- GCC_except_table7120
- GCC_except_table7210
- GCC_except_table7308
- GCC_except_table7315
- GCC_except_table7333
- GCC_except_table7384
- GCC_except_table7385
- GCC_except_table7388
- GCC_except_table7409
- ___107-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern _locked_detectVersionHashMismatchIfNeeded:childKey:]_block_invoke
- ___block_descriptor_40_e8_32r_e14_v24?0{?=qiI}8lr32l8
- ___swift_memcpy72_8
- ___swift_memcpy73_8
- _objc_msgSend$_logTimeJumpForItem:fromTime:toTime:userInitiated:timeStamp:
- _objc_msgSend$_playbackDidStopForItem:source:reason:time:timeStamp:
- _objc_msgSend$preferredAudioAssetTypeForSongWithTrait:isStartItem:
- _objc_msgSend$setShouldIgnoreExpiration:
- _objc_msgSend$stereoAssetTypeWithIsStartItem:explanation:
- _objc_msgSend$userSeekCompletedForItem:fromTime:toTime:timeStamp:
- _objc_release_x10
- _swift_retain_x11
- _symbolic Sb7success_______pSg4itemSdSg9startTimeSd03endD0SS10identifierSb7passive_____9timeStampt 17MediaPlaybackCore10PlayerItemP AA9EventTimeC
CStrings:
+ "4.AlbumAvailability"
+ "5.Outcome"
+ "Forcing HLS to apply jitter treatment"
+ "[PIA] %p store resolved a different versionHash than requested [using store version] identifier=%{public}@ requestedVersionHash=%{public}@"
+ "[SPIR:%{sonic:fourCC}u] populateSection:sectionIndex: | populated section [store resolved a different versionHash than requested; using store version] progressiveSection=%{public}@ requestedVersionHash=%{public}@ relatedProgressiveResults.count=%ld"
+ "interstitial-primary-position"
+ "item-primary-end-position"
+ "item-primary-start-position"
+ "lease-acquisition"
+ "primaryStartTime"
+ "success item startTime primaryStartTime endTime primaryEndTime identifier passive timeStamp "
+ "video-rendering-mode-did-change-position"
+ "video-rendering-mode-did-change-primary-position"
+ "|%{public}@ %{public}@ %2i %{public}@  │ primaryEnd: %0.2f"
+ "|%{public}@ %{public}@ %2i %{public}@  │ primaryStart: %0.2f"
+ "|%{public}@ %{public}@ %2i %{public}@  ╰ primaryPosition: %0.2f"
- "4.Outcome"
- "AccumulationVersionHashUnavailable"
- "Store did not provide versionHash '%@' for container %@"
- "[PIA] %p failing request [requested versionHash unavailable after load] identifier=%{public}@ versionHash=%{public}@"
- "[SPIR:%{sonic:fourCC}u] populateSection:sectionIndex: | container has no children with any versionHash [treating as empty, not a versionHash mismatch] progressiveSection=%{public}@"
- "[SPIR:%{sonic:fourCC}u] populateSection:sectionIndex: | failing request [store cannot provide requested versionHash] progressiveSection=%{public}@ versionHash=%{public}@"
- "success item startTime endTime identifier passive timeStamp "
```
