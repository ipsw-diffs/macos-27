## XPCSupport

> `/System/Library/PrivateFrameworks/XPCSupport.framework/Versions/A/XPCSupport`

```diff

-3298.60.14.0.0
-  __TEXT.__text: 0x10fc
-  __TEXT.__lazy_helpers: 0x594
+3298.60.20.0.0
+  __TEXT.__text: 0x13a0
+  __TEXT.__lazy_helpers: 0x690
   __TEXT.__const: 0x50
-  __TEXT.__oslogstring: 0x110
-  __TEXT.__cstring: 0x1cc
+  __TEXT.__oslogstring: 0x174
+  __TEXT.__cstring: 0x23a
   __TEXT.__unwind_info: 0xb0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_methname: 0x0
   __DATA_CONST.__const: 0xc8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x58
+  __DATA_CONST.__objc_selrefs: 0x70
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x20
-  __AUTH_CONST.__lazy_load_got: 0x80
+  __AUTH_CONST.__lazy_load_got: 0x98
   __AUTH_CONST.__auth_got: 0x0
   __DATA.__crash_info: 0x148
   __DATA.__data: 0x10

   __DATA_DIRTY.__common: 0x8
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 15
-  Symbols:   61
-  CStrings:  25
+  Functions: 16
+  Symbols:   65
+  CStrings:  28
 
Symbols:
+ _BTMDispositionIsLaunchable
+ _BTMErrorString
+ _OBJC_CLASS_$_NSURL
+ _xpc_support_register_xpcservice_with_btm
Functions:
+ _xpc_support_register_xpcservice_with_btm
CStrings:
+ "BTMManager registerItem returned nil item: path=%s"
+ "Failed to register XPC service with BTM: path=%s, error=%s"
+ "assertion failure: \"(domain_type == XPC_DOMAIN_SYSTEM) || (domain_type == XPC_DOMAIN_USER)\" -> %llu"
```
