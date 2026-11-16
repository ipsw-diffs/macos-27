## VoiceShortcuts

> `/System/Library/PrivateFrameworks/VoiceShortcuts.framework/Versions/A/VoiceShortcuts`

```diff

-5203.0.1.0.0
-  __TEXT.__text: 0x130050
-  __TEXT.__objc_methlist: 0x4b2c
+5206.0.5.0.0
+  __TEXT.__text: 0x133580
+  __TEXT.__objc_methlist: 0x4b6c
   __TEXT.__const: 0x6858
   __TEXT.__dlopen_cstrs: 0x25a
   __TEXT.__constg_swiftt: 0x21b8
-  __TEXT.__swift5_typeref: 0x331d
+  __TEXT.__swift5_typeref: 0x337f
+  __TEXT.__swift5_reflstr: 0x1521
+  __TEXT.__swift5_fieldmd: 0x1800
   __TEXT.__swift5_builtin: 0x154
-  __TEXT.__swift5_reflstr: 0x14e1
-  __TEXT.__swift5_fieldmd: 0x17e8
   __TEXT.__swift5_assocty: 0x648
   __TEXT.__swift5_proto: 0x418
   __TEXT.__swift5_types: 0x1fc
-  __TEXT.__cstring: 0xd2fd
-  __TEXT.__swift5_capture: 0x2e84
-  __TEXT.__oslogstring: 0xe770
+  __TEXT.__cstring: 0xd682
+  __TEXT.__swift5_capture: 0x2fa8
+  __TEXT.__oslogstring: 0xe9b1
   __TEXT.__swift_as_entry: 0x2f0
   __TEXT.__swift_as_ret: 0x300
   __TEXT.__swift_as_cont: 0x6d4
   __TEXT.__swift5_protos: 0x4c
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__gcc_except_tab: 0x8e0
+  __TEXT.__gcc_except_tab: 0x8dc
   __TEXT.__ustring: 0xf0
-  __TEXT.__unwind_info: 0x5908
-  __TEXT.__eh_frame: 0x8304
+  __TEXT.__unwind_info: 0x5978
+  __TEXT.__eh_frame: 0x834c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x218
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4078
+  __DATA_CONST.__objc_selrefs: 0x4058
   __DATA_CONST.__objc_protorefs: 0xa8
   __DATA_CONST.__objc_superrefs: 0x158
   __DATA_CONST.__objc_arraydata: 0x88
-  __DATA_CONST.__got: 0x1718
-  __AUTH_CONST.__const: 0xbbe8
-  __AUTH_CONST.__cfstring: 0x3de0
-  __AUTH_CONST.__objc_const: 0x8c70
+  __DATA_CONST.__got: 0x1708
+  __AUTH_CONST.__const: 0xbf10
+  __AUTH_CONST.__cfstring: 0x3f00
+  __AUTH_CONST.__objc_const: 0x8cf0
   __AUTH_CONST.__objc_intobj: 0xa8
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x1ed0
   __AUTH.__objc_data: 0x5a8
-  __AUTH.__data: 0x9e0
-  __DATA.__objc_ivar: 0x360
-  __DATA.__data: 0x1d40
+  __AUTH.__data: 0x9d8
+  __DATA.__objc_ivar: 0x368
+  __DATA.__data: 0x1d58
   __DATA.__bss: 0x3f40
   __DATA_DIRTY.__objc_data: 0x1480
-  __DATA_DIRTY.__data: 0x3158
+  __DATA_DIRTY.__data: 0x3108
   __DATA_DIRTY.__crash_info: 0x148
   __DATA_DIRTY.__bss: 0x3810
   __DATA_DIRTY.__common: 0x38

   - /usr/lib/swift/libswiftOSLog.dylib
   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftQuartzCore.dylib
-  - /usr/lib/swift/libswiftRegexBuilder.dylib
   - /usr/lib/swift/libswiftSpatial.dylib
   - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib
   - /usr/lib/swift/libswiftXPC.dylib

   - /usr/lib/swift/libswift_DarwinFoundation3.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7728
-  Symbols:   6537
-  CStrings:  2121
+  Functions: 7821
+  Symbols:   6526
+  CStrings:  2145
 
Symbols:
+ +[VCDaemonDatabaseProvider loadActionKit]
+ -[VCCKShortcutSyncCoordinator walrusStatus]
+ -[VCCKShortcutSyncService encryptedSchemaVersion]
+ -[VCCKShortcutSyncService initWithContainer:database:daemonTaskScheduler:applicationObserver:debuggingOptions:logger:encryptedSchemaVersion:]
+ -[VCCKShortcutSyncService sendChangedWorkflowsForEventName:]
+ -[VCCKShortcutSyncService setEncryptedSchemaVersion:]
+ -[VCCKShortcutSyncService updateEncryptedSchemaVersion:]
+ -[WFConfiguredSystemActionMigrator updateActionsUsingTransform:]
+ GCC_except_table1010
+ GCC_except_table1050
+ GCC_except_table1067
+ GCC_except_table1073
+ GCC_except_table1097
+ GCC_except_table1168
+ GCC_except_table1176
+ GCC_except_table1180
+ GCC_except_table1205
+ GCC_except_table1232
+ GCC_except_table1250
+ GCC_except_table1255
+ GCC_except_table1258
+ GCC_except_table1260
+ GCC_except_table1292
+ GCC_except_table1298
+ GCC_except_table1319
+ GCC_except_table1331
+ GCC_except_table1336
+ GCC_except_table1358
+ GCC_except_table1362
+ GCC_except_table1380
+ GCC_except_table1384
+ GCC_except_table1400
+ GCC_except_table1404
+ GCC_except_table1424
+ GCC_except_table1427
+ GCC_except_table1441
+ GCC_except_table398
+ GCC_except_table424
+ GCC_except_table439
+ GCC_except_table515
+ GCC_except_table593
+ GCC_except_table594
+ GCC_except_table608
+ GCC_except_table619
+ GCC_except_table637
+ GCC_except_table832
+ GCC_except_table954
+ GCC_except_table980
+ GCC_except_table986
+ GCC_except_table988
+ _OBJC_IVAR_$_VCCKShortcutSyncCoordinator._walrusStatus
+ _OBJC_IVAR_$_VCCKShortcutSyncService._encryptedSchemaVersion
+ _WFDebugViewExpectedEncryptedSchemaVersion
+ __OBJC_$_CLASS_METHODS_VCDaemonDatabaseProvider
+ ___56-[VCCKShortcutSyncService updateEncryptedSchemaVersion:]_block_invoke
+ ___block_descriptor_157_e8_32s40s_e26_"NSMutableDictionary"8?0l
+ ___block_descriptor_48_e8_32s_e5_v8?0l
+ ___swift_closure_destructor.106Tm
+ ___swift_closure_destructor.22Tm
+ ___swift_closure_destructor.28Tm
+ ___swift_closure_destructor.30Tm
+ ___swift_memcpy25_8
+ _getWFSystemShortcutLogObject
+ _objc_msgSend$appendShortcutWithIdentifier:toCollectionWithIdentifier:error:
+ _objc_msgSend$desiredFolderSyncOperationForCollection:currentEncryptedSchemaVersion:
+ _objc_msgSend$desiredSyncOperationForWorkflow:currentEncryptedSchemaVersion:
+ _objc_msgSend$handleFetchedWorkflowRecord:identifier:recordChangeTag:modificationDate:encryptedSchemaVersion:error:
+ _objc_msgSend$initWithContainer:database:daemonTaskScheduler:applicationObserver:debuggingOptions:logger:encryptedSchemaVersion:
+ _objc_msgSend$initWithUUIDBytes:
+ _objc_msgSend$insertFolderWithName:icon:identifier:
+ _objc_msgSend$loadActionKit
+ _objc_msgSend$logDesiredSyncSummary:recordType:name:recordIDsToSave:recordIDsToDelete:reasonsNotNeeded:
+ _objc_msgSend$nameForDesiredSyncOperation:
+ _objc_msgSend$sendChangedWorkflowsForEventName:
+ _objc_msgSend$setEncryptedSchemaVersion:
+ _objc_msgSend$updateEncryptedSchemaVersion:
+ _symbolic Ig_
+ _symbolic SDySo19WFUnifiedTriggerKeyCSSG
+ _symbolic ShySo19WFUnifiedTriggerKeyCG
+ _symbolic So20WFWorkflowCollectionC
+ _symbolic ______p 11WorkflowKit28WFTriggerRegistrationStoringP
+ _symbolic _____ySo19WFUnifiedTriggerKeyCG s11_SetStorageC
+ _symbolic _____ySo19WFUnifiedTriggerKeyCSSG s17_NativeDictionaryV
+ _symbolic _____ySsG s23_ContiguousArrayStorageC
+ _type_layout_string So14WFEventInfoKeya
- -[VCCKShortcutSyncCoordinator handleWalrusStatusDidChange]
- -[VCCKShortcutSyncService initWithContainer:database:daemonTaskScheduler:applicationObserver:debuggingOptions:logger:]
- -[VCCKShortcutSyncService sendChangedWorkflows]
- -[VCMetricSubmitter hasSeenAutoShortcutsSections]
- GCC_except_table1006
- GCC_except_table1046
- GCC_except_table1063
- GCC_except_table1069
- GCC_except_table1091
- GCC_except_table1162
- GCC_except_table1170
- GCC_except_table1174
- GCC_except_table1199
- GCC_except_table1226
- GCC_except_table1244
- GCC_except_table1249
- GCC_except_table1252
- GCC_except_table1254
- GCC_except_table1285
- GCC_except_table1291
- GCC_except_table1305
- GCC_except_table1324
- GCC_except_table1330
- GCC_except_table1352
- GCC_except_table1356
- GCC_except_table1374
- GCC_except_table1378
- GCC_except_table1392
- GCC_except_table1394
- GCC_except_table1418
- GCC_except_table1421
- GCC_except_table1435
- GCC_except_table396
- GCC_except_table419
- GCC_except_table434
- GCC_except_table510
- GCC_except_table589
- GCC_except_table590
- GCC_except_table604
- GCC_except_table615
- GCC_except_table633
- GCC_except_table828
- GCC_except_table950
- GCC_except_table976
- GCC_except_table982
- GCC_except_table984
- _OUTLINED_FUNCTION_229
- _OUTLINED_FUNCTION_230
- _OUTLINED_FUNCTION_231
- _OUTLINED_FUNCTION_232
- _OUTLINED_FUNCTION_233
- _OUTLINED_FUNCTION_234
- _OUTLINED_FUNCTION_235
- _OUTLINED_FUNCTION_236
- _OUTLINED_FUNCTION_237
- _OUTLINED_FUNCTION_238
- _OUTLINED_FUNCTION_239
- _OUTLINED_FUNCTION_240
- _OUTLINED_FUNCTION_241
- _OUTLINED_FUNCTION_242
- _OUTLINED_FUNCTION_243
- _OUTLINED_FUNCTION_244
- _OUTLINED_FUNCTION_245
- _WFLastViewedAutoShortcutsAtTimeKey
- _WFWalrusEnabledKey
- ___block_descriptor_158_e8_32s40s_e26_"NSMutableDictionary"8?0l
- ___swift_closure_destructor.198Tm
- ___swift_closure_destructor.32Tm
- ___swift_closure_destructor.67Tm
- _objc_msgSend$deleteFolderWithIdentifier:
- _objc_msgSend$desiredFolderSyncOperationForCollection:
- _objc_msgSend$desiredSyncOperationForWorkflow:
- _objc_msgSend$folderWithIdentifier:error:
- _objc_msgSend$handleFetchedWorkflowRecord:identifier:recordChangeTag:modificationDate:error:
- _objc_msgSend$handleWalrusStatusDidChange
- _objc_msgSend$hasSeenAutoShortcutsSections
- _objc_msgSend$initWithContainer:database:daemonTaskScheduler:applicationObserver:debuggingOptions:logger:
- _objc_msgSend$insertFolderWithName:icon:identifier:insertAt:error:
- _objc_msgSend$isWalrusEnabled
- _objc_msgSend$lastRemoteFolderOrderingForCollection:
- _objc_msgSend$lastRemoteShortcutOrderingForCollection:
- _objc_msgSend$moveFolders:toIndex:error:
- _objc_msgSend$sendChangedWorkflows
- _objc_msgSend$setShortcutOrdering:forCollectionIdentifier:error:
- _objc_msgSend$setWalrusEnabled:
- _objc_msgSend$updateWalrusStatus
- _objc_msgSend$wf_orderedSetByMergingOrderedSet:withOrderedSet:baseOrderedSet:
- _symbolic SbIegd_
- _symbolic _____ 11WorkflowKit26WFTriggerRegistrationStoreC
- _symbolic _____Iegd_ s5Int32V
- _symbolic _____Iegr_ s5Int32V
- _symbolic _____ySSG s20CollectionDifferenceV
- _symbolic _____ySS_G s20CollectionDifferenceV6ChangeO
- _symbolic _____y_____ySS_GG s23_ContiguousArrayStorageC s20CollectionDifferenceV6ChangeO
- _symbolic _____yypG s23_ContiguousArrayStorageC
- _type_layout_string So16VCXPCEventStreama
CStrings:
+ " in root instead"
+ "%s Encrypted schema version changed from %ld to %ld"
+ "%s Failed to resolve system shortcut %{public}@: %{public}@"
+ "%s Updated system action type: %@ with the transform, success: %i"
+ "%s Walrus status is unknown (%{public}@), not creating new sync service"
+ ", unavailable resources: ["
+ "-[VCCKShortcutSyncService sendChangedWorkflowsForEventName:]"
+ "-[VCCKShortcutSyncService updateEncryptedSchemaVersion:]"
+ "-[WFConfiguredSystemActionMigrator updateActionsUsingTransform:]"
+ "-[WFSystemShortcutService runSystemShortcutWithToken:bundleIdentifier:reply:]"
+ "Finished updating trigger registration with no changes. Skipped: %{public}ld. Total active: %{public}ld."
+ "Finished updating trigger registration. Registered: %{public}ld, re-registered: %{public}ld, unregistered: %{public}ld, skipped: %{public}ld, failed: %{public}ld. Total active: %{public}ld."
+ "Local categories (%{public}s) do not match remote categories (%{public}s)"
+ "Reconciliation added folder %{public}s"
+ "Reconciliation failed to add shortcut "
+ "Reconciliation failed to add shortcut %{public}s to category %{public}s, should be unreachable."
+ "Reconciliation: can't find folder "
+ "Reconciliation: can't find folder %{public}s, putting %{public}s in root instead."
+ "Reconciliation: couldn't get shortcuts for folder "
+ "Reconciliation: throwing on getting shortcuts from a folder ID (%{public}s) we got from the same library should be unreachable. \n%s"
+ "Reconciling shortcuts in %{public}s."
+ "Reconciling shortcuts in folder %{public}s."
+ "Shortcuts in %{public}s don't need to be reconciled."
+ "Shortcuts in folder %{public}s don't need to be reconciled."
+ "Skipping trigger with identifier: %{public}s, key: %{public}@ | %{public}s."
+ "VCCKShortcutSyncService.encryptedSchemaVersionChanged"
+ "], unconfigured parameters: ["
+ "account info fetch failed: %@:%ld"
+ "account info fetch returned an error: %@:%ld"
+ "account status changed: %@ -> %@"
+ "com.apple.shortcuts.WFTriggerRegistrar.registration"
+ "could not build WFNewTrigger"
+ "encrypted schema version changed: %ld -> %ld"
+ "fetched folder %@ with newer encrypted schema version %lld, leaving it alone"
+ "fetched workflow %@ with newer encrypted schema version %lld, leaving it alone"
+ "not starting sync service: walrus status unknown"
+ "up to date"
+ "update encrypted schema version to %ld"
+ "walrus status changed: %@ -> %@"
- "%s Handling CloudKit Walrus status change, walrusEnabled = %d"
- "%s Walrus status did change, but we couldn't find a database to update: %@"
- "-[VCCKShortcutSyncCoordinator handleWalrusStatusDidChange]"
- "-[VCCKShortcutSyncService sendChangedWorkflows]"
- "Device records response was unexpectedly empty."
- "Finished updating trigger registration. Registered: %{public}ld, re-registered: %{public}ld, unregistered: %{public}ld, skipped: %{public}ld. Total active: %{public}ld."
- "Inserted folder %s not found in local library."
- "Local categories (%s) do not match remote categories (%s)"
- "Reconciling shortcuts in %s."
- "Reconciling shortcuts in folder %s."
- "Shortcuts in %s don't need to be reconciled."
- "Shortcuts in folder %s don't need to be reconciled."
- "Skipping trigger with identifier: %{public}s, key: %{public}@ | isAvailable: %{bool,public}d, isValid: %{bool,public}d."
- "autoShortcutsSectionsViewed"
- "com.apple.shortcuts.walrus"
```
