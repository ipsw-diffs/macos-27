## agx_b000

> `Firmware/agx/armfw_g14d.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4f2bc
+  __TEXT.__text: 0x4f300
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x86958
+  __DATA.__zerofill: 0x86978
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 510
   Symbols:   196
Functions:
~ sub_ffffff8000003434 : 964 -> 1004
~ sub_ffffff80000106a0 -> sub_ffffff80000106c8 : 532 -> 536
~ sub_ffffff80000108b4 -> sub_ffffff80000108e0 : 516 -> 524
~ sub_ffffff8000011150 -> sub_ffffff8000011184 : 536 -> 540
~ sub_ffffff8000027684 -> sub_ffffff80000276bc : 18012 -> 18016
~ sub_ffffff8000030488 -> sub_ffffff80000304c4 : 2456 -> 2464
~ sub_ffffff800004f178 -> sub_ffffff800004f1bc : 332 -> 324
CStrings:
+ "Nov 10 2026 03:25:11"
- "Oct 30 2026 01:15:09"
```
