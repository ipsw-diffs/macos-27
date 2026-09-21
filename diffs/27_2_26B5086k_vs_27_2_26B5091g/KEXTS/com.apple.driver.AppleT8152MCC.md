## com.apple.driver.AppleT8152MCC

> `com.apple.driver.AppleT8152MCC`

```diff

-127.40.4.0.0
+127.40.5.0.0
   __TEXT.__const: 0x70
-  __TEXT.__cstring: 0x62e1
-  __TEXT.__os_log: 0x29ec
-  __TEXT_EXEC.__text: 0x17b10
+  __TEXT.__cstring: 0x634d
+  __TEXT.__os_log: 0x2a48
+  __TEXT_EXEC.__text: 0x17c34
   __TEXT_EXEC.__auth_stubs: 0x5b0
   __DATA.__data: 0xc4b0
   __DATA.__common: 0x1f0

   __DATA_CONST.__auth_got: 0x2d8
   __DATA_CONST.__got: 0xc0
   Functions: 575
-  Symbols:   1321
-  CStrings:  1013
+  Symbols:   1323
+  CStrings:  1017
 
Symbols:
+ __ZZN20AppleMCCUserClientV219clientMemoryForTypeEjPjPP18IOMemoryDescriptorE11_os_log_fmt_3
+ __ZZZN25AppleMemCacheControllerV230getDataCollectionMemDescriptorEvEUb4_E11_os_log_fmt_0
Functions:
~ ____ZN25AppleMemCacheControllerV221disableDataCollectionEv_block_invoke : 312 -> 348
~ ____ZN25AppleMemCacheControllerV230getDataCollectionMemDescriptorEv_block_invoke : 256 -> 412
~ __ZN20AppleMCCUserClientV219clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 600 -> 700
CStrings:
+ "%s:%d: Failed to create mem descriptor for shared data queue\n\n"
+ "%s:%d: No data collection buffer available\n\n"
+ "Failed to create mem descriptor for shared data queue\n"
+ "No data collection buffer available\n"
```
