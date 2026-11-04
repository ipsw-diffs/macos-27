## agx_a000

> `Firmware/agx/armfw_g15d.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x54080
+  __TEXT.__text: 0x541d4
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x12e8
-  __TEXT.__cstring: 0x2bcf
+  __TEXT.__cstring: 0x2c19
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 522
   Symbols:   179
-  CStrings:  293
+  CStrings:  294
 
Functions:
~ sub_fffffc000000786c : 5624 -> 5648
~ sub_fffffc0000039990 -> sub_fffffc00000399a8 : 1904 -> 2176
~ sub_fffffc000003c940 -> sub_fffffc000003ca68 : 1860 -> 1888
~ sub_fffffc0000040500 -> sub_fffffc0000040644 : 1028 -> 1044
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:11:39"
- "Oct 14 2026 23:07:10"
```
