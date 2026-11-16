## IntelligencePlatformLibrary

> `/System/Library/PrivateFrameworks/IntelligencePlatformLibrary.framework/Versions/A/IntelligencePlatformLibrary`

```diff

-441.45.0.0.0
-  __TEXT.__text: 0x76615c
-  __TEXT.__objc_methlist: 0x2634c
-  __TEXT.__const: 0x5d1e0
-  __TEXT.__constg_swiftt: 0xa3b8
-  __TEXT.__swift5_typeref: 0xab18
-  __TEXT.__swift5_fieldmd: 0x177e0
-  __TEXT.__swift5_types: 0x14e0
-  __TEXT.__swift5_reflstr: 0x1621a
-  __TEXT.__swift5_assocty: 0x45b0
+441.45.5.0.0
+  __TEXT.__text: 0x7870e4
+  __TEXT.__objc_methlist: 0x26594
+  __TEXT.__const: 0x5ed60
+  __TEXT.__constg_swiftt: 0xa6d8
+  __TEXT.__swift5_typeref: 0xaebc
+  __TEXT.__swift5_fieldmd: 0x18190
+  __TEXT.__swift5_types: 0x1548
+  __TEXT.__swift5_reflstr: 0x16d3a
+  __TEXT.__swift5_assocty: 0x47c0
   __TEXT.__oslogstring: 0x1f4
-  __TEXT.__swift5_capture: 0x38e0
-  __TEXT.__swift5_proto: 0x6798
+  __TEXT.__swift5_capture: 0x3910
+  __TEXT.__swift5_proto: 0x69b8
   __TEXT.__swift5_protos: 0x40
-  __TEXT.__cstring: 0x71ab1
+  __TEXT.__cstring: 0x737a5
   __TEXT.__swift5_builtin: 0x640
   __TEXT.__swift5_mpenum: 0x608
   __TEXT.__gcc_except_tab: 0x40
-  __TEXT.__unwind_info: 0x28f78
-  __TEXT.__eh_frame: 0x22028
+  __TEXT.__unwind_info: 0x29c18
+  __TEXT.__eh_frame: 0x22fc8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9510
-  __DATA_CONST.__objc_classlist: 0x13b8
+  __DATA_CONST.__const: 0x95a0
+  __DATA_CONST.__objc_classlist: 0x13c8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x64a8
+  __DATA_CONST.__objc_selrefs: 0x6500
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x88
-  __DATA_CONST.__got: 0x17f8
-  __AUTH_CONST.__const: 0x41b90
-  __AUTH_CONST.__cfstring: 0x269a0
-  __AUTH_CONST.__objc_const: 0x40810
+  __DATA_CONST.__got: 0x1808
+  __AUTH_CONST.__const: 0x42e80
+  __AUTH_CONST.__cfstring: 0x26c60
+  __AUTH_CONST.__objc_const: 0x40d10
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__auth_got: 0xc98
-  __AUTH.__objc_data: 0xb6a8
-  __AUTH.__data: 0x3bd8
-  __DATA.__objc_ivar: 0x32e0
-  __DATA.__data: 0xb1a8
-  __DATA.__bss: 0x72290
-  __DATA.__common: 0x6788
+  __AUTH.__objc_data: 0xb748
+  __AUTH.__data: 0x40a0
+  __DATA.__objc_ivar: 0x332c
+  __DATA.__data: 0xb558
+  __DATA.__bss: 0x74ba0
+  __DATA.__common: 0x6938
   __DATA_DIRTY.__objc_data: 0x1310
   __DATA_DIRTY.__data: 0x5fc8
-  __DATA_DIRTY.__bss: 0xa740
+  __DATA_DIRTY.__bss: 0xa980
   __DATA_DIRTY.__common: 0x18
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 62794
-  Symbols:   30068
-  CStrings:  11137
+  Functions: 63798
+  Symbols:   30275
+  CStrings:  11354
 
Symbols:
+ +[CCSetLibraryConfigurationRegistry configurationForSet_SiriConversationRecap]
+ +[CCSetLibraryConfigurationRegistry syncPolicyForSet_SiriConversationRecap]
+ +[CCSiriConversationRecapContent contentMessageClass]
+ +[CCSiriConversationRecapContent descriptionForTypeIdentifier:]
+ +[CCSiriConversationRecapContent itemType]
+ +[CCSiriConversationRecapContent metaContentMessageClass]
+ +[CCSiriConversationRecapContent typeIdentifierForDescription:]
+ +[CCSiriConversationRecapMetaContent contentMessageClass]
+ +[CCSiriConversationRecapMetaContent descriptionForTypeIdentifier:]
+ +[CCSiriConversationRecapMetaContent itemType]
+ +[CCSiriConversationRecapMetaContent metaContentMessageClass]
+ +[CCSiriConversationRecapMetaContent typeIdentifierForDescription:]
+ -[CCSiriConversationRecapContent .cxx_destruct]
+ -[CCSiriConversationRecapContent captureIntervalEnd]
+ -[CCSiriConversationRecapContent captureIntervalStart]
+ -[CCSiriConversationRecapContent copyApplyingPatch:deletedFieldTypes:error:]
+ -[CCSiriConversationRecapContent decodeFieldValuesFromData:error:]
+ -[CCSiriConversationRecapContent enumerateFieldsUsingBlock:parentFieldType:]
+ -[CCSiriConversationRecapContent hasIsSaved]
+ -[CCSiriConversationRecapContent inferredLocationTags]
+ -[CCSiriConversationRecapContent initWithData:error:]
+ -[CCSiriConversationRecapContent initWithJSONDictionary:error:]
+ -[CCSiriConversationRecapContent initWithKind:title:summary:transcriptsText:inferredLocationTags:captureIntervalStart:captureIntervalEnd:isSaved:error:]
+ -[CCSiriConversationRecapContent isSaved]
+ -[CCSiriConversationRecapContent jsonDictionary]
+ -[CCSiriConversationRecapContent kind]
+ -[CCSiriConversationRecapContent setHasIsSaved:]
+ -[CCSiriConversationRecapContent summary]
+ -[CCSiriConversationRecapContent title]
+ -[CCSiriConversationRecapContent transcriptsText]
+ -[CCSiriConversationRecapMetaContent .cxx_destruct]
+ -[CCSiriConversationRecapMetaContent cacheContentHash]
+ -[CCSiriConversationRecapMetaContent copyApplyingPatch:deletedFieldTypes:error:]
+ -[CCSiriConversationRecapMetaContent createdDate]
+ -[CCSiriConversationRecapMetaContent decodeFieldValuesFromData:error:]
+ -[CCSiriConversationRecapMetaContent enumerateFieldsUsingBlock:parentFieldType:]
+ -[CCSiriConversationRecapMetaContent hasCacheContentHash]
+ -[CCSiriConversationRecapMetaContent initWithData:error:]
+ -[CCSiriConversationRecapMetaContent initWithJSONDictionary:error:]
+ -[CCSiriConversationRecapMetaContent initWithSourceItemIdentifier:sourceBundleIdentifier:createdDate:modifiedDate:cacheContentHash:error:]
+ -[CCSiriConversationRecapMetaContent jsonDictionary]
+ -[CCSiriConversationRecapMetaContent modifiedDate]
+ -[CCSiriConversationRecapMetaContent setHasCacheContentHash:]
+ -[CCSiriConversationRecapMetaContent sourceBundleIdentifier]
+ -[CCSiriConversationRecapMetaContent sourceItemIdentifier]
+ GCC_except_table7602
+ GCC_except_table8197
+ _CCModelCatalogRequestedUseCaseContentArgumentIdentifierFromString.sortedEnums
+ _OBJC_CLASS_$_CCSiriConversationRecapContent
+ _OBJC_CLASS_$_CCSiriConversationRecapMetaContent
+ _OBJC_IVAR_$_CCSiriConversationRecapContent._hasIsSaved
+ _OBJC_IVAR_$_CCSiriConversationRecapContent._hasRaw_captureIntervalEnd
+ _OBJC_IVAR_$_CCSiriConversationRecapContent._hasRaw_captureIntervalStart
+ _OBJC_IVAR_$_CCSiriConversationRecapContent._inferredLocationTags
+ _OBJC_IVAR_$_CCSiriConversationRecapContent._isSaved
+ _OBJC_IVAR_$_CCSiriConversationRecapContent._kind
+ _OBJC_IVAR_$_CCSiriConversationRecapContent._raw_captureIntervalEnd
+ _OBJC_IVAR_$_CCSiriConversationRecapContent._raw_captureIntervalStart
+ _OBJC_IVAR_$_CCSiriConversationRecapContent._summary
+ _OBJC_IVAR_$_CCSiriConversationRecapContent._title
+ _OBJC_IVAR_$_CCSiriConversationRecapContent._transcriptsText
+ _OBJC_IVAR_$_CCSiriConversationRecapMetaContent._cacheContentHash
+ _OBJC_IVAR_$_CCSiriConversationRecapMetaContent._hasCacheContentHash
+ _OBJC_IVAR_$_CCSiriConversationRecapMetaContent._hasRaw_createdDate
+ _OBJC_IVAR_$_CCSiriConversationRecapMetaContent._hasRaw_modifiedDate
+ _OBJC_IVAR_$_CCSiriConversationRecapMetaContent._raw_createdDate
+ _OBJC_IVAR_$_CCSiriConversationRecapMetaContent._raw_modifiedDate
+ _OBJC_IVAR_$_CCSiriConversationRecapMetaContent._sourceBundleIdentifier
+ _OBJC_IVAR_$_CCSiriConversationRecapMetaContent._sourceItemIdentifier
+ _OBJC_METACLASS_$_CCSiriConversationRecapContent
+ _OBJC_METACLASS_$_CCSiriConversationRecapMetaContent
+ _OUTLINED_FUNCTION_491
+ _OUTLINED_FUNCTION_492
+ _OUTLINED_FUNCTION_631
+ _OUTLINED_FUNCTION_632
+ _OUTLINED_FUNCTION_633
+ _OUTLINED_FUNCTION_634
+ _OUTLINED_FUNCTION_635
+ _OUTLINED_FUNCTION_636
+ _OUTLINED_FUNCTION_637
+ __OBJC_$_CLASS_METHODS_CCSiriConversationRecapContent
+ __OBJC_$_CLASS_METHODS_CCSiriConversationRecapMetaContent
+ __OBJC_$_INSTANCE_METHODS_CCSiriConversationRecapContent
+ __OBJC_$_INSTANCE_METHODS_CCSiriConversationRecapMetaContent
+ __OBJC_$_INSTANCE_VARIABLES_CCSiriConversationRecapContent
+ __OBJC_$_INSTANCE_VARIABLES_CCSiriConversationRecapMetaContent
+ __OBJC_$_PROP_LIST_CCSiriConversationRecapContent
+ __OBJC_$_PROP_LIST_CCSiriConversationRecapMetaContent
+ __OBJC_CLASS_PROTOCOLS_$_CCSiriConversationRecapContent
+ __OBJC_CLASS_PROTOCOLS_$_CCSiriConversationRecapMetaContent
+ __OBJC_CLASS_RO_$_CCSiriConversationRecapContent
+ __OBJC_CLASS_RO_$_CCSiriConversationRecapMetaContent
+ __OBJC_METACLASS_RO_$_CCSiriConversationRecapContent
+ __OBJC_METACLASS_RO_$_CCSiriConversationRecapMetaContent
+ ___swift_memcpy132_8
+ ___swift_memcpy663_8
+ _associated conformance 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV10TaskConfigV02DpK0VSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV10TaskConfigV8FeaturesVSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV10TaskConfigVSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV16DonationMetadataVSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogVSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary0C0O7StreamsO05AppleA6ReportO23FedStatsTransparencyLogOAA14StreamResourceAA9EventTypeAaJP_AA0K4Data
+ _associated conformance 27IntelligencePlatformLibrary0C0O7StreamsO22RegionalSafetyAnalysisO11DisablementOAA14StreamResourceAA9EventTypeAaJP_AA0I4Data
+ _associated conformance 27IntelligencePlatformLibrary0C0O7StreamsO22RegionalSafetyAnalysisO11EligibilityOAA14StreamResourceAA9EventTypeAaJP_AA0I4Data
+ _associated conformance 27IntelligencePlatformLibrary0C0O7StreamsO22RegionalSafetyAnalysisO15GuardrailResultOAA14StreamResourceAA9EventTypeAaJP_AA0J4Data
+ _associated conformance 27IntelligencePlatformLibrary0C0O7StreamsO22RegionalSafetyAnalysisO17LiteViolationDataOAA14StreamResourceAA9EventTypeAaJP_AA0kJ0
+ _associated conformance 27IntelligencePlatformLibrary0C0O7StreamsO22RegionalSafetyAnalysisO9KeywordIDOAA14StreamResourceAA9EventTypeAaJP_AA0J4Data
+ _associated conformance 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV12InstanceTypeOSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV12InstanceTypeOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV12InstanceTypeOs25LosslessStringConvertibleAAs06CustomlM0
+ _associated conformance 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV17ViolationCategoryOSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV17ViolationCategoryOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV17ViolationCategoryOs25LosslessStringConvertibleAAs06CustomlM0
+ _associated conformance 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDVSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary33RegionalSafetyAnalysisDisablementVSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary33RegionalSafetyAnalysisEligibilityVSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV12InstanceTypeOSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV12InstanceTypeOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV12InstanceTypeOs25LosslessStringConvertibleAAs06CustomlM0
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV15JudgementSourceOSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV15JudgementSourceOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV15JudgementSourceOs25LosslessStringConvertibleAAs06CustomlM0
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV5ErrorOSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV5ErrorOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV5ErrorOs25LosslessStringConvertibleAAs06CustomkL0
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV8SeverityOSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV8SeverityOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV8SeverityOs25LosslessStringConvertibleAAs06CustomkL0
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV9SensitiveOSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV9SensitiveOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV9SensitiveOs25LosslessStringConvertibleAAs06CustomkL0
+ _associated conformance 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultVSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary39RegionalSafetyAnalysisLiteViolationDataV0gH8CategoryOSHAASQ
+ _associated conformance 27IntelligencePlatformLibrary39RegionalSafetyAnalysisLiteViolationDataV0gH8CategoryOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 27IntelligencePlatformLibrary39RegionalSafetyAnalysisLiteViolationDataV0gH8CategoryOs25LosslessStringConvertibleAAs06CustomlM0
+ _associated conformance 27IntelligencePlatformLibrary39RegionalSafetyAnalysisLiteViolationDataVSHAASQ
+ _objc_msgSend$captureIntervalEnd
+ _objc_msgSend$captureIntervalStart
+ _objc_msgSend$configurationForSet_SiriConversationRecap
+ _objc_msgSend$hasIsSaved
+ _objc_msgSend$inferredLocationTags
+ _objc_msgSend$initWithKind:title:summary:transcriptsText:inferredLocationTags:captureIntervalStart:captureIntervalEnd:isSaved:error:
+ _objc_msgSend$initWithSourceItemIdentifier:sourceBundleIdentifier:createdDate:modifiedDate:cacheContentHash:error:
+ _objc_msgSend$isSaved
+ _objc_msgSend$syncPolicyForSet_SiriConversationRecap
+ _objc_msgSend$transcriptsText
+ _symbolic Say_____G 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV12InstanceTypeO
+ _symbolic Say_____G 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV17ViolationCategoryO
+ _symbolic Say_____G 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV12InstanceTypeO
+ _symbolic Say_____G 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV15JudgementSourceO
+ _symbolic Say_____G 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV5ErrorO
+ _symbolic Say_____G 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV8SeverityO
+ _symbolic Say_____G 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV9SensitiveO
+ _symbolic Say_____G 27IntelligencePlatformLibrary39RegionalSafetyAnalysisLiteViolationDataV0gH8CategoryO
+ _symbolic _____ 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV
+ _symbolic _____ 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV10TaskConfigV
+ _symbolic _____ 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV10TaskConfigV02DpK0V
+ _symbolic _____ 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV10TaskConfigV8FeaturesV
+ _symbolic _____ 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV16DonationMetadataV
+ _symbolic _____ 27IntelligencePlatformLibrary0C0O7StreamsO05AppleA6ReportO
+ _symbolic _____ 27IntelligencePlatformLibrary0C0O7StreamsO05AppleA6ReportO23FedStatsTransparencyLogO
+ _symbolic _____ 27IntelligencePlatformLibrary0C0O7StreamsO22RegionalSafetyAnalysisO
+ _symbolic _____ 27IntelligencePlatformLibrary0C0O7StreamsO22RegionalSafetyAnalysisO11DisablementO
+ _symbolic _____ 27IntelligencePlatformLibrary0C0O7StreamsO22RegionalSafetyAnalysisO11EligibilityO
+ _symbolic _____ 27IntelligencePlatformLibrary0C0O7StreamsO22RegionalSafetyAnalysisO15GuardrailResultO
+ _symbolic _____ 27IntelligencePlatformLibrary0C0O7StreamsO22RegionalSafetyAnalysisO17LiteViolationDataO
+ _symbolic _____ 27IntelligencePlatformLibrary0C0O7StreamsO22RegionalSafetyAnalysisO9KeywordIDO
+ _symbolic _____ 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV
+ _symbolic _____ 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV12InstanceTypeO
+ _symbolic _____ 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV17ViolationCategoryO
+ _symbolic _____ 27IntelligencePlatformLibrary33RegionalSafetyAnalysisDisablementV
+ _symbolic _____ 27IntelligencePlatformLibrary33RegionalSafetyAnalysisEligibilityV
+ _symbolic _____ 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV
+ _symbolic _____ 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV12InstanceTypeO
+ _symbolic _____ 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV15JudgementSourceO
+ _symbolic _____ 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV5ErrorO
+ _symbolic _____ 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV8SeverityO
+ _symbolic _____ 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV9SensitiveO
+ _symbolic _____ 27IntelligencePlatformLibrary39RegionalSafetyAnalysisLiteViolationDataV
+ _symbolic _____ 27IntelligencePlatformLibrary39RegionalSafetyAnalysisLiteViolationDataV0gH8CategoryO
+ _symbolic _____Sg 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV10TaskConfigV
+ _symbolic _____Sg 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV10TaskConfigV02DpK0V
+ _symbolic _____Sg 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV10TaskConfigV8FeaturesV
+ _symbolic _____Sg 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV16DonationMetadataV
+ _symbolic _____Sg 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV12InstanceTypeO
+ _symbolic _____Sg 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV17ViolationCategoryO
+ _symbolic _____Sg 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV12InstanceTypeO
+ _symbolic _____Sg 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV15JudgementSourceO
+ _symbolic _____Sg 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV5ErrorO
+ _symbolic _____Sg 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV8SeverityO
+ _symbolic _____Sg 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV9SensitiveO
+ _symbolic _____Sg 27IntelligencePlatformLibrary39RegionalSafetyAnalysisLiteViolationDataV0gH8CategoryO
+ _symbolic _____y_____G 27IntelligencePlatformLibrary12EventWrapperC AA05AppleA29ReportFedStatsTransparencyLogV
+ _symbolic _____y_____G 27IntelligencePlatformLibrary12EventWrapperC AA31RegionalSafetyAnalysisKeywordIDV
+ _symbolic _____y_____G 27IntelligencePlatformLibrary12EventWrapperC AA33RegionalSafetyAnalysisDisablementV
+ _symbolic _____y_____G 27IntelligencePlatformLibrary12EventWrapperC AA33RegionalSafetyAnalysisEligibilityV
+ _symbolic _____y_____G 27IntelligencePlatformLibrary12EventWrapperC AA37RegionalSafetyAnalysisGuardrailResultV
+ _symbolic _____y_____G 27IntelligencePlatformLibrary12EventWrapperC AA39RegionalSafetyAnalysisLiteViolationDataV
+ _symbolic _____y_____G 27IntelligencePlatformLibrary25ProtobufMessageSerializerV AA05AppleA29ReportFedStatsTransparencyLogV
+ _symbolic _____y_____G 27IntelligencePlatformLibrary25ProtobufMessageSerializerV AA31RegionalSafetyAnalysisKeywordIDV
+ _symbolic _____y_____G 27IntelligencePlatformLibrary25ProtobufMessageSerializerV AA33RegionalSafetyAnalysisDisablementV
+ _symbolic _____y_____G 27IntelligencePlatformLibrary25ProtobufMessageSerializerV AA33RegionalSafetyAnalysisEligibilityV
+ _symbolic _____y_____G 27IntelligencePlatformLibrary25ProtobufMessageSerializerV AA37RegionalSafetyAnalysisGuardrailResultV
+ _symbolic _____y_____G 27IntelligencePlatformLibrary25ProtobufMessageSerializerV AA39RegionalSafetyAnalysisLiteViolationDataV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV12InstanceTypeO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 27IntelligencePlatformLibrary31RegionalSafetyAnalysisKeywordIDV17ViolationCategoryO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV12InstanceTypeO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV15JudgementSourceO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV5ErrorO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV8SeverityO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 27IntelligencePlatformLibrary37RegionalSafetyAnalysisGuardrailResultV9SensitiveO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 27IntelligencePlatformLibrary39RegionalSafetyAnalysisLiteViolationDataV0jK8CategoryO
+ _type_layout_string 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV10TaskConfigV
+ _type_layout_string 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV10TaskConfigV02DpK0V
+ _type_layout_string 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV10TaskConfigV8FeaturesV
+ _type_layout_string 27IntelligencePlatformLibrary05AppleA29ReportFedStatsTransparencyLogV16DonationMetadataV
- GCC_except_table7600
- GCC_except_table8195
- _CCHealthKitSampleTypeFromString.sortedEnums
- _OUTLINED_FUNCTION_468
- _OUTLINED_FUNCTION_506
- _OUTLINED_FUNCTION_806
- _OUTLINED_FUNCTION_807
- ___swift_memcpy130_8
- ___swift_memcpy661_8
CStrings:
+ "3AA4400B-F6AD-4F0B-A6FB-129D7E85ABE8"
+ "3BCF8011-790C-49A1-BD4A-816DE43E9E1A"
+ "58C4A87F-BA2F-485F-B51E-FEF9C2383E2F"
+ "68BF406C-C913-4A9E-9672-FB8BF50B2B9C"
+ "6B998066-E2F5-41E4-AE10-8493A83A2CF3"
+ "AnnxModuleRunFailed"
+ "AnnxModuleSetupFailed"
+ "AppleIntelligenceReport.FedStatsTransparencyLog"
+ "AppleIntelligenceReportFedStatsTransparencyLog"
+ "AppleIntelligenceReportFedStatsTransparencyLog.DonationMetadata"
+ "AppleIntelligenceReportFedStatsTransparencyLog.TaskConfig"
+ "AppleIntelligenceReportFedStatsTransparencyLog.TaskConfig.DpConfig"
+ "AppleIntelligenceReportFedStatsTransparencyLog.TaskConfig.Features"
+ "B32A35C0-AAF4-4976-A684-2030A38AD613"
+ "BE29F413-3A3E-4466-9660-1E73A1E56F22"
+ "C9D79ADE-C17E-448D-B52D-6EA4D0112194"
+ "CacheAssetsFailed"
+ "CheckOTAPackageHeaderError"
+ "CheckOTAPackageProcessError"
+ "ChildNodesIsMiss"
+ "E"
+ "ErrorAnnxModuleRunFailed"
+ "ErrorAnnxModuleSetupFailed"
+ "ErrorCacheAssetsFailed"
+ "ErrorCheckOTAIOError"
+ "ErrorCheckOTAPackageHeaderError"
+ "ErrorCheckOTAPackageProcessError"
+ "ErrorChildNodesIsMiss"
+ "ErrorDetectFailed"
+ "ErrorFolderIsNotExist"
+ "ErrorFolderNotExist"
+ "ErrorImageInferFailed"
+ "ErrorIsNotOperatorNode"
+ "ErrorIsUnknownNode"
+ "ErrorKfcModuleSetupFailed"
+ "ErrorKfcSearchFailed"
+ "ErrorLoadAssetsCacheFailed"
+ "ErrorMergeFilesFailed"
+ "ErrorModuleIsNotFound"
+ "ErrorModulePreUpdateFailed"
+ "ErrorNoConfigForScence"
+ "ErrorNoZipperFound"
+ "ErrorNodeTypeIsException"
+ "ErrorOcrInferFailed"
+ "ErrorOcrServiceIsNil"
+ "ErrorOperatorIsNotRegister"
+ "ErrorParseResourcesError"
+ "ErrorParseSolutionError"
+ "ErrorParseSolutionPatchError"
+ "ErrorPreparseAssetsFailed"
+ "ErrorQuakeModuleRunFailed"
+ "ErrorQuakeModuleSetupFailed"
+ "ErrorRemoveNeedDeletedFilesFailed"
+ "ErrorResourceFileIsNotExist"
+ "ErrorResourceFileNotExist"
+ "ErrorRestoreBackupWorkFailed"
+ "ErrorRootFolderNotExist"
+ "ErrorScenceCodeNotSupport"
+ "ErrorServiceIsLoading"
+ "ErrorServiceNotInit"
+ "ErrorServiceParamsIsMissed"
+ "ErrorSolutionIsNotMatchSampleType"
+ "ErrorSolutionNotMatchSampleType"
+ "ErrorStartAbilityServiceError"
+ "ErrorTextInferFailed"
+ "ErrorTextSpliteResultIsEmpty"
+ "ErrorUnknown"
+ "FolderIsNotExist"
+ "ImageInferFailed"
+ "IsMainlandChina"
+ "IsNotOperatorNode"
+ "JudgementSourceEmbedding"
+ "JudgementSourceKeyword"
+ "JudgementSourceModel"
+ "JudgementSourceUnknown"
+ "KfcModuleSetupFailed"
+ "Library.Streams.AppleIntelligenceReport.FedStatsTransparencyLog"
+ "Library.Streams.RegionalSafetyAnalysis.Disablement"
+ "Library.Streams.RegionalSafetyAnalysis.Eligibility"
+ "Library.Streams.RegionalSafetyAnalysis.GuardrailResult"
+ "Library.Streams.RegionalSafetyAnalysis.KeywordID"
+ "Library.Streams.RegionalSafetyAnalysis.LiteViolationData"
+ "LiteViolationCategoryA1"
+ "LiteViolationCategoryA2"
+ "LiteViolationCategoryA3"
+ "LiteViolationCategoryA4"
+ "LiteViolationCategoryA5"
+ "LiteViolationCategoryUnknown"
+ "LoadAssetsCacheFailed"
+ "MarkedSensitiveAndRedirected"
+ "MarkedSensitiveAndRedirectedAndGotResponse"
+ "MergeFilesFailed"
+ "ModuleIsNotFound"
+ "ModulePreUpdateFailed"
+ "NoConfigForScence"
+ "NodeTypeIsException"
+ "OperatorIsNotRegister"
+ "ParseResourcesError"
+ "ParseSolutionError"
+ "ParseSolutionPatchError"
+ "PreparseAssetsFailed"
+ "QuakeModuleRunFailed"
+ "QuakeModuleSetupFailed"
+ "Qwen"
+ "RegionMainlandChina"
+ "RegionalSafetyAnalysis.Disablement"
+ "RegionalSafetyAnalysis.Eligibility"
+ "RegionalSafetyAnalysis.GuardrailResult"
+ "RegionalSafetyAnalysis.KeywordID"
+ "RegionalSafetyAnalysis.LiteViolationData"
+ "RegionalSafetyAnalysisDisablement"
+ "RegionalSafetyAnalysisEligibility"
+ "RegionalSafetyAnalysisGuardrailResult"
+ "RegionalSafetyAnalysisKeywordID"
+ "RegionalSafetyAnalysisLiteViolationData"
+ "RemoveNeedDeletedFilesFailed"
+ "ResourceFileIsNotExist"
+ "ResourceFileNotExist"
+ "RestoreBackupWorkFailed"
+ "RootFolderNotExist"
+ "Safari.AutoDarkMode"
+ "ScenceCodeNotSupport"
+ "SensitiveMarkedSensitive"
+ "SensitiveMarkedSensitiveAndRedirected"
+ "SensitiveMarkedSensitiveAndRedirectedAndGotResponse"
+ "SensitiveUnknown"
+ "ServiceIsLoading"
+ "ServiceParamsIsMissed"
+ "SeverityHigh"
+ "SeverityLow"
+ "SeverityNone"
+ "SeverityUnknown"
+ "Siri.ConversationRecap"
+ "SiriConversationRecap"
+ "SiriConversationRecapContent_captureIntervalEnd"
+ "SiriConversationRecapContent_captureIntervalStart"
+ "SiriConversationRecapContent_inferredLocationTags"
+ "SiriConversationRecapContent_isSaved"
+ "SiriConversationRecapContent_kind"
+ "SiriConversationRecapContent_summary"
+ "SiriConversationRecapContent_title"
+ "SiriConversationRecapContent_transcriptsText"
+ "SiriConversationRecapMetaContent_cacheContentHash"
+ "SiriConversationRecapMetaContent_createdDate"
+ "SiriConversationRecapMetaContent_modifiedDate"
+ "SiriConversationRecapMetaContent_sourceBundleIdentifier"
+ "SiriConversationRecapMetaContent_sourceItemIdentifier"
+ "SolutionIsNotMatchSampleType"
+ "SolutionNotMatchSampleType"
+ "StartAbilityServiceError"
+ "TextSpliteResultIsEmpty"
+ "ViolationCategoryA1"
+ "ViolationCategoryA1a"
+ "ViolationCategoryA1b"
+ "ViolationCategoryA1c"
+ "ViolationCategoryA1d"
+ "ViolationCategoryA1e"
+ "ViolationCategoryA1f"
+ "ViolationCategoryA1g"
+ "ViolationCategoryA1h"
+ "ViolationCategoryA2"
+ "ViolationCategoryA2a"
+ "ViolationCategoryA2b"
+ "ViolationCategoryA2c"
+ "ViolationCategoryA2d"
+ "ViolationCategoryA2e"
+ "ViolationCategoryA2f"
+ "ViolationCategoryA2g"
+ "ViolationCategoryA2h"
+ "ViolationCategoryA2i"
+ "ViolationCategoryA3"
+ "ViolationCategoryA3a"
+ "ViolationCategoryA3b"
+ "ViolationCategoryA3c"
+ "ViolationCategoryA3d"
+ "ViolationCategoryA3e"
+ "ViolationCategoryA4"
+ "ViolationCategoryA4a"
+ "ViolationCategoryA4b"
+ "ViolationCategoryA4c"
+ "ViolationCategoryA4d"
+ "ViolationCategoryA4e"
+ "ViolationCategoryA4f"
+ "ViolationCategoryA4g"
+ "ViolationCategoryA5"
+ "ViolationCategoryA5a"
+ "ViolationCategoryA5b"
+ "ViolationCategoryUnknown"
+ "captureIntervalEnd"
+ "captureIntervalStart"
+ "didTriggerAutomaticDisablement"
+ "differentialPrivacyConfig"
+ "dimension"
+ "features"
+ "inferredLocationTags"
+ "isAppleIntelligenceEligible"
+ "isAppleIntelligenceToggledOn"
+ "isOnboarded3rdParty"
+ "isSaved"
+ "isStaleSafetyData"
+ "judgementSource"
+ "keywordIdentifier"
+ "kvCacheHasDuplicateId"
+ "kvCacheInputMismatch"
+ "liteViolationCategory"
+ "localEpsilon"
+ "minBatchSize"
+ "ohttp"
+ "privateAccessToken"
+ "safetyDataVersion"
+ "sensitivity"
+ "severity"
+ "targetCentralDelta"
+ "targetCentralEpsilon"
+ "taskConfig"
+ "taskExpiration"
+ "transcriptsText"
```
