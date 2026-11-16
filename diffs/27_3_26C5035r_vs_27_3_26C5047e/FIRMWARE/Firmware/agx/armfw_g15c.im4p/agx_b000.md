## agx_b000

> `Firmware/agx/armfw_g15c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x531a0
+  __TEXT.__text: 0x531e0
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0xcb798
+  __DATA.__zerofill: 0xcb7b8
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 519
   Symbols:   179
Functions:
~ sub_fffffc0000002f2c : 1400 -> 1440
~ sub_fffffc0000014864 -> sub_fffffc000001488c : 532 -> 536
~ sub_fffffc0000014a78 -> sub_fffffc0000014aa4 : 492 -> 500
~ sub_fffffc00000152e4 -> sub_fffffc0000015318 : 512 -> 516
~ sub_fffffc0000032ca0 -> sub_fffffc0000032cd8 : 2312 -> 2320
CStrings:
+ "Nov 10 2026 03:26:44"
- "Oct 30 2026 01:16:22"
```
