## com.apple.filesystems.hfs.kext

> `com.apple.filesystems.hfs.kext`

```diff

-753.60.3.0.0
+753.60.5.0.0
   __TEXT.__const: 0x1ab0
-  __TEXT.__cstring: 0xadca
-  __TEXT_EXEC.__text: 0x4ec24
+  __TEXT.__cstring: 0xaf9f
+  __TEXT_EXEC.__text: 0x4ef3c
   __TEXT_EXEC.__auth_stubs: 0x1850
   __DATA.__data: 0x4d0
   __DATA.__common: 0x10

   __DATA_CONST.__auth_ptr: 0x8
   Functions: 510
   Symbols:   1569
-  CStrings:  878
+  CStrings:  886
 
Symbols:
+ _CreateExtentRecord.kalloc_type_view_309
+ _CreateExtentRecord.kalloc_type_view_340
+ _DeleteExtentRecord.kalloc_type_view_356
+ _DeleteExtentRecord.kalloc_type_view_374
+ _FindExtentRecord.kalloc_type_view_288
+ _UpdateExtentRecord.kalloc_type_view_1889
+ _UpdateExtentRecord.kalloc_type_view_1924
+ _cat_lookup_dirlink.kalloc_type_view_4135
+ _cat_lookup_dirlink.kalloc_type_view_4138
+ _cat_lookup_dirlink.kalloc_type_view_4176
+ _cat_lookup_dirlink.kalloc_type_view_4178
- _CreateExtentRecord.kalloc_type_view_288
- _CreateExtentRecord.kalloc_type_view_319
- _DeleteExtentRecord.kalloc_type_view_335
- _DeleteExtentRecord.kalloc_type_view_353
- _FindExtentRecord.kalloc_type_view_267
- _UpdateExtentRecord.kalloc_type_view_1868
- _UpdateExtentRecord.kalloc_type_view_1903
- _cat_lookup_dirlink.kalloc_type_view_4125
- _cat_lookup_dirlink.kalloc_type_view_4128
- _cat_lookup_dirlink.kalloc_type_view_4166
- _cat_lookup_dirlink.kalloc_type_view_4168
Functions:
~ _InsertKeyRecord : 424 -> 488
~ _BTIterateRecord : 1796 -> 1988
~ _BTIterateRecords : 1844 -> 2072
~ _BTReloadData : 264 -> 312
~ _hfs_swap_BTNode : 5812 -> 5976
~ _builddesc : 520 -> 516
~ _ExtendBTree : 1140 -> 1160
~ _FindExtentRecord : 560 -> 640
CStrings:
+ "\"hfs_swap_BTNode: header node has %d records, should be 3\\n\" @%s:%d"
+ "\"hfs_swap_BTNode: map node has %d records, should be 1\\n\" @%s:%d"
+ "BTIterateRecord"
+ "BTIterateRecords"
+ "FindExtentRecord: invalid extent (startBlock %u, blockCount %u, totalBlocks %u)\n"
+ "hfs: %s() found mismatched sibling node on volume %s: found kind=%d, height=%u; expected kind=%d, height=%u\n"
+ "hfs_swap_BTNode: header node has %d records, should be 3\n"
+ "hfs_swap_BTNode: map node has %d records, should be 1\n"
```
