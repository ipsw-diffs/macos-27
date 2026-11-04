## iCloudDriveCore

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/Versions/A/iCloudDriveCore`

```diff

-5168.40.162.0.0
-  __TEXT.__text: 0x33e428
-  __TEXT.__objc_methlist: 0x1c3c4
+5168.60.14.0.0
+  __TEXT.__text: 0x33f118
+  __TEXT.__objc_methlist: 0x1c3cc
   __TEXT.__const: 0x4f8
-  __TEXT.__cstring: 0x85267
-  __TEXT.__oslogstring: 0x40031
-  __TEXT.__gcc_except_tab: 0x17f94
+  __TEXT.__cstring: 0x852e4
+  __TEXT.__oslogstring: 0x400c5
+  __TEXT.__gcc_except_tab: 0x180f0
   __TEXT.__ustring: 0x36
-  __TEXT.__unwind_info: 0xd940
+  __TEXT.__unwind_info: 0xd958
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0xd8
   __DATA_CONST.__objc_protolist: 0x2b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf460
+  __DATA_CONST.__objc_selrefs: 0xf480
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x960
   __DATA_CONST.__objc_arraydata: 0xfd8
-  __DATA_CONST.__got: 0x1810
-  __AUTH_CONST.__const: 0xbf98
+  __DATA_CONST.__got: 0x1818
+  __AUTH_CONST.__const: 0xbfc8
   __AUTH_CONST.__cfstring: 0x24100
   __AUTH_CONST.__objc_const: 0x422f8
   __AUTH_CONST.__objc_intobj: 0xc30

   - /usr/lib/libprequelite.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 14626
-  Symbols:   24842
-  CStrings:  12407
+  Functions: 14630
+  Symbols:   24860
+  CStrings:  12410
 
