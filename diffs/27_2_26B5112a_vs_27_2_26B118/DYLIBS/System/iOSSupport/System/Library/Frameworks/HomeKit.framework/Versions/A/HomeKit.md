## HomeKit

> `/System/iOSSupport/System/Library/Frameworks/HomeKit.framework/Versions/A/HomeKit`

```diff

 1520.2.7.4.1
-  __TEXT.__text: 0x46f4b4
-  __TEXT.__objc_methlist: 0x290a4
-  __TEXT.__const: 0x12018
+  __TEXT.__text: 0x479694
+  __TEXT.__objc_methlist: 0x298ac
+  __TEXT.__const: 0x12038
   __TEXT.__dlopen_cstrs: 0x3b7
   __TEXT.__swift5_typeref: 0x45a3
-  __TEXT.__cstring: 0x31b50
+  __TEXT.__cstring: 0x3231d
   __TEXT.__constg_swiftt: 0x3e48
   __TEXT.__swift5_reflstr: 0x2bce
   __TEXT.__swift5_fieldmd: 0x39fc

   __TEXT.__swift_as_entry: 0x2c0
   __TEXT.__swift_as_ret: 0x318
   __TEXT.__swift_as_cont: 0x680
-  __TEXT.__oslogstring: 0x58a73
+  __TEXT.__oslogstring: 0x59953
   __TEXT.__swift5_mpenum: 0x20
   __TEXT.__gcc_except_tab: 0x66c0
   __TEXT.__ustring: 0x50
-  __TEXT.__unwind_info: 0x12d98
-  __TEXT.__eh_frame: 0xd40c
+  __TEXT.__unwind_info: 0x12fe0
+  __TEXT.__eh_frame: 0xd444
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x92a0
-  __DATA_CONST.__objc_classlist: 0x13b8
+  __DATA_CONST.__const: 0x9338
+  __DATA_CONST.__objc_classlist: 0x13e0
   __DATA_CONST.__objc_catlist: 0x108
   __DATA_CONST.__objc_protolist: 0x560
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe798
+  __DATA_CONST.__objc_selrefs: 0xe9d0
   __DATA_CONST.__objc_protorefs: 0x110
-  __DATA_CONST.__objc_superrefs: 0xfc0
+  __DATA_CONST.__objc_superrefs: 0xfe0
   __DATA_CONST.__objc_arraydata: 0x14d0
-  __DATA_CONST.__got: 0x2098
-  __AUTH_CONST.__const: 0xb488
-  __AUTH_CONST.__cfstring: 0x2c980
-  __AUTH_CONST.__objc_const: 0x4a790
+  __DATA_CONST.__got: 0x20c0
+  __AUTH_CONST.__const: 0xb508
+  __AUTH_CONST.__cfstring: 0x2d000
+  __AUTH_CONST.__objc_const: 0x4b2d8
   __AUTH_CONST.__objc_intobj: 0xa08
   __AUTH_CONST.__objc_dictobj: 0x848
   __AUTH_CONST.__objc_arrayobj: 0x630
   __AUTH_CONST.__objc_doubleobj: 0x70
   __AUTH_CONST.__auth_got: 0x1fc8
-  __AUTH.__objc_data: 0x92b8
+  __AUTH.__objc_data: 0x9448
   __AUTH.__data: 0x3d48
-  __DATA.__objc_ivar: 0x28b4
-  __DATA.__data: 0x79e0
-  __DATA.__bss: 0x1bd90
+  __DATA.__objc_ivar: 0x2914
+  __DATA.__data: 0x79d0
+  __DATA.__bss: 0x1bdd0
   __DATA.__common: 0x198
   __DATA_DIRTY.__objc_data: 0x3768
-  __DATA_DIRTY.__data: 0x1a0
-  __DATA_DIRTY.__bss: 0x2a0
+  __DATA_DIRTY.__data: 0x190
+  __DATA_DIRTY.__bss: 0x290
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 21860
-  Symbols:   34207
-  CStrings:  12740
+  Functions: 22041
+  Symbols:   34517
+  CStrings:  12839
 
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
+ GCC_except_table10028
+ GCC_except_table10029
+ GCC_except_table10030
+ GCC_except_table10063
+ GCC_except_table10072
+ GCC_except_table10086
+ GCC_except_table10157
+ GCC_except_table10187
+ GCC_except_table10188
+ GCC_except_table10189
+ GCC_except_table10191
+ GCC_except_table10194
+ GCC_except_table10195
+ GCC_except_table10201
+ GCC_except_table10350
+ GCC_except_table10351
+ GCC_except_table10352
+ GCC_except_table10356
+ GCC_except_table10411
+ GCC_except_table10432
+ GCC_except_table10513
+ GCC_except_table10515
+ GCC_except_table10517
+ GCC_except_table10519
+ GCC_except_table10527
+ GCC_except_table10577
+ GCC_except_table10589
+ GCC_except_table10591
+ GCC_except_table10781
+ GCC_except_table10782
+ GCC_except_table10817
+ GCC_except_table10850
+ GCC_except_table10853
+ GCC_except_table10856
+ GCC_except_table10858
+ GCC_except_table10924
+ GCC_except_table10944
+ GCC_except_table10945
+ GCC_except_table10946
+ GCC_except_table10985
+ GCC_except_table10987
+ GCC_except_table10989
+ GCC_except_table11054
+ GCC_except_table11086
+ GCC_except_table11088
+ GCC_except_table11092
+ GCC_except_table11109
+ GCC_except_table11111
+ GCC_except_table11117
+ GCC_except_table11121
+ GCC_except_table11124
+ GCC_except_table11131
+ GCC_except_table11135
+ GCC_except_table11141
+ GCC_except_table11153
+ GCC_except_table11156
+ GCC_except_table11164
+ GCC_except_table11165
+ GCC_except_table11167
+ GCC_except_table11169
+ GCC_except_table11171
+ GCC_except_table11191
+ GCC_except_table11201
+ GCC_except_table11417
+ GCC_except_table11430
+ GCC_except_table11471
+ GCC_except_table11474
+ GCC_except_table11476
+ GCC_except_table11489
+ GCC_except_table11490
+ GCC_except_table11558
+ GCC_except_table11561
+ GCC_except_table11562
+ GCC_except_table11909
+ GCC_except_table11947
+ GCC_except_table11960
+ GCC_except_table12337
+ GCC_except_table12338
+ GCC_except_table12340
+ GCC_except_table12341
+ GCC_except_table12351
+ GCC_except_table12375
+ GCC_except_table12376
+ GCC_except_table12379
+ GCC_except_table12382
+ GCC_except_table12391
+ GCC_except_table12392
+ GCC_except_table12393
+ GCC_except_table12490
+ GCC_except_table12516
+ GCC_except_table12518
+ GCC_except_table12522
+ GCC_except_table12523
+ GCC_except_table12571
+ GCC_except_table12597
+ GCC_except_table12610
+ GCC_except_table12636
+ GCC_except_table12640
+ GCC_except_table12689
+ GCC_except_table12690
+ GCC_except_table12691
+ GCC_except_table12692
+ GCC_except_table12693
+ GCC_except_table12694
+ GCC_except_table12695
+ GCC_except_table12696
+ GCC_except_table12697
+ GCC_except_table12698
+ GCC_except_table12699
+ GCC_except_table12700
+ GCC_except_table12701
+ GCC_except_table12702
+ GCC_except_table12703
+ GCC_except_table12704
+ GCC_except_table12727
+ GCC_except_table12754
+ GCC_except_table12864
+ GCC_except_table12865
+ GCC_except_table12868
+ GCC_except_table12934
+ GCC_except_table12936
+ GCC_except_table12944
+ GCC_except_table12955
+ GCC_except_table12957
+ GCC_except_table12962
+ GCC_except_table12963
+ GCC_except_table12964
+ GCC_except_table13188
+ GCC_except_table13389
+ GCC_except_table13397
+ GCC_except_table13407
+ GCC_except_table13412
+ GCC_except_table13414
+ GCC_except_table13419
+ GCC_except_table13420
+ GCC_except_table13422
+ GCC_except_table13504
+ GCC_except_table13506
+ GCC_except_table13525
+ GCC_except_table13526
+ GCC_except_table13527
+ GCC_except_table13528
+ GCC_except_table13533
+ GCC_except_table13547
+ GCC_except_table13553
+ GCC_except_table13556
+ GCC_except_table13558
+ GCC_except_table13636
+ GCC_except_table13644
+ GCC_except_table13645
+ GCC_except_table13650
+ GCC_except_table13656
+ GCC_except_table13658
+ GCC_except_table13660
+ GCC_except_table13662
+ GCC_except_table13664
+ GCC_except_table13666
+ GCC_except_table13668
+ GCC_except_table13801
+ GCC_except_table13857
+ GCC_except_table13858
+ GCC_except_table13859
+ GCC_except_table13860
+ GCC_except_table13870
+ GCC_except_table13871
+ GCC_except_table13895
+ GCC_except_table13896
+ GCC_except_table13972
+ GCC_except_table13994
+ GCC_except_table13997
+ GCC_except_table14145
+ GCC_except_table14345
+ GCC_except_table14351
+ GCC_except_table14354
+ GCC_except_table14410
+ GCC_except_table14445
+ GCC_except_table14451
+ GCC_except_table14455
+ GCC_except_table14456
+ GCC_except_table14461
+ GCC_except_table14463
+ GCC_except_table14464
+ GCC_except_table14465
+ GCC_except_table14466
+ GCC_except_table14467
+ GCC_except_table14468
+ GCC_except_table14469
+ GCC_except_table14476
+ GCC_except_table14617
+ GCC_except_table14712
+ GCC_except_table14760
+ GCC_except_table14762
+ GCC_except_table14808
+ GCC_except_table14811
+ GCC_except_table14832
+ GCC_except_table14834
+ GCC_except_table14835
+ GCC_except_table1511
+ GCC_except_table1537
+ GCC_except_table1603
+ GCC_except_table1678
+ GCC_except_table1681
+ GCC_except_table1699
+ GCC_except_table1767
+ GCC_except_table1769
+ GCC_except_table1780
+ GCC_except_table1782
+ GCC_except_table1921
+ GCC_except_table1977
+ GCC_except_table1980
+ GCC_except_table2054
+ GCC_except_table2141
+ GCC_except_table2142
+ GCC_except_table2191
+ GCC_except_table2478
+ GCC_except_table2484
+ GCC_except_table2489
+ GCC_except_table2493
+ GCC_except_table2502
+ GCC_except_table2523
+ GCC_except_table2524
+ GCC_except_table2525
+ GCC_except_table2526
+ GCC_except_table3097
+ GCC_except_table3102
+ GCC_except_table3128
+ GCC_except_table3131
+ GCC_except_table3144
+ GCC_except_table3176
+ GCC_except_table3179
+ GCC_except_table3205
+ GCC_except_table3207
+ GCC_except_table3209
+ GCC_except_table3211
+ GCC_except_table3358
+ GCC_except_table3361
+ GCC_except_table3369
+ GCC_except_table3370
+ GCC_except_table3391
+ GCC_except_table3418
+ GCC_except_table3419
+ GCC_except_table3489
+ GCC_except_table3491
+ GCC_except_table3494
+ GCC_except_table3495
+ GCC_except_table3519
+ GCC_except_table3521
+ GCC_except_table3538
+ GCC_except_table3539
+ GCC_except_table3540
+ GCC_except_table3542
+ GCC_except_table3543
+ GCC_except_table3544
+ GCC_except_table3545
+ GCC_except_table3546
+ GCC_except_table3629
+ GCC_except_table3652
+ GCC_except_table3655
+ GCC_except_table3658
+ GCC_except_table3661
+ GCC_except_table3664
+ GCC_except_table3667
+ GCC_except_table3670
+ GCC_except_table3735
+ GCC_except_table3736
+ GCC_except_table3789
+ GCC_except_table3790
+ GCC_except_table3791
+ GCC_except_table3794
+ GCC_except_table3795
+ GCC_except_table3796
+ GCC_except_table3798
+ GCC_except_table3806
+ GCC_except_table3835
+ GCC_except_table3839
+ GCC_except_table3842
+ GCC_except_table3845
+ GCC_except_table3886
+ GCC_except_table3890
+ GCC_except_table3894
+ GCC_except_table3899
+ GCC_except_table3907
+ GCC_except_table3911
+ GCC_except_table3920
+ GCC_except_table3922
+ GCC_except_table4166
+ GCC_except_table4170
+ GCC_except_table4174
+ GCC_except_table4182
+ GCC_except_table4191
+ GCC_except_table4195
+ GCC_except_table4199
+ GCC_except_table4228
+ GCC_except_table4230
+ GCC_except_table4232
+ GCC_except_table4235
+ GCC_except_table4236
+ GCC_except_table4238
+ GCC_except_table4241
+ GCC_except_table4316
+ GCC_except_table4330
+ GCC_except_table4333
+ GCC_except_table4335
+ GCC_except_table4338
+ GCC_except_table4345
+ GCC_except_table4400
+ GCC_except_table4467
+ GCC_except_table4482
+ GCC_except_table4485
+ GCC_except_table4577
+ GCC_except_table4578
+ GCC_except_table4585
+ GCC_except_table4589
+ GCC_except_table4592
+ GCC_except_table4594
+ GCC_except_table4602
+ GCC_except_table4864
+ GCC_except_table4867
+ GCC_except_table4879
+ GCC_except_table4955
+ GCC_except_table5001
+ GCC_except_table5094
+ GCC_except_table5289
+ GCC_except_table5301
+ GCC_except_table5328
+ GCC_except_table5329
+ GCC_except_table5330
+ GCC_except_table5331
+ GCC_except_table5386
+ GCC_except_table5396
+ GCC_except_table5765
+ GCC_except_table5772
+ GCC_except_table5777
+ GCC_except_table5974
+ GCC_except_table6029
+ GCC_except_table6231
+ GCC_except_table6233
+ GCC_except_table6248
+ GCC_except_table6269
+ GCC_except_table6280
+ GCC_except_table6285
+ GCC_except_table6288
+ GCC_except_table6302
+ GCC_except_table6307
+ GCC_except_table6318
+ GCC_except_table6323
+ GCC_except_table6328
+ GCC_except_table6333
+ GCC_except_table6337
+ GCC_except_table6342
+ GCC_except_table6393
+ GCC_except_table6397
+ GCC_except_table6405
+ GCC_except_table6410
+ GCC_except_table6429
+ GCC_except_table6453
+ GCC_except_table6455
+ GCC_except_table6457
+ GCC_except_table6460
+ GCC_except_table6465
+ GCC_except_table6472
+ GCC_except_table6477
+ GCC_except_table6481
+ GCC_except_table6518
+ GCC_except_table6561
+ GCC_except_table6570
+ GCC_except_table6613
+ GCC_except_table6615
+ GCC_except_table6630
+ GCC_except_table6755
+ GCC_except_table6757
+ GCC_except_table6775
+ GCC_except_table6821
+ GCC_except_table6916
+ GCC_except_table6936
+ GCC_except_table6937
+ GCC_except_table6938
+ GCC_except_table6940
+ GCC_except_table6943
+ GCC_except_table6944
+ GCC_except_table6946
+ GCC_except_table7295
+ GCC_except_table7301
+ GCC_except_table7303
+ GCC_except_table7313
+ GCC_except_table7314
+ GCC_except_table7519
+ GCC_except_table7630
+ GCC_except_table7634
+ GCC_except_table7636
+ GCC_except_table7637
+ GCC_except_table7845
+ GCC_except_table7943
+ GCC_except_table7962
+ GCC_except_table7972
+ GCC_except_table8122
+ GCC_except_table8131
+ GCC_except_table8144
+ GCC_except_table8151
+ GCC_except_table8190
+ GCC_except_table8192
+ GCC_except_table8227
+ GCC_except_table8229
+ GCC_except_table8231
+ GCC_except_table8233
+ GCC_except_table8240
+ GCC_except_table8258
+ GCC_except_table8270
+ GCC_except_table8276
+ GCC_except_table8363
+ GCC_except_table8372
+ GCC_except_table8374
+ GCC_except_table8384
+ GCC_except_table8386
+ GCC_except_table8388
+ GCC_except_table8390
+ GCC_except_table8392
+ GCC_except_table8398
+ GCC_except_table8402
+ GCC_except_table8415
+ GCC_except_table8417
+ GCC_except_table8419
+ GCC_except_table8421
+ GCC_except_table8448
+ GCC_except_table8478
+ GCC_except_table8565
+ GCC_except_table8572
+ GCC_except_table8689
+ GCC_except_table8744
+ GCC_except_table8748
+ GCC_except_table8770
+ GCC_except_table8800
+ GCC_except_table8812
+ GCC_except_table8837
+ GCC_except_table8843
+ GCC_except_table8854
+ GCC_except_table8856
+ GCC_except_table8858
+ GCC_except_table8860
+ GCC_except_table8862
+ GCC_except_table8864
+ GCC_except_table8866
+ GCC_except_table8868
+ GCC_except_table8870
+ GCC_except_table8872
+ GCC_except_table8874
+ GCC_except_table8876
+ GCC_except_table8878
+ GCC_except_table8883
+ GCC_except_table8897
+ GCC_except_table8898
+ GCC_except_table8921
+ GCC_except_table8923
+ GCC_except_table8948
+ GCC_except_table8961
+ GCC_except_table8979
+ GCC_except_table9158
+ GCC_except_table9509
+ GCC_except_table9552
+ GCC_except_table9645
+ GCC_except_table9654
+ GCC_except_table9829
+ GCC_except_table9831
+ GCC_except_table9832
+ GCC_except_table9833
+ GCC_except_table9835
+ GCC_except_table9837
+ GCC_except_table9838
+ GCC_except_table9839
+ GCC_except_table9874
+ GCC_except_table9881
+ GCC_except_table9884
+ GCC_except_table9885
+ GCC_except_table9928
+ GCC_except_table9929
+ GCC_except_table9930
+ GCC_except_table9937
+ GCC_except_table9938
+ GCC_except_table9940
+ GCC_except_table9959
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
+ ___block_descriptor_48_e8_32s40s_e43_"HMMediaGroupParticipant"16?0"NSString"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e30_v24?0"NSString"8"NSError"16ls32l8s40l8s48l8
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
+ logCategory._hmf_once_t744
+ logCategory._hmf_once_t75
+ logCategory._hmf_once_t822
+ logCategory._hmf_once_t92
+ logCategory._hmf_once_v745
+ logCategory._hmf_once_v76
+ logCategory._hmf_once_v823
+ logCategory._hmf_once_v93
- GCC_except_table10004
- GCC_except_table10033
- GCC_except_table10034
- GCC_except_table10035
- GCC_except_table10037
- GCC_except_table10040
- GCC_except_table10041
- GCC_except_table10047
- GCC_except_table10196
- GCC_except_table10197
- GCC_except_table10198
- GCC_except_table10202
- GCC_except_table10257
- GCC_except_table10278
- GCC_except_table10358
- GCC_except_table10360
- GCC_except_table10362
- GCC_except_table10364
- GCC_except_table10372
- GCC_except_table10422
- GCC_except_table10434
- GCC_except_table10436
- GCC_except_table10626
- GCC_except_table10627
- GCC_except_table10662
- GCC_except_table10695
- GCC_except_table10698
- GCC_except_table10701
- GCC_except_table10703
- GCC_except_table10769
- GCC_except_table10789
- GCC_except_table10790
- GCC_except_table10791
- GCC_except_table10830
- GCC_except_table10832
- GCC_except_table10834
- GCC_except_table10899
- GCC_except_table10931
- GCC_except_table10933
- GCC_except_table10937
- GCC_except_table10954
- GCC_except_table10956
- GCC_except_table10962
- GCC_except_table10966
- GCC_except_table10969
- GCC_except_table10976
- GCC_except_table10980
- GCC_except_table10986
- GCC_except_table10998
- GCC_except_table11001
- GCC_except_table11009
- GCC_except_table11010
- GCC_except_table11012
- GCC_except_table11014
- GCC_except_table11016
- GCC_except_table11036
- GCC_except_table11046
- GCC_except_table11262
- GCC_except_table11275
- GCC_except_table11316
- GCC_except_table11319
- GCC_except_table11321
- GCC_except_table11334
- GCC_except_table11335
- GCC_except_table11403
- GCC_except_table11406
- GCC_except_table11407
- GCC_except_table11754
- GCC_except_table11792
- GCC_except_table11805
- GCC_except_table12182
- GCC_except_table12183
- GCC_except_table12185
- GCC_except_table12186
- GCC_except_table12196
- GCC_except_table12220
- GCC_except_table12221
- GCC_except_table12224
- GCC_except_table12227
- GCC_except_table12236
- GCC_except_table12237
- GCC_except_table12238
- GCC_except_table12335
- GCC_except_table12361
- GCC_except_table12363
- GCC_except_table12367
- GCC_except_table12368
- GCC_except_table12416
- GCC_except_table12442
- GCC_except_table12455
- GCC_except_table12481
- GCC_except_table12485
- GCC_except_table12534
- GCC_except_table12535
- GCC_except_table12536
- GCC_except_table12537
- GCC_except_table12538
- GCC_except_table12539
- GCC_except_table12540
- GCC_except_table12541
- GCC_except_table12542
- GCC_except_table12543
- GCC_except_table12544
- GCC_except_table12545
- GCC_except_table12546
- GCC_except_table12547
- GCC_except_table12548
- GCC_except_table12549
- GCC_except_table12572
- GCC_except_table12599
- GCC_except_table12709
- GCC_except_table12710
- GCC_except_table12713
- GCC_except_table12779
- GCC_except_table12781
- GCC_except_table12789
- GCC_except_table12800
- GCC_except_table12802
- GCC_except_table12807
- GCC_except_table12808
- GCC_except_table12809
- GCC_except_table13033
- GCC_except_table13234
- GCC_except_table13237
- GCC_except_table13242
- GCC_except_table13246
- GCC_except_table13252
- GCC_except_table13257
- GCC_except_table13259
- GCC_except_table13264
- GCC_except_table13265
- GCC_except_table13267
- GCC_except_table13349
- GCC_except_table13351
- GCC_except_table13370
- GCC_except_table13371
- GCC_except_table13372
- GCC_except_table13373
- GCC_except_table13378
- GCC_except_table13398
- GCC_except_table13403
- GCC_except_table13481
- GCC_except_table13489
- GCC_except_table13490
- GCC_except_table13495
- GCC_except_table13501
- GCC_except_table13503
- GCC_except_table13505
- GCC_except_table13507
- GCC_except_table13509
- GCC_except_table13511
- GCC_except_table13513
- GCC_except_table13646
- GCC_except_table13702
- GCC_except_table13703
- GCC_except_table13704
- GCC_except_table13705
- GCC_except_table13715
- GCC_except_table13716
- GCC_except_table13740
- GCC_except_table13741
- GCC_except_table13817
- GCC_except_table13839
- GCC_except_table13842
- GCC_except_table13990
- GCC_except_table14190
- GCC_except_table14196
- GCC_except_table14199
- GCC_except_table14255
- GCC_except_table14290
- GCC_except_table14296
- GCC_except_table14300
- GCC_except_table14301
- GCC_except_table14306
- GCC_except_table14308
- GCC_except_table14309
- GCC_except_table14310
- GCC_except_table14311
- GCC_except_table14312
- GCC_except_table14313
- GCC_except_table14314
- GCC_except_table14321
- GCC_except_table14452
- GCC_except_table14462
- GCC_except_table14557
- GCC_except_table14605
- GCC_except_table14653
- GCC_except_table14656
- GCC_except_table14677
- GCC_except_table14679
- GCC_except_table14680
- GCC_except_table1509
- GCC_except_table1535
- GCC_except_table1601
- GCC_except_table1672
- GCC_except_table1675
- GCC_except_table1693
- GCC_except_table1761
- GCC_except_table1763
- GCC_except_table1774
- GCC_except_table1776
- GCC_except_table1915
- GCC_except_table1969
- GCC_except_table1972
- GCC_except_table2046
- GCC_except_table2133
- GCC_except_table2134
- GCC_except_table2183
- GCC_except_table2470
- GCC_except_table2473
- GCC_except_table2476
- GCC_except_table2485
- GCC_except_table2494
- GCC_except_table2507
- GCC_except_table2509
- GCC_except_table2510
- GCC_except_table2516
- GCC_except_table3083
- GCC_except_table3088
- GCC_except_table3114
- GCC_except_table3117
- GCC_except_table3130
- GCC_except_table3162
- GCC_except_table3165
- GCC_except_table3191
- GCC_except_table3193
- GCC_except_table3195
- GCC_except_table3197
- GCC_except_table3344
- GCC_except_table3347
- GCC_except_table3355
- GCC_except_table3356
- GCC_except_table3377
- GCC_except_table3404
- GCC_except_table3405
- GCC_except_table3475
- GCC_except_table3477
- GCC_except_table3480
- GCC_except_table3481
- GCC_except_table3505
- GCC_except_table3507
- GCC_except_table3515
- GCC_except_table3517
- GCC_except_table3524
- GCC_except_table3525
- GCC_except_table3526
- GCC_except_table3528
- GCC_except_table3530
- GCC_except_table3532
- GCC_except_table3615
- GCC_except_table3638
- GCC_except_table3641
- GCC_except_table3644
- GCC_except_table3647
- GCC_except_table3650
- GCC_except_table3653
- GCC_except_table3656
- GCC_except_table3721
- GCC_except_table3722
- GCC_except_table3768
- GCC_except_table3775
- GCC_except_table3776
- GCC_except_table3777
- GCC_except_table3780
- GCC_except_table3781
- GCC_except_table3784
- GCC_except_table3792
- GCC_except_table3814
- GCC_except_table3821
- GCC_except_table3825
- GCC_except_table3831
- GCC_except_table3872
- GCC_except_table3876
- GCC_except_table3880
- GCC_except_table3885
- GCC_except_table3893
- GCC_except_table3897
- GCC_except_table3906
- GCC_except_table3908
- GCC_except_table4152
- GCC_except_table4156
- GCC_except_table4160
- GCC_except_table4163
- GCC_except_table4167
- GCC_except_table4168
- GCC_except_table4171
- GCC_except_table4208
- GCC_except_table4210
- GCC_except_table4212
- GCC_except_table4215
- GCC_except_table4216
- GCC_except_table4218
- GCC_except_table4221
- GCC_except_table4296
- GCC_except_table4310
- GCC_except_table4313
- GCC_except_table4315
- GCC_except_table4318
- GCC_except_table4325
- GCC_except_table4380
- GCC_except_table4445
- GCC_except_table4460
- GCC_except_table4463
- GCC_except_table4555
- GCC_except_table4556
- GCC_except_table4558
- GCC_except_table4563
- GCC_except_table4567
- GCC_except_table4570
- GCC_except_table4572
- GCC_except_table4838
- GCC_except_table4841
- GCC_except_table4853
- GCC_except_table4929
- GCC_except_table4975
- GCC_except_table5068
- GCC_except_table5263
- GCC_except_table5275
- GCC_except_table5277
- GCC_except_table5302
- GCC_except_table5304
- GCC_except_table5305
- GCC_except_table5360
- GCC_except_table5370
- GCC_except_table5736
- GCC_except_table5743
- GCC_except_table5748
- GCC_except_table5945
- GCC_except_table6000
- GCC_except_table6202
- GCC_except_table6204
- GCC_except_table6211
- GCC_except_table6219
- GCC_except_table6251
- GCC_except_table6256
- GCC_except_table6259
- GCC_except_table6273
- GCC_except_table6278
- GCC_except_table6284
- GCC_except_table6289
- GCC_except_table6294
- GCC_except_table6299
- GCC_except_table6304
- GCC_except_table6308
- GCC_except_table6364
- GCC_except_table6368
- GCC_except_table6376
- GCC_except_table6381
- GCC_except_table6395
- GCC_except_table6400
- GCC_except_table6407
- GCC_except_table6423
- GCC_except_table6426
- GCC_except_table6428
- GCC_except_table6431
- GCC_except_table6443
- GCC_except_table6448
- GCC_except_table6489
- GCC_except_table6532
- GCC_except_table6541
- GCC_except_table6584
- GCC_except_table6586
- GCC_except_table6601
- GCC_except_table6643
- GCC_except_table6645
- GCC_except_table6663
- GCC_except_table6709
- GCC_except_table6804
- GCC_except_table6824
- GCC_except_table6825
- GCC_except_table6826
- GCC_except_table6828
- GCC_except_table6831
- GCC_except_table6832
- GCC_except_table6834
- GCC_except_table7181
- GCC_except_table7187
- GCC_except_table7189
- GCC_except_table7199
- GCC_except_table7200
- GCC_except_table7405
- GCC_except_table7409
- GCC_except_table7516
- GCC_except_table7520
- GCC_except_table7522
- GCC_except_table7728
- GCC_except_table7731
- GCC_except_table7823
- GCC_except_table7852
- GCC_except_table8002
- GCC_except_table8011
- GCC_except_table8024
- GCC_except_table8031
- GCC_except_table8070
- GCC_except_table8072
- GCC_except_table8107
- GCC_except_table8109
- GCC_except_table8111
- GCC_except_table8113
- GCC_except_table8120
- GCC_except_table8128
- GCC_except_table8138
- GCC_except_table8150
- GCC_except_table8156
- GCC_except_table8239
- GCC_except_table8250
- GCC_except_table8260
- GCC_except_table8262
- GCC_except_table8264
- GCC_except_table8266
- GCC_except_table8268
- GCC_except_table8274
- GCC_except_table8278
- GCC_except_table8291
- GCC_except_table8293
- GCC_except_table8295
- GCC_except_table8297
- GCC_except_table8324
- GCC_except_table8354
- GCC_except_table8413
- GCC_except_table8420
- GCC_except_table8537
- GCC_except_table8592
- GCC_except_table8594
- GCC_except_table8596
- GCC_except_table8618
- GCC_except_table8648
- GCC_except_table8660
- GCC_except_table8685
- GCC_except_table8691
- GCC_except_table8702
- GCC_except_table8704
- GCC_except_table8706
- GCC_except_table8708
- GCC_except_table8710
- GCC_except_table8712
- GCC_except_table8714
- GCC_except_table8716
- GCC_except_table8718
- GCC_except_table8720
- GCC_except_table8722
- GCC_except_table8724
- GCC_except_table8726
- GCC_except_table8731
- GCC_except_table8745
- GCC_except_table8769
- GCC_except_table8771
- GCC_except_table8796
- GCC_except_table8809
- GCC_except_table8827
- GCC_except_table9006
- GCC_except_table9357
- GCC_except_table9400
- GCC_except_table9493
- GCC_except_table9502
- GCC_except_table9677
- GCC_except_table9679
- GCC_except_table9680
- GCC_except_table9681
- GCC_except_table9683
- GCC_except_table9685
- GCC_except_table9686
- GCC_except_table9687
- GCC_except_table9722
- GCC_except_table9725
- GCC_except_table9726
- GCC_except_table9729
- GCC_except_table9732
- GCC_except_table9733
- GCC_except_table9776
- GCC_except_table9777
- GCC_except_table9778
- GCC_except_table9785
- GCC_except_table9786
- GCC_except_table9788
- GCC_except_table9807
- GCC_except_table9876
- GCC_except_table9911
- GCC_except_table9920
- GCC_except_table9934
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
