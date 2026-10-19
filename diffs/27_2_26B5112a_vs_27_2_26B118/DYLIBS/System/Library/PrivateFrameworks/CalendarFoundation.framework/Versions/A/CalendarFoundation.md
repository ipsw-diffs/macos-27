## CalendarFoundation

> `/System/Library/PrivateFrameworks/CalendarFoundation.framework/Versions/A/CalendarFoundation`

```diff

 1636.2.2.0.0
-  __TEXT.__text: 0x69c04
-  __TEXT.__objc_methlist: 0x600c
-  __TEXT.__cstring: 0x70d2
+  __TEXT.__text: 0x6b278
+  __TEXT.__objc_methlist: 0x6024
+  __TEXT.__cstring: 0x7132
   __TEXT.__const: 0x8c4
-  __TEXT.__gcc_except_tab: 0xa78
-  __TEXT.__oslogstring: 0x37d5
+  __TEXT.__gcc_except_tab: 0xb4c
+  __TEXT.__oslogstring: 0x3b85
   __TEXT.__ustring: 0x2e8
   __TEXT.__dlopen_cstrs: 0xe0
   __TEXT.__swift5_typeref: 0x2cc

   __TEXT.__swift_as_entry: 0x8
   __TEXT.__swift_as_ret: 0x8
   __TEXT.__swift_as_cont: 0x8
-  __TEXT.__unwind_info: 0x2940
+  __TEXT.__unwind_info: 0x2998
   __TEXT.__eh_frame: 0x130
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0xb0
   __DATA_CONST.__objc_protolist: 0xc0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x43b8
+  __DATA_CONST.__objc_selrefs: 0x43d8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x188
   __DATA_CONST.__objc_arraydata: 0xf8
-  __DATA_CONST.__got: 0x938
-  __AUTH_CONST.__const: 0x1d68
-  __AUTH_CONST.__cfstring: 0x97c0
+  __DATA_CONST.__got: 0x940
+  __AUTH_CONST.__const: 0x1d98
+  __AUTH_CONST.__cfstring: 0x9820
   __AUTH_CONST.__objc_const: 0x7c10
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_intobj: 0x18
-  __AUTH_CONST.__auth_got: 0xb80
+  __AUTH_CONST.__auth_got: 0xbd0
   __AUTH.__objc_data: 0xee0
   __AUTH.__data: 0x178
   __DATA.__objc_ivar: 0x364

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2887
-  Symbols:   6092
-  CStrings:  1654
+  Functions: 2907
+  Symbols:   6122
+  CStrings:  1672
 
Symbols:
+ +[CalAttachmentUtils URL:isContainedInDirectory:]
+ +[CalAttachmentUtils isSymbolicLinkAtURL:]
+ UnzipArchiveWithLimits
+ _BOMCopierCancelCopy
+ _BOMCopierSetCopyFileFinishedHandler
+ _BOMCopierSetCopyFileStartedHandler
+ _BOMCopierSetCopyFileUpdateHandler
+ _BOMCopierUserData
+ _CalUnzipCopyFileFinished
+ _CalUnzipCopyFileStarted
+ _CalUnzipCopyFileUpdate
+ _UnzipArchiveWithLimits
+ __CalUnzipCopyFileFinished
+ __CalUnzipCopyFileStarted
+ __CalUnzipCopyFileUpdate
+ __CalUnzipEntryDestinationPath
+ __CalUnzipParentIsContained
+ __CalUnzipTrackTopLevelPath
+ ___CalUnzipRemoveEscapingSymlinks_block_invoke
+ ____CalUnzipRemoveEscapingSymlinks_block_invoke
+ ___block_descriptor_40_e8_32r_e27_B24?0"NSURL"8"NSError"16l
+ _lstat
+ _objc_msgSend$URL:isContainedInDirectory:
+ _objc_msgSend$enumeratorAtURL:includingPropertiesForKeys:options:errorHandler:
+ _objc_msgSend$fileURLWithPath:isDirectory:
+ _objc_msgSend$isSymbolicLinkAtURL:
+ _realpath$DARWIN_EXTSN
+ _strcmp
+ _strncmp
+ _unlink
CStrings:
+ ".."
+ "Archive contains a symlink pointing outside destination; removing it. entry = %@"
+ "Archive entry exceeds total size limit (%llu bytes); canceling extraction."
+ "Archive entry resolves outside destination; canceling extraction. entry = %s"
+ "Archive entry's parent directory escapes destination (likely via an earlier symlink entry); canceling extraction. entry = %s"
+ "Archive exceeds item count limit (%lu); canceling extraction."
+ "Archive exceeds total size limit (%llu bytes) while writing an entry; canceling extraction."
+ "Archive exceeds total size limit (%llu bytes); canceling extraction."
+ "B24@?0@\"NSURL\"8@\"NSError\"16"
+ "Could not lstat %@: %d"
+ "Could not resolve %@ or %@: %d"
+ "Could not resolve destination %@: %d; refusing to extract."
+ "Failed to enumerate extracted archive contents at %@: %@; treating as unsafe."
+ "Failed to remove debris left by a failed extraction at %@: %@"
+ "Failed to remove escaping symlink: %d"
+ "Refusing to remove %@: its parent directory is not contained in destination."
+ "enforceDestinationEncapsulation"
+ "enforceDestinationLocation"
```
