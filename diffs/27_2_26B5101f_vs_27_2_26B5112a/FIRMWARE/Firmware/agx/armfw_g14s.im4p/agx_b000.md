## agx_b000

> `Firmware/agx/armfw_g14s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4e624
-  __TEXT.__gxf_code: 0x1054
+  __TEXT.__text: 0x4e670
+  __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1f08
+  __TEXT.__const: 0x1f00
   __TEXT.__cstring: 0x236b
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
Functions:
~ sub_ffffff8000023308 : 928 -> 924
~ sub_ffffff8000025e84 -> sub_ffffff8000025e80 : 724 -> 732
~ sub_ffffff8000026a18 -> sub_ffffff8000026a1c : 796 -> 804
~ sub_ffffff800002b450 -> sub_ffffff800002b45c : 1324 -> 1328
~ sub_ffffff8000039c64 -> sub_ffffff8000039c74 : 6860 -> 6920
CStrings:
+ "Oct  7 2026 23:31:42"
- "Sep 29 2026 21:21:43"
```
