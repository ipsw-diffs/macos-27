## com.apple.iokit.AppleSEPGenericTransfer

> `com.apple.iokit.AppleSEPGenericTransfer`

```diff

 34.0.0.0.0
   __TEXT.__cstring: 0x9a4
   __TEXT.__os_log: 0x3e7
-  __TEXT_EXEC.__text: 0x487c
+  __TEXT_EXEC.__text: 0x49a8
   __TEXT_EXEC.__auth_stubs: 0x260
   __DATA.__data: 0xc8
   __DATA.__common: 0x88
Functions:
~ _gt_clean_transfer : 144 -> 148
~ _gt_send_transact_message : 208 -> 212
~ _gt_write_first_packet : 348 -> 352
~ _gt_write_next_packet : 424 -> 428
~ _gt_read_first_packet : 900 -> 904
~ _gt_read_next_packet : 664 -> 668
~ _gt_read_error : 188 -> 192
~ _gt_handle_generic_transaction : 540 -> 544
~ __ZN21GTOutputBufferGenericD2Ev : 60 -> 64
~ __ZN21GTOutputBufferGeneric7cleanupEv : 56 -> 60
~ __ZN21GTOutputBufferGenericD1Ev : 60 -> 64
~ __ZN21GTOutputBufferGeneric7setDataEPvm : 80 -> 84
~ __ZN23AppleSEPGenericTransfer9MetaClassC1Ev : 72 -> 76
~ __ZN23AppleSEPGenericTransferC2EPK11OSMetaClass : 68 -> 72
~ __ZN23AppleSEPGenericTransferC1EPK11OSMetaClass : 68 -> 72
~ __ZN23AppleSEPGenericTransferD2Ev : 280 -> 284
~ __ZN23AppleSEPGenericTransferD1Ev : 280 -> 284
~ __ZN23AppleSEPGenericTransferD0Ev : 68 -> 72
~ __ZN23AppleSEPGenericTransfer9MetaClassC2Ev : 72 -> 76
~ __ZNK23AppleSEPGenericTransfer9MetaClass5allocEv : 52 -> 56
~ __ZN23AppleSEPGenericTransferC2Ev : 104 -> 108
~ __ZN23AppleSEPGenericTransfer4initEP9IOServicePFvP8OSObjectPvS4_Ejjj : 964 -> 968
~ __ZN23AppleSEPGenericTransfer4freeEv : 224 -> 228
~ __ZN23AppleSEPGenericTransfer7disableEv : 236 -> 240
~ __ZN23AppleSEPGenericTransfer6enableEv : 156 -> 160
~ __ZN23AppleSEPGenericTransfer26enableEndpointContinuationEP8OSObjecti : 124 -> 128
~ __ZN23AppleSEPGenericTransfer14enableEndpointEv : 2456 -> 2460
~ __ZN23AppleSEPGenericTransfer11getEndpointEv : 660 -> 664
~ __ZN23AppleSEPGenericTransfer17sepMessageHandlerEPvS0_U13block_pointerFiyE : 520 -> 524
~ __ZN23AppleSEPGenericTransfer14sendRawMessageEy : 396 -> 400
~ __ZN23AppleSEPGenericTransfer11sendMessageEhti : 128 -> 132
~ __ZN23AppleSEPGenericTransfer8transactEjPKvmPPvPmj : 1176 -> 1180
~ __ZN23AppleSEPGenericTransfer14transactToIOMDEjPKvmP18IOMemoryDescriptorPjj : 936 -> 940
~ __ZN23AppleSEPGenericTransfer25setTransferStatusCallbackEU13block_pointerFvNS_28gt_transfer_status_message_tEE : 140 -> 144
~ __ZN23AppleSEPGenericTransfer23setTransferDataCallbackEU13block_pointerFvyPKhmbE : 140 -> 144
~ _gt_transfer_reading_complete : 268 -> 272
~ _gt_transfer_error : 288 -> 292
~ _gt_send_message_raw_internal : 264 -> 268
~ _gt_get_ool_buffer_size_internal : 200 -> 204
~ _gt_get_max_transaction_size_internal : 200 -> 204
~ _GLOBAL__sub_I_AppleSEPGenericTransfer.cpp : 80 -> 84
~ __ZN10GTGateLock9MetaClassC1Ev : 72 -> 76
~ __ZN10GTGateLockC2EPK11OSMetaClass : 56 -> 60
~ __ZN10GTGateLockC1EPK11OSMetaClass : 56 -> 60
~ __ZN10GTGateLockD2Ev : 120 -> 124
~ __ZN10GTGateLockD1Ev : 120 -> 124
~ __ZN10GTGateLockD0Ev : 68 -> 72
~ __ZN10GTGateLock9MetaClassC2Ev : 72 -> 76
~ __ZNK10GTGateLock9MetaClass5allocEv : 108 -> 112
~ __ZN10GTGateLockC1Ev : 92 -> 96
~ __ZN10GTGateLockC2Ev : 92 -> 96
~ __ZN10GTGateLock8withGateEP13IOCommandGate : 88 -> 92
~ __ZN10GTGateLock8withGateE11OSSharedPtrI13IOCommandGateE : 204 -> 208
~ __ZN10GTGateLock12initWithGateE11OSSharedPtrI13IOCommandGateE : 160 -> 164
~ __ZN10GTGateLock12initWithGateEP13IOCommandGate : 96 -> 100
~ __ZN10GTGateLock4lockEj : 228 -> 232
~ __ZN11GTCondition9MetaClassC1Ev : 72 -> 76
~ __ZN11GTConditionC2EPK11OSMetaClass : 56 -> 60
~ __ZN11GTConditionC1EPK11OSMetaClass : 56 -> 60
~ __ZN11GTConditionD2Ev : 120 -> 124
~ __ZN11GTConditionD1Ev : 120 -> 124
~ __ZN11GTConditionD0Ev : 68 -> 72
~ __ZN11GTCondition9MetaClassC2Ev : 72 -> 76
~ __ZNK11GTCondition9MetaClass5allocEv : 108 -> 112
~ __ZN11GTConditionC1Ev : 92 -> 96
~ __ZN11GTConditionC2Ev : 92 -> 96
~ __ZN11GTCondition8withGateEP13IOCommandGate : 88 -> 92
~ __ZN11GTCondition8withGateE11OSSharedPtrI13IOCommandGateE : 204 -> 208
~ __ZN11GTCondition12initWithGateE11OSSharedPtrI13IOCommandGateE : 160 -> 164
~ __ZN11GTCondition12initWithGateEP13IOCommandGate : 96 -> 100
~ __ZN11GTCondition4waitEj : 164 -> 168
~ _GLOBAL__sub_I_GTUtilities.cpp : 148 -> 152
~ __GLOBAL__D_a : 56 -> 60
~ _ZN21GTOutputBufferGeneric7setDataEPvm.cold.1 : 44 -> 48
~ _ZN23AppleSEPGenericTransfer11getEndpointEv.cold.1 : 100 -> 104
```
