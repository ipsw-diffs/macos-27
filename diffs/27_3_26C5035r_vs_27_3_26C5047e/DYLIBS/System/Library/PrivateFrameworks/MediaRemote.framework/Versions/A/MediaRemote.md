## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/Versions/A/MediaRemote`

```diff

-4026.300.11.0.0
-  __TEXT.__text: 0x310a84
-  __TEXT.__objc_methlist: 0x2ba5c
+4026.340.18.1.0
+  __TEXT.__text: 0x313c70
+  __TEXT.__objc_methlist: 0x2bc04
   __TEXT.__const: 0x6c8
-  __TEXT.__cstring: 0x2c6b9
-  __TEXT.__oslogstring: 0xd42d
-  __TEXT.__gcc_except_tab: 0x5940
+  __TEXT.__cstring: 0x2c886
+  __TEXT.__oslogstring: 0xd653
+  __TEXT.__gcc_except_tab: 0x594c
   __TEXT.__dlopen_cstrs: 0x40b
   __TEXT.__ustring: 0x7b8
-  __TEXT.__unwind_info: 0xe358
+  __TEXT.__unwind_info: 0xe430
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x4c10
-  __DATA_CONST.__objc_classlist: 0x11c0
+  __DATA_CONST.__objc_classlist: 0x11c8
   __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0x228
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf1f0
+  __DATA_CONST.__objc_selrefs: 0xf2b0
   __DATA_CONST.__objc_protorefs: 0x80
-  __DATA_CONST.__objc_superrefs: 0xff0
+  __DATA_CONST.__objc_superrefs: 0xff8
   __DATA_CONST.__objc_arraydata: 0x260
   __DATA_CONST.__got: 0x1428
-  __AUTH_CONST.__const: 0xa4b0
-  __AUTH_CONST.__cfstring: 0x24060
-  __AUTH_CONST.__objc_const: 0x468e0
+  __AUTH_CONST.__const: 0xa5d0
+  __AUTH_CONST.__cfstring: 0x24180
+  __AUTH_CONST.__objc_const: 0x46be0
   __AUTH_CONST.__objc_intobj: 0x510
   __AUTH_CONST.__objc_arrayobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0xaa8
-  __AUTH.__objc_data: 0x5d20
-  __DATA.__objc_ivar: 0x331c
+  __AUTH_CONST.__auth_got: 0xab0
+  __AUTH.__objc_data: 0x5d70
+  __DATA.__objc_ivar: 0x3350
   __DATA.__data: 0x1a08
   __DATA.__bss: 0x8b8
   __DATA.__common: 0x8

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 20641
-  Symbols:   34469
-  CStrings:  6533
+  Functions: 20701
+  Symbols:   34559
+  CStrings:  6553
 
Symbols:
+ +[_MRDeviceInfoMessageProtobuf homeKitUserIdentifiersType]
+ -[MRClient representsSystemBooksApplication]
+ -[MRClient representsSystemClassicalRoomApplication]
+ -[MRClient representsSystemMediaApplication]
+ -[MRClient representsSystemPodcastsApplication]
+ -[MRDeviceInfo deviceInfoByRedactingHomeKitUserIdentifiers]
+ -[MRDeviceInfo homeKitUserIdentifiers]
+ -[MRDeviceInfo setHomeKitUserIdentifiers:]
+ -[MRNowPlayingControllerHelper controller:deviceLastPlayingDateDidChange:]
+ -[MRNowPlayingControllerHelper deviceLastPlayingDateDidChange]
+ -[MRNowPlayingControllerHelper setDeviceLastPlayingDateDidChange:]
+ -[MRSystemEndpointHomeKitUserObserver .cxx_destruct]
+ -[MRSystemEndpointHomeKitUserObserver _handleActiveSystemEndpointDidChange:]
+ -[MRSystemEndpointHomeKitUserObserver _handleEndpointDeviceInfoDidChange:]
+ -[MRSystemEndpointHomeKitUserObserver _handleEndpointDidDisconnect:]
+ -[MRSystemEndpointHomeKitUserObserver _onQueue_reload]
+ -[MRSystemEndpointHomeKitUserObserver _onQueue_scheduleRetry]
+ -[MRSystemEndpointHomeKitUserObserver _onQueue_updateHomeKitUserIdentifiers:]
+ -[MRSystemEndpointHomeKitUserObserver begin]
+ -[MRSystemEndpointHomeKitUserObserver dealloc]
+ -[MRSystemEndpointHomeKitUserObserver delegate]
+ -[MRSystemEndpointHomeKitUserObserver end]
+ -[MRSystemEndpointHomeKitUserObserver homeKitUserIdentifiers]
+ -[MRSystemEndpointHomeKitUserObserver initWithDelegate:queue:]
+ -[MRSystemEndpointHomeKitUserObserver setDelegate:]
+ -[MRUserSettings resetUserSelectedEndpointOnLocalPlayback]
+ -[MRUserSettings syncHomeKitUser]
+ -[MRV2NowPlayingController _notifyDelegateOfUpdatedDeviceLastPlayingDate:]
+ -[MRV2NowPlayingController _requestDeviceLastPlayingDateForPlayerPath:queue:completion:]
+ -[MRV2NowPlayingController lastKnownPlaybackState]
+ -[MRV2NowPlayingController setLastKnownPlaybackState:]
+ -[_MRDeviceInfoMessageProtobuf addHomeKitUserIdentifiers:]
+ -[_MRDeviceInfoMessageProtobuf clearHomeKitUserIdentifiers]
+ -[_MRDeviceInfoMessageProtobuf homeKitUserIdentifiersAtIndex:]
+ -[_MRDeviceInfoMessageProtobuf homeKitUserIdentifiersCount]
+ -[_MRDeviceInfoMessageProtobuf homeKitUserIdentifiers]
+ -[_MRDeviceInfoMessageProtobuf setHomeKitUserIdentifiers:]
+ GCC_except_table172
+ GCC_except_table218
+ GCC_except_table219
+ GCC_except_table77
+ _OBJC_CLASS_$_MRSystemEndpointHomeKitUserObserver
+ _OBJC_IVAR_$_MRDeviceInfo._homeKitUserIdentifiers
+ _OBJC_IVAR_$_MRNowPlayingControllerHelper._deviceLastPlayingDateDidChange
+ _OBJC_IVAR_$_MRSystemEndpointHomeKitUserObserver._delegate
+ _OBJC_IVAR_$_MRSystemEndpointHomeKitUserObserver._delegateQueue
+ _OBJC_IVAR_$_MRSystemEndpointHomeKitUserObserver._endpoint
+ _OBJC_IVAR_$_MRSystemEndpointHomeKitUserObserver._generation
+ _OBJC_IVAR_$_MRSystemEndpointHomeKitUserObserver._homeKitUserIdentifiers
+ _OBJC_IVAR_$_MRSystemEndpointHomeKitUserObserver._lock
+ _OBJC_IVAR_$_MRSystemEndpointHomeKitUserObserver._queue
+ _OBJC_IVAR_$_MRSystemEndpointHomeKitUserObserver._retryAttempt
+ _OBJC_IVAR_$_MRSystemEndpointHomeKitUserObserver._running
+ _OBJC_IVAR_$_MRV2NowPlayingController._lastKnownPlaybackState
+ _OBJC_IVAR_$__MRDeviceInfoMessageProtobuf._homeKitUserIdentifiers
+ _OBJC_METACLASS_$_MRSystemEndpointHomeKitUserObserver
+ __OBJC_$_INSTANCE_METHODS_MRSystemEndpointHomeKitUserObserver
+ __OBJC_$_INSTANCE_VARIABLES_MRSystemEndpointHomeKitUserObserver
+ __OBJC_$_PROP_LIST_MRSystemEndpointHomeKitUserObserver
+ __OBJC_CLASS_RO_$_MRSystemEndpointHomeKitUserObserver
+ __OBJC_METACLASS_RO_$_MRSystemEndpointHomeKitUserObserver
+ ___42-[MRSystemEndpointHomeKitUserObserver end]_block_invoke
+ ___44-[MRSystemEndpointHomeKitUserObserver begin]_block_invoke
+ ___54-[MRSystemEndpointHomeKitUserObserver _onQueue_reload]_block_invoke
+ ___54-[MRSystemEndpointHomeKitUserObserver _onQueue_reload]_block_invoke_2
+ ___61-[MRSystemEndpointHomeKitUserObserver _onQueue_scheduleRetry]_block_invoke
+ ___68-[MRSystemEndpointHomeKitUserObserver _handleEndpointDidDisconnect:]_block_invoke
+ ___68-[MRV2NowPlayingController _handlePlaybackStateChangedNotification:]_block_invoke_2
+ ___68-[MRV2NowPlayingController _handlePlaybackStateChangedNotification:]_block_invoke_3
+ ___74-[MRSystemEndpointHomeKitUserObserver _handleEndpointDeviceInfoDidChange:]_block_invoke
+ ___76-[MRSystemEndpointHomeKitUserObserver _handleActiveSystemEndpointDidChange:]_block_invoke
+ ___77-[MRSystemEndpointHomeKitUserObserver _onQueue_updateHomeKitUserIdentifiers:]_block_invoke
+ ___88-[MRV2NowPlayingController _requestDeviceLastPlayingDateForPlayerPath:queue:completion:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e28_v24?0"NSDate"8"NSError"16l
+ ___block_descriptor_48_e8_32s_e34_v24?0"MRAVEndpoint"8"NSError"16l
+ ___block_descriptor_56_e8_32s40s_e17_v16?0"NSError"8l
+ ___block_descriptor_64_e8_32s40s48s_e5_v8?0l
+ _exp2
+ _objc_msgSend$_onQueue_reload
+ _objc_msgSend$_onQueue_scheduleRetry
+ _objc_msgSend$_onQueue_updateHomeKitUserIdentifiers:
+ _objc_msgSend$_requestDeviceLastPlayingDateForPlayerPath:queue:completion:
+ _objc_msgSend$addHomeKitUserIdentifiers:
+ _objc_msgSend$clearHomeKitUserIdentifiers
+ _objc_msgSend$contents
+ _objc_msgSend$dataByteSize
+ _objc_msgSend$deviceInfoByRedactingHomeKitUserIdentifiers
+ _objc_msgSend$deviceLastPlayingDateDidChange
+ _objc_msgSend$homeKitUserIdentifiersAtIndex:
+ _objc_msgSend$homeKitUserIdentifiersCount
+ _objc_msgSend$lastKnownPlaybackState
+ _objc_msgSend$requestDeviceLastPlayingDateOnQueue:completion:
+ _objc_msgSend$setDeviceLastPlayingDateDidChange:
+ _objc_msgSend$setHomeKitUserIdentifiers:
+ _objc_msgSend$setLastKnownPlaybackState:
+ _objc_msgSend$startOffset
+ _objc_msgSend$systemEndpointHomeKitUserObserver:homeKitUserIdentifiersDidChange:
+ _objc_msgSend$variableFramesInPacket
- -[MRAVDistantRoutingDiscoverySession configurationWithCompletion:]
- GCC_except_table143
- GCC_except_table144
- GCC_except_table209
- GCC_except_table210
- GCC_except_table212
- GCC_except_table213
- GCC_except_table80
CStrings:
+ "05AC:110B"
+ "MRAVEndpoint.addOutputDevicesWithUIDs"
+ "MRAVEndpoint.moveOutputDevicesWithUIDs"
+ "MRAudioDataBlock.m"
+ "UIDs=(%@), group=%@"
+ "[MRSystemEndpointHomeKitUserObserver] Failed to connect to system endpoint %{public}@: %{public}@"
+ "[MRSystemEndpointHomeKitUserObserver] Failed to resolve system endpoint: %{public}@"
+ "[MRSystemEndpointHomeKitUserObserver] HomeKit user identifiers changed: %{public}@"
+ "[MRSystemEndpointHomeKitUserObserver] Retrying in %.0fs"
+ "[MRSystemEndpointHomeKitUserObserver] System endpoint changed, reloading"
+ "[MRSystemEndpointHomeKitUserObserver] System endpoint disconnected: %{public}@"
+ "addOutputDevicesWithUIDs.xpcInterface"
+ "com.apple.MediaRemote.MRSystemEndpointHomeKitUserObserver"
+ "groupedDeviceUID"
+ "homeKitUserIdentifiers"
+ "homepod.2.and.homepod.mini.2.and.appletv.fill"
+ "invalid buffer size for decoding voice input message (%lu > (%lu * %lu))"
+ "moveOutputDevicesWithUIDs.xpcInterface"
+ "packet descriptions exceed maximum packet capacity (%lu > %lu)"
+ "resetUserSelectedEndpointOnLocalPlayback"
+ "sync_homekit_user"
- "76,4363"
```
