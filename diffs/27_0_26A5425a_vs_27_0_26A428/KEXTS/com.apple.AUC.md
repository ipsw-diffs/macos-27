## com.apple.AUC

> `com.apple.AUC`

```diff

   __TEXT.__cstring: 0xd88
   __TEXT.__os_log: 0x184c
   __TEXT.__const: 0x20
-  __TEXT_EXEC.__text: 0x7d48
+  __TEXT_EXEC.__text: 0x7f84
   __TEXT_EXEC.__auth_stubs: 0x380
   __DATA.__data: 0xd1
   __DATA.__common: 0xd8
Functions:
~ __ZN3AUC9MetaClassC1Ev : 72 -> 76
~ __ZN3AUCC2EPK11OSMetaClass : 52 -> 56
~ __ZN3AUCC1EPK11OSMetaClass : 52 -> 56
~ __ZN3AUCD0Ev : 68 -> 72
~ __ZN3AUC9MetaClassC2Ev : 72 -> 76
~ __ZNK3AUC9MetaClass5allocEv : 104 -> 108
~ __ZN3AUCC1Ev : 88 -> 92
~ __ZN3AUCC2Ev : 88 -> 92
~ __ZN3AUC26createDisplayNotificationsEv : 220 -> 224
~ __ZN3AUC25AUCVideoInterfaceMatchingE12IOAVLocation : 112 -> 116
~ __ZN3AUC21DPPluggedNotificationEPvP9IOService : 380 -> 384
~ __ZN3AUC21DPRemovedNotificationEPvP9IOService : 308 -> 312
~ __ZN3AUC5startEP9IOService : 648 -> 652
~ __ZN3AUC43protectedIOSurfaceSeenRecentlyTimer_HandlerEP8OSObjectP18IOTimerEventSource : 724 -> 728
~ __ZN3AUC4stopEP9IOService : 360 -> 364
~ __ZN3AUC4initEP12OSDictionary : 228 -> 232
~ __ZN3AUC4freeEv : 224 -> 228
~ __ZN3AUC9terminateEj : 156 -> 160
~ __ZN3AUC42protectedIOSurfaceSeenRecentlyTimer_EnableEb : 260 -> 264
~ __ZN3AUC13read_edt_dataEP9IOServicePKcjPj : 680 -> 684
~ __ZN3AUC15read_edt_stringEP9IOServicePKcjPc : 700 -> 704
~ __ZN3AUC30checkForHooverProtocolRequiredEv : 552 -> 556
~ __ZN3AUC13SetUserClientEP13AUCUserClientPj : 368 -> 372
~ __ZN3AUC16RemoveUserClientEP13AUCUserClientj : 444 -> 448
~ __ZN3AUC29HDCPGetSecureStatusForDisplayEjPjS0_S0_S0_Pb : 396 -> 400
~ __ZN3AUC22protectedIOSurfaceSeenEP18IOAVVideoInterface : 496 -> 500
~ __ZN3AUC23InterfaceForDisplayTypeE14AUCDisplayType : 272 -> 276
~ __ZN3AUC22InterfaceStatusAndTypeEP18IOAVVideoInterfacePjS2_ : 696 -> 700
~ __ZN3AUC20DisplayStatusAndTypeE14AUCDisplayTypePjS1_ : 84 -> 88
~ __ZN3AUC14DisplayCapableEy14AUCDisplayType : 424 -> 428
~ __ZN3AUC24DisplayProtectionOptionsE14AUCDisplayTypePy : 320 -> 324
~ __ZN3AUC16InterfaceCapableEP18IOAVVideoInterfaceyPb : 604 -> 608
~ __ZN3AUC26InterfaceProtectionOptionsEP18IOAVVideoInterfacePy : 244 -> 248
~ __ZN3AUC26DPPluggedNotificationAsyncEPvS0_ : 308 -> 312
~ __ZN3AUC31call_DPPluggedNotificationGatedEP9IOService : 304 -> 308
~ __ZN3AUC26DPPluggedNotificationGatedEP9IOService : 888 -> 892
~ __ZN3AUC26DPRemovedNotificationGatedEP9IOService : 776 -> 780
~ __ZN3AUC26DPRemovedNotificationAsyncEPvS0_ : 268 -> 272
~ __ZN3AUC23hdcp_send_request_gatedEPKhmP18ConnectionWatchdog : 556 -> 560
~ __ZL27auc_CreateAUPPacketCallbackP8OSObjectP6OSDataPv : 464 -> 468
~ __ZN3AUC14hdcp_get_replyEPhPm : 692 -> 696
~ __ZN3AUC34aucUpstreamConnectionStatusUpdatedEv : 104 -> 108
~ __ZN3AUC34aucUpstreamConnectionStatusChangedEv : 192 -> 196
~ __ZN3AUC33hdcp_ConnectionWatchdog_will_stopEP18ConnectionWatchdog : 124 -> 128
~ __Z6AUCLogPKcz : 184 -> 188
~ _GLOBAL__sub_I_AUC.cpp : 80 -> 84
~ __ZN13AUCUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN13AUCUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN13AUCUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN13AUCUserClientD0Ev : 68 -> 72
~ __ZN13AUCUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK13AUCUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN13AUCUserClientC1Ev : 88 -> 92
~ __ZN13AUCUserClientC2Ev : 88 -> 92
~ __ZN13AUCUserClient16_CloseUserClientEPS_PvP25IOExternalMethodArguments : 28 -> 32
~ __ZN13AUCUserClient17_IsDisplayCapableEPS_PvP25IOExternalMethodArguments : 64 -> 68
~ __ZN13AUCUserClient8withTaskEP4task : 196 -> 200
~ __ZN13AUCUserClient5startEP9IOService : 128 -> 132
~ __ZN13AUCUserClient4stopEP9IOService : 156 -> 160
~ __ZN13AUCUserClient9terminateEj : 104 -> 108
~ __ZN13AUCUserClient11clientCloseEv : 64 -> 68
~ __ZN13AUCUserClient14OpenUserClientEv : 148 -> 152
~ __ZN13AUCUserClient15CloseUserClientEv : 200 -> 204
~ __ZN13AUCUserClient19ProcessStatusChangeEv : 136 -> 140
~ __ZN13AUCUserClient16IsDisplayCapableEP34_AUCKernelIsDisplayCapableInStructP35_AUCKernelIsDisplayCapableOutStruct : 64 -> 68
~ _GLOBAL__sub_I_AUCUserClient.cpp : 80 -> 84
~ __ZN7AUCLockC2Ev : 56 -> 60
~ __ZN7AUCLockC1Ev : 56 -> 60
~ __ZN7AUCLockD2Ev : 56 -> 60
~ __ZN7AUCLockD1Ev : 56 -> 60
~ __ZN7AUCLock6createEv : 68 -> 72
~ __ZN7AUCLock6createEP7_IOLock : 52 -> 56
~ __ZN16AUCRecursiveLockC2Ev : 56 -> 60
~ __ZN16AUCRecursiveLockC1Ev : 56 -> 60
~ __ZN16AUCRecursiveLockD2Ev : 56 -> 60
~ __ZN16AUCRecursiveLockD1Ev : 56 -> 60
~ __ZN16AUCRecursiveLock6createEv : 68 -> 72
~ __ZN16AUCRecursiveLock6createEP16_IORecursiveLock : 52 -> 56
~ __ZN11AUCWorkloop9MetaClassC1Ev : 72 -> 76
~ __ZN11AUCWorkloopC2EPK11OSMetaClass : 52 -> 56
~ __ZN11AUCWorkloopC1EPK11OSMetaClass : 52 -> 56
~ __ZN11AUCWorkloopD0Ev : 68 -> 72
~ __ZN11AUCWorkloop9MetaClassC2Ev : 72 -> 76
~ __ZNK11AUCWorkloop9MetaClass5allocEv : 104 -> 108
~ __ZN11AUCWorkloopC1Ev : 88 -> 92
~ __ZN11AUCWorkloopC2Ev : 88 -> 92
~ __ZN11AUCWorkloop4initEPc : 88 -> 92
~ __ZN11AUCWorkloop6createEPc : 188 -> 192
~ __ZN11AUCWorkloop4freeEv : 132 -> 136
~ __ZN12AUCSchedulerC2EPc : 60 -> 64
~ __ZN12AUCSchedulerC1EPc : 60 -> 64
~ __ZL34DispatchDPPluggedNotificationLocalPvS_ : 84 -> 88
~ __ZL34DispatchDPRemovedNotificationLocalPvS_ : 84 -> 88
~ __ZN12AUCScheduler6createEPc : 72 -> 76
~ _GLOBAL__sub_I_AUCUtilities.cpp : 80 -> 84
~ __Z14initAUCLoggingv : 84 -> 88
~ __Z13canLogMessagej : 12 -> 24
~ __ZN24AUCAsynchronousScheduler9MetaClassC1Ev : 72 -> 76
~ __ZN24AUCAsynchronousSchedulerC2EPK11OSMetaClass : 52 -> 56
~ __ZN24AUCAsynchronousSchedulerC1EPK11OSMetaClass : 52 -> 56
~ __ZN24AUCAsynchronousSchedulerD0Ev : 68 -> 72
~ __ZN24AUCAsynchronousScheduler9MetaClassC2Ev : 72 -> 76
~ __ZNK24AUCAsynchronousScheduler9MetaClass5allocEv : 104 -> 108
~ __ZN24AUCAsynchronousSchedulerC1Ev : 88 -> 92
~ __ZN24AUCAsynchronousSchedulerC2Ev : 88 -> 92
~ __ZN24AUCAsynchronousScheduler24aucAsynchronousSchedulerEPFiPvS0_S0_S0_E : 192 -> 196
~ __ZN24AUCAsynchronousScheduler19createArgumentEntryEv : 132 -> 136
~ __ZN24AUCAsynchronousScheduler20releaseArgumentEntryEPNS_13ArgumentEntryEb : 164 -> 168
~ __ZN24AUCAsynchronousScheduler16setDefaultActionEPFiPvS0_S0_S0_E : 116 -> 120
~ __ZN24AUCAsynchronousScheduler2goEPFiPvS0_S0_S0_EPjbS0_S0_S0_S0_ : 280 -> 284
~ __ZN24AUCAsynchronousScheduler21checkAndQueueArgumentEPNS_13ArgumentEntryE : 176 -> 180
~ __ZN24AUCAsynchronousScheduler12notifyThreadEjPvS0_S0_S0_ : 260 -> 264
~ __ZN24AUCAsynchronousScheduler11abortThreadEj : 328 -> 332
~ __ZN24AUCAsynchronousScheduler10joinThreadEjj : 152 -> 156
~ __ZN24AUCAsynchronousScheduler15sleepForPointerEPvj : 128 -> 132
~ __ZN24AUCAsynchronousScheduler4initEv : 292 -> 296
~ __ZN24AUCAsynchronousScheduler20performActions_gatedEv : 608 -> 612
~ __ZN24AUCAsynchronousScheduler4freeEv : 168 -> 172
~ _GLOBAL__sub_I_AUCAsynchronousScheduler.cpp : 80 -> 84
~ __ZN18ConnectionWatchdog9MetaClassC1Ev : 72 -> 76
~ __ZN18ConnectionWatchdogC2EPK11OSMetaClass : 52 -> 56
~ __ZN18ConnectionWatchdogC1EPK11OSMetaClass : 52 -> 56
~ __ZN18ConnectionWatchdogD0Ev : 68 -> 72
~ __ZN18ConnectionWatchdog9MetaClassC2Ev : 72 -> 76
~ __ZNK18ConnectionWatchdog9MetaClass5allocEv : 104 -> 108
~ __ZN18ConnectionWatchdogC1Ev : 88 -> 92
~ __ZN18ConnectionWatchdogC2Ev : 88 -> 92
~ __ZN18ConnectionWatchdog11instantiateEP3AUC17AULUpstreamFlavor : 248 -> 252
~ __ZN18ConnectionWatchdog4initEP3AUC17AULUpstreamFlavor : 360 -> 364
~ __ZN18ConnectionWatchdog19timer_handler_gatedEPvS0_S0_ : 784 -> 788
~ __ZN18ConnectionWatchdog15startConnectionEv : 32 -> 36
~ __ZN18ConnectionWatchdog24messageTimerEnable_gatedEb : 236 -> 240
~ __ZN18ConnectionWatchdog13endConnectionEv : 180 -> 184
~ __ZN18ConnectionWatchdog27upstreamConnectionSetStatusEjbjb : 936 -> 940
~ __ZN18ConnectionWatchdog32setMessageTimerThresholdMS_gatedEj : 132 -> 136
~ __ZN18ConnectionWatchdog4freeEv : 172 -> 176
~ __ZN18ConnectionWatchdog29upstreamConnectionSendMessageEv : 500 -> 504
~ __ZN18ConnectionWatchdog17LocalAULRcvRspMsgE17AULUpstreamFlavorPhjPj : 216 -> 220
~ __ZN18ConnectionWatchdog28upstreamConnectionGetMessageEv : 436 -> 440
~ __ZN18ConnectionWatchdog39upstreamConnectionGetStatusFromAULFlagsEjPjPb : 968 -> 972
~ _GLOBAL__sub_I_ConnectionWatchdog.cpp : 80 -> 84
```
