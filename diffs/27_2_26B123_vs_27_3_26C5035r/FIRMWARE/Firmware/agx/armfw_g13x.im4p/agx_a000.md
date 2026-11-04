## agx_a000

> `Firmware/agx/armfw_g13x.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x44a98
+  __TEXT.__text: 0x44bfc
   __TEXT.__gxf_code: 0x10e4
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1f80
-  __TEXT.__cstring: 0x1f57
+  __TEXT.__const: 0x1f90
+  __TEXT.__cstring: 0x1fa1
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x1e8
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 478
   Symbols:   195
-  CStrings:  230
+  CStrings:  231
 
Functions:
~ sub_ffffff8000005d0c : 7076 -> 7100
~ sub_ffffff800002b3d4 -> sub_ffffff800002b3ec : 1784 -> 2080
~ sub_ffffff800002fa24 -> sub_ffffff800002fb64 : 1996 -> 2024
~ sub_ffffff8000032988 -> sub_ffffff8000032ae4 : 768 -> 776
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:17:57"
- "Oct 14 2026 23:13:11"
```
