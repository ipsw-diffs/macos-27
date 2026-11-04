## AppSSO

> `/System/Library/PrivateFrameworks/AppSSO.framework/Versions/A/AppSSO`

```diff

-643.40.34.0.0
-  __TEXT.__text: 0x32394
-  __TEXT.__objc_methlist: 0x1cfc
-  __TEXT.__const: 0x160
-  __TEXT.__gcc_except_tab: 0x1bf4
-  __TEXT.__oslogstring: 0x565f
-  __TEXT.__cstring: 0x3acb
+643.60.12.0.0
+  __TEXT.__text: 0x3350c
+  __TEXT.__objc_methlist: 0x1d54
+  __TEXT.__const: 0x168
+  __TEXT.__gcc_except_tab: 0x1c40
+  __TEXT.__oslogstring: 0x57c5
+  __TEXT.__cstring: 0x3c24
   __TEXT.__dlopen_cstrs: 0x7b6
-  __TEXT.__unwind_info: 0x1500
+  __TEXT.__unwind_info: 0x1578
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0xc0
   __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1400
+  __DATA_CONST.__objc_selrefs: 0x1448
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x88
   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__got: 0x228
-  __AUTH_CONST.__const: 0x10d0
-  __AUTH_CONST.__cfstring: 0x1480
-  __AUTH_CONST.__objc_const: 0x49b8
+  __AUTH_CONST.__const: 0x1130
+  __AUTH_CONST.__cfstring: 0x1520
+  __AUTH_CONST.__objc_const: 0x4a08
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0xa0
-  __DATA.__objc_ivar: 0x180
+  __DATA.__objc_ivar: 0x188
   __DATA.__data: 0x730
   __DATA.__bss: 0x220
   __DATA_DIRTY.__objc_data: 0x6e0

   - /System/Library/PrivateFrameworks/ViewBridge.framework/Versions/A/ViewBridge
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1193
-  Symbols:   2085
-  CStrings:  793
+  Functions: 1214
+  Symbols:   2112
+  CStrings:  806
 
Symbols:
+ -[SOExtension _attachAuthorizationViewControllerWithCompletion:]
+ -[SOExtension _failRegisteredDelegatesWithMessage:]
+ -[SOExtension _resetFailedRequestIdentifiers]
+ -[SOExtension abandonRequestWithIdentifier:]
+ -[SOExtension attachAuthorizationViewControllerWithCompletion:]
+ -[SOExtension sessionSetupTimeout]
+ -[SOExtension setSessionSetupTimeout:]
+ GCC_except_table100
+ GCC_except_table102
+ GCC_except_table103
+ GCC_except_table104
+ GCC_except_table116
+ GCC_except_table80
+ _OBJC_IVAR_$_SOExtension._failedRequestIdentifiers
+ _OBJC_IVAR_$_SOExtension._sessionSetupTimeout
+ _OUTLINED_FUNCTION_16
+ ___63-[SOExtension attachAuthorizationViewControllerWithCompletion:]_block_invoke
+ ___64-[SOExtension _attachAuthorizationViewControllerWithCompletion:]_block_invoke
+ ___64-[SOExtension _attachAuthorizationViewControllerWithCompletion:]_block_invoke_2
+ ___64-[SOExtension _attachAuthorizationViewControllerWithCompletion:]_block_invoke_3
+ ___block_descriptor_40_e8_32bs_e5_v8?0l
+ ___block_descriptor_48_e8_32r40r_e5_B8?0l
+ ___block_descriptor_64_e8_32s40bs48bs56r_e28_v24?0"NSUUID"8"NSError"16l
+ ___block_descriptor_72_e8_32s40s48bs56bs64r_e17_v16?0"NSError"8l
+ ___copy_helper_block_e8_32r40r
+ ___copy_helper_block_e8_32s40b48b56r
+ ___copy_helper_block_e8_32s40s48b56b64r
+ ___destroy_helper_block_e8_32r40r
+ _objc_msgSend$_attachAuthorizationViewControllerWithCompletion:
+ _objc_msgSend$_failRegisteredDelegatesWithMessage:
+ _objc_msgSend$_resetFailedRequestIdentifiers
+ _objc_msgSend$removeAllObjects
+ _objc_msgSend$sessionSetupTimeout
+ _objc_msgSend$set
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
- GCC_except_table101
- GCC_except_table105
- GCC_except_table62
- GCC_except_table74
- GCC_except_table87
- ___block_descriptor_56_e8_32s40bs48r_e28_v24?0"NSUUID"8"NSError"16l
- ___block_descriptor_64_e8_32s40s48bs56r_e17_v16?0"NSError"8l
- ___copy_helper_block_e8_32s40b48r
- ___copy_helper_block_e8_32s40s48b56r
CStrings:
+ "-[SOExtension abandonRequestWithIdentifier:]"
+ "-[SOExtension attachAuthorizationViewControllerWithCompletion:]"
+ "B8@?0"
+ "No extension session to attach a view controller to"
+ "No remote extension context for the session"
+ "Timed out attaching a view controller for extension %{public}@"
+ "Timed out attaching a view controller to the existing session for extension %{public}@ -- failing the request"
+ "Timed out attaching a view controller to the extension session"
+ "Timed out setting up a session for extension %{public}@ -- failing the request"
+ "Timed out setting up the extension session"
+ "extension session unloaded"
+ "failing %lu registered delegate(s): %{public}@"
+ "request %{public}@ already completed -- nothing to abandon"
```
