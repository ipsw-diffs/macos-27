## NeutrinoCore

> `/System/Library/PrivateFrameworks/NeutrinoCore.framework/Versions/A/NeutrinoCore`

```diff

-916.58.114.0.0
-  __TEXT.__text: 0x354c94
-  __TEXT.__objc_methlist: 0x216f4
-  __TEXT.__const: 0x27a8
+920.8.100.0.0
+  __TEXT.__text: 0x35c778
+  __TEXT.__objc_methlist: 0x21dcc
+  __TEXT.__const: 0x2990
   __TEXT.__dlopen_cstrs: 0x45
-  __TEXT.__swift5_typeref: 0x52b
+  __TEXT.__constg_swiftt: 0x178
+  __TEXT.__swift5_typeref: 0x569
+  __TEXT.__swift5_builtin: 0xdc
   __TEXT.__swift5_reflstr: 0x93
-  __TEXT.__swift5_assocty: 0x78
-  __TEXT.__constg_swiftt: 0x158
-  __TEXT.__swift5_builtin: 0xc8
-  __TEXT.__swift5_fieldmd: 0x15c
-  __TEXT.__swift5_proto: 0x64
-  __TEXT.__swift5_types: 0x28
-  __TEXT.__cstring: 0x4116b
-  __TEXT.__swift5_capture: 0x350
-  __TEXT.__gcc_except_tab: 0x81c8
-  __TEXT.__oslogstring: 0x594f
-  __TEXT.__ustring: 0x2e
-  __TEXT.__unwind_info: 0xa660
-  __TEXT.__eh_frame: 0x650
+  __TEXT.__swift5_fieldmd: 0x178
+  __TEXT.__swift5_assocty: 0xc0
+  __TEXT.__swift5_proto: 0x84
+  __TEXT.__swift5_types: 0x2c
+  __TEXT.__cstring: 0x41e1e
+  __TEXT.__swift5_capture: 0x390
+  __TEXT.__gcc_except_tab: 0x825c
+  __TEXT.__oslogstring: 0x598d
+  __TEXT.__ustring: 0x3e
+  __TEXT.__unwind_info: 0xa850
+  __TEXT.__eh_frame: 0x6c0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1670
-  __DATA_CONST.__objc_classlist: 0x1618
+  __DATA_CONST.__const: 0x16b0
+  __DATA_CONST.__objc_classlist: 0x1640
   __DATA_CONST.__objc_catlist: 0xa8
-  __DATA_CONST.__objc_protolist: 0x4e0
+  __DATA_CONST.__objc_protolist: 0x4e8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb880
-  __DATA_CONST.__objc_protorefs: 0x68
-  __DATA_CONST.__objc_superrefs: 0x1028
-  __DATA_CONST.__objc_arraydata: 0xad0
-  __DATA_CONST.__got: 0x22f8
-  __AUTH_CONST.__const: 0x87e0
-  __AUTH_CONST.__cfstring: 0x1d500
-  __AUTH_CONST.__objc_const: 0x37ed0
+  __DATA_CONST.__objc_selrefs: 0xba00
+  __DATA_CONST.__objc_protorefs: 0x60
+  __DATA_CONST.__objc_superrefs: 0x1040
+  __DATA_CONST.__objc_arraydata: 0xb10
+  __DATA_CONST.__got: 0x2328
+  __AUTH_CONST.__const: 0x8978
+  __AUTH_CONST.__cfstring: 0x1dc00
+  __AUTH_CONST.__objc_const: 0x38640
   __AUTH_CONST.__weak_auth_got: 0x18
-  __AUTH_CONST.__objc_intobj: 0x8d0
   __AUTH_CONST.__objc_dictobj: 0x348
-  __AUTH_CONST.__objc_doubleobj: 0x210
-  __AUTH_CONST.__objc_floatobj: 0x70
-  __AUTH_CONST.__objc_arrayobj: 0xf0
+  __AUTH_CONST.__objc_intobj: 0x990
+  __AUTH_CONST.__objc_doubleobj: 0x1f0
+  __AUTH_CONST.__objc_arrayobj: 0x108
+  __AUTH_CONST.__objc_floatobj: 0x50
   __AUTH_CONST.__auth_got: 0xfe0
-  __AUTH.__objc_data: 0x190
-  __DATA.__objc_ivar: 0x1aa4
-  __DATA.__data: 0x248
+  __AUTH.__objc_data: 0x320
+  __DATA.__objc_ivar: 0x1ad0
+  __DATA.__data: 0x2f0
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x1020
+  __DATA.__bss: 0x1410
   __DATA_DIRTY.__objc_data: 0xdb60
   __DATA_DIRTY.__data: 0x3780
   __DATA_DIRTY.__bss: 0x158

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12231
-  Symbols:   25987
-  CStrings:  7384
+  Functions: 12390
+  Symbols:   26231
+  CStrings:  7473
 
Symbols:
+ +[CIVector(NUControlDataRepresentable) nu_valueFromControlData:error:]
+ +[NSArray(NUControlDataRepresentable) nu_valueFromControlData:error:]
+ +[NSDictionary(NUControlDataRepresentable) nu_valueFromControlData:error:]
+ +[NSNumber(NUControlDataRepresentable) nu_valueFromControlData:error:]
+ +[NSString(NUControlDataRepresentable) nu_valueFromControlData:error:]
+ +[NUAssetCapability capabilityMarkerFormat]
+ +[NUAssetCapability(NURawDecode) rawDecode]
+ +[NUChannelControlData opaqueDataWithValue:identifier:]
+ +[NUChannelControlFormat opaqueFormat:]
+ +[NUChannelData opaque:identifier:]
+ +[NUChannelData orientation:]
+ +[NUChannelExpression forceUnwrap:]
+ +[NUEnumDescriptor orientationDescriptor]
+ +[NUEnumDescriptor orientationIdentifier]
+ +[NUOptionalDescriptor requiredOptionalWithDescriptor:]
+ +[NUOptionalDescriptor unavailableOptionalWithDescriptor:]
+ +[NUOptionalDescriptor unavailableOptionalWithDescriptor:defaultValue:]
+ +[NUPipelineProcessor identifier]
+ +[NUStyleTransferPipeline colorSpaceFormat]
+ +[_NURawDecodeCapability rawDecodeCapabilityFormat]
+ +[_NUStyleEngineMemoryResource usingSharedMemoryResourceForMetalCommandQueue:withDescriptor:perform:]
+ -[NSArray(NUControlDataRepresentable) nu_convertedFromFormat:toFormat:error:]
+ -[NSDictionary(NUControlDataRepresentable) nu_convertedFromFormat:toFormat:error:]
+ -[NUArrayDescriptor descriptorWithValueType:]
+ -[NUArrayDescriptor initWithElement:min:max:valueType:]
+ -[NUArrayDescriptor initWithValueType:]
+ -[NUAssetCapability format]
+ -[NUChannelArrayData _untypedValue]
+ -[NUChannelContainsExpression compactDescription]
+ -[NUChannelContainsExpression description]
+ -[NUChannelContainsExpression evaluateWithLeftData:rightData:outputFormat:error:]
+ -[NUChannelContainsExpression formatWithLeftData:rightData:error:]
+ -[NUChannelContainsExpression hash]
+ -[NUChannelContainsExpression isEqualToContainsExpression:]
+ -[NUChannelContainsExpression isEqualToExpression:]
+ -[NUChannelControlData _untypedValue]
+ -[NUChannelControlData opaqueValue]
+ -[NUChannelControlData valueOfType:]
+ -[NUChannelControlFormat descriptor]
+ -[NUChannelControlFormat shortDescription]
+ -[NUChannelData _opaqueValueOfClass:]
+ -[NUChannelData _untypedValue]
+ -[NUChannelData arrayValue]
+ -[NUChannelData dictionaryValue]
+ -[NUChannelData geometryValue]
+ -[NUChannelData mediaValue]
+ -[NUChannelData metadataValue]
+ -[NUChannelData numberValue]
+ -[NUChannelData opaqueArrayValue]
+ -[NUChannelData opaqueDataValue]
+ -[NUChannelData opaqueDictionaryValue]
+ -[NUChannelData opaqueStringValue]
+ -[NUChannelData opaqueValue]
+ -[NUChannelData rectangleValue]
+ -[NUChannelData stringEnumValue]
+ -[NUChannelData timeValue]
+ -[NUChannelData valueOfType:]
+ -[NUChannelElementData _untypedValue]
+ -[NUChannelExpression contains:]
+ -[NUChannelExpressionData _untypedValue]
+ -[NUChannelForceUnwrapExpression compactDescription]
+ -[NUChannelForceUnwrapExpression description]
+ -[NUChannelForceUnwrapExpression evaluateWithData:outputFormat:error:]
+ -[NUChannelForceUnwrapExpression formatWithData:error:]
+ -[NUChannelForceUnwrapExpression hash]
+ -[NUChannelForceUnwrapExpression isEqualToExpression:]
+ -[NUChannelFormat canAcceptOptionalDataWithFormat:]
+ -[NUChannelFormat shortDescription]
+ -[NUChannelMediaData _untypedValue]
+ -[NUChannelMediaData mediaValue]
+ -[NUChannelMediaFormat componentMediaType]
+ -[NUChannelMetadata _untypedValue]
+ -[NUChannelMetadata metadataValue]
+ -[NUChannelNilCoalesceExpression compactDescription]
+ -[NUChannelNilCoalesceExpression description]
+ -[NUChannelNilCoalesceExpression evaluateWithLeftData:rightData:outputFormat:error:]
+ -[NUChannelNilCoalesceExpression formatWithLeftData:rightData:error:]
+ -[NUChannelNilCoalesceExpression hash]
+ -[NUChannelNilCoalesceExpression isEqualToExpression:]
+ -[NUChannelNilCoalesceExpression isEqualToNilCoalesceExpression:]
+ -[NUChannelNullData _untypedValue]
+ -[NUCompoundDescriptor descriptorWithValueType:]
+ -[NUCompoundDescriptor identifier]
+ -[NUCompoundDescriptor initWithProperties:identifier:]
+ -[NUCompoundDescriptor initWithProperties:identifier:valueType:]
+ -[NUCompoundDescriptor initWithValueType:]
+ -[NUCompoundDescriptor shortDescription]
+ -[NUControlDescriptor defaultValue]
+ -[NUControlDescriptor descriptorWithObjectType:]
+ -[NUControlDescriptor descriptorWithValueType:]
+ -[NUControlDescriptor enforceValidValue:]
+ -[NUControlDescriptor initWithValueType:]
+ -[NUControlDescriptor isValue:equalToValue:]
+ -[NUControlDescriptor shortDescription]
+ -[NUControlDescriptor validate:error:]
+ -[NUControlDescriptor valueType]
+ -[NUCoreImageFilterPipelineProcessor identifier]
+ -[NUEnumDescriptor debugDescription]
+ -[NUEnumDescriptor descriptorWithValueType:]
+ -[NUEnumDescriptor enumValueType]
+ -[NUEnumDescriptor identifier]
+ -[NUEnumDescriptor initWithEnumValueType:values:identifier:valueType:]
+ -[NUEnumDescriptor initWithIntegerValues:identifier:]
+ -[NUEnumDescriptor initWithStringValues:identifier:]
+ -[NUEnumDescriptor initWithValueType:]
+ -[NUEnumDescriptor initWithValues:valueType:]
+ -[NUEnumDescriptor isEqualToEnumDescriptor:]
+ -[NUGlobalSettings setStandardPreviewSizeInMegapixels:]
+ -[NUGlobalSettings standardPreviewSizeInMegapixels]
+ -[NUMediaGeometryDescriptor controlType]
+ -[NUMediaGeometryDescriptor defaultValueType]
+ -[NUMediaGeometryDescriptor descriptorWithValueType:]
+ -[NUMediaGeometryDescriptor initWithProperties:identifier:]
+ -[NUMediaGeometryDescriptor initWithProperties:identifier:valueType:]
+ -[NUMediaGeometryDescriptor initWithValueType:]
+ -[NUNumberDescriptor descriptorWithValueType:]
+ -[NUNumberDescriptor enforceValidValue:]
+ -[NUNumberDescriptor initWithNumberType:min:max:precision:]
+ -[NUNumberDescriptor initWithNumberType:min:max:precision:valueType:]
+ -[NUNumberDescriptor initWithValueType:]
+ -[NUNumberDescriptor isValue:equalToValue:]
+ -[NUNumberDescriptor precision]
+ -[NUNumberDescriptor validBoolValue:]
+ -[NUNumberDescriptor validDoubleValue:]
+ -[NUNumberDescriptor validIntegerValue:]
+ -[NUOpaqueDescriptor canAcceptDataWithDescriptor:]
+ -[NUOpaqueDescriptor descriptorWithValueType:]
+ -[NUOpaqueDescriptor initWithIdentifier:valueType:]
+ -[NUOpaqueDescriptor initWithValueType:]
+ -[NUOptionalDescriptor canAcceptDataWithNonOptionalDescriptor:]
+ -[NUOptionalDescriptor canAcceptDataWithOptionalDescriptor:]
+ -[NUOptionalDescriptor descriptorWithValueType:]
+ -[NUOptionalDescriptor enforceValidValue:]
+ -[NUOptionalDescriptor initWithDescriptor:optionality:validatedDefaultValue:]
+ -[NUOptionalDescriptor initWithValueType:]
+ -[NUOptionalDescriptor optionality]
+ -[NUOptionalDescriptor valueType]
+ -[NUPipelineProcessor identifier]
+ -[NURectDescriptor descriptorWithValueType:]
+ -[NURunQueue synchronize:]
+ -[NURunQueueLane synchronize:]
+ -[NUStandardPreviewScalePolicy .cxx_destruct]
+ -[NUStandardPreviewScalePolicy init]
+ -[NUStandardPreviewScalePolicy scaleForImageGeometry:]
+ -[NUStandardPreviewScalePolicy scaleForImageSize:]
+ -[NUTimeDescriptor descriptorWithValueType:]
+ -[NUVectorDescriptor descriptorWithValueType:]
+ -[NUVectorDescriptor initWithElement:size:valueType:]
+ -[NUVectorDescriptor initWithValueType:]
+ -[_NUAsset addCapability:value:]
+ -[_NUContainerPipeline .cxx_destruct]
+ -[_NUContainerPipeline componentFormat]
+ -[_NUContainerPipeline componentInputPort]
+ -[_NUContainerPipeline componentOutputPort]
+ -[_NUContainerPipeline initWithContainerFormat:componentFormat:]
+ -[_NUHDRToneMapLearnPipeline _genericInputPortsMatchingOutputPort:]
+ -[_NUHDRToneMapLearnPipeline _genericOutputPortsMatchingInputPort:]
+ -[_NULivePhotoRenderResult image]
+ -[_NULivePhotoRenderResult setImage:]
+ -[_NUPipeline addContainerPipelineWithContainerFormat:componentFormat:block:]
+ -[_NUPipeline addContainerPipelineWithContainerFormat:componentFormat:block:error:]
+ -[_NUPipeline insertContainerMapAt:containerFormat:componentFormat:block:error:]
+ -[_NUPipeline insertContainerMapAt:input:componentFormat:block:error:]
+ -[_NUPipeline processContainer:componentFormat:forEachComponent:error:]
+ -[_NUPipeline processContainerPort:componentFormat:forEachComponentPort:error:]
+ -[_NURawDecodeCapability format]
+ -[_NURawDecodePipeline rawForceDraftModeWithOptions:]
+ -[_NURenderNodePipeline _formatForInput:]
+ -[_NUStyleEngineMemoryResource metalCommandQueue]
+ -[_NUStyleEngineMemoryResource setMetalCommandQueue:]
+ GCC_except_table10011
+ GCC_except_table10073
+ GCC_except_table10080
+ GCC_except_table10085
+ GCC_except_table10087
+ GCC_except_table10205
+ GCC_except_table10446
+ GCC_except_table10453
+ GCC_except_table1056
+ GCC_except_table10701
+ GCC_except_table10705
+ GCC_except_table10925
+ GCC_except_table11204
+ GCC_except_table11207
+ GCC_except_table1128
+ GCC_except_table11364
+ GCC_except_table11374
+ GCC_except_table11375
+ GCC_except_table11382
+ GCC_except_table11387
+ GCC_except_table11392
+ GCC_except_table11412
+ GCC_except_table11419
+ GCC_except_table11420
+ GCC_except_table11421
+ GCC_except_table11422
+ GCC_except_table11625
+ GCC_except_table11637
+ GCC_except_table11642
+ GCC_except_table11649
+ GCC_except_table11667
+ GCC_except_table11685
+ GCC_except_table11688
+ GCC_except_table11689
+ GCC_except_table11693
+ GCC_except_table11694
+ GCC_except_table11804
+ GCC_except_table11829
+ GCC_except_table11831
+ GCC_except_table11856
+ GCC_except_table11927
+ GCC_except_table11929
+ GCC_except_table11931
+ GCC_except_table11936
+ GCC_except_table11945
+ GCC_except_table11946
+ GCC_except_table1270
+ GCC_except_table1282
+ GCC_except_table134
+ GCC_except_table18
+ GCC_except_table19
+ GCC_except_table194
+ GCC_except_table197
+ GCC_except_table199
+ GCC_except_table2040
+ GCC_except_table2155
+ GCC_except_table2372
+ GCC_except_table238
+ GCC_except_table24
+ GCC_except_table2515
+ GCC_except_table2531
+ GCC_except_table2545
+ GCC_except_table2548
+ GCC_except_table2558
+ GCC_except_table2570
+ GCC_except_table2575
+ GCC_except_table2593
+ GCC_except_table2595
+ GCC_except_table2596
+ GCC_except_table26
+ GCC_except_table2601
+ GCC_except_table2602
+ GCC_except_table2604
+ GCC_except_table2605
+ GCC_except_table2616
+ GCC_except_table2620
+ GCC_except_table2622
+ GCC_except_table2642
+ GCC_except_table2647
+ GCC_except_table2652
+ GCC_except_table2655
+ GCC_except_table2657
+ GCC_except_table2662
+ GCC_except_table2676
+ GCC_except_table2678
+ GCC_except_table2679
+ GCC_except_table2684
+ GCC_except_table2685
+ GCC_except_table2697
+ GCC_except_table2930
+ GCC_except_table2931
+ GCC_except_table2932
+ GCC_except_table2933
+ GCC_except_table2934
+ GCC_except_table2936
+ GCC_except_table2938
+ GCC_except_table2953
+ GCC_except_table2954
+ GCC_except_table2955
+ GCC_except_table2968
+ GCC_except_table2969
+ GCC_except_table2970
+ GCC_except_table2971
+ GCC_except_table2986
+ GCC_except_table2987
+ GCC_except_table3001
+ GCC_except_table3002
+ GCC_except_table3007
+ GCC_except_table3047
+ GCC_except_table32
+ GCC_except_table33
+ GCC_except_table35
+ GCC_except_table36
+ GCC_except_table3864
+ GCC_except_table3865
+ GCC_except_table3869
+ GCC_except_table3870
+ GCC_except_table3871
+ GCC_except_table3872
+ GCC_except_table3879
+ GCC_except_table3880
+ GCC_except_table3889
+ GCC_except_table3899
+ GCC_except_table3905
+ GCC_except_table3906
+ GCC_except_table3907
+ GCC_except_table3909
+ GCC_except_table3911
+ GCC_except_table3914
+ GCC_except_table3915
+ GCC_except_table3916
+ GCC_except_table3932
+ GCC_except_table3934
+ GCC_except_table3954
+ GCC_except_table4006
+ GCC_except_table4010
+ GCC_except_table4038
+ GCC_except_table4157
+ GCC_except_table4241
+ GCC_except_table4247
+ GCC_except_table4255
+ GCC_except_table4332
+ GCC_except_table4333
+ GCC_except_table4338
+ GCC_except_table4339
+ GCC_except_table4341
+ GCC_except_table4342
+ GCC_except_table4343
+ GCC_except_table4344
+ GCC_except_table4346
+ GCC_except_table4349
+ GCC_except_table4350
+ GCC_except_table4352
+ GCC_except_table4353
+ GCC_except_table4354
+ GCC_except_table4356
+ GCC_except_table4357
+ GCC_except_table4367
+ GCC_except_table4368
+ GCC_except_table4373
+ GCC_except_table4374
+ GCC_except_table4375
+ GCC_except_table4376
+ GCC_except_table4379
+ GCC_except_table4380
+ GCC_except_table4381
+ GCC_except_table4382
+ GCC_except_table4384
+ GCC_except_table4387
+ GCC_except_table4388
+ GCC_except_table4389
+ GCC_except_table4390
+ GCC_except_table4391
+ GCC_except_table4394
+ GCC_except_table4399
+ GCC_except_table4400
+ GCC_except_table4403
+ GCC_except_table4406
+ GCC_except_table4407
+ GCC_except_table4415
+ GCC_except_table4416
+ GCC_except_table4417
+ GCC_except_table4419
+ GCC_except_table4420
+ GCC_except_table4421
+ GCC_except_table4423
+ GCC_except_table4425
+ GCC_except_table4426
+ GCC_except_table4427
+ GCC_except_table4432
+ GCC_except_table4433
+ GCC_except_table4434
+ GCC_except_table4435
+ GCC_except_table4436
+ GCC_except_table4438
+ GCC_except_table4439
+ GCC_except_table4440
+ GCC_except_table4441
+ GCC_except_table4442
+ GCC_except_table4443
+ GCC_except_table4444
+ GCC_except_table4445
+ GCC_except_table4450
+ GCC_except_table4451
+ GCC_except_table4452
+ GCC_except_table4453
+ GCC_except_table4454
+ GCC_except_table4455
+ GCC_except_table4508
+ GCC_except_table4531
+ GCC_except_table4535
+ GCC_except_table4536
+ GCC_except_table4541
+ GCC_except_table4542
+ GCC_except_table4545
+ GCC_except_table4546
+ GCC_except_table4547
+ GCC_except_table4548
+ GCC_except_table4549
+ GCC_except_table4550
+ GCC_except_table4551
+ GCC_except_table4553
+ GCC_except_table4563
+ GCC_except_table4567
+ GCC_except_table4568
+ GCC_except_table4569
+ GCC_except_table4571
+ GCC_except_table4578
+ GCC_except_table4580
+ GCC_except_table4581
+ GCC_except_table482
+ GCC_except_table4831
+ GCC_except_table4910
+ GCC_except_table4911
+ GCC_except_table4915
+ GCC_except_table4917
+ GCC_except_table4921
+ GCC_except_table4923
+ GCC_except_table4925
+ GCC_except_table4926
+ GCC_except_table4930
+ GCC_except_table4934
+ GCC_except_table4935
+ GCC_except_table4936
+ GCC_except_table4937
+ GCC_except_table4938
+ GCC_except_table4940
+ GCC_except_table4941
+ GCC_except_table4943
+ GCC_except_table4944
+ GCC_except_table4954
+ GCC_except_table4956
+ GCC_except_table4982
+ GCC_except_table4985
+ GCC_except_table4986
+ GCC_except_table4987
+ GCC_except_table4989
+ GCC_except_table4990
+ GCC_except_table4991
+ GCC_except_table4992
+ GCC_except_table4993
+ GCC_except_table4994
+ GCC_except_table4996
+ GCC_except_table4997
+ GCC_except_table4998
+ GCC_except_table4999
+ GCC_except_table5000
+ GCC_except_table5001
+ GCC_except_table5002
+ GCC_except_table5003
+ GCC_except_table5004
+ GCC_except_table5005
+ GCC_except_table5006
+ GCC_except_table5007
+ GCC_except_table5008
+ GCC_except_table5013
+ GCC_except_table5014
+ GCC_except_table5020
+ GCC_except_table5021
+ GCC_except_table5026
+ GCC_except_table5027
+ GCC_except_table5028
+ GCC_except_table503
+ GCC_except_table5030
+ GCC_except_table5031
+ GCC_except_table5032
+ GCC_except_table5033
+ GCC_except_table5034
+ GCC_except_table504
+ GCC_except_table5040
+ GCC_except_table5041
+ GCC_except_table5042
+ GCC_except_table5044
+ GCC_except_table5045
+ GCC_except_table5049
+ GCC_except_table505
+ GCC_except_table5050
+ GCC_except_table5051
+ GCC_except_table5052
+ GCC_except_table5053
+ GCC_except_table5054
+ GCC_except_table5055
+ GCC_except_table5056
+ GCC_except_table5058
+ GCC_except_table5060
+ GCC_except_table5063
+ GCC_except_table5064
+ GCC_except_table5065
+ GCC_except_table5066
+ GCC_except_table5067
+ GCC_except_table5069
+ GCC_except_table5071
+ GCC_except_table5072
+ GCC_except_table5073
+ GCC_except_table5074
+ GCC_except_table508
+ GCC_except_table5082
+ GCC_except_table509
+ GCC_except_table512
+ GCC_except_table5176
+ GCC_except_table5265
+ GCC_except_table529
+ GCC_except_table530
+ GCC_except_table531
+ GCC_except_table534
+ GCC_except_table535
+ GCC_except_table536
+ GCC_except_table541
+ GCC_except_table543
+ GCC_except_table548
+ GCC_except_table549
+ GCC_except_table550
+ GCC_except_table5500
+ GCC_except_table5514
+ GCC_except_table552
+ GCC_except_table5526
+ GCC_except_table554
+ GCC_except_table5549
+ GCC_except_table5561
+ GCC_except_table5566
+ GCC_except_table5656
+ GCC_except_table5659
+ GCC_except_table5668
+ GCC_except_table5693
+ GCC_except_table5758
+ GCC_except_table5766
+ GCC_except_table5781
+ GCC_except_table5880
+ GCC_except_table5887
+ GCC_except_table5888
+ GCC_except_table5889
+ GCC_except_table5890
+ GCC_except_table5891
+ GCC_except_table5894
+ GCC_except_table5895
+ GCC_except_table5898
+ GCC_except_table590
+ GCC_except_table5901
+ GCC_except_table5902
+ GCC_except_table5904
+ GCC_except_table5907
+ GCC_except_table5908
+ GCC_except_table5909
+ GCC_except_table5910
+ GCC_except_table5911
+ GCC_except_table5912
+ GCC_except_table5913
+ GCC_except_table5914
+ GCC_except_table5924
+ GCC_except_table5925
+ GCC_except_table5937
+ GCC_except_table5953
+ GCC_except_table5954
+ GCC_except_table5959
+ GCC_except_table5960
+ GCC_except_table5962
+ GCC_except_table5965
+ GCC_except_table5966
+ GCC_except_table5970
+ GCC_except_table5973
+ GCC_except_table5974
+ GCC_except_table5976
+ GCC_except_table5977
+ GCC_except_table5980
+ GCC_except_table5982
+ GCC_except_table5984
+ GCC_except_table5985
+ GCC_except_table5986
+ GCC_except_table5987
+ GCC_except_table5988
+ GCC_except_table5992
+ GCC_except_table5998
+ GCC_except_table65
+ GCC_except_table658
+ GCC_except_table667
+ GCC_except_table6788
+ GCC_except_table689
+ GCC_except_table708
+ GCC_except_table7090
+ GCC_except_table7098
+ GCC_except_table7105
+ GCC_except_table7106
+ GCC_except_table7110
+ GCC_except_table7181
+ GCC_except_table7210
+ GCC_except_table7216
+ GCC_except_table7231
+ GCC_except_table7286
+ GCC_except_table7354
+ GCC_except_table7364
+ GCC_except_table7391
+ GCC_except_table7392
+ GCC_except_table7442
+ GCC_except_table7609
+ GCC_except_table7645
+ GCC_except_table7654
+ GCC_except_table7677
+ GCC_except_table7681
+ GCC_except_table7683
+ GCC_except_table7684
+ GCC_except_table7685
+ GCC_except_table7709
+ GCC_except_table7760
+ GCC_except_table7761
+ GCC_except_table7762
+ GCC_except_table7763
+ GCC_except_table7768
+ GCC_except_table7774
+ GCC_except_table7775
+ GCC_except_table7782
+ GCC_except_table7785
+ GCC_except_table7792
+ GCC_except_table7794
+ GCC_except_table7795
+ GCC_except_table7797
+ GCC_except_table7798
+ GCC_except_table7799
+ GCC_except_table7800
+ GCC_except_table7805
+ GCC_except_table7807
+ GCC_except_table7808
+ GCC_except_table7809
+ GCC_except_table7810
+ GCC_except_table7814
+ GCC_except_table7815
+ GCC_except_table7817
+ GCC_except_table7819
+ GCC_except_table782
+ GCC_except_table7821
+ GCC_except_table7823
+ GCC_except_table7829
+ GCC_except_table7832
+ GCC_except_table7836
+ GCC_except_table7837
+ GCC_except_table7839
+ GCC_except_table7840
+ GCC_except_table7841
+ GCC_except_table7842
+ GCC_except_table7843
+ GCC_except_table7845
+ GCC_except_table7846
+ GCC_except_table7847
+ GCC_except_table7848
+ GCC_except_table7849
+ GCC_except_table7850
+ GCC_except_table7851
+ GCC_except_table7852
+ GCC_except_table7853
+ GCC_except_table7854
+ GCC_except_table7855
+ GCC_except_table7856
+ GCC_except_table7857
+ GCC_except_table7858
+ GCC_except_table7859
+ GCC_except_table7860
+ GCC_except_table7861
+ GCC_except_table7862
+ GCC_except_table7962
+ GCC_except_table7991
+ GCC_except_table8076
+ GCC_except_table8270
+ GCC_except_table8285
+ GCC_except_table8322
+ GCC_except_table8329
+ GCC_except_table8382
+ GCC_except_table8427
+ GCC_except_table8571
+ GCC_except_table8576
+ GCC_except_table8579
+ GCC_except_table8646
+ GCC_except_table8941
+ GCC_except_table8945
+ GCC_except_table8981
+ GCC_except_table8985
+ GCC_except_table8987
+ GCC_except_table9050
+ GCC_except_table9064
+ GCC_except_table9104
+ GCC_except_table9136
+ GCC_except_table9137
+ GCC_except_table9205
+ GCC_except_table9394
+ GCC_except_table9404
+ GCC_except_table9405
+ GCC_except_table9407
+ GCC_except_table9408
+ GCC_except_table9569
+ GCC_except_table9596
+ GCC_except_table9620
+ GCC_except_table9628
+ GCC_except_table9752
+ GCC_except_table9791
+ _NUAssetPipelineOptionRawDecodeDraftMode
+ _NUControlOptionalityDescription
+ _NUEnumValueClassForValueType
+ _NUEnumValueTypeDescription
+ _NURawDecodeDraftModeAuto
+ _NURawDecodeDraftModeDisabled
+ _NURawDecodeDraftModeEnabled
+ _OBJC_CLASS_$_NUChannelContainsExpression
+ _OBJC_CLASS_$_NUChannelForceUnwrapExpression
+ _OBJC_CLASS_$_NUChannelNilCoalesceExpression
+ _OBJC_CLASS_$_NUStandardPreviewScalePolicy
+ _OBJC_CLASS_$__NURawDecodeCapability
+ _OBJC_IVAR_$_NUChannelControlFormat._descriptor
+ _OBJC_IVAR_$_NUCompoundDescriptor._identifier
+ _OBJC_IVAR_$_NUControlDescriptor._valueType
+ _OBJC_IVAR_$_NUEnumDescriptor._enumValueType
+ _OBJC_IVAR_$_NUEnumDescriptor._identifier
+ _OBJC_IVAR_$_NUNumberDescriptor._precision
+ _OBJC_IVAR_$_NUOptionalDescriptor._defaultValue
+ _OBJC_IVAR_$_NUOptionalDescriptor._optionality
+ _OBJC_IVAR_$_NUStandardPreviewScalePolicy._actualPolicy
+ _OBJC_IVAR_$__NUContainerPipeline._componentFormat
+ _OBJC_IVAR_$__NUContainerPipeline._componentInputPort
+ _OBJC_IVAR_$__NUContainerPipeline._componentOutputPort
+ _OBJC_IVAR_$__NULivePhotoRenderResult._image
+ _OBJC_IVAR_$__NUStyleEngineMemoryResource._metalCommandQueue
+ _OBJC_METACLASS_$_NUChannelContainsExpression
+ _OBJC_METACLASS_$_NUChannelForceUnwrapExpression
+ _OBJC_METACLASS_$_NUChannelNilCoalesceExpression
+ _OBJC_METACLASS_$_NUStandardPreviewScalePolicy
+ _OBJC_METACLASS_$__NURawDecodeCapability
+ __OBJC_$_CATEGORY_CIVector_$_NUControlDataRepresentable
+ __OBJC_$_CATEGORY_CLASS_METHODS_CIVector_$_NUControlDataRepresentable
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSArray_$_NUControlDataRepresentable
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSDictionary_$_NUControlDataRepresentable
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSNumber_$_NUControlDataRepresentable
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSString_$_NUControlDataRepresentable
+ __OBJC_$_CATEGORY_NSArray_$_NUControlDataRepresentable
+ __OBJC_$_CATEGORY_NSDictionary_$_NUControlDataRepresentable
+ __OBJC_$_CATEGORY_NSNull_$_NUControlDataRepresentable
+ __OBJC_$_CATEGORY_NSNumber_$_NUControlDataRepresentable
+ __OBJC_$_CATEGORY_NSObject_$_NUControlDataRepresentable
+ __OBJC_$_CATEGORY_NSString_$_NUControlDataRepresentable
+ __OBJC_$_CATEGORY_NSValue_$_NUControlDataRepresentable
+ __OBJC_$_CLASS_METHODS_NSObject(NUControlDataRepresentable|NUDigest|NURenderPipelineFunction|NUUtilities)
+ __OBJC_$_CLASS_METHODS_NSValue(NUControlDataRepresentable|NUDigest|NUGeometryExtensions)
+ __OBJC_$_CLASS_METHODS_NUAssetCapability(NURawDecode)
+ __OBJC_$_CLASS_METHODS_NUEnumDescriptor
+ __OBJC_$_CLASS_METHODS__NURawDecodeCapability
+ __OBJC_$_CLASS_PROP_LIST_NUEnumDescriptor
+ __OBJC_$_INSTANCE_METHODS_CIVector(NUControlDataRepresentable|NUDigest)
+ __OBJC_$_INSTANCE_METHODS_NSArray(NUControlDataRepresentable|NUDigest|NURenderPipelineFunction)
+ __OBJC_$_INSTANCE_METHODS_NSDictionary(NUControlDataRepresentable|NUDigest|NURenderPipelineFunction)
+ __OBJC_$_INSTANCE_METHODS_NSNull(NUControlDataRepresentable|NUDigest)
+ __OBJC_$_INSTANCE_METHODS_NSNumber(NUControlDataRepresentable|NUEnumValueRepresentable|NUSchemaAdditions)
+ __OBJC_$_INSTANCE_METHODS_NSObject(NUControlDataRepresentable|NUDigest|NURenderPipelineFunction|NUUtilities)
+ __OBJC_$_INSTANCE_METHODS_NSString(NUControlDataRepresentable|NUEnumValueRepresentable|NUDigest)
+ __OBJC_$_INSTANCE_METHODS_NSValue(NUControlDataRepresentable|NUDigest|NUGeometryExtensions)
+ __OBJC_$_INSTANCE_METHODS_NUCIImageSourceDefinition(NUAssetLoader|NodeProvider)
+ __OBJC_$_INSTANCE_METHODS_NUChannelContainsExpression
+ __OBJC_$_INSTANCE_METHODS_NUChannelForceUnwrapExpression
+ __OBJC_$_INSTANCE_METHODS_NUChannelNilCoalesceExpression
+ __OBJC_$_INSTANCE_METHODS_NUFileSourceDefinition(NUAssetLoader|NodeProvider)
+ __OBJC_$_INSTANCE_METHODS_NULivePhotoSourceDefinition(NUAssetLoader|NodeProvider)
+ __OBJC_$_INSTANCE_METHODS_NUMultipleSourceDefinition(NUAssetLoader|NodeProvider)
+ __OBJC_$_INSTANCE_METHODS_NURenderJob(DebugAdditions|Media|RendererSupport)
+ __OBJC_$_INSTANCE_METHODS_NUSourceDefinition(NUAssetLoader|NodeProvider)
+ __OBJC_$_INSTANCE_METHODS_NUStandardPreviewScalePolicy
+ __OBJC_$_INSTANCE_METHODS_NUVideoDataSourceDefinition(NUAssetLoader|NodeProvider)
+ __OBJC_$_INSTANCE_METHODS__NURawDecodeCapability
+ __OBJC_$_INSTANCE_VARIABLES_NUStandardPreviewScalePolicy
+ __OBJC_$_INSTANCE_VARIABLES__NUContainerPipeline
+ __OBJC_$_PROP_LIST_NSObject_$_NUControlDataRepresentable
+ __OBJC_$_PROP_LIST_NUStandardPreviewScalePolicy
+ __OBJC_$_PROP_LIST__NUContainerPipeline
+ __OBJC_$_PROTOCOL_REFS_NUEnumValueRepresentable
+ __OBJC_CATEGORY_PROTOCOLS_$_NSObject_$_NUControlDataRepresentable
+ __OBJC_CLASS_PROTOCOLS_$_NSNumber(NUControlDataRepresentable|NUEnumValueRepresentable|NUSchemaAdditions)
+ __OBJC_CLASS_PROTOCOLS_$_NSString(NUControlDataRepresentable|NUEnumValueRepresentable|NUDigest)
+ __OBJC_CLASS_PROTOCOLS_$_NUStandardPreviewScalePolicy
+ __OBJC_CLASS_RO_$_NUChannelContainsExpression
+ __OBJC_CLASS_RO_$_NUChannelForceUnwrapExpression
+ __OBJC_CLASS_RO_$_NUChannelNilCoalesceExpression
+ __OBJC_CLASS_RO_$_NUStandardPreviewScalePolicy
+ __OBJC_CLASS_RO_$__NURawDecodeCapability
+ __OBJC_LABEL_PROTOCOL_$_NUEnumValueRepresentable
+ __OBJC_METACLASS_RO_$_NUChannelContainsExpression
+ __OBJC_METACLASS_RO_$_NUChannelForceUnwrapExpression
+ __OBJC_METACLASS_RO_$_NUChannelNilCoalesceExpression
+ __OBJC_METACLASS_RO_$_NUStandardPreviewScalePolicy
+ __OBJC_METACLASS_RO_$__NURawDecodeCapability
+ __OBJC_PROTOCOL_$_NUEnumValueRepresentable
+ ___101+[_NUStyleEngineMemoryResource usingSharedMemoryResourceForMetalCommandQueue:withDescriptor:perform:]_block_invoke
+ ___26-[NURunQueue synchronize:]_block_invoke
+ ___41-[NURenderContext _dequeueRateLimitedJob]_block_invoke
+ ___51-[NUGlobalSettings standardPreviewSizeInMegapixels]_block_invoke
+ ___51-[_NURawProfilePipeline_v0 buildWithOptions:error:]_block_invoke_2
+ ___51-[_NURawProfilePipeline_v1 buildWithOptions:error:]_block_invoke_2
+ ___67-[_NUHDRToneMapLearnPipeline _genericInputPortsMatchingOutputPort:]_block_invoke
+ ___67-[_NUHDRToneMapLearnPipeline _genericOutputPortsMatchingInputPort:]_block_invoke
+ ___70-[NUEnumDescriptor initWithEnumValueType:values:identifier:valueType:]_block_invoke
+ ___71-[_NUPipeline processContainer:componentFormat:forEachComponent:error:]_block_invoke
+ ___77-[_NUPipeline addContainerPipelineWithContainerFormat:componentFormat:block:]_block_invoke
+ ___79-[_NUPipeline processContainerPort:componentFormat:forEachComponentPort:error:]_block_invoke
+ ___block_descriptor_32_e28_B32?0"NURenderJob"8Q16^B24l
+ ___block_descriptor_40_e8_32bs_e73_"NUChannelPortRef"32?0"_NUContainerPipeline"8"NUChannelPortRef"16^24l
+ ___block_descriptor_40_e8_32s_e35_"_NUChannelPort"16?0"NUChannel"8l
+ ___block_descriptor_40_e8_B16?08lu32l8
+ ___block_descriptor_56_e8_32s40r48r_e42_v32?0"NSString"8"NUChannelFormat"16^B24l
+ _associated conformance So20NURawDecodeDraftModeaSHSCSQ
+ _associated conformance So20NURawDecodeDraftModeas12CaseIterable12NeutrinoCore8AllCasessACP_Sl
+ _associated conformance So20NURawDecodeDraftModeas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So20NURawDecodeDraftModeas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _kCMMetadataBaseDataType_ISOLatin1
+ _kCMMetadataBaseDataType_MacRoman
+ _kCMMetadataBaseDataType_RawData
+ _kCMMetadataBaseDataType_UTF16
+ _kCMMetadataBaseDataType_UTF8
+ _objc_msgSend$_formatForInput:
+ _objc_msgSend$_opaqueValueOfClass:
+ _objc_msgSend$_untypedValue
+ _objc_msgSend$addCapability:value:
+ _objc_msgSend$addContainerPipelineWithContainerFormat:componentFormat:block:error:
+ _objc_msgSend$canAcceptDataWithOptionalDescriptor:
+ _objc_msgSend$canAcceptOptionalDataWithFormat:
+ _objc_msgSend$capabilityMarkerFormat
+ _objc_msgSend$colorSpaceFormat
+ _objc_msgSend$componentInputPort
+ _objc_msgSend$componentOutputPort
+ _objc_msgSend$descriptorWithValueType:
+ _objc_msgSend$dictionaryWithCapacity:
+ _objc_msgSend$enforceValidValue:
+ _objc_msgSend$enumValueType
+ _objc_msgSend$equal:
+ _objc_msgSend$forceUnwrap:
+ _objc_msgSend$geometryValue
+ _objc_msgSend$initWithContainerFormat:componentFormat:
+ _objc_msgSend$initWithDescriptor:optionality:validatedDefaultValue:
+ _objc_msgSend$initWithElement:min:max:valueType:
+ _objc_msgSend$initWithElement:size:valueType:
+ _objc_msgSend$initWithEnumValueType:values:identifier:valueType:
+ _objc_msgSend$initWithIdentifier:valueType:
+ _objc_msgSend$initWithIntegerValues:identifier:
+ _objc_msgSend$initWithNumberType:min:max:precision:valueType:
+ _objc_msgSend$initWithProperties:identifier:
+ _objc_msgSend$initWithProperties:identifier:valueType:
+ _objc_msgSend$initWithStringValues:identifier:
+ _objc_msgSend$initWithValueType:
+ _objc_msgSend$insertContainerMapAt:containerFormat:componentFormat:block:error:
+ _objc_msgSend$insertContainerMapAt:input:componentFormat:block:error:
+ _objc_msgSend$isEqualToContainsExpression:
+ _objc_msgSend$isEqualToEnumDescriptor:
+ _objc_msgSend$isEqualToNilCoalesceExpression:
+ _objc_msgSend$isValue:equalToValue:
+ _objc_msgSend$metadataValue
+ _objc_msgSend$opaque:identifier:
+ _objc_msgSend$opaqueDataWithValue:identifier:
+ _objc_msgSend$opaqueFormat:
+ _objc_msgSend$opaqueStringValue
+ _objc_msgSend$opaqueValue
+ _objc_msgSend$optionality
+ _objc_msgSend$orientationDescriptor
+ _objc_msgSend$orientationIdentifier
+ _objc_msgSend$precision
+ _objc_msgSend$processContainer:componentFormat:forEachComponent:error:
+ _objc_msgSend$processContainerPort:componentFormat:forEachComponentPort:error:
+ _objc_msgSend$rawForceDraftModeWithOptions:
+ _objc_msgSend$rectangleValue
+ _objc_msgSend$setMetalCommandQueue:
+ _objc_msgSend$standardPreviewSizeInMegapixels
+ _objc_msgSend$stringEnumValue
+ _objc_msgSend$synchronize:
+ _objc_msgSend$timeValue
+ _objc_msgSend$unavailableOptionalWithDescriptor:
+ _objc_msgSend$usingSharedMemoryResourceForMetalCommandQueue:withDescriptor:perform:
+ _objc_msgSend$validBoolValue:
+ _objc_msgSend$validDoubleValue:
+ _objc_msgSend$validIntegerValue:
+ _objc_msgSend$valueOfType:
+ _symbolic Say_____G So20NURawDecodeDraftModea
+ _symbolic _____ So20NURawDecodeDraftModea
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So20NURawDecodeDraftModea
+ _type_layout_string So20NURawDecodeDraftModea
+ _type_layout_string So7NUScalea
- +[NUAssetCapability rawDecodeCapabilityFormat]
- +[NUAssetCapability rawDecode]
- +[NUChannel controlChannelWithSchema:]
- +[NUChannel controlChannelWithSchema:name:]
- +[NUChannel controlChannelWithSetting:name:]
- +[NUChannelControlData controlDataWithAdjustment:]
- +[NUChannelControlData controlDataWithComposition:]
- +[NUChannelControlData controlDataWithSetting:value:]
- +[NUChannelControlData controlDataWithSource:]
- +[NUChannelControlFormat controlFormatWithSchema:]
- +[NUChannelControlFormat controlFormatWithSetting:]
- +[NUChannelData adjustment:]
- +[NUChannelData composition:]
- +[_NUStyleEngineMemoryResource usingSharedMemoryResourceForDevice:withDescriptor:perform:]
- -[NUChannelArrayData value]
- -[NUChannelControlData initWithData:schema:]
- -[NUChannelControlData initWithSetting:value:]
- -[NUChannelControlData value]
- -[NUChannelControlFormat controlType]
- -[NUChannelControlFormat dataModel]
- -[NUChannelControlFormat descriptor:canAcceptSetting:]
- -[NUChannelControlFormat initWithControlType:dataModel:]
- -[NUChannelControlFormat initWithControlType:dataModel:valueType:]
- -[NUChannelControlFormat setting:canAcceptDescriptor:]
- -[NUChannelData value]
- -[NUChannelElementData value]
- -[NUChannelExpressionData value]
- -[NUChannelMediaData value]
- -[NUChannelMetadata value]
- -[NUChannelNullData value]
- -[NUControlDescriptor initWithAttributes:]
- -[NUOptionalDescriptor descriptorDefault]
- -[_NUAsset addCapability:data:]
- -[_NUContainerPipeline init]
- -[_NUPipeline addContainerPipeline:]
- -[_NUPipeline addContainerPipeline:error:]
- -[_NUPipeline processContainer:forEachComponent:error:]
- -[_NUPipeline processContainerPort:forEachComponentPort:error:]
- GCC_except_table10017
- GCC_except_table10024
- GCC_except_table10102
- GCC_except_table10150
- GCC_except_table10174
- GCC_except_table10175
- GCC_except_table10179
- GCC_except_table10180
- GCC_except_table10181
- GCC_except_table10182
- GCC_except_table10189
- GCC_except_table10190
- GCC_except_table10199
- GCC_except_table10209
- GCC_except_table10215
- GCC_except_table10216
- GCC_except_table10217
- GCC_except_table10219
- GCC_except_table10221
- GCC_except_table10224
- GCC_except_table10225
- GCC_except_table10226
- GCC_except_table10298
- GCC_except_table10308
- GCC_except_table105
- GCC_except_table10523
- GCC_except_table10524
- GCC_except_table10530
- GCC_except_table10531
- GCC_except_table10533
- GCC_except_table10534
- GCC_except_table106
- GCC_except_table10631
- GCC_except_table10632
- GCC_except_table10635
- GCC_except_table10636
- GCC_except_table10637
- GCC_except_table10638
- GCC_except_table10639
- GCC_except_table10640
- GCC_except_table10642
- GCC_except_table10645
- GCC_except_table10646
- GCC_except_table10648
- GCC_except_table10649
- GCC_except_table10650
- GCC_except_table10652
- GCC_except_table10653
- GCC_except_table10664
- GCC_except_table10669
- GCC_except_table10670
- GCC_except_table10671
- GCC_except_table10672
- GCC_except_table10674
- GCC_except_table10675
- GCC_except_table10676
- GCC_except_table10677
- GCC_except_table10679
- GCC_except_table10680
- GCC_except_table10681
- GCC_except_table10682
- GCC_except_table10683
- GCC_except_table10684
- GCC_except_table10687
- GCC_except_table10690
- GCC_except_table10691
- GCC_except_table10694
- GCC_except_table10697
- GCC_except_table10698
- GCC_except_table10706
- GCC_except_table10707
- GCC_except_table10708
- GCC_except_table10709
- GCC_except_table10710
- GCC_except_table10711
- GCC_except_table10713
- GCC_except_table10715
- GCC_except_table10716
- GCC_except_table10717
- GCC_except_table10722
- GCC_except_table10723
- GCC_except_table10724
- GCC_except_table10725
- GCC_except_table10726
- GCC_except_table10728
- GCC_except_table10729
- GCC_except_table10730
- GCC_except_table10731
- GCC_except_table10732
- GCC_except_table10733
- GCC_except_table10734
- GCC_except_table10735
- GCC_except_table10740
- GCC_except_table10741
- GCC_except_table10742
- GCC_except_table10743
- GCC_except_table10744
- GCC_except_table10745
- GCC_except_table108
- GCC_except_table10803
- GCC_except_table10854
- GCC_except_table109
- GCC_except_table10943
- GCC_except_table10947
- GCC_except_table1117
- GCC_except_table11455
- GCC_except_table11616
- GCC_except_table11618
- GCC_except_table11664
- GCC_except_table11718
- GCC_except_table11726
- GCC_except_table11733
- GCC_except_table11734
- GCC_except_table11738
- GCC_except_table1312
- GCC_except_table1316
- GCC_except_table1324
- GCC_except_table1325
- GCC_except_table1326
- GCC_except_table1329
- GCC_except_table1330
- GCC_except_table1333
- GCC_except_table1354
- GCC_except_table1363
- GCC_except_table1388
- GCC_except_table1392
- GCC_except_table1394
- GCC_except_table1395
- GCC_except_table1396
- GCC_except_table1406
- GCC_except_table1456
- GCC_except_table1458
- GCC_except_table1678
- GCC_except_table1692
- GCC_except_table1704
- GCC_except_table1727
- GCC_except_table173
- GCC_except_table1739
- GCC_except_table1744
- GCC_except_table1834
- GCC_except_table1837
- GCC_except_table1846
- GCC_except_table1871
- GCC_except_table1963
- GCC_except_table2091
- GCC_except_table2092
- GCC_except_table2093
- GCC_except_table2094
- GCC_except_table2095
- GCC_except_table2097
- GCC_except_table2122
- GCC_except_table2175
- GCC_except_table2285
- GCC_except_table2286
- GCC_except_table2762
- GCC_except_table2842
- GCC_except_table2988
- GCC_except_table3000
- GCC_except_table3163
- GCC_except_table3310
- GCC_except_table3390
- GCC_except_table3397
- GCC_except_table3398
- GCC_except_table3401
- GCC_except_table3402
- GCC_except_table3403
- GCC_except_table3406
- GCC_except_table3407
- GCC_except_table3410
- GCC_except_table3413
- GCC_except_table3414
- GCC_except_table3418
- GCC_except_table3421
- GCC_except_table3422
- GCC_except_table3423
- GCC_except_table3424
- GCC_except_table3425
- GCC_except_table3426
- GCC_except_table3427
- GCC_except_table3428
- GCC_except_table3436
- GCC_except_table3441
- GCC_except_table3442
- GCC_except_table3447
- GCC_except_table3454
- GCC_except_table3470
- GCC_except_table3471
- GCC_except_table3476
- GCC_except_table3477
- GCC_except_table3479
- GCC_except_table3482
- GCC_except_table3483
- GCC_except_table3487
- GCC_except_table349
- GCC_except_table3490
- GCC_except_table3491
- GCC_except_table3494
- GCC_except_table3495
- GCC_except_table3498
- GCC_except_table3500
- GCC_except_table3502
- GCC_except_table3503
- GCC_except_table3504
- GCC_except_table3505
- GCC_except_table3506
- GCC_except_table3510
- GCC_except_table3516
- GCC_except_table359
- GCC_except_table376
- GCC_except_table4083
- GCC_except_table4154
- GCC_except_table4158
- GCC_except_table4160
- GCC_except_table421
- GCC_except_table4300
- GCC_except_table4310
- GCC_except_table4311
- GCC_except_table4318
- GCC_except_table4323
- GCC_except_table4328
- GCC_except_table4351
- GCC_except_table4358
- GCC_except_table4363
- GCC_except_table4365
- GCC_except_table449
- GCC_except_table4492
- GCC_except_table4493
- GCC_except_table4494
- GCC_except_table4497
- GCC_except_table4498
- GCC_except_table4499
- GCC_except_table4504
- GCC_except_table4506
- GCC_except_table4511
- GCC_except_table4512
- GCC_except_table4513
- GCC_except_table4515
- GCC_except_table4517
- GCC_except_table4534
- GCC_except_table455
- GCC_except_table4595
- GCC_except_table4596
- GCC_except_table4599
- GCC_except_table4600
- GCC_except_table4605
- GCC_except_table4606
- GCC_except_table4609
- GCC_except_table4610
- GCC_except_table4611
- GCC_except_table4612
- GCC_except_table4613
- GCC_except_table4614
- GCC_except_table4615
- GCC_except_table4617
- GCC_except_table4623
- GCC_except_table4627
- GCC_except_table4631
- GCC_except_table4635
- GCC_except_table4642
- GCC_except_table4644
- GCC_except_table4645
- GCC_except_table4720
- GCC_except_table506
- GCC_except_table5155
- GCC_except_table5161
- GCC_except_table5164
- GCC_except_table5174
- GCC_except_table5178
- GCC_except_table5179
- GCC_except_table5193
- GCC_except_table5303
- GCC_except_table5407
- GCC_except_table5410
- GCC_except_table5412
- GCC_except_table5451
- GCC_except_table5533
- GCC_except_table5825
- GCC_except_table593
- GCC_except_table5955
- GCC_except_table5991
- GCC_except_table5993
- GCC_except_table5995
- GCC_except_table6000
- GCC_except_table6009
- GCC_except_table6010
- GCC_except_table6014
- GCC_except_table6050
- GCC_except_table6071
- GCC_except_table6092
- GCC_except_table6097
- GCC_except_table6116
- GCC_except_table6118
- GCC_except_table6119
- GCC_except_table6124
- GCC_except_table6125
- GCC_except_table6127
- GCC_except_table6128
- GCC_except_table6142
- GCC_except_table6155
- GCC_except_table6158
- GCC_except_table6159
- GCC_except_table6160
- GCC_except_table6162
- GCC_except_table6165
- GCC_except_table6166
- GCC_except_table6167
- GCC_except_table6168
- GCC_except_table6169
- GCC_except_table6171
- GCC_except_table6172
- GCC_except_table6173
- GCC_except_table6174
- GCC_except_table6175
- GCC_except_table6176
- GCC_except_table6177
- GCC_except_table6178
- GCC_except_table6179
- GCC_except_table6180
- GCC_except_table6181
- GCC_except_table6182
- GCC_except_table6183
- GCC_except_table6188
- GCC_except_table6189
- GCC_except_table6195
- GCC_except_table6196
- GCC_except_table620
- GCC_except_table6202
- GCC_except_table6203
- GCC_except_table6205
- GCC_except_table6206
- GCC_except_table6207
- GCC_except_table6208
- GCC_except_table6209
- GCC_except_table6214
- GCC_except_table6215
- GCC_except_table6216
- GCC_except_table6217
- GCC_except_table6219
- GCC_except_table6220
- GCC_except_table6224
- GCC_except_table6225
- GCC_except_table6226
- GCC_except_table6227
- GCC_except_table6228
- GCC_except_table6229
- GCC_except_table6230
- GCC_except_table6231
- GCC_except_table6233
- GCC_except_table6235
- GCC_except_table6238
- GCC_except_table6239
- GCC_except_table6240
- GCC_except_table6241
- GCC_except_table6242
- GCC_except_table6244
- GCC_except_table6246
- GCC_except_table6247
- GCC_except_table6249
- GCC_except_table6250
- GCC_except_table6358
- GCC_except_table6362
- GCC_except_table6422
- GCC_except_table644
- GCC_except_table6454
- GCC_except_table6455
- GCC_except_table6493
- GCC_except_table6499
- GCC_except_table6507
- GCC_except_table6532
- GCC_except_table654
- GCC_except_table6612
- GCC_except_table6624
- GCC_except_table6629
- GCC_except_table6636
- GCC_except_table6654
- GCC_except_table6672
- GCC_except_table6675
- GCC_except_table6676
- GCC_except_table6680
- GCC_except_table6681
- GCC_except_table6785
- GCC_except_table6794
- GCC_except_table6814
- GCC_except_table6831
- GCC_except_table6905
- GCC_except_table6971
- GCC_except_table6976
- GCC_except_table6979
- GCC_except_table7002
- GCC_except_table7046
- GCC_except_table7189
- GCC_except_table7265
- GCC_except_table7280
- GCC_except_table7281
- GCC_except_table7282
- GCC_except_table7295
- GCC_except_table7296
- GCC_except_table7297
- GCC_except_table7298
- GCC_except_table7313
- GCC_except_table7314
- GCC_except_table7328
- GCC_except_table7329
- GCC_except_table7334
- GCC_except_table7374
- GCC_except_table7447
- GCC_except_table7448
- GCC_except_table7452
- GCC_except_table7454
- GCC_except_table7458
- GCC_except_table7460
- GCC_except_table7462
- GCC_except_table7463
- GCC_except_table7467
- GCC_except_table7471
- GCC_except_table7472
- GCC_except_table7475
- GCC_except_table7476
- GCC_except_table7477
- GCC_except_table7479
- GCC_except_table7480
- GCC_except_table7482
- GCC_except_table7483
- GCC_except_table7553
- GCC_except_table7590
- GCC_except_table7629
- GCC_except_table7630
- GCC_except_table7680
- GCC_except_table8390
- GCC_except_table8393
- GCC_except_table8463
- GCC_except_table8606
- GCC_except_table8611
- GCC_except_table8614
- GCC_except_table8616
- GCC_except_table8621
- GCC_except_table8635
- GCC_except_table8637
- GCC_except_table8638
- GCC_except_table8643
- GCC_except_table8644
- GCC_except_table8664
- GCC_except_table8671
- GCC_except_table8672
- GCC_except_table8673
- GCC_except_table8674
- GCC_except_table8687
- GCC_except_table8876
- GCC_except_table8923
- GCC_except_table9302
- GCC_except_table9387
- GCC_except_table95
- GCC_except_table9565
- GCC_except_table9759
- GCC_except_table9774
- GCC_except_table9811
- GCC_except_table9818
- GCC_except_table9858
- GCC_except_table9859
- GCC_except_table9860
- GCC_except_table9861
- GCC_except_table9866
- GCC_except_table9872
- GCC_except_table9873
- GCC_except_table9880
- GCC_except_table9883
- GCC_except_table9890
- GCC_except_table9892
- GCC_except_table9893
- GCC_except_table9895
- GCC_except_table9896
- GCC_except_table9897
- GCC_except_table9898
- GCC_except_table9903
- GCC_except_table9905
- GCC_except_table9906
- GCC_except_table9907
- GCC_except_table9908
- GCC_except_table9912
- GCC_except_table9913
- GCC_except_table9915
- GCC_except_table9917
- GCC_except_table9919
- GCC_except_table9921
- GCC_except_table9927
- GCC_except_table9930
- GCC_except_table9934
- GCC_except_table9935
- GCC_except_table9937
- GCC_except_table9938
- GCC_except_table9939
- GCC_except_table9940
- GCC_except_table9941
- GCC_except_table9943
- GCC_except_table9944
- GCC_except_table9945
- GCC_except_table9946
- GCC_except_table9947
- GCC_except_table9948
- GCC_except_table9949
- GCC_except_table9950
- GCC_except_table9951
- GCC_except_table9952
- GCC_except_table9953
- GCC_except_table9954
- GCC_except_table9955
- GCC_except_table9956
- GCC_except_table9957
- GCC_except_table9958
- GCC_except_table9959
- GCC_except_table9960
- _NUChannelControlTypeDescription
- _OBJC_CLASS_$_NSOrderedSet
- _OBJC_IVAR_$_NUChannelControlFormat._controlType
- _OBJC_IVAR_$_NUChannelControlFormat._dataModel
- _OBJC_IVAR_$_NUOptionalDescriptor._descriptorDefault
- __OBJC_$_CATEGORY_CIVector_$_NUDigest
- __OBJC_$_CATEGORY_INSTANCE_METHODS_CIVector_$_NUDigest
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSNumber_$_NUSchemaAdditions
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSString_$_NUDigest
- __OBJC_$_CATEGORY_NSArray_$_NUDigest
- __OBJC_$_CATEGORY_NSDictionary_$_NUDigest
- __OBJC_$_CATEGORY_NSNull_$_NUDigest
- __OBJC_$_CATEGORY_NSNumber_$_NUSchemaAdditions
- __OBJC_$_CATEGORY_NSObject_$_NUDigest
- __OBJC_$_CATEGORY_NSString_$_NUDigest
- __OBJC_$_CATEGORY_NSValue_$_NUDigest
- __OBJC_$_CLASS_METHODS_NSObject(NUDigest|NURenderPipelineFunction|NUControlDataRepresentable|NUUtilities)
- __OBJC_$_CLASS_METHODS_NSValue(NUDigest|NUGeometryExtensions|NUControlDataRepresentable)
- __OBJC_$_CLASS_METHODS_NUAssetCapability
- __OBJC_$_CLASS_PROP_LIST_NUAssetCapability
- __OBJC_$_INSTANCE_METHODS_NSArray(NUDigest|NURenderPipelineFunction|NUControlDataRepresentable)
- __OBJC_$_INSTANCE_METHODS_NSDictionary(NUDigest|NURenderPipelineFunction)
- __OBJC_$_INSTANCE_METHODS_NSNull(NUDigest|NUControlDataRepresentable)
- __OBJC_$_INSTANCE_METHODS_NSObject(NUDigest|NURenderPipelineFunction|NUControlDataRepresentable|NUUtilities)
- __OBJC_$_INSTANCE_METHODS_NSValue(NUDigest|NUGeometryExtensions|NUControlDataRepresentable)
- __OBJC_$_INSTANCE_METHODS_NUCIImageSourceDefinition(NodeProvider|NUAssetLoader)
- __OBJC_$_INSTANCE_METHODS_NUFileSourceDefinition(NodeProvider|NUAssetLoader)
- __OBJC_$_INSTANCE_METHODS_NULivePhotoSourceDefinition(NodeProvider|NUAssetLoader)
- __OBJC_$_INSTANCE_METHODS_NUMultipleSourceDefinition(NodeProvider|NUAssetLoader)
- __OBJC_$_INSTANCE_METHODS_NURenderJob(Media|RendererSupport|DebugAdditions)
- __OBJC_$_INSTANCE_METHODS_NUSourceDefinition(NodeProvider|NUAssetLoader)
- __OBJC_$_INSTANCE_METHODS_NUVideoDataSourceDefinition(NodeProvider|NUAssetLoader)
- __OBJC_CLASS_PROTOCOLS_$_NSObject(NUDigest|NURenderPipelineFunction|NUControlDataRepresentable|NUUtilities)
- __OBJC_PROTOCOL_REFERENCE_$_NUMediaGeometry
- ___36-[_NUPipeline addContainerPipeline:]_block_invoke
- ___46+[NUAssetCapability rawDecodeCapabilityFormat]_block_invoke
- ___54-[NUChannelControlFormat setting:canAcceptDescriptor:]_block_invoke
- ___55-[_NUPipeline processContainer:forEachComponent:error:]_block_invoke
- ___63-[_NUPipeline processContainerPort:forEachComponentPort:error:]_block_invoke
- ___90+[_NUStyleEngineMemoryResource usingSharedMemoryResourceForDevice:withDescriptor:perform:]_block_invoke
- ___block_descriptor_32_e36_24?0"NSString"8"NUChannelData"16l
- ___block_descriptor_72_e8_32s40s48s56r64r_e42_v32?0"NSString"8"NUChannelFormat"16^B24l
- _objc_msgSend$addCapability:data:
- _objc_msgSend$addContainerPipeline:error:
- _objc_msgSend$controlChannelWithSchema:name:
- _objc_msgSend$controlChannelWithSetting:name:
- _objc_msgSend$controlDataWithAdjustment:
- _objc_msgSend$controlDataWithComposition:
- _objc_msgSend$controlDataWithSetting:value:
- _objc_msgSend$controlFormatWithSchema:
- _objc_msgSend$controlFormatWithSetting:
- _objc_msgSend$convertedToFormat:
- _objc_msgSend$dataModel
- _objc_msgSend$descriptor:canAcceptSetting:
- _objc_msgSend$descriptorDefault
- _objc_msgSend$initWithControlType:dataModel:
- _objc_msgSend$initWithControlType:dataModel:valueType:
- _objc_msgSend$initWithData:schema:
- _objc_msgSend$initWithDimension:attributes:
- _objc_msgSend$initWithMinimum:maximum:attributes:
- _objc_msgSend$initWithSetting:value:
- _objc_msgSend$integer:
- _objc_msgSend$isNotNil:
- _objc_msgSend$orderedSetWithArray:
- _objc_msgSend$outputMatching:
- _objc_msgSend$processContainer:forEachComponent:error:
- _objc_msgSend$processContainerPort:forEachComponentPort:error:
- _objc_msgSend$setting:canAcceptDescriptor:
- _objc_msgSend$usingSharedMemoryResourceForDevice:withDescriptor:perform:
- _rawDecodeCapabilityFormat.format
- _rawDecodeCapabilityFormat.onceToken
- _type_layout_string So12NUPixelPointa
- _type_layout_string So13NUChannelNamea
CStrings:
+ "%@(%@, default:%@)"
+ "(%@!)"
+ "(%@??%@)"
+ "(%@∋%@)"
+ "+[CIVector(NUControlDataRepresentable) nu_valueFromControlData:error:]"
+ "+[NSArray(NUControlDataRepresentable) nu_valueFromControlData:error:]"
+ "+[NSDictionary(NUControlDataRepresentable) nu_valueFromControlData:error:]"
+ "+[NSNumber(NUControlDataRepresentable) nu_valueFromControlData:error:]"
+ "+[NSObject(NUControlDataRepresentable) nu_valueFromControlData:error:]"
+ "+[NSString(NUControlDataRepresentable) nu_valueFromControlData:error:]"
+ "+[NSValue(NUControlDataRepresentable) nu_valueFromControlData:error:]"
+ "+[NUChannelControlData opaqueDataWithValue:identifier:]"
+ "+[NUChannelData orientation:]"
+ "+[NUChannelExpression forceUnwrap:]"
+ "+[NUOptionalDescriptor unavailableOptionalWithDescriptor:defaultValue:]"
+ "-[NUArrayDescriptor initWithElement:min:max:valueType:]"
+ "-[NUArrayDescriptor initWithValueType:]"
+ "-[NUChannelContainsExpression evaluateWithLeftData:rightData:outputFormat:error:]"
+ "-[NUChannelControlData valueOfType:]"
+ "-[NUChannelControlFormat initWithDescriptor:valueType:]"
+ "-[NUChannelData _untypedValue]"
+ "-[NUChannelData valueOfType:]"
+ "-[NUChannelFormat canAcceptOptionalDataWithFormat:]"
+ "-[NUCompoundDescriptor initWithProperties:identifier:valueType:]"
+ "-[NUCompoundDescriptor initWithValueType:]"
+ "-[NUControlDescriptor descriptorWithValueType:]"
+ "-[NUControlDescriptor validate:error:]"
+ "-[NUEnumDescriptor initWithEnumValueType:values:identifier:valueType:]"
+ "-[NUEnumDescriptor initWithValueType:]"
+ "-[NUMediaGeometryDescriptor initWithProperties:identifier:]"
+ "-[NUMediaGeometryDescriptor initWithProperties:identifier:valueType:]"
+ "-[NUNumberDescriptor initWithNumberType:min:max:precision:valueType:]"
+ "-[NUNumberDescriptor initWithValueType:]"
+ "-[NUNumberDescriptor isValue:equalToValue:]"
+ "-[NUOpaqueDescriptor initWithIdentifier:valueType:]"
+ "-[NUOpaqueDescriptor initWithValueType:]"
+ "-[NUOptionalDescriptor initWithDescriptor:optionality:validatedDefaultValue:]"
+ "-[NUOptionalDescriptor initWithValueType:]"
+ "-[NUVectorDescriptor initWithElement:size:valueType:]"
+ "-[NUVectorDescriptor initWithValueType:]"
+ "-[_NUContainerPipeline _addInputChannel:]"
+ "-[_NUContainerPipeline _addOutputChannel:]"
+ "-[_NUContainerPipeline initWithContainerFormat:componentFormat:]"
+ "-[_NUPipeline addContainerPipelineWithContainerFormat:componentFormat:block:]"
+ "-[_NUPipeline insertContainerMapAt:containerFormat:componentFormat:block:error:]"
+ "-[_NUPipeline insertContainerMapAt:input:componentFormat:block:error:]"
+ "-[_NUPipeline processContainer:componentFormat:forEachComponent:error:]"
+ "-[_NUPipeline processContainerPort:componentFormat:forEachComponentPort:error:]"
+ "<%@: %p identifier: %@ properties: %@>"
+ "<%@: %p identifier: %@ type: %@ values: %@>"
+ "<%@:%p descriptor:%@>"
+ "@\"NUChannelPortRef\"32@?0@\"_NUContainerPipeline\"8@\"NUChannelPortRef\"16^@24"
+ "@\"_NUChannelPort\"16@?0@\"NUChannel\"8"
+ "A descriptor is required"
+ "AVCameraCalibrationData"
+ "AVMetadataItems"
+ "Abstract descriptor"
+ "Array elements cannot be compared with right data"
+ "B32@?0@\"NURenderJob\"8Q16^B24"
+ "CGColorSpace"
+ "CGImageMetadata"
+ "CGImageProperties"
+ "CGImagePropertyOrientation"
+ "CVPixelFormatType"
+ "CancellationCheck"
+ "Cannot add input channels to a container pipeline"
+ "Cannot add output channels to a container pipeline"
+ "Cannot read %{public}@ as %{public}@: %{public}@"
+ "Cannot read %{public}@ as an opaque value: %{public}@"
+ "Cannot read %{public}@ as an opaque value: its descriptor describes %{public}@"
+ "Converted %@ is not a %@"
+ "Converted value is not an instance of the specified value type"
+ "Data"
+ "Descriptor does not describe a number"
+ "Descriptor does not describe a value type"
+ "Descriptor does not describe a vector"
+ "Descriptor does not describe an enum"
+ "Dictionary"
+ "Every value must be distinct"
+ "Every value must match the enumeration type"
+ "Expected container media input"
+ "Expression format is not compatible"
+ "Failed to connect container pipeline contents"
+ "Failed to convert array element"
+ "Failed to convert compound property"
+ "Failed to convert property value"
+ "Failed to get value for key"
+ "Failed to read array element"
+ "Failed to read compound property"
+ "Generic"
+ "Incompatible enum value type"
+ "Incompatible left input format, expected an array"
+ "Input array is optional"
+ "Invalid processor result"
+ "Invalid value (unavailable)"
+ "Missing data for input channel: %@"
+ "Missing required value"
+ "NU_STANDARD_PREVIEW_SIZE"
+ "String"
+ "Transform"
+ "Unexpectedly found nil while unwrapping an optional value"
+ "Value is not a dictionary"
+ "Value is not a number"
+ "Value is not a string"
+ "Value is not a value type"
+ "Value is not a vector"
+ "Value is not an array"
+ "Value must be nil"
+ "Vector does not have the expected number of components"
+ "Vector must have 4 components (rect)"
+ "`"
+ "add<%@,%@>"
+ "array<%@>"
+ "array[%@..%@]<%@>"
+ "array[%@..]<%@>"
+ "array[%@]<%@>"
+ "array[..%@]<%@>"
+ "availableVersions"
+ "com.apple.coreimage:"
+ "componentFormat != nil"
+ "componentFormat.componentMediaType != NUChannelMediaTypeUnspecified || componentFormat.temporality != NUChannelMediaTemporalityUnspecified"
+ "componentFormat.mediaType != NUChannelMediaTypeContainer"
+ "compound(%@)"
+ "compound(%@)=%@"
+ "containerFormat != nil"
+ "containerFormat.mediaType == NUChannelMediaTypeContainer"
+ "contains<%@,%@>"
+ "defaultValue != nil"
+ "defaultValue == nil || optionality != NUControlOptionalityRequired"
+ "disabled"
+ "enabled"
+ "enum:%@(%@)"
+ "expressionFormat"
+ "forceDraftMode"
+ "forceUnwrap<%@>"
+ "format.descriptor.isOptional"
+ "geometry"
+ "integer"
+ "nilCoalesce<%@,%@>"
+ "number:%@"
+ "number:%@[%@..%@]"
+ "number:%@[%@..]"
+ "number:%@[..%@]"
+ "opaque(%@)"
+ "optionalExpression != nil"
+ "otherValue != nil"
+ "otherwise"
+ "precision == nil || numberType == NUNumberTypeReal"
+ "rawDecodeDraftMode"
+ "resultData"
+ "string"
+ "unavailable"
+ "valueType != Nil"
+ "vector%lu[%@]"
- "((NUControlDescriptor *)format.dataModel).isOptional"
- "+[NUChannel controlChannelWithSchema:]"
- "+[NUChannel controlChannelWithSchema:name:]"
- "+[NUChannel controlChannelWithSetting:name:]"
- "+[NUChannelControlData controlDataWithAdjustment:]"
- "+[NUChannelControlData controlDataWithComposition:]"
- "+[NUChannelControlData controlDataWithSetting:value:]"
- "+[NUChannelControlData controlDataWithSource:]"
- "-[NUArrayDescriptor initWithElement:min:max:]"
- "-[NUChannelControlData initWithData:schema:]"
- "-[NUChannelControlData initWithSetting:value:]"
- "-[NUChannelControlFormat initWithControlType:dataModel:valueType:]"
- "-[NUChannelData value]"
- "-[NUCompoundDescriptor initWithProperties:]"
- "-[NUControlDescriptor initWithAttributes:]"
- "-[NUEnumDescriptor initWithValues:]"
- "-[NUNumberDescriptor initWithNumberType:min:max:]"
- "-[NUOpaqueDescriptor initWithIdentifier:]"
- "-[NUOptionalDescriptor initWithDescriptor:validatedDefaultValue:]"
- "-[NUVectorDescriptor initWithElement:size:]"
- "-[_NUPipeline addContainerPipeline:]"
- "-[_NUPipeline addContainerPipeline:error:]"
- "-[_NUPipeline processContainer:forEachComponent:error:]"
- "-[_NUPipeline processContainerPort:forEachComponentPort:error:]"
- "<%@: %p properties: %@>"
- "<%@:%p type:%@ model:%@>"
- "??"
- "Data format is not compatible"
- "Either a descriptor or a setting is required"
- "Failed to add RAW output channels"
- "Failed to connect RAW output channel"
- "Failed to convert subkey"
- "Failed to read intensity channel data"
- "Incompatible output format"
- "Invalid control format"
- "Invalid value is not of type string"
- "Mixed control formats"
- "Multiple inputs matching output component"
- "Object is not of a supported rect type"
- "Unsupported subchannel format %@:%@"
- "[format.dataModel isKindOfClass:NUControlDescriptor.class]"
- "add(%@,%@>"
- "dataModel != nil"
- "descriptor:%@"
- "descriptor:%@[%@..%@]"
- "descriptor:%@[%@..]"
- "descriptor:%@[..%@]"
- "descriptor:array"
- "descriptor:compound"
- "descriptor:enum%@"
- "descriptor:opaque(%@)"
- "descriptor:optional"
- "descriptor:rect"
- "descriptor:time"
- "descriptor:unknown"
- "descriptor:unknownNumber"
- "descriptor:vector[%@, %lu]"
- "faces"
- "inputFactor"
- "numberType != NUNumberTypeUnknown"
- "scheduler '%{public}@' coalescing job #%llu (stage: WaitDependencies, older of two)"
- "schema"
- "schema:%@"
- "setting != nil"
- "setting:%@"
```
