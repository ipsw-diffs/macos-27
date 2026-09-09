## QuartzCore

> `/System/Library/Frameworks/QuartzCore.framework/Versions/A/QuartzCore`

```diff

-1223.2.2.0.0
-  __TEXT.__text: 0x3f5f18
-  __TEXT.__objc_methlist: 0xc8fc
-  __TEXT.__const: 0x17fa4
-  __TEXT.__dlopen_cstrs: 0x24a
-  __TEXT.__cstring: 0x295b3
-  __TEXT.__gcc_except_tab: 0xa3a4
-  __TEXT.__oslogstring: 0x11a0b
-  __TEXT.__unwind_info: 0x9c48
+1223.2.3.0.0
+  __TEXT.__text: 0x3fa52c
+  __TEXT.__objc_methlist: 0xc9e8
+  __TEXT.__const: 0x17fe4
+  __TEXT.__dlopen_cstrs: 0x2ae
+  __TEXT.__cstring: 0x296c2
+  __TEXT.__gcc_except_tab: 0xa564
+  __TEXT.__oslogstring: 0x12238
+  __TEXT.__unwind_info: 0x9d08
   __TEXT.__eh_frame: 0x50
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xf5f0
-  __DATA_CONST.__objc_classlist: 0x4c8
+  __DATA_CONST.__const: 0xf660
+  __DATA_CONST.__objc_classlist: 0x4d8
   __DATA_CONST.__objc_catlist: 0x80
-  __DATA_CONST.__objc_protolist: 0xe0
+  __DATA_CONST.__objc_protolist: 0xe8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5f70
+  __DATA_CONST.__objc_selrefs: 0x6028
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x5d0
+  __DATA_CONST.__objc_superrefs: 0x5e0
   __DATA_CONST.__objc_arraydata: 0x3798
-  __DATA_CONST.__got: 0xf20
-  __AUTH_CONST.__const: 0x199f0
-  __AUTH_CONST.__cfstring: 0x1a440
-  __AUTH_CONST.__objc_const: 0xf308
+  __DATA_CONST.__got: 0xf58
+  __AUTH_CONST.__const: 0x19b00
+  __AUTH_CONST.__cfstring: 0x1a520
+  __AUTH_CONST.__objc_const: 0xf540
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_doubleobj: 0xe0
   __AUTH_CONST.__objc_intobj: 0x4278
   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH_CONST.__objc_dictobj: 0x348
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x2c78
-  __AUTH.__objc_data: 0x14f0
+  __AUTH_CONST.__auth_got: 0x2cc0
+  __AUTH.__objc_data: 0x1590
   __AUTH.__data: 0x60
-  __DATA.__objc_ivar: 0x6b0
-  __DATA.__data: 0x14e0
+  __DATA.__objc_ivar: 0x6b8
+  __DATA.__data: 0x1540
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x3e38
+  __DATA.__bss: 0x3e50
   __DATA.__common: 0xc
   __DATA_DIRTY.__objc_data: 0x1ae0
   __DATA_DIRTY.__data: 0x6e8
-  __DATA_DIRTY.__bss: 0x68e8
+  __DATA_DIRTY.__bss: 0x69c8
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/ColorSync.framework/Versions/A/ColorSync
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 14051
-  Symbols:   23479
-  CStrings:  8599
+  Functions: 14091
+  Symbols:   23598
+  CStrings:  8665
 
Symbols:
+ -[CAWindowServerDisplayExternalSyncManager _init]
+ -[CAWindowServerDisplayExternalSyncManager dealloc]
+ -[CAWindowServerDisplayExternalSyncManager externalSyncManager]
+ -[CAWindowServerDisplayExternalSyncManager sessionUUID]
+ -[DisplayExternalSyncObserver clockPresenceChanged:isPresent:]
+ -[DisplayExternalSyncObserver initWithManager:]
+ -[DisplayExternalSyncObserver isOutOfBounds:errorNanos:]
+ -[DisplayExternalSyncObserver lockStateChanged:isLocked:]
+ -[DisplayExternalSyncObserver observeValueForKeyPath:ofObject:change:context:]
+ -[DisplayExternalSyncObserver sessionStopped:withStatus:]
+ -[DisplayExternalSyncObserver startObservingSSAMDevices]
+ -[DisplayExternalSyncObserver stopObservingSSAMDevices]
+ GCC_except_table10046
+ GCC_except_table10051
+ GCC_except_table10060
+ GCC_except_table10061
+ GCC_except_table10062
+ GCC_except_table10063
+ GCC_except_table10074
+ GCC_except_table10076
+ GCC_except_table10121
+ GCC_except_table10128
+ GCC_except_table10130
+ GCC_except_table10516
+ GCC_except_table10523
+ GCC_except_table10524
+ GCC_except_table10543
+ GCC_except_table10554
+ GCC_except_table10626
+ GCC_except_table10627
+ GCC_except_table10628
+ GCC_except_table10633
+ GCC_except_table10639
+ GCC_except_table10640
+ GCC_except_table10641
+ GCC_except_table10642
+ GCC_except_table10657
+ GCC_except_table10658
+ GCC_except_table10659
+ GCC_except_table10660
+ GCC_except_table10686
+ GCC_except_table10713
+ GCC_except_table10715
+ GCC_except_table10730
+ GCC_except_table10756
+ GCC_except_table10758
+ GCC_except_table10763
+ GCC_except_table10769
+ GCC_except_table10770
+ GCC_except_table10777
+ GCC_except_table10778
+ GCC_except_table10779
+ GCC_except_table10792
+ GCC_except_table10794
+ GCC_except_table10804
+ GCC_except_table10809
+ GCC_except_table10810
+ GCC_except_table10811
+ GCC_except_table10828
+ GCC_except_table10956
+ GCC_except_table10957
+ GCC_except_table10963
+ GCC_except_table10965
+ GCC_except_table11054
+ GCC_except_table11168
+ GCC_except_table11188
+ GCC_except_table11190
+ GCC_except_table11352
+ GCC_except_table11399
+ GCC_except_table11542
+ GCC_except_table11705
+ GCC_except_table11748
+ GCC_except_table11945
+ GCC_except_table11947
+ GCC_except_table11952
+ GCC_except_table11961
+ GCC_except_table11964
+ GCC_except_table11966
+ GCC_except_table12027
+ GCC_except_table12154
+ GCC_except_table12155
+ GCC_except_table12157
+ GCC_except_table12349
+ GCC_except_table12351
+ GCC_except_table12352
+ GCC_except_table12354
+ GCC_except_table12373
+ GCC_except_table12643
+ GCC_except_table12677
+ GCC_except_table12849
+ GCC_except_table12852
+ GCC_except_table12855
+ GCC_except_table12860
+ GCC_except_table12881
+ GCC_except_table13260
+ GCC_except_table13262
+ GCC_except_table13265
+ GCC_except_table13270
+ GCC_except_table13305
+ GCC_except_table13328
+ GCC_except_table13458
+ GCC_except_table13605
+ GCC_except_table13624
+ GCC_except_table13647
+ GCC_except_table13655
+ GCC_except_table13663
+ GCC_except_table13664
+ GCC_except_table13712
+ GCC_except_table13742
+ GCC_except_table13744
+ GCC_except_table13758
+ GCC_except_table13760
+ GCC_except_table13768
+ GCC_except_table13774
+ GCC_except_table13779
+ GCC_except_table13784
+ GCC_except_table13847
+ GCC_except_table13900
+ GCC_except_table13937
+ GCC_except_table13942
+ GCC_except_table13955
+ GCC_except_table13979
+ GCC_except_table13982
+ GCC_except_table14127
+ GCC_except_table14133
+ GCC_except_table14137
+ GCC_except_table14146
+ GCC_except_table14190
+ GCC_except_table14193
+ GCC_except_table14232
+ GCC_except_table14321
+ GCC_except_table9104
+ GCC_except_table9106
+ GCC_except_table9191
+ GCC_except_table9196
+ GCC_except_table9197
+ GCC_except_table9202
+ GCC_except_table9215
+ GCC_except_table9216
+ GCC_except_table9319
+ GCC_except_table9321
+ GCC_except_table9326
+ GCC_except_table9363
+ GCC_except_table9366
+ GCC_except_table9371
+ GCC_except_table9373
+ GCC_except_table9376
+ GCC_except_table9389
+ GCC_except_table9390
+ GCC_except_table9391
+ GCC_except_table9392
+ GCC_except_table9400
+ GCC_except_table9434
+ GCC_except_table9435
+ GCC_except_table9436
+ GCC_except_table9556
+ GCC_except_table9559
+ GCC_except_table9561
+ GCC_except_table9574
+ GCC_except_table9579
+ GCC_except_table9580
+ GCC_except_table9586
+ GCC_except_table9588
+ GCC_except_table9589
+ GCC_except_table9596
+ GCC_except_table9602
+ GCC_except_table9605
+ GCC_except_table9608
+ GCC_except_table9619
+ GCC_except_table9620
+ GCC_except_table9630
+ GCC_except_table9637
+ GCC_except_table9643
+ GCC_except_table9644
+ GCC_except_table9651
+ GCC_except_table9652
+ GCC_except_table9668
+ GCC_except_table9670
+ GCC_except_table9673
+ GCC_except_table9675
+ GCC_except_table9676
+ GCC_except_table9685
+ GCC_except_table9708
+ GCC_except_table9715
+ GCC_except_table9718
+ GCC_except_table9725
+ GCC_except_table9737
+ GCC_except_table9745
+ GCC_except_table9746
+ GCC_except_table9751
+ GCC_except_table9752
+ GCC_except_table9754
+ GCC_except_table9764
+ GCC_except_table9766
+ GCC_except_table9775
+ GCC_except_table9777
+ GCC_except_table9778
+ GCC_except_table9798
+ GCC_except_table9903
+ GCC_except_table9905
+ GCC_except_table9915
+ GCC_except_table9916
+ GCC_except_table9917
+ GCC_except_table9918
+ GCC_except_table9924
+ GCC_except_table9935
+ GCC_except_table9940
+ GCC_except_table9942
+ GCC_except_table9943
+ GCC_except_table9954
+ GCC_except_table9956
+ OBJC_IVAR_$_CAWindowServerDisplayExternalSyncManager._external_sync_manager
+ OBJC_IVAR_$_DisplayExternalSyncObserver._manager
+ _MSGConfigureDerivedSync
+ _MSGDeinitializeDeviceHandle
+ _MSGGetSyncRunState
+ _MSGInitDerivedSync
+ _MSGInitializeDeviceHandle
+ _MSGInitializeSyncHandle
+ _MSGReleaseSyncHandle
+ _MSGResetSync
+ _MSGStartSync
+ _NSKeyValueChangeNewKey
+ _OBJC_CLASS_$_CAWindowServerDisplayExternalSyncManager
+ _OBJC_CLASS_$_DisplayExternalSyncObserver
+ _OBJC_CLASS_$_TSMSGFollowConfig
+ _OBJC_CLASS_$_TSMSGService
+ _OBJC_CLASS_$_TSMSGSyncDescriptor
+ _OBJC_CLASS_$_TSSyncEntityManager
+ _OBJC_METACLASS_$_CAWindowServerDisplayExternalSyncManager
+ _OBJC_METACLASS_$_DisplayExternalSyncObserver
+ _TSNullClockIdentifier
+ _ZL30IOMobileFramebufferLibraryCorePPc
+ _ZL31audit_stringIOMobileFramebuffer
+ _ZZL57getIOMobileFramebufferTimingSupportsExternalSyncSymbolLocvE3ptr
+ __OBJC_$_INSTANCE_METHODS_CAWindowServerDisplayExternalSyncManager
+ __OBJC_$_INSTANCE_METHODS_DisplayExternalSyncObserver
+ __OBJC_$_INSTANCE_VARIABLES_CAWindowServerDisplayExternalSyncManager
+ __OBJC_$_INSTANCE_VARIABLES_DisplayExternalSyncObserver
+ __OBJC_$_PROP_LIST_CAWindowServerDisplayExternalSyncManager
+ __OBJC_$_PROP_LIST_DisplayExternalSyncObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_TSMSGFollowDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TSMSGFollowDelegate
+ __OBJC_$_PROTOCOL_REFS_TSMSGFollowDelegate
+ __OBJC_CLASS_PROTOCOLS_$_DisplayExternalSyncObserver
+ __OBJC_CLASS_RO_$_CAWindowServerDisplayExternalSyncManager
+ __OBJC_CLASS_RO_$_DisplayExternalSyncObserver
+ __OBJC_LABEL_PROTOCOL_$_TSMSGFollowDelegate
+ __OBJC_METACLASS_RO_$_CAWindowServerDisplayExternalSyncManager
+ __OBJC_METACLASS_RO_$_DisplayExternalSyncObserver
+ __OBJC_PROTOCOL_$_TSMSGFollowDelegate
+ __ZL57getIOMobileFramebufferTimingSupportsExternalSyncSymbolLocv
+ __ZN2CA12WindowServer26DisplayExternalSyncManager12kDeviceNamesE
+ __ZN2CA12WindowServer26DisplayExternalSyncManager12stop_sessionEv
+ __ZN2CA12WindowServer26DisplayExternalSyncManager17handle_clock_lostEv
+ __ZN2CA12WindowServer26DisplayExternalSyncManager18stop_clock_pollingEv
+ __ZN2CA12WindowServer26DisplayExternalSyncManager19start_clock_pollingEv
+ __ZN2CA12WindowServer26DisplayExternalSyncManager21finalize_session_stopEv
+ __ZN2CA12WindowServer26DisplayExternalSyncManager25trigger_mode_list_rebuildEj
+ __ZN2CA12WindowServer26DisplayExternalSyncManager27release_sync_handles_lockedEv
+ __ZN2CA12WindowServer26DisplayExternalSyncManager29stop_derived_sync_for_displayEj
+ __ZN2CA12WindowServerL15kDerivedSyncIDsE
+ __ZNKSt3__110__function6__funcIZZN2CA12WindowServer12IOMFBDisplay20update_digital_modesERNS3_7Display7ModeSetERNS5_4ModeEPK9__CFArraySC_ENK3$_1clERKS8_RKNS2_6Render11PerModeInfoEEUlfE_FbfEE7__cloneEPNS0_6__baseISL_EE
+ __ZNKSt3__110__function6__funcIZZN2CA12WindowServer12IOMFBDisplay20update_digital_modesERNS3_7Display7ModeSetERNS5_4ModeEPK9__CFArraySC_ENK3$_1clERKS8_RKNS2_6Render11PerModeInfoEEUlfE_FbfEE7__cloneEv
+ __ZNKSt3__112__hash_tableINS_17__hash_value_typeIN2CA12WindowServer7Display4ModeENS3_12IOMFBDisplay8ModeInfoEEENS_22__unordered_map_hasherIS5_NS_4pairIKS5_S7_EENS6_8ModeHashENS_8equal_toIS5_EEEENS_21__unordered_map_equalIS5_SC_SF_SD_EENS_9allocatorISC_EEE4findIS5_EENS_21__hash_const_iteratorIPNS_11__hash_nodeIS8_PvEEEERKT_
+ __ZNSt3__110__function12__value_funcIFbfEED2B9nqn220106Ev
+ __ZNSt3__110__function6__funcIZZN2CA12WindowServer12IOMFBDisplay20update_digital_modesERNS3_7Display7ModeSetERNS5_4ModeEPK9__CFArraySC_ENK3$_1clERKS8_RKNS2_6Render11PerModeInfoEEUlfE_FbfEE18destroy_deallocateEv
+ __ZNSt3__110__function6__funcIZZN2CA12WindowServer12IOMFBDisplay20update_digital_modesERNS3_7Display7ModeSetERNS5_4ModeEPK9__CFArraySC_ENK3$_1clERKS8_RKNS2_6Render11PerModeInfoEEUlfE_FbfEE7destroyEv
+ __ZNSt3__110__function6__funcIZZN2CA12WindowServer12IOMFBDisplay20update_digital_modesERNS3_7Display7ModeSetERNS5_4ModeEPK9__CFArraySC_ENK3$_1clERKS8_RKNS2_6Render11PerModeInfoEEUlfE_FbfEED0Ev
+ __ZNSt3__110__function6__funcIZZN2CA12WindowServer12IOMFBDisplay20update_digital_modesERNS3_7Display7ModeSetERNS5_4ModeEPK9__CFArraySC_ENK3$_1clERKS8_RKNS2_6Render11PerModeInfoEEUlfE_FbfEED1Ev
+ __ZNSt3__110__function6__funcIZZN2CA12WindowServer12IOMFBDisplay20update_digital_modesERNS3_7Display7ModeSetERNS5_4ModeEPK9__CFArraySC_ENK3$_1clERKS8_RKNS2_6Render11PerModeInfoEEUlfE_FbfEEclEOf
+ __ZNSt3__112__hash_tableINS_17__hash_value_typeIymEENS_22__unordered_map_hasherIyNS_4pairIKymEENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS6_SA_S8_EENS_9allocatorIS6_EEE4findIyEENS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEERKT_
+ __ZNSt3__112__hash_tableINS_17__hash_value_typeIymEENS_22__unordered_map_hasherIyNS_4pairIKymEENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS6_SA_S8_EENS_9allocatorIS6_EEED2Ev
+ __ZNSt3__16vectorI29CADisplayExternalSyncModeDescNS_9allocatorIS1_EEE20__throw_length_errorB9nqn220106Ev
+ __ZNSt3__16vectorI29CADisplayExternalSyncModeDescNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJS1_EEEPS1_DpOT_
+ __ZTVNSt3__110__function6__funcIZZN2CA12WindowServer12IOMFBDisplay20update_digital_modesERNS3_7Display7ModeSetERNS5_4ModeEPK9__CFArraySC_ENK3$_1clERKS8_RKNS2_6Render11PerModeInfoEEUlfE_FbfEEE
+ __ZZ31x_log_get_display_external_syncvE3log
+ __ZZ31x_log_get_display_external_syncvE4once
+ __ZZN12_GLOBAL__N_126check_frameworks_availableEvE4once
+ __ZZN12_GLOBAL__N_126check_frameworks_availableEvE9available
+ __ZZN2CA12WindowServer12IOMFBDisplay20update_digital_modesERNS0_7Display7ModeSetERNS2_4ModeEPK9__CFArrayS9_ENK3$_1clERKS5_RKNS_6Render11PerModeInfoE
+ __ZZN2CA12WindowServerL18snap_to_media_rateEfE11kMediaRates
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIymEENS_22__unordered_map_hasherIyNS_4pairIKymEENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS6_SA_S8_EENS_9allocatorIS6_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS5_EEENSL_IJEEEEEENS4_INS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSM_SK_OSN_OSO_E_clESM_SK_SZ_S10_
+ ___ZL30IOMobileFramebufferLibraryCorePPc_block_invoke
+ ____Z31x_log_get_display_external_syncv_block_invoke
+ ____ZL57getIOMobileFramebufferTimingSupportsExternalSyncSymbolLocv_block_invoke
+ ____ZN12_GLOBAL__N_126check_frameworks_availableEv_block_invoke
+ ____ZN2CA12WindowServer26DisplayExternalSyncManager18stop_clock_pollingEv_block_invoke
+ ____ZN2CA12WindowServer26DisplayExternalSyncManager19start_clock_pollingEv_block_invoke
+ _objc_msgSend$addMSGClock:withNominalSyncDuration:error:
+ _objc_msgSend$addObserver:forKeyPath:options:context:
+ _objc_msgSend$createFromDeviceName:syncID:
+ _objc_msgSend$displayExternalSyncManager
+ _objc_msgSend$externalSyncManager
+ _objc_msgSend$externalSyncMultiplier
+ _objc_msgSend$getPeriod:andPhaseAnchor:error:
+ _objc_msgSend$initWithManager:
+ _objc_msgSend$initWithSyncEntityUUID:syncDescriptors:nominalClockPeriod:syncMultiplier:toleranceEntityClockDurationNanos:toleranceMSGSyncDurationNanos:timeoutNanos:
+ _objc_msgSend$isActive
+ _objc_msgSend$isExternalSync
+ _objc_msgSend$rebuildModeList
+ _objc_msgSend$removeMSGClock:error:
+ _objc_msgSend$removeObserver:forKeyPath:
+ _objc_msgSend$setActive:error:
+ _objc_msgSend$sharedMSGService
+ _objc_msgSend$sharedSyncEntityManager
+ _objc_msgSend$startFollowSyncSessionWithConfig:delegate:error:
+ _objc_msgSend$startObservingSSAMDevices
+ _objc_msgSend$stopFollowSyncSession:error:
+ _objc_msgSend$stopObservingSSAMDevices
- GCC_except_table10042
- GCC_except_table10043
- GCC_except_table10044
- GCC_except_table10053
- GCC_except_table10058
- GCC_except_table10059
- GCC_except_table10070
- GCC_except_table10072
- GCC_except_table10117
- GCC_except_table10122
- GCC_except_table10124
- GCC_except_table10512
- GCC_except_table10519
- GCC_except_table10520
- GCC_except_table10539
- GCC_except_table10550
- GCC_except_table10622
- GCC_except_table10623
- GCC_except_table10624
- GCC_except_table10625
- GCC_except_table10634
- GCC_except_table10635
- GCC_except_table10636
- GCC_except_table10637
- GCC_except_table10649
- GCC_except_table10650
- GCC_except_table10651
- GCC_except_table10652
- GCC_except_table10682
- GCC_except_table10709
- GCC_except_table10711
- GCC_except_table10722
- GCC_except_table10751
- GCC_except_table10752
- GCC_except_table10753
- GCC_except_table10754
- GCC_except_table10762
- GCC_except_table10767
- GCC_except_table10773
- GCC_except_table10774
- GCC_except_table10788
- GCC_except_table10790
- GCC_except_table10800
- GCC_except_table10802
- GCC_except_table10803
- GCC_except_table10805
- GCC_except_table10824
- GCC_except_table10952
- GCC_except_table10953
- GCC_except_table10959
- GCC_except_table10961
- GCC_except_table11050
- GCC_except_table11164
- GCC_except_table11184
- GCC_except_table11186
- GCC_except_table11348
- GCC_except_table11395
- GCC_except_table11538
- GCC_except_table11701
- GCC_except_table11744
- GCC_except_table11941
- GCC_except_table11943
- GCC_except_table11944
- GCC_except_table11957
- GCC_except_table11958
- GCC_except_table11960
- GCC_except_table12023
- GCC_except_table12147
- GCC_except_table12150
- GCC_except_table12153
- GCC_except_table12345
- GCC_except_table12347
- GCC_except_table12348
- GCC_except_table12350
- GCC_except_table12369
- GCC_except_table12639
- GCC_except_table12673
- GCC_except_table12845
- GCC_except_table12848
- GCC_except_table12851
- GCC_except_table12856
- GCC_except_table12877
- GCC_except_table13279
- GCC_except_table13562
- GCC_except_table13578
- GCC_except_table13581
- GCC_except_table13604
- GCC_except_table13612
- GCC_except_table13620
- GCC_except_table13669
- GCC_except_table13699
- GCC_except_table13701
- GCC_except_table13715
- GCC_except_table13717
- GCC_except_table13725
- GCC_except_table13731
- GCC_except_table13736
- GCC_except_table13741
- GCC_except_table13804
- GCC_except_table13856
- GCC_except_table13857
- GCC_except_table13894
- GCC_except_table13912
- GCC_except_table13936
- GCC_except_table13939
- GCC_except_table14084
- GCC_except_table14090
- GCC_except_table14094
- GCC_except_table14103
- GCC_except_table14147
- GCC_except_table14150
- GCC_except_table14189
- GCC_except_table14278
- GCC_except_table9187
- GCC_except_table9192
- GCC_except_table9193
- GCC_except_table9198
- GCC_except_table9211
- GCC_except_table9212
- GCC_except_table9313
- GCC_except_table9315
- GCC_except_table9322
- GCC_except_table9354
- GCC_except_table9359
- GCC_except_table9364
- GCC_except_table9365
- GCC_except_table9367
- GCC_except_table9383
- GCC_except_table9385
- GCC_except_table9386
- GCC_except_table9388
- GCC_except_table9396
- GCC_except_table9427
- GCC_except_table9430
- GCC_except_table9432
- GCC_except_table9551
- GCC_except_table9552
- GCC_except_table9557
- GCC_except_table9569
- GCC_except_table9570
- GCC_except_table9571
- GCC_except_table9572
- GCC_except_table9578
- GCC_except_table9584
- GCC_except_table9592
- GCC_except_table9597
- GCC_except_table9598
- GCC_except_table9604
- GCC_except_table9611
- GCC_except_table9612
- GCC_except_table9626
- GCC_except_table9631
- GCC_except_table9633
- GCC_except_table9636
- GCC_except_table9646
- GCC_except_table9647
- GCC_except_table9648
- GCC_except_table9653
- GCC_except_table9655
- GCC_except_table9660
- GCC_except_table9672
- GCC_except_table9677
- GCC_except_table9704
- GCC_except_table9707
- GCC_except_table9714
- GCC_except_table9717
- GCC_except_table9733
- GCC_except_table9741
- GCC_except_table9742
- GCC_except_table9744
- GCC_except_table9747
- GCC_except_table9750
- GCC_except_table9758
- GCC_except_table9760
- GCC_except_table9767
- GCC_except_table9769
- GCC_except_table9770
- GCC_except_table9794
- GCC_except_table9899
- GCC_except_table9901
- GCC_except_table9908
- GCC_except_table9909
- GCC_except_table9910
- GCC_except_table9911
- GCC_except_table9920
- GCC_except_table9931
- GCC_except_table9936
- GCC_except_table9938
- GCC_except_table9939
- GCC_except_table9948
- GCC_except_table9950
CStrings:
+ "%s MSG device not available (single-die system)"
+ ", external sync %lux"
+ "26A425"
+ "Acquired sync handles for die %zu (%s)"
+ "AppleMSG framework not available at runtime"
+ "CA_DISABLE_REFLECTION_COMPENSATION"
+ "Cannot configure derived sync: TimeSync not locked"
+ "Cannot initialize syncs: handles not acquired"
+ "Cannot start session: invalid clock frequency"
+ "Cannot start session: no SSAM entity UUID"
+ "Clock frequency changed: %.3f Hz -> %.3f Hz"
+ "Clock signal acquired: %.3f Hz"
+ "Clock signal lost: %s"
+ "Clock signal out of range: %.3f Hz"
+ "Configured derived syncs on die %zu (%s) with multiplier %u"
+ "Display %u entered external sync mode with multiplier %u"
+ "Display %u exited external sync mode"
+ "DisplayExternalSync"
+ "Error stopping session: %s"
+ "Failed to acquire sync handles for SSAM entity"
+ "Failed to activate SSAM entity: %s"
+ "Failed to add MSG clock: %s"
+ "Failed to configure derived sync %u on die %zu: 0x%x"
+ "Failed to configure external sync for display %u, aborting mode switch"
+ "Failed to create TSMSGFollowConfig"
+ "Failed to initialize MSG device handle for %s: 0x%x"
+ "Failed to initialize base sync handle for %s: 0x%x"
+ "Failed to initialize derived sync %u on die %zu: 0x%x"
+ "Failed to initialize sync handle for %s sync ID %u: 0x%x"
+ "Failed to rebuild syncs for display %u"
+ "Failed to start session for initialize_syncs"
+ "Failed to start session: %s"
+ "Failed to start sync %u on die %zu: 0x%x"
+ "IOMFBExternalSyncCapability"
+ "IOMobileFramebufferTimingSupportsExternalSync"
+ "Multiplier mismatch: requested %u but active is %u"
+ "Released sync handles"
+ "Reset already-running base sync on die %zu"
+ "Reset already-running derived sync %u on die %zu"
+ "Reset syncs on all active dies"
+ "SSAM device connected: %s"
+ "SSAM device disconnected: %s"
+ "SSAM entity disconnected"
+ "Started MSG clock with ID: 0x%llx, nominal sync duration: %lld/%lld"
+ "Started clock presence polling"
+ "Started observing SSAM devices"
+ "Started session: %s with multiplier %u"
+ "Stopped clock presence polling"
+ "Stopped session"
+ "TSMSGService"
+ "TSSyncEntityManager"
+ "TSSyncEntityManager not available"
+ "TimeSync clock acquired at %.3f Hz"
+ "TimeSync clock lost"
+ "TimeSync framework not available at runtime"
+ "TimeSync lock acquired, external sync modes are now functional"
+ "TimeSync lock lost, ending session"
+ "TimeSync lock state changed: %s"
+ "TimeSync out of bounds — stopping session"
+ "TimeSync session stopped"
+ "Total"
+ "Triggered mode list rebuild (excluding display %u)"
+ "Triggered mode list rebuild for all displays"
+ "apple11"
+ "com.apple.QuartzCore.DisplayExternalSync.polling"
+ "die1"
+ "syncEntities"
+ "unlocked"
- "26A5415a"
- "Display ID %u: dropping out-of-bounds SIL swap for region %u: center [%f %f] half-extent %f"
```
