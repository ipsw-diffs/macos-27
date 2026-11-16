## AppPredictionClient

> `/System/Library/PrivateFrameworks/AppPredictionClient.framework/Versions/A/AppPredictionClient`

```diff

-678.2.1.0.3
-  __TEXT.__text: 0x1a0424
-  __TEXT.__objc_methlist: 0x18dec
+678.2.6.0.1
+  __TEXT.__text: 0x1a12f0
+  __TEXT.__objc_methlist: 0x18e64
   __TEXT.__const: 0x718
-  __TEXT.__cstring: 0x1c88f
-  __TEXT.__oslogstring: 0x17ee6
+  __TEXT.__cstring: 0x1cb37
+  __TEXT.__oslogstring: 0x17f26
   __TEXT.__gcc_except_tab: 0x1d14
   __TEXT.__dlopen_cstrs: 0x2cc
   __TEXT.__ustring: 0x18a
-  __TEXT.__unwind_info: 0x8580
+  __TEXT.__unwind_info: 0x85a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x240
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa1a0
+  __DATA_CONST.__objc_selrefs: 0xa1d0
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0xbf8
   __DATA_CONST.__objc_arraydata: 0xb30
   __DATA_CONST.__got: 0x16e8
-  __AUTH_CONST.__const: 0x6650
-  __AUTH_CONST.__cfstring: 0x156c0
-  __AUTH_CONST.__objc_const: 0x45140
+  __AUTH_CONST.__const: 0x6680
+  __AUTH_CONST.__cfstring: 0x15780
+  __AUTH_CONST.__objc_const: 0x451e8
   __AUTH_CONST.__objc_intobj: 0xa98
   __AUTH_CONST.__objc_arrayobj: 0x6d8
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH_CONST.__auth_got: 0x690
   __AUTH.__objc_data: 0x3430
-  __DATA.__objc_ivar: 0x1cd0
+  __DATA.__objc_ivar: 0x1cd4
   __DATA.__data: 0x1b00
   __DATA.__bss: 0x320
   __DATA_DIRTY.__objc_data: 0x55f0

   - /usr/lib/libarchive.2.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 10999
-  Symbols:   20409
-  CStrings:  4882
+  Functions: 11013
+  Symbols:   20426
+  CStrings:  4896
 
Symbols:
+ +[ATXApplicationRecord isStoreDownloadInstallTypeForBundle:]
+ +[ATXDefaultHomeScreenItemManager _widgetIdentifiersInDenyListWithKey:]
+ -[ATXNotificationCategorizationClient collectEngagementMetricsForNotificationUUIDs:completion:]
+ -[ATXNotificationCategorizationClient collectNotificationFeedbackContentWithCompletion:]
+ -[ATXNotificationCategorizationClient deleteNotificationFeedbackContentWithCompletion:]
+ -[ATXPosterDescriptorGalleryOptions setTimeStyle:]
+ -[ATXPosterDescriptorGalleryOptions timeStyle]
+ _OBJC_IVAR_$_ATXPosterDescriptorGalleryOptions._timeStyle
+ ___87-[ATXNotificationCategorizationClient deleteNotificationFeedbackContentWithCompletion:]_block_invoke
+ ___88-[ATXNotificationCategorizationClient collectNotificationFeedbackContentWithCompletion:]_block_invoke
+ ___95-[ATXNotificationCategorizationClient collectEngagementMetricsForNotificationUUIDs:completion:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e28_v24?0"NSData"8"NSError"16l
+ _objc_msgSend$_widgetIdentifiersInDenyListWithKey:
+ _objc_msgSend$collectEngagementMetricsForNotificationUUIDs:completion:
+ _objc_msgSend$collectNotificationFeedbackContentWithCompletion:
+ _objc_msgSend$deleteNotificationFeedbackContentWithCompletion:
+ _objc_msgSend$timeStyle
CStrings:
+ "-[ATXNotificationCategorizationClient collectEngagementMetricsForNotificationUUIDs:completion:]"
+ "-[ATXNotificationCategorizationClient collectEngagementMetricsForNotificationUUIDs:completion:]_block_invoke"
+ "-[ATXNotificationCategorizationClient collectNotificationFeedbackContentWithCompletion:]"
+ "-[ATXNotificationCategorizationClient collectNotificationFeedbackContentWithCompletion:]_block_invoke"
+ "-[ATXNotificationCategorizationClient deleteNotificationFeedbackContentWithCompletion:]"
+ "-[ATXNotificationCategorizationClient deleteNotificationFeedbackContentWithCompletion:]_block_invoke"
+ "ADAPTIVE"
+ "COMPACT"
+ "Could not copy intent for action %@; returning the action as is"
+ "DEFAULT"
+ "denyListWidgets"
+ "timeStyle"
+ "timeStyle: %zd"
+ "v24@?0@\"NSData\"8@\"NSError\"16"
```
