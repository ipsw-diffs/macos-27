## com.apple.plugin.IOAVBDiscoveryPlugin

> `com.apple.plugin.IOAVBDiscoveryPlugin`

```diff

   __TEXT.__cstring: 0x80e
   __TEXT.__os_log: 0x1abb
   __TEXT.__const: 0x66
-  __TEXT_EXEC.__text: 0x7268
+  __TEXT_EXEC.__text: 0x73e0
   __TEXT_EXEC.__auth_stubs: 0x2e0
   __DATA.__data: 0xc8
   __DATA.__common: 0x100
Functions:
~ __ZN16IOAVB17221Entity9MetaClassC1Ev : 72 -> 76
~ __ZN16IOAVB17221EntityC2EPK11OSMetaClass : 52 -> 56
~ __ZN16IOAVB17221EntityC1EPK11OSMetaClass : 52 -> 56
~ __ZN16IOAVB17221EntityD0Ev : 68 -> 72
~ __ZN16IOAVB17221Entity9MetaClassC2Ev : 72 -> 76
~ __ZNK16IOAVB17221Entity9MetaClass5allocEv : 104 -> 108
~ __ZN16IOAVB17221EntityC1Ev : 88 -> 92
~ __ZN16IOAVB17221EntityC2Ev : 88 -> 92
~ __ZN16IOAVB17221Entity4initEhyyjttttjjyhPhyttt : 880 -> 884
~ __ZN16IOAVB17221Entity5startEP9IOService : 240 -> 244
~ __ZN16IOAVB17221Entity20publishADPPropertiesEb : 1960 -> 1964
~ __ZN16IOAVB17221Entity4freeEv : 112 -> 116
~ __ZN16IOAVB17221Entity22updateEntityParametersEhyyjttttjjyhPhyttt : 632 -> 636
~ __ZN16IOAVB17221Entity15timeToLiveTimerEv : 360 -> 364
~ _GLOBAL__sub_I_IOAVB17221Entity.cpp : 80 -> 84
~ __ZN25IOAVB17221EntityDiscovery9MetaClassC1Ev : 72 -> 76
~ __ZN25IOAVB17221EntityDiscoveryC2EPK11OSMetaClass : 52 -> 56
~ __ZN25IOAVB17221EntityDiscoveryC1EPK11OSMetaClass : 52 -> 56
~ __ZN25IOAVB17221EntityDiscoveryD0Ev : 68 -> 72
~ __ZN25IOAVB17221EntityDiscovery9MetaClassC2Ev : 72 -> 76
~ __ZNK25IOAVB17221EntityDiscovery9MetaClass5allocEv : 104 -> 108
~ __ZN25IOAVB17221EntityDiscoveryC1Ev : 88 -> 92
~ __ZN25IOAVB17221EntityDiscoveryC2Ev : 88 -> 92
~ __ZN25IOAVB17221EntityDiscovery4initEP12OSDictionary : 1208 -> 1212
~ __ZN25IOAVB17221EntityDiscovery17timeToLiveTimeoutEP8OSObjectP18IOTimerEventSource : 60 -> 64
~ __ZN25IOAVB17221EntityDiscovery4freeEv : 920 -> 924
~ __ZN25IOAVB17221EntityDiscovery5startEP9IOService : 1808 -> 1812
~ __ZN25IOAVB17221EntityDiscovery19filterInputCallbackEPvP7__ifnetjPP6__mbufPPc : 36 -> 40
~ __ZN25IOAVB17221EntityDiscovery4stopEP9IOService : 1064 -> 1068
~ __ZN25IOAVB17221EntityDiscovery7messageEjP9IOServicePv : 916 -> 920
~ __ZN25IOAVB17221EntityDiscovery16linkStateUpAsyncEPvS0_ : 144 -> 148
~ __ZN25IOAVB17221EntityDiscovery18linkStateDownAsyncEPvS0_ : 144 -> 148
~ __ZN25IOAVB17221EntityDiscovery15timeToLiveTimerEv : 1300 -> 1304
~ __ZN25IOAVB17221EntityDiscovery9sendFrameEP18IOAVB17221ADPFrame : 424 -> 428
~ __ZN25IOAVB17221EntityDiscovery13setPowerStateEmP9IOService : 212 -> 216
~ __ZN25IOAVB17221EntityDiscovery12sendDiscoverEy : 116 -> 120
~ __ZN25IOAVB17221EntityDiscovery14addLocalEntityEhyyjttttjyhyttt : 1520 -> 1524
~ __ZN25IOAVB17221EntityDiscovery17removeLocalEntityEy : 684 -> 688
~ __ZN25IOAVB17221EntityDiscovery30changedEntityGPTPGrandmasterIDEyy : 580 -> 584
~ __ZN25IOAVB17221EntityDiscovery19addDiscoveredEntityEhyyjttttjjyhPhyttt : 1812 -> 1816
~ __ZN25IOAVB17221EntityDiscovery22removeDiscoveredEntityEy : 612 -> 616
~ __ZN25IOAVB17221EntityDiscovery16receivedDiscoverEy : 668 -> 672
~ __ZN25IOAVB17221EntityDiscovery14cableUnpluggedEv : 924 -> 928
~ __ZN25IOAVB17221EntityDiscovery14cableRepluggedEv : 232 -> 236
~ ____ZN25IOAVB17221EntityDiscovery14cableRepluggedEv_block_invoke : 52 -> 56
~ __ZN25IOAVB17221EntityDiscovery19filterReceivedFrameEPP6__mbufPPc : 376 -> 380
~ _GLOBAL__sub_I_IOAVB17221EntityDiscovery.cpp : 80 -> 84
~ __ZN35IOAVB17221EntityDiscoveryUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN35IOAVB17221EntityDiscoveryUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN35IOAVB17221EntityDiscoveryUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN35IOAVB17221EntityDiscoveryUserClientD0Ev : 68 -> 72
~ __ZN35IOAVB17221EntityDiscoveryUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK35IOAVB17221EntityDiscoveryUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN35IOAVB17221EntityDiscoveryUserClientC1Ev : 88 -> 92
~ __ZN35IOAVB17221EntityDiscoveryUserClientC2Ev : 88 -> 92
~ __ZN35IOAVB17221EntityDiscoveryUserClient12initWithTaskEP4taskPvjP12OSDictionary : 412 -> 416
~ __ZN35IOAVB17221EntityDiscoveryUserClient4freeEv : 128 -> 132
~ __ZN35IOAVB17221EntityDiscoveryUserClient5startEP9IOService : 232 -> 236
~ __ZN35IOAVB17221EntityDiscoveryUserClient4stopEP9IOService : 396 -> 400
~ __ZN35IOAVB17221EntityDiscoveryUserClient11clientCloseEv : 392 -> 396
~ __ZN35IOAVB17221EntityDiscoveryUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 472 -> 476
~ __ZN35IOAVB17221EntityDiscoveryUserClient14addLocalEntityEhyyjttttjyhyttt : 472 -> 476
~ __ZN35IOAVB17221EntityDiscoveryUserClient17removeLocalEntityEy : 564 -> 568
~ _GLOBAL__sub_I_IOAVB17221EntityDiscoveryUserClient.cpp : 80 -> 84
~ __ZN21IOAVB17221LocalEntity9MetaClassC1Ev : 72 -> 76
~ __ZN21IOAVB17221LocalEntityC2EPK11OSMetaClass : 52 -> 56
~ __ZN21IOAVB17221LocalEntityC1EPK11OSMetaClass : 52 -> 56
~ __ZN21IOAVB17221LocalEntityD0Ev : 68 -> 72
~ __ZN21IOAVB17221LocalEntity9MetaClassC2Ev : 72 -> 76
~ __ZNK21IOAVB17221LocalEntity9MetaClass5allocEv : 104 -> 108
~ __ZN21IOAVB17221LocalEntityC1Ev : 88 -> 92
~ __ZN21IOAVB17221LocalEntityC2Ev : 88 -> 92
~ __ZN21IOAVB17221LocalEntity15timeToLiveTimerEv : 208 -> 212
~ __ZN21IOAVB17221LocalEntity15resetTimeToLiveEv : 196 -> 200
~ __ZN21IOAVB17221LocalEntity15setFramePayloadEP18IOAVB17221ADPFrame : 296 -> 300
~ _GLOBAL__sub_I_IOAVB17221LocalEntity.cpp : 80 -> 84
~ __ZN22IOAVB17221RemoteEntity9MetaClassC1Ev : 72 -> 76
~ __ZN22IOAVB17221RemoteEntityC2EPK11OSMetaClass : 52 -> 56
~ __ZN22IOAVB17221RemoteEntityC1EPK11OSMetaClass : 52 -> 56
~ __ZN22IOAVB17221RemoteEntityD0Ev : 68 -> 72
~ __ZN22IOAVB17221RemoteEntity9MetaClassC2Ev : 72 -> 76
~ __ZNK22IOAVB17221RemoteEntity9MetaClass5allocEv : 104 -> 108
~ __ZN22IOAVB17221RemoteEntityC1Ev : 88 -> 92
~ __ZN22IOAVB17221RemoteEntityC2Ev : 88 -> 92
~ _GLOBAL__sub_I_IOAVB17221RemoteEntity.cpp : 80 -> 84
~ __ZN19IOAVB17221EntityMAC9MetaClassC1Ev : 72 -> 76
~ __ZN19IOAVB17221EntityMACC2EPK11OSMetaClass : 52 -> 56
~ __ZN19IOAVB17221EntityMACC1EPK11OSMetaClass : 52 -> 56
~ __ZN19IOAVB17221EntityMACD0Ev : 68 -> 72
~ __ZN19IOAVB17221EntityMAC9MetaClassC2Ev : 72 -> 76
~ __ZNK19IOAVB17221EntityMAC9MetaClass5allocEv : 104 -> 108
~ __ZN19IOAVB17221EntityMACC1Ev : 88 -> 92
~ __ZN19IOAVB17221EntityMACC2Ev : 88 -> 92
~ _GLOBAL__sub_I_IOAVB17221EntityMAC.cpp : 80 -> 84
```
