## libRPAC.dylib

> `/usr/lib/libRPAC.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__AUTH_CONST.__interpose`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 106.0.0.0.0
-  __TEXT.__text: 0x8e848
+  __TEXT.__text: 0x8e650
   __TEXT.__auth_stubs: 0x800
   __TEXT.__objc_stubs: 0x1a0
   __TEXT.__init_offsets: 0x4

   __TEXT.__gcc_except_tab: 0xbc
   __TEXT.__objc_methname: 0x13b
   __TEXT.__oslogstring: 0x1d
-  __TEXT.__unwind_info: 0x2f0
+  __TEXT.__unwind_info: 0x3e0
   __DATA_CONST.__const: 0x3f8
   __DATA_CONST.__cfstring: 0x260
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ __replacement_NSData_initWithContentsOfFile : 188 -> 176
~ __replacement_NSData_initWithContentsOfFile_options_error : 212 -> 200
~ __replacement_NSData_initWithContentsOfURL : 240 -> 228
~ __replacement_NSData_initWithContentsOfURL_options_error : 264 -> 252
~ __replacement_NSData_dataWithContentsOfFile : 188 -> 176
~ __replacement_NSData_dataWithContentsOfFile_options_error : 212 -> 200
~ __replacement_AVCaptureSession_startRunning : 136 -> 124
~ __replacement_ISIcon_prepareImageForDescriptor : 272 -> 260
~ __replacement_ISIcon_prepareImagesForDescriptors : 268 -> 256
~ __replacement_ISIcon_prepareImagesForImageDescriptors : 268 -> 256
~ __replacement_NSURLConnection_sendSynchronousRequest_returningResponse_error : 200 -> 188
~ _initializeSwizzlers : 1052 -> 1040
~ _interposed_CGImageSourceCreateThumbnailAtIndex : 128 -> 116
~ _interposed_CGImageSourceCreateImageAtIndex : 128 -> 116
~ _interposed_CGImageDestinationFinalize : 104 -> 92
~ ___library_initializer : 2320 -> 2308
~ _____library_initializer_block_invoke : 72 -> 56
~ _lockLockInDispatchLockMap : 16 -> 20
~ _unlockLockInDispatchLockMap : 16 -> 20
~ _interposed_dispatch_semaphore_wait : 328 -> 316
~ _interposed_dispatch_semaphore_signal : 184 -> 172
~ _interposed_dispatch_group_leave : 240 -> 228
~ _interposed_dispatch_group_wait : 364 -> 352
~ _printStatistics : 348 -> 336
~ _prepareInstanceMethodSwizzler : 216 -> 192
~ _prepareClassMethodSwizzler : 216 -> 192
~ __ZL33preInitializationDuplicationCheckl20PerformanceIssueType : 248 -> 236
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIl13hashed_addr_tEENS_22__unordered_map_hasherIlNS_4pairIKlS2_EENS_4hashIlEENS_8equal_toIlEEEENS_21__unordered_map_equalIlS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9nqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_ : 536 -> 532
~ __ZNSt3__112__hash_tableINS_17__hash_value_typeIl13hashed_addr_tEENS_22__unordered_map_hasherIlNS_4pairIKlS2_EENS_4hashIlEENS_8equal_toIlEEEENS_21__unordered_map_equalIlS7_SB_S9_EENS_9allocatorIS7_EEE8__rehashILb1EEEvm : 228 -> 212
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ ___skipSwizzle_block_invoke : 124 -> 112
~ _custom_xpc_connection_send_message_with_reply_sync : 248 -> 236
~ _main_thread_hang_inducer : 264 -> 252
~ _lockLockInNSCondtionLockMap : 16 -> 20
~ _unlockLockInNSConditionLockMap : 16 -> 20
~ __replacement_NSCondition_wait : 388 -> 376
~ __replacement_NSCondition_signal : 240 -> 228
~ __replacement_NSCondition_broadcast : 240 -> 228
~ ____Z22initializePrimitiveMapv_block_invoke : 184 -> 172
~ _qosWaiterSignallerInvariantCheck : 2512 -> 2500
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIl10qos_info_tEENS_22__unordered_map_hasherIlNS_4pairIKlS2_EENS_4hashIlEENS_8equal_toIlEEEENS_21__unordered_map_equalIlS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9nqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_ : 540 -> 536
~ ___culledOsLogFault_block_invoke : 280 -> 268
~ ___copy_helper_block_e8_32r40r : 80 -> 68
~ ___destroy_helper_block_e8_32r40r : 68 -> 56
~ _copyMainBundleDirectory : 52 -> 40
~ ___suppressionCheck_block_invoke : 740 -> 728
```
