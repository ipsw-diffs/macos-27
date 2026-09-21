## MetalPerformanceShadersGraph

> `/System/Library/Frameworks/MetalPerformanceShadersGraph.framework/Versions/A/MetalPerformanceShadersGraph`

```diff

-7.1.3.0.0
-  __TEXT.__text: 0x221a698
+7.1.4.0.0
+  __TEXT.__text: 0x2218728
   __TEXT.__mpsgraph_init_: 0x40
   __TEXT.__objc_methlist: 0x8624
-  __TEXT.__const: 0x6d4f8
-  __TEXT.__cstring: 0xf284a
+  __TEXT.__const: 0x6dcf8
+  __TEXT.__cstring: 0xf24e8
   __TEXT.__swift5_typeref: 0xb72
   __TEXT.__swift5_capture: 0x340
   __TEXT.__oslogstring: 0x378f

   __TEXT.__swift_as_entry: 0x14
   __TEXT.__swift_as_ret: 0x4
   __TEXT.__swift_as_cont: 0x10
-  __TEXT.__gcc_except_tab: 0x1381d8
+  __TEXT.__gcc_except_tab: 0x138168
   __TEXT.__ustring: 0x19c
-  __TEXT.__unwind_info: 0x776d8
+  __TEXT.__unwind_info: 0x776b0
   __TEXT.__eh_frame: 0x3d84
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 105245
-  Symbols:   148355
-  CStrings:  21158
+  Functions: 105237
+  Symbols:   148349
+  CStrings:  21138
 
Symbols:
+ _ZN4mlir9OpBuilder6createINS_6tensor5DimOpEJNS_13BlockArgumentERNS_5ValueEEEET_NS_8LocationEDpOT0_
+ __ZN12_GLOBAL__N_122comparisonPredicateForE12Z3_decl_kind
+ __ZN12_GLOBAL__N_124chainOperandsLeftToRightIN4mlir5arith5OrIOpEEENS1_5ValueEN4llvm8ArrayRefIS4_EERNS1_10IRRewriterENS1_8LocationE
+ __ZN12_GLOBAL__N_124chainOperandsLeftToRightIN4mlir5arith6AddIOpEEENS1_5ValueEN4llvm8ArrayRefIS4_EERNS1_10IRRewriterENS1_8LocationE
+ __ZN12_GLOBAL__N_124chainOperandsLeftToRightIN4mlir5arith6AndIOpEEENS1_5ValueEN4llvm8ArrayRefIS4_EERNS1_10IRRewriterENS1_8LocationE
+ __ZN12_GLOBAL__N_124chainOperandsLeftToRightIN4mlir5arith6MulIOpEEENS1_5ValueEN4llvm8ArrayRefIS4_EERNS1_10IRRewriterENS1_8LocationE
+ __ZN4mlir3mps12_GLOBAL__N_116kFloat8E5M2ToF32E
+ __ZN4mlir3mps12_GLOBAL__N_118kFloat8E4M3FNToF32E
+ __ZN4mlir4mpsx17Z3ToMLIRGenerator16emitValueForNodeERKN2z34exprERNS_10IRRewriterENS_8LocationE
+ __ZN4mlir4mpsx17Z3ToMLIRGenerator24emitValueForNodeUncachedERKN2z34exprERNS_10IRRewriterENS_8LocationE
+ __ZN4mlir4mpsx17Z3ToMLIRGenerator25resetForNextShapeFunctionEv
+ __ZN4mlir4mpsx17Z3ToMLIRGenerator25setDimCoordinatesBySymbolERKNSt3__13mapINS2_12basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEENS2_4pairIjjEENS2_4lessIS9_EENS7_INSA_IKS9_SB_EEEEEE
+ __ZN4mlir4mpsx17Z3ToMLIRGenerator34emitSimplifiedMathForReturnOperandERKN2z34exprENS_4func6FuncOpEjRNS_10IRRewriterE
+ __ZN4mlir6detail24FunctionOpInterfaceTraitINS_4func6FuncOpEE15getNumArgumentsEv
+ __ZN4mlir9OpBuilder6createINS_6tensor5DimOpEJNS_13BlockArgumentERNS_5ValueEEEET_NS_8LocationEDpOT0_
+ __ZNK2z33ast4kindEv
+ __ZNK2z34expr17get_numeral_int64Ev
+ __ZNK2z34expr7is_trueEv
- _Z3_ast_to_string
- __Z20log_Z3_ast_to_stringP11_Z3_contextP7_Z3_ast
- __ZN4mlir4mpsx17Z3ToMLIRGenerator11clearCachesEv
- __ZN4mlir4mpsx17Z3ToMLIRGenerator11generateIteERKN2z34exprERNS_10IRRewriterENS_8LocationE
- __ZN4mlir4mpsx17Z3ToMLIRGenerator14generateModuloERKN2z34exprERNS_10IRRewriterENS_8LocationE
- __ZN4mlir4mpsx17Z3ToMLIRGenerator15resolveVariableERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEERNS_10IRRewriterENS_8LocationE
- __ZN4mlir4mpsx17Z3ToMLIRGenerator16generateAdditionERKN2z34exprERNS_10IRRewriterENS_8LocationE
- __ZN4mlir4mpsx17Z3ToMLIRGenerator16generateDivisionERKN2z34exprERNS_10IRRewriterENS_8LocationE
- __ZN4mlir4mpsx17Z3ToMLIRGenerator17generateConditionERKN2z34exprERNS_10IRRewriterENS_8LocationE
- __ZN4mlir4mpsx17Z3ToMLIRGenerator18generateFromZ3ExprERKN2z34exprERNS_10IRRewriterENS_8LocationE
- __ZN4mlir4mpsx17Z3ToMLIRGenerator19generateSubtractionERKN2z34exprERNS_10IRRewriterENS_8LocationE
- __ZN4mlir4mpsx17Z3ToMLIRGenerator20createFundamentalDimEjjRNS_10IRRewriterENS_8LocationE
- __ZN4mlir4mpsx17Z3ToMLIRGenerator22generateMultiplicationERKN2z34exprERNS_10IRRewriterENS_8LocationE
- __ZN4mlir4mpsx17Z3ToMLIRGenerator24setSymbolToArgDimMappingERKNSt3__13mapINS2_12basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEENS2_4pairIjjEENS2_4lessIS9_EENS7_INSA_IKS9_SB_EEEEEE
- __ZN4mlir4mpsx17Z3ToMLIRGenerator27generateShapeFunctionFromZ3ERKN2z34exprENS_4func6FuncOpEjRNS_10IRRewriterE
- __ZN4mlir4mpsx17Z3ToMLIRGeneratorD2Ev
- __ZN4mlir4mpsx31ShapeFunctionResultDeduplicator23ShapeEquivalenceTracker34analyzeExpressionBasedEquivalencesENS_12OperandRangeE
- __ZN4mlir4mpsx31ShapeFunctionResultDeduplicator31runExpressionBasedDeduplicationEPNS_9OperationEPNS_11MLIRContextE
- __ZNK2z33ast9to_stringEv
- __ZNK2z34expr8num_argsEv
- __ZNK4mlir4mpsx31ShapeFunctionResultDeduplicator23ShapeEquivalenceTracker21getSimplifiedEquationENS_5ValueE
- __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEN4mlir5ValueEEENS_19__map_value_compareIS7_NS_4pairIKS7_S9_EENS_4lessIS7_EEEENS5_ISE_EEE14__tree_deleterclB9nqn220106EPNS_11__tree_nodeISA_PvEE
- __ZZN4mlir4mpsx31ShapeFunctionResultDeduplicator23ShapeEquivalenceTracker34analyzeExpressionBasedEquivalencesENS_12OperandRangeEENK3$_0clENS_5ValueE
- __ZZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEN4mlir5ValueEEENS_19__map_value_compareIS7_NS_4pairIKS7_S9_EENS_4lessIS7_EEEENS5_ISE_EEE16__emplace_uniqueB9nqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRSD_EEENSO_IJEEEEEENSC_INS_15__tree_iteratorISA_PNS_11__tree_nodeISA_PvEElEEbEEDpOT_ENKUlSP_SN_OSQ_OSR_E_clESP_SN_S12_S13_
CStrings:
+ "7.1.4"
+ "Z3 operation has unexpected arity\n"
- "Addition requires at least 2 arguments\n"
- "Comparison requires 2 arguments\n"
- "Division requires exactly 2 arguments\n"
- "Failed to generate branches for ite\n"
- "Failed to generate first operand for addition\n"
- "Failed to generate first operand for multiplication\n"
- "Failed to generate operand for addition\n"
- "Failed to generate operand for multiplication\n"
- "Failed to generate operands for division\n"
- "Failed to generate operands for modulo\n"
- "Failed to generate operands for subtraction\n"
- "ITE condition must be an application expression\n"
- "ITE requires exactly 3 arguments (condition, then, else)\n"
- "Identical Z3-simplified equation: "
- "Modulo requires exactly 2 arguments\n"
- "Multiplication requires at least 2 arguments\n"
- "No current shape function set\n"
- "Refusing to generate modulo by zero\n"
- "Subtraction requires exactly 2 arguments\n"
- "UMINUS requires exactly 1 argument\n"
- "Unsupported ITE condition kind\n"
- "Z3 Expression-based deduplication failed\n"
```
