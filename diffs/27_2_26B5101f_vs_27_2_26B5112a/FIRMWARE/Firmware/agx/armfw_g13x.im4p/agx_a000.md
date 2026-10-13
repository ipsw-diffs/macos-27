## agx_a000

> `Firmware/agx/armfw_g13x.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x44aa0
-  __TEXT.__gxf_code: 0x10dc
+  __TEXT.__text: 0x44a98
+  __TEXT.__gxf_code: 0x10e4
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1f88
+  __TEXT.__const: 0x1f80
   __TEXT.__cstring: 0x1f57
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x1e8
Functions:
~ sub_ffffff8000020120 : 1272 -> 1264
~ sub_ffffff800004495c -> sub_ffffff8000044954 : 324 -> 332
CStrings:
+ "Oct  7 2026 23:34:55"
- "Sep 29 2026 21:25:29"
```
