## PrivateMLClientInferenceProvider

> `/System/Library/PrivateFrameworks/PrivateMLClientInferenceProvider.framework/Versions/A/PrivateMLClientInferenceProvider`

```diff

-218.13.3.0.1
-  __TEXT.__text: 0x9d0b0
-  __TEXT.__const: 0x2024
+218.13.7.0.0
+  __TEXT.__text: 0x9d934
+  __TEXT.__const: 0x2044
   __TEXT.__constg_swiftt: 0x68c
-  __TEXT.__swift5_typeref: 0xc23
+  __TEXT.__swift5_typeref: 0xc39
   __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift5_mpenum: 0x18
   __TEXT.__swift5_reflstr: 0xc1c
   __TEXT.__swift5_fieldmd: 0x938
   __TEXT.__swift5_proto: 0xfc
   __TEXT.__swift5_types: 0x78
-  __TEXT.__cstring: 0xf27
-  __TEXT.__oslogstring: 0x4029
+  __TEXT.__cstring: 0xf57
+  __TEXT.__oslogstring: 0x40b9
   __TEXT.__swift5_protos: 0x8
   __TEXT.__swift5_assocty: 0x138
   __TEXT.__swift_as_entry: 0x108
   __TEXT.__swift_as_ret: 0x128
   __TEXT.__swift_as_cont: 0x274
   __TEXT.__swift5_capture: 0x764
-  __TEXT.__unwind_info: 0x11b8
-  __TEXT.__eh_frame: 0x3010
+  __TEXT.__unwind_info: 0x11c0
+  __TEXT.__eh_frame: 0x3020
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x19e1
   __AUTH_CONST.__objc_const: 0x720
-  __AUTH_CONST.__auth_got: 0x1c58
+  __AUTH_CONST.__auth_got: 0x1ca0
   __AUTH.__objc_data: 0xf0
   __AUTH.__data: 0x578
-  __DATA.__data: 0x590
+  __DATA.__data: 0x5a8
   __DATA.__bss: 0x1700
   __DATA.__common: 0x8
   __DATA_DIRTY.__objc_data: 0x50

   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/Network.framework/Versions/A/Network
+  - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/PrivateFrameworks/AppleIntelligenceReporting.framework/Versions/A/AppleIntelligenceReporting
   - /System/Library/PrivateFrameworks/CloudTelemetry.framework/Versions/A/CloudTelemetry
   - /System/Library/PrivateFrameworks/GenerativeFunctionsFoundation.framework/Versions/A/GenerativeFunctionsFoundation

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1052
-  Symbols:   526
-  CStrings:  397
+  Functions: 1053
+  Symbols:   531
+  CStrings:  400
 
Symbols:
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateWithAuditToken
+ _symbolic _____Sg 15PrivateMLClient15RateLimitStatusV18PrivilegedMetadataV
+ _symbolic _____Sg 15TokenGeneration30CurrentRateLimitStatusResponseV18PrivilegedMetadataV
+ _symbolic yXlSg
CStrings:
+ "PCC usage entitlement check: no audit token or SecTask"
+ "PCC usage entitlement check: pid=%d value=%{public}s entitled=%{bool}d"
+ "com.apple.privatecloudcompute.usage"
```
