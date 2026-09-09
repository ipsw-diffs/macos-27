## CompositorServicesPostProcess

> `/System/Library/Frameworks/CompositorServices.framework/Versions/A/XPCServices/CompositorServicesPostProcess.xpc/Contents/MacOS/CompositorServicesPostProcess`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 467.0.8.0.0
-  __TEXT.__text: 0x820c
+  __TEXT.__text: 0x8080
   __TEXT.__auth_stubs: 0x730
   __TEXT.__objc_stubs: 0x10e0
   __TEXT.__objc_methlist: 0x34c

   __TEXT.__swift5_types: 0x8
   __TEXT.__cstring: 0x6fc
   __TEXT.__oslogstring: 0x23a
-  __TEXT.__unwind_info: 0x178
+  __TEXT.__unwind_info: 0x1c0
   __DATA_CONST.__const: 0x2b0
   __DATA_CONST.__cfstring: 0x300
   __DATA_CONST.__objc_classlist: 0x30
Functions:
~ -[CPPPClientLayer invalidate] : 64 -> 52
~ -[CPPPClientLayer remoteLayer] : 44 -> 32
~ ___59-[CompositorServicesPostProcessService initWithConnection:]_block_invoke : 64 -> 52
~ __59-[CompositorServicesPostProcessService initWithConnection:]_block_invoke.89 : 64 -> 52
~ -[CompositorServicesPostProcessService sendBoostWithReply:] : 108 -> 96
~ ___136-[CompositorServicesPostProcessService newPostProcessServiceForLayerUID:configuration:swapchain:recorderSwapchain:channelRequest:reply:]_block_invoke : 64 -> 52
~ ___136-[CompositorServicesPostProcessService newPostProcessServiceForLayerUID:configuration:swapchain:recorderSwapchain:channelRequest:reply:]_block_invoke_2 : 64 -> 52
~ __136-[CompositorServicesPostProcessService newPostProcessServiceForLayerUID:configuration:swapchain:recorderSwapchain:channelRequest:reply:]_block_invoke.113 : 364 -> 352
~ ___copy_helper_block_8_32r40r48r56r64r72r : 144 -> 132
~ ___destroy_helper_block_8_32r40r48r56r64r72r : 116 -> 104
~ ___copy_helper_block_8_32r40w : 76 -> 64
~ ___destroy_helper_block_8_32r40w : 64 -> 52
~ __136-[CompositorServicesPostProcessService newPostProcessServiceForLayerUID:configuration:swapchain:recorderSwapchain:channelRequest:reply:]_block_invoke.126 : 100 -> 88
~ -[CompositorServicesPostProcessService invalidate] : 340 -> 328
~ -[CompositorServicesPostProcessService _initServicesWithConfiguration:device:library:binaryArchives:] : 284 -> 272
~ -[CompositorServicesPostProcessService stageRecorderSwapchain:completionHandler:] : 232 -> 220
~ -[CompositorServicesPostProcessService .cxx_destruct] : 224 -> 212
~ -[HoverEffectsRenderer updateAnimationWith:frame:hitTrackingArea:] : 1436 -> 1424
~ -[HoverEffectsRenderer .cxx_destruct] : 140 -> 128
~ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERZ66-[HoverEffectsRenderer updateAnimationWith:frame:hitTrackingArea:]E3$_1P15HoverEffectAreaLb0EEEvT1_S6_T0_NS_15iterator_traitsIS6_E15difference_typeEb : 5684 -> 5672
~ -[TrackingAreasNISCopy onPresent:chainlink:postProcessService:commandBuffer:gazeViewport:] : 2276 -> 2280
~ -[TrackingAreasNISCopy .cxx_destruct] : 128 -> 116
~ ___cp_pp_log_block_invoke : 72 -> 60
~ _$s20ComponentPostProcess0bC18MetalBinaryArchiveC29makeNISCopyPipelineDescriptor7library8archives7options20isClientRemoteServer11layerLayout6hasVRRSo010MTLComputeiJ0CSo10MTLLibrary_p_SaySo09MTLBinaryF0_pGSo18MTLFunctionOptionsVSbSiSbtFZTo : 176 -> 164
~ _$s20ComponentPostProcess0bC18MetalBinaryArchiveC34makeHoverEffectsPipelineDescriptor7library8archives7options16colorPixelFormat11layerLayout9glowCount15useTextureArraySo09MTLRenderjK0CSo10MTLLibrary_p_SaySo09MTLBinaryF0_pGSo18MTLFunctionOptionsVSo08MTLPixelQ0VS2iSbtFZTo : 192 -> 180
~ _$s20ComponentPostProcess0bC18MetalBinaryArchiveCACycfC : 44 -> 32
~ _new_texture_descriptor : 120 -> 108
~ _metal_device_get : 104 -> 80
~ ___metal_device_get_block_invoke : 56 -> 44
~ _new_billed_vm_page_backed_buffer : 412 -> 400
~ _get_binary_archives : 952 -> 940
~ ___get_binary_archives_block_invoke : 64 -> 52
~ _wb_residency_set_add_allocation_and_commit : 364 -> 352
~ _rt_cpu_accessible_texture_create_from_descriptor_with_alignment : 632 -> 628
```
