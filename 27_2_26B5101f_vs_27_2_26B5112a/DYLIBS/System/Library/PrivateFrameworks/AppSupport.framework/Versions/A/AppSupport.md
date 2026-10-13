## AppSupport

> `/System/Library/PrivateFrameworks/AppSupport.framework/Versions/A/AppSupport`

```diff

-2672.1.3.0.0
-  __TEXT.__text: 0x2bac8
+2672.1.5.0.0
+  __TEXT.__text: 0x2bc74
   __TEXT.__objc_methlist: 0x12a0
   __TEXT.__cstring: 0x4df7
   __TEXT.__const: 0x4dc0

   __AUTH.__objc_data: 0x5f0
   __AUTH.__data: 0x38
   __DATA.__objc_ivar: 0x244
-  __DATA.__data: 0x551
-  __DATA.__bss: 0x1f8
+  __DATA.__data: 0x591
+  __DATA.__bss: 0x208
   __DATA_DIRTY.__objc_data: 0x320
   __DATA_DIRTY.__data: 0x109
   __DATA_DIRTY.__bss: 0x158

   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
   Functions: 1173
-  Symbols:   2815
+  Symbols:   2817
   CStrings:  737
 
Symbols:
+ ___yieldRegisteredDatabases
+ ___yieldStateLock
Functions:
~ _CPSqliteDatabaseClose : 108 -> 168
~ _CPSqliteRegisterYieldNotifyBlock : 88 -> 128
~ _CPSqliteDatabaseSetShouldYieldWhenRequested : 280 -> 492
~ ___updateNotifyRegistration_block_invoke : 64 -> 180
```
