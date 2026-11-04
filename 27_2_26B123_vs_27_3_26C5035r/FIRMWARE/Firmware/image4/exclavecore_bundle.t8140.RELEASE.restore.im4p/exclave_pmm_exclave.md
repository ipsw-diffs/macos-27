## exclave_pmm_exclave

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_pmm_exclave`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_fixups`
- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA.__shared_cache`
- `__DATA.__mod_init_func`

```diff

-1490.40.28.0.0
-  __TEXT.__text: 0x4d294
+1490.60.7.0.0
+  __TEXT.__text: 0x4d3d4
   __TEXT.__const: 0x1d140
-  __TEXT.__cstring: 0x12568
+  __TEXT.__cstring: 0x125f2
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x60
   __TEXT.__eh_frame: 0x48
-  __DATA.__const: 0x14a0
+  __DATA.__const: 0x14d8
   __DATA.__data: 0x2421
-  __DATA.__auth_ptr: 0x30
+  __DATA.__auth_ptr: 0x28
   __DATA.__ENDPOINTS: 0x93f
   __DATA.__shared_cache: 0x70
   __DATA.__mod_init_func: 0x18

   __PDATA.__shared_cache: 0x0
   Functions: 1214
   Symbols:   4
-  CStrings:  1529
+  CStrings:  1536
 
Functions:
~ sub_7ffe5c4 : 1124 -> 1276
~ sub_7ffea28 -> sub_7ffeac0 : 504 -> 328
~ sub_7ffec20 -> sub_7ffec08 : 276 -> 248
~ sub_8000bdc -> sub_8000ba8 : 184 -> 192
~ sub_8000c94 -> sub_8000c68 : 536 -> 608
~ sub_8000ee8 -> sub_8000f04 : 676 -> 972
~ sub_800df90 -> sub_800e0d4 : 668 -> 672
~ sub_8020848 -> sub_8020990 : 3076 -> 3084
~ sub_8036958 -> sub_8036aa8 : 272 -> 256
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveCore.MacOSX.platform/Developer/SDKs/ExclaveCore.MacOSX27.3.Internal.sdk/System/ExclaveCore/System/Library/Frameworks/xrt.framework/Headers/thread.h"
+ "bundle_size_kib"
+ "carveout_permanent_kib"
+ "carveout_reclaimable_kib"
+ "carveout_total_kib"
+ "cl4_allocations_kib"
+ "ipmm_usage_kib"
+ "unknown_global_stat"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveCore.MacOSX.platform/Developer/SDKs/ExclaveCore.MacOSX27.2.Internal.sdk/System/ExclaveCore/System/Library/Frameworks/xrt.framework/Headers/thread.h"
```
