## agx_b000

> `Firmware/agx/armfw_g14c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4e9d8
-  __TEXT.__gxf_code: 0x1054
+  __TEXT.__text: 0x4ea14
+  __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1f08
+  __TEXT.__const: 0x1f00
   __TEXT.__cstring: 0x236b
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
Functions:
~ sub_ffffff8000023550 : 928 -> 924
~ sub_ffffff800002b770 -> sub_ffffff800002b76c : 1324 -> 1328
~ sub_ffffff800003a01c : 6856 -> 6916
~ sub_ffffff800004e894 -> sub_ffffff800004e8d0 : 332 -> 324
CStrings:
+ "Oct  7 2026 23:31:26"
- "Sep 29 2026 21:21:21"
```
