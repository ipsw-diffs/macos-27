## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1572.8.0.0.0
-  __TEXT.__text: 0x2879f8
+  __TEXT.__text: 0x287d04
   __TEXT.__auth_stubs: 0x25b0
   __TEXT.__init_offsets: 0x1c0
-  __TEXT.__cstring: 0x82c9e
+  __TEXT.__cstring: 0x82dd9
   __TEXT.__const: 0x3d858
-  __TEXT.__unwind_info: 0xa450
+  __TEXT.__unwind_info: 0xa460
   __TEXT.__eh_frame: 0x38
   __TEXT.__oslogstring: 0x1e7a
   __DATA_CONST.__const: 0x212e8

   - /System/DriverKit/System/Library/PrivateFrameworks/IOFileValidation.framework/IOFileValidation
   - /System/DriverKit/System/Library/PrivateFrameworks/OLYHALDriverKit.framework/OLYHALDriverKit
   - /System/DriverKit/usr/lib/libc++.dylib
-  Functions: 14191
+  Functions: 14194
   Symbols:   12071
-  CStrings:  13093
+  CStrings:  13097
 
CStrings:
+ "Oct  3 2026 14:59:16"
+ "[dk] %s@%d:ERROR: NAN attribute header runs past the end of the attribute list\n"
+ "[dk] %s@%d:ERROR: NAN attribute length %u exceeds the remaining attribute list\n"
+ "[dk] %s@%d:ERROR: NAN shared key descriptor body %u too short, minimum %u\n"
+ "[dk] %s@%d:ERROR: NAN shared key descriptor key data length %u exceeds body %u\n"
- "Oct  3 2026 20:46:11"
```
