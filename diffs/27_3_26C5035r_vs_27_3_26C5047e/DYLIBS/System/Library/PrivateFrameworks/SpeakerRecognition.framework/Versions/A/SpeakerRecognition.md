## SpeakerRecognition

> `/System/Library/PrivateFrameworks/SpeakerRecognition.framework/Versions/A/SpeakerRecognition`

```diff

-3610.11.1.0.0
-  __TEXT.__text: 0xa3adc
-  __TEXT.__objc_methlist: 0x6c68
+3610.19.5.0.0
+  __TEXT.__text: 0xa550c
+  __TEXT.__objc_methlist: 0x6d70
   __TEXT.__const: 0xb58
-  __TEXT.__cstring: 0x107e6
+  __TEXT.__cstring: 0x10c66
   __TEXT.__swift5_typeref: 0x515
-  __TEXT.__oslogstring: 0xd516
+  __TEXT.__oslogstring: 0xd6f9
   __TEXT.__swift5_capture: 0x19c
   __TEXT.__constg_swiftt: 0x6a8
   __TEXT.__swift5_reflstr: 0x471

   __TEXT.__swift_as_cont: 0x74
   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_proto: 0x20
-  __TEXT.__gcc_except_tab: 0x2458
-  __TEXT.__unwind_info: 0x25e8
+  __TEXT.__gcc_except_tab: 0x246c
+  __TEXT.__unwind_info: 0x2648
   __TEXT.__eh_frame: 0x868
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x818
-  __DATA_CONST.__objc_classlist: 0x320
+  __DATA_CONST.__const: 0x820
+  __DATA_CONST.__objc_classlist: 0x328
   __DATA_CONST.__objc_catlist: 0x30
-  __DATA_CONST.__objc_protolist: 0x160
+  __DATA_CONST.__objc_protolist: 0x168
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3d20
-  __DATA_CONST.__objc_protorefs: 0x48
+  __DATA_CONST.__objc_selrefs: 0x3dc0
+  __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x228
-  __DATA_CONST.__objc_arraydata: 0x3c0
-  __DATA_CONST.__got: 0xb80
-  __AUTH_CONST.__const: 0x25e0
-  __AUTH_CONST.__cfstring: 0x5800
-  __AUTH_CONST.__objc_const: 0xb888
-  __AUTH_CONST.__objc_dictobj: 0x960
+  __DATA_CONST.__objc_arraydata: 0x3e0
+  __DATA_CONST.__got: 0xb88
+  __AUTH_CONST.__const: 0x26a0
+  __AUTH_CONST.__cfstring: 0x5920
+  __AUTH_CONST.__objc_const: 0xb988
+  __AUTH_CONST.__objc_dictobj: 0x9b0
   __AUTH_CONST.__objc_intobj: 0x1c8
   __AUTH_CONST.__objc_floatobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__auth_got: 0xde0
-  __AUTH.__objc_data: 0x1c8
+  __AUTH.__objc_data: 0x218
   __AUTH.__data: 0x90
-  __DATA.__objc_ivar: 0x858
-  __DATA.__data: 0x12e0
+  __DATA.__objc_ivar: 0x860
+  __DATA.__data: 0x1340
   __DATA.__bss: 0x4f8
   __DATA.__common: 0x60
   __DATA_DIRTY.__objc_data: 0x2440

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2926
-  Symbols:   6267
-  CStrings:  2523
+  Functions: 2948
+  Symbols:   6327
+  CStrings:  2550
 
Symbols:
+ +[SSRVoiceProfileEmbeddingTrainer _addSpeakerEmbedding:toProfile:withContext:]
+ +[SSRVoiceProfileEmbeddingTrainer _copyModelFile:toExclaveModelFile:ofProfile:]
+ +[SSRVoiceProfileEmbeddingTrainer _errorWithCode:reason:]
+ +[SSRVoiceProfileEmbeddingTrainer _seedScorer:withModelFile:embedding:dimensions:]
+ +[SSRVoiceProfileEmbeddingTrainer addSpeakerEmbedding:toProfile:withContext:error:]
+ -[CSVTUIAudioSessionRecorder setAudioRecordingSampleCount:]
+ -[SSRSpeakerAnalyzerPSR latestSpeakerVector]
+ -[SSRSpeakerRecognitionController fetchFinalEmbeddingWithCompletion:]
+ -[SSRSpeakerRecognitionOrchestrator fetchFinalEmbeddingWithCompletion:]
+ -[SSRSpeakerRecognizerPSR latestSpeakerVector]
+ -[SSRVTUITrainingManager _builtInVoiceTrigger]
+ -[SSRVTUITrainingManager _cancelEnrollmentVoiceTriggerWait]
+ -[SSRVTUITrainingManager _startAudioSessionAfterVoiceTrigger:forSession:]
+ -[SSRVoiceProfileManager extractEmbeddingFromSession:toProfile:withContext:withCompletion:]
+ -[SSRVoiceProfileStore addUserVoiceProfile:withSpeakerEmbedding:withContext:withCompletion:]
+ GCC_except_table1014
+ GCC_except_table1017
+ GCC_except_table1018
+ GCC_except_table1019
+ GCC_except_table1020
+ GCC_except_table1021
+ GCC_except_table1022
+ GCC_except_table1023
+ GCC_except_table1024
+ GCC_except_table1025
+ GCC_except_table1027
+ GCC_except_table1028
+ GCC_except_table1030
+ GCC_except_table1033
+ GCC_except_table1110
+ GCC_except_table1122
+ GCC_except_table1138
+ GCC_except_table1192
+ GCC_except_table1196
+ GCC_except_table1214
+ GCC_except_table1316
+ GCC_except_table1317
+ GCC_except_table1319
+ GCC_except_table1340
+ GCC_except_table1344
+ GCC_except_table1353
+ GCC_except_table1363
+ GCC_except_table1369
+ GCC_except_table1430
+ GCC_except_table1441
+ GCC_except_table1472
+ GCC_except_table1485
+ GCC_except_table1530
+ GCC_except_table1545
+ GCC_except_table1561
+ GCC_except_table1568
+ GCC_except_table1615
+ GCC_except_table1622
+ GCC_except_table1645
+ GCC_except_table1672
+ GCC_except_table1773
+ GCC_except_table1779
+ GCC_except_table1794
+ GCC_except_table1806
+ GCC_except_table1816
+ GCC_except_table1821
+ GCC_except_table183
+ GCC_except_table1838
+ GCC_except_table1842
+ GCC_except_table1851
+ GCC_except_table186
+ GCC_except_table1866
+ GCC_except_table188
+ GCC_except_table1942
+ GCC_except_table1946
+ GCC_except_table2006
+ GCC_except_table2041
+ GCC_except_table2108
+ GCC_except_table2129
+ GCC_except_table2142
+ GCC_except_table2152
+ GCC_except_table2171
+ GCC_except_table309
+ GCC_except_table330
+ GCC_except_table361
+ GCC_except_table369
+ GCC_except_table381
+ GCC_except_table386
+ GCC_except_table479
+ GCC_except_table537
+ GCC_except_table552
+ GCC_except_table565
+ GCC_except_table641
+ GCC_except_table650
+ GCC_except_table656
+ GCC_except_table726
+ GCC_except_table763
+ GCC_except_table791
+ GCC_except_table848
+ GCC_except_table891
+ GCC_except_table898
+ GCC_except_table928
+ GCC_except_table931
+ _OBJC_CLASS_$_SSRVoiceProfileEmbeddingTrainer
+ _OBJC_IVAR_$_CSVTUIAudioSessionRecorder._shouldUseRecordingStartSampleCount
+ _OBJC_IVAR_$_CSVTUIAudioSessionRecorder._startRecordingSampleCount
+ _OBJC_METACLASS_$_SSRVoiceProfileEmbeddingTrainer
+ _SSRVTUITrainingServiceEntitlement
+ __OBJC_$_CLASS_METHODS_SSRVoiceProfileEmbeddingTrainer
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSVoiceTriggerManagerProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SSRSpeakerRecognizer
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSVoiceTriggerManagerProviding
+ __OBJC_$_PROTOCOL_REFS_CSVoiceTriggerManagerProviding
+ __OBJC_CLASS_RO_$_SSRVoiceProfileEmbeddingTrainer
+ __OBJC_LABEL_PROTOCOL_$_CSVoiceTriggerManagerProviding
+ __OBJC_METACLASS_RO_$_SSRVoiceProfileEmbeddingTrainer
+ __OBJC_PROTOCOL_$_CSVoiceTriggerManagerProviding
+ __OBJC_PROTOCOL_REFERENCE_$_CSVoiceTriggerManagerProviding
+ ___71-[SSRSpeakerRecognitionOrchestrator fetchFinalEmbeddingWithCompletion:]_block_invoke
+ ___73-[SSRVTUITrainingManager _startAudioSessionAfterVoiceTrigger:forSession:]_block_invoke
+ ___73-[SSRVTUITrainingManager _startAudioSessionAfterVoiceTrigger:forSession:]_block_invoke_2
+ ___91-[SSRVoiceProfileManager extractEmbeddingFromSession:toProfile:withContext:withCompletion:]_block_invoke
+ ___92-[SSRVoiceProfileStore addUserVoiceProfile:withSpeakerEmbedding:withContext:withCompletion:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e37_v28?0"CSVTUITrainingResult"8B16^20l
+ ___block_descriptor_48_e8_32s40w_e23_v28?0B8Q12"NSError"20l
+ ___block_descriptor_56_e8_32s40s48bs_e16_v16?0"NSData"8l
+ ___block_descriptor_65_e8_32s40s48s_e5_v8?0l
+ _objc_msgSend$_addSpeakerEmbedding:toProfile:withContext:
+ _objc_msgSend$_builtInVoiceTrigger
+ _objc_msgSend$_cancelEnrollmentVoiceTriggerWait
+ _objc_msgSend$_copyModelFile:toExclaveModelFile:ofProfile:
+ _objc_msgSend$_errorWithCode:reason:
+ _objc_msgSend$_seedScorer:withModelFile:embedding:dimensions:
+ _objc_msgSend$_startAudioSessionAfterVoiceTrigger:forSession:
+ _objc_msgSend$addSpeakerEmbedding:toProfile:withContext:error:
+ _objc_msgSend$addUserVoiceProfile:withSpeakerEmbedding:withContext:withCompletion:
+ _objc_msgSend$awaitEnrollmentVoiceTriggerWithCompletion:
+ _objc_msgSend$beginEnrollmentForLocale:
+ _objc_msgSend$builtInVoiceTrigger
+ _objc_msgSend$cancelEnrollmentVoiceTriggerWait
+ _objc_msgSend$conformsToProtocol:
+ _objc_msgSend$endEnrollment
+ _objc_msgSend$fetchFinalEmbeddingWithCompletion:
+ _objc_msgSend$latestSpeakerVector
+ _objc_msgSend$setAudioRecordingSampleCount:
+ _objc_msgSend$setRequestHistoricalAudioDataSampleCount:
+ _objc_msgSend$setStartRecordingSampleCount:
- GCC_except_table1000
- GCC_except_table1001
- GCC_except_table1002
- GCC_except_table1003
- GCC_except_table1004
- GCC_except_table1005
- GCC_except_table1006
- GCC_except_table1007
- GCC_except_table1008
- GCC_except_table1013
- GCC_except_table1016
- GCC_except_table1093
- GCC_except_table1105
- GCC_except_table1121
- GCC_except_table1175
- GCC_except_table1179
- GCC_except_table1197
- GCC_except_table1299
- GCC_except_table1300
- GCC_except_table1302
- GCC_except_table1323
- GCC_except_table1327
- GCC_except_table1336
- GCC_except_table1346
- GCC_except_table1352
- GCC_except_table1407
- GCC_except_table1413
- GCC_except_table1455
- GCC_except_table1468
- GCC_except_table1513
- GCC_except_table1528
- GCC_except_table1544
- GCC_except_table1551
- GCC_except_table1598
- GCC_except_table1606
- GCC_except_table1629
- GCC_except_table1656
- GCC_except_table1757
- GCC_except_table1763
- GCC_except_table1778
- GCC_except_table1790
- GCC_except_table1800
- GCC_except_table1805
- GCC_except_table182
- GCC_except_table1822
- GCC_except_table1826
- GCC_except_table1835
- GCC_except_table185
- GCC_except_table1850
- GCC_except_table187
- GCC_except_table1923
- GCC_except_table1927
- GCC_except_table1987
- GCC_except_table2022
- GCC_except_table2088
- GCC_except_table2100
- GCC_except_table2109
- GCC_except_table2130
- GCC_except_table2149
- GCC_except_table307
- GCC_except_table326
- GCC_except_table357
- GCC_except_table365
- GCC_except_table377
- GCC_except_table382
- GCC_except_table475
- GCC_except_table529
- GCC_except_table548
- GCC_except_table561
- GCC_except_table637
- GCC_except_table646
- GCC_except_table648
- GCC_except_table751
- GCC_except_table780
- GCC_except_table832
- GCC_except_table874
- GCC_except_table881
- GCC_except_table911
- GCC_except_table914
- GCC_except_table993
- GCC_except_table994
- GCC_except_table997
CStrings:
+ "%s Audio provider selector does not provide a voice trigger, enrollment will not wait for a voice trigger"
+ "%s ERR: Failed to add speaker embedding to %{public}@ with error %{public}@"
+ "%s Exclave voice trigger detected, recording from sample count %llu"
+ "%s Exclave voice trigger was not detected : %{public}@"
+ "%s Live transcriber has text; finalizing at endpoint without EOS window"
+ "%s Setting start recording sample count to %llu"
+ "%s Waiting for the exclave voice trigger before recording"
+ "+[SSRVoiceProfileEmbeddingTrainer _errorWithCode:reason:]"
+ "-[CSVTUIAudioSessionRecorder setAudioRecordingSampleCount:]"
+ "-[SSRVTUITrainingManager _builtInVoiceTrigger]"
+ "-[SSRVTUITrainingManager _startAudioSessionAfterVoiceTrigger:forSession:]"
+ "-[SSRVTUITrainingManager _startAudioSessionAfterVoiceTrigger:forSession:]_block_invoke"
+ "-[SSRVTUITrainingManager _startAudioSessionAfterVoiceTrigger:forSession:]_block_invoke_2"
+ "-[SSRVoiceProfileManager extractEmbeddingFromSession:toProfile:withContext:withCompletion:]"
+ "-[SSRVoiceProfileManager extractEmbeddingFromSession:toProfile:withContext:withCompletion:]_block_invoke"
+ "-[SSRVoiceProfileStore addUserVoiceProfile:withSpeakerEmbedding:withContext:withCompletion:]_block_invoke"
+ "Cannot copy the model to %@: %@"
+ "Cannot create the scorer for the speaker embedding"
+ "Cannot reset the model for the speaker embedding"
+ "No PSR model context to add the speaker embedding to"
+ "No speaker recognition session to extract the embedding from"
+ "Speaker embedding is empty"
+ "Speaker embedding was not added to the model"
+ "The speaker recognition pass has no embedding"
+ "corespeech.uitrainingservice"
+ "v16@?0@\"NSData\"8"
+ "v28@?0B8Q12@\"NSError\"20"
```
