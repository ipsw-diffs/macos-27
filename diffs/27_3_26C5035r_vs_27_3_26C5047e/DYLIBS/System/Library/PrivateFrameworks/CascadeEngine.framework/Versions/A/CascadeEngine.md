## CascadeEngine

> `/System/Library/PrivateFrameworks/CascadeEngine.framework/Versions/A/CascadeEngine`

```diff

-259.2.0.2.0
-  __TEXT.__text: 0x80fec
-  __TEXT.__objc_methlist: 0x21f4
+259.5.0.0.0
+  __TEXT.__text: 0x81e40
+  __TEXT.__objc_methlist: 0x226c
   __TEXT.__const: 0x1bcc
   __TEXT.__gcc_except_tab: 0x73c
-  __TEXT.__cstring: 0x325f
+  __TEXT.__cstring: 0x32af
   __TEXT.__ustring: 0x84
-  __TEXT.__oslogstring: 0x754e
+  __TEXT.__oslogstring: 0x772e
   __TEXT.__dlopen_cstrs: 0x47
   __TEXT.__swift5_typeref: 0x120d
   __TEXT.__swift5_reflstr: 0x4bc

   __TEXT.__swift_as_cont: 0xdc
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x2050
-  __TEXT.__eh_frame: 0x1f38
+  __TEXT.__unwind_info: 0x20a8
+  __TEXT.__eh_frame: 0x1f78
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2a8
+  __DATA_CONST.__const: 0x2b0
   __DATA_CONST.__objc_classlist: 0x150
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x128
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1d10
+  __DATA_CONST.__objc_selrefs: 0x1d60
   __DATA_CONST.__objc_protorefs: 0x68
   __DATA_CONST.__objc_superrefs: 0xf8
-  __DATA_CONST.__objc_arraydata: 0x50
+  __DATA_CONST.__objc_arraydata: 0x58
   __DATA_CONST.__got: 0x748
-  __AUTH_CONST.__const: 0x41a0
-  __AUTH_CONST.__cfstring: 0x1c80
-  __AUTH_CONST.__objc_const: 0x5670
+  __AUTH_CONST.__const: 0x4200
+  __AUTH_CONST.__cfstring: 0x1ce0
+  __AUTH_CONST.__objc_const: 0x5700
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0xe68
   __AUTH.__objc_data: 0x8b0
   __AUTH.__data: 0x138
-  __DATA.__objc_ivar: 0x2ec
+  __DATA.__objc_ivar: 0x2fc
   __DATA.__data: 0x1050
   __DATA.__bss: 0x1330
   __DATA_DIRTY.__objc_data: 0xb00

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 2891
-  Symbols:   3142
-  CStrings:  894
+  Functions: 2911
+  Symbols:   3172
+  CStrings:  906
 
Symbols:
+ -[CCImmediateSyncBudgetTracker _globalBudgetAllowsImmediateSyncAt:description:windowWasReset:]
+ -[CCImmediateSyncBudgetTracker shouldAllowImmediateSync]
+ -[CCSyncManager _finishDeviceAddedSync:]
+ -[CCSyncManager _handleCompanionLinkDeviceAddedWithCompletionHandler:]
+ -[CCSyncManager _isDeviceAddedSyncFeatureEnabled]
+ -[CCSyncManager _runDeviceAddedSync]
+ -[CCSyncManager _startDeviceAddedSync]
+ -[CCSyncManager deviceAddedSyncDebounceInterval]
+ -[CCSyncManager handleCompanionLinkDeviceAddedWithCompletionHandler:]
+ -[CCSyncManager setDeviceAddedSyncDebounceInterval:]
+ GCC_except_table58
+ _OBJC_IVAR_$_CCSyncManager._deviceAddedSyncCompletionHandlers
+ _OBJC_IVAR_$_CCSyncManager._deviceAddedSyncDebounceInterval
+ _OBJC_IVAR_$_CCSyncManager._deviceAddedSyncScheduled
+ _OBJC_IVAR_$_CCSyncManager._setChangeListenerQueue
+ ___36-[CCSyncManager _runDeviceAddedSync]_block_invoke
+ ___36-[CCSyncManager _runDeviceAddedSync]_block_invoke_2
+ ___38-[CCSyncManager _startDeviceAddedSync]_block_invoke
+ ___38-[CCSyncManager _startDeviceAddedSync]_block_invoke_2
+ ___69-[CCSyncManager handleCompanionLinkDeviceAddedWithCompletionHandler:]_block_invoke
+ ___70-[CCSyncManager _handleCompanionLinkDeviceAddedWithCompletionHandler:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48s_e5_v8?0l
+ ___block_descriptor_58_e8_32s40s48s_e5_v8?0l
+ _objc_msgSend$_finishDeviceAddedSync:
+ _objc_msgSend$_globalBudgetAllowsImmediateSyncAt:description:windowWasReset:
+ _objc_msgSend$_handleCompanionLinkDeviceAddedWithCompletionHandler:
+ _objc_msgSend$_isDeviceAddedSyncFeatureEnabled
+ _objc_msgSend$_runDeviceAddedSync
+ _objc_msgSend$_startDeviceAddedSync
+ _objc_msgSend$shouldAllowImmediateSync
+ _objc_msgSend$syncAllPersonasNowWithReason:activity:completionHandler:
- _OUTLINED_FUNCTION_205
CStrings:
+ "App.BlockedApp"
+ "DeviceAdded"
+ "Failed to record immediate sync budget, skipping sync on device added: %@"
+ "Ignoring Rapport device added: sync on device added is not enabled"
+ "Immediate sync budget denies sync on device added"
+ "Immediate sync budget tracker unavailable, skipping sync on device added: %@"
+ "Rapport device added, coalescing with pending sync"
+ "Rapport device added, scheduling sync in %.0fs"
+ "Sync on device added finished with %lu completed interaction(s), errors: %@"
+ "Triggering Rapport sync on device added"
+ "rapportSyncOnDeviceAdded"
+ "set-agnostic trigger"
```
