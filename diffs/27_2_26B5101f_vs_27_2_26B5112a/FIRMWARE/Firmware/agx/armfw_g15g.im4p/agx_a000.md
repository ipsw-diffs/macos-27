## agx_a000

> `Firmware/agx/armfw_g15g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4f38c
-  __TEXT.__gxf_code: 0x1054
+  __TEXT.__text: 0x4f578
+  __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x23fc
+  __TEXT.__const: 0x2428
   __TEXT.__cstring: 0x2424
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
Functions:
~ sub_fffffc0000017c80 : 18524 -> 18520
~ sub_fffffc000001ccf4 -> sub_fffffc000001ccf0 : 1832 -> 1896
~ sub_fffffc000001ef10 -> sub_fffffc000001ef4c : 1828 -> 1848
~ sub_fffffc0000021aa8 -> sub_fffffc0000021af8 : 1596 -> 1664
~ sub_fffffc000002229c -> sub_fffffc0000022330 : 1988 -> 2116
~ sub_fffffc0000022a60 -> sub_fffffc0000022b74 : 1016 -> 1096
~ sub_fffffc00000230e8 -> sub_fffffc000002324c : 1460 -> 1596
CStrings:
+ "Oct  7 2026 23:27:23"
- "Sep 29 2026 21:16:38"
```
