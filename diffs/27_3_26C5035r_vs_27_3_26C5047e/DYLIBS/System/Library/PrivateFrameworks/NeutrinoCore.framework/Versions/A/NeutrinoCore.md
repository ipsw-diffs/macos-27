## NeutrinoCore

> `/System/Library/PrivateFrameworks/NeutrinoCore.framework/Versions/A/NeutrinoCore`

```diff

-920.8.100.0.0
-  __TEXT.__text: 0x35c778
-  __TEXT.__objc_methlist: 0x21dcc
+920.12.210.0.0
+  __TEXT.__text: 0x3621f4
+  __TEXT.__objc_methlist: 0x2221c
   __TEXT.__const: 0x2990
   __TEXT.__dlopen_cstrs: 0x45
   __TEXT.__constg_swiftt: 0x178

   __TEXT.__swift5_assocty: 0xc0
   __TEXT.__swift5_proto: 0x84
   __TEXT.__swift5_types: 0x2c
-  __TEXT.__cstring: 0x41e1e
+  __TEXT.__cstring: 0x42172
   __TEXT.__swift5_capture: 0x390
   __TEXT.__gcc_except_tab: 0x825c
-  __TEXT.__oslogstring: 0x598d
+  __TEXT.__oslogstring: 0x59c3
   __TEXT.__ustring: 0x3e
-  __TEXT.__unwind_info: 0xa850
+  __TEXT.__unwind_info: 0xa978
   __TEXT.__eh_frame: 0x6c0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x16b0
+  __DATA_CONST.__const: 0x16f0
   __DATA_CONST.__objc_classlist: 0x1640
   __DATA_CONST.__objc_catlist: 0xa8
-  __DATA_CONST.__objc_protolist: 0x4e8
+  __DATA_CONST.__objc_protolist: 0x4f0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0xba00
+  __DATA_CONST.__objc_selrefs: 0xbad8
   __DATA_CONST.__objc_protorefs: 0x60
-  __DATA_CONST.__objc_superrefs: 0x1040
+  __DATA_CONST.__objc_superrefs: 0x1048
   __DATA_CONST.__objc_arraydata: 0xb10
   __DATA_CONST.__got: 0x2328
-  __AUTH_CONST.__const: 0x8978
-  __AUTH_CONST.__cfstring: 0x1dc00
-  __AUTH_CONST.__objc_const: 0x38640
+  __AUTH_CONST.__const: 0x8998
+  __AUTH_CONST.__cfstring: 0x1de60
+  __AUTH_CONST.__objc_const: 0x38820
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_dictobj: 0x348
   __AUTH_CONST.__objc_intobj: 0x990

   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__objc_floatobj: 0x50
   __AUTH_CONST.__auth_got: 0xfe0
-  __AUTH.__objc_data: 0x320
-  __DATA.__objc_ivar: 0x1ad0
-  __DATA.__data: 0x2f0
+  __AUTH.__objc_data: 0x370
+  __DATA.__objc_ivar: 0x1ae0
+  __DATA.__data: 0x350
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x1410
-  __DATA_DIRTY.__objc_data: 0xdb60
+  __DATA_DIRTY.__objc_data: 0xdb10
   __DATA_DIRTY.__data: 0x3780
   __DATA_DIRTY.__bss: 0x158
   __DATA_DIRTY.__common: 0x40

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12390
-  Symbols:   26231
-  CStrings:  7473
+  Functions: 12479
+  Symbols:   26359
+  CStrings:  7499
 
Symbols:
+ +[NUChannelPortRef parseLocation:pipelinePath:portMatching:isInput:isConnectedInput:isUnwrapped:error:]
+ +[NUPipelineFactory selectorPipelineWithFormat:]
+ +[_NUMediaGeometry geometryDescriptor]
+ +[_NUMediaGeometry geometryIdentifier]
+ -[NSNull(NUControlDataRepresentable) nu_subdataForKey:format:error:]
+ -[NSObject(NUControlDataRepresentable) nu_checkDigestibility:]
+ -[NUArrayDescriptor hash]
+ -[NUChannel nonOptionalChannel]
+ -[NUChannel optionalChannel]
+ -[NUChannel unwrappedSubchannel]
+ -[NUChannelConstantExpression nu_checkDigestibility:]
+ -[NUChannelContainerMediaFormat componentsDescription]
+ -[NUChannelControlData dataWithFormat:error:]
+ -[NUChannelControlFormat unwrappedChannel]
+ -[NUChannelData checkDigestibility:]
+ -[NUChannelData dataWithFormat:error:]
+ -[NUChannelData nu_updateDigest:]
+ -[NUChannelElementFormat nonOptionalFormat]
+ -[NUChannelElementFormat optionalFormat]
+ -[NUChannelExpression nu_checkDigestibility:]
+ -[NUChannelForceUnwrapExpression subexpressionForKey:]
+ -[NUChannelFormat compactDescription]
+ -[NUChannelFormat unwrappedChannel]
+ -[NUChannelMediaData dataWithFormat:error:]
+ -[NUChannelNilCoalesceExpression subexpressionForKey:]
+ -[NUChannelOptionalFormat unwrappedChannel]
+ -[NUChannelPortRef isUnwrapped]
+ -[NUChannelPortRef unwrappedRef]
+ -[NUChannelStaticExpression nu_checkDigestibility:]
+ -[NUChannelUnwrappedFormat .cxx_destruct]
+ -[NUChannelUnwrappedFormat arrayItemFormat]
+ -[NUChannelUnwrappedFormat canAcceptDataWithFormat:]
+ -[NUChannelUnwrappedFormat canSpecializeFormat:]
+ -[NUChannelUnwrappedFormat channelType]
+ -[NUChannelUnwrappedFormat compactDescription]
+ -[NUChannelUnwrappedFormat debugDescription]
+ -[NUChannelUnwrappedFormat description]
+ -[NUChannelUnwrappedFormat elementChannel]
+ -[NUChannelUnwrappedFormat genericFormat]
+ -[NUChannelUnwrappedFormat hash]
+ -[NUChannelUnwrappedFormat initWithOptionalFormat:]
+ -[NUChannelUnwrappedFormat init]
+ -[NUChannelUnwrappedFormat isArray]
+ -[NUChannelUnwrappedFormat isComparableToChannelFormat:]
+ -[NUChannelUnwrappedFormat isComputedData]
+ -[NUChannelUnwrappedFormat isEqualToChannelFormat:]
+ -[NUChannelUnwrappedFormat isEqualToUnwrappedFormat:]
+ -[NUChannelUnwrappedFormat isGeneric]
+ -[NUChannelUnwrappedFormat isOptional]
+ -[NUChannelUnwrappedFormat nonOptionalFormat]
+ -[NUChannelUnwrappedFormat optionalFormat]
+ -[NUChannelUnwrappedFormat specializedWithFormat:]
+ -[NUChannelUnwrappedFormat subchannelFormatForKey:]
+ -[NUChannelUnwrappedFormat subchannelKeys]
+ -[NUCompoundDescriptor hash]
+ -[NUCompoundDescriptor initWithProperties:identifier:buildable:]
+ -[NUCompoundDescriptor initWithProperties:identifier:valueType:buildable:]
+ -[NUCompoundDescriptor isBuildable]
+ -[NUCompoundDescriptor subdescriptorForKey:]
+ -[NUCompoundDescriptor subvalueForKey:value:]
+ -[NUControlDescriptor subdescriptorForKey:]
+ -[NUControlDescriptor subvalueForKey:value:]
+ -[NUEnumDescriptor hash]
+ -[NUGlobalSettings rendererContextUseMemoryLimit]
+ -[NUGlobalSettings setRendererContextUseMemoryLimit:]
+ -[NULivePhotoExportRequest setVideoOutputSettings:]
+ -[NULivePhotoExportRequest videoOutputSettings]
+ -[NUNumberDescriptor hash]
+ -[NUOpaqueDescriptor hash]
+ -[NUOptionalDescriptor availability]
+ -[NUOptionalDescriptor hash]
+ -[NUOptionalDescriptor initWithDescriptor:availability:validatedDefaultValue:]
+ -[NUOptionalDescriptor subdescriptorForKey:]
+ -[NUOptionalDescriptor subvalueForKey:value:]
+ -[NURectDescriptor hash]
+ -[NURectDescriptor subdescriptorForKey:]
+ -[NUTimeDescriptor hash]
+ -[NUVectorDescriptor hash]
+ -[_NUAssetPipeline assetMediaWithOriginalStyle:]
+ -[_NUAssetPipeline containerMediaWithOriginalStyle:error:]
+ -[_NUAssetPipeline primaryMediaWithOriginalStyle:deltaMedia:metadataMedia:revertToOriginalStyle:error:]
+ -[_NUAuxiliaryMetadata formatIdentifier]
+ -[_NUAuxiliaryMetadata metadataWithIdentifier:]
+ -[_NUAuxiliaryMetadata nu_updateDigest:]
+ -[_NUCachedComputedMedia mediaWithFormat:error:]
+ -[_NUCachedMedia initWithBaseMedia:cacheNode:format:]
+ -[_NUChannelPort _elementSubportWithChannel:]
+ -[_NUChannelPort isUnwrapped]
+ -[_NUChannelPort nonOptionalElementSubport]
+ -[_NUChannelPort optionalElementSubport]
+ -[_NUChannelPort unwrappedSubport]
+ -[_NUCompositeMedia mediaWithFormat:error:]
+ -[_NUComputedMedia mediaWithFormat:error:]
+ -[_NUCropPipeline _genericInputPortsMatchingOutputPort:]
+ -[_NUCropPipeline _genericOutputPortsMatchingInputPort:]
+ -[_NUHDRColorVolumePipeline _genericInputPortsMatchingOutputPort:]
+ -[_NUHDRColorVolumePipeline _genericOutputPortsMatchingInputPort:]
+ -[_NUHDRGainMapComputePipeline _genericInputPortsMatchingOutputPort:]
+ -[_NUHDRGainMapComputePipeline _genericOutputPortsMatchingInputPort:]
+ -[_NUHDRToneMapApplyPipeline _genericInputPortsMatchingOutputPort:]
+ -[_NUHDRToneMapApplyPipeline _genericOutputPortsMatchingInputPort:]
+ -[_NUImageMetadata formatIdentifier]
+ -[_NUImageMetadata metadataWithIdentifier:]
+ -[_NUImageMetadata nu_updateDigest:]
+ -[_NUMedia mediaWithFormat:error:]
+ -[_NUMediaGeometry valueForKey:]
+ -[_NUOrientationPipeline _genericInputPortsMatchingOutputPort:]
+ -[_NUOrientationPipeline _genericOutputPortsMatchingInputPort:]
+ -[_NURenderMedia mediaWithFormat:error:]
+ -[_NUVideoMetadata formatIdentifier]
+ -[_NUVideoMetadata metadataWithIdentifier:]
+ -[_NUVideoMetadata nu_updateDigest:]
+ GCC_except_table10099
+ GCC_except_table10161
+ GCC_except_table10168
+ GCC_except_table10173
+ GCC_except_table10175
+ GCC_except_table10293
+ GCC_except_table10534
+ GCC_except_table10541
+ GCC_except_table10751
+ GCC_except_table10789
+ GCC_except_table10793
+ GCC_except_table1087
+ GCC_except_table11013
+ GCC_except_table11293
+ GCC_except_table11296
+ GCC_except_table11453
+ GCC_except_table11463
+ GCC_except_table11464
+ GCC_except_table11471
+ GCC_except_table11476
+ GCC_except_table11481
+ GCC_except_table11501
+ GCC_except_table11508
+ GCC_except_table11509
+ GCC_except_table11510
+ GCC_except_table11511
+ GCC_except_table1160
+ GCC_except_table11714
+ GCC_except_table11726
+ GCC_except_table11731
+ GCC_except_table11738
+ GCC_except_table11756
+ GCC_except_table11774
+ GCC_except_table11777
+ GCC_except_table11778
+ GCC_except_table11782
+ GCC_except_table11783
+ GCC_except_table11893
+ GCC_except_table11918
+ GCC_except_table11920
+ GCC_except_table12016
+ GCC_except_table12018
+ GCC_except_table12020
+ GCC_except_table12025
+ GCC_except_table12034
+ GCC_except_table12035
+ GCC_except_table1323
+ GCC_except_table2076
+ GCC_except_table2191
+ GCC_except_table2411
+ GCC_except_table2562
+ GCC_except_table2578
+ GCC_except_table2592
+ GCC_except_table2617
+ GCC_except_table2640
+ GCC_except_table2643
+ GCC_except_table2648
+ GCC_except_table2649
+ GCC_except_table2651
+ GCC_except_table2663
+ GCC_except_table2667
+ GCC_except_table2669
+ GCC_except_table2689
+ GCC_except_table2694
+ GCC_except_table2699
+ GCC_except_table2702
+ GCC_except_table2704
+ GCC_except_table2709
+ GCC_except_table2723
+ GCC_except_table2725
+ GCC_except_table2726
+ GCC_except_table2731
+ GCC_except_table2732
+ GCC_except_table2744
+ GCC_except_table2977
+ GCC_except_table2978
+ GCC_except_table2979
+ GCC_except_table2980
+ GCC_except_table2981
+ GCC_except_table2983
+ GCC_except_table2985
+ GCC_except_table3000
+ GCC_except_table3015
+ GCC_except_table3016
+ GCC_except_table3017
+ GCC_except_table3018
+ GCC_except_table3033
+ GCC_except_table3034
+ GCC_except_table3048
+ GCC_except_table3049
+ GCC_except_table3054
+ GCC_except_table3094
+ GCC_except_table3912
+ GCC_except_table3917
+ GCC_except_table3918
+ GCC_except_table3919
+ GCC_except_table3926
+ GCC_except_table3927
+ GCC_except_table3936
+ GCC_except_table3946
+ GCC_except_table3952
+ GCC_except_table3953
+ GCC_except_table3956
+ GCC_except_table3958
+ GCC_except_table3961
+ GCC_except_table3962
+ GCC_except_table3963
+ GCC_except_table3979
+ GCC_except_table3981
+ GCC_except_table4001
+ GCC_except_table4053
+ GCC_except_table4057
+ GCC_except_table4085
+ GCC_except_table4204
+ GCC_except_table4288
+ GCC_except_table4294
+ GCC_except_table4302
+ GCC_except_table4385
+ GCC_except_table4386
+ GCC_except_table4393
+ GCC_except_table4396
+ GCC_except_table4397
+ GCC_except_table4401
+ GCC_except_table4404
+ GCC_except_table4414
+ GCC_except_table4422
+ GCC_except_table4428
+ GCC_except_table4429
+ GCC_except_table4431
+ GCC_except_table4437
+ GCC_except_table4446
+ GCC_except_table4447
+ GCC_except_table4462
+ GCC_except_table4463
+ GCC_except_table4464
+ GCC_except_table4466
+ GCC_except_table4467
+ GCC_except_table4468
+ GCC_except_table4470
+ GCC_except_table4472
+ GCC_except_table4473
+ GCC_except_table4474
+ GCC_except_table4479
+ GCC_except_table4480
+ GCC_except_table4481
+ GCC_except_table4482
+ GCC_except_table4483
+ GCC_except_table4485
+ GCC_except_table4486
+ GCC_except_table4487
+ GCC_except_table4488
+ GCC_except_table4489
+ GCC_except_table4490
+ GCC_except_table4491
+ GCC_except_table4492
+ GCC_except_table4497
+ GCC_except_table4498
+ GCC_except_table4499
+ GCC_except_table4500
+ GCC_except_table4501
+ GCC_except_table4502
+ GCC_except_table4556
+ GCC_except_table4579
+ GCC_except_table4583
+ GCC_except_table4584
+ GCC_except_table4589
+ GCC_except_table4590
+ GCC_except_table4593
+ GCC_except_table4594
+ GCC_except_table4595
+ GCC_except_table4596
+ GCC_except_table4597
+ GCC_except_table4598
+ GCC_except_table4599
+ GCC_except_table4601
+ GCC_except_table4607
+ GCC_except_table4611
+ GCC_except_table4615
+ GCC_except_table4616
+ GCC_except_table4617
+ GCC_except_table4619
+ GCC_except_table4626
+ GCC_except_table4628
+ GCC_except_table4629
+ GCC_except_table4680
+ GCC_except_table4681
+ GCC_except_table4879
+ GCC_except_table4958
+ GCC_except_table4959
+ GCC_except_table4963
+ GCC_except_table4965
+ GCC_except_table4969
+ GCC_except_table4971
+ GCC_except_table4973
+ GCC_except_table4974
+ GCC_except_table4978
+ GCC_except_table4983
+ GCC_except_table4984
+ GCC_except_table4988
+ GCC_except_table5035
+ GCC_except_table5037
+ GCC_except_table5038
+ GCC_except_table5046
+ GCC_except_table5047
+ GCC_except_table5048
+ GCC_except_table5061
+ GCC_except_table5062
+ GCC_except_table5068
+ GCC_except_table5075
+ GCC_except_table5076
+ GCC_except_table5078
+ GCC_except_table5079
+ GCC_except_table5080
+ GCC_except_table5081
+ GCC_except_table5087
+ GCC_except_table5088
+ GCC_except_table5089
+ GCC_except_table5090
+ GCC_except_table5092
+ GCC_except_table5093
+ GCC_except_table5097
+ GCC_except_table5098
+ GCC_except_table5099
+ GCC_except_table5100
+ GCC_except_table5101
+ GCC_except_table5102
+ GCC_except_table5103
+ GCC_except_table5104
+ GCC_except_table5106
+ GCC_except_table5108
+ GCC_except_table5111
+ GCC_except_table5112
+ GCC_except_table5113
+ GCC_except_table5114
+ GCC_except_table5115
+ GCC_except_table5117
+ GCC_except_table5119
+ GCC_except_table5120
+ GCC_except_table5121
+ GCC_except_table5122
+ GCC_except_table5130
+ GCC_except_table5224
+ GCC_except_table5315
+ GCC_except_table5555
+ GCC_except_table5570
+ GCC_except_table5582
+ GCC_except_table5606
+ GCC_except_table5618
+ GCC_except_table5623
+ GCC_except_table5714
+ GCC_except_table5717
+ GCC_except_table5726
+ GCC_except_table5751
+ GCC_except_table5817
+ GCC_except_table5825
+ GCC_except_table5840
+ GCC_except_table5948
+ GCC_except_table5955
+ GCC_except_table5956
+ GCC_except_table5957
+ GCC_except_table5958
+ GCC_except_table5963
+ GCC_except_table5969
+ GCC_except_table5972
+ GCC_except_table5975
+ GCC_except_table5978
+ GCC_except_table5979
+ GCC_except_table5981
+ GCC_except_table5993
+ GCC_except_table6005
+ GCC_except_table6021
+ GCC_except_table6022
+ GCC_except_table6027
+ GCC_except_table6028
+ GCC_except_table6030
+ GCC_except_table6033
+ GCC_except_table6034
+ GCC_except_table6038
+ GCC_except_table6041
+ GCC_except_table6042
+ GCC_except_table6044
+ GCC_except_table6045
+ GCC_except_table6048
+ GCC_except_table6050
+ GCC_except_table6052
+ GCC_except_table6053
+ GCC_except_table6054
+ GCC_except_table6055
+ GCC_except_table6056
+ GCC_except_table6060
+ GCC_except_table6066
+ GCC_except_table6269
+ GCC_except_table6864
+ GCC_except_table7177
+ GCC_except_table7185
+ GCC_except_table7192
+ GCC_except_table7193
+ GCC_except_table7197
+ GCC_except_table7268
+ GCC_except_table7297
+ GCC_except_table7303
+ GCC_except_table7318
+ GCC_except_table7373
+ GCC_except_table7441
+ GCC_except_table7451
+ GCC_except_table7478
+ GCC_except_table7479
+ GCC_except_table7529
+ GCC_except_table7696
+ GCC_except_table7732
+ GCC_except_table7741
+ GCC_except_table7764
+ GCC_except_table7770
+ GCC_except_table7771
+ GCC_except_table7772
+ GCC_except_table7796
+ GCC_except_table7869
+ GCC_except_table7872
+ GCC_except_table7879
+ GCC_except_table7881
+ GCC_except_table7882
+ GCC_except_table7884
+ GCC_except_table7885
+ GCC_except_table7886
+ GCC_except_table7887
+ GCC_except_table7892
+ GCC_except_table7894
+ GCC_except_table7895
+ GCC_except_table7896
+ GCC_except_table7897
+ GCC_except_table7901
+ GCC_except_table7902
+ GCC_except_table7904
+ GCC_except_table7906
+ GCC_except_table7908
+ GCC_except_table7910
+ GCC_except_table7916
+ GCC_except_table7919
+ GCC_except_table7923
+ GCC_except_table7924
+ GCC_except_table7926
+ GCC_except_table7927
+ GCC_except_table7928
+ GCC_except_table7929
+ GCC_except_table7930
+ GCC_except_table7932
+ GCC_except_table7933
+ GCC_except_table7934
+ GCC_except_table7935
+ GCC_except_table7936
+ GCC_except_table7937
+ GCC_except_table7938
+ GCC_except_table7939
+ GCC_except_table7940
+ GCC_except_table7941
+ GCC_except_table7942
+ GCC_except_table7943
+ GCC_except_table7944
+ GCC_except_table7945
+ GCC_except_table7946
+ GCC_except_table7947
+ GCC_except_table7948
+ GCC_except_table7949
+ GCC_except_table8049
+ GCC_except_table8078
+ GCC_except_table8163
+ GCC_except_table8357
+ GCC_except_table8372
+ GCC_except_table8409
+ GCC_except_table8416
+ GCC_except_table8469
+ GCC_except_table8514
+ GCC_except_table8658
+ GCC_except_table8663
+ GCC_except_table8666
+ GCC_except_table8689
+ GCC_except_table8733
+ GCC_except_table9028
+ GCC_except_table9032
+ GCC_except_table9068
+ GCC_except_table9072
+ GCC_except_table9074
+ GCC_except_table9151
+ GCC_except_table9191
+ GCC_except_table9206
+ GCC_except_table9224
+ GCC_except_table9225
+ GCC_except_table9293
+ GCC_except_table9482
+ GCC_except_table9492
+ GCC_except_table9493
+ GCC_except_table9495
+ GCC_except_table9496
+ GCC_except_table9657
+ GCC_except_table9684
+ GCC_except_table9708
+ GCC_except_table9716
+ GCC_except_table9840
+ GCC_except_table9879
+ _NUControlAvailabilityDescription
+ _NUMediaMetadataFormatIdentifierAuxiliary
+ _NUMediaMetadataFormatIdentifierImage
+ _NUMediaMetadataFormatIdentifierVideo
+ _NUSanitizedRenderDestinationLabel
+ _OBJC_CLASS_$_NUChannelUnwrappedFormat
+ _OBJC_IVAR_$_NUChannelPortRef._isUnwrapped
+ _OBJC_IVAR_$_NUChannelUnwrappedFormat._optionalFormat
+ _OBJC_IVAR_$_NUCompoundDescriptor._isBuildable
+ _OBJC_IVAR_$_NULivePhotoExportRequest._videoOutputSettings
+ _OBJC_IVAR_$_NUOptionalDescriptor._availability
+ _OBJC_METACLASS_$_NUChannelUnwrappedFormat
+ __OBJC_$_CLASS_METHODS__NUMediaGeometry
+ __OBJC_$_CLASS_PROP_LIST__NUMediaGeometry
+ __OBJC_$_INSTANCE_METHODS_NUChannelData
+ __OBJC_$_INSTANCE_METHODS_NUChannelUnwrappedFormat
+ __OBJC_$_INSTANCE_VARIABLES_NUChannelUnwrappedFormat
+ __OBJC_$_PROP_LIST_NUMediaMetadataPrivate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NUMediaMetadataPrivate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NUMediaMetadataPrivate
+ __OBJC_$_PROTOCOL_REFS_NUMediaMetadataPrivate
+ __OBJC_CLASS_RO_$_NUChannelUnwrappedFormat
+ __OBJC_LABEL_PROTOCOL_$_NUMediaMetadataPrivate
+ __OBJC_METACLASS_RO_$_NUChannelUnwrappedFormat
+ __OBJC_PROTOCOL_$_NUMediaMetadataPrivate
+ ___34-[_NUChannelPort unwrappedSubport]_block_invoke
+ ___45-[NUChannelExpression nu_checkDigestibility:]_block_invoke
+ ___45-[_NUChannelPort _elementSubportWithChannel:]_block_invoke
+ ___49-[NUGlobalSettings rendererContextUseMemoryLimit]_block_invoke
+ ___54-[NUChannelContainerMediaFormat componentsDescription]_block_invoke
+ ___block_descriptor_40_e29_B16?0"NUChannelExpression"8l
+ ___block_descriptor_40_e8_32s_e42_v32?0"NSString"8"NUChannelFormat"16^B24l
+ ___block_descriptor_48_e8_32s40r_e42_v32?0"NSString"8"NUChannelFormat"16^B24l
+ _objc_msgSend$_elementSubportWithChannel:
+ _objc_msgSend$assetMediaWithOriginalStyle:
+ _objc_msgSend$availability
+ _objc_msgSend$checkDigestibility:
+ _objc_msgSend$componentsDescription
+ _objc_msgSend$dataWithFormat:error:
+ _objc_msgSend$geometryIdentifier
+ _objc_msgSend$initWithBaseMedia:cacheNode:format:
+ _objc_msgSend$initWithDescriptor:availability:validatedDefaultValue:
+ _objc_msgSend$initWithOptionalFormat:
+ _objc_msgSend$initWithProperties:identifier:buildable:
+ _objc_msgSend$initWithProperties:identifier:valueType:buildable:
+ _objc_msgSend$isBuildable
+ _objc_msgSend$isEqualToUnwrappedFormat:
+ _objc_msgSend$isUnwrapped
+ _objc_msgSend$mediaWithFormat:error:
+ _objc_msgSend$metadataWithIdentifier:
+ _objc_msgSend$nonOptionalChannel
+ _objc_msgSend$nonOptionalElementSubport
+ _objc_msgSend$nu_checkDigestibility:
+ _objc_msgSend$optionalChannel
+ _objc_msgSend$optionalElementSubport
+ _objc_msgSend$parseLocation:pipelinePath:portMatching:isInput:isConnectedInput:isUnwrapped:error:
+ _objc_msgSend$selectorPipelineWithFormat:
+ _objc_msgSend$setVideoOutputSettings:
+ _objc_msgSend$subdescriptorForKey:
+ _objc_msgSend$subvalueForKey:value:
+ _objc_msgSend$unwrappedChannel
+ _objc_msgSend$unwrappedRef
+ _objc_msgSend$unwrappedSubchannel
+ _objc_msgSend$unwrappedSubport
+ _objc_msgSend$videoOutputSettings
- +[NUChannelPortRef parseLocation:pipelinePath:portMatching:isInput:isConnectedInput:error:]
- +[NUGlobalSettings rendererContextUseMemoryLimit]
- +[NUGlobalSettings setRendererContextUseMemoryLimit:]
- +[NUMediaGeometryExpression geometryDescriptor]
- -[NUChannelData(NUDigest) nu_updateDigest:]
- -[NUCompoundDescriptor descriptorForKey:]
- -[NUCompoundDescriptor initWithProperties:identifier:valueType:]
- -[NUCompoundDescriptor valueForKey:data:]
- -[NUControlDescriptor descriptorForKey:]
- -[NUControlDescriptor valueForKey:data:]
- -[NUMediaGeometryDescriptor controlType]
- -[NUMediaGeometryDescriptor defaultValueType]
- -[NUMediaGeometryDescriptor descriptorWithValueType:]
- -[NUMediaGeometryDescriptor initWithProperties:]
- -[NUMediaGeometryDescriptor initWithProperties:identifier:]
- -[NUMediaGeometryDescriptor initWithProperties:identifier:valueType:]
- -[NUMediaGeometryDescriptor initWithValueType:]
- -[NUMediaGeometryDescriptor init]
- -[NUMediaGeometryDescriptor valueForKey:data:]
- -[NUOptionalDescriptor descriptorForKey:]
- -[NUOptionalDescriptor initWithDescriptor:optionality:validatedDefaultValue:]
- -[NUOptionalDescriptor optionality]
- -[NUOptionalDescriptor valueForKey:data:]
- -[NURectDescriptor descriptorForKey:]
- -[_NUStyleRevertPipeline buildWithOptions:error:]
- -[_NUStyleRevertPipeline containerMediaWithOriginalStyle:error:]
- -[_NUStyleRevertPipeline primaryMediaWithOriginalStyle:deltaMedia:metadataMedia:revertToOriginalStyle:error:]
- GCC_except_table10011
- GCC_except_table10073
- GCC_except_table10080
- GCC_except_table10085
- GCC_except_table10087
- GCC_except_table10205
- GCC_except_table10446
- GCC_except_table10453
- GCC_except_table1056
- GCC_except_table10663
- GCC_except_table10701
- GCC_except_table10705
- GCC_except_table10925
- GCC_except_table11204
- GCC_except_table11207
- GCC_except_table1128
- GCC_except_table11364
- GCC_except_table11374
- GCC_except_table11375
- GCC_except_table11382
- GCC_except_table11387
- GCC_except_table11392
- GCC_except_table11412
- GCC_except_table11419
- GCC_except_table11420
- GCC_except_table11421
- GCC_except_table11422
- GCC_except_table11625
- GCC_except_table11637
- GCC_except_table11642
- GCC_except_table11649
- GCC_except_table11667
- GCC_except_table11685
- GCC_except_table11688
- GCC_except_table11689
- GCC_except_table11693
- GCC_except_table11694
- GCC_except_table11804
- GCC_except_table11829
- GCC_except_table11831
- GCC_except_table11856
- GCC_except_table11927
- GCC_except_table11929
- GCC_except_table11931
- GCC_except_table11936
- GCC_except_table11946
- GCC_except_table1270
- GCC_except_table1282
- GCC_except_table2040
- GCC_except_table2155
- GCC_except_table2372
- GCC_except_table2515
- GCC_except_table2531
- GCC_except_table2545
- GCC_except_table2548
- GCC_except_table2558
- GCC_except_table2570
- GCC_except_table2575
- GCC_except_table2593
- GCC_except_table2596
- GCC_except_table2601
- GCC_except_table2602
- GCC_except_table2604
- GCC_except_table2616
- GCC_except_table2620
- GCC_except_table2647
- GCC_except_table2655
- GCC_except_table2657
- GCC_except_table2662
- GCC_except_table2676
- GCC_except_table2678
- GCC_except_table2679
- GCC_except_table2684
- GCC_except_table2685
- GCC_except_table2697
- GCC_except_table2930
- GCC_except_table2931
- GCC_except_table2932
- GCC_except_table2933
- GCC_except_table2934
- GCC_except_table2936
- GCC_except_table2938
- GCC_except_table2953
- GCC_except_table2954
- GCC_except_table2955
- GCC_except_table2968
- GCC_except_table2969
- GCC_except_table2970
- GCC_except_table2971
- GCC_except_table2986
- GCC_except_table2987
- GCC_except_table3007
- GCC_except_table3047
- GCC_except_table3864
- GCC_except_table3865
- GCC_except_table3869
- GCC_except_table3870
- GCC_except_table3871
- GCC_except_table3872
- GCC_except_table3879
- GCC_except_table3880
- GCC_except_table3889
- GCC_except_table3899
- GCC_except_table3905
- GCC_except_table3906
- GCC_except_table3907
- GCC_except_table3909
- GCC_except_table3914
- GCC_except_table3915
- GCC_except_table3932
- GCC_except_table3934
- GCC_except_table4006
- GCC_except_table4010
- GCC_except_table4038
- GCC_except_table4157
- GCC_except_table4241
- GCC_except_table4247
- GCC_except_table4255
- GCC_except_table4332
- GCC_except_table4333
- GCC_except_table4338
- GCC_except_table4339
- GCC_except_table4341
- GCC_except_table4342
- GCC_except_table4343
- GCC_except_table4344
- GCC_except_table4346
- GCC_except_table4349
- GCC_except_table4350
- GCC_except_table4352
- GCC_except_table4353
- GCC_except_table4354
- GCC_except_table4356
- GCC_except_table4357
- GCC_except_table4367
- GCC_except_table4368
- GCC_except_table4373
- GCC_except_table4374
- GCC_except_table4375
- GCC_except_table4376
- GCC_except_table4381
- GCC_except_table4382
- GCC_except_table4384
- GCC_except_table4387
- GCC_except_table4394
- GCC_except_table4406
- GCC_except_table4407
- GCC_except_table4416
- GCC_except_table4417
- GCC_except_table4419
- GCC_except_table4425
- GCC_except_table4432
- GCC_except_table4433
- GCC_except_table4439
- GCC_except_table4440
- GCC_except_table4442
- GCC_except_table4443
- GCC_except_table4444
- GCC_except_table4445
- GCC_except_table4451
- GCC_except_table4452
- GCC_except_table4455
- GCC_except_table4508
- GCC_except_table4531
- GCC_except_table4532
- GCC_except_table4535
- GCC_except_table4536
- GCC_except_table4541
- GCC_except_table4542
- GCC_except_table4545
- GCC_except_table4546
- GCC_except_table4547
- GCC_except_table4548
- GCC_except_table4549
- GCC_except_table4550
- GCC_except_table4551
- GCC_except_table4553
- GCC_except_table4559
- GCC_except_table4563
- GCC_except_table4567
- GCC_except_table4568
- GCC_except_table4569
- GCC_except_table4571
- GCC_except_table4578
- GCC_except_table4581
- GCC_except_table4632
- GCC_except_table4633
- GCC_except_table4831
- GCC_except_table4910
- GCC_except_table4911
- GCC_except_table4915
- GCC_except_table4917
- GCC_except_table4921
- GCC_except_table4923
- GCC_except_table4925
- GCC_except_table4926
- GCC_except_table4930
- GCC_except_table4934
- GCC_except_table4935
- GCC_except_table4936
- GCC_except_table4937
- GCC_except_table4938
- GCC_except_table4940
- GCC_except_table4941
- GCC_except_table4943
- GCC_except_table4944
- GCC_except_table4954
- GCC_except_table4956
- GCC_except_table4987
- GCC_except_table4990
- GCC_except_table4993
- GCC_except_table4994
- GCC_except_table4996
- GCC_except_table4997
- GCC_except_table4998
- GCC_except_table4999
- GCC_except_table5000
- GCC_except_table5001
- GCC_except_table5003
- GCC_except_table5005
- GCC_except_table5006
- GCC_except_table5007
- GCC_except_table5008
- GCC_except_table5013
- GCC_except_table5014
- GCC_except_table5020
- GCC_except_table5021
- GCC_except_table5026
- GCC_except_table5027
- GCC_except_table5028
- GCC_except_table5031
- GCC_except_table5032
- GCC_except_table5058
- GCC_except_table5060
- GCC_except_table5063
- GCC_except_table5064
- GCC_except_table5065
- GCC_except_table5066
- GCC_except_table5067
- GCC_except_table5071
- GCC_except_table5072
- GCC_except_table5073
- GCC_except_table5176
- GCC_except_table5265
- GCC_except_table5500
- GCC_except_table5514
- GCC_except_table5526
- GCC_except_table5549
- GCC_except_table5561
- GCC_except_table5566
- GCC_except_table5656
- GCC_except_table5659
- GCC_except_table5668
- GCC_except_table5693
- GCC_except_table5758
- GCC_except_table5766
- GCC_except_table5781
- GCC_except_table5880
- GCC_except_table5887
- GCC_except_table5888
- GCC_except_table5889
- GCC_except_table5890
- GCC_except_table5891
- GCC_except_table5894
- GCC_except_table5895
- GCC_except_table5898
- GCC_except_table5901
- GCC_except_table5902
- GCC_except_table5904
- GCC_except_table5907
- GCC_except_table5908
- GCC_except_table5909
- GCC_except_table5910
- GCC_except_table5911
- GCC_except_table5912
- GCC_except_table5913
- GCC_except_table5914
- GCC_except_table5924
- GCC_except_table5925
- GCC_except_table5930
- GCC_except_table5937
- GCC_except_table5953
- GCC_except_table5954
- GCC_except_table5960
- GCC_except_table5965
- GCC_except_table5973
- GCC_except_table5974
- GCC_except_table5984
- GCC_except_table5985
- GCC_except_table5986
- GCC_except_table5987
- GCC_except_table5988
- GCC_except_table6201
- GCC_except_table6788
- GCC_except_table7090
- GCC_except_table7098
- GCC_except_table7105
- GCC_except_table7106
- GCC_except_table7110
- GCC_except_table7181
- GCC_except_table7210
- GCC_except_table7216
- GCC_except_table7231
- GCC_except_table7286
- GCC_except_table7354
- GCC_except_table7364
- GCC_except_table7391
- GCC_except_table7392
- GCC_except_table7442
- GCC_except_table7609
- GCC_except_table7645
- GCC_except_table7654
- GCC_except_table7677
- GCC_except_table7681
- GCC_except_table7683
- GCC_except_table7684
- GCC_except_table7685
- GCC_except_table7709
- GCC_except_table7760
- GCC_except_table7761
- GCC_except_table7762
- GCC_except_table7763
- GCC_except_table7774
- GCC_except_table7775
- GCC_except_table7782
- GCC_except_table7785
- GCC_except_table7792
- GCC_except_table7794
- GCC_except_table7795
- GCC_except_table7797
- GCC_except_table7798
- GCC_except_table7799
- GCC_except_table7800
- GCC_except_table7805
- GCC_except_table7807
- GCC_except_table7808
- GCC_except_table7809
- GCC_except_table7810
- GCC_except_table7814
- GCC_except_table7815
- GCC_except_table7817
- GCC_except_table7819
- GCC_except_table7821
- GCC_except_table7823
- GCC_except_table7829
- GCC_except_table7832
- GCC_except_table7836
- GCC_except_table7837
- GCC_except_table7839
- GCC_except_table7840
- GCC_except_table7841
- GCC_except_table7842
- GCC_except_table7843
- GCC_except_table7845
- GCC_except_table7846
- GCC_except_table7851
- GCC_except_table7852
- GCC_except_table7853
- GCC_except_table7854
- GCC_except_table7856
- GCC_except_table7857
- GCC_except_table7858
- GCC_except_table7859
- GCC_except_table7860
- GCC_except_table7962
- GCC_except_table7991
- GCC_except_table8076
- GCC_except_table8270
- GCC_except_table8285
- GCC_except_table8322
- GCC_except_table8329
- GCC_except_table8382
- GCC_except_table8427
- GCC_except_table8571
- GCC_except_table8576
- GCC_except_table8579
- GCC_except_table8602
- GCC_except_table8646
- GCC_except_table8941
- GCC_except_table8945
- GCC_except_table8981
- GCC_except_table8985
- GCC_except_table8987
- GCC_except_table9050
- GCC_except_table9064
- GCC_except_table9104
- GCC_except_table9136
- GCC_except_table9205
- GCC_except_table9394
- GCC_except_table9404
- GCC_except_table9405
- GCC_except_table9407
- GCC_except_table9408
- GCC_except_table9569
- GCC_except_table9596
- GCC_except_table9620
- GCC_except_table9628
- GCC_except_table9752
- GCC_except_table9791
- _NUControlOptionalityDescription
- _OBJC_CLASS_$_NUMediaGeometryDescriptor
- _OBJC_IVAR_$_NUOptionalDescriptor._optionality
- _OBJC_METACLASS_$_NUMediaGeometryDescriptor
- __OBJC_$_CLASS_METHODS_NUMediaGeometryExpression
- __OBJC_$_INSTANCE_METHODS_NUChannelData(NUDigest)
- __OBJC_$_INSTANCE_METHODS_NUMediaGeometryDescriptor
- __OBJC_CLASS_RO_$_NUMediaGeometryDescriptor
- __OBJC_METACLASS_RO_$_NUMediaGeometryDescriptor
- ___32-[_NUChannelPort elementSubport]_block_invoke
- ___44-[NUChannelContainerMediaFormat description]_block_invoke
- ___49+[NUGlobalSettings rendererContextUseMemoryLimit]_block_invoke
- ___block_descriptor_40_e8_32r_e47_v32?0"NSString"8"NUChannelMediaFormat"16^B24l
- ___block_descriptor_48_e8_32s40r_e47_v32?0"NSString"8"NUChannelMediaFormat"16^B24l
- _objc_msgSend$descriptorForKey:
- _objc_msgSend$initWithDescriptor:optionality:validatedDefaultValue:
- _objc_msgSend$initWithProperties:identifier:valueType:
- _objc_msgSend$optionality
- _objc_msgSend$parseLocation:pipelinePath:portMatching:isInput:isConnectedInput:error:
- _objc_msgSend$pixelRect
- _objc_msgSend$timeChannelWithName:
- _objc_msgSend$valueForKey:data:
CStrings:
+ "%@!"
+ "-[NUChannelControlData dataWithFormat:error:]"
+ "-[NUChannelData dataWithFormat:error:]"
+ "-[NUChannelMediaData dataWithFormat:error:]"
+ "-[NUChannelStaticExpression nu_checkDigestibility:]"
+ "-[NUChannelStaticExpression nu_updateDigest:]"
+ "-[NUChannelUnwrappedFormat canAcceptDataWithFormat:]"
+ "-[NUChannelUnwrappedFormat initWithOptionalFormat:]"
+ "-[NUChannelUnwrappedFormat init]"
+ "-[NUCompoundDescriptor initWithProperties:identifier:valueType:buildable:]"
+ "-[NUCompoundDescriptor subdescriptorForKey:]"
+ "-[NUOptionalDescriptor initWithDescriptor:availability:validatedDefaultValue:]"
+ "-[NURenderSession waitForTermination]_block_invoke"
+ "-[_NUAssetPipeline primaryMediaWithOriginalStyle:deltaMedia:metadataMedia:revertToOriginalStyle:error:]"
+ "-[_NUCachedComputedMedia mediaWithFormat:error:]"
+ "-[_NUCachedMedia initWithBaseMedia:cacheNode:format:]"
+ "-[_NUChannelPort _elementSubportWithChannel:]"
+ "-[_NUCompositeMedia mediaWithFormat:error:]"
+ "-[_NUComputedMedia mediaWithFormat:error:]"
+ "-[_NURenderMedia mediaWithFormat:error:]"
+ "<%@:%p unwrapped:%@>"
+ "AuxiliaryMetadata"
+ "CLAP %@ should be contained in scaled extent size %@"
+ "Cannot convert control data"
+ "Control data is not digestible"
+ "Element subport already exists with another format: %@"
+ "Failed to convert control data"
+ "Failed to format media component"
+ "Failed to format output data"
+ "Failed to revert asset style, using the plain asset media: %{public}@"
+ "ImageMetadata"
+ "Incompatible computed media format"
+ "MediaGeometry"
+ "Missing gainMap input"
+ "NUAuxiliaryMetadata<"
+ "NUImageMetadata<"
+ "NUVideoMetadata<"
+ "Optional primary component"
+ "Port is not optional"
+ "Session is not terminating"
+ "Session was terminated"
+ "Static expressions are not digestible"
+ "Target format cannot accept a null described by the source format"
+ "Unwrapped data is nil"
+ "VideoMetadata"
+ "defaultValue == nil || availability != NUControlAvailabilityRequired"
+ "format.descriptor.controlType == NUControlTypeOptional"
+ "media!"
+ "optionalFormat != nil"
+ "optionalFormat.isOptional"
+ "sourceFormat"
+ "targetFormat"
+ "unwrapped"
+ "value!"
- "%@[%@]"
- ")<"
- "-[NUCompoundDescriptor descriptorForKey:]"
- "-[NUCompoundDescriptor initWithProperties:identifier:valueType:]"
- "-[NUMediaGeometryDescriptor initWithProperties:]"
- "-[NUMediaGeometryDescriptor initWithProperties:identifier:]"
- "-[NUMediaGeometryDescriptor initWithProperties:identifier:valueType:]"
- "-[NUMediaGeometryDescriptor valueForKey:data:]"
- "-[NUOptionalDescriptor initWithDescriptor:optionality:validatedDefaultValue:]"
- "-[_NUChannelPort specializeWithInputFormat:]"
- "-[_NUChannelPort specializeWithOutputFormat:]"
- "-[_NUStyleRevertPipeline primaryMediaWithOriginalStyle:deltaMedia:metadataMedia:revertToOriginalStyle:error:]"
- "Cannot expose computed media as control data"
- "Failed to revert asset style"
- "Missing crop rect input"
- "Missing end data"
- "Missing start data"
- "NUChannelData("
- "Unsupported media geometry key: '%@'"
- "cleanApertureRect"
- "defaultValue == nil || optionality != NUControlOptionalityRequired"
- "format.descriptor.isOptional"
- "geometry"
- "inputFormat != nil"
- "outputFormat != nil"
- "session '%{public}@' terminated"
- "useCleanRect"
- "v32@?0@\"NSString\"8@\"NUChannelMediaFormat\"16^B24"
```
