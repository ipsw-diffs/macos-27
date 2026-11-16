## agx_a000

> `Firmware/agx/armfw_g14c.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4f014
+  __TEXT.__text: 0x4f058
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x86798
+  __DATA.__zerofill: 0x867b8
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 510
   Symbols:   196
Functions:
~ sub_ffffff8000003350 : 936 -> 976
~ sub_ffffff8000010130 -> sub_ffffff8000010158 : 532 -> 536
~ sub_ffffff8000010344 -> sub_ffffff8000010370 : 516 -> 524
~ sub_ffffff8000010be0 -> sub_ffffff8000010c14 : 536 -> 540
~ sub_ffffff80000272c8 -> sub_ffffff8000027300 : 18012 -> 18016
~ sub_ffffff800003005c -> sub_ffffff8000030098 : 2244 -> 2252
~ sub_ffffff800004eed0 -> sub_ffffff800004ef14 : 324 -> 332
CStrings:
+ "Nov 10 2026 03:21:29"
- "Oct 30 2026 01:10:47"
```
