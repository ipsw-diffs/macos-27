## WorkoutAnnouncements

> `/System/Library/PrivateFrameworks/WorkoutAnnouncements.framework/Versions/A/WorkoutAnnouncements`

```diff

-3605.11.1.0.0
-  __TEXT.__text: 0x20d9c
+3610.9.1.0.0
+  __TEXT.__text: 0x21de8
   __TEXT.__objc_methlist: 0x14
-  __TEXT.__const: 0x3320
-  __TEXT.__swift5_typeref: 0x7c2
-  __TEXT.__oslogstring: 0x7c5
-  __TEXT.__swift5_capture: 0x24
-  __TEXT.__swift5_reflstr: 0x94c
-  __TEXT.__swift5_assocty: 0x120
-  __TEXT.__constg_swiftt: 0xb1c
+  __TEXT.__const: 0x3420
+  __TEXT.__swift5_typeref: 0x802
+  __TEXT.__oslogstring: 0x8b5
+  __TEXT.__swift5_capture: 0x38
+  __TEXT.__swift5_reflstr: 0x95c
+  __TEXT.__swift5_assocty: 0x138
+  __TEXT.__constg_swiftt: 0xb54
   __TEXT.__swift5_fieldmd: 0xd10
   __TEXT.__cstring: 0x512
-  __TEXT.__swift5_proto: 0x2d8
-  __TEXT.__swift5_types: 0xc0
+  __TEXT.__swift5_builtin: 0x14
+  __TEXT.__swift5_proto: 0x2e4
+  __TEXT.__swift5_types: 0xc4
   __TEXT.__swift_as_entry: 0x64
   __TEXT.__swift_as_ret: 0x7c
   __TEXT.__swift_as_cont: 0x90
   __TEXT.__swift5_protos: 0x14
-  __TEXT.__unwind_info: 0xe38
-  __TEXT.__eh_frame: 0x1cd8
+  __TEXT.__unwind_info: 0xe98
+  __TEXT.__eh_frame: 0x1d10
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x198
+  __DATA_CONST.__const: 0x1b0
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1c0
+  __DATA_CONST.__objc_selrefs: 0x1e8
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x1f00
+  __AUTH_CONST.__const: 0x1f48
   __AUTH_CONST.__objc_const: 0x2c8
-  __AUTH_CONST.__auth_got: 0x768
+  __AUTH_CONST.__auth_got: 0x7b8
   __AUTH.__objc_data: 0x140
   __AUTH.__data: 0xc0
-  __DATA.__data: 0x650
-  __DATA.__bss: 0x5280
+  __DATA.__data: 0x680
+  __DATA.__bss: 0x5400
   __DATA.__common: 0x20
   __DATA_DIRTY.__objc_data: 0x98
   __DATA_DIRTY.__data: 0x3c0

   - /System/Library/PrivateFrameworks/SiriKitInvocation.framework/Versions/A/SiriKitInvocation
   - /System/Library/PrivateFrameworks/SiriNLUTypes.framework/Versions/A/SiriNLUTypes
   - /System/Library/PrivateFrameworks/SiriOntology.framework/Versions/A/SiriOntology
+  - /System/Library/PrivateFrameworks/SiriTTSService.framework/Versions/A/SiriTTSService
   - /System/Library/PrivateFrameworks/SiriUtilities.framework/Versions/A/SiriUtilities
   - /System/Library/PrivateFrameworks/SiriVirtualDeviceResolution.framework/Versions/A/SiriVirtualDeviceResolution
   - /usr/lib/libSystem.B.dylib

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 947
-  Symbols:   471
-  CStrings:  83
+  Functions: 963
+  Symbols:   485
+  CStrings:  87
 
Symbols:
+ _OBJC_CLASS_$_AFLocalization
+ _OBJC_CLASS_$_TTSAssetType
+ _associated conformance So16TTSAssetPropertyVSHSCSQ
+ _objc_msgSend$downloading
+ _objc_msgSend$locallyAvailable
+ _objc_msgSend$name
+ _objc_msgSend$sharedInstance
+ _objc_msgSend$voiceSimilarToVoice:inSiriSessionLanguage:
+ _swift_getForeignTypeMetadata
+ _symbolic _____ 14SiriTTSService13DaemonSessionC
+ _symbolic _____ So16TTSAssetPropertyV
+ _symbolic ______ypt So16TTSAssetPropertyV
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC So16TTSAssetPropertyV
+ _symbolic _____y_____ypG s18_DictionaryStorageC So16TTSAssetPropertyV
CStrings:
+ "Message language %s does not match Siri voice language %s; speaking with voice %s in %s"
+ "No voice exists for message language %s (Siri speaks %s); not playing"
+ "Voice asset %s for %s is not on disk; subscribing to it"
+ "Voice subscription for %s failed: %@"
+ "Voice subscription for %s succeeded"
- "Message language code does not match Siri voice language code %s vs. %s; not playing"
```
