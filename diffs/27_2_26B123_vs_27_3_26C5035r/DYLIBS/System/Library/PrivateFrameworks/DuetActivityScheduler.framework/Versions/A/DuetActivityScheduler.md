## DuetActivityScheduler

> `/System/Library/PrivateFrameworks/DuetActivityScheduler.framework/Versions/A/DuetActivityScheduler`

```diff

-2467.40.49.0.0
-  __TEXT.__text: 0x3e1f0
-  __TEXT.__objc_methlist: 0x4720
+2467.60.9.0.0
+  __TEXT.__text: 0x3e628
+  __TEXT.__objc_methlist: 0x4750
   __TEXT.__const: 0x1f8
-  __TEXT.__cstring: 0x3f28
-  __TEXT.__oslogstring: 0x2c61
-  __TEXT.__gcc_except_tab: 0x1438
-  __TEXT.__unwind_info: 0x15d8
+  __TEXT.__cstring: 0x3f85
+  __TEXT.__oslogstring: 0x2c89
+  __TEXT.__gcc_except_tab: 0x1454
+  __TEXT.__unwind_info: 0x15f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2700
+  __DATA_CONST.__objc_selrefs: 0x2728
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x110
   __DATA_CONST.__objc_arraydata: 0xb0
   __DATA_CONST.__got: 0x300
   __AUTH_CONST.__const: 0xea0
-  __AUTH_CONST.__cfstring: 0x4f60
-  __AUTH_CONST.__objc_const: 0x7b58
+  __AUTH_CONST.__cfstring: 0x5040
+  __AUTH_CONST.__objc_const: 0x7b90
   __AUTH_CONST.__objc_intobj: 0x228
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x50

   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x5f0
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0x458
+  __DATA.__objc_ivar: 0x45c
   __DATA.__data: 0xd68
   __DATA.__bss: 0xb8
   __DATA.__common: 0x8

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1632
-  Symbols:   3478
-  CStrings:  945
+  Functions: 1640
+  Symbols:   3488
+  CStrings:  953
 
Symbols:
+ -[_DASActivity launchQoS]
+ -[_DASActivity setLaunchQoS:]
+ -[_DASScheduler carryLaunchQoSFromActivity:toActivity:]
+ -[_DASScheduler setDoItNowRuntimeBudget:groupType:percentAvailable:]
+ GCC_except_table149
+ GCC_except_table153
+ GCC_except_table158
+ GCC_except_table162
+ GCC_except_table171
+ GCC_except_table206
+ GCC_except_table240
+ GCC_except_table243
+ GCC_except_table248
+ GCC_except_table251
+ GCC_except_table254
+ GCC_except_table257
+ GCC_except_table265
+ GCC_except_table270
+ GCC_except_table273
+ GCC_except_table278
+ GCC_except_table281
+ GCC_except_table284
+ GCC_except_table287
+ GCC_except_table290
+ GCC_except_table293
+ GCC_except_table296
+ GCC_except_table299
+ GCC_except_table302
+ GCC_except_table305
+ GCC_except_table308
+ GCC_except_table311
+ GCC_except_table314
+ GCC_except_table317
+ GCC_except_table320
+ GCC_except_table323
+ GCC_except_table326
+ GCC_except_table329
+ GCC_except_table332
+ GCC_except_table335
+ GCC_except_table338
+ GCC_except_table341
+ GCC_except_table344
+ _OBJC_IVAR_$__DASActivity._launchQoS
+ __DASQoSClassName
+ ___68-[_DASScheduler setDoItNowRuntimeBudget:groupType:percentAvailable:]_block_invoke
+ _objc_msgSend$carryLaunchQoSFromActivity:toActivity:
+ _objc_msgSend$launchQoS
+ _objc_msgSend$setDoItNowRuntimeBudget:groupType:percentAvailable:handler:
+ _objc_msgSend$setLaunchQoS:
- GCC_except_table126
- GCC_except_table147
- GCC_except_table151
- GCC_except_table157
- GCC_except_table159
- GCC_except_table170
- GCC_except_table205
- GCC_except_table239
- GCC_except_table242
- GCC_except_table247
- GCC_except_table250
- GCC_except_table253
- GCC_except_table256
- GCC_except_table264
- GCC_except_table269
- GCC_except_table272
- GCC_except_table277
- GCC_except_table280
- GCC_except_table283
- GCC_except_table286
- GCC_except_table289
- GCC_except_table292
- GCC_except_table295
- GCC_except_table298
- GCC_except_table301
- GCC_except_table304
- GCC_except_table307
- GCC_except_table310
- GCC_except_table313
- GCC_except_table316
- GCC_except_table319
- GCC_except_table322
- GCC_except_table325
- GCC_except_table328
- GCC_except_table331
- GCC_except_table334
- GCC_except_table337
- GCC_except_table340
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT__DASActivitySchedulerIntrospectingServer
CStrings:
+ ", Launch QoS: %@"
+ "Error setting runtime budget for %@: %@"
+ "QoS %u"
+ "QoS Downgrade,"
+ "Unspecified"
+ "User Initiated"
+ "User Interactive"
+ "launchQoS"
```
