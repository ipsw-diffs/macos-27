## libcryptex.dylib

> `/usr/lib/libcryptex.dylib`

```diff

-761.40.23.0.0
-  __TEXT.__text: 0x28e8c
-  __TEXT.__objc_methlist: 0x4b0
+761.60.7.0.0
+  __TEXT.__text: 0x28f80
+  __TEXT.__objc_methlist: 0x480
   __TEXT.__const: 0x840
   __TEXT.__gcc_except_tab: 0xce0
-  __TEXT.__cstring: 0x218a
-  __TEXT.__oslogstring: 0x48f9
-  __TEXT.__unwind_info: 0x848
+  __TEXT.__cstring: 0x2187
+  __TEXT.__oslogstring: 0x4966
+  __TEXT.__unwind_info: 0x850
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x78
   __DATA_CONST.__objc_nlclslist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2e0
+  __DATA_CONST.__objc_selrefs: 0x2c0
   __DATA_CONST.__objc_superrefs: 0x78
-  __DATA_CONST.__got: 0x1e8
+  __DATA_CONST.__got: 0x1f0
   __AUTH_CONST.__const: 0x460
   __AUTH_CONST.__cfstring: 0x1a0
-  __AUTH_CONST.__objc_const: 0xe78
+  __AUTH_CONST.__objc_const: 0xe18
   __AUTH_CONST.__objc_intobj: 0x78
-  __AUTH_CONST.__auth_got: 0x9d0
+  __AUTH_CONST.__auth_got: 0x9d8
   __AUTH.__objc_data: 0x280
-  __DATA.__objc_ivar: 0x74
+  __DATA.__objc_ivar: 0x6c
   __DATA.__data: 0x30
   __DATA.__bss: 0x60
   __DATA_DIRTY.__objc_data: 0x230

   - /usr/lib/libcryptex_interface.dylib
   - /usr/lib/libimage4.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 528
-  Symbols:   1095
-  CStrings:  694
+  Functions: 529
+  Symbols:   1087
+  CStrings:  697
 
Symbols:
+ __os_log_debug_impl
+ __xpc_error_connection_invalid
- -[Collation client_con]
- -[Collation endpoint]
- -[Collation setClient_con:]
- -[Collation setEndpoint:]
- _OBJC_IVAR_$_Collation._client_con
- _OBJC_IVAR_$_Collation._endpoint
- _objc_msgSend$client_con
- _objc_msgSend$endpoint
- _objc_msgSend$setClient_con:
- _objc_msgSend$setEndpoint:
CStrings:
+ "761.60.7"
+ "@(#)VERSION:Darwin Cryptex Interface Version 2.0.0: Thu Oct 29 01:21:36 PDT 2026; root:libcryptex-761.60.7~184/libcryptex/RELEASE_ARM64E"
+ "Client connection invalidated"
+ "Collation request failed for user %u: %s"
+ "Darwin Cryptex Interface Version 2.0.0: Thu Oct 29 01:21:36 PDT 2026; root:libcryptex-761.60.7~184/libcryptex/RELEASE_ARM64E"
+ "No collation in reply for user %u: %@"
+ "No endpoint for user %u"
- "761.40.23"
- "@(#)VERSION:Darwin Cryptex Interface Version 2.0.0: Sat Oct  3 17:38:50 PDT 2026; root:libcryptex-761.40.23~872/libcryptex/RELEASE_ARM64E"
- "Darwin Cryptex Interface Version 2.0.0: Sat Oct  3 17:38:50 PDT 2026; root:libcryptex-761.40.23~872/libcryptex/RELEASE_ARM64E"
- "No endpoint for user %d"
```
