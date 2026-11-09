## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/Versions/A/AirPlayReceiver`

```diff

-1005.13.1.0.0
-  __TEXT.__text: 0xf66d8
+1005.13.5.1.0
+  __TEXT.__text: 0xf6880
   __TEXT.__objc_methlist: 0xca4
   __TEXT.__const: 0xd543
   __TEXT.__dlopen_cstrs: 0x103
   __TEXT.__gcc_except_tab: 0x8ac
-  __TEXT.__cstring: 0x2f05f
+  __TEXT.__cstring: 0x2f0a2
   __TEXT.__oslogstring: 0x2eb
-  __TEXT.__unwind_info: 0x1920
+  __TEXT.__unwind_info: 0x1928
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__got: 0x888
   __AUTH_CONST.__const: 0x3d80
-  __AUTH_CONST.__cfstring: 0xb240
+  __AUTH_CONST.__cfstring: 0xb260
   __AUTH_CONST.__objc_const: 0x18f8
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_intobj: 0x18

   - /System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/Versions/A/WiFiPeerToPeer
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1483
-  Symbols:   3759
-  CStrings:  4803
+  Functions: 1484
+  Symbols:   3760
+  CStrings:  4805
 
Symbols:
+ GCC_except_table1054
+ GCC_except_table1073
+ GCC_except_table1124
+ GCC_except_table1128
+ GCC_except_table1180
+ GCC_except_table1188
+ GCC_except_table1190
+ GCC_except_table1233
+ GCC_except_table1295
+ GCC_except_table945
+ _airplayReqProcessor_ensurePairingServices
- GCC_except_table1053
- GCC_except_table1072
- GCC_except_table1123
- GCC_except_table1127
- GCC_except_table1179
- GCC_except_table1187
- GCC_except_table1189
- GCC_except_table1232
- GCC_except_table1294
- GCC_except_table944
Functions:
~ _AirPlayReceiverServerControl : 1852 -> 1876
~ __StartOrStopServersIfNeeded : 1980 -> 2048
~ _airplayReqProcessor_requestProcessPairSetupPINStart : 684 -> 744
~ _airplayReqProcessor_requestProcessPairSetupUnauthenticatedLegacy : 848 -> 852
~ _airplayReqProcessor_requestProcessPairSetupPINLegacy : 872 -> 984
~ _airplayReqProcessor_requestProcessPairSetup : 1948 -> 2004
~ _airplayReqProcessor_requestProcessPairVerify : 2432 -> 2136
~ _airplayReqProcessor_copyPasscodeForPairingType : 212 -> 240
+ _airplayReqProcessor_ensurePairingServices
~ _airplayReqProcessor_createPairingParamsDict : 352 -> 380
~ _APPairingServicesCoreUtilsCreate : 348 -> 288
~ _coreUtilsPairing_SetProperty : 456 -> 500
CStrings:
+ "1005.13.5.1"
+ "CoreUtils"
+ "OSStatus APPairingServicesCoreUtilsCreate(CFAllocatorRef, APPairingServicesRef *)"
+ "OSStatus _StartServers(AirPlayReceiverServerRef)"
+ "OSStatus airplayReqProcessor_ensurePairingServices(APReceiverRequestProcessorRef, Boolean, APSTransportMessageProcessingStatus *)"
+ "OSStatus coreUtilsPairing_HandleSetup(APPairingServicesRef, CFStringRef, CFDataRef, CFDataRef *, Boolean *)"
+ "[%{ptr}] APPairingServicesCoreUtils created.\n"
+ "[%{ptr}] Created %s pairing services [%{ptr}]\n"
+ "_StartServers"
+ "airplayReqProcessor_ensurePairingServices"
+ "disablePairSetupThrottling"
+ "legacy"
- "1005.13.1"
- "OSStatus APPairingServicesCoreUtilsCreate(CFAllocatorRef, Boolean, APPairingServicesRef *)"
- "OSStatus coreUtilsPairing_HandleSetup(APPairingServicesRef, CFStringRef, APSecurityMode, CFDataRef, CFDataRef *, Boolean *)"
- "[%{ptr}] APPairingServicesCoreUtils (%s) created.\n"
- "[%{ptr}] Created legacy pairing services [%{ptr}]\n"
- "[%{ptr}] Created pairing services [%{ptr}] for pair-setup.\n"
- "[%{ptr}] Created pairing services [%{ptr}] for pair-verify\n"
- "private"
- "public"
- "void _StartServers(AirPlayReceiverServerRef)"
```
