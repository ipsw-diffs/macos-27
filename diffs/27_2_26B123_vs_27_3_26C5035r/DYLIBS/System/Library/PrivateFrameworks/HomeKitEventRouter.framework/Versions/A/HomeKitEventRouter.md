## HomeKitEventRouter

> `/System/Library/PrivateFrameworks/HomeKitEventRouter.framework/Versions/A/HomeKitEventRouter`

```diff

-1520.2.7.4.1
-  __TEXT.__text: 0x1864c
-  __TEXT.__objc_methlist: 0x15dc
-  __TEXT.__const: 0x48
+1535.0.0.0.2
+  __TEXT.__text: 0x18f24
+  __TEXT.__objc_methlist: 0x1624
+  __TEXT.__const: 0x58
   __TEXT.__gcc_except_tab: 0x49c
   __TEXT.__cstring: 0xb49
-  __TEXT.__oslogstring: 0x1d1a
-  __TEXT.__unwind_info: 0x770
+  __TEXT.__oslogstring: 0x1dfb
+  __TEXT.__unwind_info: 0x788
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0xa0
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xbb0
+  __DATA_CONST.__objc_selrefs: 0xbe0
   __DATA_CONST.__objc_superrefs: 0xa0
   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__got: 0xf8
   __AUTH_CONST.__const: 0x510
   __AUTH_CONST.__cfstring: 0x760
-  __AUTH_CONST.__objc_const: 0x2568
+  __AUTH_CONST.__objc_const: 0x25a0
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x320
-  __DATA.__objc_ivar: 0x1ac
+  __DATA.__objc_ivar: 0x1b0
   __DATA.__data: 0x4e0
   __DATA_DIRTY.__objc_data: 0x320
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 508
-  Symbols:   1280
-  CStrings:  252
+  Functions: 515
+  Symbols:   1293
+  CStrings:  255
 
Symbols:
+ -[HMEDelegatingEventRouter refreshSubRouterRegistrations]
+ -[HMEMessageDatagramClient _updateWantsConnection]
+ -[HMEMessageDatagramClient dormantFetchTimerInterval]
+ -[HMEMessageDatagramClient setWantsConnection:]
+ -[HMEMessageDatagramClient wantsConnection]
+ -[HMERouterClient registeredTopicFiltersForConsumer:]
+ GCC_except_table106
+ GCC_except_table112
+ GCC_except_table276
+ GCC_except_table281
+ GCC_except_table285
+ GCC_except_table293
+ GCC_except_table296
+ GCC_except_table298
+ GCC_except_table302
+ GCC_except_table304
+ GCC_except_table421
+ GCC_except_table423
+ GCC_except_table427
+ GCC_except_table439
+ GCC_except_table456
+ GCC_except_table82
+ GCC_except_table98
+ _OBJC_IVAR_$_HMEMessageDatagramClient._dormantFetchTimerInterval
+ _OBJC_IVAR_$_HMEMessageDatagramClient._wantsConnection
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HMESynchronousSubscriptionProviding
+ ___57-[HMEDelegatingEventRouter refreshSubRouterRegistrations]_block_invoke
+ _objc_msgSend$client:didChangeWantsConnection:
+ _objc_msgSend$dormantFetchTimerInterval
+ _objc_msgSend$localizedDescription
+ _objc_msgSend$registeredTopicFiltersForConsumer:
+ _objc_msgSend$setWantsConnection:
+ _objc_msgSend$wantsConnection
- -[HMEMessageDatagramClient dormatFetchTimerInterval]
- GCC_except_table101
- GCC_except_table109
- GCC_except_table270
- GCC_except_table274
- GCC_except_table278
- GCC_except_table286
- GCC_except_table289
- GCC_except_table291
- GCC_except_table295
- GCC_except_table297
- GCC_except_table414
- GCC_except_table416
- GCC_except_table420
- GCC_except_table432
- GCC_except_table449
- GCC_except_table81
- GCC_except_table97
- _OBJC_IVAR_$_HMEMessageDatagramClient._dormatFetchTimerInterval
- _objc_msgSend$dormatFetchTimerInterval
CStrings:
+ "Delegating registrations to subRouter: %{public}@, topicFilterAdditions: %lu, topicFilterRemovals: %lu"
+ "Failed to change registrations on subRouter: %{public}@, error: %{public}@"
+ "changed registrations on subRouter: %{public}@"
```
