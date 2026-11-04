## Metal

> `/System/Library/Frameworks/Metal.framework/Versions/A/Metal`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-383.1.0.0.0
-  __TEXT.__text: 0x1f57a0
+384.5.0.0.0
+  __TEXT.__text: 0x1f5bf0
   __TEXT.__objc_methlist: 0x1fac4
   __TEXT.__cstring: 0x242b9
-  __TEXT.__gcc_except_tab: 0xc5d4
+  __TEXT.__gcc_except_tab: 0xc5dc
   __TEXT.__const: 0x2e750
   __TEXT.__oslogstring: 0x2401
   __TEXT.__ustring: 0x1be
-  __TEXT.__unwind_info: 0xa718
+  __TEXT.__unwind_info: 0xa720
   __TEXT.__eh_frame: 0x78
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 14034
-  Symbols:   26119
+  Functions: 14035
+  Symbols:   26126
   CStrings:  4727
 
Symbols:
+ GCC_except_table1017
+ GCC_except_table1027
+ GCC_except_table1038
+ GCC_except_table1042
+ GCC_except_table1048
+ GCC_except_table1052
+ GCC_except_table1059
+ GCC_except_table1068
+ GCC_except_table1079
+ GCC_except_table1106
+ GCC_except_table1109
+ GCC_except_table1118
+ GCC_except_table1122
+ GCC_except_table1128
+ GCC_except_table1144
+ GCC_except_table370
+ GCC_except_table381
+ GCC_except_table383
+ GCC_except_table388
+ GCC_except_table390
+ GCC_except_table414
+ GCC_except_table418
+ GCC_except_table449
+ GCC_except_table468
+ GCC_except_table498
+ GCC_except_table502
+ GCC_except_table506
+ GCC_except_table510
+ GCC_except_table513
+ GCC_except_table533
+ GCC_except_table587
+ GCC_except_table594
+ GCC_except_table599
+ GCC_except_table602
+ GCC_except_table609
+ GCC_except_table611
+ GCC_except_table618
+ GCC_except_table623
+ GCC_except_table627
+ GCC_except_table630
+ GCC_except_table634
+ GCC_except_table637
+ GCC_except_table651
+ GCC_except_table656
+ GCC_except_table683
+ GCC_except_table697
+ GCC_except_table703
+ GCC_except_table713
+ GCC_except_table720
+ GCC_except_table730
+ GCC_except_table732
+ GCC_except_table742
+ GCC_except_table761
+ GCC_except_table764
+ GCC_except_table778
+ GCC_except_table782
+ GCC_except_table789
+ GCC_except_table793
+ GCC_except_table815
+ GCC_except_table868
+ GCC_except_table874
+ GCC_except_table885
+ GCC_except_table894
+ GCC_except_table900
+ GCC_except_table904
+ GCC_except_table912
+ GCC_except_table920
+ GCC_except_table943
+ GCC_except_table948
+ GCC_except_table950
+ GCC_except_table952
+ GCC_except_table954
+ GCC_except_table956
+ GCC_except_table965
+ GCC_except_table972
+ GCC_except_table980
+ GCC_except_table983
+ GCC_except_table987
+ __ZL21enableAIRNTInterfacesP19MTLSchedulerRequestb
- GCC_except_table1015
- GCC_except_table1026
- GCC_except_table1037
- GCC_except_table1041
- GCC_except_table1047
- GCC_except_table1051
- GCC_except_table1056
- GCC_except_table1067
- GCC_except_table1078
- GCC_except_table1104
- GCC_except_table1108
- GCC_except_table1115
- GCC_except_table1121
- GCC_except_table1127
- GCC_except_table1143
- GCC_except_table373
- GCC_except_table377
- GCC_except_table382
- GCC_except_table387
- GCC_except_table389
- GCC_except_table448
- GCC_except_table456
- GCC_except_table467
- GCC_except_table491
- GCC_except_table497
- GCC_except_table501
- GCC_except_table583
- GCC_except_table585
- GCC_except_table593
- GCC_except_table597
- GCC_except_table600
- GCC_except_table608
- GCC_except_table610
- GCC_except_table615
- GCC_except_table621
- GCC_except_table626
- GCC_except_table628
- GCC_except_table633
- GCC_except_table636
- GCC_except_table650
- GCC_except_table655
- GCC_except_table682
- GCC_except_table695
- GCC_except_table702
- GCC_except_table711
- GCC_except_table737
- GCC_except_table741
- GCC_except_table755
- GCC_except_table763
- GCC_except_table780
- GCC_except_table791
- GCC_except_table814
- GCC_except_table867
- GCC_except_table873
- GCC_except_table884
- GCC_except_table891
- GCC_except_table895
- GCC_except_table901
- GCC_except_table909
- GCC_except_table919
- GCC_except_table921
- GCC_except_table942
- GCC_except_table947
- GCC_except_table949
- GCC_except_table951
- GCC_except_table953
- GCC_except_table955
- GCC_except_table964
- GCC_except_table971
- GCC_except_table979
- GCC_except_table981
- GCC_except_table984
Functions:
~ __ZN24MTLXPCCompilerConnection8tryBoostERKNSt3__110shared_ptrI19MTLSchedulerRequestEERNS0_11unique_lockINS0_5mutexEEE : 284 -> 392
~ __ZN23MTLCompilerTaskInternal18waitUntilCompletedEv : 412 -> 460
~ -[_MTLBinaryArchive materializeEntryForKey:fileIndex:containsEntry:addEntry:] : 280 -> 272
~ __ZN25MTLCompilerBuiltinRequest17serializedRequestEjPPc : 380 -> 408
~ __ZN21MTLCompilerConnection15scheduleRequestEbNSt3__110shared_ptrI19MTLSchedulerRequestEERNS0_11unique_lockINS0_5mutexEEE : 512 -> 672
~ __ZNK21MTLCompilerConnection6isIdleEv : 28 -> 32
~ __Z19getArchiveReferenceNSt3__117basic_string_viewIcNS_11char_traitsIcEEEE : 744 -> 756
~ __ZN26MTLLegacyCompilerScheduler12buildRequestEjP18MTLCompilerRequestbP11objc_objectU13block_pointerFv16MTLCompilerErrorPU27objcproto16OS_dispatch_data8NSObjectPKcE : 1296 -> 1372
~ __ZN37MTLLegacyMonolithicCompilerConnection20BuildRequestInternalEP18MTLCompilerRequestPKcPU27objcproto16OS_dispatch_data8NSObjectP11objc_objectU13block_pointerFvjPKvmS3_E : 728 -> 732
~ ____ZN37MTLLegacyMonolithicCompilerConnection20BuildRequestInternalEP18MTLCompilerRequestPKcPU27objcproto16OS_dispatch_data8NSObjectP11objc_objectU13block_pointerFvjPKvmS3_E_block_invoke : 160 -> 164
~ +[MTLLoader(MTLLoaderAIRNT) deserializeObjectFromAIRNTHeaderAtSection:reader:errorHandler:handler:] : 1560 -> 1568
~ __Z19newLogReplayRequestP18MTLCompilerRequestPKcPU27objcproto16OS_dispatch_data8NSObjecti : 1004 -> 1048
~ __ZN17MTLLibraryBuilder35initLibraryContainerWithRequestDataEP19MTLLibraryContainerR21MTLLibraryRequestDataP11objc_objectU13block_pointerFvvE : 2924 -> 2836
~ __ZL16downgradeRequestPK26MTLCompilerFunctionRequestjPU27objcproto16OS_dispatch_data8NSObjectRK12MTLUINT256_tP11objc_objectU13block_pointerFv16MTLCompilerErrorS4_PKcE : 796 -> 752
+ __ZL21enableAIRNTInterfacesP19MTLSchedulerRequestb
~ __ZN17MTLLibraryBuilder17newLibraryWithDAGEP8NSStringP7NSArrayIPU22objcproto11MTLFunction11objc_objectEU13block_pointerFvPU21objcproto10MTLLibrary11objc_objectP7NSErrorEbNSt3__110shared_ptrINSD_6vectorI21stitchedAirDescriptorNSD_9allocatorISG_EEEEEEmPS2_IPU27objcproto16MTLBinaryArchive11objc_objectESM_P11objc_object : 1976 -> 1944
~ -[_MTLFunctionInternal newSpecializedFunctionWithDescriptor:destinationArchive:functionCache:sync:compilerTask:completionHandler:] : 2484 -> 2452
~ -[MTLCompiler compileBuiltinRequestInternal:compilerTask:completionHandler:] : 1500 -> 1456
~ -[MTLCompiler generateMachOWithID:binaryEntries:machOSpecializedData:machOType:Path:platform:bitcodeList:compilerTask:completionHandler:] : 3924 -> 3892
~ -[MTLCompiler createBinaryArchiveAsRecompileTarget:compilerTask:completionHandler:] : 640 -> 608
~ -[MTLCompiler compileFunctionRequestInternal:frameworkLinking:linkDataSize:reflectionOnly:compilerTask:completionHandler:] : 9588 -> 9544
~ -[MTLCompiler compileStatelessFunctionRequest:reflectionOnly:compilerTask:completionHandler:] : 3212 -> 3168
~ -[MTLCompiler compileLibraryRequest:compilerTask:completionHandler:] : 724 -> 680
~ __ZN20MTLCompilerScheduler13insertRequestERKNSt3__110shared_ptrI19MTLSchedulerRequestEE : 108 -> 112
~ __ZN20MTLCompilerScheduler24cleanupCancelledRequestsEv : 552 -> 560
~ __ZN20MTLCompilerScheduler25handleRequestCancellationERKNSt3__110shared_ptrI19MTLSchedulerRequestEE : 240 -> 336
~ __ZN20MTLCompilerScheduler26tryCancelRequestWithReasonERKNSt3__110shared_ptrI19MTLSchedulerRequestEENS2_12CancelReasonE : 140 -> 148
~ ____ZN20MTLCompilerScheduler19createBlockWithDataENSt3__110shared_ptrI19MTLSchedulerRequestEE_block_invoke : 464 -> 568
~ __ZN20MTLCompilerScheduler17getBestConnectionERKNSt3__110shared_ptrI19MTLSchedulerRequestEERNS0_11unique_lockINS0_5mutexEEE : 1256 -> 1308
~ __ZN20MTLCompilerScheduler32shouldScheduleAfterCompilerBoostERKNSt3__110shared_ptrI19MTLSchedulerRequestEERNS0_11unique_lockINS0_5mutexEEE : 600 -> 680
~ __ZL12boostProcessRKNSt3__110shared_ptrI19MTLSchedulerRequestEERP21MTLCompilerConnectionbbRNS_11unique_lockINS_5mutexEEE : 328 -> 364
~ __ZN20MTLCompilerScheduler12buildRequestEjNSt3__110shared_ptrI18MTLCompilerRequestEEbP11objc_objectU13block_pointerFv16MTLCompilerErrorPU27objcproto16OS_dispatch_data8NSObjectPKcE : 1740 -> 1896
~ __ZN20MTLCompilerScheduler14RequestCompareclERKNSt3__110shared_ptrI19MTLSchedulerRequestEES6_ : 112 -> 152
~ __ZN30MTLLegacyXPCCompilerConnection20BuildRequestInternalEP18MTLCompilerRequestPKcPU27objcproto16OS_dispatch_data8NSObjectibP11objc_objectU13block_pointerFvjPKvmS3_E : 1444 -> 1456
~ ____ZN30MTLLegacyXPCCompilerConnection20BuildRequestInternalEP18MTLCompilerRequestPKcPU27objcproto16OS_dispatch_data8NSObjectibP11objc_objectU13block_pointerFvjPKvmS3_E_block_invoke : 1140 -> 1144
~ ____ZN19MTLSchedulerRequest16generateXPCBlockE11qos_class_ti_block_invoke : 3060 -> 3084
~ __ZN19MTLSchedulerRequest19newLogReplayRequestERKNSt3__110shared_ptrI18MTLCompilerRequestEEPKcPU27objcproto16OS_dispatch_data8NSObjecti : 1152 -> 1368
~ ____ZN19MTLSchedulerRequest23generateMonolithicBlockE11qos_class_ti_block_invoke : 884 -> 908
~ ____ZN19MTLSchedulerRequest23generateMonolithicBlockE11qos_class_ti_block_invoke.10 : 320 -> 328
CStrings:
+ "01:46:29"
+ "Oct 29 2026"
+ "Oct 29 2026 01:46:29"
- "18:03:27"
- "Oct  3 2026"
- "Oct  3 2026 18:03:27"
```
