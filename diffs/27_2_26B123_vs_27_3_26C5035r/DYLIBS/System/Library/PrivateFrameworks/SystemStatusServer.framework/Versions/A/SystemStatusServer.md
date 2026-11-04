## SystemStatusServer

> `/System/Library/PrivateFrameworks/SystemStatusServer.framework/Versions/A/SystemStatusServer`

```diff

-288.1.5.0.0
-  __TEXT.__text: 0x1290c
-  __TEXT.__objc_methlist: 0xdf8
+288.2.6.0.0
+  __TEXT.__text: 0x12a1c
+  __TEXT.__objc_methlist: 0xe00
   __TEXT.__const: 0x88
-  __TEXT.__cstring: 0x793
+  __TEXT.__cstring: 0x795
   __TEXT.__gcc_except_tab: 0x190
   __TEXT.__oslogstring: 0x49f
-  __TEXT.__unwind_info: 0x610
+  __TEXT.__unwind_info: 0x618
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0xc8
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9d0
+  __DATA_CONST.__objc_selrefs: 0x9e0
   __DATA_CONST.__objc_superrefs: 0xc8
   __DATA_CONST.__got: 0x2c8
   __AUTH_CONST.__const: 0xa90
   __AUTH_CONST.__cfstring: 0x3a0
-  __AUTH_CONST.__objc_const: 0x24a0
+  __AUTH_CONST.__objc_const: 0x24c0
   __AUTH_CONST.__auth_got: 0x0
-  __DATA.__objc_ivar: 0x174
+  __DATA.__objc_ivar: 0x178
   __DATA.__data: 0x6c0
   __DATA_DIRTY.__objc_data: 0x7d0
   __DATA_DIRTY.__bss: 0x20

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 380
-  Symbols:   1220
+  Functions: 381
+  Symbols:   1224
   CStrings:  75
 
Symbols:
+ -[STAttributedEntityResolver initWithPreferredLocalizations:identityResolver:applicationNameProvider:]
+ _OBJC_IVAR_$_STAttributedEntityResolver._applicationNameProvider
+ _objc_msgSend$initWithPreferredLocalizations:identityResolver:applicationNameProvider:
+ _objc_msgSend$length
Functions:
~ -[STAttributedEntityResolver initWithPreferredLocalizations:identityResolver:] : 196 -> 8
+ -[STAttributedEntityResolver initWithPreferredLocalizations:identityResolver:applicationNameProvider:]
~ -[STAttributedEntityResolver resolveEntity:] : 4720 -> 4916
~ -[STAttributedEntityResolver .cxx_destruct] : 92 -> 104
```
