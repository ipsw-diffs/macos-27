## JavaScriptCore

> `/System/Library/Frameworks/JavaScriptCore.framework/Versions/A/JavaScriptCore`

```diff

-625.2.4.1.0
-  __TEXT.__text: 0x231bc30
+625.2.5.11.1
+  __TEXT.__text: 0x2318aec
   __TEXT.__jsc_int: 0x6a3b8
   __TEXT.__objc_methlist: 0xb9c
-  __TEXT.__const: 0xa10a4
+  __TEXT.__const: 0xa10b4
   __TEXT.__dlsym_cstr: 0x34
-  __TEXT.__cstring: 0x1344a4
+  __TEXT.__cstring: 0x134545
   __TEXT.__oslogstring: 0xa0f
-  __TEXT.__gcc_except_tab: 0x28a0
+  __TEXT.__gcc_except_tab: 0x2894
   __TEXT.__ustring: 0x10
-  __TEXT.__unwind_info: 0x1fcc8
+  __TEXT.__unwind_info: 0x1fcc0
   __TEXT.__eh_frame: 0x50
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH_CONST.__objc_const: 0xdf8
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__auth_got: 0x17b0
-  __AUTH.__objc_data: 0xf0
-  __AUTH.__data: 0x250
+  __AUTH.__objc_data: 0xa0
+  __AUTH.__data: 0x200
   __DATA.__objc_ivar: 0x80
   __DATA.__crash_info: 0x148
-  __DATA.__data: 0x104b4
-  __DATA.__common: 0x28d8
+  __DATA.__data: 0x103fc
+  __DATA.__common: 0x28c0
   __DATA.__bss: 0x12d0
   __DATA_DIRTY.__objc_ivar: 0x8
-  __DATA_DIRTY.__objc_data: 0x280
-  __DATA_DIRTY.__data: 0x13fb4
+  __DATA_DIRTY.__objc_data: 0x2d0
+  __DATA_DIRTY.__data: 0x140bc
   __DATA_DIRTY.__wtf_config: 0x4000
   __DATA_DIRTY.__bss: 0xb1d8
-  __DATA_DIRTY.__common: 0x4865b8
+  __DATA_DIRTY.__common: 0x4865d0
   - /System/Library/Frameworks/BrowserEngineCore.framework/Versions/A/BrowserEngineCore
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 39348
+  Functions: 39346
   Symbols:   47599
-  CStrings:  26171
+  CStrings:  26176
 
Symbols:
+ GCC_except_table218
+ __ZN3JSC11MarkedBlock6Handle16specializedSweepILb0ELNS1_9EmptyModeE0ELNS1_9SweepModeE0ELNS1_20SweepDestructionModeE0ELNS1_12ScribbleModeE0ELNS1_18NewlyAllocatedModeE0ELNS1_9MarksModeE0ENS_31JSDestructibleObjectDestroyFuncEEEvPNS_8FreeListES3_S4_S5_S6_S7_S8_RKT6_
+ __ZN3JSC11MarkedBlock6Handle16specializedSweepILb1ELNS1_9EmptyModeE0ELNS1_9SweepModeE0ELNS1_20SweepDestructionModeE1ELNS1_12ScribbleModeE0ELNS1_18NewlyAllocatedModeE1ELNS1_9MarksModeE1ENS_22IsoInlinedHeapCellTypeINS_12JSRopeStringEE11DestroyFuncEEEvPNS_8FreeListES3_S4_S5_S6_S7_S8_RKT6_
+ __ZN3JSC16NativeDOMJITCodeC2ENS_21MacroAssemblerCodeRefILN3WTF6PtrTagE1427EEENS_7JITTypeENS_9IntrinsicEPKNS_6DOMJIT9SignatureE
+ __ZN3JSC19MacroAssemblerARM644or16ENS_14ARM64Registers10RegisterIDENS_22AbstractMacroAssemblerINS_15ARM64EAssemblerEE15AbsoluteAddressE
+ __ZN3JSC22SetPrivateBrandVariantD1Ev
+ __ZN3JSC23JSGenericTypedArrayViewINS_13Uint16AdaptorEE20createWithFastVectorEPNS_14JSGlobalObjectEPNS_9StructureEmPv
+ __ZN3JSC28JITGetByValWithThisGenerator24setUpPropertyInlineCacheINS_19PropertyInlineCacheEEEvRT_PNS_9CodeBlockENS_10AccessTypeENS_9CacheTypeENS_10CodeOriginENS_13CallSiteIndexERKNS_11RegisterSetENS_11JSValueRegsESE_SE_SE_NS_14ARM64Registers10RegisterIDESG_
+ __ZN3JSC2B310BasicBlock9appendNewINS0_5ValueEJNS0_4KindENS0_6OriginEPS3_S6_EEEPT_RNS0_9ProcedureEDpT0_
+ __ZN3JSC2B312AbstractHeap12changeParentEPS1_
+ __ZN3JSC2B312_GLOBAL__N_110LowerToAir6appendIJNS0_3Air3TmpES5_RS5_EEEvNS4_4KindEDpOT_
+ __ZN3JSC3DFG14ByteCodeParser16handleNewFuncExpINS_26OpNewAsyncGeneratorFuncExpEEEvNS0_8NodeTypeET_
+ __ZN3JSC3DFG14SpeculativeJIT39tryHandleOrGetExceptionUnderSilentSpillIPFNS_24ExceptionOperationResultIPNS_8JSStringEEEPNS_14JSGlobalObjectEPNS_10JSFunctionEENS_14ARM64Registers10RegisterIDEJEN3WTF6VectorINS0_22SilentRegisterSavePlanELm2ENSF_15CrashOnOverflowELm16ENSF_10FastMallocEEEEENSt3__18optionalISE_EERKT2_T0_DpT1_
+ __ZN3JSC3DFG21CallSlowPathGeneratorINS_22AbstractMacroAssemblerINS_15ARM64EAssemblerEE8JumpListEPFNS_24ExceptionOperationResultIPNS_8JSStringEEEPNS_14JSGlobalObjectEPNS_10JSFunctionEENS_14ARM64Registers10RegisterIDEE5setUpEPNS0_14SpeculativeJITE
+ __ZN3JSC3DFG21CallSlowPathGeneratorINS_22AbstractMacroAssemblerINS_15ARM64EAssemblerEE8JumpListEPFNS_24ExceptionOperationResultIPNS_8JSStringEEEPNS_14JSGlobalObjectEPNS_10JSFunctionEENS_14ARM64Registers10RegisterIDEE8tearDownEPNS0_14SpeculativeJITE
+ __ZN3JSC3DFG21CallSlowPathGeneratorINS_22AbstractMacroAssemblerINS_15ARM64EAssemblerEE8JumpListEPFNS_24ExceptionOperationResultIPNS_8JSStringEEEPNS_14JSGlobalObjectEPNS_10JSFunctionEENS_14ARM64Registers10RegisterIDEEC2ES5_PNS0_14SpeculativeJITENS_18SpillRegistersModeENS0_25ExceptionCheckRequirementESH_
+ __ZN3JSC3DFG21newTypedArrayWithSizeINS_23JSGenericTypedArrayViewINS_13Uint16AdaptorEEEEEPcPNS_14JSGlobalObjectERNS_2VMEPNS_9StructureElS5_
+ __ZN3JSC3DFG39CallResultAndArgumentsSlowPathGeneratorINS_22AbstractMacroAssemblerINS_15ARM64EAssemblerEE8JumpListEPFNS_24ExceptionOperationResultIPNS_8JSStringEEEPNS_14JSGlobalObjectEPNS_10JSFunctionEENS_14ARM64Registers10RegisterIDEJNS0_11JITCompiler16LinkableConstantESH_EE17unpackAndGenerateIJLm0ELm1EEEEvPNS0_14SpeculativeJITENSt3__116integer_sequenceImJXspT_EEEE
+ __ZN3JSC3DFG39CallResultAndArgumentsSlowPathGeneratorINS_22AbstractMacroAssemblerINS_15ARM64EAssemblerEE8JumpListEPFNS_24ExceptionOperationResultIPNS_8JSStringEEEPNS_14JSGlobalObjectEPNS_10JSFunctionEENS_14ARM64Registers10RegisterIDEJNS0_11JITCompiler16LinkableConstantESH_EEC2ES5_PNS0_14SpeculativeJITESF_NS_18SpillRegistersModeENS0_25ExceptionCheckRequirementESH_SJ_SH_
+ __ZN3JSC3DFGL13getExecutableERNS0_11JITCompilerENS_14ARM64Registers10RegisterIDES4_
+ __ZN3JSC3FTL12_GLOBAL__N_112LowerDFGToB312exitArgumentERN3WTF6VectorIPNS_2B35ValueELm16ENS3_15CrashOnOverflowELm16ENS3_10FastMallocEEENS_10DataFormatES7_
+ __ZN3JSC3FTL12_GLOBAL__N_112LowerDFGToB323compileGetByValWithThisEv
+ __ZN3JSC3FTL13callOperationIJNS_22AbstractMacroAssemblerINS_15ARM64EAssemblerEE13TrustedImmPtrENS_14ARM64Registers10RegisterIDES7_S7_S7_S7_EEENS0_12SlowPathCallERNS_2VMERKNS_17ScalarRegisterSetERNS_12CCallHelpersEPNS4_8JumpListEN3WTF7CodePtrILNSI_6PtrTagE1ELNSI_18FunctionAttributesE0EEES7_DpT_
+ __ZN3JSC4Wasm14IPIntGenerator23branchTargetMetadataForERKNS0_16IPIntControlTypeEj
+ __ZN3JSC4Wasm14IPIntGeneratorD2Ev
+ __ZN3JSC9Structure11markIfCheapINS_19AbstractSlotVisitorEEEbRT_
+ __ZN3JSC9Structure21nonPropertyTransitionERNS_2VMEPS0_NS_14TransitionKindEPNS_41DeferredStructureTransitionWatchpointFireE
+ __ZN3JSCL10copyMemoryEPvPKvm
+ __ZN3JSCL21functionWasmCalleeIDsEPNS_14JSGlobalObjectEPNS_9CallFrameE
+ __ZN3WTF11PrintStream10atomicallyIZN3JSC11MarkedBlock6Handle16specializedSweepILb1ELNS4_9EmptyModeE0ELNS4_9SweepModeE1ELNS4_20SweepDestructionModeE1ELNS4_12ScribbleModeE0ELNS4_18NewlyAllocatedModeE1ELNS4_9MarksModeE1ENS2_15IsoHeapCellTypeEEEvPNS2_8FreeListES6_S7_S8_S9_SA_SB_RKT6_EUlRS0_E_EEvRKT_
+ __ZN3WTF11PrintStream10atomicallyIZN3JSC11MarkedBlock6Handle16specializedSweepILb1ELNS4_9EmptyModeE0ELNS4_9SweepModeE1ELNS4_20SweepDestructionModeE1ELNS4_12ScribbleModeE0ELNS4_18NewlyAllocatedModeE1ELNS4_9MarksModeE1ENS2_22IsoInlinedHeapCellTypeINS2_12JSRopeStringEE11DestroyFuncEEEvPNS2_8FreeListES6_S7_S8_S9_SA_SB_RKT6_EUlRS0_E_EEvRKT_
+ __ZN3WTF12RefCountableIN3JSC28JITGetByValWithThisGeneratorEEC2IJPNS1_9CodeBlockERPNS1_19PropertyInlineCacheENS1_7JITTypeERKNS1_10CodeOriginERNS1_13CallSiteIndexENS1_10AccessTypeENS1_11RegisterSetENS1_11JSValueRegsESI_SI_SI_RKNS1_14ARM64Registers10RegisterIDERSK_EEEDpOT_
+ __ZN3WTF12VectorBufferIN3JSC2B33Air4InstELm0ENS_10FastMallocEE5adoptEOS6_
+ __ZN3WTF25ThreadSafeWeakOrStrongPtrIN3JSC4Wasm9BBQCalleeEED2Ev
+ __ZN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_3vJRNS2_17DeferredWorkTimer6TicketEEE4callESA_
+ __ZN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_3vJRNS2_17DeferredWorkTimer6TicketEEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_3vJRNS2_17DeferredWorkTimer6TicketEEED1Ev
+ __ZN3WTF6VectorIN3JSC12GetByVariantELm1ENS_15CrashOnOverflowELm16ENS_10FastMallocEE14shrinkCapacityEm
+ __ZN3WTF6VectorIN3JSC4Wasm10IPIntValueELm8ENS_15CrashOnOverflowELm16ENS_10FastMallocEE15reserveCapacityILNS_13FailureActionE0EEEbm
+ __ZN3WTF7HashMapIPN3JSC2B35ValueEPNS2_8VariableENS_11DefaultHashIS4_EENS_10HashTraitsIS4_EENS9_IS6_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE0ENS_10FastMallocEE3addIS6_EENS_18HashTableAddResultINS_17HashTableIteratorINS_9HashTableIS4_NS_12KeyValuePairIS4_S6_EENS_24KeyValuePairKeyExtractorISL_EES8_NSF_18KeyValuePairTraitsESA_SE_EES4_SL_SN_S8_SO_SA_EEEERKS4_OT_
+ __ZN3WTF7HashMapIjNS_9RetainPtrI12NSDictionaryEENS_11DefaultHashIjEENS_10HashTraitsIjEENS6_IS3_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE0ENS_10FastMallocEE9inlineSetIjRS3_EENS_18HashTableAddResultINS_17HashTableIteratorINS_9HashTableIjNS_12KeyValuePairIjS3_EENS_24KeyValuePairKeyExtractorISJ_EES5_NSC_18KeyValuePairTraitsES7_SB_EEjSJ_SL_S5_SM_S7_EEEEOT_OT0_
+ __ZN3WTF8LivenessIN3JSC2B33Air18TmpLivenessAdapterILNS2_4BankE0ELNS3_3Arg11TemperatureE0EEEE7Workset6removeEj
+ __ZN3WTF8LivenessIN3JSC2B33Air18TmpLivenessAdapterILNS2_4BankE1ELNS3_3Arg11TemperatureE0EEEE7Workset6removeEj
+ __ZN3WTF8LivenessIN3JSC2B33Air25UnifiedTmpLivenessAdapterEE7Workset6removeEj
+ __ZN3WTF9HashTableIPN3JSC6JSCellES3_NS_17IdentityExtractorENS_11DefaultHashIS3_EENS_10HashTraitsIS3_EES8_NS_10FastMallocEE6rehashENS_7CheckedIjNS_15CrashOnOverflowEEEPS3_
+ __ZN3WTF9URLParser13percentDecodeENSt3__14spanIKhLm18446744073709551615EEE
+ __ZN3WTF9toCStringIJA16_cN3JSC12VisitRaceKeyEEEENS_7CStringEDpRKT_
+ __ZN9Inspector15RemoteInspector19updateTargetListingERKNS_24RemoteControllableTargetE
+ __ZNK3JSC3DFG11ExitProfile11hasExitSiteERKNS_18ConcurrentJSLockerERKNS0_16FrequentExitSiteE
+ __ZNK3JSC4Wasm11CalleeGroup18calleeIsReferencedERKN3WTF14AbstractLockerEPNS0_6CalleeE
+ __ZNK3JSC4Wasm14IPIntGenerator4failIJPKcjS4_tEEENSt3__110unexpectedIN3WTF6StringEEEDpT_
+ __ZNK3JSC9Structure21findPropertyHashEntryENS_12PropertyNameE
+ __ZNK3WTF29ThreadSafeWeakPtrControlBlock29makeStrongReferenceIfPossibleIN3JSC4Wasm17OMGOSREntryCalleeEEENS_6RefPtrIT_NS_12RawPtrTraitsIS6_EENS_21DefaultRefDerefTraitsIS6_EEEEPKS6_
+ __ZNK3WTF9HashTableIPN3JSC3DFG4NodeENS_12KeyValuePairIS4_S4_EENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS4_EENS_7HashMapIS4_S4_SA_NS_10HashTraitsIS4_EESD_NS_15HashTableTraitsELNS_17ShouldValidateKeyE0ENS_10FastMallocEE18KeyValuePairTraitsESD_SG_E5beginEv
+ __ZTVN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_3vJRNS2_17DeferredWorkTimer6TicketEEEE
+ __ZZN3JSC2B33Air6Greedy15GreedyAllocator22trySplitAroundClobbersILNS0_4BankE1EEEbNS1_3TmpERNS2_7TmpDataEENKUlRT_E_clINS2_13RegisterRange17AllocatedIntervalEEEN3WTF15IterationStatusESA_
+ __ZZN3JSC3FTL23createLazyCallGeneratorINS_14ARM64Registers10RegisterIDEJNS_22AbstractMacroAssemblerINS_15ARM64EAssemblerEE13TrustedImmPtrES3_S3_S3_S3_S3_EEEN3WTF3RefINS8_10SharedTaskIFvRNS_12CCallHelpersERNS0_12LazySlowPath16GenerationParamsEEEENS8_12RawPtrTraitsISH_EENS8_21DefaultRefDerefTraitsISH_EEEERNS_2VMENS8_7CodePtrILNS8_6PtrTagE1ELNS8_18FunctionAttributesE0EEET_DpT0_ENKUlSC_SF_E_clESC_SF_
+ __ZZN3JSC6ParserINS_5LexerIhEEE17parseFunctionInfoINS_10ASTBuilderEEEbRT_NS_24FunctionNameRequirementsEbNS_15ConstructorKindENS_12SuperBindingEjRNS_18ParserFunctionInfoIS6_EENS3_22FunctionDefinitionTypeENSt3__18optionalIiEEENKUlvE0_clEv
- __ZN3JSC10OpGetByVal31emitWithSmallestSizeRequirementILNS_10OpcodeSizeE1ENS_17BytecodeGeneratorEEEvPT0_NS_15VirtualRegisterES6_S6_j
- __ZN3JSC10OpGetByVal8emitImplILNS_10OpcodeSizeE1ELb1ENS_17BytecodeGeneratorEEEbPT1_NS_15VirtualRegisterES6_S6_jj
- __ZN3JSC11ArrayBuffer15notifyDetachingERNS_2VME
- __ZN3JSC12PutByVariant10transitionENS_19CacheableIdentifierERKNS_12StructureSetEPNS_9StructureERKNS_26ObjectPropertyConditionSetEi
- __ZN3JSC12allocateCellINS_23JSGenericTypedArrayViewINS_11Int8AdaptorEEEEEPvRNS_2VMEm
- __ZN3JSC13MicrotaskCall19unlinkOrUpgradeImplERNS_2VMEPNS_9CodeBlockES4_
- __ZN3JSC13MicrotaskCall5clearEv
- __ZN3JSC13NativeJITCodeC2ENS_21MacroAssemblerCodeRefILN3WTF6PtrTagE1427EEENS_7JITTypeENS_9IntrinsicENS_7JITCode14ShareAttributeE
- __ZN3JSC13OpCallVarargs6decodeEPKh
- __ZN3JSC13PropertyTable6createERNS_2VMEj
- __ZN3JSC18JITCodeWithCodeRefD2Ev
- __ZN3JSC19ArrayBufferContentsC2EOS0_
- __ZN3JSC19ArrayBufferContentsaSEOS0_
- __ZN3JSC19MacroAssemblerARM6419convertInt32ToFloatENS_14ARM64Registers10RegisterIDENS1_12FPRegisterIDE
- __ZN3JSC20typeOfDoubleNegationEy
- __ZN3JSC22AbstractMacroAssemblerINS_15ARM64EAssemblerEE7commentIJA13_cNS_14ARM64Registers12FPRegisterIDEA17_cNS_11JSValueRegsEA28_cNS_20RegisterAtOffsetListEEEEvDpRKT_
- __ZN3JSC22AbstractMacroAssemblerINS_15ARM64EAssemblerEE7commentIJA30_cEEEvDpRKT_
- __ZN3JSC22AbstractMacroAssemblerINS_15ARM64EAssemblerEE7commentIJA5_cjA4_cNS_4Wasm4TypeEEEEvDpRKT_
- __ZN3JSC26UnlinkedFunctionExecutable9clearCodeERNS_2VME
- __ZN3JSC2B33Air6Greedy15GreedyAllocator17allocateRegistersILNS0_4BankE1EEEvv
- __ZN3JSC3DFG10BasicBlock7SSADataD2Ev
- __ZN3JSC3DFG14ByteCodeParser18handleIteratorOpenEPKNS_15BaseInstructionINS_14JSOpcodeTraitsEEENS_13BytecodeIndexE
- __ZN3JSC3DFG14ByteCodeParser25handleModuleNamespaceLoadENS_15VirtualRegisterEyPNS0_4NodeENS_11GetByStatusE
- __ZN3JSC3DFG14SpeculativeJIT25compilePutPrivateNameByIdEPNS0_4NodeE
- __ZN3JSC3DFG4Node25convertToMultiGetByOffsetEPNS0_20MultiGetByOffsetDataE
- __ZN3JSC3FTL12_GLOBAL__N_112LowerDFGToB320compileToPropertyKeyEv
- __ZN3JSC3FTL12_GLOBAL__N_112LowerDFGToB321compileMatchStructureEv
- __ZN3JSC3FTL12_GLOBAL__N_112LowerDFGToB324exitValueForAvailabilityERN3WTF6VectorIPNS_2B35ValueELm16ENS3_15CrashOnOverflowELm16ENS3_10FastMallocEEERKNS3_7HashMapIPNS_3DFG4NodeEPNS0_29ExitTimeObjectMaterializationENS3_11DefaultHashISF_EENS3_10HashTraitsISF_EENSK_ISH_EENS3_15HashTableTraitsELNS3_17ShouldValidateKeyE0ES9_EENSD_12AvailabilityE
- __ZN3JSC4Wasm15TypeInformation15getCanonicalRTTEm
- __ZN3JSC7VMTraps25tryInstallTrapBreakpointsERNS0_13SignalContextEN3WTF11StackBoundsE
- __ZN3JSC9CodeBlock22optimizeNextInvocationEv
- __ZN3JSC9CodeBlock7jitSoonEv
- __ZN3JSCL25toStringWithRadixInternalEij
- __ZN3WTF11PrintStream10atomicallyIZN3JSC11MarkedBlock6Handle16specializedSweepILb1ELNS4_9EmptyModeE0ELNS4_9SweepModeE0ELNS4_20SweepDestructionModeE1ELNS4_12ScribbleModeE0ELNS4_18NewlyAllocatedModeE1ELNS4_9MarksModeE1ENS2_15IsoHeapCellTypeEEEvPNS2_8FreeListES6_S7_S8_S9_SA_SB_RKT6_EUlRS0_E_EEvRKT_
- __ZN3WTF11PrintStream10atomicallyIZN3JSC11MarkedBlock6Handle16specializedSweepILb1ELNS4_9EmptyModeE0ELNS4_9SweepModeE0ELNS4_20SweepDestructionModeE1ELNS4_12ScribbleModeE0ELNS4_18NewlyAllocatedModeE1ELNS4_9MarksModeE1ENS2_22IsoInlinedHeapCellTypeINS2_12JSRopeStringEE11DestroyFuncEEEvPNS2_8FreeListES6_S7_S8_S9_SA_SB_RKT6_EUlRS0_E_EEvRKT_
- __ZN3WTF11PrintStream10atomicallyIZN3JSC11MarkedBlock6Handle16specializedSweepILb1ELNS4_9EmptyModeE0ELNS4_9SweepModeE0ELNS4_20SweepDestructionModeE1ELNS4_12ScribbleModeE0ELNS4_18NewlyAllocatedModeE1ELNS4_9MarksModeE1ENS2_31JSDestructibleObjectDestroyFuncEEEvPNS2_8FreeListES6_S7_S8_S9_SA_SB_RKT6_EUlRS0_E_EEvRKT_
- __ZN3WTF17GenericHashTraitsIN3JSC4WeakINS1_8JSStringEEEE13assignToEmptyIS4_PS3_EEvRT_OT0_
- __ZN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_2vJRNS2_17DeferredWorkTimer6TicketEEE4callESA_
- __ZN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_2vJRNS2_17DeferredWorkTimer6TicketEEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_2vJRNS2_17DeferredWorkTimer6TicketEEED1Ev
- __ZN3WTF7HashMapIPN3JSC3DFG10BasicBlockENS_6VectorIPNS2_4NodeELm8ENS_15CrashOnOverflowELm16ENS_10FastMallocEEENS_11DefaultHashIS4_EENS_10HashTraitsIS4_EENSD_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE0ES9_E3addISA_EENS_18HashTableAddResultINS_17HashTableIteratorINS_9HashTableIS4_NS_12KeyValuePairIS4_SA_EENS_24KeyValuePairKeyExtractorISO_EESC_NSI_18KeyValuePairTraitsESE_S9_EES4_SO_SQ_SC_SR_SE_EEEERKS4_OT_
- __ZN3WTF7HashMapIPN3JSC6JSCellENS_6VectorINS1_12WriteBarrierINS1_7UnknownENS_14RawValueTraitsIS6_EEEELm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEEENS_11DefaultHashIS3_EENS_10HashTraitsIS3_EENSF_ISC_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE0ESB_E3addISC_EENS_18HashTableAddResultINS_17HashTableIteratorINS_9HashTableIS3_NS_12KeyValuePairIS3_SC_EENS_24KeyValuePairKeyExtractorISQ_EESE_NSK_18KeyValuePairTraitsESG_SB_EES3_SQ_SS_SE_ST_SG_EEEERKS3_OT_
- __ZN3WTF8LivenessIN3JSC2B33Air25UnifiedTmpLivenessAdapterEE8IteratorppEv
- __ZN3WTF8toStringIJNSt3__14spanIKDuLm18446744073709551615EEEEEENS_6StringEDpRKT_
- __ZN3WTF9HashTableINSt3__15tupleIJPN3JSC2B35ValueEyEEENS_12KeyValuePairIS7_NS_6VectorIS6_Lm1ENS_15CrashOnOverflowELm16ENS_10FastMallocEEEEENS_24KeyValuePairKeyExtractorISD_EENS_11DefaultHashIS7_EENS_7HashMapIS7_SC_SH_NS_10HashTraitsIS7_EENSJ_ISC_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE0ESB_E18KeyValuePairTraitsESK_SB_E6expandEPSD_
- __ZN3WTF9HashTableIPN3JSC6JSCellES3_NS_17IdentityExtractorENS_11DefaultHashIS3_EENS_10HashTraitsIS3_EES8_NS_10FastMallocEE6removeEPS3_
- __ZN3WTF9toCStringIJN3JSC4Wasm3RTTEEEENS_7CStringEDpRKT_
- __ZN9Inspector15RemoteInspector16pushListingsSoonEv
- __ZNK3WTF47ThreadSafeRefCountedAndCanMakeThreadSafeWeakPtrINS_6ThreadELNS_17DestructionThreadE0EE3refEv
- __ZNK3WTF8LivenessIN3JSC2B33Air25UnifiedTmpLivenessAdapterEE8IteratordeEv
- __ZNK3WTF9HashTableINSt3__14pairIPN3JSC8JSObjectEiEES6_NS_17IdentityExtractorENS_11DefaultHashIS6_EENS_10HashTraitsIS6_EESB_NS_10FastMallocEE8containsINS_22IdentityHashTranslatorISB_S9_EELNS_17ShouldValidateKeyE0ES6_EEbRKT1_
- __ZNK9Inspector15RemoteInspector16listingForTargetERKNS_24RemoteControllableTargetE
- __ZNKSt3__114default_deleteIN3WTF19EmbeddedFixedVectorIN3JSC4Wasm11CalleeGroup16OptimizedCalleesENS1_10FastMallocEEEEclB9sqn220106EPS8_
- __ZNSt3__111__sift_downB9sqn220106INS_17_ClassicAlgPolicyELb0ERZN3JSC11MarkedSpace26prepareForConservativeScanEvE3$_0PPNS2_17PreciseAllocationEEEvT2_OT1_NS_15iterator_traitsIS9_E15difference_typeESE_
- __ZTVN3WTF6Detail15CallableWrapperIZN3JSC22JSFinalizationRegistry23finalizeUnconditionallyERNS2_2VMENS2_15CollectionScopeEE3$_2vJRNS2_17DeferredWorkTimer6TicketEEEE
- __ZZN3JSC2B33Air17eliminateDeadCodeERNS1_4CodeEENK3$_5clERNS1_4InstE
- _pas_physical_page_sharing_pool_take_for_page_config
- _pas_thread_local_cache_layout_node_prepare_to_decommit
CStrings:
+ " max: "
+ "Branch target would discard too many stack values: "
+ "Expected an exported WebAssembly function"
+ "Exported function has no callee group yet"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21665:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21671:42)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21702:49), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21705:46)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21725:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21729:42)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21754:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21758:42)]"
+ "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21783:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21787:42)]"
+ "TriState JSC::Wasm::CalleeGroup::calleeIsReferenced(const AbstractLocker &, Wasm::Callee *) const"
+ "auto JSC::FTL::(anonymous namespace)::LowerDFGToB3::compileCallOrConstructVarargsSpread()::(anonymous class)::operator()(auto, Node *) const [self:auto = std::reference_wrapper<const WTF::RecursableLambda<(lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:14335:70)>>]"
+ "auto JSC::FTL::(anonymous namespace)::LowerDFGToB3::compileForwardVarargsWithSpread()::(anonymous class)::operator()(auto, Node *, LValue) const [self:auto = std::reference_wrapper<const WTF::RecursableLambda<(lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:15377:47)>>]"
+ "void JSC::DFG::clobberize(Graph &, Node *, const ReadFunctor &, const WriteFunctor &, const DefFunctor &, const ClobberTopFunctor &) [ReadFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/dfg/DFGStoreBarrierInsertionPhase.cpp:522:33), WriteFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/dfg/DFGStoreBarrierInsertionPhase.cpp:537:34), DefFunctor = JSC::DFG::NoOpClobberize, ClobberTopFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/dfg/DFGClobberize.h:45:47)]"
+ "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13753:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13756:13)]"
+ "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13767:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13770:13)]"
+ "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13781:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13784:13)]"
+ "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13795:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13798:13)]"
+ "wasmCalleeIDs"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21659:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21665:42)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21696:49), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21699:46)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21719:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21723:42)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21748:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21752:42)]"
- "LValue JSC::FTL::(anonymous namespace)::LowerDFGToB3::emitCodeBasedOnEndiannessBranch(LValue, const F1 &, const F2 &) [F1 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21777:45), F2 = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:21781:42)]"
- "ToType WTF::safeCast(FromType) [ToType = unsigned short, FromType = WTF::Checked<unsigned int>]"
- "auto JSC::FTL::(anonymous namespace)::LowerDFGToB3::compileCallOrConstructVarargsSpread()::(anonymous class)::operator()(auto, Node *) const [self:auto = std::reference_wrapper<const WTF::RecursableLambda<(lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:14329:70)>>]"
- "auto JSC::FTL::(anonymous namespace)::LowerDFGToB3::compileForwardVarargsWithSpread()::(anonymous class)::operator()(auto, Node *, LValue) const [self:auto = std::reference_wrapper<const WTF::RecursableLambda<(lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:15371:47)>>]"
- "void JSC::DFG::clobberize(Graph &, Node *, const ReadFunctor &, const WriteFunctor &, const DefFunctor &, const ClobberTopFunctor &) [ReadFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/dfg/DFGStoreBarrierInsertionPhase.cpp:514:33), WriteFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/dfg/DFGStoreBarrierInsertionPhase.cpp:529:34), DefFunctor = JSC::DFG::NoOpClobberize, ClobberTopFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/dfg/DFGClobberize.h:45:47)]"
- "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13747:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13750:13)]"
- "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13761:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13764:13)]"
- "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13775:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13778:13)]"
- "void JSC::FTL::(anonymous namespace)::LowerDFGToB3::compare(const IntFunctor &, const DoubleFunctor &, C_JITOperation_TT, C_JITOperation_B_GJssJss, S_JITOperation_GJJ) [IntFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13789:13), DoubleFunctor = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/JavaScriptCore/Source/JavaScriptCore/ftl/FTLLowerDFGToB3.cpp:13792:13)]"
```
