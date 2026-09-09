## com.apple.driver.usb.AppleUSBVHCICommonRSM

> `com.apple.driver.usb.AppleUSBVHCICommonRSM`

```diff

 1617.0.12.0.0
   __TEXT.__cstring: 0x13f8
   __TEXT.__os_log: 0x7f4
-  __TEXT_EXEC.__text: 0x537c
+  __TEXT_EXEC.__text: 0x545c
   __TEXT_EXEC.__auth_stubs: 0x1e0
   __DATA.__data: 0xc8
   __DATA.__common: 0x88
Functions:
~ __ZN26AppleUSBVHCIRSMBufferQueue9MetaClassC1Ev : 72 -> 76
~ __ZN26AppleUSBVHCIRSMBufferQueueC2EPK11OSMetaClass : 52 -> 56
~ __ZN26AppleUSBVHCIRSMBufferQueueC1EPK11OSMetaClass : 52 -> 56
~ __ZN26AppleUSBVHCIRSMBufferQueueD0Ev : 68 -> 72
~ __ZN26AppleUSBVHCIRSMBufferQueue9MetaClassC2Ev : 72 -> 76
~ __ZNK26AppleUSBVHCIRSMBufferQueue9MetaClass5allocEv : 104 -> 108
~ __ZN26AppleUSBVHCIRSMBufferQueueC1Ev : 88 -> 92
~ __ZN26AppleUSBVHCIRSMBufferQueueC2Ev : 88 -> 92
~ __ZN26AppleUSBVHCIRSMBufferQueue14withParametersEN23AppleUSBVHCIBufferQueue16tBufferQueueRoleEP12IORSMChannelPKN15StandardUSBVHCI11VHCIMessageEP22IOInterruptEventSource : 252 -> 256
~ __ZN26AppleUSBVHCIRSMBufferQueue18initWithParametersEN23AppleUSBVHCIBufferQueue16tBufferQueueRoleEP12IORSMChannelPKN15StandardUSBVHCI11VHCIMessageEP22IOInterruptEventSource : 596 -> 600
~ __ZN26AppleUSBVHCIRSMBufferQueue4freeEv : 468 -> 472
~ __ZN26AppleUSBVHCIRSMBufferQueue5closeEv : 352 -> 356
~ __ZN26AppleUSBVHCIRSMBufferQueue14transferBufferEP18IOMemoryDescriptoryyj : 1632 -> 1636
~ __ZN26AppleUSBVHCIRSMBufferQueue13cancelBuffersEv : 1052 -> 1056
~ __ZN26AppleUSBVHCIRSMBufferQueue12getNextEventEv : 3088 -> 3092
~ __ZN26AppleUSBVHCIRSMBufferQueue29registerPullReceiveDataActionEPFvP8OSObjectPS_ES1_ : 168 -> 172
~ __ZN26AppleUSBVHCIRSMBufferQueue11receiveDataEP22IORSMReceiveQueueEntry : 400 -> 404
~ __ZN26AppleUSBVHCIRSMBufferQueue13outCompletionEPP18IOMemoryDescriptori : 760 -> 764
~ _GLOBAL__sub_I_AppleUSBVHCIRSMBufferQueue.cpp : 80 -> 84
~ __ZN27AppleUSBVHCIRSMMessageQueue9MetaClassC1Ev : 72 -> 76
~ __ZN27AppleUSBVHCIRSMMessageQueueC2EPK11OSMetaClass : 52 -> 56
~ __ZN27AppleUSBVHCIRSMMessageQueueC1EPK11OSMetaClass : 52 -> 56
~ __ZN27AppleUSBVHCIRSMMessageQueueD0Ev : 68 -> 72
~ __ZN27AppleUSBVHCIRSMMessageQueue9MetaClassC2Ev : 72 -> 76
~ __ZNK27AppleUSBVHCIRSMMessageQueue9MetaClass5allocEv : 104 -> 108
~ __ZN27AppleUSBVHCIRSMMessageQueueC1Ev : 88 -> 92
~ __ZN27AppleUSBVHCIRSMMessageQueueC2Ev : 88 -> 92
~ __ZN27AppleUSBVHCIRSMMessageQueue14withParametersEP12IORSMChannelhP22IOInterruptEventSource : 244 -> 248
~ __ZN27AppleUSBVHCIRSMMessageQueue18initWithParametersEP12IORSMChannelhP22IOInterruptEventSource : 264 -> 268
~ __ZN27AppleUSBVHCIRSMMessageQueue4freeEv : 228 -> 232
~ __ZN27AppleUSBVHCIRSMMessageQueue7disableEv : 1604 -> 1608
~ __ZN27AppleUSBVHCIRSMMessageQueue11sendMessageEPKN15StandardUSBVHCI11VHCIMessageEj : 3004 -> 3008
~ __ZN27AppleUSBVHCIRSMMessageQueue18processCompletionsEv : 804 -> 808
~ __ZN27AppleUSBVHCIRSMMessageQueue10completionEPN24AppleUSBVHCIMessageQueue14tMessageRecordEi : 1084 -> 1088
~ _GLOBAL__sub_I_AppleUSBVHCIRSMMessageQueue.cpp : 80 -> 84
~ __ZN25AppleUSBVHCIRSMEventQueue9MetaClassC1Ev : 72 -> 76
~ __ZN25AppleUSBVHCIRSMEventQueueC2EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleUSBVHCIRSMEventQueueC1EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleUSBVHCIRSMEventQueueD0Ev : 68 -> 72
~ __ZN25AppleUSBVHCIRSMEventQueue9MetaClassC2Ev : 72 -> 76
~ __ZNK25AppleUSBVHCIRSMEventQueue9MetaClass5allocEv : 104 -> 108
~ __ZN25AppleUSBVHCIRSMEventQueueC1Ev : 88 -> 92
~ __ZN25AppleUSBVHCIRSMEventQueueC2Ev : 88 -> 92
~ __ZN25AppleUSBVHCIRSMEventQueue14withParametersEh : 220 -> 224
~ __ZN25AppleUSBVHCIRSMEventQueue18initWithParametersEh : 68 -> 72
~ __ZN25AppleUSBVHCIRSMEventQueue7disableEv : 464 -> 468
~ __ZN25AppleUSBVHCIRSMEventQueue12receiveEventEPKN15StandardUSBVHCI11VHCIMessageE : 1184 -> 1188
~ __ZN25AppleUSBVHCIRSMEventQueue12getNextEventEv : 400 -> 404
~ _GLOBAL__sub_I_AppleUSBVHCIRSMEventQueue.cpp : 80 -> 84
~ _ZN26AppleUSBVHCIRSMBufferQueue4freeEv.cold.1 : 24 -> 28
~ _ZN26AppleUSBVHCIRSMBufferQueue12getNextEventEv.cold.1 : 24 -> 28
~ _ZN26AppleUSBVHCIRSMBufferQueue12getNextEventEv.cold.2 : 24 -> 28
~ _ZN26AppleUSBVHCIRSMBufferQueue13outCompletionEPP18IOMemoryDescriptori.cold.1 : 24 -> 28
~ _ZN27AppleUSBVHCIRSMMessageQueue11sendMessageEPKN15StandardUSBVHCI11VHCIMessageEj.cold.1 : 24 -> 28
~ _ZN27AppleUSBVHCIRSMMessageQueue10completionEPN24AppleUSBVHCIMessageQueue14tMessageRecordEi.cold.1 : 24 -> 28
~ _ZN27AppleUSBVHCIRSMMessageQueue10completionEPN24AppleUSBVHCIMessageQueue14tMessageRecordEi.cold.2 : 24 -> 28
```
