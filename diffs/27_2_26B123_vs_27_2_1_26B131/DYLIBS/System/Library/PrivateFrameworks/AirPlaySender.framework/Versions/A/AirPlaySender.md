## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/Versions/A/AirPlaySender`

```diff

-1005.13.1.0.0
-  __TEXT.__text: 0x1cec88
+1005.13.5.1.0
+  __TEXT.__text: 0x1ceca0
   __TEXT.__objc_methlist: 0x95c
   __TEXT.__const: 0xd530
   __TEXT.__gcc_except_tab: 0x64c
-  __TEXT.__cstring: 0x71e4c
+  __TEXT.__cstring: 0x71e60
   __TEXT.__dlopen_cstrs: 0x164
   __TEXT.__oslogstring: 0xb55
   __TEXT.__unwind_info: 0x7290
Functions:
~ _coreUtilsPairing_createAirPlayPairingSession : 732 -> 748
~ _coreUtilsPairing_IsPeerKnown : 236 -> 240
~ _coreUtilsPairing_PerformVerification : 3040 -> 3044
CStrings:
+ "1005.13.5.1"
+ "OSStatus coreUtilsPairing_createAirPlayPairingSession(APPairingClientRef, PairingSessionType, Boolean, Boolean, Boolean, PairingSessionRef *)"
+ "OSStatus coreUtilsPairing_performSetupInternal(APPairingClientRef, const CFStringRef, APPairingType, Boolean, Boolean, Boolean, CFStringRef, CFStringRef *, CFDataRef *, CFDataRef *, CFTypeRef *, CFDictionaryRef *)"
- "1005.13.1"
- "OSStatus coreUtilsPairing_createAirPlayPairingSession(APPairingClientRef, PairingSessionType, Boolean, Boolean, PairingSessionRef *)"
- "OSStatus coreUtilsPairing_performSetupInternal(APPairingClientRef, const CFStringRef, APPairingType, Boolean, Boolean, CFStringRef, CFStringRef *, CFDataRef *, CFDataRef *, CFTypeRef *, CFDictionaryRef *)"
```
