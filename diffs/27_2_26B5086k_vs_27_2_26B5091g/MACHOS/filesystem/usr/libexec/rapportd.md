## rapportd

> `/usr/libexec/rapportd`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`

```diff

-751.200.31.0.0
-  __TEXT.__text: 0x17a84c
+751.200.41.0.0
+  __TEXT.__text: 0x18179c
   __TEXT.__auth_stubs: 0x3500
-  __TEXT.__objc_stubs: 0x11b00
-  __TEXT.__objc_methlist: 0x8fc8
-  __TEXT.__const: 0x6180
-  __TEXT.__cstring: 0x2fe26
-  __TEXT.__objc_classname: 0xf5f
-  __TEXT.__objc_methtype: 0x44b1
-  __TEXT.__gcc_except_tab: 0x235c
-  __TEXT.__objc_methname: 0x19c80
+  __TEXT.__objc_stubs: 0x12340
+  __TEXT.__objc_methlist: 0x9a20
+  __TEXT.__const: 0x6600
+  __TEXT.__cstring: 0x311c6
+  __TEXT.__objc_classname: 0x102f
+  __TEXT.__objc_methtype: 0x48e1
+  __TEXT.__gcc_except_tab: 0x2364
+  __TEXT.__objc_methname: 0x1b400
   __TEXT.__oslogstring: 0x3222
   __TEXT.__swift5_typeref: 0x178e
   __TEXT.__swift5_capture: 0xb38

   __TEXT.__swift5_protos: 0x4
   __TEXT.__swift5_acfuncs: 0x104
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x6a68
+  __TEXT.__unwind_info: 0x6d08
   __TEXT.__eh_frame: 0x4bbc
-  __DATA_CONST.__const: 0x80c8
-  __DATA_CONST.__cfstring: 0x5f80
-  __DATA_CONST.__objc_classlist: 0x370
+  __DATA_CONST.__const: 0x8138
+  __DATA_CONST.__cfstring: 0x6140
+  __DATA_CONST.__objc_classlist: 0x390
   __DATA_CONST.__objc_catlist: 0x10
-  __DATA_CONST.__objc_protolist: 0x148
+  __DATA_CONST.__objc_protolist: 0x168
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_protorefs: 0xb0
-  __DATA_CONST.__objc_superrefs: 0x1f8
+  __DATA_CONST.__objc_protorefs: 0xc0
+  __DATA_CONST.__objc_superrefs: 0x210
   __DATA_CONST.__objc_intobj: 0x3c0
   __DATA_CONST.__objc_arraydata: 0x58
   __DATA_CONST.__objc_arrayobj: 0x18

   __DATA_CONST.__auth_got: 0x1a90
   __DATA_CONST.__got: 0xa30
   __DATA_CONST.__auth_ptr: 0x660
-  __DATA.__objc_const: 0x107c8
-  __DATA.__objc_selrefs: 0x56a8
-  __DATA.__objc_ivar: 0xfd4
-  __DATA.__objc_data: 0x2bb0
-  __DATA.__data: 0x35c8
-  __DATA.__bss: 0x45a0
+  __DATA.__objc_const: 0x11358
+  __DATA.__objc_selrefs: 0x5be8
+  __DATA.__objc_ivar: 0x1058
+  __DATA.__objc_data: 0x2cf0
+  __DATA.__data: 0x3828
+  __DATA.__bss: 0x45c0
   __DATA.__common: 0xd0
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7844
+  Functions: 8085
   Symbols:   1359
-  CStrings:  9910
+  CStrings:  10288
 
