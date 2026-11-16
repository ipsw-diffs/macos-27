## AppSSOUI

> `/System/Library/PrivateFrameworks/AppSSOUI.framework/Versions/A/AppSSOUI`

```diff

-643.60.12.0.0
-  __TEXT.__text: 0x99cc
+643.60.14.0.0
+  __TEXT.__text: 0x9b00
   __TEXT.__objc_methlist: 0xb74
   __TEXT.__const: 0xb0
-  __TEXT.__oslogstring: 0xb28
-  __TEXT.__cstring: 0xdf7
+  __TEXT.__oslogstring: 0xb71
+  __TEXT.__cstring: 0xe21
   __TEXT.__gcc_except_tab: 0x330
   __TEXT.__dlopen_cstrs: 0x1fc
   __TEXT.__unwind_info: 0x3d8

   __DATA_CONST.__objc_classlist: 0x48
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb68
+  __DATA_CONST.__objc_selrefs: 0xb78
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x30
   __DATA_CONST.__got: 0x138
   __AUTH_CONST.__const: 0x3b0
-  __AUTH_CONST.__cfstring: 0x300
+  __AUTH_CONST.__cfstring: 0x320
   __AUTH_CONST.__objc_const: 0x1ab8
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__auth_got: 0x1b8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 194
-  Symbols:   681
-  CStrings:  147
+  Symbols:   683
+  CStrings:  149
 
Symbols:
+ _objc_msgSend$auditTokenFromData:auditToken:
+ _objc_msgSend$shouldTrustSuppliedAuditTokenFromPeerBundleIdentifier:suppliedTokenData:peerIsSocketDelegate:
Functions:
~ -[SOAgent _updateCallerPropertiesFromAuditTokenInParameters:] : 680 -> 988
CStrings:
+ "com.apple.private.network.socket-delegate"
+ "using impersonated audit token supplied by entitled %{public}@ transport"
```
