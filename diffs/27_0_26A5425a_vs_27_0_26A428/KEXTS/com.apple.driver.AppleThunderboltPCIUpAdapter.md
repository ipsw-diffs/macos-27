## com.apple.driver.AppleThunderboltPCIUpAdapter

> `com.apple.driver.AppleThunderboltPCIUpAdapter`

```diff

 443.0.0.0.0
   __TEXT.__cstring: 0x42a6
-  __TEXT_EXEC.__text: 0x18cc4
+  __TEXT_EXEC.__text: 0x18e10
   __TEXT_EXEC.__auth_stubs: 0x330
   __DATA.__data: 0x220
   __DATA.__common: 0x38
Functions:
~ __ZN28AppleThunderboltPCIUpAdapter9MetaClassC1Ev : 72 -> 76
~ __ZN28AppleThunderboltPCIUpAdapterC2EPK11OSMetaClass : 52 -> 56
~ __ZN28AppleThunderboltPCIUpAdapterC1EPK11OSMetaClass : 52 -> 56
~ __ZN28AppleThunderboltPCIUpAdapterD0Ev : 68 -> 72
~ __ZN28AppleThunderboltPCIUpAdapter9MetaClassC2Ev : 72 -> 76
~ __ZNK28AppleThunderboltPCIUpAdapter9MetaClass5allocEv : 104 -> 108
~ __ZN28AppleThunderboltPCIUpAdapterC1Ev : 88 -> 92
~ __ZN28AppleThunderboltPCIUpAdapterC2Ev : 88 -> 92
~ __ZN28AppleThunderboltPCIUpAdapter4initEv : 156 -> 160
~ __ZN28AppleThunderboltPCIUpAdapter5startEP9IOService : 4200 -> 4204
~ __ZN28AppleThunderboltPCIUpAdapter16requestTerminateEP9IOServicej : 628 -> 632
~ __ZN28AppleThunderboltPCIUpAdapter8finalizeEj : 908 -> 912
~ __ZN28AppleThunderboltPCIUpAdapter4freeEv : 364 -> 368
~ __ZN28AppleThunderboltPCIUpAdapter13setupBootArgsEv : 972 -> 976
~ __ZN28AppleThunderboltPCIUpAdapter15createResourcesEv : 1272 -> 1276
~ __ZN28AppleThunderboltPCIUpAdapter16destroyResourcesEv : 536 -> 540
~ __ZN28AppleThunderboltPCIUpAdapter21configCommandCallbackEPviP26IOThunderboltConfigCommand : 588 -> 592
~ __ZN28AppleThunderboltPCIUpAdapter29findCapabilityCommandCallbackEPviP34IOThunderboltFindCapabilityCommand : 528 -> 532
~ __ZN28AppleThunderboltPCIUpAdapter17findExistingPathsEv : 5568 -> 5572
~ __ZN28AppleThunderboltPCIUpAdapter23finishExistingPathSetupEv : 952 -> 956
~ __ZN28AppleThunderboltPCIUpAdapter17getNextPortsArrayEP7OSArray : 8484 -> 8488
~ __ZN28AppleThunderboltPCIUpAdapter18findCandidatePathsEv : 2952 -> 2956
~ __ZN28AppleThunderboltPCIUpAdapter16beginPathRoutingEv : 1312 -> 1316
~ __ZN28AppleThunderboltPCIUpAdapter19waitForDownAdaptersEv : 2372 -> 2376
~ __ZN28AppleThunderboltPCIUpAdapter25cleanupDownAdapterWaitersEv : 344 -> 348
~ __ZN28AppleThunderboltPCIUpAdapter11reverseListEP7OSArray : 244 -> 248
~ __ZN28AppleThunderboltPCIUpAdapter19getExistingPortListEP17IOThunderboltPort : 1116 -> 1120
~ __ZN28AppleThunderboltPCIUpAdapter12findBestPathEv : 11812 -> 11816
~ __ZN28AppleThunderboltPCIUpAdapter13allocatePathsEP7OSArrayS1_ : 2032 -> 2036
~ __ZN28AppleThunderboltPCIUpAdapter12destroyPathsEv : 904 -> 908
~ __ZN28AppleThunderboltPCIUpAdapter11createPathsEv : 4304 -> 4308
~ __ZN28AppleThunderboltPCIUpAdapter12syncActivateEv : 524 -> 528
~ __ZN28AppleThunderboltPCIUpAdapter8activateEv : 340 -> 344
~ __ZN28AppleThunderboltPCIUpAdapter13activatePathsEv : 1136 -> 1140
~ __ZN28AppleThunderboltPCIUpAdapter22pathActivationCallbackEPviP25IOThunderboltAbstractPath : 648 -> 652
~ __ZN28AppleThunderboltPCIUpAdapter41startActivatingFindUpAdapterPCICapabilityEv : 892 -> 896
~ __ZN28AppleThunderboltPCIUpAdapter50processActivatingFindUpAdapterPCICapabilityResultsEiP34IOThunderboltFindCapabilityCommand : 656 -> 660
~ __ZN28AppleThunderboltPCIUpAdapter43startActivatingFindDownAdapterPCICapabilityEv : 932 -> 936
~ __ZN28AppleThunderboltPCIUpAdapter52processActivatingFindDownAdapterPCICapabilityResultsEiP34IOThunderboltFindCapabilityCommand : 812 -> 816
~ __ZN28AppleThunderboltPCIUpAdapter21startPreAdapterEnableEv : 668 -> 672
~ __ZN28AppleThunderboltPCIUpAdapter16preAdapterEnableEP28IOThunderboltDispatchContext : 1624 -> 1628
~ __ZN28AppleThunderboltPCIUpAdapter27startDownAdapterEnableWriteEv : 1004 -> 1008
~ __ZN28AppleThunderboltPCIUpAdapter36processDownAdapterEnableWriteResultsEiP26IOThunderboltConfigCommand : 364 -> 368
~ __ZN28AppleThunderboltPCIUpAdapter25startUpAdapterEnableWriteEv : 940 -> 944
~ __ZN28AppleThunderboltPCIUpAdapter34processUpAdapterEnableWriteResultsEiP26IOThunderboltConfigCommand : 364 -> 368
~ __ZN28AppleThunderboltPCIUpAdapter22startPostAdapterEnableEv : 680 -> 684
~ __ZN28AppleThunderboltPCIUpAdapter17postAdapterEnableEP28IOThunderboltDispatchContext : 4612 -> 4616
~ __ZN28AppleThunderboltPCIUpAdapter14finishActivateEi : 2148 -> 2152
~ __ZN28AppleThunderboltPCIUpAdapter22deactivateDownAdaptersEv : 388 -> 392
~ __ZN28AppleThunderboltPCIUpAdapter27findUpstreamParentPCIDeviceEv : 1064 -> 1068
~ __ZN28AppleThunderboltPCIUpAdapter22findPCIChildFromDeviceEP11IOPCIDevice : 1348 -> 1352
~ __ZN28AppleThunderboltPCIUpAdapter29upstreamPCIDeviceNotificationEPvP9IOServiceP10IONotifier : 788 -> 792
~ __ZN28AppleThunderboltPCIUpAdapter19startPCICorrelationEv : 1876 -> 1880
~ __ZN28AppleThunderboltPCIUpAdapter29downAdapterActivationCompleteEP30AppleThunderboltPCIDownAdapter : 260 -> 264
~ __ZN28AppleThunderboltPCIUpAdapter14syncDeactivateEv : 628 -> 632
~ __ZN28AppleThunderboltPCIUpAdapter10deactivateEv : 220 -> 224
~ __ZN28AppleThunderboltPCIUpAdapter43startDeactivatingFindUpAdapterPCICapabilityEv : 852 -> 856
~ __ZN28AppleThunderboltPCIUpAdapter52processDeactivatingFindUpAdapterPCICapabilityResultsEiP34IOThunderboltFindCapabilityCommand : 600 -> 604
~ __ZN28AppleThunderboltPCIUpAdapter45startDeactivatingFindDownAdapterPCICapabilityEv : 892 -> 896
~ __ZN28AppleThunderboltPCIUpAdapter54processDeactivatingFindDownAdapterPCICapabilityResultsEiP34IOThunderboltFindCapabilityCommand : 760 -> 764
~ __ZN28AppleThunderboltPCIUpAdapter30startUpAdapterResetEnableWriteEv : 1072 -> 1076
~ __ZN28AppleThunderboltPCIUpAdapter39processUpAdapterResetEnableWriteResultsEiP26IOThunderboltConfigCommand : 304 -> 308
~ __ZN28AppleThunderboltPCIUpAdapter22startPreAdapterDisableEv : 788 -> 792
~ __ZN28AppleThunderboltPCIUpAdapter17preAdapterDisableEP28IOThunderboltDispatchContext : 1312 -> 1316
~ __ZN28AppleThunderboltPCIUpAdapter26startUpAdapterDisableWriteEv : 916 -> 920
~ __ZN28AppleThunderboltPCIUpAdapter35processUpAdapterDisableWriteResultsEiP26IOThunderboltConfigCommand : 304 -> 308
~ __ZN28AppleThunderboltPCIUpAdapter28startDownAdapterDisableWriteEv : 976 -> 980
~ __ZN28AppleThunderboltPCIUpAdapter37processDownAdapterDisableWriteResultsEiP26IOThunderboltConfigCommand : 304 -> 308
~ __ZN28AppleThunderboltPCIUpAdapter15deactivatePathsEv : 2432 -> 2436
~ __ZN28AppleThunderboltPCIUpAdapter24pathDeactivationCallbackEPviP25IOThunderboltAbstractPath : 832 -> 836
~ __ZN28AppleThunderboltPCIUpAdapter16finishDeactivateEi : 724 -> 728
~ __ZN28AppleThunderboltPCIUpAdapter23finishDeactivateContextEP28IOThunderboltDispatchContext : 1404 -> 1408
~ __ZN28AppleThunderboltPCIUpAdapter20setupPowerManagementEv : 464 -> 468
~ __ZN28AppleThunderboltPCIUpAdapter22destroyPowerManagementEv : 292 -> 296
~ __ZN28AppleThunderboltPCIUpAdapter13setPowerStateEmP9IOService : 1408 -> 1412
~ __ZN28AppleThunderboltPCIUpAdapter4wakeEv : 780 -> 784
~ __ZN28AppleThunderboltPCIUpAdapter5sleepEv : 376 -> 380
~ __ZN28AppleThunderboltPCIUpAdapter7unpauseEv : 264 -> 268
~ __ZN28AppleThunderboltPCIUpAdapter9lateSleepEv : 684 -> 688
~ __ZN28AppleThunderboltPCIUpAdapter9earlyWakeEv : 512 -> 516
~ __ZN28AppleThunderboltPCIUpAdapter14earlyWakeDelayEv : 960 -> 964
~ _GLOBAL__sub_I_AppleThunderboltPCIUpAdapter.cpp : 80 -> 84
~ _ZN28AppleThunderboltPCIUpAdapter16requestTerminateEP9IOServicej.cold.1 : 64 -> 68
```
