## iTunesCloud

> `/System/Library/PrivateFrameworks/iTunesCloud.framework/Versions/A/iTunesCloud`

```diff

-4026.300.13.0.0
-  __TEXT.__text: 0x31fa1c
+4026.300.16.0.0
+  __TEXT.__text: 0x31f9b8
   __TEXT.__objc_methlist: 0x1891c
   __TEXT.__const: 0x272e8
   __TEXT.__dlopen_cstrs: 0x2ff

   __AUTH_CONST.__objc_intobj: 0x468
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x258
-  __AUTH_CONST.__auth_got: 0x990
+  __AUTH_CONST.__auth_got: 0x998
   __AUTH.__objc_data: 0x280
   __DATA.__objc_ivar: 0x24d8
   __DATA.__data: 0x2aa8

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   Functions: 10179
-  Symbols:   21298
+  Symbols:   21299
   CStrings:  5448
 
Symbols:
+ _os_unfair_recursive_lock_lock
Functions:
~ -[ICNetworkMonitor _onQueue_setup] : 1392 -> 1380
~ -[ICNetworkMonitor networkType] : 224 -> 220
~ -[ICNetworkMonitor lastKnownNetworkType] : 224 -> 220
~ -[ICNetworkMonitor isRemoteServerReachable] : 224 -> 220
~ -[ICNetworkMonitor isRemoteServerLikelyReachable] : 224 -> 220
~ -[ICNetworkMonitor currentNetworkLinkQuality] : 224 -> 220
~ -[ICNetworkMonitor isCurrentNetworkLinkExpensive] : 224 -> 220
~ -[ICNetworkMonitor isWiFiAssociated] : 224 -> 220
~ -[ICNetworkMonitor isEthernetWired] : 224 -> 220
~ -[ICNetworkMonitor isWifiActive] : 224 -> 220
~ -[ICNetworkMonitor isNetworkConstrained] : 224 -> 220
~ -[ICNetworkMonitor telephonyOperatorName] : 284 -> 280
~ -[ICNetworkMonitor telephonyRegistrationStatus] : 284 -> 280
~ -[ICNetworkMonitor signalInfo] : 908 -> 904
~ -[ICNetworkMonitor signalStrength] : 1356 -> 1352
~ -[ICNetworkMonitor _onQueue_updateNetworkStateWithTelephonyChangeType:andNotifyDelegate:] : 1124 -> 1104
~ -[ICNetworkMonitor _onQueue_updateTelephonyState] : 804 -> 796
~ -[ICNetworkMonitor cellMonitorUpdate:info:] : 524 -> 520
```
