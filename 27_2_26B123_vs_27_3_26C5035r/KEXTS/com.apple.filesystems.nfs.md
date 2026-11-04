## com.apple.filesystems.nfs

> `com.apple.filesystems.nfs`

```diff

-356.40.6.0.0
-  __TEXT.__cstring: 0x9c53
+356.60.3.0.0
+  __TEXT.__cstring: 0x9cc6
   __TEXT.__const: 0x39c
-  __TEXT_EXEC.__text: 0x9db40
+  __TEXT_EXEC.__text: 0x9dd04
   __TEXT_EXEC.__auth_stubs: 0x1530
   __DATA.__data: 0xf00
   __DATA.__common: 0xee4

   __DATA_CONST.__got: 0xa8
   __DATA_CONST.__auth_ptr: 0x8
   Functions: 1000
-  Symbols:   1619
-  CStrings:  1157
+  Symbols:   1620
+  CStrings:  1159
 
Symbols:
+ _nfs4_create_rpc.kalloc_type_view_7751
+ _nfs4_create_rpc.kalloc_type_view_7882
+ _nfs4_vnop_rmdir.kalloc_type_view_8211
+ _nfs4_vnop_rmdir.kalloc_type_view_8248
+ _nfs_mountinfo_callout
- _nfs4_create_rpc.kalloc_type_view_7729
- _nfs4_create_rpc.kalloc_type_view_7860
- _nfs4_vnop_rmdir.kalloc_type_view_8189
- _nfs4_vnop_rmdir.kalloc_type_view_8226
CStrings:
+ "%s: %d: clamping nb_validend %lld to EOF: boff %lld, nb_endio %lld, nb_bufsize %u, n_size %llu"
+ "nfs_buf_read_finish"
```
