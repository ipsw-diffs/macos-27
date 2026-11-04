## com.apple.driver.AppleSecureRepair

> `com.apple.driver.AppleSecureRepair`

```diff

-1307.40.66.0.0
+1307.60.20.0.0
   __TEXT.__const: 0x110
-  __TEXT.__cstring: 0x9c3
-  __TEXT_EXEC.__text: 0x2c70
-  __TEXT_EXEC.__auth_stubs: 0x190
+  __TEXT.__cstring: 0xaf2
+  __TEXT_EXEC.__text: 0x33fc
+  __TEXT_EXEC.__auth_stubs: 0x1d0
   __DATA.__data: 0xc4
   __DATA.__common: 0xb0
   __DATA_CONST.__mod_init_func: 0x20
   __DATA_CONST.__mod_term_func: 0x20
   __DATA_CONST.__const: 0x29c8
   __DATA_CONST.__kalloc_type: 0x100
-  __DATA_CONST.__auth_got: 0xc8
-  __DATA_CONST.__got: 0x48
-  Functions: 112
-  Symbols:   472
-  CStrings:  84
+  __DATA_CONST.__auth_got: 0xe8
+  __DATA_CONST.__got: 0x58
+  Functions: 119
+  Symbols:   481
+  CStrings:  95
 
Symbols:
+ _IOMallocData
+ __ZN20AppleRepairSEPDriver22seaCookieHandleMessageEPKvmP18IOMemoryDescriptorPj
+ __ZN20AppleRepairSEPDriver25initSeaCookieProvisioningEv
+ __ZN20AppleRepairSEPDriver29sendSeaCookieIdentifiersToSEPEv
+ __ZN8OSNumber9metaClassE
+ __ZN9IOService12nameMatchingEPKcP12OSDictionary
+ __ZN9IOService19copyMatchingServiceEP12OSDictionary
+ _gIOParentMatchKey
+ _memmove
CStrings:
+ "1211111212221212121112"
+ "AppleAuthCPRelay"
+ "AppleSecureRepair: %s entry: inData:%p, inDataSize:%zu, outData:%p, outDataSize:%p\n\n"
+ "AppleSecureRepair: %s exit: err:0x%x (type:%d)\n"
+ "AppleSecureRepair: %s: message type: %d::%d\n"
+ "IDSN"
+ "flags"
+ "product"
+ "raw-panel-serial-number"
+ "seaCookieHandleMessage"
+ "sendSeaCookieIdentifiersToSEP"
+ "smc-area51"
- "121111121222121211112"
```
