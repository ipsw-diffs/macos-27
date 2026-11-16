## HealthDaemon

> `/System/Library/PrivateFrameworks/HealthDaemon.framework/Versions/A/HealthDaemon`

```diff

-7027.2.12.0.0
-  __TEXT.__text: 0xd35504
-  __TEXT.__objc_methlist: 0x49b64
-  __TEXT.__const: 0x72700
-  __TEXT.__cstring: 0x8de45
+7027.2.19.0.0
+  __TEXT.__text: 0xd38384
+  __TEXT.__objc_methlist: 0x49c14
+  __TEXT.__const: 0x72720
+  __TEXT.__cstring: 0x8df72
   __TEXT.__swift5_typeref: 0x454d
   __TEXT.__swift5_capture: 0x1d14
   __TEXT.__constg_swiftt: 0x41bc

   __TEXT.__swift5_assocty: 0xa48
   __TEXT.__swift5_proto: 0x574
   __TEXT.__swift5_types: 0x370
-  __TEXT.__oslogstring: 0x46c89
+  __TEXT.__oslogstring: 0x46daf
   __TEXT.__swift5_mpenum: 0x30
   __TEXT.__swift5_protos: 0xcc
   __TEXT.__swift5_types2: 0x4
   __TEXT.__swift_as_entry: 0x50
   __TEXT.__swift_as_ret: 0x30
   __TEXT.__swift_as_cont: 0x1c
-  __TEXT.__gcc_except_tab: 0x7b1f8
+  __TEXT.__gcc_except_tab: 0x7b1c8
   __TEXT.__ustring: 0xb6
-  __TEXT.__unwind_info: 0x35a88
+  __TEXT.__unwind_info: 0x35ae0
   __TEXT.__eh_frame: 0x6e38
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xc520
+  __DATA_CONST.__const: 0xc6c0
   __DATA_CONST.__objc_classlist: 0x2d30
   __DATA_CONST.__objc_catlist: 0x518
   __DATA_CONST.__objc_protolist: 0xb48
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x18
-  __DATA_CONST.__objc_selrefs: 0x1bf58
+  __DATA_CONST.__objc_selrefs: 0x1bfc8
   __DATA_CONST.__objc_protorefs: 0x300
   __DATA_CONST.__objc_superrefs: 0x1ef8
-  __DATA_CONST.__objc_arraydata: 0x89c0
+  __DATA_CONST.__objc_arraydata: 0x88c8
   __DATA_CONST.__got: 0x5dc8
-  __AUTH_CONST.__const: 0x3c3e0
-  __AUTH_CONST.__cfstring: 0x41d00
-  __AUTH_CONST.__objc_const: 0x87ff0
+  __AUTH_CONST.__const: 0x3c4e0
+  __AUTH_CONST.__cfstring: 0x41d60
+  __AUTH_CONST.__objc_const: 0x880c0
   __AUTH_CONST.__weak_auth_got: 0x30
-  __AUTH_CONST.__objc_dictobj: 0x168
+  __AUTH_CONST.__objc_dictobj: 0x140
   __AUTH_CONST.__objc_intobj: 0x3d80
-  __AUTH_CONST.__objc_arrayobj: 0x2178
+  __AUTH_CONST.__objc_arrayobj: 0x2190
   __AUTH_CONST.__objc_doubleobj: 0x3c0
   __AUTH_CONST.__auth_got: 0x3b68
   __AUTH.__objc_data: 0x9830
   __AUTH.__data: 0x1bf0
-  __DATA.__objc_ivar: 0x48b4
+  __DATA.__objc_ivar: 0x48c8
   __DATA.__data: 0x98d8
   __DATA.__bss: 0x7ef0
   __DATA.__common: 0x1a8
   __DATA_DIRTY.__objc_ivar: 0xe60
   __DATA_DIRTY.__objc_data: 0x14498
   __DATA_DIRTY.__data: 0x3af0
-  __DATA_DIRTY.__bss: 0x1d60
+  __DATA_DIRTY.__bss: 0x1d78
   __DATA_DIRTY.__common: 0x158
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 51790
-  Symbols:   90452
-  CStrings:  14396
+  Functions: 51816
+  Symbols:   90496
+  CStrings:  14405
 
Symbols:
+ +[HDAssociationEntity _insertEntries:healthDatabase:sourceManager:lastInsertedEntityIDs:error:]
+ +[HDAssociationEntity _syncIdentitiesForCodableSyncIdentities:syncIdentityManager:healthDatabase:error:]
+ +[HDMedicalUserDomainConceptMappingEntity enumerateSamplesMappedToUserDomainConceptID:excludingRecordID:transaction:error:handler:]
+ +[HDUserCharacteristicsManager correctedDateOfBirthForStoredValue:history:]
+ -[HDAppSubscriptionManager setUnitTesting_honorsLaunchSchedule:]
+ -[HDAppSubscriptionManager unitTesting_honorsLaunchSchedule]
+ -[HDDaemonSyncEngine _applySyncChange:entity:store:outerAccessibilityError:error:]
+ -[HDDatabase setUnitTest_willPerformSchemaMigrationHandler:]
+ -[HDDatabase unitTest_clearMigratedSchemas]
+ -[HDDatabase unitTest_hasMigratedSchemaForDatabaseType:]
+ -[HDDatabase unitTest_willPerformSchemaMigrationHandler]
+ -[HDDemoDataHeartSampleGenerator _electrocardiogramClassificationForDemoPerson:]
+ -[HDDemoDataHeartSampleGenerator electrocardiogramForDemoPerson:atTime:sampleDate:]
+ -[HDDemoDataPerson excludesAtrialFibrillationElectrocardiograms]
+ -[HDDemoDataPerson setExcludesAtrialFibrillationElectrocardiograms:]
+ -[HDUserCharacteristicsManager _correctedDateOfBirthForStoredValue:]
+ _DateOfBirthDayStart
+ _DateOfBirthDaysBetween
+ _DateOfBirthShiftExposureInterval
+ _HDQueryUsageQueryTypeCodeForPublicName
+ _HDQueryUsageQueryTypes
+ _HDQueryUsageReportedMilliseconds
+ _HDQueryUsageRoundedToTwoSignificantFigures
+ _OBJC_IVAR_$_HDAppSubscriptionManager._unitTesting_honorsLaunchSchedule
+ _OBJC_IVAR_$_HDDatabase._hasMigratedProtectedSchema
+ _OBJC_IVAR_$_HDDatabase._hasMigratedUnprotectedSchema
+ _OBJC_IVAR_$_HDDatabase._unitTest_willPerformSchemaMigrationHandler
+ _OBJC_IVAR_$_HDDemoDataPerson._excludesAtrialFibrillationElectrocardiograms
+ __HDResetReceivedSyncAnchorsForMovementEvaluations
+ __OBJC_$_CLASS_METHODS_HDUserCharacteristicsManager
+ ___104+[HDAssociationEntity _syncIdentitiesForCodableSyncIdentities:syncIdentityManager:healthDatabase:error:]_block_invoke
+ ___104+[HDAssociationEntity _syncIdentitiesForCodableSyncIdentities:syncIdentityManager:healthDatabase:error:]_block_invoke_2
+ ___131+[HDMedicalUserDomainConceptMappingEntity enumerateSamplesMappedToUserDomainConceptID:excludingRecordID:transaction:error:handler:]_block_invoke
+ ___131+[HDMedicalUserDomainConceptMappingEntity enumerateSamplesMappedToUserDomainConceptID:excludingRecordID:transaction:error:handler:]_block_invoke_2
+ ___131+[HDMedicalUserDomainConceptMappingEntity enumerateSamplesMappedToUserDomainConceptID:excludingRecordID:transaction:error:handler:]_block_invoke_3
+ ___144+[HDMedicalUserDomainConceptGenerator reconcileCategoryTypesForUserDomainConceptsAfterDeletingRecordWithPersistentID:profile:transaction:error:]_block_invoke
+ ___75+[HDUserCharacteristicsManager correctedDateOfBirthForStoredValue:history:]_block_invoke
+ ___95+[HDAssociationEntity _insertEntries:healthDatabase:sourceManager:lastInsertedEntityIDs:error:]_block_invoke
+ ___95+[HDAssociationEntity _insertEntries:healthDatabase:sourceManager:lastInsertedEntityIDs:error:]_block_invoke_2
+ ___DateOfBirthShiftExposureInterval_block_invoke
+ ___HDQueryUsageBuildQueryTypeMaps_block_invoke
+ ___block_descriptor_32_e37_q24?0"HKBirthDate"8"HKBirthDate"16l
+ ___block_descriptor_40_e8_32s_e31_q24?0"NSNumber"8"NSNumber"16l
+ ___block_descriptor_48_e8_32s40s_e15_v32?08Q16^B24l
+ ___block_descriptor_48_e8_32s_e21_v24?0q8"NSString"16l
+ ___block_descriptor_56_e8_32s40s_e25_v32?0"NSNumber"8Q16^B24l
+ ___block_descriptor_72_e8_32s40s48s56r_e9_B16?0^8l
+ _enumerateSamplesMappedToUserDomainConceptID:excludingRecordID:transaction:error:handler:.lookupKey
+ _objc_msgSend$_correctedDateOfBirthForStoredValue:
+ _objc_msgSend$_electrocardiogramClassificationForDemoPerson:
+ _objc_msgSend$_insertEntries:healthDatabase:sourceManager:lastInsertedEntityIDs:error:
+ _objc_msgSend$_syncIdentitiesForCodableSyncIdentities:syncIdentityManager:healthDatabase:error:
+ _objc_msgSend$cachedConnectionCount
+ _objc_msgSend$correctedDateOfBirthForStoredValue:history:
+ _objc_msgSend$electrocardiogramForDemoPerson:atTime:sampleDate:
+ _objc_msgSend$enumerateSamplesMappedToUserDomainConceptID:excludingRecordID:transaction:error:handler:
+ _objc_msgSend$excludesAtrialFibrillationElectrocardiograms
+ _objc_msgSend$setExcludesAtrialFibrillationElectrocardiograms:
- +[HDMedicalUserDomainConceptMappingEntity remainingSampleIDsAndDataTypesForUserDomainConceptID:excludingRecordID:transaction:error:]
- -[HDDaemonSyncEngine _applySyncChange:entity:store:error:]
- GCC_except_table171
- ___121+[HDAssociationEntity _insertCodableObjectAssociations:syncStore:sourceManager:syncIdentityManager:healthDatabase:error:]_block_invoke_2
- ___132+[HDMedicalUserDomainConceptMappingEntity remainingSampleIDsAndDataTypesForUserDomainConceptID:excludingRecordID:transaction:error:]_block_invoke
- ___132+[HDMedicalUserDomainConceptMappingEntity remainingSampleIDsAndDataTypesForUserDomainConceptID:excludingRecordID:transaction:error:]_block_invoke_2
- ___132+[HDMedicalUserDomainConceptMappingEntity remainingSampleIDsAndDataTypesForUserDomainConceptID:excludingRecordID:transaction:error:]_block_invoke_3
- ___85-[HDAssociationManager insertCodableTypedObjectAssociations:syncStore:profile:error:]_block_invoke_2
- ___HDQueryUsageServerToPublicNameMap_block_invoke
- ___block_descriptor_40_e8_32s_e31_q24?0"NSString"8"NSString"16l
- _objc_msgSend$associateSampleUUIDs:withSampleUUID:type:behavior:destinationSubObjectReference:lastInsertedEntityID:healthDatabase:sourceManager:provenance:syncIdentity:creationDate:error:
- _objc_msgSend$cacheSize
- _objc_msgSend$remainingSampleIDsAndDataTypesForUserDomainConceptID:excludingRecordID:transaction:error:
- _remainingSampleIDsAndDataTypesForUserDomainConceptID:excludingRecordID:transaction:error:.lookupKey
CStrings:
+ "%{public}@ Failed to reconcile medical user domain concept category types for record %{public}lld: %{public}@"
+ "Applying %lu objects for %{public}@ without the outer transaction: %{public}@"
+ "Failed to apply the PPT database time offset: %{public}@"
+ "Failed to insert association"
+ "Failed to read date of birth history: %{public}@"
+ "Failed to resolve sync identity"
+ "INSERT OR IGNORE INTO associations (ROWID, parent_id, child_id, sync_provenance, sync_identity) SELECT ROWID, correlation, object, provenance, ? FROM correlations ORDER BY ROWID;"
+ "INSERT OR IGNORE INTO pending_associations_new (ROWID, parent_uuid, child_uuid, sync_provenance, sync_identity) SELECT ROWID, parent_uuid, child_uuid, provenance, ? FROM pending_associations ORDER BY ROWID;"
+ "SELECT DISTINCT s.data_type, d.%@ FROM medical_user_domain_concept_mappings m JOIN samples s ON s.data_id = m.data_id LEFT JOIN %@ d ON d.data_id = m.data_id WHERE m.udc_id = ? AND m.data_id != ?"
+ "UPDATE sync_anchors SET received=0, validated=0 WHERE schema = 'main' AND type IN (83, 84);"
+ "q24@?0@\"HKBirthDate\"8@\"HKBirthDate\"16"
+ "q24@?0@\"NSNumber\"8@\"NSNumber\"16"
+ "v32@?0@8Q16^B24"
- "INSERT INTO associations (ROWID, parent_id, child_id, sync_provenance, sync_identity) SELECT ROWID, correlation, object, provenance, ? FROM correlations;"
- "INSERT INTO pending_associations_new (ROWID, parent_uuid, child_uuid, sync_provenance, sync_identity) SELECT ROWID, parent_uuid, child_uuid, provenance, ? FROM pending_associations;"
- "SELECT m.data_id, s.data_type FROM medical_user_domain_concept_mappings m JOIN samples s ON s.data_id = m.data_id WHERE m.udc_id = ? AND m.data_id != ?"
- "q24@?0@\"NSString\"8@\"NSString\"16"
```
