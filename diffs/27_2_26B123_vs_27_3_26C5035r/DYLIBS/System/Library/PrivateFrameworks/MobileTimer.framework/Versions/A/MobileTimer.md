## MobileTimer

> `/System/Library/PrivateFrameworks/MobileTimer.framework/Versions/A/MobileTimer`

```diff

-2333.2.6.0.0
-  __TEXT.__text: 0xfb934
-  __TEXT.__objc_methlist: 0xaf34
+2333.3.4.0.0
+  __TEXT.__text: 0x10231c
+  __TEXT.__objc_methlist: 0xb1bc
   __TEXT.__const: 0x1f60
-  __TEXT.__gcc_except_tab: 0xb64
-  __TEXT.__cstring: 0x7dc2
-  __TEXT.__oslogstring: 0xc7b3
-  __TEXT.__dlopen_cstrs: 0x415
+  __TEXT.__gcc_except_tab: 0xb94
+  __TEXT.__cstring: 0x7f32
+  __TEXT.__oslogstring: 0xd9f3
+  __TEXT.__dlopen_cstrs: 0x4cb
   __TEXT.__ustring: 0x2c
   __TEXT.__swift5_typeref: 0x1070
   __TEXT.__swift5_reflstr: 0x4cd

   __TEXT.__swift_as_cont: 0x3e8
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x5350
+  __TEXT.__unwind_info: 0x5598
   __TEXT.__eh_frame: 0x4310
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x19c0
-  __DATA_CONST.__objc_classlist: 0x598
+  __DATA_CONST.__const: 0x1a50
+  __DATA_CONST.__objc_classlist: 0x5a0
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x280
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x51a8
+  __DATA_CONST.__objc_selrefs: 0x52b0
   __DATA_CONST.__objc_protorefs: 0x80
-  __DATA_CONST.__objc_superrefs: 0x350
-  __DATA_CONST.__objc_arraydata: 0x38
-  __DATA_CONST.__got: 0xa38
-  __AUTH_CONST.__const: 0x7c78
-  __AUTH_CONST.__cfstring: 0x6120
-  __AUTH_CONST.__objc_const: 0x1e940
-  __AUTH_CONST.__objc_arrayobj: 0x30
+  __DATA_CONST.__objc_superrefs: 0x358
+  __DATA_CONST.__objc_arraydata: 0x58
+  __DATA_CONST.__got: 0xa40
+  __AUTH_CONST.__const: 0x7e58
+  __AUTH_CONST.__cfstring: 0x6200
+  __AUTH_CONST.__objc_const: 0x1f208
+  __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0xc38
-  __AUTH.__objc_data: 0x2218
+  __AUTH_CONST.__auth_got: 0xc40
+  __AUTH.__objc_data: 0x2268
   __AUTH.__data: 0x460
-  __DATA.__objc_ivar: 0x754
+  __DATA.__objc_ivar: 0x77c
   __DATA.__data: 0x1ff8
   __DATA.__common: 0x78
-  __DATA.__bss: 0x18d0
+  __DATA.__bss: 0x1900
   __DATA_DIRTY.__objc_data: 0x1dd0
   __DATA_DIRTY.__data: 0x558
   __DATA_DIRTY.__bss: 0x490

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 6338
-  Symbols:   9602
-  CStrings:  2102
+  Functions: 6501
+  Symbols:   9763
+  CStrings:  2200
 
Symbols:
+ +[MTFeatures supportsLiveActivitiesQFA]
+ -[MTActivityCoordinator .cxx_destruct]
+ -[MTActivityCoordinator _dismissAlarmWithId:]
+ -[MTActivityCoordinator _dismissTimerWithId:]
+ -[MTActivityCoordinator activitiesManager]
+ -[MTActivityCoordinator alarmStorage]
+ -[MTActivityCoordinator clearStaleAlarmSessions]
+ -[MTActivityCoordinator clearStaleTimerSessions]
+ -[MTActivityCoordinator currentDateProvider]
+ -[MTActivityCoordinator didAlertNotificationWithID:]
+ -[MTActivityCoordinator didRestoreAlarmSessions:]
+ -[MTActivityCoordinator endAlertingSession]
+ -[MTActivityCoordinator handleAlarmStorageReady]
+ -[MTActivityCoordinator handleSystemReady]
+ -[MTActivityCoordinator handleTimerStorageReady]
+ -[MTActivityCoordinator initWithStorage:alarmStorage:notificationCenter:]
+ -[MTActivityCoordinator nextTimerDidChange:]
+ -[MTActivityCoordinator notificationCenter]
+ -[MTActivityCoordinator processAlarmUpdate:fromAlarm:]
+ -[MTActivityCoordinator processTimerStateUpdate:fromTimer:]
+ -[MTActivityCoordinator processTimerUpdate:fromTimer:changeSet:]
+ -[MTActivityCoordinator registerAnalyticsDelegate:]
+ -[MTActivityCoordinator reportingDelegate]
+ -[MTActivityCoordinator restoreAlarmSnoozeSessions]
+ -[MTActivityCoordinator restoreTimerCountdownSessions]
+ -[MTActivityCoordinator serializerQueue]
+ -[MTActivityCoordinator serializer]
+ -[MTActivityCoordinator setActivitiesManager:]
+ -[MTActivityCoordinator setCurrentDateProvider:]
+ -[MTActivityCoordinator setReportingDelegate:]
+ -[MTActivityCoordinator setSerializer:]
+ -[MTActivityCoordinator setSerializerQueue:]
+ -[MTActivityCoordinator setSystemReady:]
+ -[MTActivityCoordinator source:didAddAlarms:]
+ -[MTActivityCoordinator source:didAddTimers:]
+ -[MTActivityCoordinator source:didChangeNextAlarm:]
+ -[MTActivityCoordinator source:didDismissAlarm:dismissAction:]
+ -[MTActivityCoordinator source:didDismissTimer:]
+ -[MTActivityCoordinator source:didFireAlarm:triggerType:]
+ -[MTActivityCoordinator source:didFireTimer:]
+ -[MTActivityCoordinator source:didRemoveAlarms:]
+ -[MTActivityCoordinator source:didRemoveTimers:]
+ -[MTActivityCoordinator source:didSnoozeAlarm:snoozeAction:]
+ -[MTActivityCoordinator source:didUpdateAlarms:]
+ -[MTActivityCoordinator source:didUpdateAlarms:previousAlarms:]
+ -[MTActivityCoordinator source:didUpdateTimers:]
+ -[MTActivityCoordinator source:didUpdateTimers:fromTimers:]
+ -[MTActivityCoordinator sourceIdentifier]
+ -[MTActivityCoordinator systemReady]
+ -[MTActivityCoordinator timerStorage]
+ -[MTActivityCoordinator useAlarmKitActivities]
+ -[MTAgent activityCoordinator]
+ -[MTAgent setActivityCoordinator:]
+ _MGCopyAnswer
+ _OBJC_CLASS_$_MTActivityCoordinator
+ _OBJC_IVAR_$_MTActivityCoordinator._activitiesManager
+ _OBJC_IVAR_$_MTActivityCoordinator._alarmStorage
+ _OBJC_IVAR_$_MTActivityCoordinator._currentDateProvider
+ _OBJC_IVAR_$_MTActivityCoordinator._notificationCenter
+ _OBJC_IVAR_$_MTActivityCoordinator._reportingDelegate
+ _OBJC_IVAR_$_MTActivityCoordinator._serializer
+ _OBJC_IVAR_$_MTActivityCoordinator._serializerQueue
+ _OBJC_IVAR_$_MTActivityCoordinator._systemReady
+ _OBJC_IVAR_$_MTActivityCoordinator._timerStorage
+ _OBJC_IVAR_$_MTAgent._activityCoordinator
+ _OBJC_METACLASS_$_MTActivityCoordinator
+ _OUTLINED_FUNCTION_7
+ _OUTLINED_FUNCTION_8
+ _OUTLINED_FUNCTION_9
+ __OBJC_$_INSTANCE_METHODS_MTActivityCoordinator
+ __OBJC_$_INSTANCE_VARIABLES_MTActivityCoordinator
+ __OBJC_$_PROP_LIST_MTActivityCoordinator
+ __OBJC_CLASS_PROTOCOLS_$_MTActivityCoordinator
+ __OBJC_CLASS_RO_$_MTActivityCoordinator
+ __OBJC_METACLASS_RO_$_MTActivityCoordinator
+ ___39+[MTFeatures supportsLiveActivitiesQFA]_block_invoke
+ ___45-[MTActivityCoordinator _dismissAlarmWithId:]_block_invoke
+ ___45-[MTActivityCoordinator _dismissAlarmWithId:]_block_invoke_2
+ ___45-[MTActivityCoordinator _dismissTimerWithId:]_block_invoke
+ ___45-[MTActivityCoordinator _dismissTimerWithId:]_block_invoke_2
+ ___45-[MTActivityCoordinator source:didAddTimers:]_block_invoke
+ ___45-[MTActivityCoordinator source:didAddTimers:]_block_invoke_2
+ ___45-[MTActivityCoordinator source:didAddTimers:]_block_invoke_3
+ ___45-[MTActivityCoordinator source:didFireTimer:]_block_invoke
+ ___45-[MTActivityCoordinator source:didFireTimer:]_block_invoke_2
+ ___48-[MTActivityCoordinator clearStaleAlarmSessions]_block_invoke
+ ___48-[MTActivityCoordinator clearStaleAlarmSessions]_block_invoke_2
+ ___48-[MTActivityCoordinator clearStaleTimerSessions]_block_invoke
+ ___48-[MTActivityCoordinator clearStaleTimerSessions]_block_invoke_2
+ ___48-[MTActivityCoordinator clearStaleTimerSessions]_block_invoke_3
+ ___48-[MTActivityCoordinator source:didDismissTimer:]_block_invoke
+ ___48-[MTActivityCoordinator source:didDismissTimer:]_block_invoke_2
+ ___48-[MTActivityCoordinator source:didRemoveAlarms:]_block_invoke
+ ___48-[MTActivityCoordinator source:didRemoveAlarms:]_block_invoke_2
+ ___48-[MTActivityCoordinator source:didRemoveTimers:]_block_invoke
+ ___48-[MTActivityCoordinator source:didRemoveTimers:]_block_invoke_2
+ ___48-[MTActivityCoordinator source:didRemoveTimers:]_block_invoke_3
+ ___49-[MTActivityCoordinator didRestoreAlarmSessions:]_block_invoke
+ ___49-[MTActivityCoordinator didRestoreAlarmSessions:]_block_invoke_2
+ ___49-[MTActivityCoordinator didRestoreAlarmSessions:]_block_invoke_3
+ ___51-[MTActivityCoordinator restoreAlarmSnoozeSessions]_block_invoke
+ ___51-[MTActivityCoordinator restoreAlarmSnoozeSessions]_block_invoke_2
+ ___51-[MTActivityCoordinator restoreAlarmSnoozeSessions]_block_invoke_3
+ ___54-[MTActivityCoordinator processAlarmUpdate:fromAlarm:]_block_invoke
+ ___54-[MTActivityCoordinator processAlarmUpdate:fromAlarm:]_block_invoke_2
+ ___54-[MTActivityCoordinator restoreTimerCountdownSessions]_block_invoke
+ ___54-[MTActivityCoordinator restoreTimerCountdownSessions]_block_invoke_2
+ ___57-[MTActivityCoordinator source:didFireAlarm:triggerType:]_block_invoke
+ ___57-[MTActivityCoordinator source:didFireAlarm:triggerType:]_block_invoke_2
+ ___57-[MTActivityCoordinator source:didFireAlarm:triggerType:]_block_invoke_3
+ ___59-[MTActivityCoordinator processTimerStateUpdate:fromTimer:]_block_invoke
+ ___59-[MTActivityCoordinator processTimerStateUpdate:fromTimer:]_block_invoke_2
+ ___59-[MTActivityCoordinator source:didUpdateTimers:fromTimers:]_block_invoke
+ ___59-[MTActivityCoordinator source:didUpdateTimers:fromTimers:]_block_invoke_2
+ ___59-[MTActivityCoordinator source:didUpdateTimers:fromTimers:]_block_invoke_3
+ ___60-[MTActivityCoordinator source:didSnoozeAlarm:snoozeAction:]_block_invoke
+ ___60-[MTActivityCoordinator source:didSnoozeAlarm:snoozeAction:]_block_invoke_2
+ ___62-[MTActivityCoordinator source:didDismissAlarm:dismissAction:]_block_invoke
+ ___62-[MTActivityCoordinator source:didDismissAlarm:dismissAction:]_block_invoke_2
+ ___63-[MTActivityCoordinator source:didUpdateAlarms:previousAlarms:]_block_invoke
+ ___63-[MTActivityCoordinator source:didUpdateAlarms:previousAlarms:]_block_invoke_2
+ ___64-[MTActivityCoordinator processTimerUpdate:fromTimer:changeSet:]_block_invoke
+ ___64-[MTActivityCoordinator processTimerUpdate:fromTimer:changeSet:]_block_invoke_2
+ ___block_descriptor_32_e18_v16?0"NSString"8l
+ ___block_descriptor_32_e27_"NSString"16?0"MTAlarm"8l
+ ___block_descriptor_32_e27_"NSString"16?0"MTTimer"8l
+ ___block_descriptor_40_e8_32s_e18_v16?0"NSString"8l
+ ___block_descriptor_48_e8_32s40s_e17_v16?0"MTTimer"8l
+ ___block_descriptor_48_e8_32s40s_e20_v20?0"MTAlarm"8B16l
+ ___block_descriptor_48_e8_32s40s_e30_v24?0"NSString"8"NSError"16l
+ ___getMTActivitiesManagerClass_block_invoke
+ _getMTActivitiesManagerClass.softClass
+ _objc_msgSend$alarmActivities:
+ _objc_msgSend$alarmCountdownActivities:
+ _objc_msgSend$alertActivityWithAlarm:playSound:completion:
+ _objc_msgSend$alertActivityWithTimer:completion:
+ _objc_msgSend$clearStaleAlarmSessions
+ _objc_msgSend$clearStaleTimerSessions
+ _objc_msgSend$createActivityWithTimer:completion:
+ _objc_msgSend$didCreateLiveActivityForAlarm:withId:date:
+ _objc_msgSend$endActivityWithAlarmID:completion:
+ _objc_msgSend$endActivityWithTimerID:completion:
+ _objc_msgSend$handleAlarmStorageReady
+ _objc_msgSend$handleTimerStorageReady
+ _objc_msgSend$initWithStorage:alarmStorage:notificationCenter:
+ _objc_msgSend$processAlarmUpdate:fromAlarm:
+ _objc_msgSend$processTimerStateUpdate:fromTimer:
+ _objc_msgSend$processTimerUpdate:fromTimer:changeSet:
+ _objc_msgSend$propertiesAffectingSessions
+ _objc_msgSend$restoreActivityWithAlarm:completion:
+ _objc_msgSend$restoreActivityWithTimer:completion:
+ _objc_msgSend$restoreAlarmSnoozeSessions
+ _objc_msgSend$restoreTimerCountdownSessions
+ _objc_msgSend$supportsLiveActivitiesQFA
+ _objc_msgSend$timerActivities:
+ _objc_msgSend$timerCountdownActivities:
+ _objc_msgSend$updateActivityWithAlarm:completion:
+ _objc_msgSend$updateActivityWithTimer:completion:
+ _objc_msgSend$useAlarmKitActivities
+ _supportsLiveActivitiesQFA.isSupportedHardware
+ _supportsLiveActivitiesQFA.onceToken
CStrings:
+ "%{public}@ Skipping user notification for %{public}@ on macOS, activities enabled"
+ "%{public}@ cannot process timer state change: %{public}@"
+ "%{public}@ did add timers, starting sessions"
+ "%{public}@ didRestoreAlarmSessions with ids: %{public}@"
+ "%{public}@ dismissing alarm completed with error: %{public}@"
+ "%{public}@ dismissing timer completed with error: %{public}@"
+ "%{public}@ error alerting alarm activity in didFireAlarm: %{public}@. Did not return activity id"
+ "%{public}@ error alerting alarm activity in didFireAlarm: %{public}@. Error: %{public}@"
+ "%{public}@ error alerting timer activity in didFireTimer: %{public}@"
+ "%{public}@ error creating alarm activity in restoreAlarmSnoozeSessions: %{public}@, %{public}@"
+ "%{public}@ error creating timer activity in didAddTimers: %{public}@"
+ "%{public}@ error creating timer activity in restoreTimerCountdownSessions: %{public}@, %{public}@"
+ "%{public}@ error ending alarm activity in didDismissAlarm: %{public}@. Error: %{public}@"
+ "%{public}@ error ending alarm activity: %{public}@, %{public}@"
+ "%{public}@ error ending timer activity in didDismissTimer: %{public}@"
+ "%{public}@ error ending timer activity in didFireTimer: %{public}@"
+ "%{public}@ error ending timer activity in didRemoveTimers: %{public}@. Error: %{public}@"
+ "%{public}@ error ending timer activity in processTimerStateUpdate: %{public}@. Error: %{public}@"
+ "%{public}@ error ending timer activity: %{public}@, %{public}@"
+ "%{public}@ error updating timer activity in processTimerStateUpdate: %{public}@. Error: %{public}@"
+ "%{public}@ error updating timer activity in processTimerUpdate: %{public}@. Error: %{public}@"
+ "%{public}@ fire time changed for timer id: %{public}@ from: %{public}@ to: %{public}@, restarting"
+ "%{public}@ interrupting audio for timer %{public}@"
+ "%{public}@ not posting alert for stop playing timer %{public}@"
+ "%{public}@ not removing session for alarm: %{public}@"
+ "%{public}@ process timer state update: %{public}@, old timer: %{public}@"
+ "%{public}@ processAlarmUpdate alarm:%{public}@ fromAlarm:%{public}@"
+ "%{public}@ received dismiss alarm action for id: %{public}@"
+ "%{public}@ received dismiss timer action for id: %{public}@"
+ "%{public}@ removing inactive alarm sessions: %{public}@"
+ "%{public}@ setting up activity coordinator"
+ "%{public}@ starting/resuming timer"
+ "%{public}@ successfully creating alarm activity in restoreAlarmSnoozeSessions: %{public}@"
+ "%{public}@ successfully creating timer activity in restoreTimerCountdownSessions: %{public}@"
+ "%{public}@ timer update change set: %{public}@"
+ "%{public}@ trying to dismiss non-firing timer: %{public}@"
+ "%{public}@ trying to dismiss snoozed alarm with id: %{public}@"
+ "%{public}@ updating session title"
+ "%{public}@: NO-OP! handling firing timer via AlarmKit!"
+ "%{public}@: NO-OP! handling new timer via AlarmKit!"
+ "%{public}@: NO-OP! handling non-sleep alarm dismiss via AlarmKit!"
+ "%{public}@: NO-OP! handling non-sleep alarm fired via AlarmKit!"
+ "%{public}@: NO-OP! handling non-sleep alarm remove via AlarmKit!"
+ "%{public}@: NO-OP! handling non-sleep alarm snoozed via AlarmKit!"
+ "%{public}@: NO-OP! handling non-sleep alarm update via AlarmKit!"
+ "%{public}@: NO-OP! handling timer dismiss via AlarmKit!"
+ "%{public}@: NO-OP! handling timer remove via AlarmKit!"
+ "%{public}@: NO-OP! handling timer update via AlarmKit!"
+ "%{public}@: clearStaleAlarmSessions"
+ "%{public}@: clearStaleTimerSessions"
+ "%{public}@: didAddAlarms"
+ "%{public}@: didChangeNextAlarm"
+ "%{public}@: didDismissAlarm"
+ "%{public}@: didDismissTimer"
+ "%{public}@: didFireAlarm"
+ "%{public}@: didFireTimer"
+ "%{public}@: didRemoveAlarms"
+ "%{public}@: didRemoveTimers"
+ "%{public}@: didSnoozeAlarm"
+ "%{public}@: didSnoozeAlarm alarm %{public}@, error updating alarm activity: %{public}@"
+ "%{public}@: didSnoozeAlarm alarm %{public}@, successfully updated activity"
+ "%{public}@: didUpdateAlarms"
+ "%{public}@: didUpdateTimers"
+ "%{public}@: found %lu orphaned alarm activities: %{public}@"
+ "%{public}@: found %lu orphaned timer activities: %{public}@"
+ "%{public}@: found active alarm ids: %{public}@"
+ "%{public}@: handle alarm storage ready received"
+ "%{public}@: handle system ready received"
+ "%{public}@: handle timer storage ready received"
+ "%{public}@: next timer did change"
+ "%{public}@: remove alarm %{public}@, error ending alarm activity: %{public}@"
+ "%{public}@: remove alarm %{public}@, successfully ended activity"
+ "%{public}@: restoreAlarmSnoozeSessions"
+ "%{public}@: restoreTimerCountdownSessions"
+ "%{public}@: retreived active timers: %{public}@"
+ "%{public}@: retrieved active alarms: %{public}@"
+ "%{public}@: retrieved active timers: %{public}@"
+ "%{public}@: retrieved alarm activities: %{public}@"
+ "%{public}@: retrieved current alarm : %{public}@"
+ "@\"NSString\"16@?0@\"MTAlarm\"8"
+ "@\"NSString\"16@?0@\"MTTimer\"8"
+ "Class getMTActivitiesManagerClass(void)_block_invoke"
+ "ClockAdoptsAlarmKit"
+ "Initializing %{public}@ with timerStorage:%{public}@ alarmStorage:%{public}@"
+ "LiveActivitiesQFA"
+ "MTActivitiesManager"
+ "MTActivityCoordinator"
+ "MTActivityCoordinator.m"
+ "Mac17,10"
+ "Mac17,11"
+ "Mac17,12"
+ "Mac17,13"
+ "MenuBar"
+ "ProductType"
+ "com.apple.MTActivityCoordinator.serialqueue"
+ "v20@?0@\"MTAlarm\"8B16"
+ "v24@?0@\"NSString\"8@\"NSError\"16"
+ "\x81"
```
