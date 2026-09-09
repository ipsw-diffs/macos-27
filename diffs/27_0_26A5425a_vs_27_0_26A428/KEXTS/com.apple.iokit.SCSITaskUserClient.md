## com.apple.iokit.SCSITaskUserClient

> `com.apple.iokit.SCSITaskUserClient`

```diff

 565.0.1.0.0
   __TEXT.__cstring: 0x22e
-  __TEXT_EXEC.__text: 0x50a8
+  __TEXT_EXEC.__text: 0x51bc
   __TEXT_EXEC.__auth_stubs: 0x380
   __DATA.__data: 0xc8
   __DATA.__common: 0x88
Functions:
~ __ZN24SCSITaskUserClientIniter9MetaClassC1Ev : 72 -> 76
~ __ZN24SCSITaskUserClientIniterC2EPK11OSMetaClass : 52 -> 56
~ __ZN24SCSITaskUserClientIniterC1EPK11OSMetaClass : 52 -> 56
~ __ZN24SCSITaskUserClientIniterD0Ev : 68 -> 72
~ __ZN24SCSITaskUserClientIniter9MetaClassC2Ev : 72 -> 76
~ __ZNK24SCSITaskUserClientIniter9MetaClass5allocEv : 104 -> 108
~ __ZN24SCSITaskUserClientIniterC1Ev : 88 -> 92
~ __ZN24SCSITaskUserClientIniterC2Ev : 88 -> 92
~ __ZN24SCSITaskUserClientIniter5startEP9IOService : 1148 -> 1152
~ _GLOBAL__sub_I_SCSITaskUserClientIniter.cpp : 80 -> 84
~ __ZN18SCSITaskUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN18SCSITaskUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN18SCSITaskUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN18SCSITaskUserClientD0Ev : 68 -> 72
~ __ZN18SCSITaskUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK18SCSITaskUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN18SCSITaskUserClientC1Ev : 88 -> 92
~ __ZN18SCSITaskUserClientC2Ev : 88 -> 92
~ __ZN18SCSITaskUserClient6detachEP9IOService : 184 -> 188
~ __ZN18SCSITaskUserClient12didTerminateEP9IOServicejPb : 348 -> 352
~ __ZN18SCSITaskUserClient15HandleTerminateEP9IOService : 136 -> 140
~ __ZN18SCSITaskUserClient4freeEv : 352 -> 356
~ __ZN18SCSITaskUserClient20ReleaseTaskReferenceEi : 532 -> 536
~ __ZN18SCSITaskUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 1700 -> 1704
~ __ZN18SCSITaskUserClient19CreateTaskReferenceEPi : 532 -> 536
~ __ZN18SCSITaskUserClient11ExecuteTaskEP12SCSITaskDataj : 1412 -> 1416
~ _GLOBAL__sub_I_SCSITaskUserClient.cpp : 80 -> 84
~ _OUTLINED_FUNCTION_15 : 24 -> 32
~ _OUTLINED_FUNCTION_17 : 48 -> 24
~ _OUTLINED_FUNCTION_18 : 28 -> 48
~ _OUTLINED_FUNCTION_20 : 24 -> 28
~ _OUTLINED_FUNCTION_23 : 16 -> 24
~ _OUTLINED_FUNCTION_26 : 12 -> 16
~ __ZN16STUCWorkLoopLock9MetaClassC1Ev : 72 -> 76
~ __ZN16STUCWorkLoopLockC2EPK11OSMetaClass : 52 -> 56
~ __ZN16STUCWorkLoopLockC1EPK11OSMetaClass : 52 -> 56
~ __ZN16STUCWorkLoopLockD0Ev : 68 -> 72
~ __ZN16STUCWorkLoopLock9MetaClassC2Ev : 72 -> 76
~ __ZNK16STUCWorkLoopLock9MetaClass5allocEv : 104 -> 108
~ __ZN16STUCWorkLoopLockC1Ev : 88 -> 92
~ __ZN16STUCWorkLoopLockC2Ev : 88 -> 92
~ _GLOBAL__sub_I_STUCWorkLoopLock.cpp : 80 -> 84
~ __ZN18SCSITaskUserClient12initWithTaskEP4taskPvjP12OSDictionary : 204 -> 208
~ __ZN18SCSITaskUserClient6attachEP9IOService : 160 -> 164
~ __ZN18SCSITaskUserClient11clientCloseEv : 224 -> 228
~ __ZN18SCSITaskUserClient16SetAsyncCallbackEPyiyy : 256 -> 264
~ __ZN18SCSITaskUserClient26IsExclusiveAccessAvailableEv : 104 -> 108
~ __ZN18SCSITaskUserClient21ObtainExclusiveAccessEv : 388 -> 392
~ __ZN18SCSITaskUserClient22ReleaseExclusiveAccessEv : 388 -> 392
~ __ZN18SCSITaskUserClient9AbortTaskEi : 204 -> 212
~ __ZN18SCSITaskUserClient10SetBuffersEiyyj : 332 -> 340
~ __ZN18SCSITaskUserClient7InquiryEP18AppleInquiryStructjP14SCSITaskStatusPj : 428 -> 432
~ __ZN18SCSITaskUserClient13TestUnitReadyEyPyPj : 308 -> 312
~ __ZN18SCSITaskUserClient14GetPerformanceEP25AppleGetPerformanceStructjP14SCSITaskStatusPj : 416 -> 420
~ __ZN18SCSITaskUserClient16GetConfigurationEP27AppleGetConfigurationStructjP14SCSITaskStatusPj : 416 -> 420
~ __ZN18SCSITaskUserClient11ModeSense10EP22AppleModeSense10StructjP14SCSITaskStatusPj : 440 -> 444
~ __ZN18SCSITaskUserClient26SetWriteParametersModePageEP34AppleWriteParametersModePageStructjP14SCSITaskStatusPj : 412 -> 416
~ __ZN18SCSITaskUserClient12GetTrayStateEPj : 204 -> 208
~ __ZN18SCSITaskUserClient12SetTrayStateEj : 168 -> 172
~ __ZN18SCSITaskUserClient19ReadTableOfContentsEP30AppleReadTableOfContentsStructjP14SCSITaskStatusPj : 452 -> 456
~ __ZN18SCSITaskUserClient19ReadDiscInformationEP23AppleReadDiscInfoStructjP14SCSITaskStatusPj : 376 -> 380
~ __ZN18SCSITaskUserClient20ReadTrackInformationEP24AppleReadTrackInfoStructjP14SCSITaskStatusPj : 404 -> 408
~ __ZN18SCSITaskUserClient17ReadDiscStructureEP28AppleReadDiscStructureStructjP14SCSITaskStatusPj : 420 -> 424
~ __ZN18SCSITaskUserClient10SetCDSpeedEP21AppleSetCDSpeedStructjP14SCSITaskStatusPj : 312 -> 316
~ __ZN18SCSITaskUserClient20ReadFormatCapacitiesEP31AppleReadFormatCapacitiesStructjP14SCSITaskStatusPj : 364 -> 368
~ __ZN18SCSITaskUserClient12SetStreamingEP23AppleSetStreamingStructjP14SCSITaskStatusPj : 416 -> 420
~ __ZN18SCSITaskUserClient12ValidateTaskEP8SCSITaskP12SCSITaskDataj : 404 -> 408
~ __ZN18SCSITaskUserClient13sTaskCallbackEP8OSObject : 104 -> 108
~ __ZN18SCSITaskUserClient9SetupTaskEPP8SCSITask : 168 -> 172
~ __ZN18SCSITaskUserClient14PrepareBuffersEPP18IOMemoryDescriptoryyj : 180 -> 184
~ __ZN18SCSITaskUserClient11SendCommandEP8SCSITaskyP14SCSITaskStatus : 368 -> 372
~ __ZN18SCSITaskUserClient12TaskCallbackEP8SCSITaskP14SCSITaskRefCon : 844 -> 824
~ __ZN16STUCWorkLoopLock18CreateWithWorkLoopEP8OSObjectP10IOWorkLoop : 232 -> 236
```
