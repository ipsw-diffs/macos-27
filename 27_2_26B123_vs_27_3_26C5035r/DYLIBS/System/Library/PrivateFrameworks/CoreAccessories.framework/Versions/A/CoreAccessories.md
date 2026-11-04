## CoreAccessories

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Versions/A/CoreAccessories`

```diff

-1219.40.10.0.0
-  __TEXT.__text: 0x28b18
-  __TEXT.__objc_methlist: 0x19d4
+1219.60.10.0.0
+  __TEXT.__text: 0x2c0cc
+  __TEXT.__objc_methlist: 0x1a54
   __TEXT.__const: 0x168
-  __TEXT.__cstring: 0x3d79
-  __TEXT.__oslogstring: 0x4021
-  __TEXT.__gcc_except_tab: 0x82c
+  __TEXT.__cstring: 0x4310
+  __TEXT.__oslogstring: 0x4186
+  __TEXT.__gcc_except_tab: 0x8b0
   __TEXT.__ustring: 0xa
-  __TEXT.__unwind_info: 0xd08
+  __TEXT.__unwind_info: 0xdf0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x17c0
+  __DATA_CONST.__const: 0x17d0
   __DATA_CONST.__objc_classlist: 0x50
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf68
+  __DATA_CONST.__objc_selrefs: 0xfa0
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x48
   __DATA_CONST.__objc_arraydata: 0xd8
-  __DATA_CONST.__got: 0x138
-  __AUTH_CONST.__const: 0x1510
-  __AUTH_CONST.__cfstring: 0x3b60
-  __AUTH_CONST.__objc_const: 0x2398
+  __DATA_CONST.__got: 0x148
+  __AUTH_CONST.__const: 0x1750
+  __AUTH_CONST.__cfstring: 0x3ba0
+  __AUTH_CONST.__objc_const: 0x23c0
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x0
   __DATA.__objc_ivar: 0xe0
   __DATA.__data: 0x760
-  __DATA.__bss: 0x120
+  __DATA.__bss: 0x128
   __DATA_DIRTY.__objc_data: 0x320
   __DATA_DIRTY.__data: 0x138
   __DATA_DIRTY.__bss: 0x68

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 850
-  Symbols:   2266
-  CStrings:  867
+  Functions: 900
+  Symbols:   2328
+  CStrings:  907
 
