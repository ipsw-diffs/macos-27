## CoreEmbeddedSpeechRecognition

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/Versions/A/CoreEmbeddedSpeechRecognition`

```diff

-3605.14.1.0.0
-  __TEXT.__text: 0x339ac0
+3610.5.1.0.0
+  __TEXT.__text: 0x34ce8c
   __TEXT.__objc_methlist: 0x4d28
-  __TEXT.__const: 0x9478
-  __TEXT.__cstring: 0xe1c8
+  __TEXT.__const: 0x95c8
+  __TEXT.__cstring: 0xe248
   __TEXT.__gcc_except_tab: 0xd64
-  __TEXT.__oslogstring: 0xc9b5
+  __TEXT.__oslogstring: 0xcc85
   __TEXT.__ustring: 0x4
   __TEXT.__dlopen_cstrs: 0xdc
-  __TEXT.__swift5_typeref: 0x43a2
-  __TEXT.__constg_swiftt: 0x28b4
-  __TEXT.__swift5_reflstr: 0x2e23
-  __TEXT.__swift5_fieldmd: 0x2ca0
+  __TEXT.__swift5_typeref: 0x4448
+  __TEXT.__constg_swiftt: 0x2904
+  __TEXT.__swift5_reflstr: 0x2f93
+  __TEXT.__swift5_fieldmd: 0x2d74
   __TEXT.__swift5_builtin: 0x21c
   __TEXT.__swift5_assocty: 0x5d0
-  __TEXT.__swift5_proto: 0x54c
-  __TEXT.__swift5_types: 0x2c8
-  __TEXT.__swift5_capture: 0xc86c
+  __TEXT.__swift5_proto: 0x554
+  __TEXT.__swift5_types: 0x2d0
+  __TEXT.__swift5_capture: 0xcebc
   __TEXT.__swift5_protos: 0x20
-  __TEXT.__swift_as_entry: 0x260
-  __TEXT.__swift_as_ret: 0x2c4
-  __TEXT.__swift_as_cont: 0x6ac
+  __TEXT.__swift_as_entry: 0x274
+  __TEXT.__swift_as_ret: 0x2d4
+  __TEXT.__swift_as_cont: 0x6e0
   __TEXT.__swift5_mpenum: 0x20
-  __TEXT.__unwind_info: 0xb580
-  __TEXT.__eh_frame: 0x5c10
+  __TEXT.__unwind_info: 0xb928
+  __TEXT.__eh_frame: 0x5dc0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_superrefs: 0x210
   __DATA_CONST.__objc_arraydata: 0x478
-  __DATA_CONST.__got: 0x1a38
-  __AUTH_CONST.__const: 0x24860
+  __DATA_CONST.__got: 0x1a80
+  __AUTH_CONST.__const: 0x25878
   __AUTH_CONST.__cfstring: 0x4d00
-  __AUTH_CONST.__objc_const: 0xb948
+  __AUTH_CONST.__objc_const: 0xb9a8
   __AUTH_CONST.__objc_intobj: 0xeb8
   __AUTH_CONST.__objc_arrayobj: 0x2a0
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x2258
+  __AUTH_CONST.__auth_got: 0x2320
   __AUTH.__objc_data: 0x1128
-  __AUTH.__data: 0xb60
-  __DATA.__objc_ivar: 0x528
-  __DATA.__data: 0x26b0
-  __DATA.__bss: 0x6668
+  __AUTH.__data: 0xc90
+  __DATA.__objc_ivar: 0x52c
+  __DATA.__data: 0x2760
+  __DATA.__bss: 0x6768
   __DATA.__common: 0x108
   __DATA_DIRTY.__objc_data: 0x1ce0
-  __DATA_DIRTY.__data: 0x3f98
+  __DATA_DIRTY.__data: 0x3fa8
   __DATA_DIRTY.__bss: 0x4030
   __DATA_DIRTY.__common: 0x178
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11283
-  Symbols:   6295
-  CStrings:  2447
+  Functions: 11507
+  Symbols:   6311
+  CStrings:  2458
 
Symbols:
+ _OBJC_IVAR_$_CESRSpeechProfileDispatcher._pendingCascadeSetsTransaction
+ _symbolic Say_____GSg 6Speech21PersonalEntityMentionV
+ _symbolic Shy_____G 6Speech17ServerTranscriberC15ReportingOptionO
+ _symbolic Shy_____G 6Speech17ServerTranscriberC19TranscriptionOptionO
+ _symbolic Shy_____G 6Speech17ServerTranscriberC21ResultAttributeOptionO
+ _symbolic Shy_____GIegr_ 6Speech17ServerTranscriberC15ReportingOptionO
+ _symbolic Shy_____GIegr_ 6Speech17ServerTranscriberC19TranscriptionOptionO
+ _symbolic Shy_____GIegr_ 6Speech17ServerTranscriberC21ResultAttributeOptionO
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition23ServerTranscriberResultV
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition31CombinedServerTranscriberOutputV
+ _symbolic _____ 6Speech13EARResultTypeO
+ _symbolic _____ 6Speech17ServerTranscriberC6ResultV
+ _symbolic _____Sg 29CoreEmbeddedSpeechRecognition31CombinedServerTranscriberOutputV
+ _symbolic _____Sg 6Speech6AssetsV
+ _symbolic _____y_Qo_ 6Speech17ServerTranscriberC7resultsQrvpQO
+ _symbolic _____y_____y_Qo______G s16AsyncMapSequenceV 6Speech17ServerTranscriberC7resultsQrvpQO 012CoreEmbeddedD11Recognition08CombinedeF6OutputV
CStrings:
+ "%s: Emergency mode with missing on-device assets for locale: %{public}s; falling back to ServerTranscriber"
+ "%s: Not in emergency orchestration mode; no server fallback"
+ "%s: On-device assets already installed for locale: %{public}s; no server fallback needed"
+ "Configuring ServerTranscriber with:\n- transcriptionOptions: %s\n- reportingOptions: %s\n- attributeOptions: %s"
+ "Configuring analyzer to produce ServerTranscriber results."
+ "Receiving ServerTranscriber results."
+ "ServerTranscriber unexpectedly produced a %{public}s result; ignoring"
+ "Skipping on-screen context entity retrieval — using ServerTranscriber for requestId %s"
+ "Using ServerTranscriber for this request"
+ "analyzerDidProduceServerTranscriberResult(_:)"
+ "com.apple.corespeechd.pendingcascadesets"
+ "shouldUseServerTranscriber(locale:taskHint:)"
- "\t"
```
