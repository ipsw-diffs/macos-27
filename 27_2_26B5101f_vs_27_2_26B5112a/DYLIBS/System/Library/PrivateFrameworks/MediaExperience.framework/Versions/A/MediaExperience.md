## MediaExperience

> `/System/Library/PrivateFrameworks/MediaExperience.framework/Versions/A/MediaExperience`

```diff

-385.10.1.0.0
-  __TEXT.__text: 0x93e88
+385.10.5.1.0
+  __TEXT.__text: 0x965c8
   __TEXT.__delay_helper: 0xdc
   __TEXT.__lazy_helpers: 0xa8
   __TEXT.__objc_methlist: 0x1e54
   __TEXT.__const: 0x1f8
-  __TEXT.__cstring: 0x11ee2
-  __TEXT.__oslogstring: 0xfc52
-  __TEXT.__gcc_except_tab: 0x1010
+  __TEXT.__cstring: 0x1220b
+  __TEXT.__oslogstring: 0x10564
+  __TEXT.__gcc_except_tab: 0x10c4
   __TEXT.__dlopen_cstrs: 0x16e
-  __TEXT.__unwind_info: 0x23c8
+  __TEXT.__unwind_info: 0x2438
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0xf8
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x13d8
+  __DATA_CONST.__objc_selrefs: 0x1400
   __DATA_CONST.__objc_superrefs: 0xd8
   __DATA_CONST.__objc_arraydata: 0x70
-  __DATA_CONST.__got: 0x810
-  __AUTH_CONST.__const: 0x2410
-  __AUTH_CONST.__cfstring: 0xade0
+  __DATA_CONST.__got: 0x818
+  __AUTH_CONST.__const: 0x2460
+  __AUTH_CONST.__cfstring: 0xae00
   __AUTH_CONST.__objc_const: 0x3378
   __AUTH_CONST.__lazy_load_got: 0x8
   __AUTH_CONST.__objc_dictobj: 0x118
-  __AUTH_CONST.__objc_intobj: 0xc0
+  __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x438
   __DATA.__objc_ivar: 0x2c0
   __DATA.__data: 0x3b4
-  __DATA.__bss: 0x3f8
+  __DATA.__bss: 0x408
   __DATA.__common: 0x1d0
   __DATA_DIRTY.__objc_data: 0x578
   __DATA_DIRTY.__bss: 0x6fc

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2765
-  Symbols:   5264
-  CStrings:  2928
+  Functions: 2797
+  Symbols:   5296
+  CStrings:  2973
 
Symbols:
+ FigRoutingManagerContextUtilities_ClearPersistedNANRouteInfo
+ FigRoutingManagerContextUtilities_CopyPersistedNANRouteInfo
+ FigRoutingManagerContextUtilities_SetPersistedNANRouteInfo
+ GCC_except_table226
+ GCC_except_table31
+ MX_FeatureFlags_AreMacNANRouteEnhancementsEnabled
+ MX_FeatureFlags_AreMacNANRouteEnhancementsEnabled.areMacNANRouteEnhancementsEnabled
+ MX_FeatureFlags_AreMacNANRouteEnhancementsEnabled.onceToken
+ _CFStringCompare
+ _FigRoutingManagerContextUtilities_ClearPersistedNANRouteInfo
+ _FigRoutingManagerContextUtilities_CopyPersistedNANRouteInfo
+ _FigRoutingManagerContextUtilities_SetPersistedNANRouteInfo
+ _FigRoutingManagerCopyNANEndpointFromPickedEndpoints
+ _FigRoutingManagerIsNANEndpointPresentInPickedEndpoints
+ _MX_FeatureFlags_AreMacNANRouteEnhancementsEnabled
+ _OBJC_CLASS_$_NSOperationQueue
+ ___FigRoutingManagerContextUtilities_ClearPersistedNANRouteInfo_block_invoke
+ ___FigRoutingManagerContextUtilities_CopyPersistedNANRouteInfo_block_invoke
+ ___FigRoutingManagerContextUtilities_SetPersistedNANRouteInfo_block_invoke
+ ___MX_FeatureFlags_AreMacNANRouteEnhancementsEnabled_block_invoke
+ ___block_descriptor_64_e8_32o40r_e24_v16?0"NSNotification"8l
+ ___routingManager_waitForRouteDiscovery_block_invoke
+ __routingManager_endpointUIAgentEventCallback_block_invoke
+ _objc_msgSend$dateWithTimeIntervalSinceNow:
+ _objc_msgSend$setMaxConcurrentOperationCount:
+ _objc_msgSend$setName:
+ _objc_msgSend$signal
+ _objc_msgSend$waitUntilDate:
+ _routingContextUtilities_clearPersistedNANRouteUID
+ _routingContextUtilities_copyEndpointID
+ _routingContextUtilities_copyEndpointName
+ _routingManager_saveNANRouteIfApplicable
CStrings:
+ "-FigRoutingManagerContextUtilities- %s: Clearing persisted NAN route"
+ "-FigRoutingManagerContextUtilities- %s: Clearing persisted NAN route - UID=%{private}@, Name=%{public}@"
+ "-FigRoutingManagerContextUtilities- %s: Persisting NAN route - UID=%{private}@, Name=%{public}@"
+ "-FigRoutingManager_macOS- %s: Attempting to find Route %{public}@ in discovery"
+ "-FigRoutingManager_macOS- %s: Attempting to restore NAN route - UID=%{private}@, Name=%{public}@"
+ "-FigRoutingManager_macOS- %s: Attempting to restore persisted NAN route - UID=%{private}@, Name=%{public}@"
+ "-FigRoutingManager_macOS- %s: Endpoint with UID %{private}@ (Name: %{public}@) not available from discovery, cannot restore"
+ "-FigRoutingManager_macOS- %s: Endpoint with UID %{public}@ not found in discovery"
+ "-FigRoutingManager_macOS- %s: Expanded subendpoints: IDs=%{private}@, Names=%{public}@"
+ "-FigRoutingManager_macOS- %s: Failed to allocate endpointIDs array"
+ "-FigRoutingManager_macOS- %s: Failed to allocate endpointNames array"
+ "-FigRoutingManager_macOS- %s: Failed to create route discoverer, err=%d"
+ "-FigRoutingManager_macOS- %s: Failed to get system audio context UUID"
+ "-FigRoutingManager_macOS- %s: Found endpoint connected over NAN at index %ld"
+ "-FigRoutingManager_macOS- %s: No NAN endpoint found in picked endpoints"
+ "-FigRoutingManager_macOS- %s: No NAN endpoint to persist"
+ "-FigRoutingManager_macOS- %s: No endpoint connected over NAN found in array of %ld endpoints"
+ "-FigRoutingManager_macOS- %s: No persisted NAN route UID to restore"
+ "-FigRoutingManager_macOS- %s: No picked endpoints to check for NAN"
+ "-FigRoutingManager_macOS- %s: No subendpoints found (subEndpoints = NULL)"
+ "-FigRoutingManager_macOS- %s: Picked endpoints: IDs=%{private}@, Names=%{public}@"
+ "-FigRoutingManager_macOS- %s: Saving NAN route for sleep/wake recovery - UID=%{private}@, Name=%{public}@"
+ "-FigRoutingManager_macOS- %s: Selecting restored NAN route: %{public}@"
+ "-FigRoutingManager_macOS- %s: Successfully discovered endpoint - UID=%{public}@, Name=%{public}@"
+ "-FigRoutingManager_macOS- %s: Timeout occurred when discovering route with UID: %{public}@"
+ "-FigRoutingManager_macOS- %s: endpoints array is empty"
+ "-FigRoutingManager_macOS- %s: endpoints parameter is NULL"
+ "-FigRoutingManager_macOS- %s: routeUID is NULL"
+ "-MX_FeatureFlags- %s: MediaExperience/MacNANRouteEnhancements feature is %{public}s"
+ "01:07:11"
+ "FigRoutingManagerContextUtilities_ClearPersistedNANRouteInfo"
+ "FigRoutingManagerContextUtilities_ClearPersistedNANRouteInfo_block_invoke"
+ "FigRoutingManagerContextUtilities_CopyPersistedNANRouteInfo"
+ "FigRoutingManagerContextUtilities_SetPersistedNANRouteInfo"
+ "FigRoutingManagerContextUtilities_SetPersistedNANRouteInfo_block_invoke"
+ "FigRoutingManagerCopyNANEndpointFromPickedEndpoints"
+ "MX_FeatureFlags_AreMacNANRouteEnhancementsEnabled_block_invoke"
+ "MacNANRouteEnhancements"
+ "Oct 10 2026"
+ "com.apple.coremedia.macosrouting.discovery"
+ "routingContextUtilities_copyEndpointConnectedOverNAN"
+ "routingContextUtilities_copyEndpointIDs"
+ "routingContextUtilities_copyEndpointNames"
+ "routingManager_discoverAndCopyEndpointWithUID"
+ "routingManager_restoreNANRouteIfApplicable"
+ "routingManager_saveNANRouteIfApplicable"
+ "routingManager_waitForRouteDiscovery"
- "04:41:47"
- "Sep 26 2026"
```
