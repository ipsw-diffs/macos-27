## TelephonyUtilities

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/Versions/A/TelephonyUtilities`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_reflstr`

```diff

-1626.200.91.1.1
-  __TEXT.__text: 0x1b9014
-  __TEXT.__objc_methlist: 0x1bb00
-  __TEXT.__cstring: 0x12a36
-  __TEXT.__const: 0x4bac
-  __TEXT.__oslogstring: 0x13a1a
-  __TEXT.__gcc_except_tab: 0x141c
+1626.300.42.0.0
+  __TEXT.__text: 0x1b97e0
+  __TEXT.__objc_methlist: 0x1bca8
+  __TEXT.__cstring: 0x12c96
+  __TEXT.__const: 0x4b8c
+  __TEXT.__oslogstring: 0x13be4
+  __TEXT.__gcc_except_tab: 0x14b4
   __TEXT.__ustring: 0xde
   __TEXT.__dlopen_cstrs: 0x4fb
-  __TEXT.__constg_swiftt: 0xec4
-  __TEXT.__swift5_typeref: 0x144b
+  __TEXT.__constg_swiftt: 0xebc
+  __TEXT.__swift5_typeref: 0x1427
   __TEXT.__swift5_builtin: 0xc8
   __TEXT.__swift5_reflstr: 0xc89
-  __TEXT.__swift5_fieldmd: 0x1320
+  __TEXT.__swift5_fieldmd: 0x132c
   __TEXT.__swift5_assocty: 0xf0
   __TEXT.__swift5_proto: 0x3dc
   __TEXT.__swift5_types: 0x14c
-  __TEXT.__swift5_capture: 0x38c
-  __TEXT.__swift_as_entry: 0xec
-  __TEXT.__swift_as_ret: 0x104
-  __TEXT.__swift_as_cont: 0x1e4
+  __TEXT.__swift5_capture: 0x2fc
+  __TEXT.__swift_as_entry: 0xd8
+  __TEXT.__swift_as_ret: 0xf4
+  __TEXT.__swift_as_cont: 0x1cc
   __TEXT.__swift5_protos: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x9178
-  __TEXT.__eh_frame: 0x31d8
+  __TEXT.__unwind_info: 0x91d8
+  __TEXT.__eh_frame: 0x2f90
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1950
-  __DATA_CONST.__objc_classlist: 0x8b8
+  __DATA_CONST.__const: 0x1990
+  __DATA_CONST.__objc_classlist: 0x8d0
   __DATA_CONST.__objc_catlist: 0xc0
-  __DATA_CONST.__objc_protolist: 0x420
+  __DATA_CONST.__objc_protolist: 0x428
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb6f8
+  __DATA_CONST.__objc_selrefs: 0xb800
   __DATA_CONST.__objc_protorefs: 0x110
-  __DATA_CONST.__objc_superrefs: 0x700
-  __DATA_CONST.__objc_arraydata: 0xac0
-  __DATA_CONST.__got: 0x1040
-  __AUTH_CONST.__const: 0x6888
-  __AUTH_CONST.__cfstring: 0x12660
-  __AUTH_CONST.__objc_const: 0x2b648
+  __DATA_CONST.__objc_superrefs: 0x708
+  __DATA_CONST.__objc_arraydata: 0xaf8
+  __DATA_CONST.__got: 0x1060
+  __AUTH_CONST.__const: 0x68f8
+  __AUTH_CONST.__cfstring: 0x12860
+  __AUTH_CONST.__objc_const: 0x2b9a0
   __AUTH_CONST.__objc_intobj: 0x318
   __AUTH_CONST.__objc_doubleobj: 0x40
-  __AUTH_CONST.__objc_arrayobj: 0x2e8
-  __AUTH_CONST.__auth_got: 0x1370
-  __AUTH.__objc_data: 0x2510
-  __AUTH.__data: 0xd18
-  __DATA.__objc_ivar: 0x1948
-  __DATA.__data: 0x3f40
-  __DATA.__bss: 0x7a60
+  __AUTH_CONST.__objc_arrayobj: 0x318
+  __AUTH_CONST.__auth_got: 0x1378
+  __AUTH.__objc_data: 0x2600
+  __AUTH.__data: 0xd08
+  __DATA.__objc_ivar: 0x1958
+  __DATA.__data: 0x3fc0
+  __DATA.__bss: 0x7ab0
   __DATA.__common: 0xb0
   __DATA_DIRTY.__objc_data: 0x3488
   __DATA_DIRTY.__data: 0x198
-  __DATA_DIRTY.__bss: 0x7c0
+  __DATA_DIRTY.__bss: 0x7d0
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/CallKit.framework/Versions/A/CallKit
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11856
-  Symbols:   20272
-  CStrings:  4454
+  Functions: 11886
+  Symbols:   20389
+  CStrings:  4490
 
Symbols:
+ +[CSDMessagingHandle(Additions) handleForRelayWithTUHandle:]
+ +[TUFeatureFlags isLiveActivitiesQFAEnabled]
+ +[TUPlatformCapabilities isDualDisplayDevice]
+ +[TUWalletBusinessCallerIDProvider sharedInstance]
+ -[TUAudioSystemController _pickedRouteIdentifier]
+ -[TUAudioSystemController _updateCachedDisabledRoutes:]
+ -[TUAudioSystemController currentlyActiveCategory]
+ -[TUBusinessServicesMetadataDataProvider fetchCachedBusinessServiceInformationForHandleValue:completion:]
+ -[TUCall isPrimaryVideoPaused]
+ -[TUCall setPrimaryVideoPaused:]
+ -[TUCallServicesInterface setPrimaryVideoPaused:forCallWithUniqueProxyIdentifier:]
+ -[TUDynamicCallDisplayContext _applyBusinessCallerItem:forCall:fromCache:]
+ -[TUDynamicCallDisplayContext updateDisplayContextWithCachedBusinessChatServiceInfoUsingCall:]
+ -[TUDynamicCallDisplayContext updateDisplayContextWithWalletBusinessInfoUsingCall:]
+ -[TUDynamicCallDisplayContext walletBusinessCallerIDProvider]
+ -[TUFeatureFlags globalReportUnknownEnabled]
+ -[TUProxyCall isPrimaryVideoPaused]
+ -[TUProxyCall setPrimaryVideoPaused:]
+ -[TURoute localizedDisabledReason]
+ -[TUVideoDeviceController setPreviewPresentationOrientation:]
+ -[TUVideoDeviceControllerProvider appendFriendModeCamerasToDevices:]
+ -[TUVideoDeviceControllerProvider setPreviewPresentationOrientation:]
+ -[TUWalletBusinessCallerIDProvider .cxx_destruct]
+ -[TUWalletBusinessCallerIDProvider digitsOnlyFromPhoneNumber:]
+ -[TUWalletBusinessCallerIDProvider escapedQueryStringLiteral:]
+ -[TUWalletBusinessCallerIDProvider fetchBusinessNameForNormalizedPhoneNumber:completion:]
+ -[TUWalletBusinessCallerIDProvider initWithSpotlightQuerying:]
+ -[TUWalletBusinessCallerIDProvider init]
+ -[TUWalletBusinessCallerIDProvider queryStringForDigitsOnlyPhoneNumber:]
+ -[TUWalletBusinessCallerIDProvider spotlightQuerying]
+ -[TUWalletCSSearchQueryRunner runQueryString:fetchAttributes:completion:]
+ GCC_except_table169
+ GCC_except_table179
+ GCC_except_table185
+ GCC_except_table191
+ GCC_except_table197
+ GCC_except_table200
+ GCC_except_table203
+ GCC_except_table224
+ _MGCopyAnswer
+ _OBJC_CLASS_$_CSSearchQuery
+ _OBJC_CLASS_$_CSSearchQueryContext
+ _OBJC_CLASS_$_TUPlatformCapabilities
+ _OBJC_CLASS_$_TUWalletBusinessCallerIDProvider
+ _OBJC_CLASS_$_TUWalletCSSearchQueryRunner
+ _OBJC_IVAR_$_TUAudioSystemController._currentDisabledRoutes
+ _OBJC_IVAR_$_TUAudioSystemController._lastPickedRouteIdentifier
+ _OBJC_IVAR_$_TUProxyCall._primaryVideoPaused
+ _OBJC_IVAR_$_TUWalletBusinessCallerIDProvider._spotlightQuerying
+ _OBJC_METACLASS_$_TUPlatformCapabilities
+ _OBJC_METACLASS_$_TUWalletBusinessCallerIDProvider
+ _OBJC_METACLASS_$_TUWalletCSSearchQueryRunner
+ _TUCallAssistantThirdPartyAvailable
+ _TUCallPrimaryVideoPausedForVideoCaptureMode
+ _TUSimulatedModeEnabledDidChangeNotification
+ __OBJC_$_CLASS_METHODS_TUPlatformCapabilities
+ __OBJC_$_CLASS_METHODS_TUWalletBusinessCallerIDProvider
+ __OBJC_$_CLASS_PROP_LIST_TUPlatformCapabilities
+ __OBJC_$_CLASS_PROP_LIST_TUWalletBusinessCallerIDProvider
+ __OBJC_$_INSTANCE_METHODS_TUWalletBusinessCallerIDProvider
+ __OBJC_$_INSTANCE_METHODS_TUWalletCSSearchQueryRunner
+ __OBJC_$_INSTANCE_VARIABLES_TUWalletBusinessCallerIDProvider
+ __OBJC_$_PROP_LIST_TUWalletBusinessCallerIDProvider
+ __OBJC_$_PROP_LIST_TUWalletCSSearchQueryRunner
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_TUWalletSpotlightQuerying
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TUWalletSpotlightQuerying
+ __OBJC_$_PROTOCOL_REFS_TUWalletSpotlightQuerying
+ __OBJC_CLASS_PROTOCOLS_$_TUWalletCSSearchQueryRunner
+ __OBJC_CLASS_RO_$_TUPlatformCapabilities
+ __OBJC_CLASS_RO_$_TUWalletBusinessCallerIDProvider
+ __OBJC_CLASS_RO_$_TUWalletCSSearchQueryRunner
+ __OBJC_LABEL_PROTOCOL_$_TUWalletSpotlightQuerying
+ __OBJC_METACLASS_RO_$_TUPlatformCapabilities
+ __OBJC_METACLASS_RO_$_TUWalletBusinessCallerIDProvider
+ __OBJC_METACLASS_RO_$_TUWalletCSSearchQueryRunner
+ __OBJC_PROTOCOL_$_TUWalletSpotlightQuerying
+ ___105-[TUBusinessServicesMetadataDataProvider fetchCachedBusinessServiceInformationForHandleValue:completion:]_block_invoke
+ ___37-[TUProxyCall setPrimaryVideoPaused:]_block_invoke
+ ___37-[TUProxyCall setPrimaryVideoPaused:]_block_invoke_2
+ ___44+[TUFeatureFlags isLiveActivitiesQFAEnabled]_block_invoke
+ ___45+[TUPlatformCapabilities isDualDisplayDevice]_block_invoke
+ ___50+[TUWalletBusinessCallerIDProvider sharedInstance]_block_invoke
+ ___68-[TUVideoDeviceControllerProvider appendFriendModeCamerasToDevices:]_block_invoke
+ ___68-[TUVideoDeviceControllerProvider appendFriendModeCamerasToDevices:]_block_invoke_2
+ ___68-[TUVideoDeviceControllerProvider appendFriendModeCamerasToDevices:]_block_invoke_3
+ ___70-[TUAudioSystemController _handlePickableRoutesDidChangeNotification:]_block_invoke_2
+ ___73-[TUWalletCSSearchQueryRunner runQueryString:fetchAttributes:completion:]_block_invoke
+ ___74-[TUDynamicCallDisplayContext _applyBusinessCallerItem:forCall:fromCache:]_block_invoke
+ ___83-[TUDynamicCallDisplayContext updateDisplayContextWithWalletBusinessInfoUsingCall:]_block_invoke
+ ___89-[TUWalletBusinessCallerIDProvider fetchBusinessNameForNormalizedPhoneNumber:completion:]_block_invoke
+ ___94-[TUDynamicCallDisplayContext updateDisplayContextWithCachedBusinessChatServiceInfoUsingCall:]_block_invoke
+ ___block_descriptor_32_e32_B32?0"AVCaptureDevice"8Q16^B24l
+ ___block_descriptor_35_e5_v8?0l
+ ___block_descriptor_48_e8_32bs40r_e17_v16?0"NSError"8l
+ ___block_descriptor_48_e8_32s40bs_e44_v24?0"<TUCachedBusinessItem>"8"NSError"16l
+ ___block_descriptor_49_e8_32s_e5_v8?0l
+ ___block_descriptor_56_e8_32s40s48w_e18_v16?0"NSString"8l
+ _appendFriendModeCamerasToDevices:._AVCaptureDeviceTypeBuiltInBostonUltraWideCamera
+ _appendFriendModeCamerasToDevices:._AVCaptureDeviceTypeBuiltInRenoUltraWideCamera
+ _appendFriendModeCamerasToDevices:._AVMediaTypeVideo
+ _appendFriendModeCamerasToDevices:._pred__AVCaptureDeviceTypeBuiltInBostonUltraWideCamera
+ _appendFriendModeCamerasToDevices:._pred__AVCaptureDeviceTypeBuiltInRenoUltraWideCamera
+ _appendFriendModeCamerasToDevices:._pred__AVMediaTypeVideo
+ _isDualDisplayDevice.onceToken
+ _isLiveActivitiesQFAEnabled.onceToken
+ _isLiveActivitiesQFAEnabled.result
+ _objc_msgSend$_applyBusinessCallerItem:forCall:fromCache:
+ _objc_msgSend$_pickedRouteIdentifier
+ _objc_msgSend$_updateCachedDisabledRoutes:
+ _objc_msgSend$attributeSet
+ _objc_msgSend$cachedBusinessItemWithPhoneNumber:completion:
+ _objc_msgSend$creator
+ _objc_msgSend$decimalDigitCharacterSet
+ _objc_msgSend$digitsOnlyFromPhoneNumber:
+ _objc_msgSend$disabledRoutes
+ _objc_msgSend$escapedQueryStringLiteral:
+ _objc_msgSend$fetchBusinessNameForNormalizedPhoneNumber:completion:
+ _objc_msgSend$fetchCachedBusinessServiceInformationForHandleValue:completion:
+ _objc_msgSend$initWithQueryString:queryContext:
+ _objc_msgSend$initWithSpotlightQuerying:
+ _objc_msgSend$invertedSet
+ _objc_msgSend$isDualDisplayDevice
+ _objc_msgSend$isLiveActivitiesQFAEnabled
+ _objc_msgSend$isPrimaryVideoPaused
+ _objc_msgSend$primarySession
+ _objc_msgSend$queryAVCaptureDeviceWithType:mediaType:position:
+ _objc_msgSend$queryStringForDigitsOnlyPhoneNumber:
+ _objc_msgSend$runQueryString:fetchAttributes:completion:
+ _objc_msgSend$setCompletionHandler:
+ _objc_msgSend$setFetchAttributes:
+ _objc_msgSend$setFoundItemsHandler:
+ _objc_msgSend$setPreviewPresentationOrientation:
+ _objc_msgSend$setPrimaryVideoPaused:forCallWithUniqueProxyIdentifier:
+ _objc_msgSend$setVideoPaused:
+ _objc_msgSend$spotlightQuerying
+ _objc_msgSend$start
+ _objc_msgSend$updateDisplayContextWithCachedBusinessChatServiceInfoUsingCall:
+ _objc_msgSend$updateDisplayContextWithWalletBusinessInfoUsingCall:
+ _objc_msgSend$walletBusinessCallerIDProvider
+ _sharedInstance.sProvider
- -[TUConfigurationProvider isSmartVoicemailActionsAvailable]
- -[TUConfigurationProvider isSmartVoicemailActionsEnabled]
- -[TUConfigurationProvider setSmartVoicemailActionsEnabled:]
- -[TUUserConfiguration isSmartVoicemailActionsEnabled]
- -[TUUserConfiguration setSmartVoicemailActionsEnabled:]
- GCC_except_table168
- GCC_except_table178
- GCC_except_table181
- GCC_except_table184
- GCC_except_table187
- GCC_except_table190
- GCC_except_table196
- GCC_except_table199
- GCC_except_table202
- GCC_except_table223
- GCC_except_table73
- _TUSmartVoicemailActionsEnabledKey
- _objc_msgSend$isSmartVoicemailActionsAvailable
- _objc_msgSend$isSmartVoicemailActionsEnabled
- _objc_msgSend$setSmartVoicemailActionsEnabled:
- _symbolic SbIeAgHr_
- _symbolic So8TUHandleC
- _symbolic _____ySb_G ScG8IteratorV
CStrings:
+ "(kMDItemContentType == \"%@\") && (%@ == 1) && (%@ == \"%@\")"
+ "AVCaptureDeviceTypeBuiltInBostonUltraWideCamera"
+ "AVCaptureDeviceTypeBuiltInRenoUltraWideCamera"
+ "AVLiveActivity"
+ "Already have business information for call: %@, ignoring lower-priority cached result."
+ "Asked to set primaryVideoPaused from %d to %d for %@. Posting necessary notifications and updating daemon"
+ "B32@?0@\"AVCaptureDevice\"8Q16^B24"
+ "ControlCenter"
+ "Disabled routes changed from %@ to %@"
+ "Discarding _cachedInputDevices because %@ is disconnected"
+ "Got cached businessItem: %@ for destinationID: %@"
+ "LiveActivitiesQFA"
+ "Mac17,10"
+ "Mac17,11"
+ "Mac17,12"
+ "Mac17,13"
+ "MacQFA"
+ "MenuBar"
+ "No Wallet business information found for '%@'"
+ "No primary session available for preview presentation orientation"
+ "Passbook_isPaymentPass"
+ "Passbook_normalizedPhoneNumbers"
+ "Posting TUAudioSystemAudioPickableRoutesChanged (didClearPickableRoutes: %d, didChangeDisabledRoutes: %d, didChangePickedRoute: %d)"
+ "ProductType"
+ "Proxying setPrimaryVideoPaused=%d for %@"
+ "Querying business service cache for destinationID: %@"
+ "ROUTE_DISABLED_ONLY_AVAILABLE_ON_FRONT_DISPLAY"
+ "Setting preview presentation orientation: %d"
+ "Sign in required"
+ "Wallet business caller ID Spotlight query failed: %@"
+ "Wallet business caller ID Spotlight query string is invalid: %@"
+ "[TUInterpreterRequest] Sign in required for %s"
+ "\\"
+ "\\\""
+ "\\\\"
+ "com.apple.TelephonyUtilities.SimulatedModeEnabledDidChange"
+ "com.apple.pkpass"
+ "globalReportUnknown"
+ "kMDItemCreator"
+ "kMDItemDisplayName"
+ "setPreviewPresentationOrientation: not available on AVCPreviewCameraSession, requested orientation: %d"
+ "v16@?0@\"NSString\"8"
+ "v24@?0@\"<TUCachedBusinessItem>\"8@\"NSError\"16"
+ "\xf0\xd1"
+ "\xf0\xf0\xf0A"
- "%@ setSmartVoicemailActionsEnabled called %d"
- "Clearing cached current pickable routes and posting TUAudioSystemAudioPickableRoutesChanged"
- "FaceTimeServiceAvailabilityHelper: All services returned unavailable"
- "FaceTimeServiceAvailabilityHelper: Querying availability of FaceTime services for handle %@ with timeout: %s"
- "FaceTimeServiceAvailabilityHelper: Received callback indicating FaceTime is available"
- "FaceTimeServiceAvailabilityHelper: Timeout reached querying availability of FaceTime, returning false"
- "SmartVoicemailActionsEnabled"
- "\xf0\xb1"
- "\xf0\xf0\xf01"
```
