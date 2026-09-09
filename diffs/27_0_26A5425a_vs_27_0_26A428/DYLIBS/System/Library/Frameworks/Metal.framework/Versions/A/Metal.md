## Metal

> `/System/Library/Frameworks/Metal.framework/Versions/A/Metal`

```diff

 382.5.3.0.0
-  __TEXT.__text: 0x1f8be0
-  __TEXT.__objc_methlist: 0x1f844
-  __TEXT.__cstring: 0x23f0c
-  __TEXT.__gcc_except_tab: 0xc588
-  __TEXT.__const: 0x2d7b0
+  __TEXT.__text: 0x1fa6b8
+  __TEXT.__objc_methlist: 0x1fac4
+  __TEXT.__cstring: 0x2429f
+  __TEXT.__gcc_except_tab: 0xc590
+  __TEXT.__const: 0x2e750
   __TEXT.__oslogstring: 0x2400
   __TEXT.__ustring: 0x1be
-  __TEXT.__unwind_info: 0x8e20
+  __TEXT.__unwind_info: 0x8e10
   __TEXT.__eh_frame: 0x78
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0x490
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x9430
+  __DATA_CONST.__objc_selrefs: 0x94e8
   __DATA_CONST.__objc_protorefs: 0x68
   __DATA_CONST.__objc_superrefs: 0xc38
   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__got: 0xa68
   __AUTH_CONST.__const: 0x6ed8
-  __AUTH_CONST.__cfstring: 0x13640
-  __AUTH_CONST.__objc_const: 0x484a0
+  __AUTH_CONST.__cfstring: 0x137a0
+  __AUTH_CONST.__objc_const: 0x48808
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_intobj: 0x180
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0xef8
   __AUTH.__objc_data: 0x4420
-  __DATA.__objc_ivar: 0x2360
+  __DATA.__objc_ivar: 0x2388
   __DATA.__data: 0x4498
   __DATA.__bss: 0x3e4
   __DATA.__common: 0x40

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 13968
-  Symbols:   26254
-  CStrings:  4694
+  Functions: 14034
+  Symbols:   26355
+  CStrings:  4726
 
Symbols:
+ -[MTL4ComputePipelineDescriptor contentionRelief]
+ -[MTL4ComputePipelineDescriptor forwardProgressUsage]
+ -[MTL4ComputePipelineDescriptor optimizeForPersistentKernel]
+ -[MTL4ComputePipelineDescriptor setContentionRelief:]
+ -[MTL4ComputePipelineDescriptor setForwardProgressUsage:]
+ -[MTL4ComputePipelineDescriptor setOptimizeForPersistentKernel:]
+ -[MTLComputePipelineDescriptorInternal contentionRelief]
+ -[MTLComputePipelineDescriptorInternal forwardProgressUsage]
+ -[MTLComputePipelineDescriptorInternal optimizeForPersistentKernel]
+ -[MTLComputePipelineDescriptorInternal setContentionRelief:]
+ -[MTLComputePipelineDescriptorInternal setForwardProgressUsage:]
+ -[MTLComputePipelineDescriptorInternal setOptimizeForPersistentKernel:]
+ -[MTLDeviceFeatureQueries familySupportsAtomicWaitNotify]
+ -[MTLDeviceFeatureQueries familySupportsMXUNarrowTileSizes]
+ -[MTLDeviceFeatureQueries familySupportsPackUnpackSmallInteger]
+ -[MTLDeviceFeatureQueries familySupportsRGBTextureBuffers]
+ -[MTLDeviceFeatureQueries familySupportsSIMDGroupParallelForwardProgress]
+ -[MTLDeviceFeatureQueries familySupportsTextureViewMinLOD]
+ -[MTLDeviceFeatureQueries supportsAtomicWaitNotify]
+ -[MTLDeviceFeatureQueries supportsMXUNarrowTileSizes]
+ -[MTLDeviceFeatureQueries supportsPackUnpackSmallInteger]
+ -[MTLDeviceFeatureQueries supportsRGBTextureBuffers]
+ -[MTLDeviceFeatureQueries supportsSIMDGroupParallelForwardProgress]
+ -[MTLDeviceFeatureQueries supportsTextureViewMinLOD]
+ -[MTLShaderValidationConfiguration enableYieldChecks]
+ -[MTLShaderValidationConfiguration setEnableYieldChecks:]
+ -[MTLTextureViewDescriptor minLOD]
+ -[MTLTextureViewDescriptor setMinLOD:]
+ -[MTLTileRenderPipelineDescriptorInternal driverCompilerOptions]
+ -[MTLTileRenderPipelineDescriptorInternal setDriverCompilerOptions:]
+ -[_MTLComputePipelineState recommendedPersistentThreadgroupsPerGridForThreadsPerThreadgroup:]
+ -[_MTLDevice supportsAtomicWaitNotify]
+ -[_MTLDevice supportsMXUNarrowTileSizes]
+ -[_MTLDevice supportsPackUnpackSmallInteger]
+ -[_MTLDevice supportsRGBTextureBuffers]
+ -[_MTLDevice supportsSIMDGroupParallelForwardProgress]
+ -[_MTLDevice supportsTextureViewMinLOD]
+ -[_MTLDeviceFeatureQueries familySupportsAtomicWaitNotify]
+ -[_MTLDeviceFeatureQueries familySupportsMXUNarrowTileSizes]
+ -[_MTLDeviceFeatureQueries familySupportsPackUnpackSmallInteger]
+ -[_MTLDeviceFeatureQueries familySupportsRGBTextureBuffers]
+ -[_MTLDeviceFeatureQueries familySupportsSIMDGroupParallelForwardProgress]
+ -[_MTLDeviceFeatureQueries familySupportsTextureViewMinLOD]
+ -[_MTLResource minLOD]
+ GCC_except_table324
+ GCC_except_table339
+ GCC_except_table425
+ GCC_except_table445
+ GCC_except_table447
+ GCC_except_table458
+ GCC_except_table503
+ GCC_except_table507
+ GCC_except_table784
+ GCC_except_table785
+ GCC_except_table838
+ GCC_except_table840
+ GCC_except_table843
+ GCC_except_table845
+ GCC_except_table898
+ GCC_except_table902
+ GCC_except_table917
+ GCC_except_table918
+ GCC_except_table922
+ OBJC_IVAR_$_MTL4ComputePipelineDescriptor._contentionRelief
+ OBJC_IVAR_$_MTL4ComputePipelineDescriptor._forwardProgressUsage
+ OBJC_IVAR_$_MTL4ComputePipelineDescriptor._optimizeForPersistentKernel
+ OBJC_IVAR_$_MTLDeviceFeatureQueries._familySupportsAtomicWaitNotify
+ OBJC_IVAR_$_MTLDeviceFeatureQueries._familySupportsMXUNarrowTileSizes
+ OBJC_IVAR_$_MTLDeviceFeatureQueries._familySupportsPackUnpackSmallInteger
+ OBJC_IVAR_$_MTLDeviceFeatureQueries._familySupportsRGBTextureBuffers
+ OBJC_IVAR_$_MTLDeviceFeatureQueries._familySupportsSIMDGroupParallelForwardProgress
+ OBJC_IVAR_$_MTLDeviceFeatureQueries._familySupportsTextureViewMinLOD
+ OBJC_IVAR_$_MTLShaderValidationConfiguration._enableYieldChecks
+ __ZZ22MTLGetPackSintFunctionEN4$_128__invokeEPKiPv
+ __ZZ22MTLGetPackSintFunctionEN4$_138__invokeEPKiPv
+ __ZZ22MTLGetPackSintFunctionEN4$_148__invokeEPKiPv
+ __ZZ22MTLGetPackUintFunctionEN4$_148__invokeEPKjPv
+ __ZZ22MTLGetPackUintFunctionEN4$_158__invokeEPKjPv
+ __ZZ22MTLGetPackUintFunctionEN4$_168__invokeEPKjPv
+ __ZZ23MTLGetPackFloatFunctionEN4$_498__invokeEPKfPv
+ __ZZ23MTLGetPackFloatFunctionEN4$_508__invokeEPKfPv
+ __ZZ23MTLGetPackFloatFunctionEN4$_518__invokeEPKfPv
+ __ZZ23MTLGetPackFloatFunctionEN4$_528__invokeEPKfPv
+ __ZZ23MTLGetPackFloatFunctionEN4$_538__invokeEPKfPv
+ __ZZ23MTLGetPackFloatFunctionEN4$_548__invokeEPKfPv
+ __ZZ23MTLGetPackFloatFunctionEN4$_558__invokeEPKfPv
+ __ZZ24MTLGetUnpackSintFunctionEN4$_128__invokeEPKvPi
+ __ZZ24MTLGetUnpackSintFunctionEN4$_138__invokeEPKvPi
+ __ZZ24MTLGetUnpackSintFunctionEN4$_148__invokeEPKvPi
+ __ZZ24MTLGetUnpackUintFunctionEN4$_148__invokeEPKvPj
+ __ZZ24MTLGetUnpackUintFunctionEN4$_158__invokeEPKvPj
+ __ZZ24MTLGetUnpackUintFunctionEN4$_168__invokeEPKvPj
+ __ZZ25MTLGetUnpackFloatFunctionEN4$_498__invokeEPKvPf
+ __ZZ25MTLGetUnpackFloatFunctionEN4$_508__invokeEPKvPf
+ __ZZ25MTLGetUnpackFloatFunctionEN4$_518__invokeEPKvPf
+ __ZZ25MTLGetUnpackFloatFunctionEN4$_528__invokeEPKvPf
+ __ZZ25MTLGetUnpackFloatFunctionEN4$_538__invokeEPKvPf
+ __ZZ25MTLGetUnpackFloatFunctionEN4$_548__invokeEPKvPf
+ __ZZ25MTLGetUnpackFloatFunctionEN4$_558__invokeEPKvPf
+ _isRGBPixelFormat
+ _objc_msgSend$contentionRelief
+ _objc_msgSend$enableYieldChecks
+ _objc_msgSend$familySupportsAtomicWaitNotify
+ _objc_msgSend$familySupportsMXUNarrowTileSizes
+ _objc_msgSend$familySupportsPackUnpackSmallInteger
+ _objc_msgSend$familySupportsRGBTextureBuffers
+ _objc_msgSend$familySupportsSIMDGroupParallelForwardProgress
+ _objc_msgSend$familySupportsTextureViewMinLOD
+ _objc_msgSend$forwardProgressUsage
+ _objc_msgSend$minLOD
+ _objc_msgSend$optimizeForPersistentKernel
+ _objc_msgSend$setContentionRelief:
+ _objc_msgSend$setForwardProgressUsage:
+ _objc_msgSend$setMinLOD:
+ _objc_msgSend$setOptimizeForPersistentKernel:
+ _objc_msgSend$supportsAtomicWaitNotify
+ _objc_msgSend$supportsMXUNarrowTileSizes
+ _objc_msgSend$supportsPackUnpackSmallInteger
+ _objc_msgSend$supportsRGBTextureBuffers
+ _objc_msgSend$supportsSIMDGroupParallelForwardProgress
+ _objc_msgSend$supportsTextureViewMinLOD
- GCC_except_table318
- GCC_except_table333
- GCC_except_table396
- GCC_except_table399
- GCC_except_table406
- GCC_except_table419
- GCC_except_table441
- GCC_except_table452
- GCC_except_table489
- GCC_except_table502
- GCC_except_table506
- GCC_except_table778
- GCC_except_table779
- GCC_except_table782
- GCC_except_table834
- GCC_except_table837
- GCC_except_table839
- GCC_except_table905
- GCC_except_table912
- GCC_except_table916
CStrings:
+ "-[_MTLComputePipelineState recommendedPersistentThreadgroupsPerGridForThreadsPerThreadgroup:]"
+ "23:04:37"
+ "Atomic Wait and Notify"
+ "Aug  9 2026"
+ "Aug  9 2026 23:04:37"
+ "ForwardProgressUsageFnAttr"
+ "MTLGPUFamilyApple11"
+ "MTLPixelFormatRGB16Bfloat"
+ "MTLPixelFormatRGB16Float"
+ "MTLPixelFormatRGB16Sint"
+ "MTLPixelFormatRGB16Snorm"
+ "MTLPixelFormatRGB16Uint"
+ "MTLPixelFormatRGB16Unorm"
+ "MTLPixelFormatRGB32Float"
+ "MTLPixelFormatRGB32Sint"
+ "MTLPixelFormatRGB32Uint"
+ "MTLPixelFormatRGB8Sint"
+ "MTLPixelFormatRGB8Snorm"
+ "MTLPixelFormatRGB8Uint"
+ "MTLPixelFormatRGB8Unorm"
+ "MXU Narrow Tile Sizes, 8x16 and 16x8"
+ "Pack and unpack support of 16b integers"
+ "PersistentFnAttr"
+ "RGB Pixel Formats for Texture Buffers"
+ "SIMDgroup Parallel Forward Progress"
+ "Texture View Min LOD"
+ "applegpu_g17d"
+ "applegpu_g18g"
+ "applegpu_g18m"
+ "applegpu_g19p"
+ "contentionRelief ="
+ "enable-yield-check"
+ "forwardProgressUsage ="
+ "optimizeForPersistentKernel ="
+ "recommendedPersistentThreadgroupsPerGridForThreadsPerThreadgroup must be overridden by the driver."
- "01:00:42"
- "Aug 10 2026"
- "Aug 10 2026 01:00:42"
```
