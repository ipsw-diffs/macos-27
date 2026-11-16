## SpaceAttribution

> `/System/Library/PrivateFrameworks/SpaceAttribution.framework/Versions/A/SpaceAttribution`

```diff

-499.40.4.0.1
-  __TEXT.__text: 0x13c78
-  __TEXT.__objc_methlist: 0x14d0
+499.60.3.0.0
+  __TEXT.__text: 0x13ec4
+  __TEXT.__objc_methlist: 0x14e0
   __TEXT.__const: 0x160
-  __TEXT.__cstring: 0x1331
-  __TEXT.__oslogstring: 0x11e6
+  __TEXT.__cstring: 0x1362
+  __TEXT.__oslogstring: 0x1269
   __TEXT.__gcc_except_tab: 0x6e8
-  __TEXT.__unwind_info: 0x8a0
+  __TEXT.__unwind_info: 0x8b0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0xb0
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe08
+  __DATA_CONST.__objc_selrefs: 0xe10
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x68
   __DATA_CONST.__objc_arraydata: 0x138

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 610
+  Functions: 614
   Symbols:   1208
-  CStrings:  315
+  CStrings:  319
 
Symbols:
+ +[SASupport getAtimeUpdateCountersForPath:info:]
- GCC_except_table51
CStrings:
+ "%s: No counters output pointer was provided"
+ "%s: No path was provided"
+ "+[SASupport getAtimeUpdateCountersForPath:info:]"
+ "Failed to GET atime update counters for %s with error %d (%s)"
```
