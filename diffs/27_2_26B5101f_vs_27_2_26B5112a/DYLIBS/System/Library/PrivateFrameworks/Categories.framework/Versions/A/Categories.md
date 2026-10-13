## Categories

> `/System/Library/PrivateFrameworks/Categories.framework/Versions/A/Categories`

```diff

-58.1.5.0.0
-  __TEXT.__text: 0xbe14
-  __TEXT.__objc_methlist: 0x84c
+58.1.7.1.0
+  __TEXT.__text: 0xc27c
+  __TEXT.__objc_methlist: 0x89c
   __TEXT.__const: 0xc0
   __TEXT.__gcc_except_tab: 0x3f0
-  __TEXT.__cstring: 0x2fe7
-  __TEXT.__oslogstring: 0x6bb
-  __TEXT.__unwind_info: 0x4c0
+  __TEXT.__cstring: 0x3297
+  __TEXT.__oslogstring: 0x6c7
+  __TEXT.__unwind_info: 0x4d0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x40
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x738
+  __DATA_CONST.__objc_selrefs: 0x770
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x28
-  __DATA_CONST.__objc_arraydata: 0xb88
+  __DATA_CONST.__objc_arraydata: 0xc18
   __DATA_CONST.__got: 0xf0
   __AUTH_CONST.__const: 0x820
-  __AUTH_CONST.__cfstring: 0x3860
-  __AUTH_CONST.__objc_const: 0xca0
-  __AUTH_CONST.__objc_intobj: 0xa8
+  __AUTH_CONST.__cfstring: 0x3b20
+  __AUTH_CONST.__objc_const: 0xcc8
+  __AUTH_CONST.__objc_intobj: 0xc0
   __AUTH_CONST.__objc_arrayobj: 0x9f0
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0

   - /System/Library/PrivateFrameworks/ContextKit.framework/Versions/A/ContextKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 251
-  Symbols:   702
-  CStrings:  517
+  Functions: 257
+  Symbols:   714
+  CStrings:  539
 
Symbols:
+ +[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:origin:withCompletionHandler:]
+ +[CTCategory _lookupAppStoreUsing:platform:origin:withCompletionHandler:]
+ +[CTCategory _shouldExcludeBundleIdentifierFromCategoryLookup:]
+ +[CTCategory categoryForBundleIdentifiers:platform:targetUserIsU13:origin:withCompletionHandler:]
+ +[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]
+ GCC_except_table122
+ GCC_except_table39
+ GCC_except_table54
+ GCC_except_table72
+ GCC_except_table73
+ GCC_except_table93
+ __103+[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:origin:withCompletionHandler:]_block_invoke
+ __105+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]_block_invoke
+ __105+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]_block_invoke_2
+ __73+[CTCategory _lookupAppStoreUsing:platform:origin:withCompletionHandler:]_block_invoke
+ ___103+[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:origin:withCompletionHandler:]_block_invoke
+ ___105+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]_block_invoke
+ ___105+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]_block_invoke_2
+ ___73+[CTCategory _lookupAppStoreUsing:platform:origin:withCompletionHandler:]_block_invoke
+ ___73+[CTCategory _lookupAppStoreUsing:platform:origin:withCompletionHandler:]_block_invoke_2
+ ___block_descriptor_64_e8_32s40s48bs_e5_v8?0l
+ ___block_descriptor_96_e8_32s40s48bs56r64r72r_e34_v24?0"NSDictionary"8"NSError"16l
+ _objc_msgSend$_bundleCategoriesLookupResultsForBundleIdentifiers:platform:origin:withCompletionHandler:
+ _objc_msgSend$_lookupAppStoreUsing:platform:origin:withCompletionHandler:
+ _objc_msgSend$_shouldExcludeBundleIdentifierFromCategoryLookup:
+ _objc_msgSend$appStoreCategoriesForBundleIDs:platform:origin:replyHandler:
+ _objc_msgSend$categoryForBundleIdentifiers:platform:targetUserIsU13:origin:withCompletionHandler:
+ _objc_msgSend$categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:
+ _objc_msgSend$containsString:
+ _objc_msgSend$initWithIdentifier:webDomains:bundleIdentifier:
- GCC_except_table116
- GCC_except_table35
- GCC_except_table62
- GCC_except_table68
- GCC_except_table88
- __66+[CTCategory _lookupAppStoreUsing:platform:withCompletionHandler:]_block_invoke
- __96+[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:withCompletionHandler:]_block_invoke
- __98+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]_block_invoke
- ___66+[CTCategory _lookupAppStoreUsing:platform:withCompletionHandler:]_block_invoke
- ___66+[CTCategory _lookupAppStoreUsing:platform:withCompletionHandler:]_block_invoke_2
- ___96+[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:withCompletionHandler:]_block_invoke
- ___98+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]_block_invoke
- ___98+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48bs_e5_v8?0l
- ___block_descriptor_88_e8_32s40s48bs56r64r72r_e34_v24?0"NSDictionary"8"NSError"16l
- _objc_msgSend$_bundleCategoriesLookupResultsForBundleIdentifiers:platform:withCompletionHandler:
- _objc_msgSend$_lookupAppStoreUsing:platform:withCompletionHandler:
- _objc_msgSend$appStoreCategoriesForBundleIDs:platform:replyHandler:
CStrings:
+ "SB"
+ "_lookupAppStoreUsing %@ origin: %ld"
+ "com.apple.control-center"
+ "com.apple.sharing."
+ "com.apple.springboard."
+ "homeaccessory"
+ "homeaccessory://com.apple.CalendarPebble"
+ "homeaccessory://com.apple.Home"
+ "homeaccessory://com.apple.MobileAddressBook"
+ "homeaccessory://com.apple.MobileSMS"
+ "homeaccessory://com.apple.Music"
+ "homeaccessory://com.apple.PebbleSettingsApp"
+ "homeaccessory://com.apple.facetime"
+ "homeaccessory://com.apple.findmy"
+ "homeaccessory://com.apple.iBooks"
+ "homeaccessory://com.apple.mobilesafari"
+ "homeaccessory://com.apple.mobiletimer"
+ "homeaccessory://com.apple.news"
+ "homeaccessory://com.apple.podcasts"
+ "homeaccessory://com.apple.reminders"
+ "homeaccessory://com.apple.stocks"
+ "homeaccessory://com.apple.tv"
+ "homeaccessory://com.apple.weather"
- "_lookupAppStoreUsing %@"
```
