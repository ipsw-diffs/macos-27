## com.apple.driver.AppleIISController

> `com.apple.driver.AppleIISController`

```diff

 600.3.0.0.0
   __TEXT.__cstring: 0x9de
   __TEXT.__os_log: 0x436
-  __TEXT_EXEC.__text: 0x8300
+  __TEXT_EXEC.__text: 0x8480
   __TEXT_EXEC.__auth_stubs: 0x2f0
   __DATA.__data: 0x188
   __DATA.__common: 0x100
Functions:
~ __ZN21AppleARMIISController9MetaClassC1Ev : 72 -> 76
~ __ZN21AppleARMIISControllerC2EPK11OSMetaClass : 60 -> 64
~ __ZN21AppleARMIISController9MetaClassC2Ev : 72 -> 76
~ __ZN21AppleARMIISController5startEP9IOService : 2264 -> 2268
~ __ZN21AppleARMIISController18addIISJournalEntryENS_10IISJournal9IISEventsEi : 160 -> 164
~ __ZN21AppleARMIISController9initForPMEP9IOService : 204 -> 208
~ __ZN21AppleARMIISController13setPowerStateEmP9IOService : 292 -> 296
~ __ZNK21AppleARMIISController14compareNubNameEPK9IOServiceP8OSStringPS4_ : 140 -> 144
~ __ZN21AppleARMIISController4freeEv : 192 -> 196
~ __ZN21AppleARMIISController15updateIISConfigEP17AppleARMIISDevice : 264 -> 268
~ __ZN21AppleARMIISController22enqueueIISCommandGatedEP17AppleARMIISDevicejP18AppleARMIISCommand : 3176 -> 3180
~ __ZN21AppleARMIISController18completeIISCommandEP18AppleARMIISCommand : 1580 -> 1584
~ __ZN21AppleARMIISController20completeIISNoCommandEv : 276 -> 280
~ __ZN18AppleARMIISCommand14withControllerEP21AppleARMIISController : 220 -> 224
~ __ZN17AppleARMIISDevice17withRegistryEntryEP15IORegistryEntryP9IOService : 228 -> 232
~ __ZN21AppleARMIISController12publishBelowEP15IORegistryEntry : 388 -> 392
~ __ZN21AppleARMIISController4initEP15IORegistryEntryPK15IORegistryPlane : 80 -> 84
~ __ZN21AppleARMIISController4initEP12OSDictionary : 232 -> 236
~ __ZN21AppleARMIISController25getSupportedChannelCountsEP17AppleARMIISConfigj : 120 -> 124
~ __ZN21AppleARMIISController15configureReportEP19IOReportChannelListjPvS2_ : 288 -> 292
~ __ZN21AppleARMIISController12updateReportEP19IOReportChannelListjPvS2_ : 288 -> 292
~ __ZN21AppleARMIISController15createReportersEv : 52 -> 56
~ __ZN21AppleARMIISController16destroyReportersEv : 72 -> 76
~ __ZN17AppleARMIISDevice9MetaClassC1Ev : 72 -> 76
~ __ZN17AppleARMIISDeviceC2EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleARMIISDeviceC1EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleARMIISDeviceD0Ev : 68 -> 72
~ __ZN17AppleARMIISDevice9MetaClassC2Ev : 72 -> 76
~ __ZNK17AppleARMIISDevice9MetaClass5allocEv : 104 -> 108
~ __ZN17AppleARMIISDeviceC1Ev : 88 -> 92
~ __ZN17AppleARMIISDeviceC2Ev : 88 -> 92
~ __ZN17AppleARMIISDevice12setIISConfigEP17AppleARMIISConfig : 424 -> 428
~ __ZN17AppleARMIISDevice14validIISConfigEP17AppleARMIISConfig : 404 -> 408
~ __ZN17AppleARMIISDevice12transferDataEP18IOMemoryDescriptorjyyP21AppleARMIISCompletionPK13mach_timespec : 1104 -> 1108
~ __ZNK17AppleARMIISDevice11compareNameEP8OSStringPS1_ : 128 -> 132
~ __ZN17AppleARMIISDevice12setIISMasterEb : 104 -> 108
~ __ZN17AppleARMIISDevice16setMCLKFrequencyEy : 364 -> 368
~ __ZN17AppleARMIISDevice15setChannelCountEjj : 128 -> 132
~ __ZN17AppleARMIISDevice17setBitsPerChannelEjj : 104 -> 108
~ __ZN17AppleARMIISDevice14setBitsPerSlotEjj : 104 -> 108
~ __ZNK17AppleARMIISDevice12getBCLKCountEv : 108 -> 112
~ __ZNK17AppleARMIISDevice18getSyncEdgeFallingEv : 76 -> 80
~ __ZNK17AppleARMIISDevice18getDataEdgeFallingEj : 124 -> 128
~ __ZN17AppleARMIISDevice21initWithRegistryEntryEP15IORegistryEntryP9IOService : 1056 -> 1060
~ __ZN18AppleARMIISCommand9MetaClassC1Ev : 72 -> 76
~ __ZN18AppleARMIISCommandC2EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleARMIISCommandC1EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleARMIISCommandD0Ev : 68 -> 72
~ __ZN18AppleARMIISCommand9MetaClassC2Ev : 72 -> 76
~ __ZNK18AppleARMIISCommand9MetaClass5allocEv : 104 -> 108
~ __ZN18AppleARMIISCommandC1Ev : 88 -> 92
~ __ZN18AppleARMIISCommandC2Ev : 88 -> 92
~ __ZN18AppleARMIISCommand18initWithControllerEP21AppleARMIISController : 260 -> 264
~ _GLOBAL__sub_I_AppleARMIIS.cpp : 208 -> 212
~ __GLOBAL__D_a : 68 -> 72
~ __ZN24AppleARMFunctionIISRoute9MetaClassC1Ev : 72 -> 76
~ __ZN24AppleARMFunctionIISRouteC2EPK11OSMetaClass : 52 -> 56
~ __ZN24AppleARMFunctionIISRouteC1EPK11OSMetaClass : 52 -> 56
~ __ZN24AppleARMFunctionIISRouteD0Ev : 68 -> 72
~ __ZN24AppleARMFunctionIISRoute9MetaClassC2Ev : 72 -> 76
~ __ZNK24AppleARMFunctionIISRoute9MetaClass5allocEv : 104 -> 108
~ __ZN24AppleARMFunctionIISRouteC1Ev : 88 -> 92
~ __ZN24AppleARMFunctionIISRouteC2Ev : 88 -> 92
~ __ZN24AppleARMFunctionIISRoute12withProviderEP9IOServicePKc : 96 -> 100
~ __ZN24AppleARMFunctionIISRoute12withProviderEP9IOServicePK8OSSymbol : 96 -> 100
~ __ZN24AppleARMFunctionIISRoute27initWithTargetDataAndSymbolEP9IOServicePK6OSDataPK8OSSymbol : 164 -> 168
~ __ZN24AppleARMFunctionIISRoute11enableRouteEjj : 80 -> 84
~ __ZN17AppleARMIISSwitch15connectI2SPortsEjjjjjjjjbPj : 1468 -> 1472
~ __ZNK24AppleARMFunctionIISRoute14getClockDomainEj : 284 -> 288
~ __ZN25AppleARMFunctionIISActive9MetaClassC1Ev : 72 -> 76
~ __ZN25AppleARMFunctionIISActiveC2EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleARMFunctionIISActiveC1EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleARMFunctionIISActiveD0Ev : 68 -> 72
~ __ZN25AppleARMFunctionIISActive9MetaClassC2Ev : 72 -> 76
~ __ZNK25AppleARMFunctionIISActive9MetaClass5allocEv : 104 -> 108
~ __ZN25AppleARMFunctionIISActiveC1Ev : 88 -> 92
~ __ZN25AppleARMFunctionIISActiveC2Ev : 88 -> 92
~ __ZN25AppleARMFunctionIISActive12withProviderEP9IOServicePKc : 96 -> 100
~ __ZN25AppleARMFunctionIISActive12withProviderEP9IOServicePK8OSSymbol : 96 -> 100
~ __ZN25AppleARMFunctionIISActive27initWithTargetDataAndSymbolEP9IOServicePK6OSDataPK8OSSymbol : 604 -> 608
~ __ZN25AppleARMFunctionIISActive4freeEv : 112 -> 116
~ __ZN17AppleARMIISSwitch9MetaClassC1Ev : 72 -> 76
~ __ZN17AppleARMIISSwitchC2EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleARMIISSwitch9MetaClassC2Ev : 72 -> 76
~ __ZN17AppleARMIISSwitch5startEP9IOService : 948 -> 952
~ __ZN17AppleARMIISSwitch4freeEv : 244 -> 248
~ __ZN17AppleARMIISSwitch20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 560 -> 564
~ __ZNK17AppleARMIISSwitch20copyRouteDescriptionEjjjjj : 248 -> 252
~ __ZNK17AppleARMIISSwitch20copyRouteDescriptionEPK8OSStringS2_jjj : 540 -> 544
~ __ZNK17AppleARMIISSwitch15_connectObjectsEjjPKNS_9ChangeSetEPjS3_S3_P7OSArrayS5_b : 2880 -> 2884
~ __ZNK17AppleARMIISSwitch15_connectObjectsEjjjjPjS0_ : 332 -> 336
~ __ZNK17AppleARMIISSwitch15_makeConnectionENS_14ConnectionTypeEjjPjS1_ : 624 -> 628
~ __ZNK17AppleARMIISSwitch18getActiveDirectionEjj : 384 -> 388
~ _GLOBAL__sub_I_AppleARMIISSwitch.cpp : 248 -> 252
~ __GLOBAL__D_a : 68 -> 72
~ _ZN17AppleARMIISSwitch5startEP9IOService.cold.1 : 164 -> 168
```
