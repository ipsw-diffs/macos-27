## FrontBoard

> `/System/Library/PrivateFrameworks/FrontBoard.framework/Versions/A/FrontBoard`

```diff

-1153.2.2.0.0
-  __TEXT.__text: 0x80510
-  __TEXT.__objc_methlist: 0x54e0
-  __TEXT.__const: 0x29c
-  __TEXT.__cstring: 0xab6d
+1153.3.2.0.0
+  __TEXT.__text: 0x80bbc
+  __TEXT.__objc_methlist: 0x5500
+  __TEXT.__const: 0x2ac
+  __TEXT.__cstring: 0xabdd
   __TEXT.__oslogstring: 0x5d2e
-  __TEXT.__gcc_except_tab: 0xaf4
+  __TEXT.__gcc_except_tab: 0xafc
   __TEXT.__dlopen_cstrs: 0x58
-  __TEXT.__unwind_info: 0x29a0
+  __TEXT.__unwind_info: 0x29c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6d8
+  __DATA_CONST.__const: 0x710
   __DATA_CONST.__objc_classlist: 0x298
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x248
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x34c8
+  __DATA_CONST.__objc_selrefs: 0x34d8
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x208
+  __DATA_CONST.__objc_superrefs: 0x210
   __DATA_CONST.__objc_arraydata: 0x20
   __DATA_CONST.__got: 0x890
   __AUTH_CONST.__const: 0x2b90
-  __AUTH_CONST.__cfstring: 0x8a00
-  __AUTH_CONST.__objc_const: 0xaea8
+  __AUTH_CONST.__cfstring: 0x8b00
+  __AUTH_CONST.__objc_const: 0xaed8
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x5a0
-  __DATA.__objc_ivar: 0x8fc
+  __DATA.__objc_ivar: 0x900
   __DATA.__data: 0x1b60
   __DATA.__bss: 0xd0
   __DATA_DIRTY.__objc_data: 0x1450

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3017
-  Symbols:   5798
-  CStrings:  1683
+  Functions: 3027
+  Symbols:   5805
+  CStrings:  1690
 
Symbols:
+ +[FBProcessWatchdogEventContext contextForEvent:visibility:settings:transitionContext:]
+ -[FBProcessWatchdogEventContext _initWithEvent:visibility:settings:transitionContext:]
+ -[FBProcessWatchdogEventContext visibility]
+ -[FBSystemService _isTrustedRequest:forCaller:fromClient:forBundleInfo:withOptions:shouldLogResult:fatalError:]
+ _FBProcessWatchdogEventVisibilityIsValid
+ _NSStringFromProcessWatchdogEventVisibility
+ _OBJC_IVAR_$_FBProcessWatchdogEventContext._visibility
+ _objc_msgSend$_initWithEvent:visibility:settings:transitionContext:
+ _objc_msgSend$_isTrustedRequest:forCaller:fromClient:forBundleInfo:withOptions:shouldLogResult:fatalError:
+ _objc_msgSend$contextForEvent:visibility:settings:transitionContext:
- -[FBSystemService _isTrustedRequest:forCaller:fromClient:forBundleInfo:withOptions:fatalError:]
- _objc_msgSend$_isTrustedRequest:forCaller:fromClient:forBundleInfo:withOptions:fatalError:
- _objc_msgSend$contextForEvent:settings:transitionContext:
CStrings:
+ "FBProcessWatchdogEvents.m"
+ "bg"
+ "fg"
+ "fg->bg"
+ "invalid event: %@"
+ "invalid visibility: %@"
+ "notSet"
+ "outError != ((void *)0)"
- "!"
```
