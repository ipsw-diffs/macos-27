## DiagnosticsKit

> `/System/Library/PrivateFrameworks/DiagnosticsKit.framework/Versions/A/DiagnosticsKit`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH.__objc_data`
- `__DATA.__data`

```diff

-104.0.0.0.0
-  __TEXT.__text: 0x1f5d8
-  __TEXT.__objc_methlist: 0x2b0c
+104.60.2.0.0
+  __TEXT.__text: 0x1f858
+  __TEXT.__objc_methlist: 0x2b24
   __TEXT.__const: 0xd0
-  __TEXT.__cstring: 0x1ba4
-  __TEXT.__gcc_except_tab: 0x970
+  __TEXT.__cstring: 0x1bce
+  __TEXT.__gcc_except_tab: 0x988
   __TEXT.__oslogstring: 0x1b2b
-  __TEXT.__unwind_info: 0xc68
-  __TEXT.__objc_stubs: 0x3c40
+  __TEXT.__unwind_info: 0xc80
+  __TEXT.__objc_stubs: 0x3c60
   __TEXT.__auth_stubs: 0x520
   __TEXT.__objc_classname: 0x605
-  __TEXT.__objc_methname: 0x520d
+  __TEXT.__objc_methname: 0x527c
   __TEXT.__objc_methtype: 0xf84
   __DATA_CONST.__const: 0x230
   __DATA_CONST.__objc_classlist: 0x150
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x108
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x12d0
+  __DATA_CONST.__objc_selrefs: 0x12e0
   __DATA_CONST.__objc_protorefs: 0x70
   __DATA_CONST.__objc_superrefs: 0x100
   __DATA_CONST.__got: 0x268
-  __AUTH_CONST.__const: 0xa20
+  __AUTH_CONST.__const: 0xa50
   __AUTH_CONST.__cfstring: 0xe00
-  __AUTH_CONST.__objc_const: 0x4a18
+  __AUTH_CONST.__objc_const: 0x4a48
   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__auth_got: 0x2a0
   __AUTH.__objc_data: 0xd20
-  __DATA.__objc_ivar: 0x274
+  __DATA.__objc_ivar: 0x278
   __DATA.__data: 0xc70
   __DATA.__bss: 0x108
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 920
-  Symbols:   2240
-  CStrings:  1434
+  Functions: 926
+  Symbols:   2247
+  CStrings:  1439
 
Symbols:
+ -[DKDiagnosticService connectionsQueue]
+ -[DKDiagnosticService setConnectionsQueue:]
+ _OBJC_IVAR_$_DKDiagnosticService._connectionsQueue
+ ___block_descriptor_48_e8_32s40w_e5_v8?0l
+ ___block_descriptor_64_e8_32s40w48w56w_e5_v8?0l
+ ___copy_helper_block_e8_32s40w
+ ___copy_helper_block_e8_32s40w48w56w
+ ___destroy_helper_block_e8_32s40w
+ ___destroy_helper_block_e8_32s40w48w56w
+ _objc_msgSend$connectionsQueue
- ___block_descriptor_56_e8_32w40w48w_e5_v8?0l
- ___copy_helper_block_e8_32w40w48w
- ___destroy_helper_block_e8_32w40w48w
CStrings:
+ "T@\"NSObject<OS_dispatch_queue>\",&,N,V_connectionsQueue"
+ "_connectionsQueue"
+ "com.apple.DiagnosticsKit.connectionsQueue"
+ "connectionsQueue"
+ "setConnectionsQueue:"
```
