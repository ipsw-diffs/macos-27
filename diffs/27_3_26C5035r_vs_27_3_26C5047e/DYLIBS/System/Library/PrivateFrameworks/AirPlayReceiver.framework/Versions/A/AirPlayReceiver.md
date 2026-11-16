## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/Versions/A/AirPlayReceiver`

```diff

-1015.5.1.0.0
-  __TEXT.__text: 0xf6c38
+1015.8.1.0.0
+  __TEXT.__text: 0xf74f8
   __TEXT.__objc_methlist: 0xca4
   __TEXT.__const: 0xd543
   __TEXT.__dlopen_cstrs: 0x103
   __TEXT.__gcc_except_tab: 0x8b8
-  __TEXT.__cstring: 0x2f216
+  __TEXT.__cstring: 0x2f609
   __TEXT.__oslogstring: 0x2eb
-  __TEXT.__unwind_info: 0x1928
+  __TEXT.__unwind_info: 0x1938
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x48
   __DATA_CONST.__objc_arraydata: 0x10
-  __DATA_CONST.__got: 0x888
+  __DATA_CONST.__got: 0x8a0
   __AUTH_CONST.__const: 0x3db0
-  __AUTH_CONST.__cfstring: 0xb2e0
+  __AUTH_CONST.__cfstring: 0xb380
   __AUTH_CONST.__objc_const: 0x18f8
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_intobj: 0x18

   - /System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/Versions/A/WiFiPeerToPeer
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1485
-  Symbols:   3764
-  CStrings:  4814
+  Functions: 1489
+  Symbols:   3771
+  CStrings:  4832
 
Symbols:
+ GCC_except_table1055
+ GCC_except_table1074
+ GCC_except_table1125
+ GCC_except_table1129
+ GCC_except_table1181
+ GCC_except_table1189
+ GCC_except_table1191
+ GCC_except_table1234
+ GCC_except_table1299
+ GCC_except_table946
+ __HandleLikelyResumableInterruptionTimeout
+ __PauseOnMediaAudioInterruption
+ __TerminateSessionOnAudioInterruption
+ _airplayReqProcessor_ensurePairingServices
+ _kFigEndpointPlaybackSessionState_Paused
+ _kFigEndpointPlaybackSessionState_Playing
+ _kFigEndpointPlaybackSessionState_Stopped
- GCC_except_table1054
- GCC_except_table1073
- GCC_except_table1124
- GCC_except_table1128
- GCC_except_table1180
- GCC_except_table1188
- GCC_except_table1190
- GCC_except_table1233
- GCC_except_table1295
- GCC_except_table945
CStrings:
+ "1015.8.1"
+ "CoreUtils"
+ "OSStatus APPairingServicesCoreUtilsCreate(CFAllocatorRef, APPairingServicesRef *)"
+ "OSStatus _StartServers(AirPlayReceiverServerRef)"
+ "OSStatus airplayReqProcessor_ensurePairingServices(APReceiverRequestProcessorRef, Boolean, APSTransportMessageProcessingStatus *)"
+ "OSStatus coreUtilsPairing_HandleSetup(APPairingServicesRef, CFStringRef, CFDataRef, CFDataRef *, Boolean *)"
+ "Video ended, restoring MR playback state %u from sender\n"
+ "[%{ptr}] APPairingServicesCoreUtils created.\n"
+ "[%{ptr}] Audio interruption is likely resumable. Survive it for up to %u seconds.\n"
+ "[%{ptr}] Created %s pairing services [%{ptr}]\n"
+ "[%{ptr}] Ignoring MR playback state %u from sender while the video player owns it\n"
+ "[%{ptr}] Likely-resumable audio interruption did not end in %u seconds. Terminate session.\n"
+ "[%{ptr}] Likely-resumable audio interruption ended and it is resumable. Cancel the timer.\n"
+ "[%{ptr}] Likely-resumable audio interruption ended, but it is not resumable. Terminate session.\n"
+ "[%{ptr}] Media audio session was paused on resumable interruption.\n"
+ "[%{ptr}] Not paused on media audio interruption. Do nothing.\n"
+ "[%{ptr}] Publishing video player state %@ as MR playback state %u\n"
+ "[%{ptr}] Started %u seconds timer for likely-resumable audio interruption.\n"
+ "_StartLikelyResumableInterruptionTimer"
+ "_StartServers"
+ "airplayReqProcessor_ensurePairingServices"
+ "disablePairSetupThrottling"
+ "isLikelyResumable"
+ "legacy"
+ "likelyResumableInterruptionTimeoutSecs"
+ "mrPlaybackStateFromSender"
+ "updateVideoPlaybackState"
+ "void _HandleLikelyResumableInterruptionTimeout(void *)"
+ "void _PauseOnMediaAudioInterruption(AirPlayReceiverSessionRef)"
+ "void _StartLikelyResumableInterruptionTimer(AirPlayReceiverSessionRef)"
- "1015.5.1"
- "OSStatus APPairingServicesCoreUtilsCreate(CFAllocatorRef, Boolean, APPairingServicesRef *)"
- "OSStatus coreUtilsPairing_HandleSetup(APPairingServicesRef, CFStringRef, APSecurityMode, CFDataRef, CFDataRef *, Boolean *)"
- "[%{ptr}] APPairingServicesCoreUtils (%s) created.\n"
- "[%{ptr}] Created legacy pairing services [%{ptr}]\n"
- "[%{ptr}] Created pairing services [%{ptr}] for pair-setup.\n"
- "[%{ptr}] Created pairing services [%{ptr}] for pair-verify\n"
- "[%{ptr}] Sender doesn't support SurviveAudioInterruption. Do nothing. \n"
- "[%{ptr}] Sender supports resumable interruption. Was paused on media audio interruption? %s.\n"
- "private"
- "public"
- "void _StartServers(AirPlayReceiverServerRef)"
```
