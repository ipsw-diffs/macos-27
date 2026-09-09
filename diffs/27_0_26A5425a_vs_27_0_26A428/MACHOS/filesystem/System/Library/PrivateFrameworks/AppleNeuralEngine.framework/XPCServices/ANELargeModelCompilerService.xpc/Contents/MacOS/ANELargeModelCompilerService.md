## ANELargeModelCompilerService

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANELargeModelCompilerService.xpc/Contents/MacOS/ANELargeModelCompilerService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 382.15.1.0.0
-  __TEXT.__text: 0x1c49c
+  __TEXT.__text: 0x1bffc
   __TEXT.__auth_stubs: 0x720
   __TEXT.__objc_stubs: 0x22c0
   __TEXT.__objc_methlist: 0x9b4

   __TEXT.__objc_methname: 0x2644
   __TEXT.__objc_methtype: 0x67b
   __TEXT.__gcc_except_tab: 0x12d4
-  __TEXT.__unwind_info: 0x478
+  __TEXT.__unwind_info: 0x5d8
   __DATA_CONST.__const: 0x3b0
   __DATA_CONST.__cfstring: 0x1980
   __DATA_CONST.__objc_classlist: 0x80
Functions:
~ +[_ANEDebugUtils parseDebugString:] : 812 -> 800
~ +[_ANEDebugUtils parseDebugEnvVar] : 136 -> 124
~ +[_ANEDebugUtils applyDebugEnvToOptions:] : 1304 -> 1292
~ ___35+[_ANEModelCacheManager initialize]_block_invoke : 140 -> 128
~ -[_ANEModelCacheManager URLForModel:bundleID:useSourceURL:forAllSegments:aotCacheUrlIdentifier:] : 1664 -> 1652
~ ___96-[_ANEModelCacheManager URLForModel:bundleID:useSourceURL:forAllSegments:aotCacheUrlIdentifier:]_block_invoke : 140 -> 128
~ ___copy_helper_block_e8_32r40r : 80 -> 68
~ ___destroy_helper_block_e8_32r40r : 68 -> 56
~ -[_ANEModelCacheManager getModelBinaryPathFromURLIdentifier:bundleID:] : 360 -> 348
~ -[_ANEModelCacheManager cachedModelPathFor:csIdentity:useSourceURL:] : 236 -> 224
~ -[_ANEModelCacheManager cachedModelAllSegmentsPathFor:csIdentity:] : 180 -> 168
~ -[_ANEModelCacheManager cachedSourceModelStoreNameFor:csIdentity:] : 204 -> 192
~ +[_ANEModelCacheManager cachedSourceModelStoreNameFor:] : 128 -> 116
~ -[_ANEModelCacheManager cachedModelRetainNameFor:csIdentity:] : 204 -> 192
~ +[_ANEModelCacheManager cachedModelRetainNameFor:] : 128 -> 116
~ -[_ANEModelCacheManager URLForBundleID:] : 224 -> 212
~ -[_ANEModelCacheManager filePathForModel:bundleID:] : 284 -> 272
~ -[_ANEModelCacheManager getDiskSpaceItemizedByBundleIDAndPurge:] : 128 -> 116
~ -[_ANEModelCacheManager getDiskSpaceForBundleID:] : 128 -> 116
~ ___68-[_ANEModelCacheManager scheduleMaintenanceWithName:directoryPaths:]_block_invoke : 104 -> 92
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ _OUTLINED_FUNCTION_6 : 24 -> 12
~ +[_ANECVAIRCompiler compileModelAt:csIdentity:plistFilename:optionsFilename:outputURL:saveSourceURL:aotModelBinaryPath:isEncryptedModel:options:ok:error:] : 1856 -> 1844
~ ___destructor_8_s0_s8_s16_s24_s32_s40_s48_s64_s72 : 116 -> 104
~ ___31+[_ANEStorageHelper initialize]_block_invoke : 140 -> 128
~ +[_ANEStorageHelper memoryMapModelAtPath:isPrecompiled:modelAttributes:] : 1636 -> 1624
~ +[_ANEStorageHelper memoryMapWeightAtPath:] : 1472 -> 1460
~ +[_ANEStorageHelper getAccessTimeForFilePath:] : 560 -> 548
~ +[_ANEStorageHelper relevantContainerForPath:] : 588 -> 576
~ +[_ANEStorageHelper sourcePathForModelInStoreAt:] : 1200 -> 1188
~ +[_ANEStorageHelper uniqueFirstLevelSubdirectories:] : 400 -> 388
~ +[_ANEStorageHelper sizeOfDirectoryAtPath:recursionLevel:] : 1452 -> 1440
~ +[_ANEStorageHelper createModelCacheDictionary] : 188 -> 176
~ +[_ANEStorageHelper sizeOfModelCacheAtPath:purgeSubdirectories:] : 1568 -> 1556
~ +[_ANEStorageHelper mergeModelCacheStorageInformation:with:] : 864 -> 852
~ _OUTLINED_FUNCTION_2 : 32 -> 20
~ +[_ANEMILCompiler compileModelAt:modelName:csIdentity:optionsFilename:outputURL:saveSourceURL:aotModelBinaryPath:isEncryptedModel:options:maxModelMemorySize:ok:error:] : 1856 -> 1844
~ +[_ANESandboxingHelper initialize] : 68 -> 56
~ +[_ANESandboxingHelper sandboxExtensionPathForModelURL:] : 240 -> 228
~ +[_ANESandboxingHelper issueSandboxExtensionForPath:error:] : 784 -> 772
~ +[_ANESandboxingHelper issueSandboxExtensionForModel:error:] : 536 -> 524
~ +[_ANEEspressoIRTranslator createErrorForPlan:status:] : 384 -> 372
~ +[_ANEEspressoIRTranslator destroyEspresso:ctx:] : 60 -> 48
~ -[_ANEInMemoryModelCacheManager URLForBundleID:] : 240 -> 228
~ -[_ANEInMemoryModelCacheManager URLForModelHash:bundleID:] : 360 -> 348
~ -[_ANEInMemoryModelCacheManager cachedModelPathMatchingHash:csIdentity:] : 236 -> 224
~ -[_ANEInMemoryModelCacheManager getDiskSpaceItemizedByBundleIDAndPurge:] : 128 -> 116
~ -[_ANEInMemoryModelCacheManager getDiskSpaceForBundleID:] : 128 -> 116
~ ___76-[_ANEInMemoryModelCacheManager scheduleMaintenanceWithName:directoryPaths:]_block_invoke : 104 -> 92
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ -[_ANETask initWithName:period:handler:] : 628 -> 620
~ +[_ANETask taskWithName:period:handler:] : 136 -> 124
~ -[_ANETask .cxx_destruct] : 92 -> 80
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ +[_ANETaskManager unregisterTask:] : 76 -> 64
~ +[_ANEMLIRCompiler compileModelAt:modelName:csIdentity:optionsFilename:outputURL:saveSourceURL:aotModelBinaryPath:isEncryptedModel:options:mpsConstants:externConstants:maxModelMemorySize:ok:error:] : 1932 -> 1920
~ +[_ANEPatchManager initialize] : 112 -> 100
~ +[_ANEPatchManager sharedManager] : 160 -> 148
~ ___33+[_ANEPatchManager sharedManager]_block_invoke : 64 -> 52
~ -[_ANEPatchManager patchedURLForModelURL:csIdentity:configuration:] : 792 -> 780
~ ___copy_helper_block_e8_32s40s48s56s64s72r80r : 120 -> 108
~ ___destroy_helper_block_e8_32s40s48s56s64s72r80r : 108 -> 96
~ -[_ANEPatchManager patchModelAtURL:csIdentity:withConfiguration:usingPatcher:error:] : 292 -> 280
~ -[_ANEPatchManager configurationIdentifierForConfiguration:] : 196 -> 184
~ -[_ANEPatchManager parentHashForModelURL:] : 328 -> 316
~ -[_ANEPatchManager sanitizedOriginalName:] : 456 -> 444
~ -[_ANEPatchManager patchedModelsDirectoryForModelURL:csIdentity:] : 528 -> 516
~ -[_ANEPatchManager modelURLForPatchedURL:] : 548 -> 536
~ -[_ANEPatchManager .cxx_destruct] : 68 -> 56
~ _OUTLINED_FUNCTION_8 : 32 -> 20
~ +[_ANECompiler initialize] : 68 -> 56
~ +[_ANECompiler createNetworkFromModelAtPath:modelFilename:] : 252 -> 240
~ +[_ANECompiler createJITNetworkFromModelAtPath:modelFilename:aotModelAtPath:aotModelFilename:] : 364 -> 352
~ +[_ANECompiler createErrorWithUnderlyingError:] : 612 -> 600
~ +[_ANECompiler compileModelJIT:ok:error:] : 5496 -> 5484
~ ___copy_helper_block_ea8_32r40r : 80 -> 68
~ ___destroy_helper_block_ea8_32r40r : 68 -> 56
~ +[_ANECompiler compileModel:options:ok:error:] : 9388 -> 9376
~ +[_ANECompiler createInMemoryConstants:] : 996 -> 984
~ +[_ANECompiler createExternConstants:] : 1676 -> 1664
~ _OUTLINED_FUNCTION_7 : 12 -> 16
~ _OUTLINED_FUNCTION_8 : 28 -> 12
~ _OUTLINED_FUNCTION_9 : 28 -> 16
~ _OUTLINED_FUNCTION_11 : 28 -> 16
~ _OUTLINED_FUNCTION_12 : 32 -> 20
~ +[_ANECoreMLModelCompiler initialize] : 68 -> 56
~ +[_ANECoreMLModelCompiler createErrorWithString:] : 340 -> 328
~ +[_ANECoreMLModelCompiler pathsForModelURL:] : 536 -> 524
~ +[_ANECoreMLModelCompiler compileModelAt:csIdentity:key:optionsFilename:tempDirectory:outputURL:saveSourceModelPath:aotModelBinaryPath:isEncryptedModel:options:ok:error:] : 3252 -> 3240
~ +[_ANECompilerService initialize] : 104 -> 92
~ __ANECompilerServiceRUsageDict : 1756 -> 1744
~ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96s104b112r : 152 -> 140
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96s104s112r : 136 -> 124
~ ___copy_helper_block_e8_32s40s48s56s64b : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___copy_helper_block_e8_32s40s48b : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
```
