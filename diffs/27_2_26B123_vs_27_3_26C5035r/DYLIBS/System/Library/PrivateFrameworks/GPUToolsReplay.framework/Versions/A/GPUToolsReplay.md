## GPUToolsReplay

> `/System/Library/PrivateFrameworks/GPUToolsReplay.framework/Versions/A/GPUToolsReplay`

```diff

-2027.1.3.0.0
-  __TEXT.__text: 0x40d324
+2027.2.4.0.0
+  __TEXT.__text: 0x411348
   __TEXT.__init_offsets: 0x10
-  __TEXT.__objc_methlist: 0x7eac
-  __TEXT.__const: 0xa518
-  __TEXT.__oslogstring: 0x18ce
-  __TEXT.__cstring: 0x110cf2
-  __TEXT.__gcc_except_tab: 0x178c4
+  __TEXT.__objc_methlist: 0x7dbc
+  __TEXT.__const: 0xa5d8
+  __TEXT.__oslogstring: 0x1903
+  __TEXT.__cstring: 0x110fe5
+  __TEXT.__gcc_except_tab: 0x18208
   __TEXT.__ustring: 0x4f6
-  __TEXT.__unwind_info: 0x7a20
+  __TEXT.__unwind_info: 0x79c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x33c740
-  __DATA_CONST.__objc_classlist: 0x298
+  __DATA_CONST.__const: 0x33c750
+  __DATA_CONST.__objc_classlist: 0x290
   __DATA_CONST.__objc_catlist: 0x30
-  __DATA_CONST.__objc_protolist: 0x1a0
+  __DATA_CONST.__objc_protolist: 0x198
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6b68
+  __DATA_CONST.__objc_selrefs: 0x6c38
   __DATA_CONST.__objc_protorefs: 0xc8
-  __DATA_CONST.__objc_superrefs: 0x270
+  __DATA_CONST.__objc_superrefs: 0x268
   __DATA_CONST.__objc_arraydata: 0xba0
-  __DATA_CONST.__got: 0x998
-  __AUTH_CONST.__const: 0x38e8
-  __AUTH_CONST.__cfstring: 0xf9a0
-  __AUTH_CONST.__objc_const: 0xc0e8
+  __DATA_CONST.__got: 0x9a8
+  __AUTH_CONST.__const: 0x3888
+  __AUTH_CONST.__cfstring: 0xfaa0
+  __AUTH_CONST.__objc_const: 0xc068
   __AUTH_CONST.__weak_auth_got: 0x30
-  __AUTH_CONST.__objc_intobj: 0x720
+  __AUTH_CONST.__objc_intobj: 0x738
   __AUTH_CONST.__objc_arrayobj: 0x270
   __AUTH_CONST.__objc_dictobj: 0x820
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0xd90
-  __AUTH.__objc_data: 0x19f0
+  __AUTH_CONST.__auth_got: 0xd98
+  __AUTH.__objc_data: 0x19a0
   __AUTH.__data: 0x20
   __AUTH.__thread_vars: 0x78
   __AUTH.__thread_bss: 0x1088
-  __DATA.__objc_ivar: 0x79c
-  __DATA.__data: 0x2668
+  __DATA.__objc_ivar: 0x7a0
+  __DATA.__data: 0x2608
   __DATA.__bss: 0x1528
   __DATA.__common: 0x51
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 7527
-  Symbols:   12318
-  CStrings:  18420
+  Functions: 7472
+  Symbols:   12284
+  CStrings:  18436
 
Symbols:
+ +[GTReplayMTLFXFrameInterpolator wrapperWithDevice:descriptor:]
+ -[GTMTLReplayObjectMap mtl4CounterHeapForKey:]
+ -[GTMTLReplayObjectMap removeMTL4CounterHeapForKey:]
+ -[GTMTLReplayObjectMap setMTL4CounterHeap:forKey:]
+ -[GTMTLReplaySharedBufferRange scalesPlaneTensorAlias:dataPlaneOffset:]
+ -[GTReplayMTLFXFrameInterpolator aspectRatio]
+ -[GTReplayMTLFXFrameInterpolator colorTextureFormat]
+ -[GTReplayMTLFXFrameInterpolator colorTextureUsage]
+ -[GTReplayMTLFXFrameInterpolator colorTexture]
+ -[GTReplayMTLFXFrameInterpolator compositedUITexture]
+ -[GTReplayMTLFXFrameInterpolator contentHeight]
+ -[GTReplayMTLFXFrameInterpolator contentWidth]
+ -[GTReplayMTLFXFrameInterpolator debugTexture]
+ -[GTReplayMTLFXFrameInterpolator deltaTime]
+ -[GTReplayMTLFXFrameInterpolator depthContentOffsetX]
+ -[GTReplayMTLFXFrameInterpolator depthContentOffsetY]
+ -[GTReplayMTLFXFrameInterpolator depthTextureFormat]
+ -[GTReplayMTLFXFrameInterpolator depthTextureUsage]
+ -[GTReplayMTLFXFrameInterpolator depthTexture]
+ -[GTReplayMTLFXFrameInterpolator distortionHeight]
+ -[GTReplayMTLFXFrameInterpolator distortionOffsetX]
+ -[GTReplayMTLFXFrameInterpolator distortionOffsetY]
+ -[GTReplayMTLFXFrameInterpolator distortionTexture]
+ -[GTReplayMTLFXFrameInterpolator distortionWidth]
+ -[GTReplayMTLFXFrameInterpolator encodeToCommandBuffer:]
+ -[GTReplayMTLFXFrameInterpolator encodeToCommandQueue:]
+ -[GTReplayMTLFXFrameInterpolator farPlane]
+ -[GTReplayMTLFXFrameInterpolator fence]
+ -[GTReplayMTLFXFrameInterpolator fieldOfView]
+ -[GTReplayMTLFXFrameInterpolator height]
+ -[GTReplayMTLFXFrameInterpolator initWithDevice:descriptor:]
+ -[GTReplayMTLFXFrameInterpolator inputHeight]
+ -[GTReplayMTLFXFrameInterpolator inputWidth]
+ -[GTReplayMTLFXFrameInterpolator isDepthReversed]
+ -[GTReplayMTLFXFrameInterpolator isUITextureComposited]
+ -[GTReplayMTLFXFrameInterpolator jitterOffsetX]
+ -[GTReplayMTLFXFrameInterpolator jitterOffsetY]
+ -[GTReplayMTLFXFrameInterpolator motionContentOffsetX]
+ -[GTReplayMTLFXFrameInterpolator motionContentOffsetY]
+ -[GTReplayMTLFXFrameInterpolator motionTextureFormat]
+ -[GTReplayMTLFXFrameInterpolator motionTextureUsage]
+ -[GTReplayMTLFXFrameInterpolator motionTexture]
+ -[GTReplayMTLFXFrameInterpolator motionVectorScaleX]
+ -[GTReplayMTLFXFrameInterpolator motionVectorScaleY]
+ -[GTReplayMTLFXFrameInterpolator nearPlane]
+ -[GTReplayMTLFXFrameInterpolator outputHeight]
+ -[GTReplayMTLFXFrameInterpolator outputOffsetX]
+ -[GTReplayMTLFXFrameInterpolator outputOffsetY]
+ -[GTReplayMTLFXFrameInterpolator outputTextureFormat]
+ -[GTReplayMTLFXFrameInterpolator outputTextureUsage]
+ -[GTReplayMTLFXFrameInterpolator outputTexture]
+ -[GTReplayMTLFXFrameInterpolator outputWidth]
+ -[GTReplayMTLFXFrameInterpolator prevColorTexture]
+ -[GTReplayMTLFXFrameInterpolator reset]
+ -[GTReplayMTLFXFrameInterpolator setAspectRatio:]
+ -[GTReplayMTLFXFrameInterpolator setColorTexture:]
+ -[GTReplayMTLFXFrameInterpolator setCompositedUITexture:]
+ -[GTReplayMTLFXFrameInterpolator setContentHeight:]
+ -[GTReplayMTLFXFrameInterpolator setContentWidth:]
+ -[GTReplayMTLFXFrameInterpolator setDebugTexture:]
+ -[GTReplayMTLFXFrameInterpolator setDeltaTime:]
+ -[GTReplayMTLFXFrameInterpolator setDepthContentOffsetX:]
+ -[GTReplayMTLFXFrameInterpolator setDepthContentOffsetY:]
+ -[GTReplayMTLFXFrameInterpolator setDepthReversed:]
+ -[GTReplayMTLFXFrameInterpolator setDepthTexture:]
+ -[GTReplayMTLFXFrameInterpolator setDistortionHeight:]
+ -[GTReplayMTLFXFrameInterpolator setDistortionOffsetX:]
+ -[GTReplayMTLFXFrameInterpolator setDistortionOffsetY:]
+ -[GTReplayMTLFXFrameInterpolator setDistortionTexture:]
+ -[GTReplayMTLFXFrameInterpolator setDistortionWidth:]
+ -[GTReplayMTLFXFrameInterpolator setFarPlane:]
+ -[GTReplayMTLFXFrameInterpolator setFence:]
+ -[GTReplayMTLFXFrameInterpolator setFieldOfView:]
+ -[GTReplayMTLFXFrameInterpolator setHeight:]
+ -[GTReplayMTLFXFrameInterpolator setIsUITextureComposited:]
+ -[GTReplayMTLFXFrameInterpolator setJitterOffsetX:]
+ -[GTReplayMTLFXFrameInterpolator setJitterOffsetY:]
+ -[GTReplayMTLFXFrameInterpolator setMotionContentOffsetX:]
+ -[GTReplayMTLFXFrameInterpolator setMotionContentOffsetY:]
+ -[GTReplayMTLFXFrameInterpolator setMotionTexture:]
+ -[GTReplayMTLFXFrameInterpolator setMotionVectorScaleX:]
+ -[GTReplayMTLFXFrameInterpolator setMotionVectorScaleY:]
+ -[GTReplayMTLFXFrameInterpolator setNearPlane:]
+ -[GTReplayMTLFXFrameInterpolator setOutputOffsetX:]
+ -[GTReplayMTLFXFrameInterpolator setOutputOffsetY:]
+ -[GTReplayMTLFXFrameInterpolator setOutputTexture:]
+ -[GTReplayMTLFXFrameInterpolator setPrevColorTexture:]
+ -[GTReplayMTLFXFrameInterpolator setReset:]
+ -[GTReplayMTLFXFrameInterpolator setShouldResetHistory:]
+ -[GTReplayMTLFXFrameInterpolator setUITexture:]
+ -[GTReplayMTLFXFrameInterpolator setViewToClipMatrix:]
+ -[GTReplayMTLFXFrameInterpolator setWidth:]
+ -[GTReplayMTLFXFrameInterpolator setWorldToViewMatrix:]
+ -[GTReplayMTLFXFrameInterpolator shouldResetHistory]
+ -[GTReplayMTLFXFrameInterpolator uiTextureFormat]
+ -[GTReplayMTLFXFrameInterpolator uiTextureUsage]
+ -[GTReplayMTLFXFrameInterpolator uiTexture]
+ -[GTReplayMTLFXFrameInterpolator viewToClipMatrix]
+ -[GTReplayMTLFXFrameInterpolator width]
+ -[GTReplayMTLFXFrameInterpolator worldToViewMatrix]
+ GCC_except_table1003
+ GCC_except_table1004
+ GCC_except_table1015
+ GCC_except_table1024
+ GCC_except_table1173
+ GCC_except_table1191
+ GCC_except_table1194
+ GCC_except_table1197
+ GCC_except_table1199
+ GCC_except_table1236
+ GCC_except_table1238
+ GCC_except_table1239
+ GCC_except_table1245
+ GCC_except_table1257
+ GCC_except_table1265
+ GCC_except_table1271
+ GCC_except_table1286
+ GCC_except_table1294
+ GCC_except_table1295
+ GCC_except_table1296
+ GCC_except_table1297
+ GCC_except_table1302
+ GCC_except_table1303
+ GCC_except_table1307
+ GCC_except_table1311
+ GCC_except_table1312
+ GCC_except_table1313
+ GCC_except_table1333
+ GCC_except_table1334
+ GCC_except_table1335
+ GCC_except_table1336
+ GCC_except_table1337
+ GCC_except_table1338
+ GCC_except_table1341
+ GCC_except_table1347
+ GCC_except_table1348
+ GCC_except_table1354
+ GCC_except_table1355
+ GCC_except_table1357
+ GCC_except_table1361
+ GCC_except_table1362
+ GCC_except_table1363
+ GCC_except_table1364
+ GCC_except_table1365
+ GCC_except_table1366
+ GCC_except_table1367
+ GCC_except_table1375
+ GCC_except_table1376
+ GCC_except_table1384
+ GCC_except_table1395
+ GCC_except_table1399
+ GCC_except_table1400
+ GCC_except_table1401
+ GCC_except_table1404
+ GCC_except_table1406
+ GCC_except_table1409
+ GCC_except_table1412
+ GCC_except_table1424
+ GCC_except_table1428
+ GCC_except_table1429
+ GCC_except_table1436
+ GCC_except_table1438
+ GCC_except_table1441
+ GCC_except_table1459
+ GCC_except_table1462
+ GCC_except_table1463
+ GCC_except_table1466
+ GCC_except_table1467
+ GCC_except_table1468
+ GCC_except_table1470
+ GCC_except_table1471
+ GCC_except_table1472
+ GCC_except_table1473
+ GCC_except_table1474
+ GCC_except_table1475
+ GCC_except_table1511
+ GCC_except_table1524
+ GCC_except_table1528
+ GCC_except_table1540
+ GCC_except_table1608
+ GCC_except_table1725
+ GCC_except_table1749
+ GCC_except_table1750
+ GCC_except_table1805
+ GCC_except_table1830
+ GCC_except_table1861
+ GCC_except_table1862
+ GCC_except_table1863
+ GCC_except_table1864
+ GCC_except_table1865
+ GCC_except_table1866
+ GCC_except_table1867
+ GCC_except_table1868
+ GCC_except_table1870
+ GCC_except_table1882
+ GCC_except_table1884
+ GCC_except_table1886
+ GCC_except_table1888
+ GCC_except_table1899
+ GCC_except_table1925
+ GCC_except_table1926
+ GCC_except_table1927
+ GCC_except_table1930
+ GCC_except_table1932
+ GCC_except_table2041
+ GCC_except_table2044
+ GCC_except_table2046
+ GCC_except_table2047
+ GCC_except_table2048
+ GCC_except_table2049
+ GCC_except_table2054
+ GCC_except_table2055
+ GCC_except_table2059
+ GCC_except_table2065
+ GCC_except_table2066
+ GCC_except_table2067
+ GCC_except_table2068
+ GCC_except_table2070
+ GCC_except_table2072
+ GCC_except_table2073
+ GCC_except_table2074
+ GCC_except_table2075
+ GCC_except_table2077
+ GCC_except_table2082
+ GCC_except_table2148
+ GCC_except_table2149
+ GCC_except_table2156
+ GCC_except_table2226
+ GCC_except_table2240
+ GCC_except_table2242
+ GCC_except_table2243
+ GCC_except_table2270
+ GCC_except_table2271
+ GCC_except_table2289
+ GCC_except_table2290
+ GCC_except_table2291
+ GCC_except_table2292
+ GCC_except_table2293
+ GCC_except_table2298
+ GCC_except_table2300
+ GCC_except_table2301
+ GCC_except_table2312
+ GCC_except_table2313
+ GCC_except_table2318
+ GCC_except_table2319
+ GCC_except_table2322
+ GCC_except_table2335
+ GCC_except_table2338
+ GCC_except_table2379
+ GCC_except_table2380
+ GCC_except_table2381
+ GCC_except_table2382
+ GCC_except_table2384
+ GCC_except_table2387
+ GCC_except_table2388
+ GCC_except_table2415
+ GCC_except_table2418
+ GCC_except_table2427
+ GCC_except_table2436
+ GCC_except_table2439
+ GCC_except_table2441
+ GCC_except_table2446
+ GCC_except_table2449
+ GCC_except_table2456
+ GCC_except_table2458
+ GCC_except_table2460
+ GCC_except_table2478
+ GCC_except_table2479
+ GCC_except_table2484
+ GCC_except_table2494
+ GCC_except_table2495
+ GCC_except_table2496
+ GCC_except_table2498
+ GCC_except_table2499
+ GCC_except_table2504
+ GCC_except_table2505
+ GCC_except_table2506
+ GCC_except_table2507
+ GCC_except_table2508
+ GCC_except_table2509
+ GCC_except_table2510
+ GCC_except_table2511
+ GCC_except_table2514
+ GCC_except_table2517
+ GCC_except_table2518
+ GCC_except_table2519
+ GCC_except_table2521
+ GCC_except_table2526
+ GCC_except_table2528
+ GCC_except_table2529
+ GCC_except_table2530
+ GCC_except_table2533
+ GCC_except_table2534
+ GCC_except_table2539
+ GCC_except_table2540
+ GCC_except_table2547
+ GCC_except_table2549
+ GCC_except_table2550
+ GCC_except_table2562
+ GCC_except_table2563
+ GCC_except_table2567
+ GCC_except_table2568
+ GCC_except_table2569
+ GCC_except_table2572
+ GCC_except_table2573
+ GCC_except_table2574
+ GCC_except_table2942
+ GCC_except_table2947
+ GCC_except_table3019
+ GCC_except_table3023
+ GCC_except_table3027
+ GCC_except_table3030
+ GCC_except_table3050
+ GCC_except_table3062
+ GCC_except_table3072
+ GCC_except_table3074
+ GCC_except_table3076
+ GCC_except_table3078
+ GCC_except_table3079
+ GCC_except_table3080
+ GCC_except_table3081
+ GCC_except_table3082
+ GCC_except_table3083
+ GCC_except_table3084
+ GCC_except_table3086
+ GCC_except_table3098
+ GCC_except_table3113
+ GCC_except_table3114
+ GCC_except_table3123
+ GCC_except_table3137
+ GCC_except_table3169
+ GCC_except_table3170
+ GCC_except_table3172
+ GCC_except_table3173
+ GCC_except_table3174
+ GCC_except_table3196
+ GCC_except_table3198
+ GCC_except_table3199
+ GCC_except_table3200
+ GCC_except_table3201
+ GCC_except_table3211
+ GCC_except_table3213
+ GCC_except_table3243
+ GCC_except_table3246
+ GCC_except_table3247
+ GCC_except_table3248
+ GCC_except_table3249
+ GCC_except_table3258
+ GCC_except_table3265
+ GCC_except_table3270
+ GCC_except_table3303
+ GCC_except_table3308
+ GCC_except_table3309
+ GCC_except_table3450
+ GCC_except_table417
+ GCC_except_table419
+ GCC_except_table420
+ GCC_except_table421
+ GCC_except_table422
+ GCC_except_table423
+ GCC_except_table424
+ GCC_except_table431
+ GCC_except_table440
+ GCC_except_table441
+ GCC_except_table442
+ GCC_except_table444
+ GCC_except_table448
+ GCC_except_table457
+ GCC_except_table468
+ GCC_except_table480
+ GCC_except_table481
+ GCC_except_table483
+ GCC_except_table486
+ GCC_except_table490
+ GCC_except_table492
+ GCC_except_table502
+ GCC_except_table518
+ GCC_except_table526
+ GCC_except_table539
+ GCC_except_table546
+ GCC_except_table583
+ GCC_except_table584
+ GCC_except_table585
+ GCC_except_table589
+ GCC_except_table616
+ GCC_except_table620
+ GCC_except_table621
+ GCC_except_table631
+ GCC_except_table633
+ GCC_except_table638
+ GCC_except_table640
+ GCC_except_table660
+ GCC_except_table667
+ GCC_except_table713
+ GCC_except_table714
+ GCC_except_table715
+ GCC_except_table716
+ GCC_except_table718
+ GCC_except_table722
+ GCC_except_table725
+ GCC_except_table727
+ GCC_except_table729
+ GCC_except_table730
+ GCC_except_table735
+ GCC_except_table737
+ GCC_except_table739
+ GCC_except_table740
+ GCC_except_table741
+ GCC_except_table747
+ GCC_except_table750
+ GCC_except_table751
+ GCC_except_table752
+ GCC_except_table753
+ GCC_except_table754
+ GCC_except_table758
+ GCC_except_table759
+ GCC_except_table760
+ GCC_except_table767
+ GCC_except_table768
+ GCC_except_table769
+ GCC_except_table772
+ GCC_except_table778
+ GCC_except_table781
+ GCC_except_table785
+ GCC_except_table786
+ GCC_except_table789
+ GCC_except_table791
+ GCC_except_table811
+ GCC_except_table820
+ GCC_except_table821
+ GCC_except_table830
+ GCC_except_table832
+ GCC_except_table833
+ GCC_except_table834
+ GCC_except_table859
+ GCC_except_table862
+ GCC_except_table863
+ GCC_except_table864
+ GCC_except_table882
+ GCC_except_table884
+ GCC_except_table886
+ GCC_except_table897
+ GCC_except_table898
+ GCC_except_table901
+ GCC_except_table903
+ GCC_except_table919
+ GCC_except_table925
+ GCC_except_table931
+ GCC_except_table932
+ GCC_except_table946
+ GCC_except_table955
+ GCC_except_table956
+ GCC_except_table958
+ GCC_except_table959
+ GCC_except_table968
+ GCC_except_table969
+ GCC_except_table971
+ GCC_except_table973
+ GCC_except_table976
+ GCC_except_table984
+ GCC_except_table994
+ _ApplyMTL4ColorAttachmentSpecialization
+ _CompareArgumentTableUse
+ _DYTraceDecode_MTL4CommandBuffer_resolveCounterHeap_withRange_intoBuffer_atOffset_waitFence_updateFence
+ _DYTraceDecode_MTL4CommandBuffer_resolveCounterHeap_withRange_intoBuffer_waitFence_updateFence
+ _DYTraceDecode_MTL4CommandBuffer_writeTimestampIntoHeap_atIndex
+ _DYTraceDecode_MTL4Compiler_newRenderPipelineStateBySpecializationWithDescriptor_pipeline_completionHandler
+ _DYTraceDecode_MTL4Compiler_newRenderPipelineStateBySpecializationWithDescriptor_pipeline_error
+ _DYTraceDecode_MTL4ComputeCommandEncoder_writeTimestampWithGranularity_intoHeap_atIndex
+ _DYTraceDecode_MTL4CounterHeap_dealloc
+ _DYTraceDecode_MTL4CounterHeap_invalidateCounterRange
+ _DYTraceDecode_MTL4CounterHeap_resolveCounterRange
+ _DYTraceDecode_MTL4CounterHeap_setLabel
+ _DYTraceDecode_MTL4RenderCommandEncoder_writeTimestampWithGranularity_afterStage_intoHeap_atIndex
+ _DYTraceDecode_MTLDevice_newCounterHeapWithDescriptor_error
+ _DecodeDYMTL4CounterHeapDescriptor
+ _GTCaptureArchive_openSeparateFile
+ _GTSMMTL4Context_getFrameInterpolators
+ _GTSMMTL4Context_getSpatialScalers
+ _GTSMMTL4Context_getTemporalDenoisedScalers
+ _GTSMMTL4Context_getTemporalScalers
+ _GTSMMTL4CounterHeap_init
+ _GTSMMTL4CounterHeap_processTraceFuncWithMap
+ _GTSMMTLBuilder_mtl4CounterHeap
+ _GTSMMTLContext_getMTL4CounterHeaps
+ _GTSMMTLRenderPipelineStateResolved_hasFragmentFunction
+ _GTSMMTLRenderPipelineStateResolved_hasObjectFunction
+ _GTSMMTLRenderPipelineStateResolved_mtl4MeshRender
+ _GTSMMTLRenderPipelineStateResolved_mtl4Render
+ _GTSMMTLRenderPipelineStateResolved_rasterSampleCount
+ _GTSMMTLRenderPipelineState_MTL4TilePipelineDescriptor
+ _GTSMMTLRenderPipelineState_resolve
+ _GTTraceContext_cleanup
+ _MakeMTL4CounterHeapDescriptor
+ _MakeScratchTensorDescriptor
+ _OBJC_CLASS_$_GTReplayFetchCounterHeap
+ _OBJC_CLASS_$_GTReplayMTLFXFrameInterpolator
+ _OBJC_CLASS_$_MTL4CounterHeapDescriptor
+ _OBJC_IVAR_$_GTMTLReplayObjectMap._mtl4CounterHeaps
+ _OBJC_METACLASS_$_GTReplayMTLFXFrameInterpolator
+ _ResolveMTL4ColorAttachmentDefaults
+ _StoreMTL4CounterHeapDescriptorUsingDecode
+ __OBJC_$_CLASS_METHODS_GTReplayMTLFXFrameInterpolator
+ __OBJC_$_INSTANCE_METHODS_GTReplayMTLFXFrameInterpolator
+ __OBJC_$_PROP_LIST_GTReplayMTLFXFrameInterpolator
+ __OBJC_$_PROP_LIST_MTLFXFrameInterpolatorBase
+ __OBJC_$_PROP_LIST_MTLFXFrameInterpolatorSPI
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLFXFrameInterpolator
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLFXFrameInterpolatorBase
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLFXFrameInterpolatorSPI
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLFXFrameInterpolator
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLFXFrameInterpolatorBase
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLFXFrameInterpolatorSPI
+ __OBJC_$_PROTOCOL_REFS_MTLFXFrameInterpolator
+ __OBJC_$_PROTOCOL_REFS_MTLFXFrameInterpolatorBase
+ __OBJC_$_PROTOCOL_REFS_MTLFXFrameInterpolatorSPI
+ __OBJC_CLASS_PROTOCOLS_$_GTReplayMTLFXFrameInterpolator
+ __OBJC_CLASS_RO_$_GTReplayMTLFXFrameInterpolator
+ __OBJC_LABEL_PROTOCOL_$_MTLFXFrameInterpolator
+ __OBJC_LABEL_PROTOCOL_$_MTLFXFrameInterpolatorBase
+ __OBJC_LABEL_PROTOCOL_$_MTLFXFrameInterpolatorSPI
+ __OBJC_METACLASS_RO_$_GTReplayMTLFXFrameInterpolator
+ __OBJC_PROTOCOL_$_MTLFXFrameInterpolator
+ __OBJC_PROTOCOL_$_MTLFXFrameInterpolatorBase
+ __OBJC_PROTOCOL_$_MTLFXFrameInterpolatorSPI
+ __ZL29ShouldInstrumentFragmentStageP21GTMTLReplayControllerRK22GTMTLIndirectResourcesPK11GTTraceFuncyP10apr_pool_t
+ __ZL30ShouldInstrumentICBObjectStageP21GTMTLReplayControllerPK11GTTraceFuncyP10apr_pool_t
+ ___NewResourceData_block_invoke_4
+ _objc_msgSend$aspectRatio
+ _objc_msgSend$compositedUITexture
+ _objc_msgSend$contentHeight
+ _objc_msgSend$contentWidth
+ _objc_msgSend$deltaTime
+ _objc_msgSend$distortionHeight
+ _objc_msgSend$distortionOffsetX
+ _objc_msgSend$distortionOffsetY
+ _objc_msgSend$distortionTexture
+ _objc_msgSend$distortionWidth
+ _objc_msgSend$farPlane
+ _objc_msgSend$fieldOfView
+ _objc_msgSend$invalidateCounterRange:
+ _objc_msgSend$isUITextureComposited
+ _objc_msgSend$mtl4CounterHeapForKey:
+ _objc_msgSend$nearPlane
+ _objc_msgSend$newCounterHeapWithDescriptor:error:
+ _objc_msgSend$newRenderPipelineStateBySpecializationWithDescriptor:pipeline:error:
+ _objc_msgSend$prevColorTexture
+ _objc_msgSend$queryTimestampFrequency
+ _objc_msgSend$removeMTL4CounterHeapForKey:
+ _objc_msgSend$resolveCounterHeap:withRange:intoBuffer:atOffset:waitFence:updateFence:
+ _objc_msgSend$resolveCounterHeap:withRange:intoBuffer:waitFence:updateFence:
+ _objc_msgSend$scalesPlaneTensorAlias:dataPlaneOffset:
+ _objc_msgSend$setCompositedUITexture:
+ _objc_msgSend$setCount:
+ _objc_msgSend$setMTL4CounterHeap:forKey:
+ _objc_msgSend$uiTexture
+ _objc_msgSend$uiTextureFormat
+ _objc_msgSend$uiTextureUsage
+ _objc_msgSend$writeTimestampIntoHeap:atIndex:
+ _objc_msgSend$writeTimestampWithGranularity:afterStage:intoHeap:atIndex:
+ _objc_msgSend$writeTimestampWithGranularity:intoHeap:atIndex:
+ _openat
- +[GTReplayMTL4FXTemporalDenoisedScaler wrapperWithDevice:descriptor:compiler:]
- +[GTReplayMTL4FXTemporalScaler wrapperWithDevice:descriptor:compiler:]
- -[GTReplayMTL4FXTemporalDenoisedScaler colorTextureBarrierStages]
- -[GTReplayMTL4FXTemporalDenoisedScaler colorTextureFormat]
- -[GTReplayMTL4FXTemporalDenoisedScaler colorTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler colorTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler debugTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler denoiseStrengthMaskTextureFormat]
- -[GTReplayMTL4FXTemporalDenoisedScaler denoiseStrengthMaskTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler denoiseStrengthMaskTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler depthTextureFormat]
- -[GTReplayMTL4FXTemporalDenoisedScaler depthTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler depthTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler diffuseAlbedoTextureFormat]
- -[GTReplayMTL4FXTemporalDenoisedScaler diffuseAlbedoTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler diffuseAlbedoTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler dilatedMotionVectors]
- -[GTReplayMTL4FXTemporalDenoisedScaler encodeToCommandBuffer:]
- -[GTReplayMTL4FXTemporalDenoisedScaler exposureTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler fence]
- -[GTReplayMTL4FXTemporalDenoisedScaler initWithDevice:descriptor:compiler:]
- -[GTReplayMTL4FXTemporalDenoisedScaler inputContentHeight]
- -[GTReplayMTL4FXTemporalDenoisedScaler inputContentMaxScale]
- -[GTReplayMTL4FXTemporalDenoisedScaler inputContentMinScale]
- -[GTReplayMTL4FXTemporalDenoisedScaler inputContentWidth]
- -[GTReplayMTL4FXTemporalDenoisedScaler inputHeight]
- -[GTReplayMTL4FXTemporalDenoisedScaler inputWidth]
- -[GTReplayMTL4FXTemporalDenoisedScaler isDepthReversed]
- -[GTReplayMTL4FXTemporalDenoisedScaler jitterOffsetX]
- -[GTReplayMTL4FXTemporalDenoisedScaler jitterOffsetY]
- -[GTReplayMTL4FXTemporalDenoisedScaler motionTextureFormat]
- -[GTReplayMTL4FXTemporalDenoisedScaler motionTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler motionTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler motionVectorScaleX]
- -[GTReplayMTL4FXTemporalDenoisedScaler motionVectorScaleY]
- -[GTReplayMTL4FXTemporalDenoisedScaler normalTextureFormat]
- -[GTReplayMTL4FXTemporalDenoisedScaler normalTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler normalTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler outputHeight]
- -[GTReplayMTL4FXTemporalDenoisedScaler outputTextureBarrierStages]
- -[GTReplayMTL4FXTemporalDenoisedScaler outputTextureFormat]
- -[GTReplayMTL4FXTemporalDenoisedScaler outputTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler outputTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler outputWidth]
- -[GTReplayMTL4FXTemporalDenoisedScaler preExposure]
- -[GTReplayMTL4FXTemporalDenoisedScaler reactiveMaskTextureFormat]
- -[GTReplayMTL4FXTemporalDenoisedScaler reactiveMaskTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler reactiveMaskTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler reactiveTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler reset]
- -[GTReplayMTL4FXTemporalDenoisedScaler roughnessTextureFormat]
- -[GTReplayMTL4FXTemporalDenoisedScaler roughnessTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler roughnessTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler setColorTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setColorTextureBarrierStages:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setDebugTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setDenoiseStrengthMaskTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setDepthReversed:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setDepthTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setDiffuseAlbedoTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setExposureTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setFence:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setInputContentHeight:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setInputContentWidth:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setJitterOffsetX:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setJitterOffsetY:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setMotionTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setMotionVectorScaleX:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setMotionVectorScaleY:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setNormalTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setOutputTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setPreExposure:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setReactiveMaskTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setReset:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setRoughnessTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setShouldResetHistory:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setSpecularAlbedoTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setSpecularHitDistanceTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setTransparencyOverlayTexture:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setViewToClipMatrix:]
- -[GTReplayMTL4FXTemporalDenoisedScaler setWorldToViewMatrix:]
- -[GTReplayMTL4FXTemporalDenoisedScaler shouldResetHistory]
- -[GTReplayMTL4FXTemporalDenoisedScaler specularAlbedoTextureFormat]
- -[GTReplayMTL4FXTemporalDenoisedScaler specularAlbedoTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler specularAlbedoTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler specularHitDistanceTextureFormat]
- -[GTReplayMTL4FXTemporalDenoisedScaler specularHitDistanceTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler specularHitDistanceTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler transparencyOverlayTextureFormat]
- -[GTReplayMTL4FXTemporalDenoisedScaler transparencyOverlayTextureUsage]
- -[GTReplayMTL4FXTemporalDenoisedScaler transparencyOverlayTexture]
- -[GTReplayMTL4FXTemporalDenoisedScaler viewToClipMatrix]
- -[GTReplayMTL4FXTemporalDenoisedScaler worldToViewMatrix]
- -[GTReplayMTL4FXTemporalScaler colorContentOffsetX]
- -[GTReplayMTL4FXTemporalScaler colorContentOffsetY]
- -[GTReplayMTL4FXTemporalScaler colorTextureBarrierStages]
- -[GTReplayMTL4FXTemporalScaler colorTextureFormat]
- -[GTReplayMTL4FXTemporalScaler colorTextureUsage]
- -[GTReplayMTL4FXTemporalScaler colorTexture]
- -[GTReplayMTL4FXTemporalScaler currentViewToClipMatrix]
- -[GTReplayMTL4FXTemporalScaler currentWorldToViewMatrix]
- -[GTReplayMTL4FXTemporalScaler debugTexture]
- -[GTReplayMTL4FXTemporalScaler depthContentOffsetX]
- -[GTReplayMTL4FXTemporalScaler depthContentOffsetY]
- -[GTReplayMTL4FXTemporalScaler depthTextureFormat]
- -[GTReplayMTL4FXTemporalScaler depthTextureUsage]
- -[GTReplayMTL4FXTemporalScaler depthTexture]
- -[GTReplayMTL4FXTemporalScaler dilatedMotionVectors]
- -[GTReplayMTL4FXTemporalScaler encodeToCommandBuffer:]
- -[GTReplayMTL4FXTemporalScaler exposureTexture]
- -[GTReplayMTL4FXTemporalScaler fence]
- -[GTReplayMTL4FXTemporalScaler initWithDevice:descriptor:compiler:]
- -[GTReplayMTL4FXTemporalScaler inputContentHeight]
- -[GTReplayMTL4FXTemporalScaler inputContentMaxScale]
- -[GTReplayMTL4FXTemporalScaler inputContentMinScale]
- -[GTReplayMTL4FXTemporalScaler inputContentWidth]
- -[GTReplayMTL4FXTemporalScaler inputHeight]
- -[GTReplayMTL4FXTemporalScaler inputWidth]
- -[GTReplayMTL4FXTemporalScaler isDepthReversed]
- -[GTReplayMTL4FXTemporalScaler jitterOffsetX]
- -[GTReplayMTL4FXTemporalScaler jitterOffsetY]
- -[GTReplayMTL4FXTemporalScaler motionContentOffsetX]
- -[GTReplayMTL4FXTemporalScaler motionContentOffsetY]
- -[GTReplayMTL4FXTemporalScaler motionTextureFormat]
- -[GTReplayMTL4FXTemporalScaler motionTextureUsage]
- -[GTReplayMTL4FXTemporalScaler motionTexture]
- -[GTReplayMTL4FXTemporalScaler motionVectorScaleX]
- -[GTReplayMTL4FXTemporalScaler motionVectorScaleY]
- -[GTReplayMTL4FXTemporalScaler outputHeight]
- -[GTReplayMTL4FXTemporalScaler outputOffsetX]
- -[GTReplayMTL4FXTemporalScaler outputOffsetY]
- -[GTReplayMTL4FXTemporalScaler outputTextureBarrierStages]
- -[GTReplayMTL4FXTemporalScaler outputTextureFormat]
- -[GTReplayMTL4FXTemporalScaler outputTextureUsage]
- -[GTReplayMTL4FXTemporalScaler outputTexture]
- -[GTReplayMTL4FXTemporalScaler outputWidth]
- -[GTReplayMTL4FXTemporalScaler preExposure]
- -[GTReplayMTL4FXTemporalScaler previousJitterOffset]
- -[GTReplayMTL4FXTemporalScaler previousViewToClipMatrix]
- -[GTReplayMTL4FXTemporalScaler previousWorldToViewMatrix]
- -[GTReplayMTL4FXTemporalScaler reactiveMaskContentOffsetX]
- -[GTReplayMTL4FXTemporalScaler reactiveMaskContentOffsetY]
- -[GTReplayMTL4FXTemporalScaler reactiveMaskTextureFormat]
- -[GTReplayMTL4FXTemporalScaler reactiveMaskTextureUsage]
- -[GTReplayMTL4FXTemporalScaler reactiveMaskTexture]
- -[GTReplayMTL4FXTemporalScaler reactiveTextureUsage]
- -[GTReplayMTL4FXTemporalScaler reset]
- -[GTReplayMTL4FXTemporalScaler setColorContentOffsetX:]
- -[GTReplayMTL4FXTemporalScaler setColorContentOffsetY:]
- -[GTReplayMTL4FXTemporalScaler setColorTexture:]
- -[GTReplayMTL4FXTemporalScaler setColorTextureBarrierStages:]
- -[GTReplayMTL4FXTemporalScaler setCurrentViewToClipMatrix:]
- -[GTReplayMTL4FXTemporalScaler setCurrentWorldToViewMatrix:]
- -[GTReplayMTL4FXTemporalScaler setDebugTexture:]
- -[GTReplayMTL4FXTemporalScaler setDepthContentOffsetX:]
- -[GTReplayMTL4FXTemporalScaler setDepthContentOffsetY:]
- -[GTReplayMTL4FXTemporalScaler setDepthReversed:]
- -[GTReplayMTL4FXTemporalScaler setDepthTexture:]
- -[GTReplayMTL4FXTemporalScaler setExposureTexture:]
- -[GTReplayMTL4FXTemporalScaler setFence:]
- -[GTReplayMTL4FXTemporalScaler setInputContentHeight:]
- -[GTReplayMTL4FXTemporalScaler setInputContentWidth:]
- -[GTReplayMTL4FXTemporalScaler setJitterOffsetX:]
- -[GTReplayMTL4FXTemporalScaler setJitterOffsetY:]
- -[GTReplayMTL4FXTemporalScaler setMotionContentOffsetX:]
- -[GTReplayMTL4FXTemporalScaler setMotionContentOffsetY:]
- -[GTReplayMTL4FXTemporalScaler setMotionTexture:]
- -[GTReplayMTL4FXTemporalScaler setMotionVectorScaleX:]
- -[GTReplayMTL4FXTemporalScaler setMotionVectorScaleY:]
- -[GTReplayMTL4FXTemporalScaler setOutputOffsetX:]
- -[GTReplayMTL4FXTemporalScaler setOutputOffsetY:]
- -[GTReplayMTL4FXTemporalScaler setOutputTexture:]
- -[GTReplayMTL4FXTemporalScaler setPreExposure:]
- -[GTReplayMTL4FXTemporalScaler setPreviousJitterOffset:]
- -[GTReplayMTL4FXTemporalScaler setPreviousViewToClipMatrix:]
- -[GTReplayMTL4FXTemporalScaler setPreviousWorldToViewMatrix:]
- -[GTReplayMTL4FXTemporalScaler setReactiveMaskContentOffsetX:]
- -[GTReplayMTL4FXTemporalScaler setReactiveMaskContentOffsetY:]
- -[GTReplayMTL4FXTemporalScaler setReactiveMaskTexture:]
- -[GTReplayMTL4FXTemporalScaler setReset:]
- GCC_except_table1006
- GCC_except_table1007
- GCC_except_table1008
- GCC_except_table1012
- GCC_except_table1013
- GCC_except_table1019
- GCC_except_table1020
- GCC_except_table1034
- GCC_except_table1035
- GCC_except_table1038
- GCC_except_table1042
- GCC_except_table1044
- GCC_except_table1046
- GCC_except_table1047
- GCC_except_table1055
- GCC_except_table1056
- GCC_except_table1057
- GCC_except_table1059
- GCC_except_table1061
- GCC_except_table1062
- GCC_except_table1064
- GCC_except_table1072
- GCC_except_table1074
- GCC_except_table1075
- GCC_except_table1077
- GCC_except_table1079
- GCC_except_table1082
- GCC_except_table1091
- GCC_except_table1092
- GCC_except_table1103
- GCC_except_table1111
- GCC_except_table1112
- GCC_except_table1131
- GCC_except_table1261
- GCC_except_table1279
- GCC_except_table1282
- GCC_except_table1285
- GCC_except_table1287
- GCC_except_table1322
- GCC_except_table1324
- GCC_except_table1350
- GCC_except_table1356
- GCC_except_table1379
- GCC_except_table1380
- GCC_except_table1381
- GCC_except_table1382
- GCC_except_table1387
- GCC_except_table1388
- GCC_except_table1415
- GCC_except_table1419
- GCC_except_table1420
- GCC_except_table1421
- GCC_except_table1422
- GCC_except_table1423
- GCC_except_table1426
- GCC_except_table1439
- GCC_except_table1442
- GCC_except_table1447
- GCC_except_table1448
- GCC_except_table1449
- GCC_except_table1450
- GCC_except_table1451
- GCC_except_table1452
- GCC_except_table1456
- GCC_except_table1460
- GCC_except_table1461
- GCC_except_table1477
- GCC_except_table1481
- GCC_except_table1482
- GCC_except_table1483
- GCC_except_table1484
- GCC_except_table1485
- GCC_except_table1486
- GCC_except_table1489
- GCC_except_table1491
- GCC_except_table1494
- GCC_except_table1495
- GCC_except_table1497
- GCC_except_table1509
- GCC_except_table1512
- GCC_except_table1513
- GCC_except_table1514
- GCC_except_table1517
- GCC_except_table1518
- GCC_except_table1521
- GCC_except_table1523
- GCC_except_table1525
- GCC_except_table1526
- GCC_except_table1531
- GCC_except_table1544
- GCC_except_table1547
- GCC_except_table1548
- GCC_except_table1551
- GCC_except_table1552
- GCC_except_table1553
- GCC_except_table1554
- GCC_except_table1555
- GCC_except_table1556
- GCC_except_table1557
- GCC_except_table1558
- GCC_except_table1559
- GCC_except_table1560
- GCC_except_table1565
- GCC_except_table1596
- GCC_except_table1609
- GCC_except_table1613
- GCC_except_table1625
- GCC_except_table1693
- GCC_except_table1810
- GCC_except_table1834
- GCC_except_table1835
- GCC_except_table1915
- GCC_except_table1946
- GCC_except_table1947
- GCC_except_table1948
- GCC_except_table1949
- GCC_except_table1950
- GCC_except_table1951
- GCC_except_table1952
- GCC_except_table1953
- GCC_except_table1955
- GCC_except_table1967
- GCC_except_table1969
- GCC_except_table1971
- GCC_except_table1973
- GCC_except_table1975
- GCC_except_table1984
- GCC_except_table2010
- GCC_except_table2011
- GCC_except_table2012
- GCC_except_table2015
- GCC_except_table2017
- GCC_except_table2129
- GCC_except_table2131
- GCC_except_table2132
- GCC_except_table2133
- GCC_except_table2134
- GCC_except_table2139
- GCC_except_table2140
- GCC_except_table2144
- GCC_except_table2155
- GCC_except_table2157
- GCC_except_table2158
- GCC_except_table2159
- GCC_except_table2160
- GCC_except_table2162
- GCC_except_table2167
- GCC_except_table2211
- GCC_except_table2233
- GCC_except_table2234
- GCC_except_table2235
- GCC_except_table2236
- GCC_except_table2237
- GCC_except_table2238
- GCC_except_table2311
- GCC_except_table2355
- GCC_except_table2356
- GCC_except_table2375
- GCC_except_table2377
- GCC_except_table2386
- GCC_except_table2397
- GCC_except_table2403
- GCC_except_table2404
- GCC_except_table2407
- GCC_except_table2410
- GCC_except_table2411
- GCC_except_table2412
- GCC_except_table2413
- GCC_except_table2420
- GCC_except_table2423
- GCC_except_table2461
- GCC_except_table2463
- GCC_except_table2464
- GCC_except_table2469
- GCC_except_table2473
- GCC_except_table2483
- GCC_except_table2500
- GCC_except_table2516
- GCC_except_table2522
- GCC_except_table2535
- GCC_except_table2542
- GCC_except_table2546
- GCC_except_table2551
- GCC_except_table2552
- GCC_except_table2553
- GCC_except_table2554
- GCC_except_table2558
- GCC_except_table2580
- GCC_except_table2582
- GCC_except_table2584
- GCC_except_table2585
- GCC_except_table2589
- GCC_except_table2590
- GCC_except_table2591
- GCC_except_table2592
- GCC_except_table2593
- GCC_except_table2594
- GCC_except_table2595
- GCC_except_table2596
- GCC_except_table2597
- GCC_except_table2598
- GCC_except_table2600
- GCC_except_table2603
- GCC_except_table2604
- GCC_except_table2605
- GCC_except_table2607
- GCC_except_table2611
- GCC_except_table2612
- GCC_except_table2613
- GCC_except_table2614
- GCC_except_table2615
- GCC_except_table2616
- GCC_except_table2618
- GCC_except_table2619
- GCC_except_table2620
- GCC_except_table2625
- GCC_except_table2626
- GCC_except_table2630
- GCC_except_table2631
- GCC_except_table2633
- GCC_except_table2635
- GCC_except_table2636
- GCC_except_table2642
- GCC_except_table2648
- GCC_except_table2649
- GCC_except_table2650
- GCC_except_table2651
- GCC_except_table2653
- GCC_except_table2654
- GCC_except_table2655
- GCC_except_table2656
- GCC_except_table2658
- GCC_except_table2659
- GCC_except_table2660
- GCC_except_table2667
- GCC_except_table3100
- GCC_except_table3104
- GCC_except_table3108
- GCC_except_table3111
- GCC_except_table3143
- GCC_except_table3153
- GCC_except_table3155
- GCC_except_table3157
- GCC_except_table3159
- GCC_except_table3161
- GCC_except_table3162
- GCC_except_table3163
- GCC_except_table3164
- GCC_except_table3165
- GCC_except_table3167
- GCC_except_table3179
- GCC_except_table3194
- GCC_except_table3218
- GCC_except_table3241
- GCC_except_table3253
- GCC_except_table3254
- GCC_except_table3255
- GCC_except_table3276
- GCC_except_table3277
- GCC_except_table3279
- GCC_except_table3280
- GCC_except_table3281
- GCC_except_table3282
- GCC_except_table3292
- GCC_except_table3293
- GCC_except_table3294
- GCC_except_table3324
- GCC_except_table3327
- GCC_except_table3328
- GCC_except_table3329
- GCC_except_table3330
- GCC_except_table3331
- GCC_except_table3332
- GCC_except_table3339
- GCC_except_table3346
- GCC_except_table3351
- GCC_except_table3384
- GCC_except_table3389
- GCC_except_table3390
- GCC_except_table3531
- GCC_except_table505
- GCC_except_table507
- GCC_except_table508
- GCC_except_table509
- GCC_except_table510
- GCC_except_table512
- GCC_except_table519
- GCC_except_table528
- GCC_except_table532
- GCC_except_table536
- GCC_except_table545
- GCC_except_table568
- GCC_except_table569
- GCC_except_table571
- GCC_except_table574
- GCC_except_table580
- GCC_except_table590
- GCC_except_table599
- GCC_except_table606
- GCC_except_table614
- GCC_except_table617
- GCC_except_table618
- GCC_except_table627
- GCC_except_table634
- GCC_except_table644
- GCC_except_table666
- GCC_except_table671
- GCC_except_table672
- GCC_except_table677
- GCC_except_table704
- GCC_except_table755
- GCC_except_table796
- GCC_except_table797
- GCC_except_table801
- GCC_except_table802
- GCC_except_table803
- GCC_except_table804
- GCC_except_table806
- GCC_except_table807
- GCC_except_table809
- GCC_except_table810
- GCC_except_table813
- GCC_except_table814
- GCC_except_table815
- GCC_except_table816
- GCC_except_table817
- GCC_except_table818
- GCC_except_table823
- GCC_except_table825
- GCC_except_table827
- GCC_except_table839
- GCC_except_table840
- GCC_except_table841
- GCC_except_table842
- GCC_except_table848
- GCC_except_table849
- GCC_except_table855
- GCC_except_table860
- GCC_except_table869
- GCC_except_table916
- GCC_except_table917
- GCC_except_table921
- GCC_except_table922
- GCC_except_table923
- GCC_except_table926
- GCC_except_table934
- GCC_except_table944
- GCC_except_table945
- GCC_except_table951
- GCC_except_table952
- GCC_except_table962
- GCC_except_table965
- GCC_except_table970
- GCC_except_table972
- GCC_except_table985
- GCC_except_table996
- GCC_except_table997
- _DYTraceDecode_MTL4FXTemporalScaler_executionMode
- _GTCaptureArchive_confinedSeparateFilePath
- _GTFenum_isSetArgumentTable
- _GTFileSystem_open
- _GTSMMTLRenderPipelineState_fragmentFunction
- _GTSMMTLRenderPipelineState_rasterSampleCount
- _GTTraceDispatch_createArgumentTableStateMapFromParams
- _GTTraceDispatch_reconstructArgumentTableState
- _GTTraceDispatch_setArgumentTableStateForGPUCommandStage
- _OBJC_CLASS_$_GTReplayMTL4FXTemporalDenoisedScaler
- _OBJC_CLASS_$_GTReplayMTL4FXTemporalScaler
- _OBJC_METACLASS_$_GTReplayMTL4FXTemporalDenoisedScaler
- _OBJC_METACLASS_$_GTReplayMTL4FXTemporalScaler
- __OBJC_$_CLASS_METHODS_GTReplayMTL4FXTemporalDenoisedScaler
- __OBJC_$_CLASS_METHODS_GTReplayMTL4FXTemporalScaler
- __OBJC_$_INSTANCE_METHODS_GTReplayMTL4FXTemporalDenoisedScaler
- __OBJC_$_INSTANCE_METHODS_GTReplayMTL4FXTemporalScaler
- __OBJC_$_PROP_LIST_GTReplayMTL4FXTemporalDenoisedScaler
- __OBJC_$_PROP_LIST_GTReplayMTL4FXTemporalScaler
- __OBJC_$_PROP_LIST_MTL4FXTemporalDenoisedScalerSPI
- __OBJC_$_PROP_LIST_MTL4FXTemporalScalerSPI
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTL4FXTemporalDenoisedScaler
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTL4FXTemporalDenoisedScalerSPI
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTL4FXTemporalScaler
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTL4FXTemporalScalerSPI
- __OBJC_$_PROTOCOL_METHOD_TYPES_MTL4FXTemporalDenoisedScaler
- __OBJC_$_PROTOCOL_METHOD_TYPES_MTL4FXTemporalDenoisedScalerSPI
- __OBJC_$_PROTOCOL_METHOD_TYPES_MTL4FXTemporalScaler
- __OBJC_$_PROTOCOL_METHOD_TYPES_MTL4FXTemporalScalerSPI
- __OBJC_$_PROTOCOL_REFS_MTL4FXTemporalDenoisedScaler
- __OBJC_$_PROTOCOL_REFS_MTL4FXTemporalDenoisedScalerSPI
- __OBJC_$_PROTOCOL_REFS_MTL4FXTemporalScaler
- __OBJC_$_PROTOCOL_REFS_MTL4FXTemporalScalerSPI
- __OBJC_CLASS_PROTOCOLS_$_GTReplayMTL4FXTemporalDenoisedScaler
- __OBJC_CLASS_PROTOCOLS_$_GTReplayMTL4FXTemporalScaler
- __OBJC_CLASS_RO_$_GTReplayMTL4FXTemporalDenoisedScaler
- __OBJC_CLASS_RO_$_GTReplayMTL4FXTemporalScaler
- __OBJC_LABEL_PROTOCOL_$_MTL4FXTemporalDenoisedScaler
- __OBJC_LABEL_PROTOCOL_$_MTL4FXTemporalDenoisedScalerSPI
- __OBJC_LABEL_PROTOCOL_$_MTL4FXTemporalScaler
- __OBJC_LABEL_PROTOCOL_$_MTL4FXTemporalScalerSPI
- __OBJC_METACLASS_RO_$_GTReplayMTL4FXTemporalDenoisedScaler
- __OBJC_METACLASS_RO_$_GTReplayMTL4FXTemporalScaler
- __OBJC_PROTOCOL_$_MTL4FXTemporalDenoisedScaler
- __OBJC_PROTOCOL_$_MTL4FXTemporalDenoisedScalerSPI
- __OBJC_PROTOCOL_$_MTL4FXTemporalScaler
- __OBJC_PROTOCOL_$_MTL4FXTemporalScalerSPI
- __ZL29ShouldInstrumentFragmentStageP21GTMTLReplayControllerRK22GTMTLIndirectResourcesPK11GTTraceFuncy
- __ZL30ShouldInstrumentICBObjectStageP21GTMTLReplayControllerPK11GTTraceFuncy
- ___67-[GTReplayMTL4FXTemporalScaler initWithDevice:descriptor:compiler:]_block_invoke
- ___75-[GTReplayMTL4FXTemporalDenoisedScaler initWithDevice:descriptor:compiler:]_block_invoke
- ___block_descriptor_56_e8_32s40s48s_e29_"<MTL4FXTemporalScaler>"8?0l
- ___block_descriptor_56_e8_32s40s48s_e37_"<MTL4FXTemporalDenoisedScaler>"8?0l
- _apr_pool_terminate
- _apr_terminate
- _objc_msgSend$colorTextureBarrierStages
- _objc_msgSend$initWithDevice:descriptor:compiler:
- _objc_msgSend$outputTextureBarrierStages
- _objc_msgSend$wrapperWithDevice:descriptor:compiler:
CStrings:
+ "-TimestampFrequency"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GPUToolsDevice/data_source/GTDataSource_load.m:724"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GPUToolsDevice/data_source/GTDataSource_load.m:745"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GPUToolsDevice/data_source/GTDataSource_restores.c:310"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/net/GTCaptureArchive.c:283"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/net/GTCaptureArchive.c:413"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/net/GTCaptureArchive.c:712"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTMTLReplay_accessTracking.mm:6984"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTMTLReplay_accessTracking.mm:7007"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTMTLReplay_argumentBuffers.m:2102"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTMTLReplay_loadArchive.m:2478"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTMTLReplay_shaderDebugger_internal.m:2184"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTMTLReplay_shaderDebugger_internal.m:5991"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func.c:1140"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func.c:1562"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func.c:479"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10030"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10074"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10085"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10107"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10140"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10184"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10195"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10217"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10459"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10492"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10525"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10536"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10558"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10580"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10690"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10701"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10745"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10778"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10789"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10811"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10833"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10932"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10943"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10976"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10987"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:11278"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:11345"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2519"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2541"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2936"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2958"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2980"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:3002"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:3041"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:3063"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:3085"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:3107"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4260"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4517"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4550"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4610"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:471"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4710"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:482"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:493"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4959"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5069"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5080"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5146"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5196"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5207"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5262"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5328"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5372"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5394"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:549"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:571"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:6800"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:8611"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:8633"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9551"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9826"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9859"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9892"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9903"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9936"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9958"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/sm/GTSMMTLBuilder.c:2657"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/sm/GTSMMTLRenderPipelineStateResolved.c:28"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/trace/GTTraceContext.c:170"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/trackers/GTResourceBinding.m:158"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/trackers/GTResourceBinding.m:3013"
+ "0xffffc0e9"
+ "0xffffc0ea"
+ "Counter heap not found"
+ "Counter heap resolve returned nil"
+ "Harvest heap"
+ "Harvesting counter heap %llu (%s) range: %llu - %llu"
+ "MTL4CounterHeap"
+ "MTL4CounterHeap-0x%llx-Fetch"
+ "Pre-play for profiling"
+ "Rewind for profiling"
+ "file.fd >= 0"
+ "kDYFEMTL4CounterHeap_dealloc"
+ "kDYFEMTL4CounterHeap_invalidateCounterRange"
+ "kDYFEMTL4CounterHeap_resolveCounterRange"
+ "kDYFEMTL4CounterHeap_setLabel"
+ "memcmp((const char*)bytes + offset, (\"CUtt\"), sizeof(\"CUtt\")) == 0"
+ "memcmp((const char*)bytes + offset, (\"Ct@2ul@2ultt\"), sizeof(\"Ct@2ul@2ultt\")) == 0"
+ "memcmp((const char*)bytes + offset, (\"Ct@2ultultt\"), sizeof(\"Ct@2ultultt\")) == 0"
+ "memcmp((const char*)bytes + offset, (\"Culultul\"), sizeof(\"Culultul\")) == 0"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GPUToolsDevice/data_source/GTDataSource_load.m:726"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GPUToolsDevice/data_source/GTDataSource_load.m:747"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GPUToolsDevice/data_source/GTDataSource_restores.c:314"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/net/GTCaptureArchive.c:278"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/net/GTCaptureArchive.c:408"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/net/GTCaptureArchive.c:719"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTMTLReplay_accessTracking.mm:7100"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTMTLReplay_accessTracking.mm:7123"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTMTLReplay_argumentBuffers.m:2083"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTMTLReplay_loadArchive.m:2452"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTMTLReplay_shaderDebugger_internal.m:2183"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTMTLReplay_shaderDebugger_internal.m:5986"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func.c:1137"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func.c:1559"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func.c:478"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10043"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10054"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10076"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10318"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10351"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10384"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10395"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10417"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10439"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10549"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10560"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10604"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10637"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10648"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10670"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10692"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10791"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10802"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10835"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:10846"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:11137"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:11204"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2389"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2411"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2806"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2828"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2850"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2872"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2911"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2933"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2955"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:2977"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:394"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4130"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:438"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4387"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4420"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4480"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4580"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:460"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4829"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4939"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:4950"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5016"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5066"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5077"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5132"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:516"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5198"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5242"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:5264"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:538"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:6659"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:8470"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:8492"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9410"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9685"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9718"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9751"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9762"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9795"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9817"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9889"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9933"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9944"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9966"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/replayer/GTTraceFbuf2Func_mtl.c.inl:9999"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/sm/GTSMMTLBuilder.c:2613"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/trace/GTTraceContext.c:162"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/trackers/GTResourceBinding.m:157"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/trackers/GTResourceBinding.m:3012"
- "@\"<MTL4FXTemporalDenoisedScaler>\"8@?0"
- "@\"<MTL4FXTemporalScaler>\"8@?0"
- "fd > 0"
- "kDYFEMTLCommandBuffer_computeCommandEncoderWithParallelExecution"
- "kDYFEMTLComputeCommandEncoder_dispatchBarrier"
```
