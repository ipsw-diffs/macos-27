## AppleNeuralEngine

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/Versions/A/AppleNeuralEngine`

```diff

-382.102.2.0.0
-  __TEXT.__text: 0x5f62c
-  __TEXT.__objc_methlist: 0x2c54
-  __TEXT.__const: 0x2c0
-  __TEXT.__oslogstring: 0xbcba
-  __TEXT.__cstring: 0x3ade
-  __TEXT.__gcc_except_tab: 0x6c2c
+382.202.0.0.0
+  __TEXT.__text: 0x6485c
+  __TEXT.__objc_methlist: 0x2ecc
+  __TEXT.__const: 0x2d8
+  __TEXT.__oslogstring: 0xc95e
+  __TEXT.__cstring: 0x3d84
+  __TEXT.__gcc_except_tab: 0x7260
   __TEXT.__ustring: 0xb76
-  __TEXT.__unwind_info: 0x1e20
+  __TEXT.__unwind_info: 0x1fa0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2b0
-  __DATA_CONST.__objc_classlist: 0x138
+  __DATA_CONST.__const: 0x300
+  __DATA_CONST.__objc_classlist: 0x158
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x1ab0
+  __DATA_CONST.__objc_selrefs: 0x1bc0
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0xd8
+  __DATA_CONST.__objc_superrefs: 0xe0
   __DATA_CONST.__objc_arraydata: 0x128
-  __DATA_CONST.__got: 0x308
-  __AUTH_CONST.__const: 0xe10
-  __AUTH_CONST.__cfstring: 0x50c0
-  __AUTH_CONST.__objc_const: 0x3d88
+  __DATA_CONST.__got: 0x320
+  __AUTH_CONST.__const: 0xe30
+  __AUTH_CONST.__cfstring: 0x5380
+  __AUTH_CONST.__objc_const: 0x41d0
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__objc_arrayobj: 0x78
-  __AUTH_CONST.__auth_got: 0x5b8
-  __AUTH.__objc_data: 0x190
-  __DATA.__objc_ivar: 0x23c
+  __AUTH_CONST.__auth_got: 0x608
+  __AUTH.__objc_data: 0x2d0
+  __DATA.__objc_ivar: 0x268
   __DATA.__data: 0x728
   __DATA.__bss: 0x1a8
   __DATA_DIRTY.__objc_data: 0xaa0

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsandbox.1.dylib
-  Functions: 1810
-  Symbols:   2983
-  CStrings:  1499
+  Functions: 1904
+  Symbols:   3121
+  CStrings:  1577
 
