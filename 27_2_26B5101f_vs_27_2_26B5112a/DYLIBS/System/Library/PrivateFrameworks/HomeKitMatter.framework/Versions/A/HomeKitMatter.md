## HomeKitMatter

> `/System/Library/PrivateFrameworks/HomeKitMatter.framework/Versions/A/HomeKitMatter`

```diff

-1520.2.3.0.2
-  __TEXT.__text: 0x18f37c
-  __TEXT.__objc_methlist: 0xadfc
+1520.2.7.4.1
+  __TEXT.__text: 0x198058
+  __TEXT.__objc_methlist: 0xafac
   __TEXT.__const: 0x2b0
   __TEXT.__dlopen_cstrs: 0x58
-  __TEXT.__gcc_except_tab: 0x30ec
-  __TEXT.__cstring: 0x6c80
-  __TEXT.__oslogstring: 0x4c73c
+  __TEXT.__gcc_except_tab: 0x3454
+  __TEXT.__cstring: 0x6f3b
+  __TEXT.__oslogstring: 0x4de25
   __TEXT.__ustring: 0x68
-  __TEXT.__unwind_info: 0x3d70
+  __TEXT.__unwind_info: 0x3ef8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xbc0
+  __DATA_CONST.__const: 0xc28
   __DATA_CONST.__objc_classlist: 0x460
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x138
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6f80
+  __DATA_CONST.__objc_selrefs: 0x7138
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x318
-  __DATA_CONST.__objc_arraydata: 0x240
-  __DATA_CONST.__got: 0x980
-  __AUTH_CONST.__const: 0x5710
-  __AUTH_CONST.__cfstring: 0x6d60
-  __AUTH_CONST.__objc_const: 0x106d0
-  __AUTH_CONST.__objc_intobj: 0x16b0
-  __AUTH_CONST.__objc_arrayobj: 0x168
+  __DATA_CONST.__objc_arraydata: 0x250
+  __DATA_CONST.__got: 0x9c8
+  __AUTH_CONST.__const: 0x5a00
+  __AUTH_CONST.__cfstring: 0x6f20
+  __AUTH_CONST.__objc_const: 0x10770
+  __AUTH_CONST.__objc_intobj: 0x17a0
+  __AUTH_CONST.__objc_arrayobj: 0x198
   __AUTH_CONST.__objc_doubleobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x1ea0
-  __DATA.__objc_ivar: 0xbb8
+  __DATA.__objc_ivar: 0xbc4
   __DATA.__data: 0xea0
-  __DATA.__bss: 0x4a8
+  __DATA.__bss: 0x4c8
   __DATA_DIRTY.__objc_data: 0xd20
   __DATA_DIRTY.__bss: 0xa0
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth

   - /System/Library/PrivateFrameworks/UARPKit.framework/Versions/A/UARPKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 4569
-  Symbols:   10459
-  CStrings:  5596
+  Functions: 4648
+  Symbols:   10618
+  CStrings:  5715
 
Symbols:
+ +[HMMTRFeatures disableDemoModeSuppressDPSForTests]
+ +[HMMTRFeatures disableFeatureLockDPSForTests]
+ +[HMMTRFeatures enableDemoModeSuppressDPSForTests]
+ +[HMMTRFeatures enableFeatureLockDPSForTests]
+ +[HMMTRFeatures unsetDemoModeSuppressDPSForTests]
+ +[HMMTRFeatures unsetFeatureLockDPSForTests]
+ -[HMMTRAccessoryServer connectivityMonitorClusterFactory]
+ -[HMMTRAccessoryServer generalCommissioningClusterFactory]
+ -[HMMTRAccessoryServer networkCommissioningClusterFactory]
+ -[HMMTRAccessoryServer removeClusterIDForCharacteristic:endpointID:]
+ -[HMMTRAccessoryServer setConnectivityMonitorClusterFactory:]
+ -[HMMTRAccessoryServer setGeneralCommissioningClusterFactory:]
+ -[HMMTRAccessoryServer setNetworkCommissioningClusterFactory:]
+ -[HMMTRAccessoryServer(Diagnostics) supportsEnhancedMetricsForAccessory:]
+ -[HMMTRAccessoryServer(NetworkRepair) _addThreadNetwork:dataset:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _addWiFiNetworks:networks:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _armFailSafeWithCluster:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _commissioningCompleteWithCluster:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _connectThreadNetwork:networkID:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _createGeneralCommissioningCluster]
+ -[HMMTRAccessoryServer(NetworkRepair) _createThreadNetworkCommissioningCluster]
+ -[HMMTRAccessoryServer(NetworkRepair) _createWiFiNetworkCommissioningCluster]
+ -[HMMTRAccessoryServer(NetworkRepair) _disarmFailSafeWithCluster:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _extractThreadExtendedPANIDFromNetworksAttribute:]
+ -[HMMTRAccessoryServer(NetworkRepair) _extractWiFiSSIDsFromNetworksAttribute:]
+ -[HMMTRAccessoryServer(NetworkRepair) _findAllNetworkCommissioningEndpoints]
+ -[HMMTRAccessoryServer(NetworkRepair) _findNetworkCommissioningEndpointForInterfaceType:]
+ -[HMMTRAccessoryServer(NetworkRepair) _handleAtCapacityWiFiRepair:deviceSSIDs:preferredNetworks:maxNetworks:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _hasDualNetworkCommissioningClusters]
+ -[HMMTRAccessoryServer(NetworkRepair) _removeWiFiNetwork:ssid:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _reorderWiFiNetworks:networks:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) hasDualNetworkCommissioningClusters]
+ -[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) repairWiFiNetworkWithCompletion:completion:]
+ -[HMMTRSyncClusterThermostat readAttributePluginCurrentRelativeHumidityWithParams:]
+ -[HMMTRSyncClusterThermostat updatedValuePluginCurrentRelativeHumidityForAttributeReport:responseHandler:]
+ GCC_except_table1020
+ GCC_except_table1083
+ GCC_except_table1091
+ GCC_except_table1213
+ GCC_except_table1281
+ GCC_except_table1327
+ GCC_except_table1335
+ GCC_except_table1388
+ GCC_except_table1396
+ GCC_except_table1433
+ GCC_except_table1471
+ GCC_except_table1498
+ GCC_except_table1697
+ GCC_except_table1740
+ GCC_except_table1895
+ GCC_except_table1896
+ GCC_except_table1899
+ GCC_except_table1922
+ GCC_except_table1923
+ GCC_except_table1926
+ GCC_except_table1934
+ GCC_except_table1935
+ GCC_except_table1946
+ GCC_except_table1949
+ GCC_except_table1950
+ GCC_except_table1951
+ GCC_except_table1961
+ GCC_except_table1970
+ GCC_except_table1977
+ GCC_except_table1979
+ GCC_except_table1981
+ GCC_except_table1982
+ GCC_except_table1984
+ GCC_except_table2053
+ GCC_except_table2059
+ GCC_except_table2147
+ GCC_except_table2265
+ GCC_except_table2267
+ GCC_except_table2298
+ GCC_except_table2309
+ GCC_except_table2311
+ GCC_except_table2367
+ GCC_except_table2413
+ GCC_except_table2438
+ GCC_except_table2510
+ GCC_except_table2808
+ GCC_except_table2810
+ GCC_except_table2812
+ GCC_except_table2816
+ GCC_except_table2877
+ GCC_except_table2910
+ GCC_except_table2957
+ GCC_except_table2959
+ GCC_except_table2990
+ GCC_except_table2991
+ GCC_except_table2992
+ GCC_except_table3014
+ GCC_except_table3015
+ GCC_except_table3016
+ GCC_except_table3018
+ GCC_except_table3019
+ GCC_except_table3020
+ GCC_except_table3021
+ GCC_except_table3031
+ GCC_except_table3033
+ GCC_except_table3045
+ GCC_except_table3066
+ GCC_except_table3081
+ GCC_except_table3087
+ GCC_except_table3105
+ GCC_except_table3109
+ GCC_except_table3124
+ GCC_except_table3127
+ GCC_except_table3131
+ GCC_except_table3133
+ GCC_except_table3163
+ GCC_except_table3172
+ GCC_except_table3177
+ GCC_except_table3189
+ GCC_except_table3243
+ GCC_except_table3244
+ GCC_except_table3640
+ GCC_except_table3665
+ GCC_except_table3666
+ GCC_except_table3667
+ GCC_except_table3671
+ GCC_except_table3677
+ GCC_except_table3680
+ GCC_except_table3696
+ GCC_except_table3711
+ GCC_except_table3780
+ GCC_except_table3781
+ GCC_except_table3814
+ GCC_except_table3823
+ GCC_except_table3827
+ GCC_except_table3861
+ GCC_except_table3865
+ GCC_except_table3873
+ GCC_except_table3895
+ GCC_except_table3899
+ GCC_except_table3942
+ GCC_except_table3944
+ GCC_except_table3946
+ GCC_except_table3965
+ GCC_except_table3967
+ GCC_except_table3988
+ GCC_except_table4065
+ GCC_except_table4112
+ GCC_except_table4132
+ GCC_except_table4155
+ GCC_except_table4159
+ GCC_except_table4174
+ GCC_except_table4175
+ GCC_except_table4176
+ GCC_except_table4182
+ GCC_except_table4189
+ GCC_except_table4194
+ GCC_except_table4231
+ GCC_except_table4253
+ GCC_except_table4299
+ GCC_except_table4305
+ GCC_except_table4308
+ GCC_except_table4394
+ GCC_except_table4395
+ GCC_except_table4453
+ GCC_except_table4456
+ GCC_except_table4520
+ GCC_except_table4580
+ GCC_except_table4584
+ GCC_except_table4590
+ GCC_except_table4594
+ GCC_except_table4628
+ OBJC_IVAR_$_HMMTRAccessoryServer._connectivityMonitorClusterFactory
+ OBJC_IVAR_$_HMMTRAccessoryServer._generalCommissioningClusterFactory
+ OBJC_IVAR_$_HMMTRAccessoryServer._networkCommissioningClusterFactory
+ _AppleExtensionNeedsAdditionalConfigurationAttribute
+ _OBJC_CLASS_$_HMHomeManager
+ _OBJC_CLASS_$_MTRClusterAppleAccessoryConnectivityMonitor
+ _OBJC_CLASS_$_MTRNetworkCommissioningClusterAddOrUpdateThreadNetworkParams
+ _OBJC_CLASS_$_MTRNetworkCommissioningClusterAddOrUpdateWiFiNetworkParams
+ _OBJC_CLASS_$_MTRNetworkCommissioningClusterConnectNetworkParams
+ _OBJC_CLASS_$_MTRNetworkCommissioningClusterRemoveNetworkParams
+ _OBJC_CLASS_$_MTRNetworkCommissioningClusterReorderNetworkParams
+ _OBJC_CLASS_$_MTRThreadOperationalDataset
+ __120-[HMMTRAccessoryServer(NetworkRepair) _handleAtCapacityWiFiRepair:deviceSSIDs:preferredNetworks:maxNetworks:completion:]_block_invoke
+ __49-[HMMTRAccessoryServer initWithKeystore:browser:]_block_invoke
+ __76-[HMMTRAccessoryServer(NetworkRepair) _addWiFiNetworks:networks:completion:]_block_invoke
+ __80-[HMMTRAccessoryServer(NetworkRepair) _reorderWiFiNetworks:networks:completion:]_block_invoke
+ __82-[HMMTRAccessoryServer(NetworkRepair) repairWiFiNetworkWithCompletion:completion:]_block_invoke
+ __84-[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_HMMTRAccessoryServer(HAPAccessory|RemoteAccess|Diagnostics|DiagnosticsInternal|SystemCommissionerPairing|NetworkRepair)
+ ___120-[HMMTRAccessoryServer(NetworkRepair) _handleAtCapacityWiFiRepair:deviceSSIDs:preferredNetworks:maxNetworks:completion:]_block_invoke
+ ___49-[HMMTRAccessoryServer initWithKeystore:browser:]_block_invoke_2
+ ___49-[HMMTRAccessoryServer initWithKeystore:browser:]_block_invoke_3
+ ___73-[HMMTRAccessoryServer(Diagnostics) supportsEnhancedMetricsForAccessory:]_block_invoke
+ ___74-[HMMTRAccessoryServer(NetworkRepair) _armFailSafeWithCluster:completion:]_block_invoke
+ ___74-[HMMTRAccessoryServer(NetworkRepair) _removeWiFiNetwork:ssid:completion:]_block_invoke
+ ___76-[HMMTRAccessoryServer(NetworkRepair) _addThreadNetwork:dataset:completion:]_block_invoke
+ ___76-[HMMTRAccessoryServer(NetworkRepair) _addWiFiNetworks:networks:completion:]_block_invoke
+ ___77-[HMMTRAccessoryServer(NetworkRepair) _disarmFailSafeWithCluster:completion:]_block_invoke
+ ___80-[HMMTRAccessoryServer(NetworkRepair) _reorderWiFiNetworks:networks:completion:]_block_invoke
+ ___82-[HMMTRAccessoryServer(NetworkRepair) _connectThreadNetwork:networkID:completion:]_block_invoke
+ ___82-[HMMTRAccessoryServer(NetworkRepair) repairWiFiNetworkWithCompletion:completion:]_block_invoke
+ ___82-[HMMTRAccessoryServer(NetworkRepair) repairWiFiNetworkWithCompletion:completion:]_block_invoke_2
+ ___84-[HMMTRAccessoryServer(NetworkRepair) _commissioningCompleteWithCluster:completion:]_block_invoke
+ ___84-[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]_block_invoke
+ ___84-[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]_block_invoke_2
+ ___84-[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]_block_invoke_3
+ ___84-[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]_block_invoke_4
+ ___84-[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]_block_invoke_5
+ ___block_descriptor_104_e8_32s40s48s56s64s72bs80bs88w_e17_v16?0"NSError"8l
+ ___block_descriptor_32_e65_"MTRClusterNetworkCommissioning"24?0"HMMTRAccessoryServer"8Q16l
+ ___block_descriptor_32_e66_"MTRBaseClusterGeneralCommissioning"16?0"HMMTRAccessoryServer"8l
+ ___block_descriptor_32_e88_"MTRClusterAppleAccessoryConnectivityMonitor"24?0"HMMTRAccessoryServer"8"NSNumber"16l
+ ___block_descriptor_40_e8_32bs_e79_v24?0"MTRNetworkCommissioningClusterNetworkConfigResponseParams"8"NSError"16l
+ ___block_descriptor_48_e8_32bs40w_e79_v24?0"MTRNetworkCommissioningClusterNetworkConfigResponseParams"8"NSError"16l
+ ___block_descriptor_48_e8_32s40bs_e80_v24?0"MTRNetworkCommissioningClusterConnectNetworkResponseParams"8"NSError"16l
+ ___block_descriptor_48_e8_32s40bs_e87_v24?0"MTRGeneralCommissioningClusterCommissioningCompleteResponseParams"8"NSError"16l
+ ___block_descriptor_56_e8_32bs40r48r_e5_v8?0l
+ ___block_descriptor_56_e8_32bs40r48w_e5_v8?0l
+ ___block_descriptor_56_e8_32s40bs48w_e17_v16?0"NSError"8l
+ ___block_descriptor_64_e8_32s40s48bs56w_e17_v16?0"NSError"8l
+ ___block_descriptor_72_e8_32s40s48r56r64w_e79_v24?0"MTRNetworkCommissioningClusterNetworkConfigResponseParams"8"NSError"16l
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e17_v16?0"NSError"8l
+ ___block_descriptor_80_e8_32s40s48r56r64r72w_e79_v24?0"MTRNetworkCommissioningClusterNetworkConfigResponseParams"8"NSError"16l
+ ___block_descriptor_80_e8_32s40s48s56s64bs72w_e17_v16?0"NSError"8l
+ ___copy_helper_block_e8_32b40r48r
+ ___copy_helper_block_e8_32s40s48r56r64r72w
+ ___copy_helper_block_e8_32s40s48r56r64w
+ ___copy_helper_block_e8_32s40s48s56s64b72w
+ ___copy_helper_block_e8_32s40s48s56s64s72b80b88w
+ ___destroy_helper_block_e8_32s40s48r56r64r72w
+ ___destroy_helper_block_e8_32s40s48r56r64w
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88w
+ ___destroy_helper_block_e8_32s40s48s56s64s72w
+ ___suppressDpsForDemoMode_block_invoke
+ __dispatch_main_q
+ _isFeatureLockDPSEnabled
+ _isFeatureLockDPSEnabledForTests
+ _isFeatureNetworkLinkManagementEnabled
+ _objc_msgSend$_addThreadNetwork:dataset:completion:
+ _objc_msgSend$_addWiFiNetworks:networks:completion:
+ _objc_msgSend$_armFailSafeWithCluster:completion:
+ _objc_msgSend$_commissioningCompleteWithCluster:completion:
+ _objc_msgSend$_connectThreadNetwork:networkID:completion:
+ _objc_msgSend$_createGeneralCommissioningCluster
+ _objc_msgSend$_createThreadNetworkCommissioningCluster
+ _objc_msgSend$_createWiFiNetworkCommissioningCluster
+ _objc_msgSend$_disarmFailSafeWithCluster:completion:
+ _objc_msgSend$_extractThreadExtendedPANIDFromNetworksAttribute:
+ _objc_msgSend$_extractWiFiSSIDsFromNetworksAttribute:
+ _objc_msgSend$_findAllNetworkCommissioningEndpoints
+ _objc_msgSend$_findNetworkCommissioningEndpointForInterfaceType:
+ _objc_msgSend$_handleAtCapacityWiFiRepair:deviceSSIDs:preferredNetworks:maxNetworks:completion:
+ _objc_msgSend$_hasDualNetworkCommissioningClusters
+ _objc_msgSend$_removeWiFiNetwork:ssid:completion:
+ _objc_msgSend$_reorderWiFiNetworks:networks:completion:
+ _objc_msgSend$addOrUpdateThreadNetworkWithParams:expectedValues:expectedValueInterval:completionHandler:
+ _objc_msgSend$addOrUpdateWiFiNetworkWithParams:expectedValues:expectedValueInterval:completionHandler:
+ _objc_msgSend$arrayByAddingObject:
+ _objc_msgSend$connectNetworkWithParams:expectedValues:expectedValueInterval:completion:
+ _objc_msgSend$demoModeStatus
+ _objc_msgSend$extendedPANID
+ _objc_msgSend$generalCommissioningClusterFactory
+ _objc_msgSend$hmf_hexadecimalRepresentation
+ _objc_msgSend$initWithData:
+ _objc_msgSend$isEnabled
+ _objc_msgSend$networkCommissioningClusterFactory
+ _objc_msgSend$networkingStatus
+ _objc_msgSend$readAttributeMaxNetworksWithParams:
+ _objc_msgSend$readAttributePluginCurrentRelativeHumidityWithParams:
+ _objc_msgSend$removeClusterIDForCharacteristic:endpointID:
+ _objc_msgSend$removeNetworkWithParams:expectedValues:expectedValueInterval:completion:
+ _objc_msgSend$reorderNetworkWithParams:expectedValues:expectedValueInterval:completion:
+ _objc_msgSend$resetCachedProtocolMapForTesting
+ _objc_msgSend$setNetworkID:
+ _objc_msgSend$setNetworkIndex:
+ _objc_msgSend$setOperationalDataset:
+ _objc_msgSend$setSsid:
+ _objc_msgSend$subarrayWithRange:
+ _objc_msgSend$suppressDPS
+ _suppressDpsForDemoMode
+ _suppressDpsForDemoModeForTests
+ logCategory._hmf_once_t210
+ logCategory._hmf_once_v211
+ suppressDpsForDemoMode.onceToken
+ suppressDpsForDemoMode.suppressed
- GCC_except_table1081
- GCC_except_table1087
- GCC_except_table1211
- GCC_except_table1279
- GCC_except_table1325
- GCC_except_table1333
- GCC_except_table1386
- GCC_except_table1394
- GCC_except_table1431
- GCC_except_table1469
- GCC_except_table1496
- GCC_except_table1695
- GCC_except_table1738
- GCC_except_table1892
- GCC_except_table1893
- GCC_except_table1897
- GCC_except_table1917
- GCC_except_table1918
- GCC_except_table1924
- GCC_except_table1927
- GCC_except_table1928
- GCC_except_table1992
- GCC_except_table1998
- GCC_except_table2086
- GCC_except_table2204
- GCC_except_table2206
- GCC_except_table2237
- GCC_except_table2248
- GCC_except_table2250
- GCC_except_table2306
- GCC_except_table2352
- GCC_except_table2377
- GCC_except_table2449
- GCC_except_table2738
- GCC_except_table2740
- GCC_except_table2742
- GCC_except_table2746
- GCC_except_table2807
- GCC_except_table2840
- GCC_except_table2887
- GCC_except_table2889
- GCC_except_table2920
- GCC_except_table2921
- GCC_except_table2922
- GCC_except_table2944
- GCC_except_table2945
- GCC_except_table2946
- GCC_except_table2947
- GCC_except_table2948
- GCC_except_table2949
- GCC_except_table2950
- GCC_except_table2951
- GCC_except_table2961
- GCC_except_table2963
- GCC_except_table2975
- GCC_except_table2996
- GCC_except_table3011
- GCC_except_table3032
- GCC_except_table3035
- GCC_except_table3039
- GCC_except_table3054
- GCC_except_table3057
- GCC_except_table3061
- GCC_except_table3063
- GCC_except_table3093
- GCC_except_table3107
- GCC_except_table3119
- GCC_except_table3173
- GCC_except_table3174
- GCC_except_table3564
- GCC_except_table3590
- GCC_except_table3591
- GCC_except_table3592
- GCC_except_table3596
- GCC_except_table3602
- GCC_except_table3605
- GCC_except_table3621
- GCC_except_table3636
- GCC_except_table3705
- GCC_except_table3706
- GCC_except_table3739
- GCC_except_table3748
- GCC_except_table3752
- GCC_except_table3786
- GCC_except_table3790
- GCC_except_table3798
- GCC_except_table3820
- GCC_except_table3824
- GCC_except_table3867
- GCC_except_table3869
- GCC_except_table3871
- GCC_except_table3890
- GCC_except_table3892
- GCC_except_table3913
- GCC_except_table3990
- GCC_except_table4037
- GCC_except_table4057
- GCC_except_table4080
- GCC_except_table4084
- GCC_except_table4099
- GCC_except_table4100
- GCC_except_table4101
- GCC_except_table4107
- GCC_except_table4114
- GCC_except_table4119
- GCC_except_table4156
- GCC_except_table4178
- GCC_except_table4220
- GCC_except_table4226
- GCC_except_table4229
- GCC_except_table4315
- GCC_except_table4316
- GCC_except_table4374
- GCC_except_table4377
- GCC_except_table4441
- GCC_except_table4501
- GCC_except_table4505
- GCC_except_table4511
- GCC_except_table4515
- GCC_except_table4549
- __OBJC_$_INSTANCE_METHODS_HMMTRAccessoryServer(HAPAccessory|RemoteAccess|Diagnostics|DiagnosticsInternal|SystemCommissionerPairing)
- __OBJC_$_PROP_LIST_HMMTRAccessoryServer
- logCategory._hmf_once_t208
- logCategory._hmf_once_v209
CStrings:
+ "0000007A-0000-1000-8000-0026BB765291"
+ "101"
+ "45"
+ "@\"MTRBaseClusterGeneralCommissioning\"16@?0@\"HMMTRAccessoryServer\"8"
+ "@\"MTRClusterAppleAccessoryConnectivityMonitor\"24@?0@\"HMMTRAccessoryServer\"8@\"NSNumber\"16"
+ "@\"MTRClusterNetworkCommissioning\"24@?0@\"HMMTRAccessoryServer\"8Q16"
+ "Door State"
+ "Door Tampered"
+ "LockDPS"
+ "MTRBaseClusterDoorLock"
+ "Network Repair: ArmFailSafe failed: %@"
+ "Network Repair: ArmFailSafe returned error code: %@"
+ "Network Repair: Arming fail-safe (60s)"
+ "Network Repair: CommissioningComplete failed: %@"
+ "Network Repair: CommissioningComplete returned error code: %@"
+ "Network Repair: CommissioningComplete succeeded"
+ "Network Repair: Device has dual NetworkCommissioning clusters: %@ (WiFi: %@, Thread: %@)"
+ "Network Repair: Disarm fail-safe failed: %@"
+ "Network Repair: Disarm fail-safe returned error code: %@"
+ "Network Repair: Disarming fail-safe (rollback)"
+ "Network Repair: Fail-safe armed"
+ "Network Repair: Failed to read parts list from root endpoint"
+ "Network Repair: Found NetworkCommissioning cluster at endpoint %@ with FeatureMap 0x%lx"
+ "Network Repair: No Matter device available"
+ "Network Repair: No NetworkCommissioning cluster found for interface type 0x%lx"
+ "Network Repair: Sending CommissioningComplete"
+ "NetworkLinkManagement"
+ "PSK"
+ "RequiresPassword"
+ "SSID"
+ "Thread Repair: AddOrUpdateThreadNetwork failed: %@"
+ "Thread Repair: AddOrUpdateThreadNetwork returned status: %@"
+ "Thread Repair: ConnectNetwork failed: %@"
+ "Thread Repair: ConnectNetwork returned status: %@"
+ "Thread Repair: ConnectNetwork with Extended PAN ID: %@"
+ "Thread Repair: Device already on home's Thread network"
+ "Thread Repair: Extended PAN ID mismatch, updating credentials"
+ "Thread Repair: Failed to extract Extended PAN ID from dataset"
+ "Thread Repair: Feature not enabled"
+ "Thread Repair: Found Thread network with Extended PAN ID: %@"
+ "Thread Repair: No Thread network on device, adding home network"
+ "Thread Repair: No operational dataset provided, skipping repair"
+ "Thread Repair: Successfully connected to Thread network"
+ "Thread Repair: Successfully updated Thread network"
+ "Topology is nil"
+ "WiFi Repair: AddOrUpdateWiFiNetwork failed for '%@': %@"
+ "WiFi Repair: Added network '%@'"
+ "WiFi Repair: Adding %lu missing network(s)"
+ "WiFi Repair: All preferred networks already on device, reordering"
+ "WiFi Repair: At capacity (%lu/%@), removing '%@' to add '%@'"
+ "WiFi Repair: At capacity (%lu/%@), updating %lu existing home network(s)"
+ "WiFi Repair: Capacity limited - adding %lu of %lu missing networks"
+ "WiFi Repair: Device WiFi capacity: %lu current, %@ max"
+ "WiFi Repair: Device at capacity and no primary network available"
+ "WiFi Repair: Failed to add networks: %@"
+ "WiFi Repair: Failed to read MaxNetworks attribute"
+ "WiFi Repair: Failed to remove '%@': %@"
+ "WiFi Repair: Feature not enabled"
+ "WiFi Repair: Found %lu network(s) on device: %@"
+ "WiFi Repair: No preferred networks provided, skipping repair"
+ "WiFi Repair: Reading device network capacity and current networks"
+ "WiFi Repair: ReorderNetwork failed for '%@': %@"
+ "WiFi Repair: Reordering had %lu failures, continuing"
+ "WiFi repair failed: unable to add home network"
+ "WiFi repair failed: unable to remove existing network"
+ "[%{public}@] Network Repair: ArmFailSafe failed: %@"
+ "[%{public}@] Network Repair: ArmFailSafe returned error code: %@"
+ "[%{public}@] Network Repair: Arming fail-safe (60s)"
+ "[%{public}@] Network Repair: CommissioningComplete failed: %@"
+ "[%{public}@] Network Repair: CommissioningComplete returned error code: %@"
+ "[%{public}@] Network Repair: CommissioningComplete succeeded"
+ "[%{public}@] Network Repair: Device has dual NetworkCommissioning clusters: %@ (WiFi: %@, Thread: %@)"
+ "[%{public}@] Network Repair: Disarm fail-safe failed: %@"
+ "[%{public}@] Network Repair: Disarm fail-safe returned error code: %@"
+ "[%{public}@] Network Repair: Disarming fail-safe (rollback)"
+ "[%{public}@] Network Repair: Fail-safe armed"
+ "[%{public}@] Network Repair: Failed to read parts list from root endpoint"
+ "[%{public}@] Network Repair: Found NetworkCommissioning cluster at endpoint %@ with FeatureMap 0x%lx"
+ "[%{public}@] Network Repair: No Matter device available"
+ "[%{public}@] Network Repair: No NetworkCommissioning cluster found for interface type 0x%lx"
+ "[%{public}@] Network Repair: Sending CommissioningComplete"
+ "[%{public}@] Thread Repair: AddOrUpdateThreadNetwork failed: %@"
+ "[%{public}@] Thread Repair: AddOrUpdateThreadNetwork returned status: %@"
+ "[%{public}@] Thread Repair: ConnectNetwork failed: %@"
+ "[%{public}@] Thread Repair: ConnectNetwork returned status: %@"
+ "[%{public}@] Thread Repair: ConnectNetwork with Extended PAN ID: %@"
+ "[%{public}@] Thread Repair: Device already on home's Thread network"
+ "[%{public}@] Thread Repair: Extended PAN ID mismatch, updating credentials"
+ "[%{public}@] Thread Repair: Failed to extract Extended PAN ID from dataset"
+ "[%{public}@] Thread Repair: Feature not enabled"
+ "[%{public}@] Thread Repair: Found Thread network with Extended PAN ID: %@"
+ "[%{public}@] Thread Repair: No Thread network on device, adding home network"
+ "[%{public}@] Thread Repair: No operational dataset provided, skipping repair"
+ "[%{public}@] Thread Repair: Successfully connected to Thread network"
+ "[%{public}@] Thread Repair: Successfully updated Thread network"
+ "[%{public}@] Topology is nil"
+ "[%{public}@] WiFi Repair: AddOrUpdateWiFiNetwork failed for '%@': %@"
+ "[%{public}@] WiFi Repair: Added network '%@'"
+ "[%{public}@] WiFi Repair: Adding %lu missing network(s)"
+ "[%{public}@] WiFi Repair: All preferred networks already on device, reordering"
+ "[%{public}@] WiFi Repair: At capacity (%lu/%@), removing '%@' to add '%@'"
+ "[%{public}@] WiFi Repair: At capacity (%lu/%@), updating %lu existing home network(s)"
+ "[%{public}@] WiFi Repair: Capacity limited - adding %lu of %lu missing networks"
+ "[%{public}@] WiFi Repair: Device WiFi capacity: %lu current, %@ max"
+ "[%{public}@] WiFi Repair: Device at capacity and no primary network available"
+ "[%{public}@] WiFi Repair: Failed to add networks: %@"
+ "[%{public}@] WiFi Repair: Failed to read MaxNetworks attribute"
+ "[%{public}@] WiFi Repair: Failed to remove '%@': %@"
+ "[%{public}@] WiFi Repair: Feature not enabled"
+ "[%{public}@] WiFi Repair: Found %lu network(s) on device: %@"
+ "[%{public}@] WiFi Repair: No preferred networks provided, skipping repair"
+ "[%{public}@] WiFi Repair: Reading device network capacity and current networks"
+ "[%{public}@] WiFi Repair: ReorderNetwork failed for '%@': %@"
+ "[%{public}@] WiFi Repair: Reordering had %lu failures, continuing"
+ "maxNetworks"
+ "networkingStatus"
+ "readAttributeDoorStateWithCompletion:"
+ "v24@?0@\"MTRNetworkCommissioningClusterConnectNetworkResponseParams\"8@\"NSError\"16"
+ "v24@?0@\"MTRNetworkCommissioningClusterNetworkConfigResponseParams\"8@\"NSError\"16"
+ "\xf0\xd2\xf0\xf0\xf0A\xf0\xb1"
- "\xf0\xd2\xf0\xf0\xf0A\xf0\x81"
```
