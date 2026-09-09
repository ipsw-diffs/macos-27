## VDC

> `/System/Library/Frameworks/CoreMediaIO.framework/Versions/A/Resources/VDC.plugin/Contents/MacOS/VDC`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 520.21.1.0.0
-  __TEXT.__text: 0x35460
+  __TEXT.__text: 0x34bd0
   __TEXT.__auth_stubs: 0xe30
   __TEXT.__gcc_except_tab: 0x2d20
   __TEXT.__const: 0x818
   __TEXT.__oslogstring: 0x5f6c
   __TEXT.__cstring: 0x305d
-  __TEXT.__unwind_info: 0x1378
-  __DATA_CONST.__const: 0x2210
+  __TEXT.__unwind_info: 0x1a70
+  __DATA_CONST.__const: 0x2218
   __DATA_CONST.__cfstring: 0x920
   __DATA_CONST.__auth_got: 0x720
   __DATA_CONST.__got: 0x1b8
Functions:
~ sub_2834 : 36 -> 24
~ sub_28b8 -> sub_28ac : 32 -> 20
~ sub_28d8 -> sub_28c0 : 24 -> 12
~ sub_28f0 -> sub_28cc : 24 -> 12
~ __ZN27CACFDistributedNotification11AddObserverEPKvPFvP22__CFNotificationCenterPvPK10__CFStringS1_PK14__CFDictionaryES7_32CFNotificationSuspensionBehavior : 92 -> 80
~ __ZN27CACFDistributedNotification14RemoveObserverEPKvPK10__CFString : 68 -> 56
~ __ZN27CACFDistributedNotification16PostNotificationEPK10__CFStringPK14__CFDictionaryb : 92 -> 80
~ __ZN7CAMutexD0Ev : 56 -> 44
~ __ZN15CACFPreferences9CopyValueEPK10__CFStringbb : 152 -> 140
~ __ZN15CACFPreferences8SetValueEPK10__CFStringPKvbbb : 168 -> 156
~ __ZN15CACFPreferences11DeleteValueEPK10__CFStringbbb : 176 -> 164
~ __ZNK9CACFArray13GetCACFStringEjR10CACFString : 168 -> 156
~ __ZNK9CACFArray12GetCACFArrayEjRS_ : 188 -> 176
~ __ZNK9CACFArray17GetCACFDictionaryEjR14CACFDictionary : 188 -> 176
~ __ZNK14CACFDictionary13GetCACFStringEPK10__CFStringR10CACFString : 144 -> 132
~ __ZNK14CACFDictionary12GetCACFArrayEPK10__CFStringR9CACFArray : 164 -> 152
~ __ZNK14CACFDictionary17GetCACFDictionaryEPK10__CFStringRS_ : 164 -> 152
~ __ZN12CACFMachPortD0Ev : 56 -> 44
~ __ZN12CACFMachPort14ReceiveMessageEjP17mach_msg_header_tj : 128 -> 116
~ sub_7718 -> sub_7634 : 56 -> 44
~ sub_789c -> sub_77ac : 56 -> 44
~ sub_7a98 -> sub_799c : 56 -> 44
~ sub_7ad0 -> sub_79c8 : 100 -> 88
~ sub_7e4c -> sub_7d38 : 56 -> 44
~ sub_7ea8 -> sub_7d88 : 32 -> 20
~ sub_7ec8 -> sub_7d9c : 28 -> 16
~ __ZN4CMIO2DP8Property10FormatListD2Ev : 152 -> 140
~ __ZN4CMIO2DP8Property10FormatListD0Ev : 56 -> 44
~ __ZN4CMIO2DP8Property10FormatList16SetCurrentFormatEPK25opaqueCMFormatDescriptionb : 124 -> 112
~ __ZN4CMIO2DP8Property10FormatList18AddAvailableFormatEPK25opaqueCMFormatDescription : 84 -> 72
~ __ZN4CMIO2DP8Property10FormatList19AddStillImageFormatEPK25opaqueCMFormatDescription : 84 -> 72
~ __ZN4CMIO2DP8Property10FormatList15SetPropertyDataERK25CMIOObjectPropertyAddressjPKvjS7_ : 972 -> 912
~ sub_9ec4 -> sub_9d14 : 252 -> 244
~ sub_a9f8 -> sub_a840 : 196 -> 192
~ sub_abbc -> sub_aa00 : 196 -> 192
~ sub_acb4 -> sub_aaf4 : 28 -> 16
~ __ZNK4CMIO2DP7Control11HasPropertyERK25CMIOObjectPropertyAddress : 228 -> 216
~ __ZNK4CMIO2DP7Control15GetPropertyDataERK25CMIOObjectPropertyAddressjPKvjRjPv : 840 -> 828
~ __ZNK4CMIO2DP14BooleanControl18IsPropertySettableERK25CMIOObjectPropertyAddress : 88 -> 76
~ __ZNK4CMIO2DP14BooleanControl15GetPropertyDataERK25CMIOObjectPropertyAddressjPKvjRjPv : 288 -> 276
~ __ZN4CMIO2DP14BooleanControl15SetPropertyDataERK25CMIOObjectPropertyAddressjPKvjS6_ : 292 -> 268
~ __ZNK4CMIO2DP15SelectorControl18IsPropertySettableERK25CMIOObjectPropertyAddress : 128 -> 116
~ __ZNK4CMIO2DP15SelectorControl19GetPropertyDataSizeERK25CMIOObjectPropertyAddressjPKv : 140 -> 128
~ __ZNK4CMIO2DP15SelectorControl15GetPropertyDataERK25CMIOObjectPropertyAddressjPKvjRjPv : 652 -> 640
~ __ZN4CMIO2DP15SelectorControl15SetPropertyDataERK25CMIOObjectPropertyAddressjPKvjS6_ : 284 -> 260
~ __ZNK4CMIO2DP14FeatureControl18IsPropertySettableERK25CMIOObjectPropertyAddress : 472 -> 460
~ __ZNK4CMIO2DP14FeatureControl15GetPropertyDataERK25CMIOObjectPropertyAddressjPKvjRjPv : 1748 -> 1696
~ __ZN4CMIO2DP14FeatureControl15SetPropertyDataERK25CMIOObjectPropertyAddressjPKvjS6_ : 1124 -> 1040
~ sub_d430 -> sub_d14c : 28 -> 16
~ __ZN4CMIO29CallbackDrivenFigDerivedClock28FigDerivedClockCopyDebugDescEP13OpaqueCMClock : 84 -> 72
~ __ZN4CMIO29CallbackDrivenFigDerivedClock28FigDerivedClockGetAnchorTimeEP13OpaqueCMClockP6CMTimeS4_ : 88 -> 76
~ sub_d898 -> sub_d590 : 104 -> 92
~ sub_d9e0 -> sub_d6cc : 3576 -> 3580
~ __ZN4CMIO29CallbackDrivenFigDerivedClock33GetAnchorTimeForDebuggingPurposesEP13OpaqueCMClockP6CMTimeS4_ : 112 -> 100
~ sub_f440 -> sub_f124 : 56 -> 44
~ sub_f638 -> sub_f310 : 12 -> 24
~ sub_f644 -> sub_f328 : 36 -> 12
~ sub_f68c -> sub_f358 : 24 -> 12
~ sub_f9a0 -> sub_f660 : 28 -> 16
~ sub_f9bc -> sub_f670 : 32 -> 20
~ sub_f9f8 -> sub_f6a0 : 32 -> 20
~ __ZN4CMIO2DP6DeviceD2Ev : 168 -> 156
~ __ZN4CMIO2DP6Device8TeardownEv : 108 -> 96
~ __ZNK4CMIO2DP6Device15GetPropertyDataERK25CMIOObjectPropertyAddressjPKvjRjPv : 5264 -> 5260
~ sub_12e44 -> sub_12ac4 : 476 -> 468
~ sub_13390 -> sub_13008 : 196 -> 192
~ sub_13674 -> sub_132e8 : 256 -> 260
~ sub_137cc -> sub_13444 : 28 -> 16
~ __ZN4CMIO2DP14ExampleCommandD0Ev : 56 -> 44
~ __ZN4CMIO2DP7HogModeD0Ev : 56 -> 44
~ __ZN4CMIO2DP6ObjectD0Ev : 56 -> 44
~ __ZN4CMIO2DP6Object11SetObjectIDEj : 204 -> 192
~ __ZNK4CMIO2DP6Object18IsPropertySettableERK25CMIOObjectPropertyAddress : 212 -> 200
~ __ZNK4CMIO2DP6Object19GetPropertyDataSizeERK25CMIOObjectPropertyAddressjPKv : 240 -> 228
~ __ZNK4CMIO2DP6Object15GetPropertyDataERK25CMIOObjectPropertyAddressjPKvjRjPv : 344 -> 332
~ __ZN4CMIO2DP6Object15SetPropertyDataERK25CMIOObjectPropertyAddressjPKvjS6_ : 588 -> 552
~ sub_190bc -> sub_18cb0 : 392 -> 388
~ sub_1931c -> sub_18f0c : 28 -> 16
~ __ZN4CMIO2DP6PlugInD2Ev : 124 -> 112
~ __ZN4CMIO2DP6PlugInD0Ev : 56 -> 44
~ __ZN4CMIO2DP6PlugIn22InitializeWithObjectIDEj : 64 -> 52
~ __ZN4CMIO2DP6PlugIn12RemoveDeviceERNS0_6ObjectE : 136 -> 124
~ __ZN4CMIO2DP6Stream10InitializeEv : 220 -> 208
~ sub_1be98 -> sub_1ba40 : 32 -> 20
~ sub_1beb8 -> sub_1ba54 : 32 -> 20
~ __ZN4CMIO3PTA22NotificationPortThread5ResetEb : 376 -> 364
~ __ZN4CMIO3PTA23IsochronousThreadForUSB5ResetEPP23IOUSBInterfaceStruct800 : 368 -> 356
~ sub_1c758 -> sub_1c2d0 : 28 -> 16
~ __ZN4CMIO2DP3VDC14FeatureControlD0Ev : 56 -> 44
~ __ZN4CMIO2DP3VDC14FeatureControl8SetOnOffEj : 324 -> 304
~ __ZN4CMIO2DP3VDC14FeatureControl18SetAutomaticManualEj : 328 -> 308
~ __ZN4CMIO2DP3VDC14FeatureControl17SetAbsoluteNativeEj : 328 -> 308
~ __ZN4CMIO2DP3VDC14FeatureControl7SetTuneEj : 324 -> 304
~ __ZN4CMIO2DP3VDC14FeatureControl14SetNativeValueEf : 308 -> 288
~ __ZN4CMIO2DP3VDC14FeatureControl16SetAbsoluteValueEf : 308 -> 288
~ __ZN4CMIO2DP3VDC11RollControlD0Ev : 56 -> 44
~ __ZN4CMIO2DP3VDC11RollControl18SetAutomaticManualEj : 332 -> 312
~ __ZN4CMIO2DP3VDC12RelativeZoomD0Ev : 56 -> 44
~ __ZNK4CMIO2DP3VDC12RelativeZoom15GetPropertyDataERK25CMIOObjectPropertyAddressjPKvjRjPv : 404 -> 392
~ __ZN4CMIO2DP3VDC12RelativeZoom15SetPropertyDataERK25CMIOObjectPropertyAddressjPKvjS7_ : 268 -> 244
~ __ZN4CMIO2DP3VDC22RelativePanTiltControlD0Ev : 56 -> 44
~ __ZNK4CMIO2DP3VDC22RelativePanTiltControl15GetPropertyDataERK25CMIOObjectPropertyAddressjPKvjRjPv : 400 -> 368
~ __ZN4CMIO2DP3VDC22RelativePanTiltControl15SetPropertyDataERK25CMIOObjectPropertyAddressjPKvjS7_ : 196 -> 172
~ __ZN4CMIO2DP3VDC22AbsolutePanTiltControlD0Ev : 56 -> 44
~ __ZN4CMIO2DP3VDC22AbsolutePanTiltControl20SetUInt64NativeValueEy : 288 -> 268
~ __ZNK4CMIO2DP3VDC22AbsolutePanTiltControl15GetPropertyDataERK25CMIOObjectPropertyAddressjPKvjRjPv : 440 -> 408
~ __ZN4CMIO2DP3VDC22AbsolutePanTiltControl15SetPropertyDataERK25CMIOObjectPropertyAddressjPKvjS7_ : 292 -> 268
~ __ZN4CMIO2DP3VDC15ExposureControlD0Ev : 56 -> 44
~ __ZNK4CMIO2DP3VDC15ExposureControl15GetPropertyDataERK25CMIOObjectPropertyAddressjPKvjRjPv : 1032 -> 1020
~ __ZN4CMIO2DP3VDC15ExposureControl15SetPropertyDataERK25CMIOObjectPropertyAddressjPKvjS7_ : 1148 -> 1064
~ __ZN4CMIO2DP3VDC15ExposureControl19SetRegionOfInterestERK6CGRect : 332 -> 312
~ __ZN4CMIO2DP3VDC15ExposureControl16SetLockThresholdEf : 316 -> 296
~ __ZN4CMIO2DP3VDC15ExposureControl18SetUnlockThresholdEf : 316 -> 296
~ __ZN4CMIO2DP3VDC15ExposureControl9SetTargetEf : 316 -> 296
~ __ZN4CMIO2DP3VDC15ExposureControl19SetConvergenceSpeedEf : 316 -> 296
~ __ZN4CMIO2DP3VDC15ExposureControl9SetStableEh : 308 -> 288
~ __ZNK4CMIO2DP3VDC15ExposureControl21ConstructControlStateEv : 604 -> 564
~ sub_20fe8 -> sub_208d8 : 28 -> 16
~ sub_21050 -> sub_20934 : 32 -> 20
~ __ZN4CMIO2DP3VDC6DeviceD2Ev : 148 -> 136
~ __ZN4CMIO2DP3VDC6DeviceD0Ev : 56 -> 44
~ __ZN4CMIO2DP3VDC6Device8TeardownEv : 108 -> 96
~ __ZN4CMIO2DP3VDC6Device6UnplugEv : 244 -> 224
~ __ZNK4CMIO2DP3VDC6Device14CopyDeviceNameEv : 340 -> 328
~ sub_25658 -> sub_24eec : 196 -> 192
~ sub_257c0 -> sub_25050 : 32 -> 20
~ sub_257e0 -> sub_25064 : 32 -> 20
~ __ZN4CMIO2DP3VDC6PlugInD2Ev : 120 -> 108
~ __ZN4CMIO2DP3VDC6PlugInD0Ev : 56 -> 44
~ __ZNK4CMIO2DP3VDC6PlugIn15GetPropertyDataERK25CMIOObjectPropertyAddressjPKvjRjPv : 256 -> 244
~ sub_27448 -> sub_26c9c : 272 -> 268
~ __ZN4CMIO3PTA16CFMachPortThread5ResetEPFvP12__CFMachPortPvlS4_ES4_ : 372 -> 360
~ __ZN4CMIO2DP3VDC6StreamD2Ev : 128 -> 116
~ __ZN4CMIO2DP3VDC6StreamD0Ev : 56 -> 44
~ __ZN4CMIO2DP3VDC6Stream41AddAvailableAndPossibleFormatDescriptionsEv : 2648 -> 2644
~ __ZN4CMIO2DP3VDC6Stream8TeardownEv : 100 -> 88
~ sub_2b354 -> sub_2ab70 : 476 -> 468
~ __ZN4CMIO2DP3VDC6Stream36TranslateNCLCColorInfoToFigColorInfoER10CACFStringS4_S4_ttt : 204 -> 192
~ sub_2c3f4 -> sub_2bbfc : 56 -> 44
~ sub_2c430 -> sub_2bc2c : 56 -> 44
~ sub_2c4d0 -> sub_2bcc0 : 56 -> 44
~ sub_2c508 -> sub_2bcec : 56 -> 44
~ sub_2c544 -> sub_2bd1c : 56 -> 44
~ sub_2c580 -> sub_2bd4c : 56 -> 44
~ sub_2c620 -> sub_2bde0 : 120 -> 108
~ sub_2c700 -> sub_2beb4 : 120 -> 108
~ sub_2caac -> sub_2c254 : 256 -> 260
~ sub_2cd44 -> sub_2c4f0 : 32 -> 20
~ sub_2cd70 -> sub_2c510 : 28 -> 16
~ sub_2cdc0 -> sub_2c554 : 24 -> 12
~ sub_2cdfc -> sub_2c584 : 24 -> 12
~ sub_2ce14 -> sub_2c590 : 28 -> 16
```
