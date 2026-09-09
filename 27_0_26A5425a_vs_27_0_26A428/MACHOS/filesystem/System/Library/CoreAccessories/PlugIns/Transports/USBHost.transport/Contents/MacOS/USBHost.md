## USBHost

> `/System/Library/CoreAccessories/PlugIns/Transports/USBHost.transport/Contents/MacOS/USBHost`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__objc_data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

 1216.0.0.0.0
-  __TEXT.__text: 0x19660
+  __TEXT.__text: 0x191dc
   __TEXT.__objc_methlist: 0x1328
   __TEXT.__const: 0x170
   __TEXT.__oslogstring: 0x2dba
-  __TEXT.__cstring: 0x19f0
+  __TEXT.__cstring: 0x1aa1
   __TEXT.__gcc_except_tab: 0x37c
-  __TEXT.__unwind_info: 0x508
+  __TEXT.__unwind_info: 0x750
   __TEXT.__objc_stubs: 0x22c0
   __TEXT.__auth_stubs: 0x840
   __TEXT.__objc_classname: 0x215
   __TEXT.__objc_methname: 0x3a49
   __TEXT.__objc_methtype: 0x9cf
-  __DATA_CONST.__const: 0x708
+  __DATA_CONST.__const: 0x768
   __DATA_CONST.__objc_classlist: 0x68
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_superrefs: 0x60
   __DATA_CONST.__got: 0x250
   __AUTH_CONST.__const: 0x480
-  __AUTH_CONST.__cfstring: 0x14e0
+  __AUTH_CONST.__cfstring: 0x15a0
   __AUTH_CONST.__objc_const: 0x2760
   __AUTH_CONST.__auth_got: 0x430
   __AUTH.__objc_data: 0x320
   __DATA.__objc_ivar: 0x254
   __DATA.__data: 0x300
-  __DATA.__bss: 0xb0
+  __DATA.__bss: 0xa8
   __DATA_DIRTY.__objc_data: 0xf0
   __DATA_DIRTY.__data: 0x30
   __DATA_DIRTY.__bss: 0x28

   - /System/Library/PrivateFrameworks/CoreAccessories.framework/Versions/A/CoreAccessories
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 616
-  Symbols:   1568
-  CStrings:  1244
+  Functions: 615
+  Symbols:   1579
+  CStrings:  1250
 
