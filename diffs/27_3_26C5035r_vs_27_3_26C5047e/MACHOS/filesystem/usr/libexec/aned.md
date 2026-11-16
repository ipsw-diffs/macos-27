## aned

> `/usr/libexec/aned`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`

```diff

-382.102.2.0.0
-  __TEXT.__text: 0x7d71c
-  __TEXT.__auth_stubs: 0xe00
-  __TEXT.__objc_stubs: 0x3460
-  __TEXT.__objc_methlist: 0x1184
+382.202.0.0.0
+  __TEXT.__text: 0x80d34
+  __TEXT.__auth_stubs: 0xdf0
+  __TEXT.__objc_stubs: 0x39c0
+  __TEXT.__objc_methlist: 0x1334
   __TEXT.__const: 0x60fc
-  __TEXT.__gcc_except_tab: 0x5e10
-  __TEXT.__cstring: 0x5cd4
-  __TEXT.__oslogstring: 0x6d2a
-  __TEXT.__objc_classname: 0x247
-  __TEXT.__objc_methname: 0x3e92
-  __TEXT.__objc_methtype: 0xeaf
-  __TEXT.__unwind_info: 0x2b68
-  __DATA_CONST.__const: 0x2bd8
-  __DATA_CONST.__cfstring: 0xaa0
-  __DATA_CONST.__objc_classlist: 0x90
+  __TEXT.__gcc_except_tab: 0x6048
+  __TEXT.__cstring: 0x5d1c
+  __TEXT.__oslogstring: 0x723a
+  __TEXT.__objc_classname: 0x28c
+  __TEXT.__objc_methname: 0x43e0
+  __TEXT.__objc_methtype: 0xf31
+  __TEXT.__unwind_info: 0x2c40
+  __DATA_CONST.__const: 0x2c98
+  __DATA_CONST.__cfstring: 0xb00
+  __DATA_CONST.__objc_classlist: 0xa8
   __DATA_CONST.__objc_protolist: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x60
-  __DATA_CONST.__objc_arraydata: 0x8
-  __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA_CONST.__objc_intobj: 0x18
-  __DATA_CONST.__auth_got: 0x718
-  __DATA_CONST.__got: 0x3b8
+  __DATA_CONST.__objc_superrefs: 0x68
+  __DATA_CONST.__objc_arraydata: 0x10
+  __DATA_CONST.__objc_arrayobj: 0x30
+  __DATA_CONST.__objc_intobj: 0x30
+  __DATA_CONST.__auth_got: 0x710
+  __DATA_CONST.__got: 0x3f8
   __DATA_CONST.__auth_ptr: 0x20
-  __DATA.__objc_const: 0x1c98
-  __DATA.__objc_selrefs: 0xfc0
-  __DATA.__objc_ivar: 0xe4
-  __DATA.__objc_data: 0x5a0
+  __DATA.__objc_const: 0x1f48
+  __DATA.__objc_selrefs: 0x1120
+  __DATA.__objc_ivar: 0xf8
+  __DATA.__objc_data: 0x690
   __DATA.__data: 0x490
-  __DATA.__bss: 0xa0
+  __DATA.__bss: 0xd8
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2795
-  Symbols:   3998
-  CStrings:  1757
+  Functions: 2850
+  Symbols:   4131
+  CStrings:  1841
 
