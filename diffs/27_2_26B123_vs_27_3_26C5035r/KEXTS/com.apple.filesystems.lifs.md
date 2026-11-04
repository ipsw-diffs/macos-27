## com.apple.filesystems.lifs

> `com.apple.filesystems.lifs`

```diff

-974.40.12.0.0
+974.60.5.0.0
   __TEXT.__os_log: 0x1fde
   __TEXT.__cstring: 0x29f1
   __TEXT.__const: 0x338
-  __TEXT_EXEC.__text: 0x20794
+  __TEXT_EXEC.__text: 0x20870
   __TEXT_EXEC.__auth_stubs: 0xfa0
   __DATA.__data: 0x528
   __DATA.__common: 0x130

   __DATA_CONST.__auth_got: 0x7d0
   __DATA_CONST.__got: 0x88
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 462
-  Symbols:   1330
+  Functions: 463
+  Symbols:   1331
   CStrings:  519
 
Symbols:
+ _add_sillyrename_entry.kalloc_type_view_2144
+ _add_sillyrename_entry.kalloc_type_view_2167
+ _cleanup_sillyrename_entries.kalloc_type_view_2265
+ _lifs_mark_setattr_supported
+ _lifs_mirror_mount_domount.kalloc_type_view_1331
+ _move_sillyrename_entries.kalloc_type_view_2239
- _add_sillyrename_entry.kalloc_type_view_2093
- _add_sillyrename_entry.kalloc_type_view_2116
- _cleanup_sillyrename_entries.kalloc_type_view_2214
- _lifs_mirror_mount_domount.kalloc_type_view_1229
- _move_sillyrename_entries.kalloc_type_view_2188
Functions:
~ _lifs_vnop_setattr : 1388 -> 1384
+ _lifs_mark_setattr_supported
```
