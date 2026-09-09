## com.apple.driver.usb.networking

> `com.apple.driver.usb.networking`

```diff

 397.0.0.0.0
   __TEXT.__cstring: 0x65f
-  __TEXT_EXEC.__text: 0x3d84
+  __TEXT_EXEC.__text: 0x3e70
   __TEXT_EXEC.__auth_stubs: 0x250
   __DATA.__data: 0xc8
   __DATA.__common: 0x88
Functions:
~ __ZN22AppleUSBNCMPacketQueueD2Ev : 64 -> 68
~ __ZN22AppleUSBNCMPacketQueueD1Ev : 64 -> 68
~ __ZN18AppleUSBNCMEncoder6encodeEP24IOBufferMemoryDescriptorPjPm : 180 -> 184
~ __ZN18AppleUSBNCMEncoder17consumeNextPacketEP6__mbuf : 116 -> 120
~ __ZN18AppleUSBNCMDecoder6decodeEP24IOBufferMemoryDescriptormPj : 216 -> 220
~ __ZN18AppleUSBNCMDecoder6decodeEPKvmPj : 912 -> 916
~ __ZN18AppleUSBNCMDecoder12submitPacketEPKvm : 396 -> 400
~ _OUTLINED_FUNCTION_2 : 20 -> 24
~ _OUTLINED_FUNCTION_6 : 64 -> 40
~ _OUTLINED_FUNCTION_7 : 20 -> 64
~ _OUTLINED_FUNCTION_8 : 16 -> 20
~ _OUTLINED_FUNCTION_10 : 40 -> 16
~ _OUTLINED_FUNCTION_26 : 20 -> 24
~ _OUTLINED_FUNCTION_28 : 12 -> 20
~ _OUTLINED_FUNCTION_29 : 20 -> 12
~ _OUTLINED_FUNCTION_31 : 12 -> 20
~ _OUTLINED_FUNCTION_32 : 20 -> 12
~ _OUTLINED_FUNCTION_33 : 12 -> 20
~ _OUTLINED_FUNCTION_34 : 20 -> 12
~ __Z20findMatchingEndpointhhPKN11StandardUSB23ConfigurationDescriptorEPKNS_19InterfaceDescriptorE : 148 -> 152
~ __ZN29AppleUSBNetworkingCommandPool9MetaClassC1Ev : 72 -> 76
~ __ZN29AppleUSBNetworkingCommandPoolC2EPK11OSMetaClass : 52 -> 56
~ __ZN29AppleUSBNetworkingCommandPoolC1EPK11OSMetaClass : 52 -> 56
~ __ZN29AppleUSBNetworkingCommandPoolD0Ev : 68 -> 72
~ __ZN29AppleUSBNetworkingCommandPool9MetaClassC2Ev : 72 -> 76
~ __ZNK29AppleUSBNetworkingCommandPool9MetaClass5allocEv : 104 -> 108
~ __ZN29AppleUSBNetworkingCommandPoolC1Ev : 88 -> 92
~ __ZN29AppleUSBNetworkingCommandPoolC2Ev : 88 -> 92
~ __ZN29AppleUSBNetworkingCommandPool14withParametersEP10IOWorkLoopjj : 248 -> 252
~ __ZN29AppleUSBNetworkingCommandPool4stopEv : 352 -> 356
~ __ZN29AppleUSBNetworkingCommandPool4freeEv : 160 -> 164
~ __ZN29AppleUSBNetworkingCommandPool13returnCommandEP9IOCommand : 156 -> 160
~ __ZN29AppleUSBNetworkingCommandPool18gatedReturnCommandEP9IOCommand : 96 -> 100
~ __ZN25AppleUSBNetworkingCommand14withParametersEP29AppleUSBNetworkingCommandPoolP24IOBufferMemoryDescriptor : 232 -> 236
~ __ZN33AppleUSBNetworkingHostCommandPool9MetaClassC1Ev : 72 -> 76
~ __ZN33AppleUSBNetworkingHostCommandPoolC2EPK11OSMetaClass : 52 -> 56
~ __ZN33AppleUSBNetworkingHostCommandPoolC1EPK11OSMetaClass : 52 -> 56
~ __ZN33AppleUSBNetworkingHostCommandPoolD0Ev : 68 -> 72
~ __ZN33AppleUSBNetworkingHostCommandPool9MetaClassC2Ev : 72 -> 76
~ __ZNK33AppleUSBNetworkingHostCommandPool9MetaClass5allocEv : 104 -> 108
~ __ZN33AppleUSBNetworkingHostCommandPoolC1Ev : 88 -> 92
~ __ZN33AppleUSBNetworkingHostCommandPoolC2Ev : 88 -> 92
~ __ZN33AppleUSBNetworkingHostCommandPool14withParametersEP18IOUSBHostInterfacejj : 248 -> 252
~ __ZN33AppleUSBNetworkingHostCommandPool4freeEv : 140 -> 144
~ __ZN25AppleUSBNetworkingCommand9MetaClassC1Ev : 72 -> 76
~ __ZN25AppleUSBNetworkingCommandC2EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleUSBNetworkingCommandC1EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleUSBNetworkingCommandD0Ev : 68 -> 72
~ __ZN25AppleUSBNetworkingCommand9MetaClassC2Ev : 72 -> 76
~ __ZNK25AppleUSBNetworkingCommand9MetaClass5allocEv : 104 -> 108
~ __ZN25AppleUSBNetworkingCommandC1Ev : 88 -> 92
~ __ZN25AppleUSBNetworkingCommandC2Ev : 88 -> 92
~ __ZN25AppleUSBNetworkingCommand4freeEv : 192 -> 196
~ __ZN25AppleUSBNetworkingCommand10setContextEP8OSObject : 152 -> 156
~ _GLOBAL__sub_I_AppleUSBNetworkingCommand.cpp : 208 -> 212
~ __GLOBAL__D_a : 68 -> 72
~ __ZN18AppleUSBNCMEncoder6encodeEPvmPjPm : 1308 -> 1304
~ __ZN18AppleUSBNCMEncoder9encodeNTBI12NTBXTxFormatEEiPhmPjPm : 468 -> 464
~ __ZN18AppleUSBNCMEncoder9encodeNTBI12NTBXRxFormatEEiPhmPjPm : 468 -> 464
~ __ZN18AppleUSBNCMDecoder9decodeNTBI12NTBXTxFormatEEiPKhmPj : 296 -> 300
~ __ZN18AppleUSBNCMDecoder9decodeNTBI12NTBXRxFormatEEiPKhmPj : 296 -> 300
~ _dumpExtendedFeatureDescriptor : 444 -> 448
~ _dumpExtendedCapabilityDescriptor : 520 -> 524
~ __Z16nameBSDInterfaceP18IONetworkInterfacej : 692 -> 696
~ __Z23copyBSDNameForInterfaceP18IONetworkInterfacePc : 192 -> 196
~ __Z18enableBSDInterfaceP18IONetworkInterface : 260 -> 264
~ __Z35configureDatagramSizeOnBSDInterfaceP18IONetworkInterfacej : 272 -> 276
~ __Z29configureIPv6LLOnBSDInterfaceP18IONetworkInterfaceb : 272 -> 276
~ __Z35disableTrafficShapingOnBSDInterfaceP18IONetworkInterface : 212 -> 216
~ __ZN29AppleUSBNetworkingCommandPool18initWithParametersEP10IOWorkLoopjj : 172 -> 176
~ __ZN29AppleUSBNetworkingCommandPool10getCommandEb : 276 -> 280
~ __ZN29AppleUSBNetworkingCommandPool15allocateCommandEv : 112 -> 116
~ __ZN33AppleUSBNetworkingHostCommandPool15allocateCommandEv : 136 -> 140
~ __ZN25AppleUSBNetworkingCommand18initWithParametersEP29AppleUSBNetworkingCommandPoolP24IOBufferMemoryDescriptor : 132 -> 136
~ __ZN25AppleUSBNetworkingCommand15setBufferLengthEm : 156 -> 160
```
