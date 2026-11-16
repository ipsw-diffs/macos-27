## com.apple.driver.AppleDPDisplayTCON

> `com.apple.driver.AppleDPDisplayTCON`

```diff

-230.60.4.0.0
-  __TEXT.__cstring: 0x226b
+230.60.5.0.0
+  __TEXT.__cstring: 0x2240
   __TEXT.__const: 0x50
-  __TEXT_EXEC.__text: 0x10ae0
-  __TEXT_EXEC.__auth_stubs: 0x230
+  __TEXT_EXEC.__text: 0x10a98
+  __TEXT_EXEC.__auth_stubs: 0x220
   __DATA.__data: 0xc4
   __DATA.__common: 0x250
   __DATA_CONST.__mod_init_func: 0x48
   __DATA_CONST.__mod_term_func: 0x48
   __DATA_CONST.__const: 0x8ec0
   __DATA_CONST.__kalloc_type: 0x380
-  __DATA_CONST.__auth_got: 0x118
+  __DATA_CONST.__auth_got: 0x110
   __DATA_CONST.__got: 0x60
   __DATA_CONST.__auth_ptr: 0x10
   Functions: 489
-  Symbols:   854
-  CStrings:  254
+  Symbols:   853
+  CStrings:  253
 
Symbols:
- _clock_interval_to_deadline
Functions:
~ ____ZN12AppleDCPTCON14handleResponseEP20AFKEndpointInterfacePviyPKvm_block_invoke : 188 -> 192
~ ____ZN12AppleDCPTCON14enqueueCommandE17TCONAFKPacketTypeP18AppleTCONComponentjPhm_block_invoke : 720 -> 644
CStrings:
- "Error: TCON command timed out after %d ms\n"
```
