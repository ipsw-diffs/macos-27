## libGPUCompilerImplLazy.dylib

> `/System/Library/PrivateFrameworks/GPUCompiler.framework/Versions/Current/Libraries/libGPUCompilerImplLazy.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__AUTH.__thread_vars`
- `__DATA_DIRTY.__data`

```diff

 32023.921.5.0.0
-  __TEXT.__text: 0x1163a7c
+  __TEXT.__text: 0x11402d8
   __TEXT.__init_offsets: 0x14
-  __TEXT.__const: 0xd6020
-  __TEXT.__cstring: 0x13a4c5
-  __TEXT.__unwind_info: 0x18be0
-  __TEXT.__auth_stubs: 0x6cc0
-  __DATA_CONST.__const: 0x192f18
+  __TEXT.__const: 0xd6470
+  __TEXT.__cstring: 0x13a8b1
+  __TEXT.__unwind_info: 0x222e0
+  __TEXT.__auth_stubs: 0x6ce0
+  __DATA_CONST.__const: 0x193140
   __DATA_CONST.__weak_got: 0x8
   __DATA_CONST.__got: 0x1f8
-  __AUTH_CONST.__const: 0xf4a20
+  __AUTH_CONST.__const: 0xf4bb8
   __AUTH_CONST.__weak_auth_got: 0xb8
-  __AUTH_CONST.__auth_got: 0x35a8
-  __AUTH.__data: 0x4b40
+  __AUTH_CONST.__auth_got: 0x35b8
+  __AUTH.__data: 0x4bd0
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x8
-  __DATA.__data: 0x1728
+  __DATA.__data: 0x1740
   __DATA.__bss: 0x58
   __DATA.__common: 0x20
   __DATA_DIRTY.__data: 0x10f0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libarchive.2.dylib
   - /usr/lib/libc++.1.dylib
-  Functions: 38025
-  Symbols:   1843
-  CStrings:  56844
+  Functions: 38074
+  Symbols:   1845
+  CStrings:  56882
 
Symbols:
+ __ZN4llvm3air12AIPersistent7getImplERNS_11LLVMContextEbNS_8Metadata11StorageTypeEb
+ __ZN4llvm3air16AIKernelFunction7getImplERNS_11LLVMContextEPNS_8FunctionENS_24MDTupleTypedArrayWrapperINS0_12AIReturnTypeEEENS6_INS0_10AIArgumentEEEPNS0_13AIVecTypeHintEPNS0_15AIWorkgroupSizeEPNS0_19AIWorkgroupSizeHintEPNS0_18AIWorkgroupMaxSizeEPNS0_16AIUserAnnotationEPNS0_12AIPersistentEPNS0_22AIForwardProgressUsageENS_8Metadata11StorageTypeEb
+ __ZN4llvm3air22AIForwardProgressUsage7getImplERNS_11LLVMContextENS0_26AIForwardProgressUsageKindENS_8Metadata11StorageTypeEb
- __ZN4llvm3air16AIKernelFunction7getImplERNS_11LLVMContextEPNS_8FunctionENS_24MDTupleTypedArrayWrapperINS0_12AIReturnTypeEEENS6_INS0_10AIArgumentEEEPNS0_13AIVecTypeHintEPNS0_15AIWorkgroupSizeEPNS0_19AIWorkgroupSizeHintEPNS0_18AIWorkgroupMaxSizeEPNS0_16AIUserAnnotationENS_8Metadata11StorageTypeEb
CStrings:
+ " Automatic"
+ " SIMDGroupParallel"
+ " Weak"
+ " [[forward_progress_usage"
+ " [[gnu::contention_relief"
+ " [[persistent"
+ " __attribute__((contention_relief"
+ "#pragma METAL contention_relief"
+ "'default', 'automatic' or 'none'"
+ "ContentionReliefKind"
+ "METAL contention_relief"
+ "METAL::contention_relief"
+ "Metal: support for contention relief"
+ "Metal: support for the forward progress usage attribute"
+ "Metal: support for the persistent attribute"
+ "MetalContentionRelief"
+ "MetalContentionReliefAttr"
+ "MetalForwardProgressUsage"
+ "MetalForwardProgressUsageAttr"
+ "MetalPersistent"
+ "MetalPersistentAttr"
+ "Usage"
+ "__metal_atomic_notify_all_simdgroup"
+ "__metal_atomic_notify_one_simdgroup"
+ "__metal_atomic_wait_explicit_simdgroup"
+ "__metal_atomic_wait_with_predicate_explicit_simdgroup"
+ "__metal_critical_section"
+ "__metal_yield_simdgroup"
+ "annot_pragma_metal_contention_relief"
+ "contention-relief"
+ "contention_relief"
+ "forward_progress_usage"
+ "gnu::contention_relief"
+ "persistent"
+ "simdgroup_parallel"
+ "uuuuiii"
+ "vu"
+ "vuuuu"
```
