## CMCapture

> `/System/Library/PrivateFrameworks/CMCapture.framework/Versions/A/CMCapture`

```diff

 764.21.3.0.0
-  __TEXT.__text: 0x3c6444
-  __TEXT.__objc_methlist: 0x283c4
-  __TEXT.__const: 0x142f38
-  __TEXT.__cstring: 0x6190d
-  __TEXT.__oslogstring: 0x2c433
-  __TEXT.__gcc_except_tab: 0x15e4
+  __TEXT.__text: 0x40e500
+  __TEXT.__objc_methlist: 0x2ac7c
+  __TEXT.__const: 0x143060
+  __TEXT.__cstring: 0x67742
+  __TEXT.__oslogstring: 0x2edd8
+  __TEXT.__gcc_except_tab: 0x16a0
   __TEXT.__dlopen_cstrs: 0x23e
   __TEXT.__ustring: 0xc
-  __TEXT.__unwind_info: 0x9948
+  __TEXT.__unwind_info: 0xa1f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x5718
-  __DATA_CONST.__objc_classlist: 0x1308
+  __DATA_CONST.__const: 0x6168
+  __DATA_CONST.__objc_classlist: 0x13f8
   __DATA_CONST.__objc_catlist: 0x18
-  __DATA_CONST.__objc_protolist: 0x330
+  __DATA_CONST.__objc_protolist: 0x378
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x119c0
+  __DATA_CONST.__objc_selrefs: 0x12be0
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x11b0
-  __DATA_CONST.__objc_arraydata: 0x1598
-  __DATA_CONST.__got: 0x6148
-  __AUTH_CONST.__const: 0x5228
-  __AUTH_CONST.__cfstring: 0x38fe0
-  __AUTH_CONST.__objc_const: 0x711b0
-  __AUTH_CONST.__objc_intobj: 0x3b70
-  __AUTH_CONST.__objc_arrayobj: 0x1170
-  __AUTH_CONST.__objc_floatobj: 0x170
-  __AUTH_CONST.__objc_doubleobj: 0x200
-  __AUTH_CONST.__objc_dictobj: 0xf0
-  __AUTH_CONST.__auth_got: 0x20b8
-  __AUTH.__objc_data: 0x25d0
+  __DATA_CONST.__objc_superrefs: 0x12a0
+  __DATA_CONST.__objc_arraydata: 0x1688
+  __DATA_CONST.__got: 0x66c0
+  __AUTH_CONST.__const: 0x5570
+  __AUTH_CONST.__cfstring: 0x3dd20
+  __AUTH_CONST.__objc_const: 0x78d00
+  __AUTH_CONST.__objc_intobj: 0x4110
+  __AUTH_CONST.__objc_arrayobj: 0x1218
+  __AUTH_CONST.__objc_floatobj: 0x1b0
+  __AUTH_CONST.__objc_doubleobj: 0x280
+  __AUTH_CONST.__objc_dictobj: 0x118
+  __AUTH_CONST.__auth_got: 0x2198
+  __AUTH.__objc_data: 0x2f30
   __AUTH.__data: 0x110
-  __DATA.__objc_ivar: 0x8778
-  __DATA.__data: 0x283c
-  __DATA.__common: 0xd40
-  __DATA.__bss: 0x1150
+  __DATA.__objc_ivar: 0x91a0
+  __DATA.__data: 0x2bfc
+  __DATA.__common: 0xe80
+  __DATA.__bss: 0x11a8
   __DATA_DIRTY.__objc_data: 0x9880
-  __DATA_DIRTY.__data: 0xfa8
+  __DATA_DIRTY.__data: 0x1048
   __DATA_DIRTY.__common: 0x120
-  __DATA_DIRTY.__bss: 0xa20
+  __DATA_DIRTY.__bss: 0xa30
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 23367
-  Symbols:   46274
-  CStrings:  12883
+  Functions: 24846
+  Symbols:   49390
+  CStrings:  13743
 
Symbols:
+ +[BWBaselineTextureStyleRenderer initialize]
+ +[BWBaselineTextureStyleRenderer requiredSharedMetalAllocatorBackendSizeWithProcessorVersion:]
+ +[BWCinematographyObjectTrackingNode initialize]
+ +[BWGlobalTextureStyleRenderer initialize]
+ +[BWGlobalTextureStyleRenderer requiredSharedMetalAllocatorBackendSizeWithProcessorVersion:]
+ +[BWGlowTextureStyleRenderer initialize]
+ +[BWGlowTextureStyleRenderer requiredSharedMetalAllocatorBackendSizeWithProcessorVersion:]
+ +[BWHVSCandidateFrameManager initialize]
+ +[BWHVSFrame initialize]
+ +[BWHVSObject initialize]
+ +[BWHVSScoringNode initialize]
+ +[BWLCBDatabaseManager initialize]
+ +[BWLCBDatabaseManager sharedManager]
+ +[BWMultiCamConfiguration configurationWithUnsynchronizedActiveStreamsPortTypes:synchronizedActiveStreamsGroupsPortTypes:mutuallyExclusiveUnsynchronizedStreamsPortTypes:stereoVideoCaptureEnabled:multiCamClientCompositingEnabled:colorAssistedSecureFaceIDEnabled:secureProcessingCoexEnabled:exclusivelyForSecureProcessing:builtInMicrophoneIsRecording:]
+ +[BWPersonalPhotographerSceneMonitorV1 initialize]
+ +[BWSecureSigningUtilityManager sharedManager]
+ +[BWSemanticMasksConverterNode initialize]
+ +[BWSensorRawTimeMachine initialize]
+ +[BWSkinTextureStyleRenderer initialize]
+ +[BWSkinTextureStyleRenderer requiredSharedMetalAllocatorBackendSizeWithProcessorVersion:]
+ +[BWStillImageDuplicateInfo supportsSecureCoding]
+ +[BWTextureStyleInfoMetadataNode initialize]
+ +[BWTextureStyleTuning captureTypeToString:]
+ +[BWTextureStyleTuning filmGrainSeedForCaptureRequestIdentifier:]
+ +[BWTextureStyleTuning initialize]
+ +[BWTextureStyleTuning parametersForPortType:captureMode:captureType:preset:]
+ +[BWTextureStyleTuning setup]
+ +[BWTextureStyleTuning unstyledImageRequiredForReversibility:]
+ +[BWTimewarpMetadataNode initialize]
+ +[BWVideoNoiseReductionNode initialize]
+ +[FigCaptureAngleMonitor initialize]
+ +[FigCaptureCameraSourcePipeline _trueVideoOverscanForDevicePosition:type:photoGraphVideoZoomFactor:]
+ +[FigCaptureCustomExposureConfiguration exposureConfigurationWithExposureDuration:minFrameRate:maxFrameRate:ISO:lensAperture:useSpotMetering:requestID:]
+ +[FigCaptureCustomExposureConfiguration exposureConfigurationWithFullAutoForPortTypes:]
+ +[FigCaptureExposureLimits apertureLimitsForStream:]
+ +[FigCaptureMagneticInterferenceMonitor initialize]
+ +[FigCaptureTextureStyle createFromDictionary:]
+ +[FigCaptureTextureStyle identityStyle]
+ +[FigCaptureTextureStyle styleWithPreset:intensity:grain:]
+ +[FigCaptureTextureStyle supportsSecureCoding]
+ -[BWAudioConverterNode movieRecordingEndOfDataBehavior]
+ -[BWAudioConverterNode setMovieRecordingEndOfDataBehavior:]
+ -[BWBaselineTextureStyleRenderer _attachedMediaKeyForMaskType:]
+ -[BWBaselineTextureStyleRenderer _mergeImageStatsIntoPeopleData:]
+ -[BWBaselineTextureStyleRenderer _setupCommonInputsFromSampleBuffer:inputPixelBuffer:processedPixelBuffer:]
+ -[BWBaselineTextureStyleRenderer _setupFilmGrainFromSampleBuffer:effectsToRender:presetTuningParameters:totalGain:]
+ -[BWBaselineTextureStyleRenderer _setupMaskFromSampleBuffer:maskType:]
+ -[BWBaselineTextureStyleRenderer _setupMasksFromSampleBuffer:]
+ -[BWBaselineTextureStyleRenderer _setupPersonDataFromSampleBuffer:]
+ -[BWBaselineTextureStyleRenderer _setupProcessorFullImageSizeAndRegionToRenderFromSampleBuffer:inputPixelBuffer:]
+ -[BWBaselineTextureStyleRenderer _setupSkinMaskFromSampleBuffer:maskType:]
+ -[BWBaselineTextureStyleRenderer _setupSkinSmoothingInEffectsToRender:presetTuningParameters:totalGain:]
+ -[BWBaselineTextureStyleRenderer adjustMetadataOfSampleBuffer:]
+ -[BWBaselineTextureStyleRenderer adjustsMetadata]
+ -[BWBaselineTextureStyleRenderer dealloc]
+ -[BWBaselineTextureStyleRenderer displayName]
+ -[BWBaselineTextureStyleRenderer initWithConfiguration:]
+ -[BWBaselineTextureStyleRenderer isMetalRenderer]
+ -[BWBaselineTextureStyleRenderer isPassThroughRenderer]
+ -[BWBaselineTextureStyleRenderer prepareForRenderingWithParameters:inputVideoFormat:inputMediaPropertiesByAttachedMediaKey:]
+ -[BWBaselineTextureStyleRenderer renderUsingParameters:inputPixelBuffer:inputSampleBuffer:processedPixelBuffer:completionHandler:]
+ -[BWBaselineTextureStyleRenderer supportsAnimation]
+ -[BWBaselineTextureStyleRenderer type]
+ -[BWBaselineTextureStyleRenderer waitForMetalCompletion]
+ -[BWCinematicVideoMetadataNode _renderSampleBufferWhenDisabled:]
+ -[BWCinematicVideoMetadataNode disabled]
+ -[BWCinematicVideoMetadataNode setDisabled:]
+ -[BWCinematicVideoMetadataNode setUseRawCinematography:]
+ -[BWCinematicVideoMetadataNode useRawCinematography]
+ -[BWCinematographyObjectTrackingNode cinematographyModelVersionString]
+ -[BWCinematographyObjectTrackingNode disabled]
+ -[BWCinematographyObjectTrackingNode globalMetadata]
+ -[BWCinematographyObjectTrackingNode initWithCaptureDevice:tuningParameters:inferenceScheduler:frameRate:prepareCinematographyOnInit:]
+ -[BWCinematographyObjectTrackingNode metadataCollectionSize]
+ -[BWCinematographyObjectTrackingNode setDisabled:]
+ -[BWCinematographyObjectTrackingNode setMetadataCollectionSize:]
+ -[BWDeferredPipelineParameters portTypesWithTextureStyleBaseLookEnabled]
+ -[BWDeferredPipelineParameters setPortTypesWithTextureStyleBaseLookEnabled:]
+ -[BWDeferredPipelineParameters setTextureStyleBaseLookEnabled:]
+ -[BWDeferredPipelineParameters setTextureStyleCreativeEffectsEnabled:]
+ -[BWDeferredPipelineParameters setTextureStyleFSINCMasksRequired:]
+ -[BWDeferredPipelineParameters setTextureStyleRenderingVersion:]
+ -[BWDeferredPipelineParameters textureStyleBaseLookEnabled]
+ -[BWDeferredPipelineParameters textureStyleCreativeEffectsEnabled]
+ -[BWDeferredPipelineParameters textureStyleFSINCMasksRequired]
+ -[BWDeferredPipelineParameters textureStyleRenderingVersion]
+ -[BWFigCaptureSession hvsScoringNode:didFinishPersonalPhotographerSessionWithCapturesToKeep:capturesToDelete:stillImageCoordinatorNode:settings:]
+ -[BWFigCaptureSession previewStabilizationNode:didApplyPreviewStabilizationShift:forPortType:]
+ -[BWFigVideoCaptureDevice _applySystemPressureFrameRateMitigationIfNeeded:]
+ -[BWFigVideoCaptureDevice _initWithCaptureDevice:attributes:synchronizedStreamsAttributes:unsynchronizedStreamsAttributes:multiCamEnabled:midFrameSynchronizationEnabled:superWideAsMidFrameSynchronizationPrimary:secureFaceIDEnabled:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:deviceVendor:createAutofocusSampleBufferProcessorFunction:cameraParameters:deviceClientPriority:error:]
+ -[BWFigVideoCaptureDevice _omahaUpdateSensorRawPoolsRequirements:]
+ -[BWFigVideoCaptureDevice _overrideIgnoredExposureSignals:values:]
+ -[BWFigVideoCaptureDevice _prepareStreamsForCurrentTimewarpMode]
+ -[BWFigVideoCaptureDevice _servicePersonalPhotographerSceneMonitoringWithCaptureStream:sampleBuffer:frameStatisticsByPortType:]
+ -[BWFigVideoCaptureDevice _smartFramingSceneMonitorMode]
+ -[BWFigVideoCaptureDevice _ubHighResolutionNondisruptiveSwitchingFormatIndexForCaptureStream:highResolutionSecureSigningNondisruptiveStreamingFormatIndexOut:]
+ -[BWFigVideoCaptureDevice _underlyingOmahaDeviceSupportsUltraHighResolutionForPortType:]
+ -[BWFigVideoCaptureDevice _updateCameraControlsSemanticHintsStreamPropertyIfNeededWithSemanticHints:]
+ -[BWFigVideoCaptureDevice _updateDocumentScanExposureSignalOverrideForStream:zoom:]
+ -[BWFigVideoCaptureDevice _updateIgnoredExposureSignals]
+ -[BWFigVideoCaptureDevice _updatePersonalPhotographerStatus:]
+ -[BWFigVideoCaptureDevice _updateResolvedIgnoredExposureSignals]
+ -[BWFigVideoCaptureDevice _updateSecureSigningClientProvidedHash:]
+ -[BWFigVideoCaptureDevice activeExposureSignals]
+ -[BWFigVideoCaptureDevice activeOmahaConstituentDeviceType]
+ -[BWFigVideoCaptureDevice activeZeroShutterLagFlavorHighResolutionFlavor]
+ -[BWFigVideoCaptureDevice adjustedAspectRatioForActiveOmahaConstituentDevice]
+ -[BWFigVideoCaptureDevice apertureControlSceneMonitorEnabled]
+ -[BWFigVideoCaptureDevice autoFullFullUltraHighResolutionZeroShutterLagEnabledByOmahaConstituentPortType]
+ -[BWFigVideoCaptureDevice autoFullFullUltraHighResolutionZeroShutterLagEnabled]
+ -[BWFigVideoCaptureDevice automaticallyIgnoresExposureSignals]
+ -[BWFigVideoCaptureDevice calibrationCaptureSettingsWithSettingsID:]
+ -[BWFigVideoCaptureDevice continuousAutoFocusDidAcquireSubject:]
+ -[BWFigVideoCaptureDevice continuousAutoFocusTrackingChangedDelegate]
+ -[BWFigVideoCaptureDevice depthSupportedWithUltraHighResolutionCaptures]
+ -[BWFigVideoCaptureDevice exposureSignalsRequireApertureControlSceneMonitor:]
+ -[BWFigVideoCaptureDevice ignoredExposureSignals]
+ -[BWFigVideoCaptureDevice initWithCaptureDevice:attributes:synchronizedStreamsAttributes:unsynchronizedStreamsAttributes:multiCamEnabled:midFrameSynchronizationEnabled:superWideAsMidFrameSynchronizationPrimary:secureFaceIDEnabled:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:deviceClientPriority:error:]
+ -[BWFigVideoCaptureDevice isOmahaVariant]
+ -[BWFigVideoCaptureDevice isShutterSoundRelaxationEnabledForDisplayRegion]
+ -[BWFigVideoCaptureDevice isTimewarpEnabled]
+ -[BWFigVideoCaptureDevice lcbDatabaseManager:didUpdateDatabase:forPortType:]
+ -[BWFigVideoCaptureDevice lensAperture]
+ -[BWFigVideoCaptureDevice lowLightVideoNoiseReductionEnabled]
+ -[BWFigVideoCaptureDevice magneticInterferenceDetected]
+ -[BWFigVideoCaptureDevice magneticInterferenceMonitor]
+ -[BWFigVideoCaptureDevice omahaConstituentDeviceLiveReconfigurationInProgress]
+ -[BWFigVideoCaptureDevice omahaRenoAngleWithinDropZone]
+ -[BWFigVideoCaptureDevice omahaRotationOffsetDegreesForPortType:]
+ -[BWFigVideoCaptureDevice personalPhotographerEnabled]
+ -[BWFigVideoCaptureDevice releaseFaceIDFrameProxyWithIdentifier:]
+ -[BWFigVideoCaptureDevice resolvedIgnoredExposureSignals]
+ -[BWFigVideoCaptureDevice secureSigningPhotoCaptureEnabled]
+ -[BWFigVideoCaptureDevice secureSigningPhotoCaptureSupportEnabled]
+ -[BWFigVideoCaptureDevice secureSigningUtilityManager:didUpdateClientProvidedHash:]
+ -[BWFigVideoCaptureDevice setActiveOmahaConstituentDeviceType:]
+ -[BWFigVideoCaptureDevice setActiveZeroShutterLagFlavorHighResolutionFlavor:]
+ -[BWFigVideoCaptureDevice setApertureControlSceneMonitorEnabled:]
+ -[BWFigVideoCaptureDevice setAutoExposureLensApertureRateLimit:]
+ -[BWFigVideoCaptureDevice setAutoFullFullUltraHighResolutionZeroShutterLagEnabled:]
+ -[BWFigVideoCaptureDevice setAutoFullFullUltraHighResolutionZeroShutterLagEnabledByOmahaConstituentPortType:]
+ -[BWFigVideoCaptureDevice setAutomaticallyIgnoresExposureSignals:]
+ -[BWFigVideoCaptureDevice setContinuousAutoFocusTrackingChangedDelegate:]
+ -[BWFigVideoCaptureDevice setDepthSupportedWithUltraHighResolutionCaptures:]
+ -[BWFigVideoCaptureDevice setFocusModeAutoWithRect:restrictToRect:continuous:smooth:tracking:trackingLensPositionBias:trackingSeedingPoint:rangeRestrictionNear:rangeRestrictionFar:isFocusRectInOverscanSpace:]
+ -[BWFigVideoCaptureDevice setIgnoredExposureSignals:]
+ -[BWFigVideoCaptureDevice setLowLightVideoNoiseReductionEnabled:]
+ -[BWFigVideoCaptureDevice setMagneticInterferenceDetected:]
+ -[BWFigVideoCaptureDevice setMagneticInterferenceMonitor:]
+ -[BWFigVideoCaptureDevice setNondisruptiveSwitchingFormatIndicesByZoomFactorSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorMainAndSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorSIFRNonBinned:nondisruptiveSwitchingFormatIndicesByZoomfactorSecureSigning:ultraHighResolutionSecureSigningNondisruptiveStreamingFormatIndex:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:forPortType:quadraSubPixelSwitchingParameters:]
+ -[BWFigVideoCaptureDevice setOmahaConstituentDeviceLiveReconfigurationInProgress:]
+ -[BWFigVideoCaptureDevice setOmahaRenoAngleWithinDropZone:]
+ -[BWFigVideoCaptureDevice setPersonalPhotographerEnabled:]
+ -[BWFigVideoCaptureDevice setSecureSigningPhotoCaptureEnabled:]
+ -[BWFigVideoCaptureDevice setSecureSigningPhotoCaptureSupportEnabled:]
+ -[BWFigVideoCaptureDevice setShutterSoundRelaxationEnabledForDisplayRegion:]
+ -[BWFigVideoCaptureDevice setTimewarpEnabled:]
+ -[BWFigVideoCaptureDevice setTimewarpMode:]
+ -[BWFigVideoCaptureDevice setUltraHighResolutionZeroShutterLagSupportEnabledByOmahaConstituentPortType:]
+ -[BWFigVideoCaptureDevice setZeroShutterLagEnabledByOmahaConstituentPortType:]
+ -[BWFigVideoCaptureDevice setZeroShutterLagTimeMachineBufferCapacityByOmahaConstituentPortType:]
+ -[BWFigVideoCaptureDevice supportedExposureSignals]
+ -[BWFigVideoCaptureDevice timewarpMode]
+ -[BWFigVideoCaptureDevice ultraHighResolutionZeroShutterLagSupportEnabledByOmahaConstituentPortType]
+ -[BWFigVideoCaptureDevice updateHVSDetectionInfo:forChangedKeys:]
+ -[BWFigVideoCaptureDevice zeroShutterLagEnabledByOmahaConstituentPortType]
+ -[BWFigVideoCaptureDevice zeroShutterLagTimeMachineBufferCapacityByOmahaConstituentPortType]
+ -[BWFigVideoCaptureStream _setActiveNondisruptiveSwitchingFormatIndex:secureSigningMode:]
+ -[BWFigVideoCaptureStream _setActiveNondisruptiveSwitchingFormatIndex:secureSigningMode:maximumAllowedFrameRate:minimumFrameRate:maximumFrameRate:]
+ -[BWFigVideoCaptureStream autoExposureLensApertureRateLimit]
+ -[BWFigVideoCaptureStream automaticallyIgnoredExposureSignals]
+ -[BWFigVideoCaptureStream captureFaceIDBracketWithConfiguration:]
+ -[BWFigVideoCaptureStream defaultLensAperture]
+ -[BWFigVideoCaptureStream faceImageQualityDetectionEnabled]
+ -[BWFigVideoCaptureStream hasSecureSigningNondisruptiveFormats]
+ -[BWFigVideoCaptureStream ignoredExposureSignals]
+ -[BWFigVideoCaptureStream initWithCaptureStream:parentDevice:attributes:sensorIDDictionary:synchronizedStreamsGroup:isOmahaVariant:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:error:]
+ -[BWFigVideoCaptureStream magneticInterferenceDetected]
+ -[BWFigVideoCaptureStream maxLensAperture]
+ -[BWFigVideoCaptureStream minLensAperture]
+ -[BWFigVideoCaptureStream releaseFaceIDFrameProxyWithIdentifier:]
+ -[BWFigVideoCaptureStream serviceNondisruptiveSwitchingFormatForZoomFactor:frameStatistics:imageControlMode:stillImageDigitalFlashMode:isStationary:binnedSIFROnSecondaryStreamAllowed:ignoreZoomFactorAndQuadraSubPixelSceneMonitoring:secureSigningMode:ultraHighResolutionZeroShutterLagEnabled:]
+ -[BWFigVideoCaptureStream setAutoExposureLensApertureRateLimit:]
+ -[BWFigVideoCaptureStream setFaceImageQualityDetectionEnabled:]
+ -[BWFigVideoCaptureStream setIgnoredExposureSignals:]
+ -[BWFigVideoCaptureStream setMagneticInterferenceDetected:]
+ -[BWFigVideoCaptureStream setTimewarpEnabled:]
+ -[BWFigVideoCaptureStream setZoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSecureSigning:ultraHighResolutionSecureSigningNondisruptiveStreamingFormatIndex:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:quadraSubPixelSwitchingParameters:]
+ -[BWFigVideoCaptureStream supportedExposureSignals]
+ -[BWFigVideoCaptureStream timewarpEnabled]
+ -[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:cinematicAudioEnabled:allowLowLatencyWhenPossible:timewarpTargetFramerate:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:]
+ -[BWFileCoordinatorNode movieRecordingEndOfDataBehavior]
+ -[BWFileCoordinatorNode setMovieRecordingEndOfDataBehavior:]
+ -[BWFrameStatistics defaultFNumber]
+ -[BWFrameStatistics exposureSignals]
+ -[BWFrameStatistics fNumber]
+ -[BWFrameStatistics initWthPortType:defaultFNumber:storage:]
+ -[BWFrameStatistics normalizedEITUsingFrameMetadata:]
+ -[BWFrameStatisticsByPortType initWithPortTypes:defaultFNumberByPortType:autoFocusRecommendedPrimaryPortTypeEnabled:]
+ -[BWGlobalTextureStyleRenderer _resolveRenderOrderFromEffectOrder:enabledEffects:]
+ -[BWGlobalTextureStyleRenderer _setupBloomFromSampleBuffer:effectsToRender:presetTuningParameters:]
+ -[BWGlobalTextureStyleRenderer _setupCommonInputsFromSampleBuffer:inputPixelBuffer:outputPixelBuffer:]
+ -[BWGlobalTextureStyleRenderer _setupDiffusionFromSampleBuffer:effectsToRender:presetTuningParameters:]
+ -[BWGlobalTextureStyleRenderer _setupFilmGrainFromSampleBuffer:effectsToRender:presetTuningParameters:smartStyle:totalGain:]
+ -[BWGlobalTextureStyleRenderer _setupGainMapFromSampleBuffer:meteorHeadroom:]
+ -[BWGlobalTextureStyleRenderer _setupHalationFromSampleBuffer:effectsToRender:presetTuningParameters:smartStyle:]
+ -[BWGlobalTextureStyleRenderer _setupPersonMaskFromSampleBuffer:]
+ -[BWGlobalTextureStyleRenderer _setupProcessorFullImageSizeAndRegionToRenderFromSampleBuffer:inputPixelBuffer:]
+ -[BWGlobalTextureStyleRenderer _setupSkinMaskFromSampleBuffer:]
+ -[BWGlobalTextureStyleRenderer _setupSkyMaskFromSampleBuffer:]
+ -[BWGlobalTextureStyleRenderer adjustMetadataOfSampleBuffer:]
+ -[BWGlobalTextureStyleRenderer adjustsMetadata]
+ -[BWGlobalTextureStyleRenderer dealloc]
+ -[BWGlobalTextureStyleRenderer displayName]
+ -[BWGlobalTextureStyleRenderer initWithConfiguration:]
+ -[BWGlobalTextureStyleRenderer isMetalRenderer]
+ -[BWGlobalTextureStyleRenderer isPassThroughRenderer]
+ -[BWGlobalTextureStyleRenderer prepareForRenderingWithParameters:inputVideoFormat:inputMediaPropertiesByAttachedMediaKey:]
+ -[BWGlobalTextureStyleRenderer renderUsingParameters:inputPixelBuffer:inputSampleBuffer:processedPixelBuffer:completionHandler:]
+ -[BWGlobalTextureStyleRenderer supportsAnimation]
+ -[BWGlobalTextureStyleRenderer type]
+ -[BWGlobalTextureStyleRenderer waitForMetalCompletion]
+ -[BWGlowTextureStyleRenderer _populateInputLinearPixelBufferColorManagementMetadata:]
+ -[BWGlowTextureStyleRenderer _setupCommonInputsFromSampleBuffer:inputPixelBuffer:outputPixelBuffer:]
+ -[BWGlowTextureStyleRenderer _setupGlowFromSampleBuffer:styledThumbnailSampleBuffer:effectsToRender:presetTuningParameters:]
+ -[BWGlowTextureStyleRenderer _setupLinearImageFromSampleBuffer:]
+ -[BWGlowTextureStyleRenderer _setupPersonMaskFromSampleBuffer:]
+ -[BWGlowTextureStyleRenderer _setupProcessorFullImageSizeAndRegionToRenderFromPixelBuffer:]
+ -[BWGlowTextureStyleRenderer adjustMetadataOfSampleBuffer:]
+ -[BWGlowTextureStyleRenderer adjustsMetadata]
+ -[BWGlowTextureStyleRenderer dealloc]
+ -[BWGlowTextureStyleRenderer displayName]
+ -[BWGlowTextureStyleRenderer initWithConfiguration:]
+ -[BWGlowTextureStyleRenderer isMetalRenderer]
+ -[BWGlowTextureStyleRenderer isPassThroughRenderer]
+ -[BWGlowTextureStyleRenderer prepareForRenderingWithParameters:inputVideoFormat:inputMediaPropertiesByAttachedMediaKey:]
+ -[BWGlowTextureStyleRenderer renderUsingParameters:inputPixelBuffer:inputSampleBuffer:processedPixelBuffer:completionHandler:]
+ -[BWGlowTextureStyleRenderer supportsAnimation]
+ -[BWGlowTextureStyleRenderer type]
+ -[BWGlowTextureStyleRenderer waitForMetalCompletion]
+ -[BWGraph startLiveExtensionSourceNodes]
+ -[BWGraph stopLiveExtensionSourceNodes]
+ -[BWHVSCandidateFrameManager .cxx_destruct]
+ -[BWHVSCandidateFrameManager _analyzeDuplicateChains]
+ -[BWHVSCandidateFrameManager _applyLargeFaceRecovery:faceAreas:]
+ -[BWHVSCandidateFrameManager _applyMaxScoresPerContext]
+ -[BWHVSCandidateFrameManager _applyTinyFaceFiltering]
+ -[BWHVSCandidateFrameManager _availableBudget]
+ -[BWHVSCandidateFrameManager _cleanupRemovalFlagsForUnpromotedCauses]
+ -[BWHVSCandidateFrameManager _contextExistsInPromotedFrames:]
+ -[BWHVSCandidateFrameManager _findLowestScoreFrameFromMostPopulatedContext]
+ -[BWHVSCandidateFrameManager _findWeakestPromotedFrameForContext:]
+ -[BWHVSCandidateFrameManager _isDuplicateOfFrame:comparedToFrame:]
+ -[BWHVSCandidateFrameManager _isDuplicateOfFrame:comparedToFrameDict:]
+ -[BWHVSCandidateFrameManager _isDuplicateWithEmbedding:timestamp:context:andEmbedding:timestamp:context:simBoost:minProximitySec:dampedSimilarity:]
+ -[BWHVSCandidateFrameManager _isFailedCaptureFrameID:]
+ -[BWHVSCandidateFrameManager _isManualPromotedFrameID:]
+ -[BWHVSCandidateFrameManager _matchBudgetByManagingExtras]
+ -[BWHVSCandidateFrameManager _newCandidateFrameFromRealtimeBucket:]
+ -[BWHVSCandidateFrameManager _newPauseFrameFromInputFrame:]
+ -[BWHVSCandidateFrameManager _postCleanupBudgetReverification]
+ -[BWHVSCandidateFrameManager _promoteAgedOutCandidatesWithCurrentTime:]
+ -[BWHVSCandidateFrameManager _promoteFrame:]
+ -[BWHVSCandidateFrameManager _promotedFrameSharingRawCaptureWithFrame:]
+ -[BWHVSCandidateFrameManager _recoverExtrasWithinBudget]
+ -[BWHVSCandidateFrameManager _resolveBreakPauseDuplicateForNewFrame:comparedToFrame:]
+ -[BWHVSCandidateFrameManager _resolveBreakPauseDuplicateForNewFrame:comparedToFrameDict:]
+ -[BWHVSCandidateFrameManager _resolveBreakPauseDuplicateForNewIsPause:newSegmentIdx:newTimestamp:dupIsPause:dupSegmentIdx:dupTimestamp:]
+ -[BWHVSCandidateFrameManager _resolvePromotedFrameDuplicatesForFrame:]
+ -[BWHVSCandidateFrameManager _shouldAddCandidate:]
+ -[BWHVSCandidateFrameManager _silentlyRemoveMaxScoreFrameID:causingFrameID:]
+ -[BWHVSCandidateFrameManager _totalBudget]
+ -[BWHVSCandidateFrameManager _tryPromoteFrame:]
+ -[BWHVSCandidateFrameManager _tryReplaceLowestCandidateOnBudgetFailure:]
+ -[BWHVSCandidateFrameManager captureFolder]
+ -[BWHVSCandidateFrameManager dealloc]
+ -[BWHVSCandidateFrameManager finalizeCandidates]
+ -[BWHVSCandidateFrameManager initWithDelegate:hvsConfig:]
+ -[BWHVSCandidateFrameManager isFixedBudgetExhausted]
+ -[BWHVSCandidateFrameManager processFrame:]
+ -[BWHVSCandidateFrameManager registerFailedCaptureFrame:]
+ -[BWHVSCandidateFrameManager registerManualCaptureFrame:]
+ -[BWHVSCandidateFrameManager reset]
+ -[BWHVSCandidateFrameManager setCaptureFolder:]
+ -[BWHVSCandidateFrameManager setFramePromotionHandler:context:]
+ -[BWHVSCandidateFrameManager setFrameRemovalHandler:context:]
+ -[BWHVSCandidateFrameManager typicalBufferingInSeconds]
+ -[BWHVSEmbeddingAnalysisResult contextProbabilities]
+ -[BWHVSEmbeddingAnalysisResult dealloc]
+ -[BWHVSEmbeddingAnalysisResult detectedContext]
+ -[BWHVSEmbeddingAnalysisResult frameScore]
+ -[BWHVSEmbeddingAnalysisResult imageEmbedding]
+ -[BWHVSEmbeddingAnalysisResult initWithImageEmbedding:contextProbabilities:detectedContext:similarityScore:frameScore:]
+ -[BWHVSEmbeddingAnalysisResult initWithMetadataDictionary:]
+ -[BWHVSEmbeddingAnalysisResult metadataRepresentation]
+ -[BWHVSEmbeddingAnalysisResult setSimilarityScore:]
+ -[BWHVSEmbeddingAnalysisResult similarityScore]
+ -[BWHVSFace dealloc]
+ -[BWHVSFace faceObservation]
+ -[BWHVSFace initWithANSTObject:faceObservation:imageDimensions:isFrontal:]
+ -[BWHVSFace isFrontal]
+ -[BWHVSFace metadataRepresentation]
+ -[BWHVSFace setFaceObservation:]
+ -[BWHVSFrame _computeCropPenaltyForFaceRects:bodyRects:faceEdgeThreshold:bodyEdgeThreshold:minBodyAreaRatio:finalCropRect:]
+ -[BWHVSFrame _computeCropPenaltyWithFaceEdgeThreshold:bodyEdgeThreshold:minBodyAreaRatio:percentOfLargestFace:minFaceArea:finalCropRect:]
+ -[BWHVSFrame _computeMaskedFaceSharpnessWithPercentOfLargestFace:minFaceArea:threshold:capRange:sensitivity:normalizeMax:]
+ -[BWHVSFrame _computePetCropPenaltyWithFaceEdgeThreshold:bodyEdgeThreshold:minBodyAreaRatio:finalCropRect:]
+ -[BWHVSFrame _faceCombinedFactor:mlvLow:mlvHigh:bonusRange:maxBonus:]
+ -[BWHVSFrame _mapAndNormalizeScore:threshold:capRange:sensitivity:normalizeMax:]
+ -[BWHVSFrame _normalizeAuxScore:statsDict:]
+ -[BWHVSFrame _normalizeDeviceSharpness:]
+ -[BWHVSFrame _normalizeGlobalSharpness:divisor:multiplier:]
+ -[BWHVSFrame captureSettingsID]
+ -[BWHVSFrame currentFrameRate]
+ -[BWHVSFrame dealloc]
+ -[BWHVSFrame description]
+ -[BWHVSFrame duplicateInfo]
+ -[BWHVSFrame ev0RawCaptureID]
+ -[BWHVSFrame exposureTime]
+ -[BWHVSFrame faceObservations]
+ -[BWHVSFrame finalCropRectLaplacianVariance]
+ -[BWHVSFrame frameID]
+ -[BWHVSFrame frameScore]
+ -[BWHVSFrame frameStatisticsByPortType]
+ -[BWHVSFrame frameTrackingEntry]
+ -[BWHVSFrame hrEnabled]
+ -[BWHVSFrame hueMapPixelBuffer]
+ -[BWHVSFrame initWithSampleBuffer:hvsFrameMetadata:hvsConfig:sessionID:]
+ -[BWHVSFrame initWithYUVSampleBuffer:rawEV0SampleBuffer:rawSIFRSampleBuffer:inputNetworkOutput:inputFaceObservations:pinnedSubjectsArray:hvsConfig:sessionID:sharpnessResults:cacheYUVPixelBuffer:]
+ -[BWHVSFrame isManualCapture]
+ -[BWHVSFrame isPauseFrame]
+ -[BWHVSFrame metadataRepresentation]
+ -[BWHVSFrame newMutableCopiedRawEV0SampleBuffer]
+ -[BWHVSFrame newMutableCopiedRawSIFRSampleBuffer]
+ -[BWHVSFrame originalCameraIntrinsicMatrixReferenceDimensions]
+ -[BWHVSFrame originalCameraIntrinsicMatrix]
+ -[BWHVSFrame pauseDurationInSec]
+ -[BWHVSFrame people]
+ -[BWHVSFrame personMaskPNGData]
+ -[BWHVSFrame pets]
+ -[BWHVSFrame rawEV0SampleBuffer]
+ -[BWHVSFrame rawSIFRSampleBuffer]
+ -[BWHVSFrame sbufPresentationTimestamp]
+ -[BWHVSFrame segmentIdx]
+ -[BWHVSFrame sessionID]
+ -[BWHVSFrame setCaptureSettingsID:]
+ -[BWHVSFrame setDuplicateInfo:]
+ -[BWHVSFrame setFrameID:]
+ -[BWHVSFrame setFrameTrackingEntry:]
+ -[BWHVSFrame setIsManualCapture:]
+ -[BWHVSFrame setIsPauseFrame:]
+ -[BWHVSFrame setPauseDurationInSec:]
+ -[BWHVSFrame setPersonMaskPNGData:]
+ -[BWHVSFrame setRawEV0SampleBuffer:]
+ -[BWHVSFrame setRawSIFRSampleBuffer:]
+ -[BWHVSFrame setSbufPresentationTimestamp:]
+ -[BWHVSFrame setSegmentIdx:]
+ -[BWHVSFrame sifrRawCaptureID]
+ -[BWHVSFrame stillImageCaptureMetadata]
+ -[BWHVSFrame stillImageSceneFlags]
+ -[BWHVSFrame timestamp]
+ -[BWHVSFrame unifiedEmbeddingsOutput]
+ -[BWHVSFrameAnalysisTask analysisEnabled]
+ -[BWHVSFrameAnalysisTask dealloc]
+ -[BWHVSFrameAnalysisTask description]
+ -[BWHVSFrameAnalysisTask faceObservations]
+ -[BWHVSFrameAnalysisTask imageEmbedding]
+ -[BWHVSFrameAnalysisTask initWithYUVSampleBuffer:matchingMainSensorRawSampleBuffer:matchingSIFRSensorRawSampleBuffer:imageEmbeddingSampleBuffer:faceQualitySampleBuffer:subtaskGroup:]
+ -[BWHVSFrameAnalysisTask joinSubtaskThreadWithName:]
+ -[BWHVSFrameAnalysisTask leaveSubtaskThread]
+ -[BWHVSFrameAnalysisTask matchingMainSensorRawSampleBuffer]
+ -[BWHVSFrameAnalysisTask matchingSIFRSensorRawSampleBuffer]
+ -[BWHVSFrameAnalysisTask personMaskPNGData]
+ -[BWHVSFrameAnalysisTask setFaceObservations:]
+ -[BWHVSFrameAnalysisTask setImageEmbedding:]
+ -[BWHVSFrameAnalysisTask setPersonMaskPNGData:]
+ -[BWHVSFrameAnalysisTask setSharpnessResults:]
+ -[BWHVSFrameAnalysisTask sharpnessResults]
+ -[BWHVSFrameAnalysisTask waitUntilComplete]
+ -[BWHVSFrameAnalysisTask yuvSampleBuffer]
+ -[BWHVSObject boundingBox]
+ -[BWHVSObject confidence]
+ -[BWHVSObject groupID]
+ -[BWHVSObject imageDimensions]
+ -[BWHVSObject initWithANSTObject:imageDimensions:]
+ -[BWHVSObject laplacianVariance]
+ -[BWHVSObject metadataRepresentation]
+ -[BWHVSObject setBoundingBox:]
+ -[BWHVSObject setConfidence:]
+ -[BWHVSObject setGroupID:]
+ -[BWHVSObject setImageDimensions:]
+ -[BWHVSObject setLaplacianVariance:]
+ -[BWHVSPerson body]
+ -[BWHVSPerson dealloc]
+ -[BWHVSPerson face]
+ -[BWHVSPerson initWithImageDimensions:face:faceObservation:body:isFrontal:]
+ -[BWHVSPerson metadataRepresentation]
+ -[BWHVSPet body]
+ -[BWHVSPet dealloc]
+ -[BWHVSPet face]
+ -[BWHVSPet initWithBody:face:imageDimensions:orientation:]
+ -[BWHVSPet metadataRepresentation]
+ -[BWHVSScoringNode .cxx_destruct]
+ -[BWHVSScoringNode _analyzeImageEmbeddings:prevNetworkOutput:anyPetsInFrame:]
+ -[BWHVSScoringNode _attachMatchingSemanticMasksToSampleBuffer:]
+ -[BWHVSScoringNode _clearScheduledFrameAnalysisTask]
+ -[BWHVSScoringNode _extractSignalsFromFrameAnalysisTask:sharpnessResults:faceObservations:networkOutput:]
+ -[BWHVSScoringNode _finalizeAndCleanupSession]
+ -[BWHVSScoringNode _handleHueMapSampleBuffer:]
+ -[BWHVSScoringNode _handleRawSampleBuffer:]
+ -[BWHVSScoringNode _handleYUVSampleBuffer:]
+ -[BWHVSScoringNode _initializeTextEmbeddings]
+ -[BWHVSScoringNode _initiatePersonalPhotographerCaptureWithFrame:manualCapture:]
+ -[BWHVSScoringNode _newFrameFromSampleBuffer:]
+ -[BWHVSScoringNode _releaseResources]
+ -[BWHVSScoringNode _resetAllTrackedStatuses]
+ -[BWHVSScoringNode _resetStatusInfo]
+ -[BWHVSScoringNode _scheduleFrameAnalysisForYUVSampleBuffer:matchingMainSensorRawSampleBuffer:matchingSIFRSensorRawSampleBuffer:analysisEnabled:]
+ -[BWHVSScoringNode _unpackRecommendedMasterSampleBufferFromYUVSampleBuffer:]
+ -[BWHVSScoringNode _updateMetadataForFrame:manualCapture:rawSampleBuffers:]
+ -[BWHVSScoringNode _updateSubjectDetectionStatusWithAnySubjectsInFrame:sessionActive:updateDevice:]
+ -[BWHVSScoringNode configurationWithID:updatedFormat:didBecomeLiveForInput:]
+ -[BWHVSScoringNode currentActiveRequestedSettings]
+ -[BWHVSScoringNode dealloc]
+ -[BWHVSScoringNode didReachEndOfDataForConfigurationID:input:]
+ -[BWHVSScoringNode didSelectFormat:forInput:]
+ -[BWHVSScoringNode didSelectFormat:forInput:forAttachedMediaKey:]
+ -[BWHVSScoringNode handleDroppedSample:forInput:]
+ -[BWHVSScoringNode hueMapInput]
+ -[BWHVSScoringNode hvsCandidateFrameManager:didRegisterFramesToKeep:framesToDelete:]
+ -[BWHVSScoringNode initWithCaptureMode:captureDevice:inferenceScheduler:threadPriority:delegate:]
+ -[BWHVSScoringNode initiateManualPersonalPhotographerCapture]
+ -[BWHVSScoringNode loadInferenceNetwork]
+ -[BWHVSScoringNode nodeSubType]
+ -[BWHVSScoringNode nodeType]
+ -[BWHVSScoringNode prepareForCurrentConfigurationToBecomeLive]
+ -[BWHVSScoringNode rawInput]
+ -[BWHVSScoringNode renderSampleBuffer:forInput:]
+ -[BWHVSScoringNode semanticMasksInput]
+ -[BWHVSScoringNode startPersonalPhotographerSessionWithSettings:stillImageCoordinator:]
+ -[BWHVSScoringNode stopPersonalPhotographerSession]
+ -[BWHVSScoringNode typicalCaptureLatencyInSeconds]
+ -[BWHVSScoringNode updatePersonalPhotographerOrientationDegrees:mirrored:]
+ -[BWHVSScoringNode willStopGraph:]
+ -[BWHVSScoringNode yuvInput]
+ -[BWIrisStagingNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:autoTrimMethod:vitalityScoringEnabled:captureDeviceHasOverCaptureEnabled:overCaptureEnabled:depthEnabled:videoStabilizationOverscanOverride:sequenceAdjusterEnabled:visMotionMetadataPreloadingMode:frameReconstructionEnabled:subjectRelightingEnabled:intermediateJPEGCompressionQuality:intermediateJPEGCompressionRate:maxLossyCompressionLevel:temporaryMovieDirectoryURL:cameraInfoByPortType:smartStyleRenderingEnabled:smartStyleReversibilityEnabled:smartFramingEnabled:textureStyleRenderingEnabled:irisRequestDelegate:inferenceScheduler:]
+ -[BWLCBDatabaseManager .cxx_destruct]
+ -[BWLCBDatabaseManager _executeDatabaseStorageWorkAsync:block:]
+ -[BWLCBDatabaseManager databaseForPortType:]
+ -[BWLCBDatabaseManager dealloc]
+ -[BWLCBDatabaseManager delegate]
+ -[BWLCBDatabaseManager init]
+ -[BWLCBDatabaseManager lcbDatabaseByPortType]
+ -[BWLCBDatabaseManager loadDatabasesForSensorConfigurationsByPortType:]
+ -[BWLCBDatabaseManager saveDatabasesIfNeeded]
+ -[BWLCBDatabaseManager setDelegate:]
+ -[BWLCBDatabaseManager updateDatabase:forPortType:]
+ -[BWMovieFileOutputAnalyticsPayload cinematicMetadataMovieRecordingStats]
+ -[BWMovieFileOutputAnalyticsPayload cinematicVideoMetadataEnabled]
+ -[BWMovieFileOutputAnalyticsPayload setCinematicMetadataMovieRecordingStats:]
+ -[BWMovieFileOutputAnalyticsPayload setCinematicVideoMetadataEnabled:]
+ -[BWMultiCamConfiguration _initWithUnsynchronizedActiveStreamsPortTypes:synchronizedActiveStreamsGroupsPortTypes:mutuallyExclusiveUnsynchronizedStreamsPortTypes:withCaptureDevice:readCurrentStateFromCaptureDevice:stereoVideoCaptureEnabled:multiCamClientCompositingEnabled:colorAssistedSecureFaceIDEnabled:secureProcessingCoexEnabled:exclusivelyForSecureProcessing:builtInMicrophoneIsRecording:]
+ -[BWMultiStreamCameraSourceNode _calculateZoomFactorsToNondisruptiveSwitchingFormatIndexMapping:nondisruptiveSwitchingFormatIndicesByZoomfactorMainAndSIFRBinnedOut:nondisruptiveSwitchingFormatIndicesByZoomfactorSIFRNonBinnedOut:nondisruptiveSwitchingFormatIndicesByZoomfactorSecureSigning:ultraHighResolutionSecureSigningNondisruptiveStreamingFormatIndex:ultraHighResolutionNondisruptiveStreamingFormatIndex:]
+ -[BWMultiStreamCameraSourceNode _renoDualTimeMachinesEnabled]
+ -[BWMultiStreamCameraSourceNode _ultraHighResolutionSecureSigningNondisruptiveStreamingFormatIndex]
+ -[BWMultiStreamCameraSourceNode _updateZoomForSemanticMaskAttachedMedia:outputIndex:]
+ -[BWMultiStreamCameraSourceNode applyIsUnsynchronizedPrimary:]
+ -[BWMultiStreamCameraSourceNode captureFaceIDBracketWithConfiguration:]
+ -[BWMultiStreamCameraSourceNode isUnsynchronizedPrimary]
+ -[BWMultiStreamCameraSourceNode setFaceIDConfiguration:]
+ -[BWMultiStreamCameraSourceNode setPreviewStabilizationShift:]
+ -[BWMultiStreamCameraSourceNodeConfiguration faceImageQualityDetectionEnabled]
+ -[BWMultiStreamCameraSourceNodeConfiguration focusTrackedObjectsDeliveryEnabled]
+ -[BWMultiStreamCameraSourceNodeConfiguration secureStreamingForFaceIDEnabled]
+ -[BWMultiStreamCameraSourceNodeConfiguration setFaceImageQualityDetectionEnabled:]
+ -[BWMultiStreamCameraSourceNodeConfiguration setFocusTrackedObjectsDeliveryEnabled:]
+ -[BWMultiStreamCameraSourceNodeConfiguration setSecureStreamingForFaceIDEnabled:]
+ -[BWNondisruptiveSwitchingFormatSelector formatIndexForZoomFactor:frameStatistics:imageControlMode:stillImageDigitalFlashMode:isStationary:isSecondaryStream:binnedSIFROnSecondaryStreamAllowed:ignoreZoomFactorAndQuadraSubPixelSceneMonitoring:secureSigningMode:ultraHighResolutionZeroShutterLagEnabled:]
+ -[BWNondisruptiveSwitchingFormatSelector hasSecureSigningFormats]
+ -[BWNondisruptiveSwitchingFormatSelector initWithPortType:quadraSubPixelSwitchingParameters:baseZoomFactor:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSecureSigning:ultraHighResolutionSecureSigningNondisruptiveStreamingFormatIndex:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:]
+ -[BWPersonalPhotographerSceneMonitorV1 _performStorageCheck]
+ -[BWPersonalPhotographerSceneMonitorV1 _setupStorageSpaceCheckTimer]
+ -[BWPersonalPhotographerSceneMonitorV1 dealloc]
+ -[BWPersonalPhotographerSceneMonitorV1 initWithTuningParametersByPortType:]
+ -[BWPersonalPhotographerSceneMonitorV1 resolvePersonalPhotographerStatusWithSampleBuffer:frameStatisticsByPortType:thermalPressureLevel:peakPowerPressureLevel:subjectDetected:personalPhotographerStatus:]
+ -[BWPhotoEncoderController _addProvenanceSensorRawForEncodingScheme:sampleBuffer:]
+ -[BWPhotoEncoderController _addSmartStyleUnstyledImageForEncodingScheme:sampleBuffer:primaryOutputAspectRatio:stillImageSettings:]
+ -[BWPhotoEncoderController _addTextureStyleMetadataForEncodingScheme:sampleBuffer:requestedStillImageCaptureSettings:resolvedStillImageCaptureSettings:]
+ -[BWPhotoEncoderController _addTextureStylePersonInstanceMasksForEncodingScheme:sampleBuffer:primaryOutputAspectRatio:settingsID:orientation:parentImageHandle:]
+ -[BWPhotoEncoderController _handlePrewarmForFSINCMasksForEncodingScheme:requestedStillImageCaptureSettings:]
+ -[BWPhotoEncoderController _newAuxiliaryImagePropertiesForFSINCMask:fsincMatteVersion:]
+ -[BWPhotoEncoderController provenanceDNGInfo]
+ -[BWPhotoEncoderControllerConfiguration secureSigningPhotoCaptureSupportEnabled]
+ -[BWPhotoEncoderControllerConfiguration setSecureSigningPhotoCaptureSupportEnabled:]
+ -[BWPhotoEncoderControllerConfiguration setTextureStyleCreativeEffectsEnabled:]
+ -[BWPhotoEncoderControllerConfiguration textureStyleCreativeEffectsEnabled]
+ -[BWPhotoEncoderControllerInput fsincMasksPrewarmedForCurrentEncoding]
+ -[BWPhotoEncoderControllerInput setFsincMasksPrewarmedForCurrentEncoding:]
+ -[BWPhotoEncoderControllerRequest dealloc]
+ -[BWPhotoEncoderControllerRequest provenanceDNGSurfaceSize]
+ -[BWPhotoEncoderControllerRequest provenanceDNGSurface]
+ -[BWPhotoEncoderControllerRequest setProvenanceDNGSurface:size:]
+ -[BWPhotoEncoderNode setTextureStyleCreativeEffectsEnabled:]
+ -[BWPreviewStabilizationNode delegate]
+ -[BWPreviewStabilizationNode setDelegate:]
+ -[BWQuickTimeMovieFileSinkNode cinematicVideoMetadataEnabled]
+ -[BWQuickTimeMovieFileSinkNode movieRecordingEndOfDataBehavior]
+ -[BWQuickTimeMovieFileSinkNode setCinematicVideoMetadataEnabled:]
+ -[BWQuickTimeMovieFileSinkNode setMovieRecordingEndOfDataBehavior:]
+ -[BWRealtimeCinematographyNode cinematicVideoDisparityProvider]
+ -[BWRealtimeCinematographyNode initWithObjectMetadataIdentifiers:cachedSimulatedAperture:captureDevice:tuningParameters:videoDepthConfiguration:smartStyleLearningEnabled:highResolutionInputEnabled:transformCinematographyDetectionsForMovieFileOutput:depthInputProvided:]
+ -[BWRealtimeCinematographyNode setCinematicVideoDisparityProvider:]
+ -[BWSecureFaceIDFrameTracker addFrameIdentifiersForFaceIDResult:]
+ -[BWSecureFaceIDFrameTracker dealloc]
+ -[BWSecureFaceIDFrameTracker init]
+ -[BWSecureFaceIDFrameTracker removeFrameIdentifier:]
+ -[BWSecureMetadataOutputConfiguration colorCameraAssistEnabled]
+ -[BWSecureMetadataOutputConfiguration faceIDConfiguration]
+ -[BWSecureMetadataOutputConfiguration faceIDEnabled]
+ -[BWSecureMetadataOutputConfiguration rawFrameDeliveryEnabled]
+ -[BWSecureMetadataOutputConfiguration setColorCameraAssistEnabled:]
+ -[BWSecureMetadataOutputConfiguration setFaceIDConfiguration:]
+ -[BWSecureMetadataOutputConfiguration setFaceIDEnabled:]
+ -[BWSecureMetadataOutputConfiguration setRawFrameDeliveryEnabled:]
+ -[BWSecureSigningUtilityManager .cxx_destruct]
+ -[BWSecureSigningUtilityManager _fetchClientProvidedSensorPayloadAndHashSynchronously]
+ -[BWSecureSigningUtilityManager _startPeriodicRefreshOnQueue]
+ -[BWSecureSigningUtilityManager _stopPeriodicRefreshOnQueue]
+ -[BWSecureSigningUtilityManager clientProvidedHash]
+ -[BWSecureSigningUtilityManager clientProvidedSensorPayloadInfoForClientProvidedHash:]
+ -[BWSecureSigningUtilityManager dealloc]
+ -[BWSecureSigningUtilityManager delegate]
+ -[BWSecureSigningUtilityManager firstSecureSigningStaticDataFailure:]
+ -[BWSecureSigningUtilityManager init]
+ -[BWSecureSigningUtilityManager isSecureSigningCertificateAvailableWithTimeout:]
+ -[BWSecureSigningUtilityManager issueSecureSigningClientCertificateOnQueue:completion:]
+ -[BWSecureSigningUtilityManager lowerBoundTimestampDataForClientProvidedHash:]
+ -[BWSecureSigningUtilityManager lowerBoundTimestampData]
+ -[BWSecureSigningUtilityManager sealingManifestData]
+ -[BWSecureSigningUtilityManager sealingManifestUniqueIDData]
+ -[BWSecureSigningUtilityManager secureBootTicketData]
+ -[BWSecureSigningUtilityManager sensorCertificateData]
+ -[BWSecureSigningUtilityManager sensorCertificateUniqueIDData]
+ -[BWSecureSigningUtilityManager setDelegate:]
+ -[BWSecureSigningUtilityManager trustObjectData]
+ -[BWSecureSigningUtilityManager trustObjectDigestData]
+ -[BWSemanticMasksConverterNode _correctRectanglesInDetectedObjectsInfo:derivedFromAttachedMedia:]
+ -[BWSemanticMasksConverterNode _createDetectedObjectsSampleBufferFromSemanticMasksSampleBuffer:]
+ -[BWSemanticMasksConverterNode configurationWithID:updatedFormat:didBecomeLiveForInput:]
+ -[BWSemanticMasksConverterNode dealloc]
+ -[BWSemanticMasksConverterNode detectedObjectsOutput]
+ -[BWSemanticMasksConverterNode didReachEndOfDataForConfigurationID:input:]
+ -[BWSemanticMasksConverterNode didStopContinuousAutoFocusTracking]
+ -[BWSemanticMasksConverterNode focusTrackedObjectOutputEnabled]
+ -[BWSemanticMasksConverterNode initWithEnabledSemanticMaskTypes:detectedObjectsMetadataIdentifiers:subjectAcquiredChangedHandler:]
+ -[BWSemanticMasksConverterNode nodeSubType]
+ -[BWSemanticMasksConverterNode nodeType]
+ -[BWSemanticMasksConverterNode rectOfInterest]
+ -[BWSemanticMasksConverterNode renderSampleBuffer:forInput:]
+ -[BWSemanticMasksConverterNode setFocusTrackedObjectOutputEnabled:]
+ -[BWSemanticMasksConverterNode setRectOfInterest:]
+ -[BWSensorRawTimeMachine _insertSampleBuffer:frameType:]
+ -[BWSensorRawTimeMachine _removeSampleBufferAtIndex:frameType:]
+ -[BWSensorRawTimeMachine _removeSampleBuffersThroughIndex:frameType:]
+ -[BWSensorRawTimeMachine attachMatchingHueMapToMainSampleBuffer:mainPTS:mainExposureTime:frameRate:]
+ -[BWSensorRawTimeMachine copyMatchingSampleBufferWithFrameType:mainPTS:mainExposureTime:frameRate:]
+ -[BWSensorRawTimeMachine dealloc]
+ -[BWSensorRawTimeMachine flushFramesUpToPTS:frameRate:]
+ -[BWSensorRawTimeMachine flush]
+ -[BWSensorRawTimeMachine initWithConfiguration:]
+ -[BWSensorRawTimeMachine insertFrame:]
+ -[BWSensorRawTimeMachine insertHueMap:]
+ -[BWSensorRawTimeMachine insertSemanticMasks:]
+ -[BWSensorRawTimeMachineConfiguration dealloc]
+ -[BWSensorRawTimeMachineConfiguration description]
+ -[BWSensorRawTimeMachineConfiguration frameConfigurationByFrameType]
+ -[BWSensorRawTimeMachineConfiguration name]
+ -[BWSensorRawTimeMachineConfiguration setFrameConfigurationByFrameType:]
+ -[BWSensorRawTimeMachineConfiguration setName:]
+ -[BWSensorRawTimeMachineFrameConfiguration allowedPTSDeltaFrameIntervalFactor]
+ -[BWSensorRawTimeMachineFrameConfiguration description]
+ -[BWSensorRawTimeMachineFrameConfiguration expectsFrameSkipping]
+ -[BWSensorRawTimeMachineFrameConfiguration maxCount]
+ -[BWSensorRawTimeMachineFrameConfiguration setAllowedPTSDeltaFrameIntervalFactor:]
+ -[BWSensorRawTimeMachineFrameConfiguration setExpectsFrameSkipping:]
+ -[BWSensorRawTimeMachineFrameConfiguration setMaxCount:]
+ -[BWSkinTextureStyleRenderer _attachedMediaKeyForMaskType:]
+ -[BWSkinTextureStyleRenderer _mergeImageStatsIntoPeopleData:]
+ -[BWSkinTextureStyleRenderer _setupCommonInputsFromSampleBuffer:inputPixelBuffer:processedPixelBuffer:]
+ -[BWSkinTextureStyleRenderer _setupMaskFromSampleBuffer:maskType:]
+ -[BWSkinTextureStyleRenderer _setupMasksFromSampleBuffer:]
+ -[BWSkinTextureStyleRenderer _setupMattifyInEffectsToRender:presetTuningParameters:renderEffect:]
+ -[BWSkinTextureStyleRenderer _setupPersonDataFromSampleBuffer:]
+ -[BWSkinTextureStyleRenderer _setupProcessorFullImageSizeAndRegionToRenderFromSampleBuffer:inputPixelBuffer:]
+ -[BWSkinTextureStyleRenderer _setupSkinSmoothingInEffectsToRender:presetTuningParameters:totalGain:]
+ -[BWSkinTextureStyleRenderer _setupUnderEyeBrightenInEffectsToRender:presetTuningParameters:renderEffect:]
+ -[BWSkinTextureStyleRenderer adjustMetadataOfSampleBuffer:]
+ -[BWSkinTextureStyleRenderer adjustsMetadata]
+ -[BWSkinTextureStyleRenderer dealloc]
+ -[BWSkinTextureStyleRenderer displayName]
+ -[BWSkinTextureStyleRenderer initWithConfiguration:]
+ -[BWSkinTextureStyleRenderer isMetalRenderer]
+ -[BWSkinTextureStyleRenderer isPassThroughRenderer]
+ -[BWSkinTextureStyleRenderer prepareForRenderingWithParameters:inputVideoFormat:inputMediaPropertiesByAttachedMediaKey:]
+ -[BWSkinTextureStyleRenderer renderUsingParameters:inputPixelBuffer:inputSampleBuffer:processedPixelBuffer:completionHandler:]
+ -[BWSkinTextureStyleRenderer supportsAnimation]
+ -[BWSkinTextureStyleRenderer type]
+ -[BWSkinTextureStyleRenderer waitForMetalCompletion]
+ -[BWSlaveFrameSynchronizerNode initWithDepthEnabled:numberOfInputs:syncSlaveForMasterPortTypes:separateDepthComponentsEnabled:preLTMThumbnailEnabled:postColorProcessingThumbnailEnabled:weightSegmentMapEnabled:styledFrameEnabled:lowLightVideoNoiseReductionEnabled:numberOfSecondaryFramesToSkip:sourceNodeSensorRawOutputsEnabled:]
+ -[BWSlaveFrameSynchronizerNode initWithDepthEnabled:numberOfInputs:syncSlaveForMasterPortTypes:separateDepthComponentsEnabled:preLTMThumbnailEnabledInputs:postColorProcessingThumbnailEnabledInputs:weightSegmentMapEnabledInputs:styledFrameEnabledInputs:lowLightVideoNoiseReductionEnabled:differentInputFormatsSupported:numberOfSlaveFramesToSkip:startEmittingMasterFramesBeforeSlaveStreamStarts:sourceNodeSensorRawOutputsEnabled:]
+ -[BWSmartFramingSceneMonitor _reset]
+ -[BWSmartFramingSceneMonitor _resolveOutputWithSampleBuffer:usingFieldsOfView:suggestedFieldOfViewOut:suggestedFieldOfViewRectOut:subjectDistanceRangeOut:subjectMotionPerSecondOut:atLeastOneSubjectGazingForShutterSoundRelaxationOut:significantSubjectCountOut:significantSubjectGroupIDsOut:persistentlySignificantSubjectCountOut:persistentlySignificantSubjectGroupIDsOut:]
+ -[BWSmartFramingSceneMonitor _updateMaximumSubjectMotionPerSecondForTrackedSubjects:pixelBufferWidth:rawSensorWidthInPhysicalSenosrPixels:nondisruptiveSwitchingFormatZoomFactor:]
+ -[BWSmartFramingSceneMonitor _updateSubjectDistanceRange:]
+ -[BWSmartFramingSceneMonitorResult apertureControlDistanceRangeWithError:]
+ -[BWSmartFramingSceneMonitorResult initWithSmartFramingSceneMonitorMode:suggestedFieldOfView:suggestedFieldOfViewRect:subjectDistanceRange:subjectMotionPerSecond:atLeastOneSubjectGazingForShutterSoundRelaxation:significantSubjectCount:significantSubjectGroupIDs:persistentlySignificantSubjectCount:persistentlySignificantSubjectGroupIDs:]
+ -[BWSmartFramingSceneMonitorResult persistentlySignificantSubjectCountWithError:]
+ -[BWSmartFramingSceneMonitorResult persistentlySignificantSubjectGroupIDsWithError:]
+ -[BWSmartFramingSceneMonitorResult significantSubjectCountWithError:]
+ -[BWSmartFramingSceneMonitorResult significantSubjectGroupIDsWithError:]
+ -[BWSmartFramingSceneMonitorResult subjectMotionPerSecondWithError:]
+ -[BWSmartStyleLearningNode _asynchronouslyLearnWithContainer:inputUnstyledSampleBuffer:withUnrefinedMasks:portTypeToLearn:synchronizedPortTypeToLearn:withStats:withStatsExtended:styleToLearn:currentTextureStyle:shouldLearn:shouldBypass:]
+ -[BWSmartStyleLearningNode _blendedTuningParametersForPortType:intensity:effectiveIntensityOut:]
+ -[BWSmartStyleLearningNode _getPortTypeFromMetadataDict:]
+ -[BWSmartStyleLearningNode _isEffectEnabled:inEffectOrder:]
+ -[BWSmartStyleLearningNode _newPixelBufferWithDimensions:pixelFormat:name:]
+ -[BWSmartStyleLearningNode _setupBloomForSkinMask:metadataDict:effectsToRender:]
+ -[BWSmartStyleLearningNode _setupCommonInputsForInputPixelBuffer:outputPixelBuffer:]
+ -[BWSmartStyleLearningNode _setupDiffusionForPersonMask:forSkinMaskPixelBuffer:metadataDict:intensity:effectsToRender:]
+ -[BWSmartStyleLearningNode _setupGlowForPersonMask:metadataDict:linearThumbnail:linearThumbnailMetadata:intensity:effectsToRender:statistics:]
+ -[BWSmartStyleLearningNode _setupInputMaskForPixelBuffer:maskType:maskIsOptional:metadataDict:]
+ -[BWSmartStyleLearningNode _setupLinearImageFromPixelBuffer:linearImageMetadata:]
+ -[BWSmartStyleLearningNode _setupMattifyForSkinMask:metadataDict:intensity:effectsToRender:]
+ -[BWSmartStyleLearningNode _setupPersonDataFromMetadata:maxFaceCount:]
+ -[BWSmartStyleLearningNode _setupProcessorFullImageSizeAndRegionToRenderPixelBuffer:]
+ -[BWSmartStyleLearningNode _tuningParametersForPortType:]
+ -[BWSmartStyleLearningNode _updateTextureStyleEnableFlagsForMetadataDict:]
+ -[BWSmartStyleLearningNode initWithOutputs:masksRefinerEnabled:propagateMasks:ispSMGProcessingSession:squareAspectRatioConfigEnabled:hardwareStreamingRenderingEnabled:textureStyleEnabled:subjectRelightingPreviewVersion:]
+ -[BWSmartStyleLearningNode setTextureStyle:]
+ -[BWSmartStyleLearningNode textureStyle]
+ -[BWSmartStyleRendererConfiguration setTextureStyleCreativeEffectsEnabled:]
+ -[BWSmartStyleRendererConfiguration setTextureStyleRenderingVersion:]
+ -[BWSmartStyleRendererConfiguration textureStyleCreativeEffectsEnabled]
+ -[BWSmartStyleRendererConfiguration textureStyleRenderingVersion]
+ -[BWSphereModeSelector magneticInterferenceDetected]
+ -[BWSphereModeSelector setMagneticInterferenceDetected:]
+ -[BWStartupCalibrationAnalyticsPayload hingeAngle]
+ -[BWStartupCalibrationAnalyticsPayload reason]
+ -[BWStartupCalibrationAnalyticsPayload setHingeAngle:]
+ -[BWStartupCalibrationAnalyticsPayload setReason:]
+ -[BWStillImageAnalyticsPayloadCommon activeExposureSignals]
+ -[BWStillImageAnalyticsPayloadCommon actualFNumber]
+ -[BWStillImageAnalyticsPayloadCommon apertureDiameter]
+ -[BWStillImageAnalyticsPayloadCommon ignoredExposureSignals]
+ -[BWStillImageAnalyticsPayloadCommon inputExposureSignals]
+ -[BWStillImageAnalyticsPayloadCommon maxVATrackingError]
+ -[BWStillImageAnalyticsPayloadCommon requestedFNumber]
+ -[BWStillImageAnalyticsPayloadCommon setActiveExposureSignals:]
+ -[BWStillImageAnalyticsPayloadCommon setActualFNumber:]
+ -[BWStillImageAnalyticsPayloadCommon setApertureDiameter:]
+ -[BWStillImageAnalyticsPayloadCommon setIgnoredExposureSignals:]
+ -[BWStillImageAnalyticsPayloadCommon setInputExposureSignals:]
+ -[BWStillImageAnalyticsPayloadCommon setMaxVATrackingError:]
+ -[BWStillImageAnalyticsPayloadCommon setRequestedFNumber:]
+ -[BWStillImageAnalyticsPayloadCommon setStdVATrackingError:]
+ -[BWStillImageAnalyticsPayloadCommon setTextureStyleGrain:]
+ -[BWStillImageAnalyticsPayloadCommon setTextureStyleIntensity:]
+ -[BWStillImageAnalyticsPayloadCommon setTextureStylePreset:]
+ -[BWStillImageAnalyticsPayloadCommon setTextureStyleRenderingSupported:]
+ -[BWStillImageAnalyticsPayloadCommon setVariableApertureTemperature:]
+ -[BWStillImageAnalyticsPayloadCommon stdVATrackingError]
+ -[BWStillImageAnalyticsPayloadCommon textureStyleGrain]
+ -[BWStillImageAnalyticsPayloadCommon textureStyleIntensity]
+ -[BWStillImageAnalyticsPayloadCommon textureStylePreset]
+ -[BWStillImageAnalyticsPayloadCommon textureStyleRenderingSupported]
+ -[BWStillImageAnalyticsPayloadCommon variableApertureTemperature]
+ -[BWStillImageCaptureAnalyticsPayload numberOfLCBsCorrectedOnIRCF]
+ -[BWStillImageCaptureAnalyticsPayload numberOfLCBsCorrectedOnLens]
+ -[BWStillImageCaptureAnalyticsPayload numberOfLCBsDetected]
+ -[BWStillImageCaptureAnalyticsPayload setLCBDetectionCountHistogram:]
+ -[BWStillImageCaptureAnalyticsPayload setNumberOfLCBsCorrectedOnIRCF:]
+ -[BWStillImageCaptureAnalyticsPayload setNumberOfLCBsCorrectedOnLens:]
+ -[BWStillImageCaptureAnalyticsPayload setNumberOfLCBsDetected:]
+ -[BWStillImageCaptureMetadata ignoredExposureSignals]
+ -[BWStillImageCaptureMetadata setIgnoredExposureSignals:]
+ -[BWStillImageCoordinatorNode _calibrationTimerFired]
+ -[BWStillImageCoordinatorNode _enqueueCalibrationRequest]
+ -[BWStillImageCoordinatorNode _requestNowWouldBePartOfShotSequence]
+ -[BWStillImageCoordinatorNode _startCalibrationTimerIfNeeded]
+ -[BWStillImageCoordinatorNode _stopCalibrationTimer]
+ -[BWStillImageCoordinatorRequest initCalibrationWithRequestedSettings:]
+ -[BWStillImageDuplicateInfo description]
+ -[BWStillImageDuplicateInfo dictionaryRepresentation]
+ -[BWStillImageDuplicateInfo encodeWithCoder:]
+ -[BWStillImageDuplicateInfo initWithCoder:]
+ -[BWStillImageDuplicateInfo initWithDictionaryRepresentation:]
+ -[BWStillImageDuplicateInfo init]
+ -[BWStillImageDuplicateInfo originalPresentationTimestamp]
+ -[BWStillImageDuplicateInfo sbufPresentationTimestamp]
+ -[BWStillImageDuplicateInfo setOriginalPresentationTimestamp:]
+ -[BWStillImageDuplicateInfo setSbufPresentationTimestamp:]
+ -[BWStillImageDuplicateInfo setSettingsID:]
+ -[BWStillImageDuplicateInfo settingsID]
+ -[BWStillImageNodeConfiguration secureSigningPhotoCaptureSupportEnabled]
+ -[BWStillImageNodeConfiguration setSecureSigningPhotoCaptureSupportEnabled:]
+ -[BWStillImageProcessingSettings setSnapshottedLCBDatabaseByPortType:]
+ -[BWStillImageProcessingSettings snapshottedLCBDatabaseByPortType]
+ -[BWStillImageSampleBufferSinkNodeAnalyticsConfiguration isTextureStyleRenderingSupported]
+ -[BWStillImageSampleBufferSinkNodeAnalyticsConfiguration setIsTextureStyleRenderingSupported:]
+ -[BWStreamingFilterNode initWithCaptureDevice:maxLossyCompressionLevel:semanticStyleRenderingEnabled:cinematicVideoEnabled:computeFocusDisparity:smartStyleRenderingEnabled:portraitPreviewForegroundBlurEnabled:depthFilterRenderingIsAfterPreviewStitcher:metalCommandQueue:priority:mirroredForMetadataAdjustment:rotationDegreesForMetadataAdjustment:sourceStillImageOutputPortTypes:squareAspectRatioConfigEnabled:cropDepthToPrimaryCaptureAspectRatio:disableDepthAndSegmentationRotationInLandscape:]
+ -[BWStreamingFilterNode latestCinematicDisparityBuffer]
+ -[BWStreamingFilterNode provideBaselineTextureStyleRenderer]
+ -[BWStreamingFilterNode provideGlobalTextureStyleRenderer]
+ -[BWStreamingFilterNode provideGlowTextureStyleRenderer]
+ -[BWStreamingFilterNode provideSkinTextureStyleRenderer]
+ -[BWStreamingFilterNode providesCinematicDisparity]
+ -[BWStreamingRaytracingSDOFRenderer initWithCaptureDevice:commandQueue:smartStyleRenderingEnabled:squareAspectRatioConfigEnabled:computeFocusDisparity:]
+ -[BWStreamingSessionAnalyticsPayload numberOfMagneticInterferenceEventsDetected]
+ -[BWStreamingSessionAnalyticsPayload setNumberOfMagneticInterferenceEventsDetected:]
+ -[BWStreamingSessionAnalyticsPayload setStylusDataReceivedDuringSession:]
+ -[BWStreamingSessionAnalyticsPayload stylusDataReceivedDuringSession]
+ -[BWTextureStyleInfoMetadataNode _emitTextureStyleInfoBoxedMetadataForSampleBuffer:metadata:time:]
+ -[BWTextureStyleInfoMetadataNode _emptyMetadataBlockBuffer]
+ -[BWTextureStyleInfoMetadataNode boxedMetadataOutput]
+ -[BWTextureStyleInfoMetadataNode configurationWithID:updatedFormat:didBecomeLiveForInput:]
+ -[BWTextureStyleInfoMetadataNode dealloc]
+ -[BWTextureStyleInfoMetadataNode didReachEndOfDataForConfigurationID:input:]
+ -[BWTextureStyleInfoMetadataNode didSelectFormat:forInput:]
+ -[BWTextureStyleInfoMetadataNode handleDroppedSample:forInput:]
+ -[BWTextureStyleInfoMetadataNode hasNonLiveConfigurationChanges]
+ -[BWTextureStyleInfoMetadataNode init]
+ -[BWTextureStyleInfoMetadataNode nodeSubType]
+ -[BWTextureStyleInfoMetadataNode nodeType]
+ -[BWTextureStyleInfoMetadataNode passthruOutput]
+ -[BWTextureStyleInfoMetadataNode renderSampleBuffer:forInput:]
+ -[BWTimewarpMetadataNode _emitBoxedMetadataSampleData:boxedMetadataOutput:pts:formatDescription:]
+ -[BWTimewarpMetadataNode _emitTimewarpMetadataForSampleBuffer:metadata:time:]
+ -[BWTimewarpMetadataNode boxedMetadataOutput]
+ -[BWTimewarpMetadataNode configurationWithID:updatedFormat:didBecomeLiveForInput:]
+ -[BWTimewarpMetadataNode dealloc]
+ -[BWTimewarpMetadataNode didReachEndOfDataForConfigurationID:input:]
+ -[BWTimewarpMetadataNode didSelectFormat:forInput:]
+ -[BWTimewarpMetadataNode handleDroppedSample:forInput:]
+ -[BWTimewarpMetadataNode initForTimewarpMode:sourceClock:]
+ -[BWTimewarpMetadataNode nodeSubType]
+ -[BWTimewarpMetadataNode nodeType]
+ -[BWTimewarpMetadataNode passthruOutput]
+ -[BWTimewarpMetadataNode renderSampleBuffer:forInput:]
+ -[BWUBCaptureParameters adaptiveFusionDowngradeSNRHysteresisLag]
+ -[BWUBCaptureParameters adaptiveFusionDowngradeSNRThreshold]
+ -[BWUBCaptureParameters learnedFusionHighResolutionDowngradeNormalizedSNRHysteresisLag]
+ -[BWUBCaptureParameters learnedFusionHighResolutionDowngradeNormalizedSNRThreshold]
+ -[BWVISNode initWithSensorIDDict:stabilizationMethod:stabilizationType:ispProcessingSession:maxSupportedFrameRate:activeMaxFrameRate:gpuPriority:metalSubmissionAndCompletionQueuePriority:motionAttachmentsSource:fillExtendedRowsOfOutputBuffer:overCaptureEnabled:stereoMode:videoStabilizationOverscanOverride:videoStabilizationStrength:zoomSmoothingEnabled:applyFrameCropOffset:motionMetadataPreloadingEnabled:visExecutionMode:livePhotoCleanOutputRect:cameraInfoByPortType:cvisExtendedLookAheadDuration:distortionCorrectionEnabledPortTypes:distortionCompensationEnabledPortTypes:minDistanceForBravoParallaxShift:videoGreenGhostOfflineMetadataEnabled:videoGreenGhostOfflineLightSourceMaskEnabled:lightSourceMaskAndKeypointDescriptorDataEnabled:attachStabilizedOutputCameraTrajectory:systemIsUnderCriticalThermalPressure:textureStyleRenderingEnabled:faceAwareVideoStabilizationEnabled:]
+ -[BWVISNode setTextureStyle:]
+ -[BWVISProcessorControllerConfiguration setTextureStyleRenderingEnabled:]
+ -[BWVISProcessorControllerConfiguration textureStyleRenderingEnabled]
+ -[BWVariableFrameRateParameters lowLightVideoNoiseReductionLuxThresholds]
+ -[BWVariableFrameRateSelector _loadDefaultsWithPortTypes:forParameters:frameRateSwitchBasedOnMotionDisabled:teleAutoVideoFrameRateAllows24FPS:lowLightVideoNoiseReductionEnabled:]
+ -[BWVariableFrameRateSelector initWithPortTypes:forParameters:frameRateSwitchBasedOnMotionDisabled:teleAutoVideoFrameRateAllows24FPS:lowLightVideoNoiseReductionEnabled:]
+ -[BWVideoCompressorNode movieRecordingEndOfDataBehavior]
+ -[BWVideoCompressorNode setMovieRecordingEndOfDataBehavior:]
+ -[BWVideoNoiseReductionNode _removeAttachedMediaAndEmitSampleBuffer:]
+ -[BWVideoNoiseReductionNode _resetSceneMonitorForPortType:quadraBinningFactor:]
+ -[BWVideoNoiseReductionNode _supportedPixelFormats]
+ -[BWVideoNoiseReductionNode dealloc]
+ -[BWVideoNoiseReductionNode didSelectFormat:forInput:]
+ -[BWVideoNoiseReductionNode hasNonLiveConfigurationChanges]
+ -[BWVideoNoiseReductionNode initWithCameraInfoByPortType:maxLossyCompressionLevel:ispProcessingSession:videoNoiseReductionGainThresholdsByPortType:visOutputDimensions:]
+ -[BWVideoNoiseReductionNode nodeSubType]
+ -[BWVideoNoiseReductionNode nodeType]
+ -[BWVideoNoiseReductionNode prepareForCurrentConfigurationToBecomeLive]
+ -[BWVideoNoiseReductionNode renderSampleBuffer:forInput:]
+ -[FigCaptureAngleMonitor active]
+ -[FigCaptureAngleMonitor dealloc]
+ -[FigCaptureAngleMonitor initWithAngleHandler:]
+ -[FigCaptureAngleMonitor normalizedAngle]
+ -[FigCaptureAngleMonitor startMonitoring]
+ -[FigCaptureAngleMonitor stopMonitoring]
+ -[FigCaptureAudioFileSinkPipeline setMovieRecordingEndOfDataBehavior:]
+ -[FigCaptureCameraParameters lcbCorrectionEnabledForPortType:sensorIDString:]
+ -[FigCaptureCameraParameters lcbMinApertureRatioForDetectionForPortType:sensorIDString:]
+ -[FigCaptureCameraParameters lowLightVideoNoiseReductionParameters]
+ -[FigCaptureCameraParameters personalPhotographerSceneMonitoringParametersForPortType:sensorIDString:]
+ -[FigCaptureCameraParameters personalPhotographerVersion]
+ -[FigCaptureCameraParameters udnetEnabledForPortType:sensorIDString:]
+ -[FigCaptureCameraSourcePipeline _addOverCaptureSourcePipelineToGraph:upstreamVideoCaptureOutputsBySourceDeviceType:depthType:depthFilterRenderingEnabled:preLTMThumbnailEnabled:postColorProcessingThumbnailEnabled:weightSegmentMapEnabled:styledFrameEnabled:lowLightVideoNoiseReductionEnabled:forPreview:maxLossyCompressionLevel:numberOfSecondaryFramesToSkip:sourceNodeSensorRawOutputsEnabled:outErr:]
+ -[FigCaptureCameraSourcePipeline _attachedMediaKeysForMetadataKeys:]
+ -[FigCaptureCameraSourcePipeline applyOmahaPrimaryStreamSourceDeviceType:]
+ -[FigCaptureCameraSourcePipeline captureFaceIDBracketWithConfiguration:]
+ -[FigCaptureCameraSourcePipeline cinematicVideoGlobalMetadata]
+ -[FigCaptureCameraSourcePipeline cinematicVideoMetadataTrackingOutput]
+ -[FigCaptureCameraSourcePipeline hueMapOutputsByPortType]
+ -[FigCaptureCameraSourcePipeline isAttachedInfraredSourcePipeline]
+ -[FigCaptureCameraSourcePipeline lowLightVideoNoiseReductionEnabled]
+ -[FigCaptureCameraSourcePipeline semanticMasksMetadataOutputForSourceDeviceType:]
+ -[FigCaptureCameraSourcePipeline semanticMasksSceneClassifierOutputForSourceDeviceType:]
+ -[FigCaptureCameraSourcePipeline sensorRawOutputsByPortType]
+ -[FigCaptureCameraSourcePipeline setFaceIDConfiguration:]
+ -[FigCaptureCameraSourcePipeline setPreviewStabilizationShift:forPortType:]
+ -[FigCaptureCameraSourcePipeline setTextureStyle:]
+ -[FigCaptureCameraSourcePipeline textureStyle]
+ -[FigCaptureCameraSourcePipeline transposeOutputDimensionsForSmartCropNode]
+ -[FigCaptureCameraSourcePipelineConfiguration setCinematicVideoCaptureEnabled:]
+ -[FigCaptureCameraSourcePipelineConfiguration setCinematicVideoMetadataDeliveryEnabled:]
+ -[FigCaptureCameraSourcePipelineConfiguration setClientIsAttachedInfraredMetadataSession:]
+ -[FigCaptureCameraSourcePipelineConfiguration setLowLightVideoNoiseReductionEnabled:]
+ -[FigCaptureCameraSourcePipelineConfiguration setTextureStyle:]
+ -[FigCaptureCameraSourcePipelineConfiguration setTextureStyleEnabled:]
+ -[FigCaptureCameraSourcePipelineConfiguration setTextureStyleRenderingVersion:]
+ -[FigCaptureCameraSourcePipelineConfiguration setTimewarpMode:]
+ -[FigCaptureCinematographyPipeline setTextureStyle:]
+ -[FigCaptureCinematographyPipelineConfiguration setDepthInferenceEnabled:]
+ -[FigCaptureCinematographyPipelineConfiguration setTextureStyle:]
+ -[FigCaptureCinematographyPipelineConfiguration setTextureStyleEnabled:]
+ -[FigCaptureCinematographyPipelineConfiguration setTextureStyleRenderingVersion:]
+ -[FigCaptureCustomExposureConfiguration _description]
+ -[FigCaptureCustomExposureConfiguration _initWithExposureDuration:minFrameRate:maxFrameRate:ISO:lensAperture:useSpotMetering:requestID:]
+ -[FigCaptureCustomExposureConfiguration description]
+ -[FigCaptureCustomExposureConfiguration isFullAuto]
+ -[FigCaptureCustomExposureConfiguration isFullManual]
+ -[FigCaptureCustomExposureConfiguration lensAperture]
+ -[FigCaptureDisplayLayout displayRegion]
+ -[FigCaptureDisplayLayout setDisplayRegion:]
+ -[FigCaptureDisplayLayoutMonitor initWithFBSDisplayLayoutMonitorCreateFunction:displayType:isV68Device:]
+ -[FigCaptureExposureLimits clampExposureDuration:ISO:lensAperture:]
+ -[FigCaptureExposureLimits defaultLensAperture]
+ -[FigCaptureExposureLimits description]
+ -[FigCaptureIrisSinkConfiguration personalPhotographerEnabled]
+ -[FigCaptureIrisSinkConfiguration secureSigningPhotoCaptureSupportEnabled]
+ -[FigCaptureIrisSinkConfiguration setPersonalPhotographerEnabled:]
+ -[FigCaptureIrisSinkConfiguration setSecureSigningPhotoCaptureSupportEnabled:]
+ -[FigCaptureIrisStillImageSettings copyForPersonalPhotographerWithSettingsID:rotationDegrees:mirrored:]
+ -[FigCaptureMagneticInterferenceMonitor _cancelExitZoneTimer]
+ -[FigCaptureMagneticInterferenceMonitor _handleMagneticInterferenceUpdate:]
+ -[FigCaptureMagneticInterferenceMonitor _setupExitZoneTimerWithDuration:]
+ -[FigCaptureMagneticInterferenceMonitor _setupStateMachine]
+ -[FigCaptureMagneticInterferenceMonitor _updateMagneticInterferenceDetectedState:]
+ -[FigCaptureMagneticInterferenceMonitor dealloc]
+ -[FigCaptureMagneticInterferenceMonitor init]
+ -[FigCaptureMagneticInterferenceMonitor isMonitoring]
+ -[FigCaptureMagneticInterferenceMonitor magneticInterferenceDetected]
+ -[FigCaptureMagneticInterferenceMonitor setMagneticInterferenceHandler:]
+ -[FigCaptureMagneticInterferenceMonitor setStylusDataReceivedDuringSession:]
+ -[FigCaptureMagneticInterferenceMonitor startMonitoringWithZone:]
+ -[FigCaptureMagneticInterferenceMonitor stopMonitoring]
+ -[FigCaptureMagneticInterferenceMonitor stylusDataReceivedDuringSession]
+ -[FigCaptureMetadataObjectSinkConfiguration cinematicVideoMetadataCaptureEnabled]
+ -[FigCaptureMetadataObjectSinkConfiguration copyWithZone:]
+ -[FigCaptureMetadataObjectSinkConfiguration copyXPCEncoding]
+ -[FigCaptureMetadataObjectSinkConfiguration initWithXPCEncoding:]
+ -[FigCaptureMetadataObjectSinkConfiguration isEqual:]
+ -[FigCaptureMetadataObjectSinkConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureMetadataObjectSinkConfiguration setCinematicVideoMetadataCaptureEnabled:]
+ -[FigCaptureMetadataSinkPipeline _buildMetadataSinkPipeline:graph:videoPreviewOutput:offlineVISMotionDataSourceOutput:metadataSourceOutputsByCategory:semanticMasksMetadataSourceOutput:captureDevice:faceTrackingPipelineStage:clientAuditToken:inferenceScheduler:delegate:]
+ -[FigCaptureMetadataSinkPipeline initWithConfiguration:graph:name:videoPreviewOutput:offlineVISMotionDataSourceOutput:metadataSourceOutputsByCategory:semanticMasksMetadataSourceOutput:captureDevice:faceTrackingPipelineStage:clientAuditToken:inferenceScheduler:delegate:]
+ -[FigCaptureMetadataSinkPipeline liveReconfigureForRotationDegrees:faceTrackingRotationDegrees:]
+ -[FigCaptureMetadataSinkPipelineConfiguration setCinematicVideoMetadataTrackingOutput:]
+ -[FigCaptureMetadataSinkPipelineConfiguration setContinuousAutoFocusTrackingMetadataSupported:]
+ -[FigCaptureMovieFileRecordingSettings setTimewarpMode:]
+ -[FigCaptureMovieFileRecordingSettings timewarpMode]
+ -[FigCaptureMovieFileSinkConfiguration cinematicVideoMetadataCaptureEnabledByClient]
+ -[FigCaptureMovieFileSinkConfiguration cinematicVideoMetadataCaptureEnabled]
+ -[FigCaptureMovieFileSinkConfiguration setCinematicVideoMetadataCaptureEnabled:]
+ -[FigCaptureMovieFileSinkConfiguration setCinematicVideoMetadataCaptureEnabledByClient:]
+ -[FigCaptureMovieFileSinkHeadPipeline _buildMovieFileSinkHeadPipeline:videoSourceCaptureOutputsByConnectionID:sourceStreamingSensorRawOutput:sourceStreamingHueMapOutput:sourceStreamingSemanticMasksOutput:audioSourceCaptureOutput:audioSourceCinematicAudioCaptureOutput:smartCameraInferenceOutput:detectedObjectBoxedMetadataOutputs:objectDetectionSourceOutput:metadataSourcePipelineOutputs:graph:parentPipeline:inferenceScheduler:captureDevicesByConnectionID:audioSourceDelegate:fileCoordinatorStatusDelegate:irisRequestDelegate:personalPhotographerCaptureDelegate:masterClock:workgroup:videoGreenGhostMitigationEnabled:]
+ -[FigCaptureMovieFileSinkHeadPipeline initWithConfiguration:videoSourceCaptureOutputsByConnectionID:sourceStreamingSensorRawOutput:sourceStreamingHueMapOutput:sourceStreamingSemanticMasksOutput:audioSourceCaptureOutput:audioSourceCinematicAudioCaptureOutput:smartCameraInferenceOutput:detectedObjectBoxedMetadataOutputs:objectDetectionSourceOutput:metadataSourcePipelineOutputs:graph:parentPipeline:inferenceScheduler:captureDevicesByConnectionID:audioSourceDelegate:fileCoordinatorStatusDelegate:irisRequestDelegate:personalPhotographerCaptureDelegate:masterClock:workgroup:videoGreenGhostMitigationEnabled:]
+ -[FigCaptureMovieFileSinkHeadPipeline personalPhotographerDelegate]
+ -[FigCaptureMovieFileSinkHeadPipelineConfiguration personalPhotographerEnabled]
+ -[FigCaptureMovieFileSinkHeadPipelineConfiguration setPersonalPhotographerEnabled:]
+ -[FigCaptureMovieFileSinkPipeline cinematographyObjectTrackingNode]
+ -[FigCaptureMovieFileSinkPipeline initWithConfiguration:videoSourceCaptureOutputsByConnectionID:sourceStreamingSensorRawOutput:sourceStreamingHueMapOutput:sourceStreamingSemanticMasksOutput:audioSourceCaptureOutput:audioSourceCinematicAudioCaptureOutput:smartCameraInferenceOutput:detectedObjectBoxedMetadataOutputs:objectDetectionSourceOutput:metadataSourcePipelineOutputs:graph:name:inferenceScheduler:captureDevicesByConnectionID:audioSourceDelegate:fileCoordinatorStatusDelegate:recordingStatusDelegate:irisRequestDelegate:personalPhotographerCaptureDelegate:multiCamClientCompositingCallback:masterClock:delayedCompressorCleanupEnabled:]
+ -[FigCaptureMovieFileSinkPipeline liveReconfigureForRotationDegrees:needToTransposeVISPipeline:]
+ -[FigCaptureMovieFileSinkPipeline loadInferenceNetworksForHVS]
+ -[FigCaptureMovieFileSinkPipeline personalPhotographerDelegate]
+ -[FigCaptureMovieFileSinkPipeline setMovieRecordingEndOfDataBehavior:]
+ -[FigCaptureMovieFileSinkPipeline setTextureStyle:]
+ -[FigCaptureMovieFileSinkPipeline updateCinematicVideoMetadataCaptureEnabled:]
+ -[FigCaptureMovieFileSinkPipelineConfiguration personalPhotographerEnabled]
+ -[FigCaptureMovieFileSinkPipelineConfiguration setCinematicVideoMetadataEnabled:]
+ -[FigCaptureMovieFileSinkPipelineConfiguration setLowLightVideoNoiseReductionEnabled:]
+ -[FigCaptureMovieFileSinkPipelineConfiguration setPersonalPhotographerEnabled:]
+ -[FigCaptureMovieFileSinkPipelineConfiguration setPersonalPhotographerTypicalCaptureLatencyInSeconds:]
+ -[FigCaptureMovieFileSinkPipelineConfiguration setTextureStyleEnabled:]
+ -[FigCaptureMovieFileSinkTailPipeline cinematographyObjectTrackingNode]
+ -[FigCaptureMovieFileSinkTailPipeline setTextureStyle:]
+ -[FigCaptureMovieFileSinkTailPipelineConfiguration cinematicVideoMetadataEnabled]
+ -[FigCaptureMovieFileSinkTailPipelineConfiguration setCinematicVideoMetadataEnabled:]
+ -[FigCapturePreviewSinkPipeline _appendFilteredPreviewPipeline:desiredPipelineStage:desiredStreamingFilterPipelineStage:previewSinkPipelineConfiguration:videoPreviewSinkConnectionConfiguration:graph:inferenceScheduler:captureDevice:focusBlurMapForDepthFiltersEnabled:depthFromMonocularNetworkEnabled:runMonocularDepthInVideoDepthNode:maxLossyCompressionLevel:metalCommandQueue:depthFilterRenderingIsAfterPreviewStitcher:portraitAutoSuggestEnabled:sourceStillImageOutputsByPortType:usePrimaryPreviewSourceAttachedMediaForInference:insertVideoDepthNodeForCinematic:]
+ -[FigCapturePreviewSinkPipeline _buildVideoPreviewSinkPipeline:sourcePreviewOutput:sourceSensorRawPreviewOutput:sourceHueMapPreviewOutput:graph:inferenceScheduler:captureDevice:previewTapDelegate:zoomPIPOverlayDelegate:personalPhotographerCaptureDelegate:sourceStillImageOutputsByPortType:]
+ -[FigCapturePreviewSinkPipeline initWithConfiguration:sourcePreviewOutput:sourceSensorRawPreviewOutput:sourceHueMapPreviewOutput:imageQueueSinkNode:graph:name:inferenceScheduler:captureDevice:previewTapDelegate:zoomPIPOverlayDelegate:personalPhotographerCaptureDelegate:sourceStillImageOutputsByPortType:]
+ -[FigCapturePreviewSinkPipeline loadInferenceNetworksForHVS]
+ -[FigCapturePreviewSinkPipeline personalPhotographerDelegate]
+ -[FigCapturePreviewSinkPipeline previewStabilizationNode]
+ -[FigCapturePreviewSinkPipelineConfiguration cinematicVideoEnabled]
+ -[FigCapturePreviewSinkPipelineConfiguration personalPhotographerEnabled]
+ -[FigCapturePreviewSinkPipelineConfiguration sceneClassifierPipelineIsSharedWithLivePhotoVitalityScoring]
+ -[FigCapturePreviewSinkPipelineConfiguration setCinematicVideoSDOFRenderingEnabled:]
+ -[FigCapturePreviewSinkPipelineConfiguration setDepthInferenceForCinematicVideoEnabled:]
+ -[FigCapturePreviewSinkPipelineConfiguration setPersonalPhotographerEnabled:]
+ -[FigCaptureSessionConfiguration coexistenceWithInfraredSourceEnabled]
+ -[FigCaptureSessionConfiguration setTextureStyle:]
+ -[FigCaptureSessionConfiguration setTextureStyleEnabled:]
+ -[FigCaptureSessionConfiguration textureStyleEnabled]
+ -[FigCaptureSessionConfiguration textureStyle]
+ -[FigCaptureSessionParsedCameraSourceConfiguration cinematicVideoMetadataDeliveryEnabled]
+ -[FigCaptureSessionParsedConfiguration textureStyleEnabled]
+ -[FigCaptureSessionParsedConfiguration textureStyle]
+ -[FigCaptureSourceAttributes lowCurrentTorchSupported]
+ -[FigCaptureSourceAttributes maxLensAperture]
+ -[FigCaptureSourceAttributes minLensAperture]
+ -[FigCaptureSourceAttributes primaryConstituentDeviceSwitchingBehaviorLockedWithDeviceSupported]
+ -[FigCaptureSourceAttributes recommendedLensApertures]
+ -[FigCaptureSourceAttributes supportedExposureSignals]
+ -[FigCaptureSourceCommonSettings cinematicVideoWithoutEmbeddedDepthSupported]
+ -[FigCaptureSourceCommonSettings colorAssistedInfraredMetadataCameraSupported]
+ -[FigCaptureSourceCommonSettings magneticInterferenceMitigationRequired]
+ -[FigCaptureSourceCommonSettings textureStyleRenderingVersion]
+ -[FigCaptureSourceConfiguration activeOmahaConstituentDeviceType]
+ -[FigCaptureSourceConfiguration faceIDCoexistenceEnabled]
+ -[FigCaptureSourceConfiguration isCinematicVideoMetadataCaptureEnabled]
+ -[FigCaptureSourceConfiguration setActiveOmahaConstituentDeviceType:]
+ -[FigCaptureSourceConfiguration setCinematicVideoMetadataCaptureEnabled:]
+ -[FigCaptureSourceConfiguration setFaceIDCoexistenceEnabled:]
+ -[FigCaptureSourceConfiguration setTimewarpEnabled:]
+ -[FigCaptureSourceConfiguration timewarpEnabled]
+ -[FigCaptureSourceExtendedAttributes adaptiveFusionSupported]
+ -[FigCaptureSourceExtendedAttributes magneticInterferenceZone]
+ -[FigCaptureSourceExtendedAttributes tnrMachineLearningImageRegistrationSupported]
+ -[FigCaptureSourceManager _clearDeviceAngleState]
+ -[FigCaptureSourceManager _clearOmahaRenoAngleWithinDropZone]
+ -[FigCaptureSourceManager _handleMagneticInterferenceChange:]
+ -[FigCaptureSourceManager _handleOmahaRenoAngleWithinDropZoneState:]
+ -[FigCaptureSourceManager _magneticInterferenceZoneFromActiveSources]
+ -[FigCaptureSourceManager _updateDeviceAngleState]
+ -[FigCaptureSourceManager _updateOccludedState]
+ -[FigCaptureSourceManager layoutMonitor:didUpdateLayout:]
+ -[FigCaptureSourceVideoFormat configureForFullFullUltraHighResolutionZeroShutterLagSupport]
+ -[FigCaptureSourceVideoFormat faceIDCompanionFormat]
+ -[FigCaptureSourceVideoFormat isAdaptiveFusionSupported]
+ -[FigCaptureSourceVideoFormat isAutoFullFullUltraHighResolutionZeroShutterLagSupported]
+ -[FigCaptureSourceVideoFormat isCinematicMetadataCaptureSupported]
+ -[FigCaptureSourceVideoFormat isContinuousAutoFocusTrackingSupported]
+ -[FigCaptureSourceVideoFormat isFaceIDCoexistenceSupported]
+ -[FigCaptureSourceVideoFormat isLearnedFusionEnhancedResolutionSupported]
+ -[FigCaptureSourceVideoFormat isLearnedFusionUltraHighResolutionSupported]
+ -[FigCaptureSourceVideoFormat isLowLightVideoNoiseReductionSupported]
+ -[FigCaptureSourceVideoFormat isPersonalPhotographerSupported]
+ -[FigCaptureSourceVideoFormat isSecureSigningFaceIDSupported]
+ -[FigCaptureSourceVideoFormat isSecureSigningPhotoCaptureSupported]
+ -[FigCaptureSourceVideoFormat isTextureStyleBaseLookSupported]
+ -[FigCaptureSourceVideoFormat isTextureStyleSupported]
+ -[FigCaptureStillImageSettings activeOmahaConstituentDeviceType]
+ -[FigCaptureStillImageSettings autoSecureSigningPhotoCaptureEnabled]
+ -[FigCaptureStillImageSettings copyForPersonalPhotographerWithSettingsID:rotationDegrees:mirrored:]
+ -[FigCaptureStillImageSettings personalPhotographerCaptureRate]
+ -[FigCaptureStillImageSettings personalPhotographerCapture]
+ -[FigCaptureStillImageSettings setActiveOmahaConstituentDeviceType:]
+ -[FigCaptureStillImageSettings setAutoSecureSigningPhotoCaptureEnabled:]
+ -[FigCaptureStillImageSettings setCaptureRequestIdentifier:]
+ -[FigCaptureStillImageSettings setPersonalPhotographerCapture:]
+ -[FigCaptureStillImageSettings setPersonalPhotographerCaptureRate:]
+ -[FigCaptureStillImageSettings setSettingsID:]
+ -[FigCaptureStillImageSettings setTextureStyle:]
+ -[FigCaptureStillImageSettings textureStyle]
+ -[FigCaptureTextureStyle _initWithPreset:intensity:grain:]
+ -[FigCaptureTextureStyle copyWithZone:]
+ -[FigCaptureTextureStyle copyXPCEncoding]
+ -[FigCaptureTextureStyle dealloc]
+ -[FigCaptureTextureStyle debugDescription]
+ -[FigCaptureTextureStyle description]
+ -[FigCaptureTextureStyle dictionaryRepresentation]
+ -[FigCaptureTextureStyle encodeWithCoder:]
+ -[FigCaptureTextureStyle grain]
+ -[FigCaptureTextureStyle hash]
+ -[FigCaptureTextureStyle initWithCoder:]
+ -[FigCaptureTextureStyle initWithXPCEncoding:]
+ -[FigCaptureTextureStyle intensity]
+ -[FigCaptureTextureStyle isEqual:]
+ -[FigCaptureTextureStyle isIdentity]
+ -[FigCaptureTextureStyle isStandardPreset]
+ -[FigCaptureTextureStyle preset]
+ -[FigCaptureVISPipeline _buildVISPipelineWithUpstreamOutput:graph:parentPipeline:videoCaptureConnectionConfiguration:pipelineStage:sdofPipelineStage:videoStabilizationType:motionAttachmentsSource:fillExtendedRowsOfOutputBuffer:overCaptureEnabled:stereoMode:videoStabilizationOverscanOverride:videoStabilizationStrength:motionMetadataPreloadingEnabled:visExecutionMode:pipelineTraceID:captureDevice:outputDimensions:generatedTransformsOutputDimensionsOverride:P3ToBT2020ConversionEnabled:stabilizeDepthAttachments:outputDepthDimensions:maxLossyCompressionLevel:videoSTFEnabled:videoGreenGhostMitigationEnabled:lightSourceMaskAndKeypointDescriptorDataEnabled:videoGreenGhostOfflineMetadataEnabled:videoGreenGhostOfflineLightSourceMaskEnabled:personSegmentationRenderingEnabled:smartStyleRenderingEnabled:smartStyleReversibilityEnabled:textureStyleRenderingEnabled:lowResImageUsedByVideoEncoderEnabled:portTypesWithGeometricDistortionCorrectionInVISEnabled:visProcessingSemaphore:]
+ -[FigCaptureVISPipeline _newVISNodeWithUpstreamOutput:graph:parentPipeline:videoCaptureConnectionConfiguration:videoStabilizationType:motionAttachmentsSource:fillExtendedRowsOfOutputBuffer:overCaptureEnabled:stereoMode:videoStabilizationOverscanOverride:videoStabilizationStrength:motionMetadataPreloadingEnabled:visExecutionMode:pipelineTraceID:pipelineStage:captureDevice:outputDimensions:generatedTransformsOutputDimensionsOverride:irisVISCleanOutputRectOut:P3ToBT2020ConversionEnabled:stabilizeDepthAttachments:outputDepthDimensions:maxLossyCompressionLevel:videoSTFEnabled:videoGreenGhostMitigationEnabled:lightSourceMaskAndKeypointDescriptorDataEnabled:videoGreenGhostOfflineMetadataEnabled:videoGreenGhostOfflineLightSourceMaskEnabled:personSegmentationRenderingEnabled:smartStyleRenderingEnabled:smartStyleReversibilityEnabled:textureStyleRenderingEnabled:lowResImageUsedByVideoEncoderEnabled:portTypesWithGeometricDistortionCorrectionInVISEnabled:visProcessingSemaphore:]
+ -[FigCaptureVISPipeline initWithUpstreamOutput:graph:name:parentPipeline:videoCaptureConnectionConfiguration:pipelineStage:sdofPipelineStage:videoStabilizationType:motionAttachmentsSource:fillExtendedRowsOfOutputBuffer:overCaptureEnabled:stereoMode:videoStabilizationOverscanOverride:videoStabilizationStrength:motionMetadataPreloadingEnabled:visExecutionMode:pipelineTraceID:captureDevice:outputDimensions:generatedTransformsOutputDimensionsOverride:P3ToBT2020ConversionEnabled:stabilizeDepthAttachments:outputDepthDimensions:maxLossyCompressionLevel:videoSTFEnabled:videoGreenGhostMitigationEnabled:lightSourceMaskAndKeypointDescriptorDataEnabled:videoGreenGhostOfflineMetadataEnabled:videoGreenGhostOfflineLightSourceMaskEnabled:personSegmentationRenderingEnabled:smartStyleRenderingEnabled:smartStyleReversibilityEnabled:textureStyleRenderingEnabled:lowResImageUsedByVideoEncoderEnabled:portTypesWithGeometricDistortionCorrectionInVISEnabled:visProcessingSemaphore:]
+ -[FigCaptureVISPipeline setTextureStyle:]
+ -[FigCaptureVideoDataSinkConfiguration cinematicVideoMetadataCaptureEnabled]
+ -[FigCaptureVideoDataSinkConfiguration setCinematicVideoMetadataCaptureEnabled:]
+ -[FigCaptureVideoDataSinkPipeline cinematicVideoMetadataCaptureEnabled]
+ -[FigCaptureVideoDataSinkPipeline liveReconfigureForRotationDegrees:needToTransposeVISPipeline:]
+ -[FigCaptureVideoDataSinkPipelineConfiguration cinematicVideoCaptureEnabled]
+ -[FigCaptureVideoDataSinkPipelineConfiguration setCinematicVideoMetadataCaptureEnabled:]
+ -[FigCaptureVideoDataSinkPipelineConfiguration setDepthInferenceForCinematicVideoEnabled:]
+ -[FigCaptureVideoPreviewSinkConfiguration overCaptureGradientPercentInset]
+ -[FigCaptureVideoPreviewSinkConfiguration primaryDisplayRegion]
+ -[FigCaptureVideoPreviewSinkConfiguration setOverCaptureGradientPercentInset:]
+ -[FigCaptureVideoPreviewSinkConfiguration setPrimaryDisplayRegion:]
+ -[FigFlashlight setLowCurrentTorchEnabled:]
+ -[FigFlashlightLocal setLowCurrentTorchEnabled:]
+ -[FigMetadataObjectCaptureConnectionConfiguration faceIDConfiguration]
+ -[FigMetadataObjectCaptureConnectionConfiguration rawFrameDeliveryEnabled]
+ -[FigMetadataObjectCaptureConnectionConfiguration setFaceIDConfiguration:]
+ -[FigMetadataObjectCaptureConnectionConfiguration setRawFrameDeliveryEnabled:]
+ -[FigVideoCaptureConnectionConfiguration lowLightVideoNoiseReductionEnabled]
+ -[FigVideoCaptureConnectionConfiguration setLowLightVideoNoiseReductionEnabled:]
+ -[FigVideoCaptureConnectionConfiguration setTimewarpDestinationFrameRate:]
+ -[FigVideoCaptureConnectionConfiguration setTimewarpMode:]
+ -[FigVideoCaptureConnectionConfiguration timewarpDestinationFrameRate]
+ -[FigVideoCaptureConnectionConfiguration timewarpMode]
+ -[SubjectSelection updateStatesUsingDetectedObjects:currentPTS:trackedSubjectsByGroupIDOut:pixelBufferSize:nondisruptiveSwitchingFormatZoomFactor:]
+ -[TrackedSubject distance]
+ -[TrackedSubject initWithGroupID:significanceDetectionThreshold:smartFramingSceneMonitorMode:isPet:vipDetectionThreshold:vipDetectionDurationTimeInSeconds:vipDropOffThreshold:vipDropOffDurationTimeInSeconds:motionFilteringWeightDecayRatio:]
+ -[TrackedSubject isSignificantForApertureControl]
+ -[TrackedSubject isVIPSignificant]
+ -[TrackedSubject motionInPreviewPixels]
+ -[TrackedSubject resetTrajectoryHistory]
+ -[TrackedSubject updateStatesUsingTrackedRect:trackedRectSize:gazeProbabilitiesData:largestFaceSize:totalDetectedFaceCount:currentPTS:distance:pixelBufferSize:vipConfidence:unscaledTrackedRect:]
+ BWCreateSampleBufferWithFaceIDDictionary
+ CMCaptureGestaltGetBoolAnswer
+ FigCaptureCopyInternalDaemonDataContainerURL
+ FigCaptureCopyInternalDaemonDataContainerURL.sOnceToken
+ FigCaptureCopyInternalDaemonDataContainerURL.sSigningIdentifier
+ FigCaptureSmartStyleSettingsGetSystemTextureStyle
+ FigCaptureSourceSetMagneticInterferenceDetected
+ FigCaptureSourceSetMagneticInterferenceMonitor
+ GCC_except_table106
+ GCC_except_table120
+ GCC_except_table147
+ GCC_except_table202
+ GCC_except_table232
+ GCC_except_table252
+ GCC_except_table303
+ GCC_except_table347
+ GCC_except_table348
+ GCC_except_table359
+ GCC_except_table374
+ GCC_except_table406
+ GCC_except_table432
+ GCC_except_table434
+ GCC_except_table44
+ GCC_except_table451
+ GCC_except_table468
+ GCC_except_table520
+ GCC_except_table555
+ GCC_except_table577
+ GCC_except_table582
+ GCC_except_table584
+ GCC_except_table586
+ GCC_except_table66
+ GCC_except_table72
+ GCC_except_table74
+ GCC_except_table742
+ GCC_except_table99
+ OBJC_IVAR_$_BWAudioConverterNode._movieRecordingEndOfDataBehavior
+ OBJC_IVAR_$_BWBaselineTextureStyleRenderer._baselineTextureStylesProcessor
+ OBJC_IVAR_$_BWBaselineTextureStyleRenderer._configuration
+ OBJC_IVAR_$_BWCinematicVideoMetadataNode._disabled
+ OBJC_IVAR_$_BWCinematicVideoMetadataNode._useRawCinematography
+ OBJC_IVAR_$_BWCinematographyObjectTrackingNode._cinematographyModelVersionString
+ OBJC_IVAR_$_BWCinematographyObjectTrackingNode._disabled
+ OBJC_IVAR_$_BWCinematographyObjectTrackingNode._globalMetadata
+ OBJC_IVAR_$_BWCinematographyObjectTrackingNode._metadataCollectionSize
+ OBJC_IVAR_$_BWDeferredPipelineParameters._portTypesWithTextureStyleBaseLookEnabled
+ OBJC_IVAR_$_BWDeferredPipelineParameters._textureStyleBaseLookEnabled
+ OBJC_IVAR_$_BWDeferredPipelineParameters._textureStyleCreativeEffectsEnabled
+ OBJC_IVAR_$_BWDeferredPipelineParameters._textureStyleFSINCMasksRequired
+ OBJC_IVAR_$_BWDeferredPipelineParameters._textureStyleRenderingVersion
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._activeExposureSignals
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._activeOmahaConstituentDeviceType
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._activeZeroShutterLagFlavorHighResolutionFlavor
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._adaptiveFusionDowngradeSceneByPortType
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._apertureControlSceneMonitorEnabled
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._autoFullFullUltraHighResolutionZeroShutterLagEnabledByOmahaConstituentPortType
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._automaticallyIgnoresExposureSignals
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._cameraControlsSemanticHints
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._cameraControlsSemanticHintsLock
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._continuousAutoFocusTrackingChangedDelegate
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._depthSupportedWithUltraHighResolutionCaptures
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._hasAdaptiveFusion
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._highResolutionSecureSigningNondisruptiveSwitchingFormatIndexByPortType
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._ignoredExposureSignals
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._learnedFusionHighResolutionDowngradeSceneByPortType
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._learnedNRWithShutterPriorityEnabled
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._lensAperture
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._lowLightVideoNoiseReductionEnabled
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._magneticInterferenceDetected
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._magneticInterferenceMonitor
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._numberOfMagneticInterferenceEventsDetected
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._omahaConstituentDeviceLiveReconfigurationInProgress
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._omahaRenoAngleWithinDropZone
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._omahaRenoCaptureStream
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._omahaRenoRotationOffsetDegrees
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._overrideIgnoredExposureSignalValues
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._overrideIgnoredExposureSignals
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._pendingLensApertureChange
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._personalPhotographerEnabled
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._personalPhotographerSceneMonitor
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._personalPhotographerSceneMonitorLock
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._personalPhotographerSessionActive
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._personalPhotographerStatus
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._personalPhotographerSubjectDetected
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._resolvedIgnoredExposureSignals
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._secureSigningPhotoCaptureEnabled
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._secureSigningPhotoCaptureSupportEnabled
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._secureSigningQueue
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._segmentFocusTrackingEnabled
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._segmentFocusTrackingSupported
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._shutterSoundRelaxationEnabledForDisplayRegion
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._supportedExposureSignals
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._timewarpActive
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._timewarpEnabled
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._timewarpMode
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._ultraHighResolutionZeroShutterLagSupportEnabledByOmahaConstituentPortType
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._zeroShutterLagEnabledByOmahaConstituentPortType
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._zeroShutterLagTimeMachineBufferCapacityByOmahaConstituentPortType
+ OBJC_IVAR_$_BWFigVideoCaptureStream._activeSecureSigningMode
+ OBJC_IVAR_$_BWFigVideoCaptureStream._autoExposureLensApertureRateLimit
+ OBJC_IVAR_$_BWFigVideoCaptureStream._defaultLensAperture
+ OBJC_IVAR_$_BWFigVideoCaptureStream._faceIDFrameTracker
+ OBJC_IVAR_$_BWFigVideoCaptureStream._faceImageQualityDetectionEnabled
+ OBJC_IVAR_$_BWFigVideoCaptureStream._ignoredExposureSignals
+ OBJC_IVAR_$_BWFigVideoCaptureStream._isOmahaVariant
+ OBJC_IVAR_$_BWFigVideoCaptureStream._maxLensAperture
+ OBJC_IVAR_$_BWFigVideoCaptureStream._minLensAperture
+ OBJC_IVAR_$_BWFigVideoCaptureStream._supportedExposureSignals
+ OBJC_IVAR_$_BWFigVideoCaptureStream._timewarpEnabled
+ OBJC_IVAR_$_BWFigVideoCaptureStream._tnrMachineLearningImageRegistrationSupported
+ OBJC_IVAR_$_BWFileCoordinatorNode._currTimewarpPTS
+ OBJC_IVAR_$_BWFileCoordinatorNode._movieRecordingEndOfDataBehavior
+ OBJC_IVAR_$_BWFileCoordinatorNode._timewarpEnabled
+ OBJC_IVAR_$_BWFileCoordinatorNode._timewarpFrameDuration
+ OBJC_IVAR_$_BWFileCoordinatorNode._timewarpFrameDurationForCapture
+ OBJC_IVAR_$_BWFrameStatistics._defaultFNumber
+ OBJC_IVAR_$_BWGlobalTextureStyleRenderer._configuration
+ OBJC_IVAR_$_BWGlobalTextureStyleRenderer._globalTextureStylesProcessor
+ OBJC_IVAR_$_BWGlowTextureStyleRenderer._configuration
+ OBJC_IVAR_$_BWGlowTextureStyleRenderer._glowTextureStylesProcessor
+ OBJC_IVAR_$_BWGlowTextureStyleRenderer._outputFormatDescription
+ OBJC_IVAR_$_BWGlowTextureStyleRenderer._smartStyleClass
+ OBJC_IVAR_$_BWGraph._liveExtensionSourceNodes
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._allPromotedFrameMetadata
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._autoFramesEvictedByManualIDs
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._breakDuplicateChains
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._breakPauseThresholdsInMS
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._bucketEntryTime
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._bucketFrame
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._budgetEnabled
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._budgetType
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._candidateEntryTimes
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._captureFolder
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._captureStartTime
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._cleanDuplicatesEnabled
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._contextCandidates
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._contextPriorities
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._currentSegmentIsValid
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._delegate
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._dumpInput
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._duplicateConstraintType
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._duplicateMaxTimeInMs
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._duplicateThresholds
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._failedCaptureFrameIDs
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._fixedBudgetMaxFrames
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._fixedBudgetMode
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._foundAnyValidCandidate
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._framePromotionHandler
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._frameRemovalHandler
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._framesToRemoveExtra
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._handlerContext
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._inPause
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._isFinalizingBudget
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._largeFacePerContext
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._legacy
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._manualFrameIDs
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._maxCandidateAgeInSec
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._maxCandidates
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._maxCandidatesPerContext
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._maxFramesPer20Sec
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._maxRTBucketAgeInSec
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._maxScoreFrame
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._minBudget
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._minCandidateProximityInSec
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._minPauseDurationInSec
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._minPercentageOfMaxScoreThresholds
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._minThresholds
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._mostRecentFrameDict
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._pauseBreakCounter
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._pauseFrame
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._pauseSegmentCounter
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._pauseStartTime
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._prevScore
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._previousSimScore
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._promotedFrames
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._promotedMaxScoreFrameID
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._promotedMaxScoreValue
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._promotedPauseFrameIDs
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._recoverExtras
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._removalHandlerContext
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._removedFramesForDuplicate
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._savePauseThresholdsInMS
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._simBoostPerContext
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._simThreshold
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._tinyFacePerContext
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._tinyFaceRatio
+ OBJC_IVAR_$_BWHVSCandidateFrameManager._tinyFaceReference
+ OBJC_IVAR_$_BWHVSEmbeddingAnalysisResult._contextProbabilities
+ OBJC_IVAR_$_BWHVSEmbeddingAnalysisResult._detectedContext
+ OBJC_IVAR_$_BWHVSEmbeddingAnalysisResult._frameScore
+ OBJC_IVAR_$_BWHVSEmbeddingAnalysisResult._imageEmbedding
+ OBJC_IVAR_$_BWHVSEmbeddingAnalysisResult._similarityScore
+ OBJC_IVAR_$_BWHVSFace._faceObservation
+ OBJC_IVAR_$_BWHVSFace._isFrontal
+ OBJC_IVAR_$_BWHVSFrame._auxScore
+ OBJC_IVAR_$_BWHVSFrame._captureSettingsID
+ OBJC_IVAR_$_BWHVSFrame._cropPenalty
+ OBJC_IVAR_$_BWHVSFrame._deviceSharpnessIntercept
+ OBJC_IVAR_$_BWHVSFrame._deviceSharpnessSlope
+ OBJC_IVAR_$_BWHVSFrame._duplicateInfo
+ OBJC_IVAR_$_BWHVSFrame._ev0RawCaptureID
+ OBJC_IVAR_$_BWHVSFrame._faceObservations
+ OBJC_IVAR_$_BWHVSFrame._finalCropRectLaplacianVariance
+ OBJC_IVAR_$_BWHVSFrame._frameID
+ OBJC_IVAR_$_BWHVSFrame._frameScore
+ OBJC_IVAR_$_BWHVSFrame._frameStatisticsByPortType
+ OBJC_IVAR_$_BWHVSFrame._frameTrackingEntry
+ OBJC_IVAR_$_BWHVSFrame._isManualCapture
+ OBJC_IVAR_$_BWHVSFrame._isPauseFrame
+ OBJC_IVAR_$_BWHVSFrame._maxFaceProminence
+ OBJC_IVAR_$_BWHVSFrame._metadata
+ OBJC_IVAR_$_BWHVSFrame._orientation
+ OBJC_IVAR_$_BWHVSFrame._originalCameraIntrinsicMatrix
+ OBJC_IVAR_$_BWHVSFrame._originalCameraIntrinsicMatrixReferenceDimensions
+ OBJC_IVAR_$_BWHVSFrame._pauseDurationInSec
+ OBJC_IVAR_$_BWHVSFrame._people
+ OBJC_IVAR_$_BWHVSFrame._personMaskPNGData
+ OBJC_IVAR_$_BWHVSFrame._petCropPenalty
+ OBJC_IVAR_$_BWHVSFrame._pets
+ OBJC_IVAR_$_BWHVSFrame._rawEV0SampleBuffer
+ OBJC_IVAR_$_BWHVSFrame._rawSIFRSampleBuffer
+ OBJC_IVAR_$_BWHVSFrame._sbufPresentationTimestamp
+ OBJC_IVAR_$_BWHVSFrame._segmentIdx
+ OBJC_IVAR_$_BWHVSFrame._sessionID
+ OBJC_IVAR_$_BWHVSFrame._sifrRawCaptureID
+ OBJC_IVAR_$_BWHVSFrame._stillImageCaptureMetadata
+ OBJC_IVAR_$_BWHVSFrame._stillImageSceneFlags
+ OBJC_IVAR_$_BWHVSFrame._timestamp
+ OBJC_IVAR_$_BWHVSFrame._unifiedEmbeddingsOutput
+ OBJC_IVAR_$_BWHVSFrame._yuvDimensions
+ OBJC_IVAR_$_BWHVSFrame._yuvPixelBuffer
+ OBJC_IVAR_$_BWHVSFrame._yuvPixelFormat
+ OBJC_IVAR_$_BWHVSFrameAnalysisTask._analysisEnabled
+ OBJC_IVAR_$_BWHVSFrameAnalysisTask._faceObservations
+ OBJC_IVAR_$_BWHVSFrameAnalysisTask._faceQualitySampleBuffer
+ OBJC_IVAR_$_BWHVSFrameAnalysisTask._imageEmbedding
+ OBJC_IVAR_$_BWHVSFrameAnalysisTask._imageEmbeddingSampleBuffer
+ OBJC_IVAR_$_BWHVSFrameAnalysisTask._loggingPrefix
+ OBJC_IVAR_$_BWHVSFrameAnalysisTask._matchingMainSensorRawSampleBuffer
+ OBJC_IVAR_$_BWHVSFrameAnalysisTask._matchingSIFRSensorRawSampleBuffer
+ OBJC_IVAR_$_BWHVSFrameAnalysisTask._personMaskPNGData
+ OBJC_IVAR_$_BWHVSFrameAnalysisTask._sharpnessResults
+ OBJC_IVAR_$_BWHVSFrameAnalysisTask._subtaskGroup
+ OBJC_IVAR_$_BWHVSFrameAnalysisTask._yuvSampleBuffer
+ OBJC_IVAR_$_BWHVSObject._boundingBox
+ OBJC_IVAR_$_BWHVSObject._confidence
+ OBJC_IVAR_$_BWHVSObject._groupID
+ OBJC_IVAR_$_BWHVSObject._imageDimensions
+ OBJC_IVAR_$_BWHVSObject._laplacianVariance
+ OBJC_IVAR_$_BWHVSPerson._body
+ OBJC_IVAR_$_BWHVSPerson._face
+ OBJC_IVAR_$_BWHVSPet._body
+ OBJC_IVAR_$_BWHVSPet._face
+ OBJC_IVAR_$_BWHVSScoringNode._bufferedYUVInputSampleBuffer
+ OBJC_IVAR_$_BWHVSScoringNode._candidateFrameManager
+ OBJC_IVAR_$_BWHVSScoringNode._candidateManagerLock
+ OBJC_IVAR_$_BWHVSScoringNode._captureDevice
+ OBJC_IVAR_$_BWHVSScoringNode._captureMode
+ OBJC_IVAR_$_BWHVSScoringNode._consecutiveFramesWithoutSubject
+ OBJC_IVAR_$_BWHVSScoringNode._contextEmbeddingsFP32
+ OBJC_IVAR_$_BWHVSScoringNode._currentSettingsID
+ OBJC_IVAR_$_BWHVSScoringNode._delayYUVInputByOneFrame
+ OBJC_IVAR_$_BWHVSScoringNode._delegate
+ OBJC_IVAR_$_BWHVSScoringNode._downscaledYUVPixelBuffer
+ OBJC_IVAR_$_BWHVSScoringNode._enableFaceQualityInference
+ OBJC_IVAR_$_BWHVSScoringNode._enableImageEmbeddingInference
+ OBJC_IVAR_$_BWHVSScoringNode._enableSegmentationMaskFallback
+ OBJC_IVAR_$_BWHVSScoringNode._enableSharpnessDetection
+ OBJC_IVAR_$_BWHVSScoringNode._faceQualityDispatchQueue
+ OBJC_IVAR_$_BWHVSScoringNode._hueMapInput
+ OBJC_IVAR_$_BWHVSScoringNode._hvsConfig
+ OBJC_IVAR_$_BWHVSScoringNode._hvsEmbeddings
+ OBJC_IVAR_$_BWHVSScoringNode._imageEmbeddingsDispatchQueue
+ OBJC_IVAR_$_BWHVSScoringNode._laplacianScratchBuffer
+ OBJC_IVAR_$_BWHVSScoringNode._laplacianScratchBufferSize
+ OBJC_IVAR_$_BWHVSScoringNode._lastFrame
+ OBJC_IVAR_$_BWHVSScoringNode._lastFrameAvailabilitySemaphore
+ OBJC_IVAR_$_BWHVSScoringNode._lastInitiatedSIFRSbufPTS
+ OBJC_IVAR_$_BWHVSScoringNode._lastRenderedPTS
+ OBJC_IVAR_$_BWHVSScoringNode._loggingPrefix
+ OBJC_IVAR_$_BWHVSScoringNode._m2mController
+ OBJC_IVAR_$_BWHVSScoringNode._manualCapturePending
+ OBJC_IVAR_$_BWHVSScoringNode._manualFramePendingRegistration
+ OBJC_IVAR_$_BWHVSScoringNode._multiFramePipeliningEnabled
+ OBJC_IVAR_$_BWHVSScoringNode._numActivePromptEmbeddings
+ OBJC_IVAR_$_BWHVSScoringNode._numFramesWithOutOfSyncSemanticMasks
+ OBJC_IVAR_$_BWHVSScoringNode._numFramesWithoutHueMap
+ OBJC_IVAR_$_BWHVSScoringNode._numFramesWithoutMainSensorRaw
+ OBJC_IVAR_$_BWHVSScoringNode._numFramesWithoutSIFRSensorRaw
+ OBJC_IVAR_$_BWHVSScoringNode._numFramesWithoutSemanticMasks
+ OBJC_IVAR_$_BWHVSScoringNode._numProcessedFrames
+ OBJC_IVAR_$_BWHVSScoringNode._numPromptPairs
+ OBJC_IVAR_$_BWHVSScoringNode._orientationHistory
+ OBJC_IVAR_$_BWHVSScoringNode._pinnedGroupIDs
+ OBJC_IVAR_$_BWHVSScoringNode._preparedInferences
+ OBJC_IVAR_$_BWHVSScoringNode._prevFrameNetworkOutput
+ OBJC_IVAR_$_BWHVSScoringNode._rawInput
+ OBJC_IVAR_$_BWHVSScoringNode._recommendedMasterPortType
+ OBJC_IVAR_$_BWHVSScoringNode._requestedSettings
+ OBJC_IVAR_$_BWHVSScoringNode._scheduledFrameAnalysisTask
+ OBJC_IVAR_$_BWHVSScoringNode._scoringEmbeddingsFP32
+ OBJC_IVAR_$_BWHVSScoringNode._semanticMasksInput
+ OBJC_IVAR_$_BWHVSScoringNode._sensorRawTimeMachine
+ OBJC_IVAR_$_BWHVSScoringNode._serializeInferences
+ OBJC_IVAR_$_BWHVSScoringNode._sessionActive
+ OBJC_IVAR_$_BWHVSScoringNode._sessionFinalizationPending
+ OBJC_IVAR_$_BWHVSScoringNode._sessionID
+ OBJC_IVAR_$_BWHVSScoringNode._sharedStateLock
+ OBJC_IVAR_$_BWHVSScoringNode._sharpnessDispatchQueue
+ OBJC_IVAR_$_BWHVSScoringNode._statusInfo
+ OBJC_IVAR_$_BWHVSScoringNode._statusInfoLock
+ OBJC_IVAR_$_BWHVSScoringNode._stillImageCoordinator
+ OBJC_IVAR_$_BWHVSScoringNode._stripSegmentationMask
+ OBJC_IVAR_$_BWHVSScoringNode._subjectDetectedStabilizationFrames
+ OBJC_IVAR_$_BWHVSScoringNode._wasSessionActive
+ OBJC_IVAR_$_BWHVSScoringNode._weightsPerCtx
+ OBJC_IVAR_$_BWHVSScoringNode._yuvInput
+ OBJC_IVAR_$_BWIrisStagingNode._textureStyleRenderingEnabled
+ OBJC_IVAR_$_BWLCBDatabaseManager._containerSandboxToken
+ OBJC_IVAR_$_BWLCBDatabaseManager._databasePathFolder
+ OBJC_IVAR_$_BWLCBDatabaseManager._databasePathPrefix
+ OBJC_IVAR_$_BWLCBDatabaseManager._databasesWereUpdated
+ OBJC_IVAR_$_BWLCBDatabaseManager._delegate
+ OBJC_IVAR_$_BWLCBDatabaseManager._lcbDatabaseByPortType
+ OBJC_IVAR_$_BWLCBDatabaseManager._lcbDatabaseQueue
+ OBJC_IVAR_$_BWMemoryAnalyticsPayload._captureTypeAdaptiveFusion
+ OBJC_IVAR_$_BWMovieFileOutputAnalyticsPayload._cinematicMetadataMovieRecordingStats
+ OBJC_IVAR_$_BWMovieFileOutputAnalyticsPayload._cinematicVideoMetadataEnabled
+ OBJC_IVAR_$_BWMultiCamConfiguration._colorAssistedSecureFaceIDEnabled
+ OBJC_IVAR_$_BWMultiCamConfiguration._mutuallyExclusiveUnsynchronizedStreamsPortTypes
+ OBJC_IVAR_$_BWMultiCamConfiguration._secureProcessingCoexEnabled
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNode._faceIDOutput
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNode._isUnsynchronizedPrimary
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNode._isUnsynchronizedPrimaryLock
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNode._lastFocusTrackedObjectPTS
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNode._lastPrimaryStreamingOutputISPAppliedZoomFactor
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNode._mostRecentFocusTrackedObject
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNode._previewStabilizationShift
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNode._previewStabilizationShiftLock
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNodeConfiguration._faceImageQualityDetectionEnabled
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNodeConfiguration._focusTrackedObjectsDeliveryEnabled
+ OBJC_IVAR_$_BWMultiStreamCameraSourceNodeConfiguration._secureStreamingForFaceIDEnabled
+ OBJC_IVAR_$_BWNondisruptiveSwitchingFormatSelector._ultraHighResolutionSecureSigningNondisruptiveStreamingFormatIndex
+ OBJC_IVAR_$_BWNondisruptiveSwitchingFormatSelector._zoomFactorToNondisruptiveSwitchingFormatIndexSecureSigning
+ OBJC_IVAR_$_BWOverCaptureSmartStyleApplyNode._skinSmoothMaskState
+ OBJC_IVAR_$_BWPersonalPhotographerSceneMonitorV1._lowStorageSpaceThresholdCheckRateSeconds
+ OBJC_IVAR_$_BWPersonalPhotographerSceneMonitorV1._maxPeakPowerPressureLevel
+ OBJC_IVAR_$_BWPersonalPhotographerSceneMonitorV1._maxThermalPressureLevel
+ OBJC_IVAR_$_BWPersonalPhotographerSceneMonitorV1._sceneIsTooDark
+ OBJC_IVAR_$_BWPersonalPhotographerSceneMonitorV1._sceneTooDarkMonitoringEnabled
+ OBJC_IVAR_$_BWPersonalPhotographerSceneMonitorV1._storageCheckLock
+ OBJC_IVAR_$_BWPersonalPhotographerSceneMonitorV1._storageCheckTimer
+ OBJC_IVAR_$_BWPersonalPhotographerSceneMonitorV1._storageSpaceIsTooLow
+ OBJC_IVAR_$_BWPersonalPhotographerSceneMonitorV1._storageSpaceThresholdCheckRateSeconds
+ OBJC_IVAR_$_BWPersonalPhotographerSceneMonitorV1._tuningParametersByPortType
+ OBJC_IVAR_$_BWPhotoEncoderController._provenanceDNGInfo
+ OBJC_IVAR_$_BWPhotoEncoderController._provenanceDNGInfoLock
+ OBJC_IVAR_$_BWPhotoEncoderController._provenanceDngEncoderManager
+ OBJC_IVAR_$_BWPhotoEncoderController._provenanceFormatDescription
+ OBJC_IVAR_$_BWPhotoEncoderControllerConfiguration._secureSigningPhotoCaptureSupportEnabled
+ OBJC_IVAR_$_BWPhotoEncoderControllerConfiguration._textureStyleCreativeEffectsEnabled
+ OBJC_IVAR_$_BWPhotoEncoderControllerInput._fsincMasksPrewarmedForCurrentEncoding
+ OBJC_IVAR_$_BWPhotoEncoderControllerRequest._provenanceDNGSurface
+ OBJC_IVAR_$_BWPhotoEncoderControllerRequest._provenanceDNGSurfaceSize
+ OBJC_IVAR_$_BWPreviewStabilizationNode._delegate
+ OBJC_IVAR_$_BWQuickTimeMovieFileSinkNode._cinematicMetadataMovieRecordingStats
+ OBJC_IVAR_$_BWQuickTimeMovieFileSinkNode._cinematicVideoMetadataEnabled
+ OBJC_IVAR_$_BWQuickTimeMovieFileSinkNode._deliveredCinematicMetadataMovieRecordingStats
+ OBJC_IVAR_$_BWQuickTimeMovieFileSinkNode._movieRecordingEndOfDataBehavior
+ OBJC_IVAR_$_BWQuickTimeMovieFileSinkNode._numberOfTimewarpTimelapseFramesWritten
+ OBJC_IVAR_$_BWQuickTimeMovieFileSinkNode._timewarpMode
+ OBJC_IVAR_$_BWQuickTimeMovieFileSinkNode._timewarpTimelapseMaxDecimationLevel
+ OBJC_IVAR_$_BWQuickTimeMovieFileSinkNode._timewarpTimelapseMaxSequenceNumber
+ OBJC_IVAR_$_BWRealtimeCinematographyNode._cinematicVideoDisparityProvider
+ OBJC_IVAR_$_BWSecureFaceIDFrameTracker._frameIdentifiers
+ OBJC_IVAR_$_BWSecureFaceIDFrameTracker._frameIdentifiersLock
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._colorCameraAssistEnabled
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._faceIDConfiguration
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._faceIDEnabled
+ OBJC_IVAR_$_BWSecureMetadataOutputConfiguration._rawFrameDeliveryEnabled
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._clientProvidedHash
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._clientProvidedHashHistory
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._delegate
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._fdrUnavailable
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._lowerBoundTimestampData
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._refreshTimer
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._sealingManifestData
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._sealingManifestError
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._sealingManifestUniqueIDData
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._secureBootTicketData
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._secureBootTicketError
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._sensorCertificateData
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._sensorCertificateError
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._sensorCertificateUniqueIDData
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._timestampQueue
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._trustObjectData
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._trustObjectDigestData
+ OBJC_IVAR_$_BWSecureSigningUtilityManager._trustObjectError
+ OBJC_IVAR_$_BWSemanticMasksConverterNode._configurationLock
+ OBJC_IVAR_$_BWSemanticMasksConverterNode._detectedObjectsOutput
+ OBJC_IVAR_$_BWSemanticMasksConverterNode._enabledSemanticMaskTypes
+ OBJC_IVAR_$_BWSemanticMasksConverterNode._focusTrackedObjectOutputEnabled
+ OBJC_IVAR_$_BWSemanticMasksConverterNode._rectOfInterest
+ OBJC_IVAR_$_BWSemanticMasksConverterNode._subjectAcquired
+ OBJC_IVAR_$_BWSemanticMasksConverterNode._subjectAcquiredChangedHandler
+ OBJC_IVAR_$_BWSemanticMasksConverterNode._subjectNotAcquiredFrameCount
+ OBJC_IVAR_$_BWSensorRawTimeMachine._configuration
+ OBJC_IVAR_$_BWSensorRawTimeMachine._lock
+ OBJC_IVAR_$_BWSensorRawTimeMachine._maxCounts
+ OBJC_IVAR_$_BWSensorRawTimeMachine._nonIncreasingPTSFailureCount
+ OBJC_IVAR_$_BWSensorRawTimeMachine._nonIncreasingPTSRadarThreshold
+ OBJC_IVAR_$_BWSensorRawTimeMachine._storedBuffers
+ OBJC_IVAR_$_BWSensorRawTimeMachine._worstCaseStoredBufferCounts
+ OBJC_IVAR_$_BWSensorRawTimeMachineConfiguration._frameConfigurationByFrameType
+ OBJC_IVAR_$_BWSensorRawTimeMachineConfiguration._name
+ OBJC_IVAR_$_BWSensorRawTimeMachineFrameConfiguration._allowedPTSDeltaFrameIntervalFactor
+ OBJC_IVAR_$_BWSensorRawTimeMachineFrameConfiguration._expectsFrameSkipping
+ OBJC_IVAR_$_BWSensorRawTimeMachineFrameConfiguration._maxCount
+ OBJC_IVAR_$_BWSkinTextureStyleRenderer._configuration
+ OBJC_IVAR_$_BWSkinTextureStyleRenderer._fileName
+ OBJC_IVAR_$_BWSkinTextureStyleRenderer._skinTextureStylesProcessor
+ OBJC_IVAR_$_BWSmartCropNode._activeOmahaConstituentDeviceType
+ OBJC_IVAR_$_BWSmartFramingSceneMonitor._subjectDistanceRangeInMM
+ OBJC_IVAR_$_BWSmartFramingSceneMonitor._subjectMotionSpeedPixelsPerSecond
+ OBJC_IVAR_$_BWSmartFramingSceneMonitorResult._persistentlySignificantSubjectCount
+ OBJC_IVAR_$_BWSmartFramingSceneMonitorResult._persistentlySignificantSubjectGroupIDs
+ OBJC_IVAR_$_BWSmartFramingSceneMonitorResult._significantSubjectCount
+ OBJC_IVAR_$_BWSmartFramingSceneMonitorResult._significantSubjectGroupIDs
+ OBJC_IVAR_$_BWSmartFramingSceneMonitorResult._subjectDistanceRange
+ OBJC_IVAR_$_BWSmartFramingSceneMonitorResult._subjectMotionPerSecond
+ OBJC_IVAR_$_BWSmartStyleApplyNode._skinSmoothMaskState
+ OBJC_IVAR_$_BWSmartStyleLearningNode._enableBloom
+ OBJC_IVAR_$_BWSmartStyleLearningNode._enableDiffusion
+ OBJC_IVAR_$_BWSmartStyleLearningNode._enableGlow
+ OBJC_IVAR_$_BWSmartStyleLearningNode._enableMattify
+ OBJC_IVAR_$_BWSmartStyleLearningNode._intermediatePixelBuffer
+ OBJC_IVAR_$_BWSmartStyleLearningNode._shouldApplyRadialExtension
+ OBJC_IVAR_$_BWSmartStyleLearningNode._statisticsToShare
+ OBJC_IVAR_$_BWSmartStyleLearningNode._targetPixelBufferWithTextureApplied
+ OBJC_IVAR_$_BWSmartStyleLearningNode._textureStyle
+ OBJC_IVAR_$_BWSmartStyleLearningNode._textureStyleEnabled
+ OBJC_IVAR_$_BWSmartStyleLearningNode._textureStylesProcessor
+ OBJC_IVAR_$_BWSmartStyleLearningNode._textureStylesProcessorHasBeenPrepared
+ OBJC_IVAR_$_BWSmartStyleRendererConfiguration._textureStyleCreativeEffectsEnabled
+ OBJC_IVAR_$_BWSmartStyleRendererConfiguration._textureStyleRenderingVersion
+ OBJC_IVAR_$_BWSphereModeSelector._magneticInterferenceDetected
+ OBJC_IVAR_$_BWStartupCalibrationAnalyticsPayload._hingeAngle
+ OBJC_IVAR_$_BWStartupCalibrationAnalyticsPayload._reason
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._activeExposureSignals
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._actualFNumber
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._apertureDiameter
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._ignoredExposureSignals
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._inputExposureSignals
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._maxVATrackingError
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._requestedFNumber
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._stdVATrackingError
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._textureStyleGrain
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._textureStyleIntensity
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._textureStylePreset
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._textureStyleRenderingSupported
+ OBJC_IVAR_$_BWStillImageAnalyticsPayloadCommon._variableApertureTemperature
+ OBJC_IVAR_$_BWStillImageCaptureAnalyticsPayload._lcbDetectionCountHistogram
+ OBJC_IVAR_$_BWStillImageCaptureAnalyticsPayload._lcbDetectionCountHistogramSet
+ OBJC_IVAR_$_BWStillImageCaptureAnalyticsPayload._numberOfLCBsCorrectedOnIRCF
+ OBJC_IVAR_$_BWStillImageCaptureAnalyticsPayload._numberOfLCBsCorrectedOnLens
+ OBJC_IVAR_$_BWStillImageCaptureAnalyticsPayload._numberOfLCBsDetected
+ OBJC_IVAR_$_BWStillImageCaptureMetadata._ignoredExposureSignals
+ OBJC_IVAR_$_BWStillImageCoordinatorNode._calibrationSettingsIDCounter
+ OBJC_IVAR_$_BWStillImageCoordinatorNode._calibrationTimer
+ OBJC_IVAR_$_BWStillImageDuplicateInfo._originalPresentationTimestamp
+ OBJC_IVAR_$_BWStillImageDuplicateInfo._sbufPresentationTimestamp
+ OBJC_IVAR_$_BWStillImageDuplicateInfo._settingsID
+ OBJC_IVAR_$_BWStillImageNodeConfiguration._secureSigningPhotoCaptureSupportEnabled
+ OBJC_IVAR_$_BWStillImageProcessingSettings._snapshottedLCBDatabaseByPortType
+ OBJC_IVAR_$_BWStillImageSampleBufferSinkNodeAnalyticsConfiguration._isTextureStyleRenderingSupported
+ OBJC_IVAR_$_BWStreamingFilterNode._computeFocusDisparity
+ OBJC_IVAR_$_BWStreamingFilterNode._latestCinematicDisparityBuffer
+ OBJC_IVAR_$_BWStreamingFilterNode._latestCinematicDisparityLock
+ OBJC_IVAR_$_BWStreamingSessionAnalyticsPayload._numberOfMagneticInterferenceEventsDetected
+ OBJC_IVAR_$_BWStreamingSessionAnalyticsPayload._stylusDataReceivedDuringSession
+ OBJC_IVAR_$_BWTextureStyleInfoMetadataNode._boxedMetadataFormatDescription
+ OBJC_IVAR_$_BWTextureStyleInfoMetadataNode._boxedMetadataOutput
+ OBJC_IVAR_$_BWTextureStyleInfoMetadataNode._emptyMetadataSampleData
+ OBJC_IVAR_$_BWTextureStyleInfoMetadataNode._localIDForTextureStyleInfoPlistMetadata_BE
+ OBJC_IVAR_$_BWTextureStyleInfoMetadataNode._passthruOutput
+ OBJC_IVAR_$_BWTextureStyleInfoMetadataNode._previousGeneratedMetadataBufferWasEmpty
+ OBJC_IVAR_$_BWTimewarpMetadataNode._boxedMetadataFormatDescription
+ OBJC_IVAR_$_BWTimewarpMetadataNode._boxedMetadataOutput
+ OBJC_IVAR_$_BWTimewarpMetadataNode._firstPreTimewarpPTSAsMillisecondsSince1970
+ OBJC_IVAR_$_BWTimewarpMetadataNode._firstPreTimewarpPTSInHostTime
+ OBJC_IVAR_$_BWTimewarpMetadataNode._localIDForPreTimewarpFrameMillisecondsSince1970Metadata_BE
+ OBJC_IVAR_$_BWTimewarpMetadataNode._localIDForTimewarpDecimationLevelMetadata_BE
+ OBJC_IVAR_$_BWTimewarpMetadataNode._localIDForTimewarpDecimationTagMetadata_BE
+ OBJC_IVAR_$_BWTimewarpMetadataNode._localIDForTimewarpSequenceCaptureIDMetadata_BE
+ OBJC_IVAR_$_BWTimewarpMetadataNode._maxDecimationLevel
+ OBJC_IVAR_$_BWTimewarpMetadataNode._maxSequenceNumber
+ OBJC_IVAR_$_BWTimewarpMetadataNode._passthruOutput
+ OBJC_IVAR_$_BWTimewarpMetadataNode._sourceClock
+ OBJC_IVAR_$_BWUBCaptureParameters._adaptiveFusionDowngradeSNRHysteresisLag
+ OBJC_IVAR_$_BWUBCaptureParameters._adaptiveFusionDowngradeSNRThreshold
+ OBJC_IVAR_$_BWUBCaptureParameters._learnedFusionHighResolutionDowngradeNormalizedSNRHysteresisLag
+ OBJC_IVAR_$_BWUBCaptureParameters._learnedFusionHighResolutionDowngradeNormalizedSNRThreshold
+ OBJC_IVAR_$_BWVISNode._textureStyle
+ OBJC_IVAR_$_BWVISNode._textureStyleRenderingEnabled
+ OBJC_IVAR_$_BWVISProcessorControllerConfiguration._textureStyleRenderingEnabled
+ OBJC_IVAR_$_BWVariableFrameRateParameters._lowLightVideoNoiseReductionLuxThresholds
+ OBJC_IVAR_$_BWVariableFrameRateSelector._lastPortType
+ OBJC_IVAR_$_BWVariableFrameRateSelector._lastQuadraBinningFactor
+ OBJC_IVAR_$_BWVariableFrameRateSelector._lowLightVideoNoiseReductionEnabled
+ OBJC_IVAR_$_BWVariableFrameRateSelector._lowLightVideoNoiseReductionLuxScene
+ OBJC_IVAR_$_BWVariableFrameRateSelector._lowLightVideoNoiseReductionLuxThresholdsByPortType
+ OBJC_IVAR_$_BWVideoCompressorNode._movieRecordingEndOfDataBehavior
+ OBJC_IVAR_$_BWVideoCompressorNode._timewarpMode
+ OBJC_IVAR_$_BWVideoDepthNode._cachedDisparityPixelBuffer
+ OBJC_IVAR_$_BWVideoDepthNode._depthPaddingPipelineState
+ OBJC_IVAR_$_BWVideoDepthNode._highFrameRateModeEnabled
+ OBJC_IVAR_$_BWVideoDepthNode._lastInferencePTS
+ OBJC_IVAR_$_BWVideoDepthNode._paddedDisparityPool
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._cameraInfoByPortType
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._clearHistoryThresholdFrameCount
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._crossfadeInEnabled
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._crossfadeRamp
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._lastApertureDiameter
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._lastCaptureID
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._lastHumanFullBodiesMask
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._lastLSCGainGridData
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._lastPortType
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._lastQuadraBinningFactor
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._maxLossyCompressionLevel
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._maximumAllowedFrameRate
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._maximumAllowedFrameRateReachedCount
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._maximumAllowedOverscan
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._maximumAllowedSystemPressureLevel
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._maximumAllowedSystemPressureLevelReached
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._outputFormatDescription
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._requiredAttachedMediaKeys
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._sceneMonitor
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._videoNoiseReductionDimensions
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._videoNoiseReductionEnabled
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._videoNoiseReductionGainThresholdsByPortType
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._visInputValidDimensions
+ OBJC_IVAR_$_BWVideoNoiseReductionNode._visOutputDimensions
+ OBJC_IVAR_$_FigCaptureAngleMonitor._active
+ OBJC_IVAR_$_FigCaptureAngleMonitor._angleHandler
+ OBJC_IVAR_$_FigCaptureAngleMonitor._angleNotificationLock
+ OBJC_IVAR_$_FigCaptureAngleMonitor._normalizedAngle
+ OBJC_IVAR_$_FigCaptureAngleMonitor._queue
+ OBJC_IVAR_$_FigCaptureAngleMonitor._started
+ OBJC_IVAR_$_FigCaptureCameraParameters._commonPersonalPhotographerParameters
+ OBJC_IVAR_$_FigCaptureCameraParameters._lowLightVideoNoiseReductionParameters
+ OBJC_IVAR_$_FigCaptureCameraSourcePipeline._attachedInfraredSourcePipeline
+ OBJC_IVAR_$_FigCaptureCameraSourcePipeline._cinematographyObjectTrackingNodeForMetadata
+ OBJC_IVAR_$_FigCaptureCameraSourcePipeline._colorAssistSourceNode
+ OBJC_IVAR_$_FigCaptureCameraSourcePipeline._lowLightVideoNoiseReductionEnabled
+ OBJC_IVAR_$_FigCaptureCameraSourcePipeline._omahaPrimaryStreamSourceDeviceType
+ OBJC_IVAR_$_FigCaptureCameraSourcePipeline._renoSuperWideSourceNode
+ OBJC_IVAR_$_FigCaptureCameraSourcePipeline._semanticMasksMetadataOutputBySourceDeviceType
+ OBJC_IVAR_$_FigCaptureCameraSourcePipeline._semanticMasksSceneClassifierOutputBySourceDeviceType
+ OBJC_IVAR_$_FigCaptureCameraSourcePipeline._textureStyle
+ OBJC_IVAR_$_FigCaptureCameraSourcePipelineConfiguration._cinematicVideoCaptureEnabled
+ OBJC_IVAR_$_FigCaptureCameraSourcePipelineConfiguration._cinematicVideoMetadataDeliveryEnabled
+ OBJC_IVAR_$_FigCaptureCameraSourcePipelineConfiguration._clientIsAttachedInfraredMetadataSession
+ OBJC_IVAR_$_FigCaptureCameraSourcePipelineConfiguration._lowLightVideoNoiseReductionEnabled
+ OBJC_IVAR_$_FigCaptureCameraSourcePipelineConfiguration._textureStyle
+ OBJC_IVAR_$_FigCaptureCameraSourcePipelineConfiguration._textureStyleEnabled
+ OBJC_IVAR_$_FigCaptureCameraSourcePipelineConfiguration._textureStyleRenderingVersion
+ OBJC_IVAR_$_FigCaptureCameraSourcePipelineConfiguration._timewarpMode
+ OBJC_IVAR_$_FigCaptureCinematographyPipeline._textureStyle
+ OBJC_IVAR_$_FigCaptureCinematographyPipelineConfiguration._depthInferenceEnabled
+ OBJC_IVAR_$_FigCaptureCinematographyPipelineConfiguration._textureStyle
+ OBJC_IVAR_$_FigCaptureCinematographyPipelineConfiguration._textureStyleEnabled
+ OBJC_IVAR_$_FigCaptureCinematographyPipelineConfiguration._textureStyleRenderingVersion
+ OBJC_IVAR_$_FigCaptureCustomExposureConfiguration._enableFNumberForAperturePriority
+ OBJC_IVAR_$_FigCaptureCustomExposureConfiguration._hasLockedAperture
+ OBJC_IVAR_$_FigCaptureCustomExposureConfiguration._lensAperture
+ OBJC_IVAR_$_FigCaptureDisplayLayout._displayRegion
+ OBJC_IVAR_$_FigCaptureDisplayLayoutMonitor._isV68Device
+ OBJC_IVAR_$_FigCaptureExposureLimits._defaultLensAperture
+ OBJC_IVAR_$_FigCaptureExposureLimits._maxLensAperture
+ OBJC_IVAR_$_FigCaptureExposureLimits._minLensAperture
+ OBJC_IVAR_$_FigCaptureIrisSinkConfiguration._personalPhotographerEnabled
+ OBJC_IVAR_$_FigCaptureIrisSinkConfiguration._secureSigningPhotoCaptureSupportEnabled
+ OBJC_IVAR_$_FigCaptureMagneticInterferenceMonitor._exitZoneDuration
+ OBJC_IVAR_$_FigCaptureMagneticInterferenceMonitor._exitZoneTimer
+ OBJC_IVAR_$_FigCaptureMagneticInterferenceMonitor._hidSystemClient
+ OBJC_IVAR_$_FigCaptureMagneticInterferenceMonitor._isMonitoring
+ OBJC_IVAR_$_FigCaptureMagneticInterferenceMonitor._lock
+ OBJC_IVAR_$_FigCaptureMagneticInterferenceMonitor._magneticInterferenceDetected
+ OBJC_IVAR_$_FigCaptureMagneticInterferenceMonitor._magneticInterferenceHandler
+ OBJC_IVAR_$_FigCaptureMagneticInterferenceMonitor._magneticInterferenceZone
+ OBJC_IVAR_$_FigCaptureMagneticInterferenceMonitor._monitorQueue
+ OBJC_IVAR_$_FigCaptureMagneticInterferenceMonitor._stateMachine
+ OBJC_IVAR_$_FigCaptureMagneticInterferenceMonitor._stylusDataReceivedDuringSession
+ OBJC_IVAR_$_FigCaptureMetadataObjectSinkConfiguration._cinematicVideoMetadataCaptureEnabled
+ OBJC_IVAR_$_FigCaptureMetadataSinkPipeline._semanticMasksConverterNode
+ OBJC_IVAR_$_FigCaptureMetadataSinkPipelineConfiguration._cinematicVideoMetadataTrackingOutput
+ OBJC_IVAR_$_FigCaptureMetadataSinkPipelineConfiguration._continuousAutoFocusTrackingMetadataSupported
+ OBJC_IVAR_$_FigCaptureMovieFileRecordingSettings._timewarpMode
+ OBJC_IVAR_$_FigCaptureMovieFileSinkConfiguration._cinematicVideoMetadataCaptureEnabled
+ OBJC_IVAR_$_FigCaptureMovieFileSinkConfiguration._cinematicVideoMetadataCaptureEnabledByClient
+ OBJC_IVAR_$_FigCaptureMovieFileSinkHeadPipeline._personalPhotographerDelegate
+ OBJC_IVAR_$_FigCaptureMovieFileSinkHeadPipelineConfiguration._personalPhotographerEnabled
+ OBJC_IVAR_$_FigCaptureMovieFileSinkPipeline._cinematographyObjectTrackingNode
+ OBJC_IVAR_$_FigCaptureMovieFileSinkPipeline._movieRecordingEndOfDataBehavior
+ OBJC_IVAR_$_FigCaptureMovieFileSinkPipelineConfiguration._cinematicVideoMetadataEnabled
+ OBJC_IVAR_$_FigCaptureMovieFileSinkPipelineConfiguration._lowLightVideoNoiseReductionEnabled
+ OBJC_IVAR_$_FigCaptureMovieFileSinkPipelineConfiguration._personalPhotographerEnabled
+ OBJC_IVAR_$_FigCaptureMovieFileSinkPipelineConfiguration._personalPhotographerTypicalCaptureLatencyInSeconds
+ OBJC_IVAR_$_FigCaptureMovieFileSinkPipelineConfiguration._textureStyleEnabled
+ OBJC_IVAR_$_FigCaptureMovieFileSinkTailPipeline._cinematographyObjectTrackingNode
+ OBJC_IVAR_$_FigCaptureMovieFileSinkTailPipelineConfiguration._cinematicVideoMetadataEnabled
+ OBJC_IVAR_$_FigCapturePreviewSinkPipeline._omahaAdditionalPreviewRotationDegrees
+ OBJC_IVAR_$_FigCapturePreviewSinkPipeline._personalPhotographerDelegate
+ OBJC_IVAR_$_FigCapturePreviewSinkPipelineConfiguration._cinematicVideoSDOFRenderingEnabled
+ OBJC_IVAR_$_FigCapturePreviewSinkPipelineConfiguration._depthInferenceForCinematicVideoEnabled
+ OBJC_IVAR_$_FigCapturePreviewSinkPipelineConfiguration._personalPhotographerEnabled
+ OBJC_IVAR_$_FigCaptureSessionConfiguration._textureStyle
+ OBJC_IVAR_$_FigCaptureSessionConfiguration._textureStyleEnabled
+ OBJC_IVAR_$_FigCaptureSessionParsedCameraSourceConfiguration._cinematicVideoMetadataDeliveryEnabled
+ OBJC_IVAR_$_FigCaptureSessionParsedConfiguration._textureStyle
+ OBJC_IVAR_$_FigCaptureSessionParsedConfiguration._textureStyleEnabled
+ OBJC_IVAR_$_FigCaptureSourceAttributes._lowCurrentTorchSupported
+ OBJC_IVAR_$_FigCaptureSourceAttributes._maxLensAperture
+ OBJC_IVAR_$_FigCaptureSourceAttributes._minLensAperture
+ OBJC_IVAR_$_FigCaptureSourceAttributes._primaryConstituentDeviceSwitchingBehaviorLockedWithDeviceSupported
+ OBJC_IVAR_$_FigCaptureSourceAttributes._recommendedLensApertures
+ OBJC_IVAR_$_FigCaptureSourceAttributes._supportedExposureSignals
+ OBJC_IVAR_$_FigCaptureSourceCommonSettings._cinematicVideoWithoutEmbeddedDepthSupported
+ OBJC_IVAR_$_FigCaptureSourceCommonSettings._colorAssistedInfraredMetadataCameraSupported
+ OBJC_IVAR_$_FigCaptureSourceCommonSettings._magneticInterferenceMitigationRequired
+ OBJC_IVAR_$_FigCaptureSourceCommonSettings._textureStyleRenderingVersion
+ OBJC_IVAR_$_FigCaptureSourceConfiguration._activeOmahaConstituentDeviceType
+ OBJC_IVAR_$_FigCaptureSourceConfiguration._cinematicVideoMetadataCaptureEnabled
+ OBJC_IVAR_$_FigCaptureSourceConfiguration._faceIDCoexistenceEnabled
+ OBJC_IVAR_$_FigCaptureSourceConfiguration._timewarpEnabled
+ OBJC_IVAR_$_FigCaptureSourceExtendedAttributes._adaptiveFusionSupported
+ OBJC_IVAR_$_FigCaptureSourceExtendedAttributes._magneticInterferenceZone
+ OBJC_IVAR_$_FigCaptureSourceExtendedAttributes._tnrMachineLearningImageRegistrationSupported
+ OBJC_IVAR_$_FigCaptureSourceManager._angleMonitor
+ OBJC_IVAR_$_FigCaptureSourceManager._angleMonitorClientBundleIDs
+ OBJC_IVAR_$_FigCaptureSourceManager._deviceAngleState
+ OBJC_IVAR_$_FigCaptureSourceManager._displayAngleStateLock
+ OBJC_IVAR_$_FigCaptureSourceManager._faceIDUnwrapQueue
+ OBJC_IVAR_$_FigCaptureSourceManager._magneticInterferenceMonitor
+ OBJC_IVAR_$_FigCaptureSourceManager._omahaRenoAngleWithinDropZone
+ OBJC_IVAR_$_FigCaptureSourceManager._primaryDisplayRegion
+ OBJC_IVAR_$_FigCaptureSourceManager._renoOccluded
+ OBJC_IVAR_$_FigCaptureSourceVideoFormat._faceIDCompanionFormat
+ OBJC_IVAR_$_FigCaptureStillImageSettings._activeOmahaConstituentDeviceType
+ OBJC_IVAR_$_FigCaptureStillImageSettings._autoSecureSigningPhotoCaptureEnabled
+ OBJC_IVAR_$_FigCaptureStillImageSettings._personalPhotographerCapture
+ OBJC_IVAR_$_FigCaptureStillImageSettings._personalPhotographerCaptureRate
+ OBJC_IVAR_$_FigCaptureStillImageSettings._textureStyle
+ OBJC_IVAR_$_FigCaptureTextureStyle._grain
+ OBJC_IVAR_$_FigCaptureTextureStyle._hash
+ OBJC_IVAR_$_FigCaptureTextureStyle._intensity
+ OBJC_IVAR_$_FigCaptureTextureStyle._preset
+ OBJC_IVAR_$_FigCaptureVideoDataSinkConfiguration._cinematicVideoMetadataCaptureEnabled
+ OBJC_IVAR_$_FigCaptureVideoDataSinkPipeline._cinematicVideoMetadataCaptureEnabled
+ OBJC_IVAR_$_FigCaptureVideoDataSinkPipelineConfiguration._cinematicVideoMetadataCaptureEnabled
+ OBJC_IVAR_$_FigCaptureVideoDataSinkPipelineConfiguration._depthInferenceForCinematicVideoEnabled
+ OBJC_IVAR_$_FigCaptureVideoPreviewSinkConfiguration._overCaptureGradientPercentInset
+ OBJC_IVAR_$_FigCaptureVideoPreviewSinkConfiguration._primaryDisplayRegion
+ OBJC_IVAR_$_FigFlashlightLocal._lowCurrentTorchEnabled
+ OBJC_IVAR_$_FigMetadataObjectCaptureConnectionConfiguration._faceIDConfiguration
+ OBJC_IVAR_$_FigMetadataObjectCaptureConnectionConfiguration._rawFrameDeliveryEnabled
+ OBJC_IVAR_$_FigVideoCaptureConnectionConfiguration._lowLightVideoNoiseReductionEnabled
+ OBJC_IVAR_$_FigVideoCaptureConnectionConfiguration._timewarpDestinationFrameRate
+ OBJC_IVAR_$_FigVideoCaptureConnectionConfiguration._timewarpMode
+ OBJC_IVAR_$_SubjectSelection._lastNondisruptiveSwitchingFormatZoomFactor
+ OBJC_IVAR_$_SubjectSelection._motionFilteringWeightDecayRatio
+ OBJC_IVAR_$_SubjectSelection._vipDetectionDurationTimeInSeconds
+ OBJC_IVAR_$_SubjectSelection._vipDetectionThreshold
+ OBJC_IVAR_$_SubjectSelection._vipDropOffDurationTimeInSeconds
+ OBJC_IVAR_$_SubjectSelection._vipDropOffThreshold
+ OBJC_IVAR_$_TrackedSubject._distance
+ OBJC_IVAR_$_TrackedSubject._firstVIPDropOffTimeStamp
+ OBJC_IVAR_$_TrackedSubject._firstVIPSignificantTimeStamp
+ OBJC_IVAR_$_TrackedSubject._isSignificantForApertureControl
+ OBJC_IVAR_$_TrackedSubject._isVIPSignificant
+ OBJC_IVAR_$_TrackedSubject._motionFilteringWeightDecayRatio
+ OBJC_IVAR_$_TrackedSubject._motionInPreviewPixels
+ OBJC_IVAR_$_TrackedSubject._vipConfidence
+ OBJC_IVAR_$_TrackedSubject._vipDetectionDurationTimeInSeconds
+ OBJC_IVAR_$_TrackedSubject._vipDetectionThreshold
+ OBJC_IVAR_$_TrackedSubject._vipDropOffDurationTimeInSeconds
+ OBJC_IVAR_$_TrackedSubject._vipDropOffThreshold
+ _AVGQ5SQS4OCN7HMWDEDJYD553WNPTI
+ _AVGQG37DCWSL47LUT3OXNYCVIFJC5M
+ _BWAttachedMediaKey_FSINCInstanceMaskPrefix
+ _BWAttachedMediaKey_FSINCSegmentationMaskEars
+ _BWAttachedMediaKey_FSINCSegmentationMaskEyebrow
+ _BWAttachedMediaKey_FSINCSegmentationMaskFace
+ _BWAttachedMediaKey_FSINCSegmentationMaskGlasses
+ _BWAttachedMediaKey_FSINCSegmentationMaskHand
+ _BWAttachedMediaKey_FSINCSegmentationMaskLips
+ _BWAttachedMediaKey_FSINCSegmentationMaskNose
+ _BWAttachedMediaKey_FSINCSegmentationMaskOtherSkin
+ _BWAttachedMediaKey_FSINCSegmentationMaskPerson
+ _BWAttachedMediaKey_FSINCSegmentationMaskPrefix
+ _BWAttachedMediaKey_FSINCSegmentationMaskSkin
+ _BWAttachedMediaKey_FSINCSegmentationMaskTattoo
+ _BWAttachedMediaKey_FSINCSegmentationMaskTeeth
+ _BWAttachedMediaKey_ProvenanceSensorRaw
+ _BWCalculateSoftmaxOfArray
+ _BWComputeCosineSimilarityFP16
+ _BWComputeEdgeMarginFactorForPointInRect
+ _BWConvertFloat16ToFloat32
+ _BWCreateProvenanceDNGDictionary
+ _BWCreateProvenanceDNGInfo
+ _BWCreateSampleBufferWithFaceIDDictionary
+ _BWDeviceModelIsV68
+ _BWDeviceModelIsV6x
+ _BWDroppedSampleReasonOmahaConstituentDeviceLiveReconfiguration
+ _BWDroppedSampleReasonOmahaRenoAngleWithinDropZone
+ _BWExposureSignalsToShortString
+ _BWFSINCAttachedMediaKeysRequiredByTextureStylesReversibility
+ _BWFigVideoCaptureDeviceActiveExposureSignalsChangedNotification
+ _BWFigVideoCaptureDeviceContinuousAutoFocusTrackingSubjectAcquiredChangedNotification
+ _BWFigVideoCaptureDeviceIgnoredExposureSignalsChangedNotification
+ _BWFigVideoCaptureDeviceLensApertureChangedNotification
+ _BWFigVideoCaptureDevicePersonalPhotographerStatusChangedNotification
+ _BWFigVideoCaptureDevicePropertyLensAperture
+ _BWGetHueMapPixelBuffer
+ _BWHVSAnySubjectWithinVisibleFOV
+ _BWHVSDetectionStatusKey_SessionActive
+ _BWHVSDetectionStatusKey_SubjectDetected
+ _BWHVSMakernoteEntryForPersonalPhotographerMetadata
+ _BWHVSPersonalPhotographerMetadata
+ _BWHVSStabilizeSubjectDetected
+ _BWIsRenoPortType
+ _BWIsSIFRSampleBuffer
+ _BWNodeSubTypeFrameScoring
+ _BWNodeSubTypeSemanticMasksConverter
+ _BWNodeSubTypeTextureStyleInfoMetadata
+ _BWNodeSubTypeTimewarpMetadata
+ _BWNodeSubTypeVideoNoiseReducer
+ _BWPhotoEncoderAttachedMediaKeyIsFSINCSegmentationMask
+ _BWPhotoEncoderTextureStylesAttachedMediaKeysForPiecemealEncoding
+ _BWSecureSigningModeFromSupportedSensorSigningConfiguration
+ _BWTextureStyleSkinSmoothActivePresetFromSampleBuffer
+ _BWTextureStyleSkinSmoothAdjustedCropRectsForZoomChange
+ _BWTextureStyleSkinSmoothCleanupIfStale
+ _BWTextureStyleSkinSmoothFaceRectsFromMetadata
+ _BWTextureStyleSkinSmoothMaskStateInit
+ _BWTextureStyleSkinSmoothMaskStateReset
+ _BWTextureStyleSkinSmoothParametersCreate
+ _BWTextureStyleSkinSmoothResolveMask
+ _BWTextureStyleSkinSmoothSaveMask
+ _CGRectContainsPoint
+ _CMCaptureGestaltGetBoolAnswer
+ _CMISmartStyleMetadataKey_OriginalInsteadOfReversibility
+ _CMPhotoCreateV2H2BinningBuffer
+ _CMPhotoExtractProvenanceMetadataFromBuffer
+ _CONTAINER_PERSONA_PRIMARY
+ _FigCFDictionaryGetArrayValue
+ _FigCaptureClientApplicationIdentifierPencilPairingApp
+ _FigCaptureClientIsPencilPairingApp
+ _FigCaptureCopyInternalDaemonDataContainerURL
+ _FigCaptureMetadataObjectConfigurationRequiresContinuousAutoFocusTrackingMetadata
+ _FigCaptureMetadataObjectConfigurationRequiresFaceID
+ _FigCaptureMetadataObjectConfigurationsRequireContinuousAutoFocusTrackingMetadata
+ _FigCaptureMetadataUtilitiesCreateMovieLevelMetadataForTimewarpCaptureMode
+ _FigCaptureMetadataUtilitiesCreateMovieLevelMetadataForTimewarpTimelapseFastDecimationAllowed
+ _FigCaptureMetadataUtilitiesCreateMovieLevelMetadataForTimewarpTimelapseMaxDecimationLevel
+ _FigCaptureMetadataUtilitiesCreateMovieLevelMetadataWithTextureStyleMetadata
+ _FigCaptureMetadataUtilitiesSetIrisAssetIdentifierForSettings
+ _FigCaptureScreenDimensionsForDisplayRegion
+ _FigCaptureShorterDimensionForDimensions
+ _FigCaptureSmartStyleSettingsGetSystemTextureStyle
+ _FigCaptureSourceFormatKey_AdaptiveFusionSupported
+ _FigCaptureSourceFormatKey_AutoFullFullUltraHighResolutionZeroShutterLagSupported
+ _FigCaptureSourceFormatKey_CinematicMetadataCaptureSupported
+ _FigCaptureSourceFormatKey_ConfigureForUltraHighResolutionZeroShutterLagSupport
+ _FigCaptureSourceFormatKey_ContinuousAutoFocusTrackingSupported
+ _FigCaptureSourceFormatKey_FaceIDCoexistenceSupported
+ _FigCaptureSourceFormatKey_FaceIDCompanionFormat
+ _FigCaptureSourceFormatKey_LearnedFusionEnhancedResolutionSupported
+ _FigCaptureSourceFormatKey_LearnedFusionUltraHighResolutionSupported
+ _FigCaptureSourceFormatKey_LowLightVideoNoiseReductionSupported
+ _FigCaptureSourceFormatKey_PersonalPhotographerSupported
+ _FigCaptureSourceFormatKey_PreviewPrimaryTargetIsRenoDisplay
+ _FigCaptureSourceFormatKey_SecureSigningFaceIDSupported
+ _FigCaptureSourceFormatKey_SecureSigningPhotoCaptureSupported
+ _FigCaptureSourceFormatKey_TextureStyleBaseLookSupported
+ _FigCaptureSourceFormatKey_TextureStyleSupported
+ _FigCaptureSourceSetDeviceAngle
+ _FigCaptureSourceSetMagneticInterferenceDetected
+ _FigCaptureSourceSetMagneticInterferenceMonitor
+ _FigCaptureSourceSetOccluded
+ _FigCaptureSourceSetPrimaryDisplayRegion
+ _FigCaptureTextureStylePresetTypeFilmic
+ _FigCaptureTextureStylePresetTypeGlowy
+ _FigCaptureTextureStylePresetTypeSoft
+ _FigCaptureTextureStylePresetTypeStandard
+ _FigCaptureTextureStylePresetTypeStudio
+ _FigCaptureTimewarpClassicTimelapseIntermediateFileBaseLayerFrameRate
+ _FigCaptureTimewarpClassicTimelapseIntermediateFileBitRateMultiplier
+ _FigCaptureTimewarpClassicTimelapseIntermediateFileFrameRate
+ _FigCaptureTimewarpClassicTimelapseIntermediateFileMaxKeyFrameInterval
+ _FigCaptureTimewarpTimelapseClassicIntermediateFilePathPostfix
+ _FigCaptureTransposedAspectRatio
+ _IOHIDEventGetChildren
+ _IOHIDEventGetFloatValue
+ _NSURLIsExcludedFromBackupKey
+ _OBJC_CLASS_$_BWBaselineTextureStyleRenderer
+ _OBJC_CLASS_$_BWCinematographyObjectTrackingNode
+ _OBJC_CLASS_$_BWGlobalTextureStyleRenderer
+ _OBJC_CLASS_$_BWGlowTextureStyleRenderer
+ _OBJC_CLASS_$_BWHVSCandidateFrameManager
+ _OBJC_CLASS_$_BWHVSEmbeddingAnalysisResult
+ _OBJC_CLASS_$_BWHVSFace
+ _OBJC_CLASS_$_BWHVSFrame
+ _OBJC_CLASS_$_BWHVSFrameAnalysisTask
+ _OBJC_CLASS_$_BWHVSObject
+ _OBJC_CLASS_$_BWHVSPerson
+ _OBJC_CLASS_$_BWHVSPet
+ _OBJC_CLASS_$_BWHVSScoringNode
+ _OBJC_CLASS_$_BWLCBDatabaseManager
+ _OBJC_CLASS_$_BWPersonalPhotographerSceneMonitorV1
+ _OBJC_CLASS_$_BWSecureFaceIDFrameTracker
+ _OBJC_CLASS_$_BWSecureSigningUtilityManager
+ _OBJC_CLASS_$_BWSemanticMasksConverterNode
+ _OBJC_CLASS_$_BWSensorRawTimeMachine
+ _OBJC_CLASS_$_BWSensorRawTimeMachineConfiguration
+ _OBJC_CLASS_$_BWSensorRawTimeMachineFrameConfiguration
+ _OBJC_CLASS_$_BWSkinTextureStyleRenderer
+ _OBJC_CLASS_$_BWStillImageDuplicateInfo
+ _OBJC_CLASS_$_BWTextureStyleInfoMetadataNode
+ _OBJC_CLASS_$_BWTextureStyleTuning
+ _OBJC_CLASS_$_BWTimewarpMetadataNode
+ _OBJC_CLASS_$_BWVideoNoiseReductionNode
+ _OBJC_CLASS_$_CMIImageTile
+ _OBJC_CLASS_$_CMILCBDatabase
+ _OBJC_CLASS_$_CMITextureStyleTuningLookup
+ _OBJC_CLASS_$_CMITextureStylesBloomParameters
+ _OBJC_CLASS_$_CMITextureStylesDiffusionParameters
+ _OBJC_CLASS_$_CMITextureStylesEffectDescriptor
+ _OBJC_CLASS_$_CMITextureStylesFilmGrainParameters
+ _OBJC_CLASS_$_CMITextureStylesGlowParameters
+ _OBJC_CLASS_$_CMITextureStylesHalationParameters
+ _OBJC_CLASS_$_CMITextureStylesMattifyParameters
+ _OBJC_CLASS_$_CMITextureStylesPersonInputData
+ _OBJC_CLASS_$_CMITextureStylesPersonInputDataUtilities
+ _OBJC_CLASS_$_CMITextureStylesProcessor
+ _OBJC_CLASS_$_CMITextureStylesSkinSmoothParameters
+ _OBJC_CLASS_$_CMITextureStylesUnderEyeBrightenParameters
+ _OBJC_CLASS_$_FigCaptureAngleMonitor
+ _OBJC_CLASS_$_FigCaptureMagneticInterferenceMonitor
+ _OBJC_CLASS_$_FigCaptureTextureStyle
+ _OBJC_METACLASS_$_BWBaselineTextureStyleRenderer
+ _OBJC_METACLASS_$_BWCinematographyObjectTrackingNode
+ _OBJC_METACLASS_$_BWGlobalTextureStyleRenderer
+ _OBJC_METACLASS_$_BWGlowTextureStyleRenderer
+ _OBJC_METACLASS_$_BWHVSCandidateFrameManager
+ _OBJC_METACLASS_$_BWHVSEmbeddingAnalysisResult
+ _OBJC_METACLASS_$_BWHVSFace
+ _OBJC_METACLASS_$_BWHVSFrame
+ _OBJC_METACLASS_$_BWHVSFrameAnalysisTask
+ _OBJC_METACLASS_$_BWHVSObject
+ _OBJC_METACLASS_$_BWHVSPerson
+ _OBJC_METACLASS_$_BWHVSPet
+ _OBJC_METACLASS_$_BWHVSScoringNode
+ _OBJC_METACLASS_$_BWLCBDatabaseManager
+ _OBJC_METACLASS_$_BWPersonalPhotographerSceneMonitorV1
+ _OBJC_METACLASS_$_BWSecureFaceIDFrameTracker
+ _OBJC_METACLASS_$_BWSecureSigningUtilityManager
+ _OBJC_METACLASS_$_BWSemanticMasksConverterNode
+ _OBJC_METACLASS_$_BWSensorRawTimeMachine
+ _OBJC_METACLASS_$_BWSensorRawTimeMachineConfiguration
+ _OBJC_METACLASS_$_BWSensorRawTimeMachineFrameConfiguration
+ _OBJC_METACLASS_$_BWSkinTextureStyleRenderer
+ _OBJC_METACLASS_$_BWStillImageDuplicateInfo
+ _OBJC_METACLASS_$_BWTextureStyleInfoMetadataNode
+ _OBJC_METACLASS_$_BWTextureStyleTuning
+ _OBJC_METACLASS_$_BWTimewarpMetadataNode
+ _OBJC_METACLASS_$_BWVideoNoiseReductionNode
+ _OBJC_METACLASS_$_FigCaptureAngleMonitor
+ _OBJC_METACLASS_$_FigCaptureMagneticInterferenceMonitor
+ _OBJC_METACLASS_$_FigCaptureTextureStyle
+ _OUTLINED_FUNCTION_445
+ _OUTLINED_FUNCTION_446
+ _OUTLINED_FUNCTION_447
+ _OUTLINED_FUNCTION_448
+ _OUTLINED_FUNCTION_449
+ _OUTLINED_FUNCTION_450
+ _OUTLINED_FUNCTION_451
+ _OUTLINED_FUNCTION_452
+ _OUTLINED_FUNCTION_453
+ _OUTLINED_FUNCTION_454
+ _OUTLINED_FUNCTION_455
+ _OUTLINED_FUNCTION_456
+ _OUTLINED_FUNCTION_457
+ _OUTLINED_FUNCTION_458
+ _OUTLINED_FUNCTION_459
+ _OUTLINED_FUNCTION_460
+ _OUTLINED_FUNCTION_461
+ _OUTLINED_FUNCTION_462
+ _OUTLINED_FUNCTION_463
+ _OUTLINED_FUNCTION_464
+ _OUTLINED_FUNCTION_465
+ _OUTLINED_FUNCTION_466
+ _OUTLINED_FUNCTION_467
+ _OUTLINED_FUNCTION_468
+ _OUTLINED_FUNCTION_469
+ _OUTLINED_FUNCTION_470
+ _OUTLINED_FUNCTION_471
+ _OUTLINED_FUNCTION_472
+ _OUTLINED_FUNCTION_473
+ _OUTLINED_FUNCTION_474
+ _OUTLINED_FUNCTION_475
+ _OUTLINED_FUNCTION_476
+ _OUTLINED_FUNCTION_477
+ _OUTLINED_FUNCTION_478
+ _OUTLINED_FUNCTION_479
+ _OUTLINED_FUNCTION_480
+ _OUTLINED_FUNCTION_481
+ _OUTLINED_FUNCTION_482
+ _OUTLINED_FUNCTION_483
+ _OUTLINED_FUNCTION_484
+ _OUTLINED_FUNCTION_485
+ __29+[BWTextureStyleTuning setup]_block_invoke
+ __39-[BWMultiStreamCameraSourceNode start:]_block_invoke
+ __53-[BWStillImageCoordinatorNode _beginResolvingCapture]_block_invoke_2
+ __63-[BWLCBDatabaseManager _executeDatabaseStorageWorkAsync:block:]_block_invoke
+ __65-[FigCaptureMagneticInterferenceMonitor startMonitoringWithZone:]_block_invoke
+ __OBJC_$_CLASS_METHODS_BWBaselineTextureStyleRenderer
+ __OBJC_$_CLASS_METHODS_BWCinematographyObjectTrackingNode
+ __OBJC_$_CLASS_METHODS_BWGlobalTextureStyleRenderer
+ __OBJC_$_CLASS_METHODS_BWGlowTextureStyleRenderer
+ __OBJC_$_CLASS_METHODS_BWHVSCandidateFrameManager
+ __OBJC_$_CLASS_METHODS_BWHVSFrame
+ __OBJC_$_CLASS_METHODS_BWHVSObject
+ __OBJC_$_CLASS_METHODS_BWHVSScoringNode
+ __OBJC_$_CLASS_METHODS_BWLCBDatabaseManager
+ __OBJC_$_CLASS_METHODS_BWPersonalPhotographerSceneMonitorV1
+ __OBJC_$_CLASS_METHODS_BWSecureSigningUtilityManager
+ __OBJC_$_CLASS_METHODS_BWSemanticMasksConverterNode
+ __OBJC_$_CLASS_METHODS_BWSensorRawTimeMachine
+ __OBJC_$_CLASS_METHODS_BWSkinTextureStyleRenderer
+ __OBJC_$_CLASS_METHODS_BWStillImageDuplicateInfo
+ __OBJC_$_CLASS_METHODS_BWTextureStyleInfoMetadataNode
+ __OBJC_$_CLASS_METHODS_BWTextureStyleTuning
+ __OBJC_$_CLASS_METHODS_BWTimewarpMetadataNode
+ __OBJC_$_CLASS_METHODS_BWVideoNoiseReductionNode
+ __OBJC_$_CLASS_METHODS_FigCaptureAngleMonitor
+ __OBJC_$_CLASS_METHODS_FigCaptureMagneticInterferenceMonitor
+ __OBJC_$_CLASS_METHODS_FigCaptureTextureStyle
+ __OBJC_$_CLASS_PROP_LIST_BWStillImageDuplicateInfo
+ __OBJC_$_CLASS_PROP_LIST_FigCaptureTextureStyle
+ __OBJC_$_INSTANCE_METHODS_BWBaselineTextureStyleRenderer
+ __OBJC_$_INSTANCE_METHODS_BWCinematographyObjectTrackingNode
+ __OBJC_$_INSTANCE_METHODS_BWGlobalTextureStyleRenderer
+ __OBJC_$_INSTANCE_METHODS_BWGlowTextureStyleRenderer
+ __OBJC_$_INSTANCE_METHODS_BWHVSCandidateFrameManager
+ __OBJC_$_INSTANCE_METHODS_BWHVSEmbeddingAnalysisResult
+ __OBJC_$_INSTANCE_METHODS_BWHVSFace
+ __OBJC_$_INSTANCE_METHODS_BWHVSFrame
+ __OBJC_$_INSTANCE_METHODS_BWHVSFrameAnalysisTask
+ __OBJC_$_INSTANCE_METHODS_BWHVSObject
+ __OBJC_$_INSTANCE_METHODS_BWHVSPerson
+ __OBJC_$_INSTANCE_METHODS_BWHVSPet
+ __OBJC_$_INSTANCE_METHODS_BWHVSScoringNode
+ __OBJC_$_INSTANCE_METHODS_BWLCBDatabaseManager
+ __OBJC_$_INSTANCE_METHODS_BWPersonalPhotographerSceneMonitorV1
+ __OBJC_$_INSTANCE_METHODS_BWSecureFaceIDFrameTracker
+ __OBJC_$_INSTANCE_METHODS_BWSecureSigningUtilityManager
+ __OBJC_$_INSTANCE_METHODS_BWSemanticMasksConverterNode
+ __OBJC_$_INSTANCE_METHODS_BWSensorRawTimeMachine
+ __OBJC_$_INSTANCE_METHODS_BWSensorRawTimeMachineConfiguration
+ __OBJC_$_INSTANCE_METHODS_BWSensorRawTimeMachineFrameConfiguration
+ __OBJC_$_INSTANCE_METHODS_BWSkinTextureStyleRenderer
+ __OBJC_$_INSTANCE_METHODS_BWStillImageDuplicateInfo
+ __OBJC_$_INSTANCE_METHODS_BWTextureStyleInfoMetadataNode
+ __OBJC_$_INSTANCE_METHODS_BWTimewarpMetadataNode
+ __OBJC_$_INSTANCE_METHODS_BWVideoNoiseReductionNode
+ __OBJC_$_INSTANCE_METHODS_FigCaptureAngleMonitor
+ __OBJC_$_INSTANCE_METHODS_FigCaptureExposureLimits
+ __OBJC_$_INSTANCE_METHODS_FigCaptureMagneticInterferenceMonitor
+ __OBJC_$_INSTANCE_METHODS_FigCaptureTextureStyle
+ __OBJC_$_INSTANCE_VARIABLES_BWBaselineTextureStyleRenderer
+ __OBJC_$_INSTANCE_VARIABLES_BWCinematographyObjectTrackingNode
+ __OBJC_$_INSTANCE_VARIABLES_BWGlobalTextureStyleRenderer
+ __OBJC_$_INSTANCE_VARIABLES_BWGlowTextureStyleRenderer
+ __OBJC_$_INSTANCE_VARIABLES_BWHVSCandidateFrameManager
+ __OBJC_$_INSTANCE_VARIABLES_BWHVSEmbeddingAnalysisResult
+ __OBJC_$_INSTANCE_VARIABLES_BWHVSFace
+ __OBJC_$_INSTANCE_VARIABLES_BWHVSFrame
+ __OBJC_$_INSTANCE_VARIABLES_BWHVSFrameAnalysisTask
+ __OBJC_$_INSTANCE_VARIABLES_BWHVSObject
+ __OBJC_$_INSTANCE_VARIABLES_BWHVSPerson
+ __OBJC_$_INSTANCE_VARIABLES_BWHVSPet
+ __OBJC_$_INSTANCE_VARIABLES_BWHVSScoringNode
+ __OBJC_$_INSTANCE_VARIABLES_BWLCBDatabaseManager
+ __OBJC_$_INSTANCE_VARIABLES_BWPersonalPhotographerSceneMonitorV1
+ __OBJC_$_INSTANCE_VARIABLES_BWPhotoEncoderControllerRequest
+ __OBJC_$_INSTANCE_VARIABLES_BWSecureFaceIDFrameTracker
+ __OBJC_$_INSTANCE_VARIABLES_BWSecureSigningUtilityManager
+ __OBJC_$_INSTANCE_VARIABLES_BWSemanticMasksConverterNode
+ __OBJC_$_INSTANCE_VARIABLES_BWSensorRawTimeMachine
+ __OBJC_$_INSTANCE_VARIABLES_BWSensorRawTimeMachineConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_BWSensorRawTimeMachineFrameConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_BWSkinTextureStyleRenderer
+ __OBJC_$_INSTANCE_VARIABLES_BWStillImageDuplicateInfo
+ __OBJC_$_INSTANCE_VARIABLES_BWTextureStyleInfoMetadataNode
+ __OBJC_$_INSTANCE_VARIABLES_BWTimewarpMetadataNode
+ __OBJC_$_INSTANCE_VARIABLES_BWVideoNoiseReductionNode
+ __OBJC_$_INSTANCE_VARIABLES_FigCaptureAngleMonitor
+ __OBJC_$_INSTANCE_VARIABLES_FigCaptureMagneticInterferenceMonitor
+ __OBJC_$_INSTANCE_VARIABLES_FigCaptureMetadataObjectSinkConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_FigCaptureTextureStyle
+ __OBJC_$_PROP_LIST_BWBaselineTextureStyleRenderer
+ __OBJC_$_PROP_LIST_BWCinematicVideoDisparityProvider
+ __OBJC_$_PROP_LIST_BWCinematographyObjectTrackingNode
+ __OBJC_$_PROP_LIST_BWGlobalTextureStyleRenderer
+ __OBJC_$_PROP_LIST_BWGlowTextureStyleRenderer
+ __OBJC_$_PROP_LIST_BWHVSCandidateFrameManager
+ __OBJC_$_PROP_LIST_BWHVSEmbeddingAnalysisResult
+ __OBJC_$_PROP_LIST_BWHVSFace
+ __OBJC_$_PROP_LIST_BWHVSFrame
+ __OBJC_$_PROP_LIST_BWHVSFrameAnalysisTask
+ __OBJC_$_PROP_LIST_BWHVSObject
+ __OBJC_$_PROP_LIST_BWHVSPerson
+ __OBJC_$_PROP_LIST_BWHVSPet
+ __OBJC_$_PROP_LIST_BWHVSScoringNode
+ __OBJC_$_PROP_LIST_BWLCBDatabaseManager
+ __OBJC_$_PROP_LIST_BWPersonalPhotographerDelegate
+ __OBJC_$_PROP_LIST_BWPersonalPhotographerSceneMonitorV1
+ __OBJC_$_PROP_LIST_BWPhotoEncoderControllerRequest
+ __OBJC_$_PROP_LIST_BWSecureSigningUtilityManager
+ __OBJC_$_PROP_LIST_BWSemanticMasksConverterNode
+ __OBJC_$_PROP_LIST_BWSensorRawTimeMachineConfiguration
+ __OBJC_$_PROP_LIST_BWSensorRawTimeMachineFrameConfiguration
+ __OBJC_$_PROP_LIST_BWSkinTextureStyleRenderer
+ __OBJC_$_PROP_LIST_BWStillImageDuplicateInfo
+ __OBJC_$_PROP_LIST_BWTextureStyleInfoMetadataNode
+ __OBJC_$_PROP_LIST_BWTimewarpMetadataNode
+ __OBJC_$_PROP_LIST_FigCaptureAngleMonitor
+ __OBJC_$_PROP_LIST_FigCaptureMagneticInterferenceMonitor
+ __OBJC_$_PROP_LIST_FigCaptureMetadataObjectSinkConfiguration
+ __OBJC_$_PROP_LIST_FigCaptureTextureStyle
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BWCinematicVideoDisparityProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BWFigVideoCaptureDeviceContinuousAutoFocusTrackingChangedDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BWHVSCandidateFrameManagerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BWLCBDatabaseManagerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BWPersonalPhotographerCaptureRegistrationDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BWPersonalPhotographerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BWPersonalPhotographerSceneMonitor
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BWPreviewStabilizationNodeDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BWSecureSigningUtilityManagerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BWCinematicVideoDisparityProvider
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BWFigVideoCaptureDeviceContinuousAutoFocusTrackingChangedDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BWHVSCandidateFrameManagerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BWLCBDatabaseManagerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BWPersonalPhotographerCaptureRegistrationDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BWPersonalPhotographerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BWPersonalPhotographerSceneMonitor
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BWPreviewStabilizationNodeDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BWSecureSigningUtilityManagerDelegate
+ __OBJC_$_PROTOCOL_REFS_BWCinematicVideoDisparityProvider
+ __OBJC_$_PROTOCOL_REFS_BWFigVideoCaptureDeviceContinuousAutoFocusTrackingChangedDelegate
+ __OBJC_$_PROTOCOL_REFS_BWHVSCandidateFrameManagerDelegate
+ __OBJC_$_PROTOCOL_REFS_BWLCBDatabaseManagerDelegate
+ __OBJC_$_PROTOCOL_REFS_BWPersonalPhotographerCaptureRegistrationDelegate
+ __OBJC_$_PROTOCOL_REFS_BWPersonalPhotographerDelegate
+ __OBJC_$_PROTOCOL_REFS_BWPersonalPhotographerSceneMonitor
+ __OBJC_$_PROTOCOL_REFS_BWPreviewStabilizationNodeDelegate
+ __OBJC_$_PROTOCOL_REFS_BWSecureSigningUtilityManagerDelegate
+ __OBJC_CLASS_PROTOCOLS_$_BWBaselineTextureStyleRenderer
+ __OBJC_CLASS_PROTOCOLS_$_BWGlobalTextureStyleRenderer
+ __OBJC_CLASS_PROTOCOLS_$_BWGlowTextureStyleRenderer
+ __OBJC_CLASS_PROTOCOLS_$_BWHVSScoringNode
+ __OBJC_CLASS_PROTOCOLS_$_BWPersonalPhotographerSceneMonitorV1
+ __OBJC_CLASS_PROTOCOLS_$_BWSemanticMasksConverterNode
+ __OBJC_CLASS_PROTOCOLS_$_BWSkinTextureStyleRenderer
+ __OBJC_CLASS_PROTOCOLS_$_BWStillImageDuplicateInfo
+ __OBJC_CLASS_PROTOCOLS_$_FigCaptureTextureStyle
+ __OBJC_CLASS_RO_$_BWBaselineTextureStyleRenderer
+ __OBJC_CLASS_RO_$_BWCinematographyObjectTrackingNode
+ __OBJC_CLASS_RO_$_BWGlobalTextureStyleRenderer
+ __OBJC_CLASS_RO_$_BWGlowTextureStyleRenderer
+ __OBJC_CLASS_RO_$_BWHVSCandidateFrameManager
+ __OBJC_CLASS_RO_$_BWHVSEmbeddingAnalysisResult
+ __OBJC_CLASS_RO_$_BWHVSFace
+ __OBJC_CLASS_RO_$_BWHVSFrame
+ __OBJC_CLASS_RO_$_BWHVSFrameAnalysisTask
+ __OBJC_CLASS_RO_$_BWHVSObject
+ __OBJC_CLASS_RO_$_BWHVSPerson
+ __OBJC_CLASS_RO_$_BWHVSPet
+ __OBJC_CLASS_RO_$_BWHVSScoringNode
+ __OBJC_CLASS_RO_$_BWLCBDatabaseManager
+ __OBJC_CLASS_RO_$_BWPersonalPhotographerSceneMonitorV1
+ __OBJC_CLASS_RO_$_BWSecureFaceIDFrameTracker
+ __OBJC_CLASS_RO_$_BWSecureSigningUtilityManager
+ __OBJC_CLASS_RO_$_BWSemanticMasksConverterNode
+ __OBJC_CLASS_RO_$_BWSensorRawTimeMachine
+ __OBJC_CLASS_RO_$_BWSensorRawTimeMachineConfiguration
+ __OBJC_CLASS_RO_$_BWSensorRawTimeMachineFrameConfiguration
+ __OBJC_CLASS_RO_$_BWSkinTextureStyleRenderer
+ __OBJC_CLASS_RO_$_BWStillImageDuplicateInfo
+ __OBJC_CLASS_RO_$_BWTextureStyleInfoMetadataNode
+ __OBJC_CLASS_RO_$_BWTextureStyleTuning
+ __OBJC_CLASS_RO_$_BWTimewarpMetadataNode
+ __OBJC_CLASS_RO_$_BWVideoNoiseReductionNode
+ __OBJC_CLASS_RO_$_FigCaptureAngleMonitor
+ __OBJC_CLASS_RO_$_FigCaptureMagneticInterferenceMonitor
+ __OBJC_CLASS_RO_$_FigCaptureTextureStyle
+ __OBJC_LABEL_PROTOCOL_$_BWCinematicVideoDisparityProvider
+ __OBJC_LABEL_PROTOCOL_$_BWFigVideoCaptureDeviceContinuousAutoFocusTrackingChangedDelegate
+ __OBJC_LABEL_PROTOCOL_$_BWHVSCandidateFrameManagerDelegate
+ __OBJC_LABEL_PROTOCOL_$_BWLCBDatabaseManagerDelegate
+ __OBJC_LABEL_PROTOCOL_$_BWPersonalPhotographerCaptureRegistrationDelegate
+ __OBJC_LABEL_PROTOCOL_$_BWPersonalPhotographerDelegate
+ __OBJC_LABEL_PROTOCOL_$_BWPersonalPhotographerSceneMonitor
+ __OBJC_LABEL_PROTOCOL_$_BWPreviewStabilizationNodeDelegate
+ __OBJC_LABEL_PROTOCOL_$_BWSecureSigningUtilityManagerDelegate
+ __OBJC_METACLASS_RO_$_BWBaselineTextureStyleRenderer
+ __OBJC_METACLASS_RO_$_BWCinematographyObjectTrackingNode
+ __OBJC_METACLASS_RO_$_BWGlobalTextureStyleRenderer
+ __OBJC_METACLASS_RO_$_BWGlowTextureStyleRenderer
+ __OBJC_METACLASS_RO_$_BWHVSCandidateFrameManager
+ __OBJC_METACLASS_RO_$_BWHVSEmbeddingAnalysisResult
+ __OBJC_METACLASS_RO_$_BWHVSFace
+ __OBJC_METACLASS_RO_$_BWHVSFrame
+ __OBJC_METACLASS_RO_$_BWHVSFrameAnalysisTask
+ __OBJC_METACLASS_RO_$_BWHVSObject
+ __OBJC_METACLASS_RO_$_BWHVSPerson
+ __OBJC_METACLASS_RO_$_BWHVSPet
+ __OBJC_METACLASS_RO_$_BWHVSScoringNode
+ __OBJC_METACLASS_RO_$_BWLCBDatabaseManager
+ __OBJC_METACLASS_RO_$_BWPersonalPhotographerSceneMonitorV1
+ __OBJC_METACLASS_RO_$_BWSecureFaceIDFrameTracker
+ __OBJC_METACLASS_RO_$_BWSecureSigningUtilityManager
+ __OBJC_METACLASS_RO_$_BWSemanticMasksConverterNode
+ __OBJC_METACLASS_RO_$_BWSensorRawTimeMachine
+ __OBJC_METACLASS_RO_$_BWSensorRawTimeMachineConfiguration
+ __OBJC_METACLASS_RO_$_BWSensorRawTimeMachineFrameConfiguration
+ __OBJC_METACLASS_RO_$_BWSkinTextureStyleRenderer
+ __OBJC_METACLASS_RO_$_BWStillImageDuplicateInfo
+ __OBJC_METACLASS_RO_$_BWTextureStyleInfoMetadataNode
+ __OBJC_METACLASS_RO_$_BWTextureStyleTuning
+ __OBJC_METACLASS_RO_$_BWTimewarpMetadataNode
+ __OBJC_METACLASS_RO_$_BWVideoNoiseReductionNode
+ __OBJC_METACLASS_RO_$_FigCaptureAngleMonitor
+ __OBJC_METACLASS_RO_$_FigCaptureMagneticInterferenceMonitor
+ __OBJC_METACLASS_RO_$_FigCaptureTextureStyle
+ __OBJC_PROTOCOL_$_BWCinematicVideoDisparityProvider
+ __OBJC_PROTOCOL_$_BWFigVideoCaptureDeviceContinuousAutoFocusTrackingChangedDelegate
+ __OBJC_PROTOCOL_$_BWHVSCandidateFrameManagerDelegate
+ __OBJC_PROTOCOL_$_BWLCBDatabaseManagerDelegate
+ __OBJC_PROTOCOL_$_BWPersonalPhotographerCaptureRegistrationDelegate
+ __OBJC_PROTOCOL_$_BWPersonalPhotographerDelegate
+ __OBJC_PROTOCOL_$_BWPersonalPhotographerSceneMonitor
+ __OBJC_PROTOCOL_$_BWPreviewStabilizationNodeDelegate
+ __OBJC_PROTOCOL_$_BWSecureSigningUtilityManagerDelegate
+ ___104-[FigCaptureDisplayLayoutMonitor initWithFBSDisplayLayoutMonitorCreateFunction:displayType:isV68Device:]_block_invoke
+ ___147-[SubjectSelection updateStatesUsingDetectedObjects:currentPTS:trackedSubjectsByGroupIDOut:pixelBufferSize:nondisruptiveSwitchingFormatZoomFactor:]_block_invoke
+ ___198-[BWFigVideoCaptureStream initWithCaptureStream:parentDevice:attributes:sensorIDDictionary:synchronizedStreamsGroup:isOmahaVariant:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:error:]_block_invoke
+ ___270-[FigCaptureMetadataSinkPipeline _buildMetadataSinkPipeline:graph:videoPreviewOutput:offlineVISMotionDataSourceOutput:metadataSourceOutputsByCategory:semanticMasksMetadataSourceOutput:captureDevice:faceTrackingPipelineStage:clientAuditToken:inferenceScheduler:delegate:]_block_invoke
+ ___28-[BWLCBDatabaseManager init]_block_invoke
+ ___29+[BWTextureStyleTuning setup]_block_invoke
+ ___302-[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:cinematicAudioEnabled:allowLowLatencyWhenPossible:timewarpTargetFramerate:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:]_block_invoke
+ ___31-[BWLCBDatabaseManager dealloc]_block_invoke
+ ___34-[FigCaptureSourceManager dealloc]_block_invoke
+ ___37+[BWLCBDatabaseManager sharedManager]_block_invoke
+ ___394-[BWFigVideoCaptureDevice _initWithCaptureDevice:attributes:synchronizedStreamsAttributes:unsynchronizedStreamsAttributes:multiCamEnabled:midFrameSynchronizationEnabled:superWideAsMidFrameSynchronizationPrimary:secureFaceIDEnabled:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:deviceVendor:createAutofocusSampleBufferProcessorFunction:cameraParameters:deviceClientPriority:error:]_block_invoke
+ ___41-[BWSecureSigningUtilityManager delegate]_block_invoke
+ ___44-[BWLCBDatabaseManager databaseForPortType:]_block_invoke
+ ___45-[BWLCBDatabaseManager lcbDatabaseByPortType]_block_invoke
+ ___45-[BWLCBDatabaseManager saveDatabasesIfNeeded]_block_invoke
+ ___45-[BWSecureSigningUtilityManager setDelegate:]_block_invoke
+ ___46+[BWSecureSigningUtilityManager sharedManager]_block_invoke
+ ___48-[BWHVSCandidateFrameManager finalizeCandidates]_block_invoke
+ ___48-[BWHVSCandidateFrameManager finalizeCandidates]_block_invoke_2
+ ___48-[BWHVSCandidateFrameManager finalizeCandidates]_block_invoke_3
+ ___48-[BWSecureSigningUtilityManager trustObjectData]_block_invoke
+ ___51-[BWLCBDatabaseManager updateDatabase:forPortType:]_block_invoke
+ ___51-[BWSecureSigningUtilityManager clientProvidedHash]_block_invoke
+ ___52-[BWSecureSigningUtilityManager sealingManifestData]_block_invoke
+ ___53-[BWHVSCandidateFrameManager _analyzeDuplicateChains]_block_invoke
+ ___53-[BWSecureSigningUtilityManager secureBootTicketData]_block_invoke
+ ___54-[BWSecureSigningUtilityManager sensorCertificateData]_block_invoke
+ ___54-[BWSecureSigningUtilityManager trustObjectDigestData]_block_invoke
+ ___55-[FigCaptureMagneticInterferenceMonitor stopMonitoring]_block_invoke
+ ___56-[BWSecureSigningUtilityManager lowerBoundTimestampData]_block_invoke
+ ___59-[FigCaptureMagneticInterferenceMonitor _setupStateMachine]_block_invoke
+ ___59-[FigCaptureMagneticInterferenceMonitor _setupStateMachine]_block_invoke_2
+ ___59-[FigCaptureMagneticInterferenceMonitor _setupStateMachine]_block_invoke_3
+ ___59-[FigCaptureMagneticInterferenceMonitor _setupStateMachine]_block_invoke_4
+ ___60-[BWSecureSigningUtilityManager sealingManifestUniqueIDData]_block_invoke
+ ___61-[BWSecureSigningUtilityManager _startPeriodicRefreshOnQueue]_block_invoke
+ ___61-[BWStillImageCoordinatorNode _startCalibrationTimerIfNeeded]_block_invoke
+ ___62-[BWSecureSigningUtilityManager sensorCertificateUniqueIDData]_block_invoke
+ ___63-[BWFigVideoCaptureDevice setFocusModeCustomWithConfiguration:]_block_invoke_2
+ ___63-[BWLCBDatabaseManager _executeDatabaseStorageWorkAsync:block:]_block_invoke
+ ___64-[BWHVSCandidateFrameManager _applyLargeFaceRecovery:faceAreas:]_block_invoke
+ ___65-[FigCaptureMagneticInterferenceMonitor startMonitoringWithZone:]_block_invoke
+ ___66-[BWFigVideoCaptureDevice _overrideIgnoredExposureSignals:values:]_block_invoke
+ ___68-[BWPersonalPhotographerSceneMonitorV1 _setupStorageSpaceCheckTimer]_block_invoke
+ ___69-[BWSecureSigningUtilityManager firstSecureSigningStaticDataFailure:]_block_invoke
+ ___71-[BWLCBDatabaseManager loadDatabasesForSensorConfigurationsByPortType:]_block_invoke
+ ___73-[FigCaptureMagneticInterferenceMonitor _setupExitZoneTimerWithDuration:]_block_invoke
+ ___75-[BWSmartCropNode configurationWithID:updatedFormat:didBecomeLiveForInput:]_block_invoke
+ ___75-[FigCaptureMagneticInterferenceMonitor _handleMagneticInterferenceUpdate:]_block_invoke
+ ___78-[BWSecureSigningUtilityManager lowerBoundTimestampDataForClientProvidedHash:]_block_invoke
+ ___80-[BWSecureSigningUtilityManager isSecureSigningCertificateAvailableWithTimeout:]_block_invoke
+ ___83-[BWFigVideoCaptureDevice secureSigningUtilityManager:didUpdateClientProvidedHash:]_block_invoke
+ ___86-[BWSecureSigningUtilityManager clientProvidedSensorPayloadInfoForClientProvidedHash:]_block_invoke
+ ___87-[BWSecureSigningUtilityManager issueSecureSigningClientCertificateOnQueue:completion:]_block_invoke
+ ___96-[BWSemanticMasksConverterNode _createDetectedObjectsSampleBufferFromSemanticMasksSampleBuffer:]_block_invoke
+ ___97-[BWHVSScoringNode initWithCaptureMode:captureDevice:inferenceScheduler:threadPriority:delegate:]_block_invoke
+ ___FigCaptureCopyInternalDaemonDataContainerURL_block_invoke
+ ___FigCaptureSmartStyleSettingsGetSystemTextureStyle_block_invoke
+ ___FigCaptureSourceSetDeviceAngle_block_invoke
+ ___FigCaptureSourceSetOccluded_block_invoke
+ ___FigCaptureSourceSetPrimaryDisplayRegion_block_invoke
+ ___block_descriptor_114_e8_32o40o48o56o64o72o80o88o_e5_v8?0l
+ ___block_descriptor_32_e156_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBBqBq^{OpaqueFigCaptureSource}f}8l
+ ___block_descriptor_32_e23_v24?08"BWHVSFrame"16l
+ ___block_descriptor_32_e35_q24?0"BWHVSFrame"8"BWHVSFrame"16l
+ ___block_descriptor_32_e56_v28?0"FigCaptureMagneticInterferenceMonitor"8I16I20i24l
+ ___block_descriptor_33_e156_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBBqBq^{OpaqueFigCaptureSource}f}8l
+ ___block_descriptor_40_e156_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBBqBq^{OpaqueFigCaptureSource}f}8l
+ ___block_descriptor_40_e8_32o_e156_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBBqBq^{OpaqueFigCaptureSource}f}8l
+ ___block_descriptor_40_e8_32o_e32_v16?0"FigCaptureAngleMonitor"8l
+ ___block_descriptor_40_e8_32o_e47_v16?0"FigCaptureMagneticInterferenceMonitor"8l
+ ___block_descriptor_40_e8_32r_e156_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBBqBq^{OpaqueFigCaptureSource}f}8l
+ ___block_descriptor_40_e8_32w_e8_v12?0B8l
+ ___block_descriptor_41_e156_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBBqBq^{OpaqueFigCaptureSource}f}8l
+ ___block_descriptor_48_e156_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBBqBq^{OpaqueFigCaptureSource}f}8l
+ ___block_descriptor_48_e8_32o40r_e43_v32?0^{__SecKey=}8"NSArray"16"NSError"24l
+ ___block_descriptor_72_e8_32o40r48r_e156_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBBqBq^{OpaqueFigCaptureSource}f}8l
+ ___block_descriptor_88_e8_32o40o48o56o64o72o_e5_v8?0l
+ ___captureSession_IrisStillImageSinkInitiateManualPersonalPhotographerCapture_block_invoke
+ ___captureSession_IrisStillImageSinkStartPersonalPhotographerSession_block_invoke
+ ___captureSession_IrisStillImageSinkStopPersonalPhotographerSession_block_invoke
+ ___captureSession_IrisStillImageSinkUpdatePersonalPhotographerOrientation_block_invoke
+ ___captureSession_MetadataSinkCaptureFaceIDBracket_block_invoke
+ ___captureSession_SetProperty_block_invoke_2
+ ___captureSession_updateGraphConfiguration_block_invoke_2
+ ___captureSource_ReleaseFaceIDFrameProxyIdentifier_block_invoke
+ ___copy_helper_block_e8_32o40o48o56o64o72o80o88o
+ ___destroy_helper_block_e8_32o40o48o56o64o72o80o88o
+ ___fvcd_significantSubjectsTrackingEnabledForPersonalPhotographer_block_invoke
+ __captureSession_IrisStillImageSinkInitiateManualPersonalPhotographerCapture_block_invoke
+ __captureSession_IrisStillImageSinkStartPersonalPhotographerSession_block_invoke
+ __captureSession_IrisStillImageSinkStopPersonalPhotographerSession_block_invoke
+ __captureSession_IrisStillImageSinkUpdatePersonalPhotographerOrientation_block_invoke
+ __captureSession_MetadataSinkCaptureFaceIDBracket_block_invoke
+ _bwtstu_captureTypeToString
+ _captureSession_IrisStillImageSinkInitiateManualPersonalPhotographerCapture
+ _captureSession_IrisStillImageSinkStartPersonalPhotographerSession
+ _captureSession_IrisStillImageSinkStopPersonalPhotographerSession
+ _captureSession_IrisStillImageSinkUpdatePersonalPhotographerOrientation
+ _captureSession_MetadataSinkCaptureFaceIDBracket
+ _captureSession_handlePersonalPhotographerError
+ _captureSession_liveReconfigureAfterWaitingOnStillImageCoordinatorsIfNeeded
+ _captureSource_ReleaseFaceIDFrameProxyIdentifier
+ _captureSource_StartFaceIDUnwrap
+ _captureSource_updateCachedPropertyAndNotifyWithForceBehaviorAndConfigurationMutexLockedState
+ _captureSource_updateShutterSoundRelaxationEnabledForDisplayRegion
+ _container_copy_sandbox_token
+ _container_error_copy_unlocalized_description
+ _container_get_path
+ _container_query_create
+ _container_query_free
+ _container_query_get_last_error
+ _container_query_get_single_result
+ _container_query_operation_set_flags
+ _container_query_set_class
+ _container_query_set_identifiers
+ _container_query_set_persona_unique_string
+ _cosf
+ _createDetectedObjectsSampleBufferFromSemanticMasksSampleBuffer:.sOnceToken
+ _cs_getCurrentTextureStyle
+ _cs_omahaHasRotationOffset
+ _cs_personalPhotographerDelegate
+ _cs_updatePreviewConnectionOutputDimensionsForCurrentDisplayRegion
+ _csp_cinematicVideoMetadataEnabled
+ _csp_shouldUpdateUltraHighResolutionZeroShutterLagProperties
+ _fcp_parametersContainsEnabledUDNet
+ _gBWHVSCandidateFrameManagerTrace
+ _gBWHVSFrameTrace
+ _gBWHVSObjectTrace
+ _gBWHVSScoringNodeTrace
+ _gBWHVSUtilitiesTrace
+ _gBWLCBDatabaseManagerTrace
+ _gBWSecureSigningUtilityManagerTrace
+ _gBWSensorRawTimeMachineTrace
+ _gBWTimewarpMetadataNodeTrace
+ _gFigCaptureAngleMonitorTrace
+ _hvscfm_duplicateInfoFromMostRecentReplacedFrame
+ _hvsframe_rawCaptureIDForSampleBuffer
+ _hvsutil_anyObjectCenterWithinRect
+ _kBWNodeSampleBufferAttachmentKey_CinematicMetadataMovieFileRecordingStats
+ _kBWNodeSampleBufferAttachmentKey_FileWriterActionTimewarpTimelapseMaxDecimationLevel
+ _kBWNodeSampleBufferAttachmentKey_FileWriterActionTimewarpTimelapseMaxSequenceCaptureID
+ _kBWNodeSampleBufferAttachmentKey_FrameStatisticsByPortType
+ _kBWNodeSampleBufferAttachmentKey_FrameWithinOmahaRenoAngleDropZone
+ _kBWNodeSampleBufferAttachmentKey_PreTimewarpPresentationTimestamp
+ _kBWNodeSampleBufferAttachmentKey_SecureSignedRawImageSurface
+ _kBWNodeSampleBufferAttachmentKey_SecureSignedRawImageSurfaceSize
+ _kBWNodeSampleBufferAttachmentKey_StillImageCaptureMetadata
+ _kBWNodeSampleBufferAttachmentKey_StillImageSceneFlags
+ _kBWNodeSampleBufferAttachmentKey_TextureStylesPostProcessedPeopleData
+ _kBWNodeSampleBufferAttachmentKey_timewarpPresentationTimestamp
+ _kBWSharpnessResultKey_FinalCropRectLaplacianVariance
+ _kBWSharpnessResultKey_PersonFaceSharpness
+ _kBWSharpnessResultKey_PetBodySharpness
+ _kBWSharpnessResultKey_PetFaceSharpness
+ _kBWTextureStyleTuningBlendPreset_Key
+ _kBWTextureStyleTuningBlendThreshold_Key
+ _kBWTextureStyleTuningCaptureMode_Key
+ _kBWTextureStyleTuningCaptureMode_LivePhoto
+ _kBWTextureStyleTuningCaptureMode_Preview
+ _kBWTextureStyleTuningCaptureMode_Still
+ _kBWTextureStyleTuningCaptureType_Key
+ _kBWTextureStyleTuningFilmGrainSeed_Key
+ _kBWTextureStyleTuningGlobalGrainSourcePreset_Key
+ _kBWTextureStyleTuningHardwareModel_Key
+ _kBWTextureStyleTuningPreset_Key
+ _kBWTextureStyleTuning_PresetStandard
+ _kCMITextureStylesStreamingMaxFaceCount
+ _kCMMetadataBaseDataType_UInt64
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticEarsMatte
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticEyebrowsMatte
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticFaceSkinMatte
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticGlassesMatteV2
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticHandsMatte
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticLipsMatte
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticNonFaceSkinMatte
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticNoseMatte
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticPersonInstances
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticPersonMatte
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticSkinMatteV2
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticTattooMatte
+ _kCMPhotoAuxiliaryImageTypeURN_SemanticTeethMatteV2
+ _kCMPhotoAuxiliaryImageTypeURN_UnstyledOriginal
+ _kCMPhotoCustomMetadataTypeURN_TextureStyles
+ _kCMPhotoDNGOptionKey_ProvenanceEnabled
+ _kCMPhoto_ProvenanceMetadata_PrimaryECDSAFrameCtl
+ _kCinematicMetadataMovieFileRecordingStatsKey_ConversionDisabledOnModuleGating
+ _kCinematicMetadataMovieFileRecordingStatsKey_PercentFramesOnWide
+ _kCinematicMetadataMovieFileRecordingStatsKey_PercentFramesOnWideInFirstTenSeconds
+ _kCinematicMetadataMovieFileRecordingStatsKey_PercentFramesOnWideInFirstTwoSeconds
+ _kFigAppleMakerNote_AEInputSignals
+ _kFigAppleMakerNote_AESignals
+ _kFigAppleMakerNote_LCBMitigation
+ _kFigAppleMakerNote_LCBMitigationKey_CorrectedLCBs
+ _kFigAppleMakerNote_LCBMitigationKey_DetectionCountHistogram
+ _kFigAppleMakerNote_LCBMitigationKey_NumberCorrectedOnIRCF
+ _kFigAppleMakerNote_LCBMitigationKey_NumberCorrectedOnLens
+ _kFigAppleMakerNote_LCBMitigationKey_NumberDetected
+ _kFigAppleMakerNote_PersonalPhotographer
+ _kFigAppleMakerNote_ProvenanceFlags
+ _kFigAppleMakerNote_TextureStyleKey_Grain
+ _kFigAppleMakerNote_TextureStyleKey_Intensity
+ _kFigAppleMakerNote_TextureStyleKey_OriginalInsteadOfReversibility
+ _kFigAppleMakerNote_TextureStyleKey_Preset
+ _kFigAppleMakerNote_TextureStyleKey_RenderingVersion
+ _kFigAutofocusSampleBufferProcessorMode_TimewarpCapture
+ _kFigAutofocusSampleBufferProcessorMode_TimewarpPreview
+ _kFigCaptureDeferredPhotoProcessorNotificationPayloadKey_SecureSignedRawSurface
+ _kFigCaptureDeferredPhotoProcessorNotificationPayloadKey_SecureSignedRawSurfaceSize
+ _kFigCaptureDeviceMultiCamConfigurationKey_MutuallyExclusiveUnsynchronizedStreams
+ _kFigCaptureDeviceMultiCamConfigurationKey_SecureFaceIDEnabled
+ _kFigCaptureDeviceMultiCamConfigurationKey_SecureProcessingCoexEnabled
+ _kFigCaptureFlatDictionaryAppleMakerNote_AEInputSignals
+ _kFigCaptureFlatDictionaryAppleMakerNote_AEInputSignals_opaque
+ _kFigCaptureFlatDictionaryAppleMakerNote_AEInputSignals_string
+ _kFigCaptureFlatDictionaryAppleMakerNote_AESignals
+ _kFigCaptureFlatDictionaryAppleMakerNote_AESignals_opaque
+ _kFigCaptureFlatDictionaryAppleMakerNote_AESignals_string
+ _kFigCaptureFlatDictionaryAppleMakerNote_LCBMitigation
+ _kFigCaptureFlatDictionaryAppleMakerNote_LCBMitigation_opaque
+ _kFigCaptureFlatDictionaryAppleMakerNote_LCBMitigation_string
+ _kFigCaptureFlatDictionaryAppleMakerNote_PersonalPhotographer
+ _kFigCaptureFlatDictionaryAppleMakerNote_PersonalPhotographer_opaque
+ _kFigCaptureFlatDictionaryAppleMakerNote_PersonalPhotographer_string
+ _kFigCaptureFlatDictionaryAppleMakerNote_ProvenanceFlags
+ _kFigCaptureFlatDictionaryAppleMakerNote_ProvenanceFlags_opaque
+ _kFigCaptureFlatDictionaryAppleMakerNote_ProvenanceFlags_string
+ _kFigCaptureManualControlAutoTime
+ _kFigCapturePersonalPhotographerDuplicateInfoKey_OriginalPresentationTimestamp
+ _kFigCapturePersonalPhotographerDuplicateInfoKey_ReplacedPhotoTimestamp
+ _kFigCapturePersonalPhotographerDuplicateInfoKey_SettingsID
+ _kFigCapturePersonalPhotographerKey_DetectedContext
+ _kFigCapturePersonalPhotographerKey_DuplicateInfo
+ _kFigCapturePersonalPhotographerKey_FrameID
+ _kFigCapturePersonalPhotographerKey_FrameScore
+ _kFigCapturePersonalPhotographerKey_ManualCapture
+ _kFigCapturePersonalPhotographerKey_SessionID
+ _kFigCapturePortType_RenoFrontFacingSuperWideCamera
+ _kFigCapturePropertyValue_FNumber
+ _kFigCapturePropertyValue_ModuleSerialNumberString
+ _kFigCapturePropertyValue_SensorSigningConfiguration
+ _kFigCaptureSampleBufferAttachedMediaKey_SmartStyleSharedStatistics
+ _kFigCaptureSampleBufferAttachedMediaKey_TextureStyleFaceAttitudeMetadata
+ _kFigCaptureSampleBufferAttachedMediaKey_TextureStyleImageStatistics
+ _kFigCaptureSampleBufferAttachmentKey_FaceID
+ _kFigCaptureSampleBufferAttachmentKey_FocusTrackedObjectInfo
+ _kFigCaptureSampleBufferMetadata_LCBMitigation
+ _kFigCaptureSampleBufferMetadata_LCBMitigationKey_CorrectedLCBs
+ _kFigCaptureSampleBufferMetadata_LCBMitigationKey_DetectionCountHistogram
+ _kFigCaptureSampleBufferMetadata_LCBMitigationKey_NumberCorrectedOnIRCF
+ _kFigCaptureSampleBufferMetadata_LCBMitigationKey_NumberCorrectedOnLens
+ _kFigCaptureSampleBufferMetadata_LCBMitigationKey_NumberDetected
+ _kFigCaptureSampleBufferMetadata_PersonalPhotographer
+ _kFigCaptureSampleBufferMetadata_TextureStylePeopleDataVersion
+ _kFigCaptureSampleBufferMetadata_TextureStylePostProcessedPeopleData
+ _kFigCaptureSampleBufferMetadata_TextureStylePreset
+ _kFigCaptureSampleBufferMetadata_UnsynchronizedStreamsIsPrimaryStream
+ _kFigCaptureSegmentFocusTrackingSalientObjectMetadata_MaskAttachedMediaKey
+ _kFigCaptureSegmentFocusTrackingSalientObjectMetadata_TrackedForContinuousAutoFocus
+ _kFigCaptureSessionDidFinishPersonalPhotographerSessionPayloadKey_CapturesToKeep
+ _kFigCaptureSessionDidFinishPersonalPhotographerSessionPayloadKey_CapturesToRemove
+ _kFigCaptureSessionIrisStillImageSinkNotification_DidFinishPersonalPhotographerSession
+ _kFigCaptureSessionNotificationPayloadKey_SecureSignedRawSurface
+ _kFigCaptureSessionNotificationPayloadKey_SecureSignedRawSurfaceSize
+ _kFigCaptureSessionNotificationPayloadKey_TimewarpTimelapseClassicIntermediateFilePath
+ _kFigCaptureSessionProperty_TextureStyle
+ _kFigCaptureSessionVideoDataSinkProperty_CinematicVideoMetadataCaptureEnabled
+ _kFigCaptureSessionWillBeginCaptureNotificationPayloadKey_SecureSigningPhotoCaptureEnabled
+ _kFigCaptureSourceAttributeKey_AdaptiveFusion
+ _kFigCaptureSourceAttributeKey_LowCurrentTorchSupported
+ _kFigCaptureSourceAttributeKey_MagneticInterferenceZone
+ _kFigCaptureSourceAttributeKey_MaxLensAperture
+ _kFigCaptureSourceAttributeKey_MinLensAperture
+ _kFigCaptureSourceAttributeKey_PrimaryConstituentDeviceSwitchingBehaviorLockedWithDeviceSupported
+ _kFigCaptureSourceAttributeKey_RecommendedLensApertures
+ _kFigCaptureSourceAttributeKey_SupportedExposureSignals
+ _kFigCaptureSourceAttributeKey_TNRMachineLearningImageRegistrationSupported
+ _kFigCaptureSourceExposureOperationKey_LensAperture
+ _kFigCaptureSourceFaceIDUnwrapStatusChangedPayloadKey_PearlSecureSessionError
+ _kFigCaptureSourceFaceIDUnwrapStatusChangedPayloadKey_Status
+ _kFigCaptureSourceFaceIDUnwrapStatusChangedPayloadKey_StreamError
+ _kFigCaptureSourceFocusOperationKey_Tracking
+ _kFigCaptureSourceFocusOperationKey_TrackingLensPositionBias
+ _kFigCaptureSourceFocusOperationKey_TrackingSeedingPoint
+ _kFigCaptureSourceNotification_ContinuousAutoFocusTrackingSubjectAcquiredChanged
+ _kFigCaptureSourceNotification_FaceIDUnwrapStatusChanged
+ _kFigCaptureSourceNotification_PersonalPhotographerSubjectDetectionStatusChanged
+ _kFigCaptureSourcePersonalPhotographerSubjectDetectionStatusChangedPayloadKey_Status
+ _kFigCaptureSourcePropertyBravoCameraSelectionConfigurationKey_LockedDeviceType
+ _kFigCaptureSourceProperty_ActiveExposureSignals
+ _kFigCaptureSourceProperty_AutoExposureLensApertureRateLimit
+ _kFigCaptureSourceProperty_AutomaticallyIgnoresExposureSignals
+ _kFigCaptureSourceProperty_DeviceAngle
+ _kFigCaptureSourceProperty_IgnoredExposureSignals
+ _kFigCaptureSourceProperty_LensAperture
+ _kFigCaptureSourceProperty_LowCurrentTorchEnabled
+ _kFigCaptureSourceProperty_Occluded
+ _kFigCaptureSourceProperty_PrimaryDisplayRegion
+ _kFigCaptureSourceProperty_SecureSigningPhotoCaptureEnabled
+ _kFigCaptureSourceProperty_SupportedExposureSignals
+ _kFigCaptureStreamABDNetConfigurationKey_Mode
+ _kFigCaptureStreamAEApertureIgnorableSignals
+ _kFigCaptureStreamApertureControlDistanceRangeSuggestionKey_Max
+ _kFigCaptureStreamApertureControlDistanceRangeSuggestionKey_Min
+ _kFigCaptureStreamApertureHealthKey_MaxTrackingError
+ _kFigCaptureStreamApertureHealthKey_TrackingError
+ _kFigCaptureStreamAutoFocusPositionSensorOffsetEstimatorInfoKey_HingeAngle
+ _kFigCaptureStreamAutoFocusPositionSensorOffsetEstimatorInfoKey_Reason
+ _kFigCaptureStreamCameraControlsSemanticHintsKey_ApertureControlDistanceRangeSuggestion
+ _kFigCaptureStreamCameraControlsSemanticHintsKey_SubjectMotionPixelsPerSecond
+ _kFigCaptureStreamMetadataOutputConfigurationKey_FocusSegmentationMaskConfiguration
+ _kFigCaptureStreamMetadataOutputConfigurationKey_FocusSegmentationMaskEnabled
+ _kFigCaptureStreamMetadataOutputConfigurationKey_SecureColorCameraAssistEnabled
+ _kFigCaptureStreamMetadataOutputConfigurationKey_SecureFaceIDConfiguration
+ _kFigCaptureStreamMetadataOutputConfigurationKey_SecureFaceIDEnabled
+ _kFigCaptureStreamMetadataOutputKey_FocusSegmentationMask
+ _kFigCaptureStreamMetadataOutputKey_SecureFaceID
+ _kFigCaptureStreamMetadata_AEApertureActiveSignals
+ _kFigCaptureStreamMetadata_AEInputSignals
+ _kFigCaptureStreamMetadata_AESignals
+ _kFigCaptureStreamMetadata_ApertureDiameter
+ _kFigCaptureStreamMetadata_ApertureHealth
+ _kFigCaptureStreamMetadata_CaptureID
+ _kFigCaptureStreamMetadata_ColorProcessingMode
+ _kFigCaptureStreamMetadata_FrontEndPyramidOutputColorProcessingParameters
+ _kFigCaptureStreamMetadata_TargetFNumber
+ _kFigCaptureStreamMetadata_TimewarpDecimationLevel
+ _kFigCaptureStreamMetadata_TimewarpDecimationTag
+ _kFigCaptureStreamMetadata_TimewarpDesiredFrameRate
+ _kFigCaptureStreamMetadata_TimewarpSequenceCaptureID
+ _kFigCaptureStreamMetadata_TimewarpShouldSkipFrame
+ _kFigCaptureStreamMetadata_VariableApertureTemperature
+ _kFigCaptureStreamObjectDetectionConfigurationKey_HumanFaceImageQualityEnabled
+ _kFigCaptureStreamProperty_ABDNetConfiguration
+ _kFigCaptureStreamProperty_AEApertureBehavior
+ _kFigCaptureStreamProperty_AEApertureIgnoreSignals
+ _kFigCaptureStreamProperty_AEMaxApertureChange
+ _kFigCaptureStreamProperty_ApertureHealthEnabled
+ _kFigCaptureStreamProperty_CaptureSecureFaceIDBracket
+ _kFigCaptureStreamProperty_LCB
+ _kFigCaptureStreamProperty_LowCurrentTorchEnabled
+ _kFigCaptureStreamProperty_MagneticInterferenceDetected
+ _kFigCaptureStreamProperty_SecureFrameProxyIdentifierRelease
+ _kFigCaptureStreamProperty_SegmentFocusTrackingConfiguration
+ _kFigCaptureStreamProperty_SensorSigningClientProvidedHash
+ _kFigCaptureStreamProperty_TimewarpConfiguration
+ _kFigCaptureStreamProperty_TimewarpRecordingInProgress
+ _kFigCaptureStreamSecureFaceIDFrameProxyKey_FrameIdentifier
+ _kFigCaptureStreamSecureFaceIDKey_MetadataFrameProxy
+ _kFigCaptureStreamSecureFaceIDKey_RawFrameProxy
+ _kFigCaptureStreamSecureFaceIDKey_ReferenceFrameProxy
+ _kFigCaptureStreamSecureObjectDetectionConfigurationKey_RawFrameDeliveryEnabled
+ _kFigCaptureStreamSegmentFocusTrackingConfigurationKey_Enabled
+ _kFigCaptureStreamSensorSigningConfigurationKey_Enabled
+ _kFigCaptureStreamSensorSigningConfigurationKey_PhaseData
+ _kFigCaptureStreamSensorSigningConfigurationKey_V2H2
+ _kFigCaptureStreamTemporalNoiseReductionConfigurationKey_MachineLearningImageRegistrationEnabled
+ _kFigCaptureStreamTemporalNoiseReductionConfigurationKey_MachineLearningImageRegistrationMaxFrameRate
+ _kFigCaptureStreamTemporalNoiseReductionConfigurationKey_MachineLearningImageRegistrationMaxLuxLevel
+ _kFigCaptureStreamTimeOfFlightAssistedAutoFocusEstimatorResultsKey_TrainingApertureZone0MLAF
+ _kFigCaptureStreamTimeOfFlightAssistedAutoFocusEstimatorResultsKey_TrainingApertureZone0PDAF
+ _kFigCaptureStreamTimeOfFlightAssistedAutoFocusEstimatorResultsKey_TrainingApertureZone1MLAF
+ _kFigCaptureStreamTimeOfFlightAssistedAutoFocusEstimatorResultsKey_TrainingApertureZone1PDAF
+ _kFigCaptureStreamTimewarpConfigurationKey_Enable
+ _kFigCaptureStreamTimewarpConfigurationKey_MaxFrameRate
+ _kFigCaptureStreamTimewarpConfigurationKey_MinFrameRate
+ _kFigCaptureStreamTimewarpConfigurationKey_Mode
+ _kFigCaptureStreamVideoFormatKey_SensorSigningEnabled
+ _kFigCaptureStreamVideoFormatKey_SupportedSensorSigningConfiguration
+ _kFigCaptureVideoSourceUniqueID_BostonSuperWide
+ _kFigCaptureVideoSourceUniqueID_BostonWide
+ _kFigCaptureVideoSourceUniqueID_ColorAssistedInfraredMetadata
+ _kFigCaptureVideoSourceUniqueID_RenoFrontSuperWideMetadata
+ _kFigCaptureVideoSourceUniqueID_RenoSuperWide
+ _kFigCaptureVideoSourceUniqueID_RenoWide
+ _kFigFSINCCGImageMetadataNamespace
+ _kFigFSINCCGImageMetadataPrefixFSINCMattes
+ _kFigFSINCCGImagePrivateMetadataTagKey_FSINCMatteVersion
+ _kFigImageControlSampleBufferProcessorProperty_ApertureLimitsByPortType
+ _kFigMetadataIdentifier_QuickTimeMetadataCinematicVideoMetadata
+ _kFigMetadataIdentifier_QuickTimeMetadataFaceID
+ _kFigMetadataIdentifier_QuickTimeMetadataFocusTrackedObject
+ _kFigPersonalPhotographerMetadata
+ _kFigPersonalPhotographerMetadata_Version
+ _kFigQuicktimeMetadataKey_TextureStyleGrain
+ _kFigQuicktimeMetadataKey_TextureStyleIntensity
+ _kFigQuicktimeMetadataKey_TextureStylePreset
+ _kFigQuicktimeMetadataKey_TextureStyleRenderingVersion
+ _kFigQuicktimeMetadataKey_TimewarpCaptureMode
+ _kFigQuicktimeMetadataKey_TimewarpTimelapseFastDecimationAllowed
+ _kFigQuicktimeMetadataKey_TimewarpTimelapseMaxDecimationLevel
+ _kFigVideoCaptureSourceActivationOptionKey_AttachedInfraredSourceEnabled
+ _kFigVideoCaptureSourceActivationOptionKey_AutoFullFullUltraHighResolutionZeroShutterLagEnabled
+ _kFigVideoCaptureSourceActivationOptionKey_CoexistenceWithInfraredSourceEnabled
+ _kFigVideoCaptureSourceActivationOptionKey_ColorAssistedSecureFaceIDEnabled
+ _kFigVideoCaptureSourceActivationOptionKey_CompatibilityWithColorAssistedFaceIDEnabled
+ _kFigVideoCaptureSourceActivationOptionKey_OmahaPrimarySourceDeviceType
+ _kFigVideoCaptureSourceActivationOptionKey_SecureSigningPhotoCaptureSupportEnabled
+ _kFigVideoStabilizationSampleBufferAttachmentKey_TextureStyleTuningParameters
+ _kFigVideoStabilizationTextureStyleTuningKey_Intensity
+ _kHVSAuxScoreStatsKeyFaceLV
+ _kHVSAuxScoreStatsKeyFaceQuality
+ _kHVSAuxScoreStatsKeyPetFaceConfidence
+ _kHVSAuxScoreStatsKeyPetFaceLV
+ _kHVSCandidateConfigKeyBreakDuplicateChains
+ _kHVSCandidateConfigKeyBreakPauseMs
+ _kHVSCandidateConfigKeyBudgetConstraint
+ _kHVSCandidateConfigKeyBudgetEnabled
+ _kHVSCandidateConfigKeyCandidateMaxAgeMs
+ _kHVSCandidateConfigKeyCandidateMaxListSize
+ _kHVSCandidateConfigKeyCandidateMaxPerContext
+ _kHVSCandidateConfigKeyCandidateMinProximityMs
+ _kHVSCandidateConfigKeyCleanDups
+ _kHVSCandidateConfigKeyContextPriorities
+ _kHVSCandidateConfigKeyDuplicateConstraint
+ _kHVSCandidateConfigKeyDuplicateMaxTimeMs
+ _kHVSCandidateConfigKeyDuplicateThresholds
+ _kHVSCandidateConfigKeyFaceMargin
+ _kHVSCandidateConfigKeyLargeFacePerContext
+ _kHVSCandidateConfigKeyLegacy
+ _kHVSCandidateConfigKeyMaxFramesPer20Sec
+ _kHVSCandidateConfigKeyMinBudget
+ _kHVSCandidateConfigKeyMinPauseDurationMs
+ _kHVSCandidateConfigKeyMinThresholds
+ _kHVSCandidateConfigKeyPOR2026
+ _kHVSCandidateConfigKeyPOR2026MaxBudget
+ _kHVSCandidateConfigKeyPercentageOfMaxScore
+ _kHVSCandidateConfigKeyRTBucketMaxAgeMs
+ _kHVSCandidateConfigKeyRecoverExtras
+ _kHVSCandidateConfigKeySavePauseMs
+ _kHVSCandidateConfigKeySimBoostPerContext
+ _kHVSCandidateConfigKeySimThreshold
+ _kHVSCandidateConfigKeyTinyFacePerContext
+ _kHVSCandidateConfigKeyTinyFaceRatio
+ _kHVSCandidateConfigKeyTinyFaceReference
+ _kHVSCandidateConfigValueBudgetSoft
+ _kHVSConfigKeyAuxFaceSharpnessWeights
+ _kHVSConfigKeyAuxScoreStats
+ _kHVSConfigKeyAuxScoreWeights
+ _kHVSConfigKeyAuxSharpnessWeights
+ _kHVSConfigKeyBodyEdgeThreshold
+ _kHVSConfigKeyBoostPerContext
+ _kHVSConfigKeyCheckpointFolder
+ _kHVSConfigKeyConfig
+ _kHVSConfigKeyContexts
+ _kHVSConfigKeyCropPenaltyWeights
+ _kHVSConfigKeyDeviceSharpnessIntercept
+ _kHVSConfigKeyDeviceSharpnessSlope
+ _kHVSConfigKeyFaceEdgeThreshold
+ _kHVSConfigKeyFaceQualityGateBonusRange
+ _kHVSConfigKeyFaceQualityGateFQTrust
+ _kHVSConfigKeyFaceQualityGateMLVHigh
+ _kHVSConfigKeyFaceQualityGateMLVLow
+ _kHVSConfigKeyFaceQualityGateMaxBonus
+ _kHVSConfigKeyFaceQualityGatePerContext
+ _kHVSConfigKeyFaceQualityGateThreshold
+ _kHVSConfigKeyFaceSharpnessBoostFalloffRate
+ _kHVSConfigKeyFaceSharpnessBoostThreshold
+ _kHVSConfigKeyFrontalPerContext
+ _kHVSConfigKeyGlobalSharpnessDivisor
+ _kHVSConfigKeyGlobalSharpnessMultiplier
+ _kHVSConfigKeyLargeFaces
+ _kHVSConfigKeyMetadata
+ _kHVSConfigKeyMinBodyAreaRatio
+ _kHVSConfigKeyMinContextProb
+ _kHVSConfigKeyMinContextProbSum
+ _kHVSConfigKeyMinFaceAreaX1e5
+ _kHVSConfigKeyMinLogitThreshold
+ _kHVSConfigKeyNetworkOutputScalar
+ _kHVSConfigKeyPeoplePetsFiltering
+ _kHVSConfigKeyPercentOfLargestFace
+ _kHVSConfigKeyPetCropPenaltyWeights
+ _kHVSConfigKeyPrompts
+ _kHVSConfigKeySharpnessMapCapRange
+ _kHVSConfigKeySharpnessMapNormalizeMax
+ _kHVSConfigKeySharpnessMapSensitivity
+ _kHVSConfigKeySharpnessMapThreshold
+ _kHVSConfigKeySharpnessTargetShorterDimension
+ _kHVSConfigKeyTransitionMatrix
+ _kHVSContextTypePetPose
+ _kHVSContextTypeUnknown
+ _kHVSEmbeddingKeyActive
+ _kHVSEmbeddingKeyCount
+ _kHVSEmbeddingKeyData
+ _kHVSEmbeddingKeyEmbedding
+ _kHVSEmbeddingKeyNegativeEmbedding
+ _kHVSEmbeddingKeyPositiveEmbedding
+ _kHVSEmbeddingKeyWeight
+ _kHVSFrameMetadataKeyAuxScore
+ _kHVSFrameMetadataKeyCaptureSettingsID
+ _kHVSFrameMetadataKeyCropPenalty
+ _kHVSFrameMetadataKeyDetectedContext
+ _kHVSFrameMetadataKeyEV0RawCaptureID
+ _kHVSFrameMetadataKeyFrameHeight
+ _kHVSFrameMetadataKeyFrameID
+ _kHVSFrameMetadataKeyFrameMetadata
+ _kHVSFrameMetadataKeyFrameOrientation
+ _kHVSFrameMetadataKeyFramePixelFormat
+ _kHVSFrameMetadataKeyFrameScore
+ _kHVSFrameMetadataKeyFrameTracking
+ _kHVSFrameMetadataKeyFrameWidth
+ _kHVSFrameMetadataKeyImageEmbedding
+ _kHVSFrameMetadataKeyIsManualCapture
+ _kHVSFrameMetadataKeyIsPauseFrame
+ _kHVSFrameMetadataKeyMaskedFrameSharpness
+ _kHVSFrameMetadataKeyMaxFaceProminence
+ _kHVSFrameMetadataKeyOriginalPresentationTimestamp
+ _kHVSFrameMetadataKeyPauseDuration
+ _kHVSFrameMetadataKeyPeople
+ _kHVSFrameMetadataKeyPersonMaskPNG
+ _kHVSFrameMetadataKeyPetCropPenalty
+ _kHVSFrameMetadataKeyPets
+ _kHVSFrameMetadataKeySIFRRawCaptureID
+ _kHVSFrameMetadataKeySbufPresentationTimestamp
+ _kHVSFrameMetadataKeySegmentIndex
+ _kHVSFrameMetadataKeyUnifiedEmbeddingNetworkOutput
+ _kLCBDatabaseQueueKey
+ _kVTCompressionPropertyKey_AverageNonDroppableFrameRate
+ _kVTCompressionPropertyKey_MaxKeyFrameInterval
+ _kVTCompressionPropertyKey_MaximumRealTimeFrameRate
+ _magneticInterference_updateStylusData
+ _multiStreamCameraSourceNode_secureFaceIDServiceQueueCallback
+ _objc_msgSend$_addProvenanceSensorRawForEncodingScheme:sampleBuffer:
+ _objc_msgSend$_addSmartStyleUnstyledImageForEncodingScheme:sampleBuffer:primaryOutputAspectRatio:stillImageSettings:
+ _objc_msgSend$_addTextureStyleMetadataForEncodingScheme:sampleBuffer:requestedStillImageCaptureSettings:resolvedStillImageCaptureSettings:
+ _objc_msgSend$_addTextureStylePersonInstanceMasksForEncodingScheme:sampleBuffer:primaryOutputAspectRatio:settingsID:orientation:parentImageHandle:
+ _objc_msgSend$_analyzeDuplicateChains
+ _objc_msgSend$_applyLargeFaceRecovery:faceAreas:
+ _objc_msgSend$_applyMaxScoresPerContext
+ _objc_msgSend$_applyTinyFaceFiltering
+ _objc_msgSend$_asynchronouslyLearnWithContainer:inputUnstyledSampleBuffer:withUnrefinedMasks:portTypeToLearn:synchronizedPortTypeToLearn:withStats:withStatsExtended:styleToLearn:currentTextureStyle:shouldLearn:shouldBypass:
+ _objc_msgSend$_availableBudget
+ _objc_msgSend$_blendedTuningParametersForPortType:intensity:effectiveIntensityOut:
+ _objc_msgSend$_cleanupRemovalFlagsForUnpromotedCauses
+ _objc_msgSend$_clearDeviceAngleState
+ _objc_msgSend$_clearOmahaRenoAngleWithinDropZone
+ _objc_msgSend$_computeCropPenaltyForFaceRects:bodyRects:faceEdgeThreshold:bodyEdgeThreshold:minBodyAreaRatio:finalCropRect:
+ _objc_msgSend$_computeCropPenaltyWithFaceEdgeThreshold:bodyEdgeThreshold:minBodyAreaRatio:percentOfLargestFace:minFaceArea:finalCropRect:
+ _objc_msgSend$_computeMaskedFaceSharpnessWithPercentOfLargestFace:minFaceArea:threshold:capRange:sensitivity:normalizeMax:
+ _objc_msgSend$_computePetCropPenaltyWithFaceEdgeThreshold:bodyEdgeThreshold:minBodyAreaRatio:finalCropRect:
+ _objc_msgSend$_contextExistsInPromotedFrames:
+ _objc_msgSend$_correctRectanglesInDetectedObjectsInfo:derivedFromAttachedMedia:
+ _objc_msgSend$_createDetectedObjectsSampleBufferFromSemanticMasksSampleBuffer:
+ _objc_msgSend$_description
+ _objc_msgSend$_faceCombinedFactor:mlvLow:mlvHigh:bonusRange:maxBonus:
+ _objc_msgSend$_findLowestScoreFrameFromMostPopulatedContext
+ _objc_msgSend$_findWeakestPromotedFrameForContext:
+ _objc_msgSend$_getPortTypeFromMetadataDict:
+ _objc_msgSend$_handleMagneticInterferenceChange:
+ _objc_msgSend$_handleOmahaRenoAngleWithinDropZoneState:
+ _objc_msgSend$_handlePrewarmForFSINCMasksForEncodingScheme:requestedStillImageCaptureSettings:
+ _objc_msgSend$_initWithCaptureDevice:attributes:synchronizedStreamsAttributes:unsynchronizedStreamsAttributes:multiCamEnabled:midFrameSynchronizationEnabled:superWideAsMidFrameSynchronizationPrimary:secureFaceIDEnabled:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:deviceVendor:createAutofocusSampleBufferProcessorFunction:cameraParameters:deviceClientPriority:error:
+ _objc_msgSend$_initWithExposureDuration:minFrameRate:maxFrameRate:ISO:lensAperture:useSpotMetering:requestID:
+ _objc_msgSend$_isDuplicateOfFrame:comparedToFrame:
+ _objc_msgSend$_isDuplicateOfFrame:comparedToFrameDict:
+ _objc_msgSend$_isDuplicateWithEmbedding:timestamp:context:andEmbedding:timestamp:context:simBoost:minProximitySec:dampedSimilarity:
+ _objc_msgSend$_isEffectEnabled:inEffectOrder:
+ _objc_msgSend$_isFailedCaptureFrameID:
+ _objc_msgSend$_isManualPromotedFrameID:
+ _objc_msgSend$_magneticInterferenceZoneFromActiveSources
+ _objc_msgSend$_mapAndNormalizeScore:threshold:capRange:sensitivity:normalizeMax:
+ _objc_msgSend$_matchBudgetByManagingExtras
+ _objc_msgSend$_newAuxiliaryImagePropertiesForFSINCMask:fsincMatteVersion:
+ _objc_msgSend$_newCandidateFrameFromRealtimeBucket:
+ _objc_msgSend$_newPauseFrameFromInputFrame:
+ _objc_msgSend$_newPixelBufferWithDimensions:pixelFormat:name:
+ _objc_msgSend$_normalizeAuxScore:statsDict:
+ _objc_msgSend$_normalizeDeviceSharpness:
+ _objc_msgSend$_normalizeGlobalSharpness:divisor:multiplier:
+ _objc_msgSend$_postCleanupBudgetReverification
+ _objc_msgSend$_promoteAgedOutCandidatesWithCurrentTime:
+ _objc_msgSend$_promoteFrame:
+ _objc_msgSend$_promotedFrameSharingRawCaptureWithFrame:
+ _objc_msgSend$_recoverExtrasWithinBudget
+ _objc_msgSend$_resolveBreakPauseDuplicateForNewFrame:comparedToFrame:
+ _objc_msgSend$_resolveBreakPauseDuplicateForNewFrame:comparedToFrameDict:
+ _objc_msgSend$_resolveBreakPauseDuplicateForNewIsPause:newSegmentIdx:newTimestamp:dupIsPause:dupSegmentIdx:dupTimestamp:
+ _objc_msgSend$_resolvePromotedFrameDuplicatesForFrame:
+ _objc_msgSend$_setupBloomForSkinMask:metadataDict:effectsToRender:
+ _objc_msgSend$_setupCommonInputsForInputPixelBuffer:outputPixelBuffer:
+ _objc_msgSend$_setupDiffusionForPersonMask:forSkinMaskPixelBuffer:metadataDict:intensity:effectsToRender:
+ _objc_msgSend$_setupGlowForPersonMask:metadataDict:linearThumbnail:linearThumbnailMetadata:intensity:effectsToRender:statistics:
+ _objc_msgSend$_setupInputMaskForPixelBuffer:maskType:maskIsOptional:metadataDict:
+ _objc_msgSend$_setupLinearImageFromPixelBuffer:linearImageMetadata:
+ _objc_msgSend$_setupMattifyForSkinMask:metadataDict:intensity:effectsToRender:
+ _objc_msgSend$_setupPersonDataFromMetadata:maxFaceCount:
+ _objc_msgSend$_setupProcessorFullImageSizeAndRegionToRenderPixelBuffer:
+ _objc_msgSend$_shouldAddCandidate:
+ _objc_msgSend$_silentlyRemoveMaxScoreFrameID:causingFrameID:
+ _objc_msgSend$_totalBudget
+ _objc_msgSend$_tryPromoteFrame:
+ _objc_msgSend$_tryReplaceLowestCandidateOnBudgetFailure:
+ _objc_msgSend$_tuningParametersForPortType:
+ _objc_msgSend$_updateDeviceAngleState
+ _objc_msgSend$_updateOccludedState
+ _objc_msgSend$_updateTextureStyleEnableFlagsForMetadataDict:
+ _objc_msgSend$active
+ _objc_msgSend$activeExposureSignals
+ _objc_msgSend$activeOmahaConstituentDeviceType
+ _objc_msgSend$activeZeroShutterLagFlavorHighResolutionFlavor
+ _objc_msgSend$adaptiveFusionDowngradeSNRHysteresisLag
+ _objc_msgSend$adaptiveFusionDowngradeSNRThreshold
+ _objc_msgSend$adaptiveFusionSupported
+ _objc_msgSend$addFrameIdentifiersForFaceIDResult:
+ _objc_msgSend$addStillImageSceneFlags:
+ _objc_msgSend$adjustedAspectRatioForActiveOmahaConstituentDevice
+ _objc_msgSend$allowedPTSDeltaFrameIntervalFactor
+ _objc_msgSend$analysisEnabled
+ _objc_msgSend$apertureControlDistanceRangeWithError:
+ _objc_msgSend$applyIsUnsynchronizedPrimary:
+ _objc_msgSend$applyOctagonMirrorExtensionToPixelBuffer:
+ _objc_msgSend$attachMatchingHueMapToMainSampleBuffer:mainPTS:mainExposureTime:frameRate:
+ _objc_msgSend$autoFullFullUltraHighResolutionZeroShutterLagEnabled
+ _objc_msgSend$autoSecureSigningPhotoCaptureEnabled
+ _objc_msgSend$automaticallyIgnoredExposureSignals
+ _objc_msgSend$automaticallyIgnoresExposureSignals
+ _objc_msgSend$blendedTuningFrom:to:intensity:blendThreshold:effectiveIntensityOut:
+ _objc_msgSend$body
+ _objc_msgSend$bufferingTime
+ _objc_msgSend$calibrationCaptureSettingsWithSettingsID:
+ _objc_msgSend$captureFaceIDBracketWithConfiguration:
+ _objc_msgSend$captureTypeToString:
+ _objc_msgSend$cinematicVideoMetadataCaptureEnabled
+ _objc_msgSend$cinematicVideoMetadataCaptureEnabledByClient
+ _objc_msgSend$cinematicVideoMetadataDeliveryEnabled
+ _objc_msgSend$cinematicVideoMetadataEnabled
+ _objc_msgSend$cinematicVideoMetadataNode
+ _objc_msgSend$cinematicVideoWithoutEmbeddedDepthSupported
+ _objc_msgSend$cinematographyObjectTrackingNode
+ _objc_msgSend$clientProvidedHash
+ _objc_msgSend$cmi_mergeEntriesFromDictionary:
+ _objc_msgSend$coexistenceWithInfraredSourceEnabled
+ _objc_msgSend$colorAssistedInfraredMetadataCameraSupported
+ _objc_msgSend$colorCameraAssistEnabled
+ _objc_msgSend$computeAuxTextureRegionInCropSpaceWithPixelBuffer:auxCropRect:fullImageSize:
+ _objc_msgSend$configurationWithUnsynchronizedActiveStreamsPortTypes:synchronizedActiveStreamsGroupsPortTypes:mutuallyExclusiveUnsynchronizedStreamsPortTypes:stereoVideoCaptureEnabled:multiCamClientCompositingEnabled:colorAssistedSecureFaceIDEnabled:secureProcessingCoexEnabled:exclusivelyForSecureProcessing:builtInMicrophoneIsRecording:
+ _objc_msgSend$configureForFullFullUltraHighResolutionZeroShutterLagSupport
+ _objc_msgSend$contextProbabilities
+ _objc_msgSend$continuousAutoFocusDidAcquireSubject:
+ _objc_msgSend$convertUnitOfAngleInPersonInputDataArrayToRadians:
+ _objc_msgSend$copyForPersonalPhotographerWithSettingsID:rotationDegrees:mirrored:
+ _objc_msgSend$copyForPortType:
+ _objc_msgSend$copyMatchingSampleBufferWithFrameType:mainPTS:mainExposureTime:frameRate:
+ _objc_msgSend$copyStatsForOtherEffectsTo:
+ _objc_msgSend$currentActiveRequestedSettings
+ _objc_msgSend$dataWithContentsOfFile:
+ _objc_msgSend$dateWithTimeInterval:sinceDate:
+ _objc_msgSend$defaultFNumber
+ _objc_msgSend$defaultLensAperture
+ _objc_msgSend$degrunge
+ _objc_msgSend$depthCompressorNode
+ _objc_msgSend$depthPaddingPipelineStateWithDevice:bundle:error:
+ _objc_msgSend$detectedContext
+ _objc_msgSend$didStopContinuousAutoFocusTracking
+ _objc_msgSend$disabled
+ _objc_msgSend$displayRegion
+ _objc_msgSend$duplicateInfo
+ _objc_msgSend$effectTypeToEffectName:
+ _objc_msgSend$ev0RawCaptureID
+ _objc_msgSend$expectsFrameSkipping
+ _objc_msgSend$exportLCBsForCaptureStream
+ _objc_msgSend$exposureSignals
+ _objc_msgSend$exposureSignalsRequireApertureControlSceneMonitor:
+ _objc_msgSend$exposureTime
+ _objc_msgSend$fNumber
+ _objc_msgSend$face
+ _objc_msgSend$faceCaptureQuality
+ _objc_msgSend$faceIDCoexistenceEnabled
+ _objc_msgSend$faceIDCompanionFormat
+ _objc_msgSend$faceIDConfiguration
+ _objc_msgSend$faceIDEnabled
+ _objc_msgSend$faceId
+ _objc_msgSend$faceImageQualityDetectionEnabled
+ _objc_msgSend$faceObservationWithRequestRevision:boundingBox:roll:yaw:pitch:
+ _objc_msgSend$faceObservations
+ _objc_msgSend$faceROI
+ _objc_msgSend$filmGrainSeedForCaptureRequestIdentifier:
+ _objc_msgSend$finalCropRectLaplacianVariance
+ _objc_msgSend$finalizeCandidates
+ _objc_msgSend$flushCachedProperties
+ _objc_msgSend$flushFramesUpToPTS:frameRate:
+ _objc_msgSend$focusTrackedObjectsDeliveryEnabled
+ _objc_msgSend$formatIndexForZoomFactor:frameStatistics:imageControlMode:stillImageDigitalFlashMode:isStationary:isSecondaryStream:binnedSIFROnSecondaryStreamAllowed:ignoreZoomFactorAndQuadraSubPixelSceneMonitoring:secureSigningMode:ultraHighResolutionZeroShutterLagEnabled:
+ _objc_msgSend$frameConfigurationByFrameType
+ _objc_msgSend$frameID
+ _objc_msgSend$frameScore
+ _objc_msgSend$fsincMasksPrewarmedForCurrentEncoding
+ _objc_msgSend$fullImageSize
+ _objc_msgSend$getRequiredMemorySize
+ _objc_msgSend$grain
+ _objc_msgSend$groupID
+ _objc_msgSend$halationChroma
+ _objc_msgSend$hasSecureSigningFormats
+ _objc_msgSend$hasSecureSigningNondisruptiveFormats
+ _objc_msgSend$hueMapPixelBuffer
+ _objc_msgSend$hvsCandidateFrameManager:didRegisterFramesToKeep:framesToDelete:
+ _objc_msgSend$hvsParameters
+ _objc_msgSend$hvsScoringNode:didFinishPersonalPhotographerSessionWithCapturesToKeep:capturesToDelete:stillImageCoordinatorNode:settings:
+ _objc_msgSend$ignoredExposureSignals
+ _objc_msgSend$imageDimensions
+ _objc_msgSend$imageEmbedding
+ _objc_msgSend$imageStats
+ _objc_msgSend$initCalibrationWithRequestedSettings:
+ _objc_msgSend$initFileURLWithFileSystemRepresentation:isDirectory:relativeToURL:
+ _objc_msgSend$initForSensorID:moduleSerial:
+ _objc_msgSend$initForTimewarpMode:sourceClock:
+ _objc_msgSend$initWithANSTObject:faceObservation:imageDimensions:isFrontal:
+ _objc_msgSend$initWithANSTObject:imageDimensions:
+ _objc_msgSend$initWithAngleHandler:
+ _objc_msgSend$initWithArray:copyItems:
+ _objc_msgSend$initWithBody:face:imageDimensions:orientation:
+ _objc_msgSend$initWithCameraInfoByPortType:maxLossyCompressionLevel:ispProcessingSession:videoNoiseReductionGainThresholdsByPortType:visOutputDimensions:
+ _objc_msgSend$initWithCaptureDevice:attributes:synchronizedStreamsAttributes:unsynchronizedStreamsAttributes:multiCamEnabled:midFrameSynchronizationEnabled:superWideAsMidFrameSynchronizationPrimary:secureFaceIDEnabled:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:deviceClientPriority:error:
+ _objc_msgSend$initWithCaptureDevice:maxLossyCompressionLevel:semanticStyleRenderingEnabled:cinematicVideoEnabled:computeFocusDisparity:smartStyleRenderingEnabled:portraitPreviewForegroundBlurEnabled:depthFilterRenderingIsAfterPreviewStitcher:metalCommandQueue:priority:mirroredForMetadataAdjustment:rotationDegreesForMetadataAdjustment:sourceStillImageOutputPortTypes:squareAspectRatioConfigEnabled:cropDepthToPrimaryCaptureAspectRatio:disableDepthAndSegmentationRotationInLandscape:
+ _objc_msgSend$initWithCaptureDevice:tuningParameters:inferenceScheduler:frameRate:prepareCinematographyOnInit:
+ _objc_msgSend$initWithCaptureStream:parentDevice:attributes:sensorIDDictionary:synchronizedStreamsGroup:isOmahaVariant:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:error:
+ _objc_msgSend$initWithConfiguration:sourcePreviewOutput:sourceSensorRawPreviewOutput:sourceHueMapPreviewOutput:imageQueueSinkNode:graph:name:inferenceScheduler:captureDevice:previewTapDelegate:zoomPIPOverlayDelegate:personalPhotographerCaptureDelegate:sourceStillImageOutputsByPortType:
+ _objc_msgSend$initWithConfiguration:videoSourceCaptureOutputsByConnectionID:sourceStreamingSensorRawOutput:sourceStreamingHueMapOutput:sourceStreamingSemanticMasksOutput:audioSourceCaptureOutput:audioSourceCinematicAudioCaptureOutput:smartCameraInferenceOutput:detectedObjectBoxedMetadataOutputs:objectDetectionSourceOutput:metadataSourcePipelineOutputs:graph:parentPipeline:inferenceScheduler:captureDevicesByConnectionID:audioSourceDelegate:fileCoordinatorStatusDelegate:irisRequestDelegate:personalPhotographerCaptureDelegate:masterClock:workgroup:videoGreenGhostMitigationEnabled:
+ _objc_msgSend$initWithDelegate:hvsConfig:
+ _objc_msgSend$initWithDepthEnabled:numberOfInputs:syncSlaveForMasterPortTypes:separateDepthComponentsEnabled:preLTMThumbnailEnabled:postColorProcessingThumbnailEnabled:weightSegmentMapEnabled:styledFrameEnabled:lowLightVideoNoiseReductionEnabled:numberOfSecondaryFramesToSkip:sourceNodeSensorRawOutputsEnabled:
+ _objc_msgSend$initWithDepthEnabled:numberOfInputs:syncSlaveForMasterPortTypes:separateDepthComponentsEnabled:preLTMThumbnailEnabledInputs:postColorProcessingThumbnailEnabledInputs:weightSegmentMapEnabledInputs:styledFrameEnabledInputs:lowLightVideoNoiseReductionEnabled:differentInputFormatsSupported:numberOfSlaveFramesToSkip:startEmittingMasterFramesBeforeSlaveStreamStarts:sourceNodeSensorRawOutputsEnabled:
+ _objc_msgSend$initWithEnabledSemanticMaskTypes:detectedObjectsMetadataIdentifiers:subjectAcquiredChangedHandler:
+ _objc_msgSend$initWithFBSDisplayLayoutMonitorCreateFunction:displayType:isV68Device:
+ _objc_msgSend$initWithGroupID:significanceDetectionThreshold:smartFramingSceneMonitorMode:isPet:vipDetectionThreshold:vipDetectionDurationTimeInSeconds:vipDropOffThreshold:vipDropOffDurationTimeInSeconds:motionFilteringWeightDecayRatio:
+ _objc_msgSend$initWithImageDimensions:face:faceObservation:body:isFrontal:
+ _objc_msgSend$initWithImageEmbedding:contextProbabilities:detectedContext:similarityScore:frameScore:
+ _objc_msgSend$initWithMetadataDictionary:
+ _objc_msgSend$initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:autoTrimMethod:vitalityScoringEnabled:captureDeviceHasOverCaptureEnabled:overCaptureEnabled:depthEnabled:videoStabilizationOverscanOverride:sequenceAdjusterEnabled:visMotionMetadataPreloadingMode:frameReconstructionEnabled:subjectRelightingEnabled:intermediateJPEGCompressionQuality:intermediateJPEGCompressionRate:maxLossyCompressionLevel:temporaryMovieDirectoryURL:cameraInfoByPortType:smartStyleRenderingEnabled:smartStyleReversibilityEnabled:smartFramingEnabled:textureStyleRenderingEnabled:irisRequestDelegate:inferenceScheduler:
+ _objc_msgSend$initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:cinematicAudioEnabled:allowLowLatencyWhenPossible:timewarpTargetFramerate:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:
+ _objc_msgSend$initWithOutputs:masksRefinerEnabled:propagateMasks:ispSMGProcessingSession:squareAspectRatioConfigEnabled:hardwareStreamingRenderingEnabled:textureStyleEnabled:subjectRelightingPreviewVersion:
+ _objc_msgSend$initWithPixelBuffer:regionInFullImageCoords:
+ _objc_msgSend$initWithPortType:quadraSubPixelSwitchingParameters:baseZoomFactor:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSecureSigning:ultraHighResolutionSecureSigningNondisruptiveStreamingFormatIndex:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:
+ _objc_msgSend$initWithPortTypes:defaultFNumberByPortType:autoFocusRecommendedPrimaryPortTypeEnabled:
+ _objc_msgSend$initWithPortTypes:forParameters:frameRateSwitchBasedOnMotionDisabled:teleAutoVideoFrameRateAllows24FPS:lowLightVideoNoiseReductionEnabled:
+ _objc_msgSend$initWithRequestedSettings:sampleBuffers:
+ _objc_msgSend$initWithSensorIDDict:stabilizationMethod:stabilizationType:ispProcessingSession:maxSupportedFrameRate:activeMaxFrameRate:gpuPriority:metalSubmissionAndCompletionQueuePriority:motionAttachmentsSource:fillExtendedRowsOfOutputBuffer:overCaptureEnabled:stereoMode:videoStabilizationOverscanOverride:videoStabilizationStrength:zoomSmoothingEnabled:applyFrameCropOffset:motionMetadataPreloadingEnabled:visExecutionMode:livePhotoCleanOutputRect:cameraInfoByPortType:cvisExtendedLookAheadDuration:distortionCorrectionEnabledPortTypes:distortionCompensationEnabledPortTypes:minDistanceForBravoParallaxShift:videoGreenGhostOfflineMetadataEnabled:videoGreenGhostOfflineLightSourceMaskEnabled:lightSourceMaskAndKeypointDescriptorDataEnabled:attachStabilizedOutputCameraTrajectory:systemIsUnderCriticalThermalPressure:textureStyleRenderingEnabled:faceAwareVideoStabilizationEnabled:
+ _objc_msgSend$initWithSmartFramingSceneMonitorMode:suggestedFieldOfView:suggestedFieldOfViewRect:subjectDistanceRange:subjectMotionPerSecond:atLeastOneSubjectGazingForShutterSoundRelaxation:significantSubjectCount:significantSubjectGroupIDs:persistentlySignificantSubjectCount:persistentlySignificantSubjectGroupIDs:
+ _objc_msgSend$initWithTuningDictionary:
+ _objc_msgSend$initWithTuningDictionary:totalGain:
+ _objc_msgSend$initWithTuningParametersByPortType:
+ _objc_msgSend$initWithYUVSampleBuffer:matchingMainSensorRawSampleBuffer:matchingSIFRSensorRawSampleBuffer:imageEmbeddingSampleBuffer:faceQualitySampleBuffer:subtaskGroup:
+ _objc_msgSend$initWithYUVSampleBuffer:rawEV0SampleBuffer:rawSIFRSampleBuffer:inputNetworkOutput:inputFaceObservations:pinnedSubjectsArray:hvsConfig:sessionID:sharpnessResults:cacheYUVPixelBuffer:
+ _objc_msgSend$initWithtype:parameters:
+ _objc_msgSend$initiateManualPersonalPhotographerCapture
+ _objc_msgSend$inputLearningTargetPixelBuffer
+ _objc_msgSend$inputLinearImage
+ _objc_msgSend$inputMasks
+ _objc_msgSend$inputMeteorGainMap
+ _objc_msgSend$inputPersonData
+ _objc_msgSend$inputPingPongImageForRendering
+ _objc_msgSend$inputUnstyledPixelBuffer
+ _objc_msgSend$inputUnstyledThumbnailPixelBuffer
+ _objc_msgSend$insertHueMap:
+ _objc_msgSend$insertSemanticMasks:
+ _objc_msgSend$instanceMaskReferenceKey
+ _objc_msgSend$isAdaptiveFusionSupported
+ _objc_msgSend$isAutoFullFullUltraHighResolutionZeroShutterLagSupported
+ _objc_msgSend$isCinematicVideoMetadataCaptureEnabled
+ _objc_msgSend$isContinuousAutoFocusTrackingSupported
+ _objc_msgSend$isFixedBudgetExhausted
+ _objc_msgSend$isFrontal
+ _objc_msgSend$isLowLightVideoNoiseReductionSupported
+ _objc_msgSend$isManualCapture
+ _objc_msgSend$isMonitoring
+ _objc_msgSend$isOmahaVariant
+ _objc_msgSend$isPauseFrame
+ _objc_msgSend$isPersistentlySignificant
+ _objc_msgSend$isSecureSigningFaceIDSupported
+ _objc_msgSend$isShutterSoundRelaxationEnabledForDisplayRegion
+ _objc_msgSend$isSignificantForApertureControl
+ _objc_msgSend$isStandardPreset
+ _objc_msgSend$isTextureStyleRenderingSupported
+ _objc_msgSend$isTextureStyleSupported
+ _objc_msgSend$isUltraHighResolutionZeroShutterLagSupported
+ _objc_msgSend$isUnsynchronizedPrimary
+ _objc_msgSend$issueSecureSigningClientCertificateOnQueue:completion:
+ _objc_msgSend$laplacianVariance
+ _objc_msgSend$lcbCorrectionEnabledForPortType:sensorIDString:
+ _objc_msgSend$lcbDatabaseByPortType
+ _objc_msgSend$lcbDatabaseManager:didUpdateDatabase:forPortType:
+ _objc_msgSend$lcbMinApertureRatioForDetectionForPortType:sensorIDString:
+ _objc_msgSend$learnedFusionHighResolutionDowngradeNormalizedSNRHysteresisLag
+ _objc_msgSend$learnedFusionHighResolutionDowngradeNormalizedSNRThreshold
+ _objc_msgSend$learnedFusionModeByPortType
+ _objc_msgSend$linearMixForBG:linearMixForSkin:saturation:forStyle:
+ _objc_msgSend$liveReconfigureForRotationDegrees:
+ _objc_msgSend$loadInferenceNetworksForHVS
+ _objc_msgSend$lowCurrentTorchSupported
+ _objc_msgSend$lowLightVideoNoiseReductionEnabled
+ _objc_msgSend$lowLightVideoNoiseReductionLuxThresholds
+ _objc_msgSend$lowLightVideoNoiseReductionParameters
+ _objc_msgSend$magneticInterferenceDetected
+ _objc_msgSend$magneticInterferenceMitigationRequired
+ _objc_msgSend$magneticInterferenceZone
+ _objc_msgSend$matchingMainSensorRawSampleBuffer
+ _objc_msgSend$matchingSIFRSensorRawSampleBuffer
+ _objc_msgSend$maxCount
+ _objc_msgSend$maxDarknessTrigger
+ _objc_msgSend$maxLensAperture
+ _objc_msgSend$metadataFormatVersion
+ _objc_msgSend$metadataRepresentation
+ _objc_msgSend$metadataSinkPipelineWithSessionID:sinkID:
+ _objc_msgSend$metalCommandBuffer
+ _objc_msgSend$minDarknessTrigger
+ _objc_msgSend$minLensAperture
+ _objc_msgSend$moduleSerial
+ _objc_msgSend$motionInPreviewPixels
+ _objc_msgSend$needsIntermediateRenderingBuffer
+ _objc_msgSend$newMutableCopiedRawEV0SampleBuffer
+ _objc_msgSend$newMutableCopiedRawSIFRSampleBuffer
+ _objc_msgSend$nightMode
+ _objc_msgSend$nightModeSharpness
+ _objc_msgSend$normalizePersonInputDataArray:toCropRect:
+ _objc_msgSend$normalizedAngle
+ _objc_msgSend$omahaConstituentDeviceLiveReconfigurationInProgress
+ _objc_msgSend$omahaRenoAngleWithinDropZone
+ _objc_msgSend$omahaRotationOffsetDegreesForPortType:
+ _objc_msgSend$orderedSetWithObjects:
+ _objc_msgSend$originalCameraIntrinsicMatrix
+ _objc_msgSend$originalCameraIntrinsicMatrixReferenceDimensions
+ _objc_msgSend$outputAspectRatioSupported
+ _objc_msgSend$overCaptureGradientPercentInset
+ _objc_msgSend$parametersForPortType:captureMode:captureType:preset:
+ _objc_msgSend$pauseDurationInSec
+ _objc_msgSend$people
+ _objc_msgSend$personInputDataArrayFromDetectedFaces:
+ _objc_msgSend$personalPhotographerCapture
+ _objc_msgSend$personalPhotographerCaptureRate
+ _objc_msgSend$personalPhotographerDelegate
+ _objc_msgSend$personalPhotographerEnabled
+ _objc_msgSend$personalPhotographerSceneMonitoringParametersForPortType:sensorIDString:
+ _objc_msgSend$personalPhotographerVersion
+ _objc_msgSend$pets
+ _objc_msgSend$pipApps
+ _objc_msgSend$pores
+ _objc_msgSend$portTypesWithTextureStyleBaseLookEnabled
+ _objc_msgSend$preset
+ _objc_msgSend$presetNameToPresetValue:
+ _objc_msgSend$previewSinkPipelineForStillImageSinkID:
+ _objc_msgSend$previewStabilizationNode
+ _objc_msgSend$previewStabilizationNode:didApplyPreviewStabilizationShift:forPortType:
+ _objc_msgSend$primaryDisplayRegion
+ _objc_msgSend$processFrame:
+ _objc_msgSend$processStillImageNowWithAssetBundle:
+ _objc_msgSend$processingMode
+ _objc_msgSend$provenanceDNGInfo
+ _objc_msgSend$provenanceDNGSurface
+ _objc_msgSend$provenanceDNGSurfaceSize
+ _objc_msgSend$provideBaselineTextureStyleRenderer
+ _objc_msgSend$provideGlobalTextureStyleRenderer
+ _objc_msgSend$provideGlowTextureStyleRenderer
+ _objc_msgSend$provideSkinTextureStyleRenderer
+ _objc_msgSend$providesCinematicDisparity
+ _objc_msgSend$rawEV0SampleBuffer
+ _objc_msgSend$rawFrameDeliveryEnabled
+ _objc_msgSend$rawSIFRSampleBuffer
+ _objc_msgSend$regionToRender
+ _objc_msgSend$registerFailedCaptureFrame:
+ _objc_msgSend$registerManualCaptureFrame:
+ _objc_msgSend$releaseFaceIDFrameProxyWithIdentifier:
+ _objc_msgSend$removeFrameIdentifier:
+ _objc_msgSend$resetTrajectoryHistory
+ _objc_msgSend$resolvePersonalPhotographerStatusWithSampleBuffer:frameStatisticsByPortType:thermalPressureLevel:peakPowerPressureLevel:subjectDetected:personalPhotographerStatus:
+ _objc_msgSend$saturation
+ _objc_msgSend$secureSigningPhotoCaptureEnabled
+ _objc_msgSend$secureSigningPhotoCaptureSupportEnabled
+ _objc_msgSend$segmentIdx
+ _objc_msgSend$sensorID
+ _objc_msgSend$serviceNondisruptiveSwitchingFormatForZoomFactor:frameStatistics:imageControlMode:stillImageDigitalFlashMode:isStationary:binnedSIFROnSecondaryStreamAllowed:ignoreZoomFactorAndQuadraSubPixelSceneMonitoring:secureSigningMode:ultraHighResolutionZeroShutterLagEnabled:
+ _objc_msgSend$sessionID
+ _objc_msgSend$setActiveExposureSignals:
+ _objc_msgSend$setActiveOmahaConstituentDeviceType:
+ _objc_msgSend$setActiveZeroShutterLagFlavorHighResolutionFlavor:
+ _objc_msgSend$setActualFNumber:
+ _objc_msgSend$setAllowedPTSDeltaFrameIntervalFactor:
+ _objc_msgSend$setApertureControlSceneMonitorEnabled:
+ _objc_msgSend$setApertureDiameter:
+ _objc_msgSend$setAutoExposureLensApertureRateLimit:
+ _objc_msgSend$setAutoFullFullUltraHighResolutionZeroShutterLagEnabled:
+ _objc_msgSend$setAutoFullFullUltraHighResolutionZeroShutterLagEnabledByOmahaConstituentPortType:
+ _objc_msgSend$setAutoSecureSigningPhotoCaptureEnabled:
+ _objc_msgSend$setAutomaticallyIgnoresExposureSignals:
+ _objc_msgSend$setBaselineExposure:
+ _objc_msgSend$setBrightnessValue:
+ _objc_msgSend$setCachingPropertiesWhileSuspended:
+ _objc_msgSend$setCaptureRequestIdentifier:
+ _objc_msgSend$setCaptureSettingsID:
+ _objc_msgSend$setCinematicMetadataMovieRecordingStats:
+ _objc_msgSend$setCinematicVideoDisparityProvider:
+ _objc_msgSend$setCinematicVideoMetadataCaptureEnabled:
+ _objc_msgSend$setCinematicVideoMetadataCaptureEnabledByClient:
+ _objc_msgSend$setCinematicVideoMetadataEnabled:
+ _objc_msgSend$setColorCameraAssistEnabled:
+ _objc_msgSend$setContinuousAutoFocusTrackingChangedDelegate:
+ _objc_msgSend$setDefaults
+ _objc_msgSend$setDegrunge:
+ _objc_msgSend$setDisabled:
+ _objc_msgSend$setDisplayRegion:
+ _objc_msgSend$setDuplicateInfo:
+ _objc_msgSend$setEffectsToRender:
+ _objc_msgSend$setEmitIfAllAttachedMediaDiscarded:
+ _objc_msgSend$setExpectsFrameSkipping:
+ _objc_msgSend$setFaceIDCoexistenceEnabled:
+ _objc_msgSend$setFaceIDConfiguration:
+ _objc_msgSend$setFaceIDEnabled:
+ _objc_msgSend$setFaceId:
+ _objc_msgSend$setFaceImageQualityDetectionEnabled:
+ _objc_msgSend$setFocusModeAutoWithRect:restrictToRect:continuous:smooth:tracking:trackingLensPositionBias:trackingSeedingPoint:rangeRestrictionNear:rangeRestrictionFar:isFocusRectInOverscanSpace:
+ _objc_msgSend$setFocusTrackedObjectOutputEnabled:
+ _objc_msgSend$setFocusTrackedObjectsDeliveryEnabled:
+ _objc_msgSend$setFrameConfigurationByFrameType:
+ _objc_msgSend$setFrameID:
+ _objc_msgSend$setFramePromotionHandler:context:
+ _objc_msgSend$setFrameStatisticsByPortType:
+ _objc_msgSend$setFsincMasksPrewarmedForCurrentEncoding:
+ _objc_msgSend$setFullImageSize:
+ _objc_msgSend$setHalationChroma:
+ _objc_msgSend$setHingeAngle:
+ _objc_msgSend$setIgnoredExposureSignals:
+ _objc_msgSend$setImageStats:
+ _objc_msgSend$setInputExposureSignals:
+ _objc_msgSend$setInputFaceNormalizedRects:
+ _objc_msgSend$setInputLinearImage:
+ _objc_msgSend$setInputLinearImageMetadata:
+ _objc_msgSend$setInputMasks:
+ _objc_msgSend$setInputMeteorGainMap:
+ _objc_msgSend$setInputPersonData:
+ _objc_msgSend$setInputPingPongImageForRendering:
+ _objc_msgSend$setInputSkinMaskPCR:
+ _objc_msgSend$setInputSkinMaskTransform:
+ _objc_msgSend$setInputSkinSmoothingParameters:
+ _objc_msgSend$setInputTextureROI:
+ _objc_msgSend$setInstanceMask:
+ _objc_msgSend$setIsManualCapture:
+ _objc_msgSend$setIsPauseFrame:
+ _objc_msgSend$setIsTextureStyleRenderingSupported:
+ _objc_msgSend$setLCBDetectionCountHistogram:
+ _objc_msgSend$setLaplacianVariance:
+ _objc_msgSend$setLearnedFusionAETablesEnabled:
+ _objc_msgSend$setLinearImageHighKey:
+ _objc_msgSend$setLinearMixForBG:
+ _objc_msgSend$setLinearMixForSkin:
+ _objc_msgSend$setLowLightVideoNoiseReductionEnabled:
+ _objc_msgSend$setMagneticInterferenceDetected:
+ _objc_msgSend$setMagneticInterferenceHandler:
+ _objc_msgSend$setMagneticInterferenceMonitor:
+ _objc_msgSend$setMaxCount:
+ _objc_msgSend$setMaxVATrackingError:
+ _objc_msgSend$setMetadataCollectionSize:
+ _objc_msgSend$setMeteorHeadroom:
+ _objc_msgSend$setMeteorHeadroomMixFactor:
+ _objc_msgSend$setMovieRecordingEndOfDataBehavior:
+ _objc_msgSend$setNondisruptiveSwitchingFormatIndicesByZoomFactorSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorMainAndSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorSIFRNonBinned:nondisruptiveSwitchingFormatIndicesByZoomfactorSecureSigning:ultraHighResolutionSecureSigningNondisruptiveStreamingFormatIndex:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:forPortType:quadraSubPixelSwitchingParameters:
+ _objc_msgSend$setNumberOfLCBsCorrectedOnIRCF:
+ _objc_msgSend$setNumberOfLCBsCorrectedOnLens:
+ _objc_msgSend$setNumberOfLCBsDetected:
+ _objc_msgSend$setNumberOfMagneticInterferenceEventsDetected:
+ _objc_msgSend$setOmahaConstituentDeviceLiveReconfigurationInProgress:
+ _objc_msgSend$setOmahaRenoAngleWithinDropZone:
+ _objc_msgSend$setOriginalPresentationTimestamp:
+ _objc_msgSend$setOutputImage:
+ _objc_msgSend$setOutputPersonImageStats:
+ _objc_msgSend$setOverCaptureGradientPercentInset:
+ _objc_msgSend$setPauseDurationInSec:
+ _objc_msgSend$setPersonalPhotographerCapture:
+ _objc_msgSend$setPersonalPhotographerCaptureRate:
+ _objc_msgSend$setPersonalPhotographerEnabled:
+ _objc_msgSend$setPores:
+ _objc_msgSend$setPortTypesWithTextureStyleBaseLookEnabled:
+ _objc_msgSend$setPreviewStabilizationShift:
+ _objc_msgSend$setPrimaryDisplayRegion:
+ _objc_msgSend$setProvenanceDNGSurface:size:
+ _objc_msgSend$setRawEV0SampleBuffer:
+ _objc_msgSend$setRawFrameDeliveryEnabled:
+ _objc_msgSend$setRawSIFRSampleBuffer:
+ _objc_msgSend$setReason:
+ _objc_msgSend$setRegionToRender:
+ _objc_msgSend$setRequestedFNumber:
+ _objc_msgSend$setResourceValue:forKey:error:
+ _objc_msgSend$setSaturation:
+ _objc_msgSend$setSaturationFromSmartStyle:
+ _objc_msgSend$setSbufPresentationTimestamp:
+ _objc_msgSend$setSecureSigningPhotoCaptureEnabled:
+ _objc_msgSend$setSecureSigningPhotoCaptureSupportEnabled:
+ _objc_msgSend$setSecureStreamingForFaceIDEnabled:
+ _objc_msgSend$setSeed:
+ _objc_msgSend$setSegmentIdx:
+ _objc_msgSend$setShouldFlushCVMTLCachesOnResetState:
+ _objc_msgSend$setShutterSoundRelaxationEnabledForDisplayRegion:
+ _objc_msgSend$setSkipRendering:
+ _objc_msgSend$setStatistics:
+ _objc_msgSend$setStdVATrackingError:
+ _objc_msgSend$setStillImageCaptureMetadata:
+ _objc_msgSend$setStreamingMode:
+ _objc_msgSend$setStylusDataReceivedDuringSession:
+ _objc_msgSend$setTextureStyle:
+ _objc_msgSend$setTextureStyleBaseLookEnabled:
+ _objc_msgSend$setTextureStyleCreativeEffectsEnabled:
+ _objc_msgSend$setTextureStyleEnabled:
+ _objc_msgSend$setTextureStyleFSINCMasksRequired:
+ _objc_msgSend$setTextureStyleGrain:
+ _objc_msgSend$setTextureStyleIntensity:
+ _objc_msgSend$setTextureStylePreset:
+ _objc_msgSend$setTextureStyleRenderingEnabled:
+ _objc_msgSend$setTextureStyleRenderingSupported:
+ _objc_msgSend$setTextureStyleRenderingVersion:
+ _objc_msgSend$setTimewarpDestinationFrameRate:
+ _objc_msgSend$setTimewarpEnabled:
+ _objc_msgSend$setTimewarpMode:
+ _objc_msgSend$setUltraHighResolutionZeroShutterLagSupportEnabledByOmahaConstituentPortType:
+ _objc_msgSend$setUseRawCinematography:
+ _objc_msgSend$setUseStatistics:
+ _objc_msgSend$setVariableApertureTemperature:
+ _objc_msgSend$setZeroShutterLagEnabledByOmahaConstituentPortType:
+ _objc_msgSend$setZeroShutterLagTimeMachineBufferCapacityByOmahaConstituentPortType:
+ _objc_msgSend$setZoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSecureSigning:ultraHighResolutionSecureSigningNondisruptiveStreamingFormatIndex:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:quadraSubPixelSwitchingParameters:
+ _objc_msgSend$sharedManager
+ _objc_msgSend$sharpnessResults
+ _objc_msgSend$sifrRawCaptureID
+ _objc_msgSend$similarityScore
+ _objc_msgSend$smartStyleCompressorNodesByAttachedMediaKey
+ _objc_msgSend$sortPersonInputDataArrayByFaceSize:maxCount:
+ _objc_msgSend$startFaceIDUnwrap
+ _objc_msgSend$startLiveExtensionSourceNodes
+ _objc_msgSend$startMonitoring
+ _objc_msgSend$startMonitoringWithZone:
+ _objc_msgSend$startPersonalPhotographerSessionWithSettings:stillImageCoordinator:
+ _objc_msgSend$stationaryStatus
+ _objc_msgSend$stopLiveExtensionSourceNodes
+ _objc_msgSend$stopMonitoring
+ _objc_msgSend$stopPersonalPhotographerSession
+ _objc_msgSend$styleWithPreset:intensity:grain:
+ _objc_msgSend$stylusDataReceivedDuringSession
+ _objc_msgSend$subjectMotionPerSecondWithError:
+ _objc_msgSend$supportedExposureSignals
+ _objc_msgSend$textureStyle
+ _objc_msgSend$textureStyleBaseLookEnabled
+ _objc_msgSend$textureStyleCreativeEffectsEnabled
+ _objc_msgSend$textureStyleEnabled
+ _objc_msgSend$textureStyleFSINCMasksRequired
+ _objc_msgSend$textureStyleRenderingEnabled
+ _objc_msgSend$textureStyleRenderingVersion
+ _objc_msgSend$timewarpDestinationFrameRate
+ _objc_msgSend$timewarpEnabled
+ _objc_msgSend$timewarpMode
+ _objc_msgSend$tnrMachineLearningImageRegistrationSupported
+ _objc_msgSend$tuningDictionary:withFilmGrainFromTuning:
+ _objc_msgSend$typicalBufferingInSeconds
+ _objc_msgSend$typicalCaptureLatencyInSeconds
+ _objc_msgSend$ultraHighResolutionZeroShutterLagSupportEnabledByOmahaConstituentPortType
+ _objc_msgSend$unifiedEmbeddingsOutput
+ _objc_msgSend$unstyledImageRequiredForReversibility:
+ _objc_msgSend$updateFaceCaptureQuality:
+ _objc_msgSend$updateHVSDetectionInfo:forChangedKeys:
+ _objc_msgSend$updatePersonalPhotographerOrientationDegrees:mirrored:
+ _objc_msgSend$updateRampTargetZoomFactor:
+ _objc_msgSend$updateStatesUsingDetectedObjects:currentPTS:trackedSubjectsByGroupIDOut:pixelBufferSize:nondisruptiveSwitchingFormatZoomFactor:
+ _objc_msgSend$updateStatesUsingTrackedRect:trackedRectSize:gazeProbabilitiesData:largestFaceSize:totalDetectedFaceCount:currentPTS:distance:pixelBufferSize:vipConfidence:unscaledTrackedRect:
+ _objc_msgSend$value:withObjCType:
+ _objc_msgSend$waitUntilComplete
+ _objc_msgSend$yuvSampleBuffer
+ _objc_msgSend$zeroShutterLagEnabledByOmahaConstituentPortType
+ _overrideIgnoredExposureSignals:values:.onceToken
+ _sandbox_extension_consume
+ _sandbox_extension_release
+ _srtm_allowedPTSDelta
+ _strerror
+ _vDSP_maxv
+ _vDSP_mmul
+ _vDSP_sve
+ _vDSP_svesq
+ _vDSP_vfill
+ _vDSP_vsadd
+ _xpc_string_create
+ captureSource_ReleaseFaceIDFrameProxyIdentifier
+ fvcd_significantSubjectsTrackingEnabledForPersonalPhotographer.sOnceToken
+ initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:cinematicAudioEnabled:allowLowLatencyWhenPossible:timewarpTargetFramerate:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:.onceToken
+ setup.parseOnceToken
+ sharedManager.onceToken
+ sharedManager.sharedInstance
+ startPersonalPhotographerSessionWithSettings:stillImageCoordinator:.sSessionID
- +[BWMultiCamConfiguration configurationWithUnsynchronizedActiveStreamsPortTypes:synchronizedActiveStreamsGroupsPortTypes:stereoVideoCaptureEnabled:multiCamClientCompositingEnabled:exclusivelyForSecureProcessing:builtInMicrophoneIsRecording:]
- +[FigCaptureCustomExposureConfiguration exposureConfigurationWithExposureDuration:minFrameRate:maxFrameRate:ISO:useSpotMetering:requestID:]
- -[BWFigVideoCaptureDevice _initWithCaptureDevice:attributes:synchronizedStreamsAttributes:unsynchronizedStreamsAttributes:multiCamEnabled:midFrameSynchronizationEnabled:superWideAsMidFrameSynchronizationPrimary:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:deviceVendor:createAutofocusSampleBufferProcessorFunction:cameraParameters:deviceClientPriority:error:]
- -[BWFigVideoCaptureDevice _ubHighResolutionNondisruptiveSwitchingFormatIndexForCaptureStream:]
- -[BWFigVideoCaptureDevice initWithCaptureDevice:attributes:synchronizedStreamsAttributes:unsynchronizedStreamsAttributes:multiCamEnabled:midFrameSynchronizationEnabled:superWideAsMidFrameSynchronizationPrimary:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:deviceClientPriority:error:]
- -[BWFigVideoCaptureDevice setFocusModeAutoWithRect:restrictToRect:continuous:smooth:rangeRestrictionNear:rangeRestrictionFar:isFocusRectInOverscanSpace:]
- -[BWFigVideoCaptureDevice setNondisruptiveSwitchingFormatIndicesByZoomFactorSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorMainAndSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:forPortType:quadraSubPixelSwitchingParameters:]
- -[BWFigVideoCaptureStream _setActiveNondisruptiveSwitchingFormatIndex:]
- -[BWFigVideoCaptureStream _setActiveNondisruptiveSwitchingFormatIndex:maximumAllowedFrameRate:minimumFrameRate:maximumFrameRate:]
- -[BWFigVideoCaptureStream initWithCaptureStream:parentDevice:attributes:sensorIDDictionary:synchronizedStreamsGroup:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:error:]
- -[BWFigVideoCaptureStream lensFNumber]
- -[BWFigVideoCaptureStream serviceNondisruptiveSwitchingFormatForZoomFactor:frameStatistics:imageControlMode:stillImageDigitalFlashMode:isStationary:binnedSIFROnSecondaryStreamAllowed:ignoreZoomFactorAndQuadraSubPixelSceneMonitoring:ultraHighResolutionZeroShutterLagEnabled:]
- -[BWFigVideoCaptureStream setZoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:quadraSubPixelSwitchingParameters:]
- -[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:cinematicAudioEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:]
- -[BWFrameStatistics initWthPortType:storage:]
- -[BWFrameStatisticsByPortType initWithPortTypes:autoFocusRecommendedPrimaryPortTypeEnabled:]
- -[BWIrisStagingNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:autoTrimMethod:vitalityScoringEnabled:captureDeviceHasOverCaptureEnabled:overCaptureEnabled:depthEnabled:videoStabilizationOverscanOverride:sequenceAdjusterEnabled:visMotionMetadataPreloadingMode:frameReconstructionEnabled:subjectRelightingEnabled:intermediateJPEGCompressionQuality:intermediateJPEGCompressionRate:maxLossyCompressionLevel:temporaryMovieDirectoryURL:cameraInfoByPortType:smartStyleRenderingEnabled:smartStyleReversibilityEnabled:smartFramingEnabled:irisRequestDelegate:inferenceScheduler:]
- -[BWMultiCamConfiguration _initWithUnsynchronizedActiveStreamsPortTypes:synchronizedActiveStreamsGroupsPortTypes:withCaptureDevice:readCurrentStateFromCaptureDevice:stereoVideoCaptureEnabled:multiCamClientCompositingEnabled:exclusivelyForSecureProcessing:builtInMicrophoneIsRecording:]
- -[BWMultiStreamCameraSourceNode _calculateZoomFactorsToNondisruptiveSwitchingFormatIndexMapping:nondisruptiveSwitchingFormatIndicesByZoomfactorMainAndSIFRBinnedOut:nondisruptiveSwitchingFormatIndicesByZoomfactorSIFRNonBinnedOut:ultraHighResolutionNondisruptiveStreamingFormatIndex:]
- -[BWNondisruptiveSwitchingFormatSelector formatIndexForZoomFactor:frameStatistics:imageControlMode:stillImageDigitalFlashMode:isStationary:isSecondaryStream:binnedSIFROnSecondaryStreamAllowed:ignoreZoomFactorAndQuadraSubPixelSceneMonitoring:ultraHighResolutionZeroShutterLagEnabled:]
- -[BWNondisruptiveSwitchingFormatSelector initWithPortType:quadraSubPixelSwitchingParameters:baseZoomFactor:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:]
- -[BWRealtimeCinematographyNode initWithObjectMetadataIdentifiers:cachedSimulatedAperture:captureDevice:tuningParameters:videoDepthConfiguration:smartStyleLearningEnabled:highResolutionInputEnabled:transformCinematographyDetectionsForMovieFileOutput:]
- -[BWSlaveFrameSynchronizerNode initWithDepthEnabled:numberOfInputs:syncSlaveForMasterPortTypes:separateDepthComponentsEnabled:preLTMThumbnailEnabled:postColorProcessingThumbnailEnabled:weightSegmentMapEnabled:styledFrameEnabled:numberOfSecondaryFramesToSkip:sourceNodeSensorRawOutputsEnabled:]
- -[BWSlaveFrameSynchronizerNode initWithDepthEnabled:numberOfInputs:syncSlaveForMasterPortTypes:separateDepthComponentsEnabled:preLTMThumbnailEnabledInputs:postColorProcessingThumbnailEnabledInputs:weightSegmentMapEnabledInputs:styledFrameEnabledInputs:differentInputFormatsSupported:numberOfSlaveFramesToSkip:startEmittingMasterFramesBeforeSlaveStreamStarts:sourceNodeSensorRawOutputsEnabled:]
- -[BWSmartFramingSceneMonitor _resolveOutputWithSampleBuffer:usingFieldsOfView:suggestedFieldOfViewOut:suggestedFieldOfViewRectOut:atLeastOneSubjectGazingForShutterSoundRelaxationOut:]
- -[BWSmartFramingSceneMonitorResult initWithSmartFramingSceneMonitorMode:suggestedFieldOfView:suggestedFieldOfViewRect:atLeastOneSubjectGazingForShutterSoundRelaxation:]
- -[BWSmartStyleLearningNode _asynchronouslyLearnWithContainer:inputUnstyledSampleBuffer:withUnrefinedMasks:portTypeToLearn:synchronizedPortTypeToLearn:withStats:withStatsExtended:styleToLearn:shouldLearn:shouldBypass:]
- -[BWSmartStyleLearningNode initWithOutputs:masksRefinerEnabled:propagateMasks:ispSMGProcessingSession:squareAspectRatioConfigEnabled:hardwareStreamingRenderingEnabled:subjectRelightingPreviewVersion:]
- -[BWStreamingFilterNode initWithCaptureDevice:maxLossyCompressionLevel:semanticStyleRenderingEnabled:cinematicVideoEnabled:smartStyleRenderingEnabled:portraitPreviewForegroundBlurEnabled:depthFilterRenderingIsAfterPreviewStitcher:metalCommandQueue:priority:mirroredForMetadataAdjustment:rotationDegreesForMetadataAdjustment:sourceStillImageOutputPortTypes:squareAspectRatioConfigEnabled:cropDepthToPrimaryCaptureAspectRatio:disableDepthAndSegmentationRotationInLandscape:]
- -[BWStreamingRaytracingSDOFRenderer initWithCaptureDevice:commandQueue:smartStyleRenderingEnabled:squareAspectRatioConfigEnabled:]
- -[BWVISNode initWithSensorIDDict:stabilizationMethod:stabilizationType:ispProcessingSession:maxSupportedFrameRate:activeMaxFrameRate:gpuPriority:metalSubmissionAndCompletionQueuePriority:motionAttachmentsSource:fillExtendedRowsOfOutputBuffer:overCaptureEnabled:stereoMode:videoStabilizationOverscanOverride:videoStabilizationStrength:zoomSmoothingEnabled:applyFrameCropOffset:motionMetadataPreloadingEnabled:visExecutionMode:livePhotoCleanOutputRect:cameraInfoByPortType:cvisExtendedLookAheadDuration:distortionCorrectionEnabledPortTypes:distortionCompensationEnabledPortTypes:minDistanceForBravoParallaxShift:videoGreenGhostOfflineMetadataEnabled:videoGreenGhostOfflineLightSourceMaskEnabled:lightSourceMaskAndKeypointDescriptorDataEnabled:attachStabilizedOutputCameraTrajectory:systemIsUnderCriticalThermalPressure:faceAwareVideoStabilizationEnabled:]
- -[BWVariableFrameRateSelector _loadDefaultsWithPortTypes:forParameters:frameRateSwitchBasedOnMotionDisabled:teleAutoVideoFrameRateAllows24FPS:]
- -[BWVariableFrameRateSelector initWithPortTypes:forParameters:frameRateSwitchBasedOnMotionDisabled:teleAutoVideoFrameRateAllows24FPS:]
- -[FigCaptureCameraSourcePipeline _addOverCaptureSourcePipelineToGraph:upstreamVideoCaptureOutputsBySourceDeviceType:depthType:depthFilterRenderingEnabled:preLTMThumbnailEnabled:postColorProcessingThumbnailEnabled:weightSegmentMapEnabled:styledFrameEnabled:forPreview:maxLossyCompressionLevel:numberOfSecondaryFramesToSkip:sourceNodeSensorRawOutputsEnabled:outErr:]
- -[FigCaptureCustomExposureConfiguration _initWithExposureDuration:minFrameRate:maxFrameRate:ISO:useSpotMetering:requestID:]
- -[FigCaptureMetadataSinkPipeline _buildMetadataSinkPipeline:graph:videoPreviewOutput:offlineVISMotionDataSourceOutput:metadataSourceOutputsByCategory:captureDevice:faceTrackingPipelineStage:clientAuditToken:inferenceScheduler:delegate:]
- -[FigCaptureMetadataSinkPipeline initWithConfiguration:graph:name:videoPreviewOutput:offlineVISMotionDataSourceOutput:metadataSourceOutputsByCategory:captureDevice:faceTrackingPipelineStage:clientAuditToken:inferenceScheduler:delegate:]
- -[FigCaptureMovieFileSinkHeadPipeline _buildMovieFileSinkHeadPipeline:videoSourceCaptureOutputsByConnectionID:sourceStreamingSensorRawOutput:sourceStreamingHueMapOutput:sourceStreamingSemanticMasksOutput:audioSourceCaptureOutput:audioSourceCinematicAudioCaptureOutput:smartCameraInferenceOutput:detectedObjectBoxedMetadataOutputs:objectDetectionSourceOutput:metadataSourcePipelineOutputs:graph:parentPipeline:inferenceScheduler:captureDevicesByConnectionID:audioSourceDelegate:fileCoordinatorStatusDelegate:irisRequestDelegate:masterClock:workgroup:videoGreenGhostMitigationEnabled:]
- -[FigCaptureMovieFileSinkHeadPipeline initWithConfiguration:videoSourceCaptureOutputsByConnectionID:sourceStreamingSensorRawOutput:sourceStreamingHueMapOutput:sourceStreamingSemanticMasksOutput:audioSourceCaptureOutput:audioSourceCinematicAudioCaptureOutput:smartCameraInferenceOutput:detectedObjectBoxedMetadataOutputs:objectDetectionSourceOutput:metadataSourcePipelineOutputs:graph:parentPipeline:inferenceScheduler:captureDevicesByConnectionID:audioSourceDelegate:fileCoordinatorStatusDelegate:irisRequestDelegate:masterClock:workgroup:videoGreenGhostMitigationEnabled:]
- -[FigCaptureMovieFileSinkPipeline initWithConfiguration:videoSourceCaptureOutputsByConnectionID:sourceStreamingSensorRawOutput:sourceStreamingHueMapOutput:sourceStreamingSemanticMasksOutput:audioSourceCaptureOutput:audioSourceCinematicAudioCaptureOutput:smartCameraInferenceOutput:detectedObjectBoxedMetadataOutputs:objectDetectionSourceOutput:metadataSourcePipelineOutputs:graph:name:inferenceScheduler:captureDevicesByConnectionID:audioSourceDelegate:fileCoordinatorStatusDelegate:recordingStatusDelegate:irisRequestDelegate:multiCamClientCompositingCallback:masterClock:delayedCompressorCleanupEnabled:]
- -[FigCapturePreviewSinkPipeline _appendFilteredPreviewPipeline:desiredPipelineStage:desiredStreamingFilterPipelineStage:previewSinkPipelineConfiguration:videoPreviewSinkConnectionConfiguration:graph:inferenceScheduler:captureDevice:focusBlurMapForDepthFiltersEnabled:depthFromMonocularNetworkEnabled:runMonocularDepthInVideoDepthNode:maxLossyCompressionLevel:metalCommandQueue:depthFilterRenderingIsAfterPreviewStitcher:portraitAutoSuggestEnabled:sourceStillImageOutputsByPortType:usePrimaryPreviewSourceAttachedMediaForInference:]
- -[FigCapturePreviewSinkPipeline _buildVideoPreviewSinkPipeline:sourcePreviewOutput:sourceSensorRawPreviewOutput:sourceHueMapPreviewOutput:graph:inferenceScheduler:captureDevice:previewTapDelegate:zoomPIPOverlayDelegate:sourceStillImageOutputsByPortType:]
- -[FigCapturePreviewSinkPipeline initWithConfiguration:sourcePreviewOutput:sourceSensorRawPreviewOutput:sourceHueMapPreviewOutput:imageQueueSinkNode:graph:name:inferenceScheduler:captureDevice:previewTapDelegate:zoomPIPOverlayDelegate:sourceStillImageOutputsByPortType:]
- -[FigCaptureVISPipeline _buildVISPipelineWithUpstreamOutput:graph:parentPipeline:videoCaptureConnectionConfiguration:pipelineStage:sdofPipelineStage:videoStabilizationType:motionAttachmentsSource:fillExtendedRowsOfOutputBuffer:overCaptureEnabled:stereoMode:videoStabilizationOverscanOverride:videoStabilizationStrength:motionMetadataPreloadingEnabled:visExecutionMode:pipelineTraceID:captureDevice:outputDimensions:generatedTransformsOutputDimensionsOverride:P3ToBT2020ConversionEnabled:stabilizeDepthAttachments:outputDepthDimensions:maxLossyCompressionLevel:videoSTFEnabled:videoGreenGhostMitigationEnabled:lightSourceMaskAndKeypointDescriptorDataEnabled:videoGreenGhostOfflineMetadataEnabled:videoGreenGhostOfflineLightSourceMaskEnabled:personSegmentationRenderingEnabled:smartStyleRenderingEnabled:smartStyleReversibilityEnabled:lowResImageUsedByVideoEncoderEnabled:portTypesWithGeometricDistortionCorrectionInVISEnabled:visProcessingSemaphore:]
- -[FigCaptureVISPipeline _newVISNodeWithUpstreamOutput:graph:parentPipeline:videoCaptureConnectionConfiguration:videoStabilizationType:motionAttachmentsSource:fillExtendedRowsOfOutputBuffer:overCaptureEnabled:stereoMode:videoStabilizationOverscanOverride:videoStabilizationStrength:motionMetadataPreloadingEnabled:visExecutionMode:pipelineTraceID:pipelineStage:captureDevice:outputDimensions:generatedTransformsOutputDimensionsOverride:irisVISCleanOutputRectOut:P3ToBT2020ConversionEnabled:stabilizeDepthAttachments:outputDepthDimensions:maxLossyCompressionLevel:videoSTFEnabled:videoGreenGhostMitigationEnabled:lightSourceMaskAndKeypointDescriptorDataEnabled:videoGreenGhostOfflineMetadataEnabled:videoGreenGhostOfflineLightSourceMaskEnabled:personSegmentationRenderingEnabled:smartStyleRenderingEnabled:smartStyleReversibilityEnabled:lowResImageUsedByVideoEncoderEnabled:portTypesWithGeometricDistortionCorrectionInVISEnabled:visProcessingSemaphore:]
- -[FigCaptureVISPipeline initWithUpstreamOutput:graph:name:parentPipeline:videoCaptureConnectionConfiguration:pipelineStage:sdofPipelineStage:videoStabilizationType:motionAttachmentsSource:fillExtendedRowsOfOutputBuffer:overCaptureEnabled:stereoMode:videoStabilizationOverscanOverride:videoStabilizationStrength:motionMetadataPreloadingEnabled:visExecutionMode:pipelineTraceID:captureDevice:outputDimensions:generatedTransformsOutputDimensionsOverride:P3ToBT2020ConversionEnabled:stabilizeDepthAttachments:outputDepthDimensions:maxLossyCompressionLevel:videoSTFEnabled:videoGreenGhostMitigationEnabled:lightSourceMaskAndKeypointDescriptorDataEnabled:videoGreenGhostOfflineMetadataEnabled:videoGreenGhostOfflineLightSourceMaskEnabled:personSegmentationRenderingEnabled:smartStyleRenderingEnabled:smartStyleReversibilityEnabled:lowResImageUsedByVideoEncoderEnabled:portTypesWithGeometricDistortionCorrectionInVISEnabled:visProcessingSemaphore:]
- -[SubjectSelection updateStatesUsingDetectedObjects:currentPTS:trackedSubjectsByGroupIDOut:]
- -[TrackedSubject initWithGroupID:significanceDetectionThreshold:smartFramingSceneMonitorMode:isPet:]
- -[TrackedSubject updateStatesUsingTrackedRect:trackedRectSize:gazeProbabilitiesData:largestFaceSize:totalDetectedFaceCount:currentPTS:unscaledTrackedRect:]
- GCC_except_table104
- GCC_except_table107
- GCC_except_table143
- GCC_except_table180
- GCC_except_table243
- GCC_except_table292
- GCC_except_table337
- GCC_except_table338
- GCC_except_table343
- GCC_except_table349
- GCC_except_table379
- GCC_except_table405
- GCC_except_table407
- GCC_except_table424
- GCC_except_table45
- GCC_except_table456
- GCC_except_table507
- GCC_except_table526
- GCC_except_table53
- GCC_except_table54
- GCC_except_table556
- GCC_except_table558
- GCC_except_table563
- GCC_except_table568
- GCC_except_table58
- GCC_except_table64
- GCC_except_table692
- GCC_except_table81
- GCC_except_table87
- GCC_except_table88
- GCC_except_table97
- OBJC_IVAR_$_BWFigVideoCaptureStream._lensFNumber
- ___183-[BWFigVideoCaptureStream initWithCaptureStream:parentDevice:attributes:sensorIDDictionary:synchronizedStreamsGroup:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:error:]_block_invoke
- ___278-[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:cinematicAudioEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:]_block_invoke
- ___374-[BWFigVideoCaptureDevice _initWithCaptureDevice:attributes:synchronizedStreamsAttributes:unsynchronizedStreamsAttributes:multiCamEnabled:midFrameSynchronizationEnabled:superWideAsMidFrameSynchronizationPrimary:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:deviceVendor:createAutofocusSampleBufferProcessorFunction:cameraParameters:deviceClientPriority:error:]_block_invoke
- ___92-[FigCaptureDisplayLayoutMonitor initWithFBSDisplayLayoutMonitorCreateFunction:displayType:]_block_invoke
- ___92-[SubjectSelection updateStatesUsingDetectedObjects:currentPTS:trackedSubjectsByGroupIDOut:]_block_invoke
- ___block_descriptor_106_e8_32o40o48o56o64o72o80o_e5_v8?0l
- ___block_descriptor_32_e153_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBB^{OpaqueFigCaptureSource}f}8l
- ___block_descriptor_33_e153_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBB^{OpaqueFigCaptureSource}f}8l
- ___block_descriptor_40_e153_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBB^{OpaqueFigCaptureSource}f}8l
- ___block_descriptor_40_e8_32o_e153_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBB^{OpaqueFigCaptureSource}f}8l
- ___block_descriptor_40_e8_32r_e153_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBB^{OpaqueFigCaptureSource}f}8l
- ___block_descriptor_72_e8_32o40r48r_e153_i16?0^{FigCaptureSourceStorage=qi^{__CFString}^{OpaqueFigSimpleMutex}CC{?=[8I]}q^{OpaqueFigCaptureSource}fBiBB^{OpaqueFigCaptureSource}f}8l
- ___copy_helper_block_e8_32o40o48o56o64o72o80o
- ___destroy_helper_block_e8_32o40o48o56o64o72o80o
- _captureSource_updateCachedPropertyAndNotifyWithForceBehavior
- _fvcd_streamingImageIntentToString
- _kFigCapturePortType_RCamera
- _kFigCaptureStreamMetadata_AD
- _kFigCaptureStreamMetadata_ActiveSignals
- _kFigCaptureStreamMetadata_Signals
- _kFigCaptureStreamProperty_RatioBehavior
- _kFigCaptureStream_FSM
- _kFigCaptureStream_FSMC
- _kFigCaptureStream_FSME
- _objc_msgSend$_asynchronouslyLearnWithContainer:inputUnstyledSampleBuffer:withUnrefinedMasks:portTypeToLearn:synchronizedPortTypeToLearn:withStats:withStatsExtended:styleToLearn:shouldLearn:shouldBypass:
- _objc_msgSend$_initWithCaptureDevice:attributes:synchronizedStreamsAttributes:unsynchronizedStreamsAttributes:multiCamEnabled:midFrameSynchronizationEnabled:superWideAsMidFrameSynchronizationPrimary:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:deviceVendor:createAutofocusSampleBufferProcessorFunction:cameraParameters:deviceClientPriority:error:
- _objc_msgSend$_initWithExposureDuration:minFrameRate:maxFrameRate:ISO:useSpotMetering:requestID:
- _objc_msgSend$configurationWithUnsynchronizedActiveStreamsPortTypes:synchronizedActiveStreamsGroupsPortTypes:stereoVideoCaptureEnabled:multiCamClientCompositingEnabled:exclusivelyForSecureProcessing:builtInMicrophoneIsRecording:
- _objc_msgSend$formatIndexForZoomFactor:frameStatistics:imageControlMode:stillImageDigitalFlashMode:isStationary:isSecondaryStream:binnedSIFROnSecondaryStreamAllowed:ignoreZoomFactorAndQuadraSubPixelSceneMonitoring:ultraHighResolutionZeroShutterLagEnabled:
- _objc_msgSend$initWithCaptureDevice:attributes:synchronizedStreamsAttributes:unsynchronizedStreamsAttributes:multiCamEnabled:midFrameSynchronizationEnabled:superWideAsMidFrameSynchronizationPrimary:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:deviceClientPriority:error:
- _objc_msgSend$initWithCaptureDevice:maxLossyCompressionLevel:semanticStyleRenderingEnabled:cinematicVideoEnabled:smartStyleRenderingEnabled:portraitPreviewForegroundBlurEnabled:depthFilterRenderingIsAfterPreviewStitcher:metalCommandQueue:priority:mirroredForMetadataAdjustment:rotationDegreesForMetadataAdjustment:sourceStillImageOutputPortTypes:squareAspectRatioConfigEnabled:cropDepthToPrimaryCaptureAspectRatio:disableDepthAndSegmentationRotationInLandscape:
- _objc_msgSend$initWithCaptureStream:parentDevice:attributes:sensorIDDictionary:synchronizedStreamsGroup:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:error:
- _objc_msgSend$initWithConfiguration:sourcePreviewOutput:sourceSensorRawPreviewOutput:sourceHueMapPreviewOutput:imageQueueSinkNode:graph:name:inferenceScheduler:captureDevice:previewTapDelegate:zoomPIPOverlayDelegate:sourceStillImageOutputsByPortType:
- _objc_msgSend$initWithConfiguration:videoSourceCaptureOutputsByConnectionID:sourceStreamingSensorRawOutput:sourceStreamingHueMapOutput:sourceStreamingSemanticMasksOutput:audioSourceCaptureOutput:audioSourceCinematicAudioCaptureOutput:smartCameraInferenceOutput:detectedObjectBoxedMetadataOutputs:objectDetectionSourceOutput:metadataSourcePipelineOutputs:graph:parentPipeline:inferenceScheduler:captureDevicesByConnectionID:audioSourceDelegate:fileCoordinatorStatusDelegate:irisRequestDelegate:masterClock:workgroup:videoGreenGhostMitigationEnabled:
- _objc_msgSend$initWithDepthEnabled:numberOfInputs:syncSlaveForMasterPortTypes:separateDepthComponentsEnabled:preLTMThumbnailEnabled:postColorProcessingThumbnailEnabled:weightSegmentMapEnabled:styledFrameEnabled:numberOfSecondaryFramesToSkip:sourceNodeSensorRawOutputsEnabled:
- _objc_msgSend$initWithDepthEnabled:numberOfInputs:syncSlaveForMasterPortTypes:separateDepthComponentsEnabled:preLTMThumbnailEnabledInputs:postColorProcessingThumbnailEnabledInputs:weightSegmentMapEnabledInputs:styledFrameEnabledInputs:differentInputFormatsSupported:numberOfSlaveFramesToSkip:startEmittingMasterFramesBeforeSlaveStreamStarts:sourceNodeSensorRawOutputsEnabled:
- _objc_msgSend$initWithGroupID:significanceDetectionThreshold:smartFramingSceneMonitorMode:isPet:
- _objc_msgSend$initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:autoTrimMethod:vitalityScoringEnabled:captureDeviceHasOverCaptureEnabled:overCaptureEnabled:depthEnabled:videoStabilizationOverscanOverride:sequenceAdjusterEnabled:visMotionMetadataPreloadingMode:frameReconstructionEnabled:subjectRelightingEnabled:intermediateJPEGCompressionQuality:intermediateJPEGCompressionRate:maxLossyCompressionLevel:temporaryMovieDirectoryURL:cameraInfoByPortType:smartStyleRenderingEnabled:smartStyleReversibilityEnabled:smartFramingEnabled:irisRequestDelegate:inferenceScheduler:
- _objc_msgSend$initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:cinematicAudioEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:
- _objc_msgSend$initWithOutputs:masksRefinerEnabled:propagateMasks:ispSMGProcessingSession:squareAspectRatioConfigEnabled:hardwareStreamingRenderingEnabled:subjectRelightingPreviewVersion:
- _objc_msgSend$initWithPortType:quadraSubPixelSwitchingParameters:baseZoomFactor:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:
- _objc_msgSend$initWithPortTypes:autoFocusRecommendedPrimaryPortTypeEnabled:
- _objc_msgSend$initWithPortTypes:forParameters:frameRateSwitchBasedOnMotionDisabled:teleAutoVideoFrameRateAllows24FPS:
- _objc_msgSend$initWithSensorIDDict:stabilizationMethod:stabilizationType:ispProcessingSession:maxSupportedFrameRate:activeMaxFrameRate:gpuPriority:metalSubmissionAndCompletionQueuePriority:motionAttachmentsSource:fillExtendedRowsOfOutputBuffer:overCaptureEnabled:stereoMode:videoStabilizationOverscanOverride:videoStabilizationStrength:zoomSmoothingEnabled:applyFrameCropOffset:motionMetadataPreloadingEnabled:visExecutionMode:livePhotoCleanOutputRect:cameraInfoByPortType:cvisExtendedLookAheadDuration:distortionCorrectionEnabledPortTypes:distortionCompensationEnabledPortTypes:minDistanceForBravoParallaxShift:videoGreenGhostOfflineMetadataEnabled:videoGreenGhostOfflineLightSourceMaskEnabled:lightSourceMaskAndKeypointDescriptorDataEnabled:attachStabilizedOutputCameraTrajectory:systemIsUnderCriticalThermalPressure:faceAwareVideoStabilizationEnabled:
- _objc_msgSend$initWithSmartFramingSceneMonitorMode:suggestedFieldOfView:suggestedFieldOfViewRect:atLeastOneSubjectGazingForShutterSoundRelaxation:
- _objc_msgSend$lensFNumber
- _objc_msgSend$serviceNondisruptiveSwitchingFormatForZoomFactor:frameStatistics:imageControlMode:stillImageDigitalFlashMode:isStationary:binnedSIFROnSecondaryStreamAllowed:ignoreZoomFactorAndQuadraSubPixelSceneMonitoring:ultraHighResolutionZeroShutterLagEnabled:
- _objc_msgSend$setFocusModeAutoWithRect:restrictToRect:continuous:smooth:rangeRestrictionNear:rangeRestrictionFar:isFocusRectInOverscanSpace:
- _objc_msgSend$setNondisruptiveSwitchingFormatIndicesByZoomFactorSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorMainAndSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:forPortType:quadraSubPixelSwitchingParameters:
- _objc_msgSend$setZoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:quadraSubPixelSwitchingParameters:
- _objc_msgSend$updateStatesUsingDetectedObjects:currentPTS:trackedSubjectsByGroupIDOut:
- _objc_msgSend$updateStatesUsingTrackedRect:trackedRectSize:gazeProbabilitiesData:largestFaceSize:totalDetectedFaceCount:currentPTS:unscaledTrackedRect:
- cs_cameraSensorOrientationCompensationDegreesCWForAllUnderlyingPortTypesOfCaptureSource
- csu_createVideoCaptureSourceInfoForCaptureDeviceFromModelSpecificPlist
- initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:cinematicAudioEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:.onceToken
CStrings:
+ " %@"
+ " %@:%@"
+ " %@:%d"
+ " (cached)"
+ " OverCaptureGradientPercentInset:%f"
+ " PEP:1"
+ " PrimaryDisplayRegion:%ld"
+ " SecureSigning:1"
+ " TWmode: %d"
+ " [%@:"
+ " adaptiveFusionDowngradeSNRThreshold=%f"
+ "! primaryCaptureDevice.cinematicVideoEnabled"
+ "! sbufIsMarkerBuffer"
+ "%@ %p: ID:%d duration:%@, ISO:%@ aperture:%@, min/max frame rates:%.3f/%.3f, locked:%d (duration:%d ISO:%d aperture:%d)"
+ "%@-%@.plist"
+ "%@.MOV"
+ "%@:%@,"
+ "%@:%d"
+ "%@:InstanceMaskReferenceKey"
+ "%ud"
+ "%{public}@ still capture SIFR frame was already used for another capture: %{public}@, settingsID:%{public}lld, requestedSettings:%{private}@"
+ "%{public}@ still capture is missing HueMap with frame: %{public}@, settingsID:%{public}lld, requestedSettings:%{private}@"
+ "%{public}@ still capture is missing SIFR with frame: %{public}@, settingsID:%{public}lld, requestedSettings:%{private}@"
+ "( ! FigCFEqual( _captureStream.portType, kFigCapturePortType_FrontFacingInfraredCamera ) ) || ( _deviceType == BWCaptureDeviceTypeInfraredMetadataCamera ) || FigCaptureSourceDeviceIsColorAssistedInfraredCamera( _deviceType )"
+ "((Boolean)(CMTimeCompare(sbufPTS, sbufDTS) == 0))"
+ "(High)"
+ "(Low)"
+ "(Medium)"
+ "(New Bugs)"
+ "+[BWTextureStyleTuning unstyledImageRequiredForReversibility:]"
+ ", (SecureSignSupport ON)"
+ ", (personalPhotographer ON)"
+ ", ActiveOmahaConstituentDeviceType %d"
+ ", CVM:1"
+ ", FaceIDCoex:1"
+ ", TWEnabled:1"
+ ", faceID:{"
+ ", textureStyle:%@"
+ ", textureStyleRenderingVersion:%d"
+ ", useSpotMetering: %d"
+ "-[BWBaselineTextureStyleRenderer renderUsingParameters:inputPixelBuffer:inputSampleBuffer:processedPixelBuffer:completionHandler:]"
+ "-[BWFigVideoCaptureDevice _initWithCaptureDevice:attributes:synchronizedStreamsAttributes:unsynchronizedStreamsAttributes:multiCamEnabled:midFrameSynchronizationEnabled:superWideAsMidFrameSynchronizationPrimary:secureFaceIDEnabled:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:deviceVendor:createAutofocusSampleBufferProcessorFunction:cameraParameters:deviceClientPriority:error:]"
+ "-[BWFigVideoCaptureDevice _prepareStreamsForCurrentTimewarpMode]"
+ "-[BWFigVideoCaptureDevice setActiveOmahaConstituentDeviceType:]"
+ "-[BWFigVideoCaptureStream _setActiveNondisruptiveSwitchingFormatIndex:secureSigningMode:maximumAllowedFrameRate:minimumFrameRate:maximumFrameRate:]"
+ "-[BWFigVideoCaptureStream initWithCaptureStream:parentDevice:attributes:sensorIDDictionary:synchronizedStreamsGroup:isOmahaVariant:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:error:]"
+ "-[BWFigVideoCaptureStream initWithCaptureStream:parentDevice:attributes:sensorIDDictionary:synchronizedStreamsGroup:isOmahaVariant:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:error:]_block_invoke"
+ "-[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:cinematicAudioEnabled:allowLowLatencyWhenPossible:timewarpTargetFramerate:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:]"
+ "-[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:cinematicAudioEnabled:allowLowLatencyWhenPossible:timewarpTargetFramerate:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:]_block_invoke"
+ "-[BWFileCoordinatorNode renderSampleBuffer:forInput:]"
+ "-[BWGraph startLiveExtensionSourceNodes]"
+ "-[BWGraph stopLiveExtensionSourceNodes]"
+ "-[BWHVSCandidateFrameManager registerFailedCaptureFrame:]"
+ "-[BWHVSScoringNode _finalizeAndCleanupSession]"
+ "-[BWHVSScoringNode _initiatePersonalPhotographerCaptureWithFrame:manualCapture:]"
+ "-[BWHVSScoringNode initiateManualPersonalPhotographerCapture]"
+ "-[BWHVSScoringNode updatePersonalPhotographerOrientationDegrees:mirrored:]"
+ "-[BWLCBDatabaseManager _executeDatabaseStorageWorkAsync:block:]_block_invoke"
+ "-[BWLCBDatabaseManager init]_block_invoke"
+ "-[BWLCBDatabaseManager saveDatabasesIfNeeded]_block_invoke"
+ "-[BWPhotoEncoderController _addProvenanceSensorRawForEncodingScheme:sampleBuffer:]"
+ "-[BWPhotoEncoderController _addTextureStylePersonInstanceMasksForEncodingScheme:sampleBuffer:primaryOutputAspectRatio:settingsID:orientation:parentImageHandle:]"
+ "-[BWQuickTimeMovieFileSinkNode renderSampleBuffer:forInput:]"
+ "-[BWSensorRawTimeMachine _insertSampleBuffer:frameType:]"
+ "-[BWSensorRawTimeMachine dealloc]"
+ "-[BWSkinTextureStyleRenderer renderUsingParameters:inputPixelBuffer:inputSampleBuffer:processedPixelBuffer:completionHandler:]"
+ "-[BWStillImageCoordinatorNode _startCalibrationTimerIfNeeded]"
+ "-[BWStillImageCoordinatorNode _stopCalibrationTimer]"
+ "-[BWTimewarpMetadataNode _emitTimewarpMetadataForSampleBuffer:metadata:time:]"
+ "-[BWTimewarpMetadataNode renderSampleBuffer:forInput:]"
+ "-[BWVISNode initWithSensorIDDict:stabilizationMethod:stabilizationType:ispProcessingSession:maxSupportedFrameRate:activeMaxFrameRate:gpuPriority:metalSubmissionAndCompletionQueuePriority:motionAttachmentsSource:fillExtendedRowsOfOutputBuffer:overCaptureEnabled:stereoMode:videoStabilizationOverscanOverride:videoStabilizationStrength:zoomSmoothingEnabled:applyFrameCropOffset:motionMetadataPreloadingEnabled:visExecutionMode:livePhotoCleanOutputRect:cameraInfoByPortType:cvisExtendedLookAheadDuration:distortionCorrectionEnabledPortTypes:distortionCompensationEnabledPortTypes:minDistanceForBravoParallaxShift:videoGreenGhostOfflineMetadataEnabled:videoGreenGhostOfflineLightSourceMaskEnabled:lightSourceMaskAndKeypointDescriptorDataEnabled:attachStabilizedOutputCameraTrajectory:systemIsUnderCriticalThermalPressure:textureStyleRenderingEnabled:faceAwareVideoStabilizationEnabled:]"
+ "-[FigCaptureAngleMonitor startMonitoring]"
+ "-[FigCaptureAngleMonitor stopMonitoring]"
+ "-[FigCaptureCameraSourcePipeline applyOmahaPrimaryStreamSourceDeviceType:]"
+ "-[FigCaptureDisplayLayoutMonitor initWithFBSDisplayLayoutMonitorCreateFunction:displayType:isV68Device:]"
+ "-[FigCaptureMovieFileSinkHeadPipeline _buildMovieFileSinkHeadPipeline:videoSourceCaptureOutputsByConnectionID:sourceStreamingSensorRawOutput:sourceStreamingHueMapOutput:sourceStreamingSemanticMasksOutput:audioSourceCaptureOutput:audioSourceCinematicAudioCaptureOutput:smartCameraInferenceOutput:detectedObjectBoxedMetadataOutputs:objectDetectionSourceOutput:metadataSourcePipelineOutputs:graph:parentPipeline:inferenceScheduler:captureDevicesByConnectionID:audioSourceDelegate:fileCoordinatorStatusDelegate:irisRequestDelegate:personalPhotographerCaptureDelegate:masterClock:workgroup:videoGreenGhostMitigationEnabled:]"
+ "-[FigCaptureSourceManager _clearDeviceAngleState]"
+ "-[FigCaptureSourceManager _clearOmahaRenoAngleWithinDropZone]"
+ "-[FigCaptureSourceManager _handleMagneticInterferenceChange:]"
+ "-[FigCaptureSourceManager _handleOmahaRenoAngleWithinDropZoneState:]"
+ "-[FigCaptureSourceManager _updateDeviceAngleState]"
+ "-[FigCaptureSourceManager _updateOccludedState]"
+ ". Exposure signals %@"
+ ".lapse.mov"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CameraCapture/CMCapture/Sources/Graph/Nodes/BWHVSScoringNode.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CameraCapture/CMCapture/Sources/Graph/Utilities/BWSensorRawTimeMachine.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CameraCapture/CMCapture/Sources/Graph/Utilities/BWTextureStyleTuning.m"
+ "16:27:22"
+ "1706882"
+ "180"
+ "<%@ %p> maxCount:%d, allowedDeltaFactor:%.2f, skipping:%d"
+ "<%@ %p> name:%@, frameConfigs:%@"
+ "<%@ %p> origPTS:%.6f sbufPTS:%.6f settingsID:%lld"
+ "<%@ %p> timestamp:%.3lf ID:%d yuv:%@ '%@'%@, ev0Raw:\"%@\", sifrRaw:\"%@\", hueMap:%@, frameScore:%f, people:%lu, pets:%lu, context:%@ sceneFlags:%@ frameStats:%d, stillImageCaptureMetadata:%d"
+ "<%p [%.3fs]>"
+ "<<<< BWBaselineTextureStyleRenderer >>>> %s: CMITextureStylesProcessor waitForSchedule failed (%d)"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: For capture stream %{public}@, set TW configuration to %{public}@"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: For capture stream %{public}@, set TW configuration to OFF %{public}@"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: For capture stream %{public}@, set TW recording in progress to false"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: Missing base ISO for Omaha stream %@"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: Set TW recording in progress to false"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: Set TW recording in progress to true"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: Set device ZSL/UHR properties for active Omaha constituent (portType %@) : zeroShutterLagEnabled=%d zeroShutterLagTimeMachineBufferCapacity=%d ultraHighResolutionZeroShutterLagSupportEnabled=%d autoFullFullUltraHighResolutionZeroShutterLagEnabled=%d ultraHighResolutionZeroShutterLagEnabled=%d"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: Time machine frames metadata invalid: Manual exposure is not supported%@"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: Unexpected EV0 count for %{public}@ HDR capture. Expected: %{public}d. Got: %{public}d"
+ "<<<< BWFigVideoCaptureStream >>>> %s: [%@] Nondisruptive switching format set to %@ with ID:%d, previous %d, minFrameRate %d, maxFrameRate %d, maximumAllowedFrameRate %d, isSecondary %d, secureSigningMode %d (%d), format %@"
+ "<<<< BWFileCoordinatorNode >>>> %s: %p: recording state %d, TW says to keep PTS %.4lf (seq:tag:level %@:%@:%@)"
+ "<<<< BWFileCoordinatorNode >>>> %s: Using default TW target framerate of 30FPS"
+ "<<<< BWGraph >>>> %s: <%p> started source node <%p, %@, %{public}@>"
+ "<<<< BWHVSCandidateFrameManager >>>> %s: Failed capture: frame (ID:%{public}d) will not be promoted"
+ "<<<< BWHVSScoringNode >>>> %s: %{public}@ Finalizing Personal Photographer session sessionID:%{public}u, settingsID:%{public}lld, numProcessedFrames:%{public}d"
+ "<<<< BWHVSScoringNode >>>> %s: %{public}@ Initiating a %{public}@ still capture for settingsID:%{public}lld with frame : %{public}@, requestedSettings:%{private}@"
+ "<<<< BWHVSScoringNode >>>> %s: %{public}@ Personal Photographer session finalization complete"
+ "<<<< BWHVSScoringNode >>>> %s: %{public}@ Updated still capture orientation to degrees:%d mirrored:%d (PTS %.3f)"
+ "<<<< BWHVSScoringNode >>>> %s: %{public}@ still capture SIFR frame was already used for another capture: %{public}@, settingsID:%{public}lld, requestedSettings:%{private}@"
+ "<<<< BWHVSScoringNode >>>> %s: %{public}@ still capture is missing HueMap with frame: %{public}@, settingsID:%{public}lld, requestedSettings:%{private}@"
+ "<<<< BWHVSScoringNode >>>> %s: %{public}@ still capture is missing SIFR with frame: %{public}@, settingsID:%{public}lld, requestedSettings:%{private}@"
+ "<<<< BWHVSScoringNode >>>> %s: Failed to initiate %{public}@ still capture with frame: %{public}@, settingsID:%{public}lld, requestedSettings:%{private}@"
+ "<<<< BWHVSScoringNode >>>> %s: Failed to initiate manual still capture, err:%d"
+ "<<<< BWHVSScoringNode >>>> %s: Personal Photographer session had %i unmatched frames due to missing sensor raws"
+ "<<<< BWHVSScoringNode >>>> Fig"
+ "<<<< BWIrisStagingNode >>>> %s: Marking buffer %.3f as cutting buffer because texture style preset doesn't match. lastStaged: %@ current: %@."
+ "<<<< BWLCBDatabaseManager >>>> %s: Error creating folder at %{public}@ : %@.  LCBDatabases will not be saved."
+ "<<<< BWLCBDatabaseManager >>>> %s: Error obtaining sandbox extension: %d %s.  Filesystem access will fail."
+ "<<<< BWLCBDatabaseManager >>>> %s: Error writing LCB database to \"%{public}@\" due to \"%{public}@\"."
+ "<<<< BWMultiStreamCameraSourceNode >>>> %s: [%p] Omaha Live Reconfiguration in Progress to NO"
+ "<<<< BWQuickTimeMovieFileSinkNode >>>> %s: Dropping frame within Omaha Reno Angle Drop Zone. input %lu PTS: {%lld/%d}"
+ "<<<< BWQuickTimeMovieFileSinkNode >>>> %s: TW max decimation level %d, max sequence number %d, number of frames written %d (fast decimation allowed %c)"
+ "<<<< BWRemoteQueueSinkNode >>>> %s: Blackening streaming frame within the Omaha Reno Angle Drop Zone. PTS: {%lld/%d}"
+ "<<<< BWSensorRawTimeMachine >>>> %s: BWSensorRawTimeMachine[%@] failed to insert %@ frame: %@"
+ "<<<< BWSensorRawTimeMachine >>>> %s: [%@] Tearing down sensor raw time machine. Worst-case stored buffer counts: %{public}@"
+ "<<<< BWSkinTextureStyleRenderer >>>> %s: CMITextureStylesProcessor finishProcessing failed (%d)"
+ "<<<< BWStillImageCoordinatorNode >>>> %s: Active Omaha constituent device type has changed from '%{public}@' to '%{public}@' for captureID:%{public}lld with capture device %{public}@ primary capture stream %{public}@"
+ "<<<< BWStillImageCoordinatorNode >>>> %s: SoftISPCal: Started timer with %d seconds interval"
+ "<<<< BWStillImageCoordinatorNode >>>> %s: SoftISPCal: Stopped timer"
+ "<<<< BWStillImageProcessing >>>> %s: %@ %lu texture style person instance masks into %@ for captureID:%lld"
+ "<<<< BWStillImageProcessing >>>> %s: Failed to create Provenance DNG encoder manager -- all Provenance DNG encoding will fail"
+ "<<<< BWStillImageProcessing >>>> %s: SecureSigning: Deferred Provenance DNG dictionary is missing for captureID:%lld"
+ "<<<< BWStillImageProcessing >>>> %s: SecureSigning: Failed to create V2H2 binned Provenance sensor raw (err:%d)"
+ "<<<< BWStillImageProcessing >>>> %s: SecureSigning: No Provenance encoder manager for %@"
+ "<<<< BWStillImageProcessing >>>> %s: SecureSigning: Unexpectedly received Provenance sensor raw for encoding for captureID:%lld"
+ "<<<< BWStillImageProcessing >>>> %s: SecureSigning: V2H2 enabled for captureID:%lld"
+ "<<<< BWStillImageProcessing >>>> %s: instanceMaskSbuf doesn't have metadata"
+ "<<<< BWTextureStyleTuning >>>> %s: No still image settings"
+ "<<<< BWTextureStyleTuning >>>> Fig"
+ "<<<< BWTimewarpMetadataNode >>>> %s: decimation level changed;  last known %d, current frame %d"
+ "<<<< BWTimewarpMetadataNode >>>> %s: stopping with max decimation level of %d"
+ "<<<< BWTimewarpMetadataNode >>>> %s: stopping with max sequecne number of %d"
+ "<<<< BWTimewarpMetadataNode >>>> Fig"
+ "<<<< BWVideoNoiseReductionNode >>>> Fig"
+ "<<<< FigCaptureAngleMonitor >>>> %s: %p startMonitoring"
+ "<<<< FigCaptureAngleMonitor >>>> %s: %p stopMonitoring"
+ "<<<< FigCaptureCameraSourcePipeline >>>> %s: Failed to clear unsynchronized-primary on previous primary source (err=%d)"
+ "<<<< FigCaptureCameraSourcePipeline >>>> %s: Failed to set unsynchronized-primary on new primary source (err=%d)"
+ "<<<< FigCaptureMovieFileSinkPipeline >>>> %s: Increased irisStagingNode.bufferingTime from %.1fs to %.1fs for personal photographer to handle typical HVS capture latency of %.1fs"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ %{public}@ personal photographer session on the delegate (err:%{public}d) for captureID:%{public}lld"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Capturing Face ID Bracket for %@, configuration: %@"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Initiate manual personal photographer capture for %@"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Start personal photographer session for %@, settings: %@"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Stop personal photographer session for %@"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Terminating Live Photo movie recording at %{public}.4f for %{public}@"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Update personal photographer orientation for %@: degrees:%d mirrored:%d"
+ "<<<< FigCaptureSession >>>> %s: Adjusting iris movie rotation degrees from %d to %d for Omaha for settings: %@"
+ "<<<< FigCaptureSession >>>> %s: Adjusting output rotation degrees from %d to %d for Omaha for settings: %@"
+ "<<<< FigCaptureSession >>>> %s: Forced Omaha sensor orientation compensation (when disabled by client) by port type: %@"
+ "<<<< FigCaptureSession >>>> %s: Live Reconfiguring Metadata Sink Pipeline %@ rotation to %d (faceTrackingRotation: %d)"
+ "<<<< FigCaptureSession >>>> %s: Live Reconfiguring Preview Pipeline %@ rotation to %d"
+ "<<<< FigCaptureSession >>>> %s: Live Reconfiguring to %@"
+ "<<<< FigCaptureSession >>>> %s: Not overriding max exposure duration to 1/50th for 4K24 since Camera app supports shutter priority controls"
+ "<<<< FigCaptureSession >>>> %s: Personal Photographer configuration error"
+ "<<<< FigCaptureSession >>>> %s: SecureSigning: Delivering Provenance DNG (surface=%p, size=%d) for captureID:%lld"
+ "<<<< FigCaptureSession >>>> %s: Transposed still image output dimensions to %@ for Omaha Reno 90° rotation"
+ "<<<< FigCaptureSession >>>> %s: Trying to live reconfig for preview display region change, but couldn't find a video preview sink connection configuration. Skipping reconfiguration."
+ "<<<< FigCaptureSession >>>> %s: Trying to live reconfigure for Constituent Omaha Device Type Change, but couldn't find a video connection configuration. Skipping reconfiguration."
+ "<<<< FigCaptureSource >>>> %s: %@ Updating Device Angle %ld"
+ "<<<< FigCaptureSource >>>> %s: %@ Updating Primary Display Region %lu"
+ "<<<< FigCaptureSource >>>> %s: [%p] Omaha Live Reconfiguration in Progress to YES"
+ "<<<< FigCaptureSource >>>> %s: [%p] Updating shutter relaxation enablement for display region: %d"
+ "<<<< FigCaptureSourceBackingsProvider >>>> %s: Failed to find a matching underlying RGB metadata format for deviceType:%d"
+ "<<<< FigCaptureSourceBackingsProvider >>>> %s: Failed to find the underlying format for the RGB metadata format %{public}@ on %{public}@"
+ "<<<< FigCaptureSourceManager >>>> %s: %@ Clearing Device Angle to Unspecified"
+ "<<<< FigCaptureSourceManager >>>> %s: %@ Omaha Reno Angle Within Drop Zone to %s (normalized=%f, displayRegion=%lu)"
+ "<<<< FigCaptureSourceManager >>>> %s: %@ Updating Device Angle to %ld (angleMonitorActive: %d, normalizedAngle: %f)"
+ "<<<< FigCaptureSourceManager >>>> %s: %@ Updating Reno Occluded to %d (angleMonitorActive: %d, normalizedAngle: %f, displayRegion: %ld)"
+ "<<<< FigCaptureSourceManager >>>> %s: Magnetic interference detected: %d"
+ "<<<< FigCaptureSourceManager >>>> %s: [%p] Clearing Omaha Reno Angle Within Drop Zone"
+ "<<<< FigCaptureSourceManager >>>> %s: skip deactivating the host capture source when activating an attached session source"
+ "<<<< FigCaptureUtilities >>>> %s: Error executing container query: %s"
+ "<<<< FigCaptureUtilities >>>> %s: Failed to get container path"
+ "<<<< FigCaptureUtilities >>>> %s: Unable to determine signing identifier for process.  No daemon data container URL will be returned."
+ "<BWHVSFrameAnalysisTask: %p [%.3fs]>"
+ "<exposure limits: duration %g-%g, iso %g-%g, aperture %g-%g (default %g)>"
+ "AEGainEnterThreshold"
+ "AEGainExitThreshold"
+ "AF Position not supported for Omaha variants"
+ "AStuckClose"
+ "AStuckOpen"
+ "AVGQ5SQS4OCN7HMWDEDJYD553WNPTI"
+ "AVGQG37DCWSL47LUT3OXNYCVIFJC5M"
+ "AVMetadataObjectTypeCinematicVideoMetadata"
+ "AVMetadataObjectTypeFaceID"
+ "AVMetadataObjectTypeFocusTrackedObject"
+ "ActiveExposureSignals"
+ "ActiveExposureSignalsChanged"
+ "Adaptive Fusion Downgrade - Scene ( Normalized QSum SNR )"
+ "AdaptiveFusion"
+ "AdaptiveFusionDowngrade"
+ "AdaptiveFusionSupported"
+ "ApertureLimitsByPortType"
+ "AttachedInfraredSourceEnabled"
+ "Aug  8 2026"
+ "Auto"
+ "AutoExposureLensApertureRateLimit"
+ "AutoFullFullUltraHighResolutionZeroShutterLagEnabled"
+ "AutoFullFullUltraHighResolutionZeroShutterLagSupported"
+ "Automatic"
+ "AutomaticallyIgnoresExposureSignals"
+ "AuxScore"
+ "BWHVSScoringNode.m"
+ "BWSensorRawTimeMachine[%@] failed to insert %@ frame: %@"
+ "BWTextureStyleTuning.m"
+ "BWTimewarpMetadataNode.m"
+ "BWVideoNoiseReductionNode.m"
+ "Baseline Texture Style Renderer"
+ "BaselineTextureStyle"
+ "BlendPreset"
+ "BlendThreshold"
+ "BlowingCandles"
+ "Body"
+ "Boston"
+ "Boston Ultra Wide Camera"
+ "Boston Wide Camera"
+ "Boston+"
+ "BostonSuperWide"
+ "BostonWide"
+ "CMITextureStylesProcessor"
+ "Calibration"
+ "CaptureMode"
+ "CaptureSessionVideoDataSinkProperty_CinematicVideoMetadataCaptureEnabled"
+ "CaptureSession_TextureStyle"
+ "CaptureSettingsID"
+ "CaptureType"
+ "CaptureTypeOverrides"
+ "CapturesToKeep"
+ "CapturesToRemove"
+ "Catch"
+ "Cheer"
+ "CinematicMetadataCaptureSupported"
+ "CinematicMetadataMovieFileRecordingStats"
+ "CinematicVideoWithoutEmbeddedDepthSupported"
+ "Cinematography Object Tracking"
+ "Cinematography Object Tracking Node"
+ "ClientBracket"
+ "CoexistenceWithInfraredSourceEnabled"
+ "ColorAssistedInfraredMetadataCameraSupported"
+ "ColorAssistedSecureFaceIDEnabled"
+ "CompatibilityWithColorAssistedFaceIDEnabled"
+ "Confidence"
+ "ConfigureForUltraHighResolutionZeroShutterLagSupport"
+ "ContextProbabilities"
+ "ContinuousAutoFocusTrackingSubjectAcquiredChanged"
+ "ContinuousAutoFocusTrackingSupported"
+ "ConversionDisabledOnModuleGating"
+ "Could not find the underlying RGB metadata capture source format for source (deviceType:%d)"
+ "CropPenalty"
+ "DF"
+ "DefaultFNumberByPortType"
+ "DetectedContext"
+ "DeviceAngle"
+ "DidFinishPersonalPhotographerSession"
+ "DocumentScan"
+ "EV0RawCaptureID"
+ "EffectOrder"
+ "Embrace"
+ "EnableUDNet"
+ "ExitingMagneticZone"
+ "FSINCInstanceMask"
+ "FSINCSegmentationMask"
+ "FSINCSegmentationMaskEars"
+ "FSINCSegmentationMaskEyebrow"
+ "FSINCSegmentationMaskFace"
+ "FSINCSegmentationMaskGlasses"
+ "FSINCSegmentationMaskHand"
+ "FSINCSegmentationMaskLips"
+ "FSINCSegmentationMaskNose"
+ "FSINCSegmentationMaskOtherSkin"
+ "FSINCSegmentationMaskPerson"
+ "FSINCSegmentationMaskSkin"
+ "FSINCSegmentationMaskTattoo"
+ "FSINCSegmentationMaskTeeth"
+ "FaceID"
+ "FaceIDCoexistenceSupported"
+ "FaceIDCompanionFormat"
+ "FaceIDUnwrapStatus"
+ "FaceIDUnwrapStatusChanged"
+ "FaceLV"
+ "FaceQuality"
+ "Failed to initiate %{public}@ still capture with frame: %{public}@, settingsID:%{public}lld, requestedSettings:%{private}@"
+ "Failed to initiate manual capture on"
+ "Failed to initiate manual still capture, err:%d"
+ "Failed to perform initiate of manual capture on"
+ "Failed to perform start of"
+ "Failed to perform stop"
+ "Failed to start"
+ "Failed to stop"
+ "FigCaptureCopyInternalDaemonDataContainerURL"
+ "FigCaptureMagneticInterferenceMonitorStateMachine"
+ "FigCaptureTextureStyle: _preset is nil, cannot encode"
+ "FigCaptureTextureStyle: preset key missing from XPC encoding"
+ "FileWriterActionTimewarpTimelapseMaxDecimationLevel"
+ "FileWriterActionTimewarpTimelapseMaxSequenceCaptureID"
+ "FilmGrainSeed"
+ "Filmic"
+ "FilterNodeBaselineTexture"
+ "FilterNodeSkinTexture"
+ "Flicker"
+ "FoodInteraction"
+ "FrameHeight"
+ "FrameID"
+ "FrameMetadata"
+ "FrameOrientation"
+ "FramePixelFormat"
+ "FrameScore"
+ "FrameScoring"
+ "FrameStatisticsByPortType"
+ "FrameTracking"
+ "FrameWidth"
+ "FrameWithinOmahaRenoAngleDropZone"
+ "Front Ultra Wide Color Assisted Infrared Metadata Camera"
+ "GiftReveal"
+ "Global Texture Style Renderer"
+ "GlobalGrainSourcePreset"
+ "GlobalTexture"
+ "GlobalTextureStyle"
+ "GlobalTextureStyleIntermediatePixelBuffer"
+ "Glow Texture Style Renderer"
+ "GlowTexture"
+ "GlowTextureStyle"
+ "GlowTextureStyleIntermediatePixelBuffer"
+ "Glowy"
+ "Graph live reconfiguration for preview display region"
+ "GroupID"
+ "GroupPhoto"
+ "H19"
+ "H19 Camera"
+ "HVS-M2MDownscaledYUV"
+ "HVSEmbeddings.plist"
+ "HandConnection"
+ "HandGesture"
+ "HardwareModel"
+ "HueMap input"
+ "IgnoredExposureSignals"
+ "IgnoredExposureSignalsChanged"
+ "ImageEmbedding"
+ "ImageSize"
+ "InMagneticZone"
+ "InstanceMaskReferenceKey"
+ "IsFrontal"
+ "IsManualCapture"
+ "IsPauseFrame"
+ "Jump"
+ "Kick"
+ "KidsPeopleInteraction"
+ "Kiss"
+ "LCB"
+ "LCBDB"
+ "LF"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:8909"
+ "LastShownBuild:BWHVSScoringNode.m:1172"
+ "LastShownBuild:BWHVSScoringNode.m:2777"
+ "LastShownBuild:BWHVSScoringNode.m:2782"
+ "LastShownBuild:BWHVSScoringNode.m:2785"
+ "LastShownBuild:BWHVSScoringNode.m:2854"
+ "LastShownBuild:BWHVSScoringNode.m:3362"
+ "LastShownBuild:BWSensorRawTimeMachine.m:267"
+ "LastShownBuild:BWTextureStyleTuning.m:256"
+ "LastShownBuild:FigCaptureSession.m:28801"
+ "LastShownDate:BWFigVideoCaptureDevice.m:8909"
+ "LastShownDate:BWHVSScoringNode.m:1172"
+ "LastShownDate:BWHVSScoringNode.m:2777"
+ "LastShownDate:BWHVSScoringNode.m:2782"
+ "LastShownDate:BWHVSScoringNode.m:2785"
+ "LastShownDate:BWHVSScoringNode.m:2854"
+ "LastShownDate:BWHVSScoringNode.m:3362"
+ "LastShownDate:BWSensorRawTimeMachine.m:267"
+ "LastShownDate:BWTextureStyleTuning.m:256"
+ "LastShownDate:FigCaptureSession.m:28801"
+ "Laugh"
+ "Learned Fusion high resolution downgrade - Scene ( Normalized SNR )"
+ "LearnedFusion-24MP"
+ "LearnedFusion-48MP"
+ "LearnedFusionEnhancedResolutionSupported"
+ "LearnedFusionHighResolutionDowngrade"
+ "LearnedFusionUltraHighResolutionSupported"
+ "LearnedHRNR"
+ "LearnedNR"
+ "LearningNode-Globaltexture"
+ "LensApertureChanged"
+ "LensApertureCurrentValue"
+ "Library/LCBDatabases"
+ "LinearImageHighKey"
+ "Live reconfiguring BWVideoNoiseReductionNode with changing formats is not supported"
+ "LivePhoto"
+ "Loaded LCB databases:"
+ "LockedDeviceType"
+ "LowCurrentTorchEnabled"
+ "LowCurrentTorchSupported"
+ "LowLightVideoNoiseReductionLuxThresholds"
+ "LowLightVideoNoiseReductionParameters"
+ "LowLightVideoNoiseReductionSupported"
+ "M"
+ "MagneticInterferenceZone"
+ "Manual"
+ "MaskedFrameSharpness"
+ "MaskedLaplacianVariance"
+ "MaxFaceProm"
+ "MaxLensAperture"
+ "MinApertureRatioForDetection"
+ "MinLensAperture"
+ "Missing base ISO for Omaha stream %@"
+ "Mode_TimewarpCapture"
+ "Mode_TimewarpPreview"
+ "Movie File Streaming HueMap Crossover"
+ "Movie File Streaming Sensor Raw Crossover"
+ "Multiple Personal Photographer Delegates: %@"
+ "No frame configuration"
+ "Non-increasing PTS (new:%lf %@ <= last:%lf %@) for %@"
+ "Occluded"
+ "Omaha"
+ "Omaha Ultra Wide Camera"
+ "Omaha Wide Camera"
+ "OmahaConstituentDeviceLiveReconfiguration"
+ "OmahaPrimarySourceDeviceType"
+ "OmahaRenoAngleWithinDropZone"
+ "OmahaSuperWide"
+ "OmahaSuperWideCamera"
+ "OmahaWide"
+ "OmahaWideCamera"
+ "OriginalPresentationTimestamp"
+ "OutOfMagneticZone"
+ "PauseDuration"
+ "PearlSecureSessionError"
+ "People"
+ "PeoplePose"
+ "PercentFramesOnWide"
+ "PercentFramesOnWideInFirstTenSeconds"
+ "PercentFramesOnWideInFirstTwoSeconds"
+ "PersonMaskPNG"
+ "Personal Photographer"
+ "Personal Photographer configuration error"
+ "Personal Photographer session had %i unmatched frames due to missing sensor raws"
+ "PersonalPhotographer"
+ "PersonalPhotographerParameters"
+ "PersonalPhotographerSceneMonitoringParameters"
+ "PersonalPhotographerSubjectDetectionStatus"
+ "PersonalPhotographerSubjectDetectionStatusChanged"
+ "PersonalPhotographerSupported"
+ "PetCandide"
+ "PetCatch"
+ "PetCropPenalty"
+ "PetFaceConfidence"
+ "PetFaceLV"
+ "PetJump"
+ "PetPose"
+ "Pets"
+ "PetsPeopleInteraction"
+ "PreTimewarpPresentationTimestamp"
+ "Preset"
+ "Preview Streaming HueMap Crossover"
+ "Preview Streaming Sensor Raw Crossover"
+ "PreviewPrimaryTargetIsRenoDisplay"
+ "PrimaryConstituentDeviceSwitchingBehaviorLockedWithDeviceSupported"
+ "PrimaryDisplayRegion"
+ "ProvenanceSensorRaw"
+ "QSub"
+ "QSum"
+ "Raw input"
+ "Reaction"
+ "RecommendedLensApertures"
+ "Rect"
+ "Reno"
+ "Reno Front Ultra Wide Metadata Camera"
+ "Reno Ultra Wide Camera"
+ "Reno Wide Camera"
+ "Reno+"
+ "RenoFrontSuperWide"
+ "RenoSuperWide"
+ "RenoSuperWideMetadata"
+ "RenoSuperWideMetadataCamera"
+ "RenoWide"
+ "Rotator/"
+ "SIFRRawCaptureID"
+ "SP"
+ "SPFaux"
+ "Sample buffer is nil"
+ "SbufPresentationTimestamp"
+ "SecureSignedRawImageSurface"
+ "SecureSignedRawImageSurfaceSize"
+ "SecureSignedRawSurface"
+ "SecureSignedRawSurfaceSize"
+ "SecureSigningFaceIDSupported"
+ "SecureSigningFetchStaticProvenanceData"
+ "SecureSigningPhotoCaptureEnabled"
+ "SecureSigningPhotoCaptureSupportEnabled"
+ "SecureSigningPhotoCaptureSupported"
+ "SegmentIndex"
+ "Semantic Masks Converter"
+ "Semantic Masks Fan Out"
+ "Semantic Masks input"
+ "SemanticMasksConverter"
+ "SessionActive"
+ "SillyFace"
+ "SimiliarityScore"
+ "Skin Texture Style Renderer"
+ "SkinTextureStyle"
+ "SkinTextureStyleIntermediatePixelBuffer"
+ "Soft"
+ "Splash"
+ "Starburst"
+ "StarburstDetected"
+ "StillImageCaptureMetadata"
+ "StillImageSceneFlags"
+ "StreamError"
+ "Studio"
+ "SubjectDetected"
+ "SubjectMotion"
+ "SuperWideColorAssistedInfraredMetadata"
+ "SupportedExposureSignals"
+ "TIR"
+ "TNRMachineLearningImageRegistrationSupported"
+ "TextureStyleBaseLookEnabled"
+ "TextureStyleBaseLookSupported"
+ "TextureStyleCameraPassThru"
+ "TextureStyleCreativeEffectsEnabled"
+ "TextureStyleFSINCMasksRequired"
+ "TextureStyleGrain"
+ "TextureStyleInfoMetadata"
+ "TextureStyleIntensity"
+ "TextureStyleParameters"
+ "TextureStylePreset"
+ "TextureStyleRenderingVersion"
+ "TextureStyleSupported"
+ "TextureStylesPostProcessedPeopleData"
+ "Throw"
+ "Time-lapse-Auto-adjust"
+ "Timewarp only works with one video input and no other inputs (%d / %d / %d)"
+ "TimewarpCapture"
+ "TimewarpMetadata"
+ "TimewarpMode"
+ "TimewarpPreview"
+ "TimewarpTimelapseClassicIntermediateFilePath"
+ "Toast"
+ "Tracking"
+ "TrackingLensPositionBias"
+ "TrackingSeedingPoint"
+ "UDNet"
+ "UnifiedEmbeddingNetworkOutput"
+ "Unrecognized underlying device type %d for Omaha variant"
+ "V63"
+ "V64"
+ "V64s"
+ "V67"
+ "V68"
+ "VFR LLVNR Lux"
+ "VFRVideo.llvnr.luxScene"
+ "VideoNoiseReducer"
+ "VideoNoiseReduction"
+ "VideoPassThru"
+ "Wave"
+ "YUV input"
+ "[%@: %@]"
+ "[FaceIDCompanionFormat]"
+ "[cinematicVideoDataSinkSourceIDs countForObject:cinematicVideoDataSinkSourceID] <= 1"
+ "[graph addNode:hueMapCrossover error:&error]"
+ "[graph addNode:sensorRawCrossover error:&error]"
+ "[graph connectOutput:cameraSourcePipeline.hueMapOutputsByPortType[portType] toInput:input pipelineStage:((void *)0)]"
+ "[graph connectOutput:cameraSourcePipeline.sensorRawOutputsByPortType[portType] toInput:input pipelineStage:((void *)0)]"
+ "[graph connectOutput:pipelineConfiguration.cinematicVideoMetadataTrackingOutput toInput:cinematicMetadataNode.input pipelineStage:((void *)0)]"
+ "[graph connectOutput:previousPrivateTextureStyleMetadataOutput toInput:_movieFileSinkNode.inputs[curMovieFileTrackIndex] pipelineStage:tailPipelineConfiguration.movieFilePipelineStage]"
+ "[graph connectOutput:previousPrivateTextureStyleMetadataOutput toInput:backPressureNode.inputs[currentBackPressureIndex] pipelineStage:postCompressionBackPressurePipelineStage]"
+ "[graph connectOutput:previousPrivateTimewarpMetadataOutput toInput:_movieFileSinkNode.inputs[curMovieFileTrackIndex] pipelineStage:tailPipelineConfiguration.movieFilePipelineStage]"
+ "[graph connectOutput:previousVideoForPrivateTextureStyleMetadataOutput toInput:textureStyleInfoMetadata.input pipelineStage:textureStyleInfoMetadataPipelineStage]"
+ "[graph connectOutput:previousVideoOutput toInput:_cinematographyObjectTrackingNode.input pipelineStage:cinematographyObjectTrackingPipelineStage]"
+ "[graph connectOutput:previousVideoOutput toInput:timewarpMetadataNode.input pipelineStage:tailPipelineStage]"
+ "[graph connectOutput:previousVideoOutput toInput:videoNoiseReductionNode.input pipelineStage:pipelineStage]"
+ "[graph connectOutput:primaryCameraSourcePipeline.hueMapOutputsByPortType[portType] toInput:input pipelineStage:((void *)0)]"
+ "[graph connectOutput:primaryCameraSourcePipeline.sensorRawOutputsByPortType[portType] toInput:input pipelineStage:((void *)0)]"
+ "[graph connectOutput:videoCaptureOutput toInput:trackingNode.input pipelineStage:((void *)0)]"
+ "[parentPipeline addNode:_cinematographyObjectTrackingNode error:&error]"
+ "[parentPipeline addNode:textureStyleInfoMetadata error:&error]"
+ "[parentPipeline addNode:timewarpMetadataNode error:&error]"
+ "[parentPipeline addNode:videoNoiseReductionNode error:&error]"
+ "[self addNode:_cinematographyObjectTrackingNode error:&error]"
+ "[super addNode:cinematicMetadataNode error:&error]"
+ "[super addNode:trackingNode error:&error]"
+ "_FigIsCurrentDispatchQueue( _input.connection.pipelineStage.queue )"
+ "_apertureControlSceneMonitorEnabled"
+ "_calibrationTimer"
+ "activeExposureSignals"
+ "activeOmahaConstituentDeviceType"
+ "activeOmahaConstituentDeviceType (%d -> %d)"
+ "adaptivefusion"
+ "age"
+ "aperture-control-cam-gaze"
+ "autoSecureSigningPhotoCaptureEnabled"
+ "automatic"
+ "aux_face_sharpness_weights"
+ "aux_score_stats"
+ "aux_score_weights"
+ "aux_sharpness_weights"
+ "baseGain"
+ "baseLineTextureIntermediatePixelBuffer"
+ "baselineExposure"
+ "body_edge_threshold"
+ "boost_per_context"
+ "bostonsuperwide"
+ "bostonwide"
+ "bracketConfiguration"
+ "break_duplicate_chains"
+ "break_pause_msec"
+ "budget_constraint"
+ "budget_enabled"
+ "bwhvsscoringnode_trace"
+ "bwlcbdatabasemanager_trace"
+ "bwsecuresigningutilitymanager_trace"
+ "bwsensorrawtimemachine_trace"
+ "bwtimewarpmetadatanode_trace"
+ "calibration"
+ "cameraConfiguration.requiredFormat.lowLightVideoNoiseReductionSupported"
+ "cameraSourcePipeline"
+ "cameraTuningParameters"
+ "candidate_max_age_msec"
+ "candidate_max_list_size"
+ "candidate_max_per_context"
+ "candidate_min_proximity_msec"
+ "captureSession_IrisStillImageSinkInitiateManualPersonalPhotographerCapture"
+ "captureSession_IrisStillImageSinkStartPersonalPhotographerSession"
+ "captureSession_IrisStillImageSinkStopPersonalPhotographerSession"
+ "captureSession_IrisStillImageSinkStopPersonalPhotographerSession_block_invoke"
+ "captureSession_IrisStillImageSinkUpdatePersonalPhotographerOrientation"
+ "captureSession_MetadataSinkCaptureFaceIDBracket"
+ "captureSession_fileStartRecording"
+ "captureSession_handlePersonalPhotographerError"
+ "captureSession_liveReconfigureForActiveOmahaConstituentDeviceTypeChange"
+ "captureSession_liveReconfigureForPreviewDisplayRegionChange"
+ "captureSource_setDeviceAngle"
+ "captureSource_setPrimaryDisplayRegion"
+ "captureSource_updateShutterSoundRelaxationEnabledForDisplayRegion"
+ "captureStream"
+ "captureTypeAdaptiveFusion"
+ "captureanglemonitor_trace"
+ "causingFrameID"
+ "checkpoint_folder"
+ "cinematicMetadataConversionDisabledOnModuleGating"
+ "cinematicMetadataPercentFramesOnWide"
+ "cinematicMetadataPercentFramesOnWideInFirstTenSeconds"
+ "cinematicMetadataPercentFramesOnWideInFirstTwoSeconds"
+ "cinematicVideoMetadataCaptureEnabled"
+ "cinematicVideoMetadataCaptureEnabled (%d -> %d)"
+ "cinematicVideoMetadataCaptureEnabledByClient"
+ "cinematicVideoMetadataCaptureEnabledByClient (%d -> %d)"
+ "cinematicVideoMetadataEnabled"
+ "clean_dups"
+ "clearing previous kFigCaptureStreamProperty_ExposureConfiguration failed"
+ "colorSourceRequiredFormat"
+ "com.apple.avfoundation.avcapturedevice.built-in_video:10"
+ "com.apple.avfoundation.avcapturedevice.built-in_video:11"
+ "com.apple.avfoundation.avcapturedevice.built-in_video:12"
+ "com.apple.avfoundation.avcapturedevice.built-in_video:13"
+ "com.apple.avfoundation.avcapturedevice.private.built-in_metadata:4"
+ "com.apple.avfoundation.avcapturedevice.private.built-in_metadata:5"
+ "com.apple.bwsecuresigningutilitymanager"
+ "com.apple.cameracapture.lcbdb-manager.db-update-queue"
+ "com.apple.cameracapture.magneticInterferenceMonitorQueue"
+ "com.apple.cameracapture.provenance"
+ "com.apple.coremedia.bwfigvideocapturedevice.secure-signing"
+ "com.apple.coremedia.capture.moviefile.noisereduction"
+ "com.apple.coremedia.faceIDUnwrapQueue"
+ "com.apple.pencil.pairing.app"
+ "com.apple.photos.captureMode"
+ "config"
+ "context_priorities"
+ "contexts"
+ "count"
+ "crop_penalty_weights"
+ "cs_cameraSensorOrientationCompensationDegreesCWForAllUnderlyingPortTypesOfCaptureSource"
+ "cs_personalPhotographerDelegate"
+ "degrees"
+ "device_sharpness_intercept"
+ "device_sharpness_slope"
+ "displayRegion: %lu"
+ "domain"
+ "duplicate_constraint"
+ "duplicate_max_time_msec"
+ "duplicate_thresholds"
+ "embedding"
+ "faceID"
+ "faceIDCoexistenceEnabled"
+ "faceIDCoexistenceEnabled (%d -> %d)"
+ "faceIDConfiguration"
+ "face_edge_threshold"
+ "face_margin"
+ "face_quality_gate_bonus_range"
+ "face_quality_gate_fq_trust"
+ "face_quality_gate_max_bonus"
+ "face_quality_gate_mlv_high"
+ "face_quality_gate_mlv_low"
+ "face_quality_gate_threshold"
+ "face_sharpness_boost_falloff_rate"
+ "face_sharpness_boost_threshold"
+ "finalCropRectLaplacianVariance"
+ "focusTrackedObject"
+ "fqgate_per_context"
+ "frame"
+ "frameA"
+ "frameB"
+ "frameIdentifier"
+ "frontal_per_context"
+ "global_sharpness_divisor"
+ "global_sharpness_multiplier"
+ "glowOutputThumbnailPixelBuffer"
+ "grain"
+ "grain must be between 0.0 and 1.0"
+ "hash"
+ "hingeAngle"
+ "i16@?0^{FigCaptureSourceStorage=qi@@@@@@@^{__CFString}@^{OpaqueFigSimpleMutex}@CC{?=[8I]}q@@^{OpaqueFigCaptureSource}f@BiBBqBq^{OpaqueFigCaptureSource}@@f}8"
+ "ignoredExposureSignals"
+ "inputExposureSignals"
+ "large_faces"
+ "largeface_per_context"
+ "lcbDetectionCountHist%d"
+ "legacy"
+ "lensApertureNumber"
+ "log10"
+ "lowCurrentTorchSupported"
+ "lowLightVideoNoiseReductionEnabled"
+ "lowLightVideoNoiseReductionEnabled (%d -> %d)"
+ "magneticInterferenceMitigationRequired"
+ "manual"
+ "max"
+ "max_frames_per_20sec"
+ "mdo_cinematicVideoMetadataCaptureEnabled"
+ "mdta/com.apple.quicktime.texturestyle-info"
+ "mdta/com.apple.quicktime.timewarp-decimation-level"
+ "mdta/com.apple.quicktime.timewarp-decimation-tag"
+ "mdta/com.apple.quicktime.timewarp-original-frame-timestamp-in-milliseconds-since-1970"
+ "mdta/com.apple.quicktime.timewarp-sequence-capture-id"
+ "mean"
+ "median"
+ "min_body_area_ratio"
+ "min_budget"
+ "min_context_prob_sum"
+ "min_context_probabilities"
+ "min_face_area_x1e5"
+ "min_logit_threshold"
+ "min_pause_duration_msec"
+ "min_thresholds"
+ "mirrored"
+ "negative_embedding"
+ "network_output_scalar"
+ "newOmahaConstituentDeviceType == kFigCaptureSourceDeviceType_RenoSuperWideCamera || newOmahaConstituentDeviceType == kFigCaptureSourceDeviceType_BostonSuperWideCamera"
+ "numActivePorts <= ( kFigPortIndex_RenoFrontFacingSuperWideCamera + 1 )"
+ "numberOfLCBsCorrectedOnIRCF"
+ "numberOfLCBsCorrectedOnLens"
+ "numberOfLCBsDetected"
+ "numberOfMagneticInterferenceEventsDetected"
+ "omahasuperwide"
+ "omahawide"
+ "overCaptureGradientPercentInset"
+ "overCaptureGradientPercentInset (%g -> %g)"
+ "payloadInfo"
+ "people_pets_filtering"
+ "percent_of_largest_face"
+ "percentage_of_max_score"
+ "personFaceSharpness"
+ "personalPhotographerCapture"
+ "personalPhotographerCaptureRate"
+ "personalPhotographerEnabled"
+ "personalPhotographerEnabled (%d -> %d)"
+ "personalPhotographerVersionNumber"
+ "petBodySharpness"
+ "petFaceSharpness"
+ "pet_crop_penalty_weights"
+ "pixelTransferOutputFormatDescriptionInOut"
+ "pixelTransferSessionInOut"
+ "por2026"
+ "por2026_max_budget"
+ "portTypesWithTextureStyleBaseLookEnabled"
+ "positive_embedding"
+ "preset"
+ "preset:%@ intensity:%.3f grain:%.3f"
+ "primaryConstituentDeviceSwitchingBehaviorLockedWithDeviceSupported"
+ "primaryDisplayRegion"
+ "primaryDisplayRegion (%d -> %d)"
+ "primaryStreamDeviceType == kFigCaptureSourceDeviceType_RenoSuperWideCamera || primaryStreamDeviceType == kFigCaptureSourceDeviceType_BostonSuperWideCamera"
+ "prompts"
+ "q24@?0@\"BWHVSFrame\"8@\"BWHVSFrame\"16"
+ "rawFrameDeliveryEnabled"
+ "rawFrameDeliveryEnabled (%d -> %d)"
+ "reason"
+ "recover_extras"
+ "reno"
+ "reno front ultra wide camera"
+ "renosuperwide"
+ "renosuperwidemetadata"
+ "renowide"
+ "resetting previous kFigCaptureStreamProperty_ExposureConfiguration failed"
+ "rt_bucket_max_age_msec"
+ "sameContext"
+ "save_pause_msec"
+ "sbufCopy"
+ "secureSigningPhotoCaptureSupportEnabled"
+ "secureSigningPhotoCaptureSupportEnabled (%d -> %d)"
+ "self.isOmahaVariant"
+ "semanticHints"
+ "sessionStorage->bwGraph.running"
+ "sharpness_map_cap_range"
+ "sharpness_map_normalize_max"
+ "sharpness_map_sensitivity"
+ "sharpness_map_threshold"
+ "sharpness_target_shorter_dimension"
+ "sim_boost_per_context"
+ "sim_threshold"
+ "similarity"
+ "std"
+ "stillImageSinkPipelineSessionStorage_stillImageOutputDimensionsForSettings"
+ "stylusDataReceivedDuringSession"
+ "superwidecolorassistedinfraredmetadata"
+ "textureStyle"
+ "textureStyleBaseLookEnabled: %d -> %d"
+ "textureStyleCreativeEffectsEnabled: %d -> %d"
+ "textureStyleEnabled"
+ "textureStyleEnabled (%d -> %d)"
+ "textureStyleFSINCMasksRequired: %d -> %d"
+ "textureStyleGrain"
+ "textureStyleIntensity"
+ "textureStylePreset"
+ "textureStyleRenderingVersion: %d -> %d"
+ "timewarpDestinationFrameRate"
+ "timewarpDestinationFrameRate (%g -> %g)"
+ "timewarpEnabled"
+ "timewarpEnabled (%d -> %d)"
+ "timewarpMetadataNode"
+ "timewarpMode"
+ "timewarpMode (%d -> %d)"
+ "timewarpPresentationTimestamp"
+ "tiny_face_ratio"
+ "tiny_face_reference"
+ "tinyface_per_context"
+ "trainingApertureZone0MLAF"
+ "trainingApertureZone0PDAF"
+ "trainingApertureZone1MLAF"
+ "trainingApertureZone1PDAF"
+ "transition_matrix"
+ "tuningParametersByPortType.count > 0"
+ "ub.scene.adaptiveFusionDowngradeSNR"
+ "ub.scene.learnedFusionHighResolutionDowngradeScene"
+ "unknown(%d)"
+ "v16@?0@\"FigCaptureAngleMonitor\"8"
+ "v16@?0@\"FigCaptureMagneticInterferenceMonitor\"8"
+ "v24@?0@8@\"BWHVSFrame\"16"
+ "v28@?0@\"FigCaptureMagneticInterferenceMonitor\"8I16I20i24"
+ "v32@?0^{__SecKey=}8@\"NSArray\"16@\"NSError\"24"
+ "v64s"
+ "vaActualFNumber"
+ "vaApertureDiameter"
+ "vaMaxTrackError"
+ "vaRequestedFNumber"
+ "vaStdTrackError"
+ "variableApertureTemperature"
+ "videoNoiseReduction.sceneMonitor"
+ "videoNoiseReductionNode"
+ "weight"
+ "\xc1"
+ "\xf0\xf01"
+ "\xf0\xf0\xf0\x81"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0A\xf0\xf0q"
- "( ! FigCFEqual( _captureStream.portType, kFigCapturePortType_FrontFacingInfraredCamera ) ) || ( _deviceType == BWCaptureDeviceTypeInfraredMetadataCamera )"
- "-[BWFigVideoCaptureDevice _initWithCaptureDevice:attributes:synchronizedStreamsAttributes:unsynchronizedStreamsAttributes:multiCamEnabled:midFrameSynchronizationEnabled:superWideAsMidFrameSynchronizationPrimary:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:deviceVendor:createAutofocusSampleBufferProcessorFunction:cameraParameters:deviceClientPriority:error:]"
- "-[BWFigVideoCaptureStream _setActiveNondisruptiveSwitchingFormatIndex:maximumAllowedFrameRate:minimumFrameRate:maximumFrameRate:]"
- "-[BWFigVideoCaptureStream initWithCaptureStream:parentDevice:attributes:sensorIDDictionary:synchronizedStreamsGroup:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:error:]"
- "-[BWFigVideoCaptureStream initWithCaptureStream:parentDevice:attributes:sensorIDDictionary:synchronizedStreamsGroup:applicationID:clientAuditToken:tccIdentity:mediaEnvironment:error:]_block_invoke"
- "-[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:cinematicAudioEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:]_block_invoke"
- "-[BWVISNode initWithSensorIDDict:stabilizationMethod:stabilizationType:ispProcessingSession:maxSupportedFrameRate:activeMaxFrameRate:gpuPriority:metalSubmissionAndCompletionQueuePriority:motionAttachmentsSource:fillExtendedRowsOfOutputBuffer:overCaptureEnabled:stereoMode:videoStabilizationOverscanOverride:videoStabilizationStrength:zoomSmoothingEnabled:applyFrameCropOffset:motionMetadataPreloadingEnabled:visExecutionMode:livePhotoCleanOutputRect:cameraInfoByPortType:cvisExtendedLookAheadDuration:distortionCorrectionEnabledPortTypes:distortionCompensationEnabledPortTypes:minDistanceForBravoParallaxShift:videoGreenGhostOfflineMetadataEnabled:videoGreenGhostOfflineLightSourceMaskEnabled:lightSourceMaskAndKeypointDescriptorDataEnabled:attachStabilizedOutputCameraTrajectory:systemIsUnderCriticalThermalPressure:faceAwareVideoStabilizationEnabled:]"
- "-[FigCaptureDisplayLayoutMonitor initWithFBSDisplayLayoutMonitorCreateFunction:displayType:]"
- "-[FigCaptureMovieFileSinkHeadPipeline _buildMovieFileSinkHeadPipeline:videoSourceCaptureOutputsByConnectionID:sourceStreamingSensorRawOutput:sourceStreamingHueMapOutput:sourceStreamingSemanticMasksOutput:audioSourceCaptureOutput:audioSourceCinematicAudioCaptureOutput:smartCameraInferenceOutput:detectedObjectBoxedMetadataOutputs:objectDetectionSourceOutput:metadataSourcePipelineOutputs:graph:parentPipeline:inferenceScheduler:captureDevicesByConnectionID:audioSourceDelegate:fileCoordinatorStatusDelegate:irisRequestDelegate:masterClock:workgroup:videoGreenGhostMitigationEnabled:]"
- "01:17:34"
- "<<<< BWFigVideoCaptureDevice >>>> %s: Time machine frames metadata invalid: Manual exposure is not supported"
- "<<<< BWFigVideoCaptureStream >>>> %s: [%@] Nondisruptive switching format set to %@ with ID:%d, previous %d, minFrameRate %d, maxFrameRate %d, maximumAllowedFrameRate %d, isSecondary %d, format %@"
- "Aug 10 2026"
- "i16@?0^{FigCaptureSourceStorage=qi@@@@@@@^{__CFString}@^{OpaqueFigSimpleMutex}@CC{?=[8I]}q@@^{OpaqueFigCaptureSource}f@BiBB^{OpaqueFigCaptureSource}@@f}8"
- "numActivePorts <= ( kFigPortIndex_BackFacingTimeOfFlightCamera + 1 )"
- "\xf0\xe1"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\x81\xf0\xf0q"
```
