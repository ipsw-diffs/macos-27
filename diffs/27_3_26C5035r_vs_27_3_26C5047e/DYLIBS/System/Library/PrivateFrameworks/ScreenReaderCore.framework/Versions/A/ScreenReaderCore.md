## ScreenReaderCore

> `/System/Library/PrivateFrameworks/ScreenReaderCore.framework/Versions/A/ScreenReaderCore`

```diff

-1050.3.12.0.0
-  __TEXT.__text: 0x3ecbc
+1050.3.22.0.0
+  __TEXT.__text: 0x3f3bc
   __TEXT.__objc_methlist: 0x39b4
-  __TEXT.__cstring: 0x83e4
-  __TEXT.__const: 0x798
+  __TEXT.__cstring: 0x84e8
+  __TEXT.__const: 0x7a8
   __TEXT.__gcc_except_tab: 0x4c0
   __TEXT.__dlopen_cstrs: 0x101
   __TEXT.__ustring: 0x2a
-  __TEXT.__oslogstring: 0x136
-  __TEXT.__unwind_info: 0x1260
+  __TEXT.__oslogstring: 0x1aa
+  __TEXT.__unwind_info: 0x1268
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_superrefs: 0x170
   __DATA_CONST.__objc_arraydata: 0x238
   __DATA_CONST.__got: 0x360
-  __AUTH_CONST.__const: 0x4a0
-  __AUTH_CONST.__cfstring: 0x8d20
+  __AUTH_CONST.__const: 0x4c0
+  __AUTH_CONST.__cfstring: 0x8e80
   __AUTH_CONST.__objc_const: 0x5180
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x50

   __DATA.__objc_ivar: 0x3b4
   __DATA.__data: 0xc30
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x400
+  __DATA.__bss: 0x410
   __DATA.__common: 0x40
   __DATA_DIRTY.__objc_data: 0x1130
   __DATA_DIRTY.__data: 0x2f0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1329
-  Symbols:   3792
-  CStrings:  1248
+  Functions: 1332
+  Symbols:   3796
+  CStrings:  1262
 
Symbols:
+ _SCRCGestureLog
+ _SCRCGestureLog.Log
+ _SCRCGestureLog.onceToken
+ ___SCRCGestureLog_block_invoke
Functions:
~ -[SCRCGestureFactory _updateTapState] : 380 -> 512
+ _SCRCGestureLog
~ -[SCRCGestureFactory _enterTrackingMode:] : 148 -> 292
~ -[SCRCGestureFactory _handleSplitEvent:] : 1452 -> 1724
~ -[SCRCGestureFactory handleGestureEvent:] : 832 -> 1104
~ -[SCRCGestureFactory _down:] : 1396 -> 1672
~ -[SCRCGestureFactory _drag:] : 3016 -> 3280
~ -[SCRCGestureFactory _up] : 376 -> 672
+ ___SCRCGestureLog_block_invoke
+ _SCRCDebugPrint.cold.1
CStrings:
+ "Cancel Event"
+ "Ignoring cancel after lift, tap count: %lu, factory: %p"
+ "SCRCGesture"
+ "Tap canceled: %@, tap count: %lu, fingers: %lu, factory: %p"
+ "_enterTrackingMode"
+ "fingers not related"
+ "horizontal flick"
+ "split fast track"
+ "split tap done"
+ "starting a split tap session"
+ "stolen by another gesture"
+ "unable to get finger information"
+ "vertical flick"
+ "wandered off pad and could not come back on"
```
