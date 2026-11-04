## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/Versions/A/AirPlaySender`

```diff

-1005.13.1.0.0
-  __TEXT.__text: 0x1cec88
+1015.5.1.0.0
+  __TEXT.__text: 0x1cfbac
   __TEXT.__objc_methlist: 0x95c
-  __TEXT.__const: 0xd530
+  __TEXT.__const: 0xd550
   __TEXT.__gcc_except_tab: 0x64c
-  __TEXT.__cstring: 0x71e4c
+  __TEXT.__cstring: 0x720fa
   __TEXT.__dlopen_cstrs: 0x164
   __TEXT.__oslogstring: 0xb55
-  __TEXT.__unwind_info: 0x7290
+  __TEXT.__unwind_info: 0x72d0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb58
+  __DATA_CONST.__objc_selrefs: 0xb78
   __DATA_CONST.__objc_superrefs: 0x20
   __DATA_CONST.__objc_arraydata: 0x170
-  __DATA_CONST.__got: 0x1e08
-  __AUTH_CONST.__const: 0x72b0
-  __AUTH_CONST.__cfstring: 0x10660
+  __DATA_CONST.__got: 0x1e10
+  __AUTH_CONST.__const: 0x72c0
+  __AUTH_CONST.__cfstring: 0x10700
   __AUTH_CONST.__objc_const: 0xc58
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__objc_dictobj: 0x1b8

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 9108
-  Symbols:   7563
-  CStrings:  9269
+  Functions: 9127
+  Symbols:   7581
+  CStrings:  9281
 
Symbols:
+ GCC_except_table105
+ GCC_except_table106
+ GCC_except_table36
+ GCC_except_table38
+ GCC_except_table87
+ GCC_except_table88
+ GCC_except_table89
+ GCC_except_table90
+ GCC_except_table91
+ GCC_except_table92
+ GCC_except_table93
+ _APEndpointAddNowPlayingAppMetrics
+ _APEndpointFlushAndAddNowPlayingAppMetrics
+ _APEndpointShouldTrackNowPlayingApps
+ _APMetadataSourceBeginRecordingNowPlayingAppDurations
+ _APMetadataSourceFlushAndCopyNowPlayingAppDurations
+ _APMetadataSourceResetNowPlayingAppDurations
+ _APSAPAPExtensionConvertLoudnessInfoDictContentTypeToBBuf
+ _APSAPAPExtensionConvertLoudnessInfoDictLibraryLoudnessToBBuf
+ ___APMetadataSourceBeginRecordingNowPlayingAppDurations_block_invoke
+ ___APMetadataSourceFlushAndCopyNowPlayingAppDurations_block_invoke
+ ___APMetadataSourceResetNowPlayingAppDurations_block_invoke
+ _kAPEndpointDescriptionProperty_SupportsReceiverSideCALMLoudness
+ _kAPEndpointNowPlayingAppHistogramBounds
+ _kFigEndpointStreamProperty_SupportsReceiverSideCALMLoudness
+ _metadataSource_closeNowPlayingAppEntry
+ _objc_msgSend$bundleIdentifier
+ _objc_msgSend$isEqualToString:
+ _objc_msgSend$parentApplicationBundleIdentifier
+ _objc_msgSend$processIdentifier
- GCC_except_table21
- GCC_except_table27
- GCC_except_table77
- GCC_except_table78
- GCC_except_table79
- GCC_except_table80
- GCC_except_table81
- GCC_except_table82
- GCC_except_table83
- GCC_except_table98
- GCC_except_table99
- _apsession_requiresHKPairVerify
CStrings:
+ "1015.5.1"
+ "AirPlayCALMLoudness"
+ "OSStatus APMetadataSourceCreateWithNowPlayingAppPID(CFAllocatorRef, pid_t, APMetadataSourceRequestOptions, APMetadataSourceRef *)"
+ "SupportsReceiverSideCALMLoudness"
+ "[%{ptr}] Create: initial SupportsReceiverSideCALMLoudness=%d"
+ "[%{ptr}] NowPlaying app duration recording started, seed %@\n"
+ "[%{ptr}] NowPlaying app entry closed after %.3f s: %@\n"
+ "[%{ptr}] Receiver-side CALM loudness %s supported across all substreams."
+ "[%{ptr}] substream( %{ptr} support=%d )  SupportsReceiverSideCALMLoudness=%d"
+ "endpointAggregate_createAndStartMetadataSource"
+ "nowPlayingAppDurationHist"
+ "nowPlayingAppSwitchCount"
+ "void APMetadataSourceBeginRecordingNowPlayingAppDurations(APMetadataSourceRef, uint64_t)_block_invoke"
+ "void metadataSource_closeNowPlayingAppEntry(APMetadataSourceRef, uint64_t)"
- "1005.13.1"
- "OSStatus APMetadataSourceCreateWithNowPlayingAppPID(CFAllocatorRef, pid_t, APMetadataSourceRef *)"
```
