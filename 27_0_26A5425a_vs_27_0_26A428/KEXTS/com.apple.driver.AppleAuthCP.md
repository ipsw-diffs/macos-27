## com.apple.driver.AppleAuthCP

> `com.apple.driver.AppleAuthCP`

```diff

 186.0.0.0.0
   __TEXT.__const: 0x7c
-  __TEXT.__cstring: 0x2b50
+  __TEXT.__cstring: 0x2cc2
   __TEXT.__os_log: 0x16da
-  __TEXT_EXEC.__text: 0x1ae98
+  __TEXT_EXEC.__text: 0x1bb40
   __TEXT_EXEC.__auth_stubs: 0x490
   __DATA.__data: 0x188
   __DATA.__common: 0x240

   __DATA_CONST.__auth_got: 0x248
   __DATA_CONST.__got: 0xd0
   __DATA_CONST.__auth_ptr: 0x18
-  Functions: 635
-  Symbols:   1235
-  CStrings:  457
+  Functions: 637
+  Symbols:   1237
+  CStrings:  463
 
Symbols:
+ _ZN16AppleAuthCPRelay28_processDeferredCommandGatedEv
+ __ZN16AppleAuthCPRelay28_processDeferredCommandGatedEv
CStrings:
+ "%s:%s No signature found for the associated challenge. Removing stored info and requesting new signature \n"
+ "%s:%s Received challenge different than what we have stored. Removing stored info and requesting new signature\n"
+ "%s:%s invalid data received for CMD=0x%x\n"
+ "%s:%s no dictionary received for CMD=0x%x\n"
+ "%s:%s processing deferred CMD=0x%x \n"
+ "_processDeferredCommandGated"
```
