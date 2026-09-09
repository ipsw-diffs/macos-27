## MLCompute

> `/System/Library/Frameworks/MLCompute.framework/Versions/A/MLCompute`

```diff

 87.0.0.0.0
-  __TEXT.__text: 0x129e1c
+  __TEXT.__text: 0x129e54
   __TEXT.__objc_methlist: 0xaf7c
   __TEXT.__const: 0x5b0
   __TEXT.__oslogstring: 0x8ee6

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 4288
+  Functions: 4289
   Symbols:   8018
   CStrings:  1385
 
Functions:
+ _OUTLINED_FUNCTION_1
~ -[MLCDeviceGPU allocateDeviceHeapForGraph:forInference:] : 4052 -> 4056
~ -[MLCDeviceCPU(MLCLayerOperations) embeddingWeightsGradients:embeddingCount:embeddingDimension:] : 540 -> 544
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchForwardAndGradientLossLayer:sourceTensor:labelsTensor:labelsTensorStride:weightsTensor:resultTensor:resultGradientTensor:] : 4048 -> 4040
~ -[MLCDeviceCPU(MLCEngineDispatch) dispatchForwardEmbeddingLayer:weight:sourceTensor:resultTensor:] : 1484 -> 1504
~ -[MLCDeviceCPU(MLCEngineDispatch) dispatchGradientEmbeddingLayer:sourceGradientTensor:] : 880 -> 884
~ _saveOrRestoreLSTMWeightsAndAccumulatorsHelper : 36 -> 40
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) updateRNNLayer:optimizer:inputWeightsParameter:hiddenWeightsParameter:biasesParameter:arrayOfParams:] : 2612 -> 2608
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) updateEmbeddingLayer:weightsParameter:optimizer:arrayOfParams:] : 1312 -> 1320
~ -[MLCGraph nodeWithMultiOutputLayer:source:forTraining:] : 2260 -> 2272
~ ANE_CreateSliceLayer.cold.1 : 72 -> 76
~ ANE_CreateSliceLayer.cold.2 : 72 -> 76
~ ANE_CreateSliceLayer.cold.3 : 100 -> 88
~ ANE_CompileSliceLayer.cold.1 : 92 -> 96
~ ANE_CompileSliceLayer.cold.2 : 80 -> 68
```
