## SpotlightDaemon

> `/System/Library/PrivateFrameworks/SpotlightDaemon.framework/Versions/A/SpotlightDaemon`

```diff

-2465.2.7.400.0
-  __TEXT.__text: 0xcbd18
-  __TEXT.__objc_methlist: 0x4e24
+2465.2.13.400.0
+  __TEXT.__text: 0xcc498
+  __TEXT.__objc_methlist: 0x4e5c
   __TEXT.__const: 0x430
-  __TEXT.__cstring: 0x9e68
-  __TEXT.__gcc_except_tab: 0x46bc
-  __TEXT.__oslogstring: 0xc44e
-  __TEXT.__unwind_info: 0x3578
+  __TEXT.__cstring: 0x9ed9
+  __TEXT.__gcc_except_tab: 0x4714
+  __TEXT.__oslogstring: 0xc578
+  __TEXT.__unwind_info: 0x35b0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3e38
+  __DATA_CONST.__objc_selrefs: 0x3e60
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x158
   __DATA_CONST.__objc_arraydata: 0x2f0
   __DATA_CONST.__got: 0xbf8
   __AUTH_CONST.__const: 0x59e8
   __AUTH_CONST.__cfstring: 0x81a0
-  __AUTH_CONST.__objc_const: 0x6620
+  __AUTH_CONST.__objc_const: 0x6680
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x360
   __AUTH_CONST.__objc_intobj: 0x210
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x1078
+  __AUTH_CONST.__auth_got: 0x10a0
   __AUTH.__objc_data: 0x320
-  __DATA.__objc_ivar: 0x560
+  __DATA.__objc_ivar: 0x56c
   __DATA.__data: 0x3f0
-  __DATA.__bss: 0x1f8
+  __DATA.__bss: 0x208
   __DATA.__common: 0x4
   __DATA_DIRTY.__objc_data: 0xfa0
   __DATA_DIRTY.__data: 0x160

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 3507
-  Symbols:   6860
-  CStrings:  2650
+  Functions: 3519
+  Symbols:   6886
+  CStrings:  2658
 
Symbols:
+ +[SPCoreSpotlightIndexer enableRecycleOnProcessFdLimit]
+ -[CSSearchAgent _queryContextFromXPCDictionary:searchConnection:]
+ -[SPConcreteCoreSpotlightIndexer _checkIndexDirectoryProbe:]
+ -[SPConcreteCoreSpotlightIndexer _deferOpenAfterFdShortage:openErrno:what:]
+ -[SPConcreteCoreSpotlightIndexer _inFdShortageBackoff]
+ -[SPLocalizedStringUsageReporter claimTerminalCall]
+ GCC_except_table1002
+ GCC_except_table1024
+ GCC_except_table104
+ GCC_except_table1052
+ GCC_except_table1081
+ GCC_except_table1082
+ GCC_except_table1091
+ GCC_except_table1107
+ GCC_except_table1152
+ GCC_except_table1157
+ GCC_except_table1221
+ GCC_except_table1262
+ GCC_except_table1275
+ GCC_except_table1276
+ GCC_except_table1277
+ GCC_except_table1287
+ GCC_except_table1289
+ GCC_except_table1307
+ GCC_except_table1313
+ GCC_except_table1317
+ GCC_except_table1332
+ GCC_except_table1348
+ GCC_except_table1355
+ GCC_except_table1362
+ GCC_except_table1369
+ GCC_except_table1376
+ GCC_except_table1394
+ GCC_except_table1469
+ GCC_except_table1470
+ GCC_except_table1472
+ GCC_except_table1479
+ GCC_except_table1539
+ GCC_except_table1546
+ GCC_except_table379
+ GCC_except_table381
+ GCC_except_table388
+ GCC_except_table397
+ GCC_except_table425
+ GCC_except_table435
+ GCC_except_table450
+ GCC_except_table486
+ GCC_except_table487
+ GCC_except_table491
+ GCC_except_table50
+ GCC_except_table517
+ GCC_except_table54
+ GCC_except_table554
+ GCC_except_table56
+ GCC_except_table575
+ GCC_except_table576
+ GCC_except_table604
+ GCC_except_table61
+ GCC_except_table631
+ GCC_except_table64
+ GCC_except_table644
+ GCC_except_table647
+ GCC_except_table67
+ GCC_except_table700
+ GCC_except_table714
+ GCC_except_table726
+ GCC_except_table75
+ GCC_except_table756
+ GCC_except_table762
+ GCC_except_table777
+ GCC_except_table778
+ GCC_except_table78
+ GCC_except_table790
+ GCC_except_table819
+ GCC_except_table845
+ GCC_except_table846
+ GCC_except_table847
+ GCC_except_table86
+ GCC_except_table874
+ GCC_except_table92
+ GCC_except_table941
+ GCC_except_table962
+ GCC_except_table97
+ GCC_except_table988
+ GCC_except_table992
+ _OBJC_IVAR_$_SPConcreteCoreSpotlightIndexer._fdProcessLimitSinceUptimeNs
+ _OBJC_IVAR_$_SPConcreteCoreSpotlightIndexer._fdShortageUptimeNs
+ _OBJC_IVAR_$_SPLocalizedStringUsageReporter._terminalCallClaimed
+ _OUTLINED_FUNCTION_46
+ _SPFdShortageForOpen
+ _SPFdShortageMarksNow
+ _SPLogUnattributedFdShortageOnce
+ __exit
+ _clock_gettime_nsec_np
+ _fd_resource_error_count
+ _fd_thread_resource_error_count
+ _objc_msgSend$_checkIndexDirectoryProbe:
+ _objc_msgSend$_deferOpenAfterFdShortage:openErrno:what:
+ _objc_msgSend$_inFdShortageBackoff
+ _objc_msgSend$_queryContextFromXPCDictionary:searchConnection:
+ _objc_msgSend$claimTerminalCall
+ _sFdRecycleClaimed
+ _sFdRecycleEnabledUptimeNs
+ _sFdRecycleWouldHaveFiredLogged
+ _sFdUnattributedShortageLogged
+ _set_dir_stats
+ _touch_crash_state
- -[SPCoreSpotlightTask _makeFilterQueryStringForQueryContext:]
- GCC_except_table1016
- GCC_except_table103
- GCC_except_table1044
- GCC_except_table106
- GCC_except_table1073
- GCC_except_table1074
- GCC_except_table1083
- GCC_except_table1099
- GCC_except_table1144
- GCC_except_table1149
- GCC_except_table1213
- GCC_except_table1254
- GCC_except_table1260
- GCC_except_table1261
- GCC_except_table1267
- GCC_except_table1279
- GCC_except_table1281
- GCC_except_table1299
- GCC_except_table1305
- GCC_except_table1309
- GCC_except_table1324
- GCC_except_table1340
- GCC_except_table1347
- GCC_except_table1354
- GCC_except_table1361
- GCC_except_table1368
- GCC_except_table1386
- GCC_except_table1461
- GCC_except_table1462
- GCC_except_table1464
- GCC_except_table1471
- GCC_except_table1531
- GCC_except_table1538
- GCC_except_table376
- GCC_except_table378
- GCC_except_table384
- GCC_except_table390
- GCC_except_table418
- GCC_except_table428
- GCC_except_table443
- GCC_except_table479
- GCC_except_table480
- GCC_except_table484
- GCC_except_table49
- GCC_except_table510
- GCC_except_table53
- GCC_except_table547
- GCC_except_table55
- GCC_except_table568
- GCC_except_table569
- GCC_except_table597
- GCC_except_table60
- GCC_except_table624
- GCC_except_table63
- GCC_except_table637
- GCC_except_table640
- GCC_except_table65
- GCC_except_table693
- GCC_except_table707
- GCC_except_table719
- GCC_except_table73
- GCC_except_table749
- GCC_except_table755
- GCC_except_table77
- GCC_except_table770
- GCC_except_table771
- GCC_except_table783
- GCC_except_table812
- GCC_except_table83
- GCC_except_table838
- GCC_except_table839
- GCC_except_table840
- GCC_except_table867
- GCC_except_table87
- GCC_except_table93
- GCC_except_table933
- GCC_except_table954
- GCC_except_table976
- GCC_except_table980
- GCC_except_table99
CStrings:
+ "/.resolve/1"
+ "SIOpenIndexAtPathWithCallbacks"
+ "create-open of the new index"
+ "fd recycle would have fired (%{public}@, EMFILE for %llus)"
+ "index directory probe"
+ "not written"
+ "openIndex %@: %s failed for lack of file descriptors (%d); retry in %llus"
+ "openIndex %{public}@: open failed (%d) while fd shortages were counted"
+ "openIndex %{public}@: out of file descriptors (EMFILE) for %llus; exiting to recycle (crash record %{public}s)"
+ "written"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf01"
- "("
- "With filters: %@"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf1"
```
