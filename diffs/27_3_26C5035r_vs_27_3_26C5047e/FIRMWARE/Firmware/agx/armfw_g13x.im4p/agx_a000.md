## agx_a000

> `Firmware/agx/armfw_g13x.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x44bfc
+  __TEXT.__text: 0x44c4c
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
~ sub_ffffff800000386c -> sub_ffffff8000003898 : 4856 -> 4872
~ sub_ffffff800000da80 -> sub_ffffff800000dabc : 528 -> 532
~ sub_ffffff800000dc90 -> sub_ffffff800000dcd0 : 484 -> 496
~ sub_ffffff800000de74 -> sub_ffffff800000dec0 : 668 -> 672
~ sub_ffffff800000e46c -> sub_ffffff800000e4bc : 512 -> 520
~ sub_ffffff800000e66c -> sub_ffffff800000e6c4 : 736 -> 740
~ sub_ffffff8000017344 -> sub_ffffff80000173a0 : 1756 -> 1760
~ sub_ffffff800002184c -> sub_ffffff80000218ac : 3652 -> 3648
~ sub_ffffff8000026990 -> sub_ffffff80000269ec : 2360 -> 2348
CStrings:
+ "Nov 10 2026 03:28:14"
- "Oct 30 2026 01:17:57"
```
