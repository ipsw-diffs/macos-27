## com.apple.driver.AppleSPMIPMU

> `com.apple.driver.AppleSPMIPMU`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

 1372.0.3.0.0
   __TEXT.__const: 0x16
   __TEXT.__cstring: 0x2c1e
-  __TEXT_EXEC.__text: 0xd5a4
+  __TEXT_EXEC.__text: 0xd7b0
   __TEXT_EXEC.__auth_stubs: 0x4d0
   __DATA.__data: 0x320
   __DATA.__common: 0xe8
Functions:
~ __ZN18AppleDialogSPMIPMU9MetaClassC1Ev : 72 -> 76
~ __ZN18AppleDialogSPMIPMUC2EPK11OSMetaClass : 124 -> 128
~ __ZN18AppleDialogSPMIPMUD0Ev : 68 -> 72
~ __ZN18AppleDialogSPMIPMU9MetaClassC2Ev : 72 -> 76
~ __ZNK18AppleDialogSPMIPMU9MetaClass5allocEv : 52 -> 56
~ __ZN18AppleDialogSPMIPMUC2Ev : 160 -> 164
~ __ZN18AppleDialogSPMIPMU5startEP9IOService : 3628 -> 3632
~ __ZN18AppleDialogSPMIPMU25_initUpsiFailureInjectionEv : 236 -> 240
~ __ZN18AppleDialogSPMIPMU16_interruptActionEP22IOInterruptEventSourcei : 192 -> 196
~ __ZN18AppleDialogSPMIPMU10_initForPMEP9IOService : 204 -> 208
~ __ZN18AppleDialogSPMIPMU19_createLpemCtrlDictEv : 1008 -> 1012
~ __ZN18AppleDialogSPMIPMU23_resetLpemInRestoreModeEv : 368 -> 372
~ __ZN18AppleDialogSPMIPMU26_checkUpsiFailureInjectionEh : 188 -> 192
~ __ZN18AppleDialogSPMIPMU20_handlePEHaltRestartEj : 256 -> 260
~ __ZN18AppleDialogSPMIPMU12publishBelowEP15IORegistryEntry : 520 -> 524
~ __ZN18AppleDialogSPMIPMU4stopEP9IOService : 112 -> 116
~ __ZN18AppleDialogSPMIPMU15updatePMSettingEhh : 356 -> 360
~ __ZN18AppleDialogSPMIPMU23handlePMSettingCallbackEPK8OSSymbolP8OSObjectm : 212 -> 216
~ __ZN18AppleDialogSPMIPMU18registerPMCallbackEv : 352 -> 356
~ __ZN18AppleDialogSPMIPMU20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 1212 -> 1216
~ __ZN26AppleDialogSPMIPMUFunctionC1Ev : 88 -> 92
~ __ZN18AppleDialogSPMIPMU8_lockBusEb : 204 -> 208
~ __ZN18AppleDialogSPMIPMU18_readConfigurationEP9IOService : 4056 -> 4060
~ __ZNK18AppleDialogSPMIPMU12copyPropertyEPKc : 140 -> 144
~ __ZN18AppleDialogSPMIPMU17copyDebugPropertyEPKc : 296 -> 300
~ __ZN18AppleDialogSPMIPMU18setDebugPropertiesEPK12OSDictionary : 504 -> 508
~ __ZN18AppleDialogSPMIPMU16_handleSpmiErrorEij : 296 -> 300
~ __ZN18AppleDialogSPMIPMU10_writeRegsEtPht : 312 -> 316
~ __ZN18AppleDialogSPMIPMU9_readRegsEtPht : 312 -> 316
~ __ZN18AppleDialogSPMIPMU6modRegEthh : 408 -> 412
~ __ZN18AppleDialogSPMIPMU9_writeMemEbtPht : 604 -> 608
~ __ZN18AppleDialogSPMIPMU8_readMemEbtPht : 604 -> 608
~ __ZN18AppleDialogSPMIPMU18_publishWakeReasonEPKcS1_ : 208 -> 212
~ __ZN18AppleDialogSPMIPMU4freeEv : 152 -> 156
~ __ZN18AppleDialogSPMIPMU13setPowerStateEmP9IOService : 292 -> 296
~ __ZN18AppleDialogSPMIPMU12_readBootKeyEhPhh : 208 -> 212
~ __ZN18AppleDialogSPMIPMU13_writeBootKeyEhPhh : 208 -> 212
~ __ZN18AppleDialogSPMIPMU13_readFaultLogEPhhb : 488 -> 492
~ __ZN18AppleDialogSPMIPMU19_readOff2WakeSourceEPhhb : 268 -> 272
~ __ZN18AppleDialogSPMIPMU13setPropertiesEP8OSObject : 4408 -> 4412
~ __ZN18AppleDialogSPMIPMU13_setLpemStateEhhhhhhh : 428 -> 432
~ __ZN18AppleDialogSPMIPMU21_setLpemBluetoothFWOKEh : 368 -> 372
~ __ZN18AppleDialogSPMIPMU21_updateBootPropertiesEb : 2604 -> 2608
~ __ZN18AppleDialogSPMIPMU13_getLpemStateEPhS0_S0_ : 192 -> 196
~ __ZN18AppleDialogSPMIPMU28_updateLpemLogDataPropertiesEPh : 276 -> 280
~ __ZN18AppleDialogSPMIPMU13_lpemCtrlDictEhhhhhhh : 828 -> 832
~ __ZN18AppleDialogSPMIPMU21_populateSOCDPropertyEv : 524 -> 528
~ __ZN18AppleDialogSPMIPMU17_writeLpemLogDataEv : 496 -> 500
~ __ZN18AppleDialogSPMIPMU21_getLpemBluetoothFWOKEPh : 132 -> 136
~ __ZN18AppleDialogSPMIPMU21_updateFaultRegistersEb : 1424 -> 1428
~ __ZN18AppleDialogSPMIPMU30_updateOff2WakeSourceRegistersEv : 1328 -> 1332
~ __ZN18AppleDialogSPMIPMU9_clearUPOEv : 80 -> 84
~ __ZN18AppleDialogSPMIPMU14_shutdownGatedEv : 2436 -> 2440
~ __ZN18AppleDialogSPMIPMU9_shutdownEj : 316 -> 320
~ __ZN18AppleDialogSPMIPMU14_enterTestModeEv : 148 -> 152
~ __ZN18AppleDialogSPMIPMU13_exitTestModeEv : 148 -> 152
~ __ZN26AppleDialogSPMIPMUFunction9MetaClassC1Ev : 72 -> 76
~ __ZN26AppleDialogSPMIPMUFunctionC2EPK11OSMetaClass : 52 -> 56
~ __ZN26AppleDialogSPMIPMUFunctionC1EPK11OSMetaClass : 52 -> 56
~ __ZN26AppleDialogSPMIPMUFunctionD0Ev : 68 -> 72
~ __ZN26AppleDialogSPMIPMUFunction9MetaClassC2Ev : 72 -> 76
~ __ZNK26AppleDialogSPMIPMUFunction9MetaClass5allocEv : 104 -> 108
~ __ZN26AppleDialogSPMIPMUFunctionC2Ev : 88 -> 92
~ __ZN26AppleDialogSPMIPMUFunction12callFunctionEPvS0_S0_ : 484 -> 488
~ __ZN26AppleDialogSPMIPMUFunction27initWithTargetDataAndSymbolEP9IOServicePK6OSDataPK8OSSymbol : 276 -> 280
~ _GLOBAL__sub_I_AppleDialogSPMIPMU.cpp : 360 -> 364
~ __GLOBAL__D_a : 56 -> 60
~ __ZN22AppleDialogSPMIPMUSOCD23readInvalidateSOCDMagicEP6OSDataRtS2_Rh : 344 -> 348
~ __ZN22AppleDialogSPMIPMUSOCD12readAndClearEP6OSDataRtS2_tPPh : 472 -> 476
~ __ZN22AppleDialogSPMIPMUSOCD8readDataEP6OSDataRtS2_tPPh : 352 -> 356
~ __ZN22AppleDialogSPMIPMUSOCD23readInvalidateMutexesV1EP6OSDataRtS2_ : 188 -> 192
~ __ZN22AppleDialogSPMIPMUSOCD19readContainerDataV0EP6OSDataRtS2_ : 300 -> 304
~ __ZN22AppleDialogSPMIPMUSOCD19readContainerDataV1EP6OSDataRtS2_ : 292 -> 296
~ __ZN22AppleDialogSPMIPMUSOCD17getSOCDContainersEP7OSArray : 492 -> 496
~ __ZN21AppleDialogSPMIPMURTC9MetaClassC1Ev : 72 -> 76
~ __ZN21AppleDialogSPMIPMURTCC2EPK11OSMetaClass : 56 -> 60
~ __ZN21AppleDialogSPMIPMURTCC1EPK11OSMetaClass : 56 -> 60
~ __ZN21AppleDialogSPMIPMURTCD0Ev : 68 -> 72
~ __ZN21AppleDialogSPMIPMURTC9MetaClassC2Ev : 72 -> 76
~ __ZNK21AppleDialogSPMIPMURTC9MetaClass5allocEv : 108 -> 112
~ __ZN21AppleDialogSPMIPMURTCC1Ev : 92 -> 96
~ __ZN21AppleDialogSPMIPMURTCC2Ev : 92 -> 96
~ __ZN21AppleDialogSPMIPMURTC11handleStartEP9IOService : 1952 -> 1956
~ __ZN21AppleDialogSPMIPMURTC21_sysctlSecondsHandlerEP10sysctl_oidPviP10sysctl_req : 108 -> 112
~ __ZN21AppleDialogSPMIPMURTC26_sysctlMicrosecondsHandlerEP10sysctl_oidPviP10sysctl_req : 368 -> 372
~ __ZN21AppleDialogSPMIPMURTC20_sysctlOffsetHandlerEP10sysctl_oidPviP10sysctl_req : 288 -> 292
~ __ZN21AppleDialogSPMIPMURTC16_smcNotificationEPK8OSSymbolP8OSObjectm : 492 -> 496
~ __ZN21AppleDialogSPMIPMURTC22_handleSMCNotificationEPv : 196 -> 200
~ __ZN21AppleDialogSPMIPMURTC25_sysctlNVRAMOffsetHandlerEP10sysctl_oidPviP10sysctl_req : 324 -> 328
~ __ZN21AppleDialogSPMIPMURTC18_readConfigurationEP9IOService : 1616 -> 1620
~ __ZN21AppleDialogSPMIPMURTC23_readCurrentOffsetTicksEPx : 492 -> 496
~ __ZN21AppleDialogSPMIPMURTC24_writeCurrentOffsetTicksEx : 284 -> 288
~ __ZN21AppleDialogSPMIPMURTC24_writeClockOffsetToNVRAMEx : 168 -> 172
~ __ZN17PMURTCNVRAMHelper14nvramWriteSI64Exb : 392 -> 396
~ __ZN21AppleDialogSPMIPMURTC20_setClockOffsetTicksEx : 184 -> 188
~ __ZN21AppleDialogSPMIPMURTC20_getClockOffsetTicksEv : 88 -> 92
~ __ZN21AppleDialogSPMIPMURTC15_getClockOffsetEv : 108 -> 112
~ __ZN21AppleDialogSPMIPMURTC14_handleSyncRTCEPyS0_ : 152 -> 156
~ __ZN17PMURTCNVRAMHelper13nvramReadSI64EPx : 700 -> 704
~ __ZN21AppleDialogSPMIPMURTC15getUTCTimeOfDayEPmPj : 180 -> 184
~ __ZN21AppleDialogSPMIPMURTC15setUTCTimeOfDayEmj : 120 -> 124
~ __ZN21AppleDialogSPMIPMURTC15programRTCAlarmEj : 612 -> 616
~ __ZN21AppleDialogSPMIPMURTC19enableDateTimeAlarmEPK11RTCDateTime : 132 -> 136
~ __ZN21AppleDialogSPMIPMURTC14readRTCUpcountEv : 60 -> 64
~ __ZN21AppleDialogSPMIPMURTC20_readRTCUpcountTicksEv : 856 -> 860
~ __ZN21AppleDialogSPMIPMURTC20scheduleRTCWakeAlarmEb : 416 -> 420
~ __ZN21AppleDialogSPMIPMURTC20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 236 -> 240
~ __ZN21AppleDialogSPMIPMURTC17checkRTCWakeEventEv : 128 -> 132
~ __ZN17PMURTCNVRAMHelper9_getNVRAMEv : 116 -> 120
~ _GLOBAL__sub_I_AppleDialogSPMIPMURTC.cpp : 80 -> 84
~ __ZN21AppleDialogSPMIPMUNub9MetaClassC1Ev : 72 -> 76
~ __ZN21AppleDialogSPMIPMUNubC2EPK11OSMetaClass : 52 -> 56
~ __ZN21AppleDialogSPMIPMUNubC1EPK11OSMetaClass : 52 -> 56
~ __ZN21AppleDialogSPMIPMUNubD0Ev : 68 -> 72
~ __ZN21AppleDialogSPMIPMUNub9MetaClassC2Ev : 72 -> 76
~ __ZNK21AppleDialogSPMIPMUNub9MetaClass5allocEv : 104 -> 108
~ __ZN21AppleDialogSPMIPMUNubC1Ev : 88 -> 92
~ __ZN21AppleDialogSPMIPMUNubC2Ev : 88 -> 92
~ __ZN21AppleDialogSPMIPMUNub5startEP9IOService : 172 -> 176
~ __ZNK21AppleDialogSPMIPMUNub11compareNameEP8OSStringPS1_ : 128 -> 132
~ __ZN21AppleDialogSPMIPMUNub8readRegsEtPhh : 200 -> 204
~ __ZN21AppleDialogSPMIPMUNub9writeRegsEtPhh : 200 -> 204
~ _GLOBAL__sub_I_AppleDialogSPMIPMUNub.cpp : 80 -> 84
~ _ZN18AppleDialogSPMIPMU20_handlePEHaltRestartEj.cold.1 : 124 -> 128
~ _ZN18AppleDialogSPMIPMU20_handlePEHaltRestartEj.cold.2 : 196 -> 200
~ _ZN18AppleDialogSPMIPMU28_updateLpemLogDataPropertiesEPh.cold.1 : 44 -> 48
~ _ZN18AppleDialogSPMIPMU14_shutdownGatedEv.cold.1 : 44 -> 48
~ _ZN18AppleDialogSPMIPMU14_shutdownGatedEv.cold.2 : 44 -> 48
~ _ZN18AppleDialogSPMIPMU14_shutdownGatedEv.cold.3 : 212 -> 216
~ __ZN21AppleDialogSPMIPMURTC18getCurrentDateTimeEP11RTCDateTime : 44 -> 48
~ __ZN21AppleDialogSPMIPMURTC18setCurrentDateTimeEPK11RTCDateTime : 44 -> 48
CStrings:
+ "%s::handleStart: %s _pmuNub: %p ** configuration not found ** built 18:51:20 Aug 30 2026\n"
+ "%s::handleStart: ro=%d nvram=%d helper=%d %s _pmuNub: %p 0x%04x:0x%04x-0x%04x built 18:51:20 Aug 30 2026\n"
+ "%s::start: %s _pmuNub: %p ** configuration not found ** built 18:51:21 Aug 30 2026\n"
+ "%s::start: %s _pmuNub: %p built 18:51:21 Aug 30 2026\n"
- "%s::handleStart: %s _pmuNub: %p ** configuration not found ** built 21:39:19 Aug 11 2026\n"
- "%s::handleStart: ro=%d nvram=%d helper=%d %s _pmuNub: %p 0x%04x:0x%04x-0x%04x built 21:39:19 Aug 11 2026\n"
- "%s::start: %s _pmuNub: %p ** configuration not found ** built 21:39:20 Aug 11 2026\n"
- "%s::start: %s _pmuNub: %p built 21:39:20 Aug 11 2026\n"
```
