## accessoryd

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 1216.0.0.0.0
-  __TEXT.__text: 0x18c0ac
+  __TEXT.__text: 0x18b100
   __TEXT.__auth_stubs: 0x1860
   __TEXT.__objc_stubs: 0x9060
-  __TEXT.__objc_methlist: 0x6d9c
+  __TEXT.__objc_methlist: 0x6dbc
   __TEXT.__const: 0x1b31
   __TEXT.__gcc_except_tab: 0x1ec4
   __TEXT.__objc_classname: 0xff5
-  __TEXT.__objc_methname: 0xfa83
-  __TEXT.__objc_methtype: 0x3369
-  __TEXT.__cstring: 0xe530
-  __TEXT.__oslogstring: 0x37314
+  __TEXT.__objc_methname: 0xfaae
+  __TEXT.__objc_methtype: 0x3399
+  __TEXT.__cstring: 0xe802
+  __TEXT.__oslogstring: 0x38365
   __TEXT.__ustring: 0x232
-  __TEXT.__unwind_info: 0x4480
-  __DATA_CONST.__const: 0x9cd8
-  __DATA_CONST.__cfstring: 0x7500
+  __TEXT.__unwind_info: 0x63d0
+  __DATA_CONST.__const: 0x9d88
+  __DATA_CONST.__cfstring: 0x7580
   __DATA_CONST.__objc_classlist: 0x308
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x188

   __DATA_CONST.__objc_arrayobj: 0xd8
   __DATA_CONST.__objc_intobj: 0xf0
   __DATA_CONST.__auth_got: 0xc40
-  __DATA_CONST.__got: 0xc30
+  __DATA_CONST.__got: 0xc50
   __DATA_CONST.__auth_ptr: 0x90
-  __DATA.__objc_const: 0xae58
-  __DATA.__objc_selrefs: 0x3330
+  __DATA.__objc_const: 0xae60
+  __DATA.__objc_selrefs: 0x3338
   __DATA.__objc_ivar: 0x778
   __DATA.__objc_data: 0x1e50
   __DATA.__data: 0x1910

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsysdiagnose.dylib
-  Functions: 8230
-  Symbols:   10763
-  CStrings:  8554
+  Functions: 8226
+  Symbols:   10791
+  CStrings:  8624
 
