## com.apple.driver.AppleTypeCRetimer

> `com.apple.driver.AppleTypeCRetimer`

```diff

   __TEXT.__const: 0x28
   __TEXT.__cstring: 0x11b6
   __TEXT.__os_log: 0xd5d
-  __TEXT_EXEC.__text: 0x8c00
+  __TEXT_EXEC.__text: 0x8dbc
   __TEXT_EXEC.__auth_stubs: 0x300
   __DATA.__data: 0xc8
   __DATA.__common: 0xe0
Functions:
~ __ZN20AppleTypeCRetimerLogC2Ev : 124 -> 128
~ __ZN17AppleTypeCRetimer9MetaClassC1Ev : 72 -> 76
~ __ZN17AppleTypeCRetimerC2EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleTypeCRetimerC1EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleTypeCRetimerD0Ev : 68 -> 72
~ __ZN17AppleTypeCRetimer9MetaClassC2Ev : 72 -> 76
~ __ZNK17AppleTypeCRetimer9MetaClass5allocEv : 104 -> 108
~ __ZN17AppleTypeCRetimerC1Ev : 88 -> 92
~ __ZN17AppleTypeCRetimerC2Ev : 88 -> 92
~ __ZN17AppleTypeCRetimer5startEP9IOService : 2528 -> 2532
~ __ZN17AppleTypeCRetimer7onTimerEP18IOTimerEventSource : 1068 -> 1072
~ __ZN17AppleTypeCRetimer13enablePollingEb : 136 -> 140
~ __ZN17AppleTypeCRetimer15messageReceivedEPvjP9IOServiceS0_m : 1724 -> 1728
~ __ZN17AppleTypeCRetimer4stopEP9IOService : 368 -> 372
~ ____ZN17AppleTypeCRetimer13enablePollingEb_block_invoke : 296 -> 300
~ __ZN17AppleTypeCRetimer8writeRegEhPKhy : 528 -> 532
~ __ZN17AppleTypeCRetimer16invalidateReportEy : 560 -> 564
~ __ZN17AppleTypeCRetimer14getSectionSizeE21dump_memory_section_ePyj : 440 -> 444
~ __ZN17AppleTypeCRetimer13setPowerStateEmP9IOService : 376 -> 380
~ __ZN17AppleTypeCRetimer13readRegLengthEhPy : 428 -> 432
~ __ZN17AppleTypeCRetimer8setStateE12RetimerState : 356 -> 360
~ __ZN17AppleTypeCRetimer7lockBusEv : 376 -> 380
~ __ZN17AppleTypeCRetimer9unlockBusEv : 376 -> 380
~ _GLOBAL__sub_I_AppleTypeCRetimer.cpp : 80 -> 84
~ __ZN35AppleTypeCRetimerCrashReportSection9MetaClassC1Ev : 72 -> 76
~ __ZN35AppleTypeCRetimerCrashReportSectionC2EPK11OSMetaClass : 52 -> 56
~ __ZN35AppleTypeCRetimerCrashReportSectionC1EPK11OSMetaClass : 52 -> 56
~ __ZN35AppleTypeCRetimerCrashReportSectionD0Ev : 68 -> 72
~ __ZN35AppleTypeCRetimerCrashReportSection9MetaClassC2Ev : 72 -> 76
~ __ZNK35AppleTypeCRetimerCrashReportSection9MetaClass5allocEv : 104 -> 108
~ __ZN35AppleTypeCRetimerCrashReportSectionC1Ev : 88 -> 92
~ __ZN35AppleTypeCRetimerCrashReportSectionC2Ev : 88 -> 92
~ __ZN28AppleTypeCRetimerCrashReport9MetaClassC1Ev : 72 -> 76
~ __ZN28AppleTypeCRetimerCrashReportC2EPK11OSMetaClass : 52 -> 56
~ __ZN28AppleTypeCRetimerCrashReportC1EPK11OSMetaClass : 52 -> 56
~ __ZN28AppleTypeCRetimerCrashReportD0Ev : 68 -> 72
~ __ZN28AppleTypeCRetimerCrashReport9MetaClassC2Ev : 72 -> 76
~ __ZNK28AppleTypeCRetimerCrashReport9MetaClass5allocEv : 104 -> 108
~ __ZN28AppleTypeCRetimerCrashReportC1Ev : 88 -> 92
~ __ZN28AppleTypeCRetimerCrashReportC2Ev : 88 -> 92
~ __ZN35AppleTypeCRetimerCrashReportSection4freeEv : 232 -> 236
~ __ZN28AppleTypeCRetimerCrashReport4freeEv : 312 -> 316
~ _GLOBAL__sub_I_AppleTypeCRetimerCrashReport.cpp : 148 -> 152
~ __GLOBAL__D_a : 56 -> 60
~ __ZN25AppleTypeCRetimerReporter9MetaClassC1Ev : 72 -> 76
~ __ZN25AppleTypeCRetimerReporterC2EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleTypeCRetimerReporterC1EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleTypeCRetimerReporterD0Ev : 68 -> 72
~ __ZN25AppleTypeCRetimerReporter9MetaClassC2Ev : 72 -> 76
~ __ZNK25AppleTypeCRetimerReporter9MetaClass5allocEv : 104 -> 108
~ __ZN25AppleTypeCRetimerReporterC1Ev : 88 -> 92
~ __ZN25AppleTypeCRetimerReporterC2Ev : 88 -> 92
~ __ZN25AppleTypeCRetimerReporter13publishReportEv : 208 -> 212
~ __ZN25AppleTypeCRetimerReporter13setPropertiesEP8OSObject : 528 -> 532
~ __ZN25AppleTypeCRetimerReporter18getProcessedReportEv : 108 -> 112
~ _GLOBAL__sub_I_AppleTypeCRetimerReporter.cpp : 148 -> 152
~ __ZN27AppleTypeCRetimerUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN27AppleTypeCRetimerUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN27AppleTypeCRetimerUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN27AppleTypeCRetimerUserClientD0Ev : 68 -> 72
~ __ZN27AppleTypeCRetimerUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK27AppleTypeCRetimerUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN27AppleTypeCRetimerUserClientC1Ev : 88 -> 92
~ __ZN27AppleTypeCRetimerUserClientC2Ev : 88 -> 92
~ __ZN27AppleTypeCRetimerUserClient12initWithTaskEP4taskPvjP12OSDictionary : 100 -> 104
~ __ZN27AppleTypeCRetimerUserClient5startEP9IOService : 760 -> 764
~ __ZN27AppleTypeCRetimerUserClient11clientCloseEv : 108 -> 112
~ __ZN27AppleTypeCRetimerUserClient14externalMethodEjP31IOExternalMethodArgumentsOpaque : 720 -> 724
~ __ZN27AppleTypeCRetimerUserClient13enablePollingEPvP25IOExternalMethodArguments : 280 -> 284
~ __ZN27AppleTypeCRetimerUserClient16isPollingEnabledEPvP25IOExternalMethodArguments : 264 -> 268
~ __ZN27AppleTypeCRetimerUserClient16invalidateReportEPvP25IOExternalMethodArguments : 260 -> 264
~ __ZN27AppleTypeCRetimerUserClient16acquireNorAccessEPvP25IOExternalMethodArguments : 280 -> 284
~ __ZN27AppleTypeCRetimerUserClient14getSectionSizeEPvP25IOExternalMethodArguments : 280 -> 284
~ __ZN27AppleTypeCRetimerUserClient14getSectionDataEPvP25IOExternalMethodArguments : 780 -> 784
~ __ZN27AppleTypeCRetimerUserClient12getRTVersionEPvP25IOExternalMethodArguments : 268 -> 272
~ __ZN27AppleTypeCRetimerUserClient15getRetimerStateEPvP25IOExternalMethodArguments : 280 -> 284
~ _GLOBAL__sub_I_AppleTypeCRetimerUserClient.cpp : 80 -> 84
~ __ZN17AppleTypeCRetimer16acquireNorAccessEb : 644 -> 648
~ __ZN17AppleTypeCRetimer7readRegEhPhyb : 900 -> 904
~ __ZN17AppleTypeCRetimer23writeMemConfigPollReadyE21dump_memory_section_eP36i2c_ap_register_dump_memory_config_tjj : 112 -> 116
~ __ZN17AppleTypeCRetimer14extractSectionEPh21dump_memory_section_eP36i2c_ap_register_dump_memory_config_tjj : 464 -> 468
~ __ZN17AppleTypeCRetimer14getSectionDataE21dump_memory_section_ePhjj : 152 -> 156
~ __ZN17AppleTypeCRetimer17checkRetimerPanicEPb : 80 -> 84
~ __ZN17AppleTypeCRetimer14onRetimerPanicEv : 2444 -> 2448
~ ____ZN17AppleTypeCRetimer15messageReceivedEPvjP9IOServiceS0_m_block_invoke : 32 -> 36
~ __ZN17AppleTypeCRetimer18apCommsTransactionER39i2c_ap_register_ap_comm_control_write_tR24ap_comm_request_result_tPhyRy : 2588 -> 2592
~ __ZN17AppleTypeCRetimer18getFwVersionStringEPc : 108 -> 112
~ __ZN17AppleTypeCRetimer18pollConfigMemReadyEP36i2c_ap_register_dump_memory_config_t : 372 -> 376
~ _ZN17AppleTypeCRetimer5startEP9IOService.cold.1 : 268 -> 272
~ _ZN17AppleTypeCRetimer5startEP9IOService.cold.2 : 228 -> 232
~ _ZN17AppleTypeCRetimer5startEP9IOService.cold.3 : 228 -> 232
~ _ZN17AppleTypeCRetimer5startEP9IOService.cold.4 : 228 -> 232
~ _ZN17AppleTypeCRetimer5startEP9IOService.cold.5 : 228 -> 232
~ _ZN17AppleTypeCRetimer5startEP9IOService.cold.6 : 228 -> 232
~ _ZN17AppleTypeCRetimer5startEP9IOService.cold.7 : 228 -> 232
~ _ZN17AppleTypeCRetimer5startEP9IOService.cold.8 : 228 -> 232
~ _ZN17AppleTypeCRetimer5startEP9IOService.cold.9 : 228 -> 232
~ _ZN17AppleTypeCRetimer5startEP9IOService.cold.10 : 268 -> 272
~ _ZN17AppleTypeCRetimer5startEP9IOService.cold.11 : 268 -> 272
~ _ZN17AppleTypeCRetimer8writeRegEhPKhy.cold.1 : 260 -> 264
~ _ZN17AppleTypeCRetimer14getSectionSizeE21dump_memory_section_ePyj.cold.1 : 260 -> 264
~ _ZN17AppleTypeCRetimer13readRegLengthEhPy.cold.1 : 260 -> 264
~ __ZNK35AppleTypeCRetimerCrashReportSection9serializeEP11OSSerialize : 252 -> 256
~ __ZN28AppleTypeCRetimerCrashReport4initEP17AppleTypeCRetimer : 136 -> 140
~ __ZN28AppleTypeCRetimerCrashReport7captureEv : 984 -> 988
~ __ZN28AppleTypeCRetimerCrashReport19captureCrashSectionE21dump_memory_section_ePP35AppleTypeCRetimerCrashReportSection : 704 -> 708
~ __ZNK28AppleTypeCRetimerCrashReport9serializeEP11OSSerialize : 492 -> 496
~ __ZN25AppleTypeCRetimerReporter10withReportEP17AppleTypeCRetimerP8OSObjecty : 116 -> 120
~ __ZN25AppleTypeCRetimerReporter14initWithReportEP17AppleTypeCRetimerP8OSObjecty : 308 -> 312
~ _ZN27AppleTypeCRetimerUserClient12initWithTaskEP4taskPvjP12OSDictionary.cold.1 : 196 -> 200
~ _ZN27AppleTypeCRetimerUserClient14getSectionDataEPvP25IOExternalMethodArguments.cold.1 : 216 -> 220
```
