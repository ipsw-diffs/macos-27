## MMCS

> `/System/Library/PrivateFrameworks/MMCS.framework/Versions/A/MMCS`

```diff

-2700.112.0.0.0
-  __TEXT.__text: 0x7ee1c
+2730.0.0.0.0
+  __TEXT.__text: 0x7faf4
   __TEXT.__objc_methlist: 0xbe0
-  __TEXT.__const: 0x9ac
+  __TEXT.__const: 0x9bc
   __TEXT.__oslogstring: 0x442c
-  __TEXT.__cstring: 0x17815
+  __TEXT.__cstring: 0x178ce
   __TEXT.__gcc_except_tab: 0x38c
-  __TEXT.__unwind_info: 0x20f0
+  __TEXT.__unwind_info: 0x2170
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x51e0
+  __DATA_CONST.__const: 0x51f0
   __DATA_CONST.__objc_classlist: 0x28
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x898
   __DATA_CONST.__objc_superrefs: 0x28
   __DATA_CONST.__got: 0x2c8
-  __AUTH_CONST.__const: 0x3028
+  __AUTH_CONST.__const: 0x3040
   __AUTH_CONST.__cfstring: 0xce60
   __AUTH_CONST.__objc_const: 0x11f0
-  __AUTH_CONST.__auth_got: 0xde8
+  __AUTH_CONST.__auth_got: 0xe38
   __DATA.__objc_ivar: 0xa0
   __DATA.__data: 0x50
   __DATA.__bss: 0x68

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 2433
-  Symbols:   3504
-  CStrings:  2987
+  Functions: 2459
+  Symbols:   3539
+  CStrings:  2994
 
Symbols:
+ _CFRunLoopAddObserver
+ _CFRunLoopObserverCreate
+ _CFRunLoopRemoveObserver
+ _MMCSResetEngineInitializedState
+ __mmcs_compute_signature_and_register_item_with_descriptor
+ __mmcs_duplicate_registered_file
+ __mmcs_engine_append_requests_description
+ __mmcs_engine_cancel_requests_if_not_closing
+ __mmcs_engine_destroy_begin_closing
+ __mmcs_engine_is_active
+ __mmcs_engine_set_metrics_enabled
+ __mmcs_get_items
+ __mmcs_get_registered_items
+ __mmcs_put_items
+ __mmcs_put_section_with_items
+ __mmcs_register_files_with_options
+ __mmcs_register_items
+ __mmcs_registered_item_count
+ __mmcs_unregister_files_in_working_directory
+ __mmcs_update_items
+ _class_getSuperclass
+ _dispatch_async_f
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
+ _dispatch_sync_f
+ _mmcs_dispatch_queue_is_concurrent
+ _mmcs_perform_dispatch_serial_queue_key
+ _mmcs_perform_dispatch_target_async_f
+ _mmcs_perform_dispatch_target_is_current
+ _mmcs_perform_dispatch_target_queue_key
+ _mmcs_perform_dispatch_target_sync_f
+ _mmcs_perform_run_loop_async_f_fire
+ _mmcs_perform_run_loop_sync_f_trampoline
+ _mmcs_perform_run_loop_target_async_f
+ _mmcs_perform_run_loop_target_is_current
+ _mmcs_perform_run_loop_target_sync_f
+ _mmcs_perform_target_assert_current
+ _mmcs_perform_target_sync_f
+ _objc_getClass
+ _object_getClass
- _MMCSDuplicateRegisteredfile2
- _mmcs_perform_dispatch_target_assert_current_debug
- _mmcs_perform_dispatch_target_assert_not_current_debug
- _mmcs_perform_run_loop_target_assert_current_debug
- _mmcs_perform_run_loop_target_assert_not_current_debug
CStrings:
+ "OS_dispatch_queue_concurrent"
+ "_mmcs_get_items"
+ "_mmcs_register_items"
+ "_mmcs_update_items"
+ "function"
+ "mmcs_dispatch_queue_is_concurrent"
+ "mmcs_perform_target: current thread is not exclusively confined"
+ "mmcs_perform_target_sync_f"
+ "mmcs_util.m"
+ "target"
- "mmcs_get_items"
- "mmcs_register_items"
- "mmcs_update_items"
```
