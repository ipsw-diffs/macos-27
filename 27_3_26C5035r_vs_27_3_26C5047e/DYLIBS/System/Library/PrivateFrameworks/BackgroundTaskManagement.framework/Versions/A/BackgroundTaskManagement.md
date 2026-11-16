## BackgroundTaskManagement

> `/System/Library/PrivateFrameworks/BackgroundTaskManagement.framework/Versions/A/BackgroundTaskManagement`

```diff

-371.2.2.0.0
-  __TEXT.__text: 0x1f610
-  __TEXT.__objc_methlist: 0x1994
+371.2.4.0.0
+  __TEXT.__text: 0x1fae8
+  __TEXT.__objc_methlist: 0x19d4
   __TEXT.__const: 0xe8
-  __TEXT.__oslogstring: 0x1ae5
-  __TEXT.__cstring: 0x1b73
+  __TEXT.__oslogstring: 0x1baa
+  __TEXT.__cstring: 0x1ba0
   __TEXT.__gcc_except_tab: 0xc3c
-  __TEXT.__unwind_info: 0xd80
+  __TEXT.__unwind_info: 0xda0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1100
+  __DATA_CONST.__objc_selrefs: 0x1128
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x68
   __DATA_CONST.__got: 0x278
   __AUTH_CONST.__const: 0xbf0
   __AUTH_CONST.__cfstring: 0x1480
-  __AUTH_CONST.__objc_const: 0x2090
+  __AUTH_CONST.__objc_const: 0x20b0
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__auth_got: 0x0
-  __DATA.__objc_ivar: 0x118
+  __DATA.__objc_ivar: 0x11c
   __DATA.__data: 0x438
   __DATA.__bss: 0x78
   __DATA_DIRTY.__objc_data: 0x410

   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libTLE.dylib
+  - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 861
-  Symbols:   1492
-  CStrings:  440
+  Functions: 871
+  Symbols:   1506
+  CStrings:  444
 
Symbols:
+ +[BTMCodeSignInfo codeSignInfoForAuditToken:error:]
+ +[BTMCodeSignInfo validateWithRequirement:url:]
+ -[BTMCodeSignInfo androgynousSecCode]
+ -[BTMCodeSignInfo initWithAuditToken:error:]
+ -[BTMCodeSignInfo validateWithRequirement:basic:]
+ _BTMItemIdentifierForAuditTokenAndType
+ _OBJC_IVAR_$_BTMCodeSignInfo._secStaticCode
+ _SecCodeCheckValidity
+ __BTMItemTypeUsesSigningIdentifier
+ _audit_token_to_pid
+ _objc_msgSend$androgynousSecCode
+ _objc_msgSend$codeSignInfoForAuditToken:error:
+ _objc_msgSend$initWithAuditToken:error:
+ _objc_msgSend$validateWithRequirement:basic:
CStrings:
+ "%s: result=%d, pid=%d"
+ "-[BTMCodeSignInfo initWithAuditToken:error:]"
+ "BTMCodeSignInfo.validateRequirement: error status %d parsing requirement: %{public}@"
+ "BTMCodeSignInfo.validateRequirement: validation failed: requirement=%{public}@, status=%d"
```
