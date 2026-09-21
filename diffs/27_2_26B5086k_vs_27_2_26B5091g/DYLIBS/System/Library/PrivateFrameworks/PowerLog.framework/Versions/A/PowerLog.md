## PowerLog

> `/System/Library/PrivateFrameworks/PowerLog.framework/Versions/A/PowerLog`

```diff

-3486.40.92.0.0
-  __TEXT.__text: 0x1bfbc
+3486.40.99.0.0
+  __TEXT.__text: 0x1bff4
   __TEXT.__objc_methlist: 0x12dc
   __TEXT.__const: 0x1d8
-  __TEXT.__gcc_except_tab: 0x694
+  __TEXT.__gcc_except_tab: 0x66c
   __TEXT.__cstring: 0x211e
   __TEXT.__oslogstring: 0x38a2
-  __TEXT.__unwind_info: 0xa00
+  __TEXT.__unwind_info: 0xa08
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_superrefs: 0x50
   __DATA_CONST.__objc_arraydata: 0x178
   __DATA_CONST.__got: 0x188
-  __AUTH_CONST.__const: 0x8d0
+  __AUTH_CONST.__const: 0x8f0
   __AUTH_CONST.__cfstring: 0x25e0
   __AUTH_CONST.__objc_const: 0x2000
   __AUTH_CONST.__objc_intobj: 0x3d8

   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x500
+  __AUTH.__objc_data: 0x488
   __DATA.__objc_ivar: 0x1ac
-  __DATA.__data: 0x60
+  __DATA.__data: 0x64
   __DATA.__bss: 0x90
-  __DATA_DIRTY.__objc_data: 0xf0
-  __DATA_DIRTY.__bss: 0x71
+  __DATA_DIRTY.__objc_data: 0x168
+  __DATA_DIRTY.__bss: 0x74
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 796
-  Symbols:   1522
+  Functions: 798
+  Symbols:   1525
   CStrings:  640
 
Symbols:
+ PLClientPPSBatchSize.onceToken
+ PLClientPPSBatchSize.sPPSBatchSize
+ ___PLClientPPSBatchSize_block_invoke
Functions:
~ -[PLClientLogger addToBatchedTaskCacheForType:forClientID:forKey:withPayload:] : 1272 -> 1176
+ ___PLClientPPSBatchSize_block_invoke
+ -[PLClientLogger addToBatchedTaskCacheForType:forClientID:forKey:withPayload:].cold.2
```
