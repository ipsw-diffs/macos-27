## sptm.t6050.release.im4p

> `Firmware/sptm.t6050.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`

```diff

 820.40.24.0.0
-  __TEXT.__cstring: 0x160e1
+  __TEXT.__cstring: 0x16199
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x7c00
   __LATE_CONST.__late_const: 0x8cc50
-  __TEXT_EXEC.__text: 0x615f0
+  __TEXT_EXEC.__text: 0x61914
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 408
   Symbols:   1
-  CStrings:  2582
+  CStrings:  2585
 
Functions:
~ sub_fffffff0270e327c : 6620 -> 6992
~ sub_fffffff0270e5204 -> sub_fffffff0270e5378 : 2956 -> 3372
~ sub_fffffff0270e9e24 -> sub_fffffff0270ea138 : 3764 -> 3772
~ sub_fffffff0270eacd8 -> sub_fffffff0270eaff4 : 13496 -> 13504
~ sub_fffffff0271155ac -> sub_fffffff0271158d0 : 68 -> 80
CStrings:
+ "%s: dart %p (%s:%u): Inconsistent unganged clock protection configuration"
+ "(&dart_gapf_ungang_map[state->gapf_ungang_map_index].lock)"
+ "SPTM-820.40.24|2026-10-07:21:08:19.808229|"
+ "sptm_t8110dart_skip_disable_clock_protection_write"
- "SPTM-820.40.24|2026-10-07:22:22:16.682501|"
```
