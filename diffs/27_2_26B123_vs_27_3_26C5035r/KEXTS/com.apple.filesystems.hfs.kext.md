## com.apple.filesystems.hfs.kext

> `com.apple.filesystems.hfs.kext`

```diff

-753.41.1.0.0
+753.60.3.0.0
   __TEXT.__const: 0x1ab0
-  __TEXT.__cstring: 0xac58
-  __TEXT_EXEC.__text: 0x4eb28
+  __TEXT.__cstring: 0xadca
+  __TEXT_EXEC.__text: 0x4ec24
   __TEXT_EXEC.__auth_stubs: 0x1850
   __DATA.__data: 0x4d0
   __DATA.__common: 0x10

   __DATA_CONST.__auth_ptr: 0x8
   Functions: 510
   Symbols:   1569
-  CStrings:  872
+  CStrings:  878
 
Symbols:
+ _cat_check_link_ancestry.kalloc_type_view_1909
+ _cat_check_link_ancestry.kalloc_type_view_1936
+ _cat_createlink.kalloc_type_view_2241
+ _cat_createlink.kalloc_type_view_2316
+ _cat_getentriesattr.kalloc_type_view_2662
+ _cat_getentriesattr.kalloc_type_view_2783
+ _cat_lookup_dirlink.kalloc_type_view_4125
+ _cat_lookup_dirlink.kalloc_type_view_4128
+ _cat_lookup_dirlink.kalloc_type_view_4168
+ _cat_lookup_lastlink.kalloc_type_view_2120
+ _cat_lookup_lastlink.kalloc_type_view_2199
+ _cat_lookup_siblinglinks.kalloc_type_view_2065
+ _cat_lookup_siblinglinks.kalloc_type_view_2096
+ _cat_lookuplink.kalloc_type_view_2021
+ _cat_lookuplink.kalloc_type_view_2045
+ _cat_rename.kalloc_type_view_1437
+ _cat_resolvelink.kalloc_type_view_3600
+ _cat_resolvelink.kalloc_type_view_3622
+ _cat_update_siblinglinks.kalloc_type_view_1992
+ _cat_update_siblinglinks.kalloc_type_view_2002
+ _getkey.kalloc_type_view_3665
+ _getkey.kalloc_type_view_3668
+ _getkey.kalloc_type_view_3702
+ _getkey.kalloc_type_view_3703
- _cat_check_link_ancestry.kalloc_type_view_1907
- _cat_check_link_ancestry.kalloc_type_view_1934
- _cat_createlink.kalloc_type_view_2239
- _cat_createlink.kalloc_type_view_2314
- _cat_getentriesattr.kalloc_type_view_2660
- _cat_getentriesattr.kalloc_type_view_2781
- _cat_lookup_dirlink.kalloc_type_view_4123
- _cat_lookup_dirlink.kalloc_type_view_4126
- _cat_lookup_dirlink.kalloc_type_view_4164
- _cat_lookup_lastlink.kalloc_type_view_2118
- _cat_lookup_lastlink.kalloc_type_view_2197
- _cat_lookup_siblinglinks.kalloc_type_view_2063
- _cat_lookup_siblinglinks.kalloc_type_view_2094
- _cat_lookuplink.kalloc_type_view_2019
- _cat_lookuplink.kalloc_type_view_2043
- _cat_rename.kalloc_type_view_1431
- _cat_resolvelink.kalloc_type_view_3598
- _cat_resolvelink.kalloc_type_view_3620
- _cat_update_siblinglinks.kalloc_type_view_1990
- _cat_update_siblinglinks.kalloc_type_view_2000
- _getkey.kalloc_type_view_3663
- _getkey.kalloc_type_view_3666
- _getkey.kalloc_type_view_3700
- _getkey.kalloc_type_view_3701
Functions:
~ _BTSearchRecord : 988 -> 992
~ _BTIterateRecord : 1792 -> 1796
~ _hfs_swap_BTNode : 5600 -> 5812
~ _cat_rename : 1708 -> 1740
CStrings:
+ "\"hfs_swap_HFSPlusBTInternalNode: catalog file record #%d %s\\n\" @%s:%d"
+ "\"hfs_swap_HFSPlusBTInternalNode: catalog folder record #%d has extra space after it\\n\" @%s:%d"
+ "\"hfs_swap_HFSPlusBTInternalNode: catalog thread record #%d has extra space after it\\n\" @%s:%d"
+ "has extra space"
+ "hfs_swap_HFSPlusBTInternalNode: catalog file record #%d %s\n"
+ "hfs_swap_HFSPlusBTInternalNode: catalog folder record #%d has extra space after it\n"
+ "hfs_swap_HFSPlusBTInternalNode: catalog thread record #%d has extra space after it\n"
+ "too big"
- "\"hfs_swap_HFSPlusBTInternalNode: catalog file record #%d too big\\n\" @%s:%d"
- "hfs_swap_HFSPlusBTInternalNode: catalog file record #%d too big\n"
```
