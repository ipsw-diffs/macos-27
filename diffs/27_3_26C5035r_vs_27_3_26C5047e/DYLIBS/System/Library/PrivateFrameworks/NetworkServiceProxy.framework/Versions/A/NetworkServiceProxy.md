## NetworkServiceProxy

> `/System/Library/PrivateFrameworks/NetworkServiceProxy.framework/Versions/A/NetworkServiceProxy`

```diff

-990.60.10.0.1
-  __TEXT.__text: 0x6dbc8
-  __TEXT.__objc_methlist: 0x6844
+990.60.12.0.1
+  __TEXT.__text: 0x6e424
+  __TEXT.__objc_methlist: 0x6864
   __TEXT.__const: 0x380
   __TEXT.__gcc_except_tab: 0xb4
-  __TEXT.__cstring: 0x5d40
-  __TEXT.__oslogstring: 0x347f
-  __TEXT.__unwind_info: 0x16c0
+  __TEXT.__cstring: 0x5da8
+  __TEXT.__oslogstring: 0x34f0
+  __TEXT.__unwind_info: 0x16d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x258
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2be8
+  __DATA_CONST.__objc_selrefs: 0x2bf8
   __DATA_CONST.__objc_superrefs: 0x240
   __DATA_CONST.__objc_arraydata: 0x48
   __DATA_CONST.__got: 0x4a0
   __AUTH_CONST.__const: 0x9a0
-  __AUTH_CONST.__cfstring: 0x5360
-  __AUTH_CONST.__objc_const: 0x8a00
+  __AUTH_CONST.__cfstring: 0x5380
+  __AUTH_CONST.__objc_const: 0x8a08
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x28

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2318
-  Symbols:   4329
-  CStrings:  1254
+  Functions: 2324
+  Symbols:   4335
+  CStrings:  1259
 
Symbols:
+ -[NSPPrivateAccessTokenFetcher clearRetryIntervalWithQueue:completionHandler:]
+ -[NSPServerClient clearRetryAfterIntervalWithFetcher:allowRetry:completionHandler:]
+ GCC_except_table24
+ ___78-[NSPPrivateAccessTokenFetcher clearRetryIntervalWithQueue:completionHandler:]_block_invoke
+ ___83-[NSPServerClient clearRetryAfterIntervalWithFetcher:allowRetry:completionHandler:]_block_invoke
+ _homepodShouldEagerlyExit
+ _objc_msgSend$clearRetryAfterIntervalWithFetcher:allowRetry:completionHandler:
- GCC_except_table23
CStrings:
+ "-[NSPPrivateAccessTokenFetcher clearRetryIntervalWithQueue:completionHandler:]"
+ "Clear retry interval got invalid connection, retrying"
+ "Clearing retry interval"
+ "Failed to clear retry interval: %@"
+ "NSPServerErrorRetryAfter"
```
