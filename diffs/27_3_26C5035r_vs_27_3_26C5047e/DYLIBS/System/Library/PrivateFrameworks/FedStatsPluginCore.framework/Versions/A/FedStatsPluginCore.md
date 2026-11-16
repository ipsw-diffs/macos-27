## FedStatsPluginCore

> `/System/Library/PrivateFrameworks/FedStatsPluginCore.framework/Versions/A/FedStatsPluginCore`

```diff

 85.0.0.0.0
-  __TEXT.__text: 0x60c80
+  __TEXT.__text: 0x615c0
   __TEXT.__objc_methlist: 0xe0c
   __TEXT.__const: 0x1cd8
-  __TEXT.__cstring: 0x2ac0
+  __TEXT.__cstring: 0x2b60
   __TEXT.__gcc_except_tab: 0x2c
-  __TEXT.__oslogstring: 0x2497
+  __TEXT.__oslogstring: 0x25b7
   __TEXT.__constg_swiftt: 0xf48
-  __TEXT.__swift5_typeref: 0xba0
+  __TEXT.__swift5_typeref: 0xba4
   __TEXT.__swift5_fieldmd: 0xe08
   __TEXT.__swift5_proto: 0xdc
   __TEXT.__swift5_types: 0xc0
   __TEXT.__swift5_reflstr: 0x15b6
-  __TEXT.__swift5_capture: 0x490
+  __TEXT.__swift5_capture: 0x4a0
   __TEXT.__swift_as_entry: 0x94
   __TEXT.__swift_as_ret: 0x90
   __TEXT.__swift_as_cont: 0x16c
   __TEXT.__swift5_protos: 0x10
   __TEXT.__swift5_assocty: 0xc0
-  __TEXT.__unwind_info: 0x1468
+  __TEXT.__unwind_info: 0x1480
   __TEXT.__eh_frame: 0x2868
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_classlist: 0x200
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa48
+  __DATA_CONST.__objc_selrefs: 0xa50
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0xa0
-  __DATA_CONST.__objc_arraydata: 0x148
-  __DATA_CONST.__got: 0x418
-  __AUTH_CONST.__const: 0x22e8
-  __AUTH_CONST.__cfstring: 0x27c0
+  __DATA_CONST.__objc_arraydata: 0x150
+  __DATA_CONST.__got: 0x420
+  __AUTH_CONST.__const: 0x2340
+  __AUTH_CONST.__cfstring: 0x2800
   __AUTH_CONST.__objc_const: 0x3cf8
-  __AUTH_CONST.__objc_arrayobj: 0xc0
+  __AUTH_CONST.__objc_arrayobj: 0xd8
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_intobj: 0x18
-  __AUTH_CONST.__auth_got: 0x8e8
+  __AUTH_CONST.__auth_got: 0x8f0
   __AUTH.__objc_data: 0xc20
   __AUTH.__data: 0x1070
   __DATA.__objc_ivar: 0xc8
-  __DATA.__data: 0x760
+  __DATA.__data: 0x768
   __DATA.__bss: 0x10b0
   __DATA.__common: 0x79
   __DATA_DIRTY.__objc_data: 0x1f8

   - /System/Library/PrivateFrameworks/CrashReporterSupport.framework/Versions/A/CrashReporterSupport
   - /System/Library/PrivateFrameworks/DifferentialPrivacy.framework/Versions/A/DifferentialPrivacy
   - /System/Library/PrivateFrameworks/FedStats.framework/Versions/A/FedStats
+  - /System/Library/PrivateFrameworks/GenerativeModels.framework/Versions/A/GenerativeModels
   - /System/Library/PrivateFrameworks/LighthouseBackground.framework/Versions/A/LighthouseBackground
   - /System/Library/PrivateFrameworks/MobileKeyBag.framework/Versions/A/MobileKeyBag
   - /usr/lib/libMobileGestalt.dylib

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1357
-  Symbols:   1442
-  CStrings:  582
+  Functions: 1363
+  Symbols:   1445
+  CStrings:  590
 
Symbols:
+ _OBJC_CLASS_$_GMAvailabilityWrapper
+ _objc_msgSend$currentWithUseCaseIdentifiers:language:isChinaPartOfAdditonalPolicyOptions:
+ _symbolic Sb
CStrings:
+ "Apple Intelligence is turned off."
+ "Device is China AI eligible."
+ "Device is not China AI eligible."
+ "GMAvailabilityStatus = %ld, isChinaPartOfAdditonalPolicyOptions = %d"
+ "GMAvailabilityStatus = %ld, isChinaPartOfAdditonalPolicyOptions = %{bool}d"
+ "SELECT eventTimestamp from 'RegionalSafetyAnalysis.GuardrailResult' ORDER BY eventTimestamp DESC LIMIT 1"
+ "The device has used China AI."
+ "com.apple.Settings.AppleIntelligence"
```
