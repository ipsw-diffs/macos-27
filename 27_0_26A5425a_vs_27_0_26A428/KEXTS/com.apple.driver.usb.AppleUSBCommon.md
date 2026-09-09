## com.apple.driver.usb.AppleUSBCommon

> `com.apple.driver.usb.AppleUSBCommon`

```diff

   __TEXT.__cstring: 0x365
   __TEXT.__const: 0x18
   __TEXT.__os_log: 0xef
-  __TEXT_EXEC.__text: 0x606c
+  __TEXT_EXEC.__text: 0x620c
   __TEXT_EXEC.__auth_stubs: 0x3a0
   __DATA.__data: 0xc8
   __DATA.__common: 0x110
Functions:
~ __ZN19AppleUSBCommonDebug19getDebugLoggingMaskEPKc : 64 -> 68
~ __ZN19AppleUSBCommonDebug31getDebugLoggingMaskForMetaClassEPK11OSMetaClassS2_PKc : 384 -> 388
~ __ZN27AppleUSBCommonDebugBootArgsD1Ev : 84 -> 88
~ __ZN27AppleUSBCommonDebugBootArgsC2Ev : 240 -> 244
~ __ZN27AppleUSBCommonDebugBootArgsD2Ev : 84 -> 88
~ __ZN27AppleUSBCommonDebugBootArgsD0Ev : 100 -> 104
~ __GLOBAL__D_a : 84 -> 88
~ __ZN19AppleUSBSparseArray9MetaClassC1Ev : 72 -> 76
~ __ZN19AppleUSBSparseArrayC2EPK11OSMetaClass : 52 -> 56
~ __ZN19AppleUSBSparseArrayC1EPK11OSMetaClass : 52 -> 56
~ __ZN19AppleUSBSparseArrayD0Ev : 68 -> 72
~ __ZN19AppleUSBSparseArray9MetaClassC2Ev : 72 -> 76
~ __ZNK19AppleUSBSparseArray9MetaClass5allocEv : 104 -> 108
~ __ZN19AppleUSBSparseArrayC1Ev : 88 -> 92
~ __ZN19AppleUSBSparseArrayC2Ev : 88 -> 92
~ __ZN19AppleUSBSparseArray12withCapacityEjj : 228 -> 232
~ __ZN19AppleUSBSparseArray16initWithCapacityEjj : 112 -> 116
~ __ZN19AppleUSBSparseArray4freeEv : 136 -> 140
~ __ZN19AppleUSBSparseArray9setObjectEP15OSMetaClassBaseRj : 328 -> 332
~ __ZN19AppleUSBSparseArray13replaceObjectEP15OSMetaClassBasej : 204 -> 208
~ __ZN19AppleUSBSparseArray14ensureCapacityEj : 156 -> 160
~ __ZN19AppleUSBSparseArray15flushCollectionEv : 112 -> 116
~ _GLOBAL__sub_I_AppleUSBSparseArray.cpp : 80 -> 84
~ __ZN19AppleUSBRequestPool9MetaClassC1Ev : 72 -> 76
~ __ZN19AppleUSBRequestPoolC2EPK11OSMetaClass : 52 -> 56
~ __ZN19AppleUSBRequestPool9MetaClassC2Ev : 72 -> 76
~ __ZN19AppleUSBRequestPool4stopEv : 352 -> 356
~ __ZN19AppleUSBRequestPool4freeEv : 216 -> 220
~ __ZN19AppleUSBRequestPool13returnCommandEP9IOCommand : 156 -> 160
~ __ZN19AppleUSBRequestPool18gatedReturnCommandEP9IOCommand : 96 -> 100
~ __ZN19AppleUSBRequestPool10getCommandEb : 140 -> 144
~ __ZN19AppleUSBRequestPool15gatedGetCommandEPP9IOCommandb : 160 -> 164
~ __ZN19AppleUSBRequestPool13getCopyBufferEv : 252 -> 256
~ ____ZN19AppleUSBRequestPool13getCopyBufferEv_block_invoke : 336 -> 340
~ ____ZN19AppleUSBRequestPool16returnCopyBufferEP24IOBufferMemoryDescriptor_block_invoke : 124 -> 128
~ __ZN19AppleUSBRequestPool13getDMACommandEv : 208 -> 212
~ ____ZN19AppleUSBRequestPool16returnDMACommandEP12IODMACommand_block_invoke : 412 -> 416
~ __ZN15AppleUSBRequest9MetaClassC1Ev : 72 -> 76
~ __ZN15AppleUSBRequestC2EPK11OSMetaClass : 52 -> 56
~ __ZN15AppleUSBRequestC1EPK11OSMetaClass : 52 -> 56
~ __ZN15AppleUSBRequestD0Ev : 68 -> 72
~ __ZN15AppleUSBRequest9MetaClassC2Ev : 72 -> 76
~ __ZN15AppleUSBRequest12initWithPoolEP19AppleUSBRequestPool : 116 -> 120
~ __ZN15AppleUSBRequest4freeEv : 156 -> 160
~ __ZN15AppleUSBRequest14setNextRequestEPS_ : 156 -> 160
~ __ZN15AppleUSBRequest8completeEv : 168 -> 172
~ __ZN15AppleUSBRequest6cancelEv : 148 -> 152
~ _GLOBAL__sub_I_AppleUSBRequest.cpp : 140 -> 144
~ __GLOBAL__D_a : 56 -> 60
~ __ZN24AppleUSBRequestCompleter9MetaClassC1Ev : 72 -> 76
~ __ZN24AppleUSBRequestCompleterC2EPK11OSMetaClass : 52 -> 56
~ __ZN24AppleUSBRequestCompleterC1EPK11OSMetaClass : 52 -> 56
~ __ZN24AppleUSBRequestCompleterD0Ev : 68 -> 72
~ __ZN24AppleUSBRequestCompleter9MetaClassC2Ev : 72 -> 76
~ __ZNK24AppleUSBRequestCompleter9MetaClass5allocEv : 104 -> 108
~ __ZN24AppleUSBRequestCompleterC1Ev : 88 -> 92
~ __ZN24AppleUSBRequestCompleterC2Ev : 88 -> 92
~ __ZN24AppleUSBRequestCompleter16requestCompleterEP8OSObjectP10IOWorkLoop : 232 -> 236
~ __ZN24AppleUSBRequestCompleter4initEP8OSObjectP10IOWorkLoopPFvS1_zE : 564 -> 568
~ __ZN24AppleUSBRequestCompleter4stopEv : 276 -> 280
~ __ZN24AppleUSBRequestCompleter4freeEv : 568 -> 572
~ __ZN24AppleUSBRequestCompleter8onThreadEv : 276 -> 280
~ __ZN24AppleUSBRequestCompleter13onThreadGatedERb : 360 -> 364
~ __ZN24AppleUSBRequestCompleter14enqueueRequestEP15AppleUSBRequest : 1184 -> 1188
~ __ZN24AppleUSBRequestCompleter41completeSynchronousRequestQueueThreadCallEP11thread_call : 324 -> 328
~ __ZN24AppleUSBRequestCompleter46completeSynchronousRequestQueueThreadCallGatedEv : 184 -> 188
~ __ZN24AppleUSBRequestCompleter12checkForWorkEv : 496 -> 500
~ __ZN24AppleUSBRequestCompleter20completeRequestQueueEP11queue_entry : 2104 -> 2108
~ __ZN24AppleUSBRequestCompleter25completeRequestThreadCallEPNS_20tRequestCompleteDataE : 348 -> 352
~ __ZN24AppleUSBRequestCompleter30completeRequestThreadCallGatedEP15AppleUSBRequest : 424 -> 428
~ _GLOBAL__sub_I_AppleUSBRequestCompleter.cpp : 80 -> 84
~ __ZN18AppleUSBDescriptor9MetaClassC1Ev : 72 -> 76
~ __ZN18AppleUSBDescriptorC2EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleUSBDescriptorC1EPK11OSMetaClass : 52 -> 56
~ __ZN18AppleUSBDescriptorD0Ev : 68 -> 72
~ __ZN18AppleUSBDescriptor9MetaClassC2Ev : 72 -> 76
~ __ZNK18AppleUSBDescriptor9MetaClass5allocEv : 104 -> 108
~ __ZN18AppleUSBDescriptorC1Ev : 88 -> 92
~ __ZN18AppleUSBDescriptorC2Ev : 88 -> 92
~ __ZN18AppleUSBDescriptor14withDescriptorEPKN11StandardUSB10DescriptorEtht : 252 -> 256
~ __ZN18AppleUSBDescriptor18initWithDescriptorEPKN11StandardUSB10DescriptorEtht : 212 -> 216
~ __ZN18AppleUSBDescriptor4freeEv : 104 -> 108
~ __ZN23AppleUSBDescriptorCache9MetaClassC1Ev : 72 -> 76
~ __ZN23AppleUSBDescriptorCacheC2EPK11OSMetaClass : 52 -> 56
~ __ZN23AppleUSBDescriptorCacheC1EPK11OSMetaClass : 52 -> 56
~ __ZN23AppleUSBDescriptorCacheD0Ev : 68 -> 72
~ __ZN23AppleUSBDescriptorCache9MetaClassC2Ev : 72 -> 76
~ __ZNK23AppleUSBDescriptorCache9MetaClass5allocEv : 104 -> 108
~ __ZN23AppleUSBDescriptorCacheC1Ev : 88 -> 92
~ __ZN23AppleUSBDescriptorCacheC2Ev : 88 -> 92
~ __ZN23AppleUSBDescriptorCache15descriptorCacheEv : 176 -> 180
~ __ZN23AppleUSBDescriptorCache4initEv : 100 -> 104
~ __ZN23AppleUSBDescriptorCache4freeEv : 240 -> 244
~ __ZN23AppleUSBDescriptorCache13setDescriptorEPKN11StandardUSB10DescriptorEtht : 776 -> 780
~ __ZN23AppleUSBDescriptorCache13getDescriptorEhRtht : 428 -> 432
~ __ZN23AppleUSBDescriptorCache16removeDescriptorEhht : 532 -> 536
~ _GLOBAL__sub_I_AppleUSBDescriptorCache.cpp : 148 -> 152
~ __GLOBAL__D_a : 56 -> 60
~ ___ZN19AppleUSBRequestPool16returnDMACommandEP12IODMACommand_block_invoke.cold.1 : 44 -> 48
~ _ZN24AppleUSBRequestCompleter4freeEv.cold.1 : 24 -> 28
~ _ZN24AppleUSBRequestCompleter14enqueueRequestEP15AppleUSBRequest.cold.1 : 24 -> 28
~ _ZN24AppleUSBRequestCompleter14enqueueRequestEP15AppleUSBRequest.cold.2 : 24 -> 28
~ _ZN24AppleUSBRequestCompleter12checkForWorkEv.cold.1 : 24 -> 28
~ _ZN24AppleUSBRequestCompleter20completeRequestQueueEP11queue_entry.cold.1 : 24 -> 28
```
