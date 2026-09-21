## MediaPlaybackCore

> `/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/Versions/A/MediaPlaybackCore`

```diff

-26200.26.36.301.0
-  __TEXT.__text: 0x3b784c
-  __TEXT.__objc_methlist: 0x16558
+26200.26.37.501.0
+  __TEXT.__text: 0x3b9d88
+  __TEXT.__objc_methlist: 0x165c8
   __TEXT.__dlopen_cstrs: 0xbe
-  __TEXT.__const: 0xd880
-  __TEXT.__cstring: 0x232f0
+  __TEXT.__const: 0xd9a0
+  __TEXT.__cstring: 0x233cf
   __TEXT.__constg_swiftt: 0x65f8
-  __TEXT.__swift5_typeref: 0x461a
+  __TEXT.__swift5_typeref: 0x4636
   __TEXT.__swift5_builtin: 0x578
-  __TEXT.__swift5_reflstr: 0x49a2
-  __TEXT.__swift5_fieldmd: 0x4830
+  __TEXT.__swift5_reflstr: 0x49b2
+  __TEXT.__swift5_fieldmd: 0x483c
   __TEXT.__swift5_assocty: 0xa20
-  __TEXT.__oslogstring: 0x42221
+  __TEXT.__oslogstring: 0x4228f
   __TEXT.__swift5_proto: 0x7a8
   __TEXT.__swift5_types: 0x44c
-  __TEXT.__swift5_capture: 0x6528
+  __TEXT.__swift5_capture: 0x6534
   __TEXT.__swift_as_entry: 0x2c0
   __TEXT.__swift_as_ret: 0x320
   __TEXT.__swift_as_cont: 0x8ac
-  __TEXT.__swift5_mpenum: 0xb8
+  __TEXT.__swift5_mpenum: 0xf8
   __TEXT.__swift5_protos: 0xc4
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x56c0
+  __TEXT.__gcc_except_tab: 0x5700
   __TEXT.__ustring: 0x4d4
-  __TEXT.__unwind_info: 0xd3a8
-  __TEXT.__eh_frame: 0x9d28
+  __TEXT.__unwind_info: 0xd3d0
+  __TEXT.__eh_frame: 0x9d30
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2c08
+  __DATA_CONST.__const: 0x2c30
   __DATA_CONST.__objc_classlist: 0xc20
   __DATA_CONST.__objc_catlist: 0x280
   __DATA_CONST.__objc_protolist: 0x6c8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xbf90
+  __DATA_CONST.__objc_selrefs: 0xbfd8
   __DATA_CONST.__objc_protorefs: 0x2c8
   __DATA_CONST.__objc_superrefs: 0x6b8
   __DATA_CONST.__objc_arraydata: 0x298
-  __DATA_CONST.__got: 0x2a70
-  __AUTH_CONST.__const: 0x1e588
-  __AUTH_CONST.__cfstring: 0x1e000
-  __AUTH_CONST.__objc_const: 0x30c50
-  __AUTH_CONST.__objc_intobj: 0x888
+  __DATA_CONST.__got: 0x2a78
+  __AUTH_CONST.__const: 0x1e558
+  __AUTH_CONST.__cfstring: 0x1e0c0
+  __AUTH_CONST.__objc_const: 0x30cd8
+  __AUTH_CONST.__objc_intobj: 0x8a0
   __AUTH_CONST.__objc_arrayobj: 0x288
   __AUTH_CONST.__objc_dictobj: 0xc8
-  __AUTH_CONST.__objc_doubleobj: 0x60
-  __AUTH_CONST.__auth_got: 0x26f8
+  __AUTH_CONST.__objc_doubleobj: 0x50
+  __AUTH_CONST.__auth_got: 0x2700
   __AUTH.__objc_data: 0x4808
   __AUTH.__data: 0x1ef0
   __DATA.__objc_ivar: 0x1a48

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 19149
-  Symbols:   22808
-  CStrings:  7580
+  Functions: 19158
+  Symbols:   22829
+  CStrings:  7589
 
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
+ GCC_except_table3336
+ GCC_except_table3377
+ GCC_except_table3381
+ GCC_except_table3391
+ GCC_except_table3402
+ GCC_except_table3406
+ GCC_except_table3456
+ GCC_except_table3501
+ GCC_except_table3506
+ GCC_except_table3622
+ GCC_except_table3643
+ GCC_except_table3650
+ GCC_except_table3677
+ GCC_except_table3681
+ GCC_except_table3691
+ GCC_except_table3748
+ GCC_except_table3755
+ GCC_except_table3759
+ GCC_except_table3830
+ GCC_except_table3933
+ GCC_except_table3937
+ GCC_except_table3949
+ GCC_except_table3965
+ GCC_except_table3972
+ GCC_except_table3982
+ GCC_except_table4110
+ GCC_except_table4155
+ GCC_except_table4156
+ GCC_except_table4157
+ GCC_except_table4177
+ GCC_except_table4188
+ GCC_except_table4206
+ GCC_except_table4211
+ GCC_except_table4213
+ GCC_except_table4249
+ GCC_except_table4261
+ GCC_except_table4350
+ GCC_except_table4369
+ GCC_except_table4384
+ GCC_except_table4393
+ GCC_except_table4424
+ GCC_except_table4595
+ GCC_except_table4596
+ GCC_except_table4775
+ GCC_except_table4810
+ GCC_except_table4828
+ GCC_except_table4844
+ GCC_except_table4856
+ GCC_except_table4866
+ GCC_except_table4877
+ GCC_except_table4890
+ GCC_except_table4937
+ GCC_except_table4952
+ GCC_except_table4969
+ GCC_except_table4974
+ GCC_except_table4980
+ GCC_except_table5025
+ GCC_except_table5060
+ GCC_except_table5143
+ GCC_except_table5500
+ GCC_except_table5602
+ GCC_except_table5752
+ GCC_except_table5777
+ GCC_except_table5949
+ GCC_except_table6015
+ GCC_except_table6040
+ GCC_except_table6075
+ GCC_except_table6078
+ GCC_except_table6081
+ GCC_except_table6167
+ GCC_except_table6384
+ GCC_except_table6401
+ GCC_except_table6852
+ GCC_except_table7196
+ GCC_except_table7206
+ GCC_except_table7306
+ GCC_except_table7395
+ GCC_except_table7402
+ GCC_except_table7420
+ GCC_except_table7472
+ GCC_except_table7475
+ GCC_except_table7480
+ GCC_except_table7496
+ _MPCPlaybackEngineEventPayloadKeyInterstitialPrimaryPosition
+ _MPCPlaybackEngineEventPayloadKeyItemPrimaryEndPosition
+ _MPCPlaybackEngineEventPayloadKeyItemPrimaryStartPosition
+ _MPCPlaybackEngineEventPayloadKeyVideoRenderingModeDidChangePosition
+ _MPCPlaybackEngineEventPayloadKeyVideoRenderingModeDidChangePrimaryPosition
+ _MPModelPropertyAlbumExpectedReleaseDateComponents
+ ___58-[MPCModelGenericAVItem prepareForRate:completionHandler:]_block_invoke_4
+ ___58-[MPCModelGenericAVItem prepareForRate:completionHandler:]_block_invoke_5
+ ___unnamed_10
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
- GCC_except_table3334
- GCC_except_table3375
- GCC_except_table3379
- GCC_except_table3389
- GCC_except_table3400
- GCC_except_table3404
- GCC_except_table3448
- GCC_except_table3493
- GCC_except_table3498
- GCC_except_table3614
- GCC_except_table3635
- GCC_except_table3642
- GCC_except_table3669
- GCC_except_table3673
- GCC_except_table3683
- GCC_except_table3740
- GCC_except_table3747
- GCC_except_table3751
- GCC_except_table3822
- GCC_except_table3925
- GCC_except_table3929
- GCC_except_table3941
- GCC_except_table3957
- GCC_except_table3964
- GCC_except_table3974
- GCC_except_table4102
- GCC_except_table4147
- GCC_except_table4148
- GCC_except_table4149
- GCC_except_table4169
- GCC_except_table4180
- GCC_except_table4198
- GCC_except_table4203
- GCC_except_table4205
- GCC_except_table4241
- GCC_except_table4253
- GCC_except_table4342
- GCC_except_table4361
- GCC_except_table4376
- GCC_except_table4385
- GCC_except_table4416
- GCC_except_table4587
- GCC_except_table4588
- GCC_except_table4767
- GCC_except_table4802
- GCC_except_table4804
- GCC_except_table4836
- GCC_except_table4848
- GCC_except_table4858
- GCC_except_table4869
- GCC_except_table4882
- GCC_except_table4929
- GCC_except_table4944
- GCC_except_table4961
- GCC_except_table4966
- GCC_except_table4972
- GCC_except_table5017
- GCC_except_table5052
- GCC_except_table5135
- GCC_except_table5492
- GCC_except_table5594
- GCC_except_table5744
- GCC_except_table5769
- GCC_except_table5941
- GCC_except_table6007
- GCC_except_table6032
- GCC_except_table6067
- GCC_except_table6070
- GCC_except_table6073
- GCC_except_table6159
- GCC_except_table6376
- GCC_except_table6393
- GCC_except_table6844
- GCC_except_table7188
- GCC_except_table7198
- GCC_except_table7288
- GCC_except_table7386
- GCC_except_table7393
- GCC_except_table7411
- GCC_except_table7462
- GCC_except_table7463
- GCC_except_table7466
- GCC_except_table7487
- ___107-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern _locked_detectVersionHashMismatchIfNeeded:childKey:]_block_invoke
- ___block_descriptor_40_e8_32r_e14_v24?0{?=qiI}8l
- ___swift_memcpy72_8
- ___swift_memcpy73_8
- ___unnamed_11
- _objc_msgSend$_logTimeJumpForItem:fromTime:toTime:userInitiated:timeStamp:
- _objc_msgSend$_playbackDidStopForItem:source:reason:time:timeStamp:
- _objc_msgSend$preferredAudioAssetTypeForSongWithTrait:isStartItem:
- _objc_msgSend$setShouldIgnoreExpiration:
- _objc_msgSend$stereoAssetTypeWithIsStartItem:explanation:
- _objc_msgSend$userSeekCompletedForItem:fromTime:toTime:timeStamp:
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
