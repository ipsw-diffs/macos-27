## HomeKit

> `/System/Library/PrivateFrameworks/HomeKit.framework/Versions/A/HomeKit`

```diff

-1520.2.3.0.2
-  __TEXT.__text: 0x4049f8
-  __TEXT.__objc_methlist: 0x288cc
-  __TEXT.__const: 0x8578
+1520.2.7.4.1
+  __TEXT.__text: 0x46b204
+  __TEXT.__objc_methlist: 0x28e24
+  __TEXT.__const: 0x10578
   __TEXT.__dlopen_cstrs: 0x3bb
-  __TEXT.__swift5_typeref: 0x26d1
-  __TEXT.__cstring: 0x2fe30
-  __TEXT.__constg_swiftt: 0x2308
-  __TEXT.__swift5_reflstr: 0x172f
-  __TEXT.__swift5_fieldmd: 0x1c44
-  __TEXT.__swift5_builtin: 0xb4
-  __TEXT.__swift5_assocty: 0x420
+  __TEXT.__swift5_typeref: 0x3983
+  __TEXT.__cstring: 0x31196
+  __TEXT.__constg_swiftt: 0x3564
+  __TEXT.__swift5_reflstr: 0x25ee
+  __TEXT.__swift5_fieldmd: 0x31b8
+  __TEXT.__swift5_builtin: 0xc8
+  __TEXT.__swift5_assocty: 0x850
   __TEXT.__swift5_capture: 0x988
   __TEXT.__swift5_protos: 0x38
-  __TEXT.__swift5_proto: 0x690
-  __TEXT.__swift5_types: 0x278
-  __TEXT.__swift_as_entry: 0x20c
-  __TEXT.__swift_as_ret: 0x250
-  __TEXT.__swift_as_cont: 0x474
-  __TEXT.__oslogstring: 0x56b5c
-  __TEXT.__swift5_mpenum: 0x18
-  __TEXT.__gcc_except_tab: 0x67a4
+  __TEXT.__swift5_proto: 0xd98
+  __TEXT.__swift5_types: 0x43c
+  __TEXT.__swift_as_entry: 0x274
+  __TEXT.__swift_as_ret: 0x2b8
+  __TEXT.__swift_as_cont: 0x53c
+  __TEXT.__oslogstring: 0x578a7
+  __TEXT.__swift5_mpenum: 0x20
+  __TEXT.__gcc_except_tab: 0x67cc
   __TEXT.__ustring: 0x50
-  __TEXT.__unwind_info: 0xfae0
-  __TEXT.__eh_frame: 0x8930
+  __TEXT.__unwind_info: 0x12290
+  __TEXT.__eh_frame: 0xbac0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x5b30
-  __DATA_CONST.__objc_classlist: 0x1340
+  __DATA_CONST.__const: 0x6178
+  __DATA_CONST.__objc_classlist: 0x1368
   __DATA_CONST.__objc_catlist: 0x108
   __DATA_CONST.__objc_protolist: 0x560
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe348
+  __DATA_CONST.__objc_selrefs: 0xe568
   __DATA_CONST.__objc_protorefs: 0x110
-  __DATA_CONST.__objc_superrefs: 0xf98
-  __DATA_CONST.__objc_arraydata: 0x13f0
-  __DATA_CONST.__got: 0x1e30
-  __AUTH_CONST.__const: 0xafb0
-  __AUTH_CONST.__cfstring: 0x2bf00
-  __AUTH_CONST.__objc_const: 0x48da8
-  __AUTH_CONST.__objc_intobj: 0x9a8
+  __DATA_CONST.__objc_superrefs: 0xfa8
+  __DATA_CONST.__objc_arraydata: 0x14c8
+  __DATA_CONST.__got: 0x1eb8
+  __AUTH_CONST.__const: 0xe078
+  __AUTH_CONST.__cfstring: 0x2c8a0
+  __AUTH_CONST.__objc_const: 0x49b88
+  __AUTH_CONST.__objc_intobj: 0x9f0
   __AUTH_CONST.__objc_dictobj: 0x848
-  __AUTH_CONST.__objc_arrayobj: 0x5d0
+  __AUTH_CONST.__objc_arrayobj: 0x618
   __AUTH_CONST.__objc_doubleobj: 0x70
-  __AUTH_CONST.__auth_got: 0x1908
-  __AUTH.__objc_data: 0x8e00
-  __AUTH.__data: 0x1dc8
-  __DATA.__objc_ivar: 0x282c
-  __DATA.__data: 0x57e8
-  __DATA.__bss: 0xc670
+  __AUTH_CONST.__auth_got: 0x1a48
+  __AUTH.__objc_data: 0x8fc0
+  __AUTH.__data: 0x3468
+  __DATA.__objc_ivar: 0x2894
+  __DATA.__data: 0x70d0
+  __DATA.__bss: 0x19d70
   __DATA.__common: 0x90
   __DATA_DIRTY.__objc_data: 0x3748
-  __DATA_DIRTY.__data: 0x180
-  __DATA_DIRTY.__bss: 0x220
+  __DATA_DIRTY.__data: 0x1a0
+  __DATA_DIRTY.__bss: 0x2a8
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
+  - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics
   - /System/Library/Frameworks/CoreLocation.framework/Versions/A/CoreLocation
   - /System/Library/Frameworks/CoreMedia.framework/Versions/A/CoreMedia
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 18223
-  Symbols:   32853
-  CStrings:  12400
+  Functions: 21197
+  Symbols:   33721
+  CStrings:  12586
 
Symbols:
+ +[HMCameraVideoSensor supportsSecureCoding]
+ +[HMCameraVideoSensorSettings supportsSecureCoding]
+ +[HMClientConnection areAnyHomeAccessoriesConfigured]
+ -[HMAccessory _handleSupportsHumiditySensorPriorityMessage:]
+ -[HMAccessory _handleSupportsTemperatureSensorPriorityMessage:]
+ -[HMAccessory homeAccessoryVariant]
+ -[HMAccessory notifyDelegateUpdatedSupportsTopCapPlusAndMinusUsingContext:]
+ -[HMAccessory notifyDelegateUpdatedSupportsTopCapTouchAndHoldUsingContext:]
+ -[HMAccessory setHomeAccessoryVariant:]
+ -[HMAccessory setSupportsAppleTVSiriSettings:]
+ -[HMAccessory setSupportsAssistantAccessControl:]
+ -[HMAccessory setSupportsTopCapPlusAndMinus:]
+ -[HMAccessory setSupportsTopCapTouchAndHold:]
+ -[HMAccessory supportsAppleTVSiriSettings]
+ -[HMAccessory supportsAssistantAccessControl]
+ -[HMAccessory supportsTopCapPlusAndMinus]
+ -[HMAccessory supportsTopCapTouchAndHold]
+ -[HMAccessory(ThreadManagement) repairThreadCommissioningWithCompletion:]
+ -[HMAccessory(ThreadManagement) repairWiFiCredentialsWithCompletion:]
+ -[HMAccessory(ThreadManagement) writePreferredWiFiListWithNetworks:completion:]
+ -[HMAccessoryCapabilities supportsAppleTVSiriSettings]
+ -[HMAccessoryCapabilities supportsTopCapPlusAndMinus]
+ -[HMAccessoryCapabilities supportsTopCapTouchAndHold]
+ -[HMBulletinBoardNotification leftUnsecuredThreshold]
+ -[HMBulletinBoardNotification setLeftUnsecuredThreshold:]
+ -[HMCameraClip setVideoSensorUUID:]
+ -[HMCameraClip videoSensorUUID]
+ -[HMCameraProfile setVideoSensorsDelegate:]
+ -[HMCameraProfile snapshotControlForVideoSensorWithUUID:]
+ -[HMCameraProfile streamControlForVideoSensorUUID:]
+ -[HMCameraProfile streamControlForVideoSensorWithUUID:]
+ -[HMCameraProfile userSettingsForVideoSensorWithUUID:]
+ -[HMCameraProfile videoSensorIsAvailable:]
+ -[HMCameraProfile videoSensorsDelegate]
+ -[HMCameraProfile videoSensors]
+ -[HMCameraSignificantEvent setVideoSensorUUID:]
+ -[HMCameraSignificantEvent videoSensorUUID]
+ -[HMCameraUserSettings _copyForVideoSensorUUID:]
+ -[HMCameraUserSettings setVideoSensorUUID:]
+ -[HMCameraUserSettings videoSensorUUID]
+ -[HMCameraVideoSensor .cxx_destruct]
+ -[HMCameraVideoSensor copyWithZone:]
+ -[HMCameraVideoSensor description]
+ -[HMCameraVideoSensor encodeWithCoder:]
+ -[HMCameraVideoSensor hash]
+ -[HMCameraVideoSensor initWithCoder:]
+ -[HMCameraVideoSensor initWithSensorType:sensorIntent:uniqueIdentifier:]
+ -[HMCameraVideoSensor initWithSensorType:sensorIntent:uniqueIdentifier:streamingServiceUUID:]
+ -[HMCameraVideoSensor isEqual:]
+ -[HMCameraVideoSensor sensorIntent]
+ -[HMCameraVideoSensor sensorType]
+ -[HMCameraVideoSensor streamingServiceUUID]
+ -[HMCameraVideoSensor uniqueIdentifier]
+ -[HMCameraVideoSensorSettings .cxx_destruct]
+ -[HMCameraVideoSensorSettings activityZonesIncludedForSignificantEventDetection]
+ -[HMCameraVideoSensorSettings activityZones]
+ -[HMCameraVideoSensorSettings copyWithZone:]
+ -[HMCameraVideoSensorSettings description]
+ -[HMCameraVideoSensorSettings encodeWithCoder:]
+ -[HMCameraVideoSensorSettings hash]
+ -[HMCameraVideoSensorSettings initWithActivityZones:activityZonesIncludedForSignificantEventDetection:recordingEventTriggers:]
+ -[HMCameraVideoSensorSettings initWithCoder:]
+ -[HMCameraVideoSensorSettings isEqual:]
+ -[HMCameraVideoSensorSettings recordingEventTriggers]
+ -[HMHome fetchAggregateClimateDataForDiagnosticsWithCompletion:]
+ -[HMHome hasOwnerAcknowledgedHomePodSiriOnboarding]
+ -[HMHome injectClimateDataWithType:thermostatUUID:value:completionHandler:]
+ -[HMHome setHasOwnerAcknowledgedHomePodSiriOnboarding:]
+ -[HMHome setHasOwnerAcknowledgedHomePodSiriOnboardingWithCompletionHandler:]
+ -[HMHome setWifiAutoRepairMode:]
+ -[HMHome updateWiFiAutoRepairMode:completion:]
+ -[HMHome wifiAutoRepairMode]
+ -[HMMediaGroupStageRequestPayload initWithDestinations:destinationControllersData:groups:removedGroupIdentifiers:metricType:timeToLive:]
+ -[HMMediaGroupStageRequestPayload timeToLive]
+ -[HMMediaGroupStagingManager startTimerWithTimeInterval:]
+ -[HMResidentCapabilities supportsHealthCheck]
+ -[HMResidentCapabilities supportsInstallerMode]
+ -[HMResidentCapabilities supportsMultiSensorCameraRecording]
+ -[HMResidentCapabilities supportsProInstallHAPTransfer]
+ -[_HMCameraProfile initWithUUID:services:mostRecentSnapshot:userSettings:videoSensors:]
+ -[_HMCameraProfile setVideoSensors:]
+ -[_HMCameraProfile snapshotControlForVideoSensorUUID:]
+ -[_HMCameraProfile snapshotControlsByVideoSensorUUID]
+ -[_HMCameraProfile streamControlForVideoSensorUUID:]
+ -[_HMCameraProfile streamControlsByVideoSensorUUID]
+ -[_HMCameraProfile updateVideoSensors:]
+ -[_HMCameraProfile videoSensorIsAvailable:]
+ -[_HMCameraProfile videoSensors]
+ -[_HMCameraSnapshotControl initWithCameraProfile:profileUniqueIdentifier:mostRecentSnapshot:videoSensorUUID:]
+ -[_HMCameraSnapshotControl setVideoSensorUUID:]
+ -[_HMCameraSnapshotControl videoSensorUUID]
+ -[_HMCameraStreamControl initWithCameraProfile:profileUniqueIdentifier:videoSensorUUID:]
+ -[_HMCameraStreamControl setVideoSensorUUID:]
+ -[_HMCameraStreamControl videoSensorUUID]
+ -[_HMCameraUserSettings setVideoSensorSettings:]
+ -[_HMCameraUserSettings settingsForVideoSensorWithUUID:]
+ -[_HMCameraUserSettings videoSensorSettings]
+ GCC_except_table10039
+ GCC_except_table10068
+ GCC_except_table10069
+ GCC_except_table10070
+ GCC_except_table10072
+ GCC_except_table10075
+ GCC_except_table10076
+ GCC_except_table10082
+ GCC_except_table10231
+ GCC_except_table10232
+ GCC_except_table10233
+ GCC_except_table10237
+ GCC_except_table10292
+ GCC_except_table10315
+ GCC_except_table10395
+ GCC_except_table10397
+ GCC_except_table10399
+ GCC_except_table10401
+ GCC_except_table10409
+ GCC_except_table10459
+ GCC_except_table10471
+ GCC_except_table10473
+ GCC_except_table10664
+ GCC_except_table10699
+ GCC_except_table10732
+ GCC_except_table10735
+ GCC_except_table10738
+ GCC_except_table10740
+ GCC_except_table10806
+ GCC_except_table10826
+ GCC_except_table10827
+ GCC_except_table10828
+ GCC_except_table10867
+ GCC_except_table10869
+ GCC_except_table10871
+ GCC_except_table10968
+ GCC_except_table10991
+ GCC_except_table10993
+ GCC_except_table10999
+ GCC_except_table11003
+ GCC_except_table11013
+ GCC_except_table11017
+ GCC_except_table11023
+ GCC_except_table11035
+ GCC_except_table11038
+ GCC_except_table11046
+ GCC_except_table11047
+ GCC_except_table11049
+ GCC_except_table11051
+ GCC_except_table11053
+ GCC_except_table11073
+ GCC_except_table11083
+ GCC_except_table11299
+ GCC_except_table11312
+ GCC_except_table11353
+ GCC_except_table11356
+ GCC_except_table11358
+ GCC_except_table11371
+ GCC_except_table11372
+ GCC_except_table11440
+ GCC_except_table11443
+ GCC_except_table11444
+ GCC_except_table11791
+ GCC_except_table11829
+ GCC_except_table11842
+ GCC_except_table12219
+ GCC_except_table12220
+ GCC_except_table12222
+ GCC_except_table12223
+ GCC_except_table12233
+ GCC_except_table12257
+ GCC_except_table12258
+ GCC_except_table12261
+ GCC_except_table12273
+ GCC_except_table12274
+ GCC_except_table12275
+ GCC_except_table12372
+ GCC_except_table12398
+ GCC_except_table12400
+ GCC_except_table12404
+ GCC_except_table12405
+ GCC_except_table12453
+ GCC_except_table12479
+ GCC_except_table12492
+ GCC_except_table12518
+ GCC_except_table12522
+ GCC_except_table12571
+ GCC_except_table12572
+ GCC_except_table12573
+ GCC_except_table12574
+ GCC_except_table12575
+ GCC_except_table12576
+ GCC_except_table12577
+ GCC_except_table12578
+ GCC_except_table12579
+ GCC_except_table12580
+ GCC_except_table12581
+ GCC_except_table12582
+ GCC_except_table12583
+ GCC_except_table12584
+ GCC_except_table12585
+ GCC_except_table12586
+ GCC_except_table12609
+ GCC_except_table12636
+ GCC_except_table12746
+ GCC_except_table12747
+ GCC_except_table12750
+ GCC_except_table12816
+ GCC_except_table12818
+ GCC_except_table12826
+ GCC_except_table12837
+ GCC_except_table12839
+ GCC_except_table12844
+ GCC_except_table12845
+ GCC_except_table12846
+ GCC_except_table13070
+ GCC_except_table13271
+ GCC_except_table13274
+ GCC_except_table13279
+ GCC_except_table13283
+ GCC_except_table13291
+ GCC_except_table13296
+ GCC_except_table13298
+ GCC_except_table13306
+ GCC_except_table13388
+ GCC_except_table13390
+ GCC_except_table13409
+ GCC_except_table13410
+ GCC_except_table13411
+ GCC_except_table13412
+ GCC_except_table13417
+ GCC_except_table13431
+ GCC_except_table13437
+ GCC_except_table13522
+ GCC_except_table13530
+ GCC_except_table13531
+ GCC_except_table13536
+ GCC_except_table13542
+ GCC_except_table13544
+ GCC_except_table13546
+ GCC_except_table13548
+ GCC_except_table13550
+ GCC_except_table13552
+ GCC_except_table13554
+ GCC_except_table13687
+ GCC_except_table13743
+ GCC_except_table13744
+ GCC_except_table13745
+ GCC_except_table13746
+ GCC_except_table13756
+ GCC_except_table13757
+ GCC_except_table13781
+ GCC_except_table13782
+ GCC_except_table13858
+ GCC_except_table13880
+ GCC_except_table13883
+ GCC_except_table14031
+ GCC_except_table14266
+ GCC_except_table14301
+ GCC_except_table14307
+ GCC_except_table14311
+ GCC_except_table14312
+ GCC_except_table14317
+ GCC_except_table14319
+ GCC_except_table14320
+ GCC_except_table14321
+ GCC_except_table14322
+ GCC_except_table14323
+ GCC_except_table14324
+ GCC_except_table14325
+ GCC_except_table14332
+ GCC_except_table14463
+ GCC_except_table14473
+ GCC_except_table14570
+ GCC_except_table14618
+ GCC_except_table14620
+ GCC_except_table14666
+ GCC_except_table14669
+ GCC_except_table14690
+ GCC_except_table14692
+ GCC_except_table14693
+ GCC_except_table1528
+ GCC_except_table1555
+ GCC_except_table1621
+ GCC_except_table1692
+ GCC_except_table1697
+ GCC_except_table1715
+ GCC_except_table1783
+ GCC_except_table1785
+ GCC_except_table1796
+ GCC_except_table1798
+ GCC_except_table1938
+ GCC_except_table1995
+ GCC_except_table2069
+ GCC_except_table2156
+ GCC_except_table2157
+ GCC_except_table2206
+ GCC_except_table2493
+ GCC_except_table2496
+ GCC_except_table2504
+ GCC_except_table2508
+ GCC_except_table2517
+ GCC_except_table2530
+ GCC_except_table2532
+ GCC_except_table2538
+ GCC_except_table2539
+ GCC_except_table2540
+ GCC_except_table2541
+ GCC_except_table3106
+ GCC_except_table3111
+ GCC_except_table3137
+ GCC_except_table3140
+ GCC_except_table3153
+ GCC_except_table3185
+ GCC_except_table3188
+ GCC_except_table3214
+ GCC_except_table3216
+ GCC_except_table3218
+ GCC_except_table3220
+ GCC_except_table3367
+ GCC_except_table3370
+ GCC_except_table3378
+ GCC_except_table3379
+ GCC_except_table3400
+ GCC_except_table3427
+ GCC_except_table3428
+ GCC_except_table3486
+ GCC_except_table3488
+ GCC_except_table3491
+ GCC_except_table3492
+ GCC_except_table3518
+ GCC_except_table3520
+ GCC_except_table3528
+ GCC_except_table3539
+ GCC_except_table3541
+ GCC_except_table3542
+ GCC_except_table3543
+ GCC_except_table3544
+ GCC_except_table3545
+ GCC_except_table3628
+ GCC_except_table3651
+ GCC_except_table3654
+ GCC_except_table3657
+ GCC_except_table3660
+ GCC_except_table3663
+ GCC_except_table3666
+ GCC_except_table3669
+ GCC_except_table3734
+ GCC_except_table3735
+ GCC_except_table3789
+ GCC_except_table3793
+ GCC_except_table3794
+ GCC_except_table3795
+ GCC_except_table3797
+ GCC_except_table3805
+ GCC_except_table3827
+ GCC_except_table3840
+ GCC_except_table3843
+ GCC_except_table3846
+ GCC_except_table3887
+ GCC_except_table3891
+ GCC_except_table3895
+ GCC_except_table3900
+ GCC_except_table3908
+ GCC_except_table3912
+ GCC_except_table3921
+ GCC_except_table3923
+ GCC_except_table4167
+ GCC_except_table4179
+ GCC_except_table4183
+ GCC_except_table4184
+ GCC_except_table4189
+ GCC_except_table4195
+ GCC_except_table4199
+ GCC_except_table4203
+ GCC_except_table4228
+ GCC_except_table4230
+ GCC_except_table4233
+ GCC_except_table4234
+ GCC_except_table4236
+ GCC_except_table4239
+ GCC_except_table4314
+ GCC_except_table4328
+ GCC_except_table4331
+ GCC_except_table4333
+ GCC_except_table4343
+ GCC_except_table4398
+ GCC_except_table4463
+ GCC_except_table4478
+ GCC_except_table4481
+ GCC_except_table4573
+ GCC_except_table4574
+ GCC_except_table4578
+ GCC_except_table4587
+ GCC_except_table4590
+ GCC_except_table4592
+ GCC_except_table4600
+ GCC_except_table4858
+ GCC_except_table4861
+ GCC_except_table4873
+ GCC_except_table4949
+ GCC_except_table4995
+ GCC_except_table5088
+ GCC_except_table5295
+ GCC_except_table5297
+ GCC_except_table5322
+ GCC_except_table5323
+ GCC_except_table5324
+ GCC_except_table5325
+ GCC_except_table5380
+ GCC_except_table5395
+ GCC_except_table5761
+ GCC_except_table5768
+ GCC_except_table5773
+ GCC_except_table5970
+ GCC_except_table6025
+ GCC_except_table6227
+ GCC_except_table6229
+ GCC_except_table6236
+ GCC_except_table6244
+ GCC_except_table6265
+ GCC_except_table6276
+ GCC_except_table6281
+ GCC_except_table6298
+ GCC_except_table6309
+ GCC_except_table6314
+ GCC_except_table6319
+ GCC_except_table6324
+ GCC_except_table6329
+ GCC_except_table6333
+ GCC_except_table6338
+ GCC_except_table6385
+ GCC_except_table6389
+ GCC_except_table6399
+ GCC_except_table6404
+ GCC_except_table6423
+ GCC_except_table6447
+ GCC_except_table6448
+ GCC_except_table6450
+ GCC_except_table6452
+ GCC_except_table6455
+ GCC_except_table6460
+ GCC_except_table6467
+ GCC_except_table6472
+ GCC_except_table6476
+ GCC_except_table6514
+ GCC_except_table6561
+ GCC_except_table6570
+ GCC_except_table6613
+ GCC_except_table6615
+ GCC_except_table6630
+ GCC_except_table6674
+ GCC_except_table6676
+ GCC_except_table6694
+ GCC_except_table6740
+ GCC_except_table6855
+ GCC_except_table6856
+ GCC_except_table6857
+ GCC_except_table6859
+ GCC_except_table6862
+ GCC_except_table6863
+ GCC_except_table6865
+ GCC_except_table7212
+ GCC_except_table7218
+ GCC_except_table7220
+ GCC_except_table7230
+ GCC_except_table7231
+ GCC_except_table7436
+ GCC_except_table7440
+ GCC_except_table7547
+ GCC_except_table7551
+ GCC_except_table7553
+ GCC_except_table7554
+ GCC_except_table7759
+ GCC_except_table7762
+ GCC_except_table7854
+ GCC_except_table7873
+ GCC_except_table7883
+ GCC_except_table8033
+ GCC_except_table8042
+ GCC_except_table8055
+ GCC_except_table8062
+ GCC_except_table8103
+ GCC_except_table8138
+ GCC_except_table8140
+ GCC_except_table8142
+ GCC_except_table8144
+ GCC_except_table8151
+ GCC_except_table8159
+ GCC_except_table8169
+ GCC_except_table8181
+ GCC_except_table8187
+ GCC_except_table8270
+ GCC_except_table8279
+ GCC_except_table8291
+ GCC_except_table8293
+ GCC_except_table8295
+ GCC_except_table8297
+ GCC_except_table8299
+ GCC_except_table8305
+ GCC_except_table8309
+ GCC_except_table8322
+ GCC_except_table8324
+ GCC_except_table8326
+ GCC_except_table8328
+ GCC_except_table8355
+ GCC_except_table8385
+ GCC_except_table8444
+ GCC_except_table8453
+ GCC_except_table8570
+ GCC_except_table8625
+ GCC_except_table8627
+ GCC_except_table8629
+ GCC_except_table8651
+ GCC_except_table8693
+ GCC_except_table8718
+ GCC_except_table8724
+ GCC_except_table8735
+ GCC_except_table8737
+ GCC_except_table8739
+ GCC_except_table8741
+ GCC_except_table8743
+ GCC_except_table8745
+ GCC_except_table8747
+ GCC_except_table8749
+ GCC_except_table8751
+ GCC_except_table8753
+ GCC_except_table8755
+ GCC_except_table8759
+ GCC_except_table8764
+ GCC_except_table8778
+ GCC_except_table8779
+ GCC_except_table8804
+ GCC_except_table8806
+ GCC_except_table8831
+ GCC_except_table8844
+ GCC_except_table8862
+ GCC_except_table9041
+ GCC_except_table9392
+ GCC_except_table9435
+ GCC_except_table9528
+ GCC_except_table9537
+ GCC_except_table9712
+ GCC_except_table9714
+ GCC_except_table9715
+ GCC_except_table9716
+ GCC_except_table9718
+ GCC_except_table9720
+ GCC_except_table9721
+ GCC_except_table9722
+ GCC_except_table9757
+ GCC_except_table9760
+ GCC_except_table9761
+ GCC_except_table9764
+ GCC_except_table9767
+ GCC_except_table9811
+ GCC_except_table9812
+ GCC_except_table9813
+ GCC_except_table9820
+ GCC_except_table9821
+ GCC_except_table9823
+ GCC_except_table9842
+ GCC_except_table9911
+ GCC_except_table9912
+ GCC_except_table9913
+ GCC_except_table9946
+ GCC_except_table9955
+ GCC_except_table9969
+ OBJC_IVAR_$_HMAccessory._homeAccessoryVariant
+ OBJC_IVAR_$_HMAccessory._supportsAppleTVSiriSettings
+ OBJC_IVAR_$_HMAccessory._supportsAssistantAccessControl
+ OBJC_IVAR_$_HMAccessory._supportsTopCapPlusAndMinus
+ OBJC_IVAR_$_HMAccessory._supportsTopCapTouchAndHold
+ OBJC_IVAR_$_HMBulletinBoardNotification._leftUnsecuredThreshold
+ OBJC_IVAR_$_HMCameraClip._videoSensorUUID
+ OBJC_IVAR_$_HMCameraProfile._videoSensorsDelegate
+ OBJC_IVAR_$_HMCameraSignificantEvent._videoSensorUUID
+ OBJC_IVAR_$_HMCameraUserSettings._videoSensorUUID
+ OBJC_IVAR_$_HMCameraVideoSensor._sensorIntent
+ OBJC_IVAR_$_HMCameraVideoSensor._sensorType
+ OBJC_IVAR_$_HMCameraVideoSensor._streamingServiceUUID
+ OBJC_IVAR_$_HMCameraVideoSensor._uniqueIdentifier
+ OBJC_IVAR_$_HMCameraVideoSensorSettings._activityZones
+ OBJC_IVAR_$_HMCameraVideoSensorSettings._activityZonesIncludedForSignificantEventDetection
+ OBJC_IVAR_$_HMCameraVideoSensorSettings._recordingEventTriggers
+ OBJC_IVAR_$_HMHome._hasOwnerAcknowledgedHomePodSiriOnboarding
+ OBJC_IVAR_$_HMHome._wifiAutoRepairMode
+ OBJC_IVAR_$_HMMediaGroupStageRequestPayload._timeToLive
+ OBJC_IVAR_$__HMCameraProfile._snapshotControlsByVideoSensorUUID
+ OBJC_IVAR_$__HMCameraProfile._streamControlsByVideoSensorUUID
+ OBJC_IVAR_$__HMCameraProfile._videoSensors
+ OBJC_IVAR_$__HMCameraSnapshotControl._videoSensorUUID
+ OBJC_IVAR_$__HMCameraStreamControl._videoSensorUUID
+ OBJC_IVAR_$__HMCameraUserSettings._videoSensorSettings
+ _HMAccessoryCategoryTypeHomeAccessory
+ _HMAccessoryFetchThermostatHumiditySensorPriorityStateMessage
+ _HMAccessoryFetchThermostatTemperatureSensorPriorityStateMessage
+ _HMAccessoryPreferredWiFiNetworksKey
+ _HMAccessoryRepairThreadCommissioningMessage
+ _HMAccessoryRepairWiFiListMessage
+ _HMAccessorySupportsAppleTVSiriSettingsCodingKey
+ _HMAccessorySupportsAssistantAccessControlCodingKey
+ _HMAccessorySupportsHumiditySensorPriorityKey
+ _HMAccessorySupportsHumiditySensorPriorityMessage
+ _HMAccessorySupportsTemperatureSensorPriorityKey
+ _HMAccessorySupportsTemperatureSensorPriorityMessage
+ _HMAccessorySupportsTopCapPlusAndMinusCodingKey
+ _HMAccessorySupportsTopCapTouchAndHoldCodingKey
+ _HMAccessoryThermostatHumiditySensorPriorityStateKey
+ _HMAccessoryThermostatServiceRoomUUIDsKey
+ _HMAccessoryThermostatTemperatureSensorPriorityStateKey
+ _HMAccessoryUpdateSupportsHumiditySensorPriorityMessage
+ _HMAccessoryUpdateSupportsTemperatureSensorPriorityMessage
+ _HMAccessoryUpdateThermostatHumiditySensorPriorityStateMessage
+ _HMAccessoryUpdateThermostatServiceRoomsMessage
+ _HMAccessoryUpdateThermostatTemperatureSensorPriorityStateMessage
+ _HMAccessoryUpdateUseThermostatServiceRoomsMessage
+ _HMAccessoryUseThermostatServiceRoomsKey
+ _HMAccessoryWritePreferredWiFiListMessage
+ _HMCameraProfileCodingKeyVideoSensors
+ _HMCameraStreamVideoSensorUUIDMessageKey
+ _HMCameraUserSettingsVideoSensorUUIDMessageKey
+ _HMDemoModeAccessoryTypeHomeAccessory1
+ _HMDemoModeAccessoryTypeHomeAccessory2
+ _HMFPairingKeyLength
+ _HMHomeAccessoriesConfiguredStatusKey
+ _HMHomeAccessoryVariantCodingKey
+ _HMHomeHasOwnerAcknowledgedHomePodSiriOnboardingValueCodingKey
+ _HMHomeInjectClimateDataMessage
+ _HMHomeInjectClimateDataThermostatUUIDKey
+ _HMHomeInjectClimateDataTypeKey
+ _HMHomeInjectClimateDataValueKey
+ _HMHomeManagerAreAnyHomeAccessoriesConfigured
+ _HMHomeManagerHomeAccessoryAddedNotification
+ _HMHomeSetHasOwnerAcknowledgedHomePodSiriOnboardingRequestKey
+ _HMHomeStagingHomeCodingKey
+ _HMHomeUpdateWiFiAutoRepairModeMessage
+ _HMHomeWiFiAutoRepairModeCodingKey
+ _HMHomeWiFiAutoRepairModeMessageKey
+ _HMMediaGroupStageRequestPayloadDefaultTimeToLive
+ _HMStagingHomeConfigurationKey
+ _HMWiFiAutoRepairModeAsString
+ _HomeUtilAggregateRoomsKey
+ _HomeUtilAggregateThermostatsKey
+ _HomeUtilFetchAggregateDataMessage
+ _HomeUtilHomeUUIDKey
+ _OBJC_CLASS_$_HMCameraVideoSensor
+ _OBJC_CLASS_$_HMCameraVideoSensorSettings
+ _OBJC_CLASS_$_UTTypeRecord
+ _OBJC_METACLASS_$_HMCameraVideoSensor
+ _OBJC_METACLASS_$_HMCameraVideoSensorSettings
+ __38-[HMCameraProfile mergeFromNewObject:]_block_invoke
+ __DATA__TtCV7HomeKit18HealthCheckContentP33_8FE500093EFD15B839F38564CCAD92A113_StorageClass
+ __DATA__TtCV7HomeKit29HealthCheckResponseTimeMetricP33_8FE500093EFD15B839F38564CCAD92A113_StorageClass
+ __DATA__TtCV7HomeKit33HealthCheckStabilityMetricsReportP33_8FE500093EFD15B839F38564CCAD92A113_StorageClass
+ __IVARS__TtCE7HomeKitCSo11HMAccessory15SwiftExtensions
+ __IVARS__TtCV7HomeKit18HealthCheckContentP33_8FE500093EFD15B839F38564CCAD92A113_StorageClass
+ __IVARS__TtCV7HomeKit29HealthCheckResponseTimeMetricP33_8FE500093EFD15B839F38564CCAD92A113_StorageClass
+ __IVARS__TtCV7HomeKit33HealthCheckStabilityMetricsReportP33_8FE500093EFD15B839F38564CCAD92A113_StorageClass
+ __METACLASS_DATA__TtCV7HomeKit18HealthCheckContentP33_8FE500093EFD15B839F38564CCAD92A113_StorageClass
+ __METACLASS_DATA__TtCV7HomeKit29HealthCheckResponseTimeMetricP33_8FE500093EFD15B839F38564CCAD92A113_StorageClass
+ __METACLASS_DATA__TtCV7HomeKit33HealthCheckStabilityMetricsReportP33_8FE500093EFD15B839F38564CCAD92A113_StorageClass
+ __OBJC_$_CLASS_METHODS_HMAccessory(HomeKit|DynamicAccessorySettingsAdapter|SwiftExtensions|HomeKit1|SiriEndpoint|Television|LightInternal|HMDoorbellChimeProfile|NetworkRouter|PendingConfiguration|Private|CUPeerIdentifier|Diagnostics|ThreadManagement|Shortcuts|Camera|CameraInternal|CHIP|NetworkConfiguration|Climate|Light|Media)
+ __OBJC_$_CLASS_METHODS_HMCameraVideoSensor
+ __OBJC_$_CLASS_METHODS_HMCameraVideoSensorSettings
+ __OBJC_$_CLASS_PROP_LIST_HMCameraVideoSensor
+ __OBJC_$_CLASS_PROP_LIST_HMCameraVideoSensorSettings
+ __OBJC_$_INSTANCE_METHODS_HMAccessory(HomeKit|DynamicAccessorySettingsAdapter|SwiftExtensions|HomeKit1|SiriEndpoint|Television|LightInternal|HMDoorbellChimeProfile|NetworkRouter|PendingConfiguration|Private|CUPeerIdentifier|Diagnostics|ThreadManagement|Shortcuts|Camera|CameraInternal|CHIP|NetworkConfiguration|Climate|Light|Media)
+ __OBJC_$_INSTANCE_METHODS_HMCameraVideoSensor
+ __OBJC_$_INSTANCE_METHODS_HMCameraVideoSensorSettings
+ __OBJC_$_INSTANCE_VARIABLES_HMCameraVideoSensor
+ __OBJC_$_INSTANCE_VARIABLES_HMCameraVideoSensorSettings
+ __OBJC_$_PROP_LIST_HMCameraVideoSensor
+ __OBJC_$_PROP_LIST_HMCameraVideoSensorSettings
+ __OBJC_CLASS_PROTOCOLS_$_HMCameraVideoSensor
+ __OBJC_CLASS_PROTOCOLS_$_HMCameraVideoSensorSettings
+ __OBJC_CLASS_RO_$_HMCameraVideoSensor
+ __OBJC_CLASS_RO_$_HMCameraVideoSensorSettings
+ __OBJC_METACLASS_RO_$_HMCameraVideoSensor
+ __OBJC_METACLASS_RO_$_HMCameraVideoSensorSettings
+ ___46-[HMHome updateWiFiAutoRepairMode:completion:]_block_invoke
+ ___64-[HMHome fetchAggregateClimateDataForDiagnosticsWithCompletion:]_block_invoke
+ ___69-[HMAccessory(ThreadManagement) repairWiFiCredentialsWithCompletion:]_block_invoke
+ ___73-[HMAccessory(ThreadManagement) repairThreadCommissioningWithCompletion:]_block_invoke
+ ___75-[HMAccessory notifyDelegateUpdatedSupportsTopCapPlusAndMinusUsingContext:]_block_invoke
+ ___75-[HMAccessory notifyDelegateUpdatedSupportsTopCapPlusAndMinusUsingContext:]_block_invoke_2
+ ___75-[HMAccessory notifyDelegateUpdatedSupportsTopCapTouchAndHoldUsingContext:]_block_invoke
+ ___75-[HMAccessory notifyDelegateUpdatedSupportsTopCapTouchAndHoldUsingContext:]_block_invoke_2
+ ___75-[HMHome injectClimateDataWithType:thermostatUUID:value:completionHandler:]_block_invoke
+ ___75-[HMHome injectClimateDataWithType:thermostatUUID:value:completionHandler:]_block_invoke_2
+ ___76-[HMHome setHasOwnerAcknowledgedHomePodSiriOnboardingWithCompletionHandler:]_block_invoke
+ ___79-[HMAccessory(ThreadManagement) writePreferredWiFiListWithNetworks:completion:]_block_invoke
+ ___swift_memcpy32_8
+ ___swift_memcpy48_8
+ __swift_get_extra_inhabitant_index.272Tm
+ __swift_get_extra_inhabitant_index.281Tm
+ __swift_get_extra_inhabitant_index.299Tm
+ __swift_get_extra_inhabitant_index.353Tm
+ __swift_get_extra_inhabitant_index.362Tm
+ __swift_store_extra_inhabitant_index.273Tm
+ __swift_store_extra_inhabitant_index.282Tm
+ __swift_store_extra_inhabitant_index.300Tm
+ __swift_store_extra_inhabitant_index.354Tm
+ __swift_store_extra_inhabitant_index.363Tm
+ _associated conformance 7HomeKit17HealthCheckReportV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit17HealthCheckReportV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0I0
+ _associated conformance 7HomeKit17HealthCheckReportV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit17HealthCheckReportVSHAASQ
+ _associated conformance 7HomeKit18HealthCheckContentV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit18HealthCheckContentV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0I0
+ _associated conformance 7HomeKit18HealthCheckContentV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit18HealthCheckContentVSHAASQ
+ _associated conformance 7HomeKit18HealthCheckVersionO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit18HealthCheckVersionO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit18HealthCheckVersionOSHAASQ
+ _associated conformance 7HomeKit18HealthCheckVersionOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit20HealthCheckDoorStateO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit20HealthCheckDoorStateO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit20HealthCheckDoorStateOSHAASQ
+ _associated conformance 7HomeKit20HealthCheckDoorStateOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit20HealthCheckErrorInfoV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit20HealthCheckErrorInfoV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0J0
+ _associated conformance 7HomeKit20HealthCheckErrorInfoV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit20HealthCheckErrorInfoVSHAASQ
+ _associated conformance 7HomeKit20HealthCheckLockStateO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit20HealthCheckLockStateO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit20HealthCheckLockStateOSHAASQ
+ _associated conformance 7HomeKit20HealthCheckLockStateOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit21HealthCheckErrorCountV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit21HealthCheckErrorCountV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0J0
+ _associated conformance 7HomeKit21HealthCheckErrorCountV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit21HealthCheckErrorCountVSHAASQ
+ _associated conformance 7HomeKit21HealthCheckLockReportV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit21HealthCheckLockReportV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0J0
+ _associated conformance 7HomeKit21HealthCheckLockReportV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit21HealthCheckLockReportVSHAASQ
+ _associated conformance 7HomeKit22HealthCheckACErrorCodeO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit22HealthCheckACErrorCodeO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit22HealthCheckACErrorCodeOSHAASQ
+ _associated conformance 7HomeKit22HealthCheckACErrorCodeOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit22HealthCheckPowerReportV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit22HealthCheckPowerReportV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0J0
+ _associated conformance 7HomeKit22HealthCheckPowerReportV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit22HealthCheckPowerReportVSHAASQ
+ _associated conformance 7HomeKit23HealthCheckBatteryStateO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit23HealthCheckBatteryStateO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit23HealthCheckBatteryStateOSHAASQ
+ _associated conformance 7HomeKit23HealthCheckBatteryStateOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit23HealthCheckCameraReportV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit23HealthCheckCameraReportV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0J0
+ _associated conformance 7HomeKit23HealthCheckCameraReportV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit23HealthCheckCameraReportVSHAASQ
+ _associated conformance 7HomeKit24HealthCheckChargingStateO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit24HealthCheckChargingStateO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit24HealthCheckChargingStateOSHAASQ
+ _associated conformance 7HomeKit24HealthCheckChargingStateOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit24HealthCheckResponseStateO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit24HealthCheckResponseStateO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit24HealthCheckResponseStateOSHAASQ
+ _associated conformance 7HomeKit24HealthCheckResponseStateOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit25HealthCheckDoorbellReportV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit25HealthCheckDoorbellReportV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0J0
+ _associated conformance 7HomeKit25HealthCheckDoorbellReportV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit25HealthCheckDoorbellReportVSHAASQ
+ _associated conformance 7HomeKit25HealthCheckFirmwareReportV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit25HealthCheckFirmwareReportV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0J0
+ _associated conformance 7HomeKit25HealthCheckFirmwareReportV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit25HealthCheckFirmwareReportVSHAASQ
+ _associated conformance 7HomeKit25HealthCheckOperatingStateO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit25HealthCheckOperatingStateO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit25HealthCheckOperatingStateOSHAASQ
+ _associated conformance 7HomeKit25HealthCheckOperatingStateOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit26HealthCheckBootReasonCountV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit26HealthCheckBootReasonCountV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0K0
+ _associated conformance 7HomeKit26HealthCheckBootReasonCountV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit26HealthCheckBootReasonCountVSHAASQ
+ _associated conformance 7HomeKit26HealthCheckMDNSRecordStateO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit26HealthCheckMDNSRecordStateO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit26HealthCheckMDNSRecordStateOSHAASQ
+ _associated conformance 7HomeKit26HealthCheckMDNSRecordStateOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit27HealthCheckThermostatReportV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit27HealthCheckThermostatReportV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0J0
+ _associated conformance 7HomeKit27HealthCheckThermostatReportV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit27HealthCheckThermostatReportVSHAASQ
+ _associated conformance 7HomeKit29HealthCheckCameraEnabledStateO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit29HealthCheckCameraEnabledStateO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit29HealthCheckCameraEnabledStateOSHAASQ
+ _associated conformance 7HomeKit29HealthCheckCameraEnabledStateOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit29HealthCheckReachabilityReportV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit29HealthCheckReachabilityReportV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0J0
+ _associated conformance 7HomeKit29HealthCheckReachabilityReportV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit29HealthCheckReachabilityReportVSHAASQ
+ _associated conformance 7HomeKit29HealthCheckResponseTimeMetricV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit29HealthCheckResponseTimeMetricV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0K0
+ _associated conformance 7HomeKit29HealthCheckResponseTimeMetricV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit29HealthCheckResponseTimeMetricVSHAASQ
+ _associated conformance 7HomeKit30HealthCheckStabilityBootReasonO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit30HealthCheckStabilityBootReasonO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit30HealthCheckStabilityBootReasonOSHAASQ
+ _associated conformance 7HomeKit30HealthCheckStabilityBootReasonOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit31HealthCheckStabilityTrendMetricV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit31HealthCheckStabilityTrendMetricV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0K0
+ _associated conformance 7HomeKit31HealthCheckStabilityTrendMetricV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit31HealthCheckStabilityTrendMetricVSHAASQ
+ _associated conformance 7HomeKit33HealthCheckLocalReachabilityStateO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit33HealthCheckLocalReachabilityStateO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit33HealthCheckLocalReachabilityStateOSHAASQ
+ _associated conformance 7HomeKit33HealthCheckLocalReachabilityStateOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit33HealthCheckStabilityMetricsReportV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit33HealthCheckStabilityMetricsReportV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0K0
+ _associated conformance 7HomeKit33HealthCheckStabilityMetricsReportV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit33HealthCheckStabilityMetricsReportVSHAASQ
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV17RouteReachabilityO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV17RouteReachabilityO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV17RouteReachabilityOSHAASQ
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV17RouteReachabilityOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0K0
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV9RouteInfoV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV9RouteInfoV21InternalSwiftProtobuf26_MessageImplementationBaseAaF0M0
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV9RouteInfoV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV9RouteInfoVSHAASQ
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV9RouteTypeO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV9RouteTypeO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV9RouteTypeOSHAASQ
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportV9RouteTypeOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 7HomeKit33HealthCheckWirelessInsightsReportVSHAASQ
+ _associated conformance 7HomeKit37HealthCheckReadWritePerformanceReportV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit37HealthCheckReadWritePerformanceReportV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0L0
+ _associated conformance 7HomeKit37HealthCheckReadWritePerformanceReportV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit37HealthCheckReadWritePerformanceReportVSHAASQ
+ _associated conformance 7HomeKit40HealthCheckOperatingStateAbnormalReasonsO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit40HealthCheckOperatingStateAbnormalReasonsO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit40HealthCheckOperatingStateAbnormalReasonsOSHAASQ
+ _associated conformance 7HomeKit40HealthCheckOperatingStateAbnormalReasonsOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit45HealthCheckThermostatDemandResponseEventStateO21InternalSwiftProtobuf4EnumAASH
+ _associated conformance 7HomeKit45HealthCheckThermostatDemandResponseEventStateO21InternalSwiftProtobuf4EnumAASY
+ _associated conformance 7HomeKit45HealthCheckThermostatDemandResponseEventStateOSHAASQ
+ _associated conformance 7HomeKit45HealthCheckThermostatDemandResponseEventStateOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance So11HMAccessoryC7HomeKitE11HealthCheckO14RequestMessageVAC19HMFMessagePrototypeOAfC0F7PayloadAiFP_AI0J0
+ _associated conformance So11HMAccessoryC7HomeKitE11HealthCheckO14RequestMessageVAC19HMFMessagePrototypeOAfC15ResponsePayloadAiFP_AI0K0
+ _associated conformance So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV10ThermostatOSHACSQ
+ _associated conformance So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV4LockOSHACSQ
+ _associated conformance So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV6CameraOSHACSQ
+ _associated conformance So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV7GeneralOSHACSQ
+ _associated conformance So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV8DoorbellOSHACSQ
+ _associated conformance So11HMAccessoryC7HomeKitE29ThermostatSensorPriorityStateOSHACSQ
+ _associated conformance So13HMHomeManagerC7HomeKitE15PairingIdentityV10CodingKeys33_19526A708D3E96D6A037A081C887B197LLOSHACSQ
+ _associated conformance So13HMHomeManagerC7HomeKitE15PairingIdentityV10CodingKeys33_19526A708D3E96D6A037A081C887B197LLOs0G3KeyACs23CustomStringConvertible
+ _associated conformance So13HMHomeManagerC7HomeKitE15PairingIdentityV10CodingKeys33_19526A708D3E96D6A037A081C887B197LLOs0G3KeyACs28CustomDebugStringConvertible
+ _associated conformance So13HMHomeManagerC7HomeKitE15PairingIdentityVSHACSQ
+ _associated conformance So13HMHomeManagerC7HomeKitE24ProvisionalConfigurationV10CodingKeys33_19526A708D3E96D6A037A081C887B197LLOSHACSQ
+ _associated conformance So13HMHomeManagerC7HomeKitE24ProvisionalConfigurationV10CodingKeys33_19526A708D3E96D6A037A081C887B197LLOs0G3KeyACs23CustomStringConvertible
+ _associated conformance So13HMHomeManagerC7HomeKitE24ProvisionalConfigurationV10CodingKeys33_19526A708D3E96D6A037A081C887B197LLOs0G3KeyACs28CustomDebugStringConvertible
+ _associated conformance So13HMHomeManagerC7HomeKitE24ProvisionalConfigurationVSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE10DeviceInfoV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE10DeviceInfoV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0G3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE10DeviceInfoV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0G3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO014StopPublishingF7MessageVAC19HMFMessagePrototypeO07RequestI0AC0L7PayloadAiJP_AI0M0
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO014StopPublishingF7MessageVAC19HMFMessagePrototypeO07RequestI0AC15ResponsePayloadAiJP_AI0N0
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageVAC19HMFMessagePrototypeO07RequestH0AC0K7PayloadAiJP_AI0L0
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageVAC19HMFMessagePrototypeO07RequestH0AC15ResponsePayloadAiJP_AI0M0
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV06DeviceF0V10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV06DeviceF0V10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0L3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV06DeviceF0V10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0L3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageVAC19HMFMessagePrototypeO07RequestH0AC0K7PayloadAiJP_AI0L0
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageVAC19HMFMessagePrototypeO07RequestH0AC15ResponsePayloadAiJP_AI0M0
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO010NoEligibleC10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0J3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO010NoEligibleC10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0J3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0H3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0H3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO16ActiveCodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO16ActiveCodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0I3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO16ActiveCodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0I3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO25LinwoodDisabledCodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0J3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO25LinwoodDisabledCodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0J3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0J3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0J3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO16ResumeCodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO16ResumeCodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO24DeleteMetadataCodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO24DeleteMetadataCodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0L3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO24DeleteMetadataCodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0L3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO24MarkShouldRollCodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0M3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO24MarkShouldRollCodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0M3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageVAC19HMFMessagePrototypeO07RequestH0AC0K7PayloadAiJP_AI0L0
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageVAC19HMFMessagePrototypeO07RequestH0AC15ResponsePayloadAiJP_AI0M0
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO16DumpStateMessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO16DumpStateMessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0L3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO16DumpStateMessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0L3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO16DumpStateMessageVAC19HMFMessagePrototypeO07RequestI0AC0L7PayloadAiJP_AI0M0
+ _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO16DumpStateMessageVAC19HMFMessagePrototypeO07RequestI0AC15ResponsePayloadAiJP_AI0N0
+ _associated conformance So18HMClientConnectionC7HomeKitE14DeviceIdentityVSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO06ServerF10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0H3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO06ServerF10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0H3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO06TargetB18RejectedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0I3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO06TargetB18RejectedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0I3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0G3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0G3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO26ConnectionFailedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0I3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO26ConnectionFailedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0I3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO30AuthenticationFailedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0I3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO30AuthenticationFailedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0I3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0G3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0G3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV15FailedAccessoryV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV15FailedAccessoryV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0I3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV15FailedAccessoryV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0I3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV15FailedAccessoryV6ReasonOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV15FailedAccessoryVSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV20TransferredAccessoryV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV20TransferredAccessoryV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0I3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV20TransferredAccessoryV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0I3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV20TransferredAccessoryVSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB14TransferResultVSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB17ConnectionDetailsV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB17ConnectionDetailsV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0G3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB17ConnectionDetailsV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0G3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE011ProvisionalB17ConnectionDetailsVSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV0H7PayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV0H7PayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0J3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV0H7PayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0J3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV15ResponsePayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV15ResponsePayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0K3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV15ResponsePayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0K3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestVAC19HMFMessagePrototypeO0H7MessageAC0H7PayloadAgHP_AG0L0
+ _associated conformance So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestVAC19HMFMessagePrototypeO0H7MessageAC15ResponsePayloadAgHP_AG0M0
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV0F7PayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV0F7PayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0H3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV0F7PayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0H3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0I3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0I3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0J3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0J3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO17FailureCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO17FailureCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0K3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO17FailureCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0K3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO17SuccessCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOSHACSQ
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO17SuccessCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0K3KeyACs23CustomStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO17SuccessCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLOs0K3KeyACs28CustomDebugStringConvertible
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestVAC19HMFMessagePrototypeO0F7MessageAC0F7PayloadAgHP_AG0J0
+ _associated conformance So6HMHomeC7HomeKitE019TransferProvisionalB7RequestVAC19HMFMessagePrototypeO0F7MessageAC15ResponsePayloadAgHP_AG0K0
+ _get_enum_tag_for_layout_string So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO
+ _kBulletinBoardNotificationLeftUnsecuredThresholdCodingKey
+ _memcmp
+ _objc_msgSend$accessoryDidUpdateSupportsAppleTVSiriSettings:
+ _objc_msgSend$accessoryDidUpdateSupportsTopCapPlusAndMinus:
+ _objc_msgSend$accessoryDidUpdateSupportsTopCapTouchAndHold:
+ _objc_msgSend$activityZonesIncludedForSignificantEventDetection
+ _objc_msgSend$cameraProfileDidUpdateVideoSensors:
+ _objc_msgSend$hasOwnerAcknowledgedHomePodSiriOnboarding
+ _objc_msgSend$homeAccessoryVariant
+ _objc_msgSend$homeDidSetHasOwnerAcknowledgedHomePodSiriOnboarding:
+ _objc_msgSend$initWithActivityZones:activityZonesIncludedForSignificantEventDetection:recordingEventTriggers:
+ _objc_msgSend$initWithBool:
+ _objc_msgSend$initWithCameraProfile:profileUniqueIdentifier:mostRecentSnapshot:videoSensorUUID:
+ _objc_msgSend$initWithCameraProfile:profileUniqueIdentifier:videoSensorUUID:
+ _objc_msgSend$initWithDestinations:destinationControllersData:groups:removedGroupIdentifiers:metricType:timeToLive:
+ _objc_msgSend$initWithSensorType:sensorIntent:uniqueIdentifier:streamingServiceUUID:
+ _objc_msgSend$initWithUUID:services:mostRecentSnapshot:userSettings:videoSensors:
+ _objc_msgSend$leftUnsecuredThreshold
+ _objc_msgSend$notifyDelegateUpdatedSupportsTopCapPlusAndMinusUsingContext:
+ _objc_msgSend$notifyDelegateUpdatedSupportsTopCapTouchAndHoldUsingContext:
+ _objc_msgSend$sensorIntent
+ _objc_msgSend$sensorType
+ _objc_msgSend$setHasOwnerAcknowledgedHomePodSiriOnboarding:
+ _objc_msgSend$setHomeAccessoryVariant:
+ _objc_msgSend$setLeftUnsecuredThreshold:
+ _objc_msgSend$setSupports3f8b1c7e4d2a:
+ _objc_msgSend$setSupports8a7c4e2f9b1d:
+ _objc_msgSend$setSupportsAppleTVSiriSettings:
+ _objc_msgSend$setSupportsHealthCheck:
+ _objc_msgSend$setSupportsMultiSensorCameraRecording:
+ _objc_msgSend$setSupportsTopCapPlusAndMinus:
+ _objc_msgSend$setSupportsTopCapTouchAndHold:
+ _objc_msgSend$setSupportsc7ab8e645f37:
+ _objc_msgSend$setSupportsdafedc977558:
+ _objc_msgSend$setSupportsf36a38d2aec7:
+ _objc_msgSend$setVideoSensorSettings:
+ _objc_msgSend$setVideoSensorUUID:
+ _objc_msgSend$setVideoSensors:
+ _objc_msgSend$setWifiAutoRepairMode:
+ _objc_msgSend$settingsForVideoSensorWithUUID:
+ _objc_msgSend$snapshotControlForVideoSensorUUID:
+ _objc_msgSend$snapshotControlsByVideoSensorUUID
+ _objc_msgSend$startTimerWithTimeInterval:
+ _objc_msgSend$streamControlForVideoSensorUUID:
+ _objc_msgSend$streamControlForVideoSensorWithUUID:
+ _objc_msgSend$streamControlsByVideoSensorUUID
+ _objc_msgSend$streamingServiceUUID
+ _objc_msgSend$supports3f8b1c7e4d2a
+ _objc_msgSend$supports8a7c4e2f9b1d
+ _objc_msgSend$supportsAppleTVSiriSettings
+ _objc_msgSend$supportsHealthCheck
+ _objc_msgSend$supportsInstallerMode
+ _objc_msgSend$supportsMultiSensorCameraRecording
+ _objc_msgSend$supportsProInstallHAPTransfer
+ _objc_msgSend$supportsTopCapPlusAndMinus
+ _objc_msgSend$supportsTopCapTouchAndHold
+ _objc_msgSend$supportsc7ab8e645f37
+ _objc_msgSend$supportsdafedc977558
+ _objc_msgSend$supportsf36a38d2aec7
+ _objc_msgSend$swiftHandleSupportsHumiditySensorPriorityMessage:
+ _objc_msgSend$swiftHandleSupportsTemperatureSensorPriorityMessage:
+ _objc_msgSend$timeToLive
+ _objc_msgSend$typeRecordWithIdentifier:
+ _objc_msgSend$updateVideoSensors:
+ _objc_msgSend$videoSensorIsAvailable:
+ _objc_msgSend$videoSensorSettings
+ _objc_msgSend$videoSensorUUID
+ _objc_msgSend$videoSensors
+ _objc_msgSend$videoSensorsDelegate
+ _objc_msgSend$wifiAutoRepairMode
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_dynamicCastClassUnconditional
+ _swift_willThrowTypedImpl
+ _symbolic SDySS_____G 7HomeKit33HealthCheckWirelessInsightsReportV9RouteInfoV
+ _symbolic SS3key______5valuet 7HomeKit33HealthCheckWirelessInsightsReportV9RouteInfoV
+ _symbolic SS_SDySSypGt
+ _symbolic SS______t 7HomeKit33HealthCheckWirelessInsightsReportV9RouteInfoV
+ _symbolic Say_____G 7HomeKit18HealthCheckVersionO
+ _symbolic Say_____G 7HomeKit20HealthCheckDoorStateO
+ _symbolic Say_____G 7HomeKit20HealthCheckLockStateO
+ _symbolic Say_____G 7HomeKit21HealthCheckErrorCountV
+ _symbolic Say_____G 7HomeKit22HealthCheckACErrorCodeO
+ _symbolic Say_____G 7HomeKit23HealthCheckBatteryStateO
+ _symbolic Say_____G 7HomeKit24HealthCheckChargingStateO
+ _symbolic Say_____G 7HomeKit24HealthCheckResponseStateO
+ _symbolic Say_____G 7HomeKit25HealthCheckOperatingStateO
+ _symbolic Say_____G 7HomeKit26HealthCheckBootReasonCountV
+ _symbolic Say_____G 7HomeKit26HealthCheckMDNSRecordStateO
+ _symbolic Say_____G 7HomeKit29HealthCheckCameraEnabledStateO
+ _symbolic Say_____G 7HomeKit30HealthCheckStabilityBootReasonO
+ _symbolic Say_____G 7HomeKit33HealthCheckLocalReachabilityStateO
+ _symbolic Say_____G 7HomeKit33HealthCheckWirelessInsightsReportV17RouteReachabilityO
+ _symbolic Say_____G 7HomeKit33HealthCheckWirelessInsightsReportV9RouteTypeO
+ _symbolic Say_____G 7HomeKit40HealthCheckOperatingStateAbnormalReasonsO
+ _symbolic Say_____G 7HomeKit45HealthCheckThermostatDemandResponseEventStateO
+ _symbolic Say_____G So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV06DeviceF0V
+ _symbolic Say_____G So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV15FailedAccessoryV
+ _symbolic Say_____G So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV20TransferredAccessoryV
+ _symbolic Sb5pause_t
+ _symbolic ScCySo6HMHomeC______pG s5ErrorP
+ _symbolic Shy_____G So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV10ThermostatO
+ _symbolic Shy_____G So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV4LockO
+ _symbolic Shy_____G So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV6CameraO
+ _symbolic Shy_____G So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV7GeneralO
+ _symbolic Shy_____G So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV8DoorbellO
+ _symbolic _____ 7HomeKit17HealthCheckReportV
+ _symbolic _____ 7HomeKit18HealthCheckContentV
+ _symbolic _____ 7HomeKit18HealthCheckContentV13_StorageClass33_8FE500093EFD15B839F38564CCAD92A1LLC
+ _symbolic _____ 7HomeKit18HealthCheckVersionO
+ _symbolic _____ 7HomeKit20HealthCheckDoorStateO
+ _symbolic _____ 7HomeKit20HealthCheckErrorInfoV
+ _symbolic _____ 7HomeKit20HealthCheckLockStateO
+ _symbolic _____ 7HomeKit21HealthCheckErrorCountV
+ _symbolic _____ 7HomeKit21HealthCheckLockReportV
+ _symbolic _____ 7HomeKit22HealthCheckACErrorCodeO
+ _symbolic _____ 7HomeKit22HealthCheckPowerReportV
+ _symbolic _____ 7HomeKit23HealthCheckBatteryStateO
+ _symbolic _____ 7HomeKit23HealthCheckCameraReportV
+ _symbolic _____ 7HomeKit24HealthCheckChargingStateO
+ _symbolic _____ 7HomeKit24HealthCheckResponseStateO
+ _symbolic _____ 7HomeKit25HealthCheckDoorbellReportV
+ _symbolic _____ 7HomeKit25HealthCheckFirmwareReportV
+ _symbolic _____ 7HomeKit25HealthCheckOperatingStateO
+ _symbolic _____ 7HomeKit26HealthCheckBootReasonCountV
+ _symbolic _____ 7HomeKit26HealthCheckMDNSRecordStateO
+ _symbolic _____ 7HomeKit27HealthCheckThermostatReportV
+ _symbolic _____ 7HomeKit29HealthCheckCameraEnabledStateO
+ _symbolic _____ 7HomeKit29HealthCheckReachabilityReportV
+ _symbolic _____ 7HomeKit29HealthCheckResponseTimeMetricV
+ _symbolic _____ 7HomeKit29HealthCheckResponseTimeMetricV13_StorageClass33_8FE500093EFD15B839F38564CCAD92A1LLC
+ _symbolic _____ 7HomeKit30HealthCheckStabilityBootReasonO
+ _symbolic _____ 7HomeKit31HealthCheckStabilityTrendMetricV
+ _symbolic _____ 7HomeKit33HealthCheckLocalReachabilityStateO
+ _symbolic _____ 7HomeKit33HealthCheckStabilityMetricsReportV
+ _symbolic _____ 7HomeKit33HealthCheckStabilityMetricsReportV13_StorageClass33_8FE500093EFD15B839F38564CCAD92A1LLC
+ _symbolic _____ 7HomeKit33HealthCheckWirelessInsightsReportV
+ _symbolic _____ 7HomeKit33HealthCheckWirelessInsightsReportV17RouteReachabilityO
+ _symbolic _____ 7HomeKit33HealthCheckWirelessInsightsReportV9RouteInfoV
+ _symbolic _____ 7HomeKit33HealthCheckWirelessInsightsReportV9RouteTypeO
+ _symbolic _____ 7HomeKit37HealthCheckReadWritePerformanceReportV
+ _symbolic _____ 7HomeKit40HealthCheckOperatingStateAbnormalReasonsO
+ _symbolic _____ 7HomeKit45HealthCheckThermostatDemandResponseEventStateO
+ _symbolic _____ So11HMAccessoryC7HomeKitE11HealthCheckO
+ _symbolic _____ So11HMAccessoryC7HomeKitE11HealthCheckO0dE15ResponsePayloadV
+ _symbolic _____ So11HMAccessoryC7HomeKitE11HealthCheckO14RequestMessageV
+ _symbolic _____ So11HMAccessoryC7HomeKitE11HealthCheckO14RequestMessageV0F7PayloadV
+ _symbolic _____ So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV
+ _symbolic _____ So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV10ThermostatO
+ _symbolic _____ So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV4LockO
+ _symbolic _____ So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV6CameraO
+ _symbolic _____ So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV7GeneralO
+ _symbolic _____ So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV8DoorbellO
+ _symbolic _____ So11HMAccessoryC7HomeKitE29ThermostatSensorPriorityStateO
+ _symbolic _____ So13HMHomeManagerC7HomeKitE15PairingIdentityV
+ _symbolic _____ So13HMHomeManagerC7HomeKitE15PairingIdentityV10CodingKeys33_19526A708D3E96D6A037A081C887B197LLO
+ _symbolic _____ So13HMHomeManagerC7HomeKitE24ProvisionalConfigurationV
+ _symbolic _____ So13HMHomeManagerC7HomeKitE24ProvisionalConfigurationV10CodingKeys33_19526A708D3E96D6A037A081C887B197LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE10DeviceInfoV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE10DeviceInfoV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO014StopPublishingF7MessageV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV14RequestPayloadV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV14RequestPayloadV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV06DeviceF0V
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV06DeviceF0V10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO010NoEligibleC10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO16ActiveCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO0C5StateO25LinwoodDisabledCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV14RequestPayloadV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO16ResumeCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO24DeleteMetadataCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO24MarkShouldRollCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO16DumpStateMessageV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO16DumpStateMessageV15ResponsePayloadV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO16DumpStateMessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE14DeviceIdentityV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE17RemoteContextInfoV
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO06ServerF10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO06TargetB18RejectedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO26ConnectionFailedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB13TransferErrorO30AuthenticationFailedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV15FailedAccessoryV
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV15FailedAccessoryV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV15FailedAccessoryV6ReasonO
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV20TransferredAccessoryV
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV20TransferredAccessoryV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB17ConnectionDetailsV
+ _symbolic _____ So6HMHomeC7HomeKitE011ProvisionalB17ConnectionDetailsV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV
+ _symbolic _____ So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV0H7PayloadV
+ _symbolic _____ So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV0H7PayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV15ResponsePayloadV
+ _symbolic _____ So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV15ResponsePayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV
+ _symbolic _____ So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV0F7PayloadV
+ _symbolic _____ So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV0F7PayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV
+ _symbolic _____ So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO
+ _symbolic _____ So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO17FailureCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____ So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO17SuccessCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____14homeIdentifier_t 10Foundation4UUIDV
+ _symbolic _____Sg 21InternalSwiftProtobuf07Google_C10_TimestampV
+ _symbolic _____Sg 21InternalSwiftProtobuf07Google_C9_DurationV
+ _symbolic _____Sg 7HomeKit17HealthCheckReportV
+ _symbolic _____Sg 7HomeKit18HealthCheckContentV
+ _symbolic _____Sg 7HomeKit18HealthCheckVersionO
+ _symbolic _____Sg 7HomeKit20HealthCheckDoorStateO
+ _symbolic _____Sg 7HomeKit20HealthCheckErrorInfoV
+ _symbolic _____Sg 7HomeKit20HealthCheckLockStateO
+ _symbolic _____Sg 7HomeKit21HealthCheckLockReportV
+ _symbolic _____Sg 7HomeKit22HealthCheckPowerReportV
+ _symbolic _____Sg 7HomeKit23HealthCheckBatteryStateO
+ _symbolic _____Sg 7HomeKit23HealthCheckCameraReportV
+ _symbolic _____Sg 7HomeKit24HealthCheckChargingStateO
+ _symbolic _____Sg 7HomeKit24HealthCheckResponseStateO
+ _symbolic _____Sg 7HomeKit25HealthCheckDoorbellReportV
+ _symbolic _____Sg 7HomeKit25HealthCheckFirmwareReportV
+ _symbolic _____Sg 7HomeKit25HealthCheckOperatingStateO
+ _symbolic _____Sg 7HomeKit26HealthCheckMDNSRecordStateO
+ _symbolic _____Sg 7HomeKit27HealthCheckThermostatReportV
+ _symbolic _____Sg 7HomeKit29HealthCheckCameraEnabledStateO
+ _symbolic _____Sg 7HomeKit29HealthCheckReachabilityReportV
+ _symbolic _____Sg 7HomeKit29HealthCheckResponseTimeMetricV
+ _symbolic _____Sg 7HomeKit30HealthCheckStabilityBootReasonO
+ _symbolic _____Sg 7HomeKit31HealthCheckStabilityTrendMetricV
+ _symbolic _____Sg 7HomeKit33HealthCheckLocalReachabilityStateO
+ _symbolic _____Sg 7HomeKit33HealthCheckStabilityMetricsReportV
+ _symbolic _____Sg 7HomeKit33HealthCheckWirelessInsightsReportV
+ _symbolic _____Sg 7HomeKit33HealthCheckWirelessInsightsReportV17RouteReachabilityO
+ _symbolic _____Sg 7HomeKit33HealthCheckWirelessInsightsReportV9RouteTypeO
+ _symbolic _____Sg 7HomeKit37HealthCheckReadWritePerformanceReportV
+ _symbolic _____Sg 7HomeKit45HealthCheckThermostatDemandResponseEventStateO
+ _symbolic _____Sg s5Int32V
+ _symbolic _____Sg s6UInt32V
+ _symbolic _____Sg_ABt 21InternalSwiftProtobuf07Google_C10_TimestampV
+ _symbolic _____Sg_ABt 21InternalSwiftProtobuf07Google_C9_DurationV
+ _symbolic _____Sg_ABt 7HomeKit18HealthCheckContentV
+ _symbolic _____Sg_ABt 7HomeKit20HealthCheckErrorInfoV
+ _symbolic _____Sg_ABt 7HomeKit21HealthCheckLockReportV
+ _symbolic _____Sg_ABt 7HomeKit22HealthCheckPowerReportV
+ _symbolic _____Sg_ABt 7HomeKit23HealthCheckCameraReportV
+ _symbolic _____Sg_ABt 7HomeKit25HealthCheckDoorbellReportV
+ _symbolic _____Sg_ABt 7HomeKit25HealthCheckFirmwareReportV
+ _symbolic _____Sg_ABt 7HomeKit27HealthCheckThermostatReportV
+ _symbolic _____Sg_ABt 7HomeKit29HealthCheckReachabilityReportV
+ _symbolic _____Sg_ABt 7HomeKit29HealthCheckResponseTimeMetricV
+ _symbolic _____Sg_ABt 7HomeKit31HealthCheckStabilityTrendMetricV
+ _symbolic _____Sg_ABt 7HomeKit33HealthCheckStabilityMetricsReportV
+ _symbolic _____Sg_ABt 7HomeKit33HealthCheckWirelessInsightsReportV
+ _symbolic _____Sg_ABt 7HomeKit37HealthCheckReadWritePerformanceReportV
+ _symbolic ___________t So18HMClientConnectionC7HomeKitE14DeviceIdentityV AbCE17RemoteContextInfoV
+ _symbolic _____ySSSDySSypGG s18_DictionaryStorageC
+ _symbolic _____ySS_SDySSypGtG s23_ContiguousArrayStorageC
+ _symbolic _____ySS_____G s18_DictionaryStorageC 7HomeKit33HealthCheckWirelessInsightsReportV9RouteInfoV
+ _symbolic _____ySay_____GG 15Synchronization5MutexVAARi_zrlE 10Foundation4UUIDV
+ _symbolic _____ySbG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____ySo6HMRoomCG s11_SetStorageC
+ _symbolic _____ySo6HMRoomC_G Sh5IndexV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE So11HMAccessoryC7HomeKitE29ThermostatSensorPriorityStateO
+ _symbolic _____y_____G s11_SetStorageC So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV10ThermostatO
+ _symbolic _____y_____G s11_SetStorageC So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV4LockO
+ _symbolic _____y_____G s11_SetStorageC So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV6CameraO
+ _symbolic _____y_____G s11_SetStorageC So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV7GeneralO
+ _symbolic _____y_____G s11_SetStorageC So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV8DoorbellO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So13HMHomeManagerC7HomeKitE15PairingIdentityV10CodingKeys33_19526A708D3E96D6A037A081C887B197LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So13HMHomeManagerC7HomeKitE24ProvisionalConfigurationV10CodingKeys33_19526A708D3E96D6A037A081C887B197LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE10DeviceInfoV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishI7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveI7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveI7MessageV15ResponsePayloadV06DeviceI0V10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveI7MessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO0F5StateO010NoEligibleF10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO0F5StateO10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO0F5StateO16ActiveCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO0F5StateO25LinwoodDisabledCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO16ResumeCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO24DeleteMetadataCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO24MarkShouldRollCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO16DumpStateMessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE011ProvisionalE13TransferErrorO06ServerI10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE011ProvisionalE13TransferErrorO06TargetE18RejectedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE011ProvisionalE13TransferErrorO10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE011ProvisionalE13TransferErrorO26ConnectionFailedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE011ProvisionalE13TransferErrorO30AuthenticationFailedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE011ProvisionalE14TransferResultV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE011ProvisionalE14TransferResultV15FailedAccessoryV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE011ProvisionalE14TransferResultV20TransferredAccessoryV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE011ProvisionalE17ConnectionDetailsV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE013IsProvisionalE18ForIdentityRequestV0K7PayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE013IsProvisionalE18ForIdentityRequestV15ResponsePayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE019TransferProvisionalE7RequestV0I7PayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE019TransferProvisionalE7RequestV15ResponsePayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE019TransferProvisionalE7RequestV15ResponsePayloadV7OutcomeO10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE019TransferProvisionalE7RequestV15ResponsePayloadV7OutcomeO17FailureCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So6HMHomeC7HomeKitE019TransferProvisionalE7RequestV15ResponsePayloadV7OutcomeO17SuccessCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So13HMHomeManagerC7HomeKitE15PairingIdentityV10CodingKeys33_19526A708D3E96D6A037A081C887B197LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So13HMHomeManagerC7HomeKitE24ProvisionalConfigurationV10CodingKeys33_19526A708D3E96D6A037A081C887B197LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE10DeviceInfoV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishI7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveI7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveI7MessageV15ResponsePayloadV06DeviceI0V10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveI7MessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO0F5StateO010NoEligibleF10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO0F5StateO10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO0F5StateO16ActiveCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO0F5StateO25LinwoodDisabledCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO16ResumeCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO24DeleteMetadataCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV6ActionO24MarkShouldRollCodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO16DumpStateMessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE011ProvisionalE13TransferErrorO06ServerI10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE011ProvisionalE13TransferErrorO06TargetE18RejectedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE011ProvisionalE13TransferErrorO10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE011ProvisionalE13TransferErrorO26ConnectionFailedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE011ProvisionalE13TransferErrorO30AuthenticationFailedCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE011ProvisionalE14TransferResultV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE011ProvisionalE14TransferResultV15FailedAccessoryV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE011ProvisionalE14TransferResultV20TransferredAccessoryV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE011ProvisionalE17ConnectionDetailsV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE013IsProvisionalE18ForIdentityRequestV0K7PayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE013IsProvisionalE18ForIdentityRequestV15ResponsePayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE019TransferProvisionalE7RequestV0I7PayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE019TransferProvisionalE7RequestV15ResponsePayloadV10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE019TransferProvisionalE7RequestV15ResponsePayloadV7OutcomeO10CodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE019TransferProvisionalE7RequestV15ResponsePayloadV7OutcomeO17FailureCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So6HMHomeC7HomeKitE019TransferProvisionalE7RequestV15ResponsePayloadV7OutcomeO17SuccessCodingKeys33_E183C36FFEFAE7F444AF59781A559EA7LLO
+ _symbolic _____y__________G s18_DictionaryStorageC So18HMClientConnectionC7HomeKitE14DeviceIdentityV 10Foundation4DataV
+ _symbolic _____y__________G s18_DictionaryStorageC So18HMClientConnectionC7HomeKitE14DeviceIdentityV AdEE17RemoteContextInfoV
+ _symbolic _____y___________tG s23_ContiguousArrayStorageC So18HMClientConnectionC7HomeKitE14DeviceIdentityV AdEE17RemoteContextInfoV
+ _symbolic _____yyXlXpG s23_ContiguousArrayStorageC
+ _type_layout_string So11HMAccessoryC7HomeKitE11HealthCheckO15RecommendationsV
+ _type_layout_string So13HMHomeManagerC7HomeKitE15PairingIdentityV
+ _type_layout_string So13HMHomeManagerC7HomeKitE24ProvisionalConfigurationV
+ _type_layout_string So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV14RequestPayloadV
+ _type_layout_string So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV14RequestPayloadV
+ _type_layout_string So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV
+ _type_layout_string So18HMClientConnectionC7HomeKitE13RemoteContextO14ControlMessageV14RequestPayloadV
+ _type_layout_string So6HMHomeC7HomeKitE011ProvisionalB14TransferResultV
+ _type_layout_string So6HMHomeC7HomeKitE011ProvisionalB17ConnectionDetailsV
+ _type_layout_string So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV0H7PayloadV
+ _type_layout_string So6HMHomeC7HomeKitE013IsProvisionalB18ForIdentityRequestV15ResponsePayloadV
+ _type_layout_string So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV
+ _type_layout_string So6HMHomeC7HomeKitE019TransferProvisionalB7RequestV15ResponsePayloadV7OutcomeO
+ keypath_get.113Tm
+ keypath_get.153Tm
+ keypath_get.155Tm
+ keypath_get.169Tm
+ keypath_get.39Tm
+ keypath_get.65Tm
+ keypath_get.73Tm
+ keypath_get.75Tm
+ keypath_set.114Tm
+ keypath_set.154Tm
+ keypath_set.156Tm
+ keypath_set.170Tm
+ keypath_set.40Tm
+ keypath_set.66Tm
+ keypath_set.74Tm
+ keypath_set.76Tm
+ logCategory._hmf_once_t740
+ logCategory._hmf_once_t810
+ logCategory._hmf_once_v741
+ logCategory._hmf_once_v811
- -[HMMediaGroupStagingManager startTimer]
- GCC_except_table10005
- GCC_except_table10154
- GCC_except_table10155
- GCC_except_table10156
- GCC_except_table10160
- GCC_except_table10215
- GCC_except_table10238
- GCC_except_table10318
- GCC_except_table10320
- GCC_except_table10322
- GCC_except_table10324
- GCC_except_table10332
- GCC_except_table10382
- GCC_except_table10394
- GCC_except_table10396
- GCC_except_table10586
- GCC_except_table10587
- GCC_except_table10622
- GCC_except_table10655
- GCC_except_table10658
- GCC_except_table10661
- GCC_except_table10729
- GCC_except_table10749
- GCC_except_table10750
- GCC_except_table10751
- GCC_except_table10790
- GCC_except_table10792
- GCC_except_table10794
- GCC_except_table10859
- GCC_except_table10891
- GCC_except_table10893
- GCC_except_table10897
- GCC_except_table10914
- GCC_except_table10916
- GCC_except_table10922
- GCC_except_table10926
- GCC_except_table10929
- GCC_except_table10940
- GCC_except_table10946
- GCC_except_table10958
- GCC_except_table10961
- GCC_except_table10969
- GCC_except_table10972
- GCC_except_table10976
- GCC_except_table10996
- GCC_except_table11206
- GCC_except_table11219
- GCC_except_table11260
- GCC_except_table11263
- GCC_except_table11265
- GCC_except_table11278
- GCC_except_table11279
- GCC_except_table11347
- GCC_except_table11350
- GCC_except_table11351
- GCC_except_table11698
- GCC_except_table11736
- GCC_except_table11749
- GCC_except_table12111
- GCC_except_table12112
- GCC_except_table12114
- GCC_except_table12115
- GCC_except_table12125
- GCC_except_table12149
- GCC_except_table12150
- GCC_except_table12153
- GCC_except_table12156
- GCC_except_table12165
- GCC_except_table12166
- GCC_except_table12167
- GCC_except_table12290
- GCC_except_table12292
- GCC_except_table12296
- GCC_except_table12297
- GCC_except_table12345
- GCC_except_table12371
- GCC_except_table12384
- GCC_except_table12410
- GCC_except_table12414
- GCC_except_table12463
- GCC_except_table12464
- GCC_except_table12465
- GCC_except_table12466
- GCC_except_table12467
- GCC_except_table12468
- GCC_except_table12469
- GCC_except_table12470
- GCC_except_table12471
- GCC_except_table12472
- GCC_except_table12473
- GCC_except_table12474
- GCC_except_table12475
- GCC_except_table12476
- GCC_except_table12477
- GCC_except_table12478
- GCC_except_table12501
- GCC_except_table12528
- GCC_except_table12638
- GCC_except_table12639
- GCC_except_table12642
- GCC_except_table12708
- GCC_except_table12710
- GCC_except_table12718
- GCC_except_table12729
- GCC_except_table12731
- GCC_except_table12736
- GCC_except_table12737
- GCC_except_table12738
- GCC_except_table12962
- GCC_except_table13163
- GCC_except_table13166
- GCC_except_table13171
- GCC_except_table13175
- GCC_except_table13183
- GCC_except_table13188
- GCC_except_table13190
- GCC_except_table13195
- GCC_except_table13196
- GCC_except_table13198
- GCC_except_table13280
- GCC_except_table13282
- GCC_except_table13301
- GCC_except_table13302
- GCC_except_table13309
- GCC_except_table13323
- GCC_except_table13329
- GCC_except_table13332
- GCC_except_table13336
- GCC_except_table13414
- GCC_except_table13422
- GCC_except_table13423
- GCC_except_table13428
- GCC_except_table13434
- GCC_except_table13436
- GCC_except_table13438
- GCC_except_table13442
- GCC_except_table13446
- GCC_except_table13579
- GCC_except_table13635
- GCC_except_table13636
- GCC_except_table13637
- GCC_except_table13638
- GCC_except_table13648
- GCC_except_table13649
- GCC_except_table13673
- GCC_except_table13674
- GCC_except_table13748
- GCC_except_table13770
- GCC_except_table13773
- GCC_except_table13921
- GCC_except_table14091
- GCC_except_table14097
- GCC_except_table14100
- GCC_except_table14156
- GCC_except_table14191
- GCC_except_table14197
- GCC_except_table14202
- GCC_except_table14209
- GCC_except_table14211
- GCC_except_table14212
- GCC_except_table14213
- GCC_except_table14214
- GCC_except_table14215
- GCC_except_table14222
- GCC_except_table14353
- GCC_except_table14363
- GCC_except_table14459
- GCC_except_table14507
- GCC_except_table14509
- GCC_except_table14552
- GCC_except_table14555
- GCC_except_table14575
- GCC_except_table14577
- GCC_except_table14578
- GCC_except_table1526
- GCC_except_table1552
- GCC_except_table1618
- GCC_except_table1689
- GCC_except_table1694
- GCC_except_table1712
- GCC_except_table1780
- GCC_except_table1782
- GCC_except_table1793
- GCC_except_table1795
- GCC_except_table1935
- GCC_except_table1989
- GCC_except_table2066
- GCC_except_table2153
- GCC_except_table2154
- GCC_except_table2203
- GCC_except_table2488
- GCC_except_table2491
- GCC_except_table2494
- GCC_except_table2503
- GCC_except_table2512
- GCC_except_table2525
- GCC_except_table2527
- GCC_except_table2528
- GCC_except_table2534
- GCC_except_table2535
- GCC_except_table2536
- GCC_except_table3099
- GCC_except_table3104
- GCC_except_table3130
- GCC_except_table3133
- GCC_except_table3146
- GCC_except_table3178
- GCC_except_table3181
- GCC_except_table3207
- GCC_except_table3209
- GCC_except_table3211
- GCC_except_table3213
- GCC_except_table3360
- GCC_except_table3363
- GCC_except_table3371
- GCC_except_table3372
- GCC_except_table3393
- GCC_except_table3420
- GCC_except_table3421
- GCC_except_table3479
- GCC_except_table3481
- GCC_except_table3484
- GCC_except_table3485
- GCC_except_table3511
- GCC_except_table3513
- GCC_except_table3521
- GCC_except_table3523
- GCC_except_table3531
- GCC_except_table3532
- GCC_except_table3534
- GCC_except_table3535
- GCC_except_table3536
- GCC_except_table3621
- GCC_except_table3644
- GCC_except_table3647
- GCC_except_table3650
- GCC_except_table3653
- GCC_except_table3656
- GCC_except_table3659
- GCC_except_table3662
- GCC_except_table3727
- GCC_except_table3728
- GCC_except_table3774
- GCC_except_table3782
- GCC_except_table3783
- GCC_except_table3786
- GCC_except_table3787
- GCC_except_table3798
- GCC_except_table3820
- GCC_except_table3829
- GCC_except_table3833
- GCC_except_table3839
- GCC_except_table3880
- GCC_except_table3884
- GCC_except_table3888
- GCC_except_table3893
- GCC_except_table3901
- GCC_except_table3905
- GCC_except_table3914
- GCC_except_table3916
- GCC_except_table4160
- GCC_except_table4165
- GCC_except_table4169
- GCC_except_table4177
- GCC_except_table4182
- GCC_except_table4188
- GCC_except_table4192
- GCC_except_table4196
- GCC_except_table4219
- GCC_except_table4221
- GCC_except_table4223
- GCC_except_table4227
- GCC_except_table4229
- GCC_except_table4232
- GCC_except_table4307
- GCC_except_table4321
- GCC_except_table4324
- GCC_except_table4326
- GCC_except_table4329
- GCC_except_table4391
- GCC_except_table4456
- GCC_except_table4471
- GCC_except_table4474
- GCC_except_table4566
- GCC_except_table4567
- GCC_except_table4571
- GCC_except_table4576
- GCC_except_table4580
- GCC_except_table4585
- GCC_except_table4593
- GCC_except_table4844
- GCC_except_table4847
- GCC_except_table4859
- GCC_except_table4935
- GCC_except_table4981
- GCC_except_table5074
- GCC_except_table5269
- GCC_except_table5281
- GCC_except_table5308
- GCC_except_table5309
- GCC_except_table5310
- GCC_except_table5311
- GCC_except_table5366
- GCC_except_table5381
- GCC_except_table5743
- GCC_except_table5750
- GCC_except_table5755
- GCC_except_table5949
- GCC_except_table5997
- GCC_except_table6197
- GCC_except_table6199
- GCC_except_table6206
- GCC_except_table6214
- GCC_except_table6235
- GCC_except_table6246
- GCC_except_table6251
- GCC_except_table6254
- GCC_except_table6268
- GCC_except_table6273
- GCC_except_table6279
- GCC_except_table6289
- GCC_except_table6294
- GCC_except_table6299
- GCC_except_table6308
- GCC_except_table6355
- GCC_except_table6359
- GCC_except_table6369
- GCC_except_table6374
- GCC_except_table6388
- GCC_except_table6393
- GCC_except_table6400
- GCC_except_table6417
- GCC_except_table6420
- GCC_except_table6422
- GCC_except_table6425
- GCC_except_table6437
- GCC_except_table6442
- GCC_except_table6446
- GCC_except_table6484
- GCC_except_table6531
- GCC_except_table6540
- GCC_except_table6583
- GCC_except_table6585
- GCC_except_table6600
- GCC_except_table6644
- GCC_except_table6646
- GCC_except_table6664
- GCC_except_table6710
- GCC_except_table6805
- GCC_except_table6825
- GCC_except_table6826
- GCC_except_table6827
- GCC_except_table6829
- GCC_except_table6832
- GCC_except_table6833
- GCC_except_table7173
- GCC_except_table7179
- GCC_except_table7181
- GCC_except_table7191
- GCC_except_table7192
- GCC_except_table7397
- GCC_except_table7401
- GCC_except_table7499
- GCC_except_table7503
- GCC_except_table7505
- GCC_except_table7506
- GCC_except_table7709
- GCC_except_table7712
- GCC_except_table7804
- GCC_except_table7823
- GCC_except_table7833
- GCC_except_table7975
- GCC_except_table7984
- GCC_except_table7997
- GCC_except_table8004
- GCC_except_table8043
- GCC_except_table8045
- GCC_except_table8080
- GCC_except_table8082
- GCC_except_table8084
- GCC_except_table8086
- GCC_except_table8093
- GCC_except_table8107
- GCC_except_table8117
- GCC_except_table8123
- GCC_except_table8202
- GCC_except_table8211
- GCC_except_table8213
- GCC_except_table8223
- GCC_except_table8225
- GCC_except_table8227
- GCC_except_table8229
- GCC_except_table8231
- GCC_except_table8237
- GCC_except_table8241
- GCC_except_table8254
- GCC_except_table8256
- GCC_except_table8258
- GCC_except_table8260
- GCC_except_table8311
- GCC_except_table8370
- GCC_except_table8379
- GCC_except_table8496
- GCC_except_table8551
- GCC_except_table8553
- GCC_except_table8555
- GCC_except_table8577
- GCC_except_table8607
- GCC_except_table8619
- GCC_except_table8644
- GCC_except_table8650
- GCC_except_table8661
- GCC_except_table8663
- GCC_except_table8665
- GCC_except_table8667
- GCC_except_table8669
- GCC_except_table8671
- GCC_except_table8673
- GCC_except_table8675
- GCC_except_table8677
- GCC_except_table8679
- GCC_except_table8683
- GCC_except_table8685
- GCC_except_table8690
- GCC_except_table8704
- GCC_except_table8705
- GCC_except_table8730
- GCC_except_table8732
- GCC_except_table8770
- GCC_except_table8788
- GCC_except_table8967
- GCC_except_table9318
- GCC_except_table9361
- GCC_except_table9454
- GCC_except_table9463
- GCC_except_table9638
- GCC_except_table9640
- GCC_except_table9641
- GCC_except_table9642
- GCC_except_table9644
- GCC_except_table9646
- GCC_except_table9647
- GCC_except_table9648
- GCC_except_table9683
- GCC_except_table9686
- GCC_except_table9687
- GCC_except_table9690
- GCC_except_table9693
- GCC_except_table9694
- GCC_except_table9737
- GCC_except_table9738
- GCC_except_table9739
- GCC_except_table9746
- GCC_except_table9747
- GCC_except_table9749
- GCC_except_table9837
- GCC_except_table9838
- GCC_except_table9839
- GCC_except_table9878
- GCC_except_table9892
- GCC_except_table9962
- GCC_except_table9991
- GCC_except_table9992
- GCC_except_table9993
- GCC_except_table9995
- GCC_except_table9998
- GCC_except_table9999
- __29-[HMHome mergeFromNewObject:]_block_invoke_5
- __29-[HMHome mergeFromNewObject:]_block_invoke_6
- __OBJC_$_CLASS_METHODS_HMAccessory(HomeKit|DynamicAccessorySettingsAdapter|SwiftExtensions|SiriEndpoint|Television|LightInternal|HMDoorbellChimeProfile|NetworkRouter|PendingConfiguration|Private|CUPeerIdentifier|Diagnostics|Shortcuts|Camera|CameraInternal|CHIP|NetworkConfiguration|Climate|Light|Media)
- __OBJC_$_INSTANCE_METHODS_HMAccessory(HomeKit|DynamicAccessorySettingsAdapter|SwiftExtensions|SiriEndpoint|Television|LightInternal|HMDoorbellChimeProfile|NetworkRouter|PendingConfiguration|Private|CUPeerIdentifier|Diagnostics|Shortcuts|Camera|CameraInternal|CHIP|NetworkConfiguration|Climate|Light|Media)
- _objc_msgSend$initWithCameraProfile:profileUniqueIdentifier:
- _objc_msgSend$initWithUUID:services:mostRecentSnapshot:userSettings:
- _objc_msgSend$startTimer
- logCategory._hmf_once_t706
- logCategory._hmf_once_t780
- logCategory._hmf_once_v707
- logCategory._hmf_once_v781
CStrings:
+ "%s/%s No message dispatcher"
+ "%s/%s XPC transport failure: %@"
+ ", Video Sensor UUID: %@"
+ ", timeToLive: %@"
+ "-[HMAccessory(ThreadManagement) repairThreadCommissioningWithCompletion:]"
+ "-[HMAccessory(ThreadManagement) repairWiFiCredentialsWithCompletion:]"
+ "-[HMAccessory(ThreadManagement) writePreferredWiFiListWithNetworks:completion:]"
+ "-[HMHome injectClimateDataWithType:thermostatUUID:value:completionHandler:]"
+ "-[HMHome setHasOwnerAcknowledgedHomePodSiriOnboardingWithCompletionHandler:]"
+ "-[HMHome updateWiFiAutoRepairMode:completion:]"
+ "5755BD27-56DA-43CA-AE89-68CEA284C23B"
+ "<%@ sensorType=%lu, sensorIntent=%lu, uniqueIdentifier=%@, streamingServiceUUID=%@>"
+ "<%@: %p, zones=%@, included=%@, triggers=%@>"
+ "Accessory context is nil"
+ "AppleTVPersonalContent"
+ "Could not decode uniqueIdentifier"
+ "Disabled"
+ "Event trigger evaluation condition raised an exception"
+ "HM.BulletinBoardNotificationLeftUnsecuredThreshold"
+ "HM.ac.HMAccessorySupportsAppleTVSiriSettingsCodingKey"
+ "HM.ac.HMAccessorySupportsTopCapPlusAndMinusCodingKey"
+ "HM.ac.HMAccessorySupportsTopCapTouchAndHoldCodingKey"
+ "HM.ac.supportsAssistantAccessControl"
+ "HM.homeAccessoryVariantCodingKey"
+ "HMA.FetchThermostatHumiditySensorPriorityStateMessage"
+ "HMA.FetchThermostatTemperatureSensorPriorityStateMessage"
+ "HMA.UpdateSupportsHumiditySensorPriorityMessage"
+ "HMA.UpdateSupportsTemperatureSensorPriorityMessage"
+ "HMA.UpdateThermostatHumiditySensorPriorityStateMessage"
+ "HMA.UpdateThermostatServiceRoomsMessage"
+ "HMA.UpdateThermostatTemperatureSensorPriorityStateMessage"
+ "HMA.UpdateUseThermostatServiceRoomsMessage"
+ "HMA.preferredWiFiNetworks"
+ "HMA.repairThreadCommissioning"
+ "HMA.repairWiFiList"
+ "HMA.supportsHumiditySensorPriority"
+ "HMA.supportsTemperatureSensorPriority"
+ "HMA.thermostatHumiditySensorPriorityState"
+ "HMA.thermostatServiceRoomUUIDs"
+ "HMA.thermostatTemperatureSensorPriorityState"
+ "HMA.useThermostatServiceRooms"
+ "HMA.writePreferredWiFiList"
+ "HMAccessory.HealthCheck"
+ "HMAccessoryHealthCheckReportDataKey"
+ "HMAccessorySupportsHumiditySensorPriorityMessage"
+ "HMAccessorySupportsTemperatureSensorPriorityMessage"
+ "HMCC.ck.vsu"
+ "HMCP.ck.videoSensors"
+ "HMCVS.ck.si"
+ "HMCVS.ck.ssu"
+ "HMCVS.ck.st"
+ "HMCVS.ck.uid"
+ "HMHM.wifiAutoRepairMode"
+ "HMHomeAccessoriesConfiguredStatusKey"
+ "HMHomeHasOwnerAcknowledgedHomePodSiriOnboardingValueCodingKey"
+ "HMHomeInjectClimateDataMessage"
+ "HMHomeInjectClimateDataThermostatUUIDKey"
+ "HMHomeInjectClimateDataTypeKey"
+ "HMHomeInjectClimateDataValueKey"
+ "HMHomePodVariantB525"
+ "HMHomeSetHasOwnerAcknowledgedHomePodSiriOnboardingRequestKey"
+ "HMHomeStagingHomeCodingKey"
+ "HMHomeUpdateWiFiAutoRepairModeMessage"
+ "HMMediaGroupStageRequestPayloadTimeToLiveKey"
+ "HMStagingHomeConfigurationKey"
+ "HOME_ACCESSORY_CATEGORY"
+ "HOME_ACCESSORY_CATEGORY_MULTIPLE"
+ "HOME_ACCESSORY_CATEGORY_SINGULAR"
+ "Home context unavailable"
+ "HomePodTopCap"
+ "HomeUtilAggregateRoomsKey"
+ "HomeUtilAggregateThermostatsKey"
+ "HomeUtilFetchAggregateDataMessage"
+ "HomeUtilHomeUUIDKey"
+ "Merging due to leftUnsecuredThreshold value change from %@ to %@"
+ "NetworkLinkManagement"
+ "No internal snapshot control for sensor UUID %{public,uuid_t}.16P"
+ "No internal stream control for sensor UUID %{public,uuid_t}.16P"
+ "No snapshot control in cache for known sensor UUID %{public,uuid_t}.16P"
+ "No stream control in cache for known sensor UUID %{public,uuid_t}.16P"
+ "No video sensor with UUID %{public,uuid_t}.16P"
+ "NotSet"
+ "Notifying client of updated supportsTopCapPlusAndMinus: %@, delegate: %@"
+ "Notifying client of updated supportsTopCapTouchAndHold: %@, delegate: %@"
+ "Notifying video sensors delegate of updated video sensors"
+ "ProInstallHAPTransfer"
+ "R"
+ "Requested sensor UUID %{public,uuid_t}.16P is not in the video sensors array"
+ "SecondPartyCamera"
+ "Sending set owner acknowledged HomePod Siri onboarding request"
+ "Sending update WiFi auto-repair mode request"
+ "Unexpected sensor type %lu for sensor UUID %{public,uuid_t}.16P"
+ "Unknown(%tu)"
+ "Updated WiFi auto-repair mode to %@"
+ "Updating supportsAppleTVSiriSettings from %@ to %@"
+ "Updating supportsAssistantAccessControl from %@ to %@"
+ "Updating supportsTopCapPlusAndMinus from %@ to %@"
+ "Updating supportsTopCapTouchAndHold from %@ to %@"
+ "VendorCustomerSupport"
+ "WiFi auto-repair mode is already set to:%@, skipping request"
+ "WiFi auto-repair mode request responded with error: %@"
+ "WiFi auto-repair mode updated to %@"
+ "[%{public}@] Could not decode uniqueIdentifier"
+ "[%{public}@] Merging due to leftUnsecuredThreshold value change from %@ to %@"
+ "[%{public}@] No internal snapshot control for sensor UUID %{public,uuid_t}.16P"
+ "[%{public}@] No internal stream control for sensor UUID %{public,uuid_t}.16P"
+ "[%{public}@] No snapshot control in cache for known sensor UUID %{public,uuid_t}.16P"
+ "[%{public}@] No stream control in cache for known sensor UUID %{public,uuid_t}.16P"
+ "[%{public}@] No video sensor with UUID %{public,uuid_t}.16P"
+ "[%{public}@] Notifying client of updated supportsTopCapPlusAndMinus: %@, delegate: %@"
+ "[%{public}@] Notifying client of updated supportsTopCapTouchAndHold: %@, delegate: %@"
+ "[%{public}@] Notifying video sensors delegate of updated video sensors"
+ "[%{public}@] Requested sensor UUID %{public,uuid_t}.16P is not in the video sensors array"
+ "[%{public}@] Sending set owner acknowledged HomePod Siri onboarding request"
+ "[%{public}@] Sending update WiFi auto-repair mode request"
+ "[%{public}@] Unexpected sensor type %lu for sensor UUID %{public,uuid_t}.16P"
+ "[%{public}@] Updated WiFi auto-repair mode to %@"
+ "[%{public}@] Updating supportsAppleTVSiriSettings from %@ to %@"
+ "[%{public}@] Updating supportsAssistantAccessControl from %@ to %@"
+ "[%{public}@] Updating supportsTopCapPlusAndMinus from %@ to %@"
+ "[%{public}@] Updating supportsTopCapTouchAndHold from %@ to %@"
+ "[%{public}@] WiFi auto-repair mode is already set to:%@, skipping request"
+ "[%{public}@] WiFi auto-repair mode request responded with error: %@"
+ "[%{public}@] WiFi auto-repair mode updated to %@"
+ "[%{public}@] hasOwnerAcknowledgedHomePodSiriOnboarding value %{BOOL}d is merging"
+ "[%{public}@] hasOwnerAcknowledgedHomePodSiriOnboarding value (NO) will not be merged"
+ "[%{public}@] setHasOwnerAcknowledgedHomePodSiriOnboardingHandler is already set, skipping send message notification"
+ "apple.homekit.healthcheck.BootReasonCount"
+ "apple.homekit.healthcheck.CameraReport"
+ "apple.homekit.healthcheck.Content"
+ "apple.homekit.healthcheck.DoorbellReport"
+ "apple.homekit.healthcheck.ErrorCount"
+ "apple.homekit.healthcheck.ErrorInfo"
+ "apple.homekit.healthcheck.FirmwareReport"
+ "apple.homekit.healthcheck.LockReport"
+ "apple.homekit.healthcheck.PowerReport"
+ "apple.homekit.healthcheck.ReachabilityReport"
+ "apple.homekit.healthcheck.ReadWritePerformanceReport"
+ "apple.homekit.healthcheck.Report"
+ "apple.homekit.healthcheck.ResponseTimeMetric"
+ "apple.homekit.healthcheck.StabilityMetricsReport"
+ "apple.homekit.healthcheck.StabilityTrendMetric"
+ "apple.homekit.healthcheck.ThermostatReport"
+ "apple.homekit.healthcheck.WirelessInsightsReport"
+ "authenticationFailed"
+ "com.apple.homeaccessory-1"
+ "com.apple.homed.HomeAccessoryAdded"
+ "connectionDetails"
+ "connectionFailed"
+ "failedAccessories"
+ "hasOwnerAcknowledgedHomePodSiriOnboarding value %{BOOL}d is merging"
+ "hasOwnerAcknowledgedHomePodSiriOnboarding value (NO) will not be merged"
+ "hm.isProvisionalHomeForIdentityRequest"
+ "hm.remoteContext.control"
+ "hm.remoteContext.dumpState"
+ "hm.remoteContext.publishContext"
+ "hm.remoteContext.retrieveContext"
+ "hm.remoteContext.stopPublishingContext"
+ "hm.transferProvisionalHomeRequest"
+ "hmcus.vsid"
+ "hmcus.vss"
+ "hmcvss.az"
+ "hmcvss.azifsed"
+ "hmcvss.ret"
+ "homeAccessory1"
+ "homeAccessory2"
+ "hubHAPPairingIdentifier"
+ "hubHAPPairingPublicKey"
+ "hubPairingIdentity"
+ "isProvisionalHome"
+ "isProvisionalHome(forPairingIdentifier:)"
+ "kCameraVideoSensorUUID"
+ "localizedFailureDescription"
+ "pairingIdentifier"
+ "root.display.touchAndVisualization.interaction.touchEnabled"
+ "root.display.touchAndVisualization.mediaVisualizer.visualization"
+ "root.siri.personalSiriEnabled"
+ "setHasOwnerAcknowledgedHomePodSiriOnboardingHandler is already set, skipping send message notification"
+ "targetHomeRejected"
+ "threadNetworkIdentifier"
+ "transferProvisionalHome(connectionDetails:targetHomeUniqueIdentifier:)"
+ "transferredAccessories"
+ "uniqueIdentifier != nil"
+ "unsupported-accessory-type"
+ "vsu"
+ "wifiAutoRepairMode"
+ "\xa1\xf0\xf0\xb1"
- "\xa1\xf0\xf0\xa1"
```
