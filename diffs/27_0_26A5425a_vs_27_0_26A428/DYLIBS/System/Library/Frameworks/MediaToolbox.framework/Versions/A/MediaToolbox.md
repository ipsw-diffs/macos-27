## MediaToolbox

> `/System/Library/Frameworks/MediaToolbox.framework/Versions/A/MediaToolbox`

```diff

 3350.77.5.6.0
-  __TEXT.__text: 0xa261d0
+  __TEXT.__text: 0xa285b8
   __TEXT.__lazy_helpers: 0x2a0
   __TEXT.__objc_methlist: 0x22cc
-  __TEXT.__cstring: 0x645a4
-  __TEXT.__const: 0x1d740
+  __TEXT.__cstring: 0x64754
+  __TEXT.__const: 0x1d750
   __TEXT.__gcc_except_tab: 0x1428
-  __TEXT.__oslogstring: 0x602ae
+  __TEXT.__oslogstring: 0x60776
   __TEXT.__ustring: 0x24e
   __TEXT.__dlopen_cstrs: 0x21c
   __TEXT.__constg_swiftt: 0x234

   __TEXT.__swift_as_ret: 0x10
   __TEXT.__swift_as_cont: 0x30
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x128d0
+  __TEXT.__unwind_info: 0x12908
   __TEXT.__eh_frame: 0x408
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1ea98
+  __DATA_CONST.__const: 0x1eae8
   __DATA_CONST.__objc_classlist: 0x1e0
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x1a8
   __DATA_CONST.__objc_arraydata: 0x30
-  __DATA_CONST.__got: 0x42a8
-  __AUTH_CONST.__const: 0x3ca30
-  __AUTH_CONST.__cfstring: 0x4dae0
+  __DATA_CONST.__got: 0x42c0
+  __AUTH_CONST.__const: 0x3ca60
+  __AUTH_CONST.__cfstring: 0x4db80
   __AUTH_CONST.__objc_const: 0x47a8
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__lazy_load_got: 0x38
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x48
-  __AUTH_CONST.__auth_got: 0x5550
+  __AUTH_CONST.__auth_got: 0x5590
   __AUTH.__objc_data: 0xd20
   __AUTH.__data: 0x6c0
   __DATA.__objc_ivar: 0x2b4
   __DATA.__data: 0x2858
   __DATA.__common: 0x1890
-  __DATA.__bss: 0x4830
+  __DATA.__bss: 0x4860
   __DATA_DIRTY.__objc_data: 0x5a0
   __DATA_DIRTY.__data: 0x878
   __DATA_DIRTY.__common: 0x5e0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 39683
-  Symbols:   11890
-  CStrings:  18909
+  Functions: 39738
+  Symbols:   11908
+  CStrings:  18932
 
Symbols:
+ _CMClockCreateGenlockClock
+ _CMClockGetPreferredStartTimePattern
+ _CMClockImplementsGetPreferredStartTimePattern
+ _CMGenlockClockFigGetNotifyingObjectForGenlockModeChanged
+ _CMGenlockClockIsLocked
+ _CMGenlockClockValidateSyncSessionUUID
+ _CMIsAnyDisplaySynchronizedToLockedGenlockSignal
+ _FigAudioQueueSetGetPreferredStartTimePatternCallback
+ _SLSDisplayCopyDisplaySyncSessionUUID
+ _kCMGenlockClockNotificationPayload_AnyDisplayIsSynchronizedToGenlock
+ _kCMGenlockClockNotificationPayload_GenlockClockIsLocked
+ _kCMGenlockClockNotification_GenlockModeChanged
+ _kFigPlayerProperty_GenlockDisplayModeActiveOverrideValue
+ _kFigPlayerProperty_OverrideGenlockDisplayModeActive
+ _kFigSampleBufferAudioRendererProperty_GenlockDisplayModeActiveOverrideValue
+ _kFigSampleBufferAudioRendererProperty_OverrideGenlockDisplayModeActive
+ _kFigSampleBufferRenderSynchronizerProperty_GenlockDisplayModeActiveOverrideValue
+ _kFigSampleBufferRenderSynchronizerProperty_OverrideGenlockDisplayModeActive
CStrings:
+ "<<<< Alt >>>> %s: Display sync session UUID %{public}@ is different than the one associated with the genlock clock %{public}@"
+ "<<<< Alt >>>> %s: current host time %1.3f; preferred start host time %1.3f (= now %+1.3f)"
+ "<<<< FAQRP >>>> %s: (%p %{public}s) Will not request preferred start time because hostClockTime %1.3f is specified"
+ "<<<< FAQRP >>>> %s: (%p %{public}s) itemTime %1.3f, currentHostTime %1.3f, first preferred start host time %1.3f (= now %+1.3f), deltaBetweenPreferredStartTimes %1.3f"
+ "<<<< FAQRP >>>> %s: (%p %{public}s) preferred start host time %1.6f (= now %+1.6f), delta %1.6f"
+ "<<<< FigFilePlayer >>>> %s: <%p|%{public}s> beginning synchronization to Genlock clock, so pausing and resuming"
+ "<<<< FigPlayerAudioDevice >>>> %s: CMClockCreateGenlockClock failed unexpectedly, so going to choose the next best clock"
+ "<<<< FigStreamPlayer >>>> %s: [%p|%{public}s] <%p|%{public}s>: Called"
+ "<<<< FigStreamPlayer >>>> %s: [%p|%{public}s] <%p|%{public}s>: beginning synchronization to Genlock clock, so pausing and resuming"
+ "<<<< IQ-cadence >>>> %s: imageTime %1.3f presentationHostTime %1.3f calculatedDurationOnGlass=%1.6f does not match expected %1.6f or %1.6f (genlock_clock_rate=%1.3f Hz, video_frame_rate=%1.3f Hz)"
+ "FPSupport_GetPreferredAnchorTimeForTimebaseAndSource"
+ "FPSupport_ResolveAndCopyTimebaseSourceClock"
+ "FPSupport_ValidateGenlockSyncSessionUUID"
+ "FigImageQueueDisplayCountHistory_ValidateDurationOnGlass"
+ "GenlockClock"
+ "GenlockDisplayModeActiveOverrideValue"
+ "OverrideGenlockDisplayModeActive"
+ "faqrp_getPreferredStartTimePattern"
+ "fpfsi_GenlockModeChanged"
+ "fpfsi_applyGenlockClockChange"
+ "genlock_clock_rate"
+ "itemfig_applyGenlockClockChange"
+ "video_frame_rate"
```
