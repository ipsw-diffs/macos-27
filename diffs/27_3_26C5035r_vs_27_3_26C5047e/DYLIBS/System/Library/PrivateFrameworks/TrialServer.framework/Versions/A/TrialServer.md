## TrialServer

> `/System/Library/PrivateFrameworks/TrialServer.framework/Versions/A/TrialServer`

```diff

-511.2.2.0.0
-  __TEXT.__text: 0x167838
+511.2.4.0.0
+  __TEXT.__text: 0x168cec
   __TEXT.__delay_stubs: 0x80
   __TEXT.__delay_helper: 0xa28
   __TEXT.__lazy_helpers: 0xe8
-  __TEXT.__objc_methlist: 0xc834
-  __TEXT.__const: 0xefc
+  __TEXT.__objc_methlist: 0xc904
+  __TEXT.__const: 0xf00
   __TEXT.__dlopen_cstrs: 0x54
-  __TEXT.__cstring: 0x170c6
+  __TEXT.__cstring: 0x170f4
   __TEXT.__constg_swiftt: 0x38
   __TEXT.__swift5_typeref: 0x14
   __TEXT.__swift5_fieldmd: 0x10
   __TEXT.__swift5_types: 0x4
-  __TEXT.__oslogstring: 0x1e2d2
-  __TEXT.__gcc_except_tab: 0x7f58
-  __TEXT.__unwind_info: 0x52d8
+  __TEXT.__oslogstring: 0x1e485
+  __TEXT.__gcc_except_tab: 0x7fb8
+  __TEXT.__unwind_info: 0x5320
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1268
-  __DATA_CONST.__objc_classlist: 0x9c0
+  __DATA_CONST.__objc_classlist: 0x9c8
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x268
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x65d0
+  __DATA_CONST.__objc_selrefs: 0x6640
   __DATA_CONST.__objc_protorefs: 0x50
-  __DATA_CONST.__objc_superrefs: 0x630
+  __DATA_CONST.__objc_superrefs: 0x638
   __DATA_CONST.__objc_arraydata: 0x390
-  __DATA_CONST.__got: 0x1438
-  __AUTH_CONST.__const: 0x7a90
+  __DATA_CONST.__got: 0x1458
+  __AUTH_CONST.__const: 0x7a60
   __AUTH_CONST.__cfstring: 0xf300
-  __AUTH_CONST.__objc_const: 0x18268
+  __AUTH_CONST.__objc_const: 0x18358
   __AUTH_CONST.__lazy_load_got: 0x10
   __AUTH_CONST.__objc_intobj: 0xe58
   __AUTH_CONST.__objc_arrayobj: 0x360
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x10f0
+  __AUTH.__objc_data: 0x1140
   __AUTH.__data: 0x6e0
-  __DATA.__objc_ivar: 0x96c
+  __DATA.__objc_ivar: 0x974
   __DATA.__data: 0x2ae8
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0xa0

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 5140
-  Symbols:   12252
-  CStrings:  4291
+  Functions: 5156
+  Symbols:   12295
+  CStrings:  4302
 
Symbols:
+ +[NSFileManager(TRIServer) _triTakeOwnershipOfItemAtPath:]
+ +[NSFileManager(TRIServer) _triTakeOwnershipOfTreeAtPath:]
+ +[NSFileManager(TRIServer) triCopyDirectoryWithoutFollowingLinksFromPath:toNewPath:]
+ +[TRIInternalAgentToSystemServiceRequestHandler _areValidFactorNames:]
+ +[TRIInternalAgentToSystemServiceRequestHandler _isValidGlobalFactorPackPath:treatmentsDir:]
+ -[TRIFBFactorPackStorage _removeUnreferencedFactorLevelsWithExternalReferenceStore:removedCount:]
+ -[TRIFBFactorPackStorage _removeUnreferencedFactorPackSetsWithNamespaceName:externalReferenceStore:removedCount:]
+ -[TRIFBFactorPackStorage _removeUnreferencedFactorPackSetsWithParentDir:externalReferenceStore:removedCount:]
+ -[TRIFBFactorPackStorage removeUnreferencedFactorLevelsWithServerContext:removedCount:]
+ -[TRIFactorPackStorage _removeUnreferencedFactorPackSetsWithNamespaceName:externalReferenceStore:removedCount:]
+ -[TRIFactorPackStorage _removeUnreferencedFactorPackSetsWithParentDir:externalReferenceStore:removedCount:]
+ -[TRIFactorPackStorage _removeUnreferencedFactorPacksWithExternalReferenceStore:removedCount:]
+ -[TRIFactorPackStorage removeUnreferencedFactorPacksWithServerContext:removedCount:]
+ -[TRIGlobalFactorPackExternalReferenceStore .cxx_destruct]
+ -[TRIGlobalFactorPackExternalReferenceStore hasReferenceToPath:]
+ -[TRIGlobalFactorPackExternalReferenceStore initWithServerContext:]
+ -[TRIInternalAgentToSystemServiceRequestHandler _ensureGlobalFactorPackIsOwnedByCurrentProcessAtPath:]
+ -[TRIInternalAgentToSystemServiceRequestHandler _replaceGlobalFactorPackAtPath:withCopyOfDirectory:]
+ GCC_except_table50
+ _NSFileGroupOwnerAccountID
+ _NSFileOwnerAccountID
+ _NSFilePosixPermissions
+ _OBJC_CLASS_$_TRIGlobalFactorPackExternalReferenceStore
+ _OBJC_IVAR_$_TRIGlobalFactorPackExternalReferenceStore._activeFactorPackIds
+ _OBJC_IVAR_$_TRIGlobalFactorPackExternalReferenceStore._context
+ _OBJC_METACLASS_$_TRIGlobalFactorPackExternalReferenceStore
+ __OBJC_$_CLASS_METHODS_TRIInternalAgentToSystemServiceRequestHandler
+ __OBJC_$_INSTANCE_METHODS_TRIGlobalFactorPackExternalReferenceStore
+ __OBJC_$_INSTANCE_VARIABLES_TRIGlobalFactorPackExternalReferenceStore
+ __OBJC_CLASS_PROTOCOLS_$_TRIGlobalFactorPackExternalReferenceStore
+ __OBJC_CLASS_RO_$_TRIGlobalFactorPackExternalReferenceStore
+ __OBJC_METACLASS_RO_$_TRIGlobalFactorPackExternalReferenceStore
+ ___107-[TRIFactorPackStorage _removeUnreferencedFactorPackSetsWithParentDir:externalReferenceStore:removedCount:]_block_invoke
+ ___109-[TRIFBFactorPackStorage _removeUnreferencedFactorPackSetsWithParentDir:externalReferenceStore:removedCount:]_block_invoke
+ ___58+[NSFileManager(TRIServer) _triTakeOwnershipOfTreeAtPath:]_block_invoke
+ _copyfile
+ _getegid
+ _objc_msgSend$_areValidFactorNames:
+ _objc_msgSend$_ensureGlobalFactorPackIsOwnedByCurrentProcessAtPath:
+ _objc_msgSend$_isValidGlobalFactorPackPath:treatmentsDir:
+ _objc_msgSend$_removeUnreferencedFactorLevelsWithExternalReferenceStore:removedCount:
+ _objc_msgSend$_removeUnreferencedFactorPackSetsWithNamespaceName:externalReferenceStore:removedCount:
+ _objc_msgSend$_removeUnreferencedFactorPackSetsWithParentDir:externalReferenceStore:removedCount:
+ _objc_msgSend$_removeUnreferencedFactorPacksWithExternalReferenceStore:removedCount:
+ _objc_msgSend$_replaceGlobalFactorPackAtPath:withCopyOfDirectory:
+ _objc_msgSend$_triTakeOwnershipOfItemAtPath:
+ _objc_msgSend$_triTakeOwnershipOfTreeAtPath:
+ _objc_msgSend$dataWithPropertyList:error:
+ _objc_msgSend$filePosixPermissions
+ _objc_msgSend$removeUnreferencedFactorLevelsWithServerContext:removedCount:
+ _objc_msgSend$removeUnreferencedFactorPacksWithServerContext:removedCount:
+ _objc_msgSend$triContainsControlCharacters
+ _objc_msgSend$triCopyDirectoryWithoutFollowingLinksFromPath:toNewPath:
- -[TRIFBFactorPackStorage _removeUnreferencedFactorPackSetsWithParentDir:removedCount:]
- -[TRIFBFactorPackStorage removeUnreferencedFactorLevelsWithRemovedCount:]
- -[TRIFactorPackStorage _removeUnreferencedFactorPackSetsWithParentDir:removedCount:]
- ___84-[TRIFactorPackStorage _removeUnreferencedFactorPackSetsWithParentDir:removedCount:]_block_invoke
- ___86-[TRIFBFactorPackStorage _removeUnreferencedFactorPackSetsWithParentDir:removedCount:]_block_invoke
- ___block_descriptor_56_e8_32s40r_e22_v24?0"NSString"8^B16l
- _objc_msgSend$_removeUnreferencedFactorPackSetsWithNamespaceName:removedCount:
- _objc_msgSend$_removeUnreferencedFactorPackSetsWithParentDir:removedCount:
- _objc_msgSend$removeUnreferencedFactorLevelsWithRemovedCount:
- _objc_msgSend$removeUnreferencedFactorPacksWithRemovedCount:
CStrings:
+ "-[TRIFBFactorPackStorage _removeUnreferencedFactorPackSetsWithNamespaceName:externalReferenceStore:removedCount:]"
+ "-[TRIFactorPackStorage _removeUnreferencedFactorPackSetsWithNamespaceName:externalReferenceStore:removedCount:]"
+ "Cannot copy %{public}@, not a directory"
+ "Cannot copy to %{public}@, already exists"
+ "Could not update ownership of factor pack: %@"
+ "Failed to copy %{public}@ to %{public}@: %s (%d)"
+ "Failed to read %{public}@: %{public}@"
+ "Failed to read attributes of %{public}@: %{public}@"
+ "Failed to take ownership of %{public}@: %{public}@"
+ "Failed to write users per factor file with error: %{public}@"
+ "Global factor pack at %@ is not a directory"
+ "Invalid factor names: %@"
+ "Nov 10 2026"
+ "Rejecting invalid factor name: %@"
+ "Rejecting invalid global factor pack path: %@"
+ "Replacing global factor pack at %@ owned by uid %u with a copy"
+ "TrialXP-511.2.4"
- "-[TRIFBFactorPackStorage _removeUnreferencedFactorPackSetsWithNamespaceName:removedCount:]"
- "-[TRIFactorPackStorage _removeUnreferencedFactorPackSetsWithNamespaceName:removedCount:]"
- "Asked to delete factor pack at non-global or non-treatment directory location: %@"
- "Failed to write users per factor file to temp path with error: %{public}@"
- "Oct 29 2026"
- "TrialXP-511.2.2"
```
