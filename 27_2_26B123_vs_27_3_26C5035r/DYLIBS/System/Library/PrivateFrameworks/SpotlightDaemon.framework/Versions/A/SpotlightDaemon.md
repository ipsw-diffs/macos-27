## SpotlightDaemon

> `/System/Library/PrivateFrameworks/SpotlightDaemon.framework/Versions/A/SpotlightDaemon`

```diff

-2465.1.9.0.0
-  __TEXT.__text: 0xca7f4
-  __TEXT.__objc_methlist: 0x4d54
-  __TEXT.__const: 0x410
-  __TEXT.__cstring: 0x9d6f
-  __TEXT.__gcc_except_tab: 0x46a8
-  __TEXT.__oslogstring: 0xc426
-  __TEXT.__unwind_info: 0x3510
+2465.2.7.400.0
+  __TEXT.__text: 0xcbd18
+  __TEXT.__objc_methlist: 0x4e24
+  __TEXT.__const: 0x430
+  __TEXT.__cstring: 0x9e68
+  __TEXT.__gcc_except_tab: 0x46bc
+  __TEXT.__oslogstring: 0xc44e
+  __TEXT.__unwind_info: 0x3578
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x650
-  __DATA_CONST.__objc_classlist: 0x1d8
+  __DATA_CONST.__const: 0x678
+  __DATA_CONST.__objc_classlist: 0x1e0
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3dc0
+  __DATA_CONST.__objc_selrefs: 0x3e38
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x150
+  __DATA_CONST.__objc_superrefs: 0x158
   __DATA_CONST.__objc_arraydata: 0x2f0
-  __DATA_CONST.__got: 0xbf0
-  __AUTH_CONST.__const: 0x5988
-  __AUTH_CONST.__cfstring: 0x80a0
-  __AUTH_CONST.__objc_const: 0x64e8
+  __DATA_CONST.__got: 0xbf8
+  __AUTH_CONST.__const: 0x59e8
+  __AUTH_CONST.__cfstring: 0x81a0
+  __AUTH_CONST.__objc_const: 0x6620
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x360
   __AUTH_CONST.__objc_intobj: 0x210
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x1068
-  __AUTH.__objc_data: 0x2d0
-  __DATA.__objc_ivar: 0x54c
+  __AUTH_CONST.__auth_got: 0x1078
+  __AUTH.__objc_data: 0x320
+  __DATA.__objc_ivar: 0x560
   __DATA.__data: 0x3f0
-  __DATA.__bss: 0x1f0
+  __DATA.__bss: 0x1f8
   __DATA.__common: 0x4
   __DATA_DIRTY.__objc_data: 0xfa0
   __DATA_DIRTY.__data: 0x160
-  __DATA_DIRTY.__bss: 0x600
+  __DATA_DIRTY.__bss: 0x5f8
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 3476
-  Symbols:   6798
-  CStrings:  2640
+  Functions: 3507
+  Symbols:   6860
+  CStrings:  2650
 
Symbols:
+ -[MDSearchableIndexService _evaluateFileProviderContainerGroups:excludedBundleIDs:allowedBundleIDs:completionHandler:]
+ -[SPConcreteCoreSpotlightIndexer _closeIndexOnLockSuspendQueue]
+ -[SPConcreteCoreSpotlightIndexer _commitUpdatesUnlessSuspended:]
+ -[SPConcreteCoreSpotlightIndexer _openIndexOnLockSuspendQueue:shouldReindexAll:readOnly:forcePC:]
+ -[SPConcreteCoreSpotlightIndexer _resumeIndexOnLockSuspendQueue]
+ -[SPConcreteCoreSpotlightIndexer _test_isSuspending]
+ -[SPConcreteCoreSpotlightIndexer dispatchDeviceLockSuspendToGroup:]
+ -[SPConcreteCoreSpotlightIndexer lockSuspendQueue]
+ -[SPConcreteCoreSpotlightIndexer suspendIndexForDeviceLock:outstandingMaintenance:]
+ -[SPCoreSpotlightIndexer _finishLocalizedStringUsageTask:identifier:reporter:]
+ -[SPCoreSpotlightIndexer _sampleLocalizedStringUsageWithReporter:completion:]
+ -[SPLocalizedStringUsageReporter addCensus:]
+ -[SPLocalizedStringUsageReporter cancelFlag]
+ -[SPLocalizedStringUsageReporter cancel]
+ -[SPLocalizedStringUsageReporter censusCount]
+ -[SPLocalizedStringUsageReporter init]
+ -[SPLocalizedStringUsageReporter isCanceled]
+ -[SPLocalizedStringUsageReporter payload]
+ GCC_except_table1016
+ GCC_except_table1044
+ GCC_except_table1073
+ GCC_except_table1074
+ GCC_except_table1083
+ GCC_except_table1099
+ GCC_except_table1144
+ GCC_except_table1149
+ GCC_except_table1213
+ GCC_except_table1254
+ GCC_except_table1260
+ GCC_except_table1267
+ GCC_except_table1268
+ GCC_except_table1269
+ GCC_except_table1281
+ GCC_except_table1299
+ GCC_except_table1305
+ GCC_except_table1309
+ GCC_except_table1324
+ GCC_except_table1340
+ GCC_except_table1347
+ GCC_except_table1354
+ GCC_except_table1361
+ GCC_except_table1368
+ GCC_except_table1386
+ GCC_except_table1461
+ GCC_except_table1462
+ GCC_except_table1464
+ GCC_except_table1471
+ GCC_except_table1531
+ GCC_except_table1538
+ GCC_except_table378
+ GCC_except_table384
+ GCC_except_table390
+ GCC_except_table418
+ GCC_except_table428
+ GCC_except_table443
+ GCC_except_table479
+ GCC_except_table480
+ GCC_except_table484
+ GCC_except_table510
+ GCC_except_table547
+ GCC_except_table568
+ GCC_except_table569
+ GCC_except_table597
+ GCC_except_table624
+ GCC_except_table637
+ GCC_except_table640
+ GCC_except_table693
+ GCC_except_table707
+ GCC_except_table719
+ GCC_except_table749
+ GCC_except_table755
+ GCC_except_table770
+ GCC_except_table771
+ GCC_except_table783
+ GCC_except_table812
+ GCC_except_table838
+ GCC_except_table839
+ GCC_except_table840
+ GCC_except_table867
+ GCC_except_table933
+ GCC_except_table954
+ GCC_except_table976
+ GCC_except_table980
+ GCC_except_table984
+ _OBJC_CLASS_$_SPLocalizedStringUsageReporter
+ _OBJC_IVAR_$_SPConcreteCoreSpotlightIndexer._lockSuspendQueue
+ _OBJC_IVAR_$_SPConcreteCoreSpotlightIndexer._suspendsPending
+ _OBJC_IVAR_$_SPLocalizedStringUsageReporter._canceled
+ _OBJC_IVAR_$_SPLocalizedStringUsageReporter._censusCount
+ _OBJC_IVAR_$_SPLocalizedStringUsageReporter._lock
+ _OBJC_IVAR_$_SPLocalizedStringUsageReporter._totals
+ _OBJC_METACLASS_$_SPLocalizedStringUsageReporter
+ _OUTLINED_FUNCTION_45
+ _SPLocalizedStringUsageEventName
+ _SPLocalizedStringUsageLocalizedFieldCountKey
+ _SPLocalizedStringUsageLocalizedVariantCountKey
+ _SPLocalizedStringUsagePagesPerIndex
+ _SPLocalizedStringUsagePayload
+ _SPLocalizedStringUsageRegularFieldCountKey
+ _SPLocalizedStringUsageRoundedEstimate
+ _SPLocalizedStringUsageSampledPagesKey
+ _SPLocalizedStringUsageTotalsAddCensus
+ __OBJC_$_INSTANCE_METHODS_SPLocalizedStringUsageReporter
+ __OBJC_$_INSTANCE_VARIABLES_SPLocalizedStringUsageReporter
+ __OBJC_CLASS_RO_$_SPLocalizedStringUsageReporter
+ __OBJC_METACLASS_RO_$_SPLocalizedStringUsageReporter
+ __SISampleStringFieldCensus
+ ___118-[MDSearchableIndexService _evaluateFileProviderContainerGroups:excludedBundleIDs:allowedBundleIDs:completionHandler:]_block_invoke
+ ___30-[SPCoreSpotlightIndexer init]_block_invoke_6
+ ___44-[SPConcreteCoreSpotlightIndexer closeIndex]_block_invoke
+ ___64-[SPConcreteCoreSpotlightIndexer _resumeIndexOnLockSuspendQueue]_block_invoke
+ ___64-[SPConcreteCoreSpotlightIndexer _resumeIndexOnLockSuspendQueue]_block_invoke_2
+ ___67-[SPConcreteCoreSpotlightIndexer dispatchDeviceLockSuspendToGroup:]_block_invoke
+ ___77-[SPCoreSpotlightIndexer _sampleLocalizedStringUsageWithReporter:completion:]_block_invoke
+ ___77-[SPCoreSpotlightIndexer _sampleLocalizedStringUsageWithReporter:completion:]_block_invoke_2
+ ___78-[SPCoreSpotlightIndexer _finishLocalizedStringUsageTask:identifier:reporter:]_block_invoke
+ ___83-[SPConcreteCoreSpotlightIndexer suspendIndexForDeviceLock:outstandingMaintenance:]_block_invoke
+ ___83-[SPConcreteCoreSpotlightIndexer suspendIndexForDeviceLock:outstandingMaintenance:]_block_invoke_2
+ ___83-[SPConcreteCoreSpotlightIndexer suspendIndexForDeviceLock:outstandingMaintenance:]_block_invoke_3
+ ___97-[SPConcreteCoreSpotlightIndexer _openIndexOnLockSuspendQueue:shouldReindexAll:readOnly:forcePC:]_block_invoke
+ ___97-[SPConcreteCoreSpotlightIndexer _openIndexOnLockSuspendQueue:shouldReindexAll:readOnly:forcePC:]_block_invoke_2
+ ___97-[SPConcreteCoreSpotlightIndexer _openIndexOnLockSuspendQueue:shouldReindexAll:readOnly:forcePC:]_block_invoke_3
+ ___block_descriptor_48_e8_32s40s_e38_v16?0r^{SIStringFieldCensus=QQQQQQQ}8l
+ ___block_descriptor_59_e8_32s40s48r_e5_v8?0l
+ __openIndexOnLockSuspendQueue:shouldReindexAll:readOnly:forcePC:.onceToken
+ _objc_msgSend$_closeIndexOnLockSuspendQueue
+ _objc_msgSend$_commitUpdatesUnlessSuspended:
+ _objc_msgSend$_evaluateFileProviderContainerGroups:excludedBundleIDs:allowedBundleIDs:completionHandler:
+ _objc_msgSend$_finishLocalizedStringUsageTask:identifier:reporter:
+ _objc_msgSend$_openIndexOnLockSuspendQueue:shouldReindexAll:readOnly:forcePC:
+ _objc_msgSend$_resumeIndexOnLockSuspendQueue
+ _objc_msgSend$_sampleLocalizedStringUsageWithReporter:completion:
+ _objc_msgSend$addCensus:
+ _objc_msgSend$cancelFlag
+ _objc_msgSend$censusCount
+ _objc_msgSend$dispatchDeviceLockSuspendToGroup:
+ _objc_msgSend$fileProviderAllowedBundleIDs
+ _objc_msgSend$isCanceled
+ _objc_msgSend$lockSuspendQueue
+ _objc_msgSend$payload
+ _objc_msgSend$suspendIndexForDeviceLock:outstandingMaintenance:
+ _strchr
- -[MDSearchableIndexService _evaluateFileProviderContainerGroups:excludedBundleIDs:completionHandler:]
- -[SPConcreteCoreSpotlightIndexer suspendIndexForDeviceLock:]
- GCC_except_table1001
- GCC_except_table1024
- GCC_except_table1053
- GCC_except_table1054
- GCC_except_table1063
- GCC_except_table1079
- GCC_except_table1124
- GCC_except_table1129
- GCC_except_table1193
- GCC_except_table1234
- GCC_except_table1240
- GCC_except_table1241
- GCC_except_table1247
- GCC_except_table1248
- GCC_except_table1249
- GCC_except_table1259
- GCC_except_table1285
- GCC_except_table1289
- GCC_except_table1304
- GCC_except_table1320
- GCC_except_table1327
- GCC_except_table1334
- GCC_except_table1341
- GCC_except_table1348
- GCC_except_table1366
- GCC_except_table1441
- GCC_except_table1442
- GCC_except_table1444
- GCC_except_table1451
- GCC_except_table1511
- GCC_except_table1518
- GCC_except_table382
- GCC_except_table388
- GCC_except_table416
- GCC_except_table426
- GCC_except_table441
- GCC_except_table476
- GCC_except_table477
- GCC_except_table481
- GCC_except_table507
- GCC_except_table536
- GCC_except_table557
- GCC_except_table558
- GCC_except_table586
- GCC_except_table613
- GCC_except_table626
- GCC_except_table629
- GCC_except_table682
- GCC_except_table696
- GCC_except_table708
- GCC_except_table738
- GCC_except_table744
- GCC_except_table759
- GCC_except_table760
- GCC_except_table772
- GCC_except_table801
- GCC_except_table827
- GCC_except_table828
- GCC_except_table829
- GCC_except_table855
- GCC_except_table921
- GCC_except_table942
- GCC_except_table964
- GCC_except_table968
- GCC_except_table972
- _OBJC_IVAR_$_SPConcreteCoreSpotlightIndexer._suspending
- ___101-[MDSearchableIndexService _evaluateFileProviderContainerGroups:excludedBundleIDs:completionHandler:]_block_invoke
- ___45-[SPConcreteCoreSpotlightIndexer resumeIndex]_block_invoke_2
- ___60-[SPConcreteCoreSpotlightIndexer suspendIndexForDeviceLock:]_block_invoke
- ___60-[SPConcreteCoreSpotlightIndexer suspendIndexForDeviceLock:]_block_invoke_2
- ___60-[SPConcreteCoreSpotlightIndexer suspendIndexForDeviceLock:]_block_invoke_3
- ___78-[SPConcreteCoreSpotlightIndexer openIndex:shouldReindexAll:readOnly:forcePC:]_block_invoke_2
- ___78-[SPConcreteCoreSpotlightIndexer openIndex:shouldReindexAll:readOnly:forcePC:]_block_invoke_3
- _objc_msgSend$_evaluateFileProviderContainerGroups:excludedBundleIDs:completionHandler:
- _objc_msgSend$dirtyTransaction
- _objc_msgSend$setDirtyTransaction:
- _objc_msgSend$suspendIndexForDeviceLock:
- _openIndex:shouldReindexAll:readOnly:forcePC:.onceToken
CStrings:
+ "25F"
+ "Task %@ sampled %lu indexes, payload:%@"
+ "com.apple.searchd.reportLocalizedStringUsage"
+ "com.apple.spotlight.index.LocalizedStringUsage"
+ "com.apple.spotlight.lockSuspendQueue.%@"
+ "localizedFieldCount"
+ "localizedVariantCount"
+ "regularFieldCount"
+ "sampledPages"
+ "v16@?0r^{SIStringFieldCensus=QQQQQQQ}8"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf1"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xc1"
```
