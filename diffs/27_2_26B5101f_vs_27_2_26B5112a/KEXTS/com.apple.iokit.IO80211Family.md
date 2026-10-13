## com.apple.iokit.IO80211Family

> `com.apple.iokit.IO80211Family`

```diff

-1587.9.0.0.0
+1587.10.0.0.0
   __TEXT.__os_log: 0x9e58
   __TEXT.__const: 0x2bec0
-  __TEXT.__cstring: 0x9959f
-  __TEXT_EXEC.__text: 0x27138c
+  __TEXT.__cstring: 0x99646
+  __TEXT_EXEC.__text: 0x27143c
   __TEXT_EXEC.__auth_stubs: 0x1420
   __DATA.__data: 0x5ec8
   __DATA.__common: 0x50c8

   __DATA_CONST.__got: 0x150
   __DATA_CONST.__auth_ptr: 0x20
   Functions: 13152
-  Symbols:   17177
-  CStrings:  14929
+  Symbols:   17176
+  CStrings:  14931
 
Symbols:
- __FUNCTION__._ZN25IO80211P2PDFSProxyManager28checkForDFSPrimeAvailabilityEP18apple80211_channelPh28apple80211_dfs_proxy_clients
Functions:
~ __ZN22IO80211AWDLPeerManager15setAirDropStateEb : 276 -> 308
~ __ZN25IO80211P2PDFSProxyManager28checkForDFSPrimeAvailabilityEP18apple80211_channelPh28apple80211_dfs_proxy_clients : 352 -> 432
~ __ZN25IO80211P2PDFSProxyManager27configureDFSPrimeMonitoringEv : 396 -> 404
~ __ZN25IO80211P2PDFSProxyManager14handleScanDoneEv : 1088 -> 1104
~ __ZN25IO80211P2PDFSProxyManager11setDFSProxyEhPhb : 248 -> 288
CStrings:
+ "\"IO80211_kexts-1587.10\""
+ "%s:%d DFSP AWDL peer manager not available, not starting DFS monitoring for %s\n"
+ "%s:%d ERROR: DFSP AWDL peer manager not available, cannot configure DFS Proxy\n"
+ "IO80211_kexts-1587.10"
+ "Oct  7 2026 22:34:55"
+ "[ik] %s@%d:AirDrop state changed to <%d> <%llu>\n"
- "\"IO80211_kexts-1587.9\""
- "IO80211_kexts-1587.9"
- "Sep 29 2026 21:17:06"
- "[ik] %s@%d:AirDrop state changed to <%d> \n"
```
