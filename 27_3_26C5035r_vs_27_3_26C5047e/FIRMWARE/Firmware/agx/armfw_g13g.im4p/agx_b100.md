## agx_b100

> `Firmware/agx/armfw_g13g.im4p/agx_b100`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x41204
+  __TEXT.__text: 0x41260
   __TEXT.__gxf_code: 0x10e4
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x52df8
+  __DATA.__zerofill: 0x53018
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 426
   Symbols:   194
Functions:
~ sub_ffffff8000003350 : 776 -> 808
~ sub_ffffff800000381c -> sub_ffffff800000383c : 4688 -> 4704
~ sub_ffffff800000d40c -> sub_ffffff800000d43c : 528 -> 532
~ sub_ffffff800000d61c -> sub_ffffff800000d650 : 484 -> 496
~ sub_ffffff800000d800 -> sub_ffffff800000d840 : 668 -> 672
~ sub_ffffff800000ddf8 -> sub_ffffff800000de3c : 512 -> 520
~ sub_ffffff800000dff8 -> sub_ffffff800000e044 : 736 -> 740
~ sub_ffffff80000169fc -> sub_ffffff8000016a4c : 1756 -> 1760
~ sub_ffffff8000021090 -> sub_ffffff80000210e4 : 3740 -> 3736
~ sub_ffffff800002537c -> sub_ffffff80000253cc : 2004 -> 2016
CStrings:
+ "Nov 10 2026 03:31:30"
- "Oct 30 2026 01:21:30"
```
