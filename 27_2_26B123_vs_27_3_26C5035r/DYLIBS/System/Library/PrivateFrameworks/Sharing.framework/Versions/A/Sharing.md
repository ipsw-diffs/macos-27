## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Versions/A/Sharing`

```diff

-2131.21.31.1.3
-  __TEXT.__text: 0x337958
-  __TEXT.__objc_methlist: 0x12ebc
-  __TEXT.__cstring: 0x2cf48
-  __TEXT.__const: 0x21f8c
-  __TEXT.__gcc_except_tab: 0x35b0
-  __TEXT.__oslogstring: 0xcff3
+2131.30.43.1.1
+  __TEXT.__text: 0x338b74
+  __TEXT.__objc_methlist: 0x12efc
+  __TEXT.__cstring: 0x2d068
+  __TEXT.__const: 0x21f7c
+  __TEXT.__gcc_except_tab: 0x35c0
+  __TEXT.__oslogstring: 0xd2e3
   __TEXT.__dlopen_cstrs: 0x5f2
   __TEXT.__ustring: 0x18
-  __TEXT.__swift5_typeref: 0x8a0f
+  __TEXT.__swift5_typeref: 0x8a1f
   __TEXT.__constg_swiftt: 0x726c
-  __TEXT.__swift5_reflstr: 0x420a
-  __TEXT.__swift5_fieldmd: 0x7068
+  __TEXT.__swift5_reflstr: 0x41ea
+  __TEXT.__swift5_fieldmd: 0x7044
   __TEXT.__swift5_builtin: 0x1e0
   __TEXT.__swift5_assocty: 0x1130
   __TEXT.__swift5_capture: 0x29e4

   __TEXT.__swift_as_ret: 0x40c
   __TEXT.__swift_as_cont: 0xa88
   __TEXT.__swift5_mpenum: 0xb8
-  __TEXT.__unwind_info: 0x11958
+  __TEXT.__unwind_info: 0x119b8
   __TEXT.__eh_frame: 0xeb8c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x360
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x87b0
+  __DATA_CONST.__objc_selrefs: 0x8830
   __DATA_CONST.__objc_protorefs: 0x1d8
   __DATA_CONST.__objc_classrefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x508
   __DATA_CONST.__objc_arraydata: 0x2f0
   __DATA_CONST.__got: 0x12b8
-  __AUTH_CONST.__const: 0x1c4e8
-  __AUTH_CONST.__cfstring: 0x11900
-  __AUTH_CONST.__objc_const: 0x35a38
+  __AUTH_CONST.__const: 0x1c698
+  __AUTH_CONST.__cfstring: 0x11b00
+  __AUTH_CONST.__objc_const: 0x35a10
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x498
   __AUTH_CONST.__objc_dictobj: 0x398
   __AUTH_CONST.__objc_arrayobj: 0xa8
-  __AUTH_CONST.__auth_got: 0x2970
+  __AUTH_CONST.__auth_got: 0x2978
   __AUTH.__objc_data: 0x2ba8
   __AUTH.__data: 0x3098
-  __DATA.__objc_ivar: 0x1ff4
+  __DATA.__objc_ivar: 0x1ff0
   __DATA.__data: 0xba20
   __DATA.__bss: 0x39ad0
   __DATA.__common: 0x160

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 21937
-  Symbols:   20660
-  CStrings:  7490
+  Functions: 21958
+  Symbols:   20697
+  CStrings:  7520
 
Symbols:
+ +[SFCollaborationUtilities _applyScreeningDisclosureFooterToShareOptions:]
+ +[SFCollaborationUtilities _resolveShareOptionsForSWCollaborationShareOptions:itemProvider:completionHandler:]
+ +[SFCollaborationUtilities addParticipantsAllowedForURL:share:auditToken:completionHandler:]
+ +[SFCollaborationUtilities applyScreeningDisclosureToShareOptions:forFileURL:completionHandler:]
+ +[SFCollaborationUtilities requiresScreeningDisclosureForShare:inContainerID:]
+ -[SFCollaborationCloudSharingRequest auditToken]
+ -[SFCollaborationCloudSharingRequest setAuditToken:]
+ -[SFCollaborationPerformer _requiresScreeningDisclosureForShare:]
+ -[SFCollaborationPerformer _stopForHandOff]
+ -[SFCompanionManager currentRendezvousName]
+ GCC_except_table109
+ GCC_except_table111
+ GCC_except_table113
+ GCC_except_table140
+ GCC_except_table142
+ GCC_except_table152
+ GCC_except_table154
+ GCC_except_table159
+ GCC_except_table161
+ GCC_except_table210
+ GCC_except_table211
+ GCC_except_table218
+ GCC_except_table219
+ GCC_except_table70
+ GCC_except_table75
+ GCC_except_table79
+ GCC_except_table80
+ GCC_except_table82
+ _NSSelectorFromString
+ _OBJC_IVAR_$_SFCollaborationCloudSharingRequest._auditToken
+ _SFDeviceIsIPhoneDuoDevice
+ ___110+[SFCollaborationUtilities _resolveShareOptionsForSWCollaborationShareOptions:itemProvider:completionHandler:]_block_invoke
+ ___110+[SFCollaborationUtilities _resolveShareOptionsForSWCollaborationShareOptions:itemProvider:completionHandler:]_block_invoke_2
+ ___43-[SFCompanionManager currentRendezvousName]_block_invoke
+ ___52-[_SFFPShareCollaborationItem _loadMetadataIfNeeded]_block_invoke_4
+ ___74+[SFCollaborationUtilities _applyScreeningDisclosureFooterToShareOptions:]_block_invoke
+ ___92+[SFCollaborationUtilities addParticipantsAllowedForURL:share:auditToken:completionHandler:]_block_invoke
+ ___96+[SFCollaborationUtilities applyScreeningDisclosureToShareOptions:forFileURL:completionHandler:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e30_v16?0"CKContainerSetupInfo"8l
+ ___block_descriptor_40_e8_32bs_e83_v40?0"<SFCompanionServiceManagerProtocol>"8"NSString"16"NSString"24"NSError"32l
+ ___block_descriptor_40_e8_32s_e83_v40?0"<SFCompanionServiceManagerProtocol>"8"NSString"16"NSString"24"NSError"32l
+ ___block_descriptor_48_e8_32s40r_e18_v16?0"NSString"8l
+ ___block_descriptor_48_e8_32s40s_e45_v24?0"SFCollaborationMetadata"8"NSError"16l
+ ___block_descriptor_56_e8_32s40bs_e29_v24?0"CKShare"8"NSError"16l
+ ___block_descriptor_56_e8_32s40bs_e42_v24?0"CKShare"8"CKContainerSetupInfo"16l
+ ___block_descriptor_64_e8_32s40s48bs_e5_v8?0l
+ ___block_descriptor_65_e8_32s40s48s_e20_v20?0B8"NSError"12l
+ ___block_descriptor_65_e8_32s40s48s_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48bs_e45_v24?0"<NSItemProviderReading>"8"NSError"16l
+ _getCKContainerIDClass
+ _keypath_set.118Tm
+ _objc_msgSend$_applyScreeningDisclosureFooterToShareOptions:
+ _objc_msgSend$_requiresScreeningDisclosureForShare:
+ _objc_msgSend$_resolveShareOptionsForSWCollaborationShareOptions:itemProvider:completionHandler:
+ _objc_msgSend$_stopForHandOff
+ _objc_msgSend$applyScreeningDisclosureToShareOptions:forFileURL:completionHandler:
+ _objc_msgSend$containerIdentifier
+ _objc_msgSend$currentRendezvousName
+ _objc_msgSend$hasBeenScreened
+ _objc_msgSend$realToken
+ _objc_msgSend$recordChangeTag
+ _objc_msgSend$recordID
+ _objc_msgSend$rendezvousNameWithReply:
+ _objc_msgSend$requiresScreeningDisclosureForShare:inContainerID:
+ _objc_msgSend$serverPublicPermission
+ _objc_msgSend$setFooter:
+ _objc_msgSend$showRequestAccessAlertForActivityType:shareSupportsRequestAccess:optionsIncludeAccessRequestsOption:requiresScreeningDisclosure:completionHandler:
+ _objc_msgSend$supportsShareScreening
+ _symbolic _____ySSG s11_SetStorageC
- +[SFCollaborationUtilities addParticipantsAllowedForURL:share:completionHandler:]
- +[SFCompanionService serviceFromDictionary:]
- -[SFCompanionManager deviceName]
- -[SFCompanionManager setDeviceName:]
- -[SFCompanionService deviceName]
- -[SFCompanionService setDeviceName:]
- GCC_except_table100
- GCC_except_table127
- GCC_except_table128
- GCC_except_table129
- GCC_except_table135
- GCC_except_table139
- GCC_except_table158
- GCC_except_table160
- GCC_except_table194
- GCC_except_table199
- GCC_except_table200
- GCC_except_table207
- GCC_except_table208
- GCC_except_table96
- GCC_except_table98
- _OBJC_IVAR_$_SFCompanionManager._deviceName
- _OBJC_IVAR_$_SFCompanionService._deviceName
- ___81+[SFCollaborationUtilities addParticipantsAllowedForURL:share:completionHandler:]_block_invoke
- ___block_descriptor_40_e8_32bs_e96_v48?0"<SFCompanionServiceManagerProtocol>"8"NSString"16"NSString"24"NSString"32"NSError"40l
- ___block_descriptor_40_e8_32s_e45_v24?0"SFCollaborationMetadata"8"NSError"16l
- ___block_descriptor_40_e8_32s_e96_v48?0"<SFCompanionServiceManagerProtocol>"8"NSString"16"NSString"24"NSString"32"NSError"40l
- ___block_descriptor_56_e8_32s40bs_e45_v24?0"<NSItemProviderReading>"8"NSError"16l
- _kSFCompanionServiceDeviceNameKey
- _keypath_set.117Tm
- _objc_msgSend$setDeviceName:
- _objc_msgSend$showRequestAccessAlertForActivityType:shareSupportsRequestAccess:optionsIncludeAccessRequestsOption:completionHandler:
CStrings:
+ "Cannot create sharing URL because calling process %@ has no access to file %@"
+ "Cannot request sharing URL because calling process %@ has no access to file %@"
+ "Cannot request whether add participants is allowed because calling process %@ has no access to file %@"
+ "CloudKit"
+ "Collaboration: error fetching existing share for screening disclosure, error:%@"
+ "ERROR_MESSAGE_FILE_NO_ACCESS"
+ "Error retrieving proxy object. Returned values (proxy = %@, deviceID = %@, deviceIP = %@, error = %@)"
+ "J510"
+ "K114"
+ "K116"
+ "LiveActivitiesQFA"
+ "Mac17,10"
+ "Mac17,11"
+ "Mac17,12"
+ "Mac17,13"
+ "Mac18,1"
+ "Mac18,2"
+ "Mac18,3"
+ "Mac18,4"
+ "MenuBar"
+ "No manager proxy when asking for rendezvous name"
+ "ProximityServiceThirdPartyHomeSetup"
+ "SFCompanionService (serviceType = %@, deviceID = %@, managerID = %@, identifier = %@)"
+ "SHARE_OPTIONS_ANYONE_WITH_LINK_FOOTER"
+ "SHARE_OPTIONS_ANYONE_WITH_LINK_FOOTER_LEARN_MORE"
+ "Screening disclosure %{public}s for share %@ (isNewShare: %d, hasBeenScreened: %d)"
+ "Screening disclosure not required for share %@: container %{public}@ does not support screening"
+ "Screening disclosure not required for share %@: sharing compliance is disabled"
+ "Stop Collaboration creation for collaboration item %@ to hand off to Manage Share"
+ "Timed out asking for rendezvous name"
+ "footerLinkText"
+ "footerLinkURL"
+ "https://support.apple.com/149168?cid=mc-ols-icloud-article_149168-macos-62028290"
+ "iCloudSharingCompliance"
+ "iPad19,1"
+ "iPad19,2"
+ "iPhone19,4"
+ "not required"
+ "required"
+ "setFooterLinkText:"
+ "setFooterLinkURL:"
+ "v40@?0@\"<SFCompanionServiceManagerProtocol>\"8@\"NSString\"16@\"NSString\"24@\"NSError\"32"
- " - receiverTLSCertDigest "
- " - senderTLSCertDigest "
- "DeviceID"
- "Error retrieving proxy object. Returned values (proxy = %@, deviceName = %@, deviceID = %@, deviceIP = %@, error = %@)"
- "IPAddress"
- "ManagerID"
- "SFCompanionService (serviceType = %@, deviceName = %@, deviceID = %@, managerID = %@, identifier = %@)"
- "ServiceIdentifier"
- "device_name"
- "receiverTLSCertDigest"
- "senderTLSCertDigest"
- "v48@?0@\"<SFCompanionServiceManagerProtocol>\"8@\"NSString\"16@\"NSString\"24@\"NSString\"32@\"NSError\"40"
```
