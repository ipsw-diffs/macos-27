## ExchangeWebServices

> `/System/Library/PrivateFrameworks/ExchangeWebServices.framework/Versions/A/ExchangeWebServices`

```diff

-846.300.31.1.1
-  __TEXT.__text: 0x436d8
-  __TEXT.__objc_methlist: 0xb420
+846.300.41.0.0
+  __TEXT.__text: 0x43bd8
+  __TEXT.__objc_methlist: 0xb4a8
   __TEXT.__const: 0x1b0
-  __TEXT.__cstring: 0xac50
-  __TEXT.__oslogstring: 0x13a9
+  __TEXT.__cstring: 0xacf7
+  __TEXT.__oslogstring: 0x1420
   __TEXT.__gcc_except_tab: 0x5f0
-  __TEXT.__unwind_info: 0x1870
+  __TEXT.__unwind_info: 0x1890
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2650
-  __DATA_CONST.__objc_classlist: 0xfb0
+  __DATA_CONST.__const: 0x2668
+  __DATA_CONST.__objc_classlist: 0xfb8
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4108
+  __DATA_CONST.__objc_selrefs: 0x4168
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x458
   __DATA_CONST.__objc_arraydata: 0x110
-  __DATA_CONST.__got: 0x1100
+  __DATA_CONST.__got: 0x1108
   __AUTH_CONST.__const: 0x7d0
-  __AUTH_CONST.__cfstring: 0x10c40
-  __AUTH_CONST.__objc_const: 0x4a448
+  __AUTH_CONST.__cfstring: 0x10d60
+  __AUTH_CONST.__objc_const: 0x4a568
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_intobj: 0x90
   __AUTH_CONST.__auth_got: 0x340
-  __AUTH.__objc_data: 0x9ce0
-  __DATA.__objc_ivar: 0x1030
+  __AUTH.__objc_data: 0x9d30
+  __DATA.__objc_ivar: 0x103c
   __DATA.__data: 0x550
   __DATA.__bss: 0x2a0
   __DATA.__common: 0x8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3338
-  Symbols:   9248
-  CStrings:  2286
+  Functions: 3349
+  Symbols:   9277
+  CStrings:  2296
 
Symbols:
+ +[EWSAccountAudiencePolicy administratorMessagingAppliesToAudience:]
+ +[EWSAccountAudiencePolicy audienceForTenantID:]
+ +[EWSAccountAudiencePolicy tokenForAudience:]
+ +[ExchangeOAuthClient audienceForAccount:]
+ +[ExchangeOAuthClient stampEnterpriseOnAccount:ifVerifiedBy:]
+ +[ExchangeOAuthTokenRefreshResponse summaryOfErrorCodes:]
+ -[EWSRetirementAlertAccountSnapshot audience]
+ -[EWSRetirementAlertAccountSnapshot initWithIdentifier:emailAddress:displayName:inAccountStore:managed:graphCapable:audience:]
+ -[ExchangeOAuthTokenRefreshResponse errorCodesSummary]
+ -[ExchangeOAuthTokenRefreshResponse graceVerdict]
+ -[ExchangeOAuthTokenRefreshResponse setGraceVerdict:]
+ -[JWTValidator tenantID]
+ GCC_except_table42
+ _OBJC_CLASS_$_EWSAccountAudiencePolicy
+ _OBJC_IVAR_$_EWSRetirementAlertAccountSnapshot._audience
+ _OBJC_IVAR_$_ExchangeOAuthTokenRefreshResponse._errorCodesSummary
+ _OBJC_IVAR_$_ExchangeOAuthTokenRefreshResponse._graceVerdict
+ _OBJC_METACLASS_$_EWSAccountAudiencePolicy
+ __OBJC_$_CLASS_METHODS_EWSAccountAudiencePolicy
+ __OBJC_CLASS_RO_$_EWSAccountAudiencePolicy
+ __OBJC_METACLASS_RO_$_EWSAccountAudiencePolicy
+ _kExchangeOAuthRefreshFailureCount
+ _kExchangeOAuthRefreshFirstFailureTime
+ _kExchangeVerifiedEnterpriseAccountKey
+ _objc_msgSend$administratorMessagingAppliesToAudience:
+ _objc_msgSend$audience
+ _objc_msgSend$audienceForTenantID:
+ _objc_msgSend$initWithUUIDString:
+ _objc_msgSend$summaryOfErrorCodes:
+ _objc_msgSend$tenantID
+ _objc_msgSend$tokenForAudience:
- -[EWSRetirementAlertAccountSnapshot initWithIdentifier:emailAddress:displayName:inAccountStore:managed:graphCapable:]
- GCC_except_table41
CStrings:
+ "%lu"
+ "Account %{public}@ is not being alerted proactively because it is not verified as organizational, audience %{public}@."
+ "ExchangeOAuthRefreshFailureCount"
+ "ExchangeOAuthRefreshFirstFailureTime"
+ "ExchangeVerifiedEnterpriseAccount"
+ "ProactiveAlertEnabled"
+ "error_codes"
+ "malformed"
+ "organizational"
+ "personal"
+ "unknown"
- "ProactiveEnabled"
```
