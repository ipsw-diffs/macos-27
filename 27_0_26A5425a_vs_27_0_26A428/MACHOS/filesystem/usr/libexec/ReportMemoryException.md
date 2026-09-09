## ReportMemoryException

> `/usr/libexec/ReportMemoryException`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 365.0.0.0.0
-  __TEXT.__text: 0x99a8
+  __TEXT.__text: 0x9844
   __TEXT.__auth_stubs: 0x620
   __TEXT.__objc_stubs: 0xf60
   __TEXT.__objc_methlist: 0x2c

   __TEXT.__oslogstring: 0x1d6c
   __TEXT.__gcc_except_tab: 0x28
   __TEXT.__objc_methname: 0xab7
-  __TEXT.__unwind_info: 0x198
+  __TEXT.__unwind_info: 0x1e0
   __DATA_CONST.__const: 0x478
   __DATA_CONST.__cfstring: 0x11c0
   __DATA_CONST.__objc_classlist: 0x10
Functions:
~ ___220+[RMETelemetry emitTelemetryForExecName:bundleID:exceptionType:footprint:footprintPeak:jetsamLimit:memgraphAttempted:memgraphSkippedReason:memgraphSucceeded:memgraphFailedReason:diagFilePath:isMSLEnabled:isGcoreCapture:]_block_invoke : 1092 -> 1080
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ __isFileQuotaAvailable : 3204 -> 3192
~ ___handleAnalyzeRequestAsync_block_invoke : 72 -> 60
~ ___copy_helper_block_e8_32s40s48s56b : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56s : 76 -> 64
~ ___handleRequestMemgraphWriteToFileAsync_block_invoke : 72 -> 60
~ ___copy_helper_block_e8_32s40s48s56s64b : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___emitSignpostWithExceptionInfo_block_invoke : 72 -> 60
~ ___copy_helper_block_e8_32s40s48b56r : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ _saveLogFile : 2256 -> 2244
~ _createFilePathTemplate : 880 -> 868
~ ___gregorianCalendar_block_invoke : 80 -> 68
~ ___copy_helper_block_e8_32s40w48w : 80 -> 68
~ ___destroy_helper_block_e8_32s40w48w : 68 -> 56
~ ___liteAnalysisMemgraphOnly_block_invoke : 68 -> 56
~ ___copy_helper_block_e8_32s40s48s56b64r : 104 -> 92
~ ___destroy_helper_block_e8_32s40s48s56s64r : 88 -> 76
~ ___copy_helper_block_e8_32s40r48w56w : 96 -> 84
~ ___destroy_helper_block_e8_32s40r48w56w : 80 -> 68
~ _RMEGetCriticalProcesses : 92 -> 80
~ _RMEGetPrefs : 348 -> 336
~ _RMEGetDefaultCriticalProcesses : 60 -> 48
~ _RMEGetDefaultLargeExemptedProcesses : 100 -> 88
~ _RMEPopulateDefaultPrefs : 1740 -> 1800
~ _RMEGetPrefsWithProfileDicts : 148 -> 136
~ ___RMEIsAutoSubmitEnabled_block_invoke : 56 -> 60
~ _RMEGetMemgraphLimitForExecName : 1332 -> 1324
~ _RMEGetLiteLimitForExecName : 192 -> 188
~ _RMEExtractExecNameForFilename : 312 -> 300
~ -[RMELogPath .cxx_destruct] : 68 -> 56
~ _RMEGetTimeOrderedLogPaths : 772 -> 760
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ ___handleRequest_block_invoke : 236 -> 224
```
