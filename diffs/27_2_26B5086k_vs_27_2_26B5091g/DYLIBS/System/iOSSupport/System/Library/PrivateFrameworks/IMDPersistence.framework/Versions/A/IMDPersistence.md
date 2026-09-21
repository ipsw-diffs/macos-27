## IMDPersistence

> `/System/iOSSupport/System/Library/PrivateFrameworks/IMDPersistence.framework/Versions/A/IMDPersistence`

```diff

-1491.200.63.0.0
-  __TEXT.__text: 0x2ea580
-  __TEXT.__objc_methlist: 0xa3ac
+1491.200.73.0.0
+  __TEXT.__text: 0x2eaee0
+  __TEXT.__objc_methlist: 0xa3b4
   __TEXT.__const: 0xc198
-  __TEXT.__cstring: 0x5d984
-  __TEXT.__oslogstring: 0x3bda4
-  __TEXT.__gcc_except_tab: 0xc610
+  __TEXT.__cstring: 0x5dae4
+  __TEXT.__oslogstring: 0x3bfe4
+  __TEXT.__gcc_except_tab: 0xc664
   __TEXT.__ustring: 0x434
   __TEXT.__dlopen_cstrs: 0x21a
   __TEXT.__swift5_typeref: 0x5190

   __TEXT.__swift_as_cont: 0x364
   __TEXT.__swift5_mpenum: 0x44
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__unwind_info: 0xd3f8
+  __TEXT.__unwind_info: 0xd410
   __TEXT.__eh_frame: 0x992c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6498
+  __DATA_CONST.__const: 0x64c0
   __DATA_CONST.__objc_classlist: 0x6c8
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x300
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6ab0
+  __DATA_CONST.__objc_selrefs: 0x6ab8
   __DATA_CONST.__objc_protorefs: 0x138
   __DATA_CONST.__objc_superrefs: 0x228
   __DATA_CONST.__objc_arraydata: 0x2c0
   __DATA_CONST.__got: 0x1bc0
-  __AUTH_CONST.__const: 0xe048
-  __AUTH_CONST.__cfstring: 0x12f40
+  __AUTH_CONST.__const: 0xe068
+  __AUTH_CONST.__cfstring: 0x13040
   __AUTH_CONST.__objc_const: 0x137b0
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x2900
-  __AUTH.__objc_data: 0xff0
-  __AUTH.__data: 0x1ce0
+  __AUTH.__objc_data: 0xf78
+  __AUTH.__data: 0x1b80
   __DATA.__objc_ivar: 0x564
-  __DATA.__data: 0x36a8
-  __DATA.__bss: 0x6088
-  __DATA.__common: 0x210
-  __DATA_DIRTY.__objc_data: 0x2f78
-  __DATA_DIRTY.__data: 0x64c0
-  __DATA_DIRTY.__bss: 0x2d70
-  __DATA_DIRTY.__common: 0x160
+  __DATA.__data: 0x35a8
+  __DATA.__bss: 0x5e08
+  __DATA.__common: 0x1f8
+  __DATA_DIRTY.__objc_data: 0x2ff0
+  __DATA_DIRTY.__data: 0x66e0
+  __DATA_DIRTY.__bss: 0x2ff0
+  __DATA_DIRTY.__common: 0x178
   - /System/Library/Frameworks/AppIntents.framework/Versions/A/AppIntents
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13661
+  Functions: 13668
   Symbols:   2845
-  CStrings:  7479
+  CStrings:  7491
 
CStrings:
+ "Alert watermark dated in the future: %@"
+ "BOOL __IMDDatabasePerformOneMigration(int, CSDBSqliteDatabase *, CSDBSqliteConnection *, int, int *, NSError *__autoreleasing *, __strong MigratorBlock)"
+ "Copying %lu attachment download info entries beforeDate: %@ earliestDate: %lld limit: %lld"
+ "IMDNotificationsController.futureAlertWatermark"
+ "Last alerted failed message date was stored in the future: [%lld]-[%@], now: [%lld]-[%@]. Clamping to now, which restores alerting for failures dated before it."
+ "Last alerted message date was stored in the future: [%lld]-[%@], now: [%lld]-[%@]. Clamping to now, which restores alerting for messages dated before it."
+ "Notifications"
+ "Refusing to advance last alerted failed message date to a future date: [%lld]-[%@], now: [%lld]-[%@]. Clamping it to now instead."
+ "Refusing to advance last alerted message date to a future date: [%lld]-[%@], now: [%lld]-[%@]. Clamping it to now instead."
+ "SELECT a.ROWID, a.guid, a.total_bytes, a.ck_record_id, m.date FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 AND IFNULL(m.date, 0) >= ? ORDER BY m.date DESC, a.ROWID ASC LIMIT ? "
+ "SELECT a.ROWID, a.guid, a.total_bytes, a.ck_record_id, m.date FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 AND m.date < ? AND IFNULL(m.date, 0) >= ? ORDER BY m.date DESC, a.ROWID ASC LIMIT ? "
+ "advance-failed"
+ "advance-received"
+ "earliestDate"
+ "setupFirstLoad-failed"
+ "setupFirstLoad-received"
+ "void IMDMessageRecordAnonymizedUpdate(IMDMessageRecordRef, CFStringRef, CFDataRef, CFStringRef, CFStringRef, CFStringRef, CFDataRef, CFDataRef, CFStringRef, BOOL, BOOL, CFStringRef, CFStringRef, CFStringRef)"
+ "void _IMDPerformBlock(__strong dispatch_block_t, IMFileLocation_t *)"
+ "void _IMDPerformBlockWithDelay(NSTimeInterval, __strong dispatch_block_t, IMFileLocation_t *)"
+ "void _IMDPerformLockedConnectionBlock(__strong CSDBLockedConnection, IMFileLocation_t *)"
+ "void _IMDPerformLockedDatabaseBlock(__strong CSDBLockedDatabase, IMFileLocation_t *)"
+ "void _IMDPerformLockedMessageStoreBlock(__strong CSDBLockedRecordStore, IMFileLocation_t *)"
+ "void _IMDPerformLockedMessageStoreBlockWithoutInitialize(__strong CSDBLockedRecordStore, IMFileLocation_t *)"
+ "void _IMDPerformLockedStatementBlockWithQuery(CFStringRef, __strong CSDBLockedStatement, IMFileLocation_t *)"
- "BOOL __IMDDatabasePerformOneMigration(int, CSDBSqliteDatabase *, CSDBSqliteConnection *, int, int *, NSError **, MigratorBlock)"
- "Copying %lu attachment download info entries beforeDate: %@ limit: %lld"
- "SELECT a.ROWID, a.guid, a.total_bytes, a.ck_record_id, m.date FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 AND m.date < ? ORDER BY m.date DESC, a.ROWID ASC LIMIT ? "
- "SELECT a.ROWID, a.guid, a.total_bytes, a.ck_record_id, m.date FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 ORDER BY m.date DESC, a.ROWID ASC LIMIT ? "
- "void IMDMessageRecordAnonymizedUpdate(IMDMessageRecordRef, CFStringRef, CFDataRef, CFStringRef, CFStringRef, CFStringRef, CFDataRef, CFDataRef, CFStringRef, BOOL, CFStringRef, CFStringRef, CFStringRef)"
- "void _IMDPerformBlock(dispatch_block_t, IMFileLocation_t *)"
- "void _IMDPerformBlockWithDelay(NSTimeInterval, dispatch_block_t, IMFileLocation_t *)"
- "void _IMDPerformLockedConnectionBlock(CSDBLockedConnection, IMFileLocation_t *)"
- "void _IMDPerformLockedDatabaseBlock(CSDBLockedDatabase, IMFileLocation_t *)"
- "void _IMDPerformLockedMessageStoreBlock(CSDBLockedRecordStore, IMFileLocation_t *)"
- "void _IMDPerformLockedMessageStoreBlockWithoutInitialize(CSDBLockedRecordStore, IMFileLocation_t *)"
- "void _IMDPerformLockedStatementBlockWithQuery(CFStringRef, CSDBLockedStatement, IMFileLocation_t *)"
```
