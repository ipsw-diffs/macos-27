## SafariSharedUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/SafariSharedUI.framework/Versions/A/SafariSharedUI`

```diff

-625.2.7.1.0
-  __TEXT.__text: 0x1fb9c8
-  __TEXT.__objc_methlist: 0xa14c
-  __TEXT.__const: 0x42978
-  __TEXT.__gcc_except_tab: 0x9264
-  __TEXT.__cstring: 0x1feb5
-  __TEXT.__oslogstring: 0x9729
+625.2.8.11.6
+  __TEXT.__text: 0x1fc8dc
+  __TEXT.__objc_methlist: 0xa164
+  __TEXT.__const: 0x42988
+  __TEXT.__gcc_except_tab: 0x9424
+  __TEXT.__cstring: 0x1fef5
+  __TEXT.__oslogstring: 0x9869
   __TEXT.__ustring: 0x1024
   __TEXT.__dlopen_cstrs: 0x2bc
   __TEXT.__swift5_typeref: 0x5eea

   __TEXT.__swift_as_ret: 0x590
   __TEXT.__swift_as_cont: 0xb94
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0xc010
+  __TEXT.__unwind_info: 0xc090
   __TEXT.__eh_frame: 0xe928
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x5e58
+  __DATA_CONST.__const: 0x5e78
   __DATA_CONST.__objc_classlist: 0x648
   __DATA_CONST.__objc_catlist: 0x128
   __DATA_CONST.__objc_protolist: 0x258
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x71d0
+  __DATA_CONST.__objc_selrefs: 0x7208
   __DATA_CONST.__objc_protorefs: 0x80
   __DATA_CONST.__objc_superrefs: 0x3c0
-  __DATA_CONST.__objc_arraydata: 0x1a08
-  __DATA_CONST.__got: 0x1948
-  __AUTH_CONST.__const: 0x9f08
-  __AUTH_CONST.__cfstring: 0xe140
-  __AUTH_CONST.__objc_const: 0x142c8
+  __DATA_CONST.__objc_arraydata: 0x1a18
+  __DATA_CONST.__got: 0x1998
+  __AUTH_CONST.__const: 0x9f48
+  __AUTH_CONST.__cfstring: 0xe160
+  __AUTH_CONST.__objc_const: 0x142e8
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x5a0
   __AUTH_CONST.__objc_doubleobj: 0x50
-  __AUTH_CONST.__objc_arrayobj: 0x780
+  __AUTH_CONST.__objc_arrayobj: 0x798
   __AUTH_CONST.__objc_dictobj: 0x208
   __AUTH_CONST.__auth_got: 0x23d8
   __AUTH.__objc_data: 0x2058
   __AUTH.__data: 0x1f90
-  __DATA.__objc_ivar: 0xc10
-  __DATA.__data: 0x48d0
-  __DATA.__bss: 0xe4d0
+  __DATA.__objc_ivar: 0xc14
+  __DATA.__data: 0x4930
+  __DATA.__bss: 0xe4f0
   __DATA.__common: 0x160
   __DATA_DIRTY.__objc_data: 0x2298
   __DATA_DIRTY.__data: 0x168

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 10394
-  Symbols:   12859
-  CStrings:  3216
+  Functions: 10417
+  Symbols:   12883
+  CStrings:  3224
 
Symbols:
+ -[WBSSearchEngineBannerActivityTracker _pageLoadSourceForWebView:]
+ -[WBSSearchEngineBannerActivityTracker notePageLoadSource:inWebView:]
+ -[WBSSearchEngineBannerActivityTracker reportBannerAppearanceWithCategory:signedIn:pageLoadSource:]
+ OBJC_IVAR_$_WBSSearchEngineBannerActivityTracker._pageLoadSourcesByWebView
+ _NSLocaleCountryCode
+ _NSLocaleLanguageCode
+ _NSLocaleScriptCode
+ _ZL52countryCodeIsExcludedFromSearchEngineBannerAnalyticsP8NSString
+ _ZL52searchEngineBannerAnalyticsExcludedLocaleIdentifiersv
+ __ZL26normalizedLocaleIdentifierP8NSString
+ __ZL40searchEngineBannerAnalyticsAreSuppressedv
+ __ZL52countryCodeIsExcludedFromSearchEngineBannerAnalyticsP8NSString
+ __ZL52searchEngineBannerAnalyticsExcludedLocaleIdentifiersv
+ __ZZL47searchEngineBannerAnalyticsExcludedCountryCodesvE12countryCodes
+ __ZZL47searchEngineBannerAnalyticsExcludedCountryCodesvE4once
+ __ZZL52searchEngineBannerAnalyticsExcludedLocaleIdentifiersvE17localeIdentifiers
+ __ZZL52searchEngineBannerAnalyticsExcludedLocaleIdentifiersvE4once
+ ____ZL47searchEngineBannerAnalyticsExcludedCountryCodesv_block_invoke
+ ____ZL52searchEngineBannerAnalyticsExcludedLocaleIdentifiersv_block_invoke
+ ___block_descriptor_64_ea8_32s40s_e17_v16?0"NSArray"8ls32l8s40l8
+ _objc_msgSend$_pageLoadSourceForWebView:
+ _objc_msgSend$componentsFromLocaleIdentifier:
+ _objc_msgSend$didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:pageLoadSource:
+ _objc_msgSend$localeIdentifierFromComponents:
+ _objc_msgSend$regionCode
+ _objc_msgSend$reportBannerAppearanceWithCategory:signedIn:pageLoadSource:
+ _objc_msgSend$safari_countryCodeForCountrySetInMacBuddy
+ _objc_msgSend$uppercaseString
- -[WBSSearchEngineBannerActivityTracker reportBannerAppearanceWithCategory:signedIn:]
- ___block_descriptor_56_ea8_32s40s_e17_v16?0"NSArray"8ls32l8s40l8
- _objc_msgSend$didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:
- _objc_msgSend$reportBannerAppearanceWithCategory:signedIn:
CStrings:
+ "Search engine banner accepted; not reporting because analytics are suppressed in this region"
+ "Search engine banner appeared (category: %{public}s, signed in: %{public}s, page load source: %{public}s)"
+ "Search engine banner appeared; not reporting because analytics are suppressed in this region"
+ "Search engine banner dismissed; not reporting because analytics are suppressed in this region"
+ "bookmark"
+ "ko_KR"
+ "manual navigation"
+ "smart search field"
+ "spotlight"
- "Search engine banner appeared (category: %{public}s, signed in: %{public}s)"
```
