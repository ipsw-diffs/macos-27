## locationd

> `/usr/libexec/locationd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_proto`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 3185.0.6.0.0
-  __TEXT.__text: 0x68800c
+  __TEXT.__text: 0x678e88
   __TEXT.__auth_stubs: 0x38f0
   __TEXT.__objc_stubs: 0x10e00
   __TEXT.__init_offsets: 0x184
   __TEXT.__objc_methlist: 0x12a70
-  __TEXT.__const: 0x17f98
-  __TEXT.__gcc_except_tab: 0x2a958
-  __TEXT.__cstring: 0x7ae16
-  __TEXT.__oslogstring: 0x988d6
+  __TEXT.__const: 0x17fb8
+  __TEXT.__gcc_except_tab: 0x2ab1c
+  __TEXT.__cstring: 0x7af26
+  __TEXT.__oslogstring: 0x98b26
   __TEXT.__objc_methname: 0x1fd8e
   __TEXT.__objc_classname: 0x33f4
   __TEXT.__objc_methtype: 0xf14c

   __TEXT.__swift_as_cont: 0x10
   __TEXT.__swift5_proto: 0x4c
   __TEXT.__swift5_assocty: 0x30
-  __TEXT.__unwind_info: 0x1aba8
-  __TEXT.__eh_frame: 0x620
-  __DATA_CONST.__const: 0x2bfb8
+  __TEXT.__unwind_info: 0x1e260
+  __TEXT.__eh_frame: 0x630
+  __DATA_CONST.__const: 0x2c160
   __DATA_CONST.__cfstring: 0x15d00
   __DATA_CONST.__objc_classlist: 0x8d0
   __DATA_CONST.__objc_catlist: 0x78

   __DATA.__objc_data: 0x5b98
   __DATA.__data: 0x56e8
   __DATA.__common: 0x7d8
-  __DATA.__bss: 0x2c40
+  __DATA.__bss: 0x2c60
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 27076
+  Functions: 26947
   Symbols:   1391
-  CStrings:  24919
+  CStrings:  24939
 
CStrings:
+ "!_guts->valid"
+ "#gfm, onHeartbeat, failure context, dominantOrientation, %{public}d, dominantOrientationExtensionState, %{public}d"
+ "22:39:01"
+ "Aug  8 2026"
+ "Aug  8 2026 22:40:21"
+ "CL: CLMotionLogger::onAngleData"
+ "CL: CLMotionLogger::onHESData"
+ "CLMotionLogger::onAngleData"
+ "CLMotionLogger::onHESData"
+ "Logging accelerometer1 at interval, %f"
+ "Logging gyro1 at interval, %f"
+ "Logging gyro1 temperature at interval, %f"
+ "MotionLoggerAccelerometer1LoggingInterval"
+ "MotionLoggerGyro1LoggingInterval"
+ "MotionLoggerLogAngle"
+ "MotionLoggerLogHES"
+ "Registering for HES notifications"
+ "Registering for angle notifications"
+ "Unregistering for HES notifications"
+ "Unregistering for angle notifications"
+ "deviceState"
+ "void CLMotionLogger::disableRuntimeSwitchableLogging()"
+ "{\"msg%{public}.0s\":\"CLMotionLogger::onAngleData\", \"event\":%{public, location:escape_only}s, \"this\":\"%{public}p\"}"
+ "{\"msg%{public}.0s\":\"CLMotionLogger::onHESData\", \"event\":%{public, location:escape_only}s, \"this\":\"%{public}p\"}"
+ "~DestructionAwareMutex"
- "#gfm, onHeartbeat, failure context, dominantOrientation, %{public}d"
- "04:49:39"
- "Aug 10 2026"
- "Aug 10 2026 04:51:20"
- "kData4"
```
