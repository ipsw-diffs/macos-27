## ParavirtualizedANE

> `/System/Library/PrivateFrameworks/ParavirtualizedANE.framework/Versions/A/ParavirtualizedANE`

```diff

-382.102.2.0.0
-  __TEXT.__text: 0x22204
-  __TEXT.__objc_methlist: 0x814
-  __TEXT.__const: 0x188
-  __TEXT.__cstring: 0xf6e
-  __TEXT.__oslogstring: 0x65cf
-  __TEXT.__gcc_except_tab: 0x3dd4
-  __TEXT.__unwind_info: 0xb98
+382.202.0.0.0
+  __TEXT.__text: 0x257cc
+  __TEXT.__objc_methlist: 0x978
+  __TEXT.__const: 0x198
+  __TEXT.__cstring: 0x107b
+  __TEXT.__oslogstring: 0x6d7f
+  __TEXT.__gcc_except_tab: 0x4528
+  __TEXT.__unwind_info: 0xc80
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x20
-  __DATA_CONST.__objc_classlist: 0x18
+  __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa78
-  __DATA_CONST.__objc_superrefs: 0x10
-  __DATA_CONST.__got: 0x1c0
-  __AUTH_CONST.__const: 0x130
-  __AUTH_CONST.__cfstring: 0x11c0
-  __AUTH_CONST.__objc_const: 0x570
+  __DATA_CONST.__objc_selrefs: 0xbd8
+  __DATA_CONST.__objc_superrefs: 0x18
+  __DATA_CONST.__got: 0x1e8
+  __AUTH_CONST.__const: 0x1b0
+  __AUTH_CONST.__cfstring: 0x1320
+  __AUTH_CONST.__objc_const: 0x810
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x18
-  __AUTH_CONST.__auth_got: 0x258
-  __AUTH.__objc_data: 0xf0
-  __DATA.__objc_ivar: 0x4c
-  __DATA.__bss: 0x60
+  __AUTH_CONST.__auth_got: 0x280
+  __AUTH.__objc_data: 0x140
+  __DATA.__objc_ivar: 0x74
+  __DATA.__bss: 0x70
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 549
-  Symbols:   862
-  CStrings:  562
+  Functions: 602
+  Symbols:   973
+  CStrings:  608
 
Symbols:
+ +[_ANEVirtualPlatformClient assetUUIDFromLookupKey:]
+ +[_ANEVirtualPlatformClient prepareSharedCacheDirectory:]
+ -[_ANEAssetStagingState .cxx_destruct]
+ -[_ANEAssetStagingState contentDigest]
+ -[_ANEAssetStagingState emptyDirectories]
+ -[_ANEAssetStagingState expectedFileSizes]
+ -[_ANEAssetStagingState fileDigests]
+ -[_ANEAssetStagingState init]
+ -[_ANEAssetStagingState isComplete]
+ -[_ANEAssetStagingState publishedDirectory]
+ -[_ANEAssetStagingState receivedByteCounts]
+ -[_ANEAssetStagingState setEmptyDirectories:]
+ -[_ANEAssetStagingState setExpectedFileSizes:]
+ -[_ANEAssetStagingState setFileDigests:]
+ -[_ANEAssetStagingState setPublishedDirectory:]
+ -[_ANEAssetStagingState setReceivedByteCounts:]
+ -[_ANEAssetStagingState setStagingDirectory:]
+ -[_ANEAssetStagingState stagingDirectory]
+ -[_ANEVirtualPlatformClient assetStagingStates]
+ -[_ANEVirtualPlatformClient beginStagedTransferWithManifest:publishedDirectory:uuid:]
+ -[_ANEVirtualPlatformClient createAssetOnHost:dataSize:dataIOSID:filePathComplete:directoryPath:hashingInto:]
+ -[_ANEVirtualPlatformClient createModelFileAtPath:fromIOSID:withDataLength:shouldAppend:hashingInto:]
+ -[_ANEVirtualPlatformClient lastSharedAssetSweepDate]
+ -[_ANEVirtualPlatformClient maintenanceQueue]
+ -[_ANEVirtualPlatformClient publishStagedAssetForUUID:]
+ -[_ANEVirtualPlatformClient publishedDirectoryForLookupKey:]
+ -[_ANEVirtualPlatformClient setAssetStagingStates:]
+ -[_ANEVirtualPlatformClient setLastSharedAssetSweepDate:]
+ -[_ANEVirtualPlatformClient setSharedANEBaseDirectory:]
+ -[_ANEVirtualPlatformClient setSharedCachePath:]
+ -[_ANEVirtualPlatformClient sharedANEBaseDirectory]
+ GCC_except_table1
+ GCC_except_table100
+ GCC_except_table108
+ GCC_except_table109
+ GCC_except_table114
+ GCC_except_table115
+ GCC_except_table131
+ GCC_except_table132
+ GCC_except_table133
+ GCC_except_table134
+ GCC_except_table135
+ GCC_except_table138
+ GCC_except_table139
+ GCC_except_table140
+ GCC_except_table141
+ GCC_except_table144
+ GCC_except_table148
+ GCC_except_table149
+ GCC_except_table150
+ GCC_except_table151
+ GCC_except_table153
+ GCC_except_table157
+ GCC_except_table158
+ GCC_except_table180
+ GCC_except_table181
+ GCC_except_table182
+ GCC_except_table187
+ GCC_except_table189
+ GCC_except_table190
+ GCC_except_table191
+ GCC_except_table195
+ GCC_except_table196
+ GCC_except_table197
+ GCC_except_table2
+ GCC_except_table21
+ GCC_except_table3
+ GCC_except_table48
+ GCC_except_table61
+ GCC_except_table62
+ GCC_except_table68
+ GCC_except_table74
+ GCC_except_table75
+ GCC_except_table79
+ GCC_except_table94
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_CLASS_$__ANEAssetStagingState
+ _OBJC_CLASS_$__ANEAtomicPublish
+ _OBJC_CLASS_$__ANECacheMaintenance
+ _OBJC_CLASS_$__ANEIncrementalHash
+ _OBJC_IVAR_$__ANEAssetStagingState._emptyDirectories
+ _OBJC_IVAR_$__ANEAssetStagingState._expectedFileSizes
+ _OBJC_IVAR_$__ANEAssetStagingState._fileDigests
+ _OBJC_IVAR_$__ANEAssetStagingState._publishedDirectory
+ _OBJC_IVAR_$__ANEAssetStagingState._receivedByteCounts
+ _OBJC_IVAR_$__ANEAssetStagingState._stagingDirectory
+ _OBJC_IVAR_$__ANEVirtualPlatformClient._assetStagingStates
+ _OBJC_IVAR_$__ANEVirtualPlatformClient._lastSharedAssetSweepDate
+ _OBJC_IVAR_$__ANEVirtualPlatformClient._maintenanceQueue
+ _OBJC_IVAR_$__ANEVirtualPlatformClient._sharedANEBaseDirectory
+ _OBJC_METACLASS_$__ANEAssetStagingState
+ _OUTLINED_FUNCTION_34
+ _OUTLINED_FUNCTION_35
+ __OBJC_$_INSTANCE_METHODS__ANEAssetStagingState
+ __OBJC_$_INSTANCE_VARIABLES__ANEAssetStagingState
+ __OBJC_$_PROP_LIST__ANEAssetStagingState
+ __OBJC_CLASS_RO_$__ANEAssetStagingState
+ __OBJC_METACLASS_RO_$__ANEAssetStagingState
+ __ZZ52-[_ANEVirtualPlatformClient assetReceivedFromGuest:]E15manifestClasses
+ __ZZ52-[_ANEVirtualPlatformClient assetReceivedFromGuest:]E9onceToken
+ ___48-[_ANEVirtualPlatformClient setSharedCachePath:]_block_invoke
+ ___52-[_ANEVirtualPlatformClient assetReceivedFromGuest:]_block_invoke
+ ___55-[_ANEVirtualPlatformClient publishStagedAssetForUUID:]_block_invoke
+ ___85-[_ANEVirtualPlatformClient beginStagedTransferWithManifest:publishedDirectory:uuid:]_block_invoke
+ ___block_descriptor_40_ea8_32s_e5_v8?0l
+ ___block_descriptor_56_ea8_32s40s_e5_v8?0l
+ ___copy_helper_block_ea8_32s40s
+ ___destroy_helper_block_ea8_32s40s
+ _dispatch_async
+ _dispatch_queue_attr_make_with_qos_class
+ _objc_getProperty
+ _objc_msgSend$array
+ _objc_msgSend$assetDigestForFileDigests:emptyDirectories:
+ _objc_msgSend$assetUUIDFromLookupKey:
+ _objc_msgSend$beginStagedTransferWithManifest:publishedDirectory:uuid:
+ _objc_msgSend$characterAtIndex:
+ _objc_msgSend$contentDigest
+ _objc_msgSend$createAssetOnHost:dataSize:dataIOSID:filePathComplete:directoryPath:hashingInto:
+ _objc_msgSend$createModelFileAtPath:fromIOSID:withDataLength:shouldAppend:hashingInto:
+ _objc_msgSend$dictionary
+ _objc_msgSend$emptyDirectories
+ _objc_msgSend$expectedFileSizes
+ _objc_msgSend$fileDigests
+ _objc_msgSend$hexString
+ _objc_msgSend$isAbsolutePath
+ _objc_msgSend$isComplete
+ _objc_msgSend$isEqualToNumber:
+ _objc_msgSend$isPath:safelyWithinDirectory:
+ _objc_msgSend$loadedStateForSharedUnload
+ _objc_msgSend$prepareSharedCacheDirectory:
+ _objc_msgSend$processIdentifier
+ _objc_msgSend$processInfo
+ _objc_msgSend$publishDirectory:to:label:
+ _objc_msgSend$publishStagedAssetForUUID:
+ _objc_msgSend$publishedDirectory
+ _objc_msgSend$publishedDirectoryForLookupKey:
+ _objc_msgSend$rangeOfCharacterFromSet:
+ _objc_msgSend$receivedByteCounts
+ _objc_msgSend$removeEntriesAtPath:notAccessedFor:
+ _objc_msgSend$reset
+ _objc_msgSend$restoreLoadedState:
+ _objc_msgSend$setPublishedDirectory:
+ _objc_msgSend$setStagingDirectory:
+ _objc_msgSend$sharedANEBaseDirectory
+ _objc_msgSend$stagingDirectory
+ _objc_msgSend$stringByStandardizingPath
+ _objc_msgSend$substringToIndex:
+ _objc_msgSend$timeIntervalSinceDate:
+ _objc_msgSend$updateAccessTimeForPath:
+ _objc_msgSend$updateWithData:
+ _objc_setProperty_atomic_copy
+ _objc_setProperty_nonatomic_copy
- -[_ANEVirtualPlatformClient createAssetOnHost:dataSize:dataIOSID:filePathComplete:directoryPath:]
- -[_ANEVirtualPlatformClient createModelFileAtPath:fromIOSID:withDataLength:shouldAppend:]
- GCC_except_table102
- GCC_except_table103
- GCC_except_table107
- GCC_except_table112
- GCC_except_table12
- GCC_except_table122
- GCC_except_table128
- GCC_except_table13
- GCC_except_table15
- GCC_except_table16
- GCC_except_table160
- GCC_except_table161
- GCC_except_table162
- GCC_except_table20
- GCC_except_table22
- GCC_except_table23
- GCC_except_table25
- GCC_except_table29
- GCC_except_table30
- GCC_except_table31
- GCC_except_table32
- GCC_except_table35
- GCC_except_table38
- GCC_except_table39
- GCC_except_table40
- GCC_except_table42
- GCC_except_table5
- GCC_except_table8
- GCC_except_table85
- GCC_except_table91
- GCC_except_table95
- GCC_except_table98
- GCC_except_table99
- _objc_msgSend$createAssetOnHost:dataSize:dataIOSID:filePathComplete:directoryPath:
- _objc_msgSend$createModelFileAtPath:fromIOSID:withDataLength:shouldAppend:
- _objc_msgSend$mapper
- _objc_msgSend$program
- _objc_msgSend$setMapper:
- _objc_msgSend$setProgram:
CStrings:
+ "%@ (no host model for programHandle=%llu)"
+ "%@/%@-%@/"
+ "%@: ANEVirtualPlatformClient evaluate model does not exist programHandle=%llu!"
+ "%@: ANEVirtualPlatformClient shared cache disabled"
+ "%@: ANEVirtualPlatformClient shared cache enabled, filepath:%@"
+ "%@: Cannot create shared cache directory %@: %@"
+ "%@: Cannot write to shared cache directory %@: %@"
+ "%@: ERROR : BAD_ARGUMENT : manifest, publishedDirectory or uuid missing!"
+ "%@: ERROR asset manifest is missing a UUID!"
+ "%@: ERROR could not clear stale staging directory=%@ with error=%@"
+ "%@: ERROR could not create empty directory=%@ with error=%@"
+ "%@: ERROR could not create parent directory=%@ with error=%@"
+ "%@: ERROR could not create staging directory=%@ with error=%@"
+ "%@: ERROR could not derive a content digest for uuid=%@, not publishing"
+ "%@: ERROR could not resolve a parent directory for uuid=%@ (shared=%d)"
+ "%@: ERROR failed to get asset manifest from IOSurface with ID %u!"
+ "%@: ERROR failed to handle asset manifest, unable to generate a destination baseDirectory from inDictionary data!"
+ "%@: ERROR malformed published directory=%@ for uuid=%@"
+ "%@: ERROR manifest entryCount=%lu out of range"
+ "%@: ERROR manifest is missing its file or directory list"
+ "%@: ERROR no staged transfer for uuid=%@"
+ "%@: ERROR staged chunk for uuid=%@ has no file name!"
+ "%@: ERROR staged chunk for uuid=%@ names path=%@ which the manifest did not declare!"
+ "%@: ERROR staged chunk path=%@ escapes staging directory=%@"
+ "%@: Opened staged transfer uuid=%@ fileCount=%lu staging=%@"
+ "%@: Published asset uuid=%@ at %@"
+ "%@: could not remove staging directory=%@ with error=%@"
+ "%@: dropping stale mapping for uuid=%@ (path=%@ is gone)"
+ "%@: found published asset for key=%@ at %@"
+ "%@: leaving shared asset in place for uuid=%@ at %@"
+ "%@: manifest empty directory escapes staging directory: %@"
+ "%@: manifest empty directory rejected: %@"
+ "%@: manifest file rejected: %@"
+ "%@: no asset held for uuid=%@; caller will transfer it"
+ "%@: shared cache path rejected (not absolute): %@"
+ "%@: shared cache stays disabled, %@ is not usable"
+ ".staging"
+ ".write-probe.%d"
+ "0123456789ABCDEFabcdef"
+ "assetContentDigest"
+ "assetManifestEmptyDirectories"
+ "assetManifestFiles"
+ "com.apple.appleneuralengine"
+ "com.apple.avp.ane.maintenance"
+ "inputIndexArrayCount"
+ "outputIndexArrayCount"
```
