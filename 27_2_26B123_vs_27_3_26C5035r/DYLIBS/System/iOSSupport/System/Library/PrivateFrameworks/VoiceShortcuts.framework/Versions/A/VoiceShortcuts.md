## VoiceShortcuts

> `/System/iOSSupport/System/Library/PrivateFrameworks/VoiceShortcuts.framework/Versions/A/VoiceShortcuts`

```diff

-5114.0.6.204.0
-  __TEXT.__text: 0x112654
-  __TEXT.__objc_methlist: 0x46dc
-  __TEXT.__const: 0x6318
+5203.0.1.0.0
+  __TEXT.__text: 0x113c40
+  __TEXT.__objc_methlist: 0x482c
+  __TEXT.__const: 0x6320
   __TEXT.__dlopen_cstrs: 0x12d
-  __TEXT.__constg_swiftt: 0x1f58
+  __TEXT.__constg_swiftt: 0x1f60
   __TEXT.__swift5_typeref: 0x3011
   __TEXT.__swift5_builtin: 0x140
   __TEXT.__swift5_reflstr: 0x1301

   __TEXT.__swift5_assocty: 0x618
   __TEXT.__swift5_proto: 0x3e8
   __TEXT.__swift5_types: 0x1e0
-  __TEXT.__cstring: 0xc3d7
+  __TEXT.__cstring: 0xc48a
   __TEXT.__swift5_capture: 0x2bf8
-  __TEXT.__oslogstring: 0xc98d
+  __TEXT.__oslogstring: 0xca69
   __TEXT.__swift_as_entry: 0x2c8
   __TEXT.__swift_as_ret: 0x2f4
   __TEXT.__swift_as_cont: 0x6a8
   __TEXT.__swift5_protos: 0x4c
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__gcc_except_tab: 0x760
+  __TEXT.__gcc_except_tab: 0x800
   __TEXT.__ustring: 0x44
-  __TEXT.__unwind_info: 0x53d8
+  __TEXT.__unwind_info: 0x5400
   __TEXT.__eh_frame: 0x8040
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1aa0
+  __DATA_CONST.__const: 0x1ad8
   __DATA_CONST.__objc_classlist: 0x290
   __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0x230
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3c78
+  __DATA_CONST.__objc_selrefs: 0x3d78
   __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_superrefs: 0x140
   __DATA_CONST.__objc_arraydata: 0x40
-  __DATA_CONST.__got: 0x1560
+  __DATA_CONST.__got: 0x1588
   __AUTH_CONST.__const: 0x9c38
-  __AUTH_CONST.__cfstring: 0x37a0
-  __AUTH_CONST.__objc_const: 0x81d0
+  __AUTH_CONST.__cfstring: 0x38a0
+  __AUTH_CONST.__objc_const: 0x8430
   __AUTH_CONST.__objc_intobj: 0xa8
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x1e78
+  __AUTH_CONST.__auth_got: 0x1ec8
   __AUTH.__objc_data: 0x3d8
   __AUTH.__data: 0x990
-  __DATA.__objc_ivar: 0x304
-  __DATA.__data: 0x1de0
+  __DATA.__objc_ivar: 0x338
+  __DATA.__data: 0x1df0
   __DATA.__bss: 0x3d90
   __DATA_DIRTY.__objc_data: 0x1340
   __DATA_DIRTY.__data: 0x2b80

   - /usr/lib/swift/libswift_DarwinFoundation3.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7332
-  Symbols:   6230
-  CStrings:  1901
+  Functions: 7370
+  Symbols:   6316
+  CStrings:  1910
 
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
+ GCC_except_table1069
+ GCC_except_table1075
+ GCC_except_table1077
+ GCC_except_table1126
+ GCC_except_table1165
+ GCC_except_table1171
+ GCC_except_table1183
+ GCC_except_table1189
+ GCC_except_table1199
+ GCC_except_table1205
+ GCC_except_table1220
+ GCC_except_table1224
+ GCC_except_table1242
+ GCC_except_table1246
+ GCC_except_table1260
+ GCC_except_table1262
+ GCC_except_table1266
+ GCC_except_table1284
+ GCC_except_table1287
+ GCC_except_table1301
+ GCC_except_table374
+ GCC_except_table397
+ GCC_except_table410
+ GCC_except_table484
+ GCC_except_table566
+ GCC_except_table590
+ GCC_except_table604
+ GCC_except_table761
+ GCC_except_table885
+ GCC_except_table901
+ GCC_except_table907
+ GCC_except_table909
+ GCC_except_table927
+ GCC_except_table967
+ GCC_except_table984
+ GCC_except_table988
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
+ ___79-[VCCKShortcutSyncCoordinator containerContainsRecordOfType:withTimeout:error:]_block_invoke_2
+ ___87-[VCCKShortcutSyncCoordinator syncVersionConsultingDatabase:withCloudKitTimeout:error:]_block_invoke
+ ___block_descriptor_40_e8_32w_e8_v12?0i8lw32l8
+ ___block_descriptor_48_e8_32s40r_e35_v24?0"CKQueryCursor"8"NSError"16lr40l8s32l8
+ ___block_descriptor_72_e8_32s40s48s56r64r_e29_v24?0"NSArray"8"NSError"16lr56l8s32l8s40l8s48l8r64l8
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
- GCC_except_table1044
- GCC_except_table1050
- GCC_except_table1052
- GCC_except_table1101
- GCC_except_table1137
- GCC_except_table1141
- GCC_except_table1155
- GCC_except_table1160
- GCC_except_table1170
- GCC_except_table1176
- GCC_except_table1190
- GCC_except_table1194
- GCC_except_table1212
- GCC_except_table1216
- GCC_except_table1230
- GCC_except_table1232
- GCC_except_table1236
- GCC_except_table1254
- GCC_except_table1257
- GCC_except_table1271
- GCC_except_table354
- GCC_except_table376
- GCC_except_table459
- GCC_except_table540
- GCC_except_table541
- GCC_except_table554
- GCC_except_table736
- GCC_except_table860
- GCC_except_table876
- GCC_except_table882
- GCC_except_table884
- GCC_except_table902
- GCC_except_table942
- GCC_except_table959
- GCC_except_table963
- ___61-[VCCKShortcutSyncCoordinator containerContainsRecordOfType:]_block_invoke
- ___61-[VCCKShortcutSyncCoordinator containerContainsRecordOfType:]_block_invoke_2
- ___64-[VCCKShortcutSyncCoordinator migrateToCoherenceSyncIfPossible:]_block_invoke
- ___block_descriptor_40_e8_32s_e35_v24?0"CKQueryCursor"8"NSError"16ls32l8
- ___block_descriptor_56_e8_32s40s48r_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8r48l8
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
