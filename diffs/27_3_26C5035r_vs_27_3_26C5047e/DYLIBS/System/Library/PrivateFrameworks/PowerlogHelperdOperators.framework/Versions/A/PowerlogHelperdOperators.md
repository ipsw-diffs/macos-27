## PowerlogHelperdOperators

> `/System/Library/PrivateFrameworks/PowerlogHelperdOperators.framework/Versions/A/PowerlogHelperdOperators`

```diff

-3486.60.36.0.0
-  __TEXT.__text: 0x113b6c
-  __TEXT.__objc_methlist: 0xaa78
+3486.60.47.0.0
+  __TEXT.__text: 0x1165a8
+  __TEXT.__objc_methlist: 0xab18
   __TEXT.__const: 0x4c0
-  __TEXT.__cstring: 0x16d20
-  __TEXT.__oslogstring: 0xb633
-  __TEXT.__gcc_except_tab: 0x1cf0
-  __TEXT.__unwind_info: 0x39d8
+  __TEXT.__cstring: 0x16fe2
+  __TEXT.__oslogstring: 0xbb66
+  __TEXT.__gcc_except_tab: 0x1d08
+  __TEXT.__unwind_info: 0x3a90
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2290
+  __DATA_CONST.__const: 0x22e8
   __DATA_CONST.__objc_classlist: 0x248
   __DATA_CONST.__objc_nlclslist: 0xb0
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7498
+  __DATA_CONST.__objc_selrefs: 0x7528
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x1d8
   __DATA_CONST.__objc_arraydata: 0x2918
   __DATA_CONST.__got: 0xac0
-  __AUTH_CONST.__const: 0x2c58
-  __AUTH_CONST.__cfstring: 0x20f80
-  __AUTH_CONST.__objc_const: 0xdbe8
+  __AUTH_CONST.__const: 0x2ce8
+  __AUTH_CONST.__cfstring: 0x213c0
+  __AUTH_CONST.__objc_const: 0xdc18
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_doubleobj: 0x6b0
   __AUTH_CONST.__objc_intobj: 0x14e8
   __AUTH_CONST.__objc_dictobj: 0x1d10
   __AUTH_CONST.__objc_arrayobj: 0xd80
-  __AUTH_CONST.__auth_got: 0xb88
+  __AUTH_CONST.__auth_got: 0xbc8
   __AUTH.__objc_data: 0xa78
-  __DATA.__objc_ivar: 0xde8
+  __DATA.__objc_ivar: 0xdec
   __DATA.__data: 0x3a0
-  __DATA.__bss: 0xe60
+  __DATA.__bss: 0xe90
   __DATA.__common: 0x74
   __DATA_DIRTY.__objc_data: 0xc58
   __DATA_DIRTY.__bss: 0x2c0

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 5384
-  Symbols:   10638
-  CStrings:  5549
+  Functions: 5434
+  Symbols:   10703
+  CStrings:  5605
 
Symbols:
+ +[PLUtilities isPlistSafeObject:]
+ +[PLUtilities isPlistSafeObject:atDepth:]
+ +[PLUtilities isValidBatteryUIRequestingService:]
+ +[PLUtilities privilegedCopyFileNamed:fromDirectoryFd:toDirectoryFd:]
+ +[PLUtilities privilegedCopyItemsFromPath:toDirectory:]
+ +[PLUtilities stringContainsControlCharacters:]
+ +[PPSFileUtilities(APFS) markFileDescriptorAsPurgeable:urgency:startDate:]
+ -[PLBatteryAgent parsedAlertKeysFromLowBatteryLogString:]
+ -[PLBatteryAgent parsedCPMSKeysFromLowBatteryLogString:]
+ -[PLBatteryUIResponderService plistSafeResultDictionary]
+ -[PLXPCAgent handleHingeUsageNotificationWithPayload:]
+ -[PLXPCAgent hingeUsageXPCListener]
+ -[PLXPCAgent logHingeUsageToCA:]
+ -[PLXPCAgent setHingeUsageXPCListener:]
+ GCC_except_table11
+ GCC_except_table180
+ GCC_except_table210
+ GCC_except_table252
+ GCC_except_table254
+ GCC_except_table258
+ GCC_except_table27
+ GCC_except_table30
+ GCC_except_table302
+ GCC_except_table306
+ GCC_except_table310
+ GCC_except_table34
+ GCC_except_table41
+ _OBJC_IVAR_$_PLXPCAgent._hingeUsageXPCListener
+ _PLBatteryAgentIntegerFromLowBatteryLogValue
+ _PLBatteryAgentRealFromLowBatteryLogValue
+ _PLBatteryAgentSecondsFromLowBatteryLogDuration
+ _PLBatteryAgentSplitPerDisplayValue
+ _PLBatteryAgentSplitPerDisplayValue.once
+ _PLBatteryAgentSplitPerDisplayValue.regex
+ _PLBatteryUsageUIKeyForRequest
+ ___32-[PLXPCAgent logHingeUsageToCA:]_block_invoke
+ ___47+[PLUtilities stringContainsControlCharacters:]_block_invoke
+ ___49+[PLUtilities isValidBatteryUIRequestingService:]_block_invoke
+ ___56-[PLBatteryAgent parsedCPMSKeysFromLowBatteryLogString:]_block_invoke
+ ___56-[PLBatteryAgent parsedCPMSKeysFromLowBatteryLogString:]_block_invoke_2
+ ___56-[PLBatteryUIResponderService plistSafeResultDictionary]_block_invoke
+ ___PLBatteryAgentSplitPerDisplayValue_block_invoke
+ ___block_descriptor_40_e8_32s_e25_v32?0"NSString"816^B24l
+ _closedir
+ _dirfd
+ _fcopyfile
+ _fdopendir
+ _fstat
+ _isValidBatteryUIRequestingService:.disallowedCharacters
+ _isValidBatteryUIRequestingService:.onceToken
+ _kPLBatteryAgentStringAwakeTime
+ _kPLBatteryAgentStringCapacity
+ _kPLBatteryAgentStringForegroundApplications
+ _kPLBatteryAgentStringForegroundApplicationsX
+ _kPLBatteryAgentStringHingeState
+ _kPLBatteryAgentStringPartialCharge
+ _kPLBatteryAgentStringPowerAssertions
+ _kPLBatteryAgentStringScreenBrightness
+ _kPLBatteryAgentStringScreenBrightnessX
+ _kPLBatteryAgentStringStandbyTime
+ _kPLBatteryAgentStringVoltageMV
+ _objc_msgSend$controlCharacterSet
+ _objc_msgSend$invertedSet
+ _objc_msgSend$isPlistSafeObject:
+ _objc_msgSend$isPlistSafeObject:atDepth:
+ _objc_msgSend$isValidBatteryUIRequestingService:
+ _objc_msgSend$logHingeUsageToCA:
+ _objc_msgSend$markFileDescriptorAsPurgeable:urgency:startDate:
+ _objc_msgSend$parsedAlertKeysFromLowBatteryLogString:
+ _objc_msgSend$parsedCPMSKeysFromLowBatteryLogString:
+ _objc_msgSend$plistSafeResultDictionary
+ _objc_msgSend$privilegedCopyFileNamed:fromDirectoryFd:toDirectoryFd:
+ _objc_msgSend$privilegedCopyItemsFromPath:toDirectory:
+ _objc_msgSend$rangeOfCharacterFromSet:
+ _objc_msgSend$scanDouble:
+ _objc_msgSend$scanLongLong:
+ _objc_msgSend$stringContainsControlCharacters:
+ _openat
+ _parsedCPMSKeysFromLowBatteryLogString:.kvRegex
+ _parsedCPMSKeysFromLowBatteryLogString:.once
+ _readdir
+ _stringContainsControlCharacters:.controlCharacters
+ _stringContainsControlCharacters:.onceToken
+ _unlinkat
- -[PLBatteryAgent parsedCPMSKeysFromLowBatteryLog]
- GCC_except_table172
- GCC_except_table202
- GCC_except_table22
- GCC_except_table242
- GCC_except_table243
- GCC_except_table249
- GCC_except_table297
- GCC_except_table300
- GCC_except_table304
- GCC_except_table31
- GCC_except_table33
- _CFDataGetTypeID
- ___49-[PLBatteryAgent parsedCPMSKeysFromLowBatteryLog]_block_invoke
- ___49-[PLBatteryAgent parsedCPMSKeysFromLowBatteryLog]_block_invoke_2
- _objc_msgSend$PLCopyItemsFromPath:toPath:
- _objc_msgSend$parsedCPMSKeysFromLowBatteryLog
- _parsedCPMSKeysFromLowBatteryLog.kvRegex
- _parsedCPMSKeysFromLowBatteryLog.once
CStrings:
+ ":"
+ ": "
+ "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789_-"
+ "Awake Time"
+ "AwakeTime"
+ "Capacity"
+ "CoreMotion"
+ "Could not open source directory %@ for privileged copy, errno %d"
+ "Error copying files from source path %@ to destination path %@"
+ "Failed to mark fd %d as purgeable with label: '%@' (error %d = '%s')"
+ "Foreground Applications"
+ "ForegroundApplications"
+ "ForegroundApplicationsX"
+ "Hinge State"
+ "HingeMetricsStartTime"
+ "HingeState"
+ "HingeUsage"
+ "HingeUsage: logging data to CA: %@"
+ "HingeUsage: logging entry: %@"
+ "HingeUsage: received nil payload"
+ "Marked fd %d as purgeable with label: '%@'"
+ "Object graph has control characters in a key, unsafe to serialize"
+ "Object graph has control characters in a string value, unsafe to serialize"
+ "Object graph has non-string key of class %{public}@, unsafe to serialize"
+ "Partial Charge"
+ "PartialCharge"
+ "Power Assertions"
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
+ "Rejecting requestingService containing disallowed characters"
+ "Rejecting requestingService of unexpected class %{public}@"
+ "Rejecting requestingService with invalid length %lu"
+ "Responder Service: omitting entry with unsafe key from plist"
+ "Responder Service: omitting entry with unsafe value from plist"
+ "Responder Service: omitting non-string key from plist"
+ "Screen Brightness"
+ "ScreenBrightness"
+ "ScreenBrightnessX"
+ "Standby Time"
+ "StandbyTime"
+ "TotalCloses"
+ "TotalOpens"
+ "Treating object graph nested deeper than %d levels as unsafe to serialize"
+ "VoltageMV"
+ "\\.inner:\\s*(\\{[^}]*\\}|[^,}]+?)\\s*,\\s*\\.cover:\\s*(\\{[^}]*\\}|[^,}]+?)\\s*\\}"
+ "com.apple.power.hingeUsage"
+ "embeddingTableResidentRatio"
+ "expertsLoadedDuringPromptCount"
+ "expertsLoadedFromCacheDuringPromptCount"
+ "expertsNeedingNANDLoadDuringPromptCount"
+ "expertsSwappedDuringPromptCount"
+ "totalExpertsLoadedCount"
- "Checking %@ with flags %u"
- "Could not get eachFlags"
- "Could not get flags"
- "Skip %@ with flags %u - not a full AP wake reason"
```
