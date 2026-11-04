## agx_b000

> `Firmware/agx/armfw_g15c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x5304c
+  __TEXT.__text: 0x531a0
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x11f8
-  __TEXT.__cstring: 0x2bb2
+  __TEXT.__cstring: 0x2bfc
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 519
   Symbols:   179
-  CStrings:  293
+  CStrings:  294
 
Functions:
~ sub_fffffc000000772c : 5940 -> 5964
~ sub_fffffc0000038a58 -> sub_fffffc0000038a70 : 1904 -> 2176
~ sub_fffffc000003ba08 -> sub_fffffc000003bb30 : 1860 -> 1888
~ sub_fffffc000003f4cc -> sub_fffffc000003f610 : 1028 -> 1044
~ sub_fffffc0000052f0c -> sub_fffffc0000053060 : 328 -> 320
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:16:22"
- "Oct 14 2026 23:11:42"
```
