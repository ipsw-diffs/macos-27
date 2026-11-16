## libsystem_platform.dylib

> `/usr/lib/system/libsystem_platform.dylib`

```diff

-402.40.3.0.0
-  __TEXT.__text: 0x7c4c
+402.60.2.0.0
+  __TEXT.__text: 0x7cb0
   __TEXT.__resolver_help: 0x288
   __TEXT.__const: 0xb0
   __TEXT.__cstring: 0x844
-  __TEXT.__unwind_info: 0x340
+  __TEXT.__unwind_info: 0x348
   __TEXT.__stubs: 0x48
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__got: 0x0

   __TPRO_CONST.__data: 0x8
   - /usr/lib/system/libdyld.dylib
   - /usr/lib/system/libsystem_kernel.dylib
-  Functions: 278
-  Symbols:   320
+  Functions: 282
+  Symbols:   324
   CStrings:  68
 
Symbols:
+ _os_unfair_recursive_lock_assert_not_owned_by_self
+ _os_unfair_recursive_lock_assert_owned_by_self
+ _os_unfair_recursive_lock_lock
+ _os_unfair_recursive_lock_lock_with_flags
```
