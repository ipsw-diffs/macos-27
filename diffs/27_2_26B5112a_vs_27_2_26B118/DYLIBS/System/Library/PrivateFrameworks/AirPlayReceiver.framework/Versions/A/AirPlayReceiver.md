## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/Versions/A/AirPlayReceiver`

```diff

 1005.13.1.0.0
-  __TEXT.__text: 0xf6540
+  __TEXT.__text: 0xf66d8
   __TEXT.__objc_methlist: 0xca4
   __TEXT.__const: 0xd543
   __TEXT.__dlopen_cstrs: 0x103
   __TEXT.__gcc_except_tab: 0x8ac
-  __TEXT.__cstring: 0x2f05b
+  __TEXT.__cstring: 0x2f05f
   __TEXT.__oslogstring: 0x2eb
   __TEXT.__unwind_info: 0x1920
   __TEXT.__objc_stubs: 0x0

   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__got: 0x888
   __AUTH_CONST.__const: 0x3d80
-  __AUTH_CONST.__cfstring: 0xb220
+  __AUTH_CONST.__cfstring: 0xb240
   __AUTH_CONST.__objc_const: 0x18f8
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_intobj: 0x18

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 1483
-  Symbols:   3792
-  CStrings:  4802
+  Symbols:   3796
+  CStrings:  4803
 
Symbols:
+ _APSGetClusterMemberIDForSurroundRole
+ _APSGetSurroundRoleFromClusterSummary
+ _APSIsHomeTheaterSurroundEnabled
+ _APSSurroundToOdeonFallbackEnabled
Functions:
~ ____IsWiFiDECaptureAllowed_block_invoke : 36 -> 40
~ _sysInfo_updatePrefs : 4132 -> 4184
~ _sysInfo_updateAdvertiserInfo : 3384 -> 3452
~ __APAdvertiserInfoAddAirPlayData : 3724 -> 3812
~ _APAdvertiserInfoCopyAirPlayDataWithNANServiceType : 3704 -> 3804
~ _APAdvertiserInfoCopyClusterCompatibleAirPlayData : 2640 -> 2736
CStrings:
+ "pgs"
```
