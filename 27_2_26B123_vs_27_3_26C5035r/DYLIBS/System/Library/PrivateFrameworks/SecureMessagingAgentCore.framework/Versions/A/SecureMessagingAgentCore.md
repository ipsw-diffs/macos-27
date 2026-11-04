## SecureMessagingAgentCore

> `/System/Library/PrivateFrameworks/SecureMessagingAgentCore.framework/Versions/A/SecureMessagingAgentCore`

```diff

-59.200.41.0.0
-  __TEXT.__text: 0x138c4c
+59.300.21.0.0
+  __TEXT.__text: 0x138e28
   __TEXT.__objc_methlist: 0x9e8
-  __TEXT.__const: 0x8948
+  __TEXT.__const: 0x8958
   __TEXT.__cstring: 0x3f39
-  __TEXT.__oslogstring: 0x9c6f
+  __TEXT.__oslogstring: 0x9cef
   __TEXT.__swift5_typeref: 0x24c8
-  __TEXT.__constg_swiftt: 0x1fc0
+  __TEXT.__constg_swiftt: 0x1fc8
   __TEXT.__swift5_reflstr: 0x1932
   __TEXT.__swift5_fieldmd: 0x1b28
   __TEXT.__swift5_proto: 0x378

   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_mpenum: 0x1c
   __TEXT.__unwind_info: 0x6800
-  __TEXT.__eh_frame: 0x1280c
+  __TEXT.__eh_frame: 0x1281c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __AUTH_CONST.__const: 0x9f91
   __AUTH_CONST.__cfstring: 0x60
   __AUTH_CONST.__objc_const: 0x2708
-  __AUTH_CONST.__auth_got: 0x1410
+  __AUTH_CONST.__auth_got: 0x1418
   __AUTH.__objc_data: 0x610
   __AUTH.__data: 0x658
   __DATA.__objc_ivar: 0xc
-  __DATA.__data: 0x1160
+  __DATA.__data: 0x1170
   __DATA.__bss: 0x3530
   __DATA.__common: 0x1b8
   __DATA_DIRTY.__objc_data: 0x828
-  __DATA_DIRTY.__data: 0x1c20
+  __DATA_DIRTY.__data: 0x1c40
   __DATA_DIRTY.__common: 0x280
   __DATA_DIRTY.__bss: 0x1900
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   Functions: 5878
-  Symbols:   11621
-  CStrings:  685
+  Symbols:   11623
+  CStrings:  686
 
Symbols:
+ _$s15SecureMessaging9ServerBagV3KDSP17refreshKeysJitterSdvgTj
+ _$s24SecureMessagingAgentCore27KDSRegistrationStateMachineC15heartbeatJitter33_229819B7868B1079C93FA683752F9003LLSdvg
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.1573TQ0_
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.1573Tu
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.1585TQ0_
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.1585Tu
+ ___swift_closure_destructor.193Tm
+ ___swift_closure_destructor.616Tm
+ ___swift_closure_destructor.992Tm
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.1572TQ0_
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.1572Tu
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.1584TQ0_
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.1584Tu
- ___swift_closure_destructor.192Tm
- ___swift_closure_destructor.615Tm
- ___swift_closure_destructor.991Tm
CStrings:
+ "Cert does not need refresh. { issueDate: %s, adjustedIssueDate: %s, currentDate: %s, flooredCertRefreshInterval: %ld, certRefreshThreshold: %f }"
+ "Cert will need refresh. { issueDate: %s, adjustedIssueDate: %s, currentDate: %s, flooredCertRefreshInterval: %ld, certRefreshThreshold: %f }"
+ "Remaining %fs exceeds maxHeartbeatInterval %fs. Using refreshKeysInterval."
+ "Scheduling next heartbeat { interval: %f, jitter: %f, jitteredInterval: %f }"
- "Cert does not need refresh. { issueDate: %s, adjustedIssueDate: %s, currentDate: %s, flooredCertRefreshInterval: %ld }"
- "Cert will need refresh. { issueDate: %s, adjustedIssueDate: %s, currentDate: %s, flooredCertRefreshInterval: %ld }"
- "Remaining %fs exceeds refreshKeysInterval %fs. Using refreshKeysInterval."
```
