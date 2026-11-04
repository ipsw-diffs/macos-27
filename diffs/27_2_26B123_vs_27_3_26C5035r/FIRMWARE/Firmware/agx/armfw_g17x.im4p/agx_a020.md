## agx_a020

> `Firmware/agx/armfw_g17x.im4p/agx_a020`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3d8b0
+  __TEXT.__text: 0x3d8ec
   __TEXT.__gxf_code: 0x50a0
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1204
+  __TEXT.__const: 0x120c
   __TEXT._rtk_tunables: 0x740
   __TEXT._rtk_patchbay: 0x231
-  __TEXT.__cstring: 0x21ff
+  __TEXT.__cstring: 0x2249
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x24
   __DATA.__gxf_data: 0x8130

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 415
   Symbols:   175
-  CStrings:  231
+  CStrings:  232
 
Functions:
~ sub_fffffc00000068a0 : 5052 -> 5076
~ sub_fffffc0000008d00 -> sub_fffffc0000008d18 : 916 -> 924
~ sub_fffffc000000a14c -> sub_fffffc000000a16c : 680 -> 672
~ sub_fffffc000000c62c -> sub_fffffc000000c644 : 10700 -> 10656
~ sub_fffffc000000eff8 -> sub_fffffc000000efe4 : 2272 -> 2264
~ sub_fffffc000000f8d8 -> sub_fffffc000000f8bc : 340 -> 324
~ sub_fffffc000000fa2c -> sub_fffffc000000fa00 : 1588 -> 1544
~ sub_fffffc000001035c -> sub_fffffc0000010304 : 9824 -> 9756
~ sub_fffffc000001cd04 -> sub_fffffc000001cc68 : 3240 -> 3136
~ sub_fffffc0000021ed8 -> sub_fffffc0000021dd4 : 2452 -> 2460
~ sub_fffffc0000027bc8 -> sub_fffffc0000027acc : 1784 -> 1812
~ sub_fffffc00000282c0 -> sub_fffffc00000281e0 : 8196 -> 8180
~ sub_fffffc000002a2c4 -> sub_fffffc000002a1d4 : 2124 -> 2424
~ sub_fffffc000003d76c -> sub_fffffc000003d7a8 : 324 -> 332
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:27:21"
- "Oct 14 2026 23:21:41"
```
