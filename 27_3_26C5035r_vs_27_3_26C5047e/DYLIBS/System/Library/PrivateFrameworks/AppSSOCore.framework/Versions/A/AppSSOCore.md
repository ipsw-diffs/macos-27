## AppSSOCore

> `/System/Library/PrivateFrameworks/AppSSOCore.framework/Versions/A/AppSSOCore`

```diff

-643.60.12.0.0
-  __TEXT.__text: 0x12e80
-  __TEXT.__objc_methlist: 0x1234
+643.60.14.0.0
+  __TEXT.__text: 0x12f74
+  __TEXT.__objc_methlist: 0x1244
   __TEXT.__const: 0x120
-  __TEXT.__cstring: 0x195f
-  __TEXT.__oslogstring: 0x1c06
+  __TEXT.__cstring: 0x1989
+  __TEXT.__oslogstring: 0x1c49
   __TEXT.__gcc_except_tab: 0x1b8
-  __TEXT.__unwind_info: 0x7b0
+  __TEXT.__unwind_info: 0x7b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x98
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9e8
+  __DATA_CONST.__objc_selrefs: 0x9f0
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x78
   __DATA_CONST.__objc_arraydata: 0x108

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 553
-  Symbols:   1148
-  CStrings:  343
+  Functions: 556
+  Symbols:   1150
+  CStrings:  345
 
Symbols:
+ +[SOUtils shouldTrustSuppliedAuditTokenFromPeerBundleIdentifier:suppliedTokenData:peerIsSocketDelegate:]
+ _OUTLINED_FUNCTION_8
Functions:
~ +[SOUtils sandboxAllowsXPC:].cold.1 : 100 -> 96
+ +[SOUtils shouldTrustSuppliedAuditTokenFromPeerBundleIdentifier:suppliedTokenData:peerIsSocketDelegate:]
~ _OUTLINED_FUNCTION_7 : 20 -> 12
+ _OUTLINED_FUNCTION_8
~ +[SOUtils bundleIdentifierFromAuditToken:].cold.1 : 60 -> 56
~ +[SOUtils bundleIdentifierFromAuditToken:].cold.2 : 60 -> 56
+ +[SOUtils shouldTrustSuppliedAuditTokenFromPeerBundleIdentifier:suppliedTokenData:peerIsSocketDelegate:].cold.1
CStrings:
+ "%{public}@ supplied an audit token without %{public}s, ignoring it"
+ "com.apple.private.network.socket-delegate"
```
