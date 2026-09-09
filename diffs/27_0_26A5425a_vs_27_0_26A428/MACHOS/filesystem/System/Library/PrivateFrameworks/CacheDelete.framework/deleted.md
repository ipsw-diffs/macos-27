## deleted

> `/System/Library/PrivateFrameworks/CacheDelete.framework/deleted`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 904.0.7.0.0
-  __TEXT.__text: 0x5d194
+  __TEXT.__text: 0x5c32c
   __TEXT.__auth_stubs: 0xe30
   __TEXT.__objc_stubs: 0x6780
   __TEXT.__objc_methlist: 0x2f64

   __TEXT.__oslogstring: 0xa14d
   __TEXT.__objc_classname: 0x3fb
   __TEXT.__objc_methtype: 0xeab
-  __TEXT.__unwind_info: 0xdd0
+  __TEXT.__unwind_info: 0x1078
   __DATA_CONST.__const: 0x1ed8
   __DATA_CONST.__cfstring: 0x47c0
   __DATA_CONST.__objc_classlist: 0x120
Functions:
~ -[CacheDeleteAnalytics persistPath] : 196 -> 184
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ +[CacheDeleteAnalytics currentSystemInfo] : 160 -> 148
~ +[CacheDeleteAnalytics buildType] : 72 -> 60
~ +[CacheDeleteAnalytics individualAppStatsForAppInfo:phase:purgeAttempt:] : 1080 -> 1068
~ +[CacheDeleteAnalytics appStatsBatchForFairPurgeResult:purgeAttempt:] : 2892 -> 2872
~ -[CacheDeleteAnalytics fetchLowDiskStats] : 1192 -> 1180
~ -[CacheDeleteAnalytics fetchStorageStats] : 3280 -> 3268
~ -[CacheDeleteAnalytics fetchTimingStats:] : 968 -> 956
~ -[CacheDeleteAnalytics fetchApplicationUsageStats] : 108 -> 96
~ -[CacheDeleteAnalytics fetchAdditionalStats] : 196 -> 184
~ -[CacheDeleteAnalytics _addDailyStats:] : 96 -> 84
~ -[CacheDeleteAnalytics _postDailyStats:] : 372 -> 360
~ -[CacheDeleteAnalytics _reportPurgeTimingInfo:] : 268 -> 256
~ -[CacheDeleteAnalytics _reportPurgeableTimingInfo:] : 268 -> 256
~ -[CacheDeleteAnalytics roundNumber:toSignificantDigits:] : 92 -> 80
~ -[CacheDeleteAnalytics incrementDailyValueForKey:] : 244 -> 232
~ -[CacheDeleteAnalytics addDailyValueForKey:value:] : 332 -> 320
~ -[CacheDeleteAnalytics dailyPurgeableStats:] : 2316 -> 2304
~ -[CacheDeleteAnalytics systemUsageStats] : 1384 -> 1372
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[CacheDeleteAnalytics cacheManagementUsageStats] : 1008 -> 996
~ +[CacheDeleteAnalytics getLowDiskLevelFromPurgeResult:] : 184 -> 172
~ ___52-[CacheDeleteAnalytics processPurgeOperationResult:]_block_invoke : 744 -> 732
~ ___56-[CacheDeleteAnalytics processPurgeableOperationResult:]_block_invoke : 292 -> 280
~ ___55-[CacheDeleteAnalytics processPeriodicOperationResult:]_block_invoke : 456 -> 444
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ -[CacheDeleteAnalytics .cxx_destruct] : 104 -> 92
~ -[PurgeStatsReporter load] : 284 -> 272
~ -[PurgeStatsReporter .cxx_destruct] : 68 -> 56
~ -[AppCacheDeleteOptions .cxx_destruct] : 68 -> 56
~ +[AppContainerCaches deleteAppCaches:telemetry:] : 176 -> 164
~ +[AppContainerCaches deleteAppCaches:urgency:telemetry:group:] : 224 -> 212
~ +[AppContainerCaches deleteAppCaches:options:] : 3940 -> 3928
~ +[AppContainerCaches appContainerCachesWithInfo:] : 96 -> 84
~ -[AppContainerCaches encodeWithCoder:] : 108 -> 96
~ -[AppContainerCaches cachesForInstalledApps] : 172 -> 160
~ -[AppContainerCaches cachesForInstalledApps:bytesNeeded:volume:sortForUrgency:telemetry:] : 756 -> 744
~ -[AppContainerCaches cdVolumeForPath:] : 576 -> 564
~ -[AppContainerCaches appCache:forPath:] : 444 -> 432
~ ___39-[AppContainerCaches appCache:forPath:]_block_invoke : 256 -> 244
~ ___copy_helper_block_e8_32s40s48s56s64r : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48s56s64r : 88 -> 76
~ -[AppContainerCaches copyWithZone:] : 48 -> 36
~ ___copy_helper_block_e8_32s40s48s56r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ -[AppContainerCaches .cxx_destruct] : 148 -> 136
~ +[CacheDeleteDaemonVolume uuidForMountPoint:] : 808 -> 796
~ +[CacheDeleteDaemonVolume daSessQ] : 84 -> 72
~ ___34+[CacheDeleteDaemonVolume daSessQ]_block_invoke : 68 -> 56
~ -[CacheDeleteDaemonVolume setDiskRef:] : 104 -> 92
~ +[CacheDeleteDaemonVolume volumeWithDiskRef:] : 408 -> 396
~ -[CacheDeleteDaemonVolume bsdDisk] : 536 -> 524
~ -[CacheDeleteDaemonVolume bsdNamesForContainerNamed:] : 572 -> 560
~ -[CacheDeleteDaemonVolume siblings] : 1252 -> 1240
~ -[CacheDeleteDaemonVolume copyWithZone:] : 64 -> 52
~ +[CacheDeleteDaemonVolume volumeWithPath:] : 248 -> 236
~ +[CacheDeleteDaemonVolume createVolume:isPrimary:] : 424 -> 412
~ ___50+[CacheDeleteDaemonVolume createVolume:isPrimary:]_block_invoke : 108 -> 96
~ ___copy_helper_block_e8_32s40r48r : 88 -> 76
~ ___destroy_helper_block_e8_32s40r48r : 76 -> 64
~ +[CacheDeleteDaemonVolume volumeWithMountpoint:] : 224 -> 212
~ -[CacheDeleteDaemonVolume isSpecialVolume] : 40 -> 28
~ -[CacheDeleteDaemonVolume description] : 216 -> 204
~ -[CacheDeleteDaemonVolume .cxx_destruct] : 100 -> 88
~ -[CacheDeleteDaemonVolume(Snapshots) snapshots] : 376 -> 364
~ ___47-[CacheDeleteDaemonVolume(Snapshots) snapshots]_block_invoke : 140 -> 128
~ ___76-[CacheDeleteDaemonVolume(Snapshots) hasSnapshotsMatchingRegularExpression:]_block_invoke : 144 -> 132
~ ___73-[CacheDeleteDaemonVolume(Snapshots) snapshotsMatchingRegularExpression:]_block_invoke : 176 -> 164
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ ___74-[CacheDeleteDaemonVolume(Snapshots) snapshotsExcludingRegularExpression:]_block_invoke : 176 -> 164
~ -[CacheDeleteDaemonVolume(Snapshots) snapshotsExcludingTimeMachine] : 92 -> 80
~ +[CDAppClassifier sharedClassifier] : 84 -> 72
~ ___35+[CDAppClassifier sharedClassifier]_block_invoke : 64 -> 52
~ -[CDAppClassifier _updateWithMappingData:] : 340 -> 328
~ -[CDAppClassifier allVisibleAppBundleGroups] : 288 -> 276
~ -[CDAppClassifier allHiddenAppBundleGroups] : 288 -> 276
~ -[CDAppClassifier appBundleIDForPlugin:] : 352 -> 340
~ ___40-[CDAppClassifier appBundleIDForPlugin:]_block_invoke : 104 -> 92
~ -[CDAppClassifier pluginsForApp:] : 348 -> 336
~ ___33-[CDAppClassifier pluginsForApp:]_block_invoke : 132 -> 120
~ -[CDAppClassifier dirStatIDToBundleMap] : 712 -> 700
~ -[CDAppClassifier buildAppInfoForBundleGroups:] : 356 -> 344
~ -[CDAppClassifier .cxx_destruct] : 164 -> 152
~ ___FairPurgeSkippedBundleIDs_block_invoke : 76 -> 64
~ +[CDFairPurgeState sharedState] : 84 -> 72
~ ___31+[CDFairPurgeState sharedState]_block_invoke : 64 -> 52
~ -[CDFairPurgeState lastRunTimestamp] : 88 -> 76
~ -[CDFairPurgeState .cxx_destruct] : 68 -> 56
~ -[CDPurgeableAppInfo bundlesKey] : 200 -> 188
~ -[CDPurgeableAppInfo description] : 300 -> 288
~ -[CDPurgeableAppInfo encodeWithCoder:] : 616 -> 604
~ -[CDPurgeableAppInfo .cxx_destruct] : 68 -> 56
~ +[CacheDeleteListener(Daemon) daemonListenerWithExportedObject:] : 120 -> 108
~ +[CacheDeleteListener(Daemon) daemonPublicListenerWithExportedObject:] : 120 -> 108
~ +[CacheDeleteListener(Daemon) daemonPrivateListenerWithExportedObject:] : 120 -> 108
~ ___copy_helper_block_e8_32s40b : 72 -> 60
~ ___57-[CacheDeleteFairPurgeOperation loadSAFDataSynchronously]_block_invoke : 92 -> 80
~ ___51-[CacheDeleteFairPurgeOperation executeFirstPhase:]_block_invoke : 152 -> 140
~ __51-[CacheDeleteFairPurgeOperation executeFirstPhase:]_block_invoke.58 : 152 -> 140
~ __51-[CacheDeleteFairPurgeOperation executeFirstPhase:]_block_invoke.68 : 152 -> 140
~ +[CacheDeleteFairPurgeOperation criticalSystemPluginExemptions] : 84 -> 72
~ __85-[CacheDeleteFairPurgeOperation roundRobinPurgeServices:amount:batchSize:completion:]_block_invoke.104 : 144 -> 132
~ ___copy_helper_block_e8_32s40s48s56s64s72r80r : 120 -> 108
~ ___destroy_helper_block_e8_32s40s48s56s64s72r80r : 108 -> 96
~ ___copy_helper_block_e8_32s40s48s56b : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56s : 76 -> 64
~ ___copy_helper_block_e8_32s40b48r : 88 -> 76
~ -[CacheDeleteFairPurgeOperation purgeSentinel:outInode:] : 1008 -> 996
~ -[CacheDeleteFairPurgeOperation serializeTelemetry] : 2344 -> 2332
~ -[CacheDeleteFairPurgeOperation getStatistics] : 1080 -> 1068
~ ___74-[CacheDeleteFairPurgeOperation _updateFSPurgeableSizesForApps:forVolume:]_block_invoke : 132 -> 120
~ -[CacheDeleteFairPurgeOperation _analyzeAndSortAppsByWeight:] : 856 -> 844
~ ___53-[CacheDeleteFairPurgeOperation _purgePluginsForApp:]_block_invoke : 144 -> 132
~ -[CacheDeleteFairPurgeOperation .cxx_destruct] : 196 -> 184
~ ___copy_helper_block_e8_32b40r : 80 -> 68
~ ___copy_helper_block_e8_32s40b48r56r : 104 -> 92
~ ___destroy_helper_block_e8_32s40s48r56r : 84 -> 72
~ -[CacheDeleteOperation servicesForVolume:] : 460 -> 448
~ -[CacheDeleteOperation performBlockWithUrgency:] : 156 -> 144
~ ___44-[CacheDeleteOperation processTestFailures:]_block_invoke : 68 -> 56
~ -[CacheDeleteOperation volumeNames] : 364 -> 352
~ -[CacheDeleteOperation description] : 680 -> 668
~ -[CacheDeleteOperation .cxx_destruct] : 176 -> 164
~ ___48-[CacheDeletePeriodicOperation _startOperation:]_block_invoke_2 : 76 -> 64
~ ___copy_helper_block_e8_32s40s48s56s64s72s80r88r : 128 -> 116
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80r88r : 116 -> 104
~ ___copy_helper_block_e8_32s40s48s56s64s72r80r88r : 136 -> 124
~ ___destroy_helper_block_e8_32s40s48s56s64s72r80r88r : 120 -> 108
~ __48-[CacheDeletePeriodicOperation _startOperation:]_block_invoke.37 : 72 -> 60
~ ___copy_helper_block_e8_32s40r48r56r : 104 -> 92
~ ___destroy_helper_block_e8_32s40r48r56r : 88 -> 76
~ ___45-[CacheDeletePurgeableOperation addInFlight:]_block_invoke : 76 -> 64
~ ___48-[CacheDeletePurgeableOperation removeInFlight:]_block_invoke : 76 -> 64
~ ___46-[CacheDeletePurgeableOperation copyInFlights]_block_invoke : 96 -> 84
~ -[CacheDeletePurgeableOperation performBlockWithUrgency:] : 100 -> 88
~ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96w : 124 -> 112
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96w : 116 -> 104
~ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96s104s112s120r128w : 164 -> 152
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96s104s112s120r128w : 152 -> 140
~ ___copy_helper_block_e8_32s40s48s56s64s72s80r : 112 -> 100
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80r : 104 -> 92
~ ___copy_helper_block_e8_32s40s48s56s64w : 92 -> 80
~ ___destroy_helper_block_e8_32s40s48s56s64w : 84 -> 72
~ ___copy_helper_block_e8_32s40s48s56s64s72s80w : 108 -> 96
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80w : 100 -> 88
~ -[CacheDeletePurgeableOperation .cxx_destruct] : 100 -> 88
~ -[CacheDeletePurgeOperation purgeSentinel:outInode:] : 1008 -> 996
~ ___93-[CacheDeletePurgeOperation createAndStartFSEventStreamForSentinel:path:semaphore:outRescan:]_block_invoke : 104 -> 92
~ -[CacheDeletePurgeOperation createFSPurgeNotificationWithEventID:volumes:mustRescan:] : 568 -> 556
~ -[CacheDeletePurgeOperation filterServices:] : 548 -> 536
~ ___45-[CacheDeletePurgeOperation _startOperation:]_block_invoke : 104 -> 92
~ ___copy_helper_block_e8_32s40s48s56r64r72r80r : 136 -> 124
~ ___destroy_helper_block_e8_32s40s48s56r64r72r80r : 116 -> 104
~ ___copy_helper_block_e8_32s40s48s56r64r : 104 -> 92
~ ___destroy_helper_block_e8_32s40s48s56r64r : 92 -> 80
~ __45-[CacheDeletePurgeOperation _startOperation:]_block_invoke.114 : 2264 -> 2260
~ __45-[CacheDeletePurgeOperation _startOperation:]_block_invoke.115 : 6700 -> 6692
~ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96r104w : 140 -> 128
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96r104w : 128 -> 116
~ __45-[CacheDeletePurgeOperation _startOperation:]_block_invoke.118 : 132 -> 120
~ ___copy_helper_block_e8_32s40s48s56s64s72s80s88w : 116 -> 104
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88w : 108 -> 96
~ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96s104w : 132 -> 120
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96s104w : 124 -> 112
~ ___copy_helper_block_e8_32s40s48s56s64s72b : 104 -> 92
~ ___destroy_helper_block_e8_32s40s48s56s64s72s : 92 -> 80
~ ___copy_helper_block_e8_32s40s48s56s64s72b80r88w : 132 -> 120
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80r88w : 112 -> 100
~ ___copy_helper_block_e8_32s40s48s56s64s72s80b : 112 -> 100
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s : 100 -> 88
~ -[CacheDeletePurgeOperation .cxx_destruct] : 100 -> 88
~ +[CDDaemonPurgeableResultCache pathForVersion:] : 152 -> 140
~ +[CDDaemonPurgeableResultCache defaultPath] : 128 -> 116
~ +[CDDaemonPurgeableResultCache sharedPurgeableResultsCache] : 84 -> 72
~ ___59+[CDDaemonPurgeableResultCache sharedPurgeableResultsCache]_block_invoke : 112 -> 100
~ ___copy_helper_block_e8_32s40s48b : 80 -> 68
~ -[CDDaemonPurgeableResultCache emitRecentInfo:] : 528 -> 516
~ ___47-[CDDaemonPurgeableResultCache emitRecentInfo:]_block_invoke : 128 -> 116
~ ___49-[CDDaemonPurgeableResultCache addInvalidVolume:]_block_invoke : 76 -> 64
~ ___52-[CDDaemonPurgeableResultCache updateInvalidVolumes]_block_invoke : 68 -> 56
~ __73-[CDDaemonPurgeableResultCache updateRecentInfoForServiceID:volume:info:]_block_invoke.58 : 64 -> 52
~ ___copy_helper_block_e8_32s40s48s56s : 76 -> 64
~ ___79-[CDDaemonPurgeableResultCache deductPurgeableAmount:serviceID:volume:urgency:]_block_invoke : 172 -> 160
~ ___50-[CDDaemonPurgeableResultCache removeServiceInfo:]_block_invoke : 152 -> 140
~ ___59-[CDDaemonPurgeableResultCache updateRecentStateforVolume:]_block_invoke : 204 -> 192
~ ___48-[CDDaemonPurgeableResultCache prunePreserving:]_block_invoke : 152 -> 140
~ ___53-[CDDaemonPurgeableResultCache forgetPushingService:]_block_invoke : 104 -> 92
~ ___65-[CDDaemonPurgeableResultCache invalidateRecentResultsForVolume:]_block_invoke : 104 -> 92
~ ___71-[CDDaemonPurgeableResultCache copyInvalidServicesForVolume:atUrgency:]_block_invoke : 148 -> 136
~ ___51-[CDDaemonPurgeableResultCache copyPushingServices]_block_invoke : 96 -> 84
~ -[CDDaemonPurgeableResultCache .cxx_destruct] : 132 -> 120
~ +[CDDaemonRecentInfo recentInfoForVolumes:] : 96 -> 84
~ -[CDDaemonRecentInfo _createNewRecentVolumeInfo] : 48 -> 36
~ -[CDDaemonRecentInfo invalidateForVolume:] : 128 -> 116
~ -[CDDaemonRecentInfo addInvalidVolume:] : 96 -> 84
~ +[CDDaemonRecentVolumeInfo CDRecentVolumeInfo:] : 100 -> 88
~ -[CDDaemonRecentVolumeInfo bsdDisk] : 304 -> 292
~ -[CDDaemonRecentVolumeInfo thresholds] : 304 -> 292
~ -[CDFairPurgeOperationResult .cxx_destruct] : 84 -> 72
~ -[CDPeriodicOperationResult addResult:] : 112 -> 100
~ -[CDPeriodicOperationResult .cxx_destruct] : 84 -> 72
~ -[CDPurgeableOperationResult addResult:] : 112 -> 100
~ -[CDPurgeableOperationResult .cxx_destruct] : 84 -> 72
~ -[CDPurgeOperationResult addResult:] : 112 -> 100
~ -[CDPurgeOperationResult .cxx_destruct] : 116 -> 104
~ +[CacheDeletePruner prunerWithFileAge:dirAge:] : 76 -> 64
~ -[CDResult finish] : 84 -> 72
~ ___copy_helper_block_e8_32s40w : 68 -> 56
~ ___destroy_helper_block_e8_32s40w : 60 -> 48
~ -[CDAnonymousXPCService .cxx_destruct] : 84 -> 72
~ ___copy_helper_block_e8_32s40s48b56r64w : 108 -> 96
~ ___destroy_helper_block_e8_32s40s48s56r64w : 88 -> 76
~ -[CDAppExtensionService invalidateConnection] : 392 -> 380
~ -[CDAppExtensionService .cxx_destruct] : 84 -> 72
~ +[purgeOP purgeOpAtUrgency:info:reply:] : 140 -> 128
~ -[purgeOP .cxx_destruct] : 68 -> 56
~ __28-[CDService drainPurgeQueue]_block_invoke.67 : 124 -> 112
~ -[CDService description] : 236 -> 224
~ +[CDService serviceWithInfo:] : 156 -> 144
~ +[CDService serviceWithInfo:endpoint:] : 224 -> 212
~ +[CDService serviceWithInfo:extension:] : 132 -> 120
~ -[CDService .cxx_destruct] : 152 -> 140
~ -[CDXPCService addProcInfoForConnection:toDict:] : 232 -> 220
~ ___50-[CDXPCService _servicePurgeable:info:replyBlock:]_block_invoke_3 : 136 -> 124
~ ___copy_helper_block_e8_32s40s48s56b64b : 104 -> 92
~ ___destroy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___copy_helper_block_e8_32s40s48b56b : 96 -> 84
~ ___46-[CDXPCService _servicePurge:info:replyBlock:]_block_invoke_3 : 136 -> 124
~ ___49-[CDXPCService _servicePeriodic:info:replyBlock:]_block_invoke_3 : 108 -> 96
~ ___copy_helper_block_e8_32s40b48b : 88 -> 76
~ ___36-[CDXPCService _serviceCancelPurge:]_block_invoke_3 : 104 -> 92
~ ___copy_helper_block_e8_32b40b : 80 -> 68
~ ___42-[CDXPCService _serviceNotify:replyBlock:]_block_invoke_3 : 104 -> 92
~ ___44-[CDXPCService _serviceCallback:replyBlock:]_block_invoke_3 : 136 -> 124
~ ___copy_helper_block_e8_32s40s48b56r64r : 112 -> 100
~ ___copy_helper_block_e8_32b40r48r56w : 108 -> 96
~ ___destroy_helper_block_e8_32s40r48r56w : 84 -> 72
~ ___copy_helper_block_e8_32r40r48r56w : 108 -> 96
~ ___destroy_helper_block_e8_32r40r48r56w : 88 -> 76
~ ___copy_helper_block_e8_32s40b48b56r : 104 -> 92
~ -[CDXPCService obtainXPCConnection:] : 176 -> 164
~ -[CDXPCService resumeConnection] : 64 -> 52
~ -[CDXPCService .cxx_destruct] : 84 -> 72
~ ___19-[CacheDelete init]_block_invoke_2 : 72 -> 60
~ __19-[CacheDelete init]_block_invoke.86 : 92 -> 80
~ +[CacheDelete sharedCacheDelete] : 84 -> 72
~ ___32+[CacheDelete sharedCacheDelete]_block_invoke : 88 -> 76
~ ___40-[CacheDelete processLowDiskVolume:key:]_block_invoke : 104 -> 92
~ __40-[CacheDelete processLowDiskVolume:key:]_block_invoke.139 : 104 -> 92
~ __40-[CacheDelete processLowDiskVolume:key:]_block_invoke.143 : 104 -> 92
~ __40-[CacheDelete processLowDiskVolume:key:]_block_invoke.144 : 104 -> 92
~ -[CacheDelete extractThresholdsAndGoals:] : 568 -> 556
~ ___39-[CacheDelete handleVFSStreamXPCEvent:]_block_invoke : 256 -> 244
~ ___copy_helper_block_e8_32s40s48r56r64r : 112 -> 100
~ ___destroy_helper_block_e8_32s40s48r56r64r : 96 -> 84
~ __39-[CacheDelete handleVFSStreamXPCEvent:]_block_invoke.196 : 132 -> 120
~ __create_xpc_dictionary : 196 -> 184
~ -[CacheDelete registerActivityWithIdentifier:criteria:runHandler:] : 388 -> 376
~ -[CacheDelete saveRecentInfo] : 100 -> 88
~ ___37-[CacheDelete cancelPersistenceTimer]_block_invoke : 116 -> 104
~ ___30-[CacheDelete log_recent_info]_block_invoke : 68 -> 56
~ -[CacheDelete applicationExtensions] : 352 -> 340
~ __36-[CacheDelete applicationExtensions]_block_invoke.235 : 80 -> 68
~ -[CacheDelete fsPurgedVolumes:] : 588 -> 576
~ ___27-[CacheDelete copyServices]_block_invoke : 140 -> 128
~ -[CacheDelete serviceWithID:] : 116 -> 104
~ -[CacheDelete keyForVolume:atUrgency:] : 148 -> 136
~ -[CacheDelete shouldUpdateVolumes:atUrgency:] : 1428 -> 1416
~ ___37-[CacheDelete shouldUpdatePurgeable:]_block_invoke : 136 -> 124
~ ___89-[CacheDelete updateRecentResultsForVolumes:fsPurgeableOnly:withInfo:qos:receiveResults:]_block_invoke : 132 -> 120
~ ___copy_helper_block_e8_32s40s48s56s64s72s80s : 100 -> 88
~ ___30-[CacheDelete totalAvailable:]_block_invoke : 76 -> 64
~ -[CacheDelete purge:volume:callback:] : 7792 -> 7780
~ ___copy_helper_block_e8_32s40s48s56b64r72r : 120 -> 108
~ ___destroy_helper_block_e8_32s40s48s56s64r72r : 100 -> 88
~ ___copy_helper_block_e8_32s40s48s56s64b72r : 112 -> 100
~ ___destroy_helper_block_e8_32s40s48s56s64s72r : 96 -> 84
~ __37-[CacheDelete purge:volume:callback:]_block_invoke.410 : 104 -> 92
~ -[CacheDelete _purge:volume:services:callback:] : 2580 -> 2564
~ ___copy_helper_block_e8_32s40s48b56r : 96 -> 84
~ ___53-[CacheDelete invokeAfterMaxSeconds:min:group:block:]_block_invoke : 76 -> 64
~ ___copy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___49-[CacheDelete clientCheckin:endpoint:info:reply:]_block_invoke : 164 -> 152
~ ___copy_helper_block_e8_32s40s48r56r : 96 -> 84
~ ___copy_helper_block_e8_32s40w48w : 80 -> 68
~ ___destroy_helper_block_e8_32s40w48w : 68 -> 56
~ __49-[CacheDelete clientCheckin:endpoint:info:reply:]_block_invoke.510 : 76 -> 64
~ -[CacheDelete _entitlementToCheck:] : 264 -> 252
~ __38-[CacheDelete clientPurge:replyBlock:]_block_invoke.563 : 92 -> 80
~ __57-[CacheDelete clientPerformPeriodicsWithInfo:completion:]_block_invoke.584 : 96 -> 84
~ ___49-[CacheDelete clientPerformOperation:replyBlock:]_block_invoke : 132 -> 120
~ __49-[CacheDelete clientPerformOperation:replyBlock:]_block_invoke.673 : 132 -> 120
~ -[CacheDelete clientRegisterLowDiskFailure:failureType:isRoot:] : 120 -> 108
~ ___33-[CacheDelete registerOperation:]_block_invoke : 76 -> 64
~ ___25-[CacheDelete debugState]_block_invoke : 180 -> 168
~ -[CacheDelete operationsDebugState] : 192 -> 180
~ ___35-[CacheDelete operationsDebugState]_block_invoke : 80 -> 68
~ -[CacheDelete servicesDebugState] : 200 -> 188
~ ___33-[CacheDelete servicesDebugState]_block_invoke : 116 -> 104
~ -[CacheDelete .cxx_destruct] : 320 -> 308
~ __main_block_invoke.1014 : 284 -> 280
~ __main_block_invoke_3.1065 : 80 -> 68
~ __main_block_invoke_2.1106 : 76 -> 64
```
