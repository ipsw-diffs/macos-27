## librdmacm.dylib

> `/usr/lib/rdma/librdmacm.dylib`

```diff

-112.40.17.0.0
-  __TEXT.__text: 0x5a64
-  __TEXT.__cstring: 0x322
+112.60.8.0.0
+  __TEXT.__text: 0x59c0
+  __TEXT.__cstring: 0x2bc
   __TEXT.__const: 0x68
   __TEXT.__unwind_info: 0x218
   __TEXT.__auth_stubs: 0x0

   __DATA.__data: 0x9c
   __DATA.__bss: 0x278
   __DATA.__common: 0x4
-  - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/rdma/libibverbs.dylib
-  Functions: 100
-  Symbols:   186
-  CStrings:  31
+  Functions: 99
+  Symbols:   180
+  CStrings:  28
 
Symbols:
+ _fcntl
+ _open
+ _poll
+ _write
- _IOConnectCallStructMethod
- _IOServiceGetMatchingService
- _IOServiceNameMatching
- _IOServiceOpen
- ___stderrp
- _fprintf
- _fwrite
- _kIOMainPortDefault
- _mach_task_self_
- _write_cmd
Functions:
~ _rdma_create_event_channel : 232 -> 116
- _write_cmd
~ _rdma_get_cm_event : 1224 -> 1296
CStrings:
+ "/dev/rdma_cm"
- "IOConnectCallStructMethod error 0x%x\n"
- "IORDMACM"
- "cannot find the IORDMACM service\n"
- "cannot open the IORDMACM service\n"
```
