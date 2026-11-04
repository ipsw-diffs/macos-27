## dyld

> `/usr/lib/dyld`

```diff

-27104.0.0.0.0
-  __TEXT.__text: 0xa136c
-  __TEXT.__const: 0x1a68
-  __TEXT.__cstring: 0x13950
-  __TEXT.__unwind_info: 0x3590
+27200.1.0.0.0
+  __TEXT.__text: 0xa1a5c
+  __TEXT.__const: 0x1a98
+  __TEXT.__cstring: 0x139b5
+  __TEXT.__unwind_info: 0x35b0
   __DATA_CONST.__const: 0x2bd0
-  __AUTH_CONST.__const: 0x6348
+  __AUTH_CONST.__const: 0x63a8
   __DATA.__data: 0x1c0
   __DATA.__crash_info: 0x148
   __DATA.__common: 0x8f0

   __DATA_DIRTY.__bss: 0x48
   __TPRO_CONST.__data: 0xe1
   __TPRO_CONST.__allocator: 0x20000
-  Functions: 3376
-  Symbols:   3408
-  CStrings:  2381
+  Functions: 3383
+  Symbols:   3413
+  CStrings:  2383
 
Symbols:
+ __ZN5dyld35ArrayIN5dyld417InterposeTupleAllEE9push_backERKS2_
+ __ZNK15DyldSharedCache12inTPRORegionEPKv
+ __ZNK15DyldSharedCache17forEachTPRORegionEU13block_pointerFvPKvyyRbE
+ __ZNK5dyld46Loader6headerERKNS_12RuntimeStateE
+ ____ZNK15DyldSharedCache12inTPRORegionEPKv_block_invoke
CStrings:
+ "  cache dylib rooted, so also interposed cache binds to 0x%08lX with 0x%08lX\n"
+ "27200.1"
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Wed Oct 28 21:34:12 PDT 2026; root:libignition-64~30353/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Wed Oct 28 21:34:12 PDT 2026; root:libignition-64~30353/libignition_core/RELEASE_ARM64E"
+ "v40@?0r^v8Q16Q24^B32"
- "27104"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Sat Oct 10 00:30:20 PDT 2026; root:libignition-64~29901/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Sat Oct 10 00:30:20 PDT 2026; root:libignition-64~29901/libignition_core/RELEASE_ARM64E"
```
