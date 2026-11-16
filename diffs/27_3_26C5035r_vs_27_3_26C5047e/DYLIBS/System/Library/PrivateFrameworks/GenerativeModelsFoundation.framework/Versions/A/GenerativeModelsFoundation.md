## GenerativeModelsFoundation

> `/System/Library/PrivateFrameworks/GenerativeModelsFoundation.framework/Versions/A/GenerativeModelsFoundation`

```diff

-297.15.7.0.0
-  __TEXT.__text: 0x5e884
-  __TEXT.__objc_methlist: 0x254
-  __TEXT.__const: 0xbf10
-  __TEXT.__cstring: 0x1435
-  __TEXT.__swift5_typeref: 0x2924
-  __TEXT.__oslogstring: 0x1003
-  __TEXT.__swift5_reflstr: 0x14f3
-  __TEXT.__swift5_assocty: 0x228
-  __TEXT.__swift5_fieldmd: 0x23d4
-  __TEXT.__constg_swiftt: 0x2360
+297.15.13.0.0
+  __TEXT.__text: 0x72fc0
+  __TEXT.__objc_methlist: 0x25c
+  __TEXT.__const: 0xc990
+  __TEXT.__cstring: 0x1665
+  __TEXT.__swift5_typeref: 0x2e0a
+  __TEXT.__oslogstring: 0x14f3
+  __TEXT.__swift5_reflstr: 0x1613
+  __TEXT.__swift5_assocty: 0x240
+  __TEXT.__swift5_fieldmd: 0x2648
+  __TEXT.__constg_swiftt: 0x25ac
   __TEXT.__swift5_builtin: 0x8c
-  __TEXT.__swift5_capture: 0x380
-  __TEXT.__swift5_proto: 0xab8
-  __TEXT.__swift5_types: 0x354
-  __TEXT.__swift_as_entry: 0x9c
-  __TEXT.__swift_as_ret: 0x7c
-  __TEXT.__swift_as_cont: 0x144
-  __TEXT.__swift5_protos: 0x34
+  __TEXT.__swift5_capture: 0x490
+  __TEXT.__swift5_proto: 0xb3c
+  __TEXT.__swift5_types: 0x390
+  __TEXT.__swift_as_entry: 0xb8
+  __TEXT.__swift_as_ret: 0x9c
+  __TEXT.__swift_as_cont: 0x18c
+  __TEXT.__swift5_protos: 0x38
   __TEXT.__swift5_mpenum: 0x20
-  __TEXT.__unwind_info: 0x33e0
-  __TEXT.__eh_frame: 0x33e8
+  __TEXT.__unwind_info: 0x39b8
+  __TEXT.__eh_frame: 0x3dc8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x148
-  __DATA_CONST.__objc_classlist: 0xa0
+  __DATA_CONST.__objc_classlist: 0xa8
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x148
+  __DATA_CONST.__objc_selrefs: 0x150
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x6630
-  __AUTH_CONST.__objc_const: 0x1048
-  __AUTH_CONST.__auth_got: 0xd60
+  __AUTH_CONST.__const: 0x6f18
+  __AUTH_CONST.__objc_const: 0x1148
+  __AUTH_CONST.__auth_got: 0xf88
   __AUTH.__objc_data: 0x1d8
-  __AUTH.__data: 0x9c8
-  __DATA.__data: 0x1ef0
-  __DATA.__bss: 0x12d80
-  __DATA.__common: 0x10
+  __AUTH.__data: 0xbe8
+  __DATA.__data: 0x2230
+  __DATA.__bss: 0x13d80
+  __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x68
-  __DATA_DIRTY.__data: 0x14c0
+  __DATA_DIRTY.__data: 0x1570
   __DATA_DIRTY.__bss: 0x2580
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/PrivateFrameworks/CollectionsInternal.framework/Versions/A/CollectionsInternal
+  - /System/Library/PrivateFrameworks/CoreTime.framework/Versions/A/CoreTime
   - /System/Library/PrivateFrameworks/GenerativeAgents.framework/Versions/A/GenerativeAgents
   - /System/Library/PrivateFrameworks/GenerativeFunctions.framework/Versions/A/GenerativeFunctions
   - /System/Library/PrivateFrameworks/GenerativeFunctionsFoundation.framework/Versions/A/GenerativeFunctionsFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4436
-  Symbols:   206
-  CStrings:  187
+  Functions: 4923
+  Symbols:   214
+  CStrings:  222
 
Symbols:
+ _TMGetReferenceTime
+ _clock_gettime_nsec_np
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_release_n
+ _swift_retain_n
+ _swift_stdlib_random
+ _sysctlbyname
CStrings:
+ "%{sensitive}s"
+ ", enablement time: "
+ "AvailabilityFoundationClient.updateVersionGatingRules(_:)"
+ "Boot session reference dates: %s"
+ "Could not query os_eligibility for additional criteria, falling back to Model Catalog"
+ "FailureTracking(blockedUseCases): Use case identifier "
+ "FailureTracking(blockedUseCases:) blocked use case:"
+ "FailureTracking(track:): Not in china mode. Will not track failure for %s"
+ "FailureTracking(track:): Use case identifier "
+ "FailureTracking.SecureStorage.failures: PropertyListDecoder().decode error: %@"
+ "FailureTracking.SecureStorage.failures: data = value as? Data is nil"
+ "FailureTracking.SecureStorage.failures: keyValueStore.object(forKey: Self.failuresKey) is null for .nobody. Returning []."
+ "FailureTracking.SecureStorage.failures: keyValueStore.object(forKey: Self.failuresKey) is null for current user. Falling back to nobody."
+ "FailureTracking._blockedUseCases(failureRecords:) called"
+ "FailureTracking._blockedUseCases(failureRecords:) finished running"
+ "InternalVariantArguments: Could not determine isChinaMode. Defaulting to false. Error: %@"
+ "InternalVariantArguments: isMainlandChina resolved to %{bool}d"
+ "Setting current boot session info"
+ "Should consider secure walltime: %{bool}d"
+ "Start date in consideration: %s"
+ "adjust trusted wall time to user wall time, offset: %f"
+ "bootMonotonicTimestamp"
+ "chinaRegion"
+ "com.apple.snowflake"
+ "disabled"
+ "failed to convert to UseCaseIdentifier %s"
+ "group.summarizationSummarizeMailMessage"
+ "group.textCompositionMailReply"
+ "group.textCompositionMessages"
+ "group.writingTools"
+ "kern.bootsessionuuid"
+ "maxOSVersion"
+ "minOSVersion"
+ "resources"
+ "updateVersionGatingRules error: %@"
```
