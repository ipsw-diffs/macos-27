## WorkflowKit

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/Versions/A/WorkflowKit`

```diff

-5110.0.8.0.0
-  __TEXT.__text: 0x81e990
-  __TEXT.__objc_methlist: 0x2cfa4
-  __TEXT.__const: 0x25ea8
+5111.0.1.0.0
+  __TEXT.__text: 0x821294
+  __TEXT.__objc_methlist: 0x2d09c
+  __TEXT.__const: 0x25ed8
   __TEXT.__dlopen_cstrs: 0xf06
-  __TEXT.__swift5_typeref: 0xd648
-  __TEXT.__cstring: 0xaa78f
-  __TEXT.__oslogstring: 0x235ab
-  __TEXT.__constg_swiftt: 0x9d0c
+  __TEXT.__swift5_typeref: 0xd66c
+  __TEXT.__cstring: 0xaa9a9
+  __TEXT.__oslogstring: 0x23621
+  __TEXT.__constg_swiftt: 0x9d14
   __TEXT.__swift5_reflstr: 0x6648
   __TEXT.__swift5_fieldmd: 0x7d9c
   __TEXT.__swift5_builtin: 0x668

   __TEXT.__swift_as_cont: 0x13c4
   __TEXT.__swift5_protos: 0x14c
   __TEXT.__swift5_mpenum: 0xcc
-  __TEXT.__gcc_except_tab: 0x4d30
+  __TEXT.__gcc_except_tab: 0x4d4c
   __TEXT.__ustring: 0x3a22
-  __TEXT.__unwind_info: 0x21220
-  __TEXT.__eh_frame: 0x22e08
+  __TEXT.__unwind_info: 0x21308
+  __TEXT.__eh_frame: 0x22f10
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4e88
-  __DATA_CONST.__objc_classlist: 0x2438
+  __DATA_CONST.__const: 0x4f00
+  __DATA_CONST.__objc_classlist: 0x2450
   __DATA_CONST.__objc_catlist: 0x3d8
   __DATA_CONST.__objc_protolist: 0x690
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x13448
+  __DATA_CONST.__objc_selrefs: 0x134a8
   __DATA_CONST.__objc_protorefs: 0x290
-  __DATA_CONST.__objc_superrefs: 0x1368
+  __DATA_CONST.__objc_superrefs: 0x1370
   __DATA_CONST.__objc_arraydata: 0x1578
-  __DATA_CONST.__got: 0x5b90
-  __AUTH_CONST.__const: 0x4cc18
-  __AUTH_CONST.__cfstring: 0x293c0
-  __AUTH_CONST.__objc_const: 0x55618
+  __DATA_CONST.__got: 0x5bb8
+  __AUTH_CONST.__const: 0x4cc88
+  __AUTH_CONST.__cfstring: 0x294c0
+  __AUTH_CONST.__objc_const: 0x558b0
   __AUTH_CONST.__objc_dictobj: 0x4d8
   __AUTH_CONST.__objc_intobj: 0x1038
   __AUTH_CONST.__objc_arrayobj: 0x810
   __AUTH_CONST.__objc_doubleobj: 0x20
-  __AUTH_CONST.__auth_got: 0x4ee0
-  __AUTH.__objc_data: 0xf530
-  __AUTH.__data: 0x6898
-  __DATA.__objc_ivar: 0x2140
-  __DATA.__data: 0xccf8
-  __DATA.__bss: 0x30ad0
+  __AUTH_CONST.__auth_got: 0x4f08
+  __AUTH.__objc_data: 0xf580
+  __AUTH.__data: 0x68c8
+  __DATA.__objc_ivar: 0x2148
+  __DATA.__data: 0xcc58
+  __DATA.__bss: 0x308d0
   __DATA.__common: 0x2cc0
