## agx_b000

> `Firmware/agx/armfw_g13x.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x449f4
+  __TEXT.__text: 0x44b58
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
~ sub_ffffff8000005db4 : 7076 -> 7100
~ sub_ffffff800002b330 -> sub_ffffff800002b348 : 1784 -> 2080
~ sub_ffffff800002f980 -> sub_ffffff800002fac0 : 1996 -> 2024
~ sub_ffffff80000328e4 -> sub_ffffff8000032a40 : 768 -> 776
~ sub_ffffff80000448b0 -> sub_ffffff8000044a14 : 324 -> 332
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:19:53"
- "Oct 14 2026 23:15:08"
```
