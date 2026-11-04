## agx_a000

> `Firmware/agx/armfw_g16c.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x51dec
+  __TEXT.__text: 0x5208c
   __TEXT.__gxf_code: 0x50c0
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x132c
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x6a0
-  __TEXT.__cstring: 0x2f91
+  __TEXT.__cstring: 0x2fdb
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x20
   __DATA.__gxf_data: 0x8130

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 498
   Symbols:   173
-  CStrings:  307
+  CStrings:  308
 
Functions:
~ sub_fffffc00000058cc : 5304 -> 5328
~ sub_fffffc0000010d4c -> sub_fffffc0000010d64 : 672 -> 680
~ sub_fffffc0000013a10 -> sub_fffffc0000013a30 : 11436 -> 11452
~ sub_fffffc0000017294 -> sub_fffffc00000172c4 : 324 -> 340
~ sub_fffffc00000173d8 -> sub_fffffc0000017418 : 2056 -> 2100
~ sub_fffffc0000017f10 -> sub_fffffc0000017f7c : 10156 -> 10272
~ sub_fffffc0000028650 -> sub_fffffc0000028730 : 3012 -> 3116
~ sub_fffffc000003245c -> sub_fffffc00000325a4 : 2300 -> 2292
~ sub_fffffc0000039878 -> sub_fffffc00000399b8 : 1528 -> 1556
~ sub_fffffc0000039e70 -> sub_fffffc0000039fcc : 7664 -> 7680
~ sub_fffffc000003bc60 -> sub_fffffc000003bdcc : 2064 -> 2372
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:11:42"
- "Oct 14 2026 23:07:13"
```
