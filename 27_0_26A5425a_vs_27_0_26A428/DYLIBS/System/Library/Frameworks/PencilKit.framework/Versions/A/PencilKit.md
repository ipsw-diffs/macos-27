## PencilKit

> `/System/Library/Frameworks/PencilKit.framework/Versions/A/PencilKit`

```diff

 616.0.0.0.0
-  __TEXT.__text: 0x15f0b4
+  __TEXT.__text: 0x15f148
   __TEXT.__objc_methlist: 0xd690
   __TEXT.__const: 0x59b8
   __TEXT.__cstring: 0x44f0

   __TEXT.__oslogstring: 0x2ceb
   __TEXT.__gcc_except_tab: 0x13c84
   __TEXT.__ustring: 0xe
-  __TEXT.__unwind_info: 0x8238
+  __TEXT.__unwind_info: 0x8230
   __TEXT.__eh_frame: 0x1338
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
Functions:
~ __ZNSt3__16vectorINS_10unique_ptrIN14legacy_drawing20VectorTimestampClockENS_14default_deleteIS3_EEEENS_9allocatorIS6_EEE24__emplace_back_slow_pathIJS6_EEEPS6_DpOT_ : 224 -> 228
~ __ZN9drawingV18StrokeID8readFromERN2PB6ReaderE : 1088 -> 1096
~ -[PKMetalRenderer generatePaintCacheForStroke:animatingStroke:segmentSteps:liveStrokePoints:liveStrokeStartTime:duration:] : 2556 -> 2552
~ -[PKMetalRenderer generateParticleCacheForStroke:animatingStroke:starts:ends:secondaryParticles:] : 2432 -> 2428
~ __ZNK15PKBSplineFilter24calculateStepsForSegmentEmRK14_PKStrokePointS2_ : 836 -> 872
~ __ZN14legacy_drawing32VectorTimestampClockReplicaClock8readFromERN2PB6ReaderE : 836 -> 844
~ -[_PKStrokeConcrete(PKStrokePersistenceAdditions) initWithLegacyArchive:sortedUUIDs:] : 1572 -> 1568
~ -[PKStrokePath initWithControlPoints:creationDate:strokePathID:] : 524 -> 520
~ __ZNSt3__16vectorI23PKCompressedStrokePointNS_9allocatorIS1_EEE6resizeEm : 372 -> 376
~ __ZNSt3__16vectorI7CGPointNS_9allocatorIS1_EEE6insertENS_11__wrap_iterIPKS1_EERS6_ : 476 -> 472
~ -[PKShapeDrawingController _strokeFromPoints:inputScale:averageInputPoint:sourceStroke:] : 1856 -> 1852
~ __ZNSt3__114__split_bufferI7CGPointRNS_9allocatorIS1_EEE12emplace_backIJRKS1_EEEvDpOT_ : 264 -> 268
~ __ZNSt3__16vectorI12PKInputPointNS_9allocatorIS1_EEE6resizeEm : 372 -> 376
~ +[PKInkBehavior(Internal) inkFunctionForProperty:outputFunctions:index:] : 1816 -> 1812
~ __ZN25PKFunctionPiecewiseBezier5solveEv : 868 -> 876
~ +[PKPathUtility convexHull:forPoints:] : 1500 -> 1504
~ +[PKPathUtility centripetalCatmullRomPointsFromConvexHull:alpha:granularity:] : 1072 -> 1088
~ __ZNSt3__115__inplace_mergeINS_17_ClassicAlgPolicyERNS_6__lessIvvEENS_11__wrap_iterIP10PolarPointEEEEvT1_S9_S9_OT0_NS_15iterator_traitsIS9_E15difference_typeESE_PNSD_10value_typeEl : 1324 -> 1328
~ __ZN10ClipperLib4AreaERKNSt3__16vectorINS_8IntPointENS0_9allocatorIS2_EEEE : 136 -> 140
~ __ZN10ClipperLib10GetOverlapExxxxRxS0_ : 124 -> 136
~ __ZN10ClipperLib13ClipperOffset8DoOffsetEd : 2568 -> 2584
~ __ZN10ClipperLib9MinkowskiERKNSt3__16vectorINS_8IntPointENS0_9allocatorIS2_EEEES7_RNS1_IS5_NS3_IS5_EEEEbb : 2404 -> 2412
~ __ZNSt3__16vectorIPN10ClipperLib5TEdgeENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJRKS3_EEEPS3_DpOT_ : 184 -> 176
~ __ZNSt3__16vectorIxNS_9allocatorIxEEE24__emplace_back_slow_pathIJRKxEEEPxDpOT_ : 184 -> 176
~ __ZNSt3__16vectorINS_10unique_ptrIN14legacy_drawing7CommandENS_14default_deleteIS3_EEEENS_9allocatorIS6_EEE24__emplace_back_slow_pathIJS6_EEEPS6_DpOT_ : 220 -> 224
~ __ZN7drawing8StrokeID8readFromERN2PB6ReaderE : 1088 -> 1096
~ -[PKStroke(Slicing) _appendPointsOfInterestForSelectionMasked:] : 708 -> 712
~ -[PKDrawing(Slicing) sliceWithEraseStroke:honoringErasable:] : 4280 -> 4284
~ __ZNSt3__16vectorIPN10ClipperLib8PolyNodeENS_9allocatorIS3_EEE18__insert_with_sizeB9nqe220106INS_17_ClassicAlgPolicyENS_11__wrap_iterIPS3_EESB_EESB_NS9_IPKS3_EET0_T1_l : 552 -> 568
~ __ZNSt3__16vectorIU8__strongP7NSArrayIP8PKStrokeENS_9allocatorIS6_EEEC2B9nqe220106EmRU8__strongKS5_ : 124 -> 132
~ __ZNSt3__16vectorIU8__strongP8PKStrokeNS_9allocatorIS3_EEEC2B9nqe220106EmRU8__strongKS2_ : 152 -> 160
~ __ZNSt3__16vectorIN2PB4DataENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJS2_EEEPS2_DpOT_ : 272 -> 268
~ __Z26PKArcLengthsFromPointArrayRKNSt3__16vectorI7CGPointNS_9allocatorIS1_EEEERNS0_IdNS2_IdEEEE : 248 -> 252
~ __ZNSt3__16vectorIP6CGPathNS_9allocatorIS2_EEE24__emplace_back_slow_pathIJRKS2_EEEPS2_DpOT_ : 184 -> 176
~ __ZN27PKVelocityCalculationFilter25copyUpdatedRangeFromIndexEmPNSt3__16vectorI12PKInputPointNS0_9allocatorIS2_EEEE : 600 -> 596
~ __ZN21PKInputToOutputFilter3runEv : 400 -> 404
~ __ZN14legacy_drawing9CommandID8readFromERN2PB6ReaderE : 1088 -> 1096
```
