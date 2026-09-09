## ANEStorageMaintainer

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANEStorageMaintainer.xpc/Contents/MacOS/ANEStorageMaintainer`

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
-  __TEXT.__text: 0x8fe4
+  __TEXT.__text: 0x8e94
   __TEXT.__auth_stubs: 0x3f0
   __TEXT.__objc_stubs: 0xfa0
   __TEXT.__objc_methlist: 0x3e4

   __TEXT.__objc_methtype: 0x276
   __TEXT.__gcc_except_tab: 0x154
   __TEXT.__cstring: 0x1ee
-  __TEXT.__unwind_info: 0x1a0
+  __TEXT.__unwind_info: 0x220
   __DATA_CONST.__const: 0x130
   __DATA_CONST.__cfstring: 0x320
   __DATA_CONST.__objc_classlist: 0x20
Functions:
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
~ _OUTLINED_FUNCTION_6 : 24 -> 12
~ +[_ANEStorageMaintainer initialize] : 68 -> 56
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
```
