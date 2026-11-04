## agx_a000

> `Firmware/agx/armfw_g16g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x52df0
+  __TEXT.__text: 0x52f50
   __TEXT.__gxf_code: 0x5220
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1dbc
-  __TEXT.__cstring: 0x273f
+  __TEXT.__cstring: 0x2789
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x6a0
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 518
   Symbols:   191
-  CStrings:  272
+  CStrings:  273
 
Functions:
~ sub_fffffc0000007ae8 : 7888 -> 7912
~ sub_fffffc0000038a14 -> sub_fffffc0000038a2c : 1576 -> 1868
~ sub_fffffc000003bb70 -> sub_fffffc000003bcac : 1716 -> 1744
~ sub_fffffc000003f4e4 -> sub_fffffc000003f63c : 1212 -> 1220
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:11:07"
- "Oct 14 2026 23:06:40"
```
