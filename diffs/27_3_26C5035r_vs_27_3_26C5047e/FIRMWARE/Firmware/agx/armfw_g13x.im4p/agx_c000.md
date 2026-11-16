## agx_c000

> `Firmware/agx/armfw_g13x.im4p/agx_c000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x44b58
+  __TEXT.__text: 0x44ba8
   __TEXT.__gxf_code: 0x10e4
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x535d8
+  __DATA.__zerofill: 0x537f8
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 478
   Symbols:   195
Functions:
~ sub_ffffff8000003350 : 856 -> 900
~ sub_ffffff80000038ac -> sub_ffffff80000038d8 : 4856 -> 4872
~ sub_ffffff800000daf0 -> sub_ffffff800000db2c : 528 -> 532
~ sub_ffffff800000dd00 -> sub_ffffff800000dd40 : 484 -> 496
~ sub_ffffff800000dee4 -> sub_ffffff800000df30 : 668 -> 672
~ sub_ffffff800000e4dc -> sub_ffffff800000e52c : 512 -> 520
~ sub_ffffff800000e6dc -> sub_ffffff800000e734 : 736 -> 740
~ sub_ffffff80000172a0 -> sub_ffffff80000172fc : 1756 -> 1760
~ sub_ffffff80000217a8 -> sub_ffffff8000021808 : 3652 -> 3648
~ sub_ffffff80000268ec -> sub_ffffff8000026948 : 2360 -> 2348
CStrings:
+ "Nov 10 2026 03:30:08"
- "Oct 30 2026 01:19:53"
```
