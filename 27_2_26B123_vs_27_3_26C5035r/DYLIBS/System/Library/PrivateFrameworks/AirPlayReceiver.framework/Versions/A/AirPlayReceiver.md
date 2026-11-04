## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/Versions/A/AirPlayReceiver`

```diff

-1005.13.1.0.0
-  __TEXT.__text: 0xf66d8
+1015.5.1.0.0
+  __TEXT.__text: 0xf6c38
   __TEXT.__objc_methlist: 0xca4
   __TEXT.__const: 0xd543
   __TEXT.__dlopen_cstrs: 0x103
-  __TEXT.__gcc_except_tab: 0x8ac
-  __TEXT.__cstring: 0x2f05f
+  __TEXT.__gcc_except_tab: 0x8b8
+  __TEXT.__cstring: 0x2f216
   __TEXT.__oslogstring: 0x2eb
-  __TEXT.__unwind_info: 0x1920
+  __TEXT.__unwind_info: 0x1928
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_superrefs: 0x48
   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__got: 0x888
-  __AUTH_CONST.__const: 0x3d80
-  __AUTH_CONST.__cfstring: 0xb240
+  __AUTH_CONST.__const: 0x3db0
+  __AUTH_CONST.__cfstring: 0xb2e0
   __AUTH_CONST.__objc_const: 0x18f8
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_intobj: 0x18

   - /System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/Versions/A/WiFiPeerToPeer
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1483
-  Symbols:   3759
-  CStrings:  4803
+  Functions: 1485
+  Symbols:   3764
+  CStrings:  4814
 
Symbols:
+ GCC_except_table1054
+ GCC_except_table1073
+ GCC_except_table1124
+ GCC_except_table1128
+ GCC_except_table1180
+ GCC_except_table1188
+ GCC_except_table1190
+ GCC_except_table1233
+ GCC_except_table1295
+ GCC_except_table400
+ GCC_except_table456
+ GCC_except_table480
+ GCC_except_table534
+ GCC_except_table538
+ GCC_except_table545
+ GCC_except_table553
+ GCC_except_table733
+ GCC_except_table745
+ GCC_except_table748
+ GCC_except_table751
+ GCC_except_table759
+ GCC_except_table772
+ GCC_except_table774
+ GCC_except_table945
+ _AirPlayManagedDefaultsLogging_HandleReceiverManagedDefaultsLoggingChanged
+ _CFPreferencesAppSynchronize
+ _LogControlCF
+ ____StartAudioSessionsIfNeeded_block_invoke
+ ___block_descriptor_48_e8_32r_e15_v24?0r^v8r^v16l
+ ___block_descriptor_64_e8_32o_e8_v12?0i8l
- GCC_except_table1053
- GCC_except_table1072
- GCC_except_table1123
- GCC_except_table1127
- GCC_except_table1179
- GCC_except_table1187
- GCC_except_table1189
- GCC_except_table1232
- GCC_except_table1294
- GCC_except_table399
- GCC_except_table455
- GCC_except_table479
- GCC_except_table533
- GCC_except_table537
- GCC_except_table544
- GCC_except_table552
- GCC_except_table732
- GCC_except_table744
- GCC_except_table747
- GCC_except_table750
- GCC_except_table758
- GCC_except_table771
- GCC_except_table773
- GCC_except_table944
- ___block_descriptor_56_e8_32o_e8_v12?0i8l
Functions:
+ _AirPlayManagedDefaultsLogging_HandleReceiverManagedDefaultsLoggingChanged
~ ___AirPlayReceiverServerPlatformInitialize_block_invoke : 12 -> 4
~ _AirPlayReceiverServerPlatformSetProperty : 428 -> 416
~ -[AirPlayReceiverPlatform setReceiverSessionCountAndUpdateStateIfNeeded:] : 376 -> 412
~ -[AirPlayReceiverPlatform _startNowPlayingSessionAsync:] : 324 -> 348
~ ___56-[AirPlayReceiverPlatform _startNowPlayingSessionAsync:]_block_invoke : 340 -> 348
~ ___56-[AirPlayReceiverPlatform _startNowPlayingSessionAsync:]_block_invoke_2 : 268 -> 308
~ ____IsWiFiDECaptureAllowed_block_invoke : 40 -> 36
~ _sysInfo_updatePrefs : 4184 -> 4200
~ _sysInfo_createFeaturesInternal : 1396 -> 1424
~ _AirPlayReceiverServerCreate : 11760 -> 11752
~ __HandleHTTPConnectionMessage : 12608 -> 12576
~ _airplayReqProcessor_Stop : 1368 -> 1472
~ _airplayReqProcessor_reportSessionActivationMetricsIfNeeded : 1040 -> 1048
~ _airplayReqProcessor_handleMediaTerminationMetricsIfNeeded : 820 -> 980
~ _airplayReqProcessor_registerReqProcWithSessionManager : 1644 -> 1656
~ _airplayReqProcessor_ensureReceiverSessionPreparedForMedia : 1692 -> 1868
~ _airplayReqProcessor_createSession : 2128 -> 2124
~ _AirPlayReceiverSessionCopyProperty : 1524 -> 1576
~ _AirPlayReceiverSessionSetup : 14912 -> 14920
~ __GeneralAudioSetup : 14180 -> 14184
+ ____StartAudioSessionsIfNeeded_block_invoke
~ ____TimingSetupAsync_block_invoke : 720 -> 724
~ _APReceiverSessionManagerUpdateAndNotifyReceiverSessionState : 612 -> 688
~ _APReceiverSessionManagerRemoveSession : 1092 -> 1104
CStrings:
+ "1015.5.1"
+ "Added a new %s session.\n"
+ "AirPlayCALMLoudness"
+ "AirPlayServerLoggingLevel"
+ "AirPlayServerLoggingOutput"
+ "MediaControlSenderLogControlCF"
+ "Music/"
+ "OSStatus _StartAudioSessionsIfNeeded(AirPlayReceiverSessionRef)_block_invoke"
+ "Releasing %s session\n"
+ "[%{ptr}] APReceiverAudioSession [%{ptr}] already started\n"
+ "[%{ptr}] General audio setup, stream type %d\n"
+ "[%{ptr}] Starting APReceiverAudioSession [%{ptr}] set up before prepare for media\n"
+ "_StartAudioSessionsIfNeeded_block_invoke"
+ "mediaStandard"
+ "networkClockAsyncStartDurationMs"
+ "receiverSessionCount: %d -> %d (media %d -> %d)\n"
- "1005.13.1"
- "Added a new AirPlay session.\n"
- "Releasing AirPlay session\n"
- "[%{ptr}] General audio setup\n"
- "receiverSessionCount: %d -> %d\n"
```
