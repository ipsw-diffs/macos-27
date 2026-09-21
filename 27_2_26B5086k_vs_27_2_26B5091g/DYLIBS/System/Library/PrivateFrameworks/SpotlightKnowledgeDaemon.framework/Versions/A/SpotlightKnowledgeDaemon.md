## SpotlightKnowledgeDaemon

> `/System/Library/PrivateFrameworks/SpotlightKnowledgeDaemon.framework/Versions/A/SpotlightKnowledgeDaemon`

```diff

-2465.1.2.0.0
-  __TEXT.__text: 0x4b182c
-  __TEXT.__objc_methlist: 0x9610
-  __TEXT.__const: 0x17938
-  __TEXT.__oslogstring: 0x12a2e
-  __TEXT.__cstring: 0x1637e
-  __TEXT.__gcc_except_tab: 0x5b74
+2465.1.3.0.0
+  __TEXT.__text: 0x4b5af0
+  __TEXT.__objc_methlist: 0x9628
+  __TEXT.__const: 0x17aa8
+  __TEXT.__oslogstring: 0x12b8e
+  __TEXT.__cstring: 0x16443
+  __TEXT.__gcc_except_tab: 0x5d88
   __TEXT.__dlopen_cstrs: 0x5e
-  __TEXT.__swift5_typeref: 0xedea
-  __TEXT.__constg_swiftt: 0x90b8
+  __TEXT.__swift5_typeref: 0xee46
+  __TEXT.__constg_swiftt: 0x9188
+  __TEXT.__swift5_reflstr: 0x8d7d
+  __TEXT.__swift5_fieldmd: 0x9194
   __TEXT.__swift5_builtin: 0x244
-  __TEXT.__swift5_reflstr: 0x8d1a
-  __TEXT.__swift5_fieldmd: 0x9130
-  __TEXT.__swift5_assocty: 0x13b0
-  __TEXT.__swift5_capture: 0x38c4
-  __TEXT.__swift5_proto: 0x10ac
-  __TEXT.__swift5_types: 0x8e8
-  __TEXT.__swift_as_entry: 0x488
-  __TEXT.__swift_as_ret: 0x4d8
-  __TEXT.__swift_as_cont: 0x580
-  __TEXT.__swift5_protos: 0x280
+  __TEXT.__swift5_assocty: 0x13e0
+  __TEXT.__swift5_proto: 0x10c4
+  __TEXT.__swift5_types: 0x8f4
+  __TEXT.__swift5_capture: 0x3900
+  __TEXT.__swift_as_entry: 0x498
+  __TEXT.__swift_as_ret: 0x4e0
+  __TEXT.__swift_as_cont: 0x584
+  __TEXT.__swift5_protos: 0x284
   __TEXT.__swift5_mpenum: 0x94
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__unwind_info: 0xf998
-  __TEXT.__eh_frame: 0x15000
+  __TEXT.__unwind_info: 0xfff0
+  __TEXT.__eh_frame: 0x155f0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xd48
+  __DATA_CONST.__const: 0xd30
   __DATA_CONST.__objc_classlist: 0x968
   __DATA_CONST.__objc_catlist: 0x28
-  __DATA_CONST.__objc_protolist: 0x1f8
+  __DATA_CONST.__objc_protolist: 0x1f0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5e48
+  __DATA_CONST.__objc_selrefs: 0x5e68
   __DATA_CONST.__objc_protorefs: 0xc0
-  __DATA_CONST.__objc_superrefs: 0x4d8
-  __DATA_CONST.__objc_arraydata: 0x8b0
-  __DATA_CONST.__got: 0x2328
-  __AUTH_CONST.__const: 0x1c5f0
-  __AUTH_CONST.__cfstring: 0x9360
-  __AUTH_CONST.__objc_const: 0x18388
+  __DATA_CONST.__objc_superrefs: 0x4d0
+  __DATA_CONST.__objc_arraydata: 0xa50
+  __DATA_CONST.__got: 0x2340
+  __AUTH_CONST.__const: 0x1c8a0
+  __AUTH_CONST.__cfstring: 0x9500
+  __AUTH_CONST.__objc_const: 0x184d0
   __AUTH_CONST.__weak_auth_got: 0x18
-  __AUTH_CONST.__objc_intobj: 0x990
-  __AUTH_CONST.__objc_arrayobj: 0x588
-  __AUTH_CONST.__objc_dictobj: 0x2d0
+  __AUTH_CONST.__objc_intobj: 0xb28
+  __AUTH_CONST.__objc_arrayobj: 0x630
+  __AUTH_CONST.__objc_dictobj: 0x320
   __AUTH_CONST.__objc_doubleobj: 0x20
-  __AUTH_CONST.__auth_got: 0x35e8
-  __AUTH.__objc_data: 0x1698
-  __AUTH.__data: 0x2bb8
-  __DATA.__objc_ivar: 0xb68
-  __DATA.__data: 0x3ed0
-  __DATA.__bss: 0xfba0
-  __DATA.__common: 0xe0
-  __DATA_DIRTY.__objc_data: 0x3f50
-  __DATA_DIRTY.__data: 0xbf60
-  __DATA_DIRTY.__bss: 0x8900
-  __DATA_DIRTY.__common: 0x380
+  __AUTH_CONST.__auth_got: 0x35f0
+  __AUTH.__objc_data: 0x15f8
+  __AUTH.__data: 0x2478
+  __DATA.__objc_ivar: 0xb8c
+  __DATA.__data: 0x3560
+  __DATA.__bss: 0xeb00
+  __DATA.__common: 0x58
+  __DATA_DIRTY.__objc_data: 0x3fa0
+  __DATA_DIRTY.__data: 0xd118
+  __DATA_DIRTY.__bss: 0x9a00
+  __DATA_DIRTY.__common: 0x408
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreML.framework/Versions/A/CoreML

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 16901
-  Symbols:   14380
-  CStrings:  3770
+  Functions: 17007
+  Symbols:   14428
+  CStrings:  3782
 
Symbols:
+ -[SKDAnalyticsLogger accumulateError:processor:cellKey:status:]
+ -[SKDAnalyticsLogger accumulateModelCounts:context:language:bucket:]
+ -[SKDAnalyticsLogger sendEvents:]
+ -[SKDAnalyticsLogger slotForCellKey:]
+ -[SKDAnalyticsLogger slotForModelCellKey:]
+ -[SKDAnalyticsLogger takeSnapshot:batchCells:replacementCells:]
+ -[SKDLocationResolution _logPIROutcomeWithLocations:error:]
+ -[SKDPipelineFeedback addAddressesCount:]
+ -[SKDPipelineFeedback addBreadcrumbsCount:]
+ -[SKDPipelineFeedback addLocationsCount:]
+ -[SKDPipelineFeedback addPIRCount:]
+ -[SKDPipelineFeedback addressesCount]
+ -[SKDPipelineFeedback setAddressesCount:]
+ -[SKDPipelineFeedback setPIRCount:]
+ -[SKDRecordProcessor(Internal) logBatchFailureForUpdates:info:]
+ -[SKGDataDetector _callPIRWithQuery:errorBlock:useCase:]
+ -[SKGDataDetector _retrieveLocationFromPIR:locale:errorBlock:]
+ -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityBlock:rangeBlock:errorBlock:]
+ -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityCategories:entityBlock:rangeBlock:errorBlock:]
+ -[SKGDataDetector enumerateDetectedLocationsInString:locale:entityBlock:rangeBlock:errorBlock:]
+ -[SKGDataDetector locationFromAddress:locale:errorBlock:]
+ GCC_except_table58
+ GCC_except_table62
+ OBJC_IVAR_$_SKDAnalyticsLogger._cellCount
+ OBJC_IVAR_$_SKDAnalyticsLogger._cellKeys
+ OBJC_IVAR_$_SKDAnalyticsLogger._cellOverflow
+ OBJC_IVAR_$_SKDAnalyticsLogger._completedItemCount
+ OBJC_IVAR_$_SKDAnalyticsLogger._errorKeyCount
+ OBJC_IVAR_$_SKDAnalyticsLogger._erroredItemCount
+ OBJC_IVAR_$_SKDAnalyticsLogger._modelCellCount
+ OBJC_IVAR_$_SKDAnalyticsLogger._modelCellCounts
+ OBJC_IVAR_$_SKDAnalyticsLogger._modelCellKeys
+ OBJC_IVAR_$_SKDAnalyticsLogger._modelCellOverflow
+ OBJC_IVAR_$_SKDAnalyticsLogger._resultCount
+ OBJC_IVAR_$_SKDPipelineFeedback._addressesCount
+ __62-[SKGDataDetector _retrieveLocationFromPIR:locale:errorBlock:]_block_invoke
+ __83-[SKDDataDetector enumerateResultsWithInputs:options:usingBlock:completionHandler:]_block_invoke_3
+ __DATA__TtC24SpotlightKnowledgeDaemon29GLPInsightsEmbeddingProcessor
+ __IVARS__TtC24SpotlightKnowledgeDaemon29GLPInsightsEmbeddingProcessor
+ __METACLASS_DATA__TtC24SpotlightKnowledgeDaemon29GLPInsightsEmbeddingProcessor
+ __MergedGlobals
+ ___40-[SKDAnalyticsLogSender sendLog:domain:]_block_invoke_2
+ ___56-[SKGDataDetector _callPIRWithQuery:errorBlock:useCase:]_block_invoke
+ ___62-[SKGDataDetector _retrieveLocationFromPIR:locale:errorBlock:]_block_invoke
+ ___62-[SKGDataDetector _retrieveLocationFromPIR:locale:errorBlock:]_block_invoke_2
+ ___76-[SKGDataDetector enumerateAirportCodesInStringUsingGeoScanner:entityBlock:]_block_invoke
+ ___78-[SKDLocationResolution _collectPIRResults:forQuery:locale:completionHandler:]_block_invoke_2
+ ___83-[SKDDataDetector enumerateResultsWithInputs:options:usingBlock:completionHandler:]_block_invoke_3
+ ___89-[SKDLocationResolution enumerateResultsWithInputs:options:usingBlock:completionHandler:]_block_invoke_3
+ ___block_descriptor_48_e8_32bs40r_e17_v16?0"NSError"8l
+ ___block_descriptor_64_e8_32s40s48s56bs_e29_v24?0"NSArray"8"NSError"16l
+ ___block_descriptor_64_e8_32s40s48s56bs_e39_v24?0"SKDEntityLocation"8"NSError"16l
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0l
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e5_v8?0l
+ ___contextIndexFromFeedback_block_invoke
+ ___copy_helper_block_e8_32s40s48s56s64s72b
+ ___destroy_helper_block_e8_32s40s48s56s64s72s
+ ___errorCodeTable_block_invoke
+ ___errorDomainTable_block_invoke
+ ___processorIndexFromIdentifier_block_invoke
+ ___reportPIRError_block_invoke
+ __swift_exist.box.addr_destructor.789Tm
+ _associated conformance 24SpotlightKnowledgeDaemon39GLPInsightsEmbeddingProcessorDescriptorVAA07CascadefG8ProtocolAA0F0AA0fgI0P_AA0hfI0
+ _associated conformance 24SpotlightKnowledgeDaemon39GLPInsightsEmbeddingProcessorDescriptorVAA0fG8ProtocolAA0F0AaDP_AA0fH0
+ _contextIndexFromFeedback
+ _errorDomainTable
+ _objc_msgSend$_callPIRWithQuery:errorBlock:useCase:
+ _objc_msgSend$_retrieveLocationFromPIR:locale:errorBlock:
+ _objc_msgSend$addAddressesCount:
+ _objc_msgSend$addBreadcrumbsCount:
+ _objc_msgSend$addLocationsCount:
+ _objc_msgSend$addPIRCount:
+ _objc_msgSend$addressesCount
+ _objc_msgSend$enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityBlock:rangeBlock:errorBlock:
+ _objc_msgSend$enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityCategories:entityBlock:rangeBlock:errorBlock:
+ _objc_msgSend$enumerateDetectedLocationsInString:locale:entityBlock:rangeBlock:errorBlock:
+ _objc_msgSend$locationFromAddress:locale:errorBlock:
+ _objc_msgSend$logBatchFailureForUpdates:info:
+ _objc_msgSend$setPIRCount:
+ _processorIndexFromIdentifier
+ _reportPIRError
+ _sPIRNoLocationFoundError
+ _sPIRServerErrorNoUnderlying
+ _symbolic $s24SpotlightKnowledgeDaemon22GLPInsightsInterfacingP
+ _symbolic _____ 24SpotlightKnowledgeDaemon20GLPInsightsInterfaceV
+ _symbolic _____ 24SpotlightKnowledgeDaemon29GLPInsightsEmbeddingProcessorC
+ _symbolic _____ 24SpotlightKnowledgeDaemon39GLPInsightsEmbeddingProcessorDescriptorV
+ _symbolic ______p 24SpotlightKnowledgeDaemon22GLPInsightsInterfacingP
+ contextIndexFromFeedback
+ contextIndexFromFeedback.map
+ contextIndexFromFeedback.onceToken
+ errorDomainTable
+ errorDomainTable.domains
+ errorDomainTable.onceToken
+ processorIndexFromIdentifier
+ processorIndexFromIdentifier.map
+ processorIndexFromIdentifier.onceToken
+ reportPIRError.onceToken
- -[SKDAnalyticsErrorKey .cxx_destruct]
- -[SKDAnalyticsErrorKey code]
- -[SKDAnalyticsErrorKey copyWithZone:]
- -[SKDAnalyticsErrorKey domain]
- -[SKDAnalyticsErrorKey hash]
- -[SKDAnalyticsErrorKey initWithDomain:code:]
- -[SKDAnalyticsErrorKey isEqual:]
- -[SKDAnalyticsLogger accumulateError:]
- -[SKDBaseItem initWithIdentifier:status:info:]
- -[SKDPipelineFeedback setPirCount:]
- -[SKDRecordUpdate initWithIdentifier:status:info:]
- -[SKGDataDetector _callPIRWithQuery:hitError:useCase:]
- -[SKGDataDetector _retrieveLocationFromPIR:locale:]
- -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityBlock:rangeBlock:]
- -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityCategories:entityBlock:rangeBlock:]
- -[SKGDataDetector enumerateDetectedLocationsInString:locale:entityBlock:rangeBlock:]
- -[SKGDataDetector locationFromAddress:locale:]
- GCC_except_table59
- OBJC_IVAR_$_SKDAnalyticsErrorKey._code
- OBJC_IVAR_$_SKDAnalyticsErrorKey._domain
- OBJC_IVAR_$_SKDAnalyticsLogger._processTable
- _OBJC_CLASS_$_SKDAnalyticsErrorKey
- _OBJC_METACLASS_$_SKDAnalyticsErrorKey
- __83-[SKDDataDetector enumerateResultsWithInputs:options:usingBlock:completionHandler:]_block_invoke_2
- __OBJC_$_INSTANCE_METHODS_SKDAnalyticsErrorKey
- __OBJC_$_INSTANCE_VARIABLES_SKDAnalyticsErrorKey
- __OBJC_$_PROP_LIST_SKDAnalyticsErrorKey
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCopying
- __OBJC_$_PROTOCOL_METHOD_TYPES_NSCopying
- __OBJC_CLASS_PROTOCOLS_$_SKDAnalyticsErrorKey
- __OBJC_CLASS_RO_$_SKDAnalyticsErrorKey
- __OBJC_LABEL_PROTOCOL_$_NSCopying
- __OBJC_METACLASS_RO_$_SKDAnalyticsErrorKey
- __OBJC_PROTOCOL_$_NSCopying
- ___51-[SKGDataDetector _retrieveLocationFromPIR:locale:]_block_invoke
- ___51-[SKGDataDetector _retrieveLocationFromPIR:locale:]_block_invoke_2
- ___54-[SKGDataDetector _callPIRWithQuery:hitError:useCase:]_block_invoke
- ___block_descriptor_56_e8_32s40s48bs_e29_v24?0"NSArray"8"NSError"16l
- ___block_descriptor_56_e8_32s40s48bs_e39_v24?0"SKDEntityLocation"8"NSError"16l
- __swift_exist.box.addr_destructor.786Tm
- _objc_msgSend$_callPIRWithQuery:hitError:useCase:
- _objc_msgSend$_retrieveLocationFromPIR:locale:
- _objc_msgSend$enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityBlock:rangeBlock:
- _objc_msgSend$enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityCategories:entityBlock:rangeBlock:
- _objc_msgSend$enumerateDetectedLocationsInString:locale:entityBlock:rangeBlock:
- _objc_msgSend$initWithDomain:code:
- _objc_msgSend$locationFromAddress:locale:
- _objc_msgSend$setBreadcrumbsCount:
- _objc_msgSend$setPirCount:
- pipelineIndexFromName.map
- pipelineIndexFromName.onceToken
CStrings:
+ "SKDAnalyticsLogger: merged cell table saturated at %{public}lu cells; some (processor, context, language, textSize) cells were not reported"
+ "SKDAnalyticsLogger: model cell table saturated at %{public}lu cells; some (model, context, language, textSize) cells were not reported"
+ "SKDDataDetectorsProcessor"
+ "SKDKeyphrasesProcessor"
+ "SKDLocationResolutionProcessor"
+ "SKDTextEmbeddingProcessor"
+ "[GLPInsightsEmbeddingProcessor] Passing through item in set %hu"
+ "[ModelCatalog] AEM version modified, %s to %ld. Requesting MD%ld. Posting notification"
+ "contextName"
+ "glpInsightsEmbedding"
+ "itemCount"
+ "languageType"
+ "modelCount"
+ "modelName"
+ "resultCount"
+ "textContentSize"
- "[ModelCatalog] AEM version modified, %ld to %ld. Posting notification"
- "skd_batch_summary"
- "skd_error_summary"
- "skd_process_summary"
```
