## agx_a000

> `Firmware/agx/armfw_g14g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x526d8
+  __TEXT.__text: 0x52728
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x53278
+  __DATA.__zerofill: 0x53478
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 476
   Symbols:   196
Functions:
~ sub_ffffff8000003350 : 856 -> 900
~ sub_ffffff8000003880 -> sub_ffffff80000038ac : 5288 -> 5304
~ sub_ffffff80000102f8 -> sub_ffffff8000010334 : 528 -> 532
~ sub_ffffff8000010508 -> sub_ffffff8000010548 : 484 -> 496
~ sub_ffffff80000106ec -> sub_ffffff8000010738 : 668 -> 672
~ sub_ffffff8000010ce4 -> sub_ffffff8000010d34 : 512 -> 520
~ sub_ffffff8000010ee4 -> sub_ffffff8000010f3c : 736 -> 740
~ sub_ffffff800001a498 -> sub_ffffff800001a4f4 : 1756 -> 1760
~ sub_ffffff800002a9d4 -> sub_ffffff800002aa34 : 2016 -> 2004
~ sub_ffffff800002ee40 -> sub_ffffff800002ee94 : 24928 -> 24924
CStrings:
+ "Nov 10 2026 03:20:57"
- "Oct 30 2026 01:10:12"
```
