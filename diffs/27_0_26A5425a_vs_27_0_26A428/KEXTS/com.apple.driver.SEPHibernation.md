## com.apple.driver.SEPHibernation

> `com.apple.driver.SEPHibernation`

```diff

 928.0.2.0.0
   __TEXT.__cstring: 0xa51
   __TEXT.__const: 0xc0
-  __TEXT_EXEC.__text: 0x1d08
+  __TEXT_EXEC.__text: 0x1e24
   __TEXT_EXEC.__auth_stubs: 0x160
   __DATA.__data: 0xc4
   __DATA.__common: 0x60
Functions:
~ __ZN10Hibernator9MetaClassC1Ev : 72 -> 76
~ __ZN10HibernatorC2EPK11OSMetaClass : 52 -> 56
~ __ZN10HibernatorC1EPK11OSMetaClass : 52 -> 56
~ __ZN10HibernatorD0Ev : 68 -> 72
~ __ZN10Hibernator9MetaClassC2Ev : 72 -> 76
~ __ZNK10Hibernator9MetaClass5allocEv : 104 -> 108
~ __ZN10HibernatorC1Ev : 88 -> 92
~ __ZN10HibernatorC2Ev : 88 -> 92
~ __ZN10Hibernator10hibernatorEP18HibernationService : 168 -> 172
~ _GLOBAL__sub_I_Hibernator.cpp : 80 -> 84
~ __ZN18HibernationService9MetaClassC1Ev : 72 -> 76
~ __ZN18HibernationServiceC2EPK11OSMetaClass : 52 -> 56
~ __ZN18HibernationServiceC1EPK11OSMetaClass : 52 -> 56
~ __ZN18HibernationServiceD0Ev : 68 -> 72
~ __ZN18HibernationService9MetaClassC2Ev : 72 -> 76
~ __ZNK18HibernationService9MetaClass5allocEv : 104 -> 108
~ __ZN18HibernationServiceC1Ev : 88 -> 92
~ __ZN18HibernationServiceC2Ev : 88 -> 92
~ __ZN18HibernationService5startEP9IOService : 472 -> 476
~ __ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService : 676 -> 680
~ __ZN18HibernationService19_setPowerStateGatedEPm : 576 -> 580
~ __ZN18HibernationService23_resumeHibernationGatedEPK25hibe_resume_hib_payload_t : 192 -> 196
~ __ZN18HibernationService13setPowerStateEmP9IOService : 132 -> 136
~ __ZN18HibernationService12_msgReceivedEPvS0_ : 128 -> 132
~ __ZN18HibernationService17_sendMessageGatedEPK10hibe_msg_t : 312 -> 316
~ __ZN18HibernationService24_prepareToHibernateGatedEP20sephib_wrapped_key_tP27sephib_seprom_hib_payload_t : 260 -> 264
~ __ZN18HibernationService20_startOperationGatedEv : 344 -> 348
~ __ZN18HibernationService18_endOperationGatedEv : 204 -> 208
~ __ZN18HibernationService18prepareToHibernateEP20sephib_wrapped_key_tP27sephib_seprom_hib_payload_t : 112 -> 116
~ _GLOBAL__sub_I_HibernationService.cpp : 80 -> 84
~ _ZN10Hibernator10hibernatorEP18HibernationService.cold.1 : 56 -> 60
~ _ZN10Hibernator10hibernatorEP18HibernationService.cold.2 : 56 -> 60
~ _ZN18HibernationService5startEP9IOService.cold.1 : 52 -> 56
~ _ZN18HibernationService5startEP9IOService.cold.2 : 52 -> 56
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.1 : 44 -> 48
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.2 : 44 -> 48
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.3 : 44 -> 48
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.4 : 44 -> 48
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.5 : 44 -> 48
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.6 : 44 -> 48
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.7 : 44 -> 48
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.8 : 44 -> 48
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.9 : 44 -> 48
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.10 : 44 -> 48
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.11 : 44 -> 48
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.12 : 44 -> 48
~ _ZN18HibernationService14_setupEndpointEP21AppleSEPDeviceService.cold.13 : 44 -> 48
~ _ZN18HibernationService19_setPowerStateGatedEPm.cold.1 : 52 -> 56
~ _ZN18HibernationService19_setPowerStateGatedEPm.cold.2 : 52 -> 56
~ _ZN18HibernationService19_setPowerStateGatedEPm.cold.3 : 52 -> 56
~ _ZN18HibernationService19_setPowerStateGatedEPm.cold.4 : 52 -> 56
~ _ZN18HibernationService19_setPowerStateGatedEPm.cold.5 : 52 -> 56
~ _ZN18HibernationService23_resumeHibernationGatedEPK25hibe_resume_hib_payload_t.cold.1 : 52 -> 56
~ _ZN18HibernationService23_resumeHibernationGatedEPK25hibe_resume_hib_payload_t.cold.2 : 52 -> 56
~ _ZN18HibernationService13setPowerStateEmP9IOService.cold.1 : 52 -> 56
~ _ZN18HibernationService12_msgReceivedEPvS0_.cold.1 : 52 -> 56
~ _ZN18HibernationService12_msgReceivedEPvS0_.cold.2 : 52 -> 56
~ _ZN18HibernationService12_msgReceivedEPvS0_.cold.3 : 52 -> 56
~ _ZN18HibernationService17_sendMessageGatedEPK10hibe_msg_t.cold.1 : 52 -> 56
~ _ZN18HibernationService17_sendMessageGatedEPK10hibe_msg_t.cold.2 : 52 -> 56
~ _ZN18HibernationService17_sendMessageGatedEPK10hibe_msg_t.cold.3 : 52 -> 56
~ _ZN18HibernationService17_sendMessageGatedEPK10hibe_msg_t.cold.4 : 52 -> 56
~ _ZN18HibernationService24_prepareToHibernateGatedEP20sephib_wrapped_key_tP27sephib_seprom_hib_payload_t.cold.1 : 52 -> 56
~ _ZN18HibernationService24_prepareToHibernateGatedEP20sephib_wrapped_key_tP27sephib_seprom_hib_payload_t.cold.2 : 52 -> 56
~ _ZN18HibernationService24_prepareToHibernateGatedEP20sephib_wrapped_key_tP27sephib_seprom_hib_payload_t.cold.3 : 52 -> 56
~ _ZN18HibernationService20_startOperationGatedEv.cold.1 : 52 -> 56
~ _ZN18HibernationService20_startOperationGatedEv.cold.2 : 52 -> 56
~ _ZN18HibernationService20_startOperationGatedEv.cold.3 : 52 -> 56
~ _ZN18HibernationService18_endOperationGatedEv.cold.1 : 52 -> 56
~ _ZN18HibernationService18_endOperationGatedEv.cold.2 : 52 -> 56
~ _ZN18HibernationService18prepareToHibernateEP20sephib_wrapped_key_tP27sephib_seprom_hib_payload_t.cold.1 : 52 -> 56
```
