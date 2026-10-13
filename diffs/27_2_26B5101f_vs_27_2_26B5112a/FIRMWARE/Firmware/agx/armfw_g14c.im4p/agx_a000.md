## agx_a000

> `Firmware/agx/armfw_g14c.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4ee68
-  __TEXT.__gxf_code: 0x1054
+  __TEXT.__text: 0x4eea4
+  __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1f20
+  __TEXT.__const: 0x1f18
   __TEXT.__cstring: 0x236b
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
Functions:
~ sub_ffffff80000236f0 : 928 -> 924
~ sub_ffffff800002b910 -> sub_ffffff800002b90c : 1324 -> 1328
~ sub_ffffff800003a438 : 6972 -> 7032
~ sub_ffffff800004ed24 -> sub_ffffff800004ed60 : 332 -> 324
CStrings:
+ "Oct  7 2026 23:27:21"
- "Sep 29 2026 21:16:39"
```
