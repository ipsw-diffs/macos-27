## MetalPerformanceShadersGraph

> `/System/Library/Frameworks/MetalPerformanceShadersGraph.framework/Versions/A/MetalPerformanceShadersGraph`

```diff

-7.1.5.0.0
-  __TEXT.__text: 0x2219624
+7.1.6.0.0
+  __TEXT.__text: 0x221af30
   __TEXT.__mpsgraph_init_: 0x40
   __TEXT.__objc_methlist: 0x8624
   __TEXT.__const: 0x6dd98
-  __TEXT.__cstring: 0xf256a
+  __TEXT.__cstring: 0xf2748
   __TEXT.__swift5_typeref: 0xb72
   __TEXT.__swift5_capture: 0x340
   __TEXT.__oslogstring: 0x378f

   __TEXT.__swift_as_cont: 0x10
   __TEXT.__gcc_except_tab: 0x1381d8
   __TEXT.__ustring: 0x19c
-  __TEXT.__unwind_info: 0x776c8
+  __TEXT.__unwind_info: 0x776e0
   __TEXT.__eh_frame: 0x3d84
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 105245
-  Symbols:   148368
-  CStrings:  21143
+  Functions: 105252
+  Symbols:   148375
+  CStrings:  21153
 
Symbols:
+ _ZN4llvm12function_refIFvPN4mlir9OperationEEE11callback_fnIZNS1_3mps12_GLOBAL__N_122findTrailingDataLayoutENS1_4mpsx10StitchedOpEE3$_0EEvlS3_
+ _ZN4mlir3mpsL30validateAndCollectConcatAllocsENS0_8ConcatOpENS_10ValueRangeEybRNS_15PatternRewriterEb
+ _ZN4mlir9OpBuilder6createINS_7mps_spi18StridedArrayViewOpEJRNS_10MemRefTypeENS_6detail10TypedValueIS4_EERxRN4llvm11SmallVectorIxLj6EEESD_EEET_NS_8LocationEDpOT0_
+ __ZN4llvm12DenseMapBaseINS_13SmallDenseMapIPN4mlir9OperationENS_6detail13DenseSetEmptyELj4ENS_12DenseMapInfoIS4_vEENS5_12DenseSetPairIS4_EEEES4_S6_S8_SA_E11try_emplaceIJRS6_EEENSt3__14pairINS_16DenseMapIteratorIS4_S6_S8_SA_Lb0EEEbEEOS4_DpOT_
+ __ZN4llvm12function_refIFvPN4mlir9OperationEEE11callback_fnIZNS1_3mps12_GLOBAL__N_122findTrailingDataLayoutENS1_4mpsx10StitchedOpEE3$_0EEvlS3_
+ __ZN4llvm15SmallVectorImplIN4mlir3mps17ConcatOperandInfoEEaSEOS4_
+ __ZN4llvm23SmallVectorTemplateBaseIN4mlir3mps17ConcatOperandInfoELb0EE4growEm
+ __ZN4llvm23SmallVectorTemplateBaseIN4mlir3mps17ConcatOperandInfoELb0EE9push_backERKS3_
+ __ZN4mlir3mps12_GLOBAL__N_114findStitchedOpENS_4mpsx14MemrefBackedOpE
+ __ZN4mlir3mps12_GLOBAL__N_121isCanonicalConversionENS0_16TensorDataLayoutEN4llvm8ArrayRefIxEE
+ __ZN4mlir3mps12_GLOBAL__N_122findTrailingDataLayoutENS_4mpsx10StitchedOpE
+ __ZN4mlir3mpsL30validateAndCollectConcatAllocsENS0_8ConcatOpENS_10ValueRangeEybRNS_15PatternRewriterEb
+ __ZN4mlir9OpBuilder6createINS_7mps_spi18StridedArrayViewOpEJRNS_10MemRefTypeENS_6detail10TypedValueIS4_EERxRN4llvm11SmallVectorIxLj6EEESD_EEET_NS_8LocationEDpOT0_
+ __ZNSt3__124__optional_destruct_baseIN4mlir3mps15ConcatAllocInfoELb0EEC2B9nqn220106IJS3_EEENS_10in_place_tEDpOT_
- _ZN4llvm12function_refIFvPN4mlir9OperationEEE11callback_fnIZNKS1_3mps12_GLOBAL__N_132LayoutConversionPermuteConverter15matchAndRewriteENS7_9PermuteOpERNS1_15PatternRewriterEEUlS3_E_EEvlS3_
- _ZN4mlir3mpsL30validateAndCollectConcatAllocsENS0_8ConcatOpENS_10ValueRangeEybRNS_15PatternRewriterE
- __ZN4llvm12function_refIFvPN4mlir9OperationEEE11callback_fnIZNKS1_3mps12_GLOBAL__N_132LayoutConversionPermuteConverter15matchAndRewriteENS7_9PermuteOpERNS1_15PatternRewriterEEUlS3_E_EEvlS3_
- __ZN4mlir3mps12_GLOBAL__N_132LayoutConversionPermuteConverter21isCanonicalConversionENS0_16TensorDataLayoutEN4llvm8ArrayRefIxEE
- __ZN4mlir3mpsL30validateAndCollectConcatAllocsENS0_8ConcatOpENS_10ValueRangeEybRNS_15PatternRewriterE
- __ZN4mlir6Region4walkILNS_9WalkOrderE0ENS_15ForwardIteratorEZNKS_3mps12_GLOBAL__N_132LayoutConversionPermuteConverter15matchAndRewriteENS4_9PermuteOpERNS_15PatternRewriterEEUlPNS_9OperationEE_SB_vEET3_OT1_
- __ZN4mlir6Region6getOpsEv
CStrings:
+ "7.1.6"
+ "concat operands share a backing alloc"
+ "concat: static strides exceed INT32_MAX; cannot be represented as mps_spi.strided_array_view (MPSNDArray stride fields are int32)"
+ "layout concat operand: alloc has a non-identity layout"
+ "layout concat operand: multiple writers"
+ "layout concat operand: no writer"
+ "layout concat operand: the NHWC tensor is returned"
+ "layout concat operand: unexpected alloc user"
+ "non-constant operand permute"
+ "operand permute is not a canonical layout conversion"
```
