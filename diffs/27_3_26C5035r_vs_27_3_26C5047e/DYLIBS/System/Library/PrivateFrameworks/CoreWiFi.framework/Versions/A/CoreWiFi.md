## CoreWiFi

> `/System/Library/PrivateFrameworks/CoreWiFi.framework/Versions/A/CoreWiFi`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`

```diff

-1046.2.0.0.0
-  __TEXT.__text: 0x4644bc
+1046.3.0.0.0
+  __TEXT.__text: 0x464a08
   __TEXT.__objc_methlist: 0x12a98
   __TEXT.__const: 0x9bf8
-  __TEXT.__cstring: 0x2bebe
+  __TEXT.__cstring: 0x2bede
   __TEXT.__oslogstring: 0x20d6c
   __TEXT.__gcc_except_tab: 0x160c8
   __TEXT.__dlopen_cstrs: 0x9cc

   __TEXT.__swift5_types: 0x1bc
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_capture: 0x1e0
-  __TEXT.__unwind_info: 0xc368
+  __TEXT.__unwind_info: 0xc370
   __TEXT.__eh_frame: 0x1278
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 11221
-  Symbols:   22770
-  CStrings:  6880
+  Functions: 11222
+  Symbols:   22771
+  CStrings:  6882
 
Symbols:
+ ___CWFColocatedScanPass
+ ___os_log_helper_16_2_8_8_34_8_34_4_0_8_0_8_34_8_0_8_0_8_64
- ___os_log_helper_16_2_7_8_34_8_34_4_0_8_0_8_0_8_0_8_64
CStrings:
+ "DFS "
+ "[corewifi] %{public}s (%{public}s:%u) Colocated consent scanned %lu %{public}schannel(s) in %llums, %lu result(s): %@"
+ "__CWFColocatedScanPass"
- "[corewifi] %{public}s (%{public}s:%u) Colocated consent scanned %lu channel(s) in %llums, %lu result(s): %@"
```
