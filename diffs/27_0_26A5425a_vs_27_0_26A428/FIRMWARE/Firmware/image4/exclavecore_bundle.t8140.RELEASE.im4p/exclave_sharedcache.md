## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.im4p/exclave_sharedcache`

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
-  __TEXT.__text: 0xd53afc
+  __TEXT.__text: 0xd59f78
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0xa0f91
-  __TEXT.__const: 0x1cc994
-  __TEXT.__swift5_typeref: 0x29c1e
-  __TEXT.__swift5_reflstr: 0x42718
+  __TEXT.__cstring: 0xa2991
+  __TEXT.__const: 0x1ccb34
+  __TEXT.__swift5_typeref: 0x29d4e
+  __TEXT.__swift5_reflstr: 0x429d8
   __TEXT.__swift5_assocty: 0xe188
-  __TEXT.__swift5_fieldmd: 0x6c2bc
-  __TEXT.__constg_swiftt: 0x6395c
-  __TEXT.__swift5_protos: 0x1160
-  __TEXT.__swift5_proto: 0xa2e4
-  __TEXT.__swift5_types: 0x6640
+  __TEXT.__swift5_fieldmd: 0x6c460
+  __TEXT.__constg_swiftt: 0x63ca8
+  __TEXT.__swift5_protos: 0x1164
+  __TEXT.__swift5_proto: 0xa2ec
+  __TEXT.__swift5_types: 0x6654
   __TEXT.__swift5_types2: 0xb8
-  __TEXT.__swift5_builtin: 0x26fc
+  __TEXT.__swift5_builtin: 0x2710
   __TEXT.__swift5_capture: 0x35d4
   __TEXT.__objc_methtype: 0x2b6
-  __TEXT.__swift5_mpenum: 0xbc0
+  __TEXT.__swift5_mpenum: 0xbe0
   __TEXT.__swift_as_entry: 0x15a4
   __TEXT.__swift_as_ret: 0x17dc
   __TEXT.__swift_as_cont: 0x2dc8

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x140
-  __TEXT.__eh_frame: 0x72e70
+  __TEXT.__eh_frame: 0x72e78
   __DATA.__TIGHTBEAM_VT: 0x1080
   __DATA.__TIGHTBEAM: 0x448
-  __DATA.__const: 0x119c28
-  __DATA.__data: 0x4f848
+  __DATA.__const: 0x119df8
+  __DATA.__data: 0x4fb98
   __DATA.__mod_init_func: 0x48
   __DATA.__ENDPOINTS: 0x1b7b4
-  __DATA.__auth_ptr: 0x6108
+  __DATA.__auth_ptr: 0x6110
   __DATA.__DEVICETREE: 0x30
   __DATA.__shared_cache: 0x3b8
   __DATA.__DARTS: 0x93f

   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 48983
+  Functions: 49025
   Symbols:   1
-  CStrings:  14933
+  CStrings:  15027
 
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
+ "Sat Aug  8 16:48:44 PDT 2026"
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
