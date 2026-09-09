## NeutrinoCore

> `/System/Library/PrivateFrameworks/NeutrinoCore.framework/Versions/A/NeutrinoCore`

```diff

 911.0.134.0.0
-  __TEXT.__text: 0x340944
-  __TEXT.__objc_methlist: 0x2046c
+  __TEXT.__text: 0x344448
+  __TEXT.__objc_methlist: 0x20834
   __TEXT.__const: 0x2918
+  __TEXT.__dlopen_cstrs: 0x45
   __TEXT.__swift5_typeref: 0x3e7
   __TEXT.__swift5_reflstr: 0x93
   __TEXT.__swift5_assocty: 0xa8

   __TEXT.__swift5_fieldmd: 0x178
   __TEXT.__swift5_proto: 0x7c
   __TEXT.__swift5_types: 0x2c
-  __TEXT.__cstring: 0x3f510
+  __TEXT.__cstring: 0x3fbf3
   __TEXT.__swift5_capture: 0x210
-  __TEXT.__gcc_except_tab: 0x7fe8
-  __TEXT.__oslogstring: 0x550b
+  __TEXT.__gcc_except_tab: 0x8060
+  __TEXT.__oslogstring: 0x57c3
   __TEXT.__ustring: 0x2e
-  __TEXT.__unwind_info: 0x8700
+  __TEXT.__unwind_info: 0x8748
   __TEXT.__eh_frame: 0x430
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x15f0
-  __DATA_CONST.__objc_classlist: 0x15b8
+  __DATA_CONST.__const: 0x1610
+  __DATA_CONST.__objc_classlist: 0x15c8
   __DATA_CONST.__objc_catlist: 0xa8
-  __DATA_CONST.__objc_protolist: 0x4f0
+  __DATA_CONST.__objc_protolist: 0x500
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb358
+  __DATA_CONST.__objc_selrefs: 0xb4a8
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0xfe8
   __DATA_CONST.__objc_arraydata: 0xac0
-  __DATA_CONST.__got: 0x2220
-  __AUTH_CONST.__const: 0x80d8
-  __AUTH_CONST.__cfstring: 0x1ca20
-  __AUTH_CONST.__objc_const: 0x36110
+  __DATA_CONST.__got: 0x2240
+  __AUTH_CONST.__const: 0x8108
+  __AUTH_CONST.__cfstring: 0x1cf20
+  __AUTH_CONST.__objc_const: 0x36938
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x8b8
   __AUTH_CONST.__objc_dictobj: 0x320
   __AUTH_CONST.__objc_doubleobj: 0x210
   __AUTH_CONST.__objc_floatobj: 0x70
   __AUTH_CONST.__objc_arrayobj: 0xf0
-  __AUTH_CONST.__auth_got: 0xfd0
-  __AUTH.__objc_data: 0x50
-  __DATA.__objc_ivar: 0x196c
-  __DATA.__data: 0x3898
+  __AUTH_CONST.__auth_got: 0xfe8
+  __AUTH.__objc_data: 0xf0
+  __DATA.__objc_ivar: 0x19c4
+  __DATA.__data: 0x3958
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x1270
+  __DATA.__bss: 0x1280
   __DATA_DIRTY.__objc_data: 0xd8e0
   __DATA_DIRTY.__data: 0x8
-  __DATA_DIRTY.__bss: 0x1e0
+  __DATA_DIRTY.__bss: 0x1e8
   __DATA_DIRTY.__common: 0x40
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /System/Library/PrivateFrameworks/CMPhoto.framework/Versions/A/CMPhoto
   - /System/Library/PrivateFrameworks/PhotoFoundation.framework/Versions/A/PhotoFoundation
   - /System/Library/PrivateFrameworks/PhotosFormats.framework/Versions/A/PhotosFormats
+  - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11793
-  Symbols:   25260
-  CStrings:  7178
+  Functions: 11858
+  Symbols:   25430
+  CStrings:  7245
 
Symbols:
+ +[NUVideoUtilities metadataTrackContainsTextureStyleData:]
+ +[_NUTextureStylePersonInstanceProperties personInstancePropertiesFromDictionary:error:]
+ +[_NUTextureStyleProperties textureStylePropertiesFromImageMetadata:auxImageMetadata:error:]
+ +[_NUTextureStyleProperties textureStyleVideoPropertiesFromTextureStyleData:faceInfoData:error:]
+ -[NUCGImageSourceNode _loadTextureStylesProperties:error:]
+ -[NUCGImageSourceNode hasProvenanceData]
+ -[NUCGImageSourceNode setHasProvenanceData:]
+ -[NUCGImageSourceNode setTextureStylesProperties:]
+ -[NUCGImageSourceNode textureStylesProperties]
+ -[NUImageExportRequest embedProvenanceData]
+ -[NUImageExportRequest setEmbedProvenanceData:]
+ -[_NUImageProperties hasProvenanceData]
+ -[_NUImageProperties setHasProvenanceData:]
+ -[_NUImageProperties setTextureStyleProperties:]
+ -[_NUImageProperties textureStyleProperties]
+ -[_NUSemanticStyleProperties linearHighKey]
+ -[_NUSemanticStyleProperties revertUsingOriginal]
+ -[_NUSemanticStyleProperties setLinearHighKey:]
+ -[_NUSemanticStyleProperties setRevertUsingOriginal:]
+ -[_NUTextureStylePersonInstanceProperties .cxx_destruct]
+ -[_NUTextureStylePersonInstanceProperties copyWithZone:]
+ -[_NUTextureStylePersonInstanceProperties description]
+ -[_NUTextureStylePersonInstanceProperties instanceMaskReferenceKey]
+ -[_NUTextureStylePersonInstanceProperties maskSize]
+ -[_NUTextureStylePersonInstanceProperties nu_updateDigest:]
+ -[_NUTextureStylePersonInstanceProperties opaquePersonInfo]
+ -[_NUTextureStylePersonInstanceProperties pixelFormat]
+ -[_NUTextureStylePersonInstanceProperties setInstanceMaskReferenceKey:]
+ -[_NUTextureStylePersonInstanceProperties setMaskSize:]
+ -[_NUTextureStylePersonInstanceProperties setOpaquePersonInfo:]
+ -[_NUTextureStylePersonInstanceProperties setPixelFormat:]
+ -[_NUTextureStyleProperties .cxx_destruct]
+ -[_NUTextureStyleProperties captureMode]
+ -[_NUTextureStyleProperties captureType]
+ -[_NUTextureStyleProperties copyWithZone:]
+ -[_NUTextureStyleProperties description]
+ -[_NUTextureStyleProperties filmGrainSeed]
+ -[_NUTextureStyleProperties hardwareModel]
+ -[_NUTextureStyleProperties isVideo]
+ -[_NUTextureStyleProperties nu_updateDigest:]
+ -[_NUTextureStyleProperties numberOfPersons]
+ -[_NUTextureStyleProperties personInstances]
+ -[_NUTextureStyleProperties portType]
+ -[_NUTextureStyleProperties setCaptureMode:]
+ -[_NUTextureStyleProperties setCaptureType:]
+ -[_NUTextureStyleProperties setFilmGrainSeed:]
+ -[_NUTextureStyleProperties setHardwareModel:]
+ -[_NUTextureStyleProperties setIsVideo:]
+ -[_NUTextureStyleProperties setNumberOfPersons:]
+ -[_NUTextureStyleProperties setPersonInstances:]
+ -[_NUTextureStyleProperties setPortType:]
+ -[_NUTextureStyleProperties setVersion:]
+ -[_NUTextureStyleProperties setVideoFacesInfoData:]
+ -[_NUTextureStyleProperties setVideoOpaquePersonsInfo:]
+ -[_NUTextureStyleProperties version]
+ -[_NUTextureStyleProperties videoFacesInfoData]
+ -[_NUTextureStyleProperties videoOpaquePersonsInfo]
+ GCC_except_table10061
+ GCC_except_table10071
+ GCC_except_table10286
+ GCC_except_table10287
+ GCC_except_table10293
+ GCC_except_table10294
+ GCC_except_table10296
+ GCC_except_table10297
+ GCC_except_table10394
+ GCC_except_table10398
+ GCC_except_table10399
+ GCC_except_table10400
+ GCC_except_table10401
+ GCC_except_table10402
+ GCC_except_table10403
+ GCC_except_table10412
+ GCC_except_table10416
+ GCC_except_table10434
+ GCC_except_table10435
+ GCC_except_table10437
+ GCC_except_table10444
+ GCC_except_table10445
+ GCC_except_table10446
+ GCC_except_table10447
+ GCC_except_table10450
+ GCC_except_table10453
+ GCC_except_table10454
+ GCC_except_table10457
+ GCC_except_table10460
+ GCC_except_table10461
+ GCC_except_table10469
+ GCC_except_table10470
+ GCC_except_table10471
+ GCC_except_table10472
+ GCC_except_table10473
+ GCC_except_table10474
+ GCC_except_table10476
+ GCC_except_table10478
+ GCC_except_table10479
+ GCC_except_table10480
+ GCC_except_table10485
+ GCC_except_table10486
+ GCC_except_table10487
+ GCC_except_table10488
+ GCC_except_table10489
+ GCC_except_table10491
+ GCC_except_table10492
+ GCC_except_table10493
+ GCC_except_table10494
+ GCC_except_table10495
+ GCC_except_table10496
+ GCC_except_table10497
+ GCC_except_table10498
+ GCC_except_table10503
+ GCC_except_table10504
+ GCC_except_table10505
+ GCC_except_table10506
+ GCC_except_table10507
+ GCC_except_table10508
+ GCC_except_table10566
+ GCC_except_table10617
+ GCC_except_table10706
+ GCC_except_table10710
+ GCC_except_table11154
+ GCC_except_table11315
+ GCC_except_table11317
+ GCC_except_table11363
+ GCC_except_table11417
+ GCC_except_table11425
+ GCC_except_table11432
+ GCC_except_table11433
+ GCC_except_table11437
+ GCC_except_table1939
+ GCC_except_table2066
+ GCC_except_table2067
+ GCC_except_table2068
+ GCC_except_table2069
+ GCC_except_table2071
+ GCC_except_table2096
+ GCC_except_table2150
+ GCC_except_table2259
+ GCC_except_table2260
+ GCC_except_table2797
+ GCC_except_table2862
+ GCC_except_table2912
+ GCC_except_table2924
+ GCC_except_table3083
+ GCC_except_table3230
+ GCC_except_table3310
+ GCC_except_table3317
+ GCC_except_table3318
+ GCC_except_table3321
+ GCC_except_table3322
+ GCC_except_table3323
+ GCC_except_table3326
+ GCC_except_table3327
+ GCC_except_table3330
+ GCC_except_table3333
+ GCC_except_table3334
+ GCC_except_table3338
+ GCC_except_table3343
+ GCC_except_table3345
+ GCC_except_table3346
+ GCC_except_table3361
+ GCC_except_table3362
+ GCC_except_table3374
+ GCC_except_table3390
+ GCC_except_table3391
+ GCC_except_table3396
+ GCC_except_table3397
+ GCC_except_table3399
+ GCC_except_table3402
+ GCC_except_table3403
+ GCC_except_table3407
+ GCC_except_table3410
+ GCC_except_table3411
+ GCC_except_table3414
+ GCC_except_table3415
+ GCC_except_table3418
+ GCC_except_table3420
+ GCC_except_table3422
+ GCC_except_table3423
+ GCC_except_table3424
+ GCC_except_table3425
+ GCC_except_table3426
+ GCC_except_table3430
+ GCC_except_table3436
+ GCC_except_table3788
+ GCC_except_table3969
+ GCC_except_table4038
+ GCC_except_table4042
+ GCC_except_table4044
+ GCC_except_table4181
+ GCC_except_table4191
+ GCC_except_table4199
+ GCC_except_table4207
+ GCC_except_table4212
+ GCC_except_table4235
+ GCC_except_table4242
+ GCC_except_table4247
+ GCC_except_table4249
+ GCC_except_table4376
+ GCC_except_table4377
+ GCC_except_table4378
+ GCC_except_table4381
+ GCC_except_table4382
+ GCC_except_table4383
+ GCC_except_table4390
+ GCC_except_table4395
+ GCC_except_table4396
+ GCC_except_table4397
+ GCC_except_table4399
+ GCC_except_table4401
+ GCC_except_table4416
+ GCC_except_table4418
+ GCC_except_table4479
+ GCC_except_table4480
+ GCC_except_table4483
+ GCC_except_table4484
+ GCC_except_table4489
+ GCC_except_table4490
+ GCC_except_table4493
+ GCC_except_table4494
+ GCC_except_table4495
+ GCC_except_table4496
+ GCC_except_table4497
+ GCC_except_table4498
+ GCC_except_table4499
+ GCC_except_table4501
+ GCC_except_table4507
+ GCC_except_table4511
+ GCC_except_table4515
+ GCC_except_table4516
+ GCC_except_table4517
+ GCC_except_table4519
+ GCC_except_table4526
+ GCC_except_table4528
+ GCC_except_table4529
+ GCC_except_table4604
+ GCC_except_table4906
+ GCC_except_table5017
+ GCC_except_table5023
+ GCC_except_table5026
+ GCC_except_table5036
+ GCC_except_table5040
+ GCC_except_table5041
+ GCC_except_table5055
+ GCC_except_table5165
+ GCC_except_table5299
+ GCC_except_table5381
+ GCC_except_table5673
+ GCC_except_table5776
+ GCC_except_table5801
+ GCC_except_table5837
+ GCC_except_table5841
+ GCC_except_table5846
+ GCC_except_table5855
+ GCC_except_table5856
+ GCC_except_table5860
+ GCC_except_table5896
+ GCC_except_table5960
+ GCC_except_table5962
+ GCC_except_table5963
+ GCC_except_table5968
+ GCC_except_table5969
+ GCC_except_table5981
+ GCC_except_table5991
+ GCC_except_table5992
+ GCC_except_table6001
+ GCC_except_table6003
+ GCC_except_table6005
+ GCC_except_table6006
+ GCC_except_table6014
+ GCC_except_table6021
+ GCC_except_table6022
+ GCC_except_table6027
+ GCC_except_table6028
+ GCC_except_table6029
+ GCC_except_table6031
+ GCC_except_table6032
+ GCC_except_table6033
+ GCC_except_table6034
+ GCC_except_table6035
+ GCC_except_table6040
+ GCC_except_table6041
+ GCC_except_table6042
+ GCC_except_table6043
+ GCC_except_table6045
+ GCC_except_table6046
+ GCC_except_table6050
+ GCC_except_table6051
+ GCC_except_table6052
+ GCC_except_table6053
+ GCC_except_table6054
+ GCC_except_table6055
+ GCC_except_table6056
+ GCC_except_table6057
+ GCC_except_table6059
+ GCC_except_table6061
+ GCC_except_table6064
+ GCC_except_table6065
+ GCC_except_table6066
+ GCC_except_table6067
+ GCC_except_table6068
+ GCC_except_table6070
+ GCC_except_table6072
+ GCC_except_table6073
+ GCC_except_table6075
+ GCC_except_table6076
+ GCC_except_table6184
+ GCC_except_table6188
+ GCC_except_table6248
+ GCC_except_table6280
+ GCC_except_table6281
+ GCC_except_table6318
+ GCC_except_table6324
+ GCC_except_table6332
+ GCC_except_table6353
+ GCC_except_table6433
+ GCC_except_table6445
+ GCC_except_table6450
+ GCC_except_table6457
+ GCC_except_table6475
+ GCC_except_table6493
+ GCC_except_table6496
+ GCC_except_table6497
+ GCC_except_table6501
+ GCC_except_table6502
+ GCC_except_table6605
+ GCC_except_table6614
+ GCC_except_table6634
+ GCC_except_table6651
+ GCC_except_table6725
+ GCC_except_table6791
+ GCC_except_table6796
+ GCC_except_table6799
+ GCC_except_table6822
+ GCC_except_table6866
+ GCC_except_table7009
+ GCC_except_table7084
+ GCC_except_table7099
+ GCC_except_table7100
+ GCC_except_table7101
+ GCC_except_table7114
+ GCC_except_table7115
+ GCC_except_table7116
+ GCC_except_table7117
+ GCC_except_table7132
+ GCC_except_table7133
+ GCC_except_table7147
+ GCC_except_table7148
+ GCC_except_table7153
+ GCC_except_table7193
+ GCC_except_table7266
+ GCC_except_table7267
+ GCC_except_table7271
+ GCC_except_table7273
+ GCC_except_table7277
+ GCC_except_table7279
+ GCC_except_table7281
+ GCC_except_table7282
+ GCC_except_table7286
+ GCC_except_table7290
+ GCC_except_table7291
+ GCC_except_table7294
+ GCC_except_table7295
+ GCC_except_table7296
+ GCC_except_table7298
+ GCC_except_table7299
+ GCC_except_table7301
+ GCC_except_table7302
+ GCC_except_table7372
+ GCC_except_table7409
+ GCC_except_table7448
+ GCC_except_table7449
+ GCC_except_table7499
+ GCC_except_table8192
+ GCC_except_table8195
+ GCC_except_table8263
+ GCC_except_table8402
+ GCC_except_table8411
+ GCC_except_table8414
+ GCC_except_table8416
+ GCC_except_table8421
+ GCC_except_table8435
+ GCC_except_table8437
+ GCC_except_table8438
+ GCC_except_table8443
+ GCC_except_table8444
+ GCC_except_table8464
+ GCC_except_table8471
+ GCC_except_table8472
+ GCC_except_table8473
+ GCC_except_table8474
+ GCC_except_table8487
+ GCC_except_table8675
+ GCC_except_table8722
+ GCC_except_table9065
+ GCC_except_table9150
+ GCC_except_table9328
+ GCC_except_table9522
+ GCC_except_table9537
+ GCC_except_table9574
+ GCC_except_table9621
+ GCC_except_table9622
+ GCC_except_table9623
+ GCC_except_table9624
+ GCC_except_table9629
+ GCC_except_table9659
+ GCC_except_table9660
+ GCC_except_table9661
+ GCC_except_table9666
+ GCC_except_table9668
+ GCC_except_table9669
+ GCC_except_table9670
+ GCC_except_table9671
+ GCC_except_table9675
+ GCC_except_table9676
+ GCC_except_table9678
+ GCC_except_table9680
+ GCC_except_table9682
+ GCC_except_table9684
+ GCC_except_table9690
+ GCC_except_table9693
+ GCC_except_table9697
+ GCC_except_table9698
+ GCC_except_table9700
+ GCC_except_table9701
+ GCC_except_table9702
+ GCC_except_table9703
+ GCC_except_table9704
+ GCC_except_table9706
+ GCC_except_table9707
+ GCC_except_table9708
+ GCC_except_table9709
+ GCC_except_table9710
+ GCC_except_table9711
+ GCC_except_table9712
+ GCC_except_table9713
+ GCC_except_table9714
+ GCC_except_table9716
+ GCC_except_table9717
+ GCC_except_table9718
+ GCC_except_table9719
+ GCC_except_table9720
+ GCC_except_table9721
+ GCC_except_table9723
+ GCC_except_table9780
+ GCC_except_table9787
+ GCC_except_table9865
+ GCC_except_table9937
+ GCC_except_table9938
+ GCC_except_table9942
+ GCC_except_table9943
+ GCC_except_table9944
+ GCC_except_table9945
+ GCC_except_table9952
+ GCC_except_table9953
+ GCC_except_table9962
+ GCC_except_table9972
+ GCC_except_table9978
+ GCC_except_table9979
+ GCC_except_table9980
+ GCC_except_table9982
+ GCC_except_table9984
+ GCC_except_table9987
+ GCC_except_table9988
+ GCC_except_table9989
+ ImageIOLibraryCore.frameworkLibrary
+ OBJC_IVAR_$_NUCGImageSourceNode._hasProvenanceData
+ OBJC_IVAR_$_NUCGImageSourceNode._textureStylesProperties
+ OBJC_IVAR_$_NUImageExportRequest._embedProvenanceData
+ OBJC_IVAR_$__NUImageProperties._hasProvenanceData
+ OBJC_IVAR_$__NUImageProperties._textureStyleProperties
+ OBJC_IVAR_$__NUSemanticStyleProperties._linearHighKey
+ OBJC_IVAR_$__NUSemanticStyleProperties._revertUsingOriginal
+ OBJC_IVAR_$__NUTextureStylePersonInstanceProperties._instanceMaskReferenceKey
+ OBJC_IVAR_$__NUTextureStylePersonInstanceProperties._maskSize
+ OBJC_IVAR_$__NUTextureStylePersonInstanceProperties._opaquePersonInfo
+ OBJC_IVAR_$__NUTextureStylePersonInstanceProperties._pixelFormat
+ OBJC_IVAR_$__NUTextureStyleProperties._captureMode
+ OBJC_IVAR_$__NUTextureStyleProperties._captureType
+ OBJC_IVAR_$__NUTextureStyleProperties._filmGrainSeed
+ OBJC_IVAR_$__NUTextureStyleProperties._hardwareModel
+ OBJC_IVAR_$__NUTextureStyleProperties._isVideo
+ OBJC_IVAR_$__NUTextureStyleProperties._numberOfPersons
+ OBJC_IVAR_$__NUTextureStyleProperties._personInstances
+ OBJC_IVAR_$__NUTextureStyleProperties._portType
+ OBJC_IVAR_$__NUTextureStyleProperties._version
+ OBJC_IVAR_$__NUTextureStyleProperties._videoFacesInfoData
+ OBJC_IVAR_$__NUTextureStyleProperties._videoOpaquePersonsInfo
+ _ImageIOLibrary
+ _ImageIOLibraryCore
+ _NUAuxiliaryImagesPropertiesKeyFromReferenceKey
+ _NUTextureStyleMetadataKey_FaceAttitude
+ _OBJC_CLASS_$__NUTextureStylePersonInstanceProperties
+ _OBJC_CLASS_$__NUTextureStyleProperties
+ _OBJC_METACLASS_$__NUTextureStylePersonInstanceProperties
+ _OBJC_METACLASS_$__NUTextureStyleProperties
+ __OBJC_$_CLASS_METHODS__NUTextureStylePersonInstanceProperties
+ __OBJC_$_CLASS_METHODS__NUTextureStyleProperties
+ __OBJC_$_INSTANCE_METHODS__NUTextureStylePersonInstanceProperties
+ __OBJC_$_INSTANCE_METHODS__NUTextureStyleProperties
+ __OBJC_$_INSTANCE_VARIABLES__NUTextureStylePersonInstanceProperties
+ __OBJC_$_INSTANCE_VARIABLES__NUTextureStyleProperties
+ __OBJC_$_PROP_LIST_NUTextureStylePersonInstanceProperties
+ __OBJC_$_PROP_LIST_NUTextureStyleProperties
+ __OBJC_$_PROP_LIST__NUTextureStylePersonInstanceProperties
+ __OBJC_$_PROP_LIST__NUTextureStyleProperties
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NUTextureStylePersonInstanceProperties
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NUTextureStyleProperties
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NUTextureStylePersonInstanceProperties
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NUTextureStyleProperties
+ __OBJC_$_PROTOCOL_REFS_NUTextureStylePersonInstanceProperties
+ __OBJC_$_PROTOCOL_REFS_NUTextureStyleProperties
+ __OBJC_CLASS_PROTOCOLS_$__NUTextureStylePersonInstanceProperties
+ __OBJC_CLASS_PROTOCOLS_$__NUTextureStyleProperties
+ __OBJC_CLASS_RO_$__NUTextureStylePersonInstanceProperties
+ __OBJC_CLASS_RO_$__NUTextureStyleProperties
+ __OBJC_LABEL_PROTOCOL_$_NUTextureStylePersonInstanceProperties
+ __OBJC_LABEL_PROTOCOL_$_NUTextureStyleProperties
+ __OBJC_METACLASS_RO_$__NUTextureStylePersonInstanceProperties
+ __OBJC_METACLASS_RO_$__NUTextureStyleProperties
+ __OBJC_PROTOCOL_$_NUTextureStylePersonInstanceProperties
+ __OBJC_PROTOCOL_$_NUTextureStyleProperties
+ ___ImageIOLibraryCore_block_invoke
+ ___block_descriptor_40_e8_32r_e5_v8?0l
+ ___getCGImageDestinationSetProvenanceDataSymbolLoc_block_invoke
+ ___getCGImageSourceCopyProvenanceDataAtIndexSymbolLoc_block_invoke
+ __sl_dlopen
+ _audit_stringImageIO
+ _dlerror
+ _dlsym
+ _getCGImageSourceCopyProvenanceDataAtIndexSymbolLoc
+ _kCMPhotoCustomMetadataTypeURN_Provenance_ProcessedImage
+ _kCMPhotoCustomMetadataTypeURN_Provenance_UnprocessedImage
+ _kMetadataIdentifier_TextureStyleInfo
+ _objc_msgSend$_loadPersonInstanceMaskMetadata
+ _objc_msgSend$_loadTextureStylesProperties:error:
+ _objc_msgSend$captureMode
+ _objc_msgSend$captureType
+ _objc_msgSend$embedProvenanceData
+ _objc_msgSend$filmGrainSeed
+ _objc_msgSend$hardwareModel
+ _objc_msgSend$hasProvenanceData
+ _objc_msgSend$instanceMaskReferenceKey
+ _objc_msgSend$linearHighKey
+ _objc_msgSend$maskSize
+ _objc_msgSend$metadataTrackContainsTextureStyleData:
+ _objc_msgSend$numberOfPersons
+ _objc_msgSend$opaquePersonInfo
+ _objc_msgSend$personInstancePropertiesFromDictionary:error:
+ _objc_msgSend$personInstances
+ _objc_msgSend$portType
+ _objc_msgSend$revertUsingOriginal
+ _objc_msgSend$setCaptureMode:
+ _objc_msgSend$setCaptureType:
+ _objc_msgSend$setFilmGrainSeed:
+ _objc_msgSend$setHardwareModel:
+ _objc_msgSend$setHasProvenanceData:
+ _objc_msgSend$setInstanceMaskReferenceKey:
+ _objc_msgSend$setLinearHighKey:
+ _objc_msgSend$setMaskSize:
+ _objc_msgSend$setNumberOfPersons:
+ _objc_msgSend$setOpaquePersonInfo:
+ _objc_msgSend$setPersonInstances:
+ _objc_msgSend$setPortType:
+ _objc_msgSend$setRevertUsingOriginal:
+ _objc_msgSend$setTextureStyleProperties:
+ _objc_msgSend$setTextureStylesProperties:
+ _objc_msgSend$setVideoFacesInfoData:
+ _objc_msgSend$setVideoOpaquePersonsInfo:
+ _objc_msgSend$textureStyleProperties
+ _objc_msgSend$textureStylePropertiesFromImageMetadata:auxImageMetadata:error:
+ _objc_msgSend$textureStylesProperties
+ _objc_msgSend$unsignedShortValue
+ _objc_msgSend$videoFacesInfoData
+ _objc_msgSend$videoOpaquePersonsInfo
+ getCGImageDestinationSetProvenanceDataSymbolLoc.ptr
+ getCGImageSourceCopyProvenanceDataAtIndexSymbolLoc.ptr
- GCC_except_table10006
- GCC_except_table10221
- GCC_except_table10222
- GCC_except_table10228
- GCC_except_table10229
- GCC_except_table10231
- GCC_except_table10232
- GCC_except_table10329
- GCC_except_table10330
- GCC_except_table10333
- GCC_except_table10334
- GCC_except_table10335
- GCC_except_table10336
- GCC_except_table10337
- GCC_except_table10338
- GCC_except_table10340
- GCC_except_table10343
- GCC_except_table10344
- GCC_except_table10346
- GCC_except_table10347
- GCC_except_table10348
- GCC_except_table10350
- GCC_except_table10351
- GCC_except_table10361
- GCC_except_table10362
- GCC_except_table10367
- GCC_except_table10368
- GCC_except_table10369
- GCC_except_table10370
- GCC_except_table10372
- GCC_except_table10373
- GCC_except_table10374
- GCC_except_table10375
- GCC_except_table10377
- GCC_except_table10378
- GCC_except_table10379
- GCC_except_table10380
- GCC_except_table10381
- GCC_except_table10382
- GCC_except_table10385
- GCC_except_table10388
- GCC_except_table10389
- GCC_except_table10392
- GCC_except_table10396
- GCC_except_table10404
- GCC_except_table10406
- GCC_except_table10407
- GCC_except_table10414
- GCC_except_table10420
- GCC_except_table10421
- GCC_except_table10422
- GCC_except_table10423
- GCC_except_table10424
- GCC_except_table10428
- GCC_except_table10429
- GCC_except_table10430
- GCC_except_table10431
- GCC_except_table10441
- GCC_except_table10501
- GCC_except_table10552
- GCC_except_table10641
- GCC_except_table10645
- GCC_except_table11089
- GCC_except_table11250
- GCC_except_table11252
- GCC_except_table11298
- GCC_except_table11352
- GCC_except_table11360
- GCC_except_table11367
- GCC_except_table11368
- GCC_except_table11372
- GCC_except_table1934
- GCC_except_table2059
- GCC_except_table2060
- GCC_except_table2061
- GCC_except_table2062
- GCC_except_table2063
- GCC_except_table2090
- GCC_except_table2144
- GCC_except_table2249
- GCC_except_table2250
- GCC_except_table2742
- GCC_except_table2807
- GCC_except_table2857
- GCC_except_table2869
- GCC_except_table3028
- GCC_except_table3175
- GCC_except_table3255
- GCC_except_table3262
- GCC_except_table3263
- GCC_except_table3266
- GCC_except_table3267
- GCC_except_table3268
- GCC_except_table3271
- GCC_except_table3272
- GCC_except_table3275
- GCC_except_table3278
- GCC_except_table3279
- GCC_except_table3283
- GCC_except_table3286
- GCC_except_table3287
- GCC_except_table3288
- GCC_except_table3289
- GCC_except_table3290
- GCC_except_table3291
- GCC_except_table3292
- GCC_except_table3293
- GCC_except_table3301
- GCC_except_table3306
- GCC_except_table3307
- GCC_except_table3312
- GCC_except_table3319
- GCC_except_table3335
- GCC_except_table3336
- GCC_except_table3352
- GCC_except_table3355
- GCC_except_table3359
- GCC_except_table3360
- GCC_except_table3363
- GCC_except_table3365
- GCC_except_table3368
- GCC_except_table3369
- GCC_except_table3370
- GCC_except_table3371
- GCC_except_table3375
- GCC_except_table3381
- GCC_except_table3733
- GCC_except_table3914
- GCC_except_table3983
- GCC_except_table3987
- GCC_except_table3989
- GCC_except_table4126
- GCC_except_table4136
- GCC_except_table4137
- GCC_except_table4144
- GCC_except_table4152
- GCC_except_table4157
- GCC_except_table4180
- GCC_except_table4187
- GCC_except_table4194
- GCC_except_table4321
- GCC_except_table4322
- GCC_except_table4323
- GCC_except_table4326
- GCC_except_table4327
- GCC_except_table4328
- GCC_except_table4333
- GCC_except_table4335
- GCC_except_table4340
- GCC_except_table4341
- GCC_except_table4342
- GCC_except_table4344
- GCC_except_table4346
- GCC_except_table4361
- GCC_except_table4363
- GCC_except_table4424
- GCC_except_table4425
- GCC_except_table4428
- GCC_except_table4429
- GCC_except_table4434
- GCC_except_table4435
- GCC_except_table4438
- GCC_except_table4439
- GCC_except_table4440
- GCC_except_table4441
- GCC_except_table4442
- GCC_except_table4444
- GCC_except_table4446
- GCC_except_table4452
- GCC_except_table4456
- GCC_except_table4460
- GCC_except_table4461
- GCC_except_table4462
- GCC_except_table4464
- GCC_except_table4471
- GCC_except_table4473
- GCC_except_table4474
- GCC_except_table4549
- GCC_except_table4849
- GCC_except_table4960
- GCC_except_table4966
- GCC_except_table4969
- GCC_except_table4979
- GCC_except_table4983
- GCC_except_table4984
- GCC_except_table4998
- GCC_except_table5108
- GCC_except_table5242
- GCC_except_table5324
- GCC_except_table5616
- GCC_except_table5719
- GCC_except_table5744
- GCC_except_table5780
- GCC_except_table5782
- GCC_except_table5784
- GCC_except_table5789
- GCC_except_table5798
- GCC_except_table5799
- GCC_except_table5803
- GCC_except_table5858
- GCC_except_table5879
- GCC_except_table5884
- GCC_except_table5903
- GCC_except_table5905
- GCC_except_table5906
- GCC_except_table5911
- GCC_except_table5912
- GCC_except_table5914
- GCC_except_table5924
- GCC_except_table5927
- GCC_except_table5928
- GCC_except_table5929
- GCC_except_table5931
- GCC_except_table5934
- GCC_except_table5935
- GCC_except_table5937
- GCC_except_table5938
- GCC_except_table5940
- GCC_except_table5942
- GCC_except_table5943
- GCC_except_table5944
- GCC_except_table5945
- GCC_except_table5946
- GCC_except_table5947
- GCC_except_table5948
- GCC_except_table5949
- GCC_except_table5950
- GCC_except_table5951
- GCC_except_table5952
- GCC_except_table5957
- GCC_except_table5958
- GCC_except_table5964
- GCC_except_table5965
- GCC_except_table5970
- GCC_except_table5974
- GCC_except_table5975
- GCC_except_table5976
- GCC_except_table5977
- GCC_except_table5978
- GCC_except_table5983
- GCC_except_table5989
- GCC_except_table5996
- GCC_except_table6010
- GCC_except_table6011
- GCC_except_table6013
- GCC_except_table6016
- GCC_except_table6018
- GCC_except_table6019
- GCC_except_table6127
- GCC_except_table6131
- GCC_except_table6191
- GCC_except_table6223
- GCC_except_table6224
- GCC_except_table6261
- GCC_except_table6268
- GCC_except_table6289
- GCC_except_table6369
- GCC_except_table6381
- GCC_except_table6386
- GCC_except_table6393
- GCC_except_table6410
- GCC_except_table6428
- GCC_except_table6431
- GCC_except_table6432
- GCC_except_table6436
- GCC_except_table6437
- GCC_except_table6540
- GCC_except_table6549
- GCC_except_table6569
- GCC_except_table6586
- GCC_except_table6660
- GCC_except_table6726
- GCC_except_table6731
- GCC_except_table6734
- GCC_except_table6757
- GCC_except_table6801
- GCC_except_table6944
- GCC_except_table7019
- GCC_except_table7034
- GCC_except_table7035
- GCC_except_table7036
- GCC_except_table7049
- GCC_except_table7050
- GCC_except_table7051
- GCC_except_table7052
- GCC_except_table7067
- GCC_except_table7068
- GCC_except_table7082
- GCC_except_table7083
- GCC_except_table7088
- GCC_except_table7128
- GCC_except_table7201
- GCC_except_table7202
- GCC_except_table7206
- GCC_except_table7208
- GCC_except_table7212
- GCC_except_table7214
- GCC_except_table7216
- GCC_except_table7217
- GCC_except_table7221
- GCC_except_table7225
- GCC_except_table7226
- GCC_except_table7229
- GCC_except_table7230
- GCC_except_table7231
- GCC_except_table7233
- GCC_except_table7234
- GCC_except_table7236
- GCC_except_table7237
- GCC_except_table7307
- GCC_except_table7344
- GCC_except_table7383
- GCC_except_table7384
- GCC_except_table7434
- GCC_except_table8127
- GCC_except_table8130
- GCC_except_table8198
- GCC_except_table8337
- GCC_except_table8341
- GCC_except_table8346
- GCC_except_table8349
- GCC_except_table8351
- GCC_except_table8356
- GCC_except_table8370
- GCC_except_table8372
- GCC_except_table8373
- GCC_except_table8378
- GCC_except_table8379
- GCC_except_table8399
- GCC_except_table8407
- GCC_except_table8408
- GCC_except_table8409
- GCC_except_table8422
- GCC_except_table8610
- GCC_except_table8657
- GCC_except_table9000
- GCC_except_table9085
- GCC_except_table9263
- GCC_except_table9457
- GCC_except_table9472
- GCC_except_table9509
- GCC_except_table9516
- GCC_except_table9556
- GCC_except_table9557
- GCC_except_table9558
- GCC_except_table9559
- GCC_except_table9564
- GCC_except_table9570
- GCC_except_table9571
- GCC_except_table9578
- GCC_except_table9588
- GCC_except_table9590
- GCC_except_table9591
- GCC_except_table9593
- GCC_except_table9594
- GCC_except_table9595
- GCC_except_table9596
- GCC_except_table9601
- GCC_except_table9603
- GCC_except_table9604
- GCC_except_table9605
- GCC_except_table9606
- GCC_except_table9610
- GCC_except_table9611
- GCC_except_table9613
- GCC_except_table9615
- GCC_except_table9617
- GCC_except_table9619
- GCC_except_table9625
- GCC_except_table9628
- GCC_except_table9632
- GCC_except_table9633
- GCC_except_table9637
- GCC_except_table9638
- GCC_except_table9639
- GCC_except_table9641
- GCC_except_table9642
- GCC_except_table9644
- GCC_except_table9645
- GCC_except_table9647
- GCC_except_table9648
- GCC_except_table9649
- GCC_except_table9650
- GCC_except_table9651
- GCC_except_table9652
- GCC_except_table9654
- GCC_except_table9657
- GCC_except_table9800
- GCC_except_table9848
- GCC_except_table9872
- GCC_except_table9873
- GCC_except_table9877
- GCC_except_table9878
- GCC_except_table9879
- GCC_except_table9880
- GCC_except_table9887
- GCC_except_table9888
- GCC_except_table9897
- GCC_except_table9907
- GCC_except_table9914
- GCC_except_table9915
- GCC_except_table9917
- GCC_except_table9919
- GCC_except_table9922
- GCC_except_table9923
- GCC_except_table9924
- GCC_except_table9996
CStrings:
+ "%s"
+ "+[_NUTextureStylePersonInstanceProperties personInstancePropertiesFromDictionary:error:]"
+ "+[_NUTextureStyleProperties textureStylePropertiesFromImageMetadata:auxImageMetadata:error:]"
+ "+[_NUTextureStyleProperties textureStyleVideoPropertiesFromTextureStyleData:faceInfoData:error:]"
+ "/System/Library/Frameworks/ImageIO.framework/Contents/MacOS/ImageIO"
+ "<%@:%p referenceKey:%@>"
+ "<%@:%p version=%@ people:%lu hw=%@ port=%@ mode=%@ type=%@ seed=%@>"
+ "<%@:%p> url=%@ fileUTI=%@ size=%@ orientation=%@ colorSpace=%@ headroom=%f raw=%@ aux=%@ semanticStyle=%@ textureStyle=%@ metadata=%@"
+ "Bypassing revert for stills"
+ "CFDataRef  _Nullable soft_CGImageSourceCopyProvenanceDataAtIndex(CGImageSourceRef _Nonnull, size_t, uint32_t * _Nullable)"
+ "CGImageDestinationSetProvenanceData"
+ "CGImageSourceCopyProvenanceDataAtIndex"
+ "CaptureMode"
+ "CaptureType"
+ "Could not deserialize property list from texture metadata"
+ "Failed to extract provenance data, %{public}@"
+ "Failed to load person instance properties (%@), skipping"
+ "Failed to load texture style properties"
+ "FilmGrainSeed"
+ "HardwareModel"
+ "Invalid height value %@, skipping"
+ "Invalid instanceMaskReferenceKey value"
+ "Invalid linearHighKey: %{public}@, ignored"
+ "Invalid people data %@, treating as empty"
+ "Invalid person entry %@, skipping"
+ "Invalid pixel format value %@, skipping"
+ "Invalid revertUsingOriginal: %{public}@, ignored"
+ "Invalid texture style custom metadata"
+ "Invalid texture style version number"
+ "Invalid width value %@, skipping"
+ "LinearImage"
+ "Missing CMPhoto container"
+ "Missing mask metadata for key %@, skipping"
+ "Missing or invalid capture mode in texture style metadata: %@"
+ "Missing or invalid capture type in texture style metadata: %@"
+ "Missing or invalid hardware model in texture style metadata: %@"
+ "Missing or invalid port type in texture style metadata: %@"
+ "Missing texture style version value"
+ "NUImageExportJob.m"
+ "PortType"
+ "TextureStyleFaceAttitudeMetadata"
+ "TextureStylePeopleDataVersion"
+ "TextureStylePostProcessedPeopleData"
+ "_NUTextureStylePersonInstanceProperties<"
+ "_NUTextureStyleProperties<"
+ "captureMode:"
+ "captureType:"
+ "filmGrainSeed:"
+ "hardwareModel:"
+ "highKey"
+ "imageMetadata != nil"
+ "instanceMaskReferenceKey"
+ "instanceMaskReferenceKey:"
+ "kCGImageAuxiliaryDataTypeProvenanceProcessedImage"
+ "kCGImageAuxiliaryDataTypeProvenanceUnprocessedImage"
+ "l"
+ "linearHighKey:"
+ "maskSize:"
+ "mdta/com.apple.quicktime.texturestyle-info"
+ "personIntances:"
+ "pixelFormat:"
+ "portType:"
+ "revertUsingOriginal:"
+ "softlink:r:path:/System/Library/Frameworks/ImageIO.framework/ImageIO"
+ "tag:apple.com,2026:photo:metadata:texture_styles"
+ "textureData != nil"
+ "void *ImageIOLibrary(void)"
+ "void soft_CGImageDestinationSetProvenanceData(CGImageDestinationRef _Nonnull, uint32_t, CFDataRef _Nullable)"
- "<%@:%p> url=%@ fileUTI=%@ size=%@ orientation=%@ colorSpace=%@ headroom=%f raw=%@ aux=%@ semanticStyle=%@ metadata=%@"
```
