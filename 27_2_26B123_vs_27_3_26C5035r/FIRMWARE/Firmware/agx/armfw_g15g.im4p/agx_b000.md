## agx_b000

> `Firmware/agx/armfw_g15g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x550b0
+  __TEXT.__text: 0x55210
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x2438
-  __TEXT.__cstring: 0x25c8
+  __TEXT.__cstring: 0x2612
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 503
   Symbols:   197
-  CStrings:  265
+  CStrings:  266
 
Functions:
~ sub_fffffc00000077a8 : 7872 -> 7896
~ sub_fffffc000003b9d0 -> sub_fffffc000003b9e8 : 1600 -> 1892
~ sub_fffffc000003ecbc -> sub_fffffc000003edf8 : 1716 -> 1744
~ sub_fffffc000004264c -> sub_fffffc00000427a4 : 1212 -> 1220
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:14:49"
- "Oct 14 2026 23:10:16"
```
