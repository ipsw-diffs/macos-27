## Sentry

> `/System/Library/PrivateFrameworks/Sentry.framework/Versions/A/Sentry`

```diff

 11.0.0.0.0
-  __TEXT.__text: 0x1b71c
+  __TEXT.__text: 0x1b828
   __TEXT.__objc_methlist: 0x1778
   __TEXT.__const: 0x174
-  __TEXT.__cstring: 0x1ea8
-  __TEXT.__oslogstring: 0x3043
-  __TEXT.__gcc_except_tab: 0x3f4
+  __TEXT.__cstring: 0x1eca
+  __TEXT.__oslogstring: 0x3061
+  __TEXT.__gcc_except_tab: 0x408
   __TEXT.__unwind_info: 0x710
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_arraydata: 0xa8
   __DATA_CONST.__got: 0x3b0
   __AUTH_CONST.__const: 0xb60
-  __AUTH_CONST.__cfstring: 0x1e80
+  __AUTH_CONST.__cfstring: 0x1ea0
   __AUTH_CONST.__objc_const: 0x31f0
   __AUTH_CONST.__objc_intobj: 0xc0
   __AUTH_CONST.__objc_arrayobj: 0x18

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libspindump.dylib
   - /usr/lib/libtailspin.dylib
-  Functions: 765
+  Functions: 766
   Symbols:   1808
-  CStrings:  516
+  CStrings:  518
 
Functions:
~ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:] : 2144 -> 2360
~ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:].cold.3 : 96 -> 52
~ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:].cold.4 : 52 -> 96
~ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:].cold.8 : 108 -> 52
+ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:].cold.9
CStrings:
+ "App launch threshold enforced"
+ "ApplicationFirstFramePresentation"
```
