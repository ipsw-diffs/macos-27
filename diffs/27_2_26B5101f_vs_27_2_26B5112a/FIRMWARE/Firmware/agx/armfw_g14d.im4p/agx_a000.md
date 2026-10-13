## agx_a000

> `Firmware/agx/armfw_g14d.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4f5a8
-  __TEXT.__gxf_code: 0x1054
+  __TEXT.__text: 0x4f5e4
+  __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1f60
+  __TEXT.__const: 0x1f58
   __TEXT.__cstring: 0x236b
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
Functions:
~ sub_ffffff8000023c0c : 928 -> 924
~ sub_ffffff800002be74 -> sub_ffffff800002be70 : 1324 -> 1328
~ sub_ffffff800003ab44 : 7024 -> 7084
~ sub_ffffff800004f464 -> sub_ffffff800004f4a0 : 332 -> 324
CStrings:
+ "Oct  7 2026 23:27:23"
- "Sep 29 2026 21:16:42"
```
