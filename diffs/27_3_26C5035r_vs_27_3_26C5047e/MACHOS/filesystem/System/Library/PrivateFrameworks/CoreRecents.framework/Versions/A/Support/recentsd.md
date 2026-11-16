## recentsd

> `/System/Library/PrivateFrameworks/CoreRecents.framework/Versions/A/Support/recentsd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1237.300.1.0.0
-  __TEXT.__text: 0x1720c
-  __TEXT.__auth_stubs: 0xa70
-  __TEXT.__objc_stubs: 0x3f60
-  __TEXT.__objc_methlist: 0x147c
-  __TEXT.__const: 0x114
-  __TEXT.__objc_methname: 0x3a87
-  __TEXT.__cstring: 0x46b2
+1237.300.2.0.0
+  __TEXT.__text: 0x18400
+  __TEXT.__auth_stubs: 0xab0
+  __TEXT.__objc_stubs: 0x4160
+  __TEXT.__objc_methlist: 0x1524
+  __TEXT.__const: 0x124
+  __TEXT.__objc_methname: 0x3d08
+  __TEXT.__cstring: 0x4783
   __TEXT.__objc_classname: 0x2fc
-  __TEXT.__objc_methtype: 0xaa5
-  __TEXT.__gcc_except_tab: 0x2e8
-  __TEXT.__oslogstring: 0x145e
-  __TEXT.__unwind_info: 0x9b0
+  __TEXT.__objc_methtype: 0xb1a
+  __TEXT.__gcc_except_tab: 0x34c
+  __TEXT.__oslogstring: 0x16cb
+  __TEXT.__unwind_info: 0xa00
   __DATA_CONST.__const: 0xbe0
   __DATA_CONST.__cfstring: 0x1ce0
   __DATA_CONST.__objc_classlist: 0xd8

   __DATA_CONST.__objc_intobj: 0x78
   __DATA_CONST.__objc_arraydata: 0x30
   __DATA_CONST.__objc_arrayobj: 0x30
-  __DATA_CONST.__auth_got: 0x548
-  __DATA_CONST.__got: 0x3a0
-  __DATA.__objc_const: 0x2330
-  __DATA.__objc_selrefs: 0x1208
-  __DATA.__objc_ivar: 0x174
+  __DATA_CONST.__auth_got: 0x568
+  __DATA_CONST.__got: 0x3b8
+  __DATA.__objc_const: 0x2460
+  __DATA.__objc_selrefs: 0x1298
+  __DATA.__objc_ivar: 0x198
   __DATA.__objc_data: 0x870
   __DATA.__data: 0x368
   __DATA.__bss: 0x80

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 603
-  Symbols:   292
-  CStrings:  1313
+  Functions: 622
+  Symbols:   299
+  CStrings:  1360
 
Symbols:
+ _NSPOSIXErrorDomain
+ _NSUnderlyingErrorKey
+ _OBJC_CLASS_$_NSProcessInfo
+ ___error
+ _sqlite3_extended_errcode
+ _sqlite3_system_errno
+ _statfs
CStrings:
+ " - volume is out of space"
+ "-[_CRRecentsLibrary _deleteRecentsWithRecentIDs:storeKeys:recentsDomain:deleteInUbiquitousStore:error:]"
+ "@24@0:8^{?=iiBBB}16"
+ "Another connection already replaced the damaged recents database, not deleting it again"
+ "B24@0:8^{sqlite3_stmt=}16"
+ "B24@0:8i16i20"
+ "B32@0:8@16^@24"
+ "B36@0:8@?16B24^@28"
+ "Could not delete %lu recent(s) from '%{public}@', leaving them in place"
+ "Could not open the recents database (%{public}s): sqlite error %d, system error %d (%{public}s), attempt %lu, trying again in %.0fs"
+ "Error %d (extended %d) on connection %p %{public}@: %{public}s"
+ "Error %d (extended %d) on connection %p %{public}@: %{public}s - system error %d (%{public}s)%{public}s"
+ "Error removing records for domain %{public}@: %{public}@"
+ "Migrating the recents database failed (sqlite error %d)"
+ "Opened the recents database after %lu failed attempts"
+ "Q32@0:8@16^B24"
+ "Q56@0:8@16@24@32@40^@48"
+ "SQLite error %d on the recents database, system error %d (%{public}s): %{public}s"
+ "TB,N,V_diskFull"
+ "The recents database is damaged, deleting it and creating a new one"
+ "Treating sqlite error %d as the volume being out of space: almost no free space left"
+ "Treating the failed migration as the volume being out of space: almost no free space left"
+ "_consecutiveOpenFailures"
+ "_currentRecoveryCount"
+ "_databasePropertyValueByKey:didRead:"
+ "_databaseUnavailableError"
+ "_databaseUnavailableErrorForDiskFull:"
+ "_deleteRecentsWithRecentIDs:storeKeys:recentsDomain:deleteInUbiquitousStore:error:"
+ "_diskFull"
+ "_isDiskFullError:systemErrno:"
+ "_lastOpenFailureWasDiskFull"
+ "_mayAttemptToOpenDatabase"
+ "_newOpenedConnectionReportingFailure:"
+ "_nextOpenAttemptTime"
+ "_noteDatabaseOpenFailed:"
+ "_noteDatabaseOpenSucceeded"
+ "_openErrorCode"
+ "_openStateLock"
+ "_openSystemErrno"
+ "_performTransaction:forWriting:error:"
+ "_recoveryCount"
+ "_recoveryLock"
+ "_removeDamagedDatabaseUnlessRecoveredSince:"
+ "_removeLocalRecordsForDomain:removeInUbiquitousStore:error:"
+ "_saveRecentContacts:error:"
+ "_stepToCompletion:"
+ "aborting"
+ "carrying on"
+ "diskFull"
+ "extendedErrorCode"
+ "fileExistsAtPath:"
+ "fileSystemRepresentation"
+ "lastSystemErrno"
+ "processInfo"
+ "recordContactEvents:recentsDomain:sendingAddress:source:error:"
+ "schema migration failed"
+ "see the sqlite error"
+ "setDiskFull:"
+ "systemUptime"
+ "the database is damaged, deleting it and aborting"
+ "the volume is out of space"
+ "the volume is out of space, failing the transaction"
+ "v28@0:8{?=iiBBB}16"
- "-[_CRRecentsLibrary _deleteRecentsWithRecentIDs:storeKeys:recentsDomain:deleteInUbiquitousStore:]"
- "Deleting recents database: SQLITE_CANTOPEN/PERM/READONLY/AUTH"
- "Deleting recents database: SQLITE_FULL (volume out of space)"
- "Deleting recents database: schema migration failed"
- "Error %d on connection %p %{public}@: %s"
- "Error %d on connection %p %{public}@: %s - I/O error %d (%s)"
- "Unclassified sqlite error %d opening recents database"
- "_abortForUnclassifiedSQLiteErrorCode:"
- "_deleteRecentsWithRecentIDs:storeKeys:recentsDomain:deleteInUbiquitousStore:"
- "_performTransaction:forWriting:"
- "_removeDatabaseForCannotOpenAndAbort"
- "_removeDatabaseForDiskFullAndAbort"
- "_removeDatabaseForMigrationFailureAndAbort"
- "nil != connection"
- "v28@0:8@?16B24"
- "v44@0:8@16@24@32B40"
```
