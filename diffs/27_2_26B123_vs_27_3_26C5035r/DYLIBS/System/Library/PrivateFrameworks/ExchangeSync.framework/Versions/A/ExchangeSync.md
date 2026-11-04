## ExchangeSync

> `/System/Library/PrivateFrameworks/ExchangeSync.framework/Versions/A/ExchangeSync`

```diff

-2080.200.61.0.0
-  __TEXT.__text: 0x1ba4dc
-  __TEXT.__objc_methlist: 0x6cf4
-  __TEXT.__const: 0x9808
-  __TEXT.__gcc_except_tab: 0x1588
-  __TEXT.__cstring: 0xb5bc
-  __TEXT.__oslogstring: 0x11beb
-  __TEXT.__swift5_typeref: 0x2cea
-  __TEXT.__swift5_reflstr: 0x3076
-  __TEXT.__swift5_assocty: 0xa10
-  __TEXT.__constg_swiftt: 0x31b4
-  __TEXT.__swift5_fieldmd: 0x3280
-  __TEXT.__swift5_proto: 0x498
-  __TEXT.__swift5_types: 0x3fc
-  __TEXT.__swift5_protos: 0xbc
-  __TEXT.__swift5_capture: 0x82c
-  __TEXT.__swift5_builtin: 0xa0
-  __TEXT.__swift5_mpenum: 0x18
-  __TEXT.__unwind_info: 0x6640
-  __TEXT.__eh_frame: 0x5784
+2080.300.31.0.0
+  __TEXT.__text: 0x23e844
+  __TEXT.__objc_methlist: 0x864c
+  __TEXT.__const: 0xb238
+  __TEXT.__gcc_except_tab: 0x1970
+  __TEXT.__cstring: 0xff8b
+  __TEXT.__oslogstring: 0x1814b
+  __TEXT.__swift5_typeref: 0x3800
+  __TEXT.__swift5_reflstr: 0x3c34
+  __TEXT.__swift5_assocty: 0xa40
+  __TEXT.__constg_swiftt: 0x3a9c
+  __TEXT.__swift5_fieldmd: 0x3f24
+  __TEXT.__swift5_proto: 0x5a0
+  __TEXT.__swift5_types: 0x4dc
+  __TEXT.__swift5_protos: 0xcc
+  __TEXT.__swift5_capture: 0x1050
+  __TEXT.__swift5_builtin: 0xdc
+  __TEXT.__swift5_mpenum: 0x40
+  __TEXT.__unwind_info: 0x7e40
+  __TEXT.__eh_frame: 0x651c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6b0
-  __DATA_CONST.__objc_classlist: 0x3c8
+  __DATA_CONST.__const: 0x7b0
+  __DATA_CONST.__objc_classlist: 0x4b8
   __DATA_CONST.__objc_catlist: 0x20
-  __DATA_CONST.__objc_protolist: 0xb0
+  __DATA_CONST.__objc_protolist: 0xc0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x43c0
+  __DATA_CONST.__objc_selrefs: 0x5010
   __DATA_CONST.__objc_protorefs: 0x38
-  __DATA_CONST.__objc_superrefs: 0x1f0
+  __DATA_CONST.__objc_superrefs: 0x248
   __DATA_CONST.__objc_arraydata: 0x20
-  __DATA_CONST.__got: 0x1580
-  __AUTH_CONST.__const: 0xa480
-  __AUTH_CONST.__cfstring: 0x4d80
-  __AUTH_CONST.__objc_const: 0xe768
+  __DATA_CONST.__got: 0x17b0
+  __AUTH_CONST.__const: 0xce68
+  __AUTH_CONST.__cfstring: 0x5da0
+  __AUTH_CONST.__objc_const: 0x125b8
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x2160
-  __AUTH.__objc_data: 0x2130
-  __AUTH.__data: 0x35e0
-  __DATA.__objc_ivar: 0x880
-  __DATA.__data: 0x1820
-  __DATA.__bss: 0x85c0
-  __DATA.__common: 0x518
+  __AUTH_CONST.__auth_got: 0x2398
+  __AUTH.__objc_data: 0x2920
+  __AUTH.__data: 0x40f8
+  __DATA.__objc_ivar: 0xaf0
+  __DATA.__data: 0x1cd8
+  __DATA.__bss: 0xa8e0
+  __DATA.__common: 0x610
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 7792
-  Symbols:   7555
-  CStrings:  1966
+  Functions: 9753
+  Symbols:   9164
+  CStrings:  2442
 
Symbols:
+ +[EXSAccount acAccountHasGraphAPIEndpoint:]
+ +[EXSAccountManager _recordNoDataToConvertForUntrackedACAccounts:trackedAccountKeys:]
+ +[EXSAccountManager _transientAccountForKey:acAccount:]
+ +[EXSDataManager _nonPersonaExchangeSyncDataVaultDirectory]
+ +[EXSDataManager databaseFilesAreAbsentForAccount:]
+ +[EXSDataclassCallGate gateForDataclass:]
+ +[EXSDataclassCallGate(ForTesting) gateForTestingWithLabel:timeout:probeInterval:escalationInterval:]
+ +[EXSEWSSyncUtils deviceZoneComponentsFromEWSDateTime:]
+ +[EXSEWSSyncUtils ewsTaskCompleteDateComponentsFromDate:]
+ +[EXSEWSSyncUtils ewsTaskDayComponentsFromDay:contextZone:]
+ +[EXSEWSSyncUtils ewsTaskReminderDueByComponentsFromComponents:]
+ +[EXSFeatureFlagManager setGraphMigrationEnabledOverrideForTesting:]
+ +[EXSFeatureFlagManager setGraphSyncEnabledOverrideForTesting:]
+ +[EXSGSCalendarFolderIDCanonicalizer canonicalizeCalendarFolderIDsForAccount:dataManager:syncProtocol:deadline:]
+ +[EXSGSCalendarFolderIDCanonicalizer canonicalizeCalendarFolderIDsForAccount:dataManager:syncProtocol:deadline:failureReason:]
+ +[EXSGSCalendarFolderIDCanonicalizer defaultDeadline]
+ +[EXSGSCalendarFolderIDCanonicalizer log]
+ +[EXSGSGraphIDConversionCoordinator _cancellationCheckWithDataManager:deadline:deadlineExceeded:]
+ +[EXSGSGraphIDConversionCoordinator _outcomeForReport:account:dataManager:deadlineExceeded:]
+ +[EXSGSGraphIDConversionCoordinator attemptConversionForAccount:dataManager:databaseOpenResult:deadline:]
+ +[EXSGSGraphIDConversionCoordinator defaultDeadline]
+ +[EXSGSGraphIDConversionCoordinator log]
+ +[EXSGSGraphIDConversionCoordinator maximumConversionAttempts]
+ +[EXSGSGraphIDConversionCoordinator shouldAttemptConversionForAccount:dataManager:]
+ +[EXSGSMigrationEscalation decisionForFailure:attemptsSoFar:policy:]
+ +[EXSGSMigrationEscalation logFailure:decision:attemptsSoFar:policy:accountKey:]
+ +[EXSGSMigrationEscalation log]
+ +[EXSGSMigrationEscalation maximumAttemptsPerPhase]
+ +[EXSGSMigrationEscalationPolicy currentPolicy]
+ +[EXSGSMigrationEscalationPolicy policyWithGraphMigrationEnabled:maximumAttemptsPerPhase:]
+ +[EXSGSMigrationFailure _failureWithPhase:kind:reason:]
+ +[EXSGSMigrationFailure failureForConversionOutcome:]
+ +[EXSGSMigrationFailure failureForHousekeepingReason:]
+ +[EXSGSMigrationGate _decodeMigrationStateFromACAccount:accountKey:]
+ +[EXSGSMigrationGate accountHasGraphAPIEndpoint:]
+ +[EXSGSMigrationGate advanceMigrationStateForAccount:to:]
+ +[EXSGSMigrationGate convertedStoreRequiresCutover:]
+ +[EXSGSMigrationGate migrationStateForACAccount:accountKey:]
+ +[EXSGSMigrationGate setLiveACAccountResolverForTesting:]
+ +[EXSStoreResetOptions defaultOptionsWithPushingChangeSourceIDs:]
+ +[EXSSyncProtocolFactory log]
+ -[EXSAccount adoptRefreshedACAccount:]
+ -[EXSAvailabilityRequestComponents receivedAtMonotonicNanoseconds]
+ -[EXSCalendarItemProperties relocateToParentCalendar]
+ -[EXSCalendarItemProperties setRelocateToParentCalendar:]
+ -[EXSChangeItem adoptCommittedExternalID:]
+ -[EXSDataConsumerInstance _clearChangeTokenAfterClientStoreTeardownForConsumer:]
+ -[EXSDataConsumerInstance _consumer:wantsAnyOfChangeItems:]
+ -[EXSDataConsumerInstance _persistDeclinedThroughChangeID:fromStoredChangeID:forChangeSource:]
+ -[EXSDataConsumerInstance _pushChangeItems:toConsumer:withTrackingToken:]
+ -[EXSDataConsumerInstance clientStoreIsReachable]
+ -[EXSDataConsumerInstance dataConsumerNeedsOutstandingChangesRedelivered:]
+ -[EXSDataConsumerInstance discardClientStoreForAccountReset]
+ -[EXSDataManager _adjustGraphIDConversionAttemptCountBy:context:]
+ -[EXSDataManager _createWebPushSubscriptionsTableWithDB:]
+ -[EXSDataManager _ensureChangeItemsCreateTokenColumnWithDB:]
+ -[EXSDataManager _ensureItemsExternalIDIndexWithDB:]
+ -[EXSDataManager _ensureWebPushSubscriptionsTableWithDB:schemaVersion:]
+ -[EXSDataManager _getLastDataPushStateForChangeSource:inAccount:recoveryTrackingToken:recoveryTimestamp:]
+ -[EXSDataManager _lowestConsumedChangeItemIDExcludingChangeSourceIDs:outLowestChangeItemID:]
+ -[EXSDataManager _pruneStaleChangeItemsBelowWatermark:limit:]
+ -[EXSDataManager _registeredChangeSourceIDsForAccount:]
+ -[EXSDataManager _updateGraphMigrationRowWithAssignment:context:]
+ -[EXSDataManager advanceLastChangeIDForChangeSource:inAccount:fromChangeID:pastDeclinedChangeID:]
+ -[EXSDataManager cleanupStaleDataExcludingChangeSourceIDs:]
+ -[EXSDataManager databaseOpenResult]
+ -[EXSDataManager deleteAllWebPushSubscriptionRows]
+ -[EXSDataManager deleteWebPushSubscriptionRowForDataClass:folderExternalID:]
+ -[EXSDataManager endDataPushForChangeSource:inAccount:forLastChangeID:withOutcome:batchItemCount:pusherCanBatch:]
+ -[EXSDataManager getGraphIDConversionAttemptCount:]
+ -[EXSDataManager hasCompletedGraphIDConversion]
+ -[EXSDataManager recordGraphIDConversionAttempt]
+ -[EXSDataManager recordGraphIDConversionFailure]
+ -[EXSDataManager recordTerminalPurgeCompleted]
+ -[EXSDataManager releaseGraphIDConversionAttempt]
+ -[EXSDataManager setDatabaseOpenResult:]
+ -[EXSDataManager setStaleChangeItemPruneBatchSize:]
+ -[EXSDataManager staleChangeItemPruneBatchSize]
+ -[EXSDataManager upsertWebPushSubscriptionRow:]
+ -[EXSDataManager webPushSubscriptionRows]
+ -[EXSDataManager(ChangeItems) _changeItemsSinceChangeID:shouldBatch:fetchBatch:]
+ -[EXSDataManager(ChangeItems) _collapseSiblingsOfItem:fromRows:repointingChangeItemsTo:usingDBConnection:]
+ -[EXSDataManager(ChangeItems) _getUpsyncChangeItemsSinceChangeID:shouldBatch:]
+ -[EXSDataManager(ChangeItems) _patchDetachedChangeItems:]
+ -[EXSDataManager(ChangeItems) clearCreateTokenForChangeID:]
+ -[EXSDataManager(ChangeItems) createTokenForChangeID:]
+ -[EXSDataManager(ChangeItems) createTokenForChangeID:mintedNow:]
+ -[EXSDataManager(ChangeItems) externalIDsWithUnpushedChangesOfItemType:pastWatermarkOfChangeSource:]
+ -[EXSDataManager(ChangeItems) getUpsyncChangeItemsSinceChangeID:shouldBatch:]
+ -[EXSDataManager(ChangeItems) hasLaterDeletionOfChangeItem:]
+ -[EXSDataManager(ChangeItems) hasUpsyncChangeItemsSinceChangeID:]
+ -[EXSDataManager(ChangeItems) recordCreatedExternalID:externalChangeKey:onLaterDeletionsOfChangeItem:]
+ -[EXSDataManager(ChangeItems) upsertItemForChangeItem:usingDBConnection:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationHasConvertedAtStamp]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationStampConversionCompletion:report:state:]
+ -[EXSDataManager(GraphIDMigration) calendarFolderExternalIDsForGraphCanonicalization]
+ -[EXSDataManager(GraphIDMigration) foldLegacyNotesFolder:messageRootIDs:intoContainer:]
+ -[EXSDataManager(GraphIDMigration) hasAnyLocalRowsForGraphIDMigration]
+ -[EXSDataManager(GraphIDMigration) legacyNotesContainerForGraphCutoverWithContainer:]
+ -[EXSDataManager(GraphIDMigration) rewriteFolderExternalIDs:]
+ -[EXSDataManager(Items) findItemWithItemID:]
+ -[EXSDataManager(Items_Private) _itemsWithExternalID:]
+ -[EXSDataManager(StoreReset) _logStoreResetReport:]
+ -[EXSDataManager(StoreReset) _performStoreResetWithScope:targetRowID:targetInternalID:folderType:accountMismatch:options:report:state:]
+ -[EXSDataManager(StoreReset) _runStoreResetWithScope:targetRowID:targetInternalID:folderType:verifyAccount:callerOptions:]
+ -[EXSDataManager(StoreReset) _storeResetAbort:report:reason:]
+ -[EXSDataManager(StoreReset) _storeResetAllCachedAttachmentPaths]
+ -[EXSDataManager(StoreReset) _storeResetApplyPendingCountsForNonWrite:report:]
+ -[EXSDataManager(StoreReset) _storeResetAttachmentsForSurvivingChunkKeysWithRowIDs:paths:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetChangeItemIsPending:state:]
+ -[EXSDataManager(StoreReset) _storeResetClearAllServerCursorsWithOptions:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetClearChangeSourceCursors:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetClearFolderSyncStateForFolderIDs:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetClearStaleDrainStatesWithOptions:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetCountFrom:]
+ -[EXSDataManager(StoreReset) _storeResetDeleteDistinguishedRowsForExternalID:db:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetDeleteFolderChangeItemsForFolderRowID:db:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetDeleteItemChunkWithRowIDs:externalIDs:internalIDs:skipped:db:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetDistinctAccountCount]
+ -[EXSDataManager(StoreReset) _storeResetDrainPositionsForOptions:]
+ -[EXSDataManager(StoreReset) _storeResetEntireStoreWithOptions:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetExecute:db:options:report:state:write:]
+ -[EXSDataManager(StoreReset) _storeResetExistingFolderCountForFolderIDs:]
+ -[EXSDataManager(StoreReset) _storeResetFirstDataConsumerIdentifierInSet:]
+ -[EXSDataManager(StoreReset) _storeResetFolderRow:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetFolderRowIDForInternalID:]
+ -[EXSDataManager(StoreReset) _storeResetFolderSubtreeFromRowID:restrictToFolderType:folderType:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetFolderTypeForFolderID:]
+ -[EXSDataManager(StoreReset) _storeResetFoldersOfType:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetItemHasPendingChangeItemWithRowID:externalID:internalID:state:]
+ -[EXSDataManager(StoreReset) _storeResetItemRequiresMissingCursorSourcesForRowID:options:]
+ -[EXSDataManager(StoreReset) _storeResetItemRow:externalID:internalID:db:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetItemRowIDForInternalID:]
+ -[EXSDataManager(StoreReset) _storeResetItemWithRowID:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetItemsInFolderID:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetLoadChunkKeysWithRowIDs:externalIDs:internalIDs:db:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetMarkChunkKeysSurviving:db:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetNoteOrphanedAttachmentRowsIntoReport:]
+ -[EXSDataManager(StoreReset) _storeResetNoteSkippedItemRow:reason:state:]
+ -[EXSDataManager(StoreReset) _storeResetOrphanBucketForFolderType:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetOrphanedAttachmentRowsExistWithOptions:]
+ -[EXSDataManager(StoreReset) _storeResetPerformUnit:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetPreconditionForScope:schemaVersion:accountMismatch:options:staleDrainChangeSourceIDs:]
+ -[EXSDataManager(StoreReset) _storeResetPromotePendingFiles:options:]
+ -[EXSDataManager(StoreReset) _storeResetRunScope:targetRowID:folderType:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetSchemaVersion]
+ -[EXSDataManager(StoreReset) _storeResetShouldStop:options:]
+ -[EXSDataManager(StoreReset) _storeResetSkipReasonForFolderRowID:externalID:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetSkipReasonForItemRowID:externalID:internalID:options:state:]
+ -[EXSDataManager(StoreReset) _storeResetSubtreeFolderIDsFrom:restrictToFolderType:folderType:options:report:state:]
+ -[EXSDataManager(StoreReset) _storeResetTargetExistsForScope:rowID:]
+ -[EXSDataManager(StoreReset) _storeResetUnlinkCommittedFiles:options:report:]
+ -[EXSDataManager(StoreReset) _storeResetUnlinkedAttachmentRowCount]
+ -[EXSDataManager(StoreReset) _storeResetUnpushedFolderCount]
+ -[EXSDataManager(StoreReset) _storeResetUnpushedItemCount]
+ -[EXSDataManager(StoreReset) _storeResetUnpushedLocalChangeCountWithOptions:]
+ -[EXSDataManager(StoreReset) _storeResetUnpushedLocalChangesExistWithOptions:]
+ -[EXSDataManager(StoreReset) _storeResetZeroChangeSourceWatermarksWithDB:options:report:state:]
+ -[EXSDataManager(StoreReset) resetEntireStoreForAccount:options:]
+ -[EXSDataManager(StoreReset) resetFolderWithFolderID:options:]
+ -[EXSDataManager(StoreReset) resetFolderWithInternalID:options:]
+ -[EXSDataManager(StoreReset) resetFoldersOfType:forAccount:options:]
+ -[EXSDataManager(StoreReset) resetItemWithInternalID:options:]
+ -[EXSDataManager(StoreReset) resetItemWithRowID:options:]
+ -[EXSDataclassCall .cxx_destruct]
+ -[EXSDataclassCall initWithGate:epoch:]
+ -[EXSDataclassCall isCurrent]
+ -[EXSDataclassCallGate .cxx_destruct]
+ -[EXSDataclassCallGate _creditRecoveredReplacementLocked]
+ -[EXSDataclassCallGate _currentProbeIntervalLocked]
+ -[EXSDataclassCallGate _dispatchDurableWork:token:onQueue:]
+ -[EXSDataclassCallGate _ensureDurableTransactionsLocked]
+ -[EXSDataclassCallGate _newQueue]
+ -[EXSDataclassCallGate _noteCallCompletedLocked]
+ -[EXSDataclassCallGate _probeDidRunForEpoch:]
+ -[EXSDataclassCallGate _pruneRecoveryObserversMatchingOwner:]
+ -[EXSDataclassCallGate _retireDurableWorkWithToken:]
+ -[EXSDataclassCallGate _runAndWait:]
+ -[EXSDataclassCallGate _scheduleTick]
+ -[EXSDataclassCallGate _tick]
+ -[EXSDataclassCallGate _tripAfterTimeout]
+ -[EXSDataclassCallGate addRecoveryObserver:block:]
+ -[EXSDataclassCallGate callIsCurrent]
+ -[EXSDataclassCallGate consecutiveTripCountForTesting]
+ -[EXSDataclassCallGate currentEpoch]
+ -[EXSDataclassCallGate initWithName:timeout:probeInterval:escalationInterval:]
+ -[EXSDataclassCallGate isTripped]
+ -[EXSDataclassCallGate pendingDurableTransactionCountForTesting]
+ -[EXSDataclassCallGate pendingDurableWorkCountForTesting]
+ -[EXSDataclassCallGate performDurablyIgnoringBreaker:]
+ -[EXSDataclassCallGate performSynchronously:result:]
+ -[EXSDataclassCallGate performSynchronouslyBOOL:result:]
+ -[EXSDataclassCallGate queueReplacementCountForTesting]
+ -[EXSDataclassCallGate tryPerformAsynchronously:]
+ -[EXSDataclassCallGate tryPerformAsynchronouslyAfter:block:]
+ -[EXSDataclassCallGateRecoveryObserver .cxx_destruct]
+ -[EXSDataclassCallGateRecoveryObserver block]
+ -[EXSDataclassCallGateRecoveryObserver owner]
+ -[EXSDataclassCallGateRecoveryObserver setBlock:]
+ -[EXSDataclassCallGateRecoveryObserver setOwner:]
+ -[EXSEWSCreateTaskOperation _createTaskItemTypeForChangeItem:contextZone:]
+ -[EXSEWSOperation _fetchCurrentChangeKeyForItemWithExternalID:]
+ -[EXSEWSOperation _runUpdateItemRequest:schemaVersion:timeZoneContext:error:]
+ -[EXSEWSOperation sendUpdateItemRequest:schemaVersion:timeZoneContext:refreshingChangeKeyOnConflict:itemIdWithFreshKey:error:]
+ -[EXSEWSOperation taskTimeZoneContextForZone:]
+ -[EXSEWSSyncProtocol _makeSyncAllFolderItemsTransaction]
+ -[EXSEWSSyncProtocol _scheduleTransactionReleaseFallback:afterSeconds:]
+ -[EXSEWSUpdateCalendarItemOperation _itemIdForChangeItem:itemExternalID:changeKey:]
+ -[EXSEWSUpdateItemOperation _buildItemSettersForTaskChangeItem:contextZone:]
+ -[EXSGSMigrationEscalationPolicy _initWithGraphMigrationEnabled:maximumAttemptsPerPhase:]
+ -[EXSGSMigrationEscalationPolicy graphMigrationEnabled]
+ -[EXSGSMigrationEscalationPolicy maximumAttemptsPerPhase]
+ -[EXSGSMigrationFailure _initWithPhase:kind:reason:]
+ -[EXSGSMigrationFailure kind]
+ -[EXSGSMigrationFailure phase]
+ -[EXSGSMigrationFailure reason]
+ -[EXSGSMigrationTerminalPurge .cxx_destruct]
+ -[EXSGSMigrationTerminalPurge _accumulateResetReport:intoReport:]
+ -[EXSGSMigrationTerminalPurge _discardClientStoresIntoReport:]
+ -[EXSGSMigrationTerminalPurge _finish:outcome:]
+ -[EXSGSMigrationTerminalPurge _outcomeForRefusedReset:]
+ -[EXSGSMigrationTerminalPurge _pushingChangeSourceIDs]
+ -[EXSGSMigrationTerminalPurge _resetEachDataClassIntoReport:]
+ -[EXSGSMigrationTerminalPurge _resetLocalStoreIntoReport:]
+ -[EXSGSMigrationTerminalPurge _resetOptions]
+ -[EXSGSMigrationTerminalPurge accountKey]
+ -[EXSGSMigrationTerminalPurge account]
+ -[EXSGSMigrationTerminalPurge clientStoreDiscarder]
+ -[EXSGSMigrationTerminalPurge dataManager]
+ -[EXSGSMigrationTerminalPurge databaseOpenResult]
+ -[EXSGSMigrationTerminalPurge ewsChangeSourceID]
+ -[EXSGSMigrationTerminalPurge initWithAccount:dataManager:databaseOpenResult:clientStoreDiscarder:]
+ -[EXSGSMigrationTerminalPurge run]
+ -[EXSGSMigrationTerminalPurgeReport attachmentRowsRemoved]
+ -[EXSGSMigrationTerminalPurgeReport changeItemsRemoved]
+ -[EXSGSMigrationTerminalPurgeReport clientStoreDiscardAttempts]
+ -[EXSGSMigrationTerminalPurgeReport clientStoresCompleted]
+ -[EXSGSMigrationTerminalPurgeReport clientStoresEnqueued]
+ -[EXSGSMigrationTerminalPurgeReport clientStoresFaulted]
+ -[EXSGSMigrationTerminalPurgeReport folderMapCleared]
+ -[EXSGSMigrationTerminalPurgeReport foldersRemoved]
+ -[EXSGSMigrationTerminalPurgeReport itemsRemoved]
+ -[EXSGSMigrationTerminalPurgeReport lastStep]
+ -[EXSGSMigrationTerminalPurgeReport outcome]
+ -[EXSGSMigrationTerminalPurgeReport setAttachmentRowsRemoved:]
+ -[EXSGSMigrationTerminalPurgeReport setChangeItemsRemoved:]
+ -[EXSGSMigrationTerminalPurgeReport setClientStoreDiscardAttempts:]
+ -[EXSGSMigrationTerminalPurgeReport setClientStoresCompleted:]
+ -[EXSGSMigrationTerminalPurgeReport setClientStoresEnqueued:]
+ -[EXSGSMigrationTerminalPurgeReport setClientStoresFaulted:]
+ -[EXSGSMigrationTerminalPurgeReport setFolderMapCleared:]
+ -[EXSGSMigrationTerminalPurgeReport setFoldersRemoved:]
+ -[EXSGSMigrationTerminalPurgeReport setItemsRemoved:]
+ -[EXSGSMigrationTerminalPurgeReport setLastStep:]
+ -[EXSGSMigrationTerminalPurgeReport setOutcome:]
+ -[EXSGSMigrationTerminalPurgeReport setStaleDrainStatesCleared:]
+ -[EXSGSMigrationTerminalPurgeReport setStampAttempts:]
+ -[EXSGSMigrationTerminalPurgeReport setStamped:]
+ -[EXSGSMigrationTerminalPurgeReport setStoreResetAttempts:]
+ -[EXSGSMigrationTerminalPurgeReport setStoreResetPrecondition:]
+ -[EXSGSMigrationTerminalPurgeReport setUnpushedLocalChangesDiscarded:]
+ -[EXSGSMigrationTerminalPurgeReport setUsedPerDataClassReset:]
+ -[EXSGSMigrationTerminalPurgeReport staleDrainStatesCleared]
+ -[EXSGSMigrationTerminalPurgeReport stampAttempts]
+ -[EXSGSMigrationTerminalPurgeReport stamped]
+ -[EXSGSMigrationTerminalPurgeReport storeResetAttempts]
+ -[EXSGSMigrationTerminalPurgeReport storeResetPrecondition]
+ -[EXSGSMigrationTerminalPurgeReport unpushedLocalChangesDiscarded]
+ -[EXSGSMigrationTerminalPurgeReport usedPerDataClassReset]
+ -[EXSGSPluginClientStoreDiscarder .cxx_destruct]
+ -[EXSGSPluginClientStoreDiscarder discardClientStoreForFolderType:]
+ -[EXSGSPluginClientStoreDiscarder folderTypesWithClientStores]
+ -[EXSGSPluginClientStoreDiscarder initWithAccount:plugins:instanceFactory:]
+ -[EXSGSPluginClientStoreDiscarder instancesByFolderType]
+ -[EXSGSPluginClientStoreDiscarder orderedFolderTypes]
+ -[EXSGraphIDMigrationOptions setStampsConversionCompletion:]
+ -[EXSGraphIDMigrationOptions stampsConversionCompletion]
+ -[EXSNotesLegacyContainer .cxx_destruct]
+ -[EXSNotesLegacyContainer containerRowExists]
+ -[EXSNotesLegacyContainer legacyNotesFolderID]
+ -[EXSNotesLegacyContainer messageRootIDs]
+ -[EXSNotesLegacyContainer setContainerRowExists:]
+ -[EXSNotesLegacyContainer setLegacyNotesFolderID:]
+ -[EXSNotesLegacyContainer setMessageRootIDs:]
+ -[EXSSearchDirectoryRequest initWithRequestID:searchQuery:recordTypes:includeFullData:responseManager:]
+ -[EXSSearchDirectoryRequest receivedAtMonotonicNanoseconds]
+ -[EXSSearchDirectoryRequest recordTypes]
+ -[EXSStoreResetDrainPosition .cxx_destruct]
+ -[EXSStoreResetDrainPosition changeSourceID]
+ -[EXSStoreResetDrainPosition lastChangeItemID]
+ -[EXSStoreResetDrainPosition setChangeSourceID:]
+ -[EXSStoreResetDrainPosition setLastChangeItemID:]
+ -[EXSStoreResetOptions .cxx_destruct]
+ -[EXSStoreResetOptions chunkSize]
+ -[EXSStoreResetOptions copyWithZone:]
+ -[EXSStoreResetOptions cursorChangeSourceIDs]
+ -[EXSStoreResetOptions databaseOpenResult]
+ -[EXSStoreResetOptions dryRun]
+ -[EXSStoreResetOptions idleChangeSourceIDs]
+ -[EXSStoreResetOptions includesOrphanedAttachmentRows]
+ -[EXSStoreResetOptions includesUnpushedLocalChanges]
+ -[EXSStoreResetOptions init]
+ -[EXSStoreResetOptions pushingChangeSourceIDs]
+ -[EXSStoreResetOptions setChunkSize:]
+ -[EXSStoreResetOptions setCursorChangeSourceIDs:]
+ -[EXSStoreResetOptions setDatabaseOpenResult:]
+ -[EXSStoreResetOptions setDryRun:]
+ -[EXSStoreResetOptions setIdleChangeSourceIDs:]
+ -[EXSStoreResetOptions setIncludesOrphanedAttachmentRows:]
+ -[EXSStoreResetOptions setIncludesUnpushedLocalChanges:]
+ -[EXSStoreResetOptions setPushingChangeSourceIDs:]
+ -[EXSStoreResetOptions setShouldCancel:]
+ -[EXSStoreResetOptions setTransactionMode:]
+ -[EXSStoreResetOptions shouldCancel]
+ -[EXSStoreResetOptions transactionMode]
+ -[EXSStoreResetPendingCounts .cxx_destruct]
+ -[EXSStoreResetPendingCounts applyToReport:]
+ -[EXSStoreResetPendingCounts attachmentRowsRemoved]
+ -[EXSStoreResetPendingCounts changeItemsRemoved]
+ -[EXSStoreResetPendingCounts changeSourceCursorsCleared]
+ -[EXSStoreResetPendingCounts changeSourceWatermarksZeroed]
+ -[EXSStoreResetPendingCounts detachedOccurrenceChangeItemsReported]
+ -[EXSStoreResetPendingCounts discard]
+ -[EXSStoreResetPendingCounts distinguishedFolderRowsRemoved]
+ -[EXSStoreResetPendingCounts foldersRemoved]
+ -[EXSStoreResetPendingCounts foldersRetainedForSkippedItems]
+ -[EXSStoreResetPendingCounts foldersSkippedForUnpushedLocalChanges]
+ -[EXSStoreResetPendingCounts foldersSyncStateClearedTakenBack]
+ -[EXSStoreResetPendingCounts foldersSyncStateCleared]
+ -[EXSStoreResetPendingCounts init]
+ -[EXSStoreResetPendingCounts itemsRemoved]
+ -[EXSStoreResetPendingCounts itemsSkippedForUnpushedLocalChanges]
+ -[EXSStoreResetPendingCounts notes]
+ -[EXSStoreResetPendingCounts setAttachmentRowsRemoved:]
+ -[EXSStoreResetPendingCounts setChangeItemsRemoved:]
+ -[EXSStoreResetPendingCounts setChangeSourceCursorsCleared:]
+ -[EXSStoreResetPendingCounts setChangeSourceWatermarksZeroed:]
+ -[EXSStoreResetPendingCounts setDetachedOccurrenceChangeItemsReported:]
+ -[EXSStoreResetPendingCounts setDistinguishedFolderRowsRemoved:]
+ -[EXSStoreResetPendingCounts setFoldersRemoved:]
+ -[EXSStoreResetPendingCounts setFoldersRetainedForSkippedItems:]
+ -[EXSStoreResetPendingCounts setFoldersSkippedForUnpushedLocalChanges:]
+ -[EXSStoreResetPendingCounts setFoldersSyncStateCleared:]
+ -[EXSStoreResetPendingCounts setFoldersSyncStateClearedTakenBack:]
+ -[EXSStoreResetPendingCounts setItemsRemoved:]
+ -[EXSStoreResetPendingCounts setItemsSkippedForUnpushedLocalChanges:]
+ -[EXSStoreResetPendingCounts setStaleDrainStatesCleared:]
+ -[EXSStoreResetPendingCounts setUnpushedLocalChangesDiscarded:]
+ -[EXSStoreResetPendingCounts staleDrainStatesCleared]
+ -[EXSStoreResetPendingCounts unpushedLocalChangesDiscarded]
+ -[EXSStoreResetReport .cxx_destruct]
+ -[EXSStoreResetReport abortReason]
+ -[EXSStoreResetReport accountKey]
+ -[EXSStoreResetReport addNote:]
+ -[EXSStoreResetReport attachmentFilesFailedToUnlink]
+ -[EXSStoreResetReport attachmentFilesUnlinked]
+ -[EXSStoreResetReport attachmentRowsRemoved]
+ -[EXSStoreResetReport cancelled]
+ -[EXSStoreResetReport changeItemsRemoved]
+ -[EXSStoreResetReport changeSourceCursorsCleared]
+ -[EXSStoreResetReport changeSourceWatermarksZeroed]
+ -[EXSStoreResetReport chunkSize]
+ -[EXSStoreResetReport chunksCommitted]
+ -[EXSStoreResetReport committed]
+ -[EXSStoreResetReport databaseSchemaVersion]
+ -[EXSStoreResetReport detachedOccurrenceChangeItemsReported]
+ -[EXSStoreResetReport distinguishedFolderRowsRemoved]
+ -[EXSStoreResetReport dryRun]
+ -[EXSStoreResetReport foldersRemoved]
+ -[EXSStoreResetReport foldersRetainedForSkippedItems]
+ -[EXSStoreResetReport foldersSkippedForUnpushedLocalChanges]
+ -[EXSStoreResetReport foldersSyncStateCleared]
+ -[EXSStoreResetReport init]
+ -[EXSStoreResetReport itemsRemoved]
+ -[EXSStoreResetReport itemsSkippedForUnpushedLocalChanges]
+ -[EXSStoreResetReport mutableNotes]
+ -[EXSStoreResetReport notesOfKind:]
+ -[EXSStoreResetReport notes]
+ -[EXSStoreResetReport orphanedAttachmentRowsFound]
+ -[EXSStoreResetReport precondition]
+ -[EXSStoreResetReport scope]
+ -[EXSStoreResetReport setAbortReason:]
+ -[EXSStoreResetReport setAccountKey:]
+ -[EXSStoreResetReport setAttachmentFilesFailedToUnlink:]
+ -[EXSStoreResetReport setAttachmentFilesUnlinked:]
+ -[EXSStoreResetReport setAttachmentRowsRemoved:]
+ -[EXSStoreResetReport setCancelled:]
+ -[EXSStoreResetReport setChangeItemsRemoved:]
+ -[EXSStoreResetReport setChangeSourceCursorsCleared:]
+ -[EXSStoreResetReport setChangeSourceWatermarksZeroed:]
+ -[EXSStoreResetReport setChunkSize:]
+ -[EXSStoreResetReport setChunksCommitted:]
+ -[EXSStoreResetReport setCommitted:]
+ -[EXSStoreResetReport setDatabaseSchemaVersion:]
+ -[EXSStoreResetReport setDetachedOccurrenceChangeItemsReported:]
+ -[EXSStoreResetReport setDistinguishedFolderRowsRemoved:]
+ -[EXSStoreResetReport setDryRun:]
+ -[EXSStoreResetReport setFoldersRemoved:]
+ -[EXSStoreResetReport setFoldersRetainedForSkippedItems:]
+ -[EXSStoreResetReport setFoldersSkippedForUnpushedLocalChanges:]
+ -[EXSStoreResetReport setFoldersSyncStateCleared:]
+ -[EXSStoreResetReport setItemsRemoved:]
+ -[EXSStoreResetReport setItemsSkippedForUnpushedLocalChanges:]
+ -[EXSStoreResetReport setMutableNotes:]
+ -[EXSStoreResetReport setOrphanedAttachmentRowsFound:]
+ -[EXSStoreResetReport setPrecondition:]
+ -[EXSStoreResetReport setScope:]
+ -[EXSStoreResetReport setStaleDrainStatesCleared:]
+ -[EXSStoreResetReport setTargetRowID:]
+ -[EXSStoreResetReport setTotalNanos:]
+ -[EXSStoreResetReport setTransactionMode:]
+ -[EXSStoreResetReport setTransactionNanos:]
+ -[EXSStoreResetReport setUnpushedLocalChangesDiscarded:]
+ -[EXSStoreResetReport staleDrainStatesCleared]
+ -[EXSStoreResetReport targetRowID]
+ -[EXSStoreResetReport totalNanos]
+ -[EXSStoreResetReport totalRowsRemoved]
+ -[EXSStoreResetReport transactionMode]
+ -[EXSStoreResetReport transactionNanos]
+ -[EXSStoreResetReport unpushedLocalChangesDiscarded]
+ -[EXSStoreResetReport wipeWasComplete]
+ -[EXSStoreResetRowNote .cxx_destruct]
+ -[EXSStoreResetRowNote initWithTable:rowID:kind:reason:]
+ -[EXSStoreResetRowNote kind]
+ -[EXSStoreResetRowNote reason]
+ -[EXSStoreResetRowNote rowID]
+ -[EXSStoreResetRowNote table]
+ -[EXSStoreResetRunState .cxx_destruct]
+ -[EXSStoreResetRunState blankedFolderIDs]
+ -[EXSStoreResetRunState cancelled]
+ -[EXSStoreResetRunState changeSourceCursorsCleared]
+ -[EXSStoreResetRunState committedFilePaths]
+ -[EXSStoreResetRunState drainPositions]
+ -[EXSStoreResetRunState fatalFailure]
+ -[EXSStoreResetRunState init]
+ -[EXSStoreResetRunState pendingCounts]
+ -[EXSStoreResetRunState pendingFilePaths]
+ -[EXSStoreResetRunState setBlankedFolderIDs:]
+ -[EXSStoreResetRunState setCancelled:]
+ -[EXSStoreResetRunState setChangeSourceCursorsCleared:]
+ -[EXSStoreResetRunState setCommittedFilePaths:]
+ -[EXSStoreResetRunState setDrainPositions:]
+ -[EXSStoreResetRunState setFatalFailure:]
+ -[EXSStoreResetRunState setPendingCounts:]
+ -[EXSStoreResetRunState setPendingFilePaths:]
+ -[EXSStoreResetRunState setStaleDrainChangeSourceIDs:]
+ -[EXSStoreResetRunState setTransactionDB:]
+ -[EXSStoreResetRunState setUnitsRun:]
+ -[EXSStoreResetRunState setVisitedFolderIDs:]
+ -[EXSStoreResetRunState staleDrainChangeSourceIDs]
+ -[EXSStoreResetRunState transactionDB]
+ -[EXSStoreResetRunState unitsRun]
+ -[EXSStoreResetRunState visitedFolderIDs]
+ -[EXSSyncEngine _recordNoDataToConvertAfterRemovalOfAccount:terminalRemoval:databaseRemoved:]
+ -[EXSSyncEngineInstance _performGraphMigrationCutoverHousekeepingReportingFailureReason:]
+ -[EXSSyncEngineInstance _processOutstandingChangeItemsOnBothDrainsForProtocol:consumerInstances:]
+ -[EXSSyncEngineInstance _reinstallGraphAfterTerminalPurgeForPhase:]
+ -[EXSSyncEngineInstance _runCutoverHousekeepingPhase]
+ -[EXSSyncEngineInstance _runPreGraphMigrationPhase:]
+ -[EXSSyncEngineInstance _runTerminalPurgeForPhase:]
+ -[EXSSyncEngineInstance clientStoreDiscarderForTerminalPurge]
+ -[EXSSyncEngineInstance prepareSyncProtocolForAccountRemovalWithGroup:]
+ -[EXSSyncEngineInstance purgedThisStartup]
+ -[EXSSyncEngineInstance setPurgedThisStartup:]
+ -[EXSSyncEngineInstance setStartupDatabaseOpenResult:]
+ -[EXSSyncEngineInstance setTerminalPurgeAttemptedThisStartup:]
+ -[EXSSyncEngineInstance startupDatabaseOpenResult]
+ -[EXSSyncEngineInstance terminalPurgeAttemptedThisStartup]
+ -[EXSSyncProtocol canonicalCalendarFolderIDsForStoredIDs:deadline:outMissingIDs:]
+ -[EXSSyncProtocol canonicalCalendarFolderIDsForStoredIDs:deadline:outMissingIDs:outFailureKind:]
+ -[EXSSyncProtocol cursorOnlyChangeSourceIDs]
+ -[EXSSyncProtocol prepareForAccountRemoval]
+ -[EXSSyncProtocol prepareNotesFolderStateForGraphCutover]
+ -[EXSSyncProtocol pushDrainStoppedWithChangeItemsQueued]
+ -[EXSWebPushSubscriptionRow .cxx_destruct]
+ -[EXSWebPushSubscriptionRow changeType]
+ -[EXSWebPushSubscriptionRow dataClass]
+ -[EXSWebPushSubscriptionRow expirationAt]
+ -[EXSWebPushSubscriptionRow folderExternalID]
+ -[EXSWebPushSubscriptionRow graphResource]
+ -[EXSWebPushSubscriptionRow isActive]
+ -[EXSWebPushSubscriptionRow notificationURLHash]
+ -[EXSWebPushSubscriptionRow setChangeType:]
+ -[EXSWebPushSubscriptionRow setDataClass:]
+ -[EXSWebPushSubscriptionRow setExpirationAt:]
+ -[EXSWebPushSubscriptionRow setFolderExternalID:]
+ -[EXSWebPushSubscriptionRow setGraphResource:]
+ -[EXSWebPushSubscriptionRow setIsActive:]
+ -[EXSWebPushSubscriptionRow setNotificationURLHash:]
+ -[EXSWebPushSubscriptionRow setSubscriberKeyHash:]
+ -[EXSWebPushSubscriptionRow setSubscriptionID:]
+ -[EXSWebPushSubscriptionRow setTopic:]
+ -[EXSWebPushSubscriptionRow subscriberKeyHash]
+ -[EXSWebPushSubscriptionRow subscriptionID]
+ -[EXSWebPushSubscriptionRow topic]
+ -[EXSXPCInterfaceImplementation beginSearchDirectoryForAccountID:queryString:recordTypes:fullContactData:withReply:]
+ GCC_except_table100
+ GCC_except_table102
+ GCC_except_table103
+ GCC_except_table104
+ GCC_except_table106
+ GCC_except_table108
+ GCC_except_table110
+ GCC_except_table112
+ GCC_except_table114
+ GCC_except_table116
+ GCC_except_table120
+ GCC_except_table124
+ GCC_except_table133
+ GCC_except_table140
+ GCC_except_table153
+ GCC_except_table165
+ GCC_except_table173
+ GCC_except_table20
+ GCC_except_table22
+ GCC_except_table24
+ GCC_except_table26
+ GCC_except_table57
+ GCC_except_table59
+ GCC_except_table61
+ GCC_except_table63
+ GCC_except_table69
+ GCC_except_table70
+ GCC_except_table73
+ GCC_except_table82
+ GCC_except_table83
+ GCC_except_table87
+ GCC_except_table88
+ GCC_except_table89
+ GCC_except_table91
+ GCC_except_table98
+ _ESDCalendarDirectorySearchRecordType_Locations
+ _EXSDataclassCallGateNow
+ _EXSStoreResetAddPosition
+ _EXSStoreResetCountOrFault
+ _EXSStoreResetReadFaultReason
+ _EXSStoreResetRowIDList
+ _EXSStoreResetRowIDSlices
+ _NSCocoaErrorDomain
+ _OBJC_CLASS_$_EXSDataclassCall
+ _OBJC_CLASS_$_EXSDataclassCallGate
+ _OBJC_CLASS_$_EXSDataclassCallGateRecoveryObserver
+ _OBJC_CLASS_$_EXSGSCalendarFolderIDCanonicalizer
+ _OBJC_CLASS_$_EXSGSGraphIDConversionCoordinator
+ _OBJC_CLASS_$_EXSGSMigrationEscalation
+ _OBJC_CLASS_$_EXSGSMigrationEscalationPolicy
+ _OBJC_CLASS_$_EXSGSMigrationFailure
+ _OBJC_CLASS_$_EXSGSMigrationTerminalPurge
+ _OBJC_CLASS_$_EXSGSMigrationTerminalPurgeReport
+ _OBJC_CLASS_$_EXSGSPluginClientStoreDiscarder
+ _OBJC_CLASS_$_EXSGSWallClockTimer
+ _OBJC_CLASS_$_EXSNotesLegacyContainer
+ _OBJC_CLASS_$_EXSStoreResetDrainPosition
+ _OBJC_CLASS_$_EXSStoreResetOptions
+ _OBJC_CLASS_$_EXSStoreResetPendingCounts
+ _OBJC_CLASS_$_EXSStoreResetReport
+ _OBJC_CLASS_$_EXSStoreResetRowNote
+ _OBJC_CLASS_$_EXSStoreResetRunState
+ _OBJC_CLASS_$_EXSWebPushSubscriptionRow
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_IVAR_$_EXSAvailabilityRequestComponents._receivedAtMonotonicNanoseconds
+ _OBJC_IVAR_$_EXSCalendarItemProperties._relocateToParentCalendar
+ _OBJC_IVAR_$_EXSDataManager._databaseOpenResult
+ _OBJC_IVAR_$_EXSDataManager._staleChangeItemPruneBatchSize
+ _OBJC_IVAR_$_EXSDataclassCall._epoch
+ _OBJC_IVAR_$_EXSDataclassCall._gate
+ _OBJC_IVAR_$_EXSDataclassCallGate._consecutiveTrips
+ _OBJC_IVAR_$_EXSDataclassCallGate._durableRescues
+ _OBJC_IVAR_$_EXSDataclassCallGate._durableTransactionLabel
+ _OBJC_IVAR_$_EXSDataclassCallGate._durableTransactions
+ _OBJC_IVAR_$_EXSDataclassCallGate._durableWork
+ _OBJC_IVAR_$_EXSDataclassCallGate._epoch
+ _OBJC_IVAR_$_EXSDataclassCallGate._escalationInterval
+ _OBJC_IVAR_$_EXSDataclassCallGate._healthySinceUptime
+ _OBJC_IVAR_$_EXSDataclassCallGate._lock
+ _OBJC_IVAR_$_EXSDataclassCallGate._log
+ _OBJC_IVAR_$_EXSDataclassCallGate._loggedTerminalState
+ _OBJC_IVAR_$_EXSDataclassCallGate._name
+ _OBJC_IVAR_$_EXSDataclassCallGate._probeEnqueued
+ _OBJC_IVAR_$_EXSDataclassCallGate._probeInterval
+ _OBJC_IVAR_$_EXSDataclassCallGate._queue
+ _OBJC_IVAR_$_EXSDataclassCallGate._queueReplacements
+ _OBJC_IVAR_$_EXSDataclassCallGate._recoveryObservers
+ _OBJC_IVAR_$_EXSDataclassCallGate._tickScheduled
+ _OBJC_IVAR_$_EXSDataclassCallGate._timeout
+ _OBJC_IVAR_$_EXSDataclassCallGate._timerQueue
+ _OBJC_IVAR_$_EXSDataclassCallGate._tripped
+ _OBJC_IVAR_$_EXSDataclassCallGate._trippedAtUptime
+ _OBJC_IVAR_$_EXSDataclassCallGateRecoveryObserver._block
+ _OBJC_IVAR_$_EXSDataclassCallGateRecoveryObserver._owner
+ _OBJC_IVAR_$_EXSGSMigrationEscalationPolicy._graphMigrationEnabled
+ _OBJC_IVAR_$_EXSGSMigrationEscalationPolicy._maximumAttemptsPerPhase
+ _OBJC_IVAR_$_EXSGSMigrationFailure._kind
+ _OBJC_IVAR_$_EXSGSMigrationFailure._phase
+ _OBJC_IVAR_$_EXSGSMigrationFailure._reason
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurge._account
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurge._clientStoreDiscarder
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurge._dataManager
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurge._databaseOpenResult
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._attachmentRowsRemoved
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._changeItemsRemoved
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._clientStoreDiscardAttempts
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._clientStoresCompleted
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._clientStoresEnqueued
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._clientStoresFaulted
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._folderMapCleared
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._foldersRemoved
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._itemsRemoved
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._lastStep
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._outcome
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._staleDrainStatesCleared
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._stampAttempts
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._stamped
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._storeResetAttempts
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._storeResetPrecondition
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._unpushedLocalChangesDiscarded
+ _OBJC_IVAR_$_EXSGSMigrationTerminalPurgeReport._usedPerDataClassReset
+ _OBJC_IVAR_$_EXSGSPluginClientStoreDiscarder._instancesByFolderType
+ _OBJC_IVAR_$_EXSGSPluginClientStoreDiscarder._orderedFolderTypes
+ _OBJC_IVAR_$_EXSGraphIDMigrationOptions._stampsConversionCompletion
+ _OBJC_IVAR_$_EXSNotesLegacyContainer._containerRowExists
+ _OBJC_IVAR_$_EXSNotesLegacyContainer._legacyNotesFolderID
+ _OBJC_IVAR_$_EXSNotesLegacyContainer._messageRootIDs
+ _OBJC_IVAR_$_EXSSearchDirectoryRequest._receivedAtMonotonicNanoseconds
+ _OBJC_IVAR_$_EXSSearchDirectoryRequest._recordTypes
+ _OBJC_IVAR_$_EXSStoreResetDrainPosition._changeSourceID
+ _OBJC_IVAR_$_EXSStoreResetDrainPosition._lastChangeItemID
+ _OBJC_IVAR_$_EXSStoreResetOptions._chunkSize
+ _OBJC_IVAR_$_EXSStoreResetOptions._cursorChangeSourceIDs
+ _OBJC_IVAR_$_EXSStoreResetOptions._databaseOpenResult
+ _OBJC_IVAR_$_EXSStoreResetOptions._dryRun
+ _OBJC_IVAR_$_EXSStoreResetOptions._idleChangeSourceIDs
+ _OBJC_IVAR_$_EXSStoreResetOptions._includesOrphanedAttachmentRows
+ _OBJC_IVAR_$_EXSStoreResetOptions._includesUnpushedLocalChanges
+ _OBJC_IVAR_$_EXSStoreResetOptions._pushingChangeSourceIDs
+ _OBJC_IVAR_$_EXSStoreResetOptions._shouldCancel
+ _OBJC_IVAR_$_EXSStoreResetOptions._transactionMode
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._attachmentRowsRemoved
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._changeItemsRemoved
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._changeSourceCursorsCleared
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._changeSourceWatermarksZeroed
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._detachedOccurrenceChangeItemsReported
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._distinguishedFolderRowsRemoved
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._foldersRemoved
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._foldersRetainedForSkippedItems
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._foldersSkippedForUnpushedLocalChanges
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._foldersSyncStateCleared
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._foldersSyncStateClearedTakenBack
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._itemsRemoved
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._itemsSkippedForUnpushedLocalChanges
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._notes
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._staleDrainStatesCleared
+ _OBJC_IVAR_$_EXSStoreResetPendingCounts._unpushedLocalChangesDiscarded
+ _OBJC_IVAR_$_EXSStoreResetReport._abortReason
+ _OBJC_IVAR_$_EXSStoreResetReport._accountKey
+ _OBJC_IVAR_$_EXSStoreResetReport._attachmentFilesFailedToUnlink
+ _OBJC_IVAR_$_EXSStoreResetReport._attachmentFilesUnlinked
+ _OBJC_IVAR_$_EXSStoreResetReport._attachmentRowsRemoved
+ _OBJC_IVAR_$_EXSStoreResetReport._cancelled
+ _OBJC_IVAR_$_EXSStoreResetReport._changeItemsRemoved
+ _OBJC_IVAR_$_EXSStoreResetReport._changeSourceCursorsCleared
+ _OBJC_IVAR_$_EXSStoreResetReport._changeSourceWatermarksZeroed
+ _OBJC_IVAR_$_EXSStoreResetReport._chunkSize
+ _OBJC_IVAR_$_EXSStoreResetReport._chunksCommitted
+ _OBJC_IVAR_$_EXSStoreResetReport._committed
+ _OBJC_IVAR_$_EXSStoreResetReport._databaseSchemaVersion
+ _OBJC_IVAR_$_EXSStoreResetReport._detachedOccurrenceChangeItemsReported
+ _OBJC_IVAR_$_EXSStoreResetReport._distinguishedFolderRowsRemoved
+ _OBJC_IVAR_$_EXSStoreResetReport._dryRun
+ _OBJC_IVAR_$_EXSStoreResetReport._foldersRemoved
+ _OBJC_IVAR_$_EXSStoreResetReport._foldersRetainedForSkippedItems
+ _OBJC_IVAR_$_EXSStoreResetReport._foldersSkippedForUnpushedLocalChanges
+ _OBJC_IVAR_$_EXSStoreResetReport._foldersSyncStateCleared
+ _OBJC_IVAR_$_EXSStoreResetReport._itemsRemoved
+ _OBJC_IVAR_$_EXSStoreResetReport._itemsSkippedForUnpushedLocalChanges
+ _OBJC_IVAR_$_EXSStoreResetReport._mutableNotes
+ _OBJC_IVAR_$_EXSStoreResetReport._orphanedAttachmentRowsFound
+ _OBJC_IVAR_$_EXSStoreResetReport._precondition
+ _OBJC_IVAR_$_EXSStoreResetReport._scope
+ _OBJC_IVAR_$_EXSStoreResetReport._staleDrainStatesCleared
+ _OBJC_IVAR_$_EXSStoreResetReport._targetRowID
+ _OBJC_IVAR_$_EXSStoreResetReport._totalNanos
+ _OBJC_IVAR_$_EXSStoreResetReport._transactionMode
+ _OBJC_IVAR_$_EXSStoreResetReport._transactionNanos
+ _OBJC_IVAR_$_EXSStoreResetReport._unpushedLocalChangesDiscarded
+ _OBJC_IVAR_$_EXSStoreResetRowNote._kind
+ _OBJC_IVAR_$_EXSStoreResetRowNote._reason
+ _OBJC_IVAR_$_EXSStoreResetRowNote._rowID
+ _OBJC_IVAR_$_EXSStoreResetRowNote._table
+ _OBJC_IVAR_$_EXSStoreResetRunState._blankedFolderIDs
+ _OBJC_IVAR_$_EXSStoreResetRunState._cancelled
+ _OBJC_IVAR_$_EXSStoreResetRunState._changeSourceCursorsCleared
+ _OBJC_IVAR_$_EXSStoreResetRunState._committedFilePaths
+ _OBJC_IVAR_$_EXSStoreResetRunState._drainPositions
+ _OBJC_IVAR_$_EXSStoreResetRunState._fatalFailure
+ _OBJC_IVAR_$_EXSStoreResetRunState._pendingCounts
+ _OBJC_IVAR_$_EXSStoreResetRunState._pendingFilePaths
+ _OBJC_IVAR_$_EXSStoreResetRunState._staleDrainChangeSourceIDs
+ _OBJC_IVAR_$_EXSStoreResetRunState._transactionDB
+ _OBJC_IVAR_$_EXSStoreResetRunState._unitsRun
+ _OBJC_IVAR_$_EXSStoreResetRunState._visitedFolderIDs
+ _OBJC_IVAR_$_EXSSyncEngineInstance._purgedThisStartup
+ _OBJC_IVAR_$_EXSSyncEngineInstance._startupDatabaseOpenResult
+ _OBJC_IVAR_$_EXSSyncEngineInstance._terminalPurgeAttemptedThisStartup
+ _OBJC_IVAR_$_EXSSyncProtocol._lastReadUpsyncWatermark
+ _OBJC_IVAR_$_EXSSyncProtocol._lastSettledUpsyncChangeID
+ _OBJC_IVAR_$_EXSWebPushSubscriptionRow._changeType
+ _OBJC_IVAR_$_EXSWebPushSubscriptionRow._dataClass
+ _OBJC_IVAR_$_EXSWebPushSubscriptionRow._expirationAt
+ _OBJC_IVAR_$_EXSWebPushSubscriptionRow._folderExternalID
+ _OBJC_IVAR_$_EXSWebPushSubscriptionRow._graphResource
+ _OBJC_IVAR_$_EXSWebPushSubscriptionRow._isActive
+ _OBJC_IVAR_$_EXSWebPushSubscriptionRow._notificationURLHash
+ _OBJC_IVAR_$_EXSWebPushSubscriptionRow._subscriberKeyHash
+ _OBJC_IVAR_$_EXSWebPushSubscriptionRow._subscriptionID
+ _OBJC_IVAR_$_EXSWebPushSubscriptionRow._topic
+ _OBJC_METACLASS_$_EXSDataclassCall
+ _OBJC_METACLASS_$_EXSDataclassCallGate
+ _OBJC_METACLASS_$_EXSDataclassCallGateRecoveryObserver
+ _OBJC_METACLASS_$_EXSGSCalendarFolderIDCanonicalizer
+ _OBJC_METACLASS_$_EXSGSGraphIDConversionCoordinator
+ _OBJC_METACLASS_$_EXSGSMigrationEscalation
+ _OBJC_METACLASS_$_EXSGSMigrationEscalationPolicy
+ _OBJC_METACLASS_$_EXSGSMigrationFailure
+ _OBJC_METACLASS_$_EXSGSMigrationTerminalPurge
+ _OBJC_METACLASS_$_EXSGSMigrationTerminalPurgeReport
+ _OBJC_METACLASS_$_EXSGSPluginClientStoreDiscarder
+ _OBJC_METACLASS_$_EXSGSWallClockTimer
+ _OBJC_METACLASS_$_EXSNotesLegacyContainer
+ _OBJC_METACLASS_$_EXSStoreResetDrainPosition
+ _OBJC_METACLASS_$_EXSStoreResetOptions
+ _OBJC_METACLASS_$_EXSStoreResetPendingCounts
+ _OBJC_METACLASS_$_EXSStoreResetReport
+ _OBJC_METACLASS_$_EXSStoreResetRowNote
+ _OBJC_METACLASS_$_EXSStoreResetRunState
+ _OBJC_METACLASS_$_EXSWebPushSubscriptionRow
+ _OUTLINED_FUNCTION_10
+ _OUTLINED_FUNCTION_11
+ _OUTLINED_FUNCTION_12
+ _OUTLINED_FUNCTION_13
+ _OUTLINED_FUNCTION_9
+ _SecItemAdd
+ _SecItemCopyMatching
+ _SecItemDelete
+ _SecItemUpdate
+ __CLASS_METHODS_EXSGSSyncProtocol
+ __CLASS_METHODS_EXSGSWallClockTimer
+ __CLASS_PROPERTIES_EXSGSSyncProtocol
+ __DATA_EXSGSWallClockTimer
+ __DATA__TtC12ExchangeSync22EXSGSHeartbeatTickGate
+ __DATA__TtC12ExchangeSync23EXSGSBoundedTransaction
+ __DATA__TtC12ExchangeSync23EXSGSHeartbeatScheduler
+ __DATA__TtC12ExchangeSync23EXSGSThrottleController
+ __DATA__TtC12ExchangeSync25EXSGSThrottleHoldingQueue
+ __DATA__TtC12ExchangeSync39EXSGSPersistentWebPushSubscriptionStore
+ __DATA__TtC12ExchangeSyncP33_463083CFCC0FD2DAF1C8E64D936A313B17PublishedDeadline
+ __DATA__TtC12ExchangeSyncP33_F6D46D85F031ADDD4AE009C1F681546F35EXSGSHeartbeatSchedulerRegistration
+ __DATA__TtCC12ExchangeSync23EXSGSThrottleController7WeakBox
+ __DATA__TtCC12ExchangeSync25EXSGSThrottleHoldingQueueP33_9504B189D9B1AD4B4D0CA7B11235DD0412ReleaseToken
+ __INSTANCE_METHODS_EXSGSWallClockTimer
+ __IVARS__TtC12ExchangeSync22EXSGSHeartbeatTickGate
+ __IVARS__TtC12ExchangeSync23EXSGSBoundedTransaction
+ __IVARS__TtC12ExchangeSync23EXSGSHeartbeatScheduler
+ __IVARS__TtC12ExchangeSync23EXSGSThrottleController
+ __IVARS__TtC12ExchangeSync25EXSGSThrottleHoldingQueue
+ __IVARS__TtC12ExchangeSync39EXSGSPersistentWebPushSubscriptionStore
+ __IVARS__TtC12ExchangeSyncP33_463083CFCC0FD2DAF1C8E64D936A313B17PublishedDeadline
+ __IVARS__TtC12ExchangeSyncP33_463083CFCC0FD2DAF1C8E64D936A313B9OnceReply
+ __IVARS__TtC12ExchangeSyncP33_F6D46D85F031ADDD4AE009C1F681546F35EXSGSHeartbeatSchedulerRegistration
+ __IVARS__TtCC12ExchangeSync23EXSGSThrottleController7WeakBox
+ __IVARS__TtCC12ExchangeSync25EXSGSThrottleHoldingQueueP33_9504B189D9B1AD4B4D0CA7B11235DD0412ReleaseToken
+ __METACLASS_DATA_EXSGSWallClockTimer
+ __METACLASS_DATA__TtC12ExchangeSync22EXSGSHeartbeatTickGate
+ __METACLASS_DATA__TtC12ExchangeSync23EXSGSBoundedTransaction
+ __METACLASS_DATA__TtC12ExchangeSync23EXSGSHeartbeatScheduler
+ __METACLASS_DATA__TtC12ExchangeSync23EXSGSThrottleController
+ __METACLASS_DATA__TtC12ExchangeSync25EXSGSThrottleHoldingQueue
+ __METACLASS_DATA__TtC12ExchangeSync39EXSGSPersistentWebPushSubscriptionStore
+ __METACLASS_DATA__TtC12ExchangeSyncP33_463083CFCC0FD2DAF1C8E64D936A313B17PublishedDeadline
+ __METACLASS_DATA__TtC12ExchangeSyncP33_F6D46D85F031ADDD4AE009C1F681546F35EXSGSHeartbeatSchedulerRegistration
+ __METACLASS_DATA__TtCC12ExchangeSync23EXSGSThrottleController7WeakBox
+ __METACLASS_DATA__TtCC12ExchangeSync25EXSGSThrottleHoldingQueueP33_9504B189D9B1AD4B4D0CA7B11235DD0412ReleaseToken
+ __OBJC_$_CLASS_METHODS_EXSDataclassCallGate(ForTesting)
+ __OBJC_$_CLASS_METHODS_EXSGSCalendarFolderIDCanonicalizer
+ __OBJC_$_CLASS_METHODS_EXSGSGraphIDConversionCoordinator
+ __OBJC_$_CLASS_METHODS_EXSGSMigrationEscalation
+ __OBJC_$_CLASS_METHODS_EXSGSMigrationEscalationPolicy
+ __OBJC_$_CLASS_METHODS_EXSGSMigrationFailure
+ __OBJC_$_CLASS_METHODS_EXSStoreResetOptions
+ __OBJC_$_CLASS_PROP_LIST_EXSGSCalendarFolderIDCanonicalizer
+ __OBJC_$_CLASS_PROP_LIST_EXSGSGraphIDConversionCoordinator
+ __OBJC_$_CLASS_PROP_LIST_EXSGSMigrationEscalation
+ __OBJC_$_INSTANCE_METHODS_EXSDataManager(Folders|Folders_Private|Items|Items_Private|Migration|GraphIDMigration|Attachments|StoreReset|ChangeItems)
+ __OBJC_$_INSTANCE_METHODS_EXSDataclassCall
+ __OBJC_$_INSTANCE_METHODS_EXSDataclassCallGate
+ __OBJC_$_INSTANCE_METHODS_EXSDataclassCallGateRecoveryObserver
+ __OBJC_$_INSTANCE_METHODS_EXSGSMigrationEscalationPolicy
+ __OBJC_$_INSTANCE_METHODS_EXSGSMigrationFailure
+ __OBJC_$_INSTANCE_METHODS_EXSGSMigrationTerminalPurge
+ __OBJC_$_INSTANCE_METHODS_EXSGSMigrationTerminalPurgeReport
+ __OBJC_$_INSTANCE_METHODS_EXSGSPluginClientStoreDiscarder
+ __OBJC_$_INSTANCE_METHODS_EXSGSSyncProtocol(ExchangeSync|ExchangeSync|ExchangeSync1|ExchangeSync|ExchangeSync|ExchangeSync1)
+ __OBJC_$_INSTANCE_METHODS_EXSNotesLegacyContainer
+ __OBJC_$_INSTANCE_METHODS_EXSStoreResetDrainPosition
+ __OBJC_$_INSTANCE_METHODS_EXSStoreResetOptions
+ __OBJC_$_INSTANCE_METHODS_EXSStoreResetPendingCounts
+ __OBJC_$_INSTANCE_METHODS_EXSStoreResetReport
+ __OBJC_$_INSTANCE_METHODS_EXSStoreResetRowNote
+ __OBJC_$_INSTANCE_METHODS_EXSStoreResetRunState
+ __OBJC_$_INSTANCE_METHODS_EXSWebPushSubscriptionRow
+ __OBJC_$_INSTANCE_VARIABLES_EXSDataclassCall
+ __OBJC_$_INSTANCE_VARIABLES_EXSDataclassCallGate
+ __OBJC_$_INSTANCE_VARIABLES_EXSDataclassCallGateRecoveryObserver
+ __OBJC_$_INSTANCE_VARIABLES_EXSGSMigrationEscalationPolicy
+ __OBJC_$_INSTANCE_VARIABLES_EXSGSMigrationFailure
+ __OBJC_$_INSTANCE_VARIABLES_EXSGSMigrationTerminalPurge
+ __OBJC_$_INSTANCE_VARIABLES_EXSGSMigrationTerminalPurgeReport
+ __OBJC_$_INSTANCE_VARIABLES_EXSGSPluginClientStoreDiscarder
+ __OBJC_$_INSTANCE_VARIABLES_EXSNotesLegacyContainer
+ __OBJC_$_INSTANCE_VARIABLES_EXSStoreResetDrainPosition
+ __OBJC_$_INSTANCE_VARIABLES_EXSStoreResetOptions
+ __OBJC_$_INSTANCE_VARIABLES_EXSStoreResetPendingCounts
+ __OBJC_$_INSTANCE_VARIABLES_EXSStoreResetReport
+ __OBJC_$_INSTANCE_VARIABLES_EXSStoreResetRowNote
+ __OBJC_$_INSTANCE_VARIABLES_EXSStoreResetRunState
+ __OBJC_$_INSTANCE_VARIABLES_EXSWebPushSubscriptionRow
+ __OBJC_$_PROP_LIST_EXSDataclassCall
+ __OBJC_$_PROP_LIST_EXSDataclassCallGateRecoveryObserver
+ __OBJC_$_PROP_LIST_EXSGSMigrationEscalationPolicy
+ __OBJC_$_PROP_LIST_EXSGSMigrationFailure
+ __OBJC_$_PROP_LIST_EXSGSMigrationTerminalPurge
+ __OBJC_$_PROP_LIST_EXSGSMigrationTerminalPurgeReport
+ __OBJC_$_PROP_LIST_EXSGSPluginClientStoreDiscarder
+ __OBJC_$_PROP_LIST_EXSNotesLegacyContainer
+ __OBJC_$_PROP_LIST_EXSStoreResetDrainPosition
+ __OBJC_$_PROP_LIST_EXSStoreResetOptions
+ __OBJC_$_PROP_LIST_EXSStoreResetPendingCounts
+ __OBJC_$_PROP_LIST_EXSStoreResetReport
+ __OBJC_$_PROP_LIST_EXSStoreResetRowNote
+ __OBJC_$_PROP_LIST_EXSStoreResetRunState
+ __OBJC_$_PROP_LIST_EXSWebPushSubscriptionRow
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_EXSGSClientStoreDiscarding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCopying
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_EXSChangeItemPushing
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_EXSDataConsumerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_EXSGSClientStoreDiscarding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCopying
+ __OBJC_$_PROTOCOL_REFS_EXSGSClientStoreDiscarding
+ __OBJC_CLASS_PROTOCOLS_$_EXSGSPluginClientStoreDiscarder
+ __OBJC_CLASS_PROTOCOLS_$_EXSGSSyncProtocol(ExchangeSync|ExchangeSync|ExchangeSync1|ExchangeSync|ExchangeSync|ExchangeSync1)
+ __OBJC_CLASS_PROTOCOLS_$_EXSStoreResetOptions
+ __OBJC_CLASS_RO_$_EXSDataclassCall
+ __OBJC_CLASS_RO_$_EXSDataclassCallGate
+ __OBJC_CLASS_RO_$_EXSDataclassCallGateRecoveryObserver
+ __OBJC_CLASS_RO_$_EXSGSCalendarFolderIDCanonicalizer
+ __OBJC_CLASS_RO_$_EXSGSGraphIDConversionCoordinator
+ __OBJC_CLASS_RO_$_EXSGSMigrationEscalation
+ __OBJC_CLASS_RO_$_EXSGSMigrationEscalationPolicy
+ __OBJC_CLASS_RO_$_EXSGSMigrationFailure
+ __OBJC_CLASS_RO_$_EXSGSMigrationTerminalPurge
+ __OBJC_CLASS_RO_$_EXSGSMigrationTerminalPurgeReport
+ __OBJC_CLASS_RO_$_EXSGSPluginClientStoreDiscarder
+ __OBJC_CLASS_RO_$_EXSNotesLegacyContainer
+ __OBJC_CLASS_RO_$_EXSStoreResetDrainPosition
+ __OBJC_CLASS_RO_$_EXSStoreResetOptions
+ __OBJC_CLASS_RO_$_EXSStoreResetPendingCounts
+ __OBJC_CLASS_RO_$_EXSStoreResetReport
+ __OBJC_CLASS_RO_$_EXSStoreResetRowNote
+ __OBJC_CLASS_RO_$_EXSStoreResetRunState
+ __OBJC_CLASS_RO_$_EXSWebPushSubscriptionRow
+ __OBJC_LABEL_PROTOCOL_$_EXSGSClientStoreDiscarding
+ __OBJC_LABEL_PROTOCOL_$_NSCopying
+ __OBJC_METACLASS_RO_$_EXSDataclassCall
+ __OBJC_METACLASS_RO_$_EXSDataclassCallGate
+ __OBJC_METACLASS_RO_$_EXSDataclassCallGateRecoveryObserver
+ __OBJC_METACLASS_RO_$_EXSGSCalendarFolderIDCanonicalizer
+ __OBJC_METACLASS_RO_$_EXSGSGraphIDConversionCoordinator
+ __OBJC_METACLASS_RO_$_EXSGSMigrationEscalation
+ __OBJC_METACLASS_RO_$_EXSGSMigrationEscalationPolicy
+ __OBJC_METACLASS_RO_$_EXSGSMigrationFailure
+ __OBJC_METACLASS_RO_$_EXSGSMigrationTerminalPurge
+ __OBJC_METACLASS_RO_$_EXSGSMigrationTerminalPurgeReport
+ __OBJC_METACLASS_RO_$_EXSGSPluginClientStoreDiscarder
+ __OBJC_METACLASS_RO_$_EXSNotesLegacyContainer
+ __OBJC_METACLASS_RO_$_EXSStoreResetDrainPosition
+ __OBJC_METACLASS_RO_$_EXSStoreResetOptions
+ __OBJC_METACLASS_RO_$_EXSStoreResetPendingCounts
+ __OBJC_METACLASS_RO_$_EXSStoreResetReport
+ __OBJC_METACLASS_RO_$_EXSStoreResetRowNote
+ __OBJC_METACLASS_RO_$_EXSStoreResetRunState
+ __OBJC_METACLASS_RO_$_EXSWebPushSubscriptionRow
+ __OBJC_PROTOCOL_$_EXSGSClientStoreDiscarding
+ __OBJC_PROTOCOL_$_NSCopying
+ ___100-[EXSDataManager(ChangeItems) externalIDsWithUnpushedChangesOfItemType:pastWatermarkOfChangeSource:]_block_invoke
+ ___102-[EXSDataManager(ChangeItems) recordCreatedExternalID:externalChangeKey:onLaterDeletionsOfChangeItem:]_block_invoke
+ ___102-[EXSDataManager(StoreReset) _storeResetDeleteDistinguishedRowsForExternalID:db:options:report:state:]_block_invoke
+ ___103-[EXSDataManager(StoreReset) _storeResetDeleteFolderChangeItemsForFolderRowID:db:options:report:state:]_block_invoke
+ ___122-[EXSDataManager(StoreReset) _runStoreResetWithScope:targetRowID:targetInternalID:folderType:verifyAccount:callerOptions:]_block_invoke
+ ___123-[EXSDataManager(StoreReset) _storeResetDeleteItemChunkWithRowIDs:externalIDs:internalIDs:skipped:db:options:report:state:]_block_invoke
+ ___123-[EXSDataManager(StoreReset) _storeResetDeleteItemChunkWithRowIDs:externalIDs:internalIDs:skipped:db:options:report:state:]_block_invoke_2
+ ___135-[EXSDataManager(StoreReset) _performStoreResetWithScope:targetRowID:targetInternalID:folderType:accountMismatch:options:report:state:]_block_invoke
+ ___29+[EXSSyncProtocolFactory log]_block_invoke
+ ___29-[EXSDataclassCallGate _tick]_block_invoke
+ ___31+[EXSGSMigrationEscalation log]_block_invoke
+ ___36-[EXSDataclassCallGate _runAndWait:]_block_invoke
+ ___37-[EXSDataclassCallGate _scheduleTick]_block_invoke
+ ___40+[EXSGSGraphIDConversionCoordinator log]_block_invoke
+ ___40-[EXSEWSSyncProtocol syncAllFolderItems]_block_invoke
+ ___41+[EXSDataclassCallGate gateForDataclass:]_block_invoke
+ ___41+[EXSGSCalendarFolderIDCanonicalizer log]_block_invoke
+ ___41-[EXSDataManager webPushSubscriptionRows]_block_invoke
+ ___44-[EXSDataManager(Items) findItemWithItemID:]_block_invoke
+ ___45-[EXSDataclassCallGate _probeDidRunForEpoch:]_block_invoke
+ ___46-[EXSDataManager recordTerminalPurgeCompleted]_block_invoke
+ ___46-[EXSDataManager recordTerminalPurgeCompleted]_block_invoke_2
+ ___47-[EXSDataManager upsertWebPushSubscriptionRow:]_block_invoke
+ ___50-[EXSDataManager deleteAllWebPushSubscriptionRows]_block_invoke
+ ___51-[EXSDataManager getGraphIDConversionAttemptCount:]_block_invoke
+ ___51-[EXSDataManager(StoreReset) _logStoreResetReport:]_block_invoke
+ ___52+[EXSEWSSyncUtils buildEWSRecurrenceFromProperties:]_block_invoke
+ ___52-[EXSDataclassCallGate performSynchronously:result:]_block_invoke
+ ___56-[EXSDataclassCallGate performSynchronouslyBOOL:result:]_block_invoke
+ ___57-[EXSEWSUpdateItemOperation executeWithChangeItem:error:]_block_invoke
+ ___59-[EXSDataManager cleanupStaleDataExcludingChangeSourceIDs:]_block_invoke
+ ___59-[EXSDataManager(ChangeItems) clearCreateTokenForChangeID:]_block_invoke
+ ___59-[EXSDataclassCallGate _dispatchDurableWork:token:onQueue:]_block_invoke
+ ___60-[EXSDataManager(ChangeItems) hasLaterDeletionOfChangeItem:]_block_invoke
+ ___60-[EXSDataclassCallGate tryPerformAsynchronouslyAfter:block:]_block_invoke
+ ___61-[EXSDataManager(GraphIDMigration) rewriteFolderExternalIDs:]_block_invoke
+ ___61-[EXSDataManager(GraphIDMigration) rewriteFolderExternalIDs:]_block_invoke_2
+ ___61-[EXSSyncEngineInstance clientStoreDiscarderForTerminalPurge]_block_invoke
+ ___64-[EXSDataManager(ChangeItems) createTokenForChangeID:mintedNow:]_block_invoke
+ ___65-[EXSDataManager _updateGraphMigrationRowWithAssignment:context:]_block_invoke
+ ___65-[EXSDataManager(ChangeItems) hasUpsyncChangeItemsSinceChangeID:]_block_invoke
+ ___65-[EXSEWSUpdateCalendarItemOperation executeWithChangeItem:error:]_block_invoke
+ ___70-[EXSDataManager(GraphIDMigration) hasAnyLocalRowsForGraphIDMigration]_block_invoke
+ ___71-[EXSSyncEngineInstance prepareSyncProtocolForAccountRemovalWithGroup:]_block_invoke
+ ___72-[EXSDataManager(StoreReset) _storeResetFolderRow:options:report:state:]_block_invoke
+ ___72-[EXSDataManager(StoreReset) _storeResetFolderRow:options:report:state:]_block_invoke_2
+ ___74-[EXSDataManager(StoreReset) _storeResetPerformUnit:options:report:state:]_block_invoke
+ ___76-[EXSDataManager deleteWebPushSubscriptionRowForDataClass:folderExternalID:]_block_invoke
+ ___76-[EXSDataManager(StoreReset) _storeResetItemWithRowID:options:report:state:]_block_invoke
+ ___77-[EXSDataManager(ChangeItems) getUpsyncChangeItemsSinceChangeID:shouldBatch:]_block_invoke
+ ___77-[EXSDataManager(StoreReset) _storeResetEntireStoreWithOptions:report:state:]_block_invoke
+ ___77-[EXSDataManager(StoreReset) _storeResetEntireStoreWithOptions:report:state:]_block_invoke_2
+ ___77-[EXSDataManager(StoreReset) _storeResetEntireStoreWithOptions:report:state:]_block_invoke_3
+ ___77-[EXSDataManager(StoreReset) _storeResetEntireStoreWithOptions:report:state:]_block_invoke_4
+ ___77-[EXSDataManager(StoreReset) _storeResetEntireStoreWithOptions:report:state:]_block_invoke_5
+ ___77-[EXSDataManager(StoreReset) _storeResetEntireStoreWithOptions:report:state:]_block_invoke_6
+ ___78-[EXSDataManager(ChangeItems) _getUpsyncChangeItemsSinceChangeID:shouldBatch:]_block_invoke
+ ___78-[EXSDataManager(StoreReset) _storeResetItemsInFolderID:options:report:state:]_block_invoke
+ ___85-[EXSDataManager(GraphIDMigration) calendarFolderExternalIDsForGraphCanonicalization]_block_invoke
+ ___85-[EXSDataManager(GraphIDMigration) legacyNotesContainerForGraphCutoverWithContainer:]_block_invoke
+ ___87-[EXSDataManager(GraphIDMigration) foldLegacyNotesFolder:messageRootIDs:intoContainer:]_block_invoke
+ ___87-[EXSDataManager(GraphIDMigration) foldLegacyNotesFolder:messageRootIDs:intoContainer:]_block_invoke_2
+ ___87-[EXSDataManager(StoreReset) _storeResetClearAllServerCursorsWithOptions:report:state:]_block_invoke
+ ___87-[EXSDataManager(StoreReset) _storeResetClearAllServerCursorsWithOptions:report:state:]_block_invoke_2
+ ___87-[EXSDataManager(StoreReset) _storeResetClearChangeSourceCursors:options:report:state:]_block_invoke
+ ___87-[EXSDataManager(StoreReset) _storeResetClearChangeSourceCursors:options:report:state:]_block_invoke_2
+ ___87-[EXSDataManager(StoreReset) _storeResetClearStaleDrainStatesWithOptions:report:state:]_block_invoke
+ ___87-[EXSDataManager(StoreReset) _storeResetClearStaleDrainStatesWithOptions:report:state:]_block_invoke_2
+ ___88-[EXSDataManager(StoreReset) _storeResetOrphanBucketForFolderType:options:report:state:]_block_invoke
+ ___95-[EXSDataManager(ChangeItems) _getChangeItemsSinceChangeID:skippingChangeSourceID:shouldBatch:]_block_invoke
+ ___95-[EXSDataManager(StoreReset) _storeResetClearFolderSyncStateForFolderIDs:options:report:state:]_block_invoke
+ ___95-[EXSDataManager(StoreReset) _storeResetClearFolderSyncStateForFolderIDs:options:report:state:]_block_invoke_2
+ ___95-[EXSDataManager(StoreReset) _storeResetZeroChangeSourceWatermarksWithDB:options:report:state:]_block_invoke
+ ___97+[EXSGSGraphIDConversionCoordinator _cancellationCheckWithDataManager:deadline:deadlineExceeded:]_block_invoke
+ ___97-[EXSDataManager advanceLastChangeIDForChangeSource:inAccount:fromChangeID:pastDeclinedChangeID:]_block_invoke
+ ___block_descriptor_120_e8_32s40s48s56s64s_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_32_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_40_e8_32s_e25_"PQLResultSet"24?0q8q16l
+ ___block_descriptor_40_e8_32s_e37_"EWSBaseItemIdType"16?0"NSString"8l
+ ___block_descriptor_40_e8_32w_e56_"EXSDataConsumerInstance"16?0"EXSDataConsumerPlugin"8l
+ ___block_descriptor_48_e8_32bs40r_e26_v16?0"EXSDataclassCall"8l
+ ___block_descriptor_48_e8_32r_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_48_e8_32s40s_e25_"PQLResultSet"24?0q8q16l
+ ___block_descriptor_48_e8_32s40s_e29_v32?0"NSUUID"8?<v?>16^B24l
+ ___block_descriptor_48_e8_32s_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_48_e8_32s_e5_v8?0l
+ ___block_descriptor_56_e8_32bs40r48r_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_56_e8_32s40s48s_e37_"EWSBaseItemIdType"16?0"NSString"8l
+ ___block_descriptor_56_e8_32s40s_e34_"NSDateComponents"16?0"NSDate"8l
+ ___block_descriptor_56_e8_32w_e5_B8?0l
+ ___block_descriptor_57_e8_32s40r_e5_v8?0l
+ ___block_descriptor_64_e8_32s40r48r_e5_v8?0l
+ ___block_descriptor_64_e8_32s40s48r56r_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48s56s64s_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_73_e8_32s40s48s56s64bs_e5_v8?0l
+ ___block_descriptor_80_e8_32s40s48s56r_e5_v8?0l
+ ___block_descriptor_80_e8_32s40s48s56s64r_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_81_e8_32s40s48s56s64s_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_88_e8_32s40s48s56s64s72s80r_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_88_e8_32s40s48s56s64s72s80s_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_88_e8_32s40s48s56s64s72s_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_88_e8_32s40s48s56s_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_96_e8_32s40s48s56s64r_e5_v8?0l
+ ___block_descriptor_96_e8_32s40s48s56s64s72s80s88r_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_97_e8_32s40s48s56s64s_e5_v8?0l
+ ___copy_helper_block_e8_32b40r
+ ___copy_helper_block_e8_32b40r48r
+ ___copy_helper_block_e8_32s40s48s56s64s72s
+ ___copy_helper_block_e8_32s40s48s56s64s72s80r
+ ___copy_helper_block_e8_32s40s48s56s64s72s80s
+ ___copy_helper_block_e8_32s40s48s56s64s72s80s88r
+ ___destroy_helper_block_e8_32s40s48s56s64s72s
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80r
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80s
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88r
+ ___swift_closure_destructor.38Tm
+ ___swift_closure_destructor.4Tm
+ ___swift_memcpy144_8
+ ___swift_memcpy18_8
+ ___swift_memcpy4_4
+ ___swift_memcpy51_8
+ ___swift_memcpy58_8
+ ___unnamed_16
+ __logStoreResetReport:.log
+ __logStoreResetReport:.onceToken
+ __testLiveACAccountResolver
+ _associated conformance 12ExchangeSync11EXSGSConfigO9HeartbeatO14CadenceProfileOSHAASQ
+ _associated conformance 12ExchangeSync11EXSGSConfigO9HeartbeatO14CadenceProfileOs12CaseIterableAA8AllCasessAHP_Sl
+ _associated conformance 12ExchangeSync12EXSGSHoldKeyOSHAASQ
+ _associated conformance 12ExchangeSync14EXSGSHoldClassOSHAASQ
+ _associated conformance 12ExchangeSync14EXSGSHoldClassOSLAASQ
+ _associated conformance 12ExchangeSync17EXSGSThrottleGateC10TransitionOSHAASQ
+ _associated conformance 12ExchangeSync19EXSWebPushKeyRecordV10CodingKeysOSHAASQ
+ _associated conformance 12ExchangeSync19EXSWebPushKeyRecordV10CodingKeysOs0gE0AAs23CustomStringConvertible
+ _associated conformance 12ExchangeSync19EXSWebPushKeyRecordV10CodingKeysOs0gE0AAs28CustomDebugStringConvertible
+ _associated conformance 12ExchangeSync23EXSGSWebPushCoordinatorC14TeardownReasonOSHAASQ
+ _associated conformance 12ExchangeSync26EXSGSHeartbeatRefreshScopeOSHAASQ
+ _associated conformance 12ExchangeSync31EXSGSMoveCalendarEventOperationV10SkipReasonOSHAASQ
+ _associated conformance So17EXSGSSyncProtocolC12ExchangeSyncE23PendingCreateResolutionOSHACSQ
+ _associated conformance So17EXSGSSyncProtocolC12ExchangeSyncE26WebPushCoverageEntryActionOSHACSQ
+ _associated conformance So17EXSGSSyncProtocolC12ExchangeSyncE31WebPushRemovalCoordinatorSourceOSHACSQ
+ _clock_gettime_nsec_np
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
+ _gateForDataclass:.gates
+ _gateForDataclass:.gatesLock
+ _gateForDataclass:.onceToken
+ _generic environment l
+ _get_enum_tag_for_layout_string 12ExchangeSync12EXSGSHoldKeyO
+ _get_enum_tag_for_layout_string 12ExchangeSync19EXSGSNoteFolderEdgeO
+ _kEXSDataclassCallGateEpochKey
+ _kEXSDataclassCallGateIdentityKey
+ _kEXSGraphFolderIDValueRewriteStatements
+ _kSecAttrAccessGroup
+ _kSecAttrAccessible
+ _kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly
+ _kSecAttrAccount
+ _kSecAttrService
+ _kSecClass
+ _kSecClassGenericPassword
+ _kSecMatchLimit
+ _kSecMatchLimitAll
+ _kSecMatchLimitOne
+ _kSecReturnAttributes
+ _kSecReturnData
+ _kSecUseDataProtectionKeychain
+ _kSecValueData
+ _lstat
+ _memcmp
+ _objc_msgSend$ItemChanges
+ _objc_msgSend$_accumulateResetReport:intoReport:
+ _objc_msgSend$_adjustGraphIDConversionAttemptCountBy:context:
+ _objc_msgSend$_buildItemSettersForTaskChangeItem:contextZone:
+ _objc_msgSend$_cancellationCheckWithDataManager:deadline:deadlineExceeded:
+ _objc_msgSend$_changeItemsSinceChangeID:shouldBatch:fetchBatch:
+ _objc_msgSend$_clearChangeTokenAfterClientStoreTeardownForConsumer:
+ _objc_msgSend$_collapseSiblingsOfItem:fromRows:repointingChangeItemsTo:usingDBConnection:
+ _objc_msgSend$_consumer:wantsAnyOfChangeItems:
+ _objc_msgSend$_createTaskItemTypeForChangeItem:contextZone:
+ _objc_msgSend$_createWebPushSubscriptionsTableWithDB:
+ _objc_msgSend$_creditRecoveredReplacementLocked
+ _objc_msgSend$_currentProbeIntervalLocked
+ _objc_msgSend$_decodeMigrationStateFromACAccount:accountKey:
+ _objc_msgSend$_discardClientStoresIntoReport:
+ _objc_msgSend$_dispatchDurableWork:token:onQueue:
+ _objc_msgSend$_ensureChangeItemsCreateTokenColumnWithDB:
+ _objc_msgSend$_ensureDurableTransactionsLocked
+ _objc_msgSend$_ensureItemsExternalIDIndexWithDB:
+ _objc_msgSend$_ensureWebPushSubscriptionsTableWithDB:schemaVersion:
+ _objc_msgSend$_failureWithPhase:kind:reason:
+ _objc_msgSend$_fetchCurrentChangeKeyForItemWithExternalID:
+ _objc_msgSend$_finish:outcome:
+ _objc_msgSend$_getLastDataPushStateForChangeSource:inAccount:recoveryTrackingToken:recoveryTimestamp:
+ _objc_msgSend$_getUpsyncChangeItemsSinceChangeID:shouldBatch:
+ _objc_msgSend$_graphIDMigrationHasConvertedAtStamp
+ _objc_msgSend$_graphIDMigrationStampConversionCompletion:report:state:
+ _objc_msgSend$_initWithGraphMigrationEnabled:maximumAttemptsPerPhase:
+ _objc_msgSend$_initWithPhase:kind:reason:
+ _objc_msgSend$_itemIdForChangeItem:itemExternalID:changeKey:
+ _objc_msgSend$_itemsWithExternalID:
+ _objc_msgSend$_logStoreResetReport:
+ _objc_msgSend$_lowestConsumedChangeItemIDExcludingChangeSourceIDs:outLowestChangeItemID:
+ _objc_msgSend$_makeSyncAllFolderItemsTransaction
+ _objc_msgSend$_newQueue
+ _objc_msgSend$_nonPersonaExchangeSyncDataVaultDirectory
+ _objc_msgSend$_noteCallCompletedLocked
+ _objc_msgSend$_outcomeForRefusedReset:
+ _objc_msgSend$_outcomeForReport:account:dataManager:deadlineExceeded:
+ _objc_msgSend$_patchDetachedChangeItems:
+ _objc_msgSend$_performGraphMigrationCutoverHousekeepingReportingFailureReason:
+ _objc_msgSend$_performStoreResetWithScope:targetRowID:targetInternalID:folderType:accountMismatch:options:report:state:
+ _objc_msgSend$_persistDeclinedThroughChangeID:fromStoredChangeID:forChangeSource:
+ _objc_msgSend$_probeDidRunForEpoch:
+ _objc_msgSend$_processOutstandingChangeItemsOnBothDrainsForProtocol:consumerInstances:
+ _objc_msgSend$_pruneRecoveryObserversMatchingOwner:
+ _objc_msgSend$_pruneStaleChangeItemsBelowWatermark:limit:
+ _objc_msgSend$_pushChangeItems:toConsumer:withTrackingToken:
+ _objc_msgSend$_pushingChangeSourceIDs
+ _objc_msgSend$_recordNoDataToConvertAfterRemovalOfAccount:terminalRemoval:databaseRemoved:
+ _objc_msgSend$_recordNoDataToConvertForUntrackedACAccounts:trackedAccountKeys:
+ _objc_msgSend$_registeredChangeSourceIDsForAccount:
+ _objc_msgSend$_reinstallGraphAfterTerminalPurgeForPhase:
+ _objc_msgSend$_resetEachDataClassIntoReport:
+ _objc_msgSend$_resetLocalStoreIntoReport:
+ _objc_msgSend$_resetOptions
+ _objc_msgSend$_retireDurableWorkWithToken:
+ _objc_msgSend$_runAndWait:
+ _objc_msgSend$_runCutoverHousekeepingPhase
+ _objc_msgSend$_runPreGraphMigrationPhase:
+ _objc_msgSend$_runStoreResetWithScope:targetRowID:targetInternalID:folderType:verifyAccount:callerOptions:
+ _objc_msgSend$_runTerminalPurgeForPhase:
+ _objc_msgSend$_runUpdateItemRequest:schemaVersion:timeZoneContext:error:
+ _objc_msgSend$_scheduleTick
+ _objc_msgSend$_scheduleTransactionReleaseFallback:afterSeconds:
+ _objc_msgSend$_storeResetAbort:report:reason:
+ _objc_msgSend$_storeResetAllCachedAttachmentPaths
+ _objc_msgSend$_storeResetApplyPendingCountsForNonWrite:report:
+ _objc_msgSend$_storeResetAttachmentsForSurvivingChunkKeysWithRowIDs:paths:report:state:
+ _objc_msgSend$_storeResetChangeItemIsPending:state:
+ _objc_msgSend$_storeResetClearAllServerCursorsWithOptions:report:state:
+ _objc_msgSend$_storeResetClearChangeSourceCursors:options:report:state:
+ _objc_msgSend$_storeResetClearFolderSyncStateForFolderIDs:options:report:state:
+ _objc_msgSend$_storeResetClearStaleDrainStatesWithOptions:report:state:
+ _objc_msgSend$_storeResetCountFrom:
+ _objc_msgSend$_storeResetDeleteDistinguishedRowsForExternalID:db:options:report:state:
+ _objc_msgSend$_storeResetDeleteFolderChangeItemsForFolderRowID:db:options:report:state:
+ _objc_msgSend$_storeResetDeleteItemChunkWithRowIDs:externalIDs:internalIDs:skipped:db:options:report:state:
+ _objc_msgSend$_storeResetDistinctAccountCount
+ _objc_msgSend$_storeResetDrainPositionsForOptions:
+ _objc_msgSend$_storeResetEntireStoreWithOptions:report:state:
+ _objc_msgSend$_storeResetExecute:db:options:report:state:write:
+ _objc_msgSend$_storeResetExistingFolderCountForFolderIDs:
+ _objc_msgSend$_storeResetFirstDataConsumerIdentifierInSet:
+ _objc_msgSend$_storeResetFolderRow:options:report:state:
+ _objc_msgSend$_storeResetFolderRowIDForInternalID:
+ _objc_msgSend$_storeResetFolderSubtreeFromRowID:restrictToFolderType:folderType:options:report:state:
+ _objc_msgSend$_storeResetFolderTypeForFolderID:
+ _objc_msgSend$_storeResetFoldersOfType:options:report:state:
+ _objc_msgSend$_storeResetItemHasPendingChangeItemWithRowID:externalID:internalID:state:
+ _objc_msgSend$_storeResetItemRequiresMissingCursorSourcesForRowID:options:
+ _objc_msgSend$_storeResetItemRow:externalID:internalID:db:options:report:state:
+ _objc_msgSend$_storeResetItemRowIDForInternalID:
+ _objc_msgSend$_storeResetItemWithRowID:options:report:state:
+ _objc_msgSend$_storeResetItemsInFolderID:options:report:state:
+ _objc_msgSend$_storeResetLoadChunkKeysWithRowIDs:externalIDs:internalIDs:db:report:state:
+ _objc_msgSend$_storeResetMarkChunkKeysSurviving:db:report:state:
+ _objc_msgSend$_storeResetNoteOrphanedAttachmentRowsIntoReport:
+ _objc_msgSend$_storeResetNoteSkippedItemRow:reason:state:
+ _objc_msgSend$_storeResetOrphanBucketForFolderType:options:report:state:
+ _objc_msgSend$_storeResetOrphanedAttachmentRowsExistWithOptions:
+ _objc_msgSend$_storeResetPerformUnit:options:report:state:
+ _objc_msgSend$_storeResetPreconditionForScope:schemaVersion:accountMismatch:options:staleDrainChangeSourceIDs:
+ _objc_msgSend$_storeResetPromotePendingFiles:options:
+ _objc_msgSend$_storeResetRunScope:targetRowID:folderType:options:report:state:
+ _objc_msgSend$_storeResetSchemaVersion
+ _objc_msgSend$_storeResetShouldStop:options:
+ _objc_msgSend$_storeResetSkipReasonForFolderRowID:externalID:options:report:state:
+ _objc_msgSend$_storeResetSkipReasonForItemRowID:externalID:internalID:options:state:
+ _objc_msgSend$_storeResetSubtreeFolderIDsFrom:restrictToFolderType:folderType:options:report:state:
+ _objc_msgSend$_storeResetTargetExistsForScope:rowID:
+ _objc_msgSend$_storeResetUnlinkCommittedFiles:options:report:
+ _objc_msgSend$_storeResetUnlinkedAttachmentRowCount
+ _objc_msgSend$_storeResetUnpushedFolderCount
+ _objc_msgSend$_storeResetUnpushedItemCount
+ _objc_msgSend$_storeResetUnpushedLocalChangeCountWithOptions:
+ _objc_msgSend$_storeResetUnpushedLocalChangesExistWithOptions:
+ _objc_msgSend$_storeResetZeroChangeSourceWatermarksWithDB:options:report:state:
+ _objc_msgSend$_tick
+ _objc_msgSend$_transientAccountForKey:acAccount:
+ _objc_msgSend$_tripAfterTimeout
+ _objc_msgSend$_updateGraphMigrationRowWithAssignment:context:
+ _objc_msgSend$acAccountHasGraphAPIEndpoint:
+ _objc_msgSend$accountHasGraphAPIEndpoint:
+ _objc_msgSend$addNote:
+ _objc_msgSend$adoptCommittedExternalID:
+ _objc_msgSend$adoptRefreshedACAccount:
+ _objc_msgSend$advanceLastChangeIDForChangeSource:inAccount:fromChangeID:pastDeclinedChangeID:
+ _objc_msgSend$advanceMigrationStateForAccount:to:
+ _objc_msgSend$allocWithZone:
+ _objc_msgSend$appendString:
+ _objc_msgSend$applyToReport:
+ _objc_msgSend$attachmentFilesFailedToUnlink
+ _objc_msgSend$attachmentFilesUnlinked
+ _objc_msgSend$attachmentRowsRemoved
+ _objc_msgSend$attemptConversionForAccount:dataManager:databaseOpenResult:deadline:
+ _objc_msgSend$beginSearchDirectoryForAccountID:queryString:recordTypes:fullContactData:withReply:
+ _objc_msgSend$blankedFolderIDs
+ _objc_msgSend$block
+ _objc_msgSend$calendarFolderDeltaChangeSourceID
+ _objc_msgSend$calendarFolderExternalIDsForGraphCanonicalization
+ _objc_msgSend$canonicalCalendarFolderIDsForStoredIDs:deadline:outMissingIDs:
+ _objc_msgSend$canonicalCalendarFolderIDsForStoredIDs:deadline:outMissingIDs:outFailureKind:
+ _objc_msgSend$canonicalizeCalendarFolderIDsForAccount:dataManager:syncProtocol:deadline:failureReason:
+ _objc_msgSend$changeItemsRemoved
+ _objc_msgSend$changeSourceCursorsCleared
+ _objc_msgSend$changeSourceWatermarksZeroed
+ _objc_msgSend$chunksCommitted
+ _objc_msgSend$cleanupStaleDataExcludingChangeSourceIDs:
+ _objc_msgSend$clearCreateTokenForChangeID:
+ _objc_msgSend$clearNotesFolderMapWithDataManager:
+ _objc_msgSend$clientStoreDiscardAttempts
+ _objc_msgSend$clientStoreDiscarder
+ _objc_msgSend$clientStoreDiscarderForTerminalPurge
+ _objc_msgSend$clientStoreIsReachable
+ _objc_msgSend$clientStoresCompleted
+ _objc_msgSend$clientStoresEnqueued
+ _objc_msgSend$clientStoresFaulted
+ _objc_msgSend$committedFilePaths
+ _objc_msgSend$containerRowExists
+ _objc_msgSend$convertedStoreRequiresCutover:
+ _objc_msgSend$createTokenForChangeID:
+ _objc_msgSend$createTokenForChangeID:mintedNow:
+ _objc_msgSend$currentEpoch
+ _objc_msgSend$currentPolicy
+ _objc_msgSend$cursorChangeSourceIDs
+ _objc_msgSend$cursorOnlyChangeSourceIDs
+ _objc_msgSend$databaseFilesAreAbsentForAccount:
+ _objc_msgSend$decisionForFailure:attemptsSoFar:policy:
+ _objc_msgSend$defaultDeadline
+ _objc_msgSend$defaultOptions
+ _objc_msgSend$defaultOptionsWithPushingChangeSourceIDs:
+ _objc_msgSend$deleteAllWebPushSubscriptionRows
+ _objc_msgSend$deleteWebPushSubscriptionRowForDataClass:folderExternalID:
+ _objc_msgSend$detachedOccurrenceChangeItemsReported
+ _objc_msgSend$deviceZoneComponentsFromEWSDateTime:
+ _objc_msgSend$dictionaryWithCapacity:
+ _objc_msgSend$discard
+ _objc_msgSend$discardClientStoreForAccountReset
+ _objc_msgSend$discardClientStoreForFolderType:
+ _objc_msgSend$distinguishedFolderRowsRemoved
+ _objc_msgSend$drainPositions
+ _objc_msgSend$endDataPushForChangeSource:inAccount:forLastChangeID:withOutcome:batchItemCount:pusherCanBatch:
+ _objc_msgSend$ewsChangeSourceID
+ _objc_msgSend$ewsTaskCompleteDateComponentsFromDate:
+ _objc_msgSend$ewsTaskDayComponentsFromDay:contextZone:
+ _objc_msgSend$ewsTaskReminderDueByComponentsFromComponents:
+ _objc_msgSend$expirationAt
+ _objc_msgSend$externalIDsWithUnpushedChangesOfItemType:pastWatermarkOfChangeSource:
+ _objc_msgSend$failureForConversionOutcome:
+ _objc_msgSend$failureForHousekeepingReason:
+ _objc_msgSend$findFolderForDistinguishedFolderType:
+ _objc_msgSend$findItemWithItemID:
+ _objc_msgSend$foldLegacyNotesFolder:messageRootIDs:intoContainer:
+ _objc_msgSend$folderMapCleared
+ _objc_msgSend$folderTypesWithClientStores
+ _objc_msgSend$foldersRemoved
+ _objc_msgSend$foldersRetainedForSkippedItems
+ _objc_msgSend$foldersSkippedForUnpushedLocalChanges
+ _objc_msgSend$foldersSyncStateCleared
+ _objc_msgSend$foldersSyncStateClearedTakenBack
+ _objc_msgSend$getGraphIDConversionAttemptCount:
+ _objc_msgSend$getUpsyncChangeItemsSinceChangeID:shouldBatch:
+ _objc_msgSend$graphResource
+ _objc_msgSend$graphSyncChangeSourceID
+ _objc_msgSend$hasAnyLocalRowsForGraphIDMigration
+ _objc_msgSend$hasCompletedGraphIDConversion
+ _objc_msgSend$hasLaterDeletionOfChangeItem:
+ _objc_msgSend$hasUpsyncChangeItemsSinceChangeID:
+ _objc_msgSend$idleChangeSourceIDs
+ _objc_msgSend$includesOrphanedAttachmentRows
+ _objc_msgSend$includesUnpushedLocalChanges
+ _objc_msgSend$initWithAccount:dataManager:databaseOpenResult:clientStoreDiscarder:
+ _objc_msgSend$initWithAccount:plugins:instanceFactory:
+ _objc_msgSend$initWithGate:epoch:
+ _objc_msgSend$initWithName:timeout:probeInterval:escalationInterval:
+ _objc_msgSend$initWithRequestID:searchQuery:recordTypes:includeFullData:responseManager:
+ _objc_msgSend$initWithTable:rowID:kind:reason:
+ _objc_msgSend$instancesByFolderType
+ _objc_msgSend$isFileURL
+ _objc_msgSend$isSubsetOfSet:
+ _objc_msgSend$itemsRemoved
+ _objc_msgSend$itemsSkippedForUnpushedLocalChanges
+ _objc_msgSend$kind
+ _objc_msgSend$lastChangeItemID
+ _objc_msgSend$lastStep
+ _objc_msgSend$legacyNotesContainerForGraphCutoverWithContainer:
+ _objc_msgSend$legacyNotesFolderID
+ _objc_msgSend$logFailure:decision:attemptsSoFar:policy:accountKey:
+ _objc_msgSend$maximumAttemptsPerPhase
+ _objc_msgSend$messageRootIDs
+ _objc_msgSend$migrateExternalIDsToGraphWithOptions:
+ _objc_msgSend$migrationStateForACAccount:accountKey:
+ _objc_msgSend$mutableNotes
+ _objc_msgSend$notes
+ _objc_msgSend$notesFolderDeltaChangeSourceID
+ _objc_msgSend$notificationURLHash
+ _objc_msgSend$orderedFolderTypes
+ _objc_msgSend$orphanedAttachmentRowsFound
+ _objc_msgSend$owner
+ _objc_msgSend$pendingCounts
+ _objc_msgSend$pendingFilePaths
+ _objc_msgSend$phase
+ _objc_msgSend$policyWithGraphMigrationEnabled:maximumAttemptsPerPhase:
+ _objc_msgSend$prepareForAccountRemoval
+ _objc_msgSend$prepareNotesFolderStateForGraphCutover
+ _objc_msgSend$prepareSyncProtocolForAccountRemovalWithGroup:
+ _objc_msgSend$processInfo
+ _objc_msgSend$purgedThisStartup
+ _objc_msgSend$pushDrainStoppedWithChangeItemsQueued
+ _objc_msgSend$pushingChangeSourceIDs
+ _objc_msgSend$receivedAtMonotonicNanoseconds
+ _objc_msgSend$recordCreatedExternalID:externalChangeKey:onLaterDeletionsOfChangeItem:
+ _objc_msgSend$recordGraphIDConversionAttempt
+ _objc_msgSend$recordGraphIDConversionFailure
+ _objc_msgSend$recordPushDrainAborted
+ _objc_msgSend$recordTerminalPurgeCompleted
+ _objc_msgSend$recordTypes
+ _objc_msgSend$releaseGraphIDConversionAttempt
+ _objc_msgSend$relocateToParentCalendar
+ _objc_msgSend$resetEntireStoreForAccount:options:
+ _objc_msgSend$resetFoldersOfType:forAccount:options:
+ _objc_msgSend$reverseObjectEnumerator
+ _objc_msgSend$rewriteFolderExternalIDs:
+ _objc_msgSend$run
+ _objc_msgSend$scope
+ _objc_msgSend$sendUpdateItemRequest:schemaVersion:timeZoneContext:refreshingChangeKeyOnConflict:itemIdWithFreshKey:error:
+ _objc_msgSend$set
+ _objc_msgSend$setAbortsOnTranslationFailure:
+ _objc_msgSend$setArray:
+ _objc_msgSend$setAttachmentFilesFailedToUnlink:
+ _objc_msgSend$setAttachmentFilesUnlinked:
+ _objc_msgSend$setAttachmentRowsRemoved:
+ _objc_msgSend$setBlock:
+ _objc_msgSend$setChangeItemsRemoved:
+ _objc_msgSend$setChangeSourceCursorsCleared:
+ _objc_msgSend$setChangeSourceWatermarksZeroed:
+ _objc_msgSend$setChunksCommitted:
+ _objc_msgSend$setClientStoreDiscardAttempts:
+ _objc_msgSend$setClientStoresCompleted:
+ _objc_msgSend$setClientStoresEnqueued:
+ _objc_msgSend$setClientStoresFaulted:
+ _objc_msgSend$setContainerRowExists:
+ _objc_msgSend$setCursorChangeSourceIDs:
+ _objc_msgSend$setDataClass:
+ _objc_msgSend$setDatabaseOpenResult:
+ _objc_msgSend$setDetachedOccurrenceChangeItemsReported:
+ _objc_msgSend$setDistinguishedFolderRowsRemoved:
+ _objc_msgSend$setDrainPositions:
+ _objc_msgSend$setExpirationAt:
+ _objc_msgSend$setFolderMapCleared:
+ _objc_msgSend$setFoldersRemoved:
+ _objc_msgSend$setFoldersRetainedForSkippedItems:
+ _objc_msgSend$setFoldersSkippedForUnpushedLocalChanges:
+ _objc_msgSend$setFoldersSyncStateCleared:
+ _objc_msgSend$setFoldersSyncStateClearedTakenBack:
+ _objc_msgSend$setGraphResource:
+ _objc_msgSend$setIdleChangeSourceIDs:
+ _objc_msgSend$setIncludesOrphanedAttachmentRows:
+ _objc_msgSend$setIncludesUnpushedLocalChanges:
+ _objc_msgSend$setIsActive:
+ _objc_msgSend$setItemsRemoved:
+ _objc_msgSend$setItemsSkippedForUnpushedLocalChanges:
+ _objc_msgSend$setLastChangeItemID:
+ _objc_msgSend$setLastStep:
+ _objc_msgSend$setLegacyNotesFolderID:
+ _objc_msgSend$setMessageRootIDs:
+ _objc_msgSend$setNotificationURLHash:
+ _objc_msgSend$setOrphanedAttachmentRowsFound:
+ _objc_msgSend$setOutcome:
+ _objc_msgSend$setOwner:
+ _objc_msgSend$setPurgedThisStartup:
+ _objc_msgSend$setPushingChangeSourceIDs:
+ _objc_msgSend$setRelocateToParentCalendar:
+ _objc_msgSend$setScope:
+ _objc_msgSend$setShouldCancel:
+ _objc_msgSend$setStaleChangeItemPruneBatchSize:
+ _objc_msgSend$setStaleDrainStatesCleared:
+ _objc_msgSend$setStampAttempts:
+ _objc_msgSend$setStamped:
+ _objc_msgSend$setStampsConversionCompletion:
+ _objc_msgSend$setStartupDatabaseOpenResult:
+ _objc_msgSend$setStoreResetAttempts:
+ _objc_msgSend$setStoreResetPrecondition:
+ _objc_msgSend$setSubscriberKeyHash:
+ _objc_msgSend$setSubscriptionID:
+ _objc_msgSend$setTargetRowID:
+ _objc_msgSend$setTerminalPurgeAttemptedThisStartup:
+ _objc_msgSend$setTimeZoneContext:
+ _objc_msgSend$setTopic:
+ _objc_msgSend$setTransactionDB:
+ _objc_msgSend$setTransactionMode:
+ _objc_msgSend$setUnitsRun:
+ _objc_msgSend$setUnpushedLocalChangesDiscarded:
+ _objc_msgSend$setUsedPerDataClassReset:
+ _objc_msgSend$setWithCapacity:
+ _objc_msgSend$setWithSet:
+ _objc_msgSend$shouldAttemptConversionForAccount:dataManager:
+ _objc_msgSend$shouldPushChangeItem:
+ _objc_msgSend$staleChangeItemPruneBatchSize
+ _objc_msgSend$staleDrainChangeSourceIDs
+ _objc_msgSend$staleDrainStatesCleared
+ _objc_msgSend$stampAttempts
+ _objc_msgSend$stamped
+ _objc_msgSend$stampsConversionCompletion
+ _objc_msgSend$startupDatabaseOpenResult
+ _objc_msgSend$storeResetAttempts
+ _objc_msgSend$storeResetPrecondition
+ _objc_msgSend$string
+ _objc_msgSend$subarrayWithRange:
+ _objc_msgSend$subscriberKeyHash
+ _objc_msgSend$subscriptionID
+ _objc_msgSend$systemUptime
+ _objc_msgSend$targetRowID
+ _objc_msgSend$taskListDeltaChangeSourceID
+ _objc_msgSend$taskTimeZoneContextForZone:
+ _objc_msgSend$terminalPurgeAttemptedThisStartup
+ _objc_msgSend$totalRowsRemoved
+ _objc_msgSend$transactionDB
+ _objc_msgSend$transactionMode
+ _objc_msgSend$tryPerformAsynchronously:
+ _objc_msgSend$unionSet:
+ _objc_msgSend$unitsRun
+ _objc_msgSend$unpushedLocalChangesDiscarded
+ _objc_msgSend$upsertItemForChangeItem:usingDBConnection:
+ _objc_msgSend$upsertWebPushSubscriptionRow:
+ _objc_msgSend$usedPerDataClassReset
+ _objc_msgSend$visitedFolderIDs
+ _objc_msgSend$webPushSubscriptionRows
+ _objc_msgSend$wipeWasComplete
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _sGraphMigrationEnabledOverride
+ _sGraphSyncEnabledOverride
+ _swift_deallocBox
+ _swift_dynamicCastClass
+ _swift_getAtKeyPath
+ _swift_getExistentialTypeMetadata
+ _swift_getFunctionTypeMetadata0
+ _swift_getKeyPath
+ _swift_getTupleTypeMetadata3
+ _swift_isUniquelyReferenced_nonNull
+ _swift_unknownObjectRetain_n
+ _swift_weakAssign
+ _symbolic $s12ExchangeSync18EXSWebPushKeyStoreP
+ _symbolic $s12ExchangeSync22EXSGSHeartbeatTickableP
+ _symbolic $s12ExchangeSync27EXSGSXPCActivityRegisteringP
+ _symbolic $s12ExchangeSync29EXSGSWebPushRecordPersistenceP
+ _symbolic 7Request______26graphSyncResponseDataModel_____QZSg______pIegrzo_ 12ExchangeSync30EXSGSCreateCollectionOperationP 05GraphB00fB11RequestableP s5ErrorP
+ _symbolic 7Request______26graphSyncResponseDataModel_____QZSg______pIegrzo_Sg 12ExchangeSync30EXSGSCreateCollectionOperationP 05GraphB00fB11RequestableP s5ErrorP
+ _symbolic G0R0_
+ _symbolic G0R2_
+ _symbolic Ieg_
+ _symbolic IeyB_
+ _symbolic SDySSSDySSypGG
+ _symbolic SDySSSaySo27ESECalendarAvailabilitySpanCGG
+ _symbolic SDySSSiG
+ _symbolic SDySS_____G 12ExchangeSync22EXSGSAttachmentManagerC15PendingDownload33_072DC6A9C1AB6733BC7ED7AD2387F139LLV
+ _symbolic SDySiSaySSGG
+ _symbolic SDy_____SiG 12ExchangeSync12EXSGSHoldKeyO
+ _symbolic SDy__________G 12ExchangeSync12EXSGSHoldKeyO AA25EXSGSThrottleHoldingQueueC5Entry33_9504B189D9B1AD4B4D0CA7B11235DD04LLV
+ _symbolic SDy__________G 12ExchangeSync21EXSGSWebPushDataClassO AA0cD11EligibilityO
+ _symbolic SDy__________G So13EXSFolderTypeV 12ExchangeSync23EXSGSThrottleControllerC10OwedRecord33_463083CFCC0FD2DAF1C8E64D936A313BLLV
+ _symbolic SDy__________G So13EXSFolderTypeV 12ExchangeSync26EXSGSHeartbeatRefreshScopeO
+ _symbolic SS10accountKey______t So13EXSFolderTypeV
+ _symbolic SS11requestedID______8resourcet 9GraphSync0aB22CalendarFolderResourceV
+ _symbolic SS11requestedID_x8resourcet
+ _symbolic SS14changeSourceID_t
+ _symbolic SS8serverID_SS012itemExternalB0SSSg08calendardB0tSg
+ _symbolic SS_SDySSypGt
+ _symbolic SS______t 10Foundation4DataV
+ _symbolic SS______t 12ExchangeSync22EXSGSAttachmentManagerC15PendingDownload33_072DC6A9C1AB6733BC7ED7AD2387F139LLV
+ _symbolic SaySDySSypGG
+ _symbolic SaySS11requestedID_x8resourcetG
+ _symbolic SaySo18ESEGrantedDelegateCG
+ _symbolic Say_____G 10Foundation4DateV
+ _symbolic Say_____G 12ExchangeSync11EXSGSConfigO9HeartbeatO14CadenceProfileO
+ _symbolic Say_____G 12ExchangeSync23EXSGSHeartbeatSchedulerC10Registrant33_2C7CFFE49C44D040B0731D891EFA8DCDLLV
+ _symbolic Say_____G 12ExchangeSync24EXSGSHeartbeatPollActionO
+ _symbolic Say_____G 9GraphSync0aB18PeopleQuerySourcesV
+ _symbolic Say_____G So13EXSFolderTypeV
+ _symbolic Say___________tG So13EXSFolderTypeV 12ExchangeSync22EXSGSHeartbeatDecisionO
+ _symbolic Say______pG9tickables_Si6pruned_____8criteriaSb7changedtSg 12ExchangeSync22EXSGSHeartbeatTickableP AA0C16ActivityCriteriaV
+ _symbolic SayyycG
+ _symbolic Sb6failed_t
+ _symbolic SbSg
+ _symbolic SbSgz_Xx
+ _symbolic SbycSg
+ _symbolic Sd5since_t
+ _symbolic SdSg
+ _symbolic SdSg10retryAfter_t
+ _symbolic Sdyc
+ _symbolic Shy_____G 12ExchangeSync11EXSGSConfigO9HeartbeatO14CadenceProfileO
+ _symbolic Shy_____G So13EXSFolderTypeV
+ _symbolic Si11dataClasses_Sd11downSecondst
+ _symbolic Si11dataClasses_t
+ _symbolic Si2id_t
+ _symbolic Si3key______5valuet 12ExchangeSync34EXSGSNotePendingFolderCascadeStoreO5EntryV
+ _symbolic Si8revision_Si11folderCountt
+ _symbolic Si_SSt
+ _symbolic Si_So9EXSFolderCt
+ _symbolic Si______t 12ExchangeSync34EXSGSNotePendingFolderCascadeStoreO5EntryV
+ _symbolic So18ESEGrantedDelegateC
+ _symbolic So25EXSGrantedDelegateRequestC
+ _symbolic So32EXSAvailabilityRequestComponentsC
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 12ExchangeSync11EXSGSConfigO9HeartbeatO14CadenceProfileO
+ _symbolic _____ 12ExchangeSync12EXSGSHoldKeyO
+ _symbolic _____ 12ExchangeSync14EXSGSHoldClassO
+ _symbolic _____ 12ExchangeSync16EXSGSCreateTokenO
+ _symbolic _____ 12ExchangeSync17EXSGSThrottleGateC10TransitionO
+ _symbolic _____ 12ExchangeSync17PublishedDeadline33_463083CFCC0FD2DAF1C8E64D936A313BLLC
+ _symbolic _____ 12ExchangeSync19EXSGSNoteFolderEdgeO
+ _symbolic _____ 12ExchangeSync19EXSGSWallClockTimerC
+ _symbolic _____ 12ExchangeSync19EXSWebPushKeyRecordV
+ _symbolic _____ 12ExchangeSync19EXSWebPushKeyRecordV10CodingKeysO
+ _symbolic _____ 12ExchangeSync19EXSWebPushTransportC7APSLink33_F599398DB63F31C565EB854B8922C17DLLO
+ _symbolic _____ 12ExchangeSync20EXSGSWebPushLivenessV
+ _symbolic _____ 12ExchangeSync20EXSGSWebPushLivenessV14ApsOutageClearO
+ _symbolic _____ 12ExchangeSync21EXSGSFailureLogFieldsV
+ _symbolic _____ 12ExchangeSync22EXSGSHeartbeatPollPlanV
+ _symbolic _____ 12ExchangeSync22EXSGSHeartbeatTickGateC
+ _symbolic _____ 12ExchangeSync23EXSGSBoundedTransactionC
+ _symbolic _____ 12ExchangeSync23EXSGSHeartbeatSchedulerC
+ _symbolic _____ 12ExchangeSync23EXSGSHeartbeatSchedulerC10Registrant33_2C7CFFE49C44D040B0731D891EFA8DCDLLV
+ _symbolic _____ 12ExchangeSync23EXSGSNoteFolderMapStoreO11SeedOutcomeO
+ _symbolic _____ 12ExchangeSync23EXSGSThrottleControllerC
+ _symbolic _____ 12ExchangeSync23EXSGSThrottleControllerC10OwedRecord33_463083CFCC0FD2DAF1C8E64D936A313BLLV
+ _symbolic _____ 12ExchangeSync23EXSGSThrottleControllerC7WeakBoxC
+ _symbolic _____ 12ExchangeSync23EXSGSThrottleControllerC9DeltaOwedV
+ _symbolic _____ 12ExchangeSync23EXSGSWebPushCoordinatorC14TeardownReasonO
+ _symbolic _____ 12ExchangeSync23EXSWebPushKeyStoreErrorO
+ _symbolic _____ 12ExchangeSync23EXSWebPushKeychainStoreV
+ _symbolic _____ 12ExchangeSync24EXSGSHeartbeatPollActionO
+ _symbolic _____ 12ExchangeSync24EXSGSHeartbeatRefreshRunV
+ _symbolic _____ 12ExchangeSync24EXSGSHeartbeatTickSourceO
+ _symbolic _____ 12ExchangeSync24EXSGSPushDownsyncRequestV
+ _symbolic _____ 12ExchangeSync25EXSGSSearchRoomsOperationV
+ _symbolic _____ 12ExchangeSync25EXSGSThrottleHoldingQueueC
+ _symbolic _____ 12ExchangeSync25EXSGSThrottleHoldingQueueC12ReleaseToken33_9504B189D9B1AD4B4D0CA7B11235DD04LLC
+ _symbolic _____ 12ExchangeSync25EXSGSThrottleHoldingQueueC5Entry33_9504B189D9B1AD4B4D0CA7B11235DD04LLV
+ _symbolic _____ 12ExchangeSync26EXSGSCollectionCreateTokenO
+ _symbolic _____ 12ExchangeSync26EXSGSHeartbeatRefreshScopeO
+ _symbolic _____ 12ExchangeSync27EXSGSHeartbeatTickDecisionsV
+ _symbolic _____ 12ExchangeSync28EXSGSTierPassStateTransitionO
+ _symbolic _____ 12ExchangeSync28EXSGSTierPassStateTransitionO5ClearV
+ _symbolic _____ 12ExchangeSync29EXSGSLiveXPCActivityRegistrarV
+ _symbolic _____ 12ExchangeSync30EXSGSHeartbeatActivityCriteriaV
+ _symbolic _____ 12ExchangeSync31EXSGSMoveCalendarEventOperationV10SkipReasonO
+ _symbolic _____ 12ExchangeSync34EXSGSNotePendingFolderCascadeStoreO
+ _symbolic _____ 12ExchangeSync34EXSGSNotePendingFolderCascadeStoreO5EntryV
+ _symbolic _____ 12ExchangeSync35EXSGSHeartbeatSchedulerRegistration33_F6D46D85F031ADDD4AE009C1F681546FLLC
+ _symbolic _____ 12ExchangeSync39EXSGSPersistentWebPushSubscriptionStoreC
+ _symbolic _____ 12ExchangeSync44EXSGSDrainNotePendingFolderCascadesOperationV
+ _symbolic _____ 12ExchangeSync9OnceReply33_463083CFCC0FD2DAF1C8E64D936A313BLLC
+ _symbolic _____ So17EXSGSSyncProtocolC12ExchangeSyncE23PendingCreateResolutionO
+ _symbolic _____ So17EXSGSSyncProtocolC12ExchangeSyncE26WebPushCoverageEntryActionO
+ _symbolic _____ So17EXSGSSyncProtocolC12ExchangeSyncE26sendGrantedDelegateRequest7requestSbSo010EXSGrantedgH0C_tF4PlanL_O
+ _symbolic _____ So17EXSGSSyncProtocolC12ExchangeSyncE31WebPushRemovalCoordinatorSourceO
+ _symbolic _____ s5Int64V
+ _symbolic _____10retryAfter_t 10Foundation4DateV
+ _symbolic _____6status_t s5Int32V
+ _symbolic _____8criteria______11claimedGatet 12ExchangeSync30EXSGSHeartbeatActivityCriteriaV AA0C8TickGateC
+ _symbolic _____Igy_Iegg_ 12ExchangeSync30EXSGSHeartbeatActivityCriteriaV
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic _____Sg 12ExchangeSync19EXSGSOperationErrorO
+ _symbolic _____Sg 12ExchangeSync19EXSWebPushKeyRecordV
+ _symbolic _____Sg 12ExchangeSync19EXSWebPushTransportC7APSLink33_F599398DB63F31C565EB854B8922C17DLLO
+ _symbolic _____Sg 12ExchangeSync22EXSGSAttachmentManagerC15PendingDownload33_072DC6A9C1AB6733BC7ED7AD2387F139LLV
+ _symbolic _____Sg 12ExchangeSync23EXSGSHeartbeatSchedulerC10Registrant33_2C7CFFE49C44D040B0731D891EFA8DCDLLV
+ _symbolic _____Sg 12ExchangeSync25EXSGSThrottleHoldingQueueC5Entry33_9504B189D9B1AD4B4D0CA7B11235DD04LLV
+ _symbolic _____Sg 12ExchangeSync30EXSGSHeartbeatActivityCriteriaV
+ _symbolic _____Sg 12ExchangeSync34EXSGSNotePendingFolderCascadeStoreO5EntryV
+ _symbolic _____Sg 9GraphSync0aB18PersonTypeResourceV
+ _symbolic _____Sg 9GraphSync0aB20ResolveNamesResponseV
+ _symbolic _____Sg 9GraphSync0aB22StickyNoteListResourceV
+ _symbolic _____Sg 9GraphSync0aB24EventsCollectionResponseV
+ _symbolic _____SgXw 12ExchangeSync17EXSGSThrottleGateC
+ _symbolic _____SgXw 12ExchangeSync23EXSGSBoundedTransactionC
+ _symbolic _____SgXw 12ExchangeSync23EXSGSHeartbeatSchedulerC
+ _symbolic _____SgXw 12ExchangeSync23EXSGSThrottleControllerC
+ _symbolic _____SgXw 12ExchangeSync25EXSGSThrottleHoldingQueueC
+ _symbolic _____SgXwz_Xx 12ExchangeSync17EXSGSThrottleGateC
+ _symbolic _____SgXwz_Xx 12ExchangeSync23EXSGSHeartbeatSchedulerC
+ _symbolic _____SgXwz_Xx 12ExchangeSync23EXSGSThrottleControllerC
+ _symbolic _____SgXwz_Xx 12ExchangeSync25EXSGSThrottleHoldingQueueC
+ _symbolic _____Sg_ABt 12ExchangeSync34EXSGSNotePendingFolderCascadeStoreO5EntryV
+ _symbolic _____Sg_ABt 9GraphSync0aB18ImportanceResourceO
+ _symbolic _____Sgyc 10Foundation4DateV
+ _symbolic _____Shy_____Gc 12ExchangeSync30EXSGSHeartbeatActivityCriteriaV AA11EXSGSConfigO9HeartbeatO14CadenceProfileO
+ _symbolic _____XDXMT 12ExchangeSync23EXSGSHeartbeatSchedulerC
+ _symbolic _____XDXMT 12ExchangeSync25EXSGSThrottleHoldingQueueC
+ _symbolic ___________t 12ExchangeSync12EXSGSHoldKeyO AA25EXSGSThrottleHoldingQueueC5Entry33_9504B189D9B1AD4B4D0CA7B11235DD04LLV
+ _symbolic ___________t So13EXSFolderTypeV 12ExchangeSync24EXSGSHeartbeatSkipReasonO
+ _symbolic ___________t So13EXSFolderTypeV 12ExchangeSync26EXSGSHeartbeatRefreshScopeO
+ _symbolic __________c 12ExchangeSync24EXSGSPushDownsyncOutcomeO AA0cD7RequestV
+ _symbolic ______p 12ExchangeSync20OSTransactionVendingP
+ _symbolic ______p 12ExchangeSync22EXSGSHeartbeatTickableP
+ _symbolic ______p 12ExchangeSync27EXSGSXPCActivityRegisteringP
+ _symbolic ______p 12ExchangeSync29EXSGSWebPushRecordPersistenceP
+ _symbolic ______pIegg_ s5ErrorP
+ _symbolic ______pSg 12ExchangeSync18EXSWebPushKeyStoreP
+ _symbolic ______pSgXw 12ExchangeSync22EXSGSHeartbeatTickableP
+ _symbolic ______pytIegnr_ s5ErrorP
+ _symbolic _____ySS3key______5valuetG s23_ContiguousArrayStorageC 12ExchangeSync30EXSGSWebPushSubscriptionRecordV
+ _symbolic _____ySSSDySSypGG s18_DictionaryStorageC
+ _symbolic _____ySSSaySo32ESECalendarDirectorySearchResultCGG s18_DictionaryStorageC
+ _symbolic _____ySS_SDySSypGtG s23_ContiguousArrayStorageC
+ _symbolic _____ySS_____G s18_DictionaryStorageC 10Foundation4DataV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 12ExchangeSync22EXSGSAttachmentManagerC15PendingDownload33_072DC6A9C1AB6733BC7ED7AD2387F139LLV
+ _symbolic _____ySS______tG s23_ContiguousArrayStorageC 10Foundation4DataV
+ _symbolic _____ySS______tG s23_ContiguousArrayStorageC 12ExchangeSync30EXSGSWebPushSubscriptionRecordV
+ _symbolic _____ySiSSG s18_DictionaryStorageC
+ _symbolic _____ySiSaySSGG s18_DictionaryStorageC
+ _symbolic _____ySiSo9EXSFolderCG s18_DictionaryStorageC
+ _symbolic _____ySi_SStG s23_ContiguousArrayStorageC
+ _symbolic _____ySi_So9EXSFolderCtG s23_ContiguousArrayStorageC
+ _symbolic _____ySi_____G s18_DictionaryStorageC 12ExchangeSync34EXSGSNotePendingFolderCascadeStoreO5EntryV
+ _symbolic _____ySi______tG s23_ContiguousArrayStorageC 12ExchangeSync34EXSGSNotePendingFolderCascadeStoreO5EntryV
+ _symbolic _____y_____G 8Dispatch0A11SpecificKeyC 12ExchangeSync23EXSGSThrottleControllerC7WeakBoxC
+ _symbolic _____y_____G s11_SetStorageC 12ExchangeSync11EXSGSConfigO9HeartbeatO14CadenceProfileO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12ExchangeSync19EXSWebPushKeyRecordV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12ExchangeSync19EXSWebPushKeyRecordV10CodingKeysO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12ExchangeSync11EXSGSConfigO9HeartbeatO14CadenceProfileO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12ExchangeSync14EXSWebPushKeysV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12ExchangeSync23EXSGSHeartbeatSchedulerC10Registrant33_2C7CFFE49C44D040B0731D891EFA8DCDLLV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12ExchangeSync24EXSGSHeartbeatPollActionO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12ExchangeSync25EXSGSThrottleHoldingQueueC5Entry33_9504B189D9B1AD4B4D0CA7B11235DD04LLV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 9GraphSync0dE18PeopleQuerySourcesV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5Int64V
+ _symbolic _____y_____SgG s23_ContiguousArrayStorageC 10Foundation4DateV
+ _symbolic _____y_____SiG s18_DictionaryStorageC 12ExchangeSync12EXSGSHoldKeyO
+ _symbolic _____y__________G s18_DictionaryStorageC 12ExchangeSync12EXSGSHoldKeyO AC25EXSGSThrottleHoldingQueueC5Entry33_9504B189D9B1AD4B4D0CA7B11235DD04LLV
+ _symbolic _____y__________G s18_DictionaryStorageC 12ExchangeSync21EXSGSWebPushDataClassO AC0eF11EligibilityO
+ _symbolic _____y__________G s18_DictionaryStorageC So13EXSFolderTypeV 12ExchangeSync23EXSGSThrottleControllerC10OwedRecord33_463083CFCC0FD2DAF1C8E64D936A313BLLV
+ _symbolic _____y__________G s18_DictionaryStorageC So13EXSFolderTypeV 12ExchangeSync26EXSGSHeartbeatRefreshScopeO
+ _symbolic _____y___________tG s23_ContiguousArrayStorageC So13EXSFolderTypeV 12ExchangeSync22EXSGSHeartbeatDecisionO
+ _symbolic _____y______pG s23_ContiguousArrayStorageC 12ExchangeSync22EXSGSHeartbeatTickableP
+ _symbolic _____yxG 12ExchangeSync9OnceReply33_463083CFCC0FD2DAF1C8E64D936A313BLLC
+ _symbolic _____yyycG s23_ContiguousArrayStorageC
+ _symbolic x______pIegrzo_ s5ErrorP
+ _symbolic ySaySSGKc
+ _symbolic y______SitcSg 12ExchangeSync12EXSGSHoldKeyO
+ _symbolic y_____cSg 12ExchangeSync17EXSGSThrottleGateC10TransitionO
+ _symbolic y_____yx______pGcSg s6ResultOsRi_zRi0_zrlE s5ErrorP
+ _symbolic ypSgyKc
+ _symbolic yycSd_yyctc
+ _symbolic yycyc
+ _type_layout_string 12ExchangeSync12EXSGSHoldKeyO
+ _type_layout_string 12ExchangeSync19EXSGSNoteFolderEdgeO
+ _type_layout_string 12ExchangeSync19EXSWebPushKeyRecordV
+ _type_layout_string 12ExchangeSync20EXSGSWebPushLivenessV
+ _type_layout_string 12ExchangeSync21EXSGSFailureLogFieldsV
+ _type_layout_string 12ExchangeSync22EXSGSHeartbeatPollPlanV
+ _type_layout_string 12ExchangeSync23EXSGSThrottleControllerC10OwedRecord33_463083CFCC0FD2DAF1C8E64D936A313BLLV
+ _type_layout_string 12ExchangeSync23EXSGSThrottleControllerC9DeltaOwedV
+ _type_layout_string 12ExchangeSync23EXSWebPushKeychainStoreV
+ _type_layout_string 12ExchangeSync24EXSGSHeartbeatRefreshRunV
+ _type_layout_string 12ExchangeSync24EXSGSHeartbeatTickSourceO
+ _type_layout_string 12ExchangeSync24EXSGSPushDownsyncRequestV
+ _type_layout_string 12ExchangeSync25EXSGSSearchRoomsOperationV
+ _type_layout_string 12ExchangeSync27EXSGSHeartbeatTickDecisionsV
+ _type_layout_string 12ExchangeSync28EXSGSTierPassStateTransitionO5ClearV
+ _type_layout_string 12ExchangeSync30EXSGSHeartbeatActivityCriteriaV
+ _xpc_activity_set_criteria
- -[EXSDataConsumerInstance dataConsumerHasAction:action:executeAfter:]
- -[EXSDataConsumerInstance dispatchAfter:onWorkQueue:]
- -[EXSDataManager _cleanupStaleData]
- -[EXSDataManager cleanupStaleData]
- -[EXSDataManager(ChangeItems) hasChangeItemsSinceChangeID:skippingChangeSourceID:]
- -[EXSEWSCreateTaskOperation _createTaskItemTypeForChangeItem:]
- -[EXSEWSUpdateItemOperation _buildItemSettersForTaskChangeItem:]
- -[EXSSearchDirectoryRequest initWithRequestID:searchQuery:includeFullData:responseManager:]
- -[EXSSyncEngineInstance _performGraphMigrationCutoverHousekeeping]
- GCC_except_table1
- GCC_except_table145
- GCC_except_table2
- GCC_except_table31
- GCC_except_table32
- GCC_except_table40
- GCC_except_table56
- GCC_except_table58
- GCC_except_table60
- GCC_except_table62
- GCC_except_table64
- GCC_except_table68
- GCC_except_table80
- __OBJC_$_INSTANCE_METHODS_EXSDataManager(Folders|Folders_Private|Items|Items_Private|Migration|GraphIDMigration|Attachments|ChangeItems)
- __OBJC_$_INSTANCE_METHODS_EXSGSSyncProtocol(ExchangeSync|ExchangeSync|ExchangeSync1|ExchangeSync)
- __OBJC_CLASS_PROTOCOLS_$_EXSGSSyncProtocol(ExchangeSync|ExchangeSync|ExchangeSync1|ExchangeSync)
- ___34-[EXSDataManager cleanupStaleData]_block_invoke
- ___53-[EXSDataConsumerInstance dispatchAfter:onWorkQueue:]_block_invoke
- ___59-[EXSDataManager _setGraphMigrationColumn:toValue:context:]_block_invoke
- ___82-[EXSDataManager(ChangeItems) hasChangeItemsSinceChangeID:skippingChangeSourceID:]_block_invoke
- ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0l
- ___swift_memcpy128_8
- _associated conformance 12ExchangeSync27EXSGSGetStickyNoteOperationVAA0c4ItemF0AA7RequestAaDP_05GraphB00iB11Requestable
- _associated conformance 12ExchangeSync27EXSGSGetStickyNoteOperationVAA0c4ItemF0AA8ResourceAaDP_05GraphB00iB10Responsive
- _associated conformance 12ExchangeSync27EXSGSGetStickyNoteOperationVAA0c4ItemF0AA8ResponseAaDP_05GraphB00iB10Responsive
- _associated conformance 12ExchangeSync33EXSGSListTaskCollectionsOperationVAA0ceF0AA7RequestAaDP_05GraphB00hB11Requestable
- _associated conformance 12ExchangeSync33EXSGSListTaskCollectionsOperationVAA0ceF0AA8ResourceAaDP_05GraphB00hB10Responsive
- _associated conformance 12ExchangeSync33EXSGSListTaskCollectionsOperationVAA0ceF0AA8ResponseAaDP_05GraphB00hB10Responsive
- _get_enum_tag_for_layout_string 12ExchangeSync19EXSGSOperationErrorO
- _objc_msgSend$_buildItemSettersForTaskChangeItem:
- _objc_msgSend$_cleanupStaleData
- _objc_msgSend$_createTaskItemTypeForChangeItem:
- _objc_msgSend$_performGraphMigrationCutoverHousekeeping
- _objc_msgSend$hasChangeItemsSinceChangeID:skippingChangeSourceID:
- _objc_msgSend$initWithRequestID:searchQuery:includeFullData:responseManager:
- _symbolic _____ 12ExchangeSync15EXSGSPollActionO
- _symbolic _____ 12ExchangeSync18EXSGSDeltaRoundLogV13FailureFieldsV
- _symbolic _____ 12ExchangeSync27EXSGSGetStickyNoteOperationV
- _symbolic _____ 12ExchangeSync33EXSGSListTaskCollectionsOperationV
- _symbolic _____ 9GraphSync0aB20GetStickyNoteRequestV
- _symbolic _____ 9GraphSync0aB21TodoTaskListsResponseV
- _symbolic _____Sg 9GraphSync0aB21TodoTaskListsResponseV
- _symbolic _____XMT 12ExchangeSync19EXSWebPushTransportC
- _symbolic ___________SSShySSGtc 12ExchangeSync24EXSGSPushDownsyncOutcomeO AA18EXSGSDownsyncScopeV
- _symbolic _____ySaySSGG s23_ContiguousArrayStorageC
- _type_layout_string 12ExchangeSync18EXSGSDeltaRoundLogV13FailureFieldsV
- _type_layout_string 12ExchangeSync19EXSGSOperationErrorO
- _type_layout_string 12ExchangeSync27EXSGSGetStickyNoteOperationV
- _type_layout_string 12ExchangeSync33EXSGSListTaskCollectionsOperationV
CStrings:
+ "#ExchangeSync No Windows time zone for %{private}@; the task write sends no TimeZoneContext."
+ "#ExchangeSync UpdateItem conflict for %{public}@; change key fetch failed, not retrying."
+ "#ExchangeSync UpdateItem conflict for %{public}@; no ItemId for the fetched change key, not retrying."
+ "#ExchangeSync UpdateItem conflict for %{public}@; retrying once with the fetched change key."
+ "#folderHierarchy"
+ "$batch %{public}s throttled (HTTP 429, or 503 with Retry-After) on %ld sub-request(s); over inline budget or retries exhausted"
+ "$batch %{public}s throttled (HTTP 429, or 503 with Retry-After) on %ld sub-request(s); waiting %{public}.*fs then retrying just those"
+ "$batch %{public}s throttled on %ld sub-request(s); not retrying, the throttle gate just closed"
+ "%@=%lld"
+ "%{public}s account=%{public}s %{public}s delta round paused at a page boundary: throttle gate closed; resumes from its checkpoint (pagesPersisted=%ld)"
+ "%{public}s adopted the folder an earlier attempt created for change item %ld"
+ "%{public}s adopted the item an earlier attempt created for change item %ld"
+ "%{public}s adopted the note an earlier attempt created for change item %ld"
+ "%{public}s could not look for an earlier attempt's folder, sending anyway: %{public}s requestID=%{public}s"
+ "%{public}s could not look for an earlier attempt's note, sending anyway: httpStatus=%{public}s requestID=%{public}s"
+ "%{public}s could not look up the item an earlier attempt created for change item %ld: requestID=%{public}s %{private}s"
+ "%{public}s failed: %{private}s %{public}s xpcRequestID=%{public}s%{public}s"
+ "%{public}s found %{public}ld notes for one create token, adopting the first"
+ "%{public}s found no item for change item %ld's create token after a duplicate-token refusal"
+ "%{public}s has no create token for change item %ld; creating without one"
+ "%{public}s returned error %{private}s %{public}s"
+ "%{public}s skipped — folder already has externalID %{public}s"
+ "' and ep/value eq '"
+ "@\"EWSBaseItemIdType\"16@?0@\"NSString\"8"
+ "@\"EXSDataConsumerInstance\"16@?0@\"EXSDataConsumerPlugin\"8"
+ "@\"NSDateComponents\"16@?0@\"NSDate\"8"
+ "@\"PQLResultSet\"24@?0q8q16"
+ "ALTER TABLE exs_change_items ADD create_token text"
+ "Account %{public}@ has a converted local store but resolved to EWS; routing to Graph instead."
+ "Account %{public}@ settled on sync dialect %ld (protocol kind %ld)."
+ "Add Calendar Delegate Operation returned error %{private}s %{public}s"
+ "Advanced change source (%{public}@) past declined change items to %ld."
+ "Advanced the Graph migration state for account %{public}@ from %ld to %ld."
+ "Applied folder map revision %ld from %{public}s (%ld folder(s), hash %{public}s): %ld row change(s), %ld removal(s), %ld kept, %ld held%{public}s%{public}s"
+ "Availability lookup outcome=failure xpcRequestID=%{public}s queuedMs=%{public}ld durationMs=%{public}ld recipientCount=%{public}ld"
+ "Availability lookup outcome=success xpcRequestID=%{public}s queuedMs=%{public}ld durationMs=%{public}ld recipientCount=%{public}ld resultCount=%{public}ld"
+ "B8@?0"
+ "CREATE INDEX IF NOT EXISTS exs_attachments_associated_event_id_idx ON exs_attachments (associated_event_id)"
+ "CREATE INDEX IF NOT EXISTS exs_change_items_item_id_idx ON exs_change_items (item_id)"
+ "CREATE INDEX IF NOT EXISTS exs_items_external_itemID_idx ON exs_items (external_itemID)"
+ "CREATE INDEX IF NOT EXISTS exs_items_folder_id_item_id_idx ON exs_items (folder_id, item_id)"
+ "CREATE TABLE IF NOT EXISTS exs_web_push_subscriptions (account_key text NOT NULL, data_class text NOT NULL, folder_externalID text NOT NULL, graph_resource text NOT NULL, change_type text NOT NULL, topic text NOT NULL, state tinyint NOT NULL, subscription_id text NOT NULL, expiration_at bigint NOT NULL, notification_url_hash text NOT NULL, subscriber_key_hash text NOT NULL, PRIMARY KEY (data_class, folder_externalID))"
+ "CREATE TEMP TABLE IF NOT EXISTS exs_store_reset_chunk_keys (item_id INTEGER, internal_itemID TEXT, external_itemID TEXT, surviving INTEGER)"
+ "Calendar folder id canonicalization for account %{public}@ aborted -- %{public}lu folder(s) could not be resolved. Nothing was written; the next startup retries."
+ "Calendar folder id canonicalization for account %{public}@ aborted -- a stored identifier was neither resolved nor reported gone. Nothing was written."
+ "Calendar folder id canonicalization for account %{public}@ aborted -- all %{public}lu stored identifier(s) were reported gone, which is a failed lookup rather than an empty mailbox. Nothing was written; the next startup retries."
+ "Calendar folder id canonicalization for account %{public}@ aborted -- the rewrite transaction rolled back. The next startup retries."
+ "Calendar folder id canonicalization for account %{public}@ aborted -- the stored identifiers could not be read."
+ "Calendar folder id canonicalization for account %{public}@: %{public}lu stored, %{public}lu rewritten, %{public}lu already canonical, %{public}lu reported gone."
+ "Calendar folder id canonicalization for account %{public}@: no calendar folders stored, nothing to canonicalize."
+ "Calendar permission operation (type=%ld) returned error %{private}s %{public}s"
+ "Change item %ld's item was deleted while its create was in flight; recorded the server ID on %lld later deletion(s)"
+ "Collapsed %{public}lu duplicate item row(s); kept %{public}lu linked to another local object"
+ "Committed the one-way Graph migration latch for account %{public}@."
+ "Consumer change source %{public}@ lacks the %{public}@ prefix; its local edits will never upsync."
+ "Couldn't add create_token to change items table in sync engine database: %{public}@ %ld"
+ "Couldn't clear web push subscriptions in sync engine database: %{public}@"
+ "Couldn't collapse a duplicate item row: %{public}@"
+ "Couldn't create attachments associated_event_id index in sync engine database: %{public}@"
+ "Couldn't create change items item_id index in sync engine database: %{public}@"
+ "Couldn't create items external_itemID index in sync engine database: %{public}@ %ld"
+ "Couldn't create items folder_id index in sync engine database: %{public}@"
+ "Couldn't create web push subscriptions table in sync engine database: %{public}@"
+ "Couldn't delete web push subscription from sync engine database: %{public}@"
+ "Couldn't drop web push subscriptions table in sync engine database: %{public}@ %ld"
+ "Couldn't read change items columns in sync engine database: %{public}@ %ld"
+ "Couldn't read web push subscriptions columns in sync engine database: %{public}@ %ld"
+ "Couldn't read web push subscriptions from sync engine database: %{public}@"
+ "Couldn't record the terminal purge stamp in sync engine database: %{public}@ %ld"
+ "Couldn't record the terminal purge stamp: the sync engine database is closed."
+ "Couldn't refetch live ACAccount to advance the Graph migration state for %{public}@: %{public}@ %ld"
+ "Couldn't save the Graph migration state %ld for account %{public}@: %{public}@ %ld"
+ "Couldn't update item for an add: %{public}@"
+ "Couldn't write web push subscription to sync engine database: %{public}@"
+ "Created missing web push subscriptions table at schema version %li"
+ "DELETE FROM exs_attachments WHERE account_id=%ld AND rowid IN (%@)"
+ "DELETE FROM exs_change_items WHERE account_id=%ld AND change_id IN (%@)"
+ "DELETE FROM exs_change_items WHERE account_id=%ld AND item_id=%ld AND item_type IN (%ld,%ld,%ld,%ld,%ld,%ld)"
+ "DELETE FROM exs_change_items WHERE change_id IN (SELECT change_id FROM exs_change_items WHERE account_id=%ld AND change_id < %ld LIMIT %ld)"
+ "DELETE FROM exs_distinguished_folders WHERE account_id=%ld AND external_folderID=%@"
+ "DELETE FROM exs_folders WHERE account_id=%ld AND folder_id=%ld"
+ "DELETE FROM exs_items WHERE account_id=%ld AND item_id IN (%@)"
+ "DELETE FROM exs_store_reset_chunk_keys"
+ "DELETE FROM exs_web_push_subscriptions WHERE account_key=%@"
+ "DELETE FROM exs_web_push_subscriptions WHERE account_key=%@ AND data_class=%@ AND folder_externalID=%@"
+ "DROP TABLE exs_web_push_subscriptions"
+ "DataConsumer-"
+ "DataConsumer-*"
+ "Dataclass-0x%lx"
+ "Deleted on server (op=%{public}s, change=%ld, externalID=%{public}s)"
+ "Did not advance change source (%{public}@) past declined change items: its watermark is no longer %ld."
+ "Directory search outcome=%{public}s %{private}s %{public}s xpcRequestID=%{public}s recordTypes=%{public}s failedTypes=%{public}s queuedMs=%{public}ld durationMs=%{public}ld resultCount=%{public}ld queryLength=%{public}ld"
+ "Directory search outcome=invalidRequest %{private}s recordTypes=%{public}s queuedMs=%{public}ld"
+ "Directory search outcome=success xpcRequestID=%{public}s recordTypes=%{public}s queuedMs=%{public}ld durationMs=%{public}ld resultCount=%{public}ld queryLength=%{public}ld"
+ "Duplicate values for key: '"
+ "EXSDataConsumerInstance: consumer asked for held change items to be re-delivered."
+ "EXSDataclassCallGate"
+ "EXSDataclassCallGate: a %{public}@ client call took %.1fs from enqueue (timeout %.0fs)."
+ "EXSDataclassCallGate: re-enqueueing %lu durable %{public}@ call(s) onto the fresh queue."
+ "EXSDataclassCallGate: the %{public}@ client store did not answer within %.0fs; abandoning the call and refusing further calls until it does. Callers see a refusal immediately rather than another wait. (consecutive trips: %lu)"
+ "EXSDataclassCallGate: the %{public}@ client store has not answered for %.0fs; the call is presumed lost and its queue permanently wedged. Starting a fresh queue (%lu of %lu abandoned queues now outstanding); one thread stays parked in the abandoned call until it drains."
+ "EXSDataclassCallGate: the %{public}@ client store is answering again; closing the breaker."
+ "EXSDataclassCallGate: the %{public}@ client store is not answering and all %lu abandoned queues are still wedged, so there is no budget left to start another. Every call for this data class is refused until one of them drains or the daemon restarts. Durable calls stranded on those queues: %lu."
+ "EXSGSBoundedTransaction '%{public}s' still held after its bound elapsed; force-released"
+ "EXSGSCalendarFolderIDCanonicalization"
+ "EXSGSGraphIDConversion"
+ "EXSGSMigrationEscalation"
+ "EXSSyncProtocol: change %ld was offered again after it settled; moved the watermark from %ld to %ld (change source %{public}@)"
+ "EXSSyncProtocol: stopping the push drain, change %ld was offered again after it settled; the watermark reads %ld (change source %{public}@)"
+ "EXSSyncProtocolFactory"
+ "EXSXPCInterfaceImplementation: Received an XPC call beginSearchDirectoryForAccountID:queryString:recordTypes:fullContactData:withReply:"
+ "EXSXPCInterfaceImplementation: addDelegateWithName timed out after %lld s waiting for the delegate permission check"
+ "Error while advancing change source (%{public}@) past declined change items in sync engine database: %{public}@"
+ "ErrorDuplicateTransactionId"
+ "Exchange is temporarily limiting requests for this account. Try again in a few minutes."
+ "Executing room search for query %{private}s"
+ "Expected GraphSyncEventsCollectionResponse from calendar event list"
+ "Expected GraphSyncListCalendarsResponse from the calendar listing"
+ "Expected GraphSyncStickyNoteListResource from the note lookup"
+ "Failed to clear the create token for change item %ld: %{public}@"
+ "Failed to mint create token for change item %ld: %{public}@"
+ "Failed to probe for a later deletion of change item %ld: %{public}@ %ld"
+ "Failed to prune stale change items below watermark %ld for account %ld: %{public}@"
+ "Failed to read create token for change item %ld: %{public}@ %ld"
+ "Failed to read unpushed change items: %{public}@"
+ "Failed to record the created item's ID on later deletions of change item %ld: %{public}@"
+ "Fatal error"
+ "Get item change key"
+ "Giving up on %ld note folder cascade(s) after %ld days — their notes may stay on the server"
+ "Graph ID conversion attempt"
+ "Graph ID conversion attempt refund"
+ "Graph ID conversion cancelled for account %{public}@. Attempt refunded, retrying next launch."
+ "Graph ID conversion committed for account %{public}@: %lu identifiers in %llu ms."
+ "Graph ID conversion deferred for account %{public}@: attempt count unreadable."
+ "Graph ID conversion deferred for account %{public}@: could not charge an attempt."
+ "Graph ID conversion deferred for account %{public}@: database open result %ld is not up to date."
+ "Graph ID conversion exceeded its deadline for account %{public}@. Attempt charged."
+ "Graph ID conversion failed for account %{public}@: %{public}@"
+ "Graph ID conversion failure"
+ "Graph ID conversion for account %{public}@ committed AND recorded an abort reason. Treating as a failure."
+ "Graph ID conversion for account %{public}@ committed over an empty store. Recording NoDataToConvert."
+ "Graph ID conversion for account %{public}@ committed with %lu untranslated rows. The abort policy did not hold."
+ "Graph ID conversion for account %{public}@ rolled back with no abort reason."
+ "Graph ID conversion held for account %{public}@ with precondition %ld."
+ "Graph ID conversion held for account %{public}@: %ld attempts exhausted."
+ "Graph ID conversion refused for account %{public}@ with precondition %ld. Retrying next launch."
+ "Graph ID conversion starting for account %{public}@ (attempt %ld of %ld)."
+ "Graph Sync: %{public}s found what an earlier attempt committed; not sending again (attempt %{public}ld)"
+ "Graph Sync: %{public}s not retrying; the throttle gate just closed"
+ "Graph Sync: Notes cutover could not fold the EWS Notes folder; will retry next startup"
+ "Graph Sync: Notes cutover could not read the legacy Notes folder; will retry next startup"
+ "Graph Sync: Notes cutover could not store the seeded folder map; will retry next startup"
+ "Graph Sync: Notes cutover folded the EWS Notes folder into the Graph container"
+ "Graph Sync: Notes cutover folder map is over the size cap; the hierarchy will not be published"
+ "Graph Sync: Notes cutover found both the EWS Notes folder and the Graph container; leaving both"
+ "Graph Sync: Notes cutover found no Notes folders to seed a folder map from"
+ "Graph Sync: Notes cutover kept the folder map already stored"
+ "Graph Sync: Notes cutover seeded folder map revision %{public}ld with %{public}ld folder(s); it publishes after the first Graph round"
+ "Graph Sync: Starting polling (heartbeat scheduler)"
+ "Graph Sync: Stopping polling (heartbeat scheduler)"
+ "Graph Sync: applied the server's name for folder %{public}s"
+ "Graph Sync: calendar folder id canonicalization for account %{public}s could not resolve %{public}ld of %{public}ld folder(s) in a batch (%{public}ld empty-bodied, %{public}ld dropped); cutover housekeeping will retry next startup"
+ "Graph Sync: calendar folder id canonicalization for account %{public}s exceeded its %{public}.*fs deadline with %{public}ld of %{public}ld folder(s) resolved; cutover housekeeping will retry next startup"
+ "Graph Sync: calendar folder id canonicalization for account %{public}s failed for a batch of %{public}ld folder(s), %{public}s %{public}ld requestID=%{public}s; cutover housekeeping will retry next startup"
+ "Graph Sync: calendar folder id canonicalization for account %{public}s got a calendar with no id; cutover housekeeping will retry next startup"
+ "Graph Sync: calendar folder id canonicalization for account %{public}s resolved %{public}ld of %{public}ld folder(s); %{public}ld reported gone"
+ "Graph Sync: change %ld (changeType %ld itemType %ld) was deleted locally before it reached the server; skipping it"
+ "Graph Sync: change %ld was recorded before its create landed; addressing it with the server ID the create stored (%{private}s)"
+ "Graph Sync: could not apply the server's name for folder %{public}s - %{public}s %ld"
+ "Graph Sync: declining to %{public}s the distinguished Tasks list, the server does not permit it - account %{public}s folder %{public}s"
+ "Graph Sync: dropping the task-list delta cursor for %{public}s, the next round re-seeds - account %{public}s"
+ "Graph Sync: failed to drop the task-list delta cursor for %{public}s; the distinguished Tasks list stays diverged locally"
+ "Graph Sync: heartbeat config %{public}s account=%{public}s"
+ "Graph Sync: heartbeat deferForPush (draining) tiers=%{public}s consecutiveDefers=%{public}ld account=%{public}s"
+ "Graph Sync: heartbeat not stamped tier=%{public}ld refreshCompleted=%{bool,public}d errorSurfaced=%{bool,public}d account=%{public}s"
+ "Graph Sync: heartbeat runFolderTier (push-covered) tier=%{public}ld account=%{public}s"
+ "Graph Sync: heartbeat runFullSync tier=%{public}ld account=%{public}s"
+ "Graph Sync: heartbeat scheduler activity criteria updated delay=%{public}lldm grace=%{public}lldm"
+ "Graph Sync: heartbeat scheduler activity registered delay=%{public}lldm grace=%{public}lldm"
+ "Graph Sync: heartbeat scheduler activity unregistered (no registrants)"
+ "Graph Sync: heartbeat scheduler fire accounts=%{public}ld pruned=%{public}ld"
+ "Graph Sync: heartbeat scheduler fire queued=%{public}ld of accounts=%{public}ld"
+ "Graph Sync: heartbeat scheduler fire with no live registrants"
+ "Graph Sync: heartbeat scheduler registered account=%{public}s registrants=%{public}ld"
+ "Graph Sync: heartbeat scheduler unregistered account=%{public}s registrants=%{public}ld"
+ "Graph Sync: heartbeat skip (%{public}s) tier=%{public}ld account=%{public}s"
+ "Graph Sync: heartbeat stamping resumed tier=%{public}ld account=%{public}s"
+ "Graph Sync: heartbeat tick skipped, account not registered account=%{public}s"
+ "Graph Sync: heartbeat tick skipped, previous tick still queued account=%{public}s"
+ "Graph Sync: holding queue coalesced %{public}s (class=%{public}ld)"
+ "Graph Sync: holding queue dropped %{public}ld parked entr(ies) at shutdown"
+ "Graph Sync: holding queue dropped stale %{public}s"
+ "Graph Sync: holding queue gave up on %{public}s after its patience ran out"
+ "Graph Sync: holding queue parked %{public}s (class=%{public}ld parked=%{public}ld)"
+ "Graph Sync: holding queue released %{public}s after %{public}.*fs (remaining=%{public}ld)"
+ "Graph Sync: holding queue wake %{public}s dropped done without calling it; finishing its release"
+ "Graph Sync: holding queue wake %{public}s has not finished after %{public}.*fs; release is stalled"
+ "Graph Sync: holding the surfaced sync state; Calendar's round sat out the throttle window"
+ "Graph Sync: not surfacing Calendar's short throttle (retryAfter=%{public}s)"
+ "Graph Sync: note %{public}s carries no folder edge — keeping its stored folder %{public}s"
+ "Graph Sync: note folder map blob is unreadable; nothing to clear"
+ "Graph Sync: note folder map clear did not persist"
+ "Graph Sync: on-demand request refused; the throttle window has %{public}.*fs left, past the %{public}.*fs patience"
+ "Graph Sync: pending note folder cascades did not persist (%ld folder(s))"
+ "Graph Sync: pending note folder cascades stopped — %{public}s requestID=%{public}s; still owed"
+ "Graph Sync: push parked — throttle gate closed"
+ "Graph Sync: repeated inline throttle waits; closing the throttle gate"
+ "Graph Sync: task create has no title; sending the untitled-task title"
+ "Graph Sync: throttle gate closed, parking calendar folder hierarchy sync"
+ "Graph Sync: throttle gate closed, parking task folder hierarchy sync"
+ "Graph Sync: throttle gate closed, turning work away (turnedAway=%{public}ld)"
+ "Graph Sync: throttle gate reopened after %{public}.*fs (turnedAway=%{public}ld, window elapsed)"
+ "Graph Sync: user refresh parked for %{public}ld — throttle gate closed"
+ "Graph calendar folder id rewrite faulted on statement %{public}zu with error %{public}ld; rolling back."
+ "Graph folder id rewrite refused: the mapping chains one identifier onto another. Nothing was written."
+ "Graph folder id rewrite refused: two stored identifiers map onto the same new one. Nothing was written."
+ "Graph migration %{public}s for account %{public}@: phase=%ld kind=%ld reason=%ld attempt=%ld/%ld decision=%ld"
+ "Graph migration cutover housekeeping complete for account %{public}@."
+ "Graph migration cutover housekeeping for account %{public}@ aborted -- Notes folder preparation failed."
+ "Graph migration cutover housekeeping for account %{public}@ aborted -- calendar folder identifier canonicalization failed. Nothing was written."
+ "Graph migration cutover housekeeping for account %{public}@: Notes folders prepared."
+ "Graph migration cutover housekeeping for account %{public}@: calendar folder identifiers canonicalized."
+ "Graph migration cutover housekeeping for account %{public}@: every folder's external sync state cleared, a full reconciling seed will follow."
+ "Graph migration cutover housekeeping for account %{public}@: watermark seeded."
+ "Graph migration for account %{public}@: Graph reinstalled over the purged store."
+ "Graph migration for account %{public}@: after the terminal purge the protocol re-derived to kind %ld (requiresCutover %d); holding paused."
+ "Graph migration for account %{public}@: could not write TerminalFailure after the purge; a later launch advances it to GraphEngineUp instead."
+ "Graph migration for account %{public}@: terminal purge triggered by phase %ld."
+ "Graph migration state for account %{public}@ is NoDataToConvert (8) with no local EWS history -- proceeding to Graph."
+ "Graph migration terminal purge %{public}s for account %{public}@: phase=%ld step=%ld outcome=%ld resetPrecondition=%ld clientStores=%lu/%lu/%lu faulted=%lu stamped=%d"
+ "Graph migration terminal purge for account %{public}@ could not stamp the store after %lu attempts."
+ "Graph migration terminal purge for account %{public}@: Notes folder map cleared."
+ "Graph migration terminal purge for account %{public}@: client store for folder type %ld NOT discarded (outcome=%ld attempts=%lu). It may duplicate on re-seed."
+ "Graph migration terminal purge for account %{public}@: client store for folder type %ld discarded (outcome=%ld attempts=%lu)."
+ "Graph migration terminal purge for account %{public}@: local store reset (items=%lu folders=%lu changeItems=%lu attachments=%lu unpushedDiscarded=%lu staleDrainsCleared=%lu attempts=%lu perDataClass=%d)."
+ "Graph migration terminal purge starting for account %{public}@."
+ "GraphHeartbeatIgnorePush"
+ "GraphHeartbeatPushCoveredIntervalMinutes"
+ "GraphHeartbeatPushHealthyWindowMinutes"
+ "GraphHeartbeatWaitCapMinutes"
+ "GraphSyncResolveNamesResponse"
+ "Holding note folder %{public}s at revision %ld: it has a local change not yet pushed"
+ "INSERT INTO exs_store_reset_chunk_keys (item_id, internal_itemID, external_itemID, surviving) VALUES (%ld,%@,%@,0)"
+ "INSERT OR REPLACE INTO exs_web_push_subscriptions (account_key, data_class, folder_externalID, graph_resource, change_type, topic, state, subscription_id, expiration_at, notification_url_hash, subscriber_key_hash) VALUES (%@, %@, %@, %@, %@, %@, %d, %@, %lld, %@, %@)"
+ "Item has no external ID - was never synced to server, treating as success (op=%{public}s, change=%ld)"
+ "Migrating to database version: %i"
+ "Move attachment copy — %ld copied, %ld already present, %ld skipped of %ld source attachment(s)"
+ "Move attachment copy — listing the moved event's attachments failed (%{private}s); copying all"
+ "Move completed (change=%ld, from=%{public}s, to=%{public}s, cancellationsRecreated=%ld, hasAttachments=%{bool}d, originalAlreadyGone=%{bool}d)"
+ "Move rollback failed to persist; local move stands (reason=%{public}s, event=%{public}s)"
+ "Move rollback not possible — no source calendar recorded; local move stands (reason=%{public}s, event=%{public}s)"
+ "Move rollback not possible — source calendar has no local folder; local move stands (reason=%{public}s, event=%{public}s)"
+ "Move rolled back — event returns to its source calendar (reason=%{public}s, event=%{public}s, calendar=%{public}s)"
+ "Move skipped — event has %ld attendee(s); Graph cannot move a meeting between calendars."
+ "Move skipped — event has no server identity yet (change=%ld)"
+ "Move skipped — item already remapped to the moved event (change=%ld, event=%{public}s)"
+ "Move — cleaned up orphaned CREATE after a failed cancellation recreation"
+ "Move — orphaned CREATE already gone on cleanup (404/410), nothing to do"
+ "Move — orphaned CREATE not removed (%{private}s); manual cleanup needed"
+ "No response message for update request."
+ "Not recording NoDataToConvert for untracked account %{public}@: a local store may exist."
+ "Not writing Graph migration state NoDataToConvert (8) for account %{public}@: it reads %ld, not NeedsMigration (0)."
+ "Note folder %{public}s cascade left notes on the server and could not be recorded — the folder can resurrect"
+ "Note folder %{public}s cascade left notes on the server — owed to the next Notes round"
+ "Notes cutover fold faulted on step %{public}d with error %{public}ld; rolling back."
+ "Notes cutover fold refused: the container already exists or could not be checked."
+ "Notes cutover: %{public}lu candidate EWS Notes folders; folding none."
+ "Pruned %lld stale change items below watermark %ld for account %ld"
+ "Push data state (fail) for change source (%{public}@) matched no row; last_change_item_id stays where it was"
+ "Push data state (success) for change source (%{public}@) matched no row; last_change_item_id stays where it was"
+ "PushCoveredIntervalMinutes"
+ "PushHealthyWindowMinutes"
+ "Received an XPC request to sync account for nil dataclass; draining only"
+ "Recreated web push subscriptions table missing %li columns at schema version %li"
+ "Refusing to advance the Graph migration state for %{public}@: it already reads %ld, which is terminal or undefined."
+ "Refusing to advance the Graph migration state from a delegate account %{public}@ -- the property is parent-scoped."
+ "Refusing to discard the client store: this instance already has a live consumer."
+ "Refusing to write Graph migration state %ld for account %{public}@ -- not a state this engine owns."
+ "RelocateToParentCalendar"
+ "Response item count is %lu (expected to be 1), class is %{public}@ (expected to be EWSItemType)."
+ "Retrying %ld note delete(s) owed by %ld deleted folder(s)"
+ "Room search returned %{public}ld result(s) before the room-type guard"
+ "Round paused at a page boundary — the throttle gate closed"
+ "SELECT 1 FROM exs_change_items WHERE account_id=%ld AND change_id > %ld AND change_source_id GLOB %@ LIMIT 1"
+ "SELECT 1 FROM exs_change_items WHERE account_id=%ld AND internal_itemID=%@ AND item_type=%ld AND change_type=%ld AND change_id > %ld AND IFNULL(isDetached, 0)=0 AND change_source_id GLOB %@ LIMIT 1"
+ "SELECT 1 FROM exs_folders WHERE account_id=%ld AND folder_id=%ld LIMIT 1"
+ "SELECT 1 FROM exs_graph_migration_verified WHERE id=1 AND converted_at IS NOT NULL"
+ "SELECT 1 FROM exs_items WHERE account_id=%ld AND item_id=%ld LIMIT 1"
+ "SELECT 1 FROM pragma_table_info('exs_change_items') WHERE name='create_token'"
+ "SELECT 1 FROM sqlite_master WHERE type='table' AND name='exs_change_items'"
+ "SELECT 1 FROM sqlite_master WHERE type='table' AND name='exs_items'"
+ "SELECT COALESCE(MIN(CASE WHEN change_source_id GLOB %@ THEN change_id END) - 1, MAX(change_id), 0) FROM exs_change_items WHERE account_id=%ld AND change_id > %ld"
+ "SELECT COALESCE(conversion_attempt_count, 0) FROM exs_graph_migration_verified WHERE id=1"
+ "SELECT COUNT(*), COUNT(CASE WHEN name IN ('account_key', 'data_class', 'folder_externalID', 'graph_resource', 'change_type', 'topic', 'state', 'subscription_id', 'expiration_at', 'notification_url_hash', 'subscriber_key_hash') THEN 1 END) FROM pragma_table_info('exs_web_push_subscriptions')"
+ "SELECT DISTINCT d.folder_type, d.external_folderID FROM exs_distinguished_folders d WHERE d.account_id=%ld AND d.external_folderID != '' AND (d.folder_type=%ld OR (d.folder_type=%ld AND d.external_folderID != %@  AND EXISTS (SELECT 1 FROM exs_folders f WHERE f.account_id=d.account_id   AND f.external_folderID=d.external_folderID AND f.folder_type=%ld AND f.marked_as_deleted=0))) ORDER BY 1, 2"
+ "SELECT DISTINCT external_itemID FROM exs_change_items WHERE account_id=%ld AND item_type=%ld AND change_source_id GLOB %@ AND external_itemID IS NOT NULL AND external_itemID != '' AND change_id > COALESCE((SELECT last_change_item_id FROM exs_change_sources WHERE account_id=%ld AND change_source_id=%@), 0)"
+ "SELECT EXISTS (SELECT 1 FROM exs_items) OR EXISTS (SELECT 1 FROM exs_folders) OR EXISTS (SELECT 1 FROM exs_distinguished_folders) OR EXISTS (SELECT 1 FROM exs_change_items) OR EXISTS (SELECT 1 FROM exs_attachments)"
+ "SELECT cached_file_path FROM exs_attachments WHERE cached_file_path IS NOT NULL AND cached_file_path!=''"
+ "SELECT change_id FROM exs_change_items WHERE account_id=%ld AND item_id=%ld AND item_type IN (%ld,%ld,%ld,%ld,%ld,%ld)"
+ "SELECT change_id FROM exs_change_items WHERE account_id=%ld AND item_type IN (%ld,%ld,%ld,%ld,%ld,%ld) AND (item_id=%ld   OR (internal_itemID IS NOT NULL AND internal_itemID!='' AND internal_itemID=%@)   OR (external_itemID IS NOT NULL AND external_itemID!='' AND external_itemID=%@))"
+ "SELECT change_id, account_id, item_type, change_type, change_source_id, modification_dt, item_id, external_itemID, external_changeKey, external_parentFolderID, internal_itemID, internal_changeKey, internal_parentFolderID, shouldSendNotification, eventHasAttendees, isDetached, parentExternalID, parentInternalID, instanceIndex, properties_blob FROM exs_change_items WHERE account_id=%ld AND change_id > %ld AND change_source_id != %@ ORDER BY change_id LIMIT %ld"
+ "SELECT change_id, account_id, item_type, change_type, change_source_id, modification_dt, item_id, external_itemID, external_changeKey, external_parentFolderID, internal_itemID, internal_changeKey, internal_parentFolderID, shouldSendNotification, eventHasAttendees, isDetached, parentExternalID, parentInternalID, instanceIndex, properties_blob FROM exs_change_items WHERE account_id=%ld AND change_id > %ld AND change_source_id GLOB %@ ORDER BY change_id LIMIT %ld"
+ "SELECT change_id, item_id, internal_itemID, external_itemID, isDetached, parentExternalID, parentInternalID FROM exs_change_items WHERE account_id=%ld AND item_type IN (%ld,%ld,%ld,%ld,%ld,%ld) AND (item_id IN (SELECT item_id FROM exs_store_reset_chunk_keys)   OR (internal_itemID IS NOT NULL AND internal_itemID!=''       AND internal_itemID IN (SELECT internal_itemID FROM exs_store_reset_chunk_keys                               WHERE internal_itemID IS NOT NULL))   OR (external_itemID IS NOT NULL AND external_itemID!=''       AND external_itemID IN (SELECT external_itemID FROM exs_store_reset_chunk_keys                               WHERE external_itemID IS NOT NULL))   OR (isDetached!=0 AND parentExternalID IS NOT NULL AND parentExternalID!=''       AND parentExternalID IN (SELECT external_itemID FROM exs_store_reset_chunk_keys                                WHERE external_itemID IS NOT NULL))   OR (isDetached!=0 AND parentInternalID IS NOT NULL AND parentInternalID!=''       AND parentInternalID IN (SELECT internal_itemID FROM exs_store_reset_chunk_keys                                WHERE internal_itemID IS NOT NULL)))"
+ "SELECT change_source_id FROM exs_change_sources WHERE account_id=%ld"
+ "SELECT change_source_id, last_change_item_id FROM exs_change_sources WHERE account_id=%ld"
+ "SELECT count(*) FROM (SELECT 1 FROM exs_change_items WHERE account_id=%ld AND change_id > %ld LIMIT 1)"
+ "SELECT count(*) FROM (SELECT DISTINCT account_id FROM exs_items UNION SELECT DISTINCT account_id FROM exs_folders UNION SELECT DISTINCT account_id FROM exs_attachments UNION SELECT DISTINCT account_id FROM exs_change_items UNION SELECT DISTINCT account_id FROM exs_distinguished_folders)"
+ "SELECT count(*) FROM exs_attachments"
+ "SELECT count(*) FROM exs_attachments WHERE account_id=%ld AND (associated_event_id IS NULL OR associated_event_id='')"
+ "SELECT count(*) FROM exs_change_items"
+ "SELECT count(*) FROM exs_change_items WHERE account_id=%ld AND change_id > %ld"
+ "SELECT count(*) FROM exs_change_items WHERE account_id=%ld AND item_id=%ld AND item_type IN (%ld,%ld,%ld,%ld,%ld,%ld)"
+ "SELECT count(*) FROM exs_change_sources WHERE account_id=%ld AND change_source_id NOT GLOB %@"
+ "SELECT count(*) FROM exs_distinguished_folders"
+ "SELECT count(*) FROM exs_distinguished_folders WHERE account_id=%ld AND external_folderID=%@"
+ "SELECT count(*) FROM exs_folders"
+ "SELECT count(*) FROM exs_folders WHERE account_id=%ld AND (external_folderID IS NULL OR external_folderID='')"
+ "SELECT count(*) FROM exs_folders WHERE account_id=%ld AND external_folderID=%@"
+ "SELECT count(*) FROM exs_folders WHERE account_id=%ld AND external_folderID=%@ AND marked_as_deleted=0"
+ "SELECT count(*) FROM exs_folders WHERE account_id=%ld AND folder_id=%ld"
+ "SELECT count(*) FROM exs_folders WHERE account_id=%ld AND folder_id=(SELECT folder_id FROM exs_items WHERE account_id=%ld AND item_id=%ld)"
+ "SELECT count(*) FROM exs_items"
+ "SELECT count(*) FROM exs_items WHERE account_id=%ld AND (external_itemID IS NULL OR external_itemID='')"
+ "SELECT create_token FROM exs_change_items WHERE account_id=%ld AND change_id=%ld"
+ "SELECT data_class, folder_externalID, graph_resource, change_type, topic, state, subscription_id, expiration_at, notification_url_hash, subscriber_key_hash FROM exs_web_push_subscriptions WHERE account_key=%@"
+ "SELECT external_folderID FROM exs_folders WHERE account_id=%ld AND folder_id=%ld LIMIT 1"
+ "SELECT external_folderID FROM exs_folders WHERE account_id=%ld AND folder_type=%ld AND external_folderID IS NOT NULL AND external_folderID != '' UNION SELECT external_folderID FROM exs_distinguished_folders WHERE account_id=%ld AND folder_type=%ld AND external_folderID IS NOT NULL AND external_folderID != '' ORDER BY 1"
+ "SELECT external_folderID, internal_folderID FROM exs_folders WHERE account_id=%ld AND folder_id=%ld LIMIT 1"
+ "SELECT external_itemID, external_changeKey FROM exs_items WHERE account_id=%ld AND external_itemID IN (SELECT value FROM json_each(%@)) ORDER BY (internal_itemID IS NULL OR internal_itemID = '') ASC, item_id DESC"
+ "SELECT folder_id FROM exs_folders WHERE account_id=%ld AND ((external_parentFolderID IS NOT NULL AND external_parentFolderID!=''       AND external_parentFolderID=%@)   OR (internal_parentFolderID IS NOT NULL AND internal_parentFolderID!=''       AND internal_parentFolderID=%@))"
+ "SELECT folder_id FROM exs_folders WHERE account_id=%ld AND folder_type=%ld ORDER BY folder_id"
+ "SELECT folder_id FROM exs_folders WHERE account_id=%ld AND internal_folderID=%@ LIMIT 1"
+ "SELECT folder_type FROM exs_folders WHERE account_id=%ld AND folder_id=%ld LIMIT 1"
+ "SELECT item_id FROM exs_items WHERE account_id=%ld AND internal_itemID=%@ LIMIT 1"
+ "SELECT item_id, external_itemID, internal_itemID FROM exs_items WHERE account_id=%ld AND folder_id=%ld AND item_id > %ld ORDER BY item_id LIMIT %ld"
+ "SELECT item_id, external_itemID, internal_itemID FROM exs_items WHERE account_id=%ld AND folder_id=%ld AND item_type=%ld AND item_id > %ld ORDER BY item_id LIMIT %ld"
+ "SELECT item_id, folder_id, account_id, item_type, external_itemID, external_changeKey, external_parentFolderID, internal_itemID, internal_changeKey, internal_parentFolderID FROM exs_items WHERE account_id=%ld AND external_itemID=%@ ORDER BY (internal_itemID IS NULL OR internal_itemID = '') ASC, item_id DESC"
+ "SELECT item_id, folder_id, item_type, external_itemID, internal_itemID FROM exs_items WHERE account_id=%ld AND item_id=%ld LIMIT 1"
+ "SELECT rowid FROM exs_attachments WHERE account_id=%ld AND (associated_event_id IS NULL OR associated_event_id='')"
+ "SELECT rowid, cached_file_path FROM exs_attachments WHERE account_id=%ld AND associated_event_id IS NOT NULL AND associated_event_id!='' AND associated_event_id IN (SELECT internal_itemID FROM exs_store_reset_chunk_keys                             WHERE surviving=1 AND internal_itemID IS NOT NULL                               AND internal_itemID!='')"
+ "Search Rooms"
+ "Search query is nil or empty."
+ "Skipping stale change item cleanup: no consuming change source registered for account %ld"
+ "Skipping the change-source integrity check: the consumer cannot reach its client store."
+ "Splitting availability lookup uniqueRecipientCount=%{public}ld requestCount=%{public}ld"
+ "Store reset for account %{public}@ could not clear its scratch table after finishing: %{public}@"
+ "Store reset for account %{public}@ removed %{public}lu row(s) but invalidated no cursor. The deleted data cannot return on a delta round."
+ "Store reset for account %{public}@ rolled back: %{public}@"
+ "Store reset for account %{public}@: scope=%{public}ld rowID=%{public}ld dryRun=%{public}d committed=%{public}d cancelled=%{public}d chunks=%{public}lu items=%{public}lu folders=%{public}lu changeItems=%{public}lu attachments=%{public}lu files=%{public}lu foldersSeeded=%{public}lu cursorsCleared=%{public}lu watermarksZeroed=%{public}lu staleDrainsCleared=%{public}lu unpushedDiscarded=%{public}lu skippedUnpushed=%{public}lu foldersSkippedUnpushed=%{public}lu foldersRetained=%{public}lu detachedReported=%{public}lu orphanAttachments=%{public}lu unlinkFailures=%{public}lu complete=%{public}d totalMs=%{public}.1f"
+ "Store reset refused for account %{public}@: scope=%{public}ld precondition=%{public}ld rowID=%{public}ld schemaVersion=%{public}ld"
+ "StoreReset"
+ "Swift/NativeDictionary.swift"
+ "TestHeartbeatCalendar"
+ "TestHeartbeatCalendarDelegates"
+ "TestHeartbeatNotes"
+ "TestHeartbeatReminders"
+ "TestHeartbeatWaitCapMinutes"
+ "The persisted subscriber keys could not be read, so no new keys were minted"
+ "The sync protocol was released before the request ran"
+ "The terminal purge stamp committed but did not read back."
+ "UPDATE exs_change_items SET create_token=%@ WHERE account_id=%ld AND change_id=%ld AND create_token IS NULL"
+ "UPDATE exs_change_items SET create_token=NULL WHERE account_id=%ld AND change_id=%ld"
+ "UPDATE exs_change_items SET external_itemID=%@, external_changeKey=%@ WHERE account_id=%ld AND internal_itemID=%@ AND item_type=%ld AND change_type=%ld AND change_id > %ld AND IFNULL(isDetached, 0)=0 AND (external_itemID IS NULL OR external_itemID='') AND change_source_id GLOB %@ AND NOT EXISTS (SELECT 1 FROM exs_items WHERE account_id=%ld AND internal_itemID=%@)"
+ "UPDATE exs_change_items SET external_parentFolderID=%@ WHERE account_id=%ld AND item_type=%ld AND external_parentFolderID=%@"
+ "UPDATE exs_change_items SET external_parentFolderID=%@ WHERE external_parentFolderID=%@ AND account_id=%ld"
+ "UPDATE exs_change_items SET item_id=%ld WHERE account_id=%ld AND item_id=%ld"
+ "UPDATE exs_change_items SET parentExternalID=%@ WHERE account_id=%ld AND item_type=%ld AND parentExternalID=%@"
+ "UPDATE exs_change_items SET parentExternalID=%@ WHERE parentExternalID=%@ AND account_id=%ld"
+ "UPDATE exs_change_sources SET last_change_item_id=%ld WHERE account_id=%ld AND change_source_id=%@ AND IFNULL(last_change_item_id, 0)=%ld"
+ "UPDATE exs_change_sources SET last_change_item_id=%ld, working_change_item_id=%ld WHERE account_id=%ld"
+ "UPDATE exs_change_sources SET push_data_state=%ld WHERE account_id=%ld AND change_source_id=%@"
+ "UPDATE exs_change_sources SET sync_state=%@ WHERE account_id=%ld AND change_source_id NOT GLOB %@"
+ "UPDATE exs_distinguished_folders SET external_folderID=%@ WHERE external_folderID=%@ AND account_id=%ld"
+ "UPDATE exs_folders SET external_folderID=%@ WHERE external_folderID=%@ AND account_id=%ld"
+ "UPDATE exs_folders SET external_folderID=%@, external_parentFolderID=NULL WHERE account_id=%ld AND folder_type=%ld AND external_folderID=%@"
+ "UPDATE exs_folders SET external_parentFolderID=%@ WHERE account_id=%ld AND folder_type=%ld AND external_parentFolderID=%@"
+ "UPDATE exs_folders SET external_parentFolderID=%@ WHERE external_parentFolderID=%@ AND account_id=%ld"
+ "UPDATE exs_folders SET external_syncState=NULL WHERE account_id=%ld AND folder_id IN (%@)"
+ "UPDATE exs_graph_migration_verified SET %@ WHERE id=1"
+ "UPDATE exs_graph_migration_verified SET converted_at=%ld WHERE id=1"
+ "UPDATE exs_graph_migration_verified SET converted_at=COALESCE(converted_at, %ld), housekeeping_completed_at=COALESCE(housekeeping_completed_at, %ld) WHERE id=1"
+ "UPDATE exs_items SET external_parentFolderID=%@ WHERE account_id=%ld AND item_type=%ld AND external_parentFolderID=%@"
+ "UPDATE exs_items SET external_parentFolderID=%@ WHERE external_parentFolderID=%@ AND account_id=%ld"
+ "UPDATE exs_store_reset_chunk_keys SET surviving=1 WHERE item_id IN (%@)"
+ "Update request failed. ResponseClass=%{public}ld ResponseCode=%{public}ld MessageText=%{private}@"
+ "Web Push: VAPID key fetch throttled; not suppressing. requestID=%{public}s"
+ "[EXSDataConsumerInstance _drainOutstandingChangeItems] Change %ld was offered again after it settled; moved the watermark for change source %{public}@ from %ld to %ld."
+ "[EXSDataConsumerInstance _drainOutstandingChangeItems] Stopping, change %ld was offered again after it settled; the watermark for change source %{public}@ reads %ld."
+ "[EXSDataConsumerInstance _drainOutstandingChangeItems] Stopping, could not persist the declined run."
+ "a change item for this row is still pending upsync; deleting both would let the server's older version overwrite the local edit"
+ "a chunk did not commit; its writes were discarded"
+ "a chunk's transaction could not be opened"
+ "a folder-type change item for this row is still pending upsync; deleting both would let the server's older version overwrite the local change"
+ "a refused rename"
+ "a write unit declined without recording a reason"
+ "accountKey=%{public}s holding %ld queued prefetch(es) behind the downsync throttle gate; re-pump in %{public}.*fs"
+ "accountRemoved"
+ "associated_event_id is null or empty; the row belongs to no item"
+ "attendees"
+ "built"
+ "cached_file_path is not a file URL"
+ "calendarDelegates"
+ "com.apple.exchangesync.dataclasscallgate.%s.%lu"
+ "com.apple.exchangesync.dataclasscallgate.%s.durable"
+ "com.apple.exchangesync.dataclasscallgate.%s.timer"
+ "com.apple.exchangesync.graph.throttle-holding-queue"
+ "com.apple.exchangesync.graphOnDemandThrottled"
+ "com.apple.exchangesync.poll."
+ "com.apple.exchangesync.poll.heartbeatDefer."
+ "com.apple.exchangesync.retryAfterDate"
+ "com.apple.exchangesync.webpush.notification."
+ "com.apple.exchangesync.webpush.subscribe."
+ "com.apple.exchangesync.webpush.subscriberkeys"
+ "com.apple.exchangesync.webpush.teardown."
+ "com.apple.exchangesyncd.graph_heartbeat"
+ "com.apple.exchangesyncd.graph_heartbeat.activity"
+ "com.apple.exchangesyncd.graph_heartbeat.state"
+ "completed"
+ "conversion_attempt_count=MAX(COALESCE(conversion_attempt_count, 0) + %ld, 0)"
+ "conversion_last_failure_at"
+ "converted_at"
+ "createdDateTime desc"
+ "dataClassIneligible"
+ "deferred"
+ "detached occurrence whose master item this reset removed"
+ "dropping attachmentUUID=%{public}s after %ld throttle requeue(s)"
+ "existing"
+ "expected actual "
+ "exs_change_sources"
+ "exs_graph_migration_verified"
+ "exs_store_reset_chunk_keys"
+ "external_folderID is null or empty; the folder has never reached the server"
+ "external_itemID is null or empty; the row has never reached the server"
+ "failure charged, holding"
+ "failure charged, retrying"
+ "failure escalated to a terminal purge"
+ "failure not charged, holding"
+ "filename size limit "
+ "folder still holds items skipped as unpushed local changes"
+ "folderHierarchyIneligible"
+ "folderTierOnly"
+ "has an unpushed local change"
+ "heartbeatEnabled="
+ "internalId externalId "
+ "m pushCoveredInterval="
+ "m pushHealthyWindow="
+ "masterID candidateCount "
+ "more than one folder on this account shares the external id being removed; the distinguished-folder row cannot be attributed to one of them safely"
+ "no non-consumer change source exists to invalidate; emptying the store would leave every server cursor claiming to be current"
+ "not requeueing attachmentUUID=%{public}s; account is gone"
+ "notesPendingFolderCascades"
+ "personType/subclass eq 'Room'"
+ "priv"
+ "pub"
+ "pushDisabled"
+ "q"
+ "read on %@ faulted with error %ld"
+ "read on %@ returned no result set"
+ "refused"
+ "refusing to stamp converted_at with %lu untranslated rows"
+ "requestedID resource "
+ "requeued attachmentUUID=%{public}s after a server backoff (requeue %ld/%ld)"
+ "scoredEmailAddresses"
+ "seedChangeSourceWatermarkFromExistingSources: Error reading pending change items for change source (%{public}@) in sync engine database: %{public}@"
+ "seriesWithExceptions"
+ "singleOccurrence"
+ "singleValueExtendedProperties/any(ep:ep/id eq '"
+ "syncAllFolderItems transaction '%{public}@' still held after its bound elapsed; force-released"
+ "the distinguished Tasks list is missing locally"
+ "the reset did not commit"
+ "the run was cancelled before the remaining cached files were unlinked; their metadata rows are already gone"
+ "throttle window ended"
+ "unknownType"
+ "unlink failed with error %ld"
+ "unrecognizedType"
+ "userPrincipalName"
+ "v"
+ "v16@?0@\"EXSDataclassCall\"8"
+ "v32@?0@\"NSUUID\"8@?<v@?>16^B24"
+ "webpush APS link connected=%{public}@"
+ "webpush health cleared=apsLinkDown again dataClasses=%{public}ld account=%{public}s"
+ "webpush health cleared=apsLinkDown dataClasses=%{public}ld downSeconds=%{public}ld account=%{public}s"
+ "webpush health dataClass=%{public}s cleared=expired account=%{public}s"
+ "webpush health dataClass=%{public}s cleared=renewGone account=%{public}s"
+ "webpush keystore delete failed=%{public}@ topic=%{private}@"
+ "webpush keystore load failed=%{public}@; keys are in-memory for this run"
+ "webpush keystore read failed=%{public}@ topic=%{private}@"
+ "webpush keystore read failed=%{public}@ treated=inMemoryOnly reason=missingEntitlement topic=%{private}@"
+ "webpush keystore read skipped=undecodable topic=%{private}@"
+ "webpush keystore restored topics=%{public}ld"
+ "webpush keystore save failed=%{public}@ topic=%{private}@"
+ "webpush keystore skipped=topicRemoved topic=%{private}@"
+ "webpush keystore skipped=undecodable count=%{public}ld"
+ "webpush recordstore clear failed"
+ "webpush recordstore clear failed dataClass=%{public}s"
+ "webpush recordstore delete failed dataClass=%{public}s"
+ "webpush recordstore restore failed; coverage stands down for this run"
+ "webpush recordstore restored records=%{public}ld skipped=%{public}ld"
+ "webpush recordstore write failed dataClass=%{public}s"
+ "webpush recordstore write skipped=wrongScope dataClass=%{public}s"
+ "webpush removal hook coordinator=%{public}s account=%{public}s"
+ "webpush renew failed kind=%{public}s subscriptionID=%{public}s kept=%{public}s httpStatus=%{public}s graphErrorCode=%{public}s error=%{public}s requestID=%{public}s"
+ "webpush renew kind=%{public}s subscriptionID=%{public}s grantedExpiry=%{public}s"
+ "webpush stage=1 eligibility dataClass=%{public}s kind=folderHierarchy eligible=no reason=delegateFolderHierarchyUnverified account=%{public}s"
+ "webpush stage=1 reconcile adopted subscriptionID=%{public}s dataClass=%{public}s"
+ "webpush stage=1 reconcile deleteFailed subscriptionID=%{public}s error=%{public}s"
+ "webpush stage=1 reconcile dropped=%{public}s subscriptionID=%{public}s dataClass=%{public}s"
+ "webpush stage=1 reconcile purgedKeys=unclaimedTopic account=%{public}s"
+ "webpush stage=1 reconcile summary dataClass=%{public}s adopted=%{public}ld replaced=%{public}ld dropped=%{public}ld account=%{public}s"
+ "webpush stage=1 reconcile walkSkipped=recordsIncomplete account=%{public}s"
+ "webpush stage=10 caller=%{public}s downsync scope=%{public}s reason=%{public}s narrowed=%{public}s skippedItemFolders=%{public}ld folderTiers=%{public}ld itemTiers=%{public}ld refreshed=%{public}s folderHierarchy=%{public}s uncursored=%{public}ld"
+ "webpush stage=10 caller=%{public}s downsync scope=%{public}s reason=%{public}s skipped=throttled"
+ "webpush stage=2 coverage skipped=restoreIncomplete account=%{public}s"
+ "webpush stage=4 apsTokenRequested refused=keyStoreUnavailable topic=%{private}@"
+ "webpush stage=4 apsTokenRequested reused=persistedKeys topic=%{private}@"
+ "webpush stage=6 graphCreate dataClass=%{public}s kind=%{public}s resourceShape=%{public}s changeType=%{public}s topic=%{private}s"
+ "webpush stage=7 graphCreate failed dataClass=%{public}s kind=%{public}s resourceShape=%{public}s httpStatus=%{public}s graphErrorCode=%{public}s error=%{public}s requestID=%{public}s"
+ "webpush stage=7 graphCreateConflict409 dataClass=%{public}s kind=%{public}s resourceShape=%{public}s changeType=%{public}s requestID=%{public}s message=%{private}s"
+ "webpush stage=7 graphCreated subscriptionID=%{public}s grantedExpiry=%{public}s kind=%{public}s resourceShape=%{public}s"
+ "webpush stage=9 routed dropped=ineligible dataClass=%{public}s reason=%{public}s account=%{public}s"
+ "webpush stage=9b narrow dataClass=%{public}s entries=%{public}ld rejectedClientState=%{public}ld missingSubID=%{public}ld named=%{public}ld matchedLocal=%{public}ld folderHierarchy=%{public}ld keys=%{public}s"
+ "webpush stage=9c dropped=unknownSubscriptions dataClass=%{public}s named=%{public}ld"
+ "webpush teardown deleteFailed subscriptionID=%{public}s dataClass=%{public}s kind=%{public}s httpStatus=%{public}s graphErrorCode=%{public}s error=%{public}s requestID=%{public}s"
+ "webpush teardown reason=%{public}s deleted=%{public}ld dropped=%{public}ld stopped=%{public}s account=%{public}s"
+ "webpush teardown reason=pushDisabled skipped=restoreIncomplete account=%{public}s"
+ "write to %@ faulted with error %ld"
+ "\xf1"
- "$batch %{public}s throttled (HTTP 429) on %ld sub-request(s); over inline budget or retries exhausted"
- "$batch %{public}s throttled (HTTP 429) on %ld sub-request(s); waiting %{public}.*fs then retrying just those"
- "%{public}s failed: %{private}s"
- "%{public}s returned error %{private}s"
- "/me/calendars/{id}/events"
- "/me/todo/lists/{id}/tasks"
- "Add Calendar Delegate Operation returned error %{private}s"
- "Applied folder map revision %ld from %{public}s (%ld folder(s), hash %{public}s): %ld row change(s), %ld removal(s), %ld kept%{public}s%{public}s"
- "Calendar permission operation (type=%ld) returned error %{private}s"
- "DELETE FROM exs_change_items WHERE account_id=%ld AND change_id < %ld"
- "Expecting GraphSyncTodoTaskListsResponse but received Optional<Any>"
- "Graph Sync: declining to rename the distinguished Tasks list, the server does not permit it - account %{public}s folder %{public}s"
- "Graph Sync: failed to drop the task-list delta cursor after a refused rename; the distinguished Tasks list keeps the rejected name locally"
- "Graph Sync: heartbeat deferForPush (draining) consecutiveDefers=%{public}ld account=%{public}s"
- "Graph Sync: heartbeat not stamped (refreshCompleted=%{bool,public}d errorSurfaced=%{bool,public}d) account=%{public}s"
- "Graph Sync: heartbeat runFullSync account=%{public}s"
- "Graph Sync: heartbeat skip (%{public}s) account=%{public}s"
- "Graph Sync: throttle gate cleared after %{public}ld skipped round(s) (%{public}s)"
- "Graph Sync: throttle gate closed, skipping round (skipped=%{public}ld)"
- "Graph Sync: throttle gate reopened after %{public}.*fs (skipped=%{public}ld rounds, %{public}s)"
- "GraphHeartbeatEnabled"
- "GraphHeartbeatIntervalMinutes"
- "GraphWebPushFreshnessMinutes"
- "Item has no external ID - was never synced to server, treating as success"
- "List Notes"
- "Move attachment copy — %ld copied, %ld skipped of %ld source attachment(s)"
- "Move skipped — event has %ld attendee(s); meetings can only live in the default calendar."
- "Move skipped — event has no server identity yet"
- "Move skipped — item already remapped to the moved event"
- "Note folder %{public}s cascade left notes on the server — the folder can resurrect"
- "Received an XPC request to sync account for nil dataclass"
- "Response item count is %lu (expected to be 1), class is %@ (expected to be EWSItemType)."
- "Response message is not success. It's class %ld."
- "SELECT 1 FROM exs_change_items WHERE account_id=%ld AND change_id > %ld AND change_source_id != %@ LIMIT 1"
- "SELECT change_id, account_id, item_type, change_type, change_source_id, modification_dt, item_id, external_itemID, external_changeKey, external_parentFolderID, internal_itemID, internal_changeKey, internal_parentFolderID, shouldSendNotification, eventHasAttendees, isDetached, parentExternalID, parentInternalID, instanceIndex, properties_blob FROM exs_change_items WHERE account_id=%ld AND change_id > %ld AND change_source_id != %@ LIMIT %ld"
- "SELECT external_itemID, external_changeKey FROM exs_items WHERE account_id=%ld AND external_itemID IN (SELECT value FROM json_each(%@))"
- "SELECT item_id, folder_id, account_id, item_type, external_itemID, external_changeKey, external_parentFolderID, internal_itemID, internal_changeKey, internal_parentFolderID FROM exs_items WHERE account_id=%ld AND external_itemID=%@"
- "SELECT last_change_item_id FROM exs_change_sources WHERE account_id=%ld"
- "UPDATE exs_graph_migration_verified SET %@=%lld WHERE id=1"
- "account changed"
- "com.apple.exchangesync.exptool"
- "dataclass refresh requested"
- "webpush renew failed subscriptionID=%{public}s kept=%{public}s error=%{public}s requestID=%{public}s"
- "webpush renew subscriptionID=%{public}s grantedExpiry=%{public}s"
- "webpush stage=10 downsync scope=%{public}s reason=%{public}s narrowed=%{public}s folderTiers=%{public}ld itemTiers=%{public}ld refreshed=%{public}s"
- "webpush stage=10 downsync scope=%{public}s reason=%{public}s skipped=throttled"
- "webpush stage=6 graphCreate dataClass=%{public}s resourceShape=%{public}s changeType=%{public}s topic=%{private}s"
- "webpush stage=7 graphCreate failed dataClass=%{public}s resourceShape=%{public}s error=%{public}s requestID=%{public}s"
- "webpush stage=7 graphCreateConflict409 dataClass=%{public}s resourceShape=%{public}s changeType=%{public}s requestID=%{public}s message=%{private}s"
- "webpush stage=7 graphCreated subscriptionID=%{public}s grantedExpiry=%{public}s resourceShape=%{public}s"
- "webpush stage=9b narrow dataClass=%{public}s entries=%{public}ld rejectedClientState=%{public}ld missingSubID=%{public}ld named=%{public}ld matchedLocal=%{public}ld keys=%{public}s"
```
