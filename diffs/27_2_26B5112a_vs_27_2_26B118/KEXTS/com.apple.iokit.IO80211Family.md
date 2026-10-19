## com.apple.iokit.IO80211Family

> `com.apple.iokit.IO80211Family`

```diff

 1587.10.0.0.0
   __TEXT.__os_log: 0x9e58
   __TEXT.__const: 0x2bec0
-  __TEXT.__cstring: 0x99646
-  __TEXT_EXEC.__text: 0x27143c
+  __TEXT.__cstring: 0x999ac
+  __TEXT_EXEC.__text: 0x271a20
   __TEXT_EXEC.__auth_stubs: 0x1420
   __DATA.__data: 0x5ec8
   __DATA.__common: 0x50c8

   __DATA_CONST.__auth_ptr: 0x20
   Functions: 13152
   Symbols:   17176
-  CStrings:  14931
+  CStrings:  14943
 
Functions:
~ __Z27IO80211_io80211isDebuggablev : 228 -> 236
~ __ZN17IO80211Controller19io80211isDebuggableEPb : 240 -> 252
~ __ZN27IO80211NANDataPathInitiator4freeEv : 108 -> 120
~ __ZN27IO80211NANDataPathInitiator27handleDataPathResponseRecvdEP39apple80211_nan_dp_resp_recvd_event_data : 2044 -> 2176
~ __ZN27IO80211NANDataPathInitiator28parseNANDPAttrServiceInfoTLVEP32apple80211_nan_data_path_ext_tlv : 192 -> 200
~ __ZN27IO80211NANDataPathResponder4initEP21IO80211NANPeerManagerP18IO80211PeerManager22apple80211_nan_dp_rolePv : 268 -> 264
~ __ZN27IO80211NANDataPathResponder26handleDataPathRequestRecvdEP42apple80211_nan_dp_request_recvd_event_data : 2084 -> 2176
~ __ZN27IO80211NANDataPathResponder4freeEv : 108 -> 120
~ __ZN27IO80211NANDataPathResponder28parseNANDPAttrServiceInfoTLVEP32apple80211_nan_data_path_ext_tlv : 192 -> 200
~ __ZN27IO80211NANServiceDescriptor17parseSDAAttributeEP24apple80211_nan_attributetP18apple80211_sdf_ctx : 596 -> 1528
~ __ZN27IO80211NANServiceDescriptor21parseNANSDFAttributesEPhtP18apple80211_sdf_ctx : 608 -> 904
CStrings:
+ "%s: ERROR: DP attribute length %u too short for publish id\n"
+ "%s: ERROR: DP attribute length %u too short for responder NDI\n"
+ "%s: ERROR: DP attribute length %u too short, minimum %u\n"
+ "ERROR: %s::%s NAN attribute ID %d at offset %u with length %u exceeds dataLen %u\n"
+ "ERROR: %s::%s Parsing SD attribute, SRF length %u exceeds remaining %u\n"
+ "ERROR: %s::%s Parsing SD attribute, length %u too short for SRF header\n"
+ "ERROR: %s::%s Parsing SD attribute, length %u too short for match filter length\n"
+ "ERROR: %s::%s Parsing SD attribute, length %u too short for service info length\n"
+ "ERROR: %s::%s Parsing SD attribute, length %u too short, minimum %u\n"
+ "ERROR: %s::%s Parsing SD attribute, match filter length %u exceeds remaining %u\n"
+ "ERROR: %s::%s Parsing SD attribute, service info length %u exceeds remaining %u\n"
+ "ERROR: %s::%s Truncated NAN attribute header at offset %u, dataLen %u\n"
+ "Oct 14 2026 23:07:05"
- "Oct  7 2026 22:34:55"
```
