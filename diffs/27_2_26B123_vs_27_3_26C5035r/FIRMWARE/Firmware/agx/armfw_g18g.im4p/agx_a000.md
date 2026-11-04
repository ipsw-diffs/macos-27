## agx_a000

> `Firmware/agx/armfw_g18g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3c93c
+  __TEXT.__text: 0x3c9b0
   __TEXT.__gxf_code: 0x4f60
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x2110
+  __TEXT.__const: 0x2118
   __TEXT._rtk_patchbay: 0x23a
   __TEXT._rtk_tunables: 0x7e0
-  __TEXT.__cstring: 0x247d
+  __TEXT.__cstring: 0x24c7
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x20
   __DATA.__gxf_data: 0x80b8

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 404
   Symbols:   169
-  CStrings:  237
+  CStrings:  238
 
Functions:
~ sub_fffffc0000006ef0 : 5212 -> 5236
~ sub_fffffc0000008cb4 -> sub_fffffc0000008ccc : 916 -> 924
~ sub_fffffc000000a0bc -> sub_fffffc000000a0dc : 680 -> 672
~ sub_fffffc000000c3e0 -> sub_fffffc000000c3f8 : 10604 -> 10588
~ sub_fffffc000000ed4c -> sub_fffffc000000ed54 : 1664 -> 1656
~ sub_fffffc000000f3cc : 412 -> 396
~ sub_fffffc000000f568 -> sub_fffffc000000f558 : 1628 -> 1592
~ sub_fffffc000000febc -> sub_fffffc000000fe88 : 9800 -> 9744
~ sub_fffffc000001c97c -> sub_fffffc000001c910 : 3416 -> 3320
~ sub_fffffc00000216a8 -> sub_fffffc00000215dc : 2120 -> 2128
~ sub_fffffc00000277f4 -> sub_fffffc0000027730 : 1760 -> 1788
~ sub_fffffc0000027ed4 -> sub_fffffc0000027e2c : 8192 -> 8176
~ sub_fffffc0000029ed4 -> sub_fffffc0000029e1c : 2204 -> 2504
~ sub_fffffc000003c7f8 -> sub_fffffc000003c86c : 332 -> 324
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:13:26"
- "Oct 14 2026 23:08:46"
```
