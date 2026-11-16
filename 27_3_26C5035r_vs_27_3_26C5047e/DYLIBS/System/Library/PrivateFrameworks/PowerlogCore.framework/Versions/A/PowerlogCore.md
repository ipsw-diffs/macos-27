## PowerlogCore

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/Versions/A/PowerlogCore`

```diff

-3486.60.36.0.0
-  __TEXT.__text: 0xd39a0
-  __TEXT.__objc_methlist: 0x8b70
-  __TEXT.__const: 0x678
-  __TEXT.__cstring: 0x40a5b
-  __TEXT.__oslogstring: 0x758e
+3486.60.47.0.0
+  __TEXT.__text: 0xd54b8
+  __TEXT.__objc_methlist: 0x8bf0
+  __TEXT.__const: 0x690
+  __TEXT.__cstring: 0x40db3
+  __TEXT.__oslogstring: 0x7bc6
   __TEXT.__gcc_except_tab: 0x2160
-  __TEXT.__unwind_info: 0x3ca8
+  __TEXT.__unwind_info: 0x3d48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5228
+  __DATA_CONST.__objc_selrefs: 0x5290
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x2b0
-  __DATA_CONST.__objc_arraydata: 0x44788
+  __DATA_CONST.__objc_arraydata: 0x44b48
   __DATA_CONST.__got: 0x618
-  __AUTH_CONST.__const: 0x37d0
-  __AUTH_CONST.__cfstring: 0x69420
-  __AUTH_CONST.__objc_const: 0x9cc8
-  __AUTH_CONST.__objc_intobj: 0x4c20
+  __AUTH_CONST.__const: 0x3850
+  __AUTH_CONST.__cfstring: 0x699e0
+  __AUTH_CONST.__objc_const: 0x9cf8
+  __AUTH_CONST.__objc_intobj: 0x4c38
   __AUTH_CONST.__objc_doubleobj: 0x14d0
   __AUTH_CONST.__objc_arrayobj: 0x1020
-  __AUTH_CONST.__objc_dictobj: 0xf578
-  __AUTH_CONST.__auth_got: 0xb20
+  __AUTH_CONST.__objc_dictobj: 0xf668
+  __AUTH_CONST.__auth_got: 0xb68
   __AUTH.__objc_data: 0x460
-  __DATA.__objc_ivar: 0x708
+  __DATA.__objc_ivar: 0x70c
   __DATA.__data: 0x440
-  __DATA.__bss: 0x15e1
+  __DATA.__bss: 0x1611
   __DATA.__common: 0x8
   __DATA_DIRTY.__objc_data: 0x1c70
   __DATA_DIRTY.__data: 0x14

   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libsystemstats.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 4539
-  Symbols:   8486
-  CStrings:  14628
+  Functions: 4583
+  Symbols:   8521
+  CStrings:  14700
 
