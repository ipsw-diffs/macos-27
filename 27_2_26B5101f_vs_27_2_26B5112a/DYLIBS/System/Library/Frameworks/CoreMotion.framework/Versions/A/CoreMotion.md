## CoreMotion

> `/System/Library/Frameworks/CoreMotion.framework/Versions/A/CoreMotion`

```diff

-3186.0.21.0.0
-  __TEXT.__text: 0x320d40
-  __TEXT.__objc_methlist: 0x9f94
-  __TEXT.__const: 0xa738
+3186.0.22.0.0
+  __TEXT.__text: 0x3234cc
+  __TEXT.__objc_methlist: 0xa044
+  __TEXT.__const: 0xa908
   __TEXT.__swift5_typeref: 0x257
   __TEXT.__swift5_reflstr: 0x2e
   __TEXT.__swift5_assocty: 0x90
   __TEXT.__constg_swiftt: 0xb8
   __TEXT.__swift5_fieldmd: 0x70
   __TEXT.__swift5_capture: 0x40
-  __TEXT.__oslogstring: 0x242f6
-  __TEXT.__cstring: 0x39804
+  __TEXT.__oslogstring: 0x24548
+  __TEXT.__cstring: 0x39a96
   __TEXT.__swift5_proto: 0x10
   __TEXT.__swift5_types: 0x10
   __TEXT.__swift_as_entry: 0x18
   __TEXT.__swift_as_ret: 0x18
   __TEXT.__swift_as_cont: 0x30
-  __TEXT.__gcc_except_tab: 0xa664
-  __TEXT.__unwind_info: 0xaaf0
+  __TEXT.__gcc_except_tab: 0xa944
+  __TEXT.__unwind_info: 0xaca8
   __TEXT.__eh_frame: 0x150
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1ca8
-  __DATA_CONST.__objc_classlist: 0x6c0
+  __DATA_CONST.__objc_classlist: 0x6c8
   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x42c0
+  __DATA_CONST.__objc_selrefs: 0x42e0
   __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0x5d0
+  __DATA_CONST.__objc_superrefs: 0x5d8
   __DATA_CONST.__objc_arraydata: 0xe0
   __DATA_CONST.__got: 0x688
-  __AUTH_CONST.__const: 0x13ed8
-  __AUTH_CONST.__cfstring: 0xf8e0
-  __AUTH_CONST.__objc_const: 0x15f98
+  __AUTH_CONST.__const: 0x14190
+  __AUTH_CONST.__cfstring: 0xf920
+  __AUTH_CONST.__objc_const: 0x16140
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__objc_floatobj: 0x30
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__auth_got: 0x1268
-  __AUTH.__objc_data: 0x190
+  __AUTH.__objc_data: 0x1e0
   __AUTH.__data: 0x210
-  __DATA.__objc_ivar: 0x1140
-  __DATA.__data: 0xaf0
+  __DATA.__objc_ivar: 0x1150
+  __DATA.__data: 0xb10
   __DATA.__bss: 0x460
-  __DATA.__common: 0xc0
+  __DATA.__common: 0xd0
   __DATA_DIRTY.__objc_ivar: 0x18c
   __DATA_DIRTY.__objc_data: 0x41f0
   __DATA_DIRTY.__data: 0x118

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 10528
+  Functions: 10596
   Symbols:   1595
-  CStrings:  9556
+  CStrings:  9582
 
CStrings:
+ "%{public}s calling setDisplayAngleHandler:%{public}p interval:%{public}f"
+ "-[CMMotionManager setDisplayAngleHandler:interval:]"
+ "22:01:34"
+ "CLHomeHubServiceNotifier"
+ "CLHomeHubServiceNotifier.mm"
+ "CMDisplayAngleService.mm"
+ "DisplayAngle"
+ "Oct  3 2026"
+ "WakeGesture"
+ "[CLHomeHubServiceNotifier] %{public}s : Bump detected, timestamp=%{public}lf, now=%{public}lf"
+ "[CLHomeHubServiceNotifier] %{public}s : angle=%{public}f, isAngleStable=%{public}d, timestamp=%{public}lf, now=%{public}lf"
+ "[CLHomeHubServiceNotifier] Bad report,type,%{public}d,size,%{public}lu"
+ "[CLHomeHubServiceNotifier] Empty payload, returning"
+ "[CLHomeHubServiceNotifier] Event ref invalid"
+ "[CLHomeHubServiceNotifier] Failed to send EnableBumpEvents command"
+ "[CLHomeHubServiceNotifier] Failed to send EnableDisplayAngle command"
+ "angle %f, isStable: %d @ %f"
+ "fHaveActivatedAOP"
+ "fHidDriverInterface"
+ "isAngleStable"
+ "onDisplayAngleChange"
+ "reopenHIDDriverInterface"
+ "updateReportInterval"
+ "virtual void CLHomeHubServiceNotifier::visitBumpEvent(const CMHomeHubReport::BumpEvent &)"
+ "virtual void CLHomeHubServiceNotifier::visitDisplayAngleState(const DisplayAngleState &)"
+ "void CLHomeHubServiceNotifier::onIoHidEvent(IOHIDEventRef)"
+ "void CLHomeHubServiceNotifier::setBumpEventsEnabled(bool)"
+ "void CLHomeHubServiceNotifier::setDisplayAngleEnabled(bool)"
- "23:44:43"
- "Sep 27 2026"
```
