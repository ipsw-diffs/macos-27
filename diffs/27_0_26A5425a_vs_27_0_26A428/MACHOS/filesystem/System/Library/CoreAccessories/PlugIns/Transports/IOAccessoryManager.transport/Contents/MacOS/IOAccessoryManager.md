## IOAccessoryManager

> `/System/Library/CoreAccessories/PlugIns/Transports/IOAccessoryManager.transport/Contents/MacOS/IOAccessoryManager`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 1216.0.0.0.0
-  __TEXT.__text: 0x4640c
-  __TEXT.__auth_stubs: 0x1040
-  __TEXT.__objc_stubs: 0x4ae0
-  __TEXT.__objc_methlist: 0x27e8
-  __TEXT.__const: 0x274
-  __TEXT.__cstring: 0x34d9
-  __TEXT.__oslogstring: 0xae5a
-  __TEXT.__objc_methname: 0x76d1
+  __TEXT.__text: 0x496dc
+  __TEXT.__auth_stubs: 0x1050
+  __TEXT.__objc_stubs: 0x4ee0
+  __TEXT.__objc_methlist: 0x2910
+  __TEXT.__const: 0x266
+  __TEXT.__cstring: 0x39d2
+  __TEXT.__oslogstring: 0xbae8
+  __TEXT.__objc_methname: 0x7c61
   __TEXT.__objc_classname: 0x3dc
-  __TEXT.__objc_methtype: 0xf28
-  __TEXT.__gcc_except_tab: 0x77c
+  __TEXT.__objc_methtype: 0xf4e
+  __TEXT.__gcc_except_tab: 0x7bc
   __TEXT.__ustring: 0x146
-  __TEXT.__unwind_info: 0xa20
-  __DATA_CONST.__const: 0x1108
-  __DATA_CONST.__cfstring: 0x2dc0
+  __TEXT.__unwind_info: 0x1038
+  __DATA_CONST.__const: 0x1228
+  __DATA_CONST.__cfstring: 0x2f60
   __DATA_CONST.__objc_classlist: 0x88
   __DATA_CONST.__objc_protolist: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arrayobj: 0x30
   __DATA_CONST.__objc_intobj: 0x60
   __DATA_CONST.__objc_dictobj: 0x50
-  __DATA_CONST.__auth_got: 0x830
-  __DATA_CONST.__got: 0x350
+  __DATA_CONST.__auth_got: 0x838
+  __DATA_CONST.__got: 0x360
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA.__objc_const: 0x4178
-  __DATA.__objc_selrefs: 0x1878
-  __DATA.__objc_ivar: 0x3c0
+  __DATA.__objc_const: 0x4298
+  __DATA.__objc_selrefs: 0x1960
+  __DATA.__objc_ivar: 0x3d8
   __DATA.__objc_data: 0x550
   __DATA.__data: 0x6c4
-  __DATA.__bss: 0x198
+  __DATA.__bss: 0x190
   __DATA.__common: 0x1c
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsysdiagnose.dylib
-  Functions: 1345
-  Symbols:   2856
-  CStrings:  2596
+  Functions: 1381
+  Symbols:   2941
+  CStrings:  2701
 
