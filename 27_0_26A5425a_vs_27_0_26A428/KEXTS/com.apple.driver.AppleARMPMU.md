## com.apple.driver.AppleARMPMU

> `com.apple.driver.AppleARMPMU`

```diff

 1150.0.1.0.0
   __TEXT.__const: 0x64
   __TEXT.__cstring: 0x2d9b
-  __TEXT_EXEC.__text: 0x159c4
+  __TEXT_EXEC.__text: 0x15c18
   __TEXT_EXEC.__auth_stubs: 0x6e0
   __DATA.__data: 0x1e8
   __DATA.__common: 0x148
Functions:
~ __ZN18AppleARMPMUCharger9MetaClassC1Ev : 72 -> 76
~ __ZN18AppleARMPMUChargerC2EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleARMPMUChargerC1EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleARMPMUChargerD0Ev : 68 -> 72
~ __ZN18AppleARMPMUCharger9MetaClassC2Ev : 72 -> 76
~ __ZNK18AppleARMPMUCharger9MetaClass5allocEv : 104 -> 108
~ __ZN18AppleARMPMUChargerC1Ev : 88 -> 92
~ __ZN18AppleARMPMUChargerC2Ev : 88 -> 92
~ __ZN18AppleARMPMUCharger5startEP9IOService : 1080 -> 1084
~ __ZN18AppleARMPMUCharger15createReportersEv : 1304 -> 1308
~ __ZN18AppleARMPMUCharger16handleStartGatedEbb : 7472 -> 7476
~ __ZN23AppleARMFunctionCharger12withProviderEP9IOServicePKc : 96 -> 100
~ __ZN18AppleARMPMUCharger17causeChargerEventEP23AppleARMFunctionChargerj : 500 -> 504
~ __ZN18AppleARMPMUCharger19uiUpdateTimerActionEP18IOTimerEventSource : 292 -> 296
~ __ZN18AppleARMPMUCharger16chargeTimerEventEP18IOTimerEventSource : 96 -> 100
~ __ZN18AppleARMPMUCharger28resetCurrentLimitTimerActionEP18IOTimerEventSource : 160 -> 164
~ __ZN18AppleARMPMUCharger16ggEOCTimerActionEP18IOTimerEventSource : 284 -> 288
~ __ZN18AppleARMPMUCharger21forceUiSocTimerActionEP18IOTimerEventSource : 280 -> 284
~ __ZN18AppleARMPMUCharger25enableChargerEventsActionEP23AppleARMFunctionChargerPb : 300 -> 304
~ __ZN18AppleARMPMUCharger8postInitEv : 388 -> 392
~ __ZN18AppleARMPMUCharger19handleSetPowerStateEb : 384 -> 388
~ __ZN18AppleARMPMUCharger42copyAndSetAdapterDetailFromChargerFunctionEP23AppleARMFunctionChargerPKc : 468 -> 472
~ __ZN18AppleARMPMUCharger22chargerInterruptActionEP23AppleARMFunctionChargerPv : 360 -> 364
~ __ZN18AppleARMPMUCharger21inputCurrentLimitStepEv : 376 -> 380
~ __ZN18AppleARMPMUCharger18gatedSetPropertiesEP8OSObject : 12940 -> 12944
~ __ZN18AppleARMPMUCharger20setChargerPropertiesEP23AppleARMFunctionChargerP12OSDictionary : 1272 -> 1276
~ __ZN18AppleARMPMUCharger13posmState2PmuEh : 308 -> 312
~ __ZN18AppleARMPMUCharger20DisplayCapacityCurve30createReplacementCapacityCurveEffbffb : 608 -> 616
~ __ZNK18AppleARMPMUCharger23copyBatteryVoltageArrayEbi : 876 -> 880
~ __ZNK18AppleARMPMUCharger25copyChargerBatteryVoltageEP23AppleARMFunctionChargerb : 164 -> 168
~ __ZNK18AppleARMPMUCharger12copyPropertyEPKc : 812 -> 816
~ __ZN18AppleARMPMUCharger18resetUSBInputLimitEjb : 132 -> 136
~ __ZNK18AppleARMPMUCharger18invokeDockChargersIbEEvjMS_KFvP23AppleARMFunctionChargerT_ES3_ : 420 -> 424
~ __ZN18AppleARMPMUCharger16copyDetectStatusEjb : 256 -> 260
~ __ZN18AppleARMPMUCharger21getDetectStatusActionEP23AppleARMFunctionChargerPNS_26GetDetectStatusActionParamE : 208 -> 212
~ __ZN18AppleARMPMUCharger14getChargeLimitEPj : 2580 -> 2584
~ __ZN18AppleARMPMUCharger21DisplayCapacityFilter17_clock_get_uptimeEv : 244 -> 248
~ __ZN18AppleARMPMUCharger19handleUSBInputFlagsEjPbS0_ : 656 -> 660
~ __ZN18AppleARMPMUCharger25handleUSBInputFlagsActionEP23AppleARMFunctionChargerPNS_24HandleUSBInputFlagsParamE : 660 -> 664
~ __ZN18AppleARMPMUCharger10setChargerEPKijbPb : 1840 -> 1844
~ __ZNK18AppleARMPMUCharger17getCurrentUpcountEv : 80 -> 84
~ __ZN18AppleARMPMUCharger18invokeDockChargersIPvEEvjMS_FvP23AppleARMFunctionChargerT_ES4_ : 404 -> 408
~ __ZN18AppleARMPMUCharger28setChargerCurrentLimitActionEP23AppleARMFunctionChargerPNS_33SetChargerCurrentLimitActionParamE : 296 -> 300
~ __ZNK18AppleARMPMUCharger31chargerInputConfigurationActionEP23AppleARMFunctionChargerPj : 320 -> 324
~ __ZNK18AppleARMPMUCharger24copyChargerConfigurationEP23AppleARMFunctionChargerj : 136 -> 140
~ __ZN18AppleARMPMUCharger21setChargerHighVoltageEjj : 272 -> 276
~ __ZN18AppleARMPMUCharger19setChargerHvcActionEP23AppleARMFunctionChargerj : 324 -> 328
~ __ZN18AppleARMPMUCharger27inputCurrentLimitStepActionEP23AppleARMFunctionChargerPy : 1740 -> 1744
~ __ZN18AppleARMPMUCharger30resetCurrentLimitChargerActionEP23AppleARMFunctionChargerPb : 256 -> 260
~ __ZN18AppleARMPMUCharger12startChargerEv : 444 -> 448
~ __ZN18AppleARMPMUCharger15measureCapacityEbj : 2224 -> 2228
~ __ZN18AppleARMPMUCharger12chargingWorkEb : 644 -> 648
~ __ZN18AppleARMPMUCharger18invokeDockChargersIPbEEvjMS_FvP23AppleARMFunctionChargerT_ES4_ : 420 -> 424
~ __ZN18AppleARMPMUCharger24updateChargeStatusActionEP23AppleARMFunctionChargerPb : 2360 -> 2364
~ __ZN18AppleARMPMUCharger17checkHvcSelectionEv : 672 -> 676
~ __ZN23AppleARMFunctionCharger9MetaClassC1Ev : 72 -> 76
~ __ZN23AppleARMFunctionChargerC2EPK11OSMetaClass : 52 -> 56
~ __ZN23AppleARMFunctionCharger9MetaClassC2Ev : 72 -> 76
~ __ZN23AppleARMFunctionCharger12withProviderEP9IOServicePK8OSSymbol : 96 -> 100
~ __ZN26AppleARMFunctionChargerMux9MetaClassC1Ev : 72 -> 76
~ __ZN26AppleARMFunctionChargerMuxC2EPK11OSMetaClass : 52 -> 56
~ __ZN26AppleARMFunctionChargerMux9MetaClassC2Ev : 72 -> 76
~ __ZN26AppleARMFunctionChargerMux24enableChargerStatusEventEb : 132 -> 136
~ __ZN26AppleARMFunctionChargerMux29enablePowerSupplyLimitedEventEb : 132 -> 136
~ __ZN26AppleARMFunctionChargerMux18getUSBPowerLimitedEv : 184 -> 188
~ __ZN26AppleARMFunctionChargerMux15getChargerStateEPbS0_S0_PPKc : 256 -> 260
~ __ZN26AppleARMFunctionChargerMux23setUSBInputCurrentLimitEjPb : 216 -> 220
~ __ZN26AppleARMFunctionChargerMux33getUSBInputCurrentLimitTargetInfoEjPjS0_ : 228 -> 232
~ __ZN26AppleARMFunctionChargerMux26getUSBInputCurrentLimitMaxEv : 116 -> 120
~ __ZN26AppleARMFunctionChargerMux27getUSBInputCurrentLimitStepEjjj : 156 -> 160
~ __ZN26AppleARMFunctionChargerMux22setUSBInputHighVoltageEbj : 228 -> 232
~ __ZN26AppleARMFunctionChargerMux21setChargeCurrentLimitEbjPj : 224 -> 228
~ __ZN26AppleARMFunctionChargerMux16resetChargeTimerEv : 184 -> 188
~ __ZN26AppleARMFunctionChargerMux16resetEndOfChargeEj : 192 -> 196
~ __ZN26AppleARMFunctionChargerMux21setChargeVoltageLimitEj : 192 -> 196
~ __ZN26AppleARMFunctionChargerMux29getChargeCurrentConfigurationEv : 184 -> 188
~ __ZN26AppleARMFunctionChargerMux29getChargeVoltageConfigurationEv : 184 -> 188
~ __ZN26AppleARMFunctionChargerMux18measureVBUSCurrentEPi : 200 -> 204
~ __ZN26AppleARMFunctionChargerMux21measureBatteryVoltageEPi : 132 -> 136
~ __ZN26AppleARMFunctionChargerMux25measureBatteryTemperatureEPi : 132 -> 136
~ __ZN26AppleARMFunctionChargerMux20measureSystemVoltageEPi : 132 -> 136
~ __ZN26AppleARMFunctionChargerMux20setChargerPropertiesEPK12OSDictionary : 192 -> 196
~ __ZN26AppleARMFunctionChargerMux17copyDebugPropertyEPKc : 196 -> 200
~ __ZN18AppleARMPMUCharger21DisplayCapacityFilter15setDisplayLevelEf : 72 -> 76
~ __ZN18AppleARMPMUCharger21DisplayCapacityFilter15getDisplayLevelEfjbi : 428 -> 432
~ __ZNK18AppleARMPMUCharger16copyDockChargersIbEEP8OSObjectjMS_KFS2_P23AppleARMFunctionChargerT_EbS5_ : 548 -> 552
~ __ZNK18AppleARMPMUCharger22copyDockChargersActionIbEEvP23AppleARMFunctionChargerPNS_32ConstCopyDockChargersActionParamIT_EE : 296 -> 300
~ __ZNK18AppleARMPMUCharger22copyDockChargersActionIPjEEvP23AppleARMFunctionChargerPNS_32ConstCopyDockChargersActionParamIT_EE : 292 -> 296
~ __ZNK18AppleARMPMUCharger16copyDockChargersIjEEP8OSObjectjMS_KFS2_P23AppleARMFunctionChargerT_EbS5_ : 548 -> 552
~ __ZNK18AppleARMPMUCharger22copyDockChargersActionIjEEvP23AppleARMFunctionChargerPNS_32ConstCopyDockChargersActionParamIT_EE : 292 -> 296
~ _GLOBAL__sub_I_AppleARMPMUCharger.cpp : 288 -> 292
~ __GLOBAL__D_a : 68 -> 72
~ __ZN22AppleARMPMUPowerSource9MetaClassC1Ev : 72 -> 76
~ __ZN22AppleARMPMUPowerSourceC2EPK11OSMetaClass : 52 -> 56
~ __ZN22AppleARMPMUPowerSource9MetaClassC2Ev : 72 -> 76
~ __ZN22AppleARMPMUPowerSource4initEP12OSDictionary : 120 -> 124
~ __ZN22AppleARMPMUPowerSource5startEP9IOService : 1840 -> 1844
~ __ZN22AppleARMPMUPowerSource17powerSupplyChangeEv : 60 -> 64
~ __ZN22AppleARMPMUPowerSource9initForPMEP9IOService : 204 -> 208
~ __ZN22ApplePowerSourceMemLog4logEEPKcS1_tjjPv : 336 -> 340
~ __ZN22AppleARMPMUPowerSource16finishStartGatedEP7_IOLockPb : 1320 -> 1324
~ __ZNK22AppleARMPMUPowerSource19functionWithChargerEiPKc : 160 -> 164
~ __ZN22AppleARMPMUPowerSource15handleInterruptEP22IOInterruptEventSourcei : 140 -> 144
~ __ZN22AppleARMPMUAccessoryPSC1Ev : 88 -> 92
~ __ZN22AppleARMPMUAccessoryPS19initWithPowerSourceEP22AppleARMPMUPowerSourcej : 184 -> 188
~ __ZN22AppleARMPMUPowerSource19powerSupplyDebounceEj : 184 -> 188
~ __ZN22AppleARMPMUPowerSource26sleepWakeNotificationGatedEj : 260 -> 264
~ __ZN22AppleARMPMUPowerSource20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 308 -> 312
~ __ZN22AppleARMPMUPowerSource16powerSupplyEventEbj : 72 -> 76
~ __ZN22AppleARMPMUPowerSource14updateRegistryEv : 756 -> 760
~ __ZN22AppleARMPMUPowerSource13setPropertiesEP8OSObject : 280 -> 284
~ __ZN22AppleARMPMUPowerSource18gatedSetPropertiesEP8OSObject : 516 -> 520
~ __ZN22AppleARMPMUPowerSource10setChargerEv : 44 -> 48
~ __ZN22AppleARMPMUPowerSource13setPSPropertyEPK8OSSymbolyj : 132 -> 136
~ __ZNK22AppleARMPMUPowerSource14getBatteryPackEi : 140 -> 144
~ __ZNK22AppleARMPMUPowerSource20getDockInflowDisableEi : 140 -> 144
~ __ZN22AppleARMPMUPowerSource16removePSPropertyEPK8OSSymbol : 196 -> 200
~ __ZN22AppleARMPMUPowerSource13setPSPropertyEPK8OSSymbolPKc : 128 -> 132
~ __ZN22AppleARMPMUPowerSource25setAdapterDetailsPropertyEjPKcyj : 216 -> 220
~ __ZN22AppleARMPMUPowerSource25setAdapterDetailsPropertyEjPKcS1_ : 212 -> 216
~ __ZN22AppleARMPMUPowerSource29getUSBInputCurrentLimitOffsetEjPi : 128 -> 132
~ __ZN22AppleARMPMUPowerSource23getUSBInputCurrentLimitEjPi : 144 -> 148
~ __ZN22AppleARMPMUPowerSource10setChargerEPb : 1068 -> 1072
~ __ZN22AppleARMPMUPowerSource13setHvcAdapterEj : 676 -> 680
~ __ZN22AppleARMPMUPowerSource18setHvcConfigParamsEjPK7OSArray : 1864 -> 1868
~ __ZN30AppleARMPassthroughPowerSource9MetaClassC1Ev : 72 -> 76
~ __ZN30AppleARMPassthroughPowerSourceC2EPK11OSMetaClass : 52 -> 56
~ __ZN30AppleARMPassthroughPowerSourceC1EPK11OSMetaClass : 52 -> 56
~ __ZN30AppleARMPassthroughPowerSourceD0Ev : 68 -> 72
~ __ZN30AppleARMPassthroughPowerSource9MetaClassC2Ev : 72 -> 76
~ __ZNK30AppleARMPassthroughPowerSource9MetaClass5allocEv : 104 -> 108
~ __ZN30AppleARMPassthroughPowerSourceC1Ev : 88 -> 92
~ __ZN30AppleARMPassthroughPowerSourceC2Ev : 88 -> 92
~ __ZN22AppleARMPMUAccessoryPS9MetaClassC1Ev : 72 -> 76
~ __ZN22AppleARMPMUAccessoryPSC2EPK11OSMetaClass : 52 -> 56
~ __ZN22AppleARMPMUAccessoryPSC1EPK11OSMetaClass : 52 -> 56
~ __ZN22AppleARMPMUAccessoryPSD0Ev : 68 -> 72
~ __ZN22AppleARMPMUAccessoryPS9MetaClassC2Ev : 72 -> 76
~ __ZNK22AppleARMPMUAccessoryPS9MetaClass5allocEv : 104 -> 108
~ __ZN22AppleARMPMUAccessoryPSC2Ev : 88 -> 92
~ __ZN22AppleARMPMUAccessoryPS4freeEv : 112 -> 116
~ __ZN22AppleARMPMUAccessoryPS23handlePowerSourceDetectEPK30IOAccessoryPowerSourceBehavior : 292 -> 296
~ _GLOBAL__sub_I_AppleARMPMUPowerSource.cpp : 428 -> 432
~ __GLOBAL__D_a : 68 -> 72
~ _ZN22AppleARMPMUPowerSource5startEP9IOService.cold.1 : 44 -> 48
~ _ZN22AppleARMPMUPowerSource16finishStartGatedEP7_IOLockPb.cold.1 : 80 -> 84
~ _ZN22AppleARMPMUPowerSource16finishStartGatedEP7_IOLockPb.cold.2 : 80 -> 84
~ _ZN22AppleARMPMUPowerSource16finishStartGatedEP7_IOLockPb.cold.3 : 80 -> 84
```
