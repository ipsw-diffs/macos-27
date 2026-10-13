## agx_b000

> `Firmware/agx/armfw_g15s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x5042c
-  __TEXT.__gxf_code: 0x1054
+  __TEXT.__text: 0x5062c
+  __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1138
+  __TEXT.__const: 0x1160
   __TEXT.__cstring: 0x27a4
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
Functions:
~ sub_fffffc00000176f4 : 20312 -> 20328
~ sub_fffffc000001ceb8 -> sub_fffffc000001cec8 : 1832 -> 1896
~ sub_fffffc000001f0bc -> sub_fffffc000001f10c : 1212 -> 1232
~ sub_fffffc0000021ac0 -> sub_fffffc0000021b24 : 1672 -> 1740
~ sub_fffffc00000223c0 -> sub_fffffc0000022468 : 1848 -> 1976
~ sub_fffffc0000022af8 -> sub_fffffc0000022c20 : 1092 -> 1172
~ sub_fffffc00000232d0 -> sub_fffffc0000023448 : 1444 -> 1588
~ sub_fffffc00000290c0 -> sub_fffffc00000292c8 : 936 -> 928
CStrings:
+ "Oct  7 2026 23:33:05"
- "Sep 29 2026 21:23:20"
```
