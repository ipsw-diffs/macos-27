## EventKit

> `/System/Library/Frameworks/EventKit.framework/Versions/A/EventKit`

```diff

 1976.2.2.0.0
-  __TEXT.__text: 0x1ae794
-  __TEXT.__objc_methlist: 0x15bd4
+  __TEXT.__text: 0x1aee68
+  __TEXT.__objc_methlist: 0x15c04
   __TEXT.__cstring: 0xc20f
   __TEXT.__const: 0x4810
-  __TEXT.__oslogstring: 0xf064
-  __TEXT.__gcc_except_tab: 0x3a2c
+  __TEXT.__oslogstring: 0xf0c4
+  __TEXT.__gcc_except_tab: 0x3a58
   __TEXT.__dlopen_cstrs: 0x4e4
   __TEXT.__ustring: 0x1a0
   __TEXT.__swift5_typeref: 0x1988

   __TEXT.__swift_as_ret: 0xec
   __TEXT.__swift_as_cont: 0x1a8
   __TEXT.__swift5_mpenum: 0x60
-  __TEXT.__unwind_info: 0x8620
+  __TEXT.__unwind_info: 0x8648
   __TEXT.__eh_frame: 0x25ec
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0xa0
   __DATA_CONST.__objc_protolist: 0x260
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xaf58
+  __DATA_CONST.__objc_selrefs: 0xaf88
   __DATA_CONST.__objc_protorefs: 0x70
   __DATA_CONST.__objc_superrefs: 0x520
   __DATA_CONST.__objc_arraydata: 0x5d8
-  __DATA_CONST.__got: 0x1a20
-  __AUTH_CONST.__const: 0x82f0
+  __DATA_CONST.__got: 0x1a28
+  __AUTH_CONST.__const: 0x8310
   __AUTH_CONST.__cfstring: 0x9f40
-  __AUTH_CONST.__objc_const: 0x188d0
+  __AUTH_CONST.__objc_const: 0x188e0
   __AUTH_CONST.__objc_intobj: 0x6d8
   __AUTH_CONST.__objc_arrayobj: 0x1f8
   __AUTH_CONST.__objc_dictobj: 0x1b8
   __AUTH_CONST.__objc_doubleobj: 0x100
-  __AUTH_CONST.__auth_got: 0x1240
+  __AUTH_CONST.__auth_got: 0x1248
   __AUTH.__objc_data: 0x1db8
   __AUTH.__data: 0x610
   __DATA.__objc_ivar: 0xd80
   __DATA.__data: 0x28e0
-  __DATA.__bss: 0x45a0
+  __DATA.__bss: 0x45b0
   __DATA.__common: 0x68
   __DATA_DIRTY.__objc_data: 0x3388
   __DATA_DIRTY.__data: 0x928

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 10838
-  Symbols:   17905
-  CStrings:  2702
+  Functions: 10846
+  Symbols:   17921
+  CStrings:  2704
 
Symbols:
+ +[EKAttachment _expandedArchiveTemporaryDirectoryRootForURL:]
+ +[EKAttachment _volumeIdentifierForURL:]
+ -[EKAttachment _mirroredTemporaryURLForExpandedArchiveContentsOfArchiveAtURL:]
+ -[EKAttachment localURLExpandingArchiveIfNeeded]
+ _NSURLVolumeIdentifierKey
+ _UnzipArchive
+ ___61+[EKAttachment _expandedArchiveTemporaryDirectoryRootForURL:]_block_invoke
+ _expandedArchiveTemporaryDirectoryRootForURL:.cachedRootsByVolume
+ _expandedArchiveTemporaryDirectoryRootForURL:.onceToken
+ _objc_msgSend$CalTemporaryDirectoryAppropriateForURL:
+ _objc_msgSend$_expandedArchiveTemporaryDirectoryRootForURL:
+ _objc_msgSend$_mirroredTemporaryURLForExpandedArchiveContentsOfArchiveAtURL:
+ _objc_msgSend$_volumeIdentifierForURL:
+ _objc_msgSend$autoArchived
+ _objc_msgSend$fileExistsAtPath:
+ _objc_msgSend$localURLForArchivedData
CStrings:
+ "Unable to determine volume identifier for %@: %@"
+ "Unable to expand attachment archive %@"
```