Symbols:
+ +[PLGestaltUtilities isV68]
+ +[PLUtilities isPlistSafeObject:]
+ +[PLUtilities isPlistSafeObject:atDepth:]
+ +[PLUtilities isValidBatteryUIRequestingService:]
+ +[PLUtilities privilegedCopyFileNamed:fromDirectoryFd:toDirectoryFd:]
+ +[PLUtilities privilegedCopyItemsFromPath:toDirectory:]
+ +[PLUtilities stringContainsControlCharacters:]
+ +[PPSFileUtilities(APFS) markFileDescriptorAsPurgeable:urgency:startDate:]
+ -[PLCoreStorage backgroundProcessingResponder]
+ -[PLCoreStorage setBackgroundProcessingResponder:]
+ GCC_except_table101
+ GCC_except_table111
+ GCC_except_table130
+ GCC_except_table137
+ GCC_except_table142
+ GCC_except_table155
+ GCC_except_table177
+ GCC_except_table180
+ GCC_except_table210
+ _OBJC_IVAR_$_PLCoreStorage._backgroundProcessingResponder
+ _OUTLINED_FUNCTION_16
+ _PLCopyPrunedBackgroundProcessingLog
+ ___27+[PLGestaltUtilities isV68]_block_invoke
+ ___47+[PLUtilities stringContainsControlCharacters:]_block_invoke
+ ___49+[PLUtilities isValidBatteryUIRequestingService:]_block_invoke
+ _closedir
+ _dirfd
+ _fcopyfile
+ _fdopendir
+ _fstat
+ _isV68.onceToken
+ _isV68.ret
+ _isValidBatteryUIRequestingService:.disallowedCharacters
+ _isValidBatteryUIRequestingService:.onceToken
+ _objc_msgSend$controlCharacterSet
+ _objc_msgSend$invertedSet
+ _objc_msgSend$isDeviceClass:
+ _objc_msgSend$isPlistSafeObject:atDepth:
+ _objc_msgSend$markFileDescriptorAsPurgeable:urgency:startDate:
+ _objc_msgSend$privilegedCopyFileNamed:fromDirectoryFd:toDirectoryFd:
+ _objc_msgSend$rangeOfCharacterFromSet:
+ _objc_msgSend$setBackgroundProcessingResponder:
+ _objc_msgSend$stringContainsControlCharacters:
+ _openat
+ _readdir
+ _stringContainsControlCharacters:.controlCharacters
+ _stringContainsControlCharacters:.onceToken
+ _unlinkat
- GCC_except_table100
- GCC_except_table110
- GCC_except_table115
- GCC_except_table129
- GCC_except_table136
- GCC_except_table141
- GCC_except_table146
- GCC_except_table154
- GCC_except_table172
- GCC_except_table176
- GCC_except_table202
- ___41-[PLCoreStorage initOperatorDependancies]_block_invoke_5
- ___41-[PLCoreStorage initOperatorDependancies]_block_invoke_6
CStrings:
+ "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789_-"
+ "AggAngleCloses"
+ "AggAngleOpens"
+ "AggIntAngleCloses"
+ "AggIntAngleOpens"
+ "AwakeTime"
+ "Background processing log not placed at destination '%{public}@': %{public}@"
+ "BackgroundProcessingLog"
+ "Capacity"
+ "Could not open source directory %@ for privileged copy, errno %d"
+ "DuetDiagnosticExtension"
+ "Error copying files from source path %@ to destination path %@"
+ "Failed to copy background processing log into %@: %@"
+ "Failed to copy background processing log: %@"
+ "Failed to create a scratch directory for the background processing log: %{public}@"
+ "Failed to mark fd %d as purgeable with label: '%@' (error %d = '%s')"
+ "Failed to remove the background processing log scratch directory: %{public}@"
+ "ForegroundApplications"
+ "ForegroundApplicationsX"
+ "HingeMetricsStartTime"
+ "HingeState"
+ "HingeUsage"
+ "Marked fd %d as purgeable with label: '%@'"
+ "MitigationValue"
+ "Object graph has control characters in a key, unsafe to serialize"
+ "Object graph has control characters in a string value, unsafe to serialize"
+ "Object graph has non-string key of class %{public}@, unsafe to serialize"
+ "PLDisplayAgent_EventForward_DisplayX_ALS"
+ "PLDisplayAgent_EventForward_Display_ALS"
+ "PartialCharge"
+ "PowerAssertions"
+ "Privileged copy could not create destination %s, errno %d"
+ "Privileged copy could not open source %s, errno %d"
+ "Privileged copy could not remove partial destination %s, errno %d"
+ "Privileged copy could not stat source %s, errno %d"
+ "Privileged copy of %s failed, errno %d"
+ "Privileged copy refusing non-regular source %s"
+ "Refusing privileged copy to %@, errno %d"
+ "Refusing privileged copy to destination of unexpected class %{public}@"
+ "Refusing privileged copy to empty destination path"
+ "Refusing to copy the background processing log to the destination requested by %@"
+ "Rejecting requestingService containing disallowed characters"
+ "Rejecting requestingService of unexpected class %{public}@"
+ "Rejecting requestingService with invalid length %lu"
+ "ScreenBrightness"
+ "ScreenBrightnessX"
+ "StandbyTime"
+ "TLCMitigation"
+ "TotalCloses"
+ "TotalOpens"
+ "Treating object graph nested deeper than %d levels as unsafe to serialize"
+ "VoltageMV"
+ "colorALSMask"
+ "colorX_1"
+ "colorX_14"
+ "colorY_1"
+ "colorY_14"
+ "colorZ_1"
+ "colorZ_14"
+ "embeddingTableMemoryCostKB"
+ "embeddingTableResidentRatio"
+ "expertsLoadedDuringPromptCount"
+ "expertsLoadedFromCacheDuringPromptCount"
+ "expertsNeedingNANDLoadDuringPromptCount"
+ "expertsSwappedDuringPromptCount"
+ "harmonyStrength"
+ "lux_1"
+ "lux_11"
+ "lux_14"
+ "totalExpertsLoadedCount"
+ "triggers"
+ "trustedALS"
```