Symbols:
+ -[ACCTransportIOAccessoryAuthCP _handleBusyComponentAuth]
+ -[ACCTransportIOAccessoryManager _clearOOBPairingEarlyInfo]
+ -[ACCTransportIOAccessoryManager _handleOOBPairingEarlyInfo:]
+ -[ACCTransportIOAccessoryManager _processOOBPairingAccessoryInfoDataProperty]
+ -[ACCTransportIOAccessoryManager _processOOBPairingEarlyInfoChange]
+ -[ACCTransportIOAccessoryManager _processOOBPairingEarlyInfo]
+ -[ACCTransportIOAccessoryManager _processOOBPairingProperty:label:existingData:messageID:completion:]
+ -[ACCTransportIOAccessoryManager oobPairingAccessoryData]
+ -[ACCTransportIOAccessoryManager oobPairingAccessoryInfo]
+ -[ACCTransportIOAccessoryManager oobPairingEarlyInfoBDADDR]
+ -[ACCTransportIOAccessoryManager oobPairingEarlyInfoEndpointUUID]
+ -[ACCTransportIOAccessoryManager oobPairingEarlyInfoSessionState]
+ -[ACCTransportIOAccessoryManager oobPairingEarlyInfo]
+ -[ACCTransportIOAccessoryManager setOobPairingAccessoryData:]
+ -[ACCTransportIOAccessoryManager setOobPairingAccessoryInfo:]
+ -[ACCTransportIOAccessoryManager setOobPairingEarlyInfo:]
+ -[ACCTransportIOAccessoryManager setOobPairingEarlyInfoBDADDR:]
+ -[ACCTransportIOAccessoryManager setOobPairingEarlyInfoEndpointUUID:]
+ -[ACCTransportIOAccessoryManager setOobPairingEarlyInfoSessionState:]
+ -[ACCTransportIOAccessorySharedManager _blePairingTransportTypeForConnectionType:]
+ -[ACCTransportIOAccessorySharedManager _createBLEPairingEndpointForManager:publish:]
+ -[ACCTransportIOAccessorySharedManager _destroyBLEPairingEndpointForManager:]
+ -[ACCTransportIOAccessorySharedManager _handleInductiveOOBPairingTransmitData:forEndpointUUID:manager:]
+ -[ACCTransportIOAccessorySharedManager _managerForInductiveOOBPairingEndpointUUID:]
+ -[ACCTransportIOAccessorySharedManager handleOOBPairingEarlyInfoNotification:]
+ GCC_except_table126
+ GCC_except_table130
+ GCC_except_table44
+ GCC_except_table51
+ GCC_except_table58
+ GCC_except_table65
+ GCC_except_table80
+ OBJC_IVAR_$_ACCTransportIOAccessoryManager._oobPairingAccessoryData
+ OBJC_IVAR_$_ACCTransportIOAccessoryManager._oobPairingAccessoryInfo
+ OBJC_IVAR_$_ACCTransportIOAccessoryManager._oobPairingEarlyInfo
+ OBJC_IVAR_$_ACCTransportIOAccessoryManager._oobPairingEarlyInfoBDADDR
+ OBJC_IVAR_$_ACCTransportIOAccessoryManager._oobPairingEarlyInfoEndpointUUID
+ OBJC_IVAR_$_ACCTransportIOAccessoryManager._oobPairingEarlyInfoSessionState
+ _ACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _ACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _ACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _ACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _ACCUserDefaultsKey_PlatformIDOverride
+ _ACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ _IOAccessoryManagerSetInductiveOOBPairingHostInfo
+ _OUTLINED_FUNCTION_24
+ _OUTLINED_FUNCTION_25
+ __77-[ACCTransportIOAccessoryManager _processOOBPairingAccessoryInfoDataProperty]_block_invoke
+ ___77-[ACCTransportIOAccessoryManager _processOOBPairingAccessoryInfoDataProperty]_block_invoke
+ ___83-[ACCTransportIOAccessorySharedManager _managerForInductiveOOBPairingEndpointUUID:]_block_invoke
+ ___83-[ACCTransportIOAccessorySharedManager _managerForInductiveOOBPairingEndpointUUID:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40s_e27_v24?0"NSData"8"NSData"16l
+ ___block_descriptor_80_e8_32s40r48r56r64r72r_e36_v36?0B8"NSData"12"NSData"20B28i32l
+ ___copy_helper_block_e8_32s40r48r56r64r72r
+ ___destroy_helper_block_e8_32s40r48r56r64r72r
+ _kACCProperties_Connection_OOBPairingEarlyInfoBDADDR
+ _kACCProperties_Connection_OOBPairingEarlyInfoSessionState
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _kCFACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ _objc_msgSend$_blePairingTransportTypeForConnectionType:
+ _objc_msgSend$_clearOOBPairingEarlyInfo
+ _objc_msgSend$_createBLEPairingEndpointForManager:publish:
+ _objc_msgSend$_handleBusyComponentAuth
+ _objc_msgSend$_handleInductiveOOBPairingTransmitData:forEndpointUUID:manager:
+ _objc_msgSend$_handleOOBPairingEarlyInfo:
+ _objc_msgSend$_invalidateAllAccessoryInfoFields
+ _objc_msgSend$_managerForInductiveOOBPairingEndpointUUID:
+ _objc_msgSend$_processOOBPairingAccessoryInfoDataProperty
+ _objc_msgSend$_processOOBPairingEarlyInfo
+ _objc_msgSend$_processOOBPairingEarlyInfoChange
+ _objc_msgSend$_processOOBPairingProperty:label:existingData:messageID:completion:
+ _objc_msgSend$anyObject
+ _objc_msgSend$authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:
+ _objc_msgSend$bIsShuttingDown
+ _objc_msgSend$deferredAuthChallenge
+ _objc_msgSend$endpointForConnectionWithUUID:forProtocol:
+ _objc_msgSend$handleOOBPairingEarlyInfoNotification:
+ _objc_msgSend$initWithBytes:length:
+ _objc_msgSend$isTransientPortLevelAccIDDetachForConnectionType:inductiveDeviceType:oobPairingEarlyInfoEndpoint:
+ _objc_msgSend$oobPairingAccessoryData
+ _objc_msgSend$oobPairingAccessoryInfo
+ _objc_msgSend$oobPairingEarlyInfo
+ _objc_msgSend$oobPairingEarlyInfoBDADDR
+ _objc_msgSend$oobPairingEarlyInfoEndpointUUID
+ _objc_msgSend$oobPairingEarlyInfoSessionState
+ _objc_msgSend$setOobPairingAccessoryData:
+ _objc_msgSend$setOobPairingAccessoryInfo:
+ _objc_msgSend$setOobPairingEarlyInfo:
+ _objc_msgSend$setOobPairingEarlyInfoBDADDR:
+ _objc_msgSend$setOobPairingEarlyInfoEndpointUUID:
+ _objc_msgSend$setOobPairingEarlyInfoSessionState:
- GCC_except_table118
- GCC_except_table122
- GCC_except_table45
- GCC_except_table55
- GCC_except_table62
- GCC_except_table70
- ___block_descriptor_72_e8_32s40r48r56r64r_e36_v36?0B8"NSData"12"NSData"20B28i32l
- ___copy_helper_block_e8_32s40r48r56r64r
- ___destroy_helper_block_e8_32s40r48r56r64r
- systemInfo_isDeveloperBuild.developerBuild
CStrings:
+ "%02x:%02x:%02x:%02x:%02x:%02x"
+ "%s: %@ create OOBPairingEndpoint for manager service %d, inductiveDeviceType %@, oobPairingEarlyInfo %@"
+ "%s: %@ destroy connection for OOBPairingEndpoint for manager service %d, inductiveDeviceType %@, oobPairingEarlyInfo %@"
+ "%s: %@ destroy endpoint for OOBPairingEndpoint for manager service %d, inductiveDeviceType %@, oobPairingEarlyInfo %@, oobPairingEarlyInfoEndpointUUID %@"
+ "%s: %s changed, %lu bytes, endpointUUID %@, %@ -> %@"
+ "%s: %s is zero-length, ignoring"
+ "%s: Create Endpoint ioAccMgr.oobPairingEarlyInfo = %@ (%@, %d), ioAccMgr.connectionUUID = %@,  %{coreacc:ACCConnection_Type_t}d, transportType %{coreacc:ACCEndpoint_TransportType_t}d, accInfoDictionary = %@"
+ "%s: IOAccessoryManagerSetInductiveOOBPairingHostInfo failed 0x%X, endpointUUID %@"
+ "%s: IOAccessoryManagerSetInductiveOOBPairingHostInfo success, endpointUUID %@, payloadLen %lu"
+ "%s: IOServiceOpen failed 0x%X, service %d, endpointUUID %@"
+ "%s: Not enough bytes (%lu) for message header, endpointUUID %@"
+ "%s: Test cfOOBPairingEarlyInfo %@ -> %@"
+ "%s: Unsupported messageID %d for inductive OOBPairing, endpointUUID %@"
+ "%s: connectionType %{coreacc:ACCConnection_Type_t}d -> transportType %{coreacc:ACCEndpoint_TransportType_t}d"
+ "%s: could not find manager object for service %d"
+ "%s: deviceUID %@"
+ "%s: deviceUID %@ -> %@"
+ "%s: endpoint %@ on connection %@ is the manager's OOBPairingEarlyInfo endpoint — connection stays alive until inductiveDeviceType -> 0"
+ "%s: endpointUUID %@, already created for connectionUUID %@"
+ "%s: endpointUUID %@, messageID %d, payloadLen %lu, manager service %d"
+ "%s: familyID %@, extendedID %@, deviceType %@"
+ "%s: found manager service %d for endpointUUID %@"
+ "%s: inductiveDeviceType %@, cfOOBPairingEarlyInfo %@, oobPairingEarlyInfo %@"
+ "%s: inductiveDeviceType %@, oobPairingEarlyInfo %@, self.oobPairingEarlyInfo %@"
+ "%s: inductiveDeviceType %@, oobPairingEarlyInfo: %@, BDADDR %@, SessionState %d, self.connectionUUID %@"
+ "%s: ioAccMgr.oobPairingEarlyInfo = %@ (%@, %d), ioAccMgr.inductiveDeviceType %@, ioAccMgr.connectionUUID = %@, connectionType %{coreacc:ACCConnection_Type_t}d, publish %d"
+ "%s: ioAccMgr.oobPairingEarlyInfo = %@, ioAccMgr.inductiveDeviceType %@, ioAccMgr.connectionUUID = %@, connectionType %{coreacc:ACCConnection_Type_t}d, endpointUUID %@"
+ "%s: oobPairingEarlyInfo SAME: %@ -> %@, BDADDR %@ -> %@, SessionState %d -> %d"
+ "%s: oobPairingEarlyInfo: %@ -> %@, BDADDR %@ -> %@, SessionState %d -> %d"
+ "%s: oobPairingEarlyInfoBDADDR %@"
+ "%s: unexpected CFTypeID for %s property: %lu"
+ "%s: unexpected CFTypeID for oobPairingEarlyInfo property: %lu"
+ "%s: unexpectedly found %lu managers for endpointUUID %@ — returning nil to avoid arbitrary routing"
+ "-[ACCTransportIOAccessoryManager _handleOOBPairingEarlyInfo:]"
+ "-[ACCTransportIOAccessoryManager _processOOBPairingEarlyInfoChange]"
+ "-[ACCTransportIOAccessoryManager _processOOBPairingEarlyInfo]"
+ "-[ACCTransportIOAccessoryManager _processOOBPairingProperty:label:existingData:messageID:completion:]"
+ "-[ACCTransportIOAccessorySharedManager _blePairingTransportTypeForConnectionType:]"
+ "-[ACCTransportIOAccessorySharedManager _createBLEPairingEndpointForManager:publish:]"
+ "-[ACCTransportIOAccessorySharedManager _destroyBLEPairingEndpointForManager:]"
+ "-[ACCTransportIOAccessorySharedManager _handleInductiveOOBPairingTransmitData:forEndpointUUID:manager:]"
+ "-[ACCTransportIOAccessorySharedManager _managerForInductiveOOBPairingEndpointUUID:]"
+ "-[ACCTransportIOAccessorySharedManager handleOOBPairingEarlyInfoNotification:]"
+ "AccessoryData"
+ "AccessoryInfo"
+ "BLEPairingConfigRequestDelayMs"
+ "BLEPairingDisableOOBPPlusFlow"
+ "BLEPairingDontEarlyInfoAsDeviceUID"
+ "BLEPairingIgnoreZeroEarlyInfo"
+ "CertificateSupportsRCAM"
+ "ComponentBusyError"
+ "Got kIOMessageServicePropertyChange (svc:%d) for manager, Insufficient bytes (or all 0) for oobPairingEarlyInfo: %lu, expected valid %d bytes!!!"
+ "IOAccessoryManagerInductiveOOBPairingAccessoryData"
+ "IOAccessoryManagerInductiveOOBPairingAccessoryInfo"
+ "IOAccessoryManagerInductiveOOBPairingEarlyInfo"
+ "PlatformIDOverride"
+ "RCAM"
+ "T@\"NSData\",&,V_oobPairingAccessoryData"
+ "T@\"NSData\",&,V_oobPairingAccessoryInfo"
+ "T@\"NSData\",&,V_oobPairingEarlyInfo"
+ "T@\"NSData\",&,V_oobPairingEarlyInfoBDADDR"
+ "T@\"NSString\",&,V_oobPairingEarlyInfoEndpointUUID"
+ "TC,V_oobPairingEarlyInfoSessionState"
+ "TestCreateBLEPairingOnInductive"
+ "Transient port-level detach (svc:%d): inductiveDeviceType=%@ still non-zero and OOBPairingEarlyInfo endpoint %@ live; skipping detach propagation. Real detach will arrive via inductiveDeviceType -> 0."
+ "_blePairingTransportTypeForConnectionType:"
+ "_clearOOBPairingEarlyInfo"
+ "_createBLEPairingEndpointForManager:publish:"
+ "_destroyBLEPairingEndpointForManager:"
+ "_handleBusyComponentAuth"
+ "_handleInductiveOOBPairingTransmitData:forEndpointUUID:manager:"
+ "_handleOOBPairingEarlyInfo:"
+ "_managerForInductiveOOBPairingEndpointUUID:"
+ "_oobPairingAccessoryData"
+ "_oobPairingAccessoryInfo"
+ "_oobPairingEarlyInfo"
+ "_oobPairingEarlyInfoBDADDR"
+ "_oobPairingEarlyInfoEndpointUUID"
+ "_oobPairingEarlyInfoSessionState"
+ "_processOOBPairingAccessoryInfoDataProperty"
+ "_processOOBPairingEarlyInfo"
+ "_processOOBPairingEarlyInfoChange"
+ "_processOOBPairingProperty:label:existingData:messageID:completion:"
+ "anyObject"
+ "authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:"
+ "endpointForConnectionWithUUID:forProtocol:"
+ "handleOOBPairingEarlyInfoNotification:"
+ "initWithBytes:length:"
+ "kAppleAuthCPMessageDeferredSignatureReceived received.  Re-Starting authentication process."
+ "oobPairingAccessoryData"
+ "oobPairingAccessoryInfo"
+ "oobPairingEarlyInfo"
+ "oobPairingEarlyInfoBDADDR"
+ "oobPairingEarlyInfoEndpointUUID"
+ "oobPairingEarlyInfoSessionState"
+ "prpc"
+ "setFeaturesFromAuthStatus: [%d] authStatus %d, _bIsInductive %d, inductiveFwMode %d, isEspressoOutAccessory %d, supportInductivePowerTX %d -> %d"
+ "setOobPairingAccessoryData:"
+ "setOobPairingAccessoryInfo:"
+ "setOobPairingEarlyInfo:"
+ "setOobPairingEarlyInfoBDADDR:"
+ "setOobPairingEarlyInfoEndpointUUID:"
+ "setOobPairingEarlyInfoSessionState:"
+ "v24@?0@\"NSData\"8@\"NSData\"16"
+ "v52@0:8^{__CFString=}16r*24@32S40@?44"
```
