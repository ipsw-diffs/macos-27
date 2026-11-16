## Mail

> `/System/Library/PrivateFrameworks/Mail.framework/Versions/A/Mail`

```diff

-3901.300.31.0.0
-  __TEXT.__text: 0xaab0d8
-  __TEXT.__objc_methlist: 0x1a014
-  __TEXT.__gcc_except_tab: 0x4ccec
-  __TEXT.__const: 0x62249
-  __TEXT.__cstring: 0x336c4
-  __TEXT.__oslogstring: 0x24349
+3901.300.60.0.0
+  __TEXT.__text: 0xab6c60
+  __TEXT.__objc_methlist: 0x1a12c
+  __TEXT.__gcc_except_tab: 0x4d4b0
+  __TEXT.__const: 0x62b59
+  __TEXT.__cstring: 0x33884
+  __TEXT.__oslogstring: 0x245c9
   __TEXT.__ustring: 0x44
-  __TEXT.__swift5_typeref: 0xf336
-  __TEXT.__constg_swiftt: 0xc550
-  __TEXT.__swift5_reflstr: 0xf010
-  __TEXT.__swift5_fieldmd: 0x13de4
-  __TEXT.__swift5_builtin: 0xc6c
-  __TEXT.__swift5_assocty: 0x1c60
-  __TEXT.__swift5_proto: 0x2350
-  __TEXT.__swift5_types: 0x15e0
-  __TEXT.__swift5_capture: 0x2a270
-  __TEXT.__swift5_mpenum: 0x750
-  __TEXT.__swift5_protos: 0x78
-  __TEXT.__unwind_info: 0x2ffd8
-  __TEXT.__eh_frame: 0x16900
+  __TEXT.__swift5_typeref: 0xf3aa
+  __TEXT.__constg_swiftt: 0xc750
+  __TEXT.__swift5_reflstr: 0xf0e0
+  __TEXT.__swift5_fieldmd: 0x13ff8
+  __TEXT.__swift5_builtin: 0xca8
+  __TEXT.__swift5_assocty: 0x1ca8
+  __TEXT.__swift5_proto: 0x23c4
+  __TEXT.__swift5_types: 0x1620
+  __TEXT.__swift5_capture: 0x2a2cc
+  __TEXT.__swift5_mpenum: 0x774
+  __TEXT.__swift5_protos: 0x7c
+  __TEXT.__unwind_info: 0x2feb8
+  __TEXT.__eh_frame: 0x16c64
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x11930
-  __DATA_CONST.__objc_classlist: 0xe18
+  __DATA_CONST.__const: 0x11938
+  __DATA_CONST.__objc_classlist: 0xe10
   __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0x5c0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0xe4c0
+  __DATA_CONST.__objc_selrefs: 0xe530
   __DATA_CONST.__objc_protorefs: 0x1e0
   __DATA_CONST.__objc_superrefs: 0x840
   __DATA_CONST.__objc_arraydata: 0x278
   __DATA_CONST.__got: 0x38a0
-  __AUTH_CONST.__const: 0x95c58
-  __AUTH_CONST.__cfstring: 0x1aa00
-  __AUTH_CONST.__objc_const: 0x2c520
+  __AUTH_CONST.__const: 0x962d8
+  __AUTH_CONST.__cfstring: 0x1a9e0
+  __AUTH_CONST.__objc_const: 0x2c660
   __AUTH_CONST.__weak_auth_got: 0x20
-  __AUTH_CONST.__objc_intobj: 0xd38
+  __AUTH_CONST.__objc_intobj: 0xd08
   __AUTH_CONST.__objc_arrayobj: 0x288
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_floatobj: 0x20
-  __AUTH_CONST.__auth_got: 0x3798
-  __AUTH.__objc_data: 0x6868
-  __AUTH.__data: 0xaa08
-  __DATA.__objc_ivar: 0x1660
-  __DATA.__data: 0xd2ac
+  __AUTH_CONST.__auth_got: 0x3778
+  __AUTH.__objc_data: 0x6818
+  __AUTH.__data: 0xa9b8
+  __DATA.__objc_ivar: 0x167c
+  __DATA.__data: 0xd384
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x458b8
+  __DATA.__bss: 0x46528
   __DATA.__common: 0xe6c
   __DATA_DIRTY.__objc_data: 0x25d0
   __DATA_DIRTY.__data: 0x10
-  __DATA_DIRTY.__bss: 0x898
+  __DATA_DIRTY.__bss: 0x888
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AddressBook.framework/Versions/A/AddressBook
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/swift/libswift_DarwinFoundation2.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 45110
-  Symbols:   29145
-  CStrings:  8001
+  Functions: 45384
+  Symbols:   29237
+  CStrings:  8015
 
Symbols:
+ +[MFEWSAccountTaskManager numberOfFoldersPendingGraphMigrationResyncForAccount:]
+ +[MFExchangeAccount isGraphSyncStateCaughtUp:]
+ +[MFExchangeAccount mailboxesPendingGraphMigrationResync:]
+ -[MFEWSAccountSyncActivity cancel]
+ -[MFEWSAccountTaskManager _checkGraphMigrationResyncCompletionIfNeeded]
+ -[MFEWSAccountTaskManager isCheckingGraphMigrationResync]
+ -[MFEWSAccountTaskManager needsGraphMigrationResyncRecheck]
+ -[MFEWSAccountTaskManager setIsCheckingGraphMigrationResync:]
+ -[MFEWSAccountTaskManager setNeedsGraphMigrationResyncRecheck:]
+ -[MFEWSCreateEventReplyRequestOperation mapRemoteIDsUsingBlock:]
+ -[MFEWSCreateFolderRequestOperation mapRemoteIDsUsingBlock:]
+ -[MFEWSCreateItemRequestOperation mapRemoteIDsUsingBlock:]
+ -[MFEWSCreateMessageRequestOperation mapRemoteIDsUsingBlock:]
+ -[MFEWSDeleteFolderRequestOperation mapRemoteIDsUsingBlock:]
+ -[MFEWSDeleteItemsRequestOperation mapRemoteIDsUsingBlock:]
+ -[MFEWSGateway mapOfflineRequestRemoteIDsUsingBlock:]
+ -[MFEWSMoveFolderRequestOperation mapRemoteIDsUsingBlock:]
+ -[MFEWSPersistActionResultsOperation _removeMigrationTagFromRestoredSourceMessagesForAction:results:]
+ -[MFEWSPersistMessageMetadataOperation _messagesWithRemoteIDs:inMailbox:options:includingMigratedRemoteIDs:library:]
+ -[MFEWSRequestOperation mapRemoteIDsUsingBlock:]
+ -[MFExchangeAccount _currentMigrationStatus]
+ -[MFExchangeAccount _finishGraphMigrationProgress]
+ -[MFExchangeAccount _loadedMailboxesPendingGraphMigrationResync]
+ -[MFExchangeAccount _setEWSToGraphMigrationStatus:]
+ -[MFExchangeAccount _stopGraphMigrationProgress]
+ -[MFExchangeAccount _writeMigrationStatus:]
+ -[MFExchangeAccount completeGraphMigrationResync]
+ -[MFExchangeAccount graphMigrationResyncDidFinishForMailbox:]
+ -[MFExchangeAccount isGraphMigrationResyncPending]
+ -[MFExchangeAccount isMailboxPendingGraphMigrationResync:]
+ -[MFExchangeAccount migrateOfflineRequestIDs]
+ -[MFExchangeAccount numberOfMailboxesPendingGraphMigrationResync]
+ -[MFExchangeAccount setEWSToGraphMigrationConverted]
+ -[MFExchangeAccount setEWSToGraphMigrationConverting]
+ -[MFExchangeAccount shouldHoldConnectionsForGraphMigration]
+ -[MFExchangeAccount test_graphMigrationProgress]
+ -[MFExchangeAccount updateGraphMigrationProgress]
+ -[MFLibrary messagesWithRemoteIDPrefix:inMailbox:options:]
+ GCC_except_table210
+ GCC_except_table271
+ GCC_except_table287
+ GCC_except_table288
+ GCC_except_table348
+ GCC_except_table356
+ GCC_except_table360
+ GCC_except_table363
+ GCC_except_table364
+ GCC_except_table367
+ GCC_except_table371
+ GCC_except_table375
+ GCC_except_table376
+ GCC_except_table382
+ GCC_except_table383
+ GCC_except_table388
+ GCC_except_table389
+ GCC_except_table392
+ GCC_except_table393
+ GCC_except_table400
+ GCC_except_table401
+ GCC_except_table411
+ GCC_except_table414
+ GCC_except_table415
+ GCC_except_table419
+ GCC_except_table420
+ GCC_except_table456
+ GCC_except_table461
+ GCC_except_table469
+ GCC_except_table470
+ GCC_except_table482
+ GCC_except_table483
+ GCC_except_table503
+ GCC_except_table511
+ GCC_except_table517
+ GCC_except_table525
+ GCC_except_table526
+ GCC_except_table531
+ GCC_except_table534
+ _MCProgressUserInfoKeyUpdatingAccount
+ _MFExchangeMigratedRemoteIDPrefix
+ _MFFinishGraphMigrationProgress
+ _OBJC_CLASS_$_EDAddSearchableAccountsTableUpgradeStep
+ _OBJC_CLASS_$_EDServerMessagePersistence
+ _OBJC_IVAR_$_MFEWSAccountSyncActivity._mailboxesAwaitingFolderHierarchy
+ _OBJC_IVAR_$_MFEWSAccountTaskManager._isCheckingGraphMigrationResync
+ _OBJC_IVAR_$_MFEWSAccountTaskManager._needsGraphMigrationResyncRecheck
+ _OBJC_IVAR_$_MFExchangeAccount._graphMigrationProgress
+ _OBJC_IVAR_$_MFExchangeAccount._graphMigrationProgressQueue
+ _OBJC_IVAR_$_MFExchangeAccount._graphMigrationResyncLock
+ _OBJC_IVAR_$_MFExchangeAccount._graphMigrationTrackingEnded
+ _OBJC_IVAR_$_MFExchangeAccount._mailboxesPendingGraphMigrationResync
+ _OfflineRequestClasses
+ _SecTrustEvaluateWithError
+ __DATA__TtC12NIOIMAPCore219NIONetworkInterface
+ __DATA__TtCV12NIOIMAPCore216NIONetworkDeviceP33_0376AFE35F6C75FF3DBC73C1B95A56AC7Backing
+ __IVARS__TtC12NIOIMAPCore219NIONetworkInterface
+ __IVARS__TtC12NIOIMAPCore23Box
+ __IVARS__TtCV12NIOIMAPCore216NIONetworkDeviceP33_0376AFE35F6C75FF3DBC73C1B95A56AC7Backing
+ __METACLASS_DATA__TtC12NIOIMAPCore219NIONetworkInterface
+ __METACLASS_DATA__TtCV12NIOIMAPCore216NIONetworkDeviceP33_0376AFE35F6C75FF3DBC73C1B95A56AC7Backing
+ ___45-[MFExchangeAccount migrateOfflineRequestIDs]_block_invoke
+ ___48-[MFExchangeAccount _stopGraphMigrationProgress]_block_invoke
+ ___48-[MFExchangeAccount test_graphMigrationProgress]_block_invoke
+ ___49-[MFExchangeAccount updateGraphMigrationProgress]_block_invoke
+ ___53-[MFEWSGateway mapOfflineRequestRemoteIDsUsingBlock:]_block_invoke
+ ___53-[MFEWSGateway mapOfflineRequestRemoteIDsUsingBlock:]_block_invoke_2
+ ___58-[MFLibrary messagesWithRemoteIDPrefix:inMailbox:options:]_block_invoke
+ ___71-[MFEWSAccountTaskManager _checkGraphMigrationResyncCompletionIfNeeded]_block_invoke
+ ___71-[MFEWSAccountTaskManager _checkGraphMigrationResyncCompletionIfNeeded]_block_invoke_2
+ ___block_descriptor_40_ea8_32bs_e22_16?0"NSDictionary"8l
+ ___block_descriptor_48_ea8_32s40bs_e35_v32?0"NSString"8"NSString"16^B24l
+ _associated conformance 12NIOIMAPCore212NIOBSDSocketO11OptionLevelVSHAASQ
+ _associated conformance 12NIOIMAPCore212NIOBSDSocketO13AddressFamilyVSHAASQ
+ _associated conformance 12NIOIMAPCore212NIOBSDSocketO14ProtocolFamilyVSHAASQ
+ _associated conformance 12NIOIMAPCore212NIOBSDSocketO6OptionVSHAASQ
+ _associated conformance 12NIOIMAPCore213SocketAddressOSHAASQ
+ _associated conformance 12NIOIMAPCore216NIONetworkDeviceVSHAASQ
+ _associated conformance 12NIOIMAPCore218SocketAddressErrorO25FailedToParseIPByteBufferVSHAASQ
+ _freeaddrinfo
+ _freeifaddrs
+ _get_enum_tag_for_layout_string 12NIOIMAPCore213SocketAddressO
+ _get_enum_tag_for_layout_string 12NIOIMAPCore218SocketAddressErrorO
+ _get_enum_tag_for_layout_string 12NIOIMAPCore27IOErrorV18FailureDescriptionO
+ _getaddrinfo
+ _getifaddrs
+ _if_nametoindex
+ _inet_ntop
+ _inet_pton
+ _objc_msgSend$_checkGraphMigrationResyncCompletionIfNeeded
+ _objc_msgSend$_currentMigrationStatus
+ _objc_msgSend$_finishGraphMigrationProgress
+ _objc_msgSend$_loadedMailboxesPendingGraphMigrationResync
+ _objc_msgSend$_messagesWithRemoteIDs:inMailbox:options:includingMigratedRemoteIDs:library:
+ _objc_msgSend$_removeMigrationTagFromRestoredSourceMessagesForAction:results:
+ _objc_msgSend$_setEWSToGraphMigrationStatus:
+ _objc_msgSend$_stopGraphMigrationProgress
+ _objc_msgSend$_writeMigrationStatus:
+ _objc_msgSend$completeGraphMigrationResync
+ _objc_msgSend$graphMigrationResyncDidFinishForMailbox:
+ _objc_msgSend$initWithNewItemIDsBySourceID:missingItemIDs:sourceGoneItemIDs:throttleError:
+ _objc_msgSend$isCheckingGraphMigrationResync
+ _objc_msgSend$isGraphMigrationResyncPending
+ _objc_msgSend$isGraphSyncStateCaughtUp:
+ _objc_msgSend$isMailboxPendingGraphMigrationResync:
+ _objc_msgSend$mailboxesPendingGraphMigrationResync:
+ _objc_msgSend$mapOfflineRequestRemoteIDsUsingBlock:
+ _objc_msgSend$mapRemoteIDsUsingBlock:
+ _objc_msgSend$messagesWithRemoteIDPrefix:inMailbox:options:
+ _objc_msgSend$migrateOfflineRequestIDs
+ _objc_msgSend$needsGraphMigrationResyncRecheck
+ _objc_msgSend$numberOfFoldersPendingGraphMigrationResyncForAccount:
+ _objc_msgSend$numberOfMailboxesPendingGraphMigrationResync
+ _objc_msgSend$remoteIDsBeingMovedOutOfMailboxURL:amongRemoteIDs:
+ _objc_msgSend$setEWSToGraphMigrationConverted
+ _objc_msgSend$setEWSToGraphMigrationConverting
+ _objc_msgSend$setIsCheckingGraphMigrationResync:
+ _objc_msgSend$setNeedsGraphMigrationResyncRecheck:
+ _objc_msgSend$shouldHoldConnectionsForGraphMigration
+ _objc_msgSend$sourceGoneItemIDs
+ _objc_msgSend$updateGraphMigrationProgress
+ _objc_msgSend$utilityQueue
+ _symbolic $s12NIOIMAPCore216SockAddrProtocolP
+ _symbolic SS4host_Si4portt
+ _symbolic _____ 12NIOIMAPCore212NIOBSDSocketO
+ _symbolic _____ 12NIOIMAPCore212NIOBSDSocketO11OptionLevelV
+ _symbolic _____ 12NIOIMAPCore212NIOBSDSocketO13AddressFamilyV
+ _symbolic _____ 12NIOIMAPCore212NIOBSDSocketO14ProtocolFamilyV
+ _symbolic _____ 12NIOIMAPCore212NIOBSDSocketO6OptionV
+ _symbolic _____ 12NIOIMAPCore213SocketAddressO
+ _symbolic _____ 12NIOIMAPCore213SocketAddressO04IPv4C0V
+ _symbolic _____ 12NIOIMAPCore213SocketAddressO04IPv6C0V
+ _symbolic _____ 12NIOIMAPCore213SocketAddressO04UnixbC0V
+ _symbolic _____ 12NIOIMAPCore216NIONetworkDeviceV
+ _symbolic _____ 12NIOIMAPCore216NIONetworkDeviceV7Backing33_0376AFE35F6C75FF3DBC73C1B95A56ACLLC
+ _symbolic _____ 12NIOIMAPCore218SocketAddressErrorO
+ _symbolic _____ 12NIOIMAPCore218SocketAddressErrorO25FailedToParseIPByteBufferV
+ _symbolic _____ 12NIOIMAPCore219NIONetworkInterfaceC
+ _symbolic _____ 12NIOIMAPCore23BoxC
+ _symbolic _____ 12NIOIMAPCore26SystemO
+ _symbolic _____ 12NIOIMAPCore27IOErrorV
+ _symbolic _____ 12NIOIMAPCore27IOErrorV18FailureDescriptionO
+ _symbolic _____ 12NIOIMAPCore27IOErrorV5Error33_CF036C1866A83216E800C0068578574BLLO
+ _symbolic _____7address_SS4hostt So11sockaddr_inV
+ _symbolic _____7address_SS4hostt So12sockaddr_in6V
+ _symbolic _____Sg 12NIOIMAPCore213SocketAddressO
+ _symbolic _____y_____7address_SS4hosttG 12NIOIMAPCore23BoxC So11sockaddr_inV
+ _symbolic _____y_____7address_SS4hosttG 12NIOIMAPCore23BoxC So12sockaddr_in6V
+ _symbolic _____y_____G 12NIOIMAPCore23BoxC So11sockaddr_unV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12NIOIMAPCore216NIONetworkDeviceV
+ _sysconf
+ _type_layout_string 12NIOIMAPCore212NIOBSDSocketO13AddressFamilyV
+ _type_layout_string 12NIOIMAPCore213SocketAddressO
+ _type_layout_string 12NIOIMAPCore213SocketAddressO04IPv4C0V
+ _type_layout_string 12NIOIMAPCore213SocketAddressO04IPv6C0V
+ _type_layout_string 12NIOIMAPCore213SocketAddressO04UnixbC0V
+ _type_layout_string 12NIOIMAPCore216NIONetworkDeviceV
+ _type_layout_string 12NIOIMAPCore218SocketAddressErrorO
+ _type_layout_string 12NIOIMAPCore218SocketAddressErrorO25FailedToParseIPByteBufferV
+ _type_layout_string 12NIOIMAPCore27IOErrorV
+ _type_layout_string 12NIOIMAPCore27IOErrorV18FailureDescriptionO
+ _type_layout_string So20NSJSONReadingOptionsV
- +[MFAccountAliasDiagnostics _aliasDetailsForAccount:]
- +[MFAccountAliasDiagnostics _descriptionForAccount:]
- +[MFAccountAliasDiagnostics _descriptionForAliasValue:]
- +[MFAccountAliasDiagnostics _isEnabled]
- +[MFAccountAliasDiagnostics _markAccountIdentifierAsNotified:]
- +[MFAccountAliasDiagnostics _promptToFileRadarForAccount:]
- +[MFAccountAliasDiagnostics log]
- +[MFAccountAliasDiagnostics notifyOfMissingAliasesForAccount:]
- -[MFExchangeAccount setEWSToGraphMigrationComplete]
- GCC_except_table208
- GCC_except_table254
- GCC_except_table255
- GCC_except_table264
- GCC_except_table334
- GCC_except_table352
- GCC_except_table358
- GCC_except_table362
- GCC_except_table365
- GCC_except_table366
- GCC_except_table369
- GCC_except_table377
- GCC_except_table378
- GCC_except_table384
- GCC_except_table385
- GCC_except_table390
- GCC_except_table391
- GCC_except_table395
- GCC_except_table396
- GCC_except_table404
- GCC_except_table405
- GCC_except_table413
- GCC_except_table417
- GCC_except_table418
- GCC_except_table425
- GCC_except_table426
- GCC_except_table458
- GCC_except_table463
- GCC_except_table479
- GCC_except_table480
- GCC_except_table501
- GCC_except_table509
- GCC_except_table515
- GCC_except_table521
- GCC_except_table522
- GCC_except_table527
- GCC_except_table530
- _OBJC_CLASS_$_MFAccountAliasDiagnostics
- _OBJC_CLASS_$_MSRadarURLBuilder
- _OBJC_IVAR_$_MFExchangeAccount._hasMigrationStatus
- _OBJC_METACLASS_$_MFAccountAliasDiagnostics
- __DATA__TtC12IMAP2Helpers12CertUIPrompt
- __DATA__TtC12IMAP2Helpers18CertUITrustManager
- __IVARS__TtC12IMAP2Helpers12CertUIPrompt
- __IVARS__TtC12IMAP2Helpers18CertUITrustManager
- __METACLASS_DATA__TtC12IMAP2Helpers12CertUIPrompt
- __METACLASS_DATA__TtC12IMAP2Helpers18CertUITrustManager
- __OBJC_$_CLASS_METHODS_MFAccountAliasDiagnostics
- __OBJC_$_CLASS_PROP_LIST_MFAccountAliasDiagnostics
- __OBJC_$_INSTANCE_METHODS__TtC12IMAP2Helpers12CertUIPrompt(IMAP2Helpers)
- __OBJC_$_INSTANCE_METHODS__TtC12IMAP2Helpers18CertUITrustManager(IMAP2Helpers)
- __OBJC_$_PROP_LIST_MFAccountAliasDiagnostics
- __OBJC_CLASS_PROTOCOLS_$_MFAccountAliasDiagnostics
- __OBJC_CLASS_RO_$_MFAccountAliasDiagnostics
- __OBJC_METACLASS_RO_$_MFAccountAliasDiagnostics
- ___32+[MFAccountAliasDiagnostics log]_block_invoke
- ___58+[MFAccountAliasDiagnostics _promptToFileRadarForAccount:]_block_invoke
- ___62+[MFAccountAliasDiagnostics notifyOfMissingAliasesForAccount:]_block_invoke
- ___block_descriptor_64_ea8_32s40s48s_e27_v16?0"MSRadarURLBuilder"8l
- __markAccountIdentifierAsNotified:.lock
- __markAccountIdentifierAsNotified:.notifiedAccountIdentifiers
- _associated conformance 4Mail35MFGraphSyncPagedMessageDeltaRequest33_358C2A1F6007F72385C5D1B579DB72AELLV05GraphC00qC11RequestableAA05graphC17ResponseDataModelAeFP_SE
- _associated conformance 4Mail35MFGraphSyncPagedMessageDeltaRequest33_358C2A1F6007F72385C5D1B579DB72AELLV05GraphC00qC11RequestableAA05graphC17ResponseDataModelAeFP_Se
- _class_getClassMethod
- _class_getInstanceMethod
- _method_getImplementation
- _objc_msgSend$_aliasDetailsForAccount:
- _objc_msgSend$_descriptionForAccount:
- _objc_msgSend$_descriptionForAliasValue:
- _objc_msgSend$_isEnabled
- _objc_msgSend$_markAccountIdentifierAsNotified:
- _objc_msgSend$_promptToFileRadarForAccount:
- _objc_msgSend$initWithTitle:message:radarURL:
- _objc_msgSend$localTimeZone
- _objc_msgSend$notifyOfMissingAliasesForAccount:
- _objc_msgSend$promptToFile
- _objc_msgSend$radarURLWithBuilder:
- _objc_msgSend$setAppendSysdiagnoseHowTo:
- _objc_msgSend$setEWSToGraphMigrationComplete
- _objc_msgSend$setKeywords:
- _objc_msgSend$stringFromDate:timeZone:formatOptions:
- _symbolic $s9GraphSync0aB11RequestableP
- _symbolic _____ 12IMAP2Helpers12CertUIPromptC
- _symbolic _____ 12IMAP2Helpers18CertUITrustManagerC
- _symbolic _____ 16IMAP2Persistence16CertificateTrustO0A10ConnectionE12PromptResultO
- _symbolic _____ 4Mail35MFGraphSyncPagedMessageDeltaRequest33_358C2A1F6007F72385C5D1B579DB72AELLV
- _symbolic _____ 9GraphSync0aB19MessageDeltaRequestV
- _symbolic _____ 9GraphSync0aB25MessageCollectionResponseV
- _symbolic _____Iegy_ 16IMAP2Persistence16CertificateTrustO0A10ConnectionE12PromptResultO
- _symbolic _____IeyBy_ s6UInt32V
- _symbolic ______p 15IMAP2Connection23CertificateTrustAccountP
- _symbolic _____yXl___________SgSSSgAEtXC So18SecTrustResultTypeV 10ObjectiveC8SelectorV So0aB3Refa
- _symbolic yXl
- _symbolic yyXl______SDy_____ypGSgy_____ctXC 10ObjectiveC8SelectorV s11AnyHashableV s6UInt32V
- _symbolic yyXl______SSSgtXC 10ObjectiveC8SelectorV
- _symbolic yyXl___________SgSSSgADtXC 10ObjectiveC8SelectorV So11SecTrustRefa
- _symbolic yyXl___________SgtXC 10ObjectiveC8SelectorV So11SecTrustRefa
- _type_layout_string 16IMAP2Persistence16CertificateTrustO0A10ConnectionE29DefaultVerifierImplementationV
- _type_layout_string So19MFMailboxAttributesV
CStrings:
+ "$deltatoken="
+ "%@ FROM %@ WHERE mailbox = (SELECT ROWID FROM mailboxes WHERE url = %@) AND messages.remote_id GLOB '%@*'"
+ "%{public}@ Removing %lu migrated messages the server no longer has"
+ "-[MFExchangeAccount test_graphMigrationProgress]"
+ "-[MFLibrary messagesWithRemoteIDPrefix:inMailbox:options:]"
+ "11"
+ ": Broken strerror, unknown error: "
+ "@16@?0@\"NSDictionary\"8"
+ "Could not confirm whether the message to copy is gone, error: %@"
+ "EWSGraphRestartButton"
+ "EWSGraphRestartMessage"
+ "EWSGraphRestartNotNow"
+ "EWSGraphRestartTitle"
+ "Error migrating offline cache for %@: %@"
+ "ExchangeSyncMac"
+ "Finished Graph migration progress for account %{public}@"
+ "NIOIMAPCore2/SocketAddresses.swift"
+ "Not adding %lu messages that a queued move is taking out of the mailbox"
+ "Showing Graph migration progress for account %{public}@"
+ "The copy loop was throttled, stopping the remaining items: %@"
+ "The message to copy is no longer on the server, so the move discards it instead of restoring it"
+ "[%{public}@] Graph migration complete for account"
+ "[%{public}@] Graph migration converted local IDs; waiting for the first full Graph sync"
+ "[%{public}@] Graph migration resync pending: folder hierarchy not caught up"
+ "[%{public}@] Graph migration resync pending: pendingFolders=%lu"
+ "com.apple.mail.MFExchangeAccount.graphMigrationProgress"
+ "finding messages for remote ID prefix"
+ "folder ID for folder delete is invalid after mapping to Graph"
+ "graphMigration"
+ "inet_ntop(addressFamily:addressBytes:addressDescription:addressDescriptionLength:)"
+ "inet_pton(addressFamily:addressDescription:address:)"
+ "mapped deleteItem ID is nil"
+ "mapping block is nil for createEventReply ID"
+ "mapping block is nil for createFolder folder ID"
+ "mapping block is nil for createItem ID"
+ "mapping block is nil for createMessage ID"
+ "mapping block is nil for deleteFolder folder ID"
+ "mapping block is nil for deleteItem ID"
+ "mapping block is nil for moveFolder folder ID"
+ "migrated:"
- "!1"
- "Account alias value (ignored for Apple Accounts): %@\n"
- "Account identifier: %@\n"
- "Account type: %@\n"
- "Apple Account %{public}@ has no email aliases"
- "Apple Account Has No Email Aliases"
- "Apple Account has no email aliases"
- "EWSGraphRelaunchMessage"
- "EWSGraphRelaunchRestartLater"
- "EWSGraphRelaunchRestartNow"
- "EWSGraphRelaunchTitle"
- "GraphSyncMailMigration"
- "Mail found no email aliases for %@. Please file a Radar. Internal Only."
- "Mail found no email aliases for an Apple Account.\n\nAccount: %@\n%@\nDetected at: %@"
- "Parent account identifier: %@\n"
- "Parent account type: %@\n"
- "Parent alias value: %@\n"
- "Parent mail dataclass property keys: %@\n"
- "Prefer"
- "The GraphSyncMessageCopyRequest was throttled, stopping the remaining items: %@"
- "array with %lu entries"
- "email aliases, accountsd, iCloud"
- "kCertUIServiceTypeIMAP"
- "odata.maxpagesize="
- "unexpected %@"
- "v16@?0@\"MSRadarURLBuilder\"8"
```
