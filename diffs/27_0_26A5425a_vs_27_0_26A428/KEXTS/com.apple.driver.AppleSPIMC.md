## com.apple.driver.AppleSPIMC

> `com.apple.driver.AppleSPIMC`

```diff

 40.0.0.0.0
   __TEXT.__const: 0x10
   __TEXT.__cstring: 0x179d
-  __TEXT_EXEC.__text: 0x712c
+  __TEXT_EXEC.__text: 0x7290
   __TEXT_EXEC.__auth_stubs: 0x250
   __DATA.__data: 0xc4
   __DATA.__common: 0x68
Functions:
~ __ZN20AppleSPIMCController9MetaClassC1Ev : 72 -> 76
~ __ZN20AppleSPIMCControllerC2EPK11OSMetaClass : 52 -> 56
~ __ZN20AppleSPIMCControllerC1EPK11OSMetaClass : 52 -> 56
~ __ZN20AppleSPIMCControllerD0Ev : 68 -> 72
~ __ZN20AppleSPIMCController9MetaClassC2Ev : 72 -> 76
~ __ZNK20AppleSPIMCController9MetaClass5allocEv : 104 -> 108
~ __ZN20AppleSPIMCControllerC1Ev : 88 -> 92
~ __ZN20AppleSPIMCControllerC2Ev : 88 -> 92
~ __ZN20AppleSPIMCController5startEP9IOService : 2756 -> 2760
~ __ZN25AppleSPIMCControllerStats6createEP16AppleARMIODevice : 136 -> 140
~ __ZN20AppleSPIMCController22_powerOffTimerCallbackEP18IOTimerEventSource : 200 -> 204
~ __ZN20AppleSPIMCController20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 336 -> 340
~ __ZN20AppleSPIMCController20_platformActionGatedEm : 112 -> 116
~ __ZN20AppleSPIMCController22setSPIControllerActiveEb : 1208 -> 1212
~ __ZN20AppleSPIMCController9_logEntryEPKcS1_z : 300 -> 304
~ __ZN20AppleSPIMCController14validSPIConfigEP17AppleARMSPIConfig : 256 -> 260
~ __ZN20AppleSPIMCController17executeSPICommandEP18AppleARMSPICommand : 524 -> 528
~ __ZN20AppleSPIMCController22_executeSPICommandNULLEP18AppleARMSPICommand : 132 -> 136
~ __ZN20AppleSPIMCController23_configureHardwareDelayEv : 1208 -> 1212
~ __ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand : 2404 -> 2408
~ __ZN25AppleSPIMCControllerStats12spiXferStartEP18AppleARMSPICommand : 84 -> 88
~ __ZN25AppleSPIMCControllerStats11spiXferDoneEP18AppleARMSPICommand : 140 -> 144
~ __ZN20AppleSPIMCController21_executeSPICommandPIOEP18AppleARMSPICommand : 3988 -> 3992
~ __ZN20AppleSPIMCController9_dmaAbortEP18AppleARMSPICommandiPKcS3_ : 428 -> 432
~ __ZN20AppleSPIMCController8_dmaStopEP16IODMAEventSourcePjyPKc : 536 -> 540
~ __ZN20AppleSPIMCController15_dmaEventActionEP16IODMAEventSourceP12IODMACommandiy : 716 -> 720
~ __ZN20AppleSPIMCController20_interruptActionSubrEv : 732 -> 736
~ __ZN20AppleSPIMCController20_interruptActionDoneEbPj : 404 -> 408
~ __ZN20AppleSPIMCController16_interruptActionEP22IOInterruptEventSourcei : 308 -> 312
~ __ZN20AppleSPIMCController14_interruptPollEj : 576 -> 580
~ __ZN20AppleSPIMCController14_setInternalCSEb : 164 -> 168
~ __ZN20AppleSPIMCController18_enableDeviceClockEb : 320 -> 324
~ __ZN20AppleSPIMCController15_getTxFIFOCountEv : 64 -> 68
~ __ZN20AppleSPIMCController15_getTxFIFOSpaceEv : 72 -> 76
~ __ZN20AppleSPIMCController15_getRxFIFOCountEv : 64 -> 68
~ __ZN20AppleSPIMCController15_getRxFIFOSpaceEv : 72 -> 76
~ __ZN25AppleSPIMCControllerStats9MetaClassC1Ev : 72 -> 76
~ __ZN25AppleSPIMCControllerStatsC2EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleSPIMCControllerStatsC1EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleSPIMCControllerStatsD0Ev : 68 -> 72
~ __ZN25AppleSPIMCControllerStats9MetaClassC2Ev : 72 -> 76
~ __ZNK25AppleSPIMCControllerStats9MetaClass5allocEv : 104 -> 108
~ __ZN25AppleSPIMCControllerStatsC1Ev : 88 -> 92
~ __ZN25AppleSPIMCControllerStatsC2Ev : 88 -> 92
~ __ZN25AppleSPIMCControllerStats4initEv : 152 -> 156
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize : 2520 -> 2524
~ _GLOBAL__sub_I_AppleSPIMC.cpp : 140 -> 144
~ __GLOBAL__D_a : 56 -> 60
~ _ZN20AppleSPIMCController5startEP9IOService.cold.1 : 116 -> 120
~ _ZN20AppleSPIMCController5startEP9IOService.cold.2 : 112 -> 116
~ _ZN20AppleSPIMCController5startEP9IOService.cold.3 : 116 -> 120
~ _ZN20AppleSPIMCController5startEP9IOService.cold.4 : 128 -> 132
~ _ZN25AppleSPIMCControllerStats6createEP16AppleARMIODevice.cold.1 : 36 -> 40
~ _ZN20AppleSPIMCController17executeSPICommandEP18AppleARMSPICommand.cold.1 : 116 -> 120
~ _ZN20AppleSPIMCController17executeSPICommandEP18AppleARMSPICommand.cold.2 : 116 -> 120
~ _ZN20AppleSPIMCController17executeSPICommandEP18AppleARMSPICommand.cold.3 : 116 -> 120
~ _ZN20AppleSPIMCController17executeSPICommandEP18AppleARMSPICommand.cold.4 : 116 -> 120
~ _ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.1 : 124 -> 128
~ _ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.2 : 136 -> 140
~ _ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.3 : 140 -> 144
~ _ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.4 : 140 -> 144
~ _ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.5 : 136 -> 140
~ _ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.6 : 124 -> 128
~ _ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.7 : 124 -> 128
~ _ZN20AppleSPIMCController21_executeSPICommandPIOEP18AppleARMSPICommand.cold.1 : 132 -> 136
~ _ZN20AppleSPIMCController21_executeSPICommandPIOEP18AppleARMSPICommand.cold.2 : 132 -> 136
~ _ZN20AppleSPIMCController21_executeSPICommandPIOEP18AppleARMSPICommand.cold.3 : 96 -> 100
~ _ZN20AppleSPIMCController21_executeSPICommandPIOEP18AppleARMSPICommand.cold.4 : 96 -> 100
~ _ZN20AppleSPIMCController14_interruptPollEj.cold.1 : 96 -> 100
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.1 : 116 -> 120
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.2 : 116 -> 120
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.3 : 116 -> 120
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.4 : 116 -> 120
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.5 : 96 -> 100
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.6 : 96 -> 100
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.7 : 96 -> 100
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.8 : 96 -> 100
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.9 : 108 -> 112
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.10 : 108 -> 112
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.11 : 108 -> 112
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.12 : 108 -> 112
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.13 : 112 -> 116
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.14 : 112 -> 116
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.15 : 112 -> 116
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.16 : 112 -> 116
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.17 : 112 -> 116
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.18 : 112 -> 116
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.19 : 144 -> 148
~ _ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.20 : 112 -> 116
```