CStrings:
+ "%@ %lu devices, conn %@]"
+ "%@ Resolve post-completion grace expired, invalidating peer\n"
+ "%@ Resolve response delivered, holding CompanionLink for %.0fs grace before invalidating\n"
+ "+[RPNWClientEndpointContext _currentAltDSID]"
+ "+[RPNWClientEndpointContext _currentIDSDeviceID]"
+ "+[RPNWClientEndpointContext _currentStatusFlags]"
+ "+[RPNWClientEndpointContext contextFromNetworkRepresentation:]"
+ ", connected"
+ ", disconnected %@"
+ "-- RPAccessPolicyDaemon --\n"
+ "-[QRServiceDiscoveryClient _localDeviceMonitorActivate]"
+ "-[QRServiceDiscoveryClient _localDeviceMonitorActivate]_block_invoke"
+ "-[QRServiceDiscoveryClient _localDeviceMonitorInterrupted]"
+ "-[QRServiceDiscoveryClient _localDeviceMonitorInvalidate]"
+ "-[QRServiceDiscoveryClient _localDeviceMonitorInvalidated]"
+ "-[QRServiceDiscoveryClient _serviceDiscovery:startAdvertisement:completionHandler:]_block_invoke_2"
+ "-[QRServiceDiscoveryClient _serviceDiscovery:startQuery:completionHandler:]_block_invoke_2"
+ "-[QRServiceDiscoveryClient _serviceDiscovery:stopAdvertisement:completionHandler:]_block_invoke_2"
+ "-[QRServiceDiscoveryClient _serviceDiscovery:stopQuery:completionHandler:]_block_invoke_2"
+ "-[QRServiceDiscoveryClient _serviceDiscovery:updateAdvertisement:metadata:completionHandler:]_block_invoke_2"
+ "-[QRServiceDiscoveryClient _updatePrimaryAltDSID:]"
+ "-[QRServiceDiscoveryClient daemonInfoChanged:]"
+ "-[QRServiceDiscoveryClient regenerateQueryResults:]"
+ "-[QRServiceDiscoveryClient startAdvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]"
+ "-[QRServiceDiscoveryClient startAdvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke"
+ "-[QRServiceDiscoveryClient startAdvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke_2"
+ "-[QRServiceDiscoveryClient startAdvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke_3"
+ "-[RPAccessPolicyDaemon _activate]"
+ "-[RPAccessPolicyDaemon _cLinkActivate]"
+ "-[RPAccessPolicyDaemon _cLinkActivate]_block_invoke_2"
+ "-[RPAccessPolicyDaemon _cLinkDeviceChanged:]"
+ "-[RPAccessPolicyDaemon _cLinkDeviceFound:]"
+ "-[RPAccessPolicyDaemon _cLinkDeviceLost:]"
+ "-[RPAccessPolicyDaemon _cLinkInterrupted]"
+ "-[RPAccessPolicyDaemon _cLinkInvalidate]"
+ "-[RPAccessPolicyDaemon _cLinkInvalidated]"
+ "-[RPAccessPolicyDaemon _invalidate]"
+ "-[RPAccessPolicyDaemon _localStatePermitsAccess]"
+ "-[RPAccessPolicyDaemon _lockTimerFired]"
+ "-[RPAccessPolicyDaemon _lockTimerStart]"
+ "-[RPAccessPolicyDaemon _lockTimerStop]"
+ "-[RPAccessPolicyDaemon _peerExpirationPrune]"
+ "-[RPAccessPolicyDaemon _peerExpirationTimerFired]"
+ "-[RPAccessPolicyDaemon _peerExpirationTimerStart:]"
+ "-[RPAccessPolicyDaemon _peerExpirationTimerStop]"
+ "-[RPAccessPolicyDaemon _xpcHandleLostClient:]"
+ "-[RPAccessPolicyDaemon _xpcHandleNewConnection:]"
+ "-[RPAccessPolicyDaemon listener:shouldAcceptNewConnection:]"
+ "-[RPAccessPolicyDaemon prefsChanged]"
+ "-[RPAccessPolicyXPCConnection accessPolicyClientActivate:serviceName:completion:]"
+ "-[RPAccessPolicyXPCConnection setDevices:]"
+ "-[RPAccessPolicyXPCConnection setDevices:]_block_invoke"
+ "-[RPAccessPolicyXPCConnection setDevices:]_block_invoke_2"
+ "-[RPDaemonXPCConnection endpointContextForService:trustCircles:completion:]"
+ "-[RPDaemonXPCConnection updateEncodedEndpoint:forService:usingContext:completion:]"
+ "-[RPNWClientEndpointContext networkRepresentationForTrustCircles:]"
+ "-[RPNWPeer resolvePeer:token:controlFlags:applicationService:clientPublicKey:resolveHandler:]_block_invoke_2"
+ "-[RPNWPeer resolvePeer:token:controlFlags:applicationService:clientPublicKey:resolveHandler:]_block_invoke_3"
+ "-[RPServiceDiscoveryClient startAdvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke"
+ "-[RPServiceDiscoveryClient startAdvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke_2"
+ "-[RPServiceDiscoveryClient startAdvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke_3"
+ "@\"RPAccessPolicyDaemon\""
+ "@28@0:8@16B24"
+ "Activated"
+ "Activated cLink %@"
+ "Added client (now %lu): %@"
+ "Already activated"
+ "Browser: %@\n"
+ "Daemon info changed: %#ll{flags}"
+ "Failed to activate cLink %@: %{error}"
+ "Failed to activate local device monitor %@: %@"
+ "Failed to decode context"
+ "Failed to decode endpoint"
+ "Failed to encode endpoint"
+ "Failed to obtain AltDSID"
+ "Failed to obtain IDS device ID"
+ "Failed to obtain local device"
+ "GetEndpointContext"
+ "HMHomeDelegatePrivate"
+ "HMHomeManagerDelegate"
+ "IDS Agent UUID"
+ "Invalid policy %u"
+ "Invalid service name '%@'"
+ "Invalidated"
+ "Invalidating cLink %@"
+ "Invalidating local device monitor %@"
+ "Local Device Monitor interrupted"
+ "Local Device Monitor invalidated"
+ "Local primary AltDSID updated: %@ -> %@"
+ "Local state permits access: %c"
+ "Lock timer fired"
+ "Lock timer not needed in state %d"
+ "Lock timer not needed without target time"
+ "Lock timer start %f is in the past"
+ "Lock: State(%d) Last(%@)\n"
+ "Lost client (now %lu): %@"
+ "Missing entitlement to %@ for '%@'"
+ "Next peer prune timer start %@ is in the past"
+ "Nothing to encode for %#ll{flags}"
+ "Now %lu/%lu peers after finding device %@"
+ "Now %lu/%lu peers after losing device %@"
+ "Now %lu/%lu peers after removing expired device %@"
+ "Now %lu/%lu peers after updating device %@"
+ "Peer expiration timer fired"
+ "Peers: Connected(%lu) Previous(%lu)\n"
+ "Policies: RULD(%f) DLD(%f)\n"
+ "Preference override DLD: %f"
+ "Preference override RULD: %f"
+ "Pruning expired previous peers"
+ "RPAccessPolicyDaemon"
+ "RPAccessPolicyDeviceInfo"
+ "RPAccessPolicyXPCClientInterface"
+ "RPAccessPolicyXPCConnection"
+ "RPAccessPolicyXPCServerInterface"
+ "RPNWClientEndpointContext"
+ "Regenerating query results (reason: %@)"
+ "Rejecting new XPC connection %@ from unknown listener %@"
+ "Rejecting unentitled XPC connection from %#{pid}"
+ "Resetting DLD to default"
+ "Resetting RULD to default"
+ "Service %@ exists but requires priority boost"
+ "Setting up local device monitor %@"
+ "Started lock timer (%f s)"
+ "Started peer expiration timer (%f s)"
+ "Stopping lock timer"
+ "Stopping peer expiration timer"
+ "T@\"NSMutableDictionary\",R,N,V_peerDevices"
+ "T@\"NSMutableSet\",R,N,V_xpcClients"
+ "T@\"NSNumber\",&,N,V_lastUnlockTime"
+ "T@\"NSNumber\",R,N,V_lastConnected"
+ "T@\"NSObject<OS_dispatch_source>\",&,N,V_lockTimer"
+ "T@\"NSObject<OS_dispatch_source>\",&,N,V_peerExpirationTimer"
+ "T@\"NSSet\",&,N,V_devices"
+ "T@\"NSString\",&,N,V_primaryAltDSID"
+ "T@\"NSString\",C,N,V_iCloudAltDSID"
+ "T@\"NSString\",C,N,V_idsDeviceID"
+ "T@\"NSString\",R,N,V_logPrefix"
+ "T@\"NSString\",R,N,V_serviceName"
+ "T@\"NSXPCConnection\",R,N,V_xpcConnection"
+ "T@\"NSXPCInterface\",R,N,V_xpcClientInterface"
+ "T@\"NSXPCInterface\",R,N,V_xpcServerInterface"
+ "T@\"NSXPCListener\",R,N,V_xpcListener"
+ "T@\"RPAccessPolicyDaemon\",R,N,V_daemon"
+ "T@\"RPCompanionLinkClient\",R,N,V_cLinkBrowser"
+ "T@\"RPCompanionLinkClient\",R,N,V_localDeviceMonitor"
+ "T@\"RPCompanionLinkDevice\",R,N,V_device"
+ "TB,N,V_activated"
+ "TB,N,V_updatePending"
+ "TI,R,N,V_policyType"
+ "TQ,N,V_authFlags"
+ "Td,N,V_permittedDeviceLostDuration"
+ "Td,N,V_permittedRecentlyUnlockedDuration"
+ "Ti,N,V_lockState"
+ "UpdateEndpointAttributes"
+ "XPC Client %#{pid}"
+ "XPC Client %#{pid} %u %@"
+ "XPC Clients: %lu\n"
+ "[%@] Activating with policy %u (%lu initial devices)"
+ "[%@] Delivering update (%lu devices)"
+ "[%@] No change in devices: %@"
+ "[%@] Skipping update without activation: %@"
+ "[%@] Unable to activate: %{error}"
+ "[%@] Unable to deliver update due to XPC error: %{error}"
+ "_activated"
+ "_authFlags"
+ "_cLinkActivate"
+ "_cLinkBrowser"
+ "_cLinkDeviceIDsForDevice:"
+ "_carPlayMonitorDiedNotification:"
+ "_carPlayStateChangedNotification:"
+ "_carplayMonitorActivate"
+ "_carplayMonitorInvalidate"
+ "_carplayStateChanged:"
+ "_continuousTimeNow"
+ "_continuousTimeNowNum"
+ "_currentAltDSID"
+ "_currentIDSDeviceID"
+ "_currentStatusFlags"
+ "_dateFromContinuousTime:"
+ "_dbLookupServiceProvider"
+ "_device"
+ "_deviceIDsForClient:"
+ "_filterDevices:isConnected:"
+ "_iCloudAltDSID"
+ "_idsDeviceID"
+ "_initWithIDSDeviceID:iCloudAltDSID:statusFlags:"
+ "_initWithQueryResult:agentUUID:resolveIdentity:"
+ "_lastConnected"
+ "_lastUnlockTime"
+ "_localDeviceMonitor"
+ "_localDeviceMonitorActivate"
+ "_localDeviceMonitorInterrupted"
+ "_localDeviceMonitorInvalidate"
+ "_localDeviceMonitorInvalidated"
+ "_localDeviceUpdated:"
+ "_localStatePermitsAccess"
+ "_lockState"
+ "_lockTimer"
+ "_lockTimerFired"
+ "_lockTimerNextFire"
+ "_lockTimerStart"
+ "_lockTimerStop"
+ "_logPrefix"
+ "_peerExpirationNextFire"
+ "_peerExpirationPrune"
+ "_peerExpirationTimer"
+ "_peerExpirationTimerFired"
+ "_peerExpirationTimerStart:"
+ "_peerExpirationTimerStop"
+ "_permittedDeviceLostDuration"
+ "_permittedRecentlyUnlockedDuration"
+ "_policyType"
+ "_primaryAltDSID"
+ "_refreshAccessoriesForPresence"
+ "_serviceIsRestricted:"
+ "_serviceName"
+ "_systemMonitorActivate"
+ "_systemMonitorInvalidate"
+ "_systemMonitorLockStateChanged:"
+ "_updatePrimaryAltDSID:"
+ "_xpcActivate"
+ "_xpcClients"
+ "_xpcConnection"
+ "_xpcHandleLostClient:"
+ "_xpcHandleNewConnection:"
+ "_xpcInvalidate"
+ "accessPolicyClientActivate:serviceName:completion:"
+ "accessPolicyUpdatedDevices:"
+ "activated"
+ "apDeviceLostDuration"
+ "apRecentlyUnlockedDuration"
+ "applyToEndpoint:"
+ "authFlags"
+ "cLink interrupted"
+ "cLink invalidated"
+ "cLinkBrowser"
+ "com.apple.rapport.AccessPolicy"
+ "com.apple.rapport.EndpointContext"
+ "com.apple.rapport.RPAccessPolicyDaemon"
+ "contextForLocalDevice"
+ "contextFromNetworkRepresentation:"
+ "currentAltDSID"
+ "daemon info %#ll{flags}"
+ "deviceIDs"
+ "endpointContextForService:trustCircles:completion:"
+ "home:didAddAccessoryNetworkProtectionGroup:"
+ "home:didAddMediaSystem:"
+ "home:didAddResidentDevice:"
+ "home:didFailAccessorySetupWithError:"
+ "home:didRemoveAccessoryNetworkProtectionGroup:"
+ "home:didRemoveMediaSystem:"
+ "home:didRemoveResidentDevice:"
+ "home:didUpdateAccessControlForUser:"
+ "home:didUpdateAccessoryInvitationsForUser:"
+ "home:didUpdateAccessoryNetworkProtectionGroup:"
+ "home:didUpdateActionSet:isExecuting:"
+ "home:didUpdateApplicationDataForActionSet:"
+ "home:didUpdateApplicationDataForRoom:"
+ "home:didUpdateApplicationDataForServiceGroup:"
+ "home:didUpdateAreBulletinNotificationsSupported:"
+ "home:didUpdateAudioAnalysisClassifierOptions:"
+ "home:didUpdateAudioGroupsController:"
+ "home:didUpdateAutomaticSoftwareUpdateEnabled:"
+ "home:didUpdateAutomaticThirdPartyAccessorySoftwareUpdateEnabled:"
+ "home:didUpdateClipCaptionLocales:"
+ "home:didUpdateClipCaptioningEnabled:"
+ "home:didUpdateClipCaptioningEnabledCameras:"
+ "home:didUpdateDismissedWalletKeyUWBUnlockOnboarding:"
+ "home:didUpdateEventLogDuration:"
+ "home:didUpdateEventLogEnabled:"
+ "home:didUpdateHasOnboardedForWalletKey:"
+ "home:didUpdateHomeActivityState:isActivityStateHoldActive:activityStateHoldEndDate:transitionalStateEndDate:"
+ "home:didUpdateHomeActivityStateSchedule:"
+ "home:didUpdateLastExecutionDateForActionSet:"
+ "home:didUpdateLocation:"
+ "home:didUpdateMediaPassword:"
+ "home:didUpdateMediaPeerToPeerEnabled:"
+ "home:didUpdateMinimumMediaUserPrivilege:"
+ "home:didUpdateOnboardAudioAnalysis:"
+ "home:didUpdatePersonManagerSettings:"
+ "home:didUpdateReprovisionStateForAccessory:"
+ "home:didUpdateSiriPhraseOptions:"
+ "home:didUpdateStateForOutgoingInvitations:"
+ "home:didUpdateSupportsResidentActionSetStateEvaluation:"
+ "home:didUpdateTimeZone:"
+ "homeDidAddWalletKey:"
+ "homeDidEnableLocationServices:"
+ "homeDidEnableMultiUser:"
+ "homeDidOnboardLocationServices:"
+ "homeDidRemoveWalletKey:"
+ "homeDidSetEnableDoorbellChime:"
+ "homeDidSetHasAnyUserAcknowledgedCameraRecordingOnboarding:"
+ "homeDidSetHasOnboardedForAccessCode:"
+ "homeDidUpdateApplicationData:"
+ "homeDidUpdateAssistantIdentifiers:"
+ "homeDidUpdateAutoSelectedPreferredResident:"
+ "homeDidUpdateHomeLocationStatus:"
+ "homeDidUpdateNetworkRouterSupport:"
+ "homeDidUpdateOnboardedEventLog:"
+ "homeDidUpdatePrimaryResidentNetworkInfo:"
+ "homeDidUpdateProtectionMode:"
+ "homeDidUpdateSoundCheck:"
+ "homeDidUpdateSupportsResidentSelection:"
+ "homeDidUpdateToROAR:"
+ "homeDidUpdateUserSelectedPreferredResident:"
+ "homeManager:didAddHome:"
+ "homeManager:didReceiveAddAccessoryRequest:"
+ "homeManager:didRemoveHome:"
+ "homeManager:didUpdateAuthorizationStatus:"
+ "homeManagerDidUpdateHomes:"
+ "homeManagerDidUpdatePrimaryHome:"
+ "iCloudAltDSID"
+ "idsID"
+ "initWithConnection:daemon:"
+ "initWithDevice:lastConnected:"
+ "isEqualToSet:"
+ "isEquivalentToDeviceInfo:"
+ "isMeDevice"
+ "isPriorityBoosted:serviceProvider:"
+ "isRestricted:serviceProvider:"
+ "lastConnected"
+ "lastObject"
+ "lastUnlockTime"
+ "localDevice"
+ "localDeviceMonitor"
+ "lockState"
+ "lockTimer"
+ "logPrefix"
+ "networkRepresentationForTrustCircles:"
+ "peerExpirationTimer"
+ "permittedDeviceLostDuration"
+ "permittedRecentlyUnlockedDuration"
+ "personal"
+ "policyType"
+ "primary AltDSID"
+ "primaryAltDSID"
+ "regenerateQueryResults:"
+ "resolveIdentityForQueryResult:"
+ "sF"
+ "serviceRequiresPriorityBoost:"
+ "setActivated:"
+ "setAuthFlags:"
+ "setICloudAltDSID:"
+ "setLastUnlockTime:"
+ "setLockState:"
+ "setLockTimer:"
+ "setPeerExpirationTimer:"
+ "setPermittedDeviceLostDuration:"
+ "setPermittedRecentlyUnlockedDuration:"
+ "setPrimaryAltDSID:"
+ "setSystemLockStateChangedHandler:"
+ "setUpdatePending:"
+ "setXPCType:forSelector:argumentIndex:ofReply:"
+ "sharedDaemonNoCreate"
+ "sortUsingSelector:"
+ "systemLockState"
+ "systemLockStateSync"
+ "updateEncodedEndpoint:forService:usingContext:completion:"
+ "updatePending"
+ "v16@?0@\"QRServiceDiscoveryQueryResult\"8"
+ "v24@0:8@\"HMHomeManager\"16"
+ "v24@0:8@\"NSSet\"16"
+ "v24@0:8d16"
+ "v28@0:8@\"HMHome\"16B24"
+ "v32@0:8@\"HMHome\"16@\"CLLocation\"24"
+ "v32@0:8@\"HMHome\"16@\"HMAccessoryNetworkProtectionGroup\"24"
+ "v32@0:8@\"HMHome\"16@\"HMHomeActivityStateSchedule\"24"
+ "v32@0:8@\"HMHome\"16@\"HMHomePersonManagerSettings\"24"
+ "v32@0:8@\"HMHome\"16@\"HMMediaGroupsController\"24"
+ "v32@0:8@\"HMHome\"16@\"HMMediaSystem\"24"
+ "v32@0:8@\"HMHome\"16@\"HMResidentDevice\"24"
+ "v32@0:8@\"HMHome\"16@\"NSArray\"24"
+ "v32@0:8@\"HMHome\"16@\"NSError\"24"
+ "v32@0:8@\"HMHome\"16@\"NSSet\"24"
+ "v32@0:8@\"HMHome\"16@\"NSString\"24"
+ "v32@0:8@\"HMHome\"16@\"NSTimeZone\"24"
+ "v32@0:8@\"HMHome\"16q24"
+ "v32@0:8@\"HMHomeManager\"16@\"HMAddAccessoryRequest\"24"
+ "v32@0:8@\"HMHomeManager\"16@\"HMHome\"24"
+ "v32@0:8@\"HMHomeManager\"16Q24"
+ "v36@0:8@\"HMHome\"16@\"HMActionSet\"24B32"
+ "v36@0:8I16@\"NSString\"20@?<v@?@\"NSSet\"@\"NSError\">28"
+ "v36@0:8I16@20@?28"
+ "v40@0:8@\"NSString\"16Q24@?<v@?@\"NSData\"@\"NSError\">32"
+ "v48@0:8@\"NSObject<OS_xpc_object>\"16@\"NSString\"24@\"NSData\"32@?<v@?@\"NSObject<OS_xpc_object>\"@\"NSError\">40"
+ "v52@0:8@\"HMHome\"16Q24B32@\"NSDate\"36@\"NSDate\"44"
+ "v52@0:8@16Q24B32@36@44"
+ "xpcClientInterface"
+ "xpcClients"
+ "xpcConnection"
+ "xpcServerInterface"
+ "\xa1"
- "-[QRServiceDiscoveryClient _serviceDiscovery:startAdvertisement:completionHandler:]"
- "-[QRServiceDiscoveryClient _serviceDiscovery:startQuery:completionHandler:]"
- "-[QRServiceDiscoveryClient _serviceDiscovery:stopAdvertisement:completionHandler:]"
- "-[QRServiceDiscoveryClient _serviceDiscovery:stopQuery:completionHandler:]"
- "-[QRServiceDiscoveryClient _serviceDiscovery:updateAdvertisement:metadata:completionHandler:]"
- "-[QRServiceDiscoveryClient startAvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]"
- "-[QRServiceDiscoveryClient startAvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke"
- "-[QRServiceDiscoveryClient startAvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke_2"
- "-[QRServiceDiscoveryClient startAvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke_3"
- "-[RPServiceDiscoveryClient startAvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke"
- "-[RPServiceDiscoveryClient startAvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke_2"
- "-[RPServiceDiscoveryClient startAvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke_3"
- "_initWithQueryResult:agentUUID:"
- "startAvertisementForAdvertiseDescriptor:withMetadata:completionHandler:"
```
