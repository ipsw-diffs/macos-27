## PackageKit

> `/System/Library/PrivateFrameworks/PackageKit.framework/Versions/A/PackageKit`

```diff

-1525.40.8.0.0
-  __TEXT.__text: 0x89dbc
-  __TEXT.__objc_methlist: 0x7b34
+1525.60.3.0.0
+  __TEXT.__text: 0x8aa60
+  __TEXT.__objc_methlist: 0x7b9c
   __TEXT.__const: 0x390
   __TEXT.__constg_swiftt: 0x188
   __TEXT.__swift5_typeref: 0x7c
   __TEXT.__swift5_reflstr: 0x21
   __TEXT.__swift5_fieldmd: 0x5c
   __TEXT.__swift5_types: 0x8
-  __TEXT.__cstring: 0x12c22
-  __TEXT.__gcc_except_tab: 0x161c
+  __TEXT.__cstring: 0x12eeb
+  __TEXT.__gcc_except_tab: 0x1690
   __TEXT.__oslogstring: 0x39
   __TEXT.__dof_PackageKi: 0x1ba4
-  __TEXT.__unwind_info: 0x2980
+  __TEXT.__unwind_info: 0x2990
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4698
+  __DATA_CONST.__objc_selrefs: 0x46e0
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x3c0
   __DATA_CONST.__objc_arraydata: 0x68
-  __DATA_CONST.__got: 0x9c8
+  __DATA_CONST.__got: 0x9c0
   __AUTH_CONST.__const: 0x1850
   __AUTH_CONST.__cfstring: 0xbc80
-  __AUTH_CONST.__objc_const: 0xc368
+  __AUTH_CONST.__objc_const: 0xc3f8
   __AUTH_CONST.__objc_intobj: 0x480
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__auth_got: 0x10e0
   __AUTH.__objc_data: 0x13d0
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0xa20
+  __DATA.__objc_ivar: 0xa2c
   __DATA.__data: 0x830
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x168

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 2886
-  Symbols:   7563
-  CStrings:  2162
+  Functions: 2895
+  Symbols:   7585
+  CStrings:  2170
 
Symbols:
+ +[PKBundleComponent _enumerateDirectoryWithFileDescriptor:anchor:relativePath:intoReferenceArray:droppedEntries:]
+ +[PKFileReference fileReferenceWithAnchor:relativePath:fileStat:parentStat:error:]
+ -[PKBundleComponent onDiskSubpathFileReferences]
+ -[PKFileReference _openAndStatAnchoredParentWithOpenOptions:outStatBuf:error:]
+ -[PKFileReference anchorParentRange]
+ -[PKFileReference anchor]
+ -[PKFileReference fileMode]
+ -[PKFileReference initWithPath:parentDeviceID:parentInode:fileDeviceID:fileInode:fileMode:]
+ -[PKFileReference setAnchor:]
+ -[PKFileReference setAnchorParentRange:]
+ -[PKFileReference setFileMode:]
+ GCC_except_table45
+ _OBJC_IVAR_$_PKFileReference._anchor
+ _OBJC_IVAR_$_PKFileReference._anchorParentRange
+ _OBJC_IVAR_$_PKFileReference._fileMode
+ _objc_msgSend$_enumerateDirectoryWithFileDescriptor:anchor:relativePath:intoReferenceArray:droppedEntries:
+ _objc_msgSend$_openAndStatAnchoredParentWithOpenOptions:outStatBuf:error:
+ _objc_msgSend$anchor
+ _objc_msgSend$anchorParentRange
+ _objc_msgSend$fileMode
+ _objc_msgSend$initWithPath:parentDeviceID:parentInode:fileDeviceID:fileInode:fileMode:
+ _objc_msgSend$onDiskSubpathFileReferences
+ _objc_msgSend$setAnchor:
+ _objc_msgSend$setAnchorParentRange:
+ _objc_msgSend$setFileMode:
- +[PKFileReference fileReferenceWithPath:error:]
- -[PKFileReference initWithPath:parentDeviceID:parentInode:fileDeviceID:fileInode:]
- _objc_msgSend$initWithPath:parentDeviceID:parentInode:fileDeviceID:fileInode:
CStrings:
+ "PackageKit: %lu entries of PKComponent(%s) were left out of its references in total."
+ "PackageKit: Cannot obsolete expected directory (%s) and its .DS_Store has already been removed, unlinkat() has failed. %s"
+ "PackageKit: Cannot obsolete expected directory (%s), removing its .DS_Store failed. %s"
+ "PackageKit: Cannot obsolete expected directory (%s), unlinkat() has failed. %s"
+ "PackageKit: Failed to fstat directory for reference enumeration: %s"
+ "PackageKit: Leaving %s out of the bundle's references: %s"
+ "PackageKit: Not descending into %s: it changed between being stat'd and opened."
+ "PackageKit: Recording %s without its contents: %s"
+ "PackageKit: Refusing to enumerate references for PKComponent(%s): no validated bundle reference."
+ "PackageKit: Will not obsolete bundle %s: its on-disk contents could not be enumerated through a validated descriptor."
- "PackageKit: Cannot obsolete expected directory (%s), removefileat() has failed. %s"
- "PackageKit: Error creating reference for %s: %s"
```
