## com.apple.driver.ApplePassthroughPPM

> `com.apple.driver.ApplePassthroughPPM`

```diff

-1191.60.10.0.0
+1191.60.11.0.0
   __TEXT.__const: 0x1170
   __TEXT.__cstring: 0xffb2
-  __TEXT.__os_log: 0x4646
-  __TEXT_EXEC.__text: 0x585c4
+  __TEXT.__os_log: 0x4698
+  __TEXT_EXEC.__text: 0x58708
   __TEXT_EXEC.__auth_stubs: 0x7c0
   __DATA.__data: 0x160
   __DATA.__common: 0x578
-  __DATA.__bss: 0x200
+  __DATA.__bss: 0x1f8
   __DATA_CONST.__mod_init_func: 0xf8
   __DATA_CONST.__mod_term_func: 0xc8
   __DATA_CONST.__const: 0x9370

   __DATA_CONST.__got: 0xe0
   __DATA_CONST.__auth_ptr: 0x10
   Functions: 2373
-  Symbols:   2590
-  CStrings:  1931
+  Symbols:   2589
+  CStrings:  1932
 
Symbols:
+ __ZZN42ApplePassthroughPPMSystemCapabilityMonitor23readBatteryInputFromASBEvE11_os_log_fmt_7
- __ZZN23ApplePPMBatteryModel4RC26handleDynamicShutdownParamEvE12prevModeLpem
- __ZZN23ApplePPMBatteryModel4RC26handleDynamicShutdownParamEvE15lpemParamsExist
Functions:
~ __ZN42ApplePassthroughPPMSystemCapabilityMonitor21createPPMBatteryModelEv : 208 -> 216
~ __ZN42ApplePassthroughPPMSystemCapabilityMonitor23readBatteryInputFromASBEv : 1192 -> 1380
~ __ZN35ApplePPMCPMSSystemCapabilityMonitor25consumeInternalSourceDataEP12OSDictionary : 3108 -> 3236
~ __ZN35ApplePPMCPMSSystemCapabilityMonitor21createPPMBatteryModelEv : 188 -> 196
~ __ZN23ApplePPMBatteryModel4RC26handleDynamicShutdownParamEv : 748 -> 740
CStrings:
+ "%s::%s:failed to get WeightedRa from bank %u\n"
+ "%s::%s:failed to get array entry for bank %u from key kBankBatteryDataDict\n"
+ "%s::%s:failed to get array entry for bank %u from key kLPEMDict\n"
- "%s::%s:failed to get array from key kBankBatteryDataDict\n"
- "%s::%s:failed to get array from key kLPEMDict\n"
```
