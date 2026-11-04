## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/Versions/A/MediaRemote`

```diff

-4026.240.3.0.0
-  __TEXT.__text: 0x30fd4c
-  __TEXT.__objc_methlist: 0x2b9a4
-  __TEXT.__const: 0x678
-  __TEXT.__cstring: 0x2c65f
+4026.300.11.0.0
+  __TEXT.__text: 0x310a84
+  __TEXT.__objc_methlist: 0x2ba5c
+  __TEXT.__const: 0x6c8
+  __TEXT.__cstring: 0x2c6b9
   __TEXT.__oslogstring: 0xd42d
-  __TEXT.__gcc_except_tab: 0x5934
+  __TEXT.__gcc_except_tab: 0x5940
   __TEXT.__dlopen_cstrs: 0x40b
   __TEXT.__ustring: 0x7b8
-  __TEXT.__unwind_info: 0xe300
+  __TEXT.__unwind_info: 0xe358
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0x228
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf1a8
+  __DATA_CONST.__objc_selrefs: 0xf1f0
   __DATA_CONST.__objc_protorefs: 0x80
   __DATA_CONST.__objc_superrefs: 0xff0
   __DATA_CONST.__objc_arraydata: 0x260
   __DATA_CONST.__got: 0x1428
-  __AUTH_CONST.__const: 0xa460
-  __AUTH_CONST.__cfstring: 0x24020
-  __AUTH_CONST.__objc_const: 0x467c8
+  __AUTH_CONST.__const: 0xa4b0
+  __AUTH_CONST.__cfstring: 0x24060
+  __AUTH_CONST.__objc_const: 0x468e0
   __AUTH_CONST.__objc_intobj: 0x510
   __AUTH_CONST.__objc_arrayobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0xa90
+  __AUTH_CONST.__auth_got: 0xaa8
   __AUTH.__objc_data: 0x5d20
-  __DATA.__objc_ivar: 0x3308
+  __DATA.__objc_ivar: 0x331c
   __DATA.__data: 0x1a08
-  __DATA.__bss: 0x8a8
+  __DATA.__bss: 0x8b8
   __DATA.__common: 0x8
   __DATA_DIRTY.__objc_data: 0x5460
   __DATA_DIRTY.__data: 0x88

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 20621
-  Symbols:   34429
-  CStrings:  6529
+  Functions: 20641
+  Symbols:   34469
+  CStrings:  6533
 
Symbols:
+ -[MRDestinationResolver endpointChangesRegistration]
+ -[MRDestinationResolver setEndpointChangesRegistration:]
+ -[MRDeviceInfo airPlayBidirectionalAudioSessionID]
+ -[MRDeviceInfo airPlayServerConnectionInfo]
+ -[MRDeviceInfo hasAirPlayBidirectionalAudioSessionID]
+ -[MRDeviceInfo setAirPlayBidirectionalAudioSessionID:]
+ -[MRDeviceInfo setAirPlayServerConnectionInfo:]
+ -[MRDeviceInfo setHasAirPlayBidirectionalAudioSessionID:]
+ -[_MRDeviceInfoMessageProtobuf airPlayBidirectionalAudioSessionID]
+ -[_MRDeviceInfoMessageProtobuf airPlayServerConnectionInfo]
+ -[_MRDeviceInfoMessageProtobuf hasAirPlayBidirectionalAudioSessionID]
+ -[_MRDeviceInfoMessageProtobuf hasAirPlayServerConnectionInfo]
+ -[_MRDeviceInfoMessageProtobuf setAirPlayBidirectionalAudioSessionID:]
+ -[_MRDeviceInfoMessageProtobuf setAirPlayServerConnectionInfo:]
+ -[_MRDeviceInfoMessageProtobuf setHasAirPlayBidirectionalAudioSessionID:]
+ _MGIsDeviceOneOfType
+ _MRMediaRemoteAirPlayReceiverCopyServerConnectionInfo
+ _MRMediaRemoteAirPlayReceiverGetBidirectionalAudioSessionID
+ _OBJC_IVAR_$_MRDestinationResolver._endpointChangesRegistration
+ _OBJC_IVAR_$_MRDeviceInfo._airPlayBidirectionalAudioSessionID
+ _OBJC_IVAR_$_MRDeviceInfo._airPlayServerConnectionInfo
+ _OBJC_IVAR_$_MRDeviceInfo._hasAirPlayBidirectionalAudioSessionID
+ _OBJC_IVAR_$_MRV1NowPlayingController._helper
+ _OBJC_IVAR_$__MRDeviceInfoMessageProtobuf._airPlayBidirectionalAudioSessionID
+ _OBJC_IVAR_$__MRDeviceInfoMessageProtobuf._airPlayServerConnectionInfo
+ ___46-[MRSharedSettings supportAgentLiveActivities]_block_invoke
+ ___70-[MRDestinationResolver registerForEndpointChangesForOutputDeviceUID:]_block_invoke_2
+ ___block_descriptor_48_e8_32w_e28_v16?0^{__MRAVEndpointRef=}8l
+ _objc_getProperty
+ _objc_msgSend$airPlayBidirectionalAudioSessionID
+ _objc_msgSend$airPlayServerConnectionInfo
+ _objc_msgSend$endpointChangesRegistration
+ _objc_msgSend$hasAirPlayBidirectionalAudioSessionID
+ _objc_msgSend$playbackRateDidChange
+ _objc_msgSend$repeatModeDidChange
+ _objc_msgSend$setAirPlayBidirectionalAudioSessionID:
+ _objc_msgSend$setAirPlayServerConnectionInfo:
+ _objc_msgSend$setEndpointChangesRegistration:
+ _objc_msgSend$setHasAirPlayBidirectionalAudioSessionID:
+ _objc_msgSend$shuffleModeDidChange
+ _objc_msgSend$supportNowPlayingDrivenAgent
+ _objc_setProperty_atomic_copy
+ _supportAgentLiveActivities.__supports
+ _supportAgentLiveActivities.onceToken
- GCC_except_table160
- _OBJC_IVAR_$_MRSharedSettings._supportAgentLiveActivities
- _OBJC_IVAR_$_MRV1NowPlayingController.helper
- __OBJC_$_INSTANCE_VARIABLES_MRSharedSettings
CStrings:
+ "LiveActivitiesQFA"
+ "MenuBar"
+ "airPlayBidirectionalAudioSessionID"
+ "airPlayServerConnectionInfo"
```
