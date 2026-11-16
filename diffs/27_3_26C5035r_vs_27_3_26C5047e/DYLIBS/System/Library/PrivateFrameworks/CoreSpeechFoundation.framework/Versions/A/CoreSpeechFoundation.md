## CoreSpeechFoundation

> `/System/Library/PrivateFrameworks/CoreSpeechFoundation.framework/Versions/A/CoreSpeechFoundation`

```diff

-3610.11.1.0.0
-  __TEXT.__text: 0xcd130
-  __TEXT.__objc_methlist: 0xdeb0
-  __TEXT.__const: 0xb98
+3610.19.5.0.0
+  __TEXT.__text: 0xcebe8
+  __TEXT.__objc_methlist: 0xe090
+  __TEXT.__const: 0xba8
   __TEXT.__dlopen_cstrs: 0x18c
   __TEXT.__constg_swiftt: 0x25c
   __TEXT.__swift5_typeref: 0x19d
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_types: 0x20
-  __TEXT.__cstring: 0x165b1
+  __TEXT.__cstring: 0x16853
   __TEXT.__swift5_reflstr: 0x174
   __TEXT.__swift5_assocty: 0x18
   __TEXT.__swift5_fieldmd: 0x180
   __TEXT.__swift5_proto: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__gcc_except_tab: 0x3db8
-  __TEXT.__oslogstring: 0x1158d
-  __TEXT.__unwind_info: 0x4930
+  __TEXT.__gcc_except_tab: 0x3e24
+  __TEXT.__oslogstring: 0x11a23
+  __TEXT.__unwind_info: 0x49b8
   __TEXT.__eh_frame: 0xe0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x10a0
-  __DATA_CONST.__objc_classlist: 0x790
+  __DATA_CONST.__objc_classlist: 0x7a8
   __DATA_CONST.__objc_catlist: 0x58
-  __DATA_CONST.__objc_protolist: 0x218
+  __DATA_CONST.__objc_protolist: 0x220
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x18
-  __DATA_CONST.__objc_selrefs: 0x75f8
+  __DATA_CONST.__objc_selrefs: 0x7730
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0x580
+  __DATA_CONST.__objc_superrefs: 0x588
   __DATA_CONST.__objc_arraydata: 0x1e0
-  __DATA_CONST.__got: 0xc88
-  __AUTH_CONST.__const: 0x3bf0
-  __AUTH_CONST.__cfstring: 0x9c40
-  __AUTH_CONST.__objc_const: 0x157e0
+  __DATA_CONST.__got: 0xca8
+  __AUTH_CONST.__const: 0x3c30
+  __AUTH_CONST.__cfstring: 0x9da0
+  __AUTH_CONST.__objc_const: 0x15bc8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_dictobj: 0x1e0
   __AUTH_CONST.__objc_intobj: 0x4e0
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_floatobj: 0x1a0
-  __AUTH_CONST.__auth_got: 0xef0
-  __AUTH.__objc_data: 0x3f8
+  __AUTH_CONST.__auth_got: 0xf10
+  __AUTH.__objc_data: 0x4e8
   __AUTH.__data: 0x18
-  __DATA.__objc_ivar: 0xe34
-  __DATA.__data: 0x1968
-  __DATA.__bss: 0x9f0
+  __DATA.__objc_ivar: 0xe60
+  __DATA.__data: 0x19c8
+  __DATA.__bss: 0xa10
   __DATA_DIRTY.__objc_data: 0x4860
   __DATA_DIRTY.__data: 0x310
   __DATA_DIRTY.__bss: 0x658

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5394
-  Symbols:   12371
-  CStrings:  3746
+  Functions: 5431
+  Symbols:   12492
+  CStrings:  3775
 
Symbols:
+ +[CSConfig audioProviderRetainedChannelBitsetForNumChannels:]
+ +[CSConfig audioProviderRetainedChannelBitsetForNumChannels:isHorseman:isPebble:horsemanDeviceType:pruningDisabled:fullRingDumpEnabled:]
+ +[CSFOnDeviceCachedIrPurgingUtils purgeCachedIrForAssetExcludingCurrentAsset:baseCachedIrDir:]
+ +[CSFOnDeviceCachedIrPurgingUtils removeCachedIrsForModelType:]
+ +[CSOnDeviceCompilationUtils onDeviceCompilationQueue]
+ +[CSUtils isAttendingOSDQuietModeEnabled]
+ +[CSUtils shouldReuseLiveEmbeddingForCCProfile]
+ -[CSAsset _optimizedOSDConfigPath]
+ -[CSAsset _osdConfigPathForLinwoodEnabled:]
+ -[CSAsset osdConfigPath]
+ -[CSAudioCircularBuffer initWithNumChannels:recordingDuration:samplingRate:audioTimeConverter:retainedChannelMask:]
+ -[CSAudioCircularBuffer numRetainedChannels]
+ -[CSAudioCircularBuffer prunedChannelReadCount]
+ -[CSAudioProvider isExclaveCursorRewindPending]
+ -[CSAudioProvider setIsExclaveCursorRewindPending:]
+ -[CSExclaveRecordClient setRaiseToSpeakDeviceOrientation:]
+ -[CSFMil2bnnsCompilationConfig _setOptionsFromDictionary:]
+ -[CSFPreferences isAudioProviderRingBufferPruningDisabled]
+ -[CSRequestMutex acquisitionTime]
+ -[CSRequestMutexAnalyticsEventManager .cxx_destruct]
+ -[CSRequestMutexAnalyticsEventManager _mhIdForTrackedRequest:requestId:mhId:requester:]
+ -[CSRequestMutexAnalyticsEventManager _trackedRequestForRequestId:]
+ -[CSRequestMutexAnalyticsEventManager acquisitionRefusedForRequestId:mhId:requester:resourceType:snapshot:]
+ -[CSRequestMutexAnalyticsEventManager acquisitionSucceededForRequestId:mhId:requester:resourceType:]
+ -[CSRequestMutexAnalyticsEventManager initWithEmitter:capacity:]
+ -[CSRequestMutexAnalyticsEventManager init]
+ -[CSRequestMutexAnalyticsSELFEmitter _emitMutexRequested:forMhId:]
+ -[CSRequestMutexAnalyticsSELFEmitter _mutexRequestedForRequester:requestedResourceType:successfullyAcquired:]
+ -[CSRequestMutexAnalyticsSELFEmitter emitFirstAcquisitionForMhId:requester:requestedResourceType:]
+ -[CSRequestMutexAnalyticsSELFEmitter emitFirstRefusalForMhId:requester:requestedResourceType:snapshot:]
+ -[CSRequestMutexController _acquisitionSnapshotAtHostTime:]
+ -[CSRequestMutexController _reportAcquisitionForOwner:requestId:mhId:resourceType:succeeded:snapshot:]
+ -[CSRequestMutexController initWithSingleTenancyEnforced:analyticsEventManager:]
+ -[CSRequestMutexController tryAcquireForLocalWithRequestId:mhId:resourceType:]
+ -[CSRequestMutexController tryAcquireForOwner:requestId:mhId:resourceType:]
+ -[CSRequestMutexTrackedRequest .cxx_destruct]
+ -[CSRequestMutexTrackedRequest acquired]
+ -[CSRequestMutexTrackedRequest mhId]
+ -[CSRequestMutexTrackedRequest refused]
+ -[CSRequestMutexTrackedRequest setAcquired:]
+ -[CSRequestMutexTrackedRequest setMhId:]
+ -[CSRequestMutexTrackedRequest setRefused:]
+ -[CSUncompressedAudioLogging _removeAudioFile]
+ GCC_except_table1000
+ GCC_except_table1015
+ GCC_except_table1016
+ GCC_except_table1022
+ GCC_except_table1027
+ GCC_except_table1036
+ GCC_except_table1037
+ GCC_except_table1038
+ GCC_except_table1052
+ GCC_except_table1122
+ GCC_except_table1124
+ GCC_except_table1125
+ GCC_except_table1135
+ GCC_except_table1471
+ GCC_except_table1502
+ GCC_except_table1592
+ GCC_except_table1593
+ GCC_except_table1594
+ GCC_except_table1595
+ GCC_except_table1596
+ GCC_except_table1597
+ GCC_except_table1606
+ GCC_except_table1609
+ GCC_except_table1617
+ GCC_except_table1621
+ GCC_except_table1623
+ GCC_except_table1625
+ GCC_except_table1629
+ GCC_except_table1807
+ GCC_except_table2017
+ GCC_except_table2018
+ GCC_except_table2022
+ GCC_except_table2025
+ GCC_except_table2028
+ GCC_except_table2034
+ GCC_except_table2042
+ GCC_except_table2043
+ GCC_except_table2109
+ GCC_except_table2114
+ GCC_except_table2179
+ GCC_except_table2232
+ GCC_except_table2235
+ GCC_except_table2236
+ GCC_except_table2244
+ GCC_except_table2256
+ GCC_except_table2269
+ GCC_except_table2312
+ GCC_except_table2330
+ GCC_except_table2413
+ GCC_except_table2513
+ GCC_except_table2550
+ GCC_except_table2723
+ GCC_except_table2727
+ GCC_except_table2803
+ GCC_except_table2816
+ GCC_except_table2821
+ GCC_except_table2823
+ GCC_except_table2845
+ GCC_except_table2847
+ GCC_except_table2865
+ GCC_except_table2886
+ GCC_except_table2936
+ GCC_except_table2940
+ GCC_except_table2999
+ GCC_except_table3001
+ GCC_except_table3002
+ GCC_except_table3173
+ GCC_except_table3313
+ GCC_except_table3321
+ GCC_except_table3331
+ GCC_except_table3340
+ GCC_except_table3343
+ GCC_except_table3345
+ GCC_except_table3346
+ GCC_except_table3385
+ GCC_except_table3391
+ GCC_except_table3441
+ GCC_except_table3534
+ GCC_except_table3546
+ GCC_except_table3552
+ GCC_except_table3559
+ GCC_except_table3571
+ GCC_except_table3596
+ GCC_except_table3597
+ GCC_except_table3598
+ GCC_except_table3599
+ GCC_except_table3624
+ GCC_except_table3637
+ GCC_except_table3833
+ GCC_except_table3907
+ GCC_except_table3949
+ GCC_except_table3950
+ GCC_except_table3983
+ GCC_except_table3984
+ GCC_except_table3986
+ GCC_except_table3989
+ GCC_except_table3990
+ GCC_except_table3991
+ GCC_except_table4012
+ GCC_except_table4019
+ GCC_except_table4020
+ GCC_except_table4021
+ GCC_except_table4029
+ GCC_except_table4053
+ GCC_except_table4079
+ GCC_except_table4100
+ GCC_except_table4121
+ GCC_except_table4122
+ GCC_except_table4123
+ GCC_except_table4124
+ GCC_except_table4225
+ GCC_except_table4231
+ GCC_except_table4232
+ GCC_except_table4235
+ GCC_except_table4237
+ GCC_except_table4238
+ GCC_except_table4241
+ GCC_except_table4244
+ GCC_except_table4251
+ GCC_except_table4257
+ GCC_except_table4258
+ GCC_except_table4262
+ GCC_except_table4268
+ GCC_except_table4275
+ GCC_except_table4280
+ GCC_except_table4281
+ GCC_except_table4284
+ GCC_except_table4285
+ GCC_except_table4286
+ GCC_except_table4288
+ GCC_except_table4289
+ GCC_except_table4291
+ GCC_except_table4292
+ GCC_except_table4293
+ GCC_except_table4294
+ GCC_except_table4322
+ GCC_except_table4372
+ GCC_except_table4378
+ GCC_except_table4434
+ GCC_except_table4435
+ GCC_except_table4442
+ GCC_except_table4443
+ GCC_except_table4444
+ GCC_except_table4445
+ GCC_except_table4447
+ GCC_except_table4448
+ GCC_except_table4470
+ GCC_except_table4472
+ GCC_except_table4473
+ GCC_except_table4474
+ GCC_except_table4476
+ GCC_except_table4477
+ GCC_except_table4478
+ GCC_except_table4479
+ GCC_except_table4481
+ GCC_except_table4482
+ GCC_except_table4483
+ GCC_except_table4507
+ GCC_except_table4509
+ GCC_except_table4512
+ GCC_except_table4514
+ GCC_except_table4516
+ GCC_except_table4518
+ GCC_except_table4520
+ GCC_except_table4521
+ GCC_except_table4523
+ GCC_except_table4525
+ GCC_except_table4528
+ GCC_except_table4530
+ GCC_except_table4532
+ GCC_except_table4534
+ GCC_except_table4541
+ GCC_except_table4554
+ GCC_except_table4555
+ GCC_except_table4557
+ GCC_except_table4560
+ GCC_except_table4564
+ GCC_except_table4571
+ GCC_except_table4573
+ GCC_except_table4577
+ GCC_except_table4578
+ GCC_except_table4608
+ GCC_except_table4768
+ GCC_except_table4775
+ GCC_except_table4858
+ GCC_except_table4930
+ GCC_except_table4940
+ GCC_except_table4988
+ GCC_except_table4989
+ GCC_except_table4990
+ GCC_except_table4992
+ GCC_except_table4993
+ GCC_except_table4996
+ GCC_except_table4998
+ GCC_except_table5000
+ GCC_except_table5001
+ GCC_except_table5003
+ GCC_except_table5005
+ GCC_except_table5006
+ GCC_except_table5008
+ GCC_except_table502
+ GCC_except_table5044
+ GCC_except_table5110
+ GCC_except_table5115
+ GCC_except_table5156
+ GCC_except_table5222
+ GCC_except_table590
+ GCC_except_table627
+ GCC_except_table749
+ GCC_except_table753
+ GCC_except_table758
+ GCC_except_table764
+ GCC_except_table920
+ GCC_except_table929
+ GCC_except_table991
+ GCC_except_table992
+ GCC_except_table999
+ _OBJC_CLASS_$_CSRequestMutexAnalyticsEventManager
+ _OBJC_CLASS_$_CSRequestMutexAnalyticsSELFEmitter
+ _OBJC_CLASS_$_CSRequestMutexTrackedRequest
+ _OBJC_CLASS_$_MHSchemaMHMutexRequested
+ _OBJC_IVAR_$_CSAsset._didResolveOptimizedOSDConfigPath
+ _OBJC_IVAR_$_CSAsset._optimizedOSDConfigPath
+ _OBJC_IVAR_$_CSAudioProvider._isExclaveCursorRewindPending
+ _OBJC_IVAR_$_CSRequestMutex._acquisitionTime
+ _OBJC_IVAR_$_CSRequestMutexAnalyticsEventManager._capacity
+ _OBJC_IVAR_$_CSRequestMutexAnalyticsEventManager._emitter
+ _OBJC_IVAR_$_CSRequestMutexAnalyticsEventManager._lock
+ _OBJC_IVAR_$_CSRequestMutexAnalyticsEventManager._trackedRequestIdsInInsertionOrder
+ _OBJC_IVAR_$_CSRequestMutexAnalyticsEventManager._trackedRequests
+ _OBJC_IVAR_$_CSRequestMutexController._analyticsEventManager
+ _OBJC_IVAR_$_CSRequestMutexTrackedRequest._acquired
+ _OBJC_IVAR_$_CSRequestMutexTrackedRequest._mhId
+ _OBJC_IVAR_$_CSRequestMutexTrackedRequest._refused
+ _OBJC_METACLASS_$_CSRequestMutexAnalyticsEventManager
+ _OBJC_METACLASS_$_CSRequestMutexAnalyticsSELFEmitter
+ _OBJC_METACLASS_$_CSRequestMutexTrackedRequest
+ __OBJC_$_INSTANCE_METHODS_CSRequestMutexAnalyticsEventManager
+ __OBJC_$_INSTANCE_METHODS_CSRequestMutexAnalyticsSELFEmitter
+ __OBJC_$_INSTANCE_METHODS_CSRequestMutexTrackedRequest
+ __OBJC_$_INSTANCE_VARIABLES_CSRequestMutexAnalyticsEventManager
+ __OBJC_$_INSTANCE_VARIABLES_CSRequestMutexTrackedRequest
+ __OBJC_$_PROP_LIST_CSRequestMutexAnalyticsSELFEmitter
+ __OBJC_$_PROP_LIST_CSRequestMutexTrackedRequest
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSRequestMutexAnalyticsEmitting
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSRequestMutexAnalyticsEmitting
+ __OBJC_$_PROTOCOL_REFS_CSRequestMutexAnalyticsEmitting
+ __OBJC_CLASS_PROTOCOLS_$_CSRequestMutexAnalyticsSELFEmitter
+ __OBJC_CLASS_RO_$_CSRequestMutexAnalyticsEventManager
+ __OBJC_CLASS_RO_$_CSRequestMutexAnalyticsSELFEmitter
+ __OBJC_CLASS_RO_$_CSRequestMutexTrackedRequest
+ __OBJC_LABEL_PROTOCOL_$_CSRequestMutexAnalyticsEmitting
+ __OBJC_METACLASS_RO_$_CSRequestMutexAnalyticsEventManager
+ __OBJC_METACLASS_RO_$_CSRequestMutexAnalyticsSELFEmitter
+ __OBJC_METACLASS_RO_$_CSRequestMutexTrackedRequest
+ __OBJC_PROTOCOL_$_CSRequestMutexAnalyticsEmitting
+ ___46-[CSUncompressedAudioLogging _removeAudioFile]_block_invoke
+ ___54+[CSOnDeviceCompilationUtils onDeviceCompilationQueue]_block_invoke
+ ___58-[CSFPreferences isAudioProviderRingBufferPruningDisabled]_block_invoke
+ ___94+[CSFOnDeviceCachedIrPurgingUtils purgeCachedIrForAssetExcludingCurrentAsset:baseCachedIrDir:]_block_invoke
+ _arc4random
+ _isAudioProviderRingBufferPruningDisabled.disabled
+ _isAudioProviderRingBufferPruningDisabled.onceToken
+ _objc_msgSend$_acquisitionSnapshotAtHostTime:
+ _objc_msgSend$_emitMutexRequested:forMhId:
+ _objc_msgSend$_mhIdForTrackedRequest:requestId:mhId:requester:
+ _objc_msgSend$_mutexRequestedForRequester:requestedResourceType:successfullyAcquired:
+ _objc_msgSend$_optimizedOSDConfigPath
+ _objc_msgSend$_osdConfigPathForLinwoodEnabled:
+ _objc_msgSend$_removeAudioFile
+ _objc_msgSend$_reportAcquisitionForOwner:requestId:mhId:resourceType:succeeded:snapshot:
+ _objc_msgSend$_setOptionsFromDictionary:
+ _objc_msgSend$_trackedRequestForRequestId:
+ _objc_msgSend$acquired
+ _objc_msgSend$acquisitionRefusedForRequestId:mhId:requester:resourceType:snapshot:
+ _objc_msgSend$acquisitionSucceededForRequestId:mhId:requester:resourceType:
+ _objc_msgSend$acquisitionTime
+ _objc_msgSend$audioProviderRetainedChannelBitsetForNumChannels:
+ _objc_msgSend$audioProviderRetainedChannelBitsetForNumChannels:isHorseman:isPebble:horsemanDeviceType:pruningDisabled:fullRingDumpEnabled:
+ _objc_msgSend$emitFirstAcquisitionForMhId:requester:requestedResourceType:
+ _objc_msgSend$emitFirstRefusalForMhId:requester:requestedResourceType:snapshot:
+ _objc_msgSend$initWithEmitter:capacity:
+ _objc_msgSend$initWithNumChannels:recordingDuration:samplingRate:audioTimeConverter:retainedChannelMask:
+ _objc_msgSend$initWithSingleTenancyEnforced:analyticsEventManager:
+ _objc_msgSend$isAudioProviderRingBufferPruningDisabled
+ _objc_msgSend$isMultiChannelAudioLoggingEnabled
+ _objc_msgSend$isSelfTriggerNearMissAudioLoggingEnabled
+ _objc_msgSend$mhId
+ _objc_msgSend$myriadFileLoggingEnabled
+ _objc_msgSend$numRetainedChannels
+ _objc_msgSend$onDeviceCompilationQueue
+ _objc_msgSend$refused
+ _objc_msgSend$setAcquired:
+ _objc_msgSend$setCurrentOwner:
+ _objc_msgSend$setHoldTimeOfASRResourceInMs:
+ _objc_msgSend$setHoldTimeOfAudioResourceInMs:
+ _objc_msgSend$setHoldTimeOfUnspecifiedResourceInMs:
+ _objc_msgSend$setMutexRequested:
+ _objc_msgSend$setRaiseToSpeakDeviceOrientation:
+ _objc_msgSend$setRefused:
+ _objc_msgSend$setRequestedResourceType:
+ _objc_msgSend$setRequester:
+ _objc_msgSend$setSuccessfullyAcquired:
+ _objc_msgSend$tryAcquireForLocalWithRequestId:mhId:resourceType:
+ _objc_msgSend$tryAcquireForOwner:requestId:mhId:resourceType:
+ _objc_sync_enter
+ _objc_sync_exit
+ _onDeviceCompilationQueue.onceToken
+ _onDeviceCompilationQueue.queue
+ _os_unfair_recursive_lock_lock
+ _rename
- +[CSFOnDeviceCachedIrPurgingUtils purgeCachedIrForTrialAssetExcludingCurrentAsset:baseCachedIrDir:]
- -[CSRequestMutexController tryAcquireForOwner:requestId:resourceType:]
- -[CSUncompressedAudioLogging _moveAudioLoggingToCollectionDirectory:]
- -[CSUncompressedAudioLogging _removeTmpAudioFile]
- -[CSUncompressedAudioLogging setTmpAudioFilePath:]
- -[CSUncompressedAudioLogging setTmpDirectory:]
- -[CSUncompressedAudioLogging tmpAudioFilePath]
- -[CSUncompressedAudioLogging tmpDirectory]
- GCC_except_table1011
- GCC_except_table1012
- GCC_except_table1013
- GCC_except_table1018
- GCC_except_table1019
- GCC_except_table1020
- GCC_except_table1030
- GCC_except_table1048
- GCC_except_table1118
- GCC_except_table1120
- GCC_except_table1121
- GCC_except_table1131
- GCC_except_table1465
- GCC_except_table1496
- GCC_except_table1579
- GCC_except_table1583
- GCC_except_table1584
- GCC_except_table1586
- GCC_except_table1587
- GCC_except_table1588
- GCC_except_table1599
- GCC_except_table1602
- GCC_except_table1603
- GCC_except_table1608
- GCC_except_table1611
- GCC_except_table1614
- GCC_except_table1616
- GCC_except_table1800
- GCC_except_table2013
- GCC_except_table2014
- GCC_except_table2020
- GCC_except_table2023
- GCC_except_table2024
- GCC_except_table2032
- GCC_except_table2038
- GCC_except_table2041
- GCC_except_table2107
- GCC_except_table2112
- GCC_except_table2177
- GCC_except_table2230
- GCC_except_table2231
- GCC_except_table2234
- GCC_except_table2240
- GCC_except_table2251
- GCC_except_table2264
- GCC_except_table2307
- GCC_except_table2325
- GCC_except_table2406
- GCC_except_table2506
- GCC_except_table2543
- GCC_except_table2714
- GCC_except_table2718
- GCC_except_table2794
- GCC_except_table2805
- GCC_except_table2807
- GCC_except_table2812
- GCC_except_table2829
- GCC_except_table2836
- GCC_except_table2856
- GCC_except_table2877
- GCC_except_table2927
- GCC_except_table2931
- GCC_except_table2990
- GCC_except_table2992
- GCC_except_table2993
- GCC_except_table3162
- GCC_except_table3302
- GCC_except_table3310
- GCC_except_table3320
- GCC_except_table3329
- GCC_except_table3332
- GCC_except_table3334
- GCC_except_table3335
- GCC_except_table3374
- GCC_except_table3380
- GCC_except_table3430
- GCC_except_table3523
- GCC_except_table3535
- GCC_except_table3541
- GCC_except_table3548
- GCC_except_table3560
- GCC_except_table3585
- GCC_except_table3586
- GCC_except_table3587
- GCC_except_table3588
- GCC_except_table3613
- GCC_except_table3626
- GCC_except_table3819
- GCC_except_table3879
- GCC_except_table3935
- GCC_except_table3936
- GCC_except_table3969
- GCC_except_table3970
- GCC_except_table3972
- GCC_except_table3975
- GCC_except_table3976
- GCC_except_table3977
- GCC_except_table3997
- GCC_except_table3999
- GCC_except_table4004
- GCC_except_table4005
- GCC_except_table4006
- GCC_except_table4038
- GCC_except_table4064
- GCC_except_table4085
- GCC_except_table4106
- GCC_except_table4107
- GCC_except_table4108
- GCC_except_table4109
- GCC_except_table4196
- GCC_except_table4197
- GCC_except_table4208
- GCC_except_table4210
- GCC_except_table4213
- GCC_except_table4216
- GCC_except_table4217
- GCC_except_table4220
- GCC_except_table4221
- GCC_except_table4222
- GCC_except_table4229
- GCC_except_table4230
- GCC_except_table4233
- GCC_except_table4247
- GCC_except_table4253
- GCC_except_table4254
- GCC_except_table4259
- GCC_except_table4265
- GCC_except_table4266
- GCC_except_table4270
- GCC_except_table4271
- GCC_except_table4273
- GCC_except_table4276
- GCC_except_table4277
- GCC_except_table4279
- GCC_except_table4307
- GCC_except_table4357
- GCC_except_table4363
- GCC_except_table4419
- GCC_except_table4420
- GCC_except_table4427
- GCC_except_table4428
- GCC_except_table4429
- GCC_except_table4430
- GCC_except_table4432
- GCC_except_table4433
- GCC_except_table4455
- GCC_except_table4457
- GCC_except_table4458
- GCC_except_table4459
- GCC_except_table4461
- GCC_except_table4462
- GCC_except_table4463
- GCC_except_table4464
- GCC_except_table4465
- GCC_except_table4466
- GCC_except_table4467
- GCC_except_table4468
- GCC_except_table4489
- GCC_except_table4491
- GCC_except_table4492
- GCC_except_table4493
- GCC_except_table4494
- GCC_except_table4496
- GCC_except_table4497
- GCC_except_table4499
- GCC_except_table4501
- GCC_except_table4502
- GCC_except_table4503
- GCC_except_table4505
- GCC_except_table4513
- GCC_except_table4515
- GCC_except_table4539
- GCC_except_table4540
- GCC_except_table4542
- GCC_except_table4543
- GCC_except_table4545
- GCC_except_table4547
- GCC_except_table4548
- GCC_except_table4549
- GCC_except_table4556
- GCC_except_table4593
- GCC_except_table4731
- GCC_except_table4738
- GCC_except_table4821
- GCC_except_table4893
- GCC_except_table4903
- GCC_except_table4951
- GCC_except_table4952
- GCC_except_table4953
- GCC_except_table4955
- GCC_except_table4956
- GCC_except_table4959
- GCC_except_table4961
- GCC_except_table4963
- GCC_except_table4964
- GCC_except_table4966
- GCC_except_table4968
- GCC_except_table4969
- GCC_except_table4971
- GCC_except_table5007
- GCC_except_table5073
- GCC_except_table5078
- GCC_except_table5119
- GCC_except_table5185
- GCC_except_table584
- GCC_except_table624
- GCC_except_table746
- GCC_except_table750
- GCC_except_table752
- GCC_except_table761
- GCC_except_table917
- GCC_except_table926
- GCC_except_table988
- GCC_except_table989
- GCC_except_table996
- _OBJC_IVAR_$_CSUncompressedAudioLogging._tmpAudioFilePath
- _OBJC_IVAR_$_CSUncompressedAudioLogging._tmpDirectory
- ___49-[CSUncompressedAudioLogging _removeTmpAudioFile]_block_invoke
- ___99+[CSFOnDeviceCachedIrPurgingUtils purgeCachedIrForTrialAssetExcludingCurrentAsset:baseCachedIrDir:]_block_invoke
- _objc_msgSend$_moveAudioLoggingToCollectionDirectory:
- _objc_msgSend$_removeTmpAudioFile
- _objc_msgSend$getOnDeviceCompilationCacheDirectoryForBenchmark
- _objc_msgSend$tmpAudioFilePath
- _objc_msgSend$tryAcquireForOwner:requestId:resourceType:
- _os_unfair_recursive_lock_lock_with_options
CStrings:
+ "%s #requestLock #analytics MHMutexRequested mhId: %@ { requester: %c, requestedResourceType: %s, successfullyAcquired: 0, currentOwner: %c, holdTimeOfUnspecifiedResourceInMs: %u, holdTimeOfAudioResourceInMs: %u, holdTimeOfASRResourceInMs: %u }"
+ "%s #requestLock #analytics MHMutexRequested mhId: %@ { requester: %c, requestedResourceType: %s, successfullyAcquired: 1 }"
+ "%s #requestLock #analytics mhId %@ isn't a UUID, skipping MHMutexRequested"
+ "%s #requestLock #analytics no mhId yet for local requestId %@, not reporting its acquire"
+ "%s #requestLock #analytics no mhId yet for local requestId %@, not reporting its refusal"
+ "%s %@: Audio sample does not exist : %@"
+ "%s %@: Failed to remove audio logging : %@"
+ "%s CSAudioProvider[%{public}@]:Circular buffer keeps %{public}lu of %{public}lu channels (retainedMask = 0x%{public}llx)"
+ "%s Invalid channel request: channelIdx=%{public}lu, numChannels=%{public}lu"
+ "%s Optimized OSD config not in asset, falling back to %{public}@"
+ "%s Read of pruned channel %{public}lu (retainedMask=0x%{public}llx, reads so far=%{public}llu)"
+ "%s asset specified as nil for purging"
+ "%s mil2bnns model config not found, using default options: %@"
+ "%s no cached ir directory for model type: %lu"
+ "%s numChannels: %{public}lu, retainedChannels: %{public}lu, retainedMask: 0x%{public}llx, recordingDuration: %{public}f, sampleRate: %{public}f"
+ "+[CSFOnDeviceCachedIrPurgingUtils purgeCachedIrForAssetExcludingCurrentAsset:baseCachedIrDir:]"
+ "+[CSFOnDeviceCachedIrPurgingUtils removeCachedIrsForModelType:]"
+ "-[CSAsset _optimizedOSDConfigPath]"
+ "-[CSAudioCircularBuffer initWithNumChannels:recordingDuration:samplingRate:audioTimeConverter:retainedChannelMask:]"
+ "-[CSRequestMutexAnalyticsEventManager acquisitionRefusedForRequestId:mhId:requester:resourceType:snapshot:]"
+ "-[CSRequestMutexAnalyticsEventManager acquisitionSucceededForRequestId:mhId:requester:resourceType:]"
+ "-[CSRequestMutexAnalyticsSELFEmitter _emitMutexRequested:forMhId:]"
+ "-[CSRequestMutexAnalyticsSELFEmitter emitFirstAcquisitionForMhId:requester:requestedResourceType:]"
+ "-[CSRequestMutexAnalyticsSELFEmitter emitFirstRefusalForMhId:requester:requestedResourceType:snapshot:]"
+ "-[CSRequestMutexController tryAcquireForOwner:requestId:mhId:resourceType:]"
+ "-[CSUncompressedAudioLogging _removeAudioFile]_block_invoke"
+ ".%u"
+ ".bnnsir"
+ "CSOnDeviceCompilationQueue"
+ "CoreSpeechMil2BnnsCache"
+ "Could not move compiled BNNSIR to %@: %s"
+ "Disable Audio Provider Ring Buffer Channel Pruning"
+ "_optimized"
+ "es-CL"
+ "es-ES"
+ "es-MX"
+ "es-US"
+ "pt-BR"
+ "pt-PT"
- "%s %@: Failed to move audio logging %@"
- "%s %@: Failed to remove audio logging in the tmp : %@"
- "%s numChannels: %{public}lu, recordingDuration: %{public}f, sampleRate: %{public}f"
- "+[CSFOnDeviceCachedIrPurgingUtils purgeCachedIrForTrialAssetExcludingCurrentAsset:baseCachedIrDir:]"
- "-[CSAudioCircularBuffer initWithNumChannels:recordingDuration:samplingRate:audioTimeConverter:]"
- "-[CSRequestMutexController tryAcquireForOwner:requestId:resourceType:]"
- "-[CSUncompressedAudioLogging _moveAudioLoggingToCollectionDirectory:]"
- "-[CSUncompressedAudioLogging _removeTmpAudioFile]_block_invoke"
- "CSOnDeviceCompilationHanlder"
- "config file not found for %@"
```
