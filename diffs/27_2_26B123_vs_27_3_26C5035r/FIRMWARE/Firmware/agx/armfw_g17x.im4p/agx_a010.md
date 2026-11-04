## agx_a010

> `Firmware/agx/armfw_g17x.im4p/agx_a010`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3cdec
+  __TEXT.__text: 0x3ce28
   __TEXT.__gxf_code: 0x50a0
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1204
+  __TEXT.__const: 0x120c
   __TEXT._rtk_tunables: 0x740
   __TEXT._rtk_patchbay: 0x231
-  __TEXT.__cstring: 0x21ff
+  __TEXT.__cstring: 0x2249
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x24
   __DATA.__gxf_data: 0x8130

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 414
   Symbols:   175
-  CStrings:  231
+  CStrings:  232
 
Functions:
~ sub_fffffc0000006780 : 5244 -> 5268
~ sub_fffffc0000008694 -> sub_fffffc00000086ac : 916 -> 924
~ sub_fffffc0000009ae0 -> sub_fffffc0000009b00 : 680 -> 672
~ sub_fffffc000000bfc0 -> sub_fffffc000000bfd8 : 10700 -> 10656
~ sub_fffffc000000e98c -> sub_fffffc000000e978 : 2272 -> 2264
~ sub_fffffc000000f26c -> sub_fffffc000000f250 : 340 -> 324
~ sub_fffffc000000f3c0 -> sub_fffffc000000f394 : 1588 -> 1544
~ sub_fffffc000000fcf0 -> sub_fffffc000000fc98 : 9824 -> 9756
~ sub_fffffc000001c5a0 -> sub_fffffc000001c504 : 3240 -> 3136
~ sub_fffffc0000021548 -> sub_fffffc0000021444 : 2144 -> 2152
~ sub_fffffc0000027104 -> sub_fffffc0000027008 : 1784 -> 1812
~ sub_fffffc00000277fc -> sub_fffffc000002771c : 8196 -> 8180
~ sub_fffffc0000029800 -> sub_fffffc0000029710 : 2124 -> 2424
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:13:01"
- "Oct 14 2026 23:08:27"
```
