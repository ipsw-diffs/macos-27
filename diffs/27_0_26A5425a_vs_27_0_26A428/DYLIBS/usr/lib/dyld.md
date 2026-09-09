## dyld

> `/usr/lib/dyld`

```diff

 27062.0.0.0.0
-  __TEXT.__text: 0xa5ab4
+  __TEXT.__text: 0xa5a94
   __TEXT.__const: 0x1a38
-  __TEXT.__cstring: 0x137f1
+  __TEXT.__cstring: 0x13886
   __TEXT.__unwind_info: 0x34a0
-  __DATA_CONST.__const: 0x2b90
+  __DATA_CONST.__const: 0x2bd0
   __AUTH_CONST.__const: 0x6310
   __DATA.__data: 0x1c8
   __DATA.__crash_info: 0x148

   __TPRO_CONST.__data: 0xe1
   __TPRO_CONST.__allocator: 0x20000
   Functions: 3369
-  Symbols:   3760
-  CStrings:  2365
+  Symbols:   3762
+  CStrings:  2376
 
Symbols:
+ __ZN5dyld3L14archCacheMagicE
+ __ZN5dyld3L9archNamesE
Functions:
~ __ZNK12PatchTableV232forEachPatchableCacheUseOfExportEjjyU13block_pointerFyjEU13block_pointerFvyN6mach_o15PointerMetaDataEybE : 484 -> 480
~ __ZNK12PatchTableV432forEachPatchableCacheUseOfExportEjjyU13block_pointerFyjEU13block_pointerFvyN6mach_o15PointerMetaDataEybE : 464 -> 460
~ ____ZNK5dyld313MachOAnalyzer15withChainStartsER11DiagnosticsyU13block_pointerFvPK28dyld_chained_starts_in_imageE_block_invoke : 452 -> 456
~ __ZNK5dyld313MachOAnalyzer25forEachRebase_RelocationsER11DiagnosticsRKNS_11MachOLoaded12LinkEditInfoEPKN6mach_o12UnsafeHeader11SegmentInfoEU13block_pointerFvPKcS6_SB_bjhyNS0_6RebaseERbE : 844 -> 824
~ __ZNK5dyld313MachOAnalyzer15sortRelocationsERNS_5ArrayI15relocation_infoEE : 192 -> 188
~ ____ZNK5dyld311MachOLoaded21fixupAllChainedFixupsER11DiagnosticsPK28dyld_chained_starts_in_imagemNS_5ArrayIPKvEEU13block_pointerFvPvSA_E_block_invoke : 456 -> 460
~ ____ZNK12objc_visitor7Visitor11findSectionENSt3__14spanIKPKcLm18446744073709551615EEES4__block_invoke : 280 -> 276
~ __ZN12PropertyList6encodeER10ByteStream : 2816 -> 2812
~ ____ZN5dyld44APIs25_dyld_for_each_objc_classEPKcNS_16ReadOnlyCallbackIU13block_pointerFvPvbPbEEE_block_invoke : 164 -> 160
~ ____ZN5dyld44APIs28_dyld_for_each_objc_protocolEPKcNS_16ReadOnlyCallbackIU13block_pointerFvPvbPbEEE_block_invoke : 164 -> 160
~ ____ZN5dyld44APIs24_dyld_visit_objc_classesENS_16ReadOnlyCallbackIU13block_pointerFvPKvEEE_block_invoke : 112 -> 108
~ __ZZN5dyld44APIs11dlopen_fromEPKciPvENK3$_0clEv : 2932 -> 2928
~ __ZZZN5dyld44APIs11dlopen_fromEPKciPvENK3$_0clEvENKUlvE_clEv : 3816 -> 3848
~ __ZN3lsl6VectorI18AuthenticatedValueIPN5dyld411PseudoDylibEEE5eraseENS6_15CheckedIteratorIS5_EE : 184 -> 192
~ __ZN5dyld4L7prepareERNS_4APIsEPKN6mach_o12UnsafeHeaderE : 5940 -> 5928
~ __ZN3lsl6VectorIPKN5dyld46LoaderEEcvNSt3__14spanIS4_Lm18446744073709551615EEEEv : 84 -> 92
~ __ZNK5dyld413ProcessConfig7Process13forEachEnvVarEU13block_pointerFvNSt3__117basic_string_viewIcNS2_11char_traitsIcEEEE7CStringRbE : 216 -> 212
~ __ZN5dyld413ProcessConfig13PathOverridesC2ERKNS0_7ProcessERKNS0_8SecurityERKNS0_7LoggingERKNS0_9DyldCacheERNS_15SyscallDelegateERN3lsl9AllocatorE : 808 -> 804
~ __ZN5dyld412RuntimeState18notifyDebuggerLoadEPKNS_6LoaderE : 400 -> 404
~ __ZN5dyld412RuntimeState23recordInDataConstBitmapEy : 356 -> 368
~ __ZN5dyld412RuntimeState23appendInterposingTuplesEPKNS_6LoaderEPKhj : 1796 -> 1772
~ __ZN5dyld46Reaper14garbageCollectEv : 216 -> 200
~ __ZN5dyld412RuntimeState19garbageCollectInnerEv : 836 -> 852
~ __ZN5dyld412RuntimeState12notifyUnloadERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEE : 4608 -> 4536
~ __ZN5dyld412RuntimeState13removeLoadersERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEE : 172 -> 164
~ ____ZN5dyld412RuntimeState12notifyDtraceERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEE_block_invoke : 152 -> 156
~ __ZN5dyld412RuntimeState18notifyDebuggerLoadERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEE : 724 -> 728
~ __ZN5dyld412RuntimeState20notifyDebuggerUnloadERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEE : 364 -> 360
~ __ZN5dyld412RuntimeState10notifyLoadERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEE : 1884 -> 1876
~ ____ZN5dyld412RuntimeState12notifyUnloadERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEE_block_invoke : 412 -> 408
~ ____ZN5dyld412RuntimeState12notifyUnloadERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEE_block_invoke_2 : 340 -> 336
~ __ZZN5dyld412RuntimeState28rebindMissingFlatLazySymbolsERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEEENK3$_0clERKNS0_17MissingFlatSymbolE : 296 -> 292
~ __ZN3lsl6VectorIN5dyld412RuntimeState11DlopenCountEE5eraseENS4_15CheckedIteratorIS3_EE : 184 -> 192
~ __ZZZN5dyld412RuntimeState10notifyLoadERKNSt3__14spanIPKNS_6LoaderELm18446744073709551615EEEEUb_ENK3$_8clEv : 1284 -> 1276
~ ____ZN3lsl13MemoryManager26withWritableMemoryInternalIZN5dyld412RuntimeLocks20withLoadersWriteLockIZNS2_12RuntimeState12notifyUnloadERKNSt3__14spanIPKNS2_6LoaderELm18446744073709551615EEEE3$_1EEvT_EUlvE_EEvSF__block_invoke : 568 -> 560
~ ____ZZN5dyld412RuntimeState16setObjCNotifiersENS_16ReadOnlyCallbackIPFvPKcPK11mach_headerEEENS1_IPFvS6_PvS6_PKvEEENS1_IPFvPK29_dyld_objc_notify_mapped_infoEEENS1_IPFvjSI_U13block_pointerFvjEEEEENK3$_0clEv_block_invoke : 1584 -> 1552
~ __ZN5dyld423ExternallyViewableState17createMinimalInfoERN3lsl9AllocatorEyPKcyS5_PK15DyldSharedCache : 1856 -> 1852
~ __ZN5dyld423ExternallyViewableState9addImagesERN3lsl9AllocatorES3_RKNSt3__14spanINS0_9ImageInfoELm18446744073709551615EEE : 1516 -> 1512
~ __ZN5dyld423ExternallyViewableState12removeImagesERN3lsl9AllocatorES3_RNSt3__14spanIPK11mach_headerLm18446744073709551615EEE : 1740 -> 1736
~ __ZN3lsl6VectorI15dyld_image_infoE5eraseENS2_15CheckedIteratorIS1_EE : 196 -> 204
~ __ZN5dyld423ExternallyViewableState19removeRosettaImagesERNSt3__14spanIPK11mach_headerLm18446744073709551615EEE : 392 -> 388
~ __ZNK5dyld416JustInTimeLoader11matchesPathERKNS_12RuntimeStateEPKc : 268 -> 272
~ __ZN5dyld416JustInTimeLoader14loadDependentsER11DiagnosticsRNS_12RuntimeStateERKNS_6Loader11LoadOptionsE : 724 -> 728
~ ____ZN5dyld416JustInTimeLoader14loadDependentsER11DiagnosticsRNS_12RuntimeStateERKNS_6Loader11LoadOptionsE_block_invoke : 988 -> 992
~ __ZN5dyld416JustInTimeLoader4makeERNS_12RuntimeStateEPKN6mach_o12UnsafeHeaderEPKcRKNS_6FileIDEybbbt : 1296 -> 1304
~ __ZN5dyld46Loader11mapSegmentsER11DiagnosticsRNS_12RuntimeStateEPKciyRKNS0_19CodeSignatureInFileEbNSt3__14spanIKNS0_6RegionELm18446744073709551615EEEbbRKNS0_18FileValidationInfoE : 1452 -> 1448
~ __ZN5dyld46Loader16addWeakDefsToMapERNS_12RuntimeStateERKNSt3__14spanIPKS0_Lm18446744073709551615EEE : 260 -> 256
~ __ZN5dyld4L15fixupPageAuth64EPvPK12mwl_info_hdrPK30dyld_chained_starts_in_segmentjb : 384 -> 388
~ __ZN5dyld4L11fixupPage64EPvPK12mwl_info_hdrPK30dyld_chained_starts_in_segmentjb : 236 -> 240
~ __ZN5dyld4L12fixupChain32EPjPK12mwl_info_hdrPK30dyld_chained_starts_in_segmentPKjS0_ : 192 -> 196
~ __ZNK5dyld414PrebuiltLoader11applyFixupsER11DiagnosticsRNS_12RuntimeStateERNS_34DyldCacheDataConstLazyScopedWriterEbPN3lsl6VectorINSt3__14pairIPKNS_6LoaderEPKcEEEE : 1316 -> 1312
~ __ZN5dyld412PrebuiltObjC22generatePerImageFixupsERNS_12RuntimeStateE : 636 -> 632
~ __ZN5dyld412PrebuiltObjC4makeER11DiagnosticsRNS_12RuntimeStateE : 3304 -> 3308
~ __ZN5dyld3L20mapSplitCachePrivateERKNS_18SharedCacheOptionsEPNS_19SharedCacheLoadInfoE : 4300 -> 4312
~ __ZN5dyld3L22preflightMainCacheFileERKNS_18SharedCacheOptionsEPNS_19SharedCacheLoadInfoEPNS_9CacheInfoEPcPNSt3__15arrayIA32_cLm128EEE : 328 -> 460
~ __ZN5dyld3L10validMagicERKNS_18SharedCacheOptionsEPK15DyldSharedCache : 108 -> 132
~ __ZNK6mach_o21FunctionVariantFixups5validENSt3__14spanIKNS_13MappedSegmentELm18446744073709551615EEE : 188 -> 184
~ __ZNK6mach_o21FunctionVariantFixups12forEachFixupEU13block_pointerFvNS0_13InternalFixupEE : 88 -> 80
~ __ZNK6mach_o19GradedArchitectures8bestArchENSt3__14spanIKNS_12ArchitectureELm18446744073709551615EEE : 164 -> 148
~ __ZNK6mach_o19GradedArchitectures8containsENS_12ArchitectureE : 92 -> 84
~ __ZNK6mach_o19GradedArchitectures9bestSliceENSt3__14spanIKhLm18446744073709551615EEERS4_ : 556 -> 552
~ __ZNK6mach_o19GradedArchitectures9archNamesER14CStringBuilder : 244 -> 240
~ __ZNK6mach_o6Header22validStructureLinkeditERKNS_6PolicyEy : 1632 -> 1624
~ __ZNK6mach_o5Image13linkeditBytesENS_6Header13LinkEditRangeE : 172 -> 180
~ ____ZNK6mach_o5Image13validLinkeditERKNS_6PolicyE_block_invoke : 720 -> 716
CStrings:
+ "16777228--2147483636"
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Tue Aug 11 20:40:24 PDT 2026; root:libignition-64~19252/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Tue Aug 11 20:40:24 PDT 2026; root:libignition-64~19252/libignition_core/RELEASE_ARM64E"
+ "arm64.x1"
+ "arm64.x2"
+ "arm64e.x1"
+ "arm64e.x1.kernel"
+ "arm64e.x1.old"
+ "arm64e.x2"
+ "arm64e.x2.kernel"
+ "arm64e_x1"
+ "dyld_v1  arm64e"
+ "dyld_v1arm64ex1"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Tue Aug 11 21:44:28 PDT 2026; root:libignition-64~19270/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Tue Aug 11 21:44:28 PDT 2026; root:libignition-64~19270/libignition_core/RELEASE_ARM64E"
```
