## CoreMotion

> `/System/Library/Frameworks/CoreMotion.framework/Versions/A/CoreMotion`

```diff

 3185.0.6.0.0
-  __TEXT.__text: 0x31de40
-  __TEXT.__objc_methlist: 0x9b44
-  __TEXT.__const: 0xa330
+  __TEXT.__text: 0x326c3c
+  __TEXT.__objc_methlist: 0x9e54
+  __TEXT.__const: 0xa698
   __TEXT.__swift5_typeref: 0x257
   __TEXT.__swift5_reflstr: 0x2e
   __TEXT.__swift5_assocty: 0x90
   __TEXT.__constg_swiftt: 0xb8
   __TEXT.__swift5_fieldmd: 0x70
   __TEXT.__swift5_capture: 0x40
-  __TEXT.__oslogstring: 0x235cd
-  __TEXT.__cstring: 0x38a98
+  __TEXT.__oslogstring: 0x24186
+  __TEXT.__cstring: 0x3945f
   __TEXT.__swift5_proto: 0x10
   __TEXT.__swift5_types: 0x10
   __TEXT.__swift_as_entry: 0x18
   __TEXT.__swift_as_ret: 0x18
   __TEXT.__swift_as_cont: 0x30
-  __TEXT.__gcc_except_tab: 0x9eb4
-  __TEXT.__unwind_info: 0x9660
+  __TEXT.__gcc_except_tab: 0xa5bc
+  __TEXT.__unwind_info: 0x99a8
   __TEXT.__eh_frame: 0x150
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1c90
-  __DATA_CONST.__objc_classlist: 0x690
+  __DATA_CONST.__const: 0x1ca8
+  __DATA_CONST.__objc_classlist: 0x6b8
   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x4170
+  __DATA_CONST.__objc_selrefs: 0x4248
   __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0x5a8
+  __DATA_CONST.__objc_superrefs: 0x5c8
   __DATA_CONST.__objc_arraydata: 0xe0
-  __DATA_CONST.__got: 0x670
-  __AUTH_CONST.__const: 0x13960
-  __AUTH_CONST.__cfstring: 0xf620
-  __AUTH_CONST.__objc_const: 0x15650
+  __DATA_CONST.__got: 0x680
+  __AUTH_CONST.__const: 0x13e10
+  __AUTH_CONST.__cfstring: 0xf7c0
+  __AUTH_CONST.__objc_const: 0x15d20
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__objc_floatobj: 0x30
   __AUTH_CONST.__objc_arrayobj: 0x30
-  __AUTH_CONST.__auth_got: 0x1240
-  __AUTH.__objc_data: 0x2e40
+  __AUTH_CONST.__auth_got: 0x1270
+  __AUTH.__objc_data: 0x2fd0
   __AUTH.__data: 0x210
-  __DATA.__objc_ivar: 0x10f4
-  __DATA.__data: 0xae0
+  __DATA.__objc_ivar: 0x111c
+  __DATA.__data: 0xaf0
   __DATA.__bss: 0x460
-  __DATA.__common: 0xa0
-  __DATA_DIRTY.__objc_ivar: 0x16c
+  __DATA.__common: 0xc0
+  __DATA_DIRTY.__objc_ivar: 0x18c
   __DATA_DIRTY.__objc_data: 0x1360
   __DATA_DIRTY.__data: 0x118
   __DATA_DIRTY.__common: 0x58

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 10320
-  Symbols:   1579
-  CStrings:  9424
+  Functions: 10479
+  Symbols:   1593
+  CStrings:  9531
 
Symbols:
+ _IOHIDEventCreateHingeAngleEvent
+ _IOHIDEventCreateVendorDefinedEvent
+ _IOHIDEventGetDoubleValue
+ _IOHIDEventGetEvent
+ _IOHIDEventGetPhase
+ _IOHIDEventGetTimeStampOfType
+ _OBJC_CLASS_$_CMAngle
+ _OBJC_CLASS_$_CMAngleManager
+ _OBJC_CLASS_$_CMFactoryAngle
+ _OBJC_CLASS_$_CMFactoryAngleManager
+ _OBJC_METACLASS_$_CMAngle
+ _OBJC_METACLASS_$_CMAngleManager
+ _OBJC_METACLASS_$_CMFactoryAngle
+ _OBJC_METACLASS_$_CMFactoryAngleManager
CStrings:
+ "%{public}s calling setAngleHandler:%{public}p interval:%{public}f"
+ "%{public}s calling setFactoryAngleHandler:%{public}p"
+ "%{signpost.description:begin_time}llu"
+ "%{signpost.description:begin_time}llu %{signpost.description:end_time}llu"
+ "%{signpost.description:end_time}llu"
+ "+[CMFactoryAngleManager isAvailable]"
+ "-[CMAngleManager setAngleHandler:interval:]"
+ "-[CMAngleManagerInternal cancelPendingAngleUpdate]"
+ "-[CMAngleManagerInternal isAngleActive]"
+ "-[CMAngleManagerInternal notifyAngleChange:]"
+ "-[CMAngleManagerInternal onAngleChange:]"
+ "-[CMAngleManagerInternal scheduleAngleUpdate]_block_invoke"
+ "-[CMAngleManagerInternal setAngleUpdateIntervalPrivate:]"
+ "-[CMAngleManagerInternal startAngleUpdatesPrivateToQueue:handler:]"
+ "-[CMAngleManagerInternal stopAngleUpdatesPrivate]"
+ "-[CMFactoryAngleManager setFactoryAngleHandler:]"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Shared/Motion/Notifiers/Angle/CLAngleNotifier.mm"
+ "15:53:32"
+ "A"
+ "Angle"
+ "Angle=%{signpost.description:attribute}f State=%{signpost.description:attribute}s %{signpost.description:begin_time}llu %{signpost.description:end_time}llu"
+ "Aug  8 2026"
+ "Began"
+ "CLAngleNotifier"
+ "CLAngleNotifier.mm"
+ "CLAngleNotifier::isAvailable()"
+ "CLFactoryAngleService.mm"
+ "CLFactoryAngleService::CLFactoryAngleService(std::function<void (const Sample &)> &&)"
+ "CLFactoryAngleService::isAvailable()"
+ "CMAngle.m"
+ "CMAngleAPArrivalToNotified"
+ "CMAngleEventPhaseFromCLMotionTypeAngleEventPhase"
+ "CMAngleGestureBeganToWakeEvent"
+ "CMAngleManager.mm"
+ "CMAngleStateChangeAPArrivalToNotified"
+ "CMAngleStateChangeEventSentToAPArrival"
+ "CMAngleStateChangeEventToEventSent"
+ "CMAngleStateChangeGestureBeganToEvent"
+ "CMAngleStateFromCLMotionTypeAngleState"
+ "CMAngleWakeEventSentToAPArrival"
+ "CMAngleWakeEventToWakeEventSent"
+ "CMFactoryAngleManager.mm"
+ "Canceled pending angle update for %{public}p"
+ "Cancelled"
+ "Changed"
+ "Ended"
+ "Gesture ended for %{public}p with phase %{public}u"
+ "Getting latest AP angle for %{public}p"
+ "IOHIDEventGetType(event) == kIOHIDEventTypeHingeAngle"
+ "Invalid payload size"
+ "Invalid state"
+ "Invalid usage"
+ "Invalid usagePage"
+ "IsSimulator"
+ "IsVirtualDevice"
+ "MayBegin"
+ "OverridesAngleAxisX"
+ "OverridesAngleAxisY"
+ "OverridesAngleAxisZ"
+ "Scheduling angle update for %{public}p to handler %{public}p on queue %{public}p with CMAngle = { %@ }"
+ "Starting angle updates for %p with handler %{public}p, queue %{public}p"
+ "Stopping angle updates for %p with handler %{public}p, queue %{public}p"
+ "Undefined"
+ "Unexpected event type"
+ "[CLAngleNotifier] %{public}s : phase=%{public}s, state=%{public}s, angle=%{public}f, mechanicalAngle=%{public}f, velocity=%{public}f, timestamp=%{public}lf (%{public}llu), continuousTimestamp=%{public}lf (%{public}llu), gestureBeganContinuousTimestamp=%{public}f (%{public}llu), messageSentContinuousTimestamp=%{public}f (%{public}llu), isWakeEvent=%{public}d"
+ "[CLAngleNotifier] Event ref invalid"
+ "[CLAngleNotifier] Skipping open for physical HID device on VM/Simulator"
+ "[CLAngleNotifier] Unrecognized update interval notification %{public}d"
+ "[CLAngleNotifier] copied event is invalid"
+ "[CLAngleNotifier] copyEvent returned invalid event ref"
+ "[CLAngleNotifier] copyEvent: no HID device available"
+ "[CLFactoryAngleService] Overriding axis with x=%f, y=%f, z=%f"
+ "[CLIoHidInterface] setMatchingEventForCopyEvent should be called from motion thread"
+ "[static_cast<id>(info) isKindOfClass:CMAngleManagerInternal.class]"
+ "angle %f, isValid: %d @ %f"
+ "angle: %f, mechanicalAngleDegrees: %f, progress: %f, isAngleValid: %d, velocityDegreesPerSeconds: %f, isVelocityValid: %d, state: %ld, eventPhase: %ld @ absoluteTime: %f, continuousTime: %f"
+ "angleDataFromAngleHIDEvent"
+ "angleEventPhase"
+ "angleState"
+ "deviceState"
+ "onAccelerometer1Change"
+ "onAccelerometerChange"
+ "onAngleChange"
+ "onGyro1Change"
+ "onGyroChange"
+ "onIoHidEvent"
+ "onIoHidEventBounce"
+ "onIoHidEventBounceVirtual"
+ "payload && payloadSize == sizeof(CMAnglePrivateData)"
+ "reConfigure"
+ "report"
+ "setMatchingEventForCopyEvent"
+ "std::optional<AngleData> CLAngleNotifier::copyEvent(CLIoHidInterface::Device::NeedsEventUpdate)"
+ "std::optional<AngleData> CLAngleNotifier::copyEvent(CLIoHidInterface::Device::NeedsEventUpdate)_block_invoke"
+ "target"
+ "toCLMotionType"
+ "toString"
+ "updateAngleDataWithPrivateDataFromAngleHIDEvent"
+ "usage == kHIDUsage_AppleVendorMotion_CranePrivateData"
+ "usagePage == kHIDPage_AppleVendorMotion"
+ "velocityDegreesPerSeconds"
+ "virtual CFTimeInterval CLAngleNotifier::minimumUpdateIntervalChanged(int, const CFTimeInterval &)"
+ "void CLAngleNotifier::onIoHidEvent(IOHIDEventRef, bool)"
+ "void CLAngleNotifier::openHIDDriverInterfaceIfNeeded()"
+ "{\"msg%{public}.0s\":\"Invalid payload size\", \"payloadSize\":%{public}d, \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid state\", \"hidState\":%{public}d, \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid usage\", \"usage\":%{public}d, \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid usagePage\", \"usagePage\":%{public}d, \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Unexpected event type\", \"eventType\":%{public}d, \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"[CLIoHidInterface] setMatchingEventForCopyEvent should be called from motion thread\", \"usagePage\":%{public}d, \"usage\":%{public}d, \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
- "01:00:43"
- "Aug 10 2026"
- "kData4"
```
