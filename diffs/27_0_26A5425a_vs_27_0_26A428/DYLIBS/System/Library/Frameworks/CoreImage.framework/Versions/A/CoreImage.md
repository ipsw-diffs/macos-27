## CoreImage

> `/System/Library/Frameworks/CoreImage.framework/Versions/A/CoreImage`

```diff

 1667.21.2.0.0
-  __TEXT.__text: 0x352aa4
-  __TEXT.__objc_methlist: 0x16050
+  __TEXT.__text: 0x352bcc
+  __TEXT.__objc_methlist: 0x16078
   __TEXT.__const: 0xe268
   __TEXT.__gcc_except_tab: 0xaa58
   __TEXT.__cstring: 0x105a08

   __TEXT.__cikl2metal_pre: 0x54b
   __TEXT.__grain: 0x105040
   __TEXT.__cruft: 0x36d1
-  __TEXT.__unwind_info: 0xaab8
+  __TEXT.__unwind_info: 0xaab0
   __TEXT.__eh_frame: 0x350
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9080
+  __DATA_CONST.__objc_selrefs: 0x9098
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x3a0
   __DATA_CONST.__objc_arraydata: 0x1478
   __DATA_CONST.__got: 0xb38
   __AUTH_CONST.__const: 0x10440
   __AUTH_CONST.__cfstring: 0x1de40
-  __AUTH_CONST.__objc_const: 0x2bdb8
+  __AUTH_CONST.__objc_const: 0x2bdf0
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0xde0
   __AUTH_CONST.__objc_dictobj: 0x3e8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 15316
+  Functions: 15314
   Symbols:   29336
   CStrings:  9009
 
Functions:
~ __ZNK2CI8TileTask15pixelsOverdrawnEv : 1176 -> 1180
~ __ZN2CIL37RemoveFromStartUntilAtOrBelowCapacityEv : 720 -> 724
~ __ZN2CI11GraphObject18traverse_stoppableEPS0_S1_iiU13block_pointerFbS1_S1_iiEU13block_pointerFvS1_S1_iiE : 656 -> 660
~ __ZNK2CI21SoftwareDAGDescriptor7executeEPNS_26SWRendererFunctionArgumentE6CGRectPKNS_13BitmapSamplerE : 756 -> 784
~ __ZN2CI9DAGHelper17add_function_infoEPKNS_11ProgramNodeEPKNS_17GeneralKernelNodeEPNS_20SerialObjectPtrArrayEmmNS_11OtherDigestEPchRm : 3100 -> 3116
~ __ZNK2CI18SWRendererPipeline16execute_scanlineEPKNS_26SWRendererFunctionArgumentEPNS_24SWRendererFunctionOutputEmP10SamplerObjPviii : 408 -> 412
~ ___36-[CIAreaHistogram outputImageNonMPS]_block_invoke_2 : 1292 -> 1296
~ +[TiledHistogram processWithInputs:arguments:output:error:] : 580 -> 588
~ ___35-[CIAreaHoughTransform outputImage]_block_invoke : 376 -> 384
~ -[CIContext(_createCGImageInternal) _createCGImage:fromRect:format:premultiplied:colorSpace:deferred:renderCallback:] : 5960 -> 5968
~ __122-[CIContext(ImageRepresentation) _CMPhotoRepresentationOfImage:depth:allowAlpha:containerFormat:colorSpace:options:error:]_block_invoke.230 : 244 -> 248
~ -[CIContext(CIDepthBlurEffect) _performFaceDetection:image:orientation:filter:] : 1568 -> 1572
~ __ZN2CI20sw_convolutionrgb7x7ERKNS_22SWRendererFunctionNodeEPKNS_26SWRendererFunctionArgumentEPKNS_24SWRendererFunctionOutputEP10SamplerObjPvRK6IPointm : 4632 -> 4648
~ __ZN2CI17sw_convolution7x7ERKNS_22SWRendererFunctionNodeEPKNS_26SWRendererFunctionArgumentEPKNS_24SWRendererFunctionOutputEP10SamplerObjPvRK6IPointm : 4632 -> 4640
- _OUTLINED_FUNCTION_8
~ __ZN2CI21sw_faceMaskCalculatorERKNS_22SWRendererFunctionNodeEPKNS_26SWRendererFunctionArgumentEPKNS_24SWRendererFunctionOutputEP10SamplerObjPvRK6IPointm : 1252 -> 1260
~ __ZN2CI16sw_gaussianBlur7ERKNS_22SWRendererFunctionNodeEPKNS_26SWRendererFunctionArgumentEPKNS_24SWRendererFunctionOutputEP10SamplerObjPvRK6IPointm : 416 -> 412
~ __ZN16CIKLLibraryMaker9tokenizerEPKcP7__sFILEU13block_pointerFvS1_itS3_E : 420 -> 428
~ __ZN2CI24sw_raw_dm_interleaveRGGBERKNS_22SWRendererFunctionNodeEPKNS_26SWRendererFunctionArgumentEPKNS_24SWRendererFunctionOutputEP10SamplerObjPvRK6IPointm : 288 -> 292
~ __ZN2CI9sw_mesh16ERKNS_22SWRendererFunctionNodeEPKNS_26SWRendererFunctionArgumentEPKNS_24SWRendererFunctionOutputEP10SamplerObjPvRK6IPointm : 2612 -> 2620
~ __ZN2CI9sw_mesh32ERKNS_22SWRendererFunctionNodeEPKNS_26SWRendererFunctionArgumentEPKNS_24SWRendererFunctionOutputEP10SamplerObjPvRK6IPointm : 5068 -> 5092
~ __ZL17CriticalPointsDOD6CGRect17CGAffineTransformP7CGPoint : 244 -> 256
~ __ZL11pageCurlROIi6CGRect17CGAffineTransformS0_S0_S_S_ : 1052 -> 1080
~ __ZN2CI31sw_pageCurlWithShadowTransitionERKNS_22SWRendererFunctionNodeEPKNS_26SWRendererFunctionArgumentEPKNS_24SWRendererFunctionOutputEP10SamplerObjPvRK6IPointm : 1888 -> 1900
~ __ZN2CI23sw_planarToInterleaved3ERKNS_22SWRendererFunctionNodeEPKNS_26SWRendererFunctionArgumentEPKNS_24SWRendererFunctionOutputEP10SamplerObjPvRK6IPointm : 364 -> 360
~ __ZN2CI23sw_planarToInterleaved4ERKNS_22SWRendererFunctionNodeEPKNS_26SWRendererFunctionArgumentEPKNS_24SWRendererFunctionOutputEP10SamplerObjPvRK6IPointm : 428 -> 424
~ -[CITemperatureAndTint setInputNeutral:] : 1988 -> 1992
~ _ConvertYCbCrtoREDEYEFORMAT : 1532 -> 1516
~ -[CIRedEyeRepair3(CIRedEyeRepair3Analyze) magnitudeMap:fromGabor:] : 136 -> 144
~ -[CIRedEyeRepair3(CIRedEyeRepair3Analyze) renderConvexHull:distance:fieldToBitmap:] : 1368 -> 1356
~ -[CIRedEyeRepair3(CIRedEyeRepair3Analyze) analyzeMask:usingConvexHull:producingOptimizedMask:] : 2112 -> 2116
~ -[CIRedEyeRepair3(CIRedEyeRepair3Analyze) attemptClosureOfThreadIndex:] : 1332 -> 1336
~ -[CIRedEyeRepair3(CIRedEyeRepair3Analyze) prominenceConvexHull:facts:] : 2724 -> 2736
~ _computeBitmask : 5628 -> 5644
~ _redEyeCancellation : 1960 -> 2000
~ _whiteEyeCancellation : 3524 -> 3556
~ _cornealReflectionBitmask : 1260 -> 1252
~ _infillChannelWithBitmask : 5308 -> 5312
~ _computePupilAlphaMap : 3908 -> 3920
~ _computeOutlineByTracingSnake : 3828 -> 3820
~ _computeBorderForAlpha : 928 -> 916
~ _minEnergyHopperInsert : 152 -> 156
~ -[CIRedEyeRepair redEyeRemovalWithPoint:alignPupilShades:matching:force:IOD:tap:] : 4124 -> 4172
~ ___getBytesAtPositionCallback_YCbYCr_block_invoke : 212 -> 216
~ ___getBytesAtPositionCallback_CbYCrY_block_invoke : 216 -> 220
~ ___getBytesAtPositionCallback_YCbYCrFull_block_invoke : 268 -> 272
~ ___getBytesAtPositionCallback_CbYCrYFull_block_invoke : 272 -> 276
~ ___getBytesAtPositionCallback_2C08_block_invoke : 76 -> 80
~ ___getBytesAtPositionCallback_1C08_block_invoke : 76 -> 80
~ ___getBytesAtPositionCallback_1C08_lut_block_invoke : 232 -> 236
~ ___getBytesAtPositionCallback_A008_block_invoke : 72 -> 76
~ _CI_xy_to_TempTint : 328 -> 332
~ __ZNSt3__16vectorIN2CI7TextureENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJS2_EEEPS2_DpOT_ : 284 -> 288
~ __ZN2CI7Context16recursive_renderEPKNS_17RenderDestinationEPNS_8TileTaskERKNS_6roiKeyEPKNS_4NodeEb : 5964 -> 5960
~ __ZN2CIL20convert_ycch_to_420pEmm13vImage_BufferS0_S0_xx : 664 -> 656
~ __ZN2CIL20convert_ycch_to_444nEhmm13vImage_BufferS0_S0_xx : 424 -> 436
~ __ZN2CIL18convert_ycc_to_420IDF16_EEvmm13vImage_BufferS1_S1_xx : 376 -> 388
~ __block_invoke : 692 -> 696
~ __ZN2CI14MetalDAGHelper17add_function_infoEPKNS_11ProgramNodeEPKNS_17GeneralKernelNodeEPNS_20SerialObjectPtrArrayEmmNS_11OtherDigestEPchRmh : 5976 -> 5980
- __ZNSt3__16vectorINS_4pairIiiEENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJS2_EEEPS2_DpOT_
~ __ZN2CI13TileCacheNode20getIntersectingTilesEPNS_8TileableE6CGRect : 648 -> 652
~ __ZNSt3__16vectorIbNS_9allocatorIbEEE18__construct_at_endIPbS5_EEvT_T0_m : 196 -> 204
~ ____ZN2CIL26get_converter_roi_callbackEPNS_4NodeENS_13ConvertReasonE_block_invoke : 768 -> 772
~ __ZNSt3__16vectorI6CGRectNS_9allocatorIS1_EEE18__insert_with_sizeB9nqn220106INS_17_ClassicAlgPolicyENS_11__wrap_iterIPKS1_EESA_EENS7_IPS1_EESA_T0_T1_l : 516 -> 532
~ __ZN2CI11GraphObject18traverse_stoppableEPKS0_S2_iiU13block_pointerFbS2_S2_iiEU13block_pointerFvS2_S2_iiE : 656 -> 660
~ __ZN2CIL22subdivide_program_roisEPNS_7ContextEPNS_4NodeE6CGRectPNSt3__13mapIPKS2_NS_13useCountDepthENS5_4lessIS8_EENS5_9allocatorINS5_4pairIKS8_S9_EEEEEEbRKNS5_6vectorIS8_NSC_IS8_EEEERNS5_5dequeIPKNS_11ProgramNodeENSC_ISR_EEEERSL_Rm : 5104 -> 5124
~ __ZNSt3__15dequeIPKN2CI11ProgramNodeENS_9allocatorIS4_EEE19__add_back_capacityEv : 468 -> 472
~ __ZNSt3__114__split_bufferIPPKN2CI11ProgramNodeENS_9allocatorIS5_EEE12emplace_backIJRS5_EEEvDpOT_ : 256 -> 260
~ __ZNSt3__114__split_bufferIPPKN2CI11ProgramNodeERNS_9allocatorIS5_EEE12emplace_backIJS5_EEEvDpOT_ : 256 -> 260
~ __ZNSt3__16vectorI6CGRectNS_9allocatorIS1_EEE18__insert_with_sizeB9nqn220106INS_17_ClassicAlgPolicyENS_11__wrap_iterIPS1_EES9_EES9_NS7_IPKS1_EET0_T1_l : 492 -> 508
~ __ZNSt3__15dequeIPN2CI17SurfaceCacheEntryENS_9allocatorIS3_EEE19__add_back_capacityEv : 372 -> 376
~ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERZZNK2CI8TileTask15pixelsOverdrawnEvENK3$_0clERKNS_6vectorI6CGRectNS_9allocatorIS6_EEEEEUlNS_4pairIdiEESD_E_PSD_Lb0EEEvT1_SH_T0_NS_15iterator_traitsISH_E15difference_typeEb : 2976 -> 2980
~ __ZNSt3__16vectorINS_10unique_ptrIN2CI8TileTaskENS2_13ObjectDeleterIS3_EEEENS_9allocatorIS6_EEE24__emplace_back_slow_pathIJS6_EEEPS6_DpOT_ : 224 -> 228
~ -[CIDualRedEyeRepairSession validateSetPrimary].cold.5 : 88 -> 80
~ -[CIDualRedEyeRepairSession redEyeFaceFromObservation:exifOrientation:].cold.1 : 64 -> 68
~ -[CIDualRedEyeRepairSession redEyeFaceFromObservation:exifOrientation:].cold.2 : 64 -> 68
~ -[CIDualRedEyeRepairSession redEyeFaceFromObservation:exifOrientation:].cold.3 : 84 -> 88
~ -[CIDualRedEyeRepairSession setPrimary:observations:metadata:].cold.2 : 72 -> 76
~ -[CIKernelLibrary initWithSource:error:].cold.2 : 80 -> 76
~ +[CIKernelLibrary(Internal) internalBinaryArchiveWithName:device:].cold.1 : 76 -> 84
~ +[CIKernelLibrary(Internal) internalBinaryArchiveWithName:device:].cold.2 : 108 -> 104
~ ___ZL37addSpecializedFunctionToBinaryArchiveP21MTLFunctionDescriptorPU21objcproto10MTLLibrary11objc_object_block_invoke.cold.1 : 80 -> 88
```
