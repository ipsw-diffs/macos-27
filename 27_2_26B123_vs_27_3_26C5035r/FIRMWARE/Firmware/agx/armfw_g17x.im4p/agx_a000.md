## agx_a000

> `Firmware/agx/armfw_g17x.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3d168
+  __TEXT.__text: 0x3d1a4
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
~ sub_fffffc0000006888 : 5052 -> 5076
~ sub_fffffc00000088e8 -> sub_fffffc0000008900 : 916 -> 924
~ sub_fffffc0000009d34 -> sub_fffffc0000009d54 : 680 -> 672
~ sub_fffffc000000c214 -> sub_fffffc000000c22c : 10700 -> 10656
~ sub_fffffc000000ebe0 -> sub_fffffc000000ebcc : 2272 -> 2264
~ sub_fffffc000000f4c0 -> sub_fffffc000000f4a4 : 340 -> 324
~ sub_fffffc000000f614 -> sub_fffffc000000f5e8 : 1588 -> 1544
~ sub_fffffc000000ff44 -> sub_fffffc000000feec : 9824 -> 9756
~ sub_fffffc000001c7f4 -> sub_fffffc000001c758 : 3240 -> 3136
~ sub_fffffc0000021854 -> sub_fffffc0000021750 : 2256 -> 2264
~ sub_fffffc0000027480 -> sub_fffffc0000027384 : 1784 -> 1812
~ sub_fffffc0000027b78 -> sub_fffffc0000027a98 : 8196 -> 8180
~ sub_fffffc0000029b7c -> sub_fffffc0000029a8c : 2124 -> 2424
~ sub_fffffc000003d024 -> sub_fffffc000003d060 : 332 -> 324
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:22:15"
- "Oct 14 2026 23:17:02"
```
