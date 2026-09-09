## FontValidator

> `/System/Library/Frameworks/ApplicationServices.framework/Versions/Current/Frameworks/ATS.framework/Versions/Current/Support/FontValidator`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 601.0.0.0.0
-  __TEXT.__text: 0x12754
+  __TEXT.__text: 0x12510
   __TEXT.__auth_stubs: 0xc20
   __TEXT.__objc_stubs: 0xc00
   __TEXT.__init_offsets: 0x4

   __TEXT.__objc_methname: 0xb01
   __TEXT.__objc_classname: 0x51
   __TEXT.__objc_methtype: 0xdf
-  __TEXT.__unwind_info: 0x4d0
+  __TEXT.__unwind_info: 0x508
   __DATA_CONST.__const: 0xe60
   __DATA_CONST.__cfstring: 0x2ec0
   __DATA_CONST.__objc_classlist: 0x28
Functions:
~ __ZNSt3__16vectorIcNS_9allocatorIcEEE6resizeEm : 284 -> 268
~ __ZL13SignalHandleri : 60 -> 48
~ __ZL18FontValidatorTimerP16__CFRunLoopTimerPv : 40 -> 28
~ _HighLevelAPITestsCT : 132 -> 120
~ _RenderString : 668 -> 656
~ __ZL37CTFontCreateWithFontDescriptorProcPtrPK18__CTFontDescriptordPK17CGAffineTransform : 76 -> 64
~ __ZNSt3__117__call_once_proxyB9nqn220106INS_5tupleIJOZN13AppleMetadata13GetPrivateKeyEvEUlvE_EEEEEvPv : 188 -> 176
~ _OUTLINED_FUNCTION_0 : 28 -> 16
~ _GetEnvironmentVariable : 96 -> 84
~ _CopyATSDefaultPref : 132 -> 120
~ +[ProcessURLInfo processURLInfo:expandCarFiles:] : 328 -> 316
~ -[ProcessURLInfo processURLInfo:] : 124 -> 112
~ -[ProcessURLInfo rootAsset] : 100 -> 88
~ -[ProcessURLInfo .cxx_destruct] : 104 -> 92
~ _ValidateFontFile : 444 -> 432
~ ___ValidateFontFile_block_invoke : 396 -> 384
~ __ZL14ProcessFileURLP14ProcessURLInfoji : 3024 -> 3012
~ +[FontValidatorResults withError:] : 84 -> 72
~ +[FontValidatorResults withError:reports:] : 124 -> 112
~ _FontValidatorCore : 4628 -> 4616
~ __ZL22AbsolutePathFromStringPKcbPb : 448 -> 436
~ ___FontValidatorCore_block_invoke : 356 -> 344
~ ___copy_helper_block_ea8_32s40r48r56r : 104 -> 92
~ ___destroy_helper_block_ea8_32s40r48r56r : 88 -> 76
~ ___copy_helper_block_ea8_32s40b : 72 -> 60
~ ___destroy_helper_block_ea8_32s40s : 60 -> 48
~ +[FVValidationFont validationFontWithDict:] : 272 -> 260
~ +[FVValidationFont validationFontsWithArray:] : 428 -> 416
~ -[FVValidationFont .cxx_destruct] : 92 -> 80
~ +[FVReportValidation validationWithDict:] : 284 -> 272
~ +[FVReport report:] : 480 -> 468
~ +[FVReport validateURL:options:outputType:] : 136 -> 124
~ +[FVReport validateWithArguments:] : 780 -> 768
~ -[FVReport .cxx_destruct] : 104 -> 92
~ __ZL11CarUtilPathv : 68 -> 56
~ __ZL21GetSimplifiedCTReportP14ProcessURLInfoP12NSDictionaryji : 4068 -> 4056
~ ____ZL20ProcessUniqueTempDirbP8NSString_block_invoke : 132 -> 120
~ __ZL20CreateUniqueTemDirAtP8NSString : 372 -> 360
~ _GLOBAL__sub_I_FontValidatorCore.m : 80 -> 68
~ __ZN5woff214WOFF2StringOut5WriteEPKvmm : 196 -> 192
~ __ZN5woff214WOFF2MemoryOut5WriteEPKvmm : 112 -> 108
~ __ZNSt3__16vectorIhNS_9allocatorIhEEE24__emplace_back_slow_pathIJhEEEPhDpOT_ : 220 -> 216
~ __ZNSt3__16vectorIN5woff25TableENS_9allocatorIS2_EEE6resizeEm : 372 -> 360
~ __ZNSt3__16vectorItNS_9allocatorItEEE6resizeEm : 280 -> 264
~ __ZNSt3__16vectorIN5woff212_GLOBAL__N_113WOFF2FontInfoENS_9allocatorIS3_EEE6resizeEm : 604 -> 588
~ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERNS_6__lessIvvEEPN5woff25TableELb0EEEvT1_S8_T0_NS_15iterator_traitsIS8_E15difference_typeEb : 3200 -> 3164
~ __ZNSt3__16vectorIPN5woff25TableENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJS3_EEEPS3_DpOT_ : 208 -> 204
~ __ZNSt3__16vectorIjNS_9allocatorIjEEE24__emplace_back_slow_pathIJRKjEEEPjDpOT_ : 208 -> 204
~ _OUTLINED_FUNCTION_1 : 20 -> 28
~ _OUTLINED_FUNCTION_2 : 28 -> 20
~ _OUTLINED_FUNCTION_4 : 28 -> 12
~ _OUTLINED_FUNCTION_5 : 12 -> 28
~ HighLevelTest.cold.1 : 160 -> 148
~ __ZN5woff217ConvertWOFF2ToTTFEPKhmPNS_8WOFF2OutE : 9336 -> 9340
```
