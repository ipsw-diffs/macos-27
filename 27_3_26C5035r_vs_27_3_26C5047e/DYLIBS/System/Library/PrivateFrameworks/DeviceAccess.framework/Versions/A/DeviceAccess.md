## DeviceAccess

> `/System/Library/PrivateFrameworks/DeviceAccess.framework/Versions/A/DeviceAccess`

```diff

-2702.5.0.0.0
-  __TEXT.__text: 0x5aa3c
-  __TEXT.__objc_methlist: 0x4a1c
-  __TEXT.__const: 0xaf8
-  __TEXT.__cstring: 0xa913
+2702.8.0.0.0
+  __TEXT.__text: 0x5c770
+  __TEXT.__objc_methlist: 0x4ad4
+  __TEXT.__const: 0xbf8
+  __TEXT.__cstring: 0xaaf3
   __TEXT.__gcc_except_tab: 0x1358
   __TEXT.__constg_swiftt: 0x3b8
   __TEXT.__swift5_typeref: 0x25a

   __TEXT.__swift5_proto: 0x14
   __TEXT.__swift5_protos: 0x8
   __TEXT.__swift5_capture: 0x1c
-  __TEXT.__unwind_info: 0x1ba0
+  __TEXT.__unwind_info: 0x1bd8
   __TEXT.__eh_frame: 0x4d0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x20f8
+  __DATA_CONST.__objc_selrefs: 0x2170
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x198
   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__got: 0x528
-  __AUTH_CONST.__const: 0x13f0
-  __AUTH_CONST.__cfstring: 0x3880
-  __AUTH_CONST.__objc_const: 0x8698
+  __AUTH_CONST.__const: 0x14b0
+  __AUTH_CONST.__cfstring: 0x3960
+  __AUTH_CONST.__objc_const: 0x8768
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_intobj: 0x90
   __AUTH_CONST.__auth_got: 0xa88
   __AUTH.__objc_data: 0x138
   __AUTH.__data: 0x90
-  __DATA.__objc_ivar: 0x774
+  __DATA.__objc_ivar: 0x784
   __DATA.__data: 0xc68
   __DATA.__bss: 0x2f0
   __DATA.__common: 0x8

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2434
-  Symbols:   4057
-  CStrings:  1576
+  Functions: 2458
+  Symbols:   4097
+  CStrings:  1592
 
Symbols:
+ +[DADevice appServicesFromArchive:]
+ +[DADevice normalizedPersistentServices:]
+ +[DADevice persistentServiceInfos:deviceID:perApp:authorizations:]
+ -[DADevice accessoryServicesMapForBundleID:]
+ -[DADevice appServicesInternalMap]
+ -[DADevice appServicesMap]
+ -[DADevice encodeAppServices]
+ -[DADevice loadPersistentServices:authorizations:]
+ -[DADevice scopedToBundleID:]
+ -[DADevice setAppServicesInternalMap:]
+ -[DADevice setEncodeAppServices:]
+ -[DAEventExtension bundleID]
+ -[DAEventExtension setBundleID:]
+ -[DAExtensionCapability _terminateLaunchedProcess]
+ -[DAExtensionCapability invalidateRequested]
+ -[DAExtensionCapability setInvalidateRequested:]
+ GCC_except_table100
+ GCC_except_table113
+ GCC_except_table21
+ GCC_except_table45
+ GCC_except_table56
+ GCC_except_table69
+ _OBJC_IVAR_$_DADevice._appServicesInternalMap
+ _OBJC_IVAR_$_DADevice._encodeAppServices
+ _OBJC_IVAR_$_DAEventExtension._bundleID
+ _OBJC_IVAR_$_DAExtensionCapability._invalidateRequested
+ ___25-[DADevice copyWithZone:]_block_invoke
+ ___41+[DADevice normalizedPersistentServices:]_block_invoke
+ ___50-[DADevice loadPersistentServices:authorizations:]_block_invoke
+ ___block_descriptor_40_e8_32s_e39_v32?0"NSString"8"NSDictionary"16^B24l
+ ___block_descriptor_40_e8_32s_e46_v32?0"NSString"8"NSMutableDictionary"16^B24l
+ ___block_descriptor_52_e8_32r40r_e46_v32?0"NSString"8"NSMutableDictionary"16^B24l
+ ___block_descriptor_56_e8_32s40s48s_e39_v32?0"NSString"8"NSDictionary"16^B24l
+ _objc_msgSend$_terminateLaunchedProcess
+ _objc_msgSend$accessoryServicesMapForBundleID:
+ _objc_msgSend$addEntriesFromDictionary:
+ _objc_msgSend$appServicesFromArchive:
+ _objc_msgSend$initWithPersistentDictionaryRepresentation:deviceID:error:
+ _objc_msgSend$invalidateRequested
+ _objc_msgSend$normalizedPersistentServices:
+ _objc_msgSend$persistentServiceInfos:deviceID:perApp:authorizations:
+ _objc_msgSend$setAccessoryServicesInternalMap:
+ _objc_msgSend$setAppAccessInfoDeviceMap:
+ _objc_msgSend$setAppServicesInternalMap:
+ _objc_msgSend$setAuthorizationLevel:
+ _objc_msgSend$setInvalidateRequested:
- GCC_except_table110
- GCC_except_table17
- GCC_except_table44
- GCC_except_table55
- GCC_except_table97
- _objc_msgSend$accessoryServicesInternalMap
CStrings:
+ "### Failed to terminate PID %d: %@"
+ "+[DADevice persistentServiceInfos:deviceID:perApp:authorizations:]"
+ "-[DAExtensionCapability _terminateLaunchedProcess]"
+ "AppExtensionGeneralWorker"
+ "CapabilityInfoMap: no accessory services found for '%@' on %@"
+ "DAErrorCodeTaskInterrupted"
+ "DAErrorCodeTaskRejected"
+ "Invalidated while launching"
+ "Invalidated while launching, %s PID %d: %@"
+ "[ServiceInfo Decoding Error] %@"
+ "appServices"
+ "dApS"
+ "not starting"
+ "services"
+ "terminating"
+ "v32@?0@\"NSString\"8@\"NSDictionary\"16^B24"
+ "v32@?0@\"NSString\"8@\"NSMutableDictionary\"16^B24"
- "CapabilityInfoMap: no accessory services found for %@"
```
