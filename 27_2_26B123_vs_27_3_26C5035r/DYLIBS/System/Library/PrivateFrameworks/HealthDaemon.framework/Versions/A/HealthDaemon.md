## HealthDaemon

> `/System/Library/PrivateFrameworks/HealthDaemon.framework/Versions/A/HealthDaemon`

```diff

-7027.1.56.1.1
-  __TEXT.__text: 0xd0ff84
-  __TEXT.__objc_methlist: 0x4960c
-  __TEXT.__const: 0x724d0
-  __TEXT.__cstring: 0x8d370
-  __TEXT.__swift5_typeref: 0x44af
-  __TEXT.__swift5_capture: 0x1b48
-  __TEXT.__constg_swiftt: 0x411c
+7027.2.12.0.0
+  __TEXT.__text: 0xd35504
+  __TEXT.__objc_methlist: 0x49b64
+  __TEXT.__const: 0x72700
+  __TEXT.__cstring: 0x8de45
+  __TEXT.__swift5_typeref: 0x454d
+  __TEXT.__swift5_capture: 0x1d14
+  __TEXT.__constg_swiftt: 0x41bc
   __TEXT.__swift5_builtin: 0x154
-  __TEXT.__swift5_reflstr: 0x2cf8
-  __TEXT.__swift5_fieldmd: 0x2fc0
+  __TEXT.__swift5_reflstr: 0x2d18
+  __TEXT.__swift5_fieldmd: 0x3038
   __TEXT.__swift5_assocty: 0xa48
-  __TEXT.__swift5_proto: 0x564
-  __TEXT.__swift5_types: 0x364
-  __TEXT.__oslogstring: 0x45e52
+  __TEXT.__swift5_proto: 0x574
+  __TEXT.__swift5_types: 0x370
+  __TEXT.__oslogstring: 0x46c89
   __TEXT.__swift5_mpenum: 0x30
   __TEXT.__swift5_protos: 0xcc
   __TEXT.__swift5_types2: 0x4
   __TEXT.__swift_as_entry: 0x50
   __TEXT.__swift_as_ret: 0x30
   __TEXT.__swift_as_cont: 0x1c
-  __TEXT.__gcc_except_tab: 0x7a81c
+  __TEXT.__gcc_except_tab: 0x7b1f8
   __TEXT.__ustring: 0xb6
-  __TEXT.__unwind_info: 0x35470
-  __TEXT.__eh_frame: 0x6978
+  __TEXT.__unwind_info: 0x35a88
+  __TEXT.__eh_frame: 0x6e38
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xc4c8
-  __DATA_CONST.__objc_classlist: 0x2d28
+  __DATA_CONST.__const: 0xc520
+  __DATA_CONST.__objc_classlist: 0x2d30
   __DATA_CONST.__objc_catlist: 0x518
   __DATA_CONST.__objc_protolist: 0xb48
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x18
-  __DATA_CONST.__objc_selrefs: 0x1bc80
+  __DATA_CONST.__objc_selrefs: 0x1bf58
   __DATA_CONST.__objc_protorefs: 0x300
-  __DATA_CONST.__objc_superrefs: 0x1ec8
-  __DATA_CONST.__objc_arraydata: 0x8a18
-  __DATA_CONST.__got: 0x5c88
-  __AUTH_CONST.__const: 0x3bbe0
-  __AUTH_CONST.__cfstring: 0x41780
-  __AUTH_CONST.__objc_const: 0x87ad0
+  __DATA_CONST.__objc_superrefs: 0x1ef8
+  __DATA_CONST.__objc_arraydata: 0x89c0
+  __DATA_CONST.__got: 0x5dc8
+  __AUTH_CONST.__const: 0x3c3e0
+  __AUTH_CONST.__cfstring: 0x41d00
+  __AUTH_CONST.__objc_const: 0x87ff0
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_dictobj: 0x168
-  __AUTH_CONST.__objc_intobj: 0x3e10
-  __AUTH_CONST.__objc_arrayobj: 0x21d8
+  __AUTH_CONST.__objc_intobj: 0x3d80
+  __AUTH_CONST.__objc_arrayobj: 0x2178
   __AUTH_CONST.__objc_doubleobj: 0x3c0
-  __AUTH_CONST.__auth_got: 0x3898
-  __AUTH.__objc_data: 0x97e0
-  __AUTH.__data: 0x1b50
-  __DATA.__objc_ivar: 0x4850
-  __DATA.__data: 0x9810
-  __DATA.__bss: 0x7ce0
+  __AUTH_CONST.__auth_got: 0x3b68
+  __AUTH.__objc_data: 0x9830
+  __AUTH.__data: 0x1bf0
+  __DATA.__objc_ivar: 0x48b4
+  __DATA.__data: 0x98d8
+  __DATA.__bss: 0x7ef0
   __DATA.__common: 0x1a8
-  __DATA_DIRTY.__objc_ivar: 0xe54
-  __DATA_DIRTY.__objc_data: 0x14448
-  __DATA_DIRTY.__data: 0x3ae0
-  __DATA_DIRTY.__bss: 0x1d30
+  __DATA_DIRTY.__objc_ivar: 0xe60
+  __DATA_DIRTY.__objc_data: 0x14498
+  __DATA_DIRTY.__data: 0x3af0
+  __DATA_DIRTY.__bss: 0x1d60
   __DATA_DIRTY.__common: 0x158
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 51395
-  Symbols:   90138
-  CStrings:  14283
+  Functions: 51790
+  Symbols:   90452
+  CStrings:  14396
 
Symbols:
+ +[HDActivityCacheEntity applyTimeOffset:dayCount:database:error:]
+ +[HDActivityCacheEntity columnNamesForTimeOffset]
+ +[HDAuthorizationBackupSyncEntity _isRestoreCompleteWithHealthDatabase:]
+ +[HDAuthorizationBackupSyncEntity _lock_isRotationPending]
+ +[HDAuthorizationBackupSyncEntity _rotationCountForKey:]
+ +[HDAuthorizationBackupSyncEntity _setRestoredAuthorizationBackupRestoreIdentifier:]
+ +[HDAuthorizationBackupSyncEntity _setRotationCount:forKey:]
+ +[HDAuthorizationBackupSyncEntity acceptedAuthorizationBackupRestoreIdentifiersWithHealthDatabase:]
+ +[HDAuthorizationBackupSyncEntity clearRestoredAuthorizationBackupRestoreIdentifier]
+ +[HDAuthorizationBackupSyncEntity didCompleteCloudSyncPushWithHealthDatabase:]
+ +[HDAuthorizationBackupSyncEntity isAuthorizationBackupRestoreIdentifierRotationPending]
+ +[HDAuthorizationBackupSyncEntity requestAuthorizationBackupRestoreIdentifierRotation]
+ +[HDAuthorizationBackupSyncEntity restoredAuthorizationBackupRestoreIdentifier]
+ +[HDAuthorizationBackupSyncEntity unitTesting_resetRotationState]
+ +[HDAuthorizationBackupSyncEntity willBeginCloudSyncPush]
+ +[HDAuthorizationEntity _accumulateDecisionChangeForSourceIdentifier:dataTypeCode:authorizationStatus:authorizationMode:modeInfo:database:decisionChanged:error:]
+ +[HDCachedQueryMetadataEntity applyTimeOffset:dayCount:database:error:]
+ +[HDClinicalRecordEntity deleteRecordsDerivedFromMHRecordWithPersistentID:profile:transaction:error:]
+ +[HDCloudSyncChangeRecord recordID:canBeInSequence:]
+ +[HDHealthEntity(TimeShift) applyTimeOffset:dayCount:database:error:]
+ +[HDLocationSeriesDataEntity applyTimeOffset:database:error:]
+ +[HDLocationSeriesSampleEntity applyTimeOffset:dayCount:database:error:]
+ +[HDNotificationInstructionEntity columnNamesForTimeOffset]
+ +[HDQuantitySampleSeriesEntity applyTimeOffset:dayCount:database:error:]
+ +[HDQuantitySampleStatisticsEntity columnNamesForTimeOffset]
+ +[HDQuantitySeriesDataEntity applyTimeOffset:database:error:]
+ +[HDRaceRouteClusterEntity applyTimeOffset:dayCount:database:error:]
+ +[HDRaceRouteClusterEntity columnNamesForTimeOffset]
+ +[HDRaceRouteWorkoutEntity columnNamesForTimeOffset]
+ +[HDSampleAggregateCacheEntity applyTimeOffset:dayCount:database:error:]
+ +[HDSampleAggregateCacheEntity enumerateCachedDataAndLastVisitedTimesForQueryIdentifier:sourceEntity:profile:startIndex:endIndex:error:enumerationHandler:]
+ +[HDSleepDaySummaryCacheEntity applyTimeOffset:dayCount:database:error:]
+ +[HDTrainingLoadStatisticsCacheEntity applyTimeOffset:dayCount:database:error:]
+ +[HDWorkoutActivityEntity columnNamesForTimeOffset]
+ +[HDWorkoutBuilderAssociatedObjectEntity columnNamesForTimeOffset]
+ +[HDWorkoutBuilderEntity applyTimeOffset:dayCount:database:error:]
+ +[HDWorkoutBuilderEntity columnNamesForTimeOffset]
+ +[HDWorkoutClusterEntity columnNamesForTimeOffset]
+ +[HDWorkoutCondenser _addCondensedWorkoutsVerifiedBeforeDate:toBatch:maximumCount:transaction:error:]
+ +[HDWorkoutCondenser _remainingCapacityOfBatch:limit:]
+ +[HDWorkoutCondenser _uncondensedWorkoutPredicateWithProfile:error:]
+ +[HDWorkoutEntity _insertSubActivitiesForWorkout:ownerID:primaryEntity:database:error:]
+ +[HDWorkoutEntity enumerateAssociationsOfWorkoutsWithCondenserVersion:afterRowID:throughRowID:transaction:error:handler:]
+ +[HDWorkoutEventEntity columnNamesForTimeOffset]
+ +[HDWorkoutSessionEntity applyTimeOffset:dayCount:database:error:]
+ +[HDWorkoutSessionEntity columnNamesForTimeOffset]
+ +[HKSource(HealthDaemon) hd_researchEntitlementStateForSource:]
+ -[HDCloudSyncCachedZone _recordsForClass:epoch:recordIDFilter:error:enumerationHandler:]
+ -[HDCloudSyncCachedZone changeRecordsInSequence:error:enumerationHandler:]
+ -[HDCloudSyncCachedZone changeRecordsInSequences:error:enumerationHandler:]
+ -[HDCodableCodedQuantity hasUnitConceptIdentifier]
+ -[HDCodableCodedQuantity setHasUnitConceptIdentifier:]
+ -[HDCodableCodedQuantity setUnitConceptIdentifier:]
+ -[HDCodableCodedQuantity unitConceptIdentifier]
+ -[HDDataEntityDeletionContext _recordDeletedObjectParents:]
+ -[HDDataEntityDeletionContext _recordDeletedObjectUUID:objectType:]
+ -[HDDatabase inactivityFlushMode]
+ -[HDDatabase offsetDayCount]
+ -[HDDatabase setInactivityFlushMode:]
+ -[HDDatabase setOffsetDayCount:]
+ -[HDDemoDataAudioExposureSampleGenerator _randomlySelectedGaussianWithMean:deviation:]
+ -[HDDemoDataBodySampleGenerator generateFirstRunObjectsForDemoPerson:firstDate:objectCollection:]
+ -[HDDemoDataHeartSampleGenerator _meanVO2MaxValueForDemoPerson:date:]
+ -[HDDemoDataPerson generatesContinuousHeartRate]
+ -[HDDemoDataPerson heartRateVariabilitySDNNSampleFrequencyStdDev]
+ -[HDDemoDataPerson heartRateVariabilitySDNNSampleFrequency]
+ -[HDDemoDataPerson heartRateVariabilitySDNN]
+ -[HDDemoDataPerson rerollRestingHeartRateWithUnitRandom:]
+ -[HDDemoDataPerson restingHeartRateDailyMaximum]
+ -[HDDemoDataPerson restingHeartRateDailyMinimum]
+ -[HDDemoDataPerson setGeneratesContinuousHeartRate:]
+ -[HDDemoDataPerson setHeartRateVariabilitySDNN:]
+ -[HDDemoDataPerson setHeartRateVariabilitySDNNSampleFrequency:]
+ -[HDDemoDataPerson setHeartRateVariabilitySDNNSampleFrequencyStdDev:]
+ -[HDDemoDataPerson setRestingHeartRateDailyMaximum:]
+ -[HDDemoDataPerson setRestingHeartRateDailyMinimum:]
+ -[HDDemoDataPerson setVo2MaxMean:]
+ -[HDDemoDataPerson vo2MaxMean]
+ -[HDDemoDataReproductiveHealthSampleGenerator _computeFirstRunCycleFactorSamplesForDemoPerson:]
+ -[HDDemoDataReproductiveHealthSampleGenerator _dayOfCycleForDemoPerson:sampleDate:anchorDate:]
+ -[HDDemoDataReproductiveHealthSampleGenerator _menstrualCycleAnchorDate]
+ -[HDDemoDataReproductiveHealthSampleGenerator headacheSymptomForDemoPerson:withSampleDate:anchorDate:]
+ -[HDDemoDataReproductiveHealthSampleGenerator menstrualCrampSymptomForDemoPerson:withSampleDate:anchorDate:]
+ -[HDDemoDataReproductiveHealthSampleGenerator menstrualFlowForDemoPerson:withSampleDate:anchorDate:]
+ -[HDDemoDataReproductiveHealthSampleGenerator ovulationTestResultForDemoPerson:withSampleDate:anchorDate:]
+ -[HDDemoDataVitalsSampleGenerator cooldownHeartRateForDemoPerson:maxHeartRate:percentCooled:]
+ -[HDDemoDataVitalsSampleGenerator motionHeartRateForDemoPerson:isMoving:secondsSinceMotionEnded:noise:]
+ -[HDDemoDataVitalsSampleGenerator workoutHeartRateForDemoPerson:maxHeartRate:noise:]
+ -[HDDeviceContext appleIntelligenceEligibility]
+ -[HDDeviceContext initWithType:productTypeName:currentOSName:currentOSVersion:modificationDate:syncIdentity:appleIntelligenceEligibility:]
+ -[HDMaintenanceOperation setYieldsToForegroundClients:]
+ -[HDMaintenanceOperation yieldsToForegroundClients]
+ -[HDProfileManager _lock_finishLoadingSecondaryProfiles]
+ -[HDProfileManager executeBlockAfterSecondaryProfilesLoad:queue:]
+ -[HDSQLiteDatabase(TimeShift) hd_applyTimeOffset:toUniqueColumn:inTable:error:]
+ -[HDWorkoutBuilderEntity addWorkoutActivitySets:workoutSetWrapper:transaction:error:]
+ -[HDWorkoutBuilderServer _canEndActivity:endDate:error:]
+ -[HDWorkoutBuilderServer remote_addWorkoutActivityUnitWithWrapper:completion:]
+ -[HDWorkoutBuilderServer remote_discardCurrentActivityUnitWithCompletion:]
+ -[HDWorkoutBuilderServer remote_endCurrentActivityUnitWithDate:completion:]
+ -[HDWorkoutBuilderServer remote_replaceWorkoutActivityUnitOld:newUnit:completion:]
+ -[HDWorkoutBuilderServer remote_updateActivityWithUUID:workoutSetWrapper:completion:]
+ -[HDWorkoutBuilderServer remote_updateCurrentActivityAddingSetWrapper:completion:]
+ -[HDWorkoutCondenser _recondensationKeyValueDomain]
+ -[HDWorkoutCondenser unitTest_setReverifyBeforeDate:error:]
+ -[_HDWorkoutCondenserBatch .cxx_destruct]
+ -[_HDWorkoutCondenserBatch init]
+ _DateOfBirthComponentsHaveSameDay
+ _HDClinicalRecordEntityPropertyOriginalMHRecordROWID
+ _HDConcurrentDatabaseReaderLimit
+ _HDDemoData_hrvSDNN
+ _HDDemoData_hrvSDNNDayLevel
+ _HDPPTDatabaseSetUpAllowNonInternalInstallDefaultsKey
+ _HDPPTDatabaseSetUpDayCountBetweenDays
+ _HDPPTDatabaseSetUpDayStartDate
+ _HDPPTDatabaseSetUpDayString
+ _HDPPTDatabaseSetUpOffsetTimesAppliedDefaultsKey
+ _HDPPTDatabaseSetUpOffsetTimesEnabledDefaultsKey
+ _HDPPTDatabaseSetUpOffsetToDayDefaultsKey
+ _HDPPTDatabaseSetUpSeedLatestDayDefaultsKey
+ _HDWorkoutEntityPredicateForWorkoutCondenserDateBefore
+ _HKCurrentAppleIntelligenceEligibility
+ _HKLogActivityCacheCategory
+ _HKQuantityTypeIdentifierHeartRateVariabilitySDNN
+ _HKQuantityTypeIdentifierHipCircumference
+ _HKQuantityTypeIdentifierWaistCircumference
+ _OBJC_CLASS_$_HKWorkoutStrengthTrainingSetWrapper
+ _OBJC_CLASS_$__HDWorkoutCondenserBatch
+ _OBJC_IVAR_$_HDCodableCodedQuantity._has
+ _OBJC_IVAR_$_HDCodableCodedQuantity._unitConceptIdentifier
+ _OBJC_IVAR_$_HDDatabase._inactivityFlushMode
+ _OBJC_IVAR_$_HDDatabase._offsetDayCount
+ _OBJC_IVAR_$_HDDemoDataPerson._generatesContinuousHeartRate
+ _OBJC_IVAR_$_HDDemoDataPerson._heartRateVariabilitySDNN
+ _OBJC_IVAR_$_HDDemoDataPerson._heartRateVariabilitySDNNSampleFrequency
+ _OBJC_IVAR_$_HDDemoDataPerson._heartRateVariabilitySDNNSampleFrequencyStdDev
+ _OBJC_IVAR_$_HDDemoDataPerson._restingHeartRateDailyMaximum
+ _OBJC_IVAR_$_HDDemoDataPerson._restingHeartRateDailyMinimum
+ _OBJC_IVAR_$_HDDemoDataPerson._vo2MaxMean
+ _OBJC_IVAR_$_HDDeviceContext._appleIntelligenceEligibility
+ _OBJC_IVAR_$_HDMaintenanceOperation._yieldsToForegroundClients
+ _OBJC_IVAR_$_HDProfileManager._lock_blocksAfterSecondaryProfilesLoad
+ _OBJC_IVAR_$_HDProfileManager._lock_secondaryProfilesLoaded
+ _OBJC_IVAR_$__HDWorkoutCondenserBatch._changedWorkoutFirstAssociationRowIDs
+ _OBJC_IVAR_$__HDWorkoutCondenserBatch._configuration
+ _OBJC_IVAR_$__HDWorkoutCondenserBatch._previousVerifiedAssociationRowID
+ _OBJC_IVAR_$__HDWorkoutCondenserBatch._reverifyBeforeTime
+ _OBJC_IVAR_$__HDWorkoutCondenserBatch._scanStopAssociationRowID
+ _OBJC_IVAR_$__HDWorkoutCondenserBatch._scannedAssociations
+ _OBJC_IVAR_$__HDWorkoutCondenserBatch._stateWasReset
+ _OBJC_IVAR_$__HDWorkoutCondenserBatch._throughAssociationRowID
+ _OBJC_IVAR_$__HDWorkoutCondenserBatch._uncondensedCount
+ _OBJC_IVAR_$__HDWorkoutCondenserBatch._workoutEntities
+ _OBJC_METACLASS_$__HDWorkoutCondenserBatch
+ __HDAddAppleIntelligenceEligibilityColumnToDeviceContextTable
+ __HDAddClinicalRecordMHRecordOrigin
+ __HDAppendUUIDsByType
+ __HDImmutableUUIDsByType
+ __HKPrivateMetadataKeyOriginalMHRecordUUID
+ __HKPrivateMetadataKeyWorkoutActivitySet
+ __OBJC_$_CLASS_METHODS_HDDatabaseTransaction(HealthDaemon|Logging|PendingCommitStorage)
+ __OBJC_$_CLASS_METHODS_HDSQLiteDatabase(MigrationUtilities|Health|TimeShift)
+ __OBJC_$_INSTANCE_METHODS_HDDatabaseTransaction(HealthDaemon|Logging|PendingCommitStorage)
+ __OBJC_$_INSTANCE_METHODS_HDSQLiteDatabase(MigrationUtilities|Health|TimeShift)
+ __OBJC_$_INSTANCE_METHODS_HDWorkoutBuilderServer(HealthDaemon|HealthDaemon1|HealthDaemon2|HealthDaemon3)
+ __OBJC_$_INSTANCE_METHODS__HDWorkoutCondenserBatch
+ __OBJC_$_INSTANCE_VARIABLES__HDWorkoutCondenserBatch
+ __OBJC_CLASS_RO_$__HDWorkoutCondenserBatch
+ __OBJC_METACLASS_RO_$__HDWorkoutCondenserBatch
+ __PPTDatabaseSetUpDayFormatter
+ __PPTDatabaseSetUpDayStartDate
+ ___101+[HDClinicalRecordEntity deleteRecordsDerivedFromMHRecordWithPersistentID:profile:transaction:error:]_block_invoke
+ ___103+[HDWorkoutCondenser _workoutEntitiesRequiringCondensationWithProfile:limit:allowRecondensation:error:]_block_invoke
+ ___121+[HDWorkoutEntity enumerateAssociationsOfWorkoutsWithCondenserVersion:afterRowID:throughRowID:transaction:error:handler:]_block_invoke
+ ___121+[HDWorkoutEntity enumerateAssociationsOfWorkoutsWithCondenserVersion:afterRowID:throughRowID:transaction:error:handler:]_block_invoke_2
+ ___155+[HDSampleAggregateCacheEntity enumerateCachedDataAndLastVisitedTimesForQueryIdentifier:sourceEntity:profile:startIndex:endIndex:error:enumerationHandler:]_block_invoke
+ ___155+[HDSampleAggregateCacheEntity enumerateCachedDataAndLastVisitedTimesForQueryIdentifier:sourceEntity:profile:startIndex:endIndex:error:enumerationHandler:]_block_invoke_2
+ ___155+[HDSampleAggregateCacheEntity enumerateCachedDataAndLastVisitedTimesForQueryIdentifier:sourceEntity:profile:startIndex:endIndex:error:enumerationHandler:]_block_invoke_3
+ ___161+[HDAuthorizationEntity _accumulateDecisionChangeForSourceIdentifier:dataTypeCode:authorizationStatus:authorizationMode:modeInfo:database:decisionChanged:error:]_block_invoke
+ ___161+[HDAuthorizationEntity _accumulateDecisionChangeForSourceIdentifier:dataTypeCode:authorizationStatus:authorizationMode:modeInfo:database:decisionChanged:error:]_block_invoke_2
+ ___161+[HDAuthorizationEntity _accumulateDecisionChangeForSourceIdentifier:dataTypeCode:authorizationStatus:authorizationMode:modeInfo:database:decisionChanged:error:]_block_invoke_3
+ ___48-[HDDataEntityDeletionContext deletedObjectsMap]_block_invoke
+ ___54-[HDDataEntityDeletionContext deletedObjectsParentMap]_block_invoke
+ ___65+[HDActivityCacheEntity applyTimeOffset:dayCount:database:error:]_block_invoke
+ ___65-[HDProfileManager executeBlockAfterSecondaryProfilesLoad:queue:]_block_invoke
+ ___68+[HDWorkoutCondenser _maximumAssociationRowIDWithTransaction:error:]_block_invoke
+ ___69+[HDHealthEntity(TimeShift) applyTimeOffset:dayCount:database:error:]_block_invoke
+ ___71-[HDWorkoutCondenser _queue_batchWithLimit:analyticsAccumulator:error:]_block_invoke
+ ___73+[HDWorkoutCondenser _addChangedWorkoutsToBatch:limit:transaction:error:]_block_invoke
+ ___74-[HDWorkoutBuilderServer remote_discardCurrentActivityUnitWithCompletion:]_block_invoke
+ ___74-[HDWorkoutBuilderServer remote_discardCurrentActivityUnitWithCompletion:]_block_invoke_2
+ ___75+[HDWorkoutCondenser _condenseWorkouts:configuration:processedCount:error:]_block_invoke
+ ___75-[HDCloudSyncCachedZone changeRecordsInSequences:error:enumerationHandler:]_block_invoke
+ ___75-[HDWorkoutBuilderServer remote_endCurrentActivityUnitWithDate:completion:]_block_invoke
+ ___78+[HDActivityCacheEntity _applyTimeOffset:toStatisticsInColumn:database:error:]_block_invoke
+ ___78-[HDWorkoutBuilderServer remote_addWorkoutActivityUnitWithWrapper:completion:]_block_invoke
+ ___79-[HDSQLiteDatabase(TimeShift) hd_applyTimeOffset:toUniqueColumn:inTable:error:]_block_invoke
+ ___82-[HDWorkoutBuilderServer remote_replaceWorkoutActivityUnitOld:newUnit:completion:]_block_invoke
+ ___82-[HDWorkoutBuilderServer remote_updateCurrentActivityAddingSetWrapper:completion:]_block_invoke
+ ___85-[HDWorkoutBuilderServer remote_updateActivityWithUUID:workoutSetWrapper:completion:]_block_invoke
+ ___85-[HDWorkoutBuilderServer remote_updateActivityWithUUID:workoutSetWrapper:completion:]_block_invoke_2
+ ___86-[HDDatabase _runPostMigrationUpdatesWithUnprotectedDatabase:protectedDatabase:error:]_block_invoke
+ ___86-[HDDatabase _runPostMigrationUpdatesWithUnprotectedDatabase:protectedDatabase:error:]_block_invoke_2
+ ___87+[HDWorkoutEntity _insertSubActivitiesForWorkout:ownerID:primaryEntity:database:error:]_block_invoke
+ ___88-[HDCloudSyncCachedZone _recordsForClass:epoch:recordIDFilter:error:enumerationHandler:]_block_invoke
+ ___88-[HDCloudSyncCachedZone _recordsForClass:epoch:recordIDFilter:error:enumerationHandler:]_block_invoke_2
+ ___93-[HDObserverQueryServer _queue_enumerateLatestSampleWithEnumerator:sampleType:error:handler:]_block_invoke
+ ___93-[HDObserverQueryServer _queue_enumerateLatestSampleWithEnumerator:sampleType:error:handler:]_block_invoke_2
+ ___96+[HDWorkoutEntity _backfillStrengthActivityTreeForWorkout:ownerID:primaryEntity:database:error:]_block_invoke
+ ____HDAppendUUIDsByType_block_invoke
+ ____HDImmutableUUIDsByType_block_invoke
+ ___block_descriptor_112_e8_32s40s48s56s64s72s80s88s96s104r_e24_B32?0"NSUUID"8^B16^24l
+ ___block_descriptor_128_e8_32s40s48s56s64s72s80s88s96s104r_e35_B24?0"HDDatabaseTransaction"8^16l
+ ___block_descriptor_40_e8_32bs_e29_B48?0"NSData"8q16q24d32^40l
+ ___block_descriptor_40_e8_32s_e38_v32?0"HKObjectType"8"NSArray"16^B24l
+ ___block_descriptor_40_e8_32s_e40_B32?0"HDCloudSyncChangeRecord"8q16^24l
+ ___block_descriptor_40_e8_32s_e45_v32?0"HKObjectType"8"NSMutableArray"16^B24l
+ ___block_descriptor_40_e8_32s_e50_v32?0"HKObjectType"8"NSMutableOrderedSet"16^B24l
+ ___block_descriptor_48_e8_32s40bs_e40_B32?0"HDCloudSyncChangeRecord"8q16^24l
+ ___block_descriptor_48_e8_32s40r_e40_B32?0"HDCloudSyncChangeRecord"8q16^24l
+ ___block_descriptor_56_e8_32s40s48s_e40_B32?0"HDCloudSyncChangeRecord"8q16^24l
+ ___block_descriptor_64_e8_32s40s48r_e11_B24?0q8q16l
+ ___block_descriptor_64_ea8_32s40s_e30_B24?0"HDSQLiteDatabase"8^16l
+ ___block_descriptor_72_e8_32s40bs48bs_e35_B24?0"HDDatabaseTransaction"8^16lu56l8
+ ___block_descriptor_72_e8_32s40s48bs56bs_e65_B48?0"HDCachedCKRecordEntity"8"CKRecordID"16"NSData"24q32^40lu64l8
+ ___block_descriptor_73_e8_32s40s48s_e35_B24?0"HDDatabaseTransaction"8^16l
+ ___block_descriptor_80_e8_32s40s48s56s64r_e41_B40?0q8"NSArray"16^{HDSQLiteRow=}24^32l
+ ___block_descriptor_88_e8_32s40s48s56s64r72r_e31_v32?0"HDSyncIdentity"8Q16^B24l
+ ___block_descriptor_88_e8_32s40s_e34_v16?0^{HDSQLiteStatementBinder=}8l
+ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96s104r
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96s104r
+ ___swift_memcpy104_8
+ __accumulateDecisionChangeForSourceIdentifier:dataTypeCode:authorizationStatus:authorizationMode:modeInfo:database:decisionChanged:error:.lookupKey
+ _associated conformance 12HealthDaemon22HDWorkoutSetMeEqEntityC6RecordVSHAASQ
+ _kHDDemoDataSDNNCycleLevels
+ _kHKBridgeBundleIdentifier
+ _objc_msgSend$_makeNormallyDistributedAudioExposureLevelsWithCount:audioLevelType:loudData:
+ _objc_msgSend$_meanVO2MaxValueForDemoPerson:date:
+ _objc_msgSend$_menstrualCycleAnchorDate
+ _objc_msgSend$_newUUID
+ _objc_msgSend$_recordDeletedObjectParents:
+ _objc_msgSend$_recordDeletedObjectUUID:objectType:
+ _objc_msgSend$_validateAndAddActivity:parentActivity:skipActivityTypeValidation:excludingActivityUUIDs:transaction:error:
+ _objc_msgSend$acceptedAuthorizationBackupRestoreIdentifiersWithHealthDatabase:
+ _objc_msgSend$addWorkoutActivitySets:workoutSetWrapper:transaction:error:
+ _objc_msgSend$addWorkoutActivitySets:wrapper:error:
+ _objc_msgSend$applyTimeOffset:database:error:
+ _objc_msgSend$applyTimeOffset:dayCount:database:error:
+ _objc_msgSend$changeRecordsInSequence:error:enumerationHandler:
+ _objc_msgSend$changeRecordsInSequences:error:enumerationHandler:
+ _objc_msgSend$clearRestoredAuthorizationBackupRestoreIdentifier
+ _objc_msgSend$cooldownHeartRateForDemoPerson:maxHeartRate:percentCooled:
+ _objc_msgSend$databaseTransactionContext
+ _objc_msgSend$dateFromString:
+ _objc_msgSend$deleteWorkoutActivityIncludingChildren:transaction:error:
+ _objc_msgSend$didCompleteCloudSyncPushWithHealthDatabase:
+ _objc_msgSend$enumerateAssociationsOfWorkoutsWithCondenserVersion:afterRowID:throughRowID:transaction:error:handler:
+ _objc_msgSend$enumerateCachedDataAndLastVisitedTimesForQueryIdentifier:sourceEntity:profile:startIndex:endIndex:error:enumerationHandler:
+ _objc_msgSend$equipment
+ _objc_msgSend$fullNodeWrapper
+ _objc_msgSend$generatesContinuousHeartRate
+ _objc_msgSend$hasEquipment
+ _objc_msgSend$hasUnitConceptIdentifier
+ _objc_msgSend$hasWeightQuantity
+ _objc_msgSend$hd_applyTimeOffset:toUniqueColumn:inTable:error:
+ _objc_msgSend$hd_recordReadTimingWithConnectionWait:duration:
+ _objc_msgSend$hd_researchEntitlementStateForSource:
+ _objc_msgSend$headacheSymptomForDemoPerson:withSampleDate:anchorDate:
+ _objc_msgSend$heartRateVariabilitySDNN
+ _objc_msgSend$heartRateVariabilitySDNNSampleFrequency
+ _objc_msgSend$heartRateVariabilitySDNNSampleFrequencyStdDev
+ _objc_msgSend$initWithRawValue:comparatorCoding:unitCoding:unitConceptIdentifier:
+ _objc_msgSend$initWithType:localDevice:productTypeName:currentOSName:currentOSVersion:modificationDate:appleIntelligenceEligibility:
+ _objc_msgSend$initWithType:productTypeName:currentOSName:currentOSVersion:modificationDate:syncIdentity:appleIntelligenceEligibility:
+ _objc_msgSend$insertActivityUnitWrapper:wrapper:error:
+ _objc_msgSend$insertSetWrapper:transaction:outError:
+ _objc_msgSend$insertWorkoutSetsOnActivityEntityIfNeededWithActivity:database:outError:
+ _objc_msgSend$insertWorkoutSetsOnBuilderActivityEntityIfNeededWithActivity:database:outError:
+ _objc_msgSend$isStrengthTrainingWorkout:
+ _objc_msgSend$level
+ _objc_msgSend$localeWithLocaleIdentifier:
+ _objc_msgSend$makeRestWorkoutActivityWithConfiguration:startDate:endDate:metadata:skipValidation:
+ _objc_msgSend$makeRestWorkoutConfiguration
+ _objc_msgSend$makeStrengthTrainingWorkoutActivityFromSyncWithConfiguration:startDate:endDate:metadata:codableSets:
+ _objc_msgSend$makeStrengthTrainingWorkoutActivityWithConfiguration:startDate:endDate:metadata:skipValidation:
+ _objc_msgSend$makeStrengthWorkoutConfigurationWithExerciseType:muscleGroups:
+ _objc_msgSend$menstrualCrampSymptomForDemoPerson:withSampleDate:anchorDate:
+ _objc_msgSend$menstrualFlowForDemoPerson:withSampleDate:anchorDate:
+ _objc_msgSend$motionHeartRateForDemoPerson:isMoving:secondsSinceMotionEnded:noise:
+ _objc_msgSend$muscleGroups
+ _objc_msgSend$observerQueryIndexedInitialAnchor
+ _objc_msgSend$offsetDayCount
+ _objc_msgSend$ovulationTestResultForDemoPerson:withSampleDate:anchorDate:
+ _objc_msgSend$rangeOfString:options:
+ _objc_msgSend$rangeOfString:options:range:
+ _objc_msgSend$recordID:canBeInSequence:
+ _objc_msgSend$removeIntervalsWithUUIDs:
+ _objc_msgSend$removeSubtreeFrom:activity:
+ _objc_msgSend$repCount
+ _objc_msgSend$repetitionType
+ _objc_msgSend$replaceActivityUnitWrapper:newWrapper:error:
+ _objc_msgSend$requestAuthorizationBackupRestoreIdentifierRotation
+ _objc_msgSend$rerollRestingHeartRateWithUnitRandom:
+ _objc_msgSend$restingHeartRateDailyMaximum
+ _objc_msgSend$restingHeartRateDailyMinimum
+ _objc_msgSend$restoredAuthorizationBackupRestoreIdentifier
+ _objc_msgSend$setDateFormat:
+ _objc_msgSend$setEquipment:
+ _objc_msgSend$setFromBitmask:
+ _objc_msgSend$setFullNodeWrapper:
+ _objc_msgSend$setGeneratesContinuousHeartRate:
+ _objc_msgSend$setHeartRateVariabilitySDNN:
+ _objc_msgSend$setHeartRateVariabilitySDNNSampleFrequency:
+ _objc_msgSend$setHeartRateVariabilitySDNNSampleFrequencyStdDev:
+ _objc_msgSend$setInactivityFlushMode:
+ _objc_msgSend$setOffsetDayCount:
+ _objc_msgSend$setRepCount:
+ _objc_msgSend$setRepetitionType:
+ _objc_msgSend$setRestingHeartRateDailyMaximum:
+ _objc_msgSend$setRestingHeartRateDailyMinimum:
+ _objc_msgSend$setSide:
+ _objc_msgSend$setStrengthPropertiesOnActivityIfNeededWithWorkoutActivity:activityOwnerID:database:outError:
+ _objc_msgSend$setStrengthPropertiesOnBuilderActivityIfNeededWithWorkoutActivity:activityOwnerID:database:outError:
+ _objc_msgSend$setUnitConceptIdentifier:
+ _objc_msgSend$setVo2MaxMean:
+ _objc_msgSend$setWeightQuantity:
+ _objc_msgSend$setYieldsToForegroundClients:
+ _objc_msgSend$sets
+ _objc_msgSend$seymourSExerciseIdentifier
+ _objc_msgSend$seymourSWorkoutIdentifier
+ _objc_msgSend$side
+ _objc_msgSend$strengthExerciseType
+ _objc_msgSend$trimCachedConnectionsToCount:
+ _objc_msgSend$unitConceptIdentifier
+ _objc_msgSend$userRequested
+ _objc_msgSend$vo2MaxMean
+ _objc_msgSend$weightQuantity
+ _objc_msgSend$willBeginCloudSyncPush
+ _objc_msgSend$workoutActivityNodeWrapperFrom:targetActivity:children:
+ _objc_msgSend$workoutHeartRateForDemoPerson:maxHeartRate:noise:
+ _symbolic SDySS_____GSg 9HealthKit19HKMetadataValueTypeO
+ _symbolic Say_____G 9HealthKit33HKWorkoutStrengthTrainingActivityC
+ _symbolic Say_____Gz_Xx 9HealthKit33HKWorkoutStrengthTrainingActivityC
+ _symbolic Shy_____G 9HealthKit18HKWorkoutEquipmentO
+ _symbolic So35HKWorkoutStrengthTrainingSetWrapperC
+ _symbolic _____ 12HealthDaemon18HDWorkoutSetEntityC6RecordV
+ _symbolic _____ 12HealthDaemon20HDWorkoutSetMeEntityC6RecordV
+ _symbolic _____ 12HealthDaemon22HDWorkoutSetMeEqEntityC6RecordV
+ _symbolic _____ 9HealthKit18HKWorkoutEquipmentO
+ _symbolic _____ 9HealthKit21HKWorkoutActivityNodeV
+ _symbolic _____ 9HealthKit23HKWorkoutRepetitionTypeO
+ _symbolic _____ 9HealthKit46HKWorkoutStrengthTrainingExerciseConfigurationC
+ _symbolic _____S2iSdSAySo7NSErrorCSgGSgSbIggyyyyd_ 10Foundation4DataV
+ _symbolic _____y_____G 9HealthKit23SleepSessionQueryAnchorV AA0C10DaySummaryV
+ _type_layout_string 12HealthDaemon18HDWorkoutSetEntityC6RecordV
+ _type_layout_string 12HealthDaemon22HDWorkoutSetMeEqEntityC6RecordV
+ _unitTesting_restoredAuthorizationBackupIdentifier
- +[HDWorkoutCondenser _workoutEntitiesRequiringCondensationWithProfile:limit:allowRecondensation:analyticsAccumulator:error:]
- -[HDDataManager mergeDictionary:intoDictionary:]
- -[HDDemoDataReproductiveHealthSampleGenerator _computeFirstRunCycleFactorSamplesForDemoPerson:targetDate:]
- -[HDDemoDataReproductiveHealthSampleGenerator menstrualFlowForDemoPerson:withSampleDate:]
- -[HDDemoDataVitalsSampleGenerator _computeMaxHRForDemoPerson:atTime:]
- GCC_except_table109
- GCC_except_table183
- _HDPPTTestDataUpdateAppliedDefaultsKey
- _HDPPTTestRunningDefaultsKey
- _HDSQLiteQueryDescriptorForOwningQueryID
- __OBJC_$_CATEGORY_INSTANCE_METHODS_HDSQLiteDatabase_$_MigrationUtilities
- __OBJC_$_CLASS_METHODS_HDDatabaseTransaction(Logging|PendingCommitStorage)
- __OBJC_$_CLASS_METHODS_HDSQLiteDatabase(MigrationUtilities|Health)
- __OBJC_$_INSTANCE_METHODS_HDDatabaseTransaction(Logging|PendingCommitStorage)
- __OBJC_$_INSTANCE_METHODS_HDWorkoutBuilderServer(HealthDaemon|HealthDaemon1|HealthDaemon2)
- ___119-[HDDemoDataAudioExposureSampleGenerator _makeNormallyDistributedAudioExposureLevelsWithCount:audioLevelType:loudData:]_block_invoke_3
- ___124+[HDWorkoutCondenser _workoutEntitiesRequiringCondensationWithProfile:limit:allowRecondensation:analyticsAccumulator:error:]_block_invoke
- ___136+[HDSampleAggregateCacheEntity enumerateCachedDataForQueryIdentifier:sourceEntity:profile:startIndex:endIndex:error:enumerationHandler:]_block_invoke_2
- ___136+[HDSampleAggregateCacheEntity enumerateCachedDataForQueryIdentifier:sourceEntity:profile:startIndex:endIndex:error:enumerationHandler:]_block_invoke_3
- ___158+[HDSampleAggregateCacheEntity(Testing) enumerateCachedDataForQueryIdentifierWithTimestamp:sourceEntity:profile:startIndex:endIndex:error:enumerationHandler:]_block_invoke_2
- ___158+[HDSampleAggregateCacheEntity(Testing) enumerateCachedDataForQueryIdentifierWithTimestamp:sourceEntity:profile:startIndex:endIndex:error:enumerationHandler:]_block_invoke_3
- ___54-[HDDatabase _applyOffsetTimeInterval:database:error:]_block_invoke
- ___57-[HDDatabase _runPostMigrationUpdatesWithDatabase:error:]_block_invoke
- ___60+[HDWorkoutCondenser _condenseWorkouts:configuration:error:]_block_invoke
- ___72-[HDCloudSyncCachedZone recordsForClass:epoch:error:enumerationHandler:]_block_invoke
- ___72-[HDCloudSyncCachedZone recordsForClass:epoch:error:enumerationHandler:]_block_invoke_2
- ___block_descriptor_112_e8_32s40s48s56s64s72s80s88r96r104r_e24_B32?0"NSUUID"8^B16^24l
- ___block_descriptor_120_e8_32s40s48s56s64s72s80s88s96s_e35_B24?0"HDDatabaseTransaction"8^16l
- ___block_descriptor_48_e8_32s40s_e33_B16?0"HDCloudSyncChangeRecord"8l
- ___block_descriptor_48_ea8_32s_e30_B24?0"HDSQLiteDatabase"8^16l
- ___block_descriptor_64_e8_32s40bs_e35_B24?0"HDDatabaseTransaction"8^16lu48l8
- ___block_descriptor_64_e8_32s40s48bs_e65_B48?0"HDCachedCKRecordEntity"8"CKRecordID"16"NSData"24q32^40lu56l8
- ___block_descriptor_72_e8_32s40s48s56s_e41_B40?0q8"NSArray"16^{HDSQLiteRow=}24^32l
- ___block_descriptor_80_e8_32s40s48s56r64r_e31_v32?0"HDSyncIdentity"8Q16^B24l
- ___block_descriptor_80_e8_32s40s_e34_v16?0^{HDSQLiteStatementBinder=}8l
- ___block_descriptor_81_e8_32s40s48s56s_e35_B24?0"HDDatabaseTransaction"8^16l
- ___swift_memcpy96_8
- _objc_msgSend$codedQuantityWithValue:comparatorCoding:unitCoding:
- _objc_msgSend$initWithType:localDevice:productTypeName:currentOSName:currentOSVersion:modificationDate:
- _objc_msgSend$initWithType:productTypeName:currentOSName:currentOSVersion:modificationDate:syncIdentity:
- _objc_msgSend$sources
- _symbolic _____S2iSAySo7NSErrorCSgGSgSbIggyyyd_ 10Foundation4DataV
- _unitTesting_currentAuthorizationBackupIdentifier
CStrings:
+ " (another decision is waiting for the next push)"
+ "%@ attempted to set yieldsToForegroundClients after queuing"
+ "%@: Failed to find parent node of activity unit to replace"
+ "%@: Unable to add workout activity sets. Incorrect parent configuration"
+ "%@: Unable to add workout activity sets. Profile not configured"
+ "%@: Unable to insert workout activity unit. Profile not configured"
+ "%@: Unable to replace workout activity unit. Profile not found"
+ "%ld workouts requiring condensation (%ld uncondensed, %ld changed, %ld recondensable)"
+ "%ld:%d:%ld:%ld"
+ "%{public}@: Adding workout sets to activity with UUID %@"
+ "%{public}@: Adding workout sets to current activity unit UUID %@"
+ "%{public}@: Client's discardCurrentActivityUnit completion handler not called, error fetching client proxy: %{public}@"
+ "%{public}@: Client's endCurrentActivityUnit completion handler not called, error fetching client proxy: %{public}@"
+ "%{public}@: Client's replaceWorkoutActivityUnit completion handler not called, error fetching client proxy: %{public}@"
+ "%{public}@: Discarding activity unit with UUID %@"
+ "%{public}@: Failed to read restore completion date: %{public}@"
+ "%{public}@: Failed to remove undecided authorizations for \"%{public}@\": %{public}@"
+ "%{public}@: Layout element %{public}@, level: %ld, filtered: %{public}@"
+ "%{public}@: Push succeeded; authorization backup identifier is now %{public}@%{public}@"
+ "%{public}@: Restore complete; no longer accepting restored identifier %{public}@"
+ "%{public}@: Restore incomplete; still accepting restored identifier %{public}@"
+ "%{public}@: Skipping %lu objects with no backup identifier and %lu objects with backup identifiers %{public}@ that match none of %{public}@"
+ "%{public}@: Skipping restored authorizations for \"%{public}@\": a local decision exists"
+ "%{public}@: Trimming idle connections due to inactivity."
+ "%{public}s Failed to convert exercise type to HKWorkoutStrengthTrainingExerciseType"
+ "%{public}s Failed to convert workout unit to activity node. Unknown unit type."
+ "<%@:%p type:%ld productType:%@ OSName:%@ OSVersion:%@ sync identity:%@ last modified:%@ appleIntelligenceEligibility:%ld"
+ "ALTER TABLE clinical_record_samples ADD COLUMN original_mh_record_rowid INTEGER REFERENCES mh_records (data_id) ON DELETE NO ACTION"
+ "ALTER TABLE device_context ADD COLUMN apple_intelligence_eligibility INTEGER NOT NULL DEFAULT 0"
+ "Activity is incorrect type."
+ "Activity not found."
+ "Activity unit is unexpectedly nil"
+ "Activity unit tree is unexpectedly nil"
+ "Add workout activity unit"
+ "AppleIntelligenceEligibility"
+ "B48@?0@\"NSData\"8q16q24d32^@40"
+ "Begin applying PPT database time offset of %f seconds (%ld days)"
+ "Corrected research entitlement for %{public}@: stored %{public}s, installed %{public}s"
+ "Could not find activity unit to replace"
+ "Could not find subtree for activity unit to replace"
+ "End applying PPT database time offset of %f seconds (%ld days)"
+ "Failed to add activity unit. %@"
+ "Failed to add sets. %@"
+ "Failed to create HDCodableWorkoutSet for encoding"
+ "Failed to create HDCodableWorkoutSetMetric for encoding"
+ "Failed to create rest activity from configuration %@."
+ "Failed to create strength activity from configuration %@."
+ "Failed to create strength configuration."
+ "Failed to find parent activity with persistent id %lld in database."
+ "Failed to find parent node of activity unit to replace"
+ "Failed to get databse from transaction"
+ "Failed to replace activity unit wrapper. %@"
+ "Failed to replace activity unit. %@"
+ "Failed to save activity unit sets. %@"
+ "Failed to save activity unit wrapper. %@"
+ "Failed to save activity unit. %@"
+ "Failed to save recondensation state: %{public}@"
+ "Failed to save replaced activity unit. %@"
+ "Failed to save sets. %@"
+ "HDAuthorizationBackupStampIdentifier"
+ "HDAuthorizationBackupSyncEntityRestoredIdentifier"
+ "HDAuthorizationBackupSyncEntityRotationHandledCount"
+ "HDAuthorizationBackupSyncEntityRotationRequestCount"
+ "HDDemoDataHeartSampleGeneratorNextHRVSDNNSampleTimeKey"
+ "HDDemoDataReproductiveHealthSampleHelperMenstrualCycleAnchorDateKey"
+ "HDDemoDataVitalsSampleHelperLastMotionEndTimeKey"
+ "HDPPTDatabaseSetUpAllowNonInternalInstall"
+ "HDPPTDatabaseSetUpOffsetTimesApplied"
+ "HDPPTDatabaseSetUpOffsetTimesEnabled"
+ "HDPPTDatabaseSetUpOffsetToDay"
+ "HDPPTDatabaseSetUpSeedLatestDay"
+ "HDWorkoutCondenserRecondensation"
+ "Incorrect parent activity configuration"
+ "Leaving %{public}@ of activity cache %lld without a time offset; failed to decode it: %{public}@"
+ "Merging Strength Workout"
+ "New activity unit is unexpectedly nil"
+ "New activity unit tree is unexpectedly nil"
+ "No MHRecord found for the origin UUID provided for FK on insert"
+ "No OrignalFHIRResource, OriginalSignedClinicalDataRecord, or MHRecord ROWID provided for FK on insert"
+ "No activity unit active."
+ "No root activity unit found."
+ "Offsetting PPT database times by %f seconds (%ld days), from %{public}@ to %{public}@"
+ "Old activity unit is unexpectedly nil"
+ "PPT database offset not applied: expected \"%{public}@\" and \"%{public}@\" formatted as \"yyyy-MM-dd <time zone identifier>\", got \"%{public}@\" and \"%{public}@\""
+ "Replace workout activity unit"
+ "ReverifyBeforeTime"
+ "SELECT %@, %@ FROM %@ WHERE %@ > ? AND %@ <= ? AND %@ IN (SELECT %@ FROM %@ WHERE %@ = ?) ORDER BY %@"
+ "SELECT %@, %@ FROM %@ WHERE %@ IS NOT NULL"
+ "SELECT %@, %@, %@, %@, %@, %@ FROM %@ WHERE %@ = ? AND %@ = ?"
+ "Skipping hip circumference sample; demoPerson.hipCircumferenceInInches is unconfigured (0)"
+ "Skipping waist circumference sample; demoPerson.waistCircumferenceInInches is unconfigured (0)"
+ "UPDATE %@ SET %@ = %@ + ?"
+ "UPDATE %@ SET %@ = -%@"
+ "UPDATE %@ SET %@ = -(%@ + ?)"
+ "Unable to find primary activity with UUID %@ during backfill"
+ "VerifiedAssociationRowID"
+ "VerifiedConfiguration"
+ "Wrote one-time adult height sample: %.1f cm at %@"
+ "Wrote one-time hip circumference sample: %.1f in at %@"
+ "Wrote one-time waist circumference sample: %.1f in at %@"
+ "[%{public}@] Failed to count existing contraceptives: %{public}@"
+ "[%{public}@] Failed to count existing pregnancies: %{public}@"
+ "[%{public}@] Failed to enable fertile window projections: %{public}@"
+ "[%{public}@] Failed to enable menstruation projections: %{public}@"
+ "apple_intelligence_eligibility"
+ "com.apple.healthd.HDPPTDatabaseSetUpOffsetTimesDidApply"
+ "en_US_POSIX"
+ "entitled"
+ "not entitled"
+ "original_mh_record_rowid"
+ "protectedDatabase != nil"
+ "startDate endDate "
+ "unitConceptIdentifier"
+ "user_requested"
+ "v32@?0@\"HKObjectType\"8@\"NSArray\"16^B24"
+ "v32@?0@\"HKObjectType\"8@\"NSMutableArray\"16^B24"
+ "v32@?0@\"HKObjectType\"8@\"NSMutableOrderedSet\"16^B24"
+ "yyyy-MM-dd"
- "<%@:%p type:%ld productType:%@ OSName:%@ OSVersion:%@ sync identity:%@ last modified:%@ "
- "HDPPTTestDataUpdateApplied"
- "HDPPTTestRunning"
- "queryConfiguration"
- "sleepAnalysisSourceOrderAnchor"
```
