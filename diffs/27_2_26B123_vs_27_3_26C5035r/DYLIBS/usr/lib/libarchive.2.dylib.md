## libarchive.2.dylib

> `/usr/lib/libarchive.2.dylib`

```diff

-182.40.6.0.0
-  __TEXT.__text: 0xe3460
+182.60.2.0.0
+  __TEXT.__text: 0xe3660
   __TEXT.__const: 0x9334
   __TEXT.__cstring: 0x9e64
-  __TEXT.__unwind_info: 0x2228
+  __TEXT.__unwind_info: 0x2230
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0x1a10
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0xd48
-  __AUTH_CONST.__auth_got: 0x8e0
+  __AUTH_CONST.__auth_got: 0x900
   __DATA.__data: 0xc
   __DATA.__bss: 0x1438
   __DATA_DIRTY.__data: 0x4

   - /usr/lib/liblzma.5.dylib
   - /usr/lib/libxml2.2.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 2249
-  Symbols:   2535
+  Functions: 2250
+  Symbols:   2540
   CStrings:  1828
 
Symbols:
+ __qtn_proc_alloc
+ __qtn_proc_free
+ __qtn_proc_init_with_self
+ _cfcb
+ _copyfile_state_get
Functions:
~ _archive_write_disk_set_quarantine : 92 -> 156
~ _archive_write_disk_new : 260 -> 340
~ __archive_write_disk_free : 456 -> 480
~ _copy_metadata : 476 -> 544
~ _create_tempdatafork : 404 -> 472
~ _copy_xattrs : 856 -> 872
+ _cfcb
~ _set_xattrs : 576 -> 592
```
