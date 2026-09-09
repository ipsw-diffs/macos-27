## com.apple.driver.IOBluetoothHIDDriver

> `com.apple.driver.IOBluetoothHIDDriver`

```diff

   __TEXT.__const: 0x1e
   __TEXT.__cstring: 0x2fe1
   __TEXT.__os_log: 0x4776
-  __TEXT_EXEC.__text: 0x1166c
+  __TEXT_EXEC.__text: 0x11820
   __TEXT_EXEC.__auth_stubs: 0x350
   __DATA.__data: 0x188
   __DATA.__common: 0x88
Functions:
~ __ZN25IOAppleBluetoothHIDDriver9MetaClassC1Ev : 72 -> 76
~ __ZN25IOAppleBluetoothHIDDriverC2EPK11OSMetaClass : 52 -> 56
~ __ZN25IOAppleBluetoothHIDDriverC1EPK11OSMetaClass : 52 -> 56
~ __ZN25IOAppleBluetoothHIDDriverD0Ev : 68 -> 72
~ __ZN25IOAppleBluetoothHIDDriver9MetaClassC2Ev : 72 -> 76
~ __ZNK25IOAppleBluetoothHIDDriver9MetaClass5allocEv : 104 -> 108
~ __ZN25IOAppleBluetoothHIDDriverC1Ev : 88 -> 92
~ __ZN25IOAppleBluetoothHIDDriverC2Ev : 88 -> 92
~ __ZN25IOAppleBluetoothHIDDriver4freeEv : 140 -> 144
~ __ZN25IOAppleBluetoothHIDDriver5probeEP9IOServicePi : 176 -> 180
~ __ZN25IOAppleBluetoothHIDDriver13willTerminateEP9IOServicej : 144 -> 148
~ __ZN25IOAppleBluetoothHIDDriver11handleStartEP9IOService : 1600 -> 1604
~ __ZN25IOAppleBluetoothHIDDriver12handleStopWLEP9IOService : 400 -> 404
~ __ZN25IOAppleBluetoothHIDDriver11handleSleepEv : 228 -> 232
~ __ZN25IOAppleBluetoothHIDDriver10handleWakeEv : 236 -> 240
~ __ZN25IOAppleBluetoothHIDDriver11deviceReadyEv : 264 -> 268
~ __ZN25IOAppleBluetoothHIDDriver14handleShutdownEv : 232 -> 236
~ __ZN25IOAppleBluetoothHIDDriver13handleRestartEv : 232 -> 236
~ __ZN25IOAppleBluetoothHIDDriver20processInterruptDataEPht : 296 -> 300
~ __ZN25IOAppleBluetoothHIDDriver11getProtocolEv : 128 -> 132
~ __ZN25IOAppleBluetoothHIDDriver16processCommandWLEP8OSStringP8OSNumber : 2696 -> 2700
~ __ZN25IOAppleBluetoothHIDDriver18startBatteryUpdateEv : 168 -> 172
~ __ZN25IOAppleBluetoothHIDDriver18updateBatteryLevelEv : 488 -> 492
~ __ZN25IOAppleBluetoothHIDDriver18updateBatteryStateEi : 600 -> 604
~ __ZN25IOAppleBluetoothHIDDriver15getBatteryStateEv : 380 -> 384
~ __ZN25IOAppleBluetoothHIDDriver12willShutdownEv : 812 -> 816
~ __ZN25IOAppleBluetoothHIDDriver17getExtendedReportEPKc : 1292 -> 1296
~ __ZN25IOAppleBluetoothHIDDriver17setExtendedReportEPKcPvy : 1124 -> 1128
~ __ZN25IOAppleBluetoothHIDDriver11setCapsLockEb : 100 -> 104
~ _GLOBAL__sub_I_IOAppleBluetoothHIDDriver.cpp : 80 -> 84
~ __ZN20IOBluetoothHIDDriver9MetaClassC1Ev : 72 -> 76
~ __ZN20IOBluetoothHIDDriverC2EPK11OSMetaClass : 52 -> 56
~ __ZN20IOBluetoothHIDDriverC1EPK11OSMetaClass : 52 -> 56
~ __ZN20IOBluetoothHIDDriverD0Ev : 68 -> 72
~ __ZN20IOBluetoothHIDDriver9MetaClassC2Ev : 72 -> 76
~ __ZNK20IOBluetoothHIDDriver9MetaClass5allocEv : 104 -> 108
~ __ZN20IOBluetoothHIDDriverC1Ev : 88 -> 92
~ __ZN20IOBluetoothHIDDriverC2Ev : 88 -> 92
~ __ZN20IOBluetoothHIDDriver5probeEP9IOServicePi : 452 -> 456
~ __ZN20IOBluetoothHIDDriver4freeEv : 516 -> 520
~ __ZN20IOBluetoothHIDDriver13willTerminateEP9IOServicej : 612 -> 616
~ __ZN20IOBluetoothHIDDriver33sendDeviceDisconnectNotificationsEv : 368 -> 372
~ __ZN20IOBluetoothHIDDriver24messageClientsWithStringEjP8OSString : 396 -> 400
~ __ZN20IOBluetoothHIDDriver11handleStartEP9IOService : 5396 -> 5400
~ __ZN20IOBluetoothHIDDriver10timerFiredEP8OSObjectP18IOTimerEventSource : 104 -> 108
~ __ZN20IOBluetoothHIDDriver22ReadyToSleepTimerFiredEP8OSObjectP18IOTimerEventSource : 104 -> 108
~ __ZN20IOBluetoothHIDDriver20debugPrintTimerFiredEP8OSObjectP18IOTimerEventSource : 104 -> 108
~ __ZN20IOBluetoothHIDDriver30staticPrepControlChannelActionEP8OSObjectPvS2_S2_S2_ : 252 -> 256
~ __ZN20IOBluetoothHIDDriver23waitForInterruptChannelEv : 556 -> 560
~ __ZN20IOBluetoothHIDDriver10handleStopEP9IOService : 1060 -> 1064
~ __ZN20IOBluetoothHIDDriver12handleStopWLEP9IOService : 324 -> 328
~ __ZN20IOBluetoothHIDDriver11deviceReadyEv : 408 -> 412
~ __ZN20IOBluetoothHIDDriver17powerStateHandlerEPvS0_jP9IOServiceS0_m : 184 -> 188
~ __ZN20IOBluetoothHIDDriver17closeDownServicesEv : 292 -> 296
~ __ZN20IOBluetoothHIDDriver11handleSleepEv : 288 -> 292
~ __ZNK20IOBluetoothHIDDriver16newProductStringEv : 108 -> 112
~ __ZNK20IOBluetoothHIDDriver19newReportDescriptorEPP18IOMemoryDescriptor : 232 -> 236
~ __ZN20IOBluetoothHIDDriver9getReportEP18IOMemoryDescriptor15IOHIDReportTypej : 612 -> 616
~ __ZN20IOBluetoothHIDDriver9setReportEP18IOMemoryDescriptor15IOHIDReportTypej : 612 -> 616
~ __ZN20IOBluetoothHIDDriver13setPropertiesEP8OSObject : 836 -> 840
~ __ZN20IOBluetoothHIDDriver8sendDataEP23IOBluetoothL2CAPChannelPvy : 3324 -> 3328
~ __ZN20IOBluetoothHIDDriver18staticSendToActionEP8OSObjectPvS2_S2_S2_ : 464 -> 468
~ __ZN20IOBluetoothHIDDriver18processControlDataEPht : 2356 -> 2360
~ __ZN20IOBluetoothHIDDriver20processInterruptDataEPht : 1936 -> 1940
~ __ZN20IOBluetoothHIDDriver27processOkToSendNotificationEv : 332 -> 336
~ __ZN20IOBluetoothHIDDriver11waitForDataEP18IOMemoryDescriptorhh : 2224 -> 2228
~ __Z16DecodedHandshakeh : 340 -> 344
~ __ZN20IOBluetoothHIDDriver16waitForHandshakeEv : 2008 -> 2012
~ __ZN20IOBluetoothHIDDriver15waitForOkToSendEv : 2104 -> 2108
~ __ZN20IOBluetoothHIDDriver10hidControlEh : 668 -> 672
~ __ZN20IOBluetoothHIDDriver11getProtocolEv : 364 -> 368
~ __ZN20IOBluetoothHIDDriver11setProtocolEh : 144 -> 148
~ __ZN20IOBluetoothHIDDriver7getIdleEv : 364 -> 368
~ __ZN20IOBluetoothHIDDriver7setIdleEh : 144 -> 148
~ __ZN20IOBluetoothHIDDriver13setPowerStateEmP9IOService : 372 -> 376
~ __ZN20IOBluetoothHIDDriver15setPowerStateWLEmP9IOService : 472 -> 476
~ __ZN20IOBluetoothHIDDriver17createCommandGateEP9IOService : 240 -> 244
~ __ZN20IOBluetoothHIDDriver19getDevicePropertiesEP9IOService : 352 -> 356
~ __Z27incomingControlDataCallbackP9IOServiceP23IOBluetoothL2CAPChanneltPv : 152 -> 156
~ __ZN20IOBluetoothHIDDriver35staticInterruptChannelOpeningActionEP8OSObjectPvS2_S2_S2_ : 160 -> 164
~ __ZN20IOBluetoothHIDDriver19closeDownServicesWLEv : 1116 -> 1120
~ __ZN20IOBluetoothHIDDriver22prepInterruptChannelWLEv : 1300 -> 1304
~ __Z29incomingInterruptDataCallbackP9IOServiceP23IOBluetoothL2CAPChanneltPv : 152 -> 156
~ __ZN20IOBluetoothHIDDriver11getReportWLEP18IOMemoryDescriptor15IOHIDReportTypej : 1012 -> 1016
~ __ZN20IOBluetoothHIDDriver11setReportWLEP18IOMemoryDescriptor15IOHIDReportTypej : 1988 -> 1992
~ __ZN20IOBluetoothHIDDriver16processCommandWLEP8OSStringP8OSNumber : 5036 -> 5040
~ __ZN20IOBluetoothHIDDriver21getDevicePropertiesWLEP9IOService : 2968 -> 2972
~ __ZN20IOBluetoothHIDDriver25interruptChannelOpeningWLEP23IOBluetoothL2CAPChannel : 1064 -> 1068
~ __ZN20IOBluetoothHIDDriver15willTerminateWLEv : 1196 -> 1200
~ __ZN20IOBluetoothHIDDriver22decrementOutstandingIOEv : 432 -> 436
~ __ZN20IOBluetoothHIDDriver13handleTimeoutEv : 676 -> 680
~ __ZN20IOBluetoothHIDDriver36decrementOutstandingMemoryBlockCountEv : 152 -> 156
~ __ZN20IOBluetoothHIDDriver14GetCurrentTimeEv : 84 -> 88
~ __ZN20IOBluetoothHIDDriver28handleReadyToSleepTimerFiredEv : 92 -> 96
~ __ZN20IOBluetoothHIDDriver26handleDebugPrintTimerFiredEv : 96 -> 100
~ __ZN20IOBluetoothHIDDriver15HIDCommandSleepEPvjPcb : 252 -> 256
~ _GLOBAL__sub_I_IOBluetoothHIDDriver.cpp : 80 -> 84
~ __Z11DoLogPacketPKctPht : 136 -> 140
~ __Z14DoDecodePacketPKctPht : 1816 -> 1820
~ __ZN27IOBluetoothGamepadHIDDriver9MetaClassC1Ev : 72 -> 76
~ __ZN27IOBluetoothGamepadHIDDriverC2EPK11OSMetaClass : 52 -> 56
~ __ZN27IOBluetoothGamepadHIDDriverC1EPK11OSMetaClass : 52 -> 56
~ __ZN27IOBluetoothGamepadHIDDriverD0Ev : 68 -> 72
~ __ZN27IOBluetoothGamepadHIDDriver9MetaClassC2Ev : 72 -> 76
~ __ZNK27IOBluetoothGamepadHIDDriver9MetaClass5allocEv : 104 -> 108
~ __ZN27IOBluetoothGamepadHIDDriverC1Ev : 88 -> 92
~ __ZN27IOBluetoothGamepadHIDDriverC2Ev : 88 -> 92
~ __ZN27IOBluetoothGamepadHIDDriver11deviceReadyEv : 196 -> 200
~ _GLOBAL__sub_I_IOBluetoothGamepadHIDDriver.cpp : 80 -> 84
```
