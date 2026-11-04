## CoreRoutineDiagnostics

> `/System/Library/PrivateFrameworks/CoreRoutineDiagnostics.framework/Versions/A/CoreRoutineDiagnostics`

```diff

-1123.0.3.0.0
-  __TEXT.__text: 0xf720
-  __TEXT.__objc_methlist: 0xabc
+1123.0.6.0.0
+  __TEXT.__text: 0xf734
+  __TEXT.__objc_methlist: 0xac4
   __TEXT.__dlopen_cstrs: 0x6d
   __TEXT.__const: 0x178
   __TEXT.__gcc_except_tab: 0x3b4
   __TEXT.__oslogstring: 0x1b79
-  __TEXT.__cstring: 0x17d6
+  __TEXT.__cstring: 0x1804
   __TEXT.__ustring: 0x7c
-  __TEXT.__unwind_info: 0x478
+  __TEXT.__unwind_info: 0x470
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8c0
+  __DATA_CONST.__objc_selrefs: 0x8c8
   __DATA_CONST.__objc_superrefs: 0x48
   __DATA_CONST.__got: 0x178
   __AUTH_CONST.__const: 0x3c0
-  __AUTH_CONST.__cfstring: 0x18e0
+  __AUTH_CONST.__cfstring: 0x1900
   __AUTH_CONST.__objc_const: 0xed8
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_intobj: 0x120

   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 285
-  Symbols:   870
-  CStrings:  362
+  Functions: 284
+  Symbols:   871
+  CStrings:  363
 
Symbols:
+ -[RTBugCaptureManager _generateRadarDescriptionForReason:diagnosticsMask:additionalDescription:]
+ -[RTBugCaptureManager captureBugForReason:module:category:diagnosticsMask:additionalDescription:handler:]
+ GCC_except_table27
+ GCC_except_table31
+ GCC_except_table46
+ GCC_except_table5
+ GCC_except_table50
+ ___105-[RTBugCaptureManager captureBugForReason:module:category:diagnosticsMask:additionalDescription:handler:]_block_invoke
+ ___105-[RTBugCaptureManager captureBugForReason:module:category:diagnosticsMask:additionalDescription:handler:]_block_invoke_2
+ ___block_descriptor_112_e8_32s40s48s56s64s72s80bs88r_e17_v16?0"NSArray"8l
+ ___block_descriptor_88_e8_32s40s48s56s64bs_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s64s72s80b88r
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88r
+ _objc_msgSend$_generateRadarDescriptionForReason:diagnosticsMask:additionalDescription:
+ _objc_msgSend$captureBugForReason:module:category:diagnosticsMask:additionalDescription:handler:
- -[RTBugCaptureManager _generateRadarDescriptionForReason:diagnosticsMask:]
- GCC_except_table28
- GCC_except_table32
- GCC_except_table47
- GCC_except_table51
- ___83-[RTBugCaptureManager captureBugForReason:module:category:diagnosticsMask:handler:]_block_invoke
- ___83-[RTBugCaptureManager captureBugForReason:module:category:diagnosticsMask:handler:]_block_invoke_2
- ___block_descriptor_104_e8_32s40s48s56s64s72bs80r_e17_v16?0"NSArray"8l
- ___block_descriptor_80_e8_32s40s48s56bs_e5_v8?0l
- ___copy_helper_block_e8_32s40s48s56b
- ___copy_helper_block_e8_32s40s48s56s64s72b80r
- ___destroy_helper_block_e8_32s40s48s56s
- ___destroy_helper_block_e8_32s40s48s56s64s72s80r
- _objc_msgSend$_generateRadarDescriptionForReason:diagnosticsMask:
CStrings:
+ "-[RTBugCaptureManager captureBugForReason:module:category:diagnosticsMask:additionalDescription:handler:]"
+ "Diagnostic Detail:\n%@\n\n"
- "-[RTBugCaptureManager captureBugForReason:module:category:diagnosticsMask:handler:]"
```
