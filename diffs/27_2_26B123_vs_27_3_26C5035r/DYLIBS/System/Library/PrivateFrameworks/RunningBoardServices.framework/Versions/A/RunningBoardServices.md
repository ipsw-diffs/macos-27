## RunningBoardServices

> `/System/Library/PrivateFrameworks/RunningBoardServices.framework/Versions/A/RunningBoardServices`

```diff

-1084.40.7.0.0
-  __TEXT.__text: 0x46a20
-  __TEXT.__objc_methlist: 0x5cc8
+1084.60.3.0.0
+  __TEXT.__text: 0x47b9c
+  __TEXT.__objc_methlist: 0x5cd0
   __TEXT.__const: 0x170
-  __TEXT.__cstring: 0x4b98
+  __TEXT.__cstring: 0x4bce
   __TEXT.__oslogstring: 0x29d9
   __TEXT.__gcc_except_tab: 0x85c
   __TEXT.__unwind_info: 0x1e68

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6e8
+  __DATA_CONST.__const: 0x6f0
   __DATA_CONST.__objc_classlist: 0x458
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1e60
+  __DATA_CONST.__objc_selrefs: 0x1e98
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x2f0
   __DATA_CONST.__objc_arraydata: 0x10
-  __DATA_CONST.__got: 0x520
+  __DATA_CONST.__got: 0x528
   __AUTH_CONST.__const: 0xeb0
-  __AUTH_CONST.__cfstring: 0x6400
+  __AUTH_CONST.__cfstring: 0x64c0
   __AUTH_CONST.__objc_const: 0xb210
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_intobj: 0x18

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2417
-  Symbols:   4716
-  CStrings:  1117
+  Functions: 2418
+  Symbols:   4725
+  CStrings:  1123
 
Symbols:
+ -[NSError(RBSErrors) rbs_errorRedactedForUntrustedClient]
+ _OBJC_CLASS_$_NSCharacterSet
+ _RBSErrorRedactForUntrustedClientKey
+ _objc_msgSend$appendString:
+ _objc_msgSend$characterAtIndex:
+ _objc_msgSend$characterIsMember:
+ _objc_msgSend$controlCharacterSet
+ _objc_msgSend$rangeOfCharacterFromSet:
+ _objc_msgSend$stringWithCapacity:
Functions:
~ -[RBSDextProcessIdentity _initDextWithServerName:label:containingAppBundleID:] : 396 -> 760
~ -[RBSXPCServiceProcessIdentity _initWithXPCServiceID:pid:auid:] : 908 -> 1596
~ -[RBSXPCServiceDefinition description] : 128 -> 512
+ -[NSError(RBSErrors) rbs_errorRedactedForUntrustedClient]
~ -[RBSMacAppProcessIdentity _initMacAppWithLabel:bundleID:personaString:auid:platform:] : 700 -> 1432
~ -[RBSMacAppProcessIdentity debugDescription] : 296 -> 932
~ -[RBSExtensionProcessIdentity _initWithExtensionIdentity:hostIdentity:hostIdentifier:auid:] : 628 -> 2048
CStrings:
+ "%C"
+ "RBSErrorRedactForUntrustedClient"
+ "\\n"
+ "\\r"
+ "\\t"
+ "\\u{%04x}"
```
