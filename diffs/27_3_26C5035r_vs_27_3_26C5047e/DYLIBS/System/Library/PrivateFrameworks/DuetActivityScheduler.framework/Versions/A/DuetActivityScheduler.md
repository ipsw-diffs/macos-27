## DuetActivityScheduler

> `/System/Library/PrivateFrameworks/DuetActivityScheduler.framework/Versions/A/DuetActivityScheduler`

```diff

-2467.60.9.0.0
-  __TEXT.__text: 0x3e628
-  __TEXT.__objc_methlist: 0x4750
+2467.60.20.0.0
+  __TEXT.__text: 0x3ebe8
+  __TEXT.__objc_methlist: 0x47b0
   __TEXT.__const: 0x1f8
   __TEXT.__cstring: 0x3f85
-  __TEXT.__oslogstring: 0x2c89
-  __TEXT.__gcc_except_tab: 0x1454
-  __TEXT.__unwind_info: 0x15f8
+  __TEXT.__oslogstring: 0x2d05
+  __TEXT.__gcc_except_tab: 0x1464
+  __TEXT.__unwind_info: 0x1628
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2728
+  __DATA_CONST.__objc_selrefs: 0x2758
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x110
   __DATA_CONST.__objc_arraydata: 0xb0
   __DATA_CONST.__got: 0x300
-  __AUTH_CONST.__const: 0xea0
+  __AUTH_CONST.__const: 0xed0
   __AUTH_CONST.__cfstring: 0x5040
-  __AUTH_CONST.__objc_const: 0x7b90
+  __AUTH_CONST.__objc_const: 0x7bb0
   __AUTH_CONST.__objc_intobj: 0x228
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x50

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1640
-  Symbols:   3488
-  CStrings:  953
+  Functions: 1651
+  Symbols:   3499
+  CStrings:  956
 
Symbols:
+ -[_DASScheduler getAppUsagePriorities]
+ -[_DASScheduler submitRateLimitConfiguration:synchronously:]
+ -[_DASScheduler submitRateLimitConfigurationAsynchronously:]
+ -[_DASScheduler updateAppUsagePriorities:version:timestamp:completionHandler:]
+ GCC_except_table151
+ GCC_except_table154
+ GCC_except_table163
+ GCC_except_table164
+ GCC_except_table173
+ GCC_except_table208
+ GCC_except_table242
+ GCC_except_table245
+ GCC_except_table250
+ GCC_except_table253
+ GCC_except_table256
+ GCC_except_table259
+ GCC_except_table267
+ GCC_except_table272
+ GCC_except_table275
+ GCC_except_table283
+ GCC_except_table286
+ GCC_except_table289
+ GCC_except_table292
+ GCC_except_table295
+ GCC_except_table298
+ GCC_except_table301
+ GCC_except_table304
+ GCC_except_table307
+ GCC_except_table310
+ GCC_except_table313
+ GCC_except_table316
+ GCC_except_table319
+ GCC_except_table322
+ GCC_except_table325
+ GCC_except_table328
+ GCC_except_table331
+ GCC_except_table334
+ GCC_except_table337
+ GCC_except_table340
+ GCC_except_table343
+ GCC_except_table346
+ GCC_except_table349
+ GCC_except_table352
+ ___38-[_DASScheduler getAppUsagePriorities]_block_invoke
+ ___60-[_DASScheduler submitRateLimitConfiguration:synchronously:]_block_invoke
+ ___78-[_DASScheduler updateAppUsagePriorities:version:timestamp:completionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e20_v20?0B8"NSError"12l
+ _objc_msgSend$getAppUsagePrioritiesWithHandler:
+ _objc_msgSend$submitRateLimitConfiguration:synchronously:
+ _objc_msgSend$submitRateLimitConfigurationAsynchronously:
+ _objc_msgSend$updateAppUsagePriorities:version:timestamp:withHandler:
- GCC_except_table149
- GCC_except_table152
- GCC_except_table158
- GCC_except_table161
- GCC_except_table171
- GCC_except_table206
- GCC_except_table240
- GCC_except_table243
- GCC_except_table248
- GCC_except_table251
- GCC_except_table254
- GCC_except_table257
- GCC_except_table265
- GCC_except_table270
- GCC_except_table273
- GCC_except_table278
- GCC_except_table281
- GCC_except_table284
- GCC_except_table287
- GCC_except_table290
- GCC_except_table293
- GCC_except_table296
- GCC_except_table299
- GCC_except_table302
- GCC_except_table305
- GCC_except_table308
- GCC_except_table311
- GCC_except_table314
- GCC_except_table317
- GCC_except_table320
- GCC_except_table323
- GCC_except_table326
- GCC_except_table329
- GCC_except_table332
- GCC_except_table335
- GCC_except_table338
- GCC_except_table341
- GCC_except_table344
- ___46-[_DASScheduler submitRateLimitConfiguration:]_block_invoke
- _objc_msgSend$submitRateLimitConfiguration:
CStrings:
+ "Error getting app usage priorities: %@"
+ "updateAppUsagePriorities Failed: %@"
+ "updateAppUsagePriorities Failed: Server error %@"
```
