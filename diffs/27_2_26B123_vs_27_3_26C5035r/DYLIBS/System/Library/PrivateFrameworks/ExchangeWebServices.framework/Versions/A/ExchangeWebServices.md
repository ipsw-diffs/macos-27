## ExchangeWebServices

> `/System/Library/PrivateFrameworks/ExchangeWebServices.framework/Versions/A/ExchangeWebServices`

```diff

-846.200.71.0.0
-  __TEXT.__text: 0x425e0
-  __TEXT.__objc_methlist: 0xb308
-  __TEXT.__const: 0x1a8
-  __TEXT.__cstring: 0xab43
-  __TEXT.__oslogstring: 0x12c9
+846.300.31.1.1
+  __TEXT.__text: 0x436d8
+  __TEXT.__objc_methlist: 0xb420
+  __TEXT.__const: 0x1b0
+  __TEXT.__cstring: 0xac50
+  __TEXT.__oslogstring: 0x13a9
   __TEXT.__gcc_except_tab: 0x5f0
-  __TEXT.__unwind_info: 0x1820
+  __TEXT.__unwind_info: 0x1870
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2628
-  __DATA_CONST.__objc_classlist: 0xfa0
+  __DATA_CONST.__const: 0x2650
+  __DATA_CONST.__objc_classlist: 0xfb0
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4080
+  __DATA_CONST.__objc_selrefs: 0x4108
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x458
-  __DATA_CONST.__objc_arraydata: 0x118
-  __DATA_CONST.__got: 0x10f8
-  __AUTH_CONST.__const: 0x760
-  __AUTH_CONST.__cfstring: 0x10aa0
-  __AUTH_CONST.__objc_const: 0x49f48
-  __AUTH_CONST.__objc_arrayobj: 0xa8
+  __DATA_CONST.__objc_arraydata: 0x110
+  __DATA_CONST.__got: 0x1100
+  __AUTH_CONST.__const: 0x7d0
+  __AUTH_CONST.__cfstring: 0x10c40
+  __AUTH_CONST.__objc_const: 0x4a448
+  __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_intobj: 0x90
   __AUTH_CONST.__auth_got: 0x340
-  __AUTH.__objc_data: 0x9c40
-  __DATA.__objc_ivar: 0x1028
+  __AUTH.__objc_data: 0x9ce0
+  __DATA.__objc_ivar: 0x1030
   __DATA.__data: 0x550
-  __DATA.__bss: 0x280
+  __DATA.__bss: 0x2a0
   __DATA.__common: 0x8
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3313
-  Symbols:   9189
-  CStrings:  2269
+  Functions: 3338
+  Symbols:   9248
+  CStrings:  2286
 
Symbols:
+ +[EWSGraphCutoverPolicy URLFromAccountPropertyValue:]
+ +[EWSGraphCutoverPolicy eligibilityForAccount:]
+ +[EWSGraphCutoverPolicy graphEndpointURLForAccount:]
+ +[EWSGraphCutoverPolicy hasLiveGraphEndpoint:]
+ +[EWSGraphCutoverPolicy tokenRefreshHostURLForAccount:]
+ +[EWSMailboxLocationProbe _serverLocationForLogFromData:]
+ +[EWSTimeZoneContextType definition]
+ +[ExchangeOAuthClient allGraphMigrationKeys]
+ +[ExchangeOAuthClient graphMigrationEnabled]
+ +[ExchangeOAuthClient graphUpgradeOfferOneShotVerificationFailureError]
+ +[ExchangeOAuthClient hasEverBeenEWSAccountWithExternalURLPresent:internalURLPresent:anyMigrationKeyPresent:]
+ +[ExchangeOAuthClient isArmedMigrationKeyValue:]
+ +[ExchangeOAuthClient isEligibleForGraphCutoverWithHasEWSHistory:allMigrationKeysArmed:hasGraphEndpoint:]
+ +[ExchangeOAuthTokenRequest loggableDescriptionForRequest:]
+ +[ExchangeOAuthTokenRequest loggableSummaryForError:]
+ -[EWSExchangeServiceBindingTask setTimeZoneContext:]
+ -[EWSExchangeServiceBindingTask timeZoneContext]
+ -[EWSTimeZoneContextType .cxx_destruct]
+ -[EWSTimeZoneContextType TimeZoneDefinition]
+ -[EWSTimeZoneContextType description]
+ -[EWSTimeZoneContextType setTimeZoneDefinition:]
+ _EWSLoggableRequestHeaderString
+ _EWSMailboxLocationProbeLog.log
+ _EWSMailboxLocationProbeLog.onceToken
+ _OBJC_CLASS_$_EWSGraphCutoverPolicy
+ _OBJC_CLASS_$_EWSTimeZoneContextType
+ _OBJC_IVAR_$_EWSExchangeServiceBindingTask._timeZoneContext
+ _OBJC_IVAR_$_EWSTimeZoneContextType._TimeZoneDefinition
+ _OBJC_METACLASS_$_EWSGraphCutoverPolicy
+ _OBJC_METACLASS_$_EWSTimeZoneContextType
+ __OBJC_$_CLASS_METHODS_EWSGraphCutoverPolicy
+ __OBJC_$_CLASS_METHODS_EWSTimeZoneContextType
+ __OBJC_$_INSTANCE_METHODS_EWSTimeZoneContextType
+ __OBJC_$_INSTANCE_VARIABLES_EWSTimeZoneContextType
+ __OBJC_$_PROP_LIST_EWSTimeZoneContextType
+ __OBJC_CLASS_PROTOCOLS_$_EWSTimeZoneContextType
+ __OBJC_CLASS_RO_$_EWSGraphCutoverPolicy
+ __OBJC_CLASS_RO_$_EWSTimeZoneContextType
+ __OBJC_METACLASS_RO_$_EWSGraphCutoverPolicy
+ __OBJC_METACLASS_RO_$_EWSTimeZoneContextType
+ ___44+[ExchangeOAuthClient allGraphMigrationKeys]_block_invoke
+ ___EWSLoggableRequestHeaderString_block_invoke
+ ___EWSMailboxLocationProbeLog_block_invoke
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSString"8"NSString"16^B24l
+ _allGraphMigrationKeys.keys
+ _allGraphMigrationKeys.onceToken
+ _kExchangeAutodiscoverADFSIssuer
+ _kExchangeGraphUpgradeOfferLastShownDate
+ _kExchangeGraphUpgradeOfferPendingKey
+ _kGraphMigrationDefaultsKey
+ _kGraphUpgradeOfferReshowIntervalDefaultsKey
+ _objc_msgSend$URLFromAccountPropertyValue:
+ _objc_msgSend$_serverLocationForLogFromData:
+ _objc_msgSend$allGraphMigrationKeys
+ _objc_msgSend$graphEndpointURLForAccount:
+ _objc_msgSend$graphMigrationEnabled
+ _objc_msgSend$hasEverBeenEWSAccountWithExternalURLPresent:internalURLPresent:anyMigrationKeyPresent:
+ _objc_msgSend$hasLiveGraphEndpoint:
+ _objc_msgSend$isArmedMigrationKeyValue:
+ _objc_msgSend$isEligibleForGraphCutoverWithHasEWSHistory:allMigrationKeysArmed:hasGraphEndpoint:
+ _objc_msgSend$setTimeZoneDefinition:
+ _objc_msgSend$timeZoneContext
- +[ExchangeOAuthClient _defaultOIDCScopesForGraphDomain]
- ___EWSLogURLRequest_block_invoke
- _objc_msgSend$_defaultOIDCScopesForGraphDomain
CStrings:
+ "%@ %@://%@%@"
+ "%@ %ld"
+ "%{public}@ TimeZoneContext %{public}@ omitted: schema %{public}@ does not support it"
+ "(no URL)"
+ "<redacted>"
+ "ADFS"
+ "ExchangeGraphUpgradeOfferLastShownDate"
+ "ExchangeGraphUpgradeOfferPending"
+ "GraphMigration"
+ "GraphUpgradeOfferReshowInterval"
+ "MailboxLocationProbe"
+ "People.Read"
+ "Proxy-Authorization"
+ "ServerLocation probe: status=%ld location=%ld serverLocation=%{public}@ requestID=%{public}@ errorDomain=%{public}@ errorCode=%ld error=%@"
+ "TimeZoneContext"
+ "TimeZoneDefinition"
+ "graphMigration"
+ "none"
+ "request-id"
- "email"
- "profile"
```
