## footprint

> `/usr/bin/footprint`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 365.0.0.0.0
-  __TEXT.__text: 0x23254
+  __TEXT.__text: 0x22bd8
   __TEXT.__auth_stubs: 0xb50
   __TEXT.__objc_stubs: 0x2560
   __TEXT.__objc_methlist: 0x132c

   __TEXT.__objc_methname: 0x25d4
   __TEXT.__ustring: 0xd0
   __TEXT.__oslogstring: 0x21
-  __TEXT.__unwind_info: 0x520
+  __TEXT.__unwind_info: 0x688
   __DATA_CONST.__const: 0x7e8
   __DATA_CONST.__cfstring: 0x1320
   __DATA_CONST.__objc_classlist: 0xc8
Functions:
~ -[FPSystemMem gatherData:] : 880 -> 868
~ +[FPMemgraphProcess processWithMemgraph:error:] : 1264 -> 1252
~ ___copy_helper_block_e8_32s40b48r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ -[FPMemgraphProcess _gatherLedgers] : 232 -> 220
~ -[FPMemoryRegion addSubrange:memoryTotal:] : 128 -> 116
~ +[FPMemoryRegion categoryNameForTag:] : 344 -> 332
~ +[FPMemoryRegion vmLedgerNameForTag:] : 116 -> 104
~ -[FPMemoryRegion fullName] : 144 -> 132
~ -[FPMemoryRegion description] : 284 -> 272
~ -[FPMemoryRegion ensureMemoryObject] : 92 -> 80
~ -[FPMemoryRegion extendedInfo] : 132 -> 120
~ -[FPMemoryRegion setExtendedInfo:] : 148 -> 136
~ -[FPMemoryRegion .cxx_destruct] : 80 -> 68
~ ____extendedInfoStorage_block_invoke : 68 -> 56
~ +[FPSharedCache sharedCacheForDyldSnapshot:] : 424 -> 412
~ +[FPSharedCache instanceCache] : 92 -> 80
~ -[FPMemoryObject addRegion:forProcess:] : 136 -> 124
~ -[FPMemoryObject _addRegion:forProcess:] : 412 -> 400
~ -[FPMemoryObject _fakeRegion] : 292 -> 280
~ -[FPMemoryObject _canonicalRegion] : 352 -> 340
~ -[FPMemoryObject name] : 80 -> 68
~ -[FPMemoryObject detailedName] : 80 -> 68
~ -[FPMemoryObject fullName] : 80 -> 68
~ -[FPMemoryObject auxData] : 84 -> 72
~ -[FPMemoryObject detailedAuxData] : 84 -> 72
~ -[FPMemoryObject auxDataName] : 84 -> 72
~ -[FPMemoryObject detailedAuxDataName] : 84 -> 72
~ -[FPMemoryObject .cxx_destruct] : 68 -> 56
~ +[FPProcess processWithBsdInfo:] : 92 -> 80
~ +[FPProcess processWithPid:] : 232 -> 220
~ -[FPProcess gatherData:extendedInfoProvider:] : 104 -> 92
~ +[FPProcess _nameForBsdInfoCommName:] : 144 -> 132
~ +[FPProcess _nameForBsdInfo:] : 444 -> 432
~ +[FPProcess allProcessesExcludingPids:] : 336 -> 324
~ +[FPProcess pidsForStringDescriptions:errors:] : 1200 -> 1188
~ +[FPProcess childPidsForPids:] : 760 -> 748
~ +[FPProcess removeIdleExitCleanProcessesFrom:] : 376 -> 364
~ -[FPProcess description] : 136 -> 124
~ -[FPProcess .cxx_destruct] : 128 -> 116
~ -[FPUserProcess _gatherOwnedVmObjects] : 564 -> 552
~ -[FPUserProcess _populateMemoryRegionWithPageQueries:regionInfo:] : 1024 -> 1020
~ ___65-[FPUserProcess _populateMemoryRegionWithPageQueries:regionInfo:]_block_invoke : 904 -> 892
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ -[FPUserProcess _enumerateDispositionChunksWithStartAddr:pagesToQuery:block:] : 400 -> 404
~ ___copy_helper_block_e8_32s40r48r56r64r : 120 -> 108
~ ___destroy_helper_block_e8_32s40r48r56r64r : 100 -> 88
~ ___56-[FPUserProcess _gatherMemoryData:extendedInfoProvider:]_block_invoke : 3524 -> 3516
~ ___copy_helper_block_e8_32s40s48s56s64r72r : 112 -> 100
~ ___destroy_helper_block_e8_32s40s48s56s64r72r : 100 -> 88
~ -[FPUserProcess _gatherLedgers] : 196 -> 172
~ -[FPUserProcess _gatherSharedCacheFromDyldSnapshot:] : 80 -> 68
~ ___33-[FPUserProcess _gatherImageData]_block_invoke_2 : 1660 -> 1668
~ ___copy_helper_block_e8_32s40r48r : 88 -> 76
~ ___destroy_helper_block_e8_32s40r48r : 76 -> 64
~ -[FPUserProcess auxData] : 680 -> 668
~ -[FPUserProcess extendedInfoForRegionType:at:extendedInfoProvider:] : 1524 -> 1512
~ -[FPUserProcess addLedgerData:count:] : 36 -> 28
~ -[FPUserProcess .cxx_destruct] : 104 -> 92
~ -[FPBootCarveout _gatherData:extendedInfoProvider:] : 4532 -> 4520
~ -[FPKernelProcess _gatherData:extendedInfoProvider:] : 2700 -> 2704
~ +[FPKernelProcess _nameForWiredInfo:withSymbolicator:zoneNames:zoneCount:] : 512 -> 500
~ -[FPKernelProcess auxData] : 232 -> 220
~ -[FPKernelProcess addMemoryRegion:] : 112 -> 100
~ -[FPKernelProcess removeMemoryRegion:] : 112 -> 100
~ -[FPKernelProcess .cxx_destruct] : 100 -> 88
~ -[FPMemoryMultiRegion auxData] : 200 -> 188
~ -[FPMemoryMultiRegion auxDataName] : 108 -> 96
~ -[FPRangeList _addRangeList:] : 108 -> 96
~ -[FPRangeList addRegion:] : 292 -> 280
~ -[FPRangeList distributeKernelRegionBudget:useDirtyCap:] : 176 -> 160
~ -[FPRangeList enumerateUsingBlock:] : 112 -> 100
~ __FPRangeListSplitNodeAtIntersection : 256 -> 236
~ -[FPImage setName:] : 196 -> 184
~ -[FPImage .cxx_destruct] : 68 -> 56
~ -[FPImageEnumerator nextImageForStart:end:] : 240 -> 228
~ -[NSDictionary(FPAuxData) fp_mergeAuxDatum:withDatum:forceAggregate:] : 316 -> 304
~ -[NSDictionary(FPAuxData) fp_mergeWithData:forceAggregate:] : 740 -> 728
~ -[NSDictionary(FPAuxData) fp_jsonRepresentation] : 360 -> 348
~ -[FPAuxData description] : 172 -> 160
~ -[FPFootprintArgs targetProcessesAndError:] : 4840 -> 4828
~ -[FPFootprintArgs .cxx_destruct] : 116 -> 104
~ _main : 9112 -> 9108
~ ___main_block_invoke : 76 -> 72
~ ___copy_helper_block_e8_32s40s48s56r64r72r80r88r96r : 168 -> 156
~ ___destroy_helper_block_e8_32s40s48s56r64r72r80r88r96r : 140 -> 128
~ __sampleFootprint_block_invoke.201 : 172 -> 160
~ ___copy_helper_block_e8_32s40s48s56r64r : 104 -> 92
~ ___destroy_helper_block_e8_32s40s48s56r64r : 92 -> 80
~ +[FPFootprint installCancelHandler:] : 136 -> 124
~ ___26-[FPFootprint gatherData:]_block_invoke : 124 -> 112
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ -[FPFootprint _notHiddenProcesses] : 108 -> 96
~ -[FPFootprint _categoriesForObjects:viewedByProcess:hasProcessView:summarize:] : 560 -> 548
~ ___copy_helper_block_e8_32s40s48s56s : 76 -> 64
~ ___destroy_helper_block_e8_32s40s48s56s : 76 -> 64
~ -[FPFootprint ioSurfaceExtendedInfoDetailsAtAddress:for:] : 780 -> 768
~ -[FPFootprint ioAccelMemoryInfoDetailsAtAddress:for:error:] : 1844 -> 1832
~ -[FPFootprint .cxx_destruct] : 188 -> 176
~ -[FPOutputFormatterJSON startAtTime:] : 296 -> 284
~ -[FPOutputFormatterJSON printProcessTotal:forProcess:] : 224 -> 212
~ -[FPOutputFormatterJSON printProcessCategories:total:forProcess:] : 228 -> 216
~ -[FPOutputFormatterJSON printProcessAuxData:forProcess:] : 208 -> 196
~ -[FPOutputFormatterJSON printSummaryCategories:total:hadErrors:] : 864 -> 852
~ -[FPOutputFormatterJSON printGlobalAuxData:] : 148 -> 136
~ -[FPOutputFormatterJSON .cxx_destruct] : 80 -> 68
~ -[FPProcessGroupMinimal addProcess:] : 132 -> 120
~ -[FPProcessGroupMinimal immutableCopy] : 100 -> 88
~ -[FPProcessGroupMinimal description] : 140 -> 128
~ -[FPProcessGroup addObject:] : 116 -> 104
~ -[FPProcessGroup attachCachedCategories:refcount:] : 120 -> 108
~ -[FPProcessGroup consumeCachedCategories] : 124 -> 112
~ -[FPProcessGroup .cxx_destruct] : 68 -> 56
~ +[FPTime now] : 52 -> 40
~ -[FPTime date] : 64 -> 52
~ -[FPOutputFormatterPerfdata startAtTime:] : 100 -> 88
~ -[FPOutputFormatterPerfdata printProcessCategories:total:forProcess:] : 140 -> 128
~ -[FPOutputFormatterPerfdata endAtTime:] : 204 -> 192
~ -[FPOutputFormatterPerfdata .cxx_destruct] : 92 -> 80
~ -[FPAuxDataInfo .cxx_destruct] : 68 -> 56
~ _FPTextAllColumns : 184 -> 172
~ -[FPOutputFormatterText _truncatedNameForString:] : 212 -> 200
~ -[FPOutputFormatterText printHeader] : 92 -> 80
~ -[FPOutputFormatterText printProcessAuxData:forProcess:] : 196 -> 184
~ -[FPOutputFormatterText printGlobalAuxData:] : 1284 -> 1272
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ -[FPOutputFormatterText endAtTime:] : 1792 -> 1780
~ -[FPOutputFormatterText _printHorizontallyForProcess:verticalAlignment:string:] : 628 -> 616
~ -[FPOutputFormatterText .cxx_destruct] : 152 -> 140
~ -[FPMemoryCategory name] : 96 -> 84
~ -[FPMemoryCategory detailedName] : 80 -> 56
~ -[FPMemoryCategory auxData] : 172 -> 160
~ -[FPMemoryCategory auxDataFullName] : 208 -> 196
~ -[FPMemoryCategory addMemoryObject:] : 220 -> 208
~ -[FPMemoryCategory .cxx_destruct] : 68 -> 56
~ __FPRangeListAddNode : 628 -> 588
```
