## com.apple.driver.AppleSEPManager

> `com.apple.driver.AppleSEPManager`

```diff

-928.60.4.0.0
-  __TEXT.__cstring: 0xd477
+928.60.5.0.0
+  __TEXT.__cstring: 0xd49d
   __TEXT.__const: 0x56c
-  __TEXT_EXEC.__text: 0x2f038
+  __TEXT_EXEC.__text: 0x2f0ec
   __TEXT_EXEC.__auth_stubs: 0x920
   __DATA.__data: 0x168
   __DATA.__common: 0xb08

   __DATA_CONST.__auth_got: 0x490
   __DATA_CONST.__got: 0x138
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 1777
+  Functions: 1779
   Symbols:   1891
-  CStrings:  1170
+  CStrings:  1172
 
CStrings:
+ "12111112122212121221122221111"
+ "_recv_ool_size <= sep_page_size * ds->getReceiveOolMaxPages()"
+ "_recv_ool_size > 0"
+ "_recv_ool_size >= sep_page_size * ds->getReceiveOolMinPages()"
+ "_send_ool_size <= sep_page_size * ds->getSendOolMaxPages()"
+ "_send_ool_size > 0"
+ "_send_ool_size >= sep_page_size * ds->getSendOolMinPages()"
- "1211111212221212122111111"
- "ool_size <= ds->getSepPageSize() * ds->getReceiveOolMaxPages()"
- "ool_size <= ds->getSepPageSize() * ds->getSendOolMaxPages()"
- "ool_size >= ds->getSepPageSize() * ds->getReceiveOolMinPages()"
- "ool_size >= ds->getSepPageSize() * ds->getSendOolMinPages()"
```
