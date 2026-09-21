## com.apple.driver.AppleARMPlatform

> `com.apple.driver.AppleARMPlatform`

```diff

-1150.40.3.0.0
+1150.40.4.0.0
   __TEXT.__const: 0x1ae0
-  __TEXT.__os_log: 0x14f7
-  __TEXT.__cstring: 0xd0ec
-  __TEXT_EXEC.__text: 0x54800
+  __TEXT.__os_log: 0x1553
+  __TEXT.__cstring: 0xd158
+  __TEXT_EXEC.__text: 0x54920
   __TEXT_EXEC.__auth_stubs: 0xd60
   __DATA.__data: 0x6c8
   __DATA.__common: 0xcd8

   __DATA_CONST.__auth_got: 0x6b0
   __DATA_CONST.__got: 0x1f8
   Functions: 2244
-  Symbols:   3609
-  CStrings:  1738
+  Symbols:   3611
+  CStrings:  1742
 
Symbols:
+ __ZZN18AppleMCCUserClient19clientMemoryForTypeEjPjPP18IOMemoryDescriptorE11_os_log_fmt_3
+ __ZZZN23AppleMemCacheController30getDataCollectionMemDescriptorEvEUb4_E11_os_log_fmt_0
Functions:
~ __ZN18AppleMCCUserClient19clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 600 -> 700
~ ____ZN23AppleMemCacheController21disableDataCollectionEv_block_invoke : 316 -> 348
~ ____ZN23AppleMemCacheController30getDataCollectionMemDescriptorEv_block_invoke : 256 -> 412
CStrings:
+ "%s:%d: Failed to create mem descriptor for shared data queue\n\n"
+ "%s:%d: No data collection buffer available\n\n"
+ "Failed to create mem descriptor for shared data queue\n"
+ "No data collection buffer available\n"
```
