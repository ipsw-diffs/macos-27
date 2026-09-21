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
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`

```diff

-2467.40.37.0.0
-  __TEXT.__text: 0x133bc4
-  __TEXT.__auth_stubs: 0x1e40
-  __TEXT.__objc_stubs: 0x15480
-  __TEXT.__objc_methlist: 0xf84c
+2467.40.41.0.0
+  __TEXT.__text: 0x135238
+  __TEXT.__auth_stubs: 0x1e50
+  __TEXT.__objc_stubs: 0x15680
+  __TEXT.__objc_methlist: 0xf904
   __TEXT.__const: 0x1268
-  __TEXT.__objc_methname: 0x24b0b
-  __TEXT.__cstring: 0xc566
-  __TEXT.__oslogstring: 0x10209
-  __TEXT.__objc_classname: 0x1808
-  __TEXT.__objc_methtype: 0x3121
-  __TEXT.__gcc_except_tab: 0x3ad8
+  __TEXT.__objc_methname: 0x24d2b
+  __TEXT.__cstring: 0xc6c6
+  __TEXT.__oslogstring: 0x10429
+  __TEXT.__objc_classname: 0x1828
+  __TEXT.__objc_methtype: 0x3161
+  __TEXT.__gcc_except_tab: 0x3b10
   __TEXT.__dlopen_cstrs: 0x268
   __TEXT.__swift5_typeref: 0x8f8
   __TEXT.__swift5_capture: 0x1e4

   __TEXT.__swift_as_cont: 0x78
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x50d0
+  __TEXT.__unwind_info: 0x5160
   __TEXT.__eh_frame: 0xbb0
-  __DATA_CONST.__const: 0x4170
-  __DATA_CONST.__cfstring: 0xdb60
-  __DATA_CONST.__objc_classlist: 0x620
+  __DATA_CONST.__const: 0x4238
+  __DATA_CONST.__cfstring: 0xdd20
+  __DATA_CONST.__objc_classlist: 0x628
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x1a0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x60
-  __DATA_CONST.__objc_superrefs: 0x518
+  __DATA_CONST.__objc_superrefs: 0x520
   __DATA_CONST.__objc_intobj: 0x1368
-  __DATA_CONST.__objc_arraydata: 0x1e0
-  __DATA_CONST.__objc_arrayobj: 0xd8
+  __DATA_CONST.__objc_arraydata: 0x238
+  __DATA_CONST.__objc_arrayobj: 0xf0
   __DATA_CONST.__objc_doubleobj: 0x30
   __DATA_CONST.__objc_dictobj: 0x168
-  __DATA_CONST.__auth_got: 0xf30
-  __DATA_CONST.__got: 0xaf0
+  __DATA_CONST.__auth_got: 0xf38
+  __DATA_CONST.__got: 0xb08
   __DATA_CONST.__auth_ptr: 0x190
-  __DATA.__objc_const: 0x2b300
-  __DATA.__objc_selrefs: 0x7d30
-  __DATA.__objc_ivar: 0x119c
-  __DATA.__objc_data: 0x3ff8
+  __DATA.__objc_const: 0x2b418
+  __DATA.__objc_selrefs: 0x7da8
+  __DATA.__objc_ivar: 0x11ac
+  __DATA.__objc_data: 0x4048
   __DATA.__data: 0x1b18
-  __DATA.__bss: 0x11b0
+  __DATA.__bss: 0x11e0
   __DATA.__common: 0x18
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices
   - /System/Library/Frameworks/CoreData.framework/Versions/A/CoreData

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6829
-  Symbols:   858
-  CStrings:  9685
+  Functions: 6862
+  Symbols:   862
+  CStrings:  9732
 
Symbols:
+ _OBJC_CLASS_$__CDContextValue
+ _SCDynamicStoreSetDispatchQueue
+ __CDInformativeContextualChangeNewValueKey
+ __CDInformativeContextualChangeOldValueKey
CStrings:
+ "%@.%@"
+ "@\"_CDContextualChangeRegistration\""
+ "AppLifecycleConsoleUserMonitor"
+ "AppLifecycleRecorder"
+ "B36@0:8@16B24@28"
+ "B48@0:8Q16@24@32^@40"
+ "Backfilled %lu app lifecycle checkpoints"
+ "Backfilling app lifecycle checkpoints for %{public}@ - %{public}@"
+ "Donated checkpoint %lu for %{public}@ at %{public}@"
+ "Failed to create SCDynamicStore; macOS donations will be limited to startup"
+ "Failed to read App.InFocus: %{public}@"
+ "Failed to record checkpoint %lu for %{public}@: %{public}@"
+ "Failed to set console user notification keys"
+ "No console user; deferring backfill until login"
+ "Nothing to backfill; resume point is not before the window end"
+ "Registered for ContextStore foreground app changes"
+ "_DASAppLifecycleRecorder"
+ "_foregroundAppRegistration"
+ "_liveDonationStartDate"
+ "absoluteTimestamp"
+ "appLifecycle"
+ "backfillCheckpointsUpToDate:"
+ "backfillHistoryPrecedingLiveWindow"
+ "com.apple.DocumentsApp"
+ "com.apple.MobileSMS"
+ "com.apple.Notes"
+ "com.apple.dasd.appLifecycle.foregroundApp"
+ "com.apple.dasd.appLifecycleBackfill"
+ "com.apple.dasd.appLifecycleRecorder"
+ "com.apple.iCal"
+ "com.apple.mail"
+ "com.apple.mobilecal"
+ "com.apple.mobilenotes"
+ "com.apple.mobileslideshow"
+ "com.apple.reminders"
+ "donateTransitionForApp:foregrounded:atDate:"
+ "handleForegroundAppChange:"
+ "inLongInactivityWindow"
+ "initInternal"
+ "installConsoleUserObserver"
+ "installForegroundAppObserver"
+ "isThermallyConstrainedHardware"
+ "localNonWakingRegistrationWithIdentifier:contextualPredicate:clientIdentifier:callback:"
+ "reportCustomCheckpoint:forTask:atDate:error:"
+ "resumeDateBefore:"
+ "sharedRecorder"
+ "startDonating"
```
