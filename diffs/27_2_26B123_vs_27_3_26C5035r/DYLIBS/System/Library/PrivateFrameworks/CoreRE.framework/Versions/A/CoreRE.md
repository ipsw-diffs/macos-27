## CoreRE

> `/System/Library/PrivateFrameworks/CoreRE.framework/Versions/A/CoreRE`

```diff

-453.40.5.0.0
-  __TEXT.__text: 0x1814e68
-  __TEXT.__objc_methlist: 0x48f8
-  __TEXT.__const: 0x11e254
+453.60.1.0.1
+  __TEXT.__text: 0x1816e8c
+  __TEXT.__objc_methlist: 0x4910
+  __TEXT.__const: 0x11e0d4
   __TEXT.__constg_swiftt: 0x44
   __TEXT.__swift5_typeref: 0x2f
   __TEXT.__swift5_fieldmd: 0x44
   __TEXT.__swift5_reflstr: 0x1f
   __TEXT.__swift5_types: 0x8
-  __TEXT.__cstring: 0xcf494
-  __TEXT.__gcc_except_tab: 0xdfc8
-  __TEXT.__oslogstring: 0x573e0
+  __TEXT.__cstring: 0xcfa2d
+  __TEXT.__gcc_except_tab: 0xdf90
+  __TEXT.__oslogstring: 0x576e9
   __TEXT.__ustring: 0x1a
-  __TEXT.__unwind_info: 0x5d130
+  __TEXT.__unwind_info: 0x5d168
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xc838
+  __DATA_CONST.__const: 0xca38
   __DATA_CONST.__objc_classlist: 0x278
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x4f10
+  __DATA_CONST.__objc_selrefs: 0x4f28
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__objc_superrefs: 0x200
   __DATA_CONST.__objc_arraydata: 0x88
   __DATA_CONST.__got: 0x1228
-  __AUTH_CONST.__const: 0xae4c8
-  __AUTH_CONST.__cfstring: 0x144e0
-  __AUTH_CONST.__objc_const: 0x8e68
+  __AUTH_CONST.__const: 0xae550
+  __AUTH_CONST.__cfstring: 0x14520
+  __AUTH_CONST.__objc_const: 0x8ec8
   __AUTH_CONST.__weak_auth_got: 0x48
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__objc_arrayobj: 0x30

   __AUTH.__data: 0x18
   __AUTH.__thread_vars: 0xd8
   __AUTH.__thread_bss: 0x318
-  __DATA.__objc_ivar: 0x518
-  __DATA.__data: 0x22d09
-  __DATA.__bss: 0x71f0
-  __DATA.__common: 0x6d20
+  __DATA.__objc_ivar: 0x524
+  __DATA.__data: 0x23079
+  __DATA.__bss: 0x7200
+  __DATA.__common: 0x6d30
   __DATA_DIRTY.__objc_ivar: 0x130
   __DATA_DIRTY.__objc_data: 0x1540
   __DATA_DIRTY.__data: 0x8188
-  __DATA_DIRTY.__bss: 0x5f6b0
+  __DATA_DIRTY.__bss: 0x5f810
   __DATA_DIRTY.__common: 0x3a69
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/swift/libswiftObservation.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 93389
-  Symbols:   135031
-  CStrings:  26131
+  Functions: 93409
+  Symbols:   135070
+  CStrings:  26175
 
Symbols:
+ -[VideoSpillMapMetalSession configureGPU:withHeapPoolTable:withLibrary:]
+ -[VideoSpillMapMetalSession configureOnePassDiffuseLightSpillWeights:]
+ -[VideoSpillMapMetalSession generateSpillTextureOnePass:sourceTexture:intermediateWidth:intermediateHeight:protectionOptions:pipeline:withCommandBuffer:]
+ -[VideoSpillMapMetalSession init:withHeapPoolTable:withLibrary:]
+ GCC_except_table112
+ _OBJC_IVAR_$_VideoSpillMapMetalSession._onePassTapCount
+ _OBJC_IVAR_$_VideoSpillMapMetalSession._onePassTapStepInIntermediateTexels
+ _OBJC_IVAR_$_VideoSpillMapMetalSession._onePassTapWeights
+ _REMaterialAssetBuilderSetNeedsTransmission
+ __ZGVZN2re13VideoDefaults24lightSpillOnePassEnabledEvE5value
+ __ZGVZN2re19VideoTextureHandles13kEmptyHandlesEvE5empty
+ __ZN2re12SmallHashSetImLm10ENS_17PrecalculatedHashENS_7EqualToImEELb0EE3addERKm
+ __ZN2re13VideoDefaults24lightSpillOnePassEnabledEv
+ __ZN2re18VideoSpillMapMetal31computeSpillMapFromMetalTextureEN2NS9SharedPtrIN3MTL7TextureEEES5_hNS_3mtl13CommandBufferE
+ __ZN2re19VideoTextureHandles13kEmptyHandlesEv
+ __ZN2re20TransmissionProviderD0Ev
+ __ZN2re20TransmissionProviderD1Ev
+ __ZN2re21TransmissionFrameDataD0Ev
+ __ZN2re21TransmissionFrameDataD1Ev
+ __ZN2re24VideoLightSpillGenerator12setupSessionEiiiRKNS_3mtl6DeviceERNS_13HeapPoolTableERKNS1_7LibraryE
+ __ZN2re24VideoLightSpillGenerator26MakeOnePassDiffusePipelineERKNS_3mtl6DeviceERKNS1_7LibraryERKN2NS9SharedPtrIN3MTL13BinaryArchiveEEE
+ __ZN2re24VideoLightSpillGenerator6WarmUpERKNS_3mtl6DeviceERNS_13HeapPoolTableERKNS1_7LibraryE
+ __ZN2re24VideoLightSpillGeneratorD2Ev
+ __ZN2re28VideoLightSpillSessionCreateEPK13__CFAllocatorPK14__CFDictionaryPU19objcproto9MTLDevice11objc_objectRNS_13HeapPoolTableEPU21objcproto10MTLLibrary11objc_object
+ __ZN2re30initInfo_TransmissionFrameDataEPNS_17IntrospectionBaseE
+ __ZN2re31allocInfo_TransmissionFrameDataEv
+ __ZN2re32introspect_TransmissionFrameDataEb
+ __ZN2re4ecs214VideoComponent18processAttachmentsEPNS_13RenderManagerEdRKNS_19VideoTextureHandlesEjjPNS_17VideoColorManagerEbb
+ __ZN2re4ecs214VideoComponent36applyVideoAttachmentToParameterBlockEPNS0_6EntityERKNS0_23VideoMaterialAttachmentERKNS_19VideoTextureHandlesERNS_22MaterialParameterBlockERNS_8OptionalINS_21VideoProcessingParamsEEEjj
+ __ZN2re4ecs214VideoComponent48applyVideoTextureArrayAttachmentToParameterBlockEPNS0_6EntityERKNS0_23VideoMaterialAttachmentERKNS_19VideoTextureHandlesERNS_22MaterialParameterBlockE
+ __ZN2re8internal15defaultDestructINS_21TransmissionFrameDataEEEvRKNS_17IntrospectionBaseEPNS_20IntrospectionContextEPv
+ __ZN2re8internal16defaultConstructINS_21TransmissionFrameDataEEEvRKNS_17IntrospectionBaseEPNS_20IntrospectionContextEPv
+ __ZN2re8internal17defaultDestructV2INS_21TransmissionFrameDataEEEvPvRKNS_8TypeInfoEPNS_9AllocatorES3_
+ __ZN2re8internal18defaultConstructV2INS_21TransmissionFrameDataEEEvPvRKNS_8TypeInfoEPNS_9AllocatorES3_
+ __ZN2re8internal24introspectionInfoStorageINS_21TransmissionFrameDataEEE
+ __ZNK2re20TransmissionProvider12prepareFrameEPKcS2_RNS_11RenderFrameE
+ __ZNK2re20TransmissionProvider7provideEPKcS2_RNS_11RenderFrameE
+ __ZNK2re20VideoPixelBufferBase11displaySizeEv
+ __ZNK2re2sg25CachedCompilationMaterial18getHasTransmissionEv
+ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERZNK2re4ecs220VideoComponentSystem14updateInternalEPNS3_5SceneENS3_6System13UpdateContextEE3$_2PZNKS4_14updateInternalES6_S8_E14VideoAssetInfoLb0EEEvT1_SD_T0_NS_15iterator_traitsISD_E15difference_typeEb
+ __ZNSt3__127__insertion_sort_incompleteB9nqn220106INS_17_ClassicAlgPolicyERZNK2re4ecs220VideoComponentSystem14updateInternalEPNS3_5SceneENS3_6System13UpdateContextEE3$_2PZNKS4_14updateInternalES6_S8_E14VideoAssetInfoEEbT1_SD_T0_
+ __ZNSt3__17__sort3B9nqn220106INS_17_ClassicAlgPolicyERZNK2re4ecs220VideoComponentSystem14updateInternalEPNS3_5SceneENS3_6System13UpdateContextEE3$_2PZNKS4_14updateInternalES6_S8_E14VideoAssetInfoLi0EEEbT1_SD_SD_T0_
+ __ZNSt3__17__sort4B9nqn220106INS_17_ClassicAlgPolicyERZNK2re4ecs220VideoComponentSystem14updateInternalEPNS3_5SceneENS3_6System13UpdateContextEE3$_2PZNKS4_14updateInternalES6_S8_E14VideoAssetInfoLi0EEEvT1_SD_SD_SD_T0_
+ __ZNSt3__17__sort5B9nqn220106INS_17_ClassicAlgPolicyERZNK2re4ecs220VideoComponentSystem14updateInternalEPNS3_5SceneENS3_6System13UpdateContextEE3$_2PZNKS4_14updateInternalES6_S8_E14VideoAssetInfoLi0EEEvT1_SD_SD_SD_SD_T0_
+ __ZTIN2re20TransmissionProviderE
+ __ZTIN2re21TransmissionFrameDataE
+ __ZTSN2re20TransmissionProviderE
+ __ZTSN2re21TransmissionFrameDataE
+ __ZTVN2re20TransmissionProviderE
+ __ZTVN2re21TransmissionFrameDataE
+ __ZZN12_GLOBAL__N_133unifiedDeploymentTargetForReleaseEN2re19RealityFilePlatformENS0_17RealityKitReleaseEE24unifiedDeploymentTargets
+ __ZZN2re13VideoDefaults24lightSpillOnePassEnabledEvE5value
+ __ZZN2re19VideoTextureHandles13kEmptyHandlesEvE5empty
+ __ZZN2re24VideoLightSpillGenerator6WarmUpERKNS_3mtl6DeviceERNS_13HeapPoolTableERKNS1_7LibraryEE9onceToken
+ __ZZN2re4ecs214VideoComponent36applyVideoAttachmentToParameterBlockEPNS0_6EntityERKNS0_23VideoMaterialAttachmentERKNS_19VideoTextureHandlesERNS_22MaterialParameterBlockERNS_8OptionalINS_21VideoProcessingParamsEEEjjE23__FILE____LINE___logged
+ ____ZN2re24VideoLightSpillGenerator6WarmUpERKNS_3mtl6DeviceERNS_13HeapPoolTableERKNS1_7LibraryE_block_invoke
+ _objc_msgSend$configureGPU:withHeapPoolTable:withLibrary:
+ _objc_msgSend$configureOnePassDiffuseLightSpillWeights:
+ _objc_msgSend$generateSpillTextureOnePass:sourceTexture:intermediateWidth:intermediateHeight:protectionOptions:pipeline:withCommandBuffer:
+ _objc_msgSend$hasTransmission
+ _objc_msgSend$init:withHeapPoolTable:withLibrary:
+ _objc_msgSend$setsThinFilm
- -[VideoSpillMapMetalSession configureGPU:withHeapPoolTable:]
- -[VideoSpillMapMetalSession init:withHeapPoolTable:]
- __ZN2re19VideoTextureHandlesaSEOS0_
- __ZN2re24VideoLightSpillGenerator12setupSessionEiiiRKNS_3mtl6DeviceERNS_13HeapPoolTableE
- __ZN2re24VideoLightSpillGenerator6WarmUpERKNS_3mtl6DeviceERNS_13HeapPoolTableE
- __ZN2re28VideoLightSpillSessionCreateEPK13__CFAllocatorPK14__CFDictionaryPU19objcproto9MTLDevice11objc_objectRNS_13HeapPoolTableE
- __ZN2re4ecs214VideoComponent18processAttachmentsEPNS_13RenderManagerEdNS_19VideoTextureHandlesEjjPNS_17VideoColorManagerEbb
- __ZN2re4ecs214VideoComponent36applyVideoAttachmentToParameterBlockEPNS0_6EntityERKNS0_23VideoMaterialAttachmentERNS_19VideoTextureHandlesERNS_22MaterialParameterBlockERNS_8OptionalINS_21VideoProcessingParamsEEEjj
- __ZN2re4ecs214VideoComponent48applyVideoTextureArrayAttachmentToParameterBlockEPNS0_6EntityERKNS0_23VideoMaterialAttachmentERNS_19VideoTextureHandlesERNS_22MaterialParameterBlockE
- __ZNK2re10VideoAsset22getVideoTextureHandlesEv
- __ZNK2re10VideoAsset28getLegacyVideoTextureHandlesEv
- __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERZNK2re4ecs220VideoComponentSystem14updateInternalEPNS3_5SceneENS3_6System13UpdateContextEE3$_1PZNKS4_14updateInternalES6_S8_E14VideoAssetInfoLb0EEEvT1_SD_T0_NS_15iterator_traitsISD_E15difference_typeEb
- __ZNSt3__127__insertion_sort_incompleteB9nqn220106INS_17_ClassicAlgPolicyERZNK2re4ecs220VideoComponentSystem14updateInternalEPNS3_5SceneENS3_6System13UpdateContextEE3$_1PZNKS4_14updateInternalES6_S8_E14VideoAssetInfoEEbT1_SD_T0_
- __ZNSt3__17__sort3B9nqn220106INS_17_ClassicAlgPolicyERZNK2re4ecs220VideoComponentSystem14updateInternalEPNS3_5SceneENS3_6System13UpdateContextEE3$_1PZNKS4_14updateInternalES6_S8_E14VideoAssetInfoLi0EEEbT1_SD_SD_T0_
- __ZNSt3__17__sort4B9nqn220106INS_17_ClassicAlgPolicyERZNK2re4ecs220VideoComponentSystem14updateInternalEPNS3_5SceneENS3_6System13UpdateContextEE3$_1PZNKS4_14updateInternalES6_S8_E14VideoAssetInfoLi0EEEvT1_SD_SD_SD_T0_
- __ZNSt3__17__sort5B9nqn220106INS_17_ClassicAlgPolicyERZNK2re4ecs220VideoComponentSystem14updateInternalEPNS3_5SceneENS3_6System13UpdateContextEE3$_1PZNKS4_14updateInternalES6_S8_E14VideoAssetInfoLi0EEEvT1_SD_SD_SD_SD_T0_
- __ZZN12_GLOBAL__N_130tvOSDeploymentTargetForReleaseEN2re17RealityKitReleaseEE21tvOSDeploymentTargets
- __ZZN2re24VideoLightSpillGenerator6WarmUpERKNS_3mtl6DeviceERNS_13HeapPoolTableEE9onceToken
- __ZZN2re4ecs214VideoComponent36applyVideoAttachmentToParameterBlockEPNS0_6EntityERKNS0_23VideoMaterialAttachmentERNS_19VideoTextureHandlesERNS_22MaterialParameterBlockERNS_8OptionalINS_21VideoProcessingParamsEEEjjE23__FILE____LINE___logged
- ____ZN2re24VideoLightSpillGenerator6WarmUpERKNS_3mtl6DeviceERNS_13HeapPoolTableE_block_invoke
- _objc_msgSend$configureGPU:withHeapPoolTable:
- _objc_msgSend$init:withHeapPoolTable:
- _objc_msgSend$newDefaultLibraryWithBundle:error:
CStrings:
+ "<unnamed>"
+ "EnableThinFilm"
+ "EnableTransmission"
+ "HasTransmission"
+ "TransmissionFrameData"
+ "TransmissionProvider"
+ "Transmissive material \"%s\" has no Transparent pass technique; it will draw in the Opaque pass and transmission cannot be ordered correctly."
+ "[VideoLightSpillGenerator] [MakeOnePassDiffusePipeline] Failed: %@"
+ "[VideoLightSpillGenerator] [MakeOnePassDiffusePipeline] Max %lu threads per threadgroup, using MPS"
+ "[VideoLightSpillGenerator] [MakeOnePassDiffusePipeline] Not Metal 3 Apple7+, using MPS"
+ "[VideoLightSpillGenerator] [MakeOnePassDiffusePipeline] SIMD-group width %lu, using MPS"
+ "[VideoLightSpillGenerator] [MakeOnePassDiffusePipeline] Unable to find the kernel"
+ "[VideoLightSpillGenerator] [VideoSpillMapMetal::computeSpillMapFromMetalTextureOnePass] Unable to compute light spill"
+ "[VideoLightSpillGenerator] [VideoSpillMapMetal::computeSpillMapFromMetalTextureOnePass] Unable to create command buffer"
+ "[VideoLightSpillGenerator] [configureGPU] Unable to get metal library"
+ "layer1Enabled"
+ "layer2Enabled"
+ "layer3Enabled"
+ "layer4Enabled"
+ "layer5Enabled"
+ "needsTransmission"
+ "onePassDiffuseLightSpill"
+ "realitykit::surface_private::api::refraction_max_thickness"
+ "realitykit::surface_private::api::refraction_scale"
+ "realitykit::surface_private::api::refraction_thickness"
+ "realitykit::surface_private::api::set_refraction_max_thickness"
+ "realitykit::surface_private::api::set_refraction_scale"
+ "realitykit::surface_private::api::set_refraction_thickness"
+ "realitykit::surface_private::api::set_thin_film_ior"
+ "realitykit::surface_private::api::set_thin_film_thickness"
+ "realitykit::surface_private::api::set_thin_film_weight"
+ "realitykit::surface_private::api::set_transmission_color"
+ "realitykit::surface_private::api::set_transmission_depth"
+ "realitykit::surface_private::api::set_transmission_scatter"
+ "realitykit::surface_private::api::set_transmission_weight"
+ "realitykit::surface_private::api::thin_film_ior"
+ "realitykit::surface_private::api::thin_film_thickness"
+ "realitykit::surface_private::api::thin_film_weight"
+ "realitykit::surface_private::api::transmission_color"
+ "realitykit::surface_private::api::transmission_depth"
+ "realitykit::surface_private::api::transmission_scatter"
+ "realitykit::surface_private::api::transmission_weight"
+ "transmissionSliceIndex"
+ "transmissionSliceRunsToEnd"
+ "video.lightspill.one_pass.enabled"
- "[VideoLightSpillGenerator] [configureGPU] Unable to get metal library for bundle %@ error: %@"
```
