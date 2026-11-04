## agx_a000

> `Firmware/agx/armfw_g17p.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3c140
+  __TEXT.__text: 0x3c16c
   __TEXT.__gxf_code: 0x5150
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1d3c
+  __TEXT.__const: 0x1d44
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x6a0
-  __TEXT.__cstring: 0x2303
+  __TEXT.__cstring: 0x234d
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x24
   __DATA.__gxf_data: 0x8168

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 434
   Symbols:   191
-  CStrings:  235
+  CStrings:  236
 
Functions:
~ sub_fffffc000000597c : 5360 -> 5384
~ sub_fffffc0000008edc -> sub_fffffc0000008ef4 : 680 -> 672
~ sub_fffffc000000b2d0 -> sub_fffffc000000b2e0 : 11008 -> 10992
~ sub_fffffc000000e78c : 340 -> 324
~ sub_fffffc000000e8e0 -> sub_fffffc000000e8d0 : 2100 -> 2056
~ sub_fffffc000000f444 -> sub_fffffc000000f408 : 10324 -> 10208
~ sub_fffffc000001b69c -> sub_fffffc000001b5ec : 3188 -> 3084
~ sub_fffffc00000209f4 -> sub_fffffc00000208dc : 2120 -> 2128
~ sub_fffffc00000269d4 -> sub_fffffc00000268c4 : 1840 -> 1868
~ sub_fffffc0000027104 -> sub_fffffc0000027010 : 7096 -> 7080
~ sub_fffffc0000028cbc -> sub_fffffc0000028bb8 : 2212 -> 2516
~ sub_fffffc000003bffc -> sub_fffffc000003c028 : 324 -> 332
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:11:13"
- "Oct 14 2026 23:06:45"
```
