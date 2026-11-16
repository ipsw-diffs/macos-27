## agx_b000

> `Firmware/agx/armfw_g15g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x55210
+  __TEXT.__text: 0x55250
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x69998
+  __DATA.__zerofill: 0x69b98
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 503
   Symbols:   197
Functions:
~ sub_fffffc0000003350 : 944 -> 984
~ sub_fffffc0000015bbc -> sub_fffffc0000015be4 : 532 -> 536
~ sub_fffffc0000015dd0 -> sub_fffffc0000015dfc : 492 -> 500
~ sub_fffffc000001663c -> sub_fffffc0000016670 : 512 -> 516
~ sub_fffffc000002dd30 -> sub_fffffc000002dd68 : 17288 -> 17292
~ sub_fffffc0000036694 -> sub_fffffc00000366d0 : 2120 -> 2108
~ sub_fffffc0000037080 -> sub_fffffc00000370b0 : 856 -> 872
CStrings:
+ "Nov 10 2026 03:25:36"
- "Oct 30 2026 01:14:49"
```
