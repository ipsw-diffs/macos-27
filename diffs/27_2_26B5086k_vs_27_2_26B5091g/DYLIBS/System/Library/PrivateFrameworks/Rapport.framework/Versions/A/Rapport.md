## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Versions/A/Rapport`

```diff

-751.200.31.0.0
-  __TEXT.__text: 0xe024c
-  __TEXT.__objc_methlist: 0x9f80
-  __TEXT.__cstring: 0x13d7c
+751.200.41.0.0
+  __TEXT.__text: 0xe2270
+  __TEXT.__objc_methlist: 0xa130
+  __TEXT.__cstring: 0x1453c
   __TEXT.__const: 0x41b8
-  __TEXT.__gcc_except_tab: 0x14b0
+  __TEXT.__gcc_except_tab: 0x14f0
   __TEXT.__oslogstring: 0x26fd
   __TEXT.__swift5_typeref: 0xc4f
   __TEXT.__swift5_capture: 0x950

   __TEXT.__swift5_builtin: 0x50
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x3b68
+  __TEXT.__unwind_info: 0x3c08
   __TEXT.__eh_frame: 0x960
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x12f8
-  __DATA_CONST.__objc_classlist: 0x2d0
+  __DATA_CONST.__objc_classlist: 0x2d8
   __DATA_CONST.__objc_catlist: 0x20
-  __DATA_CONST.__objc_protolist: 0x160
+  __DATA_CONST.__objc_protolist: 0x170
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x44d8
-  __DATA_CONST.__objc_protorefs: 0xf0
-  __DATA_CONST.__objc_superrefs: 0x1f0
+  __DATA_CONST.__objc_selrefs: 0x4580
+  __DATA_CONST.__objc_protorefs: 0x100
+  __DATA_CONST.__objc_superrefs: 0x1f8
   __DATA_CONST.__objc_arraydata: 0xb0
-  __DATA_CONST.__got: 0x4e0
-  __AUTH_CONST.__const: 0x3e70
-  __AUTH_CONST.__cfstring: 0x60e0
-  __AUTH_CONST.__objc_const: 0x11368
+  __DATA_CONST.__got: 0x4e8
+  __AUTH_CONST.__const: 0x3f00
+  __AUTH_CONST.__cfstring: 0x6140
+  __AUTH_CONST.__objc_const: 0x115f0
   __AUTH_CONST.__objc_intobj: 0x258
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0xfb0
-  __AUTH.__objc_data: 0x1300
-  __AUTH.__data: 0x520
-  __DATA.__objc_ivar: 0x10f0
-  __DATA.__data: 0x2138
-  __DATA.__bss: 0x2e30
+  __AUTH_CONST.__auth_got: 0xfc0
+  __AUTH.__objc_data: 0x50
+  __DATA.__objc_ivar: 0x1114
+  __DATA.__data: 0x738
+  __DATA.__bss: 0x2e20
   __DATA.__common: 0x68
-  __DATA_DIRTY.__objc_data: 0x1318
-  __DATA_DIRTY.__data: 0x5f8
-  __DATA_DIRTY.__bss: 0xd8
+  __DATA_DIRTY.__objc_data: 0x2618
+  __DATA_DIRTY.__data: 0x2650
+  __DATA_DIRTY.__bss: 0xe8
   __DATA_DIRTY.__common: 0x28
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5814
-  Symbols:   8340
-  CStrings:  2997
+  Functions: 5868
+  Symbols:   8429
+  CStrings:  3047
 
Symbols:
+ -[RPAccessPolicyClient .cxx_destruct]
+ -[RPAccessPolicyClient _activateWithPolicy:forService:completion:]
+ -[RPAccessPolicyClient _invalidate]
+ -[RPAccessPolicyClient _invalidated]
+ -[RPAccessPolicyClient _updateState:]
+ -[RPAccessPolicyClient _xpcActivate:completion:]
+ -[RPAccessPolicyClient _xpcInterrupted]
+ -[RPAccessPolicyClient _xpcInvalidated]
+ -[RPAccessPolicyClient _xpcSetup]
+ -[RPAccessPolicyClient accessPermittedHandler]
+ -[RPAccessPolicyClient accessPolicyUpdatedDevices:]
+ -[RPAccessPolicyClient accessRevokedHandler]
+ -[RPAccessPolicyClient activateWithPolicy:forService:completion:]
+ -[RPAccessPolicyClient devices]
+ -[RPAccessPolicyClient dispatchQueue]
+ -[RPAccessPolicyClient init]
+ -[RPAccessPolicyClient invalidate]
+ -[RPAccessPolicyClient invalidationHandler]
+ -[RPAccessPolicyClient policy]
+ -[RPAccessPolicyClient serviceName]
+ -[RPAccessPolicyClient setAccessPermittedHandler:]
+ -[RPAccessPolicyClient setAccessRevokedHandler:]
+ -[RPAccessPolicyClient setDevices:]
+ -[RPAccessPolicyClient setDispatchQueue:]
+ -[RPAccessPolicyClient setInvalidationHandler:]
+ -[RPAccessPolicyClient setState:]
+ -[RPAccessPolicyClient setXpcConnection:]
+ -[RPAccessPolicyClient state]
+ -[RPAccessPolicyClient xpcConnection]
+ GCC_except_table14
+ OBJC_IVAR_$_RPAccessPolicyClient._accessPermittedHandler
+ OBJC_IVAR_$_RPAccessPolicyClient._accessRevokedHandler
+ OBJC_IVAR_$_RPAccessPolicyClient._devices
+ OBJC_IVAR_$_RPAccessPolicyClient._dispatchQueue
+ OBJC_IVAR_$_RPAccessPolicyClient._invalidationHandler
+ OBJC_IVAR_$_RPAccessPolicyClient._policy
+ OBJC_IVAR_$_RPAccessPolicyClient._serviceName
+ OBJC_IVAR_$_RPAccessPolicyClient._state
+ OBJC_IVAR_$_RPAccessPolicyClient._xpcConnection
+ _OBJC_CLASS_$_RPAccessPolicyClient
+ _OBJC_METACLASS_$_RPAccessPolicyClient
+ __33-[RPAccessPolicyClient _xpcSetup]_block_invoke
+ __48-[RPAccessPolicyClient _xpcActivate:completion:]_block_invoke
+ __72-[RPClient updateEndpointAttributes:forService:usingContext:completion:]_block_invoke_3
+ __OBJC_$_INSTANCE_METHODS_RPAccessPolicyClient
+ __OBJC_$_INSTANCE_VARIABLES_RPAccessPolicyClient
+ __OBJC_$_PROP_LIST_RPAccessPolicyClient
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_RPAccessPolicyXPCClientInterface
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_RPAccessPolicyXPCServerInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_RPAccessPolicyXPCClientInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_RPAccessPolicyXPCServerInterface
+ __OBJC_CLASS_PROTOCOLS_$_RPAccessPolicyClient
+ __OBJC_CLASS_RO_$_RPAccessPolicyClient
+ __OBJC_LABEL_PROTOCOL_$_RPAccessPolicyXPCClientInterface
+ __OBJC_LABEL_PROTOCOL_$_RPAccessPolicyXPCServerInterface
+ __OBJC_METACLASS_RO_$_RPAccessPolicyClient
+ __OBJC_PROTOCOL_$_RPAccessPolicyXPCClientInterface
+ __OBJC_PROTOCOL_$_RPAccessPolicyXPCServerInterface
+ __OBJC_PROTOCOL_REFERENCE_$_RPAccessPolicyXPCClientInterface
+ __OBJC_PROTOCOL_REFERENCE_$_RPAccessPolicyXPCServerInterface
+ ___33-[RPAccessPolicyClient _xpcSetup]_block_invoke
+ ___34-[RPAccessPolicyClient invalidate]_block_invoke
+ ___48-[RPAccessPolicyClient _xpcActivate:completion:]_block_invoke
+ ___62-[RPClient endpointContextForService:trustCircles:completion:]_block_invoke_2
+ ___65-[RPAccessPolicyClient activateWithPolicy:forService:completion:]_block_invoke
+ ___72-[RPClient updateEndpointAttributes:forService:usingContext:completion:]_block_invoke_2
+ ___72-[RPClient updateEndpointAttributes:forService:usingContext:completion:]_block_invoke_3
+ ___block_descriptor_49_e8_32s40bs_e27_v24?0"NSSet"8"NSError"16l
+ ___block_descriptor_56_e8_32s40s48bs_e45_v24?0"NSObject<OS_xpc_object>"8"NSError"16l
+ ___block_descriptor_64_e8_32s40s48bs_e5_v8?0l
+ __xpc_type_dictionary
+ _gLogCategory_RPAccessPolicyClient
+ _nw_endpoint_copy_dictionary
+ _nw_endpoint_create_from_dictionary
+ _objc_msgSend$_activateWithPolicy:forService:completion:
+ _objc_msgSend$_updateState:
+ _objc_msgSend$_xpcActivate:completion:
+ _objc_msgSend$_xpcInterrupted
+ _objc_msgSend$_xpcInvalidated
+ _objc_msgSend$_xpcSetup
+ _objc_msgSend$accessPolicyClientActivate:serviceName:completion:
+ _objc_msgSend$endpointContextForService:trustCircles:completion:
+ _objc_msgSend$initWithArray:
+ _objc_msgSend$intersectSet:
+ _objc_msgSend$isEqualToSet:
+ _objc_msgSend$minusSet:
+ _objc_msgSend$setDevices:
+ _objc_msgSend$setXPCType:forSelector:argumentIndex:ofReply:
+ _objc_msgSend$updateEncodedEndpoint:forService:usingContext:completion:
CStrings:
+ "-[RPAccessPolicyClient _activateWithPolicy:forService:completion:]"
+ "-[RPAccessPolicyClient _invalidate]"
+ "-[RPAccessPolicyClient _invalidated]"
+ "-[RPAccessPolicyClient _updateState:]"
+ "-[RPAccessPolicyClient _xpcActivate:completion:]"
+ "-[RPAccessPolicyClient _xpcActivate:completion:]_block_invoke"
+ "-[RPAccessPolicyClient _xpcInterrupted]"
+ "-[RPAccessPolicyClient _xpcInvalidated]"
+ "-[RPAccessPolicyClient _xpcSetup]"
+ "-[RPAccessPolicyClient accessPolicyUpdatedDevices:]"
+ "-[RPAccessPolicyClient setDevices:]"
+ "-[RPClient updateEndpointAttributes:forService:usingContext:completion:]_block_invoke"
+ "-[RPClient updateEndpointAttributes:forService:usingContext:completion:]_block_invoke_3"
+ "Access permitted for %@ for %@"
+ "Access revoked for %@ for %@"
+ "Activating with policy %u for %@"
+ "Activation complete for %@ (%lu existing devices)"
+ "Activation failed for %@: %{error}"
+ "Capture"
+ "Cockpit"
+ "Devices changed (%lu -> %lu) for %@: %lu added, %lu removed, %lu unchanged"
+ "Error updating state to %u: %{error}"
+ "Failed to decode endpoint"
+ "Failed to encode endpoint"
+ "Failed to update attributes of endpoint %@ for %@: %{error}"
+ "Ignoring device update (%lu devices) for %@ from daemon in state %u"
+ "Invalid policy %u"
+ "Invalid service name '%@'"
+ "Invalid state transition %u -> %u"
+ "Invalidating"
+ "No change in devices: %@"
+ "No endpoint provided"
+ "RPAccessPolicyClient"
+ "Reactivation complete for %@ (%lu existing devices)"
+ "Reactivation failed for %@: %{error}"
+ "Received device update (%lu devices) for %@ from daemon"
+ "Starting in invalid state %u"
+ "Successfully updated attributes of endpoint %@ for %@: %@"
+ "Unable to activate for %@ with XPC error %{error}"
+ "Unable to activate for %@: %{error}"
+ "Unable to activate: %{error}"
+ "Unable to reactivate for %@ with XPC error %{error}"
+ "Unable to reactivate for %@: %{error}"
+ "Unable to setup XPC in state %u"
+ "Unexpected state %u"
+ "Updating state: %u -> %u"
+ "XPC connection interrupted"
+ "com.apple.rapport.AccessPolicy"
+ "v24@?0@\"NSObject<OS_xpc_object>\"8@\"NSError\"16"
+ "v24@?0@\"NSSet\"8@\"NSError\"16"
```
