## locationd

> `/usr/libexec/locationd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_proto`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3188.0.7.0.0
-  __TEXT.__text: 0x6890c8
+3188.0.11.0.0
+  __TEXT.__text: 0x690480
   __TEXT.__auth_stubs: 0x3d10
-  __TEXT.__objc_stubs: 0x11000
-  __TEXT.__init_offsets: 0x188
-  __TEXT.__objc_methlist: 0x12c58
-  __TEXT.__const: 0x18368
-  __TEXT.__gcc_except_tab: 0x2ae28
-  __TEXT.__cstring: 0x7ba0a
-  __TEXT.__oslogstring: 0x9a420
-  __TEXT.__objc_methname: 0x202ae
+  __TEXT.__objc_stubs: 0x11100
+  __TEXT.__init_offsets: 0x18c
+  __TEXT.__objc_methlist: 0x12ce8
+  __TEXT.__const: 0x18448
+  __TEXT.__gcc_except_tab: 0x2b024
+  __TEXT.__cstring: 0x7c06a
+  __TEXT.__oslogstring: 0x9b3d0
+  __TEXT.__objc_methname: 0x2056e
   __TEXT.__objc_classname: 0x3454
-  __TEXT.__objc_methtype: 0xf25c
+  __TEXT.__objc_methtype: 0xf27c
   __TEXT.__ustring: 0x346
   __TEXT.__constg_swiftt: 0x4a4
   __TEXT.__swift5_typeref: 0x37b

   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x1e650
+  __TEXT.__unwind_info: 0x1e810
   __TEXT.__eh_frame: 0x7d0
-  __DATA_CONST.__const: 0x2c698
-  __DATA_CONST.__cfstring: 0x16400
+  __DATA_CONST.__const: 0x2c7d0
+  __DATA_CONST.__cfstring: 0x16520
   __DATA_CONST.__objc_classlist: 0x8e0
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x5b8

   __DATA_CONST.__linkguard: 0x15
   __DATA_CONST.__auth_got: 0x1ea8
   __DATA_CONST.__got: 0xc80
-  __DATA_CONST.__auth_ptr: 0x348
-  __DATA.__objc_const: 0x1ee30
-  __DATA.__objc_selrefs: 0x7908
-  __DATA.__objc_ivar: 0x12ac
+  __DATA_CONST.__auth_ptr: 0x350
+  __DATA.__objc_const: 0x1ef90
+  __DATA.__objc_selrefs: 0x7960
+  __DATA.__objc_ivar: 0x12d8
   __DATA.__objc_data: 0x5cc0
   __DATA.__data: 0x5880
   __DATA.__common: 0x868
-  __DATA.__bss: 0x2f00
+  __DATA.__bss: 0x2f20
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 27180
+  Functions: 27282
   Symbols:   1480
-  CStrings:  25142
+  CStrings:  25240
 
