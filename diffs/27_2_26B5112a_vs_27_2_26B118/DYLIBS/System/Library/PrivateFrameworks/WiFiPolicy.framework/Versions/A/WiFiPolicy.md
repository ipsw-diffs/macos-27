## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/Versions/A/WiFiPolicy`

```diff

 1077.3.0.0.0
-  __TEXT.__text: 0xdecac
+  __TEXT.__text: 0xdeca8
   __TEXT.__objc_methlist: 0x137c8
   __TEXT.__const: 0x7c0
-  __TEXT.__cstring: 0x239fb
+  __TEXT.__cstring: 0x23a3b
   __TEXT.__oslogstring: 0x4026
   __TEXT.__gcc_except_tab: 0x1754
   __TEXT.__dlopen_cstrs: 0x52

   __DATA_CONST.__objc_arraydata: 0x1528
   __DATA_CONST.__got: 0xb40
   __AUTH_CONST.__const: 0x2118
-  __AUTH_CONST.__cfstring: 0x1fc80
+  __AUTH_CONST.__cfstring: 0x1fca0
   __AUTH_CONST.__objc_const: 0x25248
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x1a58

   __AUTH.__objc_data: 0x5c8
   __DATA.__objc_ivar: 0x2510
   __DATA.__data: 0x1c38
-  __DATA.__bss: 0x49
+  __DATA.__bss: 0x48
   __DATA_DIRTY.__objc_data: 0x34d8
   __DATA_DIRTY.__data: 0x150
   __DATA_DIRTY.__bss: 0x338

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   Functions: 7072
-  Symbols:   15326
-  CStrings:  5062
+  Symbols:   15325
+  CStrings:  5063
 
Symbols:
- __isSeedInstall
Functions:
~ -[WiFiUsageLinkSession performLinkTestFor:isTriggeredByFault:] : 976 -> 1008
~ -[WFMeasure initWithType:andReason:prevTestedOptions:prevTestedTrafficClass:andInterfaceName:] : 1620 -> 1608
~ -[WiFiUsageSession _generateState] : 1028 -> 1032
~ +[WiFiUsagePrivacyFilter initialize] : 52 -> 40
~ +[WiFiUsagePrivacyFilter isInternalOrSeedInstall] : 28 -> 12
CStrings:
+ "%s Rejected due to [WiFiUsagePrivacyFilter isInternalInstall]\n"
```
