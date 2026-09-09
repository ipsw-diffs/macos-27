## CoreMIDI

> `/System/Library/Frameworks/CoreMIDI.framework/Versions/A/CoreMIDI`

```diff

 333.0.0.0.0
-  __TEXT.__text: 0xa82f0
+  __TEXT.__text: 0xa8314
   __TEXT.__realtime: 0x1844
   __TEXT.__objc_methlist: 0x15c0
   __TEXT.__const: 0xa48
   __TEXT.__dlopen_cstrs: 0x4e
-  __TEXT.__gcc_except_tab: 0xdc08
+  __TEXT.__gcc_except_tab: 0xdc10
   __TEXT.__cstring: 0x4e9c
   __TEXT.__oslogstring: 0x2a1e
   __TEXT.__unwind_info: 0x40c0
Functions:
~ __ZN26MIDIDriverPlugin_DriverKit9StartMIDIEj : 5732 -> 5736
~ __ZNSt3__110__function6__funcIZN26MIDIDriverPlugin_DriverKitC1EO19MIDIDriverKitClientPK10__CFStringS7_EUljNS_4spanIKjLm18446744073709551615EEEE_FvjSA_EEclEOjOSA_ : 4868 -> 4864
~ __ZNSt3__16vectorIjNS_9allocatorIjEEE24__emplace_back_slow_pathIJjEEEPjDpOT_ : 184 -> 176
~ _MIDIEventListForEachEvent : 1708 -> 1712
~ __ZN6MIDICI14SysexCollector4feedEPK13MIDIEventList : 848 -> 860
~ _MIDIEventPacketSysexBytesForGroup : 800 -> 804
~ __ZNSt3__16vectorIyNS_9allocatorIyEEE24__emplace_back_slow_pathIJyEEEPyDpOT_ : 184 -> 176
~ __ZNSt3__16vectorIN10applesauce2CF9NumberRefENS_9allocatorIS3_EEE7reserveEm : 132 -> 136
~ __ZN4MIDI36sendOrDeferEventsOnActiveSysExGroupsEPKNS_9EventListENSt3__14spanIbLm18446744073709551615EEEN5caulk16inplace_functionIFvS2_ELm32ELm8ENS6_23inplace_function_detail9rt_vtableEEENS7_IFv14MIDIProtocolIDPK15MIDIEventPacketELm32ELm8ESA_EE : 1016 -> 1024
~ __ZNSt3__16vectorIP10MIDISourceNS_9allocatorIS2_EEE24__emplace_back_slow_pathIJRKS2_EEEPS2_DpOT_ : 184 -> 176
~ __UMPCIDiscover : 1172 -> 1168
~ __ZNSt3__16vectorIN8nlohmann10basic_jsonINS_3mapES0_NS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEbxydS7_NS1_14adl_serializerENS0_IhNS7_IhEEEEEENS7_ISD_EEE24__emplace_back_slow_pathIJNS1_6detail7value_tEEEEPSD_DpOT_ : 292 -> 296
~ __ZN4MIDI11StreamState22update_with_v1_packetsENSt3__14spanIKjLm18446744073709551615EEE : 360 -> 356
~ __ZN4MIDI18MIDI_1UP_DelivererclEPKNS_9EventListE : 1240 -> 1224
~ __ZNSt3__16vectorIN13MIDIInputPort15ConnectedSourceENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJRP10MIDISourceNS_10unique_ptrIN4MIDI18EventListDelivererENS_14default_deleteISC_EEEEEEEPS2_DpOT_ : 308 -> 316
~ __ZNSt3__110__function6__funcIZN6MIDICI13DeviceManagerC1ER18UMPCIServerContextE3$_0FvjPK13MIDIEventListEEclEOjOS9_ : 1516 -> 1524
~ __ZNSt3__16vectorINS_10unique_ptrI14MIDIConnectionNS_14default_deleteIS2_EEEENS_9allocatorIS5_EEE24__emplace_back_slow_pathIJS5_EEEPS5_DpOT_ : 220 -> 224
~ __ZL17AddDeviceChildrenRNSt3__16vectorIjNS_9allocatorIjEEEEj : 920 -> 916
~ __ZNSt3__16vectorI18CIAsyncTransactionNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJS1_EEEPS1_DpOT_ : 468 -> 464
~ __ZN15MIDIDestination14SendPacketsNowEPvPKN4MIDI9EventListE : 1244 -> 1248
~ __ZN15MIDIDestination28DeliverAndDequeueIfNecessaryEPKN4MIDI9EventListEPv : 1216 -> 1220
~ __ZZN5caulk23inplace_function_detail9rt_vtableIvJPKN4MIDI9EventListEEEC1IZN10MIDISource17AddThruConnectionEP14MIDIConnectionE3$_0EENS0_7wrapperIT_EEENUlPvOS5_E_8__invokeESF_SG_ : 2312 -> 2316
~ __ZL19CountChildrenOfNodejb : 192 -> 196
~ __ZL14GetChildOfNodejmb : 220 -> 224
~ __ZN16FlushManagerBase12InspectEventER14ScheduledEvent : 460 -> 464
~ __ZN16BaseOpaqueObjectC2Ev : 460 -> 464
~ __ZN16BaseOpaqueObjectD2Ev : 456 -> 460
~ __ZN5caulk10concurrent25guarded_lookup_hash_tableIjP16BaseOpaqueObjectLNS0_33guarded_lookup_hash_table_optionsE0E24OpaqueObjectIdentityHashE6rehashEj : 300 -> 304
```
