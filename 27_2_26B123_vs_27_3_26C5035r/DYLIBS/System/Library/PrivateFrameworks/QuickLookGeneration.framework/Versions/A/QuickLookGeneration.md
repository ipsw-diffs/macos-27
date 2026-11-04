## QuickLookGeneration

> `/System/Library/PrivateFrameworks/QuickLookGeneration.framework/Versions/A/QuickLookGeneration`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_imageinfo`

```diff

-1114.1.11.0.0
-  __TEXT.__text: 0x448
-  __TEXT.__objc_methlist: 0x17c
-  __TEXT.__const: 0x48
-  __TEXT.__cstring: 0x25
-  __TEXT.__unwind_info: 0x70
+1114.3.2.0.0
+  __TEXT.__text: 0xd240
+  __TEXT.__objc_methlist: 0x244
+  __TEXT.__const: 0x4e4
+  __TEXT.__oslogstring: 0x30e
+  __TEXT.__cstring: 0x2cb
+  __TEXT.__constg_swiftt: 0x11c
+  __TEXT.__swift5_typeref: 0x1de
+  __TEXT.__swift5_fieldmd: 0x15c
+  __TEXT.__swift5_builtin: 0x14
+  __TEXT.__swift5_reflstr: 0x11c
+  __TEXT.__swift5_assocty: 0x48
+  __TEXT.__swift5_proto: 0x28
+  __TEXT.__swift5_types: 0x18
+  __TEXT.__unwind_info: 0x2e8
+  __TEXT.__eh_frame: 0x80
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__objc_classlist: 0x10
+  __DATA_CONST.__const: 0x68
+  __DATA_CONST.__objc_classlist: 0x28
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x110
+  __DATA_CONST.__objc_selrefs: 0x1d8
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x30
-  __AUTH_CONST.__objc_const: 0x2f8
-  __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0xa0
-  __DATA.__data: 0xc0
+  __AUTH_CONST.__const: 0x390
+  __AUTH_CONST.__objc_const: 0x5b8
+  __AUTH_CONST.__auth_got: 0x670
+  __AUTH.__objc_data: 0x2a8
+  __AUTH.__data: 0x50
+  __DATA.__data: 0x2f0
+  __DATA.__bss: 0x510
+  __DATA.__common: 0x20
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /System/Library/PrivateFrameworks/QuickLookSupport.framework/Versions/A/QuickLookSupport
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 6
-  Symbols:   76
-  CStrings:  1
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftIOKit.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswift_StringProcessing.dylib
+  - /usr/lib/swift/libswiftos.dylib
+  Functions: 167
+  Symbols:   277
+  CStrings:  34
 
