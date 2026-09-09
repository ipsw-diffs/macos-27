## com.apple.driver.AppleCSEmbeddedAudio

> `com.apple.driver.AppleCSEmbeddedAudio`

```diff

   __TEXT.__cstring: 0x59d
   __TEXT.__os_log: 0x1ea
   __TEXT.__const: 0x30
-  __TEXT_EXEC.__text: 0xa020
+  __TEXT_EXEC.__text: 0xa1fc
   __TEXT_EXEC.__auth_stubs: 0x260
   __DATA.__data: 0x188
   __DATA.__common: 0x198
Functions:
~ __ZN25AppleEmbeddedAudioButtons9MetaClassC1Ev : 72 -> 76
~ __ZN25AppleEmbeddedAudioButtonsC2EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleEmbeddedAudioButtons9MetaClassC2Ev : 72 -> 76
~ __ZN25AppleEmbeddedAudioButtons20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 280 -> 284
~ __ZN25AppleEmbeddedAudioButtons11handleStartEP9IOService : 608 -> 612
~ __ZN25AppleEmbeddedAudioButtons13willTerminateEP9IOServicej : 280 -> 284
~ __ZN25AppleEmbeddedAudioButtons13attachServiceEP9IOService : 276 -> 280
~ __ZN25AppleEmbeddedAudioButtons13startHPDetectEv : 216 -> 220
~ __ZN25AppleEmbeddedAudioButtons14setButtonStateEbP8OSObject : 256 -> 260
~ __ZN25AppleEmbeddedAudioButtons17dispatchPTTButtonEb : 404 -> 408
~ __ZNK25AppleEmbeddedAudioButtons19newReportDescriptorEPP18IOMemoryDescriptor : 148 -> 152
~ __ZN25AppleEmbeddedAudioButtons22dispatchReportForUsageEyjjjj : 428 -> 432
~ _GLOBAL__sub_I_AppleEmbeddedAudioButtons.cpp : 80 -> 84
~ __ZN29AppleEmbeddedButtonController9MetaClassC1Ev : 72 -> 76
~ __ZN29AppleEmbeddedButtonControllerC2EPK11OSMetaClass : 52 -> 56
~ __ZN29AppleEmbeddedButtonController9MetaClassC2Ev : 72 -> 76
~ __ZN29AppleEmbeddedButtonController11handleStartEP9IOService : 252 -> 256
~ __ZN29AppleEmbeddedButtonController13willTerminateEP9IOServicej : 388 -> 392
~ __ZN29AppleEmbeddedButtonController4stopEP9IOService : 256 -> 260
~ __ZN29AppleEmbeddedButtonController15triggerHPDetectEb : 336 -> 340
~ __ZN29AppleEmbeddedButtonController20triggerHPDetectGatedEb : 408 -> 412
~ __ZN29AppleEmbeddedButtonController12initHPDetectEv : 664 -> 668
~ __ZN29AppleEmbeddedButtonController24handlePowerStageChangeOnEb : 796 -> 800
~ __ZN29AppleEmbeddedButtonController13forceHPDetectEP9OSBoolean : 160 -> 164
~ __ZN29AppleEmbeddedButtonController14enableHPDetectEb : 184 -> 188
~ __ZN29AppleEmbeddedButtonController11getHPDetectEPb : 184 -> 188
~ __ZN29AppleEmbeddedButtonController17handleDetectTimerEv : 620 -> 624
~ __ZNK29AppleEmbeddedButtonController20_timeSinceHPInsertMSEv : 156 -> 160
~ __ZN29AppleEmbeddedButtonController16completeHPDetectEbP12OSDictionaryPK8OSSymbol : 2876 -> 2880
~ __ZN29AppleEmbeddedButtonController21handleInterruptActionEv : 152 -> 156
~ __ZN29AppleEmbeddedButtonController14detectFinishedEP12OSDictionaryPK8OSSymbol : 396 -> 400
~ __ZN29AppleEmbeddedButtonController14setButtonStateEbP8OSObject : 248 -> 252
~ __ZN29AppleEmbeddedButtonController21setHSSwitchDebugStateEP8OSObject : 240 -> 244
~ _GLOBAL__sub_I_AppleEmbeddedButtonController.cpp : 288 -> 292
~ __ZN18AppleMikeyReceiver9MetaClassC1Ev : 72 -> 76
~ __ZN18AppleMikeyReceiverC2EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleMikeyReceiver9MetaClassC2Ev : 72 -> 76
~ __ZN18AppleMikeyReceiver11handleStartEP9IOService : 432 -> 436
~ __ZN18AppleMikeyReceiver12handleAttachEv : 292 -> 296
~ __ZN18AppleMikeyReceiver4stopEP9IOService : 112 -> 116
~ __ZN18AppleMikeyReceiver13willTerminateEP9IOServicej : 612 -> 616
~ __ZN18AppleMikeyReceiver15getButtonDetectEv : 132 -> 136
~ __ZN18AppleMikeyReceiver16_getButtonDetectEPb : 156 -> 160
~ __ZN18AppleMikeyReceiver20_startMicDetectGatedEb : 1196 -> 1200
~ __ZN18AppleMikeyReceiver15_setHeadsetTypeEPK8OSSymbol : 352 -> 356
~ __ZN18AppleMikeyReceiver23_continueMicDetectGatedEv : 264 -> 268
~ __ZN18AppleMikeyReceiver15_configureMikeyEv : 956 -> 960
~ __ZN18AppleMikeyReceiver22_disableMicDetectGatedEbb : 460 -> 464
~ __ZN18AppleMikeyReceiver24handleMicDetectInterruptEb : 212 -> 216
~ __ZN18AppleMikeyReceiver20handleTxACKInterruptEbbPKj : 2960 -> 2964
~ __ZN18AppleMikeyReceiver21handleButtonInterruptEhb : 248 -> 252
~ __ZN18AppleMikeyReceiver20handleShortInterruptEbb : 332 -> 336
~ __ZN18AppleMikeyReceiver21handleDetachInterruptEv : 204 -> 208
~ __ZN18AppleMikeyReceiver18_releaseAllButtonsEv : 168 -> 172
~ __ZN18AppleMikeyReceiver27mikeyConfigureHeadsetSwitchEj : 100 -> 104
~ __ZN18AppleMikeyReceiver34mikeyGetHeadsetSwitchSlowRampDelayEv : 104 -> 108
~ __ZN18AppleMikeyReceiver24mikeyDetectHeadsetSwitchEPP8OSObjectb : 732 -> 736
~ __ZN18AppleMikeyReceiver33mikeyGetHeadsetSwitchDetectStatusEv : 232 -> 236
~ __ZN18AppleMikeyReceiver9initForPMEP9IOService : 204 -> 208
~ __ZN18AppleMikeyReceiver18systemWillShutdownEj : 212 -> 216
~ __ZN18AppleMikeyReceiver21_enableMicDetectGatedEv : 544 -> 548
~ _GLOBAL__sub_I_AppleMikeyReceiver.cpp : 300 -> 304
~ __ZN17AppleCSCodecMikey9MetaClassC1Ev : 72 -> 76
~ __ZN17AppleCSCodecMikeyC2EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleCSCodecMikey9MetaClassC2Ev : 72 -> 76
~ __ZN17AppleCSCodecMikey11handleStartEP9IOService : 408 -> 412
~ __ZN17AppleCSCodecMikey14enableHPDetectEb : 164 -> 168
~ __ZN17AppleCSCodecMikey17_setInterruptMaskEb : 288 -> 292
~ __ZN17AppleCSCodecMikey11getHPDetectEPb : 164 -> 168
~ __ZN17AppleCSCodecMikey25mikeyEnableLatchToVCCMAINEb : 720 -> 724
~ __ZN17AppleCSCodecMikey26mikeyDisableLatchToVCCMAINEv : 132 -> 136
~ __ZN17AppleCSCodecMikey25mikeyGetStatusShortDetectEv : 128 -> 132
~ __ZN17AppleCSCodecMikey23mikeyGetStatusMicDetectEv : 332 -> 336
~ __ZN17AppleCSCodecMikey27mikeyClearPendingInterruptsEPb : 400 -> 404
~ __ZN17AppleCSCodecMikey23mikeyConfigureMicDetectEN18AppleMikeyReceiver13MicDetectTypeE : 164 -> 168
~ __ZN17AppleCSCodecMikey23mikeyConfigurePowerModeEN18AppleMikeyReceiver9PowerModeEb : 1160 -> 1164
~ __ZN17AppleCSCodecMikey14_setDetectCtl1Ehh : 1040 -> 1044
~ __ZN17AppleCSCodecMikey27mikeyConfigureHeadsetSwitchEj : 132 -> 136
~ __ZN17AppleCSCodecMikey20mikeyInterruptActionEv : 284 -> 288
~ __ZN17AppleCSCodecMikey18processMikeyStatusEhhhh : 680 -> 684
~ __ZN22AppleCSDS911CodecMikey9MetaClassC1Ev : 72 -> 76
~ __ZN22AppleCSDS911CodecMikeyC2EPK11OSMetaClass : 52 -> 56
~ __ZN22AppleCSDS911CodecMikey9MetaClassC2Ev : 72 -> 76
~ __ZN22AppleCSDS911CodecMikey22codecReadDetectStatus1Ev : 132 -> 136
~ __ZN22AppleCSDS911CodecMikey22codecReadDetectStatus2Ev : 132 -> 136
~ __ZN22AppleCSDS911CodecMikey24codecMaskWriteDetectCtl1Ehh : 176 -> 180
~ __ZN22AppleCSDS911CodecMikey24codecMaskWriteDetectCtl2Ehh : 176 -> 180
~ __ZN22AppleCSDS911CodecMikey20codecWriteDetectCtl3Eh : 160 -> 164
~ __ZN22AppleCSDS911CodecMikey21codecWriteMicSenseCtlEh : 160 -> 164
~ __ZN22AppleCSDS911CodecMikey27codecSetMicLevelDetectPowerEb : 164 -> 168
~ __ZN22AppleCSDS911CodecMikey27codecGetMicLevelDetectPowerEv : 136 -> 140
~ __ZN22AppleCSDS911CodecMikey26codecReadHPInterruptStatusEv : 132 -> 136
~ __ZN22AppleCSDS911CodecMikey30codecReadButtonInterruptStatusEv : 132 -> 136
~ __ZN22AppleCSDS911CodecMikey31codecReadDetectInterruptStatus1Ev : 132 -> 136
~ __ZN22AppleCSDS911CodecMikey31codecReadDetectInterruptStatus2Ev : 132 -> 136
~ __ZN22AppleCSDS911CodecMikey30codecWriteDetectInterruptMask1Eh : 164 -> 168
~ __ZN22AppleCSDS911CodecMikey30codecWriteDetectInterruptMask2Eh : 164 -> 168
~ __ZN22AppleCSDS911CodecMikey18codecSetWakeOutputEbb : 188 -> 192
~ __ZN22AppleCSDS911CodecMikey16codecSetWakeMaskEbb : 204 -> 208
~ __ZN22AppleCSDS911CodecMikey23codecSetHPDetectControlEhhb : 204 -> 208
~ __ZN20AppleCSHTDCodecMikey9MetaClassC1Ev : 72 -> 76
~ __ZN20AppleCSHTDCodecMikeyC2EPK11OSMetaClass : 52 -> 56
~ __ZN20AppleCSHTDCodecMikey9MetaClassC2Ev : 72 -> 76
~ __ZN20AppleCSHTDCodecMikey11handleStartEP9IOService : 424 -> 428
~ __ZN20AppleCSHTDCodecMikey29mikeySetExternalHeadsetSwitchEbbb : 236 -> 240
~ __ZN20AppleCSHTDCodecMikey27mikeyConfigureHeadsetSwitchEj : 552 -> 556
~ __ZN20AppleCSHTDCodecMikey25mikeyEnableLatchToVCCMAINEb : 116 -> 120
~ __ZN20AppleCSHTDCodecMikey25mikeyChangingHPOUTEnabledEb : 104 -> 108
~ __ZN20AppleCSHTDCodecMikey23mikeyConfigurePowerModeEN18AppleMikeyReceiver9PowerModeEb : 216 -> 220
~ __ZN20AppleCSHTDCodecMikey33mikeyGetHeadsetSwitchDetectStatusEv : 80 -> 84
~ __ZN20AppleCSHTDCodecMikey24mikeyDetectHeadsetSwitchEPP8OSObjectb : 1464 -> 1468
~ _GLOBAL__sub_I_AppleCSCodecMikey.cpp : 208 -> 212
~ __GLOBAL__D_a : 68 -> 72
~ __ZN31AppleEmbeddedAudioHeadsetSwitch9MetaClassC1Ev : 72 -> 76
~ __ZN31AppleEmbeddedAudioHeadsetSwitchC2EPK11OSMetaClass : 52 -> 56
~ __ZN31AppleEmbeddedAudioHeadsetSwitch9MetaClassC2Ev : 72 -> 76
~ __ZN31AppleEmbeddedAudioHeadsetSwitch20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 420 -> 424
~ __ZN31AppleEmbeddedAudioHeadsetSwitch5startEP9IOService : 96 -> 100
~ _GLOBAL__sub_I_AppleEmbeddedAudioHeadsetSwitch.cpp : 80 -> 84
```
