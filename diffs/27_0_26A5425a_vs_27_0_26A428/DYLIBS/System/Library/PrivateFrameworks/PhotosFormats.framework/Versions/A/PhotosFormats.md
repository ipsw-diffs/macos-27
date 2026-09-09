## PhotosFormats

> `/System/Library/PrivateFrameworks/PhotosFormats.framework/Versions/A/PhotosFormats`

```diff

 911.0.134.0.0
-  __TEXT.__text: 0xdd5cc
-  __TEXT.__objc_methlist: 0xc740
-  __TEXT.__const: 0x2da0
+  __TEXT.__text: 0xe4910
+  __TEXT.__objc_methlist: 0xce18
+  __TEXT.__const: 0x3390
   __TEXT.__dlopen_cstrs: 0x43
-  __TEXT.__gcc_except_tab: 0x2c1c
-  __TEXT.__cstring: 0xdd9c
-  __TEXT.__oslogstring: 0x6e0f
+  __TEXT.__cstring: 0xe28e
+  __TEXT.__constg_swiftt: 0xa0
+  __TEXT.__swift5_typeref: 0xeb
+  __TEXT.__swift5_reflstr: 0x162
+  __TEXT.__swift5_fieldmd: 0xf4
+  __TEXT.__swift5_proto: 0x2c
+  __TEXT.__swift5_types: 0x10
+  __TEXT.__gcc_except_tab: 0x2c34
+  __TEXT.__oslogstring: 0x7137
   __TEXT.__ustring: 0x44
-  __TEXT.__unwind_info: 0x3308
+  __TEXT.__unwind_info: 0x3540
+  __TEXT.__eh_frame: 0x380
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1598
-  __DATA_CONST.__objc_classlist: 0x540
+  __DATA_CONST.__const: 0x15c8
+  __DATA_CONST.__objc_classlist: 0x580
   __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x6118
+  __DATA_CONST.__objc_selrefs: 0x63c0
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x388
+  __DATA_CONST.__objc_superrefs: 0x3b8
   __DATA_CONST.__objc_arraydata: 0x800
-  __DATA_CONST.__got: 0x15c0
-  __AUTH_CONST.__const: 0x33d0
-  __AUTH_CONST.__cfstring: 0xca40
-  __AUTH_CONST.__objc_const: 0x142f8
+  __DATA_CONST.__got: 0x1758
+  __AUTH_CONST.__const: 0x3568
+  __AUTH_CONST.__cfstring: 0xcda0
+  __AUTH_CONST.__objc_const: 0x15050
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__objc_intobj: 0x900
   __AUTH_CONST.__objc_arrayobj: 0x348
   __AUTH_CONST.__objc_doubleobj: 0x1b0
   __AUTH_CONST.__objc_dictobj: 0x208
-  __AUTH_CONST.__auth_got: 0xe50
-  __AUTH.__objc_data: 0x500
-  __DATA.__objc_ivar: 0xcf8
-  __DATA.__data: 0xd28
-  __DATA.__bss: 0x7f8
+  __AUTH_CONST.__auth_got: 0x10a0
+  __AUTH.__objc_data: 0x7a0
+  __AUTH.__data: 0xc0
+  __DATA.__objc_ivar: 0xd74
+  __DATA.__data: 0xda8
+  __DATA.__bss: 0xdf8
   __DATA_DIRTY.__objc_data: 0x2f80
   __DATA_DIRTY.__bss: 0x748
   __DATA_DIRTY.__common: 0x10

   - /System/Library/PrivateFrameworks/PhotoFoundation.framework/Versions/A/PhotoFoundation
   - /System/Library/PrivateFrameworks/Portrait.framework/Versions/A/Portrait
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
+  - /System/Library/PrivateFrameworks/SwiftASN1Internal.framework/Versions/A/SwiftASN1Internal
   - /usr/lib/libAppleArchive.dylib
   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
   - /usr/lib/swift/libswiftAVFoundation.dylib
+  - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/swift/libswiftCoreAudio.dylib
   - /usr/lib/swift/libswiftCoreFoundation.dylib
   - /usr/lib/swift/libswiftCoreImage.dylib

   - /usr/lib/swift/libswiftDispatch.dylib
   - /usr/lib/swift/libswiftIOKit.dylib
   - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib
   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftQuartzCore.dylib
   - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4844
-  Symbols:   11553
-  CStrings:  2532
+  Functions: 5109
+  Symbols:   11954
+  CStrings:  2586
 
Symbols:
+ +[PFContentProvenanceDNGHelper dngFileContainsEmbeddedProvenanceImage:checkUnprocessed:]
+ +[PFContentProvenanceResourceInfo dataContainsNonZeroBytes:]
+ +[PFContentProvenanceResourceInfo reconciledProvenanceState:forMetadata:hasUnprocessedEmbeddedProvenanceContent:assetContainsProvenanceResource:utiConformsToDNGType:]
+ +[PFImageMetadataChangePolicySetProvenanceFlags supportsSecureCoding]
+ +[PFMetadataIdentifier quickTimeMetadataCoreMediaCaptureMode]
+ -[PFAssetBundle initWithOriginalPhotoURL:alternatePhotoURL:fullSizePhotoURL:adjustmentBaseFullSizePhotoURL:spatialOvercapturePhotoURL:originalPairedVideoURL:fullSizePairedVideoURL:adjustmentBaseFullSizePairedVideoURL:spatialOvercapturePairedVideoURL:fullSizeVideoURL:adjustmentsURL:originalAdjustmentsURL:adjustmentsSecondaryDataURL:originalProvenanceURL:mediaSubtypes:playbackStyle:playbackVariation:videoComplementVisibilityState:]
+ -[PFAssetBundle originalProvenanceURL]
+ -[PFContentProvenanceDNGHelper .cxx_destruct]
+ -[PFContentProvenanceDNGHelper containsNonZeroUpperBoundTimestampData]
+ -[PFContentProvenanceDNGHelper initWithDNGFileURL:error:]
+ -[PFContentProvenanceDNGHelper nonceDataForModification]
+ -[PFContentProvenanceDNGHelper nonceReservedLength]
+ -[PFContentProvenanceDNGHelper sensorSignature]
+ -[PFContentProvenanceDNGHelper sepSignature]
+ -[PFContentProvenanceDNGHelper setNonceDataForModification:]
+ -[PFContentProvenanceDNGHelper setUpperBoundTimestampDataForModification:]
+ -[PFContentProvenanceDNGHelper upperBoundTimestampDataForModification]
+ -[PFContentProvenanceDNGHelper upperBoundTimestampReservedLength]
+ -[PFContentProvenanceDNGHelper writeModificationsToURL:error:]
+ -[PFContentProvenanceEmbeddedImageWriter .cxx_destruct]
+ -[PFContentProvenanceEmbeddedImageWriter _provenanceStateForMode]
+ -[PFContentProvenanceEmbeddedImageWriter _writeCombinedProvenanceImageToURL:error:]
+ -[PFContentProvenanceEmbeddedImageWriter initWithMode:regularImageURL:payloadToEmbed:]
+ -[PFContentProvenanceEmbeddedImageWriter validateConfiguration]
+ -[PFContentProvenanceEmbeddedImageWriter writeCombinedImageToURL:error:]
+ -[PFContentProvenanceProcessedImageInfo .cxx_destruct]
+ -[PFContentProvenanceProcessedImageInfo certificateVerificationStatus]
+ -[PFContentProvenanceProcessedImageInfo fileContentPartialDigest]
+ -[PFContentProvenanceProcessedImageInfo processedImageJPEGData]
+ -[PFContentProvenanceProcessedImageInfo setCertificateVerificationStatus:]
+ -[PFContentProvenanceProcessedImageInfo setFileContentPartialDigest:]
+ -[PFContentProvenanceProcessedImageInfo setProcessedImageJPEGData:]
+ -[PFContentProvenanceProcessedImageInfo setSignatureVerificationStatus:]
+ -[PFContentProvenanceProcessedImageInfo setUtcLowerBoundTimestamp:]
+ -[PFContentProvenanceProcessedImageInfo setUtcProcessingTimestamp:]
+ -[PFContentProvenanceProcessedImageInfo setUtcUpperBoundTimestamp:]
+ -[PFContentProvenanceProcessedImageInfo signatureVerificationStatus]
+ -[PFContentProvenanceProcessedImageInfo utcLowerBoundTimestamp]
+ -[PFContentProvenanceProcessedImageInfo utcProcessingTimestamp]
+ -[PFContentProvenanceProcessedImageInfo utcUpperBoundTimestamp]
+ -[PFContentProvenanceProcessedImageReader .cxx_destruct]
+ -[PFContentProvenanceProcessedImageReader initWithProcessedProvenanceImageURL:]
+ -[PFContentProvenanceProcessedImageReader initWithRegularImageWithProcessedProvenanceImageURL:]
+ -[PFContentProvenanceProcessedImageReader readProcessedImageWithError:]
+ -[PFContentProvenanceResourceInfo .cxx_destruct]
+ -[PFContentProvenanceResourceInfo baaCertificateChainData]
+ -[PFContentProvenanceResourceInfo configureWithMetadata:]
+ -[PFContentProvenanceResourceInfo containsNonZeroUpperBoundTimestampData]
+ -[PFContentProvenanceResourceInfo developmentStatus]
+ -[PFContentProvenanceResourceInfo dngProperties]
+ -[PFContentProvenanceResourceInfo fileType]
+ -[PFContentProvenanceResourceInfo initWithMetadata:]
+ -[PFContentProvenanceResourceInfo lowerBoundTimestampData]
+ -[PFContentProvenanceResourceInfo sealingManifestData]
+ -[PFContentProvenanceResourceInfo secureBootManifestData]
+ -[PFContentProvenanceResourceInfo sensorSignatureData]
+ -[PFContentProvenanceResourceInfo sepSignatureData]
+ -[PFContentProvenanceResourceInfo timestampStatus]
+ -[PFContentProvenanceResourceInfo upperBoundTimestampData]
+ -[PFContentProvenanceUnprocessedEmbeddedImageReader .cxx_destruct]
+ -[PFContentProvenanceUnprocessedEmbeddedImageReader dataForEmbeddedUnprocessedProvenanceImageWithError:]
+ -[PFContentProvenanceUnprocessedEmbeddedImageReader initWithRegularImageWithUnprocessedProvenanceImageURL:]
+ -[PFContentProvenanceUnprocessedEmbeddedImageReader writeEmbeddedUnprocessedProvenanceImageToURL:error:]
+ -[PFImageIODestinationOptionsBuilder setShouldPreserveProvenance:]
+ -[PFImageIODestinationOptionsBuilder shouldPreserveProvenance]
+ -[PFImageMetadataChangePolicySetProvenanceFlags _flagForProvenanceState:]
+ -[PFImageMetadataChangePolicySetProvenanceFlags encodeWithCoder:]
+ -[PFImageMetadataChangePolicySetProvenanceFlags initWithCoder:]
+ -[PFImageMetadataChangePolicySetProvenanceFlags initWithProvenanceState:]
+ -[PFImageMetadataChangePolicySetProvenanceFlags metadataNeedsProcessing:]
+ -[PFImageMetadataChangePolicySetProvenanceFlags processMetadata:]
+ -[PFImageMetadataChangePolicySetProvenanceFlags provenanceState]
+ -[PFImageMetadataChangePolicySetProvenanceFlags setProvenanceState:]
+ -[PFMetadata cinematicRenderingVersion]
+ -[PFMetadata coreMediaCaptureMode]
+ -[PFMetadata hasProcessedProvenanceAuxiliaryMetadata]
+ -[PFMetadata hasProcessedProvenanceDNGMetadata]
+ -[PFMetadata hasProvenanceMetadata]
+ -[PFMetadata hasTextureStyle]
+ -[PFMetadata hasUnprocessedProvenanceAuxiliaryMetadata]
+ -[PFMetadata hasUnprocessedProvenanceDNGMetadata]
+ -[PFMetadata isCinematicCapableVideo]
+ -[PFMetadata isTimelapseAutoAdjust]
+ -[PFMetadata isTimelapseClassic]
+ -[PFMetadata metadataIndicatesDevelopedProvenanceImage]
+ -[PFMetadata metadataIndicatesUndevelopedProvenanceImage]
+ -[PFMetadata provenanceFlags]
+ -[PFMetadata provenanceState]
+ -[PFMetadata textureStyleGrainIntensity]
+ -[PFMetadata textureStyleIntensity]
+ -[PFMetadata textureStyleIsReversible]
+ -[PFMetadata textureStylePreset]
+ -[PFMetadataImage hasProcessedProvenanceAuxiliaryMetadata]
+ -[PFMetadataImage hasProcessedProvenanceDNGMetadata]
+ -[PFMetadataImage hasProvenanceMetadata]
+ -[PFMetadataImage hasTextureStyle]
+ -[PFMetadataImage hasUnprocessedProvenanceAuxiliaryMetadata]
+ -[PFMetadataImage hasUnprocessedProvenanceDNGMetadata]
+ -[PFMetadataImage metadataIndicatesDevelopedProvenanceImage]
+ -[PFMetadataImage metadataIndicatesUndevelopedProvenanceImage]
+ -[PFMetadataImage provenanceFlags]
+ -[PFMetadataImage provenanceState]
+ -[PFMetadataImage textureStyleGrainIntensity]
+ -[PFMetadataImage textureStyleIntensity]
+ -[PFMetadataImage textureStyleIsReversible]
+ -[PFMetadataImage textureStylePreset]
+ -[PFMetadataMovie cinematicRenderingVersion]
+ -[PFMetadataMovie coreMediaCaptureMode]
+ -[PFMetadataMovie isCinematicCapableVideo]
+ -[PFMetadataMovie isTimelapseAutoAdjust]
+ -[PFMetadataMovie isTimelapseClassic]
+ GCC_except_table1160
+ GCC_except_table1538
+ GCC_except_table1545
+ GCC_except_table1548
+ GCC_except_table1583
+ GCC_except_table1599
+ GCC_except_table1705
+ GCC_except_table1784
+ GCC_except_table1786
+ GCC_except_table1870
+ GCC_except_table1874
+ GCC_except_table1885
+ GCC_except_table1924
+ GCC_except_table1926
+ GCC_except_table1951
+ GCC_except_table1962
+ GCC_except_table1989
+ GCC_except_table1997
+ GCC_except_table2000
+ GCC_except_table2014
+ GCC_except_table2039
+ GCC_except_table2044
+ GCC_except_table2049
+ GCC_except_table2060
+ GCC_except_table2165
+ GCC_except_table2204
+ GCC_except_table2268
+ GCC_except_table2279
+ GCC_except_table2301
+ GCC_except_table2369
+ GCC_except_table2374
+ GCC_except_table2381
+ GCC_except_table2485
+ GCC_except_table2587
+ GCC_except_table2588
+ GCC_except_table2595
+ GCC_except_table2598
+ GCC_except_table2600
+ GCC_except_table2603
+ GCC_except_table2634
+ GCC_except_table2657
+ GCC_except_table2659
+ GCC_except_table2787
+ GCC_except_table295
+ GCC_except_table3067
+ GCC_except_table3133
+ GCC_except_table3137
+ GCC_except_table3139
+ GCC_except_table3140
+ GCC_except_table3144
+ GCC_except_table3146
+ GCC_except_table3148
+ GCC_except_table3149
+ GCC_except_table3150
+ GCC_except_table3152
+ GCC_except_table3153
+ GCC_except_table3160
+ GCC_except_table3161
+ GCC_except_table3162
+ GCC_except_table3163
+ GCC_except_table3166
+ GCC_except_table3169
+ GCC_except_table3179
+ GCC_except_table3182
+ GCC_except_table3185
+ GCC_except_table3192
+ GCC_except_table3193
+ GCC_except_table3194
+ GCC_except_table3216
+ GCC_except_table3218
+ GCC_except_table3219
+ GCC_except_table3225
+ GCC_except_table3226
+ GCC_except_table3227
+ GCC_except_table3228
+ GCC_except_table3229
+ GCC_except_table3235
+ GCC_except_table3240
+ GCC_except_table3297
+ GCC_except_table3444
+ GCC_except_table3447
+ GCC_except_table3448
+ GCC_except_table3450
+ GCC_except_table3451
+ GCC_except_table3453
+ GCC_except_table3454
+ GCC_except_table3455
+ GCC_except_table3459
+ GCC_except_table3465
+ GCC_except_table3472
+ GCC_except_table3475
+ GCC_except_table3476
+ GCC_except_table3478
+ GCC_except_table3483
+ GCC_except_table3484
+ GCC_except_table3485
+ GCC_except_table3491
+ GCC_except_table3498
+ GCC_except_table3499
+ GCC_except_table3519
+ GCC_except_table3571
+ GCC_except_table3575
+ GCC_except_table3578
+ GCC_except_table3579
+ GCC_except_table3629
+ GCC_except_table3638
+ GCC_except_table3713
+ GCC_except_table3792
+ GCC_except_table3794
+ GCC_except_table3811
+ GCC_except_table3835
+ GCC_except_table3837
+ GCC_except_table3926
+ GCC_except_table4159
+ GCC_except_table4163
+ GCC_except_table4175
+ GCC_except_table4256
+ GCC_except_table4257
+ GCC_except_table4258
+ GCC_except_table4262
+ GCC_except_table4264
+ GCC_except_table4271
+ GCC_except_table4275
+ GCC_except_table4282
+ GCC_except_table4296
+ GCC_except_table4297
+ GCC_except_table4299
+ GCC_except_table4304
+ GCC_except_table4305
+ GCC_except_table4307
+ GCC_except_table4308
+ GCC_except_table4311
+ GCC_except_table4324
+ GCC_except_table4331
+ GCC_except_table4336
+ GCC_except_table4337
+ GCC_except_table4341
+ GCC_except_table4346
+ GCC_except_table4375
+ GCC_except_table4380
+ GCC_except_table4381
+ GCC_except_table4382
+ GCC_except_table4383
+ GCC_except_table4384
+ GCC_except_table4386
+ GCC_except_table4391
+ GCC_except_table4392
+ GCC_except_table4394
+ GCC_except_table4395
+ GCC_except_table4397
+ GCC_except_table4398
+ GCC_except_table4399
+ GCC_except_table4400
+ GCC_except_table4401
+ GCC_except_table4402
+ GCC_except_table4404
+ GCC_except_table4406
+ GCC_except_table4407
+ GCC_except_table4408
+ GCC_except_table4409
+ GCC_except_table4412
+ GCC_except_table4484
+ GCC_except_table4551
+ GCC_except_table4557
+ GCC_except_table4626
+ GCC_except_table4630
+ GCC_except_table4632
+ GCC_except_table4635
+ GCC_except_table4636
+ GCC_except_table4656
+ GCC_except_table4674
+ GCC_except_table4675
+ GCC_except_table4676
+ GCC_except_table4678
+ GCC_except_table4680
+ GCC_except_table4944
+ GCC_except_table4953
+ GCC_except_table4957
+ GCC_except_table647
+ GCC_except_table668
+ GCC_except_table671
+ GCC_except_table725
+ GCC_except_table732
+ GCC_except_table773
+ GCC_except_table777
+ GCC_except_table787
+ GCC_except_table790
+ GCC_except_table791
+ GCC_except_table802
+ GCC_except_table805
+ GCC_except_table806
+ GCC_except_table807
+ GCC_except_table812
+ GCC_except_table813
+ GCC_except_table818
+ GCC_except_table819
+ GCC_except_table831
+ GCC_except_table832
+ GCC_except_table839
+ GCC_except_table844
+ GCC_except_table845
+ GCC_except_table846
+ GCC_except_table851
+ GCC_except_table856
+ GCC_except_table870
+ GCC_except_table872
+ GCC_except_table873
+ GCC_except_table874
+ OBJC_IVAR_$_PFAssetBundle._originalProvenanceURL
+ OBJC_IVAR_$_PFContentProvenanceDNGHelper._dngData
+ OBJC_IVAR_$_PFContentProvenanceDNGHelper._dngDict
+ OBJC_IVAR_$_PFContentProvenanceDNGHelper._dngFileURL
+ OBJC_IVAR_$_PFContentProvenanceDNGHelper._dngProperties
+ OBJC_IVAR_$_PFContentProvenanceDNGHelper._nonceDataForModification
+ OBJC_IVAR_$_PFContentProvenanceDNGHelper._upperBoundTimestampDataForModification
+ OBJC_IVAR_$_PFContentProvenanceEmbeddedImageWriter._mode
+ OBJC_IVAR_$_PFContentProvenanceEmbeddedImageWriter._outputContentType
+ OBJC_IVAR_$_PFContentProvenanceEmbeddedImageWriter._payloadToEmbed
+ OBJC_IVAR_$_PFContentProvenanceEmbeddedImageWriter._regularImageURL
+ OBJC_IVAR_$_PFContentProvenanceProcessedImageInfo._certificateVerificationStatus
+ OBJC_IVAR_$_PFContentProvenanceProcessedImageInfo._fileContentPartialDigest
+ OBJC_IVAR_$_PFContentProvenanceProcessedImageInfo._processedImageJPEGData
+ OBJC_IVAR_$_PFContentProvenanceProcessedImageInfo._signatureVerificationStatus
+ OBJC_IVAR_$_PFContentProvenanceProcessedImageInfo._utcLowerBoundTimestamp
+ OBJC_IVAR_$_PFContentProvenanceProcessedImageInfo._utcProcessingTimestamp
+ OBJC_IVAR_$_PFContentProvenanceProcessedImageInfo._utcUpperBoundTimestamp
+ OBJC_IVAR_$_PFContentProvenanceProcessedImageReader._processedProvenanceImageURL
+ OBJC_IVAR_$_PFContentProvenanceProcessedImageReader._regularImageWithProcessedProvenanceImageURL
+ OBJC_IVAR_$_PFContentProvenanceResourceInfo._contentType
+ OBJC_IVAR_$_PFContentProvenanceResourceInfo._developmentStatus
+ OBJC_IVAR_$_PFContentProvenanceResourceInfo._dngProperties
+ OBJC_IVAR_$_PFContentProvenanceResourceInfo._fileType
+ OBJC_IVAR_$_PFContentProvenanceResourceInfo._fileURLFromMetadata
+ OBJC_IVAR_$_PFContentProvenanceResourceInfo._timestampStatus
+ OBJC_IVAR_$_PFContentProvenanceUnprocessedEmbeddedImageReader._regularImageWithUnprocessedProvenanceImageURL
+ OBJC_IVAR_$_PFImageIODestinationOptionsBuilder._shouldPreserveProvenance
+ OBJC_IVAR_$_PFImageMetadataChangePolicySetProvenanceFlags._provenanceState
+ OBJC_IVAR_$_PFMetadataImage._hasProcessedProvenanceDNGMetadataValue
+ OBJC_IVAR_$_PFMetadataImage._hasUnprocessedProvenanceDNGMetadataValue
+ _AVAppleMakerNote_ProvenanceFlags
+ _AVAppleMakerNote_TextureStyleKey_Grain
+ _AVAppleMakerNote_TextureStyleKey_Intensity
+ _AVAppleMakerNote_TextureStyleKey_OriginalInsteadOfReversibility
+ _AVAppleMakerNote_TextureStyleKey_Preset
+ _CMPhotoDNGCopyProperties
+ _CMPhotoDNGReplaceTagsInPlace
+ _CMPhotoDecompressionContainerCopyCustomMetadataForIndexWithOptions
+ _CMPhotoDecompressionContainerGetCustomMetadataCountForIndexWithOptions
+ _CMPhotoEncodeLengthPrefixedData
+ _CMPhotoProvenanceInsertProvenanceImage
+ _CMPhotoVerifyProvenanceSignatureAndCertificates
+ _NSOSStatusErrorDomain
+ _OBJC_CLASS_$_PFContentProvenanceDNGHelper
+ _OBJC_CLASS_$_PFContentProvenanceEmbeddedImageWriter
+ _OBJC_CLASS_$_PFContentProvenanceProcessedImageInfo
+ _OBJC_CLASS_$_PFContentProvenanceProcessedImageReader
+ _OBJC_CLASS_$_PFContentProvenanceResourceInfo
+ _OBJC_CLASS_$_PFContentProvenanceUnprocessedEmbeddedImageReader
+ _OBJC_CLASS_$_PFContentProvenanceUpperBoundTimestampDigestBuilder
+ _OBJC_CLASS_$_PFImageMetadataChangePolicySetProvenanceFlags
+ _OBJC_CLASS_$_PTGlobalRenderingMetadata
+ _OBJC_CLASS_$_PTGlobalVideoMetadata
+ _OBJC_CLASS_$_PTRenderPipeline
+ _OBJC_METACLASS_$_PFContentProvenanceDNGHelper
+ _OBJC_METACLASS_$_PFContentProvenanceEmbeddedImageWriter
+ _OBJC_METACLASS_$_PFContentProvenanceProcessedImageInfo
+ _OBJC_METACLASS_$_PFContentProvenanceProcessedImageReader
+ _OBJC_METACLASS_$_PFContentProvenanceResourceInfo
+ _OBJC_METACLASS_$_PFContentProvenanceUnprocessedEmbeddedImageReader
+ _OBJC_METACLASS_$_PFContentProvenanceUpperBoundTimestampDigestBuilder
+ _OBJC_METACLASS_$_PFImageMetadataChangePolicySetProvenanceFlags
+ _OUTLINED_FUNCTION_0
+ _OUTLINED_FUNCTION_1
+ _OUTLINED_FUNCTION_10
+ _OUTLINED_FUNCTION_11
+ _OUTLINED_FUNCTION_12
+ _OUTLINED_FUNCTION_13
+ _OUTLINED_FUNCTION_14
+ _OUTLINED_FUNCTION_15
+ _OUTLINED_FUNCTION_16
+ _OUTLINED_FUNCTION_17
+ _OUTLINED_FUNCTION_18
+ _OUTLINED_FUNCTION_19
+ _OUTLINED_FUNCTION_2
+ _OUTLINED_FUNCTION_20
+ _OUTLINED_FUNCTION_21
+ _OUTLINED_FUNCTION_22
+ _OUTLINED_FUNCTION_23
+ _OUTLINED_FUNCTION_24
+ _OUTLINED_FUNCTION_25
+ _OUTLINED_FUNCTION_26
+ _OUTLINED_FUNCTION_27
+ _OUTLINED_FUNCTION_28
+ _OUTLINED_FUNCTION_29
+ _OUTLINED_FUNCTION_3
+ _OUTLINED_FUNCTION_30
+ _OUTLINED_FUNCTION_31
+ _OUTLINED_FUNCTION_32
+ _OUTLINED_FUNCTION_33
+ _OUTLINED_FUNCTION_4
+ _OUTLINED_FUNCTION_5
+ _OUTLINED_FUNCTION_6
+ _OUTLINED_FUNCTION_7
+ _OUTLINED_FUNCTION_8
+ _OUTLINED_FUNCTION_9
+ _PFAssetBundlePathOriginalProvenanceKey
+ _PFReadEmbeddedImageDataFromImageURLForCustomMetadataURI
+ _UTTypeHEIF
+ __DATA_PFContentProvenanceUpperBoundTimestampDigestBuilder
+ __INSTANCE_METHODS_PFContentProvenanceUpperBoundTimestampDigestBuilder
+ __IVARS_PFContentProvenanceUpperBoundTimestampDigestBuilder
+ __METACLASS_DATA_PFContentProvenanceUpperBoundTimestampDigestBuilder
+ __MergedGlobals
+ __OBJC_$_CLASS_METHODS_PFContentProvenanceDNGHelper
+ __OBJC_$_CLASS_METHODS_PFContentProvenanceResourceInfo
+ __OBJC_$_CLASS_METHODS_PFImageMetadataChangePolicySetProvenanceFlags
+ __OBJC_$_INSTANCE_METHODS_PFContentProvenanceDNGHelper
+ __OBJC_$_INSTANCE_METHODS_PFContentProvenanceEmbeddedImageWriter
+ __OBJC_$_INSTANCE_METHODS_PFContentProvenanceProcessedImageInfo
+ __OBJC_$_INSTANCE_METHODS_PFContentProvenanceProcessedImageReader
+ __OBJC_$_INSTANCE_METHODS_PFContentProvenanceResourceInfo
+ __OBJC_$_INSTANCE_METHODS_PFContentProvenanceUnprocessedEmbeddedImageReader
+ __OBJC_$_INSTANCE_METHODS_PFImageMetadataChangePolicySetProvenanceFlags
+ __OBJC_$_INSTANCE_VARIABLES_PFContentProvenanceDNGHelper
+ __OBJC_$_INSTANCE_VARIABLES_PFContentProvenanceEmbeddedImageWriter
+ __OBJC_$_INSTANCE_VARIABLES_PFContentProvenanceProcessedImageInfo
+ __OBJC_$_INSTANCE_VARIABLES_PFContentProvenanceProcessedImageReader
+ __OBJC_$_INSTANCE_VARIABLES_PFContentProvenanceResourceInfo
+ __OBJC_$_INSTANCE_VARIABLES_PFContentProvenanceUnprocessedEmbeddedImageReader
+ __OBJC_$_INSTANCE_VARIABLES_PFImageMetadataChangePolicySetProvenanceFlags
+ __OBJC_$_PROP_LIST_PFContentProvenanceDNGHelper
+ __OBJC_$_PROP_LIST_PFContentProvenanceProcessedImageInfo
+ __OBJC_$_PROP_LIST_PFContentProvenanceResourceInfo
+ __OBJC_$_PROP_LIST_PFImageMetadataChangePolicySetProvenanceFlags
+ __OBJC_CLASS_RO_$_PFContentProvenanceDNGHelper
+ __OBJC_CLASS_RO_$_PFContentProvenanceEmbeddedImageWriter
+ __OBJC_CLASS_RO_$_PFContentProvenanceProcessedImageInfo
+ __OBJC_CLASS_RO_$_PFContentProvenanceProcessedImageReader
+ __OBJC_CLASS_RO_$_PFContentProvenanceResourceInfo
+ __OBJC_CLASS_RO_$_PFContentProvenanceUnprocessedEmbeddedImageReader
+ __OBJC_CLASS_RO_$_PFImageMetadataChangePolicySetProvenanceFlags
+ __OBJC_METACLASS_RO_$_PFContentProvenanceDNGHelper
+ __OBJC_METACLASS_RO_$_PFContentProvenanceEmbeddedImageWriter
+ __OBJC_METACLASS_RO_$_PFContentProvenanceProcessedImageInfo
+ __OBJC_METACLASS_RO_$_PFContentProvenanceProcessedImageReader
+ __OBJC_METACLASS_RO_$_PFContentProvenanceResourceInfo
+ __OBJC_METACLASS_RO_$_PFContentProvenanceUnprocessedEmbeddedImageReader
+ __OBJC_METACLASS_RO_$_PFImageMetadataChangePolicySetProvenanceFlags
+ __PROPERTIES_PFContentProvenanceUpperBoundTimestampDigestBuilder
+ ___39-[PFMetadataMovie coreMediaCaptureMode]_block_invoke
+ ___42-[PFMetadataMovie isCinematicCapableVideo]_block_invoke
+ ___42-[PFMetadataMovie isCinematicCapableVideo]_block_invoke_2
+ ___44-[PFMetadataMovie cinematicRenderingVersion]_block_invoke
+ ___swift_allocate_boxed_opaque_existential_0
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_getEnumTagSinglePayload
+ ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
+ ___swift_instantiateConcreteTypeFromMangledNameV2
+ ___swift_memcpy24_8
+ ___swift_memcpy32_8
+ ___swift_memcpy72_8
+ ___swift_storeEnumTagSinglePayload
+ __readEmbeddedImageDataFromDNGForCustomMetadataURI
+ __swiftEmptyArrayStorage
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftOSLog_$_PhotosFormats
+ __swift_stdlib_malloc_size
+ __swift_stdlib_reportUnimplementedInitializer
+ _associated conformance 13PhotosFormats25UpperBoundTimestampDigest33_DBB759D668E779954A02FCD0FA8D210FLLV17SwiftASN1Internal21DERImplicitlyTaggableAaE12DERParseable
+ _associated conformance 13PhotosFormats25UpperBoundTimestampDigest33_DBB759D668E779954A02FCD0FA8D210FLLV17SwiftASN1Internal21DERImplicitlyTaggableAaE15DERSerializable
+ _associated conformance 13PhotosFormats26UpperBoundTimestampWrapper33_DBB759D668E779954A02FCD0FA8D210FLLV17SwiftASN1Internal21DERImplicitlyTaggableAaE12DERParseable
+ _associated conformance 13PhotosFormats26UpperBoundTimestampWrapper33_DBB759D668E779954A02FCD0FA8D210FLLV17SwiftASN1Internal21DERImplicitlyTaggableAaE15DERSerializable
+ _associated conformance 13PhotosFormats31UpperBoundTimestampNonceWrapper33_DBB759D668E779954A02FCD0FA8D210FLLV17SwiftASN1Internal21DERImplicitlyTaggableAaE12DERParseable
+ _associated conformance 13PhotosFormats31UpperBoundTimestampNonceWrapper33_DBB759D668E779954A02FCD0FA8D210FLLV17SwiftASN1Internal21DERImplicitlyTaggableAaE15DERSerializable
+ _associated conformance 13PhotosFormats37UpperBoundTimestampDigestBuilderErrorO10Foundation13CustomNSErrorAAs0H0
+ _get_enum_tag_for_layout_string 10Foundation4DataV15_RepresentationO
+ _kCGImageDestinationPreserveProvenance
+ _kCGImagePropertyDNGDictionary
+ _kCMPhotoCustomMetadataTypeURN_Provenance_ProcessedImage
+ _kCMPhotoCustomMetadataTypeURN_Provenance_UnprocessedImage
+ _kCMPhotoCustomMetadata_Data
+ _kCMPhotoCustomMetadata_URI
+ _kCMPhotoMetadata_Provenance_TimingInformation_LowerBoundCaptureTime
+ _kCMPhotoMetadata_Provenance_TimingInformation_ProcessingTime
+ _kCMPhotoMetadata_Provenance_TimingInformation_UpperBoundCaptureTime
+ _kCMPhotoProvenanceResult_CertificateSecTrustVerified
+ _kCMPhotoProvenanceResult_FileContentsPartialDigestData
+ _kCMPhotoProvenanceResult_PQSignatureVerified
+ _kCMPhotoProvenanceResult_TimingInformation
+ _kCMPhoto_CGImagePropertyDNGProvenanceBAACertificateChain
+ _kCMPhoto_CGImagePropertyDNGProvenanceLowerTimeBound
+ _kCMPhoto_CGImagePropertyDNGProvenanceNonce
+ _kCMPhoto_CGImagePropertyDNGProvenanceProcessedImage
+ _kCMPhoto_CGImagePropertyDNGProvenanceSEPSignature
+ _kCMPhoto_CGImagePropertyDNGProvenanceSealingManifest
+ _kCMPhoto_CGImagePropertyDNGProvenanceSecureBootManifest
+ _kCMPhoto_CGImagePropertyDNGProvenanceSensorSignature
+ _kCMPhoto_CGImagePropertyDNGProvenanceUnprocessedImage
+ _kCMPhoto_CGImagePropertyDNGProvenanceUpperTimeBound
+ _kDCIMImageWriterProvenanceMetadataPathExtension
+ _kPFVideoPropertyCaptureModeTimelapseAutoAdjust
+ _kPFVideoPropertyCaptureModeTimelapseClassic
+ _kPFVideoPropertyCoreMediaCaptureMode
+ _kSecRandomDefault
+ _malloc_size
+ _objc_allocWithZone
+ _objc_msgSend$_flagForProvenanceState:
+ _objc_msgSend$_writeCombinedProvenanceImageToURL:error:
+ _objc_msgSend$certificateVerificationStatus
+ _objc_msgSend$cinematicRenderingVersion
+ _objc_msgSend$configureWithMetadata:
+ _objc_msgSend$containsNonZeroUpperBoundTimestampData
+ _objc_msgSend$coreMediaCaptureMode
+ _objc_msgSend$dataContainsNonZeroBytes:
+ _objc_msgSend$dataForEmbeddedUnprocessedProvenanceImageWithError:
+ _objc_msgSend$dateWithTimeIntervalSince1970:
+ _objc_msgSend$deserializeMetadataWithType:fromGlobalMetadata:error:
+ _objc_msgSend$dngFileContainsEmbeddedProvenanceImage:checkUnprocessed:
+ _objc_msgSend$dngProperties
+ _objc_msgSend$fileContentPartialDigest
+ _objc_msgSend$hasProcessedProvenanceAuxiliaryMetadata
+ _objc_msgSend$hasProcessedProvenanceDNGMetadata
+ _objc_msgSend$hasUnprocessedProvenanceAuxiliaryMetadata
+ _objc_msgSend$hasUnprocessedProvenanceDNGMetadata
+ _objc_msgSend$initWithSensorSignature:sepSignature:error:
+ _objc_msgSend$isRenderVersionSupported:
+ _objc_msgSend$metadataIndicatesDevelopedProvenanceImage
+ _objc_msgSend$metadataIndicatesUndevelopedProvenanceImage
+ _objc_msgSend$nonceReservedLength
+ _objc_msgSend$provenanceFlags
+ _objc_msgSend$quickTimeMetadataCoreMediaCaptureMode
+ _objc_msgSend$reconciledProvenanceState:forMetadata:hasUnprocessedEmbeddedProvenanceContent:assetContainsProvenanceResource:utiConformsToDNGType:
+ _objc_msgSend$renderingVersion
+ _objc_msgSend$setCertificateVerificationStatus:
+ _objc_msgSend$setFileContentPartialDigest:
+ _objc_msgSend$setProcessedImageJPEGData:
+ _objc_msgSend$setSignatureVerificationStatus:
+ _objc_msgSend$setUtcLowerBoundTimestamp:
+ _objc_msgSend$setUtcProcessingTimestamp:
+ _objc_msgSend$setUtcUpperBoundTimestamp:
+ _objc_msgSend$signatureVerificationStatus
+ _objc_msgSend$upperBoundTimestampData
+ _objc_msgSend$upperBoundTimestampReservedLength
+ _objc_msgSend$utcLowerBoundTimestamp
+ _objc_msgSend$utcProcessingTimestamp
+ _objc_msgSend$utcUpperBoundTimestamp
+ _objc_msgSend$validateConfiguration
+ _swift_allocBox
+ _swift_allocError
+ _swift_allocObject
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_initWithCopy
+ _swift_cvw_initWithTake
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_deallocPartialClassInstance
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getEnumCaseMultiPayload
+ _swift_getErrorValue
+ _swift_getExistentialTypeMetadata
+ _swift_getObjCClassFromMetadata
+ _swift_getObjCClassMetadata
+ _swift_getSingletonMetadata
+ _swift_getTupleTypeMetadata2
+ _swift_getTypeByMangledNameInContext2
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_getWitnessTable
+ _swift_initStackObject
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release
+ _swift_retain
+ _swift_storeEnumTagMultiPayload
+ _swift_willThrow
+ _symbolic SS
+ _symbolic Si
+ _symbolic Si8expected_Si6actualt
+ _symbolic _____ 10Foundation4DataV
+ _symbolic _____ 13PhotosFormats25UpperBoundTimestampDigest33_DBB759D668E779954A02FCD0FA8D210FLLV
+ _symbolic _____ 13PhotosFormats26UpperBoundTimestampWrapper33_DBB759D668E779954A02FCD0FA8D210FLLV
+ _symbolic _____ 13PhotosFormats31UpperBoundTimestampNonceWrapper33_DBB759D668E779954A02FCD0FA8D210FLLV
+ _symbolic _____ 13PhotosFormats37UpperBoundTimestampDigestBuilderErrorO
+ _symbolic _____6status_t s5Int32V
+ _symbolic ____________pSg10underlyingt 10Foundation3URLV s5ErrorP
+ _symbolic ______p10underlying_t s5ErrorP
+ _symbolic ______pSg s5ErrorP
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _symbolic _____ySSypG s17_NativeDictionaryV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
+ _type_layout_string 13PhotosFormats25UpperBoundTimestampDigest33_DBB759D668E779954A02FCD0FA8D210FLLV
+ _type_layout_string 13PhotosFormats26UpperBoundTimestampWrapper33_DBB759D668E779954A02FCD0FA8D210FLLV
+ _type_layout_string 13PhotosFormats31UpperBoundTimestampNonceWrapper33_DBB759D668E779954A02FCD0FA8D210FLLV
- -[PFAssetBundle initWithOriginalPhotoURL:alternatePhotoURL:fullSizePhotoURL:adjustmentBaseFullSizePhotoURL:spatialOvercapturePhotoURL:originalPairedVideoURL:fullSizePairedVideoURL:adjustmentBaseFullSizePairedVideoURL:spatialOvercapturePairedVideoURL:fullSizeVideoURL:adjustmentsURL:originalAdjustmentsURL:adjustmentsSecondaryDataURL:mediaSubtypes:playbackStyle:playbackVariation:videoComplementVisibilityState:]
- GCC_except_table1151
- GCC_except_table1510
- GCC_except_table1517
- GCC_except_table1520
- GCC_except_table1555
- GCC_except_table1571
- GCC_except_table1677
- GCC_except_table1730
- GCC_except_table1756
- GCC_except_table1842
- GCC_except_table1846
- GCC_except_table1857
- GCC_except_table1896
- GCC_except_table1898
- GCC_except_table1923
- GCC_except_table1934
- GCC_except_table1961
- GCC_except_table1969
- GCC_except_table1972
- GCC_except_table1986
- GCC_except_table2007
- GCC_except_table2012
- GCC_except_table2023
- GCC_except_table2128
- GCC_except_table2167
- GCC_except_table2231
- GCC_except_table2242
- GCC_except_table2264
- GCC_except_table2332
- GCC_except_table2337
- GCC_except_table2344
- GCC_except_table2448
- GCC_except_table2550
- GCC_except_table2551
- GCC_except_table2558
- GCC_except_table2560
- GCC_except_table2561
- GCC_except_table2563
- GCC_except_table2566
- GCC_except_table2620
- GCC_except_table2622
- GCC_except_table2737
- GCC_except_table286
- GCC_except_table3016
- GCC_except_table3082
- GCC_except_table3083
- GCC_except_table3086
- GCC_except_table3088
- GCC_except_table3089
- GCC_except_table3093
- GCC_except_table3095
- GCC_except_table3097
- GCC_except_table3098
- GCC_except_table3099
- GCC_except_table3101
- GCC_except_table3102
- GCC_except_table3109
- GCC_except_table3110
- GCC_except_table3111
- GCC_except_table3112
- GCC_except_table3114
- GCC_except_table3115
- GCC_except_table3116
- GCC_except_table3118
- GCC_except_table3126
- GCC_except_table3128
- GCC_except_table3131
- GCC_except_table3141
- GCC_except_table3142
- GCC_except_table3143
- GCC_except_table3168
- GCC_except_table3174
- GCC_except_table3175
- GCC_except_table3176
- GCC_except_table3178
- GCC_except_table3184
- GCC_except_table3189
- GCC_except_table3246
- GCC_except_table3391
- GCC_except_table3393
- GCC_except_table3394
- GCC_except_table3395
- GCC_except_table3397
- GCC_except_table3398
- GCC_except_table3400
- GCC_except_table3401
- GCC_except_table3402
- GCC_except_table3406
- GCC_except_table3412
- GCC_except_table3419
- GCC_except_table3422
- GCC_except_table3423
- GCC_except_table3425
- GCC_except_table3430
- GCC_except_table3431
- GCC_except_table3432
- GCC_except_table3438
- GCC_except_table3445
- GCC_except_table3466
- GCC_except_table3518
- GCC_except_table3522
- GCC_except_table3525
- GCC_except_table3526
- GCC_except_table3576
- GCC_except_table3585
- GCC_except_table3660
- GCC_except_table3739
- GCC_except_table3741
- GCC_except_table3758
- GCC_except_table3782
- GCC_except_table3784
- GCC_except_table3873
- GCC_except_table4106
- GCC_except_table4108
- GCC_except_table4110
- GCC_except_table4117
- GCC_except_table4122
- GCC_except_table4132
- GCC_except_table4142
- GCC_except_table4143
- GCC_except_table4144
- GCC_except_table4148
- GCC_except_table4150
- GCC_except_table4157
- GCC_except_table4158
- GCC_except_table4168
- GCC_except_table4172
- GCC_except_table4173
- GCC_except_table4174
- GCC_except_table4181
- GCC_except_table4182
- GCC_except_table4183
- GCC_except_table4190
- GCC_except_table4191
- GCC_except_table4193
- GCC_except_table4194
- GCC_except_table4197
- GCC_except_table4210
- GCC_except_table4217
- GCC_except_table4222
- GCC_except_table4223
- GCC_except_table4227
- GCC_except_table4232
- GCC_except_table4261
- GCC_except_table4266
- GCC_except_table4267
- GCC_except_table4268
- GCC_except_table4269
- GCC_except_table4270
- GCC_except_table4277
- GCC_except_table4278
- GCC_except_table4280
- GCC_except_table4281
- GCC_except_table4283
- GCC_except_table4285
- GCC_except_table4290
- GCC_except_table4292
- GCC_except_table4293
- GCC_except_table4294
- GCC_except_table4298
- GCC_except_table4369
- GCC_except_table4436
- GCC_except_table4442
- GCC_except_table4511
- GCC_except_table4515
- GCC_except_table4517
- GCC_except_table4520
- GCC_except_table4521
- GCC_except_table4541
- GCC_except_table4559
- GCC_except_table4560
- GCC_except_table4561
- GCC_except_table4563
- GCC_except_table4565
- GCC_except_table4828
- GCC_except_table4837
- GCC_except_table4841
- GCC_except_table638
- GCC_except_table659
- GCC_except_table662
- GCC_except_table716
- GCC_except_table723
- GCC_except_table764
- GCC_except_table768
- GCC_except_table769
- GCC_except_table781
- GCC_except_table782
- GCC_except_table784
- GCC_except_table785
- GCC_except_table786
- GCC_except_table789
- GCC_except_table796
- GCC_except_table797
- GCC_except_table809
- GCC_except_table810
- GCC_except_table814
- GCC_except_table820
- GCC_except_table821
- GCC_except_table822
- GCC_except_table824
- GCC_except_table826
- GCC_except_table827
- GCC_except_table828
- GCC_except_table861
- GCC_except_table863
- GCC_except_table864
- GCC_except_table865
CStrings:
+ " underlying "
+ ".%@"
+ "ASN.1 encoding failed"
+ "CMPhotoVerifyProvenanceSignatureAndCertificates: certStatus=%d sigStatus=%d hasDigest=%d lowerBound=%{public}@ upperBound=%{public}@ processingTime=%{public}@"
+ "Could not get DNG data from dng file %@ with error: %@"
+ "Decoding not implemented"
+ "Failed to copy DNG regular image to temporary location: %@"
+ "Failed to deserialize cinematic global rendering metadata: %{public}@"
+ "Failed to insert provenance image: %d"
+ "Failed to patch DNG: OSStatus %d"
+ "Failed to read DNG properties for %@: %d"
+ "Failed to read DNG properties via CMPhotoDNGCopyProperties"
+ "Failed to read source file: %@"
+ "Failed to remove partial output file at url: %@ error: %@"
+ "Failed to remove temporary provenance original at url: %@ error: %@"
+ "Failed to write final file: %@"
+ "Failed to write modified DNG to %@"
+ "Fatal error"
+ "Invalid sensor signature length: expected "
+ "Missing sensor signature in DNG file"
+ "No DNG provenance data for URI %@ in %@"
+ "No custom metadata with URI %@ found in %@"
+ "No modifications queued"
+ "No reserved space for nonce in DNG"
+ "No reserved space for upper bound timestamp in DNG"
+ "Output content type %@ is unsupported"
+ "PFAssetBundlePathOriginalProvenanceKey"
+ "PhotosFormats.PFContentProvenanceUpperBoundTimestampDigestBuilder"
+ "PhotosFormats/PFContentProvenance.swift"
+ "Provenance UpperBound Timestamp"
+ "Random generation failed with status: "
+ "SubIFD"
+ "Time-lapse-Auto-adjust"
+ "Time-lapse-Classic"
+ "Unable to create content type for %@"
+ "Unable to create decompression session for %@: %d"
+ "Unable to get content type identifier for %@"
+ "Unable to length-prefix nonce data: %d"
+ "Unable to length-prefix upper bound timestamp data: %d"
+ "Unable to open container for %@: %d"
+ "Unable to read DNG file: "
+ "Unknown provenance embedding mode %td"
+ "cinematicRenderingVersion"
+ "com.apple.coremedia.captureMode"
+ "com.apple.quicktime.cinematic-video"
+ "expected actual "
+ "heic"
+ "init()"
+ "isCinematicCapableVideo"
+ "provenance"
+ "provenanceFlags"
+ "provenanceFlags metadata indicates embedded provenance data when none is present"
+ "temp_regular_%@.%@"
+ "{DNG}"
```
