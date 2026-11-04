## TimeMachine

> `/System/Library/PrivateFrameworks/TimeMachine.framework/Versions/A/TimeMachine`

```diff

-2615.1.0.0.0
-  __TEXT.__text: 0xb4b84
-  __TEXT.__objc_methlist: 0x5948
-  __TEXT.__const: 0x3ca6
-  __TEXT.__gcc_except_tab: 0x2000
-  __TEXT.__cstring: 0xc84d
+2616.0.0.0.0
+  __TEXT.__text: 0xb62ec
+  __TEXT.__objc_methlist: 0x5b00
+  __TEXT.__const: 0x3cc6
+  __TEXT.__gcc_except_tab: 0x1f88
+  __TEXT.__cstring: 0xcc8d
   __TEXT.__ustring: 0xa4
   __TEXT.__oslogstring: 0xb
   __TEXT.__dlopen_cstrs: 0xb0

   __TEXT.__swift_as_ret: 0x168
   __TEXT.__swift_as_cont: 0x20c
   __TEXT.__swift5_protos: 0x10
-  __TEXT.__unwind_info: 0x3830
+  __TEXT.__unwind_info: 0x3858
   __TEXT.__eh_frame: 0x3594
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xa68
-  __DATA_CONST.__objc_classlist: 0x298
+  __DATA_CONST.__const: 0xa90
+  __DATA_CONST.__objc_classlist: 0x2a0
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0xe0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3338
+  __DATA_CONST.__objc_selrefs: 0x3440
   __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__objc_superrefs: 0x228
+  __DATA_CONST.__objc_superrefs: 0x230
   __DATA_CONST.__objc_arraydata: 0xf0
-  __DATA_CONST.__got: 0xaf8
-  __AUTH_CONST.__const: 0x5bb8
-  __AUTH_CONST.__cfstring: 0x8600
-  __AUTH_CONST.__objc_const: 0x8bb0
+  __DATA_CONST.__got: 0xb10
+  __AUTH_CONST.__const: 0x5c08
+  __AUTH_CONST.__cfstring: 0x8860
+  __AUTH_CONST.__objc_const: 0x8f28
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x258
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x1438
-  __AUTH.__objc_data: 0x1048
+  __AUTH_CONST.__auth_got: 0x1450
+  __AUTH.__objc_data: 0x1098
   __AUTH.__data: 0x1f8
-  __DATA.__objc_ivar: 0x484
+  __DATA.__objc_ivar: 0x4c0
   __DATA.__data: 0x9250
-  __DATA.__bss: 0x3ee0
+  __DATA.__bss: 0x3ef0
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0xab0
   __DATA_DIRTY.__data: 0x2d0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3751
-  Symbols:   5910
-  CStrings:  1376
+  Functions: 3788
+  Symbols:   6000
+  CStrings:  1398
 
Symbols:
+ +[NSData(TMExtensions) _tm_dataByReadingRegularFileAtURL:error:]
+ +[TMConfiguration _keySupportsManagedValues:]
+ +[TMSession(Migration) _preferredVolumeStoreAmong:continuingInode:forCurrentVolumeUUID:inBackupAtURL:]
+ +[TMSession(Migration) _preferredVolumeStoreBetween:and:forCurrentVolumeUUID:]
+ -[TMBackupMetadata .cxx_destruct]
+ -[TMBackupMetadata _readSizeInformationFromVolumeStoreURL:]
+ -[TMBackupMetadata bytesAddedByBackup]
+ -[TMBackupMetadata dateBackupCompleted]
+ -[TMBackupMetadata dateVolumeStoreStarted]
+ -[TMBackupMetadata description]
+ -[TMBackupMetadata hasSizeInformation]
+ -[TMBackupMetadata initWithVolumeStoreURL:]
+ -[TMBackupMetadata itemCount]
+ -[TMBackupMetadata logicalSize]
+ -[TMBackupMetadata physicalSize]
+ -[TMBackupMetadata setBytesAddedByBackup:]
+ -[TMBackupMetadata setDateBackupCompleted:]
+ -[TMBackupMetadata setDateVolumeStoreStarted:]
+ -[TMBackupMetadata setHasSizeInformation:]
+ -[TMBackupMetadata setItemCount:]
+ -[TMBackupMetadata setLogicalSize:]
+ -[TMBackupMetadata setPhysicalSize:]
+ -[TMBackupMetadata setSourceOSBuild:]
+ -[TMBackupMetadata setSourceOSVersion:]
+ -[TMBackupMetadata setSourceVolumeBytesUsed:]
+ -[TMBackupMetadata setSourceVolumeIsEncrypted:]
+ -[TMBackupMetadata setTotalBytesCopied:]
+ -[TMBackupMetadata setTrigger:]
+ -[TMBackupMetadata sourceOSBuild]
+ -[TMBackupMetadata sourceOSVersion]
+ -[TMBackupMetadata sourceVolumeBytesUsed]
+ -[TMBackupMetadata sourceVolumeIsEncrypted]
+ -[TMBackupMetadata totalBytesCopied]
+ -[TMBackupMetadata trigger]
+ -[TMSessionVolumeStore backupMetadata]
+ _NSCocoaErrorDomain
+ _OBJC_CLASS_$_TMBackupMetadata
+ _OBJC_IVAR_$_TMBackupMetadata._bytesAddedByBackup
+ _OBJC_IVAR_$_TMBackupMetadata._dateBackupCompleted
+ _OBJC_IVAR_$_TMBackupMetadata._dateVolumeStoreStarted
+ _OBJC_IVAR_$_TMBackupMetadata._hasSizeInformation
+ _OBJC_IVAR_$_TMBackupMetadata._itemCount
+ _OBJC_IVAR_$_TMBackupMetadata._logicalSize
+ _OBJC_IVAR_$_TMBackupMetadata._physicalSize
+ _OBJC_IVAR_$_TMBackupMetadata._sourceOSBuild
+ _OBJC_IVAR_$_TMBackupMetadata._sourceOSVersion
+ _OBJC_IVAR_$_TMBackupMetadata._sourceVolumeBytesUsed
+ _OBJC_IVAR_$_TMBackupMetadata._sourceVolumeIsEncrypted
+ _OBJC_IVAR_$_TMBackupMetadata._totalBytesCopied
+ _OBJC_IVAR_$_TMBackupMetadata._trigger
+ _OBJC_IVAR_$_TMSessionVolumeStore._backupMetadata
+ _OBJC_IVAR_$_TMSessionVolumeStore._backupMetadataLock
+ _OBJC_METACLASS_$_TMBackupMetadata
+ _ReadByteCount
+ _TMOpenContainingDirectory
+ _TMReadErrorForErrno
+ __OBJC_$_INSTANCE_METHODS_TMBackupMetadata
+ __OBJC_$_INSTANCE_VARIABLES_TMBackupMetadata
+ __OBJC_$_PROP_LIST_TMBackupMetadata
+ __OBJC_CLASS_RO_$_TMBackupMetadata
+ __OBJC_METACLASS_RO_$_TMBackupMetadata
+ ___40+[TMConfiguration _expectedClassForKey:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48s_e24_B24?0"TMStructure"8Q16l
+ ___block_descriptor_64_e8_32s40s48s56s_e24_B24?0"TMStructure"8Q16l
+ ___block_descriptor_64_e8_32s40s48s56s_e41_v32?0"NSString"8"NSMutableArray"16^B24l
+ __expectedClassForKey:.expectedClassForKey
+ __expectedClassForKey:.onceToken
+ _fstatat
+ _kCSBackupSnapshotTypeXAttrKey
+ _kTMVolumeStoreBytesUsedXAttrKey
+ _kTMVolumeStoreEncryptedSourceXAttrKey
+ _kTMVolumeStoreProductBuildVersionXAttrKey
+ _kTMVolumeStoreProductUserVisibleVersionXAttrKey
+ _kTMVolumeStoreStartDateXAttrKey
+ _objc_msgSend$_keySupportsManagedValues:
+ _objc_msgSend$_preferredVolumeStoreAmong:continuingInode:forCurrentVolumeUUID:inBackupAtURL:
+ _objc_msgSend$_preferredVolumeStoreBetween:and:forCurrentVolumeUUID:
+ _objc_msgSend$_readSizeInformationFromVolumeStoreURL:
+ _objc_msgSend$_tm_dataByReadingRegularFileAtURL:error:
+ _objc_msgSend$enumerateKeysAndObjectsUsingBlock:
+ _objc_msgSend$hasSizeInformation
+ _objc_msgSend$initWithFileDescriptor:closeOnDealloc:
+ _objc_msgSend$initWithVolumeStoreURL:
+ _objc_msgSend$itemCount
+ _objc_msgSend$logicalSize
+ _objc_msgSend$physicalSize
+ _objc_msgSend$readDataToEndOfFileAndReturnError:
+ _objc_msgSend$setBytesAddedByBackup:
+ _objc_msgSend$setHasSizeInformation:
+ _objc_msgSend$setItemCount:
+ _objc_msgSend$setLogicalSize:
+ _objc_msgSend$setPhysicalSize:
+ _objc_msgSend$sourceOSBuild
+ _objc_msgSend$sourceOSVersion
+ _objc_msgSend$trigger
+ _openat
+ _renameat
+ _unlinkat
- ___block_descriptor_72_e8_32s40s48s56s64s_e24_B24?0"TMStructure"8Q16l
- ___block_descriptor_96_e8_32s40s48s56s64s72s80r88r_e24_B24?0"TMStructure"8Q16l
- ___copy_helper_block_e8_32s40s48s56s64s
- ___copy_helper_block_e8_32s40s48s56s64s72s80r88r
- ___destroy_helper_block_e8_32s40s48s56s64s
- ___destroy_helper_block_e8_32s40s48s56s64s72s80r88r
- _objc_msgSend$dataWithContentsOfURL:options:error:
- _rename
CStrings:
+ "'"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Extensions/NSData+TMExtensions.m"
+ "<%@: %p> {completed: %@, trigger: %ld, os: %@ (%@), logical: %llu, physical: %llu, items: %llu, valid: %@}"
+ "<unknown>"
+ "Backup '%@' contains %lu volume stores claiming volume UUID %@ (%@); presenting '%@'. The backup structure is damaged."
+ "FULLFSYNC failed for '%@', error: %d"
+ "FULLFSYNC failed to open '%@', error: %d"
+ "Failed to remove '%@', error: %d - the write will fail"
+ "Ignoring '%@' - not a real file or directory"
+ "NO"
+ "Refusing to read '%@' - it is a symbolic link"
+ "Refusing to read '%@' - it is not a regular file"
+ "SafeFileIO"
+ "Unexpected non-regular file at '%@' - removing it before writing"
+ "YES"
+ "com.apple.backupd.VolumeBytesUsed"
+ "com.apple.backupd.VolumeIsEncrypted"
+ "com.apple.timemachine.private.volumestore.ProductBuildVersion"
+ "com.apple.timemachine.private.volumestore.ProductUserVisibleVersion"
+ "com.apple.timemachine.private.volumestore.startdate"
+ "name"
+ "v32@?0@\"NSString\"8@\"NSMutableArray\"16^B24"
```
