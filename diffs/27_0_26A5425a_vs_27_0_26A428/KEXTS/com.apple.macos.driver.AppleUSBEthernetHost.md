## com.apple.macos.driver.AppleUSBEthernetHost

> `com.apple.macos.driver.AppleUSBEthernetHost`

```diff

 167.0.0.0.0
   __TEXT.__cstring: 0xbc4
-  __TEXT_EXEC.__text: 0x3dc0
+  __TEXT_EXEC.__text: 0x3eb8
   __TEXT_EXEC.__auth_stubs: 0x280
   __DATA.__data: 0x188
   __DATA.__common: 0x88
Functions:
~ __ZN24PacketMemoryDescriptorEx9MetaClassC1Ev : 72 -> 76
~ __ZN24PacketMemoryDescriptorExC2EPK11OSMetaClass : 52 -> 56
~ __ZN24PacketMemoryDescriptorExC1EPK11OSMetaClass : 52 -> 56
~ __ZN24PacketMemoryDescriptorExD0Ev : 68 -> 72
~ __ZN24PacketMemoryDescriptorEx9MetaClassC2Ev : 72 -> 76
~ __ZNK24PacketMemoryDescriptorEx9MetaClass5allocEv : 104 -> 108
~ __ZN24PacketMemoryDescriptorExC1Ev : 88 -> 92
~ __ZN24PacketMemoryDescriptorExC2Ev : 88 -> 92
~ __ZN24PacketMemoryDescriptorEx24withControllerForReadingEP19IONetworkController : 412 -> 416
~ __ZN24PacketMemoryDescriptorEx12initWithArgsEP19IONetworkControllerP18IOMemoryDescriptorP6__mbufm : 176 -> 180
~ __ZN24PacketMemoryDescriptorEx31withControllerForReadingNCMLiteEP19IONetworkControllerR18IOUSBHostInterface : 272 -> 276
~ __ZN24PacketMemoryDescriptorEx23withControllerAndPacketEP19IONetworkControllerP6__mbufm : 428 -> 432
~ __ZN24PacketMemoryDescriptorEx20withControllerForZLPEP19IONetworkController : 204 -> 208
~ __ZN24PacketMemoryDescriptorEx4freeEv : 196 -> 200
~ __ZN20AppleUSBEthernetHost9MetaClassC1Ev : 72 -> 76
~ __ZN20AppleUSBEthernetHostC2EPK11OSMetaClass : 52 -> 56
~ __ZN20AppleUSBEthernetHostC1EPK11OSMetaClass : 52 -> 56
~ __ZN20AppleUSBEthernetHostD0Ev : 68 -> 72
~ __ZN20AppleUSBEthernetHost9MetaClassC2Ev : 72 -> 76
~ __ZNK20AppleUSBEthernetHost9MetaClass5allocEv : 104 -> 108
~ __ZN20AppleUSBEthernetHostC1Ev : 88 -> 92
~ __ZN20AppleUSBEthernetHostC2Ev : 88 -> 92
~ __ZN20AppleUSBEthernetHost5startEP9IOService : 1548 -> 1552
~ __ZN20AppleUSBEthernetHost24powerStateChangeOccurredEv : 484 -> 488
~ __ZN20AppleUSBEthernetHost26getHardwareEthernetAddressEv : 192 -> 196
~ __ZN20AppleUSBEthernetHost22getPreferredAltSettingEv : 164 -> 168
~ __ZN20AppleUSBEthernetHost17getInterfaceFlagsEv : 224 -> 228
~ __ZN20AppleUSBEthernetHost13freeResourcesEv : 608 -> 612
~ __ZN20AppleUSBEthernetHost13setPowerStateEmP9IOService : 92 -> 96
~ __ZN20AppleUSBEthernetHost12didTerminateEP9IOServicejPb : 204 -> 208
~ __ZN20AppleUSBEthernetHost17didTerminateGatedEv : 280 -> 284
~ __ZN20AppleUSBEthernetHost17createOutputQueueEv : 96 -> 100
~ __ZNK20AppleUSBEthernetHost16getPacketFiltersEPK8OSSymbolPj : 180 -> 184
~ __ZN20AppleUSBEthernetHost6enableEP18IONetworkInterface : 892 -> 896
~ __ZN20AppleUSBEthernetHost9lockNetifEv : 140 -> 144
~ __ZN20AppleUSBEthernetHost27tryEnablingNCMEncapsulationEv : 160 -> 164
~ __ZL20findMatchingEndpointhhPKN11StandardUSB23ConfigurationDescriptorEPKNS_19InterfaceDescriptorE : 136 -> 140
~ __ZN20AppleUSBEthernetHost7disableEP18IONetworkInterface : 792 -> 796
~ __ZN20AppleUSBEthernetHost12outputPacketEP6__mbufPv : 376 -> 380
~ __ZN20AppleUSBEthernetHost17bulkWriteCompleteEPvij : 516 -> 520
~ __ZN20AppleUSBEthernetHost18startBulkReadGatedEv : 392 -> 396
~ __ZN20AppleUSBEthernetHost16bulkReadCompleteEPvij : 1252 -> 1256
~ __ZN20AppleUSBEthernetHost12submitPacketEPhj : 316 -> 320
~ __ZN20AppleUSBEthernetHost18startTransmitQueueEv : 164 -> 168
~ __ZN20AppleUSBEthernetHost17stopTransmitQueueEv : 224 -> 228
~ _GLOBAL__sub_I_AppleUSBEthernetHost.cpp : 140 -> 144
~ __GLOBAL__D_a : 56 -> 60
~ __ZN23AppleUSBEthernetHostAQM9MetaClassC1Ev : 72 -> 76
~ __ZN23AppleUSBEthernetHostAQMC2EPK11OSMetaClass : 52 -> 56
~ __ZN23AppleUSBEthernetHostAQMC1EPK11OSMetaClass : 52 -> 56
~ __ZN23AppleUSBEthernetHostAQMD0Ev : 68 -> 72
~ __ZN23AppleUSBEthernetHostAQM9MetaClassC2Ev : 72 -> 76
~ __ZNK23AppleUSBEthernetHostAQM9MetaClass5allocEv : 104 -> 108
~ __ZN23AppleUSBEthernetHostAQMC1Ev : 88 -> 92
~ __ZN23AppleUSBEthernetHostAQMC2Ev : 88 -> 92
~ __ZN23AppleUSBEthernetHostAQM18startTransmitQueueEv : 108 -> 112
~ __ZN23AppleUSBEthernetHostAQM17stopTransmitQueueEv : 68 -> 72
~ _GLOBAL__sub_I_AppleUSBEthernetHostAQM.cpp : 80 -> 84
~ __ZN20AppleUSBEthernetHost18configureInterfaceEP18IONetworkInterface : 216 -> 220
~ __ZN20AppleUSBEthernetHost15processTransferEPhj : 204 -> 208
~ __ZN23AppleUSBEthernetHostAQM18configureInterfaceEP18IONetworkInterface : 132 -> 136
~ __ZN23AppleUSBEthernetHostAQM11outputStartEP18IONetworkInterfacej : 268 -> 272
```
