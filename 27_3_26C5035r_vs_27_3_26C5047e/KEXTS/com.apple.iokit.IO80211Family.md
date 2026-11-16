## com.apple.iokit.IO80211Family

> `com.apple.iokit.IO80211Family`

```diff

-1590.3.0.0.0
+1590.5.0.0.0
   __TEXT.__os_log: 0x9e90
   __TEXT.__const: 0x2bec0
-  __TEXT.__cstring: 0x99a44
-  __TEXT_EXEC.__text: 0x2720d4
-  __TEXT_EXEC.__auth_stubs: 0x1420
+  __TEXT.__cstring: 0x99a2c
+  __TEXT_EXEC.__text: 0x272248
+  __TEXT_EXEC.__auth_stubs: 0x1430
   __DATA.__data: 0x5ee0
-  __DATA.__common: 0x50c8
+  __DATA.__common: 0x50d0
   __DATA.__bss: 0x14d8
   __DATA_CONST.__mod_init_func: 0x558
   __DATA_CONST.__mod_term_func: 0x558
   __DATA_CONST.__const: 0x3a508
   __DATA_CONST.__kalloc_type: 0x9ec0
   __DATA_CONST.__kalloc_var: 0xa00
-  __DATA_CONST.__auth_got: 0xa10
+  __DATA_CONST.__auth_got: 0xa18
   __DATA_CONST.__got: 0x150
   __DATA_CONST.__auth_ptr: 0x20
-  Functions: 13171
-  Symbols:   17184
+  Functions: 13172
+  Symbols:   17187
   CStrings:  14948
 
Symbols:
+ __Z23IO80211_isCustomerBuildv
+ __ZN18IO80211PeerMonitor17incrementTxStatusEijhP20PacketSkywalkScratchyb
+ __ZN18IO80211PeerMonitor19incrementRxExtStatsEP20IO80211NetworkPacketP15packet_info_tagP16lowlatencyStatusb
+ __ZN18IO80211PeerMonitor24updateTxCompletionStatusEijmhP20PacketSkywalkScratchyb
+ __ZZ23IO80211_isCustomerBuildvE9buildType
+ __ZZN17IO80211Controller4freeEvE20kalloc_type_view_841
+ __ZZN17IO80211Controller4freeEvE20kalloc_type_view_877
+ __ZZN17IO80211Controller4initEP12OSDictionaryE20kalloc_type_view_664
+ __ZZN22IO80211AWDLPeerManager10growAFRingEvE22kalloc_type_view_19457
+ __ZZN22IO80211AWDLPeerManager10growAFRingEvE22kalloc_type_view_19469
+ __ZZN22IO80211AWDLPeerManager12shrinkAFRingEvE22kalloc_type_view_19493
+ __ZZN22IO80211AWDLPeerManager12shrinkAFRingEvE22kalloc_type_view_19505
+ __ZZN22IO80211AWDLPeerManager22initAWDLStateTrackInfoEvE22kalloc_type_view_25007
+ __ZZN22IO80211AWDLPeerManager28freeAwdlPacketDescriptorPoolEvE22kalloc_type_view_40760
+ __ZZN22IO80211AWDLPeerManager28initAwdlPacketDescriptorPoolEjE22kalloc_type_view_40744
+ __ZZN22IO80211AWDLPeerManager33realTimeStatsGetSkywalkStatisticsEvE22kalloc_type_view_30638
+ __ZZN22IO80211AWDLPeerManager33realTimeStatsGetSkywalkStatisticsEvE22kalloc_type_view_30668
+ __ZZN30IO80211NANRadioResourceManager15initWithManagerEP21IO80211NANPeerManagerE19kalloc_type_view_81
+ __ZZN30IO80211NANRadioResourceManager4freeEvE19kalloc_type_view_95
+ ___FUNCTION__._ZN18IO80211PeerMonitor17incrementTxStatusEijhP20PacketSkywalkScratchyb
+ _kern_config_is_development
- __ZN18IO80211PeerMonitor17incrementTxStatusEijhP20PacketSkywalkScratchy
- __ZN18IO80211PeerMonitor19incrementRxExtStatsEP20IO80211NetworkPacketP15packet_info_tagP16lowlatencyStatus
- __ZN18IO80211PeerMonitor24updateTxCompletionStatusEijmhP20PacketSkywalkScratchy
- __ZZN17IO80211Controller4freeEvE20kalloc_type_view_837
- __ZZN17IO80211Controller4freeEvE20kalloc_type_view_873
- __ZZN17IO80211Controller4initEP12OSDictionaryE20kalloc_type_view_660
- __ZZN22IO80211AWDLPeerManager10growAFRingEvE22kalloc_type_view_19449
- __ZZN22IO80211AWDLPeerManager10growAFRingEvE22kalloc_type_view_19461
- __ZZN22IO80211AWDLPeerManager12shrinkAFRingEvE22kalloc_type_view_19485
- __ZZN22IO80211AWDLPeerManager12shrinkAFRingEvE22kalloc_type_view_19497
- __ZZN22IO80211AWDLPeerManager22initAWDLStateTrackInfoEvE22kalloc_type_view_24999
- __ZZN22IO80211AWDLPeerManager28freeAwdlPacketDescriptorPoolEvE22kalloc_type_view_40752
- __ZZN22IO80211AWDLPeerManager28initAwdlPacketDescriptorPoolEjE22kalloc_type_view_40736
- __ZZN22IO80211AWDLPeerManager33realTimeStatsGetSkywalkStatisticsEvE22kalloc_type_view_30630
- __ZZN22IO80211AWDLPeerManager33realTimeStatsGetSkywalkStatisticsEvE22kalloc_type_view_30660
- __ZZN30IO80211NANRadioResourceManager15initWithManagerEP21IO80211NANPeerManagerE19kalloc_type_view_80
- __ZZN30IO80211NANRadioResourceManager4freeEvE19kalloc_type_view_94
- ___FUNCTION__._ZN18IO80211PeerMonitor17incrementTxStatusEijhP20PacketSkywalkScratchy
CStrings:
+ "\"IO80211_kexts-1590.5\""
+ "Debuggable - IO80211_isCustomerBuild"
+ "IO80211_kexts-1590.5"
+ "Nov  9 2026 23:30:12"
- "\"IO80211_kexts-1590.3\""
- "ERROR: Received follow-up service length %d greater than %d\n"
- "IO80211_kexts-1590.3"
- "Oct 30 2026 01:15:10"
```
