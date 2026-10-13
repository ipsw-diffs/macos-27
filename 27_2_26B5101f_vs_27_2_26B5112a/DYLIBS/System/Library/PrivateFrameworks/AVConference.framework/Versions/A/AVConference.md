## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/Versions/A/AVConference`

```diff

-2260.14.1.0.0
-  __TEXT.__text: 0x7c0aac
+2260.15.1.0.0
+  __TEXT.__text: 0x7c3f34
   __TEXT.__realtime: 0xea4
-  __TEXT.__objc_methlist: 0x39f48
+  __TEXT.__objc_methlist: 0x3a090
   __TEXT.__const: 0x184a8
-  __TEXT.__cstring: 0x9b706
-  __TEXT.__oslogstring: 0x142c64
+  __TEXT.__cstring: 0x9bd3c
+  __TEXT.__oslogstring: 0x143df1
   __TEXT.__gcc_except_tab: 0x326c
   __TEXT.__ustring: 0x2d4
   __TEXT.__dlopen_cstrs: 0x56
-  __TEXT.__unwind_info: 0x1b508
+  __TEXT.__unwind_info: 0x1b598
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x508
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x185a0
+  __DATA_CONST.__objc_selrefs: 0x18630
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x1240
   __DATA_CONST.__objc_arraydata: 0x2790
-  __DATA_CONST.__got: 0x1b00
+  __DATA_CONST.__got: 0x1b08
   __AUTH_CONST.__const: 0x8a08
-  __AUTH_CONST.__cfstring: 0x29260
-  __AUTH_CONST.__objc_const: 0x6c7d8
+  __AUTH_CONST.__cfstring: 0x292a0
+  __AUTH_CONST.__objc_const: 0x6c908
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x4e00
   __AUTH_CONST.__objc_arrayobj: 0x1d58

   __AUTH_CONST.__auth_got: 0x2ba8
   __AUTH.__objc_data: 0x140
   __AUTH.__data: 0x8
-  __DATA.__objc_ivar: 0x76c0
+  __DATA.__objc_ivar: 0x76e0
   __DATA.__data: 0x1e20
   __DATA.__bss: 0xad8
   __DATA.__common: 0x9

   - /usr/lib/libspindump.dylib
   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 35346
-  Symbols:   54550
-  CStrings:  33391
+  Functions: 35384
+  Symbols:   54614
+  CStrings:  33447
 
Symbols:
+ +[VCAVFoundationCapture isZoomSupportedForCaptureDevice:captureSource:]
+ +[VCHardwareSettings supportsClientPreviewPresentationOrientation]
+ -[AVCPreviewCameraSession setPreviewPresentationOrientation:]
+ -[AVConferencePreview setPreviewPresentationOrientation:]
+ -[VCAVFoundationCapture clearPreviewPresentationOrientation]
+ -[VCAVFoundationCapture clearRemotePresentationOrientation]
+ -[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:hasVideoPresentationOrientation:previewPresentationOrientation:hasPreviewPresentationOrientation:]
+ -[VCAVFoundationCapture isClientPreviewPresentationOrientationGoverning]
+ -[VCAVFoundationCapture setPreviewPresentationOrientation:]
+ -[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:captureSource:]
+ -[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:]
+ -[VCAVFoundationCapture vendableAspectRatio:landscapeOrderedAlternate:captureFormat:clientPreviewGoverns:]
+ -[VCMediaRecorder hasConfiguredWriter]
+ -[VCMediaRecorderLocal localRecordingScreenAttributesDidChange:]
+ -[VCMediaRecorderLocal updateTargetScreenAttributesFromCaptureServer]
+ -[VCRemoteVideoState participantId]
+ -[VCRemoteVideoState setParticipantId:]
+ -[VCSession clearRemotePresentationOrientationOnCaptureServer]
+ -[VCVideoCaptureServer applyClientPreviewPresentationOrientationArguments:]
+ -[VCVideoCaptureServer clearPreviewPresentationOrientationRequestForDiedClient:]
+ -[VCVideoCaptureServer clearRemotePresentationOrientation]
+ -[VCVideoCaptureServer copyLocalRecordingScreenAttributesForVideoAttributes:]
+ -[VCVideoCaptureServer dispatchedClearPreviewPresentationOrientationRequest]
+ -[VCVideoCaptureServer dispatchedCopyLocalRecordingScreenAttributesForVideoAttributes:]
+ -[VCVideoCaptureServer dispatchedIsClientPreviewPresentationOrientationGoverning]
+ -[VCVideoCaptureServer handleClientPreviewPresentationOrientationMessage:]
+ -[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]
+ -[VCVideoCaptureServer setPreviewPresentationOrientation:]
+ -[VCVideoCaptureServer setPreviewPresentationOrientation:requestingClientPID:]
+ GCC_except_table142
+ GCC_except_table146
+ GCC_except_table148
+ GCC_except_table178
+ GCC_except_table185
+ GCC_except_table219
+ GCC_except_table231
+ GCC_except_table233
+ GCC_except_table235
+ GCC_except_table253
+ GCC_except_table287
+ GCC_except_table290
+ GCC_except_table293
+ GCC_except_table336
+ OBJC_IVAR_$_AVConferencePreview._preRegistrationCameraUIDToSession
+ OBJC_IVAR_$_AVConferencePreview._setPrimarySecondaryInFlightCount
+ OBJC_IVAR_$_VCAVFoundationCapture._hasPreviewPresentationOrientation
+ OBJC_IVAR_$_VCAVFoundationCapture._hasVideoPresentationOrientation
+ OBJC_IVAR_$_VCAVFoundationCapture._previewPresentationOrientation
+ OBJC_IVAR_$_VCRemoteVideoState._participantId
+ OBJC_IVAR_$_VCVideoCaptureServer._hasPreviewPresentationOrientationRequest
+ OBJC_IVAR_$_VCVideoCaptureServer._hasRemotePresentationOrientation
+ OBJC_IVAR_$_VCVideoCaptureServer._previewPresentationOrientationRequest
+ OBJC_IVAR_$_VCVideoCaptureServer._previewPresentationOrientationRequestPID
+ OBJC_IVAR_$_VCVideoCaptureServer._remotePresentationOrientation
+ VCMediaRecorderHistory_HasConfiguredWriter
+ _AVErrorDeviceKey
+ _VCMediaRecorderHistory_HasConfiguredWriter
+ _VCVideoCaptureServer_ClientPIDFromArguments
+ __47-[VCVideoCaptureServer registerBlocksForServer]_block_invoke_6
+ ___57-[AVConferencePreview setPreviewPresentationOrientation:]_block_invoke
+ ___58-[VCVideoCaptureServer clearRemotePresentationOrientation]_block_invoke
+ ___59-[VCAVFoundationCapture clearRemotePresentationOrientation]_block_invoke
+ ___59-[VCAVFoundationCapture setPreviewPresentationOrientation:]_block_invoke
+ ___60-[VCAVFoundationCapture clearPreviewPresentationOrientation]_block_invoke
+ ___61-[AVCPreviewCameraSession setPreviewPresentationOrientation:]_block_invoke
+ ___66+[VCHardwareSettings supportsClientPreviewPresentationOrientation]_block_invoke
+ ___76-[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]_block_invoke
+ ___77-[VCVideoCaptureServer copyLocalRecordingScreenAttributesForVideoAttributes:]_block_invoke
+ ___78-[VCVideoCaptureServer setPreviewPresentationOrientation:requestingClientPID:]_block_invoke
+ ___80-[VCVideoCaptureServer clearPreviewPresentationOrientationRequestForDiedClient:]_block_invoke
+ ___VCMediaRecorderHistory_HasConfiguredWriter_block_invoke
+ _objc_msgSend$applyClientPreviewPresentationOrientationArguments:
+ _objc_msgSend$clearPreviewPresentationOrientation
+ _objc_msgSend$clearPreviewPresentationOrientationRequestForDiedClient:
+ _objc_msgSend$clearRemotePresentationOrientation
+ _objc_msgSend$clearRemotePresentationOrientationOnCaptureServer
+ _objc_msgSend$copyLocalRecordingScreenAttributesForVideoAttributes:
+ _objc_msgSend$dispatchedClearPreviewPresentationOrientationRequest
+ _objc_msgSend$dispatchedCopyLocalRecordingScreenAttributesForVideoAttributes:
+ _objc_msgSend$dispatchedIsClientPreviewPresentationOrientationGoverning
+ _objc_msgSend$handleClientPreviewPresentationOrientationMessage:
+ _objc_msgSend$hasConfiguredWriter
+ _objc_msgSend$initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:hasVideoPresentationOrientation:previewPresentationOrientation:hasPreviewPresentationOrientation:
+ _objc_msgSend$isClientPreviewPresentationOrientationGoverning
+ _objc_msgSend$isZoomSupportedForCaptureDevice:captureSource:
+ _objc_msgSend$localRecordingScreenAttributesDidChange:
+ _objc_msgSend$notifyClientsLocalRecordingScreenAttributesDidChange
+ _objc_msgSend$setDictionary:
+ _objc_msgSend$setPreviewPresentationOrientation:
+ _objc_msgSend$setPreviewPresentationOrientation:requestingClientPID:
+ _objc_msgSend$supportsClientPreviewPresentationOrientation
+ _objc_msgSend$updateCameraZoomCapabilityForCaptureDeviceInput:captureSource:
+ _objc_msgSend$updateDeviceOrientationMatchesReceiver:
+ _objc_msgSend$updateTargetScreenAttributesFromCaptureServer
+ _objc_msgSend$vendableAspectRatio:landscapeOrderedAlternate:captureFormat:clientPreviewGoverns:
+ supportsClientPreviewPresentationOrientation.onceToken
+ supportsClientPreviewPresentationOrientation.resolved
- +[VCHardwareSettings supportsSquarePreviewCapture]
- -[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:]
- -[VCAVFoundationCapture squarePreviewAdjustedRequestSizeForCaptureSize:]
- -[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:]
- -[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:videoPresentationOrientation:]
- -[VCVideoCaptureServer copyLocalScreenAttributesForVideoAttributes:]
- GCC_except_table121
- GCC_except_table136
- GCC_except_table145
- GCC_except_table147
- GCC_except_table149
- GCC_except_table176
- GCC_except_table184
- GCC_except_table216
- GCC_except_table218
- GCC_except_table220
- GCC_except_table238
- GCC_except_table263
- GCC_except_table272
- GCC_except_table275
- GCC_except_table319
- OBJC_IVAR_$_VCAVFoundationCapture._clientRequestedSize
- OBJC_IVAR_$_VCAVFoundationCapture._configuringForCapture
- OBJC_IVAR_$_VCAVFoundationCapture._squarePreviewOverrideActive
- ___50+[VCHardwareSettings supportsSquarePreviewCapture]_block_invoke
- _objc_msgSend$copyLocalScreenAttributesForVideoAttributes:
- _objc_msgSend$initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:
- _objc_msgSend$squarePreviewAdjustedRequestSizeForCaptureSize:
- _objc_msgSend$supportsSquarePreviewCapture
- _objc_msgSend$updateCameraZoomCapabilityForCaptureDeviceInput:
- _objc_msgSend$updateDeviceOrientationMatchesReceiver:videoPresentationOrientation:
- supportsSquarePreviewCapture.onceToken
- supportsSquarePreviewCapture.resolved
CStrings:
+ " [%s] %s:%d %@(%p) Skipping, a writer is already composed for"
+ " [%s] %s:%d %@(%p) [FTDC] Primary connections video=%d metadata=%d"
+ " [%s] %s:%d %@(%p) width=%d, height=%d, frameRate=%d, sourceToken=0x%x, cinematicFramingEnabled=%d, orientation=%d, zoomFactor=%f, remoteSupportsFullScreenReceive=%d, videoPresentationOrientation=%d, hasVideoPresentationOrientation=%d, previewPresentationOrientation=%d, hasPreviewPresentationOrientation=%d"
+ " [%s] %s:%d Skipping, a writer is already composed for"
+ " [%s] %s:%d VCDTMFToneGenerator[%p] Initialize event=%d, powerLevel=%d, sampleRate=%d, tableAmplitude=%d, amplitude=%d"
+ " [%s] %s:%d VCHardwareSettings: clientPreviewPresentationOrientation support overridden by user default: outOfBox=%d override=%d"
+ " [%s] %s:%d [AR_TX] captureAspectRatio=%@, composeLandscapeOrderedRatio=%d, clientPreviewGoverns=%d, _videoPresentationOrientation=%d, _hasVideoPresentationOrientation=%d, _previewPresentationOrientation=%d, _hasPreviewPresentationOrientation=%d, _orientation=%d, _deviceOrientationMatchesReceiver=%d, _remotePreferFullBleed=%d, overrideByDefault=%d"
+ " [%s] %s:%d [AR_TX] client preview presentation orientation not honored, the active format cannot vend it. aspectRatio=%@, _previewPresentationOrientation=%d, _orientation=%d"
+ " [%s] %s:%d [AR_TX]_videoPresentationOrientation=%d, _hasVideoPresentationOrientation=%d, orientation=%d, _deviceOrientationMatchesReceiver=%d"
+ " [%s] %s:%d [FTDC] Primary connections video=%d metadata=%d"
+ " [%s] %s:%d _previewPresentationOrientation=%d, _hasPreviewPresentationOrientation=%d, _isPreviewing=%d, _isCapturing=%d"
+ " [%s] %s:%d _previewPresentationOrientation=%d, didChange=%d, _orientation=%d, _videoPresentationOrientation=%d, _hasVideoPresentationOrientation=%d, _isPreviewing=%d, _isCapturing=%d"
+ " [%s] %s:%d wasClientGoverning=%d, _orientation=%d, _isPreviewing=%d, _isCapturing=%d"
+ " [%s] %s:%d width=%d, height=%d, frameRate=%d, sourceToken=0x%x, cinematicFramingEnabled=%d, orientation=%d, zoomFactor=%f, remoteSupportsFullScreenReceive=%d, videoPresentationOrientation=%d, hasVideoPresentationOrientation=%d, previewPresentationOrientation=%d, hasPreviewPresentationOrientation=%d"
+ "+[VCHardwareSettings supportsClientPreviewPresentationOrientation]_block_invoke"
+ "-[AVCPreviewCameraSession setPreviewPresentationOrientation:]_block_invoke"
+ "-[AVConferencePreview setPreviewPresentationOrientation:]"
+ "-[VCAVFoundationCapture clearPreviewPresentationOrientation]_block_invoke"
+ "-[VCAVFoundationCapture clearRemotePresentationOrientation]_block_invoke"
+ "-[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:hasVideoPresentationOrientation:previewPresentationOrientation:hasPreviewPresentationOrientation:]"
+ "-[VCAVFoundationCapture setPreviewPresentationOrientation:]_block_invoke"
+ "-[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:captureSource:]"
+ "-[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:]"
+ "-[VCAVFoundationCapture vendableAspectRatio:landscapeOrderedAlternate:captureFormat:clientPreviewGoverns:]"
+ "-[VCMediaRecorderLocal localRecordingScreenAttributesDidChange:]"
+ "-[VCMediaRecorderLocal updateTargetScreenAttributesFromCaptureServer]"
+ "-[VCVideoCaptureServer applyClientPreviewPresentationOrientationArguments:]"
+ "-[VCVideoCaptureServer clearPreviewPresentationOrientationRequestForDiedClient:]_block_invoke"
+ "-[VCVideoCaptureServer clearRemotePresentationOrientation]"
+ "-[VCVideoCaptureServer clearRemotePresentationOrientation]_block_invoke"
+ "-[VCVideoCaptureServer dispatchedClearPreviewPresentationOrientationRequest]"
+ "-[VCVideoCaptureServer dispatchedCopyLocalRecordingScreenAttributesForVideoAttributes:]"
+ "-[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]"
+ "-[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]_block_invoke"
+ "-[VCVideoCaptureServer registerBlocksForServer]_block_invoke_6"
+ "-[VCVideoCaptureServer setPreviewPresentationOrientation:requestingClientPID:]"
+ "2260.15.1"
+ "AVCPreviewCameraSession [%s] %s:%d %@(%p) cameraUID=%@ orientation=%d"
+ "AVCPreviewCameraSession [%s] %s:%d cameraUID=%@ orientation=%d"
+ "AVConferencePreview [%s] %s:%d %@(%p) orientation=%d"
+ "AVConferencePreview [%s] %s:%d orientation=%d"
+ "VCMediaRecorderHistory_HasConfiguredWriter"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Discarding client preview presentation orientation request, unsupported by the hardware rule. previewPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Invalid previewPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Missing or non-numeric previewPresentationOrientation, class=%@"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) No local video attributes to derive recording screen attributes from"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Notifying client=%p of class=%@"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Retaining the remote presentation orientation at call end, unsupported by the hardware rule."
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Retaining the request, the dying client did not make it. diedClientPID=%d, _previewPresentationOrientationRequestPID=%d, _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) [AR_RX] videoOrientation=%d, screenOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d, _previewPresentationOrientationRequestPID=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) _remotePresentationOrientation=%d, _hasRemotePresentationOrientation=%d, _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) previewPresentationOrientation=%d, requestingClientPID=%d"
+ "VCVideoCaptureServer [%s] %s:%d Discarding client preview presentation orientation request, unsupported by the hardware rule. previewPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d Invalid previewPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d Missing or non-numeric previewPresentationOrientation, class=%@"
+ "VCVideoCaptureServer [%s] %s:%d No local video attributes to derive recording screen attributes from"
+ "VCVideoCaptureServer [%s] %s:%d Notifying client=%p of class=%@"
+ "VCVideoCaptureServer [%s] %s:%d Retaining the remote presentation orientation at call end, unsupported by the hardware rule."
+ "VCVideoCaptureServer [%s] %s:%d Retaining the request, the dying client did not make it. diedClientPID=%d, _previewPresentationOrientationRequestPID=%d, _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d"
+ "VCVideoCaptureServer [%s] %s:%d [AR_RX] videoOrientation=%d, screenOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d, _previewPresentationOrientationRequestPID=%d"
+ "VCVideoCaptureServer [%s] %s:%d _remotePresentationOrientation=%d, _hasRemotePresentationOrientation=%d, _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d"
+ "VCVideoCaptureServer [%s] %s:%d ignoring stale capture failure, failingCameraUID=%@, currentCameraUID=%@"
+ "VCVideoCaptureServer [%s] %s:%d previewPresentationOrientation=%d, requestingClientPID=%d"
+ "forceClientPreviewPresentationOrientation"
+ "previewPresentationOrientation"
+ "previewSetPresentationOrientation"
+ "secondary camera UID must differ from the primary camera UID"
- " [%s] %s:%d %@(%p) width=%d, height=%d, frameRate=%d, sourceToken=0x%x, cinematicFramingEnabled=%d, orientation=%d, zoomFactor=%f, remoteSupportsFullScreenReceive=%d, videoPresentationOrientation=%d"
- " [%s] %s:%d VCDTMFToneGenerator[%p] Initialize event=%d, powerLevel=%d, sampleRate=%d"
- " [%s] %s:%d VCHardwareSettings: squarePreviewCapture support overridden by user default: outOfBox=%d override=%d"
- " [%s] %s:%d [AR_TX] _deviceOrientationMatchesReceiver=%d, _remotePreferFullBleed=%d, previewOnly=%d, prefersSquarePreview=%d, captureAspectRatio=%@, overrideByDefault=%d"
- " [%s] %s:%d [AR_TX]videoPresentationOrientation=%d, orientation=%d, _deviceOrientationMatchesReceiver=%d"
- " [%s] %s:%d width=%d, height=%d, frameRate=%d, sourceToken=0x%x, cinematicFramingEnabled=%d, orientation=%d, zoomFactor=%f, remoteSupportsFullScreenReceive=%d, videoPresentationOrientation=%d"
- "+[VCHardwareSettings supportsSquarePreviewCapture]_block_invoke"
- "-[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:]"
- "-[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:]"
- "-[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:videoPresentationOrientation:]"
- "-[VCVideoCaptureServer registerBlocksForServer]_block_invoke_5"
- "2260.14.1"
- "forceSquarePreviewCapture"
```
