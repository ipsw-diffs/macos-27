## com.apple.driver.AppleH16ANEInterface

> `com.apple.driver.AppleH16ANEInterface`

```diff

-10.100.80.0.0
-  __TEXT.__const: 0x1250
-  __TEXT.__cstring: 0x11d70
-  __TEXT.__os_log: 0x3d587
-  __TEXT_EXEC.__text: 0x153fa4
-  __TEXT_EXEC.__auth_stubs: 0x1260
-  __DATA.__data: 0x54f0
+10.101.100.0.0
+  __TEXT.__cstring: 0x11e05
+  __TEXT.__os_log: 0x3df78
+  __TEXT.__const: 0x1240
+  __TEXT_EXEC.__text: 0x15574c
+  __TEXT_EXEC.__auth_stubs: 0x1270
+  __DATA.__data: 0x54f4
   __DATA.__common: 0x7e0
   __DATA.__bss: 0x868
   __DATA_CONST.__mod_init_func: 0x300
   __DATA_CONST.__mod_term_func: 0x138
-  __DATA_CONST.__const: 0x18ae0
-  __DATA_CONST.__kalloc_type: 0x7040
+  __DATA_CONST.__const: 0x18b18
   __DATA_CONST.__kalloc_var: 0x8c00
-  __DATA_CONST.__auth_got: 0x930
-  __DATA_CONST.__got: 0x140
+  __DATA_CONST.__kalloc_type: 0x7040
+  __DATA_CONST.__auth_got: 0x938
+  __DATA_CONST.__got: 0x148
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 5086
-  Symbols:   10817
-  CStrings:  5405
+  Functions: 5092
+  Symbols:   10854
+  CStrings:  5441
 
Symbols:
+ _ZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStateb
+ __Z24GetNextRotationTargetANEjj
+ __ZN11ANEHWDevice21HandleFirmwareTimeoutEb
+ __ZN11ANEHWDevice22aneExclaveToSEPHandoffEb
+ __ZN11ANEHWDevice26ANE_sendISPSurfaceRemapAckEP21FWSharedMemoryRequestjyy
+ __ZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStateb
+ __ZN12ANEScheduler23forceBondedPeerRecoveryE17aneHWBoardSubType
+ __ZN12ANEScheduler33shouldYieldToLowerPriorityRequestERK19ANEInferenceRequest
+ __ZN18ANEDeviceInterface21HandleFirmwareTimeoutEb
+ __ZN19ANEClientDeviceCore4initEj
+ __ZN19ANEInferenceRequest22endOutstandingPerfWorkEv
+ __ZN19ANEInferenceRequest38notifyPerfControllerOfNonScheduledANEsE19eAnsCmdProgramEvent
+ __ZN9ANEDriver45ANEDevicePropertiesArrivalNotificationHandlerEPvP9IOServiceP10IONotifier
+ __ZN9IOService15getPMRootDomainEv
+ __ZZ17SelectBestANECoreRK14GlobalANEStatsRK15MappingANEStatsyjRK17ANESelectionHintsE11_os_log_fmt__13_
+ __ZZ17SelectBestANECoreRK14GlobalANEStatsRK15MappingANEStatsyjRK17ANESelectionHintsE11_os_log_fmt__14_
+ __ZZ17SelectBestANECoreRK14GlobalANEStatsRK15MappingANEStatsyjRK17ANESelectionHintsE11_os_log_fmt__15_
+ __ZZ24GetNextRotationTargetANEjjE11_os_log_fmt
+ __ZZ24GetNextRotationTargetANEjjE11_os_log_fmt_0
+ __ZZN11ANEHWDevice19ANE_GetStatus_gatedEP9ANEStatusE11_os_log_fmt
+ __ZZN11ANEHWDevice20HandleRTBuddyMessageEPvS0_E11_os_log_fmt_9
+ __ZZN11ANEHWDevice20HandleRTBuddyMessageEPvS0_E11_os_log_fmt__10_
+ __ZZN11ANEHWDevice21SetRTBuddyPowerPolicyE20ANERTBuddyPowerStateE11_os_log_fmt_7
+ __ZZN11ANEHWDevice22aneExclaveToSEPHandoffEbE11_os_log_fmt
+ __ZZN11ANEHWDevice22aneExclaveToSEPHandoffEbE11_os_log_fmt_0
+ __ZZN11ANEHWDevice22aneExclaveToSEPHandoffEbE11_os_log_fmt_1
+ __ZZN11ANEHWDevice22setPowerStateGatedPrivEmP9IOServiceE11_os_log_fmt__12_
+ __ZZN11ANEHWDevice22setPowerStateGatedPrivEmP9IOServiceE11_os_log_fmt__13_
+ __ZZN11ANEHWDevice23ReadPerformanceCountersEjPK14ANEPerfCounterPybbbE11_os_log_fmt_2
+ __ZZN11ANEHWDevice23ReadPerformanceCountersEjPK14ANEPerfCounterPybbbE11_os_log_fmt_3
+ __ZZN11ANEHWDevice25takePowerAssertionPrivateEP24ANEHWDeviceClientContext21ANEHWDevicePowerLevelE11_os_log_fmt_0
+ __ZZN11ANEHWDevice26ANE_sendISPSurfaceRemapAckEP21FWSharedMemoryRequestjyyE11_os_log_fmt
+ __ZZN11ANEHWDevice26ANE_sendISPSurfaceRemapAckEP21FWSharedMemoryRequestjyyE11_os_log_fmt_0
+ __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStatebE11_os_log_fmt
+ __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStatebE11_os_log_fmt_0
+ __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStatebE11_os_log_fmt_1
+ __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStatebE11_os_log_fmt_2
+ __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStatebE11_os_log_fmt_3
+ __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStatebE11_os_log_fmt_4
+ __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStatebE11_os_log_fmt_5
+ __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStatebE11_os_log_fmt_6
+ __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStatebE11_os_log_fmt_7
+ __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStatebE11_os_log_fmt_8
+ __ZZN11ANEHWDevice27waitForPowerAssertion_gatedE21ANEHWDevicePowerLevelE11_os_log_fmt_1
+ __ZZN11ANEHWDevice28processTargetToHostIOCommandEyyyE11_os_log_fmt__29_
+ __ZZN11ANEHWDevice28processTargetToHostIOCommandEyyyE11_os_log_fmt__30_
+ __ZZN11ANEHWDevice34processSharedMallocRequestEndpointEyyE11_os_log_fmt_2
+ __ZZN11ANEHWDevice34processSharedMallocRequestEndpointEyyE11_os_log_fmt_3
+ __ZZN11ANEHWDevice34processSharedMallocRequestEndpointEyyE11_os_log_fmt_4
+ __ZZN11ANEHWDevice34processSharedMallocRequestEndpointEyyE11_os_log_fmt_5
+ __ZZN11ANEHWDevice4stopEP9IOServiceE21kalloc_type_view_4960
+ __ZZN11ANEHWDevice4stopEP9IOServiceE21kalloc_type_view_5037
+ __ZZN11ANEHWDevice4stopEP9IOServiceE21kalloc_type_view_5040
+ __ZZN12ANEScheduler23forceBondedPeerRecoveryE17aneHWBoardSubTypeE11_os_log_fmt
+ __ZZN12ANEScheduler33shouldYieldToLowerPriorityRequestERK19ANEInferenceRequestE11_os_log_fmt
+ __ZZN12ANEScheduler8scheduleER19ANEInferenceRequestE11_os_log_fmt__13_
+ __ZZN12ANEScheduler8scheduleER19ANEInferenceRequestE11_os_log_fmt__14_
+ __ZZN17ANEDebugLogStringdlEPvmE20kalloc_type_view_440
+ __ZZN17ANEDebugLogStringnwEmE20kalloc_type_view_440
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2198
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2286
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2368
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2507
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_3859
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_4002
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_4259
+ __ZZN17ANEHWDeviceConfig23initializeANEPropertiesEP11ANEHWDeviceE20kalloc_type_view_445
+ __ZZN18ANEReqCallbackDatadlEPvmE21kalloc_type_view_1398
+ __ZZN18ANEReqCallbackDatanwEmE21kalloc_type_view_1398
+ __ZZN19ANEClientDeviceCore18cleanupMappingInfoEP15ANECoalesceInfojjE21kalloc_type_view_3452
+ __ZZN19ANEClientDeviceCore27ANE_MemoryMapRequest_lockedERK24ANEMemoryMapLockedParamsE21kalloc_type_view_2547
+ __ZZN19ANEClientDeviceCore27ANE_MemoryMapRequest_lockedERK24ANEMemoryMapLockedParamsE21kalloc_type_view_2555
+ __ZZN19ANEClientDeviceCore4initEjE11_os_log_fmt
+ __ZZN19ANEClientDeviceCore4initEjE11_os_log_fmt_0
+ __ZZN19ANEInferenceRequest15removeRTCommandEvE20kalloc_type_view_598
+ __ZZN19ANEInferenceRequest15removeRTCommandEvE20kalloc_type_view_602
+ __ZZN19ANEInferenceRequest15removeRTCommandEvE20kalloc_type_view_608
+ __ZZN19ANEInferenceRequest22endOutstandingPerfWorkEvE11_os_log_fmt
+ __ZZN20ANEProcessCreateArgsdlEPvmE20kalloc_type_view_741
+ __ZZN20ANEProcessCreateArgsnwEmE20kalloc_type_view_741
+ __ZZN9ANEDriver5startEP9IOServiceE11_os_log_fmt__10_
+ __ZZZN19ANEClientDeviceCore22ANE_ProgramSendRequestEP21ANEProgramRequestArgsPyPvbP18ANEReqCallbackDataP4taskP15ANESharedEventsEN9BlockVarsdlES3_mE21kalloc_type_view_1406
+ __ZZZN19ANEClientDeviceCore22ANE_ProgramSendRequestEP21ANEProgramRequestArgsPyPvbP18ANEReqCallbackDataP4taskP15ANESharedEventsEN9BlockVarsnwEmE21kalloc_type_view_1406
+ __ZZZN9ANEDriver45ANEDevicePropertiesArrivalNotificationHandlerEPvP9IOServiceP10IONotifierEUb0_E11_os_log_fmt
+ ____ZN9ANEDriver45ANEDevicePropertiesArrivalNotificationHandlerEPvP9IOServiceP10IONotifier_block_invoke
+ _gIOPlatformActiveActionKey
- _ZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandState
- _ZN11ANEHWDevice28processTargetToHostIOCommandEyyy
- __ZN11ANEHWDevice21HandleFirmwareTimeoutEv
- __ZN11ANEHWDevice22aneExclaveToSEPHandoffEv
- __ZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandState
- __ZN12ANEScheduler33shouldYieldToLowerPriorityRequestEj
- __ZN19ANEClientDeviceCore4initEv
- __ZN19ANEInferenceRequest38notifyPerfControllerOfNonScheduledANEsEv
- __ZZN11ANEHWDevice22aneExclaveToSEPHandoffEvE11_os_log_fmt
- __ZZN11ANEHWDevice22aneExclaveToSEPHandoffEvE11_os_log_fmt_0
- __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStateE11_os_log_fmt
- __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStateE11_os_log_fmt_0
- __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStateE11_os_log_fmt_1
- __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStateE11_os_log_fmt_2
- __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStateE11_os_log_fmt_3
- __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStateE11_os_log_fmt_4
- __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStateE11_os_log_fmt_5
- __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStateE11_os_log_fmt_6
- __ZZN11ANEHWDevice27HandleFirmwareTimeout_gatedEP23ANEFirmwareCommandStateE11_os_log_fmt_7
- __ZZN11ANEHWDevice31ANE_processISPSurfaceMapRequestEP10ANEMessageE11_os_log_fmt_5
- __ZZN11ANEHWDevice31ANE_processISPSurfaceMapRequestEP10ANEMessageE11_os_log_fmt_6
- __ZZN11ANEHWDevice4stopEP9IOServiceE21kalloc_type_view_4830
- __ZZN11ANEHWDevice4stopEP9IOServiceE21kalloc_type_view_4907
- __ZZN11ANEHWDevice4stopEP9IOServiceE21kalloc_type_view_4910
- __ZZN12ANEScheduler33shouldYieldToLowerPriorityRequestEjE11_os_log_fmt
- __ZZN17ANEDebugLogStringdlEPvmE20kalloc_type_view_430
- __ZZN17ANEDebugLogStringnwEmE20kalloc_type_view_430
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2170
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2258
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2340
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2479
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_3831
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_3974
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_4231
- __ZZN17ANEHWDeviceConfig23initializeANEPropertiesEP11ANEHWDeviceE20kalloc_type_view_439
- __ZZN18ANEReqCallbackDatadlEPvmE21kalloc_type_view_1364
- __ZZN18ANEReqCallbackDatanwEmE21kalloc_type_view_1364
- __ZZN19ANEClientDeviceCore18cleanupMappingInfoEP15ANECoalesceInfojjE21kalloc_type_view_3438
- __ZZN19ANEClientDeviceCore27ANE_MemoryMapRequest_lockedERK24ANEMemoryMapLockedParamsE21kalloc_type_view_2533
- __ZZN19ANEClientDeviceCore27ANE_MemoryMapRequest_lockedERK24ANEMemoryMapLockedParamsE21kalloc_type_view_2541
- __ZZN19ANEClientDeviceCore4initEvE11_os_log_fmt
- __ZZN19ANEClientDeviceCore4initEvE11_os_log_fmt_0
- __ZZN19ANEInferenceRequest15removeRTCommandEvE20kalloc_type_view_597
- __ZZN19ANEInferenceRequest15removeRTCommandEvE20kalloc_type_view_601
- __ZZN19ANEInferenceRequest15removeRTCommandEvE20kalloc_type_view_607
- __ZZN20ANEProcessCreateArgsdlEPvmE20kalloc_type_view_707
- __ZZN20ANEProcessCreateArgsnwEmE20kalloc_type_view_707
- __ZZZN19ANEClientDeviceCore22ANE_ProgramSendRequestEP21ANEProgramRequestArgsPyPvbP18ANEReqCallbackDataP4taskP15ANESharedEventsEN9BlockVarsdlES3_mE21kalloc_type_view_1392
- __ZZZN19ANEClientDeviceCore22ANE_ProgramSendRequestEP21ANEProgramRequestArgsPyPvbP18ANEReqCallbackDataP4taskP15ANESharedEventsEN9BlockVarsnwEmE21kalloc_type_view_1392
CStrings:
+ "%s: %s: ANE Memory remap ack by mailbox offset: 0x%llx size: 0x%llx\n"
+ "%s: %s: ANE driver back-reference not set yet, reporting local max macho size 0x%llx\n"
+ "%s: %s: ANE%u: InjectTMSyncErr active -- allowing dispatch to proceed with dynamic power gating still active\n"
+ "%s: %s: ANE%u: InjectTMSyncErr active -- skipping disable dynamic power gating for this power assertion\n"
+ "%s: %s: ANE%u: recovery entry point reached -- clearing the skip-disable-DPG injection flag\n"
+ "%s: %s: ANEDevicePropertiesArrivalNotificationHandler: numANEs discovered so far: %u\n"
+ "%s: %s: Client specified ANE instance hint (core %u), skipping rotation bias\n"
+ "%s: %s: Core %u , client preference %u\n"
+ "%s: %s: Core %u, rotation bias preference %u\n"
+ "%s: %s: Firmware recovery completed... deferring ANEExclave notification until next power-on\n"
+ "%s: %s: Forcing bonded peer ANE%u through firmware timeout recovery after TM sync error on ANE%u\n"
+ "%s: %s: GetNextRotationTargetANE: %u -> %u (residencyMask 0x%x)\n"
+ "%s: %s: SUSPEND skipped for system-initiated power transition, requesting power policy %s for state %d\n"
+ "%s: %s: Servicing deferred firmware recovery notification to ANEExclave\n"
+ "%s: %s: Single-ANE rotation flipped preferred ANE to %u\n"
+ "%s: %s: Skipping SECURE mode transition ACK\n"
+ "%s: %s: WRK %-3u ANE %-3u HOL %-3u CLPC %-3u THROT %-3u clientPref %-3u PWR %-3u ROT %-3u\n"
+ "%s: %s: Waking from hibernate, clearing cached performance counters\n"
+ "%s: %s: Waking from hibernate, clearing cached performance counters (ActiveAction)\n"
+ "121111121222121212111222122222222222221222222012212021111112212211222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222221221221122122111112"
+ "12111122222222222222212222222222222221222222222222222122222222222222211110111101111122122112212212112111111211111122222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222221221222212212212212212212212"
+ "2222222222222222222111121212222222222222222222222222222222222122"
+ "ANEDevicePropertiesArrivalNotificationHandler_block_invoke"
+ "ANE_GetStatus_gated"
+ "ANE_sendISPSurfaceRemapAck"
+ "GetNextRotationTargetANE"
+ "IOHibernateState"
+ "[ERROR] %s: %s: ANE:%u detected a TM SYNC Error event!!\n"
+ "[ERROR] %s: %s: BACK_CHANNEL_RPC: message too small for %u declared rpc items: messageSize=0x%llx required=0x%llx\n"
+ "[ERROR] %s: %s: CLPC work still outstanding at destruction (residency: 0x%x, status: %u) for programHandle: 0x%llx, transactionID: 0x%llx\n"
+ "[ERROR] %s: %s: Couldn't create matching dictionary for H11ANEIn device properties notification\n"
+ "[ERROR] %s: %s: Endpoint[%ld] message too small for command header: offset[0x%llx] size[0x%llx]\n"
+ "[ERROR] %s: %s: Endpoint[%ld] message too small for handshake info: offset[0x%llx] size[0x%llx]\n"
+ "[ERROR] %s: %s: Failed to enable ane power off timer after boot bring-up: 0x%x\n"
+ "[ERROR] %s: %s: Failed to send shared memory remap ack res=%d\n"
+ "[ERROR] %s: %s: GetNextRotationTargetANE returned out-of-range index %u (numANEs: %u), skipping flip\n"
+ "[ERROR] %s: %s: GetNextRotationTargetANE: residencyMask is empty, defaulting to ANE 0\n"
+ "[ERROR] %s: %s: Invalid offset[0x%llx] and size[0x%llx] for endpoint[%ld] bufferSize[0x%zx]. Out of bounds message"
+ "[ERROR] %s: %s: Shared memory alloc message too small: offset:0x%llx, size:0x%llx\n"
+ "[ERROR] %s: %s: Shared memory free message too small: offset:0x%llx, size:0x%llx\n"
+ "[ERROR] %s: %s: Shared memory message too small for command header: offset:0x%llx, size:0x%llx\n"
+ "[ERROR] %s: %s: Shared memory remap message too small: offset:0x%llx, size:0x%llx\n"
+ "[ERROR] %s: %s: rotationPreferredAneIdx %u out of range (max: %u), skipping rotation bias\n"
+ "endOutstandingPerfWork"
+ "forceBondedPeerRecovery"
- "\"ANE:%u detected a TM SYNC Error event!!\\n\" @%s:%d"
- "%s: %s: ANE Memory remap req by mailbox offset: 0x%llx size:  0x%llx\n"
- "%s: %s: Firmware recovery completed... notifying ANEExclave\n"
- "%s: %s: WRK %-3u ANE %-3u HOL %-3u CLPC %-3u THROT %-3u clientPref %-3u PWR %-3u\n"
- "1211111212221212121112221222222222222212222220122120211111122122112222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222212212211221221111"
- "121111222222222222222122222222222222212222222222222221222222222222222111101111011111221221122122121121111112111111222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222212212212212212212212212212"
- "222222222222222222211112121222222222222222222222222222222222122"
- "ANEScheduler: %s: Core %u , client preference %u\n"
- "[ERROR] %s: %s: Invalid offset[0x%llx] and size[0x%llx] for endpoint[%ld]. Oversized message"
```
