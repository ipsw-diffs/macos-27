## CoreRepairCore

> `/System/Library/PrivateFrameworks/CoreRepairCore.framework/Versions/A/CoreRepairCore`

```diff

 1307.1.2.0.0
-  __TEXT.__text: 0x78544
-  __TEXT.__objc_methlist: 0x406c
+  __TEXT.__text: 0x7ec48
+  __TEXT.__objc_methlist: 0x440c
   __TEXT.__const: 0x866
-  __TEXT.__cstring: 0x5c23
-  __TEXT.__oslogstring: 0x90e2
-  __TEXT.__gcc_except_tab: 0x1398
-  __TEXT.__unwind_info: 0x11b8
+  __TEXT.__cstring: 0x6152
+  __TEXT.__oslogstring: 0x9495
+  __TEXT.__gcc_except_tab: 0x15e0
+  __TEXT.__unwind_info: 0x1330
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1e0
-  __DATA_CONST.__objc_classlist: 0x288
+  __DATA_CONST.__const: 0x268
+  __DATA_CONST.__objc_classlist: 0x2c0
   __DATA_CONST.__objc_catlist: 0x28
-  __DATA_CONST.__objc_protolist: 0x68
+  __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2688
-  __DATA_CONST.__objc_protorefs: 0x28
-  __DATA_CONST.__objc_superrefs: 0x188
-  __DATA_CONST.__objc_arraydata: 0x588
-  __DATA_CONST.__got: 0x510
-  __AUTH_CONST.__const: 0xe20
-  __AUTH_CONST.__cfstring: 0x6c60
-  __AUTH_CONST.__objc_const: 0x5e18
-  __AUTH_CONST.__objc_intobj: 0x270
+  __DATA_CONST.__objc_selrefs: 0x2848
+  __DATA_CONST.__objc_protorefs: 0x30
+  __DATA_CONST.__objc_superrefs: 0x1b0
+  __DATA_CONST.__objc_arraydata: 0x630
+  __DATA_CONST.__got: 0x518
+  __AUTH_CONST.__const: 0x11a0
+  __AUTH_CONST.__cfstring: 0x7300
+  __AUTH_CONST.__objc_const: 0x6428
+  __AUTH_CONST.__objc_intobj: 0x378
   __AUTH_CONST.__objc_dictobj: 0x190
-  __AUTH_CONST.__objc_arrayobj: 0x438
-  __AUTH_CONST.__auth_got: 0xa40
-  __AUTH.__objc_data: 0x1090
-  __DATA.__objc_ivar: 0x390
-  __DATA.__data: 0x5f8
-  __DATA.__bss: 0x100
+  __AUTH_CONST.__objc_arrayobj: 0x450
+  __AUTH_CONST.__auth_got: 0xa60
+  __AUTH.__objc_data: 0x12c0
+  __DATA.__objc_ivar: 0x3ac
+  __DATA.__data: 0x658
+  __DATA.__bss: 0x160
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x8c0
   __DATA_DIRTY.__bss: 0x180

   - /usr/lib/libauthinstall.dylib
   - /usr/lib/libimage4.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2326
-  Symbols:   577
-  CStrings:  2126
+  Functions: 2463
+  Symbols:   587
+  CStrings:  2207
 
Symbols:
+ _CFStringCompare
+ _OBJC_CLASS_$_CRShipModeBatteryClient
+ _OBJC_CLASS_$_CRShipModeServerNotifier
+ _OBJC_CLASS_$_CRShipModeServerResponse
+ _OBJC_METACLASS_$_CRShipModeBatteryClient
+ _OBJC_METACLASS_$_CRShipModeServerNotifier
+ _OBJC_METACLASS_$_CRShipModeServerResponse
+ _dispatch_after
+ _dispatch_block_cancel
+ _dispatch_block_create
CStrings:
+ "(nil)"
+ "(none)"
+ "/usr/standalone/update/Furei/"
+ "/usr/standalone/update/Glenbrook/"
+ "/usr/standalone/update/Hamal/"
+ "/usr/standalone/update/Lakeville/"
+ "4080"
+ "4081"
+ "B16@?0@\"NSError\"8"
+ "B8@?0"
+ "BatteryAux"
+ "CRShipModeBatteryClient: cancel plumbing failure: %s"
+ "CRShipModeBatteryClient: clear followups plumbing failure: %s"
+ "CRShipModeBatteryClient: device-error report plumbing failure: %s"
+ "CRShipModeBatteryClient: discharge status plumbing failure: %s"
+ "CRShipModeBatteryClient: discharge submit plumbing failure: %s"
+ "CRShipModeBatteryClient: disengage plumbing failure: %s"
+ "CRShipModeBatteryClient: fetch ship-mode resume state plumbing failure: %s"
+ "CRShipModeBatteryClient: notify status plumbing failure: %s"
+ "CRShipModeBatteryClient: operation status plumbing failure: %s"
+ "CRShipModeServerNotifier: XPC connection error: %s"
+ "CRShipModeServerNotifier: daemon reported failure: %s (domain=%s code=%ld)"
+ "CRShipModeServerNotifier: synchronous proxy returned without reply or error"
+ "CascadedInfo"
+ "CpCt"
+ "DisplayMain"
+ "DisplayMainTCON"
+ "Error occurred in one or more battery components"
+ "Failed to confirm key availability for front battery: %@"
+ "Failed to get version info for secondary battery"
+ "FrontCamera"
+ "FrontCameraMain"
+ "IOBoard"
+ "IPHONE AUX BATTERY"
+ "Pack[%u]: %ld, %@"
+ "Per-pack battery info:"
+ "RCAM"
+ "Unable to read Battery identifier:%@"
+ "XPC connection error"
+ "XPC connection interrupted before reply"
+ "XPC connection invalidated before reply"
+ "XPC proxy error"
+ "XPC reply timed out"
+ "bml1"
+ "com.apple.mobilerepair.shipmode"
+ "com.apple.mobilerepair.shipmode.batteryclient"
+ "com.apple.mobilerepair.shipmode.client"
+ "deviceError"
+ "enabled"
+ "frnt"
+ "innf"
+ "innr"
+ "mobilerepaird proxy does not conform to CRRepairShipModeProtocol"
+ "mobilerepaird returned without reply"
+ "multiComponentErrors"
+ "outf"
+ "outr"
+ "partnerID"
+ "partnerName"
+ "prpc-frnt"
+ "prpc-innf"
+ "prpc-outf"
+ "prpc-rcam"
+ "prpc-rear"
+ "rcam"
+ "rear"
+ "shipModeTimerDuration"
+ "shipModeTimerUnit"
+ "tcrt-innr"
+ "tcrt-outr"
+ "v24@?0@\"<CRRepairShipModeProtocol>\"8@?<B@?>16"
+ "v24@?0@\"<CRRepairShipModeProtocol>\"8@?<v@?BB@\"NSString\"@\"NSString\"@\"NSError\">16"
+ "v24@?0@\"CRShipModeServerResponse\"8@\"NSError\"16"
+ "v24@?0@\"NSUUID\"8@\"NSError\"16"
+ "v32@?0@\"NSNumber\"8@\"NSError\"16^B24"
+ "v36@?0q8B16@\"NSUUID\"20@\"NSError\"28"
+ "v40@?0B8B12@\"NSString\"16@\"NSString\"24@\"NSError\"32"
+ "v40@?0q8@\"NSUUID\"16B24B28@\"NSError\"32"
+ "vcrt-4080"
+ "vcrt-4081"
+ "ycrt-rcam"
```
