## agx_b000

> `Firmware/agx/armfw_g14s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4e7e0
+  __TEXT.__text: 0x4e824
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x86658
+  __DATA.__zerofill: 0x86678
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 509
   Symbols:   196
Functions:
~ sub_ffffff8000003350 : 936 -> 976
~ sub_ffffff800000ff08 -> sub_ffffff800000ff30 : 532 -> 536
~ sub_ffffff800001011c -> sub_ffffff8000010148 : 516 -> 524
~ sub_ffffff80000109b8 -> sub_ffffff80000109ec : 536 -> 540
~ sub_ffffff8000026e18 -> sub_ffffff8000026e50 : 18012 -> 18016
~ sub_ffffff800002fb9c -> sub_ffffff800002fbd8 : 2136 -> 2144
CStrings:
+ "Nov 10 2026 03:25:15"
- "Oct 30 2026 01:14:50"
```
