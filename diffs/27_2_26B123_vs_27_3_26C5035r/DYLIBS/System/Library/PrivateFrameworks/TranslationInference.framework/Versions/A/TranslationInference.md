## TranslationInference

> `/System/Library/PrivateFrameworks/TranslationInference.framework/Versions/A/TranslationInference`

```diff

-396.0.1.0.0
-  __TEXT.__text: 0x8eed4
-  __TEXT.__const: 0x47a8
-  __TEXT.__swift5_typeref: 0x18ce
-  __TEXT.__constg_swiftt: 0x110c
+397.2.0.0.0
+  __TEXT.__text: 0x8f8d4
+  __TEXT.__const: 0x4828
+  __TEXT.__swift5_typeref: 0x194c
+  __TEXT.__constg_swiftt: 0x1138
   __TEXT.__swift5_builtin: 0x64
-  __TEXT.__swift5_reflstr: 0x15ed
-  __TEXT.__swift5_fieldmd: 0x15d8
+  __TEXT.__swift5_reflstr: 0x168d
+  __TEXT.__swift5_fieldmd: 0x1630
   __TEXT.__swift5_assocty: 0x2e8
-  __TEXT.__oslogstring: 0x115d
-  __TEXT.__cstring: 0x1abe
+  __TEXT.__oslogstring: 0x113d
+  __TEXT.__swift5_capture: 0x304
+  __TEXT.__cstring: 0x1b2e
   __TEXT.__swift5_proto: 0x300
-  __TEXT.__swift5_types: 0x15c
+  __TEXT.__swift5_types: 0x160
   __TEXT.__swift_as_entry: 0xd8
   __TEXT.__swift_as_cont: 0x2e0
-  __TEXT.__swift5_capture: 0x2cc
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x34
   __TEXT.__swift_as_ret: 0x138
-  __TEXT.__unwind_info: 0x2060
-  __TEXT.__eh_frame: 0x4038
+  __TEXT.__unwind_info: 0x2078
+  __TEXT.__eh_frame: 0x4068
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__const: 0xe8
   __DATA_CONST.__objc_classlist: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x170
-  __DATA_CONST.__got: 0x5f0
-  __AUTH_CONST.__const: 0x2ff8
-  __AUTH_CONST.__objc_const: 0xcf0
-  __AUTH_CONST.__auth_got: 0x11c8
-  __AUTH.__data: 0x5c0
-  __DATA.__data: 0x980
+  __DATA_CONST.__objc_selrefs: 0x160
+  __DATA_CONST.__got: 0x5d8
+  __AUTH_CONST.__const: 0x3110
+  __AUTH_CONST.__objc_const: 0xd10
+  __AUTH_CONST.__auth_got: 0x11c0
+  __AUTH.__data: 0x5d0
+  __DATA.__data: 0x9c8
   __DATA.__bss: 0x54a0
   __DATA.__common: 0x68
   __DATA_DIRTY.__objc_data: 0xa0
   __DATA_DIRTY.__data: 0x1590
-  __DATA_DIRTY.__common: 0xe0
+  __DATA_DIRTY.__common: 0xd8
   __DATA_DIRTY.__bss: 0x380
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/NaturalLanguage.framework/Versions/A/NaturalLanguage
-  - /System/Library/PrivateFrameworks/AppleNeuralEngine.framework/Versions/A/AppleNeuralEngine
   - /System/Library/PrivateFrameworks/EmbeddedAcousticRecognition.framework/Versions/A/EmbeddedAcousticRecognition
   - /System/Library/PrivateFrameworks/FeatureFlags.framework/Versions/A/FeatureFlags
   - /System/Library/PrivateFrameworks/GenerativeFunctions.framework/Versions/A/GenerativeFunctions

   - /System/Library/PrivateFrameworks/SpeechEngine.framework/Versions/A/SpeechEngine
   - /System/Library/PrivateFrameworks/TokenGeneration.framework/Versions/A/TokenGeneration
   - /System/Library/PrivateFrameworks/TokenGenerationCore.framework/Versions/A/TokenGenerationCore
+  - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftAVFoundation.dylib

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2034
-  Symbols:   832
-  CStrings:  280
+  Functions: 2053
+  Symbols:   844
+  CStrings:  283
 
Symbols:
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_deviceSupportsInstructionFollowingPruningModels
+ _get_enum_tag_for_layout_string 12ModelCatalog21AssetBackedLLMAdapter_pSg
+ _symbolic SDyS2SGSg
+ _symbolic SbSg
+ _symbolic _____ 16GenerativeModels0aB12AvailabilityV10ParametersV
+ _symbolic _____ 20TranslationInference21ResolvedSessionConfigV13ModelMetadata33_CACE240C616D3418214710E0A9699679LLV
+ _symbolic _____Sg 10Foundation13URLComponentsV
+ _symbolic _____Sg 20TranslationInference21ResolvedSessionConfigV13ModelMetadata33_CACE240C616D3418214710E0A9699679LLV
+ _symbolic _____ySDySS_____G_____G s13ManagedBufferCsRi__rlE 20TranslationInference30DefaultGMSAvailabilityProviderC So16os_unfair_lock_sV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 20TranslationInference30DefaultGMSAvailabilityProviderC
+ _symbolic _____ySbG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySb_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____y______pG s23_ContiguousArrayStorageC 12ModelCatalog21AssetBackedLLMAdapterP
+ _type_layout_string 20TranslationInference21ResolvedSessionConfigV13ModelMetadata33_CACE240C616D3418214710E0A9699679LLV
- _OBJC_CLASS_$__ANEDeviceInfo
- _objc_msgSend$aneSubType
- _objc_msgSend$hasANE
CStrings:
+ "Bundle %{public}s has no LLM.Model resource; client metadata unavailable"
+ "Bundle %{public}s not found; model metadata unavailable"
+ "Early Return - No Sentences"
+ "Failed to resolve bundle %{public}s for model metadata: %{public}@"
+ "SpeechToSpeechPrepareModelPromptPrefixMarker"
+ "SpeechToSpeechSkipIFPHardwareCheck"
+ "no_translatable_text"
- "Bundle %{public}s has no LLM.Model resource; uses_completion_prompt defaults to false"
- "Bundle %{public}s not found; uses_completion_prompt defaults to false"
- "Failed to resolve bundle %{public}s for uses_completion_prompt: %{public}@"
- "SpeechToSpeechSkipANEVersionCheck"
```
