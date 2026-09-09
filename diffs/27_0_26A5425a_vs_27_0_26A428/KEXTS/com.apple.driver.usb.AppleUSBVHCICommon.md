## com.apple.driver.usb.AppleUSBVHCICommon

> `com.apple.driver.usb.AppleUSBVHCICommon`

```diff

   __TEXT.__const: 0x24
   __TEXT.__cstring: 0x91f
   __TEXT.__os_log: 0x411
-  __TEXT_EXEC.__text: 0x4100
+  __TEXT_EXEC.__text: 0x41c0
   __TEXT_EXEC.__auth_stubs: 0x1c0
   __DATA.__data: 0xc8
   __DATA.__common: 0xd8
Functions:
~ __ZN15StandardUSBVHCI26buildCreateEndpointCommandEhtPKN11StandardUSB18EndpointDescriptorEPKNS0_37SuperSpeedEndpointCompanionDescriptorEPKNS0_52SuperSpeedPlusIsochronousEndpointCompanionDescriptorE : 260 -> 264
~ __ZN22AppleUSBVHCIEventQueue9MetaClassC1Ev : 72 -> 76
~ __ZN22AppleUSBVHCIEventQueueC2EPK11OSMetaClass : 52 -> 56
~ __ZN22AppleUSBVHCIEventQueue9MetaClassC2Ev : 72 -> 76
~ __ZN22AppleUSBVHCIEventQueue4initEv : 136 -> 140
~ _GLOBAL__sub_I_AppleUSBVHCIEventQueue.cpp : 80 -> 84
~ __ZN23AppleUSBVHCIBufferQueue9MetaClassC1Ev : 72 -> 76
~ __ZN23AppleUSBVHCIBufferQueueC2EPK11OSMetaClass : 52 -> 56
~ __ZN23AppleUSBVHCIBufferQueue9MetaClassC2Ev : 72 -> 76
~ __ZN23AppleUSBVHCIBufferQueue4initEv : 132 -> 136
~ __ZN23AppleUSBVHCIBufferQueue4freeEv : 116 -> 120
~ __ZN23AppleUSBVHCIBufferQueue24registerCompletionActionEPFvP8OSObjectPvES1_S2_ : 132 -> 136
~ _GLOBAL__sub_I_AppleUSBVHCIBufferQueue.cpp : 80 -> 84
~ __ZN24AppleUSBVHCIMessageQueue9MetaClassC1Ev : 72 -> 76
~ __ZN24AppleUSBVHCIMessageQueueC2EPK11OSMetaClass : 52 -> 56
~ __ZN24AppleUSBVHCIMessageQueue9MetaClassC2Ev : 72 -> 76
~ __ZN24AppleUSBVHCIMessageQueue4initEv : 136 -> 140
~ _GLOBAL__sub_I_AppleUSBVHCIMessageQueue.cpp : 80 -> 84
~ __ZN25AppleUSBVHCITransferQueue9MetaClassC1Ev : 72 -> 76
~ __ZN25AppleUSBVHCITransferQueueC2EPK11OSMetaClass : 52 -> 56
~ __ZN25AppleUSBVHCITransferQueue9MetaClassC2Ev : 72 -> 76
~ __ZN25AppleUSBVHCITransferQueue18initWithParametersEtjPKN15StandardUSBVHCI11VHCIMessageEP23AppleUSBVHCIBufferQueueP24AppleUSBVHCIMessageQueueP10IOWorkLoop : 876 -> 880
~ __ZN25AppleUSBVHCITransferQueue4freeEv : 560 -> 564
~ __ZN25AppleUSBVHCITransferQueue11sendMessageEPN15StandardUSBVHCI11VHCIMessageE : 276 -> 280
~ __ZN25AppleUSBVHCITransferQueue24transferBufferWithStatusEP18IOMemoryDescriptoryyji : 172 -> 176
~ __ZN25AppleUSBVHCITransferQueue12getNextEventEv : 268 -> 272
~ __ZN25AppleUSBVHCITransferQueue12processEventEPKN15StandardUSBVHCI11VHCIMessageE : 316 -> 320
~ __ZN25AppleUSBVHCITransferQueue5closeEv : 452 -> 456
~ __ZN25AppleUSBVHCITransferQueue14enqueueRequestEP15AppleUSBRequest : 444 -> 448
~ __ZN25AppleUSBVHCITransferQueue12abortRequestEi : 472 -> 476
~ __ZN25AppleUSBVHCITransferQueue16abortAllRequestsEiP9IOService : 612 -> 616
~ __ZN25AppleUSBVHCITransferQueue18pollForCompletionsEj : 1008 -> 1012
~ __ZN25AppleUSBVHCITransferQueue16activateRequestsEv : 596 -> 600
~ __ZN25AppleUSBVHCITransferQueue15completeRequestEP15AppleUSBRequest : 476 -> 480
~ __ZN25AppleUSBVHCITransferQueue13setQueueStateEN15StandardUSBVHCI18tVHCIEndpointStateE : 292 -> 296
~ _GLOBAL__sub_I_AppleUSBVHCITransferQueue.cpp : 80 -> 84
~ __ZN24AppleUSBVHCICommandQueue9MetaClassC1Ev : 72 -> 76
~ __ZN24AppleUSBVHCICommandQueueC2EPK11OSMetaClass : 52 -> 56
~ __ZN24AppleUSBVHCICommandQueue9MetaClassC2Ev : 72 -> 76
~ __ZN24AppleUSBVHCICommandQueue20initWithMessageQueueEP24AppleUSBVHCIMessageQueue : 200 -> 204
~ __ZN24AppleUSBVHCICommandQueue4stopEv : 112 -> 116
~ __ZN24AppleUSBVHCICommandQueue4freeEv : 112 -> 116
~ __ZN24AppleUSBVHCICommandQueue21notifyCommandCompleteEPKN15StandardUSBVHCI11VHCIMessageE : 1312 -> 1316
~ __ZN24AppleUSBVHCICommandQueue14executeCommandEPN15StandardUSBVHCI11VHCIMessageEj : 2440 -> 2444
~ __ZN24AppleUSBVHCICommandQueue12abortCommandEPN15StandardUSBVHCI11VHCIMessageE : 1152 -> 1156
~ _GLOBAL__sub_I_AppleUSBVHCICommandQueue.cpp : 80 -> 84
~ _ZN25AppleUSBVHCITransferQueue12abortRequestEi.cold.1 : 24 -> 28
~ _ZN25AppleUSBVHCITransferQueue16abortAllRequestsEiP9IOService.cold.1 : 24 -> 28
```
