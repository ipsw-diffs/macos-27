## sptm.t6031.release.im4p

> `Firmware/sptm.t6031.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`

```diff

 820.40.24.0.0
-  __TEXT.__cstring: 0x15277
+  __TEXT.__cstring: 0x1532f
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x7b68
   __LATE_CONST.__late_const: 0x8cb40
-  __TEXT_EXEC.__text: 0x5ccf4
+  __TEXT_EXEC.__text: 0x5d034
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 391
   Symbols:   1
-  CStrings:  2475
+  CStrings:  2478
 
Functions:
~ sub_fffffff0270e1cc0 : 5644 -> 6016
~ sub_fffffff0270e35b8 -> sub_fffffff0270e372c : 2724 -> 3168
~ sub_fffffff0270e8058 -> sub_fffffff0270e8388 : 3764 -> 3772
~ sub_fffffff0270e8f0c -> sub_fffffff0270e9244 : 13504 -> 13512
CStrings:
+ "%s: dart %p (%s:%u): Inconsistent unganged clock protection configuration"
+ "(&dart_gapf_ungang_map[state->gapf_ungang_map_index].lock)"
+ "SPTM-820.40.24|2026-10-07:21:08:19.808229|"
+ "sptm_t8110dart_skip_disable_clock_protection_write"
- "SPTM-820.40.24|2026-10-07:22:22:16.682501|"
```
