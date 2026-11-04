## agx_b010

> `Firmware/agx/armfw_g17p.im4p/agx_b010`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3be90
+  __TEXT.__text: 0x3beb4
   __TEXT.__gxf_code: 0x5150
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1d3c
+  __TEXT.__const: 0x1d44
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x6a0
-  __TEXT.__cstring: 0x2295
+  __TEXT.__cstring: 0x22df
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x24
   __DATA.__gxf_data: 0x8168

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 433
   Symbols:   191
-  CStrings:  233
+  CStrings:  234
 
Functions:
~ sub_fffffc000000597c : 5360 -> 5384
~ sub_fffffc0000008edc -> sub_fffffc0000008ef4 : 680 -> 672
~ sub_fffffc000000b2c0 -> sub_fffffc000000b2d0 : 11008 -> 10992
~ sub_fffffc000000ddc0 : 2376 -> 2368
~ sub_fffffc000000e708 -> sub_fffffc000000e700 : 340 -> 324
~ sub_fffffc000000e85c -> sub_fffffc000000e844 : 2100 -> 2056
~ sub_fffffc000000f3c0 -> sub_fffffc000000f37c : 10324 -> 10208
~ sub_fffffc000001b618 -> sub_fffffc000001b560 : 3188 -> 3084
~ sub_fffffc0000020970 -> sub_fffffc0000020850 : 2120 -> 2128
~ sub_fffffc00000267fc -> sub_fffffc00000266e4 : 1840 -> 1868
~ sub_fffffc0000026f2c -> sub_fffffc0000026e30 : 6880 -> 6864
~ sub_fffffc0000028a0c -> sub_fffffc0000028900 : 2212 -> 2516
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:28:59"
- "Oct 14 2026 23:23:18"
```
