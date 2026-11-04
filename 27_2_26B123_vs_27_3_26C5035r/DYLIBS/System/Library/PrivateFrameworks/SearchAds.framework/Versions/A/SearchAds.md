## SearchAds

> `/System/Library/PrivateFrameworks/SearchAds.framework/Versions/A/SearchAds`

```diff

-557.2.14.0.0
-  __TEXT.__text: 0x10880
-  __TEXT.__objc_methlist: 0xea4
-  __TEXT.__const: 0x8c0
+557.3.10.0.0
+  __TEXT.__text: 0x11c78
+  __TEXT.__objc_methlist: 0xee4
+  __TEXT.__const: 0xae0
   __TEXT.__gcc_except_tab: 0x1f4
-  __TEXT.__cstring: 0xcdb
-  __TEXT.__oslogstring: 0xdb3
-  __TEXT.__constg_swiftt: 0x4b0
-  __TEXT.__swift5_typeref: 0x1ca
-  __TEXT.__swift5_reflstr: 0x100
-  __TEXT.__swift5_fieldmd: 0x250
+  __TEXT.__cstring: 0xd8b
+  __TEXT.__oslogstring: 0xc63
+  __TEXT.__constg_swiftt: 0x55c
+  __TEXT.__swift5_typeref: 0x252
+  __TEXT.__swift5_reflstr: 0x1f5
+  __TEXT.__swift5_fieldmd: 0x328
   __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift5_assocty: 0x30
-  __TEXT.__swift5_proto: 0x48
-  __TEXT.__swift5_types: 0x50
+  __TEXT.__swift5_proto: 0x6c
+  __TEXT.__swift5_types: 0x5c
+  __TEXT.__swift5_capture: 0x14
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x660
+  __TEXT.__unwind_info: 0x750
+  __TEXT.__eh_frame: 0x160
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x100
-  __DATA_CONST.__objc_classlist: 0xf0
+  __DATA_CONST.__const: 0x138
+  __DATA_CONST.__objc_classlist: 0x100
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xca8
+  __DATA_CONST.__objc_selrefs: 0xc40
   __DATA_CONST.__objc_superrefs: 0x68
-  __DATA_CONST.__got: 0x258
-  __AUTH_CONST.__const: 0x450
-  __AUTH_CONST.__cfstring: 0xe20
-  __AUTH_CONST.__objc_const: 0x2520
-  __AUTH_CONST.__auth_got: 0x558
-  __AUTH.__objc_data: 0x258
-  __AUTH.__data: 0x168
-  __DATA.__objc_ivar: 0x164
-  __DATA.__data: 0xe0
-  __DATA.__bss: 0x3a0
+  __DATA_CONST.__got: 0x2a0
+  __AUTH_CONST.__const: 0x508
+  __AUTH_CONST.__cfstring: 0xda0
+  __AUTH_CONST.__objc_const: 0x2710
+  __AUTH_CONST.__auth_got: 0x660
+  __AUTH.__objc_data: 0x418
+  __AUTH.__data: 0x1b8
+  __DATA.__objc_ivar: 0x160
+  __DATA.__data: 0x188
+  __DATA.__bss: 0x820
   __DATA_DIRTY.__objc_data: 0x5d8
   __DATA_DIRTY.__data: 0x718
   __DATA_DIRTY.__bss: 0x190

   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/_LocationEssentials.framework/Versions/A/_LocationEssentials
+  - /System/Library/PrivateFrameworks/APConfigurationSystem.framework/Versions/A/APConfigurationSystem
   - /System/Library/PrivateFrameworks/APFoundation.framework/Versions/A/APFoundation
   - /System/Library/PrivateFrameworks/AdCore.framework/Versions/A/AdCore
   - /System/Library/PrivateFrameworks/AdPlatformsCommon.framework/Versions/A/AdPlatformsCommon

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 562
-  Symbols:   207
-  CStrings:  214
+  Functions: 632
+  Symbols:   212
+  CStrings:  206
 
Symbols:
+ _OBJC_CLASS_$_APAnalytics
+ _OBJC_CLASS_$__TtC9SearchAds22ADClientSettingsConfig
+ _OBJC_CLASS_$__TtC9SearchAds28ADClientSettingsBaseSettings
+ _OBJC_METACLASS_$__TtC9SearchAds22ADClientSettingsConfig
+ _OBJC_METACLASS_$__TtC9SearchAds28ADClientSettingsBaseSettings
+ __swiftEmptyDictionarySingleton
+ _swift_allocBox
+ _swift_bridgeObjectRetain_n
+ _swift_deallocObject
+ _swift_retain
- _ADCopyDataFromKeychain
- _ADWriteDataToKeychain
- _OBJC_CLASS_$_ADClientSettingsRequest
- _OBJC_CLASS_$_ADClientSettingsResponse
- _swift_bridgeObjectRelease_n
CStrings:
+ "ADClientSettingsConfig: no config found in ConfigurationNode.json, falling back to default settings"
+ "ADClientSettingsConfig: retrieved config from ConfigurationNode.json"
+ "ClientSettingsConfigInit"
+ "SearchAds.ADClientSettingsBaseSettings"
+ "SearchAdsSettingsInit"
+ "[%@]: Returning:"
+ "didLoadConfig"
+ "durationMilliseconds"
+ "searchads.clientSettingsLoad"
- "ADClientSettingsKeychainKey"
- "Client Settings has not expired. (%f < %f)"
- "Client Settings is being forced to expire"
- "ClientSettingsForceExpire"
- "ClientSettingsRetrieval"
- "ClientSettingsServerRetrieval"
- "Current Client Settings: %@"
- "Error saving Client Settings to keychain: %d"
- "Received response for ADClientSettingsRequest: %@"
- "[%@]: ADClientSettingsRequest failed with error: %@."
- "[%@]: After applyClientSettings:"
- "[%@]: Properties at init:"
- "cacheHit"
- "reason=%{public}s enableTelemetry=YES"
- "serverError"
- "serverSuccess"
- "v32@?0@\"NSData\"8@\"NSURLResponse\"16@\"NSError\"24"
```
