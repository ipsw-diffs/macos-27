## agx_a000

> `Firmware/agx/armfw_g15c.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x535e4
+  __TEXT.__text: 0x53624
   __TEXT.__gxf_code: 0x105c
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
Functions:
~ sub_fffffc0000002f2c : 1400 -> 1440
~ sub_fffffc0000014840 -> sub_fffffc0000014868 : 532 -> 536
~ sub_fffffc0000014a54 -> sub_fffffc0000014a80 : 492 -> 500
~ sub_fffffc00000152c0 -> sub_fffffc00000152f4 : 512 -> 516
~ sub_fffffc0000032d50 -> sub_fffffc0000032d88 : 2312 -> 2320
CStrings:
+ "Nov 10 2026 03:22:13"
- "Oct 30 2026 01:11:38"
```
