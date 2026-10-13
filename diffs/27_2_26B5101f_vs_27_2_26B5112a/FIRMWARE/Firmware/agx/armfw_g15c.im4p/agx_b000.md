## agx_b000

> `Firmware/agx/armfw_g15c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x52e44
-  __TEXT.__gxf_code: 0x1054
+  __TEXT.__text: 0x5304c
+  __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x11d0
+  __TEXT.__const: 0x11f8
   __TEXT.__cstring: 0x2bb2
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
Functions:
~ sub_fffffc0000018020 : 20312 -> 20328
~ sub_fffffc000001d7e4 -> sub_fffffc000001d7f4 : 1832 -> 1896
~ sub_fffffc000001f9e8 -> sub_fffffc000001fa38 : 1212 -> 1232
~ sub_fffffc00000223ec -> sub_fffffc0000022450 : 1672 -> 1740
~ sub_fffffc0000022cec -> sub_fffffc0000022d94 : 1848 -> 1976
~ sub_fffffc0000023424 -> sub_fffffc000002354c : 1092 -> 1172
~ sub_fffffc0000023bfc -> sub_fffffc0000023d74 : 1444 -> 1588
~ sub_fffffc0000052d04 -> sub_fffffc0000052f0c : 320 -> 328
CStrings:
+ "Oct  7 2026 23:33:14"
- "Sep 29 2026 21:23:27"
```
