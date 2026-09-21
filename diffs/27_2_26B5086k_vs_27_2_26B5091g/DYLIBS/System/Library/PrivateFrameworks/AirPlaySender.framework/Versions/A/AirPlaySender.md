## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/Versions/A/AirPlaySender`

```diff

-1005.7.1.0.0
-  __TEXT.__text: 0x1ccffc
+1005.8.1.0.0
+  __TEXT.__text: 0x1cd438
   __TEXT.__objc_methlist: 0x92c
-  __TEXT.__const: 0xd580
+  __TEXT.__const: 0xd530
   __TEXT.__gcc_except_tab: 0x62c
-  __TEXT.__cstring: 0x718bc
+  __TEXT.__cstring: 0x71a1d
   __TEXT.__dlopen_cstrs: 0x164
   __TEXT.__oslogstring: 0xb55
-  __TEXT.__unwind_info: 0x71e8
+  __TEXT.__unwind_info: 0x71f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_superrefs: 0x20
   __DATA_CONST.__objc_arraydata: 0x170
   __DATA_CONST.__got: 0x1de0
-  __AUTH_CONST.__const: 0x7200
+  __AUTH_CONST.__const: 0x7220
   __AUTH_CONST.__cfstring: 0x105c0
   __AUTH_CONST.__objc_const: 0xc58
   __AUTH_CONST.__objc_intobj: 0x150

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 9066
-  Symbols:   8801
-  CStrings:  9265
+  Functions: 9073
+  Symbols:   8807
+  CStrings:  9270
 
Symbols:
+ _APSIsUpdateInfoForwardingEnabled
+ _APTransportDeviceForwardAirPlayInfoToBrowser
+ _FigCFNumberGetCFIndex
+ _endpointCluster_failureCountForSubEndpoint
+ _endpoint_forwardUpdateInfo
+ endpointCluster_failDelayMSecsForFailureCount.kFailDelayLadderPercent
CStrings:
+ "1005.8.1"
+ "Eligible for fast reactivate"
+ "Local HT first loss"
+ "[%{ptr}] Fail delay timer already running, discarding requested delay of %llu ms for subEndpoint [%{ptr}]%?{end}, failure count %ld"
+ "[%{ptr}] Ignoring subEndpoint [%{ptr}] failure, cluster is deactivated"
+ "[%{ptr}] Immediately triggering lost cluster buddy reconnect logic for [%{ptr}] (session state: %s, reason: %s)"
+ "[%{ptr}] Starting fail delay timer for seed %llu, subEndpoint [%{ptr}], with delay of %llu ms%?{end}, failure count %ld"
+ "endpoint_forwardUpdateInfo"
+ "void endpointCluster_startFailDelayTimerIfNeeded(FigEndpointRef, FigEndpointRef)"
- "1005.7.1"
- "[%{ptr}] Immediately triggering lost cluster buddy reconnect logic for [%{ptr}] during startup\n"
- "[%{ptr}] Starting fail delay timer for seed %llu with delay of %llu seconds.\n"
- "void endpointCluster_startFailDelayTimerIfNeeded(FigEndpointRef)"
```
