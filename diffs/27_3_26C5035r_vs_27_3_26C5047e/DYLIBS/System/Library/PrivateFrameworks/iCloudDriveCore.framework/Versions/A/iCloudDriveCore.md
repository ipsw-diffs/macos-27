## iCloudDriveCore

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/Versions/A/iCloudDriveCore`

```diff

-5168.60.14.0.0
-  __TEXT.__text: 0x33f118
+5168.60.18.0.0
+  __TEXT.__text: 0x33f5dc
   __TEXT.__objc_methlist: 0x1c3cc
   __TEXT.__const: 0x4f8
-  __TEXT.__cstring: 0x852e4
-  __TEXT.__oslogstring: 0x400c5
+  __TEXT.__cstring: 0x85336
+  __TEXT.__oslogstring: 0x4018d
   __TEXT.__gcc_except_tab: 0x180f0
   __TEXT.__ustring: 0x36
-  __TEXT.__unwind_info: 0xd958
+  __TEXT.__unwind_info: 0xd970
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0xd8
   __DATA_CONST.__objc_protolist: 0x2b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf480
+  __DATA_CONST.__objc_selrefs: 0xf488
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x960
   __DATA_CONST.__objc_arraydata: 0xfd8
-  __DATA_CONST.__got: 0x1818
-  __AUTH_CONST.__const: 0xbfc8
-  __AUTH_CONST.__cfstring: 0x24100
+  __DATA_CONST.__got: 0x1820
+  __AUTH_CONST.__const: 0xc018
+  __AUTH_CONST.__cfstring: 0x24120
   __AUTH_CONST.__objc_const: 0x422f8
   __AUTH_CONST.__objc_intobj: 0xc30
   __AUTH_CONST.__objc_arrayobj: 0x348
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_doubleobj: 0x50
-  __AUTH_CONST.__auth_got: 0xd18
+  __AUTH_CONST.__auth_got: 0xd28
   __AUTH.__objc_data: 0x2738
   __AUTH.__data: 0x38
   __DATA.__objc_ivar: 0x207c

   - /usr/lib/libprequelite.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 14630
-  Symbols:   24860
-  CStrings:  12410
+  Functions: 14638
+  Symbols:   24870
+  CStrings:  12415
 
Symbols:
+ -[PQLConnection(BRCAdditions) registerFunction:nArgs:directOnly:handler:error:]
+ GCC_except_table214
+ _NSFileProviderCloudDocsContainerIdentifier
+ ___br_reingest_cloudocs_container_fixup_block_invoke
+ _br_reingest_cloudocs_container_fixup
+ _br_update_tables_34_105
+ _brc_destroy_xfunc
+ _brc_invoke_xfunc
+ _objc_msgSend$crashIfUsedAfterClose
+ _objc_msgSend$errorForDB:
+ _objc_msgSend$registerFunction:nArgs:directOnly:handler:error:
+ _sqlite3_create_function_v2
+ _sqlite3_user_data
- -[PQLConnection(BRCAdditions) registerFunction:nArgs:handler:error:]
- _objc_msgSend$registerFunction:nArgs:handler:
- _objc_msgSend$registerFunction:nArgs:handler:error:
CStrings:
+ "-[PQLConnection(BRCAdditions) registerFunction:nArgs:directOnly:handler:error:]"
+ "[CRIT] Assertion failed: self.dbHandle%@"
+ "[DEBUG] Done force ingestion of the CloudDocs container to update its capabilities%@"
+ "[ERROR] Force ingestion of the CloudDocs container failed with error %@%@"
+ "br_reingest_cloudocs_container_fixup_block_invoke"
+ "connection is closed"
- "-[PQLConnection(BRCAdditions) registerFunction:nArgs:handler:error:]"
```