Symbols:
+ -[ACCHWComponentAuth displayAuthCloseSession:completionHandler:]
+ -[ACCHWComponentAuth displayAuthOpenSession:intermediateCertificate:key:completionHandler:]
+ -[ACCHWComponentAuth displayAuthRefreshAccessState:completionHandler:]
+ -[ACCHWComponentAuth displayAuthUserNVMRead:key:completionHandler:]
+ -[ACCHWComponentAuth displayAuthUserNVMWrite:key:value:completionHandler:]
+ GCC_except_table100
+ GCC_except_table86
+ GCC_except_table96
+ _OBJC_CLASS_$_NSError
+ ___64-[ACCHWComponentAuth displayAuthCloseSession:completionHandler:]_block_invoke
+ ___64-[ACCHWComponentAuth displayAuthCloseSession:completionHandler:]_block_invoke_2
+ ___67-[ACCHWComponentAuth displayAuthUserNVMRead:key:completionHandler:]_block_invoke
+ ___67-[ACCHWComponentAuth displayAuthUserNVMRead:key:completionHandler:]_block_invoke_2
+ ___70-[ACCHWComponentAuth displayAuthRefreshAccessState:completionHandler:]_block_invoke
+ ___70-[ACCHWComponentAuth displayAuthRefreshAccessState:completionHandler:]_block_invoke_2
+ ___74-[ACCHWComponentAuth displayAuthUserNVMWrite:key:value:completionHandler:]_block_invoke
+ ___74-[ACCHWComponentAuth displayAuthUserNVMWrite:key:value:completionHandler:]_block_invoke_2
+ ___91-[ACCHWComponentAuth displayAuthOpenSession:intermediateCertificate:key:completionHandler:]_block_invoke
+ ___91-[ACCHWComponentAuth displayAuthOpenSession:intermediateCertificate:key:completionHandler:]_block_invoke_2
+ ___block_descriptor_40_e8_32r_e17_v16?0"NSError"8l
+ ___block_descriptor_48_e8_32r40r_e21_v24?0^v8"NSError"16l
+ ___block_descriptor_48_e8_32r40r_e28_v24?0"NSData"8"NSError"16l
+ ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSError"8l
+ ___block_descriptor_48_e8_32s40bs_e23_v28?0Q8B16"NSError"20l
+ ___block_descriptor_48_e8_32s40bs_e28_v24?0"NSData"8"NSError"16l
+ ___block_descriptor_48_e8_32s40bs_e28_v24?0"NSUUID"8"NSError"16l
+ ___block_descriptor_56_e8_32r40r48r_e23_v28?0Q8B16"NSError"20l
+ ___block_descriptor_56_e8_32s40bs_e5_v8?0l
+ ___block_descriptor_58_e8_32s40bs_e5_v8?0l
+ ___block_descriptor_66_e8_32s40s48bs_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0l
+ ___copy_helper_block_e8_32r40r
+ ___copy_helper_block_e8_32r40r48r
+ ___copy_helper_block_e8_32s40s48s56s64b
+ ___destroy_helper_block_e8_32r40r
+ ___destroy_helper_block_e8_32r40r48r
+ ___destroy_helper_block_e8_32s40s48s56s64s
+ ___displayAuthCloseSession_block_invoke
+ ___displayAuthOpenSession_block_invoke
+ ___displayAuthRefreshAccessState_block_invoke
+ ___displayAuthUserNVMRead_block_invoke
+ ___displayAuthUserNVMWrite_block_invoke
+ _dispatch_semaphore_create
+ _dispatch_semaphore_signal
+ _dispatch_semaphore_wait
+ _dispatch_time
+ _displayAuthCloseSession
+ _displayAuthOpenSession
+ _displayAuthRefreshAccessState
+ _displayAuthUserNVMRead
+ _displayAuthUserNVMWrite
+ _kACCProperties_Endpoint_NFC_ShowEdgeCompensationAlert
+ _kCFACCProperties_Endpoint_NFC_ShowEdgeCompensationAlert
+ _objc_msgSend$displayAuthCloseSession:completionHandler:
+ _objc_msgSend$displayAuthOpenSession:intermediateCertificate:key:completionHandler:
+ _objc_msgSend$displayAuthOpenSession:intermediateCertificate:keyData:completionHandler:
+ _objc_msgSend$displayAuthRefreshAccessState:completionHandler:
+ _objc_msgSend$displayAuthUserNVMRead:key:completionHandler:
+ _objc_msgSend$displayAuthUserNVMWrite:key:value:completionHandler:
+ _objc_msgSend$errorWithDomain:code:userInfo:
+ _objc_msgSend$sharedManager
+ _systemInfo_isDeveloperBuild.developerBuild
CStrings:
+ "%s"
+ "%s: accessStateMask:%llu userNVMProtected:%d error:%@"
+ "%s: authError %@"
+ "%s: can't invoke remote object %@"
+ "%s: error:%@"
+ "%s: no completion handler"
+ "%s: sessionRef:%d authError %@"
+ "%s: sessionRef:%d error:%@"
+ "%s: timed out"
+ "%s: value:%@ error:%@"
+ "-[ACCHWComponentAuth displayAuthCloseSession:completionHandler:]"
+ "-[ACCHWComponentAuth displayAuthCloseSession:completionHandler:]_block_invoke"
+ "-[ACCHWComponentAuth displayAuthCloseSession:completionHandler:]_block_invoke_2"
+ "-[ACCHWComponentAuth displayAuthOpenSession:intermediateCertificate:key:completionHandler:]"
+ "-[ACCHWComponentAuth displayAuthOpenSession:intermediateCertificate:key:completionHandler:]_block_invoke"
+ "-[ACCHWComponentAuth displayAuthOpenSession:intermediateCertificate:key:completionHandler:]_block_invoke_2"
+ "-[ACCHWComponentAuth displayAuthRefreshAccessState:completionHandler:]"
+ "-[ACCHWComponentAuth displayAuthRefreshAccessState:completionHandler:]_block_invoke"
+ "-[ACCHWComponentAuth displayAuthUserNVMRead:key:completionHandler:]"
+ "-[ACCHWComponentAuth displayAuthUserNVMRead:key:completionHandler:]_block_invoke"
+ "-[ACCHWComponentAuth displayAuthUserNVMWrite:key:value:completionHandler:]"
+ "-[ACCHWComponentAuth displayAuthUserNVMWrite:key:value:completionHandler:]_block_invoke"
+ "ACCHWComponentAuth"
+ "NFC_ShowEdgeCompensationAlert"
+ "displayAuthCloseSession"
+ "displayAuthCloseSession_block_invoke"
+ "displayAuthOpenSession"
+ "displayAuthOpenSession_block_invoke"
+ "displayAuthRefreshAccessState"
+ "displayAuthRefreshAccessState authError %@"
+ "displayAuthRefreshAccessState_block_invoke"
+ "displayAuthUserNVMRead"
+ "displayAuthUserNVMRead authError %@"
+ "displayAuthUserNVMRead_block_invoke"
+ "displayAuthUserNVMWrite"
+ "displayAuthUserNVMWrite authError %@"
+ "displayAuthUserNVMWrite_block_invoke"
+ "v24@?0@\"NSUUID\"8@\"NSError\"16"
+ "v24@?0^v8@\"NSError\"16"
+ "v28@?0Q8B16@\"NSError\"20"
```
