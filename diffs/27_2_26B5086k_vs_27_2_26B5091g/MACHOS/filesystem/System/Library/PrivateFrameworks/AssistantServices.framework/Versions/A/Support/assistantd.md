## assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/Support/assistantd`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_ptr`

```diff

-3605.23.1.4.1
-  __TEXT.__text: 0x537320
-  __TEXT.__auth_stubs: 0x3280
-  __TEXT.__objc_stubs: 0x43400
-  __TEXT.__objc_methlist: 0x22194
-  __TEXT.__cstring: 0x4bf34
-  __TEXT.__const: 0xa2f50
+3605.24.2.0.0
+  __TEXT.__text: 0x538f90
+  __TEXT.__auth_stubs: 0x3290
+  __TEXT.__objc_stubs: 0x43520
+  __TEXT.__objc_methlist: 0x2224c
+  __TEXT.__cstring: 0x4c2eb
+  __TEXT.__const: 0xa2f58
   __TEXT.__dlopen_cstrs: 0x5bb
-  __TEXT.__gcc_except_tab: 0x3248
-  __TEXT.__oslogstring: 0x41c08
-  __TEXT.__objc_classname: 0x4e67
-  __TEXT.__objc_methname: 0x5cfcf
-  __TEXT.__objc_methtype: 0xee7e
+  __TEXT.__gcc_except_tab: 0x32f4
+  __TEXT.__oslogstring: 0x42182
+  __TEXT.__objc_classname: 0x4eb0
+  __TEXT.__objc_methname: 0x5d1bd
+  __TEXT.__objc_methtype: 0xeeb3
   __TEXT.__ustring: 0x98
-  __TEXT.__unwind_info: 0xc1b0
+  __TEXT.__unwind_info: 0xc210
   __TEXT.__eh_frame: 0x140
-  __DATA_CONST.__const: 0x23508
-  __DATA_CONST.__cfstring: 0x11c80
-  __DATA_CONST.__objc_classlist: 0xcd0
+  __DATA_CONST.__const: 0x23630
+  __DATA_CONST.__cfstring: 0x11f20
+  __DATA_CONST.__objc_classlist: 0xce0
   __DATA_CONST.__objc_catlist: 0x630
-  __DATA_CONST.__objc_protolist: 0x6a8
+  __DATA_CONST.__objc_protolist: 0x6b0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0xa8
-  __DATA_CONST.__objc_superrefs: 0xab8
-  __DATA_CONST.__objc_arraydata: 0x420
-  __DATA_CONST.__objc_arrayobj: 0x180
+  __DATA_CONST.__objc_superrefs: 0xac0
+  __DATA_CONST.__objc_arraydata: 0x4d0
+  __DATA_CONST.__objc_arrayobj: 0x1e0
   __DATA_CONST.__objc_intobj: 0x7c8
   __DATA_CONST.__objc_dictobj: 0x2f8
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_floatobj: 0x30
-  __DATA_CONST.__auth_got: 0x1950
-  __DATA_CONST.__got: 0x39d8
+  __DATA_CONST.__auth_got: 0x1958
+  __DATA_CONST.__got: 0x39f0
   __DATA_CONST.__auth_ptr: 0x20
-  __DATA.__objc_const: 0x32b58
-  __DATA.__objc_selrefs: 0x14260
-  __DATA.__objc_ivar: 0x2548
-  __DATA.__objc_data: 0x8020
-  __DATA.__data: 0x5b50
-  __DATA.__bss: 0xa38
+  __DATA.__objc_const: 0x32dd8
+  __DATA.__objc_selrefs: 0x142c8
+  __DATA.__objc_ivar: 0x255c
+  __DATA.__objc_data: 0x80c0
+  __DATA.__data: 0x5bb0
+  __DATA.__bss: 0xa70
   __DATA.__common: 0x1428
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/AVRouting.framework/Versions/A/AVRouting

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 14081
-  Symbols:   2770
-  CStrings:  26212
+  Functions: 14100
+  Symbols:   2772
+  CStrings:  26285
 
Symbols:
+ _OBJC_CLASS_$_SCDADeviceNameInfo
+ _TCCAccessCopyBundleIdentifiersDisabledForService
CStrings:
+ "%s %{public}s activity error: %{public}@"
+ "%s Activity %{public}s completed but another path already owns its transition; not setting done"
+ "%s Activity %{public}s did not accept DEFER during clean exit; it had already left the state we tried to release"
+ "%s Activity %{public}s finished, but the registry slot holds a DIFFERENT run; leaving it for its own owner"
+ "%s Activity %{public}s started while a previous run was still tracked (%{public}s object); the displaced run is unaccounted for"
+ "%s App %@ is excluded from Siri, not speaking announcement on platform: %@"
+ "%s App exclusion check for %@: excluded=%{BOOL}d, denyCount=%lu, expandedCount=%lu"
+ "%s App exclusions disabled by feature flag; treating %@ as not excluded"
+ "%s Clean exit: %lu of %lu in-flight XPC activit(ies) accepted a terminal transition for a pending clean exit"
+ "%s Deferring activity:%{public}s deferred:%{public}s"
+ "%s Failed setting activity state to continue for %{public}s"
+ "%s Failed setting activity state to done for %{public}s"
+ "%s Not deferring %{public}s: another path already owns its transition"
+ "%s Not starting activity %{public}s: the daemon began exiting cleanly. Releasing it."
+ "%s Not starting activity %{public}s: the daemon is exiting cleanly. Releasing it."
+ "%s Pending asset-fetch backstop count is unexpectedly large: %lu (threshold %lu), most recent language '%{public}@'. Either a client is looping on the asset-status XPC, or a tracking entry is being orphaned."
+ "%s Skipping CDM asset-status registration: no language code at registration time."
+ "%s getCompanionInfoFor couldn't find sharedUserId: %@ (primary user is %{private}@)"
+ "-[ADAssetManager _registerCDMStatusTrackerForLanguage:]"
+ "47"
+ "@\"SCDADeviceNameInfo\"24@0:8@\"NSString\"16"
+ "ADAppIsExcludedFromSiri"
+ "ADSCDADeviceNameResolver"
+ "B16@?0@\"NSObject<OS_xpc_object>\"8"
+ "MobileAssistantDaemons-3605.24.2"
+ "SCDADeviceNameResolving"
+ "_ADDeferActivityIfExitingCleanly"
+ "_ADDeferInFlightActivitiesForExit"
+ "_ADFinishInFlightActivity"
+ "_ADHandleActivityState"
+ "_ADReleaseActivityForExit"
+ "_ADRunActivity"
+ "_ADSyncReplyGraphCanary"
+ "_ADTrackInFlightActivity"
+ "_ADUntrackInFlightActivity"
+ "_assetFetchCancelGeneration"
+ "_cancelPendingAssetFetchBackstopsOnQueue"
+ "_existingSharedStore"
+ "_isAppExcludedFromSiri:"
+ "_maxObservedPendingAssetFetchBackstops"
+ "_pendingAssetFetchBackstops"
+ "_registerCDMStatusTrackerForLanguage:"
+ "_syncExitFinishers"
+ "_syncExitLock"
+ "_syncExit_armFinisher:"
+ "_syncExit_drainForReason:"
+ "_syncExit_handleDaemonWillExitCleanly:"
+ "_syncExit_retireFinisher:"
+ "appExcludedFromSiri"
+ "com.apple.Fitness"
+ "com.apple.Health"
+ "com.apple.HeartRate"
+ "com.apple.Mind"
+ "com.apple.NanoHeartRhythm"
+ "com.apple.NanoMedications"
+ "com.apple.NanoMenstrualCycles"
+ "com.apple.NanoOxygenSaturation.watchkitapp"
+ "com.apple.NanoSleep.watchkitapp"
+ "com.apple.NanoStopwatch"
+ "com.apple.NanoWorldClock"
+ "com.apple.Noise"
+ "com.apple.app-clips"
+ "com.apple.findmy"
+ "com.apple.findmy.finddevices"
+ "com.apple.findmy.finditems"
+ "com.apple.findmy.findpeople"
+ "com.apple.findmy.watchapp"
+ "com.apple.mobiletimer"
+ "daemon began exiting cleanly mid-sync"
+ "deviceNameResolver"
+ "different"
+ "initWithRoomName:deviceName:"
+ "isAppExclusionsEnabled"
+ "kTCCServiceSiriAccess"
+ "namesForIdsDeviceUniqueIdentifier:"
+ "removeObjectIdenticalTo:"
+ "same"
+ "setDeviceNameResolver:"
+ "the settings connection was invalidated before the sync finished"
+ "the settings connection went away before the sync finished"
+ "v24@0:8r*16"
+ "v32@?0@\"NSString\"8@16^B24"
- "%s %s activity error: %@"
- "%s Deferring activity:%@ deferred:%@"
- "%s Failed setting activity state to continue"
- "%s Failed setting activity state to done"
- "%s getCompanionInfoFor couldn't find sharedUserId: %@"
- "-[ADAssetManager _registerCDMStatusTracker]"
- "MobileAssistantDaemons-3605.23.1.4.1"
- "_RegisterXPCActivity_block_invoke"
- "_registerCDMStatusTracker"
```
