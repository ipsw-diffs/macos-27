## agx_b000

> `Firmware/agx/armfw_g15s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x50780
+  __TEXT.__text: 0x507ac
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0xcae38
+  __DATA.__zerofill: 0xcae58
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 502
   Symbols:   178
Functions:
~ sub_fffffc0000002f2c : 1324 -> 1364
~ sub_fffffc000001412c -> sub_fffffc0000014154 : 532 -> 536
~ sub_fffffc0000014340 -> sub_fffffc000001436c : 492 -> 500
~ sub_fffffc0000014bac -> sub_fffffc0000014be0 : 512 -> 516
~ sub_fffffc0000031b98 -> sub_fffffc0000031bd0 : 2176 -> 2164
~ sub_fffffc000005063c -> sub_fffffc0000050668 : 324 -> 332
CStrings:
+ "Nov 10 2026 03:26:37"
- "Oct 30 2026 01:16:13"
```
