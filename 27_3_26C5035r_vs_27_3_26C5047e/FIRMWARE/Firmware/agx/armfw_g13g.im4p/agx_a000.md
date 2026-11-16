## agx_a000

> `Firmware/agx/armfw_g13g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x41194
+  __TEXT.__text: 0x411f0
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
~ sub_ffffff800000d3b4 -> sub_ffffff800000d3e4 : 528 -> 532
~ sub_ffffff800000d5c4 -> sub_ffffff800000d5f8 : 484 -> 496
~ sub_ffffff800000d7a8 -> sub_ffffff800000d7e8 : 668 -> 672
~ sub_ffffff800000dda0 -> sub_ffffff800000dde4 : 512 -> 520
~ sub_ffffff800000dfa0 -> sub_ffffff800000dfec : 736 -> 740
~ sub_ffffff80000169a4 -> sub_ffffff80000169f4 : 1756 -> 1760
~ sub_ffffff8000021038 -> sub_ffffff800002108c : 3716 -> 3712
~ sub_ffffff800002530c -> sub_ffffff800002535c : 2004 -> 2016
CStrings:
+ "Nov 10 2026 03:28:18"
- "Oct 30 2026 01:18:08"
```
