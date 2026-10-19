## sptm.t8132.release.im4p

> `Firmware/sptm.t8132.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`

```diff

 820.40.24.0.0
-  __TEXT.__cstring: 0x15bac
+  __TEXT.__cstring: 0x15c64
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x7c00
   __LATE_CONST.__late_const: 0x8c8f0
-  __TEXT_EXEC.__text: 0x6004c
+  __TEXT_EXEC.__text: 0x603b8
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 401
   Symbols:   1
-  CStrings:  2550
+  CStrings:  2553
 
Functions:
~ sub_fffffff0270e2da4 : 6544 -> 6968
~ sub_fffffff0270e4cb0 -> sub_fffffff0270e4e58 : 2920 -> 3356
~ sub_fffffff0270e990c -> sub_fffffff0270e9c68 : 3764 -> 3772
~ sub_fffffff0270ea7c0 -> sub_fffffff0270eab24 : 13504 -> 13512
~ sub_fffffff027114008 -> sub_fffffff027114374 : 72 -> 76
CStrings:
+ "%s: dart %p (%s:%u): Inconsistent unganged clock protection configuration"
+ "(&dart_gapf_ungang_map[state->gapf_ungang_map_index].lock)"
+ "SPTM-820.40.24|2026-10-07:21:08:19.808229|"
+ "sptm_t8110dart_skip_disable_clock_protection_write"
- "SPTM-820.40.24|2026-10-07:22:22:16.682501|"
```
