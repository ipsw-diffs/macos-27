## libIASUnifiedProgress.dylib

> `/usr/lib/libIASUnifiedProgress.dylib`

```diff

-21.0.0.0.0
-  __TEXT.__text: 0x4f9c
-  __TEXT.__objc_methlist: 0x8b4
+21.3.1.0.0
+  __TEXT.__text: 0x503c
+  __TEXT.__objc_methlist: 0x8bc
   __TEXT.__const: 0x20
   __TEXT.__gcc_except_tab: 0x140
-  __TEXT.__cstring: 0x1420
+  __TEXT.__cstring: 0x1455
   __TEXT.__oslogstring: 0x3
-  __TEXT.__unwind_info: 0x2b0
+  __TEXT.__unwind_info: 0x2b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x38
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x660
+  __DATA_CONST.__objc_selrefs: 0x668
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x300
-  __AUTH_CONST.__cfstring: 0xd00
+  __AUTH_CONST.__cfstring: 0xd20
   __AUTH_CONST.__objc_const: 0xe38
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x1b8

   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 168
-  Symbols:   514
-  CStrings:  128
+  Functions: 169
+  Symbols:   521
+  CStrings:  129
 
Symbols:
+ -[IASUnifiedProgressManager _isProgressAppRegistered]
+ GCC_except_table11
+ GCC_except_table18
+ _bootstrap_look_up
+ _bootstrap_port
+ _mach_port_deallocate
+ _mach_task_self_
+ _objc_msgSend$_isProgressAppRegistered
- GCC_except_table17
CStrings:
+ "progress app is registered, not checking its version"
```
