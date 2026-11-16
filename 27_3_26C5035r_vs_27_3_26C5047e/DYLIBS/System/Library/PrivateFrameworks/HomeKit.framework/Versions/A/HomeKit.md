## HomeKit

> `/System/Library/PrivateFrameworks/HomeKit.framework/Versions/A/HomeKit`

```diff

-1535.0.0.0.2
-  __TEXT.__text: 0x47ff60
-  __TEXT.__objc_methlist: 0x29c74
-  __TEXT.__const: 0x10148
+1535.3.8.0.0
+  __TEXT.__text: 0x48a7d8
+  __TEXT.__objc_methlist: 0x2a054
+  __TEXT.__const: 0x10538
   __TEXT.__dlopen_cstrs: 0x407
-  __TEXT.__swift5_typeref: 0x36df
-  __TEXT.__cstring: 0x3203c
-  __TEXT.__constg_swiftt: 0x34c0
-  __TEXT.__swift5_reflstr: 0x26d0
-  __TEXT.__swift5_fieldmd: 0x31fc
+  __TEXT.__swift5_typeref: 0x3870
+  __TEXT.__cstring: 0x32573
+  __TEXT.__constg_swiftt: 0x35d4
+  __TEXT.__swift5_reflstr: 0x2756
+  __TEXT.__swift5_fieldmd: 0x32d8
   __TEXT.__swift5_builtin: 0x8c
-  __TEXT.__swift5_assocty: 0x808
-  __TEXT.__swift5_capture: 0x9b0
+  __TEXT.__swift5_assocty: 0x828
+  __TEXT.__swift5_capture: 0x9f0
   __TEXT.__swift5_protos: 0x2c
-  __TEXT.__swift5_proto: 0xd58
-  __TEXT.__swift5_types: 0x428
-  __TEXT.__swift_as_entry: 0x280
-  __TEXT.__swift_as_ret: 0x2c4
-  __TEXT.__swift_as_cont: 0x558
-  __TEXT.__oslogstring: 0x593b0
+  __TEXT.__swift5_proto: 0xda0
+  __TEXT.__swift5_types: 0x444
+  __TEXT.__swift_as_entry: 0x288
+  __TEXT.__swift_as_ret: 0x2cc
+  __TEXT.__swift_as_cont: 0x564
+  __TEXT.__oslogstring: 0x59d02
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__gcc_except_tab: 0x68dc
-  __TEXT.__ustring: 0x50
-  __TEXT.__unwind_info: 0x12788
-  __TEXT.__eh_frame: 0xbc78
+  __TEXT.__gcc_except_tab: 0x69f4
+  __TEXT.__ustring: 0x54
+  __TEXT.__unwind_info: 0x12ae0
+  __TEXT.__eh_frame: 0xc100
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x62c8
-  __DATA_CONST.__objc_classlist: 0x13b8
+  __DATA_CONST.__const: 0x6320
+  __DATA_CONST.__objc_classlist: 0x13d8
   __DATA_CONST.__objc_catlist: 0x108
-  __DATA_CONST.__objc_protolist: 0x560
+  __DATA_CONST.__objc_protolist: 0x568
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe958
+  __DATA_CONST.__objc_selrefs: 0xeb20
   __DATA_CONST.__objc_protorefs: 0x110
-  __DATA_CONST.__objc_superrefs: 0xff0
+  __DATA_CONST.__objc_superrefs: 0x1000
   __DATA_CONST.__objc_arraydata: 0x1480
-  __DATA_CONST.__got: 0x1ef8
-  __AUTH_CONST.__const: 0xdd98
-  __AUTH_CONST.__cfstring: 0x2d400
-  __AUTH_CONST.__objc_const: 0x4b148
+  __DATA_CONST.__got: 0x1f00
+  __AUTH_CONST.__const: 0xe168
+  __AUTH_CONST.__cfstring: 0x2d7a0
+  __AUTH_CONST.__objc_const: 0x4b840
   __AUTH_CONST.__objc_intobj: 0x9f0
   __AUTH_CONST.__objc_dictobj: 0x848
   __AUTH_CONST.__objc_arrayobj: 0x600
   __AUTH_CONST.__objc_doubleobj: 0x70
-  __AUTH_CONST.__auth_got: 0x1a28
-  __AUTH.__objc_data: 0x92e0
-  __AUTH.__data: 0x3758
-  __DATA.__objc_ivar: 0x2968
-  __DATA.__data: 0x7000
-  __DATA.__bss: 0x19468
+  __AUTH_CONST.__auth_got: 0x1a38
+  __AUTH.__objc_data: 0x93f0
+  __AUTH.__data: 0x38e8
+  __DATA.__objc_ivar: 0x298c
+  __DATA.__data: 0x71c8
+  __DATA.__bss: 0x19be8
   __DATA.__common: 0xa0
   __DATA_DIRTY.__objc_data: 0x3748
-  __DATA_DIRTY.__data: 0x1b0
+  __DATA_DIRTY.__data: 0x1a8
   __DATA_DIRTY.__bss: 0x288
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 21520
-  Symbols:   33954
-  CStrings:  12773
+  Functions: 21714
+  Symbols:   34149
+  CStrings:  12842
 
Symbols:
+ +[HMPredicateUtilities validatePredicateShape:options:rejectionReason:]
+ +[HMPredicateUtilities validateStoredPredicate:]
+ +[HMUnrecognizedUserParentalControlSettings(Foundation) supportsSecureCoding]
+ -[HMAccessory defaultGroupNameForMediaDestinationController:]
+ -[HMHome _updateUnrecognizedUserSettingNamed:value:completion:]
+ -[HMHome setUnrecognizedUserSettings:]
+ -[HMHome stagedHomeTheaterRenamesForMediaGroupsController:]
+ -[HMHome unrecognizedUserSettings]
+ -[HMHome updateUnrecognizedUserAllowExplicitContent:completion:]
+ -[HMHome updateUnrecognizedUserBroadWorldKnowledgeAllowed:completion:]
+ -[HMHome updateUnrecognizedUserMathAssistanceAllowed:completion:]
+ -[HMHome updateUnrecognizedUserSafariEnabled:completion:]
+ -[HMHome updateUnrecognizedUserSensitiveTopicsAllowed:completion:]
+ -[HMHome updateUnrecognizedUserWebContentFilter:completion:]
+ -[HMHome updateUnrecognizedUserWritingAssistanceAllowed:completion:]
+ -[HMMediaDestinationController configureLastNotifiedGroupName]
+ -[HMMediaDestinationController lastNotifiedGroupName]
+ -[HMMediaDestinationController locallyStageDestination:]
+ -[HMMediaDestinationController locallyStageGroupName:]
+ -[HMMediaDestinationController setLastNotifiedGroupName:]
+ -[HMMediaGroupStageHomeTheaterRename .cxx_destruct]
+ -[HMMediaGroupStageHomeTheaterRename description]
+ -[HMMediaGroupStageHomeTheaterRename destinationControllerIdentifier]
+ -[HMMediaGroupStageHomeTheaterRename groupName]
+ -[HMMediaGroupStageHomeTheaterRename hash]
+ -[HMMediaGroupStageHomeTheaterRename hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaGroupStageHomeTheaterRename initWithDestinationControllerIdentifier:groupName:defaultName:]
+ -[HMMediaGroupStageHomeTheaterRename isDefaultName]
+ -[HMMediaGroupStageHomeTheaterRename isEqual:]
+ -[HMMediaGroupStagingManager extendTimerToTimeInterval:]
+ -[HMMediaGroupStagingManager locallyStageDestination:forDestinationController:]
+ -[HMMediaGroupStagingManager locallyStageGroupName:defaultName:forDestinationControllerIdentifier:]
+ -[HMMediaGroupStagingManager notifyDestinationControllerGroupNameWithIdentifiers:]
+ -[HMMediaGroupStagingManager notifyDestinationControllersWithDestinationControllerIdentifiers:]
+ -[HMMediaGroupStagingManager stagedDestinationControllerDataIdentifiers]
+ -[HMMediaGroupStagingManager stagedGroupNameForDestinationControllerIdentifier:]
+ -[HMMediaGroupStagingManager stagedHomeTheaterRenames]
+ -[HMMediaGroupsController stagedHomeTheaterRenames]
+ -[HMPredicateShapeVisitor .cxx_destruct]
+ -[HMPredicateShapeVisitor initWithOptions:]
+ -[HMPredicateShapeVisitor isAllowedConstant:depth:]
+ -[HMPredicateShapeVisitor isAllowedFunction:operand:argumentCount:]
+ -[HMPredicateShapeVisitor isAllowedKeyPath:]
+ -[HMPredicateShapeVisitor rejectionReasonForPredicate:]
+ -[HMPredicateShapeVisitor visitPredicate:]
+ -[HMPredicateShapeVisitor visitPredicateExpression:]
+ -[HMPredicateShapeVisitor visitPredicateOperator:]
+ -[HMUnrecognizedUserParentalControlSettings(Foundation) copyWithZone:]
+ -[HMUnrecognizedUserParentalControlSettings(Foundation) description]
+ -[HMUnrecognizedUserParentalControlSettings(Foundation) encodeWithCoder:]
+ -[HMUnrecognizedUserParentalControlSettings(Foundation) hash]
+ -[HMUnrecognizedUserParentalControlSettings(Foundation) initWithCoder:]
+ -[HMUnrecognizedUserParentalControlSettings(Foundation) init]
+ -[HMUnrecognizedUserParentalControlSettings(Foundation) isEqual:]
+ GCC_except_table10050
+ GCC_except_table10053
+ GCC_except_table10054
+ GCC_except_table10439
+ GCC_except_table10452
+ GCC_except_table10786
+ GCC_except_table10796
+ GCC_except_table10893
+ GCC_except_table10985
+ GCC_except_table10986
+ GCC_except_table10988
+ GCC_except_table10989
+ GCC_except_table10999
+ GCC_except_table11023
+ GCC_except_table11024
+ GCC_except_table11027
+ GCC_except_table11030
+ GCC_except_table11039
+ GCC_except_table11040
+ GCC_except_table11041
+ GCC_except_table11138
+ GCC_except_table11164
+ GCC_except_table11166
+ GCC_except_table11171
+ GCC_except_table11219
+ GCC_except_table11245
+ GCC_except_table11258
+ GCC_except_table11288
+ GCC_except_table11292
+ GCC_except_table11341
+ GCC_except_table11342
+ GCC_except_table11343
+ GCC_except_table11344
+ GCC_except_table11345
+ GCC_except_table11346
+ GCC_except_table11347
+ GCC_except_table11348
+ GCC_except_table11349
+ GCC_except_table11350
+ GCC_except_table11351
+ GCC_except_table11352
+ GCC_except_table11353
+ GCC_except_table11354
+ GCC_except_table11355
+ GCC_except_table11356
+ GCC_except_table11379
+ GCC_except_table11406
+ GCC_except_table11516
+ GCC_except_table11517
+ GCC_except_table11520
+ GCC_except_table11588
+ GCC_except_table11596
+ GCC_except_table11607
+ GCC_except_table11609
+ GCC_except_table11614
+ GCC_except_table11615
+ GCC_except_table11616
+ GCC_except_table1181
+ GCC_except_table11917
+ GCC_except_table1192
+ GCC_except_table12114
+ GCC_except_table12164
+ GCC_except_table12176
+ GCC_except_table12378
+ GCC_except_table12380
+ GCC_except_table12387
+ GCC_except_table12395
+ GCC_except_table12416
+ GCC_except_table12427
+ GCC_except_table12432
+ GCC_except_table12435
+ GCC_except_table12449
+ GCC_except_table12454
+ GCC_except_table12460
+ GCC_except_table12465
+ GCC_except_table12470
+ GCC_except_table12475
+ GCC_except_table12480
+ GCC_except_table12484
+ GCC_except_table12489
+ GCC_except_table12536
+ GCC_except_table12540
+ GCC_except_table12550
+ GCC_except_table12555
+ GCC_except_table12569
+ GCC_except_table12574
+ GCC_except_table12581
+ GCC_except_table12598
+ GCC_except_table12599
+ GCC_except_table12601
+ GCC_except_table12603
+ GCC_except_table12606
+ GCC_except_table12611
+ GCC_except_table12618
+ GCC_except_table12627
+ GCC_except_table12665
+ GCC_except_table1269
+ GCC_except_table12711
+ GCC_except_table12720
+ GCC_except_table12728
+ GCC_except_table1278
+ GCC_except_table12850
+ GCC_except_table12853
+ GCC_except_table12952
+ GCC_except_table12971
+ GCC_except_table12981
+ GCC_except_table13134
+ GCC_except_table13137
+ GCC_except_table13146
+ GCC_except_table13159
+ GCC_except_table13166
+ GCC_except_table13205
+ GCC_except_table13207
+ GCC_except_table13244
+ GCC_except_table13246
+ GCC_except_table13248
+ GCC_except_table13255
+ GCC_except_table13263
+ GCC_except_table13273
+ GCC_except_table13285
+ GCC_except_table13291
+ GCC_except_table13294
+ GCC_except_table13381
+ GCC_except_table13390
+ GCC_except_table13392
+ GCC_except_table13402
+ GCC_except_table13404
+ GCC_except_table13406
+ GCC_except_table13408
+ GCC_except_table13410
+ GCC_except_table13416
+ GCC_except_table13420
+ GCC_except_table13433
+ GCC_except_table13435
+ GCC_except_table13437
+ GCC_except_table13439
+ GCC_except_table13467
+ GCC_except_table1348
+ GCC_except_table13497
+ GCC_except_table1350
+ GCC_except_table1353
+ GCC_except_table1355
+ GCC_except_table1357
+ GCC_except_table13582
+ GCC_except_table13783
+ GCC_except_table13786
+ GCC_except_table13791
+ GCC_except_table13795
+ GCC_except_table13803
+ GCC_except_table13808
+ GCC_except_table13810
+ GCC_except_table13815
+ GCC_except_table13816
+ GCC_except_table13818
+ GCC_except_table13900
+ GCC_except_table13902
+ GCC_except_table13921
+ GCC_except_table13922
+ GCC_except_table13923
+ GCC_except_table13924
+ GCC_except_table13929
+ GCC_except_table13943
+ GCC_except_table13949
+ GCC_except_table13952
+ GCC_except_table13956
+ GCC_except_table14002
+ GCC_except_table14044
+ GCC_except_table14045
+ GCC_except_table14050
+ GCC_except_table14056
+ GCC_except_table14058
+ GCC_except_table14060
+ GCC_except_table14062
+ GCC_except_table14064
+ GCC_except_table14068
+ GCC_except_table14201
+ GCC_except_table14258
+ GCC_except_table14259
+ GCC_except_table14260
+ GCC_except_table14270
+ GCC_except_table14271
+ GCC_except_table14295
+ GCC_except_table14296
+ GCC_except_table14372
+ GCC_except_table14394
+ GCC_except_table14397
+ GCC_except_table14545
+ GCC_except_table14715
+ GCC_except_table14721
+ GCC_except_table14724
+ GCC_except_table14780
+ GCC_except_table14815
+ GCC_except_table14821
+ GCC_except_table14826
+ GCC_except_table14827
+ GCC_except_table14829
+ GCC_except_table14830
+ GCC_except_table14833
+ GCC_except_table14834
+ GCC_except_table14835
+ GCC_except_table14836
+ GCC_except_table14837
+ GCC_except_table14838
+ GCC_except_table14839
+ GCC_except_table14840
+ GCC_except_table14841
+ GCC_except_table14842
+ GCC_except_table14843
+ GCC_except_table14844
+ GCC_except_table14845
+ GCC_except_table14846
+ GCC_except_table14847
+ GCC_except_table14857
+ GCC_except_table14864
+ GCC_except_table14868
+ GCC_except_table14871
+ GCC_except_table15021
+ GCC_except_table15024
+ GCC_except_table15045
+ GCC_except_table15047
+ GCC_except_table15048
+ GCC_except_table1531
+ GCC_except_table1558
+ GCC_except_table1624
+ GCC_except_table1699
+ GCC_except_table1704
+ GCC_except_table1722
+ GCC_except_table1790
+ GCC_except_table1792
+ GCC_except_table1803
+ GCC_except_table1805
+ GCC_except_table1947
+ GCC_except_table2006
+ GCC_except_table2009
+ GCC_except_table2083
+ GCC_except_table2170
+ GCC_except_table2171
+ GCC_except_table2220
+ GCC_except_table2523
+ GCC_except_table2526
+ GCC_except_table2529
+ GCC_except_table2534
+ GCC_except_table2538
+ GCC_except_table2547
+ GCC_except_table2560
+ GCC_except_table2562
+ GCC_except_table2568
+ GCC_except_table2569
+ GCC_except_table2570
+ GCC_except_table2571
+ GCC_except_table3164
+ GCC_except_table3169
+ GCC_except_table3194
+ GCC_except_table3196
+ GCC_except_table3230
+ GCC_except_table3233
+ GCC_except_table3246
+ GCC_except_table3290
+ GCC_except_table3307
+ GCC_except_table3310
+ GCC_except_table3336
+ GCC_except_table3338
+ GCC_except_table3340
+ GCC_except_table3342
+ GCC_except_table3489
+ GCC_except_table3492
+ GCC_except_table3500
+ GCC_except_table3501
+ GCC_except_table3522
+ GCC_except_table3549
+ GCC_except_table3550
+ GCC_except_table3608
+ GCC_except_table3610
+ GCC_except_table3613
+ GCC_except_table3614
+ GCC_except_table3640
+ GCC_except_table3642
+ GCC_except_table3650
+ GCC_except_table3652
+ GCC_except_table3659
+ GCC_except_table3660
+ GCC_except_table3661
+ GCC_except_table3663
+ GCC_except_table3664
+ GCC_except_table3665
+ GCC_except_table3666
+ GCC_except_table3667
+ GCC_except_table3750
+ GCC_except_table3773
+ GCC_except_table3776
+ GCC_except_table3779
+ GCC_except_table3782
+ GCC_except_table3785
+ GCC_except_table3788
+ GCC_except_table3791
+ GCC_except_table3856
+ GCC_except_table3857
+ GCC_except_table3903
+ GCC_except_table3910
+ GCC_except_table3911
+ GCC_except_table3912
+ GCC_except_table3915
+ GCC_except_table3916
+ GCC_except_table3917
+ GCC_except_table3919
+ GCC_except_table3927
+ GCC_except_table3949
+ GCC_except_table3958
+ GCC_except_table3962
+ GCC_except_table3965
+ GCC_except_table3968
+ GCC_except_table4010
+ GCC_except_table4014
+ GCC_except_table4018
+ GCC_except_table4023
+ GCC_except_table4031
+ GCC_except_table4035
+ GCC_except_table4046
+ GCC_except_table4290
+ GCC_except_table4295
+ GCC_except_table4299
+ GCC_except_table4302
+ GCC_except_table4306
+ GCC_except_table4307
+ GCC_except_table4312
+ GCC_except_table4318
+ GCC_except_table4322
+ GCC_except_table4326
+ GCC_except_table4355
+ GCC_except_table4357
+ GCC_except_table4359
+ GCC_except_table4363
+ GCC_except_table4365
+ GCC_except_table4443
+ GCC_except_table4457
+ GCC_except_table4460
+ GCC_except_table4462
+ GCC_except_table4465
+ GCC_except_table4472
+ GCC_except_table4594
+ GCC_except_table4609
+ GCC_except_table4612
+ GCC_except_table4704
+ GCC_except_table4705
+ GCC_except_table4709
+ GCC_except_table4714
+ GCC_except_table4718
+ GCC_except_table4721
+ GCC_except_table4723
+ GCC_except_table4731
+ GCC_except_table4995
+ GCC_except_table4998
+ GCC_except_table5010
+ GCC_except_table5086
+ GCC_except_table5132
+ GCC_except_table5225
+ GCC_except_table5422
+ GCC_except_table5434
+ GCC_except_table5436
+ GCC_except_table5462
+ GCC_except_table5463
+ GCC_except_table5464
+ GCC_except_table5519
+ GCC_except_table5534
+ GCC_except_table5802
+ GCC_except_table5804
+ GCC_except_table5819
+ GCC_except_table5946
+ GCC_except_table5948
+ GCC_except_table5966
+ GCC_except_table6012
+ GCC_except_table6107
+ GCC_except_table6127
+ GCC_except_table6128
+ GCC_except_table6129
+ GCC_except_table6131
+ GCC_except_table6134
+ GCC_except_table6135
+ GCC_except_table6137
+ GCC_except_table6495
+ GCC_except_table6501
+ GCC_except_table6503
+ GCC_except_table6513
+ GCC_except_table6514
+ GCC_except_table6721
+ GCC_except_table6725
+ GCC_except_table6832
+ GCC_except_table6836
+ GCC_except_table6838
+ GCC_except_table6839
+ GCC_except_table7006
+ GCC_except_table7015
+ GCC_except_table7132
+ GCC_except_table7187
+ GCC_except_table7189
+ GCC_except_table7191
+ GCC_except_table7213
+ GCC_except_table7243
+ GCC_except_table7280
+ GCC_except_table7286
+ GCC_except_table7297
+ GCC_except_table7299
+ GCC_except_table7301
+ GCC_except_table7303
+ GCC_except_table7305
+ GCC_except_table7307
+ GCC_except_table7309
+ GCC_except_table7311
+ GCC_except_table7313
+ GCC_except_table7315
+ GCC_except_table7317
+ GCC_except_table7319
+ GCC_except_table7321
+ GCC_except_table7326
+ GCC_except_table7340
+ GCC_except_table7341
+ GCC_except_table7366
+ GCC_except_table7368
+ GCC_except_table7393
+ GCC_except_table7406
+ GCC_except_table7424
+ GCC_except_table752
+ GCC_except_table755
+ GCC_except_table760
+ GCC_except_table7603
+ GCC_except_table763
+ GCC_except_table764
+ GCC_except_table7655
+ GCC_except_table7657
+ GCC_except_table786
+ GCC_except_table7992
+ GCC_except_table803
+ GCC_except_table8035
+ GCC_except_table8128
+ GCC_except_table8137
+ GCC_except_table823
+ GCC_except_table8312
+ GCC_except_table8314
+ GCC_except_table8315
+ GCC_except_table8316
+ GCC_except_table8318
+ GCC_except_table8320
+ GCC_except_table8321
+ GCC_except_table8322
+ GCC_except_table8360
+ GCC_except_table8361
+ GCC_except_table8364
+ GCC_except_table8367
+ GCC_except_table8368
+ GCC_except_table8411
+ GCC_except_table8412
+ GCC_except_table8413
+ GCC_except_table8420
+ GCC_except_table8421
+ GCC_except_table8423
+ GCC_except_table8442
+ GCC_except_table8511
+ GCC_except_table8512
+ GCC_except_table8513
+ GCC_except_table8547
+ GCC_except_table8556
+ GCC_except_table8570
+ GCC_except_table8641
+ GCC_except_table8671
+ GCC_except_table8672
+ GCC_except_table8673
+ GCC_except_table8675
+ GCC_except_table8678
+ GCC_except_table8679
+ GCC_except_table8687
+ GCC_except_table8839
+ GCC_except_table884
+ GCC_except_table8840
+ GCC_except_table8841
+ GCC_except_table8845
+ GCC_except_table887
+ GCC_except_table888
+ GCC_except_table8900
+ GCC_except_table8923
+ GCC_except_table9005
+ GCC_except_table9007
+ GCC_except_table9009
+ GCC_except_table9011
+ GCC_except_table9019
+ GCC_except_table9069
+ GCC_except_table9083
+ GCC_except_table9273
+ GCC_except_table9274
+ GCC_except_table9309
+ GCC_except_table9342
+ GCC_except_table9345
+ GCC_except_table9348
+ GCC_except_table9350
+ GCC_except_table9416
+ GCC_except_table9436
+ GCC_except_table9437
+ GCC_except_table9438
+ GCC_except_table9477
+ GCC_except_table9479
+ GCC_except_table9481
+ GCC_except_table954
+ GCC_except_table9546
+ GCC_except_table9578
+ GCC_except_table9580
+ GCC_except_table9584
+ GCC_except_table959
+ GCC_except_table960
+ GCC_except_table9601
+ GCC_except_table9603
+ GCC_except_table9609
+ GCC_except_table961
+ GCC_except_table9613
+ GCC_except_table9616
+ GCC_except_table962
+ GCC_except_table9623
+ GCC_except_table9627
+ GCC_except_table963
+ GCC_except_table9633
+ GCC_except_table964
+ GCC_except_table9645
+ GCC_except_table9648
+ GCC_except_table9656
+ GCC_except_table9657
+ GCC_except_table9659
+ GCC_except_table966
+ GCC_except_table9661
+ GCC_except_table9663
+ GCC_except_table9683
+ GCC_except_table9693
+ GCC_except_table972
+ GCC_except_table979
+ GCC_except_table980
+ GCC_except_table9909
+ GCC_except_table9922
+ GCC_except_table9963
+ GCC_except_table9966
+ GCC_except_table9968
+ GCC_except_table9981
+ GCC_except_table9982
+ _HMHomeSetUnrecognizedUserSettingRequestKey
+ _HMHomeUnrecognizedUserAllowExplicitContentSettingName
+ _HMHomeUnrecognizedUserBroadWorldKnowledgeAllowedSettingName
+ _HMHomeUnrecognizedUserMathAssistanceAllowedSettingName
+ _HMHomeUnrecognizedUserSafariEnabledSettingName
+ _HMHomeUnrecognizedUserSensitiveTopicsAllowedSettingName
+ _HMHomeUnrecognizedUserSettingNameKey
+ _HMHomeUnrecognizedUserSettingValueKey
+ _HMHomeUnrecognizedUserSettingsCodingKey
+ _HMHomeUnrecognizedUserWebContentFilterSettingName
+ _HMHomeUnrecognizedUserWritingAssistanceAllowedSettingName
+ _HMPredicateContainsClientFormConstants
+ _HMPredicateLeafCount
+ _HMPredicateNestingExceedsCap
+ _OBJC_CLASS_$_HMMediaGroupStageHomeTheaterRename
+ _OBJC_CLASS_$_HMPredicateShapeVisitor
+ _OBJC_CLASS_$_HMUnrecognizedUserParentalControlSettings
+ _OBJC_IVAR_$_HMHome._unrecognizedUserSettings
+ _OBJC_IVAR_$_HMMediaDestinationController._lastNotifiedGroupName
+ _OBJC_IVAR_$_HMMediaGroupStageHomeTheaterRename._defaultName
+ _OBJC_IVAR_$_HMMediaGroupStageHomeTheaterRename._destinationControllerIdentifier
+ _OBJC_IVAR_$_HMMediaGroupStageHomeTheaterRename._groupName
+ _OBJC_IVAR_$_HMMediaGroupStagingManager._stagedHomeTheaterRenamesByIdentifier
+ _OBJC_IVAR_$_HMMediaGroupStagingManager._timerDeadline
+ _OBJC_IVAR_$_HMPredicateShapeVisitor._options
+ _OBJC_IVAR_$_HMPredicateShapeVisitor._rejectionReason
+ _OBJC_METACLASS_$_HMMediaGroupStageHomeTheaterRename
+ _OBJC_METACLASS_$_HMPredicateShapeVisitor
+ _OBJC_METACLASS_$_HMUnrecognizedUserParentalControlSettings
+ __DATA_HMUnrecognizedUserParentalControlSettings
+ __DATA__TtCE7HomeKitCSo41HMUnrecognizedUserParentalControlSettingsP33_364673852D08779EE22D469B707141C67Storage
+ __IVARS_HMUnrecognizedUserParentalControlSettings
+ __IVARS__TtCE7HomeKitCSo41HMUnrecognizedUserParentalControlSettingsP33_364673852D08779EE22D469B707141C67Storage
+ __METACLASS_DATA_HMUnrecognizedUserParentalControlSettings
+ __METACLASS_DATA__TtCE7HomeKitCSo41HMUnrecognizedUserParentalControlSettingsP33_364673852D08779EE22D469B707141C67Storage
+ __OBJC_$_CLASS_METHODS_HMAccessory(HomeKit|DynamicAccessorySettingsAdapter|SwiftExtensions|HomeKit1|SiriEndpoint|Television|ErrorStatus|LightInternal|HMDoorbellChimeProfile|NetworkRouter|Shortcuts|Camera|CameraInternal|CHIP|NetworkConfiguration|Climate|PendingConfiguration|Private|CUPeerIdentifier|Diagnostics|ThreadManagement|Light|Media)
+ __OBJC_$_CLASS_METHODS_HMUnrecognizedUserParentalControlSettings(Foundation)
+ __OBJC_$_INSTANCE_METHODS_HMAccessory(HomeKit|DynamicAccessorySettingsAdapter|SwiftExtensions|HomeKit1|SiriEndpoint|Television|ErrorStatus|LightInternal|HMDoorbellChimeProfile|NetworkRouter|Shortcuts|Camera|CameraInternal|CHIP|NetworkConfiguration|Climate|PendingConfiguration|Private|CUPeerIdentifier|Diagnostics|ThreadManagement|Light|Media)
+ __OBJC_$_INSTANCE_METHODS_HMClientConnection(HomeKit)
+ __OBJC_$_INSTANCE_METHODS_HMMediaGroupStageHomeTheaterRename
+ __OBJC_$_INSTANCE_METHODS_HMPredicateShapeVisitor
+ __OBJC_$_INSTANCE_METHODS_HMUnrecognizedUserParentalControlSettings(Foundation)
+ __OBJC_$_INSTANCE_VARIABLES_HMMediaGroupStageHomeTheaterRename
+ __OBJC_$_INSTANCE_VARIABLES_HMPredicateShapeVisitor
+ __OBJC_$_PROP_LIST_HMMediaGroupStageHomeTheaterRename
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSPredicateVisitor
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSPredicateVisitor
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSPredicateVisitor
+ __OBJC_CLASS_PROTOCOLS_$_HMPredicateShapeVisitor
+ __OBJC_CLASS_PROTOCOLS_$_HMUnrecognizedUserParentalControlSettings(Foundation)
+ __OBJC_CLASS_RO_$_HMMediaGroupStageHomeTheaterRename
+ __OBJC_CLASS_RO_$_HMPredicateShapeVisitor
+ __OBJC_LABEL_PROTOCOL_$_NSPredicateVisitor
+ __OBJC_METACLASS_RO_$_HMMediaGroupStageHomeTheaterRename
+ __OBJC_METACLASS_RO_$_HMPredicateShapeVisitor
+ __OBJC_PROTOCOL_$_NSPredicateVisitor
+ __PROPERTIES_HMUnrecognizedUserParentalControlSettings
+ ___61-[HMUnrecognizedUserParentalControlSettings(Foundation) hash]_block_invoke
+ ___63-[HMHome _updateUnrecognizedUserSettingNamed:value:completion:]_block_invoke
+ ___82-[HMMediaGroupStagingManager notifyDestinationControllerGroupNameWithIdentifiers:]_block_invoke
+ ___95-[HMMediaGroupStagingManager notifyDestinationControllersWithDestinationControllerIdentifiers:]_block_invoke
+ ___block_descriptor_40_e8_32r_e35_v32?0"NSString"8"NSNumber"16^B24l
+ ___block_descriptor_40_e8_32s_e44_v16?0"HMMediaGroupStageHomeTheaterRename"8l
+ ___block_descriptor_48_e8_32s40s_e16_v16?0"NSUUID"8l
+ ___swift_closure_destructor.109Tm
+ ___swift_closure_destructor.34Tm
+ _associated conformance So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV10CodingKeys33_D8E2A7EA01489BED7C91F0A5B4305D9BLLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV10CodingKeys33_D8E2A7EA01489BED7C91F0A5B4305D9BLLOs0L3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV10CodingKeys33_D8E2A7EA01489BED7C91F0A5B4305D9BLLOs0L3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV4ItemV10CodingKeys33_D8E2A7EA01489BED7C91F0A5B4305D9BLLOSHACSQ
+ _associated conformance So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV4ItemV10CodingKeys33_D8E2A7EA01489BED7C91F0A5B4305D9BLLOs0M3KeyACs23CustomStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV4ItemV10CodingKeys33_D8E2A7EA01489BED7C91F0A5B4305D9BLLOs0M3KeyACs28CustomDebugStringConvertible
+ _associated conformance So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestVAC19HMFMessagePrototypeO0I7MessageAC0I7PayloadAgHP_AG0M0
+ _associated conformance So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestVAC19HMFMessagePrototypeO0I7MessageAC15ResponsePayloadAgHP_AG0N0
+ _logCategory._hmf_once_t100
+ _logCategory._hmf_once_t17
+ _logCategory._hmf_once_t554
+ _logCategory._hmf_once_t748
+ _logCategory._hmf_once_t848
+ _logCategory._hmf_once_t85
+ _logCategory._hmf_once_v101
+ _logCategory._hmf_once_v18
+ _logCategory._hmf_once_v555
+ _logCategory._hmf_once_v749
+ _logCategory._hmf_once_v849
+ _logCategory._hmf_once_v86
+ _objc_msgSend$_updateUnrecognizedUserSettingNamed:value:completion:
+ _objc_msgSend$acceptVisitor:flags:
+ _objc_msgSend$configureLastNotifiedGroupName
+ _objc_msgSend$defaultGroupNameForMediaDestinationController:
+ _objc_msgSend$extendTimerToTimeInterval:
+ _objc_msgSend$failWithError:
+ _objc_msgSend$homeDidUpdateUnrecognizedUserSettings:
+ _objc_msgSend$initWithDestinationControllerIdentifier:groupName:defaultName:
+ _objc_msgSend$initWithValuesBySettingName:
+ _objc_msgSend$isAllowedConstant:depth:
+ _objc_msgSend$isAllowedFunction:operand:argumentCount:
+ _objc_msgSend$isAllowedKeyPath:
+ _objc_msgSend$isValidValue:forSettingName:
+ _objc_msgSend$lastNotifiedGroupName
+ _objc_msgSend$locallyStageDestination:
+ _objc_msgSend$locallyStageDestination:forDestinationController:
+ _objc_msgSend$locallyStageGroupName:
+ _objc_msgSend$locallyStageGroupName:defaultName:forDestinationControllerIdentifier:
+ _objc_msgSend$mutableDataCopy
+ _objc_msgSend$notifyDestinationControllerGroupNameWithIdentifiers:
+ _objc_msgSend$notifyDestinationControllersWithDestinationControllerIdentifiers:
+ _objc_msgSend$operand
+ _objc_msgSend$operatorType
+ _objc_msgSend$rejectionReasonForPredicate:
+ _objc_msgSend$setLastNotifiedGroupName:
+ _objc_msgSend$setUnrecognizedUserSettings:
+ _objc_msgSend$settingsByMergingValuesBySettingName:
+ _objc_msgSend$settingsByUpdatingValue:forSettingName:
+ _objc_msgSend$stagedDestinationControllerDataIdentifiers
+ _objc_msgSend$stagedGroupNameForDestinationControllerIdentifier:
+ _objc_msgSend$stagedHomeTheaterRenames
+ _objc_msgSend$stagedHomeTheaterRenamesForMediaGroupsController:
+ _objc_msgSend$symbol
+ _objc_msgSend$unrecognizedUserSettings
+ _objc_msgSend$validatePredicateShape:options:rejectionReason:
+ _objc_msgSend$validateStoredPredicate:
+ _objc_msgSend$valuesBySettingName
+ _swift_deallocPartialClassInstance
+ _symbolic SDySSSo8NSNumberCG
+ _symbolic SS_So8NSNumberCt
+ _symbolic Say_____G So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV4ItemV
+ _symbolic So12NSDictionaryCSgSo7NSErrorCSgIeyByy_
+ _symbolic So41HMUnrecognizedUserParentalControlSettingsC
+ _symbolic So7NSArrayC
+ _symbolic _____ So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV0I7PayloadV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV10CodingKeys33_D8E2A7EA01489BED7C91F0A5B4305D9BLLO
+ _symbolic _____ So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV4ItemV
+ _symbolic _____ So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV4ItemV10CodingKeys33_D8E2A7EA01489BED7C91F0A5B4305D9BLLO
+ _symbolic _____ So41HMUnrecognizedUserParentalControlSettingsC7HomeKitE7Storage33_364673852D08779EE22D469B707141C6LLC
+ _symbolic ______Sbt 10Foundation4UUIDV
+ _symbolic _____ySSSo8NSNumberCG s18_DictionaryStorageC
+ _symbolic _____ySS_So8NSNumberCtG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV10CodingKeys33_D8E2A7EA01489BED7C91F0A5B4305D9BLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV4ItemV10CodingKeys33_D8E2A7EA01489BED7C91F0A5B4305D9BLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV10CodingKeys33_D8E2A7EA01489BED7C91F0A5B4305D9BLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV15ResponsePayloadV4ItemV10CodingKeys33_D8E2A7EA01489BED7C91F0A5B4305D9BLLO
+ _symbolic _____y_____SbG s18_DictionaryStorageC 10Foundation4UUIDV
+ _symbolic _____y______SbtG s23_ContiguousArrayStorageC 10Foundation4UUIDV
+ _type_layout_string So18HMClientConnectionC7HomeKitE31GetSceneUnsecuringStatesRequestV0I7PayloadV
- GCC_except_table10027
- GCC_except_table10060
- GCC_except_table10063
- GCC_except_table10066
- GCC_except_table10068
- GCC_except_table10134
- GCC_except_table10154
- GCC_except_table10155
- GCC_except_table10156
- GCC_except_table10195
- GCC_except_table10197
- GCC_except_table10199
- GCC_except_table1025
- GCC_except_table10264
- GCC_except_table10296
- GCC_except_table10298
- GCC_except_table1030
- GCC_except_table10302
- GCC_except_table10319
- GCC_except_table10321
- GCC_except_table10327
- GCC_except_table10331
- GCC_except_table10334
- GCC_except_table10341
- GCC_except_table10345
- GCC_except_table10351
- GCC_except_table10363
- GCC_except_table10366
- GCC_except_table10374
- GCC_except_table10375
- GCC_except_table10377
- GCC_except_table10379
- GCC_except_table10381
- GCC_except_table1039
- GCC_except_table10411
- GCC_except_table1053
- GCC_except_table1060
- GCC_except_table10627
- GCC_except_table10640
- GCC_except_table10681
- GCC_except_table10684
- GCC_except_table10686
- GCC_except_table10699
- GCC_except_table10700
- GCC_except_table10768
- GCC_except_table10771
- GCC_except_table10772
- GCC_except_table1099
- GCC_except_table1101
- GCC_except_table11119
- GCC_except_table11157
- GCC_except_table1136
- GCC_except_table1138
- GCC_except_table1140
- GCC_except_table1142
- GCC_except_table1149
- GCC_except_table11547
- GCC_except_table11548
- GCC_except_table11550
- GCC_except_table11551
- GCC_except_table11561
- GCC_except_table1157
- GCC_except_table11585
- GCC_except_table11589
- GCC_except_table11592
- GCC_except_table11601
- GCC_except_table11602
- GCC_except_table11603
- GCC_except_table1167
- GCC_except_table11700
- GCC_except_table11726
- GCC_except_table11728
- GCC_except_table11732
- GCC_except_table11733
- GCC_except_table11781
- GCC_except_table1179
- GCC_except_table11807
- GCC_except_table11820
- GCC_except_table11846
- GCC_except_table11850
- GCC_except_table1188
- GCC_except_table11899
- GCC_except_table11900
- GCC_except_table11901
- GCC_except_table11902
- GCC_except_table11903
- GCC_except_table11904
- GCC_except_table11906
- GCC_except_table11907
- GCC_except_table11908
- GCC_except_table11909
- GCC_except_table11910
- GCC_except_table11911
- GCC_except_table11913
- GCC_except_table11914
- GCC_except_table11937
- GCC_except_table11964
- GCC_except_table12074
- GCC_except_table12075
- GCC_except_table12078
- GCC_except_table12144
- GCC_except_table12146
- GCC_except_table12154
- GCC_except_table12167
- GCC_except_table12172
- GCC_except_table12173
- GCC_except_table12174
- GCC_except_table12398
- GCC_except_table12516
- GCC_except_table12526
- GCC_except_table1275
- GCC_except_table12755
- GCC_except_table12758
- GCC_except_table12763
- GCC_except_table12767
- GCC_except_table12775
- GCC_except_table12780
- GCC_except_table12782
- GCC_except_table12787
- GCC_except_table12788
- GCC_except_table12790
- GCC_except_table1284
- GCC_except_table1286
- GCC_except_table12872
- GCC_except_table12874
- GCC_except_table12893
- GCC_except_table12894
- GCC_except_table12895
- GCC_except_table12896
- GCC_except_table12901
- GCC_except_table12915
- GCC_except_table12921
- GCC_except_table12924
- GCC_except_table12928
- GCC_except_table1296
- GCC_except_table12974
- GCC_except_table1298
- GCC_except_table1300
- GCC_except_table13006
- GCC_except_table13016
- GCC_except_table13017
- GCC_except_table1302
- GCC_except_table13022
- GCC_except_table13028
- GCC_except_table13030
- GCC_except_table13032
- GCC_except_table13034
- GCC_except_table13036
- GCC_except_table13038
- GCC_except_table1304
- GCC_except_table13040
- GCC_except_table1310
- GCC_except_table1314
- GCC_except_table13173
- GCC_except_table13229
- GCC_except_table13230
- GCC_except_table13231
- GCC_except_table13232
- GCC_except_table13243
- GCC_except_table13267
- GCC_except_table13268
- GCC_except_table1327
- GCC_except_table1329
- GCC_except_table1331
- GCC_except_table1333
- GCC_except_table13344
- GCC_except_table13366
- GCC_except_table13369
- GCC_except_table13387
- GCC_except_table13389
- GCC_except_table13557
- GCC_except_table13564
- GCC_except_table13569
- GCC_except_table13766
- GCC_except_table13817
- GCC_except_table1391
- GCC_except_table14017
- GCC_except_table14019
- GCC_except_table14026
- GCC_except_table14055
- GCC_except_table14071
- GCC_except_table14074
- GCC_except_table14088
- GCC_except_table14093
- GCC_except_table14099
- GCC_except_table14104
- GCC_except_table14109
- GCC_except_table14114
- GCC_except_table14119
- GCC_except_table14123
- GCC_except_table14128
- GCC_except_table14175
- GCC_except_table14179
- GCC_except_table14189
- GCC_except_table14194
- GCC_except_table14208
- GCC_except_table14213
- GCC_except_table14220
- GCC_except_table14237
- GCC_except_table14238
- GCC_except_table14240
- GCC_except_table14242
- GCC_except_table14245
- GCC_except_table14250
- GCC_except_table14262
- GCC_except_table14266
- GCC_except_table14304
- GCC_except_table14350
- GCC_except_table14359
- GCC_except_table14500
- GCC_except_table14670
- GCC_except_table14676
- GCC_except_table14679
- GCC_except_table14735
- GCC_except_table14770
- GCC_except_table14776
- GCC_except_table14781
- GCC_except_table14782
- GCC_except_table14787
- GCC_except_table14789
- GCC_except_table14790
- GCC_except_table14791
- GCC_except_table14792
- GCC_except_table14793
- GCC_except_table14794
- GCC_except_table14795
- GCC_except_table14796
- GCC_except_table14803
- GCC_except_table14810
- GCC_except_table14814
- GCC_except_table14817
- GCC_except_table14958
- GCC_except_table14961
- GCC_except_table14982
- GCC_except_table14984
- GCC_except_table14985
- GCC_except_table1542
- GCC_except_table1545
- GCC_except_table1550
- GCC_except_table1553
- GCC_except_table1554
- GCC_except_table1576
- GCC_except_table1593
- GCC_except_table1613
- GCC_except_table1660
- GCC_except_table1663
- GCC_except_table1664
- GCC_except_table1730
- GCC_except_table1735
- GCC_except_table1736
- GCC_except_table1737
- GCC_except_table1738
- GCC_except_table1739
- GCC_except_table1740
- GCC_except_table1742
- GCC_except_table1748
- GCC_except_table1755
- GCC_except_table1756
- GCC_except_table1957
- GCC_except_table1961
- GCC_except_table1968
- GCC_except_table2045
- GCC_except_table2054
- GCC_except_table2124
- GCC_except_table2126
- GCC_except_table2129
- GCC_except_table2131
- GCC_except_table2133
- GCC_except_table2137
- GCC_except_table2307
- GCC_except_table2333
- GCC_except_table2399
- GCC_except_table2474
- GCC_except_table2477
- GCC_except_table2495
- GCC_except_table2565
- GCC_except_table2576
- GCC_except_table2578
- GCC_except_table2717
- GCC_except_table2773
- GCC_except_table2776
- GCC_except_table2850
- GCC_except_table2937
- GCC_except_table2938
- GCC_except_table2987
- GCC_except_table3277
- GCC_except_table3280
- GCC_except_table3283
- GCC_except_table3288
- GCC_except_table3292
- GCC_except_table3301
- GCC_except_table3314
- GCC_except_table3316
- GCC_except_table3317
- GCC_except_table3322
- GCC_except_table3323
- GCC_except_table3324
- GCC_except_table3325
- GCC_except_table3918
- GCC_except_table3923
- GCC_except_table3948
- GCC_except_table3950
- GCC_except_table3984
- GCC_except_table3987
- GCC_except_table4000
- GCC_except_table4061
- GCC_except_table4064
- GCC_except_table4090
- GCC_except_table4092
- GCC_except_table4094
- GCC_except_table4096
- GCC_except_table4243
- GCC_except_table4246
- GCC_except_table4254
- GCC_except_table4255
- GCC_except_table4276
- GCC_except_table4303
- GCC_except_table4304
- GCC_except_table4364
- GCC_except_table4367
- GCC_except_table4394
- GCC_except_table4396
- GCC_except_table4404
- GCC_except_table4406
- GCC_except_table4413
- GCC_except_table4414
- GCC_except_table4415
- GCC_except_table4417
- GCC_except_table4418
- GCC_except_table4419
- GCC_except_table4420
- GCC_except_table4421
- GCC_except_table4504
- GCC_except_table4530
- GCC_except_table4533
- GCC_except_table4536
- GCC_except_table4539
- GCC_except_table4542
- GCC_except_table4545
- GCC_except_table4610
- GCC_except_table4611
- GCC_except_table4657
- GCC_except_table4664
- GCC_except_table4665
- GCC_except_table4666
- GCC_except_table4669
- GCC_except_table4670
- GCC_except_table4671
- GCC_except_table4673
- GCC_except_table4681
- GCC_except_table4703
- GCC_except_table4712
- GCC_except_table4716
- GCC_except_table4719
- GCC_except_table4722
- GCC_except_table4764
- GCC_except_table4768
- GCC_except_table4772
- GCC_except_table4777
- GCC_except_table4785
- GCC_except_table4789
- GCC_except_table4798
- GCC_except_table4800
- GCC_except_table5044
- GCC_except_table5049
- GCC_except_table5053
- GCC_except_table5056
- GCC_except_table5060
- GCC_except_table5061
- GCC_except_table5064
- GCC_except_table5070
- GCC_except_table5074
- GCC_except_table5078
- GCC_except_table5107
- GCC_except_table5109
- GCC_except_table5111
- GCC_except_table5114
- GCC_except_table5115
- GCC_except_table5117
- GCC_except_table5120
- GCC_except_table5195
- GCC_except_table5209
- GCC_except_table5212
- GCC_except_table5214
- GCC_except_table5217
- GCC_except_table5224
- GCC_except_table5279
- GCC_except_table5346
- GCC_except_table5361
- GCC_except_table5364
- GCC_except_table5456
- GCC_except_table5457
- GCC_except_table5466
- GCC_except_table5470
- GCC_except_table5473
- GCC_except_table5475
- GCC_except_table5483
- GCC_except_table5747
- GCC_except_table5750
- GCC_except_table5762
- GCC_except_table5838
- GCC_except_table5884
- GCC_except_table5977
- GCC_except_table6174
- GCC_except_table6186
- GCC_except_table6188
- GCC_except_table6213
- GCC_except_table6214
- GCC_except_table6215
- GCC_except_table6216
- GCC_except_table6275
- GCC_except_table6288
- GCC_except_table6556
- GCC_except_table6558
- GCC_except_table6573
- GCC_except_table6700
- GCC_except_table6702
- GCC_except_table6720
- GCC_except_table6766
- GCC_except_table6861
- GCC_except_table6881
- GCC_except_table6882
- GCC_except_table6883
- GCC_except_table6885
- GCC_except_table6888
- GCC_except_table6889
- GCC_except_table6891
- GCC_except_table7249
- GCC_except_table7257
- GCC_except_table7267
- GCC_except_table7268
- GCC_except_table737
- GCC_except_table740
- GCC_except_table7475
- GCC_except_table7479
- GCC_except_table7586
- GCC_except_table7590
- GCC_except_table7592
- GCC_except_table7593
- GCC_except_table7760
- GCC_except_table7769
- GCC_except_table7886
- GCC_except_table7941
- GCC_except_table7943
- GCC_except_table7945
- GCC_except_table7967
- GCC_except_table7997
- GCC_except_table8009
- GCC_except_table8034
- GCC_except_table8040
- GCC_except_table8051
- GCC_except_table8053
- GCC_except_table8055
- GCC_except_table8057
- GCC_except_table8059
- GCC_except_table8061
- GCC_except_table8063
- GCC_except_table8065
- GCC_except_table8067
- GCC_except_table8069
- GCC_except_table8071
- GCC_except_table8073
- GCC_except_table8075
- GCC_except_table8080
- GCC_except_table8094
- GCC_except_table8095
- GCC_except_table8120
- GCC_except_table8122
- GCC_except_table8147
- GCC_except_table8160
- GCC_except_table8178
- GCC_except_table839
- GCC_except_table860
- GCC_except_table8712
- GCC_except_table872
- GCC_except_table8755
- GCC_except_table8848
- GCC_except_table8857
- GCC_except_table9032
- GCC_except_table9034
- GCC_except_table9035
- GCC_except_table9036
- GCC_except_table9038
- GCC_except_table9040
- GCC_except_table9041
- GCC_except_table9042
- GCC_except_table9077
- GCC_except_table9080
- GCC_except_table9084
- GCC_except_table9087
- GCC_except_table9088
- GCC_except_table9131
- GCC_except_table9132
- GCC_except_table9133
- GCC_except_table9140
- GCC_except_table9141
- GCC_except_table9143
- GCC_except_table9162
- GCC_except_table9231
- GCC_except_table9232
- GCC_except_table9233
- GCC_except_table9267
- GCC_except_table9276
- GCC_except_table9290
- GCC_except_table9361
- GCC_except_table9391
- GCC_except_table9392
- GCC_except_table9393
- GCC_except_table9395
- GCC_except_table9398
- GCC_except_table9399
- GCC_except_table9406
- GCC_except_table9557
- GCC_except_table9558
- GCC_except_table9559
- GCC_except_table9563
- GCC_except_table9618
- GCC_except_table9641
- GCC_except_table9723
- GCC_except_table9725
- GCC_except_table9727
- GCC_except_table9729
- GCC_except_table9737
- GCC_except_table9787
- GCC_except_table9799
- GCC_except_table9801
- GCC_except_table9991
- GCC_except_table9992
- __OBJC_$_CLASS_METHODS_HMAccessory(SwiftExtensions|HomeKit|HomeKit1|DynamicAccessorySettingsAdapter|PendingConfiguration|Private|CUPeerIdentifier|Diagnostics|ThreadManagement|SiriEndpoint|Television|ErrorStatus|LightInternal|HMDoorbellChimeProfile|NetworkRouter|Shortcuts|Camera|CameraInternal|CHIP|NetworkConfiguration|Climate|Light|Media)
- __OBJC_$_INSTANCE_METHODS_HMAccessory(SwiftExtensions|HomeKit|HomeKit1|DynamicAccessorySettingsAdapter|PendingConfiguration|Private|CUPeerIdentifier|Diagnostics|ThreadManagement|SiriEndpoint|Television|ErrorStatus|LightInternal|HMDoorbellChimeProfile|NetworkRouter|Shortcuts|Camera|CameraInternal|CHIP|NetworkConfiguration|Climate|Light|Media)
- __OBJC_$_INSTANCE_METHODS_HMClientConnection
- ___88-[HMMediaGroupStagingManager notifyDestinationControllersWithDestinationControllerData:]_block_invoke_2
- ___swift_closure_destructor.121Tm
- _logCategory._hmf_once_t547
- _logCategory._hmf_once_t728
- _logCategory._hmf_once_t75
- _logCategory._hmf_once_t78
- _logCategory._hmf_once_t841
- _logCategory._hmf_once_t94
- _logCategory._hmf_once_v548
- _logCategory._hmf_once_v729
- _logCategory._hmf_once_v76
- _logCategory._hmf_once_v79
- _logCategory._hmf_once_v842
- _logCategory._hmf_once_v95
CStrings:
+ ", defaultName: %@"
+ ", stagedGroupNames: %@"
+ "-[HMHome _updateUnrecognizedUserSettingNamed:value:completion:]"
+ "-[HMHome updateUnrecognizedUserWebContentFilter:completion:]"
+ "21"
+ "<%@: %@>"
+ "Configuring last notified group name: %{private}@"
+ "Could not find scene identifiers in the message payload"
+ "Failed to get default group name due to no room for controller: %@"
+ "Failed to get destination controller from data source for group name identifier: %@"
+ "Failed to get staged home theater renames due to no data source"
+ "Failed to stage destination due to invalid destination identifier: %@"
+ "Failed to stage destination due to no staging manager"
+ "Failed to stage group name due to no default group name"
+ "Failed to stage group name due to no staging manager"
+ "Fetching unsecuring states for %ld scene identifiers"
+ "Finished fetching %ld scene unsecuring states"
+ "HM.getSceneUnsecuringStates"
+ "HMHomeSetUnrecognizedUserSettingRequestKey"
+ "HMHomeUnrecognizedUserSettingNameKey"
+ "HMHomeUnrecognizedUserSettingValueKey"
+ "HMHomeUnrecognizedUserSettingsCodingKey"
+ "HMUnrecognizedUserParentalControlSettingsValuesCodingKey"
+ "HomeKit_Private.HMUnrecognizedUserParentalControlSettings"
+ "Sending set request for setting %{public}@ for unrecognized people"
+ "Set request for setting %{public}@ for unrecognized people failed, error domain %{public}@ code %ld"
+ "Setting %{public}@ for unrecognized people is already set to the same value, skipping request"
+ "Settings for unrecognized people updated"
+ "Skipping notifying of update group name due to matching group name: %{private}@"
+ "Staging destination locally for controller: %@ destination: %@"
+ "Staging group name: %{private}@ locally for controller: %{public}@"
+ "[%{public}@] Configuring last notified group name: %{private}@"
+ "[%{public}@] Failed to get default group name due to no room for controller: %@"
+ "[%{public}@] Failed to get destination controller from data source for group name identifier: %@"
+ "[%{public}@] Failed to get staged home theater renames due to no data source"
+ "[%{public}@] Failed to stage destination due to invalid destination identifier: %@"
+ "[%{public}@] Failed to stage destination due to no staging manager"
+ "[%{public}@] Failed to stage group name due to no default group name"
+ "[%{public}@] Failed to stage group name due to no staging manager"
+ "[%{public}@] Sending set request for setting %{public}@ for unrecognized people"
+ "[%{public}@] Set request for setting %{public}@ for unrecognized people failed, error domain %{public}@ code %ld"
+ "[%{public}@] Setting %{public}@ for unrecognized people is already set to the same value, skipping request"
+ "[%{public}@] Settings for unrecognized people updated"
+ "[%{public}@] Skipping notifying of update group name due to matching group name: %{private}@"
+ "[%{public}@] Staging destination locally for controller: %@ destination: %@"
+ "[%{public}@] Staging group name: %{private}@ locally for controller: %{public}@"
+ "_NSPredicateUtilities"
+ "compound predicates are nested deeper than %d levels"
+ "constant value contains a disallowed type: %@"
+ "containsUnsecuringAction"
+ "controller"
+ "expression '%@' is not recognized"
+ "expression type not allowed: %@"
+ "function '%@' is not allowed"
+ "keyPath '%@' is not allowed"
+ "operator '%@' is not allowed"
+ "operator '%@' is not recognized"
+ "operator '%@' is not used by HomeKit predicates"
+ "predicate could not be archived: %@"
+ "predicate too large (%lu bytes, limit %d)"
+ "sceneIdentifierListKey"
+ "unrecognizedUserAllowExplicitContent"
+ "unrecognizedUserBroadWorldKnowledgeAllowed"
+ "unrecognizedUserMathAssistanceAllowed"
+ "unrecognizedUserSafariEnabled"
+ "unrecognizedUserSensitiveTopicsAllowed"
+ "unrecognizedUserWebContentFilter"
+ "unrecognizedUserWritingAssistanceAllowed"
+ "v16@?0@\"HMMediaGroupStageHomeTheaterRename\"8"
+ "v32@?0@\"NSString\"8@\"NSNumber\"16^B24"
+ "\xa1\xf0\xf0\xc1"
+ "…"
- "2!"
- "\xa1\xf0\xf0\xb1"
- "\xe1!"
```
