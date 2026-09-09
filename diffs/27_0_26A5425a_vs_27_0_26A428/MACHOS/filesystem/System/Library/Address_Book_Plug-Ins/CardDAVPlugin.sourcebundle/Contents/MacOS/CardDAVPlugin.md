## CardDAVPlugin

> `/System/Library/Address Book Plug-Ins/CardDAVPlugin.sourcebundle/Contents/MacOS/CardDAVPlugin`

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

 1119.100.1.0.0
-  __TEXT.__text: 0x49ba0
+  __TEXT.__text: 0x489a0
   __TEXT.__auth_stubs: 0x600
   __TEXT.__objc_stubs: 0x8100
   __TEXT.__objc_methlist: 0x2cf4

   __TEXT.__objc_classname: 0x4a3
   __TEXT.__objc_methname: 0x905c
   __TEXT.__objc_methtype: 0x1480
-  __TEXT.__unwind_info: 0xe20
+  __TEXT.__unwind_info: 0x1358
   __DATA_CONST.__const: 0x818
   __DATA_CONST.__cfstring: 0x3500
   __DATA_CONST.__objc_classlist: 0xe8
Functions:
~ +[CDXAutoDiscovery initialize] : 124 -> 112
~ _CDXInitialize : 140 -> 128
~ _CDXGetPrefForKey : 48 -> 36
~ _DAVUtil_SetDebugMode : 272 -> 260
~ +[CDXLogging os_log] : 68 -> 56
~ ___20+[CDXLogging os_log]_block_invoke : 72 -> 60
~ -[NSDictionary(CDXHomeInfo) cdxHomeInfo_cardDAVHomeInfo] : 92 -> 80
~ -[NSDictionary(CDXHomeInfo) cdxHomeInfo_cardDAVHomePath] : 112 -> 100
~ -[NSDictionary(CDXHomeInfo) cdxHomeInfo_copyAllContainerInfosSortedByPath] : 92 -> 80
~ -[NSDictionary(CDXHomeInfo) cdxHomeInfo_containerInfoWithPath:] : 140 -> 128
~ -[NSString(CDXExtensions) cdxStringByAppendingSlashIfNeeded] : 96 -> 84
~ -[NSDictionary(CDXExtensions) cdxObjectForKeyCaseInsensitive:] : 168 -> 156
~ -[NSDictionary(CDXContainerInfo) cdxContainerInfo_hasWriteContentPrivileges] : 148 -> 136
~ -[NSString(CDXExtensions) cdxInitWithNameSpace:andName:] : 104 -> 92
~ _ParseCardDAVURLString : 1248 -> 1236
~ +[NSURL(CDXExtensions) cdxURLWithString:] : 156 -> 144
~ -[NSURL(CDXExtensions) cdxCopyPathPreservingTrailingSlash] : 76 -> 64
~ _GetCurrThreadDesc : 112 -> 100
~ -[CDXManager setInfoFromCardDAVSource:] : 792 -> 780
~ _CopyCardDAVURL : 92 -> 80
~ _CopyCardDAVURLString : 404 -> 392
~ -[NSString(CDXExtensions) cdxCopyStringByAddingPercentEscapesForHREF] : 80 -> 68
~ -[CDXAccount resetSuppressDuplicateCertDialogs] : 64 -> 52
~ -[CDXAccount setSuppressDuplicateCertDialogs:] : 196 -> 184
~ +[CDXManager startLoggingWithController:] : 144 -> 132
~ +[CDXACAccountStoreProvider initialize] : 124 -> 112
~ -[CDXManager userName] : 84 -> 72
~ +[CDXLogging os_log_sync_summary] : 68 -> 56
~ ___33+[CDXLogging os_log_sync_summary]_block_invoke : 72 -> 60
~ -[CDXManager getPrincipalURLString:] : 160 -> 148
~ -[CDXManager getPrincipalInfoPropertyWithNameSpace:andName:error:] : 184 -> 172
~ -[CDXManager getPrincipalInfo:] : 2820 -> 2808
~ +[CDXLogging os_log_auth] : 68 -> 56
~ ___25+[CDXLogging os_log_auth]_block_invoke : 72 -> 60
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ -[CDXAccount password] : 108 -> 96
~ -[CDXAccount acAccount] : 436 -> 424
~ -[CDXAccount additionalHeaderValues] : 340 -> 328
~ -[CDXAccount getAppleIDSession] : 144 -> 132
~ ___31-[CDXAccount getAppleIDSession]_block_invoke : 76 -> 64
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ -[CDXController optionsTask:error:] : 208 -> 196
~ _getStateName : 84 -> 60
~ -[CDXTaskManager shutdown] : 372 -> 360
~ -[CDXTaskManager allTasks] : 732 -> 720
~ +[CDXManager stopLoggingWithController:] : 188 -> 176
~ -[CDXManager .cxx_destruct] : 116 -> 104
~ -[CDXController .cxx_destruct] : 332 -> 320
~ -[CDXAccount .cxx_destruct] : 248 -> 236
~ -[CDXTaskManager .cxx_destruct] : 152 -> 140
~ -[NSDictionary(CDXHomeInfo) cdxHomeInfo_mainAddressBookInfo] : 92 -> 80
~ -[NSDictionary(CDXContainerInfo) cdxContainerInfo_isSharedAddressBook] : 96 -> 84
~ +[CDXAutoDiscovery _queryAdditionalServerInfo:userName:password:] : 1892 -> 1880
~ +[CDXAutoDiscovery _getAdditionalAccountInformationForKey:andRemoveFromGlobalCache:] : 332 -> 320
~ +[CDXAutoDiscovery runAutoDiscovery:] : 5856 -> 5844
~ +[CDXAutoDiscovery autodiscoveryFutureWithSettings:] : 284 -> 272
~ ___52+[CDXAutoDiscovery autodiscoveryFutureWithSettings:]_block_invoke : 224 -> 212
~ +[CDXAutoDiscovery testConnectionFuture:] : 284 -> 272
~ ___41+[CDXAutoDiscovery testConnectionFuture:]_block_invoke : 292 -> 280
~ +[CDXAutoDiscovery testConnection:] : 1472 -> 1460
~ +[CDXAutoDiscovery getAddlAcctInfoFromFullURL:] : 172 -> 160
~ +[CDXAutoDiscovery getCleanAccountURLString:accountURLString:] : 184 -> 172
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _CDXDebugDictByObscuringPassword : 468 -> 456
~ _CDXLocalizedString : 276 -> 264
~ _CDXGetCDXError : 184 -> 172
~ _CDXGetCDXErrorDesc : 116 -> 104
~ _CDXBuildErrorFromException : 528 -> 516
~ -[CDXManager accountIdentifier] : 84 -> 72
~ -[CDXManager host] : 84 -> 72
~ -[CDXManager renewPushSubscriptionAtURL:] : 96 -> 84
~ -[CDXManager handleWebAuthRequestAtURL:completionBlock:] : 132 -> 120
~ -[CDXManager accountURLString] : 112 -> 100
~ -[CDXManager password] : 132 -> 120
~ -[CDXManager getSearchInfo:] : 1584 -> 1572
~ -[CDXManager getHomeInfo:] : 196 -> 184
~ -[CDXManager getUncachedHomeInfo:] : 924 -> 912
~ -[CDXManager absoluteStringForPath:] : 300 -> 288
~ -[CDXManager absoluteURLForPath:] : 300 -> 288
~ -[CDXManager mainAddressBookPath] : 80 -> 68
~ -[CDXManager authorDisplayNameForPath:] : 256 -> 244
~ _CollectionGroupInGroups : 292 -> 280
~ _CollectionGroupForGroup : 204 -> 192
~ _CDX_AB_GetGroupCollectionPath : 160 -> 148
~ _CDX_AB_GroupForCollectionPath : 416 -> 404
~ -[CDXManager collectionPathForPerson:] : 224 -> 212
~ _CollectionGroupPathGroups : 92 -> 80
~ -[CDXManager collectionPathForGroup:] : 212 -> 200
~ _CopyFilteredPersonUnknownProperties : 396 -> 384
~ _GenerateVCardStringFromPerson : 1068 -> 1056
~ ___GenerateVCardStringFromPerson_block_invoke : 196 -> 184
~ _MakeUUID : 192 -> 180
~ _ABUtil_DebugGetPersonName : 316 -> 304
~ _AddVCardFieldAfterField : 348 -> 336
~ _ReplaceVCardProperty : 144 -> 132
~ _CleanVCardString : 188 -> 176
~ _GenerateVCardStringFromGroup : 3976 -> 3964
~ _ABUtil_PeopleMatching : 316 -> 304
~ _Debug_VerifySearchElementForProperty : 1480 -> 1468
~ _ABUtil_GroupsMatching : 320 -> 308
~ _SetDictionaryObject : 148 -> 136
~ _SplitString : 192 -> 180
~ _CDX_AB_SetRecordNeedsSync : 128 -> 116
~ _CDX_AB_ClearServerProperties : 116 -> 104
~ _CDX_AB_DebugSetTag : 100 -> 88
~ _CDX_AB_CreateGroup : 252 -> 240
~ _OUTLINED_FUNCTION_4 : 32 -> 20
~ _OUTLINED_FUNCTION_6 : 32 -> 20
~ _GetVCardField : 888 -> 876
~ _VCardHash : 300 -> 288
~ _CardInfoFromVCardData : 3392 -> 3380
~ +[CardDAVSource initialize] : 124 -> 112
~ ___41-[CardDAVSource initWithUID:persistence:]_block_invoke : 80 -> 68
~ -[CardDAVSource commonAwake] : 256 -> 244
~ -[CardDAVSource invalidate] : 72 -> 60
~ -[CardDAVSource resetSyncTag] : 220 -> 208
~ -[CardDAVSource updateSourcePermissions] : 128 -> 116
~ +[CardDAVSource containerInAddressBook:] : 208 -> 196
~ +[CardDAVSource clearPendingGuardianRestrictedUpdateWithGuardianRestricted:addressBook:] : 188 -> 176
~ -[CardDAVSource setHomeInfo:] : 160 -> 148
~ -[CardDAVSource homeInfo] : 88 -> 76
~ -[CardDAVSource setSearchInfo:] : 176 -> 164
~ -[CardDAVSource searchInfo] : 88 -> 76
~ -[CardDAVSource setSearchable:] : 80 -> 68
~ -[CardDAVSource setPrincipalInfo:] : 160 -> 148
~ -[CardDAVSource principalInfo] : 88 -> 76
~ -[CardDAVSource authorString] : 608 -> 596
~ -[CardDAVSource fullName] : 164 -> 152
~ -[CardDAVSource delegateInfos] : 364 -> 352
~ -[CardDAVSource emailAddresses] : 104 -> 92
~ _GenerateError : 288 -> 276
~ -[CardDAVSource presentAuthenticationError:modalForWindow:] : 244 -> 232
~ ___58-[CardDAVSource showPasswordPanelForError:modalForWindow:]_block_invoke : 124 -> 112
~ -[CardDAVSource credentialChanged:] : 92 -> 80
~ -[CardDAVSource setRefreshInterval:] : 80 -> 68
~ -[CardDAVSource lastKnownServerMeCardPath] : 88 -> 76
~ -[CardDAVSource setLastKnownServerMeCardPath:] : 104 -> 92
~ -[CardDAVSource aListPluginIdentifier] : 88 -> 76
~ -[CardDAVSource setAListPluginIdentifier:] : 104 -> 92
~ -[CardDAVSource acAccountIdentifier] : 88 -> 76
~ -[CardDAVSource setAcAccountIdentifier:] : 104 -> 92
~ -[CardDAVSource acAccountTypeIdentifier] : 88 -> 76
~ -[CardDAVSource setAcAccountTypeIdentifier:] : 104 -> 92
~ -[CardDAVSource acParentAccountTypeIdentifier] : 88 -> 76
~ -[CardDAVSource setAcParentAccountTypeIdentifier:] : 104 -> 92
~ -[CardDAVSource serverUrlString] : 172 -> 160
~ -[CardDAVSource emailAddress] : 92 -> 80
~ -[CardDAVSource setEmailAddress:] : 108 -> 96
~ -[CardDAVSource updateServerUrlStringFromComponents] : 76 -> 64
~ -[CardDAVSource updateServerUrlString:] : 104 -> 92
~ ___41-[CardDAVSource setServernameComponents:]_block_invoke : 176 -> 164
~ ___44-[CardDAVSource updateServernameComponents:]_block_invoke : 180 -> 168
~ -[CardDAVSource serverName] : 92 -> 80
~ -[CardDAVSource setServerName:] : 56 -> 44
~ -[CardDAVSource updateServerName:] : 108 -> 96
~ -[CardDAVSource serverPort] : 92 -> 80
~ -[CardDAVSource setServerPort:] : 56 -> 44
~ -[CardDAVSource updateServerPort:] : 128 -> 116
~ -[CardDAVSource serverRootPath] : 92 -> 80
~ -[CardDAVSource setServerRootPath:] : 56 -> 44
~ -[CardDAVSource updateServerRootPath:] : 108 -> 96
~ -[CardDAVSource userName] : 92 -> 80
~ -[CardDAVSource setUserName:] : 116 -> 104
~ -[CardDAVSource updateUserName:] : 108 -> 96
~ -[CardDAVSource setUseSSL:] : 56 -> 44
~ -[CardDAVSource updateUseSSL:] : 84 -> 72
~ -[CardDAVSource scheme] : 64 -> 52
~ -[CardDAVSource mainAddressBookGroupInAddressBook:] : 184 -> 172
~ +[CardDAVSource simpleHost:] : 116 -> 104
~ -[CardDAVSource getCollectionName:isMainAddressBook:isMainSharedAddressBook:] : 336 -> 324
~ -[CardDAVSource secureServiceName] : 104 -> 92
~ +[CardDAVSource passwordForUser:service:error:] : 396 -> 384
~ +[CardDAVSource passwordForConfiguration:] : 228 -> 216
~ ___53-[CardDAVSource cancelServerSyncWithCompletionBlock:]_block_invoke : 92 -> 80
~ ___copy_helper_block_e8_32b40b : 80 -> 68
~ -[CardDAVSource goOffline] : 56 -> 44
~ -[CardDAVSource watchReachabilityHost] : 100 -> 88
~ -[CardDAVSource startWatchingForReachabilityChanges] : 160 -> 148
~ -[CardDAVSource stopWatchingForReachabilityChanges] : 140 -> 128
~ -[CardDAVSource processError:] : 284 -> 272
~ -[CardDAVSource processErrors:] : 156 -> 144
~ -[CardDAVSource _changeRecordAttributes:targetGroup:ops:inAddressBook:] : 5396 -> 5384
~ _CopyPerson : 688 -> 676
~ +[CardDAVSource saveOptions] : 112 -> 100
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[CardDAVSource getAndResetPendingSyncMode:] : 912 -> 900
~ -[CardDAVSource clearAllCTagsAndETags:inAddressBook:] : 124 -> 112
~ _FilterChangedRecords : 964 -> 952
~ +[CardDAVSource autodiscoverSettings:] : 380 -> 368
~ +[CardDAVSource autodiscoveryFutureWithSettings:] : 224 -> 212
~ +[CardDAVSource testConnection:] : 464 -> 452
~ +[CardDAVSource testConnectionFuture:] : 224 -> 212
~ +[CardDAVSource updateTestConnectionSettingsWithAutodiscovery:] : 232 -> 220
~ +[CardDAVSource autodiscoverSettingsFromTestConnectionSettings:] : 528 -> 516
~ +[CardDAVSource updateDictionary:withObject:forKey:] : 172 -> 160
~ +[CardDAVSource createAccountUsingInfo:returningError:] : 1588 -> 1576
~ -[CardDAVSource localIdentifierForServerPath:addressBook:] : 480 -> 468
~ -[CardDAVSource defaultAccountInfoSuitableForLogging] : 88 -> 76
~ -[CardDAVSource prefsView] : 52 -> 40
~ -[CardDAVSource prefsTabView] : 52 -> 40
~ -[CardDAVSource prefsDescriptionLabel] : 52 -> 40
~ -[CardDAVSource prefsDescriptionValue] : 52 -> 40
~ -[CardDAVSource prefsUserNameLabel] : 52 -> 40
~ -[CardDAVSource prefsUserNameValue] : 52 -> 40
~ -[CardDAVSource prefsPasswordLabel] : 52 -> 40
~ -[CardDAVSource prefsPasswordValue] : 52 -> 40
~ -[CardDAVSource prefsRefreshContactsLabel] : 52 -> 40
~ -[CardDAVSource prefsRefreshContactsPopUp] : 52 -> 40
~ -[CardDAVSource prefsSharedAddressBookLabel] : 52 -> 40
~ -[CardDAVSource prefsSharedAddressBookPopUp] : 52 -> 40
~ -[CardDAVSource prefsMoreConfigurationPrefsLabel] : 52 -> 40
~ -[CardDAVSource prefsMoreConfigurationPrefsButton] : 52 -> 40
~ -[CardDAVSource .cxx_destruct] : 588 -> 576
~ -[AccessPrivilegesTransformer transformedValue:] : 68 -> 56
~ _sDeepCopy_block_invoke : 520 -> 508
~ -[CardDAVSourceSearchOperation setupManager:] : 136 -> 124
~ -[CardDAVSourceSearchOperation searchMatches] : 2268 -> 2256
~ -[CardDAVSourceSearchOperation .cxx_destruct] : 84 -> 72
~ -[CDXAccount description] : 432 -> 420
~ -[CDXAccount _connectionURLString:] : 180 -> 168
~ -[CDXAccount _authMethodsTriedConnectionDict:] : 88 -> 76
~ _GetAuthenticationChallengeDesc : 368 -> 356
~ _GetAuthMethodDescriptor : 112 -> 100
~ _GetProtectionSpaceDesc : 260 -> 248
~ -[CDXAccount grandSlamAppToken] : 344 -> 332
~ -[CDXAccount oauth2Token] : 252 -> 240
~ -[CDXAccount acAccountOrParentGoogleAccount] : 456 -> 444
~ ___36-[CDXAccount isPrimaryICloudAccount]_block_invoke : 180 -> 168
~ ___36-[CDXAccount isPrimaryICloudAccount]_block_invoke_2 : 132 -> 120
~ ___47-[CDXAccount isAccountOwnerChildInFamilyCircle]_block_invoke : 180 -> 168
~ ___47-[CDXAccount isAccountOwnerChildInFamilyCircle]_block_invoke_2 : 636 -> 624
~ _OUTLINED_FUNCTION_11 : 32 -> 20
~ +[CDXREVDateFormatter sharedFormatter] : 68 -> 56
~ ___38+[CDXREVDateFormatter sharedFormatter]_block_invoke : 136 -> 124
~ +[CDXREVDateFormatter stringWithDate:] : 120 -> 108
~ +[CDXREVDateFormatter dateFromString:] : 120 -> 108
~ +[CDXThermalMonitor sharedThermalMonitor] : 160 -> 148
~ ___41+[CDXThermalMonitor sharedThermalMonitor]_block_invoke : 64 -> 52
~ +[CDXThermalMonitor makeActiveThermalMonitor] : 60 -> 48
~ -[CDXThermalMonitor startMonitoring] : 56 -> 44
~ -[CDXChangeHistoryChangeTracker readOfflineDeletedItems] : 56 -> 44
~ -[CDXChangeHistoryChangeTracker fetchItems] : 548 -> 536
~ -[CDXChangeHistoryChangeTracker loadAnchor] : 100 -> 88
~ -[CDXChangeHistoryChangeTracker .cxx_destruct] : 92 -> 80
~ -[CDXChangeHistoryDeletionVisitor description] : 124 -> 112
~ -[CDXChangeHistoryDeletionVisitor .cxx_destruct] : 68 -> 56
~ _OUTLINED_FUNCTION_2 : 32 -> 20
~ +[CDXAccountUpdator updateAccount:withDiscoveredAccountInfo:] : 116 -> 104
~ +[CDXAccountUpdator copyServerInformationFromAccountInfo:toAccount:] : 288 -> 276
~ +[CDXAccountUpdator reconstructCorrectServerPathsOnChildDelegateAccount:] : 360 -> 348
~ +[CDXLogging logFolderURL] : 160 -> 148
~ ___26+[CDXLogging logFolderURL]_block_invoke : 88 -> 76
~ +[CDXLogging makeAndPrepareLogFolderURL] : 76 -> 64
~ +[CDXLogging makeLogFolderURL] : 208 -> 196
~ +[CDXLogging problematicCardFolderURL] : 160 -> 148
~ ___38+[CDXLogging problematicCardFolderURL]_block_invoke : 88 -> 76
~ +[CDXLogging makeAndPrepareProblematicCardFolderURL] : 116 -> 104
~ +[CDXLogging os_log_sync] : 68 -> 56
~ ___25+[CDXLogging os_log_sync]_block_invoke : 72 -> 60
~ +[CDXLogging os_log_task] : 68 -> 56
~ ___25+[CDXLogging os_log_task]_block_invoke : 72 -> 60
~ +[CDXLogging os_log_traffic] : 68 -> 56
~ ___28+[CDXLogging os_log_traffic]_block_invoke : 72 -> 60
~ +[CDXLogging os_log_discovery] : 68 -> 56
~ ___30+[CDXLogging os_log_discovery]_block_invoke : 72 -> 60
~ -[CDXTaskManager stateString] : 204 -> 192
~ +[CDXChangeTracker changeTrackerWithCardDAVSource:] : 444 -> 432
~ +[CDXChangeTracker changeHistoryTrackerWithContactStore:folderURL:] : 140 -> 128
~ +[CDXChangeTracker plistTrackerWithCardDAVSource:] : 104 -> 92
~ -[CDXFolderInfo description] : 348 -> 336
~ -[CDXFolderInfo addAction:] : 72 -> 60
~ -[CDXFolderInfo addVCardUID:] : 72 -> 60
~ -[CDXFolderInfo .cxx_destruct] : 128 -> 116
~ -[CDXController getAccountPropertiesTask:completedWithError:] : 824 -> 812
~ ___copy_helper_block_e8_32s40s48s56w : 84 -> 72
~ ___destroy_helper_block_e8_32s40s48s56w : 76 -> 64
~ -[CDXController handleWebAuthRequestAtURL:completionBlock:] : 132 -> 120
~ -[CDXController containerInfoTask:completedWithContainers:error:] : 168 -> 156
~ -[CDXController mkcolTask:parsedPropStats:error:] : 124 -> 112
~ -[CDXController propPatchTask:parsedResponses:error:] : 124 -> 112
~ -[CDXController deleteTask:completedWithError:] : 124 -> 112
~ -[CDXController _limitBulkRequestResources:maxBulkImportResources:maxBulkCRUDResources:] : 256 -> 244
~ -[CDXController containerQueryTask:completedWithFoundItems:limitReached:error:] : 184 -> 172
~ -[CDXController urlForPerson:homeInfo:] : 332 -> 320
~ -[CDXController taskGroup:didFinishWithError:] : 104 -> 92
~ -[CDXController trafficLogHandle] : 136 -> 124
~ +[CDXController trafficLogScheduler] : 68 -> 56
~ ___36+[CDXController trafficLogScheduler]_block_invoke : 76 -> 64
~ ___50-[CDXController coreDAVLogTransmittedDataPartial:]_block_invoke : 76 -> 64
~ _OUTLINED_FUNCTION_2 : 36 -> 24
~ _OUTLINED_FUNCTION_5 : 32 -> 20
~ -[CDXRecordCache _fillCacheIfEmpty] : 72 -> 60
~ -[CDXRecordCache findRecordWithVCardUID:inCollectionPath:] : 160 -> 148
~ -[CDXRecordCache findRecordWithPath:] : 376 -> 364
~ -[CDXRecordCache allPaths] : 56 -> 44
~ -[CDXRecordCache unsyncedRecords] : 56 -> 44
~ -[CDXRecordCache syncedRecords] : 56 -> 44
~ -[CDXRecordCache findUnsyncedRecordWithVCardUID:inCollectionPath:] : 160 -> 148
~ -[CDXRecordCache findUnsyncedRecordWithPath:] : 408 -> 396
~ -[CDXRecordCache collectionGroupForPath:] : 100 -> 88
~ -[CDXRecordCache .cxx_destruct] : 128 -> 116
~ -[CDXActionPayload .cxx_destruct] : 104 -> 92
~ -[CDXLocalDB unsyncedErrorsInContainers:andActions:] : 1788 -> 1776
~ -[CDXLocalDB container] : 208 -> 196
~ -[CDXLocalDB _updateMembershipOfGroup:memberVCardUIDs:collectionPath:addOnly:] : 4416 -> 4404
~ -[CDXLocalDB _updateGroupFromVCardInfo:newGroup:] : 2256 -> 2244
~ -[CDXLocalDB _cdxFindExistingPersonFor:matchingUID:orItemPath:] : 400 -> 388
~ -[CDXLocalDB containerSyncTask:retrievedAddedOrModifiedActions:removed:] : 164 -> 152
~ -[CDXLocalDB setSyncState:unsynced:] : 116 -> 104
~ -[CDXLocalDB .cxx_destruct] : 172 -> 160
~ _OUTLINED_FUNCTION_7 : 40 -> 28
~ _OUTLINED_FUNCTION_13 : 28 -> 16
~ _OUTLINED_FUNCTION_14 : 24 -> 12
~ _OUTLINED_FUNCTION_16 : 28 -> 16
~ _OUTLINED_FUNCTION_17 : 32 -> 20
~ _OUTLINED_FUNCTION_18 : 24 -> 12
~ +[NSString(CDXExtensions) cdxStringWithNameSpace:andName:] : 148 -> 136
~ -[NSString(CDXExtensions) cdxCopyStringByRemovingPercentEscapesForHREF] : 64 -> 52
~ -[NSString(CDXExtensions) cdxCopyMD5hash] : 120 -> 108
~ -[NSDictionary(CDXExtensions) cdxObjectForKeyWithNameSpace:andName:] : 188 -> 176
~ -[NSMutableDictionary(CDXExtensions) cdxRemoveObjectForKeyCaseInsensitive:] : 120 -> 108
~ -[NSMutableDictionary(CDXExtensions) cdxSetObject:forKeyCaseInsensitive:] : 164 -> 152
~ -[NSArray(CDXContainerInfo) cdxCopySortedStringArray] : 68 -> 56
~ +[NSDictionary(CDXContainerInfo) cdxContainerInfo_create:] : 1236 -> 1224
~ -[NSDictionary(CDXContainerInfo) cdxContainerInfo_bestTitle] : 148 -> 136
~ -[NSDictionary(CDXContainerInfo) cdxContainerInfo_meCardPath] : 120 -> 108
~ -[NSDictionary(CDXContainerInfo) cdxContainerInfo_hasReadPrivileges] : 120 -> 108
~ -[NSDictionary(CDXContainerInfo) cdxContainerInfo_hasWritePropertiesPrivileges] : 148 -> 136
~ +[NSDictionary(CDXHomeInfo) cdxHomeInfo_create:withOneAddressBookOnly:preferSharedAddressBook:] : 660 -> 648
~ +[NSDictionary(CDXHomeInfo) cdxHomeInfo_createWithContainerInfos:] : 368 -> 356
~ -[NSDictionary(CDXHomeInfo) cdxHomeInfo_mainSharedAddressBookPath] : 444 -> 432
~ -[NSDictionary(CDXHomeInfo) cdxHomeInfo_searchAddressBookInfo] : 92 -> 80
~ -[NSDictionary(CDXHomeInfo) cdxHomeInfo_mainSharedAddressBookInfo] : 92 -> 80
~ -[NSDictionary(CDXHomeInfo) cdxHomeInfo_searchAddressBookURLString] : 300 -> 288
~ -[NSDictionary(CDXHomeInfo) cdxHomeInfo_cardDAVHomeURLString] : 112 -> 100
~ -[NSDictionary(CDXHomeInfo) cdxHomeInfo_cardDAVHomeCardURLString] : 80 -> 68
~ -[NSDictionary(CDXHomeInfo) cdxHomeInfo_cardDAVHomeCardInfo] : 108 -> 96
~ +[UKerberosCredentialCache setInfo:forHost:user:] : 428 -> 416
~ +[UKerberosCredentialCache getInfoForHost:user:] : 260 -> 248
~ _GetCredentialForKerberosTicket : 960 -> 948
~ _GetPrincipalsForKerberosTicket : 1024 -> 1012
~ _ObscureIt : 208 -> 196
~ _UKerberos_MarkIdentityInvalid : 256 -> 244
~ _Kerb_GetErrorDesc : 124 -> 100
~ -[CardDAVSource(PushNotification) pushKeys] : 392 -> 380
~ -[CardDAVSource(PushNotification) enabledPushTransports] : 1084 -> 1072
~ -[CDXGroupValidator .cxx_destruct] : 80 -> 68
~ -[CardDAVSource(Visitation) acceptVisitor:] : 88 -> 76
~ -[CDXPlistChangeTracker readOfflineDeletedItems] : 500 -> 488
~ ___50-[CDXPlistChangeTracker _readOfflineDeletedItems:]_block_invoke : 216 -> 204
~ -[CDXPlistChangeTracker rememberUIDsForDeletion:withHomeInfo:fromAddressBook:] : 1440 -> 1428
~ -[CDXPlistChangeTracker keyForOfflineDeletedItemsWithFileName:collectionPath:] : 172 -> 160
~ _OUTLINED_FUNCTION_3 : 28 -> 16
~ _OUTLINED_FUNCTION_4 : 28 -> 16
~ -[CDXLocallyDeletedRecordEvent description] : 180 -> 168
~ -[CDXLocallyDeletedRecordEvent .cxx_destruct] : 80 -> 68
~ +[CDXThermalDelay sleepWithThermalMonitor:] : 120 -> 108
~ +[CDXThermalDelay sleepWithThermalMonitor:sleepHelper:] : 192 -> 180
~ +[CDXThermalDelay pauseSyncingForTimeInterval:sleepHelper:] : 108 -> 96
~ +[CDXThermalDelay pauseSyncingUntilThermalPressureEases:sleepHelper:] : 192 -> 180
~ +[CDXThermalDelaySleepHelper sharedSleepHelper] : 160 -> 148
~ ___47+[CDXThermalDelaySleepHelper sharedSleepHelper]_block_invoke : 60 -> 48
~ _OUTLINED_FUNCTION_2 : 32 -> 20
~ +[CDXImportsPersonProperties importPropertiesFromPerson:toPerson:] : 80 -> 68
~ +[CDXImportsPersonProperties helperWithSourcePerson:destinationPerson:] : 128 -> 116
~ -[CDXImportsPersonProperties updateProperty:] : 168 -> 156
~ -[CDXImportsPersonProperties updateValue:forProperty:] : 168 -> 156
~ +[CDXImportsPersonProperties regularPropertiesToCopy] : 68 -> 56
~ -[CDXImportsPersonProperties moveImages] : 436 -> 424
~ -[CDXImportsPersonProperties moveImagePropertiesIncludingImageDataProperties:] : 576 -> 564
~ -[CDXImportsPersonProperties .cxx_destruct] : 68 -> 56
~ -[ABPerson(CDX) _cdx_isEmptyPerson_on_upload] : 84 -> 72
~ +[CDXCardLogger loggerWithAccountName:inFolder:] : 224 -> 212
~ -[CDXCardLogger logCard:withName:] : 148 -> 136
~ -[CDXCardLogger makeSureFolderExists] : 92 -> 80
~ -[CDXCardLogger outputURLForName:] : 168 -> 156
~ -[CDXCardLogger filenameWithName:date:] : 152 -> 140
~ -[CDXCardLogger timestampForDate:] : 124 -> 112
~ +[CDXCardLogger dateFormatter] : 76 -> 64
~ -[CDXTaskManager _makeStateTransition].cold.1 : 92 -> 80
~ -[CDXTaskManager _makeStateTransition].cold.2 : 92 -> 80
```
