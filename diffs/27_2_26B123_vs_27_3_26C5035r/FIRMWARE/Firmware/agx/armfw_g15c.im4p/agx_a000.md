## agx_a000

> `Firmware/agx/armfw_g15c.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x53490
+  __TEXT.__text: 0x535e4
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x11f8
-  __TEXT.__cstring: 0x2bcf
+  __TEXT.__cstring: 0x2c19
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 520
   Symbols:   179
-  CStrings:  293
+  CStrings:  294
 
Functions:
~ sub_fffffc000000774c : 5940 -> 5964
~ sub_fffffc0000038eb0 -> sub_fffffc0000038ec8 : 1904 -> 2176
~ sub_fffffc000003be6c -> sub_fffffc000003bf94 : 1860 -> 1888
~ sub_fffffc000003f930 -> sub_fffffc000003fa74 : 1028 -> 1044
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:11:38"
- "Oct 14 2026 23:07:10"
```
