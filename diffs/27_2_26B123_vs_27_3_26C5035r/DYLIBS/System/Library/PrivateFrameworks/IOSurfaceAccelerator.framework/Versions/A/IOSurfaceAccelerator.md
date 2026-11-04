## IOSurfaceAccelerator

> `/System/Library/PrivateFrameworks/IOSurfaceAccelerator.framework/Versions/A/IOSurfaceAccelerator`

```diff

-200.67.0.0.0
-  __TEXT.__text: 0x2d30
-  __TEXT.__cstring: 0xe66
-  __TEXT.__const: 0x50
-  __TEXT.__unwind_info: 0x190
+200.74.0.0.0
+  __TEXT.__text: 0x2f98
+  __TEXT.__cstring: 0xf88
+  __TEXT.__const: 0x58
+  __TEXT.__unwind_info: 0x198
   __TEXT.__auth_stubs: 0x0
-  __DATA_CONST.__const: 0x3c0
+  __DATA_CONST.__const: 0x3e0
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x80
   __AUTH_CONST.__cfstring: 0xb20

   - /System/Library/Frameworks/IOSurface.framework/Versions/A/IOSurface
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
-  Functions: 79
-  Symbols:   217
-  CStrings:  168
+  Functions: 82
+  Symbols:   222
+  CStrings:  171
 
Symbols:
+ _IOSurfaceLookup
+ _IOSurfaceSetBulkAttachments2
+ __NSConcreteStackBlock
+ ___IOSurfaceAcceleratorGetHistogram_block_invoke
+ _applyGuestIOSurfaceBulkAttachmentKeys
Functions:
~ _IOSurfaceAcceleratorCreate : 624 -> 628
~ _IOSurfaceAcceleratorGetHistogram : 256 -> 260
+ ___IOSurfaceAcceleratorGetHistogram_block_invoke
~ _IOSurfaceAcceleratorParavirtProcessGuestData : 224 -> 332
+ _applyGuestIOSurfaceBulkAttachmentKeys
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOSurfaceAccelerator_Userspace/IOSurfaceAccelerator.c"
+ "applyGuestIOSurfaceBulkAttachmentKeys"
+ "paravirt: failed to attach colour keys to surface %u: %#x\n"
```
