## CoreFollowUp

> `/System/Library/PrivateFrameworks/CoreFollowUp.framework/Versions/A/CoreFollowUp`

```diff

-2027.2.2.0.0
-  __TEXT.__text: 0x24684
-  __TEXT.__objc_methlist: 0x1754
+2027.2.4.0.0
+  __TEXT.__text: 0x2635c
+  __TEXT.__objc_methlist: 0x17d4
   __TEXT.__const: 0xf60
-  __TEXT.__cstring: 0x22d4
+  __TEXT.__cstring: 0x26e4
   __TEXT.__gcc_except_tab: 0x2b0
   __TEXT.__oslogstring: 0x14e6
   __TEXT.__swift5_typeref: 0x3d4

   __TEXT.__swift_as_entry: 0x18
   __TEXT.__swift_as_ret: 0x18
   __TEXT.__swift_as_cont: 0x14
-  __TEXT.__unwind_info: 0xe78
+  __TEXT.__unwind_info: 0xec8
   __TEXT.__eh_frame: 0x330
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x490
+  __DATA_CONST.__const: 0x4a0
   __DATA_CONST.__objc_classlist: 0xc8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe20
-  __DATA_CONST.__objc_arraydata: 0x50
+  __DATA_CONST.__objc_selrefs: 0xeb0
+  __DATA_CONST.__objc_arraydata: 0xc0
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x1168
-  __AUTH_CONST.__cfstring: 0x2420
-  __AUTH_CONST.__objc_const: 0x4a88
+  __AUTH_CONST.__const: 0x1248
+  __AUTH_CONST.__cfstring: 0x2c20
+  __AUTH_CONST.__objc_const: 0x4a90
+  __AUTH_CONST.__objc_arrayobj: 0x18
+  __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x5a0
+  __AUTH_CONST.__auth_got: 0x5a8
   __DATA.__objc_protorefs: 0x38
-  __DATA.__objc_classrefs: 0x160
+  __DATA.__objc_classrefs: 0x178
   __DATA.__objc_superrefs: 0x58
   __DATA.__objc_ivar: 0x1a0
   __DATA.__data: 0x210
-  __DATA.__bss: 0x11d0
+  __DATA.__bss: 0x11e0
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x7d0
   __DATA_DIRTY.__data: 0x650

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 1141
-  Symbols:   1579
-  CStrings:  446
+  Functions: 1161
+  Symbols:   1631
+  CStrings:  513
 
Symbols:
+ +[FLTelemetryAnalyticsSender isEventUsed:]
+ +[FLTelemetryProcessor sharedProcessor]
+ -[FLApprovedItemsFilter approvalStatusForItem:logging:]
+ -[FLTelemetryAnalyticsController _captureItem:event:source:extra:]
+ -[FLTelemetryAnalyticsController _payloadForItem:extra:]
+ -[FLTelemetryAnalyticsController captureItemPost:isNew:process:]
+ -[FLTelemetryAnalyticsController captureNotificationDelivery:reason:]
+ -[FLTelemetryAnalyticsController captureSnapshotWithItems:trigger:]
+ -[FLTelemetryProcessor _itemsExcludingTests:]
+ -[FLTelemetryProcessor processItemPost:isNew:process:]
+ -[FLTelemetryProcessor processNotificationDelivery:reason:]
+ -[FLTelemetryProcessor processSnapshotWithItems:trigger:]
+ _AnalyticsIsEventUsed
+ _FLTelemetryItemBadges
+ _FLTelemetrySnapshotTriggerDaily
+ _FLTelemetryZeroedSnapshotCounts
+ _OBJC_CLASS_$_NSConstantArray
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ __OBJC_$_CLASS_METHODS_FLTelemetryProcessor
+ ___39+[FLTelemetryProcessor sharedProcessor]_block_invoke
+ ___45-[FLTelemetryProcessor _itemsExcludingTests:]_block_invoke
+ ___57-[FLTelemetryProcessor processSnapshotWithItems:trigger:]_block_invoke
+ ___66-[FLTelemetryAnalyticsController _captureItem:event:source:extra:]_block_invoke
+ ___67-[FLTelemetryAnalyticsController captureSnapshotWithItems:trigger:]_block_invoke
+ ___67-[FLTelemetryAnalyticsController captureSnapshotWithItems:trigger:]_block_invoke_2
+ ___69-[FLTelemetryAnalyticsController captureNotificationDelivery:reason:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e14_"NSArray"8?0l
+ ___block_descriptor_48_e8_32s40s_e46_v32?0"NSString"8"NSMutableDictionary"16^B24l
+ ___block_descriptor_64_e8_32s40s48s56s_e19_"NSDictionary"8?0l
+ ___block_descriptor_72_e8_32s40s48s56s_e19_"NSDictionary"8?0l
+ ___copy_helper_block_e8_32s40s
+ _objc_msgSend$_captureItem:event:source:extra:
+ _objc_msgSend$_itemsExcludingTests:
+ _objc_msgSend$_payloadForItem:extra:
+ _objc_msgSend$addEntriesFromDictionary:
+ _objc_msgSend$allValues
+ _objc_msgSend$approvalStatusForItem:logging:
+ _objc_msgSend$captureItemPost:isNew:process:
+ _objc_msgSend$captureNotificationDelivery:reason:
+ _objc_msgSend$captureSnapshotWithItems:trigger:
+ _objc_msgSend$collectionIdentifier
+ _objc_msgSend$component:fromDate:
+ _objc_msgSend$componentsJoinedByString:
+ _objc_msgSend$creationDate
+ _objc_msgSend$enumerateKeysAndObjectsUsingBlock:
+ _objc_msgSend$firstNotificationDelay
+ _objc_msgSend$frequency
+ _objc_msgSend$initWithController:
+ _objc_msgSend$isEventUsed:
+ _objc_msgSend$numberWithLongLong:
+ _objc_msgSend$previousNotificationActionDate
+ _objc_msgSend$set
+ _objc_msgSend$sharedFilter
+ _objc_msgSend$sharedTelemetryController
+ _objc_msgSend$sortedArrayUsingSelector:
+ _objc_msgSend$unsignedIntegerValue
+ _sharedProcessor.onceToken
+ _sharedProcessor.processor
+ _sharedTelemetryController.controller
- -[FLTelemetryAnalyticsController _captureItem:event:source:]
- -[FLTelemetryAnalyticsController captureItemAddition:]
- -[FLTelemetryProcessor processItemAddition:]
- ___44-[FLTelemetryProcessor processCurrentItems:]_block_invoke
- ___60-[FLTelemetryAnalyticsController _captureItem:event:source:]_block_invoke
- _objc_msgSend$_captureItem:event:source:
- _objc_msgSend$captureItemAddition:
CStrings:
+ ","
+ "@\"NSArray\"8@?0"
+ "Priority"
+ "actionCount"
+ "alert"
+ "approval"
+ "approved"
+ "badgeOnly"
+ "badges"
+ "badging"
+ "clientUpdated"
+ "collection"
+ "com.apple.AppleIntelligence.FollowUp.RegionalOnboarding"
+ "com.apple.Health.MedicalID.familySetupReviewFollowUp"
+ "com.apple.followup.clientSnapshot"
+ "com.apple.followup.notificationPosted"
+ "com.apple.followup.snapshot"
+ "critical"
+ "criticalPriority"
+ "daily"
+ "default"
+ "defaultPriority"
+ "displayStyle"
+ "distinctClients"
+ "expired"
+ "firstNotificationDelaySeconds"
+ "forced"
+ "forcesDelivery"
+ "hasExpiration"
+ "hasExtension"
+ "hasNotification"
+ "high"
+ "highPriority"
+ "i"
+ "isExpired"
+ "isRepeat"
+ "localHour"
+ "maxItemsPerClient"
+ "notificationAgeSeconds"
+ "notificationFrequencySeconds"
+ "notificationOptions"
+ "notifiesAlert"
+ "notifiesBanner"
+ "notifiesLockScreen"
+ "notifiesNotificationCenter"
+ "offers"
+ "oldestNotificationAgeSeconds"
+ "priority"
+ "process"
+ "reason"
+ "rejected"
+ "repeatingNotification"
+ "repeatsNotification"
+ "required"
+ "scheduled"
+ "secondsSincePreviousDelivery"
+ "settingsTopLevel"
+ "suggested"
+ "targetBundle"
+ "total"
+ "trigger"
+ "typeIdentifier"
+ "unknown"
+ "update"
+ "v32@?0@\"NSString\"8@\"NSMutableDictionary\"16^B24"
+ "withNotification"
+ "zeroAction"
```
