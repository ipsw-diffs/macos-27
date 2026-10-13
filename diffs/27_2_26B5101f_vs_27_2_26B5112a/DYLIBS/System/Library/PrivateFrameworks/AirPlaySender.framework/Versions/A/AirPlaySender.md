## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/Versions/A/AirPlaySender`

```diff

-1005.12.1.0.0
-  __TEXT.__text: 0x1ce134
+1005.13.1.0.0
+  __TEXT.__text: 0x1ce894
   __TEXT.__objc_methlist: 0x95c
   __TEXT.__const: 0xd530
   __TEXT.__gcc_except_tab: 0x64c
-  __TEXT.__cstring: 0x71b15
+  __TEXT.__cstring: 0x71e2e
   __TEXT.__dlopen_cstrs: 0x164
   __TEXT.__oslogstring: 0xb55
-  __TEXT.__unwind_info: 0x7270
+  __TEXT.__unwind_info: 0x7290
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4358
+  __DATA_CONST.__const: 0x4378
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb40
+  __DATA_CONST.__objc_selrefs: 0xb58
   __DATA_CONST.__objc_superrefs: 0x20
   __DATA_CONST.__objc_arraydata: 0x170
-  __DATA_CONST.__got: 0x1df0
+  __DATA_CONST.__got: 0x1e00
   __AUTH_CONST.__const: 0x72b0
-  __AUTH_CONST.__cfstring: 0x10600
+  __AUTH_CONST.__cfstring: 0x10640
   __AUTH_CONST.__objc_const: 0xc58
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__objc_dictobj: 0x1b8

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 9102
-  Symbols:   8844
-  CStrings:  9247
+  Functions: 9110
+  Symbols:   8859
+  CStrings:  9268
 
Symbols:
+ GCC_except_table130
+ _APSIsHomeAccessory
+ _MGGetBoolAnswer
+ _OBJC_CLASS_$_CUSystemMonitor
+ ___copy_helper_block_8_32b40r48r56r
+ ___destroy_helper_block_8_32b40r48r56r
+ ___endpoint_startPowerSourceMonitorIfNeeded_block_invoke
+ ___endpoint_startPowerSourceMonitorIfNeeded_block_invoke_2
+ ___endpoint_startPowerSourceMonitorIfNeeded_block_invoke_3
+ _airPlayDescription_isAppleHomeAccessory
+ _endpoint_startPowerSourceMonitorIfNeeded
+ _endpoint_stopPowerSourceMonitor
+ _endpoint_updateInactivityTimer
+ _kAPSDynamicLatencyManagerVariantIdentifier_B525
+ _kFigEndpointSubType_HomeAccessory
+ _objc_msgSend$powerUnlimited
+ _objc_msgSend$setInvalidationHandler:
+ _objc_msgSend$setPowerUnlimitedChangedHandler:
+ endpoint_shouldUseInactivityTimer
- _GestaltGetBoolean
- ___copy_helper_block_8_32b40r48r
- ___destroy_helper_block_8_32b40r48r
- _endpoint_startInactivityTimer
CStrings:
+ "1005.13.1"
+ "APEndpointInactivityTimeoutType endpoint_determineInactivityTimeoutBehavior(FigEndpointRef, FigEndpointFeatures, CFDictionaryRef)"
+ "AudioAccessory11"
+ "HomeAccessory"
+ "Never"
+ "NoIdleTimeout activation option"
+ "P2POnly"
+ "P2POnlyOnBattery"
+ "[%{ptr}] Inactivity timeout type: %s%?{end} (%s)\n"
+ "[%{ptr}] Monitoring power source for inactivity timer\n"
+ "[%{ptr}] Power source changed: now on %s power\n"
+ "[%{ptr}] Power source monitor creation fail"
+ "[%{ptr}] Stopped monitoring power source\n"
+ "[%{ptr}] Using inactivity timeout? %s%?{end} (type: %s)\n"
+ "battery"
+ "endpoint_shouldUseInactivityTimer"
+ "not responsive audio"
+ "responsive audio, portable Mac"
+ "responsive audio, stationary Mac"
+ "void endpoint_handlePowerSourceChanged(FigEndpointRef)"
+ "void endpoint_startPowerSourceMonitorIfNeeded(FigEndpointRef)"
+ "void endpoint_stopPowerSourceMonitor(FigEndpointRef)"
+ "void endpoint_updateInactivityTimer(FigEndpointRef, Boolean)"
+ "wall"
- "1005.12.1"
- "[%{ptr}] Using inactivity timeout? %d\n"
- "void endpoint_startInactivityTimer(FigEndpointRef)"
```
