## HomeAI

> `/System/Library/PrivateFrameworks/HomeAI.framework/Versions/A/HomeAI`

```diff

-382.0.0.0.0
-  __TEXT.__text: 0x18302c
+386.0.0.0.0
+  __TEXT.__text: 0x183374
   __TEXT.__init_offsets: 0x10
-  __TEXT.__objc_methlist: 0xa43c
+  __TEXT.__objc_methlist: 0xa444
   __TEXT.__const: 0x493d
-  __TEXT.__cstring: 0xdb32
+  __TEXT.__cstring: 0xdb5f
   __TEXT.__gcc_except_tab: 0xc094
-  __TEXT.__oslogstring: 0xde17
+  __TEXT.__oslogstring: 0xded4
   __TEXT.__swift5_typeref: 0x21
   __TEXT.__constg_swiftt: 0x28
   __TEXT.__swift5_reflstr: 0x74
   __TEXT.__swift5_fieldmd: 0x4c
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x5af8
+  __TEXT.__unwind_info: 0x5b00
   __TEXT.__eh_frame: 0x50
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xd78
+  __DATA_CONST.__const: 0xd98
   __DATA_CONST.__objc_classlist: 0x6f8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x46c0
+  __DATA_CONST.__objc_selrefs: 0x46c8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x5f0
   __DATA_CONST.__objc_arraydata: 0x6e8
   __DATA_CONST.__got: 0xbc8
-  __AUTH_CONST.__const: 0x7a40
+  __AUTH_CONST.__const: 0x7a60
   __AUTH_CONST.__cfstring: 0x8960
   __AUTH_CONST.__objc_const: 0x15e50
   __AUTH_CONST.__weak_auth_got: 0x28

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5510
-  Symbols:   11941
-  CStrings:  3129
+  Functions: 5512
+  Symbols:   11945
+  CStrings:  3132
 
Symbols:
+ +[HMITorsoClassifier predictedLinkedEntityUUIDsForPrediction:homeUUID:]
+ +[HMIVideoAnalyzerMutableReport silhouetteScoreForMatches:previousMatches:truePositiveScores:falsePositiveScores:falseNegativeScores:]
+ -[HMICameraActivityZone jsonRepresentationOfDetectedObject:motionDetection:eventClass:]
+ -[HMICameraActivityZone overlapsWithEllipseInsideRect:]
+ -[HMICameraActivityZone overlapsWithEllipseInsideRect:withInsetPercentage:]
+ _HMILineSegmentsIntersect
+ ___134+[HMIVideoAnalyzerMutableReport silhouetteScoreForMatches:previousMatches:truePositiveScores:falsePositiveScores:falseNegativeScores:]_block_invoke
+ ___134+[HMIVideoAnalyzerMutableReport silhouetteScoreForMatches:previousMatches:truePositiveScores:falsePositiveScores:falseNegativeScores:]_block_invoke_2
+ ___71+[HMITorsoClassifier predictedLinkedEntityUUIDsForPrediction:homeUUID:]_block_invoke
+ ___block_descriptor_32_e43_"NSUUID"16?0"HMIPersonsModelPrediction"8l
+ _objc_msgSend$jsonRepresentationOfDetectedObject:motionDetection:eventClass:
+ _objc_msgSend$overlapsWithEllipseInsideRect:
+ _objc_msgSend$overlapsWithEllipseInsideRect:withInsetPercentage:
+ _objc_msgSend$predictedLinkedEntityUUIDsForPrediction:homeUUID:
+ _objc_msgSend$silhouetteScoreForMatches:previousMatches:truePositiveScores:falsePositiveScores:falseNegativeScores:
- +[HMIVideoAnalyzerMutableReport sihouetteScoreForMatches:previousMatches:truePositiveScores:falsePositiveScores:falseNegativeScores:]
- -[HMICameraActivityZone jsonReperesentaionOfDetectedObject:motionDetection:eventClass:]
- -[HMICameraActivityZone overlapsWithElipseInsideRect:]
- -[HMICameraActivityZone overlapsWithElipseInsideRect:withInsetPercentage:]
- _HMILineSgementsIntersect
- ___133+[HMIVideoAnalyzerMutableReport sihouetteScoreForMatches:previousMatches:truePositiveScores:falsePositiveScores:falseNegativeScores:]_block_invoke
- ___133+[HMIVideoAnalyzerMutableReport sihouetteScoreForMatches:previousMatches:truePositiveScores:falsePositiveScores:falseNegativeScores:]_block_invoke_2
- _objc_msgSend$jsonReperesentaionOfDetectedObject:motionDetection:eventClass:
- _objc_msgSend$overlapsWithElipseInsideRect:
- _objc_msgSend$overlapsWithElipseInsideRect:withInsetPercentage:
- _objc_msgSend$sihouetteScoreForMatches:previousMatches:truePositiveScores:falsePositiveScores:falseNegativeScores:
CStrings:
+ "@\"NSUUID\"16@?0@\"HMIPersonsModelPrediction\"8"
+ "Couldn't retrieve linked predictions for torso personUUID: %@ homeUUID: %@ error: %@"
+ "Face removed from unknown and uncertain bucket, SSD confidence = %f, entropy of laplacian = %f, Face yaw = %f, box size: %f"
+ "Named person %@ with at least 1 personLink has %lu clusters, treating as impure"
+ "Successfully associated face crops (num UUIDs %lu) to person UUID: %@ for source: %@"
+ "Successfully removed persons %@"
+ "Unknown server error"
+ "[%{public}@] Couldn't retrieve linked predictions for torso personUUID: %@ homeUUID: %@ error: %@"
+ "[%{public}@] Face removed from unknown and uncertain bucket, SSD confidence = %f, entropy of laplacian = %f, Face yaw = %f, box size: %f"
+ "[%{public}@] Named person %@ with at least 1 personLink has %lu clusters, treating as impure"
+ "[%{public}@] Successfully associated face crops (num UUIDs %lu) to person UUID: %@ for source: %@"
+ "[%{public}@] Successfully removed persons %@"
- "Face removed from unknown and uncertian bucket, SSD confidence = %f, entropy of laplacian = %f, Face yaw = %f, box size: %f"
- "Named person %@ with atleast 1 personLink has %lu clusters, treating as impure"
- "Succesfully associated face crops (num UUIDs %lu) to person UUID: %@ for source: %@"
- "Succesfully removed persons %@"
- "Unkown server error"
- "[%{public}@] Face removed from unknown and uncertian bucket, SSD confidence = %f, entropy of laplacian = %f, Face yaw = %f, box size: %f"
- "[%{public}@] Named person %@ with atleast 1 personLink has %lu clusters, treating as impure"
- "[%{public}@] Succesfully associated face crops (num UUIDs %lu) to person UUID: %@ for source: %@"
- "[%{public}@] Succesfully removed persons %@"
```
