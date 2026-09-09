## libsystem_platform.dylib

> `/usr/lib/system/libsystem_platform.dylib`

### Sections with Same Size but Changed Content

- `__AUTH_CONST.__const`
- `__DATA_DIRTY.__la_resolver`

```diff

 402.0.1.0.1
-  __TEXT.__text: 0x7d44
+  __TEXT.__text: 0x7c4c
   __TEXT.__resolver_help: 0x288
   __TEXT.__const: 0xb0
   __TEXT.__cstring: 0x844
-  __TEXT.__unwind_info: 0x2c8
+  __TEXT.__unwind_info: 0x340
   __TEXT.__stubs: 0x48
   __TEXT.__auth_stubs: 0x240
   __DATA_CONST.__got: 0x20
Functions:
~ _os_unfair_recursive_lock_unlock : 96 -> 84
~ __platform_strncmp : 76 -> 56
~ __os_once_callout : 112 -> 100
~ __os_alloc : 184 -> 172
~ __platform_strcpy : 560 -> 552
~ __simple_sfree : 148 -> 136
~ _dec : 780 -> 776
~ __simple_asl_log : 108 -> 96
~ __simple_asl_log_prog : 64 -> 52
~ __simple_asl_msg_set : 312 -> 300
~ __os_once_gate_wait : 400 -> 388
~ ___libplatform_init : 100 -> 88
~ __simple_getenv : 176 -> 172
~ __platform_memmove : 736 -> 720
~ __OSSpinLockLockSlow : 116 -> 104
~ _sys_dcache_flush : 12 -> 24
~ _os_log_simple_type_from_asl : 32 -> 24
~ __simple_vsnprintf : 176 -> 172
~ _OSAtomicFifoEnqueue : 104 -> 72
~ _OSAtomicFifoDequeue : 104 -> 72
~ __platform_memccpy : 1052 -> 1060
~ _makecontext : 296 -> 288
~ _setcontext : 104 -> 92
```
