## SystemMigrationNetwork

> `/System/Library/PrivateFrameworks/SystemMigrationNetwork.framework/Versions/A/SystemMigrationNetwork`

```diff

-1446.60.1.0.0
-  __TEXT.__text: 0x3dfd4
-  __TEXT.__objc_methlist: 0x4698
+1446.60.5.0.0
+  __TEXT.__text: 0x3f98c
+  __TEXT.__objc_methlist: 0x4838
   __TEXT.__const: 0x140
-  __TEXT.__cstring: 0x9aa9
+  __TEXT.__cstring: 0x9cbe
   __TEXT.__gcc_except_tab: 0xf38
-  __TEXT.__ustring: 0x2f56
+  __TEXT.__ustring: 0x2f5a
   __TEXT.__oslogstring: 0xb
-  __TEXT.__unwind_info: 0x10e0
+  __TEXT.__unwind_info: 0x1120
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2a70
+  __DATA_CONST.__objc_selrefs: 0x2b10
   __DATA_CONST.__objc_superrefs: 0x138
   __DATA_CONST.__objc_arraydata: 0xf0
-  __DATA_CONST.__got: 0x5c0
+  __DATA_CONST.__got: 0x5d0
   __AUTH_CONST.__const: 0x810
-  __AUTH_CONST.__cfstring: 0x9ac0
-  __AUTH_CONST.__objc_const: 0x6a68
+  __AUTH_CONST.__cfstring: 0x9d20
+  __AUTH_CONST.__objc_const: 0x6c88
   __AUTH_CONST.__objc_intobj: 0x2b8
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x1298
-  __DATA.__objc_ivar: 0x544
+  __DATA.__objc_ivar: 0x568
   __DATA.__data: 0x318
   __DATA.__bss: 0x108
   __DATA.__common: 0x18

   - /usr/lib/libParallelCompression.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1564
-  Symbols:   4132
-  CStrings:  1301
+  Functions: 1597
+  Symbols:   4206
+  CStrings:  1320
 
Symbols:
+ +[XMArchiveStream _isWellTypedHeader:]
+ +[XMArchiveStream _lexicalComponentsOfPath:]
+ +[XMArchiveStream path:isContainedInRoot:]
+ +[XMArchiveStream pathNamingRealSystemFolder:]
+ -[SMNWindowsCopyAction attributeFailureCount]
+ -[SMNWindowsCopyAction attributedCount]
+ -[SMNWindowsCopyAction attributesForNewItemAtURL:forFile:isDirectory:]
+ -[SMNWindowsCopyAction setAttributeFailureCount:]
+ -[SMNWindowsCopyAction setAttributedCount:]
+ -[SMNWindowsCopyAction setSkippedCount:]
+ -[SMNWindowsCopyAction shouldWriteFile:toURL:]
+ -[SMNWindowsCopyAction skippedCount]
+ -[SMWindowsCopyPathAction attributeFailureCount]
+ -[SMWindowsCopyPathAction attributedCount]
+ -[SMWindowsCopyPathAction attributesForNewItemAtURL:forFile:isDirectory:]
+ -[SMWindowsCopyPathAction setAttributeFailureCount:]
+ -[SMWindowsCopyPathAction setAttributedCount:]
+ -[SMWindowsCopyPathAction setSkippedCount:]
+ -[SMWindowsCopyPathAction shouldWriteFile:toURL:]
+ -[SMWindowsCopyPathAction skippedCount]
+ -[XMArchiveStream _applyAttributes:toDescriptor:atURL:]
+ -[XMArchiveStream _applyAttributes:toItemAtURL:]
+ -[XMArchiveStream _attributesForNewItemAtURL:forFile:isDirectory:]
+ -[XMArchiveStream _openDirectoryAtURL:creatingLevelsForFile:]
+ -[XMArchiveStream _shouldWriteFile:]
+ -[XMArchiveStream _skipFile:]
+ -[XMArchiveStream attributeFailureCount]
+ -[XMArchiveStream attributedCount]
+ -[XMArchiveStream setAttributeFailureCount:]
+ -[XMArchiveStream setAttributedCount:]
+ -[XMArchiveStream setSkippedCount:]
+ -[XMArchiveStream skippedCount]
+ _NSFileGroupOwnerAccountID
+ _NSFileOwnerAccountID
+ _OBJC_IVAR_$_SMNWindowsCopyAction._attributeFailureCount
+ _OBJC_IVAR_$_SMNWindowsCopyAction._attributedCount
+ _OBJC_IVAR_$_SMNWindowsCopyAction._skippedCount
+ _OBJC_IVAR_$_SMWindowsCopyPathAction._attributeFailureCount
+ _OBJC_IVAR_$_SMWindowsCopyPathAction._attributedCount
+ _OBJC_IVAR_$_SMWindowsCopyPathAction._skippedCount
+ _OBJC_IVAR_$_XMArchiveStream._attributeFailureCount
+ _OBJC_IVAR_$_XMArchiveStream._attributedCount
+ _OBJC_IVAR_$_XMArchiveStream._skippedCount
+ _XMIsPrivateAlias
+ __OBJC_$_PROP_LIST_XMArchiveStream
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SMWindowsArchiveStreamDelegate
+ __OBJC_$_PROTOCOL_REFS_SMWindowsArchiveStreamDelegate
+ _fchmod
+ _fchown
+ _fstat
+ _fstatat
+ _mkdirat
+ _objc_msgSend$_applyAttributes:toDescriptor:atURL:
+ _objc_msgSend$_applyAttributes:toItemAtURL:
+ _objc_msgSend$_attributesForNewItemAtURL:forFile:isDirectory:
+ _objc_msgSend$_isWellTypedHeader:
+ _objc_msgSend$_lexicalComponentsOfPath:
+ _objc_msgSend$_openDirectoryAtURL:creatingLevelsForFile:
+ _objc_msgSend$_shouldWriteFile:
+ _objc_msgSend$_skipFile:
+ _objc_msgSend$attributeFailureCount
+ _objc_msgSend$attributedCount
+ _objc_msgSend$attributesForNewItemAtURL:forFile:isDirectory:
+ _objc_msgSend$componentsSeparatedByString:
+ _objc_msgSend$copyAction:attributesForNewItemAtURL:forFile:isDirectory:
+ _objc_msgSend$copyAction:shouldWriteFile:toURL:
+ _objc_msgSend$path:isContainedInRoot:
+ _objc_msgSend$pathNamingRealSystemFolder:
+ _objc_msgSend$removeObjectAtIndex:
+ _objc_msgSend$setAttributeFailureCount:
+ _objc_msgSend$setAttributedCount:
+ _objc_msgSend$setSkippedCount:
+ _objc_msgSend$shouldWriteFile:toURL:
+ _objc_msgSend$skippedCount
+ _openat
+ _unlinkat
- _objc_msgSend$fileExistsAtPath:isDirectory:
- _objc_msgSend$removeItemAtURL:error:
CStrings:
+ "\x00"
+ "%@: Failed to create directory %@: %d (%s)"
+ "%@: Failed to create parent directory for %@: %d (%s)"
+ "%@: Failed to open %@ to set owner or mode: %d (%s)"
+ "%@: Failed to replace existing item at %@: %d (%s)"
+ "%@: Failed to set owner or mode on %@: %d (%s)"
+ "%@: Not setting owner or mode on %@, which is not a file with one link"
+ "%@: Refusing %@ outside %@"
+ "%@: Refusing a header with a value of the wrong type"
+ "%@: Refusing file name in %@"
+ "%@: Refusing header length %d"
+ "%@: Set owner %@:%@ and mode %@ on %@"
+ "%@: Skipping %@, because a folder or another item has its name"
+ "%@: Skipping refused item %@"
+ "%@: unexpected EOF reading %@ from %d with %ld"
+ "%o"
+ "-"
+ ".."
+ "Icon\r"
+ "etc"
+ "tmp"
+ "var"
- "%@: Failed to create directory %@: %@"
- "%@: Failed to create parent directory for %@: %@"
- "Failed to delete existing file at %@: %@"
```
