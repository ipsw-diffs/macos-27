## MediaAnalysisServices

> `/System/Library/PrivateFrameworks/MediaAnalysisServices.framework/Versions/A/MediaAnalysisServices`

```diff

-460.14.5.2.0
-  __TEXT.__text: 0x3fbbc
+470.4.2.0.0
+  __TEXT.__text: 0x3fbcc
   __TEXT.__objc_methlist: 0x4fd4
   __TEXT.__const: 0x100
-  __TEXT.__cstring: 0x3bbf
+  __TEXT.__cstring: 0x3bc0
   __TEXT.__gcc_except_tab: 0x455c
   __TEXT.__oslogstring: 0x2309
   __TEXT.__dlopen_cstrs: 0x417

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x280
+  __DATA_CONST.__const: 0x288
   __DATA_CONST.__objc_classlist: 0x430
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ +[MADTextInput csuTokenizerRevision] : 56 -> 52
~ -[MADImageEmbeddingRequest init] : 168 -> 172
~ -[MADTextTokenizationRequest init] : 124 -> 128
~ +[MADTextTokenizationRequest maxTokenSize] : 104 -> 108
~ -[MADService(Text) activeTextEmbeddingVersions:] : 356 -> 360
~ -[MADTextEmbeddingRequest init] : 140 -> 144
CStrings:
+ "SearchUnifiedEmbeddingMD10"
- "SearchUnifiedEmbeddingMD8"
```
