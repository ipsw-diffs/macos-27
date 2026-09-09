## com.apple.driver.AppleSEPHDCPManager

> `com.apple.driver.AppleSEPHDCPManager`

```diff

 108.0.0.0.0
   __TEXT.__cstring: 0x876
   __TEXT.__os_log: 0x587
-  __TEXT_EXEC.__text: 0x4920
+  __TEXT_EXEC.__text: 0x4a98
   __TEXT_EXEC.__auth_stubs: 0x220
   __DATA.__data: 0xc8
   __DATA.__common: 0xb0
Functions:
~ __ZN16AppleHDCPManager9MetaClassC1Ev : 72 -> 76
~ __ZN16AppleHDCPManagerC2EPK11OSMetaClass : 52 -> 56
~ __ZN16AppleHDCPManagerC1EPK11OSMetaClass : 52 -> 56
~ __ZN16AppleHDCPManagerD0Ev : 68 -> 72
~ __ZN16AppleHDCPManager9MetaClassC2Ev : 72 -> 76
~ __ZN16AppleHDCPManager18serializeDebugInfoEPvP11OSSerialize : 552 -> 556
~ __ZN16AppleHDCPManager4freeEv : 112 -> 116
~ _GLOBAL__sub_I_AppleHDCPManager.cpp : 80 -> 84
~ __ZN25AppleHDCPEndpointProtocol11makeRequestE9RequestIdttPj : 96 -> 100
~ __ZN25AppleHDCPEndpointProtocol11makeRequestE9RequestIdtPKvmPvPm : 120 -> 124
~ __ZN25AppleHDCPEndpointProtocol14processRequestEPKNS_11RequestArgsE : 140 -> 144
~ __ZN18AppleHDCPInterface9MetaClassC1Ev : 72 -> 76
~ __ZN18AppleHDCPInterfaceC2EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleHDCPInterfaceC1EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleHDCPInterfaceD0Ev : 68 -> 72
~ __ZN18AppleHDCPInterface9MetaClassC2Ev : 72 -> 76
~ __ZNK18AppleHDCPInterface9MetaClass5allocEv : 104 -> 108
~ __ZN18AppleHDCPInterfaceC1Ev : 88 -> 92
~ __ZN18AppleHDCPInterfaceC2Ev : 88 -> 92
~ __ZN18AppleHDCPInterface11withOptionsEP9IOServiceP25AppleHDCPEndpointProtocolP20SEPHDCPInterfaceInfo : 356 -> 360
~ __ZN18AppleHDCPInterface11handleCloseEP9IOService : 240 -> 244
~ _GLOBAL__sub_I_AppleHDCPInterface.cpp : 80 -> 84
~ _OUTLINED_FUNCTION_5 : 28 -> 20
~ _OUTLINED_FUNCTION_6 : 20 -> 28
~ __ZN19AppleSEPHDCPManager9MetaClassC1Ev : 72 -> 76
~ __ZN19AppleSEPHDCPManagerC2EPK11OSMetaClass : 52 -> 56
~ __ZN19AppleSEPHDCPManagerC1EPK11OSMetaClass : 52 -> 56
~ __ZN19AppleSEPHDCPManagerD0Ev : 68 -> 72
~ __ZN19AppleSEPHDCPManager9MetaClassC2Ev : 72 -> 76
~ __ZNK19AppleSEPHDCPManager9MetaClass5allocEv : 104 -> 108
~ __ZN19AppleSEPHDCPManagerC1Ev : 88 -> 92
~ __ZN19AppleSEPHDCPManagerC2Ev : 88 -> 92
~ __ZN19AppleSEPHDCPManager5startEP9IOService : 168 -> 172
~ _GLOBAL__sub_I_AppleSEPHDCPManager.cpp : 80 -> 84
~ __ZN20AppleSEPHDCPEndpoint9MetaClassC1Ev : 72 -> 76
~ __ZN20AppleSEPHDCPEndpointC2EPK11OSMetaClass : 84 -> 88
~ __ZN20AppleSEPHDCPEndpointC1EPK11OSMetaClass : 84 -> 88
~ __ZN20AppleSEPHDCPEndpointD0Ev : 68 -> 72
~ __ZThn176_N20AppleSEPHDCPEndpointD0Ev : 72 -> 76
~ __ZN20AppleSEPHDCPEndpoint9MetaClassC2Ev : 72 -> 76
~ __ZNK20AppleSEPHDCPEndpoint9MetaClass5allocEv : 136 -> 140
~ __ZN20AppleSEPHDCPEndpointC1Ev : 120 -> 124
~ __ZN20AppleSEPHDCPEndpointC2Ev : 120 -> 124
~ __ZN20AppleSEPHDCPEndpoint21initWithDeviceServiceEP21AppleSEPDeviceService : 304 -> 308
~ __ZN20AppleSEPHDCPEndpoint6actionEPvS0_ : 380 -> 384
~ __ZN20AppleSEPHDCPEndpoint4freeEv : 152 -> 156
~ __ZN20AppleSEPHDCPEndpoint6enableEj : 152 -> 156
~ __ZThn176_N20AppleSEPHDCPEndpoint6enableEj : 152 -> 156
~ __ZN20AppleSEPHDCPEndpoint7disableEv : 152 -> 156
~ __ZN20AppleSEPHDCPEndpoint12disableGatedEv : 80 -> 84
~ __ZThn176_N20AppleSEPHDCPEndpoint7disableEv : 152 -> 156
~ __ZN20AppleSEPHDCPEndpoint13handleRequestEPKN25AppleHDCPEndpointProtocol11RequestArgsE : 164 -> 168
~ __ZThn176_N20AppleSEPHDCPEndpoint13handleRequestEPKN25AppleHDCPEndpointProtocol11RequestArgsE : 164 -> 168
~ __ZN20AppleSEPHDCPEndpoint27waitForEndpointAvailabilityEPKN25AppleHDCPEndpointProtocol11RequestArgsE : 568 -> 572
~ __ZN20AppleSEPHDCPEndpoint28signalForEndpointAvailabiltyEPKN25AppleHDCPEndpointProtocol11RequestArgsE : 240 -> 244
~ _GLOBAL__sub_I_AppleSEPHDCPEndpoint.cpp : 80 -> 84
~ __ZN16AppleHDCPManager5startEP9IOServiceP25AppleHDCPEndpointProtocol : 592 -> 596
~ __ZN16AppleHDCPManager16launchInterfacesEv : 840 -> 844
~ __ZN18AppleHDCPInterface4initEP25AppleHDCPEndpointProtocolP20SEPHDCPInterfaceInfo : 148 -> 152
~ __ZN18AppleHDCPInterface11handleStartEP9IOService : 392 -> 396
~ __ZN18AppleHDCPInterface19serializeDeviceRoleEPvP11OSSerialize : 136 -> 140
~ __ZN18AppleHDCPInterface18matchPropertyTableEP12OSDictionaryPi : 484 -> 488
~ __ZN18AppleHDCPInterface11generateRtxEP10IOHDCP_Rtx : 88 -> 92
~ __ZN18AppleHDCPInterface11generateRrxEP10IOHDCP_Rrx : 88 -> 92
~ __ZN18AppleHDCPInterface10consumeRtxE10IOHDCP_Rtx : 104 -> 108
~ __ZN18AppleHDCPInterface10consumeRrxE10IOHDCP_Rrx : 104 -> 108
~ __ZN18AppleHDCPInterface8readCertEP11IOHDCP_Cert : 216 -> 220
~ __ZN18AppleHDCPInterface12loadStoredKmEP15IOHDCP_StoredKm : 96 -> 100
~ __ZN18AppleHDCPInterface13clearStoredKmE17IOHDCP_ReceiverID : 104 -> 108
~ __ZN18AppleHDCPInterface13generateEKhKmEP14IOHDCP_UInt128 : 96 -> 100
~ __ZN18AppleHDCPInterface12saveStoredKmE14IOHDCP_UInt128 : 108 -> 112
~ __ZN18AppleHDCPInterface19generateEncryptedKmEP14IOHDCP_EKpubKm : 96 -> 100
~ __ZN18AppleHDCPInterface12consumeNewKmE14IOHDCP_EKpubKm : 248 -> 252
~ __ZN18AppleHDCPInterface8computeHE17IOHDCP_HInputData : 128 -> 132
~ __ZN18AppleHDCPInterface5readHEP14IOHDCP_UInt256 : 96 -> 100
~ __ZN18AppleHDCPInterface19generateEncryptedKsEP14IOHDCP_UInt128 : 96 -> 100
~ __ZN18AppleHDCPInterface16writeEncryptedKsE14IOHDCP_UInt128 : 108 -> 112
~ __ZN18AppleHDCPInterface11generateRivEP10IOHDCP_Riv : 88 -> 92
~ __ZN18AppleHDCPInterface10consumeRivE10IOHDCP_Riv : 104 -> 108
~ __ZN18AppleHDCPInterface10generateRnEP9IOHDCP_Rn : 88 -> 92
~ __ZN18AppleHDCPInterface9consumeRnE9IOHDCP_Rn : 104 -> 108
~ __ZN18AppleHDCPInterface5readLEP14IOHDCP_UInt256 : 88 -> 92
~ __ZN18AppleHDCPInterface12verifyVPrimeE14IOHDCP_UInt128 : 116 -> 120
~ __ZN18AppleHDCPInterface5readVEP14IOHDCP_UInt256 : 88 -> 92
~ __ZN18AppleHDCPInterface8computeME13IOHDCP_SeqNumPKvm : 144 -> 148
~ __ZN18AppleHDCPInterface5readMEP14IOHDCP_UInt256 : 88 -> 92
~ _ZN18AppleHDCPInterface11withOptionsEP9IOServiceP25AppleHDCPEndpointProtocolP20SEPHDCPInterfaceInfo.cold.1 : 64 -> 68
~ _ZN18AppleHDCPInterface11withOptionsEP9IOServiceP25AppleHDCPEndpointProtocolP20SEPHDCPInterfaceInfo.cold.2 : 64 -> 68
~ _ZN18AppleHDCPInterface11withOptionsEP9IOServiceP25AppleHDCPEndpointProtocolP20SEPHDCPInterfaceInfo.cold.3 : 196 -> 200
~ _ZN19AppleSEPHDCPManager5startEP9IOService.cold.1 : 84 -> 88
~ _ZN19AppleSEPHDCPManager5startEP9IOService.cold.2 : 84 -> 88
~ __ZN20AppleSEPHDCPEndpoint17withDeviceServiceEP21AppleSEPDeviceService : 128 -> 132
~ __ZN20AppleSEPHDCPEndpoint18handleRequestGatedEPKN25AppleHDCPEndpointProtocol11RequestArgsE : 1472 -> 1476
~ _ZN20AppleSEPHDCPEndpoint21initWithDeviceServiceEP21AppleSEPDeviceService.cold.1 : 44 -> 48
~ _ZN20AppleSEPHDCPEndpoint12disableGatedEv.cold.1 : 44 -> 48
~ _ZN20AppleSEPHDCPEndpoint28signalForEndpointAvailabiltyEPKN25AppleHDCPEndpointProtocol11RequestArgsE.cold.1 : 68 -> 72
```
