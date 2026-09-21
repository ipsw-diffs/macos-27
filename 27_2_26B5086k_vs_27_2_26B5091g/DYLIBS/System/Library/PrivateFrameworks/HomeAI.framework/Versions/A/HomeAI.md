## HomeAI

> `/System/Library/PrivateFrameworks/HomeAI.framework/Versions/A/HomeAI`

```diff

-381.0.0.0.0
-  __TEXT.__text: 0x18290c
+382.0.0.0.0
+  __TEXT.__text: 0x182ca0
   __TEXT.__init_offsets: 0x10
-  __TEXT.__objc_methlist: 0xa3d4
+  __TEXT.__objc_methlist: 0xa40c
   __TEXT.__const: 0x494d
-  __TEXT.__cstring: 0xda27
-  __TEXT.__gcc_except_tab: 0xc064
+  __TEXT.__cstring: 0xdb58
+  __TEXT.__gcc_except_tab: 0xc088
   __TEXT.__oslogstring: 0xddb2
   __TEXT.__swift5_typeref: 0x21
   __TEXT.__constg_swiftt: 0x28
   __TEXT.__swift5_reflstr: 0x74
   __TEXT.__swift5_fieldmd: 0x4c
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x5ae0
+  __TEXT.__unwind_info: 0x5ae8
   __TEXT.__eh_frame: 0x50
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xd70
+  __DATA_CONST.__const: 0xd78
   __DATA_CONST.__objc_classlist: 0x6f8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x4678
+  __DATA_CONST.__objc_selrefs: 0x46a0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x5f0
   __DATA_CONST.__objc_arraydata: 0x6e8
   __DATA_CONST.__got: 0xbc8
   __AUTH_CONST.__const: 0x79f0
-  __AUTH_CONST.__cfstring: 0x8820
-  __AUTH_CONST.__objc_const: 0x15db0
+  __AUTH_CONST.__cfstring: 0x8960
+  __AUTH_CONST.__objc_const: 0x15e10
   __AUTH_CONST.__weak_auth_got: 0x28
-  __AUTH_CONST.__objc_intobj: 0x570
+  __AUTH_CONST.__objc_intobj: 0x558
   __AUTH_CONST.__objc_arrayobj: 0x390
   __AUTH_CONST.__objc_doubleobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0x1b8

   __AUTH_CONST.__auth_got: 0xd50
   __AUTH.__objc_data: 0x4240
   __AUTH.__data: 0x350
-  __DATA.__objc_ivar: 0xd28
+  __DATA.__objc_ivar: 0xd30
   __DATA.__data: 0xd3c
   __DATA.__bss: 0x3f0
   __DATA_DIRTY.__objc_data: 0x370

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5495
-  Symbols:   12050
-  CStrings:  3119
+  Functions: 5502
+  Symbols:   12062
+  CStrings:  3129
 
Symbols:
+ +[NSError(HMIError) hmiErrorWithCode:reason:]
+ -[HMIVideoAnalyzerConfiguration fragmentBufferDuration]
+ -[HMIVideoAnalyzerConfiguration setFragmentBufferDuration:]
+ -[HMIVideoGenerativeAnalysisResult initWithRequestUUID:clipUUID:embeddingsByVersion:caption:histogramsByEventType:modelIdentifier:isHistogramDuplicate:isEmbeddingDuplicate:isDegraded:error:]
+ -[HMIVideoGenerativeAnalysisResult isDegraded]
+ OBJC_IVAR_$_HMIVideoAnalyzerConfiguration._fragmentBufferDuration
+ OBJC_IVAR_$_HMIVideoGenerativeAnalysisResult._isDegraded
+ _HMIFragmentBufferDurationKey
+ _objc_msgSend$fragmentBufferDuration
+ _objc_msgSend$initWithRequestUUID:clipUUID:embeddingsByVersion:caption:histogramsByEventType:modelIdentifier:isHistogramDuplicate:isEmbeddingDuplicate:isDegraded:error:
+ _objc_msgSend$isDegraded
+ _objc_msgSend$setFragmentBufferDuration:
CStrings:
+ "Caption flagged as no activity"
+ "Caption flagged as sensitive content"
+ "Caption flagged as unsafe content"
+ "Caption parsing failed"
+ "Fragment Buffer Duration"
+ "HMIErrorCodeCaptionNoActivity"
+ "HMIErrorCodeCaptionParsingFailed"
+ "HMIErrorCodeCaptionSensitiveContent"
+ "HMIErrorCodeCaptionUnsafeContent"
+ "Is Degraded"
+ "fragmentBufferDurationSeconds"
- "fragmentBufferSize"
```
