## com.apple.iokit.IOMobileGraphicsFamily-DCP

> `com.apple.iokit.IOMobileGraphicsFamily-DCP`

```diff

 700.50.97.9.0
-  __TEXT.__cstring: 0x5d24
+  __TEXT.__cstring: 0x5f86
   __TEXT.__const: 0x32e8
-  __TEXT_EXEC.__text: 0x2b06c
+  __TEXT_EXEC.__text: 0x2bb84
   __TEXT_EXEC.__auth_stubs: 0xef0
   __DATA.__data: 0xe8
   __DATA.__common: 0x2720
   __DATA.__bss: 0x38
   __DATA_CONST.__mod_init_func: 0x30
   __DATA_CONST.__mod_term_func: 0x30
-  __DATA_CONST.__const: 0x2d80
+  __DATA_CONST.__const: 0x2d88
   __DATA_CONST.__kalloc_type: 0x8c0
   __DATA_CONST.__kalloc_var: 0xf0
   __DATA_CONST.__auth_got: 0x778
   __DATA_CONST.__got: 0x130
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 798
-  Symbols:   1439
-  CStrings:  488
+  Functions: 801
+  Symbols:   1441
+  CStrings:  496
 
Symbols:
+ __ZN21IOMobileFramebufferAP26genlock_error_notify_gatedEy
+ __ZN31IOMobileFramebuffer_RemoteCalls15D577_callback__EPK12link_state_tP13link_stream_tPKvjPvj
CStrings:
+ "%s: dropped external_sync_error_notify message %llu\n"
+ "IOMFB: external_sync: pending notification found, delivering state=0x%llx\n"
+ "IOMFB: external_sync: userspace client registered for notifications\n"
+ "IOMFB: external_sync_error_notify_gated: delivered successfully to client %p\n"
+ "IOMFB: external_sync_error_notify_gated: no listeners registered, storing pending state=0x%llx\n"
+ "IOMFB: external_sync_error_notify_gated: sending to client %p\n"
+ "IOMFB: external_sync_error_notify_gated: state=0x%llx (late=%d expected_clock=%d incorrect_params=%d)\n"
+ "virtual void IOMobileFramebufferAP::genlock_error_notify_gated(uint64_t)"
```
