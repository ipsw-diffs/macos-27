## uarpassetmanagerd

> `/usr/libexec/uarpassetmanagerd`

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

 1587.1.3.0.0
-  __TEXT.__text: 0x2faa8
+  __TEXT.__text: 0x2f758
   __TEXT.__auth_stubs: 0x530
   __TEXT.__objc_stubs: 0x2920
   __TEXT.__objc_methlist: 0x14dc
-  __TEXT.__cstring: 0x3181
+  __TEXT.__cstring: 0x317d
   __TEXT.__oslogstring: 0x1afb
   __TEXT.__objc_methname: 0x3045
   __TEXT.__objc_classname: 0x341
   __TEXT.__objc_methtype: 0x897
   __TEXT.__gcc_except_tab: 0x11c
-  __TEXT.__unwind_info: 0x408
+  __TEXT.__unwind_info: 0x7e8
   __DATA_CONST.__const: 0x2cd8
   __DATA_CONST.__cfstring: 0x3020
   __DATA_CONST.__objc_classlist: 0x98
Symbols:
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-9e7e989f95f8a46cdbf990e9130ad4a4.o
+ ___kCFBooleanFalse
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-0f055d05674cdcd26b806ef6aa4501f8.o
- ___kCFBooleanTrue
Functions:
~ _AUSettingsPallasAudienceTypeToString : 560 -> 548
~ _getInfoForAccessory : 212 -> 200
~ _getURLForAssetURLType : 360 -> 348
~ _findPartnerSerialNumbersInDatabase : 452 -> 440
~ _findPartnerSerialNumberForAccessoryID : 284 -> 272
~ _findPartnerSerialNumberForAccessory : 1332 -> 1320
~ _getAccessoryDatabaseKeyForAccessoryID : 284 -> 272
~ _getAccessoryDatabaseKeyForAccessory : 584 -> 572
~ _updateSeedEnablementForAccessory : 732 -> 736
~ +[AUHelperInstance sharedInstance] : 220 -> 208
~ -[AUHelperInstance remoteObject] : 164 -> 152
~ +[AUHelperInstance xpcConnectionToHelper] : 816 -> 804
~ ___54-[UARPSettingsAccessory isAssetLocationSettingsEqual:]_block_invoke : 148 -> 136
~ -[UARPSettingsAccessory encodeAsDictionary] : 2888 -> 2876
~ -[UARPSettingsAccessory encodeAsChangedDictionary] : 568 -> 556
~ -[UARPSettingsAccessory description] : 156 -> 144
~ -[UARPAssetSubscriptionMobileAssetSU description] : 988 -> 976
~ -[UARPDeploymentRule description] : 204 -> 192
~ +[UARPAssetSubscriptioniCloud resolvedContainerIDForContainerID:] : 788 -> 776
~ +[UARPAssetSubscriptioniCloud cacheSubdirectoryForContainerID:developmentEnvironment:] : 540 -> 528
~ -[UARPAssetSubscriptioniCloud description] : 392 -> 380
~ +[UARPSandboxExtension readTokenStringWithURL:] : 740 -> 728
~ +[UARPSandboxExtension readWriteTokenStringWithURL:] : 740 -> 728
~ +[NSUserDefaults(AUHelperExtend) AUDeveloperSettingsAccessoryDatabase] : 424 -> 412
~ +[NSUserDefaults(AUHelperExtend) AUDeveloperSettingsObjectWithKey:] : 656 -> 644
~ +[AUDeveloperSettingsDatabase sharedDatabase] : 144 -> 132
~ -[AUDeveloperSettingsDatabase accessoryList] : 368 -> 356
~ -[AUDeveloperSettingsDatabase remoteAccessoryList] : 592 -> 580
~ -[AUDeveloperSettingsDatabase accessoriesDictionary] : 400 -> 388
~ _MapPreferenceSuiteToString : 188 -> 176
~ _currentOSTrainName : 292 -> 280
~ _createSubscriptionForPersonality : 8184 -> 8172
~ _loadProfileAssetOverrideSettings : 796 -> 784
~ _loadProfilePallasURLOverrideSetting : 324 -> 312
~ _generateMobileAssetBaseAddress : 1568 -> 1556
~ _createPersonalityForSubscription : 892 -> 880
~ _createPersonalityForiCloudSubscription : 588 -> 576
~ _getContainerIDFromCFPrefs : 500 -> 488
~ _createiCloudSubscriptionForPersonality : 992 -> 980
~ _getDefaultMesuAddress : 116 -> 104
~ _getDefaultPallasAudience : 136 -> 124
~ -[UARPAssetManagerServiceManager checkCacheForPersonality:releaseNotes:] : 592 -> 580
~ -[UARPAssetCacheRecord description] : 260 -> 248
~ _UARPAssetManagerServiceCacheTypeToString : 244 -> 232
~ _getAssetBundle : 428 -> 416
~ _getRestoreVersionForMAAsset : 160 -> 148
~ _getOSVersionForMAAsset : 160 -> 148
~ _getBuildVersionForMAAsset : 160 -> 148
~ _getMinOSVersionForMAAsset : 164 -> 152
~ _getMaxOSVersionForMAAsset : 164 -> 152
~ _getAssetVersionForMAAsset : 660 -> 648
~ _assetWithMaxVersion : 664 -> 652
~ _getSoftwareUpdateAssetVersionForMAAsset : 336 -> 324
~ _softwareUpdateAssetWithMaxVersion : 2160 -> 2148
~ _AssetManagerDirectoryPath : 136 -> 124
~ _mobileAssetPrefixForSubscription : 132 -> 120
~ _containerIDForAssetContainerType : 468 -> 456
~ -[UARPAssetCacheRecordiCloud description] : 384 -> 372
~ -[UARPAssetManagerServiceInstanceiCloud checkCacheForPersonality:releaseNotes:] : 500 -> 488
~ -[UARPAssetManagerServiceInstanceiCloud createPersonality:] : 664 -> 652
~ -[UARPAssetManagerServiceInstanceiCloud createSubscriptionForPrimeCache:] : 560 -> 548
~ -[UARPAssetManagerServiceInstanceiCloud encodedClasses] : 272 -> 260
~ -[UARPAssetManagerServiceInstanceMobileAsset checkCacheForPersonality:releaseNotes:] : 2488 -> 2476
~ -[UARPAssetManagerServiceInstanceMobileAsset createSubscriptionForPrimeCache:] : 588 -> 576
~ -[UARPAssetManagerServiceInstanceMobileAsset createPersonality:] : 848 -> 836
~ -[UARPAssetManagerServiceInstanceMobileAsset encodedClasses] : 344 -> 332
~ -[UARPAssetManagerController getAssetURLForPersonality:releaseNotes:] : 156 -> 144
~ -[UARPAssetSubscriptionMobileAsset description] : 840 -> 828
~ -[UARPAssetManagerServiceInstance checkCacheForSubscription:] : 644 -> 632
~ -[UARPAssetManagerServiceInstance description] : 156 -> 144
~ -[UARPAssetManagerServiceInstance delegate] : 64 -> 52
~ -[UARPAssetSubscription description] : 252 -> 240
CStrings:
+ "Fizz"
- "FizzSeed"
```
