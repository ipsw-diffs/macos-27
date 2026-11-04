## com.apple.driver.AppleHIDTransport

> `com.apple.driver.AppleHIDTransport`

```diff

-10410.3.0.0.0
-  __TEXT.__cstring: 0xccd1
+10420.1.0.0.0
+  __TEXT.__cstring: 0xcce8
   __TEXT.__const: 0x3c8
   __TEXT.__os_log: 0x28d
-  __TEXT_EXEC.__text: 0x746dc
+  __TEXT_EXEC.__text: 0x74714
   __TEXT_EXEC.__auth_stubs: 0x930
   __DATA.__data: 0xc8
   __DATA.__common: 0x498
   __DATA.__bss: 0x130
   __DATA_CONST.__mod_init_func: 0xd0
   __DATA_CONST.__mod_term_func: 0xd0
-  __DATA_CONST.__const: 0xec00
+  __DATA_CONST.__const: 0xec10
   __DATA_CONST.__kalloc_type: 0xa80
   __DATA_CONST.__auth_got: 0x498
   __DATA_CONST.__got: 0x160
   Functions: 2316
-  Symbols:   2239
-  CStrings:  1508
+  Symbols:   2241
+  CStrings:  1510
 
Symbols:
+ __ZN26AppleHIDTransportInterface19kHIDMaxEventSizeKeyE
+ __ZN26AppleHIDTransportInterface21kHIDEventQueueSizeKeyE
+ __ZZN26AppleHIDTransportInterface22performMasterSetReportEP23AppleHIDTransportDevicehP18IOMemoryDescriptor15IOHIDReportTypeE20kalloc_type_view_634
+ __ZZZN26AppleHIDTransportInterface22performMasterSetReportEP23AppleHIDTransportDevicehP18IOMemoryDescriptor15IOHIDReportTypeENK3$_0clEPvS6_E20kalloc_type_view_674
- __ZZN26AppleHIDTransportInterface22performMasterSetReportEP23AppleHIDTransportDevicehP18IOMemoryDescriptor15IOHIDReportTypeE20kalloc_type_view_632
- __ZZZN26AppleHIDTransportInterface22performMasterSetReportEP23AppleHIDTransportDevicehP18IOMemoryDescriptor15IOHIDReportTypeENK3$_0clEPvS6_E20kalloc_type_view_672
Functions:
~ __ZN26AppleHIDTransportHIDDevice17publishPropertiesEP9IOService : 428 -> 484
CStrings:
+ "MaxEventSize"
+ "QueueSize"
```
