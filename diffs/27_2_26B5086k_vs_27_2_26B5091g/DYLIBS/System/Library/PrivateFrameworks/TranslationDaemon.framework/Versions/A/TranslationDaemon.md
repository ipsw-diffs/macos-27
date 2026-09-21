## TranslationDaemon

> `/System/Library/PrivateFrameworks/TranslationDaemon.framework/Versions/A/TranslationDaemon`

```diff

 393.1.0.0.0
-  __TEXT.__text: 0x1b1d08
-  __TEXT.__objc_methlist: 0x1a5b0
-  __TEXT.__const: 0x9e0
+  __TEXT.__text: 0x1b08a0
+  __TEXT.__objc_methlist: 0x1a568
+  __TEXT.__const: 0x9d0
   __TEXT.__gcc_except_tab: 0x1b558
-  __TEXT.__cstring: 0x64cb
-  __TEXT.__oslogstring: 0xde2a
+  __TEXT.__cstring: 0x63fb
+  __TEXT.__oslogstring: 0xdda0
   __TEXT.__dlopen_cstrs: 0xb2
-  __TEXT.__swift5_typeref: 0x381
+  __TEXT.__swift5_typeref: 0x36d
   __TEXT.__swift5_capture: 0xe0
-  __TEXT.__constg_swiftt: 0x104
+  __TEXT.__constg_swiftt: 0xfc
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_reflstr: 0x8e
   __TEXT.__swift5_fieldmd: 0xcc

   __TEXT.__swift_as_ret: 0xc
   __TEXT.__swift_as_cont: 0x10
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x110a8
+  __TEXT.__unwind_info: 0x11078
   __TEXT.__eh_frame: 0x388
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6cd8
+  __DATA_CONST.__objc_selrefs: 0x6c90
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x1128
   __DATA_CONST.__objc_arraydata: 0x3e8
-  __DATA_CONST.__got: 0xf78
-  __AUTH_CONST.__const: 0x4358
-  __AUTH_CONST.__cfstring: 0x7f40
-  __AUTH_CONST.__objc_const: 0x2d2f8
+  __DATA_CONST.__got: 0xf50
+  __AUTH_CONST.__const: 0x4350
+  __AUTH_CONST.__cfstring: 0x7f00
+  __AUTH_CONST.__objc_const: 0x2d2c8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x348
   __AUTH_CONST.__objc_arrayobj: 0x138
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x30
-  __AUTH_CONST.__auth_got: 0xbf8
-  __AUTH.__objc_data: 0xa210
-  __DATA.__objc_ivar: 0x1200
-  __DATA.__data: 0xdc0
-  __DATA.__bss: 0x6c0
-  __DATA_DIRTY.__objc_data: 0x10e0
-  __DATA_DIRTY.__data: 0x288
-  __DATA_DIRTY.__bss: 0x310
+  __AUTH_CONST.__auth_got: 0xbc8
+  __AUTH.__objc_data: 0xa1c0
+  __DATA.__objc_ivar: 0x11fc
+  __DATA.__data: 0xd70
+  __DATA.__bss: 0x6b0
+  __DATA_DIRTY.__objc_data: 0x1130
+  __DATA_DIRTY.__data: 0x2c0
+  __DATA_DIRTY.__bss: 0x320
   __DATA_DIRTY.__common: 0x30
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 10628
-  Symbols:   21568
-  CStrings:  2298
+  Functions: 10615
+  Symbols:   21548
+  CStrings:  2292
 
Symbols:
- +[_LTTranslationServer _aiInferenceLocationErrorForContext:]
- +[_LTTranslationServer _contextForcesPrivateCloudCompute:]
- -[_LTDLanguageStatusObservationList _observationsByFoldingPCCIntoObservations:]
- -[_LTDLanguageStatusObservationList pccObservations]
- -[_LTDLanguageStatusObservationList setPccObservations:]
- OBJC_IVAR_$__LTDLanguageStatusObservationList._pccObservations
- __OBJC_$_CLASS_METHODS__LTTranslationServer
- ___PCCLanguageExpansion_isAvailable
- _objc_msgSend$_aiInferenceLocationErrorForContext:
- _objc_msgSend$_contextForcesPrivateCloudCompute:
- _objc_msgSend$_invalidateCachedObservationsIncludingPCC
- _objc_msgSend$_observationByFoldingPCCObservation:intoObservation:
- _objc_msgSend$_observationsByFoldingPCCIntoObservations:
- _objc_msgSend$allowsPrivateCloudComputeLanguages
- _objc_msgSend$lt_invalidRequestErrorWithDescription:
- _objc_msgSend$pccObservationsWithLocaleRanks:
- _objc_msgSend$setAllowsPrivateCloudComputeLanguages:
- _objc_msgSend$setPccObservations:
- _symbolic _____Sg 12ModelCatalog17UseCaseIdentifierV
- _symbolic _____Sg_ABt 12ModelCatalog17UseCaseIdentifierV
CStrings:
- "A"
- "Context forces PCC, restricting engine selection to the AI adapter; route: %ld"
- "Context's aiInferenceLocation can't be honored, returning no engine: %@"
- "PCCLanguageExpansion"
- "aiInferenceLocation is .pcc, but forcedOfflineTranslation makes this request incompatible with PCC"
- "aiInferenceLocation is .pcc, but onDeviceEngineType is .traditional, which can't use AI inference"
```
