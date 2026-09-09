## VisionCore

> `/System/Library/PrivateFrameworks/VisionCore.framework/Versions/A/VisionCore`

```diff

 10.0.44.0.0
-  __TEXT.__text: 0x437e4
+  __TEXT.__text: 0x4375c
   __TEXT.__objc_methlist: 0x326c
   __TEXT.__const: 0x570
   __TEXT.__dlopen_cstrs: 0x228

   __TEXT.__swift5_proto: 0x14
   __TEXT.__swift5_types: 0x28
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__gcc_except_tab: 0x4144
+  __TEXT.__gcc_except_tab: 0x414c
   __TEXT.__oslogstring: 0x1d5
-  __TEXT.__unwind_info: 0x1780
+  __TEXT.__unwind_info: 0x1778
   __TEXT.__eh_frame: 0x80
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1327
+  Functions: 1326
   Symbols:   3864
   CStrings:  658
 
Functions:
~ __ZNSt3__16vectorImNS_9allocatorImEEE24__emplace_back_slow_pathIJmEEEPmDpOT_ : 184 -> 176
~ -[VisionCoreSparseOpticalFlowQuad generateGridKeypointsWithMaxKeypoints:minGridFrequency:] : 972 -> 980
~ -[VisionCoreSparseOpticalFlowSession updateMemoryKeypointsWithOpticalFlowResultsSourceBuffer:destBuffer:matchBuffer:start:] : 1188 -> 1196
~ __ZNSt3__16vectorIDhNS_9allocatorIDhEEE18__insert_with_sizeB9nqe220106INS_17_ClassicAlgPolicyENS_11__wrap_iterIPDhEES8_EES8_NS6_IPKDhEET0_T1_l : 540 -> 556
~ __ZNSt3__16vectorIiNS_9allocatorIiEEE24__emplace_back_slow_pathIJRiEEEPiDpOT_ : 184 -> 176
~ -[VisionCoreValueConfidenceCurve confidenceForValue:] : 196 -> 204
~ -[VisionCoreValueConfidenceCurve encodeWithCoder:] : 852 -> 864
- __ZNSt3__16vectorI30VisionCoreValueConfidencePointNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_
~ -[VisionCoreTensorStrides initWithShape:dataType:] : 640 -> 636
~ -[VisionCoreLKTSparseGPU _enqueueImagePyramidWithCommandBuffer:inputTexture:index:] : 680 -> 688
```
