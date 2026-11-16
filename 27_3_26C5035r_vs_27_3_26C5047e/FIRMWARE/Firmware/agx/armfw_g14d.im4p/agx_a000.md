## agx_a000

> `Firmware/agx/armfw_g14d.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4f754
+  __TEXT.__text: 0x4f798
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x86998
+  __DATA.__zerofill: 0x869b8
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 511
   Symbols:   196
Functions:
~ sub_ffffff8000003434 : 964 -> 1004
~ sub_ffffff8000010688 -> sub_ffffff80000106b0 : 532 -> 536
~ sub_ffffff800001089c -> sub_ffffff80000108c8 : 516 -> 524
~ sub_ffffff8000011138 -> sub_ffffff800001116c : 536 -> 540
~ sub_ffffff800002782c -> sub_ffffff8000027864 : 18012 -> 18016
~ sub_ffffff8000030630 -> sub_ffffff800003066c : 2456 -> 2464
~ sub_ffffff800004f610 -> sub_ffffff800004f654 : 324 -> 332
CStrings:
+ "Nov 10 2026 03:21:29"
- "Oct 30 2026 01:10:50"
```
