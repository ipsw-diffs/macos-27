## CloudKitDaemon

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/Versions/A/CloudKitDaemon`

```diff

-2720.14.0.0.0
-  __TEXT.__text: 0x408934
-  __TEXT.__objc_methlist: 0x316cc
-  __TEXT.__const: 0x4e18
+2720.15.0.0.0
+  __TEXT.__text: 0x40a60c
+  __TEXT.__objc_methlist: 0x31784
+  __TEXT.__const: 0x4e20
   __TEXT.__swift5_typeref: 0x21a1
-  __TEXT.__oslogstring: 0x32ad4
+  __TEXT.__oslogstring: 0x32c68
   __TEXT.__swift5_capture: 0x918
   __TEXT.__constg_swiftt: 0x1ac0
   __TEXT.__swift5_reflstr: 0x1136

   __TEXT.__swift_as_ret: 0x16c
   __TEXT.__swift_as_cont: 0x23c
   __TEXT.__swift5_protos: 0x38
-  __TEXT.__cstring: 0x2b29c
+  __TEXT.__cstring: 0x2b513
   __TEXT.__swift5_mpenum: 0x1c
-  __TEXT.__gcc_except_tab: 0xc91c
+  __TEXT.__gcc_except_tab: 0xca14
   __TEXT.__ustring: 0x2c
-  __TEXT.__unwind_info: 0xeae0
+  __TEXT.__unwind_info: 0xeb50
   __TEXT.__eh_frame: 0x3ba8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x148
   __DATA_CONST.__objc_protolist: 0x220
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x130c0
+  __DATA_CONST.__objc_selrefs: 0x13140
   __DATA_CONST.__objc_protorefs: 0xa0
   __DATA_CONST.__objc_superrefs: 0x13c0
   __DATA_CONST.__objc_arraydata: 0x1558
   __DATA_CONST.__got: 0x2088
-  __AUTH_CONST.__const: 0xdb68
-  __AUTH_CONST.__cfstring: 0x237a0
-  __AUTH_CONST.__objc_const: 0x4acc8
+  __AUTH_CONST.__const: 0xdba8
+  __AUTH_CONST.__cfstring: 0x238e0
+  __AUTH_CONST.__objc_const: 0x4ad88
   __AUTH_CONST.__objc_intobj: 0xcd8
   __AUTH_CONST.__objc_arrayobj: 0x390
   __AUTH_CONST.__objc_dictobj: 0xbe0
   __AUTH_CONST.__auth_got: 0x2110
-  __AUTH.__objc_data: 0x5410
-  __AUTH.__data: 0x5d8
-  __DATA.__objc_ivar: 0x1a88
-  __DATA.__data: 0x1ef0
-  __DATA.__bss: 0x3220
+  __AUTH.__objc_data: 0x5258
+  __AUTH.__data: 0x5b0
+  __DATA.__objc_ivar: 0x1a8c
+  __DATA.__data: 0x1ee0
+  __DATA.__bss: 0x31a0
   __DATA.__common: 0xa0
-  __DATA_DIRTY.__objc_ivar: 0x1974
-  __DATA_DIRTY.__objc_data: 0x8378
-  __DATA_DIRTY.__data: 0x2248
-  __DATA_DIRTY.__bss: 0x3880
+  __DATA_DIRTY.__objc_ivar: 0x1980
+  __DATA_DIRTY.__objc_data: 0x8530
+  __DATA_DIRTY.__data: 0x2278
+  __DATA_DIRTY.__bss: 0x3900
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 21151
+  Functions: 21176
   Symbols:   2964
-  CStrings:  8485
+  CStrings:  8499
 
CStrings:
+ "Couldn't decrypt ancestor share %@: %@"
+ "Couldn't decrypt the share PCS for fetched zone %@: %@"
+ "Couldn't decrypt the share PCS of zone %@"
+ "Couldn't decrypt the zone PCS for fetched zone %@"
+ "Couldn't decrypt the zone PCS for fetched zone %@: %@"
+ "Couldn't decrypt the zoneish PCS for zone %@"
+ "Couldn't spawn an operation to decrypt fetched ancestor shares"
+ "Decrypting record %@ with the zone PCS supplied for zone %@ instead of fetching it"
+ "FailFirstDecryptWithSuppliedZonePCS"
+ "FailIfZonePCSFetchNeededToDecryptRecord"
+ "Failed to decrypt publicPCS for share %@ on zone %@ using invitedPCS"
+ "Fetch operation was deallocated before its ancestor chain could be wired"
+ "Fetch operation was deallocated before its ancestor shares could be decrypted"
+ "Fetch operation was deallocated before zone %@ could be decrypted"
+ "Fetched an ancestor zone without a zoneID"
+ "Fetched discontinuous ancestors for zone %@: zone %@ has parent %@, which is not the next zone returned, %@"
+ "Missing decrypted share PCS for fetched zone %@; rolling its parent requires the share's invitedPCS"
+ "Missing decrypted share PCS for zone %@"
+ "Missing decrypted zonePCS for fetched zone %@; rolling requires every ancestor zone's PCS"
+ "Missing decrypted zonePCS for zone %@"
+ "Record %@ needed a zone PCS fetch to decrypt, which this test forbids"
+ "Record %@ was failed on its supplied zone PCS by a test hook"
+ "Skipping ancestor PCS processing for zones %@ because encryption is disabled"
+ "Supplied zone PCS for zone %@ has no zoneish PCS but record %@ needs one. Fetching instead"
+ "v40@?0@\"CKRecordZoneID\"8@\"NSArray\"16@\"NSDictionary\"24@\"NSError\"32"
- "Could not decrypt zonePCS for zone %@"
- "Could not decrypt zoneishPCS for zone %@. "
- "Failed to decrypt invitedPCS for share %@ on zone %@ using parent zonePCS. Error:%@"
- "Failed to decrypt publicPCS for share %@ using invitedPCS %@"
- "Failed to decrypt publicPCS for share %@ using invitedPCS %@. Error %@."
- "Fetched ancestor zone is not continuous. Last zone: %@. Last zone's parent ID %@ does not match the current zoneID %@"
- "Fetched discontinuous ancestor array for leaf zone %@. Ancestors:%@"
- "Fetched zone %@ lacks protectionData."
- "We don't have zone PCS data to decrypt for zone %@"
- "Zone:%@. Parent:%@"
- "com.apple.cloudkit.processAncestors"
```
