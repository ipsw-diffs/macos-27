## AudioToolbox

> `/System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox`

```diff

-1638.304.1.0.0
-  __TEXT.__text: 0x173cb8
+1638.307.0.0.0
+  __TEXT.__text: 0x173be8
   __TEXT.__realtime: 0x1c208
   __TEXT.__objc_methlist: 0x161c
   __TEXT.__const: 0x4508
   __TEXT.__dlopen_cstrs: 0x3a6
-  __TEXT.__gcc_except_tab: 0x15b2c
-  __TEXT.__cstring: 0xd900
-  __TEXT.__oslogstring: 0x1abc4
+  __TEXT.__gcc_except_tab: 0x15b44
+  __TEXT.__cstring: 0xd908
+  __TEXT.__oslogstring: 0x1ac9d
   __TEXT.__unwind_info: 0x8a48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_arraydata: 0x3a8
   __DATA_CONST.__got: 0x590
   __AUTH_CONST.__const: 0xa9b0
-  __AUTH_CONST.__cfstring: 0x2e20
+  __AUTH_CONST.__cfstring: 0x2e40
   __AUTH_CONST.__objc_const: 0x2180
   __AUTH_CONST.__weak_auth_got: 0x38
   __AUTH_CONST.__objc_intobj: 0x5d0

   - /usr/lib/swift/libswiftos.dylib
   Functions: 6051
   Symbols:   10449
-  CStrings:  3868
+  CStrings:  3872
 
Symbols:
+ __ZN15LoudnessManager11GetSettingsEjP18AQConverterOrCodecjjjjbbPiPNS_8SettingsE
+ _os_unfair_recursive_lock_lock
- __ZN15LoudnessManager11GetSettingsEjP18AQConverterOrCodecjjjjbPiPNS_8SettingsE
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ _AudioServicesCreateSystemSoundID : 596 -> 592
~ __ZL18ActionDataToServerPK7__CFURLPhjjb : 1376 -> 1372
~ _AudioServicesSetProperty : 1224 -> 1216
~ _AudioServicesPlaySystemSoundWithOptions : 2544 -> 2540
~ __ZN18SSClientCompletion20SendClientCompletionEjj : 564 -> 560
~ _AudioServicesDisposeSystemSoundID : 544 -> 540
~ _AudioServicesGetProperty : 1040 -> 1036
~ _AudioServicesGetPropertyInfo : 560 -> 556
~ _AudioServicesAddSystemSoundCompletion : 1700 -> 1692
~ _CreateBuiltInInfo : 692 -> 684
~ __ZN16AudioQueueObject11GetPropertyEjR12CASerializer : 5252 -> 5232
~ __ZN16AudioQueueObject11SetPropertyEjR14CADeserializer : 13012 -> 12980
~ __ZN10AQMEDevice16IO_AdaptToDeviceEi : 3388 -> 3384
~ __ZN10AQMEDevice11AddIOClientER14AQIONodeClient : 904 -> 900
~ __ZN16AudioQueueObject12PerformFlushEv : 336 -> 332
~ __ZN10AQMEDevice24ClearScheduledParametersER14AQIONodeClient : 144 -> 140
~ __ZN10AQMEDevice13SetParametersER14AQIONodeClientPK15XAudioTimeStampiPK24AudioQueueParameterEvent : 184 -> 180
~ __ZN10AQMEDevice19RemoveRunningClientER14AQIONodeClientb : 188 -> 184
~ __ZN10AQMEDevice14RemoveIOClientER14AQIONodeClient : 788 -> 784
~ __ZN8AQIONodeD2Ev : 252 -> 248
~ __ZN14MEMixerChannel12UninitializeEv : 1212 -> 1196
~ __ZN16AudioQueueObject5PrimeEjRj : 1716 -> 1712
~ __ZN16AudioQueueObject20AcquirePlayResourcesEv : 1008 -> 1004
~ __ZN18AQConverterManager17AQConverterThread20ConverterThreadEntryEPv : 744 -> 740
~ __ZN16AudioQueueObject16DecoderInputProcEP20OpaqueAudioConverterPjP15AudioBufferListPP28AudioStreamPacketDescriptionPv : 1168 -> 1160
~ __ZN14MEMixerChannel10InitializeEv : 2460 -> 2440
~ __ZN10AQMEDevice13GetParametersER14AQIONodeClientiPKjPf : 184 -> 180
~ __ZN16AudioQueueObject12EnqueueFlushEv : 236 -> 232
~ __ZN10AQMEDevice12AwaitIOCycleEb : 164 -> 160
~ -[ATAudioSessionClientImpl resetClientConfiguration] : 188 -> 184
~ -[ATAudioSessionClientImpl AudioSessionAddPropertyListenerImpl:userProc:userData:] : 1164 -> 1160
~ -[ATAudioSessionClientImpl AudioSessionRemovePropertyListenerImpl:] : 656 -> 652
~ -[ATAudioSessionClientImpl AudioSessionRemovePropertyListenerWithUserDataImpl:userProc:userData:] : 640 -> 632
~ __ZN29AudioSessionPropertyListeners21CallPropertyListenersEjjPKv : 316 -> 312
~ __ZN15CAListenerProxy27deliverDeferredNotificationERNS_8ListenerERKNS_12NotificationE : 184 -> 180
~ __ZN15CAListenerProxy3addERNS_8ListenerE : 168 -> 164
~ __ZN15CAListenerProxy6removeERNS_8ListenerE : 360 -> 356
~ __ZN14AudioTapObjectD2Ev : 1304 -> 1300
~ ____ZN14AudioTapObject13_setTapFormatERKN2CA17StreamDescriptionERKNS0_13ChannelLayoutE_block_invoke : 360 -> 356
~ __Z15AQIONodeDeleterP8AQIONode : 96 -> 92
~ __ZN15AQIONodeManager13_FindAQIONodeERK14AQMEIO_Binding : 868 -> 864
~ __ZN15AQIONodeManager10_ShowGraphEP7__sFILE : 196 -> 192
~ __ZN8AQIONode18CompleteDeviceTimeE23ESampleTimeSanitizationR14AQIONodeClientR15XAudioTimeStamp : 304 -> 300
~ __ZN15AQIONodeManager18setDynamicsEnabledE15EDynamicsEnable : 192 -> 188
~ __ZN15AQIONodeManager12maintainTapsEb : 144 -> 140
~ __Z20AQIONode_OSWorkgroupP8AQIONode : 228 -> 224
~ __ZN8AQIONode18effectiveIOBindingEv : 180 -> 176
~ __ZN18SSClientCompletion25SendAllPendingCompletionsEv : 244 -> 240
~ ____ZN14MEMixerChannel24SpatialCustomHRTFChangedEv_block_invoke : 260 -> 256
~ ____ZN14MEMixerChannel26ConfigureNormalizationUnitERKN2CA17StreamDescriptionE_block_invoke : 184 -> 180
~ __ZN14MEMixerChannel14TimePitchState5ResetEb : 124 -> 120
~ __ZN29AudioSessionPropertyListeners24CallPropertyListenersImpERKS_jjPKv : 472 -> 468
~ ____ZN11SSClientIPC15ConnectToServerEv_block_invoke : 872 -> 868
~ ____ZN11SSClientIPC15ConnectToServerEv_block_invoke.3 : 2552 -> 2544
~ _CAClockAddListener : 216 -> 212
~ _CAClockRemoveListener : 444 -> 440
~ _CAClockSetProperty : 2820 -> 2816
~ __ZN18AQOfflineMixerBaseD2Ev : 372 -> 368
~ __ZN18AQOfflineMixerBase16EncoderInputProcEP20OpaqueAudioConverterPjP15AudioBufferListPP28AudioStreamPacketDescriptionPv : 7772 -> 7836
~ __ZN16AQMixEngine_Base7DevLockC2EPS_PK14AQIONodeClient : 164 -> 160
~ __ZN5caulk10concurrent7details15rt_message_callIZN11HeadTracker18HeadTrackerSession17UpdateCurrentPoseEvE3$_0JEE7performEv : 304 -> 300
~ __ZN5caulk10concurrent7details15rt_message_callIZN11HeadTracker18HeadTrackerSession17UpdateCurrentPoseEvE3$_1JEE7performEv : 304 -> 300
~ __ZN13MESubmixGraph31checkEnhanceDialogueModeChangedEbP14MEMixerChannel : 360 -> 356
~ __ZN15LoudnessManager17IsLMAULNPermanentEv : 408 -> 356
~ __ZN15LoudnessManager11GetSettingsEjP18AQConverterOrCodecjjjjbPiPNS_8SettingsE -> __ZN15LoudnessManager11GetSettingsEjP18AQConverterOrCodecjjjjbbPiPNS_8SettingsE : 8088 -> 8132
~ ____ZN14AQMEIO_Session4InitEv_block_invoke : 448 -> 444
~ __ZN14AQMEIO_Session12IOC_doLockedERKNSt3__18functionIFvvEEE : 120 -> 116
~ +[ATCallTranslatorInsert createProcessingInsert:inputStreamDescription:inputStreamLayoutTag:outputStreamDescription:outputStreamLayoutTag:maxFrames:reporterID:] : 4560 -> 4556
~ -[ATCallTranslatorInsert setInputMuted:] : 128 -> 124
~ -[ATCallTranslatorInsert inferActiveAudioChannel:] : 492 -> 488
~ __ZN21SpatializationManager14GetPreferencesERK11AQMESessionRK14AQMEIO_Binding20SpatialContentTypeIDR23SpatialAudioPreferencesbb : 8536 -> 8508
~ -[ATPhasePlatform volumeScalarMappedToHWCurve:] : 376 -> 372
~ -[ATPhasePlatform workgroup] : 272 -> 268
~ __ZL9PlaySoundjNSt3__110shared_ptrI19SSClientPlayOptionsEEPhjj : 1984 -> 1980
~ _AudioServicesStopSystemSound : 768 -> 764
~ _AudioServicesCreateSystemSoundIDWithPath : 312 -> 308
~ _AudioServicesCreateSystemSoundIDWithOptions : 584 -> 580
~ _AudioServicesRemoveSystemSoundCompletion : 588 -> 580
~ __ZN16AudioQueueObject4StopEbbPNS_10StopStatusE : 1476 -> 1472
~ __ZN16AudioQueueObject19GetProposedIOFormatERKN2CA17StreamDescriptionEb : 2968 -> 2964
~ __ZN16AudioQueueObject19ConverterConnection14BuildConverterERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE : 6844 -> 6840
~ __ZN16AudioQueueObject17SetLoudnessFromLMEPNS_19ConverterConnectionEPK14__CFDictionary : 12716 -> 12744
~ __ZN16AudioQueueObject15PropertyChangedEjb : 556 -> 552
~ __ZN16AudioQueueObject22ConnectToIONodeEffectsER8AQIONode : 1876 -> 1908
~ __ZN18TSharedAQIONodePtrI19AQMixEngine_OfflineE6createIJR15AQIONodeManagerRN2CA17StreamDescriptionERNS5_13ChannelLayoutEEEES1_DpOT_ : 236 -> 232
~ __ZZN16AudioQueueObject15DoIONodeConnectEbENK3$_0clI14AQMEIO_Binding17AudioTapSpecifierEE18TSharedAQIONodePtrI11AQTapIONodeERKT_RKT0_ : 1428 -> 1420
~ __ZN18TSharedAQIONodePtrI11AQAC3IONodeE6createIJRK14AQMEIO_BindingR14MEStreamTypeIDRiRdEEES1_DpOT_ : 1240 -> 1232
~ __ZN16AudioQueueObject12RunConverterEib : 7900 -> 7872
~ __ZN16AudioQueueObject5StartERK15XAudioTimeStampjNSt3__18optionalIyEES5_ : 5752 -> 5736
~ __ZN16AudioQueueObject30ResetSpatializationCompressionEP8AQIONode : 692 -> 688
~ __ZN16AudioQueueObject32IONode_SpatialPreferencesChangedEv : 372 -> 368
~ __ZN16AudioQueueObject14EnqueueSilenceEjx : 528 -> 524
~ __ZN16AudioQueueObject17FlushPendingInputEbb : 1196 -> 1192
~ __ZN16AudioQueueObject12ConvertInputEPNS_19ConverterConnectionEP15AQBufferCommandRjbb : 1920 -> 1916
~ __ZN16AudioQueueObject21currentLatencySecondsERi : 340 -> 336
~ __ZN16AudioQueueObject22SetOfflineRenderFormatEPK27AudioStreamBasicDescriptionPK18AudioChannelLayoutP18AQOfflineMixerBase : 1348 -> 1344
~ __ZZN16AudioQueueObject24PreflightOfflineRenderV2EdxjPjPhS1_ENK3$_0clEb : 332 -> 328
~ __ZN16AudioQueueObject34SetContentSourceFromISOContentTypeEjj : 448 -> 788
~ __ZN18AQConverterManager17AQConverterThread21RemoveQueueFromThreadER16AudioQueueObject : 312 -> 308
~ __ZN18TSharedAQIONodePtrI18AQMixEngine_SingleE6createIJRK14AQMEIO_BindingRbbEEES1_DpOT_ : 232 -> 228
~ __ZNSt3__14lockB9nqe220106IN5caulk4mach21unfair_recursive_lockENS1_23recursive_mutex_adapterINS1_22pooled_semaphore_mutexEEEEEvRT_RT0_ : 108 -> 104
~ __ZNSt3__112__lock_firstIN5caulk4mach21unfair_recursive_lockENS1_23recursive_mutex_adapterINS1_22pooled_semaphore_mutexEEES3_JN16AudioQueueObject20WorkQueueLockAdapterEEEEviRT_RT0_RT1_DpRT2_ : 560 -> 556
~ __ZNSt3__14lockB9nqe220106IN5caulk4mach21unfair_recursive_lockEN16AudioQueueObject20WorkQueueLockAdapterEEEvRT_RT0_ : 168 -> 160
~ __ZNSt3__112__lock_firstIN5caulk4mach21unfair_recursive_lockENS1_23recursive_mutex_adapterINS1_22pooled_semaphore_mutexEEES3_JEEEviRT_RT0_RT1_DpRT2_ : 444 -> 428
~ ____ZN2AT9MixServer6CommonC2ERKNS0_4Base12DependenciesE_block_invoke_3 : 356 -> 352
~ __ZNSt3__110__function6__funcIZN2AT9MixServer9macOSImpl18accessibilitySetupEvE3$_0FbjRKN15CAListenerProxy15HALNotificationEEEclEOjS9_ : 464 -> 460
~ ____ZN20MEOutputStreamClientC2ER11IAQMEDevice14MEStreamTypeID15EDynamicsEnable_block_invoke : 380 -> 376
~ __ZN2AQ6Server11XPCListener17accept_connectionERKN10applesauce3xpc10connectionE : 1560 -> 1556
~ __ZN20AudioQueueXPC_Server12DisposeQueueEjb : 1100 -> 1096
~ __ZN20AudioQueueXPC_Server13EnqueueBufferEjNSt3__14spanIK26AQBufferCreateDestroyEventLm18446744073709551615EEEjjjNS1_IK28AudioStreamPacketDescriptionLm18446744073709551615EEEjjNS1_IK24AudioQueueParameterEventLm18446744073709551615EEE19XAudioTimeStampBaseb : 6312 -> 6472
~ __ZN20AudioQueueXPC_Server5FlushEjb : 944 -> 940
~ __ZN20AudioQueueXPC_Server19AddPropertyListenerEjj : 544 -> 540
~ __ZN20AudioQueueXPC_Server22RemovePropertyListenerEjj : 560 -> 556
~ __ZN20AudioQueueXPC_Server20DeviceGetCurrentTimeEj : 764 -> 760
~ __ZN20AudioQueueXPC_Server19DeviceTranslateTimeEj19XAudioTimeStampBasej : 804 -> 800
~ __ZN20AudioQueueXPC_Server25DeviceGetNearestStartTimeEj19XAudioTimeStampBasej : 752 -> 748
~ __ZN20AudioQueueXPC_Server13OfflineRenderEj19XAudioTimeStampBaseNSt3__14spanIK26AQBufferCreateDestroyEventLm18446744073709551615EEEjj : 1708 -> 1704
~ __ZN20AudioQueueXPC_Server8MixerNewE27AudioStreamBasicDescriptionN2CA13ChannelLayoutE : 3844 -> 3840
~ __ZN20AudioQueueXPC_Server12SubmixTapNewEjj : 1340 -> 1336
~ __ZN2AQ6Server6V2Impl17forEachQueueTokenEbRKN5caulk12function_refIFvjEEE : 288 -> 284
~ __ZNSt3__110__function6__funcIZN2AQ6Server11XPCListener17accept_connectionERKN10applesauce3xpc10connectionEE3$_0FvRN4swix12ipc_endpointERKNS6_6objectEEEclESD_SG_ : 300 -> 296
~ __ZN5Phase13ServerManager19maxBufferSizeFramesEv : 340 -> 336
~ __ZN5Phase13ServerManager21deviceLatencyInFramesE19PHASEAudioDirection : 332 -> 328
~ __ZN7CAClock4StopEv : 324 -> 320
~ __ZN7CAClock13TellListenersE14CAClockMessagePKv : 120 -> 116
~ __ZN7CAClock5StartEbPd : 284 -> 280
~ __ZN7CAClock14GetDestTargetsE15CAClockSyncModeRiPv : 180 -> 176
~ __ZN2AT11Translation14CallTranslator18AudioFormatChangedENS1_5ScopeERKN2CA17StreamDescriptionERKNS3_13ChannelLayoutE : 284 -> 280
~ __ZN2AT11Translation14CallTranslator28HandleInjectionEndedCallbackENS1_5ScopeENS0_17AudioInjectorModeE : 628 -> 624
~ __ZN10AQMEDevice25IO_DeviceStoppedFromBelowEbb : 168 -> 164
~ __ZN10AQMEDevice12RouteChangedEv : 332 -> 328
~ __ZN10AQMEDevice17SoundCheckChangedEv : 344 -> 340
~ __ZN10AQMEDevice25ScreenSharingStateChangedEy : 964 -> 960
~ __ZN10AQMEDevice22RemoveAndReAddIOClientER14AQIONodeClient : 1320 -> 1316
~ __ZN10AQMEDevice16StopFreewheelingEv : 128 -> 124
~ __ZN10AQMEDevice18ResetOfflineRenderEv : 144 -> 140
~ __ZN10AQMEDevice26IsProcessingFeatureEnabledER14AQIONodeClient13MEProcessorIDRj : 172 -> 168
~ __ZN10AQMEDevice27SetProcessingFeatureEnabledER14AQIONodeClient13MEProcessorIDbP27AudioStreamBasicDescriptionPK20ProcessingFormatInfo : 192 -> 188
~ __ZN10AQMEDevice15ResetProcessorsER14AQIONodeClientbb : 168 -> 164
~ __ZN10AQMEDevice23AccessProcessorPropertyEP14AQIONodeClient13MEProcessorIDjbRjPv : 436 -> 432
~ __ZN10AQMEDevice17AddProcessingNodeER14AQIONodeClientR16AQProcessingNode : 168 -> 164
~ __ZN10AQMEDevice20RemoveProcessingNodeER14AQIONodeClientRK16AQProcessingNode : 160 -> 156
~ __ZN10AQMEDevice32ProcessingNodeScheduleParametersER14AQIONodeClientRK16AQProcessingNodeRK15XAudioTimeStampjPK32ATAudioProcessingNodeParameterIDPKf : 208 -> 204
~ __ZN10AQMEDevice38ProcessingNodeDeliverPendingParametersER14AQIONodeClientR16AQProcessingNodex : 168 -> 164
~ __ZN10AQMEDevice39ProcessingNodeCancelScheduledParametersER14AQIONodeClientR16AQProcessingNodeb : 168 -> 164
~ __ZN10AQMEDevice29RestartIOFollowingRouteChangeEv : 768 -> 764
~ __ZN10AQMEDevice12maintainTapsEb : 216 -> 212
~ __ZN18AQMixEngine_Single13ForAllDevicesERKNSt3__18functionIFvR11IAQMEDeviceEEE : 144 -> 140
~ __ZN11AQAC3IONode11AddIOClientER14AQIONodeClient : 844 -> 840
~ __ZN11AQAC3IONode14RemoveIOClientER14AQIONodeClient : 244 -> 240
~ __ZN11AQAC3IONode19RemoveRunningClientER14AQIONodeClientb : 316 -> 312
~ __ZN11AQAC3IONode10DebugPrintEP7__sFILE : 500 -> 496
~ __ZN11AQAC3IONode29RestartIOFollowingRouteChangeEv : 300 -> 296
~ __ZN11AQAC3IONode12AwaitIOCycleER14AQIONodeClientb : 160 -> 156
~ __ZN11AQTapIONodeD2Ev : 384 -> 380
~ __ZN11AQTapIONode11AddIOClientER14AQIONodeClient : 1200 -> 1196
~ __ZN11AQTapIONode14RemoveIOClientER14AQIONodeClient : 300 -> 296
~ __ZN11AQTapIONode16AddRunningClientER14AQIONodeClientbb : 5120 -> 5108
~ __ZN11AQTapIONode19RemoveRunningClientER14AQIONodeClientb : 328 -> 324
~ __ZN17AQMEIO_AudioQueue20ShouldHandlePropertyEj : 288 -> 272
~ __ZNK17AQMEIO_AudioQueue14AQMEDIAccessorERi : 324 -> 320
~ ____ZN10AQMEIO_HAL28scheduleConfigChangeWatchdogERN5caulk4mach21unfair_recursive_lockEdj_block_invoke : 328 -> 324
CStrings:
+ "%25s:%-5d %.*s@%p %s: AudioQueueEnqueueBuffer: buffer %d mAudioDataByteSize 0x%x exceeds capacity 0x%x"
+ "%25s:%-5d %.*s@%p %s: PreflightOfflineRender - failed to query UnflushedSampleCount: %d"
+ "%25s:%-5d %.*s@%p %s: unrecognised spatial content source: %u"
+ "%25s:%-5d %.*s@%p %s: unrecognised traditional content source: %u"
+ "%25s:%-5d [static] %s: LM AULN permanence is defeated"
+ "Offline"
- "%25s:%-5d %.*s@%p %s: PreflightOfflineRender - failed to query InputPullAheadFrameCount: %d"
- "%25s:%-5d [static] %s: LM AULN permanence is set from fflag: %s"
```
