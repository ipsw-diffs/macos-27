## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-1572.3.0.0.0
-  __TEXT.__text: 0x287b4c
+1572.4.0.0.0
+  __TEXT.__text: 0x287b98
   __TEXT.__auth_stubs: 0x25b0
   __TEXT.__init_offsets: 0x1c0
   __TEXT.__cstring: 0x82dc9
   __TEXT.__const: 0x3d858
-  __TEXT.__unwind_info: 0xa458
+  __TEXT.__unwind_info: 0xa460
   __TEXT.__eh_frame: 0x38
   __TEXT.__oslogstring: 0x1e7a
   __DATA_CONST.__const: 0x212d0

   - /System/DriverKit/System/Library/PrivateFrameworks/IOFileValidation.framework/IOFileValidation
   - /System/DriverKit/System/Library/PrivateFrameworks/OLYHALDriverKit.framework/OLYHALDriverKit
   - /System/DriverKit/usr/lib/libc++.dylib
-  Functions: 14189
-  Symbols:   12066
+  Functions: 14191
+  Symbols:   12068
   CStrings:  13096
 
Symbols:
+ __ZN24AppleBCMWLANNANInterface15flushFlowQueuesEP10ether_addr
+ __ZThn96_N24AppleBCMWLANNANInterface15flushFlowQueuesEP10ether_addr
CStrings:
+ "\"AppleBCMWLANV3_driverkit-1572.4\""
+ "AppleBCMWLANV3_driverkit-1572.4"
+ "Sep 13 2026 19:13:56"
- "\"AppleBCMWLANV3_driverkit-1572.3\""
- "AppleBCMWLANV3_driverkit-1572.3"
- "Sep  4 2026 23:22:34"
```