CStrings:
+ "-[CLGnssLocationXPCServiceManager asynchronousRemoteObjectProxyWithFailureHandler:]"
+ "-[CLGnssLocationXPCServiceManager asynchronousRemoteObjectProxyWithFailureHandler:]_block_invoke"
+ "-[CLGnssLocationXPCServiceManager clearUnansweredRequest]"
+ "-[CLGnssLocationXPCServiceManager handleConnectionLostForGeneration:interrupted:]"
+ "-[CLGnssLocationXPCServiceManager noteReplyOnGeneration:]"
+ "-[CLGnssLocationXPCServiceManager raiseRavenEventsFromData:]"
+ "-[CLGnssLocationXPCServiceManager scheduleReconfigureAfterLossWithReason:]"
+ "09:30:55"
+ "@24@0:8@?16"
+ "@MindPalace GPS always allowed, %{public}.1lf"
+ "@MindPalace GPS session not added to the shared budget, %{public}.1lf"
+ "@MindPalace GPS session, duration, %{public}.1lf, gotFix, %{public}d"
+ "@MindPalace Overriding ForceAllFencesMindPalaceMode to %{public}d"
+ "@MindPalace WiFi miss not counted, %{public}s, not a timer cycle, misses, %{public}d"
+ "@MindPalace WiFi miss, %{public}d, %{public}s"
+ "@MindPalace fallback to shipping behavior, consecutive WiFi misses, %{public}d"
+ "@MindPalace gate %{public}s, reason, %{public}s, mpFences, %{public}d, companionConnected, %{public}d, override, %{public}d, killSwitch, %{public}d"
+ "@MindPalace leaving fallback, WiFi location"
+ "@MindPalace leaving fallback, gate change"
+ "@MindPalace timer cancelled, proposal mode, %{public}d, engaged, %{public}d"
+ "@MindPalace trigger event, wifiResult, %{public}s (%{public}d), gpsResult, %{public}s (%{public}d), assertion, %{public}.1lf, assertionDuration, %{public}d, spannedSleep, %{public}d, tbTrigger, %{public}.1lf, triggerInterval, %{public}d, trigger, %{public}d, distanceToMpFence, %{public}d, skipReason, %{public}d"
+ "CLFU,could not remove %{public}s,%{public}d"
+ "CLFU,removed stale %{public}s"
+ "CLGLS,CLGnssLocationXPCServiceManager,getRavenSolutionWithReply"
+ "CLGLS,asynchronousRemoteObjectProxy error,domain,%{public}@,code,%{public}ld,%{public}@"
+ "CLGLS,asynchronousRemoteObjectProxy,nil proxy,failing fast"
+ "CLGLS,connection,lost,reason,%{public}s,gen,%{public}llu,losses,%{public}u,nextInS,%{public}.1lf"
+ "CLGLS,connection,stable,backoff reset,ageS,%{public}.1lf,losses,%{public}u"
+ "CLGLS,connection,stale handler,ignored,interrupted,%{public}d,gen,%{public}llu,current,%{public}llu"
+ "CLGLS,pauseResetAndFreeRavenSupervisor,no connection,nothing to free"
+ "CLGLS,reconfigureRavenIfNeeded,completed,success,0,service rejected the configuration"
+ "CLGLS,reconfigureRavenIfNeeded,completed,success,1"
+ "CLGLS,reconfigureRavenIfNeeded,losses,%{public}u"
+ "CLGLS,supervisor,input cutoff ended,dropped,%{public}u"
+ "CLGLS,supervisor,input cutoff,request unansweredS,%{public}.1lf"
+ "Fence: overriding disableMindPalacePolicy, %d"
+ "Fence: overriding slowTransitionAttributionEnabled, %d"
+ "FindMyProxyOptedIn"
+ "ForceAllFencesMindPalaceMode"
+ "GPS in the second stage"
+ "GeoGenericBundleId"
+ "GeofenceDisableMindPalacePolicy"
+ "GeofenceSlowTransitionAttributionEnabled"
+ "MindPalace Tracking Timer"
+ "Nov 10 2026"
+ "Nov 10 2026 09:32:31"
+ "Stop monitoring, nearby"
+ "assertionDuration"
+ "asynchronousRemoteObjectProxyWithFailureHandler:"
+ "bootPinResetResolved"
+ "clearUnansweredRequest"
+ "com.apple.clx.geofence.mindpalace"
+ "com.apple.locationd.bundle-/System/Library/LocationBundles/RelevanceIntelligence.bundle"
+ "distanceToFence"
+ "fConnectionCreatedMachContTimeSeconds"
+ "fConnectionGeneration"
+ "fRavenConsecutiveConnectionLosses"
+ "fRavenInputCutOff"
+ "fRavenInputDroppedCount"
+ "fRavenReconfigureBackoffSeconds"
+ "fRavenReconfigureNotBeforeMachContTimeSeconds"
+ "fRavenReplyReceivedOnCurrentConnection"
+ "fRavenRequestUnanswered"
+ "fRavenRequestUnansweredSinceMachContTimeSeconds"
+ "fence added"
+ "fence removed"
+ "gpsResult"
+ "handleConnectionLostForGeneration:interrupted:"
+ "hasConfiguredConnection"
+ "inactive"
+ "interrupted"
+ "invalidated"
+ "isPinResetPendingForBootSession"
+ "kCLHomePinLastBootSession"
+ "leech"
+ "masqueradeBundleId:"
+ "newServiceConnection"
+ "no location"
+ "noattempt"
+ "not created"
+ "noteReplyOnGeneration:"
+ "recordPinResetForBootSession"
+ "retry"
+ "scanonly"
+ "scanset1"
+ "scanset2"
+ "scheduleReconfigureAfterLossWithReason:"
+ "sendConfigureWithCompletion:"
+ "sendGetRavenSolutionWithReply:usingSender:"
+ "triggerInterval"
+ "unestablished"
+ "v24@?0@\"<GNSSLocationServiceProtocol>\"8@?<v@?@\"NSData\">16"
+ "v28@0:8Q16B24"
+ "void CLFenceMonitor::mpCountWifiMiss(const CFAbsoluteTime, const char *, const bool)"
+ "void CLFenceMonitor::mpNoteGateChange(const CFAbsoluteTime, const char *)"
+ "void CLFenceMonitor::mpOnLocation(const CFAbsoluteTime, const CLLocationType)"
+ "void CLFenceMonitor::mpResetFallback(const CFAbsoluteTime)"
+ "void CLFenceMonitor::mpSubmitTriggerEvent(const CFAbsoluteTime, const CLFenceAnalytics::MpWifiResult, const CLFenceAnalytics::MpGpsResult, const bool)"
+ "void CLFenceMonitor::mpUpdateArming(const CFAbsoluteTime)"
+ "void CLFenceMonitor::stopAcquisitionForConnectedCompanion()"
+ "void CLFenceSettings::applySettingOverridesAfterOta()"
+ "void CLFileUpdate::removeTempFile()"
+ "wifiResult"
+ "{\"msg%{public}.0s\":\"#FenceMetrics, mpheartbeat,1,\", \"mpPeriodStart\":\"%{public}.1f\", \"mpActiveSeconds\":\"%{public}.1f\", \"mpTimerFired\":%{public}lld, \"mpTotalCycles\":%{public}lld, \"mpCyclesWifiYield\":%{public}lld, \"mpCyclesGpsRescued\":%{public}lld, \"mpCyclesNoLocation\":%{public}lld, \"mpGpsSessions\":%{public}lld, \"mpGpsDuration\":\"%{public}.1f\", \"mpGpsSessionsNoFix\":%{public}lld, \"mpFallbacks\":%{public}lld, \"mpFallbackSeconds\":\"%{public}.1f\", \"mpMaxWifiMissStreak\":%{public}lld}"
+ "{\"msg%{public}.0s\":\"FenceMetric, geofencemetric,4\", \"timeLatencySource\":%{private}d, \"latencyUpperBound\":\"%{private}f\", \"latencyLowerBound\":\"%{private}f\", \"latencyEvidenceAccuracyScale\":\"%{private}f\", \"latencyUpperBoundFromWsb\":%{private}hhd, \"prevFixConfidentOldSide\":%{private}hhd, \"prevFixAfterTrigger\":%{private}hhd, \"prevFixClearedByCompanion\":%{private}hhd}"
+ "{\"msg%{public}.0s\":\"FenceMetric, geofencemetric,5\", \"gapDuration\":\"%{private}f\", \"gapFlags\":%{private}lld, \"gapFenceRequests\":%{private}lld, \"gapWifiStagesNoFix\":%{private}lld, \"gapRequestsNoFix\":%{private}lld, \"gapWifiScanErrors\":%{private}lld, \"gapWifiScansEmpty\":%{private}lld, \"gapTriggersSkippedFar\":%{private}lld, \"gapGpsSessions\":%{private}lld, \"gapGpsNoFix\":%{private}lld, \"gapGpsEndedByOtherFix\":%{private}lld, \"gapGpsCancelled\":%{private}lld, \"gapGpsDeniedSpacing\":%{private}lld, \"gapGpsDeniedBudget\":%{private}lld, \"gapCompanionConnectedDuration\":\"%{private}f\"}"
+ "{\"msg%{public}.0s\":\"FenceMetric, geofencemetric,6\", \"signalEnvClass\":%{private}lld, \"isLowPowerMode\":%{private}hhd, \"eventFixDuringFenceRequest\":%{private}hhd, \"eventFixWifiType\":%{private}lld, \"fenceHasPersonalizedFix\":%{private}hhd, \"companionDisconnectedAge\":\"%{private}f\"}"
+ "{\"msg%{public}.0s\":\"FenceMetric, geofencemetric,7\", \"gapHighAccuracyFixes\":%{private}lld, \"gapAmbiguousFixes\":%{private}lld, \"gapWifiFixes\":%{private}lld, \"gapWifiAmbiguousFixes\":%{private}lld, \"gapPersonalizedWifiFixes\":%{private}lld, \"gapPersonalizedWifiAmbiguousFixes\":%{private}lld, \"gapGnssFixes\":%{private}lld, \"gapGnssAmbiguousFixes\":%{private}lld, \"gapAmbiguousAccuracyBelow1\":%{private}lld, \"gapAmbiguousAccuracy1To2\":%{private}lld, \"gapAmbiguousAccuracy2To4\":%{private}lld, \"gapAmbiguousAccuracyAbove4\":%{private}lld}"
+ "{\"msg%{public}.0s\":\"GPSODOM,odometer source changed\", \"buffered\":%{public}hhd, \"extendedWorkout\":%{public}hhd, \"isLiveGpsRequested\":%{public}hhd, \"hasBufferedGnssClients\":%{public}hhd}"
- "-[CLGnssLocationXPCServiceManager getConnection]_block_invoke"
- "-[CLGnssLocationXPCServiceManager getSynchronousRemoteObjectProxy]_block_invoke"
- "05:59:28"
- "CLGLS,CLGnssLocationXPCServiceManager,getRavenSolutionAtMCTimeWithReply"
- "CLGLS,getSynchronousRemoteObjectProxy error %{public}@"
- "CLGLS,reconfigureRavenIfNeeded"
- "CLGLS,reconfigureRavenIfNeeded,completed,success,%{public}d"
- "Oct 29 2026"
- "Oct 29 2026 06:00:48"
- "getSynchronousRemoteObjectProxy"
- "{\"msg%{public}.0s\":\"FenceMetric, geofencemetric,4\", \"timeLatencySource\":%{private}d, \"latencyUpperBound\":\"%{private}f\", \"latencyLowerBound\":\"%{private}f\", \"latencyUpperBoundFromWsb\":%{private}hhd, \"prevFixConfidentOldSide\":%{private}hhd, \"prevFixAfterTrigger\":%{private}hhd, \"prevFixClearedByCompanion\":%{private}hhd}"
```
