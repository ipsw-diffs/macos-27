## agx_b000

> `Firmware/agx/armfw_g16c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x51c8c
+  __TEXT.__text: 0x51f34
   __TEXT.__gxf_code: 0x50c0
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x132c
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x6a0
-  __TEXT.__cstring: 0x2f23
+  __TEXT.__cstring: 0x2f6d
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x20
   __DATA.__gxf_data: 0x8130

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 497
   Symbols:   173
-  CStrings:  305
+  CStrings:  306
 
Functions:
~ sub_fffffc00000058cc : 5304 -> 5328
~ sub_fffffc0000010d4c -> sub_fffffc0000010d64 : 672 -> 680
~ sub_fffffc0000013a00 -> sub_fffffc0000013a20 : 11436 -> 11452
~ sub_fffffc00000166ac -> sub_fffffc00000166dc : 2892 -> 2900
~ sub_fffffc00000171f8 -> sub_fffffc0000017230 : 324 -> 340
~ sub_fffffc000001733c -> sub_fffffc0000017384 : 2056 -> 2100
~ sub_fffffc0000017e74 -> sub_fffffc0000017ee8 : 10156 -> 10272
~ sub_fffffc00000285b4 -> sub_fffffc000002869c : 3012 -> 3116
~ sub_fffffc0000032450 -> sub_fffffc00000325a0 : 2300 -> 2292
~ sub_fffffc0000039718 -> sub_fffffc0000039860 : 1528 -> 1556
~ sub_fffffc0000039d10 -> sub_fffffc0000039e74 : 7664 -> 7680
~ sub_fffffc000003bb00 -> sub_fffffc000003bc74 : 2064 -> 2372
~ sub_fffffc0000051b4c -> sub_fffffc0000051df4 : 328 -> 320
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:16:25"
- "Oct 14 2026 23:11:47"
```
