## AssistantUAUPlugin

> `/System/Library/CoreServices/UAUPlugins/AssistantUAUPlugin.bundle/Contents/MacOS/AssistantUAUPlugin`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3610.11.2.4.1
-  __TEXT.__text: 0xb94
-  __TEXT.__auth_stubs: 0x130
-  __TEXT.__objc_stubs: 0x260
-  __TEXT.__objc_methlist: 0x1dc
-  __TEXT.__const: 0x28
-  __TEXT.__cstring: 0x1ac
-  __TEXT.__oslogstring: 0x4b9
+3610.19.2.4.1
+  __TEXT.__text: 0x22dc
+  __TEXT.__auth_stubs: 0x210
+  __TEXT.__objc_stubs: 0x4a0
+  __TEXT.__objc_methlist: 0x1fc
+  __TEXT.__const: 0x70
+  __TEXT.__gcc_except_tab: 0x5c
+  __TEXT.__cstring: 0x231
+  __TEXT.__oslogstring: 0xb60
   __TEXT.__ustring: 0x34
   __TEXT.__objc_classname: 0x37
-  __TEXT.__objc_methname: 0x404
-  __TEXT.__objc_methtype: 0x120
-  __TEXT.__unwind_info: 0xb0
-  __DATA_CONST.__const: 0x70
-  __DATA_CONST.__cfstring: 0x1a0
+  __TEXT.__objc_methname: 0x5b7
+  __TEXT.__objc_methtype: 0x123
+  __TEXT.__unwind_info: 0x128
+  __DATA_CONST.__const: 0x190
+  __DATA_CONST.__cfstring: 0x1e0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0xa0
-  __DATA_CONST.__got: 0x30
-  __DATA.__objc_const: 0x288
-  __DATA.__objc_selrefs: 0x168
-  __DATA.__objc_ivar: 0xc
+  __DATA_CONST.__auth_got: 0x118
+  __DATA_CONST.__got: 0x78
+  __DATA.__objc_const: 0x2a8
+  __DATA.__objc_selrefs: 0x1f8
+  __DATA.__objc_ivar: 0x10
   __DATA.__objc_data: 0x50
   __DATA.__data: 0xc0
   __DATA.__bss: 0x10
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
+  - /System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/AssistantServices
   - /System/Library/PrivateFrameworks/UAUPlugin.framework/Versions/A/UAUPlugin
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 18
-  Symbols:   37
-  CStrings:  105
+  Functions: 42
+  Symbols:   62
+  CStrings:  153
 
Symbols:
+ _AFIsAffectedBy2026Incident
+ _AFRunCurrentRunLoopUntilSignaled
+ _AFUpdaterSessionIsOSUpdate
+ _CFAbsoluteTimeGetCurrent
+ _CFRetain
+ _CFRunLoopAddSource
+ _CFRunLoopSourceCreate
+ _CFRunLoopSourceInvalidate
+ _CFRunLoopSourceSignal
+ _CFRunLoopWakeUp
+ _NSDefaultRunLoopMode
+ _OBJC_CLASS_$_AFSiriCapabilitiesServiceClient
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSRunLoop
+ _OBJC_CLASS_$_NSThread
+ __Block_object_assign
+ __Block_object_dispose
+ __Unwind_Resume
+ ___objc_personality_v0
+ _dispatch_async
+ _dispatch_get_global_queue
+ _kCFAllocatorDefault
+ _kCFRunLoopCommonModes
+ _objc_autoreleaseReturnValue
+ _objc_retainBlock
CStrings:
+ "(nil)"
+ "App Access migration: launched siri-app-access-migrator (pid %d)."
+ "Run loop wait: %{public}s after %.3f s and %lu runs, A performed=%{BOOL}d, B performed=%{BOOL}d; sources invalidated"
+ "Run loop wait: run %lu didn't start, the default mode has no sources or timers"
+ "Run loop wait: run %lu, %.3f s left, A performed=%{BOOL}d, B performed=%{BOOL}d"
+ "Run loop wait: signaling source A after %.3f s, from %{public}s"
+ "Run loop wait: signaling source B after %.3f s, from %{public}s"
+ "Run loop wait: source A performed after %.3f s"
+ "Run loop wait: source B performed after %.3f s"
+ "Run loop wait: sources A %p and B %p added to the common modes"
+ "Run loop wait: starting A"
+ "Run loop wait: starting B"
+ "Run loop wait: starting on %{public}s, run loop %p, current mode %{public}@, timeout %.3f s"
+ "Siri AI downgrade without 3.0 data sharing answer: alreadyPerformed=%{BOOL}d affected=%{BOOL}d → %{BOOL}d"
+ "SiriAIDowngradeWithoutDataSharingV3Completed"
+ "_needsSiriAIDowngradeWithoutDataSharingV3"
+ "_waitForMigratorToolExitAndCapabilitiesUpdate:"
+ "a background thread"
+ "currentMode"
+ "currentOSBuild"
+ "currentRunLoop"
+ "date"
+ "dateWithTimeIntervalSinceNow:"
+ "done"
+ "gave up"
+ "getCFRunLoop"
+ "includePluginInUpdateSession: isOSUpdate=%{BOOL}d (previousOSBuild=%{public}@ currentOSBuild=%{public}@), needsLegacyAssistantEnabledRemoval=%{BOOL}d, needsAppAccessMigration=%{BOOL}d, needsSiriAIDataSharingOptOutV2=%{BOOL}d, needsSiriAIDowngradeWithoutDataSharingV3=%{BOOL}d"
+ "isEqualToString:"
+ "isMainThread"
+ "isSiriAIDowngradeWithoutDataSharingV3AlreadyPerformed"
+ "previousOSBuild"
+ "runMode:beforeDate:"
+ "shouldRunSiriAIDowngradeWithoutDataSharingV3"
+ "terminationReason"
+ "terminationStatus"
+ "the main thread"
+ "timeIntervalSinceNow"
+ "updateAccount wait: A: dispatching waitUntilExit for siri-app-access-migrator (pid %d)"
+ "updateAccount wait: A: siri-app-access-migrator (pid %d) exited with status %d, termination reason %ld"
+ "updateAccount wait: A: siri-app-access-migrator wasn't launched, nothing to wait for"
+ "updateAccount wait: A: waitUntilExit started for pid %d"
+ "updateAccount wait: B: asking assistantd for a capabilities update"
+ "updateAccount wait: B: assistantd answered the capabilities update"
+ "updateAccount wait: B: capabilities update failed: %{public}@"
+ "updateAccount wait: starting, timeout %.0f s. A is siri-app-access-migrator exiting (launched=%{BOOL}d, pid %d), B is assistantd answering a capabilities update"
+ "updateAccount wait: waited %.3f s: toolLaunched=%{BOOL}d toolDone=%{BOOL}d capabilitiesUpdateAnswered=%{BOOL}d"
+ "updateCapabilities:"
+ "v16@?0@\"NSError\"8"
+ "v16@?0@?<v@?>8"
+ "v24@0:8@16"
+ "waitUntilExit"
- "App Access migration: launched siri-app-access-migrator (pid %d) fire-and-forget; returning to login."
- "includePluginInUpdateSession: needsLegacyAssistantEnabledRemoval=%{BOOL}d, needsAppAccessMigration=%{BOOL}d, needsSiriAIDataSharingOptOutV2=%{BOOL}d"
- "q16@0:8"
```
