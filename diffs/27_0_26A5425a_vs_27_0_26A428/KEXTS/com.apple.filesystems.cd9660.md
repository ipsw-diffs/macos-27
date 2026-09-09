## com.apple.filesystems.cd9660

> `com.apple.filesystems.cd9660`

```diff

 46.0.0.0.0
   __TEXT.__cstring: 0x42a
   __TEXT.__const: 0x1016
-  __TEXT_EXEC.__text: 0x5314
+  __TEXT_EXEC.__text: 0x53dc
   __TEXT_EXEC.__auth_stubs: 0x5c0
   __DATA.__data: 0xd10
   __DATA.__common: 0x50
Functions:
~ _cd9660_blktooff : 80 -> 84
~ _cd9660_offtoblk : 80 -> 84
~ _cd9660_blockmap : 220 -> 224
~ _cd9660_lookup : 2024 -> 2028
~ _cd9660_blkatoff : 212 -> 216
~ _cd9660_hashinit : 112 -> 116
~ _cd9660_hashfree : 72 -> 76
~ _cd9660_get_hashed_node : 468 -> 472
~ _cd9660_ihashrem : 88 -> 92
~ _cd9660_reclaim : 164 -> 168
~ _cd9660_defattr : 356 -> 360
~ _cd9660_deftstamp : 256 -> 260
~ _cd9660_tstamp_conv17 : 148 -> 152
~ _cd9660_rrip_analyze : 72 -> 76
~ _cd9660_rrip_loop : 644 -> 648
~ _cd9660_rrip_getname : 148 -> 152
~ _cd9660_rrip_defname : 148 -> 152
~ _cd9660_rrip_getsymname : 100 -> 104
~ _cd9660_rrip_offset : 192 -> 196
~ _cd9660_rrip_tstamp : 304 -> 308
~ _cd9660_rrip_altname : 528 -> 532
~ _cd9660_rrip_slink : 872 -> 876
~ _ucsfntrans : 320 -> 324
~ _cd9660_mount : 2112 -> 2116
~ _cd9660_unmount : 156 -> 160
~ _cd9660_root : 136 -> 140
~ _cd9660_vfs_getattr : 268 -> 272
~ _cd9660_vget : 96 -> 100
~ _cd9660_vptofh : 100 -> 104
~ _cd9660_vget_internal : 1904 -> 1908
~ _cd9660_statfs : 100 -> 104
~ _cd9660_find_video_dir : 284 -> 288
~ _cd9660_phys_device : 240 -> 244
~ _cd9660_getattr : 412 -> 416
~ _cd9660_readlink : 344 -> 348
~ _cd9660_read : 1068 -> 1072
~ _cd9660_readdir : 1148 -> 1152
~ _iso_uiodir : 184 -> 188
~ _iso_shipdir : 216 -> 220
~ _cd9660_strategy : 68 -> 72
~ _cd9660_pathconf : 224 -> 228
~ _cd9660_pagein : 420 -> 424
~ _cd9660_rmdir : 28 -> 32
~ _cd9660_xa_init : 264 -> 268
~ _cd9660_xa_read : 164 -> 168
~ _cd9660_xa_read_common : 560 -> 564
~ _cd9660_module_start : 184 -> 188
~ _cd9660_module_stop : 52 -> 56
~ _cd9660_xa_pagein : 336 -> 340
~ cd9660_xa_pagein.cold.1 : 48 -> 52
```