Symbols:
+ +[_ANECompileContentKey contentKeyForInputPath:options:modelType:]
+ +[_ANECompileContentKey inputsDigestForPath:]
+ +[_ANECompileContentKey inputsFingerprintForPath:]
+ +[_ANECompileContentKey optionsDigestForOptions:]
+ +[_ANECompileContentKey optionsToSkipList]
+ +[_ANEEquivalenceIndex churnFaultThreshold]
+ +[_ANEEquivalenceIndex serialQueue]
+ -[_ANEEquivalenceIndex .cxx_destruct]
+ -[_ANEEquivalenceIndex _loadLocked]
+ -[_ANEEquivalenceIndex _resolutionForEntry:contentKey:index:dirty:]
+ -[_ANEEquivalenceIndex _safeLeafPathForName:]
+ -[_ANEEquivalenceIndex _saveLocked:]
+ -[_ANEEquivalenceIndex evictContentKey:]
+ -[_ANEEquivalenceIndex initWithModelIdentityDirectory:]
+ -[_ANEEquivalenceIndex recordContentKey:leafName:]
+ -[_ANEEquivalenceIndex resolveContentKey:]
+ -[_ANEEquivalenceResolution .cxx_destruct]
+ -[_ANEEquivalenceResolution dupCount]
+ -[_ANEEquivalenceResolution leafName]
+ -[_ANEEquivalenceResolution leafPath]
+ -[_ANEEquivalenceResolution setDupCount:]
+ -[_ANEEquivalenceResolution setLeafName:]
+ -[_ANEEquivalenceResolution setLeafPath:]
+ -[_ANEModelCacheManager _contentKeyForModel:options:fingerprint:]
+ -[_ANEModelCacheManager _indexForModel:csIdentity:options:]
+ -[_ANEModelCacheManager effectiveBundleIDForModel:bundleID:]
+ -[_ANEModelCacheManager equivalentCompiledModelForModel:csIdentity:options:modelAttributes:contentKey:inputsFingerprint:]
+ -[_ANEModelCacheManager evictEquivalenceForModel:csIdentity:options:contentKey:]
+ -[_ANEModelCacheManager modelIdentityDirectoryForModel:bundleID:useSourceURL:]
+ -[_ANEModelCacheManager recordEquivalenceForModel:csIdentity:options:contentKey:inputsFingerprint:leafPath:]
+ -[_ANEProgramForLoad createSymbolMappingForProgram:error:]
+ -[_ANEProgramForLoad createSymbolMappingWithError:]
+ -[_ANEServer cacheEquivalenceApplicableForOptions:]
+ -[_ANEServer cacheEquivalenceEnabled]
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/AppleNeuralEngine/install/TempContent/Objects/AppleNeuralEngine.build/aned.build/Objects-normal/arm64e/_ANECompileContentKey.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/AppleNeuralEngine/install/TempContent/Objects/AppleNeuralEngine.build/aned.build/Objects-normal/arm64e/_ANEEquivalenceIndex.o
+ GCC_except_table59
+ GCC_except_table70
+ _ANECompileContentKey.m
+ _ANEEquivalenceIndex.m
+ _NSFileType
+ _NSFileTypeRegular
+ _OBJC_CLASS_$_NSJSONSerialization
+ _OBJC_CLASS_$__ANECacheMaintenance
+ _OBJC_CLASS_$__ANECompileContentKey
+ _OBJC_CLASS_$__ANEEquivalenceIndex
+ _OBJC_CLASS_$__ANEEquivalenceResolution
+ _OBJC_IVAR_$__ANEEquivalenceIndex._identityDirURL
+ _OBJC_IVAR_$__ANEEquivalenceIndex._indexPath
+ _OBJC_IVAR_$__ANEEquivalenceResolution._dupCount
+ _OBJC_IVAR_$__ANEEquivalenceResolution._leafName
+ _OBJC_IVAR_$__ANEEquivalenceResolution._leafPath
+ _OBJC_METACLASS_$__ANECompileContentKey
+ _OBJC_METACLASS_$__ANEEquivalenceIndex
+ _OBJC_METACLASS_$__ANEEquivalenceResolution
+ _OUTLINED_FUNCTION_20
+ __OBJC_$_CLASS_METHODS__ANECompileContentKey
+ __OBJC_$_CLASS_METHODS__ANEEquivalenceIndex
+ __OBJC_$_CLASS_PROP_LIST__ANEEquivalenceIndex
+ __OBJC_$_INSTANCE_METHODS__ANEEquivalenceIndex
+ __OBJC_$_INSTANCE_METHODS__ANEEquivalenceResolution
+ __OBJC_$_INSTANCE_VARIABLES__ANEEquivalenceIndex
+ __OBJC_$_INSTANCE_VARIABLES__ANEEquivalenceResolution
+ __OBJC_$_PROP_LIST__ANEEquivalenceResolution
+ __OBJC_CLASS_RO_$__ANECompileContentKey
+ __OBJC_CLASS_RO_$__ANEEquivalenceIndex
+ __OBJC_CLASS_RO_$__ANEEquivalenceResolution
+ __OBJC_METACLASS_RO_$__ANECompileContentKey
+ __OBJC_METACLASS_RO_$__ANEEquivalenceIndex
+ __OBJC_METACLASS_RO_$__ANEEquivalenceResolution
+ __Z23ANEStringFromFixedFieldPKcm
+ __ZZ37-[_ANEServer cacheEquivalenceEnabled]E7enabled
+ __ZZ37-[_ANEServer cacheEquivalenceEnabled]E9onceToken
+ ___35+[_ANEEquivalenceIndex serialQueue]_block_invoke
+ ___37-[_ANEServer cacheEquivalenceEnabled]_block_invoke
+ ___40-[_ANEEquivalenceIndex evictContentKey:]_block_invoke
+ ___42+[_ANECompileContentKey optionsToSkipList]_block_invoke
+ ___42-[_ANEEquivalenceIndex resolveContentKey:]_block_invoke
+ ___50-[_ANEEquivalenceIndex recordContentKey:leafName:]_block_invoke
+ ___78-[_ANEModelCacheManager modelIdentityDirectoryForModel:bundleID:useSourceURL:]_block_invoke
+ ___block_descriptor_40_e8_32r_e31_v24?0"NSString"8"NSString"16l
+ ___block_descriptor_64_e8_32s40s48s56r_e5_v8?0l
+ ___copy_helper_block_e8_32r
+ ___copy_helper_block_e8_32s40s48s56r
+ ___destroy_helper_block_e8_32r
+ ___destroy_helper_block_e8_32s40s48s56r
+ __saveLocked:.atomicUnsupported
+ _kANEFDisableIOFencesUseSharedEventsKey
+ _kANEFEnableFWToFWSignal
+ _kANEFModelMILValue
+ _lstat
+ _objc_msgSend$_contentKeyForModel:options:fingerprint:
+ _objc_msgSend$_indexForModel:csIdentity:options:
+ _objc_msgSend$_loadLocked
+ _objc_msgSend$_resolutionForEntry:contentKey:index:dirty:
+ _objc_msgSend$_safeLeafPathForName:
+ _objc_msgSend$_saveLocked:
+ _objc_msgSend$accessTimeForPath:
+ _objc_msgSend$cacheEquivalenceApplicableForOptions:
+ _objc_msgSend$cacheEquivalenceEnabled
+ _objc_msgSend$churnFaultThreshold
+ _objc_msgSend$contentKeyForInputPath:options:modelType:
+ _objc_msgSend$createSymbolMappingForProgram:error:
+ _objc_msgSend$createSymbolMappingWithError:
+ _objc_msgSend$dataUsingEncoding:
+ _objc_msgSend$dataWithJSONObject:options:error:
+ _objc_msgSend$dictionaryWithContentsOfFile:
+ _objc_msgSend$disableCacheEquivalenceBootArg
+ _objc_msgSend$dupCount
+ _objc_msgSend$effectiveBundleIDForModel:bundleID:
+ _objc_msgSend$equivalenceIndexName
+ _objc_msgSend$equivalentCompiledModelForModel:csIdentity:options:modelAttributes:contentKey:inputsFingerprint:
+ _objc_msgSend$errorForCode:method:
+ _objc_msgSend$evictContentKey:
+ _objc_msgSend$evictEquivalenceForModel:csIdentity:options:contentKey:
+ _objc_msgSend$hexStringForData:
+ _objc_msgSend$hexStringForFileAtPath:
+ _objc_msgSend$initWithBytes:length:encoding:
+ _objc_msgSend$initWithModelIdentityDirectory:
+ _objc_msgSend$inputsDigestForPath:
+ _objc_msgSend$inputsFingerprintForPath:
+ _objc_msgSend$isValidJSONObject:
+ _objc_msgSend$leafName
+ _objc_msgSend$leafPath
+ _objc_msgSend$modelIdentityDirectoryForModel:bundleID:useSourceURL:
+ _objc_msgSend$optionsDigestForOptions:
+ _objc_msgSend$optionsToSkipList
+ _objc_msgSend$recordContentKey:leafName:
+ _objc_msgSend$recordEquivalenceForModel:csIdentity:options:contentKey:inputsFingerprint:leafPath:
+ _objc_msgSend$resolveContentKey:
+ _objc_msgSend$serialQueue
+ _objc_msgSend$setAccessTime:forPath:
+ _objc_msgSend$setDupCount:
+ _objc_msgSend$setLeafName:
+ _objc_msgSend$setLeafPath:
+ _objc_msgSend$sortedArrayUsingSelector:
+ _objc_msgSend$string
+ _objc_msgSend$updateAccessTimeForPath:
+ _objc_msgSend$writeToURL:options:error:
+ _optionsToSkipList.onceToken
+ _optionsToSkipList.skipList
+ _serialQueue.onceToken
+ _serialQueue.queue
- -[_ANEProgramForLoad createSymbolMappingForProgram:]
- -[_ANEProgramForLoad createSymbolMapping]
- GCC_except_table65
- _getxattr
- _objc_msgSend$createSymbolMapping
- _objc_msgSend$createSymbolMappingForProgram:
- _objc_msgSend$dateWithTimeIntervalSince1970:
- _objc_msgSend$hasSuffix:
- _objc_msgSend$setAccessTime:forModelFilePath:
- _setxattr
CStrings:
+ "%@: FAILED writing %{public}@ : %{public}@"
+ "%@: Model patching is only permitted on internal builds"
+ "%@: atomic write unavailable (%{public}@); writing the index in place from now on. A torn index is tolerable because an unparseable one is read as empty."
+ "%@: compile inputs changed while compiling; not recording leaf=%{public}@"
+ "%@: could not hash %@"
+ "%@: equivalence candidate unmappable: %@"
+ "%@: equivalence record for leaf=%{public}@ : recorded=%d"
+ "%@: identity path traversal rejected: %@"
+ "%@: input path does not exist: %@"
+ "%@: keyed lookup missed; matched programHandle=%llu under %@"
+ "%@: no regular files under %@"
+ "%@: options are not a valid JSON object"
+ "%@: options not canonicalizable: %@"
+ "%@: procedures[%u] claims %u inputs / %u outputs, above the kANEMaxBuffers bound of %u; refusing the descriptor"
+ "%@: refusing the program descriptor: %@"
+ "%@: refusing to record leaf with no binary: %{public}@"
+ "%@: refusing unsafe leafName=%{public}@"
+ "%@: serialise failed for %{public}@ : %{public}@"
+ "%@: skipping compile, equivalent binary already cached: %{public}@"
+ "%@: subpathsOfDirectoryAtPath:%@ failed : err=%@"
+ "."
+ "@24@0:8^@16"
+ "@32@0:8^{ANEProgramInstanceStruct=^v^vQQI^[512c]^Q^{ANEProgramIOInfoStruct}^{ANEProgramIOInfoStruct}I^[512c]^QI^{ANEProgramProcedureStruct}QIQQcQQiC}16^@24"
+ "@40@0:8@16@24^@32"
+ "@48@0:8@16@24@32^B40"
+ "@64@0:8@16@24@32^@40^@48^@56"
+ "B64@0:8@16@24@32@40@48@56"
+ "Recovered compiled model by equivalence: leaf=%{public}@ dups=%lu csIdentity=%{public}@"
+ "T@\"NSString\",C,N,V_leafName"
+ "T@\"NSString\",C,N,V_leafPath"
+ "TQ,N,V_dupCount"
+ "_ANECompileContentKey"
+ "_ANEEquivalenceIndex"
+ "_ANEEquivalenceResolution"
+ "_contentKeyForModel:options:fingerprint:"
+ "_dupCount"
+ "_identityDirURL"
+ "_indexForModel:csIdentity:options:"
+ "_indexPath"
+ "_leafName"
+ "_leafPath"
+ "_loadLocked"
+ "_resolutionForEntry:contentKey:index:dirty:"
+ "_safeLeafPathForName:"
+ "_saveLocked:"
+ "accessTimeForPath:"
+ "cacheEquivalenceApplicableForOptions:"
+ "cacheEquivalenceEnabled"
+ "churnFaultThreshold"
+ "com.apple.ane.aned.equivalenceIndex"
+ "compile-cache equivalence DISABLED by boot-arg %{public}@"
+ "compile-cache key churn: %lu redundant compiles avoided for identity %{public}@ (leaf %{public}@). A client is varying _ANEModel.key for identical compile inputs."
+ "contentKeyForInputPath:options:modelType:"
+ "createSymbolMappingForProgram:error:"
+ "createSymbolMappingWithError:"
+ "dataUsingEncoding:"
+ "dataWithJSONObject:options:error:"
+ "dictionaryWithContentsOfFile:"
+ "disableCacheEquivalenceBootArg"
+ "dupCount"
+ "dups"
+ "effectiveBundleIDForModel:bundleID:"
+ "equivalence index entry rejected: unsafe leaf name %{public}@ in %{public}@"
+ "equivalence leaf %{public}@ has no binary; dropping entry"
+ "equivalenceIndexName"
+ "equivalentCompiledModelForModel:csIdentity:options:modelAttributes:contentKey:inputsFingerprint:"
+ "errorForCode:method:"
+ "evictContentKey:"
+ "evictEquivalenceForModel:csIdentity:options:contentKey:"
+ "hexStringForData:"
+ "hexStringForFileAtPath:"
+ "initWithBytes:length:encoding:"
+ "initWithModelIdentityDirectory:"
+ "inputsDigestForPath:"
+ "inputsFingerprintForPath:"
+ "isValidJSONObject:"
+ "leaf"
+ "leafName"
+ "leafPath"
+ "modelIdentityDirectoryForModel:bundleID:useSourceURL:"
+ "optionsDigestForOptions:"
+ "optionsToSkipList"
+ "recordContentKey:leafName:"
+ "recordEquivalenceForModel:csIdentity:options:contentKey:inputsFingerprint:leafPath:"
+ "resolveContentKey:"
+ "serialQueue"
+ "setAccessTime:forPath:"
+ "setDupCount:"
+ "setLeafName:"
+ "setLeafPath:"
+ "sortedArrayUsingSelector:"
+ "string"
+ "updateAccessTimeForPath:"
+ "v48@0:8@16@24@32@40"
+ "writeToURL:options:error:"
+ "|%@:%llu:%llu:%ld.%09ld:%ld.%09ld"
+ "|%lu:%@=%@"
- "%@: +setAccessTime:forFilePath failed"
- "%@: Skipping update for filePath=%@"
- "%@: filePath=%@"
- "%@: getxattr(%@, %@, %p, %lu) failed  : errno=%d"
- "%@: getxattr(%@, %@, %p, %lu) missing attribute  : errno=%d"
- "%@: setxattr(%@, %@, %p, %lu) failed  : errno=%d"
- "%s"
- "@24@0:8^{ANEProgramInstanceStruct=^v^vQQI^[512c]^Q^{ANEProgramIOInfoStruct}^{ANEProgramIOInfoStruct}I^[512c]^QI^{ANEProgramProcedureStruct}QIQQcQQiC}16"
- "createSymbolMapping"
- "createSymbolMappingForProgram:"
- "dateWithTimeIntervalSince1970:"
- "hasSuffix:"
- "kANEAccessSeconds"
```
