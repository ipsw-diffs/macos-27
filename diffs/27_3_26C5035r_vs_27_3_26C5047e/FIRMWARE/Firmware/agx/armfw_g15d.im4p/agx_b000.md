## agx_b000

> `Firmware/agx/armfw_g15d.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x542f0
+  __TEXT.__text: 0x54330
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0xcba18
+  __DATA.__zerofill: 0xcba38
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 522
   Symbols:   179
Functions:
~ sub_fffffc0000003010 : 1428 -> 1468
~ sub_fffffc00000153dc -> sub_fffffc0000015404 : 532 -> 536
~ sub_fffffc00000155f0 -> sub_fffffc000001561c : 492 -> 500
~ sub_fffffc0000015e5c -> sub_fffffc0000015e90 : 512 -> 516
~ sub_fffffc0000033a74 -> sub_fffffc0000033aac : 2512 -> 2520
CStrings:
+ "Nov 10 2026 03:26:47"
- "Oct 30 2026 01:16:39"
```
