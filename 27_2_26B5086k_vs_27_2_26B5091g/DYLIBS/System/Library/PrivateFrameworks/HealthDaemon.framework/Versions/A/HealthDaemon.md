## HealthDaemon

> `/System/Library/PrivateFrameworks/HealthDaemon.framework/Versions/A/HealthDaemon`

```diff

-7027.1.36.1.2
-  __TEXT.__text: 0xd0ab10
-  __TEXT.__objc_methlist: 0x49394
+7027.1.45.0.0
+  __TEXT.__text: 0xd0bea8
+  __TEXT.__objc_methlist: 0x4942c
   __TEXT.__const: 0x724a0
-  __TEXT.__cstring: 0x8cdc5
+  __TEXT.__cstring: 0x8d05a
   __TEXT.__swift5_typeref: 0x44af
   __TEXT.__swift5_capture: 0x1b48
   __TEXT.__constg_swiftt: 0x411c

   __TEXT.__swift5_assocty: 0xa48
   __TEXT.__swift5_proto: 0x564
   __TEXT.__swift5_types: 0x364
-  __TEXT.__oslogstring: 0x45d6f
+  __TEXT.__oslogstring: 0x45e9a
   __TEXT.__swift5_mpenum: 0x30
   __TEXT.__swift5_protos: 0xcc
   __TEXT.__swift5_types2: 0x4
   __TEXT.__swift_as_entry: 0x50
   __TEXT.__swift_as_ret: 0x30
   __TEXT.__swift_as_cont: 0x1c
-  __TEXT.__gcc_except_tab: 0x7a8a4
+  __TEXT.__gcc_except_tab: 0x7a7e8
   __TEXT.__ustring: 0x70
-  __TEXT.__unwind_info: 0x352c0
+  __TEXT.__unwind_info: 0x35310
   __TEXT.__eh_frame: 0x6908
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xc480
+  __DATA_CONST.__const: 0xc4c8
   __DATA_CONST.__objc_classlist: 0x2d10
-  __DATA_CONST.__objc_catlist: 0x510
+  __DATA_CONST.__objc_catlist: 0x518
   __DATA_CONST.__objc_protolist: 0xb40
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x18
-  __DATA_CONST.__objc_selrefs: 0x1bb60
+  __DATA_CONST.__objc_selrefs: 0x1bbc0
   __DATA_CONST.__objc_protorefs: 0x2f8
   __DATA_CONST.__objc_superrefs: 0x1ed0
-  __DATA_CONST.__objc_arraydata: 0x89f0
-  __DATA_CONST.__got: 0x5c58
-  __AUTH_CONST.__const: 0x3ba20
-  __AUTH_CONST.__cfstring: 0x412c0
-  __AUTH_CONST.__objc_const: 0x87340
+  __DATA_CONST.__objc_arraydata: 0x8a10
+  __DATA_CONST.__got: 0x5c60
+  __AUTH_CONST.__const: 0x3bb50
+  __AUTH_CONST.__cfstring: 0x41520
+  __AUTH_CONST.__objc_const: 0x87390
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_dictobj: 0x168
   __AUTH_CONST.__objc_intobj: 0x3e10
-  __AUTH_CONST.__objc_arrayobj: 0x21a8
+  __AUTH_CONST.__objc_arrayobj: 0x21c0
   __AUTH_CONST.__objc_doubleobj: 0x3c0
-  __AUTH_CONST.__auth_got: 0x3858
-  __AUTH.__objc_data: 0x9870
-  __AUTH.__data: 0x1dc0
-  __DATA.__objc_ivar: 0x47e0
-  __DATA.__data: 0x98d8
-  __DATA.__bss: 0x8270
-  __DATA.__common: 0x1d0
+  __AUTH_CONST.__auth_got: 0x3860
+  __AUTH.__objc_data: 0x9690
+  __AUTH.__data: 0x1ad0
+  __DATA.__objc_ivar: 0x47dc
+  __DATA.__data: 0x9748
+  __DATA.__bss: 0x7cf0
+  __DATA.__common: 0x1a8
   __DATA_DIRTY.__objc_ivar: 0xe54
-  __DATA_DIRTY.__objc_data: 0x14260
-  __DATA_DIRTY.__data: 0x36a8
-  __DATA_DIRTY.__bss: 0x17b0
-  __DATA_DIRTY.__common: 0x130
+  __DATA_DIRTY.__objc_data: 0x14440
+  __DATA_DIRTY.__data: 0x3b08
+  __DATA_DIRTY.__bss: 0x1d30
+  __DATA_DIRTY.__common: 0x158
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 51263
-  Symbols:   90732
-  CStrings:  14226
+  Functions: 51287
+  Symbols:   90770
+  CStrings:  14252
 
Symbols:
+ +[HDDatabaseTransaction(PendingCommitStorage) hk_pendingCommitStorageKeyForOwner:suffix:]
+ +[NSThread(HKPendingCommitStorage) hk_existingPendingCommitStorageForKey:]
+ -[HDCloudSyncCodableDeviceContext StringAsAppleIntelligenceEligibility:]
+ -[HDCloudSyncCodableDeviceContext appleIntelligenceEligibilityAsString:]
+ -[HDCloudSyncCodableDeviceContext appleIntelligenceEligibility]
+ -[HDCloudSyncCodableDeviceContext hasAppleIntelligenceEligibility]
+ -[HDCloudSyncCodableDeviceContext setAppleIntelligenceEligibility:]
+ -[HDCloudSyncCodableDeviceContext setHasAppleIntelligenceEligibility:]
+ -[HDCloudSyncDeviceContextRecord updateAppleIntelligenceEligibilityWithDataSource:]
+ -[HDDatabaseTransaction(PendingCommitStorage) hk_accessPendingCommitStorageForKey:createIfNeeded:accessBlock:commitBlock:]
+ -[HDDatabaseValueCache _accessStorageForTransaction:accessBlock:]
+ -[HDWorkoutBuilderServer _addWorkoutActivity:parentActivity:transaction:error:]
+ -[HDWorkoutBuilderServer _isActivityDateOverlapping:endDate:excludingActivityUUIDs:error:]
+ -[HDWorkoutBuilderServer _validateActivity:skipActivityTypeValidation:excludingActivityUUIDs:error:]
+ -[HDWorkoutBuilderServer _validateAndAddActivity:parentActivity:skipActivityTypeValidation:excludingActivityUUIDs:error:]
+ -[HDWorkoutBuilderServer _validateAndAddActivity:parentActivity:skipActivityTypeValidation:excludingActivityUUIDs:transaction:error:]
+ -[HDWorkoutBuilderStatisticsCalculators removeIntervalsWithUUIDs:]
+ -[HDWorkoutManager _queue_sessionServer:canInheritLowPowerModeFrom:]
+ OBJC_IVAR_$_HDCloudSyncCodableDeviceContext._appleIntelligenceEligibility
+ OBJC_IVAR_$_HDKeyValueDomainManager._pendingCommitStorageKey
+ _OBJC_CLASS_$_HKOSEligibilityDataSource
+ __122-[HDDatabaseTransaction(PendingCommitStorage) hk_accessPendingCommitStorageForKey:createIfNeeded:accessBlock:commitBlock:]_block_invoke
+ __65-[HDDatabaseValueCache _accessStorageForTransaction:accessBlock:]_block_invoke
+ __HDRenameAuthorizationDateColumns
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSThread_$_HKPendingCommitStorage
+ __OBJC_$_CATEGORY_NSThread_$_HKPendingCommitStorage
+ __OBJC_$_CLASS_METHODS_HDDatabaseTransaction(Logging|PendingCommitStorage)
+ __OBJC_$_INSTANCE_METHODS_HDDatabaseTransaction(Logging|PendingCommitStorage)
+ ___122-[HDDatabaseTransaction(PendingCommitStorage) hk_accessPendingCommitStorageForKey:createIfNeeded:accessBlock:commitBlock:]_block_invoke
+ ___61-[HDDatabaseValueCache _lock_storeObject:forKey:transaction:]_block_invoke
+ ___62-[HDDatabaseValueCache _lock_removeAllObjectsWithTransaction:]_block_invoke
+ ___65-[HDDatabaseValueCache _accessStorageForTransaction:accessBlock:]_block_invoke
+ ___73-[HDDatabaseValueCache fetchObjectForKey:transaction:error:faultHandler:]_block_invoke
+ ___78-[HDKeyValueDomainManager batchNotificationForDomain:category:forTransaction:]_block_invoke_2
+ ___79-[HDWorkoutBuilderServer _addWorkoutActivity:parentActivity:transaction:error:]_block_invoke
+ ___block_descriptor_32_e48_v16?0"HDDatabaseValueCacheTransactionStorage"8l
+ ___block_descriptor_40_e8_32bs_e8_16?08l
+ ___block_descriptor_40_e8_32s_e8_16?08l
+ ___block_descriptor_40_e8_32s_e8_v16?08l
+ ___block_descriptor_48_e8_32s40s_e48_v16?0"HDDatabaseValueCacheTransactionStorage"8l
+ ___block_descriptor_56_e8_32s40s_e5_8?0l
+ _objc_msgSend$_validateAndAddActivity:parentActivity:skipActivityTypeValidation:excludingActivityUUIDs:error:
+ _objc_msgSend$appleIntelligenceEligibility
+ _objc_msgSend$getAnswer:forDomain:error:
+ _objc_msgSend$hasParentActivityUUID
+ _objc_msgSend$hk_accessPendingCommitStorageForKey:createIfNeeded:accessBlock:commitBlock:
+ _objc_msgSend$hk_existingPendingCommitStorageForKey:
+ _objc_msgSend$hk_pendingCommitStorageKeyForOwner:suffix:
+ _objc_msgSend$setAppleIntelligenceEligibility:
+ _objc_msgSend$setHasAppleIntelligenceEligibility:
+ _objc_msgSend$updateAppleIntelligenceEligibility:
+ _objc_msgSend$updateAppleIntelligenceEligibilityWithDataSource:
- -[HDDatabaseValueCache _storageForTransaction:createIfNecessary:]
- -[HDWorkoutBuilderServer _isActivityDateOverlapping:endDate:error:]
- -[HDWorkoutBuilderServer _validateAndAddActivity:parentActivity:skipActivityTypeValidation:error:]
- OBJC_IVAR_$_HDKeyValueDomainManager._hasAddedTransactionOnCommitBlock
- OBJC_IVAR_$_HDKeyValueDomainManager._pendingNotificationKeys
- OBJC_IVAR_$_HDKeyValueDomainManager._pendingNotificationLock
- __65-[HDDatabaseValueCache _storageForTransaction:createIfNecessary:]_block_invoke
- __OBJC_$_CLASS_METHODS_HDDatabaseTransaction(Logging)
- __OBJC_$_INSTANCE_METHODS_HDDatabaseTransaction
- ___65-[HDDatabaseValueCache _storageForTransaction:createIfNecessary:]_block_invoke
- _objc_msgSend$_validateAndAddActivity:parentActivity:skipActivityTypeValidation:error:
- _objc_msgSend$activityNodeTreeWrapperForRootActivity:ownerID:transaction:error:
- _objc_msgSend$activityNodeWrapperFrom:
- _objc_msgSend$setFullNodeWrapper:
CStrings:
+ "%@.%@.%p"
+ "%{public}@: Failed to read Apple Intelligence eligibility: %{public}@"
+ "%{public}@: Restore sync is disabled: supportsRestoreSync=%{BOOL}d, cloudSyncRestoreTask=%{BOOL}d, internalInstall=%{BOOL}d"
+ "@16@?0@8"
+ "ALTER TABLE authorization RENAME COLUMN a_e_d TO availability_end_date"
+ "ALTER TABLE authorization RENAME COLUMN a_s_d TO availability_start_date"
+ "ALTER TABLE authorization RENAME COLUMN e_d TO expiry_date"
+ "ALTER TABLE authorization RENAME COLUMN r_d TO reminder_date"
+ "Eligible"
+ "HDDatabaseTransaction+PendingCommitStorage.m"
+ "HDKeyValueDomainManager.m"
+ "Maybe"
+ "NotEligible"
+ "NotYetAvailable"
+ "Pending-commit block for %{public}@ threw: %{public}@"
+ "Workout activity %{public}@ names parent %{public}@, which is not part of this workout; attaching it to the primary activity rather than dropping it"
+ "[CyclingPowerZones] No zones configured, returning nil configuration"
+ "accessBlock != nil"
+ "appleIntelligenceEligibility"
+ "availability_end_date"
+ "availability_start_date"
+ "commitBlock != nil"
+ "createBlock != nil"
+ "expiry_date"
+ "owner != nil"
+ "pendingKeys"
+ "reminder_date"
+ "storage != nil"
+ "suffix != nil"
+ "transactionStorage"
+ "v16@?0@\"HDDatabaseValueCacheTransactionStorage\"8"
+ "v16@?0@8"
+ "\x85"
- "%@.%p"
- "%{public}@: Skipping restore-sync database assertion: cloudSyncRestoreTask feature flag is off"
- "%{public}@: Skipping restore-sync database assertion: this device does not restore"
- "a_e_d"
- "a_s_d"
- "e_d"
- "r_d"
```
