## ExchangeSync

> `/System/Library/PrivateFrameworks/ExchangeSync.framework/Versions/A/ExchangeSync`

```diff

-2080.300.31.0.0
-  __TEXT.__text: 0x23e844
-  __TEXT.__objc_methlist: 0x864c
-  __TEXT.__const: 0xb238
-  __TEXT.__gcc_except_tab: 0x1970
-  __TEXT.__cstring: 0xff8b
-  __TEXT.__oslogstring: 0x1814b
-  __TEXT.__swift5_typeref: 0x3800
-  __TEXT.__swift5_reflstr: 0x3c34
-  __TEXT.__swift5_assocty: 0xa40
-  __TEXT.__constg_swiftt: 0x3a9c
-  __TEXT.__swift5_fieldmd: 0x3f24
-  __TEXT.__swift5_proto: 0x5a0
-  __TEXT.__swift5_types: 0x4dc
-  __TEXT.__swift5_protos: 0xcc
-  __TEXT.__swift5_capture: 0x1050
+2080.300.51.0.0
+  __TEXT.__text: 0x25df48
+  __TEXT.__objc_methlist: 0x8a14
+  __TEXT.__const: 0xbb78
+  __TEXT.__gcc_except_tab: 0x1a98
+  __TEXT.__cstring: 0x107bb
+  __TEXT.__oslogstring: 0x19cfa
+  __TEXT.__swift5_typeref: 0x3a26
+  __TEXT.__swift5_reflstr: 0x3fc4
+  __TEXT.__swift5_assocty: 0xa58
+  __TEXT.__constg_swiftt: 0x3db8
+  __TEXT.__swift5_fieldmd: 0x4358
+  __TEXT.__swift5_proto: 0x5dc
+  __TEXT.__swift5_types: 0x528
+  __TEXT.__swift5_protos: 0xd0
+  __TEXT.__swift5_capture: 0x11c8
   __TEXT.__swift5_builtin: 0xdc
   __TEXT.__swift5_mpenum: 0x40
-  __TEXT.__unwind_info: 0x7e40
-  __TEXT.__eh_frame: 0x651c
+  __TEXT.__unwind_info: 0x8468
+  __TEXT.__eh_frame: 0x6b2c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x7b0
-  __DATA_CONST.__objc_classlist: 0x4b8
+  __DATA_CONST.__const: 0x768
+  __DATA_CONST.__objc_classlist: 0x4f0
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0xc0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5010
+  __DATA_CONST.__objc_selrefs: 0x5248
   __DATA_CONST.__objc_protorefs: 0x38
-  __DATA_CONST.__objc_superrefs: 0x248
+  __DATA_CONST.__objc_superrefs: 0x250
   __DATA_CONST.__objc_arraydata: 0x20
-  __DATA_CONST.__got: 0x17b0
-  __AUTH_CONST.__const: 0xce68
-  __AUTH_CONST.__cfstring: 0x5da0
-  __AUTH_CONST.__objc_const: 0x125b8
+  __DATA_CONST.__got: 0x1808
+  __AUTH_CONST.__const: 0xdcf0
+  __AUTH_CONST.__cfstring: 0x5f00
+  __AUTH_CONST.__objc_const: 0x13260
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x2398
-  __AUTH.__objc_data: 0x2920
-  __AUTH.__data: 0x40f8
-  __DATA.__objc_ivar: 0xaf0
-  __DATA.__data: 0x1cd8
-  __DATA.__bss: 0xa8e0
-  __DATA.__common: 0x610
+  __AUTH_CONST.__auth_got: 0x24a8
+  __AUTH.__objc_data: 0x2b28
+  __AUTH.__data: 0x43f8
+  __DATA.__objc_ivar: 0xb48
+  __DATA.__data: 0x1e20
+  __DATA.__bss: 0xb140
+  __DATA.__common: 0x628
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 9753
-  Symbols:   9164
-  CStrings:  2442
+  Functions: 10184
+  Symbols:   9456
+  CStrings:  2552
 
Symbols:
+ +[EXSAccountManager _sweepStaleWebPushKeysForACAccounts:delegateKeysByAccount:syncingAccounts:]
+ +[EXSEWSSyncProtocol calendarFolderIsReadOnly:known:]
+ +[EXSGSMigrationReachabilityProbe defaultSettleDelay]
+ +[EXSGSMigrationReachabilityProbe intervalAfterSpentArms:]
+ +[EXSGSMigrationReachabilityProbe log]
+ +[EXSGSMigrationReachabilityProbe responseShowsPathOpen:]
+ +[EXSNotesChangeTokenPolicy shouldFetchUnchangedToken:lastFetchedToken:lastFetchIssuedAt:]
+ +[EXSSyncEngineInstance uptimeSeconds]
+ -[EXSDataConsumerInstance _consumer:wantsAnyOfChangeItems:pushedItemTypes:]
+ -[EXSDataManager _ensureChangeItemsUpsyncIndexWithDB:]
+ -[EXSDataManager(ChangeItems) _changeItemsSinceChangeID:maxCount:fetchBatch:]
+ -[EXSDataManager(ChangeItems) _getChangeItemsSinceChangeID:skippingChangeSourceID:maxCount:]
+ -[EXSDataManager(ChangeItems) getChangeItemsSinceChangeID:skippingChangeSourceID:maxCount:]
+ -[EXSDataManager(ChangeItems) lastChangeIDBeforeNextChangeItemOfTypes:sinceChangeID:skippingChangeSourceID:]
+ -[EXSDataManager(Folders) dropUnparentedItemsOfType:]
+ -[EXSDataManager(Items) updateItemsWithInternalIDsByExternalID:]
+ -[EXSEWSSyncProtocol calendarReadOnlyPendingFolderIDs]
+ -[EXSEWSSyncProtocol calendarReadOnlyRefreshAttempts]
+ -[EXSEWSSyncProtocol readOnlyChangeItemsForCalendarFolders:]
+ -[EXSEWSSyncProtocol refreshCalendarReadOnlyOncePerLaunch]
+ -[EXSEWSSyncProtocol setCalendarReadOnlyPendingFolderIDs:]
+ -[EXSEWSSyncProtocol setCalendarReadOnlyRefreshAttempts:]
+ -[EXSFolderProperties readOnlySpecified]
+ -[EXSFolderProperties readOnly]
+ -[EXSFolderProperties setReadOnly:]
+ -[EXSGSMigrationFailure releasedByReachabilityProbe]
+ -[EXSGSMigrationPausedSyncProtocol hostnameIsNotReachable:]
+ -[EXSGSMigrationPausedSyncProtocol hostnameIsReachable:]
+ -[EXSGSMigrationPausedSyncProtocol hostnames]
+ -[EXSGSMigrationPausedSyncProtocol prepareForShutdown]
+ -[EXSGSMigrationPausedSyncProtocol reachabilityWatchSuppressedForTesting]
+ -[EXSGSMigrationPausedSyncProtocol setReachabilityWatchSuppressedForTesting:]
+ -[EXSGSMigrationPausedSyncProtocol shutdown]
+ -[EXSGSMigrationPausedSyncProtocol syncProtocolIdentifier]
+ -[EXSGSMigrationPausedSyncProtocol systemWasWokenFromSleep]
+ -[EXSGSMigrationReachabilityProbe .cxx_destruct]
+ -[EXSGSMigrationReachabilityProbe _headProbeWithCompletion:]
+ -[EXSGSMigrationReachabilityProbe _probeForTrigger:onFailure:]
+ -[EXSGSMigrationReachabilityProbe _stopOnQueue]
+ -[EXSGSMigrationReachabilityProbe cancelPendingSettledProbe]
+ -[EXSGSMigrationReachabilityProbe cancel]
+ -[EXSGSMigrationReachabilityProbe dealloc]
+ -[EXSGSMigrationReachabilityProbe drainForTesting]
+ -[EXSGSMigrationReachabilityProbe initWithAccountKey:interval:prober:onReachable:]
+ -[EXSGSMigrationReachabilityProbe probeAfterSettleDelayReportingFailure:]
+ -[EXSGSMigrationReachabilityProbe probeNowReportingFailure:]
+ -[EXSGSMigrationReachabilityProbe setSettleDelay:]
+ -[EXSGSMigrationReachabilityProbe settleDelay]
+ -[EXSGSMigrationReachabilityProbe start]
+ -[EXSSyncEngine _lateRemovalActionForAccount:terminal:delegateAccount:]
+ -[EXSSyncEngine retryHeldGraphMigrationForInstance:]
+ -[EXSSyncEngine syncEngineInstanceReachabilityProbePassedForGraphMigration:]
+ -[EXSSyncEngine transitionEngineInstance:toProtocolKind:requiresGraphCutover:fromReachabilityProbe:]
+ -[EXSSyncEngineInstance _armCutoverReachabilityProbeForFailure:]
+ -[EXSSyncEngineInstance _cutoverReachabilityProbeDidPass:]
+ -[EXSSyncEngineInstance _cutoverRetryIsBackedOff]
+ -[EXSSyncEngineInstance _disarmCutoverReachabilityProbe]
+ -[EXSSyncEngineInstance _noteReachabilityForCutoverHold:]
+ -[EXSSyncEngineInstance _runCutoverHousekeepingPhaseReturningHoldFailure:probeEarned:]
+ -[EXSSyncEngineInstance cutoverReachabilityProbe]
+ -[EXSSyncEngineInstance markNextCutoverAsProbeEarned]
+ -[EXSSyncEngineInstance newCutoverReachabilityProbeWithInterval:onReachable:]
+ -[EXSSyncEngineInstance setCutoverReachabilityProbe:]
+ -[EXSSyncProtocol drainOutstandingChangeItemsOnWorkQueue]
+ -[EXSSyncProtocol prepareForImmediateSyncDownsync]
+ -[EXSSyncProtocol syncAllFolderItemsForGraphMigrationCutover]
+ GCC_except_table101
+ GCC_except_table105
+ GCC_except_table107
+ GCC_except_table109
+ GCC_except_table111
+ GCC_except_table113
+ GCC_except_table115
+ GCC_except_table117
+ GCC_except_table121
+ GCC_except_table125
+ GCC_except_table134
+ GCC_except_table156
+ GCC_except_table16
+ GCC_except_table30
+ GCC_except_table40
+ GCC_except_table58
+ GCC_except_table60
+ GCC_except_table62
+ GCC_except_table66
+ GCC_except_table68
+ GCC_except_table74
+ GCC_except_table76
+ GCC_except_table80
+ GCC_except_table86
+ GCC_except_table90
+ GCC_except_table99
+ _OBJC_CLASS_$_EXSGSHeartbeatLaunchCheckIn
+ _OBJC_CLASS_$_EXSGSMigrationReachabilityProbe
+ _OBJC_CLASS_$_EXSGSWebPushKeySweep
+ _OBJC_CLASS_$_EXSNotesChangeTokenPolicy
+ _OBJC_CLASS_$_NSHTTPURLResponse
+ _OBJC_CLASS_$_NSMutableURLRequest
+ _OBJC_CLASS_$_NSURLComponents
+ _OBJC_IVAR_$_EXSDataConsumerInstance._intakeQueued
+ _OBJC_IVAR_$_EXSEWSSyncProtocol._calendarReadOnlyPendingFolderIDs
+ _OBJC_IVAR_$_EXSEWSSyncProtocol._calendarReadOnlyRefreshAttempts
+ _OBJC_IVAR_$_EXSFolderProperties._readOnly
+ _OBJC_IVAR_$_EXSFolderProperties._readOnlySpecified
+ _OBJC_IVAR_$_EXSGSMigrationPausedSyncProtocol._reachabilityWatchSuppressed
+ _OBJC_IVAR_$_EXSGSMigrationReachabilityProbe._accountKey
+ _OBJC_IVAR_$_EXSGSMigrationReachabilityProbe._cancelled
+ _OBJC_IVAR_$_EXSGSMigrationReachabilityProbe._interval
+ _OBJC_IVAR_$_EXSGSMigrationReachabilityProbe._onReachable
+ _OBJC_IVAR_$_EXSGSMigrationReachabilityProbe._probeInFlight
+ _OBJC_IVAR_$_EXSGSMigrationReachabilityProbe._prober
+ _OBJC_IVAR_$_EXSGSMigrationReachabilityProbe._queue
+ _OBJC_IVAR_$_EXSGSMigrationReachabilityProbe._session
+ _OBJC_IVAR_$_EXSGSMigrationReachabilityProbe._settleDelay
+ _OBJC_IVAR_$_EXSGSMigrationReachabilityProbe._settleGeneration
+ _OBJC_IVAR_$_EXSGSMigrationReachabilityProbe._timer
+ _OBJC_IVAR_$_EXSSyncEngineInstance._cutoverReachabilityProbe
+ _OBJC_IVAR_$_EXSSyncEngineInstance._lastCutoverRetryUptime
+ _OBJC_IVAR_$_EXSSyncEngineInstance._nextCutoverProbeEarned
+ _OBJC_IVAR_$_EXSSyncEngineInstance._nextReachableReportMayProbe
+ _OBJC_IVAR_$_EXSSyncEngineInstance._spentCutoverArms
+ _OBJC_METACLASS_$_EXSGSHeartbeatLaunchCheckIn
+ _OBJC_METACLASS_$_EXSGSMigrationReachabilityProbe
+ _OBJC_METACLASS_$_EXSGSWebPushKeySweep
+ _OBJC_METACLASS_$_EXSNotesChangeTokenPolicy
+ _OUTLINED_FUNCTION_14
+ __CLASS_METHODS_EXSGSHeartbeatLaunchCheckIn
+ __CLASS_METHODS_EXSGSWebPushKeySweep
+ __DATA_EXSGSHeartbeatLaunchCheckIn
+ __DATA_EXSGSWebPushKeySweep
+ __DATA__TtC12ExchangeSync22EXSGSSharedCalendarIDs
+ __DATA__TtCC12ExchangeSync20EXSGSWebPushKeySweep5Latch
+ __DATA__TtCC12ExchangeSync23EXSGSWebPushCoordinatorP33_0973A609DC8FB4860A2F59A6D0105DD414CoalescingSlot
+ __INSTANCE_METHODS_EXSGSHeartbeatLaunchCheckIn
+ __INSTANCE_METHODS_EXSGSWebPushKeySweep
+ __IVARS__TtC12ExchangeSync22EXSGSSharedCalendarIDs
+ __IVARS__TtCC12ExchangeSync20EXSGSWebPushKeySweep5Latch
+ __IVARS__TtCC12ExchangeSync23EXSGSWebPushCoordinatorP33_0973A609DC8FB4860A2F59A6D0105DD414CoalescingSlot
+ __METACLASS_DATA_EXSGSHeartbeatLaunchCheckIn
+ __METACLASS_DATA_EXSGSWebPushKeySweep
+ __METACLASS_DATA__TtC12ExchangeSync22EXSGSSharedCalendarIDs
+ __METACLASS_DATA__TtCC12ExchangeSync20EXSGSWebPushKeySweep5Latch
+ __METACLASS_DATA__TtCC12ExchangeSync23EXSGSWebPushCoordinatorP33_0973A609DC8FB4860A2F59A6D0105DD414CoalescingSlot
+ __OBJC_$_CLASS_METHODS_EXSGSMigrationReachabilityProbe
+ __OBJC_$_CLASS_METHODS_EXSNotesChangeTokenPolicy
+ __OBJC_$_INSTANCE_METHODS_EXSGSMigrationReachabilityProbe
+ __OBJC_$_INSTANCE_VARIABLES_EXSGSMigrationPausedSyncProtocol
+ __OBJC_$_INSTANCE_VARIABLES_EXSGSMigrationReachabilityProbe
+ __OBJC_$_PROP_LIST_EXSGSMigrationPausedSyncProtocol
+ __OBJC_$_PROP_LIST_EXSGSMigrationReachabilityProbe
+ __OBJC_CLASS_PROTOCOLS_$_EXSGSMigrationPausedSyncProtocol
+ __OBJC_CLASS_RO_$_EXSGSMigrationReachabilityProbe
+ __OBJC_CLASS_RO_$_EXSNotesChangeTokenPolicy
+ __OBJC_METACLASS_RO_$_EXSGSMigrationReachabilityProbe
+ __OBJC_METACLASS_RO_$_EXSNotesChangeTokenPolicy
+ ___100-[EXSSyncEngine transitionEngineInstance:toProtocolKind:requiresGraphCutover:fromReachabilityProbe:]_block_invoke
+ ___100-[EXSSyncEngine transitionEngineInstance:toProtocolKind:requiresGraphCutover:fromReachabilityProbe:]_block_invoke_2
+ ___108-[EXSDataManager(ChangeItems) lastChangeIDBeforeNextChangeItemOfTypes:sinceChangeID:skippingChangeSourceID:]_block_invoke
+ ___38+[EXSGSMigrationReachabilityProbe log]_block_invoke
+ ___40-[EXSGSMigrationReachabilityProbe start]_block_invoke
+ ___40-[EXSGSMigrationReachabilityProbe start]_block_invoke_2
+ ___41-[EXSGSMigrationReachabilityProbe cancel]_block_invoke
+ ___50-[EXSGSMigrationReachabilityProbe drainForTesting]_block_invoke
+ ___53-[EXSDataManager(Folders) dropUnparentedItemsOfType:]_block_invoke
+ ___57-[EXSSyncEngineInstance _noteReachabilityForCutoverHold:]_block_invoke
+ ___60-[EXSGSMigrationReachabilityProbe _headProbeWithCompletion:]_block_invoke
+ ___60-[EXSGSMigrationReachabilityProbe cancelPendingSettledProbe]_block_invoke
+ ___60-[EXSGSMigrationReachabilityProbe probeNowReportingFailure:]_block_invoke
+ ___62-[EXSGSMigrationReachabilityProbe _probeForTrigger:onFailure:]_block_invoke
+ ___62-[EXSGSMigrationReachabilityProbe _probeForTrigger:onFailure:]_block_invoke_2
+ ___64-[EXSDataManager(Items) updateItemsWithInternalIDsByExternalID:]_block_invoke
+ ___64-[EXSDataManager(Items) updateItemsWithInternalIDsByExternalID:]_block_invoke_2
+ ___64-[EXSDataManager(Items) updateItemsWithInternalIDsByExternalID:]_block_invoke_3
+ ___64-[EXSSyncEngineInstance _armCutoverReachabilityProbeForFailure:]_block_invoke
+ ___73-[EXSGSMigrationReachabilityProbe probeAfterSettleDelayReportingFailure:]_block_invoke
+ ___76-[EXSSyncEngine syncEngineInstanceReachabilityProbePassedForGraphMigration:]_block_invoke
+ ___91-[EXSDataManager(ChangeItems) getChangeItemsSinceChangeID:skippingChangeSourceID:maxCount:]_block_invoke
+ ___92-[EXSDataManager(ChangeItems) _getChangeItemsSinceChangeID:skippingChangeSourceID:maxCount:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24l
+ ___block_descriptor_40_e8_32w_e41_v16?0"EXSGSMigrationReachabilityProbe"8l
+ ___block_descriptor_40_e8_32w_e5_v8?0l
+ ___block_descriptor_48_e8_32r40r_e12_v24?0Q8^B16l
+ ___block_descriptor_48_e8_32s40r_e35_v32?0"NSString"8"NSString"16^B24l
+ ___block_descriptor_48_e8_32s40w_e5_v8?0l
+ ___block_descriptor_56_e8_32bs40w_e5_v8?0l
+ ___block_descriptor_56_e8_32s40s48bs_e8_v12?0B8l
+ ___block_descriptor_57_e8_32s40s48bs_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48r56r_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48r_e5_v8?0l
+ ___copy_helper_block_e8_32b40w
+ ___copy_helper_block_e8_32s40w
+ ___destroy_helper_block_e8_32s40w
+ ___swift_memcpy168_8
+ __dispatch_source_type_timer
+ _arc4random_uniform
+ _associated conformance 12ExchangeSync20EXSGSPassUpsyncOrderOSHAASQ
+ _associated conformance 12ExchangeSync21EXSGSWebPushRecordKeyV4KindOSHAASQ
+ _associated conformance 12ExchangeSync21EXSGSWebPushRecordKeyV4KindOSLAASQ
+ _associated conformance 12ExchangeSync22EXSGSDownsyncAdmissionOSHAASQ
+ _associated conformance 12ExchangeSync23EXSGSListTierCursorDropOSHAASQ
+ _associated conformance 12ExchangeSync27EXSGSWebPushFolderHierarchyV6ActionOSHAASQ
+ _associated conformance 12ExchangeSync40EXSGSAddCalendarEventAttachmentOperationVAA012EXSGSChunkedf6UploadG0AA0I14SessionRequestAaDP_05GraphB00lB11Requestable
+ _dispatch_resume
+ _dispatch_source_cancel
+ _dispatch_source_create
+ _dispatch_source_set_event_handler
+ _dispatch_source_set_timer
+ _get_enum_tag_for_layout_string 12ExchangeSync24EXSGSPushDownsyncRequestVSg
+ _get_enum_tag_for_layout_string 12ExchangeSync28EXSGSWebPushCoalescingWindowV7ClosingO
+ _get_enum_tag_for_layout_string s5Error_pIegzo_Sg
+ _objc_msgSend$PropertyTag
+ _objc_msgSend$URL
+ _objc_msgSend$_armCutoverReachabilityProbeForFailure:
+ _objc_msgSend$_changeItemsSinceChangeID:maxCount:fetchBatch:
+ _objc_msgSend$_consumer:wantsAnyOfChangeItems:pushedItemTypes:
+ _objc_msgSend$_cutoverReachabilityProbeDidPass:
+ _objc_msgSend$_cutoverRetryIsBackedOff
+ _objc_msgSend$_disarmCutoverReachabilityProbe
+ _objc_msgSend$_ensureChangeItemsUpsyncIndexWithDB:
+ _objc_msgSend$_getChangeItemsSinceChangeID:skippingChangeSourceID:maxCount:
+ _objc_msgSend$_headProbeWithCompletion:
+ _objc_msgSend$_lateRemovalActionForAccount:terminal:delegateAccount:
+ _objc_msgSend$_noteReachabilityForCutoverHold:
+ _objc_msgSend$_probeForTrigger:onFailure:
+ _objc_msgSend$_runCutoverHousekeepingPhaseReturningHoldFailure:probeEarned:
+ _objc_msgSend$_stopOnQueue
+ _objc_msgSend$_sweepStaleWebPushKeysForACAccounts:delegateKeysByAccount:syncingAccounts:
+ _objc_msgSend$calendarFolderIsReadOnly:known:
+ _objc_msgSend$calendarReadOnlyPendingFolderIDs
+ _objc_msgSend$calendarReadOnlyRefreshAttempts
+ _objc_msgSend$cancel
+ _objc_msgSend$cancelPendingSettledProbe
+ _objc_msgSend$checkIn
+ _objc_msgSend$closeAndReturnError:
+ _objc_msgSend$cutoverReachabilityProbe
+ _objc_msgSend$defaultSettleDelay
+ _objc_msgSend$drainOutstandingChangeItemsOnWorkQueue
+ _objc_msgSend$dropUnparentedItemsOfType:
+ _objc_msgSend$enumerateIndexesUsingBlock:
+ _objc_msgSend$fileHandleForReadingFromURL:error:
+ _objc_msgSend$getChangeItemsSinceChangeID:skippingChangeSourceID:maxCount:
+ _objc_msgSend$graphReachabilityHostname
+ _objc_msgSend$initWithAccountKey:interval:prober:onReachable:
+ _objc_msgSend$intervalAfterSpentArms:
+ _objc_msgSend$lastChangeIDBeforeNextChangeItemOfTypes:sinceChangeID:skippingChangeSourceID:
+ _objc_msgSend$markNextCutoverAsProbeEarned
+ _objc_msgSend$maxChangeItemsPerPush
+ _objc_msgSend$newCutoverReachabilityProbeWithInterval:onReachable:
+ _objc_msgSend$prepareForImmediateSyncDownsync
+ _objc_msgSend$probeAfterSettleDelayReportingFailure:
+ _objc_msgSend$pushedItemTypes
+ _objc_msgSend$reachabilityWatchSuppressedForTesting
+ _objc_msgSend$readOnlyChangeItemsForCalendarFolders:
+ _objc_msgSend$readOnlySpecified
+ _objc_msgSend$refreshCalendarReadOnlyOncePerLaunch
+ _objc_msgSend$releasedByReachabilityProbe
+ _objc_msgSend$repushesPartlyAppliedBatchesSafely
+ _objc_msgSend$responseShowsPathOpen:
+ _objc_msgSend$retryHeldGraphMigrationForInstance:
+ _objc_msgSend$seekToOffset:error:
+ _objc_msgSend$setBool:forKey:
+ _objc_msgSend$setCalendarReadOnlyPendingFolderIDs:
+ _objc_msgSend$setCalendarReadOnlyRefreshAttempts:
+ _objc_msgSend$setCutoverReachabilityProbe:
+ _objc_msgSend$setHTTPMethod:
+ _objc_msgSend$setHost:
+ _objc_msgSend$setRequestCachePolicy:
+ _objc_msgSend$setScheme:
+ _objc_msgSend$setTimeoutIntervalForRequest:
+ _objc_msgSend$setTimeoutIntervalForResource:
+ _objc_msgSend$settleDelay
+ _objc_msgSend$statusCode
+ _objc_msgSend$sweepStaleKeysWithAcAccountIdentifiers:delegateKeys:syncingAccountKeys:
+ _objc_msgSend$syncAllFolderItemsForGraphMigrationCutover
+ _objc_msgSend$syncEngineInstanceReachabilityProbePassedForGraphMigration:
+ _objc_msgSend$transitionEngineInstance:toProtocolKind:requiresGraphCutover:fromReachabilityProbe:
+ _objc_msgSend$unregisterIfNoAccountJoined
+ _objc_msgSend$uptimeSeconds
+ _symbolic $s12ExchangeSync37EXSGSChunkedAttachmentUploadOperationP
+ _symbolic 20UploadSessionRequest_____Qz 12ExchangeSync37EXSGSChunkedAttachmentUploadOperationP
+ _symbolic SDySS_____G 12ExchangeSync19EXSWebPushTransportC14CachedEndpoint33_F599398DB63F31C565EB854B8922C17DLLV
+ _symbolic SDy__________G 12ExchangeSync21EXSGSWebPushDataClassO AA0cD11CoordinatorC14CoalescingSlot33_0973A609DC8FB4860A2F59A6D0105DD4LLC
+ _symbolic SDy__________G 12ExchangeSync21EXSGSWebPushDataClassO AA0cD11CoordinatorC14PinnedEndpoint33_0973A609DC8FB4860A2F59A6D0105DD4LLV
+ _symbolic SaySiG
+ _symbolic SbyYbc
+ _symbolic ShySSGyKc
+ _symbolic Si9attempted_t
+ _symbolic _____ 12ExchangeSync19EXSWebPushTransportC14CachedEndpoint33_F599398DB63F31C565EB854B8922C17DLLV
+ _symbolic _____ 12ExchangeSync20EXSGSPassUpsyncOrderO
+ _symbolic _____ 12ExchangeSync20EXSGSWebPushKeySweepC
+ _symbolic _____ 12ExchangeSync20EXSGSWebPushKeySweepC5LatchC
+ _symbolic _____ 12ExchangeSync20EXSGSWebPushKeySweepC7OutcomeO
+ _symbolic _____ 12ExchangeSync21EXSGSWebPushRecordKeyV4KindO
+ _symbolic _____ 12ExchangeSync22EXSGSDownsyncAdmissionO
+ _symbolic _____ 12ExchangeSync22EXSGSSharedCalendarIDsC
+ _symbolic _____ 12ExchangeSync23EXSGSListTierCursorDropO
+ _symbolic _____ 12ExchangeSync23EXSGSWebPushCoordinatorC14CoalescingSlot33_0973A609DC8FB4860A2F59A6D0105DD4LLC
+ _symbolic _____ 12ExchangeSync23EXSGSWebPushCoordinatorC14PinnedEndpoint33_0973A609DC8FB4860A2F59A6D0105DD4LLV
+ _symbolic _____ 12ExchangeSync25EXSGSSharedCalendarsQueryO
+ _symbolic _____ 12ExchangeSync27EXSGSHeartbeatLaunchCheckInC
+ _symbolic _____ 12ExchangeSync27EXSGSWebPushFolderHierarchyV
+ _symbolic _____ 12ExchangeSync27EXSGSWebPushFolderHierarchyV6ActionO
+ _symbolic _____ 12ExchangeSync28EXSGSWebPushCoalescingWindowV
+ _symbolic _____ 12ExchangeSync28EXSGSWebPushCoalescingWindowV7ClosingO
+ _symbolic _____ 12ExchangeSync28EXSGSWebPushCoalescingWindowV9AdmissionO
+ _symbolic _____ 12ExchangeSync31EXSGSHeartbeatStaleRecordMarkerV
+ _symbolic _____ 9GraphSync0aB49CalendarEventCreateAttachmentUploadSessionRequestV
+ _symbolic _____10generation_t s6UInt64V
+ _symbolic _____3key______2att 10Foundation4DataV AA4DateV
+ _symbolic _____3key______2attSg 10Foundation4DataV AA4DateV
+ _symbolic _____3key______5valuet 12ExchangeSync21EXSGSWebPushRecordKeyV4KindO AA0cd12SubscriptionE0V
+ _symbolic _____6config______6budgett 12ExchangeSync16EXSGSRetryPolicyO6ConfigV AC6BudgetC
+ _symbolic _____Sg 12ExchangeSync22EXSGSSharedCalendarIDsC
+ _symbolic _____Sg 12ExchangeSync23EXSGSBoundedTransactionC
+ _symbolic _____Sg 12ExchangeSync24EXSGSPushDownsyncRequestV
+ _symbolic _____Sg 9GraphSync0aB16ResponseMetadataV
+ _symbolic _____Sg 9GraphSync0aB21UploadSessionResourceV
+ _symbolic _____Sg 9GraphSync0aB22UploadProgressResourceV
+ _symbolic _____Sg_ABt 12ExchangeSync30EXSGSWebPushSubscriptionRecordV
+ _symbolic _____XDXMT 12ExchangeSync22EXSGSSharedCalendarIDsC
+ _symbolic ______Si6merged_____10generationt 12ExchangeSync24EXSGSPushDownsyncRequestV s6UInt64V
+ _symbolic ___________t 12ExchangeSync21EXSGSWebPushDataClassO AA0cD11CoordinatorC14PinnedEndpoint33_0973A609DC8FB4860A2F59A6D0105DD4LLV
+ _symbolic ___________t 12ExchangeSync21EXSGSWebPushRecordKeyV4KindO AA0cd12SubscriptionE0V
+ _symbolic _____ySS_____G s18_DictionaryStorageC 12ExchangeSync19EXSWebPushTransportC14CachedEndpoint33_F599398DB63F31C565EB854B8922C17DLLV
+ _symbolic _____yShySSG______pGSg s6ResultOsRi_zRi0_zrlE s5ErrorP
+ _symbolic _____y_____3key______5valuetG s23_ContiguousArrayStorageC 12ExchangeSync21EXSGSWebPushRecordKeyV4KindO AC0fg12SubscriptionH0V
+ _symbolic _____y_____G s11_SetStorageC 12ExchangeSync21EXSGSWebPushRecordKeyV4KindO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12ExchangeSync21EXSGSWebPushRecordKeyV4KindO
+ _symbolic _____y__________G s18_DictionaryStorageC 12ExchangeSync21EXSGSWebPushDataClassO AC0eF11CoordinatorC14CoalescingSlot33_0973A609DC8FB4860A2F59A6D0105DD4LLC
+ _symbolic _____y__________G s18_DictionaryStorageC 12ExchangeSync21EXSGSWebPushDataClassO AC0eF11CoordinatorC14PinnedEndpoint33_0973A609DC8FB4860A2F59A6D0105DD4LLV
+ _symbolic _____y__________G s18_DictionaryStorageC 12ExchangeSync21EXSGSWebPushRecordKeyV4KindO AC0ef12SubscriptionG0V
+ _symbolic _____y___________tG s23_ContiguousArrayStorageC 12ExchangeSync21EXSGSWebPushRecordKeyV4KindO AC0fg12SubscriptionH0V
+ _symbolic yyKcSg
+ _symbolic yyYbc
+ _type_layout_string 12ExchangeSync19EXSWebPushTransportC14CachedEndpoint33_F599398DB63F31C565EB854B8922C17DLLV
+ _type_layout_string 12ExchangeSync23EXSGSWebPushCoordinatorC14PinnedEndpoint33_0973A609DC8FB4860A2F59A6D0105DD4LLV
+ _type_layout_string 12ExchangeSync27EXSGSWebPushFolderHierarchyV
+ _type_layout_string 12ExchangeSync28EXSGSWebPushCoalescingWindowV
+ _type_layout_string 12ExchangeSync28EXSGSWebPushCoalescingWindowV7ClosingO
+ _type_layout_string 12ExchangeSync31EXSGSHeartbeatStaleRecordMarkerV
+ _type_layout_string SSSg
+ _xpc_activity_should_defer
- -[EXSDataConsumerInstance _consumer:wantsAnyOfChangeItems:]
- -[EXSDataManager(ChangeItems) _changeItemsSinceChangeID:shouldBatch:fetchBatch:]
- -[EXSSyncEngineInstance _runCutoverHousekeepingPhase]
- GCC_except_table100
- GCC_except_table102
- GCC_except_table104
- GCC_except_table106
- GCC_except_table108
- GCC_except_table110
- GCC_except_table112
- GCC_except_table114
- GCC_except_table116
- GCC_except_table120
- GCC_except_table124
- GCC_except_table133
- GCC_except_table153
- GCC_except_table20
- GCC_except_table26
- GCC_except_table36
- GCC_except_table42
- GCC_except_table55
- GCC_except_table69
- GCC_except_table73
- GCC_except_table82
- GCC_except_table87
- GCC_except_table88
- GCC_except_table91
- GCC_except_table98
- ___78-[EXSSyncEngine transitionEngineInstance:toProtocolKind:requiresGraphCutover:]_block_invoke
- ___94-[EXSDataManager(ChangeItems) getChangeItemsSinceChangeID:skippingChangeSourceID:shouldBatch:]_block_invoke
- ___95-[EXSDataManager(ChangeItems) _getChangeItemsSinceChangeID:skippingChangeSourceID:shouldBatch:]_block_invoke
- ___block_descriptor_65_e8_32s40s48r_e5_v8?0l
- ___swift_memcpy144_8
- ___swift_memcpy72_8
- _generic environment l
- _objc_msgSend$_changeItemsSinceChangeID:shouldBatch:fetchBatch:
- _objc_msgSend$_consumer:wantsAnyOfChangeItems:
- _objc_msgSend$_getChangeItemsSinceChangeID:skippingChangeSourceID:shouldBatch:
- _objc_msgSend$_runCutoverHousekeepingPhase
- _swift_getAtKeyPath
- _swift_getKeyPath
- _symbolic SDySS_____G 12ExchangeSync18EXSWebPushEndpointV
- _symbolic SDy__________G 12ExchangeSync21EXSGSWebPushDataClassO AA06EXSWebD8EndpointV
- _symbolic SS11requestedID______8resourcet 9GraphSync0aB22CalendarFolderResourceV
- _symbolic SS11requestedID_x8resourcet
- _symbolic SaySS11requestedID_x8resourcetG
- _symbolic So11NSConditionC
- _symbolic _____ySS3key______5valuetG s23_ContiguousArrayStorageC 12ExchangeSync30EXSGSWebPushSubscriptionRecordV
- _symbolic _____ySS_____G s18_DictionaryStorageC 12ExchangeSync18EXSWebPushEndpointV
- _symbolic _____y__________G s18_DictionaryStorageC 12ExchangeSync21EXSGSWebPushDataClassO AC06EXSWebF8EndpointV
CStrings:
+ " (next expected "
+ " instead of upload progress"
+ "$batch %{public}s throttled (HTTP 429, or 503 with Retry-After) on %ld sub-request(s) (Retry-After=%{public}s attempt=%{public}ld op=%{public}s); over inline budget or retries exhausted"
+ "$batch %{public}s throttled (HTTP 429, or 503 with Retry-After) on %ld sub-request(s) (Retry-After=%{public}s attempt=%{public}ld op=%{public}s); waiting %{public}.*fs then retrying just those"
+ "$batch %{public}s throttled on %ld sub-request(s) (Retry-After=%{public}s attempt=%{public}ld op=%{public}s); not retrying, the throttle gate is closed"
+ "%{public}s: could not keep the refreshed changeKey for %{public}s; the next delta may skip the merged item"
+ "-byte upload limit"
+ "/"
+ "0x36DA"
+ "An APS endpoint request for this topic is already in flight"
+ "Attachment '%{private}s' is %ld bytes — exceeds the %ld-byte maximum Graph accepts by any path"
+ "Attachment file could not be opened for chunked upload, skipping"
+ "Attachment file is %{public}ld bytes on disk — exceeds the %{public}ld-byte maximum Graph accepts"
+ "Attachment file is empty, skipping chunked upload"
+ "Attachment file is shorter than the declared size (read "
+ "Attachment is %{public}ld bytes on a delegated or shared mailbox — large attachments are unsupported there (Microsoft known issue 13644); refusing at the %{public}ld-byte single-request limit"
+ "Attachment size on disk (%{public}ld) differs from the change item's (%{public}ld); using the file"
+ "CREATE INDEX IF NOT EXISTS exs_change_items_upsync_idx ON exs_change_items (change_id) WHERE change_source_id GLOB 'DataConsumer-*'"
+ "Calendar read-only refresh: %lu of %lu calendar folders resolved"
+ "Calendar read-only refresh: attempt %lu failed: %{public}@"
+ "Calendar read-only refresh: could not persist %lu change items"
+ "Calendar's round sat out the throttle window"
+ "Chunked attachment upload complete, server ID: %{public}s"
+ "Chunked attachment upload ended at %{public}ld bytes without a completing range, after %{public}ld range(s)"
+ "Chunked attachment upload failed at offset %{public}ld of %{public}ld after %{public}ld range(s) and %{public}.*fs"
+ "Chunked attachment upload finished — %{public}ld bytes in %{public}ld range(s) over %{public}.*fs"
+ "Chunked attachment upload starting — %{public}ld bytes in ~%{public}ld range(s) from offset %{public}ld, delegated=%{bool,public}d"
+ "Chunked attachment upload stopped by the reachability gate at offset %{public}ld of %{public}ld after %{public}ld range(s) and %{public}.*fs"
+ "Completed upload session returned no usable Location header"
+ "Could not measure attachment file length"
+ "Could not read attachment range at "
+ "Couldn't create change items upsync index in sync engine database: %{public}@ %ld"
+ "Create Attachment Upload Session"
+ "DELETE FROM exs_items WHERE account_id=%ld AND folder_id=%ld AND item_type=%ld"
+ "EXSGSHeartbeatStaleRecordCleared"
+ "EXSGSMigrationReachabilityProbe"
+ "EXSSyncEngine: Graph host is answering for account %{public}@, retrying the Graph migration cutover."
+ "EXSSyncEngine: Graph migration retry for account %{public}@ still resolves to the paused protocol; nothing to change."
+ "EXSSyncEngine: declining the Graph migration retry for account %{public}@ -- the daemon is shutting down."
+ "EXSSyncEngine: declining the Graph migration retry for account %{public}@ -- the instance is no longer the one held on the paused protocol."
+ "EXSSyncEngine: honoring a removal deferred during a declined Graph migration retry for account %{public}@."
+ "EXSSyncEngine: not transitioning account %{public}@ -- it was removed, replaced or no longer paused after the transition was decided."
+ "ErrorAccessDenied"
+ "ErrorMessageSizeExceeded"
+ "Expected GraphSyncUploadSessionResource but received "
+ "Failed to find the declined change items past %ld: %{public}@"
+ "Graph Sync: %{public}s not retrying; the throttle gate is closed"
+ "Graph Sync: calendar folder id canonicalization for account %{public}s failed on folder %{public}ld of %{public}ld, %{public}s %{public}ld requestID=%{public}s; cutover housekeeping will retry next startup"
+ "Graph Sync: calendar folder id canonicalization for account %{public}s got no calendar id for folder %{public}ld of %{public}ld; cutover housekeeping will retry next startup"
+ "Graph Sync: dropping the %{public}s delta cursor for %{public}s, the next round re-seeds - account %{public}s"
+ "Graph Sync: failed to drop the %{public}s delta cursor for %{public}s; that tier stays diverged locally"
+ "Graph Sync: fetched %{public}ld shared calendar ids"
+ "Graph Sync: heartbeat activity handler state=%{public}ld"
+ "Graph Sync: heartbeat activity handler state=%{public}ld shouldDefer=%{bool,public}d"
+ "Graph Sync: heartbeat scheduler clearing a prior activity record"
+ "Graph Sync: heartbeat scheduler exiting with no account, dropping the activity"
+ "Graph Sync: holding the surfaced sync state; %{public}s"
+ "Graph Sync: not surfacing Calendar's %{public}s (retryAfter=%{public}s)"
+ "Graph Sync: push aborted — %{public}s"
+ "Graph Sync: push aborted — offline"
+ "Graph Sync: push aborted — offline (request failed while reachable) change=%{public}ld holds=%{public}ld"
+ "Graph Sync: repush dropped the calendar folder delta cursor, the next calendar folder round re-seeds"
+ "Graph Sync: repush failed to drop the calendar folder delta cursor; calendar colors and read-only stay at defaults"
+ "Graph Sync: shared calendar id fetch failed, failing the calendar folder round - %{public}s requestID=%{public}s"
+ "Graph Sync: shared calendar ids read before hydrate fetched them"
+ "Graph Sync: skipping meeting-request lookup; the event GET failed for lack of a usable network"
+ "Graph Sync: upsync ahead of downsync reason=%{public}s drained=%{public}s account=%{public}s"
+ "Graph Sync: upsync ahead of downsync reason=%{public}s drained=aborted skipped=offlinePendingUpsync account=%{public}s"
+ "Graph host answered a probe for account %{public}@ but there is no engine to retry the Graph migration cutover."
+ "Graph host answered a probe for account %{public}@ held on the paused protocol -- asking the engine to retry the cutover."
+ "Graph host reported %{public}s for account %{public}@, held waiting on the reachability probe."
+ "Graph host reported reachable for account %{public}@, but an earlier retry is still inside its backoff window; leaving it to the timer."
+ "Graph migration cutover housekeeping for account %{public}@ failed on a retry earned by a reachability probe: reason=%ld. Holding without charging."
+ "Graph migration hold for account %{public}@: reason=%ld, not waiting on the network, will retry on the next launch or account change."
+ "Graph migration hold for account %{public}@: reason=%ld, will retry cutover housekeeping when the Graph host answers a probe (every %.0f s, %lu earlier retries spent)."
+ "Graph migration reachability probe for account %{public}@ (trigger=%{public}@): %{public}s."
+ "Graph migration reachability probe for account %{public}@ will probe in %.0f s, once the network settles."
+ "HEAD"
+ "IPF.Appointment.Birthday"
+ "Ignoring a reachability probe result for account %{public}@ from a probe that is no longer the armed one."
+ "Invalid server response: $batch hydration sub-request failed with HTTP "
+ "Move skipped — attachment of %{public}ld bytes exceeds the %{public}ld-byte copy limit; moving would delete it (rdar://190043384)."
+ "Move skipped — event has attachments and the source calendar is unknown, so the copy would drop all of them (rdar://190043384)."
+ "Non-final upload chunk at offset "
+ "Paused protocol for account %{public}@ is watching Graph reachability."
+ "Paused protocol for account %{public}@ stopped watching Graph reachability."
+ "Paused protocol for account %{public}@: Graph host is not reachable."
+ "Paused protocol for account %{public}@: Graph host is reachable."
+ "Push aborted — offline"
+ "Reachability probe passed for account %{public}@ but its protocol kind is %ld, not paused; nothing to retry."
+ "ReadOnly"
+ "SELECT 1 FROM exs_change_items WHERE account_id=%ld AND change_id > %ld AND change_source_id GLOB 'DataConsumer-*' LIMIT 1"
+ "SELECT 1 FROM exs_change_items WHERE account_id=%ld AND internal_itemID=%@ AND item_type=%ld AND change_type=%ld AND change_id > %ld AND IFNULL(isDetached, 0)=0 AND change_source_id GLOB 'DataConsumer-*' LIMIT 1"
+ "SELECT COALESCE(MIN(CASE WHEN change_source_id GLOB 'DataConsumer-*' THEN change_id END) - 1, MAX(change_id), 0) FROM exs_change_items WHERE account_id=%ld AND change_id > %ld"
+ "SELECT DISTINCT external_itemID FROM exs_change_items WHERE account_id=%ld AND item_type=%ld AND change_source_id GLOB 'DataConsumer-*' AND external_itemID IS NOT NULL AND external_itemID != '' AND change_id > COALESCE((SELECT last_change_item_id FROM exs_change_sources WHERE account_id=%ld AND change_source_id=%@), 0)"
+ "SELECT IFNULL(MAX(change_id), %ld) FROM exs_change_items WHERE account_id=%ld AND change_id > %ld AND change_source_id != %@ AND change_id < IFNULL((SELECT MIN(change_id) FROM exs_change_items WHERE account_id=%ld AND change_id > %ld AND change_source_id != %@ AND ((1 << item_type) & %ld) != 0), %ld)"
+ "SELECT change_id, account_id, item_type, change_type, change_source_id, modification_dt, item_id, external_itemID, external_changeKey, external_parentFolderID, internal_itemID, internal_changeKey, internal_parentFolderID, shouldSendNotification, eventHasAttendees, isDetached, parentExternalID, parentInternalID, instanceIndex, properties_blob FROM exs_change_items WHERE account_id=%ld AND change_id > %ld AND change_source_id GLOB 'DataConsumer-*' ORDER BY change_id LIMIT %ld"
+ "SELECT external_itemID, external_changeKey FROM exs_items WHERE account_id=%ld AND external_itemID IN (SELECT value FROM json_each(%@)) AND (folder_id IS NULL OR folder_id NOT IN (SELECT folder_id FROM exs_folders WHERE account_id=%ld AND marked_as_deleted=1)) ORDER BY (internal_itemID IS NULL OR internal_itemID = '') ASC, item_id DESC"
+ "Shared calendar list exceeded "
+ "TestWebPushEnabled"
+ "UPDATE exs_change_items SET external_itemID=%@, external_changeKey=%@ WHERE account_id=%ld AND internal_itemID=%@ AND item_type=%ld AND change_type=%ld AND change_id > %ld AND IFNULL(isDetached, 0)=0 AND (external_itemID IS NULL OR external_itemID='') AND change_source_id GLOB 'DataConsumer-*' AND NOT EXISTS (SELECT 1 FROM exs_items WHERE account_id=%ld AND internal_itemID=%@)"
+ "Upload Attachment Chunk"
+ "Upload session did not advance past offset "
+ "Upload session ended without completing the final range"
+ "Upload session refused with 403. Large attachments are not supported on a shared or delegated mailbox (Microsoft known issue 13644); the attachment will not sync."
+ "Uploading attachment chunk %{public}ld of ~%{public}ld (%{public}ld bytes at %{public}ld of %{public}ld)"
+ "Web Push: VAPID key refetch returned the key Graph rejected; keeping it, no refetch for %{public}ld min"
+ "[EXSDataConsumerInstance processChangesSinceLastSync] -- Coalesced, an intake is already queued"
+ "an inactive Calendar data class with no calendar left locally"
+ "com.apple.exchangesync.migration.reachability-probe"
+ "com.apple.exchangesync.webpush.coalesce."
+ "dropUnparentedItemsOfType: Error while dropping items in sync engine database: %{public}@"
+ "dropUnparentedItemsOfType: dropped %lld item(s) of type %ld with no parent folder"
+ "edge"
+ "folderHierarchy"
+ "folders"
+ "graphMigrationCutover"
+ "https"
+ "largeAttachment"
+ "not reachable"
+ "not reachable, will probe again later"
+ "reachability gate invalidated"
+ "reachable"
+ "status requestID "
+ "timer"
+ "v12@?0B8"
+ "v16@?0@\"EXSGSMigrationReachabilityProbe\"8"
+ "v24@?0Q8^B16"
+ "v32@?0@\"NSString\"8@\"NSString\"16^B24"
+ "webpush stage=0 enabled=%{public}s previous=%{public}s account=%{public}s"
+ "webpush stage=1 keySweep held=%{public}ld live=%{public}ld purgeAttempted=%{public}ld"
+ "webpush stage=1 keySweep skipped=noAccounts"
+ "webpush stage=1 keySweep skipped=storeUnreadable"
+ "webpush stage=10a coalesced dataClass=%{public}s pending=%{public}s count=%{public}ld account=%{public}s"
+ "webpush stage=10c coalescing closed dataClass=%{public}s merged=%{public}ld followUp=yes account=%{public}s"
+ "webpush stage=10c coalescing closed dataClass=%{public}s merged=0 followUp=no account=%{public}s"
+ "webpush stage=10c coalescing dropped dataClass=%{public}s reason=%{public}s account=%{public}s"
+ "webpush stage=4 apsTokenRequested failed=inFlightForDifferentVapidKey topic=%{private}@"
+ "webpush stage=4 apsTokenRequested rerequested=vapidKeyChanged topic=%{private}@"
+ "webpush stage=4 apsTokenRequested reused=%{public}@ topic=%{private}@"
+ "webpush stage=5 endpointChanged dataClass=%{public}s markedForReplacement=%{public}ld account=%{public}s"
+ "webpush stage=7 vapidKeyInvalidated dataClass=%{public}s rejectedCreates=%{public}ld account=%{public}s"
+ "webpush stage=7 vapidKeyRejected keyKept=yes dataClass=%{public}s rejectedCreates=%{public}ld account=%{public}s"
+ "wholeClass"
+ "\xa1!"
- "$batch %{public}s throttled (HTTP 429, or 503 with Retry-After) on %ld sub-request(s); over inline budget or retries exhausted"
- "$batch %{public}s throttled (HTTP 429, or 503 with Retry-After) on %ld sub-request(s); waiting %{public}.*fs then retrying just those"
- "$batch %{public}s throttled on %ld sub-request(s); not retrying, the throttle gate just closed"
- "$batch hydration sub-request failed with HTTP "
- "-byte single-request upload limit"
- "Conflict changeKey refresh for %{public}s found the note soft-deleted — declining the retry"
- "Graph Sync: %{public}s not retrying; the throttle gate just closed"
- "Graph Sync: calendar folder id canonicalization for account %{public}s could not resolve %{public}ld of %{public}ld folder(s) in a batch (%{public}ld empty-bodied, %{public}ld dropped); cutover housekeeping will retry next startup"
- "Graph Sync: calendar folder id canonicalization for account %{public}s failed for a batch of %{public}ld folder(s), %{public}s %{public}ld requestID=%{public}s; cutover housekeeping will retry next startup"
- "Graph Sync: calendar folder id canonicalization for account %{public}s got a calendar with no id; cutover housekeeping will retry next startup"
- "Graph Sync: dropping the task-list delta cursor for %{public}s, the next round re-seeds - account %{public}s"
- "Graph Sync: failed to drop the task-list delta cursor for %{public}s; the distinguished Tasks list stays diverged locally"
- "Graph Sync: holding the surfaced sync state; Calendar's round sat out the throttle window"
- "Graph Sync: not surfacing Calendar's short throttle (retryAfter=%{public}s)"
- "GraphHeartbeatBackstopMinutes"
- "GraphHeartbeatIgnorePush"
- "GraphHeartbeatPushCoveredIntervalMinutes"
- "GraphHeartbeatPushHealthyWindowMinutes"
- "GraphHeartbeatWaitCapMinutes"
- "GraphPollingDelayMinutes"
- "GraphPollingGracePeriodMinutes"
- "GraphWebPushEnabled"
- "Move attachment copy — listing source attachments failed (%{private}s); moving without attachments"
- "Move attachment copy — source calendar unknown; moving without attachments"
- "SELECT 1 FROM exs_change_items WHERE account_id=%ld AND change_id > %ld AND change_source_id GLOB %@ LIMIT 1"
- "SELECT 1 FROM exs_change_items WHERE account_id=%ld AND internal_itemID=%@ AND item_type=%ld AND change_type=%ld AND change_id > %ld AND IFNULL(isDetached, 0)=0 AND change_source_id GLOB %@ LIMIT 1"
- "SELECT COALESCE(MIN(CASE WHEN change_source_id GLOB %@ THEN change_id END) - 1, MAX(change_id), 0) FROM exs_change_items WHERE account_id=%ld AND change_id > %ld"
- "SELECT DISTINCT external_itemID FROM exs_change_items WHERE account_id=%ld AND item_type=%ld AND change_source_id GLOB %@ AND external_itemID IS NOT NULL AND external_itemID != '' AND change_id > COALESCE((SELECT last_change_item_id FROM exs_change_sources WHERE account_id=%ld AND change_source_id=%@), 0)"
- "SELECT change_id, account_id, item_type, change_type, change_source_id, modification_dt, item_id, external_itemID, external_changeKey, external_parentFolderID, internal_itemID, internal_changeKey, internal_parentFolderID, shouldSendNotification, eventHasAttendees, isDetached, parentExternalID, parentInternalID, instanceIndex, properties_blob FROM exs_change_items WHERE account_id=%ld AND change_id > %ld AND change_source_id GLOB %@ ORDER BY change_id LIMIT %ld"
- "SELECT external_itemID, external_changeKey FROM exs_items WHERE account_id=%ld AND external_itemID IN (SELECT value FROM json_each(%@)) ORDER BY (internal_itemID IS NULL OR internal_itemID = '') ASC, item_id DESC"
- "UPDATE exs_change_items SET external_itemID=%@, external_changeKey=%@ WHERE account_id=%ld AND internal_itemID=%@ AND item_type=%ld AND change_type=%ld AND change_id > %ld AND IFNULL(isDetached, 0)=0 AND (external_itemID IS NULL OR external_itemID='') AND change_source_id GLOB %@ AND NOT EXISTS (SELECT 1 FROM exs_items WHERE account_id=%ld AND internal_itemID=%@)"
- "q!"
- "requestedID resource "
- "webpush stage=0 flag GraphWebPushEnabled=%{public}s previous=%{public}s account=%{public}s"
- "webpush stage=4 apsTokenRequested reused=persistedKeys topic=%{private}@"
```
