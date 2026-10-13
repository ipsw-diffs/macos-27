## CoreHAP

> `/System/Library/PrivateFrameworks/CoreHAP.framework/Versions/A/CoreHAP`

```diff

-1520.2.3.0.2
-  __TEXT.__text: 0x2b0c68
-  __TEXT.__objc_methlist: 0x185e8
-  __TEXT.__const: 0x1330
-  __TEXT.__constg_swiftt: 0xa64
-  __TEXT.__swift5_typeref: 0x437
-  __TEXT.__swift5_builtin: 0x50
-  __TEXT.__swift5_reflstr: 0x581
-  __TEXT.__swift5_fieldmd: 0x49c
-  __TEXT.__swift5_assocty: 0xd8
-  __TEXT.__swift5_proto: 0x5c
-  __TEXT.__swift5_types: 0x34
-  __TEXT.__cstring: 0x1412b
-  __TEXT.__oslogstring: 0x3e034
+1520.2.7.4.1
+  __TEXT.__text: 0x3012a0
+  __TEXT.__objc_methlist: 0x1b9d0
+  __TEXT.__const: 0x1798
+  __TEXT.__constg_swiftt: 0xc20
+  __TEXT.__swift5_typeref: 0x533
+  __TEXT.__swift5_builtin: 0xdc
+  __TEXT.__swift5_reflstr: 0x851
+  __TEXT.__swift5_fieldmd: 0x6a4
+  __TEXT.__swift5_assocty: 0x138
+  __TEXT.__swift5_proto: 0x78
+  __TEXT.__swift5_types: 0x5c
+  __TEXT.__cstring: 0x16d06
+  __TEXT.__oslogstring: 0x42fda
+  __TEXT.__swift5_protos: 0x4
   __TEXT.__swift5_capture: 0x28c
-  __TEXT.__gcc_except_tab: 0x58bc
-  __TEXT.__unwind_info: 0x88b0
+  __TEXT.__gcc_except_tab: 0x6964
+  __TEXT.__unwind_info: 0x99f8
   __TEXT.__eh_frame: 0x1078
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2170
-  __DATA_CONST.__objc_classlist: 0xc40
+  __DATA_CONST.__const: 0x2498
+  __DATA_CONST.__objc_classlist: 0xd78
   __DATA_CONST.__objc_catlist: 0x30
-  __DATA_CONST.__objc_protolist: 0x398
+  __DATA_CONST.__objc_protolist: 0x3c8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7e58
-  __DATA_CONST.__objc_protorefs: 0x100
-  __DATA_CONST.__objc_superrefs: 0xa80
+  __DATA_CONST.__objc_selrefs: 0x9178
+  __DATA_CONST.__objc_protorefs: 0x110
+  __DATA_CONST.__objc_superrefs: 0xb98
   __DATA_CONST.__objc_arraydata: 0x200
-  __DATA_CONST.__got: 0x1020
-  __AUTH_CONST.__const: 0x5408
-  __AUTH_CONST.__cfstring: 0xfa40
-  __AUTH_CONST.__objc_const: 0x2afa0
-  __AUTH_CONST.__weak_auth_got: 0x8
-  __AUTH_CONST.__objc_intobj: 0x588
+  __DATA_CONST.__got: 0x1150
+  __AUTH_CONST.__const: 0x5dd0
+  __AUTH_CONST.__cfstring: 0x10e80
+  __AUTH_CONST.__objc_const: 0x30ea8
+  __AUTH_CONST.__weak_auth_got: 0x10
+  __AUTH_CONST.__objc_intobj: 0x5a0
   __AUTH_CONST.__objc_floatobj: 0x20
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__objc_arrayobj: 0xc0
-  __AUTH_CONST.__auth_got: 0x1110
-  __AUTH.__objc_data: 0x7568
-  __AUTH.__data: 0xb0
+  __AUTH_CONST.__auth_got: 0x11b8
+  __AUTH.__objc_data: 0x8330
+  __AUTH.__data: 0x130
   __AUTH.__thread_vars: 0x30
   __AUTH.__thread_bss: 0x28
-  __DATA.__objc_ivar: 0x1880
-  __DATA.__data: 0x2cd2
+  __DATA.__objc_ivar: 0x1cd4
+  __DATA.__data: 0x2fd8
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0xf10
-  __DATA.__common: 0x8
-  __DATA_DIRTY.__objc_data: 0x1068
+  __DATA.__bss: 0x11a0
+  __DATA.__common: 0x90
+  __DATA_DIRTY.__objc_data: 0x1108
   __DATA_DIRTY.__data: 0x40
-  __DATA_DIRTY.__bss: 0xa8
+  __DATA_DIRTY.__bss: 0xc8
   __DATA_DIRTY.__common: 0x20
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 9687
-  Symbols:   19878
-  CStrings:  6612
+  Functions: 11078
+  Symbols:   22445
+  CStrings:  7135
 
Symbols:
+ +[HAP2AccessoryDeviceIPAddress accessoryDeviceIPAddressWithSerializedData:]
+ +[HAP2AccessoryServerCoordinator(Test) coordinatorForUnitTestsWithBrowser:operationQueue:delegate:]
+ +[HAP2AccessoryServerDiscoveryHAPAccessoryInfo accessoryInfoWithDeviceID:rawDiscoveryInfo:]
+ +[HAP2AccessoryServerIPCacheData dataWithDictionary:deviceID:]
+ +[HAP2AccessoryServerIPCacheData logCategory]
+ +[HAP2SessionKeepAliveConfiguration computeSelectedConfigurationForTransportType:isSleepyEndDevice:supportedMinInterval:supportedMaxInterval:supportedMinRange:]
+ +[HAPBluetoothMetrics parsedFromData:error:]
+ +[HAPBootReasonsMetrics parsedFromData:error:]
+ +[HAPCHMMetrics parsedFromData:error:]
+ +[HAPConnectionHealthMonitor parsedFromData:error:]
+ +[HAPErrorCountersMetrics parsedFromData:error:]
+ +[HAPErrorCountersMetricsEntry parsedFromData:error:]
+ +[HAPHKSV3UploadLatencyMetrics parsedFromData:error:]
+ +[HAPMetricEventBluetoothVersionTypeWrapper parsedFromData:error:]
+ +[HAPMetricEventPowerSourcesBitmaskWrapper parsedFromData:error:]
+ +[HAPMetricEventPowerSourcesEnumWrapper parsedFromData:error:]
+ +[HAPMetricEventThreadFirstRestartConnectivityStateWrapper parsedFromData:error:]
+ +[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper parsedFromData:error:]
+ +[HAPMetricEventWiFiVersionTypeWrapper parsedFromData:error:]
+ +[HAPPowerMetrics parsedFromData:error:]
+ +[HAPSaturationMetrics parsedFromData:error:]
+ +[HAPSessionKeepAliveTransportTypeWrapper parsedFromData:error:]
+ +[HAPStabilityMetrics parsedFromData:error:]
+ +[HAPStabilityMetricsBootReasonTypeWrapper parsedFromData:error:]
+ +[HAPStabilityMetricsHardwareFaultTypeWrapper parsedFromData:error:]
+ +[HAPTLVPreferredWiFiEntry parsedFromData:error:]
+ +[HAPTLVPreferredWiFiList parsedFromData:error:]
+ +[HAPTLVSelectedSessionKeepAliveConfigurationEntry parsedFromData:error:]
+ +[HAPTLVSelectedSessionKeepAliveConfigurationList parsedFromData:error:]
+ +[HAPTLVSupportedSessionKeepAliveConfigurationEntry parsedFromData:error:]
+ +[HAPTLVSupportedSessionKeepAliveConfigurationList parsedFromData:error:]
+ +[HAPThermalMetrics parsedFromData:error:]
+ +[HAPWiFiMetrics parsedFromData:error:]
+ -[HAP2AccessoryAddressLists cachedPrimary]
+ -[HAP2AccessoryAddressLists cachedSecondary]
+ -[HAP2AccessoryAddressLists initWithPrimary:secondary:cachedPrimary:cachedSecondary:]
+ -[HAP2AccessoryAddressLists setCachedPrimary:]
+ -[HAP2AccessoryAddressLists setCachedSecondary:]
+ -[HAP2AccessoryAddressResolverPipeline .cxx_destruct]
+ -[HAP2AccessoryAddressResolverPipeline _acquireDNSContextOwnership]
+ -[HAP2AccessoryAddressResolverPipeline _clearAllAddresses]
+ -[HAP2AccessoryAddressResolverPipeline _coapAddressFromGAIResult:outAddress:]
+ -[HAP2AccessoryAddressResolverPipeline _handleGetaddrinfoEvent:error:]
+ -[HAP2AccessoryAddressResolverPipeline _handleGetaddrinfoResults:count:]
+ -[HAP2AccessoryAddressResolverPipeline _handleResolveCallbackWithError:hostname:port:]
+ -[HAP2AccessoryAddressResolverPipeline _recordAddedAddress:]
+ -[HAP2AccessoryAddressResolverPipeline _recordRemovedAddress:]
+ -[HAP2AccessoryAddressResolverPipeline _releaseDNSContextOwnership]
+ -[HAP2AccessoryAddressResolverPipeline _restampWorkingSetWithResolvedPort]
+ -[HAP2AccessoryAddressResolverPipeline _startGetaddrinfoForHostname:]
+ -[HAP2AccessoryAddressResolverPipeline cancel]
+ -[HAP2AccessoryAddressResolverPipeline initWithQueue:updateHandler:errorHandler:]
+ -[HAP2AccessoryAddressResolverPipeline publishedAddresses]
+ -[HAP2AccessoryAddressResolverPipeline startWithServiceName:serviceType:serviceDomain:]
+ -[HAP2AccessoryDNSResolver .cxx_destruct]
+ -[HAP2AccessoryDNSResolver _applyCachedIP:transportType:notifySubscriber:seedAgingClock:]
+ -[HAP2AccessoryDNSResolver _handlePipelineError:]
+ -[HAP2AccessoryDNSResolver _handlePipelineUpdate:]
+ -[HAP2AccessoryDNSResolver _restartPipelineOnQueue]
+ -[HAP2AccessoryDNSResolver _seedCachedIP:transportType:]
+ -[HAP2AccessoryDNSResolver _startPipelineOnQueue]
+ -[HAP2AccessoryDNSResolver _tearDownPipeline]
+ -[HAP2AccessoryDNSResolver _test_setBecameEmptyAt:]
+ -[HAP2AccessoryDNSResolver attachCacheSubscriber:]
+ -[HAP2AccessoryDNSResolver attachDelegate:]
+ -[HAP2AccessoryDNSResolver becameEmptyAt]
+ -[HAP2AccessoryDNSResolver cachedIPDidUpdate:transportType:]
+ -[HAP2AccessoryDNSResolver currentAddresses]
+ -[HAP2AccessoryDNSResolver dealloc]
+ -[HAP2AccessoryDNSResolver deferAgingClockIfRunning]
+ -[HAP2AccessoryDNSResolver detachCacheSubscriber:]
+ -[HAP2AccessoryDNSResolver detachDelegate:]
+ -[HAP2AccessoryDNSResolver deviceID]
+ -[HAP2AccessoryDNSResolver initWithDeviceID:serviceName:managerQueue:pipelineFactory:]
+ -[HAP2AccessoryDNSResolver performHealthCheck]
+ -[HAP2AccessoryDNSResolver serviceName]
+ -[HAP2AccessoryDNSResolver startPipeline]
+ -[HAP2AccessoryDNSResolver stopPipeline]
+ -[HAP2AccessoryDNSResolver updateServiceName:]
+ -[HAP2AccessoryDeviceIPAddress _classifyTransportType:]
+ -[HAP2AccessoryDeviceIPAddress debugDescription]
+ -[HAP2AccessoryDeviceIPAddress isIPv6]
+ -[HAP2AccessoryDeviceIPAddress serializedData]
+ -[HAP2AccessoryDeviceIPAddress transportType]
+ -[HAP2AccessoryServer _attachResolverAndForwardToTransport:]
+ -[HAP2AccessoryServer _runLostDiscoveryAdvertisementSideEffectsWithWillSleep:]
+ -[HAP2AccessoryServer _runResolverReactiveWorkWithWas:now:connectionState:]
+ -[HAP2AccessoryServer _setHasThreadAdvertisement:]
+ -[HAP2AccessoryServer _setHasWiFiAdvertisement:]
+ -[HAP2AccessoryServer dnsResolver]
+ -[HAP2AccessoryServer hasSeededSinceResolverAttach]
+ -[HAP2AccessoryServer hasThreadAdvertisement]
+ -[HAP2AccessoryServer hasWiFiAdvertisement]
+ -[HAP2AccessoryServer lastObservedHasAdvertisement]
+ -[HAP2AccessoryServer setDnsResolver:]
+ -[HAP2AccessoryServer setHasSeededSinceResolverAttach:]
+ -[HAP2AccessoryServer setHasThreadAdvertisement:]
+ -[HAP2AccessoryServer setHasWiFiAdvertisement:]
+ -[HAP2AccessoryServer setKeepAliveListener:]
+ -[HAP2AccessoryServer setLastObservedHasAdvertisement:]
+ -[HAP2AccessoryServer(Paired) configureKeepAliveListener:]
+ -[HAP2AccessoryServer(Paired) currentResolverSnapshot]
+ -[HAP2AccessoryServer(Paired) didChangeThreadAdvertisement:]
+ -[HAP2AccessoryServer(Paired) didChangeWiFiAdvertisement:]
+ -[HAP2AccessoryServer(Paired) didReceiveHeartbeatOnTransport:]
+ -[HAP2AccessoryServer(Paired) mergeWithNewlyDiscoveredPairedAccessoryServer:resolver:]
+ -[HAP2AccessoryServer(Paired) pairVerifyDidCompleteOnIPAddress:transportType:]
+ -[HAP2AccessoryServer(Paired) pairVerifyDidFailOnIPAddress:transportType:error:]
+ -[HAP2AccessoryServer(Paired) resolver:didUpdateAddresses:]
+ -[HAP2AccessoryServer(Paired) restartKeepAliveListener]
+ -[HAP2AccessoryServer(PairedInternal) _closeSessionIfConnectedIPAddressStaleForTransport:]
+ -[HAP2AccessoryServer(PairedInternal) _handleProbeCompletion:forKeepAliveTransport:]
+ -[HAP2AccessoryServer(PairedInternal) _haveAllTransportsHitFailureThreshold]
+ -[HAP2AccessoryServer(PairedInternal) keepAliveListener:didMissHeartbeatOnTransport:expectedInterval:timeSinceLastHeartbeat:allTransportsMissed:]
+ -[HAP2AccessoryServer(PairedInternal) keepAliveListenerDidCompleteIPPortPairCheck:]
+ -[HAP2AccessoryServer(Test) _test_becomePaired]
+ -[HAP2AccessoryServer(Test) _test_hasDiscoveryAdvertisement]
+ -[HAP2AccessoryServer(Test) _test_hasSeededSinceResolverAttach]
+ -[HAP2AccessoryServer(Test) _test_isInternallyPaired]
+ -[HAP2AccessoryServer(Test) _test_lastObservedHasAdvertisement]
+ -[HAP2AccessoryServer(Test) _test_reactiveWorkRecorderBlock]
+ -[HAP2AccessoryServer(Test) _test_setConnectionStateUnreachable]
+ -[HAP2AccessoryServer(Test) _test_setHasSeededSinceResolverAttach:]
+ -[HAP2AccessoryServer(Test) _test_setInternallyPaired:]
+ -[HAP2AccessoryServer(Test) set_test_reactiveWorkRecorderBlock:]
+ -[HAP2AccessoryServerBrowser _armPTRRevalidationWindow]
+ -[HAP2AccessoryServerBrowser _buildActiveDeviceIDsSet]
+ -[HAP2AccessoryServerBrowser _cancelPTRRevalidationWindow]
+ -[HAP2AccessoryServerBrowser _fireRevalidationSweep]
+ -[HAP2AccessoryServerBrowser _initializeFromCachedRecord:deviceID:]
+ -[HAP2AccessoryServerBrowser _performAuditPass]
+ -[HAP2AccessoryServerBrowser _reinitializeFromCachedRecordsAfterCoordinatorsStarted]
+ -[HAP2AccessoryServerBrowser _restoreCachedAccessoryServersIfNeeded]
+ -[HAP2AccessoryServerBrowser attachSelfAsCacheSubscriberOnResolver:]
+ -[HAP2AccessoryServerBrowser auditScheduler]
+ -[HAP2AccessoryServerBrowser cachedIPDidUpdate:transportType:forDeviceID:]
+ -[HAP2AccessoryServerBrowser currentPTRs]
+ -[HAP2AccessoryServerBrowser existingPTRs]
+ -[HAP2AccessoryServerBrowser hasCurrentPTRForDeviceID:]
+ -[HAP2AccessoryServerBrowser hasDiscoveryAdvertisementForAccessoryWithID:]
+ -[HAP2AccessoryServerBrowser hasThreadAdvertisementForAccessoryWithID:]
+ -[HAP2AccessoryServerBrowser hasWiFiAdvertisementForAccessoryWithID:]
+ -[HAP2AccessoryServerBrowser ipCache]
+ -[HAP2AccessoryServerBrowser isInitialCacheRestored]
+ -[HAP2AccessoryServerBrowser noteBonjourAdvertisementUpdatedForDeviceID:rawDiscoveryInfo:]
+ -[HAP2AccessoryServerBrowser noteBrowsedPTRAddForDeviceID:serviceName:]
+ -[HAP2AccessoryServerBrowser noteBrowsedPTRRemoveForDeviceID:]
+ -[HAP2AccessoryServerBrowser noteResolverReapedForDeviceID:]
+ -[HAP2AccessoryServerBrowser pendingRevalidationPTRs]
+ -[HAP2AccessoryServerBrowser resolverRegistry]
+ -[HAP2AccessoryServerBrowser revalidationTimer]
+ -[HAP2AccessoryServerBrowser setAuditScheduler:]
+ -[HAP2AccessoryServerBrowser setIPCache:]
+ -[HAP2AccessoryServerBrowser setIpCache:]
+ -[HAP2AccessoryServerBrowser setIsInitialCacheRestored:]
+ -[HAP2AccessoryServerBrowser setPendingRevalidationPTRs:]
+ -[HAP2AccessoryServerBrowser setResolverRegistry:]
+ -[HAP2AccessoryServerBrowser setRevalidationTimer:]
+ -[HAP2AccessoryServerBrowser(Test) _test_auditScheduler]
+ -[HAP2AccessoryServerBrowser(Test) _test_hasDiscoveryAdvertisementForAccessoryWithID:]
+ -[HAP2AccessoryServerBrowser(Test) _test_hasThreadAdvertisementForAccessoryWithID:]
+ -[HAP2AccessoryServerBrowser(Test) _test_hasWiFiAdvertisementForAccessoryWithID:]
+ -[HAP2AccessoryServerBrowser(Test) _test_performAuditPass]
+ -[HAP2AccessoryServerBrowser(Test) _test_restoreCachedAccessoryServersIfNeeded]
+ -[HAP2AccessoryServerBrowser(Test) _test_setLivePairedServers:]
+ -[HAP2AccessoryServerBrowser(Test) _test_setResolverRegistry:]
+ -[HAP2AccessoryServerController _announceReestablishedSessionIfNeeded]
+ -[HAP2AccessoryServerController applyResolverAddresses:completion:]
+ -[HAP2AccessoryServerController checkConnectedIPAddressStaleOnTransport:completion:]
+ -[HAP2AccessoryServerController hasArmedCacheOnlyLatch]
+ -[HAP2AccessoryServerController readLocalEndpointsWithHandler:]
+ -[HAP2AccessoryServerController secureTransport:didChangeThreadAdvertisement:]
+ -[HAP2AccessoryServerController secureTransport:didChangeWiFiAdvertisement:]
+ -[HAP2AccessoryServerController secureTransport:didReceiveHeartbeatOnTransport:]
+ -[HAP2AccessoryServerController secureTransport:pairVerifyDidCompleteOnIPAddress:transportType:]
+ -[HAP2AccessoryServerController secureTransport:pairVerifyDidFailOnIPAddress:transportType:error:]
+ -[HAP2AccessoryServerController secureTransportCurrentResolverSnapshot:]
+ -[HAP2AccessoryServerController sendProbeOnTransport:completion:]
+ -[HAP2AccessoryServerCoordinator initializePairedAccessoryServerFromCachedInfo:]
+ -[HAP2AccessoryServerCoordinator(Test) _test_deliverDiscovery:]
+ -[HAP2AccessoryServerCoordinator(Test) _test_deliverLoss:]
+ -[HAP2AccessoryServerIPCacheData .cxx_destruct]
+ -[HAP2AccessoryServerIPCacheData cachedPrimaryData]
+ -[HAP2AccessoryServerIPCacheData cachedSecondaryData]
+ -[HAP2AccessoryServerIPCacheData configurationInfo]
+ -[HAP2AccessoryServerIPCacheData deviceID]
+ -[HAP2AccessoryServerIPCacheData dictionaryRepresentation]
+ -[HAP2AccessoryServerIPCacheData initFromDictionary:deviceID:]
+ -[HAP2AccessoryServerIPCacheData initWithDeviceID:cachedPrimaryData:cachedSecondaryData:configurationInfo:]
+ -[HAP2AccessoryServerIPCacheData setCachedPrimaryData:]
+ -[HAP2AccessoryServerIPCacheData setCachedSecondaryData:]
+ -[HAP2AccessoryServerIPCacheData setConfigurationInfo:]
+ -[HAP2AccessoryServerIPCacheData setDeviceID:]
+ -[HAP2AccessoryServerSecureTransportBase applyResolverAddresses:completion:]
+ -[HAP2AccessoryServerSecureTransportBase checkConnectedIPAddressStaleOnTransport:completion:]
+ -[HAP2AccessoryServerSecureTransportBase hasArmedCacheOnlyLatch]
+ -[HAP2AccessoryServerSecureTransportBase lastCompletedMessageID]
+ -[HAP2AccessoryServerSecureTransportBase readLocalEndpointsWithHandler:]
+ -[HAP2AccessoryServerSecureTransportBase sendProbeOnTransport:completion:]
+ -[HAP2AccessoryServerSecureTransportBase setSupportsKeepAlive:]
+ -[HAP2AccessoryServerSecureTransportBase setSupportsThreadTransport:]
+ -[HAP2AccessoryServerSecureTransportBase setSupportsWiFiTransport:]
+ -[HAP2AccessoryServerSecureTransportBase transport:didChangeThreadAdvertisement:]
+ -[HAP2AccessoryServerSecureTransportBase transport:didChangeWiFiAdvertisement:]
+ -[HAP2AccessoryServerSecureTransportBase transport:didReceiveHeartbeatOnTransport:]
+ -[HAP2AccessoryServerSecureTransportBase transport:pairVerifyDidCompleteOnIPAddress:transportType:]
+ -[HAP2AccessoryServerSecureTransportBase transport:pairVerifyDidFailOnIPAddress:transportType:error:]
+ -[HAP2AccessoryServerSecureTransportBase transportCurrentResolverSnapshot:]
+ -[HAP2AccessoryServerSecureTransportPairSetup transport:didReceiveHeartbeatOnTransport:]
+ -[HAP2AccessoryServerTransportBase lastCompletedMessageID]
+ -[HAP2AccessoryServerTransportBase setSupportsKeepAlive:]
+ -[HAP2AccessoryServerTransportBase setSupportsThreadTransport:]
+ -[HAP2AccessoryServerTransportBase setSupportsWiFiTransport:]
+ -[HAP2AccessoryServerTransportBase supportsKeepAlive]
+ -[HAP2AccessoryServerTransportBase supportsThreadTransport]
+ -[HAP2AccessoryServerTransportBase supportsWiFiTransport]
+ -[HAP2AccessoryServerTransportCoAP _applyResolverAddressesOnQueue:]
+ -[HAP2AccessoryServerTransportCoAP _armInitialCacheGracePeriodTimerIfNeeded]
+ -[HAP2AccessoryServerTransportCoAP _beginInitialOpenLoggingAddress:transportLabel:]
+ -[HAP2AccessoryServerTransportCoAP _buildSecondaryCoapClientWithAddress:]
+ -[HAP2AccessoryServerTransportCoAP _cancelFailoverTimer]
+ -[HAP2AccessoryServerTransportCoAP _cancelResolver]
+ -[HAP2AccessoryServerTransportCoAP _completeRequest:error:path:]
+ -[HAP2AccessoryServerTransportCoAP _createCoapClient]
+ -[HAP2AccessoryServerTransportCoAP _evaluateCacheMissCancelIfNeededWithLivePrimaryCount:]
+ -[HAP2AccessoryServerTransportCoAP _executeCacheMissCancel]
+ -[HAP2AccessoryServerTransportCoAP _failInitialOpenWithError:]
+ -[HAP2AccessoryServerTransportCoAP _handleInitialResolvePrimary:]
+ -[HAP2AccessoryServerTransportCoAP _handleInitialResolveSecondary:]
+ -[HAP2AccessoryServerTransportCoAP _handleInitialResolverComplete]
+ -[HAP2AccessoryServerTransportCoAP _handleLiveResolverUpdate]
+ -[HAP2AccessoryServerTransportCoAP _handleRefreshResolve:isFromPrimaryList:]
+ -[HAP2AccessoryServerTransportCoAP _handleResolve:isFromPrimaryList:]
+ -[HAP2AccessoryServerTransportCoAP _logAddress:index:]
+ -[HAP2AccessoryServerTransportCoAP _maybeFireOffQueueCacheMissCancelForAddresses:]
+ -[HAP2AccessoryServerTransportCoAP _openPrimaryClientForRefreshWithAddress:]
+ -[HAP2AccessoryServerTransportCoAP _openPrimaryClientIteratingWithCompletion:]
+ -[HAP2AccessoryServerTransportCoAP _openSecondaryClientForRefreshWithAddress:]
+ -[HAP2AccessoryServerTransportCoAP _openSecondaryClientIteratingIsThreadOnly:completion:]
+ -[HAP2AccessoryServerTransportCoAP _readLocalEndpointForClient:transport:into:completion:]
+ -[HAP2AccessoryServerTransportCoAP _refreshIPAddresses]
+ -[HAP2AccessoryServerTransportCoAP _resetIPsTriedThisSession]
+ -[HAP2AccessoryServerTransportCoAP _resetInitialCacheOnlyStopgapState]
+ -[HAP2AccessoryServerTransportCoAP _resolveAddress]
+ -[HAP2AccessoryServerTransportCoAP _resolveFailedWithError:]
+ -[HAP2AccessoryServerTransportCoAP _sendEndpointRegistration]
+ -[HAP2AccessoryServerTransportCoAP _sendHelloIfReady]
+ -[HAP2AccessoryServerTransportCoAP _sendMultiTransportRequest:path:]
+ -[HAP2AccessoryServerTransportCoAP _sendRegistrationTLVWithAddressBytes:port:]
+ -[HAP2AccessoryServerTransportCoAP _sendWiFiEndpointRegistration]
+ -[HAP2AccessoryServerTransportCoAP _setIpAddress:]
+ -[HAP2AccessoryServerTransportCoAP _shouldRegisterEndpoint]
+ -[HAP2AccessoryServerTransportCoAP _startResolveTimeoutTimer]
+ -[HAP2AccessoryServerTransportCoAP _startResolverIfNeeded]
+ -[HAP2AccessoryServerTransportCoAP _takeNextPrimaryIPToTry]
+ -[HAP2AccessoryServerTransportCoAP _takeNextSecondaryIPToTry]
+ -[HAP2AccessoryServerTransportCoAP _tearDownInitialCacheGracePeriodTimer]
+ -[HAP2AccessoryServerTransportCoAP advanceEndpointAfterPairVerifyFailureWithCompletion:]
+ -[HAP2AccessoryServerTransportCoAP applyResolverAddresses:completion:]
+ -[HAP2AccessoryServerTransportCoAP checkConnectedIPAddressStaleOnTransport:completion:]
+ -[HAP2AccessoryServerTransportCoAP clientDidReceivePing:]
+ -[HAP2AccessoryServerTransportCoAP dataStreamPeerAddressWithCompletion:]
+ -[HAP2AccessoryServerTransportCoAP hasArmedCacheOnlyLatch]
+ -[HAP2AccessoryServerTransportCoAP hasRegisteredEndpoint]
+ -[HAP2AccessoryServerTransportCoAP initialACKTimeout]
+ -[HAP2AccessoryServerTransportCoAP initialCacheGracePeriodTimer]
+ -[HAP2AccessoryServerTransportCoAP initialConnectionAttemptStartedAt]
+ -[HAP2AccessoryServerTransportCoAP lastCompletedMessageID]
+ -[HAP2AccessoryServerTransportCoAP lastMessageID]
+ -[HAP2AccessoryServerTransportCoAP logIPAddresses]
+ -[HAP2AccessoryServerTransportCoAP maxTransmitAttempts]
+ -[HAP2AccessoryServerTransportCoAP primaryEffectiveListIsCacheOnly]
+ -[HAP2AccessoryServerTransportCoAP primaryIPsTriedThisSession]
+ -[HAP2AccessoryServerTransportCoAP primaryOpenInFlight]
+ -[HAP2AccessoryServerTransportCoAP readLocalEndpointsWithHandler:]
+ -[HAP2AccessoryServerTransportCoAP resolveTimeoutTimer]
+ -[HAP2AccessoryServerTransportCoAP resolverRestartTimer]
+ -[HAP2AccessoryServerTransportCoAP secondaryAddressList]
+ -[HAP2AccessoryServerTransportCoAP secondaryCoAPClient]
+ -[HAP2AccessoryServerTransportCoAP secondaryIPsTriedThisSession]
+ -[HAP2AccessoryServerTransportCoAP securedClient]
+ -[HAP2AccessoryServerTransportCoAP sendProbeOnTransport:completion:]
+ -[HAP2AccessoryServerTransportCoAP setHasRegisteredEndpoint:]
+ -[HAP2AccessoryServerTransportCoAP setInFlightRacingLogEvent:]
+ -[HAP2AccessoryServerTransportCoAP setInitialCacheGracePeriodTimer:]
+ -[HAP2AccessoryServerTransportCoAP setInitialConnectionAttemptStartedAt:]
+ -[HAP2AccessoryServerTransportCoAP setLastCompletedMessageID:]
+ -[HAP2AccessoryServerTransportCoAP setLastMessageID:]
+ -[HAP2AccessoryServerTransportCoAP setNumOfAddresses:]
+ -[HAP2AccessoryServerTransportCoAP setNumOfAddressesTried:]
+ -[HAP2AccessoryServerTransportCoAP setPrimaryEffectiveListIsCacheOnly:]
+ -[HAP2AccessoryServerTransportCoAP setPrimaryOpenInFlight:]
+ -[HAP2AccessoryServerTransportCoAP setResolveTimeoutTimer:]
+ -[HAP2AccessoryServerTransportCoAP setResolverRestartTimer:]
+ -[HAP2AccessoryServerTransportCoAP setSecondaryCoAPClient:]
+ -[HAP2AccessoryServerTransportCoAP setSecuredClient:]
+ -[HAP2AccessoryServerTransportCoAP setTryingInitialCacheOnly:]
+ -[HAP2AccessoryServerTransportCoAP signalPairVerifyFailureToDelegateWithError:]
+ -[HAP2AccessoryServerTransportCoAP signalPairVerifySuccessToDelegate]
+ -[HAP2AccessoryServerTransportCoAP tryingInitialCacheOnly]
+ -[HAP2BrowserResolverRegistry .cxx_destruct]
+ -[HAP2BrowserResolverRegistry _performAuditPassOnQueueWithActiveDeviceIDs:]
+ -[HAP2BrowserResolverRegistry browser]
+ -[HAP2BrowserResolverRegistry createResolverWithDeviceID:serviceName:]
+ -[HAP2BrowserResolverRegistry initWithName:browser:]
+ -[HAP2BrowserResolverRegistry managerQueue]
+ -[HAP2BrowserResolverRegistry name]
+ -[HAP2BrowserResolverRegistry performAuditPassWithActiveDeviceIDs:]
+ -[HAP2BrowserResolverRegistry pipelineFactory]
+ -[HAP2BrowserResolverRegistry propertyLock]
+ -[HAP2BrowserResolverRegistry removeResolverForDeviceID:]
+ -[HAP2BrowserResolverRegistry resolverForDeviceID:]
+ -[HAP2BrowserResolverRegistry resolversByDeviceID]
+ -[HAP2BrowserResolverRegistry setPipelineFactory:]
+ -[HAP2BrowserResolverRegistry updateCachedAddressesForDeviceID:cachedPrimary:cachedSecondary:]
+ -[HAP2BrowserResolverRegistry(Test) _allDeviceIDs]
+ -[HAP2BrowserResolverRegistry(Test) _managerQueue]
+ -[HAP2BrowserResolverRegistry(Test) _pipelineFactory]
+ -[HAP2BrowserResolverRegistry(Test) _privateResolverForDeviceID:]
+ -[HAP2BrowserResolverRegistry(Test) set_pipelineFactory:]
+ -[HAP2CoAPClient _didDisconnectWithError:]
+ -[HAP2CoAPClient _fireProbeCompletionWithResponse:error:]
+ -[HAP2CoAPClient address]
+ -[HAP2CoAPClient didReceivePingInSession:messageID:]
+ -[HAP2CoAPClient getLocalEndpointWithCompletion:]
+ -[HAP2CoAPClient getLocalIPv4EndpointWithCompletion:]
+ -[HAP2CoAPClient getLocalIPv6EndpointWithCompletion:]
+ -[HAP2CoAPClient getRTTStatisticsWithCompletion:]
+ -[HAP2CoAPClient sendProbeWithCompletion:]
+ -[HAP2CoAPClient sendRequestWithMethod:path:payload:messageID:dscpPriority:completion:]
+ -[HAP2DefaultAccessoryAddressResolverPipelineFactory createResolverWithServiceName:serviceType:serviceDomain:queue:updateHandler:errorHandler:]
+ -[HAP2SessionKeepAliveConfigurationEntry initWithTransportType:minimumInterval:maximumInterval:]
+ -[HAP2SessionKeepAliveConfigurationEntry maximumInterval]
+ -[HAP2SessionKeepAliveConfigurationEntry minimumInterval]
+ -[HAP2SessionKeepAliveConfigurationEntry transportType]
+ -[HAP2SessionKeepAliveListener .cxx_destruct]
+ -[HAP2SessionKeepAliveListener _copyDelegates]
+ -[HAP2SessionKeepAliveListener _handleTimerFireForTransport:]
+ -[HAP2SessionKeepAliveListener addDelegate:]
+ -[HAP2SessionKeepAliveListener dateProvider]
+ -[HAP2SessionKeepAliveListener dealloc]
+ -[HAP2SessionKeepAliveListener delegates]
+ -[HAP2SessionKeepAliveListener didReceiveHeartbeatOnTransport:]
+ -[HAP2SessionKeepAliveListener hasMissedHeartbeatForTransport:]
+ -[HAP2SessionKeepAliveListener initWithConfigurationEntries:workQueue:]
+ -[HAP2SessionKeepAliveListener initWithConfigurationEntries:workQueue:timerProvider:dateProvider:]
+ -[HAP2SessionKeepAliveListener isRunning]
+ -[HAP2SessionKeepAliveListener isTrackingTransport:]
+ -[HAP2SessionKeepAliveListener logIdentifier]
+ -[HAP2SessionKeepAliveListener missCheckTimer]
+ -[HAP2SessionKeepAliveListener removeDelegate:]
+ -[HAP2SessionKeepAliveListener resetHeartbeatTimestamps]
+ -[HAP2SessionKeepAliveListener setDateProvider:]
+ -[HAP2SessionKeepAliveListener setDelegates:]
+ -[HAP2SessionKeepAliveListener setIsRunning:]
+ -[HAP2SessionKeepAliveListener setMissCheckTimer:]
+ -[HAP2SessionKeepAliveListener setTimerProvider:]
+ -[HAP2SessionKeepAliveListener setTransportStates:]
+ -[HAP2SessionKeepAliveListener setWorkQueue:]
+ -[HAP2SessionKeepAliveListener start]
+ -[HAP2SessionKeepAliveListener stop]
+ -[HAP2SessionKeepAliveListener timeSinceLastHeartbeatForTransport:]
+ -[HAP2SessionKeepAliveListener timerDidFire:]
+ -[HAP2SessionKeepAliveListener timerProvider]
+ -[HAP2SessionKeepAliveListener trackedTransportTypes]
+ -[HAP2SessionKeepAliveListener transportStates]
+ -[HAP2SessionKeepAliveListener workQueue]
+ -[HAP2SessionKeepAliveTransportState .cxx_destruct]
+ -[HAP2SessionKeepAliveTransportState hasMissedHeartbeat]
+ -[HAP2SessionKeepAliveTransportState initWithTransportType:maximumInterval:]
+ -[HAP2SessionKeepAliveTransportState lastHeartbeatTime]
+ -[HAP2SessionKeepAliveTransportState maximumInterval]
+ -[HAP2SessionKeepAliveTransportState setHasMissedHeartbeat:]
+ -[HAP2SessionKeepAliveTransportState setLastHeartbeatTime:]
+ -[HAP2SessionKeepAliveTransportState transportType]
+ -[HAPAccessoryServer configureKeepAliveListener:]
+ -[HAPAccessoryServer hasThreadAdvertisement]
+ -[HAPAccessoryServer hasWiFiAdvertisement]
+ -[HAPAccessoryServer lastPairSetupWasSpake2]
+ -[HAPAccessoryServer setHasThreadAdvertisement:]
+ -[HAPAccessoryServer setHasWiFiAdvertisement:]
+ -[HAPAccessoryServer setLastPairSetupWasSpake2:]
+ -[HAPAccessoryServerBrowserHAP2Adapter setIPCache:]
+ -[HAPAccessoryServerHAP2Adapter accessoryServer:didUpdateLocalEndpoints:]
+ -[HAPAccessoryServerHAP2Adapter configureKeepAliveListener:]
+ -[HAPAccessoryServerHAP2Adapter dataStreamPeerAddressWithCompletion:]
+ -[HAPAccessoryServerHAP2Adapter deriveEncryptionForDataStreamWithKeySalt:completionHandler:]
+ -[HAPAccessoryServerHAP2Adapter hasThreadAdvertisement]
+ -[HAPAccessoryServerHAP2Adapter hasWiFiAdvertisement]
+ -[HAPAccessoryServerIP hasWiFiAdvertisement]
+ -[HAPBluetoothMetrics .cxx_destruct]
+ -[HAPBluetoothMetrics bluetoothVersion]
+ -[HAPBluetoothMetrics connectionCount]
+ -[HAPBluetoothMetrics connectionErrorCount]
+ -[HAPBluetoothMetrics connectionStatus]
+ -[HAPBluetoothMetrics copyWithZone:]
+ -[HAPBluetoothMetrics description]
+ -[HAPBluetoothMetrics disconnectionCount]
+ -[HAPBluetoothMetrics disconnectionErrorCount]
+ -[HAPBluetoothMetrics hwExceptionCount]
+ -[HAPBluetoothMetrics initWithBluetoothVersion:rssi:txPowerLevel:packetRxCount:packetTxCount:packetRxErrorCount:packetTxErrorCount:overrunCount:connectionStatus:connectionCount:connectionErrorCount:disconnectionCount:disconnectionErrorCount:hwExceptionCount:]
+ -[HAPBluetoothMetrics init]
+ -[HAPBluetoothMetrics isEqual:]
+ -[HAPBluetoothMetrics overrunCount]
+ -[HAPBluetoothMetrics packetRxCount]
+ -[HAPBluetoothMetrics packetRxErrorCount]
+ -[HAPBluetoothMetrics packetTxCount]
+ -[HAPBluetoothMetrics packetTxErrorCount]
+ -[HAPBluetoothMetrics parseFromData:error:]
+ -[HAPBluetoothMetrics rssi]
+ -[HAPBluetoothMetrics serializeWithError:]
+ -[HAPBluetoothMetrics setBluetoothVersion:]
+ -[HAPBluetoothMetrics setConnectionCount:]
+ -[HAPBluetoothMetrics setConnectionErrorCount:]
+ -[HAPBluetoothMetrics setConnectionStatus:]
+ -[HAPBluetoothMetrics setDisconnectionCount:]
+ -[HAPBluetoothMetrics setDisconnectionErrorCount:]
+ -[HAPBluetoothMetrics setHwExceptionCount:]
+ -[HAPBluetoothMetrics setOverrunCount:]
+ -[HAPBluetoothMetrics setPacketRxCount:]
+ -[HAPBluetoothMetrics setPacketRxErrorCount:]
+ -[HAPBluetoothMetrics setPacketTxCount:]
+ -[HAPBluetoothMetrics setPacketTxErrorCount:]
+ -[HAPBluetoothMetrics setRssi:]
+ -[HAPBluetoothMetrics setTxPowerLevel:]
+ -[HAPBluetoothMetrics txPowerLevel]
+ -[HAPBootReasonsMetrics .cxx_destruct]
+ -[HAPBootReasonsMetrics brownOutResetBootCount]
+ -[HAPBootReasonsMetrics connectivityMonitorBootCount]
+ -[HAPBootReasonsMetrics copyWithZone:]
+ -[HAPBootReasonsMetrics description]
+ -[HAPBootReasonsMetrics hardwareFaultBootCount]
+ -[HAPBootReasonsMetrics hardwareWatchdogResetBootCount]
+ -[HAPBootReasonsMetrics heapOverflowBootCount]
+ -[HAPBootReasonsMetrics initWithUnspecifiedBootCount:powerOnBootCount:brownOutResetBootCount:softwareWatchdogResetBootCount:hardwareWatchdogResetBootCount:softwareUpdateCompletedBootCount:softwareResetBootCount:softwareExceptionBootCount:hardwareFaultBootCount:stackOverflowBootCount:heapOverflowBootCount:temperatureLimitBootCount:connectivityMonitorBootCount:]
+ -[HAPBootReasonsMetrics init]
+ -[HAPBootReasonsMetrics isEqual:]
+ -[HAPBootReasonsMetrics parseFromData:error:]
+ -[HAPBootReasonsMetrics powerOnBootCount]
+ -[HAPBootReasonsMetrics serializeWithError:]
+ -[HAPBootReasonsMetrics setBrownOutResetBootCount:]
+ -[HAPBootReasonsMetrics setConnectivityMonitorBootCount:]
+ -[HAPBootReasonsMetrics setHardwareFaultBootCount:]
+ -[HAPBootReasonsMetrics setHardwareWatchdogResetBootCount:]
+ -[HAPBootReasonsMetrics setHeapOverflowBootCount:]
+ -[HAPBootReasonsMetrics setPowerOnBootCount:]
+ -[HAPBootReasonsMetrics setSoftwareExceptionBootCount:]
+ -[HAPBootReasonsMetrics setSoftwareResetBootCount:]
+ -[HAPBootReasonsMetrics setSoftwareUpdateCompletedBootCount:]
+ -[HAPBootReasonsMetrics setSoftwareWatchdogResetBootCount:]
+ -[HAPBootReasonsMetrics setStackOverflowBootCount:]
+ -[HAPBootReasonsMetrics setTemperatureLimitBootCount:]
+ -[HAPBootReasonsMetrics setUnspecifiedBootCount:]
+ -[HAPBootReasonsMetrics softwareExceptionBootCount]
+ -[HAPBootReasonsMetrics softwareResetBootCount]
+ -[HAPBootReasonsMetrics softwareUpdateCompletedBootCount]
+ -[HAPBootReasonsMetrics softwareWatchdogResetBootCount]
+ -[HAPBootReasonsMetrics stackOverflowBootCount]
+ -[HAPBootReasonsMetrics temperatureLimitBootCount]
+ -[HAPBootReasonsMetrics unspecifiedBootCount]
+ -[HAPCHMMetrics .cxx_destruct]
+ -[HAPCHMMetrics chmAccessoryRebootCompleted]
+ -[HAPCHMMetrics chmAccessoryRebootDurationToRecovery]
+ -[HAPCHMMetrics copyWithZone:]
+ -[HAPCHMMetrics description]
+ -[HAPCHMMetrics hapSessionLossCount]
+ -[HAPCHMMetrics initWithWifiTransportLossCount:wifiRecoveryAttemptCount:wifiRestartCount:wifiFirstRestartRecoveryTime:wifiFirstRestartCompleted:wifiFirstRestartConnectivityState:threadTransportLossCount:threadRecoveryAttemptCount:threadRestartCount:threadFirstRestartRecoveryTime:threadFirstRestartCompleted:threadFirstRestartConnectivityState:hapSessionLossCount:chmAccessoryRebootDurationToRecovery:chmAccessoryRebootCompleted:]
+ -[HAPCHMMetrics init]
+ -[HAPCHMMetrics isEqual:]
+ -[HAPCHMMetrics parseFromData:error:]
+ -[HAPCHMMetrics serializeWithError:]
+ -[HAPCHMMetrics setChmAccessoryRebootCompleted:]
+ -[HAPCHMMetrics setChmAccessoryRebootDurationToRecovery:]
+ -[HAPCHMMetrics setHapSessionLossCount:]
+ -[HAPCHMMetrics setThreadFirstRestartCompleted:]
+ -[HAPCHMMetrics setThreadFirstRestartConnectivityState:]
+ -[HAPCHMMetrics setThreadFirstRestartRecoveryTime:]
+ -[HAPCHMMetrics setThreadRecoveryAttemptCount:]
+ -[HAPCHMMetrics setThreadRestartCount:]
+ -[HAPCHMMetrics setThreadTransportLossCount:]
+ -[HAPCHMMetrics setWifiFirstRestartCompleted:]
+ -[HAPCHMMetrics setWifiFirstRestartConnectivityState:]
+ -[HAPCHMMetrics setWifiFirstRestartRecoveryTime:]
+ -[HAPCHMMetrics setWifiRecoveryAttemptCount:]
+ -[HAPCHMMetrics setWifiRestartCount:]
+ -[HAPCHMMetrics setWifiTransportLossCount:]
+ -[HAPCHMMetrics threadFirstRestartCompleted]
+ -[HAPCHMMetrics threadFirstRestartConnectivityState]
+ -[HAPCHMMetrics threadFirstRestartRecoveryTime]
+ -[HAPCHMMetrics threadRecoveryAttemptCount]
+ -[HAPCHMMetrics threadRestartCount]
+ -[HAPCHMMetrics threadTransportLossCount]
+ -[HAPCHMMetrics wifiFirstRestartCompleted]
+ -[HAPCHMMetrics wifiFirstRestartConnectivityState]
+ -[HAPCHMMetrics wifiFirstRestartRecoveryTime]
+ -[HAPCHMMetrics wifiRecoveryAttemptCount]
+ -[HAPCHMMetrics wifiRestartCount]
+ -[HAPCHMMetrics wifiTransportLossCount]
+ -[HAPCharacteristicResponseTuple coapMessageID]
+ -[HAPCharacteristicResponseTuple setCoapMessageID:]
+ -[HAPConnectionHealthMonitor .cxx_destruct]
+ -[HAPConnectionHealthMonitor copyWithZone:]
+ -[HAPConnectionHealthMonitor description]
+ -[HAPConnectionHealthMonitor deviceRebootDelay]
+ -[HAPConnectionHealthMonitor deviceRebootEnable]
+ -[HAPConnectionHealthMonitor initWithDeviceRebootEnable:threadRecoveryConfiguration:wiFiRecoveryConfiguration:recoveryStaggerDelay:deviceRebootDelay:threadPingTestCount:threadPingTestInterval:threadRestartMinInterval:wiFiPingTestCount:wiFiPingTestInterval:wiFiRestartMinInterval:]
+ -[HAPConnectionHealthMonitor init]
+ -[HAPConnectionHealthMonitor isEqual:]
+ -[HAPConnectionHealthMonitor parseFromData:error:]
+ -[HAPConnectionHealthMonitor recoveryStaggerDelay]
+ -[HAPConnectionHealthMonitor serializeWithError:]
+ -[HAPConnectionHealthMonitor setDeviceRebootDelay:]
+ -[HAPConnectionHealthMonitor setDeviceRebootEnable:]
+ -[HAPConnectionHealthMonitor setRecoveryStaggerDelay:]
+ -[HAPConnectionHealthMonitor setThreadPingTestCount:]
+ -[HAPConnectionHealthMonitor setThreadPingTestInterval:]
+ -[HAPConnectionHealthMonitor setThreadRecoveryConfiguration:]
+ -[HAPConnectionHealthMonitor setThreadRestartMinInterval:]
+ -[HAPConnectionHealthMonitor setWiFiPingTestCount:]
+ -[HAPConnectionHealthMonitor setWiFiPingTestInterval:]
+ -[HAPConnectionHealthMonitor setWiFiRecoveryConfiguration:]
+ -[HAPConnectionHealthMonitor setWiFiRestartMinInterval:]
+ -[HAPConnectionHealthMonitor threadPingTestCount]
+ -[HAPConnectionHealthMonitor threadPingTestInterval]
+ -[HAPConnectionHealthMonitor threadRecoveryConfiguration]
+ -[HAPConnectionHealthMonitor threadRestartMinInterval]
+ -[HAPConnectionHealthMonitor wiFiPingTestCount]
+ -[HAPConnectionHealthMonitor wiFiPingTestInterval]
+ -[HAPConnectionHealthMonitor wiFiRecoveryConfiguration]
+ -[HAPConnectionHealthMonitor wiFiRestartMinInterval]
+ -[HAPErrorCountersMetrics .cxx_destruct]
+ -[HAPErrorCountersMetrics copyWithZone:]
+ -[HAPErrorCountersMetrics description]
+ -[HAPErrorCountersMetrics entries]
+ -[HAPErrorCountersMetrics initWithEntries:]
+ -[HAPErrorCountersMetrics init]
+ -[HAPErrorCountersMetrics isEqual:]
+ -[HAPErrorCountersMetrics parseFromData:error:]
+ -[HAPErrorCountersMetrics serializeWithError:]
+ -[HAPErrorCountersMetrics setEntries:]
+ -[HAPErrorCountersMetricsEntry .cxx_destruct]
+ -[HAPErrorCountersMetricsEntry copyWithZone:]
+ -[HAPErrorCountersMetricsEntry count]
+ -[HAPErrorCountersMetricsEntry description]
+ -[HAPErrorCountersMetricsEntry errorID]
+ -[HAPErrorCountersMetricsEntry initWithErrorID:count:]
+ -[HAPErrorCountersMetricsEntry init]
+ -[HAPErrorCountersMetricsEntry isEqual:]
+ -[HAPErrorCountersMetricsEntry parseFromData:error:]
+ -[HAPErrorCountersMetricsEntry serializeWithError:]
+ -[HAPErrorCountersMetricsEntry setCount:]
+ -[HAPErrorCountersMetricsEntry setErrorID:]
+ -[HAPHKSV3UploadLatencyMetrics .cxx_destruct]
+ -[HAPHKSV3UploadLatencyMetrics abandonedRequestCount]
+ -[HAPHKSV3UploadLatencyMetrics audioOnlyFailureCount]
+ -[HAPHKSV3UploadLatencyMetrics authenticationErrorCount]
+ -[HAPHKSV3UploadLatencyMetrics copyWithZone:]
+ -[HAPHKSV3UploadLatencyMetrics description]
+ -[HAPHKSV3UploadLatencyMetrics fragmentFailureCount]
+ -[HAPHKSV3UploadLatencyMetrics fragmentRetriedCount]
+ -[HAPHKSV3UploadLatencyMetrics fragmentSuccessCount]
+ -[HAPHKSV3UploadLatencyMetrics initWithFragmentSuccessCount:fragmentFailureCount:fragmentRetriedCount:networkErrorCount:authenticationErrorCount:serverReturnedErrorCount:localErrorCount:playlistFailureCount:latencyCount250ms:latencyCount500ms:latencyCount1000ms:latencyCount2000ms:latencyCount3750ms:latencyCountOver3750ms:sessionSuccessCount:partialSuccessCount:sessionFailureCount:uploadWithoutResidentResponseCount:audioOnlyFailureCount:abandonedRequestCount:]
+ -[HAPHKSV3UploadLatencyMetrics init]
+ -[HAPHKSV3UploadLatencyMetrics isEqual:]
+ -[HAPHKSV3UploadLatencyMetrics latencyCount1000ms]
+ -[HAPHKSV3UploadLatencyMetrics latencyCount2000ms]
+ -[HAPHKSV3UploadLatencyMetrics latencyCount250ms]
+ -[HAPHKSV3UploadLatencyMetrics latencyCount3750ms]
+ -[HAPHKSV3UploadLatencyMetrics latencyCount500ms]
+ -[HAPHKSV3UploadLatencyMetrics latencyCountOver3750ms]
+ -[HAPHKSV3UploadLatencyMetrics localErrorCount]
+ -[HAPHKSV3UploadLatencyMetrics networkErrorCount]
+ -[HAPHKSV3UploadLatencyMetrics parseFromData:error:]
+ -[HAPHKSV3UploadLatencyMetrics partialSuccessCount]
+ -[HAPHKSV3UploadLatencyMetrics playlistFailureCount]
+ -[HAPHKSV3UploadLatencyMetrics serializeWithError:]
+ -[HAPHKSV3UploadLatencyMetrics serverReturnedErrorCount]
+ -[HAPHKSV3UploadLatencyMetrics sessionFailureCount]
+ -[HAPHKSV3UploadLatencyMetrics sessionSuccessCount]
+ -[HAPHKSV3UploadLatencyMetrics setAbandonedRequestCount:]
+ -[HAPHKSV3UploadLatencyMetrics setAudioOnlyFailureCount:]
+ -[HAPHKSV3UploadLatencyMetrics setAuthenticationErrorCount:]
+ -[HAPHKSV3UploadLatencyMetrics setFragmentFailureCount:]
+ -[HAPHKSV3UploadLatencyMetrics setFragmentRetriedCount:]
+ -[HAPHKSV3UploadLatencyMetrics setFragmentSuccessCount:]
+ -[HAPHKSV3UploadLatencyMetrics setLatencyCount1000ms:]
+ -[HAPHKSV3UploadLatencyMetrics setLatencyCount2000ms:]
+ -[HAPHKSV3UploadLatencyMetrics setLatencyCount250ms:]
+ -[HAPHKSV3UploadLatencyMetrics setLatencyCount3750ms:]
+ -[HAPHKSV3UploadLatencyMetrics setLatencyCount500ms:]
+ -[HAPHKSV3UploadLatencyMetrics setLatencyCountOver3750ms:]
+ -[HAPHKSV3UploadLatencyMetrics setLocalErrorCount:]
+ -[HAPHKSV3UploadLatencyMetrics setNetworkErrorCount:]
+ -[HAPHKSV3UploadLatencyMetrics setPartialSuccessCount:]
+ -[HAPHKSV3UploadLatencyMetrics setPlaylistFailureCount:]
+ -[HAPHKSV3UploadLatencyMetrics setServerReturnedErrorCount:]
+ -[HAPHKSV3UploadLatencyMetrics setSessionFailureCount:]
+ -[HAPHKSV3UploadLatencyMetrics setSessionSuccessCount:]
+ -[HAPHKSV3UploadLatencyMetrics setUploadWithoutResidentResponseCount:]
+ -[HAPHKSV3UploadLatencyMetrics uploadWithoutResidentResponseCount]
+ -[HAPMetricEventBluetoothVersionTypeWrapper copyWithZone:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper description]
+ -[HAPMetricEventBluetoothVersionTypeWrapper initWithValue:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper init]
+ -[HAPMetricEventBluetoothVersionTypeWrapper isEqual:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper parseFromData:error:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper serializeWithError:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper setValue:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper value]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper copyWithZone:]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper description]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper initWithValue:]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper init]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper isEqual:]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper parseFromData:error:]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper serializeWithError:]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper setValue:]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper value]
+ -[HAPMetricEventPowerSourcesEnumWrapper copyWithZone:]
+ -[HAPMetricEventPowerSourcesEnumWrapper description]
+ -[HAPMetricEventPowerSourcesEnumWrapper initWithValue:]
+ -[HAPMetricEventPowerSourcesEnumWrapper init]
+ -[HAPMetricEventPowerSourcesEnumWrapper isEqual:]
+ -[HAPMetricEventPowerSourcesEnumWrapper parseFromData:error:]
+ -[HAPMetricEventPowerSourcesEnumWrapper serializeWithError:]
+ -[HAPMetricEventPowerSourcesEnumWrapper setValue:]
+ -[HAPMetricEventPowerSourcesEnumWrapper value]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper copyWithZone:]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper description]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper initWithValue:]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper init]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper isEqual:]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper parseFromData:error:]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper serializeWithError:]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper setValue:]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper value]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper copyWithZone:]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper description]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper initWithValue:]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper init]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper isEqual:]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper parseFromData:error:]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper serializeWithError:]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper setValue:]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper value]
+ -[HAPMetricEventWiFiVersionTypeWrapper copyWithZone:]
+ -[HAPMetricEventWiFiVersionTypeWrapper description]
+ -[HAPMetricEventWiFiVersionTypeWrapper initWithValue:]
+ -[HAPMetricEventWiFiVersionTypeWrapper init]
+ -[HAPMetricEventWiFiVersionTypeWrapper isEqual:]
+ -[HAPMetricEventWiFiVersionTypeWrapper parseFromData:error:]
+ -[HAPMetricEventWiFiVersionTypeWrapper serializeWithError:]
+ -[HAPMetricEventWiFiVersionTypeWrapper setValue:]
+ -[HAPMetricEventWiFiVersionTypeWrapper value]
+ -[HAPPowerMetrics .cxx_destruct]
+ -[HAPPowerMetrics batteryPercentage]
+ -[HAPPowerMetrics copyWithZone:]
+ -[HAPPowerMetrics currentPowerSource]
+ -[HAPPowerMetrics description]
+ -[HAPPowerMetrics durationOnBatteryPower]
+ -[HAPPowerMetrics durationRemainingOnBatteryPower]
+ -[HAPPowerMetrics initWithSupportedPowerSources:currentPowerSource:durationOnBatteryPower:durationRemainingOnBatteryPower:batteryPercentage:]
+ -[HAPPowerMetrics init]
+ -[HAPPowerMetrics isEqual:]
+ -[HAPPowerMetrics parseFromData:error:]
+ -[HAPPowerMetrics serializeWithError:]
+ -[HAPPowerMetrics setBatteryPercentage:]
+ -[HAPPowerMetrics setCurrentPowerSource:]
+ -[HAPPowerMetrics setDurationOnBatteryPower:]
+ -[HAPPowerMetrics setDurationRemainingOnBatteryPower:]
+ -[HAPPowerMetrics setSupportedPowerSources:]
+ -[HAPPowerMetrics supportedPowerSources]
+ -[HAPSaturationMetrics .cxx_destruct]
+ -[HAPSaturationMetrics averageCPUUtilization]
+ -[HAPSaturationMetrics averageSystemMemoryUtilization]
+ -[HAPSaturationMetrics copyWithZone:]
+ -[HAPSaturationMetrics description]
+ -[HAPSaturationMetrics heapHighwaterCount]
+ -[HAPSaturationMetrics heapOverflowCount]
+ -[HAPSaturationMetrics initWithStackHighwaterCount:lastStackHighwaterTaskName:heapHighwaterCount:lastHeapHighwaterTaskName:stackOverflowCount:lastStackOverflowTaskName:heapOverflowCount:lastHeapOverflowTaskName:averageSystemMemoryUtilization:peakSystemMemoryUtilization:systemMemoryPressureCount:processCriticalMemoryCount:lastProcessCriticalMemoryName:averageCPUUtilization:peakCPUUtilization:taskDeadlineMissCount:totalTasksScheduledCount:maxTaskReadyQueueSize:loadAverage:nonVolatileMemoryWriteCount:nonVolatileMemoryReadCount:nonVolatileMemoryWriteErrorCount:nonVolatileMemoryReadErrorCount:nonVolatileMemoryUtilization:]
+ -[HAPSaturationMetrics init]
+ -[HAPSaturationMetrics isEqual:]
+ -[HAPSaturationMetrics lastHeapHighwaterTaskName]
+ -[HAPSaturationMetrics lastHeapOverflowTaskName]
+ -[HAPSaturationMetrics lastProcessCriticalMemoryName]
+ -[HAPSaturationMetrics lastStackHighwaterTaskName]
+ -[HAPSaturationMetrics lastStackOverflowTaskName]
+ -[HAPSaturationMetrics loadAverage]
+ -[HAPSaturationMetrics maxTaskReadyQueueSize]
+ -[HAPSaturationMetrics nonVolatileMemoryReadCount]
+ -[HAPSaturationMetrics nonVolatileMemoryReadErrorCount]
+ -[HAPSaturationMetrics nonVolatileMemoryUtilization]
+ -[HAPSaturationMetrics nonVolatileMemoryWriteCount]
+ -[HAPSaturationMetrics nonVolatileMemoryWriteErrorCount]
+ -[HAPSaturationMetrics parseFromData:error:]
+ -[HAPSaturationMetrics peakCPUUtilization]
+ -[HAPSaturationMetrics peakSystemMemoryUtilization]
+ -[HAPSaturationMetrics processCriticalMemoryCount]
+ -[HAPSaturationMetrics serializeWithError:]
+ -[HAPSaturationMetrics setAverageCPUUtilization:]
+ -[HAPSaturationMetrics setAverageSystemMemoryUtilization:]
+ -[HAPSaturationMetrics setHeapHighwaterCount:]
+ -[HAPSaturationMetrics setHeapOverflowCount:]
+ -[HAPSaturationMetrics setLastHeapHighwaterTaskName:]
+ -[HAPSaturationMetrics setLastHeapOverflowTaskName:]
+ -[HAPSaturationMetrics setLastProcessCriticalMemoryName:]
+ -[HAPSaturationMetrics setLastStackHighwaterTaskName:]
+ -[HAPSaturationMetrics setLastStackOverflowTaskName:]
+ -[HAPSaturationMetrics setLoadAverage:]
+ -[HAPSaturationMetrics setMaxTaskReadyQueueSize:]
+ -[HAPSaturationMetrics setNonVolatileMemoryReadCount:]
+ -[HAPSaturationMetrics setNonVolatileMemoryReadErrorCount:]
+ -[HAPSaturationMetrics setNonVolatileMemoryUtilization:]
+ -[HAPSaturationMetrics setNonVolatileMemoryWriteCount:]
+ -[HAPSaturationMetrics setNonVolatileMemoryWriteErrorCount:]
+ -[HAPSaturationMetrics setPeakCPUUtilization:]
+ -[HAPSaturationMetrics setPeakSystemMemoryUtilization:]
+ -[HAPSaturationMetrics setProcessCriticalMemoryCount:]
+ -[HAPSaturationMetrics setStackHighwaterCount:]
+ -[HAPSaturationMetrics setStackOverflowCount:]
+ -[HAPSaturationMetrics setSystemMemoryPressureCount:]
+ -[HAPSaturationMetrics setTaskDeadlineMissCount:]
+ -[HAPSaturationMetrics setTotalTasksScheduledCount:]
+ -[HAPSaturationMetrics stackHighwaterCount]
+ -[HAPSaturationMetrics stackOverflowCount]
+ -[HAPSaturationMetrics systemMemoryPressureCount]
+ -[HAPSaturationMetrics taskDeadlineMissCount]
+ -[HAPSaturationMetrics totalTasksScheduledCount]
+ -[HAPSecuritySession deriveEncryptionForDataStreamWithKeySalt:completionHandler:]
+ -[HAPSecuritySession foreignPairVerifySession]
+ -[HAPSecuritySession setForeignPairVerifySession:]
+ -[HAPSessionKeepAliveTransportTypeWrapper copyWithZone:]
+ -[HAPSessionKeepAliveTransportTypeWrapper description]
+ -[HAPSessionKeepAliveTransportTypeWrapper initWithValue:]
+ -[HAPSessionKeepAliveTransportTypeWrapper init]
+ -[HAPSessionKeepAliveTransportTypeWrapper isEqual:]
+ -[HAPSessionKeepAliveTransportTypeWrapper parseFromData:error:]
+ -[HAPSessionKeepAliveTransportTypeWrapper serializeWithError:]
+ -[HAPSessionKeepAliveTransportTypeWrapper setValue:]
+ -[HAPSessionKeepAliveTransportTypeWrapper value]
+ -[HAPStabilityMetrics .cxx_destruct]
+ -[HAPStabilityMetrics activeHardwareFaults]
+ -[HAPStabilityMetrics copyWithZone:]
+ -[HAPStabilityMetrics description]
+ -[HAPStabilityMetrics expectedBootCount]
+ -[HAPStabilityMetrics initWithSystemUptime:systemBootCount:expectedBootCount:systemCrashCount:systemHangCount:lastBootReason:activeHardwareFaults:]
+ -[HAPStabilityMetrics init]
+ -[HAPStabilityMetrics isEqual:]
+ -[HAPStabilityMetrics lastBootReason]
+ -[HAPStabilityMetrics parseFromData:error:]
+ -[HAPStabilityMetrics serializeWithError:]
+ -[HAPStabilityMetrics setActiveHardwareFaults:]
+ -[HAPStabilityMetrics setExpectedBootCount:]
+ -[HAPStabilityMetrics setLastBootReason:]
+ -[HAPStabilityMetrics setSystemBootCount:]
+ -[HAPStabilityMetrics setSystemCrashCount:]
+ -[HAPStabilityMetrics setSystemHangCount:]
+ -[HAPStabilityMetrics setSystemUptime:]
+ -[HAPStabilityMetrics systemBootCount]
+ -[HAPStabilityMetrics systemCrashCount]
+ -[HAPStabilityMetrics systemHangCount]
+ -[HAPStabilityMetrics systemUptime]
+ -[HAPStabilityMetricsBootReasonTypeWrapper copyWithZone:]
+ -[HAPStabilityMetricsBootReasonTypeWrapper description]
+ -[HAPStabilityMetricsBootReasonTypeWrapper initWithValue:]
+ -[HAPStabilityMetricsBootReasonTypeWrapper init]
+ -[HAPStabilityMetricsBootReasonTypeWrapper isEqual:]
+ -[HAPStabilityMetricsBootReasonTypeWrapper parseFromData:error:]
+ -[HAPStabilityMetricsBootReasonTypeWrapper serializeWithError:]
+ -[HAPStabilityMetricsBootReasonTypeWrapper setValue:]
+ -[HAPStabilityMetricsBootReasonTypeWrapper value]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper copyWithZone:]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper description]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper initWithValue:]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper init]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper isEqual:]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper parseFromData:error:]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper serializeWithError:]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper setValue:]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper value]
+ -[HAPTLVPreferredWiFiEntry .cxx_destruct]
+ -[HAPTLVPreferredWiFiEntry PSK]
+ -[HAPTLVPreferredWiFiEntry SSID]
+ -[HAPTLVPreferredWiFiEntry copyWithZone:]
+ -[HAPTLVPreferredWiFiEntry description]
+ -[HAPTLVPreferredWiFiEntry initWithSSID:securityMode:PSK:]
+ -[HAPTLVPreferredWiFiEntry init]
+ -[HAPTLVPreferredWiFiEntry isEqual:]
+ -[HAPTLVPreferredWiFiEntry parseFromData:error:]
+ -[HAPTLVPreferredWiFiEntry securityMode]
+ -[HAPTLVPreferredWiFiEntry serializeWithError:]
+ -[HAPTLVPreferredWiFiEntry setPSK:]
+ -[HAPTLVPreferredWiFiEntry setSSID:]
+ -[HAPTLVPreferredWiFiEntry setSecurityMode:]
+ -[HAPTLVPreferredWiFiList .cxx_destruct]
+ -[HAPTLVPreferredWiFiList copyWithZone:]
+ -[HAPTLVPreferredWiFiList description]
+ -[HAPTLVPreferredWiFiList initWithPreferredWiFiList:]
+ -[HAPTLVPreferredWiFiList init]
+ -[HAPTLVPreferredWiFiList isEqual:]
+ -[HAPTLVPreferredWiFiList parseFromData:error:]
+ -[HAPTLVPreferredWiFiList preferredWiFiList]
+ -[HAPTLVPreferredWiFiList serializeWithError:]
+ -[HAPTLVPreferredWiFiList setPreferredWiFiList:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry .cxx_destruct]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry copyWithZone:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry description]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry initWithTransportType:minimumInterval:maximumInterval:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry init]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry isEqual:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry maximumInterval]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry minimumInterval]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry parseFromData:error:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry serializeWithError:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry setMaximumInterval:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry setMinimumInterval:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry setTransportType:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry transportType]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList .cxx_destruct]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList copyWithZone:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList description]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList entries]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList initWithEntries:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList init]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList isEqual:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList parseFromData:error:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList serializeWithError:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList setEntries:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry .cxx_destruct]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry copyWithZone:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry description]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry initWithTransportType:minimumInterval:maximumInterval:minimumRange:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry init]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry isEqual:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry maximumInterval]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry minimumInterval]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry minimumRange]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry parseFromData:error:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry serializeWithError:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry setMaximumInterval:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry setMinimumInterval:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry setMinimumRange:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry setTransportType:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry transportType]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList .cxx_destruct]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList copyWithZone:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList description]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList entries]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList initWithEntries:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList init]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList isEqual:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList parseFromData:error:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList serializeWithError:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList setEntries:]
+ -[HAPThermalMetrics .cxx_destruct]
+ -[HAPThermalMetrics averageDeviceTemperature]
+ -[HAPThermalMetrics copyWithZone:]
+ -[HAPThermalMetrics description]
+ -[HAPThermalMetrics initWithTemperatureLimitViolationCount:temperatureLimitViolationDuration:minimumDeviceTemperature:maximumDeviceTemperature:averageDeviceTemperature:]
+ -[HAPThermalMetrics init]
+ -[HAPThermalMetrics isEqual:]
+ -[HAPThermalMetrics maximumDeviceTemperature]
+ -[HAPThermalMetrics minimumDeviceTemperature]
+ -[HAPThermalMetrics parseFromData:error:]
+ -[HAPThermalMetrics serializeWithError:]
+ -[HAPThermalMetrics setAverageDeviceTemperature:]
+ -[HAPThermalMetrics setMaximumDeviceTemperature:]
+ -[HAPThermalMetrics setMinimumDeviceTemperature:]
+ -[HAPThermalMetrics setTemperatureLimitViolationCount:]
+ -[HAPThermalMetrics setTemperatureLimitViolationDuration:]
+ -[HAPThermalMetrics temperatureLimitViolationCount]
+ -[HAPThermalMetrics temperatureLimitViolationDuration]
+ -[HAPWiFiMetrics .cxx_destruct]
+ -[HAPWiFiMetrics beaconLostCount]
+ -[HAPWiFiMetrics beaconRxCount]
+ -[HAPWiFiMetrics beaconRxInterval]
+ -[HAPWiFiMetrics bssid]
+ -[HAPWiFiMetrics channelNumber]
+ -[HAPWiFiMetrics connectionStatus]
+ -[HAPWiFiMetrics copyWithZone:]
+ -[HAPWiFiMetrics description]
+ -[HAPWiFiMetrics disconnectionCount]
+ -[HAPWiFiMetrics disconnectionDuration]
+ -[HAPWiFiMetrics gatewayIPv4Address]
+ -[HAPWiFiMetrics gatewayIPv6Address]
+ -[HAPWiFiMetrics gatewayMacAddress]
+ -[HAPWiFiMetrics hwExceptionCount]
+ -[HAPWiFiMetrics initWithGatewayMacAddress:gatewayIPv4Address:gatewayIPv6Address:subnetMask:bssid:wifiVersion:channelNumber:rssi:connectionStatus:disconnectionCount:disconnectionDuration:beaconRxCount:beaconRxInterval:beaconLostCount:ipAddressList:packetMulticastRxCount:packetMulticastRxErrorCount:packetMulticastTxCount:packetMulticastTxErrorCount:packetUnicastRxCount:packetUnicastRxErrorCount:packetUnicastTxCount:packetUnicastTxErrorCount:txPacketCount:txPacketErrorCount:rxPacketCount:rxPacketErrorCount:hwExceptionCount:wifiRestartCount:]
+ -[HAPWiFiMetrics init]
+ -[HAPWiFiMetrics ipAddressList]
+ -[HAPWiFiMetrics isEqual:]
+ -[HAPWiFiMetrics packetMulticastRxCount]
+ -[HAPWiFiMetrics packetMulticastRxErrorCount]
+ -[HAPWiFiMetrics packetMulticastTxCount]
+ -[HAPWiFiMetrics packetMulticastTxErrorCount]
+ -[HAPWiFiMetrics packetUnicastRxCount]
+ -[HAPWiFiMetrics packetUnicastRxErrorCount]
+ -[HAPWiFiMetrics packetUnicastTxCount]
+ -[HAPWiFiMetrics packetUnicastTxErrorCount]
+ -[HAPWiFiMetrics parseFromData:error:]
+ -[HAPWiFiMetrics rssi]
+ -[HAPWiFiMetrics rxPacketCount]
+ -[HAPWiFiMetrics rxPacketErrorCount]
+ -[HAPWiFiMetrics serializeWithError:]
+ -[HAPWiFiMetrics setBeaconLostCount:]
+ -[HAPWiFiMetrics setBeaconRxCount:]
+ -[HAPWiFiMetrics setBeaconRxInterval:]
+ -[HAPWiFiMetrics setBssid:]
+ -[HAPWiFiMetrics setChannelNumber:]
+ -[HAPWiFiMetrics setConnectionStatus:]
+ -[HAPWiFiMetrics setDisconnectionCount:]
+ -[HAPWiFiMetrics setDisconnectionDuration:]
+ -[HAPWiFiMetrics setGatewayIPv4Address:]
+ -[HAPWiFiMetrics setGatewayIPv6Address:]
+ -[HAPWiFiMetrics setGatewayMacAddress:]
+ -[HAPWiFiMetrics setHwExceptionCount:]
+ -[HAPWiFiMetrics setIpAddressList:]
+ -[HAPWiFiMetrics setPacketMulticastRxCount:]
+ -[HAPWiFiMetrics setPacketMulticastRxErrorCount:]
+ -[HAPWiFiMetrics setPacketMulticastTxCount:]
+ -[HAPWiFiMetrics setPacketMulticastTxErrorCount:]
+ -[HAPWiFiMetrics setPacketUnicastRxCount:]
+ -[HAPWiFiMetrics setPacketUnicastRxErrorCount:]
+ -[HAPWiFiMetrics setPacketUnicastTxCount:]
+ -[HAPWiFiMetrics setPacketUnicastTxErrorCount:]
+ -[HAPWiFiMetrics setRssi:]
+ -[HAPWiFiMetrics setRxPacketCount:]
+ -[HAPWiFiMetrics setRxPacketErrorCount:]
+ -[HAPWiFiMetrics setSubnetMask:]
+ -[HAPWiFiMetrics setTxPacketCount:]
+ -[HAPWiFiMetrics setTxPacketErrorCount:]
+ -[HAPWiFiMetrics setWifiRestartCount:]
+ -[HAPWiFiMetrics setWifiVersion:]
+ -[HAPWiFiMetrics subnetMask]
+ -[HAPWiFiMetrics txPacketCount]
+ -[HAPWiFiMetrics txPacketErrorCount]
+ -[HAPWiFiMetrics wifiRestartCount]
+ -[HAPWiFiMetrics wifiVersion]
+ GCC_except_table10066
+ GCC_except_table10068
+ GCC_except_table10070
+ GCC_except_table10073
+ GCC_except_table10075
+ GCC_except_table10077
+ GCC_except_table10079
+ GCC_except_table10080
+ GCC_except_table10087
+ GCC_except_table10089
+ GCC_except_table10090
+ GCC_except_table1012
+ GCC_except_table1017
+ GCC_except_table1164
+ GCC_except_table1166
+ GCC_except_table1235
+ GCC_except_table1237
+ GCC_except_table1239
+ GCC_except_table1779
+ GCC_except_table1784
+ GCC_except_table1788
+ GCC_except_table1802
+ GCC_except_table1816
+ GCC_except_table1818
+ GCC_except_table1822
+ GCC_except_table1952
+ GCC_except_table1958
+ GCC_except_table1960
+ GCC_except_table2162
+ GCC_except_table232
+ GCC_except_table233
+ GCC_except_table2378
+ GCC_except_table2380
+ GCC_except_table2385
+ GCC_except_table2391
+ GCC_except_table2393
+ GCC_except_table2399
+ GCC_except_table2401
+ GCC_except_table2405
+ GCC_except_table2413
+ GCC_except_table2417
+ GCC_except_table2423
+ GCC_except_table2425
+ GCC_except_table2427
+ GCC_except_table2429
+ GCC_except_table2435
+ GCC_except_table2439
+ GCC_except_table2447
+ GCC_except_table2449
+ GCC_except_table245
+ GCC_except_table246
+ GCC_except_table2462
+ GCC_except_table2470
+ GCC_except_table2477
+ GCC_except_table2481
+ GCC_except_table2485
+ GCC_except_table2527
+ GCC_except_table255
+ GCC_except_table256
+ GCC_except_table258
+ GCC_except_table2646
+ GCC_except_table2651
+ GCC_except_table2652
+ GCC_except_table2654
+ GCC_except_table2656
+ GCC_except_table2668
+ GCC_except_table2673
+ GCC_except_table2677
+ GCC_except_table2680
+ GCC_except_table2682
+ GCC_except_table2687
+ GCC_except_table270
+ GCC_except_table2704
+ GCC_except_table2714
+ GCC_except_table2716
+ GCC_except_table2718
+ GCC_except_table272
+ GCC_except_table2723
+ GCC_except_table2726
+ GCC_except_table2728
+ GCC_except_table273
+ GCC_except_table2731
+ GCC_except_table2734
+ GCC_except_table2738
+ GCC_except_table2740
+ GCC_except_table2743
+ GCC_except_table2748
+ GCC_except_table2750
+ GCC_except_table2752
+ GCC_except_table2756
+ GCC_except_table276
+ GCC_except_table2762
+ GCC_except_table2770
+ GCC_except_table2783
+ GCC_except_table280
+ GCC_except_table2826
+ GCC_except_table2827
+ GCC_except_table2828
+ GCC_except_table2830
+ GCC_except_table2831
+ GCC_except_table2832
+ GCC_except_table2838
+ GCC_except_table2839
+ GCC_except_table2865
+ GCC_except_table2869
+ GCC_except_table2873
+ GCC_except_table289
+ GCC_except_table295
+ GCC_except_table299
+ GCC_except_table301
+ GCC_except_table3075
+ GCC_except_table3083
+ GCC_except_table3084
+ GCC_except_table3085
+ GCC_except_table3086
+ GCC_except_table3087
+ GCC_except_table3088
+ GCC_except_table3118
+ GCC_except_table3198
+ GCC_except_table3210
+ GCC_except_table3414
+ GCC_except_table3423
+ GCC_except_table3441
+ GCC_except_table3475
+ GCC_except_table3491
+ GCC_except_table3493
+ GCC_except_table3505
+ GCC_except_table3512
+ GCC_except_table3550
+ GCC_except_table3553
+ GCC_except_table3562
+ GCC_except_table3569
+ GCC_except_table3572
+ GCC_except_table3577
+ GCC_except_table3645
+ GCC_except_table3648
+ GCC_except_table3653
+ GCC_except_table3671
+ GCC_except_table3687
+ GCC_except_table3689
+ GCC_except_table3693
+ GCC_except_table3773
+ GCC_except_table3780
+ GCC_except_table3782
+ GCC_except_table3783
+ GCC_except_table3826
+ GCC_except_table4054
+ GCC_except_table4129
+ GCC_except_table4136
+ GCC_except_table4140
+ GCC_except_table4142
+ GCC_except_table4144
+ GCC_except_table4146
+ GCC_except_table4150
+ GCC_except_table4153
+ GCC_except_table4159
+ GCC_except_table4170
+ GCC_except_table4172
+ GCC_except_table4175
+ GCC_except_table4178
+ GCC_except_table4181
+ GCC_except_table4185
+ GCC_except_table4188
+ GCC_except_table4205
+ GCC_except_table4208
+ GCC_except_table4220
+ GCC_except_table4222
+ GCC_except_table4227
+ GCC_except_table4231
+ GCC_except_table4236
+ GCC_except_table4239
+ GCC_except_table4251
+ GCC_except_table4253
+ GCC_except_table4257
+ GCC_except_table4261
+ GCC_except_table4283
+ GCC_except_table4325
+ GCC_except_table4335
+ GCC_except_table4339
+ GCC_except_table4341
+ GCC_except_table4346
+ GCC_except_table4348
+ GCC_except_table4356
+ GCC_except_table4358
+ GCC_except_table4359
+ GCC_except_table4361
+ GCC_except_table4362
+ GCC_except_table4364
+ GCC_except_table4446
+ GCC_except_table4447
+ GCC_except_table4448
+ GCC_except_table4449
+ GCC_except_table4450
+ GCC_except_table4451
+ GCC_except_table4452
+ GCC_except_table4453
+ GCC_except_table4454
+ GCC_except_table4455
+ GCC_except_table4456
+ GCC_except_table4457
+ GCC_except_table4458
+ GCC_except_table4459
+ GCC_except_table4460
+ GCC_except_table4513
+ GCC_except_table4599
+ GCC_except_table4601
+ GCC_except_table4603
+ GCC_except_table4638
+ GCC_except_table4649
+ GCC_except_table4670
+ GCC_except_table4678
+ GCC_except_table4689
+ GCC_except_table4703
+ GCC_except_table4706
+ GCC_except_table4711
+ GCC_except_table4719
+ GCC_except_table4725
+ GCC_except_table4727
+ GCC_except_table4729
+ GCC_except_table4740
+ GCC_except_table4773
+ GCC_except_table4776
+ GCC_except_table4777
+ GCC_except_table4783
+ GCC_except_table4785
+ GCC_except_table4791
+ GCC_except_table4792
+ GCC_except_table4797
+ GCC_except_table4798
+ GCC_except_table4804
+ GCC_except_table4813
+ GCC_except_table4815
+ GCC_except_table4818
+ GCC_except_table4819
+ GCC_except_table4824
+ GCC_except_table4827
+ GCC_except_table4828
+ GCC_except_table4834
+ GCC_except_table4841
+ GCC_except_table4845
+ GCC_except_table4860
+ GCC_except_table4876
+ GCC_except_table4893
+ GCC_except_table4894
+ GCC_except_table4896
+ GCC_except_table4897
+ GCC_except_table4900
+ GCC_except_table4901
+ GCC_except_table4916
+ GCC_except_table4931
+ GCC_except_table4938
+ GCC_except_table4958
+ GCC_except_table4968
+ GCC_except_table4970
+ GCC_except_table5036
+ GCC_except_table5040
+ GCC_except_table5041
+ GCC_except_table5043
+ GCC_except_table5045
+ GCC_except_table5048
+ GCC_except_table5051
+ GCC_except_table5054
+ GCC_except_table5057
+ GCC_except_table5060
+ GCC_except_table5063
+ GCC_except_table5066
+ GCC_except_table5069
+ GCC_except_table5074
+ GCC_except_table5087
+ GCC_except_table5092
+ GCC_except_table5096
+ GCC_except_table5098
+ GCC_except_table5101
+ GCC_except_table5113
+ GCC_except_table5121
+ GCC_except_table5128
+ GCC_except_table5134
+ GCC_except_table5135
+ GCC_except_table5138
+ GCC_except_table5139
+ GCC_except_table5157
+ GCC_except_table5159
+ GCC_except_table5161
+ GCC_except_table5162
+ GCC_except_table5165
+ GCC_except_table5171
+ GCC_except_table5174
+ GCC_except_table5176
+ GCC_except_table5183
+ GCC_except_table5185
+ GCC_except_table5187
+ GCC_except_table5190
+ GCC_except_table5201
+ GCC_except_table5212
+ GCC_except_table5214
+ GCC_except_table5225
+ GCC_except_table5227
+ GCC_except_table5229
+ GCC_except_table5235
+ GCC_except_table5517
+ GCC_except_table5523
+ GCC_except_table5540
+ GCC_except_table5544
+ GCC_except_table5562
+ GCC_except_table5568
+ GCC_except_table5582
+ GCC_except_table5596
+ GCC_except_table5600
+ GCC_except_table571
+ GCC_except_table5744
+ GCC_except_table598
+ GCC_except_table610
+ GCC_except_table6202
+ GCC_except_table6211
+ GCC_except_table6212
+ GCC_except_table6225
+ GCC_except_table6267
+ GCC_except_table6270
+ GCC_except_table6271
+ GCC_except_table6272
+ GCC_except_table6273
+ GCC_except_table6372
+ GCC_except_table6373
+ GCC_except_table6374
+ GCC_except_table6375
+ GCC_except_table6376
+ GCC_except_table6377
+ GCC_except_table6378
+ GCC_except_table6379
+ GCC_except_table6381
+ GCC_except_table6402
+ GCC_except_table6415
+ GCC_except_table6420
+ GCC_except_table6423
+ GCC_except_table6426
+ GCC_except_table6430
+ GCC_except_table6434
+ GCC_except_table644
+ GCC_except_table656
+ GCC_except_table657
+ GCC_except_table659
+ GCC_except_table662
+ GCC_except_table665
+ GCC_except_table679
+ GCC_except_table683
+ GCC_except_table687
+ GCC_except_table694
+ GCC_except_table697
+ GCC_except_table6985
+ GCC_except_table6986
+ GCC_except_table7005
+ GCC_except_table7015
+ GCC_except_table7018
+ GCC_except_table7023
+ GCC_except_table7026
+ GCC_except_table7031
+ GCC_except_table7300
+ GCC_except_table7304
+ GCC_except_table731
+ GCC_except_table7364
+ GCC_except_table7370
+ GCC_except_table7372
+ GCC_except_table741
+ GCC_except_table749
+ GCC_except_table7587
+ GCC_except_table7595
+ GCC_except_table7597
+ GCC_except_table7599
+ GCC_except_table7601
+ GCC_except_table7607
+ GCC_except_table7620
+ GCC_except_table7638
+ GCC_except_table7644
+ GCC_except_table7658
+ GCC_except_table7664
+ GCC_except_table7669
+ GCC_except_table7671
+ GCC_except_table7675
+ GCC_except_table776
+ GCC_except_table7771
+ GCC_except_table7778
+ GCC_except_table7782
+ GCC_except_table7783
+ GCC_except_table7784
+ GCC_except_table7785
+ GCC_except_table7792
+ GCC_except_table780
+ GCC_except_table7808
+ GCC_except_table7844
+ GCC_except_table7845
+ GCC_except_table7846
+ GCC_except_table785
+ GCC_except_table7866
+ GCC_except_table7878
+ GCC_except_table7881
+ GCC_except_table7886
+ GCC_except_table7888
+ GCC_except_table7902
+ GCC_except_table797
+ GCC_except_table799
+ GCC_except_table8137
+ GCC_except_table8150
+ GCC_except_table8155
+ GCC_except_table8158
+ GCC_except_table8159
+ GCC_except_table8161
+ GCC_except_table8162
+ GCC_except_table818
+ GCC_except_table8194
+ GCC_except_table8218
+ GCC_except_table8222
+ GCC_except_table8226
+ GCC_except_table8231
+ GCC_except_table8235
+ GCC_except_table8239
+ GCC_except_table8243
+ GCC_except_table8247
+ GCC_except_table8255
+ GCC_except_table8257
+ GCC_except_table8261
+ GCC_except_table828
+ GCC_except_table8325
+ GCC_except_table8326
+ GCC_except_table8327
+ GCC_except_table8328
+ GCC_except_table8329
+ GCC_except_table8330
+ GCC_except_table8331
+ GCC_except_table839
+ GCC_except_table8396
+ GCC_except_table8409
+ GCC_except_table8410
+ GCC_except_table8415
+ GCC_except_table8416
+ GCC_except_table8423
+ GCC_except_table8435
+ GCC_except_table8441
+ GCC_except_table8443
+ GCC_except_table8445
+ GCC_except_table845
+ GCC_except_table8450
+ GCC_except_table8456
+ GCC_except_table8470
+ GCC_except_table8473
+ GCC_except_table8474
+ GCC_except_table8479
+ GCC_except_table848
+ GCC_except_table8482
+ GCC_except_table8489
+ GCC_except_table8492
+ GCC_except_table8506
+ GCC_except_table851
+ GCC_except_table8513
+ GCC_except_table8519
+ GCC_except_table8528
+ GCC_except_table8530
+ GCC_except_table8536
+ GCC_except_table8537
+ GCC_except_table8544
+ GCC_except_table856
+ GCC_except_table8568
+ GCC_except_table8569
+ GCC_except_table8574
+ GCC_except_table8578
+ GCC_except_table8579
+ GCC_except_table8596
+ GCC_except_table8598
+ GCC_except_table860
+ GCC_except_table8604
+ GCC_except_table866
+ GCC_except_table870
+ GCC_except_table871
+ GCC_except_table8723
+ GCC_except_table8760
+ GCC_except_table8818
+ GCC_except_table8821
+ GCC_except_table8828
+ GCC_except_table8834
+ GCC_except_table8841
+ GCC_except_table8842
+ GCC_except_table8859
+ GCC_except_table8863
+ GCC_except_table8864
+ GCC_except_table8865
+ GCC_except_table8914
+ GCC_except_table8915
+ GCC_except_table8917
+ GCC_except_table8920
+ GCC_except_table8947
+ GCC_except_table8948
+ GCC_except_table8953
+ GCC_except_table8973
+ GCC_except_table8991
+ GCC_except_table8992
+ GCC_except_table8993
+ GCC_except_table8998
+ GCC_except_table8999
+ GCC_except_table9001
+ GCC_except_table9003
+ GCC_except_table9004
+ GCC_except_table9006
+ GCC_except_table9007
+ GCC_except_table9011
+ GCC_except_table9012
+ GCC_except_table9014
+ GCC_except_table9024
+ GCC_except_table9026
+ GCC_except_table9031
+ GCC_except_table9036
+ GCC_except_table9037
+ GCC_except_table9038
+ GCC_except_table9054
+ GCC_except_table9056
+ GCC_except_table906
+ GCC_except_table9063
+ GCC_except_table9070
+ GCC_except_table9075
+ GCC_except_table9081
+ GCC_except_table9093
+ GCC_except_table9094
+ GCC_except_table9099
+ GCC_except_table9109
+ GCC_except_table9116
+ GCC_except_table9117
+ GCC_except_table9121
+ GCC_except_table9123
+ GCC_except_table9125
+ GCC_except_table9129
+ GCC_except_table914
+ GCC_except_table9150
+ GCC_except_table9152
+ GCC_except_table9153
+ GCC_except_table9179
+ GCC_except_table931
+ GCC_except_table9344
+ GCC_except_table9407
+ GCC_except_table9439
+ GCC_except_table9442
+ GCC_except_table953
+ GCC_except_table9609
+ GCC_except_table9647
+ GCC_except_table9684
+ GCC_except_table972
+ GCC_except_table9762
+ GCC_except_table9764
+ GCC_except_table9766
+ GCC_except_table9768
+ GCC_except_table9770
+ GCC_except_table9772
+ GCC_except_table9774
+ GCC_except_table9780
+ GCC_except_table9782
+ GCC_except_table9785
+ GCC_except_table9787
+ GCC_except_table9789
+ GCC_except_table9798
+ GCC_except_table9804
+ GCC_except_table9809
+ GCC_except_table9812
+ GCC_except_table9817
+ GCC_except_table9822
+ GCC_except_table9825
+ GCC_except_table9828
+ GCC_except_table9854
+ GCC_except_table9857
+ GCC_except_table9858
+ GCC_except_table9877
+ GCC_except_table9878
+ GCC_except_table9879
+ GCC_except_table9881
+ GCC_except_table9882
+ GCC_except_table9884
+ GCC_except_table9885
+ GCC_except_table9886
+ GCC_except_table9888
+ GCC_except_table9889
+ GCC_except_table9891
+ GCC_except_table9895
+ GCC_except_table9896
+ GCC_except_table9900
+ GCC_except_table994
+ GCC_except_table9951
+ GCC_except_table9958
+ GCC_except_table998
+ OBJC_IVAR_$_HAP2AccessoryAddressLists._cachedPrimary
+ OBJC_IVAR_$_HAP2AccessoryAddressLists._cachedSecondary
+ OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._cancelled
+ OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._errorHandler
+ OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._gai
+ OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._queue
+ OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._resolvedHostname
+ OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._resolvedPort
+ OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._retainedContext
+ OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._serviceRef
+ OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._updateHandler
+ OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._workingSet
+ OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._workingSetCounts
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._addresses
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._becameEmptyAt
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._cacheSubscriber
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._cachedPrimaryIP
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._cachedSecondaryIP
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._delegates
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._deviceID
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._immediateRetrySpent
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._managerQueue
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._pipelineCancel
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._pipelineFactory
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._pipelineStarted
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._pipelineTornDown
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._propertyLock
+ OBJC_IVAR_$_HAP2AccessoryDNSResolver._serviceName
+ OBJC_IVAR_$_HAP2AccessoryDeviceIPAddress._transportType
+ OBJC_IVAR_$_HAP2AccessoryServer._consecutiveProbeFailures
+ OBJC_IVAR_$_HAP2AccessoryServer._dnsResolver
+ OBJC_IVAR_$_HAP2AccessoryServer._hasSeededSinceResolverAttach
+ OBJC_IVAR_$_HAP2AccessoryServer._hasThreadAdvertisement
+ OBJC_IVAR_$_HAP2AccessoryServer._hasWiFiAdvertisement
+ OBJC_IVAR_$_HAP2AccessoryServer._keepAliveListener
+ OBJC_IVAR_$_HAP2AccessoryServer._lastObservedHasAdvertisement
+ OBJC_IVAR_$_HAP2AccessoryServerBrowser._auditScheduler
+ OBJC_IVAR_$_HAP2AccessoryServerBrowser._existingPTRs
+ OBJC_IVAR_$_HAP2AccessoryServerBrowser._ipCache
+ OBJC_IVAR_$_HAP2AccessoryServerBrowser._isInitialCacheRestored
+ OBJC_IVAR_$_HAP2AccessoryServerBrowser._pendingRevalidationPTRs
+ OBJC_IVAR_$_HAP2AccessoryServerBrowser._resolverRegistry
+ OBJC_IVAR_$_HAP2AccessoryServerBrowser._revalidationTimer
+ OBJC_IVAR_$_HAP2AccessoryServerControllerOperation._coapMessageID
+ OBJC_IVAR_$_HAP2AccessoryServerIPCacheData._cachedPrimaryData
+ OBJC_IVAR_$_HAP2AccessoryServerIPCacheData._cachedSecondaryData
+ OBJC_IVAR_$_HAP2AccessoryServerIPCacheData._configurationInfo
+ OBJC_IVAR_$_HAP2AccessoryServerIPCacheData._deviceID
+ OBJC_IVAR_$_HAP2AccessoryServerTransportBase._supportsKeepAlive
+ OBJC_IVAR_$_HAP2AccessoryServerTransportBase._supportsThreadTransport
+ OBJC_IVAR_$_HAP2AccessoryServerTransportBase._supportsWiFiTransport
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._activeMessageID
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._failoverTimer
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._hasJustCompletedInitialResolve
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._hasPublishedAdvertisementState
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._hasRegisteredEndpoint
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._helloRetryCount
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._helloRetryTimer
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._inFlightRacingLogEvent
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._initialCacheGracePeriodTimer
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._initialConnectionAttemptStartedAt
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._initialResolveCompleted
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._lastCompletedMessageID
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._lastMessageID
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._lastPublishedHasThreadAdvertisement
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._lastPublishedHasWiFiAdvertisement
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._pendingEndpointRegistration
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._pendingIPRefresh
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._primaryEffectiveListIsCacheOnly
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._primaryIPsTriedThisSession
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._primaryOpenInFlight
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._resolveTimeoutTimer
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._resolverCancelBlock
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._resolverRestartTimer
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._secondaryAddressList
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._secondaryCoAPClient
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._secondaryIPsTriedThisSession
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._secondaryOpenInFlight
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._securedClient
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._triedIPsLock
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._tryingInitialCacheOnly
+ OBJC_IVAR_$_HAP2BrowserResolverRegistry._browser
+ OBJC_IVAR_$_HAP2BrowserResolverRegistry._managerQueue
+ OBJC_IVAR_$_HAP2BrowserResolverRegistry._name
+ OBJC_IVAR_$_HAP2BrowserResolverRegistry._pipelineFactory
+ OBJC_IVAR_$_HAP2BrowserResolverRegistry._propertyLock
+ OBJC_IVAR_$_HAP2BrowserResolverRegistry._resolversByDeviceID
+ OBJC_IVAR_$_HAP2CoAPClient._pendingProbeCompletion
+ OBJC_IVAR_$_HAP2CoAPClient._pendingProbeMessageID
+ OBJC_IVAR_$_HAP2SessionKeepAliveConfigurationEntry._maximumInterval
+ OBJC_IVAR_$_HAP2SessionKeepAliveConfigurationEntry._minimumInterval
+ OBJC_IVAR_$_HAP2SessionKeepAliveConfigurationEntry._transportType
+ OBJC_IVAR_$_HAP2SessionKeepAliveListener._dateProvider
+ OBJC_IVAR_$_HAP2SessionKeepAliveListener._delegateLock
+ OBJC_IVAR_$_HAP2SessionKeepAliveListener._delegates
+ OBJC_IVAR_$_HAP2SessionKeepAliveListener._isRunning
+ OBJC_IVAR_$_HAP2SessionKeepAliveListener._missCheckTimer
+ OBJC_IVAR_$_HAP2SessionKeepAliveListener._timerProvider
+ OBJC_IVAR_$_HAP2SessionKeepAliveListener._transportStates
+ OBJC_IVAR_$_HAP2SessionKeepAliveListener._workQueue
+ OBJC_IVAR_$_HAP2SessionKeepAliveTransportState._hasMissedHeartbeat
+ OBJC_IVAR_$_HAP2SessionKeepAliveTransportState._lastHeartbeatTime
+ OBJC_IVAR_$_HAP2SessionKeepAliveTransportState._maximumInterval
+ OBJC_IVAR_$_HAP2SessionKeepAliveTransportState._transportType
+ OBJC_IVAR_$_HAPAccessoryServer._hasThreadAdvertisement
+ OBJC_IVAR_$_HAPAccessoryServer._hasWiFiAdvertisement
+ OBJC_IVAR_$_HAPAccessoryServer._lastPairSetupWasSpake2
+ OBJC_IVAR_$_HAPBluetoothMetrics._bluetoothVersion
+ OBJC_IVAR_$_HAPBluetoothMetrics._connectionCount
+ OBJC_IVAR_$_HAPBluetoothMetrics._connectionErrorCount
+ OBJC_IVAR_$_HAPBluetoothMetrics._connectionStatus
+ OBJC_IVAR_$_HAPBluetoothMetrics._disconnectionCount
+ OBJC_IVAR_$_HAPBluetoothMetrics._disconnectionErrorCount
+ OBJC_IVAR_$_HAPBluetoothMetrics._hwExceptionCount
+ OBJC_IVAR_$_HAPBluetoothMetrics._overrunCount
+ OBJC_IVAR_$_HAPBluetoothMetrics._packetRxCount
+ OBJC_IVAR_$_HAPBluetoothMetrics._packetRxErrorCount
+ OBJC_IVAR_$_HAPBluetoothMetrics._packetTxCount
+ OBJC_IVAR_$_HAPBluetoothMetrics._packetTxErrorCount
+ OBJC_IVAR_$_HAPBluetoothMetrics._rssi
+ OBJC_IVAR_$_HAPBluetoothMetrics._txPowerLevel
+ OBJC_IVAR_$_HAPBootReasonsMetrics._brownOutResetBootCount
+ OBJC_IVAR_$_HAPBootReasonsMetrics._connectivityMonitorBootCount
+ OBJC_IVAR_$_HAPBootReasonsMetrics._hardwareFaultBootCount
+ OBJC_IVAR_$_HAPBootReasonsMetrics._hardwareWatchdogResetBootCount
+ OBJC_IVAR_$_HAPBootReasonsMetrics._heapOverflowBootCount
+ OBJC_IVAR_$_HAPBootReasonsMetrics._powerOnBootCount
+ OBJC_IVAR_$_HAPBootReasonsMetrics._softwareExceptionBootCount
+ OBJC_IVAR_$_HAPBootReasonsMetrics._softwareResetBootCount
+ OBJC_IVAR_$_HAPBootReasonsMetrics._softwareUpdateCompletedBootCount
+ OBJC_IVAR_$_HAPBootReasonsMetrics._softwareWatchdogResetBootCount
+ OBJC_IVAR_$_HAPBootReasonsMetrics._stackOverflowBootCount
+ OBJC_IVAR_$_HAPBootReasonsMetrics._temperatureLimitBootCount
+ OBJC_IVAR_$_HAPBootReasonsMetrics._unspecifiedBootCount
+ OBJC_IVAR_$_HAPCHMMetrics._chmAccessoryRebootCompleted
+ OBJC_IVAR_$_HAPCHMMetrics._chmAccessoryRebootDurationToRecovery
+ OBJC_IVAR_$_HAPCHMMetrics._hapSessionLossCount
+ OBJC_IVAR_$_HAPCHMMetrics._threadFirstRestartCompleted
+ OBJC_IVAR_$_HAPCHMMetrics._threadFirstRestartConnectivityState
+ OBJC_IVAR_$_HAPCHMMetrics._threadFirstRestartRecoveryTime
+ OBJC_IVAR_$_HAPCHMMetrics._threadRecoveryAttemptCount
+ OBJC_IVAR_$_HAPCHMMetrics._threadRestartCount
+ OBJC_IVAR_$_HAPCHMMetrics._threadTransportLossCount
+ OBJC_IVAR_$_HAPCHMMetrics._wifiFirstRestartCompleted
+ OBJC_IVAR_$_HAPCHMMetrics._wifiFirstRestartConnectivityState
+ OBJC_IVAR_$_HAPCHMMetrics._wifiFirstRestartRecoveryTime
+ OBJC_IVAR_$_HAPCHMMetrics._wifiRecoveryAttemptCount
+ OBJC_IVAR_$_HAPCHMMetrics._wifiRestartCount
+ OBJC_IVAR_$_HAPCHMMetrics._wifiTransportLossCount
+ OBJC_IVAR_$_HAPCharacteristicResponseTuple._coapMessageID
+ OBJC_IVAR_$_HAPConnectionHealthMonitor._deviceRebootDelay
+ OBJC_IVAR_$_HAPConnectionHealthMonitor._deviceRebootEnable
+ OBJC_IVAR_$_HAPConnectionHealthMonitor._recoveryStaggerDelay
+ OBJC_IVAR_$_HAPConnectionHealthMonitor._threadPingTestCount
+ OBJC_IVAR_$_HAPConnectionHealthMonitor._threadPingTestInterval
+ OBJC_IVAR_$_HAPConnectionHealthMonitor._threadRecoveryConfiguration
+ OBJC_IVAR_$_HAPConnectionHealthMonitor._threadRestartMinInterval
+ OBJC_IVAR_$_HAPConnectionHealthMonitor._wiFiPingTestCount
+ OBJC_IVAR_$_HAPConnectionHealthMonitor._wiFiPingTestInterval
+ OBJC_IVAR_$_HAPConnectionHealthMonitor._wiFiRecoveryConfiguration
+ OBJC_IVAR_$_HAPConnectionHealthMonitor._wiFiRestartMinInterval
+ OBJC_IVAR_$_HAPErrorCountersMetrics._entries
+ OBJC_IVAR_$_HAPErrorCountersMetricsEntry._count
+ OBJC_IVAR_$_HAPErrorCountersMetricsEntry._errorID
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._abandonedRequestCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._audioOnlyFailureCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._authenticationErrorCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._fragmentFailureCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._fragmentRetriedCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._fragmentSuccessCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._latencyCount1000ms
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._latencyCount2000ms
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._latencyCount250ms
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._latencyCount3750ms
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._latencyCount500ms
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._latencyCountOver3750ms
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._localErrorCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._networkErrorCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._partialSuccessCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._playlistFailureCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._serverReturnedErrorCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._sessionFailureCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._sessionSuccessCount
+ OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._uploadWithoutResidentResponseCount
+ OBJC_IVAR_$_HAPMetricEventBluetoothVersionTypeWrapper._value
+ OBJC_IVAR_$_HAPMetricEventPowerSourcesBitmaskWrapper._value
+ OBJC_IVAR_$_HAPMetricEventPowerSourcesEnumWrapper._value
+ OBJC_IVAR_$_HAPMetricEventThreadFirstRestartConnectivityStateWrapper._value
+ OBJC_IVAR_$_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper._value
+ OBJC_IVAR_$_HAPMetricEventWiFiVersionTypeWrapper._value
+ OBJC_IVAR_$_HAPPowerMetrics._batteryPercentage
+ OBJC_IVAR_$_HAPPowerMetrics._currentPowerSource
+ OBJC_IVAR_$_HAPPowerMetrics._durationOnBatteryPower
+ OBJC_IVAR_$_HAPPowerMetrics._durationRemainingOnBatteryPower
+ OBJC_IVAR_$_HAPPowerMetrics._supportedPowerSources
+ OBJC_IVAR_$_HAPSaturationMetrics._averageCPUUtilization
+ OBJC_IVAR_$_HAPSaturationMetrics._averageSystemMemoryUtilization
+ OBJC_IVAR_$_HAPSaturationMetrics._heapHighwaterCount
+ OBJC_IVAR_$_HAPSaturationMetrics._heapOverflowCount
+ OBJC_IVAR_$_HAPSaturationMetrics._lastHeapHighwaterTaskName
+ OBJC_IVAR_$_HAPSaturationMetrics._lastHeapOverflowTaskName
+ OBJC_IVAR_$_HAPSaturationMetrics._lastProcessCriticalMemoryName
+ OBJC_IVAR_$_HAPSaturationMetrics._lastStackHighwaterTaskName
+ OBJC_IVAR_$_HAPSaturationMetrics._lastStackOverflowTaskName
+ OBJC_IVAR_$_HAPSaturationMetrics._loadAverage
+ OBJC_IVAR_$_HAPSaturationMetrics._maxTaskReadyQueueSize
+ OBJC_IVAR_$_HAPSaturationMetrics._nonVolatileMemoryReadCount
+ OBJC_IVAR_$_HAPSaturationMetrics._nonVolatileMemoryReadErrorCount
+ OBJC_IVAR_$_HAPSaturationMetrics._nonVolatileMemoryUtilization
+ OBJC_IVAR_$_HAPSaturationMetrics._nonVolatileMemoryWriteCount
+ OBJC_IVAR_$_HAPSaturationMetrics._nonVolatileMemoryWriteErrorCount
+ OBJC_IVAR_$_HAPSaturationMetrics._peakCPUUtilization
+ OBJC_IVAR_$_HAPSaturationMetrics._peakSystemMemoryUtilization
+ OBJC_IVAR_$_HAPSaturationMetrics._processCriticalMemoryCount
+ OBJC_IVAR_$_HAPSaturationMetrics._stackHighwaterCount
+ OBJC_IVAR_$_HAPSaturationMetrics._stackOverflowCount
+ OBJC_IVAR_$_HAPSaturationMetrics._systemMemoryPressureCount
+ OBJC_IVAR_$_HAPSaturationMetrics._taskDeadlineMissCount
+ OBJC_IVAR_$_HAPSaturationMetrics._totalTasksScheduledCount
+ OBJC_IVAR_$_HAPSecuritySession._foreignPairVerifySession
+ OBJC_IVAR_$_HAPSessionKeepAliveTransportTypeWrapper._value
+ OBJC_IVAR_$_HAPStabilityMetrics._activeHardwareFaults
+ OBJC_IVAR_$_HAPStabilityMetrics._expectedBootCount
+ OBJC_IVAR_$_HAPStabilityMetrics._lastBootReason
+ OBJC_IVAR_$_HAPStabilityMetrics._systemBootCount
+ OBJC_IVAR_$_HAPStabilityMetrics._systemCrashCount
+ OBJC_IVAR_$_HAPStabilityMetrics._systemHangCount
+ OBJC_IVAR_$_HAPStabilityMetrics._systemUptime
+ OBJC_IVAR_$_HAPStabilityMetricsBootReasonTypeWrapper._value
+ OBJC_IVAR_$_HAPStabilityMetricsHardwareFaultTypeWrapper._value
+ OBJC_IVAR_$_HAPTLVPreferredWiFiEntry._PSK
+ OBJC_IVAR_$_HAPTLVPreferredWiFiEntry._SSID
+ OBJC_IVAR_$_HAPTLVPreferredWiFiEntry._securityMode
+ OBJC_IVAR_$_HAPTLVPreferredWiFiList._preferredWiFiList
+ OBJC_IVAR_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry._maximumInterval
+ OBJC_IVAR_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry._minimumInterval
+ OBJC_IVAR_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry._transportType
+ OBJC_IVAR_$_HAPTLVSelectedSessionKeepAliveConfigurationList._entries
+ OBJC_IVAR_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry._maximumInterval
+ OBJC_IVAR_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry._minimumInterval
+ OBJC_IVAR_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry._minimumRange
+ OBJC_IVAR_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry._transportType
+ OBJC_IVAR_$_HAPTLVSupportedSessionKeepAliveConfigurationList._entries
+ OBJC_IVAR_$_HAPThermalMetrics._averageDeviceTemperature
+ OBJC_IVAR_$_HAPThermalMetrics._maximumDeviceTemperature
+ OBJC_IVAR_$_HAPThermalMetrics._minimumDeviceTemperature
+ OBJC_IVAR_$_HAPThermalMetrics._temperatureLimitViolationCount
+ OBJC_IVAR_$_HAPThermalMetrics._temperatureLimitViolationDuration
+ OBJC_IVAR_$_HAPWiFiMetrics._beaconLostCount
+ OBJC_IVAR_$_HAPWiFiMetrics._beaconRxCount
+ OBJC_IVAR_$_HAPWiFiMetrics._beaconRxInterval
+ OBJC_IVAR_$_HAPWiFiMetrics._bssid
+ OBJC_IVAR_$_HAPWiFiMetrics._channelNumber
+ OBJC_IVAR_$_HAPWiFiMetrics._connectionStatus
+ OBJC_IVAR_$_HAPWiFiMetrics._disconnectionCount
+ OBJC_IVAR_$_HAPWiFiMetrics._disconnectionDuration
+ OBJC_IVAR_$_HAPWiFiMetrics._gatewayIPv4Address
+ OBJC_IVAR_$_HAPWiFiMetrics._gatewayIPv6Address
+ OBJC_IVAR_$_HAPWiFiMetrics._gatewayMacAddress
+ OBJC_IVAR_$_HAPWiFiMetrics._hwExceptionCount
+ OBJC_IVAR_$_HAPWiFiMetrics._ipAddressList
+ OBJC_IVAR_$_HAPWiFiMetrics._packetMulticastRxCount
+ OBJC_IVAR_$_HAPWiFiMetrics._packetMulticastRxErrorCount
+ OBJC_IVAR_$_HAPWiFiMetrics._packetMulticastTxCount
+ OBJC_IVAR_$_HAPWiFiMetrics._packetMulticastTxErrorCount
+ OBJC_IVAR_$_HAPWiFiMetrics._packetUnicastRxCount
+ OBJC_IVAR_$_HAPWiFiMetrics._packetUnicastRxErrorCount
+ OBJC_IVAR_$_HAPWiFiMetrics._packetUnicastTxCount
+ OBJC_IVAR_$_HAPWiFiMetrics._packetUnicastTxErrorCount
+ OBJC_IVAR_$_HAPWiFiMetrics._rssi
+ OBJC_IVAR_$_HAPWiFiMetrics._rxPacketCount
+ OBJC_IVAR_$_HAPWiFiMetrics._rxPacketErrorCount
+ OBJC_IVAR_$_HAPWiFiMetrics._subnetMask
+ OBJC_IVAR_$_HAPWiFiMetrics._txPacketCount
+ OBJC_IVAR_$_HAPWiFiMetrics._txPacketErrorCount
+ OBJC_IVAR_$_HAPWiFiMetrics._wifiRestartCount
+ OBJC_IVAR_$_HAPWiFiMetrics._wifiVersion
+ _DNSServiceRefDeallocate
+ _DNSServiceResolve
+ _DNSServiceSetDispatchQueue
+ _HAP2BonjourResolveReply
+ _HAP2CancelResolverAndReportFailure
+ _HAP2CoAPAddressEqualsAddress
+ _HAP2IPv4MappedIPv6BytesFromIPv4Bytes
+ _HAP2PipelineAddressIdentity
+ _HAP2SelectEffectiveList
+ _HAP2SessionKeepAliveSelectedMaxIntervalKey
+ _HAP2SessionKeepAliveSelectedMinIntervalKey
+ _HAP2TakeNextUntriedIP
+ _HAPMetricEventBluetoothVersionTypeAsString
+ _HAPMetricEventPowerSourcesBitmaskAsString
+ _HAPMetricEventPowerSourcesEnumAsString
+ _HAPMetricEventThreadFirstRestartConnectivityStateAsString
+ _HAPMetricEventWiFiFirstRestartConnectivityStateAsString
+ _HAPMetricEventWiFiVersionTypeAsString
+ _HAPSessionKeepAliveTransportTypeAsString
+ _HAPStabilityMetricsBootReasonTypeAsString
+ _HAPStabilityMetricsHardwareFaultTypeAsString
+ _NSCocoaErrorDomain
+ _OBJC_$_PROP_LIST_HAP2AccessoryDNSResolver
+ _OBJC_CLASS_$_HAP2AccessoryAddressResolverPipeline
+ _OBJC_CLASS_$_HAP2AccessoryDNSResolver
+ _OBJC_CLASS_$_HAP2AccessoryServerIPCacheData
+ _OBJC_CLASS_$_HAP2BrowserResolverRegistry
+ _OBJC_CLASS_$_HAP2CoAPRequestRacingLogEvent
+ _OBJC_CLASS_$_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ _OBJC_CLASS_$_HAP2SessionKeepAliveConfiguration
+ _OBJC_CLASS_$_HAP2SessionKeepAliveConfigurationEntry
+ _OBJC_CLASS_$_HAP2SessionKeepAliveListener
+ _OBJC_CLASS_$_HAP2SessionKeepAliveTransportState
+ _OBJC_CLASS_$_HAPAccessoryCHMMetricsLogEvent
+ _OBJC_CLASS_$_HAPAccessoryCHMRecoveryLogEvent
+ _OBJC_CLASS_$_HAPBluetoothMetrics
+ _OBJC_CLASS_$_HAPBootReasonsMetrics
+ _OBJC_CLASS_$_HAPCHMMetrics
+ _OBJC_CLASS_$_HAPConnectionHealthMonitor
+ _OBJC_CLASS_$_HAPErrorCountersMetrics
+ _OBJC_CLASS_$_HAPErrorCountersMetricsEntry
+ _OBJC_CLASS_$_HAPHKSV3UploadLatencyMetrics
+ _OBJC_CLASS_$_HAPMetricEventBluetoothVersionTypeWrapper
+ _OBJC_CLASS_$_HAPMetricEventPowerSourcesBitmaskWrapper
+ _OBJC_CLASS_$_HAPMetricEventPowerSourcesEnumWrapper
+ _OBJC_CLASS_$_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ _OBJC_CLASS_$_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ _OBJC_CLASS_$_HAPMetricEventWiFiVersionTypeWrapper
+ _OBJC_CLASS_$_HAPPowerMetrics
+ _OBJC_CLASS_$_HAPSaturationMetrics
+ _OBJC_CLASS_$_HAPSessionKeepAliveTransportTypeWrapper
+ _OBJC_CLASS_$_HAPStabilityMetrics
+ _OBJC_CLASS_$_HAPStabilityMetricsBootReasonTypeWrapper
+ _OBJC_CLASS_$_HAPStabilityMetricsHardwareFaultTypeWrapper
+ _OBJC_CLASS_$_HAPTLVPreferredWiFiEntry
+ _OBJC_CLASS_$_HAPTLVPreferredWiFiList
+ _OBJC_CLASS_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ _OBJC_CLASS_$_HAPTLVSelectedSessionKeepAliveConfigurationList
+ _OBJC_CLASS_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ _OBJC_CLASS_$_HAPTLVSupportedSessionKeepAliveConfigurationList
+ _OBJC_CLASS_$_HAPThermalMetrics
+ _OBJC_CLASS_$_HAPWiFiMetrics
+ _OBJC_CLASS_$_HMFTimerFactory
+ _OBJC_CLASS_$_NSCountedSet
+ _OBJC_METACLASS_$_HAP2AccessoryAddressResolverPipeline
+ _OBJC_METACLASS_$_HAP2AccessoryDNSResolver
+ _OBJC_METACLASS_$_HAP2AccessoryServerIPCacheData
+ _OBJC_METACLASS_$_HAP2BrowserResolverRegistry
+ _OBJC_METACLASS_$_HAP2CoAPRequestRacingLogEvent
+ _OBJC_METACLASS_$_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ _OBJC_METACLASS_$_HAP2SessionKeepAliveConfiguration
+ _OBJC_METACLASS_$_HAP2SessionKeepAliveConfigurationEntry
+ _OBJC_METACLASS_$_HAP2SessionKeepAliveListener
+ _OBJC_METACLASS_$_HAP2SessionKeepAliveTransportState
+ _OBJC_METACLASS_$_HAPAccessoryCHMMetricsLogEvent
+ _OBJC_METACLASS_$_HAPAccessoryCHMRecoveryLogEvent
+ _OBJC_METACLASS_$_HAPBluetoothMetrics
+ _OBJC_METACLASS_$_HAPBootReasonsMetrics
+ _OBJC_METACLASS_$_HAPCHMMetrics
+ _OBJC_METACLASS_$_HAPConnectionHealthMonitor
+ _OBJC_METACLASS_$_HAPErrorCountersMetrics
+ _OBJC_METACLASS_$_HAPErrorCountersMetricsEntry
+ _OBJC_METACLASS_$_HAPHKSV3UploadLatencyMetrics
+ _OBJC_METACLASS_$_HAPMetricEventBluetoothVersionTypeWrapper
+ _OBJC_METACLASS_$_HAPMetricEventPowerSourcesBitmaskWrapper
+ _OBJC_METACLASS_$_HAPMetricEventPowerSourcesEnumWrapper
+ _OBJC_METACLASS_$_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ _OBJC_METACLASS_$_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ _OBJC_METACLASS_$_HAPMetricEventWiFiVersionTypeWrapper
+ _OBJC_METACLASS_$_HAPPowerMetrics
+ _OBJC_METACLASS_$_HAPSaturationMetrics
+ _OBJC_METACLASS_$_HAPSessionKeepAliveTransportTypeWrapper
+ _OBJC_METACLASS_$_HAPStabilityMetrics
+ _OBJC_METACLASS_$_HAPStabilityMetricsBootReasonTypeWrapper
+ _OBJC_METACLASS_$_HAPStabilityMetricsHardwareFaultTypeWrapper
+ _OBJC_METACLASS_$_HAPTLVPreferredWiFiEntry
+ _OBJC_METACLASS_$_HAPTLVPreferredWiFiList
+ _OBJC_METACLASS_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ _OBJC_METACLASS_$_HAPTLVSelectedSessionKeepAliveConfigurationList
+ _OBJC_METACLASS_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ _OBJC_METACLASS_$_HAPTLVSupportedSessionKeepAliveConfigurationList
+ _OBJC_METACLASS_$_HAPThermalMetrics
+ _OBJC_METACLASS_$_HAPWiFiMetrics
+ _PROTOCOLS_HAPAccessoryCHMMetricsLogEvent
+ _PROTOCOLS_HAPAccessoryCHMRecoveryLogEvent
+ __107-[HAP2AccessoryServerTransportCoAP _sendRacingRequest:path:method:messageID:primaryClient:secondaryClient:]_block_invoke
+ __139-[HAP2AccessoryServerTransportCoAP _executeRacingWithRequest:path:method:messageID:primaryClient:secondaryClient:failoverTimeout:rttStats:]_block_invoke
+ __42-[HAP2CoAPClient sendProbeWithCompletion:]_block_invoke
+ __46-[HAP2AccessoryDNSResolver updateServiceName:]_block_invoke
+ __49-[HAP2AccessoryDNSResolver _startPipelineOnQueue]_block_invoke
+ __49-[HAP2CoAPClient getRTTStatisticsWithCompletion:]_block_invoke
+ __50-[HAP2AccessoryDNSResolver _handlePipelineUpdate:]_block_invoke
+ __53-[HAP2AccessoryServerTransportCoAP _sendHelloIfReady]_block_invoke
+ __53-[HAP2CoAPClient getLocalIPv4EndpointWithCompletion:]_block_invoke
+ __53-[HAP2CoAPClient getLocalIPv6EndpointWithCompletion:]_block_invoke
+ __55-[HAP2AccessoryServerTransportCoAP _refreshIPAddresses]_block_invoke
+ __58-[HAP2AccessoryServerTransportCoAP _startResolverIfNeeded]_block_invoke
+ __59-[HAP2AccessoryServer(Paired) resolver:didUpdateAddresses:]_block_invoke
+ __59-[HAP2AccessoryServerBrowser initWithCoordinators:storage:]_block_invoke
+ __61-[HAP2AccessoryServerTransportCoAP _sendEndpointRegistration]_block_invoke
+ __61-[HAP2AccessoryServerTransportCoAP _sendEndpointRegistration]_block_invoke_2
+ __62-[HAP2AccessoryServerTransportCoAP clientDidDisconnect:error:]_block_invoke
+ __65-[HAP2AccessoryServerController sendProbeOnTransport:completion:]_block_invoke
+ __65-[HAP2AccessoryServerTransportCoAP _sendWiFiEndpointRegistration]_block_invoke
+ __68-[HAP2AccessoryServerTransportCoAP _resolverDidUpdateWithAddresses:]_block_invoke
+ __68-[HAP2AccessoryServerTransportCoAP _sendMultiTransportRequest:path:]_block_invoke
+ __69-[HAP2AccessoryAddressResolverPipeline _startGetaddrinfoForHostname:]_block_invoke
+ __70-[HAP2AccessoryServerController secureTransport:didChangeState:error:]_block_invoke
+ __72-[HAP2AccessoryServerTransportCoAP _closeMultiTransportClientWithError:]_block_invoke
+ __72-[HAP2AccessoryServerTransportCoAP _closeMultiTransportClientWithError:]_block_invoke_2
+ __73-[HAP2AccessoryServerTransportCoAP _sendProbeOnTransportType:completion:]_block_invoke
+ __74-[HAP2AccessoryServerTransportCoAP _openMultiTransportClientWithActivity:]_block_invoke
+ __75-[HAP2BrowserResolverRegistry _performAuditPassOnQueueWithActiveDeviceIDs:]_block_invoke
+ __78-[HAP2AccessoryServerTransportCoAP _openPrimaryClientIteratingWithCompletion:]_block_invoke
+ __78-[HAP2AccessoryServerTransportCoAP _sendRegistrationTLVWithAddressBytes:port:]_block_invoke
+ __80-[HAP2AccessoryServerCoordinator initializePairedAccessoryServerFromCachedInfo:]_block_invoke
+ __80-[HAP2AccessoryServerCoordinator initializePairedAccessoryServerFromCachedInfo:]_block_invoke_2
+ __88-[HAP2AccessoryServerTransportCoAP advanceEndpointAfterPairVerifyFailureWithCompletion:]_block_invoke
+ __89-[HAP2AccessoryServerTransportCoAP _openSecondaryClientIteratingIsThreadOnly:completion:]_block_invoke
+ __92-[HAPAccessoryServerHAP2Adapter deriveEncryptionForDataStreamWithKeySalt:completionHandler:]_block_invoke
+ __DATA_HAP2CoAPRequestRacingLogEvent
+ __DATA_HAPAccessoryCHMMetricsLogEvent
+ __DATA_HAPAccessoryCHMRecoveryLogEvent
+ __INSTANCE_METHODS_HAP2CoAPRequestRacingLogEvent
+ __INSTANCE_METHODS_HAPAccessoryCHMMetricsLogEvent
+ __INSTANCE_METHODS_HAPAccessoryCHMRecoveryLogEvent
+ __IVARS_HAP2CoAPRequestRacingLogEvent
+ __IVARS_HAPAccessoryCHMMetricsLogEvent
+ __IVARS_HAPAccessoryCHMRecoveryLogEvent
+ __METACLASS_DATA_HAP2CoAPRequestRacingLogEvent
+ __METACLASS_DATA_HAPAccessoryCHMMetricsLogEvent
+ __METACLASS_DATA_HAPAccessoryCHMRecoveryLogEvent
+ __OBJC_$_CLASS_METHODS_HAP2AccessoryDeviceIPAddress
+ __OBJC_$_CLASS_METHODS_HAP2AccessoryServerCoordinator(Test)
+ __OBJC_$_CLASS_METHODS_HAP2AccessoryServerDiscoveryHAPAccessoryInfo
+ __OBJC_$_CLASS_METHODS_HAP2AccessoryServerIPCacheData
+ __OBJC_$_CLASS_METHODS_HAP2SessionKeepAliveConfiguration
+ __OBJC_$_CLASS_METHODS_HAPBluetoothMetrics
+ __OBJC_$_CLASS_METHODS_HAPBootReasonsMetrics
+ __OBJC_$_CLASS_METHODS_HAPCHMMetrics
+ __OBJC_$_CLASS_METHODS_HAPConnectionHealthMonitor
+ __OBJC_$_CLASS_METHODS_HAPErrorCountersMetrics
+ __OBJC_$_CLASS_METHODS_HAPErrorCountersMetricsEntry
+ __OBJC_$_CLASS_METHODS_HAPHKSV3UploadLatencyMetrics
+ __OBJC_$_CLASS_METHODS_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_$_CLASS_METHODS_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_$_CLASS_METHODS_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_$_CLASS_METHODS_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_$_CLASS_METHODS_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_$_CLASS_METHODS_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_$_CLASS_METHODS_HAPPowerMetrics
+ __OBJC_$_CLASS_METHODS_HAPSaturationMetrics
+ __OBJC_$_CLASS_METHODS_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_$_CLASS_METHODS_HAPStabilityMetrics
+ __OBJC_$_CLASS_METHODS_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_$_CLASS_METHODS_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_$_CLASS_METHODS_HAPTLVPreferredWiFiEntry
+ __OBJC_$_CLASS_METHODS_HAPTLVPreferredWiFiList
+ __OBJC_$_CLASS_METHODS_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_$_CLASS_METHODS_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_$_CLASS_METHODS_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_$_CLASS_METHODS_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_$_CLASS_METHODS_HAPThermalMetrics
+ __OBJC_$_CLASS_METHODS_HAPWiFiMetrics
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryAddressResolverPipeline
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryDNSResolver
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServer(Test|Paired|PairedInternal|Unpaired)
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServerBrowser(Test)
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServerCoordinator(Test)
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServerIPCacheData
+ __OBJC_$_INSTANCE_METHODS_HAP2BrowserResolverRegistry(Test)
+ __OBJC_$_INSTANCE_METHODS_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ __OBJC_$_INSTANCE_METHODS_HAP2SessionKeepAliveConfigurationEntry
+ __OBJC_$_INSTANCE_METHODS_HAP2SessionKeepAliveListener
+ __OBJC_$_INSTANCE_METHODS_HAP2SessionKeepAliveTransportState
+ __OBJC_$_INSTANCE_METHODS_HAPBluetoothMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPBootReasonsMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPCHMMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPConnectionHealthMonitor
+ __OBJC_$_INSTANCE_METHODS_HAPErrorCountersMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPErrorCountersMetricsEntry
+ __OBJC_$_INSTANCE_METHODS_HAPHKSV3UploadLatencyMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPPowerMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPSaturationMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPStabilityMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPTLVPreferredWiFiEntry
+ __OBJC_$_INSTANCE_METHODS_HAPTLVPreferredWiFiList
+ __OBJC_$_INSTANCE_METHODS_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_$_INSTANCE_METHODS_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_$_INSTANCE_METHODS_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_$_INSTANCE_METHODS_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_$_INSTANCE_METHODS_HAPThermalMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPWiFiMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAP2AccessoryAddressResolverPipeline
+ __OBJC_$_INSTANCE_VARIABLES_HAP2AccessoryDNSResolver
+ __OBJC_$_INSTANCE_VARIABLES_HAP2AccessoryServerIPCacheData
+ __OBJC_$_INSTANCE_VARIABLES_HAP2BrowserResolverRegistry
+ __OBJC_$_INSTANCE_VARIABLES_HAP2SessionKeepAliveConfigurationEntry
+ __OBJC_$_INSTANCE_VARIABLES_HAP2SessionKeepAliveListener
+ __OBJC_$_INSTANCE_VARIABLES_HAP2SessionKeepAliveTransportState
+ __OBJC_$_INSTANCE_VARIABLES_HAPBluetoothMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPBootReasonsMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPCHMMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPConnectionHealthMonitor
+ __OBJC_$_INSTANCE_VARIABLES_HAPErrorCountersMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPErrorCountersMetricsEntry
+ __OBJC_$_INSTANCE_VARIABLES_HAPHKSV3UploadLatencyMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPPowerMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPSaturationMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPStabilityMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVPreferredWiFiEntry
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVPreferredWiFiList
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_$_INSTANCE_VARIABLES_HAPThermalMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPWiFiMetrics
+ __OBJC_$_PROP_LIST_HAP2AccessoryAddressResolverPipeline
+ __OBJC_$_PROP_LIST_HAP2AccessoryDNSResolver
+ __OBJC_$_PROP_LIST_HAP2AccessoryDNSResolverPrivate
+ __OBJC_$_PROP_LIST_HAP2AccessoryServerIPCacheData
+ __OBJC_$_PROP_LIST_HAP2BrowserResolverRegistry
+ __OBJC_$_PROP_LIST_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ __OBJC_$_PROP_LIST_HAP2PairedAccessoryServerPrivate
+ __OBJC_$_PROP_LIST_HAP2SessionKeepAliveConfigurationEntry
+ __OBJC_$_PROP_LIST_HAP2SessionKeepAliveListener
+ __OBJC_$_PROP_LIST_HAP2SessionKeepAliveTransportState
+ __OBJC_$_PROP_LIST_HAPBluetoothMetrics
+ __OBJC_$_PROP_LIST_HAPBootReasonsMetrics
+ __OBJC_$_PROP_LIST_HAPCHMMetrics
+ __OBJC_$_PROP_LIST_HAPConnectionHealthMonitor
+ __OBJC_$_PROP_LIST_HAPErrorCountersMetrics
+ __OBJC_$_PROP_LIST_HAPErrorCountersMetricsEntry
+ __OBJC_$_PROP_LIST_HAPHKSV3UploadLatencyMetrics
+ __OBJC_$_PROP_LIST_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_$_PROP_LIST_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_$_PROP_LIST_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_$_PROP_LIST_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_$_PROP_LIST_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_$_PROP_LIST_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_$_PROP_LIST_HAPPowerMetrics
+ __OBJC_$_PROP_LIST_HAPSaturationMetrics
+ __OBJC_$_PROP_LIST_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_$_PROP_LIST_HAPStabilityMetrics
+ __OBJC_$_PROP_LIST_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_$_PROP_LIST_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_$_PROP_LIST_HAPTLVPreferredWiFiEntry
+ __OBJC_$_PROP_LIST_HAPTLVPreferredWiFiList
+ __OBJC_$_PROP_LIST_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_$_PROP_LIST_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_$_PROP_LIST_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_$_PROP_LIST_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_$_PROP_LIST_HAPThermalMetrics
+ __OBJC_$_PROP_LIST_HAPWiFiMetrics
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HAP2AccessoryAddressResolverPipelineFactory
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HAP2AccessoryDNSResolver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HAP2AccessoryDNSResolverCacheSubscriber
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HAP2AccessoryDNSResolverDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HAP2AccessoryDNSResolverPrivate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HAP2AccessoryServerSecureTransportDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HAP2AccessoryServerTransportDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HAP2AccessoryAddressResolverPipelineFactory
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HAP2AccessoryDNSResolver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HAP2AccessoryDNSResolverCacheSubscriber
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HAP2AccessoryDNSResolverDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HAP2AccessoryDNSResolverPrivate
+ __OBJC_$_PROTOCOL_REFS_HAP2AccessoryAddressResolverPipelineFactory
+ __OBJC_$_PROTOCOL_REFS_HAP2AccessoryDNSResolver
+ __OBJC_$_PROTOCOL_REFS_HAP2AccessoryDNSResolverCacheSubscriber
+ __OBJC_$_PROTOCOL_REFS_HAP2AccessoryDNSResolverDelegate
+ __OBJC_$_PROTOCOL_REFS_HAP2AccessoryDNSResolverPrivate
+ __OBJC_CLASS_PROTOCOLS_$_HAP2AccessoryDNSResolver
+ __OBJC_CLASS_PROTOCOLS_$_HAP2AccessoryServer(Test|Paired|PairedInternal|Unpaired)
+ __OBJC_CLASS_PROTOCOLS_$_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ __OBJC_CLASS_PROTOCOLS_$_HAP2SessionKeepAliveListener
+ __OBJC_CLASS_PROTOCOLS_$_HAPBluetoothMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPBootReasonsMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPCHMMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPConnectionHealthMonitor
+ __OBJC_CLASS_PROTOCOLS_$_HAPErrorCountersMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPErrorCountersMetricsEntry
+ __OBJC_CLASS_PROTOCOLS_$_HAPHKSV3UploadLatencyMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPPowerMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPSaturationMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPStabilityMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVPreferredWiFiEntry
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVPreferredWiFiList
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_CLASS_PROTOCOLS_$_HAPThermalMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPWiFiMetrics
+ __OBJC_CLASS_RO_$_HAP2AccessoryAddressResolverPipeline
+ __OBJC_CLASS_RO_$_HAP2AccessoryDNSResolver
+ __OBJC_CLASS_RO_$_HAP2AccessoryServerIPCacheData
+ __OBJC_CLASS_RO_$_HAP2BrowserResolverRegistry
+ __OBJC_CLASS_RO_$_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ __OBJC_CLASS_RO_$_HAP2SessionKeepAliveConfiguration
+ __OBJC_CLASS_RO_$_HAP2SessionKeepAliveConfigurationEntry
+ __OBJC_CLASS_RO_$_HAP2SessionKeepAliveListener
+ __OBJC_CLASS_RO_$_HAP2SessionKeepAliveTransportState
+ __OBJC_CLASS_RO_$_HAPBluetoothMetrics
+ __OBJC_CLASS_RO_$_HAPBootReasonsMetrics
+ __OBJC_CLASS_RO_$_HAPCHMMetrics
+ __OBJC_CLASS_RO_$_HAPConnectionHealthMonitor
+ __OBJC_CLASS_RO_$_HAPErrorCountersMetrics
+ __OBJC_CLASS_RO_$_HAPErrorCountersMetricsEntry
+ __OBJC_CLASS_RO_$_HAPHKSV3UploadLatencyMetrics
+ __OBJC_CLASS_RO_$_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_CLASS_RO_$_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_CLASS_RO_$_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_CLASS_RO_$_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_CLASS_RO_$_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_CLASS_RO_$_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_CLASS_RO_$_HAPPowerMetrics
+ __OBJC_CLASS_RO_$_HAPSaturationMetrics
+ __OBJC_CLASS_RO_$_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_CLASS_RO_$_HAPStabilityMetrics
+ __OBJC_CLASS_RO_$_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_CLASS_RO_$_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_CLASS_RO_$_HAPTLVPreferredWiFiEntry
+ __OBJC_CLASS_RO_$_HAPTLVPreferredWiFiList
+ __OBJC_CLASS_RO_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_CLASS_RO_$_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_CLASS_RO_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_CLASS_RO_$_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_CLASS_RO_$_HAPThermalMetrics
+ __OBJC_CLASS_RO_$_HAPWiFiMetrics
+ __OBJC_LABEL_PROTOCOL_$_HAP2AccessoryAddressResolverPipelineFactory
+ __OBJC_LABEL_PROTOCOL_$_HAP2AccessoryDNSResolver
+ __OBJC_LABEL_PROTOCOL_$_HAP2AccessoryDNSResolverCacheSubscriber
+ __OBJC_LABEL_PROTOCOL_$_HAP2AccessoryDNSResolverDelegate
+ __OBJC_LABEL_PROTOCOL_$_HAP2AccessoryDNSResolverPrivate
+ __OBJC_METACLASS_RO_$_HAP2AccessoryAddressResolverPipeline
+ __OBJC_METACLASS_RO_$_HAP2AccessoryDNSResolver
+ __OBJC_METACLASS_RO_$_HAP2AccessoryServerIPCacheData
+ __OBJC_METACLASS_RO_$_HAP2BrowserResolverRegistry
+ __OBJC_METACLASS_RO_$_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ __OBJC_METACLASS_RO_$_HAP2SessionKeepAliveConfiguration
+ __OBJC_METACLASS_RO_$_HAP2SessionKeepAliveConfigurationEntry
+ __OBJC_METACLASS_RO_$_HAP2SessionKeepAliveListener
+ __OBJC_METACLASS_RO_$_HAP2SessionKeepAliveTransportState
+ __OBJC_METACLASS_RO_$_HAPBluetoothMetrics
+ __OBJC_METACLASS_RO_$_HAPBootReasonsMetrics
+ __OBJC_METACLASS_RO_$_HAPCHMMetrics
+ __OBJC_METACLASS_RO_$_HAPConnectionHealthMonitor
+ __OBJC_METACLASS_RO_$_HAPErrorCountersMetrics
+ __OBJC_METACLASS_RO_$_HAPErrorCountersMetricsEntry
+ __OBJC_METACLASS_RO_$_HAPHKSV3UploadLatencyMetrics
+ __OBJC_METACLASS_RO_$_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_METACLASS_RO_$_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_METACLASS_RO_$_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_METACLASS_RO_$_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_METACLASS_RO_$_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_METACLASS_RO_$_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_METACLASS_RO_$_HAPPowerMetrics
+ __OBJC_METACLASS_RO_$_HAPSaturationMetrics
+ __OBJC_METACLASS_RO_$_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_METACLASS_RO_$_HAPStabilityMetrics
+ __OBJC_METACLASS_RO_$_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_METACLASS_RO_$_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_METACLASS_RO_$_HAPTLVPreferredWiFiEntry
+ __OBJC_METACLASS_RO_$_HAPTLVPreferredWiFiList
+ __OBJC_METACLASS_RO_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_METACLASS_RO_$_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_METACLASS_RO_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_METACLASS_RO_$_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_METACLASS_RO_$_HAPThermalMetrics
+ __OBJC_METACLASS_RO_$_HAPWiFiMetrics
+ __OBJC_PROTOCOL_$_HAP2AccessoryAddressResolverPipelineFactory
+ __OBJC_PROTOCOL_$_HAP2AccessoryDNSResolver
+ __OBJC_PROTOCOL_$_HAP2AccessoryDNSResolverCacheSubscriber
+ __OBJC_PROTOCOL_$_HAP2AccessoryDNSResolverDelegate
+ __OBJC_PROTOCOL_$_HAP2AccessoryDNSResolverPrivate
+ __OBJC_PROTOCOL_REFERENCE_$_HAP2AccessoryDNSResolverPrivate
+ __PROPERTIES_HAP2CoAPRequestRacingLogEvent
+ __PROPERTIES_HAPAccessoryCHMMetricsLogEvent
+ __PROPERTIES_HAPAccessoryCHMRecoveryLogEvent
+ __PROTOCOLS_HAPAccessoryCHMMetricsLogEvent
+ __PROTOCOLS_HAPAccessoryCHMRecoveryLogEvent
+ __ZL11_cacheValid
+ __ZL22_cachedMeshLocalPrefix
+ __ZL22_sharedClientOnceToken
+ __ZL24_lastInstalledNCPHandler
+ __ZL30_lastInstalledPreferredHandler
+ __ZNK6CtrXPC5Event7getNameEv
+ __ZnwmSt19__type_descriptor_t
+ ___101-[HAP2AccessoryServerSecureTransportBase transport:pairVerifyDidFailOnIPAddress:transportType:error:]_block_invoke
+ ___107-[HAP2AccessoryServerTransportCoAP _sendRacingRequest:path:method:messageID:primaryClient:secondaryClient:]_block_invoke
+ ___139-[HAP2AccessoryServerTransportCoAP _executeRacingWithRequest:path:method:messageID:primaryClient:secondaryClient:failoverTimeout:rttStats:]_block_invoke
+ ___143-[HAP2DefaultAccessoryAddressResolverPipelineFactory createResolverWithServiceName:serviceType:serviceDomain:queue:updateHandler:errorHandler:]_block_invoke
+ ___145-[HAP2AccessoryServer(PairedInternal) keepAliveListener:didMissHeartbeatOnTransport:expectedInterval:timeSinceLastHeartbeat:allTransportsMissed:]_block_invoke
+ ___145-[HAP2AccessoryServer(PairedInternal) keepAliveListener:didMissHeartbeatOnTransport:expectedInterval:timeSinceLastHeartbeat:allTransportsMissed:]_block_invoke_2
+ ___36-[HAP2SessionKeepAliveListener stop]_block_invoke
+ ___37-[HAP2AccessoryServerBrowser ipCache]_block_invoke
+ ___37-[HAP2SessionKeepAliveListener start]_block_invoke
+ ___39-[HAP2AccessoryDNSResolver serviceName]_block_invoke
+ ___40-[HAP2AccessoryDNSResolver stopPipeline]_block_invoke
+ ___41-[HAP2AccessoryDNSResolver becameEmptyAt]_block_invoke
+ ___41-[HAP2AccessoryDNSResolver startPipeline]_block_invoke
+ ___41-[HAP2AccessoryServerBrowser currentPTRs]_block_invoke
+ ___41-[HAP2AccessoryServerBrowser setIPCache:]_block_invoke
+ ___42-[HAP2CoAPClient sendProbeWithCompletion:]_block_invoke
+ ___42-[HAP2CoAPClient sendProbeWithCompletion:]_block_invoke_2
+ ___43-[HAP2AccessoryDNSResolver attachDelegate:]_block_invoke
+ ___43-[HAP2AccessoryDNSResolver detachDelegate:]_block_invoke
+ ___43-[HAP2AccessoryServer hasWiFiAdvertisement]_block_invoke
+ ___44+[HAP2ThreadNetworkUtil _sharedThreadClient]_block_invoke
+ ___44-[HAP2AccessoryDNSResolver currentAddresses]_block_invoke
+ ___45+[HAP2AccessoryServerIPCacheData logCategory]_block_invoke
+ ___45-[HAP2AccessoryServer hasThreadAdvertisement]_block_invoke
+ ___46-[HAP2AccessoryAddressResolverPipeline cancel]_block_invoke
+ ___46-[HAP2AccessoryDNSResolver updateServiceName:]_block_invoke
+ ___47-[HAP2AccessoryServer setHasWiFiAdvertisement:]_block_invoke
+ ___48+[HAP2ThreadNetworkUtil setupEventSubscriptions]_block_invoke
+ ___48-[HAP2AccessoryServer _setHasWiFiAdvertisement:]_block_invoke
+ ___49-[HAP2AccessoryDNSResolver _startPipelineOnQueue]_block_invoke
+ ___49-[HAP2AccessoryDNSResolver _startPipelineOnQueue]_block_invoke_2
+ ___49-[HAP2AccessoryServer setHasThreadAdvertisement:]_block_invoke
+ ___49-[HAP2CoAPClient getLocalEndpointWithCompletion:]_block_invoke
+ ___49-[HAP2CoAPClient getLocalEndpointWithCompletion:]_block_invoke_2
+ ___49-[HAP2CoAPClient getLocalEndpointWithCompletion:]_block_invoke_3
+ ___49-[HAP2CoAPClient getLocalEndpointWithCompletion:]_block_invoke_4
+ ___49-[HAP2CoAPClient getLocalEndpointWithCompletion:]_block_invoke_5
+ ___49-[HAP2CoAPClient getRTTStatisticsWithCompletion:]_block_invoke
+ ___49-[HAP2CoAPClient getRTTStatisticsWithCompletion:]_block_invoke_2
+ ___50-[HAP2AccessoryDNSResolver _handlePipelineUpdate:]_block_invoke
+ ___50-[HAP2AccessoryDNSResolver attachCacheSubscriber:]_block_invoke
+ ___50-[HAP2AccessoryDNSResolver detachCacheSubscriber:]_block_invoke
+ ___50-[HAP2AccessoryServer _setHasThreadAdvertisement:]_block_invoke
+ ___50-[HAP2BrowserResolverRegistry(Test) _allDeviceIDs]_block_invoke
+ ___51-[HAP2AccessoryDNSResolver _test_setBecameEmptyAt:]_block_invoke
+ ___51-[HAP2BrowserResolverRegistry resolverForDeviceID:]_block_invoke
+ ___52-[HAP2AccessoryDNSResolver deferAgingClockIfRunning]_block_invoke
+ ___52-[HAP2AccessoryServerBrowser _fireRevalidationSweep]_block_invoke
+ ___52-[HAP2SessionKeepAliveListener isTrackingTransport:]_block_invoke
+ ___53-[HAP2AccessoryServerTransportCoAP _sendHelloIfReady]_block_invoke
+ ___53-[HAP2AccessoryServerTransportCoAP _sendHelloIfReady]_block_invoke_2
+ ___53-[HAP2CoAPClient getLocalIPv4EndpointWithCompletion:]_block_invoke
+ ___53-[HAP2CoAPClient getLocalIPv4EndpointWithCompletion:]_block_invoke_2
+ ___53-[HAP2CoAPClient getLocalIPv6EndpointWithCompletion:]_block_invoke
+ ___53-[HAP2CoAPClient getLocalIPv6EndpointWithCompletion:]_block_invoke_2
+ ___53-[HAP2SessionKeepAliveListener trackedTransportTypes]_block_invoke
+ ___54-[HAP2AccessoryServerBrowser _buildActiveDeviceIDsSet]_block_invoke
+ ___55-[HAP2AccessoryServerBrowser _armPTRRevalidationWindow]_block_invoke
+ ___55-[HAP2AccessoryServerBrowser _armPTRRevalidationWindow]_block_invoke_2
+ ___55-[HAP2AccessoryServerBrowser hasCurrentPTRForDeviceID:]_block_invoke
+ ___55-[HAP2AccessoryServerTransportCoAP _refreshIPAddresses]_block_invoke
+ ___56-[HAP2SessionKeepAliveListener resetHeartbeatTimestamps]_block_invoke
+ ___57-[HAP2AccessoryServerTransportCoAP clientDidReceivePing:]_block_invoke
+ ___57-[HAP2BrowserResolverRegistry removeResolverForDeviceID:]_block_invoke
+ ___58-[HAP2AccessoryServer(Paired) configureKeepAliveListener:]_block_invoke
+ ___58-[HAP2AccessoryServerBrowser _cancelPTRRevalidationWindow]_block_invoke
+ ___58-[HAP2AccessoryServerCoordinator(Test) _test_deliverLoss:]_block_invoke
+ ___58-[HAP2AccessoryServerTransportCoAP _startResolverIfNeeded]_block_invoke
+ ___59-[HAP2AccessoryServer(Paired) resolver:didUpdateAddresses:]_block_invoke
+ ___59-[HAP2AccessoryServer(Paired) resolver:didUpdateAddresses:]_block_invoke_2
+ ___59-[HAP2AccessoryServerTransportCoAP _executeCacheMissCancel]_block_invoke
+ ___61-[HAP2AccessoryServerTransportCoAP _sendEndpointRegistration]_block_invoke
+ ___61-[HAP2AccessoryServerTransportCoAP _sendEndpointRegistration]_block_invoke_2
+ ___61-[HAP2AccessoryServerTransportCoAP _startResolveTimeoutTimer]_block_invoke
+ ___61-[HAP2AccessoryServerTransportCoAP _startResolveTimeoutTimer]_block_invoke_2
+ ___61-[HAP2CoAPClient _ioThreadDidReceivePingInSession:messageID:]_block_invoke
+ ___61-[HAP2CoAPClient _ioThreadDidReceivePongInSession:messageID:]_block_invoke
+ ___62-[HAP2AccessoryServer(Paired) didReceiveHeartbeatOnTransport:]_block_invoke
+ ___62-[HAP2AccessoryServerBrowser noteBrowsedPTRRemoveForDeviceID:]_block_invoke
+ ___62-[HAP2AccessoryServerTransportCoAP _resolverDidFailWithError:]_block_invoke
+ ___62-[HAP2AccessoryServerTransportCoAP clientDidDisconnect:error:]_block_invoke
+ ___63-[HAP2AccessoryServerController readLocalEndpointsWithHandler:]_block_invoke
+ ___63-[HAP2AccessoryServerCoordinator(Test) _test_deliverDiscovery:]_block_invoke
+ ___63-[HAP2AccessoryServerCoordinator(Test) _test_deliverDiscovery:]_block_invoke_2
+ ___63-[HAP2SessionKeepAliveListener didReceiveHeartbeatOnTransport:]_block_invoke
+ ___63-[HAP2SessionKeepAliveListener hasMissedHeartbeatForTransport:]_block_invoke
+ ___64-[HAP2AccessoryServer(Test) _test_setConnectionStateUnreachable]_block_invoke
+ ___65-[HAP2AccessoryServerController sendProbeOnTransport:completion:]_block_invoke
+ ___65-[HAP2AccessoryServerTransportCoAP _sendWiFiEndpointRegistration]_block_invoke
+ ___65-[HAP2AccessoryServerTransportCoAP _sendWiFiEndpointRegistration]_block_invoke_2
+ ___66-[HAP2AccessoryServerTransportCoAP readLocalEndpointsWithHandler:]_block_invoke
+ ___66-[HAP2AccessoryServerTransportCoAP readLocalEndpointsWithHandler:]_block_invoke_2
+ ___66-[HAP2AccessoryServerTransportCoAP readLocalEndpointsWithHandler:]_block_invoke_3
+ ___67-[HAP2BrowserResolverRegistry performAuditPassWithActiveDeviceIDs:]_block_invoke
+ ___67-[HAP2SessionKeepAliveListener timeSinceLastHeartbeatForTransport:]_block_invoke
+ ___68-[HAP2AccessoryServerBrowser _restoreCachedAccessoryServersIfNeeded]_block_invoke
+ ___68-[HAP2AccessoryServerTransportCoAP _resolverDidUpdateWithAddresses:]_block_invoke
+ ___68-[HAP2AccessoryServerTransportCoAP _sendMultiTransportRequest:path:]_block_invoke
+ ___69-[HAP2AccessoryAddressResolverPipeline _startGetaddrinfoForHostname:]_block_invoke
+ ___69-[HAP2AccessoryServerTransportCoAP signalPairVerifySuccessToDelegate]_block_invoke
+ ___69-[HAPAccessoryServerHAP2Adapter dataStreamPeerAddressWithCompletion:]_block_invoke
+ ___70-[HAP2AccessoryServerTransportCoAP applyResolverAddresses:completion:]_block_invoke
+ ___70-[HAP2BrowserResolverRegistry createResolverWithDeviceID:serviceName:]_block_invoke
+ ___71-[HAP2AccessoryServerBrowser noteBrowsedPTRAddForDeviceID:serviceName:]_block_invoke
+ ___72-[HAP2AccessoryServerSecureTransportBase readLocalEndpointsWithHandler:]_block_invoke
+ ___72-[HAP2AccessoryServerTransportCoAP _closeMultiTransportClientWithError:]_block_invoke
+ ___72-[HAP2AccessoryServerTransportCoAP _closeMultiTransportClientWithError:]_block_invoke_2
+ ___72-[HAP2AccessoryServerTransportCoAP _scheduleResolverRestartAfterFailure]_block_invoke
+ ___72-[HAP2AccessoryServerTransportCoAP _scheduleResolverRestartAfterFailure]_block_invoke_2
+ ___72-[HAP2AccessoryServerTransportCoAP dataStreamPeerAddressWithCompletion:]_block_invoke
+ ___73-[HAP2AccessoryServerTransportCoAP _sendProbeOnTransportType:completion:]_block_invoke
+ ___74-[HAP2AccessoryServerBrowser cachedIPDidUpdate:transportType:forDeviceID:]_block_invoke
+ ___74-[HAP2AccessoryServerSecureTransportBase sendProbeOnTransport:completion:]_block_invoke
+ ___74-[HAP2AccessoryServerSecureTransportBase sendProbeOnTransport:completion:]_block_invoke_2
+ ___74-[HAP2AccessoryServerTransportCoAP _finalizeRequestCompletion:path:error:]_block_invoke
+ ___74-[HAP2AccessoryServerTransportCoAP _openMultiTransportClientWithActivity:]_block_invoke
+ ___75-[HAP2BrowserResolverRegistry _performAuditPassOnQueueWithActiveDeviceIDs:]_block_invoke
+ ___76-[HAP2AccessoryServerTransportCoAP _armInitialCacheGracePeriodTimerIfNeeded]_block_invoke
+ ___76-[HAP2AccessoryServerTransportCoAP _armInitialCacheGracePeriodTimerIfNeeded]_block_invoke_2
+ ___76-[HAP2AccessoryServerTransportCoAP _openPrimaryClientForRefreshWithAddress:]_block_invoke
+ ___76-[HAP2AccessoryServerTransportCoAP _openPrimaryClientForRefreshWithAddress:]_block_invoke_2
+ ___78-[HAP2AccessoryServerTransportCoAP _openPrimaryClientIteratingWithCompletion:]_block_invoke
+ ___78-[HAP2AccessoryServerTransportCoAP _openPrimaryClientIteratingWithCompletion:]_block_invoke_2
+ ___78-[HAP2AccessoryServerTransportCoAP _openSecondaryClientForRefreshWithAddress:]_block_invoke
+ ___78-[HAP2AccessoryServerTransportCoAP _openSecondaryClientForRefreshWithAddress:]_block_invoke_2
+ ___78-[HAP2AccessoryServerTransportCoAP _sendRegistrationTLVWithAddressBytes:port:]_block_invoke
+ ___79-[HAP2AccessoryServerBrowser(Test) _test_restoreCachedAccessoryServersIfNeeded]_block_invoke
+ ___79-[HAP2AccessoryServerSecureTransportBase transport:didChangeWiFiAdvertisement:]_block_invoke
+ ___79-[HAP2AccessoryServerTransportCoAP signalPairVerifyFailureToDelegateWithError:]_block_invoke
+ ___80-[HAP2AccessoryServerCoordinator initializePairedAccessoryServerFromCachedInfo:]_block_invoke
+ ___80-[HAP2AccessoryServerCoordinator initializePairedAccessoryServerFromCachedInfo:]_block_invoke_2
+ ___81-[HAP2AccessoryServerSecureTransportBase transport:didChangeThreadAdvertisement:]_block_invoke
+ ___81-[HAPSecuritySession deriveEncryptionForDataStreamWithKeySalt:completionHandler:]_block_invoke
+ ___82-[HAP2AccessoryServerTransportCoAP _maybeFireOffQueueCacheMissCancelForAddresses:]_block_invoke
+ ___83-[HAP2AccessoryServer(PairedInternal) keepAliveListenerDidCompleteIPPortPairCheck:]_block_invoke
+ ___83-[HAP2AccessoryServer(PairedInternal) keepAliveListenerDidCompleteIPPortPairCheck:]_block_invoke_2
+ ___83-[HAP2AccessoryServerSecureTransportBase transport:didReceiveHeartbeatOnTransport:]_block_invoke
+ ___84-[HAP2AccessoryServer(PairedInternal) _handleProbeCompletion:forKeepAliveTransport:]_block_invoke
+ ___84-[HAP2AccessoryServerBrowser _reinitializeFromCachedRecordsAfterCoordinatorsStarted]_block_invoke
+ ___84-[HAP2AccessoryServerController checkConnectedIPAddressStaleOnTransport:completion:]_block_invoke
+ ___86-[HAP2AccessoryServer(Paired) mergeWithNewlyDiscoveredPairedAccessoryServer:resolver:]_block_invoke
+ ___87-[HAP2AccessoryServerTransportCoAP checkConnectedIPAddressStaleOnTransport:completion:]_block_invoke
+ ___87-[HAP2CoAPClient sendRequestWithMethod:path:payload:messageID:dscpPriority:completion:]_block_invoke
+ ___87-[HAP2CoAPClient sendRequestWithMethod:path:payload:messageID:dscpPriority:completion:]_block_invoke_2
+ ___88-[HAP2AccessoryServerTransportCoAP advanceEndpointAfterPairVerifyFailureWithCompletion:]_block_invoke
+ ___88-[HAP2AccessoryServerTransportCoAP advanceEndpointAfterPairVerifyFailureWithCompletion:]_block_invoke_2
+ ___89-[HAP2AccessoryDNSResolver _applyCachedIP:transportType:notifySubscriber:seedAgingClock:]_block_invoke
+ ___89-[HAP2AccessoryServerTransportCoAP _createDefaultResolverWithUpdateHandler:errorHandler:]_block_invoke
+ ___89-[HAP2AccessoryServerTransportCoAP _openSecondaryClientIteratingIsThreadOnly:completion:]_block_invoke
+ ___89-[HAP2AccessoryServerTransportCoAP _openSecondaryClientIteratingIsThreadOnly:completion:]_block_invoke_2
+ ___90-[HAP2AccessoryServer(PairedInternal) _closeSessionIfConnectedIPAddressStaleForTransport:]_block_invoke
+ ___90-[HAP2AccessoryServer(PairedInternal) _closeSessionIfConnectedIPAddressStaleForTransport:]_block_invoke_2
+ ___90-[HAP2AccessoryServerBrowser noteBonjourAdvertisementUpdatedForDeviceID:rawDiscoveryInfo:]_block_invoke
+ ___90-[HAP2AccessoryServerTransportCoAP _readLocalEndpointForClient:transport:into:completion:]_block_invoke
+ ___90-[HAP2AccessoryServerTransportCoAP _readLocalEndpointForClient:transport:into:completion:]_block_invoke_2
+ ___92-[HAPAccessoryServerHAP2Adapter deriveEncryptionForDataStreamWithKeySalt:completionHandler:]_block_invoke
+ ___93-[HAP2AccessoryServerSecureTransportBase checkConnectedIPAddressStaleOnTransport:completion:]_block_invoke
+ ___94-[HAP2BrowserResolverRegistry updateCachedAddressesForDeviceID:cachedPrimary:cachedSecondary:]_block_invoke
+ ___97-[HAP2CoAPClient _sendRequestWithMethod:path:payload:activity:messageID:dscpPriority:completion:]_block_invoke
+ ___97-[HAP2CoAPClient _sendRequestWithMethod:path:payload:activity:messageID:dscpPriority:completion:]_block_invoke_2
+ ___99-[HAP2AccessoryServerSecureTransportBase transport:pairVerifyDidCompleteOnIPAddress:transportType:]_block_invoke
+ ___block_descriptor_106_e8_32s40s48s56s64r72r80r88r_e28_v24?0"NSData"8"NSError"16l
+ ___block_descriptor_122_e8_32s40s48s56s64s72r80r88r96r104w_e28_v24?0"NSData"8"NSError"16l
+ ___block_descriptor_123_e8_32s40s48s56s64s72s80r88r96r104r112w_e5_v8?0l
+ ___block_descriptor_32_e716_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_40_e65_v24?0{shared_ptr<CtrXPC::Event>=^{Event}^{__shared_weak_count}}8l
+ ___block_descriptor_40_e8_32bs_e28_v24?0"NSData"8"NSError"16l
+ ___block_descriptor_40_e8_32bs_e49_v28?0B8"HAP2AccessorySessionInfo"12"NSError"20l
+ ___block_descriptor_40_e8_32s_e31_v28?0"NSData"8S16"NSError"20l
+ ___block_descriptor_40_e8_32w_e11_v16?0i8i12l
+ ___block_descriptor_40_e8_32w_e12_v24?0^8Q16l
+ ___block_descriptor_40_e8_32w_e15_v16?0?<v?q>8l
+ ___block_descriptor_40_e8_32w_e17_v16?0"NSArray"8l
+ ___block_descriptor_40_e8_32w_e22_v16?0"NSDictionary"8l
+ ___block_descriptor_42_e8_32s_e5_v8?0l
+ ___block_descriptor_48_e716_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_48_e8_32bs40r_e28_v24?0"NSData"8"NSError"16l
+ ___block_descriptor_48_e8_32bs40w_e862_v24?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_48_e8_32s40bs_e862_v24?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_48_e8_32s40s_e28_v32?0"NSOperation"8Q16^B24l
+ ___block_descriptor_48_e8_32w_e8_v12?0B8l
+ ___block_descriptor_49_e8_32bs40w_e17_v16?0"NSError"8l
+ ___block_descriptor_49_e8_32s40bs_e17_v16?0"NSError"8l
+ ___block_descriptor_50_e8_32s40bs_e5_v8?0l
+ ___block_descriptor_50_e8_32s40s_e5_v8?0l
+ ___block_descriptor_50_e8_32w_e5_v8?0l
+ ___block_descriptor_51_e8_32s40s_e17_v16?0"NSError"8l
+ ___block_descriptor_56_e8_32bs40w48w_e5_v8?0l
+ ___block_descriptor_56_e8_32s40s48bs_e862_v24?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_56_e8_32s40s48r_e72_"HAP2AccessoryServerIPCacheData"16?0"HAP2AccessoryServerIPCacheData"8l
+ ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSError"8l
+ ___block_descriptor_56_e8_32s40s48w_e20_v20?0B8"NSError"12l
+ ___block_descriptor_56_e8_32s40s_e72_"HAP2AccessoryServerIPCacheData"16?0"HAP2AccessoryServerIPCacheData"8l
+ ___block_descriptor_58_e8_32s40n9_8_8_s0_s8_e5_v8?0l
+ ___block_descriptor_58_e8_32s40s48s_e5_v8?0l
+ ___block_descriptor_58_e8_32s40s48w_e5_v8?0l
+ ___block_descriptor_59_e8_32s40s48s_e17_v16?0"NSError"8l
+ ___block_descriptor_64_e8_32bs40r48r56r_e5_v8?0l
+ ___block_descriptor_64_e8_32bs40r48w_e5_v8?0l
+ ___block_descriptor_64_e8_32bs40w_e5_v8?0l
+ ___block_descriptor_64_e8_32s40s48bs_e31_v28?0"NSData"8S16"NSError"20l
+ ___block_descriptor_65_e8_32s40s48bs56w_e20_v20?0B8"NSError"12l
+ ___block_descriptor_71_e8_32s40s48s_e716_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_72_e8_32s40s48s56s_e5_v8?0l
+ ___block_descriptor_74_e8_32s40s48s56bs_e5_v8?0l
+ ___block_descriptor_74_e8_32s40s48s56s_e28_v24?0"NSData"8"NSError"16l
+ ___block_descriptor_75_e8_32s40s48s56s64w_e22_v16?0"NSDictionary"8l
+ ___block_descriptor_81_e8_32s40s48r56r64r_e5_v8?0l
+ ___block_descriptor_82_e8_32s40s48s56w_e5_v8?0l
+ ___block_descriptor_83_e8_32s40s48s56s64bs_e5_v8?0l
+ ___block_descriptor_83_e8_32s40s48s56s64s72w_e5_v8?0l
+ ___copy_helper_block_e8_32b40r48r56r
+ ___copy_helper_block_e8_32b40r48w
+ ___copy_helper_block_e8_32b40w48w
+ ___copy_helper_block_e8_32s40n9_8_8_s0_s8
+ ___copy_helper_block_e8_32s40s48r56r64r
+ ___copy_helper_block_e8_32s40s48s56s64r72r80r88r
+ ___copy_helper_block_e8_32s40s48s56s64s72r80r88r96r104w
+ ___copy_helper_block_e8_32s40s48s56s64s72s80r88r96r104r112w
+ ___copy_helper_block_e8_32s40s48s56s64s72w
+ ___copy_helper_block_e8_32s40s48s56s64w
+ ___destroy_helper_block_e8_32s40n7_8_s0_s8
+ ___destroy_helper_block_e8_32s40s48r56r64r
+ ___destroy_helper_block_e8_32s40s48s56s64r72r80r88r
+ ___destroy_helper_block_e8_32s40s48s56s64s72r80r88r96r104w
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80r88r96r104r112w
+ ___destroy_helper_block_e8_32s40s48s56s64s72w
+ ___removeDependencyOnCompletion_block_invoke
+ _associated conformance So27HAP2CoAPAccessoryTransportsVs10SetAlgebraSCSQ
+ _associated conformance So27HAP2CoAPAccessoryTransportsVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So27HAP2CoAPAccessoryTransportsVs9OptionSetSCSY
+ _associated conformance So27HAP2CoAPAccessoryTransportsVs9OptionSetSCs0F7Algebra
+ _coapPingHandler
+ _coap_session_send_ping
+ _dispatch_activate
+ _dispatch_assert_queue_not$V2
+ _dispatch_semaphore_create
+ _dispatch_semaphore_signal
+ _dispatch_semaphore_wait
+ _dnssd_getaddrinfo_activate
+ _dnssd_getaddrinfo_create
+ _dnssd_getaddrinfo_invalidate
+ _dnssd_getaddrinfo_result_get_address
+ _dnssd_getaddrinfo_result_get_type
+ _dnssd_getaddrinfo_set_event_handler
+ _dnssd_getaddrinfo_set_flags
+ _dnssd_getaddrinfo_set_hostname
+ _dnssd_getaddrinfo_set_interface_index
+ _dnssd_getaddrinfo_set_protocols
+ _dnssd_getaddrinfo_set_queue
+ _dnssd_getaddrinfo_set_result_handler
+ _get_time_now
+ _objc_msgSend$_acquireDNSContextOwnership
+ _objc_msgSend$_addressToCIDR:withNetmask:
+ _objc_msgSend$_applyCachedIP:transportType:notifySubscriber:seedAgingClock:
+ _objc_msgSend$_armInitialCacheGracePeriodTimerIfNeeded
+ _objc_msgSend$_armPTRRevalidationWindow
+ _objc_msgSend$_buildActiveDeviceIDsSet
+ _objc_msgSend$_cancelPTRRevalidationWindow
+ _objc_msgSend$_cancelResolver
+ _objc_msgSend$_classifyTransportType:
+ _objc_msgSend$_clearAllAddresses
+ _objc_msgSend$_closeSessionIfConnectedIPAddressStaleForTransport:
+ _objc_msgSend$_coapAddressFromGAIResult:outAddress:
+ _objc_msgSend$_controllerUnchecked
+ _objc_msgSend$_copyDelegates
+ _objc_msgSend$_evaluateCacheMissCancelIfNeededWithLivePrimaryCount:
+ _objc_msgSend$_eventQueue
+ _objc_msgSend$_executeCacheMissCancel
+ _objc_msgSend$_fetchMeshLocalPrefixFromXPC
+ _objc_msgSend$_fireRevalidationSweep
+ _objc_msgSend$_handleGetaddrinfoEvent:error:
+ _objc_msgSend$_handleGetaddrinfoResults:count:
+ _objc_msgSend$_handleLiveResolverUpdate
+ _objc_msgSend$_handlePipelineError:
+ _objc_msgSend$_handlePipelineUpdate:
+ _objc_msgSend$_handleProbeCompletion:forKeepAliveTransport:
+ _objc_msgSend$_handleResolveCallbackWithError:hostname:port:
+ _objc_msgSend$_handleTimerFireForTransport:
+ _objc_msgSend$_haveAllTransportsHitFailureThreshold
+ _objc_msgSend$_initializeFromCachedRecord:deviceID:
+ _objc_msgSend$_maybeFireOffQueueCacheMissCancelForAddresses:
+ _objc_msgSend$_performAuditPass
+ _objc_msgSend$_performAuditPassOnQueueWithActiveDeviceIDs:
+ _objc_msgSend$_recordAddedAddress:
+ _objc_msgSend$_recordRemovedAddress:
+ _objc_msgSend$_refreshIPAddresses
+ _objc_msgSend$_reinitializeFromCachedRecordsAfterCoordinatorsStarted
+ _objc_msgSend$_releaseDNSContextOwnership
+ _objc_msgSend$_resetIPsTriedThisSession
+ _objc_msgSend$_resetInitialCacheOnlyStopgapState
+ _objc_msgSend$_resolveAddress
+ _objc_msgSend$_restampWorkingSetWithResolvedPort
+ _objc_msgSend$_restartPipelineOnQueue
+ _objc_msgSend$_restoreCachedAccessoryServersIfNeeded
+ _objc_msgSend$_seedCachedIP:transportType:
+ _objc_msgSend$_sendEndpointRegistration
+ _objc_msgSend$_sendMultiTransportRequest:path:
+ _objc_msgSend$_sendWiFiEndpointRegistration
+ _objc_msgSend$_setHasThreadAdvertisement:
+ _objc_msgSend$_setHasWiFiAdvertisement:
+ _objc_msgSend$_shouldRegisterEndpoint
+ _objc_msgSend$_startGetaddrinfoForHostname:
+ _objc_msgSend$_startPipelineOnQueue
+ _objc_msgSend$_startResolverIfNeeded
+ _objc_msgSend$_takeNextPrimaryIPToTry
+ _objc_msgSend$_takeNextSecondaryIPToTry
+ _objc_msgSend$_tearDownPipeline
+ _objc_msgSend$abandonedRequestCount
+ _objc_msgSend$accessory:didUpdateLocalEndpoints:
+ _objc_msgSend$accessoryDeviceIPAddressWithSerializedData:
+ _objc_msgSend$accessoryInfoWithDeviceID:rawDiscoveryInfo:
+ _objc_msgSend$accessoryServer:didUpdateLocalEndpoints:
+ _objc_msgSend$activeHardwareFaults
+ _objc_msgSend$addDelegate:
+ _objc_msgSend$addressResolverFactory
+ _objc_msgSend$allCachedRecords
+ _objc_msgSend$applyResolverAddresses:completion:
+ _objc_msgSend$arrayByAddingObject:
+ _objc_msgSend$attachCacheSubscriber:
+ _objc_msgSend$attachDelegate:
+ _objc_msgSend$attachSelfAsCacheSubscriberOnResolver:
+ _objc_msgSend$audioOnlyFailureCount
+ _objc_msgSend$auditScheduler
+ _objc_msgSend$authenticationErrorCount
+ _objc_msgSend$averageCPUUtilization
+ _objc_msgSend$averageDeviceTemperature
+ _objc_msgSend$averageSystemMemoryUtilization
+ _objc_msgSend$batteryPercentage
+ _objc_msgSend$beaconLostCount
+ _objc_msgSend$beaconRxCount
+ _objc_msgSend$beaconRxInterval
+ _objc_msgSend$becameEmptyAt
+ _objc_msgSend$bluetoothVersion
+ _objc_msgSend$brownOutResetBootCount
+ _objc_msgSend$cachedIPDidUpdate:transportType:
+ _objc_msgSend$cachedIPDidUpdate:transportType:forDeviceID:
+ _objc_msgSend$cachedPrimary
+ _objc_msgSend$cachedPrimaryData
+ _objc_msgSend$cachedSecondary
+ _objc_msgSend$cachedSecondaryData
+ _objc_msgSend$checkConnectedIPAddressStaleOnTransport:completion:
+ _objc_msgSend$chmAccessoryRebootCompleted
+ _objc_msgSend$chmAccessoryRebootDurationToRecovery
+ _objc_msgSend$clientDidReceivePing:
+ _objc_msgSend$configurationInfo
+ _objc_msgSend$configureKeepAliveListener:
+ _objc_msgSend$connectionCount
+ _objc_msgSend$connectionErrorCount
+ _objc_msgSend$connectionStatus
+ _objc_msgSend$connectivityMonitorBootCount
+ _objc_msgSend$containsHAPPortUnreachableError
+ _objc_msgSend$countForObject:
+ _objc_msgSend$createResolverWithDeviceID:serviceName:
+ _objc_msgSend$createResolverWithServiceName:serviceType:serviceDomain:queue:updateHandler:errorHandler:
+ _objc_msgSend$currentAddresses
+ _objc_msgSend$currentPTRs
+ _objc_msgSend$currentPowerSource
+ _objc_msgSend$currentResolverSnapshot
+ _objc_msgSend$dataStreamPeerAddressWithCompletion:
+ _objc_msgSend$dateProvider
+ _objc_msgSend$deferAgingClockIfRunning
+ _objc_msgSend$deliverRacingResult:forAccessoryIdentifier:messageID:
+ _objc_msgSend$deriveEncryptionForDataStreamWithKeySalt:completionHandler:
+ _objc_msgSend$detachDelegate:
+ _objc_msgSend$deviceRebootDelay
+ _objc_msgSend$deviceRebootEnable
+ _objc_msgSend$didChangeThreadAdvertisement:
+ _objc_msgSend$didChangeWiFiAdvertisement:
+ _objc_msgSend$didReceiveHeartbeatOnTransport:
+ _objc_msgSend$didReceivePingInSession:messageID:
+ _objc_msgSend$disconnectionCount
+ _objc_msgSend$disconnectionDuration
+ _objc_msgSend$disconnectionErrorCount
+ _objc_msgSend$dnsResolver
+ _objc_msgSend$durationOnBatteryPower
+ _objc_msgSend$durationRemainingOnBatteryPower
+ _objc_msgSend$entries
+ _objc_msgSend$errorID
+ _objc_msgSend$expectedBootCount
+ _objc_msgSend$forceRefreshMeshLocalPrefix
+ _objc_msgSend$foreignPairVerifySession
+ _objc_msgSend$fragmentFailureCount
+ _objc_msgSend$fragmentRetriedCount
+ _objc_msgSend$fragmentSuccessCount
+ _objc_msgSend$gatewayIPv4Address
+ _objc_msgSend$gatewayIPv6Address
+ _objc_msgSend$gatewayMacAddress
+ _objc_msgSend$getCurrentNetworkInterfaces
+ _objc_msgSend$getLocalEndpointWithCompletion:
+ _objc_msgSend$getLocalIPv4EndpointWithCompletion:
+ _objc_msgSend$getLocalIPv6EndpointWithCompletion:
+ _objc_msgSend$getRTTStatisticsWithCompletion:
+ _objc_msgSend$hapSessionLossCount
+ _objc_msgSend$hardwareFaultBootCount
+ _objc_msgSend$hardwareWatchdogResetBootCount
+ _objc_msgSend$hasArmedCacheOnlyLatch
+ _objc_msgSend$hasCurrentPTRForDeviceID:
+ _objc_msgSend$hasDiscoveryAdvertisementForAccessoryWithID:
+ _objc_msgSend$hasMissedHeartbeat
+ _objc_msgSend$hasMissedHeartbeatForTransport:
+ _objc_msgSend$hasQueuedCloseOperation
+ _objc_msgSend$hasRegisteredEndpoint
+ _objc_msgSend$hasSeededSinceResolverAttach
+ _objc_msgSend$hasThreadAdvertisement
+ _objc_msgSend$hasThreadAdvertisementForAccessoryWithID:
+ _objc_msgSend$hasWiFiAdvertisement
+ _objc_msgSend$hasWiFiAdvertisementForAccessoryWithID:
+ _objc_msgSend$heapHighwaterCount
+ _objc_msgSend$heapOverflowBootCount
+ _objc_msgSend$heapOverflowCount
+ _objc_msgSend$hwExceptionCount
+ _objc_msgSend$init:
+ _objc_msgSend$initFromDictionary:deviceID:
+ _objc_msgSend$initWithBluetoothVersion:rssi:txPowerLevel:packetRxCount:packetTxCount:packetRxErrorCount:packetTxErrorCount:overrunCount:connectionStatus:connectionCount:connectionErrorCount:disconnectionCount:disconnectionErrorCount:hwExceptionCount:
+ _objc_msgSend$initWithConfigurationEntries:workQueue:timerProvider:dateProvider:
+ _objc_msgSend$initWithDeviceID:cachedPrimaryData:cachedSecondaryData:configurationInfo:
+ _objc_msgSend$initWithDeviceID:serviceName:managerQueue:pipelineFactory:
+ _objc_msgSend$initWithDeviceRebootEnable:threadRecoveryConfiguration:wiFiRecoveryConfiguration:recoveryStaggerDelay:deviceRebootDelay:threadPingTestCount:threadPingTestInterval:threadRestartMinInterval:wiFiPingTestCount:wiFiPingTestInterval:wiFiRestartMinInterval:
+ _objc_msgSend$initWithEntries:
+ _objc_msgSend$initWithErrorID:count:
+ _objc_msgSend$initWithFragmentSuccessCount:fragmentFailureCount:fragmentRetriedCount:networkErrorCount:authenticationErrorCount:serverReturnedErrorCount:localErrorCount:playlistFailureCount:latencyCount250ms:latencyCount500ms:latencyCount1000ms:latencyCount2000ms:latencyCount3750ms:latencyCountOver3750ms:sessionSuccessCount:partialSuccessCount:sessionFailureCount:uploadWithoutResidentResponseCount:audioOnlyFailureCount:abandonedRequestCount:
+ _objc_msgSend$initWithGatewayMacAddress:gatewayIPv4Address:gatewayIPv6Address:subnetMask:bssid:wifiVersion:channelNumber:rssi:connectionStatus:disconnectionCount:disconnectionDuration:beaconRxCount:beaconRxInterval:beaconLostCount:ipAddressList:packetMulticastRxCount:packetMulticastRxErrorCount:packetMulticastTxCount:packetMulticastTxErrorCount:packetUnicastRxCount:packetUnicastRxErrorCount:packetUnicastTxCount:packetUnicastTxErrorCount:txPacketCount:txPacketErrorCount:rxPacketCount:rxPacketErrorCount:hwExceptionCount:wifiRestartCount:
+ _objc_msgSend$initWithInteger:
+ _objc_msgSend$initWithName:browser:
+ _objc_msgSend$initWithPreferredWiFiList:
+ _objc_msgSend$initWithPrimary:secondary:
+ _objc_msgSend$initWithPrimary:secondary:cachedPrimary:cachedSecondary:
+ _objc_msgSend$initWithQueue:updateHandler:errorHandler:
+ _objc_msgSend$initWithStackHighwaterCount:lastStackHighwaterTaskName:heapHighwaterCount:lastHeapHighwaterTaskName:stackOverflowCount:lastStackOverflowTaskName:heapOverflowCount:lastHeapOverflowTaskName:averageSystemMemoryUtilization:peakSystemMemoryUtilization:systemMemoryPressureCount:processCriticalMemoryCount:lastProcessCriticalMemoryName:averageCPUUtilization:peakCPUUtilization:taskDeadlineMissCount:totalTasksScheduledCount:maxTaskReadyQueueSize:loadAverage:nonVolatileMemoryWriteCount:nonVolatileMemoryReadCount:nonVolatileMemoryWriteErrorCount:nonVolatileMemoryReadErrorCount:nonVolatileMemoryUtilization:
+ _objc_msgSend$initWithStartTime:
+ _objc_msgSend$initWithSupportedPowerSources:currentPowerSource:durationOnBatteryPower:durationRemainingOnBatteryPower:batteryPercentage:
+ _objc_msgSend$initWithSystemUptime:systemBootCount:expectedBootCount:systemCrashCount:systemHangCount:lastBootReason:activeHardwareFaults:
+ _objc_msgSend$initWithTemperatureLimitViolationCount:temperatureLimitViolationDuration:minimumDeviceTemperature:maximumDeviceTemperature:averageDeviceTemperature:
+ _objc_msgSend$initWithTransportType:maximumInterval:
+ _objc_msgSend$initWithTransportType:minimumInterval:maximumInterval:
+ _objc_msgSend$initWithTransportType:minimumInterval:maximumInterval:minimumRange:
+ _objc_msgSend$initWithUnsignedInteger:
+ _objc_msgSend$initWithUnspecifiedBootCount:powerOnBootCount:brownOutResetBootCount:softwareWatchdogResetBootCount:hardwareWatchdogResetBootCount:softwareUpdateCompletedBootCount:softwareResetBootCount:softwareExceptionBootCount:hardwareFaultBootCount:stackOverflowBootCount:heapOverflowBootCount:temperatureLimitBootCount:connectivityMonitorBootCount:
+ _objc_msgSend$initWithWifiTransportLossCount:wifiRecoveryAttemptCount:wifiRestartCount:wifiFirstRestartRecoveryTime:wifiFirstRestartCompleted:wifiFirstRestartConnectivityState:threadTransportLossCount:threadRecoveryAttemptCount:threadRestartCount:threadFirstRestartRecoveryTime:threadFirstRestartCompleted:threadFirstRestartConnectivityState:hapSessionLossCount:chmAccessoryRebootDurationToRecovery:chmAccessoryRebootCompleted:
+ _objc_msgSend$initialCacheGracePeriodTimer
+ _objc_msgSend$initialConnectionAttemptStartedAt
+ _objc_msgSend$initializePairedAccessoryServerFromCachedInfo:
+ _objc_msgSend$ipAddressList
+ _objc_msgSend$ipCache
+ _objc_msgSend$isAddress:inNetwork:
+ _objc_msgSend$isEqualToDictionary:
+ _objc_msgSend$isForWriting
+ _objc_msgSend$isIPv6
+ _objc_msgSend$isThreadIPv6Address:fromInterfaces:
+ _objc_msgSend$isThreadInterface:
+ _objc_msgSend$keepAliveListener:didMissHeartbeatOnTransport:expectedInterval:timeSinceLastHeartbeat:allTransportsMissed:
+ _objc_msgSend$keepAliveListener:didReceiveHeartbeatOnTransport:
+ _objc_msgSend$keepAliveListenerDidCompleteIPPortPairCheck:
+ _objc_msgSend$lastBootReason
+ _objc_msgSend$lastCompletedMessageID
+ _objc_msgSend$lastHeapHighwaterTaskName
+ _objc_msgSend$lastHeapOverflowTaskName
+ _objc_msgSend$lastHeartbeatTime
+ _objc_msgSend$lastMessageID
+ _objc_msgSend$lastObservedHasAdvertisement
+ _objc_msgSend$lastProcessCriticalMemoryName
+ _objc_msgSend$lastStackHighwaterTaskName
+ _objc_msgSend$lastStackOverflowTaskName
+ _objc_msgSend$latencyCount1000ms
+ _objc_msgSend$latencyCount2000ms
+ _objc_msgSend$latencyCount250ms
+ _objc_msgSend$latencyCount3750ms
+ _objc_msgSend$latencyCount500ms
+ _objc_msgSend$latencyCountOver3750ms
+ _objc_msgSend$loadAverage
+ _objc_msgSend$localErrorCount
+ _objc_msgSend$managerQueue
+ _objc_msgSend$maxTaskReadyQueueSize
+ _objc_msgSend$maximumDeviceTemperature
+ _objc_msgSend$maximumInterval
+ _objc_msgSend$mergeWithNewlyDiscoveredPairedAccessoryServer:resolver:
+ _objc_msgSend$minimumDeviceTemperature
+ _objc_msgSend$minimumInterval
+ _objc_msgSend$minimumRange
+ _objc_msgSend$missCheckTimer
+ _objc_msgSend$mutateCachedRecordForDeviceID:usingBlock:
+ _objc_msgSend$networkErrorCount
+ _objc_msgSend$nonVolatileMemoryReadCount
+ _objc_msgSend$nonVolatileMemoryReadErrorCount
+ _objc_msgSend$nonVolatileMemoryUtilization
+ _objc_msgSend$nonVolatileMemoryWriteCount
+ _objc_msgSend$nonVolatileMemoryWriteErrorCount
+ _objc_msgSend$noteBonjourAdvertisementUpdatedForDeviceID:rawDiscoveryInfo:
+ _objc_msgSend$noteBrowsedPTRAddForDeviceID:serviceName:
+ _objc_msgSend$noteBrowsedPTRRemoveForDeviceID:
+ _objc_msgSend$noteResolverReapedForDeviceID:
+ _objc_msgSend$overrunCount
+ _objc_msgSend$packetMulticastRxCount
+ _objc_msgSend$packetMulticastRxErrorCount
+ _objc_msgSend$packetMulticastTxCount
+ _objc_msgSend$packetMulticastTxErrorCount
+ _objc_msgSend$packetRxCount
+ _objc_msgSend$packetRxErrorCount
+ _objc_msgSend$packetTxCount
+ _objc_msgSend$packetTxErrorCount
+ _objc_msgSend$packetUnicastRxCount
+ _objc_msgSend$packetUnicastRxErrorCount
+ _objc_msgSend$packetUnicastTxCount
+ _objc_msgSend$packetUnicastTxErrorCount
+ _objc_msgSend$pairVerifyDidCompleteOnIPAddress:transportType:
+ _objc_msgSend$pairVerifyDidFailOnIPAddress:transportType:error:
+ _objc_msgSend$partialSuccessCount
+ _objc_msgSend$peakCPUUtilization
+ _objc_msgSend$peakSystemMemoryUtilization
+ _objc_msgSend$performAuditPassWithActiveDeviceIDs:
+ _objc_msgSend$performHealthCheck
+ _objc_msgSend$pipelineFactory
+ _objc_msgSend$playlistFailureCount
+ _objc_msgSend$powerOnBootCount
+ _objc_msgSend$preferredWiFiList
+ _objc_msgSend$primaryEffectiveListIsCacheOnly
+ _objc_msgSend$primaryIPsTriedThisSession
+ _objc_msgSend$primaryOpenInFlight
+ _objc_msgSend$processCriticalMemoryCount
+ _objc_msgSend$racingTriggerReason
+ _objc_msgSend$readLocalEndpointsWithHandler:
+ _objc_msgSend$recoveryStaggerDelay
+ _objc_msgSend$removeCachedRecordForDeviceID:
+ _objc_msgSend$removeDelegate:
+ _objc_msgSend$resetHeartbeatTimestamps
+ _objc_msgSend$resolveTimeoutTimer
+ _objc_msgSend$resolver:didUpdateAddresses:
+ _objc_msgSend$resolverForDeviceID:
+ _objc_msgSend$resolverRegistry
+ _objc_msgSend$resolverRestartTimer
+ _objc_msgSend$restartKeepAliveListener
+ _objc_msgSend$revalidationTimer
+ _objc_msgSend$rxPacketCount
+ _objc_msgSend$rxPacketErrorCount
+ _objc_msgSend$secondaryAddressList
+ _objc_msgSend$secondaryCoAPClient
+ _objc_msgSend$secondaryIPsTriedThisSession
+ _objc_msgSend$secureTransport:didChangeThreadAdvertisement:
+ _objc_msgSend$secureTransport:didChangeWiFiAdvertisement:
+ _objc_msgSend$secureTransport:didReceiveHeartbeatOnTransport:
+ _objc_msgSend$secureTransport:pairVerifyDidCompleteOnIPAddress:transportType:
+ _objc_msgSend$secureTransport:pairVerifyDidFailOnIPAddress:transportType:error:
+ _objc_msgSend$secureTransportCurrentResolverSnapshot:
+ _objc_msgSend$securedClient
+ _objc_msgSend$sendProbeOnTransport:completion:
+ _objc_msgSend$sendProbeWithCompletion:
+ _objc_msgSend$sendRequestWithMethod:path:payload:messageID:dscpPriority:completion:
+ _objc_msgSend$sentOverThread
+ _objc_msgSend$sentOverWiFi
+ _objc_msgSend$serializedData
+ _objc_msgSend$serverReturnedErrorCount
+ _objc_msgSend$sessionFailureCount
+ _objc_msgSend$sessionSuccessCount
+ _objc_msgSend$setAbandonedRequestCount:
+ _objc_msgSend$setAccessoryTransports:
+ _objc_msgSend$setActiveHardwareFaults:
+ _objc_msgSend$setAudioOnlyFailureCount:
+ _objc_msgSend$setAuthenticationErrorCount:
+ _objc_msgSend$setAverageCPUUtilization:
+ _objc_msgSend$setAverageDeviceTemperature:
+ _objc_msgSend$setAverageSystemMemoryUtilization:
+ _objc_msgSend$setBatteryPercentage:
+ _objc_msgSend$setBeaconLostCount:
+ _objc_msgSend$setBeaconRxCount:
+ _objc_msgSend$setBeaconRxInterval:
+ _objc_msgSend$setBluetoothVersion:
+ _objc_msgSend$setBrownOutResetBootCount:
+ _objc_msgSend$setBssid:
+ _objc_msgSend$setChannelNumber:
+ _objc_msgSend$setChmAccessoryRebootCompleted:
+ _objc_msgSend$setChmAccessoryRebootDurationToRecovery:
+ _objc_msgSend$setClientEventsOn
+ _objc_msgSend$setCoapMessageID:
+ _objc_msgSend$setConnectionCount:
+ _objc_msgSend$setConnectionErrorCount:
+ _objc_msgSend$setConnectionStatus:
+ _objc_msgSend$setConnectivityMonitorBootCount:
+ _objc_msgSend$setCount:
+ _objc_msgSend$setCurrentPowerSource:
+ _objc_msgSend$setDeviceRebootDelay:
+ _objc_msgSend$setDeviceRebootEnable:
+ _objc_msgSend$setDisconnectionCount:
+ _objc_msgSend$setDisconnectionDuration:
+ _objc_msgSend$setDisconnectionErrorCount:
+ _objc_msgSend$setDnsResolver:
+ _objc_msgSend$setDurationOnBatteryPower:
+ _objc_msgSend$setDurationRemainingOnBatteryPower:
+ _objc_msgSend$setEntries:
+ _objc_msgSend$setErrorID:
+ _objc_msgSend$setEventHandler:EventBlock:dqueue:
+ _objc_msgSend$setExpectedBootCount:
+ _objc_msgSend$setForeignPairVerifySession:
+ _objc_msgSend$setFragmentFailureCount:
+ _objc_msgSend$setFragmentRetriedCount:
+ _objc_msgSend$setFragmentSuccessCount:
+ _objc_msgSend$setGatewayIPv4Address:
+ _objc_msgSend$setGatewayIPv6Address:
+ _objc_msgSend$setGatewayMacAddress:
+ _objc_msgSend$setHapSessionLossCount:
+ _objc_msgSend$setHardwareFaultBootCount:
+ _objc_msgSend$setHardwareWatchdogResetBootCount:
+ _objc_msgSend$setHasMissedHeartbeat:
+ _objc_msgSend$setHasRegisteredEndpoint:
+ _objc_msgSend$setHasSeededSinceResolverAttach:
+ _objc_msgSend$setHasThreadAdvertisement:
+ _objc_msgSend$setHasWiFiAdvertisement:
+ _objc_msgSend$setHeapHighwaterCount:
+ _objc_msgSend$setHeapOverflowBootCount:
+ _objc_msgSend$setHeapOverflowCount:
+ _objc_msgSend$setHwExceptionCount:
+ _objc_msgSend$setIPCache:
+ _objc_msgSend$setInitialCacheGracePeriodTimer:
+ _objc_msgSend$setInitialConnectionAttemptStartedAt:
+ _objc_msgSend$setIpAddressList:
+ _objc_msgSend$setIsRunning:
+ _objc_msgSend$setIsWrite:
+ _objc_msgSend$setLastBootReason:
+ _objc_msgSend$setLastHeapHighwaterTaskName:
+ _objc_msgSend$setLastHeapOverflowTaskName:
+ _objc_msgSend$setLastHeartbeatTime:
+ _objc_msgSend$setLastMessageID:
+ _objc_msgSend$setLastObservedHasAdvertisement:
+ _objc_msgSend$setLastPairSetupWasSpake2:
+ _objc_msgSend$setLastProcessCriticalMemoryName:
+ _objc_msgSend$setLastStackHighwaterTaskName:
+ _objc_msgSend$setLastStackOverflowTaskName:
+ _objc_msgSend$setLatencyCount1000ms:
+ _objc_msgSend$setLatencyCount2000ms:
+ _objc_msgSend$setLatencyCount250ms:
+ _objc_msgSend$setLatencyCount3750ms:
+ _objc_msgSend$setLatencyCount500ms:
+ _objc_msgSend$setLatencyCountOver3750ms:
+ _objc_msgSend$setLivePairedAccessoryServers:
+ _objc_msgSend$setLoadAverage:
+ _objc_msgSend$setLocalErrorCount:
+ _objc_msgSend$setMaxTaskReadyQueueSize:
+ _objc_msgSend$setMaximumDeviceTemperature:
+ _objc_msgSend$setMaximumInterval:
+ _objc_msgSend$setMinimumDeviceTemperature:
+ _objc_msgSend$setMinimumInterval:
+ _objc_msgSend$setMinimumRange:
+ _objc_msgSend$setMissCheckTimer:
+ _objc_msgSend$setNetworkErrorCount:
+ _objc_msgSend$setNonVolatileMemoryReadCount:
+ _objc_msgSend$setNonVolatileMemoryReadErrorCount:
+ _objc_msgSend$setNonVolatileMemoryUtilization:
+ _objc_msgSend$setNonVolatileMemoryWriteCount:
+ _objc_msgSend$setNonVolatileMemoryWriteErrorCount:
+ _objc_msgSend$setObject:atIndexedSubscript:
+ _objc_msgSend$setOverrunCount:
+ _objc_msgSend$setPacketMulticastRxCount:
+ _objc_msgSend$setPacketMulticastRxErrorCount:
+ _objc_msgSend$setPacketMulticastTxCount:
+ _objc_msgSend$setPacketMulticastTxErrorCount:
+ _objc_msgSend$setPacketRxCount:
+ _objc_msgSend$setPacketRxErrorCount:
+ _objc_msgSend$setPacketTxCount:
+ _objc_msgSend$setPacketTxErrorCount:
+ _objc_msgSend$setPacketUnicastRxCount:
+ _objc_msgSend$setPacketUnicastRxErrorCount:
+ _objc_msgSend$setPacketUnicastTxCount:
+ _objc_msgSend$setPacketUnicastTxErrorCount:
+ _objc_msgSend$setPartialSuccessCount:
+ _objc_msgSend$setPeakCPUUtilization:
+ _objc_msgSend$setPeakSystemMemoryUtilization:
+ _objc_msgSend$setPendingRevalidationPTRs:
+ _objc_msgSend$setPipelineFactory:
+ _objc_msgSend$setPlaylistFailureCount:
+ _objc_msgSend$setPowerOnBootCount:
+ _objc_msgSend$setPreferredWiFiList:
+ _objc_msgSend$setPrimaryEffectiveListIsCacheOnly:
+ _objc_msgSend$setPrimaryOpenInFlight:
+ _objc_msgSend$setProcessCriticalMemoryCount:
+ _objc_msgSend$setRaceTimeout:
+ _objc_msgSend$setRacingTriggerReason:
+ _objc_msgSend$setRecoveryStaggerDelay:
+ _objc_msgSend$setResolveTimeoutTimer:
+ _objc_msgSend$setResolverRegistry:
+ _objc_msgSend$setResolverRestartTimer:
+ _objc_msgSend$setRevalidationTimer:
+ _objc_msgSend$setRssi:
+ _objc_msgSend$setRxPacketCount:
+ _objc_msgSend$setRxPacketErrorCount:
+ _objc_msgSend$setSecondaryCoAPClient:
+ _objc_msgSend$setSecuredClient:
+ _objc_msgSend$setSentOverThread:
+ _objc_msgSend$setSentOverWiFi:
+ _objc_msgSend$setServerReturnedErrorCount:
+ _objc_msgSend$setSessionFailureCount:
+ _objc_msgSend$setSessionSuccessCount:
+ _objc_msgSend$setSoftwareExceptionBootCount:
+ _objc_msgSend$setSoftwareResetBootCount:
+ _objc_msgSend$setSoftwareUpdateCompletedBootCount:
+ _objc_msgSend$setSoftwareWatchdogResetBootCount:
+ _objc_msgSend$setStackHighwaterCount:
+ _objc_msgSend$setStackOverflowBootCount:
+ _objc_msgSend$setStackOverflowCount:
+ _objc_msgSend$setSubnetMask:
+ _objc_msgSend$setSupportedPowerSources:
+ _objc_msgSend$setSupportsKeepAlive:
+ _objc_msgSend$setSupportsThreadTransport:
+ _objc_msgSend$setSupportsWiFiTransport:
+ _objc_msgSend$setSystemBootCount:
+ _objc_msgSend$setSystemCrashCount:
+ _objc_msgSend$setSystemHangCount:
+ _objc_msgSend$setSystemMemoryPressureCount:
+ _objc_msgSend$setSystemUptime:
+ _objc_msgSend$setTaskDeadlineMissCount:
+ _objc_msgSend$setTemperatureLimitBootCount:
+ _objc_msgSend$setTemperatureLimitViolationCount:
+ _objc_msgSend$setTemperatureLimitViolationDuration:
+ _objc_msgSend$setThreadError:
+ _objc_msgSend$setThreadFirstRestartCompleted:
+ _objc_msgSend$setThreadFirstRestartConnectivityState:
+ _objc_msgSend$setThreadFirstRestartRecoveryTime:
+ _objc_msgSend$setThreadPingTestCount:
+ _objc_msgSend$setThreadPingTestInterval:
+ _objc_msgSend$setThreadRecoveryAttemptCount:
+ _objc_msgSend$setThreadRecoveryConfiguration:
+ _objc_msgSend$setThreadResponseLatency:
+ _objc_msgSend$setThreadRestartCount:
+ _objc_msgSend$setThreadRestartMinInterval:
+ _objc_msgSend$setThreadTransportLossCount:
+ _objc_msgSend$setTotalTasksScheduledCount:
+ _objc_msgSend$setTryingInitialCacheOnly:
+ _objc_msgSend$setTxPacketCount:
+ _objc_msgSend$setTxPacketErrorCount:
+ _objc_msgSend$setTxPowerLevel:
+ _objc_msgSend$setUnspecifiedBootCount:
+ _objc_msgSend$setUploadWithoutResidentResponseCount:
+ _objc_msgSend$setWiFiPingTestCount:
+ _objc_msgSend$setWiFiPingTestInterval:
+ _objc_msgSend$setWiFiRecoveryConfiguration:
+ _objc_msgSend$setWiFiRestartMinInterval:
+ _objc_msgSend$setWifiError:
+ _objc_msgSend$setWifiFirstRestartCompleted:
+ _objc_msgSend$setWifiFirstRestartConnectivityState:
+ _objc_msgSend$setWifiFirstRestartRecoveryTime:
+ _objc_msgSend$setWifiRTT:
+ _objc_msgSend$setWifiRecoveryAttemptCount:
+ _objc_msgSend$setWifiResponseLatency:
+ _objc_msgSend$setWifiRestartCount:
+ _objc_msgSend$setWifiTransportLossCount:
+ _objc_msgSend$setWifiVersion:
+ _objc_msgSend$setWinningTransport:
+ _objc_msgSend$setupEventSubscriptions
+ _objc_msgSend$signalPairVerifyFailureToDelegateWithError:
+ _objc_msgSend$signalPairVerifySuccessToDelegate
+ _objc_msgSend$softwareExceptionBootCount
+ _objc_msgSend$softwareResetBootCount
+ _objc_msgSend$softwareUpdateCompletedBootCount
+ _objc_msgSend$softwareWatchdogResetBootCount
+ _objc_msgSend$stackHighwaterCount
+ _objc_msgSend$stackOverflowBootCount
+ _objc_msgSend$stackOverflowCount
+ _objc_msgSend$startPipeline
+ _objc_msgSend$startWithServiceName:serviceType:serviceDomain:
+ _objc_msgSend$stopPipeline
+ _objc_msgSend$subnetMask
+ _objc_msgSend$supportedPowerSources
+ _objc_msgSend$supportsKeepAlive
+ _objc_msgSend$supportsThreadTransport
+ _objc_msgSend$supportsWiFiTransport
+ _objc_msgSend$systemBootCount
+ _objc_msgSend$systemCrashCount
+ _objc_msgSend$systemHangCount
+ _objc_msgSend$systemMemoryPressureCount
+ _objc_msgSend$systemUptime
+ _objc_msgSend$taskDeadlineMissCount
+ _objc_msgSend$temperatureLimitBootCount
+ _objc_msgSend$temperatureLimitViolationCount
+ _objc_msgSend$temperatureLimitViolationDuration
+ _objc_msgSend$threadFirstRestartCompleted
+ _objc_msgSend$threadFirstRestartConnectivityState
+ _objc_msgSend$threadFirstRestartRecoveryTime
+ _objc_msgSend$threadPingTestCount
+ _objc_msgSend$threadPingTestInterval
+ _objc_msgSend$threadRecoveryAttemptCount
+ _objc_msgSend$threadRecoveryConfiguration
+ _objc_msgSend$threadRestartCount
+ _objc_msgSend$threadRestartMinInterval
+ _objc_msgSend$threadTransportLossCount
+ _objc_msgSend$timeIntervalSinceNow
+ _objc_msgSend$timerProvider
+ _objc_msgSend$timerWithTimeInterval:options:
+ _objc_msgSend$totalTasksScheduledCount
+ _objc_msgSend$trackedTransportTypes
+ _objc_msgSend$transport:didChangeThreadAdvertisement:
+ _objc_msgSend$transport:didChangeWiFiAdvertisement:
+ _objc_msgSend$transport:didReceiveHeartbeatOnTransport:
+ _objc_msgSend$transport:pairVerifyDidCompleteOnIPAddress:transportType:
+ _objc_msgSend$transport:pairVerifyDidFailOnIPAddress:transportType:error:
+ _objc_msgSend$transportCurrentResolverSnapshot:
+ _objc_msgSend$transportStates
+ _objc_msgSend$tryingInitialCacheOnly
+ _objc_msgSend$txPacketCount
+ _objc_msgSend$txPacketErrorCount
+ _objc_msgSend$txPowerLevel
+ _objc_msgSend$unspecifiedBootCount
+ _objc_msgSend$updateCachedAddressesForDeviceID:cachedPrimary:cachedSecondary:
+ _objc_msgSend$updateServiceName:
+ _objc_msgSend$uploadWithoutResidentResponseCount
+ _objc_msgSend$wiFiPingTestCount
+ _objc_msgSend$wiFiPingTestInterval
+ _objc_msgSend$wiFiRecoveryConfiguration
+ _objc_msgSend$wiFiRestartMinInterval
+ _objc_msgSend$wifiFirstRestartCompleted
+ _objc_msgSend$wifiFirstRestartConnectivityState
+ _objc_msgSend$wifiFirstRestartRecoveryTime
+ _objc_msgSend$wifiRecoveryAttemptCount
+ _objc_msgSend$wifiRestartCount
+ _objc_msgSend$wifiTransportLossCount
+ _objc_msgSend$wifiVersion
+ _record_pending_message
+ _symbolic $s7CoreHAP39AccessoryMetricsDictionaryRepresentableP
+ _symbolic SS_So8NSObjectCt
+ _symbolic Si
+ _symbolic So11HMMLogEventC
+ _symbolic So7NSErrorCSg
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 7CoreHAP25CoAPRequestRacingLogEventC
+ _symbolic _____ 7CoreHAP27AccessoryCHMMetricsLogEventC
+ _symbolic _____ 7CoreHAP28AccessoryCHMRecoveryLogEventC
+ _symbolic _____ So21HAPAccessoryCHMSourceV
+ _symbolic _____ So27HAP2CoAPAccessoryTransportsV
+ _symbolic _____ So27HAP2CoAPRacingTriggerReasonV
+ _symbolic _____ So27HAPAccessoryCHMRecoveryKindV
+ _symbolic _____ So27HAPCHMWiFiConnectivityStateV
+ _symbolic _____ So29HAPCHMThreadConnectivityStateV
+ _symbolic _____ So30HAP2CoAPRacingWinningTransportV
+ _symbolic _____ySSSo8NSObjectCG s18_DictionaryStorageC
+ _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
+ logCategory._hmf_once_t8
+ logCategory._hmf_once_v9
- -[HAP2AccessoryServer(Paired) mergeWithNewlyDiscoveredPairedAccessoryServer:]
- -[HAP2CoAPClient sendRequestWithMethod:path:payload:dscpPriority:completion:]
- GCC_except_table1000
- GCC_except_table1116
- GCC_except_table1118
- GCC_except_table1224
- GCC_except_table1229
- GCC_except_table1247
- GCC_except_table1261
- GCC_except_table1263
- GCC_except_table1265
- GCC_except_table1267
- GCC_except_table1393
- GCC_except_table1399
- GCC_except_table1401
- GCC_except_table1603
- GCC_except_table1813
- GCC_except_table1815
- GCC_except_table1826
- GCC_except_table1828
- GCC_except_table1834
- GCC_except_table1836
- GCC_except_table1840
- GCC_except_table1846
- GCC_except_table1848
- GCC_except_table1850
- GCC_except_table1852
- GCC_except_table1858
- GCC_except_table1862
- GCC_except_table1872
- GCC_except_table1880
- GCC_except_table1887
- GCC_except_table1891
- GCC_except_table1895
- GCC_except_table1900
- GCC_except_table1938
- GCC_except_table2057
- GCC_except_table2062
- GCC_except_table2063
- GCC_except_table2065
- GCC_except_table2067
- GCC_except_table2079
- GCC_except_table2084
- GCC_except_table2088
- GCC_except_table2091
- GCC_except_table2093
- GCC_except_table2098
- GCC_except_table2115
- GCC_except_table2125
- GCC_except_table2127
- GCC_except_table2129
- GCC_except_table2134
- GCC_except_table2137
- GCC_except_table2139
- GCC_except_table2142
- GCC_except_table2145
- GCC_except_table2149
- GCC_except_table2151
- GCC_except_table2154
- GCC_except_table2159
- GCC_except_table2161
- GCC_except_table2163
- GCC_except_table2167
- GCC_except_table2173
- GCC_except_table2181
- GCC_except_table2194
- GCC_except_table2237
- GCC_except_table2238
- GCC_except_table2239
- GCC_except_table2241
- GCC_except_table2242
- GCC_except_table2243
- GCC_except_table2245
- GCC_except_table2249
- GCC_except_table2250
- GCC_except_table2276
- GCC_except_table2280
- GCC_except_table2284
- GCC_except_table237
- GCC_except_table247
- GCC_except_table248
- GCC_except_table2486
- GCC_except_table2494
- GCC_except_table2495
- GCC_except_table2496
- GCC_except_table2497
- GCC_except_table2498
- GCC_except_table2499
- GCC_except_table251
- GCC_except_table2515
- GCC_except_table2529
- GCC_except_table254
- GCC_except_table2609
- GCC_except_table2621
- GCC_except_table265
- GCC_except_table267
- GCC_except_table271
- GCC_except_table275
- GCC_except_table2825
- GCC_except_table284
- GCC_except_table2852
- GCC_except_table2886
- GCC_except_table290
- GCC_except_table2902
- GCC_except_table2904
- GCC_except_table2916
- GCC_except_table2923
- GCC_except_table2945
- GCC_except_table2959
- GCC_except_table2960
- GCC_except_table2961
- GCC_except_table2964
- GCC_except_table2973
- GCC_except_table2980
- GCC_except_table2983
- GCC_except_table2988
- GCC_except_table2993
- GCC_except_table2998
- GCC_except_table3039
- GCC_except_table3056
- GCC_except_table3059
- GCC_except_table3064
- GCC_except_table3066
- GCC_except_table3082
- GCC_except_table3098
- GCC_except_table3100
- GCC_except_table3112
- GCC_except_table3120
- GCC_except_table3184
- GCC_except_table3191
- GCC_except_table3193
- GCC_except_table3194
- GCC_except_table3217
- GCC_except_table3237
- GCC_except_table3465
- GCC_except_table3533
- GCC_except_table3538
- GCC_except_table3541
- GCC_except_table3543
- GCC_except_table3544
- GCC_except_table3551
- GCC_except_table3558
- GCC_except_table3568
- GCC_except_table3571
- GCC_except_table3583
- GCC_except_table3585
- GCC_except_table3590
- GCC_except_table3594
- GCC_except_table3596
- GCC_except_table3599
- GCC_except_table3602
- GCC_except_table3614
- GCC_except_table3616
- GCC_except_table3620
- GCC_except_table3624
- GCC_except_table3678
- GCC_except_table3684
- GCC_except_table3688
- GCC_except_table3692
- GCC_except_table3694
- GCC_except_table3697
- GCC_except_table3699
- GCC_except_table3708
- GCC_except_table3710
- GCC_except_table3716
- GCC_except_table3797
- GCC_except_table3798
- GCC_except_table3799
- GCC_except_table3800
- GCC_except_table3801
- GCC_except_table3802
- GCC_except_table3803
- GCC_except_table3804
- GCC_except_table3805
- GCC_except_table3807
- GCC_except_table3808
- GCC_except_table3809
- GCC_except_table3810
- GCC_except_table3811
- GCC_except_table3864
- GCC_except_table3969
- GCC_except_table3976
- GCC_except_table3991
- GCC_except_table3999
- GCC_except_table4010
- GCC_except_table4024
- GCC_except_table4027
- GCC_except_table4032
- GCC_except_table4040
- GCC_except_table4046
- GCC_except_table4048
- GCC_except_table4050
- GCC_except_table4060
- GCC_except_table4085
- GCC_except_table4091
- GCC_except_table4177
- GCC_except_table4183
- GCC_except_table4189
- GCC_except_table4192
- GCC_except_table4198
- GCC_except_table4201
- GCC_except_table4206
- GCC_except_table4228
- GCC_except_table4230
- GCC_except_table4244
- GCC_except_table4252
- GCC_except_table4259
- GCC_except_table4266
- GCC_except_table4269
- GCC_except_table4288
- GCC_except_table4290
- GCC_except_table4292
- GCC_except_table4293
- GCC_except_table4296
- GCC_except_table4305
- GCC_except_table4307
- GCC_except_table4313
- GCC_except_table4315
- GCC_except_table4317
- GCC_except_table4320
- GCC_except_table4342
- GCC_except_table4353
- GCC_except_table4645
- GCC_except_table4651
- GCC_except_table4668
- GCC_except_table4672
- GCC_except_table4690
- GCC_except_table4696
- GCC_except_table4710
- GCC_except_table4724
- GCC_except_table4728
- GCC_except_table5304
- GCC_except_table5313
- GCC_except_table5324
- GCC_except_table5366
- GCC_except_table5369
- GCC_except_table5370
- GCC_except_table5371
- GCC_except_table5372
- GCC_except_table5455
- GCC_except_table5456
- GCC_except_table5457
- GCC_except_table5458
- GCC_except_table5459
- GCC_except_table5460
- GCC_except_table5466
- GCC_except_table5467
- GCC_except_table5469
- GCC_except_table5476
- GCC_except_table5479
- GCC_except_table5481
- GCC_except_table5486
- GCC_except_table5489
- GCC_except_table5492
- GCC_except_table5496
- GCC_except_table5500
- GCC_except_table555
- GCC_except_table566
- GCC_except_table594
- GCC_except_table6049
- GCC_except_table6050
- GCC_except_table6069
- GCC_except_table6079
- GCC_except_table6082
- GCC_except_table6087
- GCC_except_table6090
- GCC_except_table6095
- GCC_except_table628
- GCC_except_table6364
- GCC_except_table6368
- GCC_except_table640
- GCC_except_table641
- GCC_except_table6417
- GCC_except_table6419
- GCC_except_table6421
- GCC_except_table643
- GCC_except_table646
- GCC_except_table649
- GCC_except_table663
- GCC_except_table6646
- GCC_except_table6653
- GCC_except_table6657
- GCC_except_table6658
- GCC_except_table6659
- GCC_except_table6660
- GCC_except_table6666
- GCC_except_table667
- GCC_except_table6682
- GCC_except_table671
- GCC_except_table6718
- GCC_except_table6719
- GCC_except_table6720
- GCC_except_table6740
- GCC_except_table6752
- GCC_except_table6755
- GCC_except_table6760
- GCC_except_table6762
- GCC_except_table6776
- GCC_except_table678
- GCC_except_table681
- GCC_except_table7011
- GCC_except_table7024
- GCC_except_table7029
- GCC_except_table7032
- GCC_except_table7033
- GCC_except_table7035
- GCC_except_table7036
- GCC_except_table7038
- GCC_except_table7068
- GCC_except_table7092
- GCC_except_table7096
- GCC_except_table7100
- GCC_except_table7105
- GCC_except_table7109
- GCC_except_table7113
- GCC_except_table7117
- GCC_except_table7121
- GCC_except_table7129
- GCC_except_table7131
- GCC_except_table7135
- GCC_except_table715
- GCC_except_table7199
- GCC_except_table7200
- GCC_except_table7201
- GCC_except_table7202
- GCC_except_table7203
- GCC_except_table7204
- GCC_except_table7205
- GCC_except_table725
- GCC_except_table7269
- GCC_except_table7276
- GCC_except_table7277
- GCC_except_table7293
- GCC_except_table7294
- GCC_except_table7295
- GCC_except_table7305
- GCC_except_table7311
- GCC_except_table7325
- GCC_except_table7328
- GCC_except_table7329
- GCC_except_table733
- GCC_except_table7334
- GCC_except_table7337
- GCC_except_table7344
- GCC_except_table7347
- GCC_except_table7361
- GCC_except_table7374
- GCC_except_table7383
- GCC_except_table7385
- GCC_except_table7391
- GCC_except_table7392
- GCC_except_table7399
- GCC_except_table7423
- GCC_except_table7424
- GCC_except_table7429
- GCC_except_table7433
- GCC_except_table7434
- GCC_except_table7437
- GCC_except_table7443
- GCC_except_table7447
- GCC_except_table7451
- GCC_except_table7453
- GCC_except_table7455
- GCC_except_table7459
- GCC_except_table7573
- GCC_except_table760
- GCC_except_table7610
- GCC_except_table764
- GCC_except_table7667
- GCC_except_table767
- GCC_except_table7670
- GCC_except_table7683
- GCC_except_table769
- GCC_except_table7690
- GCC_except_table7691
- GCC_except_table7707
- GCC_except_table7711
- GCC_except_table7712
- GCC_except_table7713
- GCC_except_table7762
- GCC_except_table7763
- GCC_except_table7765
- GCC_except_table7768
- GCC_except_table7795
- GCC_except_table7796
- GCC_except_table7801
- GCC_except_table781
- GCC_except_table7821
- GCC_except_table7839
- GCC_except_table7840
- GCC_except_table7841
- GCC_except_table7850
- GCC_except_table7855
- GCC_except_table7856
- GCC_except_table7857
- GCC_except_table7873
- GCC_except_table7876
- GCC_except_table7883
- GCC_except_table7890
- GCC_except_table7895
- GCC_except_table7901
- GCC_except_table7913
- GCC_except_table7914
- GCC_except_table7919
- GCC_except_table7928
- GCC_except_table7936
- GCC_except_table7937
- GCC_except_table7941
- GCC_except_table7943
- GCC_except_table7945
- GCC_except_table7949
- GCC_except_table7970
- GCC_except_table7972
- GCC_except_table7973
- GCC_except_table7999
- GCC_except_table802
- GCC_except_table808
- GCC_except_table812
- GCC_except_table8227
- GCC_except_table823
- GCC_except_table8259
- GCC_except_table8262
- GCC_except_table829
- GCC_except_table832
- GCC_except_table835
- GCC_except_table8429
- GCC_except_table844
- GCC_except_table8467
- GCC_except_table850
- GCC_except_table8504
- GCC_except_table854
- GCC_except_table855
- GCC_except_table8584
- GCC_except_table8586
- GCC_except_table8590
- GCC_except_table8594
- GCC_except_table8602
- GCC_except_table8605
- GCC_except_table8607
- GCC_except_table8609
- GCC_except_table8618
- GCC_except_table8624
- GCC_except_table8629
- GCC_except_table8632
- GCC_except_table8637
- GCC_except_table8642
- GCC_except_table8645
- GCC_except_table8648
- GCC_except_table8674
- GCC_except_table8677
- GCC_except_table8678
- GCC_except_table8697
- GCC_except_table8698
- GCC_except_table8699
- GCC_except_table8701
- GCC_except_table8702
- GCC_except_table8704
- GCC_except_table8705
- GCC_except_table8706
- GCC_except_table8708
- GCC_except_table8709
- GCC_except_table8711
- GCC_except_table8715
- GCC_except_table8716
- GCC_except_table8720
- GCC_except_table8771
- GCC_except_table8778
- GCC_except_table883
- GCC_except_table8884
- GCC_except_table8886
- GCC_except_table8888
- GCC_except_table8891
- GCC_except_table8893
- GCC_except_table8895
- GCC_except_table8897
- GCC_except_table8898
- GCC_except_table890
- GCC_except_table8905
- GCC_except_table8907
- GCC_except_table8908
- GCC_except_table898
- GCC_except_table937
- GCC_except_table955
- GCC_except_table977
- GCC_except_table981
- GCC_except_table995
- __51-[HAP2AccessoryServerTransportCoAP _resolveAddress]_block_invoke_2
- __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServer(Paired|PairedInternal|Unpaired)
- __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServerBrowser
- __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServerCoordinator
- __OBJC_CLASS_PROTOCOLS_$_HAP2AccessoryServer(Paired|PairedInternal|Unpaired)
- ___77-[HAP2AccessoryServer(Paired) mergeWithNewlyDiscoveredPairedAccessoryServer:]_block_invoke
- ___77-[HAP2CoAPClient sendRequestWithMethod:path:payload:dscpPriority:completion:]_block_invoke
- ___77-[HAP2CoAPClient sendRequestWithMethod:path:payload:dscpPriority:completion:]_block_invoke_2
- ___87-[HAP2CoAPClient _sendRequestWithMethod:path:payload:activity:dscpPriority:completion:]_block_invoke
- ___87-[HAP2CoAPClient _sendRequestWithMethod:path:payload:activity:dscpPriority:completion:]_block_invoke_2
- ___block_descriptor_48_e693_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}Ii}16l
- ___block_descriptor_48_e8_32bs40w_e839_v24?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}Ii}16l
- ___block_descriptor_64_e8_32s40s48bs56w_e20_v20?0B8"NSError"12l
- ___block_descriptor_69_e8_32s40s48s_e693_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}Ii}16l
- ___block_descriptor_81_e8_32s40s48s56s64bs_e5_v8?0l
- _objc_msgSend$mergeWithNewlyDiscoveredPairedAccessoryServer:
- _objc_msgSend$sendRequestWithMethod:path:payload:dscpPriority:completion:
CStrings:
+ "\v"
+ "\r"
+ " (Thread-only)"
+ "!Aq\x81"
+ "%@ '%{private}@' Connecting via secondary (Thread) transport"
+ "%@ - close with nothing to close: state change completion already handled"
+ "%@ Close with no client to close; completing the transition"
+ "%@ Failed to send hello: %@, retry count: %lu"
+ "%@ HDS-over-TCP peer selected: %s from %s (%{private}@)"
+ "%@ HDS-over-TCP peer unavailable (coapClient=%p, secondaryCoAPClient=%p)"
+ "%@ Hello deferred: registration not complete"
+ "%@ Hello deferred: secondary client not connected"
+ "%@ Hello sent successfully from secondary transport"
+ "%@ Hello skipped: secondary client is nil"
+ "%@ Max hello retries reached, giving up"
+ "%@ NLM Probe: Client for transport %lu not connected, closing and refreshing"
+ "%@ NLM Probe: No CoAP client for transport %lu, refreshing"
+ "%@ NLM Probe: Sending Empty CON probe on transport %lu"
+ "%@ NLM-APPLY hop1 controller: DROPPED, self.transport is nil"
+ "%@ NLM-APPLY hop1 controller: entry"
+ "%@ NLM-APPLY hop1 controller: forwarding to %@"
+ "%@ NLM-APPLY hop2 secure: DROPPED, underlying %@ does not respond to applyResolverAddresses:completion:"
+ "%@ NLM-APPLY hop2 secure: forwarding to underlying %@"
+ "%@ NLM-APPLY hop3 coap: DROPPED, NLM feature not enabled"
+ "%@ NLM-APPLY hop3 coap: entry primary=%lu secondary=%lu, enqueueing onto transport queue"
+ "%@ NLM: Cannot probe, no transport"
+ "%@ NLM: Cannot read local endpoints, no transport"
+ "%@ NLM: Re-advertisement while unreachable, triggering reconnection"
+ "%@ NLM: Session keep-alive %@; connected-only notify %@"
+ "%@ NLM: s# changed %u -> %u while Unreachable — full refresh"
+ "%@ Resolve completed in state %lu (not Opening), ignoring"
+ "%@ Sending hello from secondary transport"
+ "%@.registry"
+ "%@.registry.propertyLock"
+ "(nil)"
+ "(null)"
+ "00000274-0000-1000-8000-0026BB765291"
+ "00000275-0000-1000-8000-0026BB765291"
+ "3"
+ "<%@: %p primary=%lu secondary=%lu cachedPrimary=%@ cachedSecondary=%@>"
+ "<%s, %@>"
+ "<HAPBluetoothMetrics bluetoothVersion=%@, rssi=%@, txPowerLevel=%@, packetRxCount=%@, packetTxCount=%@, packetRxErrorCount=%@, packetTxErrorCount=%@, overrunCount=%@, connectionStatus=%@, connectionCount=%@, connectionErrorCount=%@, disconnectionCount=%@, disconnectionErrorCount=%@, hwExceptionCount=%@>"
+ "<HAPBootReasonsMetrics unspecifiedBootCount=%@, powerOnBootCount=%@, brownOutResetBootCount=%@, softwareWatchdogResetBootCount=%@, hardwareWatchdogResetBootCount=%@, softwareUpdateCompletedBootCount=%@, softwareResetBootCount=%@, softwareExceptionBootCount=%@, hardwareFaultBootCount=%@, stackOverflowBootCount=%@, heapOverflowBootCount=%@, temperatureLimitBootCount=%@, connectivityMonitorBootCount=%@>"
+ "<HAPCHMMetrics wifiTransportLossCount=%@, wifiRecoveryAttemptCount=%@, wifiRestartCount=%@, wifiFirstRestartRecoveryTime=%@, wifiFirstRestartCompleted=%@, wifiFirstRestartConnectivityState=%@, threadTransportLossCount=%@, threadRecoveryAttemptCount=%@, threadRestartCount=%@, threadFirstRestartRecoveryTime=%@, threadFirstRestartCompleted=%@, threadFirstRestartConnectivityState=%@, hapSessionLossCount=%@, chmAccessoryRebootDurationToRecovery=%@, chmAccessoryRebootCompleted=%@>"
+ "<HAPConnectionHealthMonitor deviceRebootEnable=%@, threadRecoveryConfiguration=%@, wiFiRecoveryConfiguration=%@, recoveryStaggerDelay=%@, deviceRebootDelay=%@, threadPingTestCount=%@, threadPingTestInterval=%@, threadRestartMinInterval=%@, wiFiPingTestCount=%@, wiFiPingTestInterval=%@, wiFiRestartMinInterval=%@>"
+ "<HAPErrorCountersMetrics entries=%@>"
+ "<HAPErrorCountersMetricsEntry errorID=%@, count=%@>"
+ "<HAPHKSV3UploadLatencyMetrics fragmentSuccessCount=%@, fragmentFailureCount=%@, fragmentRetriedCount=%@, networkErrorCount=%@, authenticationErrorCount=%@, serverReturnedErrorCount=%@, localErrorCount=%@, playlistFailureCount=%@, latencyCount250ms=%@, latencyCount500ms=%@, latencyCount1000ms=%@, latencyCount2000ms=%@, latencyCount3750ms=%@, latencyCountOver3750ms=%@, sessionSuccessCount=%@, partialSuccessCount=%@, sessionFailureCount=%@, uploadWithoutResidentResponseCount=%@, audioOnlyFailureCount=%@, abandonedRequestCount=%@>"
+ "<HAPMetricEventBluetoothVersionTypeWrapper value=%@>"
+ "<HAPMetricEventPowerSourcesBitmaskWrapper value=%@>"
+ "<HAPMetricEventPowerSourcesEnumWrapper value=%@>"
+ "<HAPMetricEventThreadFirstRestartConnectivityStateWrapper value=%@>"
+ "<HAPMetricEventWiFiFirstRestartConnectivityStateWrapper value=%@>"
+ "<HAPMetricEventWiFiVersionTypeWrapper value=%@>"
+ "<HAPPowerMetrics supportedPowerSources=%@, currentPowerSource=%@, durationOnBatteryPower=%@, durationRemainingOnBatteryPower=%@, batteryPercentage=%@>"
+ "<HAPSaturationMetrics stackHighwaterCount=%@, lastStackHighwaterTaskName=%@, heapHighwaterCount=%@, lastHeapHighwaterTaskName=%@, stackOverflowCount=%@, lastStackOverflowTaskName=%@, heapOverflowCount=%@, lastHeapOverflowTaskName=%@, averageSystemMemoryUtilization=%@, peakSystemMemoryUtilization=%@, systemMemoryPressureCount=%@, processCriticalMemoryCount=%@, lastProcessCriticalMemoryName=%@, averageCPUUtilization=%@, peakCPUUtilization=%@, taskDeadlineMissCount=%@, totalTasksScheduledCount=%@, maxTaskReadyQueueSize=%@, loadAverage=%@, nonVolatileMemoryWriteCount=%@, nonVolatileMemoryReadCount=%@, nonVolatileMemoryWriteErrorCount=%@, nonVolatileMemoryReadErrorCount=%@, nonVolatileMemoryUtilization=%@>"
+ "<HAPSessionKeepAliveTransportTypeWrapper value=%@>"
+ "<HAPStabilityMetrics systemUptime=%@, systemBootCount=%@, expectedBootCount=%@, systemCrashCount=%@, systemHangCount=%@, lastBootReason=%@, activeHardwareFaults=%@>"
+ "<HAPStabilityMetricsBootReasonTypeWrapper value=%@>"
+ "<HAPStabilityMetricsHardwareFaultTypeWrapper value=%@>"
+ "<HAPTLVPreferredWiFiEntry SSID=%@, securityMode=%@, PSK=%@>"
+ "<HAPTLVPreferredWiFiList preferredWiFiList=%@>"
+ "<HAPTLVSelectedSessionKeepAliveConfigurationEntry transportType=%@, minimumInterval=%@, maximumInterval=%@>"
+ "<HAPTLVSelectedSessionKeepAliveConfigurationList entries=%@>"
+ "<HAPTLVSupportedSessionKeepAliveConfigurationEntry transportType=%@, minimumInterval=%@, maximumInterval=%@, minimumRange=%@>"
+ "<HAPTLVSupportedSessionKeepAliveConfigurationList entries=%@>"
+ "<HAPThermalMetrics temperatureLimitViolationCount=%@, temperatureLimitViolationDuration=%@, minimumDeviceTemperature=%@, maximumDeviceTemperature=%@, averageDeviceTemperature=%@>"
+ "<HAPWiFiMetrics gatewayMacAddress=%@, gatewayIPv4Address=%@, gatewayIPv6Address=%@, subnetMask=%@, bssid=%@, wifiVersion=%@, channelNumber=%@, rssi=%@, connectionStatus=%@, disconnectionCount=%@, disconnectionDuration=%@, beaconRxCount=%@, beaconRxInterval=%@, beaconLostCount=%@, ipAddressList=%@, packetMulticastRxCount=%@, packetMulticastRxErrorCount=%@, packetMulticastTxCount=%@, packetMulticastTxErrorCount=%@, packetUnicastRxCount=%@, packetUnicastRxErrorCount=%@, packetUnicastTxCount=%@, packetUnicastTxErrorCount=%@, txPacketCount=%@, txPacketErrorCount=%@, rxPacketCount=%@, rxPacketErrorCount=%@, hwExceptionCount=%@, wifiRestartCount=%@>"
+ "@\"HAP2AccessoryServerIPCacheData\"16@?0@\"HAP2AccessoryServerIPCacheData\"8"
+ "ASSERTION: NLM: %@ Refresh primary bring-up called with live coapClient — skipping to avoid leak"
+ "ASSERTION: NLM: %@ Refresh secondary bring-up called with live secondaryCoAPClient — skipping to avoid leak"
+ "Address %@ does not match any local interface, assuming Thread"
+ "Address %@ matches interface %@ (Thread: %@)"
+ "All addresses already tried"
+ "All transports missed heartbeat"
+ "Attempting to derive HDS keys without an active session"
+ "Audit reap: evicted cache entry deviceID=%{public}@"
+ "Cache init TXT-parse failed deviceID=%{public}@"
+ "Cache init skip deviceID=%{public}@ isPaired=%d error.code=%ld"
+ "Cache init skip — no serviceName deviceID=%{public}@"
+ "Cache init: no cached records to restore"
+ "Cache init: re-running for %lu cached records after coordinators started"
+ "Cache init: restoring %lu cached accessory servers"
+ "Config UPDATE no-op (unchanged) deviceID=%{public}@"
+ "Config UPDATE persisted deviceID=%{public}@"
+ "Coordinator: dropping discovery for deviceID=%{public}@ — mDNS announcement has no service name; accessory is unreachable until it fixes its advertisement"
+ "CoreHAP"
+ "CoreHAP.AccessoryCHMMetricsLogEvent"
+ "CoreHAP.AccessoryCHMRecoveryLogEvent"
+ "Created shared CtrClient for CoreHAP"
+ "DNS context already retained"
+ "DNS-SD resolve callback delivered fatal error"
+ "DNS-SD resolver delivered fatal error event"
+ "Failed to create shared CtrClient instance"
+ "Failed to derive HDS keys from foreign pair-verify session: %@"
+ "Failed to start address resolver"
+ "Foreign pair-verify HDS key derivation failed"
+ "HAP2 adapter deallocated before HDS key derivation"
+ "HAP2 secure transport deallocated before HDS key derivation"
+ "HAP2 secure transport unavailable for HDS key derivation"
+ "HAP2 security session unavailable for HDS key derivation"
+ "HAP2AccessoryServerIPCache"
+ "HAP2AccessoryServerTest_reactiveWorkRecorder"
+ "HAP2CoAPClient"
+ "HAP2CoAPClient has no registered IO consumer or session"
+ "HAP2IPCache"
+ "HAP2ThreadNetworkUtil: force-refresh confirmed cached prefix"
+ "HAP2ThreadNetworkUtil: force-refresh detected missed event — cached=%{private}@ fresh=%{private}@ (event subscription drift)"
+ "HAP2ThreadNetworkUtil: invalidating cached mesh-local prefix on event %s"
+ "HAP2ThreadNetworkUtil: registered wpantund event subscriptions"
+ "HAPInternalErrorMarker"
+ "HAPMetricEventBluetoothVersionType4_0"
+ "HAPMetricEventBluetoothVersionType4_1"
+ "HAPMetricEventBluetoothVersionType4_2"
+ "HAPMetricEventBluetoothVersionType5_0"
+ "HAPMetricEventBluetoothVersionType5_1"
+ "HAPMetricEventBluetoothVersionType5_2"
+ "HAPMetricEventBluetoothVersionType5_3"
+ "HAPMetricEventBluetoothVersionType5_4"
+ "HAPMetricEventBluetoothVersionType6_0"
+ "HAPMetricEventBluetoothVersionTypeUnknown"
+ "HAPMetricEventPowerSourcesBitmaskRechargableBattery"
+ "HAPMetricEventPowerSourcesBitmaskReplaceableBattery"
+ "HAPMetricEventPowerSourcesBitmaskUnspecified"
+ "HAPMetricEventPowerSourcesBitmaskWired"
+ "HAPMetricEventPowerSourcesEnumRechargableBattery"
+ "HAPMetricEventPowerSourcesEnumReplaceableBattery"
+ "HAPMetricEventPowerSourcesEnumUnspecified"
+ "HAPMetricEventPowerSourcesEnumWired"
+ "HAPMetricEventThreadFirstRestartConnectivityStateBorderRouter"
+ "HAPMetricEventThreadFirstRestartConnectivityStateLeader"
+ "HAPMetricEventThreadFirstRestartConnectivityStateNeighbor"
+ "HAPMetricEventThreadFirstRestartConnectivityStateParent"
+ "HAPMetricEventThreadFirstRestartConnectivityStateResident"
+ "HAPMetricEventWiFiFirstRestartConnectivityStateGateway"
+ "HAPMetricEventWiFiFirstRestartConnectivityStateResident"
+ "HAPMetricEventWiFiVersionType802_11a"
+ "HAPMetricEventWiFiVersionType802_11ac"
+ "HAPMetricEventWiFiVersionType802_11ah"
+ "HAPMetricEventWiFiVersionType802_11ax"
+ "HAPMetricEventWiFiVersionType802_11b"
+ "HAPMetricEventWiFiVersionType802_11g"
+ "HAPMetricEventWiFiVersionType802_11n"
+ "HAPMetricEventWiFiVersionTypeUnknown"
+ "HAPSecuritySession._pairingSession nil during deriveEncryptionForDataStream"
+ "HAPSessionKeepAliveTransportTypeEthernet"
+ "HAPSessionKeepAliveTransportTypeThread"
+ "HAPSessionKeepAliveTransportTypeWiFi"
+ "HAPStabilityMetricsBootReasonTypeBrownOutReset"
+ "HAPStabilityMetricsBootReasonTypeConnectivityMonitorReset"
+ "HAPStabilityMetricsBootReasonTypeHardwareFault"
+ "HAPStabilityMetricsBootReasonTypeHardwareWatchdogReset"
+ "HAPStabilityMetricsBootReasonTypeHeapOverflow"
+ "HAPStabilityMetricsBootReasonTypePowerOnReboot"
+ "HAPStabilityMetricsBootReasonTypeSoftwareException"
+ "HAPStabilityMetricsBootReasonTypeSoftwareReset"
+ "HAPStabilityMetricsBootReasonTypeSoftwareUpdateCompleted"
+ "HAPStabilityMetricsBootReasonTypeSoftwareWatchdogReset"
+ "HAPStabilityMetricsBootReasonTypeStackOverflow"
+ "HAPStabilityMetricsBootReasonTypeTemperatureLimit"
+ "HAPStabilityMetricsBootReasonTypeUnspecified"
+ "HAPStabilityMetricsHardwareFaultTypeAudioInputFault"
+ "HAPStabilityMetricsHardwareFaultTypeAudioOutputFault"
+ "HAPStabilityMetricsHardwareFaultTypeNetworkInterfaceFault"
+ "HAPStabilityMetricsHardwareFaultTypeNonResettableOverTemp"
+ "HAPStabilityMetricsHardwareFaultTypeNonVolatileMemoryError"
+ "HAPStabilityMetricsHardwareFaultTypePowerSource"
+ "HAPStabilityMetricsHardwareFaultTypeRadio"
+ "HAPStabilityMetricsHardwareFaultTypeRegisterException"
+ "HAPStabilityMetricsHardwareFaultTypeResettableOverTemp"
+ "HAPStabilityMetricsHardwareFaultTypeSensor"
+ "HAPStabilityMetricsHardwareFaultTypeTamperDetected"
+ "HAPStabilityMetricsHardwareFaultTypeUnspecified"
+ "HAPStabilityMetricsHardwareFaultTypeUserInterfaceFault"
+ "HAPStabilityMetricsHardwareFaultTypeVisualDisplayFault"
+ "HDS key derivation failed (pairedServer=%p controller=%p secureTransport=%p)"
+ "HDS key derivation failed: no security session on HAP2 secure transport"
+ "HDS peer address unavailable (pairedServer=%p controller=%p secureTransport=%p coapTransport=%p)"
+ "IPv4"
+ "IPv6"
+ "Invalid cachedPrimaryData type for device %{public}@"
+ "Invalid cachedSecondaryData type for device %{public}@"
+ "Invalid or missing configurationInfo for device %{public}@"
+ "KeepAlive"
+ "Live resolver completed with empty endpoint set"
+ "Local endpoint is neither AF_INET nor AF_INET6"
+ "Local endpoint is not IPv4"
+ "Local endpoint is not IPv6"
+ "NCP:State"
+ "NLM keep-alive listener active, skipping reachability client"
+ "NLM-APPLY hop3 coap: DROPPED, transport deallocated before the queued block ran"
+ "NLM: %@ '%{private}@'   [%lu] IPv4: %s (port: %d, %@)"
+ "NLM: %@ '%{private}@'   [%lu] IPv6: %s (port: %d, %@)"
+ "NLM: %@ '%{private}@'   [%lu] Unknown address family: %d"
+ "NLM: %@ '%{private}@' Connecting via primary transport"
+ "NLM: %@ '%{private}@' Discovered primary address: %@"
+ "NLM: %@ '%{private}@' Discovered secondary (Thread) address: %@"
+ "NLM: %@ '%{private}@' Duplicate IP address in secondary list - skipping"
+ "NLM: %@ '%{private}@' Initial resolver complete with addresses present but all already tried — unable to connect"
+ "NLM: %@ '%{private}@' Initial resolver complete; connecting via primary transport"
+ "NLM: %@ '%{private}@' Initial resolver complete; connecting via secondary (Thread) transport"
+ "NLM: %@ '%{private}@' Primary addresses:"
+ "NLM: %@ '%{private}@' Primary addresses: %lu, Secondary (Thread) addresses: %lu"
+ "NLM: %@ '%{private}@' Resolver pipeline died; scheduled restart in %.1fs"
+ "NLM: %@ '%{private}@' Resolver pipeline failed: %@"
+ "NLM: %@ '%{private}@' Resolver restart timer fired in state %lu (not Open/Opening), ignoring"
+ "NLM: %@ '%{private}@' Resolver restart timer fired; re-arming pipeline"
+ "NLM: %@ '%{private}@' Resolver snapshot empty on open; awaiting live update with resolve-timeout backstop"
+ "NLM: %@ '%{private}@' Resolver snapshot empty on open; falling back to %lu mirrored address(es)"
+ "NLM: %@ '%{private}@' Resolver timed out after %.1fs without first usable update"
+ "NLM: %@ '%{private}@' Resolver update primary=%lu secondary=%lu"
+ "NLM: %@ '%{private}@' Secondary (Thread) addresses:"
+ "NLM: %@ '%{private}@' Seeding open from pulled resolver snapshot (primary=%lu secondary=%lu)"
+ "NLM: %@ '%{private}@' Skipping IPv6 for primary (IPv4-only policy): %@"
+ "NLM: %@ '%{private}@' Started resolver"
+ "NLM: %@ '%{private}@' resolved %lu IP address(es) - Primary: %lu, Secondary: %lu"
+ "NLM: %@ - close (primary): state change completion has already been handled"
+ "NLM: %@ - close (single): state change completion has already been handled"
+ "NLM: %@ - finalize request: completion has already been handled"
+ "NLM: %@ - open (WiFi+Thread): state change completion has already been handled"
+ "NLM: %@ Accessory does not support full NLM (WiFi:%{BOOL}d Thread:%{BOOL}d KeepAlive:%{BOOL}d), skipping registration"
+ "NLM: %@ All interfaces: %@"
+ "NLM: %@ Cache-miss cancel close returned: code=%ld domain=%{public}@"
+ "NLM: %@ Cache-miss cancel-and-restart: clearing latch, resetting tried-set, canceling in-flight primary open"
+ "NLM: %@ Cache-miss grace expired; executing cancel"
+ "NLM: %@ Cache-miss grace timer fired but latch already clear; no-op"
+ "NLM: %@ Cancelled resolver"
+ "NLM: %@ Client to register not yet connected, deferring endpoint registration"
+ "NLM: %@ Close of exhausted primary client returned: %@"
+ "NLM: %@ Close of failed PV client returned: %@"
+ "NLM: %@ Close of failed primary client returned: %@"
+ "NLM: %@ Close of failed secondary client returned: %@"
+ "NLM: %@ Closed"
+ "NLM: %@ Closed%@"
+ "NLM: %@ Closing client while an open is in flight (primary=%d secondary=%d)"
+ "NLM: %@ Closing primary client"
+ "NLM: %@ Closing secondary client first"
+ "NLM: %@ Connected address for transport %lu is no longer advertised; %lu resolver address(es) available"
+ "NLM: %@ Created Thread client during refresh, opening..."
+ "NLM: %@ Created WiFi client during refresh, opening..."
+ "NLM: %@ Created secondary CoAP client for Thread address: %{private}s"
+ "NLM: %@ Creating secondary client alongside primary, %lu secondary addresses available"
+ "NLM: %@ Effective address selection fell back to cache (primary=%{BOOL}d secondary=%{BOOL}d)"
+ "NLM: %@ Endpoint already registered, skipping"
+ "NLM: %@ Executing deferred endpoint registration"
+ "NLM: %@ Failed to close dead primary client: %@"
+ "NLM: %@ Failed to close dead probe client: %@"
+ "NLM: %@ Failed to close dead secondary client: %@"
+ "NLM: %@ Failed to close secondary: %@"
+ "NLM: %@ Failed to close%@: %@"
+ "NLM: %@ Failed to close: %@"
+ "NLM: %@ Failed to get WiFi local endpoint: %@"
+ "NLM: %@ Failed to get secondary local endpoint: %@"
+ "NLM: %@ Failed to map WiFi IPv4 endpoint to IPv4-mapped IPv6"
+ "NLM: %@ Failed to open Thread client during refresh: %@"
+ "NLM: %@ Failed to open WiFi client during refresh: %@"
+ "NLM: %@ Failed to open primary client: %@"
+ "NLM: %@ Failed to open secondary client: %@"
+ "NLM: %@ Failed to register WiFi endpoint: %@"
+ "NLM: %@ Failed to register endpoint: %@"
+ "NLM: %@ Failed to start address resolver"
+ "NLM: %@ Initial primary list is cache-only; arming stopgap latch at connect start"
+ "NLM: %@ Initial resolver complete in state %lu (not Opening), ignoring"
+ "NLM: %@ Last client disconnected, tearing down transport"
+ "NLM: %@ Live primary IPs arrived off-queue while cache-only latch armed; arming grace timer to evaluate the cancel"
+ "NLM: %@ Live primary arrived %.3fs into cache-only attempt (>1s); canceling immediately"
+ "NLM: %@ Live primary arrived %.3fs into cache-only attempt; arming %.3fs grace timer"
+ "NLM: %@ Live update: bringing up missing primary client"
+ "NLM: %@ Live update: bringing up missing secondary client"
+ "NLM: %@ Local IPv4: %s:%u"
+ "NLM: %@ Local IPv6: [%s]:%u"
+ "NLM: %@ Lost advertisement — clearing WiFi/Thread flags"
+ "NLM: %@ Message %u - Dropping stale Thread response (WiFi already won)"
+ "NLM: %@ Message %u - Dropping stale WiFi response (Thread already won)"
+ "NLM: %@ Message %u - Rcvd via Thread (Received response in %.0fms)"
+ "NLM: %@ Message %u - Rcvd via Wi-Fi (Received response in %.0fms)"
+ "NLM: %@ Message %u - Rcvd via Wi-Fi (Received response in %.0fms, updating EstimatedRTT to %.0fms)"
+ "NLM: %@ Message %u - Send via Thread (No response from Wi-Fi, sending over Thread)"
+ "NLM: %@ Message %u - Send via Wi-Fi (Fallback timeout: %.0fms)"
+ "NLM: %@ Message %u - Thread failed (code %ld), Wi-Fi still outstanding"
+ "NLM: %@ Message %u - Thread failed after %.0fms (code %ld)"
+ "NLM: %@ Message %u - Thread failed late (code %ld), WiFi won"
+ "NLM: %@ Message %u - Wi-Fi error, racing over Thread"
+ "NLM: %@ Message %u - Wi-Fi failed (code %ld), Thread still outstanding"
+ "NLM: %@ Message %u - Wi-Fi failed after %.0fms (code %ld)"
+ "NLM: %@ Message %u - Wi-Fi failed late (code %ld), Thread won"
+ "NLM: %@ No WiFi client to register"
+ "NLM: %@ No delegate to publish advertisement state — wifi=%{BOOL}d thread=%{BOOL}d"
+ "NLM: %@ No secured client available for endpoint registration"
+ "NLM: %@ No secured client for WiFi registration"
+ "NLM: %@ No untried secondary addresses available, skipping secondary client creation"
+ "NLM: %@ Now closing primary client"
+ "NLM: %@ Now opening Thread client"
+ "NLM: %@ Only one transport available (WiFi:%@, Thread:%@), skipping registration"
+ "NLM: %@ Open Client after Resolve"
+ "NLM: %@ Opened (WiFi:%@, Thread:%@)"
+ "NLM: %@ Opening WiFi client first, then Thread"
+ "NLM: %@ Opening primary client"
+ "NLM: %@ Pair-verify complete, secured client: %@"
+ "NLM: %@ Pair-verify was Thread, registering WiFi endpoint"
+ "NLM: %@ Pair-verify was WiFi, registering Thread endpoint"
+ "NLM: %@ Primary CoAP client already exists, skipping creation"
+ "NLM: %@ Primary IPs exhausted; no more to try"
+ "NLM: %@ Primary client disconnected (error: %@), continuing with Secondary-only"
+ "NLM: %@ Primary client opened"
+ "NLM: %@ Publishing advertisement state — wifi=%{BOOL}d thread=%{BOOL}d"
+ "NLM: %@ RTT tracking enabled on session"
+ "NLM: %@ Refresh resolved primary address: %{private}s"
+ "NLM: %@ Refresh resolved secondary address: %{private}s"
+ "NLM: %@ Refresh: found Thread address, creating client"
+ "NLM: %@ Refresh: found WiFi address, creating client"
+ "NLM: %@ Refresh: have Thread address, creating client"
+ "NLM: %@ Refresh: have WiFi address, creating client"
+ "NLM: %@ Refresh: primary IPs exhausted; no more to try"
+ "NLM: %@ Refresh: secondary IPs exhausted; no more to try"
+ "NLM: %@ Refresh: trying next primary IP after open failure"
+ "NLM: %@ Refresh: trying next secondary IP after open failure"
+ "NLM: %@ Registering WiFi endpoint via secured Thread client"
+ "NLM: %@ Registering secondary endpoint [%02x%02x:...:%02x%02x]:%u (%zu bytes)"
+ "NLM: %@ Request failed: %@"
+ "NLM: %@ Requesting discovery reconfirm after ICMP port unreachable"
+ "NLM: %@ Requesting discovery reconfirm after failing to open"
+ "NLM: %@ Resolve completed in state %lu (not Opening), ignoring stale resolve"
+ "NLM: %@ Resolve discovered 0 addresses in state %lu (not Opening), ignoring"
+ "NLM: %@ Resolved '%{private}@' but can't print the address..."
+ "NLM: %@ Resolved '%{private}@' to %{private}s (%s, discovered %lu, tried %lu)"
+ "NLM: %@ Secondary CoAP client already exists, skipping creation"
+ "NLM: %@ Secondary IPs exhausted; no more to try"
+ "NLM: %@ Secondary client closed"
+ "NLM: %@ Secondary client disconnected (error: %@), continuing with Primary-only"
+ "NLM: %@ Secondary client opened"
+ "NLM: %@ Secured client (primary) disconnected, transferring to secondary"
+ "NLM: %@ Secured client (secondary) disconnected, transferring to primary"
+ "NLM: %@ Sending endpoint registration via secured client: %@"
+ "NLM: %@ Sending via primary only (secondary not registered) [MID:%u]"
+ "NLM: %@ Successfully registered WiFi endpoint, racing enabled!"
+ "NLM: %@ Successfully registered secondary endpoint"
+ "NLM: %@ Thread client opened during refresh"
+ "NLM: %@ Thread-only connection: creating secondary client only, coapClient will be nil"
+ "NLM: %@ Thread-only mode: closing secondary client"
+ "NLM: %@ Thread-only mode: opening secondary client"
+ "NLM: %@ Thread-only mode: sending request via secondary client [MID:%u]"
+ "NLM: %@ Transport capabilities - WiFi:%@ Thread:%@ KeepAlive:%@"
+ "NLM: %@ Trying next primary IP after open failure"
+ "NLM: %@ Trying next secondary IP after open failure"
+ "NLM: %@ WiFi client opened, registering via secured Thread..."
+ "NLM: %@ _refreshIPAddresses - already have both clients, skipping"
+ "NLM: %@ _refreshIPAddresses - both clients alive, skipping"
+ "NLM: %@ _refreshIPAddresses - bringing up missing clients (needsPrimary=%d, needsSecondary=%d)"
+ "NLM: %@ _refreshIPAddresses - request in flight, deferring"
+ "NLM: %@ _refreshIPAddresses - tearing down dead Thread client"
+ "NLM: %@ _refreshIPAddresses - tearing down dead WiFi client"
+ "NLM: %@ advanceEndpoint: %@ picker exhausted"
+ "NLM: %@ advanceEndpoint: NLM disabled, no iteration"
+ "NLM: %@ advanceEndpoint: close already queued, not iterating"
+ "NLM: %@ advanceEndpoint: failed to open new %@ client: %@"
+ "NLM: %@ advanceEndpoint: no %@ client after build, cannot open"
+ "NLM: %@ advanceEndpoint: no active client to advance from"
+ "NLM: %@ advanceEndpoint: primary picker exhausted, retrying PV on secondary"
+ "NLM: %@ advanceEndpoint: swapping %@ client for fresh client at next IP"
+ "NLM: %@ applyResolverAddresses applied on queue (state=%lu primary=%lu secondary=%lu initialResolveCompleted=%{BOOL}d)"
+ "NLM: %@ getLocalIPv4Endpoint called"
+ "NLM: %@ getLocalIPv6Endpoint called"
+ "NLM: %@ isThreadIPv6Address: %{BOOL}d"
+ "NLM: %@ mergeWithNewTransport - names changed, recycling resolver"
+ "NLM: %@ mergeWithNewTransport - state Open, refreshing IP addresses (resolver browser-owned)"
+ "NLM: %@ mergeWithNewTransport - state is Open, refreshing IP addresses"
+ "NLM: %@ securedClient doesn't match either client, cannot register"
+ "NLM: %@ session->addr_info.local family: %d (AF_INET=%d, AF_INET6=%d)"
+ "NLM: %{public}@ resolver:didUpdateAddresses: cache-only latch armed — forwarding off-queue to bypass Server queue held by pair-verify"
+ "NLM: <Ping id=%lu> received from accessory"
+ "NLM: All transports hit failure threshold; marking accessory unreachable"
+ "NLM: Attached to resolver for deviceID=%{public}@"
+ "NLM: Browser audit pass — active=%lu"
+ "NLM: Configured transport %@ with maxInterval %.1fs"
+ "NLM: Controller forwarding PV-failure deviceID=%{public}@ transport=%lu domain=%{public}@ code=%ld"
+ "NLM: Controller forwarding PV-success deviceID=%{public}@ transport=%lu"
+ "NLM: Controller forwarding Thread advertisement %@"
+ "NLM: Controller forwarding WiFi advertisement %@"
+ "NLM: Controller forwarding heartbeat on transport %ld"
+ "NLM: DNSServiceResolve SRV changed (hostChanged=%d portChanged=%d); rebuilding getaddrinfo pipeline"
+ "NLM: DNSServiceResolve callback err=%d"
+ "NLM: DNSServiceResolve setup failed err=%d"
+ "NLM: Failed to apply RTT sample %.3fs (error %d)\n"
+ "NLM: Heartbeat received for untracked transport %ld"
+ "NLM: Heartbeat received on transport %ld"
+ "NLM: Heartbeat received on transport %ld, connectionState=%ld"
+ "NLM: Heartbeat received on transport %ld, resetting missed flag"
+ "NLM: Heartbeat received while not connected — restoring connectivity"
+ "NLM: Invalid maxInterval for transport %ld"
+ "NLM: Missed heartbeat on transport %@, time since last: %.1fs"
+ "NLM: Missed heartbeat on transport %ld, expected %.1fs, since last %.1fs"
+ "NLM: No free slots in pending request array\n"
+ "NLM: No tracked transports with positive maxInterval — listener idle"
+ "NLM: PV-failure classify deviceID=%{public}@ transport=%lu domain=%{public}@ code=%ld evict=%d"
+ "NLM: PV-success cascade deviceID=%{public}@ transport=%lu"
+ "NLM: PV-success drop — no resolver attached for deviceID=%{public}@"
+ "NLM: Probe already in flight, rejecting new probe"
+ "NLM: Probe-driven recovery failure %lu/%lu for transport %ld: %@"
+ "NLM: Probe-driven recovery succeeded for transport %ld; clearing failure counter"
+ "NLM: Probe-driven recovery succeeded — restoring connectivity (state %lu → Connected)"
+ "NLM: RTT tracking array full (32 pending), evicting oldest for MID=%u\n"
+ "NLM: Re-advertisement (resolver path) deviceID=%{public}@, triggering updateReachability"
+ "NLM: Received Empty CON ping (MID=%d), sending RST"
+ "NLM: Received ping from unknown client"
+ "NLM: Rejecting negative RTT sample: %.3f\n"
+ "NLM: Resetting heartbeat timestamps to now"
+ "NLM: Restarting keep-alive listener"
+ "NLM: SecureTransportBase forwarding heartbeat on transport %ld"
+ "NLM: Send keep-alive probe"
+ "NLM: Sent Empty CON probe, MID=%lu"
+ "NLM: Server torn down before resolver:didUpdateAddresses: block ran on operationQueue for deviceID=%{public}@; dropping update"
+ "NLM: Starting keep-alive listener with %lu transports"
+ "NLM: Stopping keep-alive listener"
+ "NLM: Stopping keep-alive listener (dealloc)"
+ "NLM: Timer fired for transport %@, but heartbeat received %.1fs ago (within %.1fs window) — not a miss"
+ "NLM: Transport %ld destination is unadvertised; closing session"
+ "NLM: Transport deallocated before RTT stats completion [MID:%u]"
+ "NLM: [%{private}@] Discarded probe failure (code %ld) for MID %u, outstanding MID %u"
+ "NLM: dnssd_getaddrinfo error event err=%d"
+ "NLM: dnssd_getaddrinfo_create failed"
+ "NLM: resolver update deviceID=%{public}@ hasPTR=%{public}d primary=%lu secondary=%lu was=%{public}d now=%{public}d"
+ "NLM: tried-key encoder received unsupported address family %u; upstream filter regression?"
+ "NetworkLinkManagement"
+ "No active CoAP session"
+ "No active session"
+ "PreferredNetworkUpdated"
+ "Primary"
+ "Q\xd1"
+ "Received ping with message id %i but session has no app data"
+ "Registry: audit reconciling orphan PTR for deviceID=%{public}@ — recreating resolver from retained serviceName"
+ "Registry: cleaned up resolver for empty+idle deviceID=%{public}@"
+ "Registry: created resolver for deviceID=%{public}@ serviceName='%{private}@'"
+ "Registry: removeResolverForDeviceID no-op for unknown deviceID=%{public}@"
+ "Registry: removed resolver for deviceID=%{public}@"
+ "Registry: updateCachedAddresses no-op for unknown deviceID=%{public}@"
+ "Rejecting cache record for device %{public}@: version type=%{public}@ expected=%ld"
+ "Resolver pipeline factory returned nil"
+ "Resolver pipeline failed"
+ "Resolver timed out before first update"
+ "Resolver: attachDelegate for deviceID=%{public}@ -> %lu delegate(s), snapshot primary=%lu secondary=%lu"
+ "Resolver: cachedIP %{public}@ deviceID=%{public}@ transport=%lu"
+ "Resolver: cachedIPDidUpdate no-op (same pointer) deviceID=%{public}@ transport=%lu"
+ "Resolver: dropping IPv6 address from primary list (IPv4-only policy) for deviceID=%{public}@"
+ "Resolver: fanned out update for deviceID=%{public}@ to %lu delegate(s) (primary=%lu secondary=%lu)"
+ "Resolver: never-delivered health-check restart for deviceID=%{public}@"
+ "Resolver: pipeline delivered fatal error for deviceID=%{public}@ domain=%{public}@ code=%ld marker=%ld"
+ "Resolver: pipeline factory failed for deviceID=%{public}@"
+ "Resolver: serviceName updated for deviceID=%{public}@ to '%{private}@'"
+ "Resolver: torn down pipeline for deviceID=%{public}@"
+ "Secondary"
+ "Secondary(Thread)"
+ "Session keep-alive detected missed heartbeats on all transports"
+ "Unknown HAPMetricEventBluetoothVersionType %ld"
+ "Unknown HAPMetricEventPowerSourcesEnum %ld"
+ "Unknown HAPMetricEventWiFiVersionType %ld"
+ "Unknown HAPSessionKeepAliveTransportType %ld"
+ "Unknown HAPStabilityMetricsBootReasonType %ld"
+ "Unknown HAPStabilityMetricsHardwareFaultType %ld"
+ "Unpair: evicted cache entry deviceID=%{public}@"
+ "Unsupported local address family"
+ "[%{public}@] Attempting to derive HDS keys without an active session"
+ "[%{public}@] Failed to derive HDS keys from foreign pair-verify session: %@"
+ "[%{public}@] HDS key derivation failed (pairedServer=%p controller=%p secureTransport=%p)"
+ "[%{public}@] HDS key derivation failed: no security session on HAP2 secure transport"
+ "[%{public}@] HDS peer address unavailable (pairedServer=%p controller=%p secureTransport=%p coapTransport=%p)"
+ "[%{public}@] Invalid cachedPrimaryData type for device %{public}@"
+ "[%{public}@] Invalid cachedSecondaryData type for device %{public}@"
+ "[%{public}@] Invalid or missing configurationInfo for device %{public}@"
+ "[%{public}@] Rejecting cache record for device %{public}@: version type=%{public}@ expected=%ld"
+ "[%{public}@] configureKeepAliveListener called -- NOP"
+ "adaptiveTimeout"
+ "cachedIPDidUpdate persisted deviceID=%{public}@ transport=%lu op=%{public}@"
+ "cachedPrimaryData"
+ "cachedSecondaryData"
+ "clear"
+ "cleared"
+ "coap-client"
+ "coap_session_create_client"
+ "com.apple.CoreHAP.HAP2.BrowserResolverRegistry.audit"
+ "com.apple.HomeKit.daemon.Accessory.CHM"
+ "com.apple.HomeKit.daemon.Accessory.CHM.Recovery"
+ "configurationInfo"
+ "configureKeepAliveListener called -- NOP"
+ "deriveSessionKeyWithSalt:info:error: returned nil without error"
+ "deviationRTT"
+ "deviceID=%{public}@ fast-set hasThreadAdvertisement=%{public}d"
+ "deviceID=%{public}@ fast-set hasWiFiAdvertisement=%{public}d"
+ "errorCode=%d"
+ "errorCode=%d hosttarget=%s"
+ "estimatedRTT"
+ "getifaddrs failed: %s"
+ "hap2.resolver.propertyLock.%@"
+ "hasDiscoveryAdvertisement=YES(ptr) deviceID=%{public}@"
+ "hasThreadAdvertisement=YES(ptr) deviceID=%{public}@"
+ "hasWiFiAdvertisement=YES(ptr) deviceID=%{public}@"
+ "honoured"
+ "init(startTime:)"
+ "interfaceName"
+ "invalid"
+ "isThread"
+ "networks"
+ "none"
+ "not honoured"
+ "resolverRegistry"
+ "secondary"
+ "secondary-coap-client"
+ "selectedMaxInterval"
+ "selectedMinInterval"
+ "sessionLossCount"
+ "set"
+ "setIPCache ignored — initialization from cache has already run"
+ "setupEventSubscriptions: CoreThreadRadio framework not available"
+ "supported"
+ "threadConnectivityState"
+ "threadRecoveryAttemptCount"
+ "threadRestartCount"
+ "threadTransportLossCount"
+ "unsupported"
+ "v16@?0@\"NSArray\"8"
+ "v16@?0i8i12"
+ "v24@?0@\"HAP2CoAPClient\"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16"
+ "v24@?0^@8Q16"
+ "v24@?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16"
+ "v24@?0{shared_ptr<CtrXPC::Event>=^{Event}^{__shared_weak_count}}8"
+ "v28@?0@\"NSData\"8S16@\"NSError\"20"
+ "version"
+ "wifiConnectivityState"
+ "wifiRecoveryAttemptCount"
+ "wifiRestartCount"
+ "wifiTransportLossCount"
+ "\x8b"
+ "\x91"
+ "\x91\xf0\xf0Q!"
- "!Aq"
- "%@ '%{private}@' resolves to %lu address(es), %@"
- "<%@: %p primary=%lu secondary=%lu>"
- "Q\xc1"
- "aborting"
- "trying first address"
- "v24@?0@\"HAP2CoAPClient\"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}Ii}16"
- "v24@?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}Ii}16"
- "\x81\xf0\xf0Q!"
- "\x8a"
- "\xd1"
```
