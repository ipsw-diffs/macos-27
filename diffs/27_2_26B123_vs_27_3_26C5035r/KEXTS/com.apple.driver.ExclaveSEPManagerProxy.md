## com.apple.driver.ExclaveSEPManagerProxy

> `com.apple.driver.ExclaveSEPManagerProxy`

```diff

-928.40.6.0.0
+928.60.4.0.0
   __TEXT.__const: 0xe0
-  __TEXT.__cstring: 0x875
-  __TEXT_EXEC.__text: 0x1d80
-  __TEXT_EXEC.__auth_stubs: 0x2b0
+  __TEXT.__cstring: 0x98c
+  __TEXT_EXEC.__text: 0x221c
+  __TEXT_EXEC.__auth_stubs: 0x2c0
   __DATA.__data: 0xc4
   __DATA.__common: 0x40
   __DATA.__bss: 0x10
   __DATA_CONST.__mod_init_func: 0x8
   __DATA_CONST.__mod_term_func: 0x8
-  __DATA_CONST.__const: 0xa60
+  __DATA_CONST.__const: 0xab0
   __DATA_CONST.__kalloc_type: 0x40
-  __DATA_CONST.__auth_got: 0x158
+  __DATA_CONST.__auth_got: 0x160
   __DATA_CONST.__got: 0x28
-  Functions: 69
-  Symbols:   394
-  CStrings:  43
+  Functions: 75
+  Symbols:   400
+  CStrings:  45
 
Symbols:
+ _IOSleep
+ __ZN22ExclaveSEPManagerProxy15sleepThreadCallEPvS0_
+ ____ZL14ready_to_sleepv_block_invoke
+ ____ZL23report_power_assertionsv_block_invoke
+ ____ZN22ExclaveSEPManagerProxy15sleepThreadCallEPvS0__block_invoke
+ _exclavesepmanager_exclavesepmanagerproxyinterface_readytosleep
+ _exclavesepmanager_exclavesepmanagerproxyinterface_reportpowerassertions
- ____ZL21outbox_not_empty_callv_block_invoke
CStrings:
+ "!sleepThreadActive"
+ "121111121222121211111121112"
+ "ExclaveSEPManagerProxy: power off waiting for %u ms on %u power assertion(s), see ExclaveSEPManager log for holders\n"
+ "Powering down ExclaveSEPManager now\n"
+ "TB_ERROR_SUCCESS == exclavesepmanager_exclavesepmanagerproxyinterface_initiatepowertransition(&client, ps,^ (bool tb_ret) { ready_to_sleep = tb_ret; })"
+ "TB_ERROR_SUCCESS == exclavesepmanager_exclavesepmanagerproxyinterface_outboxnotemptyinterrupt(&client)"
+ "TB_ERROR_SUCCESS == exclavesepmanager_exclavesepmanagerproxyinterface_readytosleep(&client, ^ (bool ret) { ready = ret; })"
+ "TB_ERROR_SUCCESS == exclavesepmanager_exclavesepmanagerproxyinterface_reportpowerassertions(&client, ^ (uint32_t ret) { count = ret; })"
- "12111112122212121111112211"
- "Powering down ExclaveSEPManager now"
- "TB_ERROR_SUCCESS == exclavesepmanager_exclavesepmanagerproxyinterface_initiatepowertransition(&client, ps,^ (uint32_t tb_ret) { initiate_pt_ret = tb_ret; })"
- "TB_ERROR_SUCCESS == exclavesepmanager_exclavesepmanagerproxyinterface_outboxnotemptyinterrupt(&client, ^ (uint32_t ret) { message_count = ret; })"
- "message_count != __UINT32_MAX__"
- "outstanding_messages >= message_count"
```
