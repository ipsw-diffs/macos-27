## AppPredictionInternal

> `/System/Library/PrivateFrameworks/AppPredictionInternal.framework/Versions/A/AppPredictionInternal`

```diff

-678.0.1.0.0
-  __TEXT.__text: 0x4fc088
-  __TEXT.__objc_methlist: 0x38b3c
+678.2.1.0.3
+  __TEXT.__text: 0x4fc46c
+  __TEXT.__objc_methlist: 0x38b84
   __TEXT.__const: 0x5ef0
-  __TEXT.__cstring: 0x59f94
-  __TEXT.__oslogstring: 0x3b029
-  __TEXT.__gcc_except_tab: 0x1073c
+  __TEXT.__cstring: 0x5a7d4
+  __TEXT.__oslogstring: 0x3b0f9
+  __TEXT.__gcc_except_tab: 0x10770
   __TEXT.__dlopen_cstrs: 0x10a
   __TEXT.__ustring: 0x90
-  __TEXT.__swift5_typeref: 0x1c4f
+  __TEXT.__swift5_typeref: 0x1c23
   __TEXT.__constg_swiftt: 0x2160
   __TEXT.__swift5_reflstr: 0xf92
   __TEXT.__swift5_fieldmd: 0x1464

   __TEXT.__swift_as_entry: 0x2c8
   __TEXT.__swift_as_ret: 0x2a4
   __TEXT.__swift_as_cont: 0x430
-  __TEXT.__swift5_capture: 0xe7c
+  __TEXT.__swift5_capture: 0xe64
   __TEXT.__swift5_builtin: 0xc8
   __TEXT.__swift5_assocty: 0x228
   __TEXT.__swift5_protos: 0x24
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x13c78
+  __TEXT.__unwind_info: 0x13c88
   __TEXT.__eh_frame: 0x5fb4
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4650
+  __DATA_CONST.__const: 0x46a0
   __DATA_CONST.__objc_classlist: 0x1f10
   __DATA_CONST.__objc_catlist: 0x110
   __DATA_CONST.__objc_protolist: 0x4b0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x1be70
+  __DATA_CONST.__objc_selrefs: 0x1bea8
   __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_superrefs: 0x1488
   __DATA_CONST.__objc_arraydata: 0x1330
   __DATA_CONST.__got: 0x3b40
-  __AUTH_CONST.__const: 0x137e8
-  __AUTH_CONST.__cfstring: 0x3b380
-  __AUTH_CONST.__objc_const: 0x828a8
+  __AUTH_CONST.__const: 0x137b0
+  __AUTH_CONST.__cfstring: 0x3b720
+  __AUTH_CONST.__objc_const: 0x82930
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__objc_intobj: 0x3450
   __AUTH_CONST.__objc_arrayobj: 0x1128

   __AUTH_CONST.__auth_got: 0x23d8
   __AUTH.__objc_data: 0x3a08
   __AUTH.__data: 0x1e20
-  __DATA.__objc_ivar: 0x4a10
+  __DATA.__objc_ivar: 0x4a1c
   __DATA.__data: 0x3cc0
   __DATA.__bss: 0x3e10
   __DATA.__common: 0xb8
   __DATA_DIRTY.__objc_data: 0x10688
-  __DATA_DIRTY.__data: 0x1330
+  __DATA_DIRTY.__data: 0x1320
   __DATA_DIRTY.__bss: 0x1960
   __DATA_DIRTY.__common: 0x140
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 26742
-  Symbols:   46502
-  CStrings:  12450
+  Functions: 26748
+  Symbols:   46524
+  CStrings:  12489
 
Symbols:
+ +[ATXMediaActionPrediction hasMediaToPlayForINPlayMediaIntent:]
+ -[ATXNotificationAndSuggestionDatabase _latestOutcomeForNotification:]
+ -[ATXNotificationAndSuggestionDatabase updateNotificationUIForNotifications:nextUI:timestamp:]
+ -[ATXNotificationTelemetryQueryResult priorityFeedback]
+ -[ATXNotificationTelemetryQueryResult resolutionEventType]
+ -[ATXNotificationTelemetryQueryResult setPriorityFeedback:]
+ -[ATXNotificationTelemetryQueryResult setResolutionEventType:]
+ GCC_except_table115
+ GCC_except_table204
+ GCC_except_table209
+ GCC_except_table92
+ _OBJC_IVAR_$_ATXNotificationHandleSummaryMetrics._unresolvedNotificationCount
+ _OBJC_IVAR_$_ATXNotificationTelemetryQueryResult._priorityFeedback
+ _OBJC_IVAR_$_ATXNotificationTelemetryQueryResult._resolutionEventType
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_ATXWidgetDescriptorCacheObserver
+ ___113-[ATXNotificationAndSuggestionDatabase insertNotificationFromEvent:deliveryMethod:modeIdentifier:deliveryReason:]_block_invoke_3
+ ___70-[ATXNotificationAndSuggestionDatabase _latestOutcomeForNotification:]_block_invoke
+ ___70-[ATXNotificationAndSuggestionDatabase _latestOutcomeForNotification:]_block_invoke_2
+ ___70-[ATXNotificationAndSuggestionDatabase _latestOutcomeForNotification:]_block_invoke_3
+ ___70-[ATXNotificationAndSuggestionDatabase _latestOutcomeForNotification:]_block_invoke_4
+ ___94-[ATXNotificationAndSuggestionDatabase updateNotificationUIForNotifications:nextUI:timestamp:]_block_invoke
+ ___94-[ATXNotificationAndSuggestionDatabase updateNotificationUIForNotifications:nextUI:timestamp:]_block_invoke_2
+ ___94-[ATXNotificationAndSuggestionDatabase updateNotificationUIForNotifications:nextUI:timestamp:]_block_invoke_3
+ ___block_descriptor_56_e8_32s_e29_v16?0"_PASSqliteStatement"8l
+ _kATXAddNotificationUUIDToNotifications
+ _kATXAddPriorityFeedbackToNotifications
+ _kATXAddResolutionUIToNotifications
+ _kATXEarlierDeliveryIndex
+ _kATXLatestOutcomeForNotificationQuery
+ _kATXRetireNotificationWithEndedDeliveryQuery
+ _kATXUpdateEarlierDeliveryUIQuery
+ _kATXUpdateNotificationPriorityFeedbackQuery
+ _objc_msgSend$_latestOutcomeForNotification:
+ _objc_msgSend$hasMediaToPlayForINPlayMediaIntent:
+ _objc_msgSend$isZKWCommuteEnabled
+ _objc_msgSend$priorityFeedback
+ _objc_msgSend$resolutionEventType
+ _objc_msgSend$setPriorityFeedback:
+ _objc_msgSend$setResolutionEventType:
+ _objc_msgSend$updateNotificationUIForNotifications:nextUI:timestamp:
- -[ATXNotificationAndSuggestionDatabase setAllNotificationsToClearedExceptProminent]
- -[ATXNotificationAndSuggestionDatabase updateNotificationUIForNotifications:nextUI:]
- GCC_except_table198
- GCC_except_table203
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_ATXWidgetDescriptorCacheObserver
- ___83-[ATXNotificationAndSuggestionDatabase setAllNotificationsToClearedExceptProminent]_block_invoke
- ___83-[ATXNotificationAndSuggestionDatabase setAllNotificationsToClearedExceptProminent]_block_invoke_2
- ___83-[ATXNotificationAndSuggestionDatabase setAllNotificationsToClearedExceptProminent]_block_invoke_3
- ___84-[ATXNotificationAndSuggestionDatabase allNotificationsFromBundleId:sinceTimestamp:]_block_invoke_3
- ___84-[ATXNotificationAndSuggestionDatabase updateNotificationUIForNotifications:nextUI:]_block_invoke
- ___84-[ATXNotificationAndSuggestionDatabase updateNotificationUIForNotifications:nextUI:]_block_invoke_2
- ___84-[ATXNotificationAndSuggestionDatabase updateNotificationUIForNotifications:nextUI:]_block_invoke_3
- _kATXChangeActiveStatusGivenProminenceQuery
- _objc_msgSend$setAllNotificationsToClearedExceptProminent
- _objc_msgSend$updateNotificationUIForNotifications:nextUI:
- _symbolic SDySS_____G 10Foundation4DateV
- _symbolic SDySS_____Gz_Xx 10Foundation4DateV
- _symbolic _____ySS_____G s18_DictionaryStorageC 10Foundation4DateV
CStrings:
+ " UPDATE notifications SET   firstUI = COALESCE(firstUI, :nextUI),   mostRecentUI = :nextUI,   isDeliveredInPrioritySection = (COALESCE(isDeliveredInPrioritySection, 0) | (:nextUI = :priorityNotificationUI)) WHERE   notificationUUID IN _pas_nsarray(:notificationUUIDs) AND   receiveTimestamp <= :timestamp AND   NOT EXISTS (     SELECT 1 FROM notifications AS laterDelivery     WHERE (laterDelivery.uuid = notifications.notificationUUID OR laterDelivery.notificationUUID = notifications.notificationUUID) AND       laterDelivery.receiveTimestamp > notifications.receiveTimestamp AND laterDelivery.receiveTimestamp <= :timestamp) "
+ " UPDATE notifications SET   firstUI = COALESCE(firstUI, :nextUI),   mostRecentUI = :nextUI,   isDeliveredInPrioritySection = (COALESCE(isDeliveredInPrioritySection, 0) | (:nextUI = :priorityNotificationUI)) WHERE   uuid IN _pas_nsarray(:notificationUUIDs) AND   NOT (receiveTimestamp > :timestamp AND EXISTS (     SELECT 1 FROM notifications AS earlierDelivery     WHERE earlierDelivery.notificationUUID = notifications.uuid AND earlierDelivery.receiveTimestamp <= :timestamp)) "
+ ":clear"
+ ":clearAll"
+ ":expired"
+ ":priorityFeedback"
+ ":priorityNotificationUI"
+ ":removed"
+ ":resolutionUI"
+ ":retiredUUID"
+ "ALTER TABLE notifications ADD COLUMN notificationUUID TEXT"
+ "ALTER TABLE notifications ADD COLUMN priorityFeedback INTEGER"
+ "ALTER TABLE notifications ADD COLUMN resolutionUI INTEGER"
+ "CREATE INDEX earlierDeliveryIndex ON notifications (notificationUUID) WHERE notificationUUID IS NOT NULL"
+ "Cleared"
+ "ClearedAll"
+ "Deduplicated"
+ "DismissedBanner"
+ "Error fetching latest outcome for notification %@: %@"
+ "Error recording priority feedback for notification event %@: %@"
+ "Error retiring ended delivery for notification event %@: %@"
+ "ExpandedNotification"
+ "Expired"
+ "INSERT OR IGNORE INTO notifications VALUES (:uuid, :receiveTimestamp, :deliveryMethod, :urgency, :bundleId, :threadId, :contactId, :isGroupMessage, :isMessage, :latestOutcome, :latestOutcomeTimestamp, :isProminent, :isActive, 0, :rawIdentifier, :receivedMode, NULL, NULL, :deliveryReason, :recordTimestamp, :notificationID, :notificationBodyLength, :notificationTitleLength, :notificationSubtitleLength, :summaryLength, :isDeliveredInPrioritySection, :isSummarized, :isPartOfStack, :isStackSummary, 0, :numberOfNotificationsInStack, :notificationPriorityStatus, :notificationSummaryStatus, :isPriorityNotificationEnabled, :isNotificationSummaryEnabled, NULL, NULL, NULL, NULL)"
+ "LegacyInteractionDetail"
+ "Media prediction for %@ has no media items, container, or buckets. Resolving as a nil prediction."
+ "MovedOffLockScreen"
+ "Negative"
+ "OpenedApp"
+ "Positive"
+ "PulledDownBanner"
+ "RemovedWithoutUserAction"
+ "ReportedConcern"
+ "SELECT     COALESCE(notificationUUID, uuid) AS uuid,     receiveTimestamp,     deliveryMethod,     urgency,     bundleId,     isMessage,     latestOutcome,     latestOutcomeTimestamp,     numExpansions,     receivedMode,     firstUI,     mostRecentUI,     deliveryReason,     notificationBodyLength,     notificationTitleLength,     notificationSubtitleLength,     summaryLength,     isDeliveredInPrioritySection,     isSummarized,     isPartOfStack,     isStackSummary,     numberOfNotificationsInStack,     notificationPriorityStatus,     notificationSummaryStatus,     isPriorityNotificationEnabled,     isNotificationSummaryEnabled,     nextAppLaunchTimestamp,     priorityFeedback,     resolutionUI FROM notifications WHERE     bundleId = :bundleId AND     notificationId = :notificationId AND     recordTimestamp = :recordTimestamp ORDER BY recordTimestamp DESC LIMIT 1 "
+ "SELECT     COALESCE(notificationUUID, uuid) AS uuid,     receiveTimestamp,     deliveryMethod,     urgency,     bundleId,     isMessage,     latestOutcome,     latestOutcomeTimestamp,     numExpansions,     receivedMode,     firstUI,     mostRecentUI,     deliveryReason,     notificationBodyLength,     notificationTitleLength,     notificationSubtitleLength,     summaryLength,     isDeliveredInPrioritySection,     isSummarized,     isPartOfStack,     isStackSummary,     numberOfNotificationsInStack,     notificationPriorityStatus,     notificationSummaryStatus,     isPriorityNotificationEnabled,     isNotificationSummaryEnabled,     nextAppLaunchTimestamp,     priorityFeedback,     resolutionUI FROM notifications WHERE     receiveTimestamp > :startTimestamp AND     receiveTimestamp < :endTimestamp "
+ "SELECT latestOutcome FROM notifications WHERE uuid = :uuid"
+ "SpringBoardRestarted"
+ "TappedActionButton"
+ "TappedNotification"
+ "UPDATE notifications SET latestOutcome = :latestOutcome, latestOutcomeTimestamp = :latestOutcomeTimestamp, resolutionUI = :resolutionUI, isProminent = (isProminent & :isProminent), isActive = (isActive & :isActive) WHERE uuid = :uuid"
+ "UPDATE notifications SET nextAppLaunchTimestamp = :nextAppLaunchTimestamp WHERE bundleId = :bundleId AND nextAppLaunchTimestamp IS NULL AND receiveTimestamp >= :receivedDateAfter AND receiveTimestamp < :nextAppLaunchTimestamp"
+ "UPDATE notifications SET notificationUUID = uuid, uuid = :retiredUUID WHERE uuid = :uuid AND latestOutcome IN (:defaultAction, :supplementaryAction, :clear, :clearAll, :removed, :appLaunch, :expired) AND recordTimestamp IS NOT :recordTimestamp"
+ "UPDATE notifications SET priorityFeedback = :priorityFeedback WHERE uuid = :uuid"
+ "earlierDeliveryIndex"
+ "notificationUUID"
+ "priorityFeedback"
+ "resolutionAction"
+ "resolutionUI"
- " UPDATE notifications SET   firstUI = COALESCE(firstUI, :nextUI),   mostRecentUI = :nextUI WHERE   uuid IN _pas_nsarray(:notificationUUIDs) "
- "-[ATXNotificationAndSuggestionDatabase allNotificationsFromBundleId:sinceTimestamp:]_block_invoke_3"
- "Error updating notification while clearing all except prominent. Error: %@"
- "INSERT OR IGNORE INTO notifications VALUES (:uuid, :receiveTimestamp, :deliveryMethod, :urgency, :bundleId, :threadId, :contactId, :isGroupMessage, :isMessage, :latestOutcome, :latestOutcomeTimestamp, :isProminent, :isActive, 0, :rawIdentifier, :receivedMode, NULL, NULL, :deliveryReason, :recordTimestamp, :notificationID, :notificationBodyLength, :notificationTitleLength, :notificationSubtitleLength, :summaryLength, :isDeliveredInPrioritySection, :isSummarized, :isPartOfStack, :isStackSummary, 0, :numberOfNotificationsInStack, :notificationPriorityStatus, :notificationSummaryStatus, :isPriorityNotificationEnabled, :isNotificationSummaryEnabled, NULL)"
- "SELECT     uuid,     receiveTimestamp,     deliveryMethod,     urgency,     bundleId,     isMessage,     latestOutcome,     latestOutcomeTimestamp,     numExpansions,     receivedMode,     firstUI,     mostRecentUI,     deliveryReason,     notificationBodyLength,     notificationTitleLength,     notificationSubtitleLength,     summaryLength,     isDeliveredInPrioritySection,     isSummarized,     isPartOfStack,     isStackSummary,     numberOfNotificationsInStack,     notificationPriorityStatus,     notificationSummaryStatus,     isPriorityNotificationEnabled,     isNotificationSummaryEnabled,     nextAppLaunchTimestamp FROM notifications WHERE     bundleId = :bundleId AND     notificationId = :notificationId AND     recordTimestamp = :recordTimestamp ORDER BY recordTimestamp DESC LIMIT 1 "
- "SELECT     uuid,     receiveTimestamp,     deliveryMethod,     urgency,     bundleId,     isMessage,     latestOutcome,     latestOutcomeTimestamp,     numExpansions,     receivedMode,     firstUI,     mostRecentUI,     deliveryReason,     notificationBodyLength,     notificationTitleLength,     notificationSubtitleLength,     summaryLength,     isDeliveredInPrioritySection,     isSummarized,     isPartOfStack,     isStackSummary,     numberOfNotificationsInStack,     notificationPriorityStatus,     notificationSummaryStatus,     isPriorityNotificationEnabled,     isNotificationSummaryEnabled,     nextAppLaunchTimestamp FROM notifications WHERE     receiveTimestamp > :startTimestamp AND     receiveTimestamp < :endTimestamp "
- "UPDATE notifications SET latestOutcome = :latestOutcome, isActive = :isActive WHERE isProminent = :isProminent"
- "UPDATE notifications SET latestOutcome = :latestOutcome, latestOutcomeTimestamp = :latestOutcomeTimestamp, isProminent = (isProminent & :isProminent), isActive = (isActive & :isActive) WHERE uuid = :uuid"
- "UPDATE notifications SET nextAppLaunchTimestamp = :nextAppLaunchTimestamp WHERE bundleId = :bundleId AND receiveTimestamp >= :receivedDateAfter AND receiveTimestamp < :nextAppLaunchTimestamp"
```
