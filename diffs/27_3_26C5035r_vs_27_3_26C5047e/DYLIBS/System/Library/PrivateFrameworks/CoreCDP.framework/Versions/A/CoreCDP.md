## CoreCDP

> `/System/Library/PrivateFrameworks/CoreCDP.framework/Versions/A/CoreCDP`

```diff

-448.250.2.0.0
-  __TEXT.__text: 0x520d8
-  __TEXT.__objc_methlist: 0x3ad4
+448.250.5.0.0
+  __TEXT.__text: 0x52288
+  __TEXT.__objc_methlist: 0x3aec
   __TEXT.__const: 0x14ec
   __TEXT.__gcc_except_tab: 0x1114
   __TEXT.__oslogstring: 0x91f1
-  __TEXT.__cstring: 0x67cd
+  __TEXT.__cstring: 0x67f2
   __TEXT.__dlopen_cstrs: 0x12e
   __TEXT.__ustring: 0x28
-  __TEXT.__unwind_info: 0x20b8
+  __TEXT.__unwind_info: 0x20c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1ef0
+  __DATA_CONST.__const: 0x1ef8
   __DATA_CONST.__objc_classlist: 0x1a8
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x21f8
+  __DATA_CONST.__objc_selrefs: 0x2218
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0xe8
   __DATA_CONST.__objc_arraydata: 0x1d0
   __DATA_CONST.__got: 0x500
   __AUTH_CONST.__const: 0x1970
-  __AUTH_CONST.__cfstring: 0x41a0
+  __AUTH_CONST.__cfstring: 0x41c0
   __AUTH_CONST.__objc_const: 0x8878
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x28

   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2444
-  Symbols:   4551
-  CStrings:  1659
+  Functions: 2446
+  Symbols:   4558
+  CStrings:  1660
 
Symbols:
+ +[CDPUtilities reportMissingEntitlementWithContext:error:]
+ +[CDPUtilities shouldDenyAccessGivenIsEntitled:context:error:alwaysEnforced:]
+ _kCDPAnalyticsMissingEntitlementEvent
+ _objc_msgSend$aaf_processName
+ _objc_msgSend$currentConnection
+ _objc_msgSend$isEntitlementEnforcementEnabled
+ _objc_msgSend$reportMissingEntitlementWithContext:error:
CStrings:
+ "com.apple.corecdp.missingEntitlement"
```
