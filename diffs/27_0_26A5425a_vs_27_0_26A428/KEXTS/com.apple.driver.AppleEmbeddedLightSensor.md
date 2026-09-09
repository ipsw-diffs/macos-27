## com.apple.driver.AppleEmbeddedLightSensor

> `com.apple.driver.AppleEmbeddedLightSensor`

```diff

   __TEXT.__cstring: 0x2914
   __TEXT.__const: 0xc0
   __TEXT.__os_log: 0x2c
-  __TEXT_EXEC.__text: 0xcb6c
+  __TEXT_EXEC.__text: 0xcd64
   __TEXT_EXEC.__auth_stubs: 0x2d0
   __DATA.__data: 0x248
   __DATA.__common: 0x108
Functions:
~ __ZN13AppleSPUCT8179MetaClassC1Ev : 72 -> 76
~ __ZN13AppleSPUCT817C2EPK11OSMetaClass : 84 -> 88
~ __ZN13AppleSPUCT817C1EPK11OSMetaClass : 84 -> 88
~ __ZN13AppleSPUCT817D0Ev : 68 -> 72
~ __ZThn200_N13AppleSPUCT817D0Ev : 72 -> 76
~ __ZN13AppleSPUCT8179MetaClassC2Ev : 72 -> 76
~ __ZNK13AppleSPUCT8179MetaClass5allocEv : 136 -> 140
~ __ZN13AppleSPUCT817C1Ev : 120 -> 124
~ __ZN13AppleSPUCT817C2Ev : 120 -> 124
~ _GLOBAL__sub_I_AppleSPUCT817.cpp : 80 -> 84
~ __ZN20AppleSPUALSLuxDriver9MetaClassC1Ev : 72 -> 76
~ __ZN20AppleSPUALSLuxDriverC2EPK11OSMetaClass : 100 -> 104
~ __ZN20AppleSPUALSLuxDriverC1EPK11OSMetaClass : 100 -> 104
~ __ZN20AppleSPUALSLuxDriverD0Ev : 68 -> 72
~ __ZThn200_N20AppleSPUALSLuxDriverD0Ev : 72 -> 76
~ __ZN20AppleSPUALSLuxDriver9MetaClassC2Ev : 72 -> 76
~ __ZNK20AppleSPUALSLuxDriver9MetaClass5allocEv : 52 -> 56
~ __ZN20AppleSPUALSLuxDriverC2Ev : 136 -> 140
~ __ZN20AppleSPUALSLuxDriver5startEP9IOService : 108 -> 112
~ __ZN20AppleSPUALSLuxDriver10handleStopEP9IOService : 124 -> 128
~ __ZN20AppleSPUALSLuxDriver14ALSSetPropertyEP12OSDictionary : 2360 -> 2364
~ __ZN20AppleSPUALSLuxDriver18setIntegrationModeEj : 124 -> 128
~ __ZN20AppleSPUALSLuxDriver18setPropertiesGatedEP12OSDictionary : 120 -> 124
~ __ZN20AppleSPUALSLuxDriver19loadCalibrationDataEv : 104 -> 108
~ __ZN20AppleSPUALSLuxDriver35fetchPlacementAndOrientationFromAOPEP17AppleSPUInterface : 200 -> 204
~ __ZN20AppleSPUALSLuxDriver14getOrientationEv : 360 -> 364
~ __ZN20AppleSPUALSLuxDriver12getPlacementEv : 360 -> 364
~ _GLOBAL__sub_I_AppleSPUALSLuxDriver.cpp : 80 -> 84
~ __ZN19AppleALSColorSensor9MetaClassC1Ev : 72 -> 76
~ __ZN19AppleALSColorSensorC2EPK11OSMetaClass : 52 -> 56
~ __ZN19AppleALSColorSensor9MetaClassC2Ev : 72 -> 76
~ __ZN19AppleALSColorSensor11handleStartEP9IOService : 1092 -> 1096
~ __ZN19AppleALSColorSensor13_timerExpiredEv : 488 -> 492
~ __ZN19AppleALSColorSensor16_interruptActionEP22IOInterruptEventSourcei : 156 -> 160
~ __ZN19AppleALSColorSensor4freeEv : 460 -> 464
~ __ZN19AppleALSColorSensor16setSensorEnabledEb : 280 -> 284
~ __ZN19AppleALSColorSensor13setPropertiesEP8OSObject : 168 -> 172
~ __ZN19AppleALSColorSensor14_setPropertiesEP8OSObject : 1308 -> 1312
~ __ZN19AppleALSColorSensor11reportEventEjjjjj : 284 -> 288
~ __ZN19AppleALSColorSensor11reportEventEfjjjjfPhj : 1056 -> 1060
~ __ZN19AppleALSColorSensor9copyEventEjP10IOHIDEventj : 432 -> 436
~ __ZN19AppleALSColorSensor10_copyEventERP10IOHIDEvent : 596 -> 600
~ __ZN19AppleALSColorSensor8readReg8EhPh : 96 -> 100
~ __ZN19AppleALSColorSensor9writeReg8Ehh : 100 -> 104
~ __ZN19AppleALSColorSensor9readReg16EhPt : 96 -> 100
~ __ZN19AppleALSColorSensor9readBurstEhPhj : 96 -> 100
~ __ZN19AppleALSColorSensor10writeReg16Eht : 108 -> 112
~ __ZN19AppleALSColorSensor10writeBurstEhPhj : 100 -> 104
~ __ZN19AppleALSColorSensor23preEmptiveSensorStartupEv : 120 -> 124
~ __ZN19AppleALSColorSensor17_updatePowerStateEv : 392 -> 396
~ _GLOBAL__sub_I_AppleALSColorSensor.cpp : 80 -> 84
~ __ZN27AppleEmbeddedI2CLightSensor9MetaClassC1Ev : 72 -> 76
~ __ZN27AppleEmbeddedI2CLightSensorC2EPK11OSMetaClass : 52 -> 56
~ __ZN27AppleEmbeddedI2CLightSensor9MetaClassC2Ev : 72 -> 76
~ __ZN27AppleEmbeddedI2CLightSensor11handleStartEP9IOService : 760 -> 764
~ __ZN27AppleEmbeddedI2CLightSensor16_interruptActionEP22IOInterruptEventSourcei : 164 -> 168
~ __ZN27AppleEmbeddedI2CLightSensor13_timerExpiredEv : 460 -> 464
~ __ZN27AppleEmbeddedI2CLightSensor24enablePowerAndInterruptsEb : 408 -> 412
~ __ZN27AppleEmbeddedI2CLightSensor10handleOpenEP9IOServicejPv : 156 -> 160
~ __ZN27AppleEmbeddedI2CLightSensor17_updatePowerStateEv : 456 -> 460
~ __ZN27AppleEmbeddedI2CLightSensor11handleCloseEP9IOServicej : 184 -> 188
~ __ZN27AppleEmbeddedI2CLightSensor4freeEv : 644 -> 648
~ __ZN27AppleEmbeddedI2CLightSensor12didTerminateEP9IOServicejPb : 628 -> 632
~ __ZN27AppleEmbeddedI2CLightSensor13setPropertiesEP8OSObject : 320 -> 324
~ __ZN27AppleEmbeddedI2CLightSensor14_setPropertiesEP8OSObject : 1852 -> 1856
~ __ZN27AppleEmbeddedI2CLightSensor31setReportingThresholdPercentageEt : 360 -> 364
~ __ZN27AppleEmbeddedI2CLightSensor11reportEventEjjj : 288 -> 292
~ __ZN27AppleEmbeddedI2CLightSensor9copyEventEjP10IOHIDEventj : 216 -> 220
~ __ZN27AppleEmbeddedI2CLightSensor10_copyEventERP10IOHIDEvent : 148 -> 152
~ __ZN27AppleEmbeddedI2CLightSensor7messageEjP9IOServicePv : 192 -> 196
~ __ZN27AppleEmbeddedI2CLightSensor8_messageEjP9IOServicePv : 156 -> 160
~ __ZN27AppleEmbeddedI2CLightSensor38hidEventPreEmptiveSensorStartupHandlerEP22IOInterruptEventSourcei : 96 -> 100
~ __ZN27AppleEmbeddedI2CLightSensor25installButtonWakeListenerEv : 1016 -> 1020
~ __ZN27AppleEmbeddedI2CLightSensor26_eventServiceCallbackGatedEP17IOHIDEventServicePvP10IOHIDEvent : 636 -> 640
~ _GLOBAL__sub_I_AppleEmbeddedLightSensor.cpp : 80 -> 84
~ __ZN10AppleCT7209MetaClassC1Ev : 72 -> 76
~ __ZN10AppleCT720C2EPK11OSMetaClass : 148 -> 152
~ __ZN10AppleCT720D0Ev : 68 -> 72
~ __ZN10AppleCT7209MetaClassC2Ev : 72 -> 76
~ __ZNK10AppleCT7209MetaClass5allocEv : 52 -> 56
~ __ZN10AppleCT720C2Ev : 184 -> 188
~ __ZN10AppleCT7205probeEP9IOServicePi : 844 -> 848
~ __ZN10AppleCT72011handleStartEP9IOService : 1148 -> 1152
~ __ZN10AppleCT72014dumpALSCalDataEv : 1540 -> 1544
~ __ZN10AppleCT72016setSensorEnabledEb : 468 -> 472
~ __ZN10AppleCT72019loadCalibrationDataEP6OSData : 1724 -> 1728
~ __ZN10AppleCT72018setPropertiesGatedEP8OSObject : 3072 -> 3076
~ __ZN10AppleCT72010updateGainEv : 192 -> 196
~ __ZN10AppleCT72020setALSReportIntervalEj : 692 -> 696
~ __ZN10AppleCT72027updateDynamicGainThresholdsEv : 268 -> 272
~ __ZN10AppleCT72021updateIntegrationTimeEv : 260 -> 264
~ __ZN10AppleCT72034updateDynamicIntegrationParametersEPtb : 1084 -> 1088
~ __ZN10AppleCT72014luxCalculationEPtPfh : 876 -> 880
~ __ZN10AppleCT72015_handleNewEventEv : 1732 -> 1736
~ _GLOBAL__sub_I_AppleCT720.cpp : 80 -> 84
~ __ZN10AppleCT8099MetaClassC1Ev : 72 -> 76
~ __ZN10AppleCT809C2EPK11OSMetaClass : 52 -> 56
~ __ZN10AppleCT809C1EPK11OSMetaClass : 52 -> 56
~ __ZN10AppleCT809D0Ev : 68 -> 72
~ __ZN10AppleCT8099MetaClassC2Ev : 72 -> 76
~ __ZNK10AppleCT8099MetaClass5allocEv : 104 -> 108
~ __ZN10AppleCT809C1Ev : 88 -> 92
~ __ZN10AppleCT809C2Ev : 88 -> 92
~ __ZN10AppleCT8096chksumEPKvi : 128 -> 132
~ __ZN10AppleCT8095probeEP9IOServicePi : 608 -> 612
~ __ZN10AppleCT8099_readReg8EhPh : 128 -> 132
~ __ZN10AppleCT80911handleStartEP9IOService : 1144 -> 1148
~ __ZN10AppleCT80910handleOpenEP9IOServicejPv : 180 -> 184
~ __ZN10AppleCT80926_setReportIntervalInternalEj : 284 -> 288
~ __ZN10AppleCT80915_dumpALSCalDataEv : 652 -> 656
~ __ZN10AppleCT80916readSensorData32EPjS0_S0_ : 416 -> 420
~ __ZN10AppleCT80914readSensorDataEPtS0_Pj : 92 -> 96
~ __ZN10AppleCT80919_handleTimerExpiredEv : 216 -> 220
~ __ZN10AppleCT80924_reportAmbientLightLevelEjjj : 244 -> 248
~ __ZN10AppleCT80916setSensorEnabledEb : 220 -> 224
~ __ZN10AppleCT80910_writeReg8Ehh : 132 -> 136
~ __ZN10AppleCT80924_setALSReportingIntervalEj : 264 -> 268
~ __ZN10AppleCT80913setPropertiesEP8OSObject : 456 -> 460
~ __ZN10AppleCT80914_setPropertiesEP8OSObject : 440 -> 444
~ __ZN10AppleCT80918setPropertiesGatedEP8OSObject : 1708 -> 1712
~ _GLOBAL__sub_I_AppleCT809.cpp : 80 -> 84
~ _init_default_corebrightness_log : 108 -> 112
~ __ZN13AppleSPUCT8175probeEP9IOServicePi : 372 -> 376
~ __ZN13AppleSPUCT81711handleStartEP9IOService : 200 -> 204
~ __ZN20AppleSPUALSLuxDriver11handleStartEP9IOService : 736 -> 740
~ __ZN27AppleEmbeddedI2CLightSensor23hidMatchingNotificationEPvP9IOServiceP10IONotifier : 892 -> 896
```
