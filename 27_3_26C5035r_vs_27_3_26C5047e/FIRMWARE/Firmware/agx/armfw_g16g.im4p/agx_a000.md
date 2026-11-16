## agx_a000

> `Firmware/agx/armfw_g16g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__gxf_data`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x52f50
-  __TEXT.__gxf_code: 0x5220
+  __TEXT.__text: 0x52f88
+  __TEXT.__gxf_code: 0x5250
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1dbc

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x7a298
+  __DATA.__zerofill: 0x7a2b8
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 518
   Symbols:   191
Functions:
~ sub_fffffc0000003350 : 1308 -> 1344
~ sub_fffffc0000015ea4 -> sub_fffffc0000015ec8 : 532 -> 536
~ sub_fffffc00000160b8 -> sub_fffffc00000160e0 : 492 -> 500
~ sub_fffffc0000016924 -> sub_fffffc0000016954 : 512 -> 516
~ sub_fffffc0000033d74 -> sub_fffffc0000033da8 : 2124 -> 2112
~ sub_fffffc00000347c4 -> sub_fffffc00000347ec : 856 -> 872
~ sub_fffffc0000052e10 -> sub_fffffc0000052e48 : 320 -> 328
CStrings:
+ "Nov 10 2026 03:21:45"
- "Oct 30 2026 01:11:07"
```