Symbols:
+ _ACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _ACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _ACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _ACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _ACCUserDefaultsKey_PlatformIDOverride
+ _ACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _kCFACCUserDefaultsKey_TestCreateBLEPairingOnInductive
- systemInfo_isDeveloperBuild.developerBuild
Functions:
~ _OUTLINED_FUNCTION_3 : 28 -> 16
~ _acc_userNotifications_generateIdentifier : 96 -> 84
~ _acc_userNotifications_accessoryNotSupported : 248 -> 236
~ _acc_userNotifications_chargingNotSupported : 304 -> 292
~ _acc_userNotifications_unlockToUseAccessories : 332 -> 320
~ _acc_userNotifications_disabledHSAID : 236 -> 224
~ +[ACCUserDefaults sharedDefaults] : 68 -> 56
~ ___33+[ACCUserDefaults sharedDefaults]_block_invoke : 76 -> 64
~ +[ACCUserDefaults sharedDefaultsIapd] : 68 -> 56
~ ___37+[ACCUserDefaults sharedDefaultsIapd]_block_invoke : 76 -> 64
~ +[ACCUserDefaults sharedDefaultsLogging] : 68 -> 56
~ ___40+[ACCUserDefaults sharedDefaultsLogging]_block_invoke : 76 -> 64
~ _acc_userDefaults_setArrayForKey : 96 -> 84
~ _acc_userDefaults_setIntegerForKey : 96 -> 84
~ _acc_userDefaults_setDoubleForKey : 96 -> 84
~ _logObjectForModule : 132 -> 120
~ -[AccessoryUSBBillboardDeviceListener .cxx_destruct] : 68 -> 56
~ -[AccessoryUSBBillboardDevice .cxx_destruct] : 68 -> 56
~ +[AccessoryUSBBillboardDeviceManager sharedManager] : 160 -> 148
~ ___51+[AccessoryUSBBillboardDeviceManager sharedManager]_block_invoke : 60 -> 48
~ -[AccessoryUSBBillboardDeviceManager .cxx_destruct] : 80 -> 68
- _OUTLINED_FUNCTION_1
~ _OUTLINED_FUNCTION_5 : 32 -> 20
~ ___copy_helper_block_e8_32s40w : 68 -> 56
~ ___destroy_helper_block_e8_32s40w : 60 -> 48
~ __46-[AccessoryTransportPluginUSBHost startPlugin]_block_invoke.24 : 164 -> 152
~ -[AccessoryTransportPluginUSBHost tearDownIOKit] : 112 -> 100
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ __50-[AccessoryTransportPluginUSBHost serviceRemoved:]_block_invoke.73 : 68 -> 56
~ ___copy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___destroy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___83-[AccessoryTransportPluginUSBHost _handleOpenSocketFromAccessoryToAppNotification:]_block_invoke : 104 -> 92
~ ___83-[AccessoryTransportPluginUSBHost _handleOpenSocketFromAppToAccessoryNotification:]_block_invoke : 104 -> 92
~ ___copy_helper_block_e8_32s40s48r56r64r72r : 128 -> 116
~ ___destroy_helper_block_e8_32s40s48r56r64r72r : 108 -> 96
~ __76-[AccessoryTransportPluginUSBHost unlockUSBHostInterfacesForConnectionUUID:]_block_invoke.89 : 76 -> 64
~ ___74-[AccessoryTransportPluginUSBHost lockUSBHostInterfacesForConnectionUUID:]_block_invoke : 120 -> 108
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ -[AccessoryTransportPluginUSBHost tearDownIOKitVIDPID] : 112 -> 100
~ __54-[AccessoryTransportPluginUSBHost VIDPIDServiceAdded:]_block_invoke.98 : 76 -> 64
~ ___87-[AccessoryTransportPluginUSBHost sendOutgoingData:forEndpointWithUUID:connectionUUID:]_block_invoke : 144 -> 132
~ ___copy_helper_block_e8_32s40s48s56r64r : 104 -> 92
~ ___destroy_helper_block_e8_32s40s48s56r64r : 92 -> 80
~ __87-[AccessoryTransportPluginUSBHost sendOutgoingData:forEndpointWithUUID:connectionUUID:]_block_invoke.113 : 216 -> 204
~ ___copy_helper_block_e8_32s40s48s56r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ -[AccessoryTransportPluginUSBHost .cxx_destruct] : 224 -> 212
~ _OUTLINED_FUNCTION_1 : 88 -> 76
~ _OUTLINED_FUNCTION_5 : 28 -> 16
~ _OUTLINED_FUNCTION_6 : 24 -> 12
~ _systemInfo_isDeveloperBuild : 56 -> 52
~ ___systemInfo_isDeveloperBuild_block_invoke : 16 -> 4
~ _logObjectForModule : 132 -> 120
~ -[IAPDataBuffer parentiAPInterface] : 44 -> 32
~ -[AccessoryIAPInterface .cxx_destruct] : 140 -> 128
~ _OUTLINED_FUNCTION_5 : 28 -> 16
~ -[iAP2EASession description] : 152 -> 140
~ -[iAP2EASession .cxx_destruct] : 68 -> 56
~ -[EAUSBBuffer moveWritePtr:] : 52 -> 48
~ -[EAUSBBuffer eaInterface] : 44 -> 32
~ __StaticSockCallback : 152 -> 140
~ -[AccessoryEAInterface _enqueueWriteBuffer:] : 92 -> 80
~ -[AccessoryEAInterface _dequeueWriteBuffer] : 112 -> 100
~ -[AccessoryEAInterface _dequeueReadBuffer] : 112 -> 100
~ -[AccessoryEAInterface _writeUSBData:] : 316 -> 304
~ __StaticUSBWriteComplete : 116 -> 104
~ -[AccessoryEAInterface _clearPipeStall:] : 132 -> 120
~ -[AccessoryEAInterface _writeComplete:writeLength:] : 148 -> 136
~ -[AccessoryEAInterface _readSessionDataFromUSB] : 416 -> 404
~ __StaticUSBReadComplete : 116 -> 104
~ -[AccessoryEAInterface _readComplete:readLength:] : 172 -> 160
~ +[AccessoryEAInterface findNativeEAInterfacesForRegistryID:] : 1636 -> 1624
~ -[AccessoryEAInterface .cxx_destruct] : 152 -> 140
~ _OUTLINED_FUNCTION_7 : 28 -> 16
~ -[ACCUserNotificationManager dismissNotification:] : 492 -> 480
~ -[ACCUserNotificationManager userNotificationWithUUID:] : 412 -> 400
~ -[ACCUserNotificationManager removeUserNotification:] : 252 -> 240
~ -[ACCUserNotificationManager updateNotification:] : 240 -> 228
~ -[ACCUserNotificationManager userNotificationCenter:didActivateNotification:] : 356 -> 344
~ -[ACCUserNotificationManager userNotificationCenter:didDismissAlert:] : 316 -> 304
~ +[ACCUserNotificationManager sharedManager] : 160 -> 148
~ ___43+[ACCUserNotificationManager sharedManager]_block_invoke : 60 -> 48
~ -[ACCUserNotificationManager .cxx_destruct] : 104 -> 92
~ _platform_systemInfo_resetDeviceUUID : 116 -> 104
~ -[AccessoryUSBCDCInterface description] : 152 -> 140
~ -[AccessoryUSBCDCInterface .cxx_destruct] : 104 -> 92
~ _init_logging : 60 -> 48
~ -[ACCUserNotification createBackingUserNotification] : 1540 -> 1528
~ -[ACCUserNotification updateBackingUserNotification] : 72 -> 60
~ -[ACCUserNotification .cxx_destruct] : 224 -> 212
CStrings:
+ "BLEPairingConfigRequestDelayMs"
+ "BLEPairingDisableOOBPPlusFlow"
+ "BLEPairingDontEarlyInfoAsDeviceUID"
+ "BLEPairingIgnoreZeroEarlyInfo"
+ "PlatformIDOverride"
+ "TestCreateBLEPairingOnInductive"
```
