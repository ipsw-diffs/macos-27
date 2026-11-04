## com.apple.iokit.IONetworkingFamily

> `com.apple.iokit.IONetworkingFamily`

```diff

-190.0.0.0.0
+192.0.0.0.0
   __TEXT.__cstring: 0x1101
   __TEXT.__const: 0x54
-  __TEXT_EXEC.__text: 0x1c264
-  __TEXT_EXEC.__auth_stubs: 0xd20
+  __TEXT_EXEC.__text: 0x1c358
+  __TEXT_EXEC.__auth_stubs: 0xd30
   __DATA.__data: 0xc8
   __DATA.__common: 0x3b8
   __DATA.__bss: 0x88

   __DATA_CONST.__kalloc_type: 0xa80
   __DATA_CONST.__kalloc_var: 0x230
   __DATA_CONST.__assert: 0x21c
-  __DATA_CONST.__auth_got: 0x690
+  __DATA_CONST.__auth_got: 0x698
   __DATA_CONST.__got: 0x108
   __LINKINFO.__symbolsets: 0xdc74
-  Functions: 976
-  Symbols:   1725
+  Functions: 978
+  Symbols:   1728
   CStrings:  211
 
Symbols:
+ __ZN18IONetworkInterface15flushInputQueueEP11IOMbufQueue
+ __ZN18IONetworkInterface25configureSynchronousInputEv
+ __ZZN18IONetworkInterface4freeEvE20kalloc_type_view_343
+ __ZZN18IONetworkInterface4freeEvE20kalloc_type_view_382
+ __ZZN18IONetworkInterface4initEP19IONetworkControllerE20kalloc_type_view_197
+ __ZZN18IONetworkInterface4initEP19IONetworkControllerE20kalloc_type_view_216
+ _ifnet_enable_synchronous_input
- __ZZN18IONetworkInterface4freeEvE20kalloc_type_view_342
- __ZZN18IONetworkInterface4freeEvE20kalloc_type_view_381
- __ZZN18IONetworkInterface4initEP19IONetworkControllerE20kalloc_type_view_196
- __ZZN18IONetworkInterface4initEP19IONetworkControllerE20kalloc_type_view_215
Functions:
+ __ZN18IONetworkInterface15flushInputQueueEP11IOMbufQueue
~ __ZN18IONetworkInterface21attachToDataLinkLayerEjPv : 2276 -> 2296
+ __ZN18IONetworkInterface25configureSynchronousInputEv
```
