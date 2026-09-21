## ISP.mediacapture

> `/System/Library/MediaCapture/ISP.mediacapture`

```diff

-20.104.2.0.0
-  __TEXT.__text: 0x1af038
+20.105.2.0.0
+  __TEXT.__text: 0x1af01c
   __TEXT.__init_offsets: 0xc
   __TEXT.__gcc_except_tab: 0x4aac
-  __TEXT.__const: 0x27a75
+  __TEXT.__const: 0x27ae5
   __TEXT.__oslogstring: 0x1c94b
-  __TEXT.__cstring: 0x16aa8
+  __TEXT.__cstring: 0x16a52
   __TEXT.__unwind_info: 0x5708
   __TEXT.__eh_frame: 0x50
   __TEXT.__objc_stubs: 0x0

   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x1f68
-  __AUTH_CONST.__cfstring: 0x83c0
+  __AUTH_CONST.__cfstring: 0x8300
   __AUTH_CONST.__weak_auth_got: 0xb0
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x1350

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
   Functions: 5136
-  Symbols:   7258
-  CStrings:  5939
+  Symbols:   7264
+  CStrings:  5933
 
Symbols:
+ _kFigCaptureStreamMetadata_SmartTapAlgorithmMetadata
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_FocusBias
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_MaskConfidence
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_ObjectID
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_TotalPoints
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_ValidCoverage
Functions:
~ __ZN3ISP23PCEFrontEtrogPresetListC2Ev : 180 -> 228
~ __ZL20StillImageCaptureNowPKvP16ISPCaptureStreamP15ISPCaptureGroupP16ISPCaptureDevice : 22152 -> 22176
~ __ZL22SetVideoOutputsEnabledPKvP16ISPCaptureStreamP15ISPCaptureGroupP16ISPCaptureDevice : 4984 -> 4960
~ __ZL33CopySupportedOutputConfigurationsPK13__CFAllocatorPvP16ISPCaptureStreamP15ISPCaptureGroupP16ISPCaptureDevice : 1024 -> 1052
~ __ZN3ISP35InitSupportedMetadataPropertiesDictERP14__CFDictionary : 52776 -> 52780
~ __ZN3ISP44GenerateAndAttachCoreMediaMetaDataDictionaryEP14__CFDictionaryP10__CVBufferPNSt3__15dequeIS3_NS4_9allocatorIS3_EEEEPNS_24ISPMetaDataOptionsStructEPNS_9ISPDeviceEdP19ISPCameraTimeStructPNS_26ISPOscarTimeSyncInfoStructE : 165504 -> 165396
CStrings:
- "FocusBias"
- "MaskConfidence"
- "ObjectID"
- "SmartTapAlgorithmMetadata"
- "TotalPoints"
- "ValidCoverage"
```
