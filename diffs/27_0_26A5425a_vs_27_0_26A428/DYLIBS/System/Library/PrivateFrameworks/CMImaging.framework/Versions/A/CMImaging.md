## CMImaging

> `/System/Library/PrivateFrameworks/CMImaging.framework/Versions/A/CMImaging`

```diff

 764.21.3.0.0
-  __TEXT.__text: 0x19c068
-  __TEXT.__objc_methlist: 0xd1f4
-  __TEXT.__cstring: 0x1551a
-  __TEXT.__const: 0x11c0
-  __TEXT.__oslogstring: 0x4713
-  __TEXT.__gcc_except_tab: 0x11fc
-  __TEXT.__unwind_info: 0x2d60
+  __TEXT.__text: 0x1e23e0
+  __TEXT.__objc_methlist: 0x110f4
+  __TEXT.__cstring: 0x1df10
+  __TEXT.__const: 0x5400
+  __TEXT.__oslogstring: 0x4c3d
+  __TEXT.__gcc_except_tab: 0x149c
+  __TEXT.__dlopen_cstrs: 0x50
+  __TEXT.__unwind_info: 0x3760
   __TEXT.__eh_frame: 0x608
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x470
-  __DATA_CONST.__objc_classlist: 0x5f0
+  __DATA_CONST.__const: 0x13e8
+  __DATA_CONST.__objc_classlist: 0x760
   __DATA_CONST.__objc_catlist: 0x18
-  __DATA_CONST.__objc_protolist: 0x1b0
+  __DATA_CONST.__objc_protolist: 0x1d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x61d0
+  __DATA_CONST.__objc_selrefs: 0x77e0
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0x4b8
-  __DATA_CONST.__objc_arraydata: 0x380
-  __DATA_CONST.__got: 0xbf0
-  __AUTH_CONST.__const: 0xe50
-  __AUTH_CONST.__cfstring: 0x64e0
-  __AUTH_CONST.__objc_const: 0x1f2c0
-  __AUTH_CONST.__objc_intobj: 0xae0
-  __AUTH_CONST.__objc_arrayobj: 0xc0
+  __DATA_CONST.__objc_superrefs: 0x5c0
+  __DATA_CONST.__objc_arraydata: 0x618
+  __DATA_CONST.__got: 0xe18
+  __AUTH_CONST.__const: 0x14e0
+  __AUTH_CONST.__cfstring: 0x8b20
+  __AUTH_CONST.__objc_const: 0x27bc0
+  __AUTH_CONST.__objc_intobj: 0xf00
+  __AUTH_CONST.__objc_arrayobj: 0x138
+  __AUTH_CONST.__objc_floatobj: 0xe0
+  __AUTH_CONST.__objc_doubleobj: 0x1300
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__objc_doubleobj: 0x1130
-  __AUTH_CONST.__auth_got: 0xad8
+  __AUTH_CONST.__auth_got: 0xb38
+  __AUTH.__objc_data: 0xcd0
   __AUTH.__data: 0x8
-  __DATA.__objc_ivar: 0x17b8
-  __DATA.__data: 0x12d88
-  __DATA.__common: 0x100
-  __DATA.__bss: 0x50
-  __DATA_DIRTY.__objc_data: 0x3b60
+  __DATA.__objc_ivar: 0x2008
+  __DATA.__data: 0x12f90
+  __DATA.__common: 0x180
+  __DATA.__bss: 0xc8
+  __DATA_DIRTY.__objc_data: 0x3cf0
   __DATA_DIRTY.__data: 0x8
-  __DATA_DIRTY.__bss: 0x1d8
-  __DATA_DIRTY.__common: 0xe0
+  __DATA_DIRTY.__bss: 0x200
+  __DATA_DIRTY.__common: 0x100
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics

   - /System/Library/PrivateFrameworks/Espresso.framework/Versions/A/Espresso
   - /System/Library/PrivateFrameworks/IOSurfaceAccelerator.framework/Versions/A/IOSurfaceAccelerator
   - /System/Library/PrivateFrameworks/LoggingSupport.framework/Versions/A/LoggingSupport
+  - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 6794
-  Symbols:   10243
-  CStrings:  2866
+  Functions: 8862
+  Symbols:   13333
+  CStrings:  3730
 
Symbols:
+ +[CMILCBDatabase initialize]
+ +[CMILCBDatabase supportsSecureCoding]
+ +[CMILCBEntry generateKeyForPosition:radius:pyramidLevel:lastDetectionGravityVector:lastDetectionTimeStamp:]
+ +[CMILCBEntry generateNewKeyFromConflictingKey:]
+ +[CMILCBEntry initialize]
+ +[CMILCBEntry supportsSecureCoding]
+ +[CMISmartStyleUtilitiesV1 defaultStyleForCastType:smartStyleRenderingVersion:]
+ +[CMISmartStyleUtilitiesV1 defaultStyleForCastType:textureStyleVersion:]
+ +[CMITextureStyle initStandardTextureStyle]
+ +[CMITextureStyle initWithPresetName:intensity:grain:]
+ +[CMITextureStyleTuningLookup _cacheKeyForHardwareModel:portType:captureMode:preset:captureType:]
+ +[CMITextureStyleTuningLookup _interpolateFrom:to:t:]
+ +[CMITextureStyleTuningLookup _loadTuningPlistIfNeeded]
+ +[CMITextureStyleTuningLookup _loadTuningPlist]
+ +[CMITextureStyleTuningLookup _mergeTuningDictionary:forCaptureType:]
+ +[CMITextureStyleTuningLookup _normalizedCaptureTypeForPresetDict:requestedCaptureType:]
+ +[CMITextureStyleTuningLookup blendedTuningFrom:to:intensity:blendThreshold:effectiveIntensityOut:]
+ +[CMITextureStyleTuningLookup defaultTextureStyleForPresetName:]
+ +[CMITextureStyleTuningLookup defaultTextureStyleForSmartStyleCastType:]
+ +[CMITextureStyleTuningLookup initialize]
+ +[CMITextureStyleTuningLookup reloadTuningPlist]
+ +[CMITextureStyleTuningLookup tuningDictionary:withFilmGrainFromTuning:]
+ +[CMITextureStyleTuningLookup tuningDictionaryForHardwareModel:portType:captureMode:preset:captureType:]
+ +[CMITextureStyleTuningLookup tuningDictionaryForMetadata:]
+ +[CMITextureStylesBloom initialize]
+ +[CMITextureStylesDiffusion initialize]
+ +[CMITextureStylesFaceLandmark landmarkFromDictionary:]
+ +[CMITextureStylesFastGaussian calculateGaussianDimsWithWidth:height:radius:nSamples:targetBlurRadius:pWorkWidth:pWorkHeight:pFinalSigma:pKernelRadius:]
+ +[CMITextureStylesFastGaussian calculateGaussianDimsWithWidth:height:sigma:nSamples:targetBlurRadius:pWorkWidth:pWorkHeight:pFinalSigma:pKernelRadius:fastMode:]
+ +[CMITextureStylesFilmGrainProcessorV1 initialize]
+ +[CMITextureStylesFilter calculateIdealRadius:andDownSamplingScale:forImageSize:andTargetFullScaleRadius:]
+ +[CMITextureStylesFilter calculateRadiusForSigma:]
+ +[CMITextureStylesGaussianGuidedFilterV3 calculateGuidedFilterDimsWithFullImageWidth:fullImageHeight:sigma:blurRadius:pMediumResWidth:pMediumResHeight:pLowResWidth:pLowResHeight:pMediumToLow:pMediumSampling:pOutputBlurRadius:]
+ +[CMITextureStylesGlow initialize]
+ +[CMITextureStylesGuidedFilter supportedRadii]
+ +[CMITextureStylesHalation initialize]
+ +[CMITextureStylesMattify dictOfZeroInitializedStats]
+ +[CMITextureStylesMattify initialize]
+ +[CMITextureStylesPersonInputData initialize]
+ +[CMITextureStylesPersonInputData metadataFormatVersion]
+ +[CMITextureStylesPersonInputData personDataFromDictionary:]
+ +[CMITextureStylesPersonInputData personDataFromDictionary:forKeys:]
+ +[CMITextureStylesPersonInputDataUtilities convertUnitOfAngleInPersonInputDataArrayToDegrees:]
+ +[CMITextureStylesPersonInputDataUtilities convertUnitOfAngleInPersonInputDataArrayToRadians:]
+ +[CMITextureStylesPersonInputDataUtilities dictionaryRepresentationsFromFigLivePhotoMetadata:]
+ +[CMITextureStylesPersonInputDataUtilities faceDiagonalRatioForFaceSize:imageSize:]
+ +[CMITextureStylesPersonInputDataUtilities initialize]
+ +[CMITextureStylesPersonInputDataUtilities normalizePersonInputDataArray:toCropRect:]
+ +[CMITextureStylesPersonInputDataUtilities personInputDataArrayFromDetectedFaces:]
+ +[CMITextureStylesPersonInputDataUtilities personInputDataArrayFromDictionaryRepresentations:keys:]
+ +[CMITextureStylesPersonInputDataUtilities personInputDataArrayFromLivePhotoMetadataAndStatsTracks:faceAttitudesMetadataTrack:effectsStatsTrack:effectsToRender:]
+ +[CMITextureStylesPersonInputDataUtilities softFadeGatingForFaceSize:imageSize:lowerBound:upperBound:]
+ +[CMITextureStylesPersonInputDataUtilities sortPersonInputDataArrayByFaceSize:maxCount:]
+ +[CMITextureStylesProcessor APIVersion]
+ +[CMITextureStylesProcessor computeAuxTextureRegionInCropSpaceWithAuxTextureSize:auxCropRect:fullImageSize:]
+ +[CMITextureStylesProcessor computeAuxTextureRegionInCropSpaceWithAuxTextureSize:fullImageSize:]
+ +[CMITextureStylesProcessor computeAuxTextureRegionInCropSpaceWithPixelBuffer:auxCropRect:fullImageSize:]
+ +[CMITextureStylesProcessor computeAuxTextureRegionInCropSpaceWithPixelBuffer:fullImageSize:]
+ +[CMITextureStylesProcessor computeAuxTextureRegionInCropSpaceWithTexture:auxCropRect:fullImageSize:]
+ +[CMITextureStylesProcessor computeAuxTextureRegionInCropSpaceWithTexture:fullImageSize:]
+ +[CMITextureStylesProcessor effectTypeToEffectName:]
+ +[CMITextureStylesProcessor effectTypeToZeroInitializedStats:]
+ +[CMITextureStylesProcessor getRequiredMemorySize]
+ +[CMITextureStylesProcessor initialize]
+ +[CMITextureStylesProcessor presetNameToPresetValue:]
+ +[CMITextureStylesProcessor presetValueToPresetName:]
+ +[CMITextureStylesSkinSmoothStandalone dictOfZeroInitializedStats]
+ +[CMITextureStylesSkinSmoothStandalone initialize]
+ +[CMITextureStylesUnderEyeBrighten dictOfZeroInitializedStats]
+ +[CMITextureStylesUnderEyeBrighten initialize]
+ -[CMILCBDatabase .cxx_destruct]
+ -[CMILCBDatabase addEntries:]
+ -[CMILCBDatabase copyWithZone:]
+ -[CMILCBDatabase count]
+ -[CMILCBDatabase deleteEntries:]
+ -[CMILCBDatabase detectionIteration]
+ -[CMILCBDatabase encodeWithCoder:]
+ -[CMILCBDatabase entriesByKey]
+ -[CMILCBDatabase entries]
+ -[CMILCBDatabase exportLCBsForCaptureStream]
+ -[CMILCBDatabase initForSensorID:moduleSerial:]
+ -[CMILCBDatabase initWithCoder:]
+ -[CMILCBDatabase moduleSerial]
+ -[CMILCBDatabase sensorID]
+ -[CMILCBDatabase updateEntries:]
+ -[CMILCBEntry .cxx_destruct]
+ -[CMILCBEntry apertureRatio]
+ -[CMILCBEntry computeMinMaxCorrectionFeatureValues]
+ -[CMILCBEntry correctionFeatures]
+ -[CMILCBEntry defocusRadius]
+ -[CMILCBEntry detectionCount]
+ -[CMILCBEntry dictionaryRepresentation]
+ -[CMILCBEntry encodeWithCoder:]
+ -[CMILCBEntry focusLensPosition]
+ -[CMILCBEntry initWithCoder:]
+ -[CMILCBEntry initWithEntry:]
+ -[CMILCBEntry initWithKey:position:radius:defocusRadius:particleDistance:apertureRatio:focusLensPosition:oisShift:opticalCenter:detectionCount:relativeToLens:lastDetectionGravityVector:lastDetectionTimeStamp:shouldCorrect:correctionFeatures:]
+ -[CMILCBEntry key]
+ -[CMILCBEntry lastDetectionGravityVector]
+ -[CMILCBEntry lastDetectionTimeStamp]
+ -[CMILCBEntry maxCorrectionFeatureValue]
+ -[CMILCBEntry minCorrectionFeatureValue]
+ -[CMILCBEntry oisShift]
+ -[CMILCBEntry opticalCenter]
+ -[CMILCBEntry particleDistance]
+ -[CMILCBEntry position]
+ -[CMILCBEntry radius]
+ -[CMILCBEntry relativeToLens]
+ -[CMILCBEntry shouldCorrect]
+ -[CMILCBEntry withDifferentKey]
+ -[CMISmartStyleUtilitiesV1 enableDeltaMapDetailEnhancement]
+ -[CMISmartStyleUtilitiesV1 inputSkinMaskPixelBuffer]
+ -[CMISmartStyleUtilitiesV1 setEnableDeltaMapDetailEnhancement:]
+ -[CMISmartStyleUtilitiesV1 setInputSkinMaskPixelBuffer:]
+ -[CMIStyleEngineApplyStyle inputFaceNormalizedRects]
+ -[CMIStyleEngineApplyStyle inputSkinMaskFlipHorizontal]
+ -[CMIStyleEngineApplyStyle inputSkinMaskFlipVertical]
+ -[CMIStyleEngineApplyStyle inputSkinMaskICR]
+ -[CMIStyleEngineApplyStyle inputSkinMaskPCR]
+ -[CMIStyleEngineApplyStyle inputSkinMaskRotationDegrees]
+ -[CMIStyleEngineApplyStyle inputSkinMaskTexture]
+ -[CMIStyleEngineApplyStyle inputSkinSmoothingParameters]
+ -[CMIStyleEngineApplyStyle resetSkinSmoothState]
+ -[CMIStyleEngineApplyStyle setInputFaceNormalizedRects:]
+ -[CMIStyleEngineApplyStyle setInputSkinMaskFlipHorizontal:]
+ -[CMIStyleEngineApplyStyle setInputSkinMaskFlipVertical:]
+ -[CMIStyleEngineApplyStyle setInputSkinMaskICR:]
+ -[CMIStyleEngineApplyStyle setInputSkinMaskPCR:]
+ -[CMIStyleEngineApplyStyle setInputSkinMaskRotationDegrees:]
+ -[CMIStyleEngineApplyStyle setInputSkinMaskTexture:]
+ -[CMIStyleEngineApplyStyle setInputSkinSmoothingParameters:]
+ -[CMIStyleEngineApplyStyle setSkinMaskPurpose:]
+ -[CMIStyleEngineApplyStyle skinMaskPurpose]
+ -[CMIStyleEngineProcessor inputFaceNormalizedRects]
+ -[CMIStyleEngineProcessor inputSkinMaskFlipHorizontal]
+ -[CMIStyleEngineProcessor inputSkinMaskFlipVertical]
+ -[CMIStyleEngineProcessor inputSkinMaskICR]
+ -[CMIStyleEngineProcessor inputSkinMaskPCR]
+ -[CMIStyleEngineProcessor inputSkinMaskRotationDegrees]
+ -[CMIStyleEngineProcessor inputSkinSmoothingParameters]
+ -[CMIStyleEngineProcessor setInputFaceNormalizedRects:]
+ -[CMIStyleEngineProcessor setInputSkinMaskFlipHorizontal:]
+ -[CMIStyleEngineProcessor setInputSkinMaskFlipVertical:]
+ -[CMIStyleEngineProcessor setInputSkinMaskICR:]
+ -[CMIStyleEngineProcessor setInputSkinMaskPCR:]
+ -[CMIStyleEngineProcessor setInputSkinMaskRotationDegrees:]
+ -[CMIStyleEngineProcessor setInputSkinSmoothingParameters:]
+ -[CMIStyleEngineProcessor setSkinMaskPurpose:]
+ -[CMIStyleEngineProcessor skinMaskPurpose]
+ -[CMITSMattifyPerPersonIntermediatesAndStats .cxx_destruct]
+ -[CMITSTextureAndFullImageRegion .cxx_destruct]
+ -[CMITSTextureAndFullImageRegion dealloc]
+ -[CMITSTextureAndFullImageRegion fullImageRegion]
+ -[CMITSTextureAndFullImageRegion setFullImageRegion:]
+ -[CMITSTextureAndFullImageRegion setTexture:]
+ -[CMITSTextureAndFullImageRegion texture]
+ -[CMITSUEBPerPersonData .cxx_destruct]
+ -[CMITextureStyle .cxx_destruct]
+ -[CMITextureStyle debugDescription]
+ -[CMITextureStyle description]
+ -[CMITextureStyle grain]
+ -[CMITextureStyle hash]
+ -[CMITextureStyle intensity]
+ -[CMITextureStyle isEqual:]
+ -[CMITextureStyle preset]
+ -[CMITextureStylesBloom .cxx_destruct]
+ -[CMITextureStylesBloom _compileShaders]
+ -[CMITextureStylesBloom _configureColorConversion:forTexture:isOutput:]
+ -[CMITextureStylesBloom _updateColorManagementForInputOutput:]
+ -[CMITextureStylesBloom _validateInputsAndParameters]
+ -[CMITextureStylesBloom allocator]
+ -[CMITextureStylesBloom calculateStats]
+ -[CMITextureStylesBloom cameraInfoByPortType]
+ -[CMITextureStylesBloom computeMinimumInputRegionInFullImageCoords:]
+ -[CMITextureStylesBloom finishProcessing]
+ -[CMITextureStylesBloom fullImageSize]
+ -[CMITextureStylesBloom initWithOptionalMetalContext:]
+ -[CMITextureStylesBloom inputOutput]
+ -[CMITextureStylesBloom instanceID]
+ -[CMITextureStylesBloom metalCommandQueue]
+ -[CMITextureStylesBloom parameters]
+ -[CMITextureStylesBloom personData]
+ -[CMITextureStylesBloom prepareToProcess:]
+ -[CMITextureStylesBloom prewarm]
+ -[CMITextureStylesBloom process]
+ -[CMITextureStylesBloom purgeResources]
+ -[CMITextureStylesBloom regionToRender]
+ -[CMITextureStylesBloom resetState]
+ -[CMITextureStylesBloom scaleParametersWithIntensity:]
+ -[CMITextureStylesBloom setAllocator:]
+ -[CMITextureStylesBloom setCameraInfoByPortType:]
+ -[CMITextureStylesBloom setFullImageSize:]
+ -[CMITextureStylesBloom setInputOutput:]
+ -[CMITextureStylesBloom setInstanceID:]
+ -[CMITextureStylesBloom setMetalCommandQueue:]
+ -[CMITextureStylesBloom setParameters:]
+ -[CMITextureStylesBloom setPersonData:]
+ -[CMITextureStylesBloom setRegionToRender:]
+ -[CMITextureStylesBloom setTuningParameters:]
+ -[CMITextureStylesBloom setup]
+ -[CMITextureStylesBloom supportsExternalMemoryResource]
+ -[CMITextureStylesBloom supportsInPlaceRendering]
+ -[CMITextureStylesBloom tuningParameters]
+ -[CMITextureStylesBloomIO .cxx_destruct]
+ -[CMITextureStylesBloomIO inputImage]
+ -[CMITextureStylesBloomIO inputSkinMask]
+ -[CMITextureStylesBloomIO outputImage]
+ -[CMITextureStylesBloomIO setInputImage:]
+ -[CMITextureStylesBloomIO setInputSkinMask:]
+ -[CMITextureStylesBloomIO setOutputImage:]
+ -[CMITextureStylesBloomParameters _floatFromDict:key:default:]
+ -[CMITextureStylesBloomParameters brightness]
+ -[CMITextureStylesBloomParameters copyWithZone:]
+ -[CMITextureStylesBloomParameters initWithTuningDictionary:]
+ -[CMITextureStylesBloomParameters init]
+ -[CMITextureStylesBloomParameters inputTextureROI]
+ -[CMITextureStylesBloomParameters lightMapGamma]
+ -[CMITextureStylesBloomParameters lightMapInvert]
+ -[CMITextureStylesBloomParameters setBrightness:]
+ -[CMITextureStylesBloomParameters setDefaults]
+ -[CMITextureStylesBloomParameters setInputTextureROI:]
+ -[CMITextureStylesBloomParameters setLightMapGamma:]
+ -[CMITextureStylesBloomParameters setLightMapInvert:]
+ -[CMITextureStylesBloomParameters setSigmaGlare:]
+ -[CMITextureStylesBloomParameters setSkinMask:]
+ -[CMITextureStylesBloomParameters setStrength:]
+ -[CMITextureStylesBloomParameters sigmaGlare]
+ -[CMITextureStylesBloomParameters skinMask]
+ -[CMITextureStylesBloomParameters strength]
+ -[CMITextureStylesBloomParameters validate]
+ -[CMITextureStylesDiffusion .cxx_destruct]
+ -[CMITextureStylesDiffusion _applyMeteorToInput:gainMap:gain:mixFactor:outputMixed:commandBuffer:]
+ -[CMITextureStylesDiffusion _calculateBlurSigma:]
+ -[CMITextureStylesDiffusion _calculateFullScaleBlurRadius:]
+ -[CMITextureStylesDiffusion _compileShaders]
+ -[CMITextureStylesDiffusion _configureColorConversion:forTexture:isOutput:]
+ -[CMITextureStylesDiffusion _createIntermediateTextures:inputRegion:blurredSize:]
+ -[CMITextureStylesDiffusion _releaseIntermediateTextures]
+ -[CMITextureStylesDiffusion _renderDiffusionWithInput:blurred:skinMask:personMask:output:diffusionParameters:commandBuffer:]
+ -[CMITextureStylesDiffusion _rescale:toLinearRGB:commandBuffer:]
+ -[CMITextureStylesDiffusion _updateColorManagementForInputTexture:outputTexture:]
+ -[CMITextureStylesDiffusion _validateInputsAndParameters]
+ -[CMITextureStylesDiffusion allocator]
+ -[CMITextureStylesDiffusion calculateStats]
+ -[CMITextureStylesDiffusion cameraInfoByPortType]
+ -[CMITextureStylesDiffusion computeMinimumInputRegionInFullImageCoords:]
+ -[CMITextureStylesDiffusion finishProcessing]
+ -[CMITextureStylesDiffusion fullImageSize]
+ -[CMITextureStylesDiffusion initWithOptionalMetalContext:]
+ -[CMITextureStylesDiffusion inputOutput]
+ -[CMITextureStylesDiffusion instanceID]
+ -[CMITextureStylesDiffusion metalCommandQueue]
+ -[CMITextureStylesDiffusion parameters]
+ -[CMITextureStylesDiffusion personData]
+ -[CMITextureStylesDiffusion prepareToProcess:]
+ -[CMITextureStylesDiffusion prewarm]
+ -[CMITextureStylesDiffusion process]
+ -[CMITextureStylesDiffusion purgeResources]
+ -[CMITextureStylesDiffusion regionToRender]
+ -[CMITextureStylesDiffusion resetState]
+ -[CMITextureStylesDiffusion scaleParametersWithIntensity:]
+ -[CMITextureStylesDiffusion setAllocator:]
+ -[CMITextureStylesDiffusion setCameraInfoByPortType:]
+ -[CMITextureStylesDiffusion setFullImageSize:]
+ -[CMITextureStylesDiffusion setInputOutput:]
+ -[CMITextureStylesDiffusion setInstanceID:]
+ -[CMITextureStylesDiffusion setMetalCommandQueue:]
+ -[CMITextureStylesDiffusion setParameters:]
+ -[CMITextureStylesDiffusion setPersonData:]
+ -[CMITextureStylesDiffusion setRegionToRender:]
+ -[CMITextureStylesDiffusion setTuningParameters:]
+ -[CMITextureStylesDiffusion setup]
+ -[CMITextureStylesDiffusion supportsExternalMemoryResource]
+ -[CMITextureStylesDiffusion supportsInPlaceRendering]
+ -[CMITextureStylesDiffusion tuningParameters]
+ -[CMITextureStylesDiffusionIO .cxx_destruct]
+ -[CMITextureStylesDiffusionIO inputGainMap]
+ -[CMITextureStylesDiffusionIO inputImage]
+ -[CMITextureStylesDiffusionIO inputPersonMask]
+ -[CMITextureStylesDiffusionIO inputSkinMask]
+ -[CMITextureStylesDiffusionIO outputImage]
+ -[CMITextureStylesDiffusionIO setInputGainMap:]
+ -[CMITextureStylesDiffusionIO setInputImage:]
+ -[CMITextureStylesDiffusionIO setInputPersonMask:]
+ -[CMITextureStylesDiffusionIO setInputSkinMask:]
+ -[CMITextureStylesDiffusionIO setOutputImage:]
+ -[CMITextureStylesDiffusionParameters _floatFromDict:key:default:]
+ -[CMITextureStylesDiffusionParameters bg]
+ -[CMITextureStylesDiffusionParameters bw3Gamma]
+ -[CMITextureStylesDiffusionParameters copyWithZone:]
+ -[CMITextureStylesDiffusionParameters difSat]
+ -[CMITextureStylesDiffusionParameters diffuseColor]
+ -[CMITextureStylesDiffusionParameters faceTempering]
+ -[CMITextureStylesDiffusionParameters fogStrength]
+ -[CMITextureStylesDiffusionParameters gaussianBlurSigma]
+ -[CMITextureStylesDiffusionParameters grading]
+ -[CMITextureStylesDiffusionParameters highlight]
+ -[CMITextureStylesDiffusionParameters hueRotate]
+ -[CMITextureStylesDiffusionParameters initWithTuningDictionary:]
+ -[CMITextureStylesDiffusionParameters init]
+ -[CMITextureStylesDiffusionParameters lift]
+ -[CMITextureStylesDiffusionParameters maxRGB]
+ -[CMITextureStylesDiffusionParameters meteorHeadroomMixFactor]
+ -[CMITextureStylesDiffusionParameters meteorHeadroom]
+ -[CMITextureStylesDiffusionParameters naturalResolution]
+ -[CMITextureStylesDiffusionParameters person]
+ -[CMITextureStylesDiffusionParameters saturation]
+ -[CMITextureStylesDiffusionParameters setBg:]
+ -[CMITextureStylesDiffusionParameters setBw3Gamma:]
+ -[CMITextureStylesDiffusionParameters setDefaults]
+ -[CMITextureStylesDiffusionParameters setDifSat:]
+ -[CMITextureStylesDiffusionParameters setDiffuseColor:]
+ -[CMITextureStylesDiffusionParameters setFaceTempering:]
+ -[CMITextureStylesDiffusionParameters setFogStrength:]
+ -[CMITextureStylesDiffusionParameters setGaussianBlurSigma:]
+ -[CMITextureStylesDiffusionParameters setGrading:]
+ -[CMITextureStylesDiffusionParameters setHighlight:]
+ -[CMITextureStylesDiffusionParameters setHueRotate:]
+ -[CMITextureStylesDiffusionParameters setLift:]
+ -[CMITextureStylesDiffusionParameters setMaxRGB:]
+ -[CMITextureStylesDiffusionParameters setMeteorHeadroom:]
+ -[CMITextureStylesDiffusionParameters setMeteorHeadroomMixFactor:]
+ -[CMITextureStylesDiffusionParameters setNaturalResolution:]
+ -[CMITextureStylesDiffusionParameters setPerson:]
+ -[CMITextureStylesDiffusionParameters setSaturation:]
+ -[CMITextureStylesDiffusionParameters setShDarken:]
+ -[CMITextureStylesDiffusionParameters setSlBG:]
+ -[CMITextureStylesDiffusionParameters setSlBright:]
+ -[CMITextureStylesDiffusionParameters setSlDark:]
+ -[CMITextureStylesDiffusionParameters setSlPerson:]
+ -[CMITextureStylesDiffusionParameters setSlSkin:]
+ -[CMITextureStylesDiffusionParameters setSoftLight:]
+ -[CMITextureStylesDiffusionParameters setSpbHL:]
+ -[CMITextureStylesDiffusionParameters setStrength:]
+ -[CMITextureStylesDiffusionParameters shDarken]
+ -[CMITextureStylesDiffusionParameters slBG]
+ -[CMITextureStylesDiffusionParameters slBright]
+ -[CMITextureStylesDiffusionParameters slDark]
+ -[CMITextureStylesDiffusionParameters slPerson]
+ -[CMITextureStylesDiffusionParameters slSkin]
+ -[CMITextureStylesDiffusionParameters softLight]
+ -[CMITextureStylesDiffusionParameters spbHL]
+ -[CMITextureStylesDiffusionParameters strength]
+ -[CMITextureStylesDiffusionParameters validate]
+ -[CMITextureStylesDownSampler .cxx_destruct]
+ -[CMITextureStylesDownSampler _compileShaders]
+ -[CMITextureStylesDownSampler downSampleInput:output:commandBuffer:]
+ -[CMITextureStylesDownSampler downSampleInput:output:encoder:]
+ -[CMITextureStylesDownSampler initWithMetalContext:]
+ -[CMITextureStylesDownSampler rescaleInput:output:commandBuffer:]
+ -[CMITextureStylesDownSampler rescaleInput:output:encoder:]
+ -[CMITextureStylesEffectDescriptor .cxx_destruct]
+ -[CMITextureStylesEffectDescriptor copyWithZone:]
+ -[CMITextureStylesEffectDescriptor description]
+ -[CMITextureStylesEffectDescriptor hash]
+ -[CMITextureStylesEffectDescriptor initWithtype:parameters:]
+ -[CMITextureStylesEffectDescriptor isEqual:]
+ -[CMITextureStylesEffectDescriptor parameters]
+ -[CMITextureStylesEffectDescriptor setSkipRendering:]
+ -[CMITextureStylesEffectDescriptor skipRendering]
+ -[CMITextureStylesEffectDescriptor type]
+ -[CMITextureStylesFaceLandmark copyWithZone:]
+ -[CMITextureStylesFaceLandmark dictionaryRepresentation]
+ -[CMITextureStylesFaceLandmark error]
+ -[CMITextureStylesFaceLandmark initWithPoint:error:]
+ -[CMITextureStylesFaceLandmark point]
+ -[CMITextureStylesFastGaussian .cxx_destruct]
+ -[CMITextureStylesFastGaussian _compileShaders]
+ -[CMITextureStylesFastGaussian _createTexture:]
+ -[CMITextureStylesFastGaussian _dispatch:pipelineState:width:height:]
+ -[CMITextureStylesFastGaussian initWithMetalContext:]
+ -[CMITextureStylesFastGaussian makeTexture:h:fmt:label:]
+ -[CMITextureStylesFastGaussian processTexture:outputTexture:radius:commandBuffer:]
+ -[CMITextureStylesFastGaussian processTexture:outputTexture:sigma:commandBuffer:fastMode:]
+ -[CMITextureStylesFastGaussian runOn:sigma:nSamples:targetBlurRadius:outTexture:commandBuffer:fastMode:]
+ -[CMITextureStylesFilmGrainIO .cxx_destruct]
+ -[CMITextureStylesFilmGrainIO brightnessValue]
+ -[CMITextureStylesFilmGrainIO inputImage]
+ -[CMITextureStylesFilmGrainIO inputPersonImage]
+ -[CMITextureStylesFilmGrainIO inputSkinImage]
+ -[CMITextureStylesFilmGrainIO inputSkyImage]
+ -[CMITextureStylesFilmGrainIO outputImage]
+ -[CMITextureStylesFilmGrainIO setBrightnessValue:]
+ -[CMITextureStylesFilmGrainIO setInputImage:]
+ -[CMITextureStylesFilmGrainIO setInputPersonImage:]
+ -[CMITextureStylesFilmGrainIO setInputSkinImage:]
+ -[CMITextureStylesFilmGrainIO setInputSkyImage:]
+ -[CMITextureStylesFilmGrainIO setOutputImage:]
+ -[CMITextureStylesFilmGrainParameters _floatFromDict:key:default:]
+ -[CMITextureStylesFilmGrainParameters _gainBasedFloatFromDict:key:totalGain:default:]
+ -[CMITextureStylesFilmGrainParameters _unsignedIntegerFromDict:key:default:]
+ -[CMITextureStylesFilmGrainParameters amplitudeDecay]
+ -[CMITextureStylesFilmGrainParameters amplitude]
+ -[CMITextureStylesFilmGrainParameters backgroundStrength]
+ -[CMITextureStylesFilmGrainParameters bvHigh]
+ -[CMITextureStylesFilmGrainParameters bvLowScale]
+ -[CMITextureStylesFilmGrainParameters bvLow]
+ -[CMITextureStylesFilmGrainParameters contrastBoost]
+ -[CMITextureStylesFilmGrainParameters copyWithZone:]
+ -[CMITextureStylesFilmGrainParameters darkScale]
+ -[CMITextureStylesFilmGrainParameters description]
+ -[CMITextureStylesFilmGrainParameters frequencyGap]
+ -[CMITextureStylesFilmGrainParameters grainBlurRadius]
+ -[CMITextureStylesFilmGrainParameters grainSelectivity]
+ -[CMITextureStylesFilmGrainParameters hueMix]
+ -[CMITextureStylesFilmGrainParameters imageGuidedFilterEpsilon]
+ -[CMITextureStylesFilmGrainParameters imageGuidedFilterRadius]
+ -[CMITextureStylesFilmGrainParameters initWithTuningDictionary:]
+ -[CMITextureStylesFilmGrainParameters initWithTuningDictionary:totalGain:]
+ -[CMITextureStylesFilmGrainParameters init]
+ -[CMITextureStylesFilmGrainParameters naturalResolution]
+ -[CMITextureStylesFilmGrainParameters octaves]
+ -[CMITextureStylesFilmGrainParameters personStrength]
+ -[CMITextureStylesFilmGrainParameters saturation]
+ -[CMITextureStylesFilmGrainParameters seed]
+ -[CMITextureStylesFilmGrainParameters setAmplitude:]
+ -[CMITextureStylesFilmGrainParameters setAmplitudeDecay:]
+ -[CMITextureStylesFilmGrainParameters setBackgroundStrength:]
+ -[CMITextureStylesFilmGrainParameters setBvHigh:]
+ -[CMITextureStylesFilmGrainParameters setBvLow:]
+ -[CMITextureStylesFilmGrainParameters setBvLowScale:]
+ -[CMITextureStylesFilmGrainParameters setContrastBoost:]
+ -[CMITextureStylesFilmGrainParameters setDarkScale:]
+ -[CMITextureStylesFilmGrainParameters setDefaults]
+ -[CMITextureStylesFilmGrainParameters setFrequencyGap:]
+ -[CMITextureStylesFilmGrainParameters setGrainBlurRadius:]
+ -[CMITextureStylesFilmGrainParameters setGrainSelectivity:]
+ -[CMITextureStylesFilmGrainParameters setHueMix:]
+ -[CMITextureStylesFilmGrainParameters setImageGuidedFilterEpsilon:]
+ -[CMITextureStylesFilmGrainParameters setImageGuidedFilterRadius:]
+ -[CMITextureStylesFilmGrainParameters setNaturalResolution:]
+ -[CMITextureStylesFilmGrainParameters setOctaves:]
+ -[CMITextureStylesFilmGrainParameters setPersonStrength:]
+ -[CMITextureStylesFilmGrainParameters setSaturation:]
+ -[CMITextureStylesFilmGrainParameters setSeed:]
+ -[CMITextureStylesFilmGrainParameters setShadowLift:]
+ -[CMITextureStylesFilmGrainParameters setSkinStrength:]
+ -[CMITextureStylesFilmGrainParameters setSkyStrength:]
+ -[CMITextureStylesFilmGrainParameters setStrength:]
+ -[CMITextureStylesFilmGrainParameters setTileSize:]
+ -[CMITextureStylesFilmGrainParameters setZoom:]
+ -[CMITextureStylesFilmGrainParameters shadowLift]
+ -[CMITextureStylesFilmGrainParameters skinStrength]
+ -[CMITextureStylesFilmGrainParameters skyStrength]
+ -[CMITextureStylesFilmGrainParameters strength]
+ -[CMITextureStylesFilmGrainParameters tileSize]
+ -[CMITextureStylesFilmGrainParameters validate]
+ -[CMITextureStylesFilmGrainParameters zoom]
+ -[CMITextureStylesFilmGrainProcessorV1 .cxx_destruct]
+ -[CMITextureStylesFilmGrainProcessorV1 _compileShaders]
+ -[CMITextureStylesFilmGrainProcessorV1 _configureColorConversion:forTexture:isOutput:]
+ -[CMITextureStylesFilmGrainProcessorV1 _encodeGrainBlendWithInputImageUsingParams:commandBuffer:inputOutput:]
+ -[CMITextureStylesFilmGrainProcessorV1 _shaderForFilterRadius:]
+ -[CMITextureStylesFilmGrainProcessorV1 _updateColorManagementForInputTexture:outputImageTexture:]
+ -[CMITextureStylesFilmGrainProcessorV1 allocator]
+ -[CMITextureStylesFilmGrainProcessorV1 calculateStats]
+ -[CMITextureStylesFilmGrainProcessorV1 cameraInfoByPortType]
+ -[CMITextureStylesFilmGrainProcessorV1 computeMinimumInputRegionInFullImageCoords:]
+ -[CMITextureStylesFilmGrainProcessorV1 dealloc]
+ -[CMITextureStylesFilmGrainProcessorV1 finishProcessing]
+ -[CMITextureStylesFilmGrainProcessorV1 fullImageSize]
+ -[CMITextureStylesFilmGrainProcessorV1 initWithOptionalMetalContext:]
+ -[CMITextureStylesFilmGrainProcessorV1 inputOutput]
+ -[CMITextureStylesFilmGrainProcessorV1 instanceID]
+ -[CMITextureStylesFilmGrainProcessorV1 metalCommandQueue]
+ -[CMITextureStylesFilmGrainProcessorV1 metalShaderParamsFromDynamicParameters:brightnessValue:]
+ -[CMITextureStylesFilmGrainProcessorV1 parameters]
+ -[CMITextureStylesFilmGrainProcessorV1 personData]
+ -[CMITextureStylesFilmGrainProcessorV1 prepareToProcess:]
+ -[CMITextureStylesFilmGrainProcessorV1 prewarm]
+ -[CMITextureStylesFilmGrainProcessorV1 process]
+ -[CMITextureStylesFilmGrainProcessorV1 purgeResources]
+ -[CMITextureStylesFilmGrainProcessorV1 regionToRender]
+ -[CMITextureStylesFilmGrainProcessorV1 resetState]
+ -[CMITextureStylesFilmGrainProcessorV1 scaleParametersWithIntensity:]
+ -[CMITextureStylesFilmGrainProcessorV1 setAllocator:]
+ -[CMITextureStylesFilmGrainProcessorV1 setCameraInfoByPortType:]
+ -[CMITextureStylesFilmGrainProcessorV1 setFullImageSize:]
+ -[CMITextureStylesFilmGrainProcessorV1 setInputOutput:]
+ -[CMITextureStylesFilmGrainProcessorV1 setInstanceID:]
+ -[CMITextureStylesFilmGrainProcessorV1 setMetalCommandQueue:]
+ -[CMITextureStylesFilmGrainProcessorV1 setParameters:]
+ -[CMITextureStylesFilmGrainProcessorV1 setPersonData:]
+ -[CMITextureStylesFilmGrainProcessorV1 setRegionToRender:]
+ -[CMITextureStylesFilmGrainProcessorV1 setTuningParameters:]
+ -[CMITextureStylesFilmGrainProcessorV1 setup]
+ -[CMITextureStylesFilmGrainProcessorV1 supportsExternalMemoryResource]
+ -[CMITextureStylesFilmGrainProcessorV1 supportsInPlaceRendering]
+ -[CMITextureStylesFilmGrainProcessorV1 tuningParameters]
+ -[CMITextureStylesFilter .cxx_destruct]
+ -[CMITextureStylesFilter _compileShaders]
+ -[CMITextureStylesFilter _guidedFilterInput:guide:outputA:outputB:radius:sigma:epsilon:type:commandBuffer:]
+ -[CMITextureStylesFilter _guidedFilterInput:guide:outputA:outputB:radius:sigma:epsilon:type:encoder:]
+ -[CMITextureStylesFilter _shaderForFilterType:radius:]
+ -[CMITextureStylesFilter calculateIdealRadius:andDownSamplingScale:forImageSize:andTargetFullScaleRadius:]
+ -[CMITextureStylesFilter calculateRadiusForSigma:]
+ -[CMITextureStylesFilter gaussianFilterInput:output:radius:sigma:commandBuffer:]
+ -[CMITextureStylesFilter gaussianFilterInput:output:radius:sigma:encoder:]
+ -[CMITextureStylesFilter guidedFilterInput:guide:outputA:outputB:radius:sigma:epsilon:commandBuffer:]
+ -[CMITextureStylesFilter guidedFilterInput:guide:outputA:outputB:radius:sigma:epsilon:encoder:]
+ -[CMITextureStylesFilter initWithMetalContext:]
+ -[CMITextureStylesFilter weightedGuidedFilterInput:guide:outputA:outputB:radius:sigma:epsilon:commandBuffer:]
+ -[CMITextureStylesFilter weightedGuidedFilterInput:guide:outputA:outputB:radius:sigma:epsilon:encoder:]
+ -[CMITextureStylesGaussianFilter .cxx_destruct]
+ -[CMITextureStylesGaussianFilter _compileShaders]
+ -[CMITextureStylesGaussianFilter encodeGaussianBlur2DWithCommandBuffer:input:output:radius:]
+ -[CMITextureStylesGaussianFilter encodeGaussianBlurWithCommandBuffer:input:output:kernel:kernelSize:]
+ -[CMITextureStylesGaussianFilter encodeGaussianBlurWithCommandBuffer:input:output:radius:]
+ -[CMITextureStylesGaussianFilter encodeSIMDGaussianBlurWithCommandBuffer:input:output:radius:]
+ -[CMITextureStylesGaussianFilter encodeSIMDMaskedDownsampledGaussianBlurWithCommandBuffer:input:output:skinMask:radius:]
+ -[CMITextureStylesGaussianFilter initWithMetalContext:]
+ -[CMITextureStylesGaussianGuidedFilterV3 .cxx_destruct]
+ -[CMITextureStylesGaussianGuidedFilterV3 _compileShaders]
+ -[CMITextureStylesGaussianGuidedFilterV3 _createTexture:]
+ -[CMITextureStylesGaussianGuidedFilterV3 _dispatch:pipelineState:width:height:]
+ -[CMITextureStylesGaussianGuidedFilterV3 initWithMetalContext:]
+ -[CMITextureStylesGaussianGuidedFilterV3 make:h:fmt:label:]
+ -[CMITextureStylesGaussianGuidedFilterV3 runWithInput:skinMask:instanceMask:highlightRetention:sigma:eps:blurRadius:fullImageSize:fullImageOffset:outputTexture:commandBuffer:]
+ -[CMITextureStylesGlow .cxx_destruct]
+ -[CMITextureStylesGlow _compileShaders]
+ -[CMITextureStylesGlow _configureColorConversion:forTexture:isOutput:]
+ -[CMITextureStylesGlow _createGlobalToneCurveTextureFromGTCData:encoder:toneCurveTextureOut:]
+ -[CMITextureStylesGlow _releaseIntermediateTextures]
+ -[CMITextureStylesGlow _updateColorManagementForInputOutput:]
+ -[CMITextureStylesGlow _validateInputsAndParameters]
+ -[CMITextureStylesGlow allocator]
+ -[CMITextureStylesGlow calculateStats]
+ -[CMITextureStylesGlow cameraInfoByPortType]
+ -[CMITextureStylesGlow computeMinimumInputRegionInFullImageCoords:]
+ -[CMITextureStylesGlow dealloc]
+ -[CMITextureStylesGlow finishProcessing]
+ -[CMITextureStylesGlow fullImageSize]
+ -[CMITextureStylesGlow initWithOptionalMetalContext:]
+ -[CMITextureStylesGlow inputOutput]
+ -[CMITextureStylesGlow instanceID]
+ -[CMITextureStylesGlow metalCommandQueue]
+ -[CMITextureStylesGlow parameters]
+ -[CMITextureStylesGlow personData]
+ -[CMITextureStylesGlow prepareToProcess:]
+ -[CMITextureStylesGlow prewarm]
+ -[CMITextureStylesGlow process]
+ -[CMITextureStylesGlow purgeResources]
+ -[CMITextureStylesGlow regionToRender]
+ -[CMITextureStylesGlow resetState]
+ -[CMITextureStylesGlow scaleParametersWithIntensity:]
+ -[CMITextureStylesGlow setAllocator:]
+ -[CMITextureStylesGlow setCameraInfoByPortType:]
+ -[CMITextureStylesGlow setFullImageSize:]
+ -[CMITextureStylesGlow setInputOutput:]
+ -[CMITextureStylesGlow setInstanceID:]
+ -[CMITextureStylesGlow setMetalCommandQueue:]
+ -[CMITextureStylesGlow setParameters:]
+ -[CMITextureStylesGlow setPersonData:]
+ -[CMITextureStylesGlow setRegionToRender:]
+ -[CMITextureStylesGlow setStreamingMode:]
+ -[CMITextureStylesGlow setTuningParameters:]
+ -[CMITextureStylesGlow setup]
+ -[CMITextureStylesGlow streamingMode]
+ -[CMITextureStylesGlow supportsExternalMemoryResource]
+ -[CMITextureStylesGlow supportsInPlaceRendering]
+ -[CMITextureStylesGlow tuningParameters]
+ -[CMITextureStylesGlowIO .cxx_destruct]
+ -[CMITextureStylesGlowIO inputImage]
+ -[CMITextureStylesGlowIO inputLinearImage]
+ -[CMITextureStylesGlowIO inputLinearMetadata]
+ -[CMITextureStylesGlowIO inputMask]
+ -[CMITextureStylesGlowIO outputImage]
+ -[CMITextureStylesGlowIO setInputImage:]
+ -[CMITextureStylesGlowIO setInputLinearImage:]
+ -[CMITextureStylesGlowIO setInputLinearMetadata:]
+ -[CMITextureStylesGlowIO setInputMask:]
+ -[CMITextureStylesGlowIO setOutputImage:]
+ -[CMITextureStylesGlowParameters .cxx_destruct]
+ -[CMITextureStylesGlowParameters _boolFromDict:key:default:]
+ -[CMITextureStylesGlowParameters _floatFromDict:key:default:]
+ -[CMITextureStylesGlowParameters baselineExposure]
+ -[CMITextureStylesGlowParameters brightnessMask]
+ -[CMITextureStylesGlowParameters brightness]
+ -[CMITextureStylesGlowParameters contrastMask]
+ -[CMITextureStylesGlowParameters contrast]
+ -[CMITextureStylesGlowParameters copyWithZone:]
+ -[CMITextureStylesGlowParameters gammaMask]
+ -[CMITextureStylesGlowParameters gamma]
+ -[CMITextureStylesGlowParameters initWithTuningDictionary:]
+ -[CMITextureStylesGlowParameters init]
+ -[CMITextureStylesGlowParameters inputTextureROI]
+ -[CMITextureStylesGlowParameters lightMapGamma]
+ -[CMITextureStylesGlowParameters lightMapMax]
+ -[CMITextureStylesGlowParameters linearImageHighKey]
+ -[CMITextureStylesGlowParameters linearMixForBG]
+ -[CMITextureStylesGlowParameters linearMixForSkin]
+ -[CMITextureStylesGlowParameters preserveColorfulnessMask]
+ -[CMITextureStylesGlowParameters preserveColorfulness]
+ -[CMITextureStylesGlowParameters saturationFromSmartStyle]
+ -[CMITextureStylesGlowParameters saturationMask]
+ -[CMITextureStylesGlowParameters saturation]
+ -[CMITextureStylesGlowParameters setBaselineExposure:]
+ -[CMITextureStylesGlowParameters setBrightness:]
+ -[CMITextureStylesGlowParameters setBrightnessMask:]
+ -[CMITextureStylesGlowParameters setContrast:]
+ -[CMITextureStylesGlowParameters setContrastMask:]
+ -[CMITextureStylesGlowParameters setDefaults]
+ -[CMITextureStylesGlowParameters setGamma:]
+ -[CMITextureStylesGlowParameters setGammaMask:]
+ -[CMITextureStylesGlowParameters setInputTextureROI:]
+ -[CMITextureStylesGlowParameters setLightMapGamma:]
+ -[CMITextureStylesGlowParameters setLightMapMax:]
+ -[CMITextureStylesGlowParameters setLinearImageHighKey:]
+ -[CMITextureStylesGlowParameters setLinearMixForBG:]
+ -[CMITextureStylesGlowParameters setLinearMixForSkin:]
+ -[CMITextureStylesGlowParameters setPreserveColorfulness:]
+ -[CMITextureStylesGlowParameters setPreserveColorfulnessMask:]
+ -[CMITextureStylesGlowParameters setSaturation:]
+ -[CMITextureStylesGlowParameters setSaturationFromSmartStyle:]
+ -[CMITextureStylesGlowParameters setSaturationMask:]
+ -[CMITextureStylesGlowParameters setStatistics:]
+ -[CMITextureStylesGlowParameters setStrength:]
+ -[CMITextureStylesGlowParameters setStrengthMask:]
+ -[CMITextureStylesGlowParameters setUseStatistics:]
+ -[CMITextureStylesGlowParameters statistics]
+ -[CMITextureStylesGlowParameters strengthMask]
+ -[CMITextureStylesGlowParameters strength]
+ -[CMITextureStylesGlowParameters useStatistics]
+ -[CMITextureStylesGlowParameters validate]
+ -[CMITextureStylesGuidedFilter .cxx_destruct]
+ -[CMITextureStylesGuidedFilter _abShaderForRadius:]
+ -[CMITextureStylesGuidedFilter _compileShaders]
+ -[CMITextureStylesGuidedFilter encodeRunWithCommandBuffer:guide:input:output:radius:epsilon:]
+ -[CMITextureStylesGuidedFilter initWithMetalContext:]
+ -[CMITextureStylesHalation .cxx_destruct]
+ -[CMITextureStylesHalation _calculateBlurSigma:]
+ -[CMITextureStylesHalation _calculateFullScaleBlurRadius:]
+ -[CMITextureStylesHalation _compileShaders]
+ -[CMITextureStylesHalation _computeAsymLumMaskWithInput:personMask:outputMask:halationParameters:brightnessValue:commandBuffer:]
+ -[CMITextureStylesHalation _configureColorConversion:forTexture:isOutput:]
+ -[CMITextureStylesHalation _createIntermediateTexturesWithInputRegion:firstBlurSize:secondBlurSize:]
+ -[CMITextureStylesHalation _halationFinalRendererWithInput:halationMask:skinMask:personMask:output:parameters:commandBuffer:]
+ -[CMITextureStylesHalation _releaseIntermediateTextures]
+ -[CMITextureStylesHalation _substractFg:bg:output:commandBuffer:]
+ -[CMITextureStylesHalation _updateColorManagementForInputTexture:outputTexture:]
+ -[CMITextureStylesHalation _validateInputsAndParameters]
+ -[CMITextureStylesHalation allocator]
+ -[CMITextureStylesHalation calculateStats]
+ -[CMITextureStylesHalation cameraInfoByPortType]
+ -[CMITextureStylesHalation computeMinimumInputRegionInFullImageCoords:]
+ -[CMITextureStylesHalation finishProcessing]
+ -[CMITextureStylesHalation fullImageSize]
+ -[CMITextureStylesHalation initWithOptionalMetalContext:]
+ -[CMITextureStylesHalation inputOutput]
+ -[CMITextureStylesHalation instanceID]
+ -[CMITextureStylesHalation metalCommandQueue]
+ -[CMITextureStylesHalation parameters]
+ -[CMITextureStylesHalation personData]
+ -[CMITextureStylesHalation prepareToProcess:]
+ -[CMITextureStylesHalation prewarm]
+ -[CMITextureStylesHalation process]
+ -[CMITextureStylesHalation purgeResources]
+ -[CMITextureStylesHalation regionToRender]
+ -[CMITextureStylesHalation resetState]
+ -[CMITextureStylesHalation scaleParametersWithIntensity:]
+ -[CMITextureStylesHalation setAllocator:]
+ -[CMITextureStylesHalation setCameraInfoByPortType:]
+ -[CMITextureStylesHalation setFullImageSize:]
+ -[CMITextureStylesHalation setInputOutput:]
+ -[CMITextureStylesHalation setInstanceID:]
+ -[CMITextureStylesHalation setMetalCommandQueue:]
+ -[CMITextureStylesHalation setParameters:]
+ -[CMITextureStylesHalation setPersonData:]
+ -[CMITextureStylesHalation setRegionToRender:]
+ -[CMITextureStylesHalation setTuningParameters:]
+ -[CMITextureStylesHalation setup]
+ -[CMITextureStylesHalation supportsExternalMemoryResource]
+ -[CMITextureStylesHalation supportsInPlaceRendering]
+ -[CMITextureStylesHalation tuningParameters]
+ -[CMITextureStylesHalationIO .cxx_destruct]
+ -[CMITextureStylesHalationIO brightnessValue]
+ -[CMITextureStylesHalationIO inputGainMap]
+ -[CMITextureStylesHalationIO inputHDRImage]
+ -[CMITextureStylesHalationIO inputImage]
+ -[CMITextureStylesHalationIO inputLightMap]
+ -[CMITextureStylesHalationIO inputPersonMask]
+ -[CMITextureStylesHalationIO inputSkinMask]
+ -[CMITextureStylesHalationIO outputImage]
+ -[CMITextureStylesHalationIO setBrightnessValue:]
+ -[CMITextureStylesHalationIO setInputGainMap:]
+ -[CMITextureStylesHalationIO setInputHDRImage:]
+ -[CMITextureStylesHalationIO setInputImage:]
+ -[CMITextureStylesHalationIO setInputLightMap:]
+ -[CMITextureStylesHalationIO setInputPersonMask:]
+ -[CMITextureStylesHalationIO setInputSkinMask:]
+ -[CMITextureStylesHalationIO setOutputImage:]
+ -[CMITextureStylesHalationParameters _floatFromDict:key:default:]
+ -[CMITextureStylesHalationParameters bg]
+ -[CMITextureStylesHalationParameters bvHigh]
+ -[CMITextureStylesHalationParameters bvLow]
+ -[CMITextureStylesHalationParameters bvThresholdDeltaLowScale]
+ -[CMITextureStylesHalationParameters copyWithZone:]
+ -[CMITextureStylesHalationParameters faceTempering]
+ -[CMITextureStylesHalationParameters halationChroma]
+ -[CMITextureStylesHalationParameters halationHue]
+ -[CMITextureStylesHalationParameters initWithTuningDictionary:]
+ -[CMITextureStylesHalationParameters init]
+ -[CMITextureStylesHalationParameters inputInnerKnot0]
+ -[CMITextureStylesHalationParameters inputInnerKnot1]
+ -[CMITextureStylesHalationParameters inputLowerBound]
+ -[CMITextureStylesHalationParameters inputLowerCoeffA]
+ -[CMITextureStylesHalationParameters inputLowerCoeffB]
+ -[CMITextureStylesHalationParameters inputOuterKnot0]
+ -[CMITextureStylesHalationParameters inputOuterKnot1]
+ -[CMITextureStylesHalationParameters inputSpread]
+ -[CMITextureStylesHalationParameters inputTextureROI]
+ -[CMITextureStylesHalationParameters inputThresholdDelta]
+ -[CMITextureStylesHalationParameters inputUpperCoeffA]
+ -[CMITextureStylesHalationParameters inputUpperCoeffB]
+ -[CMITextureStylesHalationParameters maskBlurSigma]
+ -[CMITextureStylesHalationParameters maxRGB]
+ -[CMITextureStylesHalationParameters meteorHeadroomMixFactor]
+ -[CMITextureStylesHalationParameters meteorHeadroom]
+ -[CMITextureStylesHalationParameters naturalResolution]
+ -[CMITextureStylesHalationParameters person]
+ -[CMITextureStylesHalationParameters setBg:]
+ -[CMITextureStylesHalationParameters setBvHigh:]
+ -[CMITextureStylesHalationParameters setBvLow:]
+ -[CMITextureStylesHalationParameters setBvThresholdDeltaLowScale:]
+ -[CMITextureStylesHalationParameters setDefaults]
+ -[CMITextureStylesHalationParameters setFaceTempering:]
+ -[CMITextureStylesHalationParameters setHalationChroma:]
+ -[CMITextureStylesHalationParameters setHalationHue:]
+ -[CMITextureStylesHalationParameters setInputInnerKnot0:]
+ -[CMITextureStylesHalationParameters setInputInnerKnot1:]
+ -[CMITextureStylesHalationParameters setInputLowerBound:]
+ -[CMITextureStylesHalationParameters setInputLowerCoeffA:]
+ -[CMITextureStylesHalationParameters setInputLowerCoeffB:]
+ -[CMITextureStylesHalationParameters setInputOuterKnot0:]
+ -[CMITextureStylesHalationParameters setInputOuterKnot1:]
+ -[CMITextureStylesHalationParameters setInputSpread:]
+ -[CMITextureStylesHalationParameters setInputTextureROI:]
+ -[CMITextureStylesHalationParameters setInputThresholdDelta:]
+ -[CMITextureStylesHalationParameters setInputUpperCoeffA:]
+ -[CMITextureStylesHalationParameters setInputUpperCoeffB:]
+ -[CMITextureStylesHalationParameters setMaskBlurSigma:]
+ -[CMITextureStylesHalationParameters setMaxRGB:]
+ -[CMITextureStylesHalationParameters setMeteorHeadroom:]
+ -[CMITextureStylesHalationParameters setMeteorHeadroomMixFactor:]
+ -[CMITextureStylesHalationParameters setNaturalResolution:]
+ -[CMITextureStylesHalationParameters setPerson:]
+ -[CMITextureStylesHalationParameters setStrength:]
+ -[CMITextureStylesHalationParameters strength]
+ -[CMITextureStylesHalationParameters validate]
+ -[CMITextureStylesMattify .cxx_destruct]
+ -[CMITextureStylesMattify _calculateExtendedFaceROI:leftCheekROI:rightCheekROI:triangleVerticesLeft:triangleVerticesRight:]
+ -[CMITextureStylesMattify _calculateMasks:warpedMaskAggregate:extendedFaceROI:leftCheekROI:rightCheekROI:triangleVerticesLeft:triangleVerticesRight:]
+ -[CMITextureStylesMattify _calculateStats:validMask:warpedMaskAggregate:statsBuffer:]
+ -[CMITextureStylesMattify _compileShaders]
+ -[CMITextureStylesMattify _freePersonIntermediatesAndStats:]
+ -[CMITextureStylesMattify _processApply]
+ -[CMITextureStylesMattify allocator]
+ -[CMITextureStylesMattify calculateStats]
+ -[CMITextureStylesMattify cameraInfoByPortType]
+ -[CMITextureStylesMattify computeMinimumInputRegionInFullImageCoords:]
+ -[CMITextureStylesMattify dealloc]
+ -[CMITextureStylesMattify encodeDownsampledGaussianBlurWithCommandBuffer:inputImage:outputDownsampledAndBlurredImage:outputImage:downsampleFactor:downsampleSigma:stopAfterDownsample:cropAndDownsampleSkipLevelCount:cropAndDownsampleBoxFilter:]
+ -[CMITextureStylesMattify finishProcessing]
+ -[CMITextureStylesMattify fullImageSize]
+ -[CMITextureStylesMattify initWithOptionalMetalContext:]
+ -[CMITextureStylesMattify inputOutput]
+ -[CMITextureStylesMattify instanceID]
+ -[CMITextureStylesMattify metalCommandQueue]
+ -[CMITextureStylesMattify parameters]
+ -[CMITextureStylesMattify personData]
+ -[CMITextureStylesMattify prepareToProcess:]
+ -[CMITextureStylesMattify prewarm]
+ -[CMITextureStylesMattify process]
+ -[CMITextureStylesMattify purgeResources]
+ -[CMITextureStylesMattify regionToRender]
+ -[CMITextureStylesMattify resetState]
+ -[CMITextureStylesMattify scaleParametersWithIntensity:]
+ -[CMITextureStylesMattify setAllocator:]
+ -[CMITextureStylesMattify setCameraInfoByPortType:]
+ -[CMITextureStylesMattify setFullImageSize:]
+ -[CMITextureStylesMattify setInputOutput:]
+ -[CMITextureStylesMattify setInstanceID:]
+ -[CMITextureStylesMattify setMetalCommandQueue:]
+ -[CMITextureStylesMattify setParameters:]
+ -[CMITextureStylesMattify setPersonData:]
+ -[CMITextureStylesMattify setRegionToRender:]
+ -[CMITextureStylesMattify setSkipRendering:]
+ -[CMITextureStylesMattify setStreamingMode:]
+ -[CMITextureStylesMattify setTuningParameters:]
+ -[CMITextureStylesMattify setup]
+ -[CMITextureStylesMattify skipRendering]
+ -[CMITextureStylesMattify streamingMode]
+ -[CMITextureStylesMattify supportsExternalMemoryResource]
+ -[CMITextureStylesMattify supportsInPlaceRendering]
+ -[CMITextureStylesMattify tuningParameters]
+ -[CMITextureStylesMattifyIO .cxx_destruct]
+ -[CMITextureStylesMattifyIO inputEarMask]
+ -[CMITextureStylesMattifyIO inputFaceMask]
+ -[CMITextureStylesMattifyIO inputGlassesMask]
+ -[CMITextureStylesMattifyIO inputImage]
+ -[CMITextureStylesMattifyIO inputInstanceMask]
+ -[CMITextureStylesMattifyIO inputLipsMask]
+ -[CMITextureStylesMattifyIO inputNoseMask]
+ -[CMITextureStylesMattifyIO inputSkinMask]
+ -[CMITextureStylesMattifyIO inputTattoosMask]
+ -[CMITextureStylesMattifyIO outputImage]
+ -[CMITextureStylesMattifyIO outputPersonStats]
+ -[CMITextureStylesMattifyIO setInputEarMask:]
+ -[CMITextureStylesMattifyIO setInputFaceMask:]
+ -[CMITextureStylesMattifyIO setInputGlassesMask:]
+ -[CMITextureStylesMattifyIO setInputImage:]
+ -[CMITextureStylesMattifyIO setInputInstanceMask:]
+ -[CMITextureStylesMattifyIO setInputLipsMask:]
+ -[CMITextureStylesMattifyIO setInputNoseMask:]
+ -[CMITextureStylesMattifyIO setInputSkinMask:]
+ -[CMITextureStylesMattifyIO setInputTattoosMask:]
+ -[CMITextureStylesMattifyIO setOutputImage:]
+ -[CMITextureStylesMattifyIO setOutputPersonStats:]
+ -[CMITextureStylesMattifyParameters blendColorImageAverageColorMixFactor]
+ -[CMITextureStylesMattifyParameters copyWithZone:]
+ -[CMITextureStylesMattifyParameters darknessDiffSmoothstepLowerBound]
+ -[CMITextureStylesMattifyParameters darknessDiffSmoothstepUpperBound]
+ -[CMITextureStylesMattifyParameters editingStrength]
+ -[CMITextureStylesMattifyParameters fracMaskHighlightsHeadroom]
+ -[CMITextureStylesMattifyParameters fracMaskHighlightsNormFactor]
+ -[CMITextureStylesMattifyParameters hueDiffMeanTermSmoothstepLowerBound]
+ -[CMITextureStylesMattifyParameters hueDiffMeanTermSmoothstepUpperBound]
+ -[CMITextureStylesMattifyParameters hueDiffSmoothstepLowerBound]
+ -[CMITextureStylesMattifyParameters hueDiffSmoothstepUpperBound]
+ -[CMITextureStylesMattifyParameters imageTextureFactor]
+ -[CMITextureStylesMattifyParameters imageTextureThreshold]
+ -[CMITextureStylesMattifyParameters initWithTuningDictionary:]
+ -[CMITextureStylesMattifyParameters init]
+ -[CMITextureStylesMattifyParameters largeBlurRadiusFaceDiagonalFactor]
+ -[CMITextureStylesMattifyParameters lightnessEditFactor]
+ -[CMITextureStylesMattifyParameters lightnessEditHeadroom]
+ -[CMITextureStylesMattifyParameters setBlendColorImageAverageColorMixFactor:]
+ -[CMITextureStylesMattifyParameters setDarknessDiffSmoothstepLowerBound:]
+ -[CMITextureStylesMattifyParameters setDarknessDiffSmoothstepUpperBound:]
+ -[CMITextureStylesMattifyParameters setDefaults]
+ -[CMITextureStylesMattifyParameters setEditingStrength:]
+ -[CMITextureStylesMattifyParameters setFracMaskHighlightsHeadroom:]
+ -[CMITextureStylesMattifyParameters setFracMaskHighlightsNormFactor:]
+ -[CMITextureStylesMattifyParameters setHueDiffMeanTermSmoothstepLowerBound:]
+ -[CMITextureStylesMattifyParameters setHueDiffMeanTermSmoothstepUpperBound:]
+ -[CMITextureStylesMattifyParameters setHueDiffSmoothstepLowerBound:]
+ -[CMITextureStylesMattifyParameters setHueDiffSmoothstepUpperBound:]
+ -[CMITextureStylesMattifyParameters setImageTextureFactor:]
+ -[CMITextureStylesMattifyParameters setImageTextureThreshold:]
+ -[CMITextureStylesMattifyParameters setLargeBlurRadiusFaceDiagonalFactor:]
+ -[CMITextureStylesMattifyParameters setLightnessEditFactor:]
+ -[CMITextureStylesMattifyParameters setLightnessEditHeadroom:]
+ -[CMITextureStylesMattifyParameters setSmallBlurRadiusFaceDiagonalFactor:]
+ -[CMITextureStylesMattifyParameters setTextureRestoreScalingFactor:]
+ -[CMITextureStylesMattifyParameters setTextureRestoreSmoothstepLowerBound:]
+ -[CMITextureStylesMattifyParameters setTextureRestoreSmoothstepUpperBound:]
+ -[CMITextureStylesMattifyParameters setTextureRestoreStrengthFactor:]
+ -[CMITextureStylesMattifyParameters smallBlurRadiusFaceDiagonalFactor]
+ -[CMITextureStylesMattifyParameters textureRestoreScalingFactor]
+ -[CMITextureStylesMattifyParameters textureRestoreSmoothstepLowerBound]
+ -[CMITextureStylesMattifyParameters textureRestoreSmoothstepUpperBound]
+ -[CMITextureStylesMattifyParameters textureRestoreStrengthFactor]
+ -[CMITextureStylesMattifyParameters validate]
+ -[CMITextureStylesPersonInputData .cxx_destruct]
+ -[CMITextureStylesPersonInputData convertDegreesToRadians]
+ -[CMITextureStylesPersonInputData convertRadiansToDegrees]
+ -[CMITextureStylesPersonInputData copyWithZone:]
+ -[CMITextureStylesPersonInputData dictionaryRepresentationForKeys:]
+ -[CMITextureStylesPersonInputData dictionaryRepresentation]
+ -[CMITextureStylesPersonInputData faceID]
+ -[CMITextureStylesPersonInputData faceLandmarkType]
+ -[CMITextureStylesPersonInputData faceLandmarks]
+ -[CMITextureStylesPersonInputData facePitch]
+ -[CMITextureStylesPersonInputData faceROIAndLandmarksROIRelativeScalingROI]
+ -[CMITextureStylesPersonInputData faceROI]
+ -[CMITextureStylesPersonInputData faceRoll]
+ -[CMITextureStylesPersonInputData faceSkinROI]
+ -[CMITextureStylesPersonInputData faceYaw]
+ -[CMITextureStylesPersonInputData imageStats]
+ -[CMITextureStylesPersonInputData init]
+ -[CMITextureStylesPersonInputData instanceMaskReferenceKey]
+ -[CMITextureStylesPersonInputData instanceMask]
+ -[CMITextureStylesPersonInputData instanceROI]
+ -[CMITextureStylesPersonInputData normalizeRelativeToCropRect:]
+ -[CMITextureStylesPersonInputData setFaceID:]
+ -[CMITextureStylesPersonInputData setFaceLandmarkType:]
+ -[CMITextureStylesPersonInputData setFaceLandmarks:]
+ -[CMITextureStylesPersonInputData setFacePitch:]
+ -[CMITextureStylesPersonInputData setFaceROI:]
+ -[CMITextureStylesPersonInputData setFaceRoll:]
+ -[CMITextureStylesPersonInputData setFaceSkinROI:]
+ -[CMITextureStylesPersonInputData setFaceYaw:]
+ -[CMITextureStylesPersonInputData setImageStats:]
+ -[CMITextureStylesPersonInputData setInstanceMask:]
+ -[CMITextureStylesPersonInputData setInstanceMaskReferenceKey:]
+ -[CMITextureStylesPersonInputData setInstanceROI:]
+ -[CMITextureStylesPersonInputData setUnitOfAngle:]
+ -[CMITextureStylesPersonInputData unitOfAngle]
+ -[CMITextureStylesProcessor .cxx_destruct]
+ -[CMITextureStylesProcessor _allocateRenderBufferForRegion:currentInput:outputPtr:]
+ -[CMITextureStylesProcessor _bindIOBuffers:andPerPersonTextureAndFullImageRegionArray:]
+ -[CMITextureStylesProcessor _bindIOImages:]
+ -[CMITextureStylesProcessor _bindIOImages:andPerPersonTextureAndFullImageRegionArray:]
+ -[CMITextureStylesProcessor _bindImageTile:toTextureAndFullImageRegion:withUsage:label:]
+ -[CMITextureStylesProcessor _bindPerPersonImages:]
+ -[CMITextureStylesProcessor _bindPixelBufferToTexture:usage:overrideMTLPixelFormatWithFormat:planeIndex:textureCache:]
+ -[CMITextureStylesProcessor _calculateAllImageRectIntersections:ioTextureDict:perPersonTextureAndFullImageRegionArray:]
+ -[CMITextureStylesProcessor _calculateFullImageSize:ioTextureDict:]
+ -[CMITextureStylesProcessor _calculatePaddedRegionToRender:perPersonData:roiData:paddedRegionToRenderOut:]
+ -[CMITextureStylesProcessor _createEffectProcessorsAndUtilities]
+ -[CMITextureStylesProcessor _createMemoryResource]
+ -[CMITextureStylesProcessor _denormalizePersonData:ioTextureDict:roiData:]
+ -[CMITextureStylesProcessor _getEffectRendererByType:]
+ -[CMITextureStylesProcessor _instanceLabel:]
+ -[CMITextureStylesProcessor _prepareEffectsToRender]
+ -[CMITextureStylesProcessor _preparePerPersonData]
+ -[CMITextureStylesProcessor _scaleIntensityForEffects:]
+ -[CMITextureStylesProcessor _selectOutputBufferForRegion:rendersInPlace:ioTextureDict:currentInput:intermediateTextureAndFullImageRegions:intermediateTextureAndFullImageRegionCount:currentOutputPtr:]
+ -[CMITextureStylesProcessor _setROIData:]
+ -[CMITextureStylesProcessor _setROIData:ioTextureDict:perPersonTextureAndFullImageRegionArray:]
+ -[CMITextureStylesProcessor _setROIData:perPersonTextureAndFullImageRegionArray:roiData:calculatePaddedRegionToRender:]
+ -[CMITextureStylesProcessor _validateUserSettings:]
+ -[CMITextureStylesProcessor brightnessValue]
+ -[CMITextureStylesProcessor cameraInfoByPortType]
+ -[CMITextureStylesProcessor computeMinimumInputRegionInFullImageCoords:]
+ -[CMITextureStylesProcessor dealloc]
+ -[CMITextureStylesProcessor effectsToRender]
+ -[CMITextureStylesProcessor enableSkinSmoothingMultiPersonBlending]
+ -[CMITextureStylesProcessor externalMemoryResource]
+ -[CMITextureStylesProcessor finishProcessing]
+ -[CMITextureStylesProcessor fullImageSize]
+ -[CMITextureStylesProcessor initWithOptionalMetalCommandQueue:]
+ -[CMITextureStylesProcessor init]
+ -[CMITextureStylesProcessor inputImage]
+ -[CMITextureStylesProcessor inputLinearImageMetadata]
+ -[CMITextureStylesProcessor inputLinearImage]
+ -[CMITextureStylesProcessor inputMasks]
+ -[CMITextureStylesProcessor inputMeteorGainMap]
+ -[CMITextureStylesProcessor inputPersonData]
+ -[CMITextureStylesProcessor inputPingPongImageForRendering]
+ -[CMITextureStylesProcessor inputSkinSmoothingFaceDetections]
+ -[CMITextureStylesProcessor label]
+ -[CMITextureStylesProcessor memoryResource]
+ -[CMITextureStylesProcessor metalCommandQueue]
+ -[CMITextureStylesProcessor needsIntermediateRenderingBuffer]
+ -[CMITextureStylesProcessor outputImage]
+ -[CMITextureStylesProcessor outputPersonImageStats]
+ -[CMITextureStylesProcessor outputSkinSmoothingLargeBlurGuidedFilterA]
+ -[CMITextureStylesProcessor outputSkinSmoothingLargeBlurGuidedFilterB]
+ -[CMITextureStylesProcessor outputSkinSmoothingProcessedMask]
+ -[CMITextureStylesProcessor outputSkinSmoothingSmallBlur]
+ -[CMITextureStylesProcessor outputSkinSmoothingStats]
+ -[CMITextureStylesProcessor outputSkinSmoothingTextureAddback]
+ -[CMITextureStylesProcessor prepareToProcess:]
+ -[CMITextureStylesProcessor prewarm]
+ -[CMITextureStylesProcessor process]
+ -[CMITextureStylesProcessor purgeResources]
+ -[CMITextureStylesProcessor regionToRender]
+ -[CMITextureStylesProcessor resetState]
+ -[CMITextureStylesProcessor setBrightnessValue:]
+ -[CMITextureStylesProcessor setCameraInfoByPortType:]
+ -[CMITextureStylesProcessor setEffectsToRender:]
+ -[CMITextureStylesProcessor setEnableSkinSmoothingMultiPersonBlending:]
+ -[CMITextureStylesProcessor setExternalMemoryResource:]
+ -[CMITextureStylesProcessor setFullImageSize:]
+ -[CMITextureStylesProcessor setInputImage:]
+ -[CMITextureStylesProcessor setInputLinearImage:]
+ -[CMITextureStylesProcessor setInputLinearImageMetadata:]
+ -[CMITextureStylesProcessor setInputMasks:]
+ -[CMITextureStylesProcessor setInputMeteorGainMap:]
+ -[CMITextureStylesProcessor setInputPersonData:]
+ -[CMITextureStylesProcessor setInputPingPongImageForRendering:]
+ -[CMITextureStylesProcessor setInputSkinSmoothingFaceDetections:]
+ -[CMITextureStylesProcessor setLabel:]
+ -[CMITextureStylesProcessor setMemoryResource:]
+ -[CMITextureStylesProcessor setMetalCommandQueue:]
+ -[CMITextureStylesProcessor setOutputImage:]
+ -[CMITextureStylesProcessor setOutputPersonImageStats:]
+ -[CMITextureStylesProcessor setOutputSkinSmoothingLargeBlurGuidedFilterA:]
+ -[CMITextureStylesProcessor setOutputSkinSmoothingLargeBlurGuidedFilterB:]
+ -[CMITextureStylesProcessor setOutputSkinSmoothingProcessedMask:]
+ -[CMITextureStylesProcessor setOutputSkinSmoothingSmallBlur:]
+ -[CMITextureStylesProcessor setOutputSkinSmoothingStats:]
+ -[CMITextureStylesProcessor setOutputSkinSmoothingTextureAddback:]
+ -[CMITextureStylesProcessor setRegionToRender:]
+ -[CMITextureStylesProcessor setShouldFlushCVMTLCachesOnResetState:]
+ -[CMITextureStylesProcessor setStreamingMode:]
+ -[CMITextureStylesProcessor setTextureStyleIntensity:]
+ -[CMITextureStylesProcessor setTuningParameters:]
+ -[CMITextureStylesProcessor setup]
+ -[CMITextureStylesProcessor shouldFlushCVMTLCachesOnResetState]
+ -[CMITextureStylesProcessor streamingMode]
+ -[CMITextureStylesProcessor supportsExternalMemoryResource]
+ -[CMITextureStylesProcessor textureStyleIntensity]
+ -[CMITextureStylesProcessor tuningParameters]
+ -[CMITextureStylesProcessor waitForSchedule]
+ -[CMITextureStylesPyramid .cxx_destruct]
+ -[CMITextureStylesPyramid dealloc]
+ -[CMITextureStylesPyramid dereference]
+ -[CMITextureStylesPyramid initWithImage:maxLevels:allocator:encoder:shader:]
+ -[CMITextureStylesPyramid initWithImage:maxLevels:pixelFormat:allocator:encoder:shader:]
+ -[CMITextureStylesPyramid nLevels]
+ -[CMITextureStylesPyramid objectAtIndexedSubscript:]
+ -[CMITextureStylesPyramidFactory .cxx_destruct]
+ -[CMITextureStylesPyramidFactory _compileShaders]
+ -[CMITextureStylesPyramidFactory createPyramidWithImage:maxLevels:encoder:]
+ -[CMITextureStylesPyramidFactory createPyramidWithImage:maxLevels:pixelFormat:encoder:]
+ -[CMITextureStylesPyramidFactory initWithMetalContext:]
+ -[CMITextureStylesSkinSmoothIO .cxx_destruct]
+ -[CMITextureStylesSkinSmoothIO allPersonDataForBlending]
+ -[CMITextureStylesSkinSmoothIO bodyMaskTextureAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothIO brightnessValue]
+ -[CMITextureStylesSkinSmoothIO earsMaskTextureAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothIO externalFaceRoughnessStatsOutput]
+ -[CMITextureStylesSkinSmoothIO externalLargeBlurGuidedFilterAOutput]
+ -[CMITextureStylesSkinSmoothIO externalLargeBlurGuidedFilterBOutput]
+ -[CMITextureStylesSkinSmoothIO externalSmallBlurOutput]
+ -[CMITextureStylesSkinSmoothIO externalTextureAddbackOutput]
+ -[CMITextureStylesSkinSmoothIO eyebrowsMaskTextureAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothIO faceSkinMaskTextureAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothIO glassesMaskTextureAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothIO hairMaskTextureAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothIO handsMaskTextureAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothIO inputFaceRect]
+ -[CMITextureStylesSkinSmoothIO inputImage]
+ -[CMITextureStylesSkinSmoothIO inputSkinMaskAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothIO instanceMaskTextureAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothIO lipsMaskTextureAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothIO outputImage]
+ -[CMITextureStylesSkinSmoothIO outputPersonStats]
+ -[CMITextureStylesSkinSmoothIO outputProcessedSkinMask]
+ -[CMITextureStylesSkinSmoothIO personMaskTextureAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothIO setAllPersonDataForBlending:]
+ -[CMITextureStylesSkinSmoothIO setBodyMaskTextureAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO setBrightnessValue:]
+ -[CMITextureStylesSkinSmoothIO setEarsMaskTextureAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO setExternalFaceRoughnessStatsOutput:]
+ -[CMITextureStylesSkinSmoothIO setExternalLargeBlurGuidedFilterAOutput:]
+ -[CMITextureStylesSkinSmoothIO setExternalLargeBlurGuidedFilterBOutput:]
+ -[CMITextureStylesSkinSmoothIO setExternalSmallBlurOutput:]
+ -[CMITextureStylesSkinSmoothIO setExternalTextureAddbackOutput:]
+ -[CMITextureStylesSkinSmoothIO setEyebrowsMaskTextureAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO setFaceSkinMaskTextureAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO setGlassesMaskTextureAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO setHairMaskTextureAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO setHandsMaskTextureAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO setInputFaceRect:]
+ -[CMITextureStylesSkinSmoothIO setInputImage:]
+ -[CMITextureStylesSkinSmoothIO setInputSkinMaskAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO setInstanceMaskTextureAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO setLipsMaskTextureAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO setOutputImage:]
+ -[CMITextureStylesSkinSmoothIO setOutputPersonStats:]
+ -[CMITextureStylesSkinSmoothIO setOutputProcessedSkinMask:]
+ -[CMITextureStylesSkinSmoothIO setPersonMaskTextureAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO setTattoosMaskTextureAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO setTeethMaskTextureAndFullImageRegion:]
+ -[CMITextureStylesSkinSmoothIO tattoosMaskTextureAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothIO teethMaskTextureAndFullImageRegion]
+ -[CMITextureStylesSkinSmoothParameters copyWithZone:]
+ -[CMITextureStylesSkinSmoothParameters degrungeBody]
+ -[CMITextureStylesSkinSmoothParameters degrunge]
+ -[CMITextureStylesSkinSmoothParameters detailSize]
+ -[CMITextureStylesSkinSmoothParameters enableTextureAddback]
+ -[CMITextureStylesSkinSmoothParameters eyeProtection]
+ -[CMITextureStylesSkinSmoothParameters eyebrows]
+ -[CMITextureStylesSkinSmoothParameters fastMode]
+ -[CMITextureStylesSkinSmoothParameters gFContrast]
+ -[CMITextureStylesSkinSmoothParameters gFRadius]
+ -[CMITextureStylesSkinSmoothParameters hairClothes]
+ -[CMITextureStylesSkinSmoothParameters hairTxFloor]
+ -[CMITextureStylesSkinSmoothParameters handsAndEars]
+ -[CMITextureStylesSkinSmoothParameters highlightRetention]
+ -[CMITextureStylesSkinSmoothParameters hlBlurStrength]
+ -[CMITextureStylesSkinSmoothParameters hlTextureRestore]
+ -[CMITextureStylesSkinSmoothParameters initWithTuningDictionary:]
+ -[CMITextureStylesSkinSmoothParameters initWithTuningDictionary:totalGain:]
+ -[CMITextureStylesSkinSmoothParameters init]
+ -[CMITextureStylesSkinSmoothParameters lipContrast]
+ -[CMITextureStylesSkinSmoothParameters lipCrease]
+ -[CMITextureStylesSkinSmoothParameters lipHighlights]
+ -[CMITextureStylesSkinSmoothParameters lipNegClar]
+ -[CMITextureStylesSkinSmoothParameters maxDarknessTrigger]
+ -[CMITextureStylesSkinSmoothParameters minDarknessTrigger]
+ -[CMITextureStylesSkinSmoothParameters minTexture]
+ -[CMITextureStylesSkinSmoothParameters nightModeSharpness]
+ -[CMITextureStylesSkinSmoothParameters nightMode]
+ -[CMITextureStylesSkinSmoothParameters plusGreenGuide]
+ -[CMITextureStylesSkinSmoothParameters poresBody]
+ -[CMITextureStylesSkinSmoothParameters pores]
+ -[CMITextureStylesSkinSmoothParameters roughSamples]
+ -[CMITextureStylesSkinSmoothParameters setDefaults]
+ -[CMITextureStylesSkinSmoothParameters setDegrunge:]
+ -[CMITextureStylesSkinSmoothParameters setDegrungeBody:]
+ -[CMITextureStylesSkinSmoothParameters setDetailSize:]
+ -[CMITextureStylesSkinSmoothParameters setEnableTextureAddback:]
+ -[CMITextureStylesSkinSmoothParameters setEyeProtection:]
+ -[CMITextureStylesSkinSmoothParameters setEyebrows:]
+ -[CMITextureStylesSkinSmoothParameters setFastMode:]
+ -[CMITextureStylesSkinSmoothParameters setGFContrast:]
+ -[CMITextureStylesSkinSmoothParameters setGFRadius:]
+ -[CMITextureStylesSkinSmoothParameters setHairClothes:]
+ -[CMITextureStylesSkinSmoothParameters setHairTxFloor:]
+ -[CMITextureStylesSkinSmoothParameters setHandsAndEars:]
+ -[CMITextureStylesSkinSmoothParameters setHighlightRetention:]
+ -[CMITextureStylesSkinSmoothParameters setHlBlurStrength:]
+ -[CMITextureStylesSkinSmoothParameters setHlTextureRestore:]
+ -[CMITextureStylesSkinSmoothParameters setLipContrast:]
+ -[CMITextureStylesSkinSmoothParameters setLipCrease:]
+ -[CMITextureStylesSkinSmoothParameters setLipHighlights:]
+ -[CMITextureStylesSkinSmoothParameters setLipNegClar:]
+ -[CMITextureStylesSkinSmoothParameters setMaxDarknessTrigger:]
+ -[CMITextureStylesSkinSmoothParameters setMinDarknessTrigger:]
+ -[CMITextureStylesSkinSmoothParameters setMinTexture:]
+ -[CMITextureStylesSkinSmoothParameters setNightMode:]
+ -[CMITextureStylesSkinSmoothParameters setNightModeSharpness:]
+ -[CMITextureStylesSkinSmoothParameters setPlusGreenGuide:]
+ -[CMITextureStylesSkinSmoothParameters setPores:]
+ -[CMITextureStylesSkinSmoothParameters setPoresBody:]
+ -[CMITextureStylesSkinSmoothParameters setRoughSamples:]
+ -[CMITextureStylesSkinSmoothParameters setStrongTextureProtect:]
+ -[CMITextureStylesSkinSmoothParameters setTattooSmoothing:]
+ -[CMITextureStylesSkinSmoothParameters setTattooWeight:]
+ -[CMITextureStylesSkinSmoothParameters setTeeth:]
+ -[CMITextureStylesSkinSmoothParameters setTextureClamp:]
+ -[CMITextureStylesSkinSmoothParameters setTextureDetectScale:]
+ -[CMITextureStylesSkinSmoothParameters setTextureRestore:]
+ -[CMITextureStylesSkinSmoothParameters setVarTexture:]
+ -[CMITextureStylesSkinSmoothParameters strongTextureProtect]
+ -[CMITextureStylesSkinSmoothParameters tattooSmoothing]
+ -[CMITextureStylesSkinSmoothParameters tattooWeight]
+ -[CMITextureStylesSkinSmoothParameters teeth]
+ -[CMITextureStylesSkinSmoothParameters textureClamp]
+ -[CMITextureStylesSkinSmoothParameters textureDetectScale]
+ -[CMITextureStylesSkinSmoothParameters textureRestore]
+ -[CMITextureStylesSkinSmoothParameters validate]
+ -[CMITextureStylesSkinSmoothParameters varTexture]
+ -[CMITextureStylesSkinSmoothStandalone .cxx_destruct]
+ -[CMITextureStylesSkinSmoothStandalone _allocateStatsBuffers]
+ -[CMITextureStylesSkinSmoothStandalone _calculateBlurEstimate]
+ -[CMITextureStylesSkinSmoothStandalone _calculateFaceRoughnessFromImage:smallBlurTextureAndFullImageRegion:faceSkinMaskTextureAndFullImageRegion:skinMaskTextureAndFullImageRegion:faceRect:roughSamples:commandBuffer:]
+ -[CMITextureStylesSkinSmoothStandalone _compileShaders]
+ -[CMITextureStylesSkinSmoothStandalone _computeTextureAmountFromInput:skinMask:personMask:faceMask:otherSkinMask:hairTxFloor:textureDetectScale:strongTextureProtect:textureBlurSigma:commandBuffer:fastMode:]
+ -[CMITextureStylesSkinSmoothStandalone _copyStatsBuffer:toHeapBufferOut:commandBuffer:]
+ -[CMITextureStylesSkinSmoothStandalone _createLargeBlurFromInputs:params:sigma:epsilon:filterRadius:downScaleFactor:commandBuffer:statsBuffer:]
+ -[CMITextureStylesSkinSmoothStandalone _createSmallBlurFromInput:sigma:filterRadius:downScaleFactor:commandBuffer:]
+ -[CMITextureStylesSkinSmoothStandalone _createTexture:label:]
+ -[CMITextureStylesSkinSmoothStandalone _createUncompressedTexture:label:]
+ -[CMITextureStylesSkinSmoothStandalone _packPrecomputedMasks:blendingParams:commandBuffer:packedMasks:faceDerived:]
+ -[CMITextureStylesSkinSmoothStandalone _performFinalBlending:parameters:smallBlurTextureAndFullImageRegion:statsBuffer:processedSkinMaskOverride:commandBuffer:]
+ -[CMITextureStylesSkinSmoothStandalone _popStatsBufferFromBufferPool]
+ -[CMITextureStylesSkinSmoothStandalone _processMultiPersonSkinMask:inputOutput:]
+ -[CMITextureStylesSkinSmoothStandalone _processSkinMask:inputMask:outputMask:maskFullImageRegion:personDataArray:]
+ -[CMITextureStylesSkinSmoothStandalone _returnStatsBufferToBufferPool:]
+ -[CMITextureStylesSkinSmoothStandalone _writeIntermediatesToExternalOutputs:]
+ -[CMITextureStylesSkinSmoothStandalone allocator]
+ -[CMITextureStylesSkinSmoothStandalone calculateStats]
+ -[CMITextureStylesSkinSmoothStandalone cameraInfoByPortType]
+ -[CMITextureStylesSkinSmoothStandalone computeMinimumInputRegionInFullImageCoords:]
+ -[CMITextureStylesSkinSmoothStandalone finishProcessing]
+ -[CMITextureStylesSkinSmoothStandalone fullImageSize]
+ -[CMITextureStylesSkinSmoothStandalone initWithOptionalMetalContext:]
+ -[CMITextureStylesSkinSmoothStandalone inputOutput]
+ -[CMITextureStylesSkinSmoothStandalone instanceID]
+ -[CMITextureStylesSkinSmoothStandalone metalCommandQueue]
+ -[CMITextureStylesSkinSmoothStandalone parameters]
+ -[CMITextureStylesSkinSmoothStandalone personData]
+ -[CMITextureStylesSkinSmoothStandalone prepareToProcess:]
+ -[CMITextureStylesSkinSmoothStandalone prewarm]
+ -[CMITextureStylesSkinSmoothStandalone process]
+ -[CMITextureStylesSkinSmoothStandalone purgeResources]
+ -[CMITextureStylesSkinSmoothStandalone regionToRender]
+ -[CMITextureStylesSkinSmoothStandalone resetState]
+ -[CMITextureStylesSkinSmoothStandalone scaleParametersWithIntensity:]
+ -[CMITextureStylesSkinSmoothStandalone setAllocator:]
+ -[CMITextureStylesSkinSmoothStandalone setCameraInfoByPortType:]
+ -[CMITextureStylesSkinSmoothStandalone setFullImageSize:]
+ -[CMITextureStylesSkinSmoothStandalone setInputOutput:]
+ -[CMITextureStylesSkinSmoothStandalone setInstanceID:]
+ -[CMITextureStylesSkinSmoothStandalone setMetalCommandQueue:]
+ -[CMITextureStylesSkinSmoothStandalone setParameters:]
+ -[CMITextureStylesSkinSmoothStandalone setPersonData:]
+ -[CMITextureStylesSkinSmoothStandalone setRegionToRender:]
+ -[CMITextureStylesSkinSmoothStandalone setStreamingMode:]
+ -[CMITextureStylesSkinSmoothStandalone setTuningParameters:]
+ -[CMITextureStylesSkinSmoothStandalone setup]
+ -[CMITextureStylesSkinSmoothStandalone ss_validateFaceSizeAndBlurParameters:fullImageSize:regionToRender:params:]
+ -[CMITextureStylesSkinSmoothStandalone streamingMode]
+ -[CMITextureStylesSkinSmoothStandalone supportsExternalMemoryResource]
+ -[CMITextureStylesSkinSmoothStandalone supportsInPlaceRendering]
+ -[CMITextureStylesSkinSmoothStandalone tuningParameters]
+ -[CMITextureStylesTextureCopy .cxx_destruct]
+ -[CMITextureStylesTextureCopy _compileShaders]
+ -[CMITextureStylesTextureCopy copyFromInputTexture:withInputROI:toOutputTexture:withOutputROI:encodedTo:]
+ -[CMITextureStylesTextureCopy copyFromInputTexture:withInputROI:toOutputTexture:withOutputROI:enqueuedTo:]
+ -[CMITextureStylesTextureCopy initWithMetalContext:]
+ -[CMITextureStylesTextureWarping .cxx_destruct]
+ -[CMITextureStylesTextureWarping _compileShaders]
+ -[CMITextureStylesTextureWarping _shaderForOutputPixelFormat:]
+ -[CMITextureStylesTextureWarping initWithMetalContext:]
+ -[CMITextureStylesTextureWarping processInput:output:triangleVertices:textureCoords:commandBuffer:]
+ -[CMITextureStylesUnderEyeBrighten .cxx_destruct]
+ -[CMITextureStylesUnderEyeBrighten _allocateStatsBuffers]
+ -[CMITextureStylesUnderEyeBrighten _brightenRegion:params:isLeftEye:roi:warpedUnderEyeReferenceMask:statsBuffer:taperedBrightnessMix:yawFactor:filterSigma:commandBuffer:regionToRender:instanceID:]
+ -[CMITextureStylesUnderEyeBrighten _calculateBlurEstimate]
+ -[CMITextureStylesUnderEyeBrighten _calculateStats:warpedUnderEyeReferenceMask:roi:regionToRender:statsBuffer:isLeftEye:commandBuffer:instanceID:]
+ -[CMITextureStylesUnderEyeBrighten _calculateVarianceBasedStrengthTaper:maximumUnimodalVariance:unimodalVarianceFalloff:maximumBimodalVariance:bimodalVarianceFalloff:commandBuffer:instanceID:]
+ -[CMITextureStylesUnderEyeBrighten _compileShaders]
+ -[CMITextureStylesUnderEyeBrighten _createWarpedReferenceMaskFromROI:isLeftEye:referenceMask:triangleVertices:textureCoords:maskFilterSigma:outputMask:commandBuffer:instanceID:]
+ -[CMITextureStylesUnderEyeBrighten _freeWarpedMasksAndStatsForPerson:]
+ -[CMITextureStylesUnderEyeBrighten _popStatsBuffer]
+ -[CMITextureStylesUnderEyeBrighten _removeWarpedMasksAndStatsForPerson:]
+ -[CMITextureStylesUnderEyeBrighten _returnStatsBuffer:]
+ -[CMITextureStylesUnderEyeBrighten allocator]
+ -[CMITextureStylesUnderEyeBrighten calculateStats]
+ -[CMITextureStylesUnderEyeBrighten cameraInfoByPortType]
+ -[CMITextureStylesUnderEyeBrighten computeMinimumInputRegionInFullImageCoords:]
+ -[CMITextureStylesUnderEyeBrighten dealloc]
+ -[CMITextureStylesUnderEyeBrighten finishProcessing]
+ -[CMITextureStylesUnderEyeBrighten fullImageSize]
+ -[CMITextureStylesUnderEyeBrighten initWithOptionalMetalContext:]
+ -[CMITextureStylesUnderEyeBrighten inputOutput]
+ -[CMITextureStylesUnderEyeBrighten instanceID]
+ -[CMITextureStylesUnderEyeBrighten metalCommandQueue]
+ -[CMITextureStylesUnderEyeBrighten parameters]
+ -[CMITextureStylesUnderEyeBrighten personData]
+ -[CMITextureStylesUnderEyeBrighten prepareToProcess:]
+ -[CMITextureStylesUnderEyeBrighten prewarm]
+ -[CMITextureStylesUnderEyeBrighten process]
+ -[CMITextureStylesUnderEyeBrighten purgeResources]
+ -[CMITextureStylesUnderEyeBrighten regionToRender]
+ -[CMITextureStylesUnderEyeBrighten resetState]
+ -[CMITextureStylesUnderEyeBrighten scaleParametersWithIntensity:]
+ -[CMITextureStylesUnderEyeBrighten setAllocator:]
+ -[CMITextureStylesUnderEyeBrighten setCameraInfoByPortType:]
+ -[CMITextureStylesUnderEyeBrighten setFullImageSize:]
+ -[CMITextureStylesUnderEyeBrighten setInputOutput:]
+ -[CMITextureStylesUnderEyeBrighten setInstanceID:]
+ -[CMITextureStylesUnderEyeBrighten setMetalCommandQueue:]
+ -[CMITextureStylesUnderEyeBrighten setParameters:]
+ -[CMITextureStylesUnderEyeBrighten setPersonData:]
+ -[CMITextureStylesUnderEyeBrighten setRegionToRender:]
+ -[CMITextureStylesUnderEyeBrighten setSkipRendering:]
+ -[CMITextureStylesUnderEyeBrighten setTuningParameters:]
+ -[CMITextureStylesUnderEyeBrighten setup]
+ -[CMITextureStylesUnderEyeBrighten skipRendering]
+ -[CMITextureStylesUnderEyeBrighten supportsExternalMemoryResource]
+ -[CMITextureStylesUnderEyeBrighten supportsInPlaceRendering]
+ -[CMITextureStylesUnderEyeBrighten tuningParameters]
+ -[CMITextureStylesUnderEyeBrightenIO .cxx_destruct]
+ -[CMITextureStylesUnderEyeBrightenIO brightnessValue]
+ -[CMITextureStylesUnderEyeBrightenIO inputEarMask]
+ -[CMITextureStylesUnderEyeBrightenIO inputFaceMask]
+ -[CMITextureStylesUnderEyeBrightenIO inputGlassesMask]
+ -[CMITextureStylesUnderEyeBrightenIO inputHairMask]
+ -[CMITextureStylesUnderEyeBrightenIO inputImage]
+ -[CMITextureStylesUnderEyeBrightenIO inputInstanceMask]
+ -[CMITextureStylesUnderEyeBrightenIO inputLipMask]
+ -[CMITextureStylesUnderEyeBrightenIO inputNoseMask]
+ -[CMITextureStylesUnderEyeBrightenIO inputTattooMask]
+ -[CMITextureStylesUnderEyeBrightenIO outputImage]
+ -[CMITextureStylesUnderEyeBrightenIO outputPersonStats]
+ -[CMITextureStylesUnderEyeBrightenIO setBrightnessValue:]
+ -[CMITextureStylesUnderEyeBrightenIO setInputEarMask:]
+ -[CMITextureStylesUnderEyeBrightenIO setInputFaceMask:]
+ -[CMITextureStylesUnderEyeBrightenIO setInputGlassesMask:]
+ -[CMITextureStylesUnderEyeBrightenIO setInputHairMask:]
+ -[CMITextureStylesUnderEyeBrightenIO setInputImage:]
+ -[CMITextureStylesUnderEyeBrightenIO setInputInstanceMask:]
+ -[CMITextureStylesUnderEyeBrightenIO setInputLipMask:]
+ -[CMITextureStylesUnderEyeBrightenIO setInputNoseMask:]
+ -[CMITextureStylesUnderEyeBrightenIO setInputTattooMask:]
+ -[CMITextureStylesUnderEyeBrightenIO setOutputImage:]
+ -[CMITextureStylesUnderEyeBrightenIO setOutputPersonStats:]
+ -[CMITextureStylesUnderEyeBrightenParameters _boolFromDict:key:default:]
+ -[CMITextureStylesUnderEyeBrightenParameters _floatFromDict:key:default:]
+ -[CMITextureStylesUnderEyeBrightenParameters averageColorMix]
+ -[CMITextureStylesUnderEyeBrightenParameters bimodalVarianceFalloff]
+ -[CMITextureStylesUnderEyeBrightenParameters blendConditionFilterScale]
+ -[CMITextureStylesUnderEyeBrightenParameters brightnessMix]
+ -[CMITextureStylesUnderEyeBrightenParameters colorBlendFilterScale]
+ -[CMITextureStylesUnderEyeBrightenParameters copyWithZone:]
+ -[CMITextureStylesUnderEyeBrightenParameters dominantYawTapering]
+ -[CMITextureStylesUnderEyeBrightenParameters hueMaskFilterScale]
+ -[CMITextureStylesUnderEyeBrightenParameters initWithTuningDictionary:]
+ -[CMITextureStylesUnderEyeBrightenParameters init]
+ -[CMITextureStylesUnderEyeBrightenParameters maskThreshold]
+ -[CMITextureStylesUnderEyeBrightenParameters maxDarknessTrigger]
+ -[CMITextureStylesUnderEyeBrightenParameters maxFaceFrac]
+ -[CMITextureStylesUnderEyeBrightenParameters maxHueTolerance]
+ -[CMITextureStylesUnderEyeBrightenParameters maximumBimodalVariance]
+ -[CMITextureStylesUnderEyeBrightenParameters maximumUnimodalVariance]
+ -[CMITextureStylesUnderEyeBrightenParameters minDarknessTrigger]
+ -[CMITextureStylesUnderEyeBrightenParameters minFaceFrac]
+ -[CMITextureStylesUnderEyeBrightenParameters minHueTolerance]
+ -[CMITextureStylesUnderEyeBrightenParameters minTextureAddBack]
+ -[CMITextureStylesUnderEyeBrightenParameters nightModeSharpness]
+ -[CMITextureStylesUnderEyeBrightenParameters nightMode]
+ -[CMITextureStylesUnderEyeBrightenParameters regionMaskThreshold]
+ -[CMITextureStylesUnderEyeBrightenParameters setAverageColorMix:]
+ -[CMITextureStylesUnderEyeBrightenParameters setBimodalVarianceFalloff:]
+ -[CMITextureStylesUnderEyeBrightenParameters setBlendConditionFilterScale:]
+ -[CMITextureStylesUnderEyeBrightenParameters setBrightnessMix:]
+ -[CMITextureStylesUnderEyeBrightenParameters setColorBlendFilterScale:]
+ -[CMITextureStylesUnderEyeBrightenParameters setDefaults]
+ -[CMITextureStylesUnderEyeBrightenParameters setDominantYawTapering:]
+ -[CMITextureStylesUnderEyeBrightenParameters setHueMaskFilterScale:]
+ -[CMITextureStylesUnderEyeBrightenParameters setMaskThreshold:]
+ -[CMITextureStylesUnderEyeBrightenParameters setMaxDarknessTrigger:]
+ -[CMITextureStylesUnderEyeBrightenParameters setMaxFaceFrac:]
+ -[CMITextureStylesUnderEyeBrightenParameters setMaxHueTolerance:]
+ -[CMITextureStylesUnderEyeBrightenParameters setMaximumBimodalVariance:]
+ -[CMITextureStylesUnderEyeBrightenParameters setMaximumUnimodalVariance:]
+ -[CMITextureStylesUnderEyeBrightenParameters setMinDarknessTrigger:]
+ -[CMITextureStylesUnderEyeBrightenParameters setMinFaceFrac:]
+ -[CMITextureStylesUnderEyeBrightenParameters setMinHueTolerance:]
+ -[CMITextureStylesUnderEyeBrightenParameters setMinTextureAddBack:]
+ -[CMITextureStylesUnderEyeBrightenParameters setNightMode:]
+ -[CMITextureStylesUnderEyeBrightenParameters setNightModeSharpness:]
+ -[CMITextureStylesUnderEyeBrightenParameters setRegionMaskThreshold:]
+ -[CMITextureStylesUnderEyeBrightenParameters setTextureAddBackFilterScale:]
+ -[CMITextureStylesUnderEyeBrightenParameters setTextureAddBackScale:]
+ -[CMITextureStylesUnderEyeBrightenParameters setUnimodalVarianceFalloff:]
+ -[CMITextureStylesUnderEyeBrightenParameters setYawFallOff:]
+ -[CMITextureStylesUnderEyeBrightenParameters setYawOffset:]
+ -[CMITextureStylesUnderEyeBrightenParameters textureAddBackFilterScale]
+ -[CMITextureStylesUnderEyeBrightenParameters textureAddBackScale]
+ -[CMITextureStylesUnderEyeBrightenParameters unimodalVarianceFalloff]
+ -[CMITextureStylesUnderEyeBrightenParameters validate]
+ -[CMITextureStylesUnderEyeBrightenParameters yawFallOff]
+ -[CMITextureStylesUnderEyeBrightenParameters yawOffset]
+ -[CMITiledInferenceProcessorConfig bufferCountDualANE]
+ -[CMITiledInferenceProcessorConfig setBufferCountDualANE:]
+ -[NSArray(CMILCB) arrayContainingDictionaryRepresentations]
+ CMCaptureLibrary
+ CMCaptureLibraryCore.frameworkLibrary
+ CMITSpointDenormalizedToRect
+ CMITSpointNormalizedToRect
+ GCC_except_table111
+ GCC_except_table115
+ GCC_except_table22
+ GCC_except_table30
+ GCC_except_table34
+ GCC_except_table47
+ GCC_except_table51
+ GCC_except_table95
+ GCC_except_table96
+ GCC_except_table98
+ GCC_except_table99
+ OBJC_IVAR_$_CMILCBDatabase._detectionIteration
+ OBJC_IVAR_$_CMILCBDatabase._entriesByKey
+ OBJC_IVAR_$_CMILCBDatabase._moduleSerial
+ OBJC_IVAR_$_CMILCBDatabase._sensorID
+ OBJC_IVAR_$_CMILCBEntry._apertureRatio
+ OBJC_IVAR_$_CMILCBEntry._correctionFeatures
+ OBJC_IVAR_$_CMILCBEntry._defocusRadius
+ OBJC_IVAR_$_CMILCBEntry._detectionCount
+ OBJC_IVAR_$_CMILCBEntry._focusLensPosition
+ OBJC_IVAR_$_CMILCBEntry._key
+ OBJC_IVAR_$_CMILCBEntry._lastDetectionGravityVector
+ OBJC_IVAR_$_CMILCBEntry._lastDetectionTimeStamp
+ OBJC_IVAR_$_CMILCBEntry._maxCorrectionFeatureValue
+ OBJC_IVAR_$_CMILCBEntry._minCorrectionFeatureValue
+ OBJC_IVAR_$_CMILCBEntry._oisShift
+ OBJC_IVAR_$_CMILCBEntry._opticalCenter
+ OBJC_IVAR_$_CMILCBEntry._particleDistance
+ OBJC_IVAR_$_CMILCBEntry._position
+ OBJC_IVAR_$_CMILCBEntry._radius
+ OBJC_IVAR_$_CMILCBEntry._relativeToLens
+ OBJC_IVAR_$_CMILCBEntry._shouldCorrect
+ OBJC_IVAR_$_CMISmartStyleUtilitiesV1._enableDeltaMapDetailEnhancement
+ OBJC_IVAR_$_CMISmartStyleUtilitiesV1._enhanceDetailDefaults
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._filteredGFSigma
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._inputFaceNormalizedRects
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._inputSkinMaskFlipHorizontal
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._inputSkinMaskFlipVertical
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._inputSkinMaskICR
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._inputSkinMaskPCR
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._inputSkinMaskRotationDegrees
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._inputSkinMaskTexture
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._inputSkinSmoothingParameters
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._proxyCoeff
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._proxyMean
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._skinSmoothGuidedAvgPipeline
+ OBJC_IVAR_$_CMIStyleEngineApplyStyle._skinSmoothGuidedCoeffPipeline
+ OBJC_IVAR_$_CMIStyleEngineProcessor._inputFaceNormalizedRects
+ OBJC_IVAR_$_CMIStyleEngineProcessor._inputSkinMaskFlipHorizontal
+ OBJC_IVAR_$_CMIStyleEngineProcessor._inputSkinMaskFlipVertical
+ OBJC_IVAR_$_CMIStyleEngineProcessor._inputSkinMaskICR
+ OBJC_IVAR_$_CMIStyleEngineProcessor._inputSkinMaskPCR
+ OBJC_IVAR_$_CMIStyleEngineProcessor._inputSkinMaskRotationDegrees
+ OBJC_IVAR_$_CMIStyleEngineProcessor._inputSkinMaskTexture
+ OBJC_IVAR_$_CMIStyleEngineProcessor._inputSkinSmoothingParameters
+ OBJC_IVAR_$_CMITSMattifyPerPersonIntermediatesAndStats._extendedFaceROI
+ OBJC_IVAR_$_CMITSMattifyPerPersonIntermediatesAndStats._statsBuffer
+ OBJC_IVAR_$_CMITSMattifyPerPersonIntermediatesAndStats._validMask
+ OBJC_IVAR_$_CMITSMattifyPerPersonIntermediatesAndStats._warpedMaskAggregate
+ OBJC_IVAR_$_CMITSTextureAndFullImageRegion._fullImageRegion
+ OBJC_IVAR_$_CMITSTextureAndFullImageRegion._texture
+ OBJC_IVAR_$_CMITSUEBPerPersonData._eyeROI
+ OBJC_IVAR_$_CMITSUEBPerPersonData._statsBuffer
+ OBJC_IVAR_$_CMITSUEBPerPersonData._warpedReferenceMasks
+ OBJC_IVAR_$_CMITextureStyle._grain
+ OBJC_IVAR_$_CMITextureStyle._intensity
+ OBJC_IVAR_$_CMITextureStyle._preset
+ OBJC_IVAR_$_CMITextureStylesBloom._cameraInfoByPortType
+ OBJC_IVAR_$_CMITextureStylesBloom._colorManagement
+ OBJC_IVAR_$_CMITextureStylesBloom._fullImageSize
+ OBJC_IVAR_$_CMITextureStylesBloom._generateBloomPipelineState
+ OBJC_IVAR_$_CMITextureStylesBloom._inputOutput
+ OBJC_IVAR_$_CMITextureStylesBloom._instanceID
+ OBJC_IVAR_$_CMITextureStylesBloom._metalContext
+ OBJC_IVAR_$_CMITextureStylesBloom._parameters
+ OBJC_IVAR_$_CMITextureStylesBloom._personData
+ OBJC_IVAR_$_CMITextureStylesBloom._regionToRender
+ OBJC_IVAR_$_CMITextureStylesBloom._tuningParameters
+ OBJC_IVAR_$_CMITextureStylesBloomIO._inputImage
+ OBJC_IVAR_$_CMITextureStylesBloomIO._inputSkinMask
+ OBJC_IVAR_$_CMITextureStylesBloomIO._outputImage
+ OBJC_IVAR_$_CMITextureStylesBloomParameters._brightness
+ OBJC_IVAR_$_CMITextureStylesBloomParameters._inputTextureROI
+ OBJC_IVAR_$_CMITextureStylesBloomParameters._lightMapGamma
+ OBJC_IVAR_$_CMITextureStylesBloomParameters._lightMapInvert
+ OBJC_IVAR_$_CMITextureStylesBloomParameters._sigmaGlare
+ OBJC_IVAR_$_CMITextureStylesBloomParameters._skinMask
+ OBJC_IVAR_$_CMITextureStylesBloomParameters._strength
+ OBJC_IVAR_$_CMITextureStylesDiffusion._applyDiffusion
+ OBJC_IVAR_$_CMITextureStylesDiffusion._applyMeteor
+ OBJC_IVAR_$_CMITextureStylesDiffusion._cameraInfoByPortType
+ OBJC_IVAR_$_CMITextureStylesDiffusion._colorManagement
+ OBJC_IVAR_$_CMITextureStylesDiffusion._filterer
+ OBJC_IVAR_$_CMITextureStylesDiffusion._fullImageSize
+ OBJC_IVAR_$_CMITextureStylesDiffusion._inputOutput
+ OBJC_IVAR_$_CMITextureStylesDiffusion._inputRescaled
+ OBJC_IVAR_$_CMITextureStylesDiffusion._instanceID
+ OBJC_IVAR_$_CMITextureStylesDiffusion._metalContext
+ OBJC_IVAR_$_CMITextureStylesDiffusion._meteorMixed
+ OBJC_IVAR_$_CMITextureStylesDiffusion._outputBlurredImage
+ OBJC_IVAR_$_CMITextureStylesDiffusion._parameters
+ OBJC_IVAR_$_CMITextureStylesDiffusion._personData
+ OBJC_IVAR_$_CMITextureStylesDiffusion._regionToRender
+ OBJC_IVAR_$_CMITextureStylesDiffusion._rescale420ToRGBA
+ OBJC_IVAR_$_CMITextureStylesDiffusion._tuningParameters
+ OBJC_IVAR_$_CMITextureStylesDiffusionIO._inputGainMap
+ OBJC_IVAR_$_CMITextureStylesDiffusionIO._inputImage
+ OBJC_IVAR_$_CMITextureStylesDiffusionIO._inputPersonMask
+ OBJC_IVAR_$_CMITextureStylesDiffusionIO._inputSkinMask
+ OBJC_IVAR_$_CMITextureStylesDiffusionIO._outputImage
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._bg
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._bw3Gamma
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._difSat
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._diffuseColor
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._faceTempering
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._fogStrength
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._gaussianBlurSigma
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._grading
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._highlight
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._hueRotate
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._lift
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._maxRGB
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._meteorHeadroom
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._meteorHeadroomMixFactor
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._naturalResolution
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._person
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._saturation
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._shDarken
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._slBG
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._slBright
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._slDark
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._slPerson
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._slSkin
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._softLight
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._spbHL
+ OBJC_IVAR_$_CMITextureStylesDiffusionParameters._strength
+ OBJC_IVAR_$_CMITextureStylesDownSampler._context
+ OBJC_IVAR_$_CMITextureStylesDownSampler._pyramidFactory
+ OBJC_IVAR_$_CMITextureStylesDownSampler._shaders
+ OBJC_IVAR_$_CMITextureStylesEffectDescriptor._parameters
+ OBJC_IVAR_$_CMITextureStylesEffectDescriptor._skipRendering
+ OBJC_IVAR_$_CMITextureStylesEffectDescriptor._type
+ OBJC_IVAR_$_CMITextureStylesFaceLandmark._error
+ OBJC_IVAR_$_CMITextureStylesFaceLandmark._point
+ OBJC_IVAR_$_CMITextureStylesFastGaussian._context
+ OBJC_IVAR_$_CMITextureStylesFastGaussian._shaders
+ OBJC_IVAR_$_CMITextureStylesFilmGrainIO._brightnessValue
+ OBJC_IVAR_$_CMITextureStylesFilmGrainIO._inputImage
+ OBJC_IVAR_$_CMITextureStylesFilmGrainIO._inputPersonImage
+ OBJC_IVAR_$_CMITextureStylesFilmGrainIO._inputSkinImage
+ OBJC_IVAR_$_CMITextureStylesFilmGrainIO._inputSkyImage
+ OBJC_IVAR_$_CMITextureStylesFilmGrainIO._outputImage
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._amplitude
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._amplitudeDecay
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._backgroundStrength
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._bvHigh
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._bvLow
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._bvLowScale
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._contrastBoost
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._darkScale
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._frequencyGap
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._grainBlurRadius
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._grainSelectivity
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._hueMix
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._imageGuidedFilterEpsilon
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._imageGuidedFilterRadius
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._naturalResolution
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._octaves
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._personStrength
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._saturation
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._seed
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._shadowLift
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._skinStrength
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._skyStrength
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._strength
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._tileSize
+ OBJC_IVAR_$_CMITextureStylesFilmGrainParameters._zoom
+ OBJC_IVAR_$_CMITextureStylesFilmGrainProcessorV1._cameraInfoByPortType
+ OBJC_IVAR_$_CMITextureStylesFilmGrainProcessorV1._colorManagement
+ OBJC_IVAR_$_CMITextureStylesFilmGrainProcessorV1._fullImageSize
+ OBJC_IVAR_$_CMITextureStylesFilmGrainProcessorV1._grainBlendPipeline
+ OBJC_IVAR_$_CMITextureStylesFilmGrainProcessorV1._inputOutput
+ OBJC_IVAR_$_CMITextureStylesFilmGrainProcessorV1._instanceID
+ OBJC_IVAR_$_CMITextureStylesFilmGrainProcessorV1._metalContext
+ OBJC_IVAR_$_CMITextureStylesFilmGrainProcessorV1._parameters
+ OBJC_IVAR_$_CMITextureStylesFilmGrainProcessorV1._personData
+ OBJC_IVAR_$_CMITextureStylesFilmGrainProcessorV1._regionToRender
+ OBJC_IVAR_$_CMITextureStylesFilmGrainProcessorV1._tuningParameters
+ OBJC_IVAR_$_CMITextureStylesFilter._context
+ OBJC_IVAR_$_CMITextureStylesFilter._shaders
+ OBJC_IVAR_$_CMITextureStylesGaussianFilter._context
+ OBJC_IVAR_$_CMITextureStylesGaussianFilter._shaders
+ OBJC_IVAR_$_CMITextureStylesGaussianGuidedFilterV3._context
+ OBJC_IVAR_$_CMITextureStylesGaussianGuidedFilterV3._shaders
+ OBJC_IVAR_$_CMITextureStylesGlow._cameraInfoByPortType
+ OBJC_IVAR_$_CMITextureStylesGlow._colorManagement
+ OBJC_IVAR_$_CMITextureStylesGlow._fakeStatsBuffer
+ OBJC_IVAR_$_CMITextureStylesGlow._fillToneCurvePipelineState
+ OBJC_IVAR_$_CMITextureStylesGlow._frameCount
+ OBJC_IVAR_$_CMITextureStylesGlow._fullImageSize
+ OBJC_IVAR_$_CMITextureStylesGlow._generateGlowPipelineState
+ OBJC_IVAR_$_CMITextureStylesGlow._inputOutput
+ OBJC_IVAR_$_CMITextureStylesGlow._instanceID
+ OBJC_IVAR_$_CMITextureStylesGlow._metalContext
+ OBJC_IVAR_$_CMITextureStylesGlow._parameters
+ OBJC_IVAR_$_CMITextureStylesGlow._personData
+ OBJC_IVAR_$_CMITextureStylesGlow._regionToRender
+ OBJC_IVAR_$_CMITextureStylesGlow._streamingMode
+ OBJC_IVAR_$_CMITextureStylesGlow._tuningParameters
+ OBJC_IVAR_$_CMITextureStylesGlowIO._inputImage
+ OBJC_IVAR_$_CMITextureStylesGlowIO._inputLinearImage
+ OBJC_IVAR_$_CMITextureStylesGlowIO._inputLinearMetadata
+ OBJC_IVAR_$_CMITextureStylesGlowIO._inputMask
+ OBJC_IVAR_$_CMITextureStylesGlowIO._outputImage
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._baselineExposure
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._brightness
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._brightnessMask
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._contrast
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._contrastMask
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._gamma
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._gammaMask
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._inputTextureROI
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._lightMapGamma
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._lightMapMax
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._linearImageHighKey
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._linearMixForBG
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._linearMixForSkin
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._preserveColorfulness
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._preserveColorfulnessMask
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._saturation
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._saturationFromSmartStyle
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._saturationMask
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._statistics
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._strength
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._strengthMask
+ OBJC_IVAR_$_CMITextureStylesGlowParameters._useStatistics
+ OBJC_IVAR_$_CMITextureStylesGuidedFilter._context
+ OBJC_IVAR_$_CMITextureStylesGuidedFilter._shaders
+ OBJC_IVAR_$_CMITextureStylesHalation._applyHalation
+ OBJC_IVAR_$_CMITextureStylesHalation._asymLumaMask
+ OBJC_IVAR_$_CMITextureStylesHalation._blurredSubtractMask
+ OBJC_IVAR_$_CMITextureStylesHalation._cameraInfoByPortType
+ OBJC_IVAR_$_CMITextureStylesHalation._colorManagement
+ OBJC_IVAR_$_CMITextureStylesHalation._filterer
+ OBJC_IVAR_$_CMITextureStylesHalation._fullImageSize
+ OBJC_IVAR_$_CMITextureStylesHalation._generateLumAsymMask
+ OBJC_IVAR_$_CMITextureStylesHalation._halationMask
+ OBJC_IVAR_$_CMITextureStylesHalation._inputOutput
+ OBJC_IVAR_$_CMITextureStylesHalation._instanceID
+ OBJC_IVAR_$_CMITextureStylesHalation._metalContext
+ OBJC_IVAR_$_CMITextureStylesHalation._parameters
+ OBJC_IVAR_$_CMITextureStylesHalation._personData
+ OBJC_IVAR_$_CMITextureStylesHalation._regionToRender
+ OBJC_IVAR_$_CMITextureStylesHalation._subtractBlendMode
+ OBJC_IVAR_$_CMITextureStylesHalation._subtractMask
+ OBJC_IVAR_$_CMITextureStylesHalation._tuningParameters
+ OBJC_IVAR_$_CMITextureStylesHalationIO._brightnessValue
+ OBJC_IVAR_$_CMITextureStylesHalationIO._inputGainMap
+ OBJC_IVAR_$_CMITextureStylesHalationIO._inputHDRImage
+ OBJC_IVAR_$_CMITextureStylesHalationIO._inputImage
+ OBJC_IVAR_$_CMITextureStylesHalationIO._inputLightMap
+ OBJC_IVAR_$_CMITextureStylesHalationIO._inputPersonMask
+ OBJC_IVAR_$_CMITextureStylesHalationIO._inputSkinMask
+ OBJC_IVAR_$_CMITextureStylesHalationIO._outputImage
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._bg
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._bvHigh
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._bvLow
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._bvThresholdDeltaLowScale
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._faceTempering
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._halationChroma
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._halationHue
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._inputInnerKnot0
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._inputInnerKnot1
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._inputLowerBound
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._inputLowerCoeffA
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._inputLowerCoeffB
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._inputOuterKnot0
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._inputOuterKnot1
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._inputSpread
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._inputTextureROI
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._inputThresholdDelta
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._inputUpperCoeffA
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._inputUpperCoeffB
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._maskBlurSigma
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._maxRGB
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._meteorHeadroom
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._meteorHeadroomMixFactor
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._naturalResolution
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._person
+ OBJC_IVAR_$_CMITextureStylesHalationParameters._strength
+ OBJC_IVAR_$_CMITextureStylesMattify._blurProcessor
+ OBJC_IVAR_$_CMITextureStylesMattify._cameraInfoByPortType
+ OBJC_IVAR_$_CMITextureStylesMattify._context
+ OBJC_IVAR_$_CMITextureStylesMattify._fullImageSize
+ OBJC_IVAR_$_CMITextureStylesMattify._inputOutput
+ OBJC_IVAR_$_CMITextureStylesMattify._instanceID
+ OBJC_IVAR_$_CMITextureStylesMattify._parameters
+ OBJC_IVAR_$_CMITextureStylesMattify._perPersonIntermediatesAndStats
+ OBJC_IVAR_$_CMITextureStylesMattify._personData
+ OBJC_IVAR_$_CMITextureStylesMattify._pyramidFactory
+ OBJC_IVAR_$_CMITextureStylesMattify._regionToRender
+ OBJC_IVAR_$_CMITextureStylesMattify._shadersWithConstants
+ OBJC_IVAR_$_CMITextureStylesMattify._shadersWithoutConstants
+ OBJC_IVAR_$_CMITextureStylesMattify._skipRendering
+ OBJC_IVAR_$_CMITextureStylesMattify._streamingMode
+ OBJC_IVAR_$_CMITextureStylesMattify._textureCopier
+ OBJC_IVAR_$_CMITextureStylesMattify._tuningParameters
+ OBJC_IVAR_$_CMITextureStylesMattify._warper
+ OBJC_IVAR_$_CMITextureStylesMattifyIO._inputEarMask
+ OBJC_IVAR_$_CMITextureStylesMattifyIO._inputFaceMask
+ OBJC_IVAR_$_CMITextureStylesMattifyIO._inputGlassesMask
+ OBJC_IVAR_$_CMITextureStylesMattifyIO._inputImage
+ OBJC_IVAR_$_CMITextureStylesMattifyIO._inputInstanceMask
+ OBJC_IVAR_$_CMITextureStylesMattifyIO._inputLipsMask
+ OBJC_IVAR_$_CMITextureStylesMattifyIO._inputNoseMask
+ OBJC_IVAR_$_CMITextureStylesMattifyIO._inputSkinMask
+ OBJC_IVAR_$_CMITextureStylesMattifyIO._inputTattoosMask
+ OBJC_IVAR_$_CMITextureStylesMattifyIO._outputImage
+ OBJC_IVAR_$_CMITextureStylesMattifyIO._outputPersonStats
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._blendColorImageAverageColorMixFactor
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._darknessDiffSmoothstepLowerBound
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._darknessDiffSmoothstepUpperBound
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._editingStrength
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._fracMaskHighlightsHeadroom
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._fracMaskHighlightsNormFactor
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._hueDiffMeanTermSmoothstepLowerBound
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._hueDiffMeanTermSmoothstepUpperBound
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._hueDiffSmoothstepLowerBound
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._hueDiffSmoothstepUpperBound
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._imageTextureFactor
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._imageTextureThreshold
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._largeBlurRadiusFaceDiagonalFactor
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._lightnessEditFactor
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._lightnessEditHeadroom
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._smallBlurRadiusFaceDiagonalFactor
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._textureRestoreScalingFactor
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._textureRestoreSmoothstepLowerBound
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._textureRestoreSmoothstepUpperBound
+ OBJC_IVAR_$_CMITextureStylesMattifyParameters._textureRestoreStrengthFactor
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._faceID
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._faceLandmarkType
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._faceLandmarks
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._facePitch
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._faceROI
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._faceROIAndLandmarksROIRelativeScalingROI
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._faceRoll
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._faceSkinROI
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._faceYaw
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._imageStats
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._instanceMask
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._instanceMaskReferenceKey
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._instanceROI
+ OBJC_IVAR_$_CMITextureStylesPersonInputData._unitOfAngle
+ OBJC_IVAR_$_CMITextureStylesProcessor._bloom
+ OBJC_IVAR_$_CMITextureStylesProcessor._brightnessValue
+ OBJC_IVAR_$_CMITextureStylesProcessor._bufferCache
+ OBJC_IVAR_$_CMITextureStylesProcessor._cameraInfoByPortType
+ OBJC_IVAR_$_CMITextureStylesProcessor._diffusion
+ OBJC_IVAR_$_CMITextureStylesProcessor._effectsToRender
+ OBJC_IVAR_$_CMITextureStylesProcessor._enableSkinSmoothingMultiPersonBlending
+ OBJC_IVAR_$_CMITextureStylesProcessor._externalMemoryResource
+ OBJC_IVAR_$_CMITextureStylesProcessor._filmGrain
+ OBJC_IVAR_$_CMITextureStylesProcessor._fullImageSize
+ OBJC_IVAR_$_CMITextureStylesProcessor._glow
+ OBJC_IVAR_$_CMITextureStylesProcessor._halation
+ OBJC_IVAR_$_CMITextureStylesProcessor._inputImage
+ OBJC_IVAR_$_CMITextureStylesProcessor._inputLinearImage
+ OBJC_IVAR_$_CMITextureStylesProcessor._inputLinearImageMetadata
+ OBJC_IVAR_$_CMITextureStylesProcessor._inputMasks
+ OBJC_IVAR_$_CMITextureStylesProcessor._inputMeteorGainMap
+ OBJC_IVAR_$_CMITextureStylesProcessor._inputPersonData
+ OBJC_IVAR_$_CMITextureStylesProcessor._inputPingPongImageForRendering
+ OBJC_IVAR_$_CMITextureStylesProcessor._inputSkinSmoothingFaceDetections
+ OBJC_IVAR_$_CMITextureStylesProcessor._label
+ OBJC_IVAR_$_CMITextureStylesProcessor._mattify
+ OBJC_IVAR_$_CMITextureStylesProcessor._memoryResource
+ OBJC_IVAR_$_CMITextureStylesProcessor._metalContext
+ OBJC_IVAR_$_CMITextureStylesProcessor._outputImage
+ OBJC_IVAR_$_CMITextureStylesProcessor._outputPersonImageStats
+ OBJC_IVAR_$_CMITextureStylesProcessor._outputSkinSmoothingLargeBlurGuidedFilterA
+ OBJC_IVAR_$_CMITextureStylesProcessor._outputSkinSmoothingLargeBlurGuidedFilterB
+ OBJC_IVAR_$_CMITextureStylesProcessor._outputSkinSmoothingProcessedMask
+ OBJC_IVAR_$_CMITextureStylesProcessor._outputSkinSmoothingSmallBlur
+ OBJC_IVAR_$_CMITextureStylesProcessor._outputSkinSmoothingStats
+ OBJC_IVAR_$_CMITextureStylesProcessor._outputSkinSmoothingTextureAddback
+ OBJC_IVAR_$_CMITextureStylesProcessor._regionToRender
+ OBJC_IVAR_$_CMITextureStylesProcessor._shouldFlushCVMTLCachesOnResetState
+ OBJC_IVAR_$_CMITextureStylesProcessor._skinSmoothStandalone
+ OBJC_IVAR_$_CMITextureStylesProcessor._streamingMode
+ OBJC_IVAR_$_CMITextureStylesProcessor._textureCache
+ OBJC_IVAR_$_CMITextureStylesProcessor._textureCopier
+ OBJC_IVAR_$_CMITextureStylesProcessor._textureStyleIntensity
+ OBJC_IVAR_$_CMITextureStylesProcessor._tuningParameters
+ OBJC_IVAR_$_CMITextureStylesProcessor._underEyeBrighten
+ OBJC_IVAR_$_CMITextureStylesPyramid._levels
+ OBJC_IVAR_$_CMITextureStylesPyramidFactory._context
+ OBJC_IVAR_$_CMITextureStylesPyramidFactory._shaders
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._allPersonDataForBlending
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._bodyMaskTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._brightnessValue
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._earsMaskTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._externalFaceRoughnessStatsOutput
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._externalLargeBlurGuidedFilterAOutput
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._externalLargeBlurGuidedFilterBOutput
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._externalSmallBlurOutput
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._externalTextureAddbackOutput
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._eyebrowsMaskTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._faceSkinMaskTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._glassesMaskTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._hairMaskTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._handsMaskTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._inputFaceRect
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._inputImage
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._inputSkinMaskAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._instanceMaskTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._lipsMaskTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._outputImage
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._outputPersonStats
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._outputProcessedSkinMask
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._personMaskTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._tattoosMaskTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothIO._teethMaskTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._degrunge
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._degrungeBody
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._detailSize
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._enableTextureAddback
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._eyeProtection
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._eyebrows
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._fastMode
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._gFContrast
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._gFRadius
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._hairClothes
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._hairTxFloor
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._handsAndEars
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._highlightRetention
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._hlBlurStrength
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._hlTextureRestore
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._lipContrast
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._lipCrease
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._lipHighlights
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._lipNegClar
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._maxDarknessTrigger
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._minDarknessTrigger
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._minTexture
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._nightMode
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._nightModeSharpness
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._plusGreenGuide
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._pores
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._poresBody
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._roughSamples
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._strongTextureProtect
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._tattooSmoothing
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._tattooWeight
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._teeth
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._textureClamp
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._textureDetectScale
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._textureRestore
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothParameters._varTexture
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._applyBlobToSingleFace
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._blurredTextureAmountTexture
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._cameraInfoByPortType
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._context
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._downSampler
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._enableMultiPersonBlending
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._filterer
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._fullImageSize
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._guidedFilterATextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._guidedFilterBTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._inputOutput
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._instanceID
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._internalProcessedSkinMask
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._parameters
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._personData
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._regionToRender
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._shaders
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._skipLargeBlurCompute
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._skipSmallBlurCompute
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._smallBlurTextureAndFullImageRegion
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._statsBuffer
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._statsBufferPool
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._streamingMode
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._syntheticSkinTexture
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._textureCopier
+ OBJC_IVAR_$_CMITextureStylesSkinSmoothStandalone._tuningParameters
+ OBJC_IVAR_$_CMITextureStylesTextureCopy._context
+ OBJC_IVAR_$_CMITextureStylesTextureCopy._shaders
+ OBJC_IVAR_$_CMITextureStylesTextureWarping._context
+ OBJC_IVAR_$_CMITextureStylesTextureWarping._shaders
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._cameraInfoByPortType
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._context
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._downSampler
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._filterer
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._fullImageSize
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._inputOutput
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._instanceID
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._parameters
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._perPersonData
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._personData
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._regionToRender
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._shaders
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._skipRendering
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._statsBuffers
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._textureCopier
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._tuningParameters
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrighten._warper
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenIO._brightnessValue
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenIO._inputEarMask
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenIO._inputFaceMask
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenIO._inputGlassesMask
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenIO._inputHairMask
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenIO._inputImage
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenIO._inputInstanceMask
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenIO._inputLipMask
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenIO._inputNoseMask
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenIO._inputTattooMask
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenIO._outputImage
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenIO._outputPersonStats
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._averageColorMix
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._bimodalVarianceFalloff
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._blendConditionFilterScale
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._brightnessMix
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._colorBlendFilterScale
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._dominantYawTapering
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._hueMaskFilterScale
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._maskThreshold
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._maxDarknessTrigger
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._maxFaceFrac
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._maxHueTolerance
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._maximumBimodalVariance
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._maximumUnimodalVariance
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._minDarknessTrigger
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._minFaceFrac
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._minHueTolerance
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._minTextureAddBack
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._nightMode
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._nightModeSharpness
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._regionMaskThreshold
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._textureAddBackFilterScale
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._textureAddBackScale
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._unimodalVarianceFalloff
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._yawFallOff
+ OBJC_IVAR_$_CMITextureStylesUnderEyeBrightenParameters._yawOffset
+ OBJC_IVAR_$_CMITiledInferenceProcessorConfig._bufferCountDualANE
+ _CGPointZero
+ _CGRectIntersectsRect
+ _CGRectUnion
+ _CMCaptureLibrary
+ _CMITSdiagonalLengthOfSize
+ _CMITSfullImageRectToTextureRect
+ _CMITSidealDispatchSize
+ _CMITSidealThreadGroupSize
+ _CMITSpointDenormalizedToRect
+ _CMITSpointNormalizedToRect
+ _CMITSrectDenormalizedToRect
+ _CMITSrectExpandedByPadding
+ _CMITSrectNormalizedToRect
+ _CMITSsetTextureAndNormalizedRectOnEncoder
+ _CMITStexturesAreIdentical
+ _CMITextureStylePresetNameFilmic
+ _CMITextureStylePresetNameGlowy
+ _CMITextureStylePresetNameSoft
+ _CMITextureStylePresetNameStandard
+ _CMITextureStylePresetNameStudio
+ _FASTGAUSSIAN_NOTE_VARIABLE
+ _FigGetCFPreferenceBooleanWithDefault
+ _GUIDEDFILTERV3_NOTE_VARIABLE
+ _NSStringFromClass
+ _OBJC_CLASS_$_CMILCBDatabase
+ _OBJC_CLASS_$_CMILCBEntry
+ _OBJC_CLASS_$_CMITSMattifyPerPersonIntermediatesAndStats
+ _OBJC_CLASS_$_CMITSTextureAndFullImageRegion
+ _OBJC_CLASS_$_CMITSUEBPerPersonData
+ _OBJC_CLASS_$_CMITextureStyle
+ _OBJC_CLASS_$_CMITextureStyleTuningLookup
+ _OBJC_CLASS_$_CMITextureStylesBloom
+ _OBJC_CLASS_$_CMITextureStylesBloomIO
+ _OBJC_CLASS_$_CMITextureStylesBloomParameters
+ _OBJC_CLASS_$_CMITextureStylesDiffusion
+ _OBJC_CLASS_$_CMITextureStylesDiffusionIO
+ _OBJC_CLASS_$_CMITextureStylesDiffusionParameters
+ _OBJC_CLASS_$_CMITextureStylesDownSampler
+ _OBJC_CLASS_$_CMITextureStylesEffectDescriptor
+ _OBJC_CLASS_$_CMITextureStylesFaceLandmark
+ _OBJC_CLASS_$_CMITextureStylesFastGaussian
+ _OBJC_CLASS_$_CMITextureStylesFilmGrainIO
+ _OBJC_CLASS_$_CMITextureStylesFilmGrainParameters
+ _OBJC_CLASS_$_CMITextureStylesFilmGrainProcessorV1
+ _OBJC_CLASS_$_CMITextureStylesFilter
+ _OBJC_CLASS_$_CMITextureStylesGaussianFilter
+ _OBJC_CLASS_$_CMITextureStylesGaussianGuidedFilterV3
+ _OBJC_CLASS_$_CMITextureStylesGlow
+ _OBJC_CLASS_$_CMITextureStylesGlowIO
+ _OBJC_CLASS_$_CMITextureStylesGlowParameters
+ _OBJC_CLASS_$_CMITextureStylesGuidedFilter
+ _OBJC_CLASS_$_CMITextureStylesHalation
+ _OBJC_CLASS_$_CMITextureStylesHalationIO
+ _OBJC_CLASS_$_CMITextureStylesHalationParameters
+ _OBJC_CLASS_$_CMITextureStylesMattify
+ _OBJC_CLASS_$_CMITextureStylesMattifyIO
+ _OBJC_CLASS_$_CMITextureStylesMattifyParameters
+ _OBJC_CLASS_$_CMITextureStylesPersonInputData
+ _OBJC_CLASS_$_CMITextureStylesPersonInputDataUtilities
+ _OBJC_CLASS_$_CMITextureStylesProcessor
+ _OBJC_CLASS_$_CMITextureStylesPyramid
+ _OBJC_CLASS_$_CMITextureStylesPyramidFactory
+ _OBJC_CLASS_$_CMITextureStylesSkinSmoothIO
+ _OBJC_CLASS_$_CMITextureStylesSkinSmoothParameters
+ _OBJC_CLASS_$_CMITextureStylesSkinSmoothStandalone
+ _OBJC_CLASS_$_CMITextureStylesTextureCopy
+ _OBJC_CLASS_$_CMITextureStylesTextureWarping
+ _OBJC_CLASS_$_CMITextureStylesUnderEyeBrighten
+ _OBJC_CLASS_$_CMITextureStylesUnderEyeBrightenIO
+ _OBJC_CLASS_$_CMITextureStylesUnderEyeBrightenParameters
+ _OBJC_CLASS_$_MTLRenderPipelineColorAttachmentDescriptor
+ _OBJC_CLASS_$_NSConstantFloatNumber
+ _OBJC_CLASS_$_NSPredicate
+ _OBJC_METACLASS_$_CMILCBDatabase
+ _OBJC_METACLASS_$_CMILCBEntry
+ _OBJC_METACLASS_$_CMITSMattifyPerPersonIntermediatesAndStats
+ _OBJC_METACLASS_$_CMITSTextureAndFullImageRegion
+ _OBJC_METACLASS_$_CMITSUEBPerPersonData
+ _OBJC_METACLASS_$_CMITextureStyle
+ _OBJC_METACLASS_$_CMITextureStyleTuningLookup
+ _OBJC_METACLASS_$_CMITextureStylesBloom
+ _OBJC_METACLASS_$_CMITextureStylesBloomIO
+ _OBJC_METACLASS_$_CMITextureStylesBloomParameters
+ _OBJC_METACLASS_$_CMITextureStylesDiffusion
+ _OBJC_METACLASS_$_CMITextureStylesDiffusionIO
+ _OBJC_METACLASS_$_CMITextureStylesDiffusionParameters
+ _OBJC_METACLASS_$_CMITextureStylesDownSampler
+ _OBJC_METACLASS_$_CMITextureStylesEffectDescriptor
+ _OBJC_METACLASS_$_CMITextureStylesFaceLandmark
+ _OBJC_METACLASS_$_CMITextureStylesFastGaussian
+ _OBJC_METACLASS_$_CMITextureStylesFilmGrainIO
+ _OBJC_METACLASS_$_CMITextureStylesFilmGrainParameters
+ _OBJC_METACLASS_$_CMITextureStylesFilmGrainProcessorV1
+ _OBJC_METACLASS_$_CMITextureStylesFilter
+ _OBJC_METACLASS_$_CMITextureStylesGaussianFilter
+ _OBJC_METACLASS_$_CMITextureStylesGaussianGuidedFilterV3
+ _OBJC_METACLASS_$_CMITextureStylesGlow
+ _OBJC_METACLASS_$_CMITextureStylesGlowIO
+ _OBJC_METACLASS_$_CMITextureStylesGlowParameters
+ _OBJC_METACLASS_$_CMITextureStylesGuidedFilter
+ _OBJC_METACLASS_$_CMITextureStylesHalation
+ _OBJC_METACLASS_$_CMITextureStylesHalationIO
+ _OBJC_METACLASS_$_CMITextureStylesHalationParameters
+ _OBJC_METACLASS_$_CMITextureStylesMattify
+ _OBJC_METACLASS_$_CMITextureStylesMattifyIO
+ _OBJC_METACLASS_$_CMITextureStylesMattifyParameters
+ _OBJC_METACLASS_$_CMITextureStylesPersonInputData
+ _OBJC_METACLASS_$_CMITextureStylesPersonInputDataUtilities
+ _OBJC_METACLASS_$_CMITextureStylesProcessor
+ _OBJC_METACLASS_$_CMITextureStylesPyramid
+ _OBJC_METACLASS_$_CMITextureStylesPyramidFactory
+ _OBJC_METACLASS_$_CMITextureStylesSkinSmoothIO
+ _OBJC_METACLASS_$_CMITextureStylesSkinSmoothParameters
+ _OBJC_METACLASS_$_CMITextureStylesSkinSmoothStandalone
+ _OBJC_METACLASS_$_CMITextureStylesTextureCopy
+ _OBJC_METACLASS_$_CMITextureStylesTextureWarping
+ _OBJC_METACLASS_$_CMITextureStylesUnderEyeBrighten
+ _OBJC_METACLASS_$_CMITextureStylesUnderEyeBrightenIO
+ _OBJC_METACLASS_$_CMITextureStylesUnderEyeBrightenParameters
+ _OUTLINED_FUNCTION_100
+ _OUTLINED_FUNCTION_101
+ _OUTLINED_FUNCTION_102
+ _OUTLINED_FUNCTION_103
+ _OUTLINED_FUNCTION_104
+ _OUTLINED_FUNCTION_105
+ _OUTLINED_FUNCTION_106
+ _OUTLINED_FUNCTION_107
+ _OUTLINED_FUNCTION_108
+ _OUTLINED_FUNCTION_109
+ _OUTLINED_FUNCTION_110
+ _OUTLINED_FUNCTION_111
+ _OUTLINED_FUNCTION_112
+ _OUTLINED_FUNCTION_113
+ _OUTLINED_FUNCTION_114
+ _OUTLINED_FUNCTION_115
+ _OUTLINED_FUNCTION_116
+ _OUTLINED_FUNCTION_117
+ _OUTLINED_FUNCTION_118
+ _OUTLINED_FUNCTION_119
+ _OUTLINED_FUNCTION_120
+ _OUTLINED_FUNCTION_121
+ _OUTLINED_FUNCTION_122
+ _OUTLINED_FUNCTION_123
+ _OUTLINED_FUNCTION_124
+ _OUTLINED_FUNCTION_125
+ _OUTLINED_FUNCTION_126
+ _OUTLINED_FUNCTION_127
+ _OUTLINED_FUNCTION_128
+ _OUTLINED_FUNCTION_129
+ _OUTLINED_FUNCTION_130
+ _OUTLINED_FUNCTION_131
+ _OUTLINED_FUNCTION_132
+ _OUTLINED_FUNCTION_36
+ _OUTLINED_FUNCTION_37
+ _OUTLINED_FUNCTION_38
+ _OUTLINED_FUNCTION_39
+ _OUTLINED_FUNCTION_40
+ _OUTLINED_FUNCTION_41
+ _OUTLINED_FUNCTION_42
+ _OUTLINED_FUNCTION_43
+ _OUTLINED_FUNCTION_44
+ _OUTLINED_FUNCTION_45
+ _OUTLINED_FUNCTION_46
+ _OUTLINED_FUNCTION_47
+ _OUTLINED_FUNCTION_48
+ _OUTLINED_FUNCTION_49
+ _OUTLINED_FUNCTION_50
+ _OUTLINED_FUNCTION_51
+ _OUTLINED_FUNCTION_52
+ _OUTLINED_FUNCTION_53
+ _OUTLINED_FUNCTION_54
+ _OUTLINED_FUNCTION_55
+ _OUTLINED_FUNCTION_56
+ _OUTLINED_FUNCTION_57
+ _OUTLINED_FUNCTION_58
+ _OUTLINED_FUNCTION_59
+ _OUTLINED_FUNCTION_60
+ _OUTLINED_FUNCTION_61
+ _OUTLINED_FUNCTION_62
+ _OUTLINED_FUNCTION_63
+ _OUTLINED_FUNCTION_64
+ _OUTLINED_FUNCTION_65
+ _OUTLINED_FUNCTION_66
+ _OUTLINED_FUNCTION_67
+ _OUTLINED_FUNCTION_68
+ _OUTLINED_FUNCTION_69
+ _OUTLINED_FUNCTION_70
+ _OUTLINED_FUNCTION_71
+ _OUTLINED_FUNCTION_72
+ _OUTLINED_FUNCTION_73
+ _OUTLINED_FUNCTION_75
+ _OUTLINED_FUNCTION_76
+ _OUTLINED_FUNCTION_77
+ _OUTLINED_FUNCTION_78
+ _OUTLINED_FUNCTION_79
+ _OUTLINED_FUNCTION_80
+ _OUTLINED_FUNCTION_81
+ _OUTLINED_FUNCTION_82
+ _OUTLINED_FUNCTION_83
+ _OUTLINED_FUNCTION_84
+ _OUTLINED_FUNCTION_85
+ _OUTLINED_FUNCTION_86
+ _OUTLINED_FUNCTION_87
+ _OUTLINED_FUNCTION_88
+ _OUTLINED_FUNCTION_89
+ _OUTLINED_FUNCTION_90
+ _OUTLINED_FUNCTION_91
+ _OUTLINED_FUNCTION_92
+ _OUTLINED_FUNCTION_93
+ _OUTLINED_FUNCTION_94
+ _OUTLINED_FUNCTION_95
+ _OUTLINED_FUNCTION_96
+ _OUTLINED_FUNCTION_97
+ _OUTLINED_FUNCTION_98
+ _OUTLINED_FUNCTION_99
+ _ZL26tsf_findBestRadiusAndScale6CGSizefPi.onceToken
+ _ZL26tsf_findBestRadiusAndScale6CGSizefPi.sortedFilterRadii
+ _ZL26tsf_findBestRadiusAndScaleP7NSArrayIP8NSNumberEffPimm
+ __123-[CMITextureStylesMattify _calculateExtendedFaceROI:leftCheekROI:rightCheekROI:triangleVerticesLeft:triangleVerticesRight:]_block_invoke
+ __161+[CMITextureStylesPersonInputDataUtilities personInputDataArrayFromLivePhotoMetadataAndStatsTracks:faceAttitudesMetadataTrack:effectsStatsTrack:effectsToRender:]_block_invoke
+ __161+[CMITextureStylesPersonInputDataUtilities personInputDataArrayFromLivePhotoMetadataAndStatsTracks:faceAttitudesMetadataTrack:effectsStatsTrack:effectsToRender:]_block_invoke_2
+ __161+[CMITextureStylesPersonInputDataUtilities personInputDataArrayFromLivePhotoMetadataAndStatsTracks:faceAttitudesMetadataTrack:effectsStatsTrack:effectsToRender:]_block_invoke_3
+ __34-[CMITextureStylesMattify process]_block_invoke
+ __43-[CMITextureStylesUnderEyeBrighten process]_block_invoke
+ __47-[CMITextureStylesSkinSmoothStandalone process]_block_invoke
+ __64-[CMITextureStylesProcessor _createEffectProcessorsAndUtilities]_block_invoke
+ __MergedGlobals
+ __OBJC_$_CATEGORY_NSArray_$_CMILCB
+ __OBJC_$_CLASS_METHODS_CMILCBDatabase
+ __OBJC_$_CLASS_METHODS_CMILCBEntry
+ __OBJC_$_CLASS_METHODS_CMITextureStyle
+ __OBJC_$_CLASS_METHODS_CMITextureStyleTuningLookup
+ __OBJC_$_CLASS_METHODS_CMITextureStylesBloom
+ __OBJC_$_CLASS_METHODS_CMITextureStylesDiffusion
+ __OBJC_$_CLASS_METHODS_CMITextureStylesFaceLandmark
+ __OBJC_$_CLASS_METHODS_CMITextureStylesFastGaussian
+ __OBJC_$_CLASS_METHODS_CMITextureStylesFilmGrainProcessorV1
+ __OBJC_$_CLASS_METHODS_CMITextureStylesFilter
+ __OBJC_$_CLASS_METHODS_CMITextureStylesGaussianGuidedFilterV3
+ __OBJC_$_CLASS_METHODS_CMITextureStylesGlow
+ __OBJC_$_CLASS_METHODS_CMITextureStylesGuidedFilter
+ __OBJC_$_CLASS_METHODS_CMITextureStylesHalation
+ __OBJC_$_CLASS_METHODS_CMITextureStylesMattify
+ __OBJC_$_CLASS_METHODS_CMITextureStylesPersonInputData
+ __OBJC_$_CLASS_METHODS_CMITextureStylesPersonInputDataUtilities
+ __OBJC_$_CLASS_METHODS_CMITextureStylesProcessor
+ __OBJC_$_CLASS_METHODS_CMITextureStylesSkinSmoothStandalone
+ __OBJC_$_CLASS_METHODS_CMITextureStylesUnderEyeBrighten
+ __OBJC_$_CLASS_PROP_LIST_CMILCBDatabase
+ __OBJC_$_CLASS_PROP_LIST_CMILCBEntry
+ __OBJC_$_CLASS_PROP_LIST_CMITextureStylesGuidedFilter
+ __OBJC_$_CLASS_PROP_LIST_CMITextureStylesProcessor
+ __OBJC_$_INSTANCE_METHODS_CMILCBDatabase
+ __OBJC_$_INSTANCE_METHODS_CMILCBEntry
+ __OBJC_$_INSTANCE_METHODS_CMITSMattifyPerPersonIntermediatesAndStats
+ __OBJC_$_INSTANCE_METHODS_CMITSTextureAndFullImageRegion
+ __OBJC_$_INSTANCE_METHODS_CMITSUEBPerPersonData
+ __OBJC_$_INSTANCE_METHODS_CMITextureStyle
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesBloom
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesBloomIO
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesBloomParameters
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesDiffusion
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesDiffusionIO
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesDiffusionParameters
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesDownSampler
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesEffectDescriptor
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesFaceLandmark
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesFastGaussian
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesFilmGrainIO
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesFilmGrainParameters
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesFilmGrainProcessorV1
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesFilter
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesGaussianFilter
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesGaussianGuidedFilterV3
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesGlow
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesGlowIO
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesGlowParameters
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesGuidedFilter
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesHalation
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesHalationIO
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesHalationParameters
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesMattify
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesMattifyIO
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesMattifyParameters
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesPersonInputData
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesProcessor
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesPyramid
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesPyramidFactory
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesSkinSmoothIO
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesSkinSmoothParameters
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesSkinSmoothStandalone
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesTextureCopy
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesTextureWarping
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesUnderEyeBrighten
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesUnderEyeBrightenIO
+ __OBJC_$_INSTANCE_METHODS_CMITextureStylesUnderEyeBrightenParameters
+ __OBJC_$_INSTANCE_METHODS_NSArray(CMILCB|GainValueLookup|Comprehension|Getters)
+ __OBJC_$_INSTANCE_VARIABLES_CMILCBDatabase
+ __OBJC_$_INSTANCE_VARIABLES_CMILCBEntry
+ __OBJC_$_INSTANCE_VARIABLES_CMITSMattifyPerPersonIntermediatesAndStats
+ __OBJC_$_INSTANCE_VARIABLES_CMITSTextureAndFullImageRegion
+ __OBJC_$_INSTANCE_VARIABLES_CMITSUEBPerPersonData
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStyle
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesBloom
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesBloomIO
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesBloomParameters
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesDiffusion
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesDiffusionIO
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesDiffusionParameters
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesDownSampler
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesEffectDescriptor
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesFaceLandmark
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesFastGaussian
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesFilmGrainIO
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesFilmGrainParameters
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesFilmGrainProcessorV1
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesFilter
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesGaussianFilter
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesGaussianGuidedFilterV3
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesGlow
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesGlowIO
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesGlowParameters
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesGuidedFilter
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesHalation
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesHalationIO
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesHalationParameters
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesMattify
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesMattifyIO
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesMattifyParameters
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesPersonInputData
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesProcessor
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesPyramid
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesPyramidFactory
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesSkinSmoothIO
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesSkinSmoothParameters
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesSkinSmoothStandalone
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesTextureCopy
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesTextureWarping
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesUnderEyeBrighten
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesUnderEyeBrightenIO
+ __OBJC_$_INSTANCE_VARIABLES_CMITextureStylesUnderEyeBrightenParameters
+ __OBJC_$_PROP_LIST_CMILCBDatabase
+ __OBJC_$_PROP_LIST_CMILCBEntry
+ __OBJC_$_PROP_LIST_CMITSTextureAndFullImageRegion
+ __OBJC_$_PROP_LIST_CMITextureStyle
+ __OBJC_$_PROP_LIST_CMITextureStylesBloom
+ __OBJC_$_PROP_LIST_CMITextureStylesBloomIO
+ __OBJC_$_PROP_LIST_CMITextureStylesBloomParameters
+ __OBJC_$_PROP_LIST_CMITextureStylesDiffusion
+ __OBJC_$_PROP_LIST_CMITextureStylesDiffusionIO
+ __OBJC_$_PROP_LIST_CMITextureStylesDiffusionParameters
+ __OBJC_$_PROP_LIST_CMITextureStylesEffectDescriptor
+ __OBJC_$_PROP_LIST_CMITextureStylesEffectRenderer
+ __OBJC_$_PROP_LIST_CMITextureStylesFaceLandmark
+ __OBJC_$_PROP_LIST_CMITextureStylesFilmGrainIO
+ __OBJC_$_PROP_LIST_CMITextureStylesFilmGrainParameters
+ __OBJC_$_PROP_LIST_CMITextureStylesFilmGrainProcessorV1
+ __OBJC_$_PROP_LIST_CMITextureStylesGlow
+ __OBJC_$_PROP_LIST_CMITextureStylesGlowIO
+ __OBJC_$_PROP_LIST_CMITextureStylesGlowParameters
+ __OBJC_$_PROP_LIST_CMITextureStylesHalation
+ __OBJC_$_PROP_LIST_CMITextureStylesHalationIO
+ __OBJC_$_PROP_LIST_CMITextureStylesHalationParameters
+ __OBJC_$_PROP_LIST_CMITextureStylesMattify
+ __OBJC_$_PROP_LIST_CMITextureStylesMattifyIO
+ __OBJC_$_PROP_LIST_CMITextureStylesMattifyParameters
+ __OBJC_$_PROP_LIST_CMITextureStylesPersonInputData
+ __OBJC_$_PROP_LIST_CMITextureStylesProcessor
+ __OBJC_$_PROP_LIST_CMITextureStylesPyramid
+ __OBJC_$_PROP_LIST_CMITextureStylesSkinSmoothIO
+ __OBJC_$_PROP_LIST_CMITextureStylesSkinSmoothParameters
+ __OBJC_$_PROP_LIST_CMITextureStylesSkinSmoothStandalone
+ __OBJC_$_PROP_LIST_CMITextureStylesUnderEyeBrighten
+ __OBJC_$_PROP_LIST_CMITextureStylesUnderEyeBrightenIO
+ __OBJC_$_PROP_LIST_CMITextureStylesUnderEyeBrightenParameters
+ __OBJC_$_PROP_LIST_CMITileable
+ __OBJC_$_PROTOCOL_CLASS_METHODS_OPT_CMITextureStylesEffectRenderer
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CMITextureStylesEffectParameters
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CMITextureStylesEffectRenderer
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CMITileable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CMITextureStylesEffectParameters
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CMITextureStylesEffectRenderer
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CMITextureStylesEffectParameters
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CMITextureStylesEffectRenderer
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CMITileable
+ __OBJC_$_PROTOCOL_REFS_CMITextureStylesEffectInputOutput
+ __OBJC_$_PROTOCOL_REFS_CMITextureStylesEffectParameters
+ __OBJC_$_PROTOCOL_REFS_CMITextureStylesEffectRenderer
+ __OBJC_$_PROTOCOL_REFS_CMITextureStylesFilmGrainProcessor
+ __OBJC_$_PROTOCOL_REFS_CMITileable
+ __OBJC_CLASS_PROTOCOLS_$_CMILCBDatabase
+ __OBJC_CLASS_PROTOCOLS_$_CMILCBEntry
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesBloom
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesBloomIO
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesBloomParameters
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesDiffusion
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesDiffusionIO
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesDiffusionParameters
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesEffectDescriptor
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesFaceLandmark
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesFilmGrainIO
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesFilmGrainParameters
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesFilmGrainProcessorV1
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesGlow
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesGlowIO
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesGlowParameters
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesHalation
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesHalationIO
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesHalationParameters
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesMattify
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesMattifyIO
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesMattifyParameters
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesPersonInputData
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesProcessor
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesSkinSmoothIO
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesSkinSmoothParameters
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesSkinSmoothStandalone
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesUnderEyeBrighten
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesUnderEyeBrightenIO
+ __OBJC_CLASS_PROTOCOLS_$_CMITextureStylesUnderEyeBrightenParameters
+ __OBJC_CLASS_RO_$_CMILCBDatabase
+ __OBJC_CLASS_RO_$_CMILCBEntry
+ __OBJC_CLASS_RO_$_CMITSMattifyPerPersonIntermediatesAndStats
+ __OBJC_CLASS_RO_$_CMITSTextureAndFullImageRegion
+ __OBJC_CLASS_RO_$_CMITSUEBPerPersonData
+ __OBJC_CLASS_RO_$_CMITextureStyle
+ __OBJC_CLASS_RO_$_CMITextureStyleTuningLookup
+ __OBJC_CLASS_RO_$_CMITextureStylesBloom
+ __OBJC_CLASS_RO_$_CMITextureStylesBloomIO
+ __OBJC_CLASS_RO_$_CMITextureStylesBloomParameters
+ __OBJC_CLASS_RO_$_CMITextureStylesDiffusion
+ __OBJC_CLASS_RO_$_CMITextureStylesDiffusionIO
+ __OBJC_CLASS_RO_$_CMITextureStylesDiffusionParameters
+ __OBJC_CLASS_RO_$_CMITextureStylesDownSampler
+ __OBJC_CLASS_RO_$_CMITextureStylesEffectDescriptor
+ __OBJC_CLASS_RO_$_CMITextureStylesFaceLandmark
+ __OBJC_CLASS_RO_$_CMITextureStylesFastGaussian
+ __OBJC_CLASS_RO_$_CMITextureStylesFilmGrainIO
+ __OBJC_CLASS_RO_$_CMITextureStylesFilmGrainParameters
+ __OBJC_CLASS_RO_$_CMITextureStylesFilmGrainProcessorV1
+ __OBJC_CLASS_RO_$_CMITextureStylesFilter
+ __OBJC_CLASS_RO_$_CMITextureStylesGaussianFilter
+ __OBJC_CLASS_RO_$_CMITextureStylesGaussianGuidedFilterV3
+ __OBJC_CLASS_RO_$_CMITextureStylesGlow
+ __OBJC_CLASS_RO_$_CMITextureStylesGlowIO
+ __OBJC_CLASS_RO_$_CMITextureStylesGlowParameters
+ __OBJC_CLASS_RO_$_CMITextureStylesGuidedFilter
+ __OBJC_CLASS_RO_$_CMITextureStylesHalation
+ __OBJC_CLASS_RO_$_CMITextureStylesHalationIO
+ __OBJC_CLASS_RO_$_CMITextureStylesHalationParameters
+ __OBJC_CLASS_RO_$_CMITextureStylesMattify
+ __OBJC_CLASS_RO_$_CMITextureStylesMattifyIO
+ __OBJC_CLASS_RO_$_CMITextureStylesMattifyParameters
+ __OBJC_CLASS_RO_$_CMITextureStylesPersonInputData
+ __OBJC_CLASS_RO_$_CMITextureStylesPersonInputDataUtilities
+ __OBJC_CLASS_RO_$_CMITextureStylesProcessor
+ __OBJC_CLASS_RO_$_CMITextureStylesPyramid
+ __OBJC_CLASS_RO_$_CMITextureStylesPyramidFactory
+ __OBJC_CLASS_RO_$_CMITextureStylesSkinSmoothIO
+ __OBJC_CLASS_RO_$_CMITextureStylesSkinSmoothParameters
+ __OBJC_CLASS_RO_$_CMITextureStylesSkinSmoothStandalone
+ __OBJC_CLASS_RO_$_CMITextureStylesTextureCopy
+ __OBJC_CLASS_RO_$_CMITextureStylesTextureWarping
+ __OBJC_CLASS_RO_$_CMITextureStylesUnderEyeBrighten
+ __OBJC_CLASS_RO_$_CMITextureStylesUnderEyeBrightenIO
+ __OBJC_CLASS_RO_$_CMITextureStylesUnderEyeBrightenParameters
+ __OBJC_LABEL_PROTOCOL_$_CMITextureStylesEffectInputOutput
+ __OBJC_LABEL_PROTOCOL_$_CMITextureStylesEffectParameters
+ __OBJC_LABEL_PROTOCOL_$_CMITextureStylesEffectRenderer
+ __OBJC_LABEL_PROTOCOL_$_CMITextureStylesFilmGrainProcessor
+ __OBJC_LABEL_PROTOCOL_$_CMITileable
+ __OBJC_METACLASS_RO_$_CMILCBDatabase
+ __OBJC_METACLASS_RO_$_CMILCBEntry
+ __OBJC_METACLASS_RO_$_CMITSMattifyPerPersonIntermediatesAndStats
+ __OBJC_METACLASS_RO_$_CMITSTextureAndFullImageRegion
+ __OBJC_METACLASS_RO_$_CMITSUEBPerPersonData
+ __OBJC_METACLASS_RO_$_CMITextureStyle
+ __OBJC_METACLASS_RO_$_CMITextureStyleTuningLookup
+ __OBJC_METACLASS_RO_$_CMITextureStylesBloom
+ __OBJC_METACLASS_RO_$_CMITextureStylesBloomIO
+ __OBJC_METACLASS_RO_$_CMITextureStylesBloomParameters
+ __OBJC_METACLASS_RO_$_CMITextureStylesDiffusion
+ __OBJC_METACLASS_RO_$_CMITextureStylesDiffusionIO
+ __OBJC_METACLASS_RO_$_CMITextureStylesDiffusionParameters
+ __OBJC_METACLASS_RO_$_CMITextureStylesDownSampler
+ __OBJC_METACLASS_RO_$_CMITextureStylesEffectDescriptor
+ __OBJC_METACLASS_RO_$_CMITextureStylesFaceLandmark
+ __OBJC_METACLASS_RO_$_CMITextureStylesFastGaussian
+ __OBJC_METACLASS_RO_$_CMITextureStylesFilmGrainIO
+ __OBJC_METACLASS_RO_$_CMITextureStylesFilmGrainParameters
+ __OBJC_METACLASS_RO_$_CMITextureStylesFilmGrainProcessorV1
+ __OBJC_METACLASS_RO_$_CMITextureStylesFilter
+ __OBJC_METACLASS_RO_$_CMITextureStylesGaussianFilter
+ __OBJC_METACLASS_RO_$_CMITextureStylesGaussianGuidedFilterV3
+ __OBJC_METACLASS_RO_$_CMITextureStylesGlow
+ __OBJC_METACLASS_RO_$_CMITextureStylesGlowIO
+ __OBJC_METACLASS_RO_$_CMITextureStylesGlowParameters
+ __OBJC_METACLASS_RO_$_CMITextureStylesGuidedFilter
+ __OBJC_METACLASS_RO_$_CMITextureStylesHalation
+ __OBJC_METACLASS_RO_$_CMITextureStylesHalationIO
+ __OBJC_METACLASS_RO_$_CMITextureStylesHalationParameters
+ __OBJC_METACLASS_RO_$_CMITextureStylesMattify
+ __OBJC_METACLASS_RO_$_CMITextureStylesMattifyIO
+ __OBJC_METACLASS_RO_$_CMITextureStylesMattifyParameters
+ __OBJC_METACLASS_RO_$_CMITextureStylesPersonInputData
+ __OBJC_METACLASS_RO_$_CMITextureStylesPersonInputDataUtilities
+ __OBJC_METACLASS_RO_$_CMITextureStylesProcessor
+ __OBJC_METACLASS_RO_$_CMITextureStylesPyramid
+ __OBJC_METACLASS_RO_$_CMITextureStylesPyramidFactory
+ __OBJC_METACLASS_RO_$_CMITextureStylesSkinSmoothIO
+ __OBJC_METACLASS_RO_$_CMITextureStylesSkinSmoothParameters
+ __OBJC_METACLASS_RO_$_CMITextureStylesSkinSmoothStandalone
+ __OBJC_METACLASS_RO_$_CMITextureStylesTextureCopy
+ __OBJC_METACLASS_RO_$_CMITextureStylesTextureWarping
+ __OBJC_METACLASS_RO_$_CMITextureStylesUnderEyeBrighten
+ __OBJC_METACLASS_RO_$_CMITextureStylesUnderEyeBrightenIO
+ __OBJC_METACLASS_RO_$_CMITextureStylesUnderEyeBrightenParameters
+ __OBJC_PROTOCOL_$_CMITextureStylesEffectInputOutput
+ __OBJC_PROTOCOL_$_CMITextureStylesEffectParameters
+ __OBJC_PROTOCOL_$_CMITextureStylesEffectRenderer
+ __OBJC_PROTOCOL_$_CMITextureStylesFilmGrainProcessor
+ __OBJC_PROTOCOL_$_CMITileable
+ __Z48CMITSsetImageBlockAlignedROIOnEncoderAndDispatchP30CMITSTextureAndFullImageRegion6CGRectPU34objcproto23MTLComputePipelineState11objc_objectPU35objcproto24MTLComputeCommandEncoder11objc_objectm
+ __Z48CMITSsetImageBlockAlignedROIOnEncoderAndDispatchP30CMITSTextureAndFullImageRegion6CGRectPU34objcproto23MTLComputePipelineState11objc_objectPU35objcproto24MTLComputeCommandEncoder11objc_objectmb
+ __ZL26tsf_findBestRadiusAndScaleP7NSArrayIP8NSNumberEffPimm
+ ___123-[CMITextureStylesMattify _calculateExtendedFaceROI:leftCheekROI:rightCheekROI:triangleVerticesLeft:triangleVerticesRight:]_block_invoke
+ ___161+[CMITextureStylesPersonInputDataUtilities personInputDataArrayFromLivePhotoMetadataAndStatsTracks:faceAttitudesMetadataTrack:effectsStatsTrack:effectsToRender:]_block_invoke
+ ___161+[CMITextureStylesPersonInputDataUtilities personInputDataArrayFromLivePhotoMetadataAndStatsTracks:faceAttitudesMetadataTrack:effectsStatsTrack:effectsToRender:]_block_invoke_2
+ ___161+[CMITextureStylesPersonInputDataUtilities personInputDataArrayFromLivePhotoMetadataAndStatsTracks:faceAttitudesMetadataTrack:effectsStatsTrack:effectsToRender:]_block_invoke_3
+ ___242-[CMITextureStylesMattify encodeDownsampledGaussianBlurWithCommandBuffer:inputImage:outputDownsampledAndBlurredImage:outputImage:downsampleFactor:downsampleSigma:stopAfterDownsample:cropAndDownsampleSkipLevelCount:cropAndDownsampleBoxFilter:]_block_invoke_2
+ ___31-[CMITextureStylesGlow process]_block_invoke
+ ___31-[CMITextureStylesGlow process]_block_invoke_2
+ ___32-[CMITextureStylesBloom process]_block_invoke
+ ___32-[CMITextureStylesBloom process]_block_invoke_2
+ ___34-[CMITextureStylesMattify process]_block_invoke
+ ___34-[CMITextureStylesMattify process]_block_invoke_2
+ ___35-[CMITextureStylesHalation process]_block_invoke
+ ___35-[CMITextureStylesHalation process]_block_invoke_2
+ ___36-[CMITextureStylesDiffusion process]_block_invoke
+ ___36-[CMITextureStylesDiffusion process]_block_invoke_2
+ ___40-[CMITextureStylesMattify _processApply]_block_invoke_2
+ ___40-[CMITextureStylesMattify _processApply]_block_invoke_3
+ ___43-[CMITextureStylesUnderEyeBrighten process]_block_invoke
+ ___43-[CMITextureStylesUnderEyeBrighten process]_block_invoke_2
+ ___44-[CMILCBDatabase exportLCBsForCaptureStream]_block_invoke
+ ___44-[CMILCBDatabase exportLCBsForCaptureStream]_block_invoke_2
+ ___47-[CMITextureStylesFilmGrainProcessorV1 process]_block_invoke
+ ___47-[CMITextureStylesFilmGrainProcessorV1 process]_block_invoke_2
+ ___47-[CMITextureStylesSkinSmoothStandalone process]_block_invoke
+ ___47-[CMITextureStylesSkinSmoothStandalone process]_block_invoke_2
+ ___55+[CMITextureStyleTuningLookup _loadTuningPlistIfNeeded]_block_invoke
+ ___62-[CMITextureStylesTextureWarping _shaderForOutputPixelFormat:]_block_invoke
+ ___63-[CMITextureStylesPersonInputData normalizeRelativeToCropRect:]_block_invoke
+ ___64+[CMITextureStyleTuningLookup defaultTextureStyleForPresetName:]_block_invoke
+ ___64-[CMITextureStylesProcessor _createEffectProcessorsAndUtilities]_block_invoke
+ ___64-[CMITextureStylesProcessor _createEffectProcessorsAndUtilities]_block_invoke_2
+ ___64-[CMITextureStylesProcessor _createEffectProcessorsAndUtilities]_block_invoke_3
+ ___64-[CMITextureStylesProcessor _createEffectProcessorsAndUtilities]_block_invoke_4
+ ___64-[CMITextureStylesProcessor _createEffectProcessorsAndUtilities]_block_invoke_5
+ ___64-[CMITextureStylesProcessor _createEffectProcessorsAndUtilities]_block_invoke_6
+ ___64-[CMITextureStylesProcessor _createEffectProcessorsAndUtilities]_block_invoke_7
+ ___64-[CMITextureStylesProcessor _createEffectProcessorsAndUtilities]_block_invoke_8
+ ___67-[CMITextureStylesPersonInputData dictionaryRepresentationForKeys:]_block_invoke
+ ___68+[CMITextureStylesPersonInputData personDataFromDictionary:forKeys:]_block_invoke
+ ___72+[CMITextureStyleTuningLookup defaultTextureStyleForSmartStyleCastType:]_block_invoke
+ ___79+[CMISmartStyleUtilitiesV1 defaultStyleForCastType:smartStyleRenderingVersion:]_block_invoke
+ ___79+[CMISmartStyleUtilitiesV1 defaultStyleForCastType:smartStyleRenderingVersion:]_block_invoke_2
+ ___85+[CMITextureStylesPersonInputDataUtilities normalizePersonInputDataArray:toCropRect:]_block_invoke
+ ___88+[CMITextureStylesPersonInputDataUtilities sortPersonInputDataArrayByFaceSize:maxCount:]_block_invoke
+ ___94+[CMITextureStylesPersonInputDataUtilities convertUnitOfAngleInPersonInputDataArrayToDegrees:]_block_invoke
+ ___94+[CMITextureStylesPersonInputDataUtilities convertUnitOfAngleInPersonInputDataArrayToRadians:]_block_invoke
+ ___CMCaptureLibraryCore_block_invoke
+ ____ZL25tsp_denormalizePersonDataP7NSArrayIP28CMITextureStylesFaceLandmarkE6CGSize_block_invoke
+ ____ZL26tsf_findBestRadiusAndScale6CGSizefPi_block_invoke
+ ___allIOTextureKeys_block_invoke
+ ___block_descriptor_32_e15_B32?08Q16^B24l
+ ___block_descriptor_32_e25_B24?08"NSDictionary"16l
+ ___block_descriptor_32_e74_"CMITextureStylesPersonInputData"16?0"CMITextureStylesPersonInputData"8l
+ ___block_descriptor_32_e8_I12?0I8l
+ ___block_descriptor_32_e8_i16?0Q8l
+ ___block_descriptor_40_e8_32bs_e31_B40?0{CGSize=dd}8{CGSize=dd}24l
+ ___block_descriptor_40_e8_32bs_e41_"NSArray"32?0"NSArray"8"NSArray"16Q24l
+ ___block_descriptor_40_e8_32r_e5_v8?0l
+ ___block_descriptor_40_e8_32s_e45_v32?0"CMITextureStylesFaceLandmark"8Q16^B24l
+ ___block_descriptor_40_e8_32s_e48_v32?0"CMITextureStylesPersonInputData"8Q16^B24l
+ ___block_descriptor_40_e8_32s_e8_B16?08l
+ ___block_descriptor_40_e8_32s_e8_i12?0i8l
+ ___block_descriptor_48_e68_"CMITextureStylesFaceLandmark"16?0"CMITextureStylesFaceLandmark"8l
+ ___block_descriptor_48_e8_32s40r_e5_v8?0l
+ ___block_descriptor_48_e8_32s40s_e29_v32?0"NSDictionary"8Q16^B24l
+ ___block_descriptor_48_e8_32s_e29_v32?0"NSDictionary"8Q16^B24l
+ ___block_descriptor_56_e8_32s40r48r_e8_v16?08l
+ ___block_descriptor_64_e74_"CMITextureStylesPersonInputData"16?0"CMITextureStylesPersonInputData"8l
+ ___block_descriptor_64_e8_32s40r48r56w_e8_v16?08l
+ ___block_descriptor_72_e8_32s_e68_"CMITextureStylesFaceLandmark"16?0"CMITextureStylesFaceLandmark"8l
+ ___copy_helper_block_e8_32b
+ ___copy_helper_block_e8_32s40r
+ ___copy_helper_block_e8_32s40r48r
+ ___copy_helper_block_e8_32s40r48r56w
+ ___destroy_helper_block_e8_32s40r48r
+ ___destroy_helper_block_e8_32s40r48r56w
+ ___destructor_8_s0_s8_s24
+ ___getFigLivePhotoMetadataComputeDeserializationSizeSymbolLoc_block_invoke
+ ___getFigLivePhotoMetadataDeserializeIntoBufferSymbolLoc_block_invoke
+ ___mat_generateTrianglesAndComputeROI_block_invoke
+ ___mat_generateTrianglesAndComputeROI_block_invoke_2
+ ___sincosf_stret
+ ___ueb_generateTrianglesAndComputeROI_block_invoke
+ ___ueb_generateTrianglesAndComputeROI_block_invoke_2
+ __computeSkinMaskTransform
+ __hasStats
+ __loadDefaultUserBiasByCastType
+ __packStats
+ __sl_dlopen
+ _allIOTextureKeys
+ _audit_stringCMCapture
+ _dispatch_group_async
+ _e5rt_precompiled_compute_op_create_options_set_anef_intermediate_buffer_size_hint
+ _fmod
+ _gCMILCBTrace
+ _gTextureStylesFilmGrainTrace
+ _gTextureStylesSkinSmoothTrace
+ _hypot
+ _hypotf
+ _kBloomParameterEntries
+ _kCMITextureStyleTuningBlendPreset_Key
+ _kCMITextureStyleTuningBlendThreshold_Key
+ _kCMITextureStyleTuningFilmGrainEffect_Key
+ _kCMITextureStyleTuningFilmGrainSeed_Key
+ _kCMITextureStyleTuningGrainSourcePreset_Key
+ _kCMITextureStylesMinFaceDiagonalRatio
+ _kCMITextureStylesPersonInputDataKey_faceAnglePitch
+ _kCMITextureStylesPersonInputDataKey_faceAngleRoll
+ _kCMITextureStylesPersonInputDataKey_faceAngleYaw
+ _kCMITextureStylesPersonInputDataKey_faceID
+ _kCMITextureStylesPersonInputDataKey_faceLandmarkType
+ _kCMITextureStylesPersonInputDataKey_faceLandmark_error
+ _kCMITextureStylesPersonInputDataKey_faceLandmark_point
+ _kCMITextureStylesPersonInputDataKey_faceLandmarks
+ _kCMITextureStylesPersonInputDataKey_faceROI
+ _kCMITextureStylesPersonInputDataKey_faceROIAndLandmarksROIRelativeScalingROI
+ _kCMITextureStylesPersonInputDataKey_faceSkinROI
+ _kCMITextureStylesPersonInputDataKey_faceUnitOfAngle
+ _kCMITextureStylesPersonInputDataKey_imageStats
+ _kCMITextureStylesPersonInputDataKey_instanceMaskReferenceKey
+ _kCMITextureStylesPersonInputDataKey_instanceROI
+ _kCMITextureStylesSoftGatingLowerBoundStreaming
+ _kCMITextureStylesSoftGatingUpperBoundStreaming
+ _kCMITextureStylesStatsKey_MattifyAverageFaceColor
+ _kCMITextureStylesStatsKey_MattifyFaceID
+ _kCMITextureStylesStatsKey_MattifyHighlightsToMaskRatio
+ _kCMITextureStylesStatsKey_MattifySkipPerson
+ _kCMITextureStylesStatsKey_SkinSmoothAverageFaceColour
+ _kCMITextureStylesStatsKey_SkinSmoothFaceID
+ _kCMITextureStylesStatsKey_SkinSmoothFaceRoughness
+ _kCMITextureStylesStatsKey_SkinSmoothSkipPerson
+ _kCMITextureStylesStatsKey_UEBFaceID
+ _kCMITextureStylesStatsKey_UEBLeftEyeAverageColor
+ _kCMITextureStylesStatsKey_UEBLeftEyeIsBiModal
+ _kCMITextureStylesStatsKey_UEBLeftEyeLumaVariance
+ _kCMITextureStylesStatsKey_UEBRightEyeAverageColor
+ _kCMITextureStylesStatsKey_UEBRightEyeIsBiModal
+ _kCMITextureStylesStatsKey_UEBRightEyeLumaVariance
+ _kCMITextureStylesStreamingMaxFaceCount
+ _kDiffusionParameterEntries
+ _kFaceLandmarkIndicies
+ _kFigCaptureStreamLCBEntryKey_ApertureRatio
+ _kFigCaptureStreamLCBEntryKey_CenterX
+ _kFigCaptureStreamLCBEntryKey_CenterY
+ _kFigCaptureStreamLCBEntryKey_CorrectionFeaturesBlue
+ _kFigCaptureStreamLCBEntryKey_CorrectionFeaturesGreen
+ _kFigCaptureStreamLCBEntryKey_CorrectionFeaturesRed
+ _kFigCaptureStreamLCBEntryKey_CorrectionFeaturesSpatialScalingFactor
+ _kFigCaptureStreamLCBEntryKey_DetectionConfidence
+ _kFigCaptureStreamLCBEntryKey_DetectionScore
+ _kFigCaptureStreamLCBEntryKey_DetectionSource
+ _kFigCaptureStreamLCBEntryKey_FocusPosition
+ _kFigCaptureStreamLCBEntryKey_OISShiftX
+ _kFigCaptureStreamLCBEntryKey_OISShiftY
+ _kFigCaptureStreamLCBEntryKey_PatchData
+ _kFigCaptureStreamLCBEntryKey_PatchHeight
+ _kFigCaptureStreamLCBEntryKey_PatchOriginX
+ _kFigCaptureStreamLCBEntryKey_PatchOriginY
+ _kFigCaptureStreamLCBEntryKey_PatchSpatialDownscalingFactor
+ _kFigCaptureStreamLCBEntryKey_PatchType
+ _kFigCaptureStreamLCBEntryKey_PatchWidth
+ _kFigCaptureStreamLCBEntryKey_Radius
+ _kFigCaptureStreamLCBEntryKey_Type
+ _kFigCaptureStreamLCBKey_DetectionIteration
+ _kFigCaptureStreamLCBKey_Entries
+ _kFigCaptureStreamLCBKey_MaximumGain
+ _kFigCaptureStreamLCBKey_MaximumOISStroke
+ _kFigCaptureStreamLCBKey_MinimumGain
+ _kFigCaptureStreamLCBKey_ModuleSerial
+ _kFigCaptureStreamLCBKey_SensorID
+ _kFigCaptureStreamLCBKey_Version
+ _kFigCaptureStreamMetadata_AngleInfoPitch
+ _kFigCaptureStreamMetadata_AngleInfoYaw
+ _kGlowParameterEntries
+ _kHalationParameterEntries
+ _kIOSurfaceAGXUseNearestChromaFiltering
+ _kLeftEyeLandmarkIndices
+ _kParameterEntries
+ _kRightEyeLandmarkIndices
+ _kSyntheticSkinTextureData
+ _kSyntheticSkinTextureSize
+ _ldexpf
+ _mat_generateTrianglesAndComputeROI
+ _mat_packStats
+ _objc_msgSend$_applyMeteorToInput:gainMap:gain:mixFactor:outputMixed:commandBuffer:
+ _objc_msgSend$_boolFromDict:key:default:
+ _objc_msgSend$_cacheKeyForHardwareModel:portType:captureMode:preset:captureType:
+ _objc_msgSend$_calculateBlurSigma:
+ _objc_msgSend$_calculateFullScaleBlurRadius:
+ _objc_msgSend$_computeAsymLumMaskWithInput:personMask:outputMask:halationParameters:brightnessValue:commandBuffer:
+ _objc_msgSend$_createGlobalToneCurveTextureFromGTCData:encoder:toneCurveTextureOut:
+ _objc_msgSend$_createIntermediateTextures:inputRegion:blurredSize:
+ _objc_msgSend$_createIntermediateTexturesWithInputRegion:firstBlurSize:secondBlurSize:
+ _objc_msgSend$_encodeGrainBlendWithInputImageUsingParams:commandBuffer:inputOutput:
+ _objc_msgSend$_floatFromDict:key:default:
+ _objc_msgSend$_gainBasedFloatFromDict:key:totalGain:default:
+ _objc_msgSend$_halationFinalRendererWithInput:halationMask:skinMask:personMask:output:parameters:commandBuffer:
+ _objc_msgSend$_interpolateFrom:to:t:
+ _objc_msgSend$_loadTuningPlist
+ _objc_msgSend$_loadTuningPlistIfNeeded
+ _objc_msgSend$_mergeTuningDictionary:forCaptureType:
+ _objc_msgSend$_normalizedCaptureTypeForPresetDict:requestedCaptureType:
+ _objc_msgSend$_releaseIntermediateTextures
+ _objc_msgSend$_renderDiffusionWithInput:blurred:skinMask:personMask:output:diffusionParameters:commandBuffer:
+ _objc_msgSend$_rescale:toLinearRGB:commandBuffer:
+ _objc_msgSend$_shaderForFilterRadius:
+ _objc_msgSend$_substractFg:bg:output:commandBuffer:
+ _objc_msgSend$_unsignedIntegerFromDict:key:default:
+ _objc_msgSend$_updateColorManagementForInputOutput:
+ _objc_msgSend$_updateColorManagementForInputTexture:outputImageTexture:
+ _objc_msgSend$_updateColorManagementForInputTexture:outputTexture:
+ _objc_msgSend$_validateInputsAndParameters
+ _objc_msgSend$allPersonDataForBlending
+ _objc_msgSend$allocatorType
+ _objc_msgSend$amplitude
+ _objc_msgSend$amplitudeDecay
+ _objc_msgSend$aneCount
+ _objc_msgSend$apertureRatio
+ _objc_msgSend$averageColorMix
+ _objc_msgSend$backgroundStrength
+ _objc_msgSend$base64EncodedStringWithOptions:
+ _objc_msgSend$baselineExposure
+ _objc_msgSend$bg
+ _objc_msgSend$bimodalVarianceFalloff
+ _objc_msgSend$blendColorImageAverageColorMixFactor
+ _objc_msgSend$blendConditionFilterScale
+ _objc_msgSend$bodyMaskTextureAndFullImageRegion
+ _objc_msgSend$brightness
+ _objc_msgSend$brightnessMask
+ _objc_msgSend$brightnessMix
+ _objc_msgSend$brightnessValue
+ _objc_msgSend$bufferCountDualANE
+ _objc_msgSend$bundleWithIdentifier:
+ _objc_msgSend$bvHigh
+ _objc_msgSend$bvLow
+ _objc_msgSend$bvLowScale
+ _objc_msgSend$bvThresholdDeltaLowScale
+ _objc_msgSend$bw3Gamma
+ _objc_msgSend$calculateGaussianDimsWithWidth:height:sigma:nSamples:targetBlurRadius:pWorkWidth:pWorkHeight:pFinalSigma:pKernelRadius:fastMode:
+ _objc_msgSend$calculateGuidedFilterDimsWithFullImageWidth:fullImageHeight:sigma:blurRadius:pMediumResWidth:pMediumResHeight:pLowResWidth:pLowResHeight:pMediumToLow:pMediumSampling:pOutputBlurRadius:
+ _objc_msgSend$calculateIdealRadius:andDownSamplingScale:forImageSize:andTargetFullScaleRadius:
+ _objc_msgSend$calculateRadiusForSigma:
+ _objc_msgSend$calculateStats
+ _objc_msgSend$cmi_arrayByApplyingComprehension:
+ _objc_msgSend$colorBlendFilterScale
+ _objc_msgSend$computeAuxTextureRegionInCropSpaceWithAuxTextureSize:auxCropRect:fullImageSize:
+ _objc_msgSend$computeMinMaxCorrectionFeatureValues
+ _objc_msgSend$computeMinimumInputRegionInFullImageCoords:
+ _objc_msgSend$contrast
+ _objc_msgSend$contrastBoost
+ _objc_msgSend$contrastMask
+ _objc_msgSend$convertDegreesToRadians
+ _objc_msgSend$convertRadiansToDegrees
+ _objc_msgSend$convertUnitOfAngleInPersonInputDataArrayToRadians:
+ _objc_msgSend$copyFromInputTexture:withInputROI:toOutputTexture:withOutputROI:encodedTo:
+ _objc_msgSend$copyFromInputTexture:withInputROI:toOutputTexture:withOutputROI:enqueuedTo:
+ _objc_msgSend$copyWithZone:
+ _objc_msgSend$correctionFeatures
+ _objc_msgSend$createPyramidWithImage:maxLevels:encoder:
+ _objc_msgSend$createPyramidWithImage:maxLevels:pixelFormat:encoder:
+ _objc_msgSend$darkScale
+ _objc_msgSend$darknessDiffSmoothstepLowerBound
+ _objc_msgSend$darknessDiffSmoothstepUpperBound
+ _objc_msgSend$dataWithContentsOfURL:options:error:
+ _objc_msgSend$debugDescription
+ _objc_msgSend$decodeBoolForKey:
+ _objc_msgSend$decodeDictionaryWithKeysOfClass:objectsOfClass:forKey:
+ _objc_msgSend$decodeDoubleForKey:
+ _objc_msgSend$decodeFloatForKey:
+ _objc_msgSend$defaultStyleForCastType:smartStyleRenderingVersion:
+ _objc_msgSend$defocusRadius
+ _objc_msgSend$degrunge
+ _objc_msgSend$degrungeBody
+ _objc_msgSend$detailSize
+ _objc_msgSend$detectionCount
+ _objc_msgSend$dictOfZeroInitializedStats
+ _objc_msgSend$dictionaryRepresentation
+ _objc_msgSend$dictionaryRepresentationForKeys:
+ _objc_msgSend$dictionaryRepresentationsFromFigLivePhotoMetadata:
+ _objc_msgSend$difSat
+ _objc_msgSend$diffuseColor
+ _objc_msgSend$dominantYawTapering
+ _objc_msgSend$downSampleInput:output:encoder:
+ _objc_msgSend$drawPrimitives:vertexStart:vertexCount:
+ _objc_msgSend$earsMaskTextureAndFullImageRegion
+ _objc_msgSend$editingStrength
+ _objc_msgSend$effectTypeToEffectName:
+ _objc_msgSend$effectTypeToZeroInitializedStats:
+ _objc_msgSend$enableTextureAddback
+ _objc_msgSend$encodeBool:forKey:
+ _objc_msgSend$encodeDouble:forKey:
+ _objc_msgSend$encodeFloat:forKey:
+ _objc_msgSend$encodeGaussianBlurWithCommandBuffer:input:output:kernel:kernelSize:
+ _objc_msgSend$encodeSIMDGaussianBlurWithCommandBuffer:input:output:radius:
+ _objc_msgSend$enumerateObjectsUsingBlock:
+ _objc_msgSend$externalFaceRoughnessStatsOutput
+ _objc_msgSend$externalLargeBlurGuidedFilterAOutput
+ _objc_msgSend$externalLargeBlurGuidedFilterBOutput
+ _objc_msgSend$externalMemoryResource
+ _objc_msgSend$externalSmallBlurOutput
+ _objc_msgSend$externalTextureAddbackOutput
+ _objc_msgSend$eyeProtection
+ _objc_msgSend$eyebrows
+ _objc_msgSend$eyebrowsMaskTextureAndFullImageRegion
+ _objc_msgSend$faceDiagonalRatioForFaceSize:imageSize:
+ _objc_msgSend$faceID
+ _objc_msgSend$faceLandmarkType
+ _objc_msgSend$faceLandmarks
+ _objc_msgSend$facePitch
+ _objc_msgSend$faceROI
+ _objc_msgSend$faceROIAndLandmarksROIRelativeScalingROI
+ _objc_msgSend$faceRoll
+ _objc_msgSend$faceSkinMaskTextureAndFullImageRegion
+ _objc_msgSend$faceSkinROI
+ _objc_msgSend$faceTempering
+ _objc_msgSend$faceYaw
+ _objc_msgSend$fastMode
+ _objc_msgSend$filteredArrayUsingPredicate:
+ _objc_msgSend$focusLensPosition
+ _objc_msgSend$fogStrength
+ _objc_msgSend$fracMaskHighlightsHeadroom
+ _objc_msgSend$fracMaskHighlightsNormFactor
+ _objc_msgSend$frequencyGap
+ _objc_msgSend$fullImageRegion
+ _objc_msgSend$gFContrast
+ _objc_msgSend$gFRadius
+ _objc_msgSend$gamma
+ _objc_msgSend$gammaMask
+ _objc_msgSend$gaussianBlurSigma
+ _objc_msgSend$gaussianFilterInput:output:radius:sigma:commandBuffer:
+ _objc_msgSend$gaussianFilterInput:output:radius:sigma:encoder:
+ _objc_msgSend$generateNewKeyFromConflictingKey:
+ _objc_msgSend$glassesMaskTextureAndFullImageRegion
+ _objc_msgSend$grading
+ _objc_msgSend$grain
+ _objc_msgSend$grainBlurRadius
+ _objc_msgSend$grainSelectivity
+ _objc_msgSend$hairClothes
+ _objc_msgSend$hairMaskTextureAndFullImageRegion
+ _objc_msgSend$hairTxFloor
+ _objc_msgSend$halationChroma
+ _objc_msgSend$halationHue
+ _objc_msgSend$handsAndEars
+ _objc_msgSend$handsMaskTextureAndFullImageRegion
+ _objc_msgSend$highlight
+ _objc_msgSend$highlightRetention
+ _objc_msgSend$hlBlurStrength
+ _objc_msgSend$hlTextureRestore
+ _objc_msgSend$hueDiffMeanTermSmoothstepLowerBound
+ _objc_msgSend$hueDiffMeanTermSmoothstepUpperBound
+ _objc_msgSend$hueDiffSmoothstepLowerBound
+ _objc_msgSend$hueDiffSmoothstepUpperBound
+ _objc_msgSend$hueMaskFilterScale
+ _objc_msgSend$hueMix
+ _objc_msgSend$hueRotate
+ _objc_msgSend$imageGuidedFilterEpsilon
+ _objc_msgSend$imageGuidedFilterRadius
+ _objc_msgSend$imageStats
+ _objc_msgSend$imageTextureFactor
+ _objc_msgSend$imageTextureThreshold
+ _objc_msgSend$indexesOfObjectsPassingTest:
+ _objc_msgSend$initStandardTextureStyle
+ _objc_msgSend$initWithArray:copyItems:
+ _objc_msgSend$initWithBase64EncodedString:options:
+ _objc_msgSend$initWithEntry:
+ _objc_msgSend$initWithImage:maxLevels:allocator:encoder:shader:
+ _objc_msgSend$initWithImage:maxLevels:pixelFormat:allocator:encoder:shader:
+ _objc_msgSend$initWithKey:position:radius:defocusRadius:particleDistance:apertureRatio:focusLensPosition:oisShift:opticalCenter:detectionCount:relativeToLens:lastDetectionGravityVector:lastDetectionTimeStamp:shouldCorrect:correctionFeatures:
+ _objc_msgSend$initWithOptionalMetalCommandQueue:
+ _objc_msgSend$initWithOptionalMetalContext:
+ _objc_msgSend$initWithPoint:error:
+ _objc_msgSend$initWithPresetName:intensity:grain:
+ _objc_msgSend$initWithTuningDictionary:totalGain:
+ _objc_msgSend$initWithtype:parameters:
+ _objc_msgSend$inputEarMask
+ _objc_msgSend$inputFaceMask
+ _objc_msgSend$inputFaceRect
+ _objc_msgSend$inputGainMap
+ _objc_msgSend$inputGlassesMask
+ _objc_msgSend$inputHDRImage
+ _objc_msgSend$inputHairMask
+ _objc_msgSend$inputInnerKnot1
+ _objc_msgSend$inputInstanceMask
+ _objc_msgSend$inputLinearImage
+ _objc_msgSend$inputLinearMetadata
+ _objc_msgSend$inputLipMask
+ _objc_msgSend$inputLipsMask
+ _objc_msgSend$inputLowerCoeffA
+ _objc_msgSend$inputLowerCoeffB
+ _objc_msgSend$inputMask
+ _objc_msgSend$inputNoseMask
+ _objc_msgSend$inputOuterKnot1
+ _objc_msgSend$inputOutput
+ _objc_msgSend$inputPersonImage
+ _objc_msgSend$inputPersonMask
+ _objc_msgSend$inputSkinImage
+ _objc_msgSend$inputSkinMask
+ _objc_msgSend$inputSkinMaskAndFullImageRegion
+ _objc_msgSend$inputSkyImage
+ _objc_msgSend$inputSpread
+ _objc_msgSend$inputTattooMask
+ _objc_msgSend$inputTattoosMask
+ _objc_msgSend$inputThresholdDelta
+ _objc_msgSend$inputUpperCoeffA
+ _objc_msgSend$inputUpperCoeffB
+ _objc_msgSend$instanceMask
+ _objc_msgSend$instanceMaskTextureAndFullImageRegion
+ _objc_msgSend$instanceROI
+ _objc_msgSend$intensity
+ _objc_msgSend$key
+ _objc_msgSend$landmarkFromDictionary:
+ _objc_msgSend$largeBlurRadiusFaceDiagonalFactor
+ _objc_msgSend$lastDetectionGravityVector
+ _objc_msgSend$lastDetectionTimeStamp
+ _objc_msgSend$lift
+ _objc_msgSend$lightMapGamma
+ _objc_msgSend$lightMapInvert
+ _objc_msgSend$lightMapMax
+ _objc_msgSend$lightnessEditFactor
+ _objc_msgSend$lightnessEditHeadroom
+ _objc_msgSend$linearImageHighKey
+ _objc_msgSend$linearMixForBG
+ _objc_msgSend$linearMixForSkin
+ _objc_msgSend$lipContrast
+ _objc_msgSend$lipCrease
+ _objc_msgSend$lipHighlights
+ _objc_msgSend$lipNegClar
+ _objc_msgSend$lipsMaskTextureAndFullImageRegion
+ _objc_msgSend$maskBlurSigma
+ _objc_msgSend$maskThreshold
+ _objc_msgSend$maxCorrectionFeatureValue
+ _objc_msgSend$maxDarknessTrigger
+ _objc_msgSend$maxFaceFrac
+ _objc_msgSend$maxHueTolerance
+ _objc_msgSend$maxRGB
+ _objc_msgSend$maximumBimodalVariance
+ _objc_msgSend$maximumUnimodalVariance
+ _objc_msgSend$memoryResource
+ _objc_msgSend$metalCommandQueue
+ _objc_msgSend$metalShaderParamsFromDynamicParameters:brightnessValue:
+ _objc_msgSend$meteorHeadroom
+ _objc_msgSend$meteorHeadroomMixFactor
+ _objc_msgSend$minCorrectionFeatureValue
+ _objc_msgSend$minDarknessTrigger
+ _objc_msgSend$minFaceFrac
+ _objc_msgSend$minHueTolerance
+ _objc_msgSend$minTexture
+ _objc_msgSend$minTextureAddBack
+ _objc_msgSend$nLevels
+ _objc_msgSend$naturalResolution
+ _objc_msgSend$nightMode
+ _objc_msgSend$nightModeSharpness
+ _objc_msgSend$normalizeRelativeToCropRect:
+ _objc_msgSend$numberWithBool:
+ _objc_msgSend$numberWithLong:
+ _objc_msgSend$numberWithUnsignedShort:
+ _objc_msgSend$objectsAtIndexes:
+ _objc_msgSend$octaves
+ _objc_msgSend$oisShift
+ _objc_msgSend$opticalCenter
+ _objc_msgSend$outputPersonStats
+ _objc_msgSend$outputProcessedSkinMask
+ _objc_msgSend$parameters
+ _objc_msgSend$particleDistance
+ _objc_msgSend$person
+ _objc_msgSend$personDataFromDictionary:forKeys:
+ _objc_msgSend$personInputDataArrayFromDictionaryRepresentations:keys:
+ _objc_msgSend$personMaskTextureAndFullImageRegion
+ _objc_msgSend$personStrength
+ _objc_msgSend$plusGreenGuide
+ _objc_msgSend$point
+ _objc_msgSend$pores
+ _objc_msgSend$poresBody
+ _objc_msgSend$position
+ _objc_msgSend$predicateWithBlock:
+ _objc_msgSend$preserveColorfulness
+ _objc_msgSend$preserveColorfulnessMask
+ _objc_msgSend$preset
+ _objc_msgSend$processInput:output:triangleVertices:textureCoords:commandBuffer:
+ _objc_msgSend$processTexture:outputTexture:sigma:commandBuffer:fastMode:
+ _objc_msgSend$radius
+ _objc_msgSend$regionInFullImageCoords
+ _objc_msgSend$regionMaskThreshold
+ _objc_msgSend$relativeToLens
+ _objc_msgSend$renderPipelineStateForVertexFunction:vertexDescriptor:fragmentFunction:constants:colorAttachmentDescriptorArrray:
+ _objc_msgSend$rescaleInput:output:encoder:
+ _objc_msgSend$resetSkinSmoothState
+ _objc_msgSend$roughSamples
+ _objc_msgSend$saturation
+ _objc_msgSend$saturationFromSmartStyle
+ _objc_msgSend$saturationMask
+ _objc_msgSend$scaleParametersWithIntensity:
+ _objc_msgSend$seed
+ _objc_msgSend$setAllPersonDataForBlending:
+ _objc_msgSend$setAllocatorBackend:
+ _objc_msgSend$setBodyMaskTextureAndFullImageRegion:
+ _objc_msgSend$setBrightnessMix:
+ _objc_msgSend$setDefaults
+ _objc_msgSend$setDegrunge:
+ _objc_msgSend$setDegrungeBody:
+ _objc_msgSend$setEarsMaskTextureAndFullImageRegion:
+ _objc_msgSend$setEditingStrength:
+ _objc_msgSend$setEnableTextureAddback:
+ _objc_msgSend$setEnforceImmediateDealloc:
+ _objc_msgSend$setExternalFaceRoughnessStatsOutput:
+ _objc_msgSend$setExternalLargeBlurGuidedFilterAOutput:
+ _objc_msgSend$setExternalLargeBlurGuidedFilterBOutput:
+ _objc_msgSend$setExternalSmallBlurOutput:
+ _objc_msgSend$setExternalTextureAddbackOutput:
+ _objc_msgSend$setEyebrowsMaskTextureAndFullImageRegion:
+ _objc_msgSend$setFaceID:
+ _objc_msgSend$setFaceLandmarkType:
+ _objc_msgSend$setFaceLandmarks:
+ _objc_msgSend$setFacePitch:
+ _objc_msgSend$setFaceROI:
+ _objc_msgSend$setFaceRoll:
+ _objc_msgSend$setFaceSkinMaskTextureAndFullImageRegion:
+ _objc_msgSend$setFaceSkinROI:
+ _objc_msgSend$setFaceYaw:
+ _objc_msgSend$setFastMode:
+ _objc_msgSend$setFragmentTexture:atIndex:
+ _objc_msgSend$setFullImageRegion:
+ _objc_msgSend$setFullImageSize:
+ _objc_msgSend$setGlassesMaskTextureAndFullImageRegion:
+ _objc_msgSend$setHairClothes:
+ _objc_msgSend$setHairMaskTextureAndFullImageRegion:
+ _objc_msgSend$setHalationHue:
+ _objc_msgSend$setHandsMaskTextureAndFullImageRegion:
+ _objc_msgSend$setHlBlurStrength:
+ _objc_msgSend$setImageStats:
+ _objc_msgSend$setInputEarMask:
+ _objc_msgSend$setInputFaceMask:
+ _objc_msgSend$setInputFaceNormalizedRects:
+ _objc_msgSend$setInputFaceRect:
+ _objc_msgSend$setInputGainMap:
+ _objc_msgSend$setInputGlassesMask:
+ _objc_msgSend$setInputHDRImage:
+ _objc_msgSend$setInputHairMask:
+ _objc_msgSend$setInputInnerKnot0:
+ _objc_msgSend$setInputInstanceMask:
+ _objc_msgSend$setInputLinearImage:
+ _objc_msgSend$setInputLinearMetadata:
+ _objc_msgSend$setInputLipMask:
+ _objc_msgSend$setInputLipsMask:
+ _objc_msgSend$setInputLowerBound:
+ _objc_msgSend$setInputMask:
+ _objc_msgSend$setInputNoseMask:
+ _objc_msgSend$setInputOuterKnot0:
+ _objc_msgSend$setInputOutput:
+ _objc_msgSend$setInputPersonImage:
+ _objc_msgSend$setInputPersonMask:
+ _objc_msgSend$setInputSkinImage:
+ _objc_msgSend$setInputSkinMask:
+ _objc_msgSend$setInputSkinMaskAndFullImageRegion:
+ _objc_msgSend$setInputSkinMaskFlipHorizontal:
+ _objc_msgSend$setInputSkinMaskFlipVertical:
+ _objc_msgSend$setInputSkinMaskICR:
+ _objc_msgSend$setInputSkinMaskPCR:
+ _objc_msgSend$setInputSkinMaskRotationDegrees:
+ _objc_msgSend$setInputSkinSmoothingParameters:
+ _objc_msgSend$setInputSkyImage:
+ _objc_msgSend$setInputSpread:
+ _objc_msgSend$setInputTattooMask:
+ _objc_msgSend$setInputTattoosMask:
+ _objc_msgSend$setInputTextureROI:
+ _objc_msgSend$setInstanceID:
+ _objc_msgSend$setInstanceMask:
+ _objc_msgSend$setInstanceMaskReferenceKey:
+ _objc_msgSend$setInstanceMaskTextureAndFullImageRegion:
+ _objc_msgSend$setInstanceROI:
+ _objc_msgSend$setLinearImageHighKey:
+ _objc_msgSend$setLinearMixForBG:
+ _objc_msgSend$setLinearMixForSkin:
+ _objc_msgSend$setLipContrast:
+ _objc_msgSend$setLipNegClar:
+ _objc_msgSend$setLipsMaskTextureAndFullImageRegion:
+ _objc_msgSend$setLoadAction:
+ _objc_msgSend$setMaskBlurSigma:
+ _objc_msgSend$setMaxRGB:
+ _objc_msgSend$setMemoryResource:
+ _objc_msgSend$setMetalCommandQueue:
+ _objc_msgSend$setNightMode:
+ _objc_msgSend$setOutputPersonStats:
+ _objc_msgSend$setOutputProcessedSkinMask:
+ _objc_msgSend$setParameters:
+ _objc_msgSend$setPersonData:
+ _objc_msgSend$setPersonMaskTextureAndFullImageRegion:
+ _objc_msgSend$setPores:
+ _objc_msgSend$setPoresBody:
+ _objc_msgSend$setPreserveColorfulness:
+ _objc_msgSend$setPreserveColorfulnessMask:
+ _objc_msgSend$setRenderPipelineState:
+ _objc_msgSend$setRoughSamples:
+ _objc_msgSend$setSaturationFromSmartStyle:
+ _objc_msgSend$setSigmaGlare:
+ _objc_msgSend$setSkinMaskPurpose:
+ _objc_msgSend$setSkipRendering:
+ _objc_msgSend$setSoftLight:
+ _objc_msgSend$setStatistics:
+ _objc_msgSend$setStorageMode:
+ _objc_msgSend$setStoreAction:
+ _objc_msgSend$setStreamingMode:
+ _objc_msgSend$setStrength:
+ _objc_msgSend$setStrengthMask:
+ _objc_msgSend$setTattoosMaskTextureAndFullImageRegion:
+ _objc_msgSend$setTeethMaskTextureAndFullImageRegion:
+ _objc_msgSend$setTileSize:
+ _objc_msgSend$setTriangleFillMode:
+ _objc_msgSend$setUnitOfAngle:
+ _objc_msgSend$setUseStatistics:
+ _objc_msgSend$setValue:forKey:
+ _objc_msgSend$setVertexBytes:length:atIndex:
+ _objc_msgSend$setViewport:
+ _objc_msgSend$setWithArray:
+ _objc_msgSend$shDarken
+ _objc_msgSend$shadowLift
+ _objc_msgSend$shouldCorrect
+ _objc_msgSend$sigmaGlare
+ _objc_msgSend$skinMask
+ _objc_msgSend$skinStrength
+ _objc_msgSend$skipRendering
+ _objc_msgSend$skyStrength
+ _objc_msgSend$slBG
+ _objc_msgSend$slBright
+ _objc_msgSend$slDark
+ _objc_msgSend$slPerson
+ _objc_msgSend$slSkin
+ _objc_msgSend$smallBlurRadiusFaceDiagonalFactor
+ _objc_msgSend$softFadeGatingForFaceSize:imageSize:lowerBound:upperBound:
+ _objc_msgSend$softLight
+ _objc_msgSend$sortPersonInputDataArrayByFaceSize:maxCount:
+ _objc_msgSend$sortedArrayUsingSelector:
+ _objc_msgSend$spbHL
+ _objc_msgSend$statistics
+ _objc_msgSend$strength
+ _objc_msgSend$strengthMask
+ _objc_msgSend$strongTextureProtect
+ _objc_msgSend$subarrayWithRange:
+ _objc_msgSend$supportsInPlaceRendering
+ _objc_msgSend$tattooSmoothing
+ _objc_msgSend$tattooWeight
+ _objc_msgSend$tattoosMaskTextureAndFullImageRegion
+ _objc_msgSend$teeth
+ _objc_msgSend$teethMaskTextureAndFullImageRegion
+ _objc_msgSend$textureAddBackFilterScale
+ _objc_msgSend$textureAddBackScale
+ _objc_msgSend$textureClamp
+ _objc_msgSend$textureDetectScale
+ _objc_msgSend$textureRestore
+ _objc_msgSend$textureRestoreScalingFactor
+ _objc_msgSend$textureRestoreSmoothstepLowerBound
+ _objc_msgSend$textureRestoreSmoothstepUpperBound
+ _objc_msgSend$textureRestoreStrengthFactor
+ _objc_msgSend$tuningDictionaryForHardwareModel:portType:captureMode:preset:captureType:
+ _objc_msgSend$unimodalVarianceFalloff
+ _objc_msgSend$unsignedLongValue
+ _objc_msgSend$useStatistics
+ _objc_msgSend$validate
+ _objc_msgSend$valueForKey:
+ _objc_msgSend$varTexture
+ _objc_msgSend$weightedGuidedFilterInput:guide:outputA:outputB:radius:sigma:epsilon:encoder:
+ _objc_msgSend$withDifferentKey
+ _objc_msgSend$yawFallOff
+ _objc_msgSend$yawOffset
+ _objc_msgSend$zoom
+ _sLoadOnceToken
+ _sReloadLock
+ _ss_calculateBlurSigma
+ _ss_calculateBoundingBox
+ _ss_calculateEyeROI
+ _tc_defaultROI
+ _tc_defaultTextureROI
+ _ueb_generateTrianglesAndComputeROI
+ _ueb_getPaddedROIForFilterSigma
+ _ueb_packStats
+ allIOTextureKeys
+ allIOTextureKeys.keys
+ allIOTextureKeys.onceToken
+ computeInterpolationIndicesAndWeight
+ defaultStyleForCastType:smartStyleRenderingVersion:.defaultUserBiasByCastTypeNoTextureStyles
+ defaultStyleForCastType:smartStyleRenderingVersion:.defaultUserBiasByCastTypeWithTextureStyles
+ defaultStyleForCastType:smartStyleRenderingVersion:.smartStyleOnceToken
+ defaultStyleForCastType:smartStyleRenderingVersion:.textureStyleOnceToken
+ defaultTextureStyleForSmartStyleCastType:.onlyOnce
+ defaultTextureStyleForSmartStyleCastType:.rendererDefaults
+ getFigLivePhotoMetadataComputeDeserializationSizeSymbolLoc.ptr
+ getFigLivePhotoMetadataDeserializeIntoBufferSymbolLoc.ptr
+ mat_generateTrianglesAndComputeROI
+ ss_calculateBoundingBox
+ ss_calculateEyeROI
+ ueb_generateTrianglesAndComputeROI
- GCC_except_table91
- GCC_except_table94
- __OBJC_$_CATEGORY_NSArray_$_GainValueLookup
- __OBJC_$_INSTANCE_METHODS_NSArray(GainValueLookup|Comprehension|Getters)
- ___52+[CMISmartStyleUtilitiesV1 defaultStyleForCastType:]_block_invoke
- defaultStyleForCastType:.defaultUserBiasByCastType
- defaultStyleForCastType:.onceToken
CStrings:
+ "\v"
+ "\f\xf0\xb1\""
+ "! CGRectIsEmpty( *boundingBoxOut )"
+ "! CGRectIsEmpty( *eyeROIOut )"
+ "! CGRectIsEmpty( _personData.faceROI )"
+ "! CGRectIsEmpty( allImageRectIntersections )"
+ "! CGRectIsEmpty( bounds )"
+ "! CGRectIsEmpty( eyeROI )"
+ "! CGRectIsEmpty( inputROI )"
+ "! CGRectIsEmpty( regionToRender )"
+ "! CGRectIsEmpty( roi )"
+ "! CGRectIsEmpty( roiData->regionToRender )"
+ "! CGRectIsNull( _personData.faceROI )"
+ "! CGRectIsNull( _regionToRender ) && ! CGRectIsEmpty( _regionToRender )"
+ "! CGRectIsNull( extendedFaceROI )"
+ "! CGRectIsNull( inputOutput.inputFaceRect )"
+ "! CGRectIsNull( intermediatesAndStats->_extendedFaceROI )"
+ "! CGRectIsNull( rect )"
+ "! __CGSizeEqualToSize( roiData->fullImageSize, CGSizeZero )"
+ "! _metalContext.allocator.usedSizeAll"
+ "%@:%@:%@:%@:%@"
+ "( ! CGRectIsNull( _personData.faceROI ) ) && ( ! CGRectIsEmpty( _personData.faceROI ) )"
+ "( ( personData.faceLandmarkType != CMITextureStylesFaceLandmarkType_Invalid ) && personData.faceLandmarks ) || ( personData.faceLandmarkType == CMITextureStylesFaceLandmarkType_Invalid )"
+ "( _streamingMode ) || ( ( _personData.faceLandmarks && ( _personData.faceLandmarkType != CMITextureStylesFaceLandmarkType_Invalid ) ) )"
+ "( _streamingMode ) || ( _personData.faceLandmarks && ( _personData.faceLandmarkType != CMITextureStylesFaceLandmarkType_Invalid ) && ( ! CGRectIsEmpty( _personData.faceROI ) ) && io.inputFaceMask.texture )"
+ "( _streamingMode ) || ( triangleVerticesLeft && triangleVerticesRight && ( ! CGRectIsNull( leftCheekROI ) ) && ( ! CGRectIsNull( rightCheekROI ) ) )"
+ "( blurInputTex.width == outputDownsampledAndBlurredImage.texture.width ) && ( blurInputTex.height == outputDownsampledAndBlurredImage.texture.height )"
+ "( features.count >= 76 ) && ( landmarksType == CMITextureStylesFaceLandmarkType_Vision76 )"
+ "( outputDownsampledAndBlurredImage.texture.width == outputImage.texture.width ) && ( outputDownsampledAndBlurredImage.texture.height == outputImage.texture.height )"
+ "*heapBufferOut"
+ "*outputPtr"
+ "-[CMITextureStylesFastGaussian _createTexture:]"
+ "-[CMITextureStylesFastGaussian runOn:sigma:nSamples:targetBlurRadius:outTexture:commandBuffer:fastMode:]"
+ "-[CMITextureStylesGaussianGuidedFilterV3 _createTexture:]"
+ "-[CMITextureStylesGaussianGuidedFilterV3 runWithInput:skinMask:instanceMask:highlightRetention:sigma:eps:blurRadius:fullImageSize:fullImageOffset:outputTexture:commandBuffer:]"
+ "-[CMITextureStylesSkinSmoothStandalone _createTexture:label:]"
+ "-[CMITextureStylesSkinSmoothStandalone _createUncompressedTexture:label:]"
+ "-[CMITextureStylesUnderEyeBrighten calculateStats]"
+ "-[CMITextureStylesUnderEyeBrighten process]"
+ "/System/Library/PrivateFrameworks/CMCapture.framework/Contents/MacOS/CMCapture"
+ "0 == _outputPersonImageStats.count"
+ "1#"
+ "<%@: %p %@>"
+ "<%@: %p, effect type: %ld, configuration: %@>"
+ "<%@: %p, strength=%.2f, octaves=%u, saturation=%.2f>"
+ "<<<< CMILCB >>>>"
+ "<<<< CMILCB >>>> Fig"
+ "<<<< CMITIP >>>> %s: e5rt_execution_stream_set_ane_execution_priority failed to set E5RT_ANE_EXECUTION_PRIORITY_PRIORITY_6, %s."
+ "<<<< CMITIP >>>> %s: e5rt_precompiled_compute_op_create_options_set_anef_intermediate_buffer_size_hint failed to set 1x for kANEFClientIntermediateBufferSize %s, %s."
+ "<<<< CMITIP >>>> %s: e5rt_precompiled_compute_op_create_options_set_anef_intermediate_buffer_size_hint failed to set 2x for kANEFClientIntermediateBufferSize %s, %s."
+ "<<<< CMITextureStyles::Bloom >>>>"
+ "<<<< CMITextureStyles::Diffusion >>>>"
+ "<<<< CMITextureStyles::FastGaussian >>>>"
+ "<<<< CMITextureStyles::FastGaussian >>>> %s: %@ is nil"
+ "<<<< CMITextureStyles::FastGaussian >>>> %s: provided output texture doesn't meet requirements"
+ "<<<< CMITextureStyles::FastGaussian >>>> Fig"
+ "<<<< CMITextureStyles::FilmGrain >>>>"
+ "<<<< CMITextureStyles::Glow >>>>"
+ "<<<< CMITextureStyles::GuidedFilterV3 >>>>"
+ "<<<< CMITextureStyles::GuidedFilterV3 >>>> %s: %@ is nil"
+ "<<<< CMITextureStyles::GuidedFilterV3 >>>> %s: Failed to calculate guided filter dimensions"
+ "<<<< CMITextureStyles::GuidedFilterV3 >>>> Fig"
+ "<<<< CMITextureStyles::Halation >>>>"
+ "<<<< CMITextureStyles::Mattify >>>>"
+ "<<<< CMITextureStyles::Mattify >>>> Fig"
+ "<<<< CMITextureStyles::SkinSmoothStandalone >>>>"
+ "<<<< CMITextureStyles::SkinSmoothStandalone >>>> %s: %@ is nil"
+ "<<<< CMITextureStyles::SkinSmoothStandalone >>>> %s: chinIndex is greater than number of features"
+ "<<<< CMITextureStyles::SkinSmoothStandalone >>>> %s: chinPoint is not finite"
+ "<<<< CMITextureStyles::SkinSmoothStandalone >>>> %s: features are nil"
+ "<<<< CMITextureStyles::SkinSmoothStandalone >>>> %s: foreheadPoint is not finite"
+ "<<<< CMITextureStyles::SkinSmoothStandalone >>>> %s: noseTopIndex is greater than number of features"
+ "<<<< CMITextureStyles::SkinSmoothStandalone >>>> %s: point is not finite"
+ "<<<< CMITextureStyles::SkinSmoothStandalone >>>> Fig"
+ "<<<< CMITextureStyles::UEB >>>>"
+ "<<<< CMITextureStyles::UEB >>>> Fig"
+ "<<<< CMITextureStylesEffectDescriptor >>>>"
+ "<<<< CMITextureStylesEffectDescriptor >>>> Fig"
+ "<<<< TextureStylesProcessor >>>>"
+ "<<<< TextureStylesProcessor >>>> Fig"
+ "@\"CMITextureStylesFaceLandmark\"16@?0@\"CMITextureStylesFaceLandmark\"8"
+ "@\"CMITextureStylesPersonInputData\"16@?0@\"CMITextureStylesPersonInputData\"8"
+ "@\"NSArray\"32@?0@\"NSArray\"8@\"NSArray\"16Q24"
+ "@max.intValue"
+ "@min.intValue"
+ "A="
+ "AverageFaceColor"
+ "B16@?0@8"
+ "B24@?0@8@\"NSDictionary\"16"
+ "B32@?0@8Q16^B24"
+ "B40@?0{CGSize=dd}8{CGSize=dd}24"
+ "BlendPreset"
+ "BlendThreshold"
+ "Bloom"
+ "Bloom::GenerateBloom"
+ "CGRectContainsRect( CGRectMake( 0, 0, roiData->fullImageSize.width, roiData->fullImageSize.height ), roiData->regionToRender )"
+ "CGRectContainsRect( allImageRectIntersections, roiData->regionToRender )"
+ "CMILCBDatabase.m"
+ "CMILCBEntry.m"
+ "CMITS:SkinSmoothStandalone:DownScaledTex"
+ "CMITS:SkinSmoothStandalone:DownScaledTex2"
+ "CMITS:SkinSmoothStandalone:FaceDerived"
+ "CMITS:SkinSmoothStandalone:InternalProcessedMask"
+ "CMITS:SkinSmoothStandalone:PrecomputedMasks"
+ "CMITS:SkinSmoothStandalone:SmallBlurTex"
+ "CMITS:SkinSmoothStandalone:TABBlurredTex"
+ "CMITS:SkinSmoothStandalone:gfTexA"
+ "CMITS:SkinSmoothStandalone:gfTexB"
+ "CMITS:SkinSmoothStandalone:guideTex"
+ "CMITS:SkinSmoothStandalone:weightedTex"
+ "CMITextureStylesDownSampler.m"
+ "CMITextureStylesDownSampler::DownSample"
+ "CMITextureStylesDownSampler::Rescale"
+ "CMITextureStylesEffectDescriptor.m"
+ "CMITextureStylesFaceLandmarkType_Vision76 == featuresType"
+ "CMITextureStylesFastGaussian.m"
+ "CMITextureStylesFastGaussian::downsample_area_pow2"
+ "CMITextureStylesFastGaussian::downsample_nearest2d"
+ "CMITextureStylesFastGaussian::gaussian_h"
+ "CMITextureStylesFastGaussian::gaussian_v"
+ "CMITextureStylesFilmGrain::GrainBlend"
+ "CMITextureStylesFilter.m"
+ "CMITextureStylesFilter::Gaussian"
+ "CMITextureStylesFilter::Guided"
+ "CMITextureStylesFilter::SelfGuided"
+ "CMITextureStylesFilter::WeightedGuided"
+ "CMITextureStylesGaussianFilter.m"
+ "CMITextureStylesGaussianFilter::GaussianBlur"
+ "CMITextureStylesGaussianFilter::GaussianBlur2dShared"
+ "CMITextureStylesGaussianFilter::GaussianBlurHorizontal"
+ "CMITextureStylesGaussianFilter::GaussianBlurVertical"
+ "CMITextureStylesGaussianFilter::SimdGaussianBlur"
+ "CMITextureStylesGaussianGuidedFilterV3.m"
+ "CMITextureStylesGaussianGuidedFilterV3::build_lr_from_full"
+ "CMITextureStylesGaussianGuidedFilterV3::guided_lr_2d"
+ "CMITextureStylesGaussianGuidedFilterV3::upsample_apply_to_mr"
+ "CMITextureStylesGeometry.m"
+ "CMITextureStylesGuidedFilter.m"
+ "CMITextureStylesGuidedFilter::ComputeGuided"
+ "CMITextureStylesMattify.m"
+ "CMITextureStylesMattify::ApplyRegionAddbackAndEditingStrength"
+ "CMITextureStylesMattify::BoxDownsample"
+ "CMITextureStylesMattify::CalculateAverageColor"
+ "CMITextureStylesMattify::CalculateBlendCondition"
+ "CMITextureStylesMattify::CalculateFracMaskHighlights"
+ "CMITextureStylesMattify::CalculateHistogramR"
+ "CMITextureStylesMattify::CalculateHistogramRGBA"
+ "CMITextureStylesMattify::CalculateQuantiles"
+ "CMITextureStylesMattify::CalculateValidMask"
+ "CMITextureStylesMattify::CopyStats"
+ "CMITextureStylesMattify::CreateExclusionMask"
+ "CMITextureStylesMattify::CropAndBoxDownsample"
+ "CMITextureStylesMattify::CropAndReSample"
+ "CMITextureStylesMattify::GenerateHistogramInputColorImage"
+ "CMITextureStylesMattify::GenerateMin3GrayHistogramInputImage"
+ "CMITextureStylesMattify::GenerateStrengthHistogramInputImages"
+ "CMITextureStylesMattify::ReSample"
+ "CMITextureStylesMattify::ScaleByValidMask"
+ "CMITextureStylesMattify::styleEngineThumbnailMode"
+ "CMITextureStylesMattify_process_%03d"
+ "CMITextureStylesPersonInputDataUtilities.m"
+ "CMITextureStylesProcessor-FigMetalAllocator"
+ "CMITextureStylesProcessor-FigMetalAllocatorBackend"
+ "CMITextureStylesProcessor.m"
+ "CMITextureStylesPyramid.m"
+ "CMITextureStylesPyramid::DownSample"
+ "CMITextureStylesSkinSmoothStandalone.m"
+ "CMITextureStylesSkinSmoothenStandalone::computeFaceRoughnessKernel"
+ "CMITextureStylesSkinSmoothenStandalone::computeTextureAmountKernel"
+ "CMITextureStylesSkinSmoothenStandalone::copyStatsKernel"
+ "CMITextureStylesSkinSmoothenStandalone::createWeightedAndGuideImages"
+ "CMITextureStylesSkinSmoothenStandalone::downSample"
+ "CMITextureStylesSkinSmoothenStandalone::finalBlendingKernel"
+ "CMITextureStylesSkinSmoothenStandalone::finalBlendingKernelInPlace"
+ "CMITextureStylesSkinSmoothenStandalone::multiPersonSkinMaskBlending"
+ "CMITextureStylesSkinSmoothenStandalone::packPrecomputedMasksKernel"
+ "CMITextureStylesTextureCopy.m"
+ "CMITextureStylesTextureCopy::Copy"
+ "CMITextureStylesTextureWarping.m"
+ "CMITextureStylesTextureWarping::FragmentWarp"
+ "CMITextureStylesTextureWarping::VertexWarp"
+ "CMITextureStylesUnderEyeBrighten.m"
+ "CMITextureStylesUnderEyeBrighten::AverageColor"
+ "CMITextureStylesUnderEyeBrighten::Brighten"
+ "CMITextureStylesUnderEyeBrighten::CalculateLumaVarianceAndInferDistributionModality"
+ "CMITextureStylesUnderEyeBrighten::CalculateVarianceBasedStrengthTaper"
+ "CMITextureStylesUnderEyeBrighten::CopyStats"
+ "CMITextureStylesUnderEyeBrighten::CreateEyeMask"
+ "CMITextureStylesUnderEyeBrighten::CreateHueMask"
+ "CMITextureStylesUnderEyeBrighten::FinalMix"
+ "CMITextureStylesUnderEyeBrighten::SumColorAndFillLumaHistogram"
+ "CaptureMode"
+ "CaptureType"
+ "CaptureTypeOverrides"
+ "CopyFromInputTexture"
+ "CopyFromIntermediateTexture"
+ "Could not create synthetic skin texture"
+ "Could not init CMITextureStylesSkinSmoothStandalone"
+ "Could not init CMITextureStylesSkinSmoothStandalone FigMetalContext"
+ "DC"
+ "Diffusion"
+ "Diffusion::GenerateDiffusion"
+ "Diffusion::applyMeteor"
+ "Diffusion::rescale420ToRBGA"
+ "F10b"
+ "F10g"
+ "F10r"
+ "F3b"
+ "F3g"
+ "F3r"
+ "F4b"
+ "F4g"
+ "F4r"
+ "F5b"
+ "F5g"
+ "F5r"
+ "F6b"
+ "F6g"
+ "F6r"
+ "F7b"
+ "F7g"
+ "F7r"
+ "F8b"
+ "F8g"
+ "F8r"
+ "F9b"
+ "F9g"
+ "F9r"
+ "Fast-Gaussian-Area2D"
+ "Fast-Gaussian-Area2D-Capping-Pixels"
+ "Fast-Gaussian-Horz"
+ "Fast-Gaussian-Nearest"
+ "Fast-Gaussian-Vert"
+ "FigLivePhotoMetadataComputeDeserializationSize"
+ "FigLivePhotoMetadataDeserializeIntoBuffer"
+ "FilmGrain"
+ "FilmGrainSeed"
+ "Filmic"
+ "GVx"
+ "GVy"
+ "GVz"
+ "Gaussian-GuidedFilterV3-BuildLrFromFull"
+ "Gaussian-GuidedFilterV3-GuidedLr2D"
+ "Gaussian-GuidedFilterV3-Upsample"
+ "GaussianGuidedV3-Alr"
+ "GaussianGuidedV3-Blr"
+ "GaussianGuidedV3-lrX"
+ "GaussianGuidedV3-lrY"
+ "GlobalGrainSourcePreset"
+ "Glow"
+ "Glow::FillToneCurve"
+ "Glow::GenerateGlow"
+ "Glowy"
+ "Grain"
+ "Halation"
+ "Halation::Halation"
+ "Halation::lumAsymMask"
+ "Halation::subtractBlendMode"
+ "HardwareModel"
+ "HighlightsToMaskRatio"
+ "I12@?0I8"
+ "Intensity"
+ "K"
+ "LeftEyeAverageColor"
+ "LeftEyeIsBiModal"
+ "LeftEyeLumaVariance"
+ "LinearImageHighKey"
+ "Mattify"
+ "OSStatus soft_FigLivePhotoMetadataComputeDeserializationSize(const void *, size_t, FigLivePhotoMetadataVersion, FigLivePhotoMetadataVersion * _Nullable, FigLivePhotoMetadataVersion *, size_t *)"
+ "OSStatus soft_FigLivePhotoMetadataDeserializeIntoBuffer(const void *, size_t, FigLivePhotoMetadataVersion, size_t, FigLivePhotoMetadata *)"
+ "OX"
+ "OY"
+ "Ping Pong Image For Rendering"
+ "PortType"
+ "Preset"
+ "Px"
+ "Py"
+ "R2L"
+ "RendererTuningWithTextureStyles"
+ "RightEyeAverageColor"
+ "RightEyeIsBiModal"
+ "RightEyeLumaVariance"
+ "SkinSmooth-Compute-Texture-Amount"
+ "SkinSmooth-ComputeRoughness"
+ "SkinSmooth-CopyStats"
+ "SkinSmooth-DownScale"
+ "SkinSmooth-FinalBlending"
+ "SkinSmooth-FinalBlendingInPlace"
+ "SkinSmooth-LargeBlur"
+ "SkinSmooth-PackPrecomputedMasks"
+ "SkinSmooth-ProcessMask"
+ "SkinSmoothAverageFaceColour"
+ "SkinSmoothFaceRoughness"
+ "SkinSmoothSkipPerson"
+ "SkinSmoothingStandalone"
+ "SkipPerson"
+ "SmartStyleCastToTexturePresetMapping"
+ "SmartStyleToTextureStyleMapping"
+ "Soft"
+ "Studio"
+ "StyleEngine::SkinSmoothGuidedAvg"
+ "StyleEngine::SkinSmoothGuidedCoeff"
+ "Subject too small to process, skipping effect"
+ "TS"
+ "Texture"
+ "TextureStyleTuning"
+ "UnderEyeBrightening"
+ "[_inputOutput isKindOfClass:CMITextureStylesMattifyIO.class]"
+ "[_inputOutput isKindOfClass:CMITextureStylesSkinSmoothIO.class]"
+ "[_inputOutput isKindOfClass:CMITextureStylesUnderEyeBrightenIO.class]"
+ "[_metalContext.allocator setupWithDescriptor:allocatorDesc allocatorBackend:memoryResource.allocatorBackend] == 0 "
+ "[_parameters isKindOfClass:CMITextureStylesSkinSmoothParameters.class]"
+ "[_parameters isKindOfClass:CMITextureStylesUnderEyeBrightenParameters.class]"
+ "[_parameters isKindOfClass:[CMITextureStylesMattifyParameters class]]"
+ "[_parameters validate] == 0 "
+ "[e isKindOfClass:CMILCBEntry.class]"
+ "[effect isKindOfClass:CMITextureStylesMattify.class]"
+ "[self _compileShaders] == 0 "
+ "__CGSizeEqualToSize( inputROI.size, outputROI.size )"
+ "_blurProcessor"
+ "_context"
+ "_downSampler"
+ "_entriesByKey"
+ "_filterer"
+ "_fullImageSize.width > 0 && _fullImageSize.height > 0"
+ "_guidedFilterATextureAndFullImageRegion"
+ "_guidedFilterBTextureAndFullImageRegion"
+ "_moduleSerial"
+ "_perPersonData"
+ "_perPersonIntermediatesAndStats"
+ "_personData.faceLandmarks"
+ "_pyramidFactory"
+ "_sensorID"
+ "_shadersWithConstants[Shader_ApplyRegionAddbackAndEditingStrength][styleEngineThumbnailModeValI] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"ApplyRegionAddbackAndEditingStrength\" constants:constants]"
+ "_shadersWithConstants[Shader_CalculateBlendCondition][styleEngineThumbnailModeValI] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"CalculateBlendCondition\" constants:constants]"
+ "_shadersWithConstants[Shader_CalculateValidMask][styleEngineThumbnailModeValI] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"CalculateValidMask\" constants:constants]"
+ "_shadersWithoutConstants[Shader_BoxDownsample] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"BoxDownsample\" constants:constants]"
+ "_shadersWithoutConstants[Shader_CalculateAverageColor] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"CalculateAverageColor\" constants:constants]"
+ "_shadersWithoutConstants[Shader_CalculateFracMaskHighlights] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"CalculateFracMaskHighlights\" constants:constants]"
+ "_shadersWithoutConstants[Shader_CalculateHistogramRGBA] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"CalculateHistogramRGBA\" constants:constants]"
+ "_shadersWithoutConstants[Shader_CalculateHistogramR] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"CalculateHistogramR\" constants:constants]"
+ "_shadersWithoutConstants[Shader_CalculateQuantiles] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"CalculateQuantiles\" constants:constants]"
+ "_shadersWithoutConstants[Shader_CopyStats] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"CopyStats\" constants:constants]"
+ "_shadersWithoutConstants[Shader_CreateExclusionMask] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"CreateExclusionMask\" constants:constants]"
+ "_shadersWithoutConstants[Shader_CropAndBoxDownsample] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"CropAndBoxDownsample\" constants:constants]"
+ "_shadersWithoutConstants[Shader_CropAndReSample] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"CropAndReSample\" constants:constants]"
+ "_shadersWithoutConstants[Shader_GenerateHistogramInputColorImage] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"GenerateHistogramInputColorImage\" constants:constants]"
+ "_shadersWithoutConstants[Shader_GenerateMin3GrayHistogramInputImage] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"GenerateMin3GrayHistogramInputImage\" constants:constants]"
+ "_shadersWithoutConstants[Shader_GenerateStrengthHistogramInputImages] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"GenerateStrengthHistogramInputImages\" constants:constants]"
+ "_shadersWithoutConstants[Shader_ReSample] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"ReSample\" constants:constants]"
+ "_shadersWithoutConstants[Shader_ScaleByValidMask] = [_context computePipelineStateFor:@ \"CMITextureStylesMattify::\" \"ScaleByValidMask\" constants:constants]"
+ "_shaders[Shader_AverageColor] = [_context computePipelineStateFor:@ \"CMITextureStylesUnderEyeBrighten::\" \"AverageColor\" constants:constants]"
+ "_shaders[Shader_Brighten] = [_context computePipelineStateFor:@ \"CMITextureStylesUnderEyeBrighten::\" \"Brighten\" constants:constants]"
+ "_shaders[Shader_CalculateLumaVarianceAndInferDistributionModality] = [_context computePipelineStateFor:@ \"CMITextureStylesUnderEyeBrighten::\" \"CalculateLumaVarianceAndInferDistributionModality\" constants:constants]"
+ "_shaders[Shader_CalculateVarianceBasedStrengthTaper] = [_context computePipelineStateFor:@ \"CMITextureStylesUnderEyeBrighten::\" \"CalculateVarianceBasedStrengthTaper\" constants:constants]"
+ "_shaders[Shader_CopyStats] = [_context computePipelineStateFor:@ \"CMITextureStylesUnderEyeBrighten::\" \"CopyStats\" constants:constants]"
+ "_shaders[Shader_Copy] = [_context computePipelineStateFor:@ \"CMITextureStylesTextureCopy::\" \"Copy\" constants:constants]"
+ "_shaders[Shader_CreateEyeMask] = [_context computePipelineStateFor:@ \"CMITextureStylesUnderEyeBrighten::\" \"CreateEyeMask\" constants:constants]"
+ "_shaders[Shader_CreateHueMask] = [_context computePipelineStateFor:@ \"CMITextureStylesUnderEyeBrighten::\" \"CreateHueMask\" constants:constants]"
+ "_shaders[Shader_DownSample] = [_context computePipelineStateFor:@ \"CMITextureStylesDownSampler::\" \"DownSample\" constants:constants]"
+ "_shaders[Shader_DownSample] = [_context computePipelineStateFor:@ \"CMITextureStylesPyramid::\" \"DownSample\" constants:constants]"
+ "_shaders[Shader_FinalMix] = [_context computePipelineStateFor:@ \"CMITextureStylesUnderEyeBrighten::\" \"FinalMix\" constants:constants]"
+ "_shaders[Shader_GAUSSIAN_SHADER_NAME_10] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Gaussian\" constants:constants]"
+ "_shaders[Shader_GAUSSIAN_SHADER_NAME_11] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Gaussian\" constants:constants]"
+ "_shaders[Shader_GAUSSIAN_SHADER_NAME_1] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Gaussian\" constants:constants]"
+ "_shaders[Shader_GAUSSIAN_SHADER_NAME_2] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Gaussian\" constants:constants]"
+ "_shaders[Shader_GAUSSIAN_SHADER_NAME_3] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Gaussian\" constants:constants]"
+ "_shaders[Shader_GAUSSIAN_SHADER_NAME_4] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Gaussian\" constants:constants]"
+ "_shaders[Shader_GAUSSIAN_SHADER_NAME_5] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Gaussian\" constants:constants]"
+ "_shaders[Shader_GAUSSIAN_SHADER_NAME_6] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Gaussian\" constants:constants]"
+ "_shaders[Shader_GAUSSIAN_SHADER_NAME_7] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Gaussian\" constants:constants]"
+ "_shaders[Shader_GAUSSIAN_SHADER_NAME_8] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Gaussian\" constants:constants]"
+ "_shaders[Shader_GAUSSIAN_SHADER_NAME_9] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Gaussian\" constants:constants]"
+ "_shaders[Shader_GF_SHADER_10] = [_context computePipelineStateFor:@ \"CMITextureStylesGuidedFilter::\" \"ComputeGuided\" constants:constants]"
+ "_shaders[Shader_GF_SHADER_11] = [_context computePipelineStateFor:@ \"CMITextureStylesGuidedFilter::\" \"ComputeGuided\" constants:constants]"
+ "_shaders[Shader_GF_SHADER_4] = [_context computePipelineStateFor:@ \"CMITextureStylesGuidedFilter::\" \"ComputeGuided\" constants:constants]"
+ "_shaders[Shader_GF_SHADER_5] = [_context computePipelineStateFor:@ \"CMITextureStylesGuidedFilter::\" \"ComputeGuided\" constants:constants]"
+ "_shaders[Shader_GF_SHADER_6] = [_context computePipelineStateFor:@ \"CMITextureStylesGuidedFilter::\" \"ComputeGuided\" constants:constants]"
+ "_shaders[Shader_GF_SHADER_7] = [_context computePipelineStateFor:@ \"CMITextureStylesGuidedFilter::\" \"ComputeGuided\" constants:constants]"
+ "_shaders[Shader_GF_SHADER_8] = [_context computePipelineStateFor:@ \"CMITextureStylesGuidedFilter::\" \"ComputeGuided\" constants:constants]"
+ "_shaders[Shader_GF_SHADER_9] = [_context computePipelineStateFor:@ \"CMITextureStylesGuidedFilter::\" \"ComputeGuided\" constants:constants]"
+ "_shaders[Shader_GUIDED_SHADER_NAME_10] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Guided\" constants:constants]"
+ "_shaders[Shader_GUIDED_SHADER_NAME_11] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Guided\" constants:constants]"
+ "_shaders[Shader_GUIDED_SHADER_NAME_1] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Guided\" constants:constants]"
+ "_shaders[Shader_GUIDED_SHADER_NAME_2] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Guided\" constants:constants]"
+ "_shaders[Shader_GUIDED_SHADER_NAME_3] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Guided\" constants:constants]"
+ "_shaders[Shader_GUIDED_SHADER_NAME_4] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Guided\" constants:constants]"
+ "_shaders[Shader_GUIDED_SHADER_NAME_5] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Guided\" constants:constants]"
+ "_shaders[Shader_GUIDED_SHADER_NAME_6] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Guided\" constants:constants]"
+ "_shaders[Shader_GUIDED_SHADER_NAME_7] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Guided\" constants:constants]"
+ "_shaders[Shader_GUIDED_SHADER_NAME_8] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Guided\" constants:constants]"
+ "_shaders[Shader_GUIDED_SHADER_NAME_9] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"Guided\" constants:constants]"
+ "_shaders[Shader_GaussianBlur2dShared] = [_context computePipelineStateFor:@ \"CMITextureStylesGaussianFilter::\" \"GaussianBlur2dShared\" constants:constants]"
+ "_shaders[Shader_GaussianBlurHorizontal] = [_context computePipelineStateFor:@ \"CMITextureStylesGaussianFilter::\" \"GaussianBlurHorizontal\" constants:constants]"
+ "_shaders[Shader_GaussianBlurVertical] = [_context computePipelineStateFor:@ \"CMITextureStylesGaussianFilter::\" \"GaussianBlurVertical\" constants:constants]"
+ "_shaders[Shader_GaussianBlur] = [_context computePipelineStateFor:@ \"CMITextureStylesGaussianFilter::\" \"GaussianBlur\" constants:constants]"
+ "_shaders[Shader_MTLPixelFormatR16Float] = [_context renderPipelineStateForVertexFunction:@\"CMITextureStylesTextureWarping::VertexWarp\" vertexDescriptor:((void *)0) fragmentFunction:@\"CMITextureStylesTextureWarping::FragmentWarp\" constants:((void *)0) colorAttachmentDescriptorArrray:@[desc]]"
+ "_shaders[Shader_Rescale] = [_context computePipelineStateFor:@ \"CMITextureStylesDownSampler::\" \"Rescale\" constants:constants]"
+ "_shaders[Shader_SELF_GUIDED_SHADER_NAME_10] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"SelfGuided\" constants:constants]"
+ "_shaders[Shader_SELF_GUIDED_SHADER_NAME_11] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"SelfGuided\" constants:constants]"
+ "_shaders[Shader_SELF_GUIDED_SHADER_NAME_1] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"SelfGuided\" constants:constants]"
+ "_shaders[Shader_SELF_GUIDED_SHADER_NAME_2] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"SelfGuided\" constants:constants]"
+ "_shaders[Shader_SELF_GUIDED_SHADER_NAME_3] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"SelfGuided\" constants:constants]"
+ "_shaders[Shader_SELF_GUIDED_SHADER_NAME_4] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"SelfGuided\" constants:constants]"
+ "_shaders[Shader_SELF_GUIDED_SHADER_NAME_5] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"SelfGuided\" constants:constants]"
+ "_shaders[Shader_SELF_GUIDED_SHADER_NAME_6] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"SelfGuided\" constants:constants]"
+ "_shaders[Shader_SELF_GUIDED_SHADER_NAME_7] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"SelfGuided\" constants:constants]"
+ "_shaders[Shader_SELF_GUIDED_SHADER_NAME_8] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"SelfGuided\" constants:constants]"
+ "_shaders[Shader_SELF_GUIDED_SHADER_NAME_9] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"SelfGuided\" constants:constants]"
+ "_shaders[Shader_SimdGaussianBlur] = [_context computePipelineStateFor:@ \"CMITextureStylesGaussianFilter::\" \"SimdGaussianBlur\" constants:constants]"
+ "_shaders[Shader_SumColorAndFillLumaHistogram] = [_context computePipelineStateFor:@ \"CMITextureStylesUnderEyeBrighten::\" \"SumColorAndFillLumaHistogram\" constants:constants]"
+ "_shaders[Shader_WEIGHTED_GUIDED_SHADER_NAME_10] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"WeightedGuided\" constants:constants]"
+ "_shaders[Shader_WEIGHTED_GUIDED_SHADER_NAME_11] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"WeightedGuided\" constants:constants]"
+ "_shaders[Shader_WEIGHTED_GUIDED_SHADER_NAME_1] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"WeightedGuided\" constants:constants]"
+ "_shaders[Shader_WEIGHTED_GUIDED_SHADER_NAME_2] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"WeightedGuided\" constants:constants]"
+ "_shaders[Shader_WEIGHTED_GUIDED_SHADER_NAME_3] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"WeightedGuided\" constants:constants]"
+ "_shaders[Shader_WEIGHTED_GUIDED_SHADER_NAME_4] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"WeightedGuided\" constants:constants]"
+ "_shaders[Shader_WEIGHTED_GUIDED_SHADER_NAME_5] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"WeightedGuided\" constants:constants]"
+ "_shaders[Shader_WEIGHTED_GUIDED_SHADER_NAME_6] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"WeightedGuided\" constants:constants]"
+ "_shaders[Shader_WEIGHTED_GUIDED_SHADER_NAME_7] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"WeightedGuided\" constants:constants]"
+ "_shaders[Shader_WEIGHTED_GUIDED_SHADER_NAME_8] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"WeightedGuided\" constants:constants]"
+ "_shaders[Shader_WEIGHTED_GUIDED_SHADER_NAME_9] = [_context computePipelineStateFor:@ \"CMITextureStylesFilter::\" \"WeightedGuided\" constants:constants]"
+ "_shaders[Shader_build_lr_from_full] = [_context computePipelineStateFor:@ \"CMITextureStylesGaussianGuidedFilterV3::\" \"build_lr_from_full\" constants:((void *)0)]"
+ "_shaders[Shader_computeFaceRoughnessKernel]"
+ "_shaders[Shader_computeTextureAmountKernel]"
+ "_shaders[Shader_copyStatsKernel]"
+ "_shaders[Shader_createWeightedAndGuideImages]"
+ "_shaders[Shader_downSample]"
+ "_shaders[Shader_downsample_area_pow2] = [_context computePipelineStateFor:@ \"CMITextureStylesFastGaussian::\" \"downsample_area_pow2\" constants:((void *)0)]"
+ "_shaders[Shader_downsample_nearest2d] = [_context computePipelineStateFor:@ \"CMITextureStylesFastGaussian::\" \"downsample_nearest2d\" constants:((void *)0)]"
+ "_shaders[Shader_finalBlendingKernelInPlace]"
+ "_shaders[Shader_finalBlendingKernel]"
+ "_shaders[Shader_gaussian_h] = [_context computePipelineStateFor:@ \"CMITextureStylesFastGaussian::\" \"gaussian_h\" constants:((void *)0)]"
+ "_shaders[Shader_gaussian_v] = [_context computePipelineStateFor:@ \"CMITextureStylesFastGaussian::\" \"gaussian_v\" constants:((void *)0)]"
+ "_shaders[Shader_guided_lr_2d] = [_context computePipelineStateFor:@ \"CMITextureStylesGaussianGuidedFilterV3::\" \"guided_lr_2d\" constants:((void *)0)]"
+ "_shaders[Shader_multiPersonSkinMaskBlending]"
+ "_shaders[Shader_packPrecomputedMasksKernel]"
+ "_shaders[Shader_upsample_apply_to_mr] = [_context computePipelineStateFor:@ \"CMITextureStylesGaussianGuidedFilterV3::\" \"upsample_apply_to_mr\" constants:((void *)0)]"
+ "_smallBlurTextureAndFullImageRegion"
+ "_statsBuffer"
+ "_statsBufferPool"
+ "_statsBuffers"
+ "_syntheticSkinTexture"
+ "_textureCopier"
+ "_warper"
+ "aR"
+ "amplitude"
+ "amplitudeDecay"
+ "apertureRatio"
+ "arrayOfDicts"
+ "averageColorMix"
+ "averageFaceColor && [averageFaceColor isKindOfClass:NSArray.class] && ( 3 == averageFaceColor.count ) && [averageFaceColor[0] isKindOfClass:NSNumber.class] && [averageFaceColor[1] isKindOfClass:NSNumber.class] && [averageFaceColor[2] isKindOfClass:NSNumber.class]"
+ "avg && [avg isKindOfClass:NSArray.class] && ( 3 == avg.count ) && [avg[0] isKindOfClass:NSNumber.class] && [avg[1] isKindOfClass:NSNumber.class] && [avg[2] isKindOfClass:NSNumber.class]"
+ "backgroundStrength"
+ "baseGain"
+ "baselineExposure"
+ "benc"
+ "bg"
+ "bimodalVarianceFalloff"
+ "blendColorImageAverageColorMixFactor"
+ "blendConditionFilterScale"
+ "bloom"
+ "blurHPS"
+ "blurInputTex"
+ "blurOutputTex"
+ "blurVPS"
+ "blurredTex"
+ "body mask (non-face)"
+ "boxDownsamplePS"
+ "brightness"
+ "brightnessMask"
+ "brightnessMix"
+ "bvHigh"
+ "bvLow"
+ "bvLowScale"
+ "bvThresholdDeltaLowScale"
+ "bw3Gamma"
+ "cmd"
+ "colorBlendFilterScale"
+ "com.apple.CMImaging"
+ "computeMinimumInputRegionInFullImageCoordsOut"
+ "contrast"
+ "contrastBoost"
+ "contrastMask"
+ "correctionFeatures"
+ "cropAndDownsamplePS"
+ "croppedAndPartiallyDownsampledTex"
+ "croppedRescaledMattifyExcludeMask"
+ "croppedRescaledRefPersonUnderEyeMask"
+ "curAD > 0"
+ "currentInput.texture != currentOutput.texture"
+ "currentOutput"
+ "currentOutputPtr"
+ "cvReturn == 0 "
+ "dR"
+ "darkScale"
+ "darknessDiffSmoothstepLowerBound"
+ "darknessDiffSmoothstepUpperBound"
+ "defocusRadius"
+ "degrunge"
+ "degrungeBody"
+ "desc"
+ "detailSize"
+ "detectionCount"
+ "difSat"
+ "diffuseColor"
+ "diffusion"
+ "dominantYawTapering"
+ "downScaledIm"
+ "downScaledTex"
+ "ear mask"
+ "editingStrength"
+ "effect"
+ "effect && effectDesc.parameters"
+ "effectsToRender.count"
+ "enableTextureAddback"
+ "enc"
+ "entries"
+ "entry"
+ "entry.correctionFeatures"
+ "error"
+ "eye mask"
+ "eyeIndices[i] < features.count"
+ "eyeProtection"
+ "eyebrows"
+ "fP"
+ "face mask"
+ "faceID"
+ "faceLandmarkType"
+ "faceLandmarks"
+ "facePitch"
+ "faceROI"
+ "faceROIAndLandmarksROIRelativeScalingROI"
+ "faceRoll"
+ "faceSkinROI"
+ "faceTempering"
+ "faceUnitOfAngle"
+ "faceYaw"
+ "fast-gauss-area2d"
+ "fast-gauss-area2d-capping-pixels"
+ "fast-gauss-nearest"
+ "fast-gauss-tmpH"
+ "features.count >= 74"
+ "filmGrain"
+ "focusLensPosition"
+ "fogStrength"
+ "fracMaskHighlightsHeadroom"
+ "fracMaskHighlightsNormFactor"
+ "frequencyGap"
+ "gFContrast"
+ "gFRadius"
+ "gamma"
+ "gammaMask"
+ "gauss2D"
+ "gaussianBlurSigma"
+ "gfDimsOkay"
+ "gfTexA"
+ "gfTexB"
+ "glow"
+ "grading"
+ "grainBlurRadius"
+ "grainSelectivity"
+ "guide"
+ "guideTex"
+ "hairClothes"
+ "hairTxFloor"
+ "halation"
+ "halationChroma"
+ "halationHue"
+ "hands mask"
+ "handsAndEars"
+ "height"
+ "highlight"
+ "highlightRetention"
+ "highlightsToMaskRatio && [highlightsToMaskRatio isKindOfClass:NSNumber.class]"
+ "histogramBuffer"
+ "histogramColor"
+ "histogramImageHighlights"
+ "histogramMin3Gray"
+ "histogramWarpedMaskBinary"
+ "hlBlurStrength"
+ "hlTextureRestore"
+ "hueDiffMeanTermSmoothstepLowerBound"
+ "hueDiffMeanTermSmoothstepUpperBound"
+ "hueDiffSmoothstepLowerBound"
+ "hueDiffSmoothstepUpperBound"
+ "hueMaskFilterScale"
+ "hueMix"
+ "hueRotate"
+ "i12@?0i8"
+ "i16@?0Q8"
+ "imageGuidedFilterEpsilon"
+ "imageGuidedFilterRadius"
+ "imageStats"
+ "imageTextureFactor"
+ "imageTextureThreshold"
+ "input Meteor Gain Map"
+ "input Person mask"
+ "input Sky mask"
+ "input eyebrows mask"
+ "input glasses mask"
+ "input hair mask"
+ "input linear"
+ "input teeth mask"
+ "input.height == guide.height"
+ "input.height == output.height"
+ "input.height == outputA.height"
+ "input.height == outputB.height"
+ "input.texture"
+ "input.width == guide.width"
+ "input.width == output.width"
+ "input.width == outputA.width"
+ "input.width == outputB.width"
+ "inputBodyMask"
+ "inputDownsampledTex"
+ "inputEarMask"
+ "inputEyeMask"
+ "inputEyebrowsMask"
+ "inputFaceMask"
+ "inputGlassesMask"
+ "inputHairMask"
+ "inputHandsMask"
+ "inputImage"
+ "inputInnerKnot0"
+ "inputInnerKnot1"
+ "inputIrisMask"
+ "inputLinear"
+ "inputLipsMask"
+ "inputLowerBound"
+ "inputLowerCoeffA"
+ "inputLowerCoeffB"
+ "inputMeteorGainMap"
+ "inputMouthMask"
+ "inputNoseMask"
+ "inputOuterKnot0"
+ "inputOuterKnot1"
+ "inputOutput.inputImage.texture"
+ "inputOutput.inputSkinMaskAndFullImageRegion.texture"
+ "inputOutput.outputImage.texture"
+ "inputPersonMask"
+ "inputPingPongImageForRendering"
+ "inputReferenceMaskTexture"
+ "inputReferenceMaskTextureCoords"
+ "inputReferenceMaskTriangleVertices"
+ "inputSkinMask"
+ "inputSkyMask"
+ "inputSpread"
+ "inputTattoosMask"
+ "inputTeethMask"
+ "inputThresholdDelta"
+ "inputUpperCoeffA"
+ "inputUpperCoeffB"
+ "instanceMaskReferenceKey"
+ "instanceROI"
+ "intermediateTextureAndFullImageRegions"
+ "intermediatesAndStats"
+ "internalMaskTexture"
+ "io.inputFaceMask.texture"
+ "io.inputImage.texture"
+ "io.inputInstanceMask.texture"
+ "io.outputImage.texture"
+ "ioTextureDict[kIOTextureKey_Input].texture"
+ "ioTextureDict[kIOTextureKey_Output].texture"
+ "iris mask"
+ "kCMBaseObjectError_Invalidated != err"
+ "kFaceLandmarkIndicies[i] < features.count"
+ "key"
+ "largeBlurRadiusFaceDiagonalFactor"
+ "lastDetectionGravityVector"
+ "lastDetectionTimeStamp"
+ "lcb_trace"
+ "leftAvgCol && [leftAvgCol isKindOfClass:NSArray.class] && ( 3 == leftAvgCol.count ) && [leftAvgCol[0] isKindOfClass:NSNumber.class] && [leftAvgCol[1] isKindOfClass:NSNumber.class] && [leftAvgCol[2] isKindOfClass:NSNumber.class]"
+ "leftIsBiModal && [leftIsBiModal isKindOfClass:NSNumber.class]"
+ "leftVariance && [leftVariance isKindOfClass:NSNumber.class]"
+ "lift"
+ "lightMapGamma"
+ "lightMapInvert"
+ "lightMapMax"
+ "lightnessEditFactor"
+ "lightnessEditHeadroom"
+ "lipContrast"
+ "lipCrease"
+ "lipHighlights"
+ "lipNegClar"
+ "lips mask"
+ "lr_x && lr_y && A_lr && b_lr"
+ "maskBlurSigma"
+ "maskThreshold"
+ "mattify"
+ "mattifyIO"
+ "maxDarknessTrigger"
+ "maxFaceFrac"
+ "maxHueTolerance"
+ "maxLevels"
+ "maxRGB"
+ "maximumBimodalVariance"
+ "maximumUnimodalVariance"
+ "memoryResource = self.memoryResource ?: ( self.memoryResource = [self _createMemoryResource] )"
+ "memoryResource.allocatorBackend.memSize >= allocatorDesc.memSize"
+ "meteorHeadroom"
+ "meteorHeadroomMixFactor"
+ "minDarknessTrigger"
+ "minFaceFrac"
+ "minHueTolerance"
+ "minTexture"
+ "minTextureAddBack"
+ "moduleSerial"
+ "mouth mask"
+ "nLevels"
+ "naturalResolution"
+ "newE"
+ "nightMode"
+ "nightModeSharpness"
+ "nose mask"
+ "oX"
+ "oY"
+ "octaves"
+ "oisShift"
+ "opticalCenter"
+ "outExtendedFaceROI"
+ "outLeftCheekROI"
+ "outRightCheekROI"
+ "outTriangleVerticesLeft"
+ "outTriangleVerticesRight"
+ "outputA"
+ "outputB"
+ "outputMattifyStats"
+ "outputPtr"
+ "outputRectPtr"
+ "outputSkinSmoothingStats"
+ "outputTexture.pixelFormat == MTLPixelFormatRGBA16Float"
+ "outputTexture.width == mrW && outputTexture.height == mrH"
+ "outputTexturePtr"
+ "outputUEBStats"
+ "pD"
+ "paddedRegionToRenderOut"
+ "parameters"
+ "particleDistance"
+ "perPersonIntermediatesAndStats"
+ "person"
+ "person %u instance mask"
+ "personData"
+ "personData->_statsBuffer"
+ "personStrength"
+ "plusGreenGuide"
+ "point"
+ "pores"
+ "poresBody"
+ "position"
+ "preserveColorfulness"
+ "preserveColorfulnessMask"
+ "preset:%@ intensity:%.3f grain:%.3f"
+ "pyramid"
+ "quantileBins"
+ "radius"
+ "radiusPtr"
+ "regionMaskThreshold"
+ "relativeToLens"
+ "rightAvgCol && [rightAvgCol isKindOfClass:NSArray.class] && ( 3 == rightAvgCol.count ) && [rightAvgCol[0] isKindOfClass:NSNumber.class] && [rightAvgCol[1] isKindOfClass:NSNumber.class] && [rightAvgCol[2] isKindOfClass:NSNumber.class]"
+ "rightIsBiModal && [rightIsBiModal isKindOfClass:NSNumber.class]"
+ "rightVariance && [rightVariance isKindOfClass:NSNumber.class]"
+ "roiData->fullImageSize.width && roiData->fullImageSize.height"
+ "rough && [rough isKindOfClass:NSNumber.class]"
+ "s"
+ "sC"
+ "saturation"
+ "saturationMask"
+ "scaleIsGood"
+ "scalePtr"
+ "seed"
+ "selectedShader"
+ "self._allocateStatsBuffers == 0 "
+ "self._compileShaders == 0 "
+ "sensorID"
+ "shDarken"
+ "shader"
+ "shadowLift"
+ "sharedMemorySize <= cmd.device.maxThreadgroupMemoryLength"
+ "shouldCorrect"
+ "sigma > 0.0f && nSamples > 0 && targetBlurRadius > 0.0f"
+ "sigmaGlare"
+ "simdGaussPipeline"
+ "skinSmoothStandalone"
+ "skinStrength"
+ "skip && [skip isKindOfClass:NSNumber.class]"
+ "skyStrength"
+ "slBG"
+ "slBright"
+ "slDark"
+ "slPerson"
+ "slSkin"
+ "smallBlurRadiusFaceDiagonalFactor"
+ "smallBlurTex"
+ "softLight"
+ "softlink:r:path:/System/Library/PrivateFrameworks/CMCapture.framework/CMCapture"
+ "sortedFilterRadii"
+ "spbHL"
+ "ss_calculateBoundingBox"
+ "ss_calculateFaceROI"
+ "ss_calculateUpDir"
+ "statsBuffer"
+ "strength"
+ "strengthMask"
+ "strongTextureProtect"
+ "sumColorBuffer"
+ "tattooSmoothing"
+ "tattooWeight"
+ "tattoos mask"
+ "tc_roiIsValid( inputROI, inputTexture )"
+ "tc_roiIsValid( outputROI, outputTexture )"
+ "teeth"
+ "temp"
+ "tempStats.faceRoughness >= 0.0f && tempStats.faceRoughness <= 1.0f && __tg_isfinite((__typeof__(__tg_promote((tempStats.faceRoughness))))(tempStats.faceRoughness))"
+ "textureAddBackFilterScale"
+ "textureAddBackScale"
+ "textureClamp"
+ "textureCopier"
+ "textureDetectScale"
+ "textureRestore"
+ "textureRestoreScalingFactor"
+ "textureRestoreSmoothstepLowerBound"
+ "textureRestoreSmoothstepUpperBound"
+ "textureRestoreStrengthFactor"
+ "textureStyle.mattify.editingROIFudgeFactor"
+ "textureStyle.mattify.useFallbackExtendedFaceROI"
+ "textureStyle.mattify.usePeakMemoryOptims"
+ "tileSize"
+ "tmpArea"
+ "tmpDownScaleFactor >= 1.f"
+ "tmpFilterRadius"
+ "tmpNearest"
+ "tmpTex"
+ "triangleVertices"
+ "triangleVerticesOut || roiOut"
+ "triangleVerticesX"
+ "triangleVerticesXY"
+ "triangleVerticesY"
+ "type"
+ "uebIO"
+ "ueb_generateTrianglesAndComputeROI( _personData.faceLandmarks, _personData.faceLandmarkType, UEBEyeIndex_Left == eyeIndex, ((void*)0), &eyeROI ) == 0 "
+ "underEyeBrighten"
+ "unimodalVarianceFalloff"
+ "upsamplePS"
+ "v"
+ "v32@?0@\"CMITextureStylesFaceLandmark\"8Q16^B24"
+ "v32@?0@\"CMITextureStylesPersonInputData\"8Q16^B24"
+ "v32@?0@\"NSDictionary\"8Q16^B24"
+ "validMask"
+ "varTexture"
+ "version == 4"
+ "vertexData"
+ "void *CMCaptureLibrary(void)"
+ "warpedMaskAggregate"
+ "warpedTex"
+ "warpedUnderEyeReferenceMask.texture"
+ "weightedTex"
+ "width"
+ "x"
+ "y"
+ "yawFallOff"
+ "yawOffset"
+ "zoom"
+ "\x91"
+ "\xf0a"
```
