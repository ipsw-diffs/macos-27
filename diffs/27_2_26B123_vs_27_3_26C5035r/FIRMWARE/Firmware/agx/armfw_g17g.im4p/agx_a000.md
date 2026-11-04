## agx_a000

> `Firmware/agx/armfw_g17g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3d880
+  __TEXT.__text: 0x3d8dc
   __TEXT.__gxf_code: 0x5130
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x10b4
+  __TEXT.__const: 0x10bc
   __TEXT._rtk_tunables: 0x740
   __TEXT._rtk_patchbay: 0x231
-  __TEXT.__cstring: 0x2370
+  __TEXT.__cstring: 0x23ba
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x24
   __DATA.__gxf_data: 0x8160

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 417
   Symbols:   173
-  CStrings:  236
+  CStrings:  237
 
Functions:
~ sub_fffffc00000061ac : 5320 -> 5344
~ sub_fffffc0000008854 -> sub_fffffc000000886c : 952 -> 960
~ sub_fffffc0000009e3c -> sub_fffffc0000009e5c : 680 -> 672
~ sub_fffffc000000c31c -> sub_fffffc000000c334 : 11936 -> 11920
~ sub_fffffc000000f1bc -> sub_fffffc000000f1c4 : 2284 -> 2276
~ sub_fffffc000000faa8 : 340 -> 324
~ sub_fffffc000000fbfc -> sub_fffffc000000fbec : 1600 -> 1556
~ sub_fffffc0000010580 -> sub_fffffc0000010544 : 10020 -> 9952
~ sub_fffffc000001c814 -> sub_fffffc000001c794 : 3240 -> 3136
~ sub_fffffc0000022260 -> sub_fffffc0000022178 : 2400 -> 2408
~ sub_fffffc0000027a54 -> sub_fffffc0000027974 : 1848 -> 1876
~ sub_fffffc000002818c -> sub_fffffc00000280c8 : 8792 -> 8776
~ sub_fffffc000002a3e4 -> sub_fffffc000002a310 : 2216 -> 2520
~ sub_fffffc000003d73c -> sub_fffffc000003d798 : 324 -> 332
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:12:53"
- "Oct 14 2026 23:08:17"
```