Symbols:
+ +[QLMarkdownGenerationPreviewProvider fileSizeAtURL:]
+ -[QLMarkdownGenerationPreviewProvider providePreviewForFileRequest:completionHandler:]
+ _NSURLFileSizeKey
+ _NSURLIsRegularFileKey
+ _OBJC_CLASS_$_NSBundle
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSMutableDictionary
+ _OBJC_CLASS_$_NSString
+ _OBJC_CLASS_$_QLMarkdownAssetCollector
+ _OBJC_CLASS_$_QLMarkdownGenerationPreviewProvider
+ _OBJC_CLASS_$_QLMarkdownRenderer
+ _OBJC_CLASS_$_QLPreviewReplyAttachment
+ _OBJC_CLASS_$_UTType
+ _OBJC_METACLASS_$_QLMarkdownAssetCollector
+ _OBJC_METACLASS_$_QLMarkdownGenerationPreviewProvider
+ _OBJC_METACLASS_$_QLMarkdownRenderer
+ _QLMarkdownLog
+ _QLMarkdownLog.log
+ _QLMarkdownLog.once
+ _UTTypeData
+ _UTTypeHTML
+ _UTTypeMarkdown
+ __CLASS_METHODS_QLMarkdownRenderer
+ __DATA_QLMarkdownAssetCollector
+ __DATA_QLMarkdownRenderer
+ __INSTANCE_METHODS_QLMarkdownAssetCollector
+ __INSTANCE_METHODS_QLMarkdownRenderer
+ __IVARS_QLMarkdownAssetCollector
+ __METACLASS_DATA_QLMarkdownAssetCollector
+ __METACLASS_DATA_QLMarkdownRenderer
+ __NSConcreteGlobalBlock
+ __OBJC_$_CLASS_METHODS_QLMarkdownGenerationPreviewProvider
+ __OBJC_$_INSTANCE_METHODS_QLMarkdownGenerationPreviewProvider
+ __OBJC_$_PROP_LIST_QLMarkdownGenerationPreviewProvider
+ __OBJC_CLASS_PROTOCOLS_$_QLMarkdownGenerationPreviewProvider
+ __OBJC_CLASS_RO_$_QLMarkdownGenerationPreviewProvider
+ __OBJC_METACLASS_RO_$_QLMarkdownGenerationPreviewProvider
+ __PROPERTIES_QLMarkdownAssetCollector
+ ___86-[QLMarkdownGenerationPreviewProvider providePreviewForFileRequest:completionHandler:]_block_invoke
+ ___86-[QLMarkdownGenerationPreviewProvider providePreviewForFileRequest:completionHandler:]_block_invoke_2
+ ___QLMarkdownLog_block_invoke
+ ___block_descriptor_32_e5_v8?0l
+ ___block_descriptor_48_e8_32s40s_e33_v32?0"NSString"8"NSData"16^B24l
+ ___block_descriptor_56_e8_32s40s48s_e36_"NSData"24?0"QLPreviewReply"8^16l
+ ___block_literal_global
+ ___chkstk_darwin
+ ___copy_helper_block_e8_32s40s
+ ___copy_helper_block_e8_32s40s48s
+ ___destroy_helper_block_e8_32s40s
+ ___destroy_helper_block_e8_32s40s48s
+ ___swift_allocate_value_buffer
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
+ ___swift_instantiateConcreteTypeFromMangledNameV2
+ ___swift_memcpy1_1
+ ___swift_memcpy56_8
+ ___swift_noop_void_return
+ ___swift_project_value_buffer
+ ___swift_reflection_version
+ __os_log_error_impl
+ __os_log_impl
+ __swiftEmptyArrayStorage
+ __swiftEmptyDictionarySingleton
+ __swiftEmptySetSingleton
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftCoreFoundation_$_QuickLookGeneration
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftDispatch_$_QuickLookGeneration
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftFoundation_$_QuickLookGeneration
+ __swift_FORCE_LOAD_$_swiftIOKit
+ __swift_FORCE_LOAD_$_swiftIOKit_$_QuickLookGeneration
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftObjectiveC_$_QuickLookGeneration
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers_$_QuickLookGeneration
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swiftXPC_$_QuickLookGeneration
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swift_Builtin_float_$_QuickLookGeneration
+ __swift_FORCE_LOAD_$_swiftos
+ __swift_FORCE_LOAD_$_swiftos_$_QuickLookGeneration
+ __swift_stdlib_malloc_size
+ __swift_stdlib_reportUnimplementedInitializer
+ _associated conformance 19QuickLookGeneration24QLMarkdownAssetCollectorC7Refusal33_646C135647F7A30ADE058B8ACABDE237LLOSHAASQ
+ _associated conformance So16NSURLResourceKeyaSHSCSQ
+ _associated conformance So16NSURLResourceKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So16NSURLResourceKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _bzero
+ _dispatch_once
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_allocWithZone
+ _objc_msgSend$HTMLForData:contentType:assets:
+ _objc_msgSend$URLForResource:withExtension:
+ _objc_msgSend$attachments
+ _objc_msgSend$bundleForClass:
+ _objc_msgSend$dataUsingEncoding:
+ _objc_msgSend$dataWithContentsOfURL:options:error:
+ _objc_msgSend$dictionary
+ _objc_msgSend$enumerateKeysAndObjectsUsingBlock:
+ _objc_msgSend$fileSizeAtURL:
+ _objc_msgSend$getResourceValue:forKey:error:
+ _objc_msgSend$initWithData:contentType:
+ _objc_msgSend$initWithDocumentURL:
+ _objc_msgSend$length
+ _objc_msgSend$localizedDescription
+ _objc_msgSend$mimeTypeForIdentifier:
+ _objc_msgSend$setAttachments:
+ _objc_msgSend$setObject:forKeyedSubscript:
+ _objc_msgSend$stringEncodingForData:encodingOptions:convertedString:usedLossyConversion:
+ _objc_msgSend$typeWithMIMEType:
+ _objc_msgSend$unsignedIntegerValue
+ _objc_msgSendSuper2
+ _objc_opt_self
+ _objc_retainAutoreleasedReturnValue
+ _os_log_create
+ _os_log_type_enabled
+ _swift_allocObject
+ _swift_arrayDestroy
+ _swift_arrayInitWithCopy
+ _swift_beginAccess
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_bridgeObjectRetain_n
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initWithCopy
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_deallocPartialClassInstance
+ _swift_deletedMethodError
+ _swift_endAccess
+ _swift_errorRelease
+ _swift_getEnumCaseMultiPayload
+ _swift_getForeignTypeMetadata
+ _swift_getObjCClassFromMetadata
+ _swift_getObjCClassMetadata
+ _swift_getObjectType
+ _swift_getSingletonMetadata
+ _swift_getTypeByMangledNameInContext2
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_getWitnessTable
+ _swift_initStackObject
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_isaMask
+ _swift_once
+ _swift_release
+ _swift_retain
+ _swift_setDeallocating
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_storeEnumTagMultiPayload
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_updateClassMetadata2
+ _symbolic $sSY
+ _symbolic $ss21_ObjectiveCBridgeableP
+ _symbolic SDyS2SG
+ _symbolic SDySS_____G 10Foundation4DataV
+ _symbolic SS
+ _symbolic SSSg
+ _symbolic Si
+ _symbolic Sny_____G 10Foundation16AttributedStringV5IndexV
+ _symbolic So8NSObjectC
+ _symbolic So8NSStringC
+ _symbolic _____ 10Foundation3URLV
+ _symbolic _____ 19QuickLookGeneration14QLMarkdownHTMLO
+ _symbolic _____ 19QuickLookGeneration14QLMarkdownHTMLO11OpenElement33_2C1E9B8AF39B2752D8D834EBF8F0CA91LLV
+ _symbolic _____ 19QuickLookGeneration18QLMarkdownRendererC
+ _symbolic _____ 19QuickLookGeneration24QLMarkdownAssetCollectorC
+ _symbolic _____ 19QuickLookGeneration24QLMarkdownAssetCollectorC7Refusal33_646C135647F7A30ADE058B8ACABDE237LLO
+ _symbolic _____ So16NSURLResourceKeya
+ _symbolic _____5lower_AA5uppert 10Foundation16AttributedStringV5IndexV
+ _symbolic _____Sg 10Foundation13URLComponentsV
+ _symbolic _____Sg 10Foundation18PresentationIntentV
+ _symbolic _____Sg 10Foundation18PresentationIntentV4KindO
+ _symbolic _____Sg 10Foundation3URLV
+ _symbolic _____Sg 10Foundation6LocaleV
+ _symbolic _____Sg 22UniformTypeIdentifiers6UTTypeV
+ _symbolic _____Sg SS10FoundationE8EncodingV
+ _symbolic ___________t 10Foundation3URLV 22UniformTypeIdentifiers6UTTypeV
+ _symbolic _____yS2SG s18_DictionaryStorageC
+ _symbolic _____ySJG s23_ContiguousArrayStorageC
+ _symbolic _____ySSG s11_SetStorageC
+ _symbolic _____ySS_____G s18_DictionaryStorageC 10Foundation4DataV
+ _symbolic _____ySsG 17_StringProcessing5RegexV
+ _symbolic _____ySsG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s11_SetStorageC So16NSURLResourceKeya
+ _symbolic _____y_____G s16IndexingIteratorV 10Foundation16AttributedStringV4RunsV
+ _symbolic _____y_____G s16PartialRangeFromV 10Foundation16AttributedStringV5IndexV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation18PresentationIntentV0F4TypeV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 19QuickLookGeneration14QLMarkdownHTMLO11OpenElement33_2C1E9B8AF39B2752D8D834EBF8F0CA91LLV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So16NSURLResourceKeya
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
+ _symbolic _____y_____G s5SliceV 10Foundation16AttributedStringV13CharacterViewV
+ _symbolic _____y___________t_____G s6ResultOsRi_zRi0_zrlE 10Foundation3URLV 22UniformTypeIdentifiers6UTTypeV 19QuickLookGeneration24QLMarkdownAssetCollectorC7Refusal33_646C135647F7A30ADE058B8ACABDE237LLO
+ _type_layout_string 19QuickLookGeneration14QLMarkdownHTMLO11OpenElement33_2C1E9B8AF39B2752D8D834EBF8F0CA91LLV
+ _type_layout_string So16NSURLResourceKeya
CStrings:
+ " class=\"language-"
+ " style=\"text-align:center\""
+ " style=\"text-align:right\""
+ "/&(?!#?[xX]?(?:[0-9a-fA-F]+|\\w+);)/"
+ "/<(?![a-z\\/?\\$!])/"
+ "<input type=\"checkbox\" disabled"
+ "<pre class=\"file\"><code>"
+ "Markdown"
+ "QLMarkdownTemplate"
+ "QuickLookGeneration.QLMarkdownAssetCollector"
+ "absolute path"
+ "application/octet-stream"
+ "com.apple.quicklook"
+ "empty path"
+ "init()"
+ "markdown grew past its limit while being read (%lu bytes), replying with the file itself"
+ "markdown image refused: %{public}ld bytes exceeds the per-file limit of %{public}ld"
+ "markdown image refused: %{public}s"
+ "markdown image refused: grew past its budget while being read"
+ "markdown image refused: size unavailable"
+ "markdown image refused: unreadable"
+ "markdown image refused: would exceed the total attachment budget"
+ "markdown not rendered (size %{public}@, limit %lu), replying with the file itself"
+ "markdown output exceeded its cap or failed to parse, falling back to plain text"
+ "markdown refused by its limits, falling back to plain text: %{public}ld bytes (limit %{public}ld)"
+ "markdown unreadable: %{public}@"
+ "not a regular file"
+ "not an image type"
+ "path carries a URL scheme"
+ "path could not be percent-decoded"
+ "path escapes the document's directory"
+ "v32@?0@\"NSString\"8@\"NSData\"16^B24"
+ "v8@?0"
```
