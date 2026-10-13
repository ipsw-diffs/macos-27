## MediaAnalysis

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/Versions/A/MediaAnalysis`

```diff

-460.12.1.0.0
-  __TEXT.__text: 0x4c4154
+460.14.5.1.0
+  __TEXT.__text: 0x4c4374
   __TEXT.__delay_helper: 0x1e0
-  __TEXT.__objc_methlist: 0x225e8
-  __TEXT.__const: 0x16458
-  __TEXT.__gcc_except_tab: 0x638a0
-  __TEXT.__cstring: 0x2f4b6
-  __TEXT.__oslogstring: 0x3189b
+  __TEXT.__objc_methlist: 0x22608
+  __TEXT.__const: 0x16488
+  __TEXT.__gcc_except_tab: 0x638dc
+  __TEXT.__cstring: 0x2f4f6
+  __TEXT.__oslogstring: 0x318db
   __TEXT.__dlopen_cstrs: 0x3c6
   __TEXT.__ustring: 0x40
   __TEXT.__swift5_typeref: 0x960

   __TEXT.__swift_as_ret: 0x84
   __TEXT.__swift_as_cont: 0xc4
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x17cd8
+  __TEXT.__unwind_info: 0x17ce0
   __TEXT.__eh_frame: 0x1830
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x40f8
+  __DATA_CONST.__const: 0x4100
   __DATA_CONST.__objc_classlist: 0x15a0
   __DATA_CONST.__objc_catlist: 0x1d0
   __DATA_CONST.__objc_protolist: 0x130
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0xeb68
+  __DATA_CONST.__objc_selrefs: 0xeb70
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0xf88
-  __DATA_CONST.__objc_arraydata: 0xe68
+  __DATA_CONST.__objc_arraydata: 0xe88
   __DATA_CONST.__got: 0x22d0
   __AUTH_CONST.__const: 0xabc8
   __AUTH_CONST.__cfstring: 0x1dc00
-  __AUTH_CONST.__objc_const: 0x40ad8
+  __AUTH_CONST.__objc_const: 0x40ae8
   __AUTH_CONST.__weak_auth_got: 0x70
   __AUTH_CONST.__objc_floatobj: 0x300
-  __AUTH_CONST.__objc_arrayobj: 0xba0
+  __AUTH_CONST.__objc_arrayobj: 0xbb8
   __AUTH_CONST.__objc_doubleobj: 0x240
-  __AUTH_CONST.__objc_intobj: 0x36a8
+  __AUTH_CONST.__objc_intobj: 0x36c0
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__auth_got: 0x2288
   __AUTH.__objc_data: 0xf0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 19694
-  Symbols:   34785
-  CStrings:  8742
+  Functions: 19697
+  Symbols:   34789
+  CStrings:  8743
 
Symbols:
+ -[MADServicePhotosVideoAsset isPhotosAsset]
+ -[MADServiceVideoAsset isPhotosAsset]
+ -[MADServiceVideoSafetyProcessingTask storeSafetyClassificationResults]
+ __ZL17shapeElementCountP7NSArrayIP8NSNumberE
+ _objc_msgSend$isPhotosAsset
+ _objc_msgSend$storeSafetyClassificationResults
- -[MADServiceVideoSafetyProcessingTask storeSafetyClassificationResultsForSharedAsset]
- _objc_msgSend$storeSafetyClassificationResultsForSharedAsset
Functions:
~ +[VCPMADImageEmbeddingTask bridgeEmbeddingTypeForRequest:] : 156 -> 168
~ -[VCPMADImageEmbeddingTask run] : 4136 -> 4332
+ __ZL17shapeElementCountP7NSArrayIP8NSNumberE
+ -[MADServicePhotosVideoAsset isPhotosAsset]
+ -[MADServiceVideoAsset videoSensitivityAnalysisVersion]
~ __ZNKSt3__114default_deleteIN13sentencepiece4util6Status3RepEEclB9nqe220106EPS4_ : 100 -> 108
CStrings:
+ "Failed to generate MADImageEmbeddingResult: expected shape %@ (%lu fp16 elements), got %lu elements"
+ "VCPMADImageEmbeddingTask expected shape %@ (%lu fp16 elements) but got %lu elements"
+ "[%@] Failed to obtain analysis result for Photos asset."
- "Failed to generate MADImageEmbeddingResult"
- "[%@] Failed to obtain analysis result for shared Photos asset."
```
