## VoiceShortcuts

> `/System/Library/PrivateFrameworks/VoiceShortcuts.framework/Versions/A/VoiceShortcuts`

```diff

-5114.0.6.204.0
-  __TEXT.__text: 0x12e888
-  __TEXT.__objc_methlist: 0x49dc
-  __TEXT.__const: 0x6850
+5203.0.1.0.0
+  __TEXT.__text: 0x130050
+  __TEXT.__objc_methlist: 0x4b2c
+  __TEXT.__const: 0x6858
   __TEXT.__dlopen_cstrs: 0x25a
-  __TEXT.__constg_swiftt: 0x21b0
+  __TEXT.__constg_swiftt: 0x21b8
   __TEXT.__swift5_typeref: 0x331d
   __TEXT.__swift5_builtin: 0x154
   __TEXT.__swift5_reflstr: 0x14e1

   __TEXT.__swift5_assocty: 0x648
   __TEXT.__swift5_proto: 0x418
   __TEXT.__swift5_types: 0x1fc
-  __TEXT.__cstring: 0xd24a
+  __TEXT.__cstring: 0xd2fd
   __TEXT.__swift5_capture: 0x2e84
-  __TEXT.__oslogstring: 0xe694
+  __TEXT.__oslogstring: 0xe770
   __TEXT.__swift_as_entry: 0x2f0
   __TEXT.__swift_as_ret: 0x300
   __TEXT.__swift_as_cont: 0x6d4
   __TEXT.__swift5_protos: 0x4c
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__gcc_except_tab: 0x840
+  __TEXT.__gcc_except_tab: 0x8e0
   __TEXT.__ustring: 0xf0
-  __TEXT.__unwind_info: 0x58e8
+  __TEXT.__unwind_info: 0x5908
   __TEXT.__eh_frame: 0x8304
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x888
+  __DATA_CONST.__const: 0x898
   __DATA_CONST.__objc_classlist: 0x2d0
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x218
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3f78
+  __DATA_CONST.__objc_selrefs: 0x4078
   __DATA_CONST.__objc_protorefs: 0xa8
   __DATA_CONST.__objc_superrefs: 0x158
   __DATA_CONST.__objc_arraydata: 0x88
-  __DATA_CONST.__got: 0x16f0
-  __AUTH_CONST.__const: 0xbbb8
-  __AUTH_CONST.__cfstring: 0x3ce0
-  __AUTH_CONST.__objc_const: 0x8a10
+  __DATA_CONST.__got: 0x1718
+  __AUTH_CONST.__const: 0xbbe8
+  __AUTH_CONST.__cfstring: 0x3de0
+  __AUTH_CONST.__objc_const: 0x8c70
   __AUTH_CONST.__objc_intobj: 0xa8
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0x1e80
+  __AUTH_CONST.__auth_got: 0x1ed0
   __AUTH.__objc_data: 0x5a8
   __AUTH.__data: 0x9e0
-  __DATA.__objc_ivar: 0x32c
-  __DATA.__data: 0x1d30
+  __DATA.__objc_ivar: 0x360
+  __DATA.__data: 0x1d40
   __DATA.__bss: 0x3f40
   __DATA_DIRTY.__objc_data: 0x1480
   __DATA_DIRTY.__data: 0x3158

   - /usr/lib/swift/libswift_DarwinFoundation3.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7689
-  Symbols:   6449
-  CStrings:  2112
+  Functions: 7728
+  Symbols:   6537
+  CStrings:  2121
 
Symbols:
+ -[VCCKShortcutSyncCoordinator checkIfExistingCoherenceSyncRecordsArePresentWithTimeout:error:]
+ -[VCCKShortcutSyncCoordinator containerContainsRecordOfType:withTimeout:error:]
+ -[VCCKShortcutSyncCoordinator handleSyncReadinessChange]
+ -[VCCKShortcutSyncCoordinator initWithDatabaseProvider:daemonTaskScheduler:cloudKitContainer:operationRunner:]
+ -[VCCKShortcutSyncCoordinator lastSyncVersionCheckFailed]
+ -[VCCKShortcutSyncCoordinator operationRunner]
+ -[VCCKShortcutSyncCoordinator setLastSyncVersionCheckFailed:]
+ -[VCCKShortcutSyncCoordinator syncVersionConsultingDatabase:withCloudKitTimeout:error:]
+ -[VCCKShortcutSyncService fetchCycleChanged]
+ -[VCCKShortcutSyncService fetchCycleDeleted]
+ -[VCCKShortcutSyncService fetchCycleFailed]
+ -[VCCKShortcutSyncService fetchCycleFirstError]
+ -[VCCKShortcutSyncService fetchCycleNotApplied]
+ -[VCCKShortcutSyncService inFetchCycle]
+ -[VCCKShortcutSyncService noteRecordOutcome:recordType:identifier:reason:]
+ -[VCCKShortcutSyncService sendCycleChanged]
+ -[VCCKShortcutSyncService sendCycleDeleted]
+ -[VCCKShortcutSyncService sendCycleFailed]
+ -[VCCKShortcutSyncService sendCycleFirstError]
+ -[VCCKShortcutSyncService setFetchCycleChanged:]
+ -[VCCKShortcutSyncService setFetchCycleDeleted:]
+ -[VCCKShortcutSyncService setFetchCycleFailed:]
+ -[VCCKShortcutSyncService setFetchCycleFirstError:]
+ -[VCCKShortcutSyncService setFetchCycleNotApplied:]
+ -[VCCKShortcutSyncService setInFetchCycle:]
+ -[VCCKShortcutSyncService setSendCycleChanged:]
+ -[VCCKShortcutSyncService setSendCycleDeleted:]
+ -[VCCKShortcutSyncService setSendCycleFailed:]
+ -[VCCKShortcutSyncService setSendCycleFirstError:]
+ -[VCCKShortcutSyncService startObservingSyncNowRequests]
+ -[VCCKShortcutSyncService stopObservingSyncNowRequests]
+ GCC_except_table1006
+ GCC_except_table1046
+ GCC_except_table1063
+ GCC_except_table1069
+ GCC_except_table1091
+ GCC_except_table1162
+ GCC_except_table1170
+ GCC_except_table1199
+ GCC_except_table1226
+ GCC_except_table1244
+ GCC_except_table1249
+ GCC_except_table1252
+ GCC_except_table1254
+ GCC_except_table1285
+ GCC_except_table1291
+ GCC_except_table1305
+ GCC_except_table1312
+ GCC_except_table1330
+ GCC_except_table1352
+ GCC_except_table1356
+ GCC_except_table1374
+ GCC_except_table1378
+ GCC_except_table1392
+ GCC_except_table1394
+ GCC_except_table1398
+ GCC_except_table1418
+ GCC_except_table1421
+ GCC_except_table1435
+ GCC_except_table396
+ GCC_except_table419
+ GCC_except_table434
+ GCC_except_table510
+ GCC_except_table589
+ GCC_except_table590
+ GCC_except_table604
+ GCC_except_table615
+ GCC_except_table633
+ GCC_except_table828
+ GCC_except_table950
+ GCC_except_table976
+ GCC_except_table982
+ GCC_except_table984
+ _CKStringFromAccountStatus
+ _OBJC_CLASS_$_CKSyncEngineDidFetchRecordZoneChangesEvent
+ _OBJC_IVAR_$_VCCKShortcutSyncCoordinator._lastSyncVersionCheckFailed
+ _OBJC_IVAR_$_VCCKShortcutSyncCoordinator._operationRunner
+ _OBJC_IVAR_$_VCCKShortcutSyncService._fetchCycleChanged
+ _OBJC_IVAR_$_VCCKShortcutSyncService._fetchCycleDeleted
+ _OBJC_IVAR_$_VCCKShortcutSyncService._fetchCycleFailed
+ _OBJC_IVAR_$_VCCKShortcutSyncService._fetchCycleFirstError
+ _OBJC_IVAR_$_VCCKShortcutSyncService._fetchCycleNotApplied
+ _OBJC_IVAR_$_VCCKShortcutSyncService._inFetchCycle
+ _OBJC_IVAR_$_VCCKShortcutSyncService._sendCycleChanged
+ _OBJC_IVAR_$_VCCKShortcutSyncService._sendCycleDeleted
+ _OBJC_IVAR_$_VCCKShortcutSyncService._sendCycleFailed
+ _OBJC_IVAR_$_VCCKShortcutSyncService._sendCycleFirstError
+ _OBJC_IVAR_$_VCCKShortcutSyncService._syncNowToken
+ _SecTaskCopySigningIdentifier
+ _WFCloudKitSyncVersionCoherence
+ _WFCloudKitSyncVersionLegacy
+ _WFSyncNowRequested
+ ___56-[VCCKShortcutSyncService startObservingSyncNowRequests]_block_invoke
+ ___79-[VCCKShortcutSyncCoordinator containerContainsRecordOfType:withTimeout:error:]_block_invoke
+ ___87-[VCCKShortcutSyncCoordinator syncVersionConsultingDatabase:withCloudKitTimeout:error:]_block_invoke
+ ___block_descriptor_40_e8_32w_e8_v12?0i8l
+ ___block_descriptor_48_e8_32s40r_e35_v24?0"CKQueryCursor"8"NSError"16l
+ ___block_descriptor_72_e8_32s40s48s56r64r_e29_v24?0"NSArray"8"NSError"16l
+ ___copy_helper_block_e8_32s40s48s56r64r
+ ___destroy_helper_block_e8_32s40s48s56r64r
+ ___kCFBooleanFalse
+ __dispatch_main_q
+ _notify_cancel
+ _notify_register_dispatch
+ _objc_msgSend$cancel
+ _objc_msgSend$checkIfExistingCoherenceSyncRecordsArePresentWithTimeout:error:
+ _objc_msgSend$containerContainsRecordOfType:withTimeout:error:
+ _objc_msgSend$fetchCycleChanged
+ _objc_msgSend$fetchCycleDeleted
+ _objc_msgSend$fetchCycleFailed
+ _objc_msgSend$fetchCycleFirstError
+ _objc_msgSend$fetchCycleNotApplied
+ _objc_msgSend$fetchDeviceRecordsInDatabase:completion:
+ _objc_msgSend$handleSyncReadinessChange
+ _objc_msgSend$inFetchCycle
+ _objc_msgSend$initWithDatabaseProvider:daemonTaskScheduler:cloudKitContainer:operationRunner:
+ _objc_msgSend$lastSyncVersionCheckFailed
+ _objc_msgSend$logDeviceRecords:responseTime:
+ _objc_msgSend$logRecordOutcome:recordType:identifier:reason:
+ _objc_msgSend$logSyncCycleBegin:source:
+ _objc_msgSend$logSyncCycleEnd:source:changed:deleted:failed:notApplied:firstError:
+ _objc_msgSend$noteRecordOutcome:recordType:identifier:reason:
+ _objc_msgSend$operationRunner
+ _objc_msgSend$sendCycleChanged
+ _objc_msgSend$sendCycleDeleted
+ _objc_msgSend$sendCycleFailed
+ _objc_msgSend$sendCycleFirstError
+ _objc_msgSend$setFetchCycleChanged:
+ _objc_msgSend$setFetchCycleDeleted:
+ _objc_msgSend$setFetchCycleFailed:
+ _objc_msgSend$setFetchCycleFirstError:
+ _objc_msgSend$setFetchCycleNotApplied:
+ _objc_msgSend$setInFetchCycle:
+ _objc_msgSend$setLastSyncVersionCheckFailed:
+ _objc_msgSend$setSendCycleChanged:
+ _objc_msgSend$setSendCycleDeleted:
+ _objc_msgSend$setSendCycleFailed:
+ _objc_msgSend$setSendCycleFirstError:
+ _objc_msgSend$startObservingSyncNowRequests
+ _objc_msgSend$stopObservingSyncNowRequests
+ _objc_msgSend$syncVersionConsultingDatabase:withCloudKitTimeout:error:
- -[VCCKShortcutSyncCoordinator checkIfExistingCoherenceSyncRecordsArePresent]
- -[VCCKShortcutSyncCoordinator containerContainsRecordOfType:]
- -[VCCKShortcutSyncCoordinator migrateToCoherenceSyncIfPossible:]
- GCC_except_table1019
- GCC_except_table1038
- GCC_except_table1044
- GCC_except_table1066
- GCC_except_table1137
- GCC_except_table1145
- GCC_except_table1149
- GCC_except_table1201
- GCC_except_table1219
- GCC_except_table1224
- GCC_except_table1227
- GCC_except_table1229
- GCC_except_table1257
- GCC_except_table1261
- GCC_except_table1275
- GCC_except_table1281
- GCC_except_table1293
- GCC_except_table1299
- GCC_except_table1320
- GCC_except_table1342
- GCC_except_table1346
- GCC_except_table1360
- GCC_except_table1362
- GCC_except_table1366
- GCC_except_table1386
- GCC_except_table1389
- GCC_except_table1403
- GCC_except_table376
- GCC_except_table398
- GCC_except_table483
- GCC_except_table562
- GCC_except_table563
- GCC_except_table577
- GCC_except_table588
- GCC_except_table606
- GCC_except_table801
- GCC_except_table923
- GCC_except_table949
- GCC_except_table955
- GCC_except_table957
- GCC_except_table979
- ___61-[VCCKShortcutSyncCoordinator containerContainsRecordOfType:]_block_invoke
- ___64-[VCCKShortcutSyncCoordinator migrateToCoherenceSyncIfPossible:]_block_invoke
- ___block_descriptor_40_e8_32s_e35_v24?0"CKQueryCursor"8"NSError"16l
- ___block_descriptor_56_e8_32s40s48r_e29_v24?0"NSArray"8"NSError"16l
- _objc_msgSend$checkIfExistingCoherenceSyncRecordsArePresent
- _objc_msgSend$containerContainsRecordOfType:
- _objc_msgSend$fetchDeviceRecordsInContainer:completion:
- _objc_msgSend$logDeviceRecords:
- _objc_msgSend$migrateToCoherenceSyncIfPossible:
CStrings:
+ "%s Application moved into foreground, updating account status or sync service"
+ "%s Coherence Sync migration check hit an error: %{public}@"
+ "%s Successfully fetched iCloud account info: %@, status = %@"
+ "%s Sync now requested from the debug menu, performing immediate sync"
+ "%s iCloud account changed, resetting flags for sync availability."
+ "-[VCCKShortcutSyncCoordinator syncVersionConsultingDatabase:withCloudKitTimeout:error:]"
+ "-[VCCKShortcutSyncService startObservingSyncNowRequests]_block_invoke"
+ "Coherence Sync migration check hit an error choosing sync version. %@:%ld"
+ "Device records response was unexpectedly empty."
+ "Did not get a response to device records request."
+ "Did not get a response to request."
+ "Ignoring indexer prewarm request from %{public}s: feature flag disabled"
+ "Indexer prewarm requested by %{public}s"
+ "Unable to fetch iCloud account details"
+ "coherence"
+ "could not safely choose sync 1 or sync 2"
+ "folder"
+ "legacy"
+ "v12@?0i8"
+ "workflow"
- "%s Application moved into foreground, updating account status"
- "%s Error fetching device records: %{public}@"
- "%s Successfully fetched iCloud account info: %@, status = %ld"
- "%s iCloud account changed, resetting flags for sync unavailable message"
- "-[VCCKShortcutSyncCoordinator migrateToCoherenceSyncIfPossible:]"
- "-[VCCKShortcutSyncCoordinator migrateToCoherenceSyncIfPossible:]_block_invoke"
- "conflicted stored value: "
- "conflicted workflow: %@ (reason: %@)"
- "held stored value pending MCV: "
- "ignored stored value: "
- "ignored workflow: %@ (reason: %@)"
```
