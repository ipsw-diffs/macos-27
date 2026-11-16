## MTLCompiler

> `/System/Library/PrivateFrameworks/MTLCompiler.framework/Versions/32024/MTLCompiler`

```diff

-384.5.0.0.0
-  __TEXT.__text: 0xb7558
-  __TEXT.__gcc_except_tab: 0xa6b4
-  __TEXT.__const: 0x1288
-  __TEXT.__cstring: 0x990a
-  __TEXT.__oslogstring: 0x535
-  __TEXT.__unwind_info: 0x3358
+384.7.0.0.0
+  __TEXT.__text: 0xb78f0
+  __TEXT.__gcc_except_tab: 0xa6cc
+  __TEXT.__const: 0x1298
+  __TEXT.__cstring: 0x99eb
+  __TEXT.__oslogstring: 0x58b
+  __TEXT.__unwind_info: 0x3360
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_methname: 0x0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2159
+  Functions: 2161
   Symbols:   3486
-  CStrings:  1659
+  CStrings:  1666
 
Symbols:
+ GCC_except_table329
+ GCC_except_table335
+ GCC_except_table339
+ GCC_except_table344
+ GCC_except_table354
+ GCC_except_table357
+ GCC_except_table360
+ GCC_except_table362
+ GCC_except_table370
+ GCC_except_table376
+ GCC_except_table378
+ GCC_except_table381
+ GCC_except_table395
+ GCC_except_table406
+ GCC_except_table430
+ GCC_except_table434
+ GCC_except_table443
+ GCC_except_table449
+ GCC_except_table461
+ GCC_except_table470
+ GCC_except_table477
+ GCC_except_table491
+ GCC_except_table493
+ GCC_except_table506
+ GCC_except_table508
+ GCC_except_table514
+ GCC_except_table531
+ GCC_except_table534
+ GCC_except_table537
+ GCC_except_table540
+ __ZNSt3__16vectorIPcNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJS1_EEEPS1_DpOT_
- GCC_except_table328
- GCC_except_table334
- GCC_except_table338
- GCC_except_table343
- GCC_except_table352
- GCC_except_table355
- GCC_except_table358
- GCC_except_table361
- GCC_except_table368
- GCC_except_table375
- GCC_except_table377
- GCC_except_table380
- GCC_except_table393
- GCC_except_table404
- GCC_except_table429
- GCC_except_table433
- GCC_except_table439
- GCC_except_table447
- GCC_except_table460
- GCC_except_table467
- GCC_except_table476
- GCC_except_table489
- GCC_except_table492
- GCC_except_table504
- GCC_except_table507
- GCC_except_table512
- GCC_except_table516
- GCC_except_table527
- GCC_except_table533
- GCC_except_table536
- GCC_except_table538
Functions:
~ __ZL22parseFunctionConstantsRN4llvm11LLVMContextEPKcmPj : 336 -> 368
~ __ZN17MTLCompilerObject20storeToBinaryArchiveEP29MTLBuildBinariesRequestHeadermRK20ReadModuleParametersRK24BackendCompilationOutput15MTLFunctionTypeR21FrameworkPassesOutputRKP20MTLOpaqueGPUArchiverPPc : 1868 -> 1976
~ __ZN17MTLCompilerObject13generateMachOEPKvmU13block_pointerFvjS1_mPKcE : 5104 -> 5764
+ __ZL22parseFunctionConstantsRN4llvm11LLVMContextEPKcmPj.cold.1
+ __ZN17MTLCompilerObject13generateMachOEPKvmU13block_pointerFvjS1_mPKcE.cold.1
CStrings:
+ "Failed to allocate MachO binary request entries"
+ "Failed to allocate function constants"
+ "Invalid pipeline archiver unit id"
+ "Invalid visible function request count"
+ "MachO entry %llu reflection block out of bounds"
+ "Unknown linked bitcode hash in MachO binary request"
+ "Visible function hashes do not match the tools list"
```
