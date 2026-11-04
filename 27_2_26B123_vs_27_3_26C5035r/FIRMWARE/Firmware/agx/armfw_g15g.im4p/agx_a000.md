## agx_a000

> `Firmware/agx/armfw_g15g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4f578
+  __TEXT.__text: 0x4f6d8
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x2428
-  __TEXT.__cstring: 0x2424
+  __TEXT.__cstring: 0x246e
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 490
   Symbols:   197
-  CStrings:  257
+  CStrings:  258
 
Functions:
~ sub_fffffc0000006b6c : 7852 -> 7876
~ sub_fffffc0000035ee8 -> sub_fffffc0000035f00 : 1600 -> 1892
~ sub_fffffc00000394e8 -> sub_fffffc0000039624 : 1716 -> 1744
~ sub_fffffc000003ce04 -> sub_fffffc000003cf5c : 1212 -> 1220
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:10:47"
- "Oct 14 2026 23:06:18"
```
