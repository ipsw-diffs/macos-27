## TSFundamentals

> `/System/Applications/Freeform.app/Contents/Frameworks/TSFundamentals.framework/Versions/A/TSFundamentals`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 656.1.2.0.0
-  __TEXT.__text: 0x4cac
+  __TEXT.__text: 0x4aa8
   __TEXT.__auth_stubs: 0x470
   __TEXT.__objc_stubs: 0x9e0
   __TEXT.__objc_methlist: 0x430

   __TEXT.__objc_classname: 0xb3
   __TEXT.__objc_methname: 0xb1b
   __TEXT.__objc_methtype: 0x210
-  __TEXT.__unwind_info: 0x280
+  __TEXT.__unwind_info: 0x310
   __TEXT.__eh_frame: 0x48
   __DATA_CONST.__const: 0x4e0
   __DATA_CONST.__cfstring: 0x4a0
Functions:
~ +[TSUAssertionHandler performBlockIgnoringAssertions:] : 44 -> 32
~ +[TSUAssertionHandler performBlockIgnoringFatalAssertions:] : 44 -> 32
~ +[TSUAssertionHandler performBlockIgnoringQAFatalAssertions:] : 72 -> 60
~ ___copy_helper_block_e8_32o40r : 80 -> 68
~ ___destroy_helper_block_e8_32o40r : 68 -> 56
~ +[TSUAssertionHandler packedBacktraceString] : 68 -> 56
~ _OUTLINED_FUNCTION_0 : 12 -> 20
~ +[TSUBacktrace backtrace] : 48 -> 36
~ +[TSUBacktrace new] : 44 -> 32
~ +[TSUBacktrace caller] : 44 -> 32
~ +[TSUBacktrace callee] : 44 -> 32
~ _OUTLINED_FUNCTION_2 : 32 -> 20
~ +[NSString(TSULogAdditions) tsu_redactedStringWithFormat:arguments:] : 112 -> 100
~ +[NSString(TSULogAdditions) tsu_unRedactedStringWithFormat:arguments:] : 112 -> 100
~ _TSFFrameworkBundle : 68 -> 56
~ ___TSFFrameworkBundle_block_invoke : 96 -> 84
~ _TSULogCreateCategory : 52 -> 40
~ ___TSULogBacktrace_block_invoke : 76 -> 64
~ ___TSULogEnsureCreated_block_invoke : 152 -> 140
~ _TSULogGetName : 132 -> 120
~ _TSULogGetNameDictionary : 68 -> 56
~ ___TSULogGetNameDictionary_block_invoke : 76 -> 64
~ +[TSULogHelper sharedInstance] : 68 -> 56
~ ___30+[TSULogHelper sharedInstance]_block_invoke : 64 -> 52
~ ___57-[TSULogHelper incrementThrottleCountAndCheckThottleMax:]_block_invoke : 68 -> 56
~ __57-[TSULogHelper incrementThrottleCountAndCheckThottleMax:]_block_invoke.14 : 68 -> 56
~ -[TSULogHelper .cxx_destruct] : 68 -> 56
~ -[TSUUUIDLogContext .cxx_destruct] : 68 -> 56
~ _TSULogSinkv : 168 -> 156
~ _TSULogSinkSetBlock : 228 -> 216
~ _TSULogSinkSetBlocks : 92 -> 80
~ +[TSUOSLogSink sharedInstance] : 68 -> 56
~ ___30+[TSUOSLogSink sharedInstance]_block_invoke : 64 -> 52
~ -[TSUOSLogSink logSinkBlock] : 48 -> 36
~ +[TSUStdioLogSink sharedInstance] : 68 -> 56
~ ___33+[TSUStdioLogSink sharedInstance]_block_invoke : 64 -> 52
~ -[TSUStdioLogSink logSinkBlockWithFilePointer:] : 156 -> 144
~ ___47-[TSUStdioLogSink logSinkBlockWithFilePointer:]_block_invoke_2 : 384 -> 372
~ ___copy_helper_block_e8_32s40s48s56s : 76 -> 64
~ ___destroy_helper_block_e8_32s40s48s56s : 76 -> 64
~ -[TSUStdioLogSink .cxx_destruct] : 68 -> 56
~ sub_4ab0 -> sub_48d8 : 1016 -> 1012
~ ___swift_project_boxed_opaque_existential_1 : 68 -> 48
~ sub_54f4 -> sub_5304 : 104 -> 92
~ TSUDynamicBaseAddress.cold.2 : 64 -> 56
~ __66+[TSUAssertionHandler p_performBlockIgnoringAssertions:onlyFatal:]_block_invoke.cold.2 : 64 -> 56
~ +[TSUAssertionHandler logFullBacktrace].cold.2 : 100 -> 104
~ +[TSUAssertionHandler _logBacktraceWithCallStackSymbols:].cold.2 : 108 -> 112
```
