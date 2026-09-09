## com.apple.driver.AppleBluetoothModule

> `com.apple.driver.AppleBluetoothModule`

```diff

 77.0.0.0.0
   __TEXT.__const: 0x20
   __TEXT.__cstring: 0x26a4
-  __TEXT_EXEC.__text: 0x7cf8
+  __TEXT_EXEC.__text: 0x7e78
   __TEXT_EXEC.__auth_stubs: 0x3d0
   __DATA.__data: 0x188
   __DATA.__common: 0x60
Functions:
~ __ZN20AppleBluetoothModule9MetaClassC1Ev : 72 -> 76
~ __ZN20AppleBluetoothModuleC2EPK11OSMetaClass : 52 -> 56
~ __ZN20AppleBluetoothModuleC1EPK11OSMetaClass : 52 -> 56
~ __ZN20AppleBluetoothModuleD0Ev : 68 -> 72
~ __ZN20AppleBluetoothModule9MetaClassC2Ev : 72 -> 76
~ __ZNK20AppleBluetoothModule9MetaClass5allocEv : 104 -> 108
~ __ZN20AppleBluetoothModuleC1Ev : 88 -> 92
~ __ZN20AppleBluetoothModuleC2Ev : 88 -> 92
~ __ZN20AppleBluetoothModule5startEP9IOService : 2392 -> 2396
~ __ZN20AppleBluetoothModule15initCoreCaptureE16CCStreamLogLevelS0_ : 552 -> 556
~ __ZN20AppleBluetoothModule13setupTimeSyncEP9IOService : 404 -> 408
~ __ZN20AppleBluetoothModule19amfmServiceNotifierEPvP9IOServiceP10IONotifier : 1064 -> 1068
~ __ZN20AppleBluetoothModule23interruptActionTimeSyncEP22IOInterruptEventSourcei : 260 -> 264
~ __ZN20AppleBluetoothModule23interruptFilterTimeSyncEP28IOFilterInterruptEventSource : 84 -> 88
~ __ZN20AppleBluetoothModule18isPCIDriverInResetEv : 152 -> 156
~ __ZN20AppleBluetoothModule13willTerminateEP9IOServicej : 152 -> 156
~ __ZN20AppleBluetoothModule4stopEP9IOService : 988 -> 992
~ __ZN20AppleBluetoothModule11waitForIdleEb : 152 -> 156
~ __ZN20AppleBluetoothModule9sendStatsE27AppleBluetoothStatisticTypey : 96 -> 100
~ __ZN20AppleBluetoothModule12quiesceGatedEv : 416 -> 420
~ __ZN20AppleBluetoothModule14unquiesceGatedEv : 384 -> 388
~ __ZN20AppleBluetoothModule11resetWorkerEv : 156 -> 160
~ __ZN20AppleBluetoothModule31setInitialModulePowerStateGatedEv : 380 -> 384
~ __ZL18moduleOnThreadCallPvS_ : 116 -> 120
~ __ZN20AppleBluetoothModule22powerStateWillChangeToEmmP9IOService : 416 -> 420
~ __ZN20AppleBluetoothModule27powerStateWillChangeToGatedEmmP9IOService : 348 -> 352
~ __ZN20AppleBluetoothModule13setPowerStateEmP9IOService : 292 -> 296
~ __ZN20AppleBluetoothModule18setPowerStateGatedEmP9IOService : 520 -> 524
~ __ZN20AppleBluetoothModule20claimAOTExitIfBTWakeEv : 812 -> 816
~ __ZN20AppleBluetoothModule14coredumpModuleEPKc : 280 -> 284
~ __ZN20AppleBluetoothModule15generateMacAddrEP17IOEthernetAddress : 184 -> 188
~ __ZN20AppleBluetoothModule11generateMacEPKc : 280 -> 284
~ __ZN20AppleBluetoothModule16generateMacGatedEPKc : 508 -> 512
~ __ZN20AppleBluetoothModule16pciDriverBlockerEv : 276 -> 280
~ __ZN20AppleBluetoothModule21pciDriverBlockerGatedEv : 808 -> 812
~ __ZN20AppleBluetoothModule25notifyPCIDeviceTransitionEb : 280 -> 284
~ __ZN20AppleBluetoothModule3flrEPKc : 280 -> 284
~ __ZN20AppleBluetoothModule8flrGatedEPKc : 1208 -> 1212
~ __ZN20AppleBluetoothModule11powerModuleEbPKc : 292 -> 296
~ __ZN20AppleBluetoothModule16powerModuleGatedEbPKc : 860 -> 864
~ __ZN20AppleBluetoothModule16powerCycleModuleEPKc : 280 -> 284
~ __ZN20AppleBluetoothModule21powerCycleModuleGatedEPKc : 1468 -> 1472
~ __ZN20AppleBluetoothModule17waitForWiFiDriverEv : 488 -> 492
~ __ZN20AppleBluetoothModule13deepSleepVoteEb : 276 -> 280
~ __ZN20AppleBluetoothModule13setPropertiesEP8OSObject : 2040 -> 2044
~ __ZN20AppleBluetoothModule20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 624 -> 628
~ __ZN20AppleBluetoothModule14copyPrimaryPMUEv : 356 -> 360
~ __ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm : 5436 -> 5440
~ _GLOBAL__sub_I_AppleBluetoothModule.cpp : 80 -> 84
~ __ZN30AppleBluetoothModuleUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN30AppleBluetoothModuleUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN30AppleBluetoothModuleUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN30AppleBluetoothModuleUserClientD0Ev : 68 -> 72
~ __ZN30AppleBluetoothModuleUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK30AppleBluetoothModuleUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN30AppleBluetoothModuleUserClientC1Ev : 88 -> 92
~ __ZN30AppleBluetoothModuleUserClientC2Ev : 88 -> 92
~ __ZN30AppleBluetoothModuleUserClient5startEP9IOService : 176 -> 180
~ __ZN30AppleBluetoothModuleUserClient11clientCloseEv : 148 -> 152
~ __ZN30AppleBluetoothModuleUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 332 -> 336
~ __ZN30AppleBluetoothModuleUserClient4openEP20AppleBluetoothModuleP9IOServiceP25IOExternalMethodArguments : 80 -> 84
~ __ZN30AppleBluetoothModuleUserClient5closeEP20AppleBluetoothModuleP9IOServiceP25IOExternalMethodArguments : 140 -> 144
~ _GLOBAL__sub_I_AppleBluetoothModuleUserClient.cpp : 80 -> 84
~ _ZN20AppleBluetoothModule4stopEP9IOService.cold.1 : 24 -> 28
~ _ZN20AppleBluetoothModule21pciDriverBlockerGatedEv.cold.1 : 44 -> 48
~ _ZN20AppleBluetoothModule8flrGatedEPKc.cold.1 : 44 -> 48
~ _ZN20AppleBluetoothModule8flrGatedEPKc.cold.2 : 24 -> 28
~ _ZN20AppleBluetoothModule8flrGatedEPKc.cold.3 : 24 -> 28
~ _ZN20AppleBluetoothModule21powerCycleModuleGatedEPKc.cold.1 : 44 -> 48
~ _ZN20AppleBluetoothModule21powerCycleModuleGatedEPKc.cold.2 : 44 -> 48
~ _ZN20AppleBluetoothModule21powerCycleModuleGatedEPKc.cold.3 : 24 -> 28
~ _ZN20AppleBluetoothModule21powerCycleModuleGatedEPKc.cold.4 : 24 -> 28
~ _ZN20AppleBluetoothModule17waitForWiFiDriverEv.cold.1 : 24 -> 28
~ _ZN20AppleBluetoothModule17waitForWiFiDriverEv.cold.2 : 24 -> 28
~ _ZN20AppleBluetoothModule13setPropertiesEP8OSObject.cold.1 : 44 -> 48
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.1 : 44 -> 48
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.2 : 80 -> 84
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.3 : 44 -> 48
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.4 : 44 -> 48
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.5 : 24 -> 28
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.6 : 44 -> 48
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.7 : 44 -> 48
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.8 : 24 -> 28
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.9 : 44 -> 48
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.10 : 24 -> 28
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.11 : 24 -> 28
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.12 : 24 -> 28
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.13 : 44 -> 48
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.14 : 44 -> 48
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.15 : 24 -> 28
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.16 : 24 -> 28
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.17 : 44 -> 48
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.18 : 44 -> 48
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.19 : 24 -> 28
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.20 : 24 -> 28
~ _ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.21 : 44 -> 48
```
