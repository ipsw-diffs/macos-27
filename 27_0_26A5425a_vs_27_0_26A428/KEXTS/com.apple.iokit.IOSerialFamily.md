## com.apple.iokit.IOSerialFamily

> `com.apple.iokit.IOSerialFamily`

```diff

 118.0.0.0.0
   __TEXT.__const: 0x30
   __TEXT.__cstring: 0x640
-  __TEXT_EXEC.__text: 0x7d04
+  __TEXT_EXEC.__text: 0x7e84
   __TEXT_EXEC.__auth_stubs: 0x4a0
   __DATA.__data: 0x258
   __DATA.__common: 0x130
Functions:
~ __ZN17IOSerialBSDClient9MetaClassC1Ev : 72 -> 76
~ __ZN17IOSerialBSDClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN17IOSerialBSDClientD0Ev : 68 -> 72
~ __ZNK17IOSerialBSDClient9MetaClass5allocEv : 104 -> 108
~ __ZN17IOSerialBSDClientC1Ev : 88 -> 92
~ __ZN6kernel24IOSerialBSDClientGlobalsD1Ev : 624 -> 628
~ __ZN17IOSerialBSDClient8iossopenEiiiP4proc : 508 -> 512
~ __ZN17IOSerialBSDClient9iosscloseEiiiP4proc : 280 -> 284
~ __ZN17IOSerialBSDClient8iossreadEiP3uioi : 392 -> 396
~ __ZN17IOSerialBSDClient9iosswriteEiP3uioi : 296 -> 300
~ __ZN17IOSerialBSDClient9iossioctlEimPciP4proc : 1700 -> 1704
~ __ZN17IOSerialBSDClient8iossstopEP3ttyi : 328 -> 332
~ __ZN17IOSerialBSDClient10iossselectEiiPvP4proc : 344 -> 348
~ __ZN6kernel24IOSerialBSDClientGlobalsC2Ev : 400 -> 404
~ __ZN6kernel24IOSerialBSDClientGlobals12assign_dev_tEv : 344 -> 348
~ __ZN6kernel24IOSerialBSDClientGlobals11registerTTYEiP17IOSerialBSDClient : 188 -> 192
~ __ZN6kernel24IOSerialBSDClientGlobals18getUniqueTTYSuffixEPK8OSSymbolS3_ib : 692 -> 696
~ __ZN6kernel24IOSerialBSDClientGlobals22releaseUniqueTTYSuffixEPK8OSSymbolS3_ : 220 -> 224
~ __ZN17IOSerialBSDClient14createDevNodesEb : 2548 -> 2552
~ __ZN17IOSerialBSDClient17setBaseTypeForDevEv : 468 -> 472
~ __ZN17IOSerialBSDClient5startEP9IOService : 780 -> 784
~ __ZN17IOSerialBSDClient16cleanupResourcesEv : 264 -> 268
~ __ZN17IOSerialBSDClient18matchPropertyTableEP12OSDictionary : 1068 -> 1072
~ __ZL7devNameP15IORegistryEntry : 132 -> 136
~ __ZN17IOSerialBSDClient4freeEv : 256 -> 260
~ __ZN17IOSerialBSDClient16requestTerminateEP9IOServicej : 100 -> 104
~ __ZN17IOSerialBSDClient13willTerminateEP9IOServicej : 444 -> 448
~ __ZN17IOSerialBSDClient12didTerminateEP9IOServicejPb : 328 -> 332
~ __ZN17IOSerialBSDClient14setOnePropertyEPK8OSSymbolP8OSObject : 84 -> 88
~ __ZN17IOSerialBSDClient11waitForIdleEv : 108 -> 112
~ __ZN17IOSerialBSDClient13setPropertiesEP8OSObject : 444 -> 448
~ __ZN17IOSerialBSDClient4openEiiiP4proc : 1388 -> 1392
~ __ZN17IOSerialBSDClient5closeEiiiP4proc : 904 -> 908
~ __ZN17IOSerialBSDClient13optimiseInputEP7termios : 444 -> 448
~ __ZN17IOSerialBSDClient15convertFlowCtrlEPNS_7SessionEP7termios : 224 -> 228
~ __ZN17IOSerialBSDClient9iossparamEP3ttyP7termios : 972 -> 976
~ __ZN17IOSerialBSDClient9iossstartEP3tty : 244 -> 248
~ __ZN17IOSerialBSDClient13preemptActiveEv : 352 -> 356
~ __ZN17IOSerialBSDClient11initSessionEPNS_7SessionE : 824 -> 828
~ __ZN17IOSerialBSDClient19startConnectTransitEv : 84 -> 88
~ __ZN17IOSerialBSDClient13launchThreadsEv : 252 -> 256
~ __ZN17IOSerialBSDClient11killThreadsEv : 400 -> 404
~ __ZN17IOSerialBSDClient12iossdcddelayEPvS0_ : 252 -> 256
~ __ZN17IOSerialBSDClient12waitOutDelayEPvPK7timevalS3_ : 304 -> 308
~ __ZN17IOSerialBSDClient4mctlEji : 404 -> 408
~ __ZN17IOSerialBSDClient7getDataEPNS_7SessionE : 616 -> 620
~ __ZN17IOSerialBSDClient9procEventEPNS_7SessionE : 380 -> 384
~ __ZN17IOSerialBSDClient6rxFuncEv : 724 -> 728
~ __ZN17IOSerialBSDClient6txloadEPNS_7SessionEPj : 648 -> 652
~ __ZN17IOSerialBSDClient6txFuncEv : 1148 -> 1152
~ _GLOBAL__sub_I_IOSerialBSDClient.cpp : 104 -> 108
~ __GLOBAL__D_a : 56 -> 60
~ __ZN18IOSerialDriverSync9MetaClassC1Ev : 72 -> 76
~ __ZN18IOSerialDriverSyncC2EPK11OSMetaClass : 52 -> 56
~ __ZN18IOSerialDriverSync9MetaClassC2Ev : 72 -> 76
~ __ZN18IOSerialStreamSync9MetaClassC1Ev : 72 -> 76
~ __ZN18IOSerialStreamSyncC2EPK11OSMetaClass : 52 -> 56
~ __ZN18IOSerialStreamSyncC1EPK11OSMetaClass : 52 -> 56
~ __ZN18IOSerialStreamSyncD0Ev : 68 -> 72
~ __ZN18IOSerialStreamSync9MetaClassC2Ev : 72 -> 76
~ __ZNK18IOSerialStreamSync9MetaClass5allocEv : 104 -> 108
~ __ZN18IOSerialStreamSyncC1Ev : 88 -> 92
~ __ZN18IOSerialStreamSyncC2Ev : 88 -> 92
~ __ZN23IORS232SerialStreamSync9MetaClassC1Ev : 72 -> 76
~ __ZN23IORS232SerialStreamSyncC2EPK11OSMetaClass : 52 -> 56
~ __ZN23IORS232SerialStreamSyncC1EPK11OSMetaClass : 52 -> 56
~ __ZN23IORS232SerialStreamSyncD0Ev : 68 -> 72
~ __ZN23IORS232SerialStreamSync9MetaClassC2Ev : 72 -> 76
~ __ZNK23IORS232SerialStreamSync9MetaClass5allocEv : 104 -> 108
~ __ZN23IORS232SerialStreamSyncC1Ev : 88 -> 92
~ __ZN23IORS232SerialStreamSyncC2Ev : 88 -> 92
~ __ZN23IOModemSerialStreamSync9MetaClassC1Ev : 72 -> 76
~ __ZN23IOModemSerialStreamSyncC2EPK11OSMetaClass : 52 -> 56
~ __ZN23IOModemSerialStreamSyncC1EPK11OSMetaClass : 52 -> 56
~ __ZN23IOModemSerialStreamSyncD0Ev : 68 -> 72
~ __ZN23IOModemSerialStreamSync9MetaClassC2Ev : 72 -> 76
~ __ZNK23IOModemSerialStreamSync9MetaClass5allocEv : 104 -> 108
~ __ZN23IOModemSerialStreamSyncC1Ev : 88 -> 92
~ __ZN23IOModemSerialStreamSyncC2Ev : 88 -> 92
~ __ZN18IOSerialStreamSync4initEP12OSDictionaryPv : 72 -> 76
~ __ZN18IOSerialStreamSync6attachEP9IOService : 140 -> 144
~ __ZN18IOSerialStreamSync12copyProviderEv : 92 -> 96
~ __ZN18IOSerialStreamSync11acquirePortEb : 208 -> 212
~ __ZN18IOSerialStreamSync11releasePortEv : 192 -> 196
~ __ZN18IOSerialStreamSync8setStateEjj : 216 -> 220
~ __ZN18IOSerialStreamSync8getStateEv : 180 -> 184
~ __ZN18IOSerialStreamSync10watchStateEPjj : 216 -> 220
~ __ZN18IOSerialStreamSync9nextEventEv : 180 -> 184
~ __ZN18IOSerialStreamSync12executeEventEjj : 216 -> 220
~ __ZN18IOSerialStreamSync12requestEventEjPj : 216 -> 220
~ __ZN18IOSerialStreamSync12enqueueEventEjjb : 232 -> 236
~ __ZN18IOSerialStreamSync12dequeueEventEPjS0_b : 232 -> 236
~ __ZN18IOSerialStreamSync11enqueueDataEPhjPjb : 240 -> 244
~ __ZN18IOSerialStreamSync11dequeueDataEPhjPjj : 240 -> 244
~ _GLOBAL__sub_I_IOSerialStreamSync.cpp : 264 -> 268
~ __GLOBAL__D_a : 80 -> 84
```
