## libATCommandStudioDynamic.dylib

> `/usr/lib/libATCommandStudioDynamic.dylib`

```diff

 2124.1.1.0.0
-  __TEXT.__text: 0x35f0c
+  __TEXT.__text: 0x360d0
   __TEXT.__init_offsets: 0x10
   __TEXT.__gcc_except_tab: 0x3e10
   __TEXT.__cstring: 0x3bc0
Functions:
~ __ZN9ATCSTimer14MemberCallbackI12ATCSDPCQueueE6invokeEv : 40 -> 44
~ __ZNSt3__15dequeIPN12ATCSDPCQueue8CallbackENS_9allocatorIS3_EEE19__add_back_capacityEv : 468 -> 472
~ __ZNSt3__114__split_bufferIPPN12ATCSDPCQueue8CallbackENS_9allocatorIS4_EEE12emplace_backIJRS4_EEEvDpOT_ : 256 -> 260
~ __ZNSt3__114__split_bufferIPPN12ATCSDPCQueue8CallbackERNS_9allocatorIS4_EEE12emplace_backIJS4_EEEvDpOT_ : 256 -> 260
~ __ZN3qmi16TransactionQueue5State9stop_syncEv : 524 -> 548
~ __ZN3qmi16TransactionQueue5State24findSentTransaction_syncEt : 264 -> 272
~ __ZN3qmi16TransactionQueue5State22createTransaction_syncERN5boost9ptr_dequeINS_11TransactionENS2_20heap_clone_allocatorENSt3__19allocatorIPvEEEERKNS6_10shared_ptrINS_17SerializedMessageEEENS6_6chrono8durationIxNS6_5ratioILl1ELl1000EEEEERKN8dispatch5blockIU13block_pointerFvRKNS_12ResponseBaseEEEE : 224 -> 232
~ __ZN3qmi16TransactionQueue5State19sendIfPossible_syncEv : 188 -> 204
~ __ZN3qmi16TransactionQueue5State10start_syncEv : 212 -> 236
~ __ZN5boost20ptr_sequence_adapterIN3qmi11TransactionENSt3__15dequeIPvNS3_9allocatorIS5_EEEENS_20heap_clone_allocatorEE4backEv : 124 -> 128
~ __ZNK3qmi16TransactionQueue5State14dumpState_syncEv : 800 -> 808
~ __ZN5boost20ptr_container_detail24reversible_ptr_containerINS0_15sequence_configIN3qmi11TransactionENSt3__15dequeIPvNS5_9allocatorIS7_EEEEEENS_20heap_clone_allocatorEE10remove_allEv : 140 -> 148
~ __ZNSt3__15dequeIPvNS_9allocatorIS1_EEE19__add_back_capacityEv : 468 -> 472
~ __ZNSt3__114__split_bufferIPPvNS_9allocatorIS2_EEE12emplace_backIJRS2_EEEvDpOT_ : 264 -> 268
~ __ZNSt3__114__split_bufferIPPvRNS_9allocatorIS2_EEE12emplace_backIJS2_EEEvDpOT_ : 264 -> 268
~ __ZNSt3__15dequeIPvNS_9allocatorIS1_EEE5eraseENS_16__deque_iteratorIS1_PKS1_RS6_PKS7_lLl512EEE : 512 -> 548
~ __ZNKSt3__116__deque_iteratorIPvPS1_RS1_PS2_lLl512EEplB9nqe220106El : 100 -> 108
~ __ZNKSt3__120__move_backward_implINS_17_ClassicAlgPolicyEEclB9nqe220106IPPvNS_16__deque_iteratorIS4_S5_RS4_PS5_lLl512EEELi0EEENS_4pairIT_T0_EESB_SB_SC_ : 244 -> 248
~ __ZNSt3__15dequeIPvNS_9allocatorIS1_EEE5eraseENS_16__deque_iteratorIS1_PKS1_RS6_PKS7_lLl512EEESB_ : 560 -> 584
~ __ZNSt3__15dequeIPvNS_9allocatorIS1_EEE22__insert_bidirectionalB9nqe220106INS_16__deque_iteratorIS1_PS1_RS1_PS7_lLl512EEEEESA_NS6_IS1_PKS1_RSB_PKSC_lLl512EEET_SH_m : 1408 -> 1492
~ __ZNSt3__15dequeIPvNS_9allocatorIS1_EEE20__add_front_capacityEm : 800 -> 804
~ __ZNSt3__15dequeIPvNS_9allocatorIS1_EEE19__add_back_capacityEm : 780 -> 784
~ __ZNKSt3__116__deque_iteratorIPvPS1_RS1_PS2_lLl512EEmiB9nqe220106El : 104 -> 112
~ __ZNSt3__15dequeIPvNS_9allocatorIS1_EEE9__emplaceIJRKS1_EEENS_16__deque_iteratorIS1_PS1_RS1_PS9_lLl512EEENS8_IS1_PS6_S7_PKSD_lLl512EEEDpOT_ : 872 -> 912
~ __ZNSt3__15dequeIPvNS_9allocatorIS1_EEE20__add_front_capacityEv : 572 -> 576
~ __ZNSt3__14prevB9nqe220106INS_16__deque_iteratorIPvPS2_RS2_PS3_lLl512EEELi0EEET_S7_ : 84 -> 80
~ __ZN4QMux5State11remove_syncERKNSt3__110shared_ptrIN3qmi15QMuxClientIfaceEEE : 692 -> 696
~ __ZNSt3__15dequeI13QMuxQueueItemNS_9allocatorIS1_EEE5eraseENS_16__deque_iteratorIS1_PKS1_RS6_PKS7_lLl170EEESB_ : 816 -> 808
~ __ZNSt3__15dequeI13QMuxQueueItemNS_9allocatorIS1_EEE19__add_back_capacityEv : 468 -> 472
~ __ZNSt3__114__split_bufferIP13QMuxQueueItemNS_9allocatorIS2_EEE12emplace_backIJRS2_EEEvDpOT_ : 256 -> 260
~ __ZNSt3__114__split_bufferIP13QMuxQueueItemRNS_9allocatorIS2_EEE12emplace_backIJS2_EEEvDpOT_ : 256 -> 260
~ __ZN3qmi11ClientProxy5State37sendInternalErrorResponseForTxId_syncEti : 280 -> 288
~ __ZN3qmi11ClientProxy5State22cancelAllMessages_syncEv : 896 -> 920
~ __ZN3qmi11ClientProxy5State19handleResponse_syncENS_11buffer_viewEt : 600 -> 608
~ __ZNSt3__15dequeIN3qmi11ClientProxy5State11TransactionENS_9allocatorIS4_EEE5eraseENS_16__deque_iteratorIS4_PKS4_RS9_PKSA_lLl128EEE : 528 -> 564
~ __ZN3qmi11ClientProxy5State22handleSentMessage_syncEt : 388 -> 396
~ __ZNK3qmi11ClientProxy5State20getTxQueueState_syncEv : 684 -> 688
~ __ZNSt3__15dequeIN3qmi11ClientProxy5State11TransactionENS_9allocatorIS4_EEED2B9nqe220106Ev : 304 -> 308
~ __ZNSt3__15dequeIN3qmi11ClientProxy5State11TransactionENS_9allocatorIS4_EEE19__add_back_capacityEv : 468 -> 472
~ __ZNKSt3__116__deque_iteratorIN3qmi11ClientProxy5State11TransactionEPS4_RS4_PS5_lLl128EEplB9nqe220106El : 100 -> 108
```
