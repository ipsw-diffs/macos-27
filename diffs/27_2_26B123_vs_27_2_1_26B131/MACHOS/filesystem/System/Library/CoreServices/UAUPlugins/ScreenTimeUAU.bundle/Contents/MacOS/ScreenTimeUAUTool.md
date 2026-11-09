## ScreenTimeUAUTool

> `/System/Library/CoreServices/UAUPlugins/ScreenTimeUAU.bundle/Contents/MacOS/ScreenTimeUAUTool`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__cfstring`

```diff

-655.1.14.1.0
-  __TEXT.__text: 0x778
+655.1.14.1.401
+  __TEXT.__text: 0x82c
   __TEXT.__auth_stubs: 0xc0
-  __TEXT.__objc_stubs: 0x360
-  __TEXT.__const: 0x58
+  __TEXT.__objc_stubs: 0x380
+  __TEXT.__const: 0x60
   __TEXT.__cstring: 0x73
-  __TEXT.__oslogstring: 0x10d
-  __TEXT.__objc_methname: 0x234
+  __TEXT.__oslogstring: 0x15d
+  __TEXT.__objc_methname: 0x25c
   __TEXT.__unwind_info: 0x78
   __DATA_CONST.__cfstring: 0xc0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x68
   __DATA_CONST.__got: 0x50
-  __DATA.__objc_selrefs: 0xd8
+  __DATA.__objc_selrefs: 0xe0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/PrivateFrameworks/ScreenTimeCore.framework/Versions/A/ScreenTimeCore
   - /System/Library/PrivateFrameworks/SystemAdministration.framework/Versions/A/SystemAdministration
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 8
+  Functions: 9
   Symbols:   26
-  CStrings:  41
+  CStrings:  43
 
Functions:
~ sub_100000920 : 1564 -> 1676
+ sub_1000010d0
CStrings:
+ "Failed to call agent to infer the age range for the signed-out user: %{public}@"
+ "inferAgeRangeForSignedOutUserWithError:"
```
