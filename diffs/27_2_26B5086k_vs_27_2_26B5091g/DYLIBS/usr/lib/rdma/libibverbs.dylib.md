## libibverbs.dylib

> `/usr/lib/rdma/libibverbs.dylib`

```diff

-112.40.13.0.0
-  __TEXT.__text: 0xd588
-  __TEXT.__cstring: 0x1284
+112.40.14.0.1
+  __TEXT.__text: 0xd6b0
+  __TEXT.__cstring: 0x1285
   __TEXT.__const: 0x1f8
   __TEXT.__unwind_info: 0x570
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x260
   __AUTH_CONST.__cfstring: 0x60
-  __AUTH_CONST.__auth_got: 0x2c8
+  __AUTH_CONST.__auth_got: 0x2d0
   __DATA.__data: 0xb0
   __DATA.__bss: 0x38
   __DATA.__common: 0x5

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/rdma/libccan.dylib
-  Functions: 384
-  Symbols:   475
+  Functions: 385
+  Symbols:   477
   CStrings:  212
 
Symbols:
+ ___strlcpy_chk
+ _ibv_darwin_set_resolver_ifname
Functions:
+ _ibv_darwin_set_resolver_ifname
```
