## WebBookmarks

> `/System/Library/PrivateFrameworks/WebBookmarks.framework/Versions/A/WebBookmarks`

```diff

-625.2.8.11.9
-  __TEXT.__text: 0xf57d0
-  __TEXT.__objc_methlist: 0x8bd0
-  __TEXT.__const: 0x2058
-  __TEXT.__gcc_except_tab: 0xc484
-  __TEXT.__cstring: 0xfbe0
-  __TEXT.__oslogstring: 0xbc9c
+626.1.12.11.4
+  __TEXT.__text: 0xfc068
+  __TEXT.__objc_methlist: 0x8cc8
+  __TEXT.__const: 0x22e0
+  __TEXT.__gcc_except_tab: 0xc58c
+  __TEXT.__cstring: 0xfcdb
+  __TEXT.__oslogstring: 0xc4d4
   __TEXT.__dlopen_cstrs: 0x50
-  __TEXT.__constg_swiftt: 0xadc
-  __TEXT.__swift5_typeref: 0xf5e
-  __TEXT.__swift5_reflstr: 0x5c3
-  __TEXT.__swift5_fieldmd: 0x5c8
+  __TEXT.__constg_swiftt: 0xd20
+  __TEXT.__swift5_typeref: 0x1162
+  __TEXT.__swift5_reflstr: 0x77f
+  __TEXT.__swift5_fieldmd: 0x6a8
   __TEXT.__swift5_builtin: 0x3c
-  __TEXT.__swift5_types: 0x6c
-  __TEXT.__swift5_capture: 0x7bc
-  __TEXT.__swift5_proto: 0xe4
-  __TEXT.__swift_as_entry: 0x184
+  __TEXT.__swift5_types: 0x74
+  __TEXT.__swift5_capture: 0x7e4
+  __TEXT.__swift5_proto: 0xec
+  __TEXT.__swift_as_entry: 0x188
   __TEXT.__swift_as_ret: 0x198
-  __TEXT.__swift_as_cont: 0x444
-  __TEXT.__swift5_protos: 0x8
+  __TEXT.__swift_as_cont: 0x47c
   __TEXT.__swift5_assocty: 0xa0
+  __TEXT.__swift5_protos: 0x8
   __TEXT.__swift5_mpenum: 0x1c
-  __TEXT.__unwind_info: 0x6b08
-  __TEXT.__eh_frame: 0x3d18
+  __TEXT.__unwind_info: 0x6d50
+  __TEXT.__eh_frame: 0x3fc8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xd18
-  __DATA_CONST.__objc_classlist: 0x260
+  __DATA_CONST.__const: 0xd48
+  __DATA_CONST.__objc_classlist: 0x270
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x120
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x50f8
+  __DATA_CONST.__objc_selrefs: 0x5170
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x1e0
   __DATA_CONST.__objc_arraydata: 0x378
-  __DATA_CONST.__got: 0x9f0
-  __AUTH_CONST.__const: 0x5668
-  __AUTH_CONST.__cfstring: 0x6420
-  __AUTH_CONST.__objc_const: 0xa630
+  __DATA_CONST.__got: 0xa48
+  __AUTH_CONST.__const: 0x57c8
+  __AUTH_CONST.__cfstring: 0x6460
+  __AUTH_CONST.__objc_const: 0xaa30
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0xf0
   __AUTH_CONST.__objc_intobj: 0x3c0
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0xd98
-  __AUTH.__objc_data: 0x1d8
-  __AUTH.__data: 0xd8
-  __DATA.__objc_ivar: 0x600
-  __DATA.__data: 0x1a60
-  __DATA.__bss: 0x1cc0
-  __DATA_DIRTY.__objc_data: 0x1520
-  __DATA_DIRTY.__data: 0x468
+  __AUTH_CONST.__auth_got: 0xe28
+  __AUTH.__objc_data: 0x298
+  __AUTH.__data: 0x358
+  __DATA.__objc_ivar: 0x620
+  __DATA.__data: 0x1bc8
+  __DATA.__bss: 0x1dc0
+  __DATA.__common: 0x10
+  __DATA_DIRTY.__objc_data: 0x1530
+  __DATA_DIRTY.__data: 0x478
   __DATA_DIRTY.__bss: 0x1f8
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5010
-  Symbols:   8476
-  CStrings:  2183
+  Functions: 5120
+  Symbols:   8566
+  CStrings:  2215
 
Symbols:
+ -[WBLocalTabAttributes cloudTabPosition]
+ -[WBLocalTabAttributes initWithVersion:safeToLoadWebPage:lastVisitTime:sessionStateData:ancestorTabUUIDs:dateClosed:tabIndex:windowUUID:disposable:pinned:pinnedPageURL:pinnedPageTitle:muted:queuedNavigation:displayingStandaloneImage:readerViewTopScrollOffset:readingListBookmarkID:openedFromLink:showingReader:pageContext:clusterID:cloudTabPosition:lastAccessDate:selectedStartPageSegment:]
+ -[WBLocalTabAttributes setCloudTabPosition:]
+ -[WBMutableTab setCloudTabPosition:]
+ -[WBMutableTab setContentModified:]
+ -[WBParticipantPresenceCoordinator connectionManager]
+ -[WBParticipantPresenceCoordinator initWithConnectionManager:]
+ -[WBParticipantPresenceCoordinator moveCurrentParticipantToTabIdentifier:inTabGroupIdentifier:]
+ -[WBSettingsSyncEngineAccess _updateAutoDarkModeEnabledWithRecord:]
+ -[WBTab cloudTabPosition]
+ -[WBTab wasContentModified]
+ -[WBTabCyclerCommandHandler _clearServerChangeTokensForFullSyncDown]
+ -[WBTabGroupManager closeAllTabsInProfilesWithIdentifiers:completionHandler:]
+ -[WBTabGroupManager updateTabsInTabGroupWithUUID:options:usingBlock:completionHandler:]
+ -[WBTabGroupManager userIdentityRecordIDDidUpdate:]
+ -[WBTabGroupSyncAgentProxy userIdentityRecordIDDidUpdate:]
+ -[WebBookmarkCollection(Sync) setUserRecordID:]
+ -[WebBookmarkCollection(Sync) userRecordID]
+ GCC_except_table108
+ GCC_except_table209
+ GCC_except_table229
+ GCC_except_table231
+ GCC_except_table244
+ GCC_except_table245
+ GCC_except_table249
+ GCC_except_table262
+ GCC_except_table263
+ GCC_except_table267
+ GCC_except_table273
+ GCC_except_table280
+ GCC_except_table281
+ GCC_except_table290
+ GCC_except_table292
+ GCC_except_table327
+ GCC_except_table334
+ GCC_except_table363
+ GCC_except_table364
+ _OBJC_CLASS_$_WBPersonalDeviceFastSyncConnectionManager
+ _OBJC_CLASS_$_WBSAutoDarkModePreferenceManager
+ _OBJC_IVAR_$_WBLocalTabAttributes._cloudTabPosition
+ _OBJC_IVAR_$_WBParticipantPresenceCoordinator._connectionManager
+ _OBJC_IVAR_$_WBTab._contentModified
+ _OBJC_IVAR_$_WBTabGroupManager._cloudTabOrderIndexesSnapshot
+ _OBJC_IVAR_$_WBTabGroupManager._cloudTabOrderSnapshot
+ _OBJC_IVAR_$_WBTabGroupManager._cloudTabPositionGenerator
+ _OBJC_IVAR_$_WBTabGroupManager._cloudTabPositionGeneratorDelegate
+ _OBJC_IVAR_$_WBTabGroupManager._connectionManager
+ _OBJC_METACLASS_$_WBPersonalDeviceFastSyncConnectionManager
+ _WBCKUserIdentifierRecordKey
+ _WBSAutoDarkModeEnabledKey
+ _WBSOSLogFastSync
+ _WBSPerSitePreferenceNameAutoDarkMode
+ _WBSSafariSettingsAutoDarkModeKey
+ _WBTabCloudTabPositionLocalAttributeKey
+ __DATA_WBPersonalDeviceFastSyncConnectionManager
+ __DATA__TtC12WebBookmarks32PersonalDeviceFastSyncConnection
+ __INSTANCE_METHODS_WBPersonalDeviceFastSyncConnectionManager
+ __IVARS_WBPersonalDeviceFastSyncConnectionManager
+ __IVARS__TtC12WebBookmarks32PersonalDeviceFastSyncConnection
+ __METACLASS_DATA_WBPersonalDeviceFastSyncConnectionManager
+ __METACLASS_DATA__TtC12WebBookmarks32PersonalDeviceFastSyncConnection
+ __PROPERTIES_WBPersonalDeviceFastSyncConnectionManager
+ ___58-[WBTabCollection updateTabsInTabGroup:completionHandler:]_block_invoke_2
+ ___58-[WBTabGroupSyncAgentProxy userIdentityRecordIDDidUpdate:]_block_invoke
+ ___77-[WBTabGroupManager closeAllTabsInProfilesWithIdentifiers:completionHandler:]_block_invoke
+ ___77-[WBTabGroupManager closeAllTabsInProfilesWithIdentifiers:completionHandler:]_block_invoke_2
+ ___87-[WBTabGroupManager updateTabsInTabGroupWithUUID:options:usingBlock:completionHandler:]_block_invoke
+ ___87-[WBTabGroupManager updateTabsInTabGroupWithUUID:options:usingBlock:completionHandler:]_block_invoke_2
+ ___block_descriptor_41_ea8_32bs_e8_v12?0B8l
+ ___block_descriptor_57_e8_32s40s48bs_e5_v8?0l
+ ___block_descriptor_65_ea8_32s40s48s56s_e29_v32?0"WBMutableTab"8Q16^B24l
+ ___block_descriptor_68_ea8_32s40s48s56s_e5_B8?0l
+ ___swift_closure_destructor.100Tm
+ ___swift_closure_destructor.239Tm
+ ___swift_closure_destructor.248Tm
+ ___swift_closure_destructor.299Tm
+ ___swift_closure_destructor.314Tm
+ ___swift_closure_destructor.428Tm
+ ___swift_closure_destructor.43Tm
+ ___swift_closure_destructor.52Tm
+ ___swift_closure_destructor.92Tm
+ ___swift_closure_destructor.99Tm
+ ___unnamed_14
+ __swift_stdlib_reportUnimplementedInitializer
+ _associated conformance 12WebBookmarks16WBCRDTGenerationVSLAASQ
+ _associated conformance 12WebBookmarks27CKShareGroupSessionProviderCyxG0D10Activities08PresencedeF0AaE0deF0
+ _dispatch_group_create
+ _dispatch_group_enter
+ _dispatch_group_leave
+ _dispatch_group_notify
+ _objc_msgSend$_clearServerChangeTokensForFullSyncDown
+ _objc_msgSend$_updateAutoDarkModeEnabledWithRecord:
+ _objc_msgSend$closeAllTabsInProfilesWithIdentifiers:completionHandler:
+ _objc_msgSend$initWithConnectionManager:
+ _objc_msgSend$initWithVersion:safeToLoadWebPage:lastVisitTime:sessionStateData:ancestorTabUUIDs:dateClosed:tabIndex:windowUUID:disposable:pinned:pinnedPageURL:pinnedPageTitle:muted:queuedNavigation:displayingStandaloneImage:readerViewTopScrollOffset:readingListBookmarkID:openedFromLink:showingReader:pageContext:clusterID:cloudTabPosition:lastAccessDate:selectedStartPageSegment:
+ _objc_msgSend$moveCurrentParticipantToTabIdentifier:inTabGroupIdentifier:
+ _objc_msgSend$setCloudTabPosition:
+ _objc_msgSend$setContentModified:
+ _objc_msgSend$setEnabled:source:
+ _objc_msgSend$setUserIdentityRecordID:
+ _objc_msgSend$updateTabsInTabGroupWithUUID:options:usingBlock:completionHandler:
+ _objc_msgSend$userIdentityRecordIDDidUpdate:
+ _swift_getSingletonMetadata
+ _swift_updateClassMetadata2
+ _symbolic $s12WebBookmarks14WBFastSyncableP
+ _symbolic SayScCySo10CKRecordIDC_____GG s5NeverO
+ _symbolic Say_____y______yShy_____GGGG 12WebBookmarks32PersonalDeviceFastSyncConnectionC13WeakContainer33_8E7344B3F244470CA6CB19807985A124LLV AA18AsyncBufferedQueueC 15GroupActivities11ParticipantV
+ _symbolic Say_____y______y_____y_____GSgGGG 12WebBookmarks32PersonalDeviceFastSyncConnectionC13WeakContainer33_8E7344B3F244470CA6CB19807985A124LLV AA18AsyncBufferedQueueC 15GroupActivities0S7SessionC AA0cD20CoordinationActivityV
+ _symbolic ScCySo10CKRecordIDC_____G s5NeverO
+ _symbolic ScSy_____y_____GSgG 15GroupActivities0A7SessionC 12WebBookmarks34PersonalDeviceCoordinationActivityV
+ _symbolic So10CKRecordIDC
+ _symbolic So10CKRecordIDCSg
+ _symbolic So17OS_dispatch_queueC
+ _symbolic So41WBPersonalDeviceFastSyncConnectionManagerC
+ _symbolic _____ 12WebBookmarks16WBCRDTGenerationV
+ _symbolic _____ 12WebBookmarks32PersonalDeviceFastSyncConnectionC
+ _symbolic _____ 12WebBookmarks32PersonalDeviceFastSyncConnectionC13WeakContainer33_8E7344B3F244470CA6CB19807985A124LLV
+ _symbolic _____yScCySo10CKRecordIDC_____GG s23_ContiguousArrayStorageC s5NeverO
+ _symbolic _____y_____GSg 15GroupActivities0A7SessionC 12WebBookmarks34PersonalDeviceCoordinationActivityV
+ _symbolic _____y_______GSg ScS12ContinuationV11YieldResultO 12WebBookmarks21PresenceUpdateMessageV
+ _symbolic _____y__________G 7Combine19CurrentValueSubjectC 15GroupActivities19PresenceSessionInfoV s5NeverO
+ _symbolic _____y__________GSg 12WebBookmarks31GroupSessionMessengerControllerC AA34PersonalDeviceCoordinationActivityV AA21PresenceUpdateMessageV
+ _symbolic _____y__________yABGGSg 12WebBookmarks20FastSyncStateMachineV AA34PersonalDeviceCoordinationActivityV 15GroupActivities0gK15SessionProviderC
+ _symbolic _____y______yShy_____GGG 12WebBookmarks32PersonalDeviceFastSyncConnectionC13WeakContainer33_8E7344B3F244470CA6CB19807985A124LLV AA18AsyncBufferedQueueC 15GroupActivities11ParticipantV
+ _symbolic _____y______y_____y_____GSgGG 12WebBookmarks32PersonalDeviceFastSyncConnectionC13WeakContainer33_8E7344B3F244470CA6CB19807985A124LLV AA18AsyncBufferedQueueC 15GroupActivities0S7SessionC AA0cD20CoordinationActivityV
+ _symbolic _____y_____y_____GSgG 12WebBookmarks18AsyncBufferedQueueC 15GroupActivities0F7SessionC AA34PersonalDeviceCoordinationActivityV
+ _symbolic _____y_____y_____GSg_G ScS12ContinuationV 15GroupActivities0B7SessionC 12WebBookmarks34PersonalDeviceCoordinationActivityV
+ _symbolic _____y_____y_____GSg_G ScS8IteratorV 15GroupActivities0B7SessionC 12WebBookmarks34PersonalDeviceCoordinationActivityV
+ _symbolic _____y_____y_____GSg_GSg ScS12ContinuationV 15GroupActivities0B7SessionC 12WebBookmarks34PersonalDeviceCoordinationActivityV
+ _symbolic _____y_____y_____GSg__G ScS12ContinuationV11YieldResultO 15GroupActivities0D7SessionC 12WebBookmarks34PersonalDeviceCoordinationActivityV
+ _symbolic _____y_____y_____GSg__G ScS12ContinuationV15BufferingPolicyO 15GroupActivities0D7SessionC 12WebBookmarks34PersonalDeviceCoordinationActivityV
+ _symbolic _____y_____y______yShy_____GGGG s23_ContiguousArrayStorageC 12WebBookmarks32PersonalDeviceFastSyncConnectionC13WeakContainer33_8E7344B3F244470CA6CB19807985A124LLV AC18AsyncBufferedQueueC 15GroupActivities11ParticipantV
+ _symbolic _____y_____y______y_____y_____GSgGGG s23_ContiguousArrayStorageC 12WebBookmarks32PersonalDeviceFastSyncConnectionC13WeakContainer33_8E7344B3F244470CA6CB19807985A124LLV AC18AsyncBufferedQueueC 15GroupActivities0V7SessionC AC0fG20CoordinationActivityV
+ _symbolic xSgXw
+ _type_layout_string 12WebBookmarks16WBCRDTGenerationV
+ _type_layout_string RlzCl12WebBookmarks32PersonalDeviceFastSyncConnectionC13WeakContainer33_8E7344B3F244470CA6CB19807985A124LLVy_xG
+ _type_layout_string s23CustomStringConvertibleRzs8SendableRz12ActivityTypeQy_Rsz12WebBookmarks0D20GroupSessionProviderR_AE14WBFastSyncableR0_Rld__Cr1__lAE30CollaborationConnectionManagerC13WeakContainer33_6B66ADCD97034074DFF2F301074CBFA2LLVyxq_q0__qd__G
- -[WBLocalTabAttributes initWithVersion:safeToLoadWebPage:lastVisitTime:sessionStateData:ancestorTabUUIDs:dateClosed:tabIndex:windowUUID:disposable:pinned:pinnedPageURL:pinnedPageTitle:muted:queuedNavigation:displayingStandaloneImage:readerViewTopScrollOffset:readingListBookmarkID:openedFromLink:showingReader:pageContext:clusterID:lastAccessDate:selectedStartPageSegment:]
- -[WBParticipantPresenceCoordinator init]
- -[WBParticipantPresenceCoordinator moveCurrentParticipantToTabIdentifier:inTabGroupIdentifier:withDeviceIdentifier:]
- -[WBTabGroupManager deviceIdentifier]
- GCC_except_table232
- GCC_except_table234
- GCC_except_table246
- GCC_except_table247
- GCC_except_table252
- GCC_except_table254
- GCC_except_table265
- GCC_except_table270
- GCC_except_table305
- GCC_except_table306
- GCC_except_table310
- GCC_except_table332
- GCC_except_table333
- GCC_except_table341
- GCC_except_table347
- GCC_except_table367
- GCC_except_table74
- ___59-[WBTabGroupManager closeAllTabsInProfilesWithIdentifiers:]_block_invoke
- ___69-[WBTabGroupManager updateTabsInTabGroupWithUUID:options:usingBlock:]_block_invoke
- ___69-[WBTabGroupManager updateTabsInTabGroupWithUUID:options:usingBlock:]_block_invoke_2
- ___block_descriptor_57_ea8_32s40s48s_e29_v32?0"WBMutableTab"8Q16^B24l
- ___swift_closure_destructor.236Tm
- ___swift_closure_destructor.245Tm
- ___swift_closure_destructor.302Tm
- ___swift_closure_destructor.320Tm
- ___swift_closure_destructor.335Tm
- ___swift_closure_destructor.360Tm
- ___swift_closure_destructor.389Tm
- ___swift_closure_destructor.434Tm
- ___swift_closure_destructor.91Tm
- _associated conformance 12WebBookmarks14CRDTGenerationVSLAASQ
- _objc_msgSend$initWithVersion:safeToLoadWebPage:lastVisitTime:sessionStateData:ancestorTabUUIDs:dateClosed:tabIndex:windowUUID:disposable:pinned:pinnedPageURL:pinnedPageTitle:muted:queuedNavigation:displayingStandaloneImage:readerViewTopScrollOffset:readingListBookmarkID:openedFromLink:showingReader:pageContext:clusterID:lastAccessDate:selectedStartPageSegment:
- _objc_msgSend$insertItems:inParent:afterItem:completionHandler:
- _objc_msgSend$moveCurrentParticipantToTabIdentifier:inTabGroupIdentifier:withDeviceIdentifier:
- _objc_msgSend$reorderItem:afterItem:completionHandler:
- _symbolic $s12WebBookmarks15FastSyncMessageP
- _symbolic _____ 12WebBookmarks14CRDTGenerationV
- _symbolic _____y__________yABG_____G 12WebBookmarks30CollaborationConnectionManagerC AA34PersonalDeviceCoordinationActivityV 15GroupActivities0fJ15SessionProviderC AA21PresenceUpdateMessageV
- _symbolic _____y__________yABG_____GSg 12WebBookmarks30CollaborationConnectionManagerC AA34PersonalDeviceCoordinationActivityV 15GroupActivities0fJ15SessionProviderC AA21PresenceUpdateMessageV
- _symbolic _____y__________yABG___________yShy_____GGG 12WebBookmarks30CollaborationConnectionManagerC13WeakContainer33_6B66ADCD97034074DFF2F301074CBFA2LLV AA34PersonalDeviceCoordinationActivityV 15GroupActivities0mQ15SessionProviderC AA21PresenceUpdateMessageV AA18AsyncBufferedQueueC AI11ParticipantV
- _symbolic _____y_____y__________yACG___________yShy_____GGGG s23_ContiguousArrayStorageC 12WebBookmarks30CollaborationConnectionManagerC13WeakContainer33_6B66ADCD97034074DFF2F301074CBFA2LLV AC34PersonalDeviceCoordinationActivityV 15GroupActivities0pT15SessionProviderC AC21PresenceUpdateMessageV AC18AsyncBufferedQueueC AK11ParticipantV
- _type_layout_string 12WebBookmarks14CRDTGenerationV
- _type_layout_string s23CustomStringConvertibleRzs8SendableRz12ActivityTypeQy_Rsz12WebBookmarks0D20GroupSessionProviderR_AE15FastSyncMessageR0_Rld__Cr1__lAE30CollaborationConnectionManagerC13WeakContainer33_6B66ADCD97034074DFF2F301074CBFA2LLVyxq_q0__qd__G
CStrings:
+ "CKUserIdentifier"
+ "Could not lock sync to clear server change tokens; sync down may return zero records"
+ "Device coordination was never established, nothing to pause"
+ "Did attach to shared personal device connection"
+ "Did detach from shared personal device connection"
+ "Did finish receiving messages in personal device connection"
+ "Did received updated user identity record ID from sync agent"
+ "Failed to attach personal device connection with error %@"
+ "Failed to clear last server change tokens; sync down may return zero records"
+ "Failed to unpause shared connections with error %@"
+ "Has persisted user identity record ID on disk: %{public}@"
+ "No tab groups found, clearing server change tokens for a full sync down and starting migration"
+ "PersonalDeviceFastSyncConnection: attach() called, attachedConsumerCount %{public}ld, userIdentityRecordID already set: %{bool,public}d"
+ "PersonalDeviceFastSyncConnection: detached while waiting for user identity, not starting activity"
+ "PersonalDeviceFastSyncConnection: did join provider"
+ "PersonalDeviceFastSyncConnection: failed to join, error: %@"
+ "PersonalDeviceFastSyncConnection: failed to leave, error: %@"
+ "PersonalDeviceFastSyncConnection: provider.sessions sequence ended"
+ "PersonalDeviceFastSyncConnection: session %{public}s active participants now %{public}s"
+ "PersonalDeviceFastSyncConnection: session %{public}s became available"
+ "PersonalDeviceFastSyncConnection: session %{public}s did join"
+ "PersonalDeviceFastSyncConnection: session %{public}s failed to join with error %@"
+ "PersonalDeviceFastSyncConnection: session %{public}s local participant handle %{public}s"
+ "PersonalDeviceFastSyncConnection: session %{public}s will join"
+ "PersonalDeviceFastSyncConnection: session failed, retrying: %@"
+ "PersonalDeviceFastSyncConnection: setUserIdentityRecordID(_:) called with unchanged value, ignoring"
+ "PersonalDeviceFastSyncConnection: setUserIdentityRecordID(_:) called, had a value already: %{bool,public}d"
+ "PersonalDeviceFastSyncConnection: stateMachine.startActivity returned %{bool,public}d"
+ "PersonalDeviceFastSyncConnection: waiting for user identity before starting activity"
+ "PersonalDeviceFastSyncConnection: will join provider"
+ "PersonalDeviceFastSyncConnection: will wait for group sessions"
+ "Updating the Auto Dark Mode setting"
+ "WebBookmarks.ParticipantPresenceCoordinator"
+ "com.apple.WebBookmarks.group-activities.personal-device-join-leave-session"
+ "com.apple.bookmarks.CloudTabPosition"
+ "init()"
+ "userIdentifierRecordID"
+ "waitForUserIdentityRecordID()"
- "Did begin personal device connection activity"
- "Did finnish receiving messages in personal device connection"
- "Did leave personal device connection activity"
- "Failed to leave activity"
- "Failed to start activity with error %@"
- "No tab groups found, clearing tab sync data and starting migration"
```
