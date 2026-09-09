## com.apple.driver.usb.cdc.ecm

> `com.apple.driver.usb.cdc.ecm`

```diff

 397.0.0.0.0
   __TEXT.__cstring: 0x32c
   __TEXT.__const: 0x28
-  __TEXT_EXEC.__text: 0x3efc
+  __TEXT_EXEC.__text: 0x4020
   __TEXT_EXEC.__auth_stubs: 0x320
   __DATA.__data: 0x1e8
   __DATA.__common: 0x88
Functions:
~ __ZN15AppleUSBECMData9MetaClassC1Ev : 72 -> 76
~ __ZN15AppleUSBECMDataC2EPK11OSMetaClass : 52 -> 56
~ __ZN15AppleUSBECMDataC1EPK11OSMetaClass : 52 -> 56
~ __ZN15AppleUSBECMDataD0Ev : 68 -> 72
~ __ZN15AppleUSBECMData9MetaClassC2Ev : 72 -> 76
~ __ZNK15AppleUSBECMData9MetaClass5allocEv : 104 -> 108
~ __ZN15AppleUSBECMDataC1Ev : 88 -> 92
~ __ZN15AppleUSBECMDataC2Ev : 88 -> 92
~ __ZN15AppleUSBECMData28waitForMatchingControlDriverEv : 108 -> 112
~ __ZN15AppleUSBECMData5startEP9IOService : 772 -> 776
~ __ZN15AppleUSBECMData17setLinkStatusDownEv : 108 -> 112
~ __ZN15AppleUSBECMData4stopEP9IOService : 588 -> 592
~ __ZN15AppleUSBECMData4freeEv : 116 -> 120
~ __ZN15AppleUSBECMData16setDataAlternateEv : 176 -> 180
~ __ZN15AppleUSBECMData9lockNetifEv : 140 -> 144
~ __ZN15AppleUSBECMData18flushDataTransfersEv : 232 -> 236
~ __ZN15AppleUSBECMData16setMulticastModeEb : 184 -> 188
~ __ZN15AppleUSBECMData11outputStartEP18IONetworkInterfacej : 368 -> 372
~ __ZN15AppleUSBECMData18returnOutputRecordEP16OutputPipeRecord : 188 -> 192
~ __ZN15AppleUSBECMData16zlpWriteCompleteEPvij : 120 -> 124
~ __ZN15AppleUSBECMData12submitPacketEPhj : 276 -> 280
~ __ZN15AppleUSBECMData16dataReadCompleteEPvij : 124 -> 128
~ __ZN15AppleUSBECMData15setLinkStatusUpEv : 192 -> 196
~ _GLOBAL__sub_I_AppleUSBECMData.cpp : 80 -> 84
~ __ZN18AppleUSBECMControl9MetaClassC1Ev : 72 -> 76
~ __ZN18AppleUSBECMControlC2EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleUSBECMControlC1EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleUSBECMControlD0Ev : 68 -> 72
~ __ZN18AppleUSBECMControl9MetaClassC2Ev : 72 -> 76
~ __ZNK18AppleUSBECMControl9MetaClass5allocEv : 104 -> 108
~ __ZN18AppleUSBECMControlC1Ev : 88 -> 92
~ __ZN18AppleUSBECMControlC2Ev : 88 -> 92
~ __ZN18AppleUSBECMControl5startEP9IOService : 352 -> 356
~ __ZN18AppleUSBECMControl34getInterfaceAssociationDescriptorsEv : 140 -> 144
~ _GLOBAL__sub_I_AppleUSBECMControl.cpp : 80 -> 84
~ __ZN17AppleUSBECMDataNC9MetaClassC1Ev : 72 -> 76
~ __ZN17AppleUSBECMDataNCC2EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleUSBECMDataNCC1EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleUSBECMDataNCD0Ev : 68 -> 72
~ __ZN17AppleUSBECMDataNC9MetaClassC2Ev : 72 -> 76
~ __ZNK17AppleUSBECMDataNC9MetaClass5allocEv : 104 -> 108
~ __ZN17AppleUSBECMDataNCC1Ev : 88 -> 92
~ __ZN17AppleUSBECMDataNCC2Ev : 88 -> 92
~ _GLOBAL__sub_I_AppleUSBECMDataNC.cpp : 80 -> 84
~ __ZN15AppleUSBECMData4initEP12OSDictionary : 108 -> 112
~ __ZN15AppleUSBECMData18matchControlDriverEv : 408 -> 412
~ __ZN15AppleUSBECMData20notificationCallbackEP18AppleUSBECMControlPvP18USBCDCNotification : 180 -> 184
~ __ZN15AppleUSBECMData5probeEP9IOServicePi : 428 -> 432
~ __ZN15AppleUSBECMData18createMediumTablesEv : 264 -> 268
~ __ZN15AppleUSBECMData12allocRecordsEv : 676 -> 680
~ __ZN15AppleUSBECMData13willTerminateEP9IOServicej : 348 -> 352
~ __ZN15AppleUSBECMData16updateLinkStatusEh : 120 -> 124
~ __ZN15AppleUSBECMData11freeRecordsEv : 248 -> 252
~ __ZN15AppleUSBECMData12setAlternateEh : 148 -> 152
~ __ZN15AppleUSBECMData13configureDataEv : 136 -> 140
~ __ZN15AppleUSBECMData6enableEP18IONetworkInterface : 548 -> 552
~ __ZN15AppleUSBECMData7armReadEv : 196 -> 200
~ __ZN15AppleUSBECMData7disableEP18IONetworkInterface : 280 -> 284
~ __ZN15AppleUSBECMData18setPromiscuousModeEb : 148 -> 152
~ __ZN15AppleUSBECMData25outputRecordAppendPacketsEP16OutputPipeRecordPP6__mbufj : 180 -> 184
~ __ZN15AppleUSBECMData18configureInterfaceEP18IONetworkInterface : 312 -> 316
~ __ZN15AppleUSBECMData14transmitRecordEP16OutputPipeRecord : 364 -> 368
~ __ZN15AppleUSBECMData17dataWriteCompleteEPvij : 252 -> 256
~ __ZN15AppleUSBECMData11transmitZLPEv : 368 -> 372
~ __ZN15AppleUSBECMData7armReadEP15InputPipeRecord : 312 -> 316
~ _ZN15AppleUSBECMData28waitForMatchingControlDriverEv.cold.1 : 116 -> 120
~ _ZN15AppleUSBECMData5startEP9IOService.cold.1 : 52 -> 56
~ _ZN15AppleUSBECMData16dataReadCompleteEPvij.cold.1 : 216 -> 220
~ __ZN18AppleUSBECMControl24getFunctionalDescriptorsEv : 464 -> 468
~ __ZN18AppleUSBECMControl18setMulticastFilterEP17IOEthernetAddressj : 148 -> 152
~ __ZN18AppleUSBECMControl15getPacketFilterEPt : 160 -> 164
~ __ZN18AppleUSBECMControl17pausePacketFilterEv : 124 -> 128
~ __ZN18AppleUSBECMControl15setPacketFilterEt : 124 -> 128
```
