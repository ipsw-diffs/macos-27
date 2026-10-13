## agx_c000

> `Firmware/agx/armfw_g15g.im4p/agx_c000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x54af0
-  __TEXT.__gxf_code: 0x1054
+  __TEXT.__text: 0x54d08
+  __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x240c
+  __TEXT.__const: 0x2438
   __TEXT.__cstring: 0x25c8
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
Functions:
~ sub_fffffc0000018e70 : 19464 -> 19504
~ sub_fffffc000001e2d8 -> sub_fffffc000001e300 : 1832 -> 1896
~ sub_fffffc00000204f4 -> sub_fffffc000002055c : 1828 -> 1848
~ sub_fffffc00000230c4 -> sub_fffffc0000023140 : 1596 -> 1664
~ sub_fffffc00000238b8 -> sub_fffffc0000023978 : 1988 -> 2116
~ sub_fffffc000002407c -> sub_fffffc00000241bc : 1016 -> 1096
~ sub_fffffc0000024704 -> sub_fffffc0000024894 : 1460 -> 1596
~ sub_fffffc00000549ac -> sub_fffffc0000054bc4 : 324 -> 332
CStrings:
+ "Oct  7 2026 23:36:00"
- "Sep 29 2026 21:26:33"
```
