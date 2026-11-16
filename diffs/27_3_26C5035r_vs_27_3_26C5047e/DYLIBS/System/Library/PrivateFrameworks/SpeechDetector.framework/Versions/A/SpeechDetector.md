## SpeechDetector

> `/System/Library/PrivateFrameworks/SpeechDetector.framework/Versions/A/SpeechDetector`

```diff

-3610.11.1.0.0
-  __TEXT.__text: 0xea0
-  __TEXT.__objc_methlist: 0x46c
+3610.19.5.0.0
+  __TEXT.__text: 0xf04
+  __TEXT.__objc_methlist: 0x484
   __TEXT.__const: 0x68
   __TEXT.__cstring: 0x203
   __TEXT.__oslogstring: 0x64
-  __TEXT.__unwind_info: 0xe8
+  __TEXT.__unwind_info: 0xf0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2d0
+  __DATA_CONST.__objc_selrefs: 0x2f0
   __DATA_CONST.__objc_superrefs: 0x18
   __DATA_CONST.__got: 0x40
   __AUTH_CONST.__const: 0x50
   __AUTH_CONST.__cfstring: 0x1a0
-  __AUTH_CONST.__objc_const: 0x850
+  __AUTH_CONST.__objc_const: 0x860
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0xa0
   __DATA.__objc_ivar: 0x50

   - /System/Library/PrivateFrameworks/EmbeddedAcousticRecognition.framework/Versions/A/EmbeddedAcousticRecognition
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 60
-  Symbols:   219
+  Functions: 62
+  Symbols:   224
   CStrings:  23
 
Symbols:
+ -[OSDAnalyzer _setupCaesuraSPGWithConfigFile:sampleRate:osdAnalyzerAssetLocker:quietRowsPerCompute:quietResumeAfterSilenceMs:]
+ -[OSDAnalyzer initWithConfigFile:sampleRate:context:queue:delegate:osdAnalyzerAssetLocker:quietRowsPerCompute:quietResumeAfterSilenceMs:]
+ -[OSDAnalyzer quietModeRows]
+ _objc_msgSend$_setupCaesuraSPGWithConfigFile:sampleRate:osdAnalyzerAssetLocker:quietRowsPerCompute:quietResumeAfterSilenceMs:
+ _objc_msgSend$initWithConfigFile:sampleRate:context:queue:delegate:osdAnalyzerAssetLocker:quietRowsPerCompute:quietResumeAfterSilenceMs:
+ _objc_msgSend$initWithConfigFile:samplingRate:queue:quietRowsPerCompute:quietResumeAfterSilenceMs:
+ _objc_msgSend$quietRowsPerCompute
- -[OSDAnalyzer _setupCaesuraSPGWithConfigFile:sampleRate:osdAnalyzerAssetLocker:]
- _objc_msgSend$_setupCaesuraSPGWithConfigFile:sampleRate:osdAnalyzerAssetLocker:
```
