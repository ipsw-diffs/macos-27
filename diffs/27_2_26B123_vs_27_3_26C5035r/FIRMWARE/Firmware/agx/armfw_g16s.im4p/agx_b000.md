## agx_b000

> `Firmware/agx/armfw_g16s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x51990
+  __TEXT.__text: 0x51c38
   __TEXT.__gxf_code: 0x50c0
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x132c
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x6a0
-  __TEXT.__cstring: 0x2f23
+  __TEXT.__cstring: 0x2f6d
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x20
   __DATA.__gxf_data: 0x8130

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 497
   Symbols:   173
-  CStrings:  305
+  CStrings:  306
 
Functions:
~ sub_fffffc00000058a0 : 5244 -> 5268
~ sub_fffffc0000010b1c -> sub_fffffc0000010b34 : 672 -> 680
~ sub_fffffc00000137d0 -> sub_fffffc00000137f0 : 11436 -> 11452
~ sub_fffffc000001647c -> sub_fffffc00000164ac : 2892 -> 2900
~ sub_fffffc0000016fc8 -> sub_fffffc0000017000 : 324 -> 340
~ sub_fffffc000001710c -> sub_fffffc0000017154 : 2056 -> 2100
~ sub_fffffc0000017c44 -> sub_fffffc0000017cb8 : 10156 -> 10272
~ sub_fffffc0000028388 -> sub_fffffc0000028470 : 3012 -> 3116
~ sub_fffffc0000032224 -> sub_fffffc0000032374 : 2204 -> 2196
~ sub_fffffc000003941c -> sub_fffffc0000039564 : 1528 -> 1556
~ sub_fffffc0000039a14 -> sub_fffffc0000039b78 : 7664 -> 7680
~ sub_fffffc000003b804 -> sub_fffffc000003b978 : 2064 -> 2372
~ sub_fffffc0000051850 -> sub_fffffc0000051af8 : 320 -> 328
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:16:29"
- "Oct 14 2026 23:11:44"
```
