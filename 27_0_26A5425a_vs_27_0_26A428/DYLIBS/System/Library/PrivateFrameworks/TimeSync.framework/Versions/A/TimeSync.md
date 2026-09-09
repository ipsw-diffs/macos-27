## TimeSync

> `/System/Library/PrivateFrameworks/TimeSync.framework/Versions/A/TimeSync`

```diff

 1501.7.0.0.0
-  __TEXT.__text: 0x5cba0
+  __TEXT.__text: 0x5cc14
   __TEXT.__objc_methlist: 0x6e9c
   __TEXT.__const: 0x2a8
   __TEXT.__oslogstring: 0x490e
   __TEXT.__cstring: 0x8645
   __TEXT.__gcc_except_tab: 0xf34
-  __TEXT.__unwind_info: 0x1b28
+  __TEXT.__unwind_info: 0x1b30
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2967
+  Functions: 2968
   Symbols:   5645
   CStrings:  1256
 
Functions:
~ ___45-[TSAudioTimeErrorCorrelatorQuick _makeBlock]_block_invoke : 504 -> 508
~ ___53-[TSAudioTimeErrorCorrelatorPostUpsampler _makeBlock]_block_invoke : 708 -> 712
~ -[TSTimeErrorAnalysis performAnalysisFromStartWindowSize:toEndWindowSize:stepSize:withThreadingOption:] : 896 -> 904
~ -[TSDCTranslationClock initWithClockIdentifier:].cold.1 : 112 -> 116
~ -[TSDCTranslationClock getInitialSyncInfo].cold.1 : 96 -> 84
~ -[TSClockManager init].cold.1 : 104 -> 108
~ -[TSClockManager init].cold.2 : 104 -> 108
~ -[TSClockManager init].cold.3 : 104 -> 108
+ -[TSDCgPTPClock _getInitialSyncInfo].cold.1
```
