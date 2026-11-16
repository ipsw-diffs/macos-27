## agx_a000

> `Firmware/agx/armfw_g15g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4f6d8
+  __TEXT.__text: 0x4f708
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x68ef8
+  __DATA.__zerofill: 0x69118
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 490
   Symbols:   197
Functions:
~ sub_fffffc0000003350 : 944 -> 984
~ sub_fffffc00000149c4 -> sub_fffffc00000149ec : 532 -> 536
~ sub_fffffc0000014bd8 -> sub_fffffc0000014c04 : 492 -> 500
~ sub_fffffc0000015444 -> sub_fffffc0000015478 : 512 -> 516
~ sub_fffffc000002a45c -> sub_fffffc000002a494 : 17912 -> 17916
~ sub_fffffc00000328c4 -> sub_fffffc0000032900 : 2044 -> 2032
CStrings:
+ "Nov 10 2026 03:21:26"
- "Oct 30 2026 01:10:47"
```
