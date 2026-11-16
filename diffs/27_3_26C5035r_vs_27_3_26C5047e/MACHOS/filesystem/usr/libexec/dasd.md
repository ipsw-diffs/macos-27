## dasd

> `/usr/libexec/dasd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_ptr`

```diff

-2467.60.9.0.0
-  __TEXT.__text: 0x139dd0
-  __TEXT.__auth_stubs: 0x1e90
-  __TEXT.__objc_stubs: 0x15fa0
-  __TEXT.__objc_methlist: 0xff1c
+2467.60.20.0.0
+  __TEXT.__text: 0x13f1e8
+  __TEXT.__auth_stubs: 0x1ec0
+  __TEXT.__objc_stubs: 0x165e0
+  __TEXT.__objc_methlist: 0x104ac
   __TEXT.__const: 0x1288
-  __TEXT.__objc_methname: 0x25deb
-  __TEXT.__cstring: 0xcc26
-  __TEXT.__oslogstring: 0x10789
-  __TEXT.__objc_classname: 0x18d8
-  __TEXT.__objc_methtype: 0x33b1
-  __TEXT.__gcc_except_tab: 0x3b90
+  __TEXT.__objc_methname: 0x26a18
+  __TEXT.__cstring: 0xd026
+  __TEXT.__oslogstring: 0x10d49
+  __TEXT.__objc_classname: 0x1958
+  __TEXT.__objc_methtype: 0x3471
+  __TEXT.__gcc_except_tab: 0x3db4
   __TEXT.__dlopen_cstrs: 0x268
   __TEXT.__swift5_typeref: 0x8f8
   __TEXT.__swift5_capture: 0x1e4

   __TEXT.__swift_as_cont: 0x78
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x52f8
+  __TEXT.__unwind_info: 0x54a8
   __TEXT.__eh_frame: 0xbb0
-  __DATA_CONST.__const: 0x4330
-  __DATA_CONST.__cfstring: 0xe2e0
-  __DATA_CONST.__objc_classlist: 0x640
+  __DATA_CONST.__const: 0x4440
+  __DATA_CONST.__cfstring: 0xe720
+  __DATA_CONST.__objc_classlist: 0x668
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x1c0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x60
-  __DATA_CONST.__objc_superrefs: 0x530
-  __DATA_CONST.__objc_intobj: 0x1380
+  __DATA_CONST.__objc_superrefs: 0x558
+  __DATA_CONST.__objc_intobj: 0x1398
   __DATA_CONST.__objc_arraydata: 0x238
   __DATA_CONST.__objc_arrayobj: 0xf0
   __DATA_CONST.__objc_doubleobj: 0x30
   __DATA_CONST.__objc_dictobj: 0x168
-  __DATA_CONST.__auth_got: 0xf58
-  __DATA_CONST.__got: 0xb08
+  __DATA_CONST.__auth_got: 0xf70
+  __DATA_CONST.__got: 0xb18
   __DATA_CONST.__auth_ptr: 0x190
-  __DATA.__objc_const: 0x2c070
-  __DATA.__objc_selrefs: 0x80b0
-  __DATA.__objc_ivar: 0x1244
-  __DATA.__objc_data: 0x4138
-  __DATA.__data: 0x1c98
-  __DATA.__bss: 0x11f0
+  __DATA.__objc_const: 0x2cf08
+  __DATA.__objc_selrefs: 0x8348
+  __DATA.__objc_ivar: 0x12d4
+  __DATA.__objc_data: 0x42c8
+  __DATA.__data: 0x1cb8
+  __DATA.__bss: 0x1230
   __DATA.__common: 0x18
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices
   - /System/Library/Frameworks/CoreData.framework/Versions/A/CoreData

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6990
-  Symbols:   866
-  CStrings:  9976
+  Functions: 7128
+  Symbols:   871
+  CStrings:  10179
 
Symbols:
+ _CFBooleanGetTypeID
+ _NSCocoaErrorDomain
+ _NSURLIsExcludedFromBackupKey
+ _memchr
+ _os_unfair_recursive_lock_lock
+ _strlen
- _os_unfair_recursive_lock_lock_with_options
CStrings:
+ "/System/Library/DuetActivityScheduler/Scheduler/Resources/com.apple.dasd.taskAppMap.plist"
+ "@\"_DASClientMetricsRecorder\""
+ "@\"_DASPersonalizedSchedulingMetrics\""
+ "App usage priorities v%lu accepted (previous %{public}@): %lu entries, %lu high, %lu low, %lu skipped, unchanged %{BOOL}d"
+ "App usage priorities v%lu rejected (%{public}@ v%lu, age %.0fs): %lu entries"
+ "App usage priorities v%lu rejected (%{public}@): %lu entries"
+ "Apps"
+ "B16@?0@8"
+ "B48@0:8@16Q24@32^@40"
+ "Failed to exclude app usage priorities from backup: %@"
+ "Failed to persist app usage priorities: %@"
+ "Failed to persist personalized scheduling metrics: %@"
+ "Failed to report %{public}@ to TaskThroughput"
+ "Holds discretionary and intensive tasks while a sysdiagnose is captured."
+ "Invalid persisted app usage priorities"
+ "Invalid persisted personalized scheduling metrics"
+ "Loaded app usage priorities v%lu: %lu entries, age %.0fs, stale %{BOOL}d"
+ "Loaded task app map: %lu prefixes, medium: %lu services, %lu feature codes, %lu prefixes, %lu name substrings, %lu skipped, %lu listed under more than one app"
+ "MediumFeatureCodes"
+ "MediumNameSubstrings"
+ "MediumServices"
+ "MediumTaskPrefixes"
+ "No persisted app usage priorities"
+ "No sysdiagnose stopped notification after %.0fs, releasing held tasks"
+ "Persisted app usage priorities unavailable, will retry: %@"
+ "PersonalizedSchedulingEnabled"
+ "PersonalizedSchedulingSpotlightUsesAppPriority"
+ "PersonalizedSchedulingWeightHigh"
+ "PersonalizedSchedulingWeightLow"
+ "PersonalizedSchedulingWeightMedium"
+ "Please file a bug for – client %{public}@ attempted to read app usage priorities but lacked appropriate entitlement"
+ "Please file a bug for – client %{public}@ attempted to update app usage priorities but lacked appropriate entitlement"
+ "QoSPolicyPostCSPNEnabled"
+ "Reported personalized scheduling metrics: completed %lu/%lu/%lu (low/medium/high)"
+ "Sysdiagnose started, holding discretionary and intensive tasks"
+ "Sysdiagnose stopped, releasing held tasks"
+ "T@\"NSArray\",R,N,V_mediumNameSubstrings"
+ "T@\"NSArray\",R,N,V_mediumTaskPrefixes"
+ "T@\"NSArray\",R,N,V_prefixes"
+ "T@\"NSDate\",&,N,V_lastFlushDate"
+ "T@\"NSDate\",&,N,V_lastPersistDate"
+ "T@\"NSDictionary\",&,N,V_record"
+ "T@\"NSDictionary\",R,N,V_prefixToApp"
+ "T@\"NSDictionary\",R,N,V_priorities"
+ "T@\"NSMutableDictionary\",&,N,V_trackingKeysByActivity"
+ "T@\"NSSet\",R,N,V_mediumFeatureCodes"
+ "T@\"NSSet\",R,N,V_mediumServices"
+ "T@\"NSURL\",&,N,V_fileURL"
+ "T@\"_DASClientMetricsRecorder\",&,N,V_recorder"
+ "T@\"_DASPersonalizedSchedulingMetrics\",&,N,V_personalizedSchedulingMetrics"
+ "TB,GisPostCSPNEnabled,V_postCSPNEnabled"
+ "TB,N"
+ "TB,N,V_loaded"
+ "TB,N,V_loggedLoadFailure"
+ "TB,V_sysdiagnoseInProgress"
+ "TLC prediction"
+ "TQ,N,V_captureCount"
+ "Task app map unavailable: %@"
+ "Ti,N,V_startedToken"
+ "Ti,N,V_stoppedToken"
+ "Trial: %{public}@ %{public}s, post-CSPN condition %{public}s"
+ "Trial: PersonalizedScheduling weights set to %.2f / %.2f / %.2f (high / medium / low)"
+ "Trial: PersonalizedSchedulingEnabled set to %d"
+ "Trial: PersonalizedSchedulingSpotlightUsesAppPriority set to %d"
+ "T{os_unfair_recursive_lock_s=[2I]},N,V_activityStateLock"
+ "T{os_unfair_recursive_lock_s=[2I]},N,V_applicationLaunchRequestsLock"
+ "T{os_unfair_recursive_lock_s=[2I]},N,V_lock"
+ "T{os_unfair_recursive_lock_s=[2I]},N,V_purgeableSpaceMapLock"
+ "URLByAppendingPathComponent:"
+ "[3Q]"
+ "[3d]"
+ "_DASAppUsagePriorityCache"
+ "_DASAppUsagePrioritySnapshot"
+ "_DASPersonalizedSchedulingMetrics"
+ "_DASSysdiagnosePolicy"
+ "_DASTaskAppMap"
+ "_captureCount"
+ "_completedCount"
+ "_completionTime"
+ "_fileURL"
+ "_lastFlushDate"
+ "_lastPersistDate"
+ "_loaded"
+ "_loggedLoadFailure"
+ "_mediumFeatureCodes"
+ "_mediumNameSubstrings"
+ "_mediumServices"
+ "_mediumTaskPrefixes"
+ "_personalizedSchedulingMetrics"
+ "_phaseSchedulingEnabled"
+ "_postCSPNEnabled"
+ "_prefixToApp"
+ "_prefixes"
+ "_priorities"
+ "_record"
+ "_recorder"
+ "_runtime"
+ "_startedToken"
+ "_stoppedToken"
+ "_sysdiagnoseInProgress"
+ "_trackingKeysByActivity"
+ "_weightHigh"
+ "_weightLow"
+ "_weightMedium"
+ "app:"
+ "appUsagePriorities.plist"
+ "appUsagePriority"
+ "appUsagePrioritySnapshotForActivities:date:"
+ "captureCount"
+ "com.apple.das.private.usagepriorities"
+ "com.apple.das.private.usagepriorities.read"
+ "com.apple.das.sysdiagnose.statuschanged"
+ "com.apple.dasd.personalizedScheduling"
+ "com.apple.dasd.personalizedScheduling.high"
+ "com.apple.dasd.personalizedScheduling.low"
+ "com.apple.dasd.personalizedScheduling.medium"
+ "com.apple.dasd.personalizedSchedulingMetrics"
+ "com.apple.dasd.sysdiagnosepolicy"
+ "com.apple.sysdiagnose.sysdiagnoseStopped"
+ "compareActivity:withActivity:usagePriorities:"
+ "completedCount"
+ "completionTime"
+ "csilqCSILQ"
+ "currentPriorities"
+ "d24@0:8q16"
+ "dataWithContentsOfURL:options:error:"
+ "dictionaryWithContentsOfURL:error:"
+ "domain"
+ "failed to persist"
+ "feature:"
+ "fileURL"
+ "flushIfDueAtDate:"
+ "forgetTrackingKeysForActivity:"
+ "getAppUsagePrioritiesWithHandler:"
+ "handleSysdiagnoseStarted"
+ "handleSysdiagnoseStopped"
+ "handleSysdiagnoseTimeoutForCapture:"
+ "initWithDirectory:"
+ "initWithFileURL:"
+ "initWithPriorities:date:"
+ "initWithRecorder:fileURL:"
+ "intensivePriorityForActivity:"
+ "invalid timestamp"
+ "isEqualToDictionary:"
+ "isMediumActivity:"
+ "isMediumActivity:lowercaseName:"
+ "isPersonalizedSchedulingEnabled"
+ "isPostCSPNEnabled"
+ "isStale"
+ "lastFlushDate"
+ "lastPersistDate"
+ "loadIfNeeded"
+ "loadRecordIfNeeded"
+ "loaded"
+ "loggedLoadFailure"
+ "malformed priorities"
+ "mappedBundleIdentifierForLowercaseName:"
+ "mappedBundleIdentifierForTaskName:"
+ "mediumFeatureCodes"
+ "mediumNameSubstrings"
+ "mediumServices"
+ "mediumTaskPrefixes"
+ "nonIntensivePriorityForActivity:"
+ "objCType"
+ "persistAtDate:"
+ "persistRecord:"
+ "persisted state unavailable"
+ "personalizedSchedulingMetrics"
+ "personalizedSchedulingMetrics.plist"
+ "phaseOrAppPriorityForActivity:"
+ "post-CSPN condition enabled"
+ "postCSPNEnabled"
+ "predicted TLC"
+ "prefixToApp"
+ "prefixes"
+ "priorities"
+ "prioritiesForActivities:fromAppPriorities:"
+ "priorityForActivity:"
+ "priorityForActivity:fromAppPriorities:"
+ "priorityForBundleIdentifier:"
+ "propertyListWithData:options:format:error:"
+ "q40@0:8@16@24@32"
+ "receivedDate"
+ "record"
+ "recordEndOfActivity:completed:wasRunning:priority:atDate:"
+ "recordPersonalizedSchedulingMetricsForActivity:completed:wasRunning:"
+ "recorder"
+ "refreshPersonalizedSchedulingGateWithTrialManager:"
+ "refreshWeightsWithTrialManager:"
+ "registerTrackingKey:forActivity:inGroup:"
+ "removeObjectsForKeys:"
+ "runtime"
+ "setCaptureCount:"
+ "setFileURL:"
+ "setLastFlushDate:"
+ "setLastPersistDate:"
+ "setLoaded:"
+ "setLoggedLoadFailure:"
+ "setPersonalizedSchedulingMetrics:"
+ "setPostCSPNEnabled:"
+ "setRecord:"
+ "setRecorder:"
+ "setResourceValue:forKey:error:"
+ "setSpotlightUsesAppPriority:"
+ "setStartedToken:"
+ "setStoppedToken:"
+ "setSysdiagnoseInProgress:"
+ "setTrackingKeysByActivity:"
+ "shouldLowerQoSForPredictedTLC"
+ "snapshot"
+ "spotlightUsesAppPriority"
+ "stale"
+ "startedToken"
+ "stoppedToken"
+ "sysdiagnose"
+ "sysdiagnoseInProgress"
+ "trackingKeysByActivity"
+ "unprotectedTrackerKeyForActivity:inGroup:"
+ "updateAppUsagePriorities:version:timestamp:withHandler:"
+ "updatePersonalizedSchedulingMetricsState"
+ "updatePriorities:version:timestamp:error:"
+ "updateSysdiagnoseInProgress:"
+ "v"
+ "v24@0:8{os_unfair_recursive_lock_s=[2I]}16"
+ "v32@0:8@16B24B28"
+ "v48@0:8@\"NSDictionary\"16Q24@\"NSDate\"32@?<v@?B@\"NSError\">40"
+ "v48@0:8@16B24B28q32@40"
+ "v48@0:8@16Q24@32@?40"
+ "version"
+ "version older than stored"
+ "weightForPriority:"
+ "writeToURL:options:error:"
+ "{os_unfair_recursive_lock_s=\"_os_unfair_recursive_lock_opaque\"[2I]}"
+ "{os_unfair_recursive_lock_s=[2I]}16@0:8"
+ "\xa7"
- "\t"
- "Cleared %lu remembered thermal tasks: %{public}@"
- "Remembering %{public}@ (task ID %lu) for thermal pressure, %lu remembered"
- "Sysdiagnose started, suspending running tasks if any"
- "T{os_unfair_recursive_lock_s={os_unfair_lock_s=I}I},N,V_activityStateLock"
- "T{os_unfair_recursive_lock_s={os_unfair_lock_s=I}I},N,V_applicationLaunchRequestsLock"
- "T{os_unfair_recursive_lock_s={os_unfair_lock_s=I}I},N,V_lock"
- "T{os_unfair_recursive_lock_s={os_unfair_lock_s=I}I},N,V_purgeableSpaceMapLock"
- "_thermalFirstEntryDate"
- "_thermalTaskIDs"
- "battery level"
- "charger disconnected"
- "com.apple.das.qos.batteryLevel"
- "com.apple.das.qos.thermalPressure"
- "didSuspendActivity:forQoSDowngradeWithReasons:"
- "handleSysdiagnoseStartEvent"
- "isPluggedInWithState:"
- "lifetime elapsed"
- "low battery"
- "periodic timer"
- "policy disabled"
- "recent thermal suspension"
- "resetThermalMemoryWithReason:"
- "shouldIgnoreThermalPressure"
- "thermal pressure"
- "thermalMemoryFirstEntryDate"
- "thermalMemoryTaskIDs"
- "v24@0:8{os_unfair_recursive_lock_s={os_unfair_lock_s=I}I}16"
- "v32@?0@\"_DASActivity\"8@\"NSNumber\"16^B24"
- "{os_unfair_recursive_lock_s=\"ourl_lock\"{os_unfair_lock_s=\"_os_unfair_lock_opaque\"I}\"ourl_count\"I}"
- "{os_unfair_recursive_lock_s={os_unfair_lock_s=I}I}16@0:8"
- "\x91"
```
