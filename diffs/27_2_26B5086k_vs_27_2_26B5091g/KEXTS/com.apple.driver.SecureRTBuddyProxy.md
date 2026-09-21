## com.apple.driver.SecureRTBuddyProxy

> `com.apple.driver.SecureRTBuddyProxy`

```diff

-778.40.9.0.0
-  __TEXT.__cstring: 0x11c7
+778.40.11.0.0
+  __TEXT.__cstring: 0x128b
   __TEXT.__const: 0x8
-  __TEXT_EXEC.__text: 0x99c8
+  __TEXT_EXEC.__text: 0x9cbc
   __TEXT_EXEC.__auth_stubs: 0x5a0
   __DATA.__data: 0xc8
   __DATA.__common: 0xd8

   __DATA_CONST.__mod_term_func: 0x28
   __DATA_CONST.__const: 0x1bb0
   __DATA_CONST.__kalloc_type: 0x140
+  __DATA_CONST.__assert: 0x168
   __DATA_CONST.__auth_got: 0x2d0
-  __DATA_CONST.__got: 0x78
-  Functions: 300
-  Symbols:   682
-  CStrings:  82
+  __DATA_CONST.__got: 0x80
+  Functions: 318
+  Symbols:   711
+  CStrings:  89
 
Symbols:
+ _ZN18SecureRTBuddyProxy12checkForWorkEj
+ _ZN18SecureRTBuddyProxy12powerOnGatedEv
+ _ZN18SecureRTBuddyProxy13powerOffGatedEv
+ _ZN18SecureRTBuddyProxy20changePowerStateExitE17RTBuddyPowerStatebb
+ _ZN18SecureRTBuddyProxy21changePowerStateEntryE17RTBuddyPowerStateb
+ _ZN18SecureRTBuddyProxy22notifyPowerStateChangeE17RTBuddyPowerStateS0_
+ _ZN18SecureRTBuddyProxy22recordPowerStateChangeE17RTBuddyPowerState
+ _ZN18SecureRTBuddyProxy23performPowerStateChangeE17RTBuddyPowerState
+ _ZN18SecureRTBuddyProxy5startEP9IOService
+ _ZN26SecureRTBuddyProxyEndpoint25tryCreatePMAssertionGatedEv
+ __ZZN18SecureRTBuddyProxy12checkForWorkEjE6__desc
+ __ZZN18SecureRTBuddyProxy12checkForWorkEjE6__desc_0
+ __ZZN18SecureRTBuddyProxy12findEndpointEjE6__desc
+ __ZZN18SecureRTBuddyProxy12powerOnGatedEvE6__desc
+ __ZZN18SecureRTBuddyProxy13powerOffGatedEvE6__desc
+ __ZZN18SecureRTBuddyProxy20changePowerStateExitE17RTBuddyPowerStatebbE6__desc
+ __ZZN18SecureRTBuddyProxy21changePowerStateEntryE17RTBuddyPowerStatebE6__desc
+ __ZZN18SecureRTBuddyProxy22notifyPowerStateChangeE17RTBuddyPowerStateS0_E6__desc
+ __ZZN18SecureRTBuddyProxy22notifyPowerStateChangeE17RTBuddyPowerStateS0_E6__desc_0
+ __ZZN18SecureRTBuddyProxy22recordPowerStateChangeE17RTBuddyPowerStateE6__desc
+ __ZZN18SecureRTBuddyProxy23performPowerStateChangeE17RTBuddyPowerStateE6__desc
+ __ZZN18SecureRTBuddyProxy26outboxNotEmptyHandlerGatedEP22IOInterruptEventSourceE6__desc
+ __ZZN18SecureRTBuddyProxy5startEP9IOServiceE6__desc
+ __ZZN18SecureRTBuddyProxy5startEP9IOServiceE6__desc_0
+ __ZZN24SecureRTBuddyIOReporting5startEP9IOServiceE6__desc
+ __ZZN24SecureRTBuddyIOReporting5startEP9IOServiceE6__desc_0
+ __ZZN26SecureRTBuddyProxyEndpoint25tryCreatePMAssertionGatedEvE6__desc
+ __ZZN26SecureRTBuddyProxyEndpoint25tryCreatePMAssertionGatedEvE6__desc_0
+ _kext_assertions_enable
CStrings:
+ "NULL != tb_endpoint"
+ "SecureRTBuddyProxyEndpoint.cpp"
+ "TB_ERROR_SUCCESS == tberr"
+ "_pmAssertionCount == 0"
+ "_pmAssertionID != kIOPMUndefinedDriverAssertionID"
+ "endpointNumber < 64"
+ "tberr == TB_ERROR_SUCCESS"
```
