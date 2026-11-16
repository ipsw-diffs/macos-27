## SpeechRecognitionCore

> `/System/Library/PrivateFrameworks/SpeechRecognitionCore.framework/Versions/A/SpeechRecognitionCore`

```diff

-41.1.10.0.0
-  __TEXT.__text: 0x1c7d8
+41.1.13.0.0
+  __TEXT.__text: 0x1c988
   __TEXT.__objc_methlist: 0xe3c
   __TEXT.__cstring: 0x1a84
   __TEXT.__gcc_except_tab: 0x1000
   __TEXT.__const: 0x152
-  __TEXT.__ustring: 0x41a
-  __TEXT.__oslogstring: 0x10a2
+  __TEXT.__ustring: 0x422
+  __TEXT.__oslogstring: 0x114b
   __TEXT.__swift5_typeref: 0x28
   __TEXT.__swift5_fieldmd: 0x10
-  __TEXT.__unwind_info: 0xc98
+  __TEXT.__unwind_info: 0xcb0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_selrefs: 0xa58
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x70
-  __DATA_CONST.__objc_arraydata: 0xcd0
+  __DATA_CONST.__objc_arraydata: 0xce0
   __DATA_CONST.__got: 0x218
-  __AUTH_CONST.__const: 0x970
-  __AUTH_CONST.__cfstring: 0x2dc0
+  __AUTH_CONST.__const: 0x990
+  __AUTH_CONST.__cfstring: 0x2de0
   __AUTH_CONST.__objc_const: 0x1f88
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_dictobj: 0x1e0
   __AUTH_CONST.__objc_intobj: 0x48
-  __AUTH_CONST.__auth_got: 0x720
+  __AUTH_CONST.__auth_got: 0x728
   __AUTH.__objc_data: 0x5a0
   __AUTH.__data: 0x180
   __DATA.__objc_ivar: 0x18c
   __DATA.__data: 0x4a8
-  __DATA.__bss: 0x160
+  __DATA.__bss: 0x170
   __DATA.__common: 0x30
   - /System/Library/Frameworks/CoreAudio.framework/Versions/A/CoreAudio
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 672
-  Symbols:   1689
-  CStrings:  586
+  Functions: 674
+  Symbols:   1690
+  CStrings:  589
 
Symbols:
+ __os_log_error_impl
Functions:
~ +[SRDParsedCommandTemplate templateFromString:cacheIdentifiers:adlibIdentifiers:multiMatchIdentifiers:locale:] : 1012 -> 1044
~ +[SRDParsedCommandTemplate parseSegmentsFromString:identifierLookup:adlibSet:] : 876 -> 996
+ ___SRDLogGrammarMatching_block_invoke
~ -[SRDCommandMatcher _compileMatchingStrategiesForStrings] : 4036 -> 4216
+ +[SRDParsedCommandTemplate parseSegmentsFromString:identifierLookup:adlibSet:].cold.1
CStrings:
+ "Unknown placeholder '%{public}@', dropping it from the template"
+ "[%{public}@] Unknown placeholder '%{public}@' (locale %{public}@), dropping one of the command's strings"
+ "ıki"
```
