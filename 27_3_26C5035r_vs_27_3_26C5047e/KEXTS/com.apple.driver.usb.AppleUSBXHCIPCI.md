## com.apple.driver.usb.AppleUSBXHCIPCI

> `com.apple.driver.usb.AppleUSBXHCIPCI`

```diff

-1617.60.3.0.0
+1617.60.7.0.0
   __TEXT.__cstring: 0x2c0c
   __TEXT.__os_log: 0x1565
   __TEXT.__const: 0x10
-  __TEXT_EXEC.__text: 0x18710
+  __TEXT_EXEC.__text: 0x187d8
   __TEXT_EXEC.__auth_stubs: 0x5f0
   __DATA.__data: 0x1e8
   __DATA.__common: 0x380
   __DATA_CONST.__mod_init_func: 0x78
   __DATA_CONST.__mod_term_func: 0x78
-  __DATA_CONST.__const: 0x2b4d8
+  __DATA_CONST.__const: 0x2b4c0
   __DATA_CONST.__kalloc_type: 0x580
   __DATA_CONST.__auth_got: 0x2f8
   __DATA_CONST.__got: 0x110
Symbols:
+ __ZN19AppleASMediaUSBXHCI17createRequestPoolEP10IOWorkLoopP17IOUSBHostIOSource
- __ZN19AppleASMediaUSBXHCI28createIsochronousRequestPoolEv
Functions:
~ __ZN19AppleASMediaUSBXHCI28createIsochronousRequestPoolEv -> __ZN19AppleASMediaUSBXHCI17createRequestPoolEP10IOWorkLoopP17IOUSBHostIOSource : 80 -> 280
```
