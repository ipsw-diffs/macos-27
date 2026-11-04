## agx_b000

> `Firmware/agx/armfw_g16g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x529a0
+  __TEXT.__text: 0x52b00
   __TEXT.__gxf_code: 0x5220
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1dfc
-  __TEXT.__cstring: 0x26bf
+  __TEXT.__cstring: 0x2709
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x6a0
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 517
   Symbols:   191
-  CStrings:  269
+  CStrings:  270
 
Functions:
~ sub_fffffc0000007ae8 : 7888 -> 7912
~ sub_fffffc00000385d8 -> sub_fffffc00000385f0 : 1576 -> 1868
~ sub_fffffc000003b734 -> sub_fffffc000003b870 : 1716 -> 1744
~ sub_fffffc000003f094 -> sub_fffffc000003f1ec : 1212 -> 1220
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:15:36"
- "Oct 14 2026 23:10:56"
```
