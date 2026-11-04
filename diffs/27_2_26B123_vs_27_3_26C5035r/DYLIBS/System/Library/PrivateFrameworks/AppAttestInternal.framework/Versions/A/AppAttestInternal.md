## AppAttestInternal

> `/System/Library/PrivateFrameworks/AppAttestInternal.framework/Versions/A/AppAttestInternal`

```diff

-158.0.0.0.0
-  __TEXT.__text: 0x6a5a4
-  __TEXT.__objc_methlist: 0x6c4
+162.1.0.0.0
+  __TEXT.__text: 0x6a734
+  __TEXT.__objc_methlist: 0x6cc
   __TEXT.__const: 0x4490
-  __TEXT.__cstring: 0x6a8e
-  __TEXT.__oslogstring: 0x34aa
+  __TEXT.__cstring: 0x6a9e
+  __TEXT.__oslogstring: 0x34ea
   __TEXT.__gcc_except_tab: 0x6b8
   __TEXT.__swift5_typeref: 0xb5a
   __TEXT.__swift5_reflstr: 0x125d

   __TEXT.__swift5_mpenum: 0x18
   __TEXT.__swift5_capture: 0x250
   __TEXT.__swift_as_ret: 0x10
-  __TEXT.__unwind_info: 0x1418
+  __TEXT.__unwind_info: 0x1420
   __TEXT.__eh_frame: 0x1070
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_classlist: 0xe0
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x698
+  __DATA_CONST.__objc_selrefs: 0x6a0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x48
   __DATA_CONST.__objc_arraydata: 0xf8

   __AUTH.__data: 0x2e0
   __DATA.__objc_ivar: 0x40
   __DATA.__data: 0x4a8
-  __DATA.__bss: 0x3750
+  __DATA.__bss: 0x3760
   __DATA.__common: 0x30
   __DATA_DIRTY.__objc_data: 0x838
   __DATA_DIRTY.__data: 0xc10

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1477
-  Symbols:   1300
-  CStrings:  822
+  Functions: 1479
+  Symbols:   1303
+  CStrings:  824
 
Symbols:
+ +[FeatureFlagsManager isKeyRotationEnabled]
+ ___43+[FeatureFlagsManager isKeyRotationEnabled]_block_invoke
+ _isKeyRotationEnabled.onceToken
CStrings:
+ "%25s:%-5d DeviceCheck Key Rotation feature flag enabled { enabled=%d }."
+ "AppAttest (%@-162.1) - %@"
+ "keyRotation"
- "AppAttest (%@-158) - %@"
```
