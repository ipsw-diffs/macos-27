## CMCapture

> `/System/Library/PrivateFrameworks/CMCapture.framework/Versions/A/CMCapture`

```diff

-764.41.11.0.0
-  __TEXT.__text: 0x419974
-  __TEXT.__objc_methlist: 0x2b47c
-  __TEXT.__const: 0x143090
-  __TEXT.__cstring: 0x690c6
-  __TEXT.__oslogstring: 0x31611
+764.60.7.0.2
+  __TEXT.__text: 0x41abf4
+  __TEXT.__objc_methlist: 0x2b594
+  __TEXT.__const: 0x143080
+  __TEXT.__cstring: 0x69245
+  __TEXT.__oslogstring: 0x3184b
   __TEXT.__gcc_except_tab: 0x1840
   __TEXT.__dlopen_cstrs: 0x23e
   __TEXT.__ustring: 0x6ea
-  __TEXT.__unwind_info: 0xdda8
+  __TEXT.__unwind_info: 0xde08
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6220
+  __DATA_CONST.__const: 0x6240
   __DATA_CONST.__objc_classlist: 0x1400
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x380
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x12f90
+  __DATA_CONST.__objc_selrefs: 0x13010
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x12a8
-  __DATA_CONST.__objc_arraydata: 0x1690
-  __DATA_CONST.__got: 0x67a8
-  __AUTH_CONST.__const: 0x5688
-  __AUTH_CONST.__cfstring: 0x3ea60
-  __AUTH_CONST.__objc_const: 0x7a210
-  __AUTH_CONST.__objc_intobj: 0x4200
-  __AUTH_CONST.__objc_arrayobj: 0x1218
+  __DATA_CONST.__objc_arraydata: 0x16a0
+  __DATA_CONST.__got: 0x67b8
+  __AUTH_CONST.__const: 0x56a8
+  __AUTH_CONST.__cfstring: 0x3eac0
+  __AUTH_CONST.__objc_const: 0x7a470
+  __AUTH_CONST.__objc_intobj: 0x4230
+  __AUTH_CONST.__objc_arrayobj: 0x1230
   __AUTH_CONST.__objc_floatobj: 0x1b0
   __AUTH_CONST.__objc_doubleobj: 0x280
   __AUTH_CONST.__objc_dictobj: 0x118
   __AUTH_CONST.__auth_got: 0x2198
   __AUTH.__objc_data: 0x320
-  __DATA.__objc_ivar: 0x93a8
+  __DATA.__objc_ivar: 0x93dc
   __DATA.__data: 0x21c
   __DATA.__common: 0xf40
   __DATA.__bss: 0x11d8

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 25217
-  Symbols:   49460
-  CStrings:  13977
+  Functions: 25271
+  Symbols:   49523
+  CStrings:  13989
 
Symbols:
+ -[BWCinematographyObjectTrackingNode initWithCaptureDevice:tuningParameters:inferenceScheduler:frameRate:sourceBufferDimensions:prepareCinematographyOnInit:]
+ -[BWDeskCamNode realtimeStabilizationForDeskViewEnabled]
+ -[BWDeskCamNode setRealtimeStabilizationForDeskViewEnabled:]
+ -[BWMovieFileOutputAnalyticsPayload averageLuxValue]
+ -[BWMovieFileOutputAnalyticsPayload maxLuxValue]
+ -[BWMovieFileOutputAnalyticsPayload minLuxValue]
+ -[BWMovieFileOutputAnalyticsPayload setAverageLuxValue:]
+ -[BWMovieFileOutputAnalyticsPayload setMaxLuxValue:]
+ -[BWMovieFileOutputAnalyticsPayload setMinLuxValue:]
+ -[BWSmartCropNode _updateOutputStabilizationMetadata:]
+ -[CMCaptureLocalSessionVideoConfiguration setSupportsRealtimeStabilizationForCenterStage:]
+ -[CMCaptureLocalSessionVideoConfiguration setSupportsRealtimeStabilizationForDeskView:]
+ -[CMCaptureLocalSessionVideoConfiguration supportsRealtimeStabilizationForCenterStage]
+ -[CMCaptureLocalSessionVideoConfiguration supportsRealtimeStabilizationForDeskView]
+ -[FigCaptureCMIOCaptureSessionStreamFormat supportsRealtimeStabilizationForCenterStage]
+ -[FigCaptureCMIOCaptureSessionStreamFormat supportsRealtimeStabilizationForDeskView]
+ -[FigCaptureSourceConfiguration realtimeStabilizationForCenterStageEnabled]
+ -[FigCaptureSourceConfiguration realtimeStabilizationForDeskViewEnabled]
+ -[FigCaptureSourceConfiguration setRealtimeStabilizationForCenterStageEnabled:]
+ -[FigCaptureSourceConfiguration setRealtimeStabilizationForDeskViewEnabled:]
+ -[FigCaptureVideoDataSinkConfiguration realtimeStabilizationForCenterStageEnabled]
+ -[FigCaptureVideoDataSinkConfiguration realtimeStabilizationForDeskViewEnabled]
+ -[FigCaptureVideoDataSinkConfiguration setRealtimeStabilizationForCenterStageEnabled:]
+ -[FigCaptureVideoDataSinkConfiguration setRealtimeStabilizationForDeskViewEnabled:]
+ GCC_except_table103
+ GCC_except_table34
+ GCC_except_table355
+ GCC_except_table42
+ GCC_except_table64
+ GCC_except_table79
+ GCC_except_table87
+ GCC_except_table93
+ _FigCaptureSourceModulePersonalizationStatesByPosition
+ _OBJC_IVAR_$_BWDeskCamNode._realtimeStabilizationForDeskViewEnabled
+ _OBJC_IVAR_$_BWMovieFileOutputAnalyticsPayload._averageLuxValue
+ _OBJC_IVAR_$_BWMovieFileOutputAnalyticsPayload._maxLuxValue
+ _OBJC_IVAR_$_BWMovieFileOutputAnalyticsPayload._minLuxValue
+ _OBJC_IVAR_$_BWQuickTimeMovieFileSinkNode._luxLevelStats
+ _OBJC_IVAR_$_CMCaptureLocalSessionVideoConfiguration._supportsRealtimeStabilizationForCenterStage
+ _OBJC_IVAR_$_CMCaptureLocalSessionVideoConfiguration._supportsRealtimeStabilizationForDeskView
+ _OBJC_IVAR_$_FigCaptureCMIOCaptureSessionStreamFormat._supportsRealtimeStabilizationForCenterStage
+ _OBJC_IVAR_$_FigCaptureCMIOCaptureSessionStreamFormat._supportsRealtimeStabilizationForDeskView
+ _OBJC_IVAR_$_FigCaptureSourceConfiguration._realtimeStabilizationForCenterStageEnabled
+ _OBJC_IVAR_$_FigCaptureSourceConfiguration._realtimeStabilizationForDeskViewEnabled
+ _OBJC_IVAR_$_FigCaptureVideoDataSinkConfiguration._realtimeStabilizationForCenterStageEnabled
+ _OBJC_IVAR_$_FigCaptureVideoDataSinkConfiguration._realtimeStabilizationForDeskViewEnabled
+ ___82-[FigCaptureSourceManager copySourcesWithType:clientAuditToken:clientIsBincompat:]_block_invoke
+ ___block_descriptor_32_e15_B32?08Q16^B24l
+ _captureSession_updateInflightConfigurationWithPreviewSinkPropertyForKey
+ _cmclsc_setSessionConfiguration
+ _csp_upstreamVideoFormatRequirementsWithDimensions
+ _kFigCaptureSampleBufferMetadata_SmartFramingSuggestedFieldOfViewRectForSmartCrop
+ _kFigCaptureSampleBufferMetadata_VideoStabilizationOutputRotationVector
+ _objc_msgSend$_updateOutputStabilizationMetadata:
+ _objc_msgSend$graphStateTransitionTimeoutSeconds
+ _objc_msgSend$initWithCaptureDevice:tuningParameters:inferenceScheduler:frameRate:sourceBufferDimensions:prepareCinematographyOnInit:
+ _objc_msgSend$initWithDetectedObjectsInfo:cameraCalibrationData:cameraOrientation:timestamp:aspectRatio:sensorID:gravity:videoStabilizationOutputRotationVector:
+ _objc_msgSend$outputRotation
+ _objc_msgSend$realtimeStabilizationForCenterStageEnabled
+ _objc_msgSend$realtimeStabilizationForDeskViewEnabled
+ _objc_msgSend$setAdditionalOutputCameraRotation:
+ _objc_msgSend$setApplyStabilizationRotation:
+ _objc_msgSend$setOutputFOV:
+ _objc_msgSend$setRealtimeStabilizationEnabled:
+ _objc_msgSend$setRealtimeStabilizationForCenterStageEnabled:
+ _objc_msgSend$setRealtimeStabilizationForDeskViewEnabled:
+ _objc_msgSend$setRenderingEnabled:
+ _objc_msgSend$setStabilizationRotation:
+ _objc_msgSend$setSupportsRealtimeStabilizationForCenterStage:
+ _objc_msgSend$setSupportsRealtimeStabilizationForDeskView:
+ _objc_msgSend$supportsRealtimeStabilizationForCenterStage
+ _objc_msgSend$supportsRealtimeStabilizationForDeskView
- -[BWCinematographyObjectTrackingNode initWithCaptureDevice:tuningParameters:inferenceScheduler:frameRate:prepareCinematographyOnInit:]
- GCC_except_table353
- GCC_except_table38
- GCC_except_table60
- GCC_except_table78
- GCC_except_table89
- _FigCaptureSessionSetConfiguration
- _objc_msgSend$initWithCaptureDevice:tuningParameters:inferenceScheduler:frameRate:prepareCinematographyOnInit:
- _objc_msgSend$initWithDetectedObjectsInfo:cameraCalibrationData:cameraOrientation:timestamp:aspectRatio:sensorID:gravity:
CStrings:
+ ", CinematicFraming:1(CtrlMode:%d, RTSforCS: %d)"
+ "-[BWHVSScoringNode _handleYUVSampleBuffer:]"
+ "-[BWHVSScoringNode stopPersonalPhotographerSession]"
+ "00:32:25"
+ "<%@ %p> - fmt:%c%c%c%c, w:%d, h:%d, scs:%d, cs:%d, csroi:(%.2f, %.2f, %.2f, %.2f), csfm: %d, mfpx: %.2f, mfpy: %.2f, mfzm: %.2f, RTSforCS: %d, 10BitTF: %d, 10BitFromISP: %d, tfllbme: %d, rlas: %d, rle: %d"
+ "<%@ (CS:%c) (RTSforCS:%c) (10BitTF:%c) (10BitFromISP:%c) %p>"
+ "<<<< BWHVSScoringNode >>>> %s: Budget exhausted after frame %i, but Personal Photographer session sessionID:%u was already stopped, skipping duplicate finalization"
+ "<<<< BWHVSScoringNode >>>> %s: Ignoring stop: Personal Photographer session sessionID:%u already ended, skipping duplicate finalization"
+ "<<<< FigCaptureCMIOExtensionStream >>>> %s: %{public}@ outputWidth %d outputHeight %d minFrameRate %@ maxFrameRate %@ supportsCenterStage %c supportsRealtimStabilizationForCenterStage %c supports10BitTF %c supports10BitFromISP %c"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Increasing graph stop timeout of %@ to %d seconds for Personal Photographer under critical thermal pressure"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Received error %d during processing for captureID:%lld"
+ "<<<< FigCaptureSourceManager >>>> %s: Back wide module needs personalization, hiding %d source(s) that use it"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:10158"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:10651"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11235"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11686"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11721"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11910"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11919"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11931"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11938"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11972"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:12038"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:12207"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:13103"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:13201"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:16366"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:19231"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:19619"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:20502"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:20926"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:20928"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:22831"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:24231"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:24263"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:24419"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:25173"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:25198"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:25447"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:25804"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:6245"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:7942"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:7951"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:9034"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:9035"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:9054"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:9069"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:9344"
+ "LastShownBuild:BWHVSScoringNode.m:2916"
+ "LastShownBuild:BWHVSScoringNode.m:2919"
+ "LastShownBuild:BWHVSScoringNode.m:2988"
+ "LastShownBuild:BWHVSScoringNode.m:3508"
+ "LastShownBuild:BWImageQueueSinkNode.m:1151"
+ "LastShownBuild:BWImageQueueSinkNode.m:2097"
+ "LastShownBuild:BWPixelBufferTransferRenderer.m:684"
+ "LastShownBuild:FigCaptureSession.m:11420"
+ "LastShownBuild:FigCaptureSession.m:11615"
+ "LastShownBuild:FigCaptureSession.m:19505"
+ "LastShownBuild:FigCaptureSession.m:21070"
+ "LastShownBuild:FigCaptureSession.m:21073"
+ "LastShownBuild:FigCaptureSession.m:26450"
+ "LastShownBuild:FigCaptureSession.m:26463"
+ "LastShownBuild:FigCaptureSession.m:29546"
+ "LastShownBuild:FigCaptureSession.m:9325"
+ "LastShownBuild:FigCaptureSession.m:9328"
+ "LastShownBuild:FigCaptureSession.m:9331"
+ "LastShownBuild:FigCaptureSession.m:9334"
+ "LastShownBuild:FigCaptureSession.m:9345"
+ "LastShownBuild:FigCaptureSession.m:9356"
+ "LastShownBuild:FigCaptureSession.m:9374"
+ "LastShownBuild:FigCaptureSession.m:9419"
+ "LastShownBuild:FigCaptureSession.m:9423"
+ "LastShownBuild:FigCaptureSession.m:9447"
+ "LastShownBuild:FigCaptureSession.m:9462"
+ "LastShownBuild:FigCaptureSession.m:9466"
+ "LastShownBuild:FigCaptureSession.m:9469"
+ "LastShownBuild:FigCaptureSession.m:9593"
+ "LastShownBuild:FigCaptureSession.m:9625"
+ "LastShownBuild:FigCaptureSession.m:9637"
+ "LastShownDate:BWFigVideoCaptureDevice.m:10158"
+ "LastShownDate:BWFigVideoCaptureDevice.m:10651"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11235"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11686"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11721"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11910"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11919"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11931"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11938"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11972"
+ "LastShownDate:BWFigVideoCaptureDevice.m:12038"
+ "LastShownDate:BWFigVideoCaptureDevice.m:12207"
+ "LastShownDate:BWFigVideoCaptureDevice.m:13103"
+ "LastShownDate:BWFigVideoCaptureDevice.m:13201"
+ "LastShownDate:BWFigVideoCaptureDevice.m:16366"
+ "LastShownDate:BWFigVideoCaptureDevice.m:19231"
+ "LastShownDate:BWFigVideoCaptureDevice.m:19619"
+ "LastShownDate:BWFigVideoCaptureDevice.m:20502"
+ "LastShownDate:BWFigVideoCaptureDevice.m:20926"
+ "LastShownDate:BWFigVideoCaptureDevice.m:20928"
+ "LastShownDate:BWFigVideoCaptureDevice.m:22831"
+ "LastShownDate:BWFigVideoCaptureDevice.m:24231"
+ "LastShownDate:BWFigVideoCaptureDevice.m:24263"
+ "LastShownDate:BWFigVideoCaptureDevice.m:24419"
+ "LastShownDate:BWFigVideoCaptureDevice.m:25173"
+ "LastShownDate:BWFigVideoCaptureDevice.m:25198"
+ "LastShownDate:BWFigVideoCaptureDevice.m:25447"
+ "LastShownDate:BWFigVideoCaptureDevice.m:25804"
+ "LastShownDate:BWFigVideoCaptureDevice.m:6245"
+ "LastShownDate:BWFigVideoCaptureDevice.m:7942"
+ "LastShownDate:BWFigVideoCaptureDevice.m:7951"
+ "LastShownDate:BWFigVideoCaptureDevice.m:9034"
+ "LastShownDate:BWFigVideoCaptureDevice.m:9035"
+ "LastShownDate:BWFigVideoCaptureDevice.m:9054"
+ "LastShownDate:BWFigVideoCaptureDevice.m:9069"
+ "LastShownDate:BWFigVideoCaptureDevice.m:9344"
+ "LastShownDate:BWHVSScoringNode.m:2916"
+ "LastShownDate:BWHVSScoringNode.m:2919"
+ "LastShownDate:BWHVSScoringNode.m:2988"
+ "LastShownDate:BWHVSScoringNode.m:3508"
+ "LastShownDate:BWImageQueueSinkNode.m:1151"
+ "LastShownDate:BWImageQueueSinkNode.m:2097"
+ "LastShownDate:BWPixelBufferTransferRenderer.m:684"
+ "LastShownDate:FigCaptureSession.m:11420"
+ "LastShownDate:FigCaptureSession.m:11615"
+ "LastShownDate:FigCaptureSession.m:19505"
+ "LastShownDate:FigCaptureSession.m:21070"
+ "LastShownDate:FigCaptureSession.m:21073"
+ "LastShownDate:FigCaptureSession.m:26450"
+ "LastShownDate:FigCaptureSession.m:26463"
+ "LastShownDate:FigCaptureSession.m:29546"
+ "LastShownDate:FigCaptureSession.m:9325"
+ "LastShownDate:FigCaptureSession.m:9328"
+ "LastShownDate:FigCaptureSession.m:9331"
+ "LastShownDate:FigCaptureSession.m:9334"
+ "LastShownDate:FigCaptureSession.m:9345"
+ "LastShownDate:FigCaptureSession.m:9356"
+ "LastShownDate:FigCaptureSession.m:9374"
+ "LastShownDate:FigCaptureSession.m:9419"
+ "LastShownDate:FigCaptureSession.m:9423"
+ "LastShownDate:FigCaptureSession.m:9447"
+ "LastShownDate:FigCaptureSession.m:9462"
+ "LastShownDate:FigCaptureSession.m:9466"
+ "LastShownDate:FigCaptureSession.m:9469"
+ "LastShownDate:FigCaptureSession.m:9593"
+ "LastShownDate:FigCaptureSession.m:9625"
+ "LastShownDate:FigCaptureSession.m:9637"
+ "Oct 29 2026"
+ "Output Stabilization Metadata"
+ "attentionDetectionSupported"
+ "description=CameraCapture-764.60.7.0.2"
+ "realtimeStabilizationForCenterStage"
+ "realtimeStabilizationForCenterStageEnabled"
+ "realtimeStabilizationForCenterStageEnabled (%d -> %d)"
+ "realtimeStabilizationForDeskViewEnabled"
+ "realtimeStabilizationForDeskViewEnabled (%d -> %d)"
+ "supportsRealtimeStabilizationForCenterStage"
+ "supportsRealtimeStabilizationForDeskView"
- ", CinematicFraming:1(CtrlMode:%d)"
- "21:43:54"
- "<%@ %p> - fmt:%c%c%c%c, w:%d, h:%d, scs:%d, cs:%d, csroi:(%.2f, %.2f, %.2f, %.2f), csfm: %d, mfpx: %.2f, mfpy: %.2f, mfzm: %.2f, 10BitTF: %d, 10BitFromISP: %d, tfllbme: %d, rlas: %d, rle: %d"
- "<%@ (CS:%c) (10BitTF:%c) (10BitFromISP:%c) %p>"
- "<<<< FigCaptureCMIOExtensionStream >>>> %s: %{public}@ outputWidth %d outputHeight %d minFrameRate %@ maxFrameRate %@ supportsCenterStage %c supports10BitTF %c supports10BitFromISP %c"
- "BWImageQueueSinkNodePreviewMetricsFailure"
- "LastShownBuild:BWFigVideoCaptureDevice.m:10162"
- "LastShownBuild:BWFigVideoCaptureDevice.m:10655"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11239"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11690"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11725"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11914"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11923"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11935"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11942"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11976"
- "LastShownBuild:BWFigVideoCaptureDevice.m:12042"
- "LastShownBuild:BWFigVideoCaptureDevice.m:12211"
- "LastShownBuild:BWFigVideoCaptureDevice.m:13107"
- "LastShownBuild:BWFigVideoCaptureDevice.m:13205"
- "LastShownBuild:BWFigVideoCaptureDevice.m:16370"
- "LastShownBuild:BWFigVideoCaptureDevice.m:19235"
- "LastShownBuild:BWFigVideoCaptureDevice.m:19623"
- "LastShownBuild:BWFigVideoCaptureDevice.m:20506"
- "LastShownBuild:BWFigVideoCaptureDevice.m:20932"
- "LastShownBuild:BWFigVideoCaptureDevice.m:20934"
- "LastShownBuild:BWFigVideoCaptureDevice.m:22835"
- "LastShownBuild:BWFigVideoCaptureDevice.m:24235"
- "LastShownBuild:BWFigVideoCaptureDevice.m:24267"
- "LastShownBuild:BWFigVideoCaptureDevice.m:24423"
- "LastShownBuild:BWFigVideoCaptureDevice.m:25177"
- "LastShownBuild:BWFigVideoCaptureDevice.m:25202"
- "LastShownBuild:BWFigVideoCaptureDevice.m:25451"
- "LastShownBuild:BWFigVideoCaptureDevice.m:25808"
- "LastShownBuild:BWFigVideoCaptureDevice.m:6249"
- "LastShownBuild:BWFigVideoCaptureDevice.m:7946"
- "LastShownBuild:BWFigVideoCaptureDevice.m:7955"
- "LastShownBuild:BWFigVideoCaptureDevice.m:9038"
- "LastShownBuild:BWFigVideoCaptureDevice.m:9039"
- "LastShownBuild:BWFigVideoCaptureDevice.m:9058"
- "LastShownBuild:BWFigVideoCaptureDevice.m:9073"
- "LastShownBuild:BWFigVideoCaptureDevice.m:9348"
- "LastShownBuild:BWHVSScoringNode.m:2906"
- "LastShownBuild:BWHVSScoringNode.m:2914"
- "LastShownBuild:BWHVSScoringNode.m:2983"
- "LastShownBuild:BWHVSScoringNode.m:3503"
- "LastShownBuild:BWImageQueueSinkNode.m:1150"
- "LastShownBuild:BWImageQueueSinkNode.m:2096"
- "LastShownBuild:BWImageQueueSinkNode.m:341"
- "LastShownBuild:BWPixelBufferTransferRenderer.m:645"
- "LastShownBuild:FigCaptureSession.m:11394"
- "LastShownBuild:FigCaptureSession.m:11589"
- "LastShownBuild:FigCaptureSession.m:19395"
- "LastShownBuild:FigCaptureSession.m:20960"
- "LastShownBuild:FigCaptureSession.m:20963"
- "LastShownBuild:FigCaptureSession.m:26340"
- "LastShownBuild:FigCaptureSession.m:26353"
- "LastShownBuild:FigCaptureSession.m:29436"
- "LastShownBuild:FigCaptureSession.m:9293"
- "LastShownBuild:FigCaptureSession.m:9299"
- "LastShownBuild:FigCaptureSession.m:9302"
- "LastShownBuild:FigCaptureSession.m:9305"
- "LastShownBuild:FigCaptureSession.m:9308"
- "LastShownBuild:FigCaptureSession.m:9322"
- "LastShownBuild:FigCaptureSession.m:9330"
- "LastShownBuild:FigCaptureSession.m:9393"
- "LastShownBuild:FigCaptureSession.m:9397"
- "LastShownBuild:FigCaptureSession.m:9421"
- "LastShownBuild:FigCaptureSession.m:9436"
- "LastShownBuild:FigCaptureSession.m:9440"
- "LastShownBuild:FigCaptureSession.m:9443"
- "LastShownBuild:FigCaptureSession.m:9567"
- "LastShownBuild:FigCaptureSession.m:9573"
- "LastShownBuild:FigCaptureSession.m:9611"
- "LastShownDate:BWFigVideoCaptureDevice.m:10162"
- "LastShownDate:BWFigVideoCaptureDevice.m:10655"
- "LastShownDate:BWFigVideoCaptureDevice.m:11239"
- "LastShownDate:BWFigVideoCaptureDevice.m:11690"
- "LastShownDate:BWFigVideoCaptureDevice.m:11725"
- "LastShownDate:BWFigVideoCaptureDevice.m:11914"
- "LastShownDate:BWFigVideoCaptureDevice.m:11923"
- "LastShownDate:BWFigVideoCaptureDevice.m:11935"
- "LastShownDate:BWFigVideoCaptureDevice.m:11942"
- "LastShownDate:BWFigVideoCaptureDevice.m:11976"
- "LastShownDate:BWFigVideoCaptureDevice.m:12042"
- "LastShownDate:BWFigVideoCaptureDevice.m:12211"
- "LastShownDate:BWFigVideoCaptureDevice.m:13107"
- "LastShownDate:BWFigVideoCaptureDevice.m:13205"
- "LastShownDate:BWFigVideoCaptureDevice.m:16370"
- "LastShownDate:BWFigVideoCaptureDevice.m:19235"
- "LastShownDate:BWFigVideoCaptureDevice.m:19623"
- "LastShownDate:BWFigVideoCaptureDevice.m:20506"
- "LastShownDate:BWFigVideoCaptureDevice.m:20932"
- "LastShownDate:BWFigVideoCaptureDevice.m:20934"
- "LastShownDate:BWFigVideoCaptureDevice.m:22835"
- "LastShownDate:BWFigVideoCaptureDevice.m:24235"
- "LastShownDate:BWFigVideoCaptureDevice.m:24267"
- "LastShownDate:BWFigVideoCaptureDevice.m:24423"
- "LastShownDate:BWFigVideoCaptureDevice.m:25177"
- "LastShownDate:BWFigVideoCaptureDevice.m:25202"
- "LastShownDate:BWFigVideoCaptureDevice.m:25451"
- "LastShownDate:BWFigVideoCaptureDevice.m:25808"
- "LastShownDate:BWFigVideoCaptureDevice.m:6249"
- "LastShownDate:BWFigVideoCaptureDevice.m:7946"
- "LastShownDate:BWFigVideoCaptureDevice.m:7955"
- "LastShownDate:BWFigVideoCaptureDevice.m:9038"
- "LastShownDate:BWFigVideoCaptureDevice.m:9039"
- "LastShownDate:BWFigVideoCaptureDevice.m:9058"
- "LastShownDate:BWFigVideoCaptureDevice.m:9073"
- "LastShownDate:BWFigVideoCaptureDevice.m:9348"
- "LastShownDate:BWHVSScoringNode.m:2906"
- "LastShownDate:BWHVSScoringNode.m:2914"
- "LastShownDate:BWHVSScoringNode.m:2983"
- "LastShownDate:BWHVSScoringNode.m:3503"
- "LastShownDate:BWImageQueueSinkNode.m:1150"
- "LastShownDate:BWImageQueueSinkNode.m:2096"
- "LastShownDate:BWImageQueueSinkNode.m:341"
- "LastShownDate:BWPixelBufferTransferRenderer.m:645"
- "LastShownDate:FigCaptureSession.m:11394"
- "LastShownDate:FigCaptureSession.m:11589"
- "LastShownDate:FigCaptureSession.m:19395"
- "LastShownDate:FigCaptureSession.m:20960"
- "LastShownDate:FigCaptureSession.m:20963"
- "LastShownDate:FigCaptureSession.m:26340"
- "LastShownDate:FigCaptureSession.m:26353"
- "LastShownDate:FigCaptureSession.m:29436"
- "LastShownDate:FigCaptureSession.m:9293"
- "LastShownDate:FigCaptureSession.m:9299"
- "LastShownDate:FigCaptureSession.m:9302"
- "LastShownDate:FigCaptureSession.m:9305"
- "LastShownDate:FigCaptureSession.m:9308"
- "LastShownDate:FigCaptureSession.m:9322"
- "LastShownDate:FigCaptureSession.m:9330"
- "LastShownDate:FigCaptureSession.m:9393"
- "LastShownDate:FigCaptureSession.m:9397"
- "LastShownDate:FigCaptureSession.m:9421"
- "LastShownDate:FigCaptureSession.m:9436"
- "LastShownDate:FigCaptureSession.m:9440"
- "LastShownDate:FigCaptureSession.m:9443"
- "LastShownDate:FigCaptureSession.m:9567"
- "LastShownDate:FigCaptureSession.m:9573"
- "LastShownDate:FigCaptureSession.m:9611"
- "Oct  8 2026"
- "Preview metrics failure. Average frame rate: %.2f fps. Average latency: %.3f sec. (Interval: %.1f sec. Expected: %.2f fps / %.3f sec.)"
- "description=CameraCapture-764.41.11"
```
