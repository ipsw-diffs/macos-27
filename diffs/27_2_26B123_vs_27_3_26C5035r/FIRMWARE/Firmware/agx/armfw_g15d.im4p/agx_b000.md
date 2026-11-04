## agx_b000

> `Firmware/agx/armfw_g15d.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x5419c
+  __TEXT.__text: 0x542f0
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x12e8
-  __TEXT.__cstring: 0x2bb2
+  __TEXT.__cstring: 0x2bfc
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
~ sub_fffffc0000039aac -> sub_fffffc0000039ac4 : 1904 -> 2176
~ sub_fffffc000003ca5c -> sub_fffffc000003cb84 : 1860 -> 1888
~ sub_fffffc000004061c -> sub_fffffc0000040760 : 1028 -> 1044
~ sub_fffffc000005405c -> sub_fffffc00000541b0 : 328 -> 320
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:16:39"
- "Oct 14 2026 23:11:51"
```
