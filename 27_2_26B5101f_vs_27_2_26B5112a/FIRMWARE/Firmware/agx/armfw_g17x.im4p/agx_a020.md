## agx_a020

> `Firmware/agx/armfw_g17x.im4p/agx_a020`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3d7e8
-  __TEXT.__gxf_code: 0x4f50
+  __TEXT.__text: 0x3d8b0
+  __TEXT.__gxf_code: 0x50a0
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x11d5
+  __TEXT.__const: 0x1204
   __TEXT._rtk_tunables: 0x740
   __TEXT._rtk_patchbay: 0x231
   __TEXT.__cstring: 0x21ff
   __TEXT.__init_offsets: 0x0
-  __TEXT.__chain_starts: 0x20
-  __DATA.__gxf_data: 0x80b8
+  __TEXT.__chain_starts: 0x24
+  __DATA.__gxf_data: 0x8130
   __DATA.__data: 0x17da0
   __DATA._rtk_init_stack: 0x4000
   __DATA.__const: 0x7d8

   __DATA.__zerofill: 0x58318
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 415
-  Symbols:   171
+  Symbols:   175
   CStrings:  231
 
Symbols:
+ _agfUPPLRegisterPageCount
+ _agfUPPLRegisterPages
+ _gClientFunctions
+ _premap_ranges
Functions:
~ sub_fffffc000000c62c : 10500 -> 10700
~ sub_fffffc000003d6a4 -> sub_fffffc000003d76c : 332 -> 324
CStrings:
+ "Oct  7 2026 23:44:56"
- "Sep 29 2026 21:34:25"
```
