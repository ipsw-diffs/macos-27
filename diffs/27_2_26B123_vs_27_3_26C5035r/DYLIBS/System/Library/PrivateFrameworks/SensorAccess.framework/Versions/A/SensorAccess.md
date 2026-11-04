## SensorAccess

> `/System/Library/PrivateFrameworks/SensorAccess.framework/Versions/A/SensorAccess`

```diff

-27.0.0.0.0
-  __TEXT.__text: 0x279c
-  __TEXT.__objc_methlist: 0x1b4
-  __TEXT.__const: 0x2f2
-  __TEXT.__constg_swiftt: 0x90
-  __TEXT.__swift5_typeref: 0x68
+29.60.1.0.0
+  __TEXT.__text: 0x3cc0
+  __TEXT.__objc_methlist: 0x234
+  __TEXT.__const: 0x342
+  __TEXT.__cstring: 0x554
+  __TEXT.__constg_swiftt: 0xcc
+  __TEXT.__swift5_typeref: 0x7c
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_reflstr: 0x1b
-  __TEXT.__swift5_fieldmd: 0x2c
+  __TEXT.__swift5_fieldmd: 0x3c
   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_proto: 0x24
-  __TEXT.__swift5_types: 0xc
-  __TEXT.__cstring: 0x444
-  __TEXT.__swift5_capture: 0x50
-  __TEXT.__oslogstring: 0x139
-  __TEXT.__unwind_info: 0x1b8
-  __TEXT.__eh_frame: 0xb8
+  __TEXT.__swift5_types: 0x10
+  __TEXT.__swift5_capture: 0x80
+  __TEXT.__oslogstring: 0x241
+  __TEXT.__unwind_info: 0x248
+  __TEXT.__eh_frame: 0x160
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x40
-  __DATA_CONST.__objc_classlist: 0x28
+  __DATA_CONST.__const: 0x58
+  __DATA_CONST.__objc_classlist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xd8
-  __DATA_CONST.__got: 0x88
-  __AUTH_CONST.__const: 0x98
-  __AUTH_CONST.__objc_const: 0x388
-  __AUTH_CONST.__auth_got: 0x220
-  __AUTH.__objc_data: 0x170
-  __AUTH.__data: 0xe8
-  __DATA.__data: 0xa0
+  __DATA_CONST.__objc_selrefs: 0x130
+  __DATA_CONST.__got: 0xa0
+  __AUTH_CONST.__const: 0xe8
+  __AUTH_CONST.__objc_const: 0x4e0
+  __AUTH_CONST.__auth_got: 0x268
+  __AUTH.__objc_data: 0x1e0
+  __AUTH.__data: 0x1a8
+  __DATA.__data: 0xc0
   __DATA.__bss: 0x480
   __DATA_DIRTY.__objc_data: 0x50
   __DATA_DIRTY.__data: 0x70

   - /usr/lib/swift/libswiftCoreFoundation.dylib
   - /usr/lib/swift/libswiftDispatch.dylib
   - /usr/lib/swift/libswiftIOKit.dylib
+  - /usr/lib/swift/libswiftMetal.dylib
   - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftQuartzCore.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 100
-  Symbols:   138
-  CStrings:  39
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 138
+  Symbols:   172
+  CStrings:  52
 
Symbols:
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_CLASS_$_SensorAccessChillPillState
+ _OBJC_METACLASS_$_SensorAccessChillPillState
+ __DATA_SensorAccessChillPillState
+ __DATA__TtC12SensorAccess22SensorAccessSteadyTime
+ __INSTANCE_METHODS_SensorAccessChillPillState
+ __IVARS_SensorAccessChillPillState
+ __METACLASS_DATA_SensorAccessChillPillState
+ __METACLASS_DATA__TtC12SensorAccess22SensorAccessSteadyTime
+ __PROPERTIES_SensorAccessChillPillState
+ ___swift_destroy_boxed_opaque_existential_0
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftMetal_$_SensorAccess
+ __swift_FORCE_LOAD_$_swiftQuartzCore
+ __swift_FORCE_LOAD_$_swiftQuartzCore_$_SensorAccess
+ __swift_FORCE_LOAD_$_swiftsimd
+ __swift_FORCE_LOAD_$_swiftsimd_$_SensorAccess
+ __swift_stdlib_malloc_size
+ _exclaves_indicator_chillpill_state
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_msgSend$description
+ _objc_msgSend$initWithUnsignedLongLong:
+ _objc_msgSend$initWithUsageMilliseconds:maxMilliseconds:
+ _objc_msgSend$maxMilliseconds
+ _objc_msgSend$remainingTimeAsSteadyForDisplay:
+ _objc_msgSend$remainingTimeToSteadyForDisplay:
+ _objc_msgSend$usageMilliseconds
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_retain_n
+ _symbolic _____ 12SensorAccess0aB10SteadyTimeC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
CStrings:
+ "%{public}s"
+ "Chill pill not in effect"
+ "Chill pill usage %llu ms exceeds budget %llu ms"
+ "Chill pill usage: "
+ "CoreAnimation could not determine the %{public}s deadline"
+ "GetChillPillStateFailed"
+ "GetChillPillStateNotSupported"
+ "GetRemainingSteadyTimeFailed"
+ "GetRemainingSteadyTimeNotSupported"
+ "Remaining %{public}s time %llu ns (curr_time %llu deadline %llu)"
+ "SteadyDeadlineUnknown"
+ "exclaves_indicator_chillpill_state failed with code: %d"
+ "mach_timebase_info failed"
```
