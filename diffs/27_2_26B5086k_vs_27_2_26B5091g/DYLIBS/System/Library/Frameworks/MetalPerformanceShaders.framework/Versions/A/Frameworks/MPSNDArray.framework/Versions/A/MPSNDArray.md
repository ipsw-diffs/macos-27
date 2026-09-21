## MPSNDArray

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Versions/A/Frameworks/MPSNDArray.framework/Versions/A/MPSNDArray`

```diff

-130.1.1.0.0
-  __TEXT.__text: 0x112400
+130.1.2.0.0
+  __TEXT.__text: 0x1128a8
   __TEXT.__objc_methlist: 0x7274
   __TEXT.__const: 0x9c9e0
-  __TEXT.__gcc_except_tab: 0x4e8c
-  __TEXT.__cstring: 0x133df
+  __TEXT.__gcc_except_tab: 0x4edc
+  __TEXT.__cstring: 0x133f7
   __TEXT.__oslogstring: 0x27
-  __TEXT.__unwind_info: 0x1fb0
+  __TEXT.__unwind_info: 0x1fb8
   __TEXT.__eh_frame: 0xb8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x20b88
+  __DATA_CONST.__const: 0x20cd8
   __DATA_CONST.__objc_classlist: 0x880
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_superrefs: 0x858
   __DATA_CONST.__got: 0x358
   __AUTH_CONST.__const: 0x4900
-  __AUTH_CONST.__cfstring: 0x9500
+  __AUTH_CONST.__cfstring: 0x9520
   __AUTH_CONST.__objc_const: 0xf7d0
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__auth_got: 0x570
-  __AUTH.__objc_data: 0x50
   __AUTH.__thread_vars: 0x30
   __AUTH.__thread_bss: 0x20
   __DATA.__objc_ivar: 0x7a4
-  __DATA.__data: 0x9ec
+  __DATA.__data: 0x68c
   __DATA.__bss: 0x650
-  __DATA_DIRTY.__objc_data: 0x54b0
+  __DATA_DIRTY.__objc_data: 0x5500
+  __DATA_DIRTY.__data: 0x360
   __DATA_DIRTY.__bss: 0x88
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2490
-  Symbols:   5568
-  CStrings:  1736
+  Functions: 2491
+  Symbols:   5570
+  CStrings:  1737
 
Symbols:
+ __ZNSt3__16vectorINS_4pairIPKiPKjEENS_9allocatorIS6_EEE20__throw_length_errorB9nqe220106Ev
+ __ZNSt3__16vectorINS_4pairIPKiPKjEENS_9allocatorIS6_EEE24__emplace_back_slow_pathIJS6_EEEPS6_DpOT_
Functions:
~ __ZL12EncodeDWConvPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfo : 6888 -> 6988
~ __ZL23EncodeQuantizedGatherNDPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfo : 17560 -> 18448
+ __ZNSt3__16vectorINS_4pairIPKiPKjEENS_9allocatorIS6_EEE24__emplace_back_slow_pathIJS6_EEEPS6_DpOT_
~ __ZNK38MPSNDArrayConvolutionDeviceBehaviorA1819GetKernelParametersEP9MPSKernelR50MPSNDArrayConvolutionGradientWithWeightsParametersPv11MPSDataTypeS5_S5_ : 2604 -> 2588
CStrings:
+ "depthwiseConv3d_cFirst4"
```
