## AudioToolbox

> `/System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox`

```diff

-1638.213.0.0.0
-  __TEXT.__text: 0x173aac
-  __TEXT.__realtime: 0x1c134
+1638.304.1.0.0
+  __TEXT.__text: 0x173cb8
+  __TEXT.__realtime: 0x1c208
   __TEXT.__objc_methlist: 0x161c
   __TEXT.__const: 0x4508
   __TEXT.__dlopen_cstrs: 0x3a6
-  __TEXT.__gcc_except_tab: 0x15b6c
-  __TEXT.__cstring: 0xdf7c
-  __TEXT.__oslogstring: 0x1ab7d
+  __TEXT.__gcc_except_tab: 0x15b2c
+  __TEXT.__cstring: 0xd900
+  __TEXT.__oslogstring: 0x1abc4
   __TEXT.__unwind_info: 0x8a48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1150
+  __DATA_CONST.__const: 0xfe0
   __DATA_CONST.__objc_classlist: 0xb0
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arraydata: 0x3a8
   __DATA_CONST.__got: 0x590
   __AUTH_CONST.__const: 0xa9b0
-  __AUTH_CONST.__cfstring: 0x2dc0
+  __AUTH_CONST.__cfstring: 0x2e20
   __AUTH_CONST.__objc_const: 0x2180
   __AUTH_CONST.__weak_auth_got: 0x38
   __AUTH_CONST.__objc_intobj: 0x5d0

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 6050
-  Symbols:   10450
-  CStrings:  3944
+  Functions: 6051
+  Symbols:   10449
+  CStrings:  3868
 
Symbols:
- GCC_except_table3920
Functions:
+ sub_1ad78eca8
~ _readHapticCommand : 1008 -> 1020
~ __ZN14MEMixerChannel28DisconnectReconfigureAddNodeEP11MCAudioUnitRKN2CA17StreamDescriptionERNSt3__16vectorIP15XProcessingBaseNS6_9allocatorIS9_EEEE : 12244 -> 12560
~ __ZN15LoudnessManager29ApplyLMAULNLoudnessPropertiesEP14AQIONodeClientP8AQIONodeRKNS_8SettingsE : 2652 -> 2348
~ __ZN15LoudnessManager11GetSettingsEjP18AQConverterOrCodecjjjjbPiPNS_8SettingsE : 7788 -> 8088
~ __ZN16AudioQueueObject17SetLoudnessFromLMEPNS_19ConverterConnectionEPK14__CFDictionary : 12492 -> 12716
~ __ZN16AudioQueueObject29SetContentSourceFromMediaKindEPK10__CFString : 728 -> 512
~ __ZN17AQMEIO_AudioQueue20ShouldHandlePropertyEj : 272 -> 288
~ __ZN14MEMixerChannel19TimePitchDownstreamEPvPjPK14AudioTimeStampjjP15AudioBufferList : 2116 -> 2328
CStrings:
+ "%25s:%-5d %.*s@%p %s: watch hardware not supported, Loudness Manager disabled"
+ "%25s:%-5d MEMixerChannel:: %s _OptimizeForDownMix on the time-stretching unit (%d)"
+ "%25s:%-5d [static] %s: NOT setting LM AULN input gain to %f"
+ "Disabled"
+ "Enabled"
+ "OptimizeTimeStretchingForDownmix"
+ "Private_UsesAudioSessionMode_Movie"
+ "Private_UsesAudioSessionMode_Podcast"
+ "lm-set-content-source-for-usac"
- "%25s:%-5d [static] %s: could not set kMELMLoudnessNormalizerProperty_InputGain, error %d (%s)"
- "%25s:%-5d [static] %s: setting LM AULN input gain to %f"
- "AQInternalGetOfflineBufferCompletions"
- "AQInternalPreflightOfflineRender"
- "AQInternalScheduledStart"
- "AQServer_CheckStopFromPause"
- "AddPropertyListener"
- "AudioQueueDeassignFromSubmixTap"
- "AudioQueueDeviceHasDisconnected"
- "AudioQueueIOBindingChanged"
- "AudioQueueInternalDeliverProcessingNodeEvents"
- "AudioQueueInternalFormatChanged"
- "AudioQueueInternalNotifyRunning"
- "AudioQueueInternalPause"
- "AudioQueueInternalReleasePlayResources"
- "AudioQueueInternalResetOfflineRenderState"
- "AudioQueueInternalStop_Sync"
- "AudioQueueLatencyChanged"
- "AudioQueueNotifyReadyToRestart"
- "AudioQueueSetLoudnessFromLM"
- "CreateTimeline"
- "DebugPrint"
- "DeviceGetCurrentTime"
- "DeviceGetNearestStartTime"
- "DeviceIsRunning"
- "DeviceTranslateTime"
- "DisposeQueue"
- "DisposeTimeline"
- "Flush"
- "GetCurrentTime"
- "GetMaxIOBufferFrameSize"
- "GetNearestStartTime"
- "GetPendingCallbackMessages"
- "GetProperty"
- "GetPropertySize"
- "GetSampleRate"
- "GetStreamFormat"
- "GetTotalNumberChannels"
- "HandleAQGetParameter"
- "HandleAQGetProperty"
- "HandleAQScheduledParameters"
- "HandleAQSetParameter"
- "HandleAQSetProperty"
- "LatencySamples"
- "MapSharedBuffers"
- "MixerConnectQueue"
- "MixerDispose"
- "MixerGetProperty"
- "MixerGetPropertySize"
- "MixerNew"
- "MixerRender"
- "MixerReset"
- "MixerSetProperty"
- "NewQueue"
- "ProcessingNodeDispose"
- "ProcessingNodeInstantiate"
- "ProcessingTapDispose"
- "ProcessingTapInit"
- "ProcessingTapNew"
- "QueueGetCurrentTime"
- "RemovePropertyListener"
- "ScaleOrUnscaleSampleTime"
- "SetAudioQueue"
- "SetTopologyFlags"
- "StartIO_Primitive"
- "TranslateTime"
- "_InternalDispose"
- "bluetoothAlternateTransportMode"
- "bluetoothUserHeadTrackingModeForBundleID"
- "bluetoothUserSpatialModeForBundleID"
- "calibrationData"
- "commandSize != 0"
- "customHRTFMode"
- "dynamicLatency"
- "enableHeadTrackingMode"
- "getHeadTracker"
- "getHeadTrackingSupport"
- "hasDefaultOutputSpeakerPort"
- "setClockDevice"
- "setSpatialStreamInfo"
- "setVolumeScalar"
- "triggerSPENOnAlternateTransportChange"
- "volumeScalar"
- "volumeScalarMappedToHWCurve"
- "~RemoteClient_block_invoke"
```
