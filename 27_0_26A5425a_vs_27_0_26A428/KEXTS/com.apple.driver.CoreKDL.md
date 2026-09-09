## com.apple.driver.CoreKDL

> `com.apple.driver.CoreKDL`

```diff

   __TEXT.__const: 0xc8
   __TEXT.__cstring: 0x881
   __TEXT.__os_log: 0xffa
-  __TEXT_EXEC.__text: 0x3a78
+  __TEXT_EXEC.__text: 0x3c20
   __TEXT_EXEC.__auth_stubs: 0x1e0
   __DATA.__data: 0xc8
   __DATA.__common: 0x60
Functions:
~ __ZN13CoreKDLDriver9MetaClassC1Ev : 72 -> 76
~ __ZN13CoreKDLDriverC2EPK11OSMetaClass : 96 -> 100
~ __ZN13CoreKDLDriverD2Ev : 200 -> 204
~ __ZN13CoreKDLDriverD1Ev : 200 -> 204
~ __ZN13CoreKDLDriverD0Ev : 68 -> 72
~ __ZN13CoreKDLDriver9MetaClassC2Ev : 72 -> 76
~ __ZNK13CoreKDLDriver9MetaClass5allocEv : 52 -> 56
~ __ZN13CoreKDLDriverC2Ev : 132 -> 136
~ __ZN13CoreKDLDriver5startEP9IOService : 772 -> 776
~ __ZN13CoreKDLDriver17sepMessageHandlerEPvS0_ : 132 -> 136
~ __ZN13CoreKDLDriver4stopEP9IOService : 348 -> 352
~ __ZN13CoreKDLDriver4freeEv : 292 -> 296
~ __ZN13CoreKDLDriver7powerOnEv : 260 -> 264
~ __ZN13CoreKDLDriver17getHibernateStateEv : 368 -> 372
~ __ZN13CoreKDLDriver25handleWakeFromHibernationEv : 96 -> 100
~ __ZN13CoreKDLDriver8initSKDLEv : 328 -> 332
~ __ZN13CoreKDLDriver8powerOffEv : 148 -> 152
~ __ZN13CoreKDLDriver13setPowerStateEmP9IOService : 140 -> 144
~ __ZN13CoreKDLDriver18setPowerStateGatedEPm : 124 -> 128
~ ____ZN13CoreKDLDriver17sepMessageHandlerEPvS0__block_invoke : 240 -> 244
~ __ZN13CoreKDLDriver22setSKDLProtocolVersionEv : 192 -> 196
~ __ZN13CoreKDLDriver20sendKextReceiptToSEPEv : 316 -> 320
~ __ZN13CoreKDLDriver25commandOffendingKextsInfoEP38KDLDriverCommandOffendingKextsInfoInV1mP18IOMemoryDescriptorPj : 544 -> 548
~ __ZN13CoreKDLDriver16writeBytesToIOMDEP18IOMemoryDescriptorPKvmPj : 264 -> 268
~ __ZN13CoreKDLDriver25commandListOffendingKextsEP33SKDLCommandListOffendingKextsInV1mP18IOMemoryDescriptorPj : 412 -> 416
~ __ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj : 1248 -> 1252
~ _GLOBAL__sub_I_CoreKDLDriver.cpp : 80 -> 84
~ __ZN17CoreKDLUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN17CoreKDLUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN17CoreKDLUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN17CoreKDLUserClientD0Ev : 68 -> 72
~ __ZN17CoreKDLUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK17CoreKDLUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN17CoreKDLUserClientC1Ev : 88 -> 92
~ __ZN17CoreKDLUserClientC2Ev : 88 -> 92
~ __ZN17CoreKDLUserClient17extPerformCommandEP13CoreKDLDriverPvP25IOExternalMethodArguments : 732 -> 736
~ __ZN17CoreKDLUserClient12initWithTaskEP4taskPvjP12OSDictionary : 352 -> 356
~ __ZN17CoreKDLUserClient11clientCloseEv : 200 -> 204
~ __ZN17CoreKDLUserClient5startEP9IOService : 228 -> 232
~ __ZN17CoreKDLUserClient4stopEP9IOService : 284 -> 288
~ __ZN17CoreKDLUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 244 -> 248
~ _GLOBAL__sub_I_CoreKDLUserClient.cpp : 80 -> 84
~ __ZN9os_detail21panic_trapping_policy4trapEPKc : 48 -> 52
~ _ZN13CoreKDLDriver5startEP9IOService.cold.1 : 72 -> 76
~ _ZN13CoreKDLDriver5startEP9IOService.cold.2 : 72 -> 76
~ _ZN13CoreKDLDriver5startEP9IOService.cold.3 : 72 -> 76
~ _ZN13CoreKDLDriver5startEP9IOService.cold.4 : 72 -> 76
~ _ZN13CoreKDLDriver5startEP9IOService.cold.5 : 72 -> 76
~ _ZN13CoreKDLDriver4freeEv.cold.1 : 24 -> 28
~ _ZN13CoreKDLDriver4freeEv.cold.2 : 24 -> 28
~ _ZN13CoreKDLDriver4freeEv.cold.3 : 16 -> 20
~ _ZN13CoreKDLDriver4freeEv.cold.5 : 24 -> 28
~ _ZN13CoreKDLDriver7powerOnEv.cold.1 : 68 -> 72
~ _ZN13CoreKDLDriver7powerOnEv.cold.2 : 68 -> 72
~ _ZN13CoreKDLDriver8initSKDLEv.cold.1 : 68 -> 72
~ _ZN13CoreKDLDriver8initSKDLEv.cold.2 : 68 -> 72
~ _ZN13CoreKDLDriver8powerOffEv.cold.1 : 68 -> 72
~ _ZN13CoreKDLDriver13setPowerStateEmP9IOService.cold.1 : 72 -> 76
~ ___ZN13CoreKDLDriver17sepMessageHandlerEPvS0__block_invoke.cold.1 : 72 -> 76
~ _ZN13CoreKDLDriver22setSKDLProtocolVersionEv.cold.1 : 68 -> 72
~ _ZN13CoreKDLDriver20sendKextReceiptToSEPEv.cold.1 : 68 -> 72
~ _ZN13CoreKDLDriver20sendKextReceiptToSEPEv.cold.2 : 68 -> 72
~ _ZN13CoreKDLDriver20sendKextReceiptToSEPEv.cold.3 : 72 -> 76
~ _ZN13CoreKDLDriver20sendKextReceiptToSEPEv.cold.4 : 80 -> 84
~ _ZN13CoreKDLDriver25commandOffendingKextsInfoEP38KDLDriverCommandOffendingKextsInfoInV1mP18IOMemoryDescriptorPj.cold.1 : 68 -> 72
~ _ZN13CoreKDLDriver25commandOffendingKextsInfoEP38KDLDriverCommandOffendingKextsInfoInV1mP18IOMemoryDescriptorPj.cold.2 : 68 -> 72
~ _ZN13CoreKDLDriver25commandOffendingKextsInfoEP38KDLDriverCommandOffendingKextsInfoInV1mP18IOMemoryDescriptorPj.cold.3 : 24 -> 28
~ _ZN13CoreKDLDriver25commandOffendingKextsInfoEP38KDLDriverCommandOffendingKextsInfoInV1mP18IOMemoryDescriptorPj.cold.7 : 72 -> 76
~ _ZN13CoreKDLDriver25commandOffendingKextsInfoEP38KDLDriverCommandOffendingKextsInfoInV1mP18IOMemoryDescriptorPj.cold.8 : 72 -> 76
~ _ZN13CoreKDLDriver25commandOffendingKextsInfoEP38KDLDriverCommandOffendingKextsInfoInV1mP18IOMemoryDescriptorPj.cold.9 : 72 -> 76
~ _ZN13CoreKDLDriver25commandOffendingKextsInfoEP38KDLDriverCommandOffendingKextsInfoInV1mP18IOMemoryDescriptorPj.cold.10 : 72 -> 76
~ _ZN13CoreKDLDriver25commandOffendingKextsInfoEP38KDLDriverCommandOffendingKextsInfoInV1mP18IOMemoryDescriptorPj.cold.11 : 72 -> 76
~ _ZN13CoreKDLDriver25commandOffendingKextsInfoEP38KDLDriverCommandOffendingKextsInfoInV1mP18IOMemoryDescriptorPj.cold.12 : 72 -> 76
~ _ZN13CoreKDLDriver16writeBytesToIOMDEP18IOMemoryDescriptorPKvmPj.cold.1 : 72 -> 76
~ _ZN13CoreKDLDriver16writeBytesToIOMDEP18IOMemoryDescriptorPKvmPj.cold.2 : 72 -> 76
~ _ZN13CoreKDLDriver16writeBytesToIOMDEP18IOMemoryDescriptorPKvmPj.cold.3 : 72 -> 76
~ _ZN13CoreKDLDriver16writeBytesToIOMDEP18IOMemoryDescriptorPKvmPj.cold.4 : 72 -> 76
~ _ZN13CoreKDLDriver25commandListOffendingKextsEP33SKDLCommandListOffendingKextsInV1mP18IOMemoryDescriptorPj.cold.1 : 68 -> 72
~ _ZN13CoreKDLDriver25commandListOffendingKextsEP33SKDLCommandListOffendingKextsInV1mP18IOMemoryDescriptorPj.cold.2 : 72 -> 76
~ _ZN13CoreKDLDriver25commandListOffendingKextsEP33SKDLCommandListOffendingKextsInV1mP18IOMemoryDescriptorPj.cold.6 : 72 -> 76
~ _ZN13CoreKDLDriver25commandListOffendingKextsEP33SKDLCommandListOffendingKextsInV1mP18IOMemoryDescriptorPj.cold.7 : 72 -> 76
~ _ZN13CoreKDLDriver25commandListOffendingKextsEP33SKDLCommandListOffendingKextsInV1mP18IOMemoryDescriptorPj.cold.8 : 72 -> 76
~ _ZN13CoreKDLDriver25commandListOffendingKextsEP33SKDLCommandListOffendingKextsInV1mP18IOMemoryDescriptorPj.cold.9 : 72 -> 76
~ _ZN13CoreKDLDriver25commandListOffendingKextsEP33SKDLCommandListOffendingKextsInV1mP18IOMemoryDescriptorPj.cold.10 : 72 -> 76
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.1 : 68 -> 72
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.2 : 68 -> 72
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.3 : 72 -> 76
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.4 : 72 -> 76
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.5 : 68 -> 72
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.6 : 68 -> 72
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.7 : 68 -> 72
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.8 : 68 -> 72
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.9 : 72 -> 76
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.10 : 80 -> 84
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.11 : 72 -> 76
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.12 : 72 -> 76
~ _ZN13CoreKDLDriver19performCommandGatedEP18IOMemoryDescriptorS1_Pj.cold.13 : 72 -> 76
~ _ZN17CoreKDLUserClient17extPerformCommandEP13CoreKDLDriverPvP25IOExternalMethodArguments.cold.1 : 112 -> 116
~ _ZN17CoreKDLUserClient17extPerformCommandEP13CoreKDLDriverPvP25IOExternalMethodArguments.cold.2 : 72 -> 76
~ _ZN17CoreKDLUserClient17extPerformCommandEP13CoreKDLDriverPvP25IOExternalMethodArguments.cold.3 : 72 -> 76
~ _ZN17CoreKDLUserClient12initWithTaskEP4taskPvjP12OSDictionary.cold.1 : 72 -> 76
~ _ZN17CoreKDLUserClient12initWithTaskEP4taskPvjP12OSDictionary.cold.2 : 72 -> 76
~ _ZN17CoreKDLUserClient12initWithTaskEP4taskPvjP12OSDictionary.cold.3 : 72 -> 76
~ _ZN17CoreKDLUserClient11clientCloseEv.cold.1 : 72 -> 76
~ _ZN17CoreKDLUserClient5startEP9IOService.cold.1 : 72 -> 76
~ _ZN17CoreKDLUserClient5startEP9IOService.cold.2 : 72 -> 76
```
