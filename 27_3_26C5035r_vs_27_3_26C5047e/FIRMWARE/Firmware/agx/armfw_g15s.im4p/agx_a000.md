## agx_a000

> `Firmware/agx/armfw_g15s.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x50bac
+  __TEXT.__text: 0x50bd8
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0xcaeb8
+  __DATA.__zerofill: 0xcaed8
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 503
   Symbols:   178
Functions:
~ sub_fffffc0000002f2c : 1324 -> 1364
~ sub_fffffc0000014108 -> sub_fffffc0000014130 : 532 -> 536
~ sub_fffffc000001431c -> sub_fffffc0000014348 : 492 -> 500
~ sub_fffffc0000014b88 -> sub_fffffc0000014bbc : 512 -> 516
~ sub_fffffc0000031c30 -> sub_fffffc0000031c68 : 2176 -> 2164
CStrings:
+ "Nov 10 2026 03:22:11"
- "Oct 30 2026 01:11:33"
```
