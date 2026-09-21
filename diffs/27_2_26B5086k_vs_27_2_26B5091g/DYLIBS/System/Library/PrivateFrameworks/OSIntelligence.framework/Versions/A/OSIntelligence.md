## OSIntelligence

> `/System/Library/PrivateFrameworks/OSIntelligence.framework/Versions/A/OSIntelligence`

```diff

-288.40.3.0.0
-  __TEXT.__text: 0x1a930
-  __TEXT.__objc_methlist: 0x2458
-  __TEXT.__const: 0x198
-  __TEXT.__cstring: 0x1994
-  __TEXT.__oslogstring: 0x22e8
+288.40.6.0.0
+  __TEXT.__text: 0x1b8e4
+  __TEXT.__objc_methlist: 0x24a8
+  __TEXT.__const: 0x1a0
+  __TEXT.__cstring: 0x1b7f
+  __TEXT.__oslogstring: 0x2357
   __TEXT.__gcc_except_tab: 0x6a0
-  __TEXT.__unwind_info: 0xd90
+  __TEXT.__unwind_info: 0xdc8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x198
+  __DATA_CONST.__const: 0x1e8
   __DATA_CONST.__objc_classlist: 0xd8
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1318
+  __DATA_CONST.__objc_selrefs: 0x1358
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0xa8
   __DATA_CONST.__got: 0x1b0
-  __AUTH_CONST.__const: 0x1040
-  __AUTH_CONST.__cfstring: 0x16c0
-  __AUTH_CONST.__objc_const: 0x3348
+  __AUTH_CONST.__const: 0x1090
+  __AUTH_CONST.__cfstring: 0x18a0
+  __AUTH_CONST.__objc_const: 0x3378
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x140
-  __DATA.__objc_ivar: 0x21c
+  __DATA.__objc_ivar: 0x220
   __DATA.__data: 0x4e0
-  __DATA.__bss: 0x8
+  __DATA.__bss: 0x18
   __DATA_DIRTY.__objc_data: 0x730
   __DATA_DIRTY.__bss: 0xa0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1001
-  Symbols:   1926
-  CStrings:  425
+  Functions: 1016
+  Symbols:   1947
+  CStrings:  443
 
Symbols:
+ +[_OSIBLMAnalyticsHandler allNotificationAnalyticsKeys]
+ +[_OSIBLMAnalyticsHandler analyticsKeyForNotificationDecision:]
+ -[_OSIBLMAnalyticsHandler historicalNotificationDataForDate:]
+ -[_OSIBLMAnalyticsHandler recordNotificationDecision:]
+ -[_OSIBLMAnalyticsHandler windowedNotificationSumsEndingDate:days:suffix:]
+ -[_OSIBLManager analyticsHandler]
+ -[_OSIBLManager setAnalyticsHandler:]
+ GCC_except_table46
+ OBJC_IVAR_$__OSIBLManager._analyticsHandler
+ ___54-[_OSIBLMAnalyticsHandler recordNotificationDecision:]_block_invoke
+ ___55+[_OSIBLMAnalyticsHandler allNotificationAnalyticsKeys]_block_invoke
+ ___61-[_OSIBLMAnalyticsHandler historicalNotificationDataForDate:]_block_invoke
+ ___74-[_OSIBLMAnalyticsHandler windowedNotificationSumsEndingDate:days:suffix:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48s56s_e39_v32?0"NSString"8"NSDictionary"16^B24l
+ _objc_msgSend$allNotificationAnalyticsKeys
+ _objc_msgSend$analyticsKeyForNotificationDecision:
+ _objc_msgSend$historicalNotificationDataForDate:
+ _objc_msgSend$stringByAppendingString:
+ _objc_msgSend$windowedNotificationSumsEndingDate:days:suffix:
+ allNotificationAnalyticsKeys.keys
+ allNotificationAnalyticsKeys.onceToken
CStrings:
+ "IBLMNotificationDecision"
+ "Last30Days"
+ "Last7Days"
+ "NotificationDecision"
+ "Recorded notification decision %{public}@ for %@ (now %ld)"
+ "Unsupported notification decision for analytics %ld"
+ "\\\"c"
+ "com.apple.osintelligence.iblm.recordNotificationDecision"
+ "historicalIBLMNotificationCounts"
+ "notificationEvaluationCount"
+ "notificationSuppressedByBackstop"
+ "notificationSuppressedByCooldown"
+ "notificationSuppressedByDisabled"
+ "notificationSuppressedByInsufficientData"
+ "notificationSuppressedByNotUnusual"
+ "notificationSuppressedBySlotOutOfRange"
+ "notificationSuppressedByStartHour"
+ "onboardingNotificationCount"
+ "unusualDrainNotificationCount"
- "[\"c"
```
