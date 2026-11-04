## agx_b000

> `Firmware/agx/armfw_g14s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4e670
+  __TEXT.__text: 0x4e7e0
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1f00
-  __TEXT.__cstring: 0x236b
+  __TEXT.__cstring: 0x23b5
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 509
   Symbols:   196
-  CStrings:  248
+  CStrings:  249
 
Functions:
~ sub_ffffff800000644c : 5772 -> 5796
~ sub_ffffff8000034b34 -> sub_ffffff8000034b4c : 2096 -> 2396
~ sub_ffffff8000037b50 -> sub_ffffff8000037c94 : 2592 -> 2620
~ sub_ffffff800003b77c -> sub_ffffff800003b8dc : 1028 -> 1044
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:14:50"
- "Oct 14 2026 23:10:03"
```
