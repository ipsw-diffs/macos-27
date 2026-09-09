## com.apple.iokit.IOBufferCopyEngineFamily

> `com.apple.iokit.IOBufferCopyEngineFamily`

```diff

 100.0.0.0.0
   __TEXT.__cstring: 0x780
   __TEXT.__const: 0x20
-  __TEXT_EXEC.__text: 0x88c0
+  __TEXT_EXEC.__text: 0x8b10
   __TEXT_EXEC.__auth_stubs: 0x3d0
   __DATA.__data: 0xc8
   __DATA.__common: 0x150
Functions:
~ __ZN18IOBufferCopyEngine9MetaClassC1Ev : 72 -> 76
~ __ZN18IOBufferCopyEngineC2EPK11OSMetaClass : 52 -> 56
~ __ZN18IOBufferCopyEngine9MetaClassC2Ev : 72 -> 76
~ __ZN18IOBufferCopyEngine20findBufferCopyEngineEv : 104 -> 108
~ __ZN18IOBufferCopyEngine5startEP9IOService : 904 -> 908
~ __ZN18IOBufferCopyEngine4stopEP9IOService : 56 -> 60
~ __ZN18IOBufferCopyEngine15registerServiceEj : 136 -> 140
~ __ZN18IOBufferCopyEngine4freeEv : 280 -> 284
~ __ZN18IOBufferCopyEngine27createCompletionMemoryQueueEP23IOBufferCopyEventSourceti : 608 -> 612
~ __ZN18IOBufferCopyEngine28destroyCompletionMemoryQueueEP23IOBufferCopyEventSource : 500 -> 504
~ __ZN18IOBufferCopyEngine27createSubmissionMemoryQueueEP27IOBufferCopySubmissionQueuePv : 620 -> 624
~ __ZN18IOBufferCopyEngine28destroySubmissionMemoryQueueEP27IOBufferCopySubmissionQueue : 224 -> 228
~ __ZN18IOBufferCopyEngine17notifyMemoryQueueEPv : 136 -> 140
~ __ZN18IOBufferCopyEngine7prepareEPvP18IOMemoryDescriptorj : 1272 -> 1276
~ __ZN18IOBufferCopyEngine8completeEP22IOBufferCopyDMACommand : 308 -> 312
~ __ZN18IOBufferCopyEngine9configureEjitP8IOMapper : 736 -> 740
~ __ZN24IOBufferCopyCommandQueue14withCompletionEPFvP8OSObjectP27IOBufferCopySubmissionQueueEt : 180 -> 184
~ __ZN18IOBufferCopyEngine8shutdownEv : 400 -> 404
~ __ZN18IOBufferCopyEngine30handleCompletionQueueInterruptEi : 248 -> 252
~ __ZNK18IOBufferCopyEngine11isAvailableEv : 40 -> 44
~ __ZN18IOBufferCopyEngine7disableEv : 292 -> 296
~ __ZN18IOBufferCopyEngine12disableGatedEv : 204 -> 208
~ __ZN18IOBufferCopyEngine6enableEv : 292 -> 296
~ __ZN18IOBufferCopyEngine11enableGatedEv : 36 -> 40
~ __ZN18IOBufferCopyEngine18_requestQueueIndexEv : 124 -> 128
~ __ZN18IOBufferCopyEngine17_returnQueueIndexEt : 112 -> 116
~ __ZN18IOBufferCopyEngine18_createMemoryQueueEtj : 700 -> 704
~ __ZN18IOBufferCopyEngine19_destroyMemoryQueueEPv : 188 -> 192
~ __ZN18IOBufferCopyEngine18_requestDMACommandEPv : 212 -> 216
~ __ZN22IOBufferCopyDMACommand10withMapperEP8IOMapperh : 180 -> 184
~ __ZN18IOBufferCopyEngine25_registerMemoryQueueGatedEPNS_24MemoryQueueConfigurationEPK8OSSymbolj : 340 -> 344
~ __ZN18IOBufferCopyEngine27_unregisterMemoryQueueGatedEPv : 328 -> 332
~ __ZN18IOBufferCopyEngine22_flushMemoryQueueGatedEPv : 316 -> 320
~ __ZN18IOBufferCopyEngine28_setMemoryQueuePropertyGatedEPvjy : 340 -> 344
~ __ZN18IOBufferCopyEngine16_commandCompleteEP24IOBufferCopyCommandQueue : 424 -> 428
~ __ZN22IOBufferCopyDMACommand9MetaClassC1Ev : 72 -> 76
~ __ZN22IOBufferCopyDMACommandC2EPK11OSMetaClass : 52 -> 56
~ __ZN22IOBufferCopyDMACommandC1EPK11OSMetaClass : 52 -> 56
~ __ZN22IOBufferCopyDMACommandD0Ev : 68 -> 72
~ __ZN22IOBufferCopyDMACommand9MetaClassC2Ev : 72 -> 76
~ __ZNK22IOBufferCopyDMACommand9MetaClass5allocEv : 104 -> 108
~ __ZN22IOBufferCopyDMACommandC1Ev : 88 -> 92
~ __ZN22IOBufferCopyDMACommandC2Ev : 88 -> 92
~ __ZN22IOBufferCopyDMACommand14initWithMapperEP8IOMapperh : 100 -> 104
~ __ZNK22IOBufferCopyDMACommand19getBufferParametersEPyS0_S0_S0_yy : 288 -> 292
~ __ZN22IOBufferCopyDMACommand15generateAddressEv : 236 -> 240
~ __ZN22IOBufferCopyDMACommand19generateSegmentListEPS_yPv : 412 -> 416
~ __ZN24IOBufferCopyCommandQueue9MetaClassC1Ev : 72 -> 76
~ __ZN24IOBufferCopyCommandQueueC2EPK11OSMetaClass : 52 -> 56
~ __ZN24IOBufferCopyCommandQueueC1EPK11OSMetaClass : 52 -> 56
~ __ZN24IOBufferCopyCommandQueueD0Ev : 68 -> 72
~ __ZN24IOBufferCopyCommandQueue9MetaClassC2Ev : 72 -> 76
~ __ZNK24IOBufferCopyCommandQueue9MetaClass5allocEv : 104 -> 108
~ __ZN24IOBufferCopyCommandQueueC1Ev : 88 -> 92
~ __ZN24IOBufferCopyCommandQueueC2Ev : 88 -> 92
~ __ZN24IOBufferCopyCommandQueue19registerMemoryQueueEPvPN18IOBufferCopyEngine24MemoryQueueConfigurationEPK8OSSymbolj : 568 -> 572
~ __ZN24IOBufferCopyCommandQueue21unregisterMemoryQueueEPvS0_ : 428 -> 432
~ __ZN24IOBufferCopyCommandQueue16flushMemoryQueueEPvS0_ : 428 -> 432
~ __ZN24IOBufferCopyCommandQueue22setMemoryQueuePropertyEPvS0_jy : 452 -> 456
~ __ZN24IOBufferCopyCommandQueue18initWithCompletionEPFvP8OSObjectP27IOBufferCopySubmissionQueueEt : 152 -> 156
~ _GLOBAL__sub_I_IOBufferCopyEngine.cpp : 212 -> 216
~ __GLOBAL__D_a : 80 -> 84
~ __ZN34IOBufferCopyEngineUserClientBuffer9MetaClassC1Ev : 72 -> 76
~ __ZN34IOBufferCopyEngineUserClientBufferC2EPK11OSMetaClass : 60 -> 64
~ __ZN34IOBufferCopyEngineUserClientBufferC1EPK11OSMetaClass : 60 -> 64
~ __ZN34IOBufferCopyEngineUserClientBufferD0Ev : 68 -> 72
~ __ZN34IOBufferCopyEngineUserClientBuffer9MetaClassC2Ev : 72 -> 76
~ __ZNK34IOBufferCopyEngineUserClientBuffer9MetaClass5allocEv : 52 -> 56
~ __ZN34IOBufferCopyEngineUserClientBufferC2Ev : 96 -> 100
~ __ZN33IOBufferCopyEngineUserClientState9MetaClassC1Ev : 72 -> 76
~ __ZN33IOBufferCopyEngineUserClientStateC2EPK11OSMetaClass : 60 -> 64
~ __ZN33IOBufferCopyEngineUserClientStateC1EPK11OSMetaClass : 60 -> 64
~ __ZN33IOBufferCopyEngineUserClientStateD0Ev : 68 -> 72
~ __ZN33IOBufferCopyEngineUserClientState9MetaClassC2Ev : 72 -> 76
~ __ZNK33IOBufferCopyEngineUserClientState9MetaClass5allocEv : 112 -> 116
~ __ZN33IOBufferCopyEngineUserClientStateC1Ev : 96 -> 100
~ __ZN33IOBufferCopyEngineUserClientStateC2Ev : 96 -> 100
~ __ZN28IOBufferCopyEngineUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN28IOBufferCopyEngineUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN28IOBufferCopyEngineUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN28IOBufferCopyEngineUserClientD0Ev : 68 -> 72
~ __ZN28IOBufferCopyEngineUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK28IOBufferCopyEngineUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN28IOBufferCopyEngineUserClientC1Ev : 88 -> 92
~ __ZN28IOBufferCopyEngineUserClientC2Ev : 88 -> 92
~ __ZN28IOBufferCopyEngineUserClient12initWithTaskEP4taskPvj : 300 -> 304
~ __ZN33IOBufferCopyEngineUserClientState12withWorkLoopEP10IOWorkLoop : 164 -> 168
~ __ZN28IOBufferCopyEngineUserClient11clientCloseEv : 96 -> 100
~ __ZN28IOBufferCopyEngineUserClient4freeEv : 192 -> 196
~ __ZN28IOBufferCopyEngineUserClient21createSubmissionQueueERNS_15MethodArgumentsE : 332 -> 336
~ __ZN28IOBufferCopyEngineUserClient12submitBufferERNS_15MethodArgumentsE : 196 -> 200
~ __ZN34IOBufferCopyEngineUserClientBuffer11withOptionsEyyyP4task : 172 -> 176
~ __ZN28IOBufferCopyEngineUserClient14completeBufferERNS_15MethodArgumentsE : 420 -> 424
~ __ZN28IOBufferCopyEngineUserClient29createSubmissionQueueDispatchEP8OSObjectPvP25IOExternalMethodArguments : 128 -> 132
~ __ZN28IOBufferCopyEngineUserClient28flushSubmissionQueueDispatchEP8OSObjectPvP25IOExternalMethodArguments : 168 -> 172
~ __ZN28IOBufferCopyEngineUserClient20submitBufferDispatchEP8OSObjectPvP25IOExternalMethodArguments : 128 -> 132
~ __ZN28IOBufferCopyEngineUserClient22completeBufferDispatchEP8OSObjectPvP25IOExternalMethodArguments : 128 -> 132
~ __ZN28IOBufferCopyEngineUserClient19setPropertyDispatchEP8OSObjectPvP25IOExternalMethodArguments : 180 -> 184
~ __ZN28IOBufferCopyEngineUserClient15MethodArgumentsC2EPS_P25IOExternalMethodArguments : 232 -> 236
~ __ZNK33IOBufferCopyEngineUserClientState12queueForNameEPK8OSSymbol : 88 -> 92
~ __ZN28IOBufferCopyEngineUserClient15MethodArgumentsD2Ev : 76 -> 80
~ __ZN28IOBufferCopyEngineUserClient15MethodArgumentsD1Ev : 76 -> 80
~ __ZN33IOBufferCopyEngineUserClientState16initWithWorkloopEP10IOWorkLoop : 332 -> 336
~ __ZN33IOBufferCopyEngineUserClientState17asyncCleanupThunkEPvS0_ : 172 -> 176
~ __ZN33IOBufferCopyEngineUserClientState4freeEv : 296 -> 300
~ __ZN33IOBufferCopyEngineUserClientState7cleanupEv : 880 -> 884
~ __ZN34IOBufferCopyEngineUserClientBuffer15initWithOptionsEyyyP4task : 308 -> 312
~ __ZN34IOBufferCopyEngineUserClientBuffer4freeEv : 160 -> 164
~ _GLOBAL__sub_I_IOBufferCopyEngineUserClient.cpp : 208 -> 212
~ __GLOBAL__D_a : 68 -> 72
~ __ZN23IOBufferCopyEventSource9MetaClassC1Ev : 72 -> 76
~ __ZN23IOBufferCopyEventSourceC2EPK11OSMetaClass : 52 -> 56
~ __ZN23IOBufferCopyEventSourceC1EPK11OSMetaClass : 52 -> 56
~ __ZN23IOBufferCopyEventSourceD0Ev : 68 -> 72
~ __ZN23IOBufferCopyEventSource9MetaClassC2Ev : 72 -> 76
~ __ZNK23IOBufferCopyEventSource9MetaClass5allocEv : 104 -> 108
~ __ZN23IOBufferCopyEventSourceC1Ev : 88 -> 92
~ __ZN23IOBufferCopyEventSourceC2Ev : 88 -> 92
~ __ZN23IOBufferCopyEventSource9withOwnerEP8OSObjecttiP18IOBufferCopyEngine : 172 -> 176
~ __ZN23IOBufferCopyEventSource13initWithOwnerEP8OSObjecttiP18IOBufferCopyEngine : 256 -> 260
~ __ZN23IOBufferCopyEventSource18processCompletionsEv : 92 -> 96
~ __ZN23IOBufferCopyEventSource18addSubmissionQueueEP27IOBufferCopySubmissionQueue : 332 -> 336
~ __ZN23IOBufferCopyEventSource21removeSubmissionQueueEP27IOBufferCopySubmissionQueue : 376 -> 380
~ __ZN23IOBufferCopyEventSource4freeEv : 248 -> 252
~ __ZN23IOBufferCopyEventSource12checkForWorkEv : 380 -> 384
~ __ZN23IOBufferCopyEventSource22checkCompletionPendingEv : 88 -> 92
~ __ZN23IOBufferCopyEventSource23_processCompletionQueueEv : 380 -> 384
~ __ZN27IOBufferCopySubmissionQueue9MetaClassC1Ev : 72 -> 76
~ __ZN27IOBufferCopySubmissionQueueC2EPK11OSMetaClass : 52 -> 56
~ __ZN27IOBufferCopySubmissionQueueC1EPK11OSMetaClass : 52 -> 56
~ __ZN27IOBufferCopySubmissionQueueD0Ev : 68 -> 72
~ __ZN27IOBufferCopySubmissionQueue9MetaClassC2Ev : 72 -> 76
~ __ZNK27IOBufferCopySubmissionQueue9MetaClass5allocEv : 104 -> 108
~ __ZN27IOBufferCopySubmissionQueueC1Ev : 88 -> 92
~ __ZN27IOBufferCopySubmissionQueueC2Ev : 88 -> 92
~ __ZN27IOBufferCopySubmissionQueue14withCompletionEPFvP8OSObjectPS_EPK8OSSymboljt : 204 -> 208
~ __ZN27IOBufferCopySubmissionQueue14enqueueElementEPvP22IOBufferCopyDMACommandyy : 576 -> 580
~ __ZN27IOBufferCopySubmissionQueue14enqueueElementEPvP18IOMemoryDescriptoryy : 280 -> 284
~ __ZN27IOBufferCopySubmissionQueue18initWithCompletionEPFvP8OSObjectPS_EPK8OSSymboljt : 308 -> 312
~ __ZN27IOBufferCopySubmissionQueue4freeEv : 292 -> 296
~ __ZN27IOBufferCopySubmissionQueue14setEventSourceEP23IOBufferCopyEventSource : 148 -> 152
~ __ZN27IOBufferCopySubmissionQueue24setCompletionInformationEtiyy : 136 -> 140
~ _GLOBAL__sub_I_IOBufferCopyEventSource.cpp : 140 -> 144
~ __GLOBAL__D_a : 56 -> 60
~ _ZN33IOBufferCopyEngineUserClientState7cleanupEv.cold.1 : 84 -> 88
~ _ZN23IOBufferCopyEventSource23_processCompletionQueueEv.cold.1 : 52 -> 56
~ _ZN23IOBufferCopyEventSource23_processCompletionQueueEv.cold.2 : 52 -> 56
~ _ZN27IOBufferCopySubmissionQueue24setCompletionInformationEtiyy.cold.1 : 44 -> 48
```
