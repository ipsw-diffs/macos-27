## com.apple.driver.AppleARMWatchdogTimer

> `com.apple.driver.AppleARMWatchdogTimer`

```diff

 334.0.4.0.0
   __TEXT.__cstring: 0x167d
-  __TEXT_EXEC.__text: 0x5ea8
+  __TEXT_EXEC.__text: 0x60c0
   __TEXT_EXEC.__auth_stubs: 0x590
   __DATA.__data: 0x118
   __DATA.__common: 0x110
Functions:
~ __ZN21AppleARMWatchdogTimer9MetaClassC1Ev : 72 -> 76
~ __ZN21AppleARMWatchdogTimerC2EPK11OSMetaClass : 56 -> 60
~ __ZN21AppleARMWatchdogTimerC1EPK11OSMetaClass : 56 -> 60
~ __ZN21AppleARMWatchdogTimerD0Ev : 68 -> 72
~ __ZN21AppleARMWatchdogTimer9MetaClassC2Ev : 72 -> 76
~ __ZNK21AppleARMWatchdogTimer9MetaClass5allocEv : 108 -> 112
~ __ZN21AppleARMWatchdogTimerC1Ev : 92 -> 96
~ __ZN21AppleARMWatchdogTimerC2Ev : 92 -> 96
~ __ZN21AppleARMWatchdogTimer5startEP9IOService : 4684 -> 4688
~ __ZN21AppleARMWatchdogTimer20_handlePEHaltRestartEj : 812 -> 816
~ __ZN21AppleARMWatchdogTimer16_handleInterruptEP8OSObjectPvP9IOServicei : 112 -> 116
~ __ZN21AppleARMWatchdogTimer26_handlePEARMDebugPanicHookEPKc : 244 -> 248
~ __ZN21AppleARMWatchdogTimer17awl_hwbus_presentEv : 92 -> 96
~ __ZN21AppleARMWatchdogTimer22awl_fill_watchdog_diagEv : 148 -> 152
~ __ZN21AppleARMWatchdogTimer32awl_write_scratch_broadcast_funcEv : 84 -> 88
~ __ZN21AppleARMWatchdogTimer20awl_get_kernel_slideEv : 68 -> 72
~ __ZN21AppleARMWatchdogTimer23check_system_cpu_healthEv : 248 -> 252
~ __ZN21AppleARMWatchdogTimer38check_system_cpu_health_broadcast_funcEv : 48 -> 52
~ __ZN21AppleARMWatchdogTimer12getBootStageERh : 168 -> 172
~ __ZN21AppleARMWatchdogTimer17getHibernateStateEv : 136 -> 140
~ __ZN21AppleARMWatchdogTimer20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 1040 -> 1044
~ __ZN21AppleARMWatchdogTimer32enableReconfigWatchdogMonitoringEv : 140 -> 144
~ __ZN21AppleARMWatchdogTimer28enableAONWatchdogForReconfigEv : 144 -> 148
~ __ZN21AppleARMWatchdogTimer16enableAPWatchdogEv : 348 -> 352
~ __ZN21AppleARMWatchdogTimer29disableAONWatchdogForReconfigEv : 72 -> 76
~ __ZN21AppleARMWatchdogTimer21setBootStageFromPanicEh : 124 -> 128
~ __ZN21AppleARMWatchdogTimer29enablePanicLongPeriodWatchdogEv : 296 -> 300
~ __ZN21AppleARMWatchdogTimer19extendPanicWatchdogEv : 168 -> 172
~ __ZN21AppleARMWatchdogTimer37writeCoreTriggerConfigurationCallbackEv : 92 -> 96
~ __ZN21AppleARMWatchdogTimer29_writeApWatchdogConfigurationEv : 132 -> 136
~ __ZN21AppleARMWatchdogTimer21_armWatchdogMechanismEyb : 220 -> 224
~ __ZN21AppleARMWatchdogTimer16extendAPWatchdogEv : 88 -> 92
~ __ZN21AppleARMWatchdogTimer14extendWatchdogEv : 60 -> 64
~ __ZN21AppleARMWatchdogTimer14enableWatchdogEv : 196 -> 200
~ __ZN21AppleARMWatchdogTimer15disableWatchdogEv : 128 -> 132
~ __ZN21AppleARMWatchdogTimer23forceWatchdogExpirationEv : 124 -> 128
~ __ZN21AppleARMWatchdogTimer18_armAONWatchdogTmrEy : 92 -> 96
~ __ZN21AppleARMWatchdogTimer17publishPropertiesEv : 128 -> 132
~ __ZN21AppleARMWatchdogTimer24_readModifyWriteMapped32Eyjj : 88 -> 92
~ __ZL11_dtReadpropPK13OpaqueDTEntryPKcPy : 160 -> 164
~ _GLOBAL__sub_I_AppleARMWatchdogTimer.cpp : 100 -> 104
~ __ZN43AppleARMWatchdogTimerFunctionExpireWatchdog9MetaClassC1Ev : 72 -> 76
~ __ZN43AppleARMWatchdogTimerFunctionExpireWatchdogC2EPK11OSMetaClass : 52 -> 56
~ __ZN43AppleARMWatchdogTimerFunctionExpireWatchdogC1EPK11OSMetaClass : 52 -> 56
~ __ZN43AppleARMWatchdogTimerFunctionExpireWatchdogD0Ev : 68 -> 72
~ __ZN43AppleARMWatchdogTimerFunctionExpireWatchdog9MetaClassC2Ev : 72 -> 76
~ __ZNK43AppleARMWatchdogTimerFunctionExpireWatchdog9MetaClass5allocEv : 104 -> 108
~ __ZN43AppleARMWatchdogTimerFunctionExpireWatchdogC1Ev : 88 -> 92
~ __ZN43AppleARMWatchdogTimerFunctionExpireWatchdogC2Ev : 88 -> 92
~ __ZN43AppleARMWatchdogTimerFunctionExpireWatchdog12callFunctionEPvS0_S0_ : 32 -> 36
~ __ZN43AppleARMWatchdogTimerFunctionExpireWatchdog27initWithTargetDataAndSymbolEP9IOServicePK6OSDataPK8OSSymbol : 100 -> 104
~ _GLOBAL__sub_I_AppleARMWatchdogTimerFunctions.cpp : 80 -> 84
~ __ZN20IOWatchdogUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN20IOWatchdogUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN20IOWatchdogUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN20IOWatchdogUserClientD0Ev : 68 -> 72
~ __ZN20IOWatchdogUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK20IOWatchdogUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN20IOWatchdogUserClientC1Ev : 88 -> 92
~ __ZN20IOWatchdogUserClientC2Ev : 88 -> 92
~ __ZN20IOWatchdogUserClient5startEP9IOService : 152 -> 156
~ __ZN20IOWatchdogUserClient9terminateEj : 96 -> 100
~ __ZN20IOWatchdogUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 236 -> 240
~ _GLOBAL__sub_I_IOWatchdogUserClient.cpp : 80 -> 84
~ __ZN37AppleARMWatchdogTimerHibernateHandler9MetaClassC1Ev : 72 -> 76
~ __ZN37AppleARMWatchdogTimerHibernateHandlerC2EPK11OSMetaClass : 52 -> 56
~ __ZN37AppleARMWatchdogTimerHibernateHandlerC1EPK11OSMetaClass : 52 -> 56
~ __ZN37AppleARMWatchdogTimerHibernateHandlerD0Ev : 68 -> 72
~ __ZN37AppleARMWatchdogTimerHibernateHandler9MetaClassC2Ev : 72 -> 76
~ __ZNK37AppleARMWatchdogTimerHibernateHandler9MetaClass5allocEv : 104 -> 108
~ __ZN37AppleARMWatchdogTimerHibernateHandlerC1Ev : 88 -> 92
~ __ZN37AppleARMWatchdogTimerHibernateHandlerC2Ev : 88 -> 92
~ __ZN37AppleARMWatchdogTimerHibernateHandler14initWithDriverEP21AppleARMWatchdogTimer : 68 -> 72
~ __ZN37AppleARMWatchdogTimerHibernateHandler16createWithDriverEP21AppleARMWatchdogTimer : 92 -> 96
~ _GLOBAL__sub_I_AppleARMWatchdogTimerHibernateHandler.cpp : 80 -> 84
~ __ZN10IOWatchdog9MetaClassC1Ev : 72 -> 76
~ __ZN10IOWatchdogC2EPK11OSMetaClass : 52 -> 56
~ __ZN10IOWatchdog9MetaClassC2Ev : 72 -> 76
~ __ZN10IOWatchdog5startEP9IOServiceyy : 1520 -> 1524
~ __ZN10IOWatchdog24logWatchdogConfigurationEPKc : 160 -> 164
~ __ZN10IOWatchdog25async_initialization_codeEv : 84 -> 88
~ __ZN10IOWatchdog17publishPropertiesEv : 320 -> 324
~ __ZN10IOWatchdog24check_stress_rack_deviceEv : 316 -> 320
~ __ZN10IOWatchdog20handle_defang_sysctlEP10sysctl_oidPviP10sysctl_req : 256 -> 260
~ __ZN10IOWatchdog4stopEP9IOService : 120 -> 124
~ __ZN10IOWatchdog13checkWatchdogEv : 232 -> 236
~ __ZN10IOWatchdog21shutdownCheckWatchdogEy : 372 -> 376
~ __ZN10IOWatchdog13newUserClientEP4taskPvjP12OSDictionaryPP12IOUserClient : 524 -> 528
~ __ZN10IOWatchdog15userClientCloseEv : 64 -> 68
~ __ZN10IOWatchdog21userspaceCheckEnabledEP8OSObjectPvP25IOExternalMethodArguments : 132 -> 136
~ __ZN10IOWatchdog22userspaceCheckDefangedEP8OSObjectPvP25IOExternalMethodArguments : 176 -> 180
~ __ZN10IOWatchdog16userspaceCheckinEP8OSObjectPvP25IOExternalMethodArguments : 160 -> 164
~ __ZN10IOWatchdog14userspacePanicEP8OSObjectPvP25IOExternalMethodArguments : 64 -> 68
~ __ZN10IOWatchdog35userspaceDisableUserspaceMonitoringEP8OSObjectPvP25IOExternalMethodArguments : 124 -> 128
~ __ZN10IOWatchdog36userspaceReenableUserspaceMonitoringEP8OSObjectPvP25IOExternalMethodArguments : 168 -> 172
~ __ZN10IOWatchdog36userspaceCheckIOKitMonitoringEnabledEP8OSObjectPvP25IOExternalMethodArguments : 144 -> 148
~ __ZN10IOWatchdog22increaseDefangRefCountEv : 188 -> 192
~ __ZN10IOWatchdog22decreaseDefangRefCountEv : 204 -> 208
~ _GLOBAL__sub_I_IOWatchdog.cpp : 80 -> 84
~ __ZN21AppleARMWatchdogTimer21_handlePanicInterruptEP8OSObjectPvP9IOServicei : 24 -> 28
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.1 : 44 -> 48
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.2 : 44 -> 48
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.3 : 44 -> 48
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.4 : 44 -> 48
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.5 : 96 -> 100
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.6 : 84 -> 88
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.7 : 84 -> 88
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.8 : 52 -> 56
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.9 : 84 -> 88
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.10 : 84 -> 88
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.11 : 84 -> 88
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.12 : 44 -> 48
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.13 : 44 -> 48
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.14 : 44 -> 48
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.15 : 84 -> 88
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.16 : 84 -> 88
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.17 : 52 -> 56
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.18 : 84 -> 88
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.19 : 84 -> 88
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.20 : 44 -> 48
~ _ZN21AppleARMWatchdogTimer5startEP9IOService.cold.21 : 44 -> 48
~ _ZN21AppleARMWatchdogTimer20_handlePEHaltRestartEj.cold.1 : 60 -> 64
~ _ZN21AppleARMWatchdogTimer20_handlePEHaltRestartEj.cold.2 : 44 -> 48
~ _ZN21AppleARMWatchdogTimer23check_system_cpu_healthEv.cold.1 : 44 -> 48
~ _ZN21AppleARMWatchdogTimer23check_system_cpu_healthEv.cold.2 : 44 -> 48
~ _ZN21AppleARMWatchdogTimer32enableReconfigWatchdogMonitoringEv.cold.1 : 24 -> 28
~ _ZN21AppleARMWatchdogTimer28enableAONWatchdogForReconfigEv.cold.1 : 24 -> 28
~ _ZN21AppleARMWatchdogTimer29disableAONWatchdogForReconfigEv.cold.1 : 44 -> 48
~ _ZN37AppleARMWatchdogTimerHibernateHandler14initWithDriverEP21AppleARMWatchdogTimer.cold.1 : 56 -> 60
~ _ZN37AppleARMWatchdogTimerHibernateHandler16createWithDriverEP21AppleARMWatchdogTimer.cold.1 : 44 -> 48
~ _ZN10IOWatchdog5startEP9IOServiceyy.cold.1 : 44 -> 48
~ _ZN10IOWatchdog13checkWatchdogEv.cold.1 : 108 -> 112
~ _ZN10IOWatchdog13checkWatchdogEv.cold.2 : 132 -> 136
~ _ZN10IOWatchdog14userspacePanicEP8OSObjectPvP25IOExternalMethodArguments.cold.1 : 52 -> 56
```
