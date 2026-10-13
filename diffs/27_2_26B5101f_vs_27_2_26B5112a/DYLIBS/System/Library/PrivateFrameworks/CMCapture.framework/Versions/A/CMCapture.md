## CMCapture

> `/System/Library/PrivateFrameworks/CMCapture.framework/Versions/A/CMCapture`

```diff

-764.40.7.0.0
-  __TEXT.__text: 0x417a10
-  __TEXT.__objc_methlist: 0x2b2a4
+764.41.11.0.0
+  __TEXT.__text: 0x41a02c
+  __TEXT.__objc_methlist: 0x2b464
   __TEXT.__const: 0x143090
-  __TEXT.__cstring: 0x68d70
-  __TEXT.__oslogstring: 0x314b8
+  __TEXT.__cstring: 0x692de
+  __TEXT.__oslogstring: 0x31611
   __TEXT.__gcc_except_tab: 0x1840
   __TEXT.__dlopen_cstrs: 0x23e
   __TEXT.__ustring: 0x6ea
-  __TEXT.__unwind_info: 0xddb0
+  __TEXT.__unwind_info: 0xddf0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6208
+  __DATA_CONST.__const: 0x6220
   __DATA_CONST.__objc_classlist: 0x1400
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x380
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x12ec0
+  __DATA_CONST.__objc_selrefs: 0x12f88
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x12a8
   __DATA_CONST.__objc_arraydata: 0x1690
-  __DATA_CONST.__got: 0x6710
+  __DATA_CONST.__got: 0x67a8
   __AUTH_CONST.__const: 0x5658
-  __AUTH_CONST.__cfstring: 0x3e6e0
-  __AUTH_CONST.__objc_const: 0x79e68
-  __AUTH_CONST.__objc_intobj: 0x4158
+  __AUTH_CONST.__cfstring: 0x3ea60
+  __AUTH_CONST.__objc_const: 0x7a210
+  __AUTH_CONST.__objc_intobj: 0x4200
   __AUTH_CONST.__objc_arrayobj: 0x1218
   __AUTH_CONST.__objc_floatobj: 0x1b0
   __AUTH_CONST.__objc_doubleobj: 0x280
   __AUTH_CONST.__objc_dictobj: 0x118
   __AUTH_CONST.__auth_got: 0x2198
   __AUTH.__objc_data: 0x320
-  __DATA.__objc_ivar: 0x9354
+  __DATA.__objc_ivar: 0x93a8
   __DATA.__data: 0x21c
   __DATA.__common: 0xf40
   __DATA.__bss: 0x11d8

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 25177
-  Symbols:   49851
-  CStrings:  13951
+  Functions: 25237
+  Symbols:   49969
+  CStrings:  13990
 
Symbols:
+ -[BWDeferredCaptureContainerManager setUsesReducedPriorityFlushQueue:]
+ -[BWDeferredCaptureContainerManager usesReducedPriorityFlushQueue]
+ -[BWHVSScoringNode _shouldDropYUVInputSampleBufferForThermalMitigation:]
+ -[BWMultiStreamCameraSourceNode setDeviceProximityDetectionDeviceTypes:]
+ -[BWMultiStreamCameraSourceNode setDeviceProximityDetectionTargetFrameRate:]
+ -[BWMultiStreamCameraSourceNode setLightSourceEstimationAmbientLuminance:]
+ -[BWMultiStreamCameraSourceNode setLightSourceEstimationTargetFrameRate:]
+ -[BWSecureMetadataOutputConfiguration deviceProximityDetectionDeviceTypes]
+ -[BWSecureMetadataOutputConfiguration deviceProximityDetectionEnabled]
+ -[BWSecureMetadataOutputConfiguration deviceProximityDetectionTargetFrameRate]
+ -[BWSecureMetadataOutputConfiguration lightSourceEstimationAmbientLuminance]
+ -[BWSecureMetadataOutputConfiguration lightSourceEstimationEnabled]
+ -[BWSecureMetadataOutputConfiguration lightSourceEstimationTargetFrameRate]
+ -[BWSecureMetadataOutputConfiguration perceptionTestModeEnabled]
+ -[BWSecureMetadataOutputConfiguration perceptionThumbnailChannelMetadataObjectTypes]
+ -[BWSecureMetadataOutputConfiguration perceptionThumbnailChannelTargetFrameRate]
+ -[BWSecureMetadataOutputConfiguration setDeviceProximityDetectionDeviceTypes:]
+ -[BWSecureMetadataOutputConfiguration setDeviceProximityDetectionEnabled:]
+ -[BWSecureMetadataOutputConfiguration setDeviceProximityDetectionTargetFrameRate:]
+ -[BWSecureMetadataOutputConfiguration setLightSourceEstimationAmbientLuminance:]
+ -[BWSecureMetadataOutputConfiguration setLightSourceEstimationEnabled:]
+ -[BWSecureMetadataOutputConfiguration setLightSourceEstimationTargetFrameRate:]
+ -[BWSecureMetadataOutputConfiguration setPerceptionTestModeEnabled:]
+ -[BWSecureMetadataOutputConfiguration setPerceptionThumbnailChannelMetadataObjectTypes:]
+ -[BWSecureMetadataOutputConfiguration setPerceptionThumbnailChannelTargetFrameRate:]
+ -[BWStillImageCoordinatorNode _calibrationCaptureSensorRawReleasedForRequest:]
+ -[BWVideoCompressorNode encoderPriorityInversionFixEnabled]
+ -[BWVideoCompressorNode setEncoderPriorityInversionFixEnabled:]
+ -[FigCaptureCameraSourcePipeline setDeviceProximityDetectionDeviceTypes:]
+ -[FigCaptureCameraSourcePipeline setDeviceProximityDetectionTargetFrameRate:]
+ -[FigCaptureCameraSourcePipeline setLightSourceEstimationAmbientLuminance:]
+ -[FigCaptureCameraSourcePipeline setLightSourceEstimationTargetFrameRate:]
+ -[FigCaptureSourceAttributes supportedMetadataIdentifiersForPerceptionThumbnailChannel]
+ -[FigMetadataObjectCaptureConnectionConfiguration deviceProximityDetectionDeviceTypes]
+ -[FigMetadataObjectCaptureConnectionConfiguration deviceProximityDetectionTargetFrameRate]
+ -[FigMetadataObjectCaptureConnectionConfiguration lightSourceEstimationAmbientLuminance]
+ -[FigMetadataObjectCaptureConnectionConfiguration lightSourceEstimationTargetFrameRate]
+ -[FigMetadataObjectCaptureConnectionConfiguration metadataIdentifiersForPerceptionThumbnailChannel]
+ -[FigMetadataObjectCaptureConnectionConfiguration perceptionTestModeEnabled]
+ -[FigMetadataObjectCaptureConnectionConfiguration setDeviceProximityDetectionDeviceTypes:]
+ -[FigMetadataObjectCaptureConnectionConfiguration setDeviceProximityDetectionTargetFrameRate:]
+ -[FigMetadataObjectCaptureConnectionConfiguration setLightSourceEstimationAmbientLuminance:]
+ -[FigMetadataObjectCaptureConnectionConfiguration setLightSourceEstimationTargetFrameRate:]
+ -[FigMetadataObjectCaptureConnectionConfiguration setMetadataIdentifiersForPerceptionThumbnailChannel:]
+ -[FigMetadataObjectCaptureConnectionConfiguration setPerceptionTestModeEnabled:]
+ BWCreateSampleBufferWithDeviceProximityDetectionDictionary
+ BWCreateSampleBufferWithLightSourceEstimationDictionary
+ GCC_except_table474
+ GCC_except_table527
+ GCC_except_table577
+ GCC_except_table579
+ GCC_except_table584
+ GCC_except_table589
+ GCC_except_table591
+ GCC_except_table593
+ GCC_except_table96
+ OBJC_IVAR_$_BWAssistiveOverlayNode._unpackedOutputPool
+ OBJC_IVAR_$_BWDeferredCaptureContainerManager._flushQueueReducedPriority
+ OBJC_IVAR_$_BWDeferredCaptureContainerManager._usesReducedPriorityFlushQueue
+ OBJC_IVAR_$_BWHVSScoringNode._frameSkippingThermalMitigationEnabled
+ OBJC_IVAR_$_BWHVSScoringNode._lastProcessedCaptureID
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNode._deviceProximityDetectionOutput
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNode._lightSourceEstimationOutput
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._deviceProximityDetectionDeviceTypes
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._deviceProximityDetectionEnabled
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._deviceProximityDetectionTargetFrameRate
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._lightSourceEstimationAmbientLuminance
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._lightSourceEstimationEnabled
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._lightSourceEstimationTargetFrameRate
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._perceptionTestModeEnabled
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._perceptionThumbnailChannelMetadataObjectTypes
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._perceptionThumbnailChannelTargetFrameRate
+ OBJC_IVAR_$_BWVideoCompressorNode._encoderPriorityInversionFixEnabled
+ OBJC_IVAR_$_FigCaptureSourceAttributes._supportedMetadataIdentifiersForPerceptionThumbnailChannel
+ OBJC_IVAR_$_FigMetadataObjectCaptureConnectionConfiguration._deviceProximityDetectionDeviceTypes
+ OBJC_IVAR_$_FigMetadataObjectCaptureConnectionConfiguration._deviceProximityDetectionTargetFrameRate
+ OBJC_IVAR_$_FigMetadataObjectCaptureConnectionConfiguration._lightSourceEstimationAmbientLuminance
+ OBJC_IVAR_$_FigMetadataObjectCaptureConnectionConfiguration._lightSourceEstimationTargetFrameRate
+ OBJC_IVAR_$_FigMetadataObjectCaptureConnectionConfiguration._metadataIdentifiersForPerceptionThumbnailChannel
+ OBJC_IVAR_$_FigMetadataObjectCaptureConnectionConfiguration._perceptionTestModeEnabled
+ _BWCreateSampleBufferWithDeviceProximityDetectionDictionary
+ _BWCreateSampleBufferWithLightSourceEstimationDictionary
+ _BWGetStillImageProcessingReducedFigThreadPriority
+ _FigCaptureClientApplicationIdentifierPerceptiond
+ _FigCaptureClientApplicationIdentifierVoiceOver
+ _FigCaptureMetadataObjectConfigurationRequiresDeviceProximityDetection
+ _FigCaptureMetadataObjectConfigurationRequiresLightSourceEstimation
+ __OBJC_$_PROP_LIST_BWDeferredCaptureContainerManager
+ ___59-[BWStillImageCoordinatorNode renderSampleBuffer:forInput:]_block_invoke_2
+ ___78-[BWStillImageCoordinatorNode _calibrationCaptureSensorRawReleasedForRequest:]_block_invoke
+ ___block_descriptor_49_e8_32r40r_e35_v40?0^{__CFDictionary=}8{?=qiIq}16l
+ _kFigCaptureSampleBufferAttachmentKey_DeviceProximityDetection
+ _kFigCaptureSampleBufferAttachmentKey_LightSourceEstimation
+ _kFigCaptureSourceAttributeKey_SupportedMetadataIdentifiersForPerceptionThumbnailChannel
+ _kFigCaptureStreamMetadataOutputConfigurationKey_SecureDeviceProximityDetectionConfiguration
+ _kFigCaptureStreamMetadataOutputConfigurationKey_SecureDeviceProximityDetectionEnabled
+ _kFigCaptureStreamMetadataOutputConfigurationKey_SecureLightSourceEstimationConfiguration
+ _kFigCaptureStreamMetadataOutputConfigurationKey_SecureLightSourceEstimationEnabled
+ _kFigCaptureStreamMetadataOutputKey_SecureDetectedProximityDevices
+ _kFigCaptureStreamMetadataOutputKey_SecureLightSourceEstimation
+ _kFigCaptureStreamSecureDeviceProximityDetectionConfigurationKey_DeviceTypes
+ _kFigCaptureStreamSecureDeviceProximityDetectionConfigurationKey_TargetFrameRate
+ _kFigCaptureStreamSecureFaceIDKey_FrameType
+ _kFigCaptureStreamSecureFaceIDKey_ProjectornMode
+ _kFigCaptureStreamSecureLightSourceEstimationConfigurationKey_AmbientLuminance
+ _kFigCaptureStreamSecureLightSourceEstimationConfigurationKey_TargetFrameRate
+ _kFigCaptureStreamSecureObjectDetectionConfigurationKey_PerceptionTestModeEnabled
+ _kFigCaptureStreamSecureObjectDetectionConfigurationKey_PerceptionThumbnailChannelMetadataObjectTypes
+ _kFigCaptureStreamSecureObjectDetectionConfigurationKey_PerceptionThumbnailChannelTargetFrameRate
+ _kFigCaptureStreamSecureObjectDetectionConfigurationKey_TargetFrameRate
+ _kFigMetadataIdentifier_QuickTimeMetadataDeviceProximityDetection
+ _kFigMetadataIdentifier_QuickTimeMetadataLightSourceEstimation
+ _multiStreamCameraSourceNode_secureDeviceProximityDetectionServiceQueueCallback
+ _multiStreamCameraSourceNode_secureLightSourceEstimationServiceQueueCallback
+ _objc_msgSend$deviceProximityDetectionDeviceTypes
+ _objc_msgSend$deviceProximityDetectionEnabled
+ _objc_msgSend$deviceProximityDetectionTargetFrameRate
+ _objc_msgSend$lightSourceEstimationAmbientLuminance
+ _objc_msgSend$lightSourceEstimationEnabled
+ _objc_msgSend$lightSourceEstimationTargetFrameRate
+ _objc_msgSend$metadataIdentifiersForPerceptionThumbnailChannel
+ _objc_msgSend$perceptionTestModeEnabled
+ _objc_msgSend$perceptionThumbnailChannelMetadataObjectTypes
+ _objc_msgSend$perceptionThumbnailChannelTargetFrameRate
+ _objc_msgSend$setDeviceProximityDetectionDeviceTypes:
+ _objc_msgSend$setDeviceProximityDetectionEnabled:
+ _objc_msgSend$setDeviceProximityDetectionTargetFrameRate:
+ _objc_msgSend$setEncoderPriorityInversionFixEnabled:
+ _objc_msgSend$setLightSourceEstimationAmbientLuminance:
+ _objc_msgSend$setLightSourceEstimationEnabled:
+ _objc_msgSend$setLightSourceEstimationTargetFrameRate:
+ _objc_msgSend$setMetadataIdentifiersForPerceptionThumbnailChannel:
+ _objc_msgSend$setPerceptionTestModeEnabled:
+ _objc_msgSend$setPerceptionThumbnailChannelMetadataObjectTypes:
+ _objc_msgSend$setPerceptionThumbnailChannelTargetFrameRate:
- -[BWAssistiveOverlayNode _teardownRenderResources]
- -[BWAssistiveOverlayNode configurationWithID:updatedFormat:didBecomeLiveForInput:]
- -[BWAssistiveOverlayNode didReachEndOfDataForConfigurationID:input:]
- GCC_except_table468
- GCC_except_table521
- GCC_except_table571
- GCC_except_table573
- GCC_except_table578
- GCC_except_table583
- GCC_except_table585
- GCC_except_table587
- GCC_except_table94
- OBJC_IVAR_$_BWAssistiveOverlayNode._hasPendingConfiguration
- OBJC_IVAR_$_BWAssistiveOverlayNode._liveOutputVideoFormat
- OBJC_IVAR_$_BWAssistiveOverlayNode._pendingOutputVideoFormat
- ___block_descriptor_48_e8_32r40r_e35_v40?0^{__CFDictionary=}8{?=qiIq}16l
- _kFigCaptureStreamStreamingObjectDetectionConfigurationKey_TargetFrameRate
CStrings:
+ ", deviceProximityDetection:{deviceTypes: %@"
+ ", lightSourceEstimation:{ambientLuminance:%d"
+ ", metadataIdentifiersForPerception:%lu, testMode:%d"
+ ", targetFrameRate:%.2f}"
+ "-[BWAssistiveOverlayNode renderSampleBuffer:forInput:]"
+ "-[BWStillImageCoordinatorNode _calibrationCaptureSensorRawReleasedForRequest:]_block_invoke"
+ "23:30:52"
+ "<<<< BWAssistiveOverlayNode >>>> %s: Render path not available, emitting raw input"
+ "<<<< BWMultiStreamCameraSourceNode >>>> %s: Received Face ID Result <rawFrameId: %@, metadataFrameId: %@, refFrameId: %@, frameType: %d, projectorMode: %d> %@"
+ "<<<< BWStillImageCoordinatorNode >>>> %s: SoftISPCal: Sensor raw released [%d / %d] for captureID:%lld"
+ "AVMetadataObjectTypeDeviceProximityDetection"
+ "AVMetadataObjectTypeLightSourceEstimation"
+ "BWAssistiveOverlayNode unpacked output"
+ "DeviceProximityDetection"
+ "LastShownBuild:BWHVSScoringNode.m:1205"
+ "LastShownBuild:BWHVSScoringNode.m:2906"
+ "LastShownBuild:BWHVSScoringNode.m:2911"
+ "LastShownBuild:BWHVSScoringNode.m:2914"
+ "LastShownBuild:BWHVSScoringNode.m:2983"
+ "LastShownBuild:BWHVSScoringNode.m:3503"
+ "LastShownBuild:BWMultiStreamCameraSourceNode.m:13942"
+ "LastShownBuild:BWMultiStreamCameraSourceNode.m:13958"
+ "LastShownBuild:BWStillImageCoordinatorNode.m:1480"
+ "LastShownBuild:BWStillImageCoordinatorNode.m:1487"
+ "LastShownBuild:BWStillImageCoordinatorNode.m:1557"
+ "LastShownBuild:BWStillImageCoordinatorNode.m:1663"
+ "LastShownBuild:BWStillImageCoordinatorNode.m:1674"
+ "LastShownBuild:BWStillImageCoordinatorNode.m:2320"
+ "LastShownBuild:BWStillImageCoordinatorNode.m:3975"
+ "LastShownBuild:FigCaptureSession.m:1018"
+ "LastShownBuild:FigCaptureSession.m:11394"
+ "LastShownBuild:FigCaptureSession.m:11589"
+ "LastShownBuild:FigCaptureSession.m:19395"
+ "LastShownBuild:FigCaptureSession.m:20960"
+ "LastShownBuild:FigCaptureSession.m:20963"
+ "LastShownBuild:FigCaptureSession.m:26353"
+ "LastShownBuild:FigCaptureSession.m:29436"
+ "LastShownBuild:FigCaptureSession.m:5225"
+ "LastShownBuild:FigCaptureSession.m:9293"
+ "LastShownBuild:FigCaptureSession.m:9299"
+ "LastShownBuild:FigCaptureSession.m:9302"
+ "LastShownBuild:FigCaptureSession.m:9305"
+ "LastShownBuild:FigCaptureSession.m:9308"
+ "LastShownBuild:FigCaptureSession.m:9319"
+ "LastShownBuild:FigCaptureSession.m:9322"
+ "LastShownBuild:FigCaptureSession.m:9330"
+ "LastShownBuild:FigCaptureSession.m:9348"
+ "LastShownBuild:FigCaptureSession.m:9393"
+ "LastShownBuild:FigCaptureSession.m:9397"
+ "LastShownBuild:FigCaptureSession.m:9421"
+ "LastShownBuild:FigCaptureSession.m:9436"
+ "LastShownBuild:FigCaptureSession.m:9440"
+ "LastShownBuild:FigCaptureSession.m:9443"
+ "LastShownBuild:FigCaptureSession.m:9567"
+ "LastShownBuild:FigCaptureSession.m:9573"
+ "LastShownBuild:FigCaptureSession.m:9599"
+ "LastShownBuild:FigCaptureSession.m:9611"
+ "LastShownDate:BWHVSScoringNode.m:1205"
+ "LastShownDate:BWHVSScoringNode.m:2906"
+ "LastShownDate:BWHVSScoringNode.m:2911"
+ "LastShownDate:BWHVSScoringNode.m:2914"
+ "LastShownDate:BWHVSScoringNode.m:2983"
+ "LastShownDate:BWHVSScoringNode.m:3503"
+ "LastShownDate:BWMultiStreamCameraSourceNode.m:13942"
+ "LastShownDate:BWMultiStreamCameraSourceNode.m:13958"
+ "LastShownDate:BWStillImageCoordinatorNode.m:1480"
+ "LastShownDate:BWStillImageCoordinatorNode.m:1487"
+ "LastShownDate:BWStillImageCoordinatorNode.m:1557"
+ "LastShownDate:BWStillImageCoordinatorNode.m:1663"
+ "LastShownDate:BWStillImageCoordinatorNode.m:1674"
+ "LastShownDate:BWStillImageCoordinatorNode.m:2320"
+ "LastShownDate:BWStillImageCoordinatorNode.m:3975"
+ "LastShownDate:FigCaptureSession.m:1018"
+ "LastShownDate:FigCaptureSession.m:11394"
+ "LastShownDate:FigCaptureSession.m:11589"
+ "LastShownDate:FigCaptureSession.m:19395"
+ "LastShownDate:FigCaptureSession.m:20960"
+ "LastShownDate:FigCaptureSession.m:20963"
+ "LastShownDate:FigCaptureSession.m:26353"
+ "LastShownDate:FigCaptureSession.m:29436"
+ "LastShownDate:FigCaptureSession.m:5225"
+ "LastShownDate:FigCaptureSession.m:9293"
+ "LastShownDate:FigCaptureSession.m:9299"
+ "LastShownDate:FigCaptureSession.m:9302"
+ "LastShownDate:FigCaptureSession.m:9305"
+ "LastShownDate:FigCaptureSession.m:9308"
+ "LastShownDate:FigCaptureSession.m:9319"
+ "LastShownDate:FigCaptureSession.m:9322"
+ "LastShownDate:FigCaptureSession.m:9330"
+ "LastShownDate:FigCaptureSession.m:9348"
+ "LastShownDate:FigCaptureSession.m:9393"
+ "LastShownDate:FigCaptureSession.m:9397"
+ "LastShownDate:FigCaptureSession.m:9421"
+ "LastShownDate:FigCaptureSession.m:9436"
+ "LastShownDate:FigCaptureSession.m:9440"
+ "LastShownDate:FigCaptureSession.m:9443"
+ "LastShownDate:FigCaptureSession.m:9567"
+ "LastShownDate:FigCaptureSession.m:9573"
+ "LastShownDate:FigCaptureSession.m:9599"
+ "LastShownDate:FigCaptureSession.m:9611"
+ "LightSourceEstimation"
+ "MachThreadPriorityForThreadEmittingFrames"
+ "Oct  8 2026"
+ "SupportedMetadataIdentifiersForPerceptionThumbnailChannel"
+ "bwmscsn_printMetadataPayload"
+ "com.apple.ClockFacePosters.DimensionalAnalogPosterExtension"
+ "com.apple.VoiceOverTouch"
+ "com.apple.coremedia.deferred.containermanager.flush.reduced-priority"
+ "com.apple.fatool"
+ "com.apple.homepodsensed"
+ "com.apple.perceptiond"
+ "description=CameraCapture-764.41.11"
+ "deviceProximityDetection"
+ "deviceProximityDetectionDeviceTypes"
+ "deviceProximityDetectionSupported"
+ "deviceProximityDetectionTargetFrameRate"
+ "deviceProximityDetectionTargetFrameRate (%g -> %g)"
+ "lightSourceEstimation"
+ "lightSourceEstimationAmbientLuminance"
+ "lightSourceEstimationAmbientLuminance (%u -> %u)"
+ "lightSourceEstimationTargetFrameRate"
+ "lightSourceEstimationTargetFrameRate (%g -> %g)"
+ "lite_shareddata"
+ "metadataIdentifiersForPerceptionThumbnailChannel"
+ "perceptionTestModeEnabled"
+ "perceptionTestModeEnabled (%d -> %d)"
+ "perceptionThumbnailChannelSupported"
+ "tracked_faces"
- "21:19:53"
- "LastShownBuild:BWHVSScoringNode.m:1194"
- "LastShownBuild:BWHVSScoringNode.m:2806"
- "LastShownBuild:BWHVSScoringNode.m:2811"
- "LastShownBuild:BWHVSScoringNode.m:2814"
- "LastShownBuild:BWHVSScoringNode.m:2883"
- "LastShownBuild:BWHVSScoringNode.m:3403"
- "LastShownBuild:BWMultiStreamCameraSourceNode.m:13947"
- "LastShownBuild:BWMultiStreamCameraSourceNode.m:13963"
- "LastShownBuild:BWStillImageCoordinatorNode.m:1465"
- "LastShownBuild:BWStillImageCoordinatorNode.m:1472"
- "LastShownBuild:BWStillImageCoordinatorNode.m:1542"
- "LastShownBuild:BWStillImageCoordinatorNode.m:1648"
- "LastShownBuild:BWStillImageCoordinatorNode.m:1659"
- "LastShownBuild:BWStillImageCoordinatorNode.m:2305"
- "LastShownBuild:BWStillImageCoordinatorNode.m:3946"
- "LastShownBuild:FigCaptureSession.m:1017"
- "LastShownBuild:FigCaptureSession.m:11383"
- "LastShownBuild:FigCaptureSession.m:11578"
- "LastShownBuild:FigCaptureSession.m:19384"
- "LastShownBuild:FigCaptureSession.m:20949"
- "LastShownBuild:FigCaptureSession.m:20952"
- "LastShownBuild:FigCaptureSession.m:26327"
- "LastShownBuild:FigCaptureSession.m:29423"
- "LastShownBuild:FigCaptureSession.m:5224"
- "LastShownBuild:FigCaptureSession.m:9292"
- "LastShownBuild:FigCaptureSession.m:9298"
- "LastShownBuild:FigCaptureSession.m:9301"
- "LastShownBuild:FigCaptureSession.m:9304"
- "LastShownBuild:FigCaptureSession.m:9307"
- "LastShownBuild:FigCaptureSession.m:9318"
- "LastShownBuild:FigCaptureSession.m:9321"
- "LastShownBuild:FigCaptureSession.m:9329"
- "LastShownBuild:FigCaptureSession.m:9347"
- "LastShownBuild:FigCaptureSession.m:9392"
- "LastShownBuild:FigCaptureSession.m:9396"
- "LastShownBuild:FigCaptureSession.m:9420"
- "LastShownBuild:FigCaptureSession.m:9435"
- "LastShownBuild:FigCaptureSession.m:9439"
- "LastShownBuild:FigCaptureSession.m:9442"
- "LastShownBuild:FigCaptureSession.m:9566"
- "LastShownBuild:FigCaptureSession.m:9572"
- "LastShownBuild:FigCaptureSession.m:9598"
- "LastShownBuild:FigCaptureSession.m:9610"
- "LastShownDate:BWHVSScoringNode.m:1194"
- "LastShownDate:BWHVSScoringNode.m:2806"
- "LastShownDate:BWHVSScoringNode.m:2811"
- "LastShownDate:BWHVSScoringNode.m:2814"
- "LastShownDate:BWHVSScoringNode.m:2883"
- "LastShownDate:BWHVSScoringNode.m:3403"
- "LastShownDate:BWMultiStreamCameraSourceNode.m:13947"
- "LastShownDate:BWMultiStreamCameraSourceNode.m:13963"
- "LastShownDate:BWStillImageCoordinatorNode.m:1465"
- "LastShownDate:BWStillImageCoordinatorNode.m:1472"
- "LastShownDate:BWStillImageCoordinatorNode.m:1542"
- "LastShownDate:BWStillImageCoordinatorNode.m:1648"
- "LastShownDate:BWStillImageCoordinatorNode.m:1659"
- "LastShownDate:BWStillImageCoordinatorNode.m:2305"
- "LastShownDate:BWStillImageCoordinatorNode.m:3946"
- "LastShownDate:FigCaptureSession.m:1017"
- "LastShownDate:FigCaptureSession.m:11383"
- "LastShownDate:FigCaptureSession.m:11578"
- "LastShownDate:FigCaptureSession.m:19384"
- "LastShownDate:FigCaptureSession.m:20949"
- "LastShownDate:FigCaptureSession.m:20952"
- "LastShownDate:FigCaptureSession.m:26327"
- "LastShownDate:FigCaptureSession.m:29423"
- "LastShownDate:FigCaptureSession.m:5224"
- "LastShownDate:FigCaptureSession.m:9292"
- "LastShownDate:FigCaptureSession.m:9298"
- "LastShownDate:FigCaptureSession.m:9301"
- "LastShownDate:FigCaptureSession.m:9304"
- "LastShownDate:FigCaptureSession.m:9307"
- "LastShownDate:FigCaptureSession.m:9318"
- "LastShownDate:FigCaptureSession.m:9321"
- "LastShownDate:FigCaptureSession.m:9329"
- "LastShownDate:FigCaptureSession.m:9347"
- "LastShownDate:FigCaptureSession.m:9392"
- "LastShownDate:FigCaptureSession.m:9396"
- "LastShownDate:FigCaptureSession.m:9420"
- "LastShownDate:FigCaptureSession.m:9435"
- "LastShownDate:FigCaptureSession.m:9439"
- "LastShownDate:FigCaptureSession.m:9442"
- "LastShownDate:FigCaptureSession.m:9566"
- "LastShownDate:FigCaptureSession.m:9572"
- "LastShownDate:FigCaptureSession.m:9598"
- "LastShownDate:FigCaptureSession.m:9610"
- "Sep 28 2026"
- "description=CameraCapture-764.40.7"
```
