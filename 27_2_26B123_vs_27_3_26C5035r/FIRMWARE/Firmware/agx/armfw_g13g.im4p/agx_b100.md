## agx_b100

> `Firmware/agx/armfw_g13g.im4p/agx_b100`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x410a0
+  __TEXT.__text: 0x41204
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
~ sub_ffffff80000292d8 -> sub_ffffff80000292f0 : 1836 -> 2132
~ sub_ffffff800002d870 -> sub_ffffff800002d9b0 : 1992 -> 2020
~ sub_ffffff80000309d8 -> sub_ffffff8000030b34 : 768 -> 776
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:21:30"
- "Oct 14 2026 23:16:33"
```
