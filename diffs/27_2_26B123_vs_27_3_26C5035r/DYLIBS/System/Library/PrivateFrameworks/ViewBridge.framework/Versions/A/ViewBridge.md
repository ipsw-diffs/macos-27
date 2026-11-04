## ViewBridge

> `/System/Library/PrivateFrameworks/ViewBridge.framework/Versions/A/ViewBridge`

```diff

 869.0.0.0.0
-  __TEXT.__text: 0xb5b30
-  __TEXT.__objc_methlist: 0x7b24
+  __TEXT.__text: 0xb5ca4
+  __TEXT.__objc_methlist: 0x7b3c
   __TEXT.__const: 0x1c8
   __TEXT.__gcc_except_tab: 0x5f30
-  __TEXT.__cstring: 0x23dc3
+  __TEXT.__cstring: 0x23e5b
   __TEXT.__oslogstring: 0xe0ed
-  __TEXT.__unwind_info: 0x5800
+  __TEXT.__unwind_info: 0x5810
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4c0
-  __DATA_CONST.__objc_classlist: 0x3c8
+  __DATA_CONST.__const: 0x4c8
+  __DATA_CONST.__objc_classlist: 0x3d0
   __DATA_CONST.__objc_nlclslist: 0x8
   __DATA_CONST.__objc_catlist: 0x80
   __DATA_CONST.__objc_protolist: 0x168

   __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_superrefs: 0x390
   __DATA_CONST.__objc_arraydata: 0x70
-  __DATA_CONST.__got: 0x730
+  __DATA_CONST.__got: 0x738
   __AUTH_CONST.__const: 0x3918
-  __AUTH_CONST.__cfstring: 0x101e0
-  __AUTH_CONST.__objc_const: 0xb020
+  __AUTH_CONST.__cfstring: 0x10240
+  __AUTH_CONST.__objc_const: 0xb0b0
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__auth_got: 0xb30
-  __AUTH.__objc_data: 0x18b0
+  __AUTH.__objc_data: 0x1900
   __DATA.__objc_ivar: 0x788
   __DATA.__data: 0x13d8
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x488
+  __DATA.__bss: 0x458
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0xd20
   __DATA_DIRTY.__data: 0x1a
-  __DATA_DIRTY.__bss: 0x208
+  __DATA_DIRTY.__bss: 0x238
   __DATA_DIRTY.__common: 0x8
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 5107
-  Symbols:   8104
-  CStrings:  4736
+  Functions: 5111
+  Symbols:   8108
+  CStrings:  4739
 
Symbols:
+ -[NSRendezvousStoplightsWindowController _serviceWindowFrameForRemoteViewFrame:]
+ _OBJC_CLASS_$_NSRendezvousStoplightsWindowController
+ _OBJC_METACLASS_$_NSRendezvousStoplightsWindowController
+ __OBJC_$_INSTANCE_METHODS_NSRendezvousStoplightsWindowController
+ __OBJC_CLASS_RO_$_NSRendezvousStoplightsWindowController
+ __OBJC_METACLASS_RO_$_NSRendezvousStoplightsWindowController
- _vbuHostWindowClassFromWindowBase.baseClasses
- _vbuHostWindowClassFromWindowBase.once
Functions:
~ -[NSViewServiceMarshal _addChildWindow:ordered:] : 948 -> 968
~ +[NSViewServiceMarshal beginFreeWindowRendezvous:] : 1160 -> 1180
~ ___70+[NSRendezvousWindowController bridgeKeysForSemiAutonomousWindowBase:]_block_invoke : 184 -> 220
+ -[NSRendezvousStoplightsWindowController _serviceWindowFrameForRemoteViewFrame:]
~ ___vbuHostWindowClassFromWindowBase_block_invoke : 132 -> 168
~ _OUTLINED_FUNCTION_0 : 12 -> 20
~ _OUTLINED_FUNCTION_1 : 24 -> 12
~ _OUTLINED_FUNCTION_2 : 20 -> 24
+ _OUTLINED_FUNCTION_3
+ ___70+[NSRendezvousWindowController bridgeKeysForSemiAutonomousWindowBase:]_block_invoke.cold.5
~ -[NSWindow windowBase] : 300 -> 392
~ ___vbuHostWindowClassFromWindowBase_block_invoke.cold.1 : 52 -> 44
~ ___vbuHostWindowClassFromWindowBase_block_invoke.cold.2 : 52 -> 44
~ ___vbuHostWindowClassFromWindowBase_block_invoke.cold.3 : 52 -> 44
+ ___vbuHostWindowClassFromWindowBase_block_invoke.cold.4
CStrings:
+ "%@ unable to obtain class for rendezvous stoplights window controller"
+ "AppKit.NSStopLightControlWindow"
+ "unable to obtain class for NSWindowBaseStoplights"
```
