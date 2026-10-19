## sptm.t6020.release.im4p

> `Firmware/sptm.t6020.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`

```diff

 820.40.24.0.0
-  __TEXT.__cstring: 0x15318
+  __TEXT.__cstring: 0x153d0
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x7b68
   __LATE_CONST.__late_const: 0x8ca50
-  __TEXT_EXEC.__text: 0x5c488
+  __TEXT_EXEC.__text: 0x5c7c8
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 394
   Symbols:   1
-  CStrings:  2481
+  CStrings:  2484
 
Functions:
~ sub_fffffff0270e1274 : 5644 -> 6016
~ sub_fffffff0270e2b6c -> sub_fffffff0270e2ce0 : 2724 -> 3168
~ sub_fffffff0270e760c -> sub_fffffff0270e793c : 3764 -> 3772
~ sub_fffffff0270e84c0 -> sub_fffffff0270e87f8 : 13504 -> 13512
CStrings:
+ "%s: dart %p (%s:%u): Inconsistent unganged clock protection configuration"
+ "(&dart_gapf_ungang_map[state->gapf_ungang_map_index].lock)"
+ "SPTM-820.40.24|2026-10-07:21:08:19.808229|"
+ "sptm_t8110dart_skip_disable_clock_protection_write"
- "SPTM-820.40.24|2026-10-07:22:22:16.682501|"
```
