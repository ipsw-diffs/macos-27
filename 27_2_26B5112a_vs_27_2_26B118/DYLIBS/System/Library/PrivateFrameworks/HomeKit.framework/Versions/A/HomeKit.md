## HomeKit

> `/System/Library/PrivateFrameworks/HomeKit.framework/Versions/A/HomeKit`

```diff

 1520.2.7.4.1
-  __TEXT.__text: 0x46b204
-  __TEXT.__objc_methlist: 0x28e24
-  __TEXT.__const: 0x10578
+  __TEXT.__text: 0x476878
+  __TEXT.__objc_methlist: 0x2962c
+  __TEXT.__const: 0x10588
   __TEXT.__dlopen_cstrs: 0x3bb
-  __TEXT.__swift5_typeref: 0x3983
-  __TEXT.__cstring: 0x31196
+  __TEXT.__swift5_typeref: 0x398d
+  __TEXT.__cstring: 0x31963
   __TEXT.__constg_swiftt: 0x3564
   __TEXT.__swift5_reflstr: 0x25ee
   __TEXT.__swift5_fieldmd: 0x31b8

   __TEXT.__swift_as_entry: 0x274
   __TEXT.__swift_as_ret: 0x2b8
   __TEXT.__swift_as_cont: 0x53c
-  __TEXT.__oslogstring: 0x578a7
+  __TEXT.__oslogstring: 0x58787
   __TEXT.__swift5_mpenum: 0x20
   __TEXT.__gcc_except_tab: 0x67cc
   __TEXT.__ustring: 0x50
-  __TEXT.__unwind_info: 0x12290
-  __TEXT.__eh_frame: 0xbac0
+  __TEXT.__unwind_info: 0x124f0
+  __TEXT.__eh_frame: 0xbaf8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6178
-  __DATA_CONST.__objc_classlist: 0x1368
+  __DATA_CONST.__const: 0x61c0
+  __DATA_CONST.__objc_classlist: 0x1390
   __DATA_CONST.__objc_catlist: 0x108
   __DATA_CONST.__objc_protolist: 0x560
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe568
+  __DATA_CONST.__objc_selrefs: 0xe7a0
   __DATA_CONST.__objc_protorefs: 0x110
-  __DATA_CONST.__objc_superrefs: 0xfa8
+  __DATA_CONST.__objc_superrefs: 0xfc8
   __DATA_CONST.__objc_arraydata: 0x14c8
-  __DATA_CONST.__got: 0x1eb8
-  __AUTH_CONST.__const: 0xe078
-  __AUTH_CONST.__cfstring: 0x2c8a0
-  __AUTH_CONST.__objc_const: 0x49b88
+  __DATA_CONST.__got: 0x1ee0
+  __AUTH_CONST.__const: 0xe158
+  __AUTH_CONST.__cfstring: 0x2cf20
+  __AUTH_CONST.__objc_const: 0x4a6d0
   __AUTH_CONST.__objc_intobj: 0x9f0
   __AUTH_CONST.__objc_dictobj: 0x848
   __AUTH_CONST.__objc_arrayobj: 0x618
   __AUTH_CONST.__objc_doubleobj: 0x70
   __AUTH_CONST.__auth_got: 0x1a48
-  __AUTH.__objc_data: 0x8fc0
+  __AUTH.__objc_data: 0x9150
   __AUTH.__data: 0x3468
-  __DATA.__objc_ivar: 0x2894
-  __DATA.__data: 0x70d0
-  __DATA.__bss: 0x19d70
+  __DATA.__objc_ivar: 0x28f4
+  __DATA.__data: 0x70c0
+  __DATA.__bss: 0x19db0
   __DATA.__common: 0x90
   __DATA_DIRTY.__objc_data: 0x3748
-  __DATA_DIRTY.__data: 0x1a0
-  __DATA_DIRTY.__bss: 0x2a8
+  __DATA_DIRTY.__data: 0x190
+  __DATA_DIRTY.__bss: 0x298
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 21197
-  Symbols:   33721
-  CStrings:  12586
+  Functions: 21384
+  Symbols:   34032
+  CStrings:  12685
 
Symbols:
+ +[HMCurrentMediaGroupProvider _participantRoleForSurroundSystem:destinationIdentifier:]
+ +[HMSurroundSystem derivedDestinationIdentifierForGroupIdentifier:]
+ +[HMSurroundSystem roomNameSentinel]
+ +[HMSurroundSystem supportsSecureCoding]
+ +[HMSurroundSystemConfigurationRequest logCategory]
+ +[HMSurroundSystemConfigurationRequest messageName]
+ +[HMSurroundSystemConfigurationRequest shortDescription]
+ +[HMSurroundSystemConfigurationRequestPayload logCategory]
+ +[HMSurroundSystemUpdateRolesRequest logCategory]
+ +[HMSurroundSystemUpdateRolesRequest shortDescription]
+ -[HMAccessory accessoryWithAudioDestinationIdentifier:]
+ -[HMAccessory mediaDestinationController:didGetUpdateDestinationRequestWithSurroundSystemDestination:completionHandler:]
+ -[HMAccessory setSupportsSurroundSystemFrontRoleCapability:]
+ -[HMAccessory setSupportsSurroundSystemRearRoleCapability:]
+ -[HMAccessory supportsSurroundSystemFrontRoleCapability]
+ -[HMAccessory supportsSurroundSystemFrontRole]
+ -[HMAccessory supportsSurroundSystemRearRoleCapability]
+ -[HMAccessory supportsSurroundSystemRearRole]
+ -[HMAccessoryCapabilities supportsAudioDestinationSurroundSystemFrontRole]
+ -[HMAccessoryCapabilities supportsAudioDestinationSurroundSystemRearRole]
+ -[HMAccessoryCapabilities supportsHomeTheaterSourceSurroundSystem]
+ -[HMCurrentMediaGroupProvider _mergeWithCurrentAppleTVAccessory:surroundSystemDestination:home:]
+ -[HMCurrentMediaGroupProvider _mergeWithCurrentHomePodAccessory:surroundSystem:home:]
+ -[HMCurrentMediaGroupProvider _notifyClientOfCurrentMediaGroupWithCurrentAccessory:surroundSystem:sourceAccessory:home:]
+ -[HMHome accessoryWithAudioDestinationControllerIdentifier:]
+ -[HMHome mediaGroupsController:sourceAccessoryForSurroundSystem:]
+ -[HMMediaDestination containsSurroundSystemFrontRoleSupportedOptions]
+ -[HMMediaDestination containsSurroundSystemRearRoleSupportedOptions]
+ -[HMMediaDestinationController supportsSurroundSystemDestinations]
+ -[HMMediaDestinationController updateToSurroundSystemDestination:completionHandler:]
+ -[HMMediaGroup surroundSystem]
+ -[HMMediaGroupDestination supportsSurroundSystemFrontRole]
+ -[HMMediaGroupDestination supportsSurroundSystemRearRole]
+ -[HMMediaGroupsController homeTheaterSystemForSurroundSystem:]
+ -[HMMediaGroupsController updateSurroundSystemRolesWithRequest:completion:]
+ -[HMMediaSystem supportsSurroundSystemFrontRole]
+ -[HMMediaSystem supportsSurroundSystemRearRole]
+ -[HMMutableSurroundSystem copyWithZone:]
+ -[HMProtoAccessoryCapabilities(UnobfuscatedAliases) setSupportsAudioDestinationSurroundSystemFrontRole:]
+ -[HMProtoAccessoryCapabilities(UnobfuscatedAliases) setSupportsAudioDestinationSurroundSystemRearRole:]
+ -[HMProtoAccessoryCapabilities(UnobfuscatedAliases) setSupportsHomeTheaterSourceSurroundSystem:]
+ -[HMProtoAccessoryCapabilities(UnobfuscatedAliases) supportsAudioDestinationSurroundSystemFrontRole]
+ -[HMProtoAccessoryCapabilities(UnobfuscatedAliases) supportsAudioDestinationSurroundSystemRearRole]
+ -[HMProtoAccessoryCapabilities(UnobfuscatedAliases) supportsHomeTheaterSourceSurroundSystem]
+ -[HMResidentCapabilities supportsSurroundConfiguration]
+ -[HMResidentDevice setSupportsSurroundConfiguration:]
+ -[HMResidentDevice supportsSurroundConfiguration]
+ -[HMSurroundSystem .cxx_destruct]
+ -[HMSurroundSystem destinationIdentifiers]
+ -[HMSurroundSystem destinationUniqueIdentifiers]
+ -[HMSurroundSystem encodeToProtoBufferData]
+ -[HMSurroundSystem encodeWithCoder:]
+ -[HMSurroundSystem frontLeftDestinationIdentifier]
+ -[HMSurroundSystem frontRightDestinationIdentifier]
+ -[HMSurroundSystem hash]
+ -[HMSurroundSystem hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSurroundSystem initWithCoder:]
+ -[HMSurroundSystem initWithIdentifier:parentIdentifier:associatedGroupIdentifier:frontLeftDestinationIdentifier:frontRightDestinationIdentifier:rearLeftDestinationIdentifier:rearRightDestinationIdentifier:]
+ -[HMSurroundSystem initWithIdentifier:parentIdentifier:name:defaultName:associatedGroupIdentifier:frontLeftDestinationIdentifier:frontRightDestinationIdentifier:rearLeftDestinationIdentifier:rearRightDestinationIdentifier:]
+ -[HMSurroundSystem initWithProtoBufferData:]
+ -[HMSurroundSystem isEqual:]
+ -[HMSurroundSystem metricType]
+ -[HMSurroundSystem mutableCopyWithZone:]
+ -[HMSurroundSystem rearLeftDestinationIdentifier]
+ -[HMSurroundSystem rearRightDestinationIdentifier]
+ -[HMSurroundSystem setFrontLeftDestinationIdentifier:]
+ -[HMSurroundSystem setFrontRightDestinationIdentifier:]
+ -[HMSurroundSystem setRearLeftDestinationIdentifier:]
+ -[HMSurroundSystem setRearRightDestinationIdentifier:]
+ -[HMSurroundSystem shortDescription]
+ -[HMSurroundSystemConfigurationRequest .cxx_destruct]
+ -[HMSurroundSystemConfigurationRequest accessoriesInWrongRoom]
+ -[HMSurroundSystemConfigurationRequest description]
+ -[HMSurroundSystemConfigurationRequest frontLeftAccessoryUUID]
+ -[HMSurroundSystemConfigurationRequest frontLeftAccessory]
+ -[HMSurroundSystemConfigurationRequest frontRightAccessoryUUID]
+ -[HMSurroundSystemConfigurationRequest frontRightAccessory]
+ -[HMSurroundSystemConfigurationRequest hash]
+ -[HMSurroundSystemConfigurationRequest hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSurroundSystemConfigurationRequest identifier]
+ -[HMSurroundSystemConfigurationRequest initWithIdentifier:sourceAccessory:frontLeftAccessory:frontRightAccessory:rearLeftAccessory:rearRightAccessory:]
+ -[HMSurroundSystemConfigurationRequest initWithSourceAccessory:frontLeftAccessory:frontRightAccessory:rearLeftAccessory:rearRightAccessory:]
+ -[HMSurroundSystemConfigurationRequest isEqual:]
+ -[HMSurroundSystemConfigurationRequest isUniqueAccessories]
+ -[HMSurroundSystemConfigurationRequest isValidAllFrontConfiguration]
+ -[HMSurroundSystemConfigurationRequest isValidAllRearConfiguration]
+ -[HMSurroundSystemConfigurationRequest isValidConfiguration]
+ -[HMSurroundSystemConfigurationRequest isValidHomePodConfiguration]
+ -[HMSurroundSystemConfigurationRequest isValidMixConfiguration]
+ -[HMSurroundSystemConfigurationRequest isValidSourceAccessory]
+ -[HMSurroundSystemConfigurationRequest messageName]
+ -[HMSurroundSystemConfigurationRequest metricType]
+ -[HMSurroundSystemConfigurationRequest payload]
+ -[HMSurroundSystemConfigurationRequest privateDescription]
+ -[HMSurroundSystemConfigurationRequest rearLeftAccessoryUUID]
+ -[HMSurroundSystemConfigurationRequest rearLeftAccessory]
+ -[HMSurroundSystemConfigurationRequest rearRightAccessoryUUID]
+ -[HMSurroundSystemConfigurationRequest rearRightAccessory]
+ -[HMSurroundSystemConfigurationRequest setFrontLeftAccessory:]
+ -[HMSurroundSystemConfigurationRequest setFrontRightAccessory:]
+ -[HMSurroundSystemConfigurationRequest setRearLeftAccessory:]
+ -[HMSurroundSystemConfigurationRequest setRearRightAccessory:]
+ -[HMSurroundSystemConfigurationRequest setSourceAccessory:]
+ -[HMSurroundSystemConfigurationRequest shortDescription]
+ -[HMSurroundSystemConfigurationRequest sourceAccessoryUUID]
+ -[HMSurroundSystemConfigurationRequest sourceAccessory]
+ -[HMSurroundSystemConfigurationRequestPayload .cxx_destruct]
+ -[HMSurroundSystemConfigurationRequestPayload frontLeftAccessoryUUID]
+ -[HMSurroundSystemConfigurationRequestPayload frontRightAccessoryUUID]
+ -[HMSurroundSystemConfigurationRequestPayload hash]
+ -[HMSurroundSystemConfigurationRequestPayload hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSurroundSystemConfigurationRequestPayload identifier]
+ -[HMSurroundSystemConfigurationRequestPayload initWithIdentifier:sourceAccessoryUUID:frontLeftAccessoryUUID:frontRightAccessoryUUID:rearLeftAccessoryUUID:rearRightAccessoryUUID:]
+ -[HMSurroundSystemConfigurationRequestPayload initWithPayload:]
+ -[HMSurroundSystemConfigurationRequestPayload isEqual:]
+ -[HMSurroundSystemConfigurationRequestPayload payloadCopy]
+ -[HMSurroundSystemConfigurationRequestPayload rearLeftAccessoryUUID]
+ -[HMSurroundSystemConfigurationRequestPayload rearRightAccessoryUUID]
+ -[HMSurroundSystemConfigurationRequestPayload sourceAccessoryUUID]
+ -[HMSurroundSystemUpdateRolesRequest .cxx_destruct]
+ -[HMSurroundSystemUpdateRolesRequest configurationRequestWithSourceAccessory:]
+ -[HMSurroundSystemUpdateRolesRequest description]
+ -[HMSurroundSystemUpdateRolesRequest frontLeftAccessoryUUID]
+ -[HMSurroundSystemUpdateRolesRequest frontLeftAccessory]
+ -[HMSurroundSystemUpdateRolesRequest frontRightAccessoryUUID]
+ -[HMSurroundSystemUpdateRolesRequest frontRightAccessory]
+ -[HMSurroundSystemUpdateRolesRequest hash]
+ -[HMSurroundSystemUpdateRolesRequest hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSurroundSystemUpdateRolesRequest initWithSurroundSystem:frontLeftAccessory:frontRightAccessory:rearLeftAccessory:rearRightAccessory:]
+ -[HMSurroundSystemUpdateRolesRequest isEqual:]
+ -[HMSurroundSystemUpdateRolesRequest isUniqueAccessories]
+ -[HMSurroundSystemUpdateRolesRequest isValidAllFrontConfiguration]
+ -[HMSurroundSystemUpdateRolesRequest isValidAllRearConfiguration]
+ -[HMSurroundSystemUpdateRolesRequest isValidHomePodConfiguration]
+ -[HMSurroundSystemUpdateRolesRequest isValidMixConfiguration]
+ -[HMSurroundSystemUpdateRolesRequest isValidRequest]
+ -[HMSurroundSystemUpdateRolesRequest privateDescription]
+ -[HMSurroundSystemUpdateRolesRequest rearLeftAccessoryUUID]
+ -[HMSurroundSystemUpdateRolesRequest rearLeftAccessory]
+ -[HMSurroundSystemUpdateRolesRequest rearRightAccessoryUUID]
+ -[HMSurroundSystemUpdateRolesRequest rearRightAccessory]
+ -[HMSurroundSystemUpdateRolesRequest shortDescription]
+ -[HMSurroundSystemUpdateRolesRequest surroundSystemIdentifier]
+ -[HMSurroundSystemUpdateRolesRequest surroundSystem]
+ GCC_except_table10063
+ GCC_except_table10064
+ GCC_except_table10065
+ GCC_except_table10098
+ GCC_except_table10107
+ GCC_except_table10121
+ GCC_except_table10192
+ GCC_except_table10222
+ GCC_except_table10223
+ GCC_except_table10224
+ GCC_except_table10226
+ GCC_except_table10229
+ GCC_except_table10230
+ GCC_except_table10236
+ GCC_except_table10385
+ GCC_except_table10386
+ GCC_except_table10387
+ GCC_except_table10391
+ GCC_except_table10446
+ GCC_except_table10469
+ GCC_except_table10550
+ GCC_except_table10552
+ GCC_except_table10554
+ GCC_except_table10556
+ GCC_except_table10564
+ GCC_except_table10614
+ GCC_except_table10626
+ GCC_except_table10628
+ GCC_except_table10818
+ GCC_except_table10819
+ GCC_except_table10854
+ GCC_except_table10887
+ GCC_except_table10890
+ GCC_except_table10893
+ GCC_except_table10895
+ GCC_except_table10961
+ GCC_except_table10981
+ GCC_except_table10982
+ GCC_except_table10983
+ GCC_except_table11022
+ GCC_except_table11024
+ GCC_except_table11026
+ GCC_except_table11091
+ GCC_except_table11123
+ GCC_except_table11125
+ GCC_except_table11129
+ GCC_except_table11146
+ GCC_except_table11148
+ GCC_except_table11154
+ GCC_except_table11158
+ GCC_except_table11161
+ GCC_except_table11168
+ GCC_except_table11172
+ GCC_except_table11178
+ GCC_except_table11190
+ GCC_except_table11193
+ GCC_except_table11201
+ GCC_except_table11202
+ GCC_except_table11204
+ GCC_except_table11206
+ GCC_except_table11208
+ GCC_except_table11228
+ GCC_except_table11238
+ GCC_except_table11454
+ GCC_except_table11467
+ GCC_except_table11508
+ GCC_except_table11511
+ GCC_except_table11513
+ GCC_except_table11526
+ GCC_except_table11527
+ GCC_except_table11595
+ GCC_except_table11598
+ GCC_except_table11599
+ GCC_except_table11946
+ GCC_except_table11984
+ GCC_except_table11997
+ GCC_except_table12374
+ GCC_except_table12375
+ GCC_except_table12377
+ GCC_except_table12378
+ GCC_except_table12388
+ GCC_except_table12412
+ GCC_except_table12413
+ GCC_except_table12416
+ GCC_except_table12419
+ GCC_except_table12428
+ GCC_except_table12429
+ GCC_except_table12430
+ GCC_except_table12527
+ GCC_except_table12553
+ GCC_except_table12555
+ GCC_except_table12559
+ GCC_except_table12560
+ GCC_except_table12608
+ GCC_except_table12634
+ GCC_except_table12647
+ GCC_except_table12673
+ GCC_except_table12677
+ GCC_except_table12726
+ GCC_except_table12727
+ GCC_except_table12728
+ GCC_except_table12729
+ GCC_except_table12730
+ GCC_except_table12731
+ GCC_except_table12732
+ GCC_except_table12733
+ GCC_except_table12734
+ GCC_except_table12735
+ GCC_except_table12736
+ GCC_except_table12737
+ GCC_except_table12738
+ GCC_except_table12739
+ GCC_except_table12740
+ GCC_except_table12741
+ GCC_except_table12764
+ GCC_except_table12791
+ GCC_except_table12901
+ GCC_except_table12902
+ GCC_except_table12905
+ GCC_except_table12971
+ GCC_except_table12973
+ GCC_except_table12981
+ GCC_except_table12992
+ GCC_except_table12994
+ GCC_except_table12999
+ GCC_except_table13000
+ GCC_except_table13001
+ GCC_except_table13225
+ GCC_except_table13426
+ GCC_except_table13429
+ GCC_except_table13434
+ GCC_except_table13438
+ GCC_except_table13446
+ GCC_except_table13451
+ GCC_except_table13453
+ GCC_except_table13458
+ GCC_except_table13459
+ GCC_except_table13461
+ GCC_except_table13543
+ GCC_except_table13545
+ GCC_except_table13564
+ GCC_except_table13565
+ GCC_except_table13566
+ GCC_except_table13567
+ GCC_except_table13572
+ GCC_except_table13586
+ GCC_except_table13592
+ GCC_except_table13595
+ GCC_except_table13599
+ GCC_except_table13677
+ GCC_except_table13685
+ GCC_except_table13686
+ GCC_except_table13691
+ GCC_except_table13697
+ GCC_except_table13699
+ GCC_except_table13701
+ GCC_except_table13703
+ GCC_except_table13705
+ GCC_except_table13707
+ GCC_except_table13709
+ GCC_except_table13842
+ GCC_except_table13898
+ GCC_except_table13899
+ GCC_except_table13900
+ GCC_except_table13901
+ GCC_except_table13911
+ GCC_except_table13912
+ GCC_except_table13936
+ GCC_except_table13937
+ GCC_except_table14013
+ GCC_except_table14035
+ GCC_except_table14038
+ GCC_except_table14186
+ GCC_except_table14356
+ GCC_except_table14362
+ GCC_except_table14365
+ GCC_except_table14421
+ GCC_except_table14456
+ GCC_except_table14462
+ GCC_except_table14466
+ GCC_except_table14467
+ GCC_except_table14472
+ GCC_except_table14474
+ GCC_except_table14475
+ GCC_except_table14476
+ GCC_except_table14477
+ GCC_except_table14478
+ GCC_except_table14479
+ GCC_except_table14480
+ GCC_except_table14487
+ GCC_except_table14628
+ GCC_except_table14725
+ GCC_except_table14773
+ GCC_except_table14775
+ GCC_except_table14821
+ GCC_except_table14824
+ GCC_except_table14845
+ GCC_except_table14847
+ GCC_except_table14848
+ GCC_except_table1530
+ GCC_except_table1557
+ GCC_except_table1623
+ GCC_except_table1698
+ GCC_except_table1703
+ GCC_except_table1721
+ GCC_except_table1789
+ GCC_except_table1791
+ GCC_except_table1802
+ GCC_except_table1804
+ GCC_except_table1944
+ GCC_except_table2000
+ GCC_except_table2003
+ GCC_except_table2077
+ GCC_except_table2164
+ GCC_except_table2165
+ GCC_except_table2214
+ GCC_except_table2501
+ GCC_except_table2507
+ GCC_except_table2512
+ GCC_except_table2516
+ GCC_except_table2525
+ GCC_except_table2546
+ GCC_except_table2547
+ GCC_except_table2548
+ GCC_except_table2549
+ GCC_except_table3120
+ GCC_except_table3125
+ GCC_except_table3151
+ GCC_except_table3154
+ GCC_except_table3167
+ GCC_except_table3199
+ GCC_except_table3202
+ GCC_except_table3228
+ GCC_except_table3230
+ GCC_except_table3232
+ GCC_except_table3234
+ GCC_except_table3381
+ GCC_except_table3384
+ GCC_except_table3392
+ GCC_except_table3393
+ GCC_except_table3414
+ GCC_except_table3441
+ GCC_except_table3442
+ GCC_except_table3500
+ GCC_except_table3502
+ GCC_except_table3505
+ GCC_except_table3506
+ GCC_except_table3532
+ GCC_except_table3534
+ GCC_except_table3551
+ GCC_except_table3552
+ GCC_except_table3553
+ GCC_except_table3555
+ GCC_except_table3556
+ GCC_except_table3557
+ GCC_except_table3558
+ GCC_except_table3559
+ GCC_except_table3642
+ GCC_except_table3665
+ GCC_except_table3668
+ GCC_except_table3671
+ GCC_except_table3674
+ GCC_except_table3677
+ GCC_except_table3680
+ GCC_except_table3683
+ GCC_except_table3748
+ GCC_except_table3749
+ GCC_except_table3802
+ GCC_except_table3803
+ GCC_except_table3804
+ GCC_except_table3807
+ GCC_except_table3808
+ GCC_except_table3809
+ GCC_except_table3811
+ GCC_except_table3819
+ GCC_except_table3841
+ GCC_except_table3850
+ GCC_except_table3854
+ GCC_except_table3857
+ GCC_except_table3860
+ GCC_except_table3901
+ GCC_except_table3905
+ GCC_except_table3909
+ GCC_except_table3914
+ GCC_except_table3922
+ GCC_except_table3926
+ GCC_except_table3935
+ GCC_except_table3937
+ GCC_except_table4181
+ GCC_except_table4186
+ GCC_except_table4190
+ GCC_except_table4193
+ GCC_except_table4197
+ GCC_except_table4198
+ GCC_except_table4209
+ GCC_except_table4213
+ GCC_except_table4217
+ GCC_except_table4246
+ GCC_except_table4248
+ GCC_except_table4250
+ GCC_except_table4253
+ GCC_except_table4254
+ GCC_except_table4256
+ GCC_except_table4259
+ GCC_except_table4334
+ GCC_except_table4348
+ GCC_except_table4351
+ GCC_except_table4353
+ GCC_except_table4356
+ GCC_except_table4363
+ GCC_except_table4418
+ GCC_except_table4485
+ GCC_except_table4500
+ GCC_except_table4503
+ GCC_except_table4595
+ GCC_except_table4596
+ GCC_except_table4605
+ GCC_except_table4609
+ GCC_except_table4612
+ GCC_except_table4614
+ GCC_except_table4622
+ GCC_except_table4884
+ GCC_except_table4887
+ GCC_except_table4899
+ GCC_except_table4975
+ GCC_except_table5021
+ GCC_except_table5114
+ GCC_except_table5309
+ GCC_except_table5321
+ GCC_except_table5348
+ GCC_except_table5349
+ GCC_except_table5350
+ GCC_except_table5351
+ GCC_except_table5406
+ GCC_except_table5421
+ GCC_except_table5790
+ GCC_except_table5797
+ GCC_except_table5802
+ GCC_except_table5999
+ GCC_except_table6054
+ GCC_except_table6256
+ GCC_except_table6258
+ GCC_except_table6273
+ GCC_except_table6294
+ GCC_except_table6305
+ GCC_except_table6310
+ GCC_except_table6313
+ GCC_except_table6327
+ GCC_except_table6332
+ GCC_except_table6343
+ GCC_except_table6348
+ GCC_except_table6353
+ GCC_except_table6358
+ GCC_except_table6362
+ GCC_except_table6367
+ GCC_except_table6414
+ GCC_except_table6428
+ GCC_except_table6433
+ GCC_except_table6459
+ GCC_except_table6477
+ GCC_except_table6479
+ GCC_except_table6481
+ GCC_except_table6484
+ GCC_except_table6489
+ GCC_except_table6496
+ GCC_except_table6501
+ GCC_except_table6505
+ GCC_except_table6543
+ GCC_except_table6590
+ GCC_except_table6599
+ GCC_except_table6642
+ GCC_except_table6644
+ GCC_except_table6659
+ GCC_except_table6786
+ GCC_except_table6788
+ GCC_except_table6806
+ GCC_except_table6852
+ GCC_except_table6947
+ GCC_except_table6967
+ GCC_except_table6968
+ GCC_except_table6969
+ GCC_except_table6971
+ GCC_except_table6974
+ GCC_except_table6975
+ GCC_except_table6977
+ GCC_except_table7326
+ GCC_except_table7332
+ GCC_except_table7334
+ GCC_except_table7344
+ GCC_except_table7345
+ GCC_except_table7550
+ GCC_except_table7661
+ GCC_except_table7665
+ GCC_except_table7667
+ GCC_except_table7668
+ GCC_except_table7876
+ GCC_except_table7974
+ GCC_except_table7993
+ GCC_except_table8003
+ GCC_except_table8153
+ GCC_except_table8162
+ GCC_except_table8175
+ GCC_except_table8182
+ GCC_except_table8221
+ GCC_except_table8223
+ GCC_except_table8258
+ GCC_except_table8260
+ GCC_except_table8262
+ GCC_except_table8264
+ GCC_except_table8271
+ GCC_except_table8289
+ GCC_except_table8301
+ GCC_except_table8307
+ GCC_except_table8394
+ GCC_except_table8403
+ GCC_except_table8405
+ GCC_except_table8415
+ GCC_except_table8417
+ GCC_except_table8419
+ GCC_except_table8421
+ GCC_except_table8423
+ GCC_except_table8429
+ GCC_except_table8433
+ GCC_except_table8446
+ GCC_except_table8448
+ GCC_except_table8450
+ GCC_except_table8452
+ GCC_except_table8479
+ GCC_except_table8509
+ GCC_except_table8596
+ GCC_except_table8605
+ GCC_except_table8722
+ GCC_except_table8777
+ GCC_except_table8781
+ GCC_except_table8803
+ GCC_except_table8833
+ GCC_except_table8845
+ GCC_except_table8870
+ GCC_except_table8876
+ GCC_except_table8887
+ GCC_except_table8889
+ GCC_except_table8891
+ GCC_except_table8893
+ GCC_except_table8895
+ GCC_except_table8897
+ GCC_except_table8899
+ GCC_except_table8901
+ GCC_except_table8903
+ GCC_except_table8905
+ GCC_except_table8907
+ GCC_except_table8909
+ GCC_except_table8911
+ GCC_except_table8916
+ GCC_except_table8930
+ GCC_except_table8931
+ GCC_except_table8956
+ GCC_except_table8958
+ GCC_except_table8983
+ GCC_except_table8996
+ GCC_except_table9014
+ GCC_except_table9193
+ GCC_except_table9544
+ GCC_except_table9587
+ GCC_except_table9680
+ GCC_except_table9689
+ GCC_except_table9864
+ GCC_except_table9866
+ GCC_except_table9867
+ GCC_except_table9868
+ GCC_except_table9870
+ GCC_except_table9872
+ GCC_except_table9873
+ GCC_except_table9874
+ GCC_except_table9909
+ GCC_except_table9916
+ GCC_except_table9919
+ GCC_except_table9920
+ GCC_except_table9963
+ GCC_except_table9964
+ GCC_except_table9965
+ GCC_except_table9972
+ GCC_except_table9973
+ GCC_except_table9975
+ GCC_except_table9994
+ OBJC_IVAR_$_HMAccessory._supportsSurroundSystemFrontRoleCapability
+ OBJC_IVAR_$_HMAccessory._supportsSurroundSystemRearRoleCapability
+ OBJC_IVAR_$_HMResidentDevice._supportsSurroundConfiguration
+ OBJC_IVAR_$_HMSurroundSystem._frontLeftDestinationIdentifier
+ OBJC_IVAR_$_HMSurroundSystem._frontRightDestinationIdentifier
+ OBJC_IVAR_$_HMSurroundSystem._rearLeftDestinationIdentifier
+ OBJC_IVAR_$_HMSurroundSystem._rearRightDestinationIdentifier
+ OBJC_IVAR_$_HMSurroundSystemConfigurationRequest._frontLeftAccessory
+ OBJC_IVAR_$_HMSurroundSystemConfigurationRequest._frontRightAccessory
+ OBJC_IVAR_$_HMSurroundSystemConfigurationRequest._identifier
+ OBJC_IVAR_$_HMSurroundSystemConfigurationRequest._rearLeftAccessory
+ OBJC_IVAR_$_HMSurroundSystemConfigurationRequest._rearRightAccessory
+ OBJC_IVAR_$_HMSurroundSystemConfigurationRequest._sourceAccessory
+ OBJC_IVAR_$_HMSurroundSystemConfigurationRequestPayload._frontLeftAccessoryUUID
+ OBJC_IVAR_$_HMSurroundSystemConfigurationRequestPayload._frontRightAccessoryUUID
+ OBJC_IVAR_$_HMSurroundSystemConfigurationRequestPayload._identifier
+ OBJC_IVAR_$_HMSurroundSystemConfigurationRequestPayload._rearLeftAccessoryUUID
+ OBJC_IVAR_$_HMSurroundSystemConfigurationRequestPayload._rearRightAccessoryUUID
+ OBJC_IVAR_$_HMSurroundSystemConfigurationRequestPayload._sourceAccessoryUUID
+ OBJC_IVAR_$_HMSurroundSystemUpdateRolesRequest._frontLeftAccessory
+ OBJC_IVAR_$_HMSurroundSystemUpdateRolesRequest._frontRightAccessory
+ OBJC_IVAR_$_HMSurroundSystemUpdateRolesRequest._rearLeftAccessory
+ OBJC_IVAR_$_HMSurroundSystemUpdateRolesRequest._rearRightAccessory
+ OBJC_IVAR_$_HMSurroundSystemUpdateRolesRequest._surroundSystem
+ _HMAccessorySupportsSurroundSystemFrontRoleCodingKey
+ _HMAccessorySupportsSurroundSystemRearRoleCodingKey
+ _HMResidentDeviceSupportsSurroundConfigurationCodingKey
+ _OBJC_$_PROP_LIST_HMMediaDestination
+ _OBJC_CLASS_$_HMMutableSurroundSystem
+ _OBJC_CLASS_$_HMSurroundSystem
+ _OBJC_CLASS_$_HMSurroundSystemConfigurationRequest
+ _OBJC_CLASS_$_HMSurroundSystemConfigurationRequestPayload
+ _OBJC_CLASS_$_HMSurroundSystemUpdateRolesRequest
+ _OBJC_METACLASS_$_HMMutableSurroundSystem
+ _OBJC_METACLASS_$_HMSurroundSystem
+ _OBJC_METACLASS_$_HMSurroundSystemConfigurationRequest
+ _OBJC_METACLASS_$_HMSurroundSystemConfigurationRequestPayload
+ _OBJC_METACLASS_$_HMSurroundSystemUpdateRolesRequest
+ __OBJC_$_CLASS_METHODS_HMSurroundSystem
+ __OBJC_$_CLASS_METHODS_HMSurroundSystemConfigurationRequest
+ __OBJC_$_CLASS_METHODS_HMSurroundSystemConfigurationRequestPayload
+ __OBJC_$_CLASS_METHODS_HMSurroundSystemUpdateRolesRequest
+ __OBJC_$_CLASS_PROP_LIST_HMSurroundSystem
+ __OBJC_$_INSTANCE_METHODS_HMMutableSurroundSystem
+ __OBJC_$_INSTANCE_METHODS_HMProtoAccessoryCapabilities(UnobfuscatedAliases)
+ __OBJC_$_INSTANCE_METHODS_HMSurroundSystem
+ __OBJC_$_INSTANCE_METHODS_HMSurroundSystemConfigurationRequest
+ __OBJC_$_INSTANCE_METHODS_HMSurroundSystemConfigurationRequestPayload
+ __OBJC_$_INSTANCE_METHODS_HMSurroundSystemUpdateRolesRequest
+ __OBJC_$_INSTANCE_VARIABLES_HMSurroundSystem
+ __OBJC_$_INSTANCE_VARIABLES_HMSurroundSystemConfigurationRequest
+ __OBJC_$_INSTANCE_VARIABLES_HMSurroundSystemConfigurationRequestPayload
+ __OBJC_$_INSTANCE_VARIABLES_HMSurroundSystemUpdateRolesRequest
+ __OBJC_$_PROP_LIST_HMMutableSurroundSystem
+ __OBJC_$_PROP_LIST_HMSurroundSystem
+ __OBJC_$_PROP_LIST_HMSurroundSystemConfigurationRequest
+ __OBJC_$_PROP_LIST_HMSurroundSystemConfigurationRequestPayload
+ __OBJC_$_PROP_LIST_HMSurroundSystemUpdateRolesRequest
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HMMediaDestinationControllerInternalDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HMMediaDestinationControllerInternalDelegate
+ __OBJC_CLASS_PROTOCOLS_$_HMSurroundSystemConfigurationRequest
+ __OBJC_CLASS_PROTOCOLS_$_HMSurroundSystemConfigurationRequestPayload
+ __OBJC_CLASS_PROTOCOLS_$_HMSurroundSystemUpdateRolesRequest
+ __OBJC_CLASS_RO_$_HMMutableSurroundSystem
+ __OBJC_CLASS_RO_$_HMSurroundSystem
+ __OBJC_CLASS_RO_$_HMSurroundSystemConfigurationRequest
+ __OBJC_CLASS_RO_$_HMSurroundSystemConfigurationRequestPayload
+ __OBJC_CLASS_RO_$_HMSurroundSystemUpdateRolesRequest
+ __OBJC_METACLASS_RO_$_HMMutableSurroundSystem
+ __OBJC_METACLASS_RO_$_HMSurroundSystem
+ __OBJC_METACLASS_RO_$_HMSurroundSystemConfigurationRequest
+ __OBJC_METACLASS_RO_$_HMSurroundSystemConfigurationRequestPayload
+ __OBJC_METACLASS_RO_$_HMSurroundSystemUpdateRolesRequest
+ ___120-[HMAccessory mediaDestinationController:didGetUpdateDestinationRequestWithSurroundSystemDestination:completionHandler:]_block_invoke
+ ___120-[HMCurrentMediaGroupProvider _notifyClientOfCurrentMediaGroupWithCurrentAccessory:surroundSystem:sourceAccessory:home:]_block_invoke
+ ___120-[HMCurrentMediaGroupProvider _notifyClientOfCurrentMediaGroupWithCurrentAccessory:surroundSystem:sourceAccessory:home:]_block_invoke_2
+ ___48-[HMSurroundSystem destinationUniqueIdentifiers]_block_invoke
+ ___49+[HMSurroundSystemUpdateRolesRequest logCategory]_block_invoke
+ ___51+[HMSurroundSystemConfigurationRequest logCategory]_block_invoke
+ ___55-[HMAccessory accessoryWithAudioDestinationIdentifier:]_block_invoke
+ ___58+[HMSurroundSystemConfigurationRequestPayload logCategory]_block_invoke
+ ___60-[HMHome accessoryWithAudioDestinationControllerIdentifier:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e43_"HMMediaGroupParticipant"16?0"NSString"8l
+ ___block_descriptor_56_e8_32s40s48bs_e30_v24?0"NSString"8"NSError"16l
+ _objc_msgSend$_mergeWithCurrentAppleTVAccessory:surroundSystemDestination:home:
+ _objc_msgSend$_mergeWithCurrentHomePodAccessory:surroundSystem:home:
+ _objc_msgSend$_notifyClientOfCurrentMediaGroupWithCurrentAccessory:surroundSystem:sourceAccessory:home:
+ _objc_msgSend$_participantRoleForSurroundSystem:destinationIdentifier:
+ _objc_msgSend$accessoriesFor:
+ _objc_msgSend$accessoriesInWrongRoom
+ _objc_msgSend$accessoryWithAudioDestinationControllerIdentifier:
+ _objc_msgSend$accessoryWithAudioDestinationIdentifier:
+ _objc_msgSend$allSourceAccessoryIdentifiersWithCheckSurroundCapability:
+ _objc_msgSend$availableDestinationIdentifiersForHomeTheaterSurround
+ _objc_msgSend$availableDestinationIdentifiersForMatchingHomeTheaterSurroundWithSelectedDestinationIdentifiers:selectedStereoDestinationIdentifiers:otherDestinationIdentifiers:otherStereoDestinationIdentifiers:
+ _objc_msgSend$availableDestinationIdentifiersForMixedHomeTheaterSurroundWithSelectedFrontDestinationIdentifiers:selectedFrontStereoDestinationIdentifiers:selectedRearDestinationIdentifiers:selectedRearStereoDestinationIdentifiers:otherFrontDestinationIdentifiers:otherFrontStereoDestinationIdentifiers:otherRearDestinationIdentifiers:otherRearStereoDestinationIdentifiers:
+ _objc_msgSend$availableSourceAccessoryIdentifiersForHomeTheaterSurround
+ _objc_msgSend$canFormHomeTheaterSurround
+ _objc_msgSend$configurationRequestWithSourceAccessory:
+ _objc_msgSend$containsSurroundSystemFrontRoleSupportedOptions
+ _objc_msgSend$containsSurroundSystemRearRoleSupportedOptions
+ _objc_msgSend$createGroupWithConfigurationRequest:completion:
+ _objc_msgSend$derivedDestinationIdentifierForGroupIdentifier:
+ _objc_msgSend$destinationForGroup:
+ _objc_msgSend$destinationIdentifiersForSurroundFrom:frontRole:
+ _objc_msgSend$frontLeftAccessory
+ _objc_msgSend$frontLeftAccessoryUUID
+ _objc_msgSend$frontLeftDestinationIdentifier
+ _objc_msgSend$frontRightAccessory
+ _objc_msgSend$frontRightAccessoryUUID
+ _objc_msgSend$frontRightDestinationIdentifier
+ _objc_msgSend$groupForChildDestination:
+ _objc_msgSend$groupForDestination:
+ _objc_msgSend$hasFrontLeftDestinationIdentifier
+ _objc_msgSend$hasFrontRightDestinationIdentifier
+ _objc_msgSend$hasPossibleOrValidSourceWithCheckSurroundCapability:
+ _objc_msgSend$hasRearLeftDestinationIdentifier
+ _objc_msgSend$hasRearRightDestinationIdentifier
+ _objc_msgSend$hasSelectedSurroundSystemDestination
+ _objc_msgSend$hasSurroundSystem
+ _objc_msgSend$hasValidSelectedSourceAccessoryWithCheckSurroundCapability:
+ _objc_msgSend$hasValidSelectedSurroundDestinations
+ _objc_msgSend$homeTheaterSystemForAudioDestinationIdentifier:
+ _objc_msgSend$homeTheaterSystemForSurroundSystem:
+ _objc_msgSend$initWithIdentifier:parentIdentifier:name:defaultName:associatedGroupIdentifier:frontLeftDestinationIdentifier:frontRightDestinationIdentifier:rearLeftDestinationIdentifier:rearRightDestinationIdentifier:
+ _objc_msgSend$initWithIdentifier:sourceAccessory:frontLeftAccessory:frontRightAccessory:rearLeftAccessory:rearRightAccessory:
+ _objc_msgSend$initWithIdentifier:sourceAccessoryUUID:frontLeftAccessoryUUID:frontRightAccessoryUUID:rearLeftAccessoryUUID:rearRightAccessoryUUID:
+ _objc_msgSend$internalDelegate
+ _objc_msgSend$isUniqueAccessories
+ _objc_msgSend$isValidAllFrontConfiguration
+ _objc_msgSend$isValidAllRearConfiguration
+ _objc_msgSend$isValidHomePodConfiguration
+ _objc_msgSend$isValidMixConfiguration
+ _objc_msgSend$isValidSourceAccessory
+ _objc_msgSend$mediaDestinationController:didGetUpdateDestinationRequestWithSurroundSystemDestination:completionHandler:
+ _objc_msgSend$mediaGroupsController:sourceAccessoryForSurroundSystem:
+ _objc_msgSend$mediaSystemFor:
+ _objc_msgSend$otherDestinations
+ _objc_msgSend$rearLeftAccessory
+ _objc_msgSend$rearLeftAccessoryUUID
+ _objc_msgSend$rearLeftDestinationIdentifier
+ _objc_msgSend$rearRightAccessory
+ _objc_msgSend$rearRightAccessoryUUID
+ _objc_msgSend$rearRightDestinationIdentifier
+ _objc_msgSend$setSupports1299912b90f3:
+ _objc_msgSend$setSupports3826361c217c:
+ _objc_msgSend$setSupportsSurroundConfiguration:
+ _objc_msgSend$setSupportsSurroundSystemFrontRoleCapability:
+ _objc_msgSend$setSupportsSurroundSystemRearRoleCapability:
+ _objc_msgSend$setSupportsd711b2f2f198:
+ _objc_msgSend$setSupportseac3b4015a2e:
+ _objc_msgSend$sourceAccessory
+ _objc_msgSend$sourceAccessoryUUID
+ _objc_msgSend$stereoDestinationIdentifiersForSurroundFrom:frontRole:
+ _objc_msgSend$stereoDestinationsForSurroundFrom:frontRole:
+ _objc_msgSend$supports1299912b90f3
+ _objc_msgSend$supports3826361c217c
+ _objc_msgSend$supportsAudioDestinationSurroundSystemFrontRole
+ _objc_msgSend$supportsAudioDestinationSurroundSystemRearRole
+ _objc_msgSend$supportsHomeTheaterSourceSurroundSystem
+ _objc_msgSend$supportsSurroundConfiguration
+ _objc_msgSend$supportsSurroundSystemDestinations
+ _objc_msgSend$supportsSurroundSystemFrontRole
+ _objc_msgSend$supportsSurroundSystemFrontRoleCapability
+ _objc_msgSend$supportsSurroundSystemRearRole
+ _objc_msgSend$supportsSurroundSystemRearRoleCapability
+ _objc_msgSend$supportsd711b2f2f198
+ _objc_msgSend$supportseac3b4015a2e
+ _objc_msgSend$surroundSystem
+ _objc_msgSend$surroundSystemDestinationIdentifiers
+ _objc_msgSend$surroundSystemDestinations
+ _objc_msgSend$surroundSystemIdentifier
+ _objc_msgSend$surroundSystems
+ _objc_msgSend$updateSurroundSystemRolesWithRequest:completion:
+ _objc_msgSend$updateToSurroundSystemDestination:completionHandler:
+ _symbolic _____ySSG s11_SetStorageC
+ logCategory._hmf_once_t744
+ logCategory._hmf_once_t75
+ logCategory._hmf_once_t822
+ logCategory._hmf_once_t92
+ logCategory._hmf_once_v745
+ logCategory._hmf_once_v76
+ logCategory._hmf_once_v823
+ logCategory._hmf_once_v93
- GCC_except_table10039
- GCC_except_table10068
- GCC_except_table10069
- GCC_except_table10070
- GCC_except_table10072
- GCC_except_table10075
- GCC_except_table10076
- GCC_except_table10082
- GCC_except_table10231
- GCC_except_table10232
- GCC_except_table10233
- GCC_except_table10237
- GCC_except_table10292
- GCC_except_table10315
- GCC_except_table10395
- GCC_except_table10397
- GCC_except_table10399
- GCC_except_table10401
- GCC_except_table10409
- GCC_except_table10459
- GCC_except_table10471
- GCC_except_table10473
- GCC_except_table10663
- GCC_except_table10664
- GCC_except_table10699
- GCC_except_table10732
- GCC_except_table10735
- GCC_except_table10738
- GCC_except_table10740
- GCC_except_table10806
- GCC_except_table10826
- GCC_except_table10827
- GCC_except_table10828
- GCC_except_table10867
- GCC_except_table10869
- GCC_except_table10871
- GCC_except_table10936
- GCC_except_table10968
- GCC_except_table10970
- GCC_except_table10974
- GCC_except_table10991
- GCC_except_table10993
- GCC_except_table10999
- GCC_except_table11003
- GCC_except_table11006
- GCC_except_table11013
- GCC_except_table11017
- GCC_except_table11023
- GCC_except_table11035
- GCC_except_table11038
- GCC_except_table11046
- GCC_except_table11047
- GCC_except_table11049
- GCC_except_table11051
- GCC_except_table11053
- GCC_except_table11073
- GCC_except_table11083
- GCC_except_table11299
- GCC_except_table11312
- GCC_except_table11353
- GCC_except_table11356
- GCC_except_table11358
- GCC_except_table11371
- GCC_except_table11372
- GCC_except_table11440
- GCC_except_table11443
- GCC_except_table11444
- GCC_except_table11791
- GCC_except_table11829
- GCC_except_table11842
- GCC_except_table12219
- GCC_except_table12220
- GCC_except_table12222
- GCC_except_table12223
- GCC_except_table12233
- GCC_except_table12257
- GCC_except_table12258
- GCC_except_table12261
- GCC_except_table12264
- GCC_except_table12273
- GCC_except_table12274
- GCC_except_table12275
- GCC_except_table12372
- GCC_except_table12398
- GCC_except_table12400
- GCC_except_table12404
- GCC_except_table12405
- GCC_except_table12453
- GCC_except_table12479
- GCC_except_table12492
- GCC_except_table12518
- GCC_except_table12522
- GCC_except_table12571
- GCC_except_table12572
- GCC_except_table12573
- GCC_except_table12574
- GCC_except_table12575
- GCC_except_table12576
- GCC_except_table12577
- GCC_except_table12578
- GCC_except_table12579
- GCC_except_table12580
- GCC_except_table12581
- GCC_except_table12582
- GCC_except_table12583
- GCC_except_table12584
- GCC_except_table12585
- GCC_except_table12586
- GCC_except_table12609
- GCC_except_table12636
- GCC_except_table12746
- GCC_except_table12747
- GCC_except_table12750
- GCC_except_table12816
- GCC_except_table12818
- GCC_except_table12826
- GCC_except_table12837
- GCC_except_table12839
- GCC_except_table12844
- GCC_except_table12845
- GCC_except_table12846
- GCC_except_table13070
- GCC_except_table13271
- GCC_except_table13274
- GCC_except_table13279
- GCC_except_table13283
- GCC_except_table13291
- GCC_except_table13296
- GCC_except_table13298
- GCC_except_table13303
- GCC_except_table13304
- GCC_except_table13306
- GCC_except_table13388
- GCC_except_table13390
- GCC_except_table13409
- GCC_except_table13410
- GCC_except_table13411
- GCC_except_table13412
- GCC_except_table13417
- GCC_except_table13431
- GCC_except_table13437
- GCC_except_table13440
- GCC_except_table13444
- GCC_except_table13522
- GCC_except_table13530
- GCC_except_table13531
- GCC_except_table13536
- GCC_except_table13542
- GCC_except_table13544
- GCC_except_table13546
- GCC_except_table13548
- GCC_except_table13550
- GCC_except_table13552
- GCC_except_table13554
- GCC_except_table13687
- GCC_except_table13743
- GCC_except_table13744
- GCC_except_table13745
- GCC_except_table13746
- GCC_except_table13756
- GCC_except_table13757
- GCC_except_table13781
- GCC_except_table13782
- GCC_except_table13858
- GCC_except_table13880
- GCC_except_table13883
- GCC_except_table14031
- GCC_except_table14201
- GCC_except_table14207
- GCC_except_table14210
- GCC_except_table14266
- GCC_except_table14301
- GCC_except_table14307
- GCC_except_table14311
- GCC_except_table14312
- GCC_except_table14317
- GCC_except_table14319
- GCC_except_table14320
- GCC_except_table14321
- GCC_except_table14322
- GCC_except_table14323
- GCC_except_table14324
- GCC_except_table14325
- GCC_except_table14332
- GCC_except_table14463
- GCC_except_table14473
- GCC_except_table14570
- GCC_except_table14620
- GCC_except_table14666
- GCC_except_table14669
- GCC_except_table14690
- GCC_except_table14692
- GCC_except_table14693
- GCC_except_table1528
- GCC_except_table1555
- GCC_except_table1621
- GCC_except_table1692
- GCC_except_table1697
- GCC_except_table1715
- GCC_except_table1783
- GCC_except_table1785
- GCC_except_table1796
- GCC_except_table1798
- GCC_except_table1938
- GCC_except_table1992
- GCC_except_table1995
- GCC_except_table2069
- GCC_except_table2156
- GCC_except_table2157
- GCC_except_table2206
- GCC_except_table2493
- GCC_except_table2496
- GCC_except_table2499
- GCC_except_table2508
- GCC_except_table2517
- GCC_except_table2530
- GCC_except_table2532
- GCC_except_table2533
- GCC_except_table2539
- GCC_except_table3106
- GCC_except_table3111
- GCC_except_table3137
- GCC_except_table3140
- GCC_except_table3153
- GCC_except_table3185
- GCC_except_table3188
- GCC_except_table3214
- GCC_except_table3216
- GCC_except_table3218
- GCC_except_table3220
- GCC_except_table3367
- GCC_except_table3370
- GCC_except_table3378
- GCC_except_table3379
- GCC_except_table3400
- GCC_except_table3427
- GCC_except_table3428
- GCC_except_table3486
- GCC_except_table3488
- GCC_except_table3491
- GCC_except_table3492
- GCC_except_table3518
- GCC_except_table3520
- GCC_except_table3528
- GCC_except_table3530
- GCC_except_table3537
- GCC_except_table3538
- GCC_except_table3539
- GCC_except_table3541
- GCC_except_table3543
- GCC_except_table3545
- GCC_except_table3628
- GCC_except_table3651
- GCC_except_table3654
- GCC_except_table3657
- GCC_except_table3660
- GCC_except_table3663
- GCC_except_table3666
- GCC_except_table3669
- GCC_except_table3734
- GCC_except_table3735
- GCC_except_table3781
- GCC_except_table3788
- GCC_except_table3789
- GCC_except_table3790
- GCC_except_table3793
- GCC_except_table3794
- GCC_except_table3797
- GCC_except_table3805
- GCC_except_table3827
- GCC_except_table3836
- GCC_except_table3840
- GCC_except_table3843
- GCC_except_table3846
- GCC_except_table3887
- GCC_except_table3891
- GCC_except_table3895
- GCC_except_table3900
- GCC_except_table3908
- GCC_except_table3912
- GCC_except_table3921
- GCC_except_table3923
- GCC_except_table4167
- GCC_except_table4172
- GCC_except_table4176
- GCC_except_table4179
- GCC_except_table4183
- GCC_except_table4184
- GCC_except_table4189
- GCC_except_table4195
- GCC_except_table4199
- GCC_except_table4226
- GCC_except_table4228
- GCC_except_table4230
- GCC_except_table4233
- GCC_except_table4234
- GCC_except_table4236
- GCC_except_table4239
- GCC_except_table4314
- GCC_except_table4328
- GCC_except_table4331
- GCC_except_table4333
- GCC_except_table4336
- GCC_except_table4343
- GCC_except_table4398
- GCC_except_table4463
- GCC_except_table4478
- GCC_except_table4481
- GCC_except_table4573
- GCC_except_table4574
- GCC_except_table4578
- GCC_except_table4583
- GCC_except_table4587
- GCC_except_table4590
- GCC_except_table4592
- GCC_except_table4858
- GCC_except_table4861
- GCC_except_table4873
- GCC_except_table4949
- GCC_except_table4995
- GCC_except_table5088
- GCC_except_table5283
- GCC_except_table5295
- GCC_except_table5297
- GCC_except_table5322
- GCC_except_table5324
- GCC_except_table5325
- GCC_except_table5380
- GCC_except_table5395
- GCC_except_table5761
- GCC_except_table5768
- GCC_except_table5773
- GCC_except_table5970
- GCC_except_table6025
- GCC_except_table6227
- GCC_except_table6229
- GCC_except_table6236
- GCC_except_table6244
- GCC_except_table6276
- GCC_except_table6281
- GCC_except_table6284
- GCC_except_table6298
- GCC_except_table6303
- GCC_except_table6309
- GCC_except_table6314
- GCC_except_table6319
- GCC_except_table6324
- GCC_except_table6329
- GCC_except_table6333
- GCC_except_table6385
- GCC_except_table6389
- GCC_except_table6399
- GCC_except_table6404
- GCC_except_table6423
- GCC_except_table6430
- GCC_except_table6448
- GCC_except_table6450
- GCC_except_table6455
- GCC_except_table6460
- GCC_except_table6467
- GCC_except_table6472
- GCC_except_table6514
- GCC_except_table6561
- GCC_except_table6570
- GCC_except_table6613
- GCC_except_table6615
- GCC_except_table6630
- GCC_except_table6674
- GCC_except_table6676
- GCC_except_table6694
- GCC_except_table6740
- GCC_except_table6835
- GCC_except_table6855
- GCC_except_table6856
- GCC_except_table6857
- GCC_except_table6859
- GCC_except_table6862
- GCC_except_table6863
- GCC_except_table6865
- GCC_except_table7212
- GCC_except_table7218
- GCC_except_table7220
- GCC_except_table7230
- GCC_except_table7231
- GCC_except_table7436
- GCC_except_table7440
- GCC_except_table7547
- GCC_except_table7551
- GCC_except_table7553
- GCC_except_table7759
- GCC_except_table7762
- GCC_except_table7854
- GCC_except_table7883
- GCC_except_table8033
- GCC_except_table8042
- GCC_except_table8055
- GCC_except_table8062
- GCC_except_table8101
- GCC_except_table8103
- GCC_except_table8138
- GCC_except_table8140
- GCC_except_table8142
- GCC_except_table8144
- GCC_except_table8151
- GCC_except_table8159
- GCC_except_table8169
- GCC_except_table8181
- GCC_except_table8187
- GCC_except_table8270
- GCC_except_table8281
- GCC_except_table8291
- GCC_except_table8293
- GCC_except_table8295
- GCC_except_table8297
- GCC_except_table8299
- GCC_except_table8305
- GCC_except_table8309
- GCC_except_table8322
- GCC_except_table8324
- GCC_except_table8326
- GCC_except_table8328
- GCC_except_table8355
- GCC_except_table8385
- GCC_except_table8444
- GCC_except_table8453
- GCC_except_table8570
- GCC_except_table8625
- GCC_except_table8627
- GCC_except_table8629
- GCC_except_table8651
- GCC_except_table8681
- GCC_except_table8693
- GCC_except_table8718
- GCC_except_table8724
- GCC_except_table8735
- GCC_except_table8737
- GCC_except_table8739
- GCC_except_table8741
- GCC_except_table8743
- GCC_except_table8745
- GCC_except_table8747
- GCC_except_table8749
- GCC_except_table8751
- GCC_except_table8753
- GCC_except_table8755
- GCC_except_table8757
- GCC_except_table8759
- GCC_except_table8764
- GCC_except_table8778
- GCC_except_table8804
- GCC_except_table8806
- GCC_except_table8831
- GCC_except_table8844
- GCC_except_table8862
- GCC_except_table9041
- GCC_except_table9392
- GCC_except_table9435
- GCC_except_table9528
- GCC_except_table9537
- GCC_except_table9712
- GCC_except_table9714
- GCC_except_table9715
- GCC_except_table9716
- GCC_except_table9718
- GCC_except_table9720
- GCC_except_table9721
- GCC_except_table9722
- GCC_except_table9757
- GCC_except_table9760
- GCC_except_table9761
- GCC_except_table9764
- GCC_except_table9767
- GCC_except_table9768
- GCC_except_table9811
- GCC_except_table9812
- GCC_except_table9813
- GCC_except_table9820
- GCC_except_table9821
- GCC_except_table9823
- GCC_except_table9842
- GCC_except_table9911
- GCC_except_table9946
- GCC_except_table9955
- GCC_except_table9969
- __OBJC_$_INSTANCE_METHODS_HMProtoAccessoryCapabilities
- __OBJC_$_PROP_LIST_HMProtoAccessoryCapabilities
- _objc_msgSend$allSourceAccessoryIdentifiers
- _objc_msgSend$hasPossibleOrValidSource
- _objc_msgSend$hasValidSelectedSourceAccessory
- logCategory._hmf_once_t105
- logCategory._hmf_once_t22
- logCategory._hmf_once_t71
- logCategory._hmf_once_t740
- logCategory._hmf_once_t810
- logCategory._hmf_once_t87
- logCategory._hmf_once_v106
- logCategory._hmf_once_v23
- logCategory._hmf_once_v72
- logCategory._hmf_once_v741
- logCategory._hmf_once_v811
- logCategory._hmf_once_v88
CStrings:
+ ", frontLeftAccessoryUUID: %@"
+ ", frontLeftDestinationIdentifier: %@"
+ ", frontRightAccessoryUUID: %@"
+ ", frontRightDestinationIdentifier: %@"
+ ", isValid: %@"
+ ", needsRoomChangeCount: %@"
+ ", rearLeftAccessoryUUID: %@"
+ ", rearLeftDestinationIdentifier: %@"
+ ", rearRightAccessoryUUID: %@"
+ ", rearRightDestinationIdentifier: %@"
+ ", sourceAccessoryUUID: %@"
+ ", surroundSystemIdentifier: %@"
+ "73C81D06-E21A-4614-93C9-038DC106F5E3"
+ "<Merge> Notifying client of updated supportsSurroundConfiguration value: %@"
+ "<Merge> Updating supportsSurroundConfiguration from %@ to %@"
+ "<SS %@ n:%@ L:%@ R:%@ l:%@ r:%@>"
+ "@\"HMMediaGroupParticipant\"16@?0@\"NSString\"8"
+ "Configured surround system: %@"
+ "Failed to configure surround system destination: %@ due to no home for controller: %@"
+ "Failed to configure surround system destination: %@ due to no surround system in groups controller: %@"
+ "Failed to configure surround system: %@ due to unresolved role accessories front left: %@ front right: %@ rear left: %@ rear right: %@"
+ "Failed to configure surround system: %@ with error domain: %@ code: %@"
+ "Failed to get source accessory due to no accessory with destination controller: %@"
+ "Failed to get source accessory due to no home theater group for surround system: %@"
+ "Failed to merge surround system home theater due to invalid participant count: %@"
+ "Failed to merge surround system home theater due to no surround system for destination: %@ in groups controller: %@"
+ "Failed to merge with surround system due to no destination controller for surround system: %@ destination: %@"
+ "Failed to parse surround system payload: %@"
+ "Failed to update surround system roles due to no source accessory for group: %@ from data source: %@"
+ "Failed to update to surround system destination: %@ due to no internal delegate"
+ "HM.ac.supportsSurroundSystemFrontRole"
+ "HM.ac.supportsSurroundSystemRearRole"
+ "HMCurrentMediaGroupTypeHomeTheaterSurroundSystem"
+ "HMMediaDestinationSurroundSystem"
+ "HMMediaGroupParticipantRoleSurroundSystemFrontLeft"
+ "HMMediaGroupParticipantRoleSurroundSystemFrontRight"
+ "HMMediaGroupParticipantRoleSurroundSystemRearLeft"
+ "HMMediaGroupParticipantRoleSurroundSystemRearRight"
+ "HMResidentDeviceSupportsSurroundConfigurationCodingKey"
+ "HMSurroundSystemAssociatedGroupIdentifierCodingKey"
+ "HMSurroundSystemConfigurationRequest"
+ "HMSurroundSystemDataRoomNameSentinel"
+ "HMSurroundSystemDefaultNameCodingKey"
+ "HMSurroundSystemFrontLeftAccessoryUUID"
+ "HMSurroundSystemFrontLeftDestinationIdentifierCodingKey"
+ "HMSurroundSystemFrontRightAccessoryUUID"
+ "HMSurroundSystemFrontRightDestinationIdentifierCodingKey"
+ "HMSurroundSystemIdentifier"
+ "HMSurroundSystemIdentifierCodingKey"
+ "HMSurroundSystemNameCodingKey"
+ "HMSurroundSystemParentIdentifierCodingKey"
+ "HMSurroundSystemRearLeftAccessoryUUID"
+ "HMSurroundSystemRearLeftDestinationIdentifierCodingKey"
+ "HMSurroundSystemRearRightAccessoryUUID"
+ "HMSurroundSystemRearRightDestinationIdentifierCodingKey"
+ "HMSurroundSystemSourceAccessoryUUID"
+ "Handing update destination request for surround system destination: %@ to internal delegate: %@"
+ "Handling did get update destination request with surround system destination: %@ controller: %@"
+ "HomeTheaterSurround"
+ "Media.Group.SurroundSystem.ConfigurationRequest"
+ "Media.Group.SurroundSystem.ConfigurationRequest.Payload"
+ "Media.Group.SurroundSystem.UpdateRolesRequest"
+ "SF "
+ "SR "
+ "SS "
+ "Updating supports Surround System front role capability to %@"
+ "Updating supports Surround System rear role capability to %@"
+ "Updating surround system roles with request: %@ for group: %@"
+ "[%{public}@] <Merge> Notifying client of updated supportsSurroundConfiguration value: %@"
+ "[%{public}@] <Merge> Updating supportsSurroundConfiguration from %@ to %@"
+ "[%{public}@] Configured surround system: %@"
+ "[%{public}@] Failed to configure surround system destination: %@ due to no home for controller: %@"
+ "[%{public}@] Failed to configure surround system destination: %@ due to no surround system in groups controller: %@"
+ "[%{public}@] Failed to configure surround system: %@ due to unresolved role accessories front left: %@ front right: %@ rear left: %@ rear right: %@"
+ "[%{public}@] Failed to configure surround system: %@ with error domain: %@ code: %@"
+ "[%{public}@] Failed to get source accessory due to no accessory with destination controller: %@"
+ "[%{public}@] Failed to get source accessory due to no home theater group for surround system: %@"
+ "[%{public}@] Failed to merge surround system home theater due to invalid participant count: %@"
+ "[%{public}@] Failed to merge surround system home theater due to no surround system for destination: %@ in groups controller: %@"
+ "[%{public}@] Failed to merge with surround system due to no destination controller for surround system: %@ destination: %@"
+ "[%{public}@] Failed to parse surround system payload: %@"
+ "[%{public}@] Failed to update surround system roles due to no source accessory for group: %@ from data source: %@"
+ "[%{public}@] Failed to update to surround system destination: %@ due to no internal delegate"
+ "[%{public}@] Handing update destination request for surround system destination: %@ to internal delegate: %@"
+ "[%{public}@] Handling did get update destination request with surround system destination: %@ controller: %@"
+ "[%{public}@] Updating supports Surround System front role capability to %@"
+ "[%{public}@] Updating supports Surround System rear role capability to %@"
+ "[%{public}@] Updating surround system roles with request: %@ for group: %@"
+ "[%{public}@] [HMSurroundSystem] Failed to decode event data: %@"
+ "[%{public}@] [HMSurroundSystem] Failed to derive destination unique identifier: %@"
+ "[HMSurroundSystem] Failed to decode event data: %@"
+ "[HMSurroundSystem] Failed to derive destination unique identifier: %@"
+ "frontLeftAccessory is required"
+ "frontRightAccessory is required"
+ "rearLeftAccessory is required"
+ "rearRightAccessory is required"
+ "sourceAccessory is required"
+ "surroundSystem is required"
+ "v24@?0@\"NSString\"8@\"NSError\"16"
```
