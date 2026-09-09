## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8142.RELEASE.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__mod_init_func`
- `__PDATA.__data`
- `__PDATA.__shared_cache`

```diff

 1777.0.27.0.0
-  __TEXT.__text: 0xd3fe7c
+  __TEXT.__text: 0xd4637c
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0xa1dd1
-  __TEXT.__const: 0x19a894
-  __TEXT.__swift5_typeref: 0x29f06
-  __TEXT.__swift5_reflstr: 0x3b908
+  __TEXT.__cstring: 0xa37d1
+  __TEXT.__const: 0x19aa34
+  __TEXT.__swift5_typeref: 0x2a036
+  __TEXT.__swift5_reflstr: 0x3bbc8
   __TEXT.__swift5_assocty: 0xe648
-  __TEXT.__swift5_fieldmd: 0x5c38c
-  __TEXT.__constg_swiftt: 0x616b8
-  __TEXT.__swift5_protos: 0x1204
-  __TEXT.__swift5_proto: 0x9a24
-  __TEXT.__swift5_types: 0x5eb0
+  __TEXT.__swift5_fieldmd: 0x5c530
+  __TEXT.__constg_swiftt: 0x61a04
+  __TEXT.__swift5_protos: 0x1208
+  __TEXT.__swift5_proto: 0x9a2c
+  __TEXT.__swift5_types: 0x5ec4
   __TEXT.__swift5_types2: 0xbc
-  __TEXT.__swift5_builtin: 0x2724
+  __TEXT.__swift5_builtin: 0x2738
   __TEXT.__swift5_capture: 0x34d4
   __TEXT.__objc_methtype: 0x2b6
-  __TEXT.__swift5_mpenum: 0xc18
+  __TEXT.__swift5_mpenum: 0xc38
   __TEXT.__swift_as_entry: 0x160c
   __TEXT.__swift_as_ret: 0x1808
   __TEXT.__swift_as_cont: 0x2e58

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x128
-  __TEXT.__eh_frame: 0x74fd4
+  __TEXT.__eh_frame: 0x74fdc
   __DATA.__TIGHTBEAM_VT: 0x1200
   __DATA.__TIGHTBEAM: 0x4a8
-  __DATA.__const: 0xe1858
-  __DATA.__data: 0x4ea18
+  __DATA.__const: 0xe1a28
+  __DATA.__data: 0x4ed68
   __DATA.__mod_init_func: 0x40
   __DATA.__ENDPOINTS: 0x1b7b4
-  __DATA.__auth_ptr: 0x7480
+  __DATA.__auth_ptr: 0x7488
   __DATA.__DEVICETREE: 0x30
   __DATA.__shared_cache: 0x3b8
   __DATA.__DARTS: 0x93f

   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 47298
+  Functions: 47342
   Symbols:   1
-  CStrings:  14969
+  CStrings:  15063
 
CStrings:
+ "  Device state = "
+ " not allowed while strobe alternative indicator is active"
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Sat Aug  8 15:53:53 PDT 2026; root:AppleImage4_exclavecore-374~17266/ExclaveImage4/RELEASE_ARM64E"
+ "Alternative Indicator Triggered = "
+ "BacklitSunClassifier_V6X"
+ "Build Date: Sat Aug  8 14:40:58 PDT 2026"
+ "Display POST Failed = "
+ "Display issue detected: continuing to use health checks until microphone is turned on"
+ "Display issue detected: switching to strobe alternative indicator"
+ "ExclaveOS Image4 Framework Version 7.0.0: Sat Aug  8 15:53:53 PDT 2026; root:AppleImage4_exclavecore-374~17266/ExclaveImage4/RELEASE_ARM64E"
+ "FaceDetectionIR_V6X"
+ "FaceDetectionRGB_V6X"
+ "FaceLivelinessFull_Int"
+ "FaceLivelinessFull_UC"
+ "Faceliveliness_UC"
+ "Failed to end strobe"
+ "Failed to end strobe after MOT met"
+ "Failed to notify corerepaird of strobe start"
+ "Failed to prepare strobe"
+ "Failed to prepare strobe before MOT was met"
+ "Failed to update strobe before MOT was met"
+ "Failed to update strobe power state"
+ "Failed to update strobe power state to "
+ "Force TCON Threshold Exceeded = "
+ "GlassesClassifierIR_V6X"
+ "GlassesClassifierRGB_V6X"
+ "GlassesClassifier_V6X"
+ "INDICATOR: STROBE ALT -> OFF"
+ "INDICATOR: STROBE ALT -> ON"
+ "INDICATOR: STROBE ALT -> PENDING STOP"
+ "INDICATOR: STROBE ALT -> PENDING STOP CANCELED"
+ "INDICATOR: STROBE ALT -> PREPARE"
+ "INDICATOR: STROBE FLASH ALT -> DONE"
+ "INDICATOR: STROBE FLASH ALT -> OFF"
+ "INDICATOR: STROBE FLASH ALT -> ON"
+ "INDICATOR: STROBE FLASH ALT -> PENDING STOP"
+ "INDICATOR: STROBE FLASH ALT -> PENDING STOP CANCELED"
+ "INDICATOR: STROBE FLASH ALT -> PREPARE"
+ "Invalid start state for strobe flash machine (pending: "
+ "LandmarkSemanticFaceIR_V6X"
+ "LandmarkSemanticFaceRGB_V6X"
+ "Notified corerepaird of strobe start"
+ "ObstructionDetection_V6X"
+ "Sat Aug  8 16:48:36 PDT 2026"
+ "System/ExclaveKit/System/Library/Frameworks/"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/Vision_internal.framework/Resources/faceliveliness_uc_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/Vision_internal.framework/Resources/facelivelinessfull_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/Vision_internal.framework/Resources/facelivelinessfull_uc_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/Vision_internal.framework/Resources/faceprint_uc_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/attention_detection_ir.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/attention_detection_rgb.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/backlit_sun_classifier.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/face_detection.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/face_detection_ir.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/face_detection_rgb.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasses_classifier.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasses_classifier_ir.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasses_classifier_rgb.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswing_net_res1.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswing_net_res2.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswing_net_res3.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswingnet.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswingnet256.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswingnet352.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswingnet512.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswingnet768.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswingnet816.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/landmark_semantic_face.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/landmark_semantic_face_ir.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/landmark_semantic_face_rgb.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/obstruction_detection.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/ViewingDistance.framework/Resources/model.bundle/*.bundle/main/main_ane"
+ "backlit_sun_classifier.*.hwx"
+ "display-post-failed"
+ "display-post-failed-1"
+ "face_detection_ir.*.hwx"
+ "face_detection_rgb.*.hwx"
+ "glasses_classifier.*.hwx"
+ "glasses_classifier_ir.*.hwx"
+ "glasses_classifier_rgb.*.hwx"
+ "glasswing_net_res1.*.hwx"
+ "glasswing_net_res2.*.hwx"
+ "glasswing_net_res3.*.hwx"
+ "glasswingnet.*.hwx"
+ "glasswingnet256.*.hwx"
+ "glasswingnet352.*.hwx"
+ "glasswingnet512.*.hwx"
+ "glasswingnet768.*.hwx"
+ "glasswingnet816.*.hwx"
+ "landmark_semantic_face_ir.*.hwx"
+ "landmark_semantic_face_rgb.*.hwx"
+ "obstruction_detection.*.hwx"
+ "octopus_fang_alt_indicator"
+ "octopus_force_alt_indicator"
+ "octopus_force_display_POST_failed"
+ "octopus_force_tcon_threshold_exceeded"
+ "octopus_no_fang_alt_indicator"
+ "policy-alt-indicator"
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Mon Aug 10 00:39:23 PDT 2026; root:AppleImage4_exclavecore-374~17304/ExclaveImage4/RELEASE_ARM64E"
- "Build Date: Sat Aug  8 17:06:14 PDT 2026"
- "ExclaveOS Image4 Framework Version 7.0.0: Mon Aug 10 00:39:23 PDT 2026; root:AppleImage4_exclavecore-374~17304/ExclaveImage4/RELEASE_ARM64E"
- "Mon Aug 10 01:20:43 PDT 2026"
```
