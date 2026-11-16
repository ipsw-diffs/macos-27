## ProactiveSummarization

> `/System/Library/PrivateFrameworks/ProactiveSummarization.framework/Versions/A/ProactiveSummarization`

```diff

-1354.3.8.0.0
-  __TEXT.__text: 0x18b738
-  __TEXT.__objc_methlist: 0x6d4
-  __TEXT.__const: 0x12e30
-  __TEXT.__dlopen_cstrs: 0xaa
-  __TEXT.__cstring: 0x9ea7
-  __TEXT.__swift5_typeref: 0x4908
-  __TEXT.__swift5_reflstr: 0x42ad
+1354.3.14.0.0
+  __TEXT.__text: 0x18d878
+  __TEXT.__objc_methlist: 0x82c
+  __TEXT.__const: 0x12b90
+  __TEXT.__dlopen_cstrs: 0xf9
+  __TEXT.__cstring: 0xb96e
+  __TEXT.__swift5_typeref: 0x48fc
+  __TEXT.__swift5_reflstr: 0x424d
   __TEXT.__swift5_assocty: 0x480
-  __TEXT.__constg_swiftt: 0x3c10
-  __TEXT.__swift5_fieldmd: 0x48c4
-  __TEXT.__swift5_proto: 0xd64
-  __TEXT.__swift5_types: 0x584
+  __TEXT.__constg_swiftt: 0x3b20
+  __TEXT.__swift5_fieldmd: 0x47d0
+  __TEXT.__swift5_proto: 0xd28
+  __TEXT.__swift5_types: 0x588
   __TEXT.__swift5_protos: 0x4c
-  __TEXT.__swift5_capture: 0x341c
-  __TEXT.__oslogstring: 0x70e8
-  __TEXT.__swift_as_entry: 0x5c0
-  __TEXT.__swift_as_ret: 0x7fc
-  __TEXT.__swift_as_cont: 0xc00
-  __TEXT.__swift5_builtin: 0x12c
-  __TEXT.__swift5_mpenum: 0x74
-  __TEXT.__gcc_except_tab: 0x100
-  __TEXT.__unwind_info: 0x7d50
-  __TEXT.__eh_frame: 0x10ec0
+  __TEXT.__swift5_capture: 0x3be8
+  __TEXT.__oslogstring: 0x73fc
+  __TEXT.__swift_as_entry: 0x594
+  __TEXT.__swift_as_ret: 0x7d0
+  __TEXT.__swift_as_cont: 0xbb8
+  __TEXT.__swift5_builtin: 0x118
+  __TEXT.__swift5_mpenum: 0x60
+  __TEXT.__gcc_except_tab: 0x10c
+  __TEXT.__unwind_info: 0x7c98
+  __TEXT.__eh_frame: 0x107e0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x208
-  __DATA_CONST.__objc_classlist: 0x188
+  __DATA_CONST.__const: 0x248
+  __DATA_CONST.__objc_classlist: 0x198
   __DATA_CONST.__objc_catlist: 0x10
-  __DATA_CONST.__objc_protolist: 0xe0
+  __DATA_CONST.__objc_protolist: 0xe8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xef0
+  __DATA_CONST.__objc_selrefs: 0x1098
   __DATA_CONST.__objc_protorefs: 0x70
   __DATA_CONST.__objc_superrefs: 0x20
   __DATA_CONST.__got: 0x1148
-  __AUTH_CONST.__const: 0xff08
-  __AUTH_CONST.__cfstring: 0x1c0
-  __AUTH_CONST.__objc_const: 0x3d68
-  __AUTH_CONST.__auth_got: 0x1dc8
+  __AUTH_CONST.__const: 0x11ab8
+  __AUTH_CONST.__cfstring: 0x300
+  __AUTH_CONST.__objc_const: 0x3ef8
+  __AUTH_CONST.__auth_got: 0x1de0
   __AUTH.__objc_data: 0x398
-  __AUTH.__data: 0xe58
-  __DATA.__objc_ivar: 0x20
-  __DATA.__data: 0x1b38
-  __DATA.__bss: 0x19ea0
-  __DATA.__common: 0xc0
+  __AUTH.__data: 0xdb8
+  __DATA.__objc_ivar: 0x30
+  __DATA.__data: 0x1b48
+  __DATA.__bss: 0x196d0
+  __DATA.__common: 0xb8
   __DATA_DIRTY.__objc_data: 0x350
-  __DATA_DIRTY.__data: 0x28a0
-  __DATA_DIRTY.__bss: 0x1630
-  __DATA_DIRTY.__common: 0x310
+  __DATA_DIRTY.__data: 0x28c0
+  __DATA_DIRTY.__bss: 0x1580
+  __DATA_DIRTY.__common: 0x308
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11117
-  Symbols:   3700
-  CStrings:  1346
+  Functions: 11299
+  Symbols:   3781
+  CStrings:  1469
 
Symbols:
+ +[PSULocationProvider stopMonitoringIfRegistered]
+ -[PSULocationProvider locationManager:didFailWithError:]
+ -[PSULocationProvider locationManager:didUpdateLocations:]
+ -[PSULocationProvider locationManager:didVisit:]
+ -[PSULocationProvider locationManagerDidChangeAuthorization:]
+ -[PSULocationProvider makeRoutineManager]
+ -[PSULocationProvider report:place:]
+ -[PSULocationProvider reportCurrentPlace]
+ -[PSULocationProvider reportPlaceAtLocation:event:arrival:]
+ -[PSULocationProvider requestFixIfAllowed]
+ -[PSULocationProvider startMonitoringPlaceWithHandler:]
+ -[PSULocationProvider stopMonitoringPlace]
+ GCC_except_table24
+ GCC_except_table39
+ GCC_except_table55
+ GCC_except_table76
+ GCC_except_table77
+ GCC_except_table8
+ GCC_except_table87
+ GCC_except_table89
+ GCC_except_table91
+ _CoreLocationLibraryCore
+ _CoreLocationLibraryCore.frameworkLibrary
+ _OBJC_CLASS_$_NSJSONSerialization
+ _OBJC_IVAR_$_PSULocationProvider._generation
+ _OBJC_IVAR_$_PSULocationProvider._handler
+ _OBJC_IVAR_$_PSULocationProvider._locationManager
+ _OBJC_IVAR_$_PSULocationProvider._queue
+ _OUTLINED_FUNCTION_527
+ __DATA__TtC22ProactiveSummarization18ContextSignalStore
+ __DATA__TtC22ProactiveSummarization30NotificationPipelineEventStore
+ __IVARS__TtC22ProactiveSummarization18ContextSignalStore
+ __IVARS__TtC22ProactiveSummarization30NotificationPipelineEventStore
+ __METACLASS_DATA__TtC22ProactiveSummarization18ContextSignalStore
+ __METACLASS_DATA__TtC22ProactiveSummarization30NotificationPipelineEventStore
+ __OBJC_$_CLASS_METHODS_PSULocationProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CLLocationManagerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CLLocationManagerDelegate
+ __OBJC_$_PROTOCOL_REFS_CLLocationManagerDelegate
+ __OBJC_CLASS_PROTOCOLS_$_PSULocationProvider
+ __OBJC_LABEL_PROTOCOL_$_CLLocationManagerDelegate
+ __OBJC_PROTOCOL_$_CLLocationManagerDelegate
+ ___41-[PSULocationProvider reportCurrentPlace]_block_invoke
+ ___41-[PSULocationProvider reportCurrentPlace]_block_invoke_2
+ ___42-[PSULocationProvider stopMonitoringPlace]_block_invoke
+ ___49+[PSULocationProvider stopMonitoringIfRegistered]_block_invoke
+ ___55-[PSULocationProvider startMonitoringPlaceWithHandler:]_block_invoke
+ ___59-[PSULocationProvider reportPlaceAtLocation:event:arrival:]_block_invoke
+ ___59-[PSULocationProvider reportPlaceAtLocation:event:arrival:]_block_invoke_2
+ ___CoreLocationLibraryCore_block_invoke
+ ___block_descriptor_40_e8_32s_e5_v8?0l
+ ___block_descriptor_48_e8_32s40bs_e5_v8?0l
+ ___block_descriptor_48_e8_32s_e5_v8?0lu40l8
+ ___block_descriptor_72_e8_32s40s48s_e29_v24?0"NSArray"8"NSError"16l
+ ___block_descriptor_72_e8_32s40s48s_e42_v24?0"RTLocationOfInterest"8"NSError"16l
+ ___block_descriptor_88_e8_32s40s48s56s64s_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s64s
+ ___destroy_helper_block_e8_32s40s48s56s64s
+ ___getCLLocationClass_block_invoke
+ ___getCLLocationManagerClass_block_invoke
+ ___swift_closure_destructor.28Tm
+ ___swift_closure_destructor.558Tm
+ ___swift_closure_destructor.662Tm
+ ___swift_closure_destructor.79Tm
+ ___swift_closure_destructor.88Tm
+ ___swift_memcpy145_8
+ ___unnamed_24
+ _audit_stringCoreLocation
+ _dispatch_async
+ _dispatch_queue_attr_make_with_autorelease_frequency
+ _dispatch_queue_attr_make_with_qos_class
+ _dispatch_queue_create
+ _getCLLocationClass.softClass
+ _getCLLocationManagerClass
+ _getCLLocationManagerClass.softClass
+ _get_enum_tag_for_layout_string 10Foundation4DataV15_RepresentationO
+ _get_enum_tag_for_layout_string 10Foundation4DataVSg
+ _objc_msgSend$addUpdateHandlerForNamespaceName:usingBlock:
+ _objc_msgSend$arrivalDate
+ _objc_msgSend$authorizationStatus
+ _objc_msgSend$contentsOfDirectoryAtPath:error:
+ _objc_msgSend$coordinate
+ _objc_msgSend$dataWithJSONObject:options:error:
+ _objc_msgSend$departureDate
+ _objc_msgSend$dictionaryForKey:
+ _objc_msgSend$distantFuture
+ _objc_msgSend$distantPast
+ _objc_msgSend$fetchLocationOfInterestAtLocation:withHandler:
+ _objc_msgSend$getDoubleAsNSNumberForColumnName:table:
+ _objc_msgSend$getNSStringForColumnName:table:
+ _objc_msgSend$horizontalAccuracy
+ _objc_msgSend$initWithCoordinate:altitude:horizontalAccuracy:verticalAccuracy:timestamp:
+ _objc_msgSend$initWithEffectiveBundlePath:delegate:onQueue:
+ _objc_msgSend$isEqualToDate:
+ _objc_msgSend$isValidJSONObject:
+ _objc_msgSend$lastObject
+ _objc_msgSend$location
+ _objc_msgSend$makeRoutineManager
+ _objc_msgSend$mutableCopy
+ _objc_msgSend$numberWithInt:
+ _objc_msgSend$numberWithInteger:
+ _objc_msgSend$objectForKeyedSubscript:
+ _objc_msgSend$refresh
+ _objc_msgSend$removeItemAtPath:error:
+ _objc_msgSend$report:place:
+ _objc_msgSend$reportCurrentPlace
+ _objc_msgSend$reportPlaceAtLocation:event:arrival:
+ _objc_msgSend$requestFixIfAllowed
+ _objc_msgSend$requestLocation
+ _objc_msgSend$setBool:forKey:
+ _objc_msgSend$setDesiredAccuracy:
+ _objc_msgSend$setObject:forKeyedSubscript:
+ _objc_msgSend$standardUserDefaults
+ _objc_msgSend$startMonitoringPlaceWithHandler:
+ _objc_msgSend$startMonitoringVisits
+ _objc_msgSend$stopMonitoringIfRegistered
+ _objc_msgSend$stopMonitoringPlace
+ _objc_msgSend$stopMonitoringVisits
+ _objc_msgSend$stringByDeletingLastPathComponent
+ _objc_msgSend$timeIntervalSinceNow
+ _objc_msgSend$userVersion
+ _objc_msgSend$writeTransaction:
+ _objc_retainBlock
+ _swift_isUniquelyReferenced_nonNull
+ _symbolic Ig_
+ _symbolic SDySSSay_____GG 10Foundation4DataV
+ _symbolic SDySSypGSg
+ _symbolic SaySay_____GG 22ProactiveSummarization19ContextSignalLoggerC10UsageEventV
+ _symbolic Say_____G 10Foundation4DataV
+ _symbolic Say_____G 22ProactiveSummarization24ContextSignalDeliveryRowV
+ _symbolic ScCySDySSSay_____GG_____G 10Foundation4DataV s5NeverO
+ _symbolic ScSy_____G 22ProactiveSummarization16PlaceObservationV
+ _symbolic So24PSUSummarizationPipelineCXDXMT
+ _symbolic So9TRIClientC
+ _symbolic _____ 22ProactiveSummarization12AssetManagerC14ConstantsCache025_A9C24845A2E6CB3ACCF47514J6E7FB6DLLV
+ _symbolic _____ 22ProactiveSummarization18ContextSignalStoreC
+ _symbolic _____ 22ProactiveSummarization19VisitLocationSourceV
+ _symbolic _____ 22ProactiveSummarization24ContextSignalDeliveryRowV
+ _symbolic _____ 22ProactiveSummarization30NotificationPipelineEventStoreC
+ _symbolic _____Sg 10Foundation4DataV
+ _symbolic _____Sg 22ProactiveSummarization19ContextSignalLoggerC
+ _symbolic _____Sg 22ProactiveSummarization24ContextSignalDeliveryRowV
+ _symbolic _____Sg 22ProactiveSummarization30NotificationPipelineEventStoreC
+ _symbolic _____XDXMT 22ProactiveSummarization30NotificationPipelineEventStoreC
+ _symbolic _____ySSSay_____GG s17_NativeDictionaryV 10Foundation4DataV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation4DataV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 22ProactiveSummarization24ContextSignalDeliveryRowV
+ _symbolic _____y_____Sg_____G s13ManagedBufferCsRi__rlE 22ProactiveSummarization30NotificationPipelineEventStoreC So16os_unfair_lock_sV
+ _symbolic _____y______G ScS12ContinuationV 22ProactiveSummarization16PlaceObservationV
+ _symbolic _____y______G ScS8IteratorV 22ProactiveSummarization16PlaceObservationV
+ _symbolic _____y_______G ScS12ContinuationV11YieldResultO 22ProactiveSummarization16PlaceObservationV
+ _symbolic _____y_______G ScS12ContinuationV15BufferingPolicyO 22ProactiveSummarization16PlaceObservationV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 22ProactiveSummarization12AssetManagerC14ConstantsCache025_A9C24845A2E6CB3ACCF47514L6E7FB6DLLV So16os_unfair_lock_sV
+ _symbolic xIgr_
+ _type_layout_string 22ProactiveSummarization12AssetManagerC14ConstantsCache025_A9C24845A2E6CB3ACCF47514J6E7FB6DLLV
+ _type_layout_string 22ProactiveSummarization19VisitLocationSourceV
+ _type_layout_string 22ProactiveSummarization24ContextSignalDeliveryRowV
- -[PSULocationProvider fetchCurrentPlaceWithinWindow:completion:]
- -[PSULocationProvider isAvailable]
- -[PSULocationProvider routineManager]
- -[PSULocationProvider startMonitoringSettledStateWithHandler:]
- -[PSULocationProvider stopMonitoringSettledState]
- GCC_except_table14
- GCC_except_table32
- GCC_except_table56
- GCC_except_table57
- GCC_except_table68
- GCC_except_table70
- GCC_except_table72
- _OUTLINED_FUNCTION_523
- _OUTLINED_FUNCTION_637
- _OUTLINED_FUNCTION_638
- ___62-[PSULocationProvider startMonitoringSettledStateWithHandler:]_block_invoke
- ___64-[PSULocationProvider fetchCurrentPlaceWithinWindow:completion:]_block_invoke
- ___block_descriptor_48_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16l
- ___block_descriptor_48_e8_32s40bs_e39_v24?0"RTScenarioTrigger"8"NSError"16l
- ___swift_closure_destructor.111Tm
- ___swift_closure_destructor.26Tm
- ___swift_closure_destructor.556Tm
- ___swift_closure_destructor.660Tm
- ___swift_closure_destructor.77Tm
- ___swift_closure_destructor.86Tm
- ___swift_closure_destructor.95Tm
- ___unnamed_34
- __os_log_debug_impl
- _associated conformance 22ProactiveSummarization18ContextSignalStoreV10CodingKeys33_5D9C3894D823D7FE9D90BDD1F5A72004LLOSHAASQ
- _associated conformance 22ProactiveSummarization18ContextSignalStoreV10CodingKeys33_5D9C3894D823D7FE9D90BDD1F5A72004LLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 22ProactiveSummarization18ContextSignalStoreV10CodingKeys33_5D9C3894D823D7FE9D90BDD1F5A72004LLOs0F3KeyAAs28CustomDebugStringConvertible
- _associated conformance 22ProactiveSummarization21DeliveredNotificationV10CodingKeys33_5D9C3894D823D7FE9D90BDD1F5A72004LLOSHAASQ
- _associated conformance 22ProactiveSummarization21DeliveredNotificationV10CodingKeys33_5D9C3894D823D7FE9D90BDD1F5A72004LLOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 22ProactiveSummarization21DeliveredNotificationV10CodingKeys33_5D9C3894D823D7FE9D90BDD1F5A72004LLOs0E3KeyAAs28CustomDebugStringConvertible
- _get_enum_tag_for_layout_string 22ProactiveSummarization24ContextSignalPersistenceV10LoadResultO
- _objc_msgSend$createDirectoryAtURL:withIntermediateDirectories:attributes:error:
- _objc_msgSend$dateByAddingTimeInterval:
- _objc_msgSend$fetchCurrentPlaceWithinWindow:completion:
- _objc_msgSend$firstObject
- _objc_msgSend$routineManager
- _objc_msgSend$startMonitoringScenarioTriggerOfType:withHandler:
- _objc_msgSend$startMonitoringSettledStateWithHandler:
- _objc_msgSend$stopMonitoringScenarioTriggerOfType:
- _objc_msgSend$stopMonitoringSettledState
- _objc_msgSend$stringWithFormat:
- _objc_msgSend$timeIntervalSinceDate:
- _symbolic SDySSSdG
- _symbolic ScCySo15PSUPlaceContextCSg_____G s5NeverO
- _symbolic ScCy_____SgSg_____G 22ProactiveSummarization16PlaceObservationV s5NeverO
- _symbolic ScCy_____SgSg_____GSg 22ProactiveSummarization16PlaceObservationV s5NeverO
- _symbolic ScSySbG
- _symbolic So15PSUPlaceContextCSg
- _symbolic _____ 10Foundation3URLV
- _symbolic _____ 22ProactiveSummarization18ContextSignalStoreV
- _symbolic _____ 22ProactiveSummarization18ContextSignalStoreV10CodingKeys33_5D9C3894D823D7FE9D90BDD1F5A72004LLO
- _symbolic _____ 22ProactiveSummarization21DeliveredNotificationV10CodingKeys33_5D9C3894D823D7FE9D90BDD1F5A72004LLO
- _symbolic _____ 22ProactiveSummarization24ContextSignalPersistenceV
- _symbolic _____ 22ProactiveSummarization24ContextSignalPersistenceV10LoadResultO
- _symbolic _____ 22ProactiveSummarization25CoreRoutineLocationSourceV
- _symbolic _____SgIeghHr_ 22ProactiveSummarization16PlaceObservationV
- _symbolic _____SgSg 22ProactiveSummarization16PlaceObservationV
- _symbolic _____ySSSdG s17_NativeDictionaryV
- _symbolic _____ySSSdG s18_DictionaryStorageC
- _symbolic _____ySb_G ScS12ContinuationV
- _symbolic _____ySb_G ScS8IteratorV
- _symbolic _____ySb__G ScS12ContinuationV11YieldResultO
- _symbolic _____ySb__G ScS12ContinuationV15BufferingPolicyO
- _symbolic _____ySdSgG s23_ContiguousArrayStorageC
- _symbolic _____y_____G s22KeyedDecodingContainerV 22ProactiveSummarization18ContextSignalStoreV10CodingKeys33_5D9C3894D823D7FE9D90BDD1F5A72004LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 22ProactiveSummarization21DeliveredNotificationV10CodingKeys33_5D9C3894D823D7FE9D90BDD1F5A72004LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 22ProactiveSummarization18ContextSignalStoreV10CodingKeys33_5D9C3894D823D7FE9D90BDD1F5A72004LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 22ProactiveSummarization21DeliveredNotificationV10CodingKeys33_5D9C3894D823D7FE9D90BDD1F5A72004LLO
- _symbolic _____y_____SgSgG 22ProactiveSummarization12DeadlineGate33_3F73588C3A92FB599084710CA662C71CLLC AA16PlaceObservationV
- _type_layout_string 22ProactiveSummarization18ContextSignalStoreV
- _type_layout_string 22ProactiveSummarization24ContextSignalPersistenceV10LoadResultO
- _type_layout_string 22ProactiveSummarization25CoreRoutineLocationSourceV
CStrings:
+ " AND deliveryMode IS NOT :deliveryMode))"
+ " ORDER BY deliveredAt DESC, rowid DESC LIMIT 1"
+ " THEN :deliveryMode ELSE deliveryMode END WHERE id = :id AND (biomeNotificationId IS NOT :biomeNotificationId OR receivedAt IS NULL OR receivedAt > :receivedAt OR ("
+ "/System/Library/Frameworks/CoreLocation.framework/Contents/MacOS/CoreLocation"
+ "/System/Library/PrivateFrameworks/CoreParsec.framework"
+ "0`"
+ ":biomeNotificationId"
+ ":cursor"
+ ":deliveredAt"
+ ":deliveryMode"
+ ":deliveryMode IS NOT NULL AND (deliveryMode IS NULL OR deliveryMode = :replaceableMode)"
+ ":event"
+ ":high"
+ ":id"
+ ":ids"
+ ":key"
+ ":low"
+ ":notificationDate"
+ ":outcome"
+ ":receivedAt"
+ ":replaceableMode"
+ ":signals"
+ ":spotlightIdentifier"
+ ":spotlightIdentifiers"
+ ":time"
+ "AND biomeNotificationId IS NULL"
+ "CLLocation"
+ "CLLocationManager"
+ "CREATE INDEX IF NOT EXISTS contextSignalDelivery_biomeNotificationId ON contextSignalDelivery(biomeNotificationId)"
+ "CREATE INDEX IF NOT EXISTS contextSignalDelivery_bundleId_notificationDate ON contextSignalDelivery(bundleId, notificationDate)"
+ "CREATE INDEX IF NOT EXISTS contextSignalDelivery_deliveredAt ON contextSignalDelivery(deliveredAt)"
+ "CREATE INDEX IF NOT EXISTS contextSignalGestureStart_time ON contextSignalGestureStart(time)"
+ "CREATE INDEX IF NOT EXISTS contextSignalLoggedEvent_time ON contextSignalLoggedEvent(time)"
+ "CREATE INDEX IF NOT EXISTS notificationPipelineEvent_spotlightIdentifier ON notificationPipelineEvent(spotlightIdentifier)"
+ "CREATE INDEX IF NOT EXISTS notificationPipelineEvent_timestamp ON notificationPipelineEvent(timestamp)"
+ "CREATE TABLE IF NOT EXISTS contextSignalCursor (pk INTEGER PRIMARY KEY CHECK (pk = 1), cursor REAL NOT NULL)"
+ "CREATE TABLE IF NOT EXISTS contextSignalDelivery (id TEXT PRIMARY KEY, bundleId TEXT NOT NULL, threadId TEXT, notificationDate REAL NOT NULL, deliveredAt REAL NOT NULL, signals BLOB NOT NULL, biomeNotificationId TEXT, receivedAt REAL, deliveryMode TEXT, outcome BLOB, outcomeLogged INTEGER NOT NULL DEFAULT 0)"
+ "CREATE TABLE IF NOT EXISTS contextSignalGestureStart (biomeNotificationId TEXT PRIMARY KEY, time REAL NOT NULL)"
+ "CREATE TABLE IF NOT EXISTS contextSignalLoggedEvent (key TEXT PRIMARY KEY, time REAL NOT NULL)"
+ "CREATE TABLE IF NOT EXISTS notificationPipelineEvent (pk INTEGER PRIMARY KEY AUTOINCREMENT, spotlightIdentifier TEXT NOT NULL, timestamp REAL NOT NULL, event BLOB NOT NULL)"
+ "Context signal %{public}s not decoded: %{public}@"
+ "Context signal %{public}s not encoded: %{public}@"
+ "Context signals off: the pipeline database has no context signal tables"
+ "ContextSignalsLastLocationRequest"
+ "ContextSignalsLastPlace"
+ "ContextSignalsVisitMonitoringRegistered"
+ "Creating the notification pipeline event table, which migration 15 didn't create"
+ "DELETE FROM contextSignalDelivery WHERE id IN _pas_nsarray(:ids)"
+ "DELETE FROM contextSignalGestureStart WHERE time < :threshold"
+ "DELETE FROM contextSignalLoggedEvent WHERE time < :threshold"
+ "DELETE FROM notificationPipelineEvent ORDER BY timestamp DESC, pk DESC LIMIT -1 OFFSET :offset"
+ "DELETE FROM notificationPipelineEvent WHERE timestamp < :threshold"
+ "INSERT INTO notificationPipelineEvent (spotlightIdentifier, timestamp, event) VALUES (:spotlightIdentifier, :timestamp, :event)"
+ "INSERT OR IGNORE INTO contextSignalDelivery (id, bundleId, threadId, notificationDate, deliveredAt, biomeNotificationId, signals) VALUES (:id, :bundleId, :threadId, :notificationDate, :deliveredAt, :biomeNotificationId, :signals)"
+ "INSERT OR REPLACE INTO contextSignalCursor (pk, cursor) VALUES (1, :cursor)"
+ "INSERT OR REPLACE INTO contextSignalGestureStart (biomeNotificationId, time) VALUES (:biomeNotificationId, :time)"
+ "INSERT OR REPLACE INTO contextSignalLoggedEvent (key, time) VALUES (:key, :time)"
+ "NotificationOutcome"
+ "NotificationSignals"
+ "PSULocationProvider: %{public}s at %{private}@ (looked up in %.2fs)"
+ "PSULocationProvider: CoreLocation or CoreRoutine unavailable"
+ "PSULocationProvider: arrival %.0fs ago, accuracy %.0fm"
+ "PSULocationProvider: authorization %d"
+ "PSULocationProvider: departed (%.0fs ago)"
+ "PSULocationProvider: location failed: %{public}@ %ld"
+ "PSULocationProvider: monitoring visits, authorization %d"
+ "PSULocationProvider: moved since the saved place (error %ld)"
+ "PSULocationProvider: no fix, last requested %.0fs ago; waiting for a visit"
+ "PSULocationProvider: no location manager"
+ "PSULocationProvider: place lookup failed: %{public}ld"
+ "PSULocationProvider: place lookup overtaken by a later visit; dropped"
+ "PSULocationProvider: requesting a location fix"
+ "PSULocationProvider: restored %{private}@, no departure in %.0fs"
+ "PSULocationProvider: restored away, reported %.0fs ago"
+ "PSULocationProvider: stopped visit monitoring left from an earlier run"
+ "Place monitoring ended; place cleared, retrying later"
+ "Place now %{private}s visits=%{private}ld"
+ "ProactiveSummarization Trial namespace updated; refreshing assets"
+ "SELECT * FROM contextSignalDelivery WHERE deliveredAt < :threshold ORDER BY deliveredAt ASC, rowid ASC"
+ "SELECT * FROM contextSignalDelivery WHERE deliveredAt >= :threshold ORDER BY deliveredAt DESC, rowid DESC LIMIT -1 OFFSET :offset"
+ "SELECT * FROM contextSignalDelivery WHERE id = :id"
+ "SELECT 1 FROM contextSignalDelivery WHERE id = :id LIMIT 1"
+ "SELECT 1 FROM contextSignalLoggedEvent WHERE key = :key LIMIT 1"
+ "SELECT 1 FROM sqlite_master WHERE type = 'table' AND name = 'notificationPipelineEvent' LIMIT 1"
+ "SELECT cursor FROM contextSignalCursor WHERE pk = 1"
+ "SELECT id FROM contextSignalDelivery WHERE biomeNotificationId = :biomeNotificationId ORDER BY deliveredAt DESC, rowid DESC LIMIT 1"
+ "SELECT id FROM contextSignalDelivery WHERE bundleId = :bundleId AND notificationDate > :low AND notificationDate < :high AND (threadId IS NULL OR :threadId IS NULL OR threadId = :threadId) "
+ "SELECT signals FROM contextSignalDelivery WHERE id = :id"
+ "SELECT spotlightIdentifier, event FROM notificationPipelineEvent WHERE spotlightIdentifier IN _pas_nsarray(:spotlightIdentifiers) AND timestamp >= :threshold ORDER BY timestamp ASC, pk ASC"
+ "SELECT time FROM contextSignalGestureStart WHERE biomeNotificationId = :biomeNotificationId"
+ "UPDATE contextSignalDelivery SET biomeNotificationId = :biomeNotificationId, receivedAt = MIN(COALESCE(receivedAt, :receivedAt), :receivedAt), deliveryMode = CASE WHEN "
+ "UPDATE contextSignalDelivery SET biomeNotificationId = COALESCE(biomeNotificationId, :biomeNotificationId), outcome = :outcome WHERE id = :id"
+ "UPDATE contextSignalDelivery SET outcomeLogged = 1 WHERE id = :id"
+ "[NotificationPipelineEventStore] Not keeping an event that isn't valid JSON"
+ "arrived"
+ "attachContextSignalReceipt(id:biomeNotificationId:receivedAt:deliveryMode:replaceableMode:)"
+ "bundleId"
+ "com.apple.suggestions.NotificationPipelineEventStore"
+ "com.apple.suggestions.PSULocationProvider"
+ "contextSignalCursor()"
+ "contextSignalDelivery(id:)"
+ "contextSignalDeliveryExists(id:)"
+ "contextSignalDeliveryId(biomeNotificationId:)"
+ "contextSignalDeliveryId(bundleId:notificationDate:threadId:unattachedOnly:)"
+ "contextSignalEventIsLogged(key:)"
+ "contextSignalGestureStart(biomeNotificationId:)"
+ "contextSignalSignals(id:)"
+ "contextSignalWriteTransaction: body did not run"
+ "currently"
+ "cursor"
+ "deliveredAt"
+ "deliveryMode"
+ "ensureNotificationPipelineEventTable()"
+ "event"
+ "events(forSpotlightIdentifiers:now:)"
+ "hasNotificationPipelineEventTable"
+ "id"
+ "insertContextSignalDelivery(id:bundleId:threadId:notificationDate:deliveredAt:biomeNotificationId:signals:)"
+ "insertNotificationPipelineEvent(spotlightIdentifier:event:timestamp:)"
+ "kind"
+ "known"
+ "markContextSignalEventLogged(key:time:)"
+ "markContextSignalOutcomeLogged(id:)"
+ "no learned place"
+ "notificationPipelineEvents endpoint unavailable"
+ "notificationPipelineEvents(spotlightIdentifiers:since:)"
+ "outcome"
+ "outcomeLogged"
+ "pruneContextSignalDeliveries(olderThan:maxRowCount:)"
+ "pruneContextSignalEvents(olderThan:)"
+ "pruneNotificationPipelineEvents(olderThan:maxRowCount:)"
+ "receivedAt"
+ "setContextSignalCursor(_:)"
+ "setContextSignalGestureStart(biomeNotificationId:time:)"
+ "signals"
+ "softlink:o:path:/System/Library/Frameworks/CoreLocation.framework/CoreLocation"
+ "spotlightIdentifier"
+ "threadId"
+ "time"
+ "updateContextSignalOutcome(id:biomeNotificationId:outcome:)"
+ "v24@?0@\"RTLocationOfInterest\"8@\"NSError\"16"
+ "visitCount"
- "%.0fs ago"
- "Context signal store not readable yet: %{public}@"
- "Context signal store not saved: %{public}@"
- "Context signal store unreadable, starting over: %{public}@"
- "CoreRoutine unavailable"
- "Device %{public}s; refreshing place"
- "No place: nothing visited in either window, or no reply within %{public}s"
- "PSULocationProvider"
- "PSULocationProvider: LOI visit fetch failed: %{public}ld"
- "PSULocationProvider: RTRoutineManager has no +defaultManager"
- "PSULocationProvider: failed to soft-link CoreRoutine"
- "PSULocationProvider: latest visit type=%{private}ld entered=%{private}.0fs ago exited=%{private}@"
- "PSULocationProvider: settled-state monitoring error: %{public}@"
- "Place pull finished after a settled-state change; discarded"
- "Settled-state monitoring ended; retrying later"
- "completion != nil"
- "currentPlace(withinWindow:)"
- "open"
- "v24@?0@\"RTScenarioTrigger\"8@\"NSError\"16"
```
