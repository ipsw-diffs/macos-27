## ARKitCore

> `/System/Library/SubFrameworks/ARKitCore.framework/Versions/A/ARKitCore`

```diff

 781.0.5.0.3
-  __TEXT.__text: 0x50154
+  __TEXT.__text: 0x50454
   __TEXT.__objc_methlist: 0x2c9c
   __TEXT.__const: 0x3660
   __TEXT.__cstring: 0xbd71
   __TEXT.__gcc_except_tab: 0x1c0c
-  __TEXT.__oslogstring: 0x5fc1
+  __TEXT.__oslogstring: 0x6013
   __TEXT.__ustring: 0xde
-  __TEXT.__unwind_info: 0x1a30
+  __TEXT.__unwind_info: 0x1a38
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classrefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x1e0
   __DATA_CONST.__objc_arraydata: 0x448
-  __DATA_CONST.__got: 0x508
-  __AUTH_CONST.__const: 0x1b70
+  __DATA_CONST.__got: 0x518
+  __AUTH_CONST.__const: 0x1b90
   __AUTH_CONST.__cfstring: 0x5ca0
   __AUTH_CONST.__objc_const: 0x72c8
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_arrayobj: 0x1b0
   __AUTH_CONST.__objc_intobj: 0x1818
   __AUTH_CONST.__objc_doubleobj: 0xd0
-  __AUTH_CONST.__auth_got: 0xb58
+  __AUTH_CONST.__auth_got: 0xb60
   __AUTH.__objc_data: 0xe10
   __DATA.__objc_ivar: 0x2a4
   __DATA.__data: 0xac8
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x658
+  __DATA.__bss: 0x768
   __DATA_DIRTY.__objc_data: 0x690
-  __DATA_DIRTY.__bss: 0x338
+  __DATA_DIRTY.__bss: 0x340
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Frameworks/vImage.framework/Versions/A/vImage
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libchannel.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/librealtime_safety.dylib
-  Functions: 2347
-  Symbols:   4629
-  CStrings:  1458
+  Functions: 2353
+  Symbols:   4640
+  CStrings:  1459
 
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
- __ARDisplayCenterTransformForCaptureDevicePosition_block_invoke
CStrings:
+ "MobileGestalt display-indexed query failed (error %d, display %ld) for device: %@"
```