-  __DATA_DIRTY.__objc_data: 0xa638
-  __DATA_DIRTY.__data: 0x1e80
-  __DATA_DIRTY.__bss: 0x2358
+  __DATA_DIRTY.__objc_data: 0xa728
+  __DATA_DIRTY.__data: 0x1fd8
+  __DATA_DIRTY.__bss: 0x2558
   __DATA_DIRTY.__common: 0x20
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /System/Library/PrivateFrameworks/GRDBInternal.framework/Versions/A/GRDBInternal
   - /System/Library/PrivateFrameworks/GenerativeModels.framework/Versions/A/GenerativeModels
   - /System/Library/PrivateFrameworks/GenerativePartnerService.framework/Versions/A/GenerativePartnerService
-  - /System/Library/PrivateFrameworks/GenerativeSearch.framework/Versions/A/GenerativeSearch
-  - /System/Library/PrivateFrameworks/GenerativeSearchAdapter.framework/Versions/A/GenerativeSearchAdapter
+  - /System/Library/PrivateFrameworks/HybridSearch.framework/Versions/A/HybridSearch
+  - /System/Library/PrivateFrameworks/HybridSearchAdapter.framework/Versions/A/HybridSearchAdapter
   - /System/Library/PrivateFrameworks/IDS.framework/Versions/A/IDS
   - /System/Library/PrivateFrameworks/IntelligencePlatformLibrary.framework/Versions/A/IntelligencePlatformLibrary
   - /System/Library/PrivateFrameworks/IntelligencePlatformQuery.framework/Versions/A/IntelligencePlatformQuery

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 43714
-  Symbols:   42437
-  CStrings:  19308
+  Functions: 43785
+  Symbols:   42479
+  CStrings:  19323
 
