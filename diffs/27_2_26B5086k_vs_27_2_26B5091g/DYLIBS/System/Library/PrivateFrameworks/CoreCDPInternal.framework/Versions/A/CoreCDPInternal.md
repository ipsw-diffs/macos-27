## CoreCDPInternal

> `/System/Library/PrivateFrameworks/CoreCDPInternal.framework/Versions/A/CoreCDPInternal`

```diff

-448.125.5.1.0
-  __TEXT.__text: 0x93488
-  __TEXT.__objc_methlist: 0x5644
+448.125.6.0.0
+  __TEXT.__text: 0x943f4
+  __TEXT.__objc_methlist: 0x56d4
   __TEXT.__const: 0x890
-  __TEXT.__oslogstring: 0x14bda
-  __TEXT.__cstring: 0xe056
-  __TEXT.__gcc_except_tab: 0xb1c
+  __TEXT.__oslogstring: 0x14caa
+  __TEXT.__cstring: 0xe136
+  __TEXT.__gcc_except_tab: 0xb4c
   __TEXT.__dlopen_cstrs: 0xbc
   __TEXT.__constg_swiftt: 0x1e4
   __TEXT.__swift5_typeref: 0x3b8

   __TEXT.__swift_as_ret: 0x58
   __TEXT.__swift_as_cont: 0x68
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x2ec8
+  __TEXT.__unwind_info: 0x2f38
   __TEXT.__eh_frame: 0x8f0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4d0
-  __DATA_CONST.__objc_classlist: 0x288
+  __DATA_CONST.__const: 0x4d8
+  __DATA_CONST.__objc_classlist: 0x290
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x180
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3928
+  __DATA_CONST.__objc_selrefs: 0x3988
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x150
   __DATA_CONST.__objc_arraydata: 0x220
-  __DATA_CONST.__got: 0x10f8
-  __AUTH_CONST.__const: 0x2dc0
-  __AUTH_CONST.__cfstring: 0x94c0
-  __AUTH_CONST.__objc_const: 0xfb48
+  __DATA_CONST.__got: 0x1100
+  __AUTH_CONST.__const: 0x2ec0
+  __AUTH_CONST.__cfstring: 0x9560
+  __AUTH_CONST.__objc_const: 0xfcb8
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__auth_got: 0x800
-  __AUTH.__objc_data: 0x120
-  __DATA.__objc_ivar: 0x3ac
+  __AUTH.__objc_data: 0x170
+  __DATA.__objc_ivar: 0x3c4
   __DATA.__data: 0x1190
   __DATA.__bss: 0x498
   __DATA_DIRTY.__objc_data: 0x1910

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3209
-  Symbols:   5939
-  CStrings:  2802
+  Functions: 3235
+  Symbols:   5997
+  CStrings:  2810
 
Symbols:
+ -[CDPDAsyncSecureBackupEnableTracker .cxx_destruct]
+ -[CDPDAsyncSecureBackupEnableTracker _recordOutcomeWithReason:]
+ -[CDPDAsyncSecureBackupEnableTracker _timeOutCurrentWaiter]
+ -[CDPDAsyncSecureBackupEnableTracker awaitSettleWithTimeout:completionHandler:]
+ -[CDPDAsyncSecureBackupEnableTracker enableStarted]
+ -[CDPDAsyncSecureBackupEnableTracker recordDidEnable:error:]
+ -[CDPDAsyncSecureBackupEnableTracker recordEnableStarted]
+ -[CDPDPCSController _sendGeneratePDPBlob:completion:]
+ -[CDPDPCSController _sendSetupPDPIdentities:completion:]
+ -[CDPDStateMachine _afterAsyncSecureBackupEnableSettles:]
+ -[CDPDStateMachine initWithContext:uiProvider:asyncSecureBackupEnableTracker:]
+ GCC_except_table129
+ GCC_except_table19
+ GCC_except_table39
+ GCC_except_table49
+ GCC_except_table57
+ GCC_except_table66
+ GCC_except_table68
+ GCC_except_table72
+ OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._didRecordOutcome
+ OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._enableStarted
+ OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._lock
+ OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._outcomeReason
+ OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._waiter
+ OBJC_IVAR_$_CDPDStateMachine._asyncSecureBackupEnableTracker
+ _CDPDAsyncSecureBackupEnableTrackerErrorDomain
+ _OBJC_CLASS_$_CDPDAsyncSecureBackupEnableTracker
+ _OBJC_METACLASS_$_CDPDAsyncSecureBackupEnableTracker
+ _OUTLINED_FUNCTION_12
+ __53-[CDPDPCSController _sendGeneratePDPBlob:completion:]_block_invoke
+ __53-[CDPDPCSController _sendGeneratePDPBlob:completion:]_block_invoke_2
+ __54-[CDPDStateMachine _attemptPDPFallbackWithCompletion:]_block_invoke_2
+ __56-[CDPDPCSController _sendSetupPDPIdentities:completion:]_block_invoke
+ __56-[CDPDPCSController _sendSetupPDPIdentities:completion:]_block_invoke_2
+ __57-[CDPDStateMachine _afterAsyncSecureBackupEnableSettles:]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_$_INSTANCE_VARIABLES_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_$_PROP_LIST_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_CLASS_RO_$_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_METACLASS_RO_$_CDPDAsyncSecureBackupEnableTracker
+ ___53-[CDPDPCSController _sendGeneratePDPBlob:completion:]_block_invoke
+ ___53-[CDPDPCSController _sendGeneratePDPBlob:completion:]_block_invoke_2
+ ___54-[CDPDStateMachine _attemptPDPFallbackWithCompletion:]_block_invoke_2
+ ___56-[CDPDPCSController _sendSetupPDPIdentities:completion:]_block_invoke
+ ___56-[CDPDPCSController _sendSetupPDPIdentities:completion:]_block_invoke_2
+ ___57-[CDPDStateMachine _afterAsyncSecureBackupEnableSettles:]_block_invoke
+ ___79-[CDPDAsyncSecureBackupEnableTracker awaitSettleWithTimeout:completionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32bs40r_e20_v24?0q8"NSError"16l
+ ___block_descriptor_48_e8_32bs40r_e28_v24?0"NSData"8"NSError"16l
+ ___block_descriptor_48_e8_32bs40r_e30_v24?0"NSNumber"8"NSError"16l
+ ___block_descriptor_56_e8_32s40r48w_e35_v16?0?<v?"NSNumber""NSError">8l
+ ___block_descriptor_56_e8_32s40s48r_e33_v16?0?<v?"NSData""NSError">8l
+ ___copy_helper_block_e8_32s40r48w
+ ___destroy_helper_block_e8_32s40r48w
+ _objc_msgSend$_afterAsyncSecureBackupEnableSettles:
+ _objc_msgSend$_recordOutcomeWithReason:
+ _objc_msgSend$_sendGeneratePDPBlob:completion:
+ _objc_msgSend$_sendSetupPDPIdentities:completion:
+ _objc_msgSend$_timeOutCurrentWaiter
+ _objc_msgSend$awaitSettleWithTimeout:completionHandler:
+ _objc_msgSend$cdp_isTransientNetworkErrorIncludingUnderlyingErrors
+ _objc_msgSend$doubleValue
+ _objc_msgSend$enableStarted
+ _objc_msgSend$initWithContext:uiProvider:asyncSecureBackupEnableTracker:
+ _objc_msgSend$recordDidEnable:error:
+ _objc_msgSend$recordEnableStarted
- GCC_except_table128
- GCC_except_table37
- GCC_except_table45
- GCC_except_table48
- GCC_except_table50
- GCC_except_table55
- __54-[CDPDStateMachine _attemptPDPFallbackWithCompletion:]_block_invoke
- ___block_descriptor_40_e8_32bs_e28_v24?0"NSData"8"NSError"16l
CStrings:
+ "%@: Renewed credentials, retrying PDP blob generation"
+ "CDPDAsyncSecureBackupEnableTracker"
+ "CDPDStateMachine: asynchronous secure-backup enable did not deliver, skipping post-Octagon PDP setup: %@"
+ "CDPDStateMachine: waiting up to %@s for asynchronous secure-backup enable to settle before post-Octagon PDP setup"
+ "DBRAsyncEnableSettleTimeout"
+ "com.apple.corecdp.pdpRecordGenerationAhead"
+ "com.apple.corecdp.pdpRecordGenerationCheckSkipped"
+ "com.apple.corecdp.pdpWrappingKeyRepair"
+ "v16@?0@?<v@?@\"NSData\"@\"NSError\">8"
- "Generate PDP Blob retry completed with blob length=%lu error=%@"
```