Symbols:
+ +[AppTelemetryTimeSeriesEvent(BRCAdditions) newNonSandboxedIPCAccessEventForCheck:bundleID:selector:]
+ -[BRCAccountSession(IPCTelemetry) postNonSandboxedIPCCheckTelemetry:bundleID:selector:]
+ -[BRCClientZone _loadPersistedStateFromPlist:]
+ -[BRCXPCRegularIPCsClient(FPFSAdditions) getDefaultAppContainerItemForContainerID:localBundleDeclaresDocumentScopePublic:recreateDocumentsIfNeeded:reply:]
+ GCC_except_table144
+ GCC_except_table158
+ GCC_except_table164
+ GCC_except_table167
+ GCC_except_table197
+ GCC_except_table239
+ GCC_except_table257
+ GCC_except_table276
+ GCC_except_table284
+ GCC_except_table297
+ GCC_except_table299
+ GCC_except_table311
+ GCC_except_table317
+ GCC_except_table326
+ GCC_except_table330
+ GCC_except_table332
+ GCC_except_table334
+ GCC_except_table336
+ GCC_except_table338
+ GCC_except_table340
+ GCC_except_table349
+ GCC_except_table350
+ GCC_except_table353
+ GCC_except_table356
+ GCC_except_table366
+ GCC_except_table380
+ GCC_except_table390
+ GCC_except_table407
+ GCC_except_table414
+ GCC_except_table418
+ GCC_except_table420
+ GCC_except_table424
+ GCC_except_table426
+ GCC_except_table431
+ GCC_except_table433
+ GCC_except_table438
+ GCC_except_table444
+ GCC_except_table449
+ GCC_except_table457
+ GCC_except_table467
+ GCC_except_table472
+ GCC_except_table474
+ GCC_except_table476
+ GCC_except_table481
+ GCC_except_table491
+ GCC_except_table507
+ GCC_except_table509
+ GCC_except_table513
+ GCC_except_table515
+ GCC_except_table517
+ GCC_except_table524
+ GCC_except_table528
+ GCC_except_table530
+ GCC_except_table538
+ GCC_except_table544
+ GCC_except_table546
+ GCC_except_table548
+ GCC_except_table550
+ GCC_except_table552
+ GCC_except_table556
+ GCC_except_table558
+ GCC_except_table562
+ GCC_except_table563
+ _SANDBOX_EXTENSION_NOFOLLOW
+ ___154-[BRCXPCRegularIPCsClient(FPFSAdditions) getDefaultAppContainerItemForContainerID:localBundleDeclaresDocumentScopePublic:recreateDocumentsIfNeeded:reply:]_block_invoke
+ ___154-[BRCXPCRegularIPCsClient(FPFSAdditions) getDefaultAppContainerItemForContainerID:localBundleDeclaresDocumentScopePublic:recreateDocumentsIfNeeded:reply:]_block_invoke_2
+ ___81-[BRCFSSchedulerBase scheduleWithBatchSize:whereSQLClause:columns:actionHandler:]_block_invoke
+ ___block_descriptor_74_e8_32s40s48s56bs_e17_v16?0"NSError"8l
+ ___block_descriptor_84_e8_32s40s48s56bs64r_e23_B16?0"PQLConnection"8l
+ _objc_msgSend$_loadPersistedStateFromPlist:
+ _objc_msgSend$br_withIOPolicyFlags:type:forBlock:
+ _objc_msgSend$brc_issueSandboxExtensionOfClass:flags:error:
+ _objc_msgSend$isMetadataExtracted
+ _objc_msgSend$newNonSandboxedIPCAccessEventForCheck:bundleID:selector:
+ _objc_msgSend$postNonSandboxedIPCCheckTelemetry:bundleID:selector:
- +[AppTelemetryTimeSeriesEvent(BRCAdditions) newNonSandboxedIPCAccessEventForCheck:bundleID:]
- -[BRCAccountSession(IPCTelemetry) postNonSandboxedIPCCheckTelemetry:bundleID:]
- -[BRCXPCRegularIPCsClient(FPFSAdditions) getDefaultAppContainerItemForContainerID:recreateDocumentsIfNeeded:reply:]
- GCC_except_table190
- GCC_except_table196
- GCC_except_table243
- GCC_except_table253
- GCC_except_table294
- GCC_except_table312
- GCC_except_table323
- GCC_except_table325
- GCC_except_table327
- GCC_except_table329
- GCC_except_table331
- GCC_except_table335
- GCC_except_table337
- GCC_except_table339
- GCC_except_table348
- GCC_except_table352
- GCC_except_table355
- GCC_except_table365
- GCC_except_table371
- GCC_except_table372
- GCC_except_table381
- GCC_except_table408
- GCC_except_table417
- GCC_except_table421
- GCC_except_table427
- GCC_except_table429
- GCC_except_table435
- GCC_except_table439
- GCC_except_table446
- GCC_except_table451
- GCC_except_table464
- GCC_except_table469
- GCC_except_table473
- GCC_except_table478
- GCC_except_table485
- GCC_except_table492
- GCC_except_table506
- GCC_except_table510
- GCC_except_table512
- GCC_except_table514
- GCC_except_table521
- GCC_except_table525
- GCC_except_table527
- GCC_except_table529
- GCC_except_table541
- GCC_except_table543
- GCC_except_table545
- GCC_except_table547
- GCC_except_table549
- GCC_except_table553
- GCC_except_table555
- GCC_except_table557
- GCC_except_table559
- ___115-[BRCXPCRegularIPCsClient(FPFSAdditions) getDefaultAppContainerItemForContainerID:recreateDocumentsIfNeeded:reply:]_block_invoke
- ___115-[BRCXPCRegularIPCsClient(FPFSAdditions) getDefaultAppContainerItemForContainerID:recreateDocumentsIfNeeded:reply:]_block_invoke_2
- ___block_descriptor_66_e8_32s40s48s56bs_e17_v16?0"NSError"8l
- _objc_msgSend$newNonSandboxedIPCAccessEventForCheck:bundleID:
- _objc_msgSend$postNonSandboxedIPCCheckTelemetry:bundleID:
CStrings:
+ "-[BRCClientZone _loadPersistedStateFromPlist:]"
+ "-[BRCXPCRegularIPCsClient(FPFSAdditions) getDefaultAppContainerItemForContainerID:localBundleDeclaresDocumentScopePublic:recreateDocumentsIfNeeded:reply:]"
+ "-[BRCXPCRegularIPCsClient(FPFSAdditions) getDefaultAppContainerItemForContainerID:localBundleDeclaresDocumentScopePublic:recreateDocumentsIfNeeded:reply:]_block_invoke"
+ "[WARNING] Clearing stale wants-data-unlinked on %@%@"
+ "[WARNING] resolveBookmarkDataToURL denied for %@: can't enforce symlink-free path resolution%@"
- "-[BRCXPCRegularIPCsClient(FPFSAdditions) getDefaultAppContainerItemForContainerID:recreateDocumentsIfNeeded:reply:]"
- "-[BRCXPCRegularIPCsClient(FPFSAdditions) getDefaultAppContainerItemForContainerID:recreateDocumentsIfNeeded:reply:]_block_invoke"
```
