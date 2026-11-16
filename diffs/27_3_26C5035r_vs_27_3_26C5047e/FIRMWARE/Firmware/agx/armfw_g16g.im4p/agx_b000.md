## agx_b000

> `Firmware/agx/armfw_g16g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__gxf_data`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x52b00
-  __TEXT.__gxf_code: 0x5220
+  __TEXT.__text: 0x52b38
+  __TEXT.__gxf_code: 0x5250
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1dfc

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x7a298
+  __DATA.__zerofill: 0x7a2b8
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 517
   Symbols:   191
Functions:
~ sub_fffffc0000003350 : 1308 -> 1344
~ sub_fffffc0000015e98 -> sub_fffffc0000015ebc : 532 -> 536
~ sub_fffffc00000160ac -> sub_fffffc00000160d4 : 492 -> 500
~ sub_fffffc0000016918 -> sub_fffffc0000016948 : 512 -> 516
~ sub_fffffc00000339d4 -> sub_fffffc0000033a08 : 2124 -> 2112
~ sub_fffffc0000034424 -> sub_fffffc000003444c : 856 -> 872
~ sub_fffffc00000529c0 -> sub_fffffc00000529f8 : 320 -> 328
CStrings:
+ "Nov 10 2026 03:25:57"
- "Oct 30 2026 01:15:36"
```
