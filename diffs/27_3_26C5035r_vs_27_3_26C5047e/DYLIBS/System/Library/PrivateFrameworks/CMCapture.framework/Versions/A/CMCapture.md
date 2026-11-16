## CMCapture

> `/System/Library/PrivateFrameworks/CMCapture.framework/Versions/A/CMCapture`

```diff

-764.60.7.0.2
-  __TEXT.__text: 0x41abf4
-  __TEXT.__objc_methlist: 0x2b594
+764.60.13.0.1
+  __TEXT.__text: 0x41c0f4
+  __TEXT.__objc_methlist: 0x2b6a4
   __TEXT.__const: 0x143080
-  __TEXT.__cstring: 0x69245
-  __TEXT.__oslogstring: 0x3184b
-  __TEXT.__gcc_except_tab: 0x1840
+  __TEXT.__cstring: 0x694c5
+  __TEXT.__oslogstring: 0x319d9
+  __TEXT.__gcc_except_tab: 0x186c
   __TEXT.__dlopen_cstrs: 0x23e
   __TEXT.__ustring: 0x6ea
-  __TEXT.__unwind_info: 0xde08
+  __TEXT.__unwind_info: 0xde68
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6240
+  __DATA_CONST.__const: 0x6260
   __DATA_CONST.__objc_classlist: 0x1400
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x380
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x13010
+  __DATA_CONST.__objc_selrefs: 0x130c8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x12a8
   __DATA_CONST.__objc_arraydata: 0x16a0
-  __DATA_CONST.__got: 0x67b8
+  __DATA_CONST.__got: 0x67c0
   __AUTH_CONST.__const: 0x56a8
-  __AUTH_CONST.__cfstring: 0x3eac0
-  __AUTH_CONST.__objc_const: 0x7a470
+  __AUTH_CONST.__cfstring: 0x3ebc0
+  __AUTH_CONST.__objc_const: 0x7a560
   __AUTH_CONST.__objc_intobj: 0x4230
   __AUTH_CONST.__objc_arrayobj: 0x1230
   __AUTH_CONST.__objc_floatobj: 0x1b0

   __AUTH_CONST.__objc_dictobj: 0x118
   __AUTH_CONST.__auth_got: 0x2198
   __AUTH.__objc_data: 0x320
-  __DATA.__objc_ivar: 0x93dc
+  __DATA.__objc_ivar: 0x93f0
   __DATA.__data: 0x21c
   __DATA.__common: 0xf40
   __DATA.__bss: 0x11d8

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 25271
-  Symbols:   49523
-  CStrings:  13989
+  Functions: 25306
+  Symbols:   49586
+  CStrings:  14006
 
Symbols:
+ -[BWCinematicFramingNode initWithOutputDimensions:cameraInfoByPortType:horizontalSensorBinningFactor:verticalSensorBinningFactor:deviceOrientationCorrectionEnabled:stillImageCaptureEnabled:objectMetadataIdentifiers:maxLossyCompressionLevel:portTypes:cinematicFramingControls:manualFramingFocalLengthMultiplier:cameraHasDistortionCoefficients:cameraHasCalibrationValidMaxRadius:centerStageMetadataDeliveryEnabled:pipelineType:downStreamRequires10BitPixelFormat:]
+ -[BWFigCaptureDeviceClient updateClientAuditToken:]
+ -[BWFigCaptureDeviceVendor updatePrewarmedClientWithClientAuditToken:]
+ -[BWFigCaptureDeviceVendorDeviceState streamsOwedAtTakeBackDevice]
+ -[BWFigVideoCaptureDevice _terminatePendingStillImageCaptureNowRetryForSuspendedCaptureStream:]
+ -[BWFigVideoCaptureDevice captureStreamDidSuspend:]
+ -[BWGraph _handleTimeoutWithStopping:description:briefReason:offendingNodes:]
+ -[BWGraph _timedOutWaitingForOperationToCompleteWithDescription:briefReason:offendingNodes:]
+ -[BWMultiStreamCameraSourceNode(GraphTimeoutCrashAttribution) _timedOutWaitingForBackColorCameraToStartOrCommit:]
+ -[BWMultiStreamCameraSourceNode(GraphTimeoutCrashAttribution) _timedOutWaitingForBackColorCameraToStop:]
+ -[BWMultiStreamCameraSourceNode(GraphTimeoutCrashAttribution) _timedOutWaitingForCameraSourceNodeToStartOrCommit:]
+ -[BWMultiStreamCameraSourceNode(GraphTimeoutCrashAttribution) _timedOutWaitingForCameraSourceNodeToStop:]
+ -[BWMultiStreamCameraSourceNode(GraphTimeoutCrashAttribution) _timedOutWaitingForFrontColorCameraToStartOrCommit:]
+ -[BWMultiStreamCameraSourceNode(GraphTimeoutCrashAttribution) _timedOutWaitingForFrontColorCameraToStop:]
+ -[BWMultiStreamCameraSourceNode(GraphTimeoutCrashAttribution) _timedOutWaitingForFrontInfraredCameraToStartOrCommit:]
+ -[BWMultiStreamCameraSourceNode(GraphTimeoutCrashAttribution) _timedOutWaitingForFrontInfraredCameraToStop:]
+ -[BWMultiStreamCameraSourceNode(GraphTimeoutCrashAttribution) graphTimedOutWithStopping:crashInfo:]
+ -[BWNode graphTimedOutWithStopping:crashInfo:]
+ -[BWPreviewStitcherRenderer _initTrueVideoHDRtoSDRCIContext]
+ -[BWPreviewStitcherRenderer _newCIContextWithOptions:]
+ -[BWPreviewStitcherRenderer _renderCIImage:context:toRenderDestination:sourceRect:destinationRect:]
+ -[FigCaptureSessionConfiguration usesPerceptionThumbnailChannel:]
+ -[FigCaptureSourceConfiguration forceManualFramingEnabled]
+ -[FigCaptureSourceConfiguration perceptionThumbnailChannelCoexistenceEnabled]
+ -[FigCaptureSourceConfiguration setForceManualFramingEnabled:]
+ -[FigCaptureSourceConfiguration setPerceptionThumbnailChannelCoexistenceEnabled:]
+ -[FigCaptureSourceManager deactivateAttachedVideoSource:device:sessionID:]
+ -[FigCaptureSourceVideoFormat forceManualFramingForRotationCorrection]
+ -[FigCaptureSourceVideoFormat isPerceptionThumbnailChannelCoexistenceSupported]
+ -[FigCaptureSourceVideoFormat manualFramingCropWidth]
+ GCC_except_table128
+ GCC_except_table141
+ GCC_except_table154
+ GCC_except_table164
+ GCC_except_table195
+ GCC_except_table208
+ GCC_except_table211
+ GCC_except_table223
+ GCC_except_table229
+ GCC_except_table262
+ GCC_except_table313
+ GCC_except_table369
+ GCC_except_table388
+ GCC_except_table421
+ GCC_except_table448
+ GCC_except_table450
+ GCC_except_table467
+ GCC_except_table572
+ GCC_except_table63
+ GCC_except_table76
+ GCC_except_table760
+ GCC_except_table89
+ GCC_except_table94
+ _FigCaptureClientApplicationIDIsSafariWebContentVariant
+ _FigCaptureSourceFormatKey_ForceManualFramingForRotationCorrection
+ _FigCaptureSourceFormatKey_ManualFramingCropWidth
+ _FigCaptureSourceFormatKey_PerceptionThumbnailChannelCoexistenceSupported
+ _FigVideoCaptureSourceCopySessionID
+ _OBJC_IVAR_$_BWCinematicFramingNode._manualFramingFocalLengthMultiplier
+ _OBJC_IVAR_$_BWFigCaptureDeviceVendorDeviceState._streamsOwedAtTakeBackDevice
+ _OBJC_IVAR_$_BWPreviewStitcherRenderer._trueVideoHDRtoSDRCIContext
+ _OBJC_IVAR_$_FigCaptureSourceConfiguration._forceManualFramingEnabled
+ _OBJC_IVAR_$_FigCaptureSourceConfiguration._perceptionThumbnailChannelCoexistenceEnabled
+ __OBJC_$_INSTANCE_METHODS_BWMultiStreamCameraSourceNode(GraphTimeoutCrashAttribution)
+ ___51-[BWFigVideoCaptureDevice captureStreamDidSuspend:]_block_invoke
+ ___70-[BWFigCaptureDeviceVendor updatePrewarmedClientWithClientAuditToken:]_block_invoke
+ ___FigVideoCaptureSourceCopySessionID_block_invoke
+ _kCGColorSpaceExtendedLinearITUR_2020
+ _kFigCaptureMetadata_ExifLensMinFNumber
+ _objc_msgSend$_initTrueVideoHDRtoSDRCIContext
+ _objc_msgSend$_newCIContextWithOptions:
+ _objc_msgSend$_renderCIImage:context:toRenderDestination:sourceRect:destinationRect:
+ _objc_msgSend$_timedOutWaitingForBackColorCameraToStartOrCommit:
+ _objc_msgSend$_timedOutWaitingForBackColorCameraToStop:
+ _objc_msgSend$_timedOutWaitingForCameraSourceNodeToStartOrCommit:
+ _objc_msgSend$_timedOutWaitingForCameraSourceNodeToStop:
+ _objc_msgSend$_timedOutWaitingForFrontColorCameraToStartOrCommit:
+ _objc_msgSend$_timedOutWaitingForFrontColorCameraToStop:
+ _objc_msgSend$_timedOutWaitingForFrontInfraredCameraToStartOrCommit:
+ _objc_msgSend$_timedOutWaitingForFrontInfraredCameraToStop:
+ _objc_msgSend$_timedOutWaitingForOperationToCompleteWithDescription:briefReason:offendingNodes:
+ _objc_msgSend$captureStreamDidSuspend:
+ _objc_msgSend$deactivateAttachedVideoSource:device:sessionID:
+ _objc_msgSend$forceManualFramingEnabled
+ _objc_msgSend$initWithOutputDimensions:cameraInfoByPortType:horizontalSensorBinningFactor:verticalSensorBinningFactor:deviceOrientationCorrectionEnabled:stillImageCaptureEnabled:objectMetadataIdentifiers:maxLossyCompressionLevel:portTypes:cinematicFramingControls:manualFramingFocalLengthMultiplier:cameraHasDistortionCoefficients:cameraHasCalibrationValidMaxRadius:centerStageMetadataDeliveryEnabled:pipelineType:downStreamRequires10BitPixelFormat:
+ _objc_msgSend$isPerceptionThumbnailChannelCoexistenceSupported
+ _objc_msgSend$perceptionThumbnailChannelCoexistenceEnabled
+ _objc_msgSend$setArray:
+ _objc_msgSend$setForceManualFramingEnabled:
+ _objc_msgSend$setManualFramingFocalLengthMultiplier:
+ _objc_msgSend$setPerceptionThumbnailChannelCoexistenceEnabled:
+ _objc_msgSend$streamsOwedAtTakeBackDevice
- -[BWCinematicFramingNode initWithOutputDimensions:cameraInfoByPortType:horizontalSensorBinningFactor:verticalSensorBinningFactor:deviceOrientationCorrectionEnabled:stillImageCaptureEnabled:objectMetadataIdentifiers:maxLossyCompressionLevel:portTypes:cinematicFramingControls:cameraHasDistortionCoefficients:cameraHasCalibrationValidMaxRadius:centerStageMetadataDeliveryEnabled:pipelineType:downStreamRequires10BitPixelFormat:]
- -[BWPreviewStitcherRenderer _renderCIImage:toRenderDestination:sourceRect:destinationRect:]
- -[FigCaptureSourceManager deactivateAttachedVideoSource:device:]
- GCC_except_table123
- GCC_except_table137
- GCC_except_table150
- GCC_except_table160
- GCC_except_table191
- GCC_except_table207
- GCC_except_table209
- GCC_except_table215
- GCC_except_table258
- GCC_except_table309
- GCC_except_table366
- GCC_except_table385
- GCC_except_table418
- GCC_except_table445
- GCC_except_table447
- GCC_except_table464
- GCC_except_table569
- GCC_except_table72
- GCC_except_table757
- GCC_except_table90
- _OUTLINED_FUNCTION_539
- __OBJC_$_INSTANCE_METHODS_BWMultiStreamCameraSourceNode
- _objc_msgSend$_renderCIImage:toRenderDestination:sourceRect:destinationRect:
- _objc_msgSend$deactivateAttachedVideoSource:device:
- _objc_msgSend$initWithOutputDimensions:cameraInfoByPortType:horizontalSensorBinningFactor:verticalSensorBinningFactor:deviceOrientationCorrectionEnabled:stillImageCaptureEnabled:objectMetadataIdentifiers:maxLossyCompressionLevel:portTypes:cinematicFramingControls:cameraHasDistortionCoefficients:cameraHasCalibrationValidMaxRadius:centerStageMetadataDeliveryEnabled:pipelineType:downStreamRequires10BitPixelFormat:
- _objc_msgSend$isLowPowerModeEnabled
CStrings:
+ ", PerceptionThumbnailChannelCoex:1"
+ ", forceMF:1"
+ "-[BWFigCaptureDeviceClient updateClientAuditToken:]"
+ "-[BWFigCaptureDeviceVendor updatePrewarmedClientWithClientAuditToken:]_block_invoke"
+ "-[BWFigVideoCaptureDevice _terminatePendingStillImageCaptureNowRetryForSuspendedCaptureStream:]"
+ "-[FigCaptureSessionAttachedSessionManager attachToRunningSession:]"
+ "01:19:31"
+ "<<<< BWFigCaptureDeviceVendor >>>> %s: Device %p still has streams owed by a previous client: %@. Invalidating it so new client %@ gets a new device"
+ "<<<< BWFigCaptureDeviceVendor >>>> %s: Updating client audit token for pid %d to pid %d"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: '%{public}@' was suspended with a pending StillImageCaptureNow retry, terminating capture for captureID:%lld"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: Driver/firmware is busy, stopping retrying (count:%d, suspended:%d, err=%d)"
+ "ExifLensMinFNumber"
+ "ForceManualFramingForRotationCorrection"
+ "LastShownBuild:BWFigCaptureDeviceVendor.m:1619"
+ "LastShownBuild:BWFigCaptureDeviceVendor.m:3075"
+ "LastShownBuild:BWFigCaptureDeviceVendor.m:3712"
+ "LastShownBuild:BWFigCaptureDeviceVendor.m:3725"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:10194"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:10687"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11271"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11722"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11757"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11946"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11955"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11967"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11974"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:12008"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:12074"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:12245"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:13141"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:13239"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:16414"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:19279"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:19667"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:20550"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:20974"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:20976"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:20978"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:22879"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:24279"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:24311"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:24467"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:25221"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:25246"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:25495"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:25852"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:6281"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:7978"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:7987"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:9070"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:9071"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:9090"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:9105"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:9380"
+ "LastShownBuild:BWFigVideoCaptureStream.m:3954"
+ "LastShownBuild:BWFigVideoCaptureStream.m:4374"
+ "LastShownBuild:BWGraph.m:2707"
+ "LastShownBuild:BWGraph.m:3617"
+ "LastShownBuild:BWGraph.m:3620"
+ "LastShownBuild:BWGraph.m:3633"
+ "LastShownBuild:BWGraph.m:3636"
+ "LastShownBuild:BWGraph.m:3639"
+ "LastShownBuild:BWHVSScoringNode.m:3517"
+ "LastShownBuild:BWMultiStreamCameraSourceNode.m:13962"
+ "LastShownBuild:BWMultiStreamCameraSourceNode.m:13978"
+ "LastShownBuild:BWPreviewStitcherNode.m:3429"
+ "LastShownBuild:FigCaptureMetadataUtilities.m:1556"
+ "LastShownBuild:FigCaptureMetadataUtilities.m:6337"
+ "LastShownBuild:FigCaptureSession.m:1020"
+ "LastShownBuild:FigCaptureSession.m:11422"
+ "LastShownBuild:FigCaptureSession.m:11617"
+ "LastShownBuild:FigCaptureSession.m:19523"
+ "LastShownBuild:FigCaptureSession.m:21088"
+ "LastShownBuild:FigCaptureSession.m:21091"
+ "LastShownBuild:FigCaptureSession.m:26487"
+ "LastShownBuild:FigCaptureSession.m:26500"
+ "LastShownBuild:FigCaptureSession.m:29592"
+ "LastShownBuild:FigCaptureSession.m:5227"
+ "LastShownBuild:FigCaptureSession.m:9321"
+ "LastShownBuild:FigCaptureSession.m:9327"
+ "LastShownBuild:FigCaptureSession.m:9330"
+ "LastShownBuild:FigCaptureSession.m:9333"
+ "LastShownBuild:FigCaptureSession.m:9336"
+ "LastShownBuild:FigCaptureSession.m:9347"
+ "LastShownBuild:FigCaptureSession.m:9350"
+ "LastShownBuild:FigCaptureSession.m:9358"
+ "LastShownBuild:FigCaptureSession.m:9376"
+ "LastShownBuild:FigCaptureSession.m:9421"
+ "LastShownBuild:FigCaptureSession.m:9425"
+ "LastShownBuild:FigCaptureSession.m:9449"
+ "LastShownBuild:FigCaptureSession.m:9464"
+ "LastShownBuild:FigCaptureSession.m:9468"
+ "LastShownBuild:FigCaptureSession.m:9471"
+ "LastShownBuild:FigCaptureSession.m:9595"
+ "LastShownBuild:FigCaptureSession.m:9601"
+ "LastShownBuild:FigCaptureSession.m:9627"
+ "LastShownBuild:FigCaptureSession.m:9639"
+ "LastShownBuild:FigCaptureSessionStateManager.m:349"
+ "LastShownBuild:FigCaptureSessionStateManager.m:376"
+ "LastShownBuild:FigCaptureSessionStateManager.m:513"
+ "LastShownDate:BWFigCaptureDeviceVendor.m:1619"
+ "LastShownDate:BWFigCaptureDeviceVendor.m:3075"
+ "LastShownDate:BWFigCaptureDeviceVendor.m:3712"
+ "LastShownDate:BWFigCaptureDeviceVendor.m:3725"
+ "LastShownDate:BWFigVideoCaptureDevice.m:10194"
+ "LastShownDate:BWFigVideoCaptureDevice.m:10687"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11271"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11722"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11757"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11946"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11955"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11967"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11974"
+ "LastShownDate:BWFigVideoCaptureDevice.m:12008"
+ "LastShownDate:BWFigVideoCaptureDevice.m:12074"
+ "LastShownDate:BWFigVideoCaptureDevice.m:12245"
+ "LastShownDate:BWFigVideoCaptureDevice.m:13141"
+ "LastShownDate:BWFigVideoCaptureDevice.m:13239"
+ "LastShownDate:BWFigVideoCaptureDevice.m:16414"
+ "LastShownDate:BWFigVideoCaptureDevice.m:19279"
+ "LastShownDate:BWFigVideoCaptureDevice.m:19667"
+ "LastShownDate:BWFigVideoCaptureDevice.m:20550"
+ "LastShownDate:BWFigVideoCaptureDevice.m:20974"
+ "LastShownDate:BWFigVideoCaptureDevice.m:20976"
+ "LastShownDate:BWFigVideoCaptureDevice.m:20978"
+ "LastShownDate:BWFigVideoCaptureDevice.m:22879"
+ "LastShownDate:BWFigVideoCaptureDevice.m:24279"
+ "LastShownDate:BWFigVideoCaptureDevice.m:24311"
+ "LastShownDate:BWFigVideoCaptureDevice.m:24467"
+ "LastShownDate:BWFigVideoCaptureDevice.m:25221"
+ "LastShownDate:BWFigVideoCaptureDevice.m:25246"
+ "LastShownDate:BWFigVideoCaptureDevice.m:25495"
+ "LastShownDate:BWFigVideoCaptureDevice.m:25852"
+ "LastShownDate:BWFigVideoCaptureDevice.m:6281"
+ "LastShownDate:BWFigVideoCaptureDevice.m:7978"
+ "LastShownDate:BWFigVideoCaptureDevice.m:7987"
+ "LastShownDate:BWFigVideoCaptureDevice.m:9070"
+ "LastShownDate:BWFigVideoCaptureDevice.m:9071"
+ "LastShownDate:BWFigVideoCaptureDevice.m:9090"
+ "LastShownDate:BWFigVideoCaptureDevice.m:9105"
+ "LastShownDate:BWFigVideoCaptureDevice.m:9380"
+ "LastShownDate:BWFigVideoCaptureStream.m:3954"
+ "LastShownDate:BWFigVideoCaptureStream.m:4374"
+ "LastShownDate:BWGraph.m:2707"
+ "LastShownDate:BWGraph.m:3617"
+ "LastShownDate:BWGraph.m:3620"
+ "LastShownDate:BWGraph.m:3633"
+ "LastShownDate:BWGraph.m:3636"
+ "LastShownDate:BWGraph.m:3639"
+ "LastShownDate:BWHVSScoringNode.m:3517"
+ "LastShownDate:BWMultiStreamCameraSourceNode.m:13962"
+ "LastShownDate:BWMultiStreamCameraSourceNode.m:13978"
+ "LastShownDate:BWPreviewStitcherNode.m:3429"
+ "LastShownDate:FigCaptureMetadataUtilities.m:1556"
+ "LastShownDate:FigCaptureMetadataUtilities.m:6337"
+ "LastShownDate:FigCaptureSession.m:1020"
+ "LastShownDate:FigCaptureSession.m:11422"
+ "LastShownDate:FigCaptureSession.m:11617"
+ "LastShownDate:FigCaptureSession.m:19523"
+ "LastShownDate:FigCaptureSession.m:21088"
+ "LastShownDate:FigCaptureSession.m:21091"
+ "LastShownDate:FigCaptureSession.m:26487"
+ "LastShownDate:FigCaptureSession.m:26500"
+ "LastShownDate:FigCaptureSession.m:29592"
+ "LastShownDate:FigCaptureSession.m:5227"
+ "LastShownDate:FigCaptureSession.m:9321"
+ "LastShownDate:FigCaptureSession.m:9327"
+ "LastShownDate:FigCaptureSession.m:9330"
+ "LastShownDate:FigCaptureSession.m:9333"
+ "LastShownDate:FigCaptureSession.m:9336"
+ "LastShownDate:FigCaptureSession.m:9347"
+ "LastShownDate:FigCaptureSession.m:9350"
+ "LastShownDate:FigCaptureSession.m:9358"
+ "LastShownDate:FigCaptureSession.m:9376"
+ "LastShownDate:FigCaptureSession.m:9421"
+ "LastShownDate:FigCaptureSession.m:9425"
+ "LastShownDate:FigCaptureSession.m:9449"
+ "LastShownDate:FigCaptureSession.m:9464"
+ "LastShownDate:FigCaptureSession.m:9468"
+ "LastShownDate:FigCaptureSession.m:9471"
+ "LastShownDate:FigCaptureSession.m:9595"
+ "LastShownDate:FigCaptureSession.m:9601"
+ "LastShownDate:FigCaptureSession.m:9627"
+ "LastShownDate:FigCaptureSession.m:9639"
+ "LastShownDate:FigCaptureSessionStateManager.m:349"
+ "LastShownDate:FigCaptureSessionStateManager.m:376"
+ "LastShownDate:FigCaptureSessionStateManager.m:513"
+ "ManualFramingCropWidth"
+ "Nov 10 2026"
+ "PerceptionThumbnailChannelCoexistenceSupported"
+ "description=CameraCapture-764.60.13.0.1"
+ "forceManualFramingEnabled"
+ "forceManualFramingEnabled (%d -> %d)"
+ "perceptionThumbnailChannelCoexistenceEnabled"
+ "perceptionThumbnailChannelCoexistenceEnabled (%d -> %d)"
- "00:32:25"
- "<<<< BWFigVideoCaptureDevice >>>> %s: Driver/firmware is busy, stopping retrying (count:%d, err=%d)"
- "LastShownBuild:BWFigCaptureDeviceVendor.m:1577"
- "LastShownBuild:BWFigCaptureDeviceVendor.m:3031"
- "LastShownBuild:BWFigCaptureDeviceVendor.m:3668"
- "LastShownBuild:BWFigCaptureDeviceVendor.m:3681"
- "LastShownBuild:BWFigVideoCaptureDevice.m:10158"
- "LastShownBuild:BWFigVideoCaptureDevice.m:10651"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11235"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11686"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11721"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11910"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11919"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11931"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11938"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11972"
- "LastShownBuild:BWFigVideoCaptureDevice.m:12038"
- "LastShownBuild:BWFigVideoCaptureDevice.m:12207"
- "LastShownBuild:BWFigVideoCaptureDevice.m:13103"
- "LastShownBuild:BWFigVideoCaptureDevice.m:13201"
- "LastShownBuild:BWFigVideoCaptureDevice.m:16366"
- "LastShownBuild:BWFigVideoCaptureDevice.m:19231"
- "LastShownBuild:BWFigVideoCaptureDevice.m:19619"
- "LastShownBuild:BWFigVideoCaptureDevice.m:20502"
- "LastShownBuild:BWFigVideoCaptureDevice.m:20926"
- "LastShownBuild:BWFigVideoCaptureDevice.m:20928"
- "LastShownBuild:BWFigVideoCaptureDevice.m:20930"
- "LastShownBuild:BWFigVideoCaptureDevice.m:22831"
- "LastShownBuild:BWFigVideoCaptureDevice.m:24231"
- "LastShownBuild:BWFigVideoCaptureDevice.m:24263"
- "LastShownBuild:BWFigVideoCaptureDevice.m:24419"
- "LastShownBuild:BWFigVideoCaptureDevice.m:25173"
- "LastShownBuild:BWFigVideoCaptureDevice.m:25198"
- "LastShownBuild:BWFigVideoCaptureDevice.m:25447"
- "LastShownBuild:BWFigVideoCaptureDevice.m:25804"
- "LastShownBuild:BWFigVideoCaptureDevice.m:6245"
- "LastShownBuild:BWFigVideoCaptureDevice.m:7942"
- "LastShownBuild:BWFigVideoCaptureDevice.m:7951"
- "LastShownBuild:BWFigVideoCaptureDevice.m:9034"
- "LastShownBuild:BWFigVideoCaptureDevice.m:9035"
- "LastShownBuild:BWFigVideoCaptureDevice.m:9054"
- "LastShownBuild:BWFigVideoCaptureDevice.m:9069"
- "LastShownBuild:BWFigVideoCaptureDevice.m:9344"
- "LastShownBuild:BWFigVideoCaptureStream.m:3950"
- "LastShownBuild:BWFigVideoCaptureStream.m:4370"
- "LastShownBuild:BWGraph.m:2684"
- "LastShownBuild:BWGraph.m:3594"
- "LastShownBuild:BWGraph.m:3597"
- "LastShownBuild:BWGraph.m:3610"
- "LastShownBuild:BWGraph.m:3613"
- "LastShownBuild:BWGraph.m:3616"
- "LastShownBuild:BWHVSScoringNode.m:3508"
- "LastShownBuild:BWMultiStreamCameraSourceNode.m:13942"
- "LastShownBuild:BWMultiStreamCameraSourceNode.m:13958"
- "LastShownBuild:BWPreviewStitcherNode.m:3432"
- "LastShownBuild:FigCaptureMetadataUtilities.m:1546"
- "LastShownBuild:FigCaptureMetadataUtilities.m:6327"
- "LastShownBuild:FigCaptureSession.m:1018"
- "LastShownBuild:FigCaptureSession.m:11420"
- "LastShownBuild:FigCaptureSession.m:11615"
- "LastShownBuild:FigCaptureSession.m:19505"
- "LastShownBuild:FigCaptureSession.m:21070"
- "LastShownBuild:FigCaptureSession.m:21073"
- "LastShownBuild:FigCaptureSession.m:26450"
- "LastShownBuild:FigCaptureSession.m:26463"
- "LastShownBuild:FigCaptureSession.m:29546"
- "LastShownBuild:FigCaptureSession.m:5225"
- "LastShownBuild:FigCaptureSession.m:9319"
- "LastShownBuild:FigCaptureSession.m:9325"
- "LastShownBuild:FigCaptureSession.m:9328"
- "LastShownBuild:FigCaptureSession.m:9331"
- "LastShownBuild:FigCaptureSession.m:9334"
- "LastShownBuild:FigCaptureSession.m:9345"
- "LastShownBuild:FigCaptureSession.m:9348"
- "LastShownBuild:FigCaptureSession.m:9356"
- "LastShownBuild:FigCaptureSession.m:9374"
- "LastShownBuild:FigCaptureSession.m:9419"
- "LastShownBuild:FigCaptureSession.m:9423"
- "LastShownBuild:FigCaptureSession.m:9447"
- "LastShownBuild:FigCaptureSession.m:9462"
- "LastShownBuild:FigCaptureSession.m:9466"
- "LastShownBuild:FigCaptureSession.m:9469"
- "LastShownBuild:FigCaptureSession.m:9593"
- "LastShownBuild:FigCaptureSession.m:9599"
- "LastShownBuild:FigCaptureSession.m:9625"
- "LastShownBuild:FigCaptureSession.m:9637"
- "LastShownBuild:FigCaptureSessionStateManager.m:351"
- "LastShownBuild:FigCaptureSessionStateManager.m:378"
- "LastShownBuild:FigCaptureSessionStateManager.m:515"
- "LastShownDate:BWFigCaptureDeviceVendor.m:1577"
- "LastShownDate:BWFigCaptureDeviceVendor.m:3031"
- "LastShownDate:BWFigCaptureDeviceVendor.m:3668"
- "LastShownDate:BWFigCaptureDeviceVendor.m:3681"
- "LastShownDate:BWFigVideoCaptureDevice.m:10158"
- "LastShownDate:BWFigVideoCaptureDevice.m:10651"
- "LastShownDate:BWFigVideoCaptureDevice.m:11235"
- "LastShownDate:BWFigVideoCaptureDevice.m:11686"
- "LastShownDate:BWFigVideoCaptureDevice.m:11721"
- "LastShownDate:BWFigVideoCaptureDevice.m:11910"
- "LastShownDate:BWFigVideoCaptureDevice.m:11919"
- "LastShownDate:BWFigVideoCaptureDevice.m:11931"
- "LastShownDate:BWFigVideoCaptureDevice.m:11938"
- "LastShownDate:BWFigVideoCaptureDevice.m:11972"
- "LastShownDate:BWFigVideoCaptureDevice.m:12038"
- "LastShownDate:BWFigVideoCaptureDevice.m:12207"
- "LastShownDate:BWFigVideoCaptureDevice.m:13103"
- "LastShownDate:BWFigVideoCaptureDevice.m:13201"
- "LastShownDate:BWFigVideoCaptureDevice.m:16366"
- "LastShownDate:BWFigVideoCaptureDevice.m:19231"
- "LastShownDate:BWFigVideoCaptureDevice.m:19619"
- "LastShownDate:BWFigVideoCaptureDevice.m:20502"
- "LastShownDate:BWFigVideoCaptureDevice.m:20926"
- "LastShownDate:BWFigVideoCaptureDevice.m:20928"
- "LastShownDate:BWFigVideoCaptureDevice.m:20930"
- "LastShownDate:BWFigVideoCaptureDevice.m:22831"
- "LastShownDate:BWFigVideoCaptureDevice.m:24231"
- "LastShownDate:BWFigVideoCaptureDevice.m:24263"
- "LastShownDate:BWFigVideoCaptureDevice.m:24419"
- "LastShownDate:BWFigVideoCaptureDevice.m:25173"
- "LastShownDate:BWFigVideoCaptureDevice.m:25198"
- "LastShownDate:BWFigVideoCaptureDevice.m:25447"
- "LastShownDate:BWFigVideoCaptureDevice.m:25804"
- "LastShownDate:BWFigVideoCaptureDevice.m:6245"
- "LastShownDate:BWFigVideoCaptureDevice.m:7942"
- "LastShownDate:BWFigVideoCaptureDevice.m:7951"
- "LastShownDate:BWFigVideoCaptureDevice.m:9034"
- "LastShownDate:BWFigVideoCaptureDevice.m:9035"
- "LastShownDate:BWFigVideoCaptureDevice.m:9054"
- "LastShownDate:BWFigVideoCaptureDevice.m:9069"
- "LastShownDate:BWFigVideoCaptureDevice.m:9344"
- "LastShownDate:BWFigVideoCaptureStream.m:3950"
- "LastShownDate:BWFigVideoCaptureStream.m:4370"
- "LastShownDate:BWGraph.m:2684"
- "LastShownDate:BWGraph.m:3594"
- "LastShownDate:BWGraph.m:3597"
- "LastShownDate:BWGraph.m:3610"
- "LastShownDate:BWGraph.m:3613"
- "LastShownDate:BWGraph.m:3616"
- "LastShownDate:BWHVSScoringNode.m:3508"
- "LastShownDate:BWMultiStreamCameraSourceNode.m:13942"
- "LastShownDate:BWMultiStreamCameraSourceNode.m:13958"
- "LastShownDate:BWPreviewStitcherNode.m:3432"
- "LastShownDate:FigCaptureMetadataUtilities.m:1546"
- "LastShownDate:FigCaptureMetadataUtilities.m:6327"
- "LastShownDate:FigCaptureSession.m:1018"
- "LastShownDate:FigCaptureSession.m:11420"
- "LastShownDate:FigCaptureSession.m:11615"
- "LastShownDate:FigCaptureSession.m:19505"
- "LastShownDate:FigCaptureSession.m:21070"
- "LastShownDate:FigCaptureSession.m:21073"
- "LastShownDate:FigCaptureSession.m:26450"
- "LastShownDate:FigCaptureSession.m:26463"
- "LastShownDate:FigCaptureSession.m:29546"
- "LastShownDate:FigCaptureSession.m:5225"
- "LastShownDate:FigCaptureSession.m:9319"
- "LastShownDate:FigCaptureSession.m:9325"
- "LastShownDate:FigCaptureSession.m:9328"
- "LastShownDate:FigCaptureSession.m:9331"
- "LastShownDate:FigCaptureSession.m:9334"
- "LastShownDate:FigCaptureSession.m:9345"
- "LastShownDate:FigCaptureSession.m:9348"
- "LastShownDate:FigCaptureSession.m:9356"
- "LastShownDate:FigCaptureSession.m:9374"
- "LastShownDate:FigCaptureSession.m:9419"
- "LastShownDate:FigCaptureSession.m:9423"
- "LastShownDate:FigCaptureSession.m:9447"
- "LastShownDate:FigCaptureSession.m:9462"
- "LastShownDate:FigCaptureSession.m:9466"
- "LastShownDate:FigCaptureSession.m:9469"
- "LastShownDate:FigCaptureSession.m:9593"
- "LastShownDate:FigCaptureSession.m:9599"
- "LastShownDate:FigCaptureSession.m:9625"
- "LastShownDate:FigCaptureSession.m:9637"
- "LastShownDate:FigCaptureSessionStateManager.m:351"
- "LastShownDate:FigCaptureSessionStateManager.m:378"
- "LastShownDate:FigCaptureSessionStateManager.m:515"
- "Oct 29 2026"
- "description=CameraCapture-764.60.7.0.2"
```
