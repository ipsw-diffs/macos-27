## com.apple.EXBrightKext

> `com.apple.EXBrightKext`

```diff

-2300.60.30.501.1
+2300.60.34.0.2
   __TEXT.__const: 0x120
-  __TEXT.__cstring: 0x4ed5
-  __TEXT_EXEC.__text: 0x18318
-  __TEXT_EXEC.__auth_stubs: 0x750
+  __TEXT.__cstring: 0x5068
+  __TEXT_EXEC.__text: 0x188d0
+  __TEXT_EXEC.__auth_stubs: 0x760
   __DATA.__data: 0xd8
   __DATA.__common: 0x130
   __DATA.__bss: 0x2
   __DATA_CONST.__mod_init_func: 0x30
   __DATA_CONST.__mod_term_func: 0x30
-  __DATA_CONST.__const: 0x2e58
+  __DATA_CONST.__const: 0x2ea8
   __DATA_CONST.__kalloc_type: 0x1c0
-  __DATA_CONST.__auth_got: 0x3a8
+  __DATA_CONST.__auth_got: 0x3b0
   __DATA_CONST.__got: 0x90
-  Functions: 604
-  Symbols:   1058
-  CStrings:  326
+  Functions: 612
+  Symbols:   1063
+  CStrings:  333
 
Symbols:
+ __ZN10DeviceTree15loadDataFromKeyIjEEbPKcRT_
+ __ZN12EXBrightKext23regularSleepWakeHandlerEPvS0_jP9IOServiceS0_m
+ ____ZN12EXBrightKext23regularSleepWakeHandlerEPvS0_jP9IOServiceS0_m_block_invoke
+ _exbrightkextinterface_exbrightkextinterface_enablesilhealthstrictmode
+ _registerSleepWakeInterest
CStrings:
+ "\"TB_ASSERT: \" \"(server->enablesilhealthstrictmode != ((void*)0)) && \\\"implementation for enableSILHealthStrictMode is not present\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "1211111212221212111111121211111111121111112222212111111112"
+ "[%s] [ERR] [StrictMode] Waking up from sleep, enabling - failed! (%u)\n"
+ "[%s] [StrictMode] Not applying!\n"
+ "[%s] [StrictMode] Waking up from sleep, enabling\n"
+ "[%s] [StrictMode] _strictModeOnWake=%d\n"
+ "[%s] [upcall] SIL Hint\n"
+ "strict-mode-on-wake"
- "12111112122212121111111211111111121111112222212111111112"
```
