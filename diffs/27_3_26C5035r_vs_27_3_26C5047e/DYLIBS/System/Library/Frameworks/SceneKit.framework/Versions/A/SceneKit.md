## SceneKit

> `/System/Library/Frameworks/SceneKit.framework/Versions/A/SceneKit`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`

```diff

-612.101.0.0.0
-  __TEXT.__text: 0x4b01c8
+612.200.0.0.0
+  __TEXT.__text: 0x4b0238
   __TEXT.__objc_methlist: 0x194b4
   __TEXT.__const: 0x26708
   __TEXT.__cstring: 0x9dced
   __TEXT.__oslogstring: 0x19903
   __TEXT.__gcc_except_tab: 0x413c
   __TEXT.__ustring: 0x3c
-  __TEXT.__unwind_info: 0x1b3a8
+  __TEXT.__unwind_info: 0x1b3b0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   - /System/Library/Frameworks/ModelIO.framework/Versions/A/ModelIO
   - /System/Library/Frameworks/OpenGL.framework/Versions/A/OpenGL
   - /System/Library/Frameworks/QuartzCore.framework/Versions/A/QuartzCore
+  - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/Versions/A/UniformTypeIdentifiers
   - /System/Library/PrivateFrameworks/CoreSymbolication.framework/Versions/A/CoreSymbolication
   - /System/Library/PrivateFrameworks/CoreUI.framework/Versions/A/CoreUI

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 29200
+  Functions: 29201
   Symbols:   39663
   CStrings:  9729
 
Functions:
~ __ZL14__AddNewSourceP9domSourcePKcP9__C3DMeshPlbP12__C3DLibrary : 2160 -> 2200
~ __ZN20SCNCJavaScriptAction27cpp_updateWithTargetForTimeEP7SCNNoded : 308 -> 296
~ __loadDDS : 2104 -> 2120
~ ___appendController : 1032 -> 1024
+ __ZN20SCNCJavaScriptAction27cpp_updateWithTargetForTimeEP7SCNNoded.cold.1
CStrings:
+ "Welcome to SceneKit 612.200 (Nov 10 2026 01:55:00)"
- "Welcome to SceneKit 612.101 (Oct 29 2026 01:06:27)"
```
