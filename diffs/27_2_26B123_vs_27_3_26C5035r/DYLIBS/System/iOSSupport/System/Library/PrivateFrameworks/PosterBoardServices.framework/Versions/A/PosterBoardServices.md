## PosterBoardServices

> `/System/iOSSupport/System/Library/PrivateFrameworks/PosterBoardServices.framework/Versions/A/PosterBoardServices`

```diff

-355.2.12.100.0
-  __TEXT.__text: 0x7837c
-  __TEXT.__objc_methlist: 0x5078
+355.3.7.0.0
+  __TEXT.__text: 0x78df0
+  __TEXT.__objc_methlist: 0x50e0
   __TEXT.__const: 0xb28
-  __TEXT.__cstring: 0x6a2b
-  __TEXT.__gcc_except_tab: 0xfbc
-  __TEXT.__oslogstring: 0x37de
+  __TEXT.__cstring: 0x6a9b
+  __TEXT.__gcc_except_tab: 0x101c
+  __TEXT.__oslogstring: 0x388e
   __TEXT.__dlopen_cstrs: 0x2f6
   __TEXT.__swift5_typeref: 0x466
   __TEXT.__constg_swiftt: 0x1b0

   __TEXT.__swift5_types: 0x24
   __TEXT.__swift5_capture: 0x30
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x2470
+  __TEXT.__unwind_info: 0x2490
   __TEXT.__eh_frame: 0x590
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1ac0
+  __DATA_CONST.__const: 0x1af0
   __DATA_CONST.__objc_classlist: 0x2b8
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0xe8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2a48
+  __DATA_CONST.__objc_selrefs: 0x2a88
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x230
   __DATA_CONST.__got: 0x6e8
   __AUTH_CONST.__const: 0x748
-  __AUTH_CONST.__cfstring: 0x4ca0
-  __AUTH_CONST.__objc_const: 0x106d8
+  __AUTH_CONST.__cfstring: 0x4d40
+  __AUTH_CONST.__objc_const: 0x10748
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0xc28
   __AUTH.__objc_data: 0x1200
   __AUTH.__data: 0x118
-  __DATA.__objc_ivar: 0x5cc
+  __DATA.__objc_ivar: 0x5d4
   __DATA.__data: 0xc20
   __DATA.__bss: 0xcc0
   __DATA.__common: 0x58

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2616
-  Symbols:   4801
-  CStrings:  1082
+  Functions: 2631
+  Symbols:   4821
+  CStrings:  1089
 
Symbols:
+ +[PRSHostConfigurationEntry entryWithExtensionID:descriptorID:posterUUID:userInfo:migratedConfigurationMatchingMask:]
+ +[PRSHostConfigurationEntry entryWithExtensionID:descriptorID:userInfo:]
+ +[PRSHostConfigurationEntry supportedUserInfoValueClasses]
+ +[PRSPosterUpdate posterUpdateColumnComplications:]
+ -[PRSHostConfigurationEntry initWithExtensionID:descriptorID:posterUUID:userInfo:migratedConfigurationMatchingMask:]
+ -[PRSHostConfigurationEntry initWithExtensionID:descriptorID:userInfo:]
+ -[PRSHostConfigurationEntry setUserInfo:]
+ -[PRSHostConfigurationEntry userInfo]
+ -[PRSMigrationDescriptor setSimulatesCrossDeviceRestore:]
+ -[PRSMigrationDescriptor simulatesCrossDeviceRestore]
+ -[PRSService _deleteDataStoreTerminating:completion:]
+ _OBJC_IVAR_$_PRSHostConfigurationEntry._userInfo
+ _OBJC_IVAR_$_PRSMigrationDescriptor._simulatesCrossDeviceRestore
+ _OUTLINED_FUNCTION_20
+ ___53-[PRSService _deleteDataStoreTerminating:completion:]_block_invoke
+ ___73-[PRSServer fetchAssociatedHomeScreenPosterConfigurationUUID:completion:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48bs_e40_v24?0"PFServerPosterPath"8"NSError"16ls32l8s48l8s40l8
+ ___block_descriptor_65_e8_32s40s48bs_e17_v16?0"NSError"8ls32l8s40l8s48l8
+ _objc_msgSend$_deleteDataStoreTerminating:completion:
+ _objc_msgSend$initWithExtensionID:descriptorID:posterUUID:userInfo:migratedConfigurationMatchingMask:
+ _objc_msgSend$initWithExtensionID:descriptorID:userInfo:
+ _objc_msgSend$setSimulatesCrossDeviceRestore:
+ _objc_msgSend$setUserInfo:
+ _objc_msgSend$simulatesCrossDeviceRestore
+ _objc_msgSend$supportedUserInfoValueClasses
- +[PRSHostConfigurationEntry entryWithExtensionID:descriptorID:posterUUID:migratedConfigurationMatchingMask:]
- -[PRSHostConfigurationEntry initWithExtensionID:descriptorID:posterUUID:migratedConfigurationMatchingMask:]
- ___44-[PRSService deleteDataStoreWithCompletion:]_block_invoke
- ___block_descriptor_64_e8_32s40s48bs_e17_v16?0"NSError"8ls32l8s40l8s48l8
- _objc_msgSend$initWithExtensionID:descriptorID:posterUUID:migratedConfigurationMatchingMask:
CStrings:
+ "Data store is being deleted by process %@ (terminate: %{BOOL}u)"
+ "PRSHostContext init: skipping screen %lu (main=%{BOOL}d) — no valid orientation"
+ "PRSHostContext init: use active display (%{public}@) instead of main display (%{public}@)"
+ "PRSPosterUpdateTypeComplicationColumn"
+ "_simulatesCrossDeviceRestore"
+ "activationState"
+ "fetching poster did error in %@ : error=%@ posterUUID=%@"
+ "simulatesCrossDeviceRestore"
+ "userInfo"
- "Data store is being deleted by process %@"
- "PRSHostContext init: skipping screen %lu — no valid orientation"
```
