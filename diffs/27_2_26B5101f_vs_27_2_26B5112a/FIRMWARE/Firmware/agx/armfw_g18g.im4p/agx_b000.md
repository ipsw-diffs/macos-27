## agx_b000

> `Firmware/agx/armfw_g18g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3c8a0
-  __TEXT.__gxf_code: 0x4f50
+  __TEXT.__text: 0x3c8f0
+  __TEXT.__gxf_code: 0x4f60
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x20e1
+  __TEXT.__const: 0x2110
   __TEXT._rtk_patchbay: 0x23a
   __TEXT._rtk_tunables: 0x7e0
   __TEXT.__cstring: 0x247d
Functions:
~ sub_fffffc000000c3e0 : 10524 -> 10604
CStrings:
+ "Oct  7 2026 23:39:51"
- "Sep 29 2026 21:29:56"
```
