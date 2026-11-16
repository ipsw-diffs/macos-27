## com.apple.filesystems.webdav

> `com.apple.filesystems.webdav`

```diff

-413.40.2.0.0
-  __TEXT.__cstring: 0x904
+413.60.1.0.1
+  __TEXT.__cstring: 0x90a
   __TEXT.__const: 0xd0
-  __TEXT_EXEC.__text: 0x5d04
-  __TEXT_EXEC.__auth_stubs: 0x790
+  __TEXT_EXEC.__text: 0x5d78
+  __TEXT_EXEC.__auth_stubs: 0x7b0
   __DATA.__data: 0x340
   __DATA.__common: 0x38
   __DATA.__bss: 0x818
   __DATA_CONST.__kalloc_type: 0x240
-  __DATA_CONST.__auth_got: 0x3c8
+  __DATA_CONST.__auth_got: 0x3d8
   __DATA_CONST.__got: 0x30
   Functions: 66
-  Symbols:   245
+  Symbols:   247
   CStrings:  62
 
Symbols:
+ _vfs_busy
+ _vfs_getvfs_with_vfsops
+ _vfs_unbusy
+ _webdav_associate_cachefile
+ _webdav_mount.kalloc_type_view_337
+ _webdav_mount.kalloc_type_view_468
+ _webdav_unmount.kalloc_type_view_549
+ _webdav_vnop_reclaim.kalloc_type_view_3846
+ _webdav_vnop_write.kalloc_type_view_2597
+ _webdav_vnop_write.kalloc_type_view_2718
- _vfs_getvfs
- _webdav_mount.kalloc_type_view_323
- _webdav_mount.kalloc_type_view_454
- _webdav_translate_ref
- _webdav_unmount.kalloc_type_view_535
- _webdav_vnop_reclaim.kalloc_type_view_3830
- _webdav_vnop_write.kalloc_type_view_2581
- _webdav_vnop_write.kalloc_type_view_2702
Functions:
~ _webdav_sysctl : 612 -> 656
~ _webdav_translate_ref -> _webdav_associate_cachefile : 136 -> 172
~ _webdav_vnop_open_locked : 584 -> 620
CStrings:
+ "webdav_sysctl: webdav_associate_cachefile() failed\n"
- "webdav_sysctl: webdav_translate_ref() failed\n"
```
