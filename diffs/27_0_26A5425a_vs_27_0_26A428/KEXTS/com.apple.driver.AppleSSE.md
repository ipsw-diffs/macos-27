## com.apple.driver.AppleSSE

> `com.apple.driver.AppleSSE`

```diff

 328.0.0.0.0
   __TEXT.__cstring: 0x17c9
   __TEXT.__const: 0xc8
-  __TEXT_EXEC.__text: 0x8a58
+  __TEXT_EXEC.__text: 0x8bb0
   __TEXT_EXEC.__auth_stubs: 0x280
   __DATA.__data: 0xc8
   __DATA.__common: 0x88
Functions:
~ __ZN18AppleSSEUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN18AppleSSEUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleSSEUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleSSEUserClientD0Ev : 68 -> 72
~ __ZN18AppleSSEUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK18AppleSSEUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN18AppleSSEUserClientC1Ev : 88 -> 92
~ __ZN18AppleSSEUserClientC2Ev : 88 -> 92
~ __ZN18AppleSSEUserClient12initWithTaskEP4taskPvjP12OSDictionary : 344 -> 348
~ __ZN18AppleSSEUserClient11clientCloseEv : 132 -> 136
~ __ZN18AppleSSEUserClient5startEP9IOService : 184 -> 188
~ _GLOBAL__sub_I_AppleSSEUserClient.cpp : 80 -> 84
~ __ZN17AppleSSEInterface9MetaClassC1Ev : 72 -> 76
~ __ZN17AppleSSEInterfaceC2EPK11OSMetaClass : 52 -> 56
~ __ZN17AppleSSEInterface9MetaClassC2Ev : 72 -> 76
~ _GLOBAL__sub_I_AppleSSEInterface.cpp : 80 -> 84
~ __ZN8AppleSSE9MetaClassC1Ev : 72 -> 76
~ __ZN8AppleSSEC2EPK11OSMetaClass : 72 -> 76
~ __ZN8AppleSSEC1EPK11OSMetaClass : 72 -> 76
~ __ZN8AppleSSED2Ev : 360 -> 364
~ __ZN8AppleSSED1Ev : 360 -> 364
~ __ZN8AppleSSED0Ev : 68 -> 72
~ __ZN8AppleSSE9MetaClassC2Ev : 72 -> 76
~ __ZNK8AppleSSE9MetaClass5allocEv : 52 -> 56
~ __ZN8AppleSSEC2Ev : 108 -> 112
~ __ZN8AppleSSE5probeEP9IOServicePi : 140 -> 144
~ __ZN8AppleSSE5startEP9IOService : 1236 -> 1240
~ __ZN8AppleSSE25powerOffCompletionHandlerEP18IOTimerEventSource : 256 -> 260
~ __ZN8AppleSSE24wakeFromHibernateHandlerEP18IOTimerEventSource : 356 -> 360
~ __ZN8AppleSSE4stopEP9IOService : 964 -> 968
~ __ZN8AppleSSE19performCommandGatedEP18IOMemoryDescriptorS1_Pj : 1908 -> 1912
~ __ZN8AppleSSE14generateSigKeyEPvmS0_Pj : 352 -> 356
~ __ZN8AppleSSE13confirmSigKeyEPvm : 264 -> 268
~ __ZN8AppleSSE12hasBridgeSSEEPvPj : 312 -> 316
~ __ZN8AppleSSE15isInternalBuildEv : 36 -> 40
~ __ZN8AppleSSE22getSignedSepScoresTestEPvmS0_Pj : 3284 -> 3288
~ __ZN8AppleSSE25getCertificateExpDateTestEPvmS0_Pj : 488 -> 492
~ __ZN8AppleSSE18getCertificateTestEPvmS0_Pj : 1380 -> 1384
~ __ZN8AppleSSE23issueNewCertificateTestEPvm : 260 -> 264
~ __ZN8AppleSSE25sendSetBlessedUserCommandEPvm : 256 -> 260
~ __ZN8AppleSSE30sendSEPCommandWithLongResponseEhiPvmS0_Pjb : 488 -> 492
~ __ZN8AppleSSE18getSignedSepScoresEhP6OSDataS1_S1_S1_S1_S1_PS1_S2_S2_ : 116 -> 120
~ __ZN8AppleSSE18getSignedSepScoresEjhP6OSDataS1_S1_S1_S1_S1_PS1_S2_S2_ : 228 -> 232
~ __ZN7libkern20intrusive_shared_ptrI6OSData27intrusive_osobject_retainerE5resetEPS1_NS_8retain_tE : 116 -> 120
~ __ZN8AppleSSE18getSignedSepScoresEhP6OSDataS1_S1_S1_S1_S1_PS1_S2_PP7OSArray : 116 -> 120
~ __ZN8AppleSSE18getSignedSepScoresEjhP6OSDataS1_S1_S1_S1_S1_PS1_S2_PP7OSArray : 896 -> 900
~ __ZN8AppleSSE23getSignedSepScoresGatedEPNS_30get_signed_sep_scores_params_tE : 1480 -> 1484
~ __ZN8AppleSSE28getCertificateExpirationDateE18certificate_type_tPy : 236 -> 240
~ __ZN8AppleSSE33getCertificateExpirationDateGatedE18certificate_type_tPy : 308 -> 312
~ __ZN8AppleSSE14getCertificateE18certificate_type_tPP7OSArray : 236 -> 240
~ __ZN8AppleSSE19getCertificateGatedE18certificate_type_tPP7OSArray : 224 -> 228
~ __ZN8AppleSSE19issueNewCertificateE18certificate_type_t : 224 -> 228
~ __ZN8AppleSSE24issueNewCertificateGatedE18certificate_type_t : 252 -> 256
~ __ZN8AppleSSE27prepareGetSignedSepScoresV2EPNS_30get_signed_sep_scores_params_tEN7libkern17bounded_array_refIhN9os_detail21panic_trapping_policyEEEPj : 1812 -> 1816
~ __ZNK7libkern17bounded_array_refIhN9os_detail21panic_trapping_policyEE5sliceEmm : 72 -> 76
~ __ZN8AppleSSE31prepareGetSignedSepScoresV3V4V5EPNS_30get_signed_sep_scores_params_tEN7libkern17bounded_array_refIhN9os_detail21panic_trapping_policyEEEPj : 1720 -> 1724
~ __ZN8AppleSSE21prepareBAACertificateEv : 200 -> 204
~ __ZN8AppleSSE17getOSDataFromBuffEjN7libkern11bounded_ptrIhN9os_detail21panic_trapping_policyEEEPhR11OSSharedPtrI6OSDataE : 556 -> 560
~ __ZN8AppleSSE26getOSArrayOfOSDataFromBuffEjN7libkern11bounded_ptrIhN9os_detail21panic_trapping_policyEEEPhR11OSSharedPtrI7OSArrayEPj : 1076 -> 1080
~ __ZN8AppleSSE31getBAACertificateExpirationDateEPy : 336 -> 340
~ __ZN8AppleSSE18getBAACertificatesEPP7OSArray : 520 -> 524
~ __ZN8AppleSSE22issueNewBAACertificateEv : 636 -> 640
~ __ZN8AppleSSE8lockItemEPjj : 252 -> 256
~ __ZN8AppleSSE13setPowerStateEmP9IOService : 188 -> 192
~ __ZN8AppleSSE22powerStateWillChangeToEmmP9IOService : 188 -> 192
~ __ZN8AppleSSE18systemWillShutdownEj : 180 -> 184
~ __ZN8AppleSSE16handleSEPMessageEPvS0_ : 608 -> 612
~ __ZN8AppleSSE17readFromSEPBufferEPvm : 480 -> 484
~ __ZN8AppleSSE14sendSEPCommandEhiPvmS0_Pjb : 1064 -> 1068
~ __ZN8AppleSSE16sendSEPCommProbeEy : 556 -> 560
~ __ZN8AppleSSE16writeToSEPBufferEPvm : 480 -> 484
~ __ZN8AppleSSE14sendSEPMessageEPvhit : 312 -> 316
~ __ZN8AppleSSE14getSEPEndpointEv : 2120 -> 2124
~ __ZN8AppleSSE21initializeSEPEndpointEv : 72 -> 76
~ _GLOBAL__sub_I_AppleSSE.cpp : 80 -> 84
~ __ZN18AppleSSEUserClient10extPerformEP8AppleSSEPvP25IOExternalMethodArguments : 368 -> 372
~ __ZN8AppleSSE18setPowerStateGatedEPm : 696 -> 700
~ __ZN9os_detail21panic_trapping_policy4trapEPKc : 48 -> 52
~ _ZN8AppleSSE22getSignedSepScoresTestEPvmS0_Pj.cold.1 : 16 -> 20
~ _ZN8AppleSSE22getSignedSepScoresTestEPvmS0_Pj.cold.8 : 16 -> 20
~ _ZN8AppleSSE22getSignedSepScoresTestEPvmS0_Pj.cold.14 : 16 -> 20
~ _ZN8AppleSSE22getSignedSepScoresTestEPvmS0_Pj.cold.19 : 16 -> 20
~ _ZNK7libkern17bounded_array_refIhN9os_detail21panic_trapping_policyEE5sliceEmm.cold.1 : 24 -> 28
~ _ZNK7libkern17bounded_array_refIhN9os_detail21panic_trapping_policyEE5sliceEmm.cold.2 : 24 -> 28
~ _ZN8AppleSSE14getSEPEndpointEv.cold.1 : 92 -> 96
~ _ZN8AppleSSE14getSEPEndpointEv.cold.2 : 92 -> 96
```
