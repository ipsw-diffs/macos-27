## com.apple.AppleSunriseWLAN

> `/System/Library/DriverExtensions/com.apple.AppleSunriseWLAN.dext/com.apple.AppleSunriseWLAN`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-365.3.0.0.0
-  __TEXT.__text: 0x398ca4
+365.5.0.0.0
+  __TEXT.__text: 0x3998e8
   __TEXT.__auth_stubs: 0x1410
-  __TEXT.__cstring: 0xe7bbf
-  __TEXT.__const: 0xd380
-  __TEXT.__unwind_info: 0x6b28
+  __TEXT.__cstring: 0xe800e
+  __TEXT.__const: 0xd360
+  __TEXT.__unwind_info: 0x6b30
   __TEXT.__oslogstring: 0x18f
   __DATA_CONST.__const: 0xe868
   __DATA_CONST.__osclassinfo: 0xd8

   - /System/DriverKit/System/Library/PrivateFrameworks/IO80211DriverKit.framework/IO80211DriverKit
   - /System/DriverKit/System/Library/PrivateFrameworks/IOFileValidation.framework/IOFileValidation
   - /System/DriverKit/usr/lib/libc++.dylib
-  Functions: 8076
-  Symbols:   10041
-  CStrings:  20370
+  Functions: 8079
+  Symbols:   10044
+  CStrings:  20393
 
Symbols:
+ _nanNdlSendNafWithRetry
+ _nanNdlStopRetryTimer
+ _nanNdpSendNafWithRetry
Functions:
+ _getReasonCodeString
- _getReasonCodeString
~ _nanDataPathProtocolFsmStep : 1756 -> 1808
~ _nanDataProtocolTimeout : 292 -> 676
~ _nanNdlMgmtFsmStep : 2288 -> 2264
~ _nanDataRetryTimeout : 268 -> 1068
~ _nanDataFreeNdl : 468 -> 488
~ _nanNdpProcessDataRequest : 2208 -> 2576
~ _nanNdpAutoReplyDataRequest : 996 -> 1120
~ _nanNdlProcessScheduleRequest : 940 -> 1424
~ _nanNdlSendScheduleResponse : 804 -> 820
~ _nanCmdDataResponse : 3196 -> 3312
~ _nanDPReqTxDone : 936 -> 948
~ _nanDPRespTxDone : 1168 -> 1160
~ _nanDPConfirmTxDone : 1116 -> 1124
~ _nanDPSecurityInstallTxDone : 1092 -> 1084
~ _nanDPTerminationTxDone : 900 -> 928
+ _nanNdlStopRetryTimer
+ _nanNdpSendNafWithRetry
~ _nanDataPathScheduleNegoGranted : 692 -> 712
+ _nanNdlSendNafWithRetry
CStrings:
+ "\"AppleSunriseWLAN_driverkit-365.5\""
+ "%llu-%u-[%d]%s:(NAN ERROR) NDP response(reject) send fail, ReasonCode = %s\n"
+ "%llu-%u-[%d]%s:(NAN ERROR) NDP response(reject) send fail, reason=%s\n"
+ "%llu-%u-[%d]%s:(NAN ERROR) SchedRsp(no resource) send fail, peer=%02x:%02x:%02x:%02x:%02x:%02x, ReasonCode = %s\n"
+ "%llu-%u-[%d]%s:(NAN ERROR) SchedRsp(reject) send fail, peer=%02x:%02x:%02x:%02x:%02x:%02x, ReasonCode = %s\n"
+ "%llu-%u-[%d]%s:(NAN ERROR) SchedRsp(reject,new NDL) send fail, peer=%02x:%02x:%02x:%02x:%02x:%02x, ReasonCode = %s\n"
+ "%llu-%u-[%d]%s:(NAN ERROR) unhandled state=(%s), NDP_ID:%u\n"
+ "%llu-%u-[%d]%s:(NAN ERROR) unhandled state=(%s), NDP_ID:%u, operating=%p, endReason=%u\n"
+ "%llu-%u-[%d]%s:(NAN STATE) no operating NDP, NDL peer=%02x:%02x:%02x:%02x:%02x:%02x, mgmtState=%s\n"
+ "%llu-%u-[%d]%s:(NAN WARN) %s send fail, go disconnect, NDP_ID:%u\n"
+ "%llu-%u-[%d]%s:(NAN WARN) %s send fail, go teardown, peer=%02x:%02x:%02x:%02x:%02x:%02x\n"
+ "%llu-%u-[%d]%s:(NAN WARN) term timeout, NDP_ID:%u\n"
+ "AppleSunriseWLAN_driverkit-365.5"
+ "NDL_INVALID_STATE"
+ "NDP Req"
+ "NDP confirm"
+ "NDP response"
+ "NDP sec-install"
+ "NDP term"
+ "NDP_INVALID_STATE"
+ "Nov  9 2026 23:47:58"
+ "SchedCfm"
+ "SchedReq"
+ "SchedRsp"
+ "nanNdlSendNafWithRetry"
+ "nanNdpSendNafWithRetry"
- "\"AppleSunriseWLAN_driverkit-365.3\""
- "AppleSunriseWLAN_driverkit-365.3"
- "Oct 28 2026 22:36:04"
```
