## com.apple.driver.usb.AppleUSBHub

> `com.apple.driver.usb.AppleUSBHub`

```diff

   __TEXT.__cstring: 0x1e48
   __TEXT.__os_log: 0x1f61
   __TEXT.__const: 0x68
-  __TEXT_EXEC.__text: 0x1b4bc
+  __TEXT_EXEC.__text: 0x1b714
   __TEXT_EXEC.__auth_stubs: 0x3f0
   __DATA.__data: 0xc8
   __DATA.__common: 0x128
Functions:
~ __ZN17AppleUSB20HubPort9MetaClassC1Ev : 72 -> 76
~ __ZN17AppleUSB20HubPortC2EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleUSB20HubPortC1EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleUSB20HubPortD0Ev : 68 -> 72
~ __ZN17AppleUSB20HubPort9MetaClassC2Ev : 72 -> 76
~ __ZNK17AppleUSB20HubPort9MetaClass5allocEv : 104 -> 108
~ __ZN17AppleUSB20HubPortC1Ev : 88 -> 92
~ __ZN17AppleUSB20HubPortC2Ev : 88 -> 92
~ __ZN17AppleUSB20HubPort4portEP12OSDictionary : 220 -> 224
~ __ZN17AppleUSB20HubPort4portEP15IORegistryEntryPK15IORegistryPlane : 228 -> 232
~ __ZN17AppleUSB20HubPort4initEP12OSDictionary : 216 -> 220
~ __ZN17AppleUSB20HubPort4initEP15IORegistryEntryPK15IORegistryPlane : 216 -> 220
~ __ZN17AppleUSB20HubPort5startEP9IOService : 180 -> 184
~ __ZN17AppleUSB20HubPort4freeEv : 112 -> 116
~ __ZN17AppleUSB20HubPort14initBusCurrentEv : 176 -> 180
~ __ZN17AppleUSB20HubPort7powerOnEv : 952 -> 956
~ __ZN17AppleUSB20HubPort7suspendEv : 820 -> 824
~ __ZN17AppleUSB20HubPort6resumeEv : 1828 -> 1832
~ __ZN17AppleUSB20HubPort17interruptOccurredEP22IOInterruptEventSourcei : 6884 -> 6888
~ __ZN17AppleUSB20HubPort10disconnectEN16AppleUSBHostPort37AppleUSBHostPortTerminateDeviceReasonE : 1100 -> 1104
~ __ZN17AppleUSB20HubPort20resetAndCreateDeviceEj : 1720 -> 1724
~ __ZN17AppleUSB20HubPort14clearPipeStallEP13IOUSBHostPipe : 384 -> 388
~ __ZN17AppleUSB20HubPort19clearPipeStallGatedEP13IOUSBHostPipe : 1664 -> 1668
~ __ZN17AppleUSB20HubPort18getPortStatusGatedERj : 240 -> 244
~ _GLOBAL__sub_I_AppleUSB20HubPort.cpp : 80 -> 84
~ __ZN13AppleUSB20Hub9MetaClassC1Ev : 72 -> 76
~ __ZN13AppleUSB20HubC2EPK11OSMetaClass : 52 -> 56
~ __ZN13AppleUSB20HubC1EPK11OSMetaClass : 52 -> 56
~ __ZN13AppleUSB20HubD0Ev : 68 -> 72
~ __ZN13AppleUSB20Hub9MetaClassC2Ev : 72 -> 76
~ __ZNK13AppleUSB20Hub9MetaClass5allocEv : 104 -> 108
~ __ZN13AppleUSB20HubC1Ev : 88 -> 92
~ __ZN13AppleUSB20HubC2Ev : 88 -> 92
~ __ZN13AppleUSB20Hub5probeEP9IOServicePi : 244 -> 248
~ __ZN13AppleUSB20Hub5startEP9IOService : 852 -> 856
~ __ZN13AppleUSB20Hub11registerHubEv : 1808 -> 1812
~ __ZN13AppleUSB20Hub21clearPortFeatureGatedEjt : 292 -> 296
~ __ZN13AppleUSB20Hub7clearTTEjP13IOUSBHostPipe : 768 -> 772
~ __ZN13AppleUSB20Hub7resetTTEj : 264 -> 268
~ _GLOBAL__sub_I_AppleUSB20Hub.cpp : 80 -> 84
~ __ZN11AppleUSBHub9MetaClassC1Ev : 72 -> 76
~ __ZN11AppleUSBHubC2EPK11OSMetaClass : 52 -> 56
~ __ZN11AppleUSBHub9MetaClassC2Ev : 72 -> 76
~ __ZN11AppleUSBHub4initEP12OSDictionary : 132 -> 136
~ __ZN11AppleUSBHub5startEP9IOService : 10648 -> 10652
~ __ZN11AppleUSBHub4stopEP9IOService : 648 -> 652
~ __ZN11AppleUSBHub8finalizeEj : 164 -> 168
~ __ZN11AppleUSBHub4freeEv : 472 -> 476
~ __ZN11AppleUSBHub21powerAssertionTimeoutEP18IOTimerEventSource : 228 -> 232
~ __ZN11AppleUSBHub4openEP9IOServicejPv : 664 -> 668
~ __ZN11AppleUSBHub9openGatedEP9IOServicejPv : 712 -> 716
~ __ZN11AppleUSBHub10handleOpenEP9IOServicejPv : 272 -> 276
~ __ZNK11AppleUSBHub12handleIsOpenEPK9IOService : 208 -> 212
~ __ZN11AppleUSBHub5closeEP9IOServicej : 344 -> 348
~ __ZN11AppleUSBHub10closeGatedEP9IOServicej : 180 -> 184
~ __ZN11AppleUSBHub11handleCloseEP9IOServicej : 208 -> 212
~ __ZN11AppleUSBHub13willTerminateEP9IOServicej : 204 -> 208
~ __ZN11AppleUSBHub15registerServiceEj : 108 -> 112
~ __ZN11AppleUSBHub22powerStateWillChangeToEmmP9IOService : 184 -> 188
~ ____ZN11AppleUSBHub22powerStateWillChangeToEmmP9IOService_block_invoke : 500 -> 504
~ ____ZN11AppleUSBHub21powerStateDidChangeToEmmP9IOService_block_invoke : 668 -> 672
~ __ZN11AppleUSBHub13setPropertiesEP8OSObject : 372 -> 376
~ __ZN11AppleUSBHub18setPropertiesGatedEP8OSObject : 960 -> 964
~ __ZN11AppleUSBHub22firstMatchNotificationEPvP9IOServiceP10IONotifier : 744 -> 748
~ __ZN11AppleUSBHub32firstMatchNotificationThreadCallEP11thread_call : 192 -> 196
~ ____ZN11AppleUSBHub32firstMatchNotificationThreadCallEP11thread_call_block_invoke : 3156 -> 3160
~ __ZN11AppleUSBHub11createPortsEv : 5028 -> 5032
~ __ZN11AppleUSBHub28allocateDownstreamBusCurrentEP9IOServiceRjS2_ : 664 -> 668
~ __ZN11AppleUSBHub33allocateDownstreamBusCurrentGatedEP9IOServiceRjS2_ : 4508 -> 4520
~ __ZN11AppleUSBHub12getHubStatusERj : 508 -> 512
~ __ZN11AppleUSBHub15clearHubFeatureEt : 496 -> 500
~ __ZN11AppleUSBHub17getHubPowerSupplyERNS_12tPowerSupplyE : 1732 -> 1736
~ __ZN11AppleUSBHub17interruptOccurredEPvij : 5444 -> 5448
~ __ZN11AppleUSBHub14interruptRetryEP18IOTimerEventSource : 848 -> 852
~ __ZN11AppleUSBHub14setPortFeatureEtt : 320 -> 324
~ __ZN11AppleUSBHub19setPortFeatureGatedEtt : 1556 -> 1560
~ __ZN11AppleUSBHub16clearPortFeatureEjt : 320 -> 324
~ __ZN11AppleUSBHub21clearPortFeatureGatedEjt : 1344 -> 1348
~ __ZN11AppleUSBHub13getPortStatusEjRj : 944 -> 948
~ __ZN11AppleUSBHub13deviceRequestERN11StandardUSB13DeviceRequestEPvP19IOUSBHostCompletionj : 1540 -> 1544
~ __ZN11AppleUSBHub17hardwareExceptionENS_18tHardwareExceptionEi : 760 -> 764
~ __ZN11AppleUSBHub21deviceResetThreadCallEP11thread_call : 140 -> 144
~ _GLOBAL__sub_I_AppleUSBHub.cpp : 80 -> 84
~ __ZN17AppleUSB30HubPort9MetaClassC1Ev : 72 -> 76
~ __ZN17AppleUSB30HubPortC2EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleUSB30HubPortC1EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleUSB30HubPortD0Ev : 68 -> 72
~ __ZN17AppleUSB30HubPort9MetaClassC2Ev : 72 -> 76
~ __ZNK17AppleUSB30HubPort9MetaClass5allocEv : 104 -> 108
~ __ZN17AppleUSB30HubPortC1Ev : 88 -> 92
~ __ZN17AppleUSB30HubPortC2Ev : 88 -> 92
~ __ZN17AppleUSB30HubPort4portEP12OSDictionary : 220 -> 224
~ __ZN17AppleUSB30HubPort4portEP15IORegistryEntryPK15IORegistryPlane : 228 -> 232
~ __ZN17AppleUSB30HubPort4initEP12OSDictionary : 136 -> 140
~ __ZN17AppleUSB30HubPort4initEP15IORegistryEntryPK15IORegistryPlane : 136 -> 140
~ __ZN17AppleUSB30HubPort5startEP9IOService : 180 -> 184
~ __ZN17AppleUSB30HubPort4freeEv : 112 -> 116
~ __ZN17AppleUSB30HubPort14initBusCurrentEv : 176 -> 180
~ __ZN17AppleUSB30HubPort7powerOnEv : 1108 -> 1112
~ __ZN17AppleUSB30HubPort7suspendEv : 804 -> 808
~ __ZN17AppleUSB30HubPort6resumeEv : 1984 -> 1988
~ __ZN17AppleUSB30HubPort17interruptOccurredEP22IOInterruptEventSourcei : 8040 -> 8044
~ __ZN17AppleUSB30HubPort20resetAndCreateDeviceEj : 3600 -> 3604
~ __ZN17AppleUSB30HubPort9warmResetEv : 2504 -> 2508
~ __ZN17AppleUSB30HubPort14clearPipeStallEP13IOUSBHostPipe : 384 -> 388
~ __ZN17AppleUSB30HubPort19clearPipeStallGatedEP13IOUSBHostPipe : 668 -> 672
~ __ZN17AppleUSB30HubPort18getPortStatusGatedERj : 324 -> 328
~ __ZN17AppleUSB30HubPort20updateLPMPolicyGatedE13tUSBLinkStateN16AppleUSBHostPort14tPortLPMPolicyEj : 848 -> 852
~ __ZN17AppleUSB30HubPort12getPortSpeedEv : 2000 -> 2004
~ _GLOBAL__sub_I_AppleUSB30HubPort.cpp : 80 -> 84
~ __ZN15AppleUSBHubPort9MetaClassC1Ev : 72 -> 76
~ __ZN15AppleUSBHubPortC2EPK11OSMetaClass : 52 -> 56
~ __ZN15AppleUSBHubPort9MetaClassC2Ev : 72 -> 76
~ __ZN15AppleUSBHubPort5startEP9IOService : 1236 -> 1240
~ __ZN15AppleUSBHubPort9terminateEj : 116 -> 120
~ __ZN15AppleUSBHubPort4freeEv : 112 -> 116
~ __ZN15AppleUSBHubPort8powerOffEv : 812 -> 816
~ __ZN15AppleUSBHubPort7powerOnEv : 792 -> 796
~ _GLOBAL__sub_I_AppleUSBHubPort.cpp : 80 -> 84
~ __ZN13AppleUSB30Hub9MetaClassC1Ev : 72 -> 76
~ __ZN13AppleUSB30HubC2EPK11OSMetaClass : 52 -> 56
~ __ZN13AppleUSB30HubC1EPK11OSMetaClass : 52 -> 56
~ __ZN13AppleUSB30HubD0Ev : 68 -> 72
~ __ZN13AppleUSB30Hub9MetaClassC2Ev : 72 -> 76
~ __ZNK13AppleUSB30Hub9MetaClass5allocEv : 104 -> 108
~ __ZN13AppleUSB30HubC1Ev : 88 -> 92
~ __ZN13AppleUSB30HubC2Ev : 88 -> 92
~ __ZN13AppleUSB30Hub5probeEP9IOServicePi : 244 -> 248
~ __ZN13AppleUSB30Hub5startEP9IOService : 2624 -> 2628
~ __ZN13AppleUSB30Hub11registerHubEv : 1124 -> 1128
~ __ZN13AppleUSB30Hub19setPortFeatureGatedEtt : 300 -> 304
~ __ZN13AppleUSB30Hub17getLPMExitLatencyE13tUSBLinkState18tUSBLPMExitLatencyRj : 1496 -> 1500
~ __ZN13AppleUSB30Hub13getPortStatusEjRyN13StandardUSB3018tHubPortStatusCodeE : 1396 -> 1400
~ _GLOBAL__sub_I_AppleUSB30Hub.cpp : 80 -> 84
~ __ZN22AppleUSB20CameraKitHub9MetaClassC1Ev : 72 -> 76
~ __ZN22AppleUSB20CameraKitHubC2EPK11OSMetaClass : 52 -> 56
~ __ZN22AppleUSB20CameraKitHubC1EPK11OSMetaClass : 52 -> 56
~ __ZN22AppleUSB20CameraKitHubD0Ev : 68 -> 72
~ __ZN22AppleUSB20CameraKitHub9MetaClassC2Ev : 72 -> 76
~ __ZNK22AppleUSB20CameraKitHub9MetaClass5allocEv : 104 -> 108
~ __ZN22AppleUSB20CameraKitHubC1Ev : 88 -> 92
~ __ZN22AppleUSB20CameraKitHubC2Ev : 88 -> 92
~ __ZN22AppleUSB20CameraKitHub5startEP9IOService : 200 -> 204
~ __ZN22AppleUSB20CameraKitHub33allocateDownstreamBusCurrentGatedEP9IOServiceRjS2_ : 1624 -> 1628
~ _GLOBAL__sub_I_AppleUSB20CameraKitHub.cpp : 80 -> 84
~ _ZN17AppleUSB20HubPort10disconnectEN16AppleUSBHostPort37AppleUSBHostPortTerminateDeviceReasonE.cold.1 : 24 -> 28
~ _ZN17AppleUSB20HubPort19clearPipeStallGatedEP13IOUSBHostPipe.cold.1 : 24 -> 28
~ _ZN11AppleUSBHub5closeEP9IOServicej.cold.1 : 88 -> 92
```
