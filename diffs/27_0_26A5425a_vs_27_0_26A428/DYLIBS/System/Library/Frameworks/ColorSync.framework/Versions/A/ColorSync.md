## ColorSync

> `/System/Library/Frameworks/ColorSync.framework/Versions/A/ColorSync`

```diff

 3929.0.0.0.0
-  __TEXT.__text: 0x81720
+  __TEXT.__text: 0x81814
   __TEXT.__const: 0x123132
   __TEXT.__cstring: 0x96aa
   __TEXT.__oslogstring: 0xb

   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_proto: 0x4
-  __TEXT.__unwind_info: 0x1ca0
+  __TEXT.__unwind_info: 0x1ca8
   __TEXT.__eh_frame: 0x790
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
Functions:
~ _ColorSyncProfileCreateWithName : 252 -> 268
~ _ColorSyncCreateSignatureFromFourCharCode : 220 -> 236
~ __ZN12CMMInvMatrixC2ERA3_P9CMMXYZTagRA3_i : 376 -> 384
~ __ZNK9CMMMatrix5IsNOPEv : 240 -> 244
~ __ZNK9CMMMatrix18IsFloatingPointNOPEv : 192 -> 196
~ _ColorSyncTransformIteratorCreate : 4640 -> 4648
~ __ZN23CMMFloatBitNChanDecoder8DoDecodeERK12CMMFloatBitsP14CMMRuntimeInfom : 636 -> 640
~ __ZN18CMMDecoderTemplateI17CMM16BitNChanDataE13InnerDoDecodeI10CMMMaxBitsEEvRKT_RKNS4_13CMMBufferTypeEm : 744 -> 748
~ _decode_headroom_adaptive_gain_curve_data : 2208 -> 2176
~ _ColorSyncCreateOutputPoppyProfileForRGBData : 1832 -> 1844
~ __create_colorsync_transform_steps_info_block_invoke.24 : 360 -> 352
~ __ZN23CMMFloatBitNChanEncoder12EncodeSampleERA3072_fmm : 380 -> 392
~ __ZN19CMMFloatAlphaCopier4CopyEm : 292 -> 304
~ __ZNK10CMMConvTRC12ConvertFloatER12CMMFloatBitsmmb : 2380 -> 2392
~ __ZN9CMMMatrix16InitializeMatrixER10CMM3x3TypeRA3_P9CMMXYZTagf : 572 -> 580
~ __ZN9CMMMatrix19InitializeRGBMatrixERKS_S1_f : 692 -> 696
~ __ZNK11CMMConvNMCL13FindMinDeltaEEiii : 268 -> 272
~ __ZN17ConversionManager19AddLegacyLutTagConvEP15CMMLegacyLutTag17CMMColorSpaceTypeS2_b17CMMConversionTypePK14__CFDictionary : 1208 -> 1200
~ __Z27RoundTripBlackPointEstimateRA256_ffff : 1144 -> 1148
~ __ZN16CMMNamedColorTag15GetLabColorDataER9CMMMemMgr : 536 -> 540
~ __ZN18CMMEncoderTemplateI17CMM10Bit3ChanDataE13InnerDoEncodeI10CMMMaxBitsEEvRKT_RNS4_13CMMBufferTypeEPmS9_ : 484 -> 492
~ __ZN18CMMEncoderTemplateI26CMM16Bit1ChanAlphaPMulDataE13InnerDoEncodeI10CMMMaxBitsEEvRKT_RNS4_13CMMBufferTypeEPmS9_ : 536 -> 544
~ __ZN18CMMEncoderTemplateI26CMM16Bit3ChanAlphaPMulDataE13InnerDoEncodeI10CMMMaxBitsEEvRKT_RNS4_13CMMBufferTypeEPmS9_ : 708 -> 716
~ __ZN18CMMEncoderTemplateI17CMM32Bit1ChanDataE13InnerDoEncodeI10CMMMaxBitsEEvRKT_RNS4_13CMMBufferTypeEPmS9_ : 388 -> 396
~ __ZN18CMMDecoderTemplateI17CMM10Bit3ChanDataE13InnerDoDecodeI10CMMMaxBitsEEvRKT_RKNS4_13CMMBufferTypeEm : 404 -> 408
~ __ZN18CMMDecoderTemplateI26CMM16Bit1ChanAlphaPMulDataE13InnerDoDecodeI10CMMMaxBitsEEvRKT_RKNS4_13CMMBufferTypeEm : 508 -> 512
~ __ZN18CMMDecoderTemplateI26CMM16Bit3ChanAlphaPMulDataE13InnerDoDecodeI10CMMMaxBitsEEvRKT_RKNS4_13CMMBufferTypeEm : 700 -> 704
~ __ZN18CMMDecoderTemplateI17CMM32Bit1ChanDataE13InnerDoDecodeI10CMMMaxBitsEEvRKT_RKNS4_13CMMBufferTypeEm : 312 -> 316
~ __ZNK12CMMTrilinearI14CMMCLUTMOutputI9CMMCLUT3DEE11InterpolateI10CMMMaxBitsEEvRT_RNS6_13CMMBufferTypeEmm : 1108 -> 1112
~ __ZNK13CMMQuadlinearI14CMMCLUT3OutputI9CMMCLUT4DEE11InterpolateI10CMMMaxBitsEEvRT_RNS6_13CMMBufferTypeEmm : 1576 -> 1536
~ __ZNK13CMMQuadlinearI14CMMCLUT4OutputI9CMMCLUT4DEE11InterpolateI10CMMMaxBitsEEvRT_RNS6_13CMMBufferTypeEmm : 1352 -> 1356
~ __ZNK13CMMQuadlinearI14CMMCLUTMOutputI9CMMCLUT4DEE11InterpolateI10CMMMaxBitsEEvRT_RNS6_13CMMBufferTypeEmm : 1968 -> 1976
~ __ZNK13CMMNDimLinearI14CMMCLUTMOutputI9CMMCLUTnDEE11InterpolateI10CMMMaxBitsEEvRT_RNS6_13CMMBufferTypeEmm : 592 -> 600
~ __ZN20CMM16Bit1ChanEncoder13InnerDoEncodeERK10CMMMaxBitsR12CMMMaxBufferPmS5_ : 400 -> 408
~ __ZN20CMM16Bit3ChanEncoder13InnerDoEncodeERK10CMMMaxBitsR12CMMMaxBufferPmS5_ : 528 -> 544
~ __ZN20CMM16Bit4ChanEncoder13InnerDoEncodeERK10CMMMaxBitsR12CMMMaxBufferPmS5_ : 564 -> 572
~ __ZN20CMM16Bit1ChanDecoder13InnerDoDecodeERK10CMMMaxBitsRK12CMMMaxBufferm : 328 -> 340
~ __ZN20CMM16Bit3ChanDecoder13InnerDoDecodeERK10CMMMaxBitsRK12CMMMaxBufferm : 404 -> 416
~ __ZN20CMM16Bit4ChanDecoder13InnerDoDecodeERK10CMMMaxBitsRK12CMMMaxBufferm : 348 -> 352
~ __ZN19CMM1BitGamutDecoder13InnerDoDecodeI10CMMMaxBitsEEvRKT_RKNS2_13CMMBufferTypeEm : 372 -> 376
~ __ZNK17CMMConvNDimLookup6LookupI10CMMMaxBitsEEvRT_RNS2_13CMMBufferTypeEjj : 344 -> 348
~ _CreateMonoCS : 2868 -> 2876
~ _CreateDEFGLabCS : 3612 -> 3644
~ _CreateDEFGXYZCS : 2972 -> 2984
~ __ColorSyncProfileMakeLCopyWithFlexGTCBasedLUT_block_invoke.7 : 668 -> 672
```
