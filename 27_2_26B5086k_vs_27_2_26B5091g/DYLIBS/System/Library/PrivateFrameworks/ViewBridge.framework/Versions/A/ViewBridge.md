## ViewBridge

> `/System/Library/PrivateFrameworks/ViewBridge.framework/Versions/A/ViewBridge`

```diff

-864.0.0.0.0
-  __TEXT.__text: 0xb579c
+865.0.0.0.0
+  __TEXT.__text: 0xb58ec
   __TEXT.__objc_methlist: 0x7b1c
   __TEXT.__const: 0x1c8
   __TEXT.__gcc_except_tab: 0x5f30
-  __TEXT.__cstring: 0x23d82
-  __TEXT.__oslogstring: 0xe015
+  __TEXT.__cstring: 0x23dc6
+  __TEXT.__oslogstring: 0xe060
   __TEXT.__unwind_info: 0x5800
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_arraydata: 0x70
   __DATA_CONST.__got: 0x730
   __AUTH_CONST.__const: 0x3918
-  __AUTH_CONST.__cfstring: 0x101c0
+  __AUTH_CONST.__cfstring: 0x101e0
   __AUTH_CONST.__objc_const: 0xb020
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x18

   - /usr/lib/libobjc.A.dylib
   Functions: 5106
   Symbols:   8405
-  CStrings:  4729
+  CStrings:  4734
 
Functions:
~ +[NSViewServiceApplication isFakeEvent:] : 84 -> 100
~ -[NSViewServiceApplication event:wouldActivateWindow:] : 424 -> 588
~ -[NSRemoteView _sendWindowFakeClick:why:] : 1436 -> 1444
~ -[NSRemoteView _serviceViewReceivedLeftMouseDown:] : 252 -> 400
CStrings:
+ "%@ forwarding click count %ld upward"
+ "%@ informing host of activating touch"
+ "notify host of activating touch"
+ "service window received touch"
+ "touch"
```
