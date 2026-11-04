## agx_b000

> `Firmware/agx/armfw_g17g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3d4f0
+  __TEXT.__text: 0x3d54c
   __TEXT.__gxf_code: 0x5130
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x10b4
+  __TEXT.__const: 0x10bc
   __TEXT._rtk_tunables: 0x740
   __TEXT._rtk_patchbay: 0x231
-  __TEXT.__cstring: 0x2426
+  __TEXT.__cstring: 0x2470
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x24
   __DATA.__gxf_data: 0x8160

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 416
   Symbols:   173
-  CStrings:  238
+  CStrings:  239
 
Functions:
~ sub_fffffc0000006164 : 5320 -> 5344
~ sub_fffffc0000008464 -> sub_fffffc000000847c : 916 -> 924
~ sub_fffffc00000099f8 -> sub_fffffc0000009a18 : 680 -> 672
~ sub_fffffc000000bed8 -> sub_fffffc000000bef0 : 11936 -> 11920
~ sub_fffffc000000ed78 -> sub_fffffc000000ed80 : 2284 -> 2276
~ sub_fffffc000000f664 : 340 -> 324
~ sub_fffffc000000f7b8 -> sub_fffffc000000f7a8 : 1600 -> 1556
~ sub_fffffc000001013c -> sub_fffffc0000010100 : 10020 -> 9952
~ sub_fffffc000001c3d0 -> sub_fffffc000001c350 : 3240 -> 3136
~ sub_fffffc0000021e1c -> sub_fffffc0000021d34 : 2400 -> 2408
~ sub_fffffc0000027990 -> sub_fffffc00000278b0 : 1848 -> 1876
~ sub_fffffc00000280c8 -> sub_fffffc0000028004 : 8076 -> 8060
~ sub_fffffc000002a054 -> sub_fffffc0000029f80 : 2216 -> 2520
~ sub_fffffc000003d3ac -> sub_fffffc000003d408 : 324 -> 332
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:21:35"
- "Oct 14 2026 23:16:37"
```
