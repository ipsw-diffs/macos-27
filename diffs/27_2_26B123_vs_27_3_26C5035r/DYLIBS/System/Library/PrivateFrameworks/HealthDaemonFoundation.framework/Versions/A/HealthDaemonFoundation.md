## HealthDaemonFoundation

> `/System/Library/PrivateFrameworks/HealthDaemonFoundation.framework/Versions/A/HealthDaemonFoundation`

```diff

-7027.1.56.1.1
-  __TEXT.__text: 0x786c4
-  __TEXT.__objc_methlist: 0x3e34
+7027.2.12.0.0
+  __TEXT.__text: 0x78870
+  __TEXT.__objc_methlist: 0x3e54
   __TEXT.__const: 0x2372
-  __TEXT.__cstring: 0x4b1b
+  __TEXT.__cstring: 0x4b2b
   __TEXT.__oslogstring: 0x3745
-  __TEXT.__gcc_except_tab: 0x30f8
+  __TEXT.__gcc_except_tab: 0x3104
   __TEXT.__swift5_typeref: 0xd2c
   __TEXT.__swift5_reflstr: 0x90b
   __TEXT.__swift5_assocty: 0xa8

   __TEXT.__swift5_protos: 0x38
   __TEXT.__swift5_mpenum: 0x24
   __TEXT.__swift5_types2: 0xc
-  __TEXT.__unwind_info: 0x31c8
+  __TEXT.__unwind_info: 0x31d8
   __TEXT.__eh_frame: 0x1510
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x21a8
+  __DATA_CONST.__objc_selrefs: 0x21c0
   __DATA_CONST.__objc_protorefs: 0x78
   __DATA_CONST.__objc_superrefs: 0x1e0
   __DATA_CONST.__objc_arraydata: 0x18
   __DATA_CONST.__got: 0x6b0
   __AUTH_CONST.__const: 0x38f8
-  __AUTH_CONST.__cfstring: 0x40e0
-  __AUTH_CONST.__objc_const: 0x8968
+  __AUTH_CONST.__cfstring: 0x4100
+  __AUTH_CONST.__objc_const: 0x8998
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0xef8
+  __AUTH_CONST.__auth_got: 0xf00
   __AUTH.__objc_data: 0xb20
   __AUTH.__data: 0x2d0
-  __DATA.__objc_ivar: 0x568
+  __DATA.__objc_ivar: 0x56c
   __DATA.__data: 0xbf0
   __DATA.__bss: 0x1d30
   __DATA_DIRTY.__objc_data: 0x16d8

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3183
-  Symbols:   4688
-  CStrings:  910
+  Functions: 3189
+  Symbols:   4696
+  CStrings:  911
 
Symbols:
+ -[HDDatabaseConnectionPool trimCachedConnectionsToCount:]
+ -[HDSQLiteConnectionHandle interruptRequested]
+ -[HDSQLiteConnectionHandle setInterruptRequested:]
+ _HDSQLiteInterruptProgressHandler
+ _OBJC_IVAR_$_HDSQLiteConnectionHandle._interruptRequested
+ _objc_msgSend$setInterruptRequested:
+ _objc_msgSend$trimCachedConnectionsToCount:
+ _sqlite3_progress_handler
CStrings:
+ "count >= 0"
```
