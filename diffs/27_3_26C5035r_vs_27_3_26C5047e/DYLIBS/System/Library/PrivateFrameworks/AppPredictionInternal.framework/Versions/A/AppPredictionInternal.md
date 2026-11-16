## AppPredictionInternal

> `/System/Library/PrivateFrameworks/AppPredictionInternal.framework/Versions/A/AppPredictionInternal`

```diff

-678.2.1.0.3
-  __TEXT.__text: 0x4fc46c
-  __TEXT.__objc_methlist: 0x38b84
-  __TEXT.__const: 0x5ef0
-  __TEXT.__cstring: 0x5a7d4
-  __TEXT.__oslogstring: 0x3b0f9
-  __TEXT.__gcc_except_tab: 0x10770
+678.2.6.0.1
+  __TEXT.__text: 0x4ff7f8
+  __TEXT.__objc_methlist: 0x38ca4
+  __TEXT.__const: 0x5f00
+  __TEXT.__cstring: 0x5b3d4
+  __TEXT.__oslogstring: 0x3b2d9
+  __TEXT.__gcc_except_tab: 0x107b8
   __TEXT.__dlopen_cstrs: 0x10a
   __TEXT.__ustring: 0x90
   __TEXT.__swift5_typeref: 0x1c23

   __TEXT.__swift5_assocty: 0x228
   __TEXT.__swift5_protos: 0x24
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x13c88
+  __TEXT.__unwind_info: 0x13d50
   __TEXT.__eh_frame: 0x5fb4
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x46a0
-  __DATA_CONST.__objc_classlist: 0x1f10
+  __DATA_CONST.__const: 0x46d0
+  __DATA_CONST.__objc_classlist: 0x1f18
   __DATA_CONST.__objc_catlist: 0x110
   __DATA_CONST.__objc_protolist: 0x4b0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x1bea8
+  __DATA_CONST.__objc_selrefs: 0x1bf40
   __DATA_CONST.__objc_protorefs: 0xb0
-  __DATA_CONST.__objc_superrefs: 0x1488
-  __DATA_CONST.__objc_arraydata: 0x1330
-  __DATA_CONST.__got: 0x3b40
-  __AUTH_CONST.__const: 0x137b0
-  __AUTH_CONST.__cfstring: 0x3b720
-  __AUTH_CONST.__objc_const: 0x82930
+  __DATA_CONST.__objc_superrefs: 0x1490
+  __DATA_CONST.__objc_arraydata: 0x1350
+  __DATA_CONST.__got: 0x3b48
+  __AUTH_CONST.__const: 0x13910
+  __AUTH_CONST.__cfstring: 0x3ba20
+  __AUTH_CONST.__objc_const: 0x82a60
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__objc_intobj: 0x3450
-  __AUTH_CONST.__objc_arrayobj: 0x1128
+  __AUTH_CONST.__objc_arrayobj: 0x1140
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_floatobj: 0x30
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__auth_got: 0x23d8
-  __AUTH.__objc_data: 0x3a08
+  __AUTH.__objc_data: 0x3a58
   __AUTH.__data: 0x1e20
-  __DATA.__objc_ivar: 0x4a1c
+  __DATA.__objc_ivar: 0x4a2c
   __DATA.__data: 0x3cc0
-  __DATA.__bss: 0x3e10
+  __DATA.__bss: 0x3e20
   __DATA.__common: 0xb8
   __DATA_DIRTY.__objc_data: 0x10688
   __DATA_DIRTY.__data: 0x1320
-  __DATA_DIRTY.__bss: 0x1960
+  __DATA_DIRTY.__bss: 0x1970
   __DATA_DIRTY.__common: 0x140
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 26748
-  Symbols:   46524
-  CStrings:  12489
+  Functions: 26796
+  Symbols:   46596
+  CStrings:  12541
 
Symbols:
+ +[ATXFaceGalleryLayoutGenerator descriptorsByPromotingCompactTimeDescriptorInDescriptors:toIndex:]
+ +[ATXNotificationCategorizationServer engagementMetricsJSONForTelemetry:error:]
+ +[ATXNotificationFeedbackContentStore isCollectionEnabled]
+ +[ATXNotificationFeedbackContentStore sharedInstance]
+ -[ATXNotificationAndSuggestionDatabase telemetryDataForNotificationUUIDs:]
+ -[ATXNotificationAndSuggestionDatastore telemetryDataForNotificationUUIDs:]
+ -[ATXNotificationCategorizationServer collectEngagementMetricsForNotificationUUIDs:completion:]
+ -[ATXNotificationCategorizationServer collectNotificationFeedbackContentWithCompletion:]
+ -[ATXNotificationCategorizationServer deleteNotificationFeedbackContentWithCompletion:]
+ -[ATXNotificationFeedbackContentStore .cxx_destruct]
+ -[ATXNotificationFeedbackContentStore _queue_deleteAllIfPresent]
+ -[ATXNotificationFeedbackContentStore _queue_deleteAll]
+ -[ATXNotificationFeedbackContentStore _queue_openDatabase]
+ -[ATXNotificationFeedbackContentStore _queue_pruneWithDatabase:]
+ -[ATXNotificationFeedbackContentStore deleteAll]
+ -[ATXNotificationFeedbackContentStore initWithPath:isCollectionEnabled:]
+ -[ATXNotificationFeedbackContentStore pruneOrDeleteIfCollectionDisabled]
+ -[ATXNotificationFeedbackContentStore recentNotificationsJSONWithError:]
+ -[ATXNotificationFeedbackContentStore recordReceivedNotification:]
+ _ATXFaceGalleryFeaturedCompactTimeIndex
+ _ATXNotificationFeedbackDataCollectionEnabledKey
+ _OBJC_CLASS_$_ATXNotificationFeedbackContentStore
+ _OBJC_IVAR_$_ATXNotificationFeedbackContentStore._db
+ _OBJC_IVAR_$_ATXNotificationFeedbackContentStore._isCollectionEnabled
+ _OBJC_IVAR_$_ATXNotificationFeedbackContentStore._path
+ _OBJC_IVAR_$_ATXNotificationFeedbackContentStore._queue
+ _OBJC_METACLASS_$_ATXNotificationFeedbackContentStore
+ __OBJC_$_CLASS_METHODS_ATXNotificationFeedbackContentStore
+ __OBJC_$_INSTANCE_METHODS_ATXNotificationFeedbackContentStore
+ __OBJC_$_INSTANCE_VARIABLES_ATXNotificationFeedbackContentStore
+ __OBJC_CLASS_RO_$_ATXNotificationFeedbackContentStore
+ __OBJC_METACLASS_RO_$_ATXNotificationFeedbackContentStore
+ ___48-[ATXNotificationFeedbackContentStore deleteAll]_block_invoke
+ ___53+[ATXNotificationFeedbackContentStore sharedInstance]_block_invoke
+ ___53+[ATXNotificationFeedbackContentStore sharedInstance]_block_invoke_2
+ ___58-[ATXNotificationFeedbackContentStore _queue_openDatabase]_block_invoke
+ ___64-[ATXNotificationFeedbackContentStore _queue_pruneWithDatabase:]_block_invoke
+ ___64-[ATXNotificationFeedbackContentStore _queue_pruneWithDatabase:]_block_invoke_2
+ ___66-[ATXNotificationFeedbackContentStore recordReceivedNotification:]_block_invoke
+ ___66-[ATXNotificationFeedbackContentStore recordReceivedNotification:]_block_invoke_2
+ ___72-[ATXNotificationFeedbackContentStore pruneOrDeleteIfCollectionDisabled]_block_invoke
+ ___72-[ATXNotificationFeedbackContentStore recentNotificationsJSONWithError:]_block_invoke
+ ___72-[ATXNotificationFeedbackContentStore recentNotificationsJSONWithError:]_block_invoke_2
+ ___74-[ATXNotificationAndSuggestionDatabase telemetryDataForNotificationUUIDs:]_block_invoke
+ ___74-[ATXNotificationAndSuggestionDatabase telemetryDataForNotificationUUIDs:]_block_invoke_2
+ ___74-[ATXNotificationAndSuggestionDatabase telemetryDataForNotificationUUIDs:]_block_invoke_3
+ ___74-[ATXNotificationAndSuggestionDatabase telemetryDataForNotificationUUIDs:]_block_invoke_4
+ ___95-[ATXNotificationCategorizationServer collectEngagementMetricsForNotificationUUIDs:completion:]_block_invoke
+ ___95-[ATXNotificationCategorizationServer collectEngagementMetricsForNotificationUUIDs:completion:]_block_invoke_2
+ ___98+[ATXFaceGalleryLayoutGenerator descriptorsByPromotingCompactTimeDescriptorInDescriptors:toIndex:]_block_invoke
+ ___block_descriptor_114_e8_32s40s48s56s64s72s80s88s_e29_v16?0"_PASSqliteStatement"8l
+ ___block_descriptor_122_e8_32s40s48s56s64s72s80s88s96s_e5_v8?0l
+ ___block_descriptor_32_e36_B32?0"ATXPosterDescriptor"8Q16^B24l
+ _collectEngagementMetricsForNotificationUUIDs:completion:.engagementMetricsQueue
+ _collectEngagementMetricsForNotificationUUIDs:completion:.onceToken
+ _kATXNotificationTelemetryForNotificationUUIDsQuery
+ _objc_msgSend$_queue_deleteAll
+ _objc_msgSend$_queue_deleteAllIfPresent
+ _objc_msgSend$_queue_openDatabase
+ _objc_msgSend$_queue_pruneWithDatabase:
+ _objc_msgSend$deleteAll
+ _objc_msgSend$descriptorsByPromotingCompactTimeDescriptorInDescriptors:toIndex:
+ _objc_msgSend$engagementMetricsJSONForTelemetry:error:
+ _objc_msgSend$initWithPath:isCollectionEnabled:
+ _objc_msgSend$isCollectionEnabled
+ _objc_msgSend$isStoreDownloadInstallTypeForBundle:
+ _objc_msgSend$isValidJSONObject:
+ _objc_msgSend$pruneOrDeleteIfCollectionDisabled
+ _objc_msgSend$recentNotificationsJSONWithError:
+ _objc_msgSend$recordReceivedNotification:
+ _objc_msgSend$telemetryDataForNotificationUUIDs:
+ _objc_msgSend$timeStyle
CStrings:
+ "%s: could not delete %@: %@"
+ "%s: could not open the database: %@"
+ "%s: could not set up the database: %@"
+ "%s: deleted the notifications kept for Notification Feedback"
+ "%s: failed to keep a notification: %@"
+ "%s: failed to prune: %@"
+ "%s: failed to read notifications: %@"
+ "%s: found %lu deliveries of %lu notifications, error: %@"
+ "%s: promoting compact time descriptor from index %lu to %lu: %@ %@"
+ "+[ATXFaceGalleryLayoutGenerator descriptorsByPromotingCompactTimeDescriptorInDescriptors:toIndex:]"
+ "-[ATXNotificationCategorizationServer collectEngagementMetricsForNotificationUUIDs:completion:]"
+ "-[ATXNotificationCategorizationServer collectEngagementMetricsForNotificationUUIDs:completion:]_block_invoke"
+ "-[ATXNotificationFeedbackContentStore _queue_deleteAll]"
+ "-[ATXNotificationFeedbackContentStore _queue_openDatabase]"
+ "-[ATXNotificationFeedbackContentStore _queue_openDatabase]_block_invoke"
+ "-[ATXNotificationFeedbackContentStore _queue_pruneWithDatabase:]_block_invoke_2"
+ "-[ATXNotificationFeedbackContentStore recentNotificationsJSONWithError:]_block_invoke"
+ "-[ATXNotificationFeedbackContentStore recordReceivedNotification:]_block_invoke"
+ "-journal"
+ ":body"
+ ":contactIds"
+ ":requestId"
+ "ATXNotificationCategorizationServer.collectEngagementMetrics"
+ "ATXNotificationFeedbackDataCollectionEnabled"
+ "ATXNotificationFeedbackEnabled"
+ "B32@?0@\"ATXPosterDescriptor\"8Q16^B24"
+ "CREATE INDEX IF NOT EXISTS notification_receiveTimestamp ON notification (receiveTimestamp)"
+ "CREATE TABLE IF NOT EXISTS notification (uuid TEXT PRIMARY KEY, bundleId TEXT NOT NULL, requestId TEXT, receiveTimestamp REAL NOT NULL, title TEXT, subtitle TEXT, body TEXT, threadId TEXT, contactIds BLOB, isMessage INTEGER NOT NULL, isGroupMessage INTEGER NOT NULL, urgency INTEGER NOT NULL)"
+ "DELETE FROM notification WHERE receiveTimestamp < :cutoff"
+ "Engagement metrics are only available on internal builds"
+ "Engagement metrics aren't valid JSON"
+ "INSERT OR REPLACE INTO notification (uuid, bundleId, requestId, receiveTimestamp, title, subtitle, body, threadId, contactIds, isMessage, isGroupMessage, urgency) VALUES (:uuid, :bundleId, :requestId, :receiveTimestamp, :title, :subtitle, :body, :threadId, :contactIds, :isMessage, :isGroupMessage, :urgency)"
+ "Notification Feedback's data collection is off"
+ "NotificationFeedbackContent.db"
+ "PRAGMA journal_mode=DELETE"
+ "PRAGMA secure_delete=ON"
+ "SELECT     COALESCE(notificationUUID, uuid) AS uuid,     receiveTimestamp,     deliveryMethod,     urgency,     bundleId,     isMessage,     latestOutcome,     latestOutcomeTimestamp,     numExpansions,     receivedMode,     firstUI,     mostRecentUI,     deliveryReason,     notificationBodyLength,     notificationTitleLength,     notificationSubtitleLength,     summaryLength,     isDeliveredInPrioritySection,     isSummarized,     isPartOfStack,     isStackSummary,     numberOfNotificationsInStack,     notificationPriorityStatus,     notificationSummaryStatus,     isPriorityNotificationEnabled,     isNotificationSummaryEnabled,     nextAppLaunchTimestamp,     priorityFeedback,     resolutionUI FROM notifications WHERE     uuid IN _pas_nsarray(:notificationUUIDs) OR     notificationUUID IN _pas_nsarray(:notificationUUIDs) ORDER BY receiveTimestamp ASC "
+ "SELECT * FROM notification ORDER BY receiveTimestamp DESC"
+ "Starting %s for %lu notifications"
+ "body"
+ "bundleIdentifier"
+ "com.apple.duetexpertd.ATXNotificationCategorizationServer.engagementMetrics"
+ "com.apple.duetexpertd.ATXNotificationFeedbackContentStore"
+ "contactIdentifiers"
+ "contactIds"
+ "isCommunication"
+ "isCritical"
+ "isGroupThread"
+ "isTimeSensitive"
+ "requestId"
+ "requestIdentifier"
+ "threadIdentifier"
```
