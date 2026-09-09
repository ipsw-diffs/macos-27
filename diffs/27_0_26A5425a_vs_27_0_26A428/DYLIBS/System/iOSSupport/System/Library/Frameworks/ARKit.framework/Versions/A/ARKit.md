## ARKit

> `/System/iOSSupport/System/Library/Frameworks/ARKit.framework/Versions/A/ARKit`

```diff

 781.0.5.0.3
-  __TEXT.__text: 0x3b55c
+  __TEXT.__text: 0x3b840
   __TEXT.__objc_methlist: 0x4454
   __TEXT.__const: 0x3690
   __TEXT.__cstring: 0x54ae
   __TEXT.__gcc_except_tab: 0x1de8
-  __TEXT.__oslogstring: 0x46d9
+  __TEXT.__oslogstring: 0x472b
   __TEXT.__ustring: 0xde
-  __TEXT.__unwind_info: 0x1248
+  __TEXT.__unwind_info: 0x1250
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_selrefs: 0x2160
   __DATA_CONST.__objc_superrefs: 0x198
   __DATA_CONST.__objc_arraydata: 0x2d0
-  __DATA_CONST.__got: 0x448
-  __AUTH_CONST.__const: 0xb00
+  __DATA_CONST.__got: 0x458
+  __AUTH_CONST.__const: 0xb20
   __AUTH_CONST.__cfstring: 0x4d60
   __AUTH_CONST.__objc_const: 0xd3a8
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__objc_intobj: 0x468
   __AUTH_CONST.__objc_arrayobj: 0x198
   __AUTH_CONST.__objc_doubleobj: 0xa0
-  __AUTH_CONST.__auth_got: 0xa08
+  __AUTH_CONST.__auth_got: 0xa10
   __AUTH.__objc_data: 0x19a0
   __DATA.__objc_ivar: 0x618
   __DATA.__data: 0x760
-  __DATA.__bss: 0x6c0
+  __DATA.__bss: 0x7d0
   __DATA_DIRTY.__objc_data: 0x50
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Frameworks/vImage.framework/Versions/A/vImage

   - /usr/lib/libarchive.2.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1985
-  Symbols:   4640
-  CStrings:  1048
+  Functions: 1991
+  Symbols:   4650
+  CStrings:  1049
 
Symbols:
+ ARDisplayCenterTransformForRegion
+ ARDisplayCenterTransformForRegion.frontTransforms
+ ARDisplayCenterTransformForRegion.onceToken
+ ARDisplayCenterTransformForRegion.rearTransforms
+ ARGetFrontCameraOffset
+ ARGetRearCameraOffset
+ _ARDisplayCenterTransformForRegion
+ _ARFrontCameraDisplayCenterTransformForDisplayIndex
+ _ARFrontWideCameraTransformFromBackWideAngleCameraTransformForRegion
+ _ARFrontWideCameraTransformFromBackWideAngleCameraTransformWithZFlipForRegion
+ _ARGetFrontCameraOffset
+ _ARGetRearCameraOffset
+ _ARMobileGestaltArrayForKeyAndDisplayIndex
+ _ARRearCameraDisplayCenterTransformForDisplayIndex
+ _MGCopyAnswerForDisplayAtIndex
+ ___ARDisplayCenterTransformForRegion_block_invoke
+ _kMGDisplayIndexedQueryFrontCameraOffsetFromDisplayCenter
+ _kMGDisplayIndexedQueryRearCameraOffsetFromDisplayCenter
- ARDisplayCenterTransformForCaptureDevicePosition
- ARFrontWideCameraTransformFromBackWideAngleCameraTransform
- ARFrontWideCameraTransformFromBackWideAngleCameraTransformWithZFlip
- _ARDisplayCenterTransformForCaptureDevicePosition
- _ARFrontWideCameraTransformFromBackWideAngleCameraTransform
- _ARFrontWideCameraTransformFromBackWideAngleCameraTransformWithZFlip
- _OUTLINED_FUNCTION_9
- __ARDisplayCenterTransformForCaptureDevicePosition_block_invoke
CStrings:
+ "MobileGestalt display-indexed query failed (error %d, display %ld) for device: %@"
```
