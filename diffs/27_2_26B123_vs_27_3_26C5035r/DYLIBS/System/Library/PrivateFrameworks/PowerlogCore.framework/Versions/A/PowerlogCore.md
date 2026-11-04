## PowerlogCore

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/Versions/A/PowerlogCore`

```diff

-3486.41.1.0.0
-  __TEXT.__text: 0xd3170
-  __TEXT.__objc_methlist: 0x8b50
-  __TEXT.__const: 0x668
-  __TEXT.__cstring: 0x40913
-  __TEXT.__oslogstring: 0x74ab
+3486.60.36.0.0
+  __TEXT.__text: 0xd39a0
+  __TEXT.__objc_methlist: 0x8b70
+  __TEXT.__const: 0x678
+  __TEXT.__cstring: 0x40a5b
+  __TEXT.__oslogstring: 0x758e
   __TEXT.__gcc_except_tab: 0x2160
-  __TEXT.__unwind_info: 0x3c90
+  __TEXT.__unwind_info: 0x3ca8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5218
+  __DATA_CONST.__objc_selrefs: 0x5228
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x2b0
-  __DATA_CONST.__objc_arraydata: 0x44648
+  __DATA_CONST.__objc_arraydata: 0x44788
   __DATA_CONST.__got: 0x618
-  __AUTH_CONST.__const: 0x37a0
-  __AUTH_CONST.__cfstring: 0x691c0
+  __AUTH_CONST.__const: 0x37d0
+  __AUTH_CONST.__cfstring: 0x69420
   __AUTH_CONST.__objc_const: 0x9cc8
   __AUTH_CONST.__objc_intobj: 0x4c20
   __AUTH_CONST.__objc_doubleobj: 0x14d0
   __AUTH_CONST.__objc_arrayobj: 0x1020
-  __AUTH_CONST.__objc_dictobj: 0xf500
+  __AUTH_CONST.__objc_dictobj: 0xf578
   __AUTH_CONST.__auth_got: 0xb20
   __AUTH.__objc_data: 0x460
   __DATA.__objc_ivar: 0x708

   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libsystemstats.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 4531
-  Symbols:   8478
-  CStrings:  14605
+  Functions: 4539
+  Symbols:   8486
+  CStrings:  14628
 
Symbols:
+ -[PLCoreOperator enumerateOperatorsWithBlock:]
+ -[PLCoreOperator teardownOperatorDependancies]
+ -[PLOperator teardownOperatorDependancies]
+ -[PLSubmissionFilePLL trialsTaskingTrimCutoffForEndDate:]
+ GCC_except_table112
+ GCC_except_table46
+ GCC_except_table60
+ GCC_except_table71
+ ___46-[PLCoreOperator teardownOperatorDependancies]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e20_v16?0"PLOperator"8l
+ _objc_msgSend$enumerateOperatorsWithBlock:
+ _objc_msgSend$teardownOperatorDependancies
+ _objc_msgSend$trialsTaskingTrimCutoffForEndDate:
- -[PLCoreOperator initOperatorDependanciesWithBlock:]
- GCC_except_table111
- GCC_except_table58
- GCC_except_table70
- _objc_msgSend$initOperatorDependanciesWithBlock:
CStrings:
+ "ChunkDurationMins"
+ "Chunks"
+ "CumulativeDayMins"
+ "Failed to convert trials tasking trim window to monotonic time"
+ "FedCapabilityData"
+ "FedExtSrcCapProductID"
+ "FedExtSrcCapVendorID"
+ "FedMaxCurrent"
+ "FedMaxPower"
+ "FedMaxVoltage"
+ "FedWPDebugData"
+ "FedWPPolicyData"
+ "IntervalStartDate"
+ "LiveRewindEnabled"
+ "MindPalace"
+ "MindPalaceEnabled"
+ "ProcessingBudgetHrs"
+ "Stop Powerlog Services"
+ "TotalConversationMinutes"
+ "TotalConversationOnBatteryMinutes"
+ "WasRetry"
+ "teardownOperatorDependancies: nil workQueue for %@, skipping"
+ "teardownOperatorDependancies: timed out waiting for %lu operator(s): %{public}@"
```
