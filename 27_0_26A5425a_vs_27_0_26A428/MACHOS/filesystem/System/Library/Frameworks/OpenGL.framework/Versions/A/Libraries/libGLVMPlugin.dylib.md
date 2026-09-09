## libGLVMPlugin.dylib

> `/System/Library/Frameworks/OpenGL.framework/Versions/A/Libraries/libGLVMPlugin.dylib`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__AUTH.__data`
- `__DATA.__data`

```diff

 24.0.2.0.0
-  __TEXT.__text: 0x5f330
+  __TEXT.__text: 0x5ec4c
   __TEXT.__const: 0x18a8
   __TEXT.__cstring: 0x6bdc
   __TEXT.__oslogstring: 0x3
-  __TEXT.__unwind_info: 0x968
+  __TEXT.__unwind_info: 0xb88
   __TEXT.__auth_stubs: 0xf20
   __DATA_CONST.__const: 0x20d0
   __DATA_CONST.__got: 0x30
Functions:
~ _gleBuildVertexSubmitFunc : 4428 -> 4424
~ _oglCodeGenServiceGenerateIR : 616 -> 568
~ __ZNK4llvm9StringRef10drop_frontEm : 48 -> 36
~ _cvmsPluginServiceTerminate : 240 -> 228
~ __ZNK4llvm9StringRef6substrEmm : 60 -> 52
~ __ZN4llvm16CVMMemoryManagerD2Ev : 104 -> 92
~ __ZN4llvm16CVMMemoryManagerD0Ev : 56 -> 44
~ _cvmDeleteFunctionInBuilder : 88 -> 76
~ __ZNK4llvm18value_use_iteratorINS_4UserEEdeEv : 40 -> 28
~ __ZN4llvm18ValueMapCallbackVHIPKNS_5ValueENS_6WeakVHENS_14ValueMapConfigIS3_EEED0Ev : 116 -> 104
~ __ZN4llvm8DenseMapINS_18ValueMapCallbackVHIPKNS_5ValueENS_6WeakVHENS_14ValueMapConfigIS4_EEEES5_NS_12DenseMapInfoIS8_EEE4growEj : 184 -> 152
~ __ZNSt3__16vectorIPN4llvm5ValueENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJS3_EEEPS3_DpOT_ : 196 -> 192
~ __ZNSt3__16vectorIPN4llvm5ValueENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJRKS3_EEEPS3_DpOT_ : 196 -> 192
~ __ZNSt3__16vectorIPN4llvm4TypeENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJS3_EEEPS3_DpOT_ : 196 -> 192
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _OUTLINED_FUNCTION_1 : 44 -> 32
~ _OUTLINED_FUNCTION_2 : 44 -> 32
~ _OUTLINED_FUNCTION_3 : 44 -> 32
~ _OUTLINED_FUNCTION_4 : 44 -> 32
~ _OUTLINED_FUNCTION_5 : 44 -> 32
~ _OUTLINED_FUNCTION_6 : 44 -> 32
~ _PPParserMacroFree : 124 -> 112
~ _PPParserIdentifierFree : 64 -> 52
~ _PPParserPreprocessString : 2532 -> 2524
~ _PPParserScopeFree : 160 -> 148
~ _PPParserFree : 124 -> 112
~ _PPParserLabelsFree : 104 -> 92
~ _glpProgram_PPStreamAddAttribBinding : 104 -> 92
~ _glpProgram_PPStreamAddOutputBinding : 84 -> 72
~ _glpProgram_PPStreamAddLabel : 84 -> 72
~ _llvmir_PPStreamAddAttribBinding : 148 -> 136
~ _PPParserDeclareNVAddressRegisters : 84 -> 72
~ _PPParserParseOperation : 1552 -> 1548
~ _PPParserParseStatement : 2968 -> 2872
~ _glvmGetSourceOffsetStride : 2032 -> 2044
~ _glvmBuildVPTransformFunction : 8284 -> 8380
~ _glvmBuildCPTransformFunction : 8012 -> 8124
~ _glvmBuildEPTransformFunction : 7940 -> 8052
~ _glvmBuildGPTransformFunction : 8232 -> 8340
~ _glvmBuildFPTransformFunction : 15052 -> 15044
~ _glpStringHashPut : 156 -> 144
~ __glpStringHashRehash : 160 -> 148
~ _glpDestroyPointerHash : 100 -> 88
~ _glpPointerHashPut : 148 -> 136
~ __glpPointerHashRehash : 168 -> 156
~ _applevec4TypeSize : 324 -> 312
~ _applevec4MatrixStride : 40 -> 28
~ _std140TypeSize : 240 -> 228
~ _std140TypeAlign : 172 -> 160
~ _glpDestroyPoolAllocator : 100 -> 88
~ _glpLLVMBuildSubroutinesTypeClasses : 1108 -> 1088
~ _glpLLVMCleanUpASTObjects : 428 -> 416
~ _glpLLVMCGFindSamplersAndBuffers : 1200 -> 1160
~ _glpLLVMCGNode : 976 -> 796
~ _glpGetConstantInt32 : 108 -> 96
~ _glpLLVMStringMetadata : 72 -> 60
~ _glpLLVMCGDeclareUniformBufferObject : 472 -> 464
~ _glpLLVMCGDeclareTFBuffer : 440 -> 432
~ _glpLLVMGetTextureTypeFromSampler : 136 -> 124
~ _glpLLVMAddParameterToHash : 96 -> 84
~ _glpLLVMCGImplicitConversion : 980 -> 896
~ _glpLLVMCGConstant : 496 -> 484
~ _glpLLVMCGNegate : 192 -> 168
~ _glpLLVMCGLogicalNot : 96 -> 84
~ _glpLLVMCGParameterDeclaration : 116 -> 104
~ _glpLLVMCGFunctionPrototype : 10252 -> 10244
~ _glpLLVMCGFunctionDefinition : 2404 -> 2388
~ _glpLLVMCGCaseStatement : 172 -> 160
~ _glpLLVMCGDefaultStatement : 88 -> 76
~ _glpLLVMCGBreakStatement : 68 -> 56
~ _glpLLVMCGContinueStatement : 68 -> 56
~ _glpLLVMCGReturnStatement : 124 -> 100
~ _glpLLVMCGLValue : 2868 -> 2844
~ _glpLLVMWriteOutput : 696 -> 684
~ _glpPrimitiveTypeToLLVMType : 416 -> 368
~ _glpTypeGetVec4s : 56 -> 44
~ _glpLLVMGetMinCommonType : 592 -> 572
~ _glpLLVMCreateConstantVectors : 416 -> 400
~ _glpGetComponentCount : 80 -> 68
~ _glpLLVMCGSamplerNode : 1352 -> 1336
~ _glpLLVMBuildNormalize : 312 -> 288
~ _glpLLVMBuildConvert : 180 -> 168
~ _glpLLVMBuildMix : 536 -> 524
~ _glpCGSwizzle : 1412 -> 1400
~ _glpAddGep : 336 -> 328
~ _glpLLVMLoadVector : 776 -> 752
~ _glpLoadSourceVariable : 260 -> 248
~ _glpLLVMUnpackDoubles : 116 -> 104
~ _glpLLVMCGGlobalVariable : 972 -> 948
~ _glpLLVMGetAggregateType : 268 -> 256
~ _glpMetalGetArgTypeNameFromASTType : 328 -> 316
~ _glpLLVMCGIfStatementShortCircuit : 368 -> 356
~ _glpLLVMReadUniform : 352 -> 328
~ _glpMangleTypeName : 796 -> 784
~ _glpLLVMGetNamedTypeInner : 84 -> 72
~ _glpLLVMEmitBranchInnerReal : 100 -> 88
~ _glpLLVMPackVectorInner : 936 -> 900
~ _glpLLVMUnpackTypeInner : 1076 -> 1040
~ _glpLLVMAddFunctionAttr : 80 -> 68
~ _glpLLVMSetGlobalConstant : 72 -> 60
~ _glpLLVMSetInitializer : 72 -> 60
~ _glpLLVMCreateBuilderInContext : 108 -> 96
~ _glpLLVMMoveBasicBlockBefore : 72 -> 60
~ _glpLLVMPositionBuilderAtEnd : 60 -> 48
~ _glpLLVMEmitBranch : 60 -> 48
~ _glpLLVMNamedMetadata : 108 -> 96
~ _glpLLVMBuildStore : 76 -> 64
~ _glpLLVMAddCase : 96 -> 84
~ _glpLLVMBuildBr : 60 -> 48
~ _glpLLVMBuildCondBr : 100 -> 88
~ _glpLLVMDIBuilderCreateCompileUnitStub : 96 -> 84
~ _glpLLVMDIBuilderCreateFileStub : 96 -> 84
~ _glpLLVMDIBuilderCreateSubProgramStub : 108 -> 96
~ _glpLLVMSetCurrentLineStub : 416 -> 404
~ _glpGetIBVariableObjectCount : 240 -> 228
~ _glpPrimitiveTypeGetScalarType : 136 -> 112
~ _glpPrimitiveTypeGetScalarCount : 128 -> 116
~ _glpPrimitiveTypeGetMaxComponentsPerVec4 : 100 -> 96
~ _glpDestroyDeserialContext : 104 -> 92
~ _glpGetPrimitiveType : 120 -> 108
~ _glpStructTypeGetSizesAndAlignments : 432 -> 412
~ _deleteBitCodeStorage : 96 -> 84
~ _glpLLVMSetupModule : 72 -> 60
~ _glpLLVMDIBuilderCreateSubProgram : 72 -> 60
~ _glpLLVMDIBuilderDelete : 64 -> 52
~ __ZNSt3__16vectorIPN4llvm6MDNodeENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJRKS3_EEEPS3_DpOT_ : 196 -> 192
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _PPStreamChunkListFree : 96 -> 84
~ _PPStreamFree : 172 -> 160
~ _gleLLVMGetConstantInt32 : 80 -> 68
~ _gleGetLLVMTypeFromType : 296 -> 284
~ _gleLLVMAddVoidFunctionCall : 112 -> 100
~ _readTempValue : 196 -> 184
~ _readAddressValue : 196 -> 184
~ _gleLLVMVectorExtend : 480 -> 468
~ _readCCValue : 156 -> 144
~ _TestCC : 636 -> 600
~ _gleVStateProgram_AttribToFunction : 316 -> 304
~ _gleVStateProgram_LightingStage : 47540 -> 47532
~ _gleFStateProgram_AttribToFunction : 520 -> 484
```
