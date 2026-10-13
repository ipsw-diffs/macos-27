## agx_b000

> `Firmware/agx/armfw_g17g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3d56c
-  __TEXT.__gxf_code: 0x4f50
+  __TEXT.__text: 0x3d4f0
+  __TEXT.__gxf_code: 0x5130
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1085
+  __TEXT.__const: 0x10b4
   __TEXT._rtk_tunables: 0x740
   __TEXT._rtk_patchbay: 0x231
   __TEXT.__cstring: 0x2426
   __TEXT.__init_offsets: 0x0
-  __TEXT.__chain_starts: 0x20
-  __DATA.__gxf_data: 0x80b8
+  __TEXT.__chain_starts: 0x24
+  __DATA.__gxf_data: 0x8160
   __DATA.__data: 0x17d40
   __DATA._rtk_init_stack: 0x4000
   __DATA.__const: 0x7c8

   __DATA.__zerofill: 0x5a778
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 416
-  Symbols:   169
+  Symbols:   173
   CStrings:  238
 
Symbols:
+ _agfUPPLRegisterPageCount
+ _agfUPPLRegisterPages
+ _gClientFunctions
+ _premap_ranges
Functions:
~ sub_fffffc000000bed8 : 12060 -> 11936
~ sub_fffffc000003d428 -> sub_fffffc000003d3ac : 332 -> 324
CStrings:
+ "Oct  7 2026 23:39:15"
- "Sep 29 2026 21:29:17"
```
