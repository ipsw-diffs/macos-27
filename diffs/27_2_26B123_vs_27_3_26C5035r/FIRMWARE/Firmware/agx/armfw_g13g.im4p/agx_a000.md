## agx_a000

> `Firmware/agx/armfw_g13g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x41030
+  __TEXT.__text: 0x41194
   __TEXT.__gxf_code: 0x10e4
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1d50
-  __TEXT.__cstring: 0x1c79
+  __TEXT.__cstring: 0x1cc3
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x1e8
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 426
   Symbols:   194
-  CStrings:  207
+  CStrings:  208
 
Functions:
~ sub_ffffff8000005d78 : 7016 -> 7040
~ sub_ffffff8000029268 -> sub_ffffff8000029280 : 1836 -> 2132
~ sub_ffffff800002d800 -> sub_ffffff800002d940 : 1992 -> 2020
~ sub_ffffff8000030968 -> sub_ffffff8000030ac4 : 768 -> 776
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:18:08"
- "Oct 14 2026 23:13:14"
```
