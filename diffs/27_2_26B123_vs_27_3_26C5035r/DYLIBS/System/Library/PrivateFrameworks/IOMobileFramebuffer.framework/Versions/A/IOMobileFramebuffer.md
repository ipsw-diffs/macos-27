## IOMobileFramebuffer

> `/System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/Versions/A/IOMobileFramebuffer`

```diff

-700.50.117.0.0
-  __TEXT.__text: 0x3ad34
+700.51.10.0.0
+  __TEXT.__text: 0x3ad60
   __TEXT.__gcc_except_tab: 0x234
   __TEXT.__const: 0x1b04
-  __TEXT.__cstring: 0x96bb
+  __TEXT.__cstring: 0x95bb
   __TEXT.__unwind_info: 0xbd0
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0xb8

   - /usr/lib/libc++.1.dylib
   Functions: 929
   Symbols:   1100
-  CStrings:  951
+  CStrings:  947
 
Functions:
~ _kern_SwapSetPostBlendLayer : 372 -> 396
~ _kern_SwapSetPostBlendLayerEventWait : 112 -> 136
~ _kern_SwapSetPostBlendLayerEventSignalOnGlass : 64 -> 8
~ _kern_SwapSetPostBlendLayerEventSignal : 112 -> 136
~ _IOMobileFramebufferOpenByName : 1560 -> 1564
~ _IOMobileFramebufferGetWirelessSurfaceWithOptions : 396 -> 404
~ _virt_SwapEnd : 636 -> 640
~ _virt_SwapCancel : 268 -> 272
~ _virt_CreateStatistics : 208 -> 216
CStrings:
- "%s - event=%p signalOnGlassValue=0x%llx\n"
- "%s - postBlendLayer=%d event=%p signalValue=0x%llx\n"
- "%s - postBlendLayer=%d event=%p waitValue=0x%llx\n"
- "IOReturn kern_SwapSetPostBlendLayerEventSignalOnGlass(IOMobileFramebufferRef, IOSurfaceSharedEventRef, uint64_t)"
```
