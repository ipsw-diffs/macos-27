## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/Versions/A/WiFiPolicy`

```diff

 1075.60.0.0.0
-  __TEXT.__text: 0xe0dc4
+  __TEXT.__text: 0xe0de8
   __TEXT.__objc_methlist: 0x13658
   __TEXT.__const: 0x7a0
-  __TEXT.__cstring: 0x2392b
+  __TEXT.__cstring: 0x2396b
   __TEXT.__oslogstring: 0x4026
   __TEXT.__gcc_except_tab: 0x1754
   __TEXT.__dlopen_cstrs: 0x52

   __DATA_CONST.__objc_arraydata: 0x1508
   __DATA_CONST.__got: 0xb38
   __AUTH_CONST.__const: 0x2118
-  __AUTH_CONST.__cfstring: 0x1fc00
+  __AUTH_CONST.__cfstring: 0x1fc20
   __AUTH_CONST.__objc_const: 0x24fd8
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x1a58

   - /usr/lib/swift/libswiftos.dylib
   Functions: 7036
   Symbols:   15214
-  CStrings:  5057
+  CStrings:  5058
 
Functions:
~ -[WiFiUsageLinkSession performLinkTestFor:isTriggeredByFault:] : 976 -> 1008
~ -[WFMeasure initWithType:andReason:prevTestedOptions:prevTestedTrafficClass:andInterfaceName:] : 1620 -> 1608
~ __ZNSt3__16vectorIN6gloria6TileIdENS_9allocatorIS2_EEE6resizeEm : 300 -> 308
~ -[WiFiUsagePoorLinkSession roamCacheDidUpdate:] : 968 -> 972
~ -[WiFiUsageSession _generateState] : 1028 -> 1032
CStrings:
+ "%s Rejected due to [WiFiUsagePrivacyFilter isInternalInstall]\n"
```
