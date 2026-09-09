## MetalTools

> `/System/Library/PrivateFrameworks/MetalTools.framework/Versions/A/MetalTools`

```diff

 382.5.3.0.0
-  __TEXT.__text: 0x14f184
-  __TEXT.__objc_methlist: 0x1b29c
+  __TEXT.__text: 0x14ff24
+  __TEXT.__objc_methlist: 0x1b37c
   __TEXT.__gcc_except_tab: 0x32e8
-  __TEXT.__cstring: 0x3643f
-  __TEXT.__const: 0x5b0
+  __TEXT.__cstring: 0x365f8
+  __TEXT.__const: 0x630
   __TEXT.__oslogstring: 0x28d1
-  __TEXT.__unwind_info: 0x5938
+  __TEXT.__unwind_info: 0x5950
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_protolist: 0x508
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x6e10
+  __DATA_CONST.__objc_selrefs: 0x6e68
   __DATA_CONST.__objc_protorefs: 0xa0
   __DATA_CONST.__objc_superrefs: 0x6c0
   __DATA_CONST.__got: 0xbe0
   __AUTH_CONST.__const: 0x1150
-  __AUTH_CONST.__cfstring: 0xfc60
-  __AUTH_CONST.__objc_const: 0x4b350
+  __AUTH_CONST.__cfstring: 0xfd40
+  __AUTH_CONST.__objc_const: 0x4b6e8
   __AUTH_CONST.__weak_auth_got: 0x18
-  __AUTH_CONST.__auth_got: 0x650
+  __AUTH_CONST.__auth_got: 0x658
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x1
-  __DATA.__objc_ivar: 0x1124
+  __DATA.__objc_ivar: 0x1128
   __DATA.__data: 0x3c90
   __DATA.__bss: 0xa8
   __DATA_DIRTY.__objc_data: 0x4e20

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 8406
-  Symbols:   15515
-  CStrings:  3748
+  Functions: 8418
+  Symbols:   15537
+  CStrings:  3756
 
Symbols:
+ -[MTLGPUDebugComputeCommandEncoder setBufferUsageTable:textureUsageTable:tensorResidencyTable:bvhUsageTable:textureTypeTable:textureWriteUsageTable:]
+ -[MTLGPUDebugRenderCommandEncoder setBufferUsageTable:textureUsageTable:tensorResidencyTable:bvhUsageTable:textureTypeTable:textureWriteUsageTable:forStage:]
+ -[MTLToolsComputePipelineState forwardProgressUsage]
+ -[MTLToolsComputePipelineState recommendedPersistentThreadgroupsPerGridForThreadsPerThreadgroup:]
+ -[MTLToolsDevice supportsAtomicWaitNotify]
+ -[MTLToolsDevice supportsMXUNarrowTileSizes]
+ -[MTLToolsDevice supportsPackUnpackSmallInteger]
+ -[MTLToolsDevice supportsRGBTextureBuffers]
+ -[MTLToolsDevice supportsSIMDGroupParallelForwardProgress]
+ -[MTLToolsDevice supportsTextureViewMinLOD]
+ -[MTLToolsTexture minLOD]
+ OBJC_IVAR_$_MTLGPUDebugDevice.textureWriteUsageTable
+ _isRGBPixelFormat
+ _objc_msgSend$forwardProgressUsage
+ _objc_msgSend$minLOD
+ _objc_msgSend$recommendedPersistentThreadgroupsPerGridForThreadsPerThreadgroup:
+ _objc_msgSend$setBufferUsageTable:textureUsageTable:tensorResidencyTable:bvhUsageTable:textureTypeTable:textureWriteUsageTable:
+ _objc_msgSend$setBufferUsageTable:textureUsageTable:tensorResidencyTable:bvhUsageTable:textureTypeTable:textureWriteUsageTable:forStage:
+ _objc_msgSend$setEnableYieldChecks:
+ _objc_msgSend$supportsAtomicWaitNotify
+ _objc_msgSend$supportsMXUNarrowTileSizes
+ _objc_msgSend$supportsPackUnpackSmallInteger
+ _objc_msgSend$supportsRGBTextureBuffers
+ _objc_msgSend$supportsSIMDGroupParallelForwardProgress
+ _objc_msgSend$supportsTextureViewMinLOD
- -[MTLGPUDebugComputeCommandEncoder setBufferUsageTable:textureUsageTable:tensorResidencyTable:bvhUsageTable:textureTypeTable:]
- -[MTLGPUDebugRenderCommandEncoder setBufferUsageTable:textureUsageTable:tensorResidencyTable:bvhUsageTable:textureTypeTable:forStage:]
- _objc_msgSend$setBufferUsageTable:textureUsageTable:tensorResidencyTable:bvhUsageTable:textureTypeTable:forStage:
CStrings:
+ "Device does not support textures with pixelFormat(%s)"
+ "MTL_SHADER_VALIDATION_YIELD_CHECK"
+ "Texture buffer with pixelFormat(%s) must be read-only"
+ "minLOD (%f) must be 0.0 because the device does not support TextureViewMinLOD."
+ "minLOD (%f) should be greater than or equal to 0.0."
+ "minLOD (%f) should be less than or equal to mipmapLevelCount (%lu) of the parent texture."
+ "pixelFormat(%s) can only be used with MTLTextureTypeTextureBuffer"
+ "yield-check"
```
