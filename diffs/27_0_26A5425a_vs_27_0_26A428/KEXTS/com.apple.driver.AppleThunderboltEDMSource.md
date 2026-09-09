## com.apple.driver.AppleThunderboltEDMSource

> `com.apple.driver.AppleThunderboltEDMSource`

```diff

 513.0.0.0.0
   __TEXT.__cstring: 0x15e4
   __TEXT.__const: 0x20
-  __TEXT_EXEC.__text: 0x89a8
+  __TEXT_EXEC.__text: 0x8bc0
   __TEXT_EXEC.__auth_stubs: 0x320
   __DATA.__data: 0x1e8
   __DATA.__common: 0xd8
Functions:
~ __ZN33AppleThunderboltEDMRequestCommand9MetaClassC1Ev : 72 -> 76
~ __ZN33AppleThunderboltEDMRequestCommandC2EPK11OSMetaClass : 52 -> 56
~ __ZN33AppleThunderboltEDMRequestCommandC1EPK11OSMetaClass : 52 -> 56
~ __ZN33AppleThunderboltEDMRequestCommandD0Ev : 68 -> 72
~ __ZN33AppleThunderboltEDMRequestCommand9MetaClassC2Ev : 72 -> 76
~ __ZNK33AppleThunderboltEDMRequestCommand9MetaClass5allocEv : 104 -> 108
~ __ZN33AppleThunderboltEDMRequestCommandC1Ev : 88 -> 92
~ __ZN33AppleThunderboltEDMRequestCommandC2Ev : 88 -> 92
~ __ZN33AppleThunderboltEDMRequestCommand14withControllerEP23IOThunderboltController : 164 -> 168
~ __ZN33AppleThunderboltEDMRequestCommand15processResponseEP27IOThunderboltReceiveCommand : 360 -> 364
~ _GLOBAL__sub_I_AppleThunderboltEDMRequestCommand.cpp : 80 -> 84
~ __ZN25AppleThunderboltEDMSource9MetaClassC1Ev : 72 -> 76
~ __ZN25AppleThunderboltEDMSourceC2EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleThunderboltEDMSourceC1EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleThunderboltEDMSourceD0Ev : 68 -> 72
~ __ZN25AppleThunderboltEDMSource9MetaClassC2Ev : 72 -> 76
~ __ZNK25AppleThunderboltEDMSource9MetaClass5allocEv : 104 -> 108
~ __ZN25AppleThunderboltEDMSourceC1Ev : 88 -> 92
~ __ZN25AppleThunderboltEDMSourceC2Ev : 88 -> 92
~ __ZN25AppleThunderboltEDMSource5startEP9IOService : 4188 -> 4192
~ __ZN25AppleThunderboltEDMSource8finalizeEj : 1040 -> 1044
~ __ZN25AppleThunderboltEDMSource4freeEv : 140 -> 144
~ __ZN25AppleThunderboltEDMSource7messageEjP9IOServicePv : 216 -> 220
~ __ZN25AppleThunderboltEDMSource20setupPowerManagementEv : 408 -> 412
~ __ZN25AppleThunderboltEDMSource13setPowerStateEmP9IOService : 364 -> 368
~ __ZN25AppleThunderboltEDMSource18systemWillShutdownEj : 316 -> 320
~ __ZN25AppleThunderboltEDMSource15createResourcesEv : 696 -> 700
~ __ZN25AppleThunderboltEDMSource16destroyResourcesEv : 648 -> 652
~ __ZN25AppleThunderboltEDMSource14createEDMPathsEj : 1784 -> 1788
~ __ZN25AppleThunderboltEDMSource15destroyEDMPathsEv : 164 -> 168
~ __ZN25AppleThunderboltEDMSource26spawnRemoveNotifiersThreadEv : 292 -> 296
~ __ZN25AppleThunderboltEDMSource15removeNotifiersEv : 284 -> 288
~ __ZN25AppleThunderboltEDMSource17newRequestCommandEPv : 828 -> 832
~ __ZN25AppleThunderboltEDMSource16spawnLoginThreadEv : 292 -> 296
~ __ZN25AppleThunderboltEDMSource11loginThreadEv : 316 -> 320
~ __ZN25AppleThunderboltEDMSource5loginEv : 1148 -> 1152
~ __ZN25AppleThunderboltEDMSource21spawnActivationThreadEv : 292 -> 296
~ __ZN25AppleThunderboltEDMSource16activationThreadEv : 272 -> 276
~ __ZN25AppleThunderboltEDMSource8activateEv : 1380 -> 1384
~ __ZN25AppleThunderboltEDMSource17spawnLogoutThreadEv : 292 -> 296
~ __ZN25AppleThunderboltEDMSource12logoutThreadEv : 160 -> 164
~ __ZN25AppleThunderboltEDMSource6logoutEv : 884 -> 888
~ __ZN25AppleThunderboltEDMSource19logoutAndNotifySinkEv : 424 -> 428
~ __ZN25AppleThunderboltEDMSource14sendEDMRequestEj : 1216 -> 1220
~ __ZN25AppleThunderboltEDMSource22requestCommandCallbackEPviP26IOThunderboltConfigCommand : 1420 -> 1424
~ __ZN25AppleThunderboltEDMSource18transactionTimeoutEv : 440 -> 444
~ __ZN25AppleThunderboltEDMSource19dpInAdapterCallbackEPvP9IOService : 724 -> 728
~ __ZN25AppleThunderboltEDMSource25spawnDPStateChangedThreadEv : 292 -> 296
~ __ZN25AppleThunderboltEDMSource14dpStateChangedEv : 456 -> 460
~ __ZN25AppleThunderboltEDMSource11setEDMStateEj : 800 -> 804
~ __ZN25AppleThunderboltEDMSource26waitForStateChangeCompleteEv : 380 -> 384
~ __ZN25AppleThunderboltEDMSource9sinkInUseEv : 496 -> 500
~ __ZN25AppleThunderboltEDMSource17enableTMUTimeSyncEb : 636 -> 640
~ __ZN25AppleThunderboltEDMSource14xdPortForStateEh : 236 -> 240
~ __ZN25AppleThunderboltEDMSource19createDPPathManagerEP23IOThunderboltController : 48 -> 52
~ __ZN25AppleThunderboltEDMSource20destroyDPPathManagerEv : 44 -> 48
~ __ZN25AppleThunderboltEDMSource20getRootDPInPortCountEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource12getSSCOffsetEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource27setDPPathManagerHopIDRangesEj23IOThunderboltHopIDRangeS0_ : 44 -> 48
~ __ZN25AppleThunderboltEDMSource34setDPPathManagerLaneRoutingOptionsEbb : 44 -> 48
~ __ZN25AppleThunderboltEDMSource32setDPPathManagerBandwidthOptionsEjjj : 44 -> 48
~ __ZN25AppleThunderboltEDMSource16createEDMPathSetEv : 52 -> 56
~ __ZN25AppleThunderboltEDMSource17destroyEDMPathSetEv : 44 -> 48
~ __ZN25AppleThunderboltEDMSource19findDPInPortAtRouteEyjbyP9IOService : 48 -> 52
~ __ZN25AppleThunderboltEDMSource11setDPInPortEP17IOThunderboltPort : 52 -> 56
~ __ZN25AppleThunderboltEDMSource35createDPInAdapterMatchingDictionaryEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource28extractDPInPortFromIOServiceEP9IOService : 48 -> 52
~ __ZN25AppleThunderboltEDMSource11getDPInPortEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource27setDPInRemoteDPCapabilitiesEj : 52 -> 56
~ __ZN25AppleThunderboltEDMSource16configDPInHopIDsEbttt : 52 -> 56
~ __ZN25AppleThunderboltEDMSource10enableDPInEb : 52 -> 56
~ __ZN25AppleThunderboltEDMSource26getDPInLocalDPCapabilitiesEjPj : 52 -> 56
~ __ZN25AppleThunderboltEDMSource21checkDPInAdapterValidEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource12clearDPInHPDEv : 52 -> 56
~ __ZN25AppleThunderboltEDMSource15reserveDPInPortEbP9IOService : 52 -> 56
~ __ZN25AppleThunderboltEDMSource17getGPUIsMuxedAwayEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource21setDPPathsPathSetTypeEj : 44 -> 48
~ __ZN25AppleThunderboltEDMSource32getVideoPathAllocatedSourceHopIDEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource37getVideoPathAllocatedDestinationHopIDEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource32getAuxTxPathAllocatedSourceHopIDEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource37getAuxTxPathAllocatedDestinationHopIDEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource32getAuxRxPathAllocatedSourceHopIDEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource37getAuxRxPathAllocatedDestinationHopIDEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource24getDPPMPathSetTypeDirectEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource20getDPPMPathTypeVideoEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource20getDPPMPathTypeAuxTxEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource20getDPPMPathTypeAuxRxEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource33getDPPMDefaultVideoPathHopIDRangeEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource31getDPPMDefaultAuxPathHopIDRangeEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource21getDPPMNULLHopIDRangeEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource18getDPPMAnyFreePortEv : 48 -> 52
~ __ZN25AppleThunderboltEDMSource22clearPathSetConfigDataEv : 44 -> 48
~ __ZN25AppleThunderboltEDMSource33setPathSetConfigDataPathsToCreateEj : 44 -> 48
~ __ZN25AppleThunderboltEDMSource30setPathSetConfigDataSourcePortEP17IOThunderboltPort : 44 -> 48
~ __ZN25AppleThunderboltEDMSource28setPathSetConfigDataSinkPortEP17IOThunderboltPort : 44 -> 48
~ _GLOBAL__sub_I_AppleThunderboltEDMSource.cpp : 80 -> 84
~ __ZN35AppleThunderboltEDMSourceUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN35AppleThunderboltEDMSourceUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN35AppleThunderboltEDMSourceUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN35AppleThunderboltEDMSourceUserClientD0Ev : 68 -> 72
~ __ZN35AppleThunderboltEDMSourceUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK35AppleThunderboltEDMSourceUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN35AppleThunderboltEDMSourceUserClientC1Ev : 88 -> 92
~ __ZN35AppleThunderboltEDMSourceUserClientC2Ev : 88 -> 92
~ __ZN35AppleThunderboltEDMSourceUserClient5startEP9IOService : 124 -> 128
~ __ZN35AppleThunderboltEDMSourceUserClient11clientCloseEv : 64 -> 68
~ __ZN35AppleThunderboltEDMSourceUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 392 -> 396
~ _GLOBAL__sub_I_AppleThunderboltEDMSourceUserClient.cpp : 80 -> 84
~ __ZN35AppleThunderboltEDMSourceGFXPolicy29MetaClassC1Ev : 72 -> 76
~ __ZN35AppleThunderboltEDMSourceGFXPolicy2C2EPK11OSMetaClass : 52 -> 56
~ __ZN35AppleThunderboltEDMSourceGFXPolicy2C1EPK11OSMetaClass : 52 -> 56
~ __ZN35AppleThunderboltEDMSourceGFXPolicy2D0Ev : 68 -> 72
~ __ZN35AppleThunderboltEDMSourceGFXPolicy29MetaClassC2Ev : 72 -> 76
~ __ZNK35AppleThunderboltEDMSourceGFXPolicy29MetaClass5allocEv : 104 -> 108
~ __ZN35AppleThunderboltEDMSourceGFXPolicy2C1Ev : 88 -> 92
~ __ZN35AppleThunderboltEDMSourceGFXPolicy2C2Ev : 88 -> 92
~ __ZN35AppleThunderboltEDMSourceGFXPolicy25probeEP9IOServicePi : 76 -> 80
~ __ZN35AppleThunderboltEDMSourceGFXPolicy219createDPPathManagerEP23IOThunderboltController : 56 -> 60
~ __ZN35AppleThunderboltEDMSourceGFXPolicy220destroyDPPathManagerEv : 72 -> 76
~ __ZN35AppleThunderboltEDMSourceGFXPolicy228extractDPInPortFromIOServiceEP9IOService : 116 -> 120
~ _GLOBAL__sub_I_AppleThunderboltEDMSourceGFXPolicy2.cpp : 80 -> 84
~ __ZN35AppleThunderboltEDMSourceGFXPolicy19MetaClassC1Ev : 72 -> 76
~ __ZN35AppleThunderboltEDMSourceGFXPolicy1C2EPK11OSMetaClass : 52 -> 56
~ __ZN35AppleThunderboltEDMSourceGFXPolicy1C1EPK11OSMetaClass : 52 -> 56
~ __ZN35AppleThunderboltEDMSourceGFXPolicy1D0Ev : 68 -> 72
~ __ZN35AppleThunderboltEDMSourceGFXPolicy19MetaClassC2Ev : 72 -> 76
~ __ZNK35AppleThunderboltEDMSourceGFXPolicy19MetaClass5allocEv : 104 -> 108
~ __ZN35AppleThunderboltEDMSourceGFXPolicy1C1Ev : 88 -> 92
~ __ZN35AppleThunderboltEDMSourceGFXPolicy1C2Ev : 88 -> 92
~ __ZN35AppleThunderboltEDMSourceGFXPolicy15probeEP9IOServicePi : 76 -> 80
~ __ZN35AppleThunderboltEDMSourceGFXPolicy119createDPPathManagerEP23IOThunderboltController : 56 -> 60
~ __ZN35AppleThunderboltEDMSourceGFXPolicy120destroyDPPathManagerEv : 72 -> 76
~ __ZN35AppleThunderboltEDMSourceGFXPolicy128extractDPInPortFromIOServiceEP9IOService : 116 -> 120
~ _GLOBAL__sub_I_AppleThunderboltEDMSourceGFXPolicy1.cpp : 80 -> 84
```
