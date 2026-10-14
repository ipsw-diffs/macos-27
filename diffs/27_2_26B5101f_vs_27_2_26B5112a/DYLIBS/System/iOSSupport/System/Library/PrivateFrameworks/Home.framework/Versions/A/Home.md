## Home

> `/System/iOSSupport/System/Library/PrivateFrameworks/Home.framework/Versions/A/Home`

```diff

-1269.2.3.0.1
-  __TEXT.__text: 0x3876b4
-  __TEXT.__objc_methlist: 0x2bce4
-  __TEXT.__const: 0x5318
-  __TEXT.__swift5_typeref: 0x28a8
-  __TEXT.__oslogstring: 0x1bdd3
+1269.2.5.4.3
+  __TEXT.__text: 0x38ae3c
+  __TEXT.__objc_methlist: 0x2bf0c
+  __TEXT.__const: 0x5330
+  __TEXT.__swift5_typeref: 0x28ee
+  __TEXT.__oslogstring: 0x1c2a3
   __TEXT.__swift5_reflstr: 0xd63
   __TEXT.__swift5_assocty: 0x2e8
   __TEXT.__swift5_fieldmd: 0x10a8

   __TEXT.__swift5_protos: 0x40
   __TEXT.__swift5_proto: 0x23c
   __TEXT.__swift5_types: 0x17c
-  __TEXT.__cstring: 0x3443e
-  __TEXT.__swift5_capture: 0xf18
+  __TEXT.__cstring: 0x34951
+  __TEXT.__swift5_capture: 0xf5c
   __TEXT.__swift_as_entry: 0x21c
   __TEXT.__swift_as_ret: 0x1e4
   __TEXT.__swift_as_cont: 0x45c
   __TEXT.__swift5_mpenum: 0x10
   __TEXT.__gcc_except_tab: 0x4a8c
   __TEXT.__ustring: 0x72
-  __TEXT.__unwind_info: 0x113a8
+  __TEXT.__unwind_info: 0x11460
   __TEXT.__eh_frame: 0x67d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x10d98
-  __DATA_CONST.__objc_classlist: 0x1828
+  __DATA_CONST.__const: 0x10e10
+  __DATA_CONST.__objc_classlist: 0x1838
   __DATA_CONST.__objc_catlist: 0x418
-  __DATA_CONST.__objc_protolist: 0x8d0
+  __DATA_CONST.__objc_protolist: 0x8e8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x128a0
-  __DATA_CONST.__objc_protorefs: 0x3d0
-  __DATA_CONST.__objc_superrefs: 0x12e8
-  __DATA_CONST.__objc_arraydata: 0x3c8
-  __DATA_CONST.__got: 0x30d0
-  __AUTH_CONST.__const: 0xeb18
-  __AUTH_CONST.__cfstring: 0x26f20
-  __AUTH_CONST.__objc_const: 0x4b018
+  __DATA_CONST.__objc_selrefs: 0x12a20
+  __DATA_CONST.__objc_protorefs: 0x3e0
+  __DATA_CONST.__objc_superrefs: 0x12f0
+  __DATA_CONST.__objc_arraydata: 0x3e8
+  __DATA_CONST.__got: 0x3110
+  __AUTH_CONST.__const: 0xecc8
+  __AUTH_CONST.__cfstring: 0x272e0
+  __AUTH_CONST.__objc_const: 0x4b288
   __AUTH_CONST.__objc_intobj: 0x22e0
   __AUTH_CONST.__objc_arrayobj: 0x270
   __AUTH_CONST.__objc_doubleobj: 0x170
   __AUTH_CONST.__objc_floatobj: 0x50
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x20d8
-  __AUTH.__objc_data: 0x9fe8
+  __AUTH_CONST.__auth_got: 0x20e0
+  __AUTH.__objc_data: 0xa038
   __AUTH.__data: 0x1230
-  __DATA.__objc_ivar: 0x1554
-  __DATA.__data: 0x72b0
+  __DATA.__objc_ivar: 0x1558
+  __DATA.__data: 0x7390
   __DATA.__objc_stublist: 0x10
   __DATA.__bss: 0x37d0
   __DATA.__common: 0x120
   __DATA_DIRTY.__objc_ivar: 0xcb4
-  __DATA_DIRTY.__objc_data: 0x6700
+  __DATA_DIRTY.__objc_data: 0x6750
   __DATA_DIRTY.__data: 0xee8
-  __DATA_DIRTY.__bss: 0x1d70
+  __DATA_DIRTY.__bss: 0x1d80
   __DATA_DIRTY.__common: 0x60
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 20613
-  Symbols:   37437
-  CStrings:  8345
+  Functions: 20668
+  Symbols:   37562
+  CStrings:  8394
 
Symbols:
+ +[HFMediaHelper isHomeAccessory:]
+ +[HFSiriUtilities addLinwoodDependencyForAccessories:toMutableResults:]
+ +[HFSiriUtilities disabledReasonText]
+ +[HFSiriUtilities hasLinwoodCapableAndAccessRestrictedPhone]
+ +[HFSiriUtilities isLinwoodCapableForAppleTVAccessory:]
+ +[HFSiriUtilities isLinwoodEnabledForAccessory:]
+ +[HFSiriUtilities isMeDeviceLinwoodEnabled]
+ +[HFSiriUtilities linwoodDependencyIdentifiersForAccessories:]
+ +[HFSiriUtilities meDeviceLinwoodStateDidChangeNotification]
+ +[HFSiriUtilities shouldDisablePersonalContentToggleForAccessory:]
+ +[HFSiriUtilities startObservingLinwoodStateChanges]
+ +[HFSiriUtilities stopObservingLinwoodStateChanges]
+ +[HFSiriUtilities supportsMeDeviceLinwoodState]
+ +[HMAccessory(HFMediaAdditions) hf_audioAccessoryProductName]
+ +[HMAccessory(HFMediaAdditions) hf_homeAccessoryProductName]
+ -[HFAccessorySettingItem _isAllowHeySiriSettingSupportedOnAppleTV]
+ -[HFAccessorySettingItem _isLinwoodSettingSupportedOnAppleTV]
+ -[HFAccessorySettingItem _shouldDisableTouchAndHoldWithReasons:]
+ -[HFAccessorySettingItem _supportsTopCapTouchAndHold]
+ -[HFAccessorySettingTouchAndVisualizationAdapter initWithHomeKitSettingsVendor:keyPaths:mode:updateHandler:]
+ -[HFAccessorySettingTouchAndVisualizationAdapter initWithHomeKitSettingsVendor:mode:]
+ -[HFAccessorySettingTouchAndVisualizationAdapter shouldShowSettingsEntity:]
+ -[HFHomeKitDispatcher addCameraVideoSensorsObserver:]
+ -[HFHomeKitDispatcher cameraVideoSensorsObserverDispatcher]
+ -[HFHomeKitDispatcher removeCameraVideoSensorsObserver:]
+ -[HFHomeKitDispatcher setCameraVideoSensorsObserverDispatcher:]
+ -[HFMediaAccessoryItem homeAccessoryVariant]
+ -[HFMediaAccessoryItem isHomeAccessory]
+ -[HFMediaAccessoryItem primaryTopCapAccessory]
+ -[HMAccessory(HFAdditions) hf_hasMotionActivatedLights]
+ -[HMAccessory(HFMediaAdditions) hf_isHomeAccessory]
+ -[HMHome(Additions) hf_allHomeAccessoriesThatWillChime]
+ -[HMHome(Additions) hf_allHomeAccessories]
+ -[HMHome(Additions) hf_hasHomeAccessories]
+ -[HMHome(Additions) hf_homeAccessories]
+ -[HMHome(Additions) hf_personalRequestCapableAppleTVs]
+ -[HMService(Additions) hf_hasMotionDetection]
+ -[HMService(Additions) hf_isLightbulbWithSetDuration]
+ GCC_except_table149
+ GCC_except_table152
+ GCC_except_table155
+ GCC_except_table158
+ GCC_except_table165
+ GCC_except_table195
+ GCC_except_table196
+ GCC_except_table199
+ GCC_except_table326
+ GCC_except_table413
+ GCC_except_table417
+ GCC_except_table425
+ GCC_except_table426
+ GCC_except_table429
+ GCC_except_table432
+ GCC_except_table440
+ GCC_except_table441
+ GCC_except_table443
+ GCC_except_table454
+ GCC_except_table465
+ GCC_except_table469
+ GCC_except_table470
+ GCC_except_table472
+ GCC_except_table473
+ OBJC_IVAR_$_HFHomeKitDispatcher._cameraVideoSensorsObserverDispatcher
+ _HFAccessorySettingAdapterIdentifierTouchAndVisualization
+ _HFDemoModeAccessoryTypeHomeAccessory1Key
+ _HFDemoModeAccessoryTypeHomeAccessory2Key
+ _HFHomePodMediaAccessorySettingKeyPathDisplayGroup
+ _HFHomePodMediaAccessorySettingKeyPathLinwood
+ _HFSymbolIconIdentifierHomeAccessory1
+ _HFSymbolIconIdentifierHomeAccessory2
+ _HFSymbolIconIdentifierMotionActivatedLight
+ _HFTouchAndVisualizationGroupKeyPath
+ _HFTouchAndVisualizationInteractionGroupKeyPath
+ _HFTouchAndVisualizationInteractionTouchEnabledGroupKeyPath
+ _HFTouchAndVisualizationMediaVisualizerVisualizationGroupKeyPath
+ _HMAccessoryCategoryTypeHomeAccessory
+ _OBJC_CLASS_$_AFSiriAvailability
+ _OBJC_CLASS_$_HFAccessorySettingTouchAndVisualizationAdapter
+ _OBJC_CLASS_$_HFSiriUtilities
+ _OBJC_CLASS_$_ISSymbol
+ _OBJC_CLASS_$_UTType
+ _OBJC_CLASS_$_UTTypeRecord
+ _OBJC_METACLASS_$_HFAccessorySettingTouchAndVisualizationAdapter
+ _OBJC_METACLASS_$_HFSiriUtilities
+ __46-[HFMediaAccessoryItem primaryTopCapAccessory]_block_invoke
+ __OBJC_$_CLASS_METHODS_HFSiriUtilities
+ __OBJC_$_CLASS_PROP_LIST_HFSiriUtilities
+ __OBJC_$_INSTANCE_METHODS_HFAccessorySettingTouchAndVisualizationAdapter
+ __OBJC_$_PROP_LIST_HFAccessorySettingTouchAndVisualizationAdapter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HMCameraProfileVideoSensorsDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HMCameraProfileVideoSensorsDelegate
+ __OBJC_$_PROTOCOL_REFS_HFCameraVideoSensorsObserver
+ __OBJC_$_PROTOCOL_REFS_HMCameraProfileVideoSensorsDelegate
+ __OBJC_CLASS_PROTOCOLS_$_HFAccessorySettingTouchAndVisualizationAdapter
+ __OBJC_CLASS_RO_$_HFAccessorySettingTouchAndVisualizationAdapter
+ __OBJC_CLASS_RO_$_HFSiriUtilities
+ __OBJC_LABEL_PROTOCOL_$_HFCameraVideoSensorsObserver
+ __OBJC_LABEL_PROTOCOL_$_HMCameraProfileVideoSensorsDelegate
+ __OBJC_METACLASS_RO_$_HFAccessorySettingTouchAndVisualizationAdapter
+ __OBJC_METACLASS_RO_$_HFSiriUtilities
+ __OBJC_PROTOCOL_$_HFCameraVideoSensorsObserver
+ __OBJC_PROTOCOL_$_HMCameraProfileVideoSensorsDelegate
+ __OBJC_PROTOCOL_REFERENCE_$_HFCameraVideoSensorsObserver
+ ___39-[HMHome(Additions) hf_homeAccessories]_block_invoke
+ ___42-[HMHome(Additions) hf_allHomeAccessories]_block_invoke
+ ___42-[HMHome(Additions) hf_hasHomeAccessories]_block_invoke
+ ___46-[HFMediaAccessoryItem primaryTopCapAccessory]_block_invoke
+ ___46-[HFMediaAccessoryItem primaryTopCapAccessory]_block_invoke_2
+ ___53-[HFAccessorySettingItem _supportsTopCapTouchAndHold]_block_invoke
+ ___53-[HFAccessorySettingItem _supportsTopCapTouchAndHold]_block_invoke_2
+ ___54-[HMHome(Additions) hf_personalRequestCapableAppleTVs]_block_invoke
+ ___55-[HMHome(Additions) hf_allHomeAccessoriesThatWillChime]_block_invoke
+ ___88-[HMCameraProfile(HFUserNotificationServiceSettings) hf_updateUserNotificationSettings:]_block_invoke
+ ___block_descriptor_41_e8_32s_e51_"NAFuture"16?0"HFServiceLikeItemUpdateResponse"8ls32l8
+ _flat unique So35HMCameraProfileVideoSensorsDelegate_p
+ _objc_msgSend$_appleTVAccessoryForVendor
+ _objc_msgSend$_isAllowHeySiriSettingSupportedOnAppleTV
+ _objc_msgSend$_isLinwoodSettingSupportedOnAppleTV
+ _objc_msgSend$_shouldDisableTouchAndHoldWithReasons:
+ _objc_msgSend$_supportsTopCapTouchAndHold
+ _objc_msgSend$_typeWithDeviceModelCode:
+ _objc_msgSend$addCameraVideoSensorsObserver:
+ _objc_msgSend$cameraVideoSensorsObserverDispatcher
+ _objc_msgSend$fromPreferences
+ _objc_msgSend$hasLinwoodCapableAndAccessRestrictedPhone
+ _objc_msgSend$hf_allHomeAccessories
+ _objc_msgSend$hf_allHomeAccessoriesThatWillChime
+ _objc_msgSend$hf_hasHomeAccessories
+ _objc_msgSend$hf_hasMotionActivatedLights
+ _objc_msgSend$hf_hasMotionDetection
+ _objc_msgSend$hf_homeAccessories
+ _objc_msgSend$hf_homeAccessoryProductName
+ _objc_msgSend$hf_isHomeAccessory
+ _objc_msgSend$hf_isLightbulbWithSetDuration
+ _objc_msgSend$homeAccessoryVariant
+ _objc_msgSend$isHomeAccessory
+ _objc_msgSend$isLinwoodCapableAndAccessRestricted
+ _objc_msgSend$isLinwoodCapableForAppleTVAccessory:
+ _objc_msgSend$isLinwoodEnabledForAccessory:
+ _objc_msgSend$linwoodDependencyIdentifiersForAccessories:
+ _objc_msgSend$removeCameraVideoSensorsObserver:
+ _objc_msgSend$setVideoSensorsDelegate:
+ _objc_msgSend$supportsAppleTVSiriSettings
+ _objc_msgSend$supportsTopCapTouchAndHold
+ _objc_msgSend$symbolForTypeIdentifier:error:
+ _objc_msgSend$typeRecordWithIdentifier:
+ _symbolic ______pSgXw So35HMCameraProfileVideoSensorsDelegateP
+ _symbolic ______pSgXwz_Xx So35HMCameraProfileVideoSensorsDelegateP
- GCC_except_table147
- GCC_except_table150
- GCC_except_table153
- GCC_except_table156
- GCC_except_table193
- GCC_except_table194
- GCC_except_table197
- GCC_except_table316
- GCC_except_table393
- GCC_except_table406
- GCC_except_table407
- GCC_except_table409
- GCC_except_table410
- GCC_except_table415
- GCC_except_table422
- GCC_except_table423
- GCC_except_table431
- GCC_except_table444
- GCC_except_table445
- GCC_except_table449
- GCC_except_table450
- GCC_except_table452
- GCC_except_table463
CStrings:
+ "-[HFAccessorySettingTouchAndVisualizationAdapter initWithHomeKitSettingsVendor:keyPaths:mode:updateHandler:]"
+ "Accessory: %@ supportsTopCapTouchAndHold: %{BOOL}d"
+ "Apple TV"
+ "Audio Accessory"
+ "AudioAccessory11,1"
+ "HFAccessorySettingTouchAndVisualizationAdapter.m"
+ "HFCharacteristicValueDoorStateDoorOpen"
+ "HFCharacteristicValueDoorStateForcedOpen"
+ "HFErrorComponent building error description for Home Accesory: %@"
+ "HFLinwoodSiriVelvetRopeFooter"
+ "HFMediaAccessoryStateSettingsSyncingDescription_J490"
+ "HFNetworkProtectionSupportIncompatibleHomeHub_J490"
+ "HFSensitiveStrings-J490"
+ "HFSensitiveStrings-Linwood"
+ "HFSensitiveStrings-LockDPS"
+ "HFSensitiveStrings-TopCapNight"
+ "HFServiceLongFormErrorNoThreadNetworkLocal_J490"
+ "HFServiceLongFormErrorNoThreadNetworkNoResident_J490"
+ "HFSetupPairingControllerStatusDescriptionFailureNoHomeHub_J490"
+ "HFSiriFooterPrivacyText_J490"
+ "HFSiriUtilitiesMeDeviceLinwoodStateDidChange"
+ "HFStatusDetailsNoRemoteAccessDescription_AppleTVHomePod_J490"
+ "HFStatusDetailsNoRemoteAccessDescription_HomePod_J490"
+ "HFSymptomDescriptionProblemFixAccountMessageHomePod_J490"
+ "HFSymptomLongDescriptionDNSServerOutage_J490"
+ "HFSymptomLongDescriptionDoubleNAT_J490"
+ "HFSymptomLongDescriptionNeediCloudCredential_J490"
+ "HFSymptomLongDescriptionNetworkMisconfiguredUnknown_J490"
+ "HFSymptomLongDescriptionNetworkNotShareableProblemWithName_J490"
+ "HFSymptomLongDescriptionNetworkNotShareableProblem_J490"
+ "HFSymptomLongDescriptionNetworkProfileFixProblemWithName_J490"
+ "HFSymptomLongDescriptionNetworkProfileFixProblem_J490"
+ "HFSymptomLongDescriptionNetworkProfileInstallProblemWithName_J490"
+ "HFSymptomLongDescriptionNetworkProfileInstallProblem_J490"
+ "HFSymptomLongDescriptionVPNProfileExpired_J490"
+ "HFSymptomLongDescriptionWiFiDisassociation_J490"
+ "HF_SiriServices"
+ "HF_TopCap"
+ "HomeAccessory"
+ "HomeAccessory1"
+ "HomeAccessory2"
+ "HomePod Siri Preview is not supported in this configuration."
+ "HomePodTopCap"
+ "SecondPartyCamera"
+ "Siri AI is disabled pending velvet rope access."
+ "Touch and Hold for Siri should be disabled because Lock Controls is on for this accessory."
+ "TouchAndVisualizationAdapter"
+ "[HFAccessorySettingGroupItem-_decorateHiddenOrDisabled]: Hiding Apple TV Personal Content | name:%{private}@ | uniqueIdentifier:%{public}@"
+ "[HFSiriUtilities-hasLinwoodCapableAndAccessRestrictedPhone]: %{BOOL}d"
+ "[HFSiriUtilities-isLinwoodCapableForAppleTVAccessory]: name:%{private}@ | uniqueIdentifier:%{public}@ | isAccessorySupported:%{BOOL}d"
+ "[HFSiriUtilities-isLinwoodEnabledForAccessory]: HomePod Linwood not supported on this train, returning NO | name:%{private}@ | uniqueIdentifier:%{public}@"
+ "[HFSiriUtilities-isLinwoodEnabledForAccessory]: No media profile found | name:%{private}@ | uniqueIdentifier:%{public}@"
+ "[HFSiriUtilities-isLinwoodEnabledForAccessory]: No value manager found | name:%{private}@ | uniqueIdentifier:%{public}@"
+ "[HFSiriUtilities-isLinwoodEnabledForAccessory]: name:%{private}@ | uniqueIdentifier:%{public}@ | linwoodEnabled:%{BOOL}d"
+ "[HFSiriUtilities-isMeDeviceLinwoodEnabled]: Not available on this platform, returning NO"
+ "[HFSiriUtilities-startObservingLinwoodStateChanges]: Not available on this platform"
+ "[HFSiriUtilities-stopObservingLinwoodStateChanges]: Not available on this platform"
+ "_J490"
+ "com.apple.homeaccessory-1"
+ "com.apple.homeaccessory-2"
+ "intercom"
+ "light.overhead.right.fill"
+ "linwood"
+ "lock_dps"
+ "root.display"
+ "root.display.touchAndVisualization"
+ "root.display.touchAndVisualization.interaction"
+ "root.display.touchAndVisualization.interaction.touchEnabled"
+ "root.display.touchAndVisualization.mediaVisualizer.visualization"
+ "root.siri.personalSiriEnabled"
- "HFMediaAccessoryStateSettingsSyncingDescription"
- "HFNetworkProtectionSupportIncompatibleHomeHub"
- "HFServiceLongFormErrorNoThreadNetworkLocal"
- "HFServiceLongFormErrorNoThreadNetworkNoResident"
- "HFSetupPairingControllerStatusDescriptionFailureNoHomeHub"
- "HFSiriFooterPrivacyText"
- "HFStatusDetailsNoRemoteAccessDescription_AppleTVHomePod"
- "HFStatusDetailsNoRemoteAccessDescription_HomePod"
- "HFSymptomDescriptionProblemFixAccountMessageHomePod"
- "HFSymptomLongDescriptionDNSServerOutage"
- "HFSymptomLongDescriptionDoubleNAT"
- "HFSymptomLongDescriptionNetworkMisconfiguredUnknown"
- "HFSymptomLongDescriptionNetworkNotShareableProblem"
- "HFSymptomLongDescriptionNetworkNotShareableProblemWithName"
- "HFSymptomLongDescriptionNetworkProfileFixProblem"
- "HFSymptomLongDescriptionNetworkProfileFixProblemWithName"
- "HFSymptomLongDescriptionNetworkProfileInstallProblem"
- "HFSymptomLongDescriptionNetworkProfileInstallProblemWithName"
- "HFSymptomLongDescriptionVPNProfileExpired"
- "HFSymptomLongDescriptionWiFiDisassociation"
- "waveform"
```
