## PosterBoardServices

> `/System/iOSSupport/System/Library/PrivateFrameworks/PosterBoardServices.framework/Versions/A/PosterBoardServices`

```diff

-355.3.7.0.0
-  __TEXT.__text: 0x78df0
-  __TEXT.__objc_methlist: 0x50e0
+355.3.12.0.0
+  __TEXT.__text: 0x7a638
+  __TEXT.__objc_methlist: 0x5188
   __TEXT.__const: 0xb28
-  __TEXT.__cstring: 0x6a9b
+  __TEXT.__cstring: 0x6bbb
   __TEXT.__gcc_except_tab: 0x101c
   __TEXT.__oslogstring: 0x388e
   __TEXT.__dlopen_cstrs: 0x2f6

   __TEXT.__swift5_types: 0x24
   __TEXT.__swift5_capture: 0x30
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x2490
+  __TEXT.__unwind_info: 0x24e0
   __TEXT.__eh_frame: 0x590
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1af0
+  __DATA_CONST.__const: 0x1b18
   __DATA_CONST.__objc_classlist: 0x2b8
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0xe8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2a88
+  __DATA_CONST.__objc_selrefs: 0x2ad0
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x230
   __DATA_CONST.__got: 0x6e8
   __AUTH_CONST.__const: 0x748
-  __AUTH_CONST.__cfstring: 0x4d40
-  __AUTH_CONST.__objc_const: 0x10748
+  __AUTH_CONST.__cfstring: 0x4d60
+  __AUTH_CONST.__objc_const: 0x10818
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0xc28
+  __AUTH_CONST.__auth_got: 0xc20
   __AUTH.__objc_data: 0x1200
   __AUTH.__data: 0x118
-  __DATA.__objc_ivar: 0x5d4
+  __DATA.__objc_ivar: 0x5d8
   __DATA.__data: 0xc20
   __DATA.__bss: 0xcc0
   __DATA.__common: 0x58

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2631
-  Symbols:   4821
-  CStrings:  1089
+  Functions: 2654
+  Symbols:   4846
+  CStrings:  1094
 
Symbols:
+ -[PRSPosterGalleryItemOptions setTimeStyle:]
+ -[PRSPosterGalleryItemOptions timeStyle]
+ -[PRSServer fetchAmbientPosterDiagnosticsWithCompletion:]
+ -[PRSServer fetchMigrationStateWithCompletion:]
+ -[PRSServer importArchivedDataStoreData:named:completion:]
+ -[PRSServer restoreArchivedDataStoreNamed:backupExistingDataStore:resetMigrationState:completion:]
+ -[PRSService fetchAmbientPosterDiagnosticsWithCompletion:]
+ -[PRSService fetchMigrationStateWithCompletion:]
+ -[PRSService importArchivedDataStoreData:named:completion:]
+ -[PRSService restoreArchivedDataStoreNamed:backupExistingDataStore:resetMigrationState:completion:]
+ _OBJC_IVAR_$_PRSPosterGalleryItemOptions._timeStyle
+ ___39-[PRSPosterGalleryItemOptions isEqual:]_block_invoke_17
+ ___47-[PRSServer fetchMigrationStateWithCompletion:]_block_invoke
+ ___48-[PRSService fetchMigrationStateWithCompletion:]_block_invoke
+ ___57-[PRSServer fetchAmbientPosterDiagnosticsWithCompletion:]_block_invoke
+ ___58-[PRSService fetchAmbientPosterDiagnosticsWithCompletion:]_block_invoke
+ ___59-[PRSService importArchivedDataStoreData:named:completion:]_block_invoke
+ ___99-[PRSService restoreArchivedDataStoreNamed:backupExistingDataStore:resetMigrationState:completion:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8
+ _objc_msgSend$fetchAmbientPosterDiagnosticsWithCompletion:
+ _objc_msgSend$fetchMigrationStateWithCompletion:
+ _objc_msgSend$importArchivedDataStoreData:named:completion:
+ _objc_msgSend$restoreArchivedDataStoreNamed:backupExistingDataStore:resetMigrationState:completion:
+ _objc_msgSend$server:fetchAmbientPosterDiagnosticsWithCompletion:
+ _objc_msgSend$server:fetchMigrationStateWithCompletion:
+ _objc_msgSend$server:importArchivedDataStoreData:named:completion:
+ _objc_msgSend$server:restoreArchivedDataStoreNamed:backupExistingDataStore:resetMigrationState:completion:
- _objc_msgSend$server:restoreArchivedDataStoreNamed:backupExistingDataStore:completion:
- _swift_release_x26
CStrings:
+ "-[PRSServer fetchAmbientPosterDiagnosticsWithCompletion:]"
+ "-[PRSServer fetchMigrationStateWithCompletion:]"
+ "-[PRSServer importArchivedDataStoreData:named:completion:]"
+ "-[PRSServer restoreArchivedDataStoreNamed:backupExistingDataStore:resetMigrationState:completion:]"
+ "archivedDataStoreName"
```
