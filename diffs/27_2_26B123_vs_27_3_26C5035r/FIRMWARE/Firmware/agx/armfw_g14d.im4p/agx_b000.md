## agx_b000

> `Firmware/agx/armfw_g14d.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4f14c
+  __TEXT.__text: 0x4f2bc
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1f38
-  __TEXT.__cstring: 0x236b
+  __TEXT.__cstring: 0x23b5
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__init_offsets: 0x0

   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 510
   Symbols:   196
-  CStrings:  248
+  CStrings:  249
 
Functions:
~ sub_ffffff80000065bc : 5564 -> 5588
~ sub_ffffff80000355e0 -> sub_ffffff80000355f8 : 2096 -> 2396
~ sub_ffffff80000385fc -> sub_ffffff8000038740 : 2592 -> 2620
~ sub_ffffff800003c258 -> sub_ffffff800003c3b8 : 1028 -> 1044
CStrings:
+ "!!! Error: GPU did not reach forced idle within %ums of the sleep request"
+ "Oct 30 2026 01:15:09"
- "Oct 14 2026 23:10:18"
```
