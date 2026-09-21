## CoreEmbeddedSpeechRecognition

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/Versions/A/CoreEmbeddedSpeechRecognition`

```diff

-3605.10.1.0.0
-  __TEXT.__text: 0x328b78
-  __TEXT.__objc_methlist: 0x4ce8
-  __TEXT.__const: 0x8b68
-  __TEXT.__cstring: 0xddf8
+3605.12.1.0.0
+  __TEXT.__text: 0x32aeec
+  __TEXT.__objc_methlist: 0x4d10
+  __TEXT.__const: 0x8b78
+  __TEXT.__cstring: 0xde58
   __TEXT.__gcc_except_tab: 0xd64
-  __TEXT.__oslogstring: 0xc845
+  __TEXT.__oslogstring: 0xc8a5
   __TEXT.__ustring: 0x4
   __TEXT.__dlopen_cstrs: 0xdc
-  __TEXT.__swift5_typeref: 0x420a
+  __TEXT.__swift5_typeref: 0x4202
   __TEXT.__constg_swiftt: 0x27b4
   __TEXT.__swift5_reflstr: 0x2b93
   __TEXT.__swift5_fieldmd: 0x28d8

   __TEXT.__swift5_assocty: 0x4f8
   __TEXT.__swift5_proto: 0x4d4
   __TEXT.__swift5_types: 0x2a8
-  __TEXT.__swift5_capture: 0xc5ec
+  __TEXT.__swift5_capture: 0xc63c
   __TEXT.__swift5_protos: 0x20
   __TEXT.__swift_as_entry: 0x260
   __TEXT.__swift_as_ret: 0x2c4
   __TEXT.__swift_as_cont: 0x6ac
   __TEXT.__swift5_mpenum: 0x18
-  __TEXT.__unwind_info: 0xb1d0
+  __TEXT.__unwind_info: 0xb1f0
   __TEXT.__eh_frame: 0x5b70
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xa00
+  __DATA_CONST.__const: 0xa08
   __DATA_CONST.__objc_classlist: 0x440
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x170
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3638
+  __DATA_CONST.__objc_selrefs: 0x3650
   __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_superrefs: 0x210
   __DATA_CONST.__objc_arraydata: 0x478
-  __DATA_CONST.__got: 0x1a10
-  __AUTH_CONST.__const: 0x23d98
-  __AUTH_CONST.__cfstring: 0x4ca0
-  __AUTH_CONST.__objc_const: 0xb840
+  __DATA_CONST.__got: 0x19f0
+  __AUTH_CONST.__const: 0x23e60
+  __AUTH_CONST.__cfstring: 0x4d00
+  __AUTH_CONST.__objc_const: 0xb898
   __AUTH_CONST.__objc_intobj: 0xeb8
   __AUTH_CONST.__objc_arrayobj: 0x2a0
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x21d0
-  __AUTH.__objc_data: 0x12b8
-  __AUTH.__data: 0xd98
-  __DATA.__objc_ivar: 0x520
-  __DATA.__data: 0x2660
-  __DATA.__bss: 0x5888
+  __AUTH_CONST.__auth_got: 0x21c8
+  __AUTH.__objc_data: 0x1128
+  __AUTH.__data: 0xb60
+  __DATA.__objc_ivar: 0x528
+  __DATA.__data: 0x24c0
+  __DATA.__bss: 0x5758
   __DATA.__common: 0x108
-  __DATA_DIRTY.__objc_data: 0x1b28
-  __DATA_DIRTY.__data: 0x3b50
-  __DATA_DIRTY.__bss: 0x3f00
+  __DATA_DIRTY.__objc_data: 0x1cb8
+  __DATA_DIRTY.__data: 0x3f98
+  __DATA_DIRTY.__bss: 0x4030
   __DATA_DIRTY.__common: 0x178
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11036
-  Symbols:   6327
-  CStrings:  2387
+  Functions: 11046
+  Symbols:   6333
+  CStrings:  2391
 
