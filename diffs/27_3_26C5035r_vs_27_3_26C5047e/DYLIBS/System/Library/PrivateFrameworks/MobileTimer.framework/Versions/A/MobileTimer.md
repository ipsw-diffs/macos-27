## MobileTimer

> `/System/Library/PrivateFrameworks/MobileTimer.framework/Versions/A/MobileTimer`

```diff

-2333.3.4.0.0
-  __TEXT.__text: 0x10231c
-  __TEXT.__objc_methlist: 0xb1bc
-  __TEXT.__const: 0x1f60
-  __TEXT.__gcc_except_tab: 0xb94
-  __TEXT.__cstring: 0x7f32
-  __TEXT.__oslogstring: 0xd9f3
+2333.3.6.0.0
+  __TEXT.__text: 0x103e34
+  __TEXT.__objc_methlist: 0xb2d4
+  __TEXT.__const: 0x1f70
+  __TEXT.__gcc_except_tab: 0xb90
+  __TEXT.__cstring: 0x7fa2
+  __TEXT.__oslogstring: 0xda73
   __TEXT.__dlopen_cstrs: 0x4cb
   __TEXT.__ustring: 0x2c
   __TEXT.__swift5_typeref: 0x1070

   __TEXT.__swift_as_cont: 0x3e8
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x5598
+  __TEXT.__unwind_info: 0x5aa0
   __TEXT.__eh_frame: 0x4310
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1a50
-  __DATA_CONST.__objc_classlist: 0x5a0
+  __DATA_CONST.__const: 0x1a58
+  __DATA_CONST.__objc_classlist: 0x5a8
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x280
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x52b0
+  __DATA_CONST.__objc_selrefs: 0x52f8
   __DATA_CONST.__objc_protorefs: 0x80
-  __DATA_CONST.__objc_superrefs: 0x358
+  __DATA_CONST.__objc_superrefs: 0x368
   __DATA_CONST.__objc_arraydata: 0x58
   __DATA_CONST.__got: 0xa40
   __AUTH_CONST.__const: 0x7e58
-  __AUTH_CONST.__cfstring: 0x6200
-  __AUTH_CONST.__objc_const: 0x1f208
+  __AUTH_CONST.__cfstring: 0x6260
+  __AUTH_CONST.__objc_const: 0x1f3c8
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0xc40
-  __AUTH.__objc_data: 0x2268
+  __AUTH.__objc_data: 0x22b8
   __AUTH.__data: 0x460
-  __DATA.__objc_ivar: 0x77c
+  __DATA.__objc_ivar: 0x794
   __DATA.__data: 0x1ff8
   __DATA.__common: 0x78
   __DATA.__bss: 0x1900

   __DATA_DIRTY.__data: 0x558
   __DATA_DIRTY.__bss: 0x490
   __DATA_DIRTY.__common: 0x18
+  - /System/Library/Frameworks/AppIntents.framework/Versions/A/AppIntents
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine
   - /System/Library/Frameworks/CoreData.framework/Versions/A/CoreData
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 6501
-  Symbols:   9763
-  CStrings:  2200
+  Functions: 6550
+  Symbols:   9829
+  CStrings:  2207
 
Symbols:
+ +[MTAppEntityDonor isAppIntentsSupportAvailable]
+ +[MTAppEntityDonor isLinwoodAvailable]
+ +[MTAppEntityDonor registerSpotlightClient:]
+ -[MTAppEntityDonor _queue_migrateIndexIfNeeded]
+ -[MTAppEntityDonor _queue_migrateIndex]
+ -[MTAppEntityDonor _queue_needsIndexMigration]
+ -[MTAppEntityDonor _queue_persistIndexVersion]
+ -[MTAppEntityDonor _queue_reindexAllItems]
+ -[MTAppEntityDonor initWithAlarmStorage:timerStorage:persistence:]
+ -[MTAppEntityDonor persistence]
+ -[MTAppEntityDonor serializerQueue]
+ -[MTAppEntityDonor serializer]
+ -[MTTimerService .cxx_destruct]
+ -[MTTimerService addTimer:withCompletion:]
+ -[MTTimerService dismissTimerWithIdentifier:withCompletion:]
+ -[MTTimerService getTimerDurationsWithCompletion:]
+ -[MTTimerService getTimersWithCompletion:]
+ -[MTTimerService initWithStorage:]
+ -[MTTimerService metrics]
+ -[MTTimerService removeTimer:withCompletion:]
+ -[MTTimerService serializer]
+ -[MTTimerService storage]
+ -[MTTimerService updateTimer:withCompletion:]
+ -[MTTimerService whenReady:]
+ GCC_except_table64
+ _OBJC_CLASS_$_MTTimerService
+ _OBJC_IVAR_$_MTAppEntityDonor._persistence
+ _OBJC_IVAR_$_MTAppEntityDonor._serializer
+ _OBJC_IVAR_$_MTAppEntityDonor._serializerQueue
+ _OBJC_IVAR_$_MTTimerService._metrics
+ _OBJC_IVAR_$_MTTimerService._serializer
+ _OBJC_IVAR_$_MTTimerService._storage
+ _OBJC_METACLASS_$_MTTimerService
+ __OBJC_$_CLASS_METHODS_MTAppEntityDonor
+ __OBJC_$_INSTANCE_METHODS_MTTimerService
+ __OBJC_$_INSTANCE_VARIABLES_MTTimerService
+ __OBJC_$_PROP_LIST_MTTimerService
+ __OBJC_CLASS_RO_$_MTTimerService
+ __OBJC_METACLASS_RO_$_MTTimerService
+ ___28-[MTTimerService whenReady:]_block_invoke
+ ___37-[MTAppEntityDonor handleSystemReady]_block_invoke
+ ___40-[MTAppEntityDonor source:didAddTimers:]_block_invoke
+ ___40-[MTAppEntityDonor source:didFireTimer:]_block_invoke
+ ___42-[MTTimerService addTimer:withCompletion:]_block_invoke
+ ___42-[MTTimerService getTimersWithCompletion:]_block_invoke
+ ___43-[MTAppEntityDonor source:didDismissTimer:]_block_invoke
+ ___43-[MTAppEntityDonor source:didRemoveAlarms:]_block_invoke
+ ___43-[MTAppEntityDonor source:didRemoveTimers:]_block_invoke
+ ___43-[MTAppEntityDonor source:didUpdateTimers:]_block_invoke
+ ___45-[MTTimerService removeTimer:withCompletion:]_block_invoke
+ ___45-[MTTimerService updateTimer:withCompletion:]_block_invoke
+ ___47-[MTAppEntityDonor _queue_migrateIndexIfNeeded]_block_invoke
+ ___47-[MTAppEntityDonor _queue_migrateIndexIfNeeded]_block_invoke_2
+ ___47-[MTAppEntityDonor _queue_migrateIndexIfNeeded]_block_invoke_3
+ ___50-[MTTimerService getTimerDurationsWithCompletion:]_block_invoke
+ ___52-[MTAppEntityDonor source:didFireAlarm:triggerType:]_block_invoke
+ ___57-[MTAppEntityDonor handleNotification:ofType:completion:]_block_invoke
+ ___57-[MTAppEntityDonor source:didDismissAlarm:dismissAction:]_block_invoke
+ ___60-[MTTimerService dismissTimerWithIdentifier:withCompletion:]_block_invoke
+ ___86-[MTAppEntityDonor reindexAllItemsForBundleID:protectionClass:acknowledgementHandler:]_block_invoke
+ _kMTAppEntityIndexVersion
+ _kMTAppEntityIndexVersionKey
+ _objc_msgSend$_queue_migrateIndex
+ _objc_msgSend$_queue_migrateIndexIfNeeded
+ _objc_msgSend$_queue_needsIndexMigration
+ _objc_msgSend$_queue_persistIndexVersion
+ _objc_msgSend$_queue_reindexAllItems
+ _objc_msgSend$initWithAlarmStorage:timerStorage:persistence:
+ _objc_msgSend$isAppIntentsSupportAvailable
+ _objc_msgSend$isLinwoodAvailable
+ _objc_msgSend$registerSpotlightClient:
- -[MTAppEntityDonor initWithAlarmStorage:timerStorage:]
- -[MTAppEntityDonor reindexAllItems]
- GCC_except_table2
- GCC_except_table7
- _objc_msgSend$reindexAllItems
CStrings:
+ "%{public}@ migrated index to version %f"
+ "%{public}@ migrating index to version %f"
+ "%{public}@ store not loaded, dropping index migration"
+ "MTAppEntityIndexVersion"
+ "MTTimerService.m"
+ "com.apple.MTAppEntityDonor.serial"
+ "com.apple.MTTimerService.access-queue"
```
