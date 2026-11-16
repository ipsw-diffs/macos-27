## com.apple.filesystems.cd9660

> `com.apple.filesystems.cd9660`

```diff

-47.40.1.0.0
-  __TEXT.__cstring: 0x490
+47.60.2.0.0
+  __TEXT.__cstring: 0x59a
   __TEXT.__const: 0x1016
-  __TEXT_EXEC.__text: 0x5390
+  __TEXT_EXEC.__text: 0x54e8
   __TEXT_EXEC.__auth_stubs: 0x5c0
   __DATA.__data: 0xd10
   __DATA.__common: 0x50

   __DATA_CONST.__got: 0x20
   Functions: 90
   Symbols:   294
-  CStrings:  37
+  CStrings:  43
 
Symbols:
+ _cd9660_unmount.kalloc_type_view_788
+ _cd9660_vget_internal.kalloc_type_view_1509
+ _iso_mountfs.kalloc_type_view_532
+ _iso_mountfs.kalloc_type_view_740
- _cd9660_unmount.kalloc_type_view_757
- _cd9660_vget_internal.kalloc_type_view_1478
- _iso_mountfs.kalloc_type_view_511
- _iso_mountfs.kalloc_type_view_709
Functions:
~ _cd9660_rrip_attr : 60 -> 148
~ _cd9660_rrip_altname : 484 -> 588
~ _cd9660_mount : 2116 -> 2268
CStrings:
+ "cd9660: RRIP invalid NM flags 0x%x\n"
+ "cd9660: RRIP invalid NM length %d\n"
+ "cd9660: RRIP invalid NM length %d, flags 0x%x\n"
+ "cd9660: RRIP invalid PX length %d\n"
+ "cd9660: bad PVD root record len %d name_len %d\n"
+ "cd9660: bad SVD root record len %d name_len %d, ignoring Joliet\n"
```
