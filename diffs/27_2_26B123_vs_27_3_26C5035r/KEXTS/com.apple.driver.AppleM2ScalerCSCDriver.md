## com.apple.driver.AppleM2ScalerCSCDriver

> `com.apple.driver.AppleM2ScalerCSCDriver`

```diff

-200.67.0.0.0
-  __TEXT.__const: 0xc3160
-  __TEXT.__cstring: 0x25a59
-  __TEXT_EXEC.__text: 0x13fa8c
-  __TEXT_EXEC.__auth_stubs: 0xba0
+200.74.0.0.0
+  __TEXT.__const: 0xc31f0
+  __TEXT.__cstring: 0x26088
+  __TEXT_EXEC.__text: 0x14133c
+  __TEXT_EXEC.__auth_stubs: 0xbb0
   __DATA.__data: 0x22388
   __DATA.__common: 0x2710
   __DATA.__bss: 0x2134
   __DATA_CONST.__mod_init_func: 0x698
   __DATA_CONST.__mod_term_func: 0x668
-  __DATA_CONST.__const: 0x3da68
+  __DATA_CONST.__const: 0x3db38
   __DATA_CONST.__kalloc_type: 0x4e40
   __DATA_CONST.__kalloc_var: 0x13b0
-  __DATA_CONST.__auth_got: 0x5d0
+  __DATA_CONST.__auth_got: 0x5d8
   __DATA_CONST.__got: 0xa8
   __DATA_CONST.__auth_ptr: 0x88
-  Functions: 10211
-  Symbols:   9701
-  CStrings:  3674
+  Functions: 10247
+  Symbols:   9708
+  CStrings:  3699
 
Symbols:
+ __ZN19AppleM2ScalerCSCHal31getCompressedMetadataRegionSizeEP13transformData17ChromaLumaOrAlpha12NormalPlanes
+ __ZNK19AppleM2ScalerCSCHal21validateBufferRegionsE19DestinationOrSourceP18M2ScalerCSCRequest
+ __ZNK23AppleM2ScalerCSCHalMSR821validateBufferRegionsE19DestinationOrSourceP18M2ScalerCSCRequest
+ __ZNK24AppleM2ScalerCSCHalMSR1021validateBufferRegionsE19DestinationOrSourceP18M2ScalerCSCRequest
+ __ZNK24AppleM2ScalerCSCHalMSR2521validateBufferRegionsE19DestinationOrSourceP18M2ScalerCSCRequest
+ __ZNK9IOSurface12getPlaneBaseEj
+ __ZZL15logFailedClientP26IOSurfaceAcceleratorClientP4taskP18M2ScalerCSCRequestE21kalloc_type_view_3160
+ __ZZN12ActiveWindow18obtainActiveWindowEjjjjE21kalloc_type_view_2397
+ __ZZN15ActiveWindowSet7releaseEvE21kalloc_type_view_2387
+ __ZZN19AppleM2ScalerCSCHal22clearShadowMapperCacheEjE22kalloc_type_view_11158
+ __ZZN19AppleM2ScalerCSCHal31mapShadowMapperCacheEntry_gatedE16ScalerMapperTypeP18IOMemoryDescriptorjE22kalloc_type_view_11088
+ __ZZN19AppleM2ScalerCSCHal31mapShadowMapperCacheEntry_gatedE16ScalerMapperTypeP18IOMemoryDescriptorjE22kalloc_type_view_11094
+ __ZZN19AppleM2ScalerCSCHal32updateShadowMapperCacheTTL_gatedEjyE22kalloc_type_view_11142
+ __ZZN19AppleM2ScalerCSCHal4freeEvE21kalloc_type_view_9612
+ __ZZN22AppleM2ScalerCSCDriver34setStatTransformEvent_gatedContextEP18M2ScalerCSCRequest14TransformEventE21kalloc_type_view_6469
+ __ZZN22AppleM2ScalerCSCDriver36pruneTransformStatQueue_gatedContextEvE21kalloc_type_view_6448
+ __ZZN22AppleM2ScalerCSCDriver4stopEP9IOServiceE21kalloc_type_view_1738
+ __ZZN22AppleM2ScalerCSCDriver4stopEP9IOServiceE21kalloc_type_view_1745
+ __ZZN26IOSurfaceAcceleratorClient29transformSurface_asynchronousEP20TransformSurfaceDataE20kalloc_type_view_631
+ __ZZN26IOSurfaceAcceleratorClient29transformSurface_asynchronousEP20TransformSurfaceDataE20kalloc_type_view_692
+ __ZZN26IOSurfaceAcceleratorClient40asynchronousUserClientCompletionCallbackEPvS0_E20kalloc_type_view_599
+ __ZZN27M2ScalerScalingControlMSR2326commitFilters_gatedContextEP18M2ScalerCSCRequestPA3_jPjPPK18FilterCoefficients20VerticalOrHorizontalbS4_S4_S4_ENK3$_0clE17ChromaLumaOrAlphaj
- __ZZL15logFailedClientP26IOSurfaceAcceleratorClientP4taskP18M2ScalerCSCRequestE21kalloc_type_view_3149
- __ZZN12ActiveWindow18obtainActiveWindowEjjjjE21kalloc_type_view_2319
- __ZZN15ActiveWindowSet7releaseEvE21kalloc_type_view_2309
- __ZZN19AppleM2ScalerCSCHal22clearShadowMapperCacheEjE22kalloc_type_view_11043
- __ZZN19AppleM2ScalerCSCHal31mapShadowMapperCacheEntry_gatedE16ScalerMapperTypeP18IOMemoryDescriptorjE22kalloc_type_view_10973
- __ZZN19AppleM2ScalerCSCHal31mapShadowMapperCacheEntry_gatedE16ScalerMapperTypeP18IOMemoryDescriptorjE22kalloc_type_view_10979
- __ZZN19AppleM2ScalerCSCHal32updateShadowMapperCacheTTL_gatedEjyE22kalloc_type_view_11027
- __ZZN19AppleM2ScalerCSCHal4freeEvE21kalloc_type_view_9609
- __ZZN22AppleM2ScalerCSCDriver34setStatTransformEvent_gatedContextEP18M2ScalerCSCRequest14TransformEventE21kalloc_type_view_6436
- __ZZN22AppleM2ScalerCSCDriver36pruneTransformStatQueue_gatedContextEvE21kalloc_type_view_6415
- __ZZN22AppleM2ScalerCSCDriver4stopEP9IOServiceE21kalloc_type_view_1727
- __ZZN22AppleM2ScalerCSCDriver4stopEP9IOServiceE21kalloc_type_view_1734
- __ZZN26IOSurfaceAcceleratorClient29transformSurface_asynchronousEP20TransformSurfaceDataE20kalloc_type_view_627
- __ZZN26IOSurfaceAcceleratorClient29transformSurface_asynchronousEP20TransformSurfaceDataE20kalloc_type_view_688
- __ZZN26IOSurfaceAcceleratorClient40asynchronousUserClientCompletionCallbackEPvS0_E20kalloc_type_view_595
CStrings:
+ "%s %s dimension (%u) + offset (%u) > buffer (%u)\n"
+ "%s Plane %u tile-data offset %llu is outside the %llu byte surface\n"
+ "%s Plane %u tiled write extent %llu exceeds plane tile-data size %llu (stride %llu x %llu macroblock rows)\n"
+ "%s Plane %u tiled write extent %llu exceeds the %llu bytes available at offset %llu (pitch %llu x %llu macroblock rows, plane height %llu, macroblock %llux%llu)\n"
+ "%s no memory descriptor\n"
+ "%s plane %d region offset 0x%llx + yOffset %lld rows exceeds plane limit 0x%llx / surface length 0x%llx\n"
+ "%s plane %d tile data offset 0x%llx (plane limit 0x%llx) or metadata offset 0x%llx/size 0x%llx exceeds surface length 0x%llx\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOSurfaceAccelerator/StatusDescriptorRingMSR29.cpp"
+ "Comm API outbound size %u exceeds max %zu\n"
+ "Comm API type %d in wrong slot %d (canonical %d)\n"
+ "GetDiag denied: diagnostics are debug-only\n"
+ "HCU API bad buffer: type=%s addr=%p len=%llu\n"
+ "HCU API entry header past end of buffer: headerEnd=%p bufferEnd=%p\n"
+ "HCU API entry too small: size=%u min=%zu type=%s\n"
+ "Interchange tile %ux%u is not a supported square tile size\n"
+ "SDR loadWritePointer: out-of-range write pointer from FW (ptr_value=%u -> %zu bytes, fLength=%zu); ignoring\n"
+ "[%s][%s]bin %d phase 16 gain %d != %d (2*%d + COEFFX %#x), err %+d\n"
+ "[IOSA] Discarding needs-reset SD frame_id %u, no outstanding request\n"
+ "[MSRCPU] %s log ring out of bounds (offset=%08X, size=%08X); disabling\n"
+ "[MSRCPU] main log flush exceeded iteration cap; aborting\n"
+ "[MSRCPU] prof log flush exceeded iteration cap; aborting\n"
+ "loadWritePointer"
+ "main"
+ "prof"
+ "received zero-size TransformSurfaceData\n"
+ "setProperties denied: runtime properties are debug-only\n"
+ "still waiting on thread %d\n"
+ "validateBufferRegions"
- "%s Plane %u Size %llu cannot support a stride of %llu for macroblocks height %llu\n"
- "HCU API bad entry header: headerEnd=%p bufferEnd=%p size=%u min=%zu type=%s\n"
- "given size (%llu) doesn't match TransformSurfaceData's (%lu)\n"
```
