## MediaExperience

> `/System/Library/PrivateFrameworks/MediaExperience.framework/Versions/A/MediaExperience`

```diff

 360.75.1.0.0
-  __TEXT.__text: 0x979d4
+  __TEXT.__text: 0x98c74
   __TEXT.__delay_helper: 0xdc
   __TEXT.__lazy_helpers: 0xa8
-  __TEXT.__objc_methlist: 0x1e1c
-  __TEXT.__const: 0x1e8
-  __TEXT.__cstring: 0x11d30
-  __TEXT.__oslogstring: 0xf6e0
-  __TEXT.__gcc_except_tab: 0x1010
-  __TEXT.__dlopen_cstrs: 0x16e
-  __TEXT.__unwind_info: 0x1b00
+  __TEXT.__objc_methlist: 0x1e3c
+  __TEXT.__const: 0x1f8
+  __TEXT.__cstring: 0x11f96
+  __TEXT.__oslogstring: 0xfacb
+  __TEXT.__gcc_except_tab: 0x1068
+  __TEXT.__dlopen_cstrs: 0x1bc
+  __TEXT.__unwind_info: 0x1b30
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2738
+  __DATA_CONST.__const: 0x2750
   __DATA_CONST.__objc_classlist: 0xf8
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1348
+  __DATA_CONST.__objc_selrefs: 0x13c8
   __DATA_CONST.__objc_superrefs: 0xd8
   __DATA_CONST.__objc_arraydata: 0x70
-  __DATA_CONST.__got: 0x7d8
-  __AUTH_CONST.__const: 0x23c0
-  __AUTH_CONST.__cfstring: 0xad80
-  __AUTH_CONST.__objc_const: 0x3308
+  __DATA_CONST.__got: 0x7f0
+  __AUTH_CONST.__const: 0x2410
+  __AUTH_CONST.__cfstring: 0xade0
+  __AUTH_CONST.__objc_const: 0x3348
   __AUTH_CONST.__lazy_load_got: 0x8
   __AUTH_CONST.__objc_dictobj: 0x118
   __AUTH_CONST.__objc_intobj: 0xc0
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x488
-  __DATA.__objc_ivar: 0x2b4
+  __DATA.__objc_ivar: 0x2bc
   __DATA.__data: 0x3b4
-  __DATA.__bss: 0x3e8
+  __DATA.__bss: 0x420
   __DATA.__common: 0x1d0
   __DATA_DIRTY.__objc_data: 0x528
   __DATA_DIRTY.__bss: 0x6fc

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2756
-  Symbols:   5217
-  CStrings:  2904
+  Functions: 2776
+  Symbols:   5273
+  CStrings:  2931
 
Symbols:
+ -[MXSessionManager initializeDisplaySyncClient]
+ -[MXSessionManager sychronizeDisplay:displaySyncStarted:]
+ -[MXSessionManager teardownDisplaySyncClient]
+ GCC_except_table39
+ GCC_except_table61
+ MX_FeatureFlags_IsDisplaySynchronizationOnMacEnabled
+ MX_FeatureFlags_IsDisplaySynchronizationOnMacEnabled.onceToken
+ MX_FeatureFlags_IsDisplaySynchronizationOnMacEnabled.sIsDisplaySynchronizationOnMacEnabled
+ OBJC_IVAR_$_MXSessionManager.displaySyncClient
+ OBJC_IVAR_$_MXSessionManager.sessionControl
+ SkyLightLibraryCore.frameworkLibrary
+ _AudioObjectHasProperty
+ _MX_FeatureFlags_IsDisplaySynchronizationOnMacEnabled
+ _OBJC_CLASS_$_TSClockManager
+ _OBJC_CLASS_$_TSMSGService
+ _OUTLINED_FUNCTION_49
+ _OUTLINED_FUNCTION_50
+ _OUTLINED_FUNCTION_51
+ _OUTLINED_FUNCTION_52
+ _OUTLINED_FUNCTION_53
+ _OUTLINED_FUNCTION_54
+ _OUTLINED_FUNCTION_55
+ _SkyLightLibrary
+ _SkyLightLibraryCore
+ _TSNullClockIdentifier
+ __47-[MXSessionManager initializeDisplaySyncClient]_block_invoke
+ ___47-[MXSessionManager initializeDisplaySyncClient]_block_invoke
+ ___MX_FeatureFlags_IsDisplaySynchronizationOnMacEnabled_block_invoke
+ ___SkyLightLibraryCore_block_invoke
+ ___block_descriptor_40_e8_32o_e25_v24?08"NSDictionary"16l
+ ___getSLSDisplaySyncSessionClientClass_block_invoke
+ ___getkSLSDisplaySyncSessionNotificationInitializedSymbolLoc_block_invoke
+ ___getkSLSDisplaySyncSessionNotificationStartedSymbolLoc_block_invoke
+ ___getkSLSDisplaySyncSessionUUIDSymbolLoc_block_invoke
+ __getSLSDisplaySyncSessionClientClass_block_invoke
+ _audit_stringSkyLight
+ _objc_msgSend$anyObject
+ _objc_msgSend$displaySyncSessionControl
+ _objc_msgSend$getFollowStatusForSession:withError:
+ _objc_msgSend$getMSGClockInfoForDescriptor:nominalSyncDuration:error:
+ _objc_msgSend$initDisplaySyncSessionClient:
+ _objc_msgSend$initializeDisplaySyncClient
+ _objc_msgSend$objectForKeyedSubscript:
+ _objc_msgSend$registerForNotificationsWithQueue:block:
+ _objc_msgSend$sharedMSGService
+ _objc_msgSend$sychronizeDisplay:displaySyncStarted:
+ _objc_msgSend$syncDescriptors
+ _objc_msgSend$syncID
+ _objc_msgSend$teardownDisplaySyncClient
+ _objc_msgSend$terminateConnection:
+ _objc_msgSend$timeSyncAudioClockDeviceUIDForClockIdentifier:
+ _objc_msgSend$unregisterNotificationBlocks
+ getSLSDisplaySyncSessionClientClass.softClass
+ getkSLSDisplaySyncSessionNotificationInitializedSymbolLoc.ptr
+ getkSLSDisplaySyncSessionNotificationStartedSymbolLoc.ptr
+ getkSLSDisplaySyncSessionUUIDSymbolLoc.ptr
CStrings:
+ "-MXSessionManager- %s: AudioObjectSetPropertyData on kAudioHardwarePropertyGlobalDefaultClockDevice with deviceID:%d and deviceUID:%{public}@ returned with err:%d"
+ "-MXSessionManager- %s: Error terminating SLSDisplaySyncSessionClient connection: %{public}@"
+ "-MXSessionManager- %s: Failed to create SyncSessionClient with err %{public}@"
+ "-MXSessionManager- %s: Property kAudioHardwarePropertyGlobalDefaultClockDevice is not supported"
+ "-MXSessionManager- %s: Received invalid TSClockIdentifier"
+ "-MXSessionManager- %s: Received notification that display synchronization has %{public}@"
+ "-MXSessionManager- %s: Successfully unsubscribed from Skylight notifications and terminated connection"
+ "-MXSessionManager- %s: Sucessfully set clockDeviceUID:%{public}@ %{public}@"
+ "-MXSessionManager- %s: Unable to create/destroy clock reference as syncDescriptors is nil"
+ "-MXSessionManager- %s: Unable to get MSG clockID with err: %{public}@"
+ "-MX_FeatureFlags- %s: MediaExperience/DisplaySynchronizationOnMac feature is %{public}@"
+ "-[MXSessionManager initializeDisplaySyncClient]"
+ "-[MXSessionManager initializeDisplaySyncClient]_block_invoke"
+ "-[MXSessionManager sychronizeDisplay:displaySyncStarted:]"
+ "-[MXSessionManager teardownDisplaySyncClient]"
+ "/System/Library/PrivateFrameworks/SkyLight.framework/Contents/MacOS/SkyLight"
+ "15:46:10"
+ "DisplaySynchronizationOnMac"
+ "MX_FeatureFlags_IsDisplaySynchronizationOnMacEnabled_block_invoke"
+ "SLSDisplaySyncSessionClient"
+ "kSLSDisplaySyncSessionNotificationInitialized"
+ "kSLSDisplaySyncSessionNotificationStarted"
+ "kSLSDisplaySyncSessionUUID"
+ "nominalSyncDuration:%llu/%llu, and syncID:%d"
+ "softlink:o:path:/System/Library/PrivateFrameworks/SkyLight.framework/SkyLight"
+ "started"
+ "stopped"
+ "v24@?0@8@\"NSDictionary\"16"
- "18:01:47"
```
