## com.apple.security.sandbox

> `com.apple.security.sandbox`

```diff

-3051.60.20.0.0
-  __TEXT.__os_log: 0x278f
-  __TEXT.__const: 0x20d17
-  __TEXT.__cstring: 0x7dc7
-  __TEXT_EXEC.__text: 0x52858
-  __TEXT_EXEC.__auth_stubs: 0x15d0
-  __DATA.__data: 0x3b0
-  __DATA.__bss: 0x7f19c
-  __DATA_CONST.__const: 0x4080
+3051.60.23.0.1
+  __TEXT.__os_log: 0x27c2
+  __TEXT.__const: 0x22877
+  __TEXT.__cstring: 0x7e31
+  __TEXT_EXEC.__text: 0x531b0
+  __TEXT_EXEC.__auth_stubs: 0x15e0
+  __DATA.__data: 0x400
+  __DATA.__bss: 0x8012c
+  __DATA_CONST.__const: 0x40d8
   __DATA_CONST.__kalloc_type: 0x1840
   __DATA_CONST.__kalloc_var: 0x550
-  __DATA_CONST.__auth_got: 0xae8
+  __DATA_CONST.__auth_got: 0xaf0
   __DATA_CONST.__got: 0x100
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 977
-  Symbols:   1964
-  CStrings:  1625
+  Functions: 981
+  Symbols:   1971
+  CStrings:  1630
 
Symbols:
+ ___check_is_storage_class_root_block_invoke
+ ___derive_private_folder_root_path_block_invoke
+ _ancestor_classification_count
+ _derive_private_folder_root_path
+ _free_queued_events.kalloc_type_view_1559
+ _get_appcontainer_root_path
+ _get_appprotection_identifier
+ _iterate_path_ancestors
+ _matches_component
+ _mount_info_alloc.kalloc_type_view_1872
+ _mount_info_release.kalloc_type_view_1907
+ _pending_approval_entry_create.kalloc_type_view_1815
+ _pending_approval_entry_create.kalloc_type_view_1822
+ _pending_approval_entry_release.kalloc_type_view_1794
+ _private_folders_enabled
+ _sandcastle_init.kalloc_type_view_3616
+ _schedule_microstackshot.kalloc_type_view_1753
+ _schedule_microstackshot.kalloc_type_view_1781
+ _schedule_microstackshot.kalloc_type_view_1804
+ _storage_class_for_vnode.kalloc_type_view_3789
+ _storage_class_for_vnode.kalloc_type_view_3800
+ _submit_queued_events_to_sandboxd.kalloc_type_view_1643
+ _sysctl__security_mac_sandbox_private_folders_enabled
+ _sysctl_sandbox_private_folders_enabled
+ _thread_ustackshot_destroy.kalloc_type_view_1719
+ _thread_ustackshot_destroy.kalloc_type_view_1722
- _check_role_account_home_access
- _ds_store_hack_check
- _free_queued_events.kalloc_type_view_1555
- _get_discriminator_for_category
- _mount_info_alloc.kalloc_type_view_1685
- _mount_info_release.kalloc_type_view_1720
- _pending_approval_entry_create.kalloc_type_view_1685
- _pending_approval_entry_create.kalloc_type_view_1692
- _pending_approval_entry_release.kalloc_type_view_1664
- _sandcastle_init.kalloc_type_view_3436
- _sb_allow_prompt
- _schedule_microstackshot.kalloc_type_view_1749
- _schedule_microstackshot.kalloc_type_view_1777
- _schedule_microstackshot.kalloc_type_view_1800
- _storage_class_for_vnode.kalloc_type_view_3602
- _storage_class_for_vnode.kalloc_type_view_3613
- _submit_queued_events_to_sandboxd.kalloc_type_view_1639
- _thread_ustackshot_destroy.kalloc_type_view_1715
- _thread_ustackshot_destroy.kalloc_type_view_1718
CStrings:
+ "2111112111111111111222221333313331111112222222222222222"
+ "com.apple.secd"
+ "failed to identify private folder root for %s: #%d"
+ "i40@?0^{vnode=}8r*16Q24^B32"
+ "kTCCServiceSystemPolicyPrivateFolders"
+ "private_folders_enabled"
- "211111211111111111122222133331333111111222222222222222"
```