Symbols:
+ -[CESRSpeechParameters initWithLanguage:requestIdentifier:dictationUIInteractionIdentifier:task:loggingContext:applicationName:profile:overrides:modelOverrideURL:originalAudioFileURL:codec:narrowband:detectUtterances:censorSpeech:farField:secureOfflineOnly:shouldStoreAudioOnDevice:continuousListening:shouldHandleCapitalization:isSpeechAPIRequest:maximumRecognitionDuration:endpointStart:inputOrigin:location:jitGrammar:deliverEagerPackage:disableDeliveringAsrFeatures:enableEmojiRecognition:enableAutoPunctuation:enableVoiceCommands:disableEagerLimit:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:recognitionStart:shouldGenerateVoiceCommandCandidates:asrId:activeUserInfo:messagesContext:sessionIdentifier:applicationProcessIdentifier:isAudioSourceRemote:]
+ -[CESRSpeechParameters isAudioSourceRemote]
+ -[CESRSpeechParameters(InterfaceCompatibility) initWithLanguage:requestIdentifier:dictationUIInteractionIdentifier:task:loggingContext:applicationName:profile:overrides:modelOverrideURL:originalAudioFileURL:codec:narrowband:detectUtterances:censorSpeech:farField:secureOfflineOnly:shouldStoreAudioOnDevice:continuousListening:shouldHandleCapitalization:isSpeechAPIRequest:maximumRecognitionDuration:endpointStart:inputOrigin:location:jitGrammar:deliverEagerPackage:disableDeliveringAsrFeatures:enableEmojiRecognition:enableAutoPunctuation:enableVoiceCommands:disableEagerLimit:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:recognitionStart:shouldGenerateVoiceCommandCandidates:asrId:activeUserInfo:messagesContext:sessionIdentifier:applicationProcessIdentifier:]
+ -[_CESRSpeechParametersMutation setIsAudioSourceRemote:]
+ OBJC_IVAR_$_CESRSpeechParameters._isAudioSourceRemote
+ OBJC_IVAR_$__CESRSpeechParametersMutation._isAudioSourceRemote
+ _objc_msgSend$initWithLanguage:requestIdentifier:dictationUIInteractionIdentifier:task:loggingContext:applicationName:profile:overrides:modelOverrideURL:originalAudioFileURL:codec:narrowband:detectUtterances:censorSpeech:farField:secureOfflineOnly:shouldStoreAudioOnDevice:continuousListening:shouldHandleCapitalization:isSpeechAPIRequest:maximumRecognitionDuration:endpointStart:inputOrigin:location:jitGrammar:deliverEagerPackage:disableDeliveringAsrFeatures:enableEmojiRecognition:enableAutoPunctuation:enableVoiceCommands:disableEagerLimit:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:recognitionStart:shouldGenerateVoiceCommandCandidates:asrId:activeUserInfo:messagesContext:sessionIdentifier:applicationProcessIdentifier:isAudioSourceRemote:
+ _objc_msgSend$isAudioSourceRemote
- -[CESRSpeechParameters initWithLanguage:requestIdentifier:dictationUIInteractionIdentifier:task:loggingContext:applicationName:profile:overrides:modelOverrideURL:originalAudioFileURL:codec:narrowband:detectUtterances:censorSpeech:farField:secureOfflineOnly:shouldStoreAudioOnDevice:continuousListening:shouldHandleCapitalization:isSpeechAPIRequest:maximumRecognitionDuration:endpointStart:inputOrigin:location:jitGrammar:deliverEagerPackage:disableDeliveringAsrFeatures:enableEmojiRecognition:enableAutoPunctuation:enableVoiceCommands:disableEagerLimit:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:recognitionStart:shouldGenerateVoiceCommandCandidates:asrId:activeUserInfo:messagesContext:sessionIdentifier:applicationProcessIdentifier:]
- _symbolic _____Sg 6Speech26FoundationModelTranscriberC15ReportingOptionO
CStrings:
+ "CESRSpeechParameters::isAudioSourceRemote"
+ "Skipping on-screen context entity retrieval — audio source is remote for requestId %s"
+ "isAudioSourceRemote"
+ "isAudioSourceRemote = %@"
```
