## NeutrinoCore

> `/System/Library/PrivateFrameworks/NeutrinoCore.framework/Versions/A/NeutrinoCore`

```diff

-916.41.100.0.0
-  __TEXT.__text: 0x343710
-  __TEXT.__objc_methlist: 0x20f0c
+916.45.110.0.0
+  __TEXT.__text: 0x345fe8
+  __TEXT.__objc_methlist: 0x210fc
   __TEXT.__const: 0x27a8
   __TEXT.__dlopen_cstrs: 0x45
   __TEXT.__swift5_typeref: 0x3c9

   __TEXT.__swift5_fieldmd: 0x15c
   __TEXT.__swift5_proto: 0x64
   __TEXT.__swift5_types: 0x28
-  __TEXT.__cstring: 0x40412
-  __TEXT.__swift5_capture: 0x230
-  __TEXT.__gcc_except_tab: 0x81ac
+  __TEXT.__cstring: 0x40712
+  __TEXT.__swift5_capture: 0x1f0
+  __TEXT.__gcc_except_tab: 0x8194
   __TEXT.__oslogstring: 0x5930
   __TEXT.__ustring: 0x2e
-  __TEXT.__unwind_info: 0xa3f0
-  __TEXT.__eh_frame: 0x460
+  __TEXT.__unwind_info: 0xa458
+  __TEXT.__eh_frame: 0x400
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1650
-  __DATA_CONST.__objc_classlist: 0x15f8
+  __DATA_CONST.__const: 0x1660
+  __DATA_CONST.__objc_classlist: 0x1600
   __DATA_CONST.__objc_catlist: 0xa8
   __DATA_CONST.__objc_protolist: 0x4d8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb6d0
+  __DATA_CONST.__objc_selrefs: 0xb738
   __DATA_CONST.__objc_protorefs: 0x68
-  __DATA_CONST.__objc_superrefs: 0x1010
+  __DATA_CONST.__objc_superrefs: 0x1018
   __DATA_CONST.__objc_arraydata: 0xac0
   __DATA_CONST.__got: 0x2290
-  __AUTH_CONST.__const: 0x8238
-  __AUTH_CONST.__cfstring: 0x1d080
-  __AUTH_CONST.__objc_const: 0x37770
+  __AUTH_CONST.__const: 0x80e8
+  __AUTH_CONST.__cfstring: 0x1d040
+  __AUTH_CONST.__objc_const: 0x37a10
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x8d0
   __AUTH_CONST.__objc_dictobj: 0x320

   __AUTH_CONST.__objc_floatobj: 0x70
   __AUTH_CONST.__objc_arrayobj: 0xf0
   __AUTH_CONST.__auth_got: 0xfd0
-  __AUTH.__objc_data: 0x2d0
-  __DATA.__objc_ivar: 0x1a4c
-  __DATA.__data: 0x3938
+  __AUTH.__objc_data: 0x50
+  __DATA.__objc_ivar: 0x1a78
+  __DATA.__data: 0x1c0
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0xf80
-  __DATA_DIRTY.__objc_data: 0xd8e0
-  __DATA_DIRTY.__data: 0x8
-  __DATA_DIRTY.__bss: 0x1e8
+  __DATA.__bss: 0x1010
+  __DATA_DIRTY.__objc_data: 0xdbb0
+  __DATA_DIRTY.__data: 0x3780
+  __DATA_DIRTY.__bss: 0x158
   __DATA_DIRTY.__common: 0x40
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11995
-  Symbols:   25733
-  CStrings:  7293
+  Functions: 12022
+  Symbols:   25803
+  CStrings:  7309
 
Symbols:
+ +[NUPipelineFactory buildPipelineWithBuilder:]
+ +[NUPipelineFactory computePipelineWithProcessorName:bundleIdentifier:error:]
+ +[NUPipelineFactory metadataPipelineWithProcessorName:bundleIdentifier:error:]
+ +[NUPipelineFactory renderPipelineWithProcessorName:bundleIdentifier:error:]
+ +[NUPipelineProcessor processorWithName:bundleIdentifier:error:]
+ -[NUArrayDescriptor canAcceptDataWithNonOptionalDescriptor:]
+ -[NUChannelControlFormat isOptional]
+ -[NUChannelControlFormat nonOptionalFormat]
+ -[NUChannelFormat isOptional]
+ -[NUChannelFormat nonOptionalFormat]
+ -[NUChannelOptionalFormat .cxx_destruct]
+ -[NUChannelOptionalFormat arrayItemFormat]
+ -[NUChannelOptionalFormat canAcceptDataWithFormat:]
+ -[NUChannelOptionalFormat canSpecializeFormat:]
+ -[NUChannelOptionalFormat channelType]
+ -[NUChannelOptionalFormat debugDescription]
+ -[NUChannelOptionalFormat description]
+ -[NUChannelOptionalFormat elementChannel]
+ -[NUChannelOptionalFormat hash]
+ -[NUChannelOptionalFormat initWithWrappedFormat:]
+ -[NUChannelOptionalFormat init]
+ -[NUChannelOptionalFormat isArray]
+ -[NUChannelOptionalFormat isComparableToChannelFormat:]
+ -[NUChannelOptionalFormat isComputedData]
+ -[NUChannelOptionalFormat isEqualToChannelFormat:]
+ -[NUChannelOptionalFormat isEqualToOptionalFormat:]
+ -[NUChannelOptionalFormat isGeneric]
+ -[NUChannelOptionalFormat isOptional]
+ -[NUChannelOptionalFormat nonOptionalFormat]
+ -[NUChannelOptionalFormat requiresSubchannelDataForKey:]
+ -[NUChannelOptionalFormat specializedWithFormat:]
+ -[NUChannelOptionalFormat subchannelFormatForKey:]
+ -[NUChannelOptionalFormat subchannelKeys]
+ -[NUChannelOptionalFormat wrappedFormat]
+ -[NUCompoundDescriptor canAcceptDataWithNonOptionalDescriptor:]
+ -[NUControlDescriptor canAcceptDataWithNonOptionalDescriptor:]
+ -[NUControlDescriptor nonOptionalDescriptor]
+ -[NUCoreImageFilterPipelineProcessor copyWithZone:]
+ -[NUEnumDescriptor canAcceptDataWithNonOptionalDescriptor:]
+ -[NUExpressionComputeProcessor copyWithZone:]
+ -[NUFaceDetectionPipelineProcessor copyWithZone:]
+ -[NUNumberDescriptor canAcceptDataWithNonOptionalDescriptor:]
+ -[NUOptionalDescriptor initWithDescriptor:validatedDefaultValue:]
+ -[NUOptionalDescriptor isOptional]
+ -[NUOptionalDescriptor nonOptionalDescriptor]
+ -[NUPipelineProcessor copyWithZone:]
+ -[NUPipelineProcessorCache processorForConfiguration:processor:controlData:error:]
+ -[NUVectorDescriptor canAcceptDataWithNonOptionalDescriptor:]
+ -[_NUHDRColorVolumePipeline .cxx_destruct]
+ -[_NUHDRColorVolumePipeline build:]
+ -[_NUHDRGainMapApplyPipeline .cxx_destruct]
+ -[_NUHDRGainMapComputePipeline .cxx_destruct]
+ -[_NUHDRGainMapComputePipeline build:]
+ -[_NUMapPipeline .cxx_destruct]
+ -[_NUMapPipeline addElementOutputChannel:]
+ -[_NUMapPipeline elementInputPort]
+ -[_NUMapPipeline initWithArrayChannel:]
+ -[_NUPipeline addPipelineWithBuilder:]
+ -[_NUReducePipeline .cxx_destruct]
+ -[_NUReducePipeline accumulatorInputPort]
+ -[_NUReducePipeline accumulatorOutputPort]
+ -[_NUReducePipeline elementInputPort]
+ -[_NUReducePipeline initWithArrayChannel:accumulatorChannel:]
+ GCC_except_table10037
+ GCC_except_table10061
+ GCC_except_table10062
+ GCC_except_table10069
+ GCC_except_table10086
+ GCC_except_table10096
+ GCC_except_table10102
+ GCC_except_table10103
+ GCC_except_table10104
+ GCC_except_table10106
+ GCC_except_table10108
+ GCC_except_table10111
+ GCC_except_table10112
+ GCC_except_table10113
+ GCC_except_table10185
+ GCC_except_table10195
+ GCC_except_table10410
+ GCC_except_table10411
+ GCC_except_table10417
+ GCC_except_table10418
+ GCC_except_table10420
+ GCC_except_table10421
+ GCC_except_table10518
+ GCC_except_table10519
+ GCC_except_table10524
+ GCC_except_table10529
+ GCC_except_table10536
+ GCC_except_table10537
+ GCC_except_table10539
+ GCC_except_table10540
+ GCC_except_table10550
+ GCC_except_table10551
+ GCC_except_table10556
+ GCC_except_table10563
+ GCC_except_table10569
+ GCC_except_table10570
+ GCC_except_table10571
+ GCC_except_table10578
+ GCC_except_table10597
+ GCC_except_table10598
+ GCC_except_table10600
+ GCC_except_table10602
+ GCC_except_table10603
+ GCC_except_table10604
+ GCC_except_table10609
+ GCC_except_table10610
+ GCC_except_table10611
+ GCC_except_table10612
+ GCC_except_table10613
+ GCC_except_table10615
+ GCC_except_table10616
+ GCC_except_table10617
+ GCC_except_table10618
+ GCC_except_table10619
+ GCC_except_table10620
+ GCC_except_table10621
+ GCC_except_table10622
+ GCC_except_table10627
+ GCC_except_table10628
+ GCC_except_table10629
+ GCC_except_table10630
+ GCC_except_table10631
+ GCC_except_table10632
+ GCC_except_table10690
+ GCC_except_table10741
+ GCC_except_table10830
+ GCC_except_table10834
+ GCC_except_table11337
+ GCC_except_table11498
+ GCC_except_table11500
+ GCC_except_table11546
+ GCC_except_table11600
+ GCC_except_table11608
+ GCC_except_table11615
+ GCC_except_table11616
+ GCC_except_table11620
+ GCC_except_table2165
+ GCC_except_table2817
+ GCC_except_table2885
+ GCC_except_table2935
+ GCC_except_table2947
+ GCC_except_table3130
+ GCC_except_table3277
+ GCC_except_table3368
+ GCC_except_table3369
+ GCC_except_table3370
+ GCC_except_table3373
+ GCC_except_table3374
+ GCC_except_table3377
+ GCC_except_table3385
+ GCC_except_table3388
+ GCC_except_table3389
+ GCC_except_table3390
+ GCC_except_table3391
+ GCC_except_table3392
+ GCC_except_table3394
+ GCC_except_table3395
+ GCC_except_table3403
+ GCC_except_table3408
+ GCC_except_table3414
+ GCC_except_table3438
+ GCC_except_table3446
+ GCC_except_table3450
+ GCC_except_table3454
+ GCC_except_table3457
+ GCC_except_table3458
+ GCC_except_table3461
+ GCC_except_table3462
+ GCC_except_table3465
+ GCC_except_table3467
+ GCC_except_table3469
+ GCC_except_table3470
+ GCC_except_table3471
+ GCC_except_table3472
+ GCC_except_table3473
+ GCC_except_table3477
+ GCC_except_table3483
+ GCC_except_table4017
+ GCC_except_table4088
+ GCC_except_table4092
+ GCC_except_table4094
+ GCC_except_table4231
+ GCC_except_table4241
+ GCC_except_table4242
+ GCC_except_table4249
+ GCC_except_table4257
+ GCC_except_table4262
+ GCC_except_table4285
+ GCC_except_table4292
+ GCC_except_table4297
+ GCC_except_table4299
+ GCC_except_table4426
+ GCC_except_table4428
+ GCC_except_table4431
+ GCC_except_table4432
+ GCC_except_table4433
+ GCC_except_table4438
+ GCC_except_table4440
+ GCC_except_table4445
+ GCC_except_table4446
+ GCC_except_table4447
+ GCC_except_table4449
+ GCC_except_table4451
+ GCC_except_table4466
+ GCC_except_table4468
+ GCC_except_table4493
+ GCC_except_table4529
+ GCC_except_table4530
+ GCC_except_table4534
+ GCC_except_table4539
+ GCC_except_table4540
+ GCC_except_table4544
+ GCC_except_table4546
+ GCC_except_table4547
+ GCC_except_table4548
+ GCC_except_table4549
+ GCC_except_table4551
+ GCC_except_table4557
+ GCC_except_table4561
+ GCC_except_table4565
+ GCC_except_table4566
+ GCC_except_table4567
+ GCC_except_table4569
+ GCC_except_table4576
+ GCC_except_table4578
+ GCC_except_table4579
+ GCC_except_table4654
+ GCC_except_table4971
+ GCC_except_table5092
+ GCC_except_table5095
+ GCC_except_table5105
+ GCC_except_table5109
+ GCC_except_table5110
+ GCC_except_table5124
+ GCC_except_table5234
+ GCC_except_table5340
+ GCC_except_table5342
+ GCC_except_table5344
+ GCC_except_table5383
+ GCC_except_table5465
+ GCC_except_table5757
+ GCC_except_table5860
+ GCC_except_table5885
+ GCC_except_table5921
+ GCC_except_table5923
+ GCC_except_table5925
+ GCC_except_table5930
+ GCC_except_table5939
+ GCC_except_table5940
+ GCC_except_table5944
+ GCC_except_table5980
+ GCC_except_table5999
+ GCC_except_table6025
+ GCC_except_table6044
+ GCC_except_table6047
+ GCC_except_table6052
+ GCC_except_table6053
+ GCC_except_table6055
+ GCC_except_table6056
+ GCC_except_table6088
+ GCC_except_table6090
+ GCC_except_table6094
+ GCC_except_table6095
+ GCC_except_table6096
+ GCC_except_table6097
+ GCC_except_table6101
+ GCC_except_table6102
+ GCC_except_table6103
+ GCC_except_table6104
+ GCC_except_table6108
+ GCC_except_table6116
+ GCC_except_table6117
+ GCC_except_table6136
+ GCC_except_table6147
+ GCC_except_table6152
+ GCC_except_table6155
+ GCC_except_table6156
+ GCC_except_table6157
+ GCC_except_table6158
+ GCC_except_table6159
+ GCC_except_table6161
+ GCC_except_table6163
+ GCC_except_table6166
+ GCC_except_table6167
+ GCC_except_table6168
+ GCC_except_table6169
+ GCC_except_table6170
+ GCC_except_table6172
+ GCC_except_table6174
+ GCC_except_table6175
+ GCC_except_table6177
+ GCC_except_table6178
+ GCC_except_table6286
+ GCC_except_table6290
+ GCC_except_table6350
+ GCC_except_table6382
+ GCC_except_table6383
+ GCC_except_table6421
+ GCC_except_table6427
+ GCC_except_table6435
+ GCC_except_table6460
+ GCC_except_table6552
+ GCC_except_table6557
+ GCC_except_table6564
+ GCC_except_table6582
+ GCC_except_table6600
+ GCC_except_table6603
+ GCC_except_table6604
+ GCC_except_table6608
+ GCC_except_table6609
+ GCC_except_table6713
+ GCC_except_table6722
+ GCC_except_table6742
+ GCC_except_table6759
+ GCC_except_table6833
+ GCC_except_table6899
+ GCC_except_table6904
+ GCC_except_table6907
+ GCC_except_table6930
+ GCC_except_table6974
+ GCC_except_table7117
+ GCC_except_table7193
+ GCC_except_table7208
+ GCC_except_table7209
+ GCC_except_table7210
+ GCC_except_table7223
+ GCC_except_table7224
+ GCC_except_table7225
+ GCC_except_table7226
+ GCC_except_table7241
+ GCC_except_table7242
+ GCC_except_table7256
+ GCC_except_table7257
+ GCC_except_table7262
+ GCC_except_table7302
+ GCC_except_table7376
+ GCC_except_table7388
+ GCC_except_table7390
+ GCC_except_table7391
+ GCC_except_table7395
+ GCC_except_table7399
+ GCC_except_table7400
+ GCC_except_table7403
+ GCC_except_table7404
+ GCC_except_table7405
+ GCC_except_table7407
+ GCC_except_table7408
+ GCC_except_table7410
+ GCC_except_table7411
+ GCC_except_table7481
+ GCC_except_table7518
+ GCC_except_table7557
+ GCC_except_table7558
+ GCC_except_table7608
+ GCC_except_table8301
+ GCC_except_table8304
+ GCC_except_table8374
+ GCC_except_table8513
+ GCC_except_table8517
+ GCC_except_table8522
+ GCC_except_table8525
+ GCC_except_table8527
+ GCC_except_table8532
+ GCC_except_table8546
+ GCC_except_table8548
+ GCC_except_table8549
+ GCC_except_table8554
+ GCC_except_table8555
+ GCC_except_table8575
+ GCC_except_table8582
+ GCC_except_table8583
+ GCC_except_table8584
+ GCC_except_table8585
+ GCC_except_table8598
+ GCC_except_table8787
+ GCC_except_table8834
+ GCC_except_table9189
+ GCC_except_table9274
+ GCC_except_table9452
+ GCC_except_table9646
+ GCC_except_table9661
+ GCC_except_table9698
+ GCC_except_table9705
+ GCC_except_table9745
+ GCC_except_table9753
+ GCC_except_table9760
+ GCC_except_table9767
+ GCC_except_table9777
+ GCC_except_table9779
+ GCC_except_table9780
+ GCC_except_table9782
+ GCC_except_table9783
+ GCC_except_table9784
+ GCC_except_table9793
+ GCC_except_table9814
+ GCC_except_table9817
+ GCC_except_table9821
+ GCC_except_table9822
+ GCC_except_table9824
+ GCC_except_table9825
+ GCC_except_table9826
+ GCC_except_table9827
+ GCC_except_table9828
+ GCC_except_table9830
+ GCC_except_table9831
+ GCC_except_table9832
+ GCC_except_table9833
+ GCC_except_table9834
+ GCC_except_table9835
+ GCC_except_table9836
+ GCC_except_table9837
+ GCC_except_table9838
+ GCC_except_table9839
+ GCC_except_table9840
+ GCC_except_table9841
+ GCC_except_table9842
+ GCC_except_table9843
+ GCC_except_table9844
+ GCC_except_table9845
+ GCC_except_table9846
+ GCC_except_table9847
+ GCC_except_table9904
+ GCC_except_table9911
+ GCC_except_table9989
+ OBJC_IVAR_$_NUChannelOptionalFormat._wrappedFormat
+ OBJC_IVAR_$__NUHDRColorVolumePipeline._filterProcessor
+ OBJC_IVAR_$__NUHDRGainMapApplyPipeline._filterProcessor
+ OBJC_IVAR_$__NUHDRGainMapComputePipeline._filterProcessor
+ OBJC_IVAR_$__NUMapPipeline._arrayChannel
+ OBJC_IVAR_$__NUMapPipeline._elementInputPort
+ OBJC_IVAR_$__NUReducePipeline._accumulatorChannel
+ OBJC_IVAR_$__NUReducePipeline._accumulatorInputPort
+ OBJC_IVAR_$__NUReducePipeline._accumulatorOutputPort
+ OBJC_IVAR_$__NUReducePipeline._arrayChannel
+ OBJC_IVAR_$__NUReducePipeline._elementInputPort
+ _OBJC_CLASS_$_NUChannelOptionalFormat
+ _OBJC_METACLASS_$_NUChannelOptionalFormat
+ __OBJC_$_INSTANCE_METHODS_NUChannelOptionalFormat
+ __OBJC_$_INSTANCE_VARIABLES_NUChannelOptionalFormat
+ __OBJC_$_INSTANCE_VARIABLES__NUHDRColorVolumePipeline
+ __OBJC_$_INSTANCE_VARIABLES__NUHDRGainMapApplyPipeline
+ __OBJC_$_INSTANCE_VARIABLES__NUMapPipeline
+ __OBJC_$_INSTANCE_VARIABLES__NUReducePipeline
+ __OBJC_$_PROP_LIST_NUChannelOptionalFormat
+ __OBJC_$_PROP_LIST__NUMapPipeline
+ __OBJC_$_PROP_LIST__NUReducePipeline
+ __OBJC_CLASS_PROTOCOLS_$_NUPipelineProcessor
+ __OBJC_CLASS_RO_$_NUChannelOptionalFormat
+ __OBJC_METACLASS_RO_$_NUChannelOptionalFormat
+ ___64+[NUPipelineProcessor processorWithName:bundleIdentifier:error:]_block_invoke
+ ___82-[NUPipelineProcessorCache processorForConfiguration:processor:controlData:error:]_block_invoke
+ _objc_msgSend$accumulatorInputPort
+ _objc_msgSend$accumulatorOutputPort
+ _objc_msgSend$addElementOutputChannel:
+ _objc_msgSend$addPipelineWithBuilder:error:
+ _objc_msgSend$canAcceptDataWithNonOptionalDescriptor:
+ _objc_msgSend$elementInputPort
+ _objc_msgSend$initWithArrayChannel:
+ _objc_msgSend$initWithArrayChannel:accumulatorChannel:
+ _objc_msgSend$initWithDescriptor:validatedDefaultValue:
+ _objc_msgSend$initWithWrappedFormat:
+ _objc_msgSend$isEqualToOptionalFormat:
+ _objc_msgSend$nonOptionalDescriptor
+ _objc_msgSend$nonOptionalFormat
+ _objc_msgSend$processorForConfiguration:processor:controlData:error:
+ _objc_msgSend$processorWithName:bundleIdentifier:error:
+ _objc_msgSend$wrappedFormat
- +[NUPipelineFactory computePipelineWithProcessorIdentifier:error:]
- +[NUPipelineFactory metadataPipelineWithProcessorIdentifier:error:]
- +[NUPipelineFactory renderPipelineWithProcessorIdentifier:error:]
- +[NUPipelineProcessor identifier]
- +[NUPipelineProcessor processorWithIdentifier:error:]
- -[NUArrayDescriptor canAcceptDataWithDescriptor:]
- -[NUCompoundDescriptor canAcceptDataWithDescriptor:]
- -[NUCoreImageFilterPipelineProcessor identifier]
- -[NUEnumDescriptor canAcceptDataWithDescriptor:]
- -[NUNumberDescriptor canAcceptDataWithDescriptor:]
- -[NUPipelineProcessor identifier]
- -[NUPipelineProcessorCache processorForConfiguration:identifier:controlData:error:]
- -[NUVectorDescriptor canAcceptDataWithDescriptor:]
- -[_NUMapPipeline _addInputChannel:]
- -[_NUMapPipeline _addOutputChannel:]
- -[_NUMapPipeline init]
- -[_NUPipeline addMapPipeline:error:]
- -[_NUPipeline addReducePipeline:error:]
- -[_NUReducePipeline _addInputChannel:]
- -[_NUReducePipeline init]
- GCC_except_table10001
- GCC_except_table10025
- GCC_except_table10026
- GCC_except_table10030
- GCC_except_table10031
- GCC_except_table10032
- GCC_except_table10033
- GCC_except_table10040
- GCC_except_table10041
- GCC_except_table10050
- GCC_except_table10060
- GCC_except_table10070
- GCC_except_table10072
- GCC_except_table10075
- GCC_except_table10149
- GCC_except_table10159
- GCC_except_table10374
- GCC_except_table10375
- GCC_except_table10381
- GCC_except_table10382
- GCC_except_table10384
- GCC_except_table10385
- GCC_except_table10482
- GCC_except_table10483
- GCC_except_table10486
- GCC_except_table10487
- GCC_except_table10488
- GCC_except_table10489
- GCC_except_table10490
- GCC_except_table10491
- GCC_except_table10493
- GCC_except_table10496
- GCC_except_table10497
- GCC_except_table10499
- GCC_except_table10500
- GCC_except_table10501
- GCC_except_table10503
- GCC_except_table10504
- GCC_except_table10514
- GCC_except_table10515
- GCC_except_table10520
- GCC_except_table10521
- GCC_except_table10528
- GCC_except_table10530
- GCC_except_table10531
- GCC_except_table10534
- GCC_except_table10538
- GCC_except_table10541
- GCC_except_table10542
- GCC_except_table10545
- GCC_except_table10548
- GCC_except_table10549
- GCC_except_table10560
- GCC_except_table10573
- GCC_except_table10575
- GCC_except_table10576
- GCC_except_table10579
- GCC_except_table10580
- GCC_except_table10582
- GCC_except_table10583
- GCC_except_table10586
- GCC_except_table10591
- GCC_except_table10592
- GCC_except_table10654
- GCC_except_table10705
- GCC_except_table10794
- GCC_except_table10798
- GCC_except_table11296
- GCC_except_table11457
- GCC_except_table11459
- GCC_except_table11505
- GCC_except_table11559
- GCC_except_table11567
- GCC_except_table11574
- GCC_except_table11575
- GCC_except_table11579
- GCC_except_table2166
- GCC_except_table2814
- GCC_except_table2880
- GCC_except_table2930
- GCC_except_table2942
- GCC_except_table3102
- GCC_except_table3249
- GCC_except_table3329
- GCC_except_table3336
- GCC_except_table3337
- GCC_except_table3340
- GCC_except_table3341
- GCC_except_table3342
- GCC_except_table3345
- GCC_except_table3346
- GCC_except_table3349
- GCC_except_table3352
- GCC_except_table3353
- GCC_except_table3360
- GCC_except_table3361
- GCC_except_table3362
- GCC_except_table3363
- GCC_except_table3366
- GCC_except_table3367
- GCC_except_table3375
- GCC_except_table3386
- GCC_except_table3410
- GCC_except_table3415
- GCC_except_table3416
- GCC_except_table3418
- GCC_except_table3422
- GCC_except_table3426
- GCC_except_table3429
- GCC_except_table3430
- GCC_except_table3433
- GCC_except_table3434
- GCC_except_table3439
- GCC_except_table3441
- GCC_except_table3442
- GCC_except_table3445
- GCC_except_table3455
- GCC_except_table3808
- GCC_except_table3995
- GCC_except_table4064
- GCC_except_table4068
- GCC_except_table4070
- GCC_except_table4207
- GCC_except_table4217
- GCC_except_table4218
- GCC_except_table4225
- GCC_except_table4233
- GCC_except_table4238
- GCC_except_table4261
- GCC_except_table4268
- GCC_except_table4273
- GCC_except_table4275
- GCC_except_table4402
- GCC_except_table4403
- GCC_except_table4404
- GCC_except_table4407
- GCC_except_table4408
- GCC_except_table4409
- GCC_except_table4414
- GCC_except_table4416
- GCC_except_table4421
- GCC_except_table4422
- GCC_except_table4423
- GCC_except_table4425
- GCC_except_table4442
- GCC_except_table4444
- GCC_except_table4469
- GCC_except_table4505
- GCC_except_table4506
- GCC_except_table4509
- GCC_except_table4510
- GCC_except_table4515
- GCC_except_table4516
- GCC_except_table4519
- GCC_except_table4520
- GCC_except_table4521
- GCC_except_table4522
- GCC_except_table4523
- GCC_except_table4524
- GCC_except_table4525
- GCC_except_table4527
- GCC_except_table4537
- GCC_except_table4541
- GCC_except_table4542
- GCC_except_table4552
- GCC_except_table4554
- GCC_except_table4555
- GCC_except_table4630
- GCC_except_table4947
- GCC_except_table5062
- GCC_except_table5068
- GCC_except_table5071
- GCC_except_table5081
- GCC_except_table5085
- GCC_except_table5100
- GCC_except_table5210
- GCC_except_table5316
- GCC_except_table5318
- GCC_except_table5320
- GCC_except_table5359
- GCC_except_table5441
- GCC_except_table5733
- GCC_except_table5836
- GCC_except_table5861
- GCC_except_table5897
- GCC_except_table5899
- GCC_except_table5901
- GCC_except_table5906
- GCC_except_table5915
- GCC_except_table5916
- GCC_except_table5920
- GCC_except_table5956
- GCC_except_table5975
- GCC_except_table5996
- GCC_except_table6001
- GCC_except_table6022
- GCC_except_table6023
- GCC_except_table6028
- GCC_except_table6029
- GCC_except_table6031
- GCC_except_table6032
- GCC_except_table6059
- GCC_except_table6062
- GCC_except_table6063
- GCC_except_table6064
- GCC_except_table6066
- GCC_except_table6069
- GCC_except_table6071
- GCC_except_table6072
- GCC_except_table6073
- GCC_except_table6075
- GCC_except_table6076
- GCC_except_table6077
- GCC_except_table6078
- GCC_except_table6079
- GCC_except_table6080
- GCC_except_table6081
- GCC_except_table6082
- GCC_except_table6084
- GCC_except_table6085
- GCC_except_table6092
- GCC_except_table6112
- GCC_except_table6113
- GCC_except_table6118
- GCC_except_table6119
- GCC_except_table6120
- GCC_except_table6121
- GCC_except_table6128
- GCC_except_table6132
- GCC_except_table6139
- GCC_except_table6146
- GCC_except_table6150
- GCC_except_table6151
- GCC_except_table6262
- GCC_except_table6266
- GCC_except_table6326
- GCC_except_table6358
- GCC_except_table6359
- GCC_except_table6397
- GCC_except_table6403
- GCC_except_table6411
- GCC_except_table6436
- GCC_except_table6516
- GCC_except_table6528
- GCC_except_table6533
- GCC_except_table6558
- GCC_except_table6576
- GCC_except_table6579
- GCC_except_table6580
- GCC_except_table6584
- GCC_except_table6585
- GCC_except_table6689
- GCC_except_table6698
- GCC_except_table6718
- GCC_except_table6735
- GCC_except_table6809
- GCC_except_table6875
- GCC_except_table6880
- GCC_except_table6883
- GCC_except_table6906
- GCC_except_table6950
- GCC_except_table7093
- GCC_except_table7168
- GCC_except_table7183
- GCC_except_table7184
- GCC_except_table7185
- GCC_except_table7198
- GCC_except_table7199
- GCC_except_table7200
- GCC_except_table7201
- GCC_except_table7216
- GCC_except_table7217
- GCC_except_table7231
- GCC_except_table7232
- GCC_except_table7237
- GCC_except_table7277
- GCC_except_table7350
- GCC_except_table7351
- GCC_except_table7355
- GCC_except_table7357
- GCC_except_table7361
- GCC_except_table7363
- GCC_except_table7365
- GCC_except_table7366
- GCC_except_table7370
- GCC_except_table7374
- GCC_except_table7378
- GCC_except_table7379
- GCC_except_table7383
- GCC_except_table7385
- GCC_except_table7456
- GCC_except_table7493
- GCC_except_table7532
- GCC_except_table7533
- GCC_except_table7583
- GCC_except_table8276
- GCC_except_table8279
- GCC_except_table8349
- GCC_except_table8488
- GCC_except_table8492
- GCC_except_table8497
- GCC_except_table8500
- GCC_except_table8502
- GCC_except_table8507
- GCC_except_table8521
- GCC_except_table8523
- GCC_except_table8524
- GCC_except_table8529
- GCC_except_table8530
- GCC_except_table8550
- GCC_except_table8557
- GCC_except_table8558
- GCC_except_table8559
- GCC_except_table8560
- GCC_except_table8573
- GCC_except_table8761
- GCC_except_table8808
- GCC_except_table9153
- GCC_except_table9238
- GCC_except_table9416
- GCC_except_table9610
- GCC_except_table9625
- GCC_except_table9662
- GCC_except_table9669
- GCC_except_table9709
- GCC_except_table9710
- GCC_except_table9711
- GCC_except_table9712
- GCC_except_table9717
- GCC_except_table9723
- GCC_except_table9724
- GCC_except_table9731
- GCC_except_table9734
- GCC_except_table9741
- GCC_except_table9743
- GCC_except_table9744
- GCC_except_table9749
- GCC_except_table9754
- GCC_except_table9756
- GCC_except_table9757
- GCC_except_table9758
- GCC_except_table9763
- GCC_except_table9764
- GCC_except_table9766
- GCC_except_table9768
- GCC_except_table9772
- GCC_except_table9778
- GCC_except_table9781
- GCC_except_table9786
- GCC_except_table9788
- GCC_except_table9789
- GCC_except_table9791
- GCC_except_table9796
- GCC_except_table9797
- GCC_except_table9798
- GCC_except_table9801
- GCC_except_table9803
- GCC_except_table9805
- GCC_except_table9807
- GCC_except_table9809
- GCC_except_table9810
- GCC_except_table9811
- GCC_except_table9868
- GCC_except_table9875
- GCC_except_table9953
- _OUTLINED_FUNCTION_25
- _OUTLINED_FUNCTION_26
- _OUTLINED_FUNCTION_27
- _OUTLINED_FUNCTION_28
- ___31-[_NUPipeline map:block:error:]_block_invoke
- ___39-[_NUPipeline reduce:with:block:error:]_block_invoke
- ___53+[NUPipelineProcessor processorWithIdentifier:error:]_block_invoke
- ___83-[NUPipelineProcessorCache processorForConfiguration:identifier:controlData:error:]_block_invoke
- ___block_descriptor_56_e8_32s40bs48r_e25_B24?0"_NUPipeline"8^16l
- ___block_descriptor_56_e8_32s40s48bs_e25_B24?0"_NUPipeline"8^16l
- _objc_msgSend$addMapPipeline:error:
- _objc_msgSend$addReducePipeline:error:
- _objc_msgSend$arrayChannel:
- _objc_msgSend$processorForConfiguration:identifier:controlData:error:
- _objc_msgSend$processorWithIdentifier:error:
CStrings:
+ "+[NUPipelineFactory buildPipelineWithBuilder:]"
+ "+[NUPipelineFactory colorVolumePipeline]"
+ "+[NUPipelineFactory computePipelineWithProcessorName:bundleIdentifier:error:]"
+ "+[NUPipelineFactory gainMapComputePipelineWithOptions:]"
+ "+[NUPipelineFactory metadataPipelineWithProcessorName:bundleIdentifier:error:]"
+ "+[NUPipelineFactory renderPipelineWithProcessorName:bundleIdentifier:error:]"
+ "+[NUPipelineProcessor processorWithName:bundleIdentifier:error:]"
+ "-[NUChannelOptionalFormat canAcceptDataWithFormat:]"
+ "-[NUChannelOptionalFormat initWithWrappedFormat:]"
+ "-[NUChannelOptionalFormat init]"
+ "-[NUControlDescriptor canAcceptDataWithDescriptor:]"
+ "-[NUOptionalDescriptor canAcceptDataWithDescriptor:]"
+ "-[NUOptionalDescriptor initWithDescriptor:validatedDefaultValue:]"
+ "-[NUPipelineProcessorCache processorForConfiguration:processor:controlData:error:]"
+ "-[_NUMapPipeline addElementOutputChannel:]"
+ "-[_NUMapPipeline initWithArrayChannel:]"
+ "-[_NUPipeline addPipelineWithBuilder:]"
+ "-[_NUReducePipeline initWithArrayChannel:accumulatorChannel:]"
+ "<%@:%p optional:%@>"
+ "Duplicate input name: %@"
+ "Failed to build colorVolumePipeline: %@"
+ "Failed to build gainMapComputePipeline: %@"
+ "Failed to build pipeline"
+ "Failed to copy the processor instance"
+ "Failed to look up metadata processor by name"
+ "Failed to look up processor by name"
+ "Invalid default value: %@, error: %@"
+ "accumulatorChannel != nil"
+ "arrayChannel != nil"
+ "arrayChannel.format.isArray"
+ "elementChannel != nil"
+ "initialInput != nil"
- "+[NUPipelineFactory computePipelineWithProcessorIdentifier:error:]"
- "+[NUPipelineFactory metadataPipelineWithProcessorIdentifier:error:]"
- "+[NUPipelineFactory renderPipelineWithProcessorIdentifier:error:]"
- "+[NUPipelineProcessor processorWithIdentifier:error:]"
- "-[NUPipelineProcessorCache processorForConfiguration:identifier:controlData:error:]"
- "Cardinality mismatch"
- "Failed to create the processor instance"
- "Failed to look up metadata processor by identifier"
- "Failed to look up processor by identifier"
- "Initial value should not be an array"
- "Missing input (initial value) channel for output channel"
- "Nothing to map"
- "Nothing to reduce"
- "channel"
- "com.apple.coreimage"
- "com.apple.neutrino.main"
```
