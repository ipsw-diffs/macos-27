## CoreRecognition

> `/System/iOSSupport/System/Library/PrivateFrameworks/CoreRecognition.framework/Versions/A/CoreRecognition`

```diff

 446.13.0.0.0
-  __TEXT.__text: 0x55914
+  __TEXT.__text: 0x558f0
   __TEXT.__objc_methlist: 0x23d4
   __TEXT.__const: 0x74c
   __TEXT.__cstring: 0x3772
Functions:
~ __ZN3CNNC2EP6CorpusP17NetworkParameters : 4544 -> 4556
~ __ZNSt3__16vectorIP5LayerIfffENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJS3_EEEPS3_DpOT_ : 184 -> 176
~ +[ActivationMapTools textFromActivationMap:codeMap:invert:] : 1896 -> 1904
~ +[ActivationMapTools extractActivationSignals:fromActivationMap:forModel:codeMap:] : 1212 -> 1216
~ _matchAgainstContact : 4420 -> 4320
~ -[CRMLModel(Activations) activationsFromImage:] : 2000 -> 2004
~ __ZN8CTCLayer14setActivationsENSt3__16vectorINS1_INS1_IfNS0_9allocatorIfEEEENS2_IS4_EEEENS2_IS6_EEEE : 728 -> 732
~ __ZN8CTCLayer23computeForwardVariablesEv : 1236 -> 1264
~ +[GeometricCutTools geometricRecognitionOf:inDerotatedRegion:withPadding:fromCorrectedBoundingBox:inImageWithSize:withCodeMap:activations:invert:networkInputSize:] : 4664 -> 4672
~ +[GeometricCutTools geometricRecognitionOf:inDerotatedRegion:withPadding:fromCorrectedBoundingBox:inImageWithSize:withCodeMap:activations:invert:networkInputSize:garbageSymbol:] : 3092 -> 3096
```
