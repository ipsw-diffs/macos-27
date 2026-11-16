## agx_c000

> `Firmware/agx/armfw_g15g.im4p/agx_c000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x54e68
+  __TEXT.__text: 0x54ea8
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x697f8
+  __DATA.__zerofill: 0x69a18
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 502
   Symbols:   197
Functions:
~ sub_fffffc0000003350 : 944 -> 984
~ sub_fffffc0000015bb4 -> sub_fffffc0000015bdc : 532 -> 536
~ sub_fffffc0000015dc8 -> sub_fffffc0000015df4 : 492 -> 500
~ sub_fffffc0000016634 -> sub_fffffc0000016668 : 512 -> 516
~ sub_fffffc000002dc7c -> sub_fffffc000002dcb4 : 17324 -> 17328
~ sub_fffffc0000036604 -> sub_fffffc0000036640 : 2120 -> 2108
~ sub_fffffc0000036ff0 -> sub_fffffc0000037020 : 856 -> 872
CStrings:
+ "Nov 10 2026 03:29:05"
- "Oct 30 2026 01:18:39"
```
