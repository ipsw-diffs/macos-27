## sptm.t8112.release.im4p

> `Firmware/sptm.t8112.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`

```diff

 820.40.24.0.0
-  __TEXT.__cstring: 0x15230
+  __TEXT.__cstring: 0x152e8
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x7b00
   __LATE_CONST.__late_const: 0x8c840
-  __TEXT_EXEC.__text: 0x5bb80
+  __TEXT_EXEC.__text: 0x5bec0
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 388
   Symbols:   1
-  CStrings:  2470
+  CStrings:  2473
 
Functions:
~ sub_fffffff0270e0754 : 5644 -> 6016
~ sub_fffffff0270e204c -> sub_fffffff0270e21c0 : 2724 -> 3168
~ sub_fffffff0270e6aec -> sub_fffffff0270e6e1c : 3764 -> 3772
~ sub_fffffff0270e79a0 -> sub_fffffff0270e7cd8 : 13504 -> 13512
CStrings:
+ "%s: dart %p (%s:%u): Inconsistent unganged clock protection configuration"
+ "(&dart_gapf_ungang_map[state->gapf_ungang_map_index].lock)"
+ "SPTM-820.40.24|2026-10-07:21:08:19.808229|"
+ "sptm_t8110dart_skip_disable_clock_protection_write"
- "SPTM-820.40.24|2026-10-07:22:22:16.682501|"
```
