## AppleMetalOpenGLRenderer

> `/System/Library/Extensions/AppleMetalOpenGLRenderer.bundle/Contents/MacOS/AppleMetalOpenGLRenderer`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 91.7.0.0.0
-  __TEXT.__text: 0x4c0d8
+  __TEXT.__text: 0x4b914
   __TEXT.__auth_stubs: 0x790
   __TEXT.__objc_stubs: 0x31a0
   __TEXT.__objc_methlist: 0x38

   __TEXT.__objc_methname: 0x2894
   __TEXT.__objc_classname: 0x17
   __TEXT.__objc_methtype: 0x1f6a
-  __TEXT.__unwind_info: 0xd10
+  __TEXT.__unwind_info: 0x1010
   __DATA_CONST.__const: 0x2808
   __DATA_CONST.__cfstring: 0xde0
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ __ZN32GLDVisibilityResultStagingBufferD1Ev : 60 -> 48
~ __ZN32GLDVisibilityResultStagingBufferD0Ev : 68 -> 56
~ __ZN32GLDVisibilityResultStagingBuffer7deallocEv : 92 -> 80
~ __ZN32GLDVisibilityResultStagingBuffer14processResultsEv : 132 -> 120
~ __ZN11GLDQueryRecD1Ev : 60 -> 48
~ __ZN11GLDQueryRecD0Ev : 68 -> 56
~ __ZN11GLDQueryRec7deallocEv : 56 -> 44
~ __ZN11GLDQueryRec16counterAvailableEv : 156 -> 144
~ __ZN11GLDQueryRec24setCommandBufferToWaitOnEPU27objcproto16MTLCommandBuffer11objc_object : 80 -> 68
~ __ZN13GLDContextRec36releaseVisibilityResultStagingBufferEP32GLDVisibilityResultStagingBuffer : 184 -> 160
~ __ZN13GLDContextRec39resumeCurrentSamplesPassedQueryIfNeededEv : 120 -> 108
~ ____ZN13GLDContextRec8endQueryEP11GLDQueryReci_block_invoke : 112 -> 100
~ ____ZN13GLDContextRec11resumeQueryEP11GLDQueryRecib_block_invoke : 100 -> 88
~ __ZZNSt3__112__hash_tableIP11GLDQueryRecNS_4hashIS2_EENS_8equal_toIS2_EENS_9allocatorIS2_EEE16__emplace_uniqueB9nqn220106IJRKS2_EEENS_4pairINS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSC_SC_E_clESC_SC_ : 580 -> 576
~ __ZNSt3__112__hash_tableIP11GLDQueryRecNS_4hashIS2_EENS_8equal_toIS2_EENS_9allocatorIS2_EEE8__rehashILb1EEEvm : 228 -> 212
~ __ZNSt3__112__hash_tableINS_17__hash_value_typeIP17GLRBufferResourceNS_6vectorIjNS_9allocatorIjEEEEEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S7_EENS_4hashIS3_EENS_8equal_toIS3_EEEENS_21__unordered_map_equalIS3_SC_SG_SE_EENS5_ISC_EEE17__deallocate_nodeB9nqn220106EPNS_11__hash_nodeIS8_PvEE : 68 -> 56
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIP17GLRBufferResourceNS_6vectorIjNS_9allocatorIjEEEEEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S7_EENS_4hashIS3_EENS_8equal_toIS3_EEEENS_21__unordered_map_equalIS3_SC_SG_SE_EENS5_ISC_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRSB_EEENSQ_IJEEEEEENSA_INS_15__hash_iteratorIPNS_11__hash_nodeIS8_PvEEEEbEEDpOT_ENKUlSR_SP_OSS_OST_E_clESR_SP_S14_S15_ : 624 -> 620
~ __ZNSt3__122__hash_node_destructorINS_9allocatorINS_11__hash_nodeINS_17__hash_value_typeIP17GLRBufferResourceNS_6vectorIjNS1_IjEEEEEEPvEEEEEclB9nqn220106EPSB_ : 100 -> 88
~ __ZNSt3__16vectorIjNS_9allocatorIjEEE24__emplace_back_slow_pathIJRjEEEPjDpOT_ : 196 -> 192
~ __ZN18GLDMemoryPluginRecD0Ev : 44 -> 32
~ __ZN18GLDMemoryPluginRec7deallocEv : 88 -> 76
~ __ZN12GLDBufferRecD0Ev : 44 -> 32
~ __ZN12GLDBufferRec7deallocEv : 112 -> 100
~ __ZN12GLDBufferRec4loadEv : 1352 -> 1344
~ __ZN12GLDBufferRec12loadUnlockedEv : 1288 -> 1280
~ __ZN12GLDBufferRec11restoreDataEj : 892 -> 884
~ __ZN12GLDDeviceRecD2Ev : 140 -> 128
~ __ZN12GLDDeviceRecD0Ev : 48 -> 36
~ __ZN12GLDDeviceRec19initWithDisplayMaskEj : 2520 -> 2516
~ ____ZN12GLDDeviceRec19initWithDisplayMaskEj_block_invoke_2 : 152 -> 140
~ __ZN12GLDDeviceRec7deallocEv : 512 -> 500
~ ____ZN12GLDDeviceRec29getRenderPipelineStateFromKeyEPP21GLDPipelineProgramRecPK20GLRRenderPipelineKey_block_invoke : 1744 -> 1732
~ __ZL17processReflectionP22GLRRenderPipelineState12PipelineTypejP7NSArrayIP11MTLArgumentE22MTLRenderPipelineFlagsP12NSDictionary : 4764 -> 4796
~ ___destroy_helper_block_e8_32o40o48o56o64o72o80o88o96r120c36_ZTS30GLRRenderPipelineStateInternal : 264 -> 252
~ ___copy_helper_block_e8_32o40r : 80 -> 68
~ ___destroy_helper_block_e8_32o40r : 68 -> 56
~ _gldCreateDevice : 1148 -> 1140
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIjP17GLRDeviceDrawableEENS_22__unordered_map_hasherIjNS_4pairIKjS3_EENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS8_SC_SA_EENS_9allocatorIS8_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSN_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSO_SM_OSP_OSQ_E_clESO_SM_S11_S12_ : 532 -> 528
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIjPU37objcproto26MTLComputePipelineStateSPI11objc_objectEENS_22__unordered_map_hasherIjNS_4pairIKjS3_EENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS8_SC_SA_EENS_9allocatorIS8_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSN_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSO_SM_OSP_OSQ_E_clESO_SM_S11_S12_ : 532 -> 528
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIyjEENS_22__unordered_map_hasherIyNS_4pairIKyjEENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS6_SA_S8_EENS_9allocatorIS6_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS5_EEENSL_IJEEEEEENS4_INS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSM_SK_OSN_OSO_E_clESM_SK_SZ_S10_ : 524 -> 520
~ __ZNSt3__112__hash_tableINS_17__hash_value_typeIj29GLRTextureSamplerArgumentInfoEENS_22__unordered_map_hasherIjNS_4pairIKjS2_EENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS7_SB_S9_EENS_9allocatorIS7_EEE16__copy_constructB9nqn220106EPNS_16__hash_node_baseIPNS_11__hash_nodeIS3_PvEEEE : 172 -> 160
~ __ZNSt3__112__hash_tableINS_17__hash_value_typeIj21GLRBufferArgumentInfoEENS_22__unordered_map_hasherIjNS_4pairIKjS2_EENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS7_SB_S9_EENS_9allocatorIS7_EEE16__copy_constructB9nqn220106EPNS_16__hash_node_baseIPNS_11__hash_nodeIS3_PvEEEE : 172 -> 160
~ __ZNSt3__112__hash_tableINS_17__hash_value_typeIyjEENS_22__unordered_map_hasherIyNS_4pairIKyjEENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS6_SA_S8_EENS_9allocatorIS6_EEE16__copy_constructB9nqn220106EPNS_16__hash_node_baseIPNS_11__hash_nodeIS2_PvEEEE : 172 -> 160
~ __ZNKSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE5rfindB9nqn220106ERKS5_m : 176 -> 172
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIj29GLRTextureSamplerArgumentInfoEENS_22__unordered_map_hasherIjNS_4pairIKjS2_EENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_ : 544 -> 540
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIj21GLRBufferArgumentInfoEENS_22__unordered_map_hasherIjNS_4pairIKjS2_EENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_ : 532 -> 528
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIjPU34objcproto23MTLComputePipelineState11objc_objectEENS_22__unordered_map_hasherIjNS_4pairIKjS3_EENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS8_SC_SA_EENS_9allocatorIS8_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSN_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSO_SM_OSP_OSQ_E_clESO_SM_S11_S12_ : 532 -> 528
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIjNS_4pairIPU34objcproto23MTLComputePipelineState11objc_objectS4_EEEENS_22__unordered_map_hasherIjNS2_IKjS5_EENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS9_SD_SB_EENS_9allocatorIS9_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS8_EEENSO_IJEEEEEENS2_INS_15__hash_iteratorIPNS_11__hash_nodeIS6_PvEEEEbEEDpOT_ENKUlSP_SN_OSQ_OSR_E_clESP_SN_S12_S13_ : 532 -> 528
~ __ZN11GLDFenceRecD0Ev : 44 -> 32
~ __ZN17GLDFramebufferRecD0Ev : 44 -> 32
~ __ZN17GLDFramebufferRec4loadEv : 612 -> 608
~ __ZN17GLDPixelConverter4initEPU19objcproto9MTLDevice11objc_object : 200 -> 188
~ __ZN17GLDPixelConverter7deallocEv : 84 -> 72
~ __ZNSt3__16vectorIPU34objcproto23MTLComputePipelineState11objc_objectNS_9allocatorIS2_EEE24__emplace_back_slow_pathIJS2_EEEPS2_DpOT_ : 196 -> 192
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIN17GLDPixelConverter16ConversionFormatEmEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_mEENS2_22ConversionFormatHasherENS_8equal_toIS3_EEEENS_21__unordered_map_equalIS3_S8_SB_S9_EENS_9allocatorIS8_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSM_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_ : 556 -> 552
~ _OUTLINED_FUNCTION_3 : 28 -> 16
~ _gldInitializeLibrary : 160 -> 148
~ __ZNSt3__16vectorIN10GLDLibrary20DisplayMaskToServiceENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJRKS2_EEEPS2_DpOT_ : 196 -> 192
~ ____ZN11GLDQueueRec15handleDstBufferEP12GLDBufferRecPK23GLDBufferImageRegionRec_block_invoke : 92 -> 80
~ __ZN11GLDQueueRec10fillBufferEP12GLDBufferRecS1_PK23GLDBufferImageRegionRecS4_ : 456 -> 448
~ __ZN11GLDQueueRec22copyFromBufferToBufferEP12GLDBufferRecS1_PK23GLDBufferImageRegionRecS4_ : 676 -> 668
~ __ZN11GLDQueueRec11fillTextureEP12GLDBufferRecP24GLDTextureComputeViewRecP23GLDBufferImageRegionRecP24GLDTextureImageRegionRec : 548 -> 540
~ __ZN21GLDPipelineProgramRecD1Ev : 60 -> 48
~ __ZN21GLDPipelineProgramRecD0Ev : 68 -> 56
~ __ZN21GLDPipelineProgramRec7deallocEv : 116 -> 104
~ __ZN21GLDPipelineProgramRec23updateMetalFunctionBaseEv : 704 -> 692
~ __ZN13GLDProgramRecD0Ev : 44 -> 32
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeI28GLDPipelineProgramVariantKeyPU22objcproto11MTLFunction11objc_objectEENS_22__unordered_map_hasherIS2_NS_4pairIKS2_S4_EENS_4hashIS2_EENS_8equal_toIS2_EEEENS_21__unordered_map_equalIS2_S9_SD_SB_EENS_9allocatorIS9_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS8_EEENSO_IJEEEEEENS7_INS_15__hash_iteratorIPNS_11__hash_nodeIS5_PvEEEEbEEDpOT_ENKUlSP_SN_OSQ_OSR_E_clESP_SN_S12_S13_ : 576 -> 572
~ __ZN19GLRResourceListPoolD0Ev : 44 -> 32
~ __ZN19GLRResourceListPool7deallocEv : 100 -> 88
~ __ZN11GLRResourceD0Ev : 44 -> 32
~ __ZN17GLRBufferResourceD0Ev : 44 -> 32
~ __ZN17GLRBufferResource7deallocEv : 60 -> 48
~ __ZN17GLRBufferResource8testIdleEj : 72 -> 48
~ __ZN22GLRTextureViewResourceD0Ev : 44 -> 32
~ __ZN22GLRTextureViewResource7deallocEv : 60 -> 48
~ __ZN22GLRTextureViewResource8testIdleEj : 72 -> 48
~ __ZN18GLRTextureResourceD0Ev : 44 -> 32
~ __ZN18GLRTextureResource7deallocEv : 236 -> 224
~ __ZN18GLRTextureResource17getGLViewResourceEbbb15eGLRSamplerType : 384 -> 392
~ __ZN15GLRResourceListD1Ev : 84 -> 72
~ __ZN15GLRResourceListD0Ev : 92 -> 80
~ __ZN15GLRResourceList7deallocEv : 72 -> 60
~ __ZN15GLRResourceList13releaseToPoolEv : 144 -> 132
~ __ZZNSt3__112__hash_tableIP11GLRResourceNS_4hashIS2_EENS_8equal_toIS2_EENS_9allocatorIS2_EEE16__emplace_uniqueB9nqn220106IJRS2_EEENS_4pairINS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlRKS2_SB_E_clESO_SB_ : 580 -> 576
~ __ZN13GLDSamplerRecD0Ev : 44 -> 32
~ __ZN13GLDSamplerRec7deallocEv : 84 -> 72
~ __ZN13GLDSamplerRec16setSeamedCubemapEbb : 272 -> 260
~ __ZN16GLDShareGroupRec7deallocEv : 244 -> 232
~ __ZN16GLDShareGroupRec13contextRetainEv : 88 -> 76
~ __ZN16GLDShareGroupRec17createZeroTextureE15eGLRSamplerTypej : 1020 -> 1008
~ __ZN16GLDShareGroupRec11signalUsageEv : 68 -> 56
~ __ZN16GLDShareGroupRec9waitUsageEPVi : 88 -> 76
~ __ZN13GLDTextureRecD0Ev : 44 -> 32
~ __ZN13GLDTextureRec7deallocEv : 236 -> 224
~ __ZN13GLDTextureRec18uploadTextureLevelEjjjjjjjjjjjjjP12GLDBufferRecPhiiiU13block_pointerFPU30objcproto19MTLCommandBufferSPI11objc_objectvEU13block_pointerFvS4_jEU13block_pointerFvU13block_pointerFvvEESC_PK15GLDPixelModeRecbb : 3492 -> 3476
~ __ZN13GLDTextureRec12getLevelInfoEPK17GLDPluginStateReciijPi : 4580 -> 4680
~ __ZN13GLDTextureRec25canGenerateMipmapsWithCPUEv : 172 -> 160
~ _OUTLINED_FUNCTION_3 : 40 -> 28
~ _OUTLINED_FUNCTION_4 : 40 -> 28
~ __ZN20GLDComputeProgramRecD1Ev : 60 -> 48
~ __ZN20GLDComputeProgramRecD0Ev : 68 -> 56
~ __ZN20GLDComputeProgramRec7deallocEv : 88 -> 76
~ __ZN20GLDComputeProgramRec12createKernelEP16GLDShareGroupRecPP12GLDKernelRecPK17GLDKernelStateRecP23GLDKernelDeviceStateRecP18GLDKernelConfigRec : 2780 -> 2776
~ __ZN12GLDKernelRecD2Ev : 76 -> 64
~ __ZN12GLDKernelRecD0Ev : 44 -> 32
~ __ZN12GLDKernelRec7deallocEv : 216 -> 204
~ __ZN11GLDQueueRec13executeKernelEP12GLDKernelRecjPmS2_S2_mPPvS2_Pj : 1984 -> 1980
~ __Z35gldModuleStringFromPluginReturnDataP6NSData : 76 -> 64
~ __Z31gldMetalLibFromPluginReturnDataP6NSData : 76 -> 64
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIjmEENS_22__unordered_map_hasherIjNS_4pairIKjmEENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS6_SA_S8_EENS_9allocatorIS6_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS5_EEENSL_IJEEEEEENS4_INS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSM_SK_OSN_OSO_E_clESM_SK_SZ_S10_ : 532 -> 528
~ __ZNSt3__112__destroy_atB9nqn220106INS_4pairIKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_6vectorIyNS5_IyEEEEEEEEvPT_ : 88 -> 76
~ __ZN13GLDContextRec22addRenderPassResourcesEv : 224 -> 212
~ ____ZN13GLDContextRec13endRenderPassE19RenderPassEndReason_block_invoke : 64 -> 52
~ __ZN13GLDContextRec22setRenderVertexBuffersEv : 340 -> 328
~ __ZN13GLDContextRec23setComputeVertexBuffersEv : 340 -> 328
~ __ZN13GLDContextRec22handleSeparateBackFillE11MTLCullMode : 116 -> 104
~ __ZN13GLDContextRec20setRenderPolygonModeEv : 164 -> 152
~ __ZN13GLDContextRec25setRenderPrimitiveRestartEv : 140 -> 128
~ __ZN13GLDContextRec24setRenderProvokingVertexEv : 92 -> 80
~ __ZN13GLDContextRec24updateRenderDepthStencilEv : 684 -> 696
~ __ZN13GLDContextRec26setRenderDepthStencilStateEv : 84 -> 72
~ __ZN13GLDContextRec14setRenderStateEj : 184 -> 164
~ __ZN13GLDContextRec23setComputePipelineStateEv : 128 -> 116
~ __ZN13GLDContextRec18setRenderViewportsEv : 116 -> 104
~ __ZN13GLDContextRec18setRenderPointSizeEv : 316 -> 304
~ __ZZN13GLDContextRec30setTexturesAndSamplersInternalE12PipelineTypejP23SetSamplerStateIMPCacheP26SetSamplerStateLODIMPCacheP18SetTextureIMPCacheENKUljjE_clEjj : 2376 -> 2380
~ _OUTLINED_FUNCTION_3 : 36 -> 32
~ _OUTLINED_FUNCTION_4 : 12 -> 36
~ _OUTLINED_FUNCTION_5 : 32 -> 12
~ _OUTLINED_FUNCTION_9 : 48 -> 24
~ _OUTLINED_FUNCTION_10 : 24 -> 36
~ _OUTLINED_FUNCTION_11 : 32 -> 24
~ _OUTLINED_FUNCTION_16 : 40 -> 28
~ _OUTLINED_FUNCTION_29 : 32 -> 20
~ _OUTLINED_FUNCTION_30 : 32 -> 20
~ _OUTLINED_FUNCTION_33 : 32 -> 20
~ _OUTLINED_FUNCTION_44 : 12 -> 20
~ _OUTLINED_FUNCTION_54 : 16 -> 12
~ _OUTLINED_FUNCTION_56 : 44 -> 16
~ _OUTLINED_FUNCTION_58 : 12 -> 44
~ _OUTLINED_FUNCTION_59 : 20 -> 12
~ _OUTLINED_FUNCTION_64 : 32 -> 20
~ __ZN17GLDVertexArrayRecD0Ev : 44 -> 32
~ __ZN17GLDVertexArrayRec7deallocEv : 60 -> 48
~ __ZN17GLDVertexArrayRec13updateBuffersEy : 160 -> 156
~ __ZN17GLDVertexArrayRec24updateVertexArrayBuffersEyy : 472 -> 464
~ _gldBufferSubData : 808 -> 800
~ _gldClearFramebufferData : 2040 -> 2036
~ __ZN23GLRFrambufferAttachment11setResourceE14AttachmentTypeP13GLDTextureRecj : 164 -> 152
~ __ZN13GLDContextRecD0Ev : 44 -> 32
~ __ZN13GLDContextRec29getBufferResourceFromFreePoolEm14MTLStorageMode : 64 -> 52
~ __ZN13GLDContextRec31releaseBufferResourceToFreePoolEP17GLRBufferResource : 96 -> 84
~ ____ZN13GLDContextRec33flushPreprocessingCommandEncodersEb_block_invoke : 136 -> 124
~ ___copy_helper_block_e8_32r40r : 80 -> 68
~ ___destroy_helper_block_e8_32r40r : 68 -> 56
~ __ZN17GLRDeviceDrawableD0Ev : 44 -> 32
~ __ZN17GLRDeviceDrawable7deallocEv : 140 -> 128
~ __ZN11GLRDrawableD0Ev : 44 -> 32
~ __ZN11GLRDrawable7deallocEv : 288 -> 276
~ __ZL13createTextureP16GLDShareGroupRecijjjttjP11__IOSurfacetthjb : 1048 -> 1044
~ _OUTLINED_FUNCTION_1 : 24 -> 12
~ _OUTLINED_FUNCTION_2 : 24 -> 12
~ __ZN13GLDContextRec24drawableMultisampleDirtyEv : 108 -> 96
~ __Z8cl2MetalPU19objcproto9MTLDevice11objc_objectPKvmPKcRNSt3__113unordered_mapINS5_12basic_stringIcNS5_11char_traitsIcEENS5_9allocatorIcEEEENS5_6vectorIyNSA_IyEEEENS5_4hashISC_EENS5_8equal_toISC_EENSA_INS5_4pairIKSC_SF_EEEEEEPP7NSError : 256 -> 244
~ __ZN20GLRDataBufferManager5resetEv : 80 -> 68
~ __ZN20GLRDataBufferManager17releaseDataBufferEPU19objcproto9MTLBuffer11objc_object : 124 -> 112
~ __ZL23gldBeginPrimitiveBufferP13GLDContextRecjPi : 392 -> 376
~ __ZL21gldEndPrimitiveBufferP13GLDContextRecjji : 11452 -> 11412
~ __ZL20gldRenderVertexArrayP13GLDContextRecjjiijPKviS2_ : 39344 -> 39276
~ __ZNSt3__16vectorIP17GLRBufferResourceNS_9allocatorIS2_EEE24__emplace_back_slow_pathIJRKS2_EEEPS2_DpOT_ : 196 -> 192
~ ____ZN13GLDContextRec8drawCoreEjjijjjPU19objcproto9MTLBuffer11objc_objectjmS1_mPNSt3__16vectorIP17GLRBufferResourceNS2_9allocatorIS5_EEEE_block_invoke : 156 -> 144
~ ____ZN13GLDContextRec8drawCoreEjjijjjPU19objcproto9MTLBuffer11objc_objectjmS1_mPNSt3__16vectorIP17GLRBufferResourceNS2_9allocatorIS5_EEEE_block_invoke_2 : 156 -> 144
~ __ZN11GLDQueueRecD1Ev : 68 -> 56
~ __ZN11GLDQueueRecD0Ev : 76 -> 64
~ __ZN11GLDQueueRec7deallocEv : 172 -> 160
~ __ZN11GLDQueueRec5flushENS_9FlushModeEb : 448 -> 436
~ ____ZN11GLDQueueRec5flushENS_9FlushModeEb_block_invoke : 128 -> 116
~ __ZN11GLDQueueRec27prepareResourceForGPUAccessEP11GLRResourcej : 84 -> 72
~ _gldSetFenceOnQueue : 76 -> 64
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIjPU26objcproto15MTLSamplerState11objc_objectEENS_22__unordered_map_hasherIjNS_4pairIKjS3_EENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS8_SC_SA_EENS_9allocatorIS8_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSN_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSO_SM_OSP_OSQ_E_clESO_SM_S11_S12_ : 532 -> 528
~ __ZN13GLDContextRec19loadCurrentSamplersEj : 376 -> 372
~ __ZN20GLRRenderPipelineKey7deallocEv : 112 -> 100
~ __ZNK20GLRRenderPipelineKey20fillVertexDescriptorEP29MTLStageInputOutputDescriptorj : 680 -> 668
~ __ZN13GLDContextRec27prepareResourceForCPUAccessEP11GLRResourcej : 316 -> 304
~ __ZN13GLDContextRec8setFenceEP11GLDFenceRec : 96 -> 84
~ _gldTestObject : 512 -> 500
~ _gldFinishContext : 84 -> 72
~ ____ZN13GLDContextRec20flushContextInternalEv_block_invoke : 292 -> 280
~ ___copy_helper_block_e8_32r40r48r56r : 112 -> 100
~ ___destroy_helper_block_e8_32r40r48r56r : 92 -> 80
~ __ZN13GLDContextRec23dispatchImageQueueEventEP13GLDTextureRec : 100 -> 88
~ __ZN13GLDContextRec19loadCurrentTexturesEjPKy : 1400 -> 1396
~ ____ZN13GLDContextRec17modifyTexSubImageEP13GLDTextureReciiiiiiiijjPKviP12GLDBufferRecj_block_invoke : 172 -> 160
~ ____ZN13GLDContextRec17modifyTexSubImageEP13GLDTextureReciiiiiiiijjPKviP12GLDBufferRecj_block_invoke_2 : 152 -> 140
~ ____ZN13GLDContextRec27generateMipmapsWithCPUAsyncEP13GLDTextureRecm_block_invoke : 212 -> 200
~ __ZN13GLDContextRec15bindVertexArrayEP17GLDVertexArrayRecyy : 580 -> 588
~ gldPopulateRendererInfo.cold.1 : 80 -> 68
~ _ZN13GLDSamplerRec16setSeamedCubemapEbb.cold.1 : 116 -> 104
~ __ZN13GLDContextRec24setRenderProgramUniformsEv : 2424 -> 2400
~ __ZN13GLDContextRec25setComputeProgramUniformsEv : 1840 -> 1820
~ gldPresentFramebufferData.cold.1 : 116 -> 104
~ gldGenerateTexMipmaps.cold.1 : 88 -> 76
```
