## AVFCapture

> `/System/Library/PrivateFrameworks/AVFCapture.framework/Versions/A/AVFCapture`

```diff

-764.40.7.0.0
-  __TEXT.__text: 0x1ac0b0
-  __TEXT.__objc_methlist: 0x180d4
-  __TEXT.__cstring: 0x395e9
+764.41.11.0.0
+  __TEXT.__text: 0x1ad448
+  __TEXT.__objc_methlist: 0x182fc
+  __TEXT.__cstring: 0x39829
   __TEXT.__const: 0x1602
   __TEXT.__gcc_except_tab: 0x3748
-  __TEXT.__oslogstring: 0xfd90
+  __TEXT.__oslogstring: 0xfe20
   __TEXT.__dlopen_cstrs: 0x275
   __TEXT.__ustring: 0x112
   __TEXT.__swift5_typeref: 0xef

   __TEXT.__swift5_reflstr: 0x24
   __TEXT.__swift5_fieldmd: 0x50
   __TEXT.__swift5_types: 0x8
-  __TEXT.__unwind_info: 0x91b8
+  __TEXT.__unwind_info: 0x9238
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1870
-  __DATA_CONST.__objc_classlist: 0x9d8
+  __DATA_CONST.__const: 0x1880
+  __DATA_CONST.__objc_classlist: 0x9e8
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0xd8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9ff8
+  __DATA_CONST.__objc_selrefs: 0xa0b0
   __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__objc_superrefs: 0x828
+  __DATA_CONST.__objc_superrefs: 0x838
   __DATA_CONST.__objc_arraydata: 0x2c0
-  __DATA_CONST.__got: 0x2fd0
+  __DATA_CONST.__got: 0x3020
   __AUTH_CONST.__const: 0x3360
-  __AUTH_CONST.__cfstring: 0x174c0
-  __AUTH_CONST.__objc_const: 0x26838
+  __AUTH_CONST.__cfstring: 0x175e0
+  __AUTH_CONST.__objc_const: 0x26b48
   __AUTH_CONST.__objc_intobj: 0xab0
   __AUTH_CONST.__objc_arrayobj: 0x2b8
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_floatobj: 0x20
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__auth_got: 0x1570
-  __AUTH.__objc_data: 0x27a8
-  __DATA.__objc_ivar: 0x27a0
+  __AUTH.__objc_data: 0x2848
+  __DATA.__objc_ivar: 0x27c8
   __DATA.__data: 0x1068
   __DATA.__bss: 0xa20
   __DATA.__common: 0x200

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11366
-  Symbols:   22404
-  CStrings:  5060
+  Functions: 11409
+  Symbols:   22506
+  CStrings:  5071
 
Symbols:
+ +[AVMetadataDeviceProximityDetectionObject deviceProximityDetectionWithDeviceDictionary:input:time:]
+ +[AVMetadataLightSourceEstimationObject lightSourceEstimationWithDictionary:input:time:]
+ -[AVCaptureDevice supportedMetadataIdentifiersForPerceptionThumbnailChannel]
+ -[AVCaptureFigVideoDevice supportedMetadataIdentifiersForPerceptionThumbnailChannel]
+ -[AVCaptureMetadataOutput _metadataIdentifiersForPerceptionThumbnailChannel]
+ -[AVCaptureMetadataOutput deviceProximityDetectionDeviceTypes]
+ -[AVCaptureMetadataOutput deviceProximityDetectionTargetFrameRate]
+ -[AVCaptureMetadataOutput lightSourceEstimationAmbientLuminance]
+ -[AVCaptureMetadataOutput lightSourceEstimationTargetFrameRate]
+ -[AVCaptureMetadataOutput metadataObjectTypesForPerceptionThumbnailChannel]
+ -[AVCaptureMetadataOutput perceptionTestModeEnabled]
+ -[AVCaptureMetadataOutput setDeviceProximityDetectionDeviceTypes:]
+ -[AVCaptureMetadataOutput setLightSourceEstimationAmbientLuminance:]
+ -[AVCaptureMetadataOutput setMetadataObjectTypesForPerceptionThumbnailChannel:]
+ -[AVCaptureMetadataOutput setPerceptionTestModeEnabled:]
+ -[AVCaptureMetadataOutput supportedMetadataObjectTypesForPerceptionThumbnailChannel]
+ -[AVCaptureMetadataOutput_Tundra _metadataIdentifiersForPerceptionThumbnailChannel]
+ -[AVCaptureMetadataOutput_Tundra deviceProximityDetectionDeviceTypes]
+ -[AVCaptureMetadataOutput_Tundra lightSourceEstimationAmbientLuminance]
+ -[AVCaptureMetadataOutput_Tundra metadataObjectTypesForPerceptionThumbnailChannel]
+ -[AVCaptureMetadataOutput_Tundra perceptionTestModeEnabled]
+ -[AVCaptureMetadataOutput_Tundra setDeviceProximityDetectionDeviceTypes:]
+ -[AVCaptureMetadataOutput_Tundra setLightSourceEstimationAmbientLuminance:]
+ -[AVCaptureMetadataOutput_Tundra setMetadataObjectTypesForPerceptionThumbnailChannel:]
+ -[AVCaptureMetadataOutput_Tundra setPerceptionTestModeEnabled:]
+ -[AVCaptureMetadataOutput_Tundra supportedMetadataObjectTypesForPerceptionThumbnailChannel]
+ -[AVMetadataDeviceProximityDetectionObject confidence]
+ -[AVMetadataDeviceProximityDetectionObject copyWithZone:]
+ -[AVMetadataDeviceProximityDetectionObject description]
+ -[AVMetadataDeviceProximityDetectionObject deviceID]
+ -[AVMetadataDeviceProximityDetectionObject deviceType]
+ -[AVMetadataDeviceProximityDetectionObject initDerivedMetadataObjectFromMetadataObject:withTransform:isVideoMirrored:rollAdjustment:]
+ -[AVMetadataDeviceProximityDetectionObject initWithDeviceDictionary:sourceCaptureInput:time:]
+ -[AVMetadataDeviceProximityDetectionObject pose]
+ -[AVMetadataLightSourceEstimationObject copyWithZone:]
+ -[AVMetadataLightSourceEstimationObject dealloc]
+ -[AVMetadataLightSourceEstimationObject description]
+ -[AVMetadataLightSourceEstimationObject initDerivedMetadataObjectFromMetadataObject:withTransform:isVideoMirrored:rollAdjustment:]
+ -[AVMetadataLightSourceEstimationObject initWithLightSourceEstimationDictionary:sourceCaptureInput:time:]
+ -[AVMetadataLightSourceEstimationObject payload]
+ -[AVMetadataObject sentToPerceptionThumbnailChannel]
+ -[AVMetadataObjectInternal sentToPerceptionThumbnailChannel]
+ -[AVMetadataObjectInternal setSentToPerceptionThumbnailChannel:]
+ GCC_except_table1030
+ GCC_except_table1038
+ GCC_except_table1048
+ GCC_except_table161
+ GCC_except_table162
+ GCC_except_table177
+ GCC_except_table183
+ GCC_except_table375
+ GCC_except_table826
+ GCC_except_table828
+ GCC_except_table830
+ GCC_except_table861
+ GCC_except_table873
+ GCC_except_table875
+ GCC_except_table877
+ GCC_except_table883
+ GCC_except_table887
+ GCC_except_table930
+ GCC_except_table939
+ OBJC_IVAR_$_AVCaptureMetadataOutputInternal.deviceProximityDetectionDeviceTypes
+ OBJC_IVAR_$_AVCaptureMetadataOutputInternal.lightSourceEstimationAmbientLuminance
+ OBJC_IVAR_$_AVCaptureMetadataOutputInternal.metadataObjectTypesForPerceptionThumbnailChannel
+ OBJC_IVAR_$_AVCaptureMetadataOutputInternal.perceptionTestModeEnabled
+ OBJC_IVAR_$_AVMetadataDeviceProximityDetectionObject._confidence
+ OBJC_IVAR_$_AVMetadataDeviceProximityDetectionObject._deviceID
+ OBJC_IVAR_$_AVMetadataDeviceProximityDetectionObject._deviceType
+ OBJC_IVAR_$_AVMetadataDeviceProximityDetectionObject._pose
+ OBJC_IVAR_$_AVMetadataLightSourceEstimationObject._payload
+ OBJC_IVAR_$_AVMetadataObjectInternal._sentToPerceptionThumbnailChannel
+ _AVMetadataObjectTypeDeviceProximityDetection
+ _AVMetadataObjectTypeLightSourceEstimation
+ _OBJC_CLASS_$_AVMetadataDeviceProximityDetectionObject
+ _OBJC_CLASS_$_AVMetadataLightSourceEstimationObject
+ _OBJC_METACLASS_$_AVMetadataDeviceProximityDetectionObject
+ _OBJC_METACLASS_$_AVMetadataLightSourceEstimationObject
+ __OBJC_$_CLASS_METHODS_AVMetadataDeviceProximityDetectionObject
+ __OBJC_$_CLASS_METHODS_AVMetadataLightSourceEstimationObject
+ __OBJC_$_INSTANCE_METHODS_AVMetadataDeviceProximityDetectionObject
+ __OBJC_$_INSTANCE_METHODS_AVMetadataLightSourceEstimationObject
+ __OBJC_$_INSTANCE_VARIABLES_AVMetadataDeviceProximityDetectionObject
+ __OBJC_$_INSTANCE_VARIABLES_AVMetadataLightSourceEstimationObject
+ __OBJC_$_PROP_LIST_AVMetadataDeviceProximityDetectionObject
+ __OBJC_$_PROP_LIST_AVMetadataLightSourceEstimationObject
+ __OBJC_CLASS_PROTOCOLS_$_AVMetadataDeviceProximityDetectionObject
+ __OBJC_CLASS_PROTOCOLS_$_AVMetadataLightSourceEstimationObject
+ __OBJC_CLASS_RO_$_AVMetadataDeviceProximityDetectionObject
+ __OBJC_CLASS_RO_$_AVMetadataLightSourceEstimationObject
+ __OBJC_METACLASS_RO_$_AVMetadataDeviceProximityDetectionObject
+ __OBJC_METACLASS_RO_$_AVMetadataLightSourceEstimationObject
+ _kFigCaptureSampleBufferAttachmentKey_DeviceProximityDetection
+ _kFigCaptureSampleBufferAttachmentKey_LightSourceEstimation
+ _kFigCaptureStreamDetectedObjectKey_SentToPerceptionThumbnailChannel
+ _kFigCaptureStreamSecureDetectedProximityDeviceKey_ConfidenceLevel
+ _kFigCaptureStreamSecureDetectedProximityDeviceKey_DeviceID
+ _kFigCaptureStreamSecureDetectedProximityDeviceKey_DeviceType
+ _kFigCaptureStreamSecureDetectedProximityDeviceKey_PoseMatrix
+ _kFigCaptureStreamSecureDetectedProximityDevicesKey_DevicesArray
+ _objc_msgSend$_metadataIdentifiersForPerceptionThumbnailChannel
+ _objc_msgSend$deviceProximityDetectionDeviceTypes
+ _objc_msgSend$deviceProximityDetectionTargetFrameRate
+ _objc_msgSend$deviceProximityDetectionWithDeviceDictionary:input:time:
+ _objc_msgSend$initWithDeviceDictionary:sourceCaptureInput:time:
+ _objc_msgSend$initWithLightSourceEstimationDictionary:sourceCaptureInput:time:
+ _objc_msgSend$lightSourceEstimationAmbientLuminance
+ _objc_msgSend$lightSourceEstimationTargetFrameRate
+ _objc_msgSend$lightSourceEstimationWithDictionary:input:time:
+ _objc_msgSend$perceptionTestModeEnabled
+ _objc_msgSend$pose
+ _objc_msgSend$sentToPerceptionThumbnailChannel
+ _objc_msgSend$setDeviceProximityDetectionDeviceTypes:
+ _objc_msgSend$setDeviceProximityDetectionTargetFrameRate:
+ _objc_msgSend$setLightSourceEstimationAmbientLuminance:
+ _objc_msgSend$setLightSourceEstimationTargetFrameRate:
+ _objc_msgSend$setMetadataIdentifiersForPerceptionThumbnailChannel:
+ _objc_msgSend$setPerceptionTestModeEnabled:
+ _objc_msgSend$setSentToPerceptionThumbnailChannel:
+ _objc_msgSend$supportedMetadataIdentifiersForPerceptionThumbnailChannel
+ _objc_msgSend$supportedMetadataObjectTypesForPerceptionThumbnailChannel
- GCC_except_table1029
- GCC_except_table1037
- GCC_except_table1047
- GCC_except_table150
- GCC_except_table160
- GCC_except_table165
- GCC_except_table167
- GCC_except_table356
- GCC_except_table825
- GCC_except_table827
- GCC_except_table829
- GCC_except_table860
- GCC_except_table872
- GCC_except_table874
- GCC_except_table876
- GCC_except_table882
- GCC_except_table886
- GCC_except_table929
- GCC_except_table938
CStrings:
+ "%@: %p deviceID: %d, confidence: %f, deviceType: %d"
+ ", sentToPerceptionThumbnailChannel=%d"
+ "<<<< AVCaptureMetadataOutput >>>> %s: Face ID Result <rawFrameId: %lu, metadataFrameId: %lu, refFrameId: %lu, frameType: %d, projectorMode: %d>"
+ "DeviceProximityDetection"
+ "LightSourceEstimation"
+ "Unsupported - check for AVMetadataDeviceProximityDetectionObject in -availableMetadataObjectTypes"
+ "Unsupported - check for AVMetadataLightSourceEstimationObject in -availableMetadataObjectTypes"
+ "Unsupported type found (%@) - use -supportedMetadataObjectTypesForPerceptionThumbnailChannel"
+ "avcmdo_faceIDCollectionForSampleBuffer"
+ "description=CameraCapture_AVF-764.41.11"
+ "mdta/com.apple.quicktime.device-proximity-detection"
+ "mdta/com.apple.quicktime.light-source-estimation"
- "description=CameraCapture_AVF-764.40.7"
```
