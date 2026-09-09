## com.apple.driver.AppleBluetoothMultitouch

> `com.apple.driver.AppleBluetoothMultitouch`

```diff

 106.0.0.0.0
   __TEXT.__cstring: 0x1efe
   __TEXT.__const: 0xe
-  __TEXT_EXEC.__text: 0x772c
+  __TEXT_EXEC.__text: 0x7868
   __TEXT_EXEC.__auth_stubs: 0x220
   __DATA.__data: 0xc8
   __DATA.__common: 0xb0
Functions:
~ __ZN28BluetoothMultitouchTransport9MetaClassC1Ev : 72 -> 76
~ __ZN28BluetoothMultitouchTransportC2EPK11OSMetaClass : 52 -> 56
~ __ZN28BluetoothMultitouchTransport9MetaClassC2Ev : 72 -> 76
~ __ZN28BluetoothMultitouchTransport4initEP12OSDictionary : 252 -> 256
~ __ZN28BluetoothMultitouchTransport4freeEv : 316 -> 320
~ __ZN28BluetoothMultitouchTransport22enableMultitouchEventsEb : 300 -> 304
~ __ZN28BluetoothMultitouchTransport19getMultitouchReportEhPhPji : 320 -> 324
~ __ZN28BluetoothMultitouchTransport19setMultitouchReportEhPhji : 320 -> 324
~ __ZN28BluetoothMultitouchTransport23getMultitouchReportInfoEhPhPji : 320 -> 324
~ __ZN28BluetoothMultitouchTransport21resetMultitouchDeviceEv : 288 -> 292
~ __ZN28BluetoothMultitouchTransport13setPropertiesEP8OSObject : 352 -> 356
~ __ZN28BluetoothMultitouchTransport24setMultitouchPreferencesEP12OSDictionary : 300 -> 304
~ __ZN28BluetoothMultitouchTransport20multitouchPropertiesEv : 1120 -> 1124
~ __ZN28BluetoothMultitouchTransport23createMultitouchHandlerEv : 432 -> 436
~ __ZN28BluetoothMultitouchTransport15startMultitouchEv : 376 -> 380
~ __ZN28BluetoothMultitouchTransport23startMultitouchThreadedEv : 1160 -> 1164
~ __ZN28BluetoothMultitouchTransport19_multitouchDidStartEv : 236 -> 240
~ __ZN28BluetoothMultitouchTransport18runActionWithRetryEPFiP8OSObjectPvS2_S2_S2_ES1_S2_S2_S2_S2_i : 268 -> 272
~ __ZN28BluetoothMultitouchTransport20desyncIncomingMTDataEPhj : 272 -> 276
~ __ZN28BluetoothMultitouchTransport26desyncIncomingMTDataActionEPS_Pvj : 212 -> 216
~ _GLOBAL__sub_I_BluetoothMultitouchTransport.cpp : 80 -> 84
~ __ZN17BNBTrackpadDevice9MetaClassC1Ev : 72 -> 76
~ __ZN17BNBTrackpadDeviceC2EPK11OSMetaClass : 52 -> 56
~ __ZN17BNBTrackpadDeviceC1EPK11OSMetaClass : 52 -> 56
~ __ZN17BNBTrackpadDeviceD0Ev : 68 -> 72
~ __ZN17BNBTrackpadDevice9MetaClassC2Ev : 72 -> 76
~ __ZNK17BNBTrackpadDevice9MetaClass5allocEv : 104 -> 108
~ __ZN17BNBTrackpadDeviceC1Ev : 88 -> 92
~ __ZN17BNBTrackpadDeviceC2Ev : 88 -> 92
~ __ZN17BNBTrackpadDevice20processInterruptDataEPht : 1460 -> 1464
~ __ZN17BNBTrackpadDevice19newDeviceUsagePairsEv : 560 -> 564
~ _GLOBAL__sub_I_BNBTrackpadDevice.cpp : 80 -> 84
~ __ZN14BNBMouseDevice9MetaClassC1Ev : 72 -> 76
~ __ZN14BNBMouseDeviceC2EPK11OSMetaClass : 52 -> 56
~ __ZN14BNBMouseDeviceC1EPK11OSMetaClass : 52 -> 56
~ __ZN14BNBMouseDeviceD0Ev : 68 -> 72
~ __ZN14BNBMouseDevice9MetaClassC2Ev : 72 -> 76
~ __ZNK14BNBMouseDevice9MetaClass5allocEv : 104 -> 108
~ __ZN14BNBMouseDeviceC1Ev : 88 -> 92
~ __ZN14BNBMouseDeviceC2Ev : 88 -> 92
~ __ZN14BNBMouseDevice20processInterruptDataEPht : 1788 -> 1792
~ __ZN14BNBMouseDevice19_multitouchDidStartEv : 420 -> 424
~ __ZN14BNBMouseDevice26setDefaultMousePreferencesEv : 396 -> 400
~ __ZN14BNBMouseDevice27_setDefaultMousePreferencesEv : 204 -> 208
~ __ZN14BNBMouseDevice18setUserPreferencesEP12OSDictionary : 524 -> 528
~ __ZN14BNBMouseDevice20syncMousePreferencesEv : 288 -> 292
~ __ZN14BNBMouseDevice21_syncMousePreferencesEv : 632 -> 636
~ _GLOBAL__sub_I_BNBMouseDevice.cpp : 80 -> 84
~ __ZN9BNBDevice9MetaClassC1Ev : 72 -> 76
~ __ZN9BNBDeviceC2EPK11OSMetaClass : 52 -> 56
~ __ZN9BNBDeviceC1EPK11OSMetaClass : 52 -> 56
~ __ZN9BNBDeviceD0Ev : 68 -> 72
~ __ZN9BNBDevice9MetaClassC2Ev : 72 -> 76
~ __ZNK9BNBDevice9MetaClass5allocEv : 104 -> 108
~ __ZN9BNBDeviceC1Ev : 88 -> 92
~ __ZN9BNBDeviceC2Ev : 88 -> 92
~ __ZN9BNBDevice4initEP12OSDictionary : 180 -> 184
~ __ZN9BNBDevice11handleStartEP9IOService : 488 -> 492
~ __ZN9BNBDevice25staticKickStartTimerFiredEP8OSObjectP18IOTimerEventSource : 156 -> 160
~ __ZN9BNBDevice13willTerminateEP9IOServicej : 144 -> 148
~ __ZN9BNBDevice10handleStopEP9IOService : 128 -> 132
~ __ZN9BNBDevice4freeEv : 164 -> 168
~ __ZN9BNBDevice16processCommandWLEP8OSStringP8OSNumber : 460 -> 464
~ __ZN9BNBDevice21processIncomingMTDataEPhj : 2084 -> 2088
~ __ZN9BNBDevice20appendMultitouchDataEPhj : 340 -> 344
~ __ZN9BNBDevice19extractTrackingDataEPhjPiS1_Pj : 852 -> 856
~ __ZN9BNBDevice19_multitouchDidStartEv : 292 -> 296
~ __ZN9BNBDevice23_enableMultitouchEventsEb : 308 -> 312
~ __ZN9BNBDevice24_getMultitouchReportInfoEhPhPj : 444 -> 448
~ __ZN9BNBDevice20_getMultitouchReportEhPhPj : 816 -> 820
~ __ZN9BNBDevice20_setMultitouchReportEhPhj : 660 -> 664
~ __ZN9BNBDevice22_resetMultitouchDeviceEv : 240 -> 244
~ __ZN9BNBDevice16_simpleGetReportEhPhj : 628 -> 632
~ __ZN9BNBDevice16_simpleSetReportEhPhj : 628 -> 632
~ __ZN9BNBDevice22_setMultitouchReportIDEh : 252 -> 256
~ __Z17MillisecondsSincey : 100 -> 104
~ __ZN9BNBDevice17getExtendedReportEPKc : 2004 -> 2008
~ __ZN9BNBDevice19newDeviceUsagePairsEv : 560 -> 564
~ _GLOBAL__sub_I_BNBDevice.cpp : 80 -> 84
```
