## agx_b000

> `Firmware/agx/armfw_g14c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4eb84
+  __TEXT.__text: 0x4ebc8
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x86758
+  __DATA.__zerofill: 0x86778
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 509
   Symbols:   196
Functions:
~ sub_ffffff8000003350 : 936 -> 976
~ sub_ffffff8000010150 -> sub_ffffff8000010178 : 532 -> 536
~ sub_ffffff8000010364 -> sub_ffffff8000010390 : 516 -> 524
~ sub_ffffff8000010c00 -> sub_ffffff8000010c34 : 536 -> 540
~ sub_ffffff8000027128 -> sub_ffffff8000027160 : 18012 -> 18016
~ sub_ffffff800002febc -> sub_ffffff800002fef8 : 2244 -> 2252
~ sub_ffffff800004ea40 -> sub_ffffff800004ea84 : 324 -> 332
CStrings:
+ "Nov 10 2026 03:25:05"
- "Oct 30 2026 01:14:33"
```
