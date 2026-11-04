## AudioAccessoryServices

> `/System/Library/PrivateFrameworks/AudioAccessoryServices.framework/Versions/A/AudioAccessoryServices`

```diff

-41.7.0.0.0
-  __TEXT.__text: 0x4ee10
-  __TEXT.__objc_methlist: 0x6024
+42.4.1.0.0
+  __TEXT.__text: 0x506d0
+  __TEXT.__objc_methlist: 0x61ac
   __TEXT.__const: 0x240
-  __TEXT.__gcc_except_tab: 0x1884
-  __TEXT.__cstring: 0xdb92
-  __TEXT.__unwind_info: 0x1cf8
+  __TEXT.__gcc_except_tab: 0x18c8
+  __TEXT.__cstring: 0xdf39
+  __TEXT.__unwind_info: 0x1db8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x980
-  __DATA_CONST.__objc_classlist: 0x1c0
+  __DATA_CONST.__objc_classlist: 0x1d0
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2978
+  __DATA_CONST.__objc_selrefs: 0x29c0
   __DATA_CONST.__objc_protorefs: 0x40
-  __DATA_CONST.__objc_superrefs: 0x168
-  __DATA_CONST.__got: 0x200
-  __AUTH_CONST.__const: 0xdb0
-  __AUTH_CONST.__cfstring: 0x2b80
-  __AUTH_CONST.__objc_const: 0xaa38
+  __DATA_CONST.__objc_superrefs: 0x178
+  __DATA_CONST.__got: 0x210
+  __AUTH_CONST.__const: 0xdf0
+  __AUTH_CONST.__cfstring: 0x2bc0
+  __AUTH_CONST.__objc_const: 0xad48
   __AUTH_CONST.__auth_got: 0x0
+  __AUTH.__objc_data: 0xa0
   __AUTH.__data: 0x8
-  __DATA.__objc_ivar: 0xa0c
-  __DATA.__data: 0xe18
+  __DATA.__objc_ivar: 0xa30
+  __DATA.__data: 0xe88
   __DATA.__common: 0x8
-  __DATA.__bss: 0x58
+  __DATA.__bss: 0x68
   __DATA_DIRTY.__objc_data: 0x1180
   __DATA_DIRTY.__data: 0x3f0
-  __DATA_DIRTY.__bss: 0x120
+  __DATA_DIRTY.__bss: 0x130
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices

   - /System/Library/PrivateFrameworks/Sharing.framework/Versions/A/Sharing
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2719
-  Symbols:   4505
-  CStrings:  1855
+  Functions: 2780
+  Symbols:   4579
+  CStrings:  1876
 
Symbols:
+ +[AAAccessoryUsageEvent supportsSecureCoding]
+ +[AAAccessoryUsageHistoryManager supportsSecureCoding]
+ -[AAAccessoryUsageEvent .cxx_destruct]
+ -[AAAccessoryUsageEvent description]
+ -[AAAccessoryUsageEvent encodeWithCoder:]
+ -[AAAccessoryUsageEvent initWithCoder:]
+ -[AAAccessoryUsageEvent initWithUsed:timestamp:]
+ -[AAAccessoryUsageEvent isUsed]
+ -[AAAccessoryUsageEvent timestamp]
+ -[AAAccessoryUsageHistoryManager .cxx_destruct]
+ -[AAAccessoryUsageHistoryManager _activate]
+ -[AAAccessoryUsageHistoryManager _ensureXPCStarted]
+ -[AAAccessoryUsageHistoryManager _interrupted]
+ -[AAAccessoryUsageHistoryManager _invalidated]
+ -[AAAccessoryUsageHistoryManager _reportError:]
+ -[AAAccessoryUsageHistoryManager activateWithCompletion:]
+ -[AAAccessoryUsageHistoryManager clientID]
+ -[AAAccessoryUsageHistoryManager description]
+ -[AAAccessoryUsageHistoryManager dispatchQueue]
+ -[AAAccessoryUsageHistoryManager encodeWithCoder:]
+ -[AAAccessoryUsageHistoryManager initWithCoder:]
+ -[AAAccessoryUsageHistoryManager init]
+ -[AAAccessoryUsageHistoryManager invalidate]
+ -[AAAccessoryUsageHistoryManager isSystemContext]
+ -[AAAccessoryUsageHistoryManager setClientID:]
+ -[AAAccessoryUsageHistoryManager setDispatchQueue:]
+ -[AAAccessoryUsageHistoryManager usageHistoryForInterval:completion:]
+ _OBJC_CLASS_$_AAAccessoryUsageEvent
+ _OBJC_CLASS_$_AAAccessoryUsageHistoryManager
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_IVAR_$_AAAccessoryUsageEvent._isUsed
+ _OBJC_IVAR_$_AAAccessoryUsageEvent._timestamp
+ _OBJC_IVAR_$_AAAccessoryUsageHistoryManager._activateCalled
+ _OBJC_IVAR_$_AAAccessoryUsageHistoryManager._activateCompletion
+ _OBJC_IVAR_$_AAAccessoryUsageHistoryManager._clientID
+ _OBJC_IVAR_$_AAAccessoryUsageHistoryManager._dispatchQueue
+ _OBJC_IVAR_$_AAAccessoryUsageHistoryManager._invalidateCalled
+ _OBJC_IVAR_$_AAAccessoryUsageHistoryManager._invalidateDone
+ _OBJC_IVAR_$_AAAccessoryUsageHistoryManager._xpcCnx
+ _OBJC_METACLASS_$_AAAccessoryUsageEvent
+ _OBJC_METACLASS_$_AAAccessoryUsageHistoryManager
+ __OBJC_$_CLASS_METHODS_AAAccessoryUsageEvent
+ __OBJC_$_CLASS_METHODS_AAAccessoryUsageHistoryManager
+ __OBJC_$_CLASS_PROP_LIST_AAAccessoryUsageEvent
+ __OBJC_$_CLASS_PROP_LIST_AAAccessoryUsageHistoryManager
+ __OBJC_$_INSTANCE_METHODS_AAAccessoryUsageEvent
+ __OBJC_$_INSTANCE_METHODS_AAAccessoryUsageHistoryManager
+ __OBJC_$_INSTANCE_VARIABLES_AAAccessoryUsageEvent
+ __OBJC_$_INSTANCE_VARIABLES_AAAccessoryUsageHistoryManager
+ __OBJC_$_PROP_LIST_AAAccessoryUsageEvent
+ __OBJC_$_PROP_LIST_AAAccessoryUsageHistoryManager
+ __OBJC_CLASS_PROTOCOLS_$_AAAccessoryUsageEvent
+ __OBJC_CLASS_PROTOCOLS_$_AAAccessoryUsageHistoryManager
+ __OBJC_CLASS_RO_$_AAAccessoryUsageEvent
+ __OBJC_CLASS_RO_$_AAAccessoryUsageHistoryManager
+ __OBJC_METACLASS_RO_$_AAAccessoryUsageEvent
+ __OBJC_METACLASS_RO_$_AAAccessoryUsageHistoryManager
+ ___36-[AAAccessoryUsageEvent description]_block_invoke
+ ___43-[AAAccessoryUsageHistoryManager _activate]_block_invoke
+ ___44-[AAAccessoryUsageHistoryManager invalidate]_block_invoke
+ ___49-[AAAccessoryUsageHistoryManager isSystemContext]_block_invoke
+ ___51-[AAAccessoryUsageHistoryManager _ensureXPCStarted]_block_invoke
+ ___57-[AAAccessoryUsageHistoryManager activateWithCompletion:]_block_invoke
+ ___69-[AAAccessoryUsageHistoryManager usageHistoryForInterval:completion:]_block_invoke
+ ___69-[AAAccessoryUsageHistoryManager usageHistoryForInterval:completion:]_block_invoke_2
+ _description.sFormatter
+ _description.sOnce
+ _gLogCategory_AAAccessoryUsageHistoryManager
+ _objc_msgSend$activateAccessoryUsageHistoryManager:completion:
+ _objc_msgSend$fetchAccessoryUsageHistory:interval:completion:
+ _objc_msgSend$initWithUsed:timestamp:
+ _objc_msgSend$setDateFormat:
+ _objc_msgSend$setTimeZone:
+ _objc_msgSend$stringFromDate:
CStrings:
+ "### Fetch XPC error: %{error}"
+ "### Fetch failed: %{error}"
+ "### Fetch failed: already invalidated"
+ "### Fetch failed: not activated"
+ "-[AAAccessoryUsageHistoryManager _activate]"
+ "-[AAAccessoryUsageHistoryManager _activate]_block_invoke"
+ "-[AAAccessoryUsageHistoryManager _ensureXPCStarted]"
+ "-[AAAccessoryUsageHistoryManager _interrupted]"
+ "-[AAAccessoryUsageHistoryManager _invalidated]"
+ "-[AAAccessoryUsageHistoryManager _reportError:]"
+ "-[AAAccessoryUsageHistoryManager activateWithCompletion:]_block_invoke"
+ "-[AAAccessoryUsageHistoryManager invalidate]_block_invoke"
+ "-[AAAccessoryUsageHistoryManager usageHistoryForInterval:completion:]_block_invoke"
+ "-[AAAccessoryUsageHistoryManager usageHistoryForInterval:completion:]_block_invoke_2"
+ "AAAccessoryUsageEvent, isUsed %d, timestamp %@"
+ "AAAccessoryUsageHistoryManager"
+ "AAAccessoryUsageHistoryManager, CID 0x%X"
+ "Fetch completed: %zu event(s)"
+ "Fetching usage history for interval %@"
+ "ts"
+ "used"
+ "yyyy-MM-dd HH:mm:ss.SSS ZZZ"
- "%@-Seed-mov"
```
