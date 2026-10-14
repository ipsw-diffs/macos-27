## SpeakerRecognition

> `/System/Library/PrivateFrameworks/SpeakerRecognition.framework/Versions/A/SpeakerRecognition`

```diff

-3605.31.3.0.0
-  __TEXT.__text: 0xa2f74
+3605.32.1.14.1
+  __TEXT.__text: 0xa3288
   __TEXT.__objc_methlist: 0x6c40
   __TEXT.__const: 0xb58
   __TEXT.__cstring: 0x1079b
   __TEXT.__swift5_typeref: 0x515
-  __TEXT.__oslogstring: 0xd395
+  __TEXT.__oslogstring: 0xd3fc
   __TEXT.__swift5_capture: 0x19c
   __TEXT.__constg_swiftt: 0x6a8
   __TEXT.__swift5_reflstr: 0x471

   __AUTH_CONST.__objc_intobj: 0x1c8
   __AUTH_CONST.__objc_floatobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x20
-  __AUTH_CONST.__auth_got: 0xdd8
+  __AUTH_CONST.__auth_got: 0xde0
   __AUTH.__objc_data: 0x1c8
   __AUTH.__data: 0x90
   __DATA.__objc_ivar: 0x858

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 2923
-  Symbols:   6308
-  CStrings:  2513
+  Symbols:   6313
+  CStrings:  2517
 
Symbols:
+ _CSIsJ265
+ _objc_msgSend$_fetchPreInstalledSecureAsset
+ _objc_msgSend$addUtterance:toProfile:withSecureAsset:error:
+ _objc_msgSend$getUseRecognizerCombinationFromSecondPassConfigWithSecureAsset:
+ _objc_msgSend$initWithSecureAsset:
Functions:
~ -[SSRVTUITrainingManager initWithLocaleIdentifier:withAppDomain:withSiriSharedUserId:withAudioProviderSelector:shouldTrainViaXPC:] : 592 -> 612
~ -[SSRVTUITrainingManager createKeywordDetector] : 476 -> 1136
~ ___106-[SSRVTUITrainingManager _trainUtteranceLocally:shouldUseASR:mhUUID:referenceString:completionWithResult:]_block_invoke_2 : 1152 -> 1172
~ -[SSRVTUITrainingManager CSVTUITrainingSession:hasTrainUtterance:languageCode:payload:] : 520 -> 600
~ +[SSRUtils isMphVTUIKeywordDetectorSupportedPlatform] : 44 -> 52
CStrings:
+ "%s _currentSecureAsset: %@"
+ "%s keywordDetector: %@"
+ "%s useRecognizerCombination: %u"
+ "%s useSecureAsset:%u"
```
