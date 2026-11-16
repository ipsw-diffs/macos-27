## EmbeddedAcousticRecognition

> `/System/Library/PrivateFrameworks/EmbeddedAcousticRecognition.framework/Versions/A/EmbeddedAcousticRecognition`

```diff

-3610.5.1.0.0
-  __TEXT.__text: 0xadf0c8
-  __TEXT.__objc_methlist: 0x6b8c
+3610.7.2.0.0
+  __TEXT.__text: 0xadfac8
+  __TEXT.__objc_methlist: 0x6bbc
   __TEXT.__const: 0x5ed38
-  __TEXT.__gcc_except_tab: 0xc0910
+  __TEXT.__gcc_except_tab: 0xc0968
   __TEXT.__cstring: 0x7a2e7
-  __TEXT.__oslogstring: 0x3161
+  __TEXT.__oslogstring: 0x3231
   __TEXT.__ustring: 0xa8
   __TEXT.__dlopen_cstrs: 0x60
   __TEXT.__constg_swiftt: 0x13c

   __TEXT.__swift_as_ret: 0x1c
   __TEXT.__swift_as_cont: 0x28
   __TEXT.__swift5_capture: 0x114
-  __TEXT.__unwind_info: 0x3e990
+  __TEXT.__unwind_info: 0x3e9c0
   __TEXT.__eh_frame: 0x520
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x20
-  __DATA_CONST.__objc_selrefs: 0x3680
+  __DATA_CONST.__objc_selrefs: 0x36a0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x3e0
   __DATA_CONST.__objc_arraydata: 0xd8
   __DATA_CONST.__got: 0x720
   __AUTH_CONST.__const: 0x4bb88
   __AUTH_CONST.__cfstring: 0x2960
-  __AUTH_CONST.__objc_const: 0xe260
+  __AUTH_CONST.__objc_const: 0xe300
   __AUTH_CONST.__weak_auth_got: 0x50
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_arrayobj: 0x48

   __AUTH.__thread_vars: 0x390
   __AUTH.__thread_data: 0x40
   __AUTH.__thread_bss: 0xae8
-  __DATA.__objc_ivar: 0x9b0
+  __DATA.__objc_ivar: 0x9c0
   __DATA.__data: 0xea8
   __DATA.__common: 0x125
   __DATA.__bss: 0x850

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 40075
-  Symbols:   61102
-  CStrings:  19857
+  Functions: 40086
+  Symbols:   61120
+  CStrings:  19860
 
Symbols:
+ -[EARCaesuraSilencePosteriorGenerator _applyQuietMode]
+ -[EARCaesuraSilencePosteriorGenerator initWithConfigFile:samplingRate:queue:quietRowsPerCompute:quietResumeAfterSilenceMs:]
+ -[EARCaesuraSilencePosteriorGenerator quietResumeAfterSilenceMs]
+ -[EARCaesuraSilencePosteriorGenerator quietRowsPerCompute]
+ _OBJC_IVAR_$_EARCaesuraSilencePosteriorGenerator._quietResumeAfterSilenceMs
+ _OBJC_IVAR_$_EARCaesuraSilencePosteriorGenerator._quietRowsPerCompute
+ _OBJC_IVAR_$_EARCaesuraSilencePosteriorGenerator._requestedQuietResumeMs
+ _OBJC_IVAR_$_EARCaesuraSilencePosteriorGenerator._requestedQuietRows
+ __ZN5kaldi22OnlineNnetForwardInput16IsRowIndependentERKNS_5nnet14NnetE
+ __ZN5kaldi22OnlineNnetForwardInput18SetStrictBatchSizeEi
+ __ZN6quasar25SilencePosteriorGenerator17setRowsPerComputeEi
+ __ZN6quasar25SilencePosteriorGenerator18enableFrameByFrameEv
+ __ZNK5kaldi22OnlineNnetForwardInput29SupportsStrictBatchSizeChangeEv
+ __ZNK6quasar25SilencePosteriorGenerator15numBufferedRowsEv
+ __ZNK6quasar25SilencePosteriorGenerator22supportsRowsPerComputeEv
+ __ZNSt3__120dynamic_pointer_castB9nqe220106IN5kaldi5nnet117Nnet1InferenceNetENS1_17FeedForwardNetItfEEENS_10shared_ptrIT_EERKNS5_IT0_EE
+ ___block_descriptor_68_ea8_32w40c62_ZTSNSt3__110shared_ptrIN6quasar25SilencePosteriorGeneratorEEE_e5_v8?0l
+ _objc_msgSend$_applyQuietMode
+ _objc_msgSend$initWithConfigFile:samplingRate:queue:quietRowsPerCompute:quietResumeAfterSilenceMs:
- ___block_descriptor_56_ea8_32w40c62_ZTSNSt3__110shared_ptrIN6quasar25SilencePosteriorGeneratorEEE_e5_v8?0l
CStrings:
+ "EARSPG: quiet mode on rows=%lu resumeAfterSilenceMs=%lu"
+ "EARSPG: quiet mode summary rows=%d frames=%llu quietFrames=%llu nnetCalls=%llu toActive=%llu toQuiet=%llu"
+ "EARSPG: quiet mode unavailable for %{public}@"
```
