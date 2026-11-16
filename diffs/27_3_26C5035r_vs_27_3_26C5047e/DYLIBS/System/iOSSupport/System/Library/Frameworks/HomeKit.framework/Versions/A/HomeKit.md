## HomeKit

> `/System/iOSSupport/System/Library/Frameworks/HomeKit.framework/Versions/A/HomeKit`

```diff

-1535.0.0.0.2
-  __TEXT.__text: 0x483108
-  __TEXT.__objc_methlist: 0x29eec
-  __TEXT.__const: 0x11db8
+1535.3.8.0.0
+  __TEXT.__text: 0x48d624
+  __TEXT.__objc_methlist: 0x2a2cc
+  __TEXT.__const: 0x121e8
   __TEXT.__dlopen_cstrs: 0x403
-  __TEXT.__swift5_typeref: 0x4354
-  __TEXT.__cstring: 0x329f6
-  __TEXT.__constg_swiftt: 0x3e10
-  __TEXT.__swift5_reflstr: 0x2ce0
-  __TEXT.__swift5_fieldmd: 0x3adc
+  __TEXT.__swift5_typeref: 0x44e4
+  __TEXT.__cstring: 0x32f2d
+  __TEXT.__constg_swiftt: 0x3f24
+  __TEXT.__swift5_reflstr: 0x2d74
+  __TEXT.__swift5_fieldmd: 0x3bb8
   __TEXT.__swift5_builtin: 0xc8
-  __TEXT.__swift5_assocty: 0x970
-  __TEXT.__swift5_capture: 0xae4
+  __TEXT.__swift5_assocty: 0x990
+  __TEXT.__swift5_capture: 0xb24
   __TEXT.__swift5_protos: 0x4c
-  __TEXT.__swift5_proto: 0xe80
-  __TEXT.__swift5_types: 0x4d8
-  __TEXT.__swift_as_entry: 0x2d8
-  __TEXT.__swift_as_ret: 0x330
-  __TEXT.__swift_as_cont: 0x6d8
-  __TEXT.__oslogstring: 0x5a4ac
+  __TEXT.__swift5_proto: 0xec8
+  __TEXT.__swift5_types: 0x4f4
+  __TEXT.__swift_as_entry: 0x2e0
+  __TEXT.__swift_as_ret: 0x338
+  __TEXT.__swift_as_cont: 0x6e4
+  __TEXT.__oslogstring: 0x5adfe
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__gcc_except_tab: 0x67d4
-  __TEXT.__ustring: 0x50
-  __TEXT.__unwind_info: 0x13808
-  __TEXT.__eh_frame: 0xd8a8
+  __TEXT.__gcc_except_tab: 0x68e4
+  __TEXT.__ustring: 0x54
+  __TEXT.__unwind_info: 0x136e8
+  __TEXT.__eh_frame: 0xdd2c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9468
-  __DATA_CONST.__objc_classlist: 0x1408
+  __DATA_CONST.__const: 0x9538
+  __DATA_CONST.__objc_classlist: 0x1428
   __DATA_CONST.__objc_catlist: 0x108
-  __DATA_CONST.__objc_protolist: 0x560
+  __DATA_CONST.__objc_protolist: 0x568
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xeb88
+  __DATA_CONST.__objc_selrefs: 0xed50
   __DATA_CONST.__objc_protorefs: 0x110
-  __DATA_CONST.__objc_superrefs: 0x1008
+  __DATA_CONST.__objc_superrefs: 0x1018
   __DATA_CONST.__objc_arraydata: 0x1488
-  __DATA_CONST.__got: 0x20e0
-  __AUTH_CONST.__const: 0xb300
-  __AUTH_CONST.__cfstring: 0x2d4e0
-  __AUTH_CONST.__objc_const: 0x4bd30
+  __DATA_CONST.__got: 0x20e8
+  __AUTH_CONST.__const: 0xb640
+  __AUTH_CONST.__cfstring: 0x2d880
+  __AUTH_CONST.__objc_const: 0x4c428
   __AUTH_CONST.__objc_intobj: 0xa08
   __AUTH_CONST.__objc_dictobj: 0x848
   __AUTH_CONST.__objc_arrayobj: 0x618
   __AUTH_CONST.__objc_doubleobj: 0x70
-  __AUTH_CONST.__auth_got: 0x1fc8
-  __AUTH.__objc_data: 0x95d0
-  __AUTH.__data: 0x4048
-  __DATA.__objc_ivar: 0x2988
-  __DATA.__data: 0x7908
-  __DATA.__bss: 0x1b588
+  __AUTH_CONST.__auth_got: 0x1fd0
+  __AUTH.__objc_data: 0x96e0
+  __AUTH.__data: 0x41c8
+  __DATA.__objc_ivar: 0x29ac
+  __DATA.__data: 0x7a80
+  __DATA.__bss: 0x1bd08
   __DATA.__common: 0x1a8
   __DATA_DIRTY.__objc_data: 0x3768
   __DATA_DIRTY.__data: 0x1b0

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 22228
-  Symbols:   34483
-  CStrings:  12922
+  Functions: 22428
+  Symbols:   34678
+  CStrings:  12991
 
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
+ GCC_except_table10016
+ GCC_except_table10019
+ GCC_except_table10020
+ GCC_except_table10405
+ GCC_except_table10418
+ GCC_except_table10752
+ GCC_except_table10762
+ GCC_except_table10857
+ GCC_except_table10949
+ GCC_except_table10950
+ GCC_except_table10952
+ GCC_except_table10953
+ GCC_except_table10963
+ GCC_except_table10987
+ GCC_except_table10988
+ GCC_except_table10991
+ GCC_except_table10994
+ GCC_except_table11003
+ GCC_except_table11004
+ GCC_except_table11005
+ GCC_except_table11102
+ GCC_except_table11128
+ GCC_except_table11130
+ GCC_except_table11134
+ GCC_except_table11135
+ GCC_except_table11183
+ GCC_except_table11209
+ GCC_except_table11222
+ GCC_except_table11252
+ GCC_except_table11256
+ GCC_except_table11305
+ GCC_except_table11306
+ GCC_except_table11307
+ GCC_except_table11308
+ GCC_except_table11309
+ GCC_except_table11310
+ GCC_except_table11311
+ GCC_except_table11312
+ GCC_except_table11313
+ GCC_except_table11314
+ GCC_except_table11315
+ GCC_except_table11316
+ GCC_except_table11317
+ GCC_except_table11318
+ GCC_except_table11319
+ GCC_except_table11320
+ GCC_except_table11343
+ GCC_except_table11370
+ GCC_except_table11480
+ GCC_except_table11481
+ GCC_except_table11484
+ GCC_except_table11550
+ GCC_except_table11560
+ GCC_except_table11571
+ GCC_except_table11573
+ GCC_except_table11578
+ GCC_except_table11579
+ GCC_except_table11580
+ GCC_except_table1166
+ GCC_except_table1170
+ GCC_except_table1177
+ GCC_except_table11881
+ GCC_except_table12078
+ GCC_except_table12128
+ GCC_except_table12129
+ GCC_except_table12342
+ GCC_except_table12344
+ GCC_except_table12351
+ GCC_except_table12359
+ GCC_except_table12380
+ GCC_except_table12391
+ GCC_except_table12396
+ GCC_except_table12399
+ GCC_except_table12413
+ GCC_except_table12418
+ GCC_except_table12424
+ GCC_except_table12429
+ GCC_except_table12434
+ GCC_except_table12439
+ GCC_except_table12444
+ GCC_except_table12448
+ GCC_except_table12453
+ GCC_except_table12504
+ GCC_except_table12508
+ GCC_except_table12516
+ GCC_except_table1252
+ GCC_except_table12521
+ GCC_except_table12535
+ GCC_except_table12540
+ GCC_except_table12547
+ GCC_except_table12563
+ GCC_except_table12564
+ GCC_except_table12566
+ GCC_except_table12568
+ GCC_except_table12571
+ GCC_except_table12576
+ GCC_except_table12583
+ GCC_except_table12588
+ GCC_except_table12592
+ GCC_except_table1261
+ GCC_except_table12629
+ GCC_except_table12672
+ GCC_except_table12681
+ GCC_except_table12689
+ GCC_except_table12811
+ GCC_except_table12814
+ GCC_except_table12913
+ GCC_except_table12932
+ GCC_except_table12942
+ GCC_except_table13095
+ GCC_except_table13098
+ GCC_except_table13107
+ GCC_except_table13120
+ GCC_except_table13127
+ GCC_except_table13166
+ GCC_except_table13168
+ GCC_except_table13205
+ GCC_except_table13207
+ GCC_except_table13209
+ GCC_except_table13216
+ GCC_except_table13224
+ GCC_except_table13234
+ GCC_except_table13246
+ GCC_except_table13252
+ GCC_except_table13255
+ GCC_except_table1329
+ GCC_except_table1331
+ GCC_except_table1334
+ GCC_except_table13342
+ GCC_except_table13351
+ GCC_except_table13353
+ GCC_except_table1336
+ GCC_except_table13363
+ GCC_except_table13365
+ GCC_except_table13367
+ GCC_except_table13369
+ GCC_except_table13371
+ GCC_except_table13377
+ GCC_except_table1338
+ GCC_except_table13381
+ GCC_except_table13394
+ GCC_except_table13396
+ GCC_except_table13398
+ GCC_except_table13400
+ GCC_except_table1342
+ GCC_except_table13428
+ GCC_except_table13458
+ GCC_except_table13543
+ GCC_except_table13744
+ GCC_except_table13747
+ GCC_except_table13752
+ GCC_except_table13756
+ GCC_except_table13762
+ GCC_except_table13767
+ GCC_except_table13769
+ GCC_except_table13774
+ GCC_except_table13775
+ GCC_except_table13859
+ GCC_except_table13861
+ GCC_except_table13880
+ GCC_except_table13881
+ GCC_except_table13882
+ GCC_except_table13883
+ GCC_except_table13888
+ GCC_except_table13902
+ GCC_except_table13908
+ GCC_except_table13911
+ GCC_except_table13913
+ GCC_except_table13959
+ GCC_except_table13991
+ GCC_except_table14001
+ GCC_except_table14002
+ GCC_except_table14007
+ GCC_except_table14013
+ GCC_except_table14017
+ GCC_except_table14019
+ GCC_except_table14021
+ GCC_except_table14023
+ GCC_except_table14025
+ GCC_except_table14158
+ GCC_except_table14214
+ GCC_except_table14215
+ GCC_except_table14216
+ GCC_except_table14217
+ GCC_except_table14228
+ GCC_except_table14252
+ GCC_except_table14253
+ GCC_except_table14329
+ GCC_except_table14351
+ GCC_except_table14354
+ GCC_except_table14502
+ GCC_except_table14702
+ GCC_except_table14708
+ GCC_except_table14711
+ GCC_except_table14767
+ GCC_except_table14802
+ GCC_except_table14808
+ GCC_except_table14813
+ GCC_except_table14814
+ GCC_except_table14816
+ GCC_except_table14817
+ GCC_except_table14820
+ GCC_except_table14821
+ GCC_except_table14822
+ GCC_except_table14823
+ GCC_except_table14824
+ GCC_except_table14825
+ GCC_except_table14826
+ GCC_except_table14827
+ GCC_except_table14828
+ GCC_except_table14829
+ GCC_except_table14830
+ GCC_except_table14831
+ GCC_except_table14832
+ GCC_except_table14833
+ GCC_except_table14834
+ GCC_except_table14844
+ GCC_except_table14851
+ GCC_except_table14855
+ GCC_except_table14858
+ GCC_except_table15008
+ GCC_except_table15011
+ GCC_except_table15032
+ GCC_except_table15034
+ GCC_except_table15035
+ GCC_except_table1512
+ GCC_except_table1604
+ GCC_except_table1679
+ GCC_except_table1682
+ GCC_except_table1700
+ GCC_except_table1768
+ GCC_except_table1770
+ GCC_except_table1781
+ GCC_except_table1783
+ GCC_except_table1924
+ GCC_except_table1983
+ GCC_except_table1986
+ GCC_except_table2060
+ GCC_except_table2147
+ GCC_except_table2148
+ GCC_except_table2197
+ GCC_except_table2500
+ GCC_except_table2503
+ GCC_except_table2506
+ GCC_except_table2511
+ GCC_except_table2515
+ GCC_except_table2524
+ GCC_except_table2537
+ GCC_except_table2539
+ GCC_except_table2540
+ GCC_except_table2545
+ GCC_except_table2546
+ GCC_except_table2547
+ GCC_except_table2548
+ GCC_except_table3141
+ GCC_except_table3146
+ GCC_except_table3171
+ GCC_except_table3173
+ GCC_except_table3207
+ GCC_except_table3210
+ GCC_except_table3223
+ GCC_except_table3267
+ GCC_except_table3284
+ GCC_except_table3313
+ GCC_except_table3315
+ GCC_except_table3317
+ GCC_except_table3319
+ GCC_except_table3466
+ GCC_except_table3469
+ GCC_except_table3477
+ GCC_except_table3478
+ GCC_except_table3499
+ GCC_except_table3526
+ GCC_except_table3527
+ GCC_except_table3597
+ GCC_except_table3599
+ GCC_except_table3602
+ GCC_except_table3603
+ GCC_except_table3627
+ GCC_except_table3629
+ GCC_except_table3637
+ GCC_except_table3639
+ GCC_except_table3646
+ GCC_except_table3647
+ GCC_except_table3648
+ GCC_except_table3650
+ GCC_except_table3651
+ GCC_except_table3652
+ GCC_except_table3653
+ GCC_except_table3654
+ GCC_except_table3737
+ GCC_except_table3760
+ GCC_except_table3763
+ GCC_except_table3766
+ GCC_except_table3769
+ GCC_except_table3772
+ GCC_except_table3775
+ GCC_except_table3778
+ GCC_except_table3843
+ GCC_except_table3844
+ GCC_except_table3890
+ GCC_except_table3897
+ GCC_except_table3898
+ GCC_except_table3899
+ GCC_except_table3902
+ GCC_except_table3903
+ GCC_except_table3904
+ GCC_except_table3906
+ GCC_except_table3914
+ GCC_except_table3936
+ GCC_except_table3943
+ GCC_except_table3947
+ GCC_except_table3950
+ GCC_except_table3953
+ GCC_except_table3995
+ GCC_except_table3999
+ GCC_except_table4003
+ GCC_except_table4008
+ GCC_except_table4016
+ GCC_except_table4020
+ GCC_except_table4029
+ GCC_except_table4031
+ GCC_except_table4275
+ GCC_except_table4279
+ GCC_except_table4283
+ GCC_except_table4286
+ GCC_except_table4290
+ GCC_except_table4291
+ GCC_except_table4294
+ GCC_except_table4300
+ GCC_except_table4304
+ GCC_except_table4308
+ GCC_except_table4337
+ GCC_except_table4339
+ GCC_except_table4341
+ GCC_except_table4344
+ GCC_except_table4345
+ GCC_except_table4350
+ GCC_except_table4425
+ GCC_except_table4439
+ GCC_except_table4442
+ GCC_except_table4444
+ GCC_except_table4447
+ GCC_except_table4454
+ GCC_except_table4509
+ GCC_except_table4576
+ GCC_except_table4591
+ GCC_except_table4687
+ GCC_except_table4689
+ GCC_except_table4694
+ GCC_except_table4698
+ GCC_except_table4701
+ GCC_except_table4711
+ GCC_except_table4975
+ GCC_except_table4978
+ GCC_except_table4990
+ GCC_except_table5066
+ GCC_except_table5112
+ GCC_except_table5205
+ GCC_except_table5402
+ GCC_except_table5414
+ GCC_except_table5416
+ GCC_except_table5441
+ GCC_except_table5442
+ GCC_except_table5443
+ GCC_except_table5499
+ GCC_except_table5509
+ GCC_except_table5777
+ GCC_except_table5779
+ GCC_except_table5794
+ GCC_except_table5919
+ GCC_except_table5921
+ GCC_except_table5939
+ GCC_except_table5985
+ GCC_except_table6080
+ GCC_except_table6100
+ GCC_except_table6101
+ GCC_except_table6102
+ GCC_except_table6104
+ GCC_except_table6107
+ GCC_except_table6108
+ GCC_except_table6110
+ GCC_except_table6468
+ GCC_except_table6474
+ GCC_except_table6476
+ GCC_except_table6486
+ GCC_except_table6487
+ GCC_except_table6694
+ GCC_except_table6698
+ GCC_except_table6805
+ GCC_except_table6809
+ GCC_except_table6811
+ GCC_except_table6812
+ GCC_except_table6979
+ GCC_except_table6986
+ GCC_except_table7103
+ GCC_except_table7158
+ GCC_except_table7160
+ GCC_except_table7162
+ GCC_except_table7184
+ GCC_except_table7214
+ GCC_except_table7226
+ GCC_except_table7251
+ GCC_except_table7257
+ GCC_except_table7268
+ GCC_except_table7270
+ GCC_except_table7272
+ GCC_except_table7274
+ GCC_except_table7276
+ GCC_except_table7278
+ GCC_except_table7280
+ GCC_except_table7282
+ GCC_except_table7284
+ GCC_except_table7286
+ GCC_except_table7288
+ GCC_except_table7290
+ GCC_except_table7292
+ GCC_except_table7297
+ GCC_except_table7311
+ GCC_except_table7312
+ GCC_except_table7335
+ GCC_except_table7337
+ GCC_except_table7362
+ GCC_except_table7375
+ GCC_except_table7393
+ GCC_except_table744
+ GCC_except_table747
+ GCC_except_table752
+ GCC_except_table755
+ GCC_except_table756
+ GCC_except_table7572
+ GCC_except_table7624
+ GCC_except_table7626
+ GCC_except_table778
+ GCC_except_table795
+ GCC_except_table7961
+ GCC_except_table8004
+ GCC_except_table8097
+ GCC_except_table8106
+ GCC_except_table814
+ GCC_except_table8281
+ GCC_except_table8283
+ GCC_except_table8284
+ GCC_except_table8285
+ GCC_except_table8287
+ GCC_except_table8289
+ GCC_except_table8290
+ GCC_except_table8291
+ GCC_except_table8329
+ GCC_except_table8330
+ GCC_except_table8333
+ GCC_except_table8336
+ GCC_except_table8337
+ GCC_except_table8380
+ GCC_except_table8381
+ GCC_except_table8382
+ GCC_except_table8389
+ GCC_except_table8390
+ GCC_except_table8392
+ GCC_except_table8411
+ GCC_except_table8480
+ GCC_except_table8481
+ GCC_except_table8482
+ GCC_except_table8515
+ GCC_except_table8524
+ GCC_except_table8538
+ GCC_except_table8609
+ GCC_except_table8639
+ GCC_except_table8640
+ GCC_except_table8641
+ GCC_except_table8643
+ GCC_except_table8646
+ GCC_except_table8647
+ GCC_except_table8655
+ GCC_except_table873
+ GCC_except_table876
+ GCC_except_table877
+ GCC_except_table8807
+ GCC_except_table8808
+ GCC_except_table8809
+ GCC_except_table8813
+ GCC_except_table8868
+ GCC_except_table8889
+ GCC_except_table8971
+ GCC_except_table8973
+ GCC_except_table8975
+ GCC_except_table8977
+ GCC_except_table8985
+ GCC_except_table9035
+ GCC_except_table9047
+ GCC_except_table9239
+ GCC_except_table9240
+ GCC_except_table9275
+ GCC_except_table9308
+ GCC_except_table9311
+ GCC_except_table9314
+ GCC_except_table9316
+ GCC_except_table9382
+ GCC_except_table9402
+ GCC_except_table9403
+ GCC_except_table9404
+ GCC_except_table943
+ GCC_except_table9443
+ GCC_except_table9445
+ GCC_except_table9447
+ GCC_except_table948
+ GCC_except_table949
+ GCC_except_table950
+ GCC_except_table951
+ GCC_except_table9512
+ GCC_except_table952
+ GCC_except_table953
+ GCC_except_table9544
+ GCC_except_table9546
+ GCC_except_table955
+ GCC_except_table9550
+ GCC_except_table9567
+ GCC_except_table9569
+ GCC_except_table957
+ GCC_except_table9575
+ GCC_except_table9579
+ GCC_except_table9582
+ GCC_except_table9589
+ GCC_except_table9593
+ GCC_except_table9599
+ GCC_except_table9611
+ GCC_except_table9614
+ GCC_except_table9622
+ GCC_except_table9623
+ GCC_except_table9625
+ GCC_except_table9627
+ GCC_except_table9629
+ GCC_except_table964
+ GCC_except_table9649
+ GCC_except_table965
+ GCC_except_table9659
+ GCC_except_table9875
+ GCC_except_table9888
+ GCC_except_table9929
+ GCC_except_table9932
+ GCC_except_table9934
+ GCC_except_table9947
+ GCC_except_table9948
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
+ ___41-[HMMediaGroupsController deriveGroupMap]_block_invoke_4
+ ___61-[HMUnrecognizedUserParentalControlSettings(Foundation) hash]_block_invoke
+ ___63-[HMHome _updateUnrecognizedUserSettingNamed:value:completion:]_block_invoke
+ ___82-[HMMediaGroupStagingManager notifyDestinationControllerGroupNameWithIdentifiers:]_block_invoke
+ ___95-[HMMediaGroupStagingManager notifyDestinationControllersWithDestinationControllerIdentifiers:]_block_invoke
+ ___block_descriptor_40_e8_32r_e35_v32?0"NSString"8"NSNumber"16^B24lr32l8
+ ___block_descriptor_40_e8_32s_e44_v16?0"HMMediaGroupStageHomeTheaterRename"8ls32l8
+ ___block_descriptor_48_e8_32s40s_e16_v16?0"NSUUID"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40bs_e5_v8?0ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s64l8s48l8s56l8
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
+ _logCategory._hmf_once_t559
+ _logCategory._hmf_once_t748
+ _logCategory._hmf_once_t848
+ _logCategory._hmf_once_t85
+ _logCategory._hmf_once_v101
+ _logCategory._hmf_once_v18
+ _logCategory._hmf_once_v560
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
- GCC_except_table1002
- GCC_except_table10026
- GCC_except_table10029
- GCC_except_table10032
- GCC_except_table10034
- GCC_except_table1005
- GCC_except_table10100
- GCC_except_table10120
- GCC_except_table10121
- GCC_except_table10122
- GCC_except_table1014
- GCC_except_table10161
- GCC_except_table10163
- GCC_except_table10165
- GCC_except_table10230
- GCC_except_table10262
- GCC_except_table10264
- GCC_except_table10268
- GCC_except_table1027
- GCC_except_table10285
- GCC_except_table10287
- GCC_except_table10293
- GCC_except_table10297
- GCC_except_table10300
- GCC_except_table10307
- GCC_except_table10311
- GCC_except_table10317
- GCC_except_table10329
- GCC_except_table10332
- GCC_except_table1034
- GCC_except_table10340
- GCC_except_table10341
- GCC_except_table10343
- GCC_except_table10345
- GCC_except_table10347
- GCC_except_table10377
- GCC_except_table10593
- GCC_except_table10606
- GCC_except_table10647
- GCC_except_table10650
- GCC_except_table10652
- GCC_except_table10665
- GCC_except_table10666
- GCC_except_table1073
- GCC_except_table10734
- GCC_except_table10737
- GCC_except_table10738
- GCC_except_table1075
- GCC_except_table11085
- GCC_except_table1110
- GCC_except_table1112
- GCC_except_table11123
- GCC_except_table11136
- GCC_except_table1114
- GCC_except_table1116
- GCC_except_table1123
- GCC_except_table1131
- GCC_except_table1141
- GCC_except_table11513
- GCC_except_table11514
- GCC_except_table11516
- GCC_except_table11517
- GCC_except_table11527
- GCC_except_table1153
- GCC_except_table11551
- GCC_except_table11555
- GCC_except_table11558
- GCC_except_table11567
- GCC_except_table11568
- GCC_except_table11569
- GCC_except_table1159
- GCC_except_table1162
- GCC_except_table11666
- GCC_except_table11692
- GCC_except_table11694
- GCC_except_table11698
- GCC_except_table11699
- GCC_except_table11747
- GCC_except_table11773
- GCC_except_table11786
- GCC_except_table11812
- GCC_except_table11816
- GCC_except_table11865
- GCC_except_table11866
- GCC_except_table11867
- GCC_except_table11868
- GCC_except_table11870
- GCC_except_table11871
- GCC_except_table11872
- GCC_except_table11873
- GCC_except_table11874
- GCC_except_table11875
- GCC_except_table11877
- GCC_except_table11878
- GCC_except_table11879
- GCC_except_table11880
- GCC_except_table11903
- GCC_except_table11930
- GCC_except_table12040
- GCC_except_table12041
- GCC_except_table12044
- GCC_except_table12110
- GCC_except_table12112
- GCC_except_table12120
- GCC_except_table12131
- GCC_except_table12133
- GCC_except_table12138
- GCC_except_table12139
- GCC_except_table12364
- GCC_except_table12482
- GCC_except_table1249
- GCC_except_table12492
- GCC_except_table1258
- GCC_except_table12587
- GCC_except_table1260
- GCC_except_table1270
- GCC_except_table12719
- GCC_except_table1272
- GCC_except_table12722
- GCC_except_table12727
- GCC_except_table12731
- GCC_except_table12737
- GCC_except_table1274
- GCC_except_table12742
- GCC_except_table12744
- GCC_except_table12749
- GCC_except_table12750
- GCC_except_table12752
- GCC_except_table1276
- GCC_except_table1278
- GCC_except_table12834
- GCC_except_table12836
- GCC_except_table1284
- GCC_except_table12855
- GCC_except_table12856
- GCC_except_table12857
- GCC_except_table12858
- GCC_except_table12863
- GCC_except_table12877
- GCC_except_table1288
- GCC_except_table12883
- GCC_except_table12886
- GCC_except_table12888
- GCC_except_table12934
- GCC_except_table12966
- GCC_except_table12976
- GCC_except_table12977
- GCC_except_table12982
- GCC_except_table12988
- GCC_except_table12990
- GCC_except_table12992
- GCC_except_table12994
- GCC_except_table12996
- GCC_except_table12998
- GCC_except_table13000
- GCC_except_table1301
- GCC_except_table1303
- GCC_except_table1305
- GCC_except_table1307
- GCC_except_table13133
- GCC_except_table13189
- GCC_except_table13190
- GCC_except_table13191
- GCC_except_table13192
- GCC_except_table13202
- GCC_except_table13227
- GCC_except_table13228
- GCC_except_table13304
- GCC_except_table13326
- GCC_except_table13329
- GCC_except_table13347
- GCC_except_table13349
- GCC_except_table1335
- GCC_except_table13517
- GCC_except_table13524
- GCC_except_table13529
- GCC_except_table1365
- GCC_except_table13726
- GCC_except_table13977
- GCC_except_table13979
- GCC_except_table13986
- GCC_except_table13994
- GCC_except_table14026
- GCC_except_table14031
- GCC_except_table14034
- GCC_except_table14048
- GCC_except_table14053
- GCC_except_table14059
- GCC_except_table14064
- GCC_except_table14069
- GCC_except_table14074
- GCC_except_table14079
- GCC_except_table14083
- GCC_except_table14088
- GCC_except_table14139
- GCC_except_table14143
- GCC_except_table14151
- GCC_except_table14156
- GCC_except_table14170
- GCC_except_table14175
- GCC_except_table14182
- GCC_except_table14198
- GCC_except_table14199
- GCC_except_table14201
- GCC_except_table14203
- GCC_except_table14206
- GCC_except_table14211
- GCC_except_table14218
- GCC_except_table14223
- GCC_except_table14264
- GCC_except_table14307
- GCC_except_table14316
- GCC_except_table14457
- GCC_except_table14657
- GCC_except_table14663
- GCC_except_table14666
- GCC_except_table14722
- GCC_except_table14757
- GCC_except_table14763
- GCC_except_table14768
- GCC_except_table14769
- GCC_except_table14774
- GCC_except_table14776
- GCC_except_table14777
- GCC_except_table14778
- GCC_except_table14779
- GCC_except_table14780
- GCC_except_table14781
- GCC_except_table14782
- GCC_except_table14783
- GCC_except_table14790
- GCC_except_table14797
- GCC_except_table14801
- GCC_except_table14804
- GCC_except_table14945
- GCC_except_table14948
- GCC_except_table14969
- GCC_except_table14971
- GCC_except_table14972
- GCC_except_table1526
- GCC_except_table1529
- GCC_except_table1534
- GCC_except_table1537
- GCC_except_table1560
- GCC_except_table1577
- GCC_except_table1596
- GCC_except_table1641
- GCC_except_table1644
- GCC_except_table1645
- GCC_except_table1711
- GCC_except_table1716
- GCC_except_table1717
- GCC_except_table1718
- GCC_except_table1719
- GCC_except_table1720
- GCC_except_table1721
- GCC_except_table1723
- GCC_except_table1725
- GCC_except_table1732
- GCC_except_table1733
- GCC_except_table1934
- GCC_except_table1938
- GCC_except_table1945
- GCC_except_table2020
- GCC_except_table2029
- GCC_except_table2097
- GCC_except_table2099
- GCC_except_table2102
- GCC_except_table2104
- GCC_except_table2106
- GCC_except_table2110
- GCC_except_table2280
- GCC_except_table2306
- GCC_except_table2372
- GCC_except_table2447
- GCC_except_table2450
- GCC_except_table2468
- GCC_except_table2536
- GCC_except_table2538
- GCC_except_table2549
- GCC_except_table2551
- GCC_except_table2690
- GCC_except_table2746
- GCC_except_table2749
- GCC_except_table2823
- GCC_except_table2910
- GCC_except_table2911
- GCC_except_table2960
- GCC_except_table3250
- GCC_except_table3253
- GCC_except_table3256
- GCC_except_table3261
- GCC_except_table3265
- GCC_except_table3274
- GCC_except_table3289
- GCC_except_table3290
- GCC_except_table3295
- GCC_except_table3296
- GCC_except_table3297
- GCC_except_table3298
- GCC_except_table3891
- GCC_except_table3896
- GCC_except_table3921
- GCC_except_table3923
- GCC_except_table3957
- GCC_except_table3960
- GCC_except_table3973
- GCC_except_table4017
- GCC_except_table4034
- GCC_except_table4037
- GCC_except_table4063
- GCC_except_table4065
- GCC_except_table4067
- GCC_except_table4069
- GCC_except_table4216
- GCC_except_table4219
- GCC_except_table4227
- GCC_except_table4228
- GCC_except_table4249
- GCC_except_table4276
- GCC_except_table4277
- GCC_except_table4349
- GCC_except_table4352
- GCC_except_table4353
- GCC_except_table4377
- GCC_except_table4379
- GCC_except_table4387
- GCC_except_table4389
- GCC_except_table4396
- GCC_except_table4397
- GCC_except_table4398
- GCC_except_table4400
- GCC_except_table4401
- GCC_except_table4402
- GCC_except_table4403
- GCC_except_table4404
- GCC_except_table4487
- GCC_except_table4510
- GCC_except_table4513
- GCC_except_table4516
- GCC_except_table4519
- GCC_except_table4522
- GCC_except_table4525
- GCC_except_table4528
- GCC_except_table4593
- GCC_except_table4640
- GCC_except_table4647
- GCC_except_table4648
- GCC_except_table4649
- GCC_except_table4652
- GCC_except_table4653
- GCC_except_table4654
- GCC_except_table4656
- GCC_except_table4664
- GCC_except_table4693
- GCC_except_table4697
- GCC_except_table4700
- GCC_except_table4745
- GCC_except_table4749
- GCC_except_table4753
- GCC_except_table4758
- GCC_except_table4766
- GCC_except_table4770
- GCC_except_table4779
- GCC_except_table4781
- GCC_except_table5025
- GCC_except_table5029
- GCC_except_table5033
- GCC_except_table5036
- GCC_except_table5040
- GCC_except_table5041
- GCC_except_table5044
- GCC_except_table5050
- GCC_except_table5054
- GCC_except_table5058
- GCC_except_table5087
- GCC_except_table5089
- GCC_except_table5091
- GCC_except_table5094
- GCC_except_table5095
- GCC_except_table5097
- GCC_except_table5100
- GCC_except_table5175
- GCC_except_table5189
- GCC_except_table5192
- GCC_except_table5194
- GCC_except_table5197
- GCC_except_table5204
- GCC_except_table5259
- GCC_except_table5326
- GCC_except_table5341
- GCC_except_table5344
- GCC_except_table5436
- GCC_except_table5437
- GCC_except_table5439
- GCC_except_table5448
- GCC_except_table5451
- GCC_except_table5453
- GCC_except_table5461
- GCC_except_table5725
- GCC_except_table5728
- GCC_except_table5740
- GCC_except_table5816
- GCC_except_table5862
- GCC_except_table5955
- GCC_except_table6152
- GCC_except_table6164
- GCC_except_table6166
- GCC_except_table6191
- GCC_except_table6192
- GCC_except_table6193
- GCC_except_table6194
- GCC_except_table6253
- GCC_except_table6263
- GCC_except_table6531
- GCC_except_table6533
- GCC_except_table6548
- GCC_except_table6673
- GCC_except_table6675
- GCC_except_table6693
- GCC_except_table6739
- GCC_except_table6834
- GCC_except_table6854
- GCC_except_table6855
- GCC_except_table6856
- GCC_except_table6858
- GCC_except_table6861
- GCC_except_table6862
- GCC_except_table6864
- GCC_except_table719
- GCC_except_table722
- GCC_except_table7222
- GCC_except_table7228
- GCC_except_table7230
- GCC_except_table7240
- GCC_except_table7241
- GCC_except_table7448
- GCC_except_table7452
- GCC_except_table7559
- GCC_except_table7563
- GCC_except_table7565
- GCC_except_table7566
- GCC_except_table7733
- GCC_except_table7740
- GCC_except_table7857
- GCC_except_table7912
- GCC_except_table7914
- GCC_except_table7916
- GCC_except_table7938
- GCC_except_table7968
- GCC_except_table7980
- GCC_except_table8005
- GCC_except_table8011
- GCC_except_table8022
- GCC_except_table8024
- GCC_except_table8026
- GCC_except_table8028
- GCC_except_table8030
- GCC_except_table8032
- GCC_except_table8034
- GCC_except_table8036
- GCC_except_table8038
- GCC_except_table8040
- GCC_except_table8042
- GCC_except_table8044
- GCC_except_table8046
- GCC_except_table8051
- GCC_except_table8065
- GCC_except_table8066
- GCC_except_table8089
- GCC_except_table8091
- GCC_except_table8116
- GCC_except_table8129
- GCC_except_table8147
- GCC_except_table820
- GCC_except_table839
- GCC_except_table849
- GCC_except_table8681
- GCC_except_table8724
- GCC_except_table8817
- GCC_except_table8826
- GCC_except_table9001
- GCC_except_table9003
- GCC_except_table9004
- GCC_except_table9005
- GCC_except_table9007
- GCC_except_table9009
- GCC_except_table9010
- GCC_except_table9011
- GCC_except_table9046
- GCC_except_table9050
- GCC_except_table9053
- GCC_except_table9056
- GCC_except_table9057
- GCC_except_table9100
- GCC_except_table9101
- GCC_except_table9102
- GCC_except_table9109
- GCC_except_table9110
- GCC_except_table9112
- GCC_except_table9131
- GCC_except_table9200
- GCC_except_table9201
- GCC_except_table9202
- GCC_except_table9235
- GCC_except_table9244
- GCC_except_table9258
- GCC_except_table9329
- GCC_except_table9359
- GCC_except_table9360
- GCC_except_table9361
- GCC_except_table9363
- GCC_except_table9366
- GCC_except_table9367
- GCC_except_table9374
- GCC_except_table9525
- GCC_except_table9526
- GCC_except_table9527
- GCC_except_table9531
- GCC_except_table9586
- GCC_except_table9607
- GCC_except_table9689
- GCC_except_table9691
- GCC_except_table9693
- GCC_except_table9695
- GCC_except_table9703
- GCC_except_table9753
- GCC_except_table9765
- GCC_except_table9767
- GCC_except_table9957
- GCC_except_table9958
- GCC_except_table9993
- __OBJC_$_CLASS_METHODS_HMAccessory(SwiftExtensions|HomeKit|HomeKit1|DynamicAccessorySettingsAdapter|PendingConfiguration|Private|CUPeerIdentifier|Diagnostics|ThreadManagement|SiriEndpoint|Television|ErrorStatus|LightInternal|HMDoorbellChimeProfile|NetworkRouter|Shortcuts|Camera|CameraInternal|CHIP|NetworkConfiguration|Climate|Light|Media)
- __OBJC_$_INSTANCE_METHODS_HMAccessory(SwiftExtensions|HomeKit|HomeKit1|DynamicAccessorySettingsAdapter|PendingConfiguration|Private|CUPeerIdentifier|Diagnostics|ThreadManagement|SiriEndpoint|Television|ErrorStatus|LightInternal|HMDoorbellChimeProfile|NetworkRouter|Shortcuts|Camera|CameraInternal|CHIP|NetworkConfiguration|Climate|Light|Media)
- __OBJC_$_INSTANCE_METHODS_HMClientConnection
- ___88-[HMMediaGroupStagingManager notifyDestinationControllersWithDestinationControllerData:]_block_invoke_2
- ___block_descriptor_56_e8_32s40bs_e5_v8?0ls40l8s32l8
- ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls56l8s32l8s40l8s48l8
- ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- ___swift_closure_destructor.121Tm
- _logCategory._hmf_once_t552
- _logCategory._hmf_once_t728
- _logCategory._hmf_once_t75
- _logCategory._hmf_once_t78
- _logCategory._hmf_once_t841
- _logCategory._hmf_once_t94
- _logCategory._hmf_once_v553
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
