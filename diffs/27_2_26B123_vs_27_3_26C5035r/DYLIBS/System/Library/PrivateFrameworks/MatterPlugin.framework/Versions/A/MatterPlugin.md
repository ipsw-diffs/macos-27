## MatterPlugin

> `/System/Library/PrivateFrameworks/MatterPlugin.framework/Versions/A/MatterPlugin`

```diff

-89.0.0.0.0
-  __TEXT.__text: 0x4d48c
-  __TEXT.__objc_methlist: 0x49e4
+93.0.0.0.0
+  __TEXT.__text: 0x4e53c
+  __TEXT.__objc_methlist: 0x4aac
   __TEXT.__const: 0xf8
-  __TEXT.__cstring: 0x13ab
-  __TEXT.__oslogstring: 0x5c0f
-  __TEXT.__gcc_except_tab: 0x1b30
-  __TEXT.__unwind_info: 0x16c8
+  __TEXT.__cstring: 0x1416
+  __TEXT.__oslogstring: 0x5cc9
+  __TEXT.__gcc_except_tab: 0x1bd8
+  __TEXT.__unwind_info: 0x1730
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1c0
+  __DATA_CONST.__const: 0x1e0
   __DATA_CONST.__objc_classlist: 0x220
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1d30
+  __DATA_CONST.__objc_selrefs: 0x1de8
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x188
   __DATA_CONST.__objc_arraydata: 0x288
   __DATA_CONST.__got: 0x460
-  __AUTH_CONST.__const: 0xbb0
+  __AUTH_CONST.__const: 0xc00
   __AUTH_CONST.__cfstring: 0x1a80
-  __AUTH_CONST.__objc_const: 0x6c38
+  __AUTH_CONST.__objc_const: 0x6cf8
   __AUTH_CONST.__objc_intobj: 0x990
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x1450
-  __DATA.__objc_ivar: 0x3b0
+  __DATA.__objc_ivar: 0x3c0
   __DATA.__data: 0x600
-  __DATA.__bss: 0xd0
+  __DATA.__bss: 0xd8
   __DATA.__common: 0x8
   __DATA_DIRTY.__objc_data: 0xf0
   __DATA_DIRTY.__bss: 0x80

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1753
-  Symbols:   3543
-  CStrings:  608
+  Functions: 1772
+  Symbols:   3593
+  CStrings:  616
 
Symbols:
+ +[MTRPluginClientXPCProxy _connectionQueueBusy]
+ +[MTRPluginClientXPCProxy connectionQueueBusyBegin]
+ +[MTRPluginClientXPCProxy connectionQueueBusyEnd]
+ -[MTRPluginClientConnection _deliverMessagePayloadToPrimaryResident:timeout:responseHandler:completion:]
+ -[MTRPluginClientXPCProxy _hasSendWindowLocked]
+ -[MTRPluginClientXPCProxy _sendBarrierCompleted]
+ -[MTRPluginClientXPCProxy _sendIssued]
+ -[MTRPluginClientXPCProxy _sendLocked:]
+ -[MTRPluginClientXPCProxy callsQueuedSinceSendBarrierCount]
+ -[MTRPluginClientXPCProxy disconnected]
+ -[MTRPluginClientXPCProxy inFlightSendCount]
+ -[MTRPluginClientXPCProxy pendingCalls]
+ -[MTRPluginClientXPCProxy queuedSendCount]
+ -[MTRPluginClientXPCProxy setCallsQueuedSinceSendBarrierCount:]
+ -[MTRPluginClientXPCProxy setDisconnected:]
+ -[MTRPluginClientXPCProxy setInFlightSendCount:]
+ -[MTRPluginClientXPCProxy setQueuedSendCount:]
+ -[MTRPluginProtobufOverModernTransport _sendMessageToPrimaryHomeHub:throughConnections:timeout:metric:]
+ -[MTRPluginRemoteClient _sendControllerConfiguration:controller:completion:]
+ -[MTRPluginRemoteClient registrationAwaitingClear]
+ -[MTRPluginRemoteClient residentMayHoldUnclearedRegistration]
+ -[MTRPluginRemoteClient setRegistrationAwaitingClear:]
+ -[MTRPluginRemoteClient setResidentMayHoldUnclearedRegistration:]
+ -[MTRPluginRemoteSessionManager _acceptsRelayedReportForNodeID:homeUUID:]
+ GCC_except_table26
+ GCC_except_table38
+ GCC_except_table48
+ GCC_except_table58
+ GCC_except_table6
+ GCC_except_table68
+ GCC_except_table7
+ _OBJC_IVAR_$_MTRPluginClientXPCProxy._callsQueuedSinceSendBarrierCount
+ _OBJC_IVAR_$_MTRPluginClientXPCProxy._disconnected
+ _OBJC_IVAR_$_MTRPluginClientXPCProxy._inFlightSendCount
+ _OBJC_IVAR_$_MTRPluginClientXPCProxy._pendingCalls
+ _OBJC_IVAR_$_MTRPluginClientXPCProxy._queuedSendCount
+ _OBJC_IVAR_$_MTRPluginRemoteClient._registrationAwaitingClear
+ _OBJC_IVAR_$_MTRPluginRemoteClient._residentMayHoldUnclearedRegistration
+ __OBJC_$_CLASS_METHODS_MTRPluginClientXPCProxy
+ ___103-[MTRPluginProtobufOverModernTransport _sendMessageToPrimaryHomeHub:throughConnections:timeout:metric:]_block_invoke
+ ___104-[MTRPluginClientConnection _deliverMessagePayloadToPrimaryResident:timeout:responseHandler:completion:]_block_invoke
+ ___39-[MTRPluginClientXPCProxy _sendLocked:]_block_invoke
+ ___76-[MTRPluginRemoteClient _sendControllerConfiguration:controller:completion:]_block_invoke
+ ___block_descriptor_32_e65_q24?0"MTRPluginClientConnection"8"MTRPluginClientConnection"16l
+ ___block_descriptor_56_e8_32s40bs48w_e5_v8?0l
+ ___block_descriptor_57_e8_32s40s48bs_e8_v16?08l
+ ___block_descriptor_64_e8_32s40s48bs56bs_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48bs56bs_e5_v8?0l
+ ___block_descriptor_80_e8_32s40s48s56s64s_e8_v12?0B8l
+ ___clientConnectionsForMessage_block_invoke
+ _clientConnectionsForMessage
+ _objc_msgSend$_acceptsRelayedReportForNodeID:homeUUID:
+ _objc_msgSend$_connectionQueueBusy
+ _objc_msgSend$_deliverMessagePayloadToPrimaryResident:timeout:responseHandler:completion:
+ _objc_msgSend$_hasSendWindowLocked
+ _objc_msgSend$_sendBarrierCompleted
+ _objc_msgSend$_sendControllerConfiguration:controller:completion:
+ _objc_msgSend$_sendIssued
+ _objc_msgSend$_sendLocked:
+ _objc_msgSend$_sendMessageToPrimaryHomeHub:throughConnections:timeout:metric:
+ _objc_msgSend$callsQueuedSinceSendBarrierCount
+ _objc_msgSend$compare:
+ _objc_msgSend$connectionQueueBusyBegin
+ _objc_msgSend$connectionQueueBusyEnd
+ _objc_msgSend$disconnected
+ _objc_msgSend$firstObject
+ _objc_msgSend$inFlightSendCount
+ _objc_msgSend$insertObject:atIndex:
+ _objc_msgSend$messageWithName:qualityOfService:destination:payload:
+ _objc_msgSend$pendingCalls
+ _objc_msgSend$queuedSendCount
+ _objc_msgSend$registrationAwaitingClear
+ _objc_msgSend$removeObjectAtIndex:
+ _objc_msgSend$residentMayHoldUnclearedRegistration
+ _objc_msgSend$setByAddingObject:
+ _objc_msgSend$setCallsQueuedSinceSendBarrierCount:
+ _objc_msgSend$setDisconnected:
+ _objc_msgSend$setInFlightSendCount:
+ _objc_msgSend$setQueuedSendCount:
+ _objc_msgSend$setRegistrationAwaitingClear:
+ _objc_msgSend$setResidentMayHoldUnclearedRegistration:
+ _objc_msgSend$sortUsingComparator:
+ _objc_msgSend$subarrayWithRange:
+ _objc_setProperty_nonatomic_copy
+ _sConnectionQueueBusyDepth
- -[MTRPluginClientConnection _deliverMessagePayloadToPrimaryResident:timeout:responseHandler:]
- -[MTRPluginClientXPCProxy callRemoteProxyObject:applyBackpressureCap:]
- -[MTRPluginClientXPCProxy inFlightPossiblyCappedSendCount]
- -[MTRPluginClientXPCProxy lastDropLogNSec]
- -[MTRPluginClientXPCProxy setInFlightPossiblyCappedSendCount:]
- -[MTRPluginClientXPCProxy setLastDropLogNSec:]
- -[MTRPluginClientXPCProxy setSuppressedDropCount:]
- -[MTRPluginClientXPCProxy suppressedDropCount]
- GCC_except_table25
- GCC_except_table29
- GCC_except_table37
- GCC_except_table40
- GCC_except_table47
- GCC_except_table52
- _OBJC_IVAR_$_MTRPluginClientXPCProxy._inFlightPossiblyCappedSendCount
- _OBJC_IVAR_$_MTRPluginClientXPCProxy._lastDropLogNSec
- _OBJC_IVAR_$_MTRPluginClientXPCProxy._suppressedDropCount
- ___70-[MTRPluginClientXPCProxy callRemoteProxyObject:applyBackpressureCap:]_block_invoke
- ___77-[MTRPluginProtobufOverModernTransport _sendMessageToPrimaryHomeHub:timeout:]_block_invoke
- ___93-[MTRPluginClientConnection _deliverMessagePayloadToPrimaryResident:timeout:responseHandler:]_block_invoke
- ___block_descriptor_48_e8_32s40s_e8_v16?08l
- ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSError"8l
- ___block_descriptor_57_e8_32s40bs48w_e5_v8?0l
- ___block_descriptor_64_e8_32s40s48bs_e5_v8?0l
- _clientConnectionForMessage
- _clock_gettime_nsec_np
- _objc_msgSend$_deliverMessagePayloadToPrimaryResident:timeout:responseHandler:
- _objc_msgSend$callRemoteProxyObject:applyBackpressureCap:
- _objc_msgSend$inFlightPossiblyCappedSendCount
- _objc_msgSend$lastDropLogNSec
- _objc_msgSend$messageWithName:destination:payload:
- _objc_msgSend$setInFlightPossiblyCappedSendCount:
- _objc_msgSend$setLastDropLogNSec:
- _objc_msgSend$setSuppressedDropCount:
- _objc_msgSend$suppressedDropCount
CStrings:
+ "!"
+ "%@ Clearing resident registration for controller %@ before registering %@"
+ "%@ Connection %@ refused _deliverMessagePayloadToPrimaryResident"
+ "%@ Deferring registration %@ for controller %@ until the resident answers the clear"
+ "%@ No connection accepted _deliverMessagePayloadToPrimaryResident for message: %@"
+ "%@ disconnecting client, %s: %lu sends in flight, %lu calls queued since the last send barrier, %lu calls queued - dropping them"
+ "Q"
+ "halted"
+ "past the 4096-call cap"
+ "q24@?0@\"MTRPluginClientConnection\"8@\"MTRPluginClientConnection\"16"
+ "v12@?0B8"
- "%@ Failed to _deliverMessagePayloadToPrimaryResident for connection: %@"
- "%@ No connection\u00a0found to _deliverMessagePayloadToPrimaryResident for message: %@"
- "%@ dropping XPC send to client - in-flight count %lu >= cap %lu (%lu drop(s) since last log)"
```