Symbols:
+ -[ACCTransportPluginManager endpointForConnectionWithUUID:forProtocol:]
+ GCC_except_table232
+ GCC_except_table249
+ GCC_except_table260
+ ____configStream_endpoint_copyOOBPairingEndpointUUID_block_invoke
+ ____configStream_endpoint_handleInternalCategoriesRequest_block_invoke
+ ____configStream_endpoint_sendOOBPairingConfigStreamMessage_block_invoke
+ ___acc_endpoint2_setParentEndpointDataSendTypeHandler_block_invoke
+ ___block_descriptor_32_e59_v48?0^v8^{__CFString=}16^{__CFString=}24^?32^{__CFData=}40l
+ ___configStream_endpoint_create_block_invoke
+ __acc_endpoint2_setParentEndpointDataSendTypeHandler_block_invoke
+ __configStream_endpoint_copyExpectedInternalClient
+ __configStream_endpoint_oobPairingSendHandler
+ __configStream_endpoint_sendMessageToOOBPairingEndpoint
+ __configStream_endpoint_sendOOBPairingConfigStreamMessage
+ __configStream_endpoint_setupOOBPairingEndpointPath
+ __oobPairing_endpoint_handlePairingInfo
+ __oobPairing_endpoint_processOOBPairingEarlyInfo
+ _acc_connection2_getOOBPairingPlatformID_internal
+ _acc_endpoint2_setParentEndpointDataSendTypeHandler
+ _configStream_endpoint_copyExpectedInternalClient
+ _configStream_endpoint_oobPairingSendHandler
+ _configStream_endpoint_sendMessageToOOBPairingEndpoint
+ _kCFACCProperties_Connection_Inductive_ExtendedID
+ _kCFACCProperties_Connection_Inductive_FamilyID
+ _kCFACCProperties_Connection_OOBPairingEarlyInfoBDADDR
+ _kCFACCProperties_Connection_OOBPairingEarlyInfoSessionState
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _oobPairing_endpoint_clearOOBPairingEarlyInfo
- GCC_except_table229
- GCC_except_table240
- GCC_except_table257
- ____configStream_endpoint_connectionInfo_categoryListReady_block_invoke
CStrings:
+ "%s: %@, accessoryPlatformID 0x%x -> 0x%lx"
+ "%s: %@, accessoryPlatformID 0x%x -> 0x%x, override %ld"
+ "%s: %@, defer configStream RequestGetProperty(%d) : OOBInfo(%d) : AccessoryOOBData(%d)"
+ "%s: %@, delay between SetPropertyValue and RequestGetProperty %ld ms"
+ "%s: %@, familyID %@, extendedID %@, deviceType %@, accessoryPlatformID 0x%x"
+ "%s: %@, messageID %d, pairingType %d, paylaodLen %ld"
+ "%s: %@, overridePlatformID %ld"
+ "%s: %@, send configStream SetPropertyValue(%d) : OOBInfo(%d) : DeviceBDADDR(%d), %ld bytes"
+ "%s: BDADDR %@ -> %@, sessionState %d -> %d"
+ "%s: BD_ADDR cleared, releasing stale cachedOOBPairingInfo %@"
+ "%s: No change: BDADDR %@, sessionState %d"
+ "%s: bdAddr %@ is invalid!!"
+ "%s: bdAddrChanged %d, everUpdated %d, pairType %d, payload %@ pairInfoList %@"
+ "%s: cfSessionState %@ is invalid!!"
+ "%s: clientStarted %d, everUpdated %d, newSessionState %d, newBDADDR %@"
+ "%s: clientStarted %d, wasFirstBDADDRUpdate %d, sessionStateChanged %d, bdAddrChanged %d"
+ "%s: connectionUUID %@, endpointUUID %@, protocol %{coreacc:ACCEndpoint_Protocol_t}d"
+ "%s: didn't find endpoint of protocol %{coreacc:ACCEndpoint_Protocol_t}d for connectionUUID %@"
+ "%s: endpoint: %@, oobPairing not supported"
+ "%s: failed to set parent endpoint UUID %@ for OOBPairing endpoint %@"
+ "%s: failed to setParentEndpointDataSendTypeHandler for oobPairing endpoint %@, parent %@"
+ "%s: sessionStateChanged %d, everUpdated %d -> %d, needFirstBDADDRUpdate %d -> %d"
+ "%s:%d platformID = %d, accessoryPlatformID = %@, accInfoOverrideDict = %@"
+ "-[ACCTransportPluginManager endpointForConnectionWithUUID:forProtocol:]"
+ "@\"NSString\"28@0:8@\"NSString\"16i24"
+ "@28@0:8@16i24"
+ "BLEPairingConfigRequestDelayMs"
+ "BLEPairingDisableOOBPPlusFlow"
+ "BLEPairingDontEarlyInfoAsDeviceUID"
+ "ERROR: Invalid messageID (%d) for OOBPairing transmit, sourceEndpointUUID %@, parentEndpointUUID %@"
+ "ERROR: Unable to match connection for sourceEndpointUUID %@, parentEndpointUUID %@"
+ "Forwarding data from endpoint %@ to parent endpoint %@, dataSendHandler %d, data length %ld"
+ "Parent endpoint %@ not found"
+ "PlatformIDOverride"
+ "Resetting parentEndpoint(%@) data send handler for endpoint %@"
+ "Send OOBPairing Info for endpoint: %@ bleUUID: %@, save to cachedDeviceBDADDR %@"
+ "Setting parentEndpoint(%@) data send handler for endpoint %@"
+ "_configStream_endpoint_createOOBPairingEndpoint"
+ "_configStream_endpoint_sendOOBPairingConfigStreamMessage"
+ "_configStream_endpoint_sendOOBPairingConfigStreamMessage_block_invoke"
+ "_configStream_endpoint_setupOOBPairingEndpointPath"
+ "_oobPairing_endpoint_copyConnectionEarlyInfoBDADDR"
+ "_oobPairing_endpoint_getConnectionEarlyInfoSessionState"
+ "_oobPairing_endpoint_processOOBPairingEarlyInfo"
+ "acc_connection2_getOOBPairingPlatformID_internal"
+ "configStream %@: oobPairing messageID %d from sourceEndpoint %@, data length %ld"
+ "configStream (manager2) createOOBPairingEndpoint for configStream endpoint: %@"
+ "configStream (manager2) created and published oobPairing endpoint %@ with parent %@, success %d"
+ "configStream (manager2) failed to create OOBPairing endpoint for connection %@"
+ "configStream (manager2) failed to get OOBPairing endpoint struct %@"
+ "configStream (manager2) failed to publish oobPairing endpoint %@"
+ "configStream (manager2) failed to set parent endpoint UUID %@ for OOBPairing endpoint %@"
+ "configStream (manager2) sendMessageToOOBPairingEndpoint: OOB endpoint %@ not on same connection as configStream endpoint %@"
+ "configStream checkOOBPairingMessage for configStream endpoint: %@, categoryID 0x%x / propertyID 0x%x"
+ "configStream checkOOBPairingMessage for configStream endpoint: %@, categoryID 0x%x / propertyID 0x%x -> oobPairingMessage 0x%x"
+ "configStream checkOOBPairingSupport for endpoint: %@, supportsOOBPairing %d"
+ "configStream handleInternalCategoriesRequest for endpoint: %@, Failed to get endpoint struct for oobPairingEndpoint %@ !!!"
+ "configStream handleInternalCategoriesRequest for endpoint: %@, create new oobPairingEndpoint!"
+ "configStream handleInternalCategoriesRequest for endpoint: %@, oobPairingEndpoint %@ already exists!"
+ "configStream processIncomingPairingInfoData: Invalid propertyValue length %lu"
+ "configStream processOOBPairingInfoData for endpoint: %@, clientUID %@, categoryID 0x%x, propertyID %u, propertyValue %@, unknown messageID %u !!!"
+ "configStream processOOBPairingInfoData for endpoint: %@, clientUID %@, internal request: categoryID 0x%x, propertyID %u, propertyValue %@"
+ "configStream sendMessageToOOBPairingEndpoint: %@, messageID %d, pairingType %d, oobPairingValueLen %d, dataIn %@"
+ "configStream sendMessageToOOBPairingEndpoint: Failed to send!!! oobPairingEndpointUUID %@, messageID %d, pairingType %d, oobPairingValueLen %d"
+ "configStream setupOOBPairingEndpointPath for configStream endpoint: %@"
+ "configStream: oobPairing endpoint %@ sending data through configStream endpoint %@, data length %ld"
+ "endpointForConnectionWithUUID:forProtocol:"
+ "oobPairing data received from endpoint %@, converted to configStream operation... ignored %d"
+ "oobPairing_endpoint_clearOOBPairingEarlyInfo"
+ "v48@?0^v8^{__CFString=}16^{__CFString=}24^?32^{__CFData=}40"
```
