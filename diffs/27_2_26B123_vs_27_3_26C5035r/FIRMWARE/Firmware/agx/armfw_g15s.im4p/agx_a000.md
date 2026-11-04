## agx_a000

> `Firmware/agx/armfw_g15s.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x50a58
+  __TEXT.__text: 0x50bac
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1160
-  __TEXT.__cstring: 0x27c1
+  __TEXT.__cstring: 0x280b
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 503
   Symbols:   178
-  CStrings:  277
+  CStrings:  278
 
Functions:
~ sub_fffffc0000007658 : 5864 -> 5888
~ sub_fffffc00000375d4 -> sub_fffffc00000375ec : 1904 -> 2176
~ sub_fffffc000003a590 -> sub_fffffc000003a6b8 : 1860 -> 1888
~ sub_fffffc000003d95c -> sub_fffffc000003daa0 : 1028 -> 1044
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:11:33"
- "Oct 14 2026 23:07:07"
```
