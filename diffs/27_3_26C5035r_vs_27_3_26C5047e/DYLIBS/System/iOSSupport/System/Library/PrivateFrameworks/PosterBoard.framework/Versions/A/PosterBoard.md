## PosterBoard

> `/System/iOSSupport/System/Library/PrivateFrameworks/PosterBoard.framework/Versions/A/PosterBoard`

```diff

-355.3.7.0.0
-  __TEXT.__text: 0x1d9b08
-  __TEXT.__objc_methlist: 0xccdc
-  __TEXT.__const: 0x6764
-  __TEXT.__gcc_except_tab: 0x4958
-  __TEXT.__cstring: 0x11bbe
-  __TEXT.__oslogstring: 0x1bf32
+355.3.12.0.0
+  __TEXT.__text: 0x1ea4e8
+  __TEXT.__objc_methlist: 0xd084
+  __TEXT.__const: 0x67c4
+  __TEXT.__gcc_except_tab: 0x4b44
+  __TEXT.__cstring: 0x11f7e
+  __TEXT.__oslogstring: 0x1ca02
   __TEXT.__dlopen_cstrs: 0x150
   __TEXT.__ustring: 0xe
-  __TEXT.__swift5_typeref: 0x69c0
-  __TEXT.__constg_swiftt: 0x4998
+  __TEXT.__swift5_typeref: 0x6a44
+  __TEXT.__constg_swiftt: 0x4b14
   __TEXT.__swift5_builtin: 0x1a4
-  __TEXT.__swift5_reflstr: 0x3555
-  __TEXT.__swift5_fieldmd: 0x2550
+  __TEXT.__swift5_reflstr: 0x3635
+  __TEXT.__swift5_fieldmd: 0x25cc
   __TEXT.__swift5_assocty: 0x538
-  __TEXT.__swift5_proto: 0x1e0
+  __TEXT.__swift5_proto: 0x1e4
   __TEXT.__swift5_types: 0x1e0
-  __TEXT.__swift5_capture: 0x1590
-  __TEXT.__swift5_protos: 0x5c
+  __TEXT.__swift5_capture: 0x1e50
+  __TEXT.__swift5_protos: 0x60
   __TEXT.__swift_as_entry: 0x2c
   __TEXT.__swift_as_ret: 0x1c
   __TEXT.__swift_as_cont: 0x48
-  __TEXT.__unwind_info: 0x7a38
+  __TEXT.__unwind_info: 0x7c98
   __TEXT.__eh_frame: 0xd08
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x49d0
-  __DATA_CONST.__objc_classlist: 0x658
-  __DATA_CONST.__objc_catlist: 0xd8
+  __DATA_CONST.__const: 0x4b60
+  __DATA_CONST.__objc_classlist: 0x668
+  __DATA_CONST.__objc_catlist: 0xe0
   __DATA_CONST.__objc_protolist: 0x530
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x83d8
+  __DATA_CONST.__objc_selrefs: 0x8620
   __DATA_CONST.__objc_protorefs: 0x220
-  __DATA_CONST.__objc_superrefs: 0x3a0
+  __DATA_CONST.__objc_superrefs: 0x3b0
   __DATA_CONST.__objc_arraydata: 0x140
-  __DATA_CONST.__got: 0x19f0
-  __AUTH_CONST.__const: 0x6210
-  __AUTH_CONST.__cfstring: 0xb6a0
-  __AUTH_CONST.__objc_const: 0x32d40
+  __DATA_CONST.__got: 0x1a10
+  __AUTH_CONST.__const: 0x7110
+  __AUTH_CONST.__cfstring: 0xb940
+  __AUTH_CONST.__objc_const: 0x335d0
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x2068
-  __AUTH.__objc_data: 0x2e40
+  __AUTH_CONST.__auth_got: 0x2090
+  __AUTH.__objc_data: 0x2ee0
   __AUTH.__data: 0xcd0
-  __DATA.__objc_ivar: 0xee4
-  __DATA.__data: 0x51e0
+  __DATA.__objc_ivar: 0xf20
+  __DATA.__data: 0x5210
   __DATA.__bss: 0x2c98
   __DATA.__common: 0xd8
-  __DATA_DIRTY.__objc_data: 0x5158
-  __DATA_DIRTY.__data: 0xc60
+  __DATA_DIRTY.__objc_data: 0x52b8
+  __DATA_DIRTY.__data: 0xc50
   __DATA_DIRTY.__bss: 0x10e0
   __DATA_DIRTY.__common: 0x88
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 9006
-  Symbols:   13287
-  CStrings:  3555
+  Functions: 9287
+  Symbols:   13506
+  CStrings:  3618
 
Symbols:
+ +[NSUserDefaults(PBFUtilities) _pbf_migrationStateKeys]
+ +[NSUserDefaults(PBFUtilities) pbf_migrationState]
+ +[NSUserDefaults(PBFUtilities) pbf_resetMigrationState]
+ +[PBFPosterRoleCoordinator posterCollectionForRole:storage:sortedPosterUUIDs:posterForUUID:error:]
+ +[PBFPosterStoreSeed _gatedSeedWithGlue:outcome:reason:error:]
+ +[PBFPosterStoreSeed _readSeedForBaseURL:outcome:reason:error:]
+ +[PBFPosterStoreSeed seedWithGlue:outcome:]
+ -[PBFDataStoreArchiveAdjudicator importArchiveData:name:error:]
+ -[PBFPosterExtensionDataStore _concludeAmbientConfigurationMigrationAfterPass:]
+ -[PBFPosterExtensionDataStore _galleryConfigurationForRole:]
+ -[PBFPosterExtensionDataStore _isGalleryWorkEnabledForRole:]
+ -[PBFPosterExtensionDataStore _publishLockScreenPosterCollection:]
+ -[PBFPosterExtensionDataStore _rolesWithGalleryWorkEnabled]
+ -[PBFPosterExtensionDataStore _stateLock_setGalleryConfiguration:forRole:]
+ -[PBFPosterExtensionDataStore _stateLock_setSwitcherConfiguration:]
+ -[PBFPosterExtensionDataStore _test_setGalleryController:forRole:]
+ -[PBFPosterExtensionDataStore publishedLockScreenGalleryConfiguration]
+ -[PBFPosterExtensionDataStore publishedLockScreenPosterCollection]
+ -[PBFPosterExtensionDataStore publishedSwitcherConfiguration]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue _baseDataStoreURL:logsMigrationStatus:]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue _currentDataStoreReadyMarker]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue _dataStoreReadyMarkerAtBaseURL:]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue _dataStoreReadyMarkerURLForBaseURL:]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue _leanBaseDataStoreURL]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue _lock_cancelDataStoreForLanguageChange]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue _lock_publishLoadedDataStore]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue _lock_unpublishLoadedDataStore]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue _lock_updatePinnedDisplays:embeddedDisplayContext:]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue blockingDataStore]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue loadDataStoreWithCompletion:]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue loadedDataStore]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue server:fetchAmbientPosterDiagnosticsWithCompletion:]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue server:fetchMigrationStateWithCompletion:]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue server:importArchivedDataStoreData:named:completion:]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue server:restoreArchivedDataStoreNamed:backupExistingDataStore:resetMigrationState:completion:]
+ -[PBFPosterModelStoreCoordinator setSkipsMigrationSupplementCreation:]
+ -[PBFPosterModelStoreCoordinator skipsMigrationSupplementCreation]
+ -[PBFPosterSnapshotDefinition disallowsFilesystemCompression]
+ -[PBFPosterSnapshotManager _compressBundleAtURL:qos:thenCompletePUIRequest:imageURL:snapshotBundle:path:compressorForTesting:]
+ -[PBFPosterSnapshotManager _findReplacementForRemovedBundleOfPUIRequest:path:removedReservation:completion:]
+ -[PBFPosterSnapshotManager _finishCompressionOfPUIRequest:imageURL:snapshotBundle:path:]
+ -[PBFPosterSnapshotManager _lock_beginCompressingPUIRequest:bundleURL:qos:]
+ -[PBFPosterSnapshotManager _lock_cachedReservations:serveAllPUIRequests:]
+ -[PBFPosterSnapshotManager _lock_completeCompressedPUIRequest:imageURL:snapshotBundle:path:replacementReservation:]
+ -[PBFPosterSnapshotManager _lock_completePUIRequest:withImageURL:snapshotBundle:path:]
+ -[PBFPosterSnapshotManager _lock_compressionQoSForPUIRequest:]
+ -[PBFPosterSnapshotManager _lock_countInProgressContextsOfRequest:forTracker:]
+ -[PBFPosterSnapshotManager _lock_endCompressingPUIRequest:]
+ -[PBFPosterSnapshotManager _lock_hasSnapshotWorkInFlightForIdentity:]
+ -[PBFPosterSnapshotManager _lock_isPosterVisibleAtPath:]
+ -[PBFPosterSnapshotManager _lock_isRenderingOrCompressingAnyContextOfRequest:]
+ -[PBFPosterSnapshotManager _lock_isRenderingOrCompressingSnapshotContext:forIdentity:]
+ -[PBFPosterSnapshotManager _lock_noteCompletedPBFRequestsForPUIRequest:]
+ -[PBFPosterSnapshotManager _lock_raiseCompressionOfPUIRequestIfNeeded:]
+ -[PBFPosterSnapshotManager _lock_releasePrewarmAssertionIfIdle]
+ -[PBFPosterSnapshotManager _lock_sendRaiseForCompression:]
+ -[PBFPosterSnapshotManager _puiRequestTracker:matchesServerIdentity:displayContext:definition:]
+ -[PBFPosterSnapshotManager _submitSnapshotRequest:fulfilledReservations:completion:]
+ -[PBFPosterSnapshotManager _test_setBundleCompressionRaiser:]
+ -[PBFPosterSnapshotManager _test_setBundleCompressor:]
+ -[PBFPosterSnapshotPBFRequestTracker addCountedInProgressContext:]
+ -[PBFPosterSnapshotPBFRequestTracker hasCountedInProgressContexts]
+ -[PBFPosterSnapshotPBFRequestTracker takeCountedInProgressContexts]
+ -[PBFPosterStoreSeed .cxx_destruct]
+ -[PBFPosterStoreSeed _initWithSwitcherConfiguration:collection:]
+ -[PBFPosterStoreSeed lockScreenPosterCollection]
+ -[PBFPosterStoreSeed switcherConfiguration]
+ -[PRMutablePosterTitleStyleConfiguration(PBFAdditions) pbf_applyGalleryOptions:]
+ -[PRPosterTitleStyleConfiguration(PBFAdditions) pbf_effectiveCompactTimeFontWithExtensionBundleURL:forRole:displayContext:]
+ -[_PBFPosterExtensionDataStoreSQLiteDatabaseImpl initWithURL:options:skipsPragmas:error:]
+ -[_PBFPosterSnapshotCompression .cxx_destruct]
+ -[_PBFPosterSnapshotCompression bundleURL]
+ -[_PBFPosterSnapshotCompression initWithBundleURL:qos:]
+ -[_PBFPosterSnapshotCompression qos]
+ -[_PBFPosterSnapshotCompression setQos:]
+ GCC_except_table107
+ GCC_except_table113
+ GCC_except_table114
+ GCC_except_table120
+ GCC_except_table131
+ GCC_except_table142
+ GCC_except_table148
+ GCC_except_table152
+ GCC_except_table161
+ GCC_except_table163
+ GCC_except_table180
+ GCC_except_table183
+ GCC_except_table225
+ GCC_except_table26
+ GCC_except_table266
+ GCC_except_table353
+ GCC_except_table360
+ GCC_except_table362
+ GCC_except_table382
+ GCC_except_table396
+ GCC_except_table407
+ GCC_except_table430
+ GCC_except_table434
+ GCC_except_table437
+ GCC_except_table454
+ GCC_except_table470
+ GCC_except_table471
+ GCC_except_table472
+ GCC_except_table474
+ GCC_except_table64
+ GCC_except_table71
+ GCC_except_table73
+ GCC_except_table90
+ GCC_except_table98
+ _OBJC_CLASS_$_PBFPosterStoreSeed
+ _OBJC_CLASS_$_PRSwitcherConfiguration
+ _OBJC_CLASS_$__PBFPosterSnapshotCompression
+ _OBJC_IVAR_$_PBFPosterExtensionDataStore._publishedLock
+ _OBJC_IVAR_$_PBFPosterExtensionDataStore._publishedLock_lockScreenPosterCollection
+ _OBJC_IVAR_$_PBFPosterExtensionDataStore._publishedLock_roleToGalleryConfiguration
+ _OBJC_IVAR_$_PBFPosterExtensionDataStore._publishedLock_switcherConfiguration
+ _OBJC_IVAR_$_PBFPosterExtensionDataStoreXPCServiceGlue._loaderQueue
+ _OBJC_IVAR_$_PBFPosterExtensionDataStoreXPCServiceGlue._lock_holdsLoadedDataStore
+ _OBJC_IVAR_$_PBFPosterExtensionDataStoreXPCServiceGlue._monitorLock_loadedDataStore
+ _OBJC_IVAR_$_PBFPosterModelStoreCoordinator._skipsMigrationSupplementCreation
+ _OBJC_IVAR_$_PBFPosterSnapshotDefinition._disallowsFilesystemCompression
+ _OBJC_IVAR_$_PBFPosterSnapshotManager._lock_bundleCompressionRaiserForTesting
+ _OBJC_IVAR_$_PBFPosterSnapshotManager._lock_bundleCompressorForTesting
+ _OBJC_IVAR_$_PBFPosterSnapshotManager._lock_compressionsByPUIRequest
+ _OBJC_IVAR_$_PBFPosterSnapshotPBFRequestTracker._lock_countedInProgressContexts
+ _OBJC_IVAR_$_PBFPosterStoreSeed._lockScreenPosterCollection
+ _OBJC_IVAR_$_PBFPosterStoreSeed._switcherConfiguration
+ _OBJC_IVAR_$__PBFPosterSnapshotCompression._bundleURL
+ _OBJC_IVAR_$__PBFPosterSnapshotCompression._qos
+ _OBJC_METACLASS_$_PBFPosterStoreSeed
+ _OBJC_METACLASS_$__PBFPosterSnapshotCompression
+ _PBFLogKeyForPath
+ _PUIAFSCCompressBundleAtURLWithQoS
+ _PUIAFSCPrefaultFileIfCompressed
+ _PUIAFSCRaiseBundleCompressionQoS
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_PRMutablePosterTitleStyleConfiguration_$_PBFAdditions
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_PRPosterTitleStyleConfiguration_$_PBFAdditions
+ __OBJC_$_CATEGORY_PRMutablePosterTitleStyleConfiguration_$_PBFAdditions
+ __OBJC_$_CATEGORY_PRPosterTitleStyleConfiguration_$_PBFAdditions
+ __OBJC_$_CLASS_METHODS_PBFPosterStoreSeed
+ __OBJC_$_INSTANCE_METHODS_PBFPosterStoreSeed
+ __OBJC_$_INSTANCE_METHODS__PBFPosterSnapshotCompression
+ __OBJC_$_INSTANCE_VARIABLES_PBFPosterStoreSeed
+ __OBJC_$_INSTANCE_VARIABLES__PBFPosterSnapshotCompression
+ __OBJC_$_PROP_LIST_PBFPosterStoreSeed
+ __OBJC_$_PROP_LIST__PBFPosterSnapshotCompression
+ __OBJC_CLASS_RO_$_PBFPosterStoreSeed
+ __OBJC_CLASS_RO_$__PBFPosterSnapshotCompression
+ __OBJC_METACLASS_RO_$_PBFPosterStoreSeed
+ __OBJC_METACLASS_RO_$__PBFPosterSnapshotCompression
+ ___108-[PBFPosterSnapshotManager _findReplacementForRemovedBundleOfPUIRequest:path:removedReservation:completion:]_block_invoke
+ ___126-[PBFPosterSnapshotManager _compressBundleAtURL:qos:thenCompletePUIRequest:imageURL:snapshotBundle:path:compressorForTesting:]_block_invoke
+ ___48-[PBFPosterSnapshotManager snapshotsForRequest:]_block_invoke_2
+ ___59-[PBFPosterExtensionDataStore _rolesWithGalleryWorkEnabled]_block_invoke
+ ___63+[PBFPosterStoreSeed _readSeedForBaseURL:outcome:reason:error:]_block_invoke
+ ___67-[PBFPosterExtensionDataStoreXPCServiceGlue _updatePinnedDisplays:]_block_invoke_2
+ ___70-[PBFPosterExtensionDataStore _hasPendingProactiveSnapshotRefreshWork]_block_invoke
+ ___73-[PBFPosterExtensionDataStoreXPCServiceGlue loadDataStoreWithCompletion:]_block_invoke
+ ___74-[PBFPosterSnapshotManager _enqueueSnapshotForRequestIfNeeded:completion:]_block_invoke_4
+ ___84-[PBFPosterSnapshotManager _submitSnapshotRequest:fulfilledReservations:completion:]_block_invoke
+ ___84-[PBFPosterSnapshotManager _submitSnapshotRequest:fulfilledReservations:completion:]_block_invoke_2
+ ___88-[PBFPosterSnapshotManager _finishCompressionOfPUIRequest:imageURL:snapshotBundle:path:]_block_invoke
+ ___95-[PBFPosterExtensionDataStoreXPCServiceGlue _lock_updatePinnedDisplays:embeddedDisplayContext:]_block_invoke
+ ___98+[PBFPosterRoleCoordinator posterCollectionForRole:storage:sortedPosterUUIDs:posterForUUID:error:]_block_invoke
+ ___98+[PBFPosterRoleCoordinator posterCollectionForRole:storage:sortedPosterUUIDs:posterForUUID:error:]_block_invoke_2
+ ___98+[PBFPosterRoleCoordinator posterCollectionForRole:storage:sortedPosterUUIDs:posterForUUID:error:]_block_invoke_3
+ ___98+[PBFPosterRoleCoordinator posterCollectionForRole:storage:sortedPosterUUIDs:posterForUUID:error:]_block_invoke_4
+ ___block_descriptor_40_e8_32r_e17_v16?0"NSError"8lr32l8
+ ___block_descriptor_40_e8_32s_e52_"PRPosterConfiguration"24?0"NSUUID"8"NSString"16ls32l8
+ ___block_descriptor_40_e8_32w_e71_v32?0"PBFPosterSnapshotContext"8"PBFPosterSnapshotReservation"16^B24lw32l8
+ ___block_descriptor_48_e8_32bs40bs_e16_16?0"NSUUID"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40bs_e26_"NSString"16?0"NSUUID"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e52_"PRPosterConfiguration"24?0"NSUUID"8"NSString"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e71_v32?0"PBFPosterSnapshotContext"8"PBFPosterSnapshotReservation"16^B24ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e22_v16?0"NSDictionary"8ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56s_e66_v32?0"PBFPosterSnapshotContext"8"PUIPosterSnapshotBundle"16^B24ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56s_e67_v32?0"PBFPosterSnapshotContext"8"PUIPosterSnapshotRequest"16^B24ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e45_v24?0"PUIPosterSnapshotBundle"8"NSError"16ls32l8s40l8s64l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56s64w_e38_v16?0"PBFPosterSnapshotReservation"8lw64l8s32l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56w64w_e17_v16?0"NSArray"8lw56l8s32l8s40l8s48l8w64l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72w_e20_v24?0Q8"NSError"16ls32l8w72l8s40l8s48l8s56l8s64l8
+ ___swift_closure_destructor.121Tm
+ ___swift_closure_destructor.131Tm
+ ___swift_closure_destructor.134Tm
+ ___swift_closure_destructor.137Tm
+ ___swift_closure_destructor.168Tm
+ ___swift_closure_destructor.184Tm
+ ___swift_closure_destructor.43Tm
+ ___swift_closure_destructor.47Tm
+ ___swift_closure_destructor.53Tm
+ ___swift_closure_destructor.60Tm
+ _dispatch_queue_attr_make_with_qos_class
+ _kPBFDataStoreReadyMarkerFileName_block_invoke.timerSource
+ _objc_msgSend$_baseDataStoreURL:logsMigrationStatus:
+ _objc_msgSend$_compressBundleAtURL:qos:thenCompletePUIRequest:imageURL:snapshotBundle:path:compressorForTesting:
+ _objc_msgSend$_concludeAmbientConfigurationMigrationAfterPass:
+ _objc_msgSend$_currentDataStoreReadyMarker
+ _objc_msgSend$_dataStoreReadyMarkerAtBaseURL:
+ _objc_msgSend$_dataStoreReadyMarkerURLForBaseURL:
+ _objc_msgSend$_findReplacementForRemovedBundleOfPUIRequest:path:removedReservation:completion:
+ _objc_msgSend$_finishCompressionOfPUIRequest:imageURL:snapshotBundle:path:
+ _objc_msgSend$_galleryConfigurationForRole:
+ _objc_msgSend$_gatedSeedWithGlue:outcome:reason:error:
+ _objc_msgSend$_initWithSwitcherConfiguration:collection:
+ _objc_msgSend$_isGalleryWorkEnabledForRole:
+ _objc_msgSend$_leanBaseDataStoreURL
+ _objc_msgSend$_lock_beginCompressingPUIRequest:bundleURL:qos:
+ _objc_msgSend$_lock_cachedReservations:serveAllPUIRequests:
+ _objc_msgSend$_lock_cancelDataStoreForLanguageChange
+ _objc_msgSend$_lock_completeCompressedPUIRequest:imageURL:snapshotBundle:path:replacementReservation:
+ _objc_msgSend$_lock_completePUIRequest:withImageURL:snapshotBundle:path:
+ _objc_msgSend$_lock_compressionQoSForPUIRequest:
+ _objc_msgSend$_lock_countInProgressContextsOfRequest:forTracker:
+ _objc_msgSend$_lock_endCompressingPUIRequest:
+ _objc_msgSend$_lock_hasSnapshotWorkInFlightForIdentity:
+ _objc_msgSend$_lock_isPosterVisibleAtPath:
+ _objc_msgSend$_lock_isRenderingOrCompressingAnyContextOfRequest:
+ _objc_msgSend$_lock_isRenderingOrCompressingSnapshotContext:forIdentity:
+ _objc_msgSend$_lock_noteCompletedPBFRequestsForPUIRequest:
+ _objc_msgSend$_lock_publishLoadedDataStore
+ _objc_msgSend$_lock_raiseCompressionOfPUIRequestIfNeeded:
+ _objc_msgSend$_lock_releasePrewarmAssertionIfIdle
+ _objc_msgSend$_lock_sendRaiseForCompression:
+ _objc_msgSend$_lock_unpublishLoadedDataStore
+ _objc_msgSend$_lock_updatePinnedDisplays:embeddedDisplayContext:
+ _objc_msgSend$_pbf_migrationStateKeys
+ _objc_msgSend$_publishLockScreenPosterCollection:
+ _objc_msgSend$_puiRequestTracker:matchesServerIdentity:displayContext:definition:
+ _objc_msgSend$_readSeedForBaseURL:outcome:reason:error:
+ _objc_msgSend$_rolesWithGalleryWorkEnabled
+ _objc_msgSend$_stateLock_setGalleryConfiguration:forRole:
+ _objc_msgSend$_stateLock_setSwitcherConfiguration:
+ _objc_msgSend$_submitSnapshotRequest:fulfilledReservations:completion:
+ _objc_msgSend$addCountedInProgressContext:
+ _objc_msgSend$blockingDataStore
+ _objc_msgSend$disallowsFilesystemCompression
+ _objc_msgSend$executeDataStoreUpdateWithChanges:diffs:options:reason:error:
+ _objc_msgSend$hasCountedInProgressContexts
+ _objc_msgSend$importArchiveData:name:error:
+ _objc_msgSend$initWithBundleURL:qos:
+ _objc_msgSend$initWithURL:options:skipsPragmas:error:
+ _objc_msgSend$loadDataStoreWithCompletion:
+ _objc_msgSend$loadedDataStore
+ _objc_msgSend$lockScreenPosterCollection
+ _objc_msgSend$pbf_applyGalleryOptions:
+ _objc_msgSend$pbf_migrationState
+ _objc_msgSend$pbf_resetMigrationState
+ _objc_msgSend$posterCollectionForRole:storage:sortedPosterUUIDs:posterForUUID:error:
+ _objc_msgSend$propertyList:isValidForFormat:
+ _objc_msgSend$publishedLockScreenGalleryConfiguration
+ _objc_msgSend$publishedLockScreenPosterCollection
+ _objc_msgSend$publishedSwitcherConfiguration
+ _objc_msgSend$qos
+ _objc_msgSend$seedWithGlue:outcome:
+ _objc_msgSend$setPermanentCompactTimeEnabled:
+ _objc_msgSend$setQos:
+ _objc_msgSend$setSkipsMigrationSupplementCreation:
+ _objc_msgSend$snapshotContext
+ _objc_msgSend$stringWithContentsOfURL:encoding:error:
+ _objc_msgSend$takeCountedInProgressContexts
+ _objc_msgSend$timeStyle
+ _objc_msgSend$writeToURL:atomically:encoding:error:
+ _os_unfair_recursive_lock_lock
+ _symbolic $s11PosterBoard0A17StoreDataProviderP
+ _symbolic Say______pGSg So17PBFDisplayContextP
+ _symbolic SayyycG
+ _symbolic Shy_____G So36PRPosterSnapshotDefinitionIdentifiera
+ _symbolic So18PRPosterCollectionCSg
+ _symbolic So23PRSwitcherConfigurationCSg
+ _symbolic So27PBFPosterExtensionDataStoreCSg
+ _symbolic _____SgXw 11PosterBoard0A5StoreC
+ _symbolic _____SgXwz_Xx 11PosterBoard0A5StoreC
+ _symbolic ______p 11PosterBoard0A17StoreDataProviderP
+ _symbolic _____yyycG s23_ContiguousArrayStorageC
- -[PBFPosterExtensionDataStoreXPCServiceGlue _lock_updatePinnedDisplays:]
- -[PBFPosterExtensionDataStoreXPCServiceGlue server:restoreArchivedDataStoreNamed:backupExistingDataStore:completion:]
- -[PRPosterTitleStyleConfiguration(PBFCompactTimeFont) pbf_effectiveCompactTimeFontWithExtensionBundleURL:forRole:displayContext:]
- -[_PBFPosterExtensionDataStoreSQLiteDatabaseImpl initWithURL:options:error:]
- GCC_except_table106
- GCC_except_table108
- GCC_except_table111
- GCC_except_table130
- GCC_except_table136
- GCC_except_table140
- GCC_except_table141
- GCC_except_table149
- GCC_except_table151
- GCC_except_table162
- GCC_except_table179
- GCC_except_table182
- GCC_except_table224
- GCC_except_table258
- GCC_except_table341
- GCC_except_table348
- GCC_except_table350
- GCC_except_table370
- GCC_except_table384
- GCC_except_table395
- GCC_except_table418
- GCC_except_table421
- GCC_except_table424
- GCC_except_table441
- GCC_except_table458
- GCC_except_table459
- GCC_except_table460
- GCC_except_table462
- _OBJC_IVAR_$_PBFPosterExtensionDataStore._stateLock_roleToGalleryConfiguration
- _OBJC_IVAR_$_PBFPosterExtensionDataStore._stateLock_switcherConfiguration
- _PBFPosterExtensionDataStoreDidTearDownNotification_block_invoke.timerSource
- _PUIAFSCEnqueueCompressionForURL
- __OBJC_$_CATEGORY_INSTANCE_METHODS_PRPosterTitleStyleConfiguration_$_PBFCompactTimeFont
- __OBJC_$_CATEGORY_PRPosterTitleStyleConfiguration_$_PBFCompactTimeFont
- ___48-[PBFPosterExtensionStoreCoordinator invalidate]_block_invoke
- ___62-[PBFPosterSnapshotManager _submitSnapshotRequest:completion:]_block_invoke
- ___64-[PBFPosterRoleCoordinator buildNewPosterCollectionFromStorage:]_block_invoke_2
- ___72-[PBFPosterExtensionDataStoreXPCServiceGlue _lock_updatePinnedDisplays:]_block_invoke
- ___block_descriptor_56_e8_32s40s48s_e67_v32?0"PBFPosterSnapshotContext"8"PUIPosterSnapshotRequest"16^B24ls32l8s40l8s48l8
- ___block_descriptor_72_e8_32s40s48s56bs64bs_e22_v16?0"NSDictionary"8ls32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_80_e8_32s40s48s56s_e47_v32?0"NSString"8"PBFGalleryController"16^B24ls32l8s40l8s48l8s56l8
- ___block_descriptor_80_e8_32s40s48s56w64w_e17_v16?0"NSArray"8lw56l8s32l8s40l8w64l8s48l8
- ___swift_closure_destructor.103Tm
- ___swift_closure_destructor.46Tm
- ___swift_closure_destructor.49Tm
- ___swift_closure_destructor.91Tm
- _objc_msgSend$_lock_updatePinnedDisplays:
- _objc_msgSend$rootNodes
- _os_unfair_recursive_lock_lock_with_options
- _symbolic So23PRSwitcherConfigurationC
- _symbolic So41PBFPosterExtensionDataStoreXPCServiceGlueC
CStrings:
+ "![self publishedSwitcherConfiguration]"
+ "%@ phase %@ skipped; gallery work disabled"
+ "%@|%lu"
+ "'%@' is not a data store archive name."
+ "(%{public}@) phase %{public}@ bail asking for new gallery; gallery work is disabled for every role"
+ "(%{public}@) phase %{public}@ gallery work is disabled for every role; nothing to snapshot"
+ "(%{public}s) Skipping gallery update for role %{public}@; gallery work is disabled, reason: %{public}@"
+ "(_stateLock_buildSwitcherConfigurationWithContext...) Can't build switcher configuration yet: role setup hasn't run"
+ "@\"NSString\"16@?0@\"NSUUID\"8"
+ "@\"PRPosterConfiguration\"24@?0@\"NSUUID\"8@\"NSString\"16"
+ "AFSC completing %{public}@ with the snapshot that replaced its removed bundle"
+ "AFSC compressed %lu file(s) for %{public}@ in %.1fms; completing"
+ "AFSC compressed nothing for %{public}@ in %.1fms; completing"
+ "AFSC failed for %{public}@ after compressing %lu file(s) in %.1fms; completing with what is on disk: %{public}@"
+ "AFSC finished for %{public}@ after its requests were cancelled; dropping it"
+ "AFSC finished for %{public}@ after the manager was invalidated; failing %lu waiter(s)"
+ "AFSC finished for %{public}@ but its bundle is gone: %{public}@"
+ "AFSC finished for %{public}@, which wasn't compressing"
+ "AFSC found nothing to replace the removed bundle of %{public}@; completing with an error: %{public}@"
+ "AFSC has no snapshot cache to replace the removed bundle of %{public}@; completing with an error"
+ "AFSC raising the compression of %{public}@ to QoS %#x for a request that joined it"
+ "AFSC skipped for %{public}@: definition %{public}@ disallows filesystem compression"
+ "AFSC skipped for %{public}@: the snapshot bundle has no URL"
+ "An archived data store named '%@' already exists."
+ "DataStoreReadyMarker"
+ "Gallery controller requested snapshot prewarm for role %{public}@, but gallery work is disabled; deferring snapshot work; newlyAdded=%{BOOL}u"
+ "Gallery work is disabled for role %{public}@. Not pushing descriptors to proactive."
+ "Imported archived data store %{public}@ (%lu bytes)"
+ "Index LRU entry points to a bundle that is gone: %{public}@"
+ "PosterBoard.PosterStore"
+ "PosterStore dropped persist of %@: no data store"
+ "PosterStore dropped selection of %s: no live configuration"
+ "PosterStore has no data store"
+ "PosterStore off-main load failed; keeping the seed or placeholder"
+ "PosterStore seed: base URL raised: %{public}@"
+ "PosterStore seed: outcome=%ld reason=%{public}@ error=%{public}@/%ld posters=%lu"
+ "PosterStoreSeedInFlight"
+ "Refresh-if-necessary for role '%{public}@' (%{public}@): gallery work is disabled, no-op"
+ "Removing the ready marker raised: %{public}@"
+ "Resetting migration state for restored data store %{public}@: %{public}@"
+ "The snapshot bundle was removed while it was being compressed."
+ "[_migrateConfigurations] Could not finalize the ambient configuration migration on its own: %{public}@"
+ "[_migrateConfigurations] Firing postersMigrated event with %lu configurations (%lu requested, anyFailed: %{BOOL}u)"
+ "[_migrateConfigurations] Not firing postersMigrated (no migration requests); bailing."
+ "[_migrateConfigurations] Raised while concluding the ambient configuration migration: %{public}@"
+ "[_migrateConfigurations] Setting ambientMigrationVersion to %ld directly; finalizing did not."
+ "[performConfigurationMigrations] Marking %{public}@ as migrated to version %ld even though %lu configuration(s) failed; failed configurations are left unmigrated and will not be retried"
+ "[performConfigurationMigrations] Out of migration budget (%.1fs left, need %.0fs); could NOT finish configuration %{public}@ for %{public}@ — leaving it unmigrated"
+ "ambientConfigurationVersion"
+ "blockingDataStore: build failed: %{public}@"
+ "breaker not armed"
+ "cancelRequests: PUI request %{public}@ is orphaned while its bundle compresses; dropping it when that ends"
+ "com.apple.PosterBoard.PBFPosterExtensionDataStoreXPCServiceGlue.loader"
+ "conclude ambient configuration migration"
+ "disallowsFilesystemCompression"
+ "gallery work disabled; snapshot prewarm requested (reason: %@)"
+ "isActive"
+ "keeping snapshot manager assertions while %lu bundle(s) compress"
+ "marker from another build"
+ "no marker"
+ "no posters"
+ "no selection"
+ "off for this build"
+ "read died in this boot"
+ "selection not listed"
+ "snapshotsForRequest: a render or compression started during the cache read for request %{public}@; the enqueue path will finish it"
+ "torn down during read"
+ "v16@?0@\"PBFPosterSnapshotReservation\"8"
+ "v24@?0Q8@\"NSError\"16"
+ "v32@?0@\"PBFPosterSnapshotContext\"8@\"PBFPosterSnapshotReservation\"16^B24"
+ "v32@?0@\"PBFPosterSnapshotContext\"8@\"PUIPosterSnapshotBundle\"16^B24"
- "!_stateLock_switcherConfiguration"
- "<%p> [_enqueueSnapshotForRequestIfNeeded]: [remainingRequests count]: %lu. [request identifier]: %@"
- "[_migrateConfigurations] Firing postersMigrated event with %lu configurations"
- "[_migrateConfigurations] Not firing postersMigrated (%lu requested, %lu migrated, anyFailed: %{BOOL}u); bailing."
- "[performConfigurationMigrations] NOT marking %{public}@ as migrated to version %ld; at least one configuration failed and will be retried on the next migration"
- "[performConfigurationMigrations] Out of migration budget (%.1fs left, need %.0fs); could NOT finish configuration %{public}@ for %{public}@ — will retry next migration"
- "_lock_teardownDataStore: applicationRootNode cancel raised: %{public}@"
- "_lock_teardownDataStore: applicationStateMonitor invalidate raised: %{public}@"
```
