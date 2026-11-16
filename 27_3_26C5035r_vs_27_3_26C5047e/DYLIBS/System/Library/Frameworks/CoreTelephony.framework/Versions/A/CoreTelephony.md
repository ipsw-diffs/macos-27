## CoreTelephony

> `/System/Library/Frameworks/CoreTelephony.framework/Versions/A/CoreTelephony`

```diff

-13504.1.0.0.0
-  __TEXT.__text: 0x16b080
-  __TEXT.__objc_methlist: 0x16bd4
-  __TEXT.__cstring: 0x1c298
+13508.0.0.0.0
+  __TEXT.__text: 0x169c10
+  __TEXT.__objc_methlist: 0x16c1c
+  __TEXT.__cstring: 0x1c168
   __TEXT.__const: 0x15f0
-  __TEXT.__gcc_except_tab: 0x19c14
-  __TEXT.__oslogstring: 0x45d6
+  __TEXT.__gcc_except_tab: 0x19c18
+  __TEXT.__oslogstring: 0x4146
   __TEXT.__swift5_typeref: 0x259
   __TEXT.__constg_swiftt: 0x118
   __TEXT.__swift5_builtin: 0x3c

   __TEXT.__swift_as_entry: 0x10
   __TEXT.__swift_as_ret: 0x10
   __TEXT.__swift_as_cont: 0x30
-  __TEXT.__unwind_info: 0xcbe0
+  __TEXT.__unwind_info: 0xcbd8
   __TEXT.__eh_frame: 0x370
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4f08
-  __DATA_CONST.__objc_classlist: 0x1130
+  __DATA_CONST.__const: 0x4ea0
+  __DATA_CONST.__objc_classlist: 0x1138
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x258
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6a60
+  __DATA_CONST.__objc_selrefs: 0x6a70
   __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__objc_superrefs: 0x1230
+  __DATA_CONST.__objc_superrefs: 0x1240
   __DATA_CONST.__objc_arraydata: 0x30
   __DATA_CONST.__got: 0x978
-  __AUTH_CONST.__const: 0x3938
-  __AUTH_CONST.__cfstring: 0x19f40
-  __AUTH_CONST.__objc_const: 0x27218
+  __AUTH_CONST.__const: 0x38e8
+  __AUTH_CONST.__cfstring: 0x19f20
+  __AUTH_CONST.__objc_const: 0x272b0
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_intobj: 0x30
-  __AUTH_CONST.__auth_got: 0xd18
-  __AUTH.__objc_data: 0x8520
+  __AUTH_CONST.__auth_got: 0xd08
+  __AUTH.__objc_data: 0x8570
   __AUTH.__data: 0xb0
   __DATA.__objc_ivar: 0x1048
   __DATA.__data: 0x2110

   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x2670
   __DATA_DIRTY.__data: 0x90
-  __DATA_DIRTY.__bss: 0x12a0
+  __DATA_DIRTY.__bss: 0x1290
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/Network.framework/Versions/A/Network

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 9695
-  Symbols:   20525
-  CStrings:  5392
+  Functions: 9686
+  Symbols:   20523
+  CStrings:  5353
 
Symbols:
+ +[CTXPCLazuliDiagnosticCommandRequest allowedClassesForArguments]
+ -[CTXPCLazuliDiagnosticCommandRequest command]
+ -[CTXPCLazuliDiagnosticCommandRequest ct_shortName]
+ -[CTXPCLazuliDiagnosticCommandRequest initWithCommand:]
+ -[CTXPCLazuliDiagnosticCommandRequest performRequestWithHandler:completionHandler:]
+ -[CTXPCLazuliDiagnosticCommandRequest requiredEntitlement]
+ -[CoreTelephonyClient(Lazuli) runLazuliDiagnosticCommand:withError:]
+ GCC_except_table344
+ GCC_except_table382
+ GCC_except_table385
+ _OBJC_CLASS_$_CTXPCLazuliDiagnosticCommandRequest
+ _OBJC_METACLASS_$_CTXPCLazuliDiagnosticCommandRequest
+ __OBJC_$_CLASS_METHODS_CTXPCLazuliDiagnosticCommandRequest
+ __OBJC_$_INSTANCE_METHODS_CTXPCLazuliDiagnosticCommandRequest
+ __OBJC_$_PROP_LIST_CTXPCLazuliDiagnosticCommandRequest
+ __OBJC_CLASS_RO_$_CTXPCLazuliDiagnosticCommandRequest
+ __OBJC_METACLASS_RO_$_CTXPCLazuliDiagnosticCommandRequest
+ ___68-[CoreTelephonyClient(Lazuli) runLazuliDiagnosticCommand:withError:]_block_invoke
+ ___68-[CoreTelephonyClient(Lazuli) runLazuliDiagnosticCommand:withError:]_block_invoke_2
+ ___83-[CTXPCLazuliDiagnosticCommandRequest performRequestWithHandler:completionHandler:]_block_invoke
+ _objc_msgSend$command
+ _objc_msgSend$initWithCommand:
+ _objc_msgSend$runLazuliDiagnosticCommand:completion:
- -[CoreTelephonyClient(SMS) injectMTsms:smsData:completion:]
- GCC_except_table343
- GCC_except_table399
- GCC_except_table400
- _OUTLINED_FUNCTION_9
- __ZL17logBlockedRequestPKcRKN3xpc4dictEP20__CTServerConnection20CTFeatureRequirement
- __ZZN8dispatch5asyncIZN9CCMonitor10initializeEvE3$_1EEvP16dispatch_queue_sNSt3__110unique_ptrIT_NS5_14default_deleteIS7_EEEEENUlPvE_8__invokeESB_
- __ZZN8dispatch5asyncIZZN9CCMonitor10initializeEvEUb_E3$_0EEvP16dispatch_queue_sNSt3__110unique_ptrIT_NS5_14default_deleteIS7_EEEEENUlPvE_8__invokeESB_
- __ZZN9CCMonitor9getLoggerEvE10sOnceToken
- __ZZN9CCMonitor9getLoggerEvE7sLogger
- ___55-[CoreTelephonyClient(Stewie) testStewieCommand:error:]_block_invoke
- ___55-[CoreTelephonyClient(Stewie) testStewieCommand:error:]_block_invoke_2
- ___59-[CoreTelephonyClient(SMS) injectMTsms:smsData:completion:]_block_invoke
- ___60-[CoreTelephonyClient(Stewie) testStewieCommand:completion:]_block_invoke
- ____ZN9CCMonitor10initializeEv_block_invoke
- ____ZN9CCMonitor9getLoggerEv_block_invoke
- ___block_descriptor_48_e8_32r40r_e34_v24?0"NSError"8"NSDictionary"16l
- _notify_get_state
- _notify_register_dispatch
- _objc_msgSend$epki
- _objc_msgSend$injectMTsms:smsData:completion:
- _objc_msgSend$setEpki:
- _objc_msgSend$setShared:
- _objc_msgSend$shared
- _objc_msgSend$testStewieCommand:completion:
CStrings:
+ "13508"
+ "13508~17"
+ "LazuliDiagnosticCommandRequest"
+ "command"
+ "messagesAppNotInstalled"
- ", epki=%@, shared=%@"
- "13504.1"
- "13504.1~151"
- "Attempt to connect to CT from %s blocked, use _CTServerConnectionAddIdentifierException to add exception"
- "Available features: [%s]"
- "Blocking %s (request: '%s', state: %s, required: %s, %p)"
- "Body:"
- "CTStewieRequestReasonAnywhere"
- "CTStewieRequestReasonAnywhereTest"
- "CTStewieRequestReasonTest"
- "CommCenter is always-on. CCMonitor is NOT used"
- "Communication blocked but cached value found. Request: '%s'. Reply: '%s'"
- "CoreTelephony logging is %s by default"
- "Daemon becomes ready..."
- "DataLen = %u"
- "Failed to create notify token for '%s'. Logging is %s by default"
- "Failed to re-register notifications in _HandleConnectionReEstablished(). Error: {domain=%d, error=%d}"
- "Failed to re-register notifications in _HandlePrepWorkBeforeSend(). Error: {domain=%d, error=%d}"
- "HeadersLen = %u"
- "Logging is %s"
- "OS log created"
- "Part %u"
- "ReregisterClientForAllEvents request is not allowed at this time. Registration is delayed"
- "XPC message"
- "XPC message with reply"
- "_CTServerConnectionGetCommCenterInitializationState request is not allowed at this time"
- "_CTServerConnectionRegisterForEvent request is not allowed at this time. Registration is delayed"
- "_CTServerConnectionUnregisterForAllNotifications request is not allowed at this time"
- "_CTServerConnectionUnregisterForEvent request is not allowed at this time"
- "async XPC message"
- "com.apple.CoreTelephony.LoggingEnabled"
- "epki"
- "kBaseband"
- "kDaemonRunning"
- "kDefaultAllowed"
- "kNotRunning"
- "kRunning"
- "kTestBlocked"
- "kThumper"
- "kUnknown"
- "nEntries = %u"
- "shared"
- "v12@?0i8"
- "v24@?0@\"NSError\"8@\"NSDictionary\"16"
```
