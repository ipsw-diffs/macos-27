## com.apple.driver.AppleSmartBatteryManager

> `com.apple.driver.AppleSmartBatteryManager`

```diff

-2043.40.52.0.2
-  __TEXT.__cstring: 0x82ad
+2043.60.6.0.0
+  __TEXT.__cstring: 0x8331
   __TEXT.__const: 0x2640
-  __TEXT.__os_log: 0x2694
-  __TEXT_EXEC.__text: 0x311d4
+  __TEXT.__os_log: 0x26c8
+  __TEXT_EXEC.__text: 0x31464
   __TEXT_EXEC.__auth_stubs: 0x790
   __DATA.__data: 0x1f0
   __DATA.__common: 0x4d8
-  __DATA.__bss: 0x5688
+  __DATA.__bss: 0x56c8
   __DATA_CONST.__mod_init_func: 0xa0
   __DATA_CONST.__mod_term_func: 0x78
   __DATA_CONST.__const: 0x9a78

   __DATA_CONST.__auth_got: 0x3c8
   __DATA_CONST.__got: 0x100
   Functions: 685
-  Symbols:   2271
-  CStrings:  1257
+  Symbols:   2281
+  CStrings:  1266
 
Symbols:
+ __ZL16_kFedMaxPowerSym
+ __ZL18_kFedMaxCurrentSym
+ __ZL18_kFedMaxVoltageSym
+ __ZL19_kFedWPDebugDataSym
+ __ZL20_kFedWPPolicyDataSym
+ __ZL22_kFedCapabilityDataSym
+ __ZL25_kFedExtSrcCapVendorIDSym
+ __ZL26_kFedExtSrcCapProductIDSym
+ __ZZN17AppleSmartBattery11copyFedInfoEhE11_os_log_fmt__20_
+ __ZZN17AppleSmartBattery11copyFedInfoEhE17fedPdCapSupported
+ __ZZN17AppleSmartBattery18initializeCommandsEvE21kalloc_type_view_2526
+ __ZZN17AppleSmartBattery18smcNotifierHandlerEPvP9IOServiceP10IONotifierE21kalloc_type_view_6528
+ __ZZN17AppleSmartBattery18smcNotifierHandlerEPvP9IOServiceP10IONotifierE21kalloc_type_view_6539
- __ZZN17AppleSmartBattery18initializeCommandsEvE21kalloc_type_view_2518
- __ZZN17AppleSmartBattery18smcNotifierHandlerEPvP9IOServiceP10IONotifierE21kalloc_type_view_6488
- __ZZN17AppleSmartBattery18smcNotifierHandlerEPvP9IOServiceP10IONotifierE21kalloc_type_view_6499
Functions:
~ __ZN17AppleSmartBattery11copyFedInfoEh : 3044 -> 3540
~ __GLOBAL__sub_I_AppleSmartBattery.cpp : 12476 -> 12636
CStrings:
+ "Failed to read FED PD cap key %c%c%c%c. rc:0x%x=%s\n"
+ "FedCapabilityData"
+ "FedExtSrcCapProductID"
+ "FedExtSrcCapVendorID"
+ "FedMaxCurrent"
+ "FedMaxPower"
+ "FedMaxVoltage"
+ "FedWPDebugData"
+ "FedWPPolicyData"
```
