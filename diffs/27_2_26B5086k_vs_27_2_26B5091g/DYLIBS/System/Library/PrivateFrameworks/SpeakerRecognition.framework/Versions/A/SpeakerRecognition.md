## SpeakerRecognition

> `/System/Library/PrivateFrameworks/SpeakerRecognition.framework/Versions/A/SpeakerRecognition`

```diff

-3605.23.1.0.0
-  __TEXT.__text: 0xa2afc
-  __TEXT.__objc_methlist: 0x6bf0
+3605.25.2.0.0
+  __TEXT.__text: 0xa2ee4
+  __TEXT.__objc_methlist: 0x6c30
   __TEXT.__const: 0xb58
-  __TEXT.__cstring: 0x106dc
+  __TEXT.__cstring: 0x1079b
   __TEXT.__swift5_typeref: 0x515
-  __TEXT.__oslogstring: 0xd295
+  __TEXT.__oslogstring: 0xd360
   __TEXT.__swift5_capture: 0x19c
   __TEXT.__constg_swiftt: 0x6a0
   __TEXT.__swift5_reflstr: 0x471

   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_proto: 0x20
   __TEXT.__gcc_except_tab: 0x2458
-  __TEXT.__unwind_info: 0x25c8
+  __TEXT.__unwind_info: 0x25e0
   __TEXT.__eh_frame: 0x868
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x160
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3cc8
+  __DATA_CONST.__objc_selrefs: 0x3cf0
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x228
   __DATA_CONST.__objc_arraydata: 0x3c0
   __DATA_CONST.__got: 0xb78
   __AUTH_CONST.__const: 0x25e0
   __AUTH_CONST.__cfstring: 0x57e0
-  __AUTH_CONST.__objc_const: 0xb868
+  __AUTH_CONST.__objc_const: 0xb888
   __AUTH_CONST.__objc_dictobj: 0x960
   __AUTH_CONST.__objc_intobj: 0x1c8
   __AUTH_CONST.__objc_floatobj: 0x50

   __AUTH_CONST.__auth_got: 0xdd8
   __AUTH.__objc_data: 0x1c8
   __AUTH.__data: 0x90
-  __DATA.__objc_ivar: 0x854
+  __DATA.__objc_ivar: 0x858
   __DATA.__data: 0x12e0
   __DATA.__bss: 0x4f8
   __DATA.__common: 0x60

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2916
-  Symbols:   6294
-  CStrings:  2505
+  Functions: 2922
+  Symbols:   6306
+  CStrings:  2512
 
Symbols:
+ -[CSVTUITrainingSession hasLiveSpeechTranscriber]
+ -[CSVTUITrainingSession hasUsableRecognizer]
+ -[CSVTUITrainingSessionWithPayload _deferCloseForTranscriberFinal]
+ -[CSVTUITrainingSessionWithPayload _firedTranscriberFinalTimeout]
+ -[CSVTUITrainingSessionWithPayload _registerTranscriberFinalTimeout]
+ GCC_except_table1656
+ GCC_except_table1762
+ GCC_except_table1777
+ GCC_except_table1789
+ GCC_except_table1799
+ GCC_except_table1804
+ GCC_except_table1821
+ GCC_except_table1825
+ GCC_except_table1834
+ GCC_except_table1849
+ GCC_except_table1922
+ GCC_except_table1926
+ GCC_except_table1986
+ GCC_except_table2021
+ GCC_except_table2087
+ GCC_except_table2099
+ GCC_except_table2108
+ GCC_except_table2119
+ GCC_except_table2129
+ GCC_except_table2148
+ OBJC_IVAR_$_CSVTUITrainingSessionWithPayload._awaitingTranscriberFinal
+ ___68-[CSVTUITrainingSessionWithPayload _registerTranscriberFinalTimeout]_block_invoke
+ _objc_msgSend$_deferCloseForTranscriberFinal
+ _objc_msgSend$_firedTranscriberFinalTimeout
+ _objc_msgSend$_registerTranscriberFinalTimeout
+ _objc_msgSend$hasLiveSpeechTranscriber
+ _objc_msgSend$hasUsableRecognizer
- GCC_except_table1652
- GCC_except_table1750
- GCC_except_table1771
- GCC_except_table1783
- GCC_except_table1793
- GCC_except_table1798
- GCC_except_table1815
- GCC_except_table1819
- GCC_except_table1828
- GCC_except_table1843
- GCC_except_table1916
- GCC_except_table1920
- GCC_except_table1980
- GCC_except_table2015
- GCC_except_table2081
- GCC_except_table2093
- GCC_except_table2102
- GCC_except_table2113
- GCC_except_table2123
- GCC_except_table2142
CStrings:
+ "%s Finalizing speech transcriber; awaiting final result"
+ "%s No usable recognizer; using no-SpeechAPI EOS timeout"
+ "%s Transcriber final result did not arrive; closing session"
+ "%s Using SpeechAPI EOS timeout"
+ "-[CSVTUITrainingSessionWithPayload _deferCloseForTranscriberFinal]"
+ "-[CSVTUITrainingSessionWithPayload _firedTranscriberFinalTimeout]"
+ "-[CSVTUITrainingSessionWithPayload _getSessionEOSTimeout]"
```
