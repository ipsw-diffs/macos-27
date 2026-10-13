## LinkServices

> `/System/Library/PrivateFrameworks/LinkServices.framework/Versions/A/LinkServices`

```diff

-301.1.15.0.0
-  __TEXT.__text: 0x14ce20
-  __TEXT.__objc_methlist: 0xae90
+301.1.16.0.0
+  __TEXT.__text: 0x14d754
+  __TEXT.__objc_methlist: 0xaed0
   __TEXT.__dlopen_cstrs: 0x5ba
-  __TEXT.__const: 0x77d8
-  __TEXT.__cstring: 0xc6db
+  __TEXT.__const: 0x77f8
   __TEXT.__constg_swiftt: 0x1afc
-  __TEXT.__swift5_typeref: 0x2e94
+  __TEXT.__swift5_typeref: 0x2ec8
   __TEXT.__swift5_builtin: 0x258
   __TEXT.__swift5_reflstr: 0xe3c
   __TEXT.__swift5_fieldmd: 0x11a8
   __TEXT.__swift5_assocty: 0x2b8
-  __TEXT.__swift5_capture: 0x12a0
-  __TEXT.__oslogstring: 0x967d
+  __TEXT.__cstring: 0xc7ff
   __TEXT.__swift5_proto: 0x284
   __TEXT.__swift5_types: 0x1a0
+  __TEXT.__swift5_protos: 0x44
+  __TEXT.__swift5_capture: 0x12a0
+  __TEXT.__oslogstring: 0x97a2
   __TEXT.__swift_as_entry: 0x114
   __TEXT.__swift_as_ret: 0x130
   __TEXT.__swift_as_cont: 0x1c4
-  __TEXT.__swift5_protos: 0x44
   __TEXT.__swift5_mpenum: 0x68
-  __TEXT.__gcc_except_tab: 0x1da4
-  __TEXT.__unwind_info: 0x6998
+  __TEXT.__gcc_except_tab: 0x1dcc
+  __TEXT.__unwind_info: 0x69c0
   __TEXT.__eh_frame: 0x4b40
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xe38
+  __DATA_CONST.__const: 0xe40
   __DATA_CONST.__objc_classlist: 0x878
   __DATA_CONST.__objc_catlist: 0x138
   __DATA_CONST.__objc_protolist: 0x1c8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5208
+  __DATA_CONST.__objc_selrefs: 0x5230
   __DATA_CONST.__objc_protorefs: 0x100
   __DATA_CONST.__objc_superrefs: 0x5f8
   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__got: 0x1930
-  __AUTH_CONST.__const: 0x8188
-  __AUTH_CONST.__cfstring: 0x8d00
+  __AUTH_CONST.__const: 0x81b8
+  __AUTH_CONST.__cfstring: 0x8d60
   __AUTH_CONST.__objc_const: 0x16840
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_arrayobj: 0x18

   __AUTH.__objc_data: 0x3e18
   __AUTH.__data: 0x12b0
   __DATA.__objc_ivar: 0xad8
-  __DATA.__data: 0x2750
+  __DATA.__data: 0x2738
   __DATA.__bss: 0x47d8
   __DATA.__common: 0x78
   __DATA_DIRTY.__objc_data: 0x23a0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 8803
-  Symbols:   11367
-  CStrings:  2214
+  Functions: 8817
+  Symbols:   11389
+  CStrings:  2221
 
Symbols:
+ -[LNActionExecutor connectAndEnqueuePerformWithOptions:]
+ -[LNActionExecutor enqueuePerformReconnectingIfNeededWithConnectionInterface:action:connection:connectionOptions:]
+ -[LNActionExecutor evaluatePreConfirmationForAction:connection:connectionInterface:connectionOptions:]
+ -[LNActionExecutor prepareConnectionInterfaceOrComplete:connection:error:]
+ -[LNActionExecutor requestSideEffectConfirmationFromResult:connectionInterface:action:connection:connectionOptions:]
+ -[LNActionExecutor subscribeToProgressUpdates]
+ GCC_except_table1764
+ GCC_except_table1767
+ GCC_except_table1772
+ GCC_except_table1773
+ GCC_except_table1775
+ GCC_except_table1776
+ GCC_except_table1777
+ GCC_except_table1913
+ GCC_except_table1924
+ GCC_except_table1933
+ GCC_except_table1951
+ GCC_except_table1973
+ GCC_except_table1985
+ GCC_except_table2001
+ GCC_except_table2055
+ GCC_except_table2090
+ GCC_except_table2096
+ GCC_except_table2098
+ GCC_except_table2100
+ GCC_except_table2112
+ GCC_except_table2124
+ GCC_except_table2136
+ GCC_except_table2148
+ GCC_except_table2160
+ GCC_except_table2176
+ GCC_except_table2187
+ GCC_except_table2199
+ GCC_except_table2211
+ GCC_except_table2223
+ GCC_except_table2233
+ GCC_except_table2247
+ GCC_except_table2257
+ GCC_except_table2269
+ GCC_except_table2294
+ GCC_except_table2308
+ GCC_except_table2319
+ GCC_except_table2331
+ GCC_except_table2345
+ GCC_except_table2346
+ GCC_except_table2356
+ GCC_except_table2365
+ GCC_except_table2654
+ GCC_except_table3112
+ GCC_except_table3117
+ GCC_except_table3122
+ GCC_except_table3256
+ GCC_except_table3268
+ GCC_except_table3323
+ GCC_except_table3327
+ GCC_except_table3340
+ GCC_except_table3364
+ GCC_except_table3368
+ GCC_except_table3499
+ GCC_except_table3514
+ _LNInterfaceIdiomHomeAccessory
+ _LNTVDisplayAttentionStateIsAsleep
+ _LNTVDisplayIsAsleep
+ __102-[LNActionExecutor evaluatePreConfirmationForAction:connection:connectionInterface:connectionOptions:]_block_invoke
+ ___102-[LNActionExecutor evaluatePreConfirmationForAction:connection:connectionInterface:connectionOptions:]_block_invoke
+ ___116-[LNActionExecutor requestSideEffectConfirmationFromResult:connectionInterface:action:connection:connectionOptions:]_block_invoke
+ ___116-[LNActionExecutor requestSideEffectConfirmationFromResult:connectionInterface:action:connection:connectionOptions:]_block_invoke_2
+ ___46-[LNActionExecutor subscribeToProgressUpdates]_block_invoke
+ ___46-[LNActionExecutor subscribeToProgressUpdates]_block_invoke_2
+ ___56-[LNActionExecutor connectAndEnqueuePerformWithOptions:]_block_invoke
+ ___block_descriptor_59_e8_32s40s_e79_v40?0"LNConnection"8"LNAction"16"<LNConnectionHostInterface>"24"NSError"32l
+ ___block_descriptor_72_e8_32s40s48s56s64s_e40_v16?0"LNPreConfirmationResultWrapper"8l
+ ___block_descriptor_72_e8_32s40s48s56s64s_e50_v24?0"LNActionConfirmationResponse"8"NSError"16l
+ ___block_descriptor_80_e8_32s40s48s56s64s72s_e5_v8?0l
+ ___block_descriptor_89_e8_32s40s48s56s64s72s80s_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s64s72s80s
+ __swift_closure_destructor.27Tm
+ _objc_msgSend$connectAndEnqueuePerformWithOptions:
+ _objc_msgSend$enqueuePerformReconnectingIfNeededWithConnectionInterface:action:connection:connectionOptions:
+ _objc_msgSend$evaluatePreConfirmationForAction:connection:connectionInterface:connectionOptions:
+ _objc_msgSend$prepareConnectionInterfaceOrComplete:connection:error:
+ _objc_msgSend$requestSideEffectConfirmationFromResult:connectionInterface:action:connection:connectionOptions:
+ _objc_msgSend$subscribeToProgressUpdates
+ _symbolic So14LSBundleRecordCSg
+ _symbolic _____ySo14LSBundleRecordCSgG s23_ContiguousArrayStorageC
- -[LNActionExecutor requestSideEffectConfirmationFromResult:connectionInterface:action:connection:]
- GCC_except_table1761
- GCC_except_table1763
- GCC_except_table1765
- GCC_except_table1769
- GCC_except_table1770
- GCC_except_table1906
- GCC_except_table1917
- GCC_except_table1926
- GCC_except_table1944
- GCC_except_table1966
- GCC_except_table1978
- GCC_except_table1994
- GCC_except_table2048
- GCC_except_table2083
- GCC_except_table2089
- GCC_except_table2091
- GCC_except_table2093
- GCC_except_table2105
- GCC_except_table2117
- GCC_except_table2129
- GCC_except_table2141
- GCC_except_table2153
- GCC_except_table2169
- GCC_except_table2180
- GCC_except_table2192
- GCC_except_table2204
- GCC_except_table2216
- GCC_except_table2226
- GCC_except_table2240
- GCC_except_table2250
- GCC_except_table2262
- GCC_except_table2287
- GCC_except_table2301
- GCC_except_table2312
- GCC_except_table2324
- GCC_except_table2338
- GCC_except_table2339
- GCC_except_table2349
- GCC_except_table2358
- GCC_except_table2647
- GCC_except_table3103
- GCC_except_table3108
- GCC_except_table3113
- GCC_except_table3247
- GCC_except_table3259
- GCC_except_table3309
- GCC_except_table3314
- GCC_except_table3331
- GCC_except_table3355
- GCC_except_table3359
- GCC_except_table3490
- GCC_except_table3505
- ___44-[LNActionExecutor performWithoutValidation]_block_invoke_2
- ___44-[LNActionExecutor performWithoutValidation]_block_invoke_3
- ___98-[LNActionExecutor requestSideEffectConfirmationFromResult:connectionInterface:action:connection:]_block_invoke
- ___98-[LNActionExecutor requestSideEffectConfirmationFromResult:connectionInterface:action:connection:]_block_invoke_2
- ___block_descriptor_64_e8_32s40s48s56s_e40_v16?0"LNPreConfirmationResultWrapper"8l
- ___block_descriptor_64_e8_32s40s48s56s_e50_v24?0"LNActionConfirmationResponse"8"NSError"16l
- ___block_descriptor_72_e8_32s40s48s56s64s_e5_v8?0l
- ___block_descriptor_81_e8_32s40s48s56s64s72s_e5_v8?0l
- __swift_closure_destructor.38Tm
- _objc_msgSend$requestSideEffectConfirmationFromResult:connectionInterface:action:connection:
CStrings:
+ "Connection dropped during pre-confirmation (state: %{public}@); reconnecting before performing"
+ "Connection resolved after executor teardown; not performing"
+ "Resolved localizedApplicationName `%{public}@` for extension `%{public}@`"
+ "Resolved the application name for extension `%{public}s`"
+ "connect"
+ "homeAccessory"
+ "state == LNActionExecutorStateClassifyingParameters || state == LNActionExecutorStateResolving || state == LNActionExecutorStatePerforming || state == LNActionExecutorStateCompleted || state == LNActionExecutorStateConnecting"
+ "state == LNActionExecutorStateWaitingForActionConfirmation || state == LNActionExecutorStatePerforming || state == LNActionExecutorStateCompleted || state == LNActionExecutorStateConnecting"
- "state == LNActionExecutorStateWaitingForActionConfirmation || state == LNActionExecutorStatePerforming || state == LNActionExecutorStateCompleted"
```