Symbols:
+ +[_ANEAtomicPublish publishDirectory:to:label:]
+ +[_ANEAtomicPublish publishDirectory:to:label:renameExcl:rename:]
+ +[_ANECacheMaintenance accessTimeForPath:]
+ +[_ANECacheMaintenance isPath:safelyWithinDirectory:]
+ +[_ANECacheMaintenance removeEntriesAtPath:notAccessedFor:]
+ +[_ANECacheMaintenance setAccessTime:forPath:]
+ +[_ANECacheMaintenance updateAccessTimeForPath:]
+ +[_ANEDeviceInfo hostBuildVersionStr]
+ +[_ANEDeviceInfo negotiatedCapabilityMask]
+ +[_ANEDeviceInfo negotiatedDataInterfaceVersion]
+ +[_ANEHashEncoding assetDigestForFileDigests:emptyDirectories:]
+ +[_ANEStrings disableCacheEquivalenceBootArg]
+ +[_ANEStrings equivalenceIndexName]
+ +[_ANEVirtualClient fingerprintForFilesAtPaths:]
+ +[_ANEVirtualClient hostFileNameForWeightFilePath:]
+ +[_ANEVirtualClient scratchPadPath:fittingLength:]
+ -[_ANEIncrementalHash .cxx_destruct]
+ -[_ANEIncrementalHash hexString]
+ -[_ANEIncrementalHash init]
+ -[_ANEIncrementalHash reset]
+ -[_ANEIncrementalHash updateWithBytes:length:]
+ -[_ANEIncrementalHash updateWithData:]
+ -[_ANEModel loadedStateForSharedUnload]
+ -[_ANEModel restoreLoadedState:]
+ -[_ANEModelLoadedState .cxx_destruct]
+ -[_ANEModelLoadedState intermediateBufferHandle]
+ -[_ANEModelLoadedState mapper]
+ -[_ANEModelLoadedState modelAttributes]
+ -[_ANEModelLoadedState numInputs]
+ -[_ANEModelLoadedState numOutputs]
+ -[_ANEModelLoadedState programHandle]
+ -[_ANEModelLoadedState program]
+ -[_ANEModelLoadedState queueDepth]
+ -[_ANEModelLoadedState setIntermediateBufferHandle:]
+ -[_ANEModelLoadedState setMapper:]
+ -[_ANEModelLoadedState setModelAttributes:]
+ -[_ANEModelLoadedState setNumInputs:]
+ -[_ANEModelLoadedState setNumOutputs:]
+ -[_ANEModelLoadedState setProgram:]
+ -[_ANEModelLoadedState setProgramHandle:]
+ -[_ANEModelLoadedState setQueueDepth:]
+ -[_ANEModelLoadedState setState:]
+ -[_ANEModelLoadedState state]
+ -[_ANEProgramForEvaluation validateRequest:model:method:error:]
+ -[_ANEVirtualClient assetLookupKeyForFilePaths:relativePaths:emptyDirectories:withUUID:]
+ -[_ANEVirtualClient collectAssetsAtPath:modelType:fileAbsolutePaths:fileRelativePaths:fileSizes:emptyDirectories:shareable:]
+ -[_ANEVirtualClient isSharedAssetCacheEnabled]
+ -[_ANEVirtualClient transferAssetManifestToHost:fileSizes:emptyDirectories:withUUID:]
+ -[_ANEVirtualClient transferAssetsToHostAtPath:withUUID:modelType:didTransfer:]
+ -[_ANEVirtualClient transferAssetsToHostForModel:assetDirectory:options:didTransfer:]
+ GCC_except_table107
+ GCC_except_table108
+ GCC_except_table112
+ GCC_except_table115
+ GCC_except_table116
+ GCC_except_table117
+ GCC_except_table127
+ GCC_except_table132
+ GCC_except_table133
+ GCC_except_table157
+ GCC_except_table159
+ GCC_except_table160
+ GCC_except_table161
+ GCC_except_table162
+ GCC_except_table163
+ GCC_except_table180
+ GCC_except_table181
+ GCC_except_table182
+ GCC_except_table184
+ GCC_except_table185
+ GCC_except_table186
+ GCC_except_table187
+ GCC_except_table188
+ GCC_except_table191
+ GCC_except_table192
+ GCC_except_table200
+ GCC_except_table207
+ GCC_except_table211
+ GCC_except_table212
+ GCC_except_table213
+ GCC_except_table221
+ GCC_except_table44
+ GCC_except_table45
+ GCC_except_table47
+ GCC_except_table52
+ GCC_except_table56
+ GCC_except_table57
+ GCC_except_table69
+ GCC_except_table76
+ GCC_except_table79
+ GCC_except_table83
+ GCC_except_table85
+ _ANEStandardizedPath
+ _CFDictionaryGetTypeID
+ _CFErrorCopyDescription
+ _OBJC_CLASS_$__ANEAtomicPublish
+ _OBJC_CLASS_$__ANECacheMaintenance
+ _OBJC_CLASS_$__ANEIncrementalHash
+ _OBJC_CLASS_$__ANEModelLoadedState
+ _OBJC_IVAR_$__ANEIncrementalHash._ctx
+ _OBJC_IVAR_$__ANEIncrementalHash._finalizedHexString
+ _OBJC_IVAR_$__ANEModelLoadedState._intermediateBufferHandle
+ _OBJC_IVAR_$__ANEModelLoadedState._mapper
+ _OBJC_IVAR_$__ANEModelLoadedState._modelAttributes
+ _OBJC_IVAR_$__ANEModelLoadedState._numInputs
+ _OBJC_IVAR_$__ANEModelLoadedState._numOutputs
+ _OBJC_IVAR_$__ANEModelLoadedState._program
+ _OBJC_IVAR_$__ANEModelLoadedState._programHandle
+ _OBJC_IVAR_$__ANEModelLoadedState._queueDepth
+ _OBJC_IVAR_$__ANEModelLoadedState._state
+ _OBJC_METACLASS_$__ANEAtomicPublish
+ _OBJC_METACLASS_$__ANECacheMaintenance
+ _OBJC_METACLASS_$__ANEIncrementalHash
+ _OBJC_METACLASS_$__ANEModelLoadedState
+ _OUTLINED_FUNCTION_40
+ __OBJC_$_CLASS_METHODS__ANEAtomicPublish
+ __OBJC_$_CLASS_METHODS__ANECacheMaintenance
+ __OBJC_$_INSTANCE_METHODS__ANEIncrementalHash
+ __OBJC_$_INSTANCE_METHODS__ANEModelLoadedState
+ __OBJC_$_INSTANCE_VARIABLES__ANEIncrementalHash
+ __OBJC_$_INSTANCE_VARIABLES__ANEModelLoadedState
+ __OBJC_$_PROP_LIST__ANEModelLoadedState
+ __OBJC_CLASS_RO_$__ANEAtomicPublish
+ __OBJC_CLASS_RO_$__ANECacheMaintenance
+ __OBJC_CLASS_RO_$__ANEIncrementalHash
+ __OBJC_CLASS_RO_$__ANEModelLoadedState
+ __OBJC_METACLASS_RO_$__ANEAtomicPublish
+ __OBJC_METACLASS_RO_$__ANECacheMaintenance
+ __OBJC_METACLASS_RO_$__ANEIncrementalHash
+ __OBJC_METACLASS_RO_$__ANEModelLoadedState
+ __ZL18copyBoundedCStringPcmP8NSString
+ __ZZ64+[_ANEVirtualClient createCFDictionaryFromIOSurface:dataLength:]E17kBinaryPlistMagic
+ ___124-[_ANEVirtualClient collectAssetsAtPath:modelType:fileAbsolutePaths:fileRelativePaths:fileSizes:emptyDirectories:shareable:]_block_invoke
+ ___61+[_ANEVirtualClient updateError:errorLength:errorCode:error:]_block_invoke
+ ___63+[_ANEHashEncoding assetDigestForFileDigests:emptyDirectories:]_block_invoke
+ ___85-[_ANEVirtualClient transferAssetManifestToHost:fileSizes:emptyDirectories:withUUID:]_block_invoke
+ ___block_descriptor_32_e31_q24?0"NSString"8"NSString"16l
+ ___block_descriptor_40_e28_"NSString"16?0"NSString"8l
+ ___block_descriptor_56_ea8_32s_e28_"NSString"16?0"NSString"8l
+ ___block_descriptor_64_ea8_32s40bs48bs_e18_B16?0"NSString"8l
+ ___block_descriptor_64_ea8_32s40bs48r56w_e33_v24?0"IOSurfaceSharedEvent"8Q16l
+ ___block_descriptor_88_ea8_32s40s48s56s64bs_e18_B16?0"NSString"8l
+ ___block_descriptor_92_ea8_32s40s48s56s64s72r80r_e5_v8?0l
+ ___copy_helper_block_ea8_32s40b48b
+ ___copy_helper_block_ea8_32s40b48r56w
+ ___copy_helper_block_ea8_32s40s48s56s64b
+ ___copy_helper_block_ea8_32s40s48s56s64s72r80r
+ ___destroy_helper_block_ea8_32s40s48r56w
+ ___destroy_helper_block_ea8_32s40s48s56s64s
+ ___destroy_helper_block_ea8_32s40s48s56s64s72r80r
+ __os_log_fault_impl
+ _getxattr
+ _kANECacheTrashDirectoryName
+ _objc_copyWeak
+ _objc_destroyWeak
+ _objc_initWeak
+ _objc_loadWeakRetained
+ _objc_msgSend$accessTimeForPath:
+ _objc_msgSend$assetDigestForFileDigests:emptyDirectories:
+ _objc_msgSend$assetLookupKeyForFilePaths:relativePaths:emptyDirectories:withUUID:
+ _objc_msgSend$collectAssetsAtPath:modelType:fileAbsolutePaths:fileRelativePaths:fileSizes:emptyDirectories:shareable:
+ _objc_msgSend$compare:options:
+ _objc_msgSend$dateWithTimeIntervalSince1970:
+ _objc_msgSend$fingerprintForFilesAtPaths:
+ _objc_msgSend$hostBuildVersionStr
+ _objc_msgSend$hostFileNameForWeightFilePath:
+ _objc_msgSend$insertObject:atIndex:
+ _objc_msgSend$isSharedAssetCacheEnabled
+ _objc_msgSend$pathComponents
+ _objc_msgSend$publishDirectory:to:label:renameExcl:rename:
+ _objc_msgSend$removeObject:
+ _objc_msgSend$removeObjectAtIndex:
+ _objc_msgSend$scratchPadPath:fittingLength:
+ _objc_msgSend$setAccessTime:forPath:
+ _objc_msgSend$setSignaledValue:
+ _objc_msgSend$string
+ _objc_msgSend$transferAssetManifestToHost:fileSizes:emptyDirectories:withUUID:
+ _objc_msgSend$transferAssetsToHostAtPath:withUUID:modelType:didTransfer:
+ _objc_msgSend$transferAssetsToHostForModel:assetDirectory:options:didTransfer:
+ _objc_msgSend$updateWithBytes:length:
+ _objc_msgSend$uppercaseString
+ _objc_msgSend$validateRequest:model:method:error:
+ _rename
+ _renamex_np
+ _setxattr
- -[_ANEVirtualClient transferAssetsToHostAtPath:withUUID:modelType:]
- GCC_except_table100
- GCC_except_table101
- GCC_except_table104
- GCC_except_table119
- GCC_except_table120
- GCC_except_table125
- GCC_except_table126
- GCC_except_table129
- GCC_except_table137
- GCC_except_table138
- GCC_except_table139
- GCC_except_table143
- GCC_except_table146
- GCC_except_table147
- GCC_except_table148
- GCC_except_table149
- GCC_except_table156
- GCC_except_table173
- GCC_except_table175
- GCC_except_table177
- GCC_except_table178
- GCC_except_table196
- GCC_except_table204
- GCC_except_table54
- GCC_except_table58
- GCC_except_table65
- GCC_except_table67
- GCC_except_table72
- GCC_except_table73
- GCC_except_table77
- GCC_except_table93
- GCC_except_table94
- GCC_except_table99
- ___75-[_ANEVirtualClient transferAssetsToHostAtPathUnlocked:withUUID:modelType:]_block_invoke_2
- ___block_descriptor_48_ea8_32s_e28_"NSString"16?0"NSString"8l
- ___block_descriptor_56_ea8_32s40s48bs_e33_v24?0"IOSurfaceSharedEvent"8Q16l
- ___block_descriptor_72_ea8_32s40s48bs56bs_e18_B16?0"NSString"8l
- ___block_descriptor_72_ea8_32s40s48bs56r_e18_B16?0"NSString"8l
- ___block_descriptor_84_ea8_32s40s48s56s64s72r_e5_v8?0l
- ___copy_helper_block_ea8_32s40s48b
- ___copy_helper_block_ea8_32s40s48b56b
- ___copy_helper_block_ea8_32s40s48b56r
- ___copy_helper_block_ea8_32s40s48s56s64s72r
- ___destroy_helper_block_ea8_32s40s48s56s
- ___destroy_helper_block_ea8_32s40s48s56s64s72r
- _objc_msgSend$transferAssetsToHostAtPath:withUUID:modelType:
CStrings:
+ "\n"
+ "!2"
+ "%@ (enqueue failed, ret=0x%x)"
+ "%@ (evaluate failed, ret=0x%x)"
+ "%@ (inputIndexArray[%u]=%u out of range, numInputs=%u)"
+ "%@ (outputIndexArray[%u]=%u out of range, numOutputs=%u)"
+ "%@ (request failed validation)"
+ "%@-%@"
+ "%@: BEGIN assetExistsOnHost lookupKey=%@"
+ "%@: ERROR : BAD_ARGUMENT : manifest has no entries!"
+ "%@: ERROR : BAD_ARGUMENT : relativeFilePaths.count=%lu does not match fileSizes.count=%lu"
+ "%@: ERROR : BAD_ARGUMENT : weightFilePath is nil or empty!"
+ "%@: ERROR Failed to call assetExistsOnHost, could not write lookup key to input buffer"
+ "%@: ERROR Failed to collect asset, could not get attributes for path=%@ with error=%@"
+ "%@: ERROR asset at path=%@ changed during transfer"
+ "%@: ERROR asset file at path=%@ has no unique name under %@; asset will not be shared"
+ "%@: ERROR asset has %lu entries, exceeding the manifest limit of %u"
+ "%@: ERROR bad arguments for label=%@"
+ "%@: ERROR could not derive host file name from path=%@!"
+ "%@: ERROR could not get complete name of .asset directory in path=%@!"
+ "%@: ERROR failed to copy the asset manifest to an IOSurface"
+ "%@: ERROR failed to transfer asset manifest to host! Could not get csIdentity"
+ "%@: ERROR failed to transfer asset manifest to host! Could not populate UUID"
+ "%@: ERROR failed to transfer asset manifest, host reported an error"
+ "%@: ERROR failed to transferAssetsForModel, could not collect directory at path=%@"
+ "%@: ERROR failed to transferAssetsForModel, could not collect file at path=%@"
+ "%@: ERROR failed to transferAssetsForModel, could not transfer asset manifest for path=%@"
+ "%@: ERROR failed to transferAssetsForModel, no assets found at path=%@"
+ "%@: ERROR loadModel failed, could not transfer assets to host model.modelURL.path=%@ modelFileParentDirectory=%@"
+ "%@: ERROR loadModelNewInstance failed, could not derive host file name for path=%@!"
+ "%@: ERROR loadModelNewInstance failed, could not transfer asset manifest"
+ "%@: ERROR rename() fallback failed for label=%@ with errno=%d (%s)"
+ "%@: ERROR renamex_np failed for label=%@ with errno=%d (%s)"
+ "%@: ERROR symlinks inside model assets are not supported: %@"
+ "%@: ERROR: inputPath '%@' is not under parent directory '%@'; asset will not be shared"
+ "%@: For procedure=%u weight=%u weight file already collected at path=%@"
+ "%@: RENAME_EXCL unsupported on this volume, falling back to rename() for label=%@"
+ "%@: Skipping update for path=%@"
+ "%@: Transferring asset manifest with fileCount=%lu emptyDirectoryCount=%lu uuid=%@"
+ "%@: Transferring weight file with size=%@ as name=%@ at path=%@"
+ "%@: asset at path=%@ cannot be named file by file; skipping the shared cache, sending privately"
+ "%@: asset at path=%@ changed while hashing; not trusting key=%@, sending"
+ "%@: asset has %lu files, %lu empty dirs, key=%@-%@"
+ "%@: asset label=%@ already published, discarding staged copy"
+ "%@: async submit failed"
+ "%@: async submit failed: %@"
+ "%@: could not fold %lu file digests into an asset digest"
+ "%@: could not hash %@"
+ "%@: could not move %@ to trash : errno=%d"
+ "%@: could not remove %@ : error=%@"
+ "%@: could not stat or hash the asset at path=%@; skipping the shared cache, sending privately"
+ "%@: errorIOSurface is nil!"
+ "%@: errorLength is 0!"
+ "%@: evaluating a model with programHandle=0 numInputs=%u numOutputs=%u attrs=%lu -- it looks unloaded"
+ "%@: getxattr(%@, %@) failed : errno=%d"
+ "%@: getxattr(%@, %@) missing attribute"
+ "%@: inputIndexArray[%u]=%u >= model.numInputs=%u"
+ "%@: lookupKey is nil or empty!"
+ "%@: nothing to reclaim at %@ : error=%@"
+ "%@: outputIndexArray[%u]=%u >= model.numOutputs=%u"
+ "%@: removed %lu of %lu entries from %@"
+ "%@: request failed validation r=%@"
+ "%@: scratchPadPath (%zu bytes) exceeds %zu, sending %@"
+ "%@: setxattr(%@, %@) failed : errno=%d"
+ "%@: shared cache hit key=%@, not sending"
+ "%@: shared cache miss key=%@, sending"
+ "%@: staging and published directories are on different file systems, asset transfer cannot be published atomically. staging=%@ published=%@"
+ "%@: uuid, function or scratchPadPath too long for the VM interface: uuid=%@ function=%@ scratchPadPath=%@"
+ "%llu:%lld:%ld.%ld:%ld.%ld|"
+ ".bundle"
+ ".trash"
+ "D"
+ "F"
+ "Program declares more inputs or outputs than the driver supports"
+ "Unable to get validationResult from host"
+ "_ANEIncrementalHash: update after hexString, ignoring %lu bytes"
+ "_ANEVirtualClient createCFDictionaryFromIOSurface : Couldn't create property list object : %{public}@"
+ "_ANEVirtualClient createCFDictionaryFromIOSurface : data (length %llu) is not a binary plist"
+ "_ANEVirtualClient createCFDictionaryFromIOSurface : dataLength %llu exceeds IOSurface alloc size %llu"
+ "_ANEVirtualClient createCFDictionaryFromIOSurface : dataLength is 0"
+ "_ANEVirtualClient createCFDictionaryFromIOSurface : parsed plist is not a dictionary"
+ "ane_disable_cache_equivalence"
+ "assetDigestForFileDigests: no digest for %@"
+ "assetManifestEmptyDirectories"
+ "assetManifestFiles"
+ "could not read error surface"
+ "could not unarchive error string: %@"
+ "equivalence.plist"
+ "error string decoded to nil"
+ "host reported evaluate failure (code %ld): %@"
+ "host wrote no error string"
+ "kANEAccessSeconds"
+ "no error surface provided"
+ "q24@?0@\"NSString\"8@\"NSString\"16"
+ "\xd1"
- "%@: BAD_ARGUMENT errorIOSurface is nil!"
- "%@: BAD_ARGUMENT errorLength is 0!"
- "%@: BEGIN assetExistsOnHost assetTransferUUID=%@"
- "%@: ERROR Failed to call assetExistsOnHost, could not write UUID to input buffer"
- "%@: ERROR failed to transferAssetsForModel, could not transfer directory at path=%@"
- "%@: ERROR failed to transferAssetsForModel, could not transfer file at path=%@"
- "%@: ERROR loadModelNewInstance failed, could not get complete name of .asset directory in path=%@!"
- "%@: ERROR loadModelNewInstance failed, get overWriteFileName from path=%@!"
- "%@: ERROR: inputPath '%@' is not under parent directory '%@'"
- "%@: For procedure=%u transferring weight=%u transferring weight file with size=%@ at path=%@"
- "%@: For procedure=%u weight=%u weight file already transferred at path=%@"
- "%@: Successfully transferred assets at path=%@"
- "%@: assetTransferUUID is nil!"
- "%@: inputIndexArray[%u]=%u >= lModel.numInputs=%u"
- "%@: outputIndexArray[%u]=%u >= lModel.numOutputs=%u"
- "Unable to get validationResult (host might be too old)"
- "_ANEVirtualClient createCFDictionaryFromIOSurface : Couldn't create CFDictionaryRef object"
```
