## CardioHealth

> `/System/Library/PrivateFrameworks/CardioHealth.framework/Versions/A/CardioHealth`

```diff

-3188.0.7.0.0
-  __TEXT.__text: 0xcf50
-  __TEXT.__const: 0x564
-  __TEXT.__gcc_except_tab: 0x3a4
+3188.0.11.0.0
+  __TEXT.__text: 0xd2cc
+  __TEXT.__const: 0x584
+  __TEXT.__gcc_except_tab: 0x3ac
   __TEXT.__cstring: 0xed
-  __TEXT.__oslogstring: 0x26ef
+  __TEXT.__oslogstring: 0x2783
   __TEXT.__unwind_info: 0x2c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/libz.1.dylib
   Functions: 103
   Symbols:   88
-  CStrings:  97
+  CStrings:  98
 
Functions:
~ sub_262736d08 -> sub_263716d08 : 5992 -> 6308
~ __ZN17CHVO2MaxEstimator16feedWorkoutEventERKN12CardioHealth12WorkoutEventE : 6256 -> 6308
~ __ZN17CHVO2MaxEstimator18retrocomputeVO2MaxEdRKNSt3__16vectorI11VO2MaxInputNS0_9allocatorIS2_EEEERKNS1_I13VO2MaxSummaryNS3_IS8_EEEERKN12CardioHealth13CHBodyMetricsEddNSD_13CHWorkoutTypeENSD_23CHWorkoutSessionDetails4TypeER31VO2MaxRetrocomputeSessionResult : 1320 -> 1376
~ sub_26273cb2c -> sub_26371ccd4 : 8660 -> 8976
~ sub_26273ed00 -> sub_26371efe4 : 1868 -> 2020
CStrings:
+ "VO2Max Step Test confident HR at or below resting: droppedPairs=%{public}d, confidentPairs=%{public}d, restingHR=%{private}.0f, hrMax=%{private}.0f"
```
