## mpsgraphtool

> `/usr/bin/mpsgraphtool`

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

 7.0.80.0.0
-  __TEXT.__text: 0x1c93c
+  __TEXT.__text: 0x1c6c4
   __TEXT.__auth_stubs: 0x690
   __TEXT.__objc_stubs: 0x11a0
   __TEXT.__objc_methlist: 0x1e8

   __TEXT.__objc_methname: 0x106f
   __TEXT.__objc_classname: 0x2f
   __TEXT.__objc_methtype: 0x1d8
-  __TEXT.__unwind_info: 0x3d8
+  __TEXT.__unwind_info: 0x448
   __DATA_CONST.__const: 0x1c0
   __DATA_CONST.__cfstring: 0x840
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ _Shim_ATFTestStartVersion : 268 -> 256
~ _Shim_ATFTestFinish : 268 -> 244
~ _Shim_ATFAnyErrors : 268 -> 244
~ _Shim_ATFMTLCollectCompilePerformanceStatistics : 176 -> 164
~ _Shim_ATFMTLSetCompileLogMode : 176 -> 164
~ _Shim_ATFMTLSetCompileLogType : 176 -> 164
~ _Shim_ATFReportLeaks : 200 -> 188
~ _Shim_ATFSubTestFinish : 140 -> 128
~ _Shim_ATFStartCaptureScope : 176 -> 164
~ _Shim_ATFEndCaptureScope : 140 -> 128
~ _Shim_ATFGetTestResultsDirectory : 140 -> 128
~ _Shim_ATFGetEnvironmentVariable : 176 -> 164
~ __ZNSt3__1lsB9nqe220106INS_11char_traitsIcEEEERNS_13basic_ostreamIcT_EES6_PKc : 72 -> 60
~ __Z10printUsageb : 2360 -> 2348
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeI9ParamKeysNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEENS_22__unordered_map_hasherIS2_NS_4pairIKS2_S8_EENS_4hashIS2_EENS_8equal_toIS2_EEEENS_21__unordered_map_equalIS2_SD_SH_SF_EENS6_ISD_EEE16__emplace_uniqueB9nqe220106IJRKSD_EEENSB_INS_15__hash_iteratorIPNS_11__hash_nodeIS9_PvEEEEbEEDpOT_ENKUlRSC_SP_E_clES10_SP_ : 792 -> 784
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 180 -> 156
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeI9ParamKeysNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEENS_22__unordered_map_hasherIS2_NS_4pairIKS2_S8_EENS_4hashIS2_EENS_8equal_toIS2_EEEENS_21__unordered_map_equalIS2_SD_SH_SF_EENS6_ISD_EEE16__emplace_uniqueB9nqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJOS2_EEENSR_IJEEEEEENSB_INS_15__hash_iteratorIPNS_11__hash_nodeIS9_PvEEEEbEEDpOT_ENKUlRSC_SQ_OST_OSU_E_clES15_SQ_S16_S17_ : 740 -> 732
~ __ZNSt3__16vectorIN19SerializationParams14SpecializationENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJRKS2_EEEPS2_DpOT_ : 512 -> 508
~ __ZNSt3__16vectorIN19SerializationParams14SpecializationENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJS2_EEEPS2_DpOT_ : 504 -> 500
~ ___GetMTKTextureLoader_block_invoke : 192 -> 180
~ _Shim_ATFMTLSaveBuffer : 240 -> 228
~ _Shim_ATFMTLSaveTexture : 240 -> 228
~ _Shim_ATFMTLCopyTestDevice : 140 -> 128
~ _Fallback_ATFMTLCopyTestDevice : 52 -> 40
~ __Z13newInputArrayPU19objcproto9MTLDevice11objc_objectP18MPSGraphShapedTypem : 1980 -> 1968
~ __Z28initTensorDataWithBinaryFileP5NSURLPU19objcproto9MTLDevice11objc_objectP18MPSGraphShapedTypem : 1712 -> 1700
~ __Z26allocateTensorDataWithTypeP18MPSGraphShapedTypePU19objcproto9MTLDevice11objc_objectP5NSURLm : 320 -> 308
~ __Z20saveTensorDataTaFileP5NSURLP18MPSGraphTensorData11MPSDataType : 192 -> 180
~ __Z27genRandomMPSTensorDataArrayP7NSArrayIP18MPSGraphShapedTypeEPU19objcproto9MTLDevice11objc_objectbm : 788 -> 776
~ __Z30readMPSTensorDataArrayFromFileP7NSArrayIP18MPSGraphShapedTypeENSt3__112basic_stringIcNS4_11char_traitsIcEENS4_9allocatorIcEEEESA_SA_PU19objcproto9MTLDevice11objc_objectbm : 1444 -> 1432
~ __Z19specializeInputTypeP18MPSGraphShapedTypeyP7NSArrayIP8NSNumberEbPS1_IS5_E : 1816 -> 1804
~ ____Z19specializeInputTypeP18MPSGraphShapedTypeyP7NSArrayIP8NSNumberEbPS1_IS5_E_block_invoke : 176 -> 152
~ __Z20readDataFromJSONFileP8NSString : 604 -> 592
~ __ZL8readLineP6NSDataR8_NSRange : 324 -> 312
~ __Z38readMPSTensorDataArrayFromJsonDataFileP7NSArrayIP18MPSGraphShapedTypeEPU19objcproto9MTLDevice11objc_objectP12NSDictionaryRKNSt3__16vectorINS8_12basic_stringIcNS8_11char_traitsIcEENS8_9allocatorIcEEEENSD_ISF_EEEEbbm : 2616 -> 2604
~ __ZNSt3__16vectorImNS_9allocatorImEEE24__emplace_back_slow_pathIJRKmEEEPmDpOT_ : 208 -> 204
~ __Z20getFileFormatFromURLP5NSURL : 1328 -> 1320
~ __Z18writeBufferContentPU19objcproto9MTLBuffer11objc_objectRKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE : 284 -> 272
~ __Z16getNSDataFromURLP5NSURL : 288 -> 276
~ __Z19getMPSSourceFromURLP5NSURL7Dialect : 432 -> 420
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE10FileFormatEENS_22__unordered_map_hasherIS7_NS_4pairIKS7_S8_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SD_SH_SF_EENS5_ISD_EEE16__emplace_uniqueB9nqe220106IJRKSD_EEENSB_INS_15__hash_iteratorIPNS_11__hash_nodeIS9_PvEEEEbEEDpOT_ENKUlRSC_SP_E_clES10_SP_ : 964 -> 956
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE7DialectEENS_22__unordered_map_hasherIS7_NS_4pairIKS7_S8_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SD_SH_SF_EENS5_ISD_EEE16__emplace_uniqueB9nqe220106IJRKSD_EEENSB_INS_15__hash_iteratorIPNS_11__hash_nodeIS9_PvEEEEbEEDpOT_ENKUlRSC_SP_E_clES10_SP_ : 984 -> 976
~ __ZN12_GLOBAL__N_115parseShapesListERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE : 664 -> 652
~ __ZZ17runToolWithParamsRKNSt3__113unordered_mapI9ParamKeysNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4hashIS1_EENS_8equal_toIS1_EENS5_INS_4pairIKS1_S7_EEEEEEENK3$_0clEP28MPSGraphExecutableDescriptor : 5444 -> 5424
~ ____Z11runPerfLoopRKNSt3__113unordered_mapI9ParamKeysNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4hashIS1_EENS_8equal_toIS1_EENS5_INS_4pairIKS1_S7_EEEEEEPU26objcproto15MTLCommandQueue11objc_objectP18MPSGraphExecutableP7NSArrayIP18MPSGraphTensorDataESR_yybbbP29MPSGraphCompilationDescriptory_block_invoke : 416 -> 404
~ ___copy_helper_block_ea8_32s40r48r56r : 104 -> 92
~ ___destroy_helper_block_ea8_32s40r48r56r : 88 -> 76
~ __Z22runSerializeWithParamsRK19SerializationParams : 12120 -> 12116
~ -[MPSGraphToolWorkload .cxx_destruct] : 80 -> 68
~ __ZZZ17runToolWithParamsRKNSt3__113unordered_mapI9ParamKeysNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4hashIS1_EENS_8equal_toIS1_EENS5_INS_4pairIKS1_S7_EEEEEEENK3$_0clEP28MPSGraphExecutableDescriptorENKUlvE_clEv : 2920 -> 2900
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE7DialectEENS_22__unordered_map_hasherIS7_NS_4pairIKS7_S8_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SD_SH_SF_EENS5_ISD_EEE16__emplace_uniqueB9nqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRSC_EEENSR_IJEEEEEENSB_INS_15__hash_iteratorIPNS_11__hash_nodeIS9_PvEEEEbEEDpOT_ENKUlSS_SQ_OST_OSU_E_clESS_SQ_S15_S16_ : 976 -> 968
~ __ZNSt3__120__shared_ptr_pointerIPN3MIL10MILContextENS_14default_deleteIS2_EENS_9allocatorIS2_EEED0Ev : 40 -> 28
```
