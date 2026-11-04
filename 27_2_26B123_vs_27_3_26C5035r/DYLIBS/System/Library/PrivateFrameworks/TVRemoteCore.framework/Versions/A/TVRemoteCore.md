## TVRemoteCore

> `/System/Library/PrivateFrameworks/TVRemoteCore.framework/Versions/A/TVRemoteCore`

```diff

-627.10.51.0.0
-  __TEXT.__text: 0x4aed8
-  __TEXT.__objc_methlist: 0x6748
+627.20.10.0.0
+  __TEXT.__text: 0x4bfd8
+  __TEXT.__objc_methlist: 0x67e0
   __TEXT.__const: 0x242
-  __TEXT.__cstring: 0x36ac
-  __TEXT.__gcc_except_tab: 0xb68
-  __TEXT.__oslogstring: 0x68bb
-  __TEXT.__unwind_info: 0x18c0
+  __TEXT.__cstring: 0x374e
+  __TEXT.__gcc_except_tab: 0xbbc
+  __TEXT.__oslogstring: 0x6b5c
+  __TEXT.__unwind_info: 0x18f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0xd8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3238
+  __DATA_CONST.__objc_selrefs: 0x3280
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x208
   __DATA_CONST.__objc_arraydata: 0xf8
   __DATA_CONST.__got: 0x4a0
-  __AUTH_CONST.__const: 0x1360
-  __AUTH_CONST.__cfstring: 0x4a80
-  __AUTH_CONST.__objc_const: 0xa028
+  __AUTH_CONST.__const: 0x1390
+  __AUTH_CONST.__cfstring: 0x4b00
+  __AUTH_CONST.__objc_const: 0xa0a0
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_doubleobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x1860
-  __DATA.__objc_ivar: 0x698
+  __DATA.__objc_ivar: 0x6a0
   __DATA.__data: 0xa30
   __DATA_DIRTY.__objc_data: 0xf0
   __DATA_DIRTY.__bss: 0x160

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 2168
-  Symbols:   4718
-  CStrings:  1280
+  Functions: 2184
+  Symbols:   4746
+  CStrings:  1298
 
Symbols:
+ -[TVRCDeviceQuery discoverySources]
+ -[TVRCDeviceQuery init]
+ -[TVRCDeviceQuery setDiscoverySources:]
+ -[TVRCMatchPointDeviceImpl discoverySource]
+ -[TVRCRPCompanionLinkClientWrapper _fetchAndUpdateSiriStatus]
+ -[TVRCRPCompanionLinkClientWrapper _startMonitoringSiriStatus]
+ -[TVRCRPCompanionLinkClientWrapper _stopMonitoringSiriStatus]
+ -[TVRCRapportDeviceImpl discoverySource]
+ -[TVRCXPCClient _beginDeviceQueryWithSources:response:]
+ -[TVRCXPCClient _startDeviceQueryRetryTimerWithEventHandler:]
+ -[TVRCXPCClient beginDeviceQueryWithSources:response:]
+ -[TVRXDevice discoverySource]
+ -[TVRXDeviceQuery _stopSearchForSources:]
+ -[TVRXDeviceQuery addDiscoverySources:]
+ -[TVRXDeviceQuery discoverySources]
+ -[TVRXDeviceQuery removeDiscoverySources:]
+ -[TVRXDeviceQuery setDiscoverySources:]
+ GCC_except_table174
+ GCC_except_table176
+ GCC_except_table18
+ _OBJC_IVAR_$_TVRCDeviceQuery._discoverySources
+ _OBJC_IVAR_$_TVRXDeviceQuery._discoverySources
+ ___54-[TVRCXPCClient beginDeviceQueryWithSources:response:]_block_invoke
+ ___55-[TVRCXPCClient _beginDeviceQueryWithSources:response:]_block_invoke
+ ___61-[TVRCRPCompanionLinkClientWrapper _fetchAndUpdateSiriStatus]_block_invoke
+ ___61-[TVRCXPCClient _startDeviceQueryRetryTimerWithEventHandler:]_block_invoke
+ ___62-[TVRCRPCompanionLinkClientWrapper _startMonitoringSiriStatus]_block_invoke
+ ___block_descriptor_56_e8_32bs40w_e5_v8?0l
+ _objc_msgSend$_beginDeviceQueryWithSources:response:
+ _objc_msgSend$_fetchAndUpdateSiriStatus
+ _objc_msgSend$_startDeviceQueryRetryTimerWithEventHandler:
+ _objc_msgSend$_startMonitoringSiriStatus
+ _objc_msgSend$_stopMonitoringSiriStatus
+ _objc_msgSend$_stopSearchForSources:
+ _objc_msgSend$beginDeviceQueryWithSources:response:
+ _objc_msgSend$discoverySource
+ _objc_msgSend$discoverySources
+ _objc_msgSend$removeObjectsForKeys:
+ _objc_msgSend$setDiscoverySources:
- -[TVRCXPCClient _beginDeviceQueryWithResponse:]
- -[TVRCXPCClient _startDeviceQueryRetryTimerWithEventHander:]
- -[TVRCXPCClient beginDeviceQueryWithResponse:]
- -[TVRXDeviceQuery _stopSearch]
- ___46-[TVRCXPCClient beginDeviceQueryWithResponse:]_block_invoke
- ___47-[TVRCXPCClient _beginDeviceQueryWithResponse:]_block_invoke
- ___60-[TVRCXPCClient _startDeviceQueryRetryTimerWithEventHander:]_block_invoke
- _objc_msgSend$_beginDeviceQueryWithResponse:
- _objc_msgSend$_startDeviceQueryRetryTimerWithEventHander:
- _objc_msgSend$_stopSearch
- _objc_msgSend$beginDeviceQueryWithResponse:
CStrings:
+ "(unknown: 0x%lx)"
+ "-[TVRCRPCompanionLinkClientWrapper _startMonitoringSiriStatus]"
+ "-[TVRCRPCompanionLinkClientWrapper _stopMonitoringSiriStatus]"
+ "1"
+ "3"
+ "<TVRXDeviceQuery %p> dropping %lu device(s) no longer covered by discovery sources %{public}@."
+ "<TVRXDeviceQuery %p> has MatchPoint enabled."
+ "<TVRXDeviceQuery %p> skipping MatchPoint discovery"
+ "<TVRXDeviceQuery %p> skipping Rapport discovery"
+ "<TVRXDeviceQuery %p> starting search with discovery sources %{public}@."
+ "<TVRXDeviceQuery %p> stopping search for discovery sources %{public}@."
+ "All"
+ "Asking tvremoted to begin device query with discovery sources %{public}@ remoteObject:%@"
+ "Companion"
+ "Device query already active in this process; this query's discovery sources (%{public}@) will be ignored"
+ "Not starting device query: discovery sources %{public}@ contain no known source"
+ "Received SiriStatusInfo: %@"
+ "Updating deviceState: %@ of discovered device:%@"
+ "|"
- "Asking tvremoted to begin device query with remoteObject:%@"
```
