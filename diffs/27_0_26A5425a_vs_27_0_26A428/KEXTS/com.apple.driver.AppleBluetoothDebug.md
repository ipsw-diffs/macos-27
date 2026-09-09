## com.apple.driver.AppleBluetoothDebug

> `com.apple.driver.AppleBluetoothDebug`

```diff

 77.0.0.0.0
   __TEXT.__cstring: 0x18c4
   __TEXT.__const: 0x90
-  __TEXT_EXEC.__text: 0xad48
+  __TEXT_EXEC.__text: 0xaf20
   __TEXT_EXEC.__auth_stubs: 0x440
   __DATA.__data: 0xf8
   __DATA.__common: 0xb1
Functions:
~ __ZN17BTDebugUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN17BTDebugUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN17BTDebugUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN17BTDebugUserClientD0Ev : 68 -> 72
~ __ZN17BTDebugUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK17BTDebugUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN17BTDebugUserClientC1Ev : 88 -> 92
~ __ZN17BTDebugUserClientC2Ev : 88 -> 92
~ __ZN17BTDebugUserClient4freeEv : 244 -> 248
~ __ZN17BTDebugUserClient5startEP9IOService : 484 -> 488
~ __ZN17BTDebugUserClient4stopEP9IOService : 220 -> 224
~ __ZN17BTDebugUserClient11clientCloseEv : 412 -> 416
~ __ZN17BTDebugUserClient16clientCloseGatedEv : 64 -> 68
~ __ZN17BTDebugUserClient13willTerminateEP9IOServicej : 152 -> 156
~ __ZN17BTDebugUserClient9_coreDumpEPS_PvP25IOExternalMethodArguments : 360 -> 364
~ __ZN17BTDebugUserClient16coreDumpCompleteEPvS0_iy : 180 -> 184
~ __ZN17BTDebugUserClient8coreDumpEyPKcPN14BTDebugService18CoreDumpCompletionE : 308 -> 312
~ __ZN17BTDebugUserClient13enableLoggingEjjPK13LogFlowParamsj : 328 -> 332
~ __ZN17BTDebugUserClient14disableLoggingEv : 272 -> 276
~ __ZN17BTDebugUserClient8dumpLogsEPKc : 280 -> 284
~ _GLOBAL__sub_I_BTDebugUserClient.cpp : 80 -> 84
~ __ZN14BTDebugAdapter9MetaClassC1Ev : 72 -> 76
~ __ZN14BTDebugAdapterC2EPK11OSMetaClass : 52 -> 56
~ __ZN14BTDebugAdapterC1EPK11OSMetaClass : 52 -> 56
~ __ZN14BTDebugAdapterD0Ev : 68 -> 72
~ __ZN14BTDebugAdapter9MetaClassC2Ev : 72 -> 76
~ __ZNK14BTDebugAdapter9MetaClass5allocEv : 104 -> 108
~ __ZN14BTDebugAdapterC1Ev : 88 -> 92
~ __ZN14BTDebugAdapterC2Ev : 88 -> 92
~ __ZN14BTDebugAdapter16withDebugServiceEP9IOService : 256 -> 260
~ __ZN14BTDebugAdapter4freeEv : 112 -> 116
~ __ZN14BTDebugAdapter8coreDumpEyPKcPN14BTDebugService18CoreDumpCompletionE : 412 -> 416
~ __ZN14BTDebugAdapter8dumpLogsEPKc : 304 -> 308
~ _GLOBAL__sub_I_BTDebugAdapter.cpp : 80 -> 84
~ __ZN15BTDebugReporter9MetaClassC1Ev : 72 -> 76
~ __ZN15BTDebugReporterC2EPK11OSMetaClass : 132 -> 136
~ __ZN15BTDebugReporterC1EPK11OSMetaClass : 132 -> 136
~ __ZN15BTDebugReporterD0Ev : 68 -> 72
~ __ZN15BTDebugReporter9MetaClassC2Ev : 72 -> 76
~ __ZNK15BTDebugReporter9MetaClass5allocEv : 52 -> 56
~ __ZN15BTDebugReporterC2Ev : 168 -> 172
~ __ZN15BTDebugReporter20withReportingServiceEP9IOServiceP11CCLogStream : 164 -> 168
~ __ZN15BTDebugReporter5startEv : 1068 -> 1072
~ __ZN15BTDebugReporter4stopEv : 176 -> 180
~ __ZN15BTDebugReporter4freeEv : 380 -> 384
~ __ZN15BTDebugReporter12addReportersEP9IOServiceP14IOReportLegend : 1236 -> 1240
~ __ZN15BTDebugReporter12updateReportEP19IOReportChannelListjPvS2_ : 140 -> 144
~ __ZN15BTDebugReporter17reportReceivedLogEjj : 188 -> 192
~ __ZN15BTDebugReporter14reportCoreDumpEiy : 112 -> 116
~ _GLOBAL__sub_I_BTDebugReporter.cpp : 80 -> 84
~ __ZN7BTDebug9MetaClassC1Ev : 72 -> 76
~ __ZN7BTDebugC2EPK11OSMetaClass : 68 -> 72
~ __ZN7BTDebugC1EPK11OSMetaClass : 68 -> 72
~ __ZN7BTDebugD0Ev : 68 -> 72
~ __ZN7BTDebug9MetaClassC2Ev : 72 -> 76
~ __ZNK7BTDebug9MetaClass5allocEv : 120 -> 124
~ __ZN7BTDebugC1Ev : 104 -> 108
~ __ZN7BTDebugC2Ev : 104 -> 108
~ __ZN7BTDebug5startEP9IOService : 2084 -> 2088
~ __ZN7BTDebug4stopEP9IOService : 552 -> 556
~ __ZN7BTDebug4freeEv : 1252 -> 1256
~ __ZN7BTDebug28initCoreCaptureForDriverLogsE16CCStreamLogLevelS0_ : 584 -> 588
~ __ZN7BTDebug26initCoreCaptureForCoreDumpEv : 1504 -> 1508
~ __ZN7BTDebug15serviceNotifierEPvP9IOServiceP10IONotifier : 688 -> 692
~ __ZN7BTDebug17enqueueAsyncEventENS_14AsyncEventTypeEPNS_10AsyncEvent7PayloadE : 820 -> 824
~ __ZN7BTDebug11openServiceEP14BTDebugService : 1156 -> 1160
~ __ZN7BTDebug12closeServiceEv : 296 -> 300
~ __ZN7BTDebug20asyncEventThreadCallEPvS0_ : 152 -> 156
~ __ZN7BTDebug17asyncEventHandlerEv : 2220 -> 2224
~ __ZN7BTDebug14queueLogBufferEPNS_9LogBufferE : 796 -> 800
~ __ZN7BTDebug8coreDumpEyPKcPN14BTDebugService18CoreDumpCompletionE : 908 -> 912
~ __ZN7BTDebug13coreDumpGatedEPNS_15CoreDumpContextE : 2452 -> 2456
~ __ZN7BTDebug16coreDumpCompleteEPviy : 236 -> 240
~ __ZN7BTDebug21coreDumpCompleteGatedEPNS_15CoreDumpContextEiy : 800 -> 804
~ __ZN7BTDebug13enableLoggingEjjPK13LogFlowParamsj : 528 -> 532
~ __ZN7BTDebug18enableLoggingGatedEjjPK13LogFlowParamsj : 1688 -> 1692
~ __ZN7BTDebug21enableLoggingInternalEv : 1696 -> 1700
~ __ZN7BTDebug14disableLoggingEv : 276 -> 280
~ __ZN7BTDebug19disableLoggingGatedEv : 360 -> 364
~ __ZN7BTDebug22disableLoggingInternalEv : 624 -> 628
~ __ZN7BTDebug8dumpLogsEPKc : 280 -> 284
~ __ZN7BTDebug13dumpLogsGatedEPKc : 848 -> 852
~ __ZN7BTDebug16readLogsCompleteEPviPN14BTDebugService7LogDataEj : 1716 -> 1720
~ __ZN7BTDebug15configureReportEP19IOReportChannelListjPvS2_ : 444 -> 448
~ __ZN7BTDebug12updateReportEP19IOReportChannelListjPvS2_ : 444 -> 448
~ __ZN7BTDebug20printDbgServiceQueueEPKc : 364 -> 368
~ __ZN7BTDebug19addServiceDebugDataEP13CCFaultReport : 820 -> 824
~ ____ZN7BTDebug19addServiceDebugDataEP13CCFaultReport_block_invoke : 684 -> 688
~ __ZN7BTDebug18mapCrashInfoBufferEv : 1048 -> 1052
~ __ZN7BTDebug17crashInfoCompleteEPvS0_i : 176 -> 180
~ _GLOBAL__sub_I_BTDebug.cpp : 80 -> 84
~ _ZN15BTDebugReporter17reportReceivedLogEjj.cold.1 : 24 -> 28
~ _ZN15BTDebugReporter14reportCoreDumpEiy.cold.1 : 24 -> 28
~ _ZN7BTDebug4freeEv.cold.1 : 24 -> 28
~ _ZN7BTDebug4freeEv.cold.2 : 24 -> 28
~ _ZN7BTDebug4freeEv.cold.3 : 24 -> 28
~ _ZN7BTDebug4freeEv.cold.4 : 24 -> 28
~ _ZN7BTDebug4freeEv.cold.5 : 24 -> 28
~ _ZN7BTDebug11openServiceEP14BTDebugService.cold.1 : 24 -> 28
~ _ZN7BTDebug20asyncEventThreadCallEPvS0_.cold.1 : 40 -> 44
~ _ZN7BTDebug20asyncEventThreadCallEPvS0_.cold.2 : 24 -> 28
~ _ZN7BTDebug17asyncEventHandlerEv.cold.1 : 24 -> 28
~ _ZN7BTDebug17asyncEventHandlerEv.cold.2 : 24 -> 28
~ _ZN7BTDebug13coreDumpGatedEPNS_15CoreDumpContextE.cold.1 : 24 -> 28
~ _ZN7BTDebug16coreDumpCompleteEPviy.cold.1 : 24 -> 28
~ _ZN7BTDebug21coreDumpCompleteGatedEPNS_15CoreDumpContextEiy.cold.1 : 24 -> 28
~ _ZN7BTDebug18enableLoggingGatedEjjPK13LogFlowParamsj.cold.1 : 24 -> 28
~ _ZN7BTDebug21enableLoggingInternalEv.cold.1 : 24 -> 28
~ _ZN7BTDebug21enableLoggingInternalEv.cold.2 : 24 -> 28
~ _ZN7BTDebug21enableLoggingInternalEv.cold.3 : 24 -> 28
~ _ZN7BTDebug21enableLoggingInternalEv.cold.4 : 24 -> 28
~ _ZN7BTDebug21enableLoggingInternalEv.cold.5 : 24 -> 28
~ _ZN7BTDebug22disableLoggingInternalEv.cold.1 : 24 -> 28
~ _ZN7BTDebug22disableLoggingInternalEv.cold.2 : 24 -> 28
~ _ZN7BTDebug16readLogsCompleteEPviPN14BTDebugService7LogDataEj.cold.1 : 24 -> 28
~ _ZN7BTDebug16readLogsCompleteEPviPN14BTDebugService7LogDataEj.cold.2 : 24 -> 28
~ _ZN7BTDebug16readLogsCompleteEPviPN14BTDebugService7LogDataEj.cold.3 : 24 -> 28
~ _ZN7BTDebug18mapCrashInfoBufferEv.cold.1 : 24 -> 28
```
