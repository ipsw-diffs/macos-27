## agx_b000

> `Firmware/agx/armfw_g14g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x52574
+  __TEXT.__text: 0x526d8
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1f28
-  __TEXT.__cstring: 0x20d1
+  __TEXT.__cstring: 0x211b
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 476
   Symbols:   196
-  CStrings:  237
+  CStrings:  238
 
Functions:
~ sub_ffffff8000006034 : 7620 -> 7644
~ sub_ffffff800003807c -> sub_ffffff8000038094 : 1836 -> 2132
~ sub_ffffff800003c72c -> sub_ffffff800003c86c : 1996 -> 2024
~ sub_ffffff800003fe20 -> sub_ffffff800003ff7c : 768 -> 776
~ sub_ffffff8000052430 -> sub_ffffff8000052594 : 324 -> 332
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:14:10"
- "Oct 14 2026 23:09:42"
```
