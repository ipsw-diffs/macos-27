## com.apple.driver.ApplePassthroughPPM

> `com.apple.driver.ApplePassthroughPPM`

```diff

-1191.40.27.0.1
+1191.60.10.0.0
   __TEXT.__const: 0x1170
-  __TEXT.__cstring: 0xffb4
+  __TEXT.__cstring: 0xffb2
   __TEXT.__os_log: 0x4646
-  __TEXT_EXEC.__text: 0x58520
-  __TEXT_EXEC.__auth_stubs: 0x7b0
+  __TEXT_EXEC.__text: 0x585c4
+  __TEXT_EXEC.__auth_stubs: 0x7c0
   __DATA.__data: 0x160
   __DATA.__common: 0x578
   __DATA.__bss: 0x200

   __DATA_CONST.__const: 0x9370
   __DATA_CONST.__kalloc_type: 0xa40
   __DATA_CONST.__kalloc_var: 0x140
-  __DATA_CONST.__auth_got: 0x3d8
+  __DATA_CONST.__auth_got: 0x3e0
   __DATA_CONST.__got: 0xe0
   __DATA_CONST.__auth_ptr: 0x10
   Functions: 2373
-  Symbols:   2589
+  Symbols:   2590
   CStrings:  1931
 
Symbols:
+ _current_task
Functions:
~ __ZN28ApplePPMPolicyCPMSPowerServo20controlEffortForLaneEi : 216 -> 232
~ __ZN8ApplePPM13setPropertiesEP8OSObject : 164 -> 280
~ __ZN12ApplePPMCPMS13setPropertiesEP8OSObject : 164 -> 280
~ __ZN12ApplePPMCPMS18setPropertiesGatedEP8OSObject : 4808 -> 4784
~ __ZN12ApplePPMCPMS18isClientRegisteredE16UniqueClientID_t : 32 -> 48
~ __ZN12ApplePPMCPMS18isClientRegisteredE16UniqueClientID_t : 32 -> 48
~ __ZN18ApplePPMUserClientC2EPK11OSMetaClass : 84 -> 64
~ __ZN18ApplePPMUserClientC1EPK11OSMetaClass : 84 -> 64
~ __ZNK18ApplePPMUserClient9MetaClass5allocEv : 136 -> 116
~ __ZN18ApplePPMUserClientC1Ev : 120 -> 100
~ __ZN18ApplePPMUserClientC2Ev : 120 -> 100
~ __ZN18ApplePPMUserClient5startEP9IOService : 320 -> 328
CStrings:
+ "12111112122212121111111111111212"
- "1211111212221212111111111111121211"
```
