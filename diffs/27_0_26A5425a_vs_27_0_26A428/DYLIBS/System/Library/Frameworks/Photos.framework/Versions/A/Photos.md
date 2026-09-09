## Photos

> `/System/Library/Frameworks/Photos.framework/Versions/A/Photos`

```diff

 911.0.134.0.0
-  __TEXT.__text: 0x2f773c
-  __TEXT.__objc_methlist: 0x25dc4
-  __TEXT.__const: 0x1770
+  __TEXT.__text: 0x2fef14
+  __TEXT.__objc_methlist: 0x26024
+  __TEXT.__const: 0x17f8
   __TEXT.__dlopen_cstrs: 0x280
-  __TEXT.__constg_swiftt: 0x544
-  __TEXT.__swift5_typeref: 0x4cd
-  __TEXT.__swift5_reflstr: 0x161
-  __TEXT.__swift5_fieldmd: 0x1a8
+  __TEXT.__constg_swiftt: 0x67c
+  __TEXT.__swift5_typeref: 0x547
   __TEXT.__swift5_builtin: 0x3c
+  __TEXT.__swift5_reflstr: 0x191
+  __TEXT.__swift5_fieldmd: 0x23c
   __TEXT.__swift5_assocty: 0xd0
   __TEXT.__swift5_proto: 0x4c
-  __TEXT.__swift5_types: 0x34
+  __TEXT.__swift5_types: 0x44
   __TEXT.__swift5_capture: 0x198
-  __TEXT.__cstring: 0x31e7c
+  __TEXT.__cstring: 0x327c1
   __TEXT.__swift_as_entry: 0x10
   __TEXT.__swift_as_ret: 0x10
   __TEXT.__swift_as_cont: 0x18
-  __TEXT.__oslogstring: 0x21567
+  __TEXT.__oslogstring: 0x22520
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__gcc_except_tab: 0x9248
+  __TEXT.__gcc_except_tab: 0x9394
   __TEXT.__ustring: 0x1e
-  __TEXT.__unwind_info: 0x9598
-  __TEXT.__eh_frame: 0x4a0
+  __TEXT.__unwind_info: 0x9698
+  __TEXT.__eh_frame: 0x4d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x31d0
-  __DATA_CONST.__objc_classlist: 0xec0
+  __DATA_CONST.__const: 0x3218
+  __DATA_CONST.__objc_classlist: 0xed0
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x2d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x13db0
+  __DATA_CONST.__objc_selrefs: 0x13fb8
   __DATA_CONST.__objc_protorefs: 0x40
   __DATA_CONST.__objc_superrefs: 0xc20
-  __DATA_CONST.__objc_arraydata: 0x858
-  __DATA_CONST.__got: 0x2800
-  __AUTH_CONST.__const: 0xb488
-  __AUTH_CONST.__cfstring: 0x2c880
-  __AUTH_CONST.__objc_const: 0x40428
-  __AUTH_CONST.__objc_intobj: 0x2388
-  __AUTH_CONST.__objc_arrayobj: 0x7b0
-  __AUTH_CONST.__objc_doubleobj: 0x130
+  __DATA_CONST.__objc_arraydata: 0x878
+  __DATA_CONST.__got: 0x2878
+  __AUTH_CONST.__const: 0xb648
+  __AUTH_CONST.__cfstring: 0x2cc60
+  __AUTH_CONST.__objc_const: 0x40820
+  __AUTH_CONST.__objc_intobj: 0x2490
+  __AUTH_CONST.__objc_arrayobj: 0x7c8
+  __AUTH_CONST.__objc_doubleobj: 0x140
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_floatobj: 0x10
-  __AUTH_CONST.__auth_got: 0x1690
-  __AUTH.__objc_data: 0x50e8
-  __AUTH.__data: 0x180
-  __DATA.__objc_ivar: 0x3468
-  __DATA.__data: 0x2980
+  __AUTH_CONST.__auth_got: 0x16d8
+  __AUTH.__objc_data: 0x5138
+  __AUTH.__data: 0x3c0
+  __DATA.__objc_ivar: 0x34a0
+  __DATA.__data: 0x29c0
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x17a8
   __DATA.__common: 0x49

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 14714
-  Symbols:   33321
-  CStrings:  8609
+  Functions: 14828
+  Symbols:   33511
+  CStrings:  8689
 
Symbols:
+ +[PHAsset fetchProcessedProvenanceAssetWithOriginatingAssetIdentifier:options:]
+ +[PHAssetCreationMetadataCopyOptions shouldEmbedProvenanceIntoSharedRenderForAsset:shouldCopyProvenanceData:]
+ +[PHAssetCreationMetadataCopyOptions shouldProcessProvenanceForAsset:shouldCopyProvenanceData:]
+ +[PHAssetCreationMetadataCopyOptions shouldStripProvenanceForAsset:shouldCopyProvenanceData:]
+ +[PHAssetCreationRequest _creationRequestForProcessedProvenanceAssetFromUnprocessedProvenanceAsset:resourceBundle:processedProvenanceResourceURL:]
+ +[PHAssetCreationRequest _validateProvenanceStateForProcessing:]
+ +[PHAssetCreationRequest creationRequestForProcessedProvenanceAssetFromUnprocessedProvenanceAsset:resourceInfo:]
+ +[PHAssetCreationRequest processedProvenanceReplacementForSharingAsset:completionHandler:]
+ +[PHAssetCreationRequestPlaceholderSupport _processedProvenanceCarrierURLFromSourceAsset:]
+ +[PHAssetCreationRequestPlaceholderSupport _removeProvenanceSidecarResourcesFrom:byType:]
+ +[PHAssetExportRequest _adjustedProvenanceRenderURLToShareForAsset:options:fileURLs:]
+ +[PHAssetExportRequest _insertAssetWithProcessedProvenanceResourceURL:unprocessedAsset:]
+ +[PHAssetExportRequest _shouldCombineEditedProvenanceIntoRenderForAsset:options:fileURLs:]
+ +[PHImportAsset scanAssetsForProvenanceData:atEnd:]
+ +[PHImportAsset stripProvenanceExtensionFrompPath:]
+ +[PHResourceLocalAvailabilityRequest _shouldAddOriginalProvenanceResourceToResourcesToShareForAsset:shouldStripProvenance:]
+ -[PHAsset _setupProvenanceStateFromFetchDictionary:]
+ -[PHAsset isCinematicCapableVideo]
+ -[PHAsset provenanceState]
+ -[PHAssetCreationMetadataCopyOptions setShouldCopyProvenanceData:]
+ -[PHAssetCreationMetadataCopyOptions shouldCopyProvenanceData]
+ -[PHAssetCreationRequest _addProcessedProvenanceResourceToAssetResources:processedProvenanceResourceURL:unprocessedOriginal:error:]
+ -[PHAssetCreationRequest _cleanupTemporaryProvenanceFilesIfNecessary]
+ -[PHAssetCreationRequest _getOriginalResource:sidecarProvenanceResource:]
+ -[PHAssetCreationRequest _updateAssetResourcesWithProcessedProvenanceResource:]
+ -[PHAssetCreationRequest originalProvenanceAssetFilename]
+ -[PHAssetCreationRequest originalProvenanceAssetUUID]
+ -[PHAssetCreationRequest performAsyncPreprocessingWithCompletionHandler:]
+ -[PHAssetCreationRequest setOriginalProvenanceAssetFilename:]
+ -[PHAssetCreationRequest setOriginalProvenanceAssetUUID:]
+ -[PHAssetCreationRequest setUseMockProvenanceProcessingClientForUnitTestSupport:]
+ -[PHAssetCreationRequest useMockProvenanceProcessingClientForUnitTestSupport]
+ -[PHAssetCreationRequestPlaceholderSupport _shouldEmbedProvenanceIntoRenderForSourceAsset:]
+ -[PHAssetExportRequestOptions forceProvenanceMetadataBaking]
+ -[PHAssetExportRequestOptions setForceProvenanceMetadataBaking:]
+ -[PHAssetExportRequestOptions setShouldStripProvenance:]
+ -[PHAssetExportRequestOptions shouldStripProvenance]
+ -[PHAssetPTPProperties provenanceState]
+ -[PHAssetResourceCreationOptions hasProvenanceData]
+ -[PHAssetResourceCreationOptions setHasProvenanceData:]
+ -[PHExternalAssetResource hasProvenanceData]
+ -[PHImportAsset hasProvenanceMetadata]
+ -[PHImportAsset provenanceAsset]
+ -[PHImportAsset setProvenanceAsset:]
+ -[PHImportSource processPotentialProvenanceAsset:plusProvenanceDNG:]
+ -[PHPhotoLibrary(ContentProvenance) lastAvailableContentProvenanceLowerBoundTimestampData]
+ -[PHResourceLocalAvailabilityRequestOptions preferUncombinedProvenanceResources]
+ -[PHResourceLocalAvailabilityRequestOptions setPreferUncombinedProvenanceResources:]
+ -[PHResourceLocalAvailabilityRequestOptions setShouldStripProvenance:]
+ -[PHResourceLocalAvailabilityRequestOptions shouldStripProvenance]
+ GCC_except_table10202
+ GCC_except_table10203
+ GCC_except_table10204
+ GCC_except_table10205
+ GCC_except_table10206
+ GCC_except_table10207
+ GCC_except_table10208
+ GCC_except_table10209
+ GCC_except_table10210
+ GCC_except_table10211
+ GCC_except_table10212
+ GCC_except_table10213
+ GCC_except_table10214
+ GCC_except_table10215
+ GCC_except_table10216
+ GCC_except_table10217
+ GCC_except_table10218
+ GCC_except_table10219
+ GCC_except_table10220
+ GCC_except_table10221
+ GCC_except_table10222
+ GCC_except_table10223
+ GCC_except_table10224
+ GCC_except_table10225
+ GCC_except_table10226
+ GCC_except_table10227
+ GCC_except_table10228
+ GCC_except_table10229
+ GCC_except_table10230
+ GCC_except_table10231
+ GCC_except_table10232
+ GCC_except_table10233
+ GCC_except_table10234
+ GCC_except_table10235
+ GCC_except_table10236
+ GCC_except_table10237
+ GCC_except_table10238
+ GCC_except_table10239
+ GCC_except_table10240
+ GCC_except_table10241
+ GCC_except_table10242
+ GCC_except_table10243
+ GCC_except_table10244
+ GCC_except_table10245
+ GCC_except_table10246
+ GCC_except_table10247
+ GCC_except_table10248
+ GCC_except_table10249
+ GCC_except_table10250
+ GCC_except_table10251
+ GCC_except_table10252
+ GCC_except_table10253
+ GCC_except_table10254
+ GCC_except_table10255
+ GCC_except_table10256
+ GCC_except_table10257
+ GCC_except_table10258
+ GCC_except_table10259
+ GCC_except_table10260
+ GCC_except_table10261
+ GCC_except_table10262
+ GCC_except_table10263
+ GCC_except_table10374
+ GCC_except_table10383
+ GCC_except_table10384
+ GCC_except_table10385
+ GCC_except_table10386
+ GCC_except_table10387
+ GCC_except_table10388
+ GCC_except_table10400
+ GCC_except_table10418
+ GCC_except_table10451
+ GCC_except_table10452
+ GCC_except_table10453
+ GCC_except_table10454
+ GCC_except_table10455
+ GCC_except_table10465
+ GCC_except_table10483
+ GCC_except_table10484
+ GCC_except_table10485
+ GCC_except_table10486
+ GCC_except_table10487
+ GCC_except_table10488
+ GCC_except_table10489
+ GCC_except_table10490
+ GCC_except_table10491
+ GCC_except_table10529
+ GCC_except_table10530
+ GCC_except_table10534
+ GCC_except_table10554
+ GCC_except_table10561
+ GCC_except_table10643
+ GCC_except_table10736
+ GCC_except_table10904
+ GCC_except_table10924
+ GCC_except_table10927
+ GCC_except_table10928
+ GCC_except_table10954
+ GCC_except_table10956
+ GCC_except_table11046
+ GCC_except_table11064
+ GCC_except_table1129
+ GCC_except_table1147
+ GCC_except_table11583
+ GCC_except_table1174
+ GCC_except_table11740
+ GCC_except_table11743
+ GCC_except_table11750
+ GCC_except_table11758
+ GCC_except_table11762
+ GCC_except_table11764
+ GCC_except_table11768
+ GCC_except_table11774
+ GCC_except_table11880
+ GCC_except_table11900
+ GCC_except_table11902
+ GCC_except_table11904
+ GCC_except_table11906
+ GCC_except_table11941
+ GCC_except_table11990
+ GCC_except_table11997
+ GCC_except_table11999
+ GCC_except_table12001
+ GCC_except_table12007
+ GCC_except_table12044
+ GCC_except_table12175
+ GCC_except_table12201
+ GCC_except_table12213
+ GCC_except_table12255
+ GCC_except_table12269
+ GCC_except_table12355
+ GCC_except_table12359
+ GCC_except_table12400
+ GCC_except_table12404
+ GCC_except_table12413
+ GCC_except_table12414
+ GCC_except_table12421
+ GCC_except_table12459
+ GCC_except_table12466
+ GCC_except_table12476
+ GCC_except_table12481
+ GCC_except_table12531
+ GCC_except_table12623
+ GCC_except_table12626
+ GCC_except_table12632
+ GCC_except_table12634
+ GCC_except_table12674
+ GCC_except_table1268
+ GCC_except_table12693
+ GCC_except_table12704
+ GCC_except_table12766
+ GCC_except_table12769
+ GCC_except_table12777
+ GCC_except_table12783
+ GCC_except_table12785
+ GCC_except_table12850
+ GCC_except_table1287
+ GCC_except_table12928
+ GCC_except_table12932
+ GCC_except_table12936
+ GCC_except_table12973
+ GCC_except_table12997
+ GCC_except_table13004
+ GCC_except_table13134
+ GCC_except_table13146
+ GCC_except_table13241
+ GCC_except_table13308
+ GCC_except_table13514
+ GCC_except_table13593
+ GCC_except_table1362
+ GCC_except_table13635
+ GCC_except_table13684
+ GCC_except_table13694
+ GCC_except_table13714
+ GCC_except_table13729
+ GCC_except_table13757
+ GCC_except_table13759
+ GCC_except_table13772
+ GCC_except_table13774
+ GCC_except_table13776
+ GCC_except_table13795
+ GCC_except_table13941
+ GCC_except_table13952
+ GCC_except_table13979
+ GCC_except_table13985
+ GCC_except_table14001
+ GCC_except_table14071
+ GCC_except_table14073
+ GCC_except_table14119
+ GCC_except_table14121
+ GCC_except_table14145
+ GCC_except_table14148
+ GCC_except_table14302
+ GCC_except_table1456
+ GCC_except_table1481
+ GCC_except_table1527
+ GCC_except_table1602
+ GCC_except_table1702
+ GCC_except_table1804
+ GCC_except_table1808
+ GCC_except_table1834
+ GCC_except_table1839
+ GCC_except_table1853
+ GCC_except_table2046
+ GCC_except_table2048
+ GCC_except_table2050
+ GCC_except_table2052
+ GCC_except_table2059
+ GCC_except_table2066
+ GCC_except_table2068
+ GCC_except_table2082
+ GCC_except_table2134
+ GCC_except_table2136
+ GCC_except_table2138
+ GCC_except_table2140
+ GCC_except_table2142
+ GCC_except_table2144
+ GCC_except_table2147
+ GCC_except_table2149
+ GCC_except_table2158
+ GCC_except_table2160
+ GCC_except_table2163
+ GCC_except_table2165
+ GCC_except_table2167
+ GCC_except_table2196
+ GCC_except_table2198
+ GCC_except_table2201
+ GCC_except_table2204
+ GCC_except_table2244
+ GCC_except_table2312
+ GCC_except_table2317
+ GCC_except_table2331
+ GCC_except_table2345
+ GCC_except_table2385
+ GCC_except_table2558
+ GCC_except_table2571
+ GCC_except_table2599
+ GCC_except_table2616
+ GCC_except_table2635
+ GCC_except_table2645
+ GCC_except_table2682
+ GCC_except_table2687
+ GCC_except_table2749
+ GCC_except_table2854
+ GCC_except_table2865
+ GCC_except_table2867
+ GCC_except_table2873
+ GCC_except_table2881
+ GCC_except_table2913
+ GCC_except_table2993
+ GCC_except_table2999
+ GCC_except_table3004
+ GCC_except_table3017
+ GCC_except_table3030
+ GCC_except_table3032
+ GCC_except_table3039
+ GCC_except_table3169
+ GCC_except_table3173
+ GCC_except_table3176
+ GCC_except_table3243
+ GCC_except_table3251
+ GCC_except_table3286
+ GCC_except_table3290
+ GCC_except_table3295
+ GCC_except_table3419
+ GCC_except_table3456
+ GCC_except_table3462
+ GCC_except_table3465
+ GCC_except_table3490
+ GCC_except_table3503
+ GCC_except_table3507
+ GCC_except_table3521
+ GCC_except_table3539
+ GCC_except_table3540
+ GCC_except_table3557
+ GCC_except_table3566
+ GCC_except_table3663
+ GCC_except_table3670
+ GCC_except_table3691
+ GCC_except_table3693
+ GCC_except_table3695
+ GCC_except_table3742
+ GCC_except_table3770
+ GCC_except_table3801
+ GCC_except_table3803
+ GCC_except_table3821
+ GCC_except_table3823
+ GCC_except_table3826
+ GCC_except_table3986
+ GCC_except_table4020
+ GCC_except_table4028
+ GCC_except_table4030
+ GCC_except_table4045
+ GCC_except_table4048
+ GCC_except_table4050
+ GCC_except_table4083
+ GCC_except_table4088
+ GCC_except_table4089
+ GCC_except_table4356
+ GCC_except_table4363
+ GCC_except_table4396
+ GCC_except_table4418
+ GCC_except_table4421
+ GCC_except_table4426
+ GCC_except_table4431
+ GCC_except_table4442
+ GCC_except_table4446
+ GCC_except_table4467
+ GCC_except_table4480
+ GCC_except_table4481
+ GCC_except_table4541
+ GCC_except_table4866
+ GCC_except_table4876
+ GCC_except_table4936
+ GCC_except_table4940
+ GCC_except_table4942
+ GCC_except_table4945
+ GCC_except_table5015
+ GCC_except_table5020
+ GCC_except_table5053
+ GCC_except_table5183
+ GCC_except_table5187
+ GCC_except_table5534
+ GCC_except_table5565
+ GCC_except_table5611
+ GCC_except_table5637
+ GCC_except_table5670
+ GCC_except_table5675
+ GCC_except_table5699
+ GCC_except_table5703
+ GCC_except_table5707
+ GCC_except_table5729
+ GCC_except_table5735
+ GCC_except_table5739
+ GCC_except_table5753
+ GCC_except_table5756
+ GCC_except_table5759
+ GCC_except_table5782
+ GCC_except_table5817
+ GCC_except_table5838
+ GCC_except_table5849
+ GCC_except_table5900
+ GCC_except_table5934
+ GCC_except_table5943
+ GCC_except_table5947
+ GCC_except_table5959
+ GCC_except_table5992
+ GCC_except_table6021
+ GCC_except_table6048
+ GCC_except_table6050
+ GCC_except_table6063
+ GCC_except_table6132
+ GCC_except_table6210
+ GCC_except_table6215
+ GCC_except_table6220
+ GCC_except_table6378
+ GCC_except_table6383
+ GCC_except_table6396
+ GCC_except_table6421
+ GCC_except_table6431
+ GCC_except_table6434
+ GCC_except_table6473
+ GCC_except_table6510
+ GCC_except_table6512
+ GCC_except_table6912
+ GCC_except_table6932
+ GCC_except_table6945
+ GCC_except_table6958
+ GCC_except_table6977
+ GCC_except_table7008
+ GCC_except_table7011
+ GCC_except_table7013
+ GCC_except_table7015
+ GCC_except_table7017
+ GCC_except_table7026
+ GCC_except_table7074
+ GCC_except_table7088
+ GCC_except_table7126
+ GCC_except_table7128
+ GCC_except_table7167
+ GCC_except_table7420
+ GCC_except_table7423
+ GCC_except_table7445
+ GCC_except_table7452
+ GCC_except_table7470
+ GCC_except_table7474
+ GCC_except_table7475
+ GCC_except_table7476
+ GCC_except_table7477
+ GCC_except_table7478
+ GCC_except_table7479
+ GCC_except_table7490
+ GCC_except_table7491
+ GCC_except_table7492
+ GCC_except_table7649
+ GCC_except_table7869
+ GCC_except_table7914
+ GCC_except_table7933
+ GCC_except_table7992
+ GCC_except_table8017
+ GCC_except_table8021
+ GCC_except_table8028
+ GCC_except_table8082
+ GCC_except_table8288
+ GCC_except_table8290
+ GCC_except_table8377
+ GCC_except_table8381
+ GCC_except_table8383
+ GCC_except_table8385
+ GCC_except_table8397
+ GCC_except_table8402
+ GCC_except_table8442
+ GCC_except_table8470
+ GCC_except_table8512
+ GCC_except_table8595
+ GCC_except_table8653
+ GCC_except_table8674
+ GCC_except_table8677
+ GCC_except_table8696
+ GCC_except_table8755
+ GCC_except_table8761
+ GCC_except_table8767
+ GCC_except_table8768
+ GCC_except_table8769
+ GCC_except_table8770
+ GCC_except_table8771
+ GCC_except_table8773
+ GCC_except_table8775
+ GCC_except_table8779
+ GCC_except_table8790
+ GCC_except_table8793
+ GCC_except_table8818
+ GCC_except_table8866
+ GCC_except_table8931
+ GCC_except_table894
+ GCC_except_table9088
+ GCC_except_table9129
+ GCC_except_table9135
+ GCC_except_table9138
+ GCC_except_table9401
+ GCC_except_table9405
+ GCC_except_table9409
+ GCC_except_table9433
+ GCC_except_table9434
+ GCC_except_table949
+ GCC_except_table9532
+ GCC_except_table9542
+ GCC_except_table9575
+ GCC_except_table9627
+ GCC_except_table9672
+ GCC_except_table9692
+ GCC_except_table9748
+ GCC_except_table978
+ GCC_except_table9781
+ GCC_except_table9783
+ GCC_except_table982
+ GCC_except_table9874
+ GCC_except_table993
+ GCC_except_table995
+ GCC_except_table9965
+ OBJC_IVAR_$_PHAsset._provenanceState
+ OBJC_IVAR_$_PHAssetCreationMetadataCopyOptions._shouldCopyProvenanceData
+ OBJC_IVAR_$_PHAssetCreationRequest._originalProvenanceAssetFilename
+ OBJC_IVAR_$_PHAssetCreationRequest._originalProvenanceAssetUUID
+ OBJC_IVAR_$_PHAssetCreationRequest._processedProvenanceURL
+ OBJC_IVAR_$_PHAssetCreationRequest._useMockProvenanceProcessingClientForUnitTestSupport
+ OBJC_IVAR_$_PHAssetCreationRequestPlaceholderSupport._downloadSourceMode_shouldCopyProvenanceData
+ OBJC_IVAR_$_PHAssetExportRequestOptions._forceProvenanceMetadataBaking
+ OBJC_IVAR_$_PHAssetExportRequestOptions._shouldStripProvenance
+ OBJC_IVAR_$_PHAssetPTPProperties._provenanceState
+ OBJC_IVAR_$_PHAssetResourceCreationOptions._hasProvenanceData
+ OBJC_IVAR_$_PHImportAsset._provenanceAsset
+ OBJC_IVAR_$_PHResourceLocalAvailabilityRequestOptions._preferUncombinedProvenanceResources
+ OBJC_IVAR_$_PHResourceLocalAvailabilityRequestOptions._shouldStripProvenance
+ _OBJC_CLASS_$_PFContentProvenanceResourceInfo
+ _OBJC_CLASS_$_PFImageMetadataChangePolicyAddPFMetadata
+ _OBJC_CLASS_$_PFImageMetadataChangePolicySetProvenanceFlags
+ _PAMediaConversionIsCancellationError
+ _PAMediaConversionResourceRoleProvenanceUnprocessed
+ _PAMediaConversionServiceOptionColorSpaceKey
+ _PAMediaConversionServiceOptionFormatConversionOnlyKey
+ _PAMediaConversionServiceOptionIsContentProvenanceProcessingConversionKey
+ _PAMediaConversionServiceOptionJobPriorityKey
+ _PAMediaConversionServiceOptionLivePhotoPairingIdentifierKey
+ _PAMediaConversionServiceOptionProvenanceOriginalAssetLocalIdentifierKey
+ _PAMediaConversionServiceOptionRequestReasonKey
+ _PHAssetExportRequestOriginalProvenanceURLKey
+ _PHAssetExportRequestProvenanceMetadataOperationForAssetWithOptions
+ _PHQueryForAssetCollectionType_Album_block_invoke_109
+ _PHQueryForAssetCollectionType_CollectionShare_block_invoke_121
+ _PHQueryForAssetCollectionType_Conversation_block_invoke_118
+ _PHQueryForAssetCollectionType_ImportSession_block_invoke_117
+ _PHQueryForAssetCollectionType_Memory_block_invoke_113
+ _PHQueryForAssetCollectionType_MomentShare_block_invoke_115
+ _PHQueryForAssetCollectionType_Moment_block_invoke_110
+ _PHQueryForAssetCollectionType_NoFetchType_block_invoke_123
+ _PHQueryForAssetCollectionType_Other_block_invoke_122
+ _PHQueryForAssetCollectionType_PhotosHighlight_block_invoke_114
+ _PHQueryForAssetCollectionType_Project_block_invoke_119
+ _PHQueryForAssetCollectionType_SmartAlbum_block_invoke_111
+ _PHQueryForAssetCollectionType_Suggestion_block_invoke_116
+ _PHQueryForAssetCollectionType_Unknown_block_invoke_112
+ _PHQueryForAssetCollectionType_Utility_block_invoke_120
+ _PHQueryForAssetInAlbumKind_ActionCamVideoAlbum_block_invoke_99
+ _PHQueryForAssetInAlbumKind_ProResAlbum_block_invoke_98
+ _PHQueryForAssetInAlbumKind_ProvenanceAlbum
+ _PHQueryForAssetInAlbumKind_ProvenanceAlbum_block_invoke_96
+ _PHQueryForAssetInAlbumKind_SharedLibrarySharingSuggestionsAlbum_block_invoke_97
+ _PHQueryForAssetsAlbum_SortKeyOther_block_invoke_100
+ _PHQueryForAssetsInAlbum_SortKeyContentTitle_block_invoke_108
+ _PHQueryForAssetsInAlbum_SortKeyCreationDate_block_invoke_102
+ _PHQueryForAssetsInAlbum_SortKeyImportDate_block_invoke_104
+ _PHQueryForAssetsInAlbum_SortKeyLastModifiedDate_block_invoke_103
+ _PHQueryForAssetsInAlbum_SortKeyManual_block_invoke_101
+ _PHQueryForAssetsInAlbum_SortKeyPublishDate_block_invoke_107
+ _PHQueryForAssetsInAlbum_SortKeyTitle_block_invoke_106
+ _PHQueryForAssetsInAlbum_SortKeyTrashDate_block_invoke_105
+ _PHQueryForAssetsInUtility_GenericDocument_block_invoke_133
+ _PHQueryForAssetsInUtility_Handwriting_block_invoke_136
+ _PHQueryForAssetsInUtility_IdentityDocuments_block_invoke_139
+ _PHQueryForAssetsInUtility_Illustrations_block_invoke_135
+ _PHQueryForAssetsInUtility_Maps_block_invoke_138
+ _PHQueryForAssetsInUtility_Other_block_invoke_140
+ _PHQueryForAssetsInUtility_QRCodes_block_invoke_137
+ _PHQueryForAssetsInUtility_Receipts_block_invoke_134
+ _PHQueryForTransientAssetCollectionType_Generic_block_invoke_124
+ _PHQueryForTransientAssetCollectionType_ImportHistory_block_invoke_125
+ _PHQueryForTransientAssetCollectionType_Other_block_invoke_132
+ _PHQueryForTransientAssetCollectionType_RecentlyEdited_block_invoke_126
+ _PHQueryForTransientAssetCollectionType_RecentlyShared_block_invoke_127
+ _PHQueryForTransientAssetCollectionType_RecentlyViewed_block_invoke_128
+ _PHQueryForTransientAssetCollectionType_SavedToday_block_invoke_131
+ _PHQueryForTransientAssetCollectionType_SearchCollectionResults_block_invoke_130
+ _PHQueryForTransientAssetCollectionType_SearchTopResults_block_invoke_129
+ _PHResourceLocalAvailabilityRequestOriginalProvenanceURLKey
+ _PHResourceLocalAvailabilityRequestOriginalProvenanceUTIKey
+ _PHResourceLocalAvailabilityRequestProcessedProvenanceURLKey
+ _PLProvenanceGetLog
+ __88+[PHAssetExportRequest _insertAssetWithProcessedProvenanceResourceURL:unprocessedAsset:]_block_invoke
+ __90+[PHAssetCreationRequest processedProvenanceReplacementForSharingAsset:completionHandler:]_block_invoke
+ __DATA__TtC6Photos20PHReferenceImageInfo
+ __DATA__TtC6Photos21PHAssetProvenanceInfo
+ __IVARS__TtC6Photos20PHReferenceImageInfo
+ __IVARS__TtC6Photos21PHAssetProvenanceInfo
+ __METACLASS_DATA__TtC6Photos20PHReferenceImageInfo
+ __METACLASS_DATA__TtC6Photos21PHAssetProvenanceInfo
+ __OBJC_$_CLASS_METHODS_PHAssetCreationRequestPlaceholderSupport
+ __OBJC_$_CLASS_METHODS_PHPhotoLibrary(ImportDeDup|Search|MediaProcessing|PHDebugUtilities|PHAdoptionUtilities|Repair|PhotosFormat|ProjectExtensions|Widgets|MigrationDate|CloudIdentifierReservations|PXCPLStatus|CollectionShare|PHAsset|CloudPhotoLibrary|FeatureAvailability|CloudIdentifiers|ContentProvenance|PHBatchFetchingArray|PersonAvailability|AssetAnalysis|PhotosKnowledgeSPI|DuplicateProcessing)
+ __OBJC_$_INSTANCE_METHODS_PHPhotoLibrary(ImportDeDup|Search|MediaProcessing|PHDebugUtilities|PHAdoptionUtilities|Repair|PhotosFormat|ProjectExtensions|Widgets|MigrationDate|CloudIdentifierReservations|PXCPLStatus|CollectionShare|PHAsset|CloudPhotoLibrary|FeatureAvailability|CloudIdentifiers|ContentProvenance|PHBatchFetchingArray|PersonAvailability|AssetAnalysis|PhotosKnowledgeSPI|DuplicateProcessing)
+ __OBJC_CLASS_PROTOCOLS_$_PHPhotoLibrary(ImportDeDup|Search|MediaProcessing|PHDebugUtilities|PHAdoptionUtilities|Repair|PhotosFormat|ProjectExtensions|Widgets|MigrationDate|CloudIdentifierReservations|PXCPLStatus|CollectionShare|PHAsset|CloudPhotoLibrary|FeatureAvailability|CloudIdentifiers|ContentProvenance|PHBatchFetchingArray|PersonAvailability|AssetAnalysis|PhotosKnowledgeSPI|DuplicateProcessing)
+ ___51+[PHImportAsset scanAssetsForProvenanceData:atEnd:]_block_invoke
+ ___51+[PHImportAsset scanAssetsForProvenanceData:atEnd:]_block_invoke_2
+ ___73-[PHAssetCreationRequest performAsyncPreprocessingWithCompletionHandler:]_block_invoke
+ ___79+[PHAsset fetchProcessedProvenanceAssetWithOriginatingAssetIdentifier:options:]_block_invoke
+ ___88+[PHAssetExportRequest _insertAssetWithProcessedProvenanceResourceURL:unprocessedAsset:]_block_invoke
+ ___90+[PHAssetCreationRequest processedProvenanceReplacementForSharingAsset:completionHandler:]_block_invoke
+ ___block_descriptor_112_e8_32s40s48s56bs64r72r80r88r96r104w_e5_v8?0l
+ ___block_descriptor_48_e8_32r40r_e42_v32?0"NSNumber"8"PHAssetResource"16^B24l
+ ___block_descriptor_64_e8_32s40s48bs56r_e20_v20?0B8"NSError"12l
+ ___block_descriptor_64_e8_32s40s48bs56r_e40_v32?0B8B12"NSDictionary"16"NSError"24l
+ ___block_descriptor_64_e8_32s40s48s56bs_e37_v32?0q8"NSDictionary"16"NSError"24l
+ ___block_descriptor_72_e8_32s40s48s56s64r_e20_v24?0q8"NSError"16l
+ ___block_descriptor_72_e8_32s40s48s56s64s_e40_v32?0B8B12"NSDictionary"16"NSError"24l
+ ___block_descriptor_80_e8_32s40s48s56s64s72r_e20_v24?0q8"NSError"16l
+ ___block_descriptor_89_e8_32s40s48s56r_e42_v32?0"NSNumber"8"PHAssetResource"16^B24l
+ ___copy_helper_block_e8_32s40s48s56b64r72r80r88r96r104w
+ ___destroy_helper_block_e8_32s40s48s56s64r72r80r88r96r104w
+ ___swift_memcpy16_8
+ _kDCIMImageWriterProvenanceMetadataPathExtension
+ _kPLImageWriterProvenancePath
+ _objc_msgSend$_addProcessedProvenanceResourceToAssetResources:processedProvenanceResourceURL:unprocessedOriginal:error:
+ _objc_msgSend$_adjustedProvenanceRenderURLToShareForAsset:options:fileURLs:
+ _objc_msgSend$_cleanupTemporaryProvenanceFilesIfNecessary
+ _objc_msgSend$_creationRequestForProcessedProvenanceAssetFromUnprocessedProvenanceAsset:resourceBundle:processedProvenanceResourceURL:
+ _objc_msgSend$_getOriginalResource:sidecarProvenanceResource:
+ _objc_msgSend$_insertAssetWithProcessedProvenanceResourceURL:unprocessedAsset:
+ _objc_msgSend$_processedProvenanceCarrierURLFromSourceAsset:
+ _objc_msgSend$_removeProvenanceSidecarResourcesFrom:byType:
+ _objc_msgSend$_setupProvenanceStateFromFetchDictionary:
+ _objc_msgSend$_shouldAddOriginalProvenanceResourceToResourcesToShareForAsset:shouldStripProvenance:
+ _objc_msgSend$_shouldCombineEditedProvenanceIntoRenderForAsset:options:fileURLs:
+ _objc_msgSend$_shouldEmbedProvenanceIntoRenderForSourceAsset:
+ _objc_msgSend$_updateAssetResourcesWithProcessedProvenanceResource:
+ _objc_msgSend$_validateProvenanceStateForProcessing:
+ _objc_msgSend$assetResourceForDuplicatingExternalAssetResource:creationOptions:
+ _objc_msgSend$creationRequestForProcessedProvenanceAssetFromUnprocessedProvenanceAsset:resourceInfo:
+ _objc_msgSend$embedProcessedProvenanceFromRegularImageAtURL:intoRegularImageAtURL:destinationURL:options:completionHandler:
+ _objc_msgSend$forceProvenanceMetadataBaking
+ _objc_msgSend$hasProvenanceData
+ _objc_msgSend$hasProvenanceMetadata
+ _objc_msgSend$hasUnprocessedProvenanceAuxiliaryMetadata
+ _objc_msgSend$hasUnprocessedProvenanceDNGMetadata
+ _objc_msgSend$initWithMetadata:
+ _objc_msgSend$initWithOriginalPhotoURL:alternatePhotoURL:fullSizePhotoURL:adjustmentBaseFullSizePhotoURL:spatialOvercapturePhotoURL:originalPairedVideoURL:fullSizePairedVideoURL:adjustmentBaseFullSizePairedVideoURL:spatialOvercapturePairedVideoURL:fullSizeVideoURL:adjustmentsURL:originalAdjustmentsURL:adjustmentsSecondaryDataURL:originalProvenanceURL:mediaSubtypes:playbackStyle:playbackVariation:videoComplementVisibilityState:
+ _objc_msgSend$initWithProvenanceState:
+ _objc_msgSend$lastAvailableContentProvenanceLowerBoundTimestampData
+ _objc_msgSend$livePhotoPairingIdentifierMetadataKey
+ _objc_msgSend$maskForProvenanceProcessingExclusions
+ _objc_msgSend$originalProvenanceAssetUUID
+ _objc_msgSend$originalProvenanceURL
+ _objc_msgSend$performChangesWithProgress:completionHandler:
+ _objc_msgSend$policyWithKey:value:
+ _objc_msgSend$powderState
+ _objc_msgSend$preferUncombinedProvenanceResources
+ _objc_msgSend$processPotentialProvenanceAsset:plusProvenanceDNG:
+ _objc_msgSend$provenanceAsset
+ _objc_msgSend$provenanceAssetDidProcessFromOriginalAssetWithUUID:error:
+ _objc_msgSend$provenanceFlags
+ _objc_msgSend$provenanceState
+ _objc_msgSend$scheduleProvenanceTimestampBackgroundJob
+ _objc_msgSend$setHasProvenanceData:
+ _objc_msgSend$setOriginalProvenanceAssetFilename:
+ _objc_msgSend$setOriginalProvenanceAssetUUID:
+ _objc_msgSend$setPowderState:
+ _objc_msgSend$setPreferUncombinedProvenanceResources:
+ _objc_msgSend$setProvenanceAsset:
+ _objc_msgSend$setProvenanceMetadataBehavior:withProcessedSourceImageURL:
+ _objc_msgSend$setProvenanceMetadataBehavior:withProvenanceSidecarURL:
+ _objc_msgSend$setProvenanceMetadataBehavior:withUnprocessedSourceAdjustedRenderURL:processedOriginalDestinationURL:sidecarURL:
+ _objc_msgSend$setResourceURL:forRole:
+ _objc_msgSend$setShouldCopyProvenanceData:
+ _objc_msgSend$setShouldPreserveProvenance:
+ _objc_msgSend$setShouldStripProvenance:
+ _objc_msgSend$setupPlaceholderAssetWithRequiredPropertiesFromSourceAsset:placeholderAssetUUID:bundleScope:share:importSessionID:bakeInAdjustmentsFromSourceAsset:flattenLivePhoto:copyTitleDescriptionAndKeywords:copyCameraProcessingAdjustmentResources:copyProvenanceData:isCurrentUser:library:
+ _objc_msgSend$shouldCopyProvenanceData
+ _objc_msgSend$shouldEmbedProvenanceIntoSharedRenderForAsset:shouldCopyProvenanceData:
+ _objc_msgSend$shouldStripProvenance
+ _objc_msgSend$shouldStripProvenanceForAsset:shouldCopyProvenanceData:
+ _objc_msgSend$stripProvenanceExtensionFrompPath:
+ _objc_msgSend$stripProvenanceMetadataFromOriginalProvenanceImageAtURL:destinationURL:options:completionHandler:
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_initWithCopy
+ _swift_cvw_initWithTake
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_getEnumCaseMultiPayload
+ _swift_storeEnumTagMultiPayload
+ _symbolic So31PFContentProvenanceResourceInfoCSg
+ _symbolic So7PHAssetC
+ _symbolic _____ 10Foundation3URLV
+ _symbolic _____ 6Photos20PHReferenceImageInfoC
+ _symbolic _____ 6Photos20PHReferenceImageInfoC0C6Source33_1A73BF63275DDEEDDC1664B3A274BE79LLO
+ _symbolic _____ 6Photos20PHReferenceImageInfoC10CacheState33_1A73BF63275DDEEDDC1664B3A274BE79LLV
+ _symbolic _____ 6Photos21PHAssetProvenanceInfoC
+ _symbolic _____Sg 22UniformTypeIdentifiers6UTTypeV
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 6Photos20PHReferenceImageInfoC10CacheState33_1A73BF63275DDEEDDC1664B3A274BE79LLV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 6Photos20PHReferenceImageInfoC10CacheState33_1A73BF63275DDEEDDC1664B3A274BE79LLV So16os_unfair_lock_sV
+ _type_layout_string 6Photos20PHReferenceImageInfoC10CacheState33_1A73BF63275DDEEDDC1664B3A274BE79LLV
- GCC_except_table10026
- GCC_except_table10036
- GCC_except_table10050
- GCC_except_table10051
- GCC_except_table10058
- GCC_except_table10061
- GCC_except_table10084
- GCC_except_table10085
- GCC_except_table10086
- GCC_except_table10088
- GCC_except_table10089
- GCC_except_table10090
- GCC_except_table10091
- GCC_except_table10094
- GCC_except_table10095
- GCC_except_table10096
- GCC_except_table10098
- GCC_except_table10099
- GCC_except_table10100
- GCC_except_table10101
- GCC_except_table10103
- GCC_except_table10104
- GCC_except_table10105
- GCC_except_table10106
- GCC_except_table10107
- GCC_except_table10108
- GCC_except_table10109
- GCC_except_table10110
- GCC_except_table10113
- GCC_except_table10114
- GCC_except_table10115
- GCC_except_table10116
- GCC_except_table10118
- GCC_except_table10120
- GCC_except_table10121
- GCC_except_table10123
- GCC_except_table10124
- GCC_except_table10125
- GCC_except_table10126
- GCC_except_table10128
- GCC_except_table10129
- GCC_except_table10130
- GCC_except_table10131
- GCC_except_table10132
- GCC_except_table10133
- GCC_except_table10134
- GCC_except_table10135
- GCC_except_table10136
- GCC_except_table10137
- GCC_except_table10138
- GCC_except_table10139
- GCC_except_table10140
- GCC_except_table10141
- GCC_except_table10142
- GCC_except_table10143
- GCC_except_table10144
- GCC_except_table10153
- GCC_except_table10154
- GCC_except_table10163
- GCC_except_table10178
- GCC_except_table10188
- GCC_except_table10312
- GCC_except_table10321
- GCC_except_table10322
- GCC_except_table10323
- GCC_except_table10324
- GCC_except_table10325
- GCC_except_table10326
- GCC_except_table10327
- GCC_except_table10338
- GCC_except_table10356
- GCC_except_table10390
- GCC_except_table10391
- GCC_except_table10392
- GCC_except_table10393
- GCC_except_table10403
- GCC_except_table10421
- GCC_except_table10422
- GCC_except_table10423
- GCC_except_table10424
- GCC_except_table10425
- GCC_except_table10426
- GCC_except_table10427
- GCC_except_table10428
- GCC_except_table10429
- GCC_except_table10430
- GCC_except_table10467
- GCC_except_table10468
- GCC_except_table10472
- GCC_except_table10499
- GCC_except_table10581
- GCC_except_table10674
- GCC_except_table10841
- GCC_except_table10861
- GCC_except_table10864
- GCC_except_table10865
- GCC_except_table10891
- GCC_except_table10893
- GCC_except_table10983
- GCC_except_table11001
- GCC_except_table1119
- GCC_except_table1137
- GCC_except_table11520
- GCC_except_table1164
- GCC_except_table11677
- GCC_except_table11680
- GCC_except_table11687
- GCC_except_table11695
- GCC_except_table11699
- GCC_except_table11701
- GCC_except_table11705
- GCC_except_table11711
- GCC_except_table11817
- GCC_except_table11836
- GCC_except_table11838
- GCC_except_table11840
- GCC_except_table11842
- GCC_except_table11877
- GCC_except_table11926
- GCC_except_table11933
- GCC_except_table11935
- GCC_except_table11937
- GCC_except_table11943
- GCC_except_table11980
- GCC_except_table12111
- GCC_except_table12137
- GCC_except_table12149
- GCC_except_table12191
- GCC_except_table12205
- GCC_except_table12291
- GCC_except_table12295
- GCC_except_table12336
- GCC_except_table12340
- GCC_except_table12349
- GCC_except_table12350
- GCC_except_table12357
- GCC_except_table12395
- GCC_except_table12402
- GCC_except_table12412
- GCC_except_table12417
- GCC_except_table12467
- GCC_except_table12559
- GCC_except_table12562
- GCC_except_table12568
- GCC_except_table12570
- GCC_except_table1258
- GCC_except_table12610
- GCC_except_table12629
- GCC_except_table12640
- GCC_except_table12702
- GCC_except_table12705
- GCC_except_table12713
- GCC_except_table12719
- GCC_except_table12721
- GCC_except_table1277
- GCC_except_table12786
- GCC_except_table12864
- GCC_except_table12868
- GCC_except_table12872
- GCC_except_table12909
- GCC_except_table12933
- GCC_except_table12940
- GCC_except_table13070
- GCC_except_table13082
- GCC_except_table13177
- GCC_except_table13244
- GCC_except_table13450
- GCC_except_table1352
- GCC_except_table13529
- GCC_except_table13571
- GCC_except_table13620
- GCC_except_table13630
- GCC_except_table13650
- GCC_except_table13665
- GCC_except_table13693
- GCC_except_table13695
- GCC_except_table13708
- GCC_except_table13710
- GCC_except_table13712
- GCC_except_table13731
- GCC_except_table13877
- GCC_except_table13888
- GCC_except_table13915
- GCC_except_table13921
- GCC_except_table13937
- GCC_except_table14007
- GCC_except_table14009
- GCC_except_table14055
- GCC_except_table14057
- GCC_except_table14081
- GCC_except_table14084
- GCC_except_table14238
- GCC_except_table1446
- GCC_except_table1471
- GCC_except_table1517
- GCC_except_table1592
- GCC_except_table1692
- GCC_except_table1794
- GCC_except_table1798
- GCC_except_table1824
- GCC_except_table1829
- GCC_except_table1833
- GCC_except_table2030
- GCC_except_table2034
- GCC_except_table2036
- GCC_except_table2038
- GCC_except_table2040
- GCC_except_table2044
- GCC_except_table2047
- GCC_except_table2058
- GCC_except_table2102
- GCC_except_table2104
- GCC_except_table2106
- GCC_except_table2108
- GCC_except_table2110
- GCC_except_table2112
- GCC_except_table2135
- GCC_except_table2137
- GCC_except_table2139
- GCC_except_table2141
- GCC_except_table2143
- GCC_except_table2146
- GCC_except_table2148
- GCC_except_table2183
- GCC_except_table2185
- GCC_except_table2188
- GCC_except_table2191
- GCC_except_table2295
- GCC_except_table2300
- GCC_except_table2310
- GCC_except_table2322
- GCC_except_table2362
- GCC_except_table2535
- GCC_except_table2548
- GCC_except_table2576
- GCC_except_table2593
- GCC_except_table2612
- GCC_except_table2622
- GCC_except_table2659
- GCC_except_table2664
- GCC_except_table2726
- GCC_except_table2831
- GCC_except_table2842
- GCC_except_table2844
- GCC_except_table2850
- GCC_except_table2858
- GCC_except_table2890
- GCC_except_table2970
- GCC_except_table2976
- GCC_except_table2981
- GCC_except_table2984
- GCC_except_table2994
- GCC_except_table3009
- GCC_except_table3016
- GCC_except_table3146
- GCC_except_table3150
- GCC_except_table3153
- GCC_except_table3220
- GCC_except_table3228
- GCC_except_table3263
- GCC_except_table3267
- GCC_except_table3272
- GCC_except_table3396
- GCC_except_table3429
- GCC_except_table3435
- GCC_except_table3438
- GCC_except_table3448
- GCC_except_table3452
- GCC_except_table3463
- GCC_except_table3466
- GCC_except_table3500
- GCC_except_table3511
- GCC_except_table3512
- GCC_except_table3537
- GCC_except_table3634
- GCC_except_table3641
- GCC_except_table3662
- GCC_except_table3664
- GCC_except_table3666
- GCC_except_table3713
- GCC_except_table3741
- GCC_except_table3772
- GCC_except_table3774
- GCC_except_table3792
- GCC_except_table3794
- GCC_except_table3797
- GCC_except_table3957
- GCC_except_table3991
- GCC_except_table3999
- GCC_except_table4001
- GCC_except_table4016
- GCC_except_table4019
- GCC_except_table4021
- GCC_except_table4054
- GCC_except_table4059
- GCC_except_table4060
- GCC_except_table4314
- GCC_except_table4321
- GCC_except_table4352
- GCC_except_table4373
- GCC_except_table4376
- GCC_except_table4382
- GCC_except_table4387
- GCC_except_table4398
- GCC_except_table4402
- GCC_except_table4420
- GCC_except_table4486
- GCC_except_table4811
- GCC_except_table4821
- GCC_except_table4881
- GCC_except_table4885
- GCC_except_table4887
- GCC_except_table4890
- GCC_except_table4960
- GCC_except_table4965
- GCC_except_table4998
- GCC_except_table5128
- GCC_except_table5132
- GCC_except_table5479
- GCC_except_table5510
- GCC_except_table5556
- GCC_except_table5582
- GCC_except_table5615
- GCC_except_table5620
- GCC_except_table5644
- GCC_except_table5648
- GCC_except_table5652
- GCC_except_table5674
- GCC_except_table5680
- GCC_except_table5684
- GCC_except_table5698
- GCC_except_table5701
- GCC_except_table5704
- GCC_except_table5727
- GCC_except_table5762
- GCC_except_table5783
- GCC_except_table5794
- GCC_except_table5833
- GCC_except_table5845
- GCC_except_table5879
- GCC_except_table5882
- GCC_except_table5892
- GCC_except_table5904
- GCC_except_table5966
- GCC_except_table5993
- GCC_except_table5995
- GCC_except_table6008
- GCC_except_table6077
- GCC_except_table6154
- GCC_except_table6159
- GCC_except_table6164
- GCC_except_table6322
- GCC_except_table6327
- GCC_except_table6340
- GCC_except_table6365
- GCC_except_table6376
- GCC_except_table6379
- GCC_except_table6417
- GCC_except_table6454
- GCC_except_table6456
- GCC_except_table6855
- GCC_except_table6875
- GCC_except_table6888
- GCC_except_table6901
- GCC_except_table6920
- GCC_except_table6950
- GCC_except_table6953
- GCC_except_table6955
- GCC_except_table6957
- GCC_except_table6959
- GCC_except_table6968
- GCC_except_table7016
- GCC_except_table7030
- GCC_except_table7066
- GCC_except_table7068
- GCC_except_table7107
- GCC_except_table7360
- GCC_except_table7363
- GCC_except_table7385
- GCC_except_table7392
- GCC_except_table7410
- GCC_except_table7414
- GCC_except_table7415
- GCC_except_table7416
- GCC_except_table7417
- GCC_except_table7418
- GCC_except_table7419
- GCC_except_table7430
- GCC_except_table7431
- GCC_except_table7432
- GCC_except_table7589
- GCC_except_table7809
- GCC_except_table7854
- GCC_except_table7872
- GCC_except_table7873
- GCC_except_table7957
- GCC_except_table7961
- GCC_except_table7968
- GCC_except_table8022
- GCC_except_table8228
- GCC_except_table8230
- GCC_except_table8277
- GCC_except_table8317
- GCC_except_table8321
- GCC_except_table8323
- GCC_except_table8325
- GCC_except_table8342
- GCC_except_table8382
- GCC_except_table8410
- GCC_except_table8452
- GCC_except_table8534
- GCC_except_table8592
- GCC_except_table8613
- GCC_except_table8616
- GCC_except_table8635
- GCC_except_table8694
- GCC_except_table8700
- GCC_except_table8706
- GCC_except_table8707
- GCC_except_table8708
- GCC_except_table8709
- GCC_except_table8710
- GCC_except_table8712
- GCC_except_table8714
- GCC_except_table8718
- GCC_except_table8729
- GCC_except_table8732
- GCC_except_table8757
- GCC_except_table8805
- GCC_except_table8870
- GCC_except_table890
- GCC_except_table9027
- GCC_except_table9068
- GCC_except_table9074
- GCC_except_table9077
- GCC_except_table9340
- GCC_except_table9344
- GCC_except_table9348
- GCC_except_table9372
- GCC_except_table9373
- GCC_except_table942
- GCC_except_table9471
- GCC_except_table9481
- GCC_except_table9514
- GCC_except_table9566
- GCC_except_table9611
- GCC_except_table9631
- GCC_except_table9659
- GCC_except_table966
- GCC_except_table9687
- GCC_except_table970
- GCC_except_table9722
- GCC_except_table981
- GCC_except_table9813
- GCC_except_table983
- GCC_except_table9904
- _OUTLINED_FUNCTION_33
- _PHQueryForAssetCollectionType_Album_block_invoke_108
- _PHQueryForAssetCollectionType_CollectionShare_block_invoke_120
- _PHQueryForAssetCollectionType_Conversation_block_invoke_117
- _PHQueryForAssetCollectionType_ImportSession_block_invoke_116
- _PHQueryForAssetCollectionType_Memory_block_invoke_112
- _PHQueryForAssetCollectionType_MomentShare_block_invoke_114
- _PHQueryForAssetCollectionType_Moment_block_invoke_109
- _PHQueryForAssetCollectionType_NoFetchType_block_invoke_122
- _PHQueryForAssetCollectionType_Other_block_invoke_121
- _PHQueryForAssetCollectionType_PhotosHighlight_block_invoke_113
- _PHQueryForAssetCollectionType_Project_block_invoke_118
- _PHQueryForAssetCollectionType_SmartAlbum_block_invoke_110
- _PHQueryForAssetCollectionType_Suggestion_block_invoke_115
- _PHQueryForAssetCollectionType_Unknown_block_invoke_111
- _PHQueryForAssetCollectionType_Utility_block_invoke_119
- _PHQueryForAssetInAlbumKind_ActionCamVideoAlbum_block_invoke_98
- _PHQueryForAssetInAlbumKind_ProResAlbum_block_invoke_97
- _PHQueryForAssetInAlbumKind_SharedLibrarySharingSuggestionsAlbum_block_invoke_96
- _PHQueryForAssetsAlbum_SortKeyOther_block_invoke_99
- _PHQueryForAssetsInAlbum_SortKeyContentTitle_block_invoke_107
- _PHQueryForAssetsInAlbum_SortKeyCreationDate_block_invoke_101
- _PHQueryForAssetsInAlbum_SortKeyImportDate_block_invoke_103
- _PHQueryForAssetsInAlbum_SortKeyLastModifiedDate_block_invoke_102
- _PHQueryForAssetsInAlbum_SortKeyManual_block_invoke_100
- _PHQueryForAssetsInAlbum_SortKeyPublishDate_block_invoke_106
- _PHQueryForAssetsInAlbum_SortKeyTitle_block_invoke_105
- _PHQueryForAssetsInAlbum_SortKeyTrashDate_block_invoke_104
- _PHQueryForAssetsInUtility_GenericDocument_block_invoke_132
- _PHQueryForAssetsInUtility_Handwriting_block_invoke_135
- _PHQueryForAssetsInUtility_IdentityDocuments_block_invoke_138
- _PHQueryForAssetsInUtility_Illustrations_block_invoke_134
- _PHQueryForAssetsInUtility_Maps_block_invoke_137
- _PHQueryForAssetsInUtility_Other_block_invoke_139
- _PHQueryForAssetsInUtility_QRCodes_block_invoke_136
- _PHQueryForAssetsInUtility_Receipts_block_invoke_133
- _PHQueryForTransientAssetCollectionType_Generic_block_invoke_123
- _PHQueryForTransientAssetCollectionType_ImportHistory_block_invoke_124
- _PHQueryForTransientAssetCollectionType_Other_block_invoke_131
- _PHQueryForTransientAssetCollectionType_RecentlyEdited_block_invoke_125
- _PHQueryForTransientAssetCollectionType_RecentlyShared_block_invoke_126
- _PHQueryForTransientAssetCollectionType_RecentlyViewed_block_invoke_127
- _PHQueryForTransientAssetCollectionType_SavedToday_block_invoke_130
- _PHQueryForTransientAssetCollectionType_SearchCollectionResults_block_invoke_129
- _PHQueryForTransientAssetCollectionType_SearchTopResults_block_invoke_128
- __106-[PHResourceLocalAvailabilityRequest _fetchResourcesForSharingAsset:options:networkAccessAllowed:handler:]_block_invoke_2
- __OBJC_$_CLASS_METHODS_PHPhotoLibrary(ImportDeDup|Search|MediaProcessing|PHDebugUtilities|PHAdoptionUtilities|Repair|PhotosFormat|ProjectExtensions|Widgets|MigrationDate|CloudIdentifierReservations|PXCPLStatus|CollectionShare|PHAsset|CloudPhotoLibrary|FeatureAvailability|CloudIdentifiers|PHBatchFetchingArray|PersonAvailability|AssetAnalysis|PhotosKnowledgeSPI|DuplicateProcessing)
- __OBJC_$_INSTANCE_METHODS_PHPhotoLibrary(ImportDeDup|Search|MediaProcessing|PHDebugUtilities|PHAdoptionUtilities|Repair|PhotosFormat|ProjectExtensions|Widgets|MigrationDate|CloudIdentifierReservations|PXCPLStatus|CollectionShare|PHAsset|CloudPhotoLibrary|FeatureAvailability|CloudIdentifiers|PHBatchFetchingArray|PersonAvailability|AssetAnalysis|PhotosKnowledgeSPI|DuplicateProcessing)
- __OBJC_CLASS_PROTOCOLS_$_PHPhotoLibrary(ImportDeDup|Search|MediaProcessing|PHDebugUtilities|PHAdoptionUtilities|Repair|PhotosFormat|ProjectExtensions|Widgets|MigrationDate|CloudIdentifierReservations|PXCPLStatus|CollectionShare|PHAsset|CloudPhotoLibrary|FeatureAvailability|CloudIdentifiers|PHBatchFetchingArray|PersonAvailability|AssetAnalysis|PhotosKnowledgeSPI|DuplicateProcessing)
- ___block_descriptor_40_e8_32r_e42_v32?0"NSNumber"8"PHAssetResource"16^B24l
- ___block_descriptor_81_e8_32s40s48r_e42_v32?0"NSNumber"8"PHAssetResource"16^B24l
- ___block_descriptor_96_e8_32s40s48s56bs64r72r80r88r_e5_v8?0l
- ___copy_helper_block_e8_32s40s48s56b64r72r80r88r
- ___destroy_helper_block_e8_32s40s48s56s64r72r80r88r
- _objc_msgSend$initWithOriginalPhotoURL:alternatePhotoURL:fullSizePhotoURL:adjustmentBaseFullSizePhotoURL:spatialOvercapturePhotoURL:originalPairedVideoURL:fullSizePairedVideoURL:adjustmentBaseFullSizePairedVideoURL:spatialOvercapturePairedVideoURL:fullSizeVideoURL:adjustmentsURL:originalAdjustmentsURL:adjustmentsSecondaryDataURL:mediaSubtypes:playbackStyle:playbackVariation:videoComplementVisibilityState:
- _objc_msgSend$setupPlaceholderAssetWithRequiredPropertiesFromSourceAsset:placeholderAssetUUID:bundleScope:share:importSessionID:bakeInAdjustmentsFromSourceAsset:flattenLivePhoto:copyTitleDescriptionAndKeywords:copyCameraProcessingAdjustmentResources:isCurrentUser:library:
CStrings:
+ " shouldCopyProvenanceData=%d"
+ "%@ missing resources for provenance processing"
+ "%@.DNG"
+ "%K == %ld"
+ "+[PHResourceLocalAvailabilityRequest _singularResourcesToShareForAsset:fromAvailableResources:options:useOriginalResources:knownUnsupported:error:]"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Photos/Projects/PhotoKit/Sources/PHResourceLocalAvailabilityRequest.m"
+ "<%@: %p, variant: \"%@\", livePhotoAsStill: %d, allowRaw: %d, flattenSlomo: %d, stripLocation: %d, stripProvenance: %d, stripCaption: %d, stripAXDescription: %d, stripKeywords: %d, assetBundle: %d, disableMetadataCorrections: %d, unmodifiedOriginals: %d>"
+ "Asset %@ is not in a provenance state that can be processed for sharing"
+ "CombiningProvenanceResources"
+ "Creating processed provenance resource from asset: %@ new asset UUID: %@ from combined-provenance resource: %d"
+ "Edited provenance asset selected its original as a provenance source but has no full-size render to carry it"
+ "Error deleting temporary directory %@"
+ "Failed to embed processed provenance into shared render for source asset %@"
+ "Failed to insert processed provenance replacement for asset %@"
+ "Failed to insert processed provenance replacement for asset %{public}@: %@"
+ "Failed to retrieve resources to process provenance for share for asset %@"
+ "Failed to retrieve resources to process provenance for share for asset %{public}@ (success=%d cancelled=%d): %@"
+ "ImageConversionService async processing failed: %@"
+ "Missing original provenance resource for source asset %@"
+ "Missing photo resource to regenerate provenance for source asset %@"
+ "MissingProcessedProvenanceResource"
+ "No photo library for asset %@; cannot process provenance for share"
+ "No photoLibrary for asset %{public}@; cannot process provenance for share"
+ "PAIRING: setting %@ as provenance asset of %@"
+ "PHAssetCreationRequest provenance development"
+ "PHAssetCreationRequestPlaceholderSupport-ProvenanceRenderEmbed-%@"
+ "PHAssetCreationRequestPlaceholderSupport-ProvenanceStrip-%@"
+ "PHAssetExportRequestMetadataOperation PHAssetExportRequestProvenanceMetadataOperationForAssetWithOptions(PHAsset *__strong _Nonnull, PHAssetExportRequestOptions *__strong _Nonnull, NSDictionary<PHAssetExportRequestFileURLKey,NSURL *> *__strong _Nonnull)"
+ "PHAssetExportRequestOriginalProvenanceURLKey"
+ "PHQueryForAssetCollectionType_Album_block_invoke_109"
+ "PHQueryForAssetCollectionType_CollectionShare_block_invoke_121"
+ "PHQueryForAssetCollectionType_Conversation_block_invoke_118"
+ "PHQueryForAssetCollectionType_ImportSession_block_invoke_117"
+ "PHQueryForAssetCollectionType_Memory_block_invoke_113"
+ "PHQueryForAssetCollectionType_MomentShare_block_invoke_115"
+ "PHQueryForAssetCollectionType_Moment_block_invoke_110"
+ "PHQueryForAssetCollectionType_NoFetchType_block_invoke_123"
+ "PHQueryForAssetCollectionType_Other_block_invoke_122"
+ "PHQueryForAssetCollectionType_PhotosHighlight_block_invoke_114"
+ "PHQueryForAssetCollectionType_Project_block_invoke_119"
+ "PHQueryForAssetCollectionType_SmartAlbum_block_invoke_111"
+ "PHQueryForAssetCollectionType_Suggestion_block_invoke_116"
+ "PHQueryForAssetCollectionType_Unknown_block_invoke_112"
+ "PHQueryForAssetCollectionType_Utility_block_invoke_120"
+ "PHQueryForAssetInAlbumKind_ActionCamVideoAlbum_block_invoke_99"
+ "PHQueryForAssetInAlbumKind_ProResAlbum_block_invoke_98"
+ "PHQueryForAssetInAlbumKind_ProvenanceAlbum_block_invoke_96"
+ "PHQueryForAssetInAlbumKind_SharedLibrarySharingSuggestionsAlbum_block_invoke_97"
+ "PHQueryForAssetsAlbum_SortKeyOther_block_invoke_100"
+ "PHQueryForAssetsInAlbum_SortKeyContentTitle_block_invoke_108"
+ "PHQueryForAssetsInAlbum_SortKeyCreationDate_block_invoke_102"
+ "PHQueryForAssetsInAlbum_SortKeyImportDate_block_invoke_104"
+ "PHQueryForAssetsInAlbum_SortKeyLastModifiedDate_block_invoke_103"
+ "PHQueryForAssetsInAlbum_SortKeyManual_block_invoke_101"
+ "PHQueryForAssetsInAlbum_SortKeyPublishDate_block_invoke_107"
+ "PHQueryForAssetsInAlbum_SortKeyTitle_block_invoke_106"
+ "PHQueryForAssetsInAlbum_SortKeyTrashDate_block_invoke_105"
+ "PHQueryForAssetsInUtility_GenericDocument_block_invoke_133"
+ "PHQueryForAssetsInUtility_Handwriting_block_invoke_136"
+ "PHQueryForAssetsInUtility_IdentityDocuments_block_invoke_139"
+ "PHQueryForAssetsInUtility_Illustrations_block_invoke_135"
+ "PHQueryForAssetsInUtility_Maps_block_invoke_138"
+ "PHQueryForAssetsInUtility_Other_block_invoke_140"
+ "PHQueryForAssetsInUtility_QRCodes_block_invoke_137"
+ "PHQueryForAssetsInUtility_Receipts_block_invoke_134"
+ "PHQueryForTransientAssetCollectionType_Generic_block_invoke_124"
+ "PHQueryForTransientAssetCollectionType_ImportHistory_block_invoke_125"
+ "PHQueryForTransientAssetCollectionType_Other_block_invoke_132"
+ "PHQueryForTransientAssetCollectionType_RecentlyEdited_block_invoke_126"
+ "PHQueryForTransientAssetCollectionType_RecentlyShared_block_invoke_127"
+ "PHQueryForTransientAssetCollectionType_RecentlyViewed_block_invoke_128"
+ "PHQueryForTransientAssetCollectionType_SavedToday_block_invoke_131"
+ "PHQueryForTransientAssetCollectionType_SearchCollectionResults_block_invoke_130"
+ "PHQueryForTransientAssetCollectionType_SearchTopResults_block_invoke_129"
+ "PHResourceLocalAvailabilityRequestOriginalProvenanceURLKey"
+ "PHResourceLocalAvailabilityRequestOriginalProvenanceUTIKey"
+ "PHResourceLocalAvailabilityRequestProcessedProvenanceURLKey"
+ "PHResourceLocalAvailabilityRequestResourceAvailabilityProvenanceCombiningRequired"
+ "Photo URL is unexpectedly nil in the resourceInfo dictionary"
+ "Processed provenance asset will be created from pre-processed resource at url: %@ for asset %@"
+ "Processed provenance asset will be created from the combined-provenance resource at url: %@ for asset %@"
+ "Processed provenance asset will be created from the original resource at url: %@ and provenance resource url: %@ for asset %@"
+ "Processed provenance resource created from asset: %@"
+ "Provenance processing for asset %{public}@ cancelled before develop"
+ "Provenance processing for asset %{public}@ cancelled during develop"
+ "Unable to remove processed provenance temp directory: %@"
+ "[PHAssetCreationRequestPlaceholderSupport] Failed to embed processed provenance into shared render for source asset %{public}@: %@; failing share"
+ "[PHAssetCreationRequestPlaceholderSupport] Missing original resource with provenance data for source asset %{public}@; failing share"
+ "[PHAssetCreationRequestPlaceholderSupport] No Photo resource to regenerate provenance for source asset %{public}@; failing share"
+ "[PHAssetExportRequest] Adjusted processed provenance asset missing original or full-size photo URL."
+ "[PHAssetExportRequest] Asset is unprocessed provenance but we are missing the original photo. "
+ "[PHAssetExportRequest] Expected to embed provenance into full-size render for asset %{public}@ but missing URL: fullSizePhoto=%{public}@ photo=%{public}@"
+ "[PHAssetExportRequest] Export request processing required for asset %{public}@: %{BOOL}d (metadataOperationLocation=%{public}@, metadataOperationProvenance=%{public}@, metadataOperationCaption=%{public}@, metadataOperationCaptionAccessibilityDescription=%{public}@, metadataOperationKeywords=%{public}@, metadataChangeCustomDate=%{private}@, livePhotoMetadataFixup=%{BOOL}d producingNewFilesForExport=%{BOOL}d, options.variant=%{public}@, requiresSloMoFlattening=%{BOOL}d, videoExportPreset=%{public}@, type = %{public}@, needsReplacementLivePhotoIdentifier = %{BOOL}d %{public}@"
+ "[PHAssetExportRequest] Failed to build processed provenance creation request for asset %{public}@"
+ "[PHAssetExportRequest] Failed to insert processed provenance asset: %@"
+ "[PHAssetExportRequest] Failed to remove staging directory at %@: %@"
+ "[PHAssetExportRequest] Failed to remove temporary processed provenance original directory for asset %{public}@: %@"
+ "[PHAssetExportRequest] Failed to retrieve required resources for processed provenance insertion for asset %{public}@ (success=%d cancelled=%d): %@"
+ "[PHAssetExportRequest] Failed to stage processed provenance resource for asset %{public}@: %@"
+ "[PHAssetExportRequest] Inserting processed provenance asset for asset %{public}@"
+ "[PHAssetExportRequest] Processed provenance insertion for asset %{public}@ completed (request: %p)"
+ "[PHAssetExportRequest] Returning provenanceMetadataOperation: %ld. Asset state: %hi"
+ "[PHAssetExportRequest] Skipping processed-provenance insertion for asset %{public}@: exported resource is not processed provenance (state=%hd)"
+ "[PHAssetExportRequest] We processed fileURLs %@. Removing the DNG and remained with these fileURLs to share: %@"
+ "[PHInternalAssetExportRequest] Waiting for provenance combining of resources of asset %{public}@..."
+ "[PHResourceLocalAvailabilityRequest: %llu] Failed to refetch resources for combined provenance asset: %{public}@, "
+ "[PHResourceLocalAvailabilityRequest] Refusing to pair provenance sidecar with derivative-only resources for asset: %@, resources: %@, options: %@"
+ "[PHResourceLocalAvailabilityRequest] Routing edited provenance render to FullSizePhotoURLKey (keeping original in PhotoURLKey) for asset:%@"
+ "[PHResourceLocalAvailabilityRequest] Selected original as provenance source but no full-size render is available to carry it for asset: %@, resources: %@, options: %@"
+ "[PHResourceLocalAvailabilityRequest] Using original/primary resource(s): %{BOOL}d for asset %{public}@ because it is edited: %{BOOL}d, known unsupported: %{BOOL}d, isRAW: %{BOOL}d, dontAllowRAW: %{BOOL}d, should use unmodified original: %{BOOL}d requiresCombinedProvenance:%{BOOL}d"
+ "_PHResourceLocalAvailabilityRequestResourceTypeCombinedProvenance"
+ "_PHResourceLocalAvailabilityRequestResourceTypeOriginalProvenance"
+ "asset %{public}@ is ineligible for provenance processing (savedAssetType: %{public}@)"
+ "asset %{public}@ is not in unprocessed provenance (state: %d)"
+ "asset %{public}@ is trashed; refusing create a provenance processing request"
+ "combined_provenance"
+ "hasProvenanceData"
+ "originalProvenanceAssetFilename"
+ "originalProvenanceAssetUUID"
+ "powderState"
+ "provenance"
+ "provenance combining"
+ "provenance resource not for display"
+ "provenance-embed-"
+ "shouldCopyProvenanceData"
+ "smartAlbumProvenance"
+ "v24@?0q8@\"NSError\"16"
+ "void PHAssetExportRequestPerformMediaConversion(PHMediaFormatConversionSource *__strong, BOOL, BOOL, UTType * _Nullable __strong, PHAssetExportRequestMetadataOperation, CLLocation * _Nullable __strong, NSDate * _Nullable __strong, NSTimeZone * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSArray<NSString *> * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSURL *__strong, NSURL *__strong, NSURL *__strong, NSURL *__strong, BOOL, NSString * _Nullable __strong, NSProgress *__strong, int64_t, NSURL *__strong, BOOL, NSString *__strong, NSString * _Nullable __strong, void (^__strong)(NSURL * _Nullable __strong, NSError * _Nullable __strong))"
- "<%@: %p, variant: \"%@\", livePhotoAsStill: %d, allowRaw: %d, flattenSlomo: %d, stripLocation: %d, stripCaption: %d, stripAXDescription: %d, stripKeywords: %d, assetBundle: %d, disableMetadataCorrections: %d, unmodifiedOriginals: %d>"
- "PHQueryForAssetCollectionType_Album_block_invoke_108"
- "PHQueryForAssetCollectionType_CollectionShare_block_invoke_120"
- "PHQueryForAssetCollectionType_Conversation_block_invoke_117"
- "PHQueryForAssetCollectionType_ImportSession_block_invoke_116"
- "PHQueryForAssetCollectionType_Memory_block_invoke_112"
- "PHQueryForAssetCollectionType_MomentShare_block_invoke_114"
- "PHQueryForAssetCollectionType_Moment_block_invoke_109"
- "PHQueryForAssetCollectionType_NoFetchType_block_invoke_122"
- "PHQueryForAssetCollectionType_Other_block_invoke_121"
- "PHQueryForAssetCollectionType_PhotosHighlight_block_invoke_113"
- "PHQueryForAssetCollectionType_Project_block_invoke_118"
- "PHQueryForAssetCollectionType_SmartAlbum_block_invoke_110"
- "PHQueryForAssetCollectionType_Suggestion_block_invoke_115"
- "PHQueryForAssetCollectionType_Unknown_block_invoke_111"
- "PHQueryForAssetCollectionType_Utility_block_invoke_119"
- "PHQueryForAssetInAlbumKind_ActionCamVideoAlbum_block_invoke_98"
- "PHQueryForAssetInAlbumKind_ProResAlbum_block_invoke_97"
- "PHQueryForAssetInAlbumKind_SharedLibrarySharingSuggestionsAlbum_block_invoke_96"
- "PHQueryForAssetsAlbum_SortKeyOther_block_invoke_99"
- "PHQueryForAssetsInAlbum_SortKeyContentTitle_block_invoke_107"
- "PHQueryForAssetsInAlbum_SortKeyCreationDate_block_invoke_101"
- "PHQueryForAssetsInAlbum_SortKeyImportDate_block_invoke_103"
- "PHQueryForAssetsInAlbum_SortKeyLastModifiedDate_block_invoke_102"
- "PHQueryForAssetsInAlbum_SortKeyManual_block_invoke_100"
- "PHQueryForAssetsInAlbum_SortKeyPublishDate_block_invoke_106"
- "PHQueryForAssetsInAlbum_SortKeyTitle_block_invoke_105"
- "PHQueryForAssetsInAlbum_SortKeyTrashDate_block_invoke_104"
- "PHQueryForAssetsInUtility_GenericDocument_block_invoke_132"
- "PHQueryForAssetsInUtility_Handwriting_block_invoke_135"
- "PHQueryForAssetsInUtility_IdentityDocuments_block_invoke_138"
- "PHQueryForAssetsInUtility_Illustrations_block_invoke_134"
- "PHQueryForAssetsInUtility_Maps_block_invoke_137"
- "PHQueryForAssetsInUtility_Other_block_invoke_139"
- "PHQueryForAssetsInUtility_QRCodes_block_invoke_136"
- "PHQueryForAssetsInUtility_Receipts_block_invoke_133"
- "PHQueryForTransientAssetCollectionType_Generic_block_invoke_123"
- "PHQueryForTransientAssetCollectionType_ImportHistory_block_invoke_124"
- "PHQueryForTransientAssetCollectionType_Other_block_invoke_131"
- "PHQueryForTransientAssetCollectionType_RecentlyEdited_block_invoke_125"
- "PHQueryForTransientAssetCollectionType_RecentlyShared_block_invoke_126"
- "PHQueryForTransientAssetCollectionType_RecentlyViewed_block_invoke_127"
- "PHQueryForTransientAssetCollectionType_SavedToday_block_invoke_130"
- "PHQueryForTransientAssetCollectionType_SearchCollectionResults_block_invoke_129"
- "PHQueryForTransientAssetCollectionType_SearchTopResults_block_invoke_128"
- "[PHAssetExportRequest] Export request processing required for asset %{public}@: %{BOOL}d (metadataOperationLocation=%{public}@, metadataOperationCaption=%{public}@, metadataOperationCaptionAccessibilityDescription=%{public}@, metadataOperationKeywords=%{public}@, metadataChangeCustomDate=%{private}@, livePhotoMetadataFixup=%{BOOL}d producingNewFilesForExport=%{BOOL}d, options.variant=%{public}@, requiresSloMoFlattening=%{BOOL}d, videoExportPreset=%{public}@, type = %{public}@, needsReplacementLivePhotoIdentifier = %{BOOL}d %{public}@"
- "[PHResourceLocalAvailabilityRequest] Using original/primary resource(s): %{BOOL}d for asset %{public}@ because it is edited: %{BOOL}d, known unsupported: %{BOOL}d, isRAW: %{BOOL}d, dontAllowRAW: %{BOOL}d, should use unmodified original: %{BOOL}d"
- "void PHAssetExportRequestPerformMediaConversion(PHMediaFormatConversionSource *__strong, BOOL, BOOL, UTType * _Nullable __strong, PHAssetExportRequestMetadataOperation, CLLocation * _Nullable __strong, NSDate * _Nullable __strong, NSTimeZone * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSArray<NSString *> * _Nullable __strong, NSString * _Nullable __strong, NSProgress *__strong, int64_t, NSURL *__strong, BOOL, NSString *__strong, NSString * _Nullable __strong, void (^__strong)(NSURL * _Nullable __strong, NSError * _Nullable __strong))"
```
