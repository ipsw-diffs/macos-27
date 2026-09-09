## com.apple.driver.driverkit.serial

> `com.apple.driver.driverkit.serial`

```diff

 157.0.0.0.0
   __TEXT.__const: 0x298
   __TEXT.__cstring: 0x137
-  __TEXT_EXEC.__text: 0x6298
+  __TEXT_EXEC.__text: 0x63fc
   __TEXT_EXEC.__auth_stubs: 0x210
   __DATA.__data: 0xc8
   __DATA.__common: 0x60
Functions:
~ __ZN12IOUserSerial9MetaClassC1Ev : 72 -> 76
~ __ZN12IOUserSerialC2EPK11OSMetaClass : 52 -> 56
~ __ZN12IOUserSerialD0Ev : 68 -> 72
~ __ZNK12IOUserSerial9MetaClass5allocEv : 104 -> 108
~ __ZN12IOUserSerialC1Ev : 88 -> 92
~ __ZN22IOUserSerialUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN22IOUserSerialUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN22IOUserSerialUserClientD0Ev : 68 -> 72
~ __ZNK22IOUserSerialUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN22IOUserSerialUserClientC1Ev : 88 -> 92
~ __ZN22IOUserSerialUserClient19clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 152 -> 156
~ __ZN22IOUserSerialUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 1200 -> 1204
~ __ZN12IOUserSerial29acquireWithSpecificationGatedEbP22IOUserSerialUserClienthhP18IOMemoryDescriptorS3_jj : 212 -> 216
~ __ZN22IOUserSerialUserClient5ioctlEmPv : 2448 -> 2452
~ __ZN12IOUserSerial13setPropertiesEP8OSObject : 268 -> 272
~ __ZN12IOUserSerial13newUserClientEP4taskPvjP12OSDictionaryPP12IOUserClient : 476 -> 480
~ __ZN12IOUserSerial4initEP12OSDictionary : 304 -> 308
~ __ZN12IOUserSerial6attachEP9IOService : 136 -> 140
~ __ZN12IOUserSerial5probeEP9IOServicePi : 140 -> 144
~ __ZN12IOUserSerial5startEP9IOService : 36 -> 40
~ __ZN12IOUserSerial13freeResourcesEv : 656 -> 660
~ __ZN12IOUserSerial11acquirePortEb : 288 -> 292
~ __ZN12IOUserSerial14allocResourcesEhhP18IOMemoryDescriptorS1_jj : 1012 -> 1016
~ __ZN12IOUserSerial11releasePortEv : 124 -> 128
~ __ZN12IOUserSerial8setStateEjj : 88 -> 92
~ __ZN12IOUserSerial8getStateEv : 188 -> 192
~ __ZNK12IOUserSerial16hwGetModemStatusEPbS0_S0_S0_ : 224 -> 228
~ __ZN12IOUserSerial12executeEventEjj : 732 -> 736
~ __ZN12IOUserSerial20handleEventLineBreakEb : 148 -> 152
~ __ZN12IOUserSerial11hwResetFIFOEbb : 192 -> 196
~ __ZN12IOUserSerial22handleEventDataLatencyEj : 148 -> 152
~ __ZN12IOUserSerial22handleEventFlowControlEj : 156 -> 160
~ __ZN12IOUserSerial12requestEventEjPj : 504 -> 508
~ __ZN12IOUserSerial11enqueueDataEPhjPjb : 1172 -> 1176
~ __ZN12IOUserSerial11dequeueDataEPhjPjj : 868 -> 872
~ __ZN12IOUserSerial18txBusyTimerExpiredEP18IOTimerEventSource : 152 -> 156
~ __ZN12IOUserSerial10hwActivateEb : 156 -> 160
~ __ZN12IOUserSerial13hwProgramUARTEv : 156 -> 160
~ __ZN12IOUserSerial17hwProgramBaudRateEv : 144 -> 148
~ __ZN12IOUserSerial11hwSendBreakEb : 172 -> 176
~ __ZNK12IOUserSerial12hwProgramMCREbb : 248 -> 252
~ __ZN12IOUserSerial20RxDataAvailable_ImplEv : 96 -> 100
~ __ZN12IOUserSerial25TxFreeSpaceAvailable_ImplEv : 96 -> 100
~ __ZN12IOUserSerial19SetModemStatus_ImplEbbbb : 192 -> 196
~ __ZN22IOUserSerialUserClient5startEP9IOService : 112 -> 116
~ __ZN22IOUserSerialUserClient11clientCloseEv : 136 -> 140
~ __ZZN12IOUserSerial13setPropertiesEP8OSObjectEN3$_08__invokeEPvPK8OSSymbolS1_ : 240 -> 244
~ _GLOBAL__sub_I_IOUserSerial.cpp : 140 -> 144
~ __GLOBAL__D_a : 56 -> 60
~ __ZN12IOUserSerial8DispatchE5IORPC : 44 -> 48
~ __ZN12IOUserSerial9_DispatchEPS_5IORPC : 1096 -> 1100
~ __ZN12IOUserSerial20ConnectQueues_InvokeE5IORPCP15OSMetaClassBasePFiS2_PP24IOBufferMemoryDescriptorPP18IOMemoryDescriptorS8_S7_S7_jjhhE : 344 -> 348
~ __ZN12IOUserSerial23DisconnectQueues_InvokeE5IORPCP15OSMetaClassBasePFiS2_E : 152 -> 156
~ __ZN12IOUserSerial21SetModemStatus_InvokeE5IORPCP15OSMetaClassBasePFiS2_bbbbE : 192 -> 196
~ __ZN12IOUserSerial14RxError_InvokeE5IORPCP15OSMetaClassBasePFiS2_bbbbE : 192 -> 196
~ __ZN12IOUserSerial17HwActivate_InvokeE5IORPCP15OSMetaClassBasePFiS2_E : 152 -> 156
~ __ZN12IOUserSerial19HwDeactivate_InvokeE5IORPCP15OSMetaClassBasePFiS2_E : 152 -> 156
~ __ZN12IOUserSerial9MetaClass8DispatchE5IORPC : 64 -> 68
~ __ZN12IOUserSerial13ConnectQueuesEPP24IOBufferMemoryDescriptorPP18IOMemoryDescriptorS5_S4_S4_jjhhPFiP15OSMetaClassBase5IORPCE : 572 -> 576
~ __ZN12IOUserSerial16DisconnectQueuesEPFiP15OSMetaClassBase5IORPCE : 248 -> 252
~ __ZN12IOUserSerial15RxDataAvailableEPFiP15OSMetaClassBase5IORPCE : 168 -> 172
~ __ZN12IOUserSerial20RxFreeSpaceAvailableEPFiP15OSMetaClassBase5IORPCE : 168 -> 172
~ __ZN12IOUserSerial15TxDataAvailableEPFiP15OSMetaClassBase5IORPCE : 168 -> 172
~ __ZN12IOUserSerial20TxFreeSpaceAvailableEPFiP15OSMetaClassBase5IORPCE : 168 -> 172
~ __ZN12IOUserSerial14SetModemStatusEbbbbPFiP15OSMetaClassBase5IORPCE : 260 -> 264
~ __ZN12IOUserSerial7RxErrorEbbbbPFiP15OSMetaClassBase5IORPCE : 260 -> 264
~ __ZN12IOUserSerial10HwActivateEPFiP15OSMetaClassBase5IORPCE : 248 -> 252
~ __ZN12IOUserSerial12HwDeactivateEPFiP15OSMetaClassBase5IORPCE : 248 -> 252
~ __ZN12IOUserSerial11HwResetFIFOEbbPFiP15OSMetaClassBase5IORPCE : 252 -> 256
~ __ZN12IOUserSerial11HwSendBreakEbPFiP15OSMetaClassBase5IORPCE : 248 -> 252
~ __ZN12IOUserSerial13HwProgramUARTEjhhhPFiP15OSMetaClassBase5IORPCE : 260 -> 264
~ __ZN12IOUserSerial17HwProgramBaudRateEjPFiP15OSMetaClassBase5IORPCE : 248 -> 252
~ __ZN12IOUserSerial12HwProgramMCREbbPFiP15OSMetaClassBase5IORPCE : 252 -> 256
~ __ZN12IOUserSerial16HwGetModemStatusEPbS0_S0_S0_PFiP15OSMetaClassBase5IORPCE : 344 -> 348
~ __ZN12IOUserSerial21HwProgramLatencyTimerEjPFiP15OSMetaClassBase5IORPCE : 248 -> 252
~ __ZN12IOUserSerial20HwProgramFlowControlEjhhPFiP15OSMetaClassBase5IORPCE : 256 -> 260
~ __ZN12IOUserSerial18HwResetFIFO_InvokeE5IORPCP15OSMetaClassBasePFiS2_bbE : 176 -> 180
~ __ZN12IOUserSerial18HwSendBreak_InvokeE5IORPCP15OSMetaClassBasePFiS2_bE : 164 -> 168
~ __ZN12IOUserSerial20HwProgramUART_InvokeE5IORPCP15OSMetaClassBasePFiS2_jhhhE : 176 -> 180
~ __ZN12IOUserSerial24HwProgramBaudRate_InvokeE5IORPCP15OSMetaClassBasePFiS2_jE : 160 -> 164
~ __ZN12IOUserSerial19HwProgramMCR_InvokeE5IORPCP15OSMetaClassBasePFiS2_bbE : 176 -> 180
~ __ZN12IOUserSerial23HwGetModemStatus_InvokeE5IORPCP15OSMetaClassBasePFiS2_PbS3_S3_S3_E : 176 -> 180
~ __ZN12IOUserSerial28HwProgramLatencyTimer_InvokeE5IORPCP15OSMetaClassBasePFiS2_jE : 160 -> 164
~ __ZN12IOUserSerial27HwProgramFlowControl_InvokeE5IORPCP15OSMetaClassBasePFiS2_jhhE : 172 -> 176
~ __ZN12IOUserSerial19handleEventActivateEb : 316 -> 320
~ __ZN12IOUserSerial13willTerminateEP9IOServicej : 196 -> 200
~ __ZNK12IOUserSerial13setStateGatedEjj : 184 -> 188
~ __ZN12IOUserSerial10watchStateEPjj : 232 -> 236
~ _ZN12IOUserSerial11releasePortEv.cold.1 : 208 -> 212
```
