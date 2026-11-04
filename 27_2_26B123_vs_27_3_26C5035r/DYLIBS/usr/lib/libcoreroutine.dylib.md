## libcoreroutine.dylib

> `/usr/lib/libcoreroutine.dylib`

```diff

-1123.0.3.0.0
-  __TEXT.__text: 0x68cac4
-  __TEXT.__objc_methlist: 0x32550
-  __TEXT.__const: 0x4678
+1123.0.6.0.0
+  __TEXT.__text: 0x694160
+  __TEXT.__objc_methlist: 0x32848
+  __TEXT.__const: 0x4698
   __TEXT.__dlopen_cstrs: 0xb2
   __TEXT.__constg_swiftt: 0x74
   __TEXT.__swift5_typeref: 0x190
   __TEXT.__swift5_fieldmd: 0x20
   __TEXT.__swift5_types: 0x8
-  __TEXT.__oslogstring: 0x7f1c2
-  __TEXT.__cstring: 0x45d0e
+  __TEXT.__oslogstring: 0x7fc52
+  __TEXT.__cstring: 0x4619e
   __TEXT.__swift5_capture: 0x7c
   __TEXT.__swift_as_entry: 0x1c
   __TEXT.__swift_as_ret: 0x20
   __TEXT.__swift_as_cont: 0x24
-  __TEXT.__gcc_except_tab: 0x28444
+  __TEXT.__gcc_except_tab: 0x28754
   __TEXT.__ustring: 0x3e
-  __TEXT.__unwind_info: 0x10688
+  __TEXT.__unwind_info: 0x107c0
   __TEXT.__eh_frame: 0x3a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3560
-  __DATA_CONST.__objc_classlist: 0x1610
-  __DATA_CONST.__objc_catlist: 0x3c0
+  __DATA_CONST.__const: 0x3580
+  __DATA_CONST.__objc_classlist: 0x1638
+  __DATA_CONST.__objc_catlist: 0x3c8
   __DATA_CONST.__objc_protolist: 0x348
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x19928
+  __DATA_CONST.__objc_selrefs: 0x19ac8
   __DATA_CONST.__objc_protorefs: 0x138
-  __DATA_CONST.__objc_superrefs: 0x11e8
+  __DATA_CONST.__objc_superrefs: 0x1200
   __DATA_CONST.__objc_arraydata: 0x2ca8
-  __DATA_CONST.__got: 0x2f60
-  __AUTH_CONST.__const: 0xf6e0
-  __AUTH_CONST.__cfstring: 0x28940
-  __AUTH_CONST.__objc_const: 0x542d8
-  __AUTH_CONST.__objc_intobj: 0x4860
+  __DATA_CONST.__got: 0x2fa8
+  __AUTH_CONST.__const: 0xf7b0
+  __AUTH_CONST.__cfstring: 0x28b20
+  __AUTH_CONST.__objc_const: 0x548c0
+  __AUTH_CONST.__objc_intobj: 0x4890
   __AUTH_CONST.__objc_arrayobj: 0xeb8
   __AUTH_CONST.__objc_doubleobj: 0xbe0
   __AUTH_CONST.__objc_dictobj: 0x280
   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH_CONST.__auth_got: 0xde0
-  __AUTH.__objc_data: 0x19a8
+  __AUTH.__objc_data: 0x1b38
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0x2838
+  __DATA.__objc_ivar: 0x285c
   __DATA.__data: 0x2a98
   __DATA.__bss: 0x50
-  __DATA_DIRTY.__objc_ivar: 0x1170
+  __DATA_DIRTY.__objc_ivar: 0x1178
   __DATA_DIRTY.__objc_data: 0xc3c0
   __DATA_DIRTY.__data: 0x648
   __DATA_DIRTY.__bss: 0x1f0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 20980
-  Symbols:   42777
-  CStrings:  15225
+  Functions: 21065
+  Symbols:   42948
+  CStrings:  15288
 
Symbols:
+ +[RTAuthorizationManager readCoreRoutineLocationClientState]
+ +[RTExtendedTimeToLiveGate refreshMFeatureVerdictWithProvider:previousVerdict:defaultsManager:]
+ +[RTPOIHarvestUtilities harvestVisit:targets:harvestType:poiHarvester:error:]
+ +[RTPOIHarvestUtilities shouldHarvestMapItemSource:harvestType:harvestMask:]
+ +[RTTripParkingMetrics(RTCoreDataTransformable) createWithManagedObject:]
+ +[RTTripParkingMetrics(RTCoreDataTransformable) createWithTripParkingMetricsMO:]
+ +[RTTripParkingMetricsCalculator circlingTimeForSortedLocations:destinationLatitude:destinationLongitude:radius_m:tripEndDate:]
+ +[RTTripParkingMetricsCalculator walkingTimeAfterLastDriveForSortedCommuteTrips:walkTimeDurationAfterDrive_sec:]
+ +[RTTripParkingMetricsMO managedObjectWithTripParkingMetrics:inManagedObjectContext:]
+ +[RTTripParkingMetricsMO(CoreDataProperties) fetchRequest]
+ +[RTTripParkingMetricsStore _predicateForCommuteID:]
+ -[RTAuthorizationManager _applyCoreRoutineLocationClientState:]
+ -[RTAuthorizationManager _readCoreRoutineLocationClientState]
+ -[RTAuthorizationManager coreRoutineEnabledVerified]
+ -[RTAuthorizationManager setCoreRoutineEnabledVerified:]
+ -[RTCheckInMetricsProvider runIsMultiDevice]
+ -[RTCheckInMetricsProvider setRunIsMultiDevice:]
+ -[RTDaemonClient fetchTripParkingMetricsWithOptions:reply:]
+ -[RTExtendedTimeToLiveGate initWithFeatureEnabled:trialManager:platform:defaultsManager:activityStatusProvider:]
+ -[RTLearnedLocationEngine _harvestVisits:places:finerGranularityInferredMapItems:]
+ -[RTPOIHarvestContext .cxx_destruct]
+ -[RTPOIHarvestContext accessPoints]
+ -[RTPOIHarvestContext fingerprintLocations]
+ -[RTPOIHarvestContext initWithAccessPoints:fingerprintLocations:motionActivities:]
+ -[RTPOIHarvestContext motionActivities]
+ -[RTPOIHarvestTarget .cxx_destruct]
+ -[RTPOIHarvestTarget initWithMapItem:source:]
+ -[RTPOIHarvestTarget mapItem]
+ -[RTPOIHarvestTarget source]
+ -[RTPOIHarvester _harvestContextForAccessPoints:metrics:]
+ -[RTPOIHarvester _harvestPOIs:accessPointArrays:referenceLocations:harvestType:metrics:error:]
+ -[RTPOIHarvester _poiHarvestWithContext:mapItem:referenceLocations:harvestType:]
+ -[RTPOIHarvester harvestPOIs:visitLocations:visitEntryDate:visitExitDate:harvestType:error:]
+ -[RTPersistenceMirroringManager _recomputeExportingAvailability]
+ -[RTPersistenceMirroringManager onExpiredRecordsRemoved:]
+ -[RTPurgeManager _longTermExtendedReferenceDate:]
+ -[RTTripClusterDataStoresContainer _refreshCloudSyncRetentionIntervals]
+ -[RTTripClusterDataStoresContainer initWithTripClusterStore:tripClusterCloudStore:tripClusterRouteStore:tripClusterRouteRoadTransitionsStore:tripClusterRecencyStore:tripClusterRecencyCloudStore:tripClusterScheduleStore:tripClusterScheduleCloudStore:tripSegmentRoadTransitionsStore:tripClusterWaypointStore:tripClusterWaypointCloudStore:tripClusterRouteSummaryStore:tripParkingMetricsStore:defaultsManager:bugCaptureManager:]
+ -[RTTripClusterDataStoresContainer isTripClusterChildDataEligibleForCloudPush:]
+ -[RTTripClusterDataStoresContainer isTripClusterEligibleForCloudPush:]
+ -[RTTripClusterDataStoresContainer isTripClusterRecencyEligibleForCloudPush:]
+ -[RTTripClusterDataStoresContainer tripParkingMetricsStore]
+ -[RTTripClusterManager _computeAndStoreTripParkingMetricsForDrivingSegment:sortedCommuteTrips:walkAndBikeTripStats:]
+ -[RTTripClusterManager fetchTripParkingMetricsWithOptions:handler:]
+ -[RTTripClusterManager isParkingMetricsEnabled]
+ -[RTTripClusterManager setIsParkingMetricsEnabled:]
+ -[RTTripParkingMetrics(RTCoreDataTransformable) managedObjectWithContext:]
+ -[RTTripParkingMetricsStore _deleteExpiredTripParkingMetricsPredating:handler:]
+ -[RTTripParkingMetricsStore _deleteTripParkingMetricsWithCommuteID:handler:]
+ -[RTTripParkingMetricsStore _fetchTripParkingMetricsWithContext:handler:]
+ -[RTTripParkingMetricsStore _fetchTripParkingMetricsWithOptions:handler:]
+ -[RTTripParkingMetricsStore _getAllStoredCommuteIDsWithHandler:]
+ -[RTTripParkingMetricsStore _purgeTripParkingMetricsWithHandler:]
+ -[RTTripParkingMetricsStore _storeTripParkingMetrics:handler:]
+ -[RTTripParkingMetricsStore deleteExpiredTripParkingMetricsPredating:handler:]
+ -[RTTripParkingMetricsStore deleteTripParkingMetricsWithCommuteID:]
+ -[RTTripParkingMetricsStore deleteTripParkingMetricsWithCommuteID:handler:]
+ -[RTTripParkingMetricsStore fetchRequestFromOptions:offset:error:]
+ -[RTTripParkingMetricsStore fetchRequestFromOptions:offset:error:inManagedObjectContext:]
+ -[RTTripParkingMetricsStore fetchRequestFromStoredTripParkingMetricsOptions:inManagedObjectContext:]
+ -[RTTripParkingMetricsStore fetchTripParkingMetricsWithContext:handler:]
+ -[RTTripParkingMetricsStore fetchTripParkingMetricsWithOptions:handler:]
+ -[RTTripParkingMetricsStore getAllStoredCommuteIDsWithHandler:]
+ -[RTTripParkingMetricsStore getAllStoredCommuteIDs]
+ -[RTTripParkingMetricsStore getTripParkingMetricsWithOptions:]
+ -[RTTripParkingMetricsStore initWithPersistenceManager:]
+ -[RTTripParkingMetricsStore purgeTripParkingMetricsWithHandler:]
+ -[RTTripParkingMetricsStore storeTripParkingMetrics:]
+ -[RTTripParkingMetricsStore storeTripParkingMetrics:handler:]
+ GCC_except_table202
+ GCC_except_table216
+ GCC_except_table227
+ GCC_except_table234
+ GCC_except_table237
+ GCC_except_table239
+ GCC_except_table254
+ GCC_except_table256
+ GCC_except_table259
+ GCC_except_table263
+ GCC_except_table270
+ GCC_except_table273
+ GCC_except_table276
+ GCC_except_table282
+ GCC_except_table285
+ GCC_except_table287
+ GCC_except_table291
+ GCC_except_table312
+ GCC_except_table314
+ GCC_except_table316
+ GCC_except_table320
+ GCC_except_table323
+ GCC_except_table325
+ GCC_except_table327
+ GCC_except_table331
+ GCC_except_table335
+ GCC_except_table338
+ GCC_except_table340
+ GCC_except_table94
+ _OBJC_CLASS_$_RTActionSuggestionActivityStatusProvider
+ _OBJC_CLASS_$_RTPOIHarvestContext
+ _OBJC_CLASS_$_RTPOIHarvestTarget
+ _OBJC_CLASS_$_RTTripParkingMetrics
+ _OBJC_CLASS_$_RTTripParkingMetricsCalculator
+ _OBJC_CLASS_$_RTTripParkingMetricsEnumerationContext
+ _OBJC_CLASS_$_RTTripParkingMetricsEnumerationOptions
+ _OBJC_CLASS_$_RTTripParkingMetricsMO
+ _OBJC_CLASS_$_RTTripParkingMetricsStore
+ _OBJC_IVAR_$_RTCheckInMetricsProvider._runIsMultiDevice
+ _OBJC_IVAR_$_RTPOIHarvestContext._accessPoints
+ _OBJC_IVAR_$_RTPOIHarvestContext._fingerprintLocations
+ _OBJC_IVAR_$_RTPOIHarvestContext._motionActivities
+ _OBJC_IVAR_$_RTPOIHarvestTarget._mapItem
+ _OBJC_IVAR_$_RTPOIHarvestTarget._source
+ _OBJC_IVAR_$_RTTripClusterDataStoresContainer._cloudSyncExpirationInterval
+ _OBJC_IVAR_$_RTTripClusterDataStoresContainer._cloudSyncShortExpirationInterval
+ _OBJC_IVAR_$_RTTripClusterDataStoresContainer._tripParkingMetricsStore
+ _OBJC_METACLASS_$_RTActionSuggestionActivityStatusProvider
+ _OBJC_METACLASS_$_RTPOIHarvestContext
+ _OBJC_METACLASS_$_RTPOIHarvestTarget
+ _OBJC_METACLASS_$_RTTripParkingMetricsCalculator
+ _OBJC_METACLASS_$_RTTripParkingMetricsMO
+ _OBJC_METACLASS_$_RTTripParkingMetricsStore
+ _RTPersistenceExpirationEnforcerDidRemoveExpiredRecordsNotificationName
+ __DATA_RTActionSuggestionActivityStatusProvider
+ __INSTANCE_METHODS_RTActionSuggestionActivityStatusProvider
+ __METACLASS_DATA_RTActionSuggestionActivityStatusProvider
+ __OBJC_$_CATEGORY_CLASS_METHODS_RTTripParkingMetrics_$_RTCoreDataTransformable
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_RTTripParkingMetrics_$_RTCoreDataTransformable
+ __OBJC_$_CATEGORY_RTTripParkingMetrics_$_RTCoreDataTransformable
+ __OBJC_$_CLASS_METHODS_RTTripParkingMetricsCalculator
+ __OBJC_$_CLASS_METHODS_RTTripParkingMetricsMO(CoreDataProperties)
+ __OBJC_$_CLASS_METHODS_RTTripParkingMetricsStore
+ __OBJC_$_INSTANCE_METHODS_RTPOIHarvestContext
+ __OBJC_$_INSTANCE_METHODS_RTPOIHarvestTarget
+ __OBJC_$_INSTANCE_METHODS_RTTripParkingMetricsStore
+ __OBJC_$_INSTANCE_VARIABLES_RTPOIHarvestContext
+ __OBJC_$_INSTANCE_VARIABLES_RTPOIHarvestTarget
+ __OBJC_$_PROP_LIST_RTPOIHarvestContext
+ __OBJC_$_PROP_LIST_RTPOIHarvestTarget
+ __OBJC_$_PROP_LIST_RTTripParkingMetrics_$_RTCoreDataTransformable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_RTActionSuggestionActivityStatusProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_RTActionSuggestionActivityStatusProviding
+ __OBJC_$_PROTOCOL_REFS_RTActionSuggestionActivityStatusProviding
+ __OBJC_CATEGORY_PROTOCOLS_$_RTTripParkingMetrics_$_RTCoreDataTransformable
+ __OBJC_CLASS_RO_$_RTPOIHarvestContext
+ __OBJC_CLASS_RO_$_RTPOIHarvestTarget
+ __OBJC_CLASS_RO_$_RTTripParkingMetricsCalculator
+ __OBJC_CLASS_RO_$_RTTripParkingMetricsMO
+ __OBJC_CLASS_RO_$_RTTripParkingMetricsStore
+ __OBJC_LABEL_PROTOCOL_$_RTActionSuggestionActivityStatusProviding
+ __OBJC_METACLASS_RO_$_RTPOIHarvestContext
+ __OBJC_METACLASS_RO_$_RTPOIHarvestTarget
+ __OBJC_METACLASS_RO_$_RTTripParkingMetricsCalculator
+ __OBJC_METACLASS_RO_$_RTTripParkingMetricsMO
+ __OBJC_METACLASS_RO_$_RTTripParkingMetricsStore
+ __OBJC_PROTOCOL_$_RTActionSuggestionActivityStatusProviding
+ __PROTOCOLS_RTActionSuggestionActivityStatusProvider
+ ___116-[RTTripClusterManager _computeAndStoreTripParkingMetricsForDrivingSegment:sortedCommuteTrips:walkAndBikeTripStats:]_block_invoke
+ ___116-[RTTripClusterManager _computeAndStoreTripParkingMetricsForDrivingSegment:sortedCommuteTrips:walkAndBikeTripStats:]_block_invoke_2
+ ___51-[RTTripParkingMetricsStore getAllStoredCommuteIDs]_block_invoke
+ ___53-[RTTripParkingMetricsStore storeTripParkingMetrics:]_block_invoke
+ ___57-[RTPOIHarvester _harvestContextForAccessPoints:metrics:]_block_invoke
+ ___57-[RTPersistenceMirroringManager onExpiredRecordsRemoved:]_block_invoke
+ ___61-[RTTripParkingMetricsStore storeTripParkingMetrics:handler:]_block_invoke
+ ___62-[RTTripParkingMetricsStore _storeTripParkingMetrics:handler:]_block_invoke
+ ___62-[RTTripParkingMetricsStore getTripParkingMetricsWithOptions:]_block_invoke
+ ___63-[RTTripParkingMetricsStore getAllStoredCommuteIDsWithHandler:]_block_invoke
+ ___64-[RTTripParkingMetricsStore _getAllStoredCommuteIDsWithHandler:]_block_invoke
+ ___64-[RTTripParkingMetricsStore purgeTripParkingMetricsWithHandler:]_block_invoke
+ ___67-[RTTripClusterManager fetchTripParkingMetricsWithOptions:handler:]_block_invoke
+ ___67-[RTTripParkingMetricsStore deleteTripParkingMetricsWithCommuteID:]_block_invoke
+ ___72-[RTTripParkingMetricsStore fetchTripParkingMetricsWithContext:handler:]_block_invoke
+ ___72-[RTTripParkingMetricsStore fetchTripParkingMetricsWithOptions:handler:]_block_invoke
+ ___73-[RTTripParkingMetricsStore _fetchTripParkingMetricsWithContext:handler:]_block_invoke
+ ___75-[RTTripParkingMetricsStore deleteTripParkingMetricsWithCommuteID:handler:]_block_invoke
+ ___76-[RTTripParkingMetricsStore _deleteTripParkingMetricsWithCommuteID:handler:]_block_invoke
+ ___78-[RTTripParkingMetricsStore deleteExpiredTripParkingMetricsPredating:handler:]_block_invoke
+ ___82-[RTLearnedLocationEngine _harvestVisits:places:finerGranularityInferredMapItems:]_block_invoke
+ ___95+[RTExtendedTimeToLiveGate refreshMFeatureVerdictWithProvider:previousVerdict:defaultsManager:]_block_invoke
+ ___block_descriptor_48_e8_32s_e54_B24?0"NSObject<OS_dispatch_semaphore>"8"NSString"16l
+ ___block_descriptor_49_e8_32s_e20_v24?0q8"NSError"16l
+ ___block_descriptor_68_e8_32s40s_e17_v16?0"NSError"8l
+ _kRTTripParkingMetricsDefaultCirclingRadius_m
+ _kRTTripParkingMetricsUnknownDuration
+ _objc_msgSend$_applyCoreRoutineLocationClientState:
+ _objc_msgSend$_computeAndStoreTripParkingMetricsForDrivingSegment:sortedCommuteTrips:walkAndBikeTripStats:
+ _objc_msgSend$_deleteExpiredTripParkingMetricsPredating:handler:
+ _objc_msgSend$_deleteTripParkingMetricsWithCommuteID:handler:
+ _objc_msgSend$_fetchTripParkingMetricsWithContext:handler:
+ _objc_msgSend$_fetchTripParkingMetricsWithOptions:handler:
+ _objc_msgSend$_getAllStoredCommuteIDsWithHandler:
+ _objc_msgSend$_harvestVisits:places:finerGranularityInferredMapItems:
+ _objc_msgSend$_longTermExtendedReferenceDate:
+ _objc_msgSend$_purgeTripParkingMetricsWithHandler:
+ _objc_msgSend$_readCoreRoutineLocationClientState
+ _objc_msgSend$_recomputeExportingAvailability
+ _objc_msgSend$_refreshCloudSyncRetentionIntervals
+ _objc_msgSend$_storeTripParkingMetrics:handler:
+ _objc_msgSend$captureBugForReason:module:category:diagnosticsMask:additionalDescription:handler:
+ _objc_msgSend$circlingTime
+ _objc_msgSend$circlingTimeForSortedLocations:destinationLatitude:destinationLongitude:radius_m:tripEndDate:
+ _objc_msgSend$coreRoutineEnabledVerified
+ _objc_msgSend$createWithTripParkingMetricsMO:
+ _objc_msgSend$deleteExpiredTripParkingMetricsPredating:handler:
+ _objc_msgSend$deleteTripParkingMetricsWithCommuteID:handler:
+ _objc_msgSend$detailedDescriptionWithTriggerReason:
+ _objc_msgSend$fetchActivityStatusWithCompletion:
+ _objc_msgSend$fetchRequestFromStoredTripParkingMetricsOptions:inManagedObjectContext:
+ _objc_msgSend$fetchTripParkingMetricsWithOptions:handler:
+ _objc_msgSend$fingerprintLocations
+ _objc_msgSend$getAllStoredCommuteIDsWithHandler:
+ _objc_msgSend$harvestPOIs:visitLocations:visitEntryDate:visitExitDate:harvestType:error:
+ _objc_msgSend$harvestVisit:targets:harvestType:poiHarvester:error:
+ _objc_msgSend$initWithAccessPoints:fingerprintLocations:motionActivities:
+ _objc_msgSend$initWithCommuteID:timeID:circlingTime:walkingTime:expirationDate:
+ _objc_msgSend$initWithFeatureEnabled:trialManager:platform:defaultsManager:activityStatusProvider:
+ _objc_msgSend$initWithMapItem:source:
+ _objc_msgSend$initWithOrphanCountsByType:sampleOrphanedVisitIdentifiers:sampleOrphanedLOIIdentifiers:sampleUnexpectedFileExtensions:totalUnexpectedFilesDetected:executionDuration:
+ _objc_msgSend$initWithTripClusterStore:tripClusterCloudStore:tripClusterRouteStore:tripClusterRouteRoadTransitionsStore:tripClusterRecencyStore:tripClusterRecencyCloudStore:tripClusterScheduleStore:tripClusterScheduleCloudStore:tripSegmentRoadTransitionsStore:tripClusterWaypointStore:tripClusterWaypointCloudStore:tripClusterRouteSummaryStore:tripParkingMetricsStore:defaultsManager:bugCaptureManager:
+ _objc_msgSend$isParkingMetricsEnabled
+ _objc_msgSend$isTripClusterChildDataEligibleForCloudPush:
+ _objc_msgSend$isTripClusterEligibleForCloudPush:
+ _objc_msgSend$isTripClusterRecencyEligibleForCloudPush:
+ _objc_msgSend$managedObjectWithTripParkingMetrics:inManagedObjectContext:
+ _objc_msgSend$motionActivities
+ _objc_msgSend$readCoreRoutineLocationClientState
+ _objc_msgSend$refreshMFeatureVerdictWithProvider:previousVerdict:defaultsManager:
+ _objc_msgSend$runIsMultiDevice
+ _objc_msgSend$setCirclingTime:
+ _objc_msgSend$setCoreRoutineEnabledVerified:
+ _objc_msgSend$setRunIsMultiDevice:
+ _objc_msgSend$setWalkingTime:
+ _objc_msgSend$storeTripParkingMetrics:handler:
+ _objc_msgSend$totalUnexpectedFilesDetected
+ _objc_msgSend$tripParkingMetricsStore
+ _objc_msgSend$walkingTime
+ _objc_msgSend$walkingTimeAfterLastDriveForSortedCommuteTrips:walkTimeDurationAfterDrive_sec:
+ _symbolic _____ 14libcoreroutine40RTActionSuggestionActivityStatusProviderC
- +[RTAuthorizationManager readCoreRoutineLocationClientEnabled]
- +[RTExtendedTimeToLiveGate refreshMFeatureVerdictWithProvider:defaultsManager:]
- +[RTPOIHarvestUtilities harvestVisits:mapItem:harvestType:poiHarvester:error:]
- -[RTBGSystemTaskScheduler setEnableHealthChecks:]
- -[RTExtendedTimeToLiveGate initWithFeatureEnabled:trialManager:platform:defaultsManager:featureStatusProvider:]
- -[RTLearnedLocationEngine _harvestVisits:places:]
- -[RTPOIHarvester _harvestPOI:mapItemSource:accessPointArrays:referenceLocations:harvestType:metrics:error:]
- -[RTPOIHarvester _poiHarvestForAccessPoints:mapItem:referenceLocations:harvestType:metrics:]
- -[RTTripClusterDataStoresContainer initWithTripClusterStore:tripClusterCloudStore:tripClusterRouteStore:tripClusterRouteRoadTransitionsStore:tripClusterRecencyStore:tripClusterRecencyCloudStore:tripClusterScheduleStore:tripClusterScheduleCloudStore:tripSegmentRoadTransitionsStore:tripClusterWaypointStore:tripClusterWaypointCloudStore:tripClusterRouteSummaryStore:defaultsManager:bugCaptureManager:]
- -[RTTripClusterDataStoresContainer shouldTripClusterBePurged:]
- -[RTTripClusterDataStoresContainer shouldTripClusterChildDataBePurged:]
- -[RTTripClusterDataStoresContainer shouldTripClusterRecencyBePurged:]
- GCC_except_table215
- GCC_except_table226
- GCC_except_table233
- GCC_except_table236
- GCC_except_table238
- GCC_except_table251
- GCC_except_table253
- GCC_except_table255
- GCC_except_table258
- GCC_except_table262
- GCC_except_table267
- GCC_except_table269
- GCC_except_table272
- GCC_except_table281
- GCC_except_table284
- GCC_except_table286
- GCC_except_table290
- GCC_except_table311
- GCC_except_table313
- GCC_except_table315
- GCC_except_table319
- GCC_except_table322
- GCC_except_table324
- GCC_except_table326
- GCC_except_table330
- GCC_except_table334
- GCC_except_table337
- GCC_except_table339
- GCC_except_table96
- _OBJC_CLASS_$_RTActionSuggestionFeatureStatusProvider
- _OBJC_METACLASS_$_RTActionSuggestionFeatureStatusProvider
- __DATA_RTActionSuggestionFeatureStatusProvider
- __INSTANCE_METHODS_RTActionSuggestionFeatureStatusProvider
- __METACLASS_DATA_RTActionSuggestionFeatureStatusProvider
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_RTActionSuggestionFeatureStatusProviding
- __OBJC_$_PROTOCOL_METHOD_TYPES_RTActionSuggestionFeatureStatusProviding
- __OBJC_$_PROTOCOL_REFS_RTActionSuggestionFeatureStatusProviding
- __OBJC_LABEL_PROTOCOL_$_RTActionSuggestionFeatureStatusProviding
- __OBJC_PROTOCOL_$_RTActionSuggestionFeatureStatusProviding
- __PROTOCOLS_RTActionSuggestionFeatureStatusProvider
- ___49-[RTLearnedLocationEngine _harvestVisits:places:]_block_invoke
- ___79+[RTExtendedTimeToLiveGate refreshMFeatureVerdictWithProvider:defaultsManager:]_block_invoke
- ___92-[RTPOIHarvester _poiHarvestForAccessPoints:mapItem:referenceLocations:harvestType:metrics:]_block_invoke
- _objc_msgSend$_harvestVisits:places:
- _objc_msgSend$fetchFeatureStatusWithCompletion:
- _objc_msgSend$harvestVisits:mapItem:harvestType:poiHarvester:error:
- _objc_msgSend$initWithFeatureEnabled:trialManager:platform:defaultsManager:featureStatusProvider:
- _objc_msgSend$initWithOrphanCountsByType:sampleOrphanedVisitIdentifiers:sampleOrphanedLOIIdentifiers:sampleUnexpectedFileExtensions:executionDuration:
- _objc_msgSend$initWithTripClusterStore:tripClusterCloudStore:tripClusterRouteStore:tripClusterRouteRoadTransitionsStore:tripClusterRecencyStore:tripClusterRecencyCloudStore:tripClusterScheduleStore:tripClusterScheduleCloudStore:tripSegmentRoadTransitionsStore:tripClusterWaypointStore:tripClusterWaypointCloudStore:tripClusterRouteSummaryStore:defaultsManager:bugCaptureManager:
- _objc_msgSend$readCoreRoutineLocationClientEnabled
- _objc_msgSend$refreshMFeatureVerdictWithProvider:defaultsManager:
- _objc_msgSend$shouldTripClusterBePurged:
- _objc_msgSend$shouldTripClusterChildDataBePurged:
- _objc_msgSend$shouldTripClusterRecencyBePurged:
- _symbolic _____ 14libcoreroutine39RTActionSuggestionFeatureStatusProviderC
CStrings:
+ "%@, %@, CoreRoutine client read was indeterminate; retaining last confirmed value, %{public}@, term left unverified"
+ "%@, %@, CoreRoutine's location client state, %{public}@"
+ "%@, %@, CoreRoutine, %{public}@"
+ "%@, %@, Detected %lu orphaned relationships and %lu unexpected files; RBC to be invoked"
+ "%@, %@, Location Services, %{public}@"
+ "%@, %@, Location services enabled, %{public}@"
+ "%@, %@, cached auth state from defaults, Location Services, %{public}@, CoreRoutine, %{public}@, enabled, %{public}@"
+ "%@, %@, read results, Location Services, %{public}@, CoreRoutine client, %{public}@"
+ "%@, %@, refreshed after CLAppResetChangedNotification, enabled, %{public}@"
+ "%@, %@, refreshed after CLAuthorizationStatusChangedNotification, Location Services, %{public}@, CoreRoutine verified, %{public}@"
+ "%@, %@, supported, %{public}@, Location Services, %{public}@, CoreRoutine, %{public}@, verified, %{public}@, enabled, %{public}@"
+ "%@, account is not single-iPhone, submitting with the multi-device outcome bit"
+ "%@, device check failed, retrying on the failure back-off, error, %@"
+ "%@, encountered error during metadata reset request for %lu object IDs, error, %@"
+ "%@, expiration cutoff, %{public}@, place type inference cutoff, %{public}@"
+ "%@, exporting available, %{public}@"
+ "%@, failed to check for expired records, suspending export, error, %@"
+ "%@, harvested visit, %{sensitive}@, primary mapItem, %{sensitive}@, finergranularity mapItem, %{sensitive}@, success, %{public}@, error, %{public}@"
+ "%@, managedObject, %@, is not supported by RTTripParkingMetrics+CoreDataReadable (in %s:%d)"
+ "%@, successfully submitted metadata reset request for %lu object IDs"
+ "%@, timed out waiting for %{public}@, error, %@"
+ "%@,%@,Error fetching all trip IDs: %@"
+ "%@,%@,Semaphore timeout fetching all trip IDs: %@"
+ "%@,%@,_isParkingMetricsEnabled,%{public}d,internalInstall,%{public}d,featureFlag,%{public}d"
+ "%@,%@,commuteID,%@,fetched count,%lu,error,%@"
+ "%@,%@,parking metrics are not enabled"
+ "%@,%@,purging entries expiring before,%@"
+ "%@,Error creating RTTripParkingMetrics from tripParkingMetricsMO"
+ "%@,Error deleting trip parking metrics for commuteID,%@,error,%@"
+ "%@,Error fetching locations for parking metrics,skipping,commuteID,%@,error,%@"
+ "%@,Error fetching trip parking metrics for commuteID,%@,error,%@"
+ "%@,Error purging expired trip parking metrics,%@"
+ "%@,Error storing trip parking metrics,%@"
+ "%@,Error storing trip parking metrics,commuteID,%@,error,%@"
+ "%@,Error storing trip parking metrics,error,%@"
+ "%@,Error,missing commuteID in options. This will fetch all trip parking metrics"
+ "%@,Negative walking time after last drive,walkTimeAfterDrive,%.1f,walkTimeBetweenDrives,%.1f"
+ "%@,Semaphore Error fetching trip parking metrics for commuteID,%@,error,%@"
+ "%@,Semaphore Error storing trip parking metrics,error,%@"
+ "%@,Semaphore error deleting trip parking metrics for commuteID,%@,error,%@"
+ "%@,Skipping cluster not eligible for cloud push: %@"
+ "%@,Skipping cluster update not eligible for cloud push: %@"
+ "%@,Skipping recency not eligible for cloud push: %@"
+ "%@,Skipping schedule not eligible for cloud push: %@"
+ "%@,Skipping schedule update not eligible for cloud push: %@"
+ "%@,Skipping waypoint cluster not eligible for cloud push: %@"
+ "%@,Stored trip parking metrics,commuteID,%@,timeID,%d,circlingTime,%f,walkingTime,%f"
+ "%@,cloud sync retention,useGatedRetention,%d,interval,%.0f,shortInterval,%.0f"
+ "%@:%@ no CoreRoutine location entity registered; cached routineEnabled=%{public}@ locally, will reconcile on next CLAppResetChangedNotification"
+ "%lu unexpected files detected"
+ "%lu unexpected files detected (%@)"
+ "%{public}@, %{public}@, No valid map item provided, exiting early"
+ "%{public}@, mFeature fetch failed, holding previous verdict, error, %{public}@"
+ "%{public}@, mFeature verdict unchanged, %{public}@"
+ "+[RTTripParkingMetrics(RTCoreDataTransformable) createWithManagedObject:]"
+ "-[RTTripClusterManager fetchTripParkingMetricsWithOptions:handler:]"
+ "-[RTTripParkingMetricsStore _deleteExpiredTripParkingMetricsPredating:handler:]"
+ "-[RTTripParkingMetricsStore _deleteTripParkingMetricsWithCommuteID:handler:]"
+ "-[RTTripParkingMetricsStore _fetchTripParkingMetricsWithContext:handler:]"
+ "-[RTTripParkingMetricsStore _fetchTripParkingMetricsWithOptions:handler:]"
+ "-[RTTripParkingMetricsStore _getAllStoredCommuteIDsWithHandler:]"
+ "-[RTTripParkingMetricsStore getAllStoredCommuteIDsWithHandler:]"
+ "-[RTTripParkingMetricsStore storeTripParkingMetrics:handler:]"
+ "03:44:07"
+ "AUTHORIZED"
+ "B24@?0@\"NSObject<OS_dispatch_semaphore>\"8@\"NSString\"16"
+ "CoreRoutine enabled, %{public}@"
+ "DENIED"
+ "INDETERMINATE"
+ "Invalid parameter not satisfying: lastPhysicalDrivingSegment"
+ "Invalid parameter not satisfying: tripParkingMetrics"
+ "Invalid parameter not satisfying: tripParkingMetrics (in %s:%d)"
+ "Invalid parameter not satisfying: tripParkingMetricsMO.commuteID"
+ "Location services enabled, %{public}@"
+ "Oct 29 2026"
+ "Parking metrics are not enabled"
+ "RTAuthorizationManagerCoreRoutineClientStateOverride"
+ "RTDefaultsTripClusterCloudSyncUseExtendedRetention"
+ "RTDefaultsTripSegmentParkingMetricsEnabled"
+ "RTPersistenceExpirationEnforcerDidRemoveExpiredRecordsNotificationName"
+ "RTTripParkingMetricsMO"
+ "TimeToPark"
+ "UNKNOWN"
+ "remove expired records"
+ "remove learned place type inferences"
+ "remove unreferenced map items"
+ "remove unreferenced places"
+ "set routine enabled to %{public}@"
+ "update routine enabled to %{public}@"
- "%@, %@, CoreRoutine's location client enabled, %@"
- "%@, %@, CoreRoutine, %@"
- "%@, %@, Detected %lu orphaned relationships; RBC to be invoked"
- "%@, %@, Location Services, %@"
- "%@, %@, Location services enabled, %@"
- "%@, %@, cached auth state from defaults, Location Services, %@, CoreRoutine, %@, enabled, %@"
- "%@, %@, refreshed after CLAppResetChangedNotification, enabled, %@"
- "%@, %@, refreshed after CLAuthorizationStatusChangedNotification, Location Services, %@"
- "%@, %@, supported, %@, Location Services, %@, CoreRoutine, %@, enabled, %@"
- "%@, account has a device other than an iPhone, or the device fetch failed, skipping, error, %@"
- "%@, encountered error during metadata reset request with object IDs %@s, error, %@"
- "%@, successfully submitted metadata reset request for %lu object IDs, %@"
- "%@,Skipping purge-eligible cluster: %@"
- "%@,Skipping purge-eligible recency: %@"
- "%@,Skipping purge-eligible schedule: %@"
- "%@,Skipping purge-eligible waypoint cluster: %@"
- "%@:%@ no CoreRoutine location entity registered; cached routineEnabled=%@ locally, will reconcile on next CLAppResetChangedNotification"
- "%{public}@, mFeature indeterminate, holding previous verdict, error, %{public}@"
- "20:25:43"
- "CoreRoutine enabled, %@"
- "Location services enabled, %@"
- "Oct  3 2026"
- "harvested %lu visits, mapItem, %{sensitive}@, success, %{public}@, error, %{public}@"
- "set routine enabled to %@"
- "unexpected files detected (%@)"
- "update routine enabled to %@"
```