Symbols:
+ -[WFHarnessTestRunDescriptor harnessDylibPath]
+ -[WFHarnessTestRunDescriptor initWithTestBundleURL:xcTestClass:xcTestMethodName:testIdentifier:harnessDylibPath:]
+ -[WFHarnessTestRunRequest initWithTestBundleURL:xcTestClass:xcTestMethodName:testIdentifier:automationType:harnessDylibPath:]
+ -[WFProgramOpaqueActionNode initWithAction:name:]
+ -[WFProgramOpaqueActionNode renderedWithContext:]
+ -[WFRemoteWidgetConnection _armTimeoutWithReason:precondition:]
+ -[WFRemoteWidgetConnection _timedOutWithReason:]
+ -[WFRemoteWidgetConnection setTimedOut:]
+ -[WFRemoteWidgetConnection timedOut]
+ GCC_except_table10017
+ GCC_except_table10052
+ GCC_except_table10085
+ GCC_except_table10087
+ GCC_except_table10112
+ GCC_except_table10119
+ GCC_except_table10121
+ GCC_except_table10123
+ GCC_except_table10165
+ GCC_except_table10170
+ GCC_except_table10210
+ GCC_except_table10213
+ GCC_except_table10216
+ GCC_except_table10219
+ GCC_except_table10483
+ GCC_except_table10500
+ GCC_except_table10546
+ GCC_except_table10765
+ GCC_except_table10792
+ GCC_except_table10807
+ GCC_except_table10862
+ GCC_except_table11006
+ GCC_except_table11087
+ GCC_except_table11093
+ GCC_except_table11096
+ GCC_except_table11099
+ GCC_except_table11102
+ GCC_except_table11105
+ GCC_except_table11108
+ GCC_except_table11115
+ GCC_except_table11119
+ GCC_except_table11124
+ GCC_except_table11136
+ GCC_except_table11139
+ GCC_except_table11142
+ GCC_except_table11145
+ GCC_except_table11148
+ GCC_except_table11151
+ GCC_except_table11154
+ GCC_except_table11157
+ GCC_except_table11160
+ GCC_except_table11163
+ GCC_except_table11166
+ GCC_except_table11271
+ GCC_except_table11438
+ GCC_except_table11598
+ GCC_except_table11619
+ GCC_except_table11621
+ GCC_except_table11626
+ GCC_except_table11658
+ GCC_except_table11671
+ GCC_except_table11678
+ GCC_except_table11732
+ GCC_except_table11771
+ GCC_except_table11785
+ GCC_except_table11789
+ GCC_except_table11791
+ GCC_except_table11887
+ GCC_except_table11903
+ GCC_except_table12001
+ GCC_except_table12059
+ GCC_except_table12112
+ GCC_except_table12141
+ GCC_except_table12196
+ GCC_except_table12207
+ GCC_except_table12257
+ GCC_except_table12259
+ GCC_except_table12274
+ GCC_except_table12432
+ GCC_except_table12494
+ GCC_except_table12525
+ GCC_except_table12604
+ GCC_except_table12637
+ GCC_except_table12680
+ GCC_except_table12725
+ GCC_except_table12738
+ GCC_except_table12743
+ GCC_except_table12764
+ GCC_except_table12765
+ GCC_except_table12766
+ GCC_except_table12775
+ GCC_except_table12786
+ GCC_except_table12936
+ GCC_except_table12959
+ GCC_except_table12962
+ GCC_except_table12964
+ GCC_except_table13025
+ GCC_except_table13037
+ GCC_except_table13041
+ GCC_except_table13245
+ GCC_except_table13313
+ GCC_except_table13556
+ GCC_except_table13597
+ GCC_except_table13726
+ GCC_except_table13829
+ GCC_except_table13834
+ GCC_except_table13843
+ GCC_except_table13846
+ GCC_except_table13894
+ GCC_except_table13923
+ GCC_except_table13934
+ GCC_except_table13936
+ GCC_except_table13949
+ GCC_except_table14021
+ GCC_except_table14146
+ GCC_except_table14167
+ GCC_except_table14178
+ GCC_except_table14192
+ GCC_except_table14195
+ GCC_except_table14364
+ GCC_except_table14391
+ GCC_except_table14487
+ GCC_except_table2825
+ GCC_except_table2828
+ GCC_except_table2842
+ GCC_except_table2912
+ GCC_except_table2945
+ GCC_except_table2962
+ GCC_except_table2968
+ GCC_except_table3020
+ GCC_except_table3030
+ GCC_except_table3038
+ GCC_except_table3046
+ GCC_except_table3074
+ GCC_except_table3119
+ GCC_except_table3399
+ GCC_except_table3439
+ GCC_except_table3444
+ GCC_except_table3477
+ GCC_except_table3495
+ GCC_except_table3499
+ GCC_except_table3561
+ GCC_except_table3572
+ GCC_except_table3574
+ GCC_except_table3577
+ GCC_except_table3679
+ GCC_except_table3687
+ GCC_except_table3691
+ GCC_except_table3693
+ GCC_except_table3698
+ GCC_except_table3838
+ GCC_except_table3961
+ GCC_except_table3965
+ GCC_except_table4342
+ GCC_except_table4455
+ GCC_except_table4529
+ GCC_except_table4543
+ GCC_except_table4562
+ GCC_except_table4570
+ GCC_except_table4720
+ GCC_except_table4858
+ GCC_except_table4864
+ GCC_except_table4870
+ GCC_except_table4922
+ GCC_except_table4936
+ GCC_except_table4998
+ GCC_except_table5069
+ GCC_except_table5096
+ GCC_except_table5103
+ GCC_except_table5206
+ GCC_except_table5215
+ GCC_except_table5274
+ GCC_except_table5329
+ GCC_except_table5339
+ GCC_except_table5377
+ GCC_except_table5386
+ GCC_except_table5387
+ GCC_except_table5452
+ GCC_except_table5532
+ GCC_except_table5535
+ GCC_except_table5538
+ GCC_except_table5541
+ GCC_except_table5544
+ GCC_except_table5551
+ GCC_except_table5558
+ GCC_except_table5564
+ GCC_except_table5568
+ GCC_except_table5572
+ GCC_except_table5828
+ GCC_except_table5971
+ GCC_except_table6004
+ GCC_except_table6078
+ GCC_except_table6090
+ GCC_except_table6203
+ GCC_except_table6283
+ GCC_except_table6350
+ GCC_except_table6351
+ GCC_except_table6451
+ GCC_except_table6501
+ GCC_except_table6519
+ GCC_except_table6765
+ GCC_except_table6766
+ GCC_except_table6906
+ GCC_except_table6907
+ GCC_except_table6969
+ GCC_except_table6973
+ GCC_except_table6974
+ GCC_except_table6977
+ GCC_except_table6983
+ GCC_except_table6988
+ GCC_except_table6993
+ GCC_except_table6994
+ GCC_except_table6998
+ GCC_except_table7039
+ GCC_except_table7044
+ GCC_except_table7102
+ GCC_except_table7118
+ GCC_except_table7180
+ GCC_except_table7181
+ GCC_except_table7391
+ GCC_except_table7401
+ GCC_except_table7477
+ GCC_except_table7482
+ GCC_except_table7696
+ GCC_except_table7699
+ GCC_except_table7777
+ GCC_except_table7778
+ GCC_except_table7815
+ GCC_except_table7871
+ GCC_except_table7920
+ GCC_except_table8065
+ GCC_except_table8076
+ GCC_except_table8195
+ GCC_except_table8204
+ GCC_except_table8216
+ GCC_except_table8274
+ GCC_except_table8289
+ GCC_except_table8290
+ GCC_except_table8774
+ GCC_except_table8811
+ GCC_except_table8878
+ GCC_except_table8930
+ GCC_except_table9134
+ GCC_except_table9140
+ GCC_except_table9153
+ GCC_except_table9159
+ GCC_except_table9171
+ GCC_except_table9175
+ GCC_except_table9188
+ GCC_except_table9201
+ GCC_except_table9207
+ GCC_except_table9214
+ GCC_except_table9261
+ GCC_except_table9267
+ GCC_except_table9273
+ GCC_except_table9311
+ GCC_except_table9320
+ GCC_except_table9405
+ GCC_except_table9464
+ GCC_except_table9495
+ GCC_except_table9497
+ GCC_except_table9506
+ GCC_except_table9508
+ GCC_except_table9515
+ GCC_except_table9518
+ GCC_except_table9539
+ GCC_except_table9541
+ GCC_except_table9543
+ GCC_except_table9548
+ GCC_except_table9656
+ GCC_except_table9826
+ GCC_except_table9832
+ GCC_except_table9851
+ OBJC_IVAR_$_WFHarnessTestRunDescriptor._harnessDylibPath
+ OBJC_IVAR_$_WFRemoteWidgetConnection._timedOut
+ _OBJC_CLASS_$_WFOpaqueActionEntry
+ _OBJC_CLASS_$_WFOpaqueActionTable
+ _OBJC_CLASS_$_WFProgramOpaqueActionNode
+ _OBJC_METACLASS_$_WFOpaqueActionEntry
+ _OBJC_METACLASS_$_WFOpaqueActionTable
+ _OBJC_METACLASS_$_WFProgramOpaqueActionNode
+ _WFActionDiscontinuedByShortcutsKey
+ _WFWhatsNewLastPresentedMessageVersionKey
+ __55-[WFRemoteWidgetConnection sendData:completionHandler:]_block_invoke
+ __DATA_WFOpaqueActionEntry
+ __DATA_WFOpaqueActionTable
+ __INSTANCE_METHODS_WFOpaqueActionEntry
+ __INSTANCE_METHODS_WFOpaqueActionTable
+ __IVARS_WFOpaqueActionEntry
+ __IVARS_WFOpaqueActionTable
+ __METACLASS_DATA_WFOpaqueActionEntry
+ __METACLASS_DATA_WFOpaqueActionTable
+ __OBJC_$_CLASS_METHODS_WFOpenUserActivityAction(WorkflowKit|WFLCompatibility)
+ __OBJC_$_INSTANCE_METHODS_WFHandleDonatedIntentAction(WorkflowKit|WFLCompatibility)
+ __OBJC_$_INSTANCE_METHODS_WFOpenUserActivityAction(WorkflowKit|WFLCompatibility)
+ __OBJC_$_INSTANCE_METHODS_WFProgramOpaqueActionNode
+ __OBJC_CLASS_RO_$_WFProgramOpaqueActionNode
+ __OBJC_METACLASS_RO_$_WFProgramOpaqueActionNode
+ __PROPERTIES_WFOpaqueActionEntry
+ ___63-[WFRemoteWidgetConnection _armTimeoutWithReason:precondition:]_block_invoke
+ ___block_descriptor_32_e34_B16?0"WFRemoteWidgetConnection"8l
+ ___block_descriptor_56_e8_32s40bs48w_e5_v8?0l
+ _objc_msgSend$_armTimeoutWithReason:precondition:
+ _objc_msgSend$_timedOutWithReason:
+ _objc_msgSend$harnessDylibPath
+ _objc_msgSend$initWithAction:name:
+ _objc_msgSend$initWithActionID:serializedParameters:
+ _objc_msgSend$initWithPythonCode:catalog:opaqueActions:
+ _objc_msgSend$initWithTestBundleURL:xcTestClass:xcTestMethodName:testIdentifier:harnessDylibPath:
+ _objc_msgSend$insertAction:preferredName:
+ _objc_msgSend$nameForOpaqueAction:preferredName:
+ _objc_msgSend$opaqueActions
+ _objc_msgSend$setTimedOut:
+ _objc_msgSend$timedOut
+ _objc_msgSend$userActivityType
+ _symbolic _____ySSSo19WFOpaqueActionEntryCG s17_NativeDictionaryV
- -[WFHandleDonatedIntentAction exportWithError:]
- -[WFHarnessTestRunDescriptor initWithTestBundleURL:xcTestClass:xcTestMethodName:testIdentifier:]
- -[WFHarnessTestRunRequest initWithTestBundleURL:xcTestClass:xcTestMethodName:testIdentifier:automationType:]
- -[WFOpenUserActivityAction exportWithError:]
- GCC_except_table10009
- GCC_except_table10044
- GCC_except_table10077
- GCC_except_table10079
- GCC_except_table10104
- GCC_except_table10111
- GCC_except_table10113
- GCC_except_table10115
- GCC_except_table10157
- GCC_except_table10162
- GCC_except_table10202
- GCC_except_table10205
- GCC_except_table10208
- GCC_except_table10211
- GCC_except_table10475
- GCC_except_table10492
- GCC_except_table10538
- GCC_except_table10757
- GCC_except_table10784
- GCC_except_table10799
- GCC_except_table10854
- GCC_except_table10998
- GCC_except_table11079
- GCC_except_table11085
- GCC_except_table11088
- GCC_except_table11091
- GCC_except_table11094
- GCC_except_table11097
- GCC_except_table11100
- GCC_except_table11103
- GCC_except_table11107
- GCC_except_table11116
- GCC_except_table11123
- GCC_except_table11128
- GCC_except_table11134
- GCC_except_table11137
- GCC_except_table11140
- GCC_except_table11143
- GCC_except_table11146
- GCC_except_table11149
- GCC_except_table11152
- GCC_except_table11155
- GCC_except_table11158
- GCC_except_table11263
- GCC_except_table11430
- GCC_except_table11590
- GCC_except_table11605
- GCC_except_table11611
- GCC_except_table11618
- GCC_except_table11650
- GCC_except_table11663
- GCC_except_table11670
- GCC_except_table11724
- GCC_except_table11763
- GCC_except_table11777
- GCC_except_table11781
- GCC_except_table11783
- GCC_except_table11879
- GCC_except_table11895
- GCC_except_table11993
- GCC_except_table12051
- GCC_except_table12104
- GCC_except_table12133
- GCC_except_table12189
- GCC_except_table12200
- GCC_except_table12250
- GCC_except_table12252
- GCC_except_table12267
- GCC_except_table12425
- GCC_except_table12487
- GCC_except_table12518
- GCC_except_table12597
- GCC_except_table12630
- GCC_except_table12673
- GCC_except_table12718
- GCC_except_table12731
- GCC_except_table12736
- GCC_except_table12750
- GCC_except_table12758
- GCC_except_table12759
- GCC_except_table12768
- GCC_except_table12779
- GCC_except_table12929
- GCC_except_table12952
- GCC_except_table12955
- GCC_except_table12957
- GCC_except_table13018
- GCC_except_table13030
- GCC_except_table13034
- GCC_except_table13238
- GCC_except_table13306
- GCC_except_table13549
- GCC_except_table13590
- GCC_except_table13719
- GCC_except_table13822
- GCC_except_table13827
- GCC_except_table13836
- GCC_except_table13839
- GCC_except_table13887
- GCC_except_table13916
- GCC_except_table13927
- GCC_except_table13929
- GCC_except_table13942
- GCC_except_table14014
- GCC_except_table14139
- GCC_except_table14160
- GCC_except_table14171
- GCC_except_table14185
- GCC_except_table14188
- GCC_except_table14357
- GCC_except_table14384
- GCC_except_table14480
- GCC_except_table2826
- GCC_except_table2829
- GCC_except_table2843
- GCC_except_table2913
- GCC_except_table2946
- GCC_except_table2963
- GCC_except_table2969
- GCC_except_table3021
- GCC_except_table3031
- GCC_except_table3039
- GCC_except_table3047
- GCC_except_table3075
- GCC_except_table3118
- GCC_except_table3398
- GCC_except_table3438
- GCC_except_table3443
- GCC_except_table3476
- GCC_except_table3494
- GCC_except_table3498
- GCC_except_table3560
- GCC_except_table3571
- GCC_except_table3573
- GCC_except_table3576
- GCC_except_table3678
- GCC_except_table3686
- GCC_except_table3690
- GCC_except_table3692
- GCC_except_table3696
- GCC_except_table3837
- GCC_except_table3960
- GCC_except_table3964
- GCC_except_table4341
- GCC_except_table4454
- GCC_except_table4528
- GCC_except_table4542
- GCC_except_table4561
- GCC_except_table4569
- GCC_except_table4719
- GCC_except_table4857
- GCC_except_table4863
- GCC_except_table4869
- GCC_except_table4920
- GCC_except_table4934
- GCC_except_table4996
- GCC_except_table5067
- GCC_except_table5094
- GCC_except_table5101
- GCC_except_table5204
- GCC_except_table5213
- GCC_except_table5272
- GCC_except_table5327
- GCC_except_table5335
- GCC_except_table5375
- GCC_except_table5384
- GCC_except_table5385
- GCC_except_table5450
- GCC_except_table5530
- GCC_except_table5533
- GCC_except_table5536
- GCC_except_table5539
- GCC_except_table5542
- GCC_except_table5545
- GCC_except_table5552
- GCC_except_table5560
- GCC_except_table5566
- GCC_except_table5570
- GCC_except_table5826
- GCC_except_table5969
- GCC_except_table6002
- GCC_except_table6076
- GCC_except_table6088
- GCC_except_table6201
- GCC_except_table6281
- GCC_except_table6347
- GCC_except_table6348
- GCC_except_table6449
- GCC_except_table6499
- GCC_except_table6517
- GCC_except_table6760
- GCC_except_table6761
- GCC_except_table6904
- GCC_except_table6905
- GCC_except_table6967
- GCC_except_table6971
- GCC_except_table6972
- GCC_except_table6975
- GCC_except_table6981
- GCC_except_table6986
- GCC_except_table6991
- GCC_except_table6992
- GCC_except_table6996
- GCC_except_table7037
- GCC_except_table7042
- GCC_except_table7100
- GCC_except_table7116
- GCC_except_table7178
- GCC_except_table7179
- GCC_except_table7389
- GCC_except_table7399
- GCC_except_table7475
- GCC_except_table7480
- GCC_except_table7694
- GCC_except_table7697
- GCC_except_table7775
- GCC_except_table7776
- GCC_except_table7813
- GCC_except_table7869
- GCC_except_table7918
- GCC_except_table8063
- GCC_except_table8074
- GCC_except_table8193
- GCC_except_table8202
- GCC_except_table8214
- GCC_except_table8272
- GCC_except_table8283
- GCC_except_table8288
- GCC_except_table8772
- GCC_except_table8809
- GCC_except_table8876
- GCC_except_table8928
- GCC_except_table9132
- GCC_except_table9138
- GCC_except_table9145
- GCC_except_table9155
- GCC_except_table9169
- GCC_except_table9173
- GCC_except_table9186
- GCC_except_table9199
- GCC_except_table9205
- GCC_except_table9212
- GCC_except_table9259
- GCC_except_table9265
- GCC_except_table9271
- GCC_except_table9309
- GCC_except_table9318
- GCC_except_table9403
- GCC_except_table9462
- GCC_except_table9491
- GCC_except_table9493
- GCC_except_table9499
- GCC_except_table9501
- GCC_except_table9510
- GCC_except_table9531
- GCC_except_table9532
- GCC_except_table9533
- GCC_except_table9535
- GCC_except_table9648
- GCC_except_table9818
- GCC_except_table9824
- GCC_except_table9843
- __OBJC_$_CLASS_METHODS_WFOpenUserActivityAction(WFLCompatibility)
- __OBJC_$_INSTANCE_METHODS_WFHandleDonatedIntentAction(WFLCompatibility)
- __OBJC_$_INSTANCE_METHODS_WFOpenUserActivityAction
- _objc_msgSend$errorForIncompatibleAction:
- _objc_msgSend$initWithPythonCode:catalog:
- _objc_msgSend$initWithTestBundleURL:xcTestClass:xcTestMethodName:testIdentifier:
- _objc_msgSend$sharedSupportURL
CStrings:
+ "%@ %p: xcTestClass: %@, xcTestMethodName: %@, testIdentifier: %@, testCase != nil: %d, testBundleURL: %@, harnessDylibPath: %@)"
+ "%@()"
+ "%s Could not dlopen test dylib at path %@: %s"
+ "%s Could not find action harness test dylib at %@"
+ "%s Remote widget outgoing connection to endpoint %@ is waiting to connect and will retry until it times out, error=%@"
+ "%s Timed out %{public}@ after %llds; failing %lu pending request(s)"
+ "-[WFHarnessTestRunDescriptor initWithTestBundleURL:xcTestClass:xcTestMethodName:testIdentifier:harnessDylibPath:]"
+ "-[WFRemoteWidgetConnection _timedOutWithReason:]"
+ "Apple.Group1.AutomationTools.Pro"
+ "Apple.Group1.AutomationTools.Zap"
+ "Archives do not support opaque actions"
+ "B16@?0@\"WFRemoteWidgetConnection\"8"
+ "DiscontinuedByShortcuts"
+ "Parent Directory"
+ "Parent Directory (Default Output Name)"
+ "WFProgramFunctionCallNode.m"
+ "WFWhatsNewLastPresentedMessageVersion"
+ "WorkflowKit_Private.Entry"
+ "establishing a connection to the target remote device"
+ "handle donated intent"
+ "harnessDylibPath"
+ "name.length > 0"
+ "opaque_action"
+ "open user activity"
+ "waiting for a response from the target remote device"
- "%@ %p: xcTestClass: %@, xcTestMethodName: %@, testIdentifier: %@, testCase != nil: %d, testBundleURL: %@)"
- "%s Could not dlopen test dylib at path %@"
- "%s Could not find action harness test dylib in bundle %@"
- "%s Timed out establishing connection to the target remote device"
- "-[WFHarnessTestRunDescriptor initWithTestBundleURL:xcTestClass:xcTestMethodName:testIdentifier:]"
- "AutomationTools.Pro"
- "AutomationTools.Zap"
- "NONE SELF.value.bundleID IN %@"
- "iPhone or iPod touch"
- "libActionHarnessTests.dylib"
```
