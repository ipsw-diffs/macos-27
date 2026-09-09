## RTSCV1

> `/System/Library/VideoProcessors/RTSCV1.bundle/Contents/MacOS/RTSCV1`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 764.21.3.0.0
-  __TEXT.__text: 0xf6dc
+  __TEXT.__text: 0xf544
   __TEXT.__auth_stubs: 0x530
   __TEXT.__objc_stubs: 0x1720
   __TEXT.__objc_methlist: 0xf74

   __TEXT.__objc_classname: 0x1c1
   __TEXT.__objc_methtype: 0x15b4
   __TEXT.__gcc_except_tab: 0x31c
-  __TEXT.__unwind_info: 0x430
+  __TEXT.__unwind_info: 0x550
   __DATA_CONST.__cfstring: 0x200
   __DATA_CONST.__objc_classlist: 0x80
   __DATA_CONST.__objc_protolist: 0x20
Functions:
~ _FigMotionGetSensorValidCropRect : 308 -> 296
~ _FigMotionGetMotionDataFromISP : 624 -> 620
~ _FigMotionGetISPHallData : 700 -> 696
~ _FigMotionComputeLensMovementAndSagForTimeStamp : 500 -> 508
~ _OUTLINED_FUNCTION_11 : 44 -> 32
~ _OUTLINED_FUNCTION_13 : 40 -> 28
~ _OUTLINED_FUNCTION_14 : 36 -> 24
~ _OUTLINED_FUNCTION_15 : 32 -> 20
~ _OUTLINED_FUNCTION_18 : 48 -> 36
~ _OUTLINED_FUNCTION_19 : 24 -> 12
~ -[RTSCShadersV1 objectAtIndexedSubscript:] : 76 -> 52
~ -[RTSCShadersV1 .cxx_destruct] : 92 -> 80
~ -[RTSCProcessorV1 process] : 176 -> 140
~ -[RTSCProcessorV1 setMetalCommandQueue:] : 100 -> 88
~ -[RTSCProcessorV1 _cachedTextureFromPixelBuffer:usage:] : 428 -> 416
~ -[RTSCProcessorV1 _bindCVPixleBuffer:usage:] : 152 -> 140
~ -[RTSCProcessorV1 _extractFinalCropRect] : 308 -> 296
~ -[RTSCProcessorV1 _calculateCropRectForOutputFOV:] : 392 -> 380
~ -[RTSCProcessorV1 _updateOutputIntrinsicForCropRect:] : 288 -> 284
~ -[RTSCProcessorV1 .cxx_destruct] : 188 -> 176
~ -[RTSCRealTimeStabilization _setDefaultParametersWithCameraExtrinsics:] : 676 -> 664
~ -[RTSCRealTimeStabilization _extractMetadataAndMotionDataFromDictionary:calibration:cameraMetadata:cameraPose:oisOffset:sagOffset:] : 2440 -> 2444
~ -[RTSCRealTimeStabilization .cxx_destruct] : 124 -> 112
~ _OUTLINED_FUNCTION_9 : 40 -> 28
~ -[RTSCFaceReframer _setDefaultParameters] : 136 -> 124
~ -[RTSCFaceReframer _computeHomographyForFramingCorrection:shiftCorrection:cameraMetadata:] : 104 -> 92
~ -[RTSCFaceReframer .cxx_destruct] : 68 -> 56
~ _OUTLINED_FUNCTION_3 : 40 -> 28
~ -[RTSCSpringAnimation _advance:] : 124 -> 112
~ -[RTSCMotionBlurFilter updateBlurVector:atTime:] : 304 -> 292
~ -[RTSCFaceTrackerV2 reset] : 144 -> 132
~ -[RTSCFaceTrackerV2 _updateFilterWithFaceBox:facePose:atTime:] : 292 -> 280
~ -[RTSCFaceTrackerV2 _updateFilterWithHeadPosition:covarianceMultiplier:] : 208 -> 196
~ -[RTSCFaceTrackerV2 _updateFilterWithPositionShift:covarianceMultiplier:] : 252 -> 240
~ -[RTSCFaceTrackerV2 .cxx_destruct] : 68 -> 56
~ -[RTSCFaceReframingV1 updateFacesWithMetadata:bufferSize:cameraMatrix:rotationFromPrevFrame:atTime:] : 764 -> 752
```
