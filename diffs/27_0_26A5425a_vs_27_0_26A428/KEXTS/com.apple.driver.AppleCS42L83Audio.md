## com.apple.driver.AppleCS42L83Audio

> `com.apple.driver.AppleCS42L83Audio`

```diff

   __TEXT.__const: 0x132
   __TEXT.__cstring: 0x48d
   __TEXT.__os_log: 0x356
-  __TEXT_EXEC.__text: 0x745c
+  __TEXT_EXEC.__text: 0x757c
   __TEXT_EXEC.__auth_stubs: 0x240
   __DATA.__data: 0xc8
   __DATA.__common: 0x88
Functions:
~ __ZN17AppleCS42L83Audio9MetaClassC1Ev : 72 -> 76
~ __ZN17AppleCS42L83AudioC2EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleCS42L83AudioC1EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleCS42L83AudioD0Ev : 68 -> 72
~ __ZN17AppleCS42L83Audio9MetaClassC2Ev : 72 -> 76
~ __ZNK17AppleCS42L83Audio9MetaClass5allocEv : 104 -> 108
~ __ZN17AppleCS42L83AudioC1Ev : 88 -> 92
~ __ZN17AppleCS42L83AudioC2Ev : 88 -> 92
~ __ZN17AppleCS42L83Audio11handleStartEP9IOService : 1920 -> 1924
~ __ZN17AppleCS42L83Audio21_codecInterruptActionEP22IOInterruptEventSourcei : 1044 -> 1048
~ __ZN17AppleCS42L83Audio13enableAudioHWEb : 644 -> 648
~ __ZN17AppleCS42L83Audio13_powerOnCodecEb : 1956 -> 1960
~ __ZN17AppleCS42L83Audio14disableAudioHWEbb : 296 -> 300
~ __ZN17AppleCS42L83Audio14_powerOffCodecEb : 1068 -> 1072
~ __ZN17AppleCS42L83Audio21_checkAndEnableExtMicEv : 288 -> 292
~ __ZN17AppleCS42L83Audio16_setupAudioInputEv : 1088 -> 1092
~ __ZN17AppleCS42L83Audio22startTransportCompleteEv : 176 -> 180
~ __ZN17AppleCS42L83Audio17_setupAudioOutputEv : 1472 -> 1476
~ __ZN17AppleCS42L83Audio17_configureIntMClkEx : 2092 -> 2096
~ __ZN17AppleCS42L83Audio15_setInputVolumeEv : 232 -> 236
~ __ZN17AppleCS42L83Audio10_enableWNFEb : 172 -> 176
~ __ZN17AppleCS42L83Audio15enableInputMuteEb : 200 -> 204
~ __ZN17AppleCS42L83Audio18_setDMicBclkSwitchEj : 232 -> 236
~ __ZN17AppleCS42L83Audio18_setDMicDataSwitchEj : 240 -> 244
~ __ZN17AppleCS42L83Audio17_setAopMclkSwitchEj : 240 -> 244
~ __ZN17AppleCS42L83Audio21_configureMicSwitchesEv : 852 -> 856
~ __ZN17AppleCS42L83Audio16enableAudioInputEb : 252 -> 256
~ __ZN17AppleCS42L83Audio20requestCodecPowerOffEv : 352 -> 356
~ __ZN17AppleCS42L83Audio17enableAudioOutputEb : 372 -> 376
~ __ZN17AppleCS42L83Audio16enableOutputMuteEb : 196 -> 200
~ __ZN17AppleCS42L83Audio13initMicDetectEv : 380 -> 384
~ __ZN17AppleCS42L83MikeyC1Ev : 88 -> 92
~ __ZN17AppleCS42L83Audio4PingEv : 216 -> 220
~ __ZN17AppleCS42L83Audio9_writeRegEjh : 140 -> 144
~ __ZN17AppleCS42L83Audio8_readRegEj : 132 -> 136
~ __ZN17AppleCS42L83Audio14_writeMultipleEjPKhy : 136 -> 140
~ __ZN17AppleCS42L83Audio13_readMultipleEjPhy : 132 -> 136
~ __ZN17AppleCS42L83Audio20_configureSerialPortEx : 384 -> 388
~ __ZN17AppleCS42L83Audio19_setHeadphoneVolumeEv : 300 -> 304
~ __ZN17AppleCS42L83Audio19getChannelsPerFrameEj : 176 -> 180
~ __ZN17AppleCS42L83Audio13setSampleRateEx : 380 -> 384
~ __ZN17AppleCS42L83Mikey9MetaClassC1Ev : 72 -> 76
~ __ZN17AppleCS42L83MikeyC2EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleCS42L83MikeyC1EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleCS42L83MikeyD0Ev : 68 -> 72
~ __ZN17AppleCS42L83Mikey9MetaClassC2Ev : 72 -> 76
~ __ZNK17AppleCS42L83Mikey9MetaClass5allocEv : 104 -> 108
~ __ZN17AppleCS42L83MikeyC2Ev : 88 -> 92
~ __ZN17AppleCS42L83Mikey11handleStartEP9IOService : 120 -> 124
~ __ZN17AppleCS42L83Mikey12handleAttachEv : 84 -> 88
~ __ZN17AppleCS42L83Mikey25codecEnableMikeyInterruptEb : 212 -> 216
~ __ZN17AppleCS42L83Mikey21codecGetHeadsetOffsetE17CirrusHTDRegister : 144 -> 148
~ __ZN17AppleCS42L83Mikey12codecReadRegE17CirrusHTDRegister : 104 -> 108
~ __ZN17AppleCS42L83Mikey13codecWriteRegE17CirrusHTDRegisterh : 112 -> 116
~ __ZN17AppleCS42L83Mikey17codecMaskWriteRegE17CirrusHTDRegisterhh : 192 -> 196
~ __ZN17AppleCS42L83Mikey21codecGetHSDetAutoDoneEv : 68 -> 72
~ __ZN17AppleCS42L83Mikey14_setDetectCtl1Ehh : 552 -> 556
~ __ZN17AppleCS42L83Mikey15triggerHPDetectEb : 244 -> 248
~ __ZN17AppleCS42L83Audio21getBooleanControlInfoEjPb : 188 -> 192
~ __ZN17AppleCS42L83Audio10SetControlEjj : 976 -> 980
~ __ZN17AppleCS42L83Audio23getLevelControlRangeMapEjjPj : 184 -> 188
~ __ZN17AppleCS42L83Audio21getSelectorControlMapEjPbPP7OSArray : 512 -> 516
~ __ZN17AppleCS42L83Audio20ValidateInternalMicsEjPK7OSArray : 280 -> 284
~ __ZN17AppleCS42L83Audio21preflightMultiControlEjPK7OSArrayS2_ : 396 -> 400
~ __ZN17AppleCS42L83Audio15SetMultiControlEjPK7OSArray : 652 -> 656
~ __ZN17AppleCS42L83Audio20blockControlExchangeEjjPv : 2700 -> 2704
~ __ZN17AppleCS42L83Audio29getSupportedBitsPerSampleListEjPj : 268 -> 272
~ __ZN17AppleCS42L83Audio28notifyStartTransportCompleteEPK8OSSymbol : 168 -> 172
~ _GLOBAL__sub_I_AppleCS42L83Audio.cpp : 240 -> 244
~ __GLOBAL__D_a : 56 -> 60
~ __ZN17AppleCS42L83Audio31notifySecondaryAudioEnableGatedEPK8OSSymboljb : 548 -> 552
~ _ZN17AppleCS42L83Audio20ValidateInternalMicsEjPK7OSArray.cold.1 : 44 -> 48
```
