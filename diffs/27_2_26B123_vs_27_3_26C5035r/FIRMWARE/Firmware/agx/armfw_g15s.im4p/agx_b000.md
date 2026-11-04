## agx_b000

> `Firmware/agx/armfw_g15s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x5062c
+  __TEXT.__text: 0x50780
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1160
-  __TEXT.__cstring: 0x27a4
+  __TEXT.__cstring: 0x27ee
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 502
   Symbols:   178
-  CStrings:  277
+  CStrings:  278
 
Functions:
~ sub_fffffc0000007638 : 5864 -> 5888
~ sub_fffffc0000037194 -> sub_fffffc00000371ac : 1904 -> 2176
~ sub_fffffc000003a144 -> sub_fffffc000003a26c : 1860 -> 1888
~ sub_fffffc000003d510 -> sub_fffffc000003d654 : 1028 -> 1044
~ sub_fffffc00000504e8 -> sub_fffffc000005063c : 332 -> 324
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:16:13"
- "Oct 14 2026 23:11:37"
```
