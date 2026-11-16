## AudioSessionServer

> `/System/Library/PrivateFrameworks/AudioSessionServer.framework/Versions/A/AudioSessionServer`

```diff

-449.302.0.0.0
-  __TEXT.__text: 0x534c0
+449.305.0.0.0
+  __TEXT.__text: 0x53618
   __TEXT.__realtime: 0x40
   __TEXT.__objc_methlist: 0x934
   __TEXT.__const: 0xaf0
-  __TEXT.__gcc_except_tab: 0x8004
-  __TEXT.__cstring: 0x3612
-  __TEXT.__oslogstring: 0x58ff
+  __TEXT.__gcc_except_tab: 0x802c
+  __TEXT.__cstring: 0x3635
+  __TEXT.__oslogstring: 0x5956
   __TEXT.__dlopen_cstrs: 0x6a
   __TEXT.__unwind_info: 0x2750
   __TEXT.__objc_stubs: 0x0

   __DATA_CONST.__objc_selrefs: 0x7e0
   __DATA_CONST.__objc_superrefs: 0x28
   __DATA_CONST.__objc_arraydata: 0x40
-  __DATA_CONST.__got: 0x6a8
+  __DATA_CONST.__got: 0x6b0
   __AUTH_CONST.__const: 0x1258
-  __AUTH_CONST.__cfstring: 0x10a0
+  __AUTH_CONST.__cfstring: 0x10c0
   __AUTH_CONST.__objc_const: 0xb70
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_arrayobj: 0x30

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 1293
-  Symbols:   2350
-  CStrings:  848
+  Symbols:   2351
+  CStrings:  850
 
Symbols:
+ _kAudioSessionNotification_InterruptionInfoKey_EndInterruptionLikelyToBeResumable
Functions:
~ -[AVAudioSessionRemoteXPCClient updateApplicationProperty:clientID:propertyID:propertyValue:context:reply:] : 976 -> 980
~ -[AVAudioSessionRemoteXPCClient setIONode:playState:modes:reply:] : 432 -> 600
~ ____ZN12_GLOBAL__N_130HandleInterruptionNotificationEjP12NSDictionary_block_invoke : 2308 -> 2480
CStrings:
+ "%25s:%-5d IONodeSession privileged play state modes (0x%lx) are not permitted over XPC"
+ "EndInterruptionLikelyToBeResumable"
```
