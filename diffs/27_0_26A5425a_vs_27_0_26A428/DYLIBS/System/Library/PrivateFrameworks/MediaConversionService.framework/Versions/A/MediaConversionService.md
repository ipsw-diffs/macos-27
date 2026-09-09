## MediaConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/Versions/A/MediaConversionService`

```diff

 911.0.134.0.0
-  __TEXT.__text: 0x1d200
-  __TEXT.__objc_methlist: 0x1c3c
+  __TEXT.__text: 0x200e0
+  __TEXT.__objc_methlist: 0x1eec
   __TEXT.__const: 0xc8
-  __TEXT.__gcc_except_tab: 0x548
-  __TEXT.__cstring: 0x4c4d
-  __TEXT.__oslogstring: 0x251f
-  __TEXT.__unwind_info: 0x760
+  __TEXT.__gcc_except_tab: 0x55c
+  __TEXT.__cstring: 0x5931
+  __TEXT.__oslogstring: 0x2885
+  __TEXT.__unwind_info: 0x7c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4f0
-  __DATA_CONST.__objc_classlist: 0xb8
+  __DATA_CONST.__const: 0x648
+  __DATA_CONST.__objc_classlist: 0xc8
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x14a8
+  __DATA_CONST.__objc_selrefs: 0x1630
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x58
-  __DATA_CONST.__objc_arraydata: 0x4c8
-  __DATA_CONST.__got: 0x390
-  __AUTH_CONST.__const: 0x860
-  __AUTH_CONST.__cfstring: 0x2d40
-  __AUTH_CONST.__objc_const: 0x2a78
+  __DATA_CONST.__objc_superrefs: 0x60
+  __DATA_CONST.__objc_arraydata: 0x578
+  __DATA_CONST.__got: 0x3b0
+  __AUTH_CONST.__const: 0x920
+  __AUTH_CONST.__cfstring: 0x3400
+  __AUTH_CONST.__objc_const: 0x2f88
   __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0
-  __DATA.__objc_ivar: 0x200
-  __DATA.__data: 0x488
+  __AUTH.__objc_data: 0xa0
+  __DATA.__objc_ivar: 0x250
+  __DATA.__data: 0x4a8
   __DATA.__bss: 0x50
   __DATA_DIRTY.__objc_data: 0x730
   __DATA_DIRTY.__bss: 0x20

   - /System/Library/PrivateFrameworks/PhotosFormats.framework/Versions/A/PhotosFormats
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 673
-  Symbols:   1911
-  CStrings:  549
+  Functions: 741
+  Symbols:   2081
+  CStrings:  619
 
Symbols:
+ -[ConversionOptionSet setSourcePathProvenanceUnprocessedImage:]
+ -[ConversionOptionSet sourcePathProvenanceUnprocessedImage]
+ -[PAImageConversionServiceClient(ContentProvenance) embedProcessedProvenanceFromRegularImageAtURL:intoRegularImageAtURL:destinationURL:options:completionHandler:]
+ -[PAImageConversionServiceClient(ContentProvenance) embedUnprocessedProvenanceImageAtURL:intoRegularImageAtURL:destinationURL:options:completionHandler:]
+ -[PAImageConversionServiceClient(ContentProvenance) processContentProvenanceForSourceURLCollection:destinationURL:options:completionHandler:]
+ -[PAImageConversionServiceClient(ContentProvenance) stripProvenanceMetadataFromOriginalProvenanceImageAtURL:destinationURL:options:completionHandler:]
+ -[PAImageConversionServiceClient(ContentProvenance) validateContentProvenanceForProcessedImageAtURL:options:completionHandler:]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult .cxx_destruct]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult diagnosticsRequested]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult setDiagnosticsRequested:]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult setUtcLowerBoundTimestamp:]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult setUtcProcessingTimestamp:]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult setUtcUpperBoundTimestamp:]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult utcLowerBoundTimestamp]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult utcProcessingTimestamp]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult utcUpperBoundTimestamp]
+ -[PAMediaConversionServiceContentProvenanceValidationResult .cxx_destruct]
+ -[PAMediaConversionServiceContentProvenanceValidationResult certificateVerificationStatus]
+ -[PAMediaConversionServiceContentProvenanceValidationResult init]
+ -[PAMediaConversionServiceContentProvenanceValidationResult processedJPEGImageData]
+ -[PAMediaConversionServiceContentProvenanceValidationResult revocationCheckIdentifier]
+ -[PAMediaConversionServiceContentProvenanceValidationResult revocationStatus]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setCertificateVerificationStatus:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setProcessedJPEGImageData:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setRevocationCheckIdentifier:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setRevocationStatus:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setSignatureVerificationStatus:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setUtcLowerBoundTimestamp:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setUtcProcessingTimestamp:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setUtcUpperBoundTimestamp:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult signatureVerificationStatus]
+ -[PAMediaConversionServiceContentProvenanceValidationResult utcLowerBoundTimestamp]
+ -[PAMediaConversionServiceContentProvenanceValidationResult utcProcessingTimestamp]
+ -[PAMediaConversionServiceContentProvenanceValidationResult utcUpperBoundTimestamp]
+ -[PAMediaConversionServiceContentProvenanceValidationResult validationStatus]
+ -[PHMediaFormatConversionCompositeRequest requiresProvenanceMetadataChange]
+ -[PHMediaFormatConversionImplementation_MediaConversionService _submitAdjustedProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]
+ -[PHMediaFormatConversionImplementation_MediaConversionService _submitProvenanceProcessedEmbedRequest:destination:options:completionHandler:]
+ -[PHMediaFormatConversionRequest _requiresNonProvenanceMetadataChange]
+ -[PHMediaFormatConversionRequest provenanceAdjustedRenderSourceURL]
+ -[PHMediaFormatConversionRequest provenanceMetadataBehavior]
+ -[PHMediaFormatConversionRequest provenanceProcessedOriginalDestinationURL]
+ -[PHMediaFormatConversionRequest provenanceProcessedSourceImageURL]
+ -[PHMediaFormatConversionRequest provenanceSidecarURL]
+ -[PHMediaFormatConversionRequest requiresProvenanceMetadataChange]
+ -[PHMediaFormatConversionRequest setProvenanceMetadataBehavior:withProcessedSourceImageURL:]
+ -[PHMediaFormatConversionRequest setProvenanceMetadataBehavior:withProvenanceSidecarURL:]
+ -[PHMediaFormatConversionRequest setProvenanceMetadataBehavior:withUnprocessedSourceAdjustedRenderURL:processedOriginalDestinationURL:sidecarURL:]
+ -[PHMediaFormatConversionRequest setShouldPreserveProvenance:]
+ -[PHMediaFormatConversionRequest shouldPreserveProvenance]
+ -[PHMediaFormatConversionSource checkForProvenanceData]
+ -[PHMediaFormatConversionSource markProvenanceMetadataAsCheckedWithStatus:]
+ -[PHMediaFormatConversionSource provenanceMetadataStatus]
+ -[PHMediaFormatConversionSource setProvenanceMetadataStatus:]
+ -[PHMediaFormatConversionSource sourceProvenanceMetadataStatus]
+ GCC_except_table107
+ GCC_except_table113
+ GCC_except_table156
+ GCC_except_table173
+ GCC_except_table177
+ GCC_except_table181
+ GCC_except_table184
+ GCC_except_table194
+ GCC_except_table202
+ GCC_except_table431
+ GCC_except_table433
+ GCC_except_table435
+ GCC_except_table437
+ GCC_except_table439
+ GCC_except_table441
+ GCC_except_table443
+ GCC_except_table445
+ GCC_except_table560
+ GCC_except_table570
+ GCC_except_table602
+ GCC_except_table606
+ GCC_except_table694
+ GCC_except_table696
+ GCC_except_table699
+ GCC_except_table701
+ GCC_except_table714
+ OBJC_IVAR_$_ConversionOptionSet._sourcePathProvenanceUnprocessedImage
+ OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceProcessingResult._diagnosticsRequested
+ OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceProcessingResult._utcLowerBoundTimestamp
+ OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceProcessingResult._utcProcessingTimestamp
+ OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceProcessingResult._utcUpperBoundTimestamp
+ OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._certificateVerificationStatus
+ OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._processedJPEGImageData
+ OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._revocationCheckIdentifier
+ OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._revocationStatus
+ OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._signatureVerificationStatus
+ OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._utcLowerBoundTimestamp
+ OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._utcProcessingTimestamp
+ OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._utcUpperBoundTimestamp
+ OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceAdjustedRenderSourceURL
+ OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceMetadataBehavior
+ OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceProcessedOriginalDestinationURL
+ OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceProcessedSourceImageURL
+ OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceSidecarURL
+ OBJC_IVAR_$_PHMediaFormatConversionRequest._shouldPreserveProvenance
+ OBJC_IVAR_$_PHMediaFormatConversionSource._provenanceMetadataStatus
+ _OBJC_CLASS_$_NSBundle
+ _OBJC_CLASS_$_PAMediaConversionServiceContentProvenanceProcessingResult
+ _OBJC_CLASS_$_PAMediaConversionServiceContentProvenanceValidationResult
+ _OBJC_METACLASS_$_PAMediaConversionServiceContentProvenanceProcessingResult
+ _OBJC_METACLASS_$_PAMediaConversionServiceContentProvenanceValidationResult
+ _PAMediaConversionIsProvenanceEligibilityError
+ _PAMediaConversionIsProvenanceProcessingTimeoutError
+ _PAMediaConversionResourceRoleProvenanceProcessedSourceImage
+ _PAMediaConversionResourceRoleProvenanceUnprocessed
+ _PAMediaConversionServiceOptionClientProcessNameKey
+ _PAMediaConversionServiceOptionIsContentProvenanceDryRunKey
+ _PAMediaConversionServiceOptionIsContentProvenanceMetadataStrippingConversionKey
+ _PAMediaConversionServiceOptionIsContentProvenanceProcessedEmbeddingConversionKey
+ _PAMediaConversionServiceOptionIsContentProvenanceProcessingConversionKey
+ _PAMediaConversionServiceOptionIsContentProvenanceUnprocessedEmbeddingConversionKey
+ _PAMediaConversionServiceOptionIsContentProvenanceValidationKey
+ _PAMediaConversionServiceOptionIsContentProvenanceValidationUnwrappedImageKey
+ _PAMediaConversionServiceOptionPreserveProvenanceKey
+ _PAMediaConversionServiceOptionProvenanceOriginalAssetLocalIdentifierKey
+ _PAMediaConversionServiceOptionUnitTestSupportUseMockProvenanceProcessingKey
+ _PAMediaConversionServiceProvenanceCertificateVerificationStatusKey
+ _PAMediaConversionServiceProvenanceCloudAppErrorDomain
+ _PAMediaConversionServiceProvenanceDiagnosticsRequestedKey
+ _PAMediaConversionServiceProvenanceProcessingDateAgeTimeIntervalKey
+ _PAMediaConversionServiceProvenanceProcessingResultMetadataKey
+ _PAMediaConversionServiceProvenanceRevocationCheckIdentifierKey
+ _PAMediaConversionServiceProvenanceRevocationStatusKey
+ _PAMediaConversionServiceProvenanceRoundTripDurationKey
+ _PAMediaConversionServiceProvenanceSignatureVerificationStatusKey
+ _PAMediaConversionServiceProvenanceUTCLowerBoundTimestampKey
+ _PAMediaConversionServiceProvenanceUTCProcessingTimestampKey
+ _PAMediaConversionServiceProvenanceUTCUpperBoundTimestampKey
+ _PAMediaConversionServiceProvenanceUploadDurationKey
+ _PAMediaConversionServiceProvenanceValidationResultMetadataKey
+ _UTTypeDNG
+ __112-[PHMediaFormatConversionImplementation_MediaConversionService performImageConversionRequest:completionHandler:]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_PAImageConversionServiceClient(ContentProvenance)
+ __OBJC_$_INSTANCE_METHODS_PAMediaConversionServiceContentProvenanceProcessingResult
+ __OBJC_$_INSTANCE_METHODS_PAMediaConversionServiceContentProvenanceValidationResult
+ __OBJC_$_INSTANCE_VARIABLES_PAMediaConversionServiceContentProvenanceProcessingResult
+ __OBJC_$_INSTANCE_VARIABLES_PAMediaConversionServiceContentProvenanceValidationResult
+ __OBJC_$_PROP_LIST_PAMediaConversionServiceContentProvenanceProcessingResult
+ __OBJC_$_PROP_LIST_PAMediaConversionServiceContentProvenanceValidationResult
+ __OBJC_CLASS_RO_$_PAMediaConversionServiceContentProvenanceProcessingResult
+ __OBJC_CLASS_RO_$_PAMediaConversionServiceContentProvenanceValidationResult
+ __OBJC_METACLASS_RO_$_PAMediaConversionServiceContentProvenanceProcessingResult
+ __OBJC_METACLASS_RO_$_PAMediaConversionServiceContentProvenanceValidationResult
+ ___127-[PAImageConversionServiceClient(ContentProvenance) validateContentProvenanceForProcessedImageAtURL:options:completionHandler:]_block_invoke
+ ___141-[PAImageConversionServiceClient(ContentProvenance) processContentProvenanceForSourceURLCollection:destinationURL:options:completionHandler:]_block_invoke
+ ___141-[PHMediaFormatConversionImplementation_MediaConversionService _submitProvenanceProcessedEmbedRequest:destination:options:completionHandler:]_block_invoke
+ ___150-[PAImageConversionServiceClient(ContentProvenance) stripProvenanceMetadataFromOriginalProvenanceImageAtURL:destinationURL:options:completionHandler:]_block_invoke
+ ___153-[PAImageConversionServiceClient(ContentProvenance) embedUnprocessedProvenanceImageAtURL:intoRegularImageAtURL:destinationURL:options:completionHandler:]_block_invoke
+ ___162-[PAImageConversionServiceClient(ContentProvenance) embedProcessedProvenanceFromRegularImageAtURL:intoRegularImageAtURL:destinationURL:options:completionHandler:]_block_invoke
+ ___165-[PHMediaFormatConversionImplementation_MediaConversionService _submitAdjustedProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]_block_invoke
+ ___75-[PHMediaFormatConversionCompositeRequest requiresProvenanceMetadataChange]_block_invoke
+ ___block_descriptor_40_e8_32bs_e37_v32?0q8"NSDictionary"16"NSError"24l
+ ___block_descriptor_56_e8_32s40s48bs_e20_v24?0q8"NSError"16l
+ ___block_descriptor_64_e8_32s40s48s56bs_e20_v24?0q8"NSError"16l
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e37_v32?0q8"NSDictionary"16"NSError"24l
+ _getprogname
+ _objc_msgSend$_requiresNonProvenanceMetadataChange
+ _objc_msgSend$_submitAdjustedProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:
+ _objc_msgSend$_submitProvenanceProcessedEmbedRequest:destination:options:completionHandler:
+ _objc_msgSend$bundleIdentifier
+ _objc_msgSend$checkForProvenanceData
+ _objc_msgSend$embedProcessedProvenanceFromRegularImageAtURL:intoRegularImageAtURL:destinationURL:options:completionHandler:
+ _objc_msgSend$hasProvenanceMetadata
+ _objc_msgSend$mainBundle
+ _objc_msgSend$markProvenanceMetadataAsCheckedWithStatus:
+ _objc_msgSend$provenanceAdjustedRenderSourceURL
+ _objc_msgSend$provenanceMetadataBehavior
+ _objc_msgSend$provenanceMetadataStatus
+ _objc_msgSend$provenanceProcessedOriginalDestinationURL
+ _objc_msgSend$provenanceProcessedSourceImageURL
+ _objc_msgSend$provenanceSidecarURL
+ _objc_msgSend$requiresProvenanceMetadataChange
+ _objc_msgSend$setCertificateVerificationStatus:
+ _objc_msgSend$setDiagnosticsRequested:
+ _objc_msgSend$setProcessedJPEGImageData:
+ _objc_msgSend$setProvenanceMetadataBehavior:withProcessedSourceImageURL:
+ _objc_msgSend$setProvenanceMetadataBehavior:withProvenanceSidecarURL:
+ _objc_msgSend$setProvenanceMetadataBehavior:withUnprocessedSourceAdjustedRenderURL:processedOriginalDestinationURL:sidecarURL:
+ _objc_msgSend$setRevocationCheckIdentifier:
+ _objc_msgSend$setRevocationStatus:
+ _objc_msgSend$setShouldPreserveProvenance:
+ _objc_msgSend$setSignatureVerificationStatus:
+ _objc_msgSend$setSourcePathProvenanceUnprocessedImage:
+ _objc_msgSend$setUtcLowerBoundTimestamp:
+ _objc_msgSend$setUtcProcessingTimestamp:
+ _objc_msgSend$setUtcUpperBoundTimestamp:
+ _objc_msgSend$shouldPreserveProvenance
+ _objc_msgSend$sourcePathProvenanceUnprocessedImage
+ _objc_msgSend$sourceProvenanceMetadataStatus
+ _objc_msgSend$stringWithUTF8String:
+ _objc_msgSend$stripProvenanceMetadataFromOriginalProvenanceImageAtURL:destinationURL:options:completionHandler:
- GCC_except_table116
- GCC_except_table133
- GCC_except_table137
- GCC_except_table141
- GCC_except_table144
- GCC_except_table154
- GCC_except_table162
- GCC_except_table374
- GCC_except_table376
- GCC_except_table378
- GCC_except_table380
- GCC_except_table382
- GCC_except_table384
- GCC_except_table386
- GCC_except_table501
- GCC_except_table511
- GCC_except_table537
- GCC_except_table541
- GCC_except_table627
- GCC_except_table629
- GCC_except_table632
- GCC_except_table634
- GCC_except_table647
- GCC_except_table77
- GCC_except_table83
- __OBJC_$_INSTANCE_METHODS_PAImageConversionServiceClient
CStrings:
+ "#Q"
+ "--source-provenance-unprocessed-image is only valid for image conversions\n"
+ "-t|--type [%@] -s|--source <input media path> -d|--destination <output media path> [--source-video-complement <input media path>] [--destination-video-complement <output media path>] [--source-provenance-unprocessed-image <input provenance image path>] [--partial-results-cache-directory <cache directory path>] [--replace] [[-o|--option <key>=<value>], ...] [-r|--preset <preset>] [-c|--count <count>] [-v|--verbose] [--wait] [-p|--progress] [--pause] [--launch] [--launch-and-pause] [--next]"
+ "Invalid request using single pass encoding option and metadata changes (like location stripping, custom location, custom creation date, custom description, custom provenance) for video source %@"
+ "Network.NWError"
+ "PAMediaConversionResourceRoleProvenanceProcessedSourceImage"
+ "PAMediaConversionResourceRoleProvenanceUnprocessed"
+ "PAMediaConversionServiceErrorCodeMissingProvenanceProcessedMetadata"
+ "PAMediaConversionServiceErrorCodeMissingProvenanceUnprocessedMetadata"
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppInternalError"
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppManifestCertificateVerificationFailed"
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppSEPSignatureVerificationFailed"
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppSensorSignatureVerificationFailed"
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppUnknown"
+ "PAMediaConversionServiceErrorCodeProvenanceIneligible"
+ "PAMediaConversionServiceErrorCodeProvenanceMalformedResponse"
+ "PAMediaConversionServiceErrorCodeProvenanceMissingPayload"
+ "PAMediaConversionServiceErrorCodeProvenanceProcessedValidationFailure"
+ "PAMediaConversionServiceErrorCodeProvenanceProcessingDateExpired"
+ "PAMediaConversionServiceErrorCodeProvenanceRevocationCheckFailure"
+ "PAMediaConversionServiceErrorCodeProvenanceSourceDNGUnavailable"
+ "PAMediaConversionServiceErrorCodeProvenanceTemporaryFileWriteFailure"
+ "PAMediaConversionServiceErrorCodeProvenanceTimeout"
+ "PAMediaConversionServiceOptionClientProcessNameKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceDryRunKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceMetadataStrippingConversionKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceProcessedEmbeddingConversionKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceProcessingConversionKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceUnprocessedEmbeddingConversionKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceValidationKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceValidationUnwrappedImageKey"
+ "PAMediaConversionServiceOptionPreserveProvenanceKey"
+ "PAMediaConversionServiceOptionProvenanceOriginalAssetLocalIdentifierKey"
+ "PAMediaConversionServiceOptionUnitTestSupportUseMockProvenanceProcessingKey"
+ "PAMediaConversionServiceProvenanceCertificateVerificationStatusKey"
+ "PAMediaConversionServiceProvenanceCloudAppErrorDomain"
+ "PAMediaConversionServiceProvenanceDiagnosticsRequestedKey"
+ "PAMediaConversionServiceProvenanceProcessingDateAgeTimeIntervalKey"
+ "PAMediaConversionServiceProvenanceProcessingResultMetadataKey"
+ "PAMediaConversionServiceProvenanceRevocationCheckIdentifierKey"
+ "PAMediaConversionServiceProvenanceRevocationStatusKey"
+ "PAMediaConversionServiceProvenanceRoundTripDurationKey"
+ "PAMediaConversionServiceProvenanceSignatureVerificationStatusKey"
+ "PAMediaConversionServiceProvenanceUTCLowerBoundTimestampKey"
+ "PAMediaConversionServiceProvenanceUTCProcessingTimestampKey"
+ "PAMediaConversionServiceProvenanceUTCUpperBoundTimestampKey"
+ "PAMediaConversionServiceProvenanceUploadDurationKey"
+ "PAMediaConversionServiceProvenanceValidationResultMetadataKey"
+ "PrivateCloudComputeError"
+ "Provenance embed processed failed: %@. Original: %@, Carrier: %@"
+ "Provenance embed processed succeeded. Destination: %@"
+ "Provenance processing failed: %@. Source: %@"
+ "Provenance processing succeeded. Destination URL: %@"
+ "Provenance provenanceSidecarURL is nil."
+ "Provenance stripping failed: %@. Source: %@"
+ "Provenance stripping succeeded. Destination: %@"
+ "Read provenance metadata status: %ld from file: %@"
+ "Requesting Provenance embed processed metadata from original: %@ into carrier: %@, destination: %@."
+ "Requesting Provenance processing with source: %@, destination: %@."
+ "Requesting Provenance strip metadata at URL: %@, destination: %@."
+ "Requesting single-pass Provenance processing with adjusted render. Source: %@, destination: %@."
+ "Single-pass Provenance processing failed: %@. Source: %@"
+ "Single-pass Provenance processing succeeded. Destination URL: %@"
+ "[sourceURLCollection resourceURLForRole:PAMediaConversionResourceRoleMainResource]"
+ "destinationURL"
+ "imageURL"
+ "originalProvenanceImageURL"
+ "processedProvenanceImageURL"
+ "regularImageURL"
+ "request.provenanceProcessedOriginalDestinationURL"
+ "source-provenance-unprocessed-image"
+ "unprocessedProvenanceImageURL"
+ "v24@?0q8@\"NSError\"16"
- "#A"
- "-t|--type [%@] -s|--source <input media path> -d|--destination <output media path> [--source-video-complement <input media path>] [--destination-video-complement <output media path>] [--partial-results-cache-directory <cache directory path>] [--replace] [[-o|--option <key>=<value>], ...] [-r|--preset <preset>] [-c|--count <count>] [-v|--verbose] [--wait] [-p|--progress] [--pause] [--launch] [--launch-and-pause] [--next]"
- "Invalid request using single pass encoding option and metadata changes (like location stripping, custom location, custom creation date, custom description) for video source %@"
```
