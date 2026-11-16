## SafariCore

> `/System/Library/PrivateFrameworks/SafariCore.framework/Versions/A/SafariCore`

```diff

-626.1.12.11.4
-  __TEXT.__text: 0x23010c
-  __TEXT.__objc_methlist: 0xded4
+626.1.17.0.0
+  __TEXT.__text: 0x2319e0
+  __TEXT.__objc_methlist: 0xdf64
   __TEXT.__const: 0x8d14
-  __TEXT.__gcc_except_tab: 0x81d0
-  __TEXT.__cstring: 0x1a27b
+  __TEXT.__gcc_except_tab: 0x82b0
+  __TEXT.__cstring: 0x1a56b
   __TEXT.__ustring: 0x1dd8
-  __TEXT.__oslogstring: 0xf191
+  __TEXT.__oslogstring: 0xf3b1
   __TEXT.__dlopen_cstrs: 0x157
   __TEXT.__constg_swiftt: 0x26e0
   __TEXT.__swift5_typeref: 0x2b4e

   __TEXT.__swift5_capture: 0x162c
   __TEXT.__swift5_protos: 0x40
   __TEXT.__swift5_mpenum: 0x18
-  __TEXT.__unwind_info: 0xd0d8
-  __TEXT.__eh_frame: 0xbcb8
+  __TEXT.__unwind_info: 0xd128
+  __TEXT.__eh_frame: 0xbd30
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2ab8
+  __DATA_CONST.__const: 0x2ad0
   __DATA_CONST.__objc_classlist: 0x770
   __DATA_CONST.__objc_catlist: 0x160
   __DATA_CONST.__objc_protolist: 0x208
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7cf0
+  __DATA_CONST.__objc_selrefs: 0x7d48
   __DATA_CONST.__objc_protorefs: 0xf8
   __DATA_CONST.__objc_superrefs: 0x4c0
   __DATA_CONST.__objc_arraydata: 0x2a98
   __DATA_CONST.__got: 0x1500
-  __AUTH_CONST.__const: 0x101c0
-  __AUTH_CONST.__cfstring: 0x1bb40
-  __AUTH_CONST.__objc_const: 0x17560
+  __AUTH_CONST.__const: 0x10230
+  __AUTH_CONST.__cfstring: 0x1bc00
+  __AUTH_CONST.__objc_const: 0x175a0
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x930
   __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH_CONST.__objc_arrayobj: 0x588
-  __AUTH_CONST.__auth_got: 0x22c0
+  __AUTH_CONST.__auth_got: 0x22c8
   __AUTH.__objc_data: 0xd28
   __AUTH.__data: 0x710
-  __DATA.__objc_ivar: 0xd44
+  __DATA.__objc_ivar: 0xd48
   __DATA.__data: 0x3b30
-  __DATA.__bss: 0xb090
+  __DATA.__bss: 0xb0b0
   __DATA.__common: 0x88
   __DATA_DIRTY.__objc_data: 0x4548
   __DATA_DIRTY.__data: 0x1a80
-  __DATA_DIRTY.__bss: 0xde0
+  __DATA_DIRTY.__bss: 0xdd0
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppIntents.framework/Versions/A/AppIntents

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12647
-  Symbols:   15270
-  CStrings:  5592
+  Functions: 12664
+  Symbols:   15304
+  CStrings:  5615
 
Symbols:
+ +[NSURLSessionConfiguration(SafariCoreExtras) safari_ephemeralSessionConfigurationWithSecondaryIdentifier:]
+ +[WBSFeatureAvailability isNotifyMeWhenInternalAnalyticsEnabled]
+ +[WBSSavedAccountStore _sharedStoreWithAutoFillQuirksManager:]
+ +[WBSSavedAccountStore sharedStoreWithAutoFillQuirksManager:]
+ -[WBSAnalyticsLogger reportNotifyMeWhenPollResultWithDetails:errorType:automationID:url:userPrompt:]
+ -[WBSSavedAccountKeychainCoordinator allPersonalSidecarKeychainItemsInPersonalKeychain]
+ -[WBSSavedAccountKeychainCoordinator personalSidecarsFromKeychainItems:]
+ -[WBSSavedAccountStore _loadSavedAccountsFromSharedAccountsGroupsIntoAllSavedAccounts:]
+ -[WBSSavedAccountStore _mergeSavedAccountsFromSharedAccountsGroupsIntoLoadedSavedAccounts]
+ -[WBSSavedAccountStore _resetForReason:]
+ -[WBSSavedAccountStore _resetOnInternalQueueForReason:]
+ -[WBSSavedAccountStore initAndPrewarmSavedAccounts:autoFillQuirksManager:forTesting:]
+ -[WBSSavedAccountStore initWithAuthenticationServicesAgentProxy:shouldPrewarmSavedAccounts:limitedToDomains:autoFillQuirksManager:forTesting:]
+ -[WBSWellKnownURLResponseCodeReliabilityChecker initWithURL:sessionConfiguration:]
+ GCC_except_table105
+ GCC_except_table107
+ GCC_except_table161
+ GCC_except_table213
+ GCC_except_table217
+ GCC_except_table268
+ GCC_except_table271
+ GCC_except_table283
+ GCC_except_table288
+ GCC_except_table293
+ GCC_except_table298
+ GCC_except_table301
+ GCC_except_table303
+ GCC_except_table305
+ GCC_except_table308
+ GCC_except_table311
+ GCC_except_table314
+ GCC_except_table320
+ GCC_except_table344
+ GCC_except_table348
+ GCC_except_table354
+ GCC_except_table364
+ GCC_except_table366
+ GCC_except_table373
+ GCC_except_table375
+ GCC_except_table377
+ GCC_except_table382
+ GCC_except_table385
+ GCC_except_table399
+ GCC_except_table401
+ GCC_except_table403
+ GCC_except_table407
+ GCC_except_table409
+ GCC_except_table412
+ GCC_except_table416
+ GCC_except_table420
+ GCC_except_table426
+ GCC_except_table428
+ GCC_except_table430
+ GCC_except_table434
+ GCC_except_table436
+ GCC_except_table444
+ GCC_except_table456
+ GCC_except_table462
+ GCC_except_table465
+ GCC_except_table477
+ GCC_except_table480
+ GCC_except_table485
+ GCC_except_table491
+ GCC_except_table493
+ GCC_except_table496
+ GCC_except_table498
+ GCC_except_table502
+ GCC_except_table505
+ GCC_except_table507
+ GCC_except_table510
+ GCC_except_table514
+ GCC_except_table525
+ GCC_except_table529
+ GCC_except_table531
+ GCC_except_table533
+ GCC_except_table535
+ GCC_except_table537
+ GCC_except_table539
+ GCC_except_table541
+ GCC_except_table543
+ GCC_except_table545
+ GCC_except_table547
+ GCC_except_table549
+ GCC_except_table551
+ _OBJC_IVAR_$_WBSSavedAccountStore._cachedPersonalSidecarItems
+ _SecTaskCreateFromSelf
+ _WBSDebugNotifyMeWhenInternalAnalyticsEnabledKey
+ _WBSPasswordWarningManagerDidUpdateWarningsNotification
+ __ZL25stringForLayoutProvenance28WBSAnalyticsLayoutProvenance
+ __ZL30configureCommonSessionSettingsP25NSURLSessionConfigurationP8NSString
+ __ZZL30configureCommonSessionSettingsP25NSURLSessionConfigurationP8NSStringE9onceToken
+ __ZZL40processCanAttributeNetworkingToOtherAppsvE33canAttributeNetworkingToOtherApps
+ __ZZL40processCanAttributeNetworkingToOtherAppsvE9onceToken
+ ___100-[WBSAnalyticsLogger reportNotifyMeWhenPollResultWithDetails:errorType:automationID:url:userPrompt:]_block_invoke
+ ___142-[WBSSavedAccountStore initWithAuthenticationServicesAgentProxy:shouldPrewarmSavedAccounts:limitedToDomains:autoFillQuirksManager:forTesting:]_block_invoke
+ ___142-[WBSSavedAccountStore initWithAuthenticationServicesAgentProxy:shouldPrewarmSavedAccounts:limitedToDomains:autoFillQuirksManager:forTesting:]_block_invoke_2
+ ___142-[WBSSavedAccountStore initWithAuthenticationServicesAgentProxy:shouldPrewarmSavedAccounts:limitedToDomains:autoFillQuirksManager:forTesting:]_block_invoke_3
+ ___40-[WBSSavedAccountStore _resetForReason:]_block_invoke
+ ___40-[WBSSavedAccountStore _resetForReason:]_block_invoke_2
+ ___55-[WBSSavedAccountStore _resetOnInternalQueueForReason:]_block_invoke
+ ___62+[WBSSavedAccountStore _sharedStoreWithAutoFillQuirksManager:]_block_invoke
+ ___72-[WBSSavedAccountKeychainCoordinator personalSidecarsFromKeychainItems:]_block_invoke
+ ___90-[WBSSavedAccountStore _mergeSavedAccountsFromSharedAccountsGroupsIntoLoadedSavedAccounts]_block_invoke
+ ____ZL30configureCommonSessionSettingsP25NSURLSessionConfigurationP8NSString_block_invoke
+ ____ZL40processCanAttributeNetworkingToOtherAppsv_block_invoke
+ ___block_descriptor_56_e8_32s40s48r_e43_v16?0"WBSPasswordWarningTopFraudTargets"8l
+ ___block_descriptor_57_e8_32s40s48r_e5_v8?0l
+ ___block_descriptor_72_ea8_32s40s48s_e19_"NSDictionary"8?0l
+ ___savedAccountsWithPasswordCredentials_block_invoke
+ __sharedStoreWithAutoFillQuirksManager:.onceToken
+ _objc_msgSend$_loadSavedAccountsFromSharedAccountsGroupsIntoAllSavedAccounts:
+ _objc_msgSend$_mergeSavedAccountsFromSharedAccountsGroupsIntoLoadedSavedAccounts
+ _objc_msgSend$_resetForReason:
+ _objc_msgSend$_resetOnInternalQueueForReason:
+ _objc_msgSend$_sharedStoreWithAutoFillQuirksManager:
+ _objc_msgSend$allPersonalSidecarKeychainItemsInPersonalKeychain
+ _objc_msgSend$initAndPrewarmSavedAccounts:autoFillQuirksManager:forTesting:
+ _objc_msgSend$initWithAuthenticationServicesAgentProxy:shouldPrewarmSavedAccounts:limitedToDomains:autoFillQuirksManager:forTesting:
+ _objc_msgSend$initWithURL:sessionConfiguration:
+ _objc_msgSend$personalSidecarsFromKeychainItems:
+ _objc_msgSend$safari_ephemeralSessionConfigurationWithSecondaryIdentifier:
+ _objc_msgSend$setAutoFillQuirksManager:
+ _os_unfair_recursive_lock_lock
- -[WBSSavedAccountKeychainCoordinator _allPersonalSidecarEntriesInPersonalKeychain]
- -[WBSSavedAccountStore _resetOnInternalQueue]
- -[WBSSavedAccountStore initWithAuthenticationServicesAgentProxy:shouldPrewarmSavedAccounts:limitedToDomains:forTesting:]
- GCC_except_table102
- GCC_except_table104
- GCC_except_table139
- GCC_except_table159
- GCC_except_table211
- GCC_except_table215
- GCC_except_table282
- GCC_except_table286
- GCC_except_table289
- GCC_except_table294
- GCC_except_table300
- GCC_except_table302
- GCC_except_table304
- GCC_except_table307
- GCC_except_table310
- GCC_except_table313
- GCC_except_table319
- GCC_except_table343
- GCC_except_table345
- GCC_except_table347
- GCC_except_table351
- GCC_except_table356
- GCC_except_table367
- GCC_except_table372
- GCC_except_table376
- GCC_except_table378
- GCC_except_table383
- GCC_except_table398
- GCC_except_table400
- GCC_except_table402
- GCC_except_table404
- GCC_except_table406
- GCC_except_table410
- GCC_except_table411
- GCC_except_table415
- GCC_except_table425
- GCC_except_table427
- GCC_except_table429
- GCC_except_table433
- GCC_except_table435
- GCC_except_table443
- GCC_except_table455
- GCC_except_table460
- GCC_except_table464
- GCC_except_table473
- GCC_except_table478
- GCC_except_table481
- GCC_except_table486
- GCC_except_table489
- GCC_except_table492
- GCC_except_table497
- GCC_except_table499
- GCC_except_table503
- GCC_except_table506
- GCC_except_table508
- GCC_except_table509
- GCC_except_table513
- GCC_except_table516
- GCC_except_table526
- GCC_except_table530
- GCC_except_table532
- GCC_except_table534
- GCC_except_table536
- GCC_except_table538
- GCC_except_table540
- GCC_except_table542
- GCC_except_table544
- GCC_except_table546
- __ZL30configureCommonSessionSettingsP25NSURLSessionConfiguration
- ___120-[WBSSavedAccountStore initWithAuthenticationServicesAgentProxy:shouldPrewarmSavedAccounts:limitedToDomains:forTesting:]_block_invoke
- ___120-[WBSSavedAccountStore initWithAuthenticationServicesAgentProxy:shouldPrewarmSavedAccounts:limitedToDomains:forTesting:]_block_invoke_2
- ___120-[WBSSavedAccountStore initWithAuthenticationServicesAgentProxy:shouldPrewarmSavedAccounts:limitedToDomains:forTesting:]_block_invoke_3
- ___29-[WBSSavedAccountStore reset]_block_invoke
- ___29-[WBSSavedAccountStore reset]_block_invoke_2
- ___35+[WBSSavedAccountStore sharedStore]_block_invoke
- ___45-[WBSSavedAccountStore _resetOnInternalQueue]_block_invoke
- ___75-[WBSSavedAccountKeychainCoordinator allPersonalSidecarsInPersonalKeychain]_block_invoke
- ___76-[WBSSavedAccountStore setShouldShowServiceNamesForPasswordAndPasskeyItems:]_block_invoke_4
- ___90-[WBSSavedAccountKeychainCoordinator allRecentlyDeletedPersonalSidecarsInPersonalKeychain]_block_invoke
- ___block_descriptor_40_e8_32s_e43_v16?0"WBSPasswordWarningTopFraudTargets"8l
- ___block_descriptor_49_e8_32s40s_e5_v8?0l
- _objc_msgSend$_allPersonalSidecarEntriesInPersonalKeychain
- _objc_msgSend$_resetOnInternalQueue
- _objc_msgSend$initAndPrewarmSavedAccounts:forTesting:
- _objc_msgSend$initWithAuthenticationServicesAgentProxy:shouldPrewarmSavedAccounts:limitedToDomains:forTesting:
- _os_unfair_recursive_lock_lock_with_options
CStrings:
+ "Attributing network session to Safari, but %{public}@ lacks the socket delegate entitlement and has no secondary identifier; DNS resolution may be rejected with NoAuth"
+ "Not attributing network sessions with secondary identifier %{public}@ to Safari: %{public}@ lacks the socket delegate entitlement"
+ "Recently Deleted maintenance changed the keychain"
+ "Resetting saved account store because %{public}s"
+ "Shared account groups changed (%lu groups); resetting saved account store"
+ "Shared account groups loaded (%lu groups); merging their saved accounts into the loaded saved accounts"
+ "Skipping account store reset because the key bag is locked (reset reason: %{public}s)"
+ "WBSDebugNotifyMeWhenInternalAnalyticsEnabled"
+ "WBSPasswordWarningManagerDidUpdateWarningsNotification"
+ "a client requested a reset"
+ "automationID"
+ "com.apple.Safari.NotifyMeWhen.PollResultWithDetails"
+ "com.apple.private.network.socket-delegate"
+ "contributed saved accounts were moved back to the personal keychain"
+ "items from exited groups were cleaned up"
+ "loading saved accounts after loading groups was requested"
+ "passwords with invalid authentication types were migrated"
+ "saved accounts were moved out of a group"
+ "saved accounts with unknown original contributors were cleaned up"
+ "shared account groups changed"
+ "the AuthenticationServicesAgent maintenance activity ended"
+ "the AutoFill quirks manager changed"
+ "the keychain changed"
+ "the service names setting changed"
+ "userPrompt"
- "No topic: the topic must be a non-empty string."
- "Skipping account store reset because the key bag is locked"
```
